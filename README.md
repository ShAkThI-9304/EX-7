# IMPLEMENTATION OF TRACEROUTE COMMAND

# EXP: 7

# DATE:20-04-2023

# AIM :
 To write the python program for simulating Traceroute command


# ALGORITHM :
 1. Start the program.
 2. Get the frame size from the user.
 3. To create the frame based on the user request.
 4. To send frames to server from the client side.
 5. If your frames reach the server, it will send ACK signal to client
otherwise it will sendNACK signal to client.
 6. Stop the program

# PROGRAM :
```PYTHON 3 

from scapy.all import *

target = ["www.google.com"]
result, unans = traceroute(target, maxttl=32)
print(result, unans)


```




# OUTPUT :
![output](P.png)




# RESULT :
 Thus, the python program for simulating Traceroute command was successfully executed.


