# Bigchaindb-Exploration

## Quick start on bigchaindb with docker

https://docs.bigchaindb.com/projects/server/en/latest/appendices/run-with-docker.html

## Consensus algorithm
Raft

### Permission (could be private or public)
https://blog.bigchaindb.com/towards-a-public-bigchaindb-654619d93fac

## Pros
* Good for assets transfer
* Good for basic constraint based transfer. eg: If 2 or more owners of an asset agree then transfer the asset to another person.

## Cons

* Smart contract concept is not matured
* Not byzantine fault tolerance


### Notes:

* To connect to your rethinkdb node: http://0.0.0.0:58080
* To connect to your bigchaindb node: http://0.0.0.0:59984
* Postman collection to create, transfer and query transaction is included in resource folder
