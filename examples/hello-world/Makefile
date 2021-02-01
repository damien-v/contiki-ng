CONTIKI_PROJECT = hello-world
all: $(CONTIKI_PROJECT)

MODULES += os/services/shell
#network
MAKE_MAC = MAKE_MAC_CSMA
MAKE_ROUTING = MAKE_ROUTING_RPL_LITE

CONTIKI = ../..
include $(CONTIKI)/Makefile.include
