# minix_notes

There was a problem installing Minix 2 in QEMU, something about RAM "unrecoverable disk error on device ...". So programs from USR floppy doesn't work. Solution are to copy necessary programs from USR to ROOT and edit /etc/rc (only start shell).

[Here full process](minix_install)
