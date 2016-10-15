Auto Docker build for hkarhani/saltminion 

Intermediate Docker built of Salt Minion 

git clone this directory. 

To build, use: docker build -t yourusername/saltminion . 

Needs to define 
/etc/salt/minion: 
master: master-ip 
id: minion-id 

Then 
service salt-minion start 

