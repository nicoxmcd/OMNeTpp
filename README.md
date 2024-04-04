# OMNeT
For the class CPE 345 - Modeling and Simulation, we utilize the OMNeT ++ IDE, which is based on the Eclipse platform. This software is for editing and building simulations. The network topology is specified using the NED language, which is made up of simple and compound models, channels, gates, etc. The .ned files are translated into C++ code by the NEDC compiler, then compiled by the C++ compiler and linked to the simulation executable.

### Classwork 8
Implementing a simple example with three nodes in the network description. As part of the assignment, we also enchance the channel parameters by adding a delay of 100 ms on all connections.  
![3 Nodes](https://github.com/nicomcd/OMNeT/blob/main/src/Classwork8.png)

### Classwork 9
ARQ (*automatic repeat request*) is a stop and wait protocol. This protocol helps to ensure transmission reliability.If the link has errors, the receiving node needs to detect errors and confirm with an ACK packet that the current packet has been received. The source node does not transmit the next packet until an ACK has been received for the previous one. After a specific time of not receiving an ACK, the source times out and resends the packet. 
For this assignment, we ignore statistics and will abstract channel errors.
![myARQ1](https://github.com/nicomcd/OMNeT/blob/main/src/Classwork9.png)
