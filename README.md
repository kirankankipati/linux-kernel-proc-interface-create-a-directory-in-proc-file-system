Sample Linux Kernel Module to create a directory in /proc file-system as discussed in my YouTube video. /proc is one of the most popular kernel to user-space interface which you can leverage to add an interface to your Kernel code such as Kernel modules, Kernel Device Drivers, etc. Personally I prefer /proc interface than other alternatives such as /sysfs, ioctl() and so on for my personal Kernel modules/stack.

Disclaimer: Of course if you just download and try this source on to any modern Linux distro comes with respective kernel, it may not work. Since as I always say in my videos, Linux Kernel is every evolving constantly changing source-code. Its nothing like user-space programming. So this example source which I wrote and discussed in the video is compatible for that version of the kernel. So kindly refer my article (link below) for further instructions, porting guidelines, and so on.

For more details kindly refer: my Website article - The Linux Channel - https://thelinuxchannel.org/2023/10/linux-kernel-proc-interface-create-a-directory-in-proc-file-system/

For all articles related to Linux Kernel /proc interface - https://thelinuxchannel.org/category/linux-kernel-programming/linux-kernel-proc-interface/

proc_example.c - discussed in my YouTube video - https://youtu.be/V1i4iwhVdW4

I also conduct sessions/classes on Systems and Network Software Programming, Linux Kernel Programming and Architecture. Kindly follow the link below: https://thelinuxchannel.org/courses/

If you have any queries or anything to discuss further on Linux Kernel Programming and writing Kernel modules kindly feel free to contact me. Kindly follow the link below: https://thelinuxchannel.org/contact/

