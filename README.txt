airport_pcie-hm
============
OS X Airport PCIe Half Mini

Airport working OOB on Mountain Lion with Broadcom BCM4360  and Atheros AR9280   Mountain Lion (10.8.5 and newer) reports as Airport Extreme; Wake on Wireless (Atheros) and AirDrop supported.  Newer Broadcom WiFi cards no longer require rebranding to work in OS X.

BCM943224 HMS, BCM943225 HMB and BCM94352 HMB  PCIe Half Mini versions tested.  AR9280, AR9285 and AR9287 PCIe Half Mini versions tested.   Mini PCIe versions  and Mini PCIe to PCIe versions expected to work. 

Requirements
1. !0.9 or newer
2. 10.8.5 or newer (This solution does not work in 10.8.4 or earlier)

Airport PCIe Half Mini Guides:
[Guide]_airport_pcie-hm_details.pdf.zip
[Guide]_airport_pcie-hm_dsdt_edits.pdf.zip
[Guide]_airport_pcie-hm_plist_edits.pdf.zip

Native Airport PCIe Half Mini cards.
2. BCM4360 - 2.4/5 GHz, ac+abgn, 3 Stream, 1300 Mbs  (PCIe x1, not HM at this time)
3. AR9280 - 2.4/5 GHz, abgn, 2 Stream, 300 Mbs
4. AR9380 - 2.4/5 GHz, abgn, 3 Stream, 450 Mbs

Non-Native Airport PCIe Half Mini cards, see [Guide] airport_pcie-hm_details.pdf
1. BCM943224 HMS - 2.4/5, GHz abgn, 2 stream, 300 Mbs
1. BCM943225 HMS - 2.4 GHz, bgn, 2 stream, 108 Mbs
2. BCM943225 HMB - 2.4 GHz, bgn, 2 stream, 108 Mbs + BT (3.0)
3. BCM94352 HMB - 2.4/5 GHz, ac+abgn, 2 stream, 867 Mbs + BT (4.0)
4. AR9285 - 2.4 GHz, abgn, 1 stream, 54 Mbs
5. AR9287 - 2.4 GHz, abgn, 2 stream, 108 Mbs

WiFi + BT
1. BCM943352 HMB/AzureWave AW-CE123H supports both Airport and Bluetooth 4.0
Note: The Asus Superfast 802.11ac (Z87 Pro & Deluxe motherboards) is the BCM4352
2. BCM943225 HMB supports both Airport and Bluetooth 3.0
3. For any working WiFi without BT; 4.0, wake, low energy, native - suggest:
http://www.gmyle.com/products/micro-usb-bluetooth-4-0-dongle-dual-mode-w-low-energy-technology-wireless-adapter-broadcom-bcm20702-chipset-x10

Airport Injection Methods
1. kext enabler, see airport_kext_enabler folder/README.txt (above)
1a. bcm4352.kext.zip - bcm4352/aw-ce123h WiFi + BT
1b. bcm4352bt.kext.zip - bcm4352/aw-ce123h BT only
1c. toledaARPT.kext.zip - see [Guide] airport_pcie-hm_details.pdf.zip
2. kext edit/Info.plist, see [Guide] airport_pcie-hm_plist_edits.pdf.zip
3. dsdt edits, [Guide] airport_pcie-hm_dsdt_edits.pdf.zip
4. ssdt enabler, see airport_ssdt_enabler folder/README.txt (above)
4a. airport_ssdt-bcm43xx_v1.zip
4b. airport_ssdt-ar928x_v1.zip

Installation/Configuration/Troubleshooting
[Guide] airport_pcie-hm_details.pdf.zip

Problem Reporting/Post to
1. http://www.tonymacx86.com/network/104850-guide-airport-pcie-half-mini-v2.html
2. http://www.insanelymac.com/forum/topic/292542-airport-pcie-half-mini/

Credit
THe KiNG 
Andy Vandijck
PikeRAlpha
EMlyDinEsH

toleda
https://github.com/toleda/airport_pcie-hm
[Guide] airport_pcie-hm_details.pdf.zip
[Guide] airport_pcie-hm_dsdt_edits.pdf.zip
[Guide] airport_pcie-hm_plist_edits.pdf.zip
README.txt
Folders
airport_kext_enabler
airport_ssdt_enabler
Patches
