# Pi-JDK-Setup
```bash
cd ~/Downloads/
wget https://github.com/adoptium/temurin17-binaries/releases/download/jdk-17.0.1%2B12/OpenJDK17U-jdk_arm_linux_hotspot_17.0.1_12.tar.gz
mkdir /opt/jdk
sudo tar -xf OpenJDK17U-jdk_arm_linux_hotspot_17.0.1_12.tar.gz -C /opt/jdk
export PATH=/opt/jdk/jdk-17.0.1+12/bin:$PATH
java -version
```
