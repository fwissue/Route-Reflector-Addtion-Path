# Route-Reflector-Addtion-Path
<br />
in iBGP route-reflector will only advertise best route in normal situation, RFC 7911 changed that. You could have redundant paths
<br /> 
For fast converge, need to enable ip bgp fast-external-fallover permit on bgp link between R2<->R5 and R1<->R5

![test image](rr-addition%20path.drawio.pdf)
