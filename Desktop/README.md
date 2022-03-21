Most popular PCI devices in Desktops
====================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Desktops ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Infiniband ](#infiniband-pci)
   * [ Input ](#input-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia ](#multimedia-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Signal processing ](#signal-processing-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage ](#storage-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/ide ](#storageide-pci)
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ Storage/sas ](#storagesas-pci)
   * [ Storage/scsi ](#storagescsi-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Video ](#video-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1439 | 1022:1234 | AMD              | Family 16h Processor Functions 5:1   | 243   | pcib       | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 1022:780e | 1022:780e | AMD              | FCH LPC Bridge                       | 196   | isab       | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:156b |           | AMD              | Family 16h (Models 30h-3fh) Host ... | 187   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1580 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 187   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1581 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 187   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1582 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 187   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1583 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 187   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1584 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 187   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1585 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 187   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1566 | 1022:1566 | AMD              | Family 16h (Models 30h-3fh) Proce... | 178   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:9d13 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 164   | pcib       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:9d12 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 162   | pcib       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:9d14 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 160   | pcib       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:9d10 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 157   | pcib       | [B9475ED44D](<Desktop/Protectli/FW/FW6/3EFC335326E0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/B9475ED44D>) |
| 8086:9d11 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 157   | pcib       | [B9475ED44D](<Desktop/Protectli/FW/FW6/3EFC335326E0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/B9475ED44D>) |
| 8086:9d15 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 156   | pcib       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 1022:1452 |           | AMD              | Family 17h (Models 00h-1fh) PCIe ... | 154   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1002:4384 |           | AMD              | SBx00 PCI to PCI Bridge              | 132   | pcib       | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 115   | isab       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 115   | pcib       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 114   | hostb      | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:22ca | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 112   | pcib       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:5904 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 112   | hostb      | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 111d:8018 |           | Microsemi / P... | PES12N3A 12-lane 3-Port PCI Expre... | 107   | pcib       | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 98    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 8086:22cc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 97    | pcib       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:22ce | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 95    | pcib       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 1022:1440 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 93    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1441 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 93    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1442 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 93    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1443 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 93    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1444 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 93    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1445 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 93    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1446 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 93    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1447 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 93    | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:43c7 | 1b21:3306 | AMD              | 400 Series Chipset PCIe Port         | 86    | pcib       | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 1022:1460 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 83    | hostb      | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1461 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 83    | hostb      | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1462 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 83    | hostb      | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1463 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 83    | hostb      | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1464 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 83    | hostb      | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1465 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 83    | hostb      | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1466 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 83    | hostb      | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1467 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 83    | hostb      | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:43c6 | 1b21:0201 | AMD              | 400 Series Chipset PCIe Bridge       | 83    | pcib       | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:9d4e | 8086:7270 | Intel            | Sunrise Point LPC Controller/eSPI... | 78    | isab       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 77    | isab       | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 8086:31d8 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 76    | pcib       | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 1022:1530 |           | AMD              | Family 16h Processor Function 0      | 72    | hostb      | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 1022:1531 |           | AMD              | Family 16h Processor Function 1      | 72    | hostb      | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 6     |            | [1BB8118ACD](<Desktop/Shuttle/DH/DH370/119ED6965086/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/1BB8118ACD>) |
| 10ec:522a | 1458:1000 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [5E980B75BC](<Desktop/Gigabyte Technology/GB-BACE/GB-BACE-3150/B48405EE0C5D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5E980B75BC>) |
| 10ec:5209 | 103c:2ac7 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx       | [1A831A1D34](<Desktop/Hewlett-Packard/120/120-1135/CCE480D5F4F8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/1A831A1D34>) |
| 10ec:5209 | 103c:2af5 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     |            | [172F23EFAC](<Desktop/Hewlett-Packard/120/120-1333w/CF46E5F843F4/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/172F23EFAC>) |
| 10ec:5209 | 103c:3399 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx       | [B11946A41A](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 Touch All-in-One PC/C898525C3ABA/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/B11946A41A>) |
| 10ec:5229 | 1025:0946 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx       | [A1E32DE7DA](<Desktop/Acer/RevoOne/RevoOne RL85/937E718E5858/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A1E32DE7DA>) |
| 10ec:5229 | 103c:2b3c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     |            | [6C628D33AB](<Desktop/Hewlett-Packard/23/23-r103la/BA7ECECD07E8/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/6C628D33AB>) |
| 10ec:5229 | 17aa:3658 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx       | [2F13D4A946](<Desktop/Lenovo/IdeaCentre/IdeaCentre B545 10100/4154E650F617/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2F13D4A946>) |
| 10ec:525a | 1028:06b9 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     |            | [A96DA2B00A](<Desktop/Dell/OptiPlex/OptiPlex 7040/3E1B177D4A77/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/A96DA2B00A>) |
| 10ec:525a | 1734:122e | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     |            | [8891E427E1](<Desktop/Fujitsu/CELSIUS/CELSIUS W570power/707C7BBA0561/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/8891E427E1>) |
| 10ec:525a | 1734:1249 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     |            | [2A0187EF7A](<Desktop/Fujitsu/CELSIUS/CELSIUS W580/2A362A4FB03E/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/2A0187EF7A>) |
| 10ec:5287 | 1025:1264 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 1     | rtsx       | [74B11992D7](<Desktop/Others/Others/Others/A81E0F9F7C65/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/74B11992D7>) |
| 10ec:5289 | 10ec:5289 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 1     |            | [0D40B0F9EB](<Desktop/Shuttle/XS35/XS35V3/463A73A74C81/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/0D40B0F9EB>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:19e2 |           | Intel            | Atom Processor C3000 Series Quick... | 20    |            | [2A3867A849](<Desktop/Others/Others/Others/E4DAE6013BC8/OPNSENSE-22.1/13.0-STABLE/AMD64/2A3867A849>) |
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 9     |            | [370A1D5B35](<Desktop/AAEON/FWS/FWS-2350/9E580EC1A050/OPNSENSE-22.1.1/13.0-STABLE/AMD64/370A1D5B35>) |
| 8086:37c8 |           | Intel            | C62x Chipset QuickAssist Technology  | 6     |            | [18576EF86C](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/199DE71C8C4A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/18576EF86C>) |
| 8086:0434 |           | Intel            | DH89XXCC Series QAT                  | 5     |            | [BAB9D9DD6D](<Desktop/Intel/DENLOW_WS/DENLOW_WS/7A23185583F9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BAB9D9DD6D>) |
| 8086:19e2 | 8086:19e2 | Intel            | Atom Processor C3000 Series Quick... | 2     | qat        | [B35BA41E9A](<Desktop/ASRockRack/C3558/C3558D4I-4L/00F1FC522527/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B35BA41E9A>) |
| 1000:0a05 | 1000:0a09 | Broadcom / LSI   |                                      | 1     |            | [53A51EC160](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/53A51EC160>) |
| 10de:03f4 | 1462:7597 | Nvidia           | MCP61 SMU                            | 1     |            | [6BE2D8AEC7](<Desktop/MSI/MS/MS-7597/30A30607F88A/FREEBSD-12.2/12.2-RELEASE/AMD64/6BE2D8AEC7>) |
| 10de:0753 | 1025:0157 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 1     |            | [DB1E7A52B9](<Desktop/Acer/Aspire/Aspire X3200/F5C25C81945B/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/DB1E7A52B9>) |
| 10de:0aa3 | 105b:0d52 | Nvidia           | MCP79 Co-processor                   | 1     |            | [79AB8EFB37](<Desktop/Foxconn/nT-330/nT-330i/70806ED76AFE/FREEBSD-12.1-P6/12.1-RELEASE-P6/AMD64/79AB8EFB37>) |
| 10de:0aa3 | 19da:a108 | Nvidia           | MCP79 Co-processor                   | 1     |            | [623EA6A889](<Desktop/Others/Others/Others/2BBBCF62335B/FREEBSD-12.1--HBSD/12.1-RELEASE-P7-HBSD/AMD64/623EA6A889>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 134   |            | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 73    |            | [C2B8C7EEBB](<Desktop/Others/Others/Others/40CC04883594/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C2B8C7EEBB>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 47    |            | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 36    |            | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:8c3a | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 31    |            | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:8c3a | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 30    |            | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 30    |            | [C4AA8D3B10](<Desktop/Protectli/FW/FW6/E40CCA659EE8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C4AA8D3B10>) |
| 8086:8c3d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 26    | uart       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:a13a | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 26    |            | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 8086:1c3a | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 25    |            | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:1e3a | 1043:84ca | Intel            | 7 Series/C216 Chipset Family MEI ... | 24    |            | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:1e3a | 1458:1c3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 24    |            | [5B6DD82DA8](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/34CE6C299230/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5B6DD82DA8>) |
| 8086:1c3a | 1458:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 23    |            | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 8086:9de0 | 8086:7270 | Intel            | Cannon Point-LP MEI Controller #1    | 22    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:8c3a | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    |            | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:5a9a | 1849:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [3E1591E714](<Desktop/ASRock/J3455/J3455B-ITX/D479CDF18817/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E1591E714>) |
| 8086:a2ba | 1043:8694 | Intel            | 200 Series PCH CSME HECI #1          | 18    |            | [AE4F0642FD](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/1E747FA168DD/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/AE4F0642FD>) |
| 8086:a360 | 1043:8694 | Intel            | Cannon Lake PCH HECI Controller      | 18    |            | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 8086:1e3a | 1028:0577 | Intel            | 7 Series/C216 Chipset Family MEI ... | 16    |            | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    |            | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:19d3 | 8086:19d3 | Intel            | Atom Processor C3000 Series ME HE... | 14    |            | [2A3867A849](<Desktop/Others/Others/Others/E4DAE6013BC8/OPNSENSE-22.1/13.0-STABLE/AMD64/2A3867A849>) |
| 8086:8c3a | 1849:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 14    |            | [DA796979AC](<Desktop/ASRock/B85/B85M-ITX/C18B8CE60627/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DA796979AC>) |
| 8086:8cba | 1458:1c3a | Intel            | 9 Series Chipset Family ME Interf... | 14    |            | [3CCD5EACE4](<Desktop/Gigabyte Technology/H97/H97N-WIFI/4343EFE08349/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/3CCD5EACE4>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 14    |            | [29FA6BEF41](<Desktop/Others/Others/Others/C96AE51A5D9A/OPNSENSE-22.1/13.0-STABLE/AMD64/29FA6BEF41>) |
| 8086:a2ba | 1458:1c3a | Intel            | 200 Series PCH CSME HECI #1          | 13    |            | [2727A8E439](<Desktop/Gigabyte Technology/H270-Gaming/H270-Gaming 3/92E92186ABE5/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2727A8E439>) |
| 8086:a360 | 1458:1c3a | Intel            | Cannon Lake PCH HECI Controller      | 13    |            | [17B3590A3F](<Desktop/Gigabyte Technology/C246/C246-WU4/4514509F1F50/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/17B3590A3F>) |
| 8086:1e3a | 103c:3397 | Intel            | 7 Series/C216 Chipset Family MEI ... | 12    |            | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:1e3d | 103c:3397 | Intel            | 7 Series/C210 Series Chipset Fami... | 12    | uart       | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:319a | 1849:319a | Intel            | Celeron/Pentium Silver Processor ... | 12    |            | [5A614C6238](<Desktop/ASRock/J5040/J5040-ITX/BA57FC9C5E6C/OPNSENSE-22.1/13.0-STABLE/AMD64/5A614C6238>) |
| 8086:8c3a | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 12    |            | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:8c3a | 1458:1c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 12    |            | [CECAC43923](<Desktop/Gigabyte Technology/P85/P85-D3/6D87717FDD41/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CECAC43923>) |
| 8086:8c3d | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 12    | uart       | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:a13a | 1458:1c3a | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [7987A8B851](<Desktop/Gigabyte Technology/H110/H110M-S2H/DC0C8E934748/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/7987A8B851>) |
| 8086:1c3a | 1028:04ad | Intel            | 6 Series/C200 Series Chipset Fami... | 11    |            | [4B4B77D8F3](<Desktop/Dell/OptiPlex/OptiPlex 790/14F63C42DF90/OPNSENSE-22.1/13.0-STABLE/AMD64/4B4B77D8F3>) |
| 8086:1c3a | 8086:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 11    |            | [D46B68CC28](<Desktop/Intel/CARLOW/CARLOW/D91B06809068/OPNSENSE-22.1.1/13.0-STABLE/AMD64/D46B68CC28>) |
| 8086:8cba | 1043:8534 | Intel            | 9 Series Chipset Family ME Interf... | 11    |            | [84D7FB3F1E](<Desktop/ASUSTek Computer/All/All Series/46CAE9B0FE93/GHOSTBSD-22.01.28/13.0-STABLE/AMD64/84D7FB3F1E>) |
| 8086:a2ba | 1849:a2ba | Intel            | 200 Series PCH CSME HECI #1          | 11    |            | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 8086:a360 | 1849:a360 | Intel            | Cannon Lake PCH HECI Controller      | 11    |            | [44FD3CD83C](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.1/13.0-STABLE/AMD64/44FD3CD83C>) |
| 8086:1c3a | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    |            | [CB96E68E6E](<Desktop/Dell/OptiPlex/OptiPlex 390/172FACB3F264/OPNSENSE-22.1.1/13.0-STABLE/AMD64/CB96E68E6E>) |
| 8086:1c3a | 1028:0585 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    |            | [9213769810](<Desktop/Dell/OptiPlex/OptiPlex 3010/678B89570748/OPNSENSE-22.1/13.0-STABLE/AMD64/9213769810>) |
| 8086:1e3a | 1028:052c | Intel            | 7 Series/C216 Chipset Family MEI ... | 10    |            | [0541A207C7](<Desktop/Dell/OptiPlex/OptiPlex 9010/630D25B19798/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0541A207C7>) |
| 8086:34a8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO UART Contro... | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:34e0 | 8086:7270 | Intel            | Ice Lake-LP Management Engine        | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:8c3a | 17aa:3098 | Intel            | 8 Series/C220 Series Chipset Fami... | 10    |            | [48DFDCF313](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10AU003DUK/BA63A6683747/OPNSENSE-22.1.3/13.0-STABLE/AMD64/48DFDCF313>) |
| 8086:8c3a | 8086:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 10    |            | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 8086:a13a | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [D7ADCA8CAC](<Desktop/NetCom IT/pczB/pczB1116/0CB716CAF1D6/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/D7ADCA8CAC>) |
| 8086:a13a | 1849:a13a | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [5C58D01F2D](<Desktop/ASRock/H110/H110M-ITX/D5B0B257B774/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5C58D01F2D>) |
| 8086:1c3a | 1028:047e | Intel            | 6 Series/C200 Series Chipset Fami... | 9     |            | [F4D8160D05](<Desktop/Dell/OptiPlex/OptiPlex 990/E38DB6E3EC62/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F4D8160D05>) |
| 8086:8c3a | 1734:11ea | Intel            | 8 Series/C220 Series Chipset Fami... | 9     |            | [43BFCEB19D](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P920/958E4EAD94D1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/43BFCEB19D>) |
| 8086:8c3a | 17aa:30a3 | Intel            | 8 Series/C220 Series Chipset Fami... | 9     |            | [EDDEB5C246](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AAA0WGUK/A53CA903F1D9/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/EDDEB5C246>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 187   |            | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 87    |            | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 69    |            | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 61    |            | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 57    |            | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 49    |            | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 1022:1486 | 1043:87c0 | AMD              | Starship/Matisse Cryptographic Co... | 27    |            | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1456 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) Platf... | 19    |            | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 177d:0010 | 177d:0001 | Cavium           | CN15XX/CN16XX [Nitrox PX]            | 16    |            | [53A51EC160](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/53A51EC160>) |
| 8086:0f18 | 1849:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 14    |            | [B4142103CB](<Desktop/ASRock/Q1900/Q1900B-ITX/A58F88E6A7C3/FREEBSD-12.3-P2/12.3-RELEASE-P1/AMD64/B4142103CB>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 14    |            | [A2EF313477](<Desktop/Protectli/FW/FW2/3CD419539C29/OPNSENSE-22.1.1/13.0-STABLE/AMD64/A2EF313477>) |
| 1022:15df | 1043:876b | AMD              | Family 17h (Models 10h-1fh) Platf... | 13    |            | [D57DE875A6](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/51805C43859D/FREEBSD-13.0/13.0-RELEASE/AMD64/D57DE875A6>) |
| 1022:1486 | 1043:8808 | AMD              | Starship/Matisse Cryptographic Co... | 8     |            | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 8     |            | [502AF52245](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10/BB7614C3933F/OPNSENSE-22.1/13.0-STABLE/AMD64/502AF52245>) |
| 1022:15df | 1849:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     |            | [F80D11C4A6](<Desktop/ASRock/4X4-4000/4X4-4000 Series/FF0DB8636C47/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F80D11C4A6>) |
| 8086:0f18 | 1458:1c3a | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     |            | [EC336DDAB4](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/FCE9E0893745/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/EC336DDAB4>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     |            | [64707B8717](<Desktop/NU591/1/1.0/686FE3922C3C/OPNSENSE-22.1/13.0-STABLE/AMD64/64707B8717>) |
| 8086:2298 | 1849:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [FB058E0B37](<Desktop/ASRock/N3700/N3700-ITX/77EAC92E80D5/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FB058E0B37>) |
| 1022:1486 | 1462:7c02 | AMD              | Starship/Matisse Cryptographic Co... | 4     |            | [14F1956220](<Desktop/MSI/MS-7/MS-7C02/0BF11DCDAD12/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/14F1956220>) |
| 8086:2298 | 1043:8534 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     |            | [289423796B](<Desktop/ASUSTek Computer/All/All Series/D02026182209/PFSENSE-2.5.0/12.2-STABLE/AMD64/289423796B>) |
| 8086:2298 | 1458:1000 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     |            | [5E980B75BC](<Desktop/Gigabyte Technology/GB-BACE/GB-BACE-3150/B48405EE0C5D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5E980B75BC>) |
| 1022:1456 | 1462:7b86 | AMD              | Family 17h (Models 00h-0fh) Platf... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 3     |            | [E4F7F31828](<Desktop/Supermicro/AS/AS -E301-9D-8CN4/72CEEFE7C3DC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E4F7F31828>) |
| 8086:2298 | 1565:3112 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     |            | [536F856D94](<Desktop/Biostar/J3160/J3160NH/F1B8BA6C9B4F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/536F856D94>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     |            | [5A4F0231BD](<Desktop/ZOTAC/Others/Others/576F6CF2C638/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5A4F0231BD>) |
| 1022:1486 | 1043:87cb | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:1486 | 1462:7b86 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 1022:1578 | 17aa:364f | AMD              | Carrizo Platform Security Processor  | 2     |            | [C43975A08F](<Desktop/Lenovo/IdeaCentre/IdeaCentre 310S-08ASR 90G90068US/439AD74C89CD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/C43975A08F>) |
| 1022:15df | 103c:87d6 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [FFA88D066B](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-1xxx/96EB6BA29D47/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/FFA88D066B>) |
| 1022:15df | 1043:8809 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [B23AB09F52](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/B23AB09F52>) |
| 8086:2298 | 1458:1c3a | Intel            | Atom/Celeron/Pentium Processor x5... | 2     |            | [382A3E1FBB](<Desktop/Gigabyte Technology/N3150/N3150ND3V/87684C325536/OPNSENSE-22.1.2/13.0-STABLE/AMD64/382A3E1FBB>) |
| 8086:2298 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     |            | [E547E2343A](<Desktop/Supermicro/SYS-E200/SYS-E200-9B/06EE75887F21/OPNSENSE-22.1/13.0-STABLE/AMD64/E547E2343A>) |
| 1022:1456 | 1462:7a40 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [43388A27A4](<Desktop/MSI/MS-7/MS-7A40/9E0B5CDB5278/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/43388A27A4>) |
| 1022:1456 | 1462:7b89 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [1123CB92BA](<Desktop/MSI/MS-7/MS-7B89/47621C911E75/FURYBSD-12.1-P9/12.1-RELEASE-P9/AMD64/1123CB92BA>) |
| 1022:1456 | 1462:7b90 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [E7BC61FACB](<Desktop/MSI/MS-7/MS-7B90/0D0E7C3B4D7C/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/E7BC61FACB>) |
| 1022:1456 | 1462:7c02 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [A87473149B](<Desktop/MSI/MS-7/MS-7C02/55874FBE1F48/FREEBSD-13.0/13.0-RELEASE/AMD64/A87473149B>) |
| 1022:1486 | 1043:87e2 | AMD              | Starship/Matisse Cryptographic Co... | 1     |            | [94C953E866](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/11439D70F63B/FREEBSD-12.2/12.2-RELEASE/AMD64/94C953E866>) |
| 1022:1486 | 1462:7b89 | AMD              | Starship/Matisse Cryptographic Co... | 1     |            | [6BFF2DB7E3](<Desktop/MSI/MS-7/MS-7B89/528C430BAE24/FREEBSD-12.1/12.1-RELEASE/AMD64/6BFF2DB7E3>) |
| 1022:1486 | 1849:1486 | AMD              | Starship/Matisse Cryptographic Co... | 1     |            | [739DB7D4A8](<Desktop/ASRockRack/B450/B450D4U-V1L/3D1C8BC698DB/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/739DB7D4A8>) |
| 1022:15df | 1458:1000 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [817CB3E603](<Desktop/Gigabyte Technology/BSRE/BSRE-1605/493093EBE60A/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/817CB3E603>) |
| 1022:15df | 1462:7a40 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [FBA459287E](<Desktop/MSI/MS-7/MS-7A40/B4CC3C2DC1A6/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/FBA459287E>) |
| 1022:15df | 1462:7c95 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [68F6EB4328](<Desktop/MSI/MS-7/MS-7C95/F962A0881828/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/68F6EB4328>) |
| 1022:15df | 1462:7d14 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [EAB7272687](<Desktop/MSI/MS-7/MS-7D14/DC8D92FA126B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/EAB7272687>) |
| 1022:15df | 17aa:318e | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [115F2C7B35](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75t Gen 2 11KECTO1WW/85187679911A/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/115F2C7B35>) |
| 1022:15df | 17aa:3728 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [7BA1CCC40D](<Desktop/Lenovo/IdeaCentre/IdeaCentre 5 14ARE05 90Q30008US/2ECD21E7A105/FREEBSD-12.2-P8/12.2-RELEASE-P8/AMD64/7BA1CCC40D>) |
| 1022:2082 | 1022:2082 | AMD              | Geode LX AES Security Block          | 1     | glxsb      | [27E7CD5267](<Desktop/Others/Others/Others/A1F86E952C1C/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/27E7CD5267>) |
| 177d:0003 | 177d:0001 | Cavium           | Nitrox XL N1 Lite                    | 1     |            | [60C61CEE80](<Desktop/Others/Others/Others/7B69D0D5B9E3/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/60C61CEE80>) |
| 8086:0f18 | 1019:7ed4 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [6741011E07](<Desktop/ECS/BAT-I/BAT-I/1BE4F925CBDC/OPNSENSE-21.1.9/12.1-RELEASE-P19-HBSD/AMD64/6741011E07>) |
| 8086:0f18 | 1028:0758 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [99E72A2B1B](<Desktop/Dell/Embedded/Embedded Box PC 3000/8633647ACDAA/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/99E72A2B1B>) |
| 8086:0f18 | 1043:8534 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [13D6D1ED51](<Desktop/ASUSTek Computer/All/All Series/4F4EBC5976FD/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/13D6D1ED51>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 8     | fwohci     | [E5043F0AF4](<Desktop/Apple/MacPro5/MacPro5,1/6FE9DFD8B0C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E5043F0AF4>) |
| 1106:3044 | 1043:81fe | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 7     | fwohci     | [FBDE5657E8](<Desktop/IEESA/P5K/P5K PRO/1DF42E107A56/FREEBSD-13.0/13.0-RELEASE/AMD64/FBDE5657E8>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 7     | fwohci     | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 1106:3044 | 1458:1000 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 7     | fwohci     | [3C315D0C15](<Desktop/Gigabyte Technology/990/990FXA-UD3/30C9592F6A6C/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/3C315D0C15>) |
| 11c1:5811 | 103c:1589 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 7     | fwohci     | [8BD32670C2](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8BD32670C2>) |
| 104c:8024 | 1458:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 6     | fwohci     | [21E4A40D62](<Desktop/Gigabyte Technology/EP45/EP45-UD3R/9AFB90672E3E/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/21E4A40D62>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 6     | fwohci     | [B7FC5EF684](<Desktop/Biostar/X470/X470GTA/2553A631F2D9/FREEBSD-13.0/13.0-RELEASE/AMD64/B7FC5EF684>) |
| 11c1:5811 | 1043:8294 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 6     | fwohci     | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 11c1:5811 | 103c:158a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 4     | fwohci     | [A9B66CB0E1](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/A9B66CB0E1>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 3     | fwohci     | [BE9D90602D](<Desktop/ASUSTek Computer/P9/P9X79/89D525F0E557/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/BE9D90602D>) |
| 11c1:5811 | 1028:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 3     | fwohci     | [97781253F2](<Desktop/Dell/Precision/Precision WorkStation T3500/092E81402E7E/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/97781253F2>) |
| 197b:2380 | 1043:8313 | JMicron Techn... | IEEE 1394 Host Controller            | 3     | fwohci     | [5999E0EBFB](<Desktop/ASUSTek Computer/P5P43TD/P5P43TD PRO/CAA935C7EB09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5999E0EBFB>) |
| 104c:8024 | 1028:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 2     |            | [EDEF5C789D](<Desktop/Dell/Studio/Studio XPS 9100/AEDEA8FF9972/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/EDEF5C789D>) |
| 1106:3044 | 1849:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 2     |            | [19BA4D2EE9](<Desktop/ASRock/Z77/Z77 Extreme6/929553D2B892/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19BA4D2EE9>) |
| 1106:3403 | 1028:040d | VIA Technologies | VT6315 Series Firewire Controller    | 2     |            | [7F75F30B75](<Desktop/Dell/Studio/Studio XPS 8100/AF73B07C29DA/FREEBSD-12.2/12.2-RELEASE/AMD64/7F75F30B75>) |
| 1106:3403 | 1043:8374 | VIA Technologies | VT6315 Series Firewire Controller    | 2     | fwohci     | [1C30F7523F](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/0638EC1B243E/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/1C30F7523F>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 2     | fwohci     | [40687B0E17](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/23AA4FC47B92/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/40687B0E17>) |
| 1106:3403 | 1849:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 2     |            | [CC090875B1](<Desktop/ASRock/970/970 Extreme4/908880BFE0BC/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/CC090875B1>) |
| 11c1:5811 | 103c:1309 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     | fwohci     | [B56BD19073](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/44AE2B54DFB8/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B56BD19073>) |
| 11c1:5811 | 103c:130a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     |            | [C2B43EFB8F](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/C2B43EFB8F>) |
| 11c1:5901 | 1b5b:803b | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 2     |            | [DA8A524302](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-12.2-P9/12.2-RELEASE-P7/AMD64/DA8A524302>) |
| 1033:00cd | 12ee:8010 | NEC Computers    | uPD72870 [Firewarden] IEEE1394a O... | 1     | fwohci     | [E34B6118A2](<Desktop/Hewlett-Packard/Compaq/Compaq 505B Microtower PC/0EF9A1953E0E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E34B6118A2>) |
| 104c:8020 | 15c5:8010 | Texas Instrum... | TSB12LV26 IEEE-1394 Controller (L... | 1     |            | [7E27B1BC46](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/28DD15B58DF2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/7E27B1BC46>) |
| 104c:8023 | 1028:021d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [E78392BC4C](<Desktop/Dell/Precision/Precision WorkStation T7400/1BAEE5C9C3FB/HELLOSYSTEM-0.5.0/12.2-RELEASE-P4/AMD64/E78392BC4C>) |
| 104c:8023 | 1043:808b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [5B1DC84DA5](<Desktop/ASUSTek Computer/P5/P5GD2-Deluxe/30982A88A2F4/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/5B1DC84DA5>) |
| 104c:8023 | 1043:815b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [A471763F19](<Desktop/ASUSTek Computer/P5/P5B-Deluxe/49386BD59CFA/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/A471763F19>) |
| 104c:8023 | 108e:5354 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [DDAE563E41](<Desktop/Sun Microsystems/Ultra/Ultra 27/33F836C0D1ED/FREENAS-11.3-P11/11.3-RELEASE-P11/AMD64/DDAE563E41>) |
| 104c:8023 | 108e:6676 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [AD993A51ED](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/16A2E5FCDB6A/FREEBSD-12.1/12.1-RELEASE/AMD64/AD993A51ED>) |
| 104c:8023 | 15d9:062c | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [EB73C9D13D](<Desktop/Supermicro/X9/X9DAi/558BB9BB7FC9/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/EB73C9D13D>) |
| 104c:8023 | 17aa:101c | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [428F39CBFF](<Desktop/Lenovo/ThinkStation/ThinkStation S10 6483CTO/53B2C53532C0/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/428F39CBFF>) |
| 104c:8023 | 17aa:101d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [6F464AAD1F](<Desktop/Lenovo/ThinkStation/ThinkStation D10 6493WEU/6A717F675FF7/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/6F464AAD1F>) |
| 104c:8023 | 8086:5044 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [E8F4F644E3](<Desktop/Intel/DG33BU/DG33BU AAD79951-408/9D3335CFA220/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/E8F4F644E3>) |
| 104c:8024 |           | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     |            | [1170B4BFD8](<Desktop/Dell/OptiPlex/OptiPlex 745/0BAF0103F9F5/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/1170B4BFD8>) |
| 104c:8024 | 1019:8056 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     |            | [B82613052E](<Desktop/Acer/ASE380/ASE380-AST180-APM8/D397FBEBCB54/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/B82613052E>) |
| 104c:8024 | 107b:604e | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     |            | [322450B653](<Desktop/Intel/D945GCF/D945GCF AAD73937-203/02CFC76F026F/FREEBSD-12.1/12.1-RELEASE/AMD64/322450B653>) |
| 104c:8024 | 1b5b:010a | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | fwohci     | [23DF6B2E94](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/2ECB6CBE56F2/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/23DF6B2E94>) |
| 104c:8235 | 104c:2200 | Texas Instrum... | XIO2200A IEEE-1394a-2000 Controll... | 1     |            | [F308AE78EA](<Desktop/Comptronic/pczB/pczB0111/15D6B8B43FFA/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/F308AE78EA>) |
| 104c:823f | 3412:7856 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 1     |            | [EF29C46355](<Desktop/ASRock/B450M/B450M Pro4/6CB7F35E1FD1/HELLOSYSTEM-0.5.0/12.1-RELEASE/AMD64/EF29C46355>) |
| 106b:0031 | 106b:5811 | Apple            | UniNorth 2 FireWire                  | 1     | fwohci     | [4B7ABCF4FB](<Desktop/Others/Others/Others/6B0A05EBCFE5/FREEBSD-12.1/12.1-RELEASE/POWERPC/4B7ABCF4FB>) |
| 106b:0052 | 106b:5811 | Apple            | Shasta Firewire                      | 1     | fwohci     | [223D74D547](<Desktop/Others/Others/Others/CEAA04E886E8/FREEBSD-12.2/12.2-RELEASE/POWERPC/223D74D547>) |
| 1106:3044 | 103c:2a2b | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [C93B86B3BA](<Desktop/Hewlett-Packard/ER904AA-ABA/ER904AA-ABA A1440N/99A7FE8ABBAC/NOMADBSD-1.3.2/12.1-RELEASE-P6/I386/C93B86B3BA>) |
| 1106:3044 | 103c:2a64 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [2A7CB7B214](<Desktop/Hewlett-Packard/Napa/Napa/C99FF842177B/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/2A7CB7B214>) |
| 1106:3044 | 103c:2a92 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [DA467830AF](<Desktop/Hewlett-Packard/HPE-570/HPE-570f/D6775F31A0B7/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/DA467830AF>) |
| 1106:3403 | 1025:0157 | VIA Technologies | VT6315 Series Firewire Controller    | 1     | fwohci     | [DB1E7A52B9](<Desktop/Acer/Aspire/Aspire X3200/F5C25C81945B/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/DB1E7A52B9>) |
| 1106:3403 | 1025:0158 | VIA Technologies | VT6315 Series Firewire Controller    | 1     |            | [A26BC8F2B3](<Desktop/Acer/Aspire/Aspire X1800/E32AE706D3B3/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/A26BC8F2B3>) |
| 1106:3403 | 1025:024d | VIA Technologies | VT6315 Series Firewire Controller    | 1     |            | [0BC978756C](<Desktop/Acer/Aspire/Aspire M3900/D36FA7E37E5A/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/0BC978756C>) |
| 1106:3403 | 1025:0250 | VIA Technologies | VT6315 Series Firewire Controller    | 1     |            | [28A6795710](<Desktop/Acer/Aspire/Aspire X3910/1E6B2A078AB7/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/28A6795710>) |
| 1106:3403 | 1028:02c9 | VIA Technologies | VT6315 Series Firewire Controller    | 1     |            | [1BD1DC24C9](<Desktop/Dell/Studio/Studio XPS 435MT/10E20858A5DB/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/1BD1DC24C9>) |
| 1106:3403 | 103c:2a9c | VIA Technologies | VT6315 Series Firewire Controller    | 1     |            | [BB2C6B383B](<Desktop/Hewlett-Packard/WC791AA-UUW/WC791AA-UUW HPE-119sc/C12B55EC0169/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/BB2C6B383B>) |
| 1106:3403 | 1462:576d | VIA Technologies | VT6315 Series Firewire Controller    | 1     |            | [76E8524CE1](<Desktop/MSI/MS/MS-7576/BCCA8BE2B875/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/76E8524CE1>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 111   | vgapci     | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 47    | vgapci     | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 8086:5916 | 8086:2015 | Intel            | HD Graphics 620                      | 43    | vgapci     | [B9475ED44D](<Desktop/Protectli/FW/FW6/3EFC335326E0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/B9475ED44D>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 42    | vgapci     | [FC2B2BB98D](<Desktop/NF541/1/1.0/B46CD6868798/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC2B2BB98D>) |
| 8086:0f31 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 33    | vgapci     | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 1002:9831 | 103c:213d | AMD              | Kabini [Radeon HD 8400E]             | 32    | vgapci     | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 30    | vgapci     | [C2B8C7EEBB](<Desktop/Others/Others/Others/40CC04883594/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C2B8C7EEBB>) |
| 8086:0a16 | 8086:0a16 | Intel            | Haswell-ULT Integrated Graphics C... | 29    | vgapci     | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 27    | nvidia     | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 8086:a001 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 27    | agp        | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:a002 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 26    | vgapci     | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 25    | vgapci     | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 8086:0412 | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 25    | vgapci     | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:0412 | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 24    | vgapci     | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:1616 | 8086:1616 | Intel            | HD Graphics 5500                     | 24    | vgapci     | [4774A3BC2F](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/D5565FC249CA/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4774A3BC2F>) |
| 8086:5917 | 8086:2015 | Intel            | UHD Graphics 620                     | 23    | vgapci     | [147ADA1C7F](<Desktop/Protectli/FW/FW6/C384134D9772/OPNSENSE-22.1.2/13.0-STABLE/AMD64/147ADA1C7F>) |
| 102b:0532 | 15d9:0624 | Matrox Electr... | MGA G200eW WPCM450                   | 22    | vgapci     | [042C1EFAC3](<Desktop/Supermicro/X9/X9SCL-X9SCM/7A7B84FA155C/OPNSENSE-22.7/13.0-STABLE/AMD64/042C1EFAC3>) |
| 8086:1626 | 8086:1626 | Intel            | HD Graphics 6000                     | 21    | vgapci     | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:2e32 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 21    | agp        | [E41BA68AA2](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33/OPNSENSE-22.1/13.0-STABLE/AMD64/E41BA68AA2>) |
| 8086:3ea0 | 8086:2212 | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 21    | vgapci     | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 19    | vgapci     | [53A51EC160](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/53A51EC160>) |
| 8086:5916 |           | Intel            | HD Graphics 620                      | 19    | vgapci     | [C5D261E811](<Desktop/Protectli/FW/FW6/9BA0256CC9A4/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C5D261E811>) |
| 8086:5916 | 8086:2212 | Intel            | HD Graphics 620                      | 19    | vgapci     | [C4AA8D3B10](<Desktop/Protectli/FW/FW6/E40CCA659EE8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C4AA8D3B10>) |
| 1002:15d8 | 1002:15d8 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 16    | vgapci     | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 1a03:2000 | 1849:2000 | ASPEED Techno... | ASPEED Graphics Family               | 16    | vgapci     | [B35BA41E9A](<Desktop/ASRockRack/C3558/C3558D4I-4L/00F1FC522527/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B35BA41E9A>) |
| 8086:5a85 | 1849:5a85 | Intel            | HD Graphics 500                      | 16    | vgapci     | [3E1591E714](<Desktop/ASRock/J3455/J3455B-ITX/D479CDF18817/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E1591E714>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 15    | vgapci     | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:0412 | 1458:d000 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 13    | vgapci     | [CECAC43923](<Desktop/Gigabyte Technology/P85/P85-D3/6D87717FDD41/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CECAC43923>) |
| 8086:0f31 | 1849:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 13    | vgapci     | [B4142103CB](<Desktop/ASRock/Q1900/Q1900B-ITX/A58F88E6A7C3/FREEBSD-12.3-P2/12.3-RELEASE-P1/AMD64/B4142103CB>) |
| 8086:0152 | 1458:d000 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 12    | vgapci     | [459BB6486D](<Desktop/Gigabyte Technology/Z77/Z77N-WIFI/798389D95EE6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/459BB6486D>) |
| 8086:0412 | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 12    | vgapci     | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 1002:15dd | 1002:15dd | AMD              | Raven Ridge [Radeon Vega Series /... | 11    | vgapci     | [EAB7272687](<Desktop/MSI/MS-7/MS-7D14/DC8D92FA126B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/EAB7272687>) |
| 8086:0152 | 1028:0577 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 11    | vgapci     | [A488C9AF25](<Desktop/Dell/OptiPlex/OptiPlex 7010/78AA11104573/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A488C9AF25>) |
| 8086:0162 | 1043:84ca | Intel            | IvyBridge GT2 [HD Graphics 4000]     | 11    | vgapci     | [E15D67E8DB](<Desktop/ASUSTek Computer/P8/P8H77-I/4CFD4EC7FC22/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/E15D67E8DB>) |
| 10de:1d01 | 1462:8c98 | Nvidia           | GP108 [GeForce GT 1030]              | 10    | nvidia     | [AE2203B146](<Desktop/Dell/OptiPlex/OptiPlex 3010/B8947DA31545/NOMADBSD-5806F915/13.0-RELEASE/AMD64/AE2203B146>) |
| 8086:0412 | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 10    | vgapci     | [C010A04C70](<Desktop/Dell/OptiPlex/OptiPlex 3020/52D87EEBDF67/OPNSENSE-22.1/13.0-STABLE/AMD64/C010A04C70>) |
| 8086:8a56 | 1e50:800a | Intel            | Iris Plus Graphics G1 (Ice Lake)     | 10    | vgapci     | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 1002:1638 | 1002:1636 | AMD              | Cezanne                              | 9     | vgapci     | [D3596DFF89](<Desktop/ASRock/X570/X570 PG Velocita/A90551D8040B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D3596DFF89>) |
| 8086:0102 | 1028:047e | Intel            | 2nd Generation Core Processor Fam... | 9     | vgapci     | [201BA6CBBA](<Desktop/Dell/OptiPlex/OptiPlex 990/920D8E738DC6/PFSENSE-2.5.0/12.2-STABLE/AMD64/201BA6CBBA>) |
| 8086:0102 | 1028:04f5 | Intel            | 2nd Generation Core Processor Fam... | 9     | vgapci     | [CB96E68E6E](<Desktop/Dell/OptiPlex/OptiPlex 390/172FACB3F264/OPNSENSE-22.1.1/13.0-STABLE/AMD64/CB96E68E6E>) |
| 8086:041e | 1028:0612 | Intel            | 4th Generation Core Processor Fam... | 9     | vgapci     | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:1916 | 8086:2015 | Intel            | Skylake GT2 [HD Graphics 520]        | 9     | vgapci     | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 8086:3185 | 1849:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 9     | vgapci     | [09B9D104B9](<Desktop/ASRock/J4105/J4105M/B34B3BEDE51E/OPNSENSE-22.1/13.0-STABLE/AMD64/09B9D104B9>) |
| 8086:5906 |           | Intel            | Kaby Lake-U GT1 Integrated Graphi... | 9     | vgapci     | [99FFE0BF41](<Desktop/Protectli/FW/FW6/7C58F64C2AFE/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/99FFE0BF41>) |
| 8086:5906 | 8086:2212 | Intel            | Kaby Lake-U GT1 Integrated Graphi... | 9     | vgapci     | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:5916 | 8086:5916 | Intel            | HD Graphics 620                      | 9     | vgapci     | [03EE17343D](<Desktop/Thomas-Krenn.AG/LES/LES network+/07C0A5B994FF/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/03EE17343D>) |
| 8086:5917 | 8086:2212 | Intel            | UHD Graphics 620                     | 9     | vgapci     | [C68808D3B4](<Desktop/Protectli/FW/FW6/7457BA1C46B5/OPNSENSE-22.1/13.0-STABLE/AMD64/C68808D3B4>) |
| 1002:15dd | 1043:876b | AMD              | Raven Ridge [Radeon Vega Series /... | 8     | vgapci     | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1002:9616 | 1043:8388 | AMD              | RS780L [Radeon 3000]                 | 8     | vgapci     | [7E27B1BC46](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/28DD15B58DF2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/7E27B1BC46>) |
| 1002:9851 | 1734:1202 | AMD              | Mullins [Radeon R4/R5 Graphics]      | 8     | vgapci     | [C9F915399A](<Desktop/Fujitsu/FUTRO/FUTRO S930/8E025691BADB/OPNSENSE-22.1/13.0-STABLE/AMD64/C9F915399A>) |

### Infiniband (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 15b3:6274 | 15b3:6274 | Mellanox Tech... | MT25204 [InfiniHost III Lx HCA]      | 1     |            | [DF55C76E1E](<Desktop/Intel/S3000PT/S3000PT D60097-206/DD8508FCC40C/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/DF55C76E1E>) |

### Input (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 5     | emujoy     | [B7FC5EF684](<Desktop/Biostar/X470/X470GTA/2553A631F2D9/FREEBSD-13.0/13.0-RELEASE/AMD64/B7FC5EF684>) |
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 3     |            | [C3884FAC44](<Desktop/ASUSTek Computer/P8/P8B75-M/D6575EA2BF9C/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/C3884FAC44>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 166   |            | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 47    |            | [1ED23967FD](<Desktop/Others/Others/Others/C29AA24281D9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/1ED23967FD>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 29    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:a121 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 27    |            | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 18    |            | [AE4F0642FD](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/1E747FA168DD/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/AE4F0642FD>) |
| 8086:a36f | 1043:8694 | Intel            | Cannon Lake PCH Shared SRAM          | 18    |            | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 8086:19de | 8086:7270 | Intel            | Atom Processor C3000 Series Power... | 14    |            | [2A3867A849](<Desktop/Others/Others/Others/E4DAE6013BC8/OPNSENSE-22.1/13.0-STABLE/AMD64/2A3867A849>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 14    |            | [29FA6BEF41](<Desktop/Others/Others/Others/C96AE51A5D9A/OPNSENSE-22.1/13.0-STABLE/AMD64/29FA6BEF41>) |
| 8086:a2a1 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family Po... | 13    |            | [2727A8E439](<Desktop/Gigabyte Technology/H270-Gaming/H270-Gaming 3/92E92186ABE5/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2727A8E439>) |
| 8086:a121 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [7987A8B851](<Desktop/Gigabyte Technology/H110/H110M-S2H/DC0C8E934748/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/7987A8B851>) |
| 8086:a2a1 | 1849:a2a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 11    |            | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 8086:a36f | 1849:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 11    |            | [44FD3CD83C](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.1/13.0-STABLE/AMD64/44FD3CD83C>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:a121 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [D7ADCA8CAC](<Desktop/NetCom IT/pczB/pczB1116/0CB716CAF1D6/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/D7ADCA8CAC>) |
| 8086:a121 | 1849:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [5C58D01F2D](<Desktop/ASRock/H110/H110M-ITX/D5B0B257B774/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5C58D01F2D>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 9     |            | [346C445C21](<Desktop/MSI/CML-U/CML-U PRO Cubi 5/CF9C6401E02D/OPNSENSE-22.1.2/13.0-STABLE/AMD64/346C445C21>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 9     |            | [AFA675E7A7](<Desktop/Gigabyte Technology/H470/H470 HD3/15B827E9B70C/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/AFA675E7A7>) |
| 8086:a121 | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [86B6B8373C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/0E7724AD506F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/86B6B8373C>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [1C45CD1B45](<Desktop/Others/Others/Others/097BA985D9D0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/1C45CD1B45>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 7     |            | [C81D79BBE7](<Desktop/ASRock/H570/H570M-ITX-ac/707C9EE26C47/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C81D79BBE7>) |
| 8086:43ef | 1043:8694 | Intel            | Tiger Lake-H Shared SRAM             | 7     |            | [4E352AE90E](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-E/32F7ED74CFA8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4E352AE90E>) |
| 8086:a121 | 1028:06bb | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [4B1A5F0AB0](<Desktop/Dell/OptiPlex/OptiPlex 3040/52B86D78970C/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/4B1A5F0AB0>) |
| 8086:a121 | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [6BAEAF5D48](<Desktop/Dell/OptiPlex/OptiPlex 7040/481FC557306C/OPNSENSE-22.1.1/13.0-STABLE/AMD64/6BAEAF5D48>) |
| 8086:a121 | 1028:06ba | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [0072834141](<Desktop/Dell/OptiPlex/OptiPlex 5040/7E980BAD0CDC/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/0072834141>) |
| 8086:a121 | 103c:8169 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [F449B4CD6C](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/12A699DD3987/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F449B4CD6C>) |
| 8086:a1a1 | 15d9:0986 | Intel            | C620 Series Chipset Family Power ... | 6     |            | [18576EF86C](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/199DE71C8C4A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/18576EF86C>) |
| 8086:06ef | 1849:06ef | Intel            | Comet Lake PCH Shared SRAM           | 5     |            | [F56CDD9FEA](<Desktop/ASRock/H470/H470M-ITX-ac/CE2789C7FDFA/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/F56CDD9FEA>) |
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 5     |            | [6AEB9ADADB](<Desktop/Supermicro/SYS-5019/SYS-5019A-FTN4/5520EE91D944/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6AEB9ADADB>) |
| 8086:a121 | 103c:805d | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [629FF57837](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 SFF/D284171DD296/OPNSENSE-22.1.2/13.0-STABLE/AMD64/629FF57837>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [566FD652E7](<Desktop/Others/Others/Others/676B0F8582A3/OPNSENSE-22.1.1/13.0-STABLE/AMD64/566FD652E7>) |
| 8086:a3a1 | 1043:8694 | Intel            | Cannon Lake PCH Power Management ... | 5     |            | [1DAFDCC71A](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-A/9F70D0828451/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1DAFDCC71A>) |
| 8086:a3a1 | 1849:a3a1 | Intel            | Cannon Lake PCH Power Management ... | 5     |            | [B6D242A90E](<Desktop/ASRock/B460/B460M-ITX-ac/0A0BCA0A718C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B6D242A90E>) |
| 10de:03e2 | 1849:03e2 | Nvidia           | MCP61 Host Bridge                    | 4     |            | [5D447C8FCF](<Desktop/ASRock/N68-VS3/N68-VS3 FX/299EFDF3CF4A/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/5D447C8FCF>) |
| 10de:03f5 | 1849:03eb | Nvidia           | MCP61 Memory Controller              | 4     |            | [5D447C8FCF](<Desktop/ASRock/N68-VS3/N68-VS3 FX/299EFDF3CF4A/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/5D447C8FCF>) |
| 8086:06ef | 1028:09aa | Intel            | Comet Lake PCH Shared SRAM           | 4     |            | [456B55DE38](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243/OPNSENSE-22.1.3/13.0-STABLE/AMD64/456B55DE38>) |
| 8086:a121 | 1028:07c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [4503BC72FA](<Desktop/Dell/PowerEdge/PowerEdge T30/9D60EB15AE00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/4503BC72FA>) |
| 8086:a2a1 | 103c:8299 | Intel            | 200 Series/Z370 Chipset Family Po... | 4     |            | [6876D2D37D](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/BB03C210EA63/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6876D2D37D>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 4     |            | [A2C59D02EE](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/EBD53B4A056D/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A2C59D02EE>) |
| 8086:a121 | 103c:802e | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [E23B3E314A](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/B4C9208C5643/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/E23B3E314A>) |
| 8086:a121 | 1297:4038 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [5FD212645C](<Desktop/Shuttle/DH/DH170/19748D970675/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5FD212645C>) |
| 8086:a2a1 | 1028:07a2 | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [2AC306B67F](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2AC306B67F>) |
| 8086:a2a1 | 103c:82b4 | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [82F060C834](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G3 SFF/EFD4A07E16D3/OPNSENSE-22.1.1/13.0-STABLE/AMD64/82F060C834>) |
| 8086:a2a1 | 1043:872f | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [8A9387C5DA](<Desktop/ASUSTek Computer/ROG/ROG Maximus X FORMULA/CBA76DD75546/FREEBSD-13.0/13.0-RELEASE/AMD64/8A9387C5DA>) |
| 8086:a2a1 | 1565:3114 | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [0C059BAB3F](<Desktop/Biostar/B365/B365MHC/4BED88A6E1AC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/0C059BAB3F>) |
| 8086:a3a1 | 103c:8768 | Intel            | Cannon Lake PCH Power Management ... | 3     |            | [65FBD31DA1](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/5416334E31EB/OPNSENSE-22.1/13.0-STABLE/AMD64/65FBD31DA1>) |
| 10de:0270 | 1043:81c0 | Nvidia           | MCP51 Host Bridge                    | 2     |            | [DAE16641BB](<Desktop/ASUSTek Computer/M2/M2NPV-MX/14DC624B8825/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/DAE16641BB>) |
| 10de:027e | 10de:027e | Nvidia           | C51 Memory Controller 2              | 2     |            | [C183BDD5AF](<Desktop/Others/Others/Others/D686EDC3BBCE/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/C183BDD5AF>) |
| 10de:027f | 10de:027f | Nvidia           | C51 Memory Controller 3              | 2     |            | [C183BDD5AF](<Desktop/Others/Others/Others/D686EDC3BBCE/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/C183BDD5AF>) |
| 10de:02f8 | 10de:02f8 | Nvidia           | C51 Memory Controller 5              | 2     |            | [C183BDD5AF](<Desktop/Others/Others/Others/D686EDC3BBCE/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/C183BDD5AF>) |
| 10de:02f9 | 10de:02f9 | Nvidia           | C51 Memory Controller 4              | 2     |            | [C183BDD5AF](<Desktop/Others/Others/Others/D686EDC3BBCE/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/C183BDD5AF>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 14    |            | [C4AA8D3B10](<Desktop/Protectli/FW/FW6/E40CCA659EE8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C4AA8D3B10>) |
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 12    |            | [2D1BF5A79A](<Desktop/BESSTAR Tech/HM/HM90/1F0A034DBC90/OPNSENSE-22.1.1/13.0-STABLE/AMD64/2D1BF5A79A>) |
| 1022:15e2 | 1849:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 6     |            | [F80D11C4A6](<Desktop/ASRock/4X4-4000/4X4-4000 Series/FF0DB8636C47/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F80D11C4A6>) |
| 1022:15e2 | 103c:8433 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [5A242D9C9E](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0CFBD160A1EE/FREEBSD-12.2/12.2-RELEASE/AMD64/5A242D9C9E>) |
| 1022:15e2 | 1458:1000 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [817CB3E603](<Desktop/Gigabyte Technology/BSRE/BSRE-1605/493093EBE60A/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/817CB3E603>) |
| 1022:15e2 | 17aa:318e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [115F2C7B35](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75t Gen 2 11KECTO1WW/85187679911A/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/115F2C7B35>) |
| 1022:15e2 | 17aa:3728 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [7BA1CCC40D](<Desktop/Lenovo/IdeaCentre/IdeaCentre 5 14ARE05 90Q30008US/2ECD21E7A105/FREEBSD-12.2-P8/12.2-RELEASE-P8/AMD64/7BA1CCC40D>) |
| 1131:7130 |           | Philips Semic... | SAA7130 Video Broadcast Decoder      | 1     |            | [C6DA80D54B](<Desktop/Gigabyte Technology/H61/H61M-D2P-B3/BC7CD91E287F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C6DA80D54B>) |
| 1131:7133 | 1043:4876 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 1     |            | [F521976730](<Desktop/ASUSTek Computer/M3A78/M3A78 PRO/F18AAB4E7AFE/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/F521976730>) |
| 1131:7133 | 16be:0010 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 1131:7146 | 13c2:101a | Philips Semic... | SAA7146                              | 1     |            | [8CF113AC55](<Desktop/ASUSTek Computer/V-P7/V-P7H55E/0AE0678A444E/NOMADBSD-5806F915/13.0-RELEASE/AMD64/8CF113AC55>) |
| 1131:7160 | 1043:48b5 | Philips Semic... | SAA7160                              | 1     |            | [5FE1A9E521](<Desktop/ASUSTek Computer/P7H55-M/P7H55-M LX/B84E7E871D43/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/5FE1A9E521>) |
| 1131:7160 | 1461:2655 | Philips Semic... | SAA7160                              | 1     |            | [13371B2AB8](<Desktop/Gigabyte Technology/Z370/Z370 AORUS ULTRAGAMING WIFI-OP/7CB030D59E17/NOMADBSD-5806F915/13.0-RELEASE/AMD64/13371B2AB8>) |
| 1131:7231 | 1461:180f | Philips Semic... | SAA7231                              | 1     |            | [1D2E9E175C](<Desktop/Gateway/DX/DX4840/E79C6FD7005F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/1D2E9E175C>) |
| 14f1:8802 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 14f1:8804 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 14f1:8811 | 0070:3401 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [1BC05B5951](<Desktop/Dell/Precision/Precision WorkStation T3400/ADEEA3484D9F/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1BC05B5951>) |
| 14f1:8811 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [380B54B271](<Desktop/AMI/PA_1900/PA_1900SL/619CDF31C1E6/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/380B54B271>) |
| 8086:0f38 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [0C6C98CBD3](<Desktop/Silicom/Minnowboard/Minnowboard Turbot D0-D1 PLATFORM/0EBCE3D07DDB/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/0C6C98CBD3>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [688C95BDA6](<Desktop/Radxa/ROCK/ROCK Pi X/A5A9E33E38CF/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/688C95BDA6>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B9F23EE753](<Desktop/AZW/BT3/BT3 X/F6FE61B4FFA6/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/B9F23EE753>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 103   | em         | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 62    | igb        | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 53    | re         | [A58B9A4F8F](<Desktop/Pegatron/IPM41/IPM41-D3/38C292CE2082/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A58B9A4F8F>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 44    | igb        | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 35    | re         | [D3596DFF89](<Desktop/ASRock/X570/X570 PG Velocita/A90551D8040B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D3596DFF89>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 35    | igb        | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:10bc | 103c:704b | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 30    | em         | [4503BC72FA](<Desktop/Dell/PowerEdge/PowerEdge T30/9D60EB15AE00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/4503BC72FA>) |
| 8086:1521 | 8086:5001 | Intel            | I350 Gigabit Network Connection      | 29    | igb        | [456B55DE38](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243/OPNSENSE-22.1.3/13.0-STABLE/AMD64/456B55DE38>) |
| 8086:105e | 8086:125e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 28    | em         | [10A235FE8F](<Desktop/Intel/DH67BL/DH67BL AAG10189-211/E50082B9AB3B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/10A235FE8F>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 28    | em         | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 8086:150e | 103c:1780 | Intel            | 82580 Gigabit Network Connection     | 27    | igb        | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 25    | re         | [0F75361707](<Desktop/Dell/OptiPlex/OptiPlex 755/EA117E39981F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F75361707>) |
| 8086:1521 |           | Intel            | I350 Gigabit Network Connection      | 25    | igb        | [A2C59D02EE](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/EBD53B4A056D/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A2C59D02EE>) |
| 8086:10e8 | 8086:a02c | Intel            | 82576 Gigabit Network Connection     | 23    | igb        | [B7A03A99A8](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G4 SFF/0475C8F7BA1E/OPNSENSE-22.1/13.0-STABLE/AMD64/B7A03A99A8>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 22    | igb        | [B10F6655D9](<Desktop/Supermicro/SYS-5019/SYS-5019A-12TN4/7A7906FED7DA/FREEBSD-12.1-P22-HBSD/12.1-RELEASE-P22-HBSD/AMD64/B10F6655D9>) |
| 10ec:8168 | 1734:11ff | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 21    | re         | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 8086:15b8 | 1043:8672 | Intel            | Ethernet Connection (2) I219-V       | 21    | em         | [A780A7BAB2](<Desktop/ASUSTek Computer/Maximus/Maximus VIII HERO/734460839920/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A780A7BAB2>) |
| 8086:10bc | 8086:11bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 19    | em         | [40407EBFEA](<Desktop/MSI/MS/MS-7995/08A5DC59F2E9/OPNSENSE-22.1.1/13.0-STABLE/AMD64/40407EBFEA>) |
| 10ec:8169 | 10ec:8169 | Realtek Semic... | RTL8169 PCI Gigabit Ethernet Cont... | 18    | re         | [8751A2776E](<Desktop/Lenovo/ThinkCentre/ThinkCentre M58 7360BB6/5E4FCFF7F285/OPNSENSE-22.1/13.0-STABLE/AMD64/8751A2776E>) |
| 10ec:8168 | 1028:0612 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | re         | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:10c9 | 8086:a02f | Intel            | 82576 Gigabit Network Connection     | 17    | igb        | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 8086:1502 | 15d9:1502 | Intel            | 82579LM Gigabit Network Connectio... | 17    | em         | [042C1EFAC3](<Desktop/Supermicro/X9/X9SCL-X9SCM/7A7B84FA155C/OPNSENSE-22.7/13.0-STABLE/AMD64/042C1EFAC3>) |
| 8086:15b8 | 1849:15b8 | Intel            | Ethernet Connection (2) I219-V       | 15    | em         | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 8086:27dc | 8086:27dc | Intel            | NM10/ICH7 Family LAN Controller      | 14    | fxp        | [DED64258B4](<Desktop/Others/Others/Others/96A056EA1F97/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/DED64258B4>) |
| 8086:10d6 | 8086:145a | Intel            | 82575GB Gigabit Network Connection   | 13    | igb        | [A6ABB45607](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8S16X0J/968E3838A942/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A6ABB45607>) |
| 8086:1502 | 103c:3397 | Intel            | 82579LM Gigabit Network Connectio... | 13    | em         | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:153a | 103c:1998 | Intel            | Ethernet Connection I217-LM          | 13    | em         | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:153b | 1458:e000 | Intel            | Ethernet Connection I217-V           | 13    | em         | [3CCD5EACE4](<Desktop/Gigabyte Technology/H97/H97N-WIFI/4343EFE08349/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/3CCD5EACE4>) |
| 8086:15e4 |           | Intel            | Ethernet Connection X553 1GbE        | 13    | ix         | [CF4C3DFC20](<Desktop/AppNeta/m/m50/CF8F3F92A2DF/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/CF4C3DFC20>) |
| 8086:107d | 8086:1082 | Intel            | 82572EI Gigabit Ethernet Controll... | 12    | em         | [A488C9AF25](<Desktop/Dell/OptiPlex/OptiPlex 7010/78AA11104573/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A488C9AF25>) |
| 8086:10bc | 8086:10bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 12    | em         | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 8086:156f |           | Intel            | Ethernet Connection I219-LM          | 12    | em         | [11D762AD87](<Desktop/Shuttle/DS77/DS77U/2528D5D211E8/OPNSENSE-22.1/13.0-STABLE/AMD64/11D762AD87>) |
| 14e4:165b | 103c:705d | Broadcom         | NetXtreme BCM5723 Gigabit Etherne... | 11    | bge        | [B62251041B](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.2-P11/12.3-RELEASE/AMD64/B62251041B>) |
| 8086:1503 | 1043:849c | Intel            | 82579V Gigabit Network Connection    | 11    | em         | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:1528 | 8086:0001 | Intel            | Ethernet Controller 10-Gigabit X5... | 11    | ix         | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 10ec:8168 | 1028:04f5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | re         | [CB96E68E6E](<Desktop/Dell/OptiPlex/OptiPlex 390/172FACB3F264/OPNSENSE-22.1.1/13.0-STABLE/AMD64/CB96E68E6E>) |
| 10ec:8168 | 1043:83a3 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | re         | [72630C073D](<Desktop/ASUSTek Computer/P7H55-M/P7H55-M LX/818BC17C0294/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/72630C073D>) |
| 10ec:8168 | 1565:2312 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | re         | [33B05FC05A](<Desktop/Biostar/A68/A68N-5545/AAB9B849BF92/OPNSENSE-22.1.2/13.0-STABLE/AMD64/33B05FC05A>) |
| 8086:10c9 | 8086:a03c | Intel            | 82576 Gigabit Network Connection     | 10    | igb        | [7AAC0F4B94](<Desktop/ASRock/B75M/B75M R2.0/EA264E2F9554/OPNSENSE-22.1.2/13.0-STABLE/AMD64/7AAC0F4B94>) |
| 8086:1516 | 8086:12b2 | Intel            | 82580 Gigabit Network Connection     | 10    | igb        | [895AEDC31F](<Desktop/Seneca/pro/pro379410/AAD39B96E388/OPNSENSE-22.1/13.0-STABLE/AMD64/895AEDC31F>) |
| 8086:1521 | 1dcf:0309 | Intel            | I350 Gigabit Network Connection      | 10    | igb        | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:153a | 103c:18e7 | Intel            | Ethernet Connection I217-LM          | 10    | em         | [2390011492](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/97D90373AEB4/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/2390011492>) |
| 8086:1572 |           | Intel            | Ethernet Controller X710 for 10Gb... | 10    | ixl        | [1ED23967FD](<Desktop/Others/Others/Others/C29AA24281D9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/1ED23967FD>) |
| 8086:15a1 | 1043:85c4 | Intel            | Ethernet Connection (2) I218-V       | 10    | em         | [84D7FB3F1E](<Desktop/ASUSTek Computer/All/All Series/46CAE9B0FE93/GHOSTBSD-22.01.28/13.0-STABLE/AMD64/84D7FB3F1E>) |
| 8086:15b7 | 103c:8053 | Intel            | Ethernet Connection (2) I219-LM      | 10    | em         | [86B6B8373C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/0E7724AD506F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/86B6B8373C>) |
| 10ec:8168 | 1734:11c0 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | re         | [57E2086302](<Desktop/Fujitsu/FUTRO/FUTRO S900/6728260A56FF/OPNSENSE-22.1.1/13.0-STABLE/AMD64/57E2086302>) |
| 10ec:8168 | 17aa:3098 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | re         | [48DFDCF313](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10AU003DUK/BA63A6683747/OPNSENSE-22.1.3/13.0-STABLE/AMD64/48DFDCF313>) |
| 8086:10c9 | 1dcf:0319 | Intel            | 82576 Gigabit Network Connection     | 9     | igb        | [BF3238A37A](<Desktop/ASRock/H97M/H97M Pro4/45C5EA8AF26A/OPNSENSE-22.1/13.0-STABLE/AMD64/BF3238A37A>) |
| 8086:1539 | 1297:4057 | Intel            | I211 Gigabit Network Connection      | 9     | igb        | [1BB8118ACD](<Desktop/Shuttle/DH/DH370/119ED6965086/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/1BB8118ACD>) |
| 8086:153a | 17aa:30a3 | Intel            | Ethernet Connection I217-LM          | 9     | em         | [EDDEB5C246](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AAA0WGUK/A53CA903F1D9/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/EDDEB5C246>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 64    | iwlwifi    | [B23AB09F52](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/B23AB09F52>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 27    | iwm        | [B6D242A90E](<Desktop/ASRock/B460/B460M-ITX-ac/0A0BCA0A718C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B6D242A90E>) |
| 168c:002a | 168c:3099 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 18    | ath        | [D08DA1541A](<Desktop/Others/Others/Others/F95318B57CEC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D08DA1541A>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 14    | iwm        | [D8F0949991](<Desktop/Dell/OptiPlex/OptiPlex 9020/76964B2E7E4F/OPNSENSE-22.1/13.0-STABLE/AMD64/D8F0949991>) |
| 8086:31dc | 8086:0034 | Intel            | Gemini Lake PCH CNVi WiFi            | 12    | iwm        | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 10    | ath        | [5C8F3708B1](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/EA7F2653211E/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/5C8F3708B1>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 10    | iwm        | [3CCD5EACE4](<Desktop/Gigabyte Technology/H97/H97N-WIFI/4343EFE08349/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/3CCD5EACE4>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 10    | iwm        | [F449B4CD6C](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/12A699DD3987/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F449B4CD6C>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 9     | iwm        | [5E980B75BC](<Desktop/Gigabyte Technology/GB-BACE/GB-BACE-3150/B48405EE0C5D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5E980B75BC>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 8     | ath        | [84D7FB3F1E](<Desktop/ASUSTek Computer/All/All Series/46CAE9B0FE93/GHOSTBSD-22.01.28/13.0-STABLE/AMD64/84D7FB3F1E>) |
| 168c:003c |           | Qualcomm Atheros | QCA986x/988x 802.11ac Wireless Ne... | 8     |            | [C2B05FC937](<Desktop/PC Engines/APU/APU2/59362430025E/OPNSENSE-22.1/13.0-STABLE/AMD64/C2B05FC937>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 8     | iwm        | [37A7A11604](<Desktop/AZW/GK/GK55/20D5EB09357F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/37A7A11604>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 7     |            | [65FBD31DA1](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/5416334E31EB/OPNSENSE-22.1/13.0-STABLE/AMD64/65FBD31DA1>) |
| 10ec:c821 | 1a3b:3043 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 6     |            | [1300217458](<Desktop/Shuttle/DS10/DS10U/578D3382155D/OPNSENSE-22.1.1/13.0-STABLE/AMD64/1300217458>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 6     | iwm        | [09F27A0F23](<Desktop/PC Engines/apu/apu4/CC94DC88ED7C/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/09F27A0F23>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 6     | iwm        | [D377E06101](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/4AD30B4CEDEC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D377E06101>) |
| 10ec:8821 | 1a3b:216a | Realtek Semic... | RTL8821AE 802.11ac PCIe Wireless ... | 5     |            | [B1C784D41A](<Desktop/Thomas-Krenn.AG/LES/LES network/56DBE8BE7C78/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/B1C784D41A>) |
| 10ec:b822 | 1043:8746 | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 5     |            | [936AFA4DE3](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z370-E GAMING/DABD658BAA97/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/936AFA4DE3>) |
| 14e4:4359 | 14e4:05e2 | Broadcom         | BCM43228 802.11a/b/g/n               | 5     |            | [B9560EC339](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/5952C3D21999/OPNSENSE-22.1.1/13.0-STABLE/AMD64/B9560EC339>) |
| 168c:002a | 103c:3041 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 5     | ath        | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 5     | iwm        | [0A36D71DB1](<Desktop/MACHINIST/X99-k9/X99-k9 V2.0/9BE4E7CB5DC7/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/0A36D71DB1>) |
| 10ec:b723 | 1a3b:2159 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 4     |            | [64707B8717](<Desktop/NU591/1/1.0/686FE3922C3C/OPNSENSE-22.1/13.0-STABLE/AMD64/64707B8717>) |
| 14e4:4353 | 14e4:04d8 | Broadcom         | BCM43224 802.11a/b/g/n               | 4     | bwn_pci    | [7CF18A3149](<Desktop/Others/Others/Others/9C1FA0201E13/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/7CF18A3149>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 4     | ath        | [4774A3BC2F](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/D5565FC249CA/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4774A3BC2F>) |
| 168c:002d | 168c:0300 | Qualcomm Atheros | AR9227 Wireless Network Adapter      | 4     | ath        | [3E8940224F](<Desktop/Toshiba/EQUIUM/EQUIUM 3200M/42F754B5635F/FREEBSD-13.0-P2/13.0-RELEASE-P1/I386/3E8940224F>) |
| 168c:0030 | 10cf:16a8 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 4     | ath        | [8D9829BABC](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/4558F6AA9DFB/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/8D9829BABC>) |
| 168c:0032 | 103c:1838 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 4     | ath        | [E90D968312](<Desktop/ASRock/B450M/B450M Pro4/8123071B0896/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/E90D968312>) |
| 168c:0032 | 1043:850d | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 4     | ath        | [6CEEE057D4](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PRO/53775680EBED/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6CEEE057D4>) |
| 8086:0082 | 8086:1301 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 4     | iwn        | [DC60A8DECE](<Desktop/Fujitsu/ESPRIMO/ESPRIMO Q900/F362B3D3880C/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/DC60A8DECE>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 4     | iwm        | [E64118D206](<Desktop/ECS/LIVA/LIVA Z/F2B17541E780/OPNSENSE-22.1/13.0-STABLE/AMD64/E64118D206>) |
| 10ec:8176 | 10ec:8175 | Realtek Semic... | RTL8188CE 802.11b/g/n WiFi Adapter   | 3     | rtwn       | [0D40B0F9EB](<Desktop/Shuttle/XS35/XS35V3/463A73A74C81/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/0D40B0F9EB>) |
| 10ec:8179 | 10ec:8197 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 3     | rtwn       | [BC3B65334E](<Desktop/Fujitsu/D3220/D3220-A1/B41A6D05B8D8/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/BC3B65334E>) |
| 10ec:8821 | 1043:85b4 | Realtek Semic... | RTL8821AE 802.11ac PCIe Wireless ... | 3     |            | [4D02A33FEC](<Desktop/ASUSTek Computer/VM/VM62/27F93FA76BBB/HELLOSYSTEM-0.5.0/12.1-RELEASE/AMD64/4D02A33FEC>) |
| 10ec:b822 | 103c:831b | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 3     |            | [F0D279747F](<Desktop/Hewlett-Packard/Pavilion/Pavilion Gaming Desktop 690-00xx/616D90CB5938/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/F0D279747F>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 3     |            | [4EE7DE3597](<Desktop/T-bao/MINI/MINI PC/2285C96C331C/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/4EE7DE3597>) |
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 3     | bwn_pci    | [E5043F0AF4](<Desktop/Apple/MacPro5/MacPro5,1/6FE9DFD8B0C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E5043F0AF4>) |
| 14e4:43a0 | 106b:0111 | Broadcom         | BCM4360 802.11ac Wireless Network... | 3     |            | [64999A24C1](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/8E66D9ACD9E5/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/64999A24C1>) |
| 14e4:43b1 | 1043:85ba | Broadcom         | BCM4352 802.11ac Wireless Network... | 3     |            | [67080049C6](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 TWR/43A679AEDAD3/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/67080049C6>) |
| 168c:0030 | 168c:3116 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 3     | ath        | [D7BCDF16F2](<Desktop/ONELAN/NDIS/NDIS B322/7A0E877E2E3A/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D7BCDF16F2>) |
| 168c:0032 | 168c:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 3     | ath        | [E24F67A603](<Desktop/ASUSTek Computer/All/All Series/31D45A2CD212/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/E24F67A603>) |
| 1814:539b | 103c:18ed | Ralink           | RT5390R 802.11bgn PCIe Wireless N... | 3     | ral        | [D30B2629EB](<Desktop/Hewlett-Packard/Pro/Pro 3500 Series/9A7085B150C2/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D30B2629EB>) |
| 8086:088e | 8086:4060 | Intel            | Centrino Advanced-N 6235             | 3     | iwn        | [61ACC33619](<Desktop/Intel/D54250WYK/D54250WYK H13922-304/0D192CE1B155/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/61ACC33619>) |
| 8086:0895 | 8086:0222 | Intel            | Centrino Wireless-N 105              | 3     | iwn        | [00A423476F](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93 10A4-A00DGE/0949A51FD79F/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/00A423476F>) |
| 8086:24f3 | 8086:0010 | Intel            | Wireless 8260                        | 3     | iwm        | [BC9DC27F58](<Desktop/MSI/MS-7/MS-7A72/9EDDE6119A60/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/BC9DC27F58>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 3     |            | [C9E43A99BD](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/1A4A0F02E058/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/C9E43A99BD>) |
| 8086:3165 | 8086:4410 | Intel            | Wireless 3165                        | 3     | iwm        | [5426AB5339](<Desktop/Dell/Inspiron/Inspiron 3880/2697DA2D36E5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5426AB5339>) |
| 10ec:8178 | 10ec:8178 | Realtek Semic... | RTL8192CE PCIe Wireless Network A... | 2     | rtwn       | [C729F82F4C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M720s 10SUS4WT00/F6ADF227305E/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C729F82F4C>) |
| 10ec:8179 | 1a3b:219a | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 2     | rtwn       | [11D762AD87](<Desktop/Shuttle/DS77/DS77U/2528D5D211E8/OPNSENSE-22.1/13.0-STABLE/AMD64/11D762AD87>) |
| 10ec:818b | 10ec:8196 | Realtek Semic... | RTL8192EE PCIe Wireless Network A... | 2     |            | [0902154C8E](<Desktop/ASRock/D1800/D1800M/4AB5523176BA/OPNSENSE-22.1/13.0-STABLE/AMD64/0902154C8E>) |
| 10ec:8812 | 10ec:8812 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 2     |            | [68F6EB4328](<Desktop/MSI/MS-7/MS-7C95/F962A0881828/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/68F6EB4328>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 424   | igb        | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:157b |           | Intel            | I210 Gigabit Network Connection      | 193   | igb        | [B9475ED44D](<Desktop/Protectli/FW/FW6/3EFC335326E0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/B9475ED44D>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 175   | re         | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 134   | re         | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 10ec:8168 | 1849:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 119   | re         | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 80    | em         | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 73    | em         | [53A51EC160](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/53A51EC160>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 72    | re         | [19BA4D2EE9](<Desktop/ASRock/Z77/Z77 Extreme6/929553D2B892/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19BA4D2EE9>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 70    | re         | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:153a | 1028:05a4 | Intel            | Ethernet Connection I217-LM          | 38    | em         | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 10ec:8168 | 1043:8505 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 37    | re         | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 36    | re         | [99AB8E7989](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX V2/F48FF9950A35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/99AB8E7989>) |
| 8086:150e | 8086:12a2 | Intel            | 82580 Gigabit Network Connection     | 29    | igb        | [EB936BEBDE](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/82FF1FFF56D4/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EB936BEBDE>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 29    | igb        | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 10ec:8168 | 103c:213d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 28    | re         | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 25    | igb        | [91B1EC3B93](<Desktop/Gigabyte Technology/X570/X570 I AORUS PRO WIFI/7DE2E889826B/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/91B1EC3B93>) |
| 10ec:8139 | 10ec:8139 | Realtek Semic... | RTL-8100/8101L/8139 PCI Fast Ethe... | 24    | rl         | [624B4F4DE7](<Desktop/ASRock/ConRoe1333/ConRoe1333-D667/7131BB32A319/OPNSENSE-22.1.1/13.0-STABLE/AMD64/624B4F4DE7>) |
| 10ec:8168 | 1043:8554 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 22    | re         | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 14e4:165f | 103c:2133 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 21    | bge        | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 8086:105e | 103c:7044 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 21    | em         | [4D7D8FD92B](<Desktop/Dell/Precision/Precision 3440/269F11AAE867/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D7D8FD92B>) |
| 8086:1502 | 1028:047e | Intel            | 82579LM Gigabit Network Connectio... | 21    | em         | [4B4B77D8F3](<Desktop/Dell/OptiPlex/OptiPlex 790/14F63C42DF90/OPNSENSE-22.1/13.0-STABLE/AMD64/4B4B77D8F3>) |
| 8086:1521 | 8086:0002 | Intel            | I350 Gigabit Network Connection      | 18    | igb        | [F617253042](<Desktop/WYSE/DQ/DQ Class/4143A473FC4C/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F617253042>) |
| 8086:105e | 8086:135e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 17    | em         | [8AEE77286E](<Desktop/MSI/MS/MS-7760/658E325602DE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8AEE77286E>) |
| 8086:1533 | 1849:1533 | Intel            | I210 Gigabit Network Connection      | 16    | igb        | [606D3086CE](<Desktop/ASRockRack/X470/X470D4U/2AA488105C83/OPNSENSE-22.1.2/13.0-STABLE/AMD64/606D3086CE>) |
| 11ab:4364 | 1043:81f8 | Marvell Techn... | 88E8056 PCI-E Gigabit Ethernet Co... | 15    | mskc       | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 8086:107c | 8086:1376 | Intel            | 82541PI Gigabit Ethernet Controller  | 15    | em         | [8BD32670C2](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8BD32670C2>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 15    | em         | [FE27EAC86A](<Desktop/Supermicro/X9/X9SCAA--L/7975E278700E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FE27EAC86A>) |
| 8086:105e | 8086:115e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 12    | em         | [11123031C6](<Desktop/Dell/OptiPlex/OptiPlex 7020/5EBB3A42B428/OPNSENSE-22.1/13.0-STABLE/AMD64/11123031C6>) |
| 8086:15b8 | 1458:e000 | Intel            | Ethernet Connection (2) I219-V       | 12    | em         | [9752EAE10B](<Desktop/Gigabyte Technology/B150/B150-HD3P-CF/D61C920AED27/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9752EAE10B>) |
| 8086:15bc | 1043:8672 | Intel            | Ethernet Connection (7) I219-V       | 12    | em         | [D377E06101](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/4AD30B4CEDEC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D377E06101>) |
| 10ec:8168 | 1043:859e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 11    | re         | [ABED13FD92](<Desktop/ASUSTek Computer/All/All Series/BBA636E81190/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/ABED13FD92>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 11    | ixl        | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 10ec:8125 | 1849:8125 | Realtek Semic... | RTL8125 2.5GbE Controller            | 9     | re         | [C81D79BBE7](<Desktop/ASRock/H570/H570M-ITX-ac/707C9EE26C47/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C81D79BBE7>) |
| 10ec:8168 | 1028:0585 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | re         | [9213769810](<Desktop/Dell/OptiPlex/OptiPlex 3010/678B89570748/OPNSENSE-22.1/13.0-STABLE/AMD64/9213769810>) |
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 9     | igb        | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:153b | 1043:859f | Intel            | Ethernet Connection I217-V           | 9     | em         | [280EA0618B](<Desktop/ASUSTek Computer/All/All Series/42F6F83D3AA0/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/280EA0618B>) |
| 8086:15b7 |           | Intel            | Ethernet Connection (2) I219-LM      | 9     | em         | [566FD652E7](<Desktop/Others/Others/Others/676B0F8582A3/OPNSENSE-22.1.1/13.0-STABLE/AMD64/566FD652E7>) |
| 10ec:8125 | 1458:e000 | Realtek Semic... | RTL8125 2.5GbE Controller            | 8     | re         | [A5FD383C40](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/7FCEC9A2C51B/FREEBSD-13.1-PRERELEASE/13.1-PRERELEASE/AMD64/A5FD383C40>) |
| 11ab:4320 | 1043:811a | Marvell Techn... | 88E8001 Gigabit Ethernet Controller  | 8     | skc        | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 15b3:1003 | 15b3:0055 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 8     | mlx4_core  | [C518DED272](<Desktop/ASRock/Z170M/Z170M Extreme4/9326F1E80AA0/FREEBSD-13.0/13.0-RELEASE/AMD64/C518DED272>) |
| 15b3:6750 | 15b3:0015 | Mellanox Tech... | MT26448 [ConnectX EN 10GigE, PCIe... | 8     | mlx4_core  | [B51A078BBF](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/D585E1B9E2E6/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/B51A078BBF>) |
| 1969:1091 | 1458:e000 | Qualcomm Atheros | AR8161 Gigabit Ethernet              | 8     | alc        | [759CE775C9](<Desktop/Gigabyte Technology/Z77/Z77X-UD3H/96AA96EF06C6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/759CE775C9>) |
| 10ec:8168 | 1043:82c6 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | re         | [73C62835C1](<Desktop/ASUSTek Computer/CP/CP5141/964CC69AA35D/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/73C62835C1>) |
| 14e4:165f | 103c:22e8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 7     | bge        | [502AF52245](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10/BB7614C3933F/OPNSENSE-22.1/13.0-STABLE/AMD64/502AF52245>) |
| 8086:10f6 |           | Intel            | 82574L Gigabit Network Connection    | 7     | em         | [E5043F0AF4](<Desktop/Apple/MacPro5/MacPro5,1/6FE9DFD8B0C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E5043F0AF4>) |
| 8086:10fb | 8086:0003 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 7     | ix         | [C9E43A99BD](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/1A4A0F02E058/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/C9E43A99BD>) |
| 8086:10fb | 8086:0006 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 7     | ix         | [1D6991F838](<Desktop/Dell/OptiPlex/OptiPlex 3010/BE1C5BCED74E/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/1D6991F838>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 7     | igb        | [370A1D5B35](<Desktop/AAEON/FWS/FWS-2350/9E580EC1A050/OPNSENSE-22.1.1/13.0-STABLE/AMD64/370A1D5B35>) |
| 8086:150e | 1734:11a8 | Intel            | 82580 Gigabit Network Connection     | 6     | igb        | [D5ADFCC6DA](<Desktop/Fujitsu/FUTRO/FUTRO S920/5163FE0BC7B4/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/D5ADFCC6DA>) |
| 1969:1026 | 1043:8226 | Qualcomm Atheros | AR8121/AR8113/AR8114 Gigabit or F... | 5     | ale        | [01C4A15001](<Desktop/ASUSTek Computer/P5/P5Q/FD4E063005F5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/01C4A15001>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 183   | sdhci_pci  | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 47    | sdhci_pci  | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 8086:9dc4 | 8086:7270 | Intel            | Cannon Point-LP SD Host Controller   | 19    | sdhci_pci  | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:9df5 | 8086:7270 | Intel            | BayHubTech Integrated SD controller  | 19    | sdhci_pci  | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:31d0 | 8086:7270 | Intel            | SD Host Controller                   | 15    | sdhci_pci  | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 14    | sdhci_pci  | [0051C86E4C](<Desktop/CNCTION-IAF-E3845/Others/Others/7FBC058A3FA5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0051C86E4C>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | sdhci_pci  | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:19db | 8086:7270 | Intel            | Atom Processor C3000 Series SD Ho... | 9     | sdhci_pci  | [629B185E76](<Desktop/Silicom/80300/80300-0134-g01/A09461A2F391/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/629B185E76>) |
| 1022:7806 | 1022:7806 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [E098F52D51](<Desktop/Hewlett-Packard/Pro/Pro 3405 Series/195D130691D4/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/E098F52D51>) |
| 8086:02c4 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS1: eMMC         | 3     | sdhci_pci  | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:02f5 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS3               | 3     | sdhci_pci  | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | sdhci_pci  | [6DB720018B](<Desktop/Beckhoff Automation/CBxx/CBxx63/D2340951707E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6DB720018B>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | sdhci_pci  | [A90E88F5D0](<Desktop/AAEON/UP-APL/UP-APL01/D01EC76C23AC/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/A90E88F5D0>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 3     | sdhci_pci  | [09D0D26857](<Desktop/ShenZhen MinWin Technology/3865/3865U-6L/35A56C7E9951/OPNSENSE-22.1/13.0-STABLE/AMD64/09D0D26857>) |
| 1022:7813 | 1022:7813 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [C6A85DA1D5](<Desktop/M613/G420/G420N1WNS/19C20EF0FF54/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A85DA1D5>) |
| 8086:2294 | 8086:2294 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | sdhci_pci  | [382A3E1FBB](<Desktop/Gigabyte Technology/N3150/N3150ND3V/87684C325536/OPNSENSE-22.1.2/13.0-STABLE/AMD64/382A3E1FBB>) |
| 8086:2296 | 8086:2296 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | sdhci_pci  | [382A3E1FBB](<Desktop/Gigabyte Technology/N3150/N3150ND3V/87684C325536/OPNSENSE-22.1.2/13.0-STABLE/AMD64/382A3E1FBB>) |
| 8086:a375 | 103c:843f | Intel            | 300 Series Chipset Family SD Host... | 2     | sdhci_pci  | [08EEA80F1C](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/BB719EE5E039/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/08EEA80F1C>) |
| 8086:06f5 | 103c:8767 | Intel            | 400 Series Chipset Family SD Host... | 1     | sdhci_pci  | [8BBD431806](<Desktop/Hewlett-Packard/ENVY/ENVY TE01-1xxx/A0D96827B596/MIDNIGHTBSD-2.1.1/2.1.1/AMD64/8BBD431806>) |
| 8086:0f15 | 8086:0f15 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | sdhci_pci  | [7763F089A3](<Desktop/CNCTION-IAF-E3845/Others/Others/FABA34AD5631/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/7763F089A3>) |
| 8086:2294 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [DF82F414F2](<Desktop/ZOTAC/Others/Others/A3D5AFB70F93/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/DF82F414F2>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [66D6A26E35](<Desktop/Others/Q2XX/Q2XX V1.1/FE940270A0FA/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/66D6A26E35>) |
| 8086:2296 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [66D6A26E35](<Desktop/Others/Q2XX/Q2XX V1.1/FE940270A0FA/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/66D6A26E35>) |
| 8086:31cc | 1458:1000 | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [E713E3ADEE](<Desktop/Gigabyte Technology/MZGLKBP/MZGLKBP-00/FE251359DFDD/NOMADBSD-5806F915/13.0-RELEASE/AMD64/E713E3ADEE>) |
| 8086:31d0 | 1458:1000 | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [E713E3ADEE](<Desktop/Gigabyte Technology/MZGLKBP/MZGLKBP-00/FE251359DFDD/NOMADBSD-5806F915/13.0-RELEASE/AMD64/E713E3ADEE>) |
| 8086:4dc4 |           | Intel            | Jasper Lake SCS1: eMMC Controller    | 1     | sdhci_pci  | [E788CEC5F5](<Desktop/BESSTAR Tech/JB/JB95/183ACC043B73/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E788CEC5F5>) |
| 8086:4df8 |           | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [E788CEC5F5](<Desktop/BESSTAR Tech/JB/JB95/183ACC043B73/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E788CEC5F5>) |
| 8086:5acc | 1019:9cc7 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [D091F171B7](<Desktop/ULTRATOP/C2017/C2017-LIVA-ZE/DB17C050528F/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/D091F171B7>) |
| 8086:5acc | 8086:2071 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [DEF5A082BE](<Desktop/Intel/CD1/CD1C64GK/27C02BE03675/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/DEF5A082BE>) |
| 8086:9d2d | 8086:7270 | Intel            | Sunrise Point-LP Secure Digital I... | 1     | sdhci_pci  | [34BB81770B](<Desktop/Others/SKYBAY/SKYBAY/62CD21EE080B/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/34BB81770B>) |
| 8086:a375 | 103c:843b | Intel            | 300 Series Chipset Family SD Host... | 1     | sdhci_pci  | [F0D279747F](<Desktop/Hewlett-Packard/Pavilion/Pavilion Gaming Desktop 690-00xx/616D90CB5938/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/F0D279747F>) |
| 8086:a375 | 103c:844c | Intel            | 300 Series Chipset Family SD Host... | 1     | sdhci_pci  | [FB7D8EAF5D](<Desktop/Hewlett-Packard/844/844C/26AC45136BF9/HELLOSYSTEM-0.7.0/12.2-RELEASE/AMD64/FB7D8EAF5D>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 22    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:9dc5 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 19    | ig4iic     | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:9de8 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 19    | ig4iic     | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:9de9 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 19    | ig4iic     | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 19    |            | [1ED23967FD](<Desktop/Others/Others/Others/C29AA24281D9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/1ED23967FD>) |
| 8086:a324 | 1043:8694 | Intel            | Cannon Lake PCH SPI Controller       | 18    |            | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 8086:19e0 | 8086:7270 | Intel            | Atom Processor C3000 Series SPI C... | 14    |            | [2A3867A849](<Desktop/Others/Others/Others/E4DAE6013BC8/OPNSENSE-22.1/13.0-STABLE/AMD64/2A3867A849>) |
| 8086:a324 | 1849:a324 | Intel            | Cannon Lake PCH SPI Controller       | 11    |            | [44FD3CD83C](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.1/13.0-STABLE/AMD64/44FD3CD83C>) |
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:34ab | 8086:7270 | Intel            | Ice Lake-LP Serial IO SPI Control... | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 10    |            | [6F621660DC](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6F621660DC>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 8     |            | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:22c1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | ig4iic     | [F8F7CD07ED](<Desktop/Protectli/FW2/FW2B/F0A1BF20D7FE/OPNSENSE-22.1/13.0-STABLE/AMD64/F8F7CD07ED>) |
| 8086:22c2 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | ig4iic     | [F8F7CD07ED](<Desktop/Protectli/FW2/FW2B/F0A1BF20D7FE/OPNSENSE-22.1/13.0-STABLE/AMD64/F8F7CD07ED>) |
| 8086:43a4 | 1043:8694 | Intel            | Tiger Lake-H SPI Controller          | 7     |            | [4E352AE90E](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-E/32F7ED74CFA8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4E352AE90E>) |
| 8086:43e8 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 7     | ig4iic     | [4E352AE90E](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-E/32F7ED74CFA8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4E352AE90E>) |
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 6     |            | [4E059E9162](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/4E059E9162>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 6     |            | [AFA675E7A7](<Desktop/Gigabyte Technology/H470/H470 HD3/15B827E9B70C/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/AFA675E7A7>) |
| 8086:43a4 | 1849:43a4 | Intel            | Tiger Lake-H SPI Controller          | 6     |            | [C81D79BBE7](<Desktop/ASRock/H570/H570M-ITX-ac/707C9EE26C47/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C81D79BBE7>) |
| 8086:43e9 | 1043:8694 | Intel            | 500 Series Chipset Family LPSS: I... | 6     | ig4iic     | [39B116CCFC](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-I GAMING WIFI/BB678DCF1D6F/OPNSENSE-22.1/13.0-STABLE/AMD64/39B116CCFC>) |
| 8086:9da4 | 1297:4076 | Intel            | Cannon Point-LP SPI Controller       | 6     |            | [1300217458](<Desktop/Shuttle/DS10/DS10U/578D3382155D/OPNSENSE-22.1.1/13.0-STABLE/AMD64/1300217458>) |
| 8086:a1a4 | 15d9:0986 | Intel            | C620 Series Chipset Family SPI Co... | 6     |            | [18576EF86C](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/199DE71C8C4A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/18576EF86C>) |
| 1425:5601 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 5     |            | [2AC306B67F](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2AC306B67F>) |
| 8086:06a4 | 1849:06a4 | Intel            | Comet Lake PCH SPI Controller        | 5     |            | [F56CDD9FEA](<Desktop/ASRock/H470/H470M-ITX-ac/CE2789C7FDFA/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/F56CDD9FEA>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 5     |            | [6AEB9ADADB](<Desktop/Supermicro/SYS-5019/SYS-5019A-FTN4/5520EE91D944/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6AEB9ADADB>) |
| 1425:4601 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 4     |            | [51EBC2C3FD](<Desktop/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/F7BBE9119163/OPNSENSE-22.1.2/13.0-STABLE/AMD64/51EBC2C3FD>) |
| 8086:06a4 | 1028:09aa | Intel            | Comet Lake PCH SPI Controller        | 4     |            | [456B55DE38](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243/OPNSENSE-22.1.3/13.0-STABLE/AMD64/456B55DE38>) |
| 8086:06e8 | 1028:09aa | Intel            | Comet Lake PCH Serial IO I2C Cont... | 4     | ig4iic     | [456B55DE38](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243/OPNSENSE-22.1.3/13.0-STABLE/AMD64/456B55DE38>) |
| 8086:a324 | 1297:4066 | Intel            | Cannon Lake PCH SPI Controller       | 4     |            | [1BB8118ACD](<Desktop/Shuttle/DH/DH370/119ED6965086/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/1BB8118ACD>) |
| 8086:a324 | 1590:028d | Intel            | Cannon Lake PCH SPI Controller       | 4     |            | [A2C59D02EE](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/EBD53B4A056D/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A2C59D02EE>) |
| 8086:a368 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 4     | ig4iic     | [F768F45DC2](<Desktop/ASUSTek Computer/P11C-I/P11C-I Series/D7C138E79E23/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F768F45DC2>) |
| 8086:a369 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 4     | ig4iic     | [F768F45DC2](<Desktop/ASUSTek Computer/P11C-I/P11C-I Series/D7C138E79E23/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F768F45DC2>) |
| 10de:1aed | 10de:21c4 | Nvidia           | TU116 USB Type-C UCSI Controller     | 3     |            | [044908E7C3](<Desktop/Others/Intel/Intel X79/80400A7A9964/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/044908E7C3>) |
| 8086:02c5 | 8086:7270 | Intel            | Comet Lake Serial IO I2C Host Con... | 3     | ig4iic     | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:02e8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 3     | ig4iic     | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:02e9 | 8086:7270 | Intel            | Comet Lake Serial IO I2C Host Con... | 3     | ig4iic     | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:31c8 | 8086:7270 | Intel            |                                      | 3     |            | [0DEBF023F1](<Desktop/Intel/CNCTION-IAF/CNCTION-IAF/3E6B282728C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0DEBF023F1>) |
| 8086:a324 | 1028:085b | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [BBCF2BAD96](<Desktop/Dell/OptiPlex/OptiPlex 5060/B3C627211006/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BBCF2BAD96>) |
| 8086:a324 | 1028:0871 | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [290F10C785](<Desktop/Dell/Precision/Precision 3630 Tower/703F414672AD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/290F10C785>) |
| 8086:a368 | 1028:085b | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | ig4iic     | [BBCF2BAD96](<Desktop/Dell/OptiPlex/OptiPlex 5060/B3C627211006/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BBCF2BAD96>) |
| 8086:a368 | 1028:0871 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | ig4iic     | [290F10C785](<Desktop/Dell/Precision/Precision 3630 Tower/703F414672AD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/290F10C785>) |
| 1002:73a4 | 1002:0408 | AMD              | Navi 21 USB                          | 2     |            | [C13B78E6D5](<Desktop/ASRock/X570/X570 Steel Legend WiFi ax/730F6AC9C266/MIDNIGHTBSD-2.1.2/2.1.2/AMD64/C13B78E6D5>) |
| 10de:1aed | 1462:8d95 | Nvidia           | TU116 USB Type-C UCSI Controller     | 2     |            | [79D8E655A3](<Desktop/ASRock/B550M/B550M Steel Legend/6852CF1058EA/OPNSENSE-22.1.2/13.0-STABLE/AMD64/79D8E655A3>) |
| 10de:1aed | 3842:1068 | Nvidia           | TU116 USB Type-C UCSI Controller     | 2     |            | [9959C0900A](<Desktop/ASUSTek Computer/TUF/TUF B450M-PRO GAMING/0C18EEA64EFE/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/9959C0900A>) |
| 10de:1aed | 3842:1667 | Nvidia           | TU116 USB Type-C UCSI Controller     | 2     |            | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 10ec:816c | 1849:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 2     |            | [F80D11C4A6](<Desktop/ASRock/4X4-4000/4X4-4000 Series/FF0DB8636C47/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F80D11C4A6>) |
| 1425:5603 |           | Chelsio Commu... | T540-CR Unified Wire Storage Cont... | 2     |            | [C04BBD635B](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/6457E123E761/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/C04BBD635B>) |
| 1425:5607 |           | Chelsio Commu... | T520-SO Unified Wire Storage Cont... | 2     |            | [502AF52245](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10/BB7614C3933F/OPNSENSE-22.1/13.0-STABLE/AMD64/502AF52245>) |
| 8086:06a4 | 1043:8694 | Intel            | Comet Lake PCH SPI Controller        | 2     |            | [B60A9DD4E3](<Desktop/ASUSTek Computer/PRIME/PRIME B460M-A R2.0/1C484EF0D1E5/OPNSENSE-22.1/13.0-STABLE/AMD64/B60A9DD4E3>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 106   | pchtherm   | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 58    |            | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 56    | ig4iic     | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 56    | ig4iic     | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 40    | ig4iic     | [CE3FEDCBAF](<Desktop/Others/Others/Others/7A46CAB81031/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CE3FEDCBAF>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 39    | ig4iic     | [CE3FEDCBAF](<Desktop/Others/Others/Others/7A46CAB81031/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CE3FEDCBAF>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 39    | ig4iic     | [CE3FEDCBAF](<Desktop/Others/Others/Others/7A46CAB81031/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CE3FEDCBAF>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    | ig4iic     | [CE3FEDCBAF](<Desktop/Others/Others/Others/7A46CAB81031/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CE3FEDCBAF>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 23    |            | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:1903 | 8086:7270 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 22    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:9df9 | 8086:7270 | Intel            | Cannon Point-LP Thermal Controller   | 22    | pchtherm   | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:1903 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 19    |            | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:2015 |           | Intel            | Sky Lake-E Ubox Registers            | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:204d |           | Intel            | Sky Lake-E M3KTI Registers           | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:204c |           | Intel            | Sky Lake-E M3KTI Registers           | 16    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 16    | uart       | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 16    | uart       | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 16    | uart       | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 16    |            | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 16    | uart       | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:9d31 | 8086:9d31 | Intel            | Sunrise Point-LP Thermal subsystem   | 14    | pchtherm   | [29FA6BEF41](<Desktop/Others/Others/Others/C96AE51A5D9A/OPNSENSE-22.1/13.0-STABLE/AMD64/29FA6BEF41>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | ig4iic     | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | ig4iic     | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:a379 | 1458:8888 | Intel            | Cannon Lake PCH Thermal Controller   | 13    | pchtherm   | [17B3590A3F](<Desktop/Gigabyte Technology/C246/C246-WU4/4514509F1F50/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/17B3590A3F>) |
| 8086:318c | 1849:318c | Intel            | Celeron/Pentium Silver Processor ... | 12    |            | [5A614C6238](<Desktop/ASRock/J5040/J5040-ITX/BA57FC9C5E6C/OPNSENSE-22.1/13.0-STABLE/AMD64/5A614C6238>) |
| 8086:a2b1 | 1849:a2b1 | Intel            | 200 Series PCH Thermal Subsystem     | 11    |            | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 8086:a379 | 1849:a379 | Intel            | Cannon Lake PCH Thermal Controller   | 11    | pchtherm   | [44FD3CD83C](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.1/13.0-STABLE/AMD64/44FD3CD83C>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 10    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 10    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 10    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 10    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 10    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:a131 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | pchtherm   | [D7ADCA8CAC](<Desktop/NetCom IT/pczB/pczB1116/0CB716CAF1D6/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/D7ADCA8CAC>) |
| 8086:a131 | 1849:a131 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | pchtherm   | [5C58D01F2D](<Desktop/ASRock/H110/H110M-ITX/D5B0B257B774/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5C58D01F2D>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 9     |            | [BA0AC00CF6](<Desktop/MSI/MS/MS-7885/A9957445CE5D/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/BA0AC00CF6>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 9     |            | [BA0AC00CF6](<Desktop/MSI/MS/MS-7885/A9957445CE5D/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/BA0AC00CF6>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 9     |            | [BA0AC00CF6](<Desktop/MSI/MS/MS-7885/A9957445CE5D/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/BA0AC00CF6>) |
| 8086:8c24 | 1734:11ea | Intel            | 8 Series Chipset Family Thermal M... | 9     | pchtherm   | [43BFCEB19D](<Desktop/Fujitsu/ESPRIMO/ESPRIMO P920/958E4EAD94D1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/43BFCEB19D>) |
| 8086:02f9 | 8086:7270 | Intel            | Comet Lake Thermal Subsytem          | 8     | pchtherm   | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:a131 | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | pchtherm   | [86B6B8373C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/0E7724AD506F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/86B6B8373C>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     | pchtherm   | [1C45CD1B45](<Desktop/Others/Others/Others/097BA985D9D0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/1C45CD1B45>) |
| 8086:0a03 |           | Intel            | Haswell-ULT Thermal Subsystem        | 7     |            | [B69015F0E0](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/270D70C7FD1C/OPNSENSE-22.1/13.0-STABLE/AMD64/B69015F0E0>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 7     |            | [D3894B9F37](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/845821A8075B/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/D3894B9F37>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 7     |            | [D3894B9F37](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/845821A8075B/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/D3894B9F37>) |
| 8086:3c44 |           | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 7     |            | [91F35751A8](<Desktop/Dell/Precision/Precision T3610/5E1736886C59/OPNSENSE-22.1.2/13.0-STABLE/AMD64/91F35751A8>) |
| 8086:3ce6 |           | Intel            | Xeon E5/Core i7 QuickPath Interco... | 7     |            | [91F35751A8](<Desktop/Dell/Precision/Precision T3610/5E1736886C59/OPNSENSE-22.1.2/13.0-STABLE/AMD64/91F35751A8>) |
| 8086:a131 | 1028:06bb | Intel            | 100 Series/C230 Series Chipset Fa... | 7     | pchtherm   | [4B1A5F0AB0](<Desktop/Dell/OptiPlex/OptiPlex 3040/52B86D78970C/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/4B1A5F0AB0>) |
| 8086:06f9 | 1458:8888 | Intel            | Comet Lake PCH Thermal Controller    | 6     |            | [AFA675E7A7](<Desktop/Gigabyte Technology/H470/H470 HD3/15B827E9B70C/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/AFA675E7A7>) |
| 8086:1903 | 1297:4076 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     |            | [1300217458](<Desktop/Shuttle/DS10/DS10U/578D3382155D/OPNSENSE-22.1.1/13.0-STABLE/AMD64/1300217458>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 6     | ig4iic     | [37A7A11604](<Desktop/AZW/GK/GK55/20D5EB09357F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/37A7A11604>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 195   | intsmb     | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 166   | ichsmb     | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 112   | ichsmb     | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 73    | ichsmb     | [C2B8C7EEBB](<Desktop/Others/Others/Others/40CC04883594/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C2B8C7EEBB>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 61    | ichsmb     | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 47    | ichsmb     | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 1022:790b | 1458:5001 | AMD              | FCH SMBus Controller                 | 46    | intsmb     | [A5FD383C40](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/7FCEC9A2C51B/FREEBSD-13.1-PRERELEASE/13.1-PRERELEASE/AMD64/A5FD383C40>) |
| 1022:790b | 1849:790b | AMD              | FCH SMBus Controller                 | 45    | intsmb     | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:790b | 1849:ffff | AMD              | FCH SMBus Controller                 | 41    | intsmb     | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 36    | ichsmb     | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 1022:790b | 1043:87c0 | AMD              | FCH SMBus Controller                 | 34    | intsmb     | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 8086:27da | 8086:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 34    | ichsmb     | [E41BA68AA2](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33/OPNSENSE-22.1/13.0-STABLE/AMD64/E41BA68AA2>) |
| 1022:780b | 103c:213d | AMD              | FCH SMBus Controller                 | 32    | intsmb     | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:8c22 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 32    | ichsmb     | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:8c22 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 30    | ichsmb     | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 29    | intsmb     | [606D3086CE](<Desktop/ASRockRack/X470/X470D4U/2AA488105C83/OPNSENSE-22.1.2/13.0-STABLE/AMD64/606D3086CE>) |
| 8086:283e | 8086:283e | Intel            | 82801H (ICH8 Family) SMBus Contro... | 28    | ichsmb     | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:a123 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 27    | ichsmb     | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 1022:790b | 1043:8747 | AMD              | FCH SMBus Controller                 | 25    | intsmb     | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 8086:1c22 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 25    | ichsmb     | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:1e22 | 1458:5001 | Intel            | 7 Series/C216 Chipset Family SMBu... | 25    | ichsmb     | [5B6DD82DA8](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/34CE6C299230/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5B6DD82DA8>) |
| 8086:3a30 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 25    | ichsmb     | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 1002:4385 | 1002:4385 | AMD              | SBx00 SMBus Controller               | 24    | intsmb     | [3C315D0C15](<Desktop/Gigabyte Technology/990/990FXA-UD3/30C9592F6A6C/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/3C315D0C15>) |
| 8086:1e22 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family SMBu... | 24    | ichsmb     | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:1c22 | 1458:5001 | Intel            | 6 Series/C200 Series Chipset Fami... | 23    | ichsmb     | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 8086:1c22 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 22    | ichsmb     | [042C1EFAC3](<Desktop/Supermicro/X9/X9SCL-X9SCM/7A7B84FA155C/OPNSENSE-22.7/13.0-STABLE/AMD64/042C1EFAC3>) |
| 8086:9da3 | 8086:7270 | Intel            | Cannon Point-LP SMBus Controller     | 22    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:8c22 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ichsmb     | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 1022:780b | 1734:1202 | AMD              | FCH SMBus Controller                 | 19    | intsmb     | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 8086:1e22 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family SMBu... | 19    | ichsmb     | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 18    | intsmb     | [0404FCFC3B](<Desktop/ASUSTek Computer/M5/M5A88-M/5B5ADE5E3B56/XIGMANAS-12.3-P2/12.3-RELEASE-P2/AMD64/0404FCFC3B>) |
| 1002:4385 | 1022:1510 | AMD              | SBx00 SMBus Controller               | 18    | intsmb     | [177DC1FBC8](<Desktop/PC Engines/apu/apu1/BE5B5D847307/OPNSENSE-22.1.2/13.0-STABLE/AMD64/177DC1FBC8>) |
| 1002:4385 | 1043:8389 | AMD              | SBx00 SMBus Controller               | 18    | intsmb     | [F1FE3FE225](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/9CF14B98B99F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/F1FE3FE225>) |
| 8086:5ad4 | 1849:5ad4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [3E1591E714](<Desktop/ASRock/J3455/J3455B-ITX/D479CDF18817/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E1591E714>) |
| 8086:a2a3 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family SM... | 18    | ichsmb     | [AE4F0642FD](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/1E747FA168DD/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/AE4F0642FD>) |
| 8086:a323 | 1043:8694 | Intel            | Cannon Lake PCH SMBus Controller     | 18    | ichsmb     | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 17    | ichsmb     | [A2EF313477](<Desktop/Protectli/FW/FW2/3CD419539C29/OPNSENSE-22.1.1/13.0-STABLE/AMD64/A2EF313477>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 16    | ichsmb     | [D46B68CC28](<Desktop/Intel/CARLOW/CARLOW/D91B06809068/OPNSENSE-22.1.1/13.0-STABLE/AMD64/D46B68CC28>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    |            | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 1022:790b | 1043:876b | AMD              | FCH SMBus Controller                 | 14    | intsmb     | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:0f12 | 1849:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 14    | ichsmb     | [B4142103CB](<Desktop/ASRock/Q1900/Q1900B-ITX/A58F88E6A7C3/FREEBSD-12.3-P2/12.3-RELEASE-P1/AMD64/B4142103CB>) |
| 8086:19df | 8086:7270 | Intel            | Atom Processor C3000 Series SMBus... | 14    | ichsmb     | [2A3867A849](<Desktop/Others/Others/Others/E4DAE6013BC8/OPNSENSE-22.1/13.0-STABLE/AMD64/2A3867A849>) |
| 8086:8c22 | 1849:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 14    | ichsmb     | [DA796979AC](<Desktop/ASRock/B85/B85M-ITX/C18B8CE60627/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DA796979AC>) |
| 8086:8ca2 | 1458:5001 | Intel            | 9 Series Chipset Family SMBus Con... | 14    | ichsmb     | [3CCD5EACE4](<Desktop/Gigabyte Technology/H97/H97N-WIFI/4343EFE08349/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/3CCD5EACE4>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 14    | ichsmb     | [29FA6BEF41](<Desktop/Others/Others/Others/C96AE51A5D9A/OPNSENSE-22.1/13.0-STABLE/AMD64/29FA6BEF41>) |
| 8086:1e22 | 103c:3397 | Intel            | 7 Series/C216 Chipset Family SMBu... | 13    | ichsmb     | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:8c22 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | ichsmb     | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | ichsmb     | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 8086:a2a3 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family SM... | 13    | ichsmb     | [2727A8E439](<Desktop/Gigabyte Technology/H270-Gaming/H270-Gaming 3/92E92186ABE5/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2727A8E439>) |
| 8086:a323 | 1458:5001 | Intel            | Cannon Lake PCH SMBus Controller     | 13    | ichsmb     | [17B3590A3F](<Desktop/Gigabyte Technology/C246/C246-WU4/4514509F1F50/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/17B3590A3F>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 104   | hdac       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 85    | hdac       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 55    | hdac       | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 8086:9ca0 | 8086:7270 | Intel            | Wildcat Point-LP High Definition ... | 44    | hdac       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:160c | 8086:160c | Intel            | Broadwell-U Audio Controller         | 43    | hdac       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 41    | hdac       | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 35    | hdac       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:0a0c | 8086:0a0c | Intel            | Haswell-ULT HD Audio Controller      | 33    | hdac       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 1002:9840 | 103c:213d | AMD              | Kabini HDMI/DP Audio                 | 32    | hdac       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:8c20 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset High... | 32    | hdac       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 1022:780d | 103c:213d | AMD              | FCH Azalia Controller                | 29    | hdac       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 27    | hdac       | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 8086:0c0c | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 27    | hdac       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 26    | hdac       | [0051C86E4C](<Desktop/CNCTION-IAF-E3845/Others/Others/7FBC058A3FA5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0051C86E4C>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 25    | hdac       | [CECAC43923](<Desktop/Gigabyte Technology/P85/P85-D3/6D87717FDD41/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CECAC43923>) |
| 8086:0c0c | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 23    | hdac       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:9dc8 | 8086:7270 | Intel            | Cannon Point-LP High Definition A... | 22    | hdac       | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 1002:9840 | 1734:1202 | AMD              | Kabini HDMI/DP Audio                 | 19    | hdac       | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 8086:0c0c | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 19    | hdac       | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 18    | hdac       | [A5FD383C40](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/7FCEC9A2C51B/FREEBSD-13.1-PRERELEASE/13.1-PRERELEASE/AMD64/A5FD383C40>) |
| 1002:aaf0 | 1da2:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 17    | hdac       | [1E6FF84E5D](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR VI HERO/35055183F5DC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/1E6FF84E5D>) |
| 8086:8c20 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset High... | 17    | hdac       | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 16    | hdac       | [D18945180C](<Desktop/Others/Others/Others/54F0D6CF58E8/OPNSENSE-22.1.1/13.0-STABLE/AMD64/D18945180C>) |
| 8086:1e20 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family High... | 16    | hdac       | [A488C9AF25](<Desktop/Dell/OptiPlex/OptiPlex 7010/78AA11104573/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A488C9AF25>) |
| 8086:8c20 | 1043:8576 | Intel            | 8 Series/C220 Series Chipset High... | 14    | hdac       | [26565F3D84](<Desktop/ASUSTek Computer/All/All Series/0F0FB0273B8E/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/26565F3D84>) |
| 1002:15de | 1043:876b | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 13    | hdac       | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:1487 | 1043:8797 | AMD              | Starship/Matisse HD Audio Controller | 13    | hdac       | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 8086:0c0c | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 13    | hdac       | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:1e20 | 103c:3397 | Intel            | 7 Series/C216 Chipset Family High... | 13    | hdac       | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | hdac       | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:8c20 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset High... | 13    | hdac       | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:9d70 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 13    | hdac       | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 8086:1c20 | 1458:a002 | Intel            | 6 Series/C200 Series Chipset Fami... | 12    | hdac       | [6C32638BAF](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/244EA5C23B4B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6C32638BAF>) |
| 8086:a2f0 | 1458:a182 | Intel            | 200 Series PCH HD Audio              | 12    | hdac       | [B0AEAC1EF8](<Desktop/Gigabyte Technology/H310M/H310M S2 2.0/F3C5B26117CA/FREEBSD-12.3-P1/12.3-RELEASE/AMD64/B0AEAC1EF8>) |
| 1022:15e3 | 1043:86c7 | AMD              | Family 17h/19h HD Audio Controller   | 11    | hdac       | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:0c0c | 8086:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 11    | hdac       | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 8086:1c20 | 1028:04ad | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | hdac       | [4B4B77D8F3](<Desktop/Dell/OptiPlex/OptiPlex 790/14F63C42DF90/OPNSENSE-22.1/13.0-STABLE/AMD64/4B4B77D8F3>) |
| 8086:1e20 | 1458:a002 | Intel            | 7 Series/C216 Chipset Family High... | 11    | hdac       | [5B6DD82DA8](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/34CE6C299230/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5B6DD82DA8>) |
| 1002:4383 | 1043:8445 | AMD              | SBx00 Azalia (Intel HDA)             | 10    | hdac       | [F1FE3FE225](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/9CF14B98B99F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/F1FE3FE225>) |
| 1002:ab38 | 1002:ab38 | AMD              | Navi 10 HDMI Audio                   | 10    | hdac       | [807A29112E](<Desktop/ASUSTek Computer/ROG/ROG STRIX X570-F GAMING/3EA73278F4B4/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/807A29112E>) |
| 1022:1457 | 1458:a182 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 10    | hdac       | [1DAAB68F1F](<Desktop/Gigabyte Technology/AB350M-Gaming/AB350M-Gaming 3/B7ED32E7D2CE/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/1DAAB68F1F>) |
| 1022:780d | 1022:780d | AMD              | FCH Azalia Controller                | 10    | hdac       | [E5A9FF1138](<Desktop/AMD/X/X64/8B1209E2156C/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/E5A9FF1138>) |
| 1022:780d | 1734:1203 | AMD              | FCH Azalia Controller                | 10    | hdac       | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 10de:0fb8 | 1462:8c98 | Nvidia           | GP108 High Definition Audio Contr... | 10    | hdac       | [AE2203B146](<Desktop/Dell/OptiPlex/OptiPlex 3010/B8947DA31545/NOMADBSD-5806F915/13.0-RELEASE/AMD64/AE2203B146>) |
| 8086:0c0c | 17aa:3098 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 10    | hdac       | [48DFDCF313](<Desktop/Lenovo/ThinkCentre/ThinkCentre E73 10AU003DUK/BA63A6683747/OPNSENSE-22.1.3/13.0-STABLE/AMD64/48DFDCF313>) |
| 8086:0c0c | 1849:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 10    | hdac       | [DA796979AC](<Desktop/ASRock/B85/B85M-ITX/C18B8CE60627/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DA796979AC>) |
| 8086:1c20 | 1028:047e | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | hdac       | [F4D8160D05](<Desktop/Dell/OptiPlex/OptiPlex 990/E38DB6E3EC62/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F4D8160D05>) |
| 8086:1c20 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | hdac       | [CB96E68E6E](<Desktop/Dell/OptiPlex/OptiPlex 390/172FACB3F264/OPNSENSE-22.1.1/13.0-STABLE/AMD64/CB96E68E6E>) |
| 8086:1c20 | 1028:0585 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | hdac       | [9213769810](<Desktop/Dell/OptiPlex/OptiPlex 3010/678B89570748/OPNSENSE-22.1/13.0-STABLE/AMD64/9213769810>) |
| 8086:3198 | 10ec:115a | Intel            | Celeron/Pentium Silver Processor ... | 10    | hdac       | [4C1F624666](<Desktop/Seeed Studio/ODYSSEY-X86J41X5/ODYSSEY-X86J41X5 SD-BS-CJ41G-300-101-H 07-21-2021 18:16:20/ABEA02A7130C/OPNSENSE-22.1.1/13.0-STABLE/AMD64/4C1F624666>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1283:8211 | 1283:8211 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 2     | atapci     | [BA1D9A51C2](<Desktop/Intel/Bearlake/Bearlake Bearlake Fab A/57F476905C38/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/BA1D9A51C2>) |
| 105a:4d30 | 105a:4d33 | Promise Techn... | PDC20267 (FastTrak100/Ultra100)      | 1     | atapci     | [D99AE1AAD1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX PLUS/627BCCBE6A6E/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/D99AE1AAD1>) |
| 105a:4d69 | 105a:4d68 | Promise Techn... | 20269                                | 1     | atapci     | [D2A09126C0](<Desktop/TYAN Computer/Intel/Intel 440BX-GX Rev. 4/05C7EC931544/FREEBSD-12.2-P2/12.2-RELEASE-P1/I386/D2A09126C0>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 165   | ahci       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 1022:7801 | 1022:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 123   | ahci       | [E56B256787](<Desktop/PC Engines/APU/APU2/FD5944A53320/PFSENSE-12.3-STABLE/12.3-STABLE/AMD64/E56B256787>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 112   | ahci       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 93    | ahci       | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:43c8 | 1b21:1062 | AMD              | 400 Series Chipset SATA Controller   | 80    | ahci       | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 75    | ahci       | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 61    | ahci       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 47    | ahci       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 1022:7901 | 1849:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 41    | ahci       | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1b21:0612 | 1849:0612 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 40    | ahci       | [7AAC0F4B94](<Desktop/ASRock/B75M/B75M R2.0/EA264E2F9554/OPNSENSE-22.1.2/13.0-STABLE/AMD64/7AAC0F4B94>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 36    | ahci       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 1022:7801 | 103c:213d | AMD              | FCH SATA Controller [AHCI mode]      | 32    | ahci       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 1022:7901 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 31    | ahci       | [1DAAB68F1F](<Desktop/Gigabyte Technology/AB350M-Gaming/AB350M-Gaming 3/B7ED32E7D2CE/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/1DAAB68F1F>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 30    | ahci       | [382A3E1FBB](<Desktop/Gigabyte Technology/N3150/N3150ND3V/87684C325536/OPNSENSE-22.1.2/13.0-STABLE/AMD64/382A3E1FBB>) |
| 8086:8c02 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 28    | ahci       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:a102 | 1043:8694 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 27    | ahci       | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 25    | ahci       | [177DC1FBC8](<Desktop/PC Engines/apu/apu1/BE5B5D847307/OPNSENSE-22.1.2/13.0-STABLE/AMD64/177DC1FBC8>) |
| 1022:43eb | 1b21:1062 | AMD              | 500 Series Chipset SATA Controller   | 24    | ahci       | [B23AB09F52](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/B23AB09F52>) |
| 1022:7901 | 1043:8747 | AMD              | FCH SATA Controller [AHCI mode]      | 23    | ahci       | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 8086:9dd3 | 8086:7270 | Intel            | Cannon Point-LP SATA Controller [... | 22    | ahci       | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:1e02 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 20    | ahci       | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:8c02 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ahci       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:8c02 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ahci       | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 1b21:0612 | 1043:84b7 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 19    | ahci       | [A0885F4F44](<Desktop/ASUSTek Computer/P8Z68-M/P8Z68-M PRO/38C7CD36884E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A0885F4F44>) |
| 8086:1c02 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 19    | ahci       | [042C1EFAC3](<Desktop/Supermicro/X9/X9SCL-X9SCM/7A7B84FA155C/OPNSENSE-22.7/13.0-STABLE/AMD64/042C1EFAC3>) |
| 8086:1e02 | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 19    | ahci       | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 1022:43b8 | 1b21:1062 | AMD              | FCH SATA Controller D                | 18    | ahci       | [96015C2D83](<Desktop/MSI/MS-7/MS-7C52/08517B2B3FEB/OPNSENSE-22.1/13.0-STABLE/AMD64/96015C2D83>) |
| 1022:7801 | 1734:1202 | AMD              | FCH SATA Controller [AHCI mode]      | 18    | ahci       | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 1022:7901 | 1849:ffff | AMD              | FCH SATA Controller [AHCI mode]      | 18    | ahci       | [D3596DFF89](<Desktop/ASRock/X570/X570 PG Velocita/A90551D8040B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D3596DFF89>) |
| 8086:1c02 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 18    | ahci       | [DF08E2E8F0](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/0C4455E7F2C2/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF08E2E8F0>) |
| 8086:5ae3 | 1849:5ae3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | ahci       | [3E1591E714](<Desktop/ASRock/J3455/J3455B-ITX/D479CDF18817/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E1591E714>) |
| 8086:a352 | 1043:8694 | Intel            | Cannon Lake PCH SATA AHCI Controller | 18    | ahci       | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 1022:43b7 | 1b21:1062 | AMD              | 300 Series Chipset SATA Controller   | 17    | ahci       | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:1e02 | 1458:b005 | Intel            | 7 Series/C210 Series Chipset Fami... | 17    | ahci       | [459BB6486D](<Desktop/Gigabyte Technology/Z77/Z77N-WIFI/798389D95EE6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/459BB6486D>) |
| 8086:a282 | 1043:8694 | Intel            | 200 Series PCH SATA controller [A... | 17    | ahci       | [AE4F0642FD](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/1E747FA168DD/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/AE4F0642FD>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 16    | ahci       | [A2EF313477](<Desktop/Protectli/FW/FW2/3CD419539C29/OPNSENSE-22.1.1/13.0-STABLE/AMD64/A2EF313477>) |
| 8086:1c02 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 16    | ahci       | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 8086:3a22 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 16    | ahci       | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    | ahci       | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:1c02 | 1458:b005 | Intel            | 6 Series/C200 Series Chipset Fami... | 15    | ahci       | [62F424CAC5](<Desktop/ATComputers/OFFICEPRO/OFFICEPRO 7000/EE1D9A13BDE7/FREEBSD-13.0/13.0-RELEASE/AMD64/62F424CAC5>) |
| 1002:4391 | 1043:84dd | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 14    | ahci       | [9F442754D0](<Desktop/ASUSTek Computer/M5A97/M5A97 R2.0/5CD4594C4068/FREEBSD-13.0-P5/13.0-STABLE/AMD64/9F442754D0>) |
| 8086:8c02 | 1849:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 14    | ahci       | [DA796979AC](<Desktop/ASRock/B85/B85M-ITX/C18B8CE60627/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DA796979AC>) |
| 8086:8c82 | 1458:b005 | Intel            | 9 Series Chipset Family SATA Cont... | 14    | ahci       | [3CCD5EACE4](<Desktop/Gigabyte Technology/H97/H97N-WIFI/4343EFE08349/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/3CCD5EACE4>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 14    | ahci       | [29FA6BEF41](<Desktop/Others/Others/Others/C96AE51A5D9A/OPNSENSE-22.1/13.0-STABLE/AMD64/29FA6BEF41>) |
| 8086:1e02 | 103c:3397 | Intel            | 7 Series/C210 Series Chipset Fami... | 13    | ahci       | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:8c02 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | ahci       | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 1002:4391 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 12    | ahci       | [155C7E0B49](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2/19ABD31D692B/XIGMANAS-12.3-P2/12.3-RELEASE-P2/AMD64/155C7E0B49>) |
| 1022:43b5 | 1b21:1062 | AMD              | X370 Series Chipset SATA Controller  | 12    | ahci       | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 1022:7901 | 1043:87c0 | AMD              | FCH SATA Controller [AHCI mode]      | 12    | ahci       | [9CD2758A5F](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/4E83FD0E25CF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/9CD2758A5F>) |
| 1b4b:9172 | 1458:b000 | Marvell Techn... | 88SE9172 SATA 6Gb/s Controller       | 12    | ahci       | [3C315D0C15](<Desktop/Gigabyte Technology/990/990FXA-UD3/30C9592F6A6C/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/3C315D0C15>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7800 | 1022:7800 | AMD              | FCH SATA Controller [IDE mode]       | 56    | ahci       | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:2850 | 8086:2850 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 27    | atapci     | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 24    | atapci     | [E41BA68AA2](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33/OPNSENSE-22.1/13.0-STABLE/AMD64/E41BA68AA2>) |
| 8086:2828 | 8086:2828 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 21    | atapci     | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:27c0 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 19    | atapci     | [E41BA68AA2](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33/OPNSENSE-22.1/13.0-STABLE/AMD64/E41BA68AA2>) |
| 1002:439c | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 18    | atapci     | [F1FE3FE225](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/9CF14B98B99F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/F1FE3FE225>) |
| 1002:439c | 1458:5002 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 14    | atapci     | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 8086:27df | 1043:8179 | Intel            | 82801G (ICH7 Family) IDE Controller  | 12    | atapci     | [99AB8E7989](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX V2/F48FF9950A35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/99AB8E7989>) |
| 1002:4390 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 10    | ahci       | [F1FE3FE225](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/9CF14B98B99F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/F1FE3FE225>) |
| 8086:1c00 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | atapci     | [CB96E68E6E](<Desktop/Dell/OptiPlex/OptiPlex 390/172FACB3F264/OPNSENSE-22.1.1/13.0-STABLE/AMD64/CB96E68E6E>) |
| 8086:1c08 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | atapci     | [CB96E68E6E](<Desktop/Dell/OptiPlex/OptiPlex 390/172FACB3F264/OPNSENSE-22.1.1/13.0-STABLE/AMD64/CB96E68E6E>) |
| 8086:27c0 | 1043:8179 | Intel            | NM10/ICH7 Family SATA Controller ... | 10    | atapci     | [99AB8E7989](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX V2/F48FF9950A35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/99AB8E7989>) |
| 1002:439c | 1849:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 9     | atapci     | [BBB1E3EA53](<Desktop/ASRock/C70/C70M1/590935D8F1B7/OPNSENSE-22.1/13.0-STABLE/AMD64/BBB1E3EA53>) |
| 8086:27c0 | 1458:b002 | Intel            | NM10/ICH7 Family SATA Controller ... | 9     | atapci     | [5A22BB6991](<Desktop/Gigabyte Technology/G31/G31M-ES2C/9E562482276E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5A22BB6991>) |
| 8086:3a20 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 9     | atapci     | [5999E0EBFB](<Desktop/ASUSTek Computer/P5P43TD/P5P43TD PRO/CAA935C7EB09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5999E0EBFB>) |
| 8086:3a26 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 9     | atapci     | [5999E0EBFB](<Desktop/ASUSTek Computer/P5P43TD/P5P43TD PRO/CAA935C7EB09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5999E0EBFB>) |
| 8086:29b6 | 1028:0211 | Intel            | 82Q35 Express PT IDER Controller     | 8     | atapci     | [0F75361707](<Desktop/Dell/OptiPlex/OptiPlex 755/EA117E39981F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F75361707>) |
| 1002:4390 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 7     | ahci       | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 1106:0415 | 1043:838f | VIA Technologies | VT6415 PATA IDE Host Controller      | 7     | atapci     | [D789A35C01](<Desktop/ASUSTek Computer/P8H67-M/P8H67-M PRO/0477E4056673/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/D789A35C01>) |
| 8086:1c00 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 7     | atapci     | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:1c08 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 7     | atapci     | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:27c0 | 1849:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 7     | atapci     | [A9A1B1A493](<Desktop/ASRock/G41/G41C-VS/9E84A9D36F15/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/A9A1B1A493>) |
| 8086:27df | 1849:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 7     | atapci     | [A9A1B1A493](<Desktop/ASRock/G41/G41C-VS/9E84A9D36F15/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/A9A1B1A493>) |
| 197b:2363 | 1458:b000 | JMicron Techn... | JMB363 SATA/IDE Controller           | 6     | atapci     | [62B94DD372](<Desktop/Gigabyte Technology/X58/X58A-UD5/5F8FCBCE26E8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/62B94DD372>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | atapci     | [6C32638BAF](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/244EA5C23B4B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6C32638BAF>) |
| 8086:1d3c | 103c:1589 | Intel            | C600/X79 series chipset IDE-r Con... | 6     | atapci     | [280CB294A5](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/F566B7B6B4CA/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/280CB294A5>) |
| 8086:27c0 | 1028:0400 | Intel            | NM10/ICH7 Family SATA Controller ... | 6     | atapci     | [17A2E12924](<Desktop/Dell/OptiPlex/OptiPlex 380/23BEB469DB7D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/17A2E12924>) |
| 8086:27df | 1028:0400 | Intel            | 82801G (ICH7 Family) IDE Controller  | 6     | atapci     | [17A2E12924](<Desktop/Dell/OptiPlex/OptiPlex 380/23BEB469DB7D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/17A2E12924>) |
| 1022:7800 | 1458:b002 | AMD              | FCH SATA Controller [IDE mode]       | 5     | ahci       | [24E23F5911](<Desktop/Gigabyte Technology/E2500/E2500N/7EB41E3CFB91/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/24E23F5911>) |
| 11ab:6121 | 1043:8212 | Marvell Techn... | 88SE6111/6121 SATA II / PATA Cont... | 5     | atapci     | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 197b:2363 | 1043:824f | JMicron Techn... | JMB363 SATA/IDE Controller           | 5     | atapci     | [73373C3C65](<Desktop/ASUSTek Computer/P7/P7P55D/FE7AE6E364ED/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/73373C3C65>) |
| 8086:1c00 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | atapci     | [6C32638BAF](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/244EA5C23B4B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6C32638BAF>) |
| 8086:27c0 | 1b0a:0005 | Intel            | NM10/ICH7 Family SATA Controller ... | 5     | atapci     | [A58B9A4F8F](<Desktop/Pegatron/IPM41/IPM41-D3/38C292CE2082/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A58B9A4F8F>) |
| 8086:3a26 | 103c:330d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 5     | atapci     | [4E059E9162](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/4E059E9162>) |
| 1002:439c | 103c:1609 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | atapci     | [B62251041B](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.2-P11/12.3-RELEASE/AMD64/B62251041B>) |
| 1022:780c | 1458:5002 | AMD              | FCH IDE Controller                   | 4     | atapci     | [18A74377AC](<Desktop/Gigabyte Technology/F2/F2A75M-HD2/DA29D87FC076/FREEBSD-13.0/13.0-RELEASE/AMD64/18A74377AC>) |
| 10de:03ec | 1849:03ec | Nvidia           | MCP61 IDE                            | 4     | atapci     | [5D447C8FCF](<Desktop/ASRock/N68-VS3/N68-VS3 FX/299EFDF3CF4A/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/5D447C8FCF>) |
| 10de:03f6 | 1849:03f6 | Nvidia           | MCP61 SATA Controller                | 4     | atapci     | [5D447C8FCF](<Desktop/ASRock/N68-VS3/N68-VS3 FX/299EFDF3CF4A/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/5D447C8FCF>) |
| 197b:2363 | 1043:81e4 | JMicron Techn... | JMB363 SATA/IDE Controller           | 4     | atapci     | [F97FBA19C1](<Desktop/ASUSTek Computer/P5B/P5B SE/FEBE76714166/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/F97FBA19C1>) |
| 8086:1c00 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 4     | atapci     | [9A24935DAB](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/5388A29693D7/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9A24935DAB>) |
| 8086:1c08 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 4     | atapci     | [9A24935DAB](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/5388A29693D7/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9A24935DAB>) |
| 8086:1e00 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 4     | atapci     | [E15D67E8DB](<Desktop/ASUSTek Computer/P8/P8H77-I/4CFD4EC7FC22/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/E15D67E8DB>) |
| 8086:1e08 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 4     | atapci     | [E15D67E8DB](<Desktop/ASUSTek Computer/P8/P8H77-I/4CFD4EC7FC22/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/E15D67E8DB>) |
| 8086:27c0 | 1462:7592 | Intel            | NM10/ICH7 Family SATA Controller ... | 4     | atapci     | [841CCE11E6](<Desktop/MSI/MS/MS-7592/3F77E8AE1F11/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/841CCE11E6>) |
| 8086:2920 | 15d9:060a | Intel            | 82801IR/IO/IH (ICH9R/DO/DH) 4 por... | 4     | atapci     | [37726BE36A](<Desktop/Supermicro/X7/X7SPA-HF/E43E7B6764BD/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/37726BE36A>) |
| 8086:2926 | 15d9:060a | Intel            | 82801I (ICH9 Family) 2 port SATA ... | 4     | atapci     | [37726BE36A](<Desktop/Supermicro/X7/X7SPA-HF/E43E7B6764BD/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/37726BE36A>) |
| 8086:2e16 | 1028:027f | Intel            | 4 Series Chipset PT IDER Controller  | 4     | atapci     | [F3444924FD](<Desktop/Dell/OptiPlex/OptiPlex 760/99F71E27B77F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F3444924FD>) |
| 1283:8213 | 1458:b000 | Integrated Te... | IT8213 IDE Controller                | 3     | atapci     | [DC1B4D8A6B](<Desktop/Gigabyte Technology/P55/P55A-UD3/1B9AE599E0BD/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/DC1B4D8A6B>) |
| 197b:2362 | 1043:8460 | JMicron Techn... | JMB362 SATA Controller               | 3     | ahci       | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 197b:2363 | 1462:7522 | JMicron Techn... | JMB363 SATA/IDE Controller           | 3     | atapci     | [BD108F94D5](<Desktop/MSI/MS/MS-7522/8E94D2B3DF48/FREEBSD-12.1-P7/12.1-RELEASE-P7/AMD64/BD108F94D5>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 91    | nvme       | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 31    | nvme       | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 24    | nvme       | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 21    | nvme       | [B23AB09F52](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/B23AB09F52>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 17    | nvme       | [BAC8D0BDB7](<Desktop/MSI/MS-7/MS-7A38/B30B426C8BF6/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/BAC8D0BDB7>) |
| 15b7:5009 | 15b7:5009 | Sandisk          | WD Blue SN550 NVMe SSD               | 16    | nvme       | [4C1F624666](<Desktop/Seeed Studio/ODYSSEY-X86J41X5/ODYSSEY-X86J41X5 SD-BS-CJ41G-300-101-H 07-21-2021 18:16:20/ABEA02A7130C/OPNSENSE-22.1.1/13.0-STABLE/AMD64/4C1F624666>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 14    | nvme       | [79D8E655A3](<Desktop/ASRock/B550M/B550M Steel Legend/6852CF1058EA/OPNSENSE-22.1.2/13.0-STABLE/AMD64/79D8E655A3>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 14    | nvme       | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 12    | nvme       | [D3596DFF89](<Desktop/ASRock/X570/X570 PG Velocita/A90551D8040B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D3596DFF89>) |
| 15b7:5006 | 15b7:5006 | Sandisk          | WD Black SN750 / PC SN730 NVMe SSD   | 10    | nvme       | [0D2956A144](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/1180D50A4B77/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/0D2956A144>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 10    | nvme       | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 10    | nvme       | [ECCB947AE4](<Desktop/ASUSTek Computer/ROG/ROG Strix GA35DX_G35DX/F076DE9CAEB5/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/ECCB947AE4>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 9     | nvme       | [E4F7F31828](<Desktop/Supermicro/AS/AS -E301-9D-8CN4/72CEEFE7C3DC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E4F7F31828>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 8     | nvme       | [360EA3B215](<Desktop/Others/SKYBAY/SKYBAY/81CF0D9B2186/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/360EA3B215>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 8     | nvme       | [47061377BD](<Desktop/Dell/OptiPlex/OptiPlex 7080/89EDBB67F349/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/47061377BD>) |
| 15b7:5002 | 15b7:5002 | Sandisk          | WD Black 2018/SN750 / PC SN720 NV... | 7     | nvme       | [F56CDD9FEA](<Desktop/ASRock/H470/H470M-ITX-ac/CE2789C7FDFA/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/F56CDD9FEA>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 7     | nvme       | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 15b7:5003 | 15b7:5003 | Sandisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 6     | nvme       | [F1F9BADF9F](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/3BC515ADBA7B/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/F1F9BADF9F>) |
| 15b7:5011 | 15b7:5011 | Sandisk          | WD PC SN810 / Black SN850 NVMe SSD   | 6     | nvme       | [1E54F9CA54](<Desktop/ASRock/H570/H570M-ITX-ac/7252CA256A2E/OPNSENSE-22.1.1/13.0-STABLE/AMD64/1E54F9CA54>) |
| 1c5c:174a | 1c5c:174a | SK Hynix         | Gold P31 SSD                         | 5     | nvme       | [BC5703B5BB](<Desktop/ASUSTek Computer/ASUS/ASUS ExpertCenter D500SA_D500SA/ABC523DBEA27/OPNSENSE-22.1.1/13.0-STABLE/AMD64/BC5703B5BB>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 5     | nvme       | [8AEE77286E](<Desktop/MSI/MS/MS-7760/658E325602DE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8AEE77286E>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 4     | nvme       | [9CD2758A5F](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/4E83FD0E25CF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/9CD2758A5F>) |
| 1344:5405 | 1344:0100 | Micron Techno... |                                      | 4     | nvme       | [1AA5CED5A0](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-A/98A2A0675D76/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1AA5CED5A0>) |
| 1c5c:1327 |           | SK Hynix         | BC501 NVMe Solid State Drive         | 4     | nvme       | [85E0CF058C](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/E5364DA82AF0/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/85E0CF058C>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 4     | nvme       | [2CC4698CBC](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-I GAMING/E76068026A5B/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/2CC4698CBC>) |
| 10ec:5763 | 10ec:5763 | Realtek Semic... |                                      | 3     | nvme       | [D2D10A1FFC](<Desktop/Gigabyte Technology/B365M/B365M DS3H/7A3F482A1C2E/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D2D10A1FFC>) |
| 1344:5410 | 1344:0100 | Micron Techno... |                                      | 3     | nvme       | [18576EF86C](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/199DE71C8C4A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/18576EF86C>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 3     | nvme       | [A2DF68E1D1](<Desktop/ASRock/TRX40/TRX40 Taichi/AC795CCA9B64/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A2DF68E1D1>) |
| 1c5c:1639 | 1c5c:1639 | SK Hynix         | hynix unknown                        | 3     | nvme       | [9478973D4C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M70s 11EX000LGE/DFD126BDDFCE/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/9478973D4C>) |
| 8086:2522 | 8086:3806 | Intel            | NVMe Optane Memory Series            | 3     | nvme       | [6876D2D37D](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/BB03C210EA63/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6876D2D37D>) |
| 10ec:5760 | 5760:10ec | Realtek Semic... |                                      | 2     | nvme       | [9614FD11D7](<Desktop/ASRock/X570/X570 Steel Legend WiFi ax/730F6AC9C266/MIDNIGHTBSD-2.1.0/2.1.0/AMD64/9614FD11D7>) |
| 14a4:22f1 | 1b4b:1093 | Lite-On Techn... | M8Pe Series NVMe SSD                 | 2     | nvme       | [C518DED272](<Desktop/ASRock/Z170M/Z170M Extreme4/9326F1E80AA0/FREEBSD-13.0/13.0-RELEASE/AMD64/C518DED272>) |
| 15ad:07f0 | 15ad:07f0 | VMware           |                                      | 2     | nvme       | [D05FB15725](<Desktop/Others/Others/Others/F4EC27092DD8/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/D05FB15725>) |
| 15b7:5001 | 1b4b:1093 | Sandisk          | WD Black NVMe SSD                    | 2     | nvme       | [A3AF1CDE86](<Desktop/ASRock/B450/B450 Steel Legend/FCCCFD706BD2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/A3AF1CDE86>) |
| 1bb1:5012 | 1bb1:5012 | Seagate Techn... | FireCuda 510 SSD                     | 2     | nvme       | [9DB52EFAE6](<Desktop/Shuttle/DH/DH470/D9A405623369/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/9DB52EFAE6>) |
| 1d97:1160 | 1d97:1160 | Shenzhen Long... |                                      | 2     | nvme       | [2AC306B67F](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2AC306B67F>) |
| 1e95:9100 | 126f:2263 | Solid State S... |                                      | 2     | nvme       | [B55A699934](<Desktop/Dell/Inspiron/Inspiron 3891/E69659E3B5AD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B55A699934>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 2     | nvme       | [F5831FBB89](<Desktop/HARDKERNEL/ODROID-H/ODROID-H2/397877110852/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/F5831FBB89>) |
| 8086:0953 | 8086:370d | Intel            | PCIe Data Center SSD                 | 2     | nvme       | [5FFEB3D23E](<Desktop/Dell/Precision/Precision Tower 5810/C17AA4683009/FREEBSD-12.1/12.1-RELEASE/AMD64/5FFEB3D23E>) |
| c0a9:5403 | c0a9:1100 | Micron/Crucia... | NVMe Controller                      | 2     | nvme       | [9268D91D01](<Desktop/HARDKERNEL/ODROID-H/ODROID-H2/14089683CB6B/OPNSENSE-22.1/13.0-STABLE/AMD64/9268D91D01>) |
| 10ec:5765 | 10ec:5765 | Realtek Semic... |                                      | 1     | nvme       | [68F6EB4328](<Desktop/MSI/MS-7/MS-7C95/F962A0881828/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/68F6EB4328>) |
| 1179:0115 | 1179:0001 | Toshiba          | XG4 NVMe SSD Controller              | 1     | nvme       | [53ABDFA3B1](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/28EF496B2A02/OPNSENSE-22.1/13.0-STABLE/AMD64/53ABDFA3B1>) |
| 1179:0116 | 1179:0001 | Toshiba          | unknown                              | 1     | nvme       | [C729F82F4C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M720s 10SUS4WT00/F6ADF227305E/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C729F82F4C>) |
| 1179:011a | 1179:0001 | Toshiba          | XG6 NVMe SSD Controller              | 1     | nvme       | [D83FC71C91](<Desktop/Gigabyte Technology/B360/B360 HD3P-LM/535230C41C44/FREEBSD-13.0-RC2/13.0-RC2/AMD64/D83FC71C91>) |
| 126f:2263 | 1dee:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 1     | nvme       | [90D91BC113](<Desktop/Hewlett-Packard/Desktop/Desktop M01-F1xxx/9193B45C9DE6/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/90D91BC113>) |
| 14a4:2300 | 1b4b:1093 | Lite-On Techn... |                                      | 1     | nvme       | [9F06290060](<Desktop/ASRockRack/X570/X570D4I-2T/B32DEFCA56BC/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9F06290060>) |
| 15b7:5005 | 15b7:5005 | Sandisk          | PC SN520 NVMe SSD                    | 1     | nvme       | [F601F00E7C](<Desktop/Hewlett-Packard/Desktop/Desktop M01-F1xxx/9193B45C9DE6/NOMADBSD-5806F915/13.0-RELEASE/AMD64/F601F00E7C>) |
| 15b7:5019 | 15b7:5019 | Sandisk          | unknown                              | 1     | nvme       | [21E1806645](<Desktop/Dell/OptiPlex/OptiPlex 7060/02DE4FC70F47/OPNSENSE-22.1/13.0-STABLE/AMD64/21E1806645>) |
| 1987:5007 | 1987:5007 | Phison Electr... | E7 NVMe Controller                   | 1     | nvme       | [B5665D0DF2](<Desktop/iEi/E/E452/9CA08BBB076E/HARDENEDBSD-13.0-STABLE-HBSD/13.0-STABLE-HBSD/AMD64/B5665D0DF2>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 1     | nvme       | [BAB75AC477](<Desktop/ASUSTek Computer/PRIME/PRIME J4005I-C/A8F3D6ECF0A3/FREEBSD-12.2/12.2-RELEASE/AMD64/BAB75AC477>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2822 | 1028:05a4 | Intel            | SATA Controller [RAID mode]          | 12    | ahci       | [7A5D842D33](<Desktop/Dell/OptiPlex/OptiPlex 9020/4AC712A10049/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/7A5D842D33>) |
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 10    | ahci       | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:2822 | 1028:047e | Intel            | SATA Controller [RAID mode]          | 6     | ahci       | [201BA6CBBA](<Desktop/Dell/OptiPlex/OptiPlex 990/920D8E738DC6/PFSENSE-2.5.0/12.2-STABLE/AMD64/201BA6CBBA>) |
| 8086:2822 | 1028:052c | Intel            | SATA Controller [RAID mode]          | 6     | ahci       | [0541A207C7](<Desktop/Dell/OptiPlex/OptiPlex 9010/630D25B19798/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0541A207C7>) |
| 8086:2826 | 103c:1589 | Intel            | C600/X79 series chipset SATA RAID... | 5     | ahci       | [8BD32670C2](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8BD32670C2>) |
| 8086:2822 | 103c:130a | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [C2B43EFB8F](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/C2B43EFB8F>) |
| 8086:2826 | 103c:158a | Intel            | C600/X79 series chipset SATA RAID... | 4     | ahci       | [A9B66CB0E1](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/A9B66CB0E1>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 3     | ciss       | [FBD2ABDA35](<Desktop/NETGEAR/ReadyDATA/ReadyDATA 5200/2E63D7AE698C/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBD2ABDA35>) |
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 3     | ciss       | [4E059E9162](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/4E059E9162>) |
| 8086:2822 | 1028:0620 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [BB86FB3E67](<Desktop/Dell/PowerEdge/PowerEdge T20/C68E45CBB411/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BB86FB3E67>) |
| 8086:2822 | 1028:07c5 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [90A1FD1C58](<Desktop/Dell/PowerEdge/PowerEdge T30/82CE853FF0D7/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/90A1FD1C58>) |
| 8086:2822 | 1028:085b | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [BBCF2BAD96](<Desktop/Dell/OptiPlex/OptiPlex 5060/B3C627211006/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BBCF2BAD96>) |
| 8086:2822 | 1458:b005 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [AE1AA5A6F7](<Desktop/Gigabyte Technology/B360N/B360N WIFI/DC3709C1C54A/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/AE1AA5A6F7>) |
| 1000:0072 | 1734:1177 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [88EE81B089](<Desktop/ASUSTek Computer/P8/P8Z77-V/AC73B1912AC9/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/88EE81B089>) |
| 105a:5275 | 1462:1290 | Promise Techn... | PDC20276 (MBFastTrak133 Lite)        | 2     | atapci     | [4AB900BDA7](<Desktop/MSI/MS/MS-9129/FE70FB1F858A/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/4AB900BDA7>) |
| 1095:3112 | 1095:3112 | Silicon Image    | SiI 3112 [SATALink/SATARaid] Seri... | 2     | atapci     | [4AB900BDA7](<Desktop/MSI/MS/MS-9129/FE70FB1F858A/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/4AB900BDA7>) |
| 1095:3114 | 1095:3114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 2     | atapci     | [714B6539CF](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/616CA97E53D9/TRUENAS-12.2-RC3/12.2-RC3/AMD64/714B6539CF>) |
| 1095:3114 | 1095:7114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 2     | atapci     | [4C9B877754](<Desktop/Gigabyte Technology/Z77/Z77X-UD3H/1B931DE47D32/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/4C9B877754>) |
| 1106:3249 | 1106:3249 | VIA Technologies | VT6421 IDE/SATA Controller           | 2     | atapci     | [5ABCE24217](<Desktop/ASRock/N68C-GS4/N68C-GS4 FX/E2B5288E6A1C/NOMADBSD-1.4-RC1/12.2-RELEASE-P7/AMD64/5ABCE24217>) |
| 8086:2822 | 1028:02da | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [F735EE3C9E](<Desktop/Dell/OptiPlex/OptiPlex 980/093C6BC1C724/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/F735EE3C9E>) |
| 8086:2822 | 1028:0420 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [FCBFBC2DFA](<Desktop/Dell/OptiPlex/OptiPlex 780/1E135D2838C7/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/FCBFBC2DFA>) |
| 8086:2822 | 1028:06ba | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [D9AE9EC6F6](<Desktop/Dell/OptiPlex/OptiPlex 5040/6A6458ACB6C7/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/D9AE9EC6F6>) |
| 8086:2822 | 1028:0871 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [290F10C785](<Desktop/Dell/Precision/Precision 3630 Tower/703F414672AD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/290F10C785>) |
| 8086:2822 | 103c:1309 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [B56BD19073](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/44AE2B54DFB8/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B56BD19073>) |
| 8086:2822 | 103c:1495 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [385D212BBF](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/103902608515/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/385D212BBF>) |
| 8086:2822 | 103c:8768 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [65FBD31DA1](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/5416334E31EB/OPNSENSE-22.1/13.0-STABLE/AMD64/65FBD31DA1>) |
| 8086:2822 | 1043:8534 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [84D7FB3F1E](<Desktop/ASUSTek Computer/All/All Series/46CAE9B0FE93/GHOSTBSD-22.01.28/13.0-STABLE/AMD64/84D7FB3F1E>) |
| 8086:2822 | 1458:b000 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 9005:028b | 9005:0200 | Adaptec          | Series 6 - 6G SAS/PCIe 2             | 2     | aacraid    | [238A9E47BF](<Desktop/MSI/MS/MS-7891/AA5249EEE69B/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/238A9E47BF>) |
| 1000:005b | 1000:8081 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mrsas      | [3956AD0525](<Desktop/Cisco Systems/UCSC-C240/UCSC-C240-M3L/39FFEFE18EB4/FREEBSD-13.0/13.0-RELEASE/AMD64/3956AD0525>) |
| 1000:005b | 1000:9271 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mrsas      | [3956AD0525](<Desktop/Cisco Systems/UCSC-C240/UCSC-C240-M3L/39FFEFE18EB4/FREEBSD-13.0/13.0-RELEASE/AMD64/3956AD0525>) |
| 1000:005d | 1000:9363 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mfi        | [205D6E0194](<Desktop/Wortmann AG/TERRA_SERVER/TERRA_SERVER/4BE5147F2077/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/205D6E0194>) |
| 1000:005d | 15d9:0809 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mfi        | [6CCB3C09D6](<Desktop/Supermicro/SSG-6028/SSG-6028R-E1CR12T/C900D9534C94/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/6CCB3C09D6>) |
| 1000:005f | 1000:9340 | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 1     | mrsas      | [1151C41ED4](<Desktop/Lenovo/70TT0008EA/70TT0008EA ThinkServer TS460/CD730048EF25/FREEBSD-12.2/12.2-RELEASE/AMD64/1151C41ED4>) |
| 1000:0073 | 1000:9241 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 1     | mfi        | [EB73C9D13D](<Desktop/Supermicro/X9/X9DAi/558BB9BB7FC9/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/EB73C9D13D>) |
| 1000:0073 | 1028:1f78 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 1     | mfi        | [16CA205380](<Desktop/Lenovo/ThinkStation/ThinkStation S30 0606A99/399D1E7F3F53/FREEBSD-12.2/12.2-RELEASE/AMD64/16CA205380>) |
| 1000:0073 | 1137:00b7 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 1     | mfi        | [3956AD0525](<Desktop/Cisco Systems/UCSC-C240/UCSC-C240-M3L/39FFEFE18EB4/FREEBSD-13.0/13.0-RELEASE/AMD64/3956AD0525>) |
| 1002:4392 | 103c:2a92 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1     | ahci       | [DA467830AF](<Desktop/Hewlett-Packard/HPE-570/HPE-570f/D6775F31A0B7/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/DA467830AF>) |
| 1002:4393 | 1043:84df | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1     | ahci       | [90C27497D9](<Desktop/ASUSTek Computer/Crosshair/Crosshair V Formula/08D4551A4F47/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/90C27497D9>) |
| 1002:4393 | 1849:4393 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1     | ahci       | [6C0BBA6D4F](<Desktop/ASRock/990FX/990FX Extreme9/F64EA030F435/FREEBSD-12.1-P6/12.1-RELEASE-P6/AMD64/6C0BBA6D4F>) |
| 103c:3238 | 103c:3211 | Hewlett-Packard  | Smart Array E200i (SAS Controller)   | 1     | ciss       | [4D525CBA3E](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G5/BA8B81390872/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/4D525CBA3E>) |
| 103c:323a | 103c:3241 | Hewlett-Packard  | Smart Array G6 controllers           | 1     | ciss       | [1151C41ED4](<Desktop/Lenovo/70TT0008EA/70TT0008EA ThinkServer TS460/CD730048EF25/FREEBSD-12.2/12.2-RELEASE/AMD64/1151C41ED4>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 1     | ciss       | [7987F643D7](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350p Gen8/40D6689C165E/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/7987F643D7>) |
| 1095:0242 | 9005:0242 | Silicon Image    | AAR-1220SA Serial ATA HostRAID Co... | 1     | siis       | [B62251041B](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.2-P11/12.3-RELEASE/AMD64/B62251041B>) |
| 1095:3114 | 1043:8136 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 1     | atapci     | [5B1DC84DA5](<Desktop/ASUSTek Computer/P5/P5GD2-Deluxe/30982A88A2F4/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/5B1DC84DA5>) |
| 1095:3114 | 1095:6114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 1     | atapci     | [7C69051998](<Desktop/MSI/MS/MS-9129/ECC2992DB9DD/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/7C69051998>) |
| 1095:3124 | 1095:7124 | Silicon Image    | SiI 3124 PCI-X Serial ATA Controller | 1     | siis       | [82D3305FB4](<Desktop/Intel/D525MW/D525MW AAE93082-401/FD679E308419/FREEBSD-12.1-P1/12.1-RELEASE-P1/AMD64/82D3305FB4>) |
| 1095:3132 | 1095:7132 | Silicon Image    | SiI 3132 Serial ATA Raid II Contr... | 1     | siis       | [CEC3CB521D](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO R2.0/00B5E8AFBD04/TRUENAS-12.2-P2/12.2-RELEASE-P2/AMD64/CEC3CB521D>) |
| 1095:3512 | 1095:3512 | Silicon Image    | SiI 3512 [SATALink/SATARaid] Seri... | 1     | atapci     | [5664E84F3C](<Desktop/MSI/MS/MS-7693/0C8C6FDA249C/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/5664E84F3C>) |
| 1095:3512 | 182d:0010 | Silicon Image    | SiI 3512 [SATALink/SATARaid] Seri... | 1     | atapci     | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1000:3020 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 12    | mps        | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 8086:1d6b | 103c:1589 | Intel            | C602 chipset 4-Port SATA Storage ... | 7     | isci       | [8BD32670C2](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8BD32670C2>) |
| 1000:0087 | 1000:3020 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 4     | mps        | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 8086:1d6b | 103c:158a | Intel            | C602 chipset 4-Port SATA Storage ... | 4     | isci       | [A9B66CB0E1](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/A9B66CB0E1>) |
| 1000:0097 | 1000:30e0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 3     | mpr        | [8E713B55DC](<Desktop/Supermicro/SSG-5028/SSG-5028R-E1CR12L-CE010/BC525F547480/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/8E713B55DC>) |
| 1000:0072 | 1000:3040 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [DC582EA4D3](<Desktop/ASRock/B550M/B550M Pro4/6D75D10E9FEA/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/DC582EA4D3>) |
| 1000:0072 | 1028:1f1c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [6859F63B6B](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML110 G6/EB5BFD5B0905/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/6859F63B6B>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [1DB4784753](<Desktop/Supermicro/SSG-6029/SSG-6029P-E1CR12L/A25F2BC1A98D/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/1DB4784753>) |
| 1000:0097 | 1849:0097 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [C04BBD635B](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/6457E123E761/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/C04BBD635B>) |
| 8086:1d6b | 17aa:1026 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [1EC71F814B](<Desktop/Lenovo/ThinkStation/ThinkStation S30 43511K5/E8B0027862B5/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1EC71F814B>) |
| 1000:005d | 15d9:0a09 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [B44FE94131](<Desktop/Supermicro/SSG-2028/SSG-2028R-E1CR24N/201BEB766364/FREENAS-11.3-P9/11.3-RELEASE-P9/AMD64/B44FE94131>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mps        | [4DCA0D2AA4](<Desktop/ASUSTek Computer/All/All Series/0AB137A413F8/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/4DCA0D2AA4>) |
| 1000:0070 | 1000:3010 | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 1     | mps        | [7A41FCA3BB](<Desktop/MSI/MS-7/MS-7A32/4145197956A6/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/7A41FCA3BB>) |
| 1000:0072 | 1000:0072 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [6A6164AF73](<Desktop/TYAN Computer/S/S5512/A897EED01FA8/TRUENAS-12.2-P2/12.2-RELEASE-P2/AMD64/6A6164AF73>) |
| 1000:0072 | 1000:3050 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [28FDD2C2DC](<Desktop/Supermicro/X9/X9SCL-X9SCM/70812EDDCEB0/FREENAS-11.2-STABLE/11.2-STABLE/AMD64/28FDD2C2DC>) |
| 1000:0072 | 1000:30f0 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [90C27497D9](<Desktop/ASUSTek Computer/Crosshair/Crosshair V Formula/08D4551A4F47/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/90C27497D9>) |
| 1000:0072 | 1028:1f1d | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [05D3AB8D4B](<Desktop/ASRock/B360/B360 Pro4/68A525A70C29/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/05D3AB8D4B>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [FBD2ABDA35](<Desktop/NETGEAR/ReadyDATA/ReadyDATA 5200/2E63D7AE698C/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBD2ABDA35>) |
| 1000:0086 | 103c:158b | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [EA62F49750](<Desktop/Supermicro/X9/X9DRD-7LN4F/97D90A6AA706/TRUENAS-12.2-P10/12.2-RELEASE-P10/AMD64/EA62F49750>) |
| 1000:0097 | 1028:0619 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [DDDF168DB9](<Desktop/Dell/Precision/Precision Tower 7910/9E71C365962A/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/DDDF168DB9>) |
| 1000:00ac | 1000:3000 | Broadcom / LSI   | SAS3416 Fusion-MPT Tri-Mode I/O C... | 1     | mpr        | [23196AA66B](<Desktop/ASRock/Z390/Z390M-ITX-ac/40E52D5C50CF/FREEBSD-12.2-P5/12.2-RELEASE-P4/AMD64/23196AA66B>) |
| 15ad:07c0 | 15ad:07c0 | VMware           | PVSCSI SCSI Controller               | 1     | pvscsi     | [392CF6EC24](<Desktop/Others/Others/Others/375B22211095/FREEBSD-13.0/13.0-RELEASE/ARM64/392CF6EC24>) |
| 8086:1d6b | 103c:158b | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 8086:1d6b | 15d9:0628 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [31017CE819](<Desktop/Penguin Computing/Icebreaker/Icebreaker 4824/D0EFCA2F74C7/FREEBSD-12.2/12.2-RELEASE/AMD64/31017CE819>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [0F3EE4CAAB](<Desktop/Fujitsu/CELSIUS/CELSIUS M720/7B5122D4B3E4/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/0F3EE4CAAB>) |
| 9005:028f | 103c:0651 | Adaptec          | Smart Storage PQI SAS                | 1     | smartpqi   | [F8A95C37D5](<Desktop/HPE/ProLiant/ProLiant ML30 Gen10/93F91BA1C4A9/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/F8A95C37D5>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1425:5501 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 5     |            | [2AC306B67F](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2AC306B67F>) |
| 1425:4501 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 4     |            | [51EBC2C3FD](<Desktop/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/F7BBE9119163/OPNSENSE-22.1.2/13.0-STABLE/AMD64/51EBC2C3FD>) |
| 17d3:1300 | 17d3:1300 | Areca Technology | ARC-1300ix-16 16-Port PCI-Express... | 4     | arcsas     | [66BBED8D59](<Desktop/ASUSTek Computer/P6T/P6T SE/9C422F2B290E/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/66BBED8D59>) |
| 9004:8178 |           | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 3     | ahc        | [B7FC5EF684](<Desktop/Biostar/X470/X470GTA/2553A631F2D9/FREEBSD-13.0/13.0-RELEASE/AMD64/B7FC5EF684>) |
| 1000:0058 | 1028:1f0e | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mpt        | [B4234170E8](<Desktop/ASUSTek Computer/P5Q/P5Q DELUXE/E1D558665C0F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B4234170E8>) |
| 1425:5503 |           | Chelsio Commu... | T540-CR Unified Wire Storage Cont... | 2     |            | [C04BBD635B](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/6457E123E761/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/C04BBD635B>) |
| 1425:5507 |           | Chelsio Commu... | T520-SO Unified Wire Storage Cont... | 2     |            | [502AF52245](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10/BB7614C3933F/OPNSENSE-22.1/13.0-STABLE/AMD64/502AF52245>) |
| 5853:0001 | 5853:0001 | XenSource        | Xen Platform Device                  | 2     | xenpci     | [FFB1FD95D3](<Desktop/PC Engines/apu/apu4/8CB6C93947A1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/FFB1FD95D3>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 2     | ahc        | [C67CCF8BC6](<Desktop/Dell/Inspiron/Inspiron 530/3762C968ACCD/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C67CCF8BC6>) |
| 1000:0001 | 1000:1000 | Broadcom / LSI   | 53c810                               | 1     | sym        | [4EE625240F](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VII HERO/37724E1F8F3B/FREEBSD-12.1-STABLE/12.1-STABLE-20200612/AMD64/4EE625240F>) |
| 1000:000f | 1000:1000 | Broadcom / LSI   | 53c875                               | 1     | sym        | [DAE16641BB](<Desktop/ASUSTek Computer/M2/M2NPV-MX/14DC624B8825/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/DAE16641BB>) |
| 1000:0030 | 103c:322a | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [2F26C69137](<Desktop/Dell/OptiPlex/OptiPlex 390/A5CC20B80AD3/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/2F26C69137>) |
| 1000:0056 | 1000:1000 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [7B2DE50C60](<Desktop/Apple/Xserve3/Xserve3,1/D499BA477C7F/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/7B2DE50C60>) |
| 1000:0056 | 1734:1131 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [FF2213E848](<Desktop/Fujitsu/CELSIUS/CELSIUS M470-2/50E1DC1E3DE9/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/FF2213E848>) |
| 1000:0058 | 103c:130b | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [6DDE87584C](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/E946340732BD/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/6DDE87584C>) |
| 1000:0058 | 15d9:a480 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [27FC294BCA](<Desktop/Supermicro/X7/X7DCL/3D21E845B8F9/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/27FC294BCA>) |
| 1000:0058 | 17aa:101d | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [6F464AAD1F](<Desktop/Lenovo/ThinkStation/ThinkStation D10 6493WEU/6A717F675FF7/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/6F464AAD1F>) |
| 1000:0059 | 15d9:0004 | Broadcom / LSI   | MegaRAID SAS 8208ELP/8208ELP         | 1     | mpt        | [7D0E121099](<Desktop/Supermicro/X8/X8STi/00B85E5857AF/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/7D0E121099>) |
| 1103:2300 | 11ab:11ab | HighPoint Tec... | RocketRAID 230x 4 Port SATA-II Co... | 1     | hptrr      | [AA29EB9C75](<Desktop/Gigabyte Technology/H67/H67A-UD3H-B3/48803C404D01/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/AA29EB9C75>) |
| 1425:5584 |           | Chelsio Commu... | T540-5084 Unified Wire Storage Co... | 1     |            | [2BBA0377AE](<Desktop/MSI/MS/MS-7733/A84A1CCB8340/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2BBA0377AE>) |
| 1425:6503 |           | Chelsio Commu... | T6425-CR Unified Wire Storage Con... | 1     |            | [17A763A917](<Desktop/MSI/MS-7/MS-7B24/D5C8F44D7DED/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/17A763A917>) |
| 9004:3860 | 9004:3869 | Adaptec          | AHA-2930CU                           | 1     | ahc        | [C7D877A988](<Desktop/Supermicro/X7/X7SBL/725A0E7344D4/FREEBSD-12.3/12.3-RELEASE/AMD64/C7D877A988>) |
| 9004:5078 |           | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 1     | ahc        | [1BC05B5951](<Desktop/Dell/Precision/Precision WorkStation T3400/ADEEA3484D9F/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1BC05B5951>) |
| 9004:8178 | 9004:7881 | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 1     | ahc        | [75E86A92F7](<Desktop/ASUSTek Computer/All/All Series/07E6A3D81A80/FREEBSD-12.2-P1/12.2-RELEASE-P1/AMD64/75E86A92F7>) |
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 1     | ahd        | [EB73C9D13D](<Desktop/Supermicro/X9/X9DAi/558BB9BB7FC9/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/EB73C9D13D>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1567 | 1022:1567 | AMD              | Mullins IOMMU                        | 128   |            | [E56B256787](<Desktop/PC Engines/APU/APU2/FD5944A53320/PFSENSE-12.3-STABLE/12.3-STABLE/AMD64/E56B256787>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 92    |            | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 44    |            | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 41    |            | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 38    |            | [58E098ECA2](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/58E098ECA2>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 38    |            | [58E098ECA2](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/58E098ECA2>) |
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 36    | amdiommu   | [606D3086CE](<Desktop/ASRockRack/X470/X470D4U/2AA488105C83/OPNSENSE-22.1.2/13.0-STABLE/AMD64/606D3086CE>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 36    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 28    |            | [58E098ECA2](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/58E098ECA2>) |
| 1022:1481 | 1043:87c0 | AMD              | Starship/Matisse IOMMU               | 27    |            | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 103c:3306 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Sl... | 26    |            | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 103c:3307 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Ma... | 26    |            | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 8086:3438 |           | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 26    |            | [58E098ECA2](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/58E098ECA2>) |
| 1022:1451 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 23    |            | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 8086:2016 |           | Intel            | Sky Lake-E Ubox Registers            | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2018 |           | Intel            | Sky Lake-E M2PCI Registers           | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2021 |           | Intel            | Sky Lake-E CBDMA Registers           | 18    | ioat       | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2025 |           | Intel            | Sky Lake-E RAS                       | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2026 | 8086:2026 | Intel            | Sky Lake-E IOAPIC                    | 18    | ioapic     | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2034 |           | Intel            | Sky Lake-E VT-d                      | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2035 |           | Intel            | Sky Lake-E RAS Configuration Regi... | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2036 | 8086:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 18    | ioapic     | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2040 |           | Intel            | Sky Lake-E Integrated Memory Cont... | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2041 |           | Intel            | Sky Lake-E Integrated Memory Cont... | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2042 |           | Intel            | Sky Lake-E Integrated Memory Cont... | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2043 |           | Intel            | Sky Lake-E Integrated Memory Cont... | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2044 |           | Intel            | Sky Lake-E Integrated Memory Cont... | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2045 |           | Intel            | Sky Lake-E LM Channel 1              | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2046 |           | Intel            | Sky Lake-E LMS Channel 1             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2047 |           | Intel            | Sky Lake-E LMDP Channel 1            | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2048 |           | Intel            | Sky Lake-E DECS Channel 2            | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2049 |           | Intel            | Sky Lake-E LM Channel 2              | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:204a |           | Intel            | Sky Lake-E LMS Channel 2             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:204b |           | Intel            | Sky Lake-E LMDP Channel 2            | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:204e |           | Intel            | Sky Lake-E M3KTI Registers           | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2054 |           | Intel            | Sky Lake-E CHA Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2055 |           | Intel            | Sky Lake-E CHA Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2056 |           | Intel            | Sky Lake-E CHA Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2057 |           | Intel            | Sky Lake-E CHA Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2066 |           | Intel            | Sky Lake-E Integrated Memory Cont... | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2080 |           | Intel            | Sky Lake-E PCU Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2081 |           | Intel            | Sky Lake-E PCU Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2082 |           | Intel            | Sky Lake-E PCU Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2083 |           | Intel            | Sky Lake-E PCU Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2084 |           | Intel            | Sky Lake-E PCU Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2085 |           | Intel            | Sky Lake-E PCU Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:2086 |           | Intel            | Sky Lake-E PCU Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:208d |           | Intel            | Sky Lake-E CHA Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:208e |           | Intel            | Sky Lake-E CHA Registers             | 18    |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:3426 |           | Intel            | 7500/5520/5500/X58 Routing and Pr... | 17    |            | [C2B43EFB8F](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/C2B43EFB8F>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7808 | 1022:7808 | AMD              | FCH USB EHCI Controller              | 188   | ehci       | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:7814 | 1022:1410 | AMD              | FCH USB XHCI Controller              | 182   | xhci       | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 166   | xhci       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 115   | xhci       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 73    | xhci       | [C2B8C7EEBB](<Desktop/Others/Others/Others/40CC04883594/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C2B8C7EEBB>) |
| 1022:149c | 1022:148c | AMD              | Matisse USB 3.0 Host Controller      | 70    | xhci       | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:43d5 | 1b21:1142 | AMD              | 400 Series Chipset USB 3.1 XHCI C... | 65    | xhci       | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 47    | xhci       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:9ca6 | 8086:7270 | Intel            | Wildcat Point-LP USB EHCI Controller | 47    | ehci       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:9cb1 | 8086:7270 | Intel            | Wildcat Point-LP USB xHCI Controller | 47    | xhci       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 1022:149c | 1022:1486 | AMD              | Matisse USB 3.0 Host Controller      | 43    | xhci       | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 42    | ehci       | [177DC1FBC8](<Desktop/PC Engines/apu/apu1/BE5B5D847307/OPNSENSE-22.1.2/13.0-STABLE/AMD64/177DC1FBC8>) |
| 1002:4397 | 1002:4397 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 40    | ohci       | [177DC1FBC8](<Desktop/PC Engines/apu/apu1/BE5B5D847307/OPNSENSE-22.1.2/13.0-STABLE/AMD64/177DC1FBC8>) |
| 1002:4399 | 1002:4399 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 36    | ohci       | [5D88E3054B](<Desktop/PC Engines/APU/APU/1E388B64AF47/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5D88E3054B>) |
| 8086:9c26 | 8086:7270 | Intel            | 8 Series USB EHCI #1                 | 36    | ehci       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 36    | xhci       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 1022:149c | 1043:87c0 | AMD              | Matisse USB 3.0 Host Controller      | 34    | xhci       | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 8086:27c8 | 8086:27c8 | Intel            | NM10/ICH7 Family USB UHCI Control... | 34    | uhci       | [E41BA68AA2](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33/OPNSENSE-22.1/13.0-STABLE/AMD64/E41BA68AA2>) |
| 1b21:1042 | 1043:8488 | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 33    | xhci       | [E838981914](<Desktop/ASUSTek Computer/P6/P6-P8H61E/C84EA68888A3/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E838981914>) |
| 8086:27c9 | 8086:27c9 | Intel            | NM10/ICH7 Family USB UHCI Control... | 33    | uhci       | [E41BA68AA2](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33/OPNSENSE-22.1/13.0-STABLE/AMD64/E41BA68AA2>) |
| 1022:7807 | 103c:213d | AMD              | FCH USB OHCI Controller              | 32    | ohci       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 1022:7808 | 103c:213d | AMD              | FCH USB EHCI Controller              | 32    | ehci       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 1022:7814 | 103c:213d | AMD              | FCH USB XHCI Controller              | 32    | xhci       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:27cc | 8086:27cc | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 32    | ehci       | [E41BA68AA2](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33/OPNSENSE-22.1/13.0-STABLE/AMD64/E41BA68AA2>) |
| 8086:8c26 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 32    | ehci       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:8c2d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 32    | ehci       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:8c31 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 32    | xhci       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:27ca | 8086:27ca | Intel            | NM10/ICH7 Family USB UHCI Control... | 31    | uhci       | [CFBFDF0E55](<Desktop/MSI/MS-9/MS-9A45/43D8B2AF7F6A/OPNSENSE-22.1/13.0-STABLE/AMD64/CFBFDF0E55>) |
| 8086:8c26 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 30    | ehci       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:27cb | 8086:27cb | Intel            | NM10/ICH7 Family USB UHCI Control... | 29    | uhci       | [CFBFDF0E55](<Desktop/MSI/MS-9/MS-9A45/43D8B2AF7F6A/OPNSENSE-22.1/13.0-STABLE/AMD64/CFBFDF0E55>) |
| 8086:8c2d | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 29    | ehci       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:8c31 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 29    | xhci       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:2830 | 8086:2830 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 28    | uhci       | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:2831 | 8086:2831 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 28    | uhci       | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:2836 | 8086:2836 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 28    | ehci       | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:a12f | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 27    | xhci       | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 103c:3300 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 26    | uhci       | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 26    | xhci       | [2D1BF5A79A](<Desktop/BESSTAR Tech/HM/HM90/1F0A034DBC90/OPNSENSE-22.1.1/13.0-STABLE/AMD64/2D1BF5A79A>) |
| 8086:1c26 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 25    | ehci       | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:1c2d | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 25    | ehci       | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:1e26 | 1458:5006 | Intel            | 7 Series/C216 Chipset Family USB ... | 25    | ehci       | [5B6DD82DA8](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/34CE6C299230/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5B6DD82DA8>) |
| 8086:1e2d | 1458:5006 | Intel            | 7 Series/C216 Chipset Family USB ... | 25    | ehci       | [5B6DD82DA8](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/34CE6C299230/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5B6DD82DA8>) |
| 8086:2832 | 8086:2832 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 25    | uhci       | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:1e26 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family USB ... | 24    | ehci       | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:1e2d | 1043:84ca | Intel            | 7 Series/C216 Chipset Family USB ... | 24    | ehci       | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:1e31 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 24    | xhci       | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:3a34 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 24    | uhci       | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 8086:3a35 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 24    | uhci       | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 8086:3a36 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 24    | uhci       | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 8086:3a37 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 24    | uhci       | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |

### Video (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14f1:8800 | 0070:3401 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [1BC05B5951](<Desktop/Dell/Precision/Precision WorkStation T3400/ADEEA3484D9F/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1BC05B5951>) |
| 14f1:8800 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 14f1:8852 | 0070:7911 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 1     |            | [436706F322](<Desktop/Lenovo/ThinkCentre/ThinkCentre M82 2756B94/2D6E0A36E7BA/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/436706F322>) |
| 14f1:8880 | 0070:2a38 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     |            | [C230C65919](<Desktop/BCM Advanced Research/MX81/MX81HV-MX81H/317BF301CDED/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/C230C65919>) |
| 1cd7:0004 |           | Nanjing Magew... |                                      | 1     |            | [A2270B6F09](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/B28241EA93D9/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/A2270B6F09>) |
| 4444:0016 | 0070:8801 | Internext Com... | iTVC16 (CX23416) Video Decoder       | 1     |            | [64D4FB9B97](<Desktop/Hewlett-Packard/AY627AA-ABA/AY627AA-ABA a4313w/2B7EE5C08CC6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/64D4FB9B97>) |
| bdbd:a10b | bdbd:a10b | Blackmagic De... | Blackmagic DeckLink                  | 1     |            | [020CCD74D8](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 CMT/D5FB9BCC8299/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/020CCD74D8>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 66    |            | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 57    |            | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 57    |            | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 52    |            | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 27    |            | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 27    |            | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1455 | 1043:8747 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 19    |            | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 1022:145a | 1043:8747 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 19    |            | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 0000:0000 |           |                  |                                      | 12    |            | [BA0AC00CF6](<Desktop/MSI/MS/MS-7885/A9957445CE5D/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/BA0AC00CF6>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 10    |            | [4EE7DE3597](<Desktop/T-bao/MINI/MINI PC/2285C96C331C/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/4EE7DE3597>) |
| 1022:1485 | 1043:8808 | AMD              | Starship/Matisse Reserved SPP        | 8     |            | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 1022:148a | 1043:8808 | AMD              | Starship/Matisse PCIe Dummy Function | 8     |            | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 8086:a1ec | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 0    | 6     |            | [18576EF86C](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/199DE71C8C4A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/18576EF86C>) |
| 8086:a1ed | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 1    | 6     |            | [18576EF86C](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/199DE71C8C4A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/18576EF86C>) |
| 1022:145a | 1002:15dd | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 5     |            | [78F79FAB6F](<Desktop/Gigabyte Technology/B450M/B450M S2H/1472F852C675/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/78F79FAB6F>) |
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     |            | [0902E5400A](<Desktop/MW/GMLK-2/GMLK-2_5G4L/36C8C01719A8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0902E5400A>) |
| 1022:1485 | 1462:7c02 | AMD              | Starship/Matisse Reserved SPP        | 4     |            | [14F1956220](<Desktop/MSI/MS-7/MS-7C02/0BF11DCDAD12/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/14F1956220>) |
| 1022:148a | 1462:7c02 | AMD              | Starship/Matisse PCIe Dummy Function | 4     |            | [14F1956220](<Desktop/MSI/MS-7/MS-7C02/0BF11DCDAD12/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/14F1956220>) |
| 1022:15e6 | 1849:15e6 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 4     |            | [78D2871C20](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-22.1.1/13.0-STABLE/AMD64/78D2871C20>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 1022:1455 | 1462:7b86 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:145a | 1462:7b86 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 15ec:5000 | 15ec:5000 | Beckhoff         |                                      | 3     |            | [6DB720018B](<Desktop/Beckhoff Automation/CBxx/CBxx63/D2340951707E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6DB720018B>) |
| 8086:8d7c | 1043:8600 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [DACF7F604C](<Desktop/ASUSTek Computer/All/All Series/67304D8B913B/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DACF7F604C>) |
| 8086:8d7c | 1849:8d7c | Intel            | C610/X99 series chipset SPSR         | 3     |            | [149D7ABD05](<Desktop/ASRock/X99/X99 Taichi/159849139E39/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/149D7ABD05>) |
| 1022:145a | 1002:15d8 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [C1A27CA913](<Desktop/Gigabyte Technology/A320/A320M-S2H/414ECBBD0663/FREEBSD-13.0/13.0-RELEASE/AMD64/C1A27CA913>) |
| 1022:145a | 1458:d000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [B953D9D2E6](<Desktop/Gigabyte Technology/B450M/B450M DS3H/305FAB632525/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/B953D9D2E6>) |
| 1022:1485 | 1043:87cb | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:1485 | 1462:7b86 | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 1022:148a | 1043:87cb | AMD              | Starship/Matisse PCIe Dummy Function | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:148a | 1462:7b86 | AMD              | Starship/Matisse PCIe Dummy Function | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 8086:5aa2 | 8086:5aa2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     |            | [B1C784D41A](<Desktop/Thomas-Krenn.AG/LES/LES network/56DBE8BE7C78/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/B1C784D41A>) |
| 8086:8d7c | 103c:212b | Intel            | C610/X99 series chipset SPSR         | 2     |            | [D3894B9F37](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/845821A8075B/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/D3894B9F37>) |
| 8086:8d7c | 1462:7885 | Intel            | C610/X99 series chipset SPSR         | 2     |            | [BA0AC00CF6](<Desktop/MSI/MS/MS-7885/A9957445CE5D/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/BA0AC00CF6>) |
| 8086:8d7c | 15d9:0844 | Intel            | C610/X99 series chipset SPSR         | 2     |            | [26FD8CD5F0](<Desktop/Supermicro/SYS-1028/SYS-1028U-TN10RT+/C9821FF03B99/HARDENEDBSD-14.0-CURRENT-HBSD/14.0-CURRENT-HBSD/AMD64/26FD8CD5F0>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [EBB920C0C4](<Desktop/Supermicro/SYS-5019/SYS-5019S-ML/9095F638CA6D/FREEBSD-12.1-P9/12.1-RELEASE-P9/AMD64/EBB920C0C4>) |
| 8086:a1ec | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 0    | 2     |            | [1DB4784753](<Desktop/Supermicro/SSG-6029/SSG-6029P-E1CR12L/A25F2BC1A98D/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/1DB4784753>) |
| 8086:a1ec | 15d9:1b35 | Intel            | C620 Series Chipset Family MROM 0    | 2     |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 2     |            | [63699D431A](<Desktop/Dell/VEP-4600/VEP-4600-V910/BAE5F41CA0D2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/63699D431A>) |
| 8086:a1ed | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 1    | 2     |            | [1DB4784753](<Desktop/Supermicro/SSG-6029/SSG-6029P-E1CR12L/A25F2BC1A98D/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/1DB4784753>) |
| 8086:a1ed | 15d9:1b35 | Intel            | C620 Series Chipset Family MROM 1    | 2     |            | [30789867A9](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.1.1/13.0-STABLE/AMD64/30789867A9>) |
| 1022:1455 | 1462:7a40 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [43388A27A4](<Desktop/MSI/MS-7/MS-7A40/9E0B5CDB5278/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/43388A27A4>) |
| 1022:1455 | 1462:7b89 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [1123CB92BA](<Desktop/MSI/MS-7/MS-7B89/47621C911E75/FURYBSD-12.1-P9/12.1-RELEASE-P9/AMD64/1123CB92BA>) |
| 1022:1455 | 1462:7b90 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [E7BC61FACB](<Desktop/MSI/MS-7/MS-7B90/0D0E7C3B4D7C/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/E7BC61FACB>) |
| 1022:1455 | 1462:7c02 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [A87473149B](<Desktop/MSI/MS-7/MS-7C02/55874FBE1F48/FREEBSD-13.0/13.0-RELEASE/AMD64/A87473149B>) |
| 1022:145a | 1002:1636 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [011FB96FE0](<Desktop/ASRock/X570/X570 Pro4/81F9BADA7E18/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/011FB96FE0>) |
| 1022:145a | 1043:876b | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [D57DE875A6](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/51805C43859D/FREEBSD-13.0/13.0-RELEASE/AMD64/D57DE875A6>) |
| 1022:145a | 1462:7a38 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [BAC8D0BDB7](<Desktop/MSI/MS-7/MS-7A38/B30B426C8BF6/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/BAC8D0BDB7>) |
| 1022:145a | 1462:7a40 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [43388A27A4](<Desktop/MSI/MS-7/MS-7A40/9E0B5CDB5278/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/43388A27A4>) |
| 1022:145a | 1462:7b89 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [1123CB92BA](<Desktop/MSI/MS-7/MS-7B89/47621C911E75/FURYBSD-12.1-P9/12.1-RELEASE-P9/AMD64/1123CB92BA>) |

