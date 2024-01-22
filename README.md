# Setup nexa node

This repository contains a script for setting up a nexa node. 

## Installation

Prerequisites:

System Requirements:
    4 or more physical CPU cores.
    At least 200GB disk storage.
    At least 16GB of memory (RAM)
    At least 100mbps network bandwidth.

#### Clone this repo using:
```bash
git clone [TODO]

```
## Setup a node first:

open a terminal window and run the following command
[Verify permission of the sh file to run]
for ubuntu
```bash
./nexa_ubuntu_node.sh
```

for mac run this script 
```bash
./nexa_mac_Script.sh
```

## Logs
**NOTE:** The blockchain syncing is running in a background as a service you can print the logs and check the logs of the node with the following command.

for ubuntu 
```bash
journalctl -u nexa -f 
```

for mac logs run this
```bash
tail -f $HOME/logfile.log
```

For stop the node 
for ubuntu
```bash
sudo systemctl stop nexa.service
```

for mac
```bash
launchctl stop com.nexa.myservice
```

