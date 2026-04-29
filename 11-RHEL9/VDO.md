```lsblk```

```sudo dnf install lvm2 vdo kmod-kvdo```

```sudo fallocate -l10G /root/disk1```

```sudo losetup -f /root/disk1 --show```

```sudo vgcreate myvg /dev/loopXX```

```sudo lvcreate --type vdo --name myvdolv --extents 100%FREE --virtualsize 50G --myvg```

```sudo mkfs.xfs -K /dev/myvg/myvdolv```

```du -sh```

```df -h```

```losetup```

```losetup -f /root/disk1 --show```
