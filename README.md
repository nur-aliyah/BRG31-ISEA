Lab 4

1) - Create test files and directories in `/home/ubuntu/Documents`. / /: 
   - Write a Bash script to recursively copy `/Documents` to `/backup`:
   - Zip the backup with a filename based on current date using `date` and `zip`:
   - Move the final backup zip into `/home/ubuntu` for easy access:
   - Grant execute permissions: `chmod 777 testscript`:
   - Move script to `/usr/bin/` and test system-wide execution: 
   - Schedule cron to run the script hourly: edit `/etc/crontab`:
   - Add an SCP command to transfer the backup to a cloud instance:
   - Test key-based SSH access and accept remote host fingerprints if prompted:
  
2) Install Additional Server: NTP Server (Time Synchronisation)
   <img width="1024" height="768" alt="additionalserver" src="https://github.com/user-attachments/assets/c94cb9ce-6226-49d0-bc17-9ad2af400718" />

3) Learning points:
   - cron runs with a minimal environment and restricted PATH rather than an interactive working directory; absolute paths e.g. /home/ubuntu/Documents, /usr/bin/testscript prevent missing-file or command-not-found errors
   - transferring archives off-site via scp protects data against local VM failure, disk corruption, or accidental deletion while simplifying recovery from another host is one of the benefit of cloud exporting backups
   - manual execution runs interactively with full user environment variables and terminal feedback while cron runs non-interactively in the background on a schedule without terminal input or immediate on-screen output
   - if a remote host's SSH fingerprint is not verified and stored in ~/.ssh/known_hosts beforehand, automated scp transfers under cron fail or hang waiting for an interactive yes/no confirmation
   - provides immediate situational awareness on system updates, active services and security reminders when users connect




