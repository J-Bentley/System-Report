# SYSINFO
Summarizes Ubuntu system metrics via shell script or Windows via powershell script using default commands with formatted stdout & error.     

* hostname
* ip
* os
* cpu
* ram
* disks
* devices
* software

[Screenshot (Ubuntu)](https://i.imgur.com/ZjLpSMU.png)  


[Screenshot (Windows)](https://i.imgur.com/7fqrEvw.png)
## Usage
```bash systeminfo.sh [-h|help, -n|name, -i|ip, -o|os, -c|cpu, -m|ram, -d|disks, -de|devices, -s|software]``` 

## Caveats
* Only 1 argument can be called at a time unless in no arg mode when all aregs but software and devices are called.

