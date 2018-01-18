# ubuntu_customization
script for automatic image build and install ubuntu on VM for testing
#unpack_iso14.sh
unpack base image
#pack_iso14.sh
Requriments
1)unpacked image(dir iso)
2)VirtualBox configured VM

When executed
1)Delete previous version of image
2)Shut down VM
3)Make image
4)Mount image to VM
5)Start VM
6)In preseed file i setup auto shutdown after install,so wait for VM power off(OS installed and shutdown)
7)Unmount install image
8)Start VM
