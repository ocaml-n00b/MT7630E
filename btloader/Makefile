obj-m := mt76xx.o

KDIR ?= /lib/modules/`uname -r`/build

all:
	$(MAKE) -fno-pie -C $(KDIR) M=$(PWD) modules
clean:
	$(MAKE) -C $(KDIR) M=$(PWD) clean
