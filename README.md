# CYD MachineStats,
### Note - This project is Open Source. (WIP, IT will ber released soon.)
----
Welcome To the CYD TempViewer!

What is This?

This Utility allows you to turn a CYD (Cheap Yellow display) Into a temprature Viewer For your computer using WiFi (USB option availible) It includes:

* CPU Temps
* GPU Temps
* Motherboard Temps (WIP)
* Ram Temps (WIP)
* Storage Temps (WIP)
* Fans RPM (WIP)
-----
This project utilises Flask and pythonnet For a WiFi server, Which allows the computer (Server) to ping/pull data to the ESP (Client) This server is Local ONLY if you decide to use WiFi (Recomended)

### Q: Will This Affect My peformance when Gaming? 

### A: No, Temprature Polling is Lightweight (MSI afterburner and HWMonitor uses it) 

### Q: Will this Impact my Network Peformance / Ping Ingame? 

### A: Again, No. it is a Localhost Web Server (Flask) and it is Also Lightweight
### It also dosent compete for Bandwidth And your Ping to Game Servers Is External, so Your ESP (Internal Device) Can't Change your WAN latency.

