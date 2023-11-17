# PhoneCam.sh

# Hawk Buckman - Long Draw Studio - Nov 2023

# This shell script is used in conjunction with a FTP/SFTP program to upload phone images directly to a 
# recieving directory where this script will process it by resizing it, deleting the original .JPG file 
# and copy the new file to /home/user/public_html/remotepics/ where it can be called via <a href> anywhere
# into your website.

# You need a FTP/SFTP app on your mobile device that can access your photos. Check out FTPManger on Apple
# and of course a webhost that allows SFTP or FTP.
#
# Run the script in CRON for your choice of time for processing.
#
# Example: https://www.hawkbuckman.com/phone-cam/
#
# Happy coding!
