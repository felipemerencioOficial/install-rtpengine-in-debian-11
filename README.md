# Install RTPEngine in Debian 11

1. Add the text down in the last line in the file /etc/apt/sources.list.  
´´
	deb http://ftp.de.debian.org/debian sid main 
´´
	
2. Install aptitude.  
´´
	apt install aptitude -y
´´
	
3. Install rtpengine using the aptitude.  
´´
	aptitude install rtpengine -y
´´
	
4. Check instalation RTPEngine.  
´´
	systemctl status rtpengine.service
´´