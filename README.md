Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed pciconf reports collected by BSD users at https://bsd-hardware.info.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 234.

Contents
--------

1. [ About ](#about)
2. [ PCI Devices ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Network ](#network-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Signal processing ](#signal-processing-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
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
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 13    | hostb      | 8936B9252C |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 10    | hostb      | 8936B9252C |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 10    | hostb      | 8936B9252C |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 10    | hostb      | 8936B9252C |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 10    | hostb      | 8936B9252C |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 10    | hostb      | 8936B9252C |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 10    | hostb      | 8936B9252C |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 10    | hostb      | 8936B9252C |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 10    | hostb      | 8936B9252C |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 8     | pcib       | 73F1BC75E0 |
| 1022:43c7 | 1b21:3306 | AMD        | 400 Series Chipset PCIe Port | 8     | pcib       | C00D9E9C92 |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 7     | pcib       | 8936B9252C |
| 1022:43c6 | 1b21:0201 | AMD        | 400 Series Chipset PCIe B... | 7     | pcib       | C00D9E9C92 |
| 1022:43b4 | 1b21:3306 | AMD        | 300 Series Chipset PCIe Port | 6     | pcib       | 8936B9252C |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 5     | hostb      | D99AE1AAD1 |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 5     | hostb      | D99AE1AAD1 |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 5     | hostb      | D99AE1AAD1 |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 5     | hostb      | D99AE1AAD1 |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 5     | hostb      | D99AE1AAD1 |
| 1022:790e | 1458:5001 | AMD        | FCH LPC Bridge               | 5     | isab       | 6BAF39851A |
| 8086:244e | 1043:82d4 | Intel      | 82801 PCI Bridge             | 5     | pcib       | 130AB3C706 |
| 1002:439d | 1002:439d | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 4     | isab       | 73F1BC75E0 |
| 1002:43a0 |           | AMD        | SB700/SB800/SB900 PCI to ... | 4     | pcib       | 73F1BC75E0 |
| 1022:1440 |           | AMD        | Matisse Device 24: Functi... | 4     | hostb      | C00D9E9C92 |
| 1022:1441 |           | AMD        | Matisse Device 24: Functi... | 4     | hostb      | C00D9E9C92 |
| 1022:1442 |           | AMD        | Matisse Device 24: Functi... | 4     | hostb      | C00D9E9C92 |
| 1022:1443 |           | AMD        | Matisse Device 24: Functi... | 4     | hostb      | C00D9E9C92 |
| 1022:1444 |           | AMD        | Matisse Device 24: Functi... | 4     | hostb      | C00D9E9C92 |
| 1022:1445 |           | AMD        | Matisse Device 24: Functi... | 4     | hostb      | C00D9E9C92 |
| 1022:1446 |           | AMD        | Matisse Device 24: Functi... | 4     | hostb      | C00D9E9C92 |
| 1022:1447 |           | AMD        | Matisse Device 24: Functi... | 4     | hostb      | C00D9E9C92 |
| 1022:1450 | 1022:1450 | AMD        | Family 17h (Models 00h-0f... | 4     | hostb      | 8936B9252C |
| 1022:1453 | 1022:1453 | AMD        | Family 17h (Models 00h-0f... | 4     | pcib       | C7C50D64CF |
| 1022:1482 |           | AMD        | Starship/Matisse PCIe Dum... | 4     | hostb      | C00D9E9C92 |
| 1022:1484 | 1022:1484 | AMD        | Starship/Matisse Internal... | 4     | pcib       | C00D9E9C92 |
| 1022:1600 |           | AMD        | Family 15h Processor Func... | 4     | hostb      | 73F1BC75E0 |
| 1022:1601 |           | AMD        | Family 15h Processor Func... | 4     | hostb      | 73F1BC75E0 |
| 1022:1602 |           | AMD        | Family 15h Processor Func... | 4     | hostb      | 73F1BC75E0 |
| 1022:1603 |           | AMD        | Family 15h Processor Func... | 4     | hostb      | 73F1BC75E0 |
| 1022:1604 |           | AMD        | Family 15h Processor Func... | 4     | hostb      | 73F1BC75E0 |
| 1022:1605 |           | AMD        | Family 15h Processor Func... | 4     | hostb      | 73F1BC75E0 |
| 8086:3a16 | 1043:82d4 | Intel      | 82801JIR (ICH10R) LPC Int... | 4     | isab       | 130AB3C706 |
| 1022:1450 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 3     | hostb      | 20FAC3B208 |
| 1022:1453 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 3     | pcib       | 20FAC3B208 |
| 1022:15db |           | AMD        | Raven/Raven2 Internal PCI... | 3     | pcib       | 6BAF39851A |
| 1022:15dc |           | AMD        | Raven/Raven2 Internal PCI... | 3     | pcib       | 6BAF39851A |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 3     | hostb      | 6BAF39851A |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 3     | hostb      | 6BAF39851A |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 3     | hostb      | 6BAF39851A |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 3     | hostb      | 6BAF39851A |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 3     | hostb      | 6BAF39851A |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 3     | hostb      | 6BAF39851A |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 3     | hostb      | 6BAF39851A |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 3     | hostb      | 6BAF39851A |
| 1022:43b2 | 1b21:0201 | AMD        | FCH PCIe Port C (Switch USP) | 3     | pcib       | A34217EC03 |
| 1022:790e | 1043:8747 | AMD        | FCH LPC Bridge               | 3     | isab       | 20FAC3B208 |
| 1b21:1080 | 1043:8489 | ASMedia... | ASM1083/1085 PCIe to PCI ... | 3     | pcib       | 1C88AE5A1F |
| 8086:0044 | 17aa:2193 | Intel      | Core Processor DRAM Contr... | 3     | hostb      | 0087B62853 |
| 8086:0154 | 17aa:21fb | Intel      | 3rd Gen Core processor DR... | 3     | hostb      | F4E8FFB5DC |
| 8086:0c00 | 1043:8534 | Intel      | 4th Gen Core Processor DR... | 3     | hostb      | 1C88AE5A1F |
| 8086:0c01 | 1043:8534 | Intel      | Xeon E3-1200 v3/4th Gen C... | 3     | pcib       | 1C88AE5A1F |
| 8086:1e10 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 3     | pcib       | 26729F77DC |
| 8086:1e10 | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     | pcib       | F4E8FFB5DC |
| 8086:1e12 | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 3     | pcib       | F4E8FFB5DC |
| 8086:1e14 | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 3     | pcib       | F4E8FFB5DC |
| 8086:1e55 | 17aa:21fb | Intel      | QM77 Express Chipset LPC ... | 3     | isab       | F4E8FFB5DC |
| 8086:2448 | 17aa:2165 | Intel      | 82801 Mobile PCI Bridge      | 3     | pcib       | 0087B62853 |
| 8086:2c62 | 17aa:2196 | Intel      | Core Processor QuickPath ... | 3     | hostb      | 0087B62853 |
| 8086:2d01 | 17aa:2196 | Intel      | Core Processor QuickPath ... | 3     | hostb      | 0087B62853 |
| 8086:2d10 | 17aa:2196 | Intel      | Core Processor QPI Link 0    | 3     | hostb      | 0087B62853 |
| 8086:2d11 | 17aa:2196 | Intel      | 1st Generation Core i3/5/... | 3     | hostb      | 0087B62853 |
| 8086:2d12 | 17aa:2196 | Intel      | 1st Generation Core i3/5/... | 3     | hostb      | 0087B62853 |
| 8086:2d13 | 17aa:2196 | Intel      | 1st Generation Core i3/5/... | 3     | hostb      | 0087B62853 |
| 8086:2e20 | 1043:82d3 | Intel      | 4 Series Chipset DRAM Con... | 3     | hostb      | 130AB3C706 |
| 8086:2e21 | 1043:82d3 | Intel      | 4 Series Chipset PCI Expr... | 3     | pcib       | 130AB3C706 |
| 8086:3a40 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcib       | 130AB3C706 |
| 8086:3a48 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcib       | 130AB3C706 |
| 8086:3a4a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) PC... | 3     | pcib       | 130AB3C706 |
| 8086:3b42 | 17aa:2164 | Intel      | 5 Series/3400 Series Chip... | 3     | pcib       | 0087B62853 |
| 8086:3b44 | 17aa:2164 | Intel      | 5 Series/3400 Series Chip... | 3     | pcib       | 0087B62853 |
| 1002:43a3 |           | AMD        | SB900 PCI to PCI bridge (... | 2     | pcib       | 33782EF7F1 |
| 1002:5a14 | 1002:5a14 | AMD        | RD9x0/RX980 Host Bridge      | 2     | hostb      | 73F1BC75E0 |
| 1002:5a16 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 2     | pcib       | 73F1BC75E0 |
| 1002:5a18 | 1002:5a14 | AMD        | RD890/RD9x0/RX980 PCI to ... | 2     | pcib       | 73F1BC75E0 |
| 1022:1439 | 1022:1234 | AMD        | Family 16h Processor Func... | 2     | pcib       | DC1C86095F |
| 1022:1454 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 2     | pcib       | 44681211FF |
| 1022:1480 | 1022:1450 | AMD        | Starship/Matisse Root Com... | 2     | hostb      | 8D60BA9DFB |
| 1022:1483 | 1022:1453 | AMD        | Starship/Matisse GPP Bridge  | 2     | pcib       | 8D60BA9DFB |
| 1022:15d0 | 1022:15d0 | AMD        | Raven/Raven2 Root Complex    | 2     | hostb      | 6BAF39851A |
| 1022:15d3 | 1022:1453 | AMD        | Raven/Raven2 PCIe GPP Bri... | 2     | pcib       | 6BAF39851A |
| 1022:43b1 | 1b21:0201 | AMD        | X399 Series Chipset PCIe ... | 2     | pcib       | 8936B9252C |
| 1022:780e | 1022:780e | AMD        | FCH LPC Bridge               | 2     | isab       | DC1C86095F |
| 1022:9600 | 1022:9600 | AMD        | RS780 Host Bridge            | 2     | hostb      | CC5724ACBC |
| 1022:9602 | 1022:9602 | AMD        | RS780/RS880 PCI to PCI br... | 2     | pcib       | E8BED535A9 |
| 1022:9603 | 1022:9600 | AMD        | RS780 PCI to PCI bridge (... | 2     | pcib       | CC5724ACBC |
| 1022:9609 | 1022:9600 | AMD        | RS780/RS880 PCI to PCI br... | 2     | pcib       | CC5724ACBC |
| 1a03:1150 | 15d9:0884 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 2     | pcib       | 18EA6EC987 |
| 1a03:1150 | 1a03:1150 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 2     | pcib       | 1DB4784753 |
| 8086:0104 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 2     | hostb      | 324265FE3F |
| 8086:0104 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 2     | hostb      | A95465CDDA |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 8086:2072 | Realtek... | RTS5229 PCI Express Card ... | 2     |            | E44A7E90E0 |
| 10ec:525a | 1028:075b | Realtek... | RTS525A PCI Express Card ... | 2     |            | 1887B030C4 |
| 10ec:5209 | 104d:90ac | Realtek... | RTS5209 PCI Express Card ... | 1     |            | 9A751DDFD8 |
| 10ec:5227 | 17aa:220e | Realtek... | RTS5227 PCI Express Card ... | 1     |            | 9001A6EA5B |
| 10ec:5227 | 17aa:2214 | Realtek... | RTS5227 PCI Express Card ... | 1     |            | C65CDB97DE |
| 10ec:5227 | 17aa:5034 | Realtek... | RTS5227 PCI Express Card ... | 1     |            | F83F765AB3 |
| 10ec:5229 | 1043:202f | Realtek... | RTS5229 PCI Express Card ... | 1     |            | DC7BB56859 |
| 10ec:522a | 103c:8079 | Realtek... | RTS522A PCI Express Card ... | 1     |            | 6C7374D0AB |
| 10ec:522a | 17aa:5050 | Realtek... | RTS522A PCI Express Card ... | 1     |            | DFD9A97EFC |
| 10ec:522a | 17aa:5062 | Realtek... | RTS522A PCI Express Card ... | 1     |            | 7DEF094AFB |
| 10ec:522a | 17aa:5122 | Realtek... | RTS522A PCI Express Card ... | 1     |            | 010DB0AED4 |
| 10ec:5249 | 103c:1909 | Realtek... | RTS5249 PCI Express Card ... | 1     |            | 3E9076F244 |
| 10ec:5249 | 103c:2255 | Realtek... | RTS5249 PCI Express Card ... | 1     |            | D615B5020D |
| 10ec:525a | 1028:06de | Realtek... | RTS525A PCI Express Card ... | 1     |            | 1A7976D306 |
| 10ec:525a | 1558:65d1 | Realtek... | RTS525A PCI Express Card ... | 1     |            | 96FCD8FC28 |
| 10ec:525a | 17aa:2238 | Realtek... | RTS525A PCI Express Card ... | 1     |            | 68840C222B |
| 10ec:525a | 17aa:224d | Realtek... | RTS525A PCI Express Card ... | 1     |            | 81EFA4B3D3 |
| 10ec:525a | 17aa:224f | Realtek... | RTS525A PCI Express Card ... | 1     |            | BB2FCF8D92 |
| 10ec:5260 | 1028:0926 | Realtek... | RTS5260 PCI Express Card ... | 1     |            | AA891D8F27 |
| 10ec:5287 | 1558:1313 | Realtek... | RTL8411B PCI Express Card... | 1     |            | 9649F2D700 |
| 1217:8221 | 1028:0492 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 1     | sdhci_pci  | 2EBFA76C28 |
| 1217:8520 | 1028:05ca | O2 Micro   | SD/MMC Card Reader Contro... | 1     | sdhci_pci  | 1DE87C0000 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e3a | 1458:1c3a | Intel      | 7 Series/C216 Chipset Fam... | 3     |            | 26729F77DC |
| 8086:1e3a | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     |            | F4E8FFB5DC |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 3     |            | 0087B62853 |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     |            | 324265FE3F |
| 8086:1c3a | 1458:1c3a | Intel      | 6 Series/C200 Series Chip... | 2     |            | C06E03CDA0 |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     |            | A95465CDDA |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     |            | 7042848932 |
| 8086:1e3a | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 2     |            | 0F7697B73A |
| 8086:319a | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | E44A7E90E0 |
| 8086:5a9a | 1849:5a9a | Intel      | Celeron N3350/Pentium N42... | 2     |            | 1C8E18B787 |
| 8086:8c3a | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 2     |            | D65F5372EC |
| 8086:9d3a | 1028:075b | Intel      | Sunrise Point-LP CSME HEC... | 2     |            | 1887B030C4 |
| 8086:a13a | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:a13b | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:a1ba | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 8086:a1bb | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 8086:a1be | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 10ec:816a | 17aa:5122 | Realtek... | Virtual COM1                 | 1     |            | 010DB0AED4 |
| 10ec:816b | 17aa:5122 | Realtek... | RealManage COM2              | 1     |            | 010DB0AED4 |
| 1415:c110 | 1415:c110 | Oxford ... | PCI Express ECP Parallel ... | 1     | ppc        | B1594A3F62 |
| 14a1:0008 | 14a1:0008 | Systembase | Enhanced Serial Multi-8/P... | 1     | puc        | 29CD63ACAA |
| 8086:1c3a | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 1     |            | 81F39F3061 |
| 8086:1c3a | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     |            | C240E3A1EA |
| 8086:1c3a | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1     |            | 94C4617D4E |
| 8086:1c3a | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     |            | 6CF7F9EA4B |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     |            | 05ED5EB1E4 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     |            | DC34D6FD02 |
| 8086:1c3b | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     |            | 6CF7F9EA4B |
| 8086:1c3d | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     | uart       | C240E3A1EA |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     | uart       | 05ED5EB1E4 |
| 8086:1d3a | 15d9:0703 | Intel      | C600/X79 series chipset M... | 1     |            | 1F4D1E4607 |
| 8086:1d3b | 15d9:0703 | Intel      | C600/X79 series chipset M... | 1     |            | 1F4D1E4607 |
| 8086:1e3a | 1028:0535 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 04CD35A77B |
| 8086:1e3a | 1028:053e | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | A7761EE829 |
| 8086:1e3a | 1043:1467 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | D14C9C0372 |
| 8086:1e3a | 104d:90ac | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 9A751DDFD8 |
| 8086:1e3a | 17aa:21f9 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 8ED0FEE673 |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 8060B3FFE1 |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 1     | uart       | 8060B3FFE1 |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 1     | uart       | EAB6164233 |
| 8086:3b64 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 239EEA83C6 |
| 8086:3b64 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 1     |            | 534617FE54 |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 6A6B06FC67 |
| 8086:3b67 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 1     | uart       | 534617FE54 |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 1     | uart       | 0087B62853 |
| 8086:8c3a | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 3E9076F244 |
| 8086:8c3a | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 1     |            | E10B99BE8B |
| 8086:8c3a | 1462:7887 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 5D38B05178 |
| 8086:8c3a | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     |            | 9001A6EA5B |
| 8086:8c3a | 17aa:30a6 | Intel      | 8 Series/C220 Series Chip... | 1     |            | DEA751EDF7 |
| 8086:8c3d | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     | uart       | 3E9076F244 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     | uart       | 9001A6EA5B |
| 8086:8c3d | 17aa:30a6 | Intel      | 8 Series/C220 Series Chip... | 1     | uart       | DEA751EDF7 |
| 8086:8d3a | 15d9:0835 | Intel      | C610/X99 series chipset M... | 1     |            | B44FE94131 |
| 8086:8d3b | 15d9:0835 | Intel      | C610/X99 series chipset M... | 1     |            | B44FE94131 |
| 8086:9c3a | 17aa:2214 | Intel      | 8 Series HECI #0             | 1     |            | C65CDB97DE |
| 8086:9c3a | 8086:2054 | Intel      | 8 Series HECI #0             | 1     |            | 90E967F56B |
| 8086:9cba | 1028:0655 | Intel      | Wildcat Point-LP MEI Cont... | 1     |            | B38C2A2E8F |
| 8086:9cba | 1458:1000 | Intel      | Wildcat Point-LP MEI Cont... | 1     |            | 07036EAB43 |
| 8086:9d3a | 103c:8079 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 6C7374D0AB |
| 8086:9d3a | 1558:1313 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 9649F2D700 |
| 8086:9d3a | 17aa:2238 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 68840C222B |
| 8086:9d3a | 17aa:224f | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | BB2FCF8D92 |
| 8086:9d3a | 17aa:3844 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 709A3DB7DE |
| 8086:9d3a | 17aa:5062 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 7DEF094AFB |
| 8086:9d3a | 8086:2063 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 6B854263E7 |
| 8086:9d3d | 17aa:5062 | Intel      | Sunrise Point-LP Active M... | 1     |            | 7DEF094AFB |
| 8086:a13a | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |
| 8086:a13a | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a13a | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DC7BB56859 |
| 8086:a13a | 1071:0758 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 528E378206 |
| 8086:a13a | 1458:1c3a | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2FC2952380 |
| 8086:a13a | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     |            | 81EFA4B3D3 |
| 8086:a13a | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DFD9A97EFC |
| 8086:a13b | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |
| 8086:a13d | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a13d | 1071:0758 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 528E378206 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 6     |            | 8936B9252C |
| 1022:1456 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 2     |            | 44681211FF |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 2     |            | 8D60BA9DFB |
| 1022:15df | 1022:15df | AMD        | Family 17h (Models 10h-1f... | 2     |            | 6BAF39851A |
| 8086:0f18 | 1849:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 2     |            | 8787D15BC5 |
| 1022:1456 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 310BD9E4AF |
| 1022:15df | 17aa:5122 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 010DB0AED4 |
| 8086:2298 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 55BE2FAB24 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8024 | 1458:1000 | Texas I... | TSB43AB23 IEEE-1394a-2000... | 2     | fwohci     | 66BCE86F33 |
| 11c1:5811 | 103c:158a | LSI        | FW322/323 [TrueFire] 1394... | 2     | fwohci     | DFFF5DD2F9 |
| 11c1:5811 | 1043:8294 | LSI        | FW322/323 [TrueFire] 1394... | 2     | fwohci     | 130AB3C706 |
| 104c:8023 | 1043:808b | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     | fwohci     | 5B1DC84DA5 |
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 1     |            | DC34D6FD02 |
| 1106:3403 | 1025:0157 | VIA Tec... | VT6315 Series Firewire Co... | 1     | fwohci     | DB1E7A52B9 |
| 1106:3403 | 1043:8384 | VIA Tec... | VT6315 Series Firewire Co... | 1     | fwohci     | 6EB355EABD |
| 1106:3403 | 1106:3403 | VIA Tec... | VT6315 Series Firewire Co... | 1     | fwohci     | 66BBED8D59 |
| 1180:0552 | 1043:1197 | Ricoh      | R5C552 IEEE 1394 Controller  | 1     |            | 1F098AC490 |
| 1180:0552 | 1043:1897 | Ricoh      | R5C552 IEEE 1394 Controller  | 1     | fwohci     | 0D292BCA2F |
| 1180:0552 | 17aa:201e | Ricoh      | R5C552 IEEE 1394 Controller  | 1     |            | F08ACC6929 |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | 2FD46CB7C7 |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 1     |            | 0087B62853 |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 1     |            | 05ED5EB1E4 |
| 11c1:5811 | 103c:130a | LSI        | FW322/323 [TrueFire] 1394... | 1     |            | B43DB1D84E |
| 1217:13f7 | 1028:053e | O2 Micro   | 1394 OHCI Compliant Host ... | 1     |            | A7761EE829 |
| 197b:2380 | 103c:1631 | JMicron... | IEEE 1394 Host Controller    | 1     |            | C240E3A1EA |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0166 | 17aa:21fb | Intel      | 3rd Gen Core processor Gr... | 3     | vgapci     | F4E8FFB5DC |
| 1002:67df | 1da2:e353 | AMD        | Ellesmere [Radeon RX 470/... | 2     | vgapci     | A34217EC03 |
| 10de:06e4 | 1043:8266 | Nvidia     | G98 [GeForce 8400 GS Rev. 2] | 2     | vgapci     | 130AB3C706 |
| 10de:0fc1 | 1043:83f3 | Nvidia     | GK107 [GeForce GT 640]       | 2     | vgapci     | 94C4617D4E |
| 10de:1380 | 1462:3102 | Nvidia     | GM107 [GeForce GTX 750 Ti]   | 2     | vgapci     | C039FF6AB2 |
| 1a03:2000 | 15d9:0884 | ASPEED ... | ASPEED Graphics Family       | 2     | vgapci     | 18EA6EC987 |
| 1a03:2000 | 15d9:0981 | ASPEED ... | ASPEED Graphics Family       | 2     | vgapci     | 1DB4784753 |
| 8086:0046 | 17aa:21c1 | Intel      | Core Processor Integrated... | 2     | vgapci     | 6394AE37A8 |
| 8086:0126 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 2     | vgapci     | A95465CDDA |
| 8086:0152 | 1458:d000 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 2     | vgapci     | A209F74444 |
| 8086:0f31 | 1849:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 2     | vgapci     | 8787D15BC5 |
| 8086:3185 | 8086:2072 | Intel      | UHD Graphics 605             | 2     | vgapci     | E44A7E90E0 |
| 8086:5916 | 1028:075b | Intel      | HD Graphics 620              | 2     | vgapci     | 1887B030C4 |
| 1002:15dd | 17aa:5122 | AMD        | Raven Ridge [Radeon Vega ... | 1     | vgapci     | 010DB0AED4 |
| 1002:515e | 103c:31fb | AMD        | ES1000                       | 1     | vgapci     | 4EBC960E9C |
| 1002:515e | 1043:81de | AMD        | ES1000                       | 1     | vgapci     | C1F04B3A84 |
| 1002:515e | 8086:3476 | AMD        | ES1000                       | 1     | vgapci     | 9A893E2CC9 |
| 1002:5b60 | 1043:005c | AMD        | RV370 [Radeon X300]          | 1     | vgapci     | 5B1DC84DA5 |
| 1002:5b70 | 1043:005d | AMD        | RV370 [Radeon X300 SE]       | 1     | vgapci     | 5B1DC84DA5 |
| 1002:66af | 1002:081e | AMD        | Vega 20 [Radeon VII]         | 1     | vgapci     | 9F0AD7BBCF |
| 1002:6741 | 106b:00e8 | AMD        | Whistler [Radeon HD 6630M... | 1     | vgapci     | DC34D6FD02 |
| 1002:677b | 1043:3021 | AMD        | Caicos PRO [Radeon HD 7450]  | 1     | vgapci     | 44681211FF |
| 1002:679a | 1458:254c | AMD        | Tahiti PRO [Radeon HD 795... | 1     | vgapci     | CC5724ACBC |
| 1002:67df | 1043:04c2 | AMD        | Ellesmere [Radeon RX 470/... | 1     | vgapci     | DB03BEF1C6 |
| 1002:67df | 1682:c580 | AMD        | Ellesmere [Radeon RX 470/... | 1     | vgapci     | B43DB1D84E |
| 1002:67df | 1da2:e366 | AMD        | Ellesmere [Radeon RX 470/... | 1     | vgapci     | AA58B291B3 |
| 1002:6841 | 104d:90ac | AMD        | Thames [Radeon HD 7550M/7... | 1     | vgapci     | 9A751DDFD8 |
| 1002:687f | 1025:1246 | AMD        | Vega 10 XL/XT [Radeon RX ... | 1     | vgapci     | 310BD9E4AF |
| 1002:68e4 | 17aa:397a | AMD        | Robson CE [Radeon HD 6370... | 1     | vgapci     | 7042848932 |
| 1002:68f9 | 1458:21e2 | AMD        | Cedar [Radeon HD 5000/600... | 1     | vgapci     | 84E9E67AA2 |
| 1002:7149 | 17aa:2005 | AMD        | RV515/M52 [Mobility Radeo... | 1     | vgapci     | EE60EB3DC8 |
| 1002:9553 | 1043:1c42 | AMD        | RV710/M92 [Mobility Radeo... | 1     | vgapci     | 6A6B06FC67 |
| 1002:9610 | 1458:d000 | AMD        | RS780 [Radeon HD 3200]       | 1     | vgapci     | 66BCE86F33 |
| 1002:9613 | 1179:ff6a | AMD        | RS780MC [Mobility Radeon ... | 1     | vgapci     | E8BED535A9 |
| 1002:9616 | 1043:8388 | AMD        | RS780L [Radeon 3000]         | 1     | vgapci     | D99AE1AAD1 |
| 1002:9831 | 103c:213d | AMD        | Kabini [Radeon HD 8400E]     | 1     | vgapci     | 23F8ADB299 |
| 102b:0522 | 1734:11cc | Matrox ... | MGA G200e [Pilot] ServerE... | 1     | vgapci     | 6CF7F9EA4B |
| 102b:0522 | 8086:0101 | Matrox ... | MGA G200e [Pilot] ServerE... | 1     | vgapci     | 6B7FBA08DD |
| 102b:0532 | 1028:0235 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | E2AB2682CB |
| 102b:0532 | 15d9:0703 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 1F4D1E4607 |
| 102b:0533 | 103c:3381 | Matrox ... | MGA G200EH                   | 1     | vgapci     | AEA3696F41 |
| 102b:0534 | 1028:06aa | Matrox ... | G200eR2                      | 1     | vgapci     | E59AEBEE71 |
| 1039:6330 | 1043:1921 | Silicon... | 661/741/760 PCI/AGP or 66... | 1     | vgapci     | 1F098AC490 |
| 10de:0185 |           | Nvidia     | NV18 [GeForce4 MX 4000]      | 1     | vgapci     | 97732C8106 |
| 10de:06e4 | 1043:8322 | Nvidia     | G98 [GeForce 8400 GS Rev. 2] | 1     | vgapci     | 66BBED8D59 |
| 10de:06e4 | 10b0:0401 | Nvidia     | G98 [GeForce 8400 GS Rev. 2] | 1     | vgapci     | 6EB355EABD |
| 10de:06e9 | 1043:19b2 | Nvidia     | G98M [GeForce 9300M GS]      | 1     | vgapci     | 2FD46CB7C7 |
| 10de:084b | 1025:0157 | Nvidia     | C77 [GeForce 8200]           | 1     | vgapci     | DB1E7A52B9 |
| 10de:0dfa | 103c:1631 | Nvidia     | GF108GLM [Quadro 1000M]      | 1     | vgapci     | C240E3A1EA |
| 10de:0dfc | 1028:1535 | Nvidia     | GF108GLM [NVS 5200M]         | 1     | vgapci     | 04CD35A77B |
| 10de:0f00 | 1458:3543 | Nvidia     | GF108 [GeForce GT 630]       | 1     | vgapci     | A1B81962AC |
| 10de:0fc1 | 19da:1258 | Nvidia     | GK107 [GeForce GT 640]       | 1     | vgapci     | BB67F0E80B |
| 10de:0fc6 | 10b0:0fc6 | Nvidia     | GK107 [GeForce GTX 650]      | 1     | vgapci     | 33782EF7F1 |
| 10de:0ffc | 1028:053e | Nvidia     | GK107GLM [Quadro K1000M]     | 1     | vgapci     | A7761EE829 |
| 10de:104a | 1458:3546 | Nvidia     | GF119 [GeForce GT 610]       | 1     | vgapci     | 09BFDEAFBD |
| 10de:1056 | 1028:0493 | Nvidia     | GF119M [NVS 4200M]           | 1     | vgapci     | 7C8A68918A |
| 10de:1140 | 1028:0655 | Nvidia     | GF117M [GeForce 610M/710M... | 1     | vgapci     | B38C2A2E8F |
| 10de:11fa | 10de:097c | Nvidia     | GK106GL [Quadro K4000]       | 1     | vgapci     | AAC1EEB66A |
| 10de:128b | 1462:8c93 | Nvidia     | GK208B [GeForce GT 710]      | 1     | vgapci     | C7C50D64CF |
| 10de:128b | 19da:5360 | Nvidia     | GK208B [GeForce GT 710]      | 1     | vgapci     | 20FAC3B208 |
| 10de:134d | 17aa:5050 | Nvidia     | GM108M [GeForce 940MX]       | 1     | vgapci     | DFD9A97EFC |
| 10de:1401 | 1462:3201 | Nvidia     | GM206 [GeForce GTX 960]      | 1     | vgapci     | 85BEBEAEA0 |
| 10de:1436 | 17aa:2251 | Nvidia     | GM206GLM [Quadro M2200 Mo... | 1     | vgapci     | 81EFA4B3D3 |
| 10de:1b06 | 10de:120f | Nvidia     | GP102 [GeForce GTX 1080 Ti]  | 1     | vgapci     | 7C311EE004 |
| 10de:1b81 | 1458:3701 | Nvidia     | GP104 [GeForce GTX 1070]     | 1     | vgapci     | 2FC2952380 |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 1     | vgapci     | 360E63CC66 |
| 10de:1c8c | 1043:15e0 | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | vgapci     | DC7BB56859 |
| 10de:1d01 | 1458:375c | Nvidia     | GP108 [GeForce GT 1030]      | 1     | vgapci     | 29CD63ACAA |
| 10de:1f10 | 1558:65d1 | Nvidia     | TU106M [GeForce RTX 2070 ... | 1     | vgapci     | 96FCD8FC28 |
| 10de:1f36 | 1028:1926 | Nvidia     | TU106GLM [Quadro RTX 3000... | 1     | vgapci     | AA891D8F27 |
| 1106:3122 | 1106:3122 | VIA Tec... | VT8623 [Apollo CLE266] in... | 1     | vgapci     | 21B471F0F6 |
| 1106:3371 | 1462:7255 | VIA Tec... | CN896/VN896/P4M900 [Chrom... | 1     | vgapci     | 3984F45545 |
| 1a03:2000 | 15d9:0835 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | B44FE94131 |
| 8086:0042 | 103c:304b | Intel      | Core Processor Integrated... | 1     | vgapci     | 534617FE54 |
| 8086:0046 | 1025:0358 | Intel      | Core Processor Integrated... | 1     | vgapci     | 239EEA83C6 |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 1     | vgapci     | 0087B62853 |
| 8086:0116 | 17aa:397a | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 7042848932 |
| 8086:0116 | 17aa:397d | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 9728D93191 |
| 8086:0126 | 1043:1467 | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | D14C9C0372 |
| 8086:0126 | 106b:00f0 | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | DC34D6FD02 |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 05ED5EB1E4 |
| 8086:0152 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 1     | vgapci     | 4620A00CCC |
| 8086:0156 | 1458:d000 | Intel      | 3rd Gen Core processor Gr... | 1     | vgapci     | 26729F77DC |
| 8086:0162 | 1028:0585 | Intel      | Xeon E3-1200 v2/3rd Gen C... | 1     | vgapci     | 81F39F3061 |
| 8086:0162 | 1043:84ca | Intel      | Xeon E3-1200 v2/3rd Gen C... | 1     | vgapci     | 0F7697B73A |
| 8086:0166 | 1028:0535 | Intel      | 3rd Gen Core processor Gr... | 1     | vgapci     | 04CD35A77B |
| 8086:0166 | 17aa:21f9 | Intel      | 3rd Gen Core processor Gr... | 1     | vgapci     | 8ED0FEE673 |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 1     | vgapci     | 8060B3FFE1 |
| 8086:0402 | 1462:7817 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | vgapci     | E10B99BE8B |
| 8086:0402 | 1462:7887 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | vgapci     | 5D38B05178 |
| 8086:0416 | 103c:1909 | Intel      | 4th Gen Core Processor In... | 1     | vgapci     | 3E9076F244 |
| 8086:0416 | 17aa:220e | Intel      | 4th Gen Core Processor In... | 1     | vgapci     | 9001A6EA5B |
| 8086:041a | 17aa:30a6 | Intel      | Xeon E3-1200 v3 Processor... | 1     | vgapci     | DEA751EDF7 |
| 8086:0a16 | 17aa:2214 | Intel      | Haswell-ULT Integrated Gr... | 1     | vgapci     | C65CDB97DE |
| 8086:0a26 | 8086:2054 | Intel      | Haswell-ULT Integrated Gr... | 1     | vgapci     | 90E967F56B |
| 8086:1606 | 1028:0655 | Intel      | HD Graphics                  | 1     | vgapci     | B38C2A2E8F |
| 8086:1616 | 1458:1000 | Intel      | HD Graphics 5500             | 1     | vgapci     | 07036EAB43 |
| 8086:1916 | 103c:8079 | Intel      | Skylake GT2 [HD Graphics ... | 1     | vgapci     | 6C7374D0AB |
| 8086:1916 | 17aa:2238 | Intel      | Skylake GT2 [HD Graphics ... | 1     | vgapci     | 68840C222B |
| 8086:191b | 1028:06de | Intel      | HD Graphics 530              | 1     | vgapci     | 1A7976D306 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 2     |            | 1887B030C4 |
| 8086:a121 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:a1a1 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 10de:0361 | 108e:6676 | Nvidia     | MCP55 LPC Bridge             | 1     |            | 970467EFEF |
| 10de:0369 | 108e:6676 | Nvidia     | MCP55 Memory Controller      | 1     |            | 970467EFEF |
| 10de:036a | 108e:6676 | Nvidia     | MCP55 Memory Controller      | 1     |            | 970467EFEF |
| 10de:0568 |           | Nvidia     | MCP78S [GeForce 8200] Mem... | 1     |            | DB1E7A52B9 |
| 10de:0751 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Mem... | 1     |            | DB1E7A52B9 |
| 10de:0754 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] Mem... | 1     |            | DB1E7A52B9 |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 1     |            | 6C7374D0AB |
| 8086:9d21 | 1558:1313 | Intel      | Sunrise Point-LP PMC         | 1     |            | 9649F2D700 |
| 8086:9d21 | 17aa:2238 | Intel      | Sunrise Point-LP PMC         | 1     |            | 68840C222B |
| 8086:9d21 | 17aa:224f | Intel      | Sunrise Point-LP PMC         | 1     |            | BB2FCF8D92 |
| 8086:9d21 | 17aa:3844 | Intel      | Sunrise Point-LP PMC         | 1     |            | 709A3DB7DE |
| 8086:9d21 | 17aa:5062 | Intel      | Sunrise Point-LP PMC         | 1     |            | 7DEF094AFB |
| 8086:9d21 | 8086:2063 | Intel      | Sunrise Point-LP PMC         | 1     |            | 6B854263E7 |
| 8086:9def | 17aa:2279 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 90E2B57F16 |
| 8086:a121 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |
| 8086:a121 | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a121 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DC7BB56859 |
| 8086:a121 | 1071:0758 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 528E378206 |
| 8086:a121 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2FC2952380 |
| 8086:a121 | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     |            | 81EFA4B3D3 |
| 8086:a121 | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DFD9A97EFC |
| 8086:a36f | 1028:0926 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | AA891D8F27 |
| 8086:a36f | 1043:8694 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | DAB7165B99 |
| 8086:a36f | 1558:65d1 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 96FCD8FC28 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 1458:e000 | Realtek... | RTL8111/8168/8411 PCI Exp... | 14    | re         | 26729F77DC |
| 10ec:8168 | 1849:8168 | Realtek... | RTL8111/8168/8411 PCI Exp... | 7     | re         | 1C8E18B787 |
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 5     | iwm        | 2D0DC32CED |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 4     | iwn        | 05ED5EB1E4 |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 4     | em         | 9BA8051E48 |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 4     | em         | F4E8FFB5DC |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 4     | iwn        | 9BA8051E48 |
| 10ec:8168 | 1043:82c6 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | re         | 84E9E67AA2 |
| 10ec:8168 | 1043:8505 | Realtek... | RTL8111/8168/8411 PCI Exp... | 3     | re         | D99AE1AAD1 |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 3     | iwn        | 2EBFA76C28 |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 3     | em         | FA253AA78C |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 3     | em         | 0087B62853 |
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 3     | igb        | 18EA6EC987 |
| 8086:1539 |           | Intel      | I211 Gigabit Network Conn... | 3     | igb        | 91F0C6425B |
| 8086:1539 | 1043:85f0 | Intel      | I211 Gigabit Network Conn... | 3     | igb        | C00D9E9C92 |
| 10ec:8139 | 10ec:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 2     | rl         | 84E9E67AA2 |
| 10ec:8139 | 11f6:8139 | Realtek... | RTL-8100/8101L/8139 PCI F... | 2     | rl         | 3984F45545 |
| 10ec:8168 | 1043:8554 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | D65F5372EC |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | 764AAAA200 |
| 10ec:8168 | 8086:2072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | E44A7E90E0 |
| 10ec:8176 | 10ec:8195 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 2     | rtwn       | F4E8FFB5DC |
| 11ab:4364 | 1043:81f8 | Marvell... | 88E8056 PCI-E Gigabit Eth... | 2     | mskc       | 130AB3C706 |
| 14e4:163b | 1028:02f1 | Broadco... | NetXtreme II BCM5716 Giga... | 2     | bce        | D224B1F8E0 |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 2     | ath        | F6CF8F7870 |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 2     | iwm        | C65CDB97DE |
| 8086:105e | 8086:115e | Intel      | 82571EB/82571GB Gigabit E... | 2     | em         | 0F7697B73A |
| 8086:10d3 | 103c:158a | Intel      | 82574L Gigabit Network Co... | 2     | em         | DFFF5DD2F9 |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 2     | em         | 324265FE3F |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 2     | iwm        | 68840C222B |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 2     | iwm        | 7B85836A46 |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 2     |            | 96FCD8FC28 |
| 8086:31dc | 8086:02a4 | Intel      | Wireless-AC 1550i Wireles... | 2     |            | E44A7E90E0 |
| 8086:37d2 | 15d9:37d2 | Intel      | Ethernet Connection X722 ... | 2     | ixl        | 1DB4784753 |
| 1039:0191 | 1043:1815 | Silicon... | 191 Gigabit Ethernet Adapter | 1     | sge        | 2FD46CB7C7 |
| 1039:0900 | 1043:1455 | Silicon... | SiS900 PCI Fast Ethernet     | 1     | sis        | 1F098AC490 |
| 10de:0760 | 1025:0157 | Nvidia     | MCP77 Ethernet               | 1     | nfe        | DB1E7A52B9 |
| 10ec:8136 | 1019:90c9 | Realtek... | RTL810xE PCI Express Fast... | 1     | re         | 57FDAB151E |
| 10ec:8136 | 1028:0655 | Realtek... | RTL810xE PCI Express Fast... | 1     | re         | B38C2A2E8F |
| 10ec:8136 | 1179:ff6a | Realtek... | RTL810xE PCI Express Fast... | 1     | re         | E8BED535A9 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 1     | re         | 9728D93191 |
| 10ec:8139 | 1043:1045 | Realtek    | RTL-8100/8101L/8139 PCI F... | 1     | rl         | 0D292BCA2F |
| 10ec:8168 | 1028:0585 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 81F39F3061 |
| 10ec:8168 | 103c:213d | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 23F8ADB299 |
| 10ec:8168 | 103c:86d3 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 8D60BA9DFB |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | DC7BB56859 |
| 10ec:8168 | 1043:8432 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 94C4617D4E |
| 10ec:8168 | 1043:859e | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 1C88AE5A1F |
| 10ec:8168 | 1043:8677 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 3DA71BE3C9 |
| 10ec:8168 | 104d:90ac | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 9A751DDFD8 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 215CEA62E1 |
| 10ec:8168 | 1462:7817 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | E10B99BE8B |
| 10ec:8168 | 1462:7b89 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 6BFF2DB7E3 |
| 10ec:8168 | 1462:7b90 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | E7BC61FACB |
| 10ec:8168 | 1558:1313 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 9649F2D700 |
| 10ec:8168 | 1558:65d1 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 96FCD8FC28 |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 56D1B97DC1 |
| 10ec:8168 | 17aa:388a | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 709A3DB7DE |
| 10ec:8168 | 17aa:5122 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 010DB0AED4 |
| 10ec:8168 | 8086:2060 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | A24CFB5DF9 |
| 10ec:8168 | 8086:d613 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | C2067BB99A |
| 10ec:8168 | 8086:d625 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 82D3305FB4 |
| 10ec:8172 | 10ec:8172 | Realtek... | RTL8191SEvB Wireless LAN ... | 1     |            | 57FDAB151E |
| 10ec:b822 | 103c:831b | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     |            | 8D60BA9DFB |
| 1106:3065 | 1106:0102 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 1     | vr         | 21B471F0F6 |
| 1106:3065 | 1462:7255 | VIA Tec... | VT6102/VT6103 [Rhine-II]     | 1     | vr         | 3984F45545 |
| 1106:3106 | 1106:0106 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 1     | vr         | 21B471F0F6 |
| 1186:1300 | 1186:1301 | D-Link ... | RTL8139 Ethernet             | 1     | rl         | 59E3624DE7 |
| 11ab:4320 | 1043:811a | Marvell... | 88E8001 Gigabit Ethernet ... | 1     | skc        | 130AB3C706 |
| 11ab:4362 | 1043:8142 | Marvell... | 88E8053 PCI-E Gigabit Eth... | 1     | mskc       | 5B1DC84DA5 |
| 14e4:1639 | 1028:0235 | Broadco... | NetXtreme II BCM5709 Giga... | 1     | bce        | E2AB2682CB |
| 14e4:1639 | 14e4:1917 | Broadco... | NetXtreme II BCM5709 Giga... | 1     | bce        | 245D470945 |
| 14e4:163b | 1028:02a4 | Broadco... | NetXtreme II BCM5716 Giga... | 1     | bce        | 245D470945 |
| 14e4:164c | 103c:7037 | Broadco... | NetXtreme II BCM5708 Giga... | 1     | bce        | 4EBC960E9C |
| 14e4:164c | 103c:7038 | Broadco... | NetXtreme II BCM5708 Giga... | 1     | bce        | 4EBC960E9C |
| 14e4:1659 | 1043:8149 | Broadco... | NetXtreme BCM5721 Gigabit... | 1     | bge        | C1F04B3A84 |
| 14e4:1659 | 14e4:1659 | Broadco... | NetXtreme BCM5721 Gigabit... | 1     | bge        | 33782EF7F1 |
| 14e4:165f | 1028:06a7 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | bge        | E59AEBEE71 |
| 14e4:165f | 103c:2133 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | bge        | AEA3696F41 |
| 14e4:165f | 103c:22e8 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | bge        | BE41B5CD29 |
| 14e4:1680 | 1028:0262 | Broadco... | NetXtreme BCM5761e Gigabi... | 1     | bge        | 54854343E4 |
| 14e4:1684 | 103c:130a | Broadco... | NetXtreme BCM5764M Gigabi... | 1     | bge        | B43DB1D84E |
| 14e4:169c | 103c:30aa | Broadco... | NetXtreme BCM5788 Gigabit... | 1     | bge        | 256E0AE719 |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 1     | bge        | DC34D6FD02 |
| 14e4:4331 | 14e4:4331 | Broadco... | BCM4331 802.11a/b/g/n        | 1     | bwn_pci    | DC34D6FD02 |
| 14e4:4727 | 1028:0010 | Broadco... | BCM4313 802.11bgn Wireles... | 1     |            | 324265FE3F |
| 168c:001a | 168c:2052 | Atheros    | AR2413/AR2414 Wireless Ne... | 1     | ath        | 0D292BCA2F |
| 168c:001c | 144f:7128 | Qualcom... | AR242x / AR542x Wireless ... | 1     | ath        | E8BED535A9 |
| 168c:002a | 168c:3099 | Qualcom... | AR928X Wireless Network A... | 1     | ath        | DC1C86095F |
| 168c:002a | 1a3b:1067 | Qualcom... | AR928X Wireless Network A... | 1     | ath        | 2FD46CB7C7 |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 1     | ath        | 239EEA83C6 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 1     | ath        | 9728D93191 |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 1     | ath        | 6A6B06FC67 |
| 168c:002e | 168c:30a4 | Qualcom... | AR9287 Wireless Network A... | 1     | ath        | 8936B9252C |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 1     | ath        | 996540C1DC |
| 168c:0032 | 105b:e044 | Qualcom... | AR9485 Wireless Network A... | 1     | ath        | 9A751DDFD8 |
| 168c:0032 | 11ad:6628 | Qualcom... | AR9485 Wireless Network A... | 1     | ath        | B9058F83DB |
| 168c:0034 | 1028:020d | Qualcom... | AR9462 Wireless Network A... | 1     | ath        | 1DE87C0000 |
| 168c:0034 | 1043:850e | Qualcom... | AR9462 Wireless Network A... | 1     | ath        | 9F0AD7BBCF |
| 168c:0034 | 105b:e058 | Qualcom... | AR9462 Wireless Network A... | 1     | ath        | F5BF2C1FC7 |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath        | 56D1B97DC1 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 2     | sdhci_pci  | 324265FE3F |
| 8086:31cc | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | E44A7E90E0 |
| 104c:803c | 103c:30aa | Texas I... | PCIxx12 SDA Standard Comp... | 1     | sdhci_pci  | 256E0AE719 |
| 1180:0822 | 1043:1197 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 1F098AC490 |
| 1180:0822 | 1043:1877 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 2FD46CB7C7 |
| 1180:0822 | 17aa:201d | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | F08ACC6929 |
| 1217:8321 | 1028:053e | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 1     | sdhci_pci  | A7761EE829 |
| 14e4:16bc |           | Broadco... | BCM57765/57785 SDXC/MMC C... | 1     | sdhci_pci  | DC34D6FD02 |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 1     |            | 90E2B57F16 |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 6A6B06FC67 |
| 197b:2381 | 104d:9075 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 1E5D0A4D7A |
| 197b:2391 | 103c:1631 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | C240E3A1EA |
| 8086:9d2d | 8086:2063 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 6B854263E7 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:1adb |           | Nvidia     | TU106 USB Type-C UCSI Con... | 2     |            | 96FCD8FC28 |
| 8086:a1a4 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 1     |            | 4EBC960E9C |
| 10ec:816c | 17aa:5122 | Realtek... | Virtual IPMI                 | 1     |            | 010DB0AED4 |
| 8086:a324 | 1028:0926 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | AA891D8F27 |
| 8086:a324 | 1558:65d1 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 96FCD8FC28 |
| 8086:a368 | 1028:0926 | Intel      | Cannon Lake PCH Serial IO... | 1     | ig4iic     | AA891D8F27 |
| 8086:a368 | 1558:65d1 | Intel      | Cannon Lake PCH Serial IO... | 1     | ig4iic     | 96FCD8FC28 |
| 8086:a369 | 1028:0926 | Intel      | Cannon Lake PCH Serial IO... | 1     | ig4iic     | AA891D8F27 |
| 8086:a369 | 1558:65d1 | Intel      | Cannon Lake PCH Serial IO... | 1     | ig4iic     | 96FCD8FC28 |

### Signal processing (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3b32 | 17aa:2190 | Intel      | 5 Series/3400 Series Chip... | 3     |            | 0087B62853 |
| 8086:1903 | 1028:075b | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     |            | 1887B030C4 |
| 8086:2015 |           | Intel      | Sky Lake-E Ubox Registers    | 2     |            | 1DB4784753 |
| 8086:204d |           | Intel      | Sky Lake-E M3KTI Registers   | 2     |            | 1DB4784753 |
| 8086:2058 |           | Intel      | Sky Lake-E KTI 0             | 2     |            | 1DB4784753 |
| 8086:9d31 | 1028:075b | Intel      | Sunrise Point-LP Thermal ... | 2     |            | 1887B030C4 |
| 8086:9d60 | 1028:075b | Intel      | Sunrise Point-LP Serial I... | 2     |            | 1887B030C4 |
| 8086:9d61 | 1028:075b | Intel      | Sunrise Point-LP Serial I... | 2     |            | 1887B030C4 |
| 8086:a131 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:a1b1 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 8086:0e30 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e34 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e36 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:1903 | 1028:06de | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 1A7976D306 |
| 8086:1903 | 1028:0926 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | AA891D8F27 |
| 8086:1d24 | 15d9:0703 | Intel      | C600/X79 series chipset T... | 1     |            | 1F4D1E4607 |
| 8086:3b32 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 239EEA83C6 |
| 8086:3b32 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 6A6B06FC67 |
| 8086:6f30 | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | B44FE94131 |
| 8086:6f32 | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | B44FE94131 |
| 8086:6f33 | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | B44FE94131 |
| 8086:6f34 | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | B44FE94131 |
| 8086:6f36 | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | B44FE94131 |
| 8086:6f37 | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | B44FE94131 |
| 8086:6f38 | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | B44FE94131 |
| 8086:6f7d | 15d9:0835 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 1     |            | B44FE94131 |
| 8086:9d27 | 8086:2063 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 6B854263E7 |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 6C7374D0AB |
| 8086:9d31 | 1558:1313 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 9649F2D700 |
| 8086:9d31 | 17aa:2238 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 68840C222B |
| 8086:9d31 | 17aa:224f | Intel      | Sunrise Point-LP Thermal ... | 1     |            | BB2FCF8D92 |
| 8086:9d31 | 17aa:3837 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 709A3DB7DE |
| 8086:9d31 | 17aa:5062 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 7DEF094AFB |
| 8086:9d31 | 8086:2063 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 6B854263E7 |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 6C7374D0AB |
| 8086:9d60 | 17aa:383c | Intel      | Sunrise Point-LP Serial I... | 1     | ig4iic     | 709A3DB7DE |
| 8086:9d60 | 17aa:5062 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 7DEF094AFB |
| 8086:9d61 | 17aa:5062 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 7DEF094AFB |
| 8086:a127 | 1071:0758 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 528E378206 |
| 8086:a131 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |
| 8086:a131 | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a131 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     | pchtherm   | DC7BB56859 |
| 8086:a131 | 1071:0758 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 528E378206 |
| 8086:a131 | 1458:8888 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2FC2952380 |
| 8086:a131 | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     |            | 81EFA4B3D3 |
| 8086:a131 | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DFD9A97EFC |
| 8086:a160 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     | ig4iic     | DC7BB56859 |
| 8086:a160 | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     | ig4iic     | 81EFA4B3D3 |
| 8086:a379 | 1028:0926 | Intel      | Cannon Lake PCH Thermal C... | 1     |            | AA891D8F27 |
| 8086:a379 | 1558:65d1 | Intel      | Cannon Lake PCH Thermal C... | 1     |            | 96FCD8FC28 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:790b | 1458:5001 | AMD        | FCH SMBus Controller         | 5     | intsmb     | 6BAF39851A |
| 8086:3a30 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SM... | 5     | ichsmb     | 130AB3C706 |
| 1022:790b | 1043:8747 | AMD        | FCH SMBus Controller         | 3     |            | 20FAC3B208 |
| 8086:1e22 | 1458:5001 | Intel      | 7 Series/C216 Chipset Fam... | 3     |            | 26729F77DC |
| 8086:1e22 | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     |            | F4E8FFB5DC |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 3     |            | 0087B62853 |
| 1002:4385 | 1458:4385 | AMD        | SBx00 SMBus Controller       | 2     | intsmb     | CC5724ACBC |
| 1022:780b | 1022:780b | AMD        | FCH SMBus Controller         | 2     | intsmb     | DC1C86095F |
| 8086:0f12 | 1849:0f12 | Intel      | Atom Processor E3800 Seri... | 2     |            | 8787D15BC5 |
| 8086:1c22 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     |            | 324265FE3F |
| 8086:1c22 | 1458:5001 | Intel      | 6 Series/C200 Series Chip... | 2     |            | C06E03CDA0 |
| 8086:1c22 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     |            | A95465CDDA |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     |            | 7042848932 |
| 8086:1d22 | 103c:158a | Intel      | C600/X79 series chipset S... | 2     |            | DFFF5DD2F9 |
| 8086:1e22 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 2     |            | 0F7697B73A |
| 8086:27da | 17aa:200f | Intel      | NM10/ICH7 Family SMBus Co... | 2     |            | EE60EB3DC8 |
| 8086:31d4 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | E44A7E90E0 |
| 8086:5ad4 | 1849:5ad4 | Intel      | Celeron N3350/Pentium N42... | 2     |            | 1C8E18B787 |
| 8086:8c22 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 2     | ichsmb     | D65F5372EC |
| 8086:9d23 | 1028:075b | Intel      | Sunrise Point-LP SMBus       | 2     |            | 1887B030C4 |
| 8086:a123 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:a1a3 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     | ichsmb     | 1DB4784753 |
| 1002:4385 | 1002:4385 | AMD        | SBx00 SMBus Controller       | 1     | intsmb     | DB03BEF1C6 |
| 1002:4385 | 1043:8389 | AMD        | SBx00 SMBus Controller       | 1     | intsmb     | D99AE1AAD1 |
| 1002:4385 | 1179:ff6a | AMD        | SBx00 SMBus Controller       | 1     |            | E8BED535A9 |
| 1002:4385 | 1462:7693 | AMD        | SBx00 SMBus Controller       | 1     | intsmb     | B1594A3F62 |
| 1002:4385 | 1849:4385 | AMD        | SBx00 SMBus Controller       | 1     | intsmb     | 33782EF7F1 |
| 1022:780b | 103c:213d | AMD        | FCH SMBus Controller         | 1     | intsmb     | 23F8ADB299 |
| 1022:790b | 1025:1246 | AMD        | FCH SMBus Controller         | 1     | intsmb     | 310BD9E4AF |
| 1022:790b | 1043:8761 | AMD        | FCH SMBus Controller         | 1     | intsmb     | 29CD63ACAA |
| 1022:790b | 17aa:5122 | AMD        | FCH SMBus Controller         | 1     |            | 010DB0AED4 |
| 1022:790b | 1849:790b | AMD        | FCH SMBus Controller         | 1     | intsmb     | AA58B291B3 |
| 10de:0752 | 1025:0157 | Nvidia     | MCP78S [GeForce 8200] SMBus  | 1     | nfsmb      | DB1E7A52B9 |
| 8086:1c22 | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 1     |            | 81F39F3061 |
| 8086:1c22 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1     |            | 94C4617D4E |
| 8086:1c22 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     |            | 6CF7F9EA4B |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     |            | 05ED5EB1E4 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     |            | DC34D6FD02 |
| 8086:1d22 | 15d9:0703 | Intel      | C600/X79 series chipset S... | 1     |            | 1F4D1E4607 |
| 8086:1e22 | 1028:0535 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 04CD35A77B |
| 8086:1e22 | 1028:053e | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | A7761EE829 |
| 8086:1e22 | 1043:1467 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | D14C9C0372 |
| 8086:1e22 | 104d:90ac | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 9A751DDFD8 |
| 8086:1e22 | 17aa:21f9 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 8ED0FEE673 |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 8060B3FFE1 |
| 8086:2292 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 55BE2FAB24 |
| 8086:266a | 1043:80a6 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | ichsmb     | 5B1DC84DA5 |
| 8086:269b | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | ichsmb     | 9A893E2CC9 |
| 8086:27da | 1043:8190 | Intel      | NM10/ICH7 Family SMBus Co... | 1     | ichsmb     | C1F04B3A84 |
| 8086:27da | 104d:9075 | Intel      | NM10/ICH7 Family SMBus Co... | 1     |            | 1E5D0A4D7A |
| 8086:27da | 1458:5001 | Intel      | NM10/ICH7 Family SMBus Co... | 1     |            | 59E3624DE7 |
| 8086:27da | 8086:d613 | Intel      | NM10/ICH7 Family SMBus Co... | 1     |            | C2067BB99A |
| 8086:2930 | 1043:8277 | Intel      | 82801I (ICH9 Family) SMBu... | 1     | ichsmb     | A1B81962AC |
| 8086:2930 | 15d9:060a | Intel      | 82801I (ICH9 Family) SMBu... | 1     |            | FA253AA78C |
| 8086:3a30 | 1458:5001 | Intel      | 82801JI (ICH10 Family) SM... | 1     | ichsmb     | E7F015C6DA |
| 8086:3b30 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 239EEA83C6 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     | ichsmb     | 6A6B06FC67 |
| 8086:3b30 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ichsmb     | 6B7FBA08DD |
| 8086:8c22 | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 3E9076F244 |
| 8086:8c22 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 1     |            | E10B99BE8B |
| 8086:8c22 | 1462:7887 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 5D38B05178 |
| 8086:8c22 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     |            | 9001A6EA5B |
| 8086:8c22 | 17aa:30a6 | Intel      | 8 Series/C220 Series Chip... | 1     |            | DEA751EDF7 |
| 8086:8d22 | 15d9:0835 | Intel      | C610/X99 series chipset S... | 1     |            | B44FE94131 |
| 8086:9c22 | 17aa:2214 | Intel      | 8 Series SMBus Controller    | 1     | ichsmb     | C65CDB97DE |
| 8086:9c22 | 8086:2054 | Intel      | 8 Series SMBus Controller    | 1     |            | 90E967F56B |
| 8086:9ca2 | 1028:0655 | Intel      | Wildcat Point-LP SMBus Co... | 1     |            | B38C2A2E8F |
| 8086:9ca2 | 1458:1000 | Intel      | Wildcat Point-LP SMBus Co... | 1     |            | 07036EAB43 |
| 8086:9d23 | 103c:8079 | Intel      | Sunrise Point-LP SMBus       | 1     | ichsmb     | 6C7374D0AB |
| 8086:9d23 | 1558:1313 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 9649F2D700 |
| 8086:9d23 | 17aa:2238 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 68840C222B |
| 8086:9d23 | 17aa:224f | Intel      | Sunrise Point-LP SMBus       | 1     | ichsmb     | BB2FCF8D92 |
| 8086:9d23 | 17aa:3842 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 709A3DB7DE |
| 8086:9d23 | 17aa:5062 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 7DEF094AFB |
| 8086:9d23 | 8086:2063 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 6B854263E7 |
| 8086:a123 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |
| 8086:a123 | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a123 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     | ichsmb     | DC7BB56859 |
| 8086:a123 | 1071:0758 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 528E378206 |
| 8086:a123 | 1458:5001 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 2FC2952380 |
| 8086:a123 | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     |            | 81EFA4B3D3 |
| 8086:a123 | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DFD9A97EFC |
| 8086:a323 | 1028:0926 | Intel      | Cannon Lake PCH SMBus Con... | 1     |            | AA891D8F27 |
| 8086:a323 | 1558:65d1 | Intel      | Cannon Lake PCH SMBus Con... | 1     |            | 96FCD8FC28 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:4383 | 1458:a002 | AMD        | SBx00 Azalia (Intel HDA)     | 3     | hdac       | 73F1BC75E0 |
| 1002:aaf0 | 1da2:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 3     | hdac       | A34217EC03 |
| 1022:1457 | 1458:a182 | AMD        | Family 17h (Models 00h-0f... | 3     | hdac       | C7C50D64CF |
| 8086:1e20 | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     | hdac       | F4E8FFB5DC |
| 10de:0e1b | 1043:83f3 | Nvidia     | GK107 HDMI Audio Controller  | 2     | hdac       | 94C4617D4E |
| 10de:0fbc | 1462:3102 | Nvidia     | GM107 High Definition Aud... | 2     | hdac       | C039FF6AB2 |
| 8086:1c20 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | hdac       | 324265FE3F |
| 8086:1c20 | 1458:a002 | Intel      | 6 Series/C200 Series Chip... | 2     | hdac       | C06E03CDA0 |
| 8086:1c20 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | hdac       | A95465CDDA |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | hdac       | 7042848932 |
| 8086:1d20 | 103c:158a | Intel      | C600/X79 series chipset H... | 2     | hdac       | DFFF5DD2F9 |
| 8086:1e20 | 1458:a002 | Intel      | 7 Series/C216 Chipset Fam... | 2     | hdac       | 26729F77DC |
| 8086:27d8 | 17aa:2010 | Intel      | NM10/ICH7 Family High Def... | 2     | hdac       | EE60EB3DC8 |
| 8086:3198 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     | hdac       | E44A7E90E0 |
| 8086:3a3e | 1043:82fe | Intel      | 82801JI (ICH10 Family) HD... | 2     | hdac       | 84E9E67AA2 |
| 8086:3a3e | 1043:8357 | Intel      | 82801JI (ICH10 Family) HD... | 2     | hdac       | 66BBED8D59 |
| 8086:3b57 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 2     | hdac       | 6394AE37A8 |
| 8086:9d71 | 1028:075b | Intel      | Sunrise Point-LP HD Audio    | 2     | hdac       | 1887B030C4 |
| 1002:15de | 17aa:5122 | AMD        | Raven/Raven2/Fenghuang HD... | 1     | hdac       | 010DB0AED4 |
| 1002:4383 | 1043:8445 | AMD        | SBx00 Azalia (Intel HDA)     | 1     | hdac       | D99AE1AAD1 |
| 1002:4383 | 1043:84fb | AMD        | SBx00 Azalia (Intel HDA)     | 1     | hdac       | DB03BEF1C6 |
| 1002:4383 | 1179:ff6a | AMD        | SBx00 Azalia (Intel HDA)     | 1     |            | E8BED535A9 |
| 1002:4383 | 1849:7892 | AMD        | SBx00 Azalia (Intel HDA)     | 1     | hdac       | 33782EF7F1 |
| 1002:960f | 1458:960f | AMD        | RS780 HDMI Audio [Radeon ... | 1     | hdac       | 66BCE86F33 |
| 1002:9840 | 103c:213d | AMD        | Kabini HDMI/DP Audio         | 1     | hdac       | 23F8ADB299 |
| 1002:aa38 | 1043:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 1     | hdac       | 6A6B06FC67 |
| 1002:aa68 | 1458:aa68 | AMD        | Cedar HDMI Audio [Radeon ... | 1     | hdac       | 84E9E67AA2 |
| 1002:aa90 | 0000:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 1     | hdac       | DC34D6FD02 |
| 1002:aa90 | 104d:90ac | AMD        | Turks HDMI Audio [Radeon ... | 1     | hdac       | 9A751DDFD8 |
| 1002:aa98 | 1043:aa98 | AMD        | Caicos HDMI Audio [Radeon... | 1     | hdac       | 44681211FF |
| 1002:aaa0 | 1458:aaa0 | AMD        | Tahiti HDMI Audio [Radeon... | 1     | hdac       | CC5724ACBC |
| 1002:aaf0 | 1043:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 1     | hdac       | DB03BEF1C6 |
| 1002:aaf0 | 1682:aaf0 | AMD        | Ellesmere HDMI Audio [Rad... | 1     | hdac       | B43DB1D84E |
| 1002:aaf8 | 1025:1246 | AMD        | Vega 10 HDMI Audio [Radeo... | 1     | hdac       | 310BD9E4AF |
| 1002:ab20 | 1002:ab20 | AMD        | Vega 20 HDMI Audio [Radeo... | 1     | hdac       | 9F0AD7BBCF |
| 1013:6003 | 1681:0050 | Cirrus ... | CS 4614/22/24/30 [Crystal... | 1     | csa        | B1594A3F62 |
| 1022:1457 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 1     | hdac       | 310BD9E4AF |
| 1022:1457 | 1043:8724 | AMD        | Family 17h (Models 00h-0f... | 1     | hdac       | 29CD63ACAA |
| 1022:1457 | 1043:8733 | AMD        | Family 17h (Models 00h-0f... | 1     | hdac       | 7C311EE004 |
| 1022:1487 | 1458:a0cf | AMD        | Starship/Matisse HD Audio... | 1     | hdac       | C039FF6AB2 |
| 1022:15e3 | 17aa:5122 | AMD        | Family 17h (Models 10h-1f... | 1     | hdac       | 010DB0AED4 |
| 1022:15e3 | 1849:6893 | AMD        | Family 17h (Models 10h-1f... | 1     | hdac       | AA58B291B3 |
| 1022:780d | 103c:213d | AMD        | FCH Azalia Controller        | 1     | hdac       | 23F8ADB299 |
| 1022:780d | 1458:a002 | AMD        | FCH Azalia Controller        | 1     | hdac       | 09BFDEAFBD |
| 1039:7012 | 1043:1193 | Silicon... | SiS7012 AC'97 Sound Contr... | 1     | pcm        | 1F098AC490 |
| 1039:7502 | 1043:1963 | Silicon... | Azalia Audio Controller      | 1     | hdac       | 2FD46CB7C7 |
| 10de:0774 | 1025:0157 | Nvidia     | MCP72XE/MCP72P/MCP78U/MCP... | 1     | hdac       | DB1E7A52B9 |
| 10de:0bea | 103c:1631 | Nvidia     | GF108 High Definition Aud... | 1     | hdac       | C240E3A1EA |
| 10de:0bea | 1458:3543 | Nvidia     | GF108 High Definition Aud... | 1     | hdac       | A1B81962AC |
| 10de:0e08 | 1028:0493 | Nvidia     | GF119 HDMI Audio Controller  | 1     | hdac       | 7C8A68918A |
| 10de:0e08 | 1458:3546 | Nvidia     | GF119 HDMI Audio Controller  | 1     | hdac       | 09BFDEAFBD |
| 10de:0e0b | 10de:097c | Nvidia     | GK106 HDMI Audio Controller  | 1     | hdac       | AAC1EEB66A |
| 10de:0e0f | 1462:8c93 | Nvidia     | GK208 HDMI/DP Audio Contr... | 1     | hdac       | C7C50D64CF |
| 10de:0e0f | 19da:5360 | Nvidia     | GK208 HDMI/DP Audio Contr... | 1     | hdac       | 20FAC3B208 |
| 10de:0e1b | 1028:053e | Nvidia     | GK107 HDMI Audio Controller  | 1     | hdac       | A7761EE829 |
| 10de:0e1b | 10b0:0fc6 | Nvidia     | GK107 HDMI Audio Controller  | 1     | hdac       | 33782EF7F1 |
| 10de:0e1b | 19da:1258 | Nvidia     | GK107 HDMI Audio Controller  | 1     |            | BB67F0E80B |
| 10de:0fb8 | 1458:375c | Nvidia     | GP108 High Definition Aud... | 1     | hdac       | 29CD63ACAA |
| 10de:0fb8 | 1458:375d | Nvidia     | GP108 High Definition Aud... | 1     | hdac       | 6BFF2DB7E3 |
| 10de:0fb8 | 1462:8c98 | Nvidia     | GP108 High Definition Aud... | 1     | hdac       | 8936B9252C |
| 10de:0fb8 | 3842:6232 | Nvidia     | GP108 High Definition Aud... | 1     | hdac       | 1C88AE5A1F |
| 10de:0fb9 | 1462:8c96 | Nvidia     | GP107GL High Definition A... | 1     | hdac       | 360E63CC66 |
| 10de:0fba | 1462:3201 | Nvidia     | GM206 High Definition Aud... | 1     | hdac       | 85BEBEAEA0 |
| 10de:10ef | 10de:120f | Nvidia     | GP102 HDMI Audio Controller  | 1     | hdac       | 7C311EE004 |
| 10de:10f0 | 1458:3701 | Nvidia     | GP104 High Definition Aud... | 1     | hdac       | 2FC2952380 |
| 10de:10f1 | 1043:85ed | Nvidia     | GP106 High Definition Aud... | 1     | hdac       | DFFF5DD2F9 |
| 10de:10f7 | 1462:3715 | Nvidia     | TU102 High Definition Aud... | 1     | hdac       | DAB7165B99 |
| 10de:10f9 | 1028:1926 | Nvidia     | TU106 High Definition Aud... | 1     | hdac       | AA891D8F27 |
| 10de:10f9 | 1558:65d1 | Nvidia     | TU106 High Definition Aud... | 1     | hdac       | 96FCD8FC28 |
| 10de:1aeb | 103c:8556 | Nvidia     | TU116 High Definition Aud... | 1     | hdac       | 8D60BA9DFB |
| 1102:0012 | 1102:0010 | Creativ... | Sound Core3D [Sound Blast... | 1     | hdac       | AAC1EEB66A |
| 1106:3288 | 1462:7255 | VIA Tec... | VT8237A/VT8251 HDA Contro... | 1     |            | 3984F45545 |
| 8086:0a0c | 17aa:2214 | Intel      | Haswell-ULT HD Audio Cont... | 1     | hdac       | C65CDB97DE |
| 8086:0a0c | 8086:2054 | Intel      | Haswell-ULT HD Audio Cont... | 1     | hdac       | 90E967F56B |
| 8086:0c0c | 1462:7887 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | hdac       | 5D38B05178 |
| 8086:0c0c | 17aa:220e | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | hdac       | 9001A6EA5B |
| 8086:0f04 | 1849:a662 | Intel      | Atom Processor Z36xxx/Z37... | 1     | hdac       | 8787D15BC5 |
| 8086:160c | 1028:0655 | Intel      | Broadwell-U Audio Controller | 1     | hdac       | B38C2A2E8F |
| 8086:160c | 1458:1000 | Intel      | Broadwell-U Audio Controller | 1     | hdac       | 07036EAB43 |
| 8086:1c20 | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 764AAAA200 |
| 8086:1c20 | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 2EBFA76C28 |
| 8086:1c20 | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 81F39F3061 |
| 8086:1c20 | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | C240E3A1EA |
| 8086:1c20 | 1043:8444 | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 94C4617D4E |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 05ED5EB1E4 |
| 8086:1c20 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 9BA8051E48 |
| 8086:1c20 | 8086:2045 | Intel      | 6 Series/C200 Series Chip... | 1     |            | 666757A826 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | DC34D6FD02 |
| 8086:1e20 | 1028:0535 | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 04CD35A77B |
| 8086:1e20 | 1028:053e | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | A7761EE829 |
| 8086:1e20 | 1043:108d | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | B9058F83DB |
| 8086:1e20 | 1043:1467 | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | D14C9C0372 |
| 8086:1e20 | 1043:841b | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 0F7697B73A |
| 8086:1e20 | 1043:8445 | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 4620A00CCC |
| 8086:1e20 | 104d:90ac | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 9A751DDFD8 |
| 8086:1e20 | 1458:a014 | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | A209F74444 |
| 8086:1e20 | 17aa:21f9 | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 8ED0FEE673 |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 8060B3FFE1 |
| 8086:2284 | 1043:8576 | Intel      | Atom/Celeron/Pentium Proc... | 1     | hdac       | 3DA71BE3C9 |
| 8086:2284 | 1849:d887 | Intel      | Atom/Celeron/Pentium Proc... | 1     | hdac       | 2B9248155E |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43c8 | 1b21:1062 | AMD        | 400 Series Chipset SATA C... | 7     | ahci       | C00D9E9C92 |
| 1022:7901 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 5     | ahci       | 6BAF39851A |
| 8086:3a22 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) SA... | 4     | ahci       | 130AB3C706 |
| 1022:43b7 | 1b21:1062 | AMD        | 300 Series Chipset SATA C... | 3     | ahci       | A34217EC03 |
| 1022:7901 | 1043:8747 | AMD        | FCH SATA Controller [AHCI... | 3     | ahci       | 20FAC3B208 |
| 1b4b:9215 | 1b4b:9215 | Marvell... | 92xx SATA 6G Controller      | 3     | ahci       | A34217EC03 |
| 8086:1e03 | 17aa:21fb | Intel      | 7 Series Chipset Family 6... | 3     | ahci       | F4E8FFB5DC |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 3     | ahci       | 0087B62853 |
| 1022:43b6 | 1b21:1062 | AMD        | X399 Series Chipset SATA ... | 2     | ahci       | 8936B9252C |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | BE41B5CD29 |
| 1b21:0612 | 1043:84b7 | ASMedia... | ASM1062 Serial ATA Contro... | 2     | ahci       | 94C4617D4E |
| 1b21:0612 | 1849:0612 | ASMedia... | ASM1062 Serial ATA Contro... | 2     | ahci       | 1C8E18B787 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 2     | ahci       | 8787D15BC5 |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe SATA 6Gb/s ... | 2     | ahci       | BE41B5CD29 |
| 8086:0f23 | 1849:0f23 | Intel      | Atom Processor E3800 Seri... | 2     | ahci       | 8787D15BC5 |
| 8086:1c02 | 1458:b005 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | C06E03CDA0 |
| 8086:1c03 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 324265FE3F |
| 8086:1c03 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | A95465CDDA |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 7042848932 |
| 8086:1e02 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 2     | ahci       | 0F7697B73A |
| 8086:27c5 | 17aa:200d | Intel      | 82801GBM/GHM (ICH7-M Fami... | 2     | ahci       | EE60EB3DC8 |
| 8086:31e3 | 8086:2072 | Intel      |                              | 2     | ahci       | E44A7E90E0 |
| 8086:5ae3 | 1849:5ae3 | Intel      | Celeron N3350/Pentium N42... | 2     | ahci       | 1C8E18B787 |
| 8086:8c02 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | D65F5372EC |
| 8086:a102 | 15d9:0884 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | 18EA6EC987 |
| 8086:a182 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     | ahci       | 1DB4784753 |
| 8086:a1d2 | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     | ahci       | 1DB4784753 |
| 1002:4391 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | D99AE1AAD1 |
| 1002:4391 | 1043:84dd | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | DB03BEF1C6 |
| 1002:4391 | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | E8BED535A9 |
| 1002:4391 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 66BCE86F33 |
| 1002:4391 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | B1594A3F62 |
| 1002:4391 | 1849:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 33782EF7F1 |
| 1022:43b5 | 1b21:1062 | AMD        | X370 Series Chipset SATA ... | 1     | ahci       | 7C311EE004 |
| 1022:43c8 | 1025:1246 | AMD        | 400 Series Chipset SATA C... | 1     | ahci       | 310BD9E4AF |
| 1022:43c8 | 1849:43c8 | AMD        | 400 Series Chipset SATA C... | 1     | ahci       | AA58B291B3 |
| 1022:7801 | 103c:213d | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 23F8ADB299 |
| 1022:7801 | 1458:b002 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 09BFDEAFBD |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 56D1B97DC1 |
| 1022:7901 | 1025:1246 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 310BD9E4AF |
| 1022:7901 | 103c:86d3 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 8D60BA9DFB |
| 1022:7901 | 1043:8761 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 29CD63ACAA |
| 1022:7901 | 1043:87c0 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | C00D9E9C92 |
| 1022:7901 | 1462:7b09 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 8936B9252C |
| 1022:7901 | 1462:7b89 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 6BFF2DB7E3 |
| 1022:7901 | 1462:7b90 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | E7BC61FACB |
| 1022:7901 | 17aa:5122 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 010DB0AED4 |
| 1022:7901 | 1849:7901 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | AA58B291B3 |
| 10de:0ad4 | 1025:0157 | Nvidia     | MCP78S [GeForce 8200] AHC... | 1     | ahci       | DB1E7A52B9 |
| 1b21:0612 | 1043:858d | ASMedia... | ASM1062 Serial ATA Contro... | 1     | ahci       | 9F0AD7BBCF |
| 1b4b:9120 | 1043:8400 | Marvell... | 88SE9120 SATA 6Gb/s Contr... | 1     | ahci       | 9F0AD7BBCF |
| 8086:1c02 | 1028:047e | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 764AAAA200 |
| 8086:1c02 | 1028:0585 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 81F39F3061 |
| 8086:1c02 | 1043:844d | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 94C4617D4E |
| 8086:1c02 | 1734:11b8 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 6CF7F9EA4B |
| 8086:1c02 | 8086:2045 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 666757A826 |
| 8086:1c03 | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | C240E3A1EA |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 05ED5EB1E4 |
| 8086:1c03 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 9BA8051E48 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | DC34D6FD02 |
| 8086:1d02 | 15d9:0703 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | 1F4D1E4607 |
| 8086:1e02 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 1     | ahci       | 48DD406069 |
| 8086:1e03 | 1028:0535 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 04CD35A77B |
| 8086:1e03 | 1028:053e | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | A7761EE829 |
| 8086:1e03 | 1043:108d | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | B9058F83DB |
| 8086:1e03 | 1043:1467 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | D14C9C0372 |
| 8086:1e03 | 104d:90ac | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 9A751DDFD8 |
| 8086:1e03 | 1458:b005 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 26729F77DC |
| 8086:1e03 | 17aa:21f9 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 8ED0FEE673 |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 8060B3FFE1 |
| 8086:1f22 | 8086:1f22 | Intel      | Atom processor C2000 AHCI... | 1     | ahci       | 91F0C6425B |
| 8086:1f32 | 8086:1f32 | Intel      | Atom processor C2000 AHCI... | 1     | ahci       | 91F0C6425B |
| 8086:22a3 | 1043:8534 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 3DA71BE3C9 |
| 8086:22a3 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 215CEA62E1 |
| 8086:22a3 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | A24CFB5DF9 |
| 8086:22a3 | 8086:7270 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 55BE2FAB24 |
| 8086:2652 | 1043:2606 | Intel      | 82801FR/FRW (ICH6R/ICH6RW... | 1     | ahci       | 5B1DC84DA5 |
| 8086:2681 | 8086:3476 | Intel      | 631xESB/632xESB SATA AHCI... | 1     | ahci       | 9A893E2CC9 |
| 8086:27c1 | 1019:90c9 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | 57FDAB151E |
| 8086:27c1 | 1043:819e | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | C1F04B3A84 |
| 8086:27c1 | 8086:574d | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | 82D3305FB4 |
| 8086:27c5 | 103c:30aa | Intel      | 82801GBM/GHM (ICH7-M Fami... | 1     | ahci       | 256E0AE719 |
| 8086:2922 | 1043:8277 | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 1     | ahci       | A1B81962AC |
| 8086:2922 | 15d9:060a | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 1     | ahci       | FA253AA78C |
| 8086:2929 | 1028:0262 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 1     | ahci       | 54854343E4 |
| 8086:3a22 | 1043:8362 | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | 5071A32803 |
| 8086:3a22 | 1458:b005 | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | E7F015C6DA |
| 8086:3b22 | 103c:304b | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 534617FE54 |
| 8086:3b22 | 15d9:060b | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | F620C0EF31 |
| 8086:3b22 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 6B7FBA08DD |
| 8086:3b29 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 239EEA83C6 |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 6A6B06FC67 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | 00C1939EAC |
| 8086:8c02 | 103c:330d | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | AEA3696F41 |
| 8086:8c02 | 1462:7817 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | E10B99BE8B |
| 8086:8c02 | 1462:7887 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 5D38B05178 |
| 8086:8c02 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 2793B07B38 |
| 8086:8c03 | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 3E9076F244 |
| 8086:8c03 | 103c:2255 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | D615B5020D |
| 8086:8c03 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 9001A6EA5B |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:439c | 1458:5002 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 3     | atapci     | 73F1BC75E0 |
| 1002:4390 | 1458:b002 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 2     | ahci       | 73F1BC75E0 |
| 197b:2363 | 1043:824f | JMicron... | JMB363 SATA/IDE Controller   | 2     | atapci     | 66BBED8D59 |
| 8086:27df | 17aa:200c | Intel      | 82801G (ICH7 Family) IDE ... | 2     | atapci     | EE60EB3DC8 |
| 1002:439c | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | atapci     | D99AE1AAD1 |
| 1002:439c | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | atapci     | E8BED535A9 |
| 1022:7800 | 1022:7800 | AMD        | FCH SATA Controller [IDE ... | 1     | ahci       | DC1C86095F |
| 1022:780c | 1458:5002 | AMD        | FCH IDE Controller           | 1     | atapci     | 09BFDEAFBD |
| 1039:1183 | 1043:1aa7 | Silicon... | SATA Controller / IDE mode   | 1     | atapci     | 2FD46CB7C7 |
| 1039:5513 | 1043:1197 | Silicon... | 5513 IDE Controller          | 1     | atapci     | 1F098AC490 |
| 1039:5513 | 1043:1aa7 | Silicon... | 5513 IDE Controller          | 1     | atapci     | 2FD46CB7C7 |
| 10de:036e | 108e:6676 | Nvidia     | MCP55 IDE                    | 1     | atapci     | 970467EFEF |
| 10de:037f | 108e:6676 | Nvidia     | MCP55 SATA Controller        | 1     | atapci     | 970467EFEF |
| 10de:0759 | 10de:cb84 | Nvidia     | MCP78S [GeForce 8200] IDE    | 1     | atapci     | DB1E7A52B9 |
| 1106:0571 | 1106:aa01 | VIA Tec... | VT82C586A/B/VT82C686/A/B/... | 1     | atapci     | 21B471F0F6 |
| 1106:5337 | 1462:7255 | VIA Tec... | Serial ATA Controller        | 1     | atapci     | 3984F45545 |
| 1166:0214 | 103c:320b | Broadcom   | BCM5785 [HT1000] IDE         | 1     | atapci     | 4EBC960E9C |
| 11ab:6121 | 1043:8212 | Marvell... | 88SE6111/6121 SATA II / P... | 1     | atapci     | 130AB3C706 |
| 11ab:6121 | 1043:82e0 | Marvell... | 88SE6111/6121 SATA II / P... | 1     | atapci     | 97732C8106 |
| 1283:8213 | 1283:8213 | Integra... | IT8213 IDE Controller        | 1     | atapci     | 5071A32803 |
| 197b:2363 | 1458:b000 | JMicron... | JMB363 SATA/IDE Controller   | 1     | atapci     | E7F015C6DA |
| 197b:2368 | 1043:824f | JMicron... | JMB368 IDE controller        | 1     | atapci     | 84E9E67AA2 |
| 8086:1d3c | 103c:158a | Intel      | C600/X79 series chipset I... | 1     | atapci     | DFFF5DD2F9 |
| 8086:1e00 | 1458:b005 | Intel      | 7 Series/C210 Series Chip... | 1     | atapci     | A209F74444 |
| 8086:1e08 | 1458:b002 | Intel      | 7 Series/C210 Series Chip... | 1     | atapci     | A209F74444 |
| 8086:24ca | 1043:1897 | Intel      | 82801DBM (ICH4-M) IDE Con... | 1     | atapci     | 0D292BCA2F |
| 8086:266f | 1043:80a6 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | atapci     | 5B1DC84DA5 |
| 8086:269e | 8086:3476 | Intel      | 631xESB/632xESB IDE Contr... | 1     | atapci     | 9A893E2CC9 |
| 8086:27c0 | 104d:9075 | Intel      | NM10/ICH7 Family SATA Con... | 1     | atapci     | 1E5D0A4D7A |
| 8086:27c0 | 1458:b002 | Intel      | NM10/ICH7 Family SATA Con... | 1     | atapci     | 59E3624DE7 |
| 8086:27df | 103c:30aa | Intel      | 82801G (ICH7 Family) IDE ... | 1     | atapci     | 256E0AE719 |
| 8086:27df | 1043:8190 | Intel      | 82801G (ICH7 Family) IDE ... | 1     | atapci     | C1F04B3A84 |
| 8086:27df | 8086:d613 | Intel      | 82801G (ICH7 Family) IDE ... | 1     | atapci     | C2067BB99A |
| 8086:2921 | 1028:0235 | Intel      | 82801IB (ICH9) 2 port SAT... | 1     | atapci     | E2AB2682CB |
| 8086:3a20 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | atapci     | 84E9E67AA2 |
| 8086:3a26 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) 2 ... | 1     | atapci     | 84E9E67AA2 |
| 8086:3b20 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | atapci     | AB1D30ED74 |
| 8086:3b26 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | atapci     | AB1D30ED74 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 7     | nvme       | DAB7165B99 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 4     | nvme       | 8936B9252C |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 2     | nvme       | 6BFF2DB7E3 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 2     | nvme       | 2D0DC32CED |
| 10ec:5760 | 5760:10ec | Realtek... |                              | 1     | nvme       | 7C311EE004 |
| 1179:0113 | 1179:0001 | Toshiba    | BG3 NVMe SSD Controller      | 1     | nvme       | 2D0DC32CED |
| 1179:0115 | 1179:0001 | Toshiba    | XG4 NVMe SSD Controller      | 1     | nvme       | 152F5CDA4C |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 1     | nvme       | 68840C222B |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 1     | nvme       | B4C4C676C4 |
| 15b7:5003 | 15b7:5003 | Sandisk    | WD Black 2018/PC SN520 NV... | 1     | nvme       | 8D60BA9DFB |
| 15b7:5006 | 15b7:5006 | Sandisk    |                              | 1     | nvme       | F620C0EF31 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 1     | nvme       | 18EA6EC987 |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 1     | nvme       | 310BD9E4AF |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   |                              | 1     | nvme       | AA891D8F27 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 1     | nvme       | 96FCD8FC28 |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 1     | nvme       | 9F0AD7BBCF |
| 8086:2700 | 8086:3900 | Intel      | Optane SSD 900P Series       | 1     | nvme       | 20FAC3B208 |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 1     | nvme       | E7BC61FACB |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2826 | 103c:158a | Intel      | C600/X79 series chipset S... | 2     | ahci       | DFFF5DD2F9 |
| 103c:3230 | 103c:3235 | Hewlett... | Smart Array Controller       | 1     | ciss       | 4EBC960E9C |
| 1095:3114 | 1043:8136 | Silicon... | SiI 3114 [SATALink/SATARa... | 1     | atapci     | 5B1DC84DA5 |
| 1095:3124 | 1095:7124 | Silicon... | SiI 3124 PCI-X Serial ATA... | 1     | siis       | 82D3305FB4 |
| 1106:3249 | 1106:3249 | VIA Tec... | VT6421 IDE/SATA Controller   | 1     | atapci     | B1594A3F62 |
| 17d3:1280 | 17d3:1221 | Areca T... | ARC-1280/1280ML 24-Port P... | 1     | arcmsr     | B1594A3F62 |
| 17d3:1680 | 17d3:1212 | Areca T... | ARC-1680 series PCIe to S... | 1     | arcmsr     | 6B7FBA08DD |
| 8086:2822 | 1028:05a4 | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | 363E0B72C4 |
| 8086:2822 | 103c:130a | Intel      | SATA Controller [RAID mode]  | 1     | ahci       | B43DB1D84E |
| 8086:2826 | 17aa:30a6 | Intel      | C600/X79 series chipset S... | 1     | ahci       | DEA751EDF7 |
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 996540C1DC |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 2EBFA76C28 |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 7B85836A46 |
| 8086:3b25 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 245D470945 |
| 9005:028b | 9005:0301 | Adaptec    | Series 6 - 6G SAS/PCIe 2     | 1     | aacraid    | 1F4D1E4607 |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0097 | 15d9:0808 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpr        | 1DB4784753 |
| 8086:1d6b | 103c:158a | Intel      | C602 chipset 4-Port SATA ... | 2     | isci       | DFFF5DD2F9 |
| 1000:005d | 15d9:0a09 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mrsas      | B44FE94131 |
| 1000:0072 | 1000:3020 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | F620C0EF31 |
| 1000:0072 | 1028:1f1c | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 61271EAE5D |
| 1000:0072 | 1028:1f1d | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | D224B1F8E0 |
| 1000:0072 | 1028:1f1e | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | E2AB2682CB |
| 8086:1d6b | 15d9:0703 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1F4D1E4607 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 17d3:1300 | 17d3:1300 | Areca T... | ARC-1300ix-16 16-Port PCI... | 4     | arcsas     | 66BBED8D59 |
| 1000:0030 | 1000:10b0 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mpt        | 970467EFEF |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | D224B1F8E0 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 7     |            | D224B1F8E0 |
| 1022:1451 | 1022:1451 | AMD        | Family 17h (Models 00h-0f... | 5     |            | 8936B9252C |
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 5     |            | D224B1F8E0 |
| 1022:1451 | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 3     |            | 20FAC3B208 |
| 1022:1481 | 1022:1481 | AMD        | Starship/Matisse IOMMU       | 2     |            | 8D60BA9DFB |
| 1180:e823 | 17aa:21da | Ricoh      | PCIe SDXC/MMC Host Contro... | 2     | sdhci_pci  | A95465CDDA |
| 8086:2014 |           | Intel      | Sky Lake-E Ubox Registers    | 2     |            | 1DB4784753 |
| 8086:2016 |           | Intel      | Sky Lake-E Ubox Registers    | 2     |            | 1DB4784753 |
| 8086:2018 |           | Intel      | Sky Lake-E M2PCI Registers   | 2     |            | 1DB4784753 |
| 8086:2021 |           | Intel      | Sky Lake-E CBDMA Registers   | 2     | ioat       | 1DB4784753 |
| 8086:2024 |           | Intel      | Sky Lake-E MM/Vt-d Config... | 2     |            | 1DB4784753 |
| 8086:2025 |           | Intel      | Sky Lake-E RAS               | 2     |            | 1DB4784753 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 2     | ioapic     | 1DB4784753 |
| 8086:2034 |           | Intel      | Sky Lake-E VT-d              | 2     |            | 1DB4784753 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 2     |            | 1DB4784753 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 2     | ioapic     | 1DB4784753 |
| 8086:2040 |           | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 1DB4784753 |
| 8086:2041 |           | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 1DB4784753 |
| 8086:2042 |           | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 1DB4784753 |
| 8086:2043 |           | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 1DB4784753 |
| 8086:2044 |           | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 1DB4784753 |
| 8086:2045 |           | Intel      | Sky Lake-E LM Channel 1      | 2     |            | 1DB4784753 |
| 8086:2046 |           | Intel      | Sky Lake-E LMS Channel 1     | 2     |            | 1DB4784753 |
| 8086:2047 |           | Intel      | Sky Lake-E LMDP Channel 1    | 2     |            | 1DB4784753 |
| 8086:2048 |           | Intel      | Sky Lake-E DECS Channel 2    | 2     |            | 1DB4784753 |
| 8086:2049 |           | Intel      | Sky Lake-E LM Channel 2      | 2     |            | 1DB4784753 |
| 8086:204a |           | Intel      | Sky Lake-E LMS Channel 2     | 2     |            | 1DB4784753 |
| 8086:204b |           | Intel      | Sky Lake-E LMDP Channel 2    | 2     |            | 1DB4784753 |
| 8086:204e |           | Intel      | Sky Lake-E M3KTI Registers   | 2     |            | 1DB4784753 |
| 8086:2054 |           | Intel      | Sky Lake-E CHA Registers     | 2     |            | 1DB4784753 |
| 8086:2055 |           | Intel      | Sky Lake-E CHA Registers     | 2     |            | 1DB4784753 |
| 8086:2056 |           | Intel      | Sky Lake-E CHA Registers     | 2     |            | 1DB4784753 |
| 8086:2057 |           | Intel      | Sky Lake-E CHA Registers     | 2     |            | 1DB4784753 |
| 8086:2059 |           | Intel      | Sky Lake-E UPI Registers     | 2     |            | 1DB4784753 |
| 8086:2066 |           | Intel      | Sky Lake-E Integrated Mem... | 2     |            | 1DB4784753 |
| 8086:2080 |           | Intel      | Sky Lake-E PCU Registers     | 2     |            | 1DB4784753 |
| 8086:2081 |           | Intel      | Sky Lake-E PCU Registers     | 2     |            | 1DB4784753 |
| 8086:2082 |           | Intel      | Sky Lake-E PCU Registers     | 2     |            | 1DB4784753 |
| 8086:2083 |           | Intel      | Sky Lake-E PCU Registers     | 2     |            | 1DB4784753 |
| 8086:2084 |           | Intel      | Sky Lake-E PCU Registers     | 2     |            | 1DB4784753 |
| 8086:2085 |           | Intel      | Sky Lake-E PCU Registers     | 2     |            | 1DB4784753 |
| 8086:2086 |           | Intel      | Sky Lake-E PCU Registers     | 2     |            | 1DB4784753 |
| 8086:208d |           | Intel      | Sky Lake-E CHA Registers     | 2     |            | 1DB4784753 |
| 8086:208e |           | Intel      | Sky Lake-E CHA Registers     | 2     |            | 1DB4784753 |
| 8086:3426 |           | Intel      | 7500/5520/5500/X58 Routin... | 2     |            | B43DB1D84E |
| 8086:3427 |           | Intel      | 7500/5520/5500 Physical a... | 2     |            | B43DB1D84E |
| 8086:3428 |           | Intel      | 7500/5520/5500 Routing & ... | 2     |            | B43DB1D84E |
| 8086:342f |           | Intel      | 7500/5520/5500/X58 Truste... | 2     |            | B43DB1D84E |
| 8086:3438 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     |            | 66BBED8D59 |
| 8086:3c28 | 103c:158a | Intel      | Xeon E5/Core i7 Address M... | 2     |            | DFFF5DD2F9 |
| 8086:3c2a | 103c:158a | Intel      | Xeon E5/Core i7 Control S... | 2     |            | DFFF5DD2F9 |
| 8086:3c2c | 8086:3c2c | Intel      | Xeon E5/Core i7 I/O APIC     | 2     | ioapic     | DFFF5DD2F9 |
| 0e11:b203 | 103c:3305 | Compaq ... | Integrated Lights Out Con... | 1     |            | 4EBC960E9C |
| 0e11:b204 | 103c:3305 | Compaq ... | Integrated Lights Out  Pr... | 1     |            | 4EBC960E9C |
| 1002:5a23 | 1002:5a23 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | DB03BEF1C6 |
| 1002:5a23 | 1462:7693 | AMD        | RD890S/RD990 I/O Memory M... | 1     |            | B1594A3F62 |
| 1022:1419 | 1022:1419 | AMD        | Family 15h (Models 10h-1f... | 1     |            | 09BFDEAFBD |
| 1022:1451 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 310BD9E4AF |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 010DB0AED4 |
| 103c:3306 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 1     |            | AEA3696F41 |
| 103c:3307 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 1     |            | AEA3696F41 |
| 1106:5364 |           | VIA Tec... | CN896/VN896/P4M900 I/O AP... | 1     |            | 3984F45545 |
| 1180:0592 | 1043:1197 | Ricoh      | R5C592 Memory Stick Bus H... | 1     |            | 1F098AC490 |
| 1180:0592 | 1043:1877 | Ricoh      | R5C592 Memory Stick Bus H... | 1     |            | 2FD46CB7C7 |
| 1180:0843 | 1043:1877 | Ricoh      | R5C843 MMC Host Controller   | 1     |            | 2FD46CB7C7 |
| 1180:0852 | 1043:1877 | Ricoh      | xD-Picture Card Controller   | 1     |            | 2FD46CB7C7 |
| 1180:e230 | 17aa:2134 | Ricoh      | R5U2xx (R5U230 / R5U231 /... | 1     |            | 0087B62853 |
| 1180:e822 | 17aa:2133 | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | 0087B62853 |
| 1180:e823 | 17aa:21ce | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | 05ED5EB1E4 |
| 1180:e823 | 17aa:21f9 | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | 8ED0FEE673 |
| 1180:e823 | 17aa:21fa | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | 8060B3FFE1 |
| 1180:e823 | 17aa:21fb | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | EAB6164233 |
| 197b:2382 | 1043:1a07 | JMicron... | SD/MMC Host Controller       | 1     |            | 6A6B06FC67 |
| 197b:2382 | 104d:9075 | JMicron... | SD/MMC Host Controller       | 1     |            | 1E5D0A4D7A |
| 197b:2383 | 1043:1a07 | JMicron... | MS Host Controller           | 1     |            | 6A6B06FC67 |
| 197b:2383 | 104d:9075 | JMicron... | MS Host Controller           | 1     |            | 1E5D0A4D7A |
| 197b:2384 | 1043:1a07 | JMicron... | xD Host Controller           | 1     |            | 6A6B06FC67 |
| 197b:2392 | 103c:1631 | JMicron... | SD/MMC Host Controller       | 1     |            | C240E3A1EA |
| 8086:0e1d | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e1e | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e1f | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e20 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioat       | 1F4D1E4607 |
| 8086:0e21 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioat       | 1F4D1E4607 |
| 8086:0e22 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioat       | 1F4D1E4607 |
| 8086:0e23 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioat       | 1F4D1E4607 |
| 8086:0e24 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioat       | 1F4D1E4607 |
| 8086:0e25 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioat       | 1F4D1E4607 |
| 8086:0e26 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioat       | 1F4D1E4607 |
| 8086:0e27 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioat       | 1F4D1E4607 |
| 8086:0e28 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e2a | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e2c | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | ioapic     | 1F4D1E4607 |
| 8086:0e71 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e80 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e81 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e90 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ea0 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ea8 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eaa | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:43d5 | 1b21:1142 | AMD        | 400 Series Chipset USB 3.... | 6     | xhci       | 8D60BA9DFB |
| 8086:3a34 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 130AB3C706 |
| 8086:3a35 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 130AB3C706 |
| 8086:3a36 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 130AB3C706 |
| 8086:3a37 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 130AB3C706 |
| 8086:3a38 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 130AB3C706 |
| 8086:3a39 | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 130AB3C706 |
| 8086:3a3a | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 5     | ehci       | 130AB3C706 |
| 8086:3a3c | 1043:82d4 | Intel      | 82801JI (ICH10 Family) US... | 5     | ehci       | 130AB3C706 |
| 1002:4396 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 3     | ehci       | 73F1BC75E0 |
| 1002:4397 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 3     | ohci       | 73F1BC75E0 |
| 1002:4399 | 1458:5004 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 3     | ohci       | 73F1BC75E0 |
| 1022:43bb | 1b21:1142 | AMD        | 300 Series Chipset USB 3.... | 3     | xhci       | A34217EC03 |
| 8086:1e26 | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci       | 26729F77DC |
| 8086:1e26 | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci       | F4E8FFB5DC |
| 8086:1e2d | 1458:5006 | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci       | 26729F77DC |
| 8086:1e2d | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci       | F4E8FFB5DC |
| 8086:1e31 | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 3     | xhci       | F4E8FFB5DC |
| 8086:3b34 | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 3     | ehci       | 0087B62853 |
| 8086:3b3c | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 3     | ehci       | 0087B62853 |
| 1002:4398 | 1458:5004 | AMD        | SB7x0 USB OHCI1 Controller   | 2     | ohci       | CC5724ACBC |
| 1022:145c | 1458:5007 | AMD        | Family 17h (Models 00h-0f... | 2     | xhci       | A34217EC03 |
| 1022:145f | 1043:8747 | AMD        | Zeppelin USB 3.0 Host con... | 2     | xhci       | 20FAC3B208 |
| 1022:43ba | 1b21:1142 | AMD        | X399 Series Chipset USB 3... | 2     | xhci       | 8936B9252C |
| 104c:8241 | 103c:158a | Texas I... | TUSB73x0 SuperSpeed USB 3... | 2     | xhci       | DFFF5DD2F9 |
| 10de:1ada |           | Nvidia     | TU106 USB 3.1 Host Contro... | 2     | xhci       | 96FCD8FC28 |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0                      | 2     | ehci       | 970467EFEF |
| 1b21:1042 | 1043:8488 | ASMedia... | ASM1042 SuperSpeed USB Ho... | 2     | xhci       | 0F7697B73A |
| 1b21:2142 | 1043:8756 | ASMedia... | ASM2142 USB 3.1 Host Cont... | 2     | xhci       | C00D9E9C92 |
| 1b6f:7023 | 1458:5007 | Etron T... | EJ168 USB 3.0 Host Contro... | 2     | xhci       | 73F1BC75E0 |
| 8086:0f35 | 1849:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 2     | xhci       | 8787D15BC5 |
| 8086:1c26 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 324265FE3F |
| 8086:1c26 | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | C06E03CDA0 |
| 8086:1c26 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | A95465CDDA |
| 8086:1c26 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 7042848932 |
| 8086:1c2d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 324265FE3F |
| 8086:1c2d | 1458:5006 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | C06E03CDA0 |
| 8086:1c2d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | A95465CDDA |
| 8086:1c2d | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 7042848932 |
| 8086:1d26 | 103c:158a | Intel      | C600/X79 series chipset U... | 2     | ehci       | DFFF5DD2F9 |
| 8086:1d2d | 103c:158a | Intel      | C600/X79 series chipset U... | 2     | ehci       | DFFF5DD2F9 |
| 8086:1e26 | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 2     | ehci       | 0F7697B73A |
| 8086:1e2d | 1043:84ca | Intel      | 7 Series/C216 Chipset Fam... | 2     | ehci       | 0F7697B73A |
| 8086:1e31 | 1043:84ca | Intel      | 7 Series/C210 Series Chip... | 2     | xhci       | 0F7697B73A |
| 8086:1e31 | 1458:5007 | Intel      | 7 Series/C210 Series Chip... | 2     | xhci       | 48DD406069 |
| 8086:27c8 | 17aa:200a | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci       | EE60EB3DC8 |
| 8086:27c9 | 17aa:200a | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci       | EE60EB3DC8 |
| 8086:27ca | 17aa:200a | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci       | EE60EB3DC8 |
| 8086:27cb | 17aa:200a | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci       | EE60EB3DC8 |
| 8086:27cc | 17aa:200b | Intel      | NM10/ICH7 Family USB2 EHC... | 2     | ehci       | EE60EB3DC8 |
| 8086:31a8 | 8086:2072 | Intel      |                              | 2     | xhci       | E44A7E90E0 |
| 8086:5aa8 | 1849:5aa8 | Intel      | Celeron N3350/Pentium N42... | 2     | xhci       | 1C8E18B787 |
| 8086:8c26 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 2     | ehci       | D65F5372EC |
| 8086:8c2d | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 2     | ehci       | D65F5372EC |
| 8086:8c31 | 1043:8534 | Intel      | 8 Series/C220 Series Chip... | 2     | xhci       | D65F5372EC |
| 8086:9d2f | 1028:075b | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci       | 1887B030C4 |
| 8086:a12f | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     | xhci       | 18EA6EC987 |
| 8086:a1af | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     | xhci       | 1DB4784753 |
| 1002:4396 | 1002:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci       | DB03BEF1C6 |
| 1002:4396 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci       | D99AE1AAD1 |
| 1002:4396 | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci       | E8BED535A9 |
| 1002:4396 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci       | B1594A3F62 |
| 1002:4396 | 1849:4396 | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci       | 33782EF7F1 |
| 1002:4397 | 1002:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | DB03BEF1C6 |
| 1002:4397 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | D99AE1AAD1 |
| 1002:4397 | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | E8BED535A9 |
| 1002:4397 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | B1594A3F62 |
| 1002:4397 | 1849:4397 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | 33782EF7F1 |
| 1002:4398 | 1043:8389 | AMD        | SB7x0 USB OHCI1 Controller   | 1     | ohci       | D99AE1AAD1 |
| 1002:4398 | 1179:ff6a | AMD        | SB7x0 USB OHCI1 Controller   | 1     | ohci       | E8BED535A9 |
| 1002:4399 | 1002:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | DB03BEF1C6 |
| 1002:4399 | 1043:8389 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | D99AE1AAD1 |
| 1002:4399 | 1462:7693 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | B1594A3F62 |
| 1002:4399 | 1849:4399 | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | 33782EF7F1 |
| 1022:145c | 1043:8747 | AMD        | Family 17h (Models 00h-0f... | 1     | xhci       | 44681211FF |
| 1022:145f | 1022:145c | AMD        | Zeppelin USB 3.0 Host con... | 1     | xhci       | 29CD63ACAA |
| 1022:145f | 1025:1246 | AMD        | Zeppelin USB 3.0 Host con... | 1     | xhci       | 310BD9E4AF |
| 1022:145f | 1043:8761 | AMD        | Zeppelin USB 3.0 Host con... | 1     | xhci       | 29CD63ACAA |
| 1022:145f | 1458:5007 | AMD        | Zeppelin USB 3.0 Host con... | 1     | xhci       | C7C50D64CF |
| 1022:149c | 1022:1486 | AMD        | Matisse USB 3.0 Host Cont... | 1     | xhci       | C039FF6AB2 |
| 1022:149c | 1022:148c | AMD        | Matisse USB 3.0 Host Cont... | 1     | xhci       | C039FF6AB2 |
| 1022:149c | 1458:5007 | AMD        | Matisse USB 3.0 Host Cont... | 1     | xhci       | C039FF6AB2 |
| 1022:15e0 | 17aa:5122 | AMD        | Raven USB 3.1                | 1     | xhci       | 010DB0AED4 |
| 1022:15e0 | 1849:7914 | AMD        | Raven USB 3.1                | 1     | xhci       | AA58B291B3 |
| 1022:15e1 | 17aa:5122 | AMD        | Raven USB 3.1                | 1     | xhci       | 010DB0AED4 |
| 1022:15e1 | 1849:7914 | AMD        | Raven USB 3.1                | 1     | xhci       | AA58B291B3 |
| 1022:43b9 | 1b21:1142 | AMD        | X370 Series Chipset USB 3... | 1     | xhci       | 7C311EE004 |
| 1022:43d5 | 1025:1246 | AMD        | 400 Series Chipset USB 3.... | 1     | xhci       | 310BD9E4AF |
| 1022:43d5 | 1849:43d0 | AMD        | 400 Series Chipset USB 3.... | 1     | xhci       | AA58B291B3 |
| 1022:7807 | 103c:213d | AMD        | FCH USB OHCI Controller      | 1     | ohci       | 23F8ADB299 |
| 1022:7807 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 1     | ohci       | 09BFDEAFBD |
| 1022:7808 | 103c:213d | AMD        | FCH USB EHCI Controller      | 1     | ehci       | 23F8ADB299 |
| 1022:7808 | 1458:5004 | AMD        | FCH USB EHCI Controller      | 1     | ehci       | 09BFDEAFBD |
| 1022:7809 | 1458:5004 | AMD        | FCH USB OHCI Controller      | 1     | ohci       | 09BFDEAFBD |
| 1022:7812 | 1458:5004 | AMD        | FCH USB XHCI Controller      | 1     | xhci       | 09BFDEAFBD |
| 1022:7814 | 103c:213d | AMD        | FCH USB XHCI Controller      | 1     | xhci       | 23F8ADB299 |
| 1033:0194 | 103c:1631 | NEC Com... | uPD720200 USB 3.0 Host Co... | 1     | xhci       | C240E3A1EA |
| 1033:0194 | 1043:8413 | NEC Com... | uPD720200 USB 3.0 Host Co... | 1     | xhci       | 9F0AD7BBCF |
| 1039:7001 | 1043:1197 | Silicon... | USB 1.1 Controller           | 1     | ohci       | 1F098AC490 |
| 1039:7001 | 1043:1aa7 | Silicon... | USB 1.1 Controller           | 1     | ohci       | 2FD46CB7C7 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 6     |            | 8936B9252C |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 6     |            | 8936B9252C |
| 1022:1455 | 1043:8747 | AMD        | Zeppelin/Renoir PCIe Dumm... | 2     |            | 44681211FF |
| 1022:145a | 1043:8747 | AMD        | Zeppelin/Raven/Raven2 PCI... | 2     |            | 44681211FF |
| 1022:1483 | 1022:1234 | AMD        | Starship/Matisse GPP Bridge  | 2     | pcib       | C00D9E9C92 |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 2     |            | 8D60BA9DFB |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 2     |            | 8D60BA9DFB |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 2     | hostb      | DC1C86095F |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 2     | hostb      | DC1C86095F |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 2     | hostb      | DC1C86095F |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 2     | hostb      | DC1C86095F |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 2     | hostb      | DC1C86095F |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 2     | hostb      | DC1C86095F |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 2     | hostb      | DC1C86095F |
| 102b:0532 | 1028:02f1 | Matrox ... | MGA G200eW WPCM450           | 2     | vgapci     | D224B1F8E0 |
| 8086:3403 | 1028:02f1 | Intel      | 5500 I/O Hub to ESI Port     | 2     | hostb      | D224B1F8E0 |
| 8086:3411 | 1028:02f1 | Intel      | 7500/5520/5500/X58 I/O Hu... | 2     | pcib       | D224B1F8E0 |
| 8086:3a16 | 1028:02f1 | Intel      | 82801JIR (ICH10R) LPC Int... | 2     | isab       | D224B1F8E0 |
| 8086:3a34 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci       | D224B1F8E0 |
| 8086:3a35 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci       | D224B1F8E0 |
| 8086:3a36 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci       | D224B1F8E0 |
| 8086:3a37 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci       | D224B1F8E0 |
| 8086:3a38 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci       | D224B1F8E0 |
| 8086:3a39 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 2     | uhci       | D224B1F8E0 |
| 8086:3a3a | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 2     | ehci       | D224B1F8E0 |
| 8086:3a3c | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 2     | ehci       | D224B1F8E0 |
| 8086:a1ec | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 8086:a1ed | 15d9:0981 | Intel      | C620 Series Chipset Famil... | 2     |            | 1DB4784753 |
| 1002:15dd | 1002:15dd | AMD        | Raven Ridge [Radeon Vega ... | 1     | vgapci     | 6BAF39851A |
| 1002:15de | 1002:15de | AMD        | Raven/Raven2/Fenghuang HD... | 1     | hdac       | 6BAF39851A |
| 1002:4385 |           | AMD        | SBx00 SMBus Controller       | 1     | intsmb     | 73F1BC75E0 |
| 1002:6611 | 1028:2121 | AMD        | Oland [Radeon HD 8570 / R... | 1     | vgapci     | 363E0B72C4 |
| 1002:9840 | 17aa:3801 | AMD        | Kabini HDMI/DP Audio         | 1     | hdac       | 56D1B97DC1 |
| 1002:9851 | 17aa:3801 | AMD        | Mullins [Radeon R4/R5 Gra... | 1     | vgapci     | 56D1B97DC1 |
| 1002:9874 | 1002:1871 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 1     | vgapci     | BE41B5CD29 |
| 1002:aab0 | 1028:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     |            | 363E0B72C4 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 1     | hostb      | 970467EFEF |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 1     | hostb      | 970467EFEF |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 1     | hostb      | 970467EFEF |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 1     | hostb      | 970467EFEF |
| 1022:1439 | 17aa:3801 | AMD        | Family 16h Processor Func... | 1     | pcib       | 56D1B97DC1 |
| 1022:1450 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | E7BC61FACB |
| 1022:1451 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 1     |            | E7BC61FACB |
| 1022:1453 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 1     | pcib       | E7BC61FACB |
| 1022:1453 | 7b09:1462 | AMD        | Family 17h (Models 00h-0f... | 1     | pcib       | 8936B9252C |
| 1022:1454 | 7b90:1462 | AMD        | Family 17h (Models 00h-0f... | 1     | pcib       | E7BC61FACB |
| 1022:1455 | 1025:1246 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 310BD9E4AF |
| 1022:1455 | 1462:7b90 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | E7BC61FACB |
| 1022:1456 | 1462:7b90 | AMD        | Family 17h (Models 00h-0f... | 1     |            | E7BC61FACB |
| 1022:1457 | 1462:cb09 | AMD        | Family 17h (Models 00h-0f... | 1     | hdac       | 8936B9252C |
| 1022:1457 | 1462:eb90 | AMD        | Family 17h (Models 00h-0f... | 1     | hdac       | E7BC61FACB |
| 1022:145a | 1002:15dd | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | AA58B291B3 |
| 1022:145a | 1025:1246 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 310BD9E4AF |
| 1022:145a | 1462:7b90 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | E7BC61FACB |
| 1022:145c | 1022:145c | AMD        | Family 17h (Models 00h-0f... | 1     | xhci       | 8936B9252C |
| 1022:145c | 1462:7b09 | AMD        | Family 17h (Models 00h-0f... | 1     | xhci       | 8936B9252C |
| 1022:145f | 1462:7b90 | AMD        | Zeppelin USB 3.0 Host con... | 1     | xhci       | E7BC61FACB |
| 1022:1480 | 1043:87c0 | AMD        | Starship/Matisse Root Com... | 1     | hostb      | C00D9E9C92 |
| 1022:1480 | 1462:7b89 | AMD        | Starship/Matisse Root Com... | 1     | hostb      | 6BFF2DB7E3 |
| 1022:1481 | 1043:87c0 | AMD        | Starship/Matisse IOMMU       | 1     |            | C00D9E9C92 |
| 1022:1481 | 1462:7b89 | AMD        | Starship/Matisse IOMMU       | 1     |            | 6BFF2DB7E3 |
| 1022:1485 | 1043:87c0 | AMD        | Starship/Matisse Reserved... | 1     |            | C00D9E9C92 |
| 1022:1485 | 1462:7b89 | AMD        | Starship/Matisse Reserved... | 1     |            | 6BFF2DB7E3 |
| 1022:1486 | 1043:87c0 | AMD        | Starship/Matisse Cryptogr... | 1     |            | C00D9E9C92 |
| 1022:1486 | 1462:7b89 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 6BFF2DB7E3 |
| 1022:1487 | 103c:86d3 | AMD        | Starship/Matisse HD Audio... | 1     | hdac       | 8D60BA9DFB |
| 1022:1487 | 1043:8735 | AMD        | Starship/Matisse HD Audio... | 1     | hdac       | C00D9E9C92 |
| 1022:1487 | 1462:eb89 | AMD        | Starship/Matisse HD Audio... | 1     | hdac       | 6BFF2DB7E3 |
| 1022:148a | 1043:87c0 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | C00D9E9C92 |
| 1022:148a | 1462:7b89 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 6BFF2DB7E3 |
| 1022:149c | 103c:86d3 | AMD        | Matisse USB 3.0 Host Cont... | 1     | xhci       | 8D60BA9DFB |
| 1022:149c | 1043:87c0 | AMD        | Matisse USB 3.0 Host Cont... | 1     | xhci       | C00D9E9C92 |
| 1022:149c | 1462:7b89 | AMD        | Matisse USB 3.0 Host Cont... | 1     | xhci       | 6BFF2DB7E3 |
| 1022:1537 | 1022:1537 | AMD        | Kabini/Mullins PSP-Platfo... | 1     |            | DC1C86095F |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 1     |            | 56D1B97DC1 |
| 1022:1566 | 1022:1566 | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | DC1C86095F |
| 1022:1566 | 17aa:3801 | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:1570 |           | AMD        | Family 15h (Models 60h-6f... | 1     | hostb      | BE41B5CD29 |
| 1022:1571 |           | AMD        | Family 15h (Models 60h-6f... | 1     | hostb      | BE41B5CD29 |
| 1022:1572 |           | AMD        | Family 15h (Models 60h-6f... | 1     | hostb      | BE41B5CD29 |
| 1022:1573 |           | AMD        | Family 15h (Models 60h-6f... | 1     | hostb      | BE41B5CD29 |
| 1022:1574 |           | AMD        | Family 15h (Models 60h-6f... | 1     | hostb      | BE41B5CD29 |
| 1022:1575 |           | AMD        | Family 15h (Models 60h-6f... | 1     | hostb      | BE41B5CD29 |
| 1022:1576 | 1022:1576 | AMD        | Family 15h (Models 60h-6f... | 1     | hostb      | BE41B5CD29 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 1     |            | BE41B5CD29 |
| 1022:157b |           | AMD        | Family 15h (Models 60h-6f... | 1     | hostb      | BE41B5CD29 |
| 1022:157c | 1022:1234 | AMD        | Family 15h (Models 60h-6f... | 1     | pcib       | BE41B5CD29 |
| 1022:157d |           | AMD        | Carrizo Audio Dummy Host ... | 1     | hostb      | BE41B5CD29 |
| 1022:15e0 | 1458:5007 | AMD        | Raven USB 3.1                | 1     | xhci       | 6BAF39851A |
| 1022:15e1 | 1458:5007 | AMD        | Raven USB 3.1                | 1     | xhci       | 6BAF39851A |
| 1022:43d0 | 1b21:1142 | AMD        | FCH USB 3.1 XHCI Host Con... | 1     | xhci       | C00D9E9C92 |
| 1022:7808 | 1022:7808 | AMD        | FCH USB EHCI Controller      | 1     |            | DC1C86095F |
| 1022:7808 | 17aa:3801 | AMD        | FCH USB EHCI Controller      | 1     | ehci       | 56D1B97DC1 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 1     | intsmb     | 56D1B97DC1 |
| 1022:780d | 17aa:3801 | AMD        | FCH Azalia Controller        | 1     | hdac       | 56D1B97DC1 |
| 1022:780e | 17aa:3801 | AMD        | FCH LPC Bridge               | 1     | isab       | 56D1B97DC1 |
| 1022:7813 | 1022:7806 | AMD        | FCH SD Flash Controller      | 1     |            | DC1C86095F |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 56D1B97DC1 |
| 1022:7814 | 1022:1410 | AMD        | FCH USB XHCI Controller      | 1     |            | DC1C86095F |
| 1022:7814 | 17aa:3801 | AMD        | FCH USB XHCI Controller      | 1     | xhci       | 56D1B97DC1 |

