CPU:
	uptime (load average)
	top / htop
	mpstat -P ALL 1 5
RAM:
	free -h
	vmstat 1 5
Disk I/O:
	df -h
	iostat -xz 1 5
	iotop
Network:
	ip -s link (или netstat)
	ss -tulpen
	sar -n DEV 1 5