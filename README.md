
multipass stop snapcraft-takenotes
snapcraft --use-lxd --debug
snap install takenotes_1_amd64.snap --dangerous --devmode
snap run takenotes