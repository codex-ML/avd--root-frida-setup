# avd--root-frida-setup

install android studio
start AVD 


root avd using rootAVD

adb push frida-server /data/local/tmp/

to fix Selinux provlem :- 
adb shell "su -c setenforce 0"

adb shell "su -c /data/local/tmp/frida-server-xx.xx.xx-android-xxx &"


