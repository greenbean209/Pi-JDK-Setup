# Pi-JDK-Setup
## Download and Install jdk 17.0.1
```bash
cd ~/Downloads/
wget https://github.com/adoptium/temurin17-binaries/releases/download/jdk-17.0.1%2B12/OpenJDK17U-jdk_arm_linux_hotspot_17.0.1_12.tar.gz
mkdir /opt/jdk
sudo tar -xf OpenJDK17U-jdk_arm_linux_hotspot_17.0.1_12.tar.gz -C /opt/jdk
export PATH=/opt/jdk/jdk-17.0.1+12/bin:$PATH
java -version
```
## Download and Install Java FX SDK
```
cd ~/Downloads/
wget https://download2.gluonhq.com/openjfx/17.0.1/openjfx-17.0.1_linux-arm32_bin-sdk.zip
```

## Setup Windows Dev Env
Setup Eclipse Adoptium JDK 17
Setup Eclipse IDE
Setup Maven
Download Maven
Extract Zip to "C:\Program Files\"
Edit Environment Variables
Add User Variable JAVA_HOME "C:\Program Files\Eclipse Adoptium\jdk-17.0.1.12-hotspot"
Add User Variable MAVEN_HOME "C:\Program Files\apache-maven-3.8.4"
Add User Variable M2_HOME "C:\Program Files\apache-maven-3.8.4"
Add System Path Variable "C:\Program Files\apache-maven-3.8.4\bin\"
