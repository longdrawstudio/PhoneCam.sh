This shell script is used in conjunction with an FTP/SFTP program to upload phone images directly to a 
receiving directory where this script will process it by resizing it and deleting the original. JPG file 
and copy the new file to /home/user/public_html/remotepics/ where it can be called via <a href> anywhere
on your website.

You need an FTP/SFTP app to access your photos on your mobile device. Check out FTPManger on Apple
and of course, a webhost that allows SFTP or FTP.

Run the script in CRON for your choice of time processing.
