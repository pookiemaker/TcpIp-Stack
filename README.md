## TcpIp-Stack
### Basic Links
* http://www.drdobbs.com/inside-the-uip-stack/184405971
* 
### Basic Concepts
* Layer 2 routing based on MAC address only
* MAC addresses not preserved in routing
* 

### Basic small stacks available exerpt from http://www.drdobbs.com/inside-the-uip-stack/184405971
* http://www.sics.se/~adam/lwip/ lwip. The "lightweight IP" stack is a simplified but full-scale TCP/IP implementation. lwIP is designed to be run in a multithreaded system with applications executing in concurrent threads; however, it can also be implemented on a system with no real-time operating system (RTOS). The protocols include Internet Control Message Protocol (ICMP), Dynamic Host Configuration Protocol (DHCP), Address Resolution Protocol (ARP), and User Datagram Protocol (UDP). It provides support for multiple local network interfaces and is flexible enough to let it be easily used on a wide variety of devices and scaled to fit different resource requirements.
*http://www.opentcp.org/ OpenTCP. Tailored to 8- and 16-bit microcontrollers, OpenTCP incorporates the ICMP, DHCP, BOOTP (Bootstrap Protocol), ARP, and UDP protocols. There are also several applications included with OpenTCP, such as a Trivial File Transfer Protocol (TFTP) server, a Post Office Protocol Version 3 (POP3) client to retrieve e-mail, Simple Mail Transfer Protocol (SMTP) support to send e-mail, and a Hypertext Transfer Protocol (HTTP) server for web-based access.
* http://www.unusualresearch.com/tinytcp/tinytcp.htm TinyTCP. TinyTCP is designed to be modular and only include the software required by the system. For example, different protocols can be compiled in/out based on configuration. It provides a BSD-compatible socket library and includes the ARP, ICMP, UDP, DHCP, BOOTP, and Internet Group Management Protocol (IGMP) protocols.
* http://ucip.sourceforge.net/ uC/IP. Pronounced "mew-kip," uC/IP is designed for microcontrollers and based on BSD. Intended to be used with the uC/OS RTOS. Protocol support includes ICMP and Point-to-Point Protocol (PPP).
*http://www.sics.se/~adam/uip/ uIP. The "micro IP" stack is designed to incorporate only the absolute minimal set of components necessary for a full TCP/IP stack. There is support for only a single network interface. Application examples included with uIP are SMTP for sending e-mail, telnet server/client, an HTTP server and web client, and Domain Name System (DNS) resolution.

