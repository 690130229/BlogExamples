obj-m += alice_domU.o

all:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) modules

clean:
	make -C /lib/modules/$(shell uname -r)/build M=$(PWD) clean

all-xen:
	make -C /lib/modules/2.6.24-29-xen/build M=$(PWD) modules
clean-xen:
	make -C /lib/modules/2.6.24-29-xen/build M=$(PWD) clean  
