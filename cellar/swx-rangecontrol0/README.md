# swx-rangecontrol0

This is a system76 "range control" laptop that Nathalie is using.

## dm creation

    docker-machine create -d generic --generic-ip-address 172.109.143.74 --generic-ssh-port 60022 --generic-ssh-key ${devops}/secrets/ssh/sofwerx --generic-ssh-user swxadmin --generic-engine-port 60376 --engine-storage-driver overlay2 swx-u-ub-rangecontrol0
    swx dm import swx-u-ub-rangecontrol0

