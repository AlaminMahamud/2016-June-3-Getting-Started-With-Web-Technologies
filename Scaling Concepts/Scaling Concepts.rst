# Find the Bottleneck

- is it the server
- or db

# Scaling the Data Store

- dedicated database server 

# Scaling the Server

- load balancer for servers
- load balancer for master database

# Caching, Indexing, Data Compressions

** Caching ** : If the user is asking for same type of data and the data is not changed then the data is cached for further requests


** Question ** : What is the speed diff in caching?


Factor of Hundreds and Thousands improvement


# Traditional Web Servers and Socket Development

Traditional Web Servers trained to "hang up" for real time updating, each server could 
support perhaps hundreds of simultaneous updates/connections

**Sockets** : maintain the socket connection. for real time updating each server could support perhaps hundreds of thousands 
of simultaneous connections/updates. 



