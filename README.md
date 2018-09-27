# yoink

~~~
usage: yoink [-h] [-i INTERFACE] [-l LINKLOCAL] [-m MAC] [-t TARGET] [-v]
             [-w WRITE]

yoink - Send unsolicited Neighbor Advertisements or gratuitous ARP

optional arguments:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface INTERFACE
                        src interface
  -l LINKLOCAL, --linklocal LINKLOCAL
                        src link-local IP
  -m MAC, --mac MAC     src MAC
  -t TARGET, --target TARGET
                        target IP
  -v, --verbose         Verbose mode
  -w WRITE, --write WRITE
                        Write pcap file instead of sending packets out the
                        wire
~~~

### TODO:

* GARP support
* link-local / MAC detection
