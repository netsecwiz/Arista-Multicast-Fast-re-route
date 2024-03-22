# Arista-Multicast-Fast-re-route
going off the guide here:https://www.arista.com/en/support/toi/eos-4-20-1f/13929-multicast-only-fast-reroute
and adding backups with scripts on leaf1 and leaf 4 we will be testing MoFrr.
Here is 
the topology: 
<br />
![image](https://github.com/netsecwiz/Arista-Multicast-Fast-re-route/assets/123339313/9c7b521a-78ca-4f68-9a33-02fa560a790a)
<br />
Leaf2 and Leaf3 can be ignored if you want. take the backups and deploy into GNS3 and run the scipts to test. 
Backups will be found in the backups folder.<br />
Scripts are found in the scritps folder. <br />
The scritps are implemnted on the arista by typing bash to go into bash. <br />
Then cd /mnt/flash/ <br />
use a text editor like vi or nano to make the script. <br />
chmod + x to make it executable. <br />
I used the mcast-sourch on host1 and the reciever on host 2. 

