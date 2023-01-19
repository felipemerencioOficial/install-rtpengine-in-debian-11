# Install RTPEngine in Debian 11

1. Add the text down in the last line in the file /etc/apt/sources.list.  
ˋˋˋ
	deb http://ftp.de.debian.org/debian sid main 
ˋˋˋ
	
2. Install aptitude.  
ˋˋˋ
	apt install aptitude -y
ˋˋˋ
	
3. Install rtpengine using the aptitude.  
ˋˋˋ
	aptitude install rtpengine -y
ˋˋˋ
	
4. Check instalation RTPEngine.  
ˋˋˋ
	systemctl status rtpengine.service
ˋˋˋ