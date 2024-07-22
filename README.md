# Install the Jenkins Server and Configuration of the Jenkins:
# System Requirements:
   1. OS: RHEL
   2. CPU Cores: 2
   3. RAM: 4 GB
   4. HD: 10 GB
   
## Pre-Requisites:

	1. Java:
		sudo su
		yum install java-17* -y
		yum install wget -y
		
	2. Download Jenkins Jar file:
		sudo su
		cd /opt
		wget https://updates.jenkins.io/latest/jenkins.war
	3. Run the Jar file:
		java -jar jenkins.war




