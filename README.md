!#/bin/bash
echo "server inventory"
lsmen
echo "here is the memoryinformation"
cat /ect/*release/
echo "here is the disk usage information"
du -h
echo "here is the cpu usage information"
lscpu
echo "here is the kernel version infomatio"
uname -r
