#Operating Systems

Even so, the way we use it today is definitely new. The main idea is that a
VMM (Virtual Machine Monitor) creates the illusion of multiple (virtual) machines
on the same physical hardware. A VMM is also known as a hypervisor. As
discussed in Sec. 1.7.5, we distinguish between type 1 hypervisors which run on
the bare metal, and type 2 hypervisors that may make use of all the wonderful services
and abstractions offered by an underlying operating system. Either way, virtualization
allows a single computer to host multiple virtual machines, each potentially
running a completely different operating system.

In fact, the ability to run at the same time applications that use
different operating systems is a big argument in favor of virtual machines