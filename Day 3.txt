Jenkins:
It is continuous integration tool .
It is open source automation tool built on java.Since it is built on Java jenkins is portable to all the major service out there in the market.
It supports 1800+ plugings that supports .it has wonderful community support and user support.absolutly free of cost and easy to install.
steps to install Jenkins
jenkin.io download
LTS is Long Term Services used  for production
installed jenkins on ubuntu by giving the commands
This is the Debian package repository of Jenkins to automate installation and upgrade. To use this repository, first add the key to your system:
    curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
    /usr/share/keyrings/jenkins-keyring.asc > /dev/null
Then add a Jenkins apt repository entry:
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
    https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
    /etc/apt/sources.list.d/jenkins.list > /dev/null

Sudo apt-get update  this commad is for to update the metadata.

after that run the command 
sudo apt-get install fontconfig openjdk-11-jre

