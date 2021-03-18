# Yet Another Server Monitor

Fork of https://github.com/shevabam/ezservermonitor-sh.

[yamon](https://github.com/yebo29/yaservermonitor) is a script for monitoring Linux servers.

It is a simple script that displays on a terminal information such as:

![](https://www.ezservermonitor.com/uploads/esm_sh/esm-sh_dashboard-complete.png)

- **System** : hostname, OS, kernel version, uptime, last boot date, number of current user(s), server datetime
- **Load average** : percentages showing the CPU load (1 minute, 5 minutes et 15 minutes)
- **CPU** : model, frequency, cores number, cache L2, bogomips
- **Memory** : displays free and total memory
- **Network usage** : displaying the IP address of each network interface (WAN and LAN)
- **Ping** : ping the hosts defined in the configuration section of the script
- **Disk usage** : table of each mount point with the space available, used and total
- **Services** : displays the status (up or down) services defined in the configuration section of the script
- **Disks and system temperatures** : displays the disks, CPU and motherboard temperatures (optional)

Several themes are available !

![](https://www.ezservermonitor.com/uploads/esm_sh/esm-sh_themes.png)

## Install and Usage

* Clone this repo or download the script. Make it executable and run the `-h` option to see available options.
