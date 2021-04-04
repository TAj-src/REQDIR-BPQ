# REQDIR-BPQ

Request directory listing automation script for LibBPQ

Place in a script directory below the BPQ install ( e.g. /home/pi/linbpq/scripts )

Edit the settings at the top of the file

Add a cron to crontab e.g.


Check for REQDIR msgs
0 1 * * * /home/pi/linbpq/scrips/reqdir.sh > /dev/null 2>&1



Replace /dev/null if you want to log the output (e.g. /tmp/reqdir.log)
