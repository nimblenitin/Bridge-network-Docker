# Bridge-network-Docker

In terms of Docker, a bridge network uses a software bridge which allows containers connected to the same bridge network to communicate, while providing isolation from containers which are not connected to that bridge network.

Simple steps to create a Bridge network-

```

1. Use the following command to create a network:
$ sudo docker network create mynetwork1

2. Use the following command to list current networks:
$ sudo docker network ls

3. Use the following command to inspect the network:
$ sudo docker network inspect mynetwork1

```
