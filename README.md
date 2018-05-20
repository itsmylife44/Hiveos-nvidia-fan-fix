# Hiveos-nvidia-fan-fix
Fixed the nvidia fan in hiveos


# ethos-nvidia-fan fix

# Name:             Autofan script for NVIDIA Cards in HiveOS
# Preparation:      Setting up script sheduled run from CRON (Crontab)
#                    1) cd /home/user/
#                    2) git clone https://github.com/itsmylife44/Hiveos-nvidia-fan-fix.git
                     3 ) cd Hiveos-nvidia-fan-fix
#                    4) chmod u+x autofan.sh.
# Sheduled-Start:    5) Edit crontab ( nano /var/spool/cron/crontabs/root  and put  */5 * * * * /home/user/script/autofan.sh
#                       This command will start script every 5 minutes, if you want to change - correct "*/5" value.
# Additional Info:  DELAY is not applicable unless the script is set-up for single running in cycle

