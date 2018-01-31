ansible consul
==============

ansible scripts used to deploy a consul cluster.

# Assumptions
  * Operating system: CentOS 7.3+ minimal
  * deployment can ssh to all nodes without password

# Roles
  * server: raft quorum, gossip protocol
  * client: gossip protocol

# Versions
  * consul: 1.0.3
