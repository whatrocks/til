Memory load:  (tweak the 0.99 to increase or decrease ram usage)
```bash
apt-get install stress
stress --vm-bytes $(awk '/MemAvailable/{printf "%d\n", $2 * 0.99;}' < /proc/meminfo)k --vm-keep -m 1
```

Create large files instantly on Linux: 
```bash
fallocate -l 10G file3
```

Create large files on Mac:
```bash
mkfile 1m test.tmp
```
