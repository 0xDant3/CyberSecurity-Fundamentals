1. Easy: Our client wants to know if we can identify which operating system their provided machine is running on. Submit the OS name as the answer.![[Pasted image 20231107104236.png]]
2. Medium:![[Pasted image 20231107104258.png]]
3. Hard: After a full port scan which took the better part of an hour, I forgot to screenshot and save. Long story short, we identified port 50000 as a port on the target system. Using the netcat trick and connecting with port 53, we found the flag.  
   ![[Pasted image 20231107104356.png]]
    