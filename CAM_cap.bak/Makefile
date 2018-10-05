export ARCH = arm
export CROSS_COMPILE=arm-poky-linux-gnueabi-
KDIR	=/root/IMX6Q0713/kernel_imx/include/	
export PATH=/opt/poky/1.5.1/sysroots/x86_64-pokysdk-linux/usr/bin/arm-poky-linux-gnueabi/:/opt/poky/1.5.1/sysroots/cortexa9hf-vfp-neon-poky-linux-gnueabi/usr/include/:$PATH

INCDIR  = 	/opt/poky/1.5.1/sysroots/x86_64-pokysdk-linux/usr/include/
MDIR	=  ./include/
all:
	arm-poky-linux-gnueabi-gcc -I$(MDIR) -o testapp mxc_v4l2_overlay.c
	#arm-poky-linux-gnueabi-gcc -I$(MDIR) -o testapp test.c


clean:
	rm testapp





