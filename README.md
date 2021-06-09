Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed pciconf reports collected by BSD users at https://bsd-hardware.info.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 4252.

Contents
--------

1. [ About ](#about)
2. [ PCI Devices ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
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

Top 100 most popular devices in each category.

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1439 | 1022:1234 | AMD        | Family 16h Processor Func... | 137   | pcib       | 7FFAED1505 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 119   | hostb      | 4AC6C9B3EB |
| 1022:780e | 1022:780e | AMD        | FCH LPC Bridge               | 111   | isab       | 7FFAED1505 |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 109   | hostb      | 7FFAED1505 |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 109   | hostb      | 7FFAED1505 |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 109   | hostb      | 7FFAED1505 |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 109   | hostb      | 7FFAED1505 |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 109   | hostb      | 7FFAED1505 |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 109   | hostb      | 7FFAED1505 |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 109   | hostb      | 7FFAED1505 |
| 1022:1566 | 1022:1566 | AMD        | Family 16h (Models 30h-3f... | 103   | hostb      | 7FFAED1505 |
| 8086:9d13 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 92    | pcib       | 8FAE98E5A6 |
| 8086:9d14 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 91    | pcib       | 8FAE98E5A6 |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 90    | pcib       | ADF592A871 |
| 8086:9d12 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 88    | pcib       | 8FAE98E5A6 |
| 8086:9d10 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 83    | pcib       | 8FAE98E5A6 |
| 8086:9d11 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 82    | pcib       | 8FAE98E5A6 |
| 8086:9d15 | 8086:7270 | Intel      | Sunrise Point-LP PCI Expr... | 81    | pcib       | 8FAE98E5A6 |
| 8086:0f1c | 8086:0f1c | Intel      | Atom Processor Z36xxx/Z37... | 71    | isab       | FF1A657505 |
| 8086:0f48 | 8086:0f48 | Intel      | Atom Processor E3800 Seri... | 71    | pcib       | FF1A657505 |
| 8086:0f4a | 8086:0f4a | Intel      | Atom Processor E3800 Seri... | 71    | pcib       | FF1A657505 |
| 8086:0f4c | 8086:0f4c | Intel      | Atom Processor E3800 Seri... | 69    | pcib       | FF1A657505 |
| 8086:0f4e | 8086:0f4e | Intel      | Atom Processor E3800 Seri... | 69    | pcib       | FF1A657505 |
| 8086:229c | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 68    | isab       | 3E773132B3 |
| 8086:2280 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 67    | hostb      | 3E773132B3 |
| 8086:22c8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 67    | pcib       | 3E773132B3 |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 66    | hostb      | 162F499C31 |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 66    | hostb      | 162F499C31 |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 66    | hostb      | 162F499C31 |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 66    | hostb      | 162F499C31 |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 66    | hostb      | 162F499C31 |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 66    | hostb      | 162F499C31 |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 66    | hostb      | 162F499C31 |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 66    | hostb      | 162F499C31 |
| 8086:5904 | 8086:2015 | Intel      | Xeon E3-1200 v6/7th Gen C... | 66    | hostb      | 8FAE98E5A6 |
| 111d:8018 |           | Microse... | PES12N3A 12-lane 3-Port P... | 65    | pcib       | DC4E61ECD4 |
| 8086:22ca | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 64    | pcib       | 3E773132B3 |
| 1022:1482 |           | AMD        | Starship/Matisse PCIe Dum... | 61    | hostb      | BD63DE17B0 |
| 8086:0f00 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 61    | hostb      | 8122431090 |
| 8086:22cc | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 56    | pcib       | 3E773132B3 |
| 1022:1440 |           | AMD        | Matisse Device 24: Functi... | 55    | hostb      | BD63DE17B0 |
| 1022:1441 |           | AMD        | Matisse Device 24: Functi... | 55    | hostb      | BD63DE17B0 |
| 1022:1442 |           | AMD        | Matisse Device 24: Functi... | 55    | hostb      | BD63DE17B0 |
| 1022:1443 |           | AMD        | Matisse Device 24: Functi... | 55    | hostb      | BD63DE17B0 |
| 1022:1444 |           | AMD        | Matisse Device 24: Functi... | 55    | hostb      | BD63DE17B0 |
| 1022:1445 |           | AMD        | Matisse Device 24: Functi... | 55    | hostb      | BD63DE17B0 |
| 1022:1446 |           | AMD        | Matisse Device 24: Functi... | 55    | hostb      | BD63DE17B0 |
| 1022:1447 |           | AMD        | Matisse Device 24: Functi... | 55    | hostb      | BD63DE17B0 |
| 8086:22ce | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 55    | pcib       | 3E773132B3 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 53    | hostb      | 4AC6C9B3EB |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 53    | hostb      | 4AC6C9B3EB |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 53    | hostb      | 4AC6C9B3EB |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 53    | hostb      | 4AC6C9B3EB |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 53    | hostb      | 4AC6C9B3EB |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 53    | hostb      | 4AC6C9B3EB |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 53    | hostb      | 4AC6C9B3EB |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 53    | hostb      | 4AC6C9B3EB |
| 1022:43c7 | 1b21:3306 | AMD        | 400 Series Chipset PCIe Port | 53    | pcib       | EDEBE87739 |
| 1022:43c6 | 1b21:0201 | AMD        | 400 Series Chipset PCIe B... | 51    | pcib       | EDEBE87739 |
| 1a03:1150 | 1a03:1150 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 49    | pcib       | B6099E8EAD |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 47    | pcib       | 162F499C31 |
| 1022:1484 | 1022:1484 | AMD        | Starship/Matisse Internal... | 42    | pcib       | BD63DE17B0 |
| 1022:1530 |           | AMD        | Family 16h Processor Func... | 41    | hostb      | C546E561B5 |
| 1022:1531 |           | AMD        | Family 16h Processor Func... | 41    | hostb      | C546E561B5 |
| 1022:1532 |           | AMD        | Family 16h Processor Func... | 41    | hostb      | C546E561B5 |
| 1022:1533 |           | AMD        | Family 16h Processor Func... | 41    | hostb      | C546E561B5 |
| 1022:1534 |           | AMD        | Family 16h Processor Func... | 41    | hostb      | C546E561B5 |
| 1022:1535 |           | AMD        | Family 16h Processor Func... | 41    | hostb      | C546E561B5 |
| 1022:1538 |           | AMD        | Family 16h Processor Func... | 41    | hostb      | C546E561B5 |
| 1022:15db |           | AMD        | Raven/Raven2 Internal PCI... | 41    | pcib       | 4AC6C9B3EB |
| 8086:9d4e | 8086:7270 | Intel      | Sunrise Point LPC Control... | 41    | isab       | 1767BCD04D |
| 1002:43a0 |           | AMD        | SB700/SB800/SB900 PCI to ... | 40    | pcib       | ADF592A871 |
| 1022:1453 | 1022:1453 | AMD        | Family 17h (Models 00h-0f... | 40    | pcib       | 162F499C31 |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 40    | pcib       | 7A41FCA3BB |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    | isab       | E5DA7D6A12 |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    | hostb      | E5DA7D6A12 |
| 8086:5ada |           | Intel      | Celeron N3350/Pentium N42... | 37    | pcib       | E5DA7D6A12 |
| 1022:15dc |           | AMD        | Raven/Raven2 Internal PCI... | 35    | pcib       | 4AC6C9B3EB |
| 1022:57ad |           | AMD        | Matisse Switch Upstream      | 35    | pcib       | 2247C7130F |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 34    | isab       | CEC3CB521D |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 34    | hostb      | CEC3CB521D |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 34    | hostb      | CEC3CB521D |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 34    | hostb      | CEC3CB521D |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 34    | hostb      | CEC3CB521D |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 34    | hostb      | CEC3CB521D |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 34    | hostb      | CEC3CB521D |
| 8086:244e | 1458:8892 | Intel      | 82801 PCI Bridge             | 34    | pcib       | 331DA3091C |
| 8086:5ad9 |           | Intel      | Celeron N3350/Pentium N42... | 34    | pcib       | E5DA7D6A12 |
| 8086:31e8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 33    | isab       | 403845D763 |
| 1022:15d0 | 1022:15d0 | AMD        | Raven/Raven2 Root Complex    | 32    | hostb      | 2F1BA02130 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 31    | pcib       | EECEB3A84C |
| 8086:244e | 8086:244e | Intel      | 82801 PCI Bridge             | 30    | pcib       | 428F39CBFF |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 29    | hostb      | 98F39AFF26 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 29    | hostb      | 98F39AFF26 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 29    | hostb      | 98F39AFF26 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 29    | hostb      | 98F39AFF26 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 29    | hostb      | 98F39AFF26 |
| 1022:790e | 1849:790e | AMD        | FCH LPC Bridge               | 29    | isab       | 9A7ADB8860 |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 29    | pcib       | BF53DF8658 |
| 8086:5ad8 |           | Intel      | Celeron N3350/Pentium N42... | 29    | pcib       | E5DA7D6A12 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5227 | 17aa:220e | Realtek... | RTS5227 PCI Express Card ... | 6     | rtsx       | 7660F9B6DB |
| 10ec:5227 | 17aa:2226 | Realtek... | RTS5227 PCI Express Card ... | 6     | rtsx       | 107AC19795 |
| 10ec:5227 | 17aa:5034 | Realtek... | RTS5227 PCI Express Card ... | 6     | rtsx       | AC567BD12D |
| 10ec:522a | 10ec:522a | Realtek... | RTS522A PCI Express Card ... | 6     | rtsx       | A628FCE397 |
| 10ec:522a | 17aa:5062 | Realtek... | RTS522A PCI Express Card ... | 5     | rtsx       | 88C27E65D7 |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 5     | sdhci_pci  | 1DBD9A5CEE |
| 10ec:5229 | 8086:2072 | Realtek... | RTS5229 PCI Express Card ... | 4     |            | 85F49B2C2D |
| 10ec:525a | 17aa:2238 | Realtek... | RTS525A PCI Express Card ... | 4     | rtsx       | 821C81E652 |
| 10ec:5227 | 10cf:187f | Realtek... | RTS5227 PCI Express Card ... | 3     | rtsx       | BCB99D0F09 |
| 10ec:5227 | 17aa:220c | Realtek... | RTS5227 PCI Express Card ... | 3     |            | B644ED3914 |
| 10ec:5227 | 17aa:2214 | Realtek... | RTS5227 PCI Express Card ... | 3     |            | CBFA45FE44 |
| 10ec:5229 | 8086:2068 | Realtek... | RTS5229 PCI Express Card ... | 3     |            | 26C56BCF3D |
| 10ec:522a | 103c:8079 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx       | 2B97986DE1 |
| 10ec:522a | 17aa:2279 | Realtek... | RTS522A PCI Express Card ... | 3     |            | 6311D603FF |
| 10ec:522a | 17aa:5122 | Realtek... | RTS522A PCI Express Card ... | 3     | rtsx       | 2F1BA02130 |
| 10ec:525a | 1028:06df | Realtek... | RTS525A PCI Express Card ... | 3     |            | C8477DA717 |
| 10ec:525a | 17aa:224f | Realtek... | RTS525A PCI Express Card ... | 3     | rtsx       | 4993AD0FEB |
| 10ec:5209 | 103c:3577 | Realtek... | RTS5209 PCI Express Card ... | 2     |            | F83C769501 |
| 10ec:5209 | 104d:90b8 | Realtek... | RTS5209 PCI Express Card ... | 2     | rtsx       | 64F3F02018 |
| 10ec:5227 | 103c:1991 | Realtek... | RTS5227 PCI Express Card ... | 2     | rtsx       | 565343B334 |
| 10ec:5227 | 103c:2246 | Realtek... | RTS5227 PCI Express Card ... | 2     | rtsx       | DA49561A8F |
| 10ec:5227 | 17aa:2217 | Realtek... | RTS5227 PCI Express Card ... | 2     | rtsx       | E9155D12C7 |
| 10ec:522a | 103c:8257 | Realtek... | RTS522A PCI Express Card ... | 2     |            | BB8BEB97BE |
| 10ec:522a | 1558:a500 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx       | 792FB07DD9 |
| 10ec:522a | 17aa:504a | Realtek... | RTS522A PCI Express Card ... | 2     |            | AA3DEADEDD |
| 10ec:522a | 17aa:5050 | Realtek... | RTS522A PCI Express Card ... | 2     |            | DDC907CCF4 |
| 10ec:522a | 17aa:5053 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx       | A069A19A1B |
| 10ec:522a | 17aa:506d | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx       | DAB0CA2417 |
| 10ec:522a | 17aa:5072 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx       | 852A900303 |
| 10ec:522a | 17aa:5082 | Realtek... | RTS522A PCI Express Card ... | 2     | rtsx       | ED75B3D15B |
| 10ec:525a | 1028:06de | Realtek... | RTS525A PCI Express Card ... | 2     |            | AF72876FD2 |
| 10ec:525a | 1028:075b | Realtek... | RTS525A PCI Express Card ... | 2     |            | 1887B030C4 |
| 10ec:525a | 1028:084c | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx       | 9468EEEF92 |
| 10ec:525a | 1028:08b8 | Realtek... | RTS525A PCI Express Card ... | 2     | rtsx       | B9D1F08BCF |
| 10ec:5286 | 1043:202f | Realtek... | RTL8402 Integrated 1-LUN ... | 2     | rtsx       | CFC7D86B5A |
| 10ec:5287 | 1025:0865 | Realtek... | RTL8411B PCI Express Card... | 2     |            | E2B6DBFE40 |
| 10ec:5287 | 1043:202f | Realtek... | RTL8411B PCI Express Card... | 2     | rtsx       | E056F1C77C |
| 10ec:5287 | 1558:1313 | Realtek... | RTL8411B PCI Express Card... | 2     |            | C23A22A72D |
| 10ec:5287 | 1558:8509 | Realtek... | RTL8411B PCI Express Card... | 2     | rtsx       | E84B5B6E5F |
| 10ec:5209 | 1025:061f | Realtek... | RTS5209 PCI Express Card ... | 1     |            | 41D2974F13 |
| 10ec:5209 | 103c:2af5 | Realtek... | RTS5209 PCI Express Card ... | 1     |            | 172F23EFAC |
| 10ec:5209 | 103c:3399 | Realtek... | RTS5209 PCI Express Card ... | 1     | rtsx       | B11946A41A |
| 10ec:5209 | 104d:908a | Realtek... | RTS5209 PCI Express Card ... | 1     |            | 7D48BD3606 |
| 10ec:5209 | 104d:90ac | Realtek... | RTS5209 PCI Express Card ... | 1     |            | 9A751DDFD8 |
| 10ec:5227 | 103c:2101 | Realtek... | RTS5227 PCI Express Card ... | 1     | rtsx       | 6BC6C5B2BF |
| 10ec:5227 | 103c:2247 | Realtek... | RTS5227 PCI Express Card ... | 1     |            | 63038D613F |
| 10ec:5229 | 1025:0946 | Realtek... | RTS5229 PCI Express Card ... | 1     |            | 6CBF99EF86 |
| 10ec:5229 | 103c:1818 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx       | 4637A9EEFF |
| 10ec:5229 | 103c:1885 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx       | AE2DE01D19 |
| 10ec:5229 | 103c:22cd | Realtek... | RTS5229 PCI Express Card ... | 1     |            | 861BDC647D |
| 10ec:5229 | 103c:2b3c | Realtek... | RTS5229 PCI Express Card ... | 1     |            | 6C628D33AB |
| 10ec:5229 | 1043:202f | Realtek... | RTS5229 PCI Express Card ... | 1     |            | DC7BB56859 |
| 10ec:5229 | 10cf:176b | Realtek... | RTS5229 PCI Express Card ... | 1     |            | 37245ACA21 |
| 10ec:5229 | 10f7:8338 | Realtek... | RTS5229 PCI Express Card ... | 1     |            | 6BBADBA65D |
| 10ec:5229 | 1179:f840 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx       | 9CF9861053 |
| 10ec:5229 | 1179:ff1e | Realtek... | RTS5229 PCI Express Card ... | 1     |            | 9FB68E38D8 |
| 10ec:5229 | 1558:6588 | Realtek... | RTS5229 PCI Express Card ... | 1     | rtsx       | 90D705DD1E |
| 10ec:5229 | 17aa:21f7 | Realtek... | RTS5229 PCI Express Card ... | 1     |            | 520982317E |
| 10ec:5229 | 17aa:3809 | Realtek... | RTS5229 PCI Express Card ... | 1     |            | D598CC6240 |
| 10ec:5229 | 17aa:381b | Realtek... | RTS5229 PCI Express Card ... | 1     |            | E4C678AFD8 |
| 10ec:5229 | 8086:2067 | Realtek... | RTS5229 PCI Express Card ... | 1     |            | 61ACC249AE |
| 10ec:522a | 103c:80fd | Realtek... | RTS522A PCI Express Card ... | 1     |            | B6C63EA3F8 |
| 10ec:522a | 103c:81a9 | Realtek... | RTS522A PCI Express Card ... | 1     |            | F27578615F |
| 10ec:522a | 103c:820d | Realtek... | RTS522A PCI Express Card ... | 1     |            | 42ECF97502 |
| 10ec:522a | 103c:8234 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx       | F808E6BB4A |
| 10ec:522a | 103c:8364 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx       | 9DD5A9EEEF |
| 10ec:522a | 103c:83c8 | Realtek... | RTS522A PCI Express Card ... | 1     |            | ADC45416CE |
| 10ec:522a | 103c:8730 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx       | DD877E6C6C |
| 10ec:522a | 1458:1000 | Realtek... | RTS522A PCI Express Card ... | 1     |            | 3623B04225 |
| 10ec:522a | 17aa:2233 | Realtek... | RTS522A PCI Express Card ... | 1     |            | 8325C794B3 |
| 10ec:522a | 17aa:2286 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx       | 0919D8936F |
| 10ec:522a | 17aa:22aa | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx       | 12C985B708 |
| 10ec:522a | 17aa:3811 | Realtek... | RTS522A PCI Express Card ... | 1     |            | B6AE43880D |
| 10ec:522a | 17aa:5048 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx       | 0A6985F078 |
| 10ec:522a | 17aa:505d | Realtek... | RTS522A PCI Express Card ... | 1     |            | CBAA19611E |
| 10ec:522a | 17aa:505f | Realtek... | RTS522A PCI Express Card ... | 1     |            | B17963CD30 |
| 10ec:522a | 17aa:5124 | Realtek... | RTS522A PCI Express Card ... | 1     |            | A1FC75A9B7 |
| 10ec:522a | 17aa:5125 | Realtek... | RTS522A PCI Express Card ... | 1     |            | 0F7FDFB5F8 |
| 10ec:522a | 17aa:5126 | Realtek... | RTS522A PCI Express Card ... | 1     |            | CD016E96EE |
| 10ec:522a | 17aa:5127 | Realtek... | RTS522A PCI Express Card ... | 1     | rtsx       | 0E5E228D18 |
| 10ec:522a | 1854:0300 | Realtek... | RTS522A PCI Express Card ... | 1     |            | D8EE6BC4E3 |
| 10ec:522a | 8086:2074 | Realtek... | RTS522A PCI Express Card ... | 1     |            | 0951C73DBA |
| 10ec:5249 | 103c:1909 | Realtek... | RTS5249 PCI Express Card ... | 1     |            | 3E9076F244 |
| 10ec:5249 | 103c:2255 | Realtek... | RTS5249 PCI Express Card ... | 1     |            | D615B5020D |
| 10ec:5249 | 1462:1113 | Realtek... | RTS5249 PCI Express Card ... | 1     |            | 35AD1FB80B |
| 10ec:5249 | 17aa:3801 | Realtek... | RTS5249 PCI Express Card ... | 1     |            | B65CD3D698 |
| 10ec:525a | 1028:06e5 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx       | 063D746A48 |
| 10ec:525a | 1028:071b | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx       | 8EC8D28024 |
| 10ec:525a | 1028:079f | Realtek... | RTS525A PCI Express Card ... | 1     |            | DEFAEE0E5C |
| 10ec:525a | 1028:07a0 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx       | 9C8BD9C479 |
| 10ec:525a | 1028:07a6 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx       | B84364959D |
| 10ec:525a | 1028:07a7 | Realtek... | RTS525A PCI Express Card ... | 1     |            | 9B38A72DD4 |
| 10ec:525a | 1028:07a8 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx       | F967516613 |
| 10ec:525a | 1028:07be | Realtek... | RTS525A PCI Express Card ... | 1     |            | 687008DA4F |
| 10ec:525a | 1028:07bf | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx       | 7D5F7B5033 |
| 10ec:525a | 1028:07f3 | Realtek... | RTS525A PCI Express Card ... | 1     |            | 1AA2A3A541 |
| 10ec:525a | 1028:0816 | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx       | 3FBA47B07F |
| 10ec:525a | 1028:0819 | Realtek... | RTS525A PCI Express Card ... | 1     |            | DADF2C296F |
| 10ec:525a | 1028:081a | Realtek... | RTS525A PCI Express Card ... | 1     |            | 9D900F918C |
| 10ec:525a | 1028:081b | Realtek... | RTS525A PCI Express Card ... | 1     | rtsx       | 2AD87768AF |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1f18 |           | Intel      | Atom processor C2000 QAT     | 21    |            | 7E6BEE8355 |
| 8086:19e2 |           | Intel      | Atom Processor C3000 Seri... | 18    |            | E6D9E7AF4E |
| 10de:0aa3 | 10de:cb79 | Nvidia     | MCP79 Co-processor           | 9     |            | F46146B79E |
| 19a2:0800 | 1734:11cc | Emulex     | ServerView iRMC HTI          | 3     |            | A9D034FE42 |
| 1734:1228 | 1734:1256 | Fujitsu... |                              | 2     |            | 6460F775B0 |
| 8086:37c8 |           | Intel      | C62x Chipset QuickAssist ... | 2     |            | 027AFA82FF |
| 10de:0753 | 1025:0157 | Nvidia     | MCP78S [GeForce 8200] Co-... | 1     |            | DB1E7A52B9 |
| 10de:0aa3 | 105b:0d52 | Nvidia     | MCP79 Co-processor           | 1     |            | 79AB8EFB37 |
| 10de:0aa3 | 19da:a108 | Nvidia     | MCP79 Co-processor           | 1     |            | 623EA6A889 |
| 1734:1228 | 1734:1229 | Fujitsu... |                              | 1     |            | 6E6F1B0F99 |
| 8086:0434 |           | Intel      | DH89XXCC Series QAT          | 1     |            | 6A8F1DF183 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d3a | 8086:1999 | Intel      | Sunrise Point-LP CSME HEC... | 83    |            | 8FAE98E5A6 |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    |            | E5DA7D6A12 |
| 8086:319a | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 33    |            | 403845D763 |
| 8086:9c3a | 8086:7270 | Intel      | 8 Series HECI #0             | 25    |            | 95A281E2F8 |
| 8086:9cba | 8086:7270 | Intel      | Wildcat Point-LP MEI Cont... | 25    |            | CD60E38216 |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 20    |            | BF53DF8658 |
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 18    |            | C44BE632D3 |
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 16    |            | A379C24586 |
| 8086:a13a | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 16    |            | 7F9CDC62A2 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 15    |            | EECEB3A84C |
| 8086:5a9a | 1849:5a9a | Intel      | Celeron N3350/Pentium N42... | 15    |            | C9218EE21D |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 14    |            | 66743A51CC |
| 8086:8c3a | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 14    |            | B5FE536096 |
| 8086:9d3a | 8086:9d3a | Intel      | Sunrise Point-LP CSME HEC... | 14    |            | 045DFAD837 |
| 8086:8c3a | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 12    |            | 09BA719AA7 |
| 8086:8c3a | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 12    |            | 6A22DA5C5D |
| 8086:8c3b | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 12    |            | 6A22DA5C5D |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 11    |            | B73E45E0DF |
| 8086:8c3a | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    |            | F2C6B4AA4D |
| 8086:8c3b | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    |            | F2C6B4AA4D |
| 8086:8c3d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 11    | uart       | 8B5FC3B9E8 |
| 8086:9de0 | 8086:7270 | Intel      | Cannon Point-LP MEI Contr... | 11    |            | 9A399621A9 |
| 8086:a360 | 1043:8694 | Intel      | Cannon Lake PCH HECI Cont... | 11    |            | DC7D89AB64 |
| 8086:19d3 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 10    |            | E6D9E7AF4E |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 10    |            | 193936B5CA |
| 8086:1d3a | 1028:0528 | Intel      | C600/X79 series chipset M... | 10    |            | 7CEC65D8F8 |
| 8086:1d3b | 1028:0528 | Intel      | C600/X79 series chipset M... | 10    |            | 7CEC65D8F8 |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 10    |            | C887FF2917 |
| 8086:8cba | 1458:1c3a | Intel      | 9 Series Chipset Family M... | 10    |            | 1DE8945DCA |
| 8086:9d3a | 8086:7270 | Intel      | Sunrise Point-LP CSME HEC... | 10    |            | CC7F385529 |
| 8086:34a8 | 8086:7270 | Intel      | Ice Lake-LP Serial IO UAR... | 9     |            | AE1BFCCF22 |
| 8086:34e0 | 8086:7270 | Intel      | Ice Lake-LP Management En... | 9     |            | AE1BFCCF22 |
| 8086:5a9c | 8086:7270 | Intel      |                              | 9     |            | 6324A2A9A9 |
| 8086:5a9e | 8086:7270 | Intel      |                              | 9     |            | 6324A2A9A9 |
| 8086:8cba | 1043:8534 | Intel      | 9 Series Chipset Family M... | 9     |            | D8ECC7077A |
| 8086:a2ba | 1043:8694 | Intel      | 200 Series PCH CSME HECI #1  | 9     |            | 15BA8E73E1 |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 8     |            | DC29D714D9 |
| 8086:2a44 | 17aa:20e6 | Intel      | Mobile 4 Series Chipset M... | 8     |            | 981517A51A |
| 8086:8c3a | 1458:1c3a | Intel      | 8 Series/C220 Series Chip... | 8     |            | 331DA3091C |
| 8086:a13a | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 8     |            | 9A0602D408 |
| 8086:19d3 | 8086:19d3 | Intel      | Atom Processor C3000 Seri... | 7     |            | B6099E8EAD |
| 8086:1e3a | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 7     |            | AB3FC66A9E |
| 8086:1e3a | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 7     |            | 0F001F65D2 |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 7     |            | AB871769F0 |
| 8086:1e3a | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 7     |            | AFC70D9C77 |
| 8086:1e3d | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 7     | uart       | AB3FC66A9E |
| 8086:319a | 1849:319a | Intel      | Celeron/Pentium Silver Pr... | 7     |            | 08D15AE852 |
| 8086:5a9a |           | Intel      | Celeron N3350/Pentium N42... | 7     |            | CC0B19EF51 |
| 8086:a2ba | 1458:1c3a | Intel      | 200 Series PCH CSME HECI #1  | 7     |            | B77CEEED88 |
| 8086:1e3d | 17aa:21f3 | Intel      | 7 Series/C210 Series Chip... | 6     | uart       | 0F001F65D2 |
| 8086:8c3a | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 6     |            | 2806E1E8CF |
| 8086:8c3a | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 6     |            | 7660F9B6DB |
| 8086:8c3a | 17aa:3098 | Intel      | 8 Series/C220 Series Chip... | 6     |            | B7EA8547CE |
| 8086:8c3d | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 6     | uart       | 2806E1E8CF |
| 8086:9cba | 17aa:2226 | Intel      | Wildcat Point-LP MEI Cont... | 6     |            | 107AC19795 |
| 8086:9cba | 17aa:5034 | Intel      | Wildcat Point-LP MEI Cont... | 6     |            | AC567BD12D |
| 8086:9cba | 8086:2057 | Intel      | Wildcat Point-LP MEI Cont... | 6     |            | 1653EA52CE |
| 8086:9d3a | 17aa:2238 | Intel      | Sunrise Point-LP CSME HEC... | 6     |            | 821C81E652 |
| 8086:9de0 | 17aa:2279 | Intel      | Cannon Point-LP MEI Contr... | 6     |            | 6311D603FF |
| 8086:a13a | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 6     |            | 9D69197550 |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 6     |            | DB95470F69 |
| 8086:a13b | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 6     |            | 9D69197550 |
| 8086:a2ba | 1849:a2ba | Intel      | 200 Series PCH CSME HECI #1  | 6     |            | 1C438D977E |
| 8086:a360 | 1458:1c3a | Intel      | Cannon Lake PCH HECI Cont... | 6     |            | B486E670FE |
| 8086:19d8 |           | Intel      | Atom Processor C3000 Seri... | 5     |            | 44E10AC014 |
| 8086:1c3a | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 5     |            | BEF38BD379 |
| 8086:1c3a | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 5     |            | E9604E52C7 |
| 8086:1c3a | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 5     |            | 49DACEE7D0 |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 5     | uart       | DC29D714D9 |
| 8086:1e3a | 1028:052c | Intel      | 7 Series/C216 Chipset Fam... | 5     |            | 351B13FD3B |
| 8086:1e3a | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 5     |            | 7C333C4F82 |
| 8086:1e3a | 8086:1e3a | Intel      | 7 Series/C216 Chipset Fam... | 5     |            | 424ADD8B03 |
| 8086:319a | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 5     |            | 8E78A839A5 |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 5     | uart       | 219E9CB1D7 |
| 8086:8c3a | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 5     |            | 56A672AF0A |
| 8086:8c3a | 1849:8c3a | Intel      | 8 Series/C220 Series Chip... | 5     |            | 7E86969DCB |
| 8086:8c3d | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 5     | uart       | 56A672AF0A |
| 8086:9c3a | 1028:05ca | Intel      | 8 Series HECI #0             | 5     |            | 1DBD9A5CEE |
| 8086:9c3a | 1028:0651 | Intel      | 8 Series HECI #0             | 5     |            | 0D1D75A914 |
| 8086:9d3a | 17aa:5062 | Intel      | Sunrise Point-LP CSME HEC... | 5     |            | 88C27E65D7 |
| 8086:9de0 | 17aa:314d | Intel      | Cannon Point-LP MEI Contr... | 5     |            | 8CE7E3A180 |
| 8086:a13a | 1849:a13a | Intel      | 100 Series/C230 Series Ch... | 5     |            | E2D2BB7F28 |
| 8086:02e0 | 8086:2081 | Intel      | Comet Lake Management Eng... | 4     |            | A09FBE5FCC |
| 8086:1c3a | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 4     |            | CEC18015BA |
| 8086:1c3a | 1849:1c3a | Intel      | 6 Series/C200 Series Chip... | 4     |            | D1580FA078 |
| 8086:1c3a | 8086:1c3a | Intel      | 6 Series/C200 Series Chip... | 4     |            | DEF6A6516D |
| 8086:1d3a | 1028:04f7 | Intel      | C600/X79 series chipset M... | 4     |            | 77475B714A |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 4     |            | 9EF7110D40 |
| 8086:1d3b | 1028:04f7 | Intel      | C600/X79 series chipset M... | 4     |            | 77475B714A |
| 8086:1e3a | 1028:0597 | Intel      | 7 Series/C216 Chipset Fam... | 4     |            | 9050866FB2 |
| 8086:1e3a | 17aa:21f6 | Intel      | 7 Series/C216 Chipset Fam... | 4     |            | 39F3A4F234 |
| 8086:1e3a | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 4     |            | FACF6FA0F8 |
| 8086:5a9a | 8086:5a9a | Intel      | Celeron N3350/Pentium N42... | 4     |            | 23751B05A9 |
| 8086:8c3a | 1028:05a5 | Intel      | 8 Series/C220 Series Chip... | 4     |            | DFF16CDD8A |
| 8086:8c3a | 1028:05cc | Intel      | 8 Series/C220 Series Chip... | 4     |            | 1847C0AADB |
| 8086:8c3a | 1734:11ea | Intel      | 8 Series/C220 Series Chip... | 4     |            | 195358C8A7 |
| 8086:8c3a | 17aa:309f | Intel      | 8 Series/C220 Series Chip... | 4     |            | 9C9E09C930 |
| 8086:8c3a | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 4     |            | 1C9FEEF8E7 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 4     | uart       | C51F274F90 |
| 8086:8c3d | 17aa:309f | Intel      | 8 Series/C220 Series Chip... | 4     | uart       | 9C9E09C930 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 106   |            | 7FFAED1505 |
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 71    |            | 8122431090 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 55    |            | 3E773132B3 |
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 45    |            | 162F499C31 |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 36    |            | 9A7ADB8860 |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 29    |            | BD63DE17B0 |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 19    |            | 10D9E99990 |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 13    |            | EDEBE87739 |
| 8086:0f18 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 12    |            | 1C67BF34D5 |
| 177d:0010 | 177d:0001 | Cavium     | CN15XX/CN16XX [Nitrox PX]    | 9     |            | B4B4EBC9F2 |
| 8086:2298 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 9     |            | CE87A10F79 |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 8     |            | 62E1C023ED |
| 1022:1468 | 1022:1468 | AMD        | Zeppelin Cryptographic Co... | 6     |            | F4A0F0941B |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 6     |            | C42933F9FD |
| 1022:15df | 1043:876b | AMD        | Family 17h (Models 10h-1f... | 4     |            | E13854338F |
| 8086:0f18 | 1458:1c3a | Intel      | Atom Processor Z36xxx/Z37... | 4     |            | 3E211C52EA |
| 8086:2298 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 4     |            | 85C4302966 |
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 4     |            | FB2CAA1184 |
| 1022:1456 | 1462:7b86 | AMD        | Family 17h (Models 00h-0f... | 3     |            | ED656E816F |
| 1022:15df | 17aa:5122 | AMD        | Family 17h (Models 10h-1f... | 3     |            | 2F1BA02130 |
| 8086:2298 | 1043:8534 | Intel      | Atom/Celeron/Pentium Proc... | 3     |            | FC5E51727E |
| 8086:2298 | 1849:2298 | Intel      | Atom/Celeron/Pentium Proc... | 3     |            | 0FE33342F7 |
| 8086:2298 | 8086:2298 | Intel      | Atom/Celeron/Pentium Proc... | 3     |            | 274326BE4A |
| 1022:1456 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 2     |            | 9E03A76684 |
| 1022:1486 | 1043:87cb | AMD        | Starship/Matisse Cryptogr... | 2     |            | 02F241B7D7 |
| 1022:1486 | 1043:8808 | AMD        | Starship/Matisse Cryptogr... | 2     |            | 8D78068CA7 |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 2     |            | 1D227A9CD2 |
| 1022:1578 | 103c:84ac | AMD        | Carrizo Platform Security... | 2     |            | 3E500C12A3 |
| 1022:1578 | 17aa:364f | AMD        | Carrizo Platform Security... | 2     |            | C43975A08F |
| 1022:15df | 103c:8786 | AMD        | Family 17h (Models 10h-1f... | 2     |            | 19F307FF6D |
| 1022:15df | 1558:a500 | AMD        | Family 17h (Models 10h-1f... | 2     |            | 792FB07DD9 |
| 1022:15df | 17aa:5082 | AMD        | Family 17h (Models 10h-1f... | 2     | ccp        | ED75B3D15B |
| 1022:15df | 17aa:5125 | AMD        | Family 17h (Models 10h-1f... | 2     |            | 7A706E46DE |
| 1022:15df | 1d05:109f | AMD        | Family 17h (Models 10h-1f... | 2     |            | 5359B4DEE9 |
| 1022:1456 | 1462:7b89 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 1123CB92BA |
| 1022:1456 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 1     |            | E7BC61FACB |
| 1022:1456 | 1462:7c02 | AMD        | Family 17h (Models 00h-0f... | 1     |            | A87473149B |
| 1022:1486 | 1043:87e2 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 94C953E866 |
| 1022:1486 | 1458:1000 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 93E2466FC6 |
| 1022:1486 | 1462:7b86 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 4CF3DD682B |
| 1022:1486 | 1462:7b89 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 6BFF2DB7E3 |
| 1022:1486 | 1462:7c02 | AMD        | Starship/Matisse Cryptogr... | 1     |            | B429D784D9 |
| 1022:1486 | 1558:50f0 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 0AC6AED43B |
| 1022:1486 | 1849:1486 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 739DB7D4A8 |
| 1022:1498 | 1022:1498 | AMD        | Starship/Matisse PTDMA       | 1     |            | 6C4D7ACEEC |
| 1022:1498 | 1458:1000 | AMD        | Starship/Matisse PTDMA       | 1     |            | 93E2466FC6 |
| 1022:1537 | 1025:0865 | AMD        | Kabini/Mullins PSP-Platfo... | 1     |            | 079F83A360 |
| 1022:1578 | 103c:8430 | AMD        | Carrizo Platform Security... | 1     |            | 0D21E083F4 |
| 1022:15df | 1025:134d | AMD        | Family 17h (Models 10h-1f... | 1     |            | 1AC21E1660 |
| 1022:15df | 1028:09f5 | AMD        | Family 17h (Models 10h-1f... | 1     |            | BA74D8EEE0 |
| 1022:15df | 103c:8523 | AMD        | Family 17h (Models 10h-1f... | 1     |            | D563D65A91 |
| 1022:15df | 103c:85b3 | AMD        | Family 17h (Models 10h-1f... | 1     |            | ECF07AD5FE |
| 1022:15df | 103c:85e0 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 5CD8E23152 |
| 1022:15df | 103c:87b1 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 5E5632D9B6 |
| 1022:15df | 1458:1000 | AMD        | Family 17h (Models 10h-1f... | 1     |            | B51CB672A4 |
| 1022:15df | 1462:7a40 | AMD        | Family 17h (Models 10h-1f... | 1     |            | FBA459287E |
| 1022:15df | 17aa:318e | AMD        | Family 17h (Models 10h-1f... | 1     |            | 115F2C7B35 |
| 1022:15df | 17aa:3728 | AMD        | Family 17h (Models 10h-1f... | 1     |            | ACD4452F00 |
| 1022:15df | 17aa:3809 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 4AC6C9B3EB |
| 1022:15df | 17aa:3816 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 1F226262CC |
| 1022:15df | 17aa:5081 | AMD        | Family 17h (Models 10h-1f... | 1     |            | BD88655975 |
| 1022:15df | 17aa:5124 | AMD        | Family 17h (Models 10h-1f... | 1     |            | A1FC75A9B7 |
| 1022:15df | 17aa:5126 | AMD        | Family 17h (Models 10h-1f... | 1     |            | CD016E96EE |
| 1022:15df | 17aa:5127 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 0E5E228D18 |
| 1022:15df | 1849:15df | AMD        | Family 17h (Models 10h-1f... | 1     |            | 05E1BDC5F5 |
| 1022:15df | 19e5:3e14 | AMD        | Family 17h (Models 10h-1f... | 1     |            | D776625073 |
| 1022:15df | 1d05:1077 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 5EC101BB3E |
| 1022:15df | 1d72:1951 | AMD        | Family 17h (Models 10h-1f... | 1     |            | A7BF2669CE |
| 8086:0f18 | 1025:0845 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | C65D08AA57 |
| 8086:0f18 | 1043:161d | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | CFC7D86B5A |
| 8086:0f18 | 17aa:2224 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | 6CD0B0ED25 |
| 8086:0f18 | 8086:2055 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | BE56203E79 |
| 8086:2298 | 1025:0998 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 39FB05C049 |
| 8086:2298 | 1043:10b0 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 5781A8B561 |
| 8086:2298 | 1043:1d5d | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 26AEF04E22 |
| 8086:2298 | 1179:f840 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 9CF9861053 |
| 8086:2298 | 1297:4033 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | BFD71EFA3B |
| 8086:2298 | 1458:1000 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 3623B04225 |
| 8086:2298 | 1462:8f83 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 4E20641615 |
| 8086:2298 | 1565:3112 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 8E97524BC4 |
| 8086:2298 | 17aa:3808 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | C5E824B558 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11c1:5901 | 11c1:5900 | LSI        | FW643 [TrueFire] PCIe 139... | 21    | fwohci     | AFC70D9C77 |
| 1180:0832 | 17aa:20c7 | Ricoh      | R5C832 IEEE 1394 Controller  | 10    | fwohci     | 981517A51A |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 6     | fwohci     | 869F003493 |
| 1106:3044 | 1458:1000 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 6     | fwohci     | F1A0CEC414 |
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 5     | fwohci     | F6EAA55ADA |
| 1106:3044 | 1043:81fe | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 5     | fwohci     | B2B56C7EC8 |
| 1106:3044 | 1106:3044 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 5     | fwohci     | 5ABCE24217 |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 5     | fwohci     | 65893EAA25 |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 4     | fwohci     | 219E9CB1D7 |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 4     |            | DC29D714D9 |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 3     | fwohci     | 211FE874FD |
| 11c1:5811 | 103c:1589 | LSI        | FW322/323 [TrueFire] 1394... | 3     |            | F97FC0533B |
| 11c1:5811 | 103c:158a | LSI        | FW322/323 [TrueFire] 1394... | 3     | fwohci     | EC84D94D08 |
| 11c1:5811 | 11c1:5811 | LSI        | FW322/323 [TrueFire] 1394... | 3     | fwohci     | ED3684513F |
| 104c:8023 | 108e:6676 | Texas I... | TSB43AB22A IEEE-1394a-200... | 2     |            | AD993A51ED |
| 104c:8023 | 15d9:0805 | Texas I... | TSB43AB22A IEEE-1394a-200... | 2     |            | 2758B438C6 |
| 1106:3403 | 1043:8374 | VIA Tec... | VT6315 Series Firewire Co... | 2     | fwohci     | 1C30F7523F |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 2     | fwohci     | 598E77539B |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 2     | fwohci     | 40687B0E17 |
| 1180:0832 | 1028:024d | Ricoh      | R5C832 IEEE 1394 Controller  | 2     | fwohci     | D5051EF185 |
| 1180:e832 | 17aa:21cf | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 2     |            | 242CD8A6E7 |
| 11c1:5811 | 1028:5811 | LSI        | FW322/323 [TrueFire] 1394... | 2     | fwohci     | 358B634E4F |
| 11c1:5901 | 1b5b:803b | LSI        | FW643 [TrueFire] PCIe 139... | 2     |            | 59E472FB01 |
| 1217:13f7 | 1028:049b | O2 Micro   | 1394 OHCI Compliant Host ... | 2     |            | 4B4CD45AC7 |
| 197b:2380 | 103c:17a7 | JMicron... | IEEE 1394 Host Controller    | 2     | fwohci     | 52BA4E835F |
| 104c:8023 | 1028:021d | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     |            | E78392BC4C |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | fwohci     | 5B1DC84DA5 |
| 104c:8023 | 1043:815b | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | fwohci     | A471763F19 |
| 104c:8023 | 108e:5354 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     |            | DDAE563E41 |
| 104c:8023 | 15d9:062c | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     |            | EB73C9D13D |
| 104c:8023 | 17aa:101c | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     |            | 428F39CBFF |
| 104c:8023 | 17aa:101d | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     |            | 6F464AAD1F |
| 104c:8024 |           | Texas I... | TSB43AB23 IEEE-1394a-2000... | 1     |            | 1170B4BFD8 |
| 104c:8024 | 1019:8056 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 1     |            | B82613052E |
| 104c:8024 | 107b:604e | Texas I... | TSB43AB23 IEEE-1394a-2000... | 1     |            | 322450B653 |
| 104c:8026 | 103c:0850 | Texas I... | TSB43AB21 IEEE-1394a-2000... | 1     |            | B7C0CB252F |
| 104c:8026 | 107b:0400 | Texas I... | TSB43AB21 IEEE-1394a-2000... | 1     | fwohci     | 41E40C653E |
| 104c:802e | 104d:818f | Texas I... | PCI7x20 1394a-2000 OHCI T... | 1     |            | F2F3923EA6 |
| 104c:803a | 1025:011f | Texas I... | PCIxx12 OHCI Compliant IE... | 1     |            | 5D6A8A51D0 |
| 104c:803a | 1028:0252 | Texas I... | PCIxx12 OHCI Compliant IE... | 1     |            | 19456100CF |
| 104c:803a | 103c:30aa | Texas I... | PCIxx12 OHCI Compliant IE... | 1     |            | 256E0AE719 |
| 104c:803a | 104d:81e6 | Texas I... | PCIxx12 OHCI Compliant IE... | 1     |            | ACE534D784 |
| 104c:803a | 104d:9016 | Texas I... | PCIxx12 OHCI Compliant IE... | 1     |            | B417DF513F |
| 104c:803a | 1179:ff00 | Texas I... | PCIxx12 OHCI Compliant IE... | 1     |            | E6E0A1294C |
| 104c:8235 | 104c:2200 | Texas I... | XIO2200A IEEE-1394a-2000 ... | 1     |            | F308AE78EA |
| 104c:823f | 3412:7856 | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 1     |            | EF29C46355 |
| 106b:0031 | 106b:5811 | Apple      | UniNorth 2 FireWire          | 1     | fwohci     | 4B7ABCF4FB |
| 1106:3044 | 103c:2a2b | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 1     |            | C93B86B3BA |
| 1106:3044 | 103c:2a64 | VIA Tec... | VT6306/7/8 [Fire II(M)] I... | 1     |            | 2A7CB7B214 |
| 1106:3403 | 1025:0157 | VIA Tec... | VT6315 Series Firewire Co... | 1     | fwohci     | DB1E7A52B9 |
| 1106:3403 | 1025:024d | VIA Tec... | VT6315 Series Firewire Co... | 1     |            | 0BC978756C |
| 1106:3403 | 1025:0250 | VIA Tec... | VT6315 Series Firewire Co... | 1     |            | 28A6795710 |
| 1106:3403 | 1028:02c9 | VIA Tec... | VT6315 Series Firewire Co... | 1     |            | 1BD1DC24C9 |
| 1106:3403 | 1028:040d | VIA Tec... | VT6315 Series Firewire Co... | 1     |            | CD086A9092 |
| 1106:3403 | 1462:576d | VIA Tec... | VT6315 Series Firewire Co... | 1     |            | 76E8524CE1 |
| 1106:3403 | 1849:3403 | VIA Tec... | VT6315 Series Firewire Co... | 1     |            | 20C77FD91B |
| 1180:0552 | 1043:1197 | Ricoh      | R5C552 IEEE 1394 Controller  | 1     |            | 1F098AC490 |
| 1180:0552 | 1043:1897 | Ricoh      | R5C552 IEEE 1394 Controller  | 1     | fwohci     | 0D292BCA2F |
| 1180:0552 | 17aa:201e | Ricoh      | R5C552 IEEE 1394 Controller  | 1     |            | F08ACC6929 |
| 1180:0832 |           | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | A76C55B066 |
| 1180:0832 | 1028:01bd | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | 7F814A7E8D |
| 1180:0832 | 1028:022f | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | D08EA3542E |
| 1180:0832 | 1028:024f | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | D25DACC162 |
| 1180:0832 | 1028:0262 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | 54854343E4 |
| 1180:0832 | 1028:029f | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | A4C1D361EB |
| 1180:0832 | 1028:02a2 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | 0B60C1CB25 |
| 1180:0832 | 103c:1521 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | 78D9A31074 |
| 1180:0832 | 103c:172a | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | 7968C7D2DD |
| 1180:0832 | 103c:30bb | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | 733C5EDB74 |
| 1180:0832 | 103c:30cc | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | 316FFB0740 |
| 1180:0832 | 103c:30e1 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | 1FD927E2CD |
| 1180:0832 | 1043:15d7 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | 593C12AA06 |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | A2EE0C9EDB |
| 1180:0832 | 104d:9035 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | 4A6CA78BC0 |
| 1180:0832 | 17aa:3829 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | 6B81593DE9 |
| 1180:0832 | 1b0a:200d | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | 50D37406DF |
| 1180:e832 | 103c:1471 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 1     |            | C1F086E90C |
| 1180:e832 | 17aa:21f6 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 1     | fwohci     | 39F3A4F234 |
| 11c1:5811 | 103c:1309 | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | BF0D7FE4F1 |
| 11c1:5811 | 103c:130a | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | EB8428D5F3 |
| 11c1:5811 | 103c:130b | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | 6DDE87584C |
| 11c1:5811 | 103c:158b | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | 3D780DD078 |
| 11c1:5811 | 103c:2a50 | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | FC1C23BEE2 |
| 11c1:5811 | 103c:2a54 | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | 22883F40DA |
| 11c1:5811 | 103c:2a5e | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | 2279DD7E5A |
| 11c1:5811 | 1734:1026 | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | FF2213E848 |
| 11c1:5811 | 1799:0515 | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | 13648FD22D |
| 11c1:5811 | 8086:5332 | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | 58F6572C18 |
| 11c1:5903 | 11c1:5900 | LSI        | FW533 [TrueFire] PCIe 139... | 1     |            | F1BC2178A9 |
| 1217:00f7 | 1028:0273 | O2 Micro   | Firewire (IEEE 1394)         | 1     |            | EF1C0E0F2E |
| 1217:00f7 | 10cf:13c6 | O2 Micro   | Firewire (IEEE 1394)         | 1     |            | AC880C0076 |
| 1217:00f7 | 1179:ff50 | O2 Micro   | Firewire (IEEE 1394)         | 1     |            | 71FD81DF30 |
| 1217:11f7 | 1028:04a4 | O2 Micro   | OZ600 1394a-2000 Controller  | 1     |            | B6C974B8BD |
| 1217:13f7 | 1028:053e | O2 Micro   | 1394 OHCI Compliant Host ... | 1     |            | A7761EE829 |
| 197b:2380 | 1025:014e | JMicron... | IEEE 1394 Host Controller    | 1     | fwohci     | 3367AE4413 |
| 197b:2380 | 103c:161c | JMicron... | IEEE 1394 Host Controller    | 1     |            | ADA1119026 |
| 197b:2380 | 103c:162a | JMicron... | IEEE 1394 Host Controller    | 1     |            | 5707FC27CE |
| 197b:2380 | 103c:1631 | JMicron... | IEEE 1394 Host Controller    | 1     |            | C240E3A1EA |
| 197b:2380 | 1043:8313 | JMicron... | IEEE 1394 Host Controller    | 1     |            | 8CF113AC55 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:22b1 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 64    | vgapci     | 3E773132B3 |
| 8086:0f31 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 60    | vgapci     | 8122431090 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 33    | vgapci     | E5DA7D6A12 |
| 8086:3185 | 8086:2212 | Intel      | GeminiLake [UHD Graphics ... | 25    | vgapci     | 403845D763 |
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 24    | vgapci     | B6099E8EAD |
| 102b:0533 | 103c:3381 | Matrox ... | MGA G200EH                   | 22    | vgapci     | 39B99E57AF |
| 8086:0a16 | 8086:0a16 | Intel      | Haswell-ULT Integrated Gr... | 21    | vgapci     | 95A281E2F8 |
| 8086:5916 | 8086:2015 | Intel      | HD Graphics 620              | 21    | vgapci     | 80122A9F4A |
| 1002:515e | 103c:31fb | AMD        | ES1000                       | 20    | vgapci     | 82D00F440D |
| 102b:0532 | 1028:04dd | Matrox ... | MGA G200eW WPCM450           | 20    | vgapci     | 9301BD0E0F |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 20    | nvidia     | 308573E703 |
| 8086:0f31 | 8086:2212 | Intel      | Atom Processor Z36xxx/Z37... | 20    | vgapci     | FF1A657505 |
| 1002:9831 | 103c:213d | AMD        | Kabini [Radeon HD 8400E]     | 17    | vgapci     | DE3D6DCDF5 |
| 8086:5916 |           | Intel      | HD Graphics 620              | 17    | vgapci     | 1767BCD04D |
| 102b:0532 | 15d9:0624 | Matrox ... | MGA G200eW WPCM450           | 15    | vgapci     | 08EB9E54FE |
| 8086:0412 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 14    | vgapci     | BF53DF8658 |
| 8086:2e32 | 8086:2e32 | Intel      | 4 Series Chipset Integrat... | 13    | agp        | E67DE92CB9 |
| 8086:5a85 | 1849:5a85 | Intel      | HD Graphics 500              | 13    | vgapci     | C9218EE21D |
| 1a03:2000 | 15d9:086d | ASPEED ... | ASPEED Graphics Family       | 12    | vgapci     | 6A22DA5C5D |
| 8086:1616 | 8086:1616 | Intel      | HD Graphics 5500             | 12    | vgapci     | CD60E38216 |
| 8086:5917 | 8086:2015 | Intel      | UHD Graphics 620             | 12    | vgapci     | 109253AFD1 |
| 1a03:2000 | 15d9:0813 | ASPEED ... | ASPEED Graphics Family       | 11    | vgapci     | 7E6BEE8355 |
| 1a03:2000 | 15d9:0921 | ASPEED ... | ASPEED Graphics Family       | 11    | vgapci     | F2C6B4AA4D |
| 8086:0126 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 11    | i915       | 66743A51CC |
| 8086:5916 | 8086:2212 | Intel      | HD Graphics 620              | 11    | vgapci     | CC7F385529 |
| 102b:0534 | 1028:0528 | Matrox ... | G200eR2                      | 10    | vgapci     | 7CEC65D8F8 |
| 1a03:2000 | 15d9:0969 | ASPEED ... | ASPEED Graphics Family       | 10    | vgapci     | E6D9E7AF4E |
| 8086:0412 | 1028:05a4 | Intel      | Xeon E3-1200 v3/4th Gen C... | 10    | vgapci     | B5FE536096 |
| 8086:1626 | 8086:1626 | Intel      | HD Graphics 6000             | 10    | vgapci     | BA0C41EF47 |
| 8086:3185 |           | Intel      | GeminiLake [UHD Graphics ... | 10    | vgapci     | 836E25BADB |
| 8086:3ea0 | 8086:2212 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 10    | vgapci     | 9A399621A9 |
| 102b:0532 | 1028:0236 | Matrox ... | MGA G200eW WPCM450           | 9     | vgapci     | 9EE7FF6592 |
| 8086:22b1 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 9     | vgapci     | CE87A10F79 |
| 8086:8a56 | 1e50:800a | Intel      | Iris Plus Graphics G1 (Ic... | 9     | vgapci     | AE1BFCCF22 |
| 8086:a001 | 8086:a001 | Intel      | Atom Processor D4xx/D5xx/... | 9     | agp        | 901FAAE6DF |
| 1002:131c | 103c:8103 | AMD        | Kaveri [Radeon R7 Graphics]  | 8     | vgapci     | 93A434D951 |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 8     | vgapci     | 9A7ADB8860 |
| 102b:0532 | 1028:0235 | Matrox ... | MGA G200eW WPCM450           | 8     | vgapci     | A2B6B36770 |
| 1a03:2000 | 15d9:0891 | ASPEED ... | ASPEED Graphics Family       | 8     | vgapci     | CE87A10F79 |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 8     | i915       | DC29D714D9 |
| 8086:0412 | 1458:d000 | Intel      | Xeon E3-1200 v3/4th Gen C... | 8     | vgapci     | CC49321B12 |
| 8086:5916 | 8086:5916 | Intel      | HD Graphics 620              | 8     | vgapci     | 045DFAD837 |
| 8086:a002 | 8086:a001 | Intel      | Atom Processor D4xx/D5xx/... | 8     | vgapci     | 901FAAE6DF |
| 1002:15d8 | 1002:15d8 | AMD        | Picasso                      | 7     | vgapci     | EF29C46355 |
| 1a03:2000 | 1849:2000 | ASPEED ... | ASPEED Graphics Family       | 7     | vgapci     | E08A5E6F7C |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 7     | i915       | 219E9CB1D7 |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 7     | vgapci     | EECEB3A84C |
| 8086:0166 | 17aa:21f3 | Intel      | 3rd Gen Core processor Gr... | 7     | i915       | 0F001F65D2 |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 7     | i915       | AB871769F0 |
| 8086:0412 | 1028:0612 | Intel      | Xeon E3-1200 v3/4th Gen C... | 7     | vgapci     | 0FDB487871 |
| 8086:0f31 | 1849:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 7     | vgapci     | 62E1C023ED |
| 8086:3185 | 1849:2212 | Intel      | GeminiLake [UHD Graphics ... | 7     | vgapci     | 08D15AE852 |
| 102b:0522 | 1734:11cc | Matrox ... | MGA G200e [Pilot] ServerE... | 6     | vgapci     | A9D034FE42 |
| 102b:0530 | 1014:0369 | Matrox ... | MGA G200EV                   | 6     | vgapci     | 5F9F2C2232 |
| 102b:0532 | 15d9:060a | Matrox ... | MGA G200eW WPCM450           | 6     | vgapci     | B316BFD5CF |
| 1a03:2000 | 15d9:0884 | ASPEED ... | ASPEED Graphics Family       | 6     | vgapci     | 9D69197550 |
| 8086:0102 | 1043:844d | Intel      | 2nd Generation Core Proce... | 6     | vgapci     | 273E379D9F |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 6     | vgapci     | 6BD5EA83B3 |
| 8086:0412 | 103c:1998 | Intel      | Xeon E3-1200 v3/4th Gen C... | 6     | vgapci     | 2806E1E8CF |
| 8086:0416 | 17aa:220e | Intel      | 4th Gen Core Processor In... | 6     | i915       | 7660F9B6DB |
| 8086:1616 | 17aa:2226 | Intel      | HD Graphics 5500             | 6     | i915       | 107AC19795 |
| 8086:1916 | 17aa:2238 | Intel      | Skylake GT2 [HD Graphics ... | 6     | i915       | 821C81E652 |
| 8086:1916 | 8086:2015 | Intel      | Skylake GT2 [HD Graphics ... | 6     | vgapci     | 6E4A978A48 |
| 8086:2a42 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 6     | agp        | 981517A51A |
| 8086:2a43 | 17aa:20e4 | Intel      | Mobile 4 Series Chipset I... | 6     | vgapci     | 981517A51A |
| 1002:9712 | 103c:1609 | AMD        | RS880M [Mobility Radeon H... | 5     | vgapci     | 080EFAF98A |
| 10de:128b | 19da:5360 | Nvidia     | GK208B [GeForce GT 710]      | 5     | vgapci     | BD63DE17B0 |
| 8086:0102 | 1028:04f5 | Intel      | 2nd Generation Core Proce... | 5     | vgapci     | E9604E52C7 |
| 8086:0152 | 1043:844d | Intel      | Xeon E3-1200 v2/3rd Gen C... | 5     | vgapci     | C44BE632D3 |
| 8086:0162 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 5     | vgapci     | 2F1E8F315F |
| 8086:0412 | 103c:18e7 | Intel      | Xeon E3-1200 v3/4th Gen C... | 5     | vgapci     | 56A672AF0A |
| 8086:0a16 | 1028:05ca | Intel      | Haswell-ULT Integrated Gr... | 5     | i915       | 1DBD9A5CEE |
| 8086:3ea0 | 17aa:2279 | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 5     | i915       | 6311D603FF |
| 8086:3ea0 | 17aa:314d | Intel      | WhiskeyLake-U GT2 [UHD Gr... | 5     | vgapci     | 8CE7E3A180 |
| 8086:5927 | 8086:2212 | Intel      | Iris Plus Graphics 650       | 5     | vgapci     | 7EA373882A |
| 8086:5a85 | 19da:b325 | Intel      | HD Graphics 500              | 5     | vgapci     | CC0B19EF51 |
| 102b:0522 | 103c:31fa | Matrox ... | MGA G200e [Pilot] ServerE... | 4     | vgapci     | A6CB9D7C3F |
| 102b:0522 | 8086:0103 | Matrox ... | MGA G200e [Pilot] ServerE... | 4     | vgapci     | 289D61B1B2 |
| 102b:0534 | 1028:04f7 | Matrox ... | G200eR2                      | 4     | vgapci     | 77475B714A |
| 102b:0534 | 1028:05e5 | Matrox ... | G200eR2                      | 4     | vgapci     | 6CBE8CABB7 |
| 102b:0534 | 1028:0601 | Matrox ... | G200eR2                      | 4     | vgapci     | 5ACC629D2E |
| 10de:040f | 10de:049a | Nvidia     | G84GL [Quadro FX 1700]       | 4     | vgapci     | 4D7013AEAB |
| 10de:0640 |           | Nvidia     | G96C [GeForce 9500 GT]       | 4     | vgapci     | 4B8BE1B909 |
| 10de:06fd | 10de:062e | Nvidia     | G98 [Quadro NVS 295]         | 4     | vgapci     | D8B645D95D |
| 10de:128b | 1043:85e7 | Nvidia     | GK208B [GeForce GT 710]      | 4     | nvidia     | 5ABCE24217 |
| 10de:1d01 | 1462:8c98 | Nvidia     | GP108 [GeForce GT 1030]      | 4     | nvidia     | 20052B0D55 |
| 1a03:2000 | 1043:8373 | ASPEED ... | ASPEED Graphics Family       | 4     | vgapci     | 8A9F749148 |
| 1a03:2000 | 15d9:0986 | ASPEED ... | ASPEED Graphics Family       | 4     | vgapci     | 027AFA82FF |
| 1a03:2000 | 15d9:1b0e | ASPEED ... | ASPEED Graphics Family       | 4     | vgapci     | FDDB0EDEE4 |
| 8086:0046 |           | Intel      | Core Processor Integrated... | 4     | agp        | 0AB44E95DF |
| 8086:0152 | 103c:3397 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 4     | vgapci     | AB3FC66A9E |
| 8086:0152 | 1849:0152 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 4     | vgapci     | D4713F1CC0 |
| 8086:0156 | 1458:d000 | Intel      | 3rd Gen Core processor Gr... | 4     | vgapci     | A379C24586 |
| 8086:0166 | 1028:0597 | Intel      | 3rd Gen Core processor Gr... | 4     | i915       | 9050866FB2 |
| 8086:0166 | 17aa:21fb | Intel      | 3rd Gen Core processor Gr... | 4     | i915       | FACF6FA0F8 |
| 8086:0402 | 8086:0402 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | vgapci     | 428B16A419 |
| 8086:041e | 1028:0612 | Intel      | 4th Generation Core Proce... | 4     | vgapci     | 09BA719AA7 |
| 8086:041e | 17aa:3098 | Intel      | 4th Generation Core Proce... | 4     | vgapci     | B7EA8547CE |
| 8086:0a16 | 1028:0651 | Intel      | Haswell-ULT Integrated Gr... | 4     | i915       | 0D1D75A914 |
| 8086:0be2 | 8086:1999 | Intel      | Atom Processor D2xxx/N2xx... | 4     | vgapci     | 8D59B379FD |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 8086:7270 | Intel      | Sunrise Point-LP PMC         | 95    |            | 8FAE98E5A6 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 28    |            | 1133FFB4F2 |
| 8086:a121 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 17    |            | 7F9CDC62A2 |
| 8086:9def | 8086:7270 | Intel      | Cannon Point-LP Shared SRAM  | 15    |            | BD8BEA4A6A |
| 8086:9d21 | 8086:9d21 | Intel      | Sunrise Point-LP PMC         | 14    |            | 045DFAD837 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 11    |            | DC7D89AB64 |
| 8086:19de | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 10    |            | E6D9E7AF4E |
| 10de:0a88 |           | Nvidia     | MCP79 Memory Controller      | 9     |            | F46146B79E |
| 10de:0a89 |           | Nvidia     | MCP79 Memory Controller      | 9     |            | F46146B79E |
| 10de:0a98 | 10de:cb79 | Nvidia     | MCP79 Memory Controller      | 9     |            | F46146B79E |
| 10de:0aa4 |           | Nvidia     | MCP79 Memory Controller      | 9     |            | F46146B79E |
| 8086:34ef | 8086:7270 | Intel      | Ice Lake-LP DRAM Controller  | 9     |            | AE1BFCCF22 |
| 8086:a2a1 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 9     |            | 15BA8E73E1 |
| 8086:a121 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 8     |            | 9A0602D408 |
| 8086:19de | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 7     |            | B6099E8EAD |
| 8086:a2a1 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 7     |            | B77CEEED88 |
| 8086:9d21 | 17aa:2238 | Intel      | Sunrise Point-LP PMC         | 6     |            | 821C81E652 |
| 8086:9def |           | Intel      | Cannon Point-LP Shared SRAM  | 6     |            | 852A900303 |
| 8086:9def | 17aa:2279 | Intel      | Cannon Point-LP Shared SRAM  | 6     |            | 6311D603FF |
| 8086:a121 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 6     |            | 9D69197550 |
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 6     |            | DB95470F69 |
| 8086:a2a1 | 1849:a2a1 | Intel      | 200 Series/Z370 Chipset F... | 6     |            | 1C438D977E |
| 8086:06ef | 8086:7270 | Intel      | Comet Lake PCH Shared SRAM   | 5     |            | 0B3C9A332D |
| 8086:9d21 | 17aa:5062 | Intel      | Sunrise Point-LP PMC         | 5     |            | 88C27E65D7 |
| 8086:9def | 17aa:314d | Intel      | Cannon Point-LP Shared SRAM  | 5     |            | 8CE7E3A180 |
| 8086:a121 | 1849:a121 | Intel      | 100 Series/C230 Series Ch... | 5     |            | E2D2BB7F28 |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 5     |            | 25E20C3F35 |
| 1912:0011 |           | Renesas... | SH7757 PCIe End-Point [PBI]  | 4     |            | 6CBE8CABB7 |
| 8086:02ef | 8086:2081 | Intel      | Comet Lake PCH-LP Shared ... | 4     |            | A09FBE5FCC |
| 8086:02ef | 8086:7270 | Intel      | Comet Lake PCH-LP Shared ... | 4     |            | 1DCB55D9FE |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 4     |            | 2B97986DE1 |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 4     |            | 005F738691 |
| 8086:a1a1 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 4     |            | 027AFA82FF |
| 8086:a36f | 1849:a36f | Intel      | Cannon Lake PCH Shared SRAM  | 4     |            | 23196AA66B |
| 8086:02ef | 1028:09ec | Intel      | Comet Lake PCH-LP Shared ... | 3     |            | 80D7BF959A |
| 8086:06ef | 1849:06ef | Intel      | Comet Lake PCH Shared SRAM   | 3     |            | 6E0891CE80 |
| 8086:34ef |           | Intel      | Ice Lake-LP DRAM Controller  | 3     |            | C2D56FC369 |
| 8086:444e | 8086:444e | Intel      | Turbo Memory Controller      | 3     |            | CF75F7C9CB |
| 8086:9d21 | 17aa:2245 | Intel      | Sunrise Point-LP PMC         | 3     |            | E27342AB94 |
| 8086:9d21 | 17aa:224f | Intel      | Sunrise Point-LP PMC         | 3     |            | 4993AD0FEB |
| 8086:9d21 | 17aa:2258 | Intel      | Sunrise Point-LP PMC         | 3     |            | EBD44C21D9 |
| 8086:9d21 | 17aa:225c | Intel      | Sunrise Point-LP PMC         | 3     |            | 16206C4970 |
| 8086:9d21 | 19e5:3e04 | Intel      | Sunrise Point-LP PMC         | 3     |            | F7E09652D9 |
| 8086:9d21 | 8086:2063 | Intel      | Sunrise Point-LP PMC         | 3     |            | 4607D1410C |
| 8086:9d21 | 8086:2068 | Intel      | Sunrise Point-LP PMC         | 3     |            | 26C56BCF3D |
| 8086:a121 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 3     |            | EFE3DBF989 |
| 8086:a121 | 1028:06b9 | Intel      | 100 Series/C230 Series Ch... | 3     |            | A0159BAB57 |
| 8086:a121 | 1028:06ba | Intel      | 100 Series/C230 Series Ch... | 3     |            | D9AE9EC6F6 |
| 8086:a121 | 1028:07c5 | Intel      | 100 Series/C230 Series Ch... | 3     |            | 17A0A5FDCF |
| 8086:a121 | 103c:8054 | Intel      | 100 Series/C230 Series Ch... | 3     |            | AB00142638 |
| 8086:a1a1 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1a1 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 10de:0270 | 1043:81c0 | Nvidia     | MCP51 Host Bridge            | 2     |            | DAE16641BB |
| 10de:0361 | 108e:6676 | Nvidia     | MCP55 LPC Bridge             | 2     |            | AD993A51ED |
| 10de:0369 | 108e:6676 | Nvidia     | MCP55 Memory Controller      | 2     |            | AD993A51ED |
| 10de:03e2 | 1849:03e2 | Nvidia     | MCP61 Host Bridge            | 2     |            | 5ABCE24217 |
| 10de:03f5 | 1458:0c11 | Nvidia     | MCP61 Memory Controller      | 2     |            | 5D94572E10 |
| 10de:03f5 | 1849:03eb | Nvidia     | MCP61 Memory Controller      | 2     |            | 5ABCE24217 |
| 8086:02ef |           | Intel      | Comet Lake PCH-LP Shared ... | 2     |            | 0BD96EF663 |
| 8086:02ef | 17aa:5079 | Intel      | Comet Lake PCH-LP Shared ... | 2     |            | 94D082C57C |
| 8086:06ef | 17aa:3172 | Intel      | Comet Lake PCH Shared SRAM   | 2     |            | 1F7035C993 |
| 8086:06ef | 17aa:3826 | Intel      | Comet Lake PCH Shared SRAM   | 2     |            | 2BE8CF963C |
| 8086:43ef |           | Intel      | Tiger Lake-H Shared SRAM     | 2     |            | 4427B4BA61 |
| 8086:43ef | 1043:8694 | Intel      | Tiger Lake-H Shared SRAM     | 2     |            | DB12A78352 |
| 8086:9d21 | 1028:06df | Intel      | Sunrise Point-LP PMC         | 2     |            | DA926F1065 |
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 2     |            | 1887B030C4 |
| 8086:9d21 | 1043:10a1 | Intel      | Sunrise Point-LP PMC         | 2     |            | D7D299F9FC |
| 8086:9d21 | 1043:1c7d | Intel      | Sunrise Point-LP PMC         | 2     |            | 57018EDD10 |
| 8086:9d21 | 1297:4037 | Intel      | Sunrise Point-LP PMC         | 2     |            | EF18FBE1C6 |
| 8086:9d21 | 1558:1313 | Intel      | Sunrise Point-LP PMC         | 2     |            | C23A22A72D |
| 8086:9d21 | 17aa:224b | Intel      | Sunrise Point-LP PMC         | 2     |            | FAA7BECF82 |
| 8086:9d21 | 17aa:2259 | Intel      | Sunrise Point-LP PMC         | 2     |            | 9773669778 |
| 8086:9d21 | 17aa:225a | Intel      | Sunrise Point-LP PMC         | 2     |            | D5A1C088B3 |
| 8086:9d21 | 17aa:504a | Intel      | Sunrise Point-LP PMC         | 2     |            | AA3DEADEDD |
| 8086:9d21 | 17aa:5053 | Intel      | Sunrise Point-LP PMC         | 2     |            | A069A19A1B |
| 8086:9d21 | 17aa:506d | Intel      | Sunrise Point-LP PMC         | 2     |            | DAB0CA2417 |
| 8086:9d21 | 8086:2070 | Intel      | Sunrise Point-LP PMC         | 2     |            | 3802B33F17 |
| 8086:9def | 1028:08b8 | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | B9D1F08BCF |
| 8086:9def | 8086:2074 | Intel      | Cannon Point-LP Shared SRAM  | 2     |            | 0951C73DBA |
| 8086:a121 | 1028:0798 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 0E99E72EC9 |
| 8086:a121 | 103c:805d | Intel      | 100 Series/C230 Series Ch... | 2     |            | DC4E61ECD4 |
| 8086:a121 | 103c:805f | Intel      | 100 Series/C230 Series Ch... | 2     |            | 8FD4D48F7E |
| 8086:a121 | 103c:8165 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 0D13EC7AC2 |
| 8086:a121 | 103c:8257 | Intel      | 100 Series/C230 Series Ch... | 2     |            | BB8BEB97BE |
| 8086:a121 | 1297:4041 | Intel      | 100 Series/C230 Series Ch... | 2     |            | E39173782F |
| 8086:a121 | 1558:8509 | Intel      | 100 Series/C230 Series Ch... | 2     |            | E84B5B6E5F |
| 8086:a121 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 2     |            | B34EE32475 |
| 8086:a121 | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 2     |            | DDC907CCF4 |
| 8086:a1a1 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1a1 | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1a1 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 8086:a1a1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a2a1 | 1028:07a1 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 1499695AAE |
| 8086:a2a1 | 103c:8299 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | C785FAC7E9 |
| 8086:a2a1 | 103c:829a | Intel      | 200 Series/Z370 Chipset F... | 2     |            | 2FC6120246 |
| 8086:a2a1 | 1462:7c08 | Intel      | 200 Series/Z370 Chipset F... | 2     |            | D8B645D95D |
| 8086:a36f | 17aa:2267 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 045A80D8BC |
| 8086:a36f | 17aa:312d | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | 5E6FBBD1EE |
| 8086:a36f | 17aa:3824 | Intel      | Cannon Lake PCH Shared SRAM  | 2     |            | DCE3BA8C99 |
| 10de:005e | 1043:815a | Nvidia     | CK804 Memory Controller      | 1     |            | B2B56C7EC8 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 1     |            | 1F098AC490 |
| 1039:7013 | 14c0:0012 | Silicon... | AC'97 Modem Controller       | 1     |            | 56A5581907 |
| 10b9:5457 | 103c:0850 | ULi Ele... | M5457 AC'97 Modem Controller | 1     |            | B7C0CB252F |
| 8086:2486 | 144f:1050 | Intel      | 82801CA/CAM AC'97 Modem C... | 1     |            | 41E40C653E |
| 8086:24c6 | 1014:0559 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | BDD45ACD8D |
| 8086:24c6 | 104d:818c | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | F2F3923EA6 |
| 8086:24c6 | 10f7:834b | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | F6EC2858A5 |
| 8086:266d | 14f1:5423 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     |            | D2CBB1F229 |

### Multimedia (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:15e2 | 1022:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 11    |            | D305B914E2 |
| 8086:1919 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 6     |            | CC7F385529 |
| 14e4:1570 | 14e4:1570 | Broadcom   | 720p FaceTime HD Camera      | 5     |            | 1C9FEEF8E7 |
| 1022:15e2 | 103c:8786 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 19F307FF6D |
| 1022:15e2 | 1558:a500 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 792FB07DD9 |
| 1022:15e2 | 17aa:5082 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | ED75B3D15B |
| 1022:15e2 | 17aa:5125 | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 7A706E46DE |
| 1022:15e2 | 1d05:109f | AMD        | Raven/Raven2/FireFlight/R... | 2     |            | 5359B4DEE9 |
| 8086:22b8 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 2     |            | 688C95BDA6 |
| 1022:15e2 | 1025:134d | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 1AC21E1660 |
| 1022:15e2 | 1028:09f5 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | BA74D8EEE0 |
| 1022:15e2 | 103c:8433 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 5A242D9C9E |
| 1022:15e2 | 103c:8523 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | D563D65A91 |
| 1022:15e2 | 103c:85b3 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | ECF07AD5FE |
| 1022:15e2 | 103c:85e0 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 5CD8E23152 |
| 1022:15e2 | 103c:8730 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | DD877E6C6C |
| 1022:15e2 | 103c:87b1 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 5E5632D9B6 |
| 1022:15e2 | 1458:1000 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | B51CB672A4 |
| 1022:15e2 | 17aa:318e | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 115F2C7B35 |
| 1022:15e2 | 17aa:3728 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | ACD4452F00 |
| 1022:15e2 | 17aa:5081 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | BD88655975 |
| 1022:15e2 | 17aa:5124 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | A1FC75A9B7 |
| 1022:15e2 | 17aa:5126 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | CD016E96EE |
| 1022:15e2 | 17aa:5127 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 0E5E228D18 |
| 1022:15e2 | 1849:15e2 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | 05E1BDC5F5 |
| 1022:15e2 | 19e5:3e14 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | D776625073 |
| 1022:15e2 | 1d72:1951 | AMD        | Raven/Raven2/FireFlight/R... | 1     |            | A7BF2669CE |
| 1131:7133 | 1043:4876 | Philips... | SAA7131/SAA7133/SAA7135 V... | 1     |            | F521976730 |
| 1131:7146 | 13c2:101a | Philips... | SAA7146                      | 1     |            | 8CF113AC55 |
| 14f1:8811 | 0070:3401 | Conexan... | CX23880/1/2/3 PCI Video a... | 1     |            | 1BC05B5951 |
| 8086:1919 | 144d:c14f | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 91C76DB748 |
| 8086:5a88 |           | Intel      | Celeron N3350/Pentium N42... | 1     |            | B9F23EE753 |
| 8086:9d32 | 144d:c14f | Intel      | CSI-2 Host Controller        | 1     |            | 91C76DB748 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:150c |           | Intel      | 82583V Gigabit Network Co... | 58    | em         | 8FAE98E5A6 |
| 8086:1533 |           | Intel      | I210 Gigabit Network Conn... | 41    | igb        | 1133FFB4F2 |
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 33    | igb        | F2C6B4AA4D |
| 10ec:8168 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 26    | re         | A76C55B066 |
| 8086:1539 | 1849:1539 | Intel      | I211 Gigabit Network Conn... | 24    | igb        | 2247C7130F |
| 10ec:8125 | 10ec:0123 | Realtek... | RTL8125 2.5GbE Controller    | 23    | re         | 695EB546EF |
| 8086:1521 | 8086:0001 | Intel      | I350 Gigabit Network Conn... | 23    | igb        | E13854338F |
| 8086:1521 | 8086:5001 | Intel      | I350 Gigabit Network Conn... | 21    | igb        | 9F4EBE949F |
| 14e4:163b | 1028:04dd | Broadcom   | NetXtreme II BCM5716 Giga... | 20    | bce        | 9301BD0E0F |
| 8086:150e | 103c:1780 | Intel      | 82580 Gigabit Network Con... | 20    | igb        | 03D5E3FAC9 |
| 8086:10e8 | 8086:a02c | Intel      | 82576 Gigabit Network Con... | 17    | igb        | DC4E61ECD4 |
| 8086:10bc | 103c:704b | Intel      | 82571EB/82571GB Gigabit E... | 16    | em         | DE3D6DCDF5 |
| 14e4:165f | 1028:1f5b | Broadcom   | NetXtreme BCM5720 Gigabit... | 15    | bge        | 7CEC65D8F8 |
| 8086:1521 |           | Intel      | I350 Gigabit Network Conn... | 14    | igb        | 045DFAD837 |
| 8086:15e4 |           | Intel      | Ethernet Connection X553 ... | 13    | ix         | B6099E8EAD |
| 8086:105e | 8086:125e | Intel      | 82571EB/82571GB Gigabit E... | 12    | em         | DFF16CDD8A |
| 8086:156f |           | Intel      | Ethernet Connection I219-LM  | 12    | em         | 045DFAD837 |
| 8086:1572 |           | Intel      | Ethernet Controller X710 ... | 12    | ixl        | 94F3A7B95A |
| 8086:15ac | 15d9:15ac | Intel      | Ethernet Connection X552 ... | 12    | ix         | F2C6B4AA4D |
| 8086:1502 | 1028:052c | Intel      | 82579LM Gigabit Network C... | 11    | em         | 7C333C4F82 |
| 8086:1502 | 15d9:1502 | Intel      | 82579LM Gigabit Network C... | 11    | em         | 08EB9E54FE |
| 8086:15ad | 15d9:15ad | Intel      | Ethernet Connection X552/... | 11    | ix         | 6A22DA5C5D |
| 8086:15b8 | 1043:8672 | Intel      | Ethernet Connection (2) I... | 11    | em         | 15BA8E73E1 |
| 8086:15e5 |           | Intel      | Ethernet Connection X553 ... | 11    | ix         | B6099E8EAD |
| 8086:1f41 | 15d9:1f41 | Intel      | Ethernet Connection I354     | 11    | igb        | 7E6BEE8355 |
| 10ec:8168 | 1028:0612 | Realtek... | RTL8111/8168/8411 PCI Exp... | 10    | re         | 09BA719AA7 |
| 8086:10bc | 8086:11bc | Intel      | 82571EB/82571GB Gigabit E... | 10    | em         | 7A41FCA3BB |
| 10de:0ab0 | 10de:cb79 | Nvidia     | MCP79 Ethernet               | 9     | nfe        | F46146B79E |
| 10ec:8169 | 10ec:8169 | Realtek... | RTL8169 PCI Gigabit Ether... | 9     | re         | F1A0CEC414 |
| 14e4:1639 | 103c:7055 | Broadcom   | NetXtreme II BCM5709 Giga... | 9     | bce        | 82D00F440D |
| 8086:10d6 | 8086:145a | Intel      | 82575GB Gigabit Network C... | 9     | igb        | B316BFD5CF |
| 8086:153b | 1458:e000 | Intel      | Ethernet Connection I217-V   | 9     | em         | 1DE8945DCA |
| 14e4:1639 | 1028:0236 | Broadcom   | NetXtreme II BCM5709 Giga... | 8     | bce        | 9EE7FF6592 |
| 8086:15a1 | 1043:85c4 | Intel      | Ethernet Connection (2) I... | 8     | em         | 6B06C67610 |
| 8086:27dc | 8086:27dc | Intel      | NM10/ICH7 Family LAN Cont... | 8     | fxp        | E67DE92CB9 |
| 10ec:8161 | 10ec:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | re         | ADF592A871 |
| 10ec:8168 | 103c:8103 | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | re         | 93A434D951 |
| 10ec:8168 | 1734:11ff | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | re         | CDF0C1C8CE |
| 14e4:165b | 103c:705d | Broadcom   | NetXtreme BCM5723 Gigabit... | 7     | bge        | A6CB9D7C3F |
| 8086:10c9 | 8086:a03c | Intel      | 82576 Gigabit Network Con... | 7     | igb        | A5F2E926FB |
| 8086:10f5 | 17aa:20ee | Intel      | 82567LM Gigabit Network C... | 7     | em         | 926FE13D8F |
| 8086:1502 | 103c:3397 | Intel      | 82579LM Gigabit Network C... | 7     | em         | AB3FC66A9E |
| 8086:1503 | 1043:849c | Intel      | 82579V Gigabit Network Co... | 7     | em         | EECEB3A84C |
| 8086:15b7 | 1734:121f | Intel      | Ethernet Connection (2) I... | 7     | em         | 9A0602D408 |
| 8086:15b8 | 1849:15b8 | Intel      | Ethernet Connection (2) I... | 7     | em         | E2D2BB7F28 |
| 14e4:1639 | 14e4:0907 | Broadcom   | NetXtreme II BCM5709 Giga... | 6     | bce        | 411477E260 |
| 14e4:1682 | 106b:00f6 | Broadcom   | NetXtreme BCM57762 Gigabi... | 6     | bge        | 1C9FEEF8E7 |
| 8086:10c9 | 8086:a04c | Intel      | 82576 Gigabit Network Con... | 6     | igb        | 5283765CBE |
| 8086:1516 | 8086:12b2 | Intel      | 82580 Gigabit Network Con... | 6     | igb        | DB450EAFB5 |
| 8086:1533 | 15bb:30e0 | Intel      | I210 Gigabit Network Conn... | 6     | igb        | 428B16A419 |
| 8086:1536 |           | Intel      | I210 Gigabit Fiber Networ... | 6     | igb        | B6099E8EAD |
| 8086:1539 | 1297:4057 | Intel      | I211 Gigabit Network Conn... | 6     | igb        | A628FCE397 |
| 8086:153a | 103c:18e7 | Intel      | Ethernet Connection I217-LM  | 6     | em         | 56A672AF0A |
| 8086:153a | 103c:1998 | Intel      | Ethernet Connection I217-LM  | 6     | em         | 2806E1E8CF |
| 8086:153a | 15d9:153a | Intel      | Ethernet Connection I217-LM  | 6     | em         | 683CFEADBA |
| 8086:1563 | 8086:0001 | Intel      | Ethernet Controller 10G X... | 6     | ix         | B486E670FE |
| 10ec:8168 | 1028:04f5 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | re         | E9604E52C7 |
| 10ec:8168 | 1043:87c3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | re         | CBBF4F86CD |
| 10ec:8168 | 17aa:3098 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | re         | 0D584C2A00 |
| 10ec:8168 | 17aa:314d | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | re         | 8CE7E3A180 |
| 10ec:8168 | 19da:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | re         | 5FE156B619 |
| 1186:4300 | 1186:4300 | D-Link ... | DGE-528T Gigabit Ethernet... | 5     | re         | DAA7AFC688 |
| 11ab:436a | 11ab:00ba | Marvell... | 88E8058 PCI-E Gigabit Eth... | 5     | mskc       | ED3684513F |
| 14e4:1639 | 1014:03a9 | Broadcom   | NetXtreme II BCM5709 Giga... | 5     | bce        | 5F9F2C2232 |
| 8086:107d | 8086:1082 | Intel      | 82572EI Gigabit Ethernet ... | 5     | em         | ABC7136D00 |
| 8086:10bc | 8086:10bc | Intel      | 82571EB/82571GB Gigabit E... | 5     | em         | 08EB9E54FE |
| 8086:10d3 | 8086:0001 | Intel      | 82574L Gigabit Network Co... | 5     | em         | FF2213E848 |
| 8086:1503 | 1458:e000 | Intel      | 82579V Gigabit Network Co... | 5     | em         | D3742D3898 |
| 8086:150c | 1462:6c40 | Intel      | 82583V Gigabit Network Co... | 5     | em         | 424ADD8B03 |
| 8086:37d0 | 15d9:37d0 | Intel      | Ethernet Connection X722 ... | 5     | ixl        | 027AFA82FF |
| 1022:1458 | 1022:1458 | AMD        | Family 17h Processor 10 G... | 4     | ax         | F4A0F0941B |
| 1077:8020 | 103c:3733 | QLogic     | cLOM8214 1/10GbE Controller  | 4     | ql         | 74F5DBCF1B |
| 10ec:8136 | 1028:0597 | Realtek... | RTL810xE PCI Express Fast... | 4     | re         | 9050866FB2 |
| 10ec:8168 | 1462:7b86 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | re         | ED656E816F |
| 10ec:8168 | 1565:2312 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | re         | 41A2A2E434 |
| 10ec:8168 | 1734:11c0 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | re         | 3D765EAF63 |
| 10ec:8168 | 17aa:5072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | re         | 852A900303 |
| 1425:4001 |           | Chelsio... | T420-CR Unified Wire Ethe... | 4     | t4iov      | 536E6B5FDF |
| 1425:4401 |           | Chelsio... | T420-CR Unified Wire Ethe... | 4     | t4nex      | 536E6B5FDF |
| 14e4:165f | 1028:04f7 | Broadcom   | NetXtreme BCM5720 Gigabit... | 4     | bge        | 77475B714A |
| 14e4:165f | 1028:05e5 | Broadcom   | NetXtreme BCM5720 Gigabit... | 4     | bge        | 6CBE8CABB7 |
| 14e4:1678 | 103c:703e | Broadcom   | NetXtreme BCM5715 Gigabit... | 4     | bge        | 59C59BDA2A |
| 14e4:1684 | 14e4:1684 | Broadcom   | NetXtreme BCM5764M Gigabi... | 4     | bge        | 0AB44E95DF |
| 14e4:168e | 14e4:1006 | Broadcom   | NetXtreme II BCM57810 10 ... | 4     | bxe        | 77F48D8337 |
| 14e4:1692 | 1028:0400 | Broadcom   | NetLink BCM57780 Gigabit ... | 4     | bge        | DB19B8D71C |
| 1969:1083 | 1458:e000 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 4     | alc        | B73E45E0DF |
| 8086:0d4f | 8086:2081 | Intel      | Ethernet Connection (10) ... | 4     | em         | A09FBE5FCC |
| 8086:109a | 15d9:109a | Intel      | 82573L Gigabit Ethernet C... | 4     | em         | 254186DAD4 |
| 8086:10c9 | 15d9:10c9 | Intel      | 82576 Gigabit Network Con... | 4     | igb        | EECEB3A84C |
| 8086:10c9 | 8086:a02f | Intel      | 82576 Gigabit Network Con... | 4     | igb        | D8B645D95D |
| 8086:10de | 1028:0276 | Intel      | 82567LM-3 Gigabit Network... | 4     | em         | FCBFBC2DFA |
| 8086:10fb | 8086:7a11 | Intel      | 82599ES 10-Gigabit SFI/SF... | 4     | ix         | EDE56150A6 |
| 8086:1502 | 103c:1495 | Intel      | 82579LM Gigabit Network C... | 4     | em         | 03D5E3FAC9 |
| 8086:150e | 8086:12a1 | Intel      | 82580 Gigabit Network Con... | 4     | igb        | 9F13074B78 |
| 8086:1521 | 1734:11ce | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 6460F775B0 |
| 8086:1521 | 1dcf:0309 | Intel      | I350 Gigabit Network Conn... | 4     | igb        | DC7D89AB64 |
| 8086:1528 | 8086:0001 | Intel      | Ethernet Controller 10-Gi... | 4     | ix         | 162F499C31 |
| 8086:1533 | 8086:0002 | Intel      | I210 Gigabit Network Conn... | 4     | igb        | 72AB5653D3 |
| 8086:1539 | 1297:4076 | Intel      | I211 Gigabit Network Conn... | 4     | igb        | BD8BEA4A6A |
| 8086:153a | 1028:05cc | Intel      | Ethernet Connection I217-LM  | 4     | em         | 1847C0AADB |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 50    |            | DB12A78352 |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 39    | iwn        | 66743A51CC |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 25    | iwm        | 53A69AA8C1 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 25    | iwm        | 85C4302966 |
| 8086:24fb | 8086:2110 | Intel      | Dual Band Wireless-AC 316... | 24    | iwm        | 62C87CF194 |
| 8086:2526 | 8086:0014 | Intel      | Wireless-AC 9260             | 22    | iwm        | F9C37F2C8D |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 19    | iwm        | E5DA7D6A12 |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 19    | iwm        | 2F1BA02130 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 15    | iwm        | 7C642E5E7D |
| 8086:08b1 | 8086:4470 | Intel      | Wireless 7260                | 13    | iwm        | F888BD5312 |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 13    | iwm        | 7660F9B6DB |
| 8086:095b | 8086:5210 | Intel      | Wireless 7265                | 13    | iwm        | AC567BD12D |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 13    | iwm        | 821C81E652 |
| 10ec:c821 | 103c:831a | Realtek... | RTL8821CE 802.11ac PCIe W... | 12    |            | 08EEA80F1C |
| 8086:24fd | 8086:0050 | Intel      | Wireless 8265 / 8275         | 12    | iwm        | 7D5F7B5033 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 11    | iwm        | 1CDBAD9DFE |
| 168c:002a | 168c:3099 | Qualcom... | AR928X Wireless Network A... | 10    | ath        | D26409D322 |
| 8086:08b1 | 8086:4070 | Intel      | Wireless 7260                | 10    | iwm        | 54F01F821D |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 10    | iwm        | 52DE90FF3D |
| 8086:31dc | 8086:02a4 | Intel      | Gemini Lake PCH CNVi WiFi    | 10    |            | 836E25BADB |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 9     | ath        | C6E717C1E9 |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 9     | ath        | 10D9E99990 |
| 168c:0036 | 1028:020c | Qualcom... | QCA9565 / AR9565 Wireless... | 9     | ath        | 0D1D75A914 |
| 8086:095a | 8086:9010 | Intel      | Wireless 7265                | 9     | iwm        | 1653EA52CE |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 9     | iwn        | A0B1FD0CA5 |
| 8086:02f0 | 8086:0074 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 8     |            | A09FBE5FCC |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 8     | iwn        | 67A6DF2B68 |
| 8086:3165 | 8086:4410 | Intel      | Wireless 3165                | 8     | iwm        | 84A1925FC9 |
| 8086:a370 | 8086:0034 | Intel      | Cannon Lake PCH CNVi WiFi    | 8     | iwm        | 3CB0E979F8 |
| 10ec:8176 | 10ec:8195 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 7     | rtwn       | 9D15DAB449 |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 7     | iwn        | ABE1869A95 |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 7     | iwn        | BDBD2D0A05 |
| 8086:08b3 | 8086:0070 | Intel      | Wireless 3160                | 7     | iwm        | E9D36A0A00 |
| 8086:24f3 | 8086:0010 | Intel      | Wireless 8260                | 7     | iwm        | 2B97986DE1 |
| 8086:4237 | 8086:1211 | Intel      | PRO/Wireless 5100 AGN [Sh... | 7     | iwn        | 981517A51A |
| 14e4:4727 | 1028:0010 | Broadcom   | BCM4313 802.11bgn Wireles... | 6     |            | C0115917D2 |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 6     | ath        | 74C3AFBF45 |
| 168c:0036 | 11ad:0642 | Qualcom... | QCA9565 / AR9565 Wireless... | 6     | ath        | C9AB1CB207 |
| 8086:08b3 | 8086:8070 | Intel      | Wireless 3160                | 6     | iwm        | 03D2A695B2 |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 6     | iwn        | 78D9A31074 |
| 10ec:c821 | 1a3b:3043 | Realtek... | RTL8821CE 802.11ac PCIe W... | 5     |            | BD8BEA4A6A |
| 14e4:432b | 106b:008d | Broadcom   | BCM4322 802.11a/b/g/n Wir... | 5     | bwn_pci    | F46146B79E |
| 14e4:4353 | 106b:0093 | Broadcom   | BCM43224 802.11a/b/g/n       | 5     | bwn_pci    | 0AB44E95DF |
| 168c:0032 | 1028:0209 | Qualcom... | AR9485 Wireless Network A... | 5     | ath        | 9B06FF01BB |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 5     | ath        | E41D9DD02E |
| 168c:0042 | 1028:1810 | Qualcom... | QCA9377 802.11ac Wireless... | 5     |            | C2D56FC369 |
| 8086:0082 | 8086:1301 | Intel      | Centrino Advanced-N 6205 ... | 5     | iwn        | 52BA4E835F |
| 8086:08b1 | 8086:4060 | Intel      | Wireless 7260                | 5     | iwm        | 6BC6C5B2BF |
| 8086:24f3 | 8086:0050 | Intel      | Wireless 8260                | 5     | iwm        | C8477DA717 |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 5     | iwm        | 9E03A76684 |
| 8086:31dc | 8086:0034 | Intel      | Gemini Lake PCH CNVi WiFi    | 5     | iwm        | 403845D763 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 5     | iwn        | 563AD840B0 |
| 14e4:4328 | 106b:0088 | Broadcom   | BCM4321 802.11a/b/g/n        | 4     | bwn_pci    | ED3684513F |
| 14e4:4331 | 106b:00d6 | Broadcom   | BCM4331 802.11a/b/g/n        | 4     | bwn_pci    | D1AAEAAD42 |
| 14e4:4331 | 14e4:4331 | Broadcom   | BCM4331 802.11a/b/g/n        | 4     | bwn_pci    | 193936B5CA |
| 168c:002d | 168c:0300 | Qualcom... | AR9227 Wireless Network A... | 4     | ath        | 9FF0FB7DF4 |
| 168c:0030 | 10cf:16a8 | Qualcom... | AR93xx Wireless Network A... | 4     | ath        | 48090193C1 |
| 168c:0032 | 1a3b:2c97 | Qualcom... | AR9485 Wireless Network A... | 4     | ath        | 9B84D1E7E6 |
| 8086:02f0 | 8086:4070 | Intel      | Comet Lake PCH-LP CNVi WiFi  | 4     |            | 80D7BF959A |
| 8086:06f0 | 8086:0074 | Intel      | Comet Lake PCH CNVi WiFi     | 4     |            | A40E426983 |
| 8086:08b2 | 8086:4270 | Intel      | Wireless 7260                | 4     | iwm        | E9155D12C7 |
| 8086:095a | 8086:5410 | Intel      | Wireless 7265                | 4     | iwm        | DCA8BA9D37 |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 4     | iwm        | 4607D1410C |
| 8086:24fd | 8086:9010 | Intel      | Wireless 8265 / 8275         | 4     | iwm        | 26C56BCF3D |
| 8086:2723 | 8086:0080 | Intel      | Wi-Fi 6 AX200                | 4     |            | BD88655975 |
| 8086:3165 | 8086:8010 | Intel      | Wireless 3165                | 4     | iwm        | 6B9C6DBD36 |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 4     | wpi        | 733C5EDB74 |
| 8086:4232 | 8086:1201 | Intel      | WiFi Link 5100               | 4     | iwn        | 50D37406DF |
| 8086:9df0 | 8086:0030 | Intel      | Cannon Point-LP CNVi [Wir... | 4     | iwm        | 6311D603FF |
| 10ec:8821 | 1043:85b4 | Realtek... | RTL8821AE 802.11ac PCIe W... | 3     |            | 4D02A33FEC |
| 10ec:8821 | 1a3b:216a | Realtek... | RTL8821AE 802.11ac PCIe W... | 3     |            | 4D84376F62 |
| 10ec:b822 | 1043:8746 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 3     |            | 15BA8E73E1 |
| 14e4:4353 | 106b:00e9 | Broadcom   | BCM43224 802.11a/b/g/n       | 3     | bwn_pci    | 0A48EE3B16 |
| 168c:002a | 1a3b:1067 | Qualcom... | AR928X Wireless Network A... | 3     | ath        | A04133B68D |
| 168c:002b | 103c:1461 | Qualcom... | AR9285 Wireless Network A... | 3     | ath        | 4FB8582DC1 |
| 168c:002b | 103c:3040 | Qualcom... | AR9285 Wireless Network A... | 3     | ath        | 258EF16ACE |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 3     | ath        | A4C1D361EB |
| 168c:0030 | 168c:3116 | Qualcom... | AR93xx Wireless Network A... | 3     | ath        | 901FAAE6DF |
| 168c:0032 | 1043:850d | Qualcom... | AR9485 Wireless Network A... | 3     | ath        | EECEB3A84C |
| 168c:0032 | 11ad:6627 | Qualcom... | AR9485 Wireless Network A... | 3     | ath        | 4368DE8D34 |
| 168c:0032 | 1a3b:1186 | Qualcom... | AR9485 Wireless Network A... | 3     | ath        | B0364FFFAF |
| 168c:0034 | 105b:e052 | Qualcom... | AR9462 Wireless Network A... | 3     | ath        | EDBF1FF1C6 |
| 168c:0036 | 11ad:0662 | Qualcom... | QCA9565 / AR9565 Wireless... | 3     | ath        | A9C4506364 |
| 168c:003c |           | Qualcom... | QCA986x/988x 802.11ac Wir... | 3     |            | 1D6CA07C5A |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 3     |            | D435C22FA0 |
| 168c:0042 | 17aa:0901 | Qualcom... | QCA9377 802.11ac Wireless... | 3     |            | 1F226262CC |
| 8086:0085 | 8086:c220 | Intel      | Centrino Advanced-N 6205 ... | 3     | iwn        | B659B95D1A |
| 8086:008a | 8086:5305 | Intel      | Centrino Wireless-N 1030 ... | 3     | iwn        | C2C592BCA8 |
| 8086:008a | 8086:5325 | Intel      | Centrino Wireless-N 1030 ... | 3     | iwn        | 87B8A38EF9 |
| 8086:06f0 | 1a56:1652 | Intel      | Comet Lake PCH CNVi WiFi     | 3     |            | 95CFF0E170 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 3     | iwn        | C52B593262 |
| 8086:0887 | 8086:4462 | Intel      | Centrino Wireless-N 2230     | 3     | iwn        | 0054EF2511 |
| 8086:088e | 8086:4460 | Intel      | Centrino Advanced-N 6235     | 3     | iwn        | 3A656DED12 |
| 8086:08b1 | 8086:c070 | Intel      | Wireless 7260                | 3     | iwm        | 23316D0F2B |
| 8086:08b2 | 8086:c260 | Intel      | Wireless 7260                | 3     | iwm        | CBFA45FE44 |
| 8086:24fd | 19e5:3e02 | Intel      | Wireless 8265 / 8275         | 3     | iwm        | F7E09652D9 |
| 8086:4227 | 8086:1011 | Intel      | PRO/Wireless 3945ABG [Gol... | 3     | wpi        | 6B81593DE9 |
| 8086:4229 | 8086:1101 | Intel      | PRO/Wireless 4965 AG or A... | 3     | iwn        | 593C12AA06 |
| 8086:4232 | 8086:1321 | Intel      | WiFi Link 5100               | 3     | iwn        | D5051EF185 |
| 8086:9df0 | 8086:4030 | Intel      | Cannon Point-LP CNVi [Wir... | 3     | iwm        | 2538B038ED |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1539 |           | Intel      | I211 Gigabit Network Conn... | 255   | igb        | FF1A657505 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 127   | re         | E5DA7D6A12 |
| 8086:157b |           | Intel      | I210 Gigabit Network Conn... | 109   | igb        | 24F3DBD372 |
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 75    | re         | 23751B05A9 |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 70    | re         | 9A7ADB8860 |
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 55    | igb        | F2C6B4AA4D |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 52    | em         | 84ABFFD607 |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 48    | re         | 338240A790 |
| 8086:10d3 |           | Intel      | 82574L Gigabit Network Co... | 40    | em         | 08EB9E54FE |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 38    | re         | EDEBE87739 |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 28    | em         | 66743A51CC |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 26    | em         | 0F001F65D2 |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 22    | re         | C44BE632D3 |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 19    | re         | 87068A97BE |
| 8086:150e | 8086:12a2 | Intel      | 82580 Gigabit Network Con... | 19    | igb        | 7C333C4F82 |
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 19    | igb        | E13854338F |
| 8086:153a | 1028:05a4 | Intel      | Ethernet Connection I217-LM  | 18    | em         | DFF16CDD8A |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 17    | rl         | E69BE420DF |
| 10ec:8168 | 103c:213d | Realtek... | RTL8111/8168/8411 PCI Exp... | 15    | re         | DE3D6DCDF5 |
| 8086:105e | 8086:135e | Intel      | 82571EB/82571GB Gigabit E... | 15    | em         | 25E20C3F35 |
| 8086:1521 | 8086:0002 | Intel      | I350 Gigabit Network Conn... | 15    | igb        | ACAD9D3480 |
| 8086:1539 | 1458:e000 | Intel      | I211 Gigabit Network Conn... | 14    | igb        | B486E670FE |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 13    | re         | AE105FB8BC |
| 8086:1f41 | 8086:1f41 | Intel      | Ethernet Connection I354     | 13    | igb        | E41D9DD02E |
| 14e4:165f | 103c:2133 | Broadcom   | NetXtreme BCM5720 Gigabit... | 12    | bge        | 39B99E57AF |
| 8086:105e | 103c:7044 | Intel      | 82571EB/82571GB Gigabit E... | 12    | em         | B621AEAAC3 |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 12    | em         | 98F39AFF26 |
| 8086:15a2 | 17aa:2226 | Intel      | Ethernet Connection (3) I... | 12    | em         | AC567BD12D |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 11    | mskc       | 65893EAA25 |
| 14e4:16b4 | 14e4:16b4 | Broadcom   | NetXtreme BCM57765 Gigabi... | 11    | bge        | AFC70D9C77 |
| 8086:105e | 8086:115e | Intel      | 82571EB/82571GB Gigabit E... | 10    | em         | B896A8E94E |
| 8086:107c | 8086:1376 | Intel      | 82541PI Gigabit Ethernet ... | 10    | em         | 783DF52955 |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 9     | re         | 57018EDD10 |
| 15b3:6750 | 15b3:0015 | Mellano... | MT26448 [ConnectX EN 10Gi... | 9     | mlx4_core  | 8A9F749148 |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 9     | em         | C887FF2917 |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 9     | em         | 821C81E652 |
| 8086:37d2 | 15d9:37d2 | Intel      | Ethernet Connection X722 ... | 9     | ixl        | 027AFA82FF |
| 14e4:1639 | 1028:0235 | Broadcom   | NetXtreme II BCM5709 Giga... | 8     | bce        | A2B6B36770 |
| 15b3:1003 | 15b3:0055 | Mellano... | MT27500 Family [ConnectX-3]  | 8     | mlx4_core  | E2D2BB7F28 |
| 8086:1502 | 1028:047e | Intel      | 82579LM Gigabit Network C... | 8     | em         | 1CDB97BFCC |
| 8086:1533 | 1849:1533 | Intel      | I210 Gigabit Network Conn... | 8     | igb        | E08A5E6F7C |
| 8086:153b | 1043:859f | Intel      | Ethernet Connection I217-V   | 8     | em         | BF53DF8658 |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | re         | 69A811CAE5 |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 7     | skc        | 65893EAA25 |
| 14e4:165f | 103c:22e8 | Broadcom   | NetXtreme BCM5720 Gigabit... | 7     | bge        | C42933F9FD |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 7     | em         | F60388BF6A |
| 8086:15b8 | 1458:e000 | Intel      | Ethernet Connection (2) I... | 7     | em         | 005F738691 |
| 8086:15bc | 1043:8672 | Intel      | Ethernet Connection (7) I... | 7     | em         | DC7D89AB64 |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 6     | re         | 4EAC97C85C |
| 1969:1091 | 1458:e000 | Qualcom... | AR8161 Gigabit Ethernet      | 6     | alc        | 1DE8945DCA |
| 8086:10fb | 8086:0006 | Intel      | 82599ES 10-Gigabit SFI/SF... | 6     | ix         | 92A93D51C5 |
| 8086:153a | 17aa:220e | Intel      | Ethernet Connection I217-LM  | 6     | em         | 7660F9B6DB |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 6     | em         | B644ED3914 |
| 8086:15a3 | 8086:2057 | Intel      | Ethernet Connection (3) I... | 6     | em         | 1653EA52CE |
| 10ec:8168 | 8086:2072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 5     | re         | 8E78A839A5 |
| 1969:1026 | 1043:8226 | Qualcom... | AR8121/AR8113/AR8114 Giga... | 5     | ale        | 22FA0D8178 |
| 8086:150e | 1734:11a8 | Intel      | 82580 Gigabit Network Con... | 5     | igb        | 56A672AF0A |
| 8086:1521 | 8086:00a2 | Intel      | I350 Gigabit Network Conn... | 5     | igb        | 7280D52EFF |
| 8086:155a | 1028:05ca | Intel      | Ethernet Connection I218-LM  | 5     | em         | 1DBD9A5CEE |
| 8086:15b7 |           | Intel      | Ethernet Connection (2) I... | 5     | em         | E39173782F |
| 10ec:8125 | 1458:e000 | Realtek... | RTL8125 2.5GbE Controller    | 4     | re         | 162F499C31 |
| 10ec:8125 | 1849:8125 | Realtek... | RTL8125 2.5GbE Controller    | 4     | re         | 05E1BDC5F5 |
| 10ec:8168 | 1028:0585 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | re         | CEC18015BA |
| 10ec:8168 | 8086:2060 | Realtek... | RTL8111/8168/8411 PCI Exp... | 4     | re         | FB2CAA1184 |
| 1425:0000 |           | Chelsio... |                              | 4     |            | 536E6B5FDF |
| 14e4:164c | 103c:7038 | Broadcom   | NetXtreme II BCM5708 Giga... | 4     | bce        | 658BE87971 |
| 8086:1528 | 15d9:1528 | Intel      | Ethernet Controller 10-Gi... | 4     | ix         | 0C0FE552AA |
| 8086:1528 | 8086:5003 | Intel      | Ethernet Controller 10-Gi... | 4     | ix         | BD63DE17B0 |
| 8086:153a | 17aa:30a6 | Intel      | Ethernet Connection I217-LM  | 4     | em         | 6390C16543 |
| 8086:1563 |           | Intel      | Ethernet Controller 10G X... | 4     | ix         | 308573E703 |
| 8086:15be | 17aa:2279 | Intel      | Ethernet Connection (6) I... | 4     | em         | 7C642E5E7D |
| 10ec:8168 | 17aa:5122 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | re         | 2F1BA02130 |
| 1425:0031 | 1425:0001 | Chelsio... | T320 10GbE Dual Port Adapter | 3     | cxgbc      | 915E62DC4A |
| 14e4:163b | 1028:02f1 | Broadcom   | NetXtreme II BCM5716 Giga... | 3     | bce        | F23BF8E1A7 |
| 14e4:165f | 1028:06a7 | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | bge        | EFE3DBF989 |
| 8086:1096 | 8086:3476 | Intel      | 80003ES2LAN Gigabit Ether... | 3     | em         | 411F470773 |
| 8086:109a | 17aa:2001 | Intel      | 82573L Gigabit Ethernet C... | 3     | em         | 5375F351A5 |
| 8086:10d3 | 103c:158a | Intel      | 82574L Gigabit Network Co... | 3     | em         | EC84D94D08 |
| 8086:10d3 | 1734:1192 | Intel      | 82574L Gigabit Network Co... | 3     | em         | 3E650BE93D |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 3     | em         | 211FE874FD |
| 8086:10f6 |           | Intel      | 82574L Gigabit Network Co... | 3     | em         | 869F003493 |
| 8086:1229 | 8086:000c | Intel      | 82557/8/9/0/1 Ethernet Pr... | 3     | fxp        | DA28E43783 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 3     | em         | 6BF1F5FE84 |
| 8086:1502 | 10f7:8338 | Intel      | 82579LM Gigabit Network C... | 3     | em         | 6BBADBA65D |
| 8086:1502 | 1734:11b7 | Intel      | 82579LM Gigabit Network C... | 3     | em         | 3E650BE93D |
| 8086:1503 |           | Intel      | 82579V Gigabit Network Co... | 3     | em         | 8698344833 |
| 8086:1570 | 8086:2063 | Intel      | Ethernet Connection I219-V   | 3     | em         | 4607D1410C |
| 10ec:8125 | 1043:879b | Realtek... | RTL8125 2.5GbE Controller    | 2     |            | 8D78068CA7 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 2     | re         | CCEC69B736 |
| 10ec:8139 | 1043:1045 | Realtek    | RTL-8100/8101L/8139 PCI F... | 2     | rl         | A04133B68D |
| 10ec:8139 | 11f6:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 2     | rl         | 3984F45545 |
| 10ec:8168 | 103c:2246 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | DA49561A8F |
| 10ec:8168 | 1462:7b89 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | 1123CB92BA |
| 10ec:8168 | 1558:1313 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | C23A22A72D |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | 1D227A9CD2 |
| 10ec:8168 | 17aa:5125 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | 7A706E46DE |
| 10ec:8168 | 8086:d613 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | E0F72BC85E |
| 11ab:4362 | 1043:8142 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 2     | mskc       | CA50169BF4 |
| 14e4:1639 | 14e4:1917 | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bce        | CF40865774 |
| 14e4:1659 | 14e4:1659 | Broadcom   | NetXtreme BCM5721 Gigabit... | 2     | bge        | F3854BA6E8 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7813 | 1022:7806 | AMD        | FCH SD Flash Controller      | 103   | sdhci_pci  | 7FFAED1505 |
| 8086:5acc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 27    | sdhci_pci  | E5DA7D6A12 |
| 8086:31cc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 23    | sdhci_pci  | 403845D763 |
| 14e4:16bc |           | Broadcom   | BCM57765/57785 SDXC/MMC C... | 12    | sdhci_pci  | AFC70D9C77 |
| 8086:31d0 | 8086:7270 | Intel      | SD Host Controller           | 12    | sdhci_pci  | 403845D763 |
| 8086:9dc4 | 8086:7270 | Intel      | 300 Series Chipset SD Hos... | 11    | sdhci_pci  | 9A399621A9 |
| 8086:9df5 | 8086:7270 | Intel      | BayHubTech Integrated SD ... | 11    | sdhci_pci  | 9A399621A9 |
| 8086:0f50 |           | Intel      | Atom Processor E3800 Seri... | 8     | sdhci_pci  | FF1A657505 |
| 8086:5ad0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 7     | sdhci_pci  | BBEEAB53DB |
| 8086:5aca | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 6     | sdhci_pci  | 0DEF6CB38E |
| 1180:0822 | 17aa:20c8 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 5     | sdhci_pci  | D223A9B1FB |
| 8086:31cc | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 5     | sdhci_pci  | 8E78A839A5 |
| 8086:5acc | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 5     | sdhci_pci  | CC0B19EF51 |
| 8086:5ad0 |           | Intel      | Celeron N3350/Pentium N42... | 5     | sdhci_pci  | CC0B19EF51 |
| 1217:8520 | 1028:05cc | O2 Micro   | SD/MMC Card Reader Contro... | 4     | sdhci_pci  | 1847C0AADB |
| 17a0:9755 | 8086:2081 | Genesys... | GL9755 SD Host Controller    | 4     | sdhci_pci  | A09FBE5FCC |
| 197b:2381 | 17aa:212d | JMicron... | Standard SD Host Controller  | 4     | sdhci_pci  | BDBD2D0A05 |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 3     | sdhci_pci  | 211FE874FD |
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 3     | sdhci_pci  | 6BF1F5FE84 |
| 8086:19db | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 3     | sdhci_pci  | FC93E31DB1 |
| 8086:9d2b | 8086:7270 | Intel      | Skylake-U/Y SCC: eMMC        | 3     | sdhci_pci  | 108EE0613E |
| 1022:7813 | 1025:0865 | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | E2B6DBFE40 |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 2     | sdhci_pci  | 1D227A9CD2 |
| 1180:0822 | 1028:024d | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 2     | sdhci_pci  | D5051EF185 |
| 1180:e822 | 1179:0001 | Ricoh      | MMC/SD Host Controller       | 2     | sdhci_pci  | 6357D0D51F |
| 1180:e823 | 10f7:8338 | Ricoh      | PCIe SDXC/MMC Host Contro... | 2     | sdhci_pci  | 04A42812BB |
| 1217:8221 | 1028:0534 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 2     | sdhci_pci  | 8D24817728 |
| 1217:8321 | 1028:049b | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 2     | sdhci_pci  | 4B4CD45AC7 |
| 1217:8520 | 1028:05bd | O2 Micro   | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | 3A656DED12 |
| 1217:8520 | 1028:05cb | O2 Micro   | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | 6EC8FD788A |
| 1217:8621 | 17aa:5072 | O2 Micro   | SD/MMC Card Reader Contro... | 2     | sdhci_pci  | 270BD22B8D |
| 17a0:9750 | 103c:8786 | Genesys... | GL9750 SD Host Controller    | 2     | sdhci_pci  | 19F307FF6D |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 2     | sdhci_pci  | 7C642E5E7D |
| 197b:2381 | 104d:9075 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 30BB4FC23C |
| 197b:2391 | 103c:17a7 | JMicron... | Standard SD Host Controller  | 2     | sdhci_pci  | 52BA4E835F |
| 8086:2294 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 2     | sdhci_pci  | 03D2A695B2 |
| 8086:31cc | 1028:080c | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | 9F4EBE949F |
| 8086:9d2b | 8086:9d2b | Intel      | Skylake-U/Y SCC: eMMC        | 2     | sdhci_pci  | 2E51DFE463 |
| 8086:9d2d | 8086:2063 | Intel      | Sunrise Point-LP Secure D... | 2     | sdhci_pci  | 55045AA9E5 |
| 8086:a375 | 103c:843f | Intel      | 300 Series Chipset Family... | 2     | sdhci_pci  | 08EEA80F1C |
| 1022:7806 | 1022:7806 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 0369617696 |
| 1022:7813 | 1022:7813 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | B5665D0DF2 |
| 1022:7813 | 1025:080d | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | CE0C079FD5 |
| 1022:7813 | 103c:22cd | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 861BDC647D |
| 104c:803c | 1025:011f | Texas I... | PCIxx12 SDA Standard Comp... | 1     | sdhci_pci  | 5D6A8A51D0 |
| 104c:803c | 1028:0252 | Texas I... | PCIxx12 SDA Standard Comp... | 1     | sdhci_pci  | 19456100CF |
| 104c:803c | 103c:30aa | Texas I... | PCIxx12 SDA Standard Comp... | 1     | sdhci_pci  | 256E0AE719 |
| 104c:803c | 1179:ff00 | Texas I... | PCIxx12 SDA Standard Comp... | 1     | sdhci_pci  | E6E0A1294C |
| 10ec:5209 | 1028:048f | Realtek... | RTS5209 PCI Express Card ... | 1     | sdhci_pci  | 67A336FAC6 |
| 10ec:5209 | 1028:05ac | Realtek... | RTS5209 PCI Express Card ... | 1     | sdhci_pci  | 0E0CDF952A |
| 10ec:5209 | 17aa:21ee | Realtek... | RTS5209 PCI Express Card ... | 1     |            | 6A96E2C5B1 |
| 1180:0822 | 1028:01bd | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 7F814A7E8D |
| 1180:0822 | 1028:01f5 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 9EE3E7CBC2 |
| 1180:0822 | 1028:022f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | D08EA3542E |
| 1180:0822 | 1028:024f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | D25DACC162 |
| 1180:0822 | 1028:0262 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 54854343E4 |
| 1180:0822 | 1028:029f | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | A4C1D361EB |
| 1180:0822 | 1028:02a2 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 0B60C1CB25 |
| 1180:0822 | 103c:1521 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 78D9A31074 |
| 1180:0822 | 103c:172a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 7968C7D2DD |
| 1180:0822 | 103c:30bb | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 733C5EDB74 |
| 1180:0822 | 103c:30cc | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 316FFB0740 |
| 1180:0822 | 103c:30e1 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 1FD927E2CD |
| 1180:0822 | 1043:1017 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | A04133B68D |
| 1180:0822 | 1043:1197 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 1F098AC490 |
| 1180:0822 | 1043:15d7 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 593C12AA06 |
| 1180:0822 | 1043:1877 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | A2EE0C9EDB |
| 1180:0822 | 104d:9035 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 4A6CA78BC0 |
| 1180:0822 | 17aa:201d | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | F08ACC6929 |
| 1180:0822 | 17aa:382a | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 6B81593DE9 |
| 1180:0822 | 1b0a:200d | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 50D37406DF |
| 1180:e822 | 103c:1471 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | C1F086E90C |
| 1180:e822 | 104d:9081 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | A69FA2363E |
| 1180:e822 | 1179:ff40 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | FEAE098542 |
| 1180:e823 | 104d:9081 | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | D8A67B4A30 |
| 1180:e823 | e823:1180 | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | 661877D8C9 |
| 1217:7120 | 1028:0273 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | EF1C0E0F2E |
| 1217:7120 | 10cf:13c6 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | AC880C0076 |
| 1217:7120 | 1179:ff50 | O2 Micro   | Integrated MMC/SD Controller | 1     | sdhci_pci  | 71FD81DF30 |
| 1217:8221 | 1028:0532 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 1     | sdhci_pci  | 696E95FC08 |
| 1217:8221 | 1028:0533 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 1     | sdhci_pci  | ABE1869A95 |
| 1217:8221 | 1028:0549 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 1     | sdhci_pci  | BEE421A110 |
| 1217:8221 | 1028:057d | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 1     | sdhci_pci  | 563AD840B0 |
| 1217:8320 | 1028:04a3 | O2 Micro   | OZ600RJ1/OZ900RJ1 SD/MMC ... | 1     | sdhci_pci  | 04FB75B4EA |
| 1217:8320 | 1028:04a4 | O2 Micro   | OZ600RJ1/OZ900RJ1 SD/MMC ... | 1     | sdhci_pci  | B6C974B8BD |
| 1217:8321 | 1028:053e | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 1     | sdhci_pci  | A7761EE829 |
| 1217:8520 | 1028:05e0 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 6CB6695DC5 |
| 1217:8520 | 1028:062c | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | DCA8BA9D37 |
| 1217:8520 | 1028:062e | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 0A8E2A2E29 |
| 1217:8520 | 10f7:8338 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 761D21F21A |
| 1217:8520 | 17aa:3800 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 1CDBAD9DFE |
| 1217:8620 | 1217:0002 | O2 Micro   | BayHubTech/O2Micro Integr... | 1     | sdhci_pci  | D563D65A91 |
| 1217:8621 | 1028:066b | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 1A49B7921A |
| 1217:8621 | 10cf:1942 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 845C584693 |
| 1217:8621 | 17aa:222c | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | BF2B792B64 |
| 1217:8621 | 17aa:3803 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | CD2AD2800E |
| 1217:8621 | 17aa:5068 | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 503378CAC9 |
| 1217:8621 | 17aa:507c | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 2DE4BC8337 |
| 14e4:16bc | 1025:0504 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 1     | sdhci_pci  | 1ADCD64182 |
| 14e4:16bc | 1025:0647 | Broadcom   | BCM57765/57785 SDXC/MMC C... | 1     | sdhci_pci  | BBBC827581 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 17    |            | 6324A2A9A9 |
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 16    | ipmi       | 82D00F440D |
| 8086:9da4 | 8086:7270 | Intel      | Cannon Point-LP SPI Contr... | 11    |            | 9A399621A9 |
| 8086:9dc5 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 11    |            | 9A399621A9 |
| 8086:9de8 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 11    |            | 9A399621A9 |
| 8086:9de9 | 8086:7270 | Intel      | Cannon Point-LP Serial IO... | 11    |            | 9A399621A9 |
| 8086:a324 | 1043:8694 | Intel      | Cannon Lake PCH SPI Contr... | 11    |            | DC7D89AB64 |
| 8086:19e0 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 10    |            | E6D9E7AF4E |
| 8086:34a4 | 8086:7270 | Intel      | Ice Lake-LP SPI Controller   | 9     |            | AE1BFCCF22 |
| 8086:34ab | 8086:7270 | Intel      | Ice Lake-LP Serial IO SPI... | 9     |            | AE1BFCCF22 |
| 8086:34e8 | 8086:7270 | Intel      | Ice Lake-LP Serial IO I2C... | 9     |            | AE1BFCCF22 |
| 8086:19e0 | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 7     |            | B6099E8EAD |
| 8086:a324 | 8086:7270 | Intel      | Cannon Lake PCH SPI Contr... | 7     |            | B486E670FE |
| 8086:9da4 | 17aa:2279 | Intel      | Cannon Point-LP SPI Contr... | 6     |            | 6311D603FF |
| 8086:9de8 | 17aa:2279 | Intel      | Cannon Point-LP Serial IO... | 6     | ig4iic     | 6311D603FF |
| 8086:9da4 | 17aa:314d | Intel      | Cannon Point-LP SPI Contr... | 5     |            | 8CE7E3A180 |
| 1425:4601 |           | Chelsio... | T420-CR Unified Wire Stor... | 4     |            | 536E6B5FDF |
| 8086:02a4 | 8086:2081 | Intel      | Comet Lake SPI (flash) Co... | 4     |            | A09FBE5FCC |
| 8086:02e8 | 8086:2081 | Intel      | Serial IO I2C Host Contro... | 4     |            | A09FBE5FCC |
| 8086:02ea | 8086:2081 | Intel      | Comet Lake PCH-LP LPSS: I... | 4     |            | A09FBE5FCC |
| 8086:22c1 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 4     |            | A1BE147141 |
| 8086:22c2 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 4     |            | A1BE147141 |
| 8086:9da4 | 1297:4076 | Intel      | Cannon Point-LP SPI Contr... | 4     |            | BD8BEA4A6A |
| 8086:9da4 | 17aa:5072 | Intel      | Cannon Point-LP SPI Contr... | 4     |            | 852A900303 |
| 8086:a1a4 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 4     |            | 027AFA82FF |
| 8086:a324 | 15d9:1b0e | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | FDDB0EDEE4 |
| 8086:a324 | 1849:a324 | Intel      | Cannon Lake PCH SPI Contr... | 4     |            | 23196AA66B |
| 8086:a368 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 4     |            | FDDB0EDEE4 |
| 8086:a369 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 4     |            | FDDB0EDEE4 |
| 10de:1adb |           | Nvidia     | TU106 USB Type-C UCSI Con... | 3     |            | 0AC6AED43B |
| 10ec:816c | 17aa:5122 | Realtek... | RTL8111xP IPMI interface     | 3     |            | 2F1BA02130 |
| 8086:02a4 | 1028:09ec | Intel      | Comet Lake SPI (flash) Co... | 3     |            | 80D7BF959A |
| 8086:02a4 | 8086:7270 | Intel      | Comet Lake SPI (flash) Co... | 3     |            | 1DCB55D9FE |
| 8086:02e8 | 1028:09ec | Intel      | Serial IO I2C Host Contro... | 3     | ig4iic     | 80D7BF959A |
| 8086:02e9 | 1028:09ec | Intel      | Comet Lake Serial IO I2C ... | 3     | ig4iic     | 80D7BF959A |
| 8086:06a4 | 1849:06a4 | Intel      | Comet Lake PCH SPI Contro... | 3     |            | 6E0891CE80 |
| 8086:a1a4 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1a4 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 1077:2532 | 103c:3262 | QLogic     | ISP2532-based 8Gb Fibre C... | 2     | isp        | D35F62BA44 |
| 10de:1aed |           | Nvidia     | TU116 USB Type-C UCSI Con... | 2     |            | F9C37F2C8D |
| 10de:1aed | 103c:8786 | Nvidia     | TU116 USB Type-C UCSI Con... | 2     |            | 19F307FF6D |
| 10ec:816c | 1043:85b5 | Realtek... | RTL8111xP IPMI interface     | 2     |            | D305B914E2 |
| 10ec:816c | 17aa:5125 | Realtek... | RTL8111xP IPMI interface     | 2     |            | 7A706E46DE |
| 10ec:816c | 17aa:5126 | Realtek... | RTL8111xP IPMI interface     | 2     |            | CD016E96EE |
| 8086:02a4 | 1558:1401 | Intel      | Comet Lake SPI (flash) Co... | 2     |            | 0BD96EF663 |
| 8086:02a4 | 17aa:5079 | Intel      | Comet Lake SPI (flash) Co... | 2     |            | 94D082C57C |
| 8086:02c5 |           | Intel      | Comet Lake Serial IO I2C ... | 2     | ig4iic     | 0BD96EF663 |
| 8086:02e8 | 1558:1401 | Intel      | Serial IO I2C Host Contro... | 2     | ig4iic     | 0BD96EF663 |
| 8086:06a4 | 17aa:3172 | Intel      | Comet Lake PCH SPI Contro... | 2     |            | 1F7035C993 |
| 8086:06a4 | 17aa:3827 | Intel      | Comet Lake PCH SPI Contro... | 2     |            | 2BE8CF963C |
| 8086:06e8 | 17aa:3803 | Intel      | Comet Lake PCH Serial IO ... | 2     | ig4iic     | 2BE8CF963C |
| 8086:06e9 | 17aa:3804 | Intel      | Comet Lake PCH Serial IO ... | 2     | ig4iic     | 2BE8CF963C |
| 8086:34a4 | 1028:097a | Intel      | Ice Lake-LP SPI Controller   | 2     |            | C2D56FC369 |
| 8086:34c5 | 1028:097a | Intel      | Ice Lake-LP Serial IO I2c... | 2     |            | C2D56FC369 |
| 8086:34e8 | 1028:097a | Intel      | Ice Lake-LP Serial IO I2C... | 2     |            | C2D56FC369 |
| 8086:34e9 | 1028:097a | Intel      | Ice Lake-LP Serial IO I2C... | 2     |            | C2D56FC369 |
| 8086:43a4 | 1043:8694 | Intel      | Tiger Lake-H SPI Controller  | 2     |            | DB12A78352 |
| 8086:43a4 | 1849:43a4 | Intel      | Tiger Lake-H SPI Controller  | 2     |            | 4427B4BA61 |
| 8086:43e8 | 1043:8694 | Intel      | Tiger Lake-H Serial IO I2... | 2     | ig4iic     | DB12A78352 |
| 8086:43e9 | 1043:8694 | Intel      | 500 Series Chipset Family... | 2     | ig4iic     | DB12A78352 |
| 8086:5ac8 |           | Intel      | Celeron N3350/Pentium N42... | 2     |            | C0517E6FF5 |
| 8086:9c61 | 1025:0a11 | Intel      | 8 Series I2C Controller #0   | 2     | ig4iic_pci | D15CAACA04 |
| 8086:9c62 | 1025:0a11 | Intel      | 8 Series I2C Controller #1   | 2     | ig4iic_pci | D15CAACA04 |
| 8086:9da4 | 1028:08b8 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | B9D1F08BCF |
| 8086:9da4 | 17aa:2292 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 4376ACCB5E |
| 8086:9da4 | 8086:2074 | Intel      | Cannon Point-LP SPI Contr... | 2     |            | 0951C73DBA |
| 8086:9dc5 | 1028:08b8 | Intel      | Cannon Point-LP Serial IO... | 2     |            | B9D1F08BCF |
| 8086:9de8 | 1028:08b8 | Intel      | Cannon Point-LP Serial IO... | 2     |            | B9D1F08BCF |
| 8086:9de8 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 2     | ig4iic     | 4376ACCB5E |
| 8086:9de9 | 1028:08b8 | Intel      | Cannon Point-LP Serial IO... | 2     |            | B9D1F08BCF |
| 8086:9de9 | 17aa:2292 | Intel      | Cannon Point-LP Serial IO... | 2     | ig4iic     | 4376ACCB5E |
| 8086:a1a4 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1a4 | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1a4 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 8086:a1a4 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a324 | 1028:084c | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 9468EEEF92 |
| 8086:a324 | 1028:088f | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | EBC09E92EB |
| 8086:a324 | 103c:843f | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 08EEA80F1C |
| 8086:a324 | 1297:4066 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | AD380CB985 |
| 8086:a324 | 1462:7b22 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | F01D541714 |
| 8086:a324 | 1590:028d | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 881D50FC9E |
| 8086:a324 | 17aa:2267 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 045A80D8BC |
| 8086:a324 | 17aa:312d | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 5E6FBBD1EE |
| 8086:a324 | 17aa:3827 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | DCE3BA8C99 |
| 8086:a324 | 8086:2089 | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | 1133FFB4F2 |
| 8086:a368 | 103c:843f | Intel      | Cannon Lake PCH Serial IO... | 2     | ig4iic     | 08EEA80F1C |
| 8086:a368 | 17aa:2267 | Intel      | Cannon Lake PCH Serial IO... | 2     | ig4iic     | 045A80D8BC |
| 8086:a368 | 17aa:3803 | Intel      | Cannon Lake PCH Serial IO... | 2     | ig4iic     | DCE3BA8C99 |
| 8086:a368 | 8086:2089 | Intel      | Cannon Lake PCH Serial IO... | 2     |            | 1133FFB4F2 |
| 8086:a369 | 103c:843f | Intel      | Cannon Lake PCH Serial IO... | 2     | ig4iic     | 08EEA80F1C |
| 8086:a369 | 17aa:3804 | Intel      | Cannon Lake PCH Serial IO... | 2     | ig4iic     | DCE3BA8C99 |
| 8086:a369 | 8086:2089 | Intel      | Cannon Lake PCH Serial IO... | 2     |            | 1133FFB4F2 |
| 1077:2432 | 103c:7040 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     |            | 7CC48A8D08 |
| 1077:2432 | 1077:0138 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     | isp        | 73D43A5525 |
| 1077:2532 | 103c:3263 | QLogic     | ISP2532-based 8Gb Fibre C... | 1     | isp        | F8A95C37D5 |
| 10de:1ad7 | 1462:3715 | Nvidia     | TU102 USB Type-C UCSI Con... | 1     |            | DAB7165B99 |
| 10de:1ad9 | 103c:372b | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | ADE306695D |
| 10de:1ad9 | 1462:12b8 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | A40E426983 |
| 10de:1ad9 | 1462:12bc | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | FEA3CDB5D1 |
| 10de:1ad9 | 1462:3721 | Nvidia     | TU104 USB Type-C UCSI Con... | 1     |            | C00D9E9C92 |

### Signal processing (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d31 | 8086:7270 | Intel      | Sunrise Point-LP Thermal ... | 65    | pchtherm   | 80122A9F4A |
| 8086:9d27 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 34    |            | 80122A9F4A |
| 8086:9d60 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 33    | ig4iic     | 80122A9F4A |
| 8086:9d61 | 8086:7270 | Intel      | Sunrise Point-LP Serial I... | 33    | ig4iic     | 80122A9F4A |
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:31b4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    |            | 403845D763 |
| 8086:31b6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    |            | 403845D763 |
| 8086:31b8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 26    |            | 403845D763 |
| 8086:204d |           | Intel      | Sky Lake-E M3KTI Registers   | 23    |            | 6460F775B0 |
| 8086:2015 |           | Intel      | Sky Lake-E Ubox Registers    | 20    |            | C4862C598A |
| 8086:31ba | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 20    |            | 5A1A372153 |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 19    | ig4iic     | 800CE2AF1D |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 17    | ig4iic     | 800CE2AF1D |
| 8086:2058 |           | Intel      | Sky Lake-E KTI 0             | 15    |            | 6460F775B0 |
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 15    |            | 5ACC629D2E |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 15    |            | 5ACC629D2E |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 15    |            | 5ACC629D2E |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:318c | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 14    |            | 403845D763 |
| 8086:5a8c |           | Intel      | Atom/Celeron/Pentium Dyna... | 14    |            | E5DA7D6A12 |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | ig4iic     | 800CE2AF1D |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | ig4iic     | 800CE2AF1D |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 14    | ig4iic     | 800CE2AF1D |
| 8086:9d31 | 8086:9d31 | Intel      | Sunrise Point-LP Thermal ... | 14    |            | 045DFAD837 |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 13    |            | BBEEAB53DB |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 13    |            | BBEEAB53DB |
| 8086:1903 | 8086:7270 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 12    |            | 9A399621A9 |
| 8086:204c |           | Intel      | Sky Lake-E M3KTI Registers   | 12    |            | C4862C598A |
| 8086:31c2 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 12    |            | 403845D763 |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 12    | ig4iic     | 800CE2AF1D |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 12    | ig4iic     | 800CE2AF1D |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 12    | ig4iic     | 800CE2AF1D |
| 8086:8c24 | 15d9:086d | Intel      | 8 Series Chipset Family T... | 12    |            | 6A22DA5C5D |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    |            | BBEEAB53DB |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 11    |            | BBEEAB53DB |
| 8086:8c24 | 15d9:0921 | Intel      | 8 Series Chipset Family T... | 11    |            | F2C6B4AA4D |
| 8086:9df9 | 8086:7270 | Intel      | Cannon Point-LP Thermal C... | 11    |            | 9A399621A9 |
| 8086:1903 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 10    |            | CC7F385529 |
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 10    |            | C887FF2917 |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 9     |            | 5ACC629D2E |
| 8086:0e30 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     |            | 8F4B51DABD |
| 8086:0e34 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     |            | 8F4B51DABD |
| 8086:0e36 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     |            | 8F4B51DABD |
| 8086:2088 |           | Intel      | Sky Lake-E DDRIO Registers   | 8     |            | 6460F775B0 |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 5ACC629D2E |
| 8086:a131 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 8     | pchtherm   | 9A0602D408 |
| 8086:318c | 1849:318c | Intel      | Celeron/Pentium Silver Pr... | 7     |            | 08D15AE852 |
| 8086:31bc | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     |            | 403845D763 |
| 8086:31be | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     |            | 403845D763 |
| 8086:31c0 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     |            | 403845D763 |
| 8086:31ee | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 7     |            | 403845D763 |
| 8086:9d60 | 8086:9d60 | Intel      | Sunrise Point-LP Serial I... | 7     |            | 994B94B7F5 |
| 8086:9d61 | 8086:9d61 | Intel      | Sunrise Point-LP Serial I... | 7     |            | 994B94B7F5 |
| 8086:1903 | 17aa:2279 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 6     |            | 6311D603FF |
| 8086:31c4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 6     |            | 836E25BADB |
| 8086:31c6 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 6     |            | 836E25BADB |
| 8086:9ca4 | 17aa:2226 | Intel      | Wildcat Point-LP Thermal ... | 6     | pchtherm   | 107AC19795 |
| 8086:9ca4 | 17aa:5034 | Intel      | Wildcat Point-LP Thermal ... | 6     | pchtherm   | AC567BD12D |
| 8086:9d31 | 17aa:2238 | Intel      | Sunrise Point-LP Thermal ... | 6     |            | 821C81E652 |
| 8086:9df9 | 17aa:2279 | Intel      | Cannon Point-LP Thermal C... | 6     |            | 6311D603FF |
| 8086:a131 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 6     |            | 9D69197550 |
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 6     |            | DB95470F69 |
| 8086:a2b1 | 1849:a2b1 | Intel      | 200 Series PCH Thermal Su... | 6     |            | 1C438D977E |
| 8086:a379 | 1458:8888 | Intel      | Cannon Lake PCH Thermal C... | 6     |            | B486E670FE |
| 8086:1903 | 17aa:314d | Intel      | Xeon E3-1200 v5/E3-1500 v... | 5     |            | 8CE7E3A180 |
| 8086:5ac2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 5     |            | BC138C0580 |
| 8086:5ac6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 5     |            | BC138C0580 |
| 8086:9d31 | 17aa:5062 | Intel      | Sunrise Point-LP Thermal ... | 5     | pchtherm   | 88C27E65D7 |
| 8086:9d60 | 17aa:5062 | Intel      | Sunrise Point-LP Serial I... | 5     | ig4iic     | 88C27E65D7 |
| 8086:9d61 | 17aa:5062 | Intel      | Sunrise Point-LP Serial I... | 5     | ig4iic     | 88C27E65D7 |
| 8086:9df9 | 17aa:314d | Intel      | Cannon Point-LP Thermal C... | 5     |            | 8CE7E3A180 |
| 8086:a131 | 1849:a131 | Intel      | 100 Series/C230 Series Ch... | 5     | pchtherm   | E2D2BB7F28 |
| 8086:02f9 | 8086:2081 | Intel      | Comet Lake Thermal Subsytem  | 4     |            | A09FBE5FCC |
| 8086:1903 | 1297:4076 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     |            | BD8BEA4A6A |
| 8086:1903 | 17aa:5072 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 4     |            | 852A900303 |
| 8086:3b32 |           | Intel      | 5 Series/3400 Series Chip... | 4     |            | 0AB44E95DF |
| 8086:3c43 | 1028:04f7 | Intel      | Xeon E5/Core i7 Ring to P... | 4     |            | 77475B714A |
| 8086:3c44 | 1028:04f7 | Intel      | Xeon E5/Core i7 Ring to Q... | 4     |            | 77475B714A |
| 8086:3c46 | 1028:04f7 | Intel      | Xeon E5/Core i7 Processor... | 4     |            | 77475B714A |
| 8086:3ce6 | 1028:04f7 | Intel      | Xeon E5/Core i7 QuickPath... | 4     |            | 77475B714A |
| 8086:5ac4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     |            | BC138C0580 |
| 8086:8c24 | 1734:11ea | Intel      | 8 Series Chipset Family T... | 4     |            | 195358C8A7 |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 4     | pchtherm   | 2B97986DE1 |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 4     | ig4iic     | 2B97986DE1 |
| 8086:9df9 | 1297:4076 | Intel      | Cannon Point-LP Thermal C... | 4     |            | BD8BEA4A6A |
| 8086:9df9 | 17aa:5072 | Intel      | Cannon Point-LP Thermal C... | 4     | pchtherm   | 852A900303 |
| 8086:a1b1 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 4     |            | 027AFA82FF |
| 8086:a379 | 15d9:1b0e | Intel      | Cannon Lake PCH Thermal C... | 4     |            | FDDB0EDEE4 |
| 8086:a379 | 1849:a379 | Intel      | Cannon Lake PCH Thermal C... | 4     |            | 23196AA66B |
| 8086:0103 | 10f7:8338 | Intel      | Core i7/i5/i3 Thermal Man... | 3     |            | 6BBADBA65D |
| 8086:0153 |           | Intel      | 3rd Gen Core Processor Th... | 3     |            | 661877D8C9 |
| 8086:02f9 | 1028:09ec | Intel      | Comet Lake Thermal Subsytem  | 3     |            | 80D7BF959A |
| 8086:02f9 | 8086:7270 | Intel      | Comet Lake Thermal Subsytem  | 3     |            | 1DCB55D9FE |
| 8086:06f9 | 1849:06f9 | Intel      | Comet Lake PCH Thermal Co... | 3     |            | 6E0891CE80 |
| 8086:0a03 |           | Intel      | Haswell-ULT Thermal Subsy... | 3     |            | 5A128DD6A3 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 111   | intsmb     | 7FFAED1505 |
| 8086:9d23 | 8086:7270 | Intel      | Sunrise Point-LP SMBus       | 95    | ichsmb     | 8FAE98E5A6 |
| 8086:0f12 | 8086:0f12 | Intel      | Atom Processor E3800 Seri... | 71    | ichsmb     | FF1A657505 |
| 8086:2292 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 65    |            | 3E773132B3 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    |            | E5DA7D6A12 |
| 8086:31d4 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 33    |            | 403845D763 |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 29    | intsmb     | 9A7ADB8860 |
| 8086:9c22 | 8086:7270 | Intel      | 8 Series SMBus Controller    | 26    |            | 95A281E2F8 |
| 8086:9ca2 | 8086:7270 | Intel      | Wildcat Point-LP SMBus Co... | 25    |            | CD60E38216 |
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 23    | intsmb     | 162F499C31 |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 22    | intsmb     | C42933F9FD |
| 1022:790b | 1043:87c0 | AMD        | FCH SMBus Controller         | 21    | intsmb     | 10D9E99990 |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 21    |            | 8D59B379FD |
| 8086:1c22 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 20    | ichsmb     | 9301BD0E0F |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 20    | ichsmb     | BF53DF8658 |
| 1022:790b | 1849:ffff | AMD        | FCH SMBus Controller         | 19    | intsmb     | BD63DE17B0 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 18    | intsmb     | B621AEAAC3 |
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 18    |            | C44BE632D3 |
| 8086:1f3c | 8086:7270 | Intel      | Atom processor C2000 PCU ... | 18    |            | 7E6BEE8355 |
| 1022:780b | 103c:213d | AMD        | FCH SMBus Controller         | 17    | intsmb     | DE3D6DCDF5 |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 17    | intsmb     | EDEBE87739 |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 17    |            | A379C24586 |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 17    | ichsmb     | 65893EAA25 |
| 8086:a123 | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 17    |            | 7F9CDC62A2 |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 15    | intsmb     | 1C30F7523F |
| 8086:1c22 | 15d9:0624 | Intel      | 6 Series/C200 Series Chip... | 15    |            | 08EB9E54FE |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 15    | ichsmb     | EECEB3A84C |
| 8086:5ad4 | 1849:5ad4 | Intel      | Celeron N3350/Pentium N42... | 15    |            | C9218EE21D |
| 8086:1c22 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 14    | ichsmb     | 66743A51CC |
| 8086:8c22 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 14    |            | B5FE536096 |
| 8086:9d23 | 8086:9d23 | Intel      | Sunrise Point-LP SMBus       | 14    |            | 045DFAD837 |
| 8086:0f12 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 12    |            | 1C67BF34D5 |
| 8086:8c22 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 12    |            | 09BA719AA7 |
| 8086:8c22 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 12    |            | 6A22DA5C5D |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 11    | ichsmb     | B73E45E0DF |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 11    |            | 193936B5CA |
| 8086:283e | 8086:283e | Intel      | 82801H (ICH8 Family) SMBu... | 11    |            | 901FAAE6DF |
| 8086:2930 | 17aa:20f9 | Intel      | 82801I (ICH9 Family) SMBu... | 11    |            | BDBD2D0A05 |
| 8086:8c22 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    |            | F2C6B4AA4D |
| 8086:8c22 | 8086:8c22 | Intel      | 8 Series/C220 Series Chip... | 11    |            | FE8DC15588 |
| 8086:9da3 | 8086:7270 | Intel      | Cannon Point-LP SMBus Con... | 11    |            | 9A399621A9 |
| 8086:a323 | 1043:8694 | Intel      | Cannon Lake PCH SMBus Con... | 11    |            | DC7D89AB64 |
| 8086:19df | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 10    |            | E6D9E7AF4E |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 10    | ichsmb     | C887FF2917 |
| 8086:8ca2 | 1458:5001 | Intel      | 9 Series Chipset Family S... | 10    | ichsmb     | 1DE8945DCA |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 9     | intsmb     | 3E474F93CF |
| 10de:0aa2 | 10de:cb79 | Nvidia     | MCP79 SMBus                  | 9     |            | F46146B79E |
| 8086:2292 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 9     |            | CE87A10F79 |
| 8086:34a3 | 8086:7270 | Intel      | Ice Lake-LP SMBus Controller | 9     |            | AE1BFCCF22 |
| 8086:8c22 | 1458:5001 | Intel      | 8 Series/C220 Series Chip... | 9     | ichsmb     | 331DA3091C |
| 8086:8ca2 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 9     | ichsmb     | D8ECC7077A |
| 8086:a2a3 | 1043:8694 | Intel      | 200 Series/Z370 Chipset F... | 9     |            | 15BA8E73E1 |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 8     | intsmb     | E69BE420DF |
| 1022:780b | 103c:8103 | AMD        | FCH SMBus Controller         | 8     | intsmb     | 93A434D951 |
| 8086:0f12 | 1849:0f12 | Intel      | Atom Processor E3800 Seri... | 8     | ichsmb     | 62E1C023ED |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 8     | ichsmb     | DC29D714D9 |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 8     | ichsmb     | 120665D4D3 |
| 8086:1e22 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 8     | ichsmb     | 0F001F65D2 |
| 8086:1e22 | 8086:1e22 | Intel      | 7 Series/C216 Chipset Fam... | 8     | ichsmb     | 424ADD8B03 |
| 8086:a123 | 1734:121d | Intel      | 100 Series/C230 Series Ch... | 8     | ichsmb     | 9A0602D408 |
| 1002:4385 | 1022:1510 | AMD        | SBx00 SMBus Controller       | 7     | intsmb     | C1DE9809DD |
| 8086:19df | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 7     |            | B6099E8EAD |
| 8086:1e22 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 7     |            | 7C333C4F82 |
| 8086:1e22 | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 7     | ichsmb     | AB3FC66A9E |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 7     |            | AB871769F0 |
| 8086:1e22 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 7     | ichsmb     | AFC70D9C77 |
| 8086:2930 | 15d9:060a | Intel      | 82801I (ICH9 Family) SMBu... | 7     | ichsmb     | 84ABFFD607 |
| 8086:31d4 | 1849:31d4 | Intel      | Celeron/Pentium Silver Pr... | 7     |            | 08D15AE852 |
| 8086:a2a3 | 1458:5001 | Intel      | 200 Series/Z370 Chipset F... | 7     |            | B77CEEED88 |
| 1022:780b | 1734:1202 | AMD        | FCH SMBus Controller         | 6     | intsmb     | CDF0C1C8CE |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 6     |            | 338240A790 |
| 8086:283e | 17aa:20a9 | Intel      | 82801H (ICH8 Family) SMBu... | 6     | ichsmb     | D223A9B1FB |
| 8086:8c22 | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 6     |            | 56A672AF0A |
| 8086:8c22 | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 6     |            | 2806E1E8CF |
| 8086:8c22 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 6     | ichsmb     | 7660F9B6DB |
| 8086:8c22 | 17aa:3098 | Intel      | 8 Series/C220 Series Chip... | 6     |            | B7EA8547CE |
| 8086:9ca2 | 17aa:2226 | Intel      | Wildcat Point-LP SMBus Co... | 6     | ichsmb     | 107AC19795 |
| 8086:9ca2 | 17aa:5034 | Intel      | Wildcat Point-LP SMBus Co... | 6     | ichsmb     | AC567BD12D |
| 8086:9ca2 | 8086:2057 | Intel      | Wildcat Point-LP SMBus Co... | 6     | ichsmb     | 1653EA52CE |
| 8086:9d23 | 17aa:2238 | Intel      | Sunrise Point-LP SMBus       | 6     | ichsmb     | 821C81E652 |
| 8086:9da3 | 17aa:2279 | Intel      | Cannon Point-LP SMBus Con... | 6     |            | 6311D603FF |
| 8086:a123 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 6     |            | 9D69197550 |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 6     |            | DB95470F69 |
| 8086:a2a3 | 1849:a2a3 | Intel      | 200 Series/Z370 Chipset F... | 6     |            | 1C438D977E |
| 8086:a323 | 1458:5001 | Intel      | Cannon Lake PCH SMBus Con... | 6     | ichsmb     | B486E670FE |
| 1022:780b | 1849:780b | AMD        | FCH SMBus Controller         | 5     | intsmb     | 917EE44FE9 |
| 8086:1c22 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 5     |            | BEF38BD379 |
| 8086:1c22 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 5     |            | E9604E52C7 |
| 8086:1c22 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 5     | ichsmb     | 49DACEE7D0 |
| 8086:1c22 | 1849:1c22 | Intel      | 6 Series/C200 Series Chip... | 5     |            | D1580FA078 |
| 8086:1e22 | 1028:052c | Intel      | 7 Series/C216 Chipset Fam... | 5     |            | 351B13FD3B |
| 8086:31d4 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 5     |            | 8E78A839A5 |
| 8086:3a30 | 1014:3a30 | Intel      | 82801JI (ICH10 Family) SM... | 5     |            | 5F9F2C2232 |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 5     | ichsmb     | 24502C7F7B |
| 8086:5ad4 | 19da:b325 | Intel      | Celeron N3350/Pentium N42... | 5     |            | CC0B19EF51 |
| 8086:8c22 | 1849:8c22 | Intel      | 8 Series/C220 Series Chip... | 5     |            | 7E86969DCB |
| 8086:8c22 | 8086:7270 | Intel      | 8 Series/C220 Series Chip... | 5     | ichsmb     | 1C9FEEF8E7 |
| 8086:9c22 | 1028:05ca | Intel      | 8 Series SMBus Controller    | 5     |            | 1DBD9A5CEE |
| 8086:9c22 | 1028:0651 | Intel      | 8 Series SMBus Controller    | 5     |            | 0D1D75A914 |
| 8086:9d23 | 17aa:5062 | Intel      | Sunrise Point-LP SMBus       | 5     | ichsmb     | 88C27E65D7 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2284 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 61    | hdac       | 3E773132B3 |
| 8086:9d71 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 45    | hdac       | 80122A9F4A |
| 8086:0f04 | 8086:0f04 | Intel      | Atom Processor Z36xxx/Z37... | 40    | hdac       | F2C0EB9D31 |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 26    | hdac       | 9A7ADB8860 |
| 8086:0a0c | 8086:0a0c | Intel      | Haswell-ULT HD Audio Cont... | 25    | hdac       | 95A281E2F8 |
| 8086:3198 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 25    | hdac       | 5A1A372153 |
| 8086:9c20 | 8086:7270 | Intel      | 8 Series HD Audio Controller | 25    | hdac       | 95A281E2F8 |
| 8086:160c | 8086:160c | Intel      | Broadwell-U Audio Controller | 23    | hdac       | CD60E38216 |
| 8086:9ca0 | 8086:7270 | Intel      | Wildcat Point-LP High Def... | 23    | hdac       | CD60E38216 |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 20    | hdac       | 308573E703 |
| 8086:0f04 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 19    | hdac       | FF1A657505 |
| 1002:9840 | 103c:213d | AMD        | Kabini HDMI/DP Audio         | 17    | hdac       | DE3D6DCDF5 |
| 8086:0c0c | 8086:2010 | Intel      | Xeon E3-1200 v3/4th Gen C... | 17    | hdac       | E9D36A0A00 |
| 8086:5a98 |           | Intel      | Celeron N3350/Pentium N42... | 16    | hdac       | E5DA7D6A12 |
| 8086:5a98 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 16    | hdac       | 65DD81D59E |
| 1022:780d | 103c:213d | AMD        | FCH Azalia Controller        | 15    | hdac       | DE3D6DCDF5 |
| 8086:0c0c | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 14    | hdac       | BF53DF8658 |
| 8086:1c20 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 14    | hdac       | 66743A51CC |
| 8086:8c20 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 14    | hdac       | B5FE536096 |
| 8086:0c0c | 1028:05a4 | Intel      | Xeon E3-1200 v3/4th Gen C... | 12    | hdac       | B5FE536096 |
| 8086:0c0c | 1028:0612 | Intel      | Xeon E3-1200 v3/4th Gen C... | 11    | hdac       | 09BA719AA7 |
| 8086:293e | 17aa:20f2 | Intel      | 82801I (ICH9 Family) HD A... | 11    | hdac       | BDBD2D0A05 |
| 8086:9dc8 | 8086:7270 | Intel      | Cannon Point-LP High Defi... | 11    | hdac       | 9A399621A9 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 10    | hdac       | 193936B5CA |
| 8086:8c20 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 10    | hdac       | 09BA719AA7 |
| 8086:8c20 | 1043:8576 | Intel      | 8 Series/C220 Series Chip... | 10    | hdac       | AE105FB8BC |
| 8086:9d70 | 8086:7270 | Intel      | Sunrise Point-LP HD Audio    | 10    | hdac       | 6E4A978A48 |
| 10de:0ac0 | 10de:cb79 | Nvidia     | MCP79 High Definition Audio  | 9     | hdac       | F46146B79E |
| 8086:34c8 | 10ec:119e | Intel      | Ice Lake-LP Smart Sound T... | 9     | hdac       | AE1BFCCF22 |
| 1002:1308 | 103c:8103 | AMD        | Kaveri HDMI/DP Audio Cont... | 8     | hdac       | 93A434D951 |
| 1022:1487 | 1043:8797 | AMD        | Starship/Matisse HD Audio... | 8     | hdac       | C6A1C1FA15 |
| 8086:0c0c | 8086:0c0c | Intel      | Xeon E3-1200 v3/4th Gen C... | 8     | hdac       | CD0467031A |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 8     | hdac       | DC29D714D9 |
| 8086:1e20 | 17aa:21f3 | Intel      | 7 Series/C216 Chipset Fam... | 8     | hdac       | 0F001F65D2 |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 8     | hdac       | C887FF2917 |
| 8086:8c20 | 1458:a002 | Intel      | 8 Series/C220 Series Chip... | 8     | hdac       | 331DA3091C |
| 1002:aaf0 | 1458:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 7     | hdac       | 87068A97BE |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 7     | hdac       | 5B71C5420F |
| 1022:780d | 103c:8103 | AMD        | FCH Azalia Controller        | 7     | hdac       | 93A434D951 |
| 8086:1c20 | 1043:8445 | Intel      | 6 Series/C200 Series Chip... | 7     | hdac       | 273E379D9F |
| 8086:1e20 | 103c:3397 | Intel      | 7 Series/C216 Chipset Fam... | 7     | hdac       | AB3FC66A9E |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 7     | hdac       | AB871769F0 |
| 8086:1e20 | 8086:1e20 | Intel      | 7 Series/C216 Chipset Fam... | 7     | hdac       | 424ADD8B03 |
| 8086:1e20 | 8086:7270 | Intel      | 7 Series/C216 Chipset Fam... | 7     | hdac       | AFC70D9C77 |
| 8086:8ca0 | 1458:a182 | Intel      | 9 Series Chipset Family H... | 7     | hdac       | 1DE8945DCA |
| 8086:a2f0 | 1458:a182 | Intel      | 200 Series PCH HD Audio      | 7     | hdac       | B77CEEED88 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 6     | hdac       | E69BE420DF |
| 1002:9840 | 1734:1202 | AMD        | Kabini HDMI/DP Audio         | 6     | hdac       | CDF0C1C8CE |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 6     | hdac       | 431EAAC648 |
| 1022:1457 | 1849:6893 | AMD        | Family 17h (Models 00h-0f... | 6     | hdac       | 950B4FBDC2 |
| 1022:780d | 1022:780d | AMD        | FCH Azalia Controller        | 6     | hdac       | 4433B8842F |
| 8086:0c0c | 103c:1998 | Intel      | Xeon E3-1200 v3/4th Gen C... | 6     | hdac       | 2806E1E8CF |
| 8086:0c0c | 17aa:220e | Intel      | Xeon E3-1200 v3/4th Gen C... | 6     | hdac       | 7660F9B6DB |
| 8086:0c0c | 17aa:3098 | Intel      | Xeon E3-1200 v3/4th Gen C... | 6     | hdac       | B7EA8547CE |
| 8086:160c | 17aa:2226 | Intel      | Broadwell-U Audio Controller | 6     | hdac       | 107AC19795 |
| 8086:160c | 17aa:5034 | Intel      | Broadwell-U Audio Controller | 6     | hdac       | AC567BD12D |
| 8086:1e20 | 1028:0577 | Intel      | 7 Series/C216 Chipset Fam... | 6     | hdac       | 7C333C4F82 |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 6     | hdac       | A379C24586 |
| 8086:284b | 17aa:20ac | Intel      | 82801H (ICH8 Family) HD A... | 6     | hdac       | D223A9B1FB |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 6     | hdac       | 22FA0D8178 |
| 8086:8c20 | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 6     | hdac       | 56A672AF0A |
| 8086:8c20 | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 6     | hdac       | 2806E1E8CF |
| 8086:8c20 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 6     | hdac       | 7660F9B6DB |
| 8086:8c20 | 17aa:3098 | Intel      | 8 Series/C220 Series Chip... | 6     | hdac       | B7EA8547CE |
| 8086:9ca0 | 17aa:2226 | Intel      | Wildcat Point-LP High Def... | 6     | hdac       | 107AC19795 |
| 8086:9d70 | 17aa:2238 | Intel      | Sunrise Point-LP HD Audio    | 6     | hdac       | 821C81E652 |
| 8086:9dc8 | 17aa:2279 | Intel      | Cannon Point-LP High Defi... | 6     | hdac       | 6311D603FF |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 5     | hdac       | DAA7AFC688 |
| 1002:9840 | 1002:9840 | AMD        | Kabini HDMI/DP Audio         | 5     | hdac       | C546E561B5 |
| 1002:aaf0 | 1462:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 5     | hdac       | A87473149B |
| 1002:ab38 | 1002:ab38 | AMD        | Navi 10 HDMI Audio           | 5     | hdac       | ADB0E59AA1 |
| 1022:1457 | 1043:86c7 | AMD        | Family 17h (Models 00h-0f... | 5     | hdac       | EDEBE87739 |
| 10de:0e0f | 19da:5360 | Nvidia     | GK208 HDMI/DP Audio Contr... | 5     | hdac       | BD63DE17B0 |
| 8086:0a0c | 1028:05ca | Intel      | Haswell-ULT HD Audio Cont... | 5     | hdac       | 1DBD9A5CEE |
| 8086:0a0c | 1028:0651 | Intel      | Haswell-ULT HD Audio Cont... | 5     | hdac       | 0D1D75A914 |
| 8086:0c0c | 103c:18e7 | Intel      | Xeon E3-1200 v3/4th Gen C... | 5     | hdac       | 56A672AF0A |
| 8086:160c | 8086:2057 | Intel      | Broadwell-U Audio Controller | 5     | hdac       | 1653EA52CE |
| 8086:1c20 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 5     | hdac       | BEF38BD379 |
| 8086:1c20 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 5     | hdac       | E9604E52C7 |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 5     | hdac       | 6BD5EA83B3 |
| 8086:1c20 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 5     | hdac       | 49DACEE7D0 |
| 8086:284b | 8086:284b | Intel      | 82801H (ICH8 Family) HD A... | 5     | hdac       | 901FAAE6DF |
| 8086:3198 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 5     | hdac       | 8E78A839A5 |
| 8086:9c20 | 1028:05ca | Intel      | 8 Series HD Audio Controller | 5     | hdac       | 1DBD9A5CEE |
| 8086:9c20 | 1028:0651 | Intel      | 8 Series HD Audio Controller | 5     | hdac       | 0D1D75A914 |
| 8086:9ca0 | 8086:2057 | Intel      | Wildcat Point-LP High Def... | 5     | hdac       | 1653EA52CE |
| 8086:9d71 | 1111:1111 | Intel      | Sunrise Point-LP HD Audio    | 5     | hdac       | 045DFAD837 |
| 8086:a170 | 1043:86c7 | Intel      | 100 Series/C230 Series Ch... | 5     | hdac       | E29CA39BAF |
| 8086:a170 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 5     | hdac       | DB95470F69 |
| 8086:a348 | 1043:86c7 | Intel      | Cannon Lake PCH cAVS         | 5     | hdac       | CB97F230B8 |
| 1002:15de | 1043:876b | AMD        | Raven/Raven2/Fenghuang HD... | 4     | hdac       | E13854338F |
| 1002:1637 | 1002:1637 | AMD        | Renoir Radeon High Defini... | 4     | hdac       | D305B914E2 |
| 1002:4383 | 1043:84fb | AMD        | SBx00 Azalia (Intel HDA)     | 4     | hdac       | A03927CC2E |
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 4     | hdac       | 47D17E6983 |
| 1002:aa68 | 174b:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 4     | hdac       | 68D5D3C6CD |
| 1002:aa98 | 174b:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 4     | hdac       | CEC3CB521D |
| 1002:aab0 | 1028:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 4     |            | BC3913FEAD |
| 1002:aae0 | 1da2:aae0 | AMD        | Baffin HDMI/DP Audio [Rad... | 4     | hdac       | F035AAB141 |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 4     | hdac       | AC6B550FF4 |
| 1022:1457 | 1022:c950 | AMD        | Family 17h (Models 00h-0f... | 4     | hdac       | F4A0F0941B |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 3     |            | 6BF1F5FE84 |
| 1217:8331 | 1028:049b | O2 Micro   | O2 Flash Memory Card         | 2     |            | 4B4CD45AC7 |
| 1283:8211 | 1283:8211 | Integra... | ITE 8211F Single Channel ... | 2     | atapci     | BA1D9A51C2 |
| 104c:803b | 1025:011f | Texas I... | PCIxx12 Flash Media Contr... | 1     |            | 5D6A8A51D0 |
| 104c:803b | 103c:30aa | Texas I... | PCIxx12 Flash Media Contr... | 1     |            | 256E0AE719 |
| 104c:803b | 104d:81e6 | Texas I... | PCIxx12 Flash Media Contr... | 1     |            | ACE534D784 |
| 104c:803b | 104d:9016 | Texas I... | PCIxx12 Flash Media Contr... | 1     |            | B417DF513F |
| 104c:803b | 1179:ff00 | Texas I... | PCIxx12 Flash Media Contr... | 1     |            | E6E0A1294C |
| 104c:ac8f | 104d:8190 | Texas I... | PCI7420/7620 SD/MS-Pro Co... | 1     |            | F2F3923EA6 |
| 105a:4d30 | 105a:4d33 | Promise... | PDC20267 (FastTrak100/Ult... | 1     | atapci     | D99AE1AAD1 |
| 105a:4d69 | 105a:4d68 | Promise... | 20269                        | 1     | atapci     | D2A09126C0 |
| 1217:7130 | 1028:0273 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | EF1C0E0F2E |
| 1217:7130 | 10cf:13c6 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | AC880C0076 |
| 1217:7130 | 1179:ff50 | O2 Micro   | Integrated MS/xD Controller  | 1     |            | 71FD81DF30 |
| 1217:8330 | 1028:04a3 | O2 Micro   | OZ600 MS/xD Controller       | 1     |            | 04FB75B4EA |
| 1217:8330 | 1028:04a4 | O2 Micro   | OZ600 MS/xD Controller       | 1     |            | B6C974B8BD |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d03 | 8086:7270 | Intel      | Sunrise Point-LP SATA Con... | 92    | ahci       | 8FAE98E5A6 |
| 8086:0f23 | 8086:0f23 | Intel      | Atom Processor E3800 Seri... | 71    | ahci       | FF1A657505 |
| 1022:7801 | 1022:7801 | AMD        | FCH SATA Controller [AHCI... | 68    | ahci       | 7FFAED1505 |
| 8086:22a3 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 65    | ahci       | 3E773132B3 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 55    | ahci       | 4AC6C9B3EB |
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 50    | ahci       | EDEBE87739 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    | ahci       | E5DA7D6A12 |
| 8086:31e3 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 31    | ahci       | 403845D763 |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 28    | ahci       | 9A7ADB8860 |
| 8086:9c03 | 8086:7270 | Intel      | 8 Series SATA Controller ... | 26    | ahci       | 95A281E2F8 |
| 8086:9c83 | 8086:7270 | Intel      | Wildcat Point-LP SATA Con... | 24    | ahci       | CD60E38216 |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 22    | ahci       | C9218EE21D |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 22    | ahci       | 5ABCE24217 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 18    | ahci       | 162F499C31 |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 18    | ahci       | BF53DF8658 |
| 1022:7801 | 103c:213d | AMD        | FCH SATA Controller [AHCI... | 17    | ahci       | DE3D6DCDF5 |
| 8086:1c02 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 17    | ahci       | 9301BD0E0F |
| 8086:1f32 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 17    | ahci       | 7E6BEE8355 |
| 8086:a102 | 1043:8694 | Intel      | Q170/Q150/B150/H170/H110/... | 17    | ahci       | 7F9CDC62A2 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 16    | ahci       | EDEBE87739 |
| 8086:5ae3 | 1849:5ae3 | Intel      | Celeron N3350/Pentium N42... | 15    | ahci       | C9218EE21D |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 13    | ahci       | C1DE9809DD |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 13    | ahci       | CEC3CB521D |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 13    | ahci       | C44BE632D3 |
| 8086:1c03 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 13    | ahci       | 66743A51CC |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 13    | ahci       | EECEB3A84C |
| 8086:1f22 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 13    | ahci       | 7E6BEE8355 |
| 8086:9d03 | 8086:9d03 | Intel      | Sunrise Point-LP SATA Con... | 13    | ahci       | 045DFAD837 |
| 8086:1c02 | 15d9:0624 | Intel      | 6 Series/C200 Series Chip... | 12    | ahci       | 08EB9E54FE |
| 8086:8c02 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 12    | ahci       | 09BA719AA7 |
| 8086:0f23 | 8086:7270 | Intel      | Atom Processor E3800 Seri... | 11    | ahci       | 1C67BF34D5 |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 11    | ahci       | 65893EAA25 |
| 8086:8c02 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | ahci       | F2C6B4AA4D |
| 8086:8c02 | 8086:8c02 | Intel      | 8 Series/C220 Series Chip... | 11    | ahci       | FE8DC15588 |
| 8086:9dd3 | 8086:7270 | Intel      | Cannon Point-LP SATA Cont... | 11    | ahci       | 9A399621A9 |
| 8086:a352 | 1043:8694 | Intel      | Cannon Lake PCH SATA AHCI... | 11    | ahci       | DC7D89AB64 |
| 1b4b:9172 | 1458:b000 | Marvell... | 88SE9172 SATA 6Gb/s Contr... | 10    | ahci       | F1A0CEC414 |
| 8086:19c2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 10    | ahci       | E6D9E7AF4E |
| 8086:2929 | 17aa:20f8 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 10    | ahci       | BDBD2D0A05 |
| 8086:8c02 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 10    | ahci       | B5FE536096 |
| 8086:8c02 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 10    | ahci       | 6A22DA5C5D |
| 8086:8c82 | 1458:b005 | Intel      | 9 Series Chipset Family S... | 10    | ahci       | 1DE8945DCA |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 9     | ahci       | CEC3CB521D |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 9     | ahci       | BA938810B9 |
| 1022:43eb | 1b21:1062 | AMD        | Starship/Matisse Chipset ... | 9     | ahci       | 162F499C31 |
| 1022:7901 | 1043:87c0 | AMD        | FCH SATA Controller [AHCI... | 9     | ahci       | 10D9E99990 |
| 10de:0ab9 | 10de:cb79 | Nvidia     | MCP79 AHCI Controller        | 9     | ahci       | F46146B79E |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 88SE9215 PCIe 2.0 x1 4-po... | 9     | ahci       | 6390C16543 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 9     | ahci       | 193936B5CA |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 9     | ahci       | D3742D3898 |
| 8086:22a3 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 9     | ahci       | CE87A10F79 |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 9     | ahci       | C887FF2917 |
| 8086:8c02 | 1458:b005 | Intel      | 8 Series/C220 Series Chip... | 9     | ahci       | 331DA3091C |
| 8086:a282 | 1043:8694 | Intel      | 200 Series PCH SATA contr... | 9     | ahci       | 15BA8E73E1 |
| 1022:43b8 | 1b21:1062 | AMD        | FCH SATA Controller D        | 8     | ahci       | 10D9E99990 |
| 1022:7801 | 103c:8103 | AMD        | FCH SATA Controller [AHCI... | 8     | ahci       | 93A434D951 |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 8     | ahci       | 6BD5EA83B3 |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 8     | ahci       | DC29D714D9 |
| 8086:8c82 | 1043:8534 | Intel      | 9 Series Chipset Family S... | 8     | ahci       | D8ECC7077A |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 7     | ahci       | DA3281B86A |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 7     | ahci       | 7A41FCA3BB |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 7     | ahci       | 9A7ADB8860 |
| 1022:7800 |           | AMD        | FCH SATA Controller [IDE ... | 7     | ahci       | 8B331CB62D |
| 1022:7901 | 1849:ffff | AMD        | FCH SATA Controller [AHCI... | 7     | ahci       | 950B4FBDC2 |
| 8086:0f23 | 1849:0f23 | Intel      | Atom Processor E3800 Seri... | 7     | ahci       | C96913C9ED |
| 8086:19b2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 7     | ahci       | E6D9E7AF4E |
| 8086:19b2 | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 7     | ahci       | B6099E8EAD |
| 8086:1c02 | 103c:330d | Intel      | 6 Series/C200 Series Chip... | 7     | ahci       | 80CF566074 |
| 8086:1e02 | 1028:0577 | Intel      | 7 Series/C210 Series Chip... | 7     | ahci       | 7C333C4F82 |
| 8086:1e02 | 103c:3397 | Intel      | 7 Series/C210 Series Chip... | 7     | ahci       | AB3FC66A9E |
| 8086:1e03 | 17aa:21f3 | Intel      | 7 Series Chipset Family 6... | 7     | ahci       | 0F001F65D2 |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 7     | ahci       | AB871769F0 |
| 8086:27c1 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 7     | ahci       | E930FAC60B |
| 8086:31e3 | 1849:31e3 | Intel      | Celeron/Pentium Silver Pr... | 7     | ahci       | 08D15AE852 |
| 8086:a102 | 1734:121d | Intel      | Q170/Q150/B150/H170/H110/... | 7     | ahci       | 9A0602D408 |
| 8086:a282 | 1458:b005 | Intel      | 200 Series PCH SATA contr... | 7     | ahci       | B77CEEED88 |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 6     | ahci       | 3E474F93CF |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 6     | ahci       | 69A811CAE5 |
| 8086:19c2 | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 6     | ahci       | 44E10AC014 |
| 8086:1e03 | 8086:7270 | Intel      | 7 Series Chipset Family 6... | 6     | ahci       | AFC70D9C77 |
| 8086:2829 | 17aa:20a7 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 6     | ahci       | D223A9B1FB |
| 8086:8c02 | 103c:18e7 | Intel      | 8 Series/C220 Series Chip... | 6     | ahci       | 56A672AF0A |
| 8086:8c02 | 103c:1998 | Intel      | 8 Series/C220 Series Chip... | 6     | ahci       | 2806E1E8CF |
| 8086:8c02 | 17aa:3098 | Intel      | 8 Series/C220 Series Chip... | 6     | ahci       | B7EA8547CE |
| 8086:8c03 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 6     | ahci       | 7660F9B6DB |
| 8086:9c83 | 17aa:2226 | Intel      | Wildcat Point-LP SATA Con... | 6     | ahci       | 107AC19795 |
| 8086:9c83 | 17aa:5034 | Intel      | Wildcat Point-LP SATA Con... | 6     | ahci       | AC567BD12D |
| 8086:9c83 | 8086:2057 | Intel      | Wildcat Point-LP SATA Con... | 6     | ahci       | 1653EA52CE |
| 8086:a102 | 15d9:0884 | Intel      | Q170/Q150/B150/H170/H110/... | 6     | ahci       | 9D69197550 |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 6     | ahci       | DB95470F69 |
| 1022:43b8 | 1849:43c8 | AMD        | FCH SATA Controller D        | 5     | ahci       | D8A1CA5210 |
| 1022:7801 | 1734:1202 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | CDF0C1C8CE |
| 1022:7801 | 1849:7801 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 917EE44FE9 |
| 144d:a801 | 144d:a801 | Samsung... | SM951 AHCI                   | 5     | ahci       | 869F003493 |
| 1b21:0612 | 1b21:1062 | ASMedia... | ASM1062 Serial ATA Contro... | 5     | ahci       | 23751B05A9 |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 5     | ahci       | C42933F9FD |
| 8086:1c02 | 1028:04ad | Intel      | 6 Series/C200 Series Chip... | 5     | ahci       | BEF38BD379 |
| 8086:1c02 | 8086:1c02 | Intel      | 6 Series/C200 Series Chip... | 5     | ahci       | 8B25E6B31B |
| 8086:1c03 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 5     | ahci       | 49DACEE7D0 |
| 8086:1e03 | 1458:b005 | Intel      | 7 Series Chipset Family 6... | 5     | ahci       | A379C24586 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7800 | 1022:7800 | AMD        | FCH SATA Controller [IDE ... | 29    | ahci       | D26409D322 |
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 14    | atapci     | E67DE92CB9 |
| 8086:27c0 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 11    | atapci     | E67DE92CB9 |
| 8086:2850 | 8086:2850 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 10    | atapci     | 901FAAE6DF |
| 8086:3a20 | 103c:330d | Intel      | 82801JI (ICH10 Family) 4 ... | 9     | atapci     | 467F7683F6 |
| 1002:439c | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 8     | atapci     | E69BE420DF |
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 8     | atapci     | C7668C5B0C |
| 1022:780c | 103c:8103 | AMD        | FCH IDE Controller           | 8     | atapci     | 93A434D951 |
| 1002:4390 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 6     | ahci       | E69BE420DF |
| 1002:439c | 1849:439c | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 6     | atapci     | DAA7AFC688 |
| 8086:2828 | 8086:2828 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 6     | atapci     | 901FAAE6DF |
| 8086:2850 | 17aa:20a6 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 6     | atapci     | D223A9B1FB |
| 8086:3a20 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 6     | atapci     | 4EAC97C85C |
| 8086:3a26 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 2 ... | 6     | atapci     | 4EAC97C85C |
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 5     | ahci       | C7668C5B0C |
| 8086:1c00 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 5     | atapci     | E9604E52C7 |
| 8086:1c00 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 5     | atapci     | E262812B4D |
| 8086:1c08 | 1028:04f5 | Intel      | 6 Series/C200 Series Chip... | 5     | atapci     | E9604E52C7 |
| 8086:1c08 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 5     | atapci     | E262812B4D |
| 8086:27c0 | 1458:b002 | Intel      | NM10/ICH7 Family SATA Con... | 5     | atapci     | 338240A790 |
| 8086:27df | 1043:8179 | Intel      | 82801G (ICH7 Family) IDE ... | 5     | atapci     | A12F14678C |
| 8086:2921 | 1028:0236 | Intel      | 82801IB (ICH9) 2 port SAT... | 5     | atapci     | 9EE7FF6592 |
| 8086:3a20 | 1014:3a20 | Intel      | 82801JI (ICH10 Family) 4 ... | 5     | atapci     | 5F9F2C2232 |
| 8086:3a26 | 1014:3a26 | Intel      | 82801JI (ICH10 Family) 2 ... | 5     | atapci     | 5F9F2C2232 |
| 8086:3a26 | 103c:330d | Intel      | 82801JI (ICH10 Family) 2 ... | 5     | atapci     | 59C59BDA2A |
| 1022:780c | 1458:5002 | AMD        | FCH IDE Controller           | 4     | atapci     | 18A74377AC |
| 1106:0415 | 1043:838f | VIA Tec... | VT6415 PATA IDE Host Cont... | 4     | atapci     | E95D6C6972 |
| 197b:2363 | 1043:824f | JMicron... | JMB363 SATA/IDE Controller   | 4     | atapci     | 4EAC97C85C |
| 197b:2363 | 1458:b000 | JMicron... | JMB363 SATA/IDE Controller   | 4     | atapci     | A48A515986 |
| 8086:27c0 | 1028:0400 | Intel      | NM10/ICH7 Family SATA Con... | 4     | atapci     | DB19B8D71C |
| 8086:27c0 | 1043:8179 | Intel      | NM10/ICH7 Family SATA Con... | 4     | atapci     | A12F14678C |
| 8086:27df | 1028:0400 | Intel      | 82801G (ICH7 Family) IDE ... | 4     | atapci     | DB19B8D71C |
| 8086:27df | 17aa:200c | Intel      | 82801G (ICH7 Family) IDE ... | 4     | atapci     | 5375F351A5 |
| 8086:2921 | 1028:0235 | Intel      | 82801IB (ICH9) 2 port SAT... | 4     | atapci     | A2B6B36770 |
| 1002:439c | 103c:1609 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | atapci     | 080EFAF98A |
| 1022:7800 | 1458:b002 | AMD        | FCH SATA Controller [IDE ... | 3     | ahci       | 4D6813B28D |
| 197b:2363 | 1462:7522 | JMicron... | JMB363 SATA/IDE Controller   | 3     | atapci     | BD108F94D5 |
| 8086:1d3c | 103c:1589 | Intel      | C600/X79 series chipset I... | 3     | atapci     | F97FC0533B |
| 8086:1e00 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 3     | atapci     | 2F1E8F315F |
| 8086:1e08 | 1458:b002 | Intel      | 7 Series/C210 Series Chip... | 3     | atapci     | 2F1E8F315F |
| 8086:27c0 | 1043:830e | Intel      | NM10/ICH7 Family SATA Con... | 3     | atapci     | E26ECEF661 |
| 8086:27c0 | 1b0a:0005 | Intel      | NM10/ICH7 Family SATA Con... | 3     | atapci     | 9A8E4A1328 |
| 8086:27df | 1043:830e | Intel      | 82801G (ICH7 Family) IDE ... | 3     | atapci     | E26ECEF661 |
| 8086:27df | 15d9:0602 | Intel      | 82801G (ICH7 Family) IDE ... | 3     | atapci     | A5F2E926FB |
| 8086:2850 | 106b:00a1 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 3     | atapci     | ED3684513F |
| 8086:2920 | 15d9:060a | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 3     | atapci     | 053F22047B |
| 8086:2926 | 15d9:060a | Intel      | 82801I (ICH9 Family) 2 po... | 3     | atapci     | 053F22047B |
| 8086:29b6 | 1028:0211 | Intel      | 82Q35 Express PT IDER Con... | 3     | atapci     | C514817023 |
| 8086:2e16 | 1028:027f | Intel      | 4 Series Chipset PT IDER ... | 3     | atapci     | BD8BF06E7F |
| 8086:7111 |           | Intel      | 82371AB/EB/MB PIIX4 IDE      | 3     | atapci     | 9FF0FB7DF4 |
| 1002:438c | 1002:438c | AMD        | SB600 IDE                    | 2     | atapci     | B621AEAAC3 |
| 1002:438c | 103c:280a | AMD        | SB600 IDE                    | 2     | atapci     | 39A185F54F |
| 1022:780c | 1022:780c | AMD        | FCH IDE Controller           | 2     | atapci     | 9E0509BD54 |
| 10de:0265 | 1043:81c0 | Nvidia     | MCP51 IDE                    | 2     | atapci     | DAE16641BB |
| 10de:0266 | 1043:81c0 | Nvidia     | MCP51 Serial ATA Controller  | 2     | atapci     | DAE16641BB |
| 10de:036e | 108e:6676 | Nvidia     | MCP55 IDE                    | 2     | atapci     | AD993A51ED |
| 10de:037f | 108e:6676 | Nvidia     | MCP55 SATA Controller        | 2     | atapci     | AD993A51ED |
| 10de:03ec | 1849:03ec | Nvidia     | MCP61 IDE                    | 2     | atapci     | 5ABCE24217 |
| 10de:03f6 | 1458:b002 | Nvidia     | MCP61 SATA Controller        | 2     | atapci     | 5D94572E10 |
| 10de:03f6 | 1849:03f6 | Nvidia     | MCP61 SATA Controller        | 2     | atapci     | 5ABCE24217 |
| 1166:0214 | 103c:320b | Broadcom   | BCM5785 [HT1000] IDE         | 2     | atapci     | 8A7564245E |
| 11ab:6121 | 1043:8212 | Marvell... | 88SE6111/6121 SATA II / P... | 2     | atapci     | 65893EAA25 |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 2     | atapci     | 86448FD312 |
| 1283:8213 | 1283:8213 | Integra... | IT8213 IDE Controller        | 2     | atapci     | 5A28B096A2 |
| 1283:8213 | 1458:b000 | Integra... | IT8213 IDE Controller        | 2     | atapci     | F6EAA55ADA |
| 197b:2363 | 1043:81e4 | JMicron... | JMB363 SATA/IDE Controller   | 2     | atapci     | A471763F19 |
| 197b:2368 | 197b:2368 | JMicron... | JMB368 IDE controller        | 2     | atapci     | B4B4EBC9F2 |
| 8086:1c00 | 15d9:0624 | Intel      | 6 Series/C200 Series Chip... | 2     | atapci     | D141FE6C1E |
| 8086:1c08 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 2     | atapci     | F60388BF6A |
| 8086:1c08 | 1458:b002 | Intel      | 6 Series/C200 Series Chip... | 2     | atapci     | B73E45E0DF |
| 8086:1c08 | 15d9:0624 | Intel      | 6 Series/C200 Series Chip... | 2     | atapci     | D141FE6C1E |
| 8086:1d3c | 103c:158a | Intel      | C600/X79 series chipset I... | 2     | atapci     | EC84D94D08 |
| 8086:1d3c | 17aa:1026 | Intel      | C600/X79 series chipset I... | 2     | atapci     | 1EC71F814B |
| 8086:1e00 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 2     | atapci     | B3ACAFEB1A |
| 8086:1e00 | 8086:1e00 | Intel      | 7 Series/C210 Series Chip... | 2     | atapci     | D8D30A13FA |
| 8086:1e08 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 2     | atapci     | B3ACAFEB1A |
| 8086:1e08 | 8086:1e08 | Intel      | 7 Series/C210 Series Chip... | 2     | atapci     | D8D30A13FA |
| 8086:266f | 1043:80a6 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 2     | atapci     | CA50169BF4 |
| 8086:269e | 1028:01b2 | Intel      | 631xESB/632xESB IDE Contr... | 2     | atapci     | F3854BA6E8 |
| 8086:269e | 103c:31fe | Intel      | 631xESB/632xESB IDE Contr... | 2     | atapci     | 658BE87971 |
| 8086:269e | 8086:3476 | Intel      | 631xESB/632xESB IDE Contr... | 2     | atapci     | 411F470773 |
| 8086:27c0 | 1019:2651 | Intel      | NM10/ICH7 Family SATA Con... | 2     | atapci     | 1186D46AC9 |
| 8086:27c0 | 104d:9075 | Intel      | NM10/ICH7 Family SATA Con... | 2     | atapci     | 30BB4FC23C |
| 8086:27c0 | 17aa:1015 | Intel      | NM10/ICH7 Family SATA Con... | 2     | atapci     | 395EF09E6D |
| 8086:27c0 | 1849:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 2     | atapci     | F2ED3275E0 |
| 8086:27df | 1019:2651 | Intel      | 82801G (ICH7 Family) IDE ... | 2     | atapci     | 1186D46AC9 |
| 8086:27df | 1028:01d1 | Intel      | 82801G (ICH7 Family) IDE ... | 2     | atapci     | 91418A4965 |
| 8086:27df | 1458:b001 | Intel      | 82801G (ICH7 Family) IDE ... | 2     | atapci     | 67B6B45D83 |
| 8086:27df | 1849:27df | Intel      | 82801G (ICH7 Family) IDE ... | 2     | atapci     | F2ED3275E0 |
| 8086:27df | 8086:d613 | Intel      | 82801G (ICH7 Family) IDE ... | 2     | atapci     | E0F72BC85E |
| 8086:2850 | 106b:00a0 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 2     | atapci     | 22BADCAB59 |
| 8086:2921 | 8086:2921 | Intel      | 82801IB (ICH9) 2 port SAT... | 2     | atapci     | BA1D9A51C2 |
| 8086:2926 | 1043:8277 | Intel      | 82801I (ICH9 Family) 2 po... | 2     | atapci     | 89FBF4A403 |
| 8086:2926 | 8086:2926 | Intel      | 82801I (ICH9 Family) 2 po... | 2     | atapci     | BA1D9A51C2 |
| 8086:2a46 | 17aa:20ea | Intel      | Mobile 4 Series Chipset P... | 2     | atapci     | F8CE633ED7 |
| 8086:2e16 | 1028:0420 | Intel      | 4 Series Chipset PT IDER ... | 2     | atapci     | D9298B716F |
| 8086:3b66 | 8086:3b66 | Intel      | 5 Series/3400 Series Chip... | 2     | atapci     | 12058880BC |
| 1002:4380 | 1002:4380 | AMD        | SB600 Non-Raid-5 SATA        | 1     | ahci       | B621AEAAC3 |
| 1002:4380 | 1028:01e5 | AMD        | SB600 Non-Raid-5 SATA        | 1     | ahci       | C71DE24556 |
| 1002:4380 | 1028:01f5 | AMD        | SB600 Non-Raid-5 SATA        | 1     | ahci       | 9EE3E7CBC2 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 102   | nvme       | 162F499C31 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 38    | nvme       | 15BA8E73E1 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 23    | nvme       | 1133FFB4F2 |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 15    | nvme       | 0B3C9A332D |
| 126f:2263 | 126f:2263 | Silicon... | SM2263EN/SM2263XT SSD Con... | 13    | nvme       | 88C27E65D7 |
| 15b7:5006 | 15b7:5006 | Sandisk    | WD Black SN750 / PC SN730... | 13    | nvme       | DB12A78352 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 13    | nvme       | 2247C7130F |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 11    | nvme       | DB95470F69 |
| 2646:2263 | 2646:2263 | Kingsto... | A2000 NVMe SSD               | 11    | nvme       | D8B645D95D |
| 144d:a809 | 144d:a801 | Samsung... | NVMe Controller              | 10    | nvme       | 3C6B3D4CE8 |
| 1987:5013 | 1987:5013 | Phison ... | PS5013 E13 NVMe Controller   | 8     | nvme       | 33B86A7DF2 |
| 1987:5016 | 1987:5016 | Phison ... | E16 PCIe4 NVMe Controller    | 8     | nvme       | AD380CB985 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 8     | nvme       | 2F1BA02130 |
| 2646:500d | 2646:500d | Kingsto... | OM3PDP3 NVMe SSD             | 7     | nvme       | AE1BFCCF22 |
| 1c5c:1327 |           | SK Hynix   | BC501 NVMe Solid State Dr... | 6     | nvme       | 337A8B5A3D |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 6     | nvme       | 0B3C9A332D |
| 1179:0115 | 1179:0001 | Toshiba    | XG4 NVMe SSD Controller      | 5     | nvme       | F2AA5A598B |
| 1179:0116 | 1179:0001 | Toshiba    | unknown                      | 5     | nvme       | DAB0CA2417 |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 5     | nvme       | 1C9FEEF8E7 |
| 144d:a80a | 144d:a801 | Samsung... | NVMe SSD Controller PM9A1... | 5     | nvme       | CBBF4F86CD |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 5     | nvme       | 045A80D8BC |
| c0a9:2263 | c0a9:2263 | Micron/... | P1 NVMe PCIe SSD             | 5     | nvme       | 547FD655F0 |
| 1179:0113 | 1179:0001 | Toshiba    | BG3 NVMe SSD Controller      | 4     | nvme       | 4607D1410C |
| 1344:5405 | 1344:0100 | Micron ... |                              | 4     | nvme       | BA74D8EEE0 |
| 1344:5410 | 1344:0100 | Micron ... |                              | 4     | nvme       | D435C22FA0 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 4     | nvme       | D6312ECF58 |
| 15b7:5011 | 15b7:5011 | Sandisk    | WD Black SN850               | 4     | nvme       | DB12A78352 |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   | hynix unknown                | 4     | nvme       | 5E6FBBD1EE |
| 1c5c:1639 | 1c5c:1639 | SK Hynix   | hynix unknown                | 4     | nvme       | 9478973D4C |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 4     | nvme       | 4710D6000D |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 4     | nvme       | C42933F9FD |
| 10ec:5760 | 5760:10ec | Realtek... |                              | 3     | nvme       | F8BDEC0105 |
| 1179:011a | 1179:0001 | Toshiba    | XG6 NVMe SSD Controller      | 3     | nvme       | 2AD87768AF |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Blue SN500 / PC SN520 ... | 3     | nvme       | 2737CDCAB2 |
| 1bb1:5016 | 1bb1:5016 | Seagate... | FireCuda 520 SSD             | 3     | nvme       | A09FBE5FCC |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 3     | nvme       | 89C0064AEB |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 3     | nvme       | FC4265EB19 |
| 10ec:5763 | 10ec:5763 | Realtek... |                              | 2     | nvme       | B77CEEED88 |
| 15b7:5001 | 1b4b:1093 | Sandisk    | WD Black NVMe SSD            | 2     | nvme       | A3AF1CDE86 |
| 15b7:5005 | 15b7:5005 | Sandisk    | PC SN520 NVMe SSD            | 2     | nvme       | 1F226262CC |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 2     | nvme       | BAB75AC477 |
| 1c5c:1339 |           | SK Hynix   | BC511                        | 2     | nvme       | 80D7BF959A |
| 1db2:2302 | 1db2:2302 | ATP ELE... |                              | 2     | nvme       | 9D69197550 |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 2     | nvme       | ADE306695D |
| 1179:010f | 1179:0001 | Toshiba    | NVMe Controller              | 1     | nvme       | DDC907CCF4 |
| 14a4:2300 | 1b4b:1093 | Lite-On... |                              | 1     | nvme       | A467FFACF3 |
| 15b7:5004 | 15b7:5004 | Sandisk    | PC SN520 NVMe SSD            | 1     | nvme       | 2538B038ED |
| 17aa:0004 | 17aa:1004 | Lenovo     |                              | 1     | nvme       | 16206C4970 |
| 1987:5007 | 1987:5007 | Phison ... | E7 NVMe Controller           | 1     | nvme       | B5665D0DF2 |
| 1987:5018 | 1987:5018 | Phison ... |                              | 1     | nvme       | 4D7013AEAB |
| 1c44:1100 | 1c44:1100 | Enmotus    |                              | 1     | nvme       | B507D43DE5 |
| 1c5c:1284 |           | SK Hynix   | PC300 NVMe Solid State Dr... | 1     | nvme       | 4993AD0FEB |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 1     | nvme       | 310BD9E4AF |
| 1c5c:1527 | 1c5c:1527 | SK Hynix   | PC401 NVMe Solid State Dr... | 1     | nvme       | 9F871AB960 |
| 1cc1:33f8 | 1cc1:33f8 | ADATA T... |                              | 1     | nvme       | DF77DD6562 |
| 1cc4:17aa | 1cc4:1008 | Union M... |                              | 1     | nvme       | 7A706E46DE |
| 1cc4:17ab | 1cc4:1007 | Union M... | NVMe 256G SSD device         | 1     | nvme       | D15116D2EB |
| 1cc4:5008 | 1cc4:5008 | Union M... |                              | 1     | nvme       | CD2AD2800E |
| 1d0f:8061 |           | Amazon.com | NVMe EBS Controller          | 1     | nvme       | 7A05270DDB |
| 1d97:1160 | 1d97:1160 | Shenzhe... |                              | 1     | nvme       | 771D8EAD80 |
| 1dee:2262 | 1dee:1dee | Biwin S... |                              | 1     | nvme       | 93A8B87E1C |
| 1e0f:0001 | 1e0f:0001 | KIOXIA     |                              | 1     | nvme       | ECF07AD5FE |
| 1e95:9100 | 126f:2263 | Solid S... |                              | 1     | nvme       | C2D56FC369 |
| 2646:500c | 2646:500c | Kingsto... |                              | 1     | nvme       | 37E4E7C85C |
| 8086:0953 | 108e:370b | Intel      | PCIe Data Center SSD         | 1     | nvme       | 7CEC65D8F8 |
| 8086:0975 | 8086:8410 | Intel      |                              | 1     | nvme       | 3AE7EEBB87 |
| 8086:0975 | 8086:8510 | Intel      |                              | 1     | nvme       | 3AE7EEBB87 |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 1     | nvme       | 4E4F164625 |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 1     | nvme       | BD63DE17B0 |
| 8086:2700 | 8086:3901 | Intel      | Optane SSD 900P Series       | 1     | nvme       | F8A95C37D5 |
| 8086:faf0 | 8086:390e | Intel      |                              | 1     | nvme       | 9517FD0273 |
| c0a9:5403 | c0a9:1100 | Micron/... | NVMe Controller              | 1     | nvme       | AC7A652266 |
| c0a9:540a | c0a9:540a | Micron/... | P2 NVMe PCIe SSD             | 1     | nvme       | 34F3A0A646 |
| c0a9:5412 | c0a9:0100 | Micron/... |                              | 1     | nvme       | 12C985B708 |
| fb5d:0a0a |           |            |                              | 1     | nvme       | 0BC0FA71BA |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 12    | ciss       | 82D00F440D |
| 1000:0060 | 1028:1f0c | Broadco... | MegaRAID SAS 1078            | 11    | mfi        | A2B6B36770 |
| 8086:282a | 8086:7270 | Intel      | 82801 Mobile SATA Control... | 10    | ahci       | AE1BFCCF22 |
| 1000:005b | 1028:1f34 | Broadco... | MegaRAID SAS 2208 [Thunde... | 8     | mfi        | 8F4B51DABD |
| 1000:005b | 1028:1f38 | Broadco... | MegaRAID SAS 2208 [Thunde... | 4     | mfi        | 77F48D8337 |
| 1000:005f | 1028:1f44 | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 4     | mfi        | 997DA6A5C6 |
| 1000:005f | 1028:1f4b | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 4     | mfi        | 5ACC629D2E |
| 1000:0079 | 1028:1f17 | Broadco... | MegaRAID SAS 2108 [Libera... | 4     | mfi        | 149B6DB16F |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 4     | ahci       | AF5D6A85EF |
| 1000:0072 | 1734:1177 | Broadco... | SAS2008 PCI-Express Fusio... | 3     | mps        | 88EE81B089 |
| 1000:0073 | 1028:1f51 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 3     | mfi        | 77475B714A |
| 1000:0079 | 1014:03c7 | Broadco... | MegaRAID SAS 2108 [Libera... | 3     | mfi        | 8BBC599CDD |
| 8086:1c04 | 1028:04dd | Intel      | 6 Series/C200 Series Desk... | 3     | ahci       | 668C05619B |
| 8086:282a | 1028:05ca | Intel      | 82801 Mobile SATA Control... | 3     | ahci       | 1DBD9A5CEE |
| 1000:0014 | 1734:1238 | Broadco... | MegaRAID Tri-Mode SAS3516    | 2     | mrsas      | 6460F775B0 |
| 1000:005d | 1028:1f49 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 2     | mfi        | 94F3A7B95A |
| 1000:0073 | 1014:03b1 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 2     | mfi        | 71D412D254 |
| 103c:3230 | 103c:3234 | Hewlett... | Smart Array Controller       | 2     | ciss       | 658BE87971 |
| 103c:3230 | 103c:3235 | Hewlett... | Smart Array Controller       | 2     | ciss       | 710C4F4AAB |
| 103c:3239 | 103c:21c5 | Hewlett... | Smart Array Gen9 Controllers | 2     | ciss       | D35F62BA44 |
| 103c:3239 | 103c:21cb | Hewlett... | Smart Array Gen9 Controllers | 2     | ciss       | D35F62BA44 |
| 103c:323a | 103c:3241 | Hewlett... | Smart Array G6 controllers   | 2     | ciss       | B1F7A57B01 |
| 103c:323a | 103c:3243 | Hewlett... | Smart Array G6 controllers   | 2     | ciss       | 4907DD5D8F |
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 2     | ciss       | 996A6207DC |
| 1095:3114 | 1095:3114 | Silicon... | SiI 3114 [SATALink/SATARa... | 2     | atapci     | 714B6539CF |
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 2     | atapci     | 5ABCE24217 |
| 13c1:1004 | 13c1:1004 | 3ware      | 9650SE SATA-II RAID PCIe     | 2     | twa        | CF2E66B6AA |
| 8086:02d7 | 1028:09ec | Intel      | Comet Lake PCH-LP SATA RA... | 2     |            | 465DD01C0D |
| 8086:2822 | 1028:0420 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | FCBFBC2DFA |
| 8086:2822 | 1028:047e | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 1CDB97BFCC |
| 8086:2822 | 1028:052c | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 4CB0341268 |
| 8086:2822 | 1028:0620 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | D714F07288 |
| 8086:2822 | 1028:06ba | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | D9AE9EC6F6 |
| 8086:2822 | 1028:07c5 | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 17A0A5FDCF |
| 8086:2822 | 1028:084c | Intel      | SATA Controller [RAID mode]  | 2     | ahci       | 9468EEEF92 |
| 8086:2826 | 103c:158a | Intel      | C600/X79 series chipset S... | 2     | ahci       | DFFF5DD2F9 |
| 8086:2826 | 17aa:30b0 | Intel      | C600/X79 series chipset S... | 2     | ahci       | DABCAB55BB |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 211FE874FD |
| 8086:282a | 1028:05cc | Intel      | 82801 Mobile SATA Control... | 2     | ahci       | 1847C0AADB |
| 9005:028b | 9005:0301 | Adaptec    | Series 6 - 6G SAS/PCIe 2     | 2     | aacraid    | 0546131058 |
| 1000:0017 | 17aa:103a | Broadco... | MegaRAID Tri-Mode SAS3408    | 1     | mrsas      | FFAA30BC08 |
| 1000:005b | 1028:1f2d | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | mrsas      | AC57AB9EF6 |
| 1000:005d | 1000:9363 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mfi        | 0573099467 |
| 1000:005d | 1028:1f41 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mrsas      | 32F145EA04 |
| 1000:005d | 1028:1f42 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mrsas      | 32F145EA04 |
| 1000:005d | 1028:1f47 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mfi        | 55C1BD261F |
| 1000:005f | 1000:9340 | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 1     | mrsas      | 1151C41ED4 |
| 1000:005f | 1734:1211 | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 1     | mfi        | 0F4461E95F |
| 1000:0072 | 1028:1f51 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 7CEC65D8F8 |
| 1000:0073 | 1000:9241 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 1     | mfi        | EB73C9D13D |
| 1000:0073 | 1028:1f78 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 1     | mfi        | 16CA205380 |
| 1000:0079 | 1000:9260 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | mfi        | 6DD2D44AA1 |
| 1000:0079 | 1000:9261 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | mfi        | 474B0E44EA |
| 1002:4393 | 1849:4393 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 6C0BBA6D4F |
| 1028:0013 | 1028:016c | Dell       | PowerEdge Expandable RAID... | 1     | amr        | BB83934454 |
| 1028:0015 | 1028:1f03 | Dell       | PowerEdge Expandable RAID... | 1     | mfi        | F3854BA6E8 |
| 103c:3220 | 103c:3225 | Hewlett... | Smart Array P600             | 1     | ciss       | 8A7564245E |
| 103c:3230 | 103c:3223 | Hewlett... | Smart Array Controller       | 1     | ciss       | 658BE87971 |
| 103c:323a | 103c:3249 | Hewlett... | Smart Array G6 controllers   | 1     | ciss       | 7CC48A8D08 |
| 103c:323b | 103c:3351 | Hewlett... | Smart Array Gen8 Controllers | 1     | ciss       | 54FD4A89D8 |
| 1095:0242 | 9005:0242 | Silicon... | AAR-1220SA Serial ATA Hos... | 1     | siis       | F51F3873CE |
| 1095:3112 | 1095:3112 | Silicon... | SiI 3112 [SATALink/SATARa... | 1     | atapci     | C71DE24556 |
| 1095:3114 | 1043:8136 | Silicon... | SiI 3114 [SATALink/SATARa... | 1     | atapci     | 5B1DC84DA5 |
| 1095:3114 | 1095:7114 | Silicon... | SiI 3114 [SATALink/SATARa... | 1     | atapci     | C9C1D22E00 |
| 1095:3124 | 1095:7124 | Silicon... | SiI 3124 PCI-X Serial ATA... | 1     | siis       | 82D3305FB4 |
| 1095:3132 | 1095:7132 | Silicon... | SiI 3132 Serial ATA Raid ... | 1     | siis       | CEC3CB521D |
| 13c1:1010 | 13c1:0001 | 3ware      | 9750 SAS2/SATA-II RAID PCIe  | 1     | tws        | 49A39EB60F |
| 17d3:1220 | 17d3:1220 | Areca T... | ARC-1220 8-Port PCI-Expre... | 1     | arcmsr     | 29F0346899 |
| 17d3:1280 | 17d3:1221 | Areca T... | ARC-1280/1280ML 24-Port P... | 1     | arcmsr     | 56E5678551 |
| 17d3:1680 | 17d3:1212 | Areca T... | ARC-1680 series PCIe to S... | 1     | arcmsr     | 6B7FBA08DD |
| 8086:02d7 | 1028:09a1 | Intel      | Comet Lake PCH-LP SATA RA... | 1     |            | 7DEF696A61 |
| 8086:06d6 | 1028:09c5 | Intel      | 400 Series Chipset Family... | 1     |            | 7B7495169B |
| 8086:06d6 | 1043:8694 | Intel      | 400 Series Chipset Family... | 1     |            | D106F46DDE |
| 8086:1c04 | 1590:006c | Intel      | 6 Series/C200 Series Desk... | 1     | ahci       | 415023D5A1 |
| 8086:27c3 | 1028:01d1 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 1     | ahci       | 91418A4965 |
| 8086:27c3 | 103c:2a2b | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 1     | ahci       | C93B86B3BA |
| 8086:27c3 | 103c:2a50 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 1     | ahci       | FC1C23BEE2 |
| 8086:27c3 | 103c:2a5e | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 1     | ahci       | 2279DD7E5A |
| 8086:27c3 | 103c:3206 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 1     | ahci       | D6114DE1CC |
| 8086:27c3 | 107b:604e | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 1     | ahci       | 322450B653 |
| 8086:2822 | 1025:024d | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 0BC978756C |
| 8086:2822 | 1028:02da | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | DA8911A7DE |
| 8086:2822 | 1028:040d | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | CD086A9092 |
| 8086:2822 | 1028:06df | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | C8477DA717 |
| 8086:2822 | 1028:07a1 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 1499695AAE |
| 8086:2822 | 1028:07a2 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | BE3EC90430 |
| 8086:2822 | 1028:0859 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 0EA0CA31BF |
| 8086:2822 | 1028:085b | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 23E7163F58 |
| 8086:2822 | 1028:0874 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 6D3DEFCDE3 |
| 8086:2822 | 103c:1309 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | BF0D7FE4F1 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | EB8428D5F3 |
| 8086:2822 | 103c:130b | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 6DDE87584C |
| 8086:2822 | 103c:1495 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | AF5DACFF9F |
| 8086:2822 | 103c:1790 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 59E472FB01 |
| 8086:2822 | 1043:8534 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 69A811CAE5 |
| 8086:2822 | 1458:b000 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | F1A0CEC414 |
| 8086:2822 | 15d9:0624 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | F71FB99CD3 |
| 8086:2822 | 1734:121d | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 8891E427E1 |
| 8086:2822 | 1849:a282 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 37AF53E334 |
| 8086:2826 | 1028:0617 | Intel      | C600/X79 series chipset S... | 1     | ahci       | 5FFEB3D23E |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0072 | 1000:3020 | Broadco... | SAS2008 PCI-Express Fusio... | 20    | mps        | E308BECDA4 |
| 1000:0072 | 1028:1f1c | Broadco... | SAS2008 PCI-Express Fusio... | 6     | mps        | F23BF8E1A7 |
| 1000:0072 | 1028:1f1d | Broadco... | SAS2008 PCI-Express Fusio... | 5     | mps        | 9301BD0E0F |
| 1000:0072 | 1028:1f1e | Broadco... | SAS2008 PCI-Express Fusio... | 3     | mps        | 27B11C7A56 |
| 1000:0087 | 1000:3020 | Broadco... | SAS2308 PCI-Express Fusio... | 3     | mps        | 5283765CBE |
| 1000:0097 | 1000:30e0 | Broadco... | SAS3008 PCI-Express Fusio... | 3     | mpr        | 5B71C5420F |
| 1000:0097 | 15d9:0808 | Broadco... | SAS3008 PCI-Express Fusio... | 3     | mpr        | 6C4D7ACEEC |
| 8086:1d6b | 103c:1589 | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | F97FC0533B |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 3     | isci       | EC84D94D08 |
| 1000:0016 | 1028:1fcd | Broadco... | MegaRAID Tri-Mode SAS3508    | 2     | mrsas      | AA44179A5F |
| 1000:0072 | 1000:0072 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mps        | 6A6164AF73 |
| 1000:0072 | 1000:3040 | Broadco... | SAS2008 PCI-Express Fusio... | 2     | mps        | 49AD4461DC |
| 1000:0097 | 1028:1f53 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpr        | B062E0F4E4 |
| 8086:1d6b | 17aa:1026 | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | 1EC71F814B |
| 1000:0016 | 1028:1fcb | Broadco... | MegaRAID Tri-Mode SAS3508    | 1     | mrsas      | E37DE1CD8C |
| 1000:005d | 15d9:0a09 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mrsas      | B44FE94131 |
| 1000:005d | 19e5:da07 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mrsas      | AC2C7107D3 |
| 1000:0064 | 1000:30c0 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mps        | 4DCA0D2AA4 |
| 1000:0064 | 1000:30d0 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mps        | CF2E66B6AA |
| 1000:0070 | 1000:3010 | Broadco... | SAS2004 PCI-Express Fusio... | 1     | mps        | 7A41FCA3BB |
| 1000:0072 | 1000:3050 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 28FDD2C2DC |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | F88EAF06AC |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 6ACB4D8445 |
| 1000:0086 | 103c:158b | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mps        | 3D780DD078 |
| 1000:0087 | 1000:3030 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mps        | E59D5D41A5 |
| 1000:0087 | 1028:1f38 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mps        | 92A93D51C5 |
| 1000:0097 | 1028:0619 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpr        | DDDF168DB9 |
| 1000:0097 | 1849:0097 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpr        | D59D8A3B6D |
| 1000:00ac | 1000:3000 | Broadco... | SAS3416 Fusion-MPT Tri-Mo... | 1     | mpr        | 23196AA66B |
| 103c:3239 | 103c:21c7 | Hewlett... | Smart Array Gen9 Controllers | 1     | ciss       | 533B1E078E |
| 103c:3239 | 103c:21c8 | Hewlett... | Smart Array Gen9 Controllers | 1     | ciss       | C2BB148E8A |
| 8086:1d6a | 8086:3583 | Intel      | C600/X79 series chipset D... | 1     | isci       | 474B0E44EA |
| 8086:1d6b | 103c:158b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 3D780DD078 |
| 8086:1d6b | 152d:899b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | A4980E3EA4 |
| 8086:1d6b | 15d9:0628 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 31017CE819 |
| 8086:1d6b | 15d9:062f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | A3BCB2FCF1 |
| 8086:1d6b | 15d9:0703 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1F4D1E4607 |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | D6AFDBD24B |
| 8086:1d6f | 1734:11b6 | Intel      | C600/X79 series chipset 4... | 1     | isci       | A9D034FE42 |
| 9005:028f | 103c:0651 | Adaptec    | Smart Storage PQI SAS        | 1     | smartpqi   | F8A95C37D5 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1425:4501 |           | Chelsio... | T420-CR Unified Wire Stor... | 4     |            | 536E6B5FDF |
| 17d3:1300 | 17d3:1300 | Areca T... | ARC-1300ix-16 16-Port PCI... | 4     | arcsas     | 66BBED8D59 |
| 1000:0058 | 1014:0394 | Broadco... | SAS1068E PCI-Express Fusi... | 3     | mpt        | 5F9F2C2232 |
| 1000:0058 | 1028:1f0f | Broadco... | SAS1068E PCI-Express Fusi... | 3     | mpt        | A9CF80B10F |
| 1000:0054 | 1028:1f09 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 2     | mpt        | E98F23CD45 |
| 1000:0058 | 1028:1f0e | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mpt        | 411477E260 |
| 1000:0001 | 1000:1000 | Broadco... | 53c810                       | 1     | sym        | 4EE625240F |
| 1000:000f | 1000:1000 | Broadco... | 53c875                       | 1     | sym        | DAE16641BB |
| 1000:0030 | 1000:10b0 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mpt        | 970467EFEF |
| 1000:0030 | 103c:322a | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mpt        | 8A7564245E |
| 1000:0030 | 1734:1041 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mpt        | ADB972BF8E |
| 1000:0056 | 1734:1131 | Broadco... | SAS1064ET PCI-Express Fus... | 1     | mpt        | FF2213E848 |
| 1000:0058 | 103c:130b | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mpt        | 6DDE87584C |
| 1000:0058 | 15d9:a480 | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mpt        | 27FC294BCA |
| 1000:0058 | 17aa:101d | Broadco... | SAS1068E PCI-Express Fusi... | 1     | mpt        | 6F464AAD1F |
| 1000:0059 | 15d9:0004 | Broadco... | MegaRAID SAS 8208ELP/8208ELP | 1     | mpt        | 7D0E121099 |
| 1103:2300 | 11ab:11ab | HighPoi... | RocketRAID 230x 4 Port SA... | 1     | hptrr      | AA29EB9C75 |
| 1425:5501 |           | Chelsio... | T520-CR Unified Wire Stor... | 1     |            | FBA459287E |
| 1425:5503 |           | Chelsio... | T540-CR Unified Wire Stor... | 1     |            | C279F7D056 |
| 1425:5584 |           | Chelsio... | T540-5084 Unified Wire St... | 1     |            | 2BBA0377AE |
| 1425:6503 |           | Chelsio... | T6425-CR Unified Wire Sto... | 1     |            | 17A763A917 |
| 5853:0001 | 5853:0001 | XenSource  | Xen Platform Device          | 1     | xenpci     | EA814A4205 |
| 9004:5078 |           | Adaptec    | AIC-7850T/7856T [AVA-2902... | 1     | ahc        | 1BC05B5951 |
| 9004:5078 | 9004:7850 | Adaptec    | AIC-7850T/7856T [AVA-2902... | 1     | ahc        | 88EE81B089 |
| 9004:8178 |           | Adaptec    | AIC-7870P/7881U [AHA-2940... | 1     | ahc        | 622589C8E7 |
| 9004:8178 | 9004:7881 | Adaptec    | AIC-7870P/7881U [AHA-2940... | 1     | ahc        | 75E86A92F7 |
| 9005:8017 | 9005:0045 | Adaptec    | ASC-29320ALP U320            | 1     | ahd        | EB73C9D13D |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1567 | 1022:1567 | AMD        | Mullins IOMMU                | 76    |            | 7FFAED1505 |
| 8086:1911 | 8086:2015 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 61    |            | 80122A9F4A |
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 53    |            | CCAF608BD7 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 53    |            | CCAF608BD7 |
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 42    |            | CCAF608BD7 |
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 38    |            | 162F499C31 |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 37    |            | 2F1BA02130 |
| 8086:6f76 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 37    |            | 289D61B1B2 |
| 8086:6f88 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 36    |            | 289D61B1B2 |
| 8086:6f8a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 36    |            | 289D61B1B2 |
| 8086:6fae |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 36    |            | 289D61B1B2 |
| 8086:6faf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 36    |            | 289D61B1B2 |
| 8086:6fbc |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 36    |            | 289D61B1B2 |
| 8086:6fbd |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 36    |            | 289D61B1B2 |
| 8086:6fbe |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 36    |            | 289D61B1B2 |
| 8086:6fbf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 36    |            | 289D61B1B2 |
| 8086:6f1d | 8086:6f1d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f1e | 8086:6f1e | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f1f | 8086:6f1f | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f71 | 8086:6f71 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f98 | 8086:6f98 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f99 | 8086:6f99 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f9a | 8086:6f9a | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f9c | 8086:6f9c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fa0 | 8086:6fa0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fa8 | 8086:6fa8 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6faa | 8086:6faa | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fab | 8086:6fab | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fac | 8086:6fac | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fad | 8086:6fad | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fb0 | 8086:6fb0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fb1 | 8086:6fb1 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fb2 | 8086:6fb2 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fb3 | 8086:6fb3 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fb4 | 8086:6fb4 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fb5 | 8086:6fb5 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fb6 | 8086:6fb6 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fb7 | 8086:6fb7 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fc0 | 8086:6fc0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fe0 | 8086:6fe0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6fe1 | 8086:6fe1 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6ff8 | 8086:6ff8 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6ffc | 8086:6fe0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6ffd | 8086:6fe0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6ffe | 8086:6fe0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f81 | 8086:6f81 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6fe2 | 8086:6fe2 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6fe3 | 8086:6fe3 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 25    |            | 5ACC629D2E |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 25    |            | CCAF608BD7 |
| 8086:1f15 |           | Intel      | Atom processor C2000 SMBu... | 24    |            | 7E6BEE8355 |
| 8086:1f16 |           | Intel      | Atom processor C2000 RCEC    | 24    |            | 7E6BEE8355 |
| 8086:2018 |           | Intel      | Sky Lake-E M2PCI Registers   | 23    |            | 6460F775B0 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 23    | ioapic     | 6460F775B0 |
| 8086:2034 |           | Intel      | Sky Lake-E VT-d              | 23    |            | 6460F775B0 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 23    |            | 6460F775B0 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 23    | ioapic     | 6460F775B0 |
| 8086:2040 |           | Intel      | Sky Lake-E Integrated Mem... | 23    |            | 6460F775B0 |
| 8086:2041 |           | Intel      | Sky Lake-E Integrated Mem... | 23    |            | 6460F775B0 |
| 8086:2042 |           | Intel      | Sky Lake-E Integrated Mem... | 23    |            | 6460F775B0 |
| 8086:2043 |           | Intel      | Sky Lake-E Integrated Mem... | 23    |            | 6460F775B0 |
| 8086:2044 |           | Intel      | Sky Lake-E Integrated Mem... | 23    |            | 6460F775B0 |
| 8086:2045 |           | Intel      | Sky Lake-E LM Channel 1      | 23    |            | 6460F775B0 |
| 8086:2046 |           | Intel      | Sky Lake-E LMS Channel 1     | 23    |            | 6460F775B0 |
| 8086:2047 |           | Intel      | Sky Lake-E LMDP Channel 1    | 23    |            | 6460F775B0 |
| 8086:2048 |           | Intel      | Sky Lake-E DECS Channel 2    | 23    |            | 6460F775B0 |
| 8086:2049 |           | Intel      | Sky Lake-E LM Channel 2      | 23    |            | 6460F775B0 |
| 8086:204a |           | Intel      | Sky Lake-E LMS Channel 2     | 23    |            | 6460F775B0 |
| 8086:204b |           | Intel      | Sky Lake-E LMDP Channel 2    | 23    |            | 6460F775B0 |
| 8086:204e |           | Intel      | Sky Lake-E M3KTI Registers   | 23    |            | 6460F775B0 |
| 8086:2066 |           | Intel      | Sky Lake-E Integrated Mem... | 23    |            | 6460F775B0 |
| 103c:3306 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 22    |            | 39B99E57AF |
| 103c:3307 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 22    |            | 39B99E57AF |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 22    |            | 5ACC629D2E |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 22    |            | 5ACC629D2E |
| 8086:2016 |           | Intel      | Sky Lake-E Ubox Registers    | 20    |            | C4862C598A |
| 8086:2024 |           | Intel      | Sky Lake-E MM/Vt-d Config... | 20    |            | 6460F775B0 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 20    |            | C4862C598A |
| 8086:2054 |           | Intel      | Sky Lake-E CHA Registers     | 20    |            | C4862C598A |
| 8086:2055 |           | Intel      | Sky Lake-E CHA Registers     | 20    |            | C4862C598A |
| 8086:2056 |           | Intel      | Sky Lake-E CHA Registers     | 20    |            | C4862C598A |
| 8086:2057 |           | Intel      | Sky Lake-E CHA Registers     | 20    |            | C4862C598A |
| 8086:2080 |           | Intel      | Sky Lake-E PCU Registers     | 20    |            | C4862C598A |
| 8086:2081 |           | Intel      | Sky Lake-E PCU Registers     | 20    |            | C4862C598A |
| 8086:2082 |           | Intel      | Sky Lake-E PCU Registers     | 20    |            | C4862C598A |
| 8086:2083 |           | Intel      | Sky Lake-E PCU Registers     | 20    |            | C4862C598A |
| 8086:2084 |           | Intel      | Sky Lake-E PCU Registers     | 20    |            | C4862C598A |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:7808 | 1022:7808 | AMD        | FCH USB EHCI Controller      | 106   | ehci       | 7FFAED1505 |
| 1022:7814 | 1022:1410 | AMD        | FCH USB XHCI Controller      | 101   | xhci       | 7FFAED1505 |
| 8086:9d2f | 8086:7270 | Intel      | Sunrise Point-LP USB 3.0 ... | 95    | xhci       | 8FAE98E5A6 |
| 8086:22b5 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 68    | xhci       | 3E773132B3 |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 60    | xhci       | FF1A657505 |
| 1022:43d5 | 1b21:1142 | AMD        | 400 Series Chipset USB 3.... | 41    | xhci       | EDEBE87739 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 38    | xhci       | E5DA7D6A12 |
| 1022:149c | 1022:148c | AMD        | Matisse USB 3.0 Host Cont... | 36    | xhci       | 2247C7130F |
| 8086:31a8 | 8086:7270 | Intel      | Celeron/Pentium Silver Pr... | 32    | xhci       | 403845D763 |
| 8086:9c26 | 8086:7270 | Intel      | 8 Series USB EHCI #1         | 26    | ehci       | 95A281E2F8 |
| 8086:9c31 | 8086:7270 | Intel      | 8 Series USB xHCI HC         | 26    | xhci       | 95A281E2F8 |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 25    | ehci       | 98F39AFF26 |
| 8086:0f34 | 8086:0f34 | Intel      | Atom Processor Z36xxx/Z37... | 25    | ehci       | FF1A657505 |
| 8086:9cb1 | 8086:7270 | Intel      | Wildcat Point-LP USB xHCI... | 25    | xhci       | CD60E38216 |
| 8086:9ca6 | 8086:7270 | Intel      | Wildcat Point-LP USB EHCI... | 24    | ehci       | CD60E38216 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 23    | ohci       | CEC3CB521D |
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 23    | xhci       | 951C3E534C |
| 1022:149c | 1022:1486 | AMD        | Matisse USB 3.0 Host Cont... | 22    | xhci       | 2247C7130F |
| 103c:3300 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 22    | uhci       | 39B99E57AF |
| 1022:149c | 1043:87c0 | AMD        | Matisse USB 3.0 Host Cont... | 21    | xhci       | 10D9E99990 |
| 8086:27c8 | 8086:27c8 | Intel      | NM10/ICH7 Family USB UHCI... | 21    | uhci       | 8D59B379FD |
| 8086:27c9 | 8086:27c9 | Intel      | NM10/ICH7 Family USB UHCI... | 21    | uhci       | 8D59B379FD |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 20    | ohci       | CEC3CB521D |
| 8086:1c26 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 20    | ehci       | 9301BD0E0F |
| 8086:1c2d | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 20    | ehci       | 9301BD0E0F |
| 8086:27ca | 8086:27ca | Intel      | NM10/ICH7 Family USB UHCI... | 20    | uhci       | 8D59B379FD |
| 8086:27cc | 8086:27cc | Intel      | NM10/ICH7 Family USB2 EHC... | 20    | ehci       | 8D59B379FD |
| 8086:8c26 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 20    | ehci       | BF53DF8658 |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 19    | xhci       | EECEB3A84C |
| 8086:8c2d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 19    | ehci       | BF53DF8658 |
| 8086:8c31 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 19    | xhci       | BF53DF8658 |
| 8086:1c26 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 18    | ehci       | C44BE632D3 |
| 8086:1c2d | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 18    | ehci       | C44BE632D3 |
| 8086:1f2c | 8086:7270 | Intel      | Atom processor C2000 USB ... | 18    | ehci       | 7E6BEE8355 |
| 8086:27cb | 8086:27cb | Intel      | NM10/ICH7 Family USB UHCI... | 18    | uhci       | 8D59B379FD |
| 1022:7807 | 103c:213d | AMD        | FCH USB OHCI Controller      | 17    | ohci       | DE3D6DCDF5 |
| 1022:7808 | 103c:213d | AMD        | FCH USB EHCI Controller      | 17    | ehci       | DE3D6DCDF5 |
| 1022:7814 | 103c:213d | AMD        | FCH USB XHCI Controller      | 17    | xhci       | DE3D6DCDF5 |
| 8086:1e26 | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 17    | ehci       | A379C24586 |
| 8086:1e2d | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 17    | ehci       | A379C24586 |
| 8086:3a34 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 17    | uhci       | 65893EAA25 |
| 8086:3a35 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 17    | uhci       | 65893EAA25 |
| 8086:3a36 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 17    | uhci       | 65893EAA25 |
| 8086:3a37 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 17    | uhci       | 65893EAA25 |
| 8086:3a38 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 17    | uhci       | 65893EAA25 |
| 8086:3a39 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 17    | uhci       | 65893EAA25 |
| 8086:3a3a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 17    | ehci       | 65893EAA25 |
| 8086:3a3c | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 17    | ehci       | 65893EAA25 |
| 8086:a12f | 1043:8694 | Intel      | 100 Series/C230 Series Ch... | 17    | xhci       | 7F9CDC62A2 |
| 103c:3300 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 16    | uhci       | 82D00F440D |
| 8086:1c26 | 15d9:0624 | Intel      | 6 Series/C200 Series Chip... | 15    | ehci       | 08EB9E54FE |
| 8086:1c2d | 15d9:0624 | Intel      | 6 Series/C200 Series Chip... | 15    | ehci       | 08EB9E54FE |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 15    | ehci       | EECEB3A84C |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 15    | ehci       | EECEB3A84C |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 15    | xhci       | EECEB3A84C |
| 8086:3a34 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 15    | uhci       | 82D00F440D |
| 8086:3a35 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 15    | uhci       | 82D00F440D |
| 8086:3a36 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 15    | uhci       | 82D00F440D |
| 8086:3a3a | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 15    | ehci       | 82D00F440D |
| 8086:5aa8 | 1849:5aa8 | Intel      | Celeron N3350/Pentium N42... | 15    | xhci       | C9218EE21D |
| 1b21:1242 | 1043:8675 | ASMedia... | ASM1142 USB 3.1 Host Cont... | 14    | xhci       | E13854338F |
| 8086:1c26 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 14    | ehci       | 66743A51CC |
| 8086:1c2d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 14    | ehci       | 66743A51CC |
| 8086:3a39 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 14    | uhci       | 82D00F440D |
| 8086:8c26 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 14    | ehci       | B5FE536096 |
| 8086:8c2d | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 14    | ehci       | B5FE536096 |
| 8086:8c31 | 1028:05a4 | Intel      | 8 Series/C220 Series Chip... | 14    | xhci       | B5FE536096 |
| 1b21:1142 | 1043:85bf | ASMedia... | ASM1042A USB 3.0 Host Con... | 13    | xhci       | D305B914E2 |
| 8086:9d2f | 8086:9d2f | Intel      | Sunrise Point-LP USB 3.0 ... | 13    | xhci       | 045DFAD837 |
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 12    | ehci       | C7668C5B0C |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 12    | ohci       | C7668C5B0C |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 12    | ohci       | C7668C5B0C |
| 8086:1e31 | 1458:5007 | Intel      | 7 Series/C210 Series Chip... | 12    | xhci       | D3742D3898 |
| 8086:8c26 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 12    | ehci       | 09BA719AA7 |
| 8086:8c26 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 12    | ehci       | 6A22DA5C5D |
| 8086:8c2d | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 12    | ehci       | 09BA719AA7 |
| 8086:8c2d | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 12    | ehci       | 6A22DA5C5D |
| 8086:8c31 | 1028:0612 | Intel      | 8 Series/C220 Series Chip... | 12    | xhci       | 09BA719AA7 |
| 8086:8c31 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 12    | xhci       | 6A22DA5C5D |
| 1022:145f | 1043:8747 | AMD        | Zeppelin USB 3.0 Host con... | 11    | xhci       | EDEBE87739 |
| 8086:1c26 | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 11    | ehci       | B73E45E0DF |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 11    | ehci       | 193936B5CA |
| 8086:1c2d | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 11    | ehci       | B73E45E0DF |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 11    | ehci       | 193936B5CA |
| 8086:2830 | 8086:2830 | Intel      | 82801H (ICH8 Family) USB ... | 11    | uhci       | 901FAAE6DF |
| 8086:2831 | 8086:2831 | Intel      | 82801H (ICH8 Family) USB ... | 11    | uhci       | 901FAAE6DF |
| 8086:2836 | 8086:2836 | Intel      | 82801H (ICH8 Family) USB2... | 11    | ehci       | 901FAAE6DF |
| 8086:2934 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 11    | uhci       | BDBD2D0A05 |
| 8086:2935 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 11    | uhci       | BDBD2D0A05 |
| 8086:2936 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 11    | uhci       | BDBD2D0A05 |
| 8086:2937 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 11    | uhci       | BDBD2D0A05 |
| 8086:2938 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 11    | uhci       | BDBD2D0A05 |
| 8086:2939 | 17aa:20f0 | Intel      | 82801I (ICH9 Family) USB ... | 11    | uhci       | BDBD2D0A05 |
| 8086:293a | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 11    | ehci       | BDBD2D0A05 |
| 8086:293c | 17aa:20f1 | Intel      | 82801I (ICH9 Family) USB2... | 11    | ehci       | BDBD2D0A05 |
| 8086:8c26 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | ehci       | F2C6B4AA4D |
| 8086:8c26 | 8086:8c26 | Intel      | 8 Series/C220 Series Chip... | 11    | ehci       | FE8DC15588 |
| 8086:8c2d | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | ehci       | F2C6B4AA4D |
| 8086:8c2d | 8086:8c2d | Intel      | 8 Series/C220 Series Chip... | 11    | ehci       | FE8DC15588 |
| 8086:8c31 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | xhci       | F2C6B4AA4D |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 45    |            | 162F499C31 |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 45    |            | 162F499C31 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 37    |            | BD63DE17B0 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 31    |            | BD63DE17B0 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 19    |            | 10D9E99990 |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 19    |            | 10D9E99990 |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 13    |            | EDEBE87739 |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 13    |            | EDEBE87739 |
| 0000:0000 |           |            |                              | 10    |            | 6B06C67610 |
| 1022:15e6 | 1022:15e4 | AMD        | Raven/Raven2/Renoir Non-S... | 7     |            | EF44FCD726 |
| 8086:9d35 | 17aa:2238 | Intel      | Sunrise Point-LP Integrat... | 6     |            | 821C81E652 |
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 5     |            | 9D69197550 |
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 4     |            | 5ACC629D2E |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 4     |            | 533B1E078E |
| 8086:a1ec | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 4     |            | 027AFA82FF |
| 8086:a1ed | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 4     |            | 027AFA82FF |
| 1022:1455 | 1462:7b86 | AMD        | Zeppelin/Renoir PCIe Dumm... | 3     |            | ED656E816F |
| 1022:145a | 1462:7b86 | AMD        | Zeppelin/Raven/Raven2 PCI... | 3     |            | ED656E816F |
| 8086:8d7c | 1043:8600 | Intel      | C610/X99 series chipset SPSR | 3     |            | 6B06C67610 |
| 8086:8d7c | 15d9:0832 | Intel      | C610/X99 series chipset SPSR | 3     |            | F36F748797 |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 3     |            | EF131C774D |
| 8086:a1ec | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1ec | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a1ed | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 1022:1455 | 1025:1246 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 9E03A76684 |
| 1022:145a | 1002:15dd | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 421DA89770 |
| 1022:145a | 1025:1246 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 9E03A76684 |
| 1022:1485 | 1043:87cb | AMD        | Starship/Matisse Reserved... | 2     |            | 02F241B7D7 |
| 1022:1485 | 1043:8808 | AMD        | Starship/Matisse Reserved... | 2     |            | 8D78068CA7 |
| 1022:148a | 1043:87cb | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 02F241B7D7 |
| 1022:148a | 1043:8808 | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 8D78068CA7 |
| 8086:8d7c |           | Intel      | C610/X99 series chipset SPSR | 2     |            | 289D61B1B2 |
| 8086:8d7c | 15d9:0834 | Intel      | C610/X99 series chipset SPSR | 2     |            | 6452298012 |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 2     |            | 14A919AB3F |
| 8086:8d7c | 1734:1201 | Intel      | C610/X99 series chipset SPSR | 2     |            | 7A9D95B303 |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 2     |            | 93A8B87E1C |
| 8086:9d35 | 17aa:2259 | Intel      | Sunrise Point-LP Integrat... | 2     |            | 9773669778 |
| 8086:9d35 | 17aa:506d | Intel      | Sunrise Point-LP Integrat... | 2     |            | DAB0CA2417 |
| 8086:a135 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 2     |            | B34EE32475 |
| 8086:a1ec | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1ec | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1ec | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a1ed | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 1022:1455 | 1462:7b89 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 1123CB92BA |
| 1022:1455 | 1462:7b90 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | E7BC61FACB |
| 1022:1455 | 1462:7c02 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | A87473149B |
| 1022:145a | 1002:15d8 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 9F780AFF14 |
| 1022:145a | 1462:7b89 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 1123CB92BA |
| 1022:145a | 1462:7b90 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | E7BC61FACB |
| 1022:145a | 1462:7c02 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | A87473149B |
| 1022:1485 | 1043:87e2 | AMD        | Starship/Matisse Reserved... | 1     |            | 94C953E866 |
| 1022:1485 | 1458:1000 | AMD        | Starship/Matisse Reserved... | 1     |            | 93E2466FC6 |
| 1022:1485 | 1462:7b86 | AMD        | Starship/Matisse Reserved... | 1     |            | 4CF3DD682B |
| 1022:1485 | 1462:7b89 | AMD        | Starship/Matisse Reserved... | 1     |            | 6BFF2DB7E3 |
| 1022:1485 | 1462:7c02 | AMD        | Starship/Matisse Reserved... | 1     |            | B429D784D9 |
| 1022:1485 | 1462:7c36 | AMD        | Starship/Matisse Reserved... | 1     |            | 207D91889F |
| 1022:1485 | 1558:50f0 | AMD        | Starship/Matisse Reserved... | 1     |            | 0AC6AED43B |
| 1022:1485 | 1849:148a | AMD        | Starship/Matisse Reserved... | 1     |            | 739DB7D4A8 |
| 1022:148a | 1043:87e2 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 94C953E866 |
| 1022:148a | 1458:1000 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 93E2466FC6 |
| 1022:148a | 1462:7b86 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 4CF3DD682B |
| 1022:148a | 1462:7b89 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 6BFF2DB7E3 |
| 1022:148a | 1462:7c02 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | B429D784D9 |
| 1022:148a | 1462:7c36 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 207D91889F |
| 1022:148a | 1558:50f0 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 0AC6AED43B |
| 1022:148a | 1849:148a | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 739DB7D4A8 |
| 1022:15e6 | 1458:1000 | AMD        | Raven/Raven2/Renoir Non-S... | 1     |            | B51CB672A4 |
| 1028:0011 | 1028:0011 | Dell       | Remote Access Card 4 Daug... | 1     |            | BB83934454 |
| 1028:0012 | 1028:0012 | Dell       | Remote Access Card 4 Daug... | 1     | uart       | BB83934454 |
| 1028:0014 | 1028:0014 | Dell       | Remote Access Card 4 Daug... | 1     |            | BB83934454 |
| 103c:193f | 103c:3381 | Hewlett... | Dynamic Smart Array B140i    | 1     |            | 533B1E078E |
| 106b:003b |           | Apple      | UniNorth/Intrepid ATA/100    | 1     | ata        | 4B7ABCF4FB |
| 106b:003e |           | Apple      | KeyLargo/Intrepid Mac I/O    | 1     | macio      | 4B7ABCF4FB |
| 10b9:7101 |           | ULi Ele... | M7101 Power Management Co... | 1     |            | 7A4C568ACE |
| 15ec:5000 | 15ec:5000 | Beckhoff   |                              | 1     |            | AB8247D8B5 |
| 8086:3591 | 1734:1041 | Intel      | E7525/E7520 Error Reporti... | 1     |            | ADB972BF8E |
| 8086:8d7c | 1028:0600 | Intel      | C610/X99 series chipset SPSR | 1     |            | 4389B1CE81 |
| 8086:8d7c | 1028:0617 | Intel      | C610/X99 series chipset SPSR | 1     |            | 5FFEB3D23E |
| 8086:8d7c | 1028:0619 | Intel      | C610/X99 series chipset SPSR | 1     |            | DDDF168DB9 |
| 8086:8d7c | 1028:061a | Intel      | C610/X99 series chipset SPSR | 1     |            | FCD1A34E85 |
| 8086:8d7c | 1028:0627 | Intel      | C610/X99 series chipset SPSR | 1     |            | 4710D6000D |
| 8086:8d7c | 103c:212b | Intel      | C610/X99 series chipset SPSR | 1     |            | 7FE9D2C508 |
| 8086:8d7c | 1458:7270 | Intel      | C610/X99 series chipset SPSR | 1     |            | 7766E24B52 |
| 8086:8d7c | 1462:7885 | Intel      | C610/X99 series chipset SPSR | 1     |            | 9B2421D9D5 |
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 1     |            | 3C7D64A2CB |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 1     |            | 223968434F |
| 8086:8d7c | 15d9:0835 | Intel      | C610/X99 series chipset SPSR | 1     |            | B44FE94131 |
| 8086:8d7c | 15d9:0844 | Intel      | C610/X99 series chipset SPSR | 1     |            | DFB2F9C5AB |
| 8086:9d24 |           | Intel      | Skylake-U/Y SPI Controller   | 1     |            | 4FFE68C199 |
| 8086:9d35 | 1028:07eb | Intel      | Sunrise Point-LP Integrat... | 1     |            | DC37C53E48 |
| 8086:9d35 | 1028:0809 | Intel      | Sunrise Point-LP Integrat... | 1     |            | 0B335F5918 |
| 8086:9d35 | 103c:81a9 | Intel      | Sunrise Point-LP Integrat... | 1     |            | F27578615F |
| 8086:9d35 | 103c:827e | Intel      | Sunrise Point-LP Integrat... | 1     |            | C8C11A071D |
| 8086:9d35 | 103c:83c8 | Intel      | Sunrise Point-LP Integrat... | 1     |            | ADC45416CE |
| 8086:9d35 | 152d:1147 | Intel      | Sunrise Point-LP Integrat... | 1     |            | E550E3BA04 |
| 8086:a135 | 15d9:0896 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5044047B6E |
| 8086:a1ec | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | CA41B3F700 |
| 8086:a1ec | 15d9:1b35 | Intel      | C620 Series Chipset Famil... | 1     |            | 9A967C1DCA |

