# CSE-310-Pinger
**I changed the source code to print "request timeout" instead of returning it.
To run my project I used the command: sudo python sample_pinger.py <destination>

First I tested my client by sending packets to local host: 127.0.0.1

![ 127.0.0.1 .png](..%2F..%2FDesktop%2F%20127.0.0.1%20.png)
![127.0.0.1.png]( /venv/127.0.0.1.png "Optional title")

Next I tested by sending packet to stonybrook.edu
![stonybrook.edu.png](..%2F..%2FDesktop%2Fstonybrook.edu.png)

Then the three root servers I used were:
1) WIDE, Project, Tokyo
![Root Server 202.12.27.33 in Tokyo.png](..%2F..%2FDesktop%2FRoot%20Server%20202.12.27.33%20in%20Tokyo.png)

2) RIPE, London
![Root Server 193.0.14.129 in London.png](..%2F..%2FDesktop%2FRoot%20Server%20193.0.14.129%20in%20London.png)

3)Autonomica, Stockholm, Sweden
![Root Server 192.36.148.17 in Sweden.png](..%2F..%2FDesktop%2FRoot%20Server%20192.36.148.17%20in%20Sweden.png)

Conclusion: The round trip times for the destinations that were physically closest to me, like stonybrook.edu 
and local host were a lot less than the root servers outside the U.S. I think that the destinations closest to me required 
less hops to get to which results in a lower RTT