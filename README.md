# RPi-3B
Extra Points? Yes, it's possible to earn a round 5.0 + extra points in this lab. Congrats, this means that you're in an unusual path. Are you capable to run a native Raspberry Pi 3B+ Machine using QEMU? I'll provide you the necessary files, but running the system is quite different. Clues: RPI3B is using an x64 ARM, so use qemu-system-aarch64 command. What is the correct processor/baseboard platform? it's not ARM Versatile, check the config files and you may figure it out. Everything you need is here... Also, you need to resize the QCOW2 system image to a usable size, for example 8GB or 16GB. Use the commands wisely.
