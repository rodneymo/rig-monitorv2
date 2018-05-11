# rig-monitorv2
rig-monitor implementation in Golang

This is the rig-monitor implementation in Go.  

The currrent beta version, includes the following features:

* single file execution with support for logging, tracing
* custom config file replaced with toml-based config file
* ability to pool hundreds of rigs and dozens of pools simulatenously
* configurable polling times
* miner support
  * claymore (tested v11.6)
  * xmr-stak (tested v2.4.2)
  * sgminer (tested v5.5.5)
* pool support
  * nanopool (all coins)
  * ethermine (all coins)
  * mpos based pools e.g. miningpoolhub.com (all coins)
  * nodejs-pool based pools e.g. hashvaultpro.com (all coins)
* power monitoring using smartplugs
  * TP-Link HS110
* Market monitoring
* Data storage using influxDB
* Cross-platform support
  * raspberry Pi 1 Model B/ARMv6
  * raspberry Pi 2/ARMv7
  * raspberry Pi 2 v1.2 /ARMv8
  *raspberry Pi 3 Model B ARMv8
  * linux/x86-64
  * macOS/x86-64
  * windows/i386
  * windows/x86-64

If you need support for other miners, pools, smart-plugs or for bug reporting, new feature request etc... then submit a new issue on the github project here:https://github.com/rodneymo/rig-monitorv2/issues

rodneymo
