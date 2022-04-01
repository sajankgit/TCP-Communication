# TCP-Communication


<img width="522" alt="Screenshot 2022-04-01 at 14 41 27" src="https://user-images.githubusercontent.com/37524392/161233484-7efeaa94-83be-45d8-bcec-017046483f91.png">


All bytes in a TCP connection are numbered, beginning at a randomly chosen initial sequence number (ISN). The SYN packets consume one sequence number, so actual data will begin at ISN+1. The sequence number is the byte number of the first byte of data in the TCP packet sent (also called a TCP segment). The acknowledgement number is the sequence number of the next byte the receiver expects to receive. The receiver ack'ing sequence number x acknowledges receipt of all data bytes less than (but not including) byte number x.
