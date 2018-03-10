# install_java_ubuntu

wget https://raw.githubusercontent.com/Shahedalam/install_java_ubuntu/master/code.sh

chmod +x code.sh

./code.sh

#copy and past this code in ssh and follow below instruction



 sudo update-alternatives --config java

There is only one alternative in link group java (providing /usr/bin/java): /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java

 sudo nano /etc/environment
 
 JAVA_HOME="/usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java"
 
 Ctrl + X and save
 
 sudo reboot

Complete

Check if install is ok 

echo $JAVA_HOME

if show the path its ok or try again
