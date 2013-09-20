airport_ARPTEnablers
============
OS X Airport PCIe Half Mini

An ARPTEnabler enables native Airport with non- native WiFi PCIe Half Mini cards on OS X/Mountain Lion/10.8.5 and newer. This method avoids dsdt and kext edits and is immune to Software Updates and BIOS revisions. 

Requirements
1. 10.8.5 or newer (This solution does not work in 10.8.4 or earlier) 

Airport Kext Enablers
1. bcm4352.kext - enables Airport WiFi and BT on installed BCM94352 WiFi Card
1a. Airport 802.11 ac/a/b/g/n dual band WiFi
1b. BT 4.0 dual mode with Low Energy Technology

2. toledaARPT.kext - enables Airport WiFi with the specified Non-Native Airport PCIe Half Mini cards, see [Guide] airport_pcie-hm_details.pdf
2a. BCM943224 HMS - 2.4/5 GHz, bgn, 2 stream, 300 Mbs
2b. BCM943225 HMB - 2.4/5 GHz, bgn, 2 stream, 300 Mbs + BT (3.0)
2c. BCM94352 HMB - 2.4/5 GHz, ac+abgn, 2 stream, 867 Mbs + BT (4.0)
2d. AR9285 - 2.4 GHz, abgn, 1 stream, 150 Mbs
2e. AR9287 - 2.4 GHz, abgn, 2 stream, 300 Mbs
2f. BT - Broadcom default

Downloads (select one)
1. Select bcm4352.kext.zip/View Raw/Save as .zip
2. Select toledaARPT.kext.zip/View Raw/Save as .zip

Tools
1. Kext installers - KextBeast, Kext Utility, DPCIManager

Installation
1. Copy Downloads/
1a. bcm4352.kext to Desktop or
1b. toledaARPT.kext to Desktop
2. Run kext installer
3. Restart
4. Configure System Preferences/Network/Airport
5. Verify Airport

Configuration/Troubleshooting
1.[Guide] airport_pcie-hm_details.pdf

Credit
MasterChef

toleda
https://github.com/toleda/airport_ARPTinjection
Files:
toledaARPT.kext