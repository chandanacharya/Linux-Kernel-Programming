obj-m += Task01.o
all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules
clean:
	make -C /lib/moduels/$(shell uname -)/build M=$(PWD) clean