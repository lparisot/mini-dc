## Our Datacenter :)

This project is part of the Coursera "Cloud Networking" cours. It contains only the source code of the controller.

Using a network emulator called Mininet (http://mininet.org/), we will emulating a datacenter.

The datacenter topology will consist of two levels of switches. The top level are called core switches and the bottom are called edge switches.

Each core switch is connected to every edge switch.

We will have also 2 or more hosts connected to each edge switch.

Switches and hosts are connected by links and on each switch is a port for each link.

We will be emulating a software-defined network with a controller which connects to all switches. On this controller, we'll be running an open source controller called Ryu (https://osrg.github.io/ryu/).
