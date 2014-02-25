Cassandra cluster setup using vagrant
=====================================

Modified from https://bitbucket.org/durdn/stash-vagrant-install.git

## Dependencies

1. Vagrant 1.3.5
2. VirtualBox 4.2.16 r86992

## Step to bring up a running cassandra

1. Clone the repository

        $ git clone https://github.com/shaochuan/vagrant-cassandra-cluster.git
        $ cd vagrant-cassandra-cluster

2. Start up and provision automatically all dependencies in the vm:

        $ vagrant up

3. Now your cluster is up and running. At your host machine, use cqlsh to connect with the cluster

        $ cqlsh

