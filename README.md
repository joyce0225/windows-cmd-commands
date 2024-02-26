# 🛠️ 40 Essential Windows CMD Commands

## 🌐 Network Commands
1. **`ipconfig`** - Displays basic IP configuration. 📡
2. **`ipconfig /all`** - Shows detailed network configuration, including MAC and DNS server addresses. 🔍
3. **`ipconfig | findstr`** - Filters output to show specific details like DNS. 🔎
4. **`ipconfig /release`** - Releases the current IP address. 📤
5. **`ipconfig /renew`** - Obtains a new IP address from the DHCP server. 📥
6. **`ipconfig /displaydns`** - Shows the DNS resolver cache. 📒
7. **`ipconfig /displaydns | clip`** - Copies DNS resolver cache to the clipboard. 📋
8. **`ipconfig /flushdns`** - Clears the DNS resolver cache. 🧹
9. **`nslookup`** - Queries DNS servers for IP addresses and other DNS records. 🔍
10. **`cls`** - Clears the Command Prompt screen. 🧽

## 🖥️ System and Disk Management
11. **`getmac /v`** - Displays MAC addresses of network interfaces. 🌐
12. **`powercfg /energy`** - Analyzes energy usage of the computer. 🔋
13. **`powercfg /batteryreport`** - Generates a battery status report. 🔋
14. **`assoc`** - Shows or modifies file extension associations. 📂
15. **`chkdsk`** - Checks the disk for errors and repairs them. 🛠️
16. **`chkdsk /f`** - Fixes errors found on the disk. 🛠️
17. **`chkdsk /r`** - Locates bad sectors and recovers readable information. 🛠️
18. **`sfc /scannow`** - Scans and repairs system files. 🛠️
19. **`DISM /Online /Cleanup-Image /RestoreHealth`** - Repairs the Windows system image. 💊
20. **`dism /checkhealth`** - Checks the health of the system image. 💊
21. **`dism /scanhealth`** - Scans system image for corruption. 🔍
22. **`dism /restorehealth`** - Repairs the system image. 💊

## 📊 Task and Process Management
23. **`tasklist`** - Lists all running processes. 📝
24. **`taskkill`** - Terminates a specific task. ❌

## 📶 Network Diagnostics and Management
25. **`netsh wlan show wlanreport`** - Generates a wireless report. 📡
26. **`netsh interface show interface`** - Displays network interfaces. 🌐
27. **`netsh advfirewall set allprofiles state off`** - Turns off Windows Defender Firewall. 🔒
28. **`netsh advfirewall set allprofiles state on`** - Turns on Windows Defender Firewall. 🔓

## 🕵️‍♂️ Connectivity and Routing
29. **`ping`** - Checks connectivity to a host. 🏓
30. **`ping -t`** - Continuously pings a host. 🏓
31. **`tracert`** - Traces packet path to a network host. 🗺️
32. **`tracert -d`** - Traces route without resolving domain names. 🗺️
33. **`netstat`** - Displays network connections and ports. 🌐
34. **`netstat -o`** - Shows connections with process IDs. 🔍
35. **`netstat -e -t 5`** - Displays network statistics every 5 seconds. 📊

## 🚦 Routing Table Management
36. **`route print`** - Shows the routing table. 🗺️
37. **`route add`** - Adds a route to the routing table. ➕
38. **`route delete`** - Removes a route from the routing table. ➖

## 🛑 Shutdown and System Management
39. **`shutdown`** - Shuts down the computer. 💤
40. **`shutdown /r /o`** - Restarts the computer and boots into BIOS. 🔄

These commands are crucial for troubleshooting, managing network settings, and maintaining Windows systems efficiently. 🛠️💻
