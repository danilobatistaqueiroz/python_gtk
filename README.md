```bsh
multipass stop snapcraft-takenotes
snapcraft --use-lxd --debug
lxc list
snap install takenotes_1_amd64.snap --dangerous --devmode
snap run takenotes
lxc delete snapcraft-takenotes
```
