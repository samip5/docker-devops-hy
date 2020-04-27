The password was basics.

The actual workflow as I'm using a Raspberry Pi 4, which is aarch64 
arch, I had to rebuild the image on RPi4, so clone the source repository 
and `docker build . -t devopsdockeruh/pull_exercise'.

Otherwise it would just yell exec format error, as that image is only for amd64, which it shouldn't be if you advertise to use for example an Raspberry Pi.

Command output: 
```
Give me the password: basics You found the correct 
password. Secret message is: "This is the secret message"
```
