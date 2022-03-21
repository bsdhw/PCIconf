Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed pciconf reports collected by BSD users at https://bsd-hardware.info.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 8784.

Contents
--------

1. [ About ](#about)
2. [ PCI Devices ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Input ](#input-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Modem ](#modem-pci)
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
   * [ Wireless controller ](#wireless-controller-pci)
   * [ Others ](#others-pci)

About
-----

The structure of the repository is the following:

    {COMPUTER TYPE}/{VENDOR}/{MODEL PREFIX}/{MODEL}/{HWID}/{OS}/{KERNEL}/{ARCH}/{PROBE ID}

    ( e.g. Notebook/Lenovo/ThinkPad/ThinkPad W540/376C44AF6B85/DEBIAN-9.1/4.9.0-3-AMD64/X86_64/F51B828085 )

You can find appropriate pciconf report in this repository by a probe ID as follows:

    find . -name {PROBE ID}

PCI Devices
-----------

Top 50 most popular devices in each category.

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1814:3298 | 103c:18ec | Ralink           | RT3290 Bluetooth                     | 3     |            | [AD95186D17](<Notebook/Hewlett-Packard/Others/Others/D84D3D5A0EA0/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/AD95186D17>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1439 | 1022:1234 | AMD              | Family 16h Processor Functions 5:1   | 257   | pcib       | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 1022:1452 |           | AMD              | Family 17h (Models 00h-1fh) PCIe ... | 209   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:780e | 1022:780e | AMD              | FCH LPC Bridge                       | 203   | isab       | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:156b |           | AMD              | Family 16h (Models 30h-3fh) Host ... | 198   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1580 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 198   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1581 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 198   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1582 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 198   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1583 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 198   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1584 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 198   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1585 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 198   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:1566 | 1022:1566 | AMD              | Family 16h (Models 30h-3fh) Proce... | 184   | hostb      | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:9d13 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 172   | pcib       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:9d14 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 169   | pcib       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:9d12 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 168   | pcib       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:9d10 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 161   | pcib       | [B9475ED44D](<Desktop/Protectli/FW/FW6/3EFC335326E0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/B9475ED44D>) |
| 8086:9d11 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 158   | pcib       | [B9475ED44D](<Desktop/Protectli/FW/FW6/3EFC335326E0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/B9475ED44D>) |
| 8086:9d15 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 157   | pcib       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 1002:4384 |           | AMD              | SBx00 PCI to PCI Bridge              | 155   | pcib       | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 138   | isab       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 137   | pcib       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 136   | hostb      | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 111d:8018 |           | Microsemi / P... | PES12N3A 12-lane 3-Port PCI Expre... | 131   | pcib       | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 8086:22ca | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 131   | pcib       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 127   | isab       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:0f48 | 8086:0f48 | Intel            | Atom Processor E3800 Series PCI E... | 126   | pcib       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:0f4a | 8086:0f4a | Intel            | Atom Processor E3800 Series PCI E... | 126   | pcib       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:0f4c | 8086:0f4c | Intel            | Atom Processor E3800 Series PCI E... | 124   | pcib       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:0f4e | 8086:0f4e | Intel            | Atom Processor E3800 Series PCI E... | 123   | pcib       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:5904 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 116   | hostb      | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:22cc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 112   | pcib       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:0f00 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 109   | hostb      | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 1022:15e8 |           | AMD              | Raven/Raven2 Device 24: Function 0   | 108   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:15e9 |           | AMD              | Raven/Raven2 Device 24: Function 1   | 108   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:15ea |           | AMD              | Raven/Raven2 Device 24: Function 2   | 108   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:15eb |           | AMD              | Raven/Raven2 Device 24: Function 3   | 108   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:15ec |           | AMD              | Raven/Raven2 Device 24: Function 4   | 108   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:15ed |           | AMD              | Raven/Raven2 Device 24: Function 5   | 108   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:15ee |           | AMD              | Raven/Raven2 Device 24: Function 6   | 108   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:15ef |           | AMD              | Raven/Raven2 Device 24: Function 7   | 108   | hostb      | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:22ce | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 106   | pcib       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 105   | hostb      | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 103   | pcib       | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1460 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 101   | hostb      | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1461 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 101   | hostb      | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1462 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 101   | hostb      | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1463 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 101   | hostb      | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1464 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 101   | hostb      | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1465 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 101   | hostb      | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1466 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 101   | hostb      | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1467 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 101   | hostb      | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5227 | 17aa:2226 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 10    | rtsx       | [4AE2360503](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CL001GUS/AB333C060A09/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/4AE2360503>) |
| 10ec:5227 | 17aa:220e | Realtek Semic... | RTS5227 PCI Express Card Reader      | 9     | rtsx       | [CBA9255F4A](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AWS1JN00/4F89B9A156FF/FREEBSD-13.0/13.0-RELEASE/AMD64/CBA9255F4A>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 9     | rtsx       | [713B33351F](<Notebook/System76/Lemur/Lemur Pro/FB3C4199D24B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/713B33351F>) |
| 10ec:5227 | 17aa:220c | Realtek Semic... | RTS5227 PCI Express Card Reader      | 8     | rtsx       | [2AF47B6502](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ006HUS/5B022BB303EA/NOMADBSD-5806F915/13.0-RELEASE/AMD64/2AF47B6502>) |
| 10ec:5227 | 17aa:5034 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 8     | rtsx       | [BC2860431E](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS0VH08/CDAB4EDF622D/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/BC2860431E>) |
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 10ec:522a | 17aa:5062 | Realtek Semic... | RTS522A PCI Express Card Reader      | 7     | rtsx       | [2E1C585715](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S0BM01/C223E0B01844/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2E1C585715>) |
| 10ec:5229 | 8086:2072 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 1217:8520 | 1028:05ca | O2 Micro         | SD/MMC Card Reader Controller        | 6     | sdhci_pci  | [762D8366D0](<Notebook/Dell/Latitude/Latitude E7240/B8876AE6AF27/FREEBSD-13.0-RC4/13.0-RC4/AMD64/762D8366D0>) |
| 10ec:5227 | 17aa:2214 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 5     | rtsx       | [66CFDD2419](<Notebook/Lenovo/ThinkPad/ThinkPad X240 20AMS2QDOC/958035AEAC5C/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/66CFDD2419>) |
| 10ec:522a | 103c:8079 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [F259F73C17](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/372FB522FD12/OPNSENSE-22.1/13.0-STABLE/AMD64/F259F73C17>) |
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [CCDA2302CF](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/41E25502F0FC/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/CCDA2302CF>) |
| 10ec:525a | 17aa:2238 | Realtek Semic... | RTS525A PCI Express Card Reader      | 5     | rtsx       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 10ec:5227 | 10cf:187f | Realtek Semic... | RTS5227 PCI Express Card Reader      | 4     | rtsx       | [C501C5C75E](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK A555/233E8905DCE8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/C501C5C75E>) |
| 10ec:522a | 1458:1000 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [5E980B75BC](<Desktop/Gigabyte Technology/GB-BACE/GB-BACE-3150/B48405EE0C5D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5E980B75BC>) |
| 10ec:522a | 17aa:5053 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [DEAC163B52](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FNCTO1WW/88EC95397971/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DEAC163B52>) |
| 10ec:525a | 1028:06de | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx       | [9E479E9C50](<Notebook/Dell/Latitude/Latitude E5470/A17BA6584F09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/9E479E9C50>) |
| 10ec:5227 | 103c:1991 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 3     | rtsx       | [362940ACBB](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G1/43570E209C4E/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/362940ACBB>) |
| 10ec:522a | 17aa:2279 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     |            | [6311D603FF](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N3X50500/5086A4A15BC2/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/6311D603FF>) |
| 10ec:522a | 17aa:5050 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [3EF1595AF6](<Notebook/Lenovo/ThinkPad/ThinkPad T460p 20FXS09D11/AEEBF4FDEE51/FREEBSD-13.0-P6/13.0-RELEASE-P4/AMD64/3EF1595AF6>) |
| 10ec:522a | 17aa:506d | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 10ec:522a | 17aa:5082 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [D028FC63D4](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y1002AFR/CFF1A3F59309/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/D028FC63D4>) |
| 10ec:522a | 17aa:5122 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [0C153D0C98](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MU000VUS/0748151D3905/MIDNIGHTBSD-2.1.1/2.1.1/AMD64/0C153D0C98>) |
| 10ec:5249 | 17aa:3801 | Realtek Semic... | RTS5249 PCI Express Card Reader      | 3     | rtsx       | [1FEB455E8C](<Notebook/Lenovo/Y50-70/Y50-70 20378/45CB117B153A/OPNSENSE-21.7.7/12.1-RELEASE-P19-HBSD/AMD64/1FEB455E8C>) |
| 10ec:525a | 1028:06df | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     |            | [C8477DA717](<Notebook/Dell/Latitude/Latitude E5570/5EFE1EB32C53/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/C8477DA717>) |
| 10ec:525a | 1028:079f | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [089B61BB38](<Notebook/Dell/Latitude/Latitude 7280/E9E3F30F4DB0/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/089B61BB38>) |
| 10ec:525a | 1028:08b8 | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [1BB6C1F63F](<Notebook/Dell/Latitude/Latitude 5400/418002D1A36C/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/1BB6C1F63F>) |
| 10ec:525a | 17aa:224f | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [4993AD0FEB](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 5th 20HQS1QC00/BB184D2CE6FD/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/4993AD0FEB>) |
| 10ec:5287 | 1043:202f | Realtek Semic... | RTL8411B PCI Express Card Reader     | 3     | rtsx       | [5624C69D4B](<Notebook/ASUSTek Computer/G551/G551JW/B7E7048EB864/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/5624C69D4B>) |
| 10ec:5209 | 103c:3577 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     |            | [F83C769501](<Notebook/Hewlett-Packard/2000/2000/5F42EBFDBCAE/FREEBSD-12.2/12.2-RELEASE/AMD64/F83C769501>) |
| 10ec:5209 | 104d:90b8 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     | rtsx       | [64F3F02018](<Notebook/Sony/SVF1421/SVF1421DSGW/D451EB9DE7D3/FREEBSD-13.0/13.0-RELEASE/AMD64/64F3F02018>) |
| 10ec:5227 | 103c:2246 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx       | [DA49561A8F](<Notebook/Hewlett-Packard/ProBook/ProBook 430 G2/0B9FDF5DA838/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/DA49561A8F>) |
| 10ec:5227 | 1179:0001 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     |            | [D498FCD3F8](<Notebook/Toshiba/TECRA/TECRA Z40-B/5E426A8E8D03/FREEBSD-11.4-P7/11.4-RELEASE-P7/AMD64/D498FCD3F8>) |
| 10ec:5227 | 17aa:2217 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx       | [39EF89F214](<Notebook/Lenovo/ThinkPad/ThinkPad S1 Yoga 20C0S0M300/DC2E490F82F3/NOMADBSD-5806F915/13.0-RELEASE-P3/AMD64/39EF89F214>) |
| 10ec:5227 | 17aa:503c | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx       | [3C27C8BF31](<Notebook/Lenovo/ThinkPad/ThinkPad L450 20DSS1S402/0FD1E037978C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P4/AMD64/3C27C8BF31>) |
| 10ec:5229 | 1043:202f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     |            | [1697EBB0A5](<Notebook/ASUSTek Computer/Strix/Strix 17 GL703GE/BAA0EBC7F5C2/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/1697EBB0A5>) |
| 10ec:5229 | 17aa:21f3 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx       | [86FD351C81](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349AK1/08273574C200/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/86FD351C81>) |
| 10ec:5229 | 17aa:38cc | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx       | [2F90D5C2BD](<Notebook/Lenovo/IdeaPad/IdeaPad 110S-11IBR 80WG/1319E554F9F6/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/2F90D5C2BD>) |
| 10ec:5229 | 17aa:5000 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx       | [990E05C219](<Notebook/Lenovo/ThinkPad/ThinkPad Edge E430 3254A68/6BEC68E32ADC/FREEBSD-13.0/13.0-RELEASE/AMD64/990E05C219>) |
| 10ec:5229 | 8086:2067 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     |            | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 10ec:522a | 103c:8257 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     |            | [ABC94E9198](<Notebook/Hewlett-Packard/OMEN/OMEN by HP Laptop/BFE1823EBDF1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/ABC94E9198>) |
| 10ec:522a | 103c:83c8 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 10ec:522a | 103c:8730 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [494195B923](<Notebook/Hewlett-Packard/ProBook/ProBook 445 G7/06DE97DEA747/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/494195B923>) |
| 10ec:522a | 1558:a500 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [792FB07DD9](<Notebook/Notebook/NL5/NL5xRU/5E9A5B67425F/FREEBSD-13.0/13.0-RELEASE/AMD64/792FB07DD9>) |
| 10ec:522a | 17aa:2233 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [DBB0E378D5](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS4KH02/DCA0C34D1413/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/DBB0E378D5>) |
| 10ec:522a | 17aa:504a | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     |            | [AA3DEADEDD](<Notebook/Lenovo/ThinkPad/ThinkPad X260 20F5S82N00/610D0A3E578D/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/AA3DEADEDD>) |
| 10ec:522a | 17aa:505d | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [7A61D90A55](<Notebook/Lenovo/ThinkPad/ThinkPad T470p 20J7S0PM00/61DA2865ABE8/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7A61D90A55>) |
| 10ec:522a | 17aa:505f | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [32080A81C5](<Notebook/Lenovo/ThinkPad/ThinkPad L470 20J40013US/A39BB2DC9412/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/32080A81C5>) |
| 10ec:522a | 17aa:5072 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [852A900303](<Notebook/Lenovo/ThinkPad/ThinkPad E490 20N9001SBR/5158B613D693/FREEBSD-13.0/13.0-RELEASE/AMD64/852A900303>) |
| 10ec:522a | 17aa:5126 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [D7812A2905](<Notebook/Lenovo/ThinkPad/ThinkPad X395 20NL000GPG/878AD42630E7/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D7812A2905>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:19e2 |           | Intel            | Atom Processor C3000 Series Quick... | 39    | qat        | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 39    |            | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 23    |            | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 8086:37c8 |           | Intel            | C62x Chipset QuickAssist Technology  | 6     |            | [18576EF86C](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/199DE71C8C4A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/18576EF86C>) |
| 8086:0434 |           | Intel            | DH89XXCC Series QAT                  | 5     |            | [BAB9D9DD6D](<Desktop/Intel/DENLOW_WS/DENLOW_WS/7A23185583F9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BAB9D9DD6D>) |
| 19a2:0800 | 1734:11cc | Emulex           | ServerView iRMC HTI                  | 4     |            | [C9B02E5D7B](<Server/Fujitsu/PRIMERGY/PRIMERGY TX1320 M2/0C5BD48E99F3/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C9B02E5D7B>) |
| 1734:1228 | 1734:1256 | Fujitsu Techn... |                                      | 2     |            | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 8086:19e2 | 8086:19e2 | Intel            | Atom Processor C3000 Series Quick... | 2     | qat        | [B35BA41E9A](<Desktop/ASRockRack/C3558/C3558D4I-4L/00F1FC522527/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B35BA41E9A>) |
| 1000:0a05 | 1000:0a09 | Broadcom / LSI   |                                      | 1     |            | [53A51EC160](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/53A51EC160>) |
| 10de:03f4 | 1462:7597 | Nvidia           | MCP61 SMU                            | 1     |            | [6BE2D8AEC7](<Desktop/MSI/MS/MS-7597/30A30607F88A/FREEBSD-12.2/12.2-RELEASE/AMD64/6BE2D8AEC7>) |
| 10de:0753 | 1025:0157 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 1     |            | [DB1E7A52B9](<Desktop/Acer/Aspire/Aspire X3200/F5C25C81945B/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/DB1E7A52B9>) |
| 10de:0aa3 | 105b:0d52 | Nvidia           | MCP79 Co-processor                   | 1     |            | [79AB8EFB37](<Desktop/Foxconn/nT-330/nT-330i/70806ED76AFE/FREEBSD-12.1-P6/12.1-RELEASE-P6/AMD64/79AB8EFB37>) |
| 10de:0aa3 | 19da:a108 | Nvidia           | MCP79 Co-processor                   | 1     |            | [623EA6A889](<Desktop/Others/Others/Others/2BBBCF62335B/FREEBSD-12.1--HBSD/12.1-RELEASE-P7-HBSD/AMD64/623EA6A889>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 1734:1228 | 1734:1229 | Fujitsu Techn... |                                      | 1     |            | [6E6F1B0F99](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M4/BA1E3C5B14F6/HARDENEDBSD-12.2--HBSD/12.2-STABLE-HBSD/AMD64/6E6F1B0F99>) |
| 8086:1f18 | 15d9:0820 | Intel            | Atom processor C2000 QAT             | 1     |            | [9ECD4CC08D](<Server/Supermicro/A1/A1SRM-2758F/17EBCD48F207/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/9ECD4CC08D>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 141   |            | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 88    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 62    |            | [D1EB8226EB](<Notebook/SIEMENS/SIMATIC/SIMATIC IPC127E/F8EC425F9C5B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D1EB8226EB>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 53    |            | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 53    |            | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:8c3a | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 32    |            | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 31    |            | [C4AA8D3B10](<Desktop/Protectli/FW/FW6/E40CCA659EE8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C4AA8D3B10>) |
| 8086:8c3a | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 30    |            | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:8c3d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 27    | uart       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:a13a | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 26    |            | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 8086:1c3a | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 25    |            | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:1e3a | 1043:84ca | Intel            | 7 Series/C216 Chipset Family MEI ... | 24    |            | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:1e3a | 1458:1c3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 24    |            | [5B6DD82DA8](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/34CE6C299230/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5B6DD82DA8>) |
| 8086:1c3a | 1458:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 23    |            | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 8086:9de0 | 8086:7270 | Intel            | Cannon Point-LP MEI Controller #1    | 23    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:19d3 | 15d9:0969 | Intel            | Atom Processor C3000 Series ME HE... | 22    |            | [67A2A6BA3E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/599C056DD2BE/OPNSENSE-22.1/13.0-STABLE/AMD64/67A2A6BA3E>) |
| 8086:3b64 | 17aa:215f | Intel            | 5 Series/3400 Series Chipset HECI... | 21    |            | [BCD5BEA2B7](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BCD5BEA2B7>) |
| 8086:8c3a | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    |            | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 20    |            | [5A75DB9142](<Notebook/TUXEDO/InfinityBook13/InfinityBook13V3/0B9DECE35038/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/5A75DB9142>) |
| 8086:1c3a | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 19    |            | [148A268A0F](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4293B43/AD955BCC7F71/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/148A268A0F>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 19    |            | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:19d3 | 8086:19d3 | Intel            | Atom Processor C3000 Series ME HE... | 18    |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 18    |            | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:5a9a | 1849:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [3E1591E714](<Desktop/ASRock/J3455/J3455B-ITX/D479CDF18817/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E1591E714>) |
| 8086:5a9c | 8086:7270 | Intel            |                                      | 18    |            | [038B174183](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-22.1/13.0-STABLE/AMD64/038B174183>) |
| 8086:5a9e | 8086:7270 | Intel            |                                      | 18    |            | [038B174183](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-22.1/13.0-STABLE/AMD64/038B174183>) |
| 8086:8c3a | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 18    |            | [E7B4F8151A](<Server/Supermicro/Super/Super Server/A22FC2D5FFA0/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E7B4F8151A>) |
| 8086:8c3b | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 18    |            | [E7B4F8151A](<Server/Supermicro/Super/Super Server/A22FC2D5FFA0/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E7B4F8151A>) |
| 8086:a2ba | 1043:8694 | Intel            | 200 Series PCH CSME HECI #1          | 18    |            | [AE4F0642FD](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/1E747FA168DD/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/AE4F0642FD>) |
| 8086:a360 | 1043:8694 | Intel            | Cannon Lake PCH HECI Controller      | 18    |            | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 8086:5a9a |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 17    |            | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:8c3a | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 17    |            | [ECAEFF1A79](<Server/Supermicro/Super/Super Server/E487EDA705A4/OPNSENSE-22.1/13.0-STABLE/AMD64/ECAEFF1A79>) |
| 8086:8c3b | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 17    |            | [ECAEFF1A79](<Server/Supermicro/Super/Super Server/E487EDA705A4/OPNSENSE-22.1/13.0-STABLE/AMD64/ECAEFF1A79>) |
| 8086:1e3a | 1028:0577 | Intel            | 7 Series/C216 Chipset Family MEI ... | 16    |            | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 16    |            | [360EA3B215](<Desktop/Others/SKYBAY/SKYBAY/81CF0D9B2186/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/360EA3B215>) |
| 8086:1c3a | 8086:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 14    |            | [D46B68CC28](<Desktop/Intel/CARLOW/CARLOW/D91B06809068/OPNSENSE-22.1.1/13.0-STABLE/AMD64/D46B68CC28>) |
| 8086:1d3a | 1028:0528 | Intel            | C600/X79 series chipset MEI Contr... | 14    |            | [5ADD1E88AA](<Server/Dell/OEM-R/OEM-R 720xd/FF3DB6477637/FREEBSD-12.2-P10/12.2-RELEASE-P7/AMD64/5ADD1E88AA>) |
| 8086:1d3b | 1028:0528 | Intel            | C600/X79 series chipset MEI Contr... | 14    |            | [5ADD1E88AA](<Server/Dell/OEM-R/OEM-R 720xd/FF3DB6477637/FREEBSD-12.2-P10/12.2-RELEASE-P7/AMD64/5ADD1E88AA>) |
| 8086:1e3a | 17aa:21fa | Intel            | 7 Series/C216 Chipset Family MEI ... | 14    |            | [06C6A282CA](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23254G7/FF7D8D42B37A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/06C6A282CA>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 14    |            | [64CCF1E6A0](<Notebook/Apple/MacBookPro10/MacBookPro10,1/60ED6011F0FC/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/64CCF1E6A0>) |
| 8086:8c3a | 1849:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 14    |            | [DA796979AC](<Desktop/ASRock/B85/B85M-ITX/C18B8CE60627/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DA796979AC>) |
| 8086:8cba | 1458:1c3a | Intel            | 9 Series Chipset Family ME Interf... | 14    |            | [3CCD5EACE4](<Desktop/Gigabyte Technology/H97/H97N-WIFI/4343EFE08349/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/3CCD5EACE4>) |
| 8086:a2ba | 1458:1c3a | Intel            | 200 Series PCH CSME HECI #1          | 13    |            | [2727A8E439](<Desktop/Gigabyte Technology/H270-Gaming/H270-Gaming 3/92E92186ABE5/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2727A8E439>) |
| 8086:a360 | 1458:1c3a | Intel            | Cannon Lake PCH HECI Controller      | 13    |            | [17B3590A3F](<Desktop/Gigabyte Technology/C246/C246-WU4/4514509F1F50/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/17B3590A3F>) |
| 8086:1c3a | 17aa:21ce | Intel            | 6 Series/C200 Series Chipset Fami... | 12    |            | [8BD2318FB6](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236MBU/D2E0D93C2306/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/8BD2318FB6>) |
| 8086:1e3a | 103c:3397 | Intel            | 7 Series/C216 Chipset Family MEI ... | 12    |            | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:1e3d | 103c:3397 | Intel            | 7 Series/C210 Series Chipset Fami... | 12    | uart       | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:2a44 | 17aa:20e6 | Intel            | Mobile 4 Series Chipset MEI Contr... | 12    |            | [384F10861A](<Notebook/Lenovo/ThinkPad/ThinkPad R500 2718W92/7F30077B1DE1/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/384F10861A>) |
| 8086:319a | 1849:319a | Intel            | Celeron/Pentium Silver Processor ... | 12    |            | [5A614C6238](<Desktop/ASRock/J5040/J5040-ITX/BA57FC9C5E6C/OPNSENSE-22.1/13.0-STABLE/AMD64/5A614C6238>) |
| 8086:8c3a | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 12    |            | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 194   |            | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 127   |            | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 109   |            | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 91    |            | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 72    | ccp        | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 52    |            | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 1022:1486 | 1043:87c0 | AMD              | Starship/Matisse Cryptographic Co... | 27    |            | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 27    |            | [A2EF313477](<Desktop/Protectli/FW/FW2/3CD419539C29/OPNSENSE-22.1.1/13.0-STABLE/AMD64/A2EF313477>) |
| 1022:1456 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) Platf... | 19    |            | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 17    | ccp        | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 177d:0010 | 177d:0001 | Cavium           | CN15XX/CN16XX [Nitrox PX]            | 16    |            | [53A51EC160](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/53A51EC160>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 14    |            | [57721BF0F2](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/734A66ADD4EA/OPNSENSE-22.1/13.0-STABLE/AMD64/57721BF0F2>) |
| 1022:15df | 1043:876b | AMD              | Family 17h (Models 10h-1fh) Platf... | 14    |            | [D57DE875A6](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/51805C43859D/FREEBSD-13.0/13.0-RELEASE/AMD64/D57DE875A6>) |
| 8086:0f18 | 1849:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 14    |            | [B4142103CB](<Desktop/ASRock/Q1900/Q1900B-ITX/A58F88E6A7C3/FREEBSD-12.3-P2/12.3-RELEASE-P1/AMD64/B4142103CB>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 14    |            | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:2298 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    |            | [B64AEB3448](<Server/Supermicro/Super/Super Server/3355157663C7/OPNSENSE-22.1.1/13.0-STABLE/AMD64/B64AEB3448>) |
| 1022:1486 | 1043:8808 | AMD              | Starship/Matisse Cryptographic Co... | 8     |            | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 8086:2298 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     |            | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 1022:15df | 1849:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     |            | [F80D11C4A6](<Desktop/ASRock/4X4-4000/4X4-4000 Series/FF0DB8636C47/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F80D11C4A6>) |
| 8086:0f18 | 1458:1c3a | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 6     |            | [EC336DDAB4](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/FCE9E0893745/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/EC336DDAB4>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     |            | [64707B8717](<Desktop/NU591/1/1.0/686FE3922C3C/OPNSENSE-22.1/13.0-STABLE/AMD64/64707B8717>) |
| 8086:2298 | 1849:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [FB058E0B37](<Desktop/ASRock/N3700/N3700-ITX/77EAC92E80D5/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FB058E0B37>) |
| 1022:1486 | 1462:7c02 | AMD              | Starship/Matisse Cryptographic Co... | 4     |            | [14F1956220](<Desktop/MSI/MS-7/MS-7C02/0BF11DCDAD12/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/14F1956220>) |
| 1022:1578 | 103c:84ac | AMD              | Carrizo Platform Security Processor  | 4     |            | [766E62F699](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/3E8F8F48759C/NOMADBSD-5806F915/13.0-RELEASE/AMD64/766E62F699>) |
| 1022:15df | 17aa:5097 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [6C208C85A5](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6C208C85A5>) |
| 8086:2298 | 1043:8534 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     |            | [289423796B](<Desktop/ASUSTek Computer/All/All Series/D02026182209/PFSENSE-2.5.0/12.2-STABLE/AMD64/289423796B>) |
| 8086:2298 | 1458:1000 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     |            | [5E980B75BC](<Desktop/Gigabyte Technology/GB-BACE/GB-BACE-3150/B48405EE0C5D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5E980B75BC>) |
| 1022:1456 | 1462:7b86 | AMD              | Family 17h (Models 00h-0fh) Platf... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:1498 | 1022:1498 | AMD              | Starship/Matisse PTDMA               | 3     |            | [4E41DC7F8B](<Server/Supermicro/Super/Super Server/C92F203FE90C/FREEBSD-13.0/13.0-RELEASE/AMD64/4E41DC7F8B>) |
| 1022:15df | 17aa:5122 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     |            | [0C153D0C98](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MU000VUS/0748151D3905/MIDNIGHTBSD-2.1.1/2.1.1/AMD64/0C153D0C98>) |
| 1022:15df | 1d05:109f | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     |            | [6F779D5170](<Notebook/TUXEDO/Pulse/Pulse 15 Gen1/C92D236C248C/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/6F779D5170>) |
| 8086:2298 | 1565:3112 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     |            | [536F856D94](<Desktop/Biostar/J3160/J3160NH/F1B8BA6C9B4F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/536F856D94>) |
| 1022:1456 | 1025:1246 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     |            | [9E03A76684](<Notebook/Acer/Predator/Predator PH517-61/401258E70C57/FREEBSD-13.0/13.0-RELEASE/AMD64/9E03A76684>) |
| 1022:1486 | 1043:87cb | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:1486 | 1458:1000 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1022:1486 | 1462:7b86 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 1022:1498 | 1458:1000 | AMD              | Starship/Matisse PTDMA               | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1022:1537 | 17aa:3801 | AMD              | Kabini/Mullins PSP-Platform Secur... | 2     |            | [1D227A9CD2](<Notebook/Lenovo/G50-45/G50-45 80E3/E53F1DE394A5/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/1D227A9CD2>) |
| 1022:1578 | 103c:8330 | AMD              | Carrizo Platform Security Processor  | 2     |            | [8E9A6CFF62](<Notebook/Hewlett-Packard/Laptop/Laptop 15-rb0xx/94A2E681C681/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8E9A6CFF62>) |
| 1022:1578 | 17aa:364f | AMD              | Carrizo Platform Security Processor  | 2     |            | [C43975A08F](<Desktop/Lenovo/IdeaCentre/IdeaCentre 310S-08ASR 90G90068US/439AD74C89CD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/C43975A08F>) |
| 1022:15df | 103c:85e0 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [E7B40F6E3B](<Notebook/Hewlett-Packard/Laptop/Laptop 14-dk0xxx/60E15DE8A8F4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E7B40F6E3B>) |
| 1022:15df | 103c:8786 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [19F307FF6D](<Notebook/Hewlett-Packard/OMEN/OMEN Laptop 15-en0xxx/99830226F687/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/19F307FF6D>) |
| 1022:15df | 103c:87b1 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [B8408CB369](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec1xxx/447033DB0DB6/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/B8408CB369>) |
| 1022:15df | 103c:87d6 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [FFA88D066B](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-1xxx/96EB6BA29D47/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/FFA88D066B>) |
| 1022:15df | 103c:88dd | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [7859F220B9](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec2xxx/32343F8FB2CF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7859F220B9>) |
| 1022:15df | 1043:8809 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [B23AB09F52](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/B23AB09F52>) |
| 1022:15df | 1558:a500 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [792FB07DD9](<Notebook/Notebook/NL5/NL5xRU/5E9A5B67425F/FREEBSD-13.0/13.0-RELEASE/AMD64/792FB07DD9>) |
| 1022:15df | 17aa:3809 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [ADE9F77281](<Notebook/Lenovo/IdeaPad/IdeaPad 330-15ARR 81D2/B11617CFB899/FREEBSD-13.0/13.0-RELEASE/AMD64/ADE9F77281>) |
| 1022:15df | 17aa:3834 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [2A54A0C338](<Notebook/Lenovo/Yoga/Yoga Slim 7 Pro 14ACH5 82MS/FD0797BFCA5B/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/2A54A0C338>) |
| 1022:15df | 17aa:5081 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [D910C79D75](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y1CTO1WW/5E03AED6E452/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D910C79D75>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 37    | fwohci     | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 18    | fwohci     | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 1180:0832 | 17aa:20c7 | Ricoh            | R5C832 IEEE 1394 Controller          | 15    | fwohci     | [F5F25EFDCC](<Notebook/Lenovo/ThinkPad/ThinkPad T61 766301U/A1D00057611B/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/F5F25EFDCC>) |
| 1180:e832 | 17aa:2136 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 12    | fwohci     | [973ADE9E4A](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537WEE/B0EAFA5FD723/OPNSENSE-22.1.2/13.0-STABLE/AMD64/973ADE9E4A>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 9     | fwohci     | [E0CF5200DE](<Notebook/Apple/MacBook4/MacBook4,1/07CFC301CF14/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E0CF5200DE>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 8     | fwohci     | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 1106:3044 | 1043:81fe | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 7     | fwohci     | [FBDE5657E8](<Desktop/IEESA/P5K/P5K PRO/1DF42E107A56/FREEBSD-13.0/13.0-RELEASE/AMD64/FBDE5657E8>) |
| 1106:3044 | 1458:1000 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 7     | fwohci     | [3C315D0C15](<Desktop/Gigabyte Technology/990/990FXA-UD3/30C9592F6A6C/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/3C315D0C15>) |
| 11c1:5811 | 103c:1589 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 7     | fwohci     | [8BD32670C2](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8BD32670C2>) |
| 104c:8024 | 1458:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 6     | fwohci     | [21E4A40D62](<Desktop/Gigabyte Technology/EP45/EP45-UD3R/9AFB90672E3E/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/21E4A40D62>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 6     | fwohci     | [B7FC5EF684](<Desktop/Biostar/X470/X470GTA/2553A631F2D9/FREEBSD-13.0/13.0-RELEASE/AMD64/B7FC5EF684>) |
| 11c1:5811 | 1043:8294 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 6     | fwohci     | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 1180:e832 | 17aa:21ce | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 5     |            | [808F58228E](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236FJ1/72229BBDCAFF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/808F58228E>) |
| 1180:e832 | 1028:040a | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 4     | fwohci     | [8C904D84E0](<Notebook/Dell/Latitude/Latitude E6410/D86C1197F0AC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/8C904D84E0>) |
| 1180:e832 | 17aa:21cf | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 4     |            | [9082353A69](<Notebook/Lenovo/ThinkPad/ThinkPad W520 4276CTO/648C52E5D9D4/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/9082353A69>) |
| 11c1:5811 | 103c:158a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 4     | fwohci     | [A9B66CB0E1](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/A9B66CB0E1>) |
| 104c:8025 |           | Texas Instrum... | TSB82AA2 IEEE-1394b Link Layer Co... | 3     | fwohci     | [D852363467](<Notebook/Apple/MacBookPro4/MacBookPro4,1/A1E7ACA2078D/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/D852363467>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 3     | fwohci     | [BE9D90602D](<Desktop/ASUSTek Computer/P9/P9X79/89D525F0E557/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/BE9D90602D>) |
| 1180:0832 | 1028:024d | Ricoh            | R5C832 IEEE 1394 Controller          | 3     | fwohci     | [FDB3DE3036](<Notebook/Dell/Latitude/Latitude E4300/B023391CA6F2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/FDB3DE3036>) |
| 11c1:5811 | 1028:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 3     | fwohci     | [97781253F2](<Desktop/Dell/Precision/Precision WorkStation T3500/092E81402E7E/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/97781253F2>) |
| 1217:13f7 | 1028:049b | O2 Micro         | 1394 OHCI Compliant Host Controller  | 3     | fwohci     | [1ED3FF35F6](<Notebook/Dell/Latitude/Latitude E5420/7F50D3A16CDB/HELLOSYSTEM-0.5.0/13.0-RELEASE/AMD64/1ED3FF35F6>) |
| 197b:2380 | 1043:8313 | JMicron Techn... | IEEE 1394 Host Controller            | 3     | fwohci     | [5999E0EBFB](<Desktop/ASUSTek Computer/P5P43TD/P5P43TD PRO/CAA935C7EB09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5999E0EBFB>) |
| 104c:8023 | 108e:6676 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 2     |            | [AD993A51ED](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/16A2E5FCDB6A/FREEBSD-12.1/12.1-RELEASE/AMD64/AD993A51ED>) |
| 104c:8023 | 15d9:0805 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 2     |            | [2758B438C6](<Server/Supermicro/X10/X10SAE/4A17C592FC65/TRUENAS-12.2-P2/12.2-RELEASE-P2/AMD64/2758B438C6>) |
| 104c:8024 | 1028:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 2     |            | [EDEF5C789D](<Desktop/Dell/Studio/Studio XPS 9100/AEDEA8FF9972/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/EDEF5C789D>) |
| 1106:3044 | 1849:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 2     |            | [19BA4D2EE9](<Desktop/ASRock/Z77/Z77 Extreme6/929553D2B892/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19BA4D2EE9>) |
| 1106:3403 | 1028:040d | VIA Technologies | VT6315 Series Firewire Controller    | 2     |            | [7F75F30B75](<Desktop/Dell/Studio/Studio XPS 8100/AF73B07C29DA/FREEBSD-12.2/12.2-RELEASE/AMD64/7F75F30B75>) |
| 1106:3403 | 1043:8374 | VIA Technologies | VT6315 Series Firewire Controller    | 2     | fwohci     | [1C30F7523F](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/0638EC1B243E/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/1C30F7523F>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 2     | fwohci     | [40687B0E17](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/23AA4FC47B92/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/40687B0E17>) |
| 1106:3403 | 1849:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 2     |            | [CC090875B1](<Desktop/ASRock/970/970 Extreme4/908880BFE0BC/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/CC090875B1>) |
| 1180:0832 | 1043:1877 | Ricoh            | R5C832 IEEE 1394 Controller          | 2     | fwohci     | [883DED6CB1](<Notebook/ASUSTek Computer/N50/N50Vc/77A5AA89F908/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/883DED6CB1>) |
| 1180:e832 | 17aa:21f6 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 2     | fwohci     | [4E7FC367BC](<Notebook/Lenovo/ThinkPad/ThinkPad W530 2447AV9/778B9CE5B6CA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/4E7FC367BC>) |
| 11c1:5811 | 103c:1309 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     | fwohci     | [B56BD19073](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/44AE2B54DFB8/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B56BD19073>) |
| 11c1:5811 | 103c:130a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     |            | [C2B43EFB8F](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/C2B43EFB8F>) |
| 11c1:5901 | 1b5b:803b | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 2     |            | [DA8A524302](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-12.2-P9/12.2-RELEASE-P7/AMD64/DA8A524302>) |
| 11c1:5903 | 11c1:5900 | LSI              | FW533 [TrueFire] PCIe 1394a Contr... | 2     | fwohci     | [29756C2371](<Notebook/Apple/MacBook5/MacBook5,2/EA861217BDD8/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/29756C2371>) |
| 1217:00f7 | 1179:ff50 | O2 Micro         | Firewire (IEEE 1394)                 | 2     | fwohci     | [13E4AA7026](<Notebook/Toshiba/Satellite/Satellite P300/AFEE934437AF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/13E4AA7026>) |
| 197b:2380 | 103c:17a7 | JMicron Techn... | IEEE 1394 Host Controller            | 2     | fwohci     | [462FC329A9](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570p/8F084339058D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/462FC329A9>) |
| 1033:00cd | 12ee:8010 | NEC Computers    | uPD72870 [Firewarden] IEEE1394a O... | 1     | fwohci     | [E34B6118A2](<Desktop/Hewlett-Packard/Compaq/Compaq 505B Microtower PC/0EF9A1953E0E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E34B6118A2>) |
| 104c:8020 | 15c5:8010 | Texas Instrum... | TSB12LV26 IEEE-1394 Controller (L... | 1     |            | [7E27B1BC46](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/28DD15B58DF2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/7E27B1BC46>) |
| 104c:8023 | 1028:021d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [E78392BC4C](<Desktop/Dell/Precision/Precision WorkStation T7400/1BAEE5C9C3FB/HELLOSYSTEM-0.5.0/12.2-RELEASE-P4/AMD64/E78392BC4C>) |
| 104c:8023 | 1043:808b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [5B1DC84DA5](<Desktop/ASUSTek Computer/P5/P5GD2-Deluxe/30982A88A2F4/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/5B1DC84DA5>) |
| 104c:8023 | 1043:815b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [A471763F19](<Desktop/ASUSTek Computer/P5/P5B-Deluxe/49386BD59CFA/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/A471763F19>) |
| 104c:8023 | 108e:5354 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [DDAE563E41](<Desktop/Sun Microsystems/Ultra/Ultra 27/33F836C0D1ED/FREENAS-11.3-P11/11.3-RELEASE-P11/AMD64/DDAE563E41>) |
| 104c:8023 | 15d9:062c | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [EB73C9D13D](<Desktop/Supermicro/X9/X9DAi/558BB9BB7FC9/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/EB73C9D13D>) |
| 104c:8023 | 17aa:101c | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [428F39CBFF](<Desktop/Lenovo/ThinkStation/ThinkStation S10 6483CTO/53B2C53532C0/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/428F39CBFF>) |
| 104c:8023 | 17aa:101d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [6F464AAD1F](<Desktop/Lenovo/ThinkStation/ThinkStation D10 6493WEU/6A717F675FF7/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/6F464AAD1F>) |
| 104c:8023 | 8086:5044 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [E8F4F644E3](<Desktop/Intel/DG33BU/DG33BU AAD79951-408/9D3335CFA220/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/E8F4F644E3>) |
| 104c:8024 |           | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     |            | [1170B4BFD8](<Desktop/Dell/OptiPlex/OptiPlex 745/0BAF0103F9F5/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/1170B4BFD8>) |
| 104c:8024 | 1019:8056 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     |            | [B82613052E](<Desktop/Acer/ASE380/ASE380-AST180-APM8/D397FBEBCB54/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/B82613052E>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 131   | vgapci     | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 108   | vgapci     | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 54    | vgapci     | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 48    | vgapci     | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 47    | vgapci     | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 47    | vgapci     | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 8086:0f31 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 46    | vgapci     | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:5916 | 8086:2015 | Intel            | HD Graphics 620                      | 43    | vgapci     | [B9475ED44D](<Desktop/Protectli/FW/FW6/3EFC335326E0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/B9475ED44D>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 40    | vgapci     | [53A51EC160](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/53A51EC160>) |
| 8086:0a16 | 8086:0a16 | Intel            | Haswell-ULT Integrated Graphics C... | 35    | vgapci     | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 1002:515e | 103c:31fb | AMD              | ES1000                               | 34    | vgapci     | [FC82E541DC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC82E541DC>) |
| 1002:9831 | 103c:213d | AMD              | Kabini [Radeon HD 8400E]             | 32    | vgapci     | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 102b:0532 | 1028:04dd | Matrox Electr... | MGA G200eW WPCM450                   | 32    | vgapci     | [DA98B2AD6B](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/DA98B2AD6B>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 28    | nvidia     | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 8086:2e32 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 27    | agp        | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:5917 | 8086:2015 | Intel            | UHD Graphics 620                     | 27    | vgapci     | [147ADA1C7F](<Desktop/Protectli/FW/FW6/C384134D9772/OPNSENSE-22.1.2/13.0-STABLE/AMD64/147ADA1C7F>) |
| 8086:a001 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 27    | agp        | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:0412 | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 26    | vgapci     | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:a002 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 26    | vgapci     | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:1616 | 8086:1616 | Intel            | HD Graphics 5500                     | 25    | vgapci     | [4774A3BC2F](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/D5565FC249CA/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4774A3BC2F>) |
| 1002:131c | 103c:8103 | AMD              | Kaveri [Radeon R7 Graphics]          | 24    | vgapci     | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:0412 | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 24    | vgapci     | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 102b:0532 | 15d9:0624 | Matrox Electr... | MGA G200eW WPCM450                   | 22    | vgapci     | [042C1EFAC3](<Desktop/Supermicro/X9/X9SCL-X9SCM/7A7B84FA155C/OPNSENSE-22.7/13.0-STABLE/AMD64/042C1EFAC3>) |
| 1a03:2000 | 15d9:0969 | ASPEED Techno... | ASPEED Graphics Family               | 22    | vgapci     | [67A2A6BA3E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/599C056DD2BE/OPNSENSE-22.1/13.0-STABLE/AMD64/67A2A6BA3E>) |
| 1a03:2000 | 15d9:0813 | ASPEED Techno... | ASPEED Graphics Family               | 21    | vgapci     | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1626 | 8086:1626 | Intel            | HD Graphics 6000                     | 21    | vgapci     | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:3ea0 | 8086:2212 | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 21    | vgapci     | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:5916 |           | Intel            | HD Graphics 620                      | 21    | vgapci     | [C5D261E811](<Desktop/Protectli/FW/FW6/9BA0256CC9A4/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C5D261E811>) |
| 8086:5916 | 8086:2212 | Intel            | HD Graphics 620                      | 19    | vgapci     | [C4AA8D3B10](<Desktop/Protectli/FW/FW6/E40CCA659EE8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C4AA8D3B10>) |
| 1a03:2000 | 15d9:086d | ASPEED Techno... | ASPEED Graphics Family               | 18    | vgapci     | [E7B4F8151A](<Server/Supermicro/Super/Super Server/A22FC2D5FFA0/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E7B4F8151A>) |
| 1002:15d8 | 1002:15d8 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 17    | vgapci     | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 1a03:2000 | 15d9:0921 | ASPEED Techno... | ASPEED Graphics Family               | 17    | vgapci     | [ECAEFF1A79](<Server/Supermicro/Super/Super Server/E487EDA705A4/OPNSENSE-22.1/13.0-STABLE/AMD64/ECAEFF1A79>) |
| 1a03:2000 | 1849:2000 | ASPEED Techno... | ASPEED Graphics Family               | 17    | vgapci     | [B35BA41E9A](<Desktop/ASRockRack/C3558/C3558D4I-4L/00F1FC522527/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B35BA41E9A>) |
| 8086:0046 | 17aa:215a | Intel            | Core Processor Integrated Graphic... | 17    | i915       | [BCD5BEA2B7](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BCD5BEA2B7>) |
| 8086:0126 | 17aa:21da | Intel            | 2nd Generation Core Processor Fam... | 16    | i915       | [148A268A0F](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4293B43/AD955BCC7F71/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/148A268A0F>) |
| 8086:0412 | 8086:0412 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 16    | vgapci     | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 16    | vgapci     | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:5a85 | 1849:5a85 | Intel            | HD Graphics 500                      | 16    | vgapci     | [3E1591E714](<Desktop/ASRock/J3455/J3455B-ITX/D479CDF18817/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E1591E714>) |
| 102b:0534 | 1028:0528 | Matrox Electr... | G200eR2                              | 14    | vgapci     | [5ADD1E88AA](<Server/Dell/OEM-R/OEM-R 720xd/FF3DB6477637/FREEBSD-12.2-P10/12.2-RELEASE-P7/AMD64/5ADD1E88AA>) |
| 8086:0166 | 17aa:21fa | Intel            | 3rd Gen Core processor Graphics C... | 14    | i915       | [06C6A282CA](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23254G7/FF7D8D42B37A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/06C6A282CA>) |
| 8086:22b1 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 14    | vgapci     | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 102b:0532 | 1028:0236 | Matrox Electr... | MGA G200eW WPCM450                   | 13    | vgapci     | [924A792460](<Server/Dell/PowerEdge/PowerEdge R610/34F0B81A9C93/OPNSENSE-22.1/13.0-STABLE/AMD64/924A792460>) |
| 8086:0402 | 8086:0402 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 13    | vgapci     | [A64041317E](<Desktop/CheckPoint/PB-15/PB-15-00/8CAA583F1507/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A64041317E>) |
| 8086:0412 | 1458:d000 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 13    | vgapci     | [CECAC43923](<Desktop/Gigabyte Technology/P85/P85-D3/6D87717FDD41/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CECAC43923>) |
| 8086:0f31 | 1849:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 13    | vgapci     | [B4142103CB](<Desktop/ASRock/Q1900/Q1900B-ITX/A58F88E6A7C3/FREEBSD-12.3-P2/12.3-RELEASE-P1/AMD64/B4142103CB>) |
| 102b:0532 | 1028:0235 | Matrox Electr... | MGA G200eW WPCM450                   | 12    | vgapci     | [5C1EA00DF3](<Server/Dell/PowerEdge/PowerEdge R710/B03FF48F1575/OPNSENSE-22.1/13.0-STABLE/AMD64/5C1EA00DF3>) |
| 1a03:2000 | 15d9:0842 | ASPEED Techno... | ASPEED Graphics Family               | 12    | vgapci     | [1B52653153](<Server/Supermicro/X10/X10SLH-N6-ST031/2DDB2C21F9DF/OPNSENSE-22.1/13.0-STABLE/AMD64/1B52653153>) |
| 8086:0126 | 17aa:21ce | Intel            | 2nd Generation Core Processor Fam... | 12    | i915       | [8BD2318FB6](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236MBU/D2E0D93C2306/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/8BD2318FB6>) |
| 8086:0152 | 1458:d000 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 12    | vgapci     | [459BB6486D](<Desktop/Gigabyte Technology/Z77/Z77N-WIFI/798389D95EE6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/459BB6486D>) |
| 8086:0412 | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 12    | vgapci     | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |

### Input (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 5     | emujoy     | [B7FC5EF684](<Desktop/Biostar/X470/X470GTA/2553A631F2D9/FREEBSD-13.0/13.0-RELEASE/AMD64/B7FC5EF684>) |
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 3     |            | [C3884FAC44](<Desktop/ASUSTek Computer/P8/P8B75-M/D6575EA2BF9C/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/C3884FAC44>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 176   |            | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 64    |            | [1ED23967FD](<Desktop/Others/Others/Others/C29AA24281D9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/1ED23967FD>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 29    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:a121 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 27    |            | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 23    |            | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 23    |            | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 23    |            | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 23    |            | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 22    |            | [67A2A6BA3E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/599C056DD2BE/OPNSENSE-22.1/13.0-STABLE/AMD64/67A2A6BA3E>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 20    |            | [5A75DB9142](<Notebook/TUXEDO/InfinityBook13/InfinityBook13V3/0B9DECE35038/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/5A75DB9142>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 20    |            | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:19de | 8086:7270 | Intel            | Atom Processor C3000 Series Power... | 18    |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 18    |            | [AE4F0642FD](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/1E747FA168DD/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/AE4F0642FD>) |
| 8086:a36f | 1043:8694 | Intel            | Cannon Lake PCH Shared SRAM          | 18    |            | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 16    |            | [346C445C21](<Desktop/MSI/CML-U/CML-U PRO Cubi 5/CF9C6401E02D/OPNSENSE-22.1.2/13.0-STABLE/AMD64/346C445C21>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 16    |            | [B48B628936](<Notebook/MSI/GE76/GE76 Raider 10UG/CBCA63C494E5/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/B48B628936>) |
| 8086:a2a1 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family Po... | 13    |            | [2727A8E439](<Desktop/Gigabyte Technology/H270-Gaming/H270-Gaming 3/92E92186ABE5/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2727A8E439>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 13    |            | [A2C59D02EE](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/EBD53B4A056D/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A2C59D02EE>) |
| 8086:a121 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [7987A8B851](<Desktop/Gigabyte Technology/H110/H110M-S2H/DC0C8E934748/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/7987A8B851>) |
| 8086:a36f | 1849:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 12    |            | [44FD3CD83C](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.1/13.0-STABLE/AMD64/44FD3CD83C>) |
| 8086:a1a1 | 15d9:0986 | Intel            | C620 Series Chipset Family Power ... | 11    |            | [68B13705C8](<Server/Supermicro/Super/Super Server/AB927389C02E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/68B13705C8>) |
| 8086:a2a1 | 1849:a2a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 11    |            | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:9def |           | Intel            | Cannon Point-LP Shared SRAM          | 10    |            | [D86C621EF0](<Notebook/Sony/VJS121/VJS121C11N/985CFCF7555D/NOMADBSD-5806F915/13.0-RELEASE/AMD64/D86C621EF0>) |
| 8086:a121 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [D7ADCA8CAC](<Desktop/NetCom IT/pczB/pczB1116/0CB716CAF1D6/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/D7ADCA8CAC>) |
| 8086:a121 | 1849:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [5C58D01F2D](<Desktop/ASRock/H110/H110M-ITX/D5B0B257B774/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5C58D01F2D>) |
| 8086:9def | 8086:2074 | Intel            | Cannon Point-LP Shared SRAM          | 9     |            | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 8     |            | [C81D79BBE7](<Desktop/ASRock/H570/H570M-ITX-ac/707C9EE26C47/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C81D79BBE7>) |
| 8086:9d21 | 8086:2068 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:a121 | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [86B6B8373C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/0E7724AD506F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/86B6B8373C>) |
| 8086:a121 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [06DB2A9C2F](<Server/Supermicro/Super/Super Server/4C2A3BFED0EE/FREEBSD-12.2-P9/12.2-RELEASE-P6/AMD64/06DB2A9C2F>) |
| 1912:0011 |           | Renesas Techn... | SH7757 PCIe End-Point [PBI]          | 7     |            | [88AB309AEB](<Server/Dell/PowerEdge/PowerEdge R220/0CDE8047F735/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/88AB309AEB>) |
| 8086:43ef | 1043:8694 | Intel            | Tiger Lake-H Shared SRAM             | 7     |            | [4E352AE90E](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-E/32F7ED74CFA8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4E352AE90E>) |
| 8086:9d21 | 17aa:2238 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:9d21 | 17aa:5062 | Intel            | Sunrise Point-LP PMC                 | 7     |            | [2E1C585715](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S0BM01/C223E0B01844/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2E1C585715>) |
| 8086:9def | 17aa:2279 | Intel            | Cannon Point-LP Shared SRAM          | 7     |            | [4147A5824D](<Notebook/Lenovo/ThinkPad/ThinkPad T590 20N4CTO1WW/3C494D1552EB/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/4147A5824D>) |
| 8086:a121 | 1028:06bb | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [4B1A5F0AB0](<Desktop/Dell/OptiPlex/OptiPlex 3040/52B86D78970C/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/4B1A5F0AB0>) |
| 8086:02ef | 8086:2081 | Intel            | Comet Lake PCH-LP Shared SRAM        | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:9d21 | 103c:8079 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [F259F73C17](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/372FB522FD12/OPNSENSE-22.1/13.0-STABLE/AMD64/F259F73C17>) |
| 8086:a121 | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [6BAEAF5D48](<Desktop/Dell/OptiPlex/OptiPlex 7040/481FC557306C/OPNSENSE-22.1.1/13.0-STABLE/AMD64/6BAEAF5D48>) |
| 8086:a121 | 1028:06ba | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [0072834141](<Desktop/Dell/OptiPlex/OptiPlex 5040/7E980BAD0CDC/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/0072834141>) |
| 8086:a121 | 103c:8169 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [F449B4CD6C](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/12A699DD3987/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F449B4CD6C>) |
| 8086:06ef | 1849:06ef | Intel            | Comet Lake PCH Shared SRAM           | 5     |            | [F56CDD9FEA](<Desktop/ASRock/H470/H470M-ITX-ac/CE2789C7FDFA/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/F56CDD9FEA>) |
| 8086:34ef |           | Intel            | Ice Lake-LP DRAM Controller          | 5     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:9d21 | 17aa:224b | Intel            | Sunrise Point-LP PMC                 | 5     |            | [6C895CB96F](<Notebook/Lenovo/ThinkPad/ThinkPad T470s W10DG 20JTS0A900/5B70EA1A7528/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/6C895CB96F>) |
| 8086:9def | 17aa:314d | Intel            | Cannon Point-LP Shared SRAM          | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:a0ef | f111:0001 | Intel            | Tiger Lake-LP Shared SRAM            | 5     |            | [1F58E0594F](<Notebook/Framework/Laptop/Laptop/12E6C3C95AB5/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1F58E0594F>) |
| 8086:a121 | 103c:805d | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [629FF57837](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 SFF/D284171DD296/OPNSENSE-22.1.2/13.0-STABLE/AMD64/629FF57837>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [566FD652E7](<Desktop/Others/Others/Others/676B0F8582A3/OPNSENSE-22.1.1/13.0-STABLE/AMD64/566FD652E7>) |
| 8086:a3a1 | 1043:8694 | Intel            | Cannon Lake PCH Power Management ... | 5     |            | [1DAFDCC71A](<Desktop/ASUSTek Computer/PRIME/PRIME H410M-A/9F70D0828451/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1DAFDCC71A>) |

### Modem (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:266d | 1014:0574 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 3     |            | [6FD6FD89C5](<Notebook/IBM/ThinkPad/ThinkPad R52 185869G/DED57F076B3E/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/6FD6FD89C5>) |
| 1039:7013 | 1043:1816 | Silicon Integ... | AC'97 Modem Controller               | 1     |            | [83106A58EF](<Notebook/ASUSTek Computer/A/A9T/CD438D683462/FREEBSD-13.0-P4/13.0-RELEASE-P4/I386/83106A58EF>) |
| 1039:7013 | 14c0:0012 | Silicon Integ... | AC'97 Modem Controller               | 1     |            | [56A5581907](<Notebook/Acer/TravelMate/TravelMate 270/A6730E9E5FB4/FREEBSD-12.1-P10/12.1-RELEASE-P9/I386/56A5581907>) |
| 10b9:5457 | 103c:0850 | ULi Electronics  | M5457 AC'97 Modem Controller         | 1     |            | [B7C0CB252F](<Notebook/Hewlett-Packard/nx/nx9010/C0E10A77D690/FREEBSD-12.1-P10/12.1-RELEASE-P9/I386/B7C0CB252F>) |
| 8086:2486 | 144f:1050 | Intel            | 82801CA/CAM AC'97 Modem Controller   | 1     |            | [41E40C653E](<Notebook/Gateway/Solo/Solo 450/3E11C9EAD72B/FREEBSD-12.2-P4/12.2-RELEASE-P4/I386/41E40C653E>) |
| 8086:24c6 | 1014:0559 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 1     |            | [ACF931A3E0](<Notebook/IBM/ThinkPad/ThinkPad T42 2374K46/696337B58774/FREEBSD-13.0-P2/13.0-RELEASE-P1/I386/ACF931A3E0>) |
| 8086:24c6 | 104d:818c | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 1     |            | [F2F3923EA6](<Notebook/Sony/VGN-S/VGN-S150/194677ED6A48/FREEBSD-13.0-CURRENT/13.0-CURRENT/I386/F2F3923EA6>) |
| 8086:24c6 | 10f7:834b | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 1     |            | [F6EC2858A5](<Notebook/Matsushita Electric Industrial/CF-T2/CF-T2BW1AXR/C85EB722BC8F/FREEBSD-14.0-CURRENT/14.0-CURRENT/I386/F6EC2858A5>) |
| 8086:266d | 14f1:5423 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 1     |            | [D2CBB1F229](<Notebook/Dell/Latitude/Latitude D610/65F95AF4AC23/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/D2CBB1F229>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 26    |            | [2D1BF5A79A](<Desktop/BESSTAR Tech/HM/HM90/1F0A034DBC90/OPNSENSE-22.1.1/13.0-STABLE/AMD64/2D1BF5A79A>) |
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 14    |            | [C4AA8D3B10](<Desktop/Protectli/FW/FW6/E40CCA659EE8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C4AA8D3B10>) |
| 14e4:1570 | 14e4:1570 | Broadcom         | 720p FaceTime HD Camera              | 9     |            | [E04A1B354C](<Notebook/Apple/MacBookPro12/MacBookPro12,1/98B93121E415/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/E04A1B354C>) |
| 1022:15e2 | 1849:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 6     |            | [F80D11C4A6](<Desktop/ASRock/4X4-4000/4X4-4000 Series/FF0DB8636C47/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F80D11C4A6>) |
| 1022:15e2 | 17aa:5097 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     |            | [6C208C85A5](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6C208C85A5>) |
| 1022:15e2 | 1d05:109f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     |            | [6F779D5170](<Notebook/TUXEDO/Pulse/Pulse 15 Gen1/C92D236C248C/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/6F779D5170>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     |            | [3454B5492B](<Notebook/AZW/BT3/BT3 PRO/8FB6E0960427/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/3454B5492B>) |
| 1022:15e2 | 103c:85e0 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [E7B40F6E3B](<Notebook/Hewlett-Packard/Laptop/Laptop 14-dk0xxx/60E15DE8A8F4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E7B40F6E3B>) |
| 1022:15e2 | 103c:8730 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [494195B923](<Notebook/Hewlett-Packard/ProBook/ProBook 445 G7/06DE97DEA747/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/494195B923>) |
| 1022:15e2 | 103c:8786 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [19F307FF6D](<Notebook/Hewlett-Packard/OMEN/OMEN Laptop 15-en0xxx/99830226F687/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/19F307FF6D>) |
| 1022:15e2 | 103c:87b1 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [B8408CB369](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec1xxx/447033DB0DB6/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/B8408CB369>) |
| 1022:15e2 | 103c:88dd | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [7859F220B9](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec2xxx/32343F8FB2CF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7859F220B9>) |
| 1022:15e2 | 1558:a500 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [792FB07DD9](<Notebook/Notebook/NL5/NL5xRU/5E9A5B67425F/FREEBSD-13.0/13.0-RELEASE/AMD64/792FB07DD9>) |
| 1022:15e2 | 17aa:3836 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [2A54A0C338](<Notebook/Lenovo/Yoga/Yoga Slim 7 Pro 14ACH5 82MS/FD0797BFCA5B/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/2A54A0C338>) |
| 1022:15e2 | 17aa:5081 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [D910C79D75](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y1CTO1WW/5E03AED6E452/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D910C79D75>) |
| 1022:15e2 | 17aa:5082 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [ED75B3D15B](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 1 20UF000QRT/28FFDBA7F5C3/FREEBSD-13.0-BETA1/13.0-BETA2/AMD64/ED75B3D15B>) |
| 1022:15e2 | 17aa:5125 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [7A706E46DE](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NJS0KP00/BBAE20B5A9E1/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/7A706E46DE>) |
| 1022:15e2 | 17aa:5126 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [D7812A2905](<Notebook/Lenovo/ThinkPad/ThinkPad X395 20NL000GPG/878AD42630E7/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D7812A2905>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     |            | [2ECB6FABA3](<Mini Pc/AMI/Aptio/Aptio CRB/FEA9A2F7C9FB/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2ECB6FABA3>) |
| 1022:15e2 | 1025:134d | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [1AC21E1660](<Notebook/Acer/Aspire/Aspire A315-42/DE5FD26538FB/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1AC21E1660>) |
| 1022:15e2 | 1025:1456 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [7FB743C654](<Notebook/Acer/Aspire/Aspire A315-23/F20A633E5003/FREEBSD-13.0/13.0-RELEASE/AMD64/7FB743C654>) |
| 1022:15e2 | 1028:09f5 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [9933A09C4F](<Notebook/Dell/G5/G5 5505/919E52ABE5A8/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/9933A09C4F>) |
| 1022:15e2 | 1028:0a12 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [8D4B342FDA](<Notebook/Dell/Inspiron/Inspiron 3505/4D47E92A2957/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8D4B342FDA>) |
| 1022:15e2 | 103c:8433 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [5A242D9C9E](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0CFBD160A1EE/FREEBSD-12.2/12.2-RELEASE/AMD64/5A242D9C9E>) |
| 1022:15e2 | 103c:8522 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15e2 | 103c:8523 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:15e2 | 103c:85b3 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [ECF07AD5FE](<Notebook/Hewlett-Packard/Laptop/Laptop 17-ca1xxx/17899E306221/FREEBSD-12.2-P2/12.2-RELEASE/AMD64/ECF07AD5FE>) |
| 1022:15e2 | 103c:888a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:15e2 | 1043:1862 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [CF360A6098](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X515UA_M515UA/E0D904EE5AF7/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/CF360A6098>) |
| 1022:15e2 | 1043:1d42 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [20CDC9D999](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA402RJ_GA402RJ/8B17C1C0752C/FREEBSD-13.0/13.0-RELEASE/AMD64/20CDC9D999>) |
| 1022:15e2 | 1458:1000 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [817CB3E603](<Desktop/Gigabyte Technology/BSRE/BSRE-1605/493093EBE60A/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/817CB3E603>) |
| 1022:15e2 | 17aa:318e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [115F2C7B35](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75t Gen 2 11KECTO1WW/85187679911A/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/115F2C7B35>) |
| 1022:15e2 | 17aa:3190 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1022:15e2 | 17aa:3728 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [7BA1CCC40D](<Desktop/Lenovo/IdeaCentre/IdeaCentre 5 14ARE05 90Q30008US/2ECD21E7A105/FREEBSD-12.2-P8/12.2-RELEASE-P8/AMD64/7BA1CCC40D>) |
| 1022:15e2 | 17aa:380f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [E660899158](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ARH05 82EY/9C5FD9AECCA2/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/E660899158>) |
| 1022:15e2 | 17aa:381c | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [1A13B7BFD1](<Notebook/Lenovo/Legion/Legion 5 15ARH05 82B5/F36FD56B8299/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/1A13B7BFD1>) |
| 1022:15e2 | 17aa:381e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [BF56B2A81A](<Notebook/Lenovo/XiaoXinPro-13ARE/XiaoXinPro-13ARE 2020 82DM/F0E303B67D1F/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/BF56B2A81A>) |
| 1022:15e2 | 17aa:3830 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [42B4BCBCC2](<Notebook/Lenovo/ThinkBook/ThinkBook 14 G3 ACL 21A2/0D8018F67544/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/42B4BCBCC2>) |
| 1022:15e2 | 17aa:5124 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [A1FC75A9B7](<Notebook/Lenovo/ThinkPad/ThinkPad E495 20NE0001US/84A292AF9512/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/A1FC75A9B7>) |
| 1022:15e2 | 17aa:5127 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [0E5E228D18](<Notebook/Lenovo/ThinkPad/ThinkPad T495s 20QKS1812F/C3CD82558289/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/0E5E228D18>) |
| 1022:15e2 | 19e5:3e14 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [D776625073](<Notebook/HUAWEI/HN-WX9/HN-WX9X/9CD27AA9940C/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D776625073>) |
| 1022:15e2 | 1a0e:1043 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [22C1AEFEAB](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A17 FA706II_FA706II/6F2D3FCBAD55/FREEBSD-13.0/13.0-RELEASE/AMD64/22C1AEFEAB>) |
| 1022:15e2 | 1d72:1951 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [A7BF2669CE](<Notebook/Timi/RedmiBook/RedmiBook 14 II/E502DAC4FD8B/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/A7BF2669CE>) |
| 1022:15e2 | 1e21:1043 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [11BBFCE5D4](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506IH_FA506IH/791A09644467/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/11BBFCE5D4>) |
| 1022:15e2 | 1e83:3e33 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [B7841E03F5](<Notebook/HUAWEI/KLVL-WXX/KLVL-WXX9/C229C05C2950/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/B7841E03F5>) |
| 1131:7130 |           | Philips Semic... | SAA7130 Video Broadcast Decoder      | 1     |            | [C6DA80D54B](<Desktop/Gigabyte Technology/H61/H61M-D2P-B3/BC7CD91E287F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C6DA80D54B>) |
| 1131:7133 | 1043:4876 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 1     |            | [F521976730](<Desktop/ASUSTek Computer/M3A78/M3A78 PRO/F18AAB4E7AFE/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/F521976730>) |
| 1131:7133 | 16be:0010 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 1131:7146 | 13c2:101a | Philips Semic... | SAA7146                              | 1     |            | [8CF113AC55](<Desktop/ASUSTek Computer/V-P7/V-P7H55E/0AE0678A444E/NOMADBSD-5806F915/13.0-RELEASE/AMD64/8CF113AC55>) |
| 1131:7160 | 1043:48b5 | Philips Semic... | SAA7160                              | 1     |            | [5FE1A9E521](<Desktop/ASUSTek Computer/P7H55-M/P7H55-M LX/B84E7E871D43/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/5FE1A9E521>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 113   | em         | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 101   | igb        | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 61    | igb        | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 56    | re         | [A58B9A4F8F](<Desktop/Pegatron/IPM41/IPM41-D3/38C292CE2082/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A58B9A4F8F>) |
| 8086:1521 | 8086:5001 | Intel            | I350 Gigabit Network Connection      | 45    | igb        | [456B55DE38](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243/OPNSENSE-22.1.3/13.0-STABLE/AMD64/456B55DE38>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 44    | igb        | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 44    | igb        | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 38    | re         | [D3596DFF89](<Desktop/ASRock/X570/X570 PG Velocita/A90551D8040B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D3596DFF89>) |
| 8086:10e8 | 8086:a02c | Intel            | 82576 Gigabit Network Connection     | 38    | igb        | [22846D44FB](<Server/Dell/PowerEdge/PowerEdge R815/6788CB525396/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/22846D44FB>) |
| 8086:1521 |           | Intel            | I350 Gigabit Network Connection      | 37    | igb        | [A2C59D02EE](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/EBD53B4A056D/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A2C59D02EE>) |
| 8086:10bc | 103c:704b | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 34    | em         | [4503BC72FA](<Desktop/Dell/PowerEdge/PowerEdge T30/9D60EB15AE00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/4503BC72FA>) |
| 14e4:163b | 1028:04dd | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 32    | bce        | [DA98B2AD6B](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/DA98B2AD6B>) |
| 8086:150e | 103c:1780 | Intel            | 82580 Gigabit Network Connection     | 32    | igb        | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:105e | 8086:125e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 30    | em         | [10A235FE8F](<Desktop/Intel/DH67BL/DH67BL AAG10189-211/E50082B9AB3B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/10A235FE8F>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 28    | em         | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 8086:15e4 |           | Intel            | Ethernet Connection X553 1GbE        | 28    | ix         | [67A2A6BA3E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/599C056DD2BE/OPNSENSE-22.1/13.0-STABLE/AMD64/67A2A6BA3E>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 26    | re         | [0F75361707](<Desktop/Dell/OptiPlex/OptiPlex 755/EA117E39981F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F75361707>) |
| 8086:15e5 |           | Intel            | Ethernet Connection X553 1GbE        | 26    | ix         | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:1572 |           | Intel            | Ethernet Controller X710 for 10Gb... | 24    | ixl        | [1ED23967FD](<Desktop/Others/Others/Others/C29AA24281D9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/1ED23967FD>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 23    | nfe        | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 8086:1f41 | 15d9:1f41 | Intel            | Ethernet Connection I354             | 23    | igb        | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1533 | 15bb:30e0 | Intel            | I210 Gigabit Network Connection      | 22    | igb        | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 10ec:8168 | 103c:8103 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 21    | re         | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 10ec:8168 | 1734:11ff | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 21    | re         | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 14e4:165f | 1028:1f5b | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 21    | bge        | [7CD73D4820](<Server/Others/0H47HH/0H47HH A07/82377467A588/OPNSENSE-22.1.2/13.0-STABLE/AMD64/7CD73D4820>) |
| 8086:1536 |           | Intel            | I210 Gigabit Fiber Network Connec... | 21    | igb        | [BAB9D9DD6D](<Desktop/Intel/DENLOW_WS/DENLOW_WS/7A23185583F9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BAB9D9DD6D>) |
| 8086:15b8 | 1043:8672 | Intel            | Ethernet Connection (2) I219-V       | 21    | em         | [A780A7BAB2](<Desktop/ASUSTek Computer/Maximus/Maximus VIII HERO/734460839920/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A780A7BAB2>) |
| 8086:10bc | 8086:11bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 20    | em         | [40407EBFEA](<Desktop/MSI/MS/MS-7995/08A5DC59F2E9/OPNSENSE-22.1.1/13.0-STABLE/AMD64/40407EBFEA>) |
| 10ec:8169 | 10ec:8169 | Realtek Semic... | RTL8169 PCI Gigabit Ethernet Cont... | 19    | re         | [DD33780E1B](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY ECONEL 50/B268E1785214/OPNSENSE-22.1/13.0-STABLE/AMD64/DD33780E1B>) |
| 8086:15ac | 15d9:15ac | Intel            | Ethernet Connection X552 10 GbE SFP+ | 19    | ix         | [ECAEFF1A79](<Server/Supermicro/Super/Super Server/E487EDA705A4/OPNSENSE-22.1/13.0-STABLE/AMD64/ECAEFF1A79>) |
| 14e4:1639 | 103c:7055 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 18    | bce        | [FC82E541DC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC82E541DC>) |
| 10ec:8168 | 1028:0612 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | re         | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:10c9 | 8086:a02f | Intel            | 82576 Gigabit Network Connection     | 17    | igb        | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 8086:1502 | 15d9:1502 | Intel            | 82579LM Gigabit Network Connectio... | 17    | em         | [042C1EFAC3](<Desktop/Supermicro/X9/X9SCL-X9SCM/7A7B84FA155C/OPNSENSE-22.7/13.0-STABLE/AMD64/042C1EFAC3>) |
| 8086:1528 | 8086:0001 | Intel            | Ethernet Controller 10-Gigabit X5... | 16    | ix         | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 8086:156f |           | Intel            | Ethernet Connection I219-LM          | 16    | em         | [11D762AD87](<Desktop/Shuttle/DS77/DS77U/2528D5D211E8/OPNSENSE-22.1/13.0-STABLE/AMD64/11D762AD87>) |
| 8086:15ad | 15d9:15ad | Intel            | Ethernet Connection X552/X557-AT ... | 16    | ix         | [E7B4F8151A](<Server/Supermicro/Super/Super Server/A22FC2D5FFA0/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E7B4F8151A>) |
| 8086:15b8 | 1849:15b8 | Intel            | Ethernet Connection (2) I219-V       | 15    | em         | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 1022:1458 | 1022:1458 | AMD              | Family 17h Processor 10 Gb Ethern... | 14    | ax         | [4D8F19BA12](<Notebook/Deciso/Netboard/Netboard A20/94D2C7F0ED24/OPNSENSE-22.1/13.0-STABLE/AMD64/4D8F19BA12>) |
| 8086:10bc | 8086:10bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 14    | em         | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 8086:10c9 | 1dcf:0319 | Intel            | 82576 Gigabit Network Connection     | 14    | igb        | [DA98B2AD6B](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/DA98B2AD6B>) |
| 8086:10d6 | 8086:145a | Intel            | 82575GB Gigabit Network Connection   | 14    | igb        | [A6ABB45607](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8S16X0J/968E3838A942/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A6ABB45607>) |
| 8086:153b | 1458:e000 | Intel            | Ethernet Connection I217-V           | 14    | em         | [3CCD5EACE4](<Desktop/Gigabyte Technology/H97/H97N-WIFI/4343EFE08349/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/3CCD5EACE4>) |
| 8086:27dc | 8086:27dc | Intel            | NM10/ICH7 Family LAN Controller      | 14    | fxp        | [DED64258B4](<Desktop/Others/Others/Others/96A056EA1F97/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/DED64258B4>) |
| 10ec:8168 | 19da:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | re         | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:107d | 8086:1082 | Intel            | 82572EI Gigabit Ethernet Controll... | 13    | em         | [A488C9AF25](<Desktop/Dell/OptiPlex/OptiPlex 7010/78AA11104573/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A488C9AF25>) |
| 8086:1502 | 103c:3397 | Intel            | 82579LM Gigabit Network Connectio... | 13    | em         | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:153a | 103c:1998 | Intel            | Ethernet Connection I217-LM          | 13    | em         | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:37d0 | 15d9:37d0 | Intel            | Ethernet Connection X722 for 10Gb... | 13    | ixl        | [68B13705C8](<Server/Supermicro/Super/Super Server/AB927389C02E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/68B13705C8>) |
| 11ab:436a | 11ab:00ba | Marvell Techn... | 88E8058 PCI-E Gigabit Ethernet Co... | 12    | mskc       | [E0CF5200DE](<Notebook/Apple/MacBook4/MacBook4,1/07CFC301CF14/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E0CF5200DE>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 91    | iwlwifi    | [B23AB09F52](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/B23AB09F52>) |
| 8086:0085 | 8086:1311 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 65    | iwn        | [148A268A0F](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4293B43/AD955BCC7F71/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/148A268A0F>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 45    | iwm        | [7FB743C654](<Notebook/Acer/Aspire/Aspire A315-23/F20A633E5003/FREEBSD-13.0/13.0-RELEASE/AMD64/7FB743C654>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 43    | iwm        | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 39    | iwm        | [F449B4CD6C](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/12A699DD3987/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F449B4CD6C>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 34    | iwm        | [D8F0949991](<Desktop/Dell/OptiPlex/OptiPlex 9020/76964B2E7E4F/OPNSENSE-22.1/13.0-STABLE/AMD64/D8F0949991>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 33    | iwm        | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 30    | iwm        | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:08b2 | 8086:c270 | Intel            | Wireless 7260                        | 25    | iwm        | [0FBC782835](<Notebook/Lenovo/ThinkPad/ThinkPad L440 20ASS0FP00/DB867CFAF011/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0FBC782835>) |
| 8086:095b | 8086:5210 | Intel            | Wireless 7265                        | 23    | iwm        | [BC2860431E](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS0VH08/CDAB4EDF622D/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/BC2860431E>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 23    | iwm        | [F333ED9201](<Notebook/Lenovo/Yoga/Yoga S730-13IWL 81J0/69CAD6B3B2BA/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F333ED9201>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 21    | ath        | [B95DA98F21](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B95DA98F21>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 20    | iwm        | [DD57366224](<Notebook/Lenovo/IdeaPad/IdeaPad Y700-15ISK 80NV/2BD0319875C3/FREEBSD-13.1-PRERELEASE/13.1-PRERELEASE/AMD64/DD57366224>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 19    |            | [65FBD31DA1](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/5416334E31EB/OPNSENSE-22.1/13.0-STABLE/AMD64/65FBD31DA1>) |
| 168c:002a | 168c:3099 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 19    | ath        | [D08DA1541A](<Desktop/Others/Others/Others/F95318B57CEC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D08DA1541A>) |
| 8086:24f3 | 8086:0130 | Intel            | Wireless 8260                        | 19    | iwm        | [DBB0E378D5](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS4KH02/DCA0C34D1413/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/DBB0E378D5>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 18    | iwm        | [B0314F9200](<Notebook/Dell/Latitude/Latitude E5440/8E86E40B0A52/FREEBSD-13.0-P6/13.0-RELEASE-P4/AMD64/B0314F9200>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 18    | iwm        | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 18    | iwm        | [384D2F888B](<Notebook/Lenovo/Legion/Legion Y540-15IRH 81SX/DB27396229F8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/384D2F888B>) |
| 8086:24f3 | 8086:0010 | Intel            | Wireless 8260                        | 17    | iwm        | [E4F43CFCAD](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HHCTO1WW/771FB79FBCC7/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/E4F43CFCAD>) |
| 8086:24fd | 8086:0050 | Intel            | Wireless 8265 / 8275                 | 17    | iwm        | [8A0388B49D](<Notebook/Dell/Latitude/Latitude 7480/720DC2256764/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/8A0388B49D>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 17    | iwm        | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:088e | 8086:4060 | Intel            | Centrino Advanced-N 6235             | 16    | iwn        | [E2CC942E3E](<Notebook/Hewlett-Packard/EliteBook/EliteBook Folio 9470m/CDDE53EE5395/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E2CC942E3E>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 15    | iwm        | [AE56D2CEDD](<Notebook/Dell/Latitude/Latitude D630/94367DB4F4E1/NOMADBSD-5806F915/13.0-RELEASE/AMD64/AE56D2CEDD>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 15    | iwm        | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:24f3 | 8086:1010 | Intel            | Wireless 8260                        | 15    | iwm        | [5A75DB9142](<Notebook/TUXEDO/InfinityBook13/InfinityBook13V3/0B9DECE35038/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/5A75DB9142>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 14    |            | [23FAF80BFE](<Mini Pc/BESSTAR Tech/GK/GK41/CA411C944153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23FAF80BFE>) |
| 8086:0084 | 8086:1315 | Intel            | Centrino Wireless-N 1000 [Condor ... | 13    | iwn        | [BCD5BEA2B7](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BCD5BEA2B7>) |
| 8086:3165 | 8086:4410 | Intel            | Wireless 3165                        | 13    | iwm        | [5426AB5339](<Desktop/Dell/Inspiron/Inspiron 3880/2697DA2D36E5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5426AB5339>) |
| 8086:31dc | 8086:0034 | Intel            | Gemini Lake PCH CNVi WiFi            | 13    | iwm        | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 168c:0036 | 1028:020c | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 12    | ath        | [2583B22E8D](<Notebook/Dell/Latitude/Latitude 3540/7AC0C6F5AC8B/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/2583B22E8D>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 12    |            | [0FA4700D17](<Notebook/Lenovo/ThinkPad/ThinkPad E15 20RD0011MX/534BB4FF83C1/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0FA4700D17>) |
| 8086:422b | 8086:1121 | Intel            | Centrino Ultimate-N 6300             | 12    | iwn        | [E0576DD008](<Notebook/Dell/Latitude/Latitude E6540/47352B0D75D6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E0576DD008>) |
| 8086:4237 | 8086:1211 | Intel            | PRO/Wireless 5100 AGN [Shiloh] Ne... | 12    | iwn        | [CA05F41685](<Desktop/PC Engines/APU/APU/255F220BC72B/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/CA05F41685>) |
| 8086:4239 | 8086:1311 | Intel            | Centrino Advanced-N 6200             | 12    | iwn        | [4A5BA4F3E4](<Notebook/Lenovo/ThinkPad/ThinkPad X201 32492EU/BADAE72EA873/GHOSTBSD-21.12.29/13.0-STABLE/AMD64/4A5BA4F3E4>) |
| 14e4:4727 | 1028:0010 | Broadcom         | BCM4313 802.11bgn Wireless Networ... | 11    |            | [5C6B94DF97](<Notebook/Dell/Latitude/Latitude E5510/9E3287D69794/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5C6B94DF97>) |
| 8086:0082 | 8086:1321 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 11    | iwn        | [FDDE41404D](<Notebook/Dell/Latitude/Latitude E6430/9A4F06581327/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/FDDE41404D>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 11    | iwm        | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:24f3 | 8086:0050 | Intel            | Wireless 8260                        | 11    | iwm        | [9E479E9C50](<Notebook/Dell/Latitude/Latitude E5470/A17BA6584F09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/9E479E9C50>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 11    | iwm        | [37A7A11604](<Desktop/AZW/GK/GK55/20D5EB09357F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/37A7A11604>) |
| 8086:4238 | 8086:1111 | Intel            | Centrino Ultimate-N 6300             | 11    | iwn        | [9082353A69](<Notebook/Lenovo/ThinkPad/ThinkPad W520 4276CTO/648C52E5D9D4/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/9082353A69>) |
| 14e4:4331 | 14e4:4331 | Broadcom         | BCM4331 802.11a/b/g/n                | 10    | bwn_pci    | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 10    | ath        | [5C8F3708B1](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/EA7F2653211E/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/5C8F3708B1>) |
| 168c:003c |           | Qualcomm Atheros | QCA986x/988x 802.11ac Wireless Ne... | 10    |            | [C2B05FC937](<Desktop/PC Engines/APU/APU2/59362430025E/OPNSENSE-22.1/13.0-STABLE/AMD64/C2B05FC937>) |
| 8086:0082 | 8086:1301 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 10    | iwn        | [F47789D894](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570p/6FBB1F806232/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/F47789D894>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 10    | iwlwifi    | [1F58E0594F](<Notebook/Framework/Laptop/Laptop/12E6C3C95AB5/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1F58E0594F>) |
| 14e4:432b | 106b:008d | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 9     | bwn_pci    | [53B106BBB6](<Notebook/Apple/MacBookPro5/MacBookPro5,5/E84835CFE8B8/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/53B106BBB6>) |
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 9     | bwn_pci    | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 9     | ath        | [84D7FB3F1E](<Desktop/ASUSTek Computer/All/All Series/46CAE9B0FE93/GHOSTBSD-22.01.28/13.0-STABLE/AMD64/84D7FB3F1E>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 9     |            | [B1D702812E](<Notebook/Lenovo/IdeaPad/IdeaPad L340-17IRH Gaming 81LL/93EFE155F7C0/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B1D702812E>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 538   | igb        | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 288   | re         | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 8086:157b |           | Intel            | I210 Gigabit Network Connection      | 216   | igb        | [B9475ED44D](<Desktop/Protectli/FW/FW6/3EFC335326E0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/B9475ED44D>) |
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 136   | re         | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 10ec:8168 | 1849:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 120   | re         | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 91    | igb        | [E9DCB4C3DA](<Server/Supermicro/X10/X10SLH-F-X10SLM+-F/E871858972D6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E9DCB4C3DA>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 86    | em         | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 83    | em         | [53A51EC160](<Desktop/Cisco/SALEEN/SALEEN/29CC5C091FD8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/53A51EC160>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 76    | re         | [19BA4D2EE9](<Desktop/ASRock/Z77/Z77 Extreme6/929553D2B892/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19BA4D2EE9>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 71    | re         | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:1502 | 17aa:21ce | Intel            | 82579LM Gigabit Network Connectio... | 42    | em         | [148A268A0F](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4293B43/AD955BCC7F71/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/148A268A0F>) |
| 8086:1502 | 17aa:21f3 | Intel            | 82579LM Gigabit Network Connectio... | 40    | em         | [86FD351C81](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349AK1/08273574C200/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/86FD351C81>) |
| 8086:153a | 1028:05a4 | Intel            | Ethernet Connection I217-LM          | 39    | em         | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 37    | re         | [B95DA98F21](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B95DA98F21>) |
| 10ec:8168 | 1043:8505 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 37    | re         | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:150e | 8086:12a2 | Intel            | 82580 Gigabit Network Connection     | 34    | igb        | [EB936BEBDE](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/82FF1FFF56D4/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EB936BEBDE>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 29    | igb        | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 10ec:8168 | 103c:213d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 28    | re         | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:105e | 103c:7044 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 28    | em         | [4D7D8FD92B](<Desktop/Dell/Precision/Precision 3440/269F11AAE867/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D7D8FD92B>) |
| 10ec:8139 | 10ec:8139 | Realtek Semic... | RTL-8100/8101L/8139 PCI Fast Ethe... | 26    | rl         | [624B4F4DE7](<Desktop/ASRock/ConRoe1333/ConRoe1333-D667/7131BB32A319/OPNSENSE-22.1.1/13.0-STABLE/AMD64/624B4F4DE7>) |
| 14e4:165f | 103c:2133 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 25    | bge        | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 8086:105e | 8086:135e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 25    | em         | [8AEE77286E](<Desktop/MSI/MS/MS-7760/658E325602DE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8AEE77286E>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 25    | igb        | [91B1EC3B93](<Desktop/Gigabyte Technology/X570/X570 I AORUS PRO WIFI/7DE2E889826B/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/91B1EC3B93>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 23    | igb        | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 10ec:8168 | 1043:8554 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 22    | re         | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 22    | bge        | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:1521 | 8086:0002 | Intel            | I350 Gigabit Network Connection      | 22    | igb        | [F617253042](<Desktop/WYSE/DQ/DQ Class/4143A473FC4C/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F617253042>) |
| 8086:1502 | 1028:047e | Intel            | 82579LM Gigabit Network Connectio... | 21    | em         | [4B4B77D8F3](<Desktop/Dell/OptiPlex/OptiPlex 790/14F63C42DF90/OPNSENSE-22.1/13.0-STABLE/AMD64/4B4B77D8F3>) |
| 8086:10ea | 17aa:2153 | Intel            | 82577LM Gigabit Network Connection   | 19    | em         | [BCD5BEA2B7](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BCD5BEA2B7>) |
| 8086:15a2 | 17aa:2226 | Intel            | Ethernet Connection (3) I218-LM      | 19    | em         | [BC2860431E](<Notebook/Lenovo/ThinkPad/ThinkPad T450 20BUS0VH08/CDAB4EDF622D/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/BC2860431E>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 19    | ixl        | [E1FCEAABC0](<Server/Supermicro/Super/Super Server/2C4DC94123A5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E1FCEAABC0>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 17    | em         | [FE27EAC86A](<Desktop/Supermicro/X9/X9SCAA--L/7975E278700E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FE27EAC86A>) |
| 8086:1533 | 1849:1533 | Intel            | I210 Gigabit Network Connection      | 16    | igb        | [606D3086CE](<Desktop/ASRockRack/X470/X470D4U/2AA488105C83/OPNSENSE-22.1.2/13.0-STABLE/AMD64/606D3086CE>) |
| 11ab:4364 | 1043:81f8 | Marvell Techn... | 88E8056 PCI-E Gigabit Ethernet Co... | 15    | mskc       | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 8086:107c | 8086:1376 | Intel            | 82541PI Gigabit Ethernet Controller  | 15    | em         | [8BD32670C2](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8BD32670C2>) |
| 14e4:165f | 103c:22e8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 14    | bge        | [57721BF0F2](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/734A66ADD4EA/OPNSENSE-22.1/13.0-STABLE/AMD64/57721BF0F2>) |
| 8086:105e | 8086:115e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 14    | em         | [11123031C6](<Desktop/Dell/OptiPlex/OptiPlex 7020/5EBB3A42B428/OPNSENSE-22.1/13.0-STABLE/AMD64/11123031C6>) |
| 8086:1528 | 15d9:1528 | Intel            | Ethernet Controller 10-Gigabit X5... | 14    | ix         | [1B52653153](<Server/Supermicro/X10/X10SLH-N6-ST031/2DDB2C21F9DF/OPNSENSE-22.1/13.0-STABLE/AMD64/1B52653153>) |
| 8086:155a | 17aa:2214 | Intel            | Ethernet Connection I218-LM          | 14    | em         | [2AF47B6502](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ006HUS/5B022BB303EA/NOMADBSD-5806F915/13.0-RELEASE/AMD64/2AF47B6502>) |
| 10ec:8168 | 1043:200f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | re         | [28B3002182](<Notebook/ASUSTek Computer/X555/X555LA/845132047FF4/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/28B3002182>) |
| 8086:156f | 17aa:2233 | Intel            | Ethernet Connection I219-LM          | 13    | em         | [DBB0E378D5](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS4KH02/DCA0C34D1413/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/DBB0E378D5>) |
| 14e4:1639 | 1028:0235 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 12    | bce        | [5C1EA00DF3](<Server/Dell/PowerEdge/PowerEdge R710/B03FF48F1575/OPNSENSE-22.1/13.0-STABLE/AMD64/5C1EA00DF3>) |
| 8086:15b7 |           | Intel            | Ethernet Connection (2) I219-LM      | 12    | em         | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:15b8 | 1458:e000 | Intel            | Ethernet Connection (2) I219-V       | 12    | em         | [9752EAE10B](<Desktop/Gigabyte Technology/B150/B150-HD3P-CF/D61C920AED27/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9752EAE10B>) |
| 8086:15bc | 1043:8672 | Intel            | Ethernet Connection (7) I219-V       | 12    | em         | [D377E06101](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/4AD30B4CEDEC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D377E06101>) |
| 10ec:8168 | 1043:859e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 11    | re         | [ABED13FD92](<Desktop/ASUSTek Computer/All/All Series/BBA636E81190/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/ABED13FD92>) |
| 15b3:1003 | 15b3:0055 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 11    | mlx4_core  | [C518DED272](<Desktop/ASRock/Z170M/Z170M Extreme4/9326F1E80AA0/FREEBSD-13.0/13.0-RELEASE/AMD64/C518DED272>) |
| 15b3:6750 | 15b3:0015 | Mellanox Tech... | MT26448 [ConnectX EN 10GigE, PCIe... | 10    | mlx4_core  | [B51A078BBF](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/D585E1B9E2E6/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/B51A078BBF>) |
| 8086:10d3 | 1043:8369 | Intel            | 82574L Gigabit Network Connection    | 10    | em         | [1347F15B56](<Server/ASUSTek Computer/P8B-M/P8B-M Series/36C252462A40/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/1347F15B56>) |
| 8086:150e | 1734:11a8 | Intel            | 82580 Gigabit Network Connection     | 10    | igb        | [045FA8357E](<Server/Swyx Solutions/SwyxExpress/SwyxExpress/09FA3CB37C02/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/045FA8357E>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 184   | sdhci_pci  | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 50    | sdhci_pci  | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 43    | sdhci_pci  | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:31d0 | 8086:7270 | Intel            | SD Host Controller                   | 27    | sdhci_pci  | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 14e4:16bc |           | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 26    | sdhci_pci  | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:9dc4 | 8086:7270 | Intel            | Cannon Point-LP SD Host Controller   | 20    | sdhci_pci  | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:9df5 | 8086:7270 | Intel            | BayHubTech Integrated SD controller  | 20    | sdhci_pci  | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 15    | sdhci_pci  | [0051C86E4C](<Desktop/CNCTION-IAF-E3845/Others/Others/7FBC058A3FA5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0051C86E4C>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 15    | sdhci_pci  | [23FAF80BFE](<Mini Pc/BESSTAR Tech/GK/GK41/CA411C944153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23FAF80BFE>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 12    | sdhci_pci  | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:5acc | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | sdhci_pci  | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | sdhci_pci  | [35869FF0DB](<Notebook/Jumper/EZbook/EZbook/BCAD2CB6073B/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/35869FF0DB>) |
| 1180:0822 | 17aa:20c8 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 9     | sdhci_pci  | [9CC0F26F6F](<Notebook/Lenovo/ThinkPad/ThinkPad R61 8935WCS/1AC798DB7C89/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/9CC0F26F6F>) |
| 8086:19db | 8086:7270 | Intel            | Atom Processor C3000 Series SD Ho... | 9     | sdhci_pci  | [629B185E76](<Desktop/Silicom/80300/80300-0134-g01/A09461A2F391/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/629B185E76>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 8     | sdhci_pci  | [35869FF0DB](<Notebook/Jumper/EZbook/EZbook/BCAD2CB6073B/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/35869FF0DB>) |
| 8086:31cc | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     | sdhci_pci  | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 6     | sdhci_pci  | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 197b:2381 | 17aa:212d | JMicron Techn... | Standard SD Host Controller          | 6     | sdhci_pci  | [B0A9802877](<Notebook/Lenovo/ThinkPad/ThinkPad SL510 2847R96/16806C85881A/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B0A9802877>) |
| 8086:31cc | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 6     | sdhci_pci  | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 1022:7806 | 1022:7806 | AMD              | FCH SD Flash Controller              | 4     | sdhci_pci  | [E098F52D51](<Desktop/Hewlett-Packard/Pro/Pro 3405 Series/195D130691D4/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/E098F52D51>) |
| 1180:e822 | 1028:040a | Ricoh            | MMC/SD Host Controller               | 4     | sdhci_pci  | [8C904D84E0](<Notebook/Dell/Latitude/Latitude E6410/D86C1197F0AC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/8C904D84E0>) |
| 1180:e822 | 1179:0001 | Ricoh            | MMC/SD Host Controller               | 4     | sdhci_pci  | [2AC9BEA1E6](<Notebook/Toshiba/PORTEGE/PORTEGE M780/9BA4726CBC1C/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/2AC9BEA1E6>) |
| 1217:8221 | 1028:0493 | O2 Micro         | OZ600FJ0/OZ900FJ0/OZ600FJS SD/MMC... | 4     | sdhci_pci  | [2E8B431CC6](<Notebook/Dell/Latitude/Latitude E6420/6637B5C9AD24/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/2E8B431CC6>) |
| 1217:8221 | 1028:0534 | O2 Micro         | OZ600FJ0/OZ900FJ0/OZ600FJS SD/MMC... | 4     | sdhci_pci  | [FDDE41404D](<Notebook/Dell/Latitude/Latitude E6430/9A4F06581327/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/FDDE41404D>) |
| 1217:8520 | 1028:05be | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [E0576DD008](<Notebook/Dell/Latitude/Latitude E6540/47352B0D75D6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E0576DD008>) |
| 1217:8520 | 1028:05cc | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [1847C0AADB](<Notebook/Dell/Precision/Precision M4800/534E5DEB811F/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/1847C0AADB>) |
| 1217:8621 | 17aa:5068 | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [BE311B6A34](<Notebook/Lenovo/ThinkPad/ThinkPad E580 20KSCTO1WW/FE16B0524669/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/BE311B6A34>) |
| 14e4:16bc | 1025:0504 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 4     | sdhci_pci  | [BD22FC8A49](<Notebook/Acer/Aspire/Aspire 5750G/1FF59E502D89/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/BD22FC8A49>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | sdhci_pci  | [6DB720018B](<Desktop/Beckhoff Automation/CBxx/CBxx63/D2340951707E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6DB720018B>) |
| 8086:2294 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | sdhci_pci  | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 4     | sdhci_pci  | [09D0D26857](<Desktop/ShenZhen MinWin Technology/3865/3865U-6L/35A56C7E9951/OPNSENSE-22.1/13.0-STABLE/AMD64/09D0D26857>) |
| 1022:7813 | 1022:7813 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [C6A85DA1D5](<Desktop/M613/G420/G420N1WNS/19C20EF0FF54/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A85DA1D5>) |
| 1180:0822 | 1028:024d | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 3     | sdhci_pci  | [FDB3DE3036](<Notebook/Dell/Latitude/Latitude E4300/B023391CA6F2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/FDB3DE3036>) |
| 1217:8321 | 1028:049b | O2 Micro         | OZ600RJ0/OZ900RJ0/OZ600RJS SD/MMC... | 3     | sdhci_pci  | [1ED3FF35F6](<Notebook/Dell/Latitude/Latitude E5420/7F50D3A16CDB/HELLOSYSTEM-0.5.0/13.0-RELEASE/AMD64/1ED3FF35F6>) |
| 1217:8520 | 1028:062e | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [8A3867F171](<Notebook/Dell/Latitude/Latitude E7450/384980EB885D/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/8A3867F171>) |
| 1217:8621 | 17aa:5072 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [98072B8DB6](<Notebook/Lenovo/ThinkPad/ThinkPad E590 20NB0012RT/F14FDAEA6645/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/98072B8DB6>) |
| 14e4:16bc | 14e4:96bc | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 3     | sdhci_pci  | [64CCF1E6A0](<Notebook/Apple/MacBookPro10/MacBookPro10,1/60ED6011F0FC/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/64CCF1E6A0>) |
| 17a0:9750 | 17aa:2279 | Genesys Logic    | GL9750 SD Host Controller            | 3     | sdhci_pci  | [4147A5824D](<Notebook/Lenovo/ThinkPad/ThinkPad T590 20N4CTO1WW/3C494D1552EB/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/4147A5824D>) |
| 8086:02c4 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS1: eMMC         | 3     | sdhci_pci  | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:02f5 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS3               | 3     | sdhci_pci  | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:9d2b | 8086:9d2b | Intel            | Skylake-U/Y SCC: eMMC                | 3     | sdhci_pci  | [4CE05F93A8](<Notebook/Chuwi/MiniBook/MiniBook/7C143B97B52B/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/4CE05F93A8>) |
| 1022:7813 | 1025:0865 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [5306253276](<Notebook/Acer/Aspire/Aspire E5-521G/6C9872FCA376/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/5306253276>) |
| 1022:7813 | 17aa:3801 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [1D227A9CD2](<Notebook/Lenovo/G50-45/G50-45 80E3/E53F1DE394A5/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/1D227A9CD2>) |
| 1180:0822 | 1043:1877 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 2     | sdhci_pci  | [883DED6CB1](<Notebook/ASUSTek Computer/N50/N50Vc/77A5AA89F908/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/883DED6CB1>) |
| 1180:e823 | 10f7:8338 | Ricoh            | PCIe SDXC/MMC Host Controller        | 2     | sdhci_pci  | [04A42812BB](<Notebook/Panasonic/CF-19/CF-19AHNC8FN/4A900A110949/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/04A42812BB>) |
| 1217:7120 | 1179:ff50 | O2 Micro         | Integrated MMC/SD Controller         | 2     | sdhci_pci  | [13E4AA7026](<Notebook/Toshiba/Satellite/Satellite P300/AFEE934437AF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/13E4AA7026>) |
| 1217:8320 | 1028:04a3 | O2 Micro         | OZ600RJ1/OZ900RJ1 SD/MMC Card Rea... | 2     | sdhci_pci  | [2F848FD2C0](<Notebook/Dell/Precision/Precision M4600/B6B9C54EEBB2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/2F848FD2C0>) |
| 1217:8520 | 1028:05bd | O2 Micro         | SD/MMC Card Reader Controller        | 2     | sdhci_pci  | [8FA2C1F5C4](<Notebook/Dell/Latitude/Latitude E6440/90F4D14BB79B/FREEBSD-13.0-P2/13.0-RELEASE-P1/AMD64/8FA2C1F5C4>) |
| 1217:8520 | 1028:05cb | O2 Micro         | SD/MMC Card Reader Controller        | 2     | sdhci_pci  | [6EC8FD788A](<Notebook/Dell/Latitude/Latitude E7440/CB2F8814A9AD/FREEBSD-12.2-P5/12.2-RELEASE-P4/AMD64/6EC8FD788A>) |
| 1217:8520 | 1028:05de | O2 Micro         | SD/MMC Card Reader Controller        | 2     | sdhci_pci  | [B0314F9200](<Notebook/Dell/Latitude/Latitude E5440/8E86E40B0A52/FREEBSD-13.0-P6/13.0-RELEASE-P4/AMD64/B0314F9200>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 26    |            | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 24    | ipmi       | [7E329C839E](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/8D54A568AC95/OPNSENSE-22.1/13.0-STABLE/AMD64/7E329C839E>) |
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 23    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 22    |            | [67A2A6BA3E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/599C056DD2BE/OPNSENSE-22.1/13.0-STABLE/AMD64/67A2A6BA3E>) |
| 8086:9dc5 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 20    | ig4iic     | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:9de8 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 20    | ig4iic     | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:9de9 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 20    | ig4iic     | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 19    |            | [1ED23967FD](<Desktop/Others/Others/Others/C29AA24281D9/OPNSENSE-22.1.2/13.0-STABLE/AMD64/1ED23967FD>) |
| 8086:19e0 | 8086:7270 | Intel            | Atom Processor C3000 Series SPI C... | 18    |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:a324 | 1043:8694 | Intel            | Cannon Lake PCH SPI Controller       | 18    |            | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 8086:a324 | 1849:a324 | Intel            | Cannon Lake PCH SPI Controller       | 12    |            | [44FD3CD83C](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.1/13.0-STABLE/AMD64/44FD3CD83C>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 11    |            | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:a1a4 | 15d9:0986 | Intel            | C620 Series Chipset Family SPI Co... | 11    |            | [68B13705C8](<Server/Supermicro/Super/Super Server/AB927389C02E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/68B13705C8>) |
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:34ab | 8086:7270 | Intel            | Ice Lake-LP Serial IO SPI Control... | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 10    |            | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 9     |            | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 1425:5601 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 7     |            | [2AC306B67F](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2AC306B67F>) |
| 8086:22c1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | ig4iic     | [F8F7CD07ED](<Desktop/Protectli/FW2/FW2B/F0A1BF20D7FE/OPNSENSE-22.1/13.0-STABLE/AMD64/F8F7CD07ED>) |
| 8086:22c2 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | ig4iic     | [F8F7CD07ED](<Desktop/Protectli/FW2/FW2B/F0A1BF20D7FE/OPNSENSE-22.1/13.0-STABLE/AMD64/F8F7CD07ED>) |
| 8086:43a4 | 1043:8694 | Intel            | Tiger Lake-H SPI Controller          | 7     |            | [4E352AE90E](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-E/32F7ED74CFA8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4E352AE90E>) |
| 8086:43e8 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 7     | ig4iic     | [4E352AE90E](<Desktop/ASUSTek Computer/PRIME/PRIME H510M-E/32F7ED74CFA8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4E352AE90E>) |
| 8086:9da4 | 17aa:2279 | Intel            | Cannon Point-LP SPI Controller       | 7     |            | [4147A5824D](<Notebook/Lenovo/ThinkPad/ThinkPad T590 20N4CTO1WW/3C494D1552EB/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/4147A5824D>) |
| 8086:9de8 | 17aa:2279 | Intel            | Cannon Point-LP Serial IO I2C Con... | 7     | ig4iic     | [4147A5824D](<Notebook/Lenovo/ThinkPad/ThinkPad T590 20N4CTO1WW/3C494D1552EB/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/4147A5824D>) |
| 8086:a324 | 15d9:1b0e | Intel            | Cannon Lake PCH SPI Controller       | 7     |            | [A1CF339702](<Server/Supermicro/Super/Super Server/AEAD0BFD0A36/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/A1CF339702>) |
| 8086:a368 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 7     |            | [A1CF339702](<Server/Supermicro/Super/Super Server/AEAD0BFD0A36/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/A1CF339702>) |
| 8086:a369 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 7     |            | [A1CF339702](<Server/Supermicro/Super/Super Server/AEAD0BFD0A36/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/A1CF339702>) |
| 1425:4601 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 6     |            | [51EBC2C3FD](<Desktop/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/F7BBE9119163/OPNSENSE-22.1.2/13.0-STABLE/AMD64/51EBC2C3FD>) |
| 8086:02a4 | 8086:2081 | Intel            | Comet Lake SPI (flash) Controller    | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:02c5 | 8086:7270 | Intel            | Comet Lake Serial IO I2C Host Con... | 6     | ig4iic     | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:02e8 | 8086:2081 | Intel            | Serial IO I2C Host Controller        | 6     | ig4iic     | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:02ea | 8086:2081 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 6     | ig4iic     | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 6     |            | [AFA675E7A7](<Desktop/Gigabyte Technology/H470/H470 HD3/15B827E9B70C/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/AFA675E7A7>) |
| 8086:43a4 | 1849:43a4 | Intel            | Tiger Lake-H SPI Controller          | 6     |            | [C81D79BBE7](<Desktop/ASRock/H570/H570M-ITX-ac/707C9EE26C47/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C81D79BBE7>) |
| 8086:43e9 | 1043:8694 | Intel            | 500 Series Chipset Family LPSS: I... | 6     | ig4iic     | [39B116CCFC](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-I GAMING WIFI/BB678DCF1D6F/OPNSENSE-22.1/13.0-STABLE/AMD64/39B116CCFC>) |
| 8086:9da4 | 1297:4076 | Intel            | Cannon Point-LP SPI Controller       | 6     |            | [1300217458](<Desktop/Shuttle/DS10/DS10U/578D3382155D/OPNSENSE-22.1.1/13.0-STABLE/AMD64/1300217458>) |
| 8086:9da4 | 17aa:5072 | Intel            | Cannon Point-LP SPI Controller       | 6     |            | [98072B8DB6](<Notebook/Lenovo/ThinkPad/ThinkPad E590 20NB0012RT/F14FDAEA6645/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/98072B8DB6>) |
| 8086:a324 | 1590:028d | Intel            | Cannon Lake PCH SPI Controller       | 6     |            | [A2C59D02EE](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/EBD53B4A056D/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A2C59D02EE>) |
| 8086:06a4 | 1849:06a4 | Intel            | Comet Lake PCH SPI Controller        | 5     |            | [F56CDD9FEA](<Desktop/ASRock/H470/H470M-ITX-ac/CE2789C7FDFA/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/F56CDD9FEA>) |
| 8086:5ac8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     |            | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:9da4 | 17aa:314d | Intel            | Cannon Point-LP SPI Controller       | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:a0a4 | f111:0001 | Intel            | Tiger Lake-LP SPI Controller         | 5     |            | [1F58E0594F](<Notebook/Framework/Laptop/Laptop/12E6C3C95AB5/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1F58E0594F>) |
| 8086:a0e8 | f111:0001 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 5     | ig4iic     | [1F58E0594F](<Notebook/Framework/Laptop/Laptop/12E6C3C95AB5/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1F58E0594F>) |
| 8086:a0e9 | f111:0001 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 5     | ig4iic     | [1F58E0594F](<Notebook/Framework/Laptop/Laptop/12E6C3C95AB5/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1F58E0594F>) |
| 8086:a0eb | f111:0001 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 5     | ig4iic     | [1F58E0594F](<Notebook/Framework/Laptop/Laptop/12E6C3C95AB5/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1F58E0594F>) |
| 8086:a324 | 1028:088f | Intel            | Cannon Lake PCH SPI Controller       | 5     |            | [545DACB881](<Server/Dell/PowerEdge/PowerEdge R240/19A6101614C9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/545DACB881>) |
| 10ec:816c | 1043:85b5 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:02e8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 4     | ig4iic     | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |
| 8086:06a4 | 1028:09aa | Intel            | Comet Lake PCH SPI Controller        | 4     |            | [456B55DE38](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243/OPNSENSE-22.1.3/13.0-STABLE/AMD64/456B55DE38>) |
| 8086:06e8 | 1028:09aa | Intel            | Comet Lake PCH Serial IO I2C Cont... | 4     | ig4iic     | [456B55DE38](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243/OPNSENSE-22.1.3/13.0-STABLE/AMD64/456B55DE38>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 115   | pchtherm   | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 60    |            | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 57    | ig4iic     | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 57    | ig4iic     | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 44    | ig4iic     | [CE3FEDCBAF](<Desktop/Others/Others/Others/7A46CAB81031/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CE3FEDCBAF>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 43    | ig4iic     | [CE3FEDCBAF](<Desktop/Others/Others/Others/7A46CAB81031/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CE3FEDCBAF>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 43    | ig4iic     | [CE3FEDCBAF](<Desktop/Others/Others/Others/7A46CAB81031/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CE3FEDCBAF>) |
| 8086:204d |           | Intel            | Sky Lake-E M3KTI Registers           | 42    |            | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 8086:2015 |           | Intel            | Sky Lake-E Ubox Registers            | 39    |            | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 37    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:204c |           | Intel            | Sky Lake-E M3KTI Registers           | 29    |            | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 29    | ig4iic     | [CE3FEDCBAF](<Desktop/Others/Others/Others/7A46CAB81031/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CE3FEDCBAF>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 29    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | ig4iic     | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 26    | ig4iic     | [B54ACE2A34](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/3406497B002A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B54ACE2A34>) |
| 8086:1903 | 8086:7270 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 23    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 23    |            | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:9df9 | 8086:7270 | Intel            | Cannon Point-LP Thermal Controller   | 23    | pchtherm   | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 22    |            | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 22    |            | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 22    |            | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 21    |            | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:3b32 | 17aa:2190 | Intel            | 5 Series/3400 Series Chipset Ther... | 21    |            | [BCD5BEA2B7](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BCD5BEA2B7>) |
| 8086:1903 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 20    |            | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:2058 |           | Intel            | Sky Lake-E KTI 0                     | 20    |            | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 20    |            | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 20    |            | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | uart       | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | uart       | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:9d31 | 8086:9d31 | Intel            | Sunrise Point-LP Thermal subsystem   | 20    | pchtherm   | [5A75DB9142](<Notebook/TUXEDO/InfinityBook13/InfinityBook13V3/0B9DECE35038/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/5A75DB9142>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 19    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    | uart       | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    | uart       | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    | uart       | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    | uart       | [1E8AC02926](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-G 08-31-2020 14:01:20/5E7431735CCD/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E8AC02926>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:8c24 | 15d9:086d | Intel            | 8 Series Chipset Family Thermal M... | 18    | pchtherm   | [E7B4F8151A](<Server/Supermicro/Super/Super Server/A22FC2D5FFA0/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E7B4F8151A>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 18    | pchtherm   | [1C45CD1B45](<Desktop/Others/Others/Others/097BA985D9D0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/1C45CD1B45>) |
| 8086:31ac | 8086:31ac | Intel            | Celeron/Pentium Silver Processor ... | 17    | ig4iic     | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:31b2 | 8086:31b2 | Intel            | Celeron/Pentium Silver Processor ... | 17    | ig4iic     | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 17    | uart       | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 202   | intsmb     | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 176   | ichsmb     | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 132   | ichsmb     | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 126   | ichsmb     | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | ichsmb     | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 62    | ichsmb     | [D1EB8226EB](<Notebook/SIEMENS/SIMATIC/SIMATIC IPC127E/F8EC425F9C5B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D1EB8226EB>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 54    | intsmb     | [606D3086CE](<Desktop/ASRockRack/X470/X470D4U/2AA488105C83/OPNSENSE-22.1.2/13.0-STABLE/AMD64/606D3086CE>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 54    | ichsmb     | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 53    | ichsmb     | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 1022:790b | 1458:5001 | AMD              | FCH SMBus Controller                 | 47    | intsmb     | [A5FD383C40](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/7FCEC9A2C51B/FREEBSD-13.1-PRERELEASE/13.1-PRERELEASE/AMD64/A5FD383C40>) |
| 1022:790b | 1849:790b | AMD              | FCH SMBus Controller                 | 45    | intsmb     | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1022:790b | 1849:ffff | AMD              | FCH SMBus Controller                 | 41    | intsmb     | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:27da | 8086:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 40    | ichsmb     | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 37    | ichsmb     | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 36    | ichsmb     | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 1022:790b | 1043:87c0 | AMD              | FCH SMBus Controller                 | 34    | intsmb     | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 8086:283e | 8086:283e | Intel            | 82801H (ICH8 Family) SMBus Contro... | 34    | ichsmb     | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:8c22 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 33    | ichsmb     | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 1022:780b | 103c:213d | AMD              | FCH SMBus Controller                 | 32    | intsmb     | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:1c22 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 32    | ichsmb     | [DA98B2AD6B](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/DA98B2AD6B>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 31    | ichsmb     | [A2EF313477](<Desktop/Protectli/FW/FW2/3CD419539C29/OPNSENSE-22.1.1/13.0-STABLE/AMD64/A2EF313477>) |
| 8086:8c22 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 30    | ichsmb     | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 1002:4385 | 1002:4385 | AMD              | SBx00 SMBus Controller               | 28    | intsmb     | [1CCF85F60D](<Notebook/ASUSTek Computer/1215/1215B/A9FC3E123192/FREEBSD-13.0/13.0-RELEASE/AMD64/1CCF85F60D>) |
| 8086:a123 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 27    | ichsmb     | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 1022:790b | 1043:8747 | AMD              | FCH SMBus Controller                 | 25    | intsmb     | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 8086:1c22 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 25    | ichsmb     | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:1e22 | 1458:5001 | Intel            | 7 Series/C216 Chipset Family SMBu... | 25    | ichsmb     | [5B6DD82DA8](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/34CE6C299230/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5B6DD82DA8>) |
| 8086:3a30 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 25    | ichsmb     | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 1022:780b | 103c:8103 | AMD              | FCH SMBus Controller                 | 24    | intsmb     | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:1e22 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family SMBu... | 24    | ichsmb     | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 23    |            | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 8086:1c22 | 1458:5001 | Intel            | 6 Series/C200 Series Chipset Fami... | 23    | ichsmb     | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 8086:9da3 | 8086:7270 | Intel            | Cannon Point-LP SMBus Controller     | 23    |            | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 8086:19df | 15d9:0969 | Intel            | Atom Processor C3000 Series SMBus... | 22    | ichsmb     | [67A2A6BA3E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/599C056DD2BE/OPNSENSE-22.1/13.0-STABLE/AMD64/67A2A6BA3E>) |
| 8086:1c22 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 22    | ichsmb     | [042C1EFAC3](<Desktop/Supermicro/X9/X9SCL-X9SCM/7A7B84FA155C/OPNSENSE-22.7/13.0-STABLE/AMD64/042C1EFAC3>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 22    | ichsmb     | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | ichsmb     | [D46B68CC28](<Desktop/Intel/CARLOW/CARLOW/D91B06809068/OPNSENSE-22.1.1/13.0-STABLE/AMD64/D46B68CC28>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | ichsmb     | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:3b30 | 17aa:2167 | Intel            | 5 Series/3400 Series Chipset SMBu... | 21    | ichsmb     | [BCD5BEA2B7](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BCD5BEA2B7>) |
| 8086:8c22 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ichsmb     | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 20    | ichsmb     | [5A75DB9142](<Notebook/TUXEDO/InfinityBook13/InfinityBook13V3/0B9DECE35038/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/5A75DB9142>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 20    | ichsmb     | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 19    | intsmb     | [0404FCFC3B](<Desktop/ASUSTek Computer/M5/M5A88-M/5B5ADE5E3B56/XIGMANAS-12.3-P2/12.3-RELEASE-P2/AMD64/0404FCFC3B>) |
| 1022:780b | 1734:1202 | AMD              | FCH SMBus Controller                 | 19    | intsmb     | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 8086:1c22 | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 19    | ichsmb     | [148A268A0F](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4293B43/AD955BCC7F71/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/148A268A0F>) |
| 8086:1e22 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family SMBu... | 19    | ichsmb     | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 1002:4385 | 1022:1510 | AMD              | SBx00 SMBus Controller               | 18    | intsmb     | [177DC1FBC8](<Desktop/PC Engines/apu/apu1/BE5B5D847307/OPNSENSE-22.1.2/13.0-STABLE/AMD64/177DC1FBC8>) |
| 1002:4385 | 1043:8389 | AMD              | SBx00 SMBus Controller               | 18    | intsmb     | [F1FE3FE225](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/9CF14B98B99F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/F1FE3FE225>) |
| 8086:19df | 8086:7270 | Intel            | Atom Processor C3000 Series SMBus... | 18    | ichsmb     | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:5ad4 | 1849:5ad4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [3E1591E714](<Desktop/ASRock/J3455/J3455B-ITX/D479CDF18817/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E1591E714>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 123   | hdac       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 88    | hdac       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 66    | hdac       | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 61    | hdac       | [5D39002367](<Mini Pc/AMI/Aptio/Aptio CRB/F4919BE5C566/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5D39002367>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 51    | hdac       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 50    | hdac       | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:9ca0 | 8086:7270 | Intel            | Wildcat Point-LP High Definition ... | 50    | hdac       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:0a0c | 8086:0a0c | Intel            | Haswell-ULT HD Audio Controller      | 45    | hdac       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:160c | 8086:160c | Intel            | Broadwell-U Audio Controller         | 45    | hdac       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 42    | hdac       | [0051C86E4C](<Desktop/CNCTION-IAF-E3845/Others/Others/7FBC058A3FA5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0051C86E4C>) |
| 8086:8c20 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset High... | 33    | hdac       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 1002:9840 | 103c:213d | AMD              | Kabini HDMI/DP Audio                 | 32    | hdac       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:0c0c | 8086:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 30    | hdac       | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 1022:780d | 103c:213d | AMD              | FCH Azalia Controller                | 29    | hdac       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:5a98 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | hdac       | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 28    | hdac       | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 8086:0c0c | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 28    | hdac       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 28    | hdac       | [CECAC43923](<Desktop/Gigabyte Technology/P85/P85-D3/6D87717FDD41/OPNSENSE-22.1.2/13.0-STABLE/AMD64/CECAC43923>) |
| 1002:1308 | 103c:8103 | AMD              | Kaveri HDMI/DP Audio Controller      | 24    | hdac       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 24    | hdac       | [A5FD383C40](<Desktop/Gigabyte Technology/B550I/B550I AORUS PRO AX/7FCEC9A2C51B/FREEBSD-13.1-PRERELEASE/13.1-PRERELEASE/AMD64/A5FD383C40>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 23    | hdac       | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 8086:0c0c | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 23    | hdac       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 23    | hdac       | [D1EB8226EB](<Notebook/SIEMENS/SIMATIC/SIMATIC IPC127E/F8EC425F9C5B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D1EB8226EB>) |
| 8086:9dc8 | 8086:7270 | Intel            | Cannon Point-LP High Definition A... | 22    | hdac       | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 1022:780d | 103c:8103 | AMD              | FCH Azalia Controller                | 20    | hdac       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1002:9840 | 1734:1202 | AMD              | Kabini HDMI/DP Audio                 | 19    | hdac       | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 8086:0c0c | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 19    | hdac       | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:1c20 | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 19    | hdac       | [148A268A0F](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4293B43/AD955BCC7F71/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/148A268A0F>) |
| 8086:3b56 | 17aa:215e | Intel            | 5 Series/3400 Series Chipset High... | 19    | hdac       | [BCD5BEA2B7](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BCD5BEA2B7>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 18    | hdac       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 1002:aaf0 | 1da2:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 17    | hdac       | [1E6FF84E5D](<Desktop/ASUSTek Computer/CROSSHAIR/CROSSHAIR VI HERO/35055183F5DC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/1E6FF84E5D>) |
| 8086:293e | 17aa:20f2 | Intel            | 82801I (ICH9 Family) HD Audio Con... | 17    | hdac       | [B0A9802877](<Notebook/Lenovo/ThinkPad/ThinkPad SL510 2847R96/16806C85881A/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B0A9802877>) |
| 8086:8c20 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset High... | 17    | hdac       | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:1e20 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family High... | 16    | hdac       | [A488C9AF25](<Desktop/Dell/OptiPlex/OptiPlex 7010/78AA11104573/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A488C9AF25>) |
| 8086:3198 | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 16    | hdac       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:9d70 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 16    | hdac       | [78B36D5068](<Desktop/Others/Others/Others/28E9610435C5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/78B36D5068>) |
| 1022:780d | 1022:780d | AMD              | FCH Azalia Controller                | 14    | hdac       | [E5A9FF1138](<Desktop/AMD/X/X64/8B1209E2156C/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/E5A9FF1138>) |
| 8086:1e20 | 17aa:21fa | Intel            | 7 Series/C216 Chipset Family High... | 14    | hdac       | [06C6A282CA](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23254G7/FF7D8D42B37A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/06C6A282CA>) |
| 8086:1e20 | 8086:1e20 | Intel            | 7 Series/C216 Chipset Family High... | 14    | hdac       | [9A060DF0A2](<Desktop/RUNING/B75M/B75M INTEL H3V/699073C65965/OPNSENSE-22.1/13.0-STABLE/AMD64/9A060DF0A2>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 14    | hdac       | [64CCF1E6A0](<Notebook/Apple/MacBookPro10/MacBookPro10,1/60ED6011F0FC/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/64CCF1E6A0>) |
| 8086:2284 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 14    | hdac       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:8c20 | 1043:8576 | Intel            | 8 Series/C220 Series Chipset High... | 14    | hdac       | [26565F3D84](<Desktop/ASUSTek Computer/All/All Series/0F0FB0273B8E/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/26565F3D84>) |
| 1002:15de | 1043:876b | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 13    | hdac       | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 1022:1487 | 1043:8797 | AMD              | Starship/Matisse HD Audio Controller | 13    | hdac       | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 8086:0c0c | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 13    | hdac       | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:1e20 | 103c:3397 | Intel            | 7 Series/C216 Chipset Family High... | 13    | hdac       | [841ED56816](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/F909A025638A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/841ED56816>) |
| 8086:8c20 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset High... | 13    | hdac       | [4D90BE9B25](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/E0896C7E47C7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/4D90BE9B25>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | hdac       | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 1022:1457 | 1022:c950 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 12    | hdac       | [4D8F19BA12](<Notebook/Deciso/Netboard/Netboard A20/94D2C7F0ED24/OPNSENSE-22.1/13.0-STABLE/AMD64/4D8F19BA12>) |
| 8086:02c8 | 8086:7270 | Intel            | Comet Lake PCH-LP cAVS               | 12    | hdac       | [A556350922](<Desktop/Others/Others/Others/01401D10170F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/A556350922>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8231 | 1028:0493 | O2 Micro         | O2Micro Integrated MS/MSPRO contr... | 4     |            | [2E8B431CC6](<Notebook/Dell/Latitude/Latitude E6420/6637B5C9AD24/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/2E8B431CC6>) |
| 1217:8331 | 1028:049b | O2 Micro         | O2 Flash Memory Card                 | 3     |            | [1ED3FF35F6](<Notebook/Dell/Latitude/Latitude E5420/7F50D3A16CDB/HELLOSYSTEM-0.5.0/13.0-RELEASE/AMD64/1ED3FF35F6>) |
| 1217:7130 | 1179:ff50 | O2 Micro         | Integrated MS/xD Controller          | 2     |            | [13E4AA7026](<Notebook/Toshiba/Satellite/Satellite P300/AFEE934437AF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/13E4AA7026>) |
| 1217:8330 | 1028:04a3 | O2 Micro         | OZ600 MS/xD Controller               | 2     |            | [2F848FD2C0](<Notebook/Dell/Precision/Precision M4600/B6B9C54EEBB2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/2F848FD2C0>) |
| 1283:8211 | 1283:8211 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 2     | atapci     | [BA1D9A51C2](<Desktop/Intel/Bearlake/Bearlake Bearlake Fab A/57F476905C38/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/BA1D9A51C2>) |
| 104c:803b | 1025:011f | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [5D6A8A51D0](<Notebook/Acer/Extensa/Extensa 5220/D9CE76F90EBD/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/5D6A8A51D0>) |
| 104c:803b | 103c:30aa | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [256E0AE719](<Notebook/Hewlett-Packard/Compaq/Compaq nc6320/BA8F7F88D1FF/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/256E0AE719>) |
| 104c:803b | 104d:81e6 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [ACE534D784](<Notebook/Sony/VGN-SZ3/VGN-SZ3VWP_X/ECFA4AD781DF/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/ACE534D784>) |
| 104c:803b | 104d:9016 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [B417DF513F](<Notebook/Sony/VGN-AR630/VGN-AR630E/0309566B32D1/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/B417DF513F>) |
| 104c:803b | 1179:ff00 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [E6E0A1294C](<Notebook/Toshiba/Satellite/Satellite M100/9A0C6DBE0166/FREEBSD-12.2-STABLE/12.2-STABLE/I386/E6E0A1294C>) |
| 104c:ac8f | 104d:8190 | Texas Instrum... | PCI7420/7620 SD/MS-Pro Controller    | 1     |            | [F2F3923EA6](<Notebook/Sony/VGN-S/VGN-S150/194677ED6A48/FREEBSD-13.0-CURRENT/13.0-CURRENT/I386/F2F3923EA6>) |
| 105a:4d30 | 105a:4d33 | Promise Techn... | PDC20267 (FastTrak100/Ultra100)      | 1     | atapci     | [D99AE1AAD1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX PLUS/627BCCBE6A6E/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/D99AE1AAD1>) |
| 105a:4d69 | 105a:4d68 | Promise Techn... | 20269                                | 1     | atapci     | [D2A09126C0](<Desktop/TYAN Computer/Intel/Intel 440BX-GX Rev. 4/05C7EC931544/FREEBSD-12.2-P2/12.2-RELEASE-P1/I386/D2A09126C0>) |
| 1217:7130 | 1028:0273 | O2 Micro         | Integrated MS/xD Controller          | 1     |            | [EF1C0E0F2E](<Notebook/Dell/Vostro/Vostro 1510/810B328E2D37/FREEBSD-12.2/12.2-RELEASE/AMD64/EF1C0E0F2E>) |
| 1217:7130 | 10cf:13c6 | O2 Micro         | Integrated MS/xD Controller          | 1     |            | [AC880C0076](<Notebook/Fujitsu/FMVNF70/FMVNF70YJ/2CAC733E41C3/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/AC880C0076>) |
| 1217:7130 | 1462:3ff3 | O2 Micro         | Integrated MS/xD Controller          | 1     |            | [7DB1345E97](<Notebook/LG Electronics/E500/E500-GP01A9/E9442CB525C8/FREEBSD-13.0-P2/13.0-RELEASE-P1/AMD64/7DB1345E97>) |
| 1217:8130 | 1028:02eb | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 1     |            | [B0A51AC0AF](<Notebook/Dell/Studio/Studio 1747/121152236620/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/B0A51AC0AF>) |
| 1217:8130 | 10cf:1568 | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 1     |            | [51B5325C85](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK NH570/6DEB38A1F3EF/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/51B5325C85>) |
| 1217:8330 | 1028:04a4 | O2 Micro         | OZ600 MS/xD Controller               | 1     |            | [B6C974B8BD](<Notebook/Dell/Precision/Precision M6600/4B49B0BB08DA/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/B6C974B8BD>) |
| 1217:8331 | 1028:049a | O2 Micro         | O2 Flash Memory Card                 | 1     |            | [E0DD26220F](<Notebook/Dell/Latitude/Latitude E5520/15949FA8A5BD/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/E0DD26220F>) |
| 19a2:0712 | 103c:3376 | Emulex           | OneConnect 10Gb iSCSI Initiator (... | 1     |            | [74A4364A7F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/2AF460D1EA85/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/74A4364A7F>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 173   | ahci       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 132   | ahci       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 1022:7801 | 1022:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 126   | ahci       | [E56B256787](<Desktop/PC Engines/APU/APU2/FD5944A53320/PFSENSE-12.3-STABLE/12.3-STABLE/AMD64/E56B256787>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 125   | ahci       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 113   | ahci       | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 89    | ahci       | [BE162C6555](<Desktop/Protectli/VP/VP2410/3631A0AAC7E1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BE162C6555>) |
| 1022:43c8 | 1b21:1062 | AMD              | 400 Series Chipset SATA Controller   | 81    | ahci       | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 62    | ahci       | [D1EB8226EB](<Notebook/SIEMENS/SIMATIC/SIMATIC IPC127E/F8EC425F9C5B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D1EB8226EB>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 53    | ahci       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 50    | ahci       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 1022:7901 | 1849:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 41    | ahci       | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 1b21:0612 | 1849:0612 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 40    | ahci       | [7AAC0F4B94](<Desktop/ASRock/B75M/B75M R2.0/EA264E2F9554/OPNSENSE-22.1.2/13.0-STABLE/AMD64/7AAC0F4B94>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 35    | ahci       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 33    | ahci       | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 1022:7801 | 103c:213d | AMD              | FCH SATA Controller [AHCI mode]      | 32    | ahci       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 1022:7901 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 32    | ahci       | [1DAAB68F1F](<Desktop/Gigabyte Technology/AB350M-Gaming/AB350M-Gaming 3/B7ED32E7D2CE/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/1DAAB68F1F>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 32    | ahci       | [382A3E1FBB](<Desktop/Gigabyte Technology/N3150/N3150ND3V/87684C325536/OPNSENSE-22.1.2/13.0-STABLE/AMD64/382A3E1FBB>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 30    | ahci       | [A2EF313477](<Desktop/Protectli/FW/FW2/3CD419539C29/OPNSENSE-22.1.1/13.0-STABLE/AMD64/A2EF313477>) |
| 8086:1c02 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 29    | ahci       | [DA98B2AD6B](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/DA98B2AD6B>) |
| 8086:8c02 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 28    | ahci       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 27    | ahci       | [177DC1FBC8](<Desktop/PC Engines/apu/apu1/BE5B5D847307/OPNSENSE-22.1.2/13.0-STABLE/AMD64/177DC1FBC8>) |
| 8086:1f22 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA2 C... | 27    | ahci       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:a102 | 1043:8694 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 27    | ahci       | [DB5D59EB88](<Desktop/ASUSTek Computer/H110/H110M-D/83B5EB75C02F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB5D59EB88>) |
| 1022:43eb | 1b21:1062 | AMD              | 500 Series Chipset SATA Controller   | 25    | ahci       | [B23AB09F52](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/B23AB09F52>) |
| 1022:7801 | 103c:8103 | AMD              | FCH SATA Controller [AHCI mode]      | 23    | ahci       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:7901 | 1043:8747 | AMD              | FCH SATA Controller [AHCI mode]      | 23    | ahci       | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 8086:9dd3 | 8086:7270 | Intel            | Cannon Point-LP SATA Controller [... | 23    | ahci       | [A54EE6F019](<Desktop/Others/Others/Others/4C68E3D2FBB0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/A54EE6F019>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 22    | ahci       | [8B51036856](<All In One/Apple/iMac9/iMac9,1/0F8F2AF88707/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8B51036856>) |
| 8086:19c2 | 15d9:0969 | Intel            | Atom Processor C3000 Series SATA ... | 21    | ahci       | [67A2A6BA3E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/599C056DD2BE/OPNSENSE-22.1/13.0-STABLE/AMD64/67A2A6BA3E>) |
| 8086:8c02 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | ahci       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:1e02 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 20    | ahci       | [73562AA169](<Desktop/ASUSTek Computer/BM6835/BM6835_BM6635_BP6335/A8FD64CE8B19/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73562AA169>) |
| 8086:8c02 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ahci       | [77C308E93E](<Desktop/Dell/OptiPlex/OptiPlex 3020/CAE61970AA22/OPNSENSE-22.1.2/13.0-STABLE/AMD64/77C308E93E>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 20    | ahci       | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 1022:43b8 | 1b21:1062 | AMD              | FCH SATA Controller D                | 19    | ahci       | [96015C2D83](<Desktop/MSI/MS-7/MS-7C52/08517B2B3FEB/OPNSENSE-22.1/13.0-STABLE/AMD64/96015C2D83>) |
| 1b21:0612 | 1043:84b7 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 19    | ahci       | [A0885F4F44](<Desktop/ASUSTek Computer/P8Z68-M/P8Z68-M PRO/38C7CD36884E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A0885F4F44>) |
| 8086:1c02 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 19    | ahci       | [042C1EFAC3](<Desktop/Supermicro/X9/X9SCL-X9SCM/7A7B84FA155C/OPNSENSE-22.7/13.0-STABLE/AMD64/042C1EFAC3>) |
| 8086:1e02 | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 19    | ahci       | [D28BEF2C37](<Desktop/Dell/OptiPlex/OptiPlex 7010/5FE57A5AC09A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D28BEF2C37>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 19    | ahci       | [5A75DB9142](<Notebook/TUXEDO/InfinityBook13/InfinityBook13V3/0B9DECE35038/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/5A75DB9142>) |
| 1022:7801 | 1734:1202 | AMD              | FCH SATA Controller [AHCI mode]      | 18    | ahci       | [AA18C11016](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AA18C11016>) |
| 1022:7901 | 1849:ffff | AMD              | FCH SATA Controller [AHCI mode]      | 18    | ahci       | [D3596DFF89](<Desktop/ASRock/X570/X570 PG Velocita/A90551D8040B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D3596DFF89>) |
| 8086:19b2 | 15d9:0969 | Intel            | Atom Processor C3000 Series SATA ... | 18    | ahci       | [67A2A6BA3E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102A-F Server/599C056DD2BE/OPNSENSE-22.1/13.0-STABLE/AMD64/67A2A6BA3E>) |
| 8086:1c02 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 18    | ahci       | [DF08E2E8F0](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/0C4455E7F2C2/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF08E2E8F0>) |
| 8086:1c03 | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 18    | ahci       | [148A268A0F](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4293B43/AD955BCC7F71/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/148A268A0F>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 18    | ahci       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:3b2f | 17aa:2168 | Intel            | 5 Series/3400 Series Chipset 6 po... | 18    | ahci       | [BCD5BEA2B7](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537BN8/4A58F0F69086/OPNSENSE-22.1.2/13.0-STABLE/AMD64/BCD5BEA2B7>) |
| 8086:5ae3 | 1849:5ae3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | ahci       | [3E1591E714](<Desktop/ASRock/J3455/J3455B-ITX/D479CDF18817/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E1591E714>) |
| 8086:a352 | 1043:8694 | Intel            | Cannon Lake PCH SATA AHCI Controller | 18    | ahci       | [3A72227408](<Desktop/ASUSTek Computer/PRIME/PRIME Z390-P/C399FF4CDA48/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A72227408>) |
| 1022:43b7 | 1b21:1062 | AMD              | 300 Series Chipset SATA Controller   | 17    | ahci       | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:1e02 | 1458:b005 | Intel            | 7 Series/C210 Series Chipset Fami... | 17    | ahci       | [459BB6486D](<Desktop/Gigabyte Technology/Z77/Z77N-WIFI/798389D95EE6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/459BB6486D>) |
| 8086:a282 | 1043:8694 | Intel            | 200 Series PCH SATA controller [A... | 17    | ahci       | [AE4F0642FD](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-P/1E747FA168DD/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/AE4F0642FD>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7800 | 1022:7800 | AMD              | FCH SATA Controller [IDE mode]       | 56    | ahci       | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:2850 | 8086:2850 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 33    | atapci     | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 29    | atapci     | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 1022:780c | 103c:8103 | AMD              | FCH IDE Controller                   | 24    | atapci     | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:2828 | 8086:2828 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 21    | atapci     | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:27c0 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 19    | atapci     | [E41BA68AA2](<Desktop/CheckPoint/T-140/T-140-00/55A5BF807E33/OPNSENSE-22.1/13.0-STABLE/AMD64/E41BA68AA2>) |
| 1002:439c | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 18    | atapci     | [F1FE3FE225](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/9CF14B98B99F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/F1FE3FE225>) |
| 8086:3a20 | 103c:330d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 17    | atapci     | [FC82E541DC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC82E541DC>) |
| 1002:439c | 1458:5002 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 14    | atapci     | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 8086:27df | 1043:8179 | Intel            | 82801G (ICH7 Family) IDE Controller  | 12    | atapci     | [99AB8E7989](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX V2/F48FF9950A35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/99AB8E7989>) |
| 1002:4390 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 10    | ahci       | [F1FE3FE225](<Desktop/ASUSTek Computer/M5/M5A78L-USB3/9CF14B98B99F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/F1FE3FE225>) |
| 8086:1c00 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | atapci     | [CB96E68E6E](<Desktop/Dell/OptiPlex/OptiPlex 390/172FACB3F264/OPNSENSE-22.1.1/13.0-STABLE/AMD64/CB96E68E6E>) |
| 8086:1c08 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | atapci     | [CB96E68E6E](<Desktop/Dell/OptiPlex/OptiPlex 390/172FACB3F264/OPNSENSE-22.1.1/13.0-STABLE/AMD64/CB96E68E6E>) |
| 8086:27c0 | 1043:8179 | Intel            | NM10/ICH7 Family SATA Controller ... | 10    | atapci     | [99AB8E7989](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX V2/F48FF9950A35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/99AB8E7989>) |
| 1002:439c | 1849:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 9     | atapci     | [BBB1E3EA53](<Desktop/ASRock/C70/C70M1/590935D8F1B7/OPNSENSE-22.1/13.0-STABLE/AMD64/BBB1E3EA53>) |
| 8086:27c0 | 1458:b002 | Intel            | NM10/ICH7 Family SATA Controller ... | 9     | atapci     | [5A22BB6991](<Desktop/Gigabyte Technology/G31/G31M-ES2C/9E562482276E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5A22BB6991>) |
| 8086:2850 | 17aa:20a6 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 9     | atapci     | [F5F25EFDCC](<Notebook/Lenovo/ThinkPad/ThinkPad T61 766301U/A1D00057611B/HELLOSYSTEM-0.7.0/13.0-RELEASE-P7/AMD64/F5F25EFDCC>) |
| 8086:2921 | 1028:0236 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 9     | atapci     | [924A792460](<Server/Dell/PowerEdge/PowerEdge R610/34F0B81A9C93/OPNSENSE-22.1/13.0-STABLE/AMD64/924A792460>) |
| 8086:3a20 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 9     | atapci     | [5999E0EBFB](<Desktop/ASUSTek Computer/P5P43TD/P5P43TD PRO/CAA935C7EB09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5999E0EBFB>) |
| 8086:3a26 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 9     | atapci     | [5999E0EBFB](<Desktop/ASUSTek Computer/P5P43TD/P5P43TD PRO/CAA935C7EB09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5999E0EBFB>) |
| 8086:2921 | 1028:0235 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 8     | atapci     | [5C1EA00DF3](<Server/Dell/PowerEdge/PowerEdge R710/B03FF48F1575/OPNSENSE-22.1/13.0-STABLE/AMD64/5C1EA00DF3>) |
| 8086:29b6 | 1028:0211 | Intel            | 82Q35 Express PT IDER Controller     | 8     | atapci     | [0F75361707](<Desktop/Dell/OptiPlex/OptiPlex 755/EA117E39981F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F75361707>) |
| 1002:4390 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 7     | ahci       | [6D4AC7F6F5](<Desktop/Gigabyte Technology/GA-78LMT-USB3/GA-78LMT-USB3 6.0/BBDCED21D8D8/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/6D4AC7F6F5>) |
| 1106:0415 | 1043:838f | VIA Technologies | VT6415 PATA IDE Host Controller      | 7     | atapci     | [D789A35C01](<Desktop/ASUSTek Computer/P8H67-M/P8H67-M PRO/0477E4056673/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/D789A35C01>) |
| 8086:1c00 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 7     | atapci     | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:1c08 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 7     | atapci     | [62474001E3](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 PLUS R2.0/E2DC98A0692A/OPNSENSE-22.1.2/13.0-STABLE/AMD64/62474001E3>) |
| 8086:27c0 | 1849:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 7     | atapci     | [A9A1B1A493](<Desktop/ASRock/G41/G41C-VS/9E84A9D36F15/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/A9A1B1A493>) |
| 8086:27df | 1849:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 7     | atapci     | [A9A1B1A493](<Desktop/ASRock/G41/G41C-VS/9E84A9D36F15/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/A9A1B1A493>) |
| 8086:3a20 | 1014:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 7     | atapci     | [F723CAE263](<Server/IBM/System/System x3550 M3 -[7944ZJN]-/B6E6FA55AFB2/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/F723CAE263>) |
| 8086:3a26 | 1014:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 7     | atapci     | [F723CAE263](<Server/IBM/System/System x3550 M3 -[7944ZJN]-/B6E6FA55AFB2/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/F723CAE263>) |
| 8086:3a26 | 103c:330d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 7     | atapci     | [4E059E9162](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/4E059E9162>) |
| 197b:2363 | 1458:b000 | JMicron Techn... | JMB363 SATA/IDE Controller           | 6     | atapci     | [62B94DD372](<Desktop/Gigabyte Technology/X58/X58A-UD5/5F8FCBCE26E8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/62B94DD372>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | atapci     | [6C32638BAF](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/244EA5C23B4B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6C32638BAF>) |
| 8086:1d3c | 103c:1589 | Intel            | C600/X79 series chipset IDE-r Con... | 6     | atapci     | [280CB294A5](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/F566B7B6B4CA/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/280CB294A5>) |
| 8086:269e | 103c:31fe | Intel            | 631xESB/632xESB IDE Controller       | 6     | atapci     | [8EAEA61913](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/2C2E7B0575F2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8EAEA61913>) |
| 8086:27c0 | 1028:0400 | Intel            | NM10/ICH7 Family SATA Controller ... | 6     | atapci     | [17A2E12924](<Desktop/Dell/OptiPlex/OptiPlex 380/23BEB469DB7D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/17A2E12924>) |
| 8086:27df | 1028:0400 | Intel            | 82801G (ICH7 Family) IDE Controller  | 6     | atapci     | [17A2E12924](<Desktop/Dell/OptiPlex/OptiPlex 380/23BEB469DB7D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/17A2E12924>) |
| 8086:27df | 17aa:200c | Intel            | 82801G (ICH7 Family) IDE Controller  | 6     | atapci     | [E2D5391A1A](<Notebook/Lenovo/ThinkPad/ThinkPad T60 1951FEG/8CFF73D19B7A/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E2D5391A1A>) |
| 8086:2850 | 106b:00a1 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 6     | atapci     | [E0CF5200DE](<Notebook/Apple/MacBook4/MacBook4,1/07CFC301CF14/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E0CF5200DE>) |
| 1022:7800 | 1458:b002 | AMD              | FCH SATA Controller [IDE mode]       | 5     | ahci       | [24E23F5911](<Desktop/Gigabyte Technology/E2500/E2500N/7EB41E3CFB91/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/24E23F5911>) |
| 11ab:6121 | 1043:8212 | Marvell Techn... | 88SE6111/6121 SATA II / PATA Cont... | 5     | atapci     | [AE82655A6F](<Desktop/ASUSTek Computer/P5/P5Q-E/AC089698D105/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/AE82655A6F>) |
| 197b:2363 | 1043:824f | JMicron Techn... | JMB363 SATA/IDE Controller           | 5     | atapci     | [73373C3C65](<Desktop/ASUSTek Computer/P7/P7P55D/FE7AE6E364ED/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/73373C3C65>) |
| 8086:1c00 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | atapci     | [9A24935DAB](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/5388A29693D7/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9A24935DAB>) |
| 8086:1c00 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | atapci     | [6C32638BAF](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/244EA5C23B4B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/6C32638BAF>) |
| 8086:1c08 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | atapci     | [9A24935DAB](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/5388A29693D7/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9A24935DAB>) |
| 8086:1d00 | 103c:18a9 | Intel            | C600/X79 series chipset 4-Port SA... | 5     | atapci     | [7987F643D7](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350p Gen8/40D6689C165E/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/7987F643D7>) |
| 8086:27c0 | 1b0a:0005 | Intel            | NM10/ICH7 Family SATA Controller ... | 5     | atapci     | [A58B9A4F8F](<Desktop/Pegatron/IPM41/IPM41-D3/38C292CE2082/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A58B9A4F8F>) |
| 1002:439c | 103c:1609 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 4     | atapci     | [B62251041B](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.2-P11/12.3-RELEASE/AMD64/B62251041B>) |
| 1022:780c | 1458:5002 | AMD              | FCH IDE Controller                   | 4     | atapci     | [18A74377AC](<Desktop/Gigabyte Technology/F2/F2A75M-HD2/DA29D87FC076/FREEBSD-13.0/13.0-RELEASE/AMD64/18A74377AC>) |
| 10de:03ec | 1849:03ec | Nvidia           | MCP61 IDE                            | 4     | atapci     | [5D447C8FCF](<Desktop/ASRock/N68-VS3/N68-VS3 FX/299EFDF3CF4A/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/5D447C8FCF>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 179   | nvme       | [2EA4F88D47](<Desktop/ASRock/H270/H270M-ITX-ac/94B464548D86/OPNSENSE-22.1.3/13.0-STABLE/AMD64/2EA4F88D47>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 60    | nvme       | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 15b7:5006 | 15b7:5006 | Sandisk          | WD Black SN750 / PC SN730 NVMe SSD   | 35    | nvme       | [0D2956A144](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/1180D50A4B77/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/0D2956A144>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 35    | nvme       | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 34    | nvme       | [79D8E655A3](<Desktop/ASRock/B550M/B550M Steel Legend/6852CF1058EA/OPNSENSE-22.1.2/13.0-STABLE/AMD64/79D8E655A3>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 30    | nvme       | [B23AB09F52](<Desktop/ASUSTek Computer/PRIME/PRIME B550M-A/57FCF8719ACE/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/B23AB09F52>) |
| 15b7:5009 | 15b7:5009 | Sandisk          | WD Blue SN550 NVMe SSD               | 29    | nvme       | [65454BCC92](<Notebook/HUAWEI/BOD-WXX/BOD-WXX9/8D0DA727E166/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/65454BCC92>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 24    | nvme       | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 19    | nvme       | [D3596DFF89](<Desktop/ASRock/X570/X570 PG Velocita/A90551D8040B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D3596DFF89>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 19    | nvme       | [BAC8D0BDB7](<Desktop/MSI/MS-7/MS-7A38/B30B426C8BF6/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/BAC8D0BDB7>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 17    | nvme       | [498BFE852C](<Notebook/Dell/Precision/Precision 7530/5BEE2A4C3CA7/FREEBSD-12.3/12.3-RELEASE/AMD64/498BFE852C>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 14    | nvme       | [2CC4698CBC](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-I GAMING/E76068026A5B/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/2CC4698CBC>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 13    | nvme       | [E7B4F8151A](<Server/Supermicro/Super/Super Server/A22FC2D5FFA0/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E7B4F8151A>) |
| 15b7:5002 | 15b7:5002 | Sandisk          | WD Black 2018/SN750 / PC SN720 NV... | 13    | nvme       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 12    | nvme       | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 11    | nvme       | [E4F7F31828](<Desktop/Supermicro/AS/AS -E301-9D-8CN4/72CEEFE7C3DC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E4F7F31828>) |
| 1c5c:1327 |           | SK Hynix         | BC501 NVMe Solid State Drive         | 11    | nvme       | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | unknown                              | 11    | nvme       | [7716F59380](<Notebook/Timi/RedmiBook/RedmiBook Pro 15/2662C76FDAA0/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/7716F59380>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 11    | nvme       | [8AEE77286E](<Desktop/MSI/MS/MS-7760/658E325602DE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8AEE77286E>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 11    | nvme       | [9E440B5500](<Notebook/Dell/Inspiron/Inspiron 5502/B3B09B220C14/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/9E440B5500>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 10    | nvme       | [1970F517FD](<Notebook/GPD/G1621/G1621-02/9557AA82FE04/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/1970F517FD>) |
| 1c5c:174a | 1c5c:174a | SK Hynix         | Gold P31 SSD                         | 9     | nvme       | [BC5703B5BB](<Desktop/ASUSTek Computer/ASUS/ASUS ExpertCenter D500SA_D500SA/ABC523DBEA27/OPNSENSE-22.1.1/13.0-STABLE/AMD64/BC5703B5BB>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 9     | nvme       | [CDC6F54D97](<Notebook/Hewlett-Packard/ZBook/ZBook Studio G4/DF14E45C3A50/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/CDC6F54D97>) |
| 1179:0113 | 1179:0001 | Toshiba          | BG3 NVMe SSD Controller              | 8     | nvme       | [BE311B6A34](<Notebook/Lenovo/ThinkPad/ThinkPad E580 20KSCTO1WW/FE16B0524669/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/BE311B6A34>) |
| 1c5c:1339 |           | SK Hynix         | BC511                                | 8     | nvme       | [1A13B7BFD1](<Notebook/Lenovo/Legion/Legion 5 15ARH05 82B5/F36FD56B8299/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/1A13B7BFD1>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 8     | nvme       | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 1179:0116 | 1179:0001 | Toshiba          | unknown                              | 7     | nvme       | [C729F82F4C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M720s 10SUS4WT00/F6ADF227305E/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C729F82F4C>) |
| 1344:5410 | 1344:0100 | Micron Techno... |                                      | 7     | nvme       | [18576EF86C](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-8CN8TP/199DE71C8C4A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/18576EF86C>) |
| 15b7:5003 | 15b7:5003 | Sandisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 7     | nvme       | [2D72B6939D](<Notebook/ASUSTek Computer/TUF/TUF Gaming FX505DU_FX505DU/FE9E4108BBBD/NOMADBSD-5806F915/13.0-RELEASE/AMD64/2D72B6939D>) |
| 15b7:5011 | 15b7:5011 | Sandisk          | WD PC SN810 / Black SN850 NVMe SSD   | 7     | nvme       | [1F58E0594F](<Notebook/Framework/Laptop/Laptop/12E6C3C95AB5/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1F58E0594F>) |
| 1344:5405 | 1344:0100 | Micron Techno... |                                      | 6     | nvme       | [1AA5CED5A0](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-A/98A2A0675D76/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1AA5CED5A0>) |
| 10ec:5763 | 10ec:5763 | Realtek Semic... |                                      | 5     | nvme       | [D2D10A1FFC](<Desktop/Gigabyte Technology/B365M/B365M DS3H/7A3F482A1C2E/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D2D10A1FFC>) |
| 1179:0115 | 1179:0001 | Toshiba          | XG4 NVMe SSD Controller              | 5     | nvme       | [53ABDFA3B1](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/28EF496B2A02/OPNSENSE-22.1/13.0-STABLE/AMD64/53ABDFA3B1>) |
| 1179:011a | 1179:0001 | Toshiba          | XG6 NVMe SSD Controller              | 5     | nvme       | [E54D79065E](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Extreme Gen 3 20TLA055CD/8C11449058DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/E54D79065E>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 5     | nvme       | [A2DF68E1D1](<Desktop/ASRock/TRX40/TRX40 Taichi/AC795CCA9B64/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A2DF68E1D1>) |
| 2646:500c | 2646:500c | Kingston Tech... |                                      | 5     | nvme       | [5B9C617DC8](<Notebook/MSI/GF63/GF63 Thin 10SCSR/CF159C44766D/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/5B9C617DC8>) |
| 8086:2522 | 8086:3806 | Intel            | NVMe Optane Memory Series            | 5     | nvme       | [6876D2D37D](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/BB03C210EA63/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6876D2D37D>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 5     | nvme       | [82F02EF145](<Desktop/ASUSTek Computer/Maximus/Maximus VIII EXTREME/B9563C53E1F5/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/82F02EF145>) |
| 14a4:22f1 | 1b4b:1093 | Lite-On Techn... | M8Pe Series NVMe SSD                 | 4     | nvme       | [C518DED272](<Desktop/ASRock/Z170M/Z170M Extreme4/9326F1E80AA0/FREEBSD-13.0/13.0-RELEASE/AMD64/C518DED272>) |
| 1c5c:1627 | 1c5c:1627 | SK Hynix         | hynix unknown                        | 4     | nvme       | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 1c5c:1639 | 1c5c:1639 | SK Hynix         | hynix unknown                        | 4     | nvme       | [9478973D4C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M70s 11EX000LGE/DFD126BDDFCE/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/9478973D4C>) |
| 1db2:2302 | 1db2:2302 | ATP ELECTRONICS  |                                      | 4     | nvme       | [EB0DC0B18E](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/6A32319ED33E/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/EB0DC0B18E>) |
| 1e95:9100 | 126f:2263 | Solid State S... |                                      | 4     | nvme       | [B55A699934](<Desktop/Dell/Inspiron/Inspiron 3891/E69659E3B5AD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B55A699934>) |
| 8086:0953 | 8086:370d | Intel            | PCIe Data Center SSD                 | 4     | nvme       | [4710D6000D](<Server/Dell/PowerEdge/PowerEdge R730xd/A61A7DA79985/FREEBSD-11.4-P6/11.4-RELEASE-P5/AMD64/4710D6000D>) |
| 10ec:5760 | 5760:10ec | Realtek Semic... |                                      | 3     | nvme       | [9614FD11D7](<Desktop/ASRock/X570/X570 Steel Legend WiFi ax/730F6AC9C266/MIDNIGHTBSD-2.1.0/2.1.0/AMD64/9614FD11D7>) |
| 15b7:5005 | 15b7:5005 | Sandisk          | PC SN520 NVMe SSD                    | 3     | nvme       | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 1bb1:5012 | 1bb1:5012 | Seagate Techn... | FireCuda 510 SSD                     | 3     | nvme       | [07221FC111](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/1BC2519D6516/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/07221FC111>) |
| 1cc1:33f8 | 1cc1:33f8 | ADATA Technology |                                      | 3     | nvme       | [85F5C972A5](<Notebook/Avell High Performance/A60/A60 MUV/0C5CDFF081CF/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/85F5C972A5>) |
| 1d79:2263 | 1d79:2263 |                  |                                      | 3     | nvme       | [3AB33909B0](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3AB33909B0>) |
| 1d97:1160 | 1d97:1160 | Shenzhen Long... |                                      | 3     | nvme       | [2AC306B67F](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2AC306B67F>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 22    | ciss       | [FC82E541DC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC82E541DC>) |
| 1000:0060 | 1028:1f0c | Broadcom / LSI   | MegaRAID SAS 1078                    | 17    | mfi        | [924A792460](<Server/Dell/PowerEdge/PowerEdge R610/34F0B81A9C93/OPNSENSE-22.1/13.0-STABLE/AMD64/924A792460>) |
| 1000:005b | 1028:1f34 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 12    | mfi        | [2897E61A2F](<Server/Dell/PowerEdge/PowerEdge R620/FC053292A103/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/2897E61A2F>) |
| 8086:2822 | 1028:05a4 | Intel            | SATA Controller [RAID mode]          | 12    | ahci       | [7A5D842D33](<Desktop/Dell/OptiPlex/OptiPlex 9020/4AC712A10049/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/7A5D842D33>) |
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 12    | ahci       | [D60B00E2C6](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D60B00E2C6>) |
| 1000:0073 | 1028:1f51 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 9     | mfi        | [B0AF5D8891](<Server/Dell/PowerEdge/PowerEdge R420/54B10CEE65CE/OPNSENSE-22.1/13.0-STABLE/AMD64/B0AF5D8891>) |
| 1000:005f | 1028:1f44 | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 8     | mfi        | [B640C5A644](<Server/Dell/PowerEdge/PowerEdge R440/381193359A29/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/B640C5A644>) |
| 1000:0079 | 1028:1f17 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 8     | mfi        | [22846D44FB](<Server/Dell/PowerEdge/PowerEdge R815/6788CB525396/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/22846D44FB>) |
| 1000:005b | 1028:1f38 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 7     | mfi        | [7CD73D4820](<Server/Others/0H47HH/0H47HH A07/82377467A588/OPNSENSE-22.1.2/13.0-STABLE/AMD64/7CD73D4820>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 7     | ciss       | [7987F643D7](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350p Gen8/40D6689C165E/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/7987F643D7>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 6     | ciss       | [FBD2ABDA35](<Desktop/NETGEAR/ReadyDATA/ReadyDATA 5200/2E63D7AE698C/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBD2ABDA35>) |
| 8086:2822 | 1028:047e | Intel            | SATA Controller [RAID mode]          | 6     | ahci       | [201BA6CBBA](<Desktop/Dell/OptiPlex/OptiPlex 990/920D8E738DC6/PFSENSE-2.5.0/12.2-STABLE/AMD64/201BA6CBBA>) |
| 8086:2822 | 1028:052c | Intel            | SATA Controller [RAID mode]          | 6     | ahci       | [0541A207C7](<Desktop/Dell/OptiPlex/OptiPlex 9010/630D25B19798/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0541A207C7>) |
| 8086:2826 | 103c:1589 | Intel            | C600/X79 series chipset SATA RAID... | 5     | ahci       | [8BD32670C2](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8BD32670C2>) |
| 9005:0286 | 1014:9580 | Adaptec          | AAC-RAID (Rocket)                    | 5     | aac        | [41D40D8752](<Server/IBM/System/System x3650 -[797941Y]-/B6A5CBBF3013/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/41D40D8752>) |
| 1000:005d | 1028:1f49 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 4     | mfi        | [3E35020209](<Server/Dell/PowerEdge/PowerEdge R630/303789A7C533/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/3E35020209>) |
| 1000:005f | 1028:1f4b | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 4     | mfi        | [5ACC629D2E](<Server/Dell/PowerEdge/PowerEdge R630/8C87677C11EE/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/5ACC629D2E>) |
| 8086:2822 | 103c:130a | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [C2B43EFB8F](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/C2B43EFB8F>) |
| 8086:2826 | 103c:158a | Intel            | C600/X79 series chipset SATA RAID... | 4     | ahci       | [A9B66CB0E1](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/A9B66CB0E1>) |
| 1000:0072 | 1734:1177 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [88EE81B089](<Desktop/ASUSTek Computer/P8/P8Z77-V/AC73B1912AC9/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/88EE81B089>) |
| 1000:0079 | 1014:03c7 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 3     | mfi        | [8BBC599CDD](<Server/IBM/System/System x3650 M3 -[7945K3G]-/4E22FDB71865/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/8BBC599CDD>) |
| 103c:3230 | 103c:3235 | Hewlett-Packard  | Smart Array Controller               | 3     | ciss       | [8EAEA61913](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/2C2E7B0575F2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8EAEA61913>) |
| 103c:323a | 103c:3241 | Hewlett-Packard  | Smart Array G6 controllers           | 3     | ciss       | [379FCF9804](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 G6/8034C079A069/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/379FCF9804>) |
| 8086:1c04 | 1028:04dd | Intel            | 6 Series/C200 Series Desktop SATA... | 3     | ahci       | [668C05619B](<Server/Dell/PowerEdge/PowerEdge R210 II/60E43151B048/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/668C05619B>) |
| 8086:2822 | 1028:0620 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [BB86FB3E67](<Desktop/Dell/PowerEdge/PowerEdge T20/C68E45CBB411/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BB86FB3E67>) |
| 8086:2822 | 1028:07c5 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [90A1FD1C58](<Desktop/Dell/PowerEdge/PowerEdge T30/82CE853FF0D7/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/90A1FD1C58>) |
| 8086:2822 | 1028:085b | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [BBCF2BAD96](<Desktop/Dell/OptiPlex/OptiPlex 5060/B3C627211006/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BBCF2BAD96>) |
| 8086:2822 | 1458:b005 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [AE1AA5A6F7](<Desktop/Gigabyte Technology/B360N/B360N WIFI/DC3709C1C54A/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/AE1AA5A6F7>) |
| 8086:282a | 1028:05ca | Intel            | 82801 Mobile SATA Controller [RAI... | 3     | ahci       | [1DBD9A5CEE](<Notebook/Dell/Latitude/Latitude E7240/A314AF9EB83E/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1DBD9A5CEE>) |
| 9005:0285 | 108e:0286 | Adaptec          | AAC-RAID                             | 3     | aac        | [51E87104A0](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/51E87104A0>) |
| 1000:0014 | 1734:1238 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3516            | 2     | mrsas      | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 1000:005d | 1000:9363 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 2     | mfi        | [205D6E0194](<Desktop/Wortmann AG/TERRA_SERVER/TERRA_SERVER/4BE5147F2077/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/205D6E0194>) |
| 1000:005d | 1028:1f42 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 2     | mrsas      | [F529F87CEA](<Server/Dell/PowerEdge/PowerEdge R440/537392E198E2/FREEBSD-12.2-P10/12.2-RELEASE-P7/AMD64/F529F87CEA>) |
| 1000:005d | 1028:1f47 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 2     | mfi        | [D778079C7F](<Server/Dell/PowerEdge/PowerEdge R7515/23F1145279FD/HARDENEDBSD-13.0-STABLE-HBSD/13.0-STABLE-HBSD/AMD64/D778079C7F>) |
| 1000:0073 | 1014:03b1 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 2     | mfi        | [71D412D254](<Server/IBM/System/System x3250 M3 -[4252K3G]-/0EA3D6B9F663/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/71D412D254>) |
| 1000:0079 | 1014:03b2 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 2     | mfi        | [F723CAE263](<Server/IBM/System/System x3550 M3 -[7944ZJN]-/B6E6FA55AFB2/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/F723CAE263>) |
| 1000:00ce | 1137:0197 | Broadcom / LSI   | MegaRAID SAS-3 3316 [Intruder]       | 2     | mrsas      | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 1028:0015 | 1028:1f03 | Dell             | PowerEdge Expandable RAID control... | 2     | mfi        | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 103c:3230 | 103c:3223 | Hewlett-Packard  | Smart Array Controller               | 2     | ciss       | [7DFAEC9B01](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/1062B96A5966/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/7DFAEC9B01>) |
| 103c:3239 | 103c:21c5 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 2     | ciss       | [D35F62BA44](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/F3C30038FE1D/FREEBSD-12.1-P6/12.1-RELEASE-P1/AMD64/D35F62BA44>) |
| 103c:3239 | 103c:21cb | Hewlett-Packard  | Smart Array Gen9 Controllers         | 2     | ciss       | [D35F62BA44](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/F3C30038FE1D/FREEBSD-12.1-P6/12.1-RELEASE-P1/AMD64/D35F62BA44>) |
| 103c:323a | 103c:3243 | Hewlett-Packard  | Smart Array G6 controllers           | 2     | ciss       | [28F84E935F](<Server/Hewlett-Packard/ProLiant/ProLiant DL180 G6/8E2A024CC455/FREEBSD-12.3-P1/12.3-RELEASE-P1/AMD64/28F84E935F>) |
| 103c:323b | 103c:3351 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 2     | ciss       | [D37478E67D](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/107FB7AB1A93/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/D37478E67D>) |
| 105a:5275 | 1462:1290 | Promise Techn... | PDC20276 (MBFastTrak133 Lite)        | 2     | atapci     | [4AB900BDA7](<Desktop/MSI/MS/MS-9129/FE70FB1F858A/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/4AB900BDA7>) |
| 1095:3112 | 1095:3112 | Silicon Image    | SiI 3112 [SATALink/SATARaid] Seri... | 2     | atapci     | [4AB900BDA7](<Desktop/MSI/MS/MS-9129/FE70FB1F858A/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/4AB900BDA7>) |
| 1095:3114 | 1095:3114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 2     | atapci     | [714B6539CF](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/616CA97E53D9/TRUENAS-12.2-RC3/12.2-RC3/AMD64/714B6539CF>) |
| 1095:3114 | 1095:7114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 2     | atapci     | [4C9B877754](<Desktop/Gigabyte Technology/Z77/Z77X-UD3H/1B931DE47D32/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/4C9B877754>) |
| 1106:3249 | 1106:3249 | VIA Technologies | VT6421 IDE/SATA Controller           | 2     | atapci     | [5ABCE24217](<Desktop/ASRock/N68C-GS4/N68C-GS4 FX/E2B5288E6A1C/NOMADBSD-1.4-RC1/12.2-RELEASE-P7/AMD64/5ABCE24217>) |
| 13c1:1004 | 13c1:1004 | 3ware            | 9650SE SATA-II RAID PCIe             | 2     | twa        | [CF2E66B6AA](<Server/Supermicro/X10/X10SLL-F/A57790A3890F/FREEBSD-12.2/12.2-RELEASE/AMD64/CF2E66B6AA>) |
| 8086:02d7 | 1028:09ec | Intel            | Comet Lake PCH-LP SATA RAID Premi... | 2     |            | [465DD01C0D](<Notebook/Dell/Latitude/Latitude 3410/1811D7B7C616/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/465DD01C0D>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1000:3020 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 22    | mps        | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 1000:0072 | 1028:1f1c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 9     | mps        | [5C8DF4DCAD](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/B77E3EF73ADC/TRUENAS-12.2-P12/12.2-RELEASE-P12/AMD64/5C8DF4DCAD>) |
| 8086:1d6b | 103c:1589 | Intel            | C602 chipset 4-Port SATA Storage ... | 7     | isci       | [8BD32670C2](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.2/13.0-STABLE/AMD64/8BD32670C2>) |
| 1000:0072 | 1028:1f1d | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 6     | mps        | [0C40D38F1D](<Server/Dell/PowerEdge/PowerEdge R310/FA9EEF8E1FF1/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/0C40D38F1D>) |
| 1000:0087 | 1000:3020 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 6     | mps        | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 1000:0097 | 1000:30e0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 4     | mpr        | [8E713B55DC](<Desktop/Supermicro/SSG-5028/SSG-5028R-E1CR12L-CE010/BC525F547480/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/8E713B55DC>) |
| 8086:1d6b | 103c:158a | Intel            | C602 chipset 4-Port SATA Storage ... | 4     | isci       | [A9B66CB0E1](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/A9B66CB0E1>) |
| 8086:1d6b | 15d9:0660 | Intel            | C602 chipset 4-Port SATA Storage ... | 4     | isci       | [2475A7B110](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/E2FD8E696E13/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2475A7B110>) |
| 1000:0072 | 1000:3040 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [DC582EA4D3](<Desktop/ASRock/B550M/B550M Pro4/6D75D10E9FEA/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/DC582EA4D3>) |
| 1000:0072 | 1028:1f1e | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [27B11C7A56](<Server/Dell/PowerEdge/PowerEdge R610/15D24070CFC2/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/27B11C7A56>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 3     | mpr        | [6C4D7ACEEC](<Server/Supermicro/Super/Super Server/B1D0F2EE5D00/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/6C4D7ACEEC>) |
| 1000:0016 | 1028:1fcb | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [6039440CE8](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/6039440CE8>) |
| 1000:0016 | 1028:1fcd | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [AA44179A5F](<Server/Dell/PowerEdge/PowerEdge R640/FB4118FD56BA/FREEBSD-12.2-P1/12.2-RELEASE-P1/AMD64/AA44179A5F>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 2     | mps        | [2F589ABF33](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/0AEF40CD9E4E/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/2F589ABF33>) |
| 1000:0070 | 1000:3010 | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 2     | mps        | [E83E6A0CD8](<Server/Supermicro/X8/X8DTU/BFC393DAED02/FREEBSD-13.0-P4/13.0-RELEASE-P3/AMD64/E83E6A0CD8>) |
| 1000:0072 | 1000:0072 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [6A6164AF73](<Desktop/TYAN Computer/S/S5512/A897EED01FA8/TRUENAS-12.2-P2/12.2-RELEASE-P2/AMD64/6A6164AF73>) |
| 1000:0072 | 103c:3371 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [FBD2ABDA35](<Desktop/NETGEAR/ReadyDATA/ReadyDATA 5200/2E63D7AE698C/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBD2ABDA35>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mps        | [EA62F49750](<Desktop/Supermicro/X9/X9DRD-7LN4F/97D90A6AA706/TRUENAS-12.2-P10/12.2-RELEASE-P10/AMD64/EA62F49750>) |
| 1000:0087 | 1028:1f34 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mps        | [FBCC442D47](<Server/Dell/PowerEdge/PowerEdge R720xd/9494C365C719/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBCC442D47>) |
| 1000:0097 | 1028:1f46 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [BA13BBECFD](<Server/Dell/PowerEdge/PowerEdge R730/BC55DA270D03/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/BA13BBECFD>) |
| 1000:0097 | 1028:1f53 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [B062E0F4E4](<Server/Dell/PowerEdge/PowerEdge R740xd/3E6753E4D93A/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/B062E0F4E4>) |
| 1000:0097 | 1849:0097 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [C04BBD635B](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/6457E123E761/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/C04BBD635B>) |
| 103c:3239 | 103c:21c7 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 2     | ciss       | [F91D50AB48](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/10EC3EA2C607/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F91D50AB48>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [0F3EE4CAAB](<Desktop/Fujitsu/CELSIUS/CELSIUS M720/7B5122D4B3E4/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/0F3EE4CAAB>) |
| 8086:1d6b | 17aa:1026 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [1EC71F814B](<Desktop/Lenovo/ThinkStation/ThinkStation S30 43511K5/E8B0027862B5/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1EC71F814B>) |
| 1000:005d | 15d9:0a09 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [B44FE94131](<Desktop/Supermicro/SSG-2028/SSG-2028R-E1CR24N/201BEB766364/FREENAS-11.3-P9/11.3-RELEASE-P9/AMD64/B44FE94131>) |
| 1000:005d | 19e5:da07 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [AC2C7107D3](<Server/Huawei/RH2288H/RH2288H V3/FFCB8F761596/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/AC2C7107D3>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mps        | [CF2E66B6AA](<Server/Supermicro/X10/X10SLL-F/A57790A3890F/FREEBSD-12.2/12.2-RELEASE/AMD64/CF2E66B6AA>) |
| 1000:0072 | 1000:3050 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [28FDD2C2DC](<Desktop/Supermicro/X9/X9SCL-X9SCM/70812EDDCEB0/FREENAS-11.2-STABLE/11.2-STABLE/AMD64/28FDD2C2DC>) |
| 1000:0072 | 1000:3060 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [F88EAF06AC](<Server/Intel/S1200/S1200BTL/BD51E5A20141/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/F88EAF06AC>) |
| 1000:0072 | 1000:30f0 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [90C27497D9](<Desktop/ASUSTek Computer/Crosshair/Crosshair V Formula/08D4551A4F47/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/90C27497D9>) |
| 1000:0072 | 1043:843c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [D50484387C](<Server/ASUSTek Computer/P8B-E/P8B-E Series/9F223A3AC70D/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/D50484387C>) |
| 1000:0086 | 103c:158b | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 1000:0087 | 1000:3030 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [E59D5D41A5](<Server/Hewlett-Packard/ProLiant/ProLiant SE326M1R2/9702C33A6606/FREENAS-11.3-P7/11.3-RELEASE-P7/AMD64/E59D5D41A5>) |
| 1000:0087 | 1028:1f38 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [3EC53E21DF](<Server/Dell/PowerEdge/PowerEdge R420/D7522FBBA9EE/OPNSENSE-22.1/13.0-STABLE/AMD64/3EC53E21DF>) |
| 1000:0090 | 1137:0155 | Broadcom / LSI   | SAS3108 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 1000:0097 | 1028:0619 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [DDDF168DB9](<Desktop/Dell/Precision/Precision Tower 7910/9E71C365962A/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/DDDF168DB9>) |
| 1000:00ac | 1000:3000 | Broadcom / LSI   | SAS3416 Fusion-MPT Tri-Mode I/O C... | 1     | mpr        | [23196AA66B](<Desktop/ASRock/Z390/Z390M-ITX-ac/40E52D5C50CF/FREEBSD-12.2-P5/12.2-RELEASE-P4/AMD64/23196AA66B>) |
| 103c:3239 | 103c:21c8 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 1     | ciss       | [C2BB148E8A](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/37E855C98CE1/FREEBSD-12.2-P2/12.2-RELEASE-P2/AMD64/C2BB148E8A>) |
| 15ad:07c0 | 15ad:07c0 | VMware           | PVSCSI SCSI Controller               | 1     | pvscsi     | [392CF6EC24](<Desktop/Others/Others/Others/375B22211095/FREEBSD-13.0/13.0-RELEASE/ARM64/392CF6EC24>) |
| 8086:1d6a | 8086:3583 | Intel            | C600/X79 series chipset Dual 4-Po... | 1     | isci       | [474B0E44EA](<Server/Wortmann AG/TERRA/TERRA Server/8361012A53E8/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/474B0E44EA>) |
| 8086:1d6b | 103c:158b | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 8086:1d6b | 152d:899b | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [A4980E3EA4](<Server/Quanta/JASPER/JASPER12/E990713EF0FC/FREEBSD-12.2-P6/12.2-RELEASE-P4/AMD64/A4980E3EA4>) |
| 8086:1d6b | 15d9:0628 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [31017CE819](<Desktop/Penguin Computing/Icebreaker/Icebreaker 4824/D0EFCA2F74C7/FREEBSD-12.2/12.2-RELEASE/AMD64/31017CE819>) |
| 8086:1d6b | 15d9:062f | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [A3BCB2FCF1](<Server/Bull SAS/bullx/bullx/4C113D9600C5/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/A3BCB2FCF1>) |
| 8086:1d6b | 15d9:0703 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [1F4D1E4607](<Server/Supermicro/X9/X9DBL-3F-X9DBL-iF/C3731809970F/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/1F4D1E4607>) |
| 8086:1d6f | 1734:11b6 | Intel            | C600/X79 series chipset 4-Port SA... | 1     | isci       | [A9D034FE42](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S8/2FAA16863AF6/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/A9D034FE42>) |
| 9005:028f | 103c:0602 | Adaptec          | Smart Storage PQI SAS                | 1     | smartpqi   | [01594B89A6](<Server/HPE/ProLiant/ProLiant DL380 Gen10/7D92A29D1AAE/OPNSENSE-21.1.9/12.1-RELEASE-P19-HBSD/AMD64/01594B89A6>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1425:5501 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 7     |            | [2AC306B67F](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2AC306B67F>) |
| 1425:4501 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 6     |            | [51EBC2C3FD](<Desktop/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/F7BBE9119163/OPNSENSE-22.1.2/13.0-STABLE/AMD64/51EBC2C3FD>) |
| 1000:0058 | 1028:1f0e | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 5     | mpt        | [B4234170E8](<Desktop/ASUSTek Computer/P5Q/P5Q DELUXE/E1D558665C0F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B4234170E8>) |
| 1000:0058 | 1028:1f0f | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 4     | mpt        | [071AD110AB](<Server/Dell/PowerEdge/PowerEdge R410/69BF745EE7B1/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/071AD110AB>) |
| 17d3:1300 | 17d3:1300 | Areca Technology | ARC-1300ix-16 16-Port PCI-Express... | 4     | arcsas     | [66BBED8D59](<Desktop/ASUSTek Computer/P6T/P6T SE/9C422F2B290E/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/66BBED8D59>) |
| 1000:0058 | 1014:0394 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mpt        | [5F9F2C2232](<Server/IBM/System/System x -[79463ag]-/9FE86345EDC2/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/5F9F2C2232>) |
| 9004:8178 |           | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 3     | ahc        | [B7FC5EF684](<Desktop/Biostar/X470/X470GTA/2553A631F2D9/FREEBSD-13.0/13.0-RELEASE/AMD64/B7FC5EF684>) |
| 1000:0030 | 103c:322a | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 2     | mpt        | [2F26C69137](<Desktop/Dell/OptiPlex/OptiPlex 390/A5CC20B80AD3/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/2F26C69137>) |
| 1000:0054 | 1028:1f09 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mpt        | [E98F23CD45](<Server/Dell/PowerEdge/PowerEdge SC1435/269A637D74C2/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/E98F23CD45>) |
| 1000:0058 | 1028:1f10 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mpt        | [5D650E34E4](<Server/Dell/PowerEdge/PowerEdge R410/E1AADBB39AD2/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/5D650E34E4>) |
| 1425:5503 |           | Chelsio Commu... | T540-CR Unified Wire Storage Cont... | 2     |            | [C04BBD635B](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/6457E123E761/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/C04BBD635B>) |
| 1425:5507 |           | Chelsio Commu... | T520-SO Unified Wire Storage Cont... | 2     |            | [502AF52245](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10/BB7614C3933F/OPNSENSE-22.1/13.0-STABLE/AMD64/502AF52245>) |
| 5853:0001 | 5853:0001 | XenSource        | Xen Platform Device                  | 2     | xenpci     | [FFB1FD95D3](<Desktop/PC Engines/apu/apu4/8CB6C93947A1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/FFB1FD95D3>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 2     | ahc        | [C67CCF8BC6](<Desktop/Dell/Inspiron/Inspiron 530/3762C968ACCD/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C67CCF8BC6>) |
| 1000:0001 | 1000:1000 | Broadcom / LSI   | 53c810                               | 1     | sym        | [4EE625240F](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VII HERO/37724E1F8F3B/FREEBSD-12.1-STABLE/12.1-STABLE-20200612/AMD64/4EE625240F>) |
| 1000:000f | 1000:1000 | Broadcom / LSI   | 53c875                               | 1     | sym        | [DAE16641BB](<Desktop/ASUSTek Computer/M2/M2NPV-MX/14DC624B8825/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/DAE16641BB>) |
| 1000:0030 | 1000:10b0 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 1000:0030 | 1000:50c0 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [7E51DD7048](<Server/Supermicro/Super/Super Server/436CD64AB3E6/FREEBSD-12.3/12.3-RELEASE/AMD64/7E51DD7048>) |
| 1000:0030 | 1734:1041 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [ADB972BF8E](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX200S2/C657395B089D/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/ADB972BF8E>) |
| 1000:0056 | 1000:1000 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [7B2DE50C60](<Desktop/Apple/Xserve3/Xserve3,1/D499BA477C7F/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/7B2DE50C60>) |
| 1000:0056 | 1734:1131 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [FF2213E848](<Desktop/Fujitsu/CELSIUS/CELSIUS M470-2/50E1DC1E3DE9/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/FF2213E848>) |
| 1000:0058 | 103c:130b | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [6DDE87584C](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/E946340732BD/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/6DDE87584C>) |
| 1000:0058 | 103c:3229 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [AE37F4EB2D](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/2E9FE6581089/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/AE37F4EB2D>) |
| 1000:0058 | 15d9:a480 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [27FC294BCA](<Desktop/Supermicro/X7/X7DCL/3D21E845B8F9/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/27FC294BCA>) |
| 1000:0058 | 17aa:101d | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [6F464AAD1F](<Desktop/Lenovo/ThinkStation/ThinkStation D10 6493WEU/6A717F675FF7/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/6F464AAD1F>) |
| 1000:0059 | 15d9:0004 | Broadcom / LSI   | MegaRAID SAS 8208ELP/8208ELP         | 1     | mpt        | [7D0E121099](<Desktop/Supermicro/X8/X8STi/00B85E5857AF/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/7D0E121099>) |
| 1103:2300 | 11ab:11ab | HighPoint Tec... | RocketRAID 230x 4 Port SATA-II Co... | 1     | hptrr      | [AA29EB9C75](<Desktop/Gigabyte Technology/H67/H67A-UD3H-B3/48803C404D01/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/AA29EB9C75>) |
| 1425:4502 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Storage Cont... | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1425:5583 |           | Chelsio Commu... | T540-5083 Unified Wire Storage Co... | 1     |            | [A1CF339702](<Server/Supermicro/Super/Super Server/AEAD0BFD0A36/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/A1CF339702>) |
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
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 100   |            | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 88    |            | [58E098ECA2](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/58E098ECA2>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 88    |            | [58E098ECA2](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/58E098ECA2>) |
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 73    |            | [58E098ECA2](<Desktop/Intel/Thurley/Thurley/38D0B4D8000D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/58E098ECA2>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 65    | amdiommu   | [753AF67FFA](<Desktop/ASUSTek Computer/PRIME/PRIME B350M-A/796624B869DA/FREEBSD-13.0-P8/13.0-RELEASE-P8/AMD64/753AF67FFA>) |
| 8086:6f76 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 60    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f88 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 59    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f8a |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 59    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fae |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 59    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6faf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 59    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 58    | amdiommu   | [5CF613062C](<Desktop/ASRock/B450M/B450M Pro4/5C7E06AB8947/OPNSENSE-22.1.2/13.0-STABLE/AMD64/5CF613062C>) |
| 8086:6fbc |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 58    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fbd |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 58    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fbe |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 58    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fbf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 58    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 103c:3306 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Sl... | 49    |            | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 103c:3307 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Ma... | 49    |            | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 8086:6f1d | 8086:6f1d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f1e | 8086:6f1e | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f1f | 8086:6f1f | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f71 | 8086:6f71 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f98 | 8086:6f98 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f99 | 8086:6f99 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f9a | 8086:6f9a | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f9c | 8086:6f9c | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fa0 | 8086:6fa0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fa8 | 8086:6fa8 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6faa | 8086:6faa | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fab | 8086:6fab | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fc0 | 8086:6fc0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fe0 | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fe1 | 8086:6fe1 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6ff8 | 8086:6ff8 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6ffc | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6ffd | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6ffe | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 48    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:1f15 |           | Intel            | Atom processor C2000 SMBus 2.0       | 47    |            | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1f16 |           | Intel            | Atom processor C2000 RCEC            | 47    |            | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:6fb0 | 8086:6fb0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 47    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fb1 | 8086:6fb1 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 47    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fb2 | 8086:6fb2 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 47    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fb3 | 8086:6fb3 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 47    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fe2 | 8086:6fe2 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 47    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fe3 | 8086:6fe3 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 47    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6f81 | 8086:6f81 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 46    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 8086:6fac | 8086:6fac | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 45    |            | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 8086:6fad | 8086:6fad | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 45    |            | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 8086:6fb4 | 8086:6fb4 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 44    |            | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 8086:6fb5 | 8086:6fb5 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 44    |            | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7808 | 1022:7808 | AMD              | FCH USB EHCI Controller              | 195   | ehci       | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 1022:7814 | 1022:1410 | AMD              | FCH USB XHCI Controller              | 182   | xhci       | [FF8DFBF357](<Desktop/PC Engines/APU/APU2/5BC2136A359B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FF8DFBF357>) |
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 176   | xhci       | [E3F0B82FEA](<Desktop/CNCTION-IAF/Others/Others/968526053CA3/OPNSENSE-22.1.3/13.0-STABLE/AMD64/E3F0B82FEA>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 138   | xhci       | [2C002DC6A8](<Desktop/Others/YL-J3160/YL-J3160L4/E5290014AF68/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C002DC6A8>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 106   | xhci       | [C3D9E88B9D](<Desktop/Others/YL-E3854/YL-E3854L4-V2/AF7B49A18152/OPNSENSE-22.1.2/13.0-STABLE/AMD64/C3D9E88B9D>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 86    | xhci       | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 1022:149c | 1022:148c | AMD              | Matisse USB 3.0 Host Controller      | 72    | xhci       | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:43d5 | 1b21:1142 | AMD              | 400 Series Chipset USB 3.1 XHCI C... | 66    | xhci       | [EBDFD000C6](<Desktop/ASRock/B450M/B450M Steel Legend/40C6F3FD48CC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/EBDFD000C6>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 62    | xhci       | [D1EB8226EB](<Notebook/SIEMENS/SIMATIC/SIMATIC IPC127E/F8EC425F9C5B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D1EB8226EB>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 54    | xhci       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:9cb1 | 8086:7270 | Intel            | Wildcat Point-LP USB xHCI Controller | 53    | xhci       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 8086:9c26 | 8086:7270 | Intel            | 8 Series USB EHCI #1                 | 50    | ehci       | [0BD1EF2B48](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/8D72983BE759/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0BD1EF2B48>) |
| 8086:9ca6 | 8086:7270 | Intel            | Wildcat Point-LP USB EHCI Controller | 50    | ehci       | [FB3FD7EA82](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/0FEFB3FAE4ED/OPNSENSE-22.1.3/13.0-STABLE/AMD64/FB3FD7EA82>) |
| 103c:3300 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 49    | uhci       | [B652261BDA](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/178FFFF9BF4B/OPNSENSE-22.1.2/13.0-STABLE/AMD64/B652261BDA>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 47    | ehci       | [177DC1FBC8](<Desktop/PC Engines/apu/apu1/BE5B5D847307/OPNSENSE-22.1.2/13.0-STABLE/AMD64/177DC1FBC8>) |
| 8086:0f34 | 8086:0f34 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 45    | ehci       | [19ED08C39C](<Mini Pc/AMI/Aptio/Aptio CRB/B514BDB172DC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19ED08C39C>) |
| 1002:4397 | 1002:4397 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 44    | ohci       | [177DC1FBC8](<Desktop/PC Engines/apu/apu1/BE5B5D847307/OPNSENSE-22.1.2/13.0-STABLE/AMD64/177DC1FBC8>) |
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 44    | xhci       | [2D1BF5A79A](<Desktop/BESSTAR Tech/HM/HM90/1F0A034DBC90/OPNSENSE-22.1.1/13.0-STABLE/AMD64/2D1BF5A79A>) |
| 1022:149c | 1022:1486 | AMD              | Matisse USB 3.0 Host Controller      | 43    | xhci       | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 8086:27c8 | 8086:27c8 | Intel            | NM10/ICH7 Family USB UHCI Control... | 40    | uhci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27c9 | 8086:27c9 | Intel            | NM10/ICH7 Family USB UHCI Control... | 39    | uhci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27cc | 8086:27cc | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 38    | ehci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 1002:4399 | 1002:4399 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 37    | ohci       | [5D88E3054B](<Desktop/PC Engines/APU/APU/1E388B64AF47/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5D88E3054B>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 37    | ehci       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:27ca | 8086:27ca | Intel            | NM10/ICH7 Family USB UHCI Control... | 37    | uhci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 1b21:1042 | 1043:8488 | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 35    | xhci       | [1CCF85F60D](<Notebook/ASUSTek Computer/1215/1215B/A9FC3E123192/FREEBSD-13.0/13.0-RELEASE/AMD64/1CCF85F60D>) |
| 8086:27cb | 8086:27cb | Intel            | NM10/ICH7 Family USB UHCI Control... | 35    | uhci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:8c26 | 8086:8c26 | Intel            | 8 Series/C220 Series Chipset Fami... | 35    | ehci       | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 8086:8c2d | 8086:8c2d | Intel            | 8 Series/C220 Series Chipset Fami... | 35    | ehci       | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 8086:8c31 | 8086:8c31 | Intel            | 8 Series/C220 Series Chipset Fami... | 35    | xhci       | [F22A45488B](<Desktop/NEXCOM/NDISB/NDISB533/C13AB8902C2F/OPNSENSE-22.1.2/13.0-STABLE/AMD64/F22A45488B>) |
| 1022:149c | 1043:87c0 | AMD              | Matisse USB 3.0 Host Controller      | 34    | xhci       | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 8086:2830 | 8086:2830 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 34    | uhci       | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:2831 | 8086:2831 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 34    | uhci       | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:2836 | 8086:2836 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 34    | ehci       | [ECBDEAF92B](<Desktop/CheckPoint/T-110/T-110-00/7CA5763D4ADE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/ECBDEAF92B>) |
| 8086:8c31 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 33    | xhci       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 1022:7807 | 103c:213d | AMD              | FCH USB OHCI Controller              | 32    | ohci       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 1022:7808 | 103c:213d | AMD              | FCH USB EHCI Controller              | 32    | ehci       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 1022:7814 | 103c:213d | AMD              | FCH USB XHCI Controller              | 32    | xhci       | [ABD079EC21](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/C3157F2E5428/OPNSENSE-22.1.1/13.0-STABLE/AMD64/ABD079EC21>) |
| 8086:1c26 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 32    | ehci       | [DA98B2AD6B](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/DA98B2AD6B>) |
| 8086:1c2d | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 32    | ehci       | [DA98B2AD6B](<Server/Dell/PowerEdge/PowerEdge R210 II/19696ACD0153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/DA98B2AD6B>) |
| 8086:8c26 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 32    | ehci       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:8c2d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 32    | ehci       | [8DA46F8DD0](<Desktop/Dell/OptiPlex/OptiPlex 9020/F53B14F3D07E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/8DA46F8DD0>) |
| 8086:8c26 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 30    | ehci       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:8c2d | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 29    | ehci       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:8c31 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 29    | xhci       | [E407674ABA](<Desktop/ASUSTek Computer/All/All Series/92636C571F98/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E407674ABA>) |
| 8086:0f35 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 27    | xhci       | [A2EF313477](<Desktop/Protectli/FW/FW2/3CD419539C29/OPNSENSE-22.1.1/13.0-STABLE/AMD64/A2EF313477>) |
| 8086:3a34 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 27    | uhci       | [FC82E541DC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC82E541DC>) |
| 8086:3a35 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 27    | uhci       | [FC82E541DC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC82E541DC>) |
| 8086:3a36 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 27    | uhci       | [FC82E541DC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC82E541DC>) |
| 8086:3a3a | 103c:330d | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 27    | ehci       | [FC82E541DC](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/2B064C7B2306/OPNSENSE-22.1.2/13.0-STABLE/AMD64/FC82E541DC>) |

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

### Wireless controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7360 | 8086:0020 | Intel            | XMM7360 LTE Advanced Modem           | 5     |            | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:7360 | 1028:5820 | Intel            | XMM7360 LTE Advanced Modem           | 1     |            | [1BB6C1F63F](<Notebook/Dell/Latitude/Latitude 5400/418002D1A36C/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/1BB6C1F63F>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 72    |            | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 72    |            | [16E7B1456B](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/16E7B1456B>) |
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 69    |            | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 55    |            | [3B2E18A52E](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/3B2E18A52E>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 27    |            | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 27    |            | [D01A922777](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/D01A922777>) |
| 1022:1455 | 1043:8747 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 19    |            | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 1022:145a | 1043:8747 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 19    |            | [3C28521DE5](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/3C28521DE5>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 14    |            | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 0000:0000 |           |                  |                                      | 13    |            | [BA0AC00CF6](<Desktop/MSI/MS/MS-7885/A9957445CE5D/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/BA0AC00CF6>) |
| 8086:a1ec | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 0    | 11    |            | [68B13705C8](<Server/Supermicro/Super/Super Server/AB927389C02E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/68B13705C8>) |
| 8086:a1ed | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 1    | 11    |            | [68B13705C8](<Server/Supermicro/Super/Super Server/AB927389C02E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/68B13705C8>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 10    |            | [4EF193841E](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.0/13.0-RELEASE/AMD64/4EF193841E>) |
| 1022:1485 | 1043:8808 | AMD              | Starship/Matisse Reserved SPP        | 8     |            | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 1022:148a | 1043:8808 | AMD              | Starship/Matisse PCIe Dummy Function | 8     |            | [8307275B2E](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/C4886ECF4649/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/8307275B2E>) |
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 7     |            | [F91D50AB48](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/10EC3EA2C607/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F91D50AB48>) |
| 8086:9d35 | 17aa:2238 | Intel            | Sunrise Point-LP Integrated Senso... | 7     |            | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [4810CFD776](<Server/Thomas-Krenn.AG/Super/Super Server/4D0E258672FB/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/4810CFD776>) |
| 1022:145a | 1002:15dd | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 5     |            | [78F79FAB6F](<Desktop/Gigabyte Technology/B450M/B450M S2H/1472F852C675/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/78F79FAB6F>) |
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     |            | [0902E5400A](<Desktop/MW/GMLK-2/GMLK-2_5G4L/36C8C01719A8/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0902E5400A>) |
| 1022:1485 | 1462:7c02 | AMD              | Starship/Matisse Reserved SPP        | 4     |            | [14F1956220](<Desktop/MSI/MS-7/MS-7C02/0BF11DCDAD12/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/14F1956220>) |
| 1022:148a | 1462:7c02 | AMD              | Starship/Matisse PCIe Dummy Function | 4     |            | [14F1956220](<Desktop/MSI/MS-7/MS-7C02/0BF11DCDAD12/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/14F1956220>) |
| 1022:15e6 | 1849:15e6 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 4     |            | [78D2871C20](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-22.1.1/13.0-STABLE/AMD64/78D2871C20>) |
| 8086:8d7c | 1028:0601 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [3E35020209](<Server/Dell/PowerEdge/PowerEdge R630/303789A7C533/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/3E35020209>) |
| 8086:8d7c | 1849:8d7c | Intel            | C610/X99 series chipset SPSR         | 4     |            | [149D7ABD05](<Desktop/ASRock/X99/X99 Taichi/159849139E39/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/149D7ABD05>) |
| 8086:a1ec | 1028:07c9 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [E69ED4862D](<Server/Dell/PowerEdge/PowerEdge R440/7E1720943EF3/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E69ED4862D>) |
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [63699D431A](<Desktop/Dell/VEP-4600/VEP-4600-V910/BAE5F41CA0D2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/63699D431A>) |
| 1022:1455 | 1462:7b86 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:145a | 1462:7b86 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 3     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 15ec:5000 | 15ec:5000 | Beckhoff         |                                      | 3     |            | [6DB720018B](<Desktop/Beckhoff Automation/CBxx/CBxx63/D2340951707E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6DB720018B>) |
| 8086:8d7c | 1043:8600 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [DACF7F604C](<Desktop/ASUSTek Computer/All/All Series/67304D8B913B/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DACF7F604C>) |
| 8086:8d7c | 15d9:0832 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [F36F748797](<Server/Supermicro/Super/Super Server/3657A16097B3/FREEBSD-12.2-P6/12.2-RELEASE-P4/AMD64/F36F748797>) |
| 8086:8d7c | 15d9:0834 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [B5CF5A33A0](<Server/Supermicro/Super/Super Server/606C789F6489/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/B5CF5A33A0>) |
| 8086:8d7c | 15d9:0857 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [E1EBA3B8F0](<Server/Supermicro/X10/X10SRA/0AF208B6DAE7/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E1EBA3B8F0>) |
| 8086:9d35 | 17aa:2259 | Intel            | Sunrise Point-LP Integrated Senso... | 3     |            | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d35 | 17aa:506d | Intel            | Sunrise Point-LP Integrated Senso... | 3     |            | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:a135 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [7E51DD7048](<Server/Supermicro/Super/Super Server/436CD64AB3E6/FREEBSD-12.3/12.3-RELEASE/AMD64/7E51DD7048>) |
| 8086:a1ec | 1028:0716 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [55C1BD261F](<Server/Dell/PowerEdge/PowerEdge R640/3E36764996BC/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/55C1BD261F>) |
| 8086:a1ec | 1734:1230 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 8086:a1ed | 1734:1230 | Intel            | C620 Series Chipset Family MROM 1    | 3     |            | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 1022:1455 | 1025:1246 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 2     |            | [9E03A76684](<Notebook/Acer/Predator/Predator PH517-61/401258E70C57/FREEBSD-13.0/13.0-RELEASE/AMD64/9E03A76684>) |
| 1022:145a |           | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [30590E8CCF](<Notebook/Deciso/DEC2700/DEC2700 - OPNsense Appliance/504812C630AE/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/30590E8CCF>) |
| 1022:145a | 1002:15d8 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [C1A27CA913](<Desktop/Gigabyte Technology/A320/A320M-S2H/414ECBBD0663/FREEBSD-13.0/13.0-RELEASE/AMD64/C1A27CA913>) |
| 1022:145a | 1022:7901 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [30590E8CCF](<Notebook/Deciso/DEC2700/DEC2700 - OPNsense Appliance/504812C630AE/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/30590E8CCF>) |
| 1022:145a | 1025:1246 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [9E03A76684](<Notebook/Acer/Predator/Predator PH517-61/401258E70C57/FREEBSD-13.0/13.0-RELEASE/AMD64/9E03A76684>) |
| 1022:145a | 1043:876b | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [D57DE875A6](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-GAMING-BR/51805C43859D/FREEBSD-13.0/13.0-RELEASE/AMD64/D57DE875A6>) |
| 1022:145a | 1458:d000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [B953D9D2E6](<Desktop/Gigabyte Technology/B450M/B450M DS3H/305FAB632525/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/B953D9D2E6>) |
| 1022:1485 | 1043:87cb | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:1485 | 1458:1000 | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |

