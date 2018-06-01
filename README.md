# rig-monitorv2
rig-monitor implementation in Golang

This is the rig-monitor implementation in Go.  

The currrent 2.2 version, includes the following features:

Complete feature list:
* Single executable for monitoring pools, rigs, power and market data with support for logging, tracing
* Custom config file replaced with toml-based config file
* Ability to pool thousands of rigs and dozens of pools simultaneously
* Automatic reload of rig, pool and power management rules in case of configuration file changes, during runtime
* miner support
  * Claymore single/dual-mining (tested v11.6)
  * Xmr-stak (tested v2.4.2)
  * Sgminer (tested v5.5.5)
  * SRBMiner
  * XMRig-proxy (tested v5.5.5)
  * PhoenixMiner (tested v2.9e)
  * CastXmr
* pool support
  * Nanopool (all coins)
  * Ethermine (all coins)
  * Mpos based pools e.g. miningpoolhub.com (all coins)
  * Nodejs-pool based pools e.g. hashvaultpro.com (all coins)
  * Fairpool
* power monitoring using smartplugs
  * TP-Link HS110 v1.0 and v2.0 hardware
  * Wemo Insight
* power management rules enable users to trigger rig reset via smart plugs or external script in case a given KPI limit is crossed
  * TP-Link HS110 v1.0 and v2.0 hardware
  * Wemo Insight
  * User-defined scripts
* Market data monitoring
  * Coinmarketcap.com
  * whattomine.com
* Data storage using influxDB
* Cross-platform support
  * raspberry Pi 1 Model B/ARMv6
  * raspberry Pi 2/3/ARMv7
  * linux/x86-64
  * macOS/x86-64
  * windows/i386
  * windows/x86-64
* Launch remote management applications like ssh or Team Viewer from Grafana
* Dashboard examples (templates) for all supported miners and pools
* Full Mining Overview Dashboard example
* Notifications via Telegram

Installation instructions here: https://www.rigmonitor.app/blog/version-2-0-beta-installation-instructions/

If you need support for other miners, pools, smart-plugs or for bug reporting, new feature request etc... then submit a new issue on the github project here:https://github.com/rodneymo/rig-monitorv2/issues

rodneymo
