Most popular PCI devices in Notebooks
=====================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Notebooks ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Modem ](#modem-pci)
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
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0044 | 17aa:2193 | Intel      | Core Processor DRAM Contr... | 3     | hostb      | 0087B62853 |
| 8086:0154 | 17aa:21fb | Intel      | 3rd Gen Core processor DR... | 3     | hostb      | F4E8FFB5DC |
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
| 8086:3b42 | 17aa:2164 | Intel      | 5 Series/3400 Series Chip... | 3     | pcib       | 0087B62853 |
| 8086:3b44 | 17aa:2164 | Intel      | 5 Series/3400 Series Chip... | 3     | pcib       | 0087B62853 |
| 1022:1452 |           | AMD        | Family 17h (Models 00h-1f... | 2     | hostb      | 310BD9E4AF |
| 8086:0104 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 2     | hostb      | 324265FE3F |
| 8086:0104 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 2     | hostb      | A95465CDDA |
| 8086:0104 | 17aa:3975 | Intel      | 2nd Generation Core Proce... | 2     | hostb      | 7042848932 |
| 8086:1c10 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | 324265FE3F |
| 8086:1c10 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | A95465CDDA |
| 8086:1c10 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | 7042848932 |
| 8086:1c12 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | 324265FE3F |
| 8086:1c12 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | A95465CDDA |
| 8086:1c12 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | 7042848932 |
| 8086:1c14 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | 324265FE3F |
| 8086:1c16 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | 324265FE3F |
| 8086:1c16 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | A95465CDDA |
| 8086:1c18 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | A95465CDDA |
| 8086:1c1a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | pcib       | 324265FE3F |
| 8086:1c49 | 17aa:3975 | Intel      | HM65 Express Chipset LPC ... | 2     | isab       | 7042848932 |
| 8086:1c4f | 1028:0493 | Intel      | QM67 Express Chipset LPC ... | 2     | isab       | 324265FE3F |
| 8086:1c4f | 17aa:21da | Intel      | QM67 Express Chipset LPC ... | 2     | isab       | A95465CDDA |
| 8086:2448 | 17aa:2013 | Intel      | 82801 Mobile PCI Bridge      | 2     | pcib       | EE60EB3DC8 |
| 8086:27b9 | 17aa:2009 | Intel      | 82801GBM (ICH7-M) LPC Int... | 2     | isab       | EE60EB3DC8 |
| 8086:27d0 | 17aa:2011 | Intel      | NM10/ICH7 Family PCI Expr... | 2     | pcib       | EE60EB3DC8 |
| 8086:27d2 | 17aa:2011 | Intel      | NM10/ICH7 Family PCI Expr... | 2     | pcib       | EE60EB3DC8 |
| 8086:27d4 | 17aa:2011 | Intel      | NM10/ICH7 Family PCI Expr... | 2     | pcib       | EE60EB3DC8 |
| 8086:27d6 | 17aa:2011 | Intel      | NM10/ICH7 Family PCI Expr... | 2     | pcib       | EE60EB3DC8 |
| 8086:2c62 | 8086:8086 | Intel      | Core Processor QuickPath ... | 2     | hostb      | 996540C1DC |
| 8086:2d01 | 8086:8086 | Intel      | Core Processor QuickPath ... | 2     | hostb      | 996540C1DC |
| 8086:2d10 | 8086:8086 | Intel      | Core Processor QPI Link 0    | 2     | hostb      | 996540C1DC |
| 8086:2d11 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2     | hostb      | 996540C1DC |
| 8086:2d12 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2     | hostb      | 996540C1DC |
| 8086:2d13 | 8086:8086 | Intel      | 1st Generation Core i3/5/... | 2     | hostb      | 996540C1DC |
| 8086:3b0f | 17aa:2166 | Intel      | QS57 Chipset LPC Interfac... | 2     | isab       | 6394AE37A8 |
| 8086:5904 | 1028:075b | Intel      | Xeon E3-1200 v6/7th Gen C... | 2     | hostb      | 1887B030C4 |
| 8086:9d10 | 1028:075b | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcib       | 1887B030C4 |
| 8086:9d15 | 1028:075b | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcib       | 1887B030C4 |
| 8086:9d18 | 1028:075b | Intel      | Sunrise Point-LP PCI Expr... | 2     | pcib       | 1887B030C4 |
| 8086:9d58 | 1028:075b | Intel      | Sunrise Point-LP LPC Cont... | 2     | isab       | 1887B030C4 |
| 1002:4384 |           | AMD        | SBx00 PCI to PCI Bridge      | 1     | pcib       | E8BED535A9 |
| 1002:439d | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 LPC hos... | 1     | isab       | E8BED535A9 |
| 1022:1300 |           | AMD        | Family 11h Processor Hype... | 1     | hostb      | E8BED535A9 |
| 1022:1301 |           | AMD        | Family 11h Processor Addr... | 1     | hostb      | E8BED535A9 |
| 1022:1302 |           | AMD        | Family 11h Processor DRAM... | 1     | hostb      | E8BED535A9 |
| 1022:1303 |           | AMD        | Family 11h Processor Misc... | 1     | hostb      | E8BED535A9 |
| 1022:1304 |           | AMD        | Family 11h Processor Link... | 1     | hostb      | E8BED535A9 |
| 1022:1450 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1453 | 1022:1453 | AMD        | Family 17h (Models 00h-0f... | 1     | pcib       | 310BD9E4AF |
| 1022:1454 | 1022:1454 | AMD        | Family 17h (Models 00h-0f... | 1     | pcib       | 310BD9E4AF |
| 1022:1460 |           | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1461 |           | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1462 |           | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1463 |           | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1464 |           | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1465 |           | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1466 |           | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1467 |           | AMD        | Family 17h (Models 00h-0f... | 1     | hostb      | 310BD9E4AF |
| 1022:1470 |           | AMD        | Vega 10 Switch Upstream i... | 1     | pcib       | 310BD9E4AF |
| 1022:1471 | 1022:1471 | AMD        | Vega 10 Switch Downstream... | 1     | pcib       | 310BD9E4AF |
| 1022:15d0 | 1022:15d0 | AMD        | Raven/Raven2 Root Complex    | 1     | hostb      | 010DB0AED4 |
| 1022:15d3 | 17aa:5122 | AMD        | Raven/Raven2 PCIe GPP Bri... | 1     | pcib       | 010DB0AED4 |
| 1022:15db |           | AMD        | Raven/Raven2 Internal PCI... | 1     | pcib       | 010DB0AED4 |
| 1022:15dc |           | AMD        | Raven/Raven2 Internal PCI... | 1     | pcib       | 010DB0AED4 |
| 1022:15e8 |           | AMD        | Raven/Raven2 Device 24: F... | 1     | hostb      | 010DB0AED4 |
| 1022:15e9 |           | AMD        | Raven/Raven2 Device 24: F... | 1     | hostb      | 010DB0AED4 |
| 1022:15ea |           | AMD        | Raven/Raven2 Device 24: F... | 1     | hostb      | 010DB0AED4 |
| 1022:15eb |           | AMD        | Raven/Raven2 Device 24: F... | 1     | hostb      | 010DB0AED4 |
| 1022:15ec |           | AMD        | Raven/Raven2 Device 24: F... | 1     | hostb      | 010DB0AED4 |
| 1022:15ed |           | AMD        | Raven/Raven2 Device 24: F... | 1     | hostb      | 010DB0AED4 |
| 1022:15ee |           | AMD        | Raven/Raven2 Device 24: F... | 1     | hostb      | 010DB0AED4 |
| 1022:15ef |           | AMD        | Raven/Raven2 Device 24: F... | 1     | hostb      | 010DB0AED4 |
| 1022:43c6 | 1025:1246 | AMD        | 400 Series Chipset PCIe B... | 1     | pcib       | 310BD9E4AF |
| 1022:43c7 | 1025:1246 | AMD        | 400 Series Chipset PCIe Port | 1     | pcib       | 310BD9E4AF |
| 1022:43c7 | 1b21:3306 | AMD        | 400 Series Chipset PCIe Port | 1     | pcib       | 310BD9E4AF |
| 1022:790e | 1025:1246 | AMD        | FCH LPC Bridge               | 1     | isab       | 310BD9E4AF |
| 1022:790e | 17aa:5122 | AMD        | FCH LPC Bridge               | 1     | isab       | 010DB0AED4 |
| 1022:9600 | 1179:ff6a | AMD        | RS780 Host Bridge            | 1     | hostb      | E8BED535A9 |
| 1022:9602 | 1022:9602 | AMD        | RS780/RS880 PCI to PCI br... | 1     | pcib       | E8BED535A9 |
| 1022:9604 | 1179:ff6a | AMD        | RS780/RS880 PCI to PCI br... | 1     | pcib       | E8BED535A9 |
| 1022:9605 | 1179:ff6a | AMD        | RS780/RS880 PCI to PCI br... | 1     | pcib       | E8BED535A9 |
| 1022:9606 | 1179:ff6a | AMD        | RS780 PCI to PCI bridge (... | 1     | pcib       | E8BED535A9 |
| 1022:9607 | 1179:ff6a | AMD        | RS780/RS880 PCI to PCI br... | 1     | pcib       | E8BED535A9 |
| 1039:0003 |           | Silicon... | AGP Port (virtual PCI-to-... | 1     | pcib       | 1F098AC490 |
| 1039:0004 | 1039:0004 | Silicon... | PCI-to-PCI bridge            | 1     | pcib       | 2FD46CB7C7 |
| 1039:000a | 1039:0004 | Silicon... | PCI-to-PCI bridge            | 1     | pcib       | 2FD46CB7C7 |
| 1039:0661 | 1043:1197 | Silicon... | 661FX/M661FX/M661MX Host     | 1     | hostb      | 1F098AC490 |
| 1039:0671 | 1043:1aa7 | Silicon... | 671MX                        | 1     | hostb      | 2FD46CB7C7 |
| 1039:0964 |           | Silicon... | SiS964 [MuTIOL Media IO] ... | 1     | isab       | 1F098AC490 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
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
| 8086:1e3a | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     |            | F4E8FFB5DC |
| 8086:3b64 | 17aa:215f | Intel      | 5 Series/3400 Series Chip... | 3     |            | 0087B62853 |
| 8086:1c3a | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     |            | 324265FE3F |
| 8086:1c3a | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     |            | A95465CDDA |
| 8086:1c3a | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     |            | 7042848932 |
| 8086:9d3a | 1028:075b | Intel      | Sunrise Point-LP CSME HEC... | 2     |            | 1887B030C4 |
| 10ec:816a | 17aa:5122 | Realtek... | Virtual COM1                 | 1     |            | 010DB0AED4 |
| 10ec:816b | 17aa:5122 | Realtek... | RealManage COM2              | 1     |            | 010DB0AED4 |
| 8086:1c3a | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     |            | C240E3A1EA |
| 8086:1c3a | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     |            | 05ED5EB1E4 |
| 8086:1c3d | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     | uart       | C240E3A1EA |
| 8086:1c3d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     | uart       | 05ED5EB1E4 |
| 8086:1e3a | 1028:0535 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 04CD35A77B |
| 8086:1e3a | 1028:053e | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | A7761EE829 |
| 8086:1e3a | 1043:1467 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | D14C9C0372 |
| 8086:1e3a | 104d:90ac | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 9A751DDFD8 |
| 8086:1e3a | 17aa:21f9 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 8ED0FEE673 |
| 8086:1e3a | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 8060B3FFE1 |
| 8086:1e3d | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 1     | uart       | 8060B3FFE1 |
| 8086:1e3d | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 1     | uart       | EAB6164233 |
| 8086:3b64 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 239EEA83C6 |
| 8086:3b64 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 6A6B06FC67 |
| 8086:3b67 | 17aa:2162 | Intel      | 5 Series/3400 Series Chip... | 1     | uart       | 0087B62853 |
| 8086:8c3a | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 3E9076F244 |
| 8086:8c3a | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     |            | 9001A6EA5B |
| 8086:8c3d | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     | uart       | 3E9076F244 |
| 8086:8c3d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     | uart       | 9001A6EA5B |
| 8086:9c3a | 17aa:2214 | Intel      | 8 Series HECI #0             | 1     |            | C65CDB97DE |
| 8086:9cba | 1028:0655 | Intel      | Wildcat Point-LP MEI Cont... | 1     |            | B38C2A2E8F |
| 8086:9d3a | 103c:8079 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 6C7374D0AB |
| 8086:9d3a | 1558:1313 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 9649F2D700 |
| 8086:9d3a | 17aa:2238 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 68840C222B |
| 8086:9d3a | 17aa:224f | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | BB2FCF8D92 |
| 8086:9d3a | 17aa:3844 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 709A3DB7DE |
| 8086:9d3a | 17aa:5062 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 7DEF094AFB |
| 8086:9d3d | 17aa:5062 | Intel      | Sunrise Point-LP Active M... | 1     |            | 7DEF094AFB |
| 8086:a13a | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a13a | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DC7BB56859 |
| 8086:a13a | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     |            | 81EFA4B3D3 |
| 8086:a13a | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DFD9A97EFC |
| 8086:a13d | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1022:1456 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 310BD9E4AF |
| 1022:15df | 17aa:5122 | AMD        | Family 17h (Models 10h-1f... | 1     |            | 010DB0AED4 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1180:0552 | 1043:1197 | Ricoh      | R5C552 IEEE 1394 Controller  | 1     |            | 1F098AC490 |
| 1180:0552 | 1043:1897 | Ricoh      | R5C552 IEEE 1394 Controller  | 1     | fwohci     | 0D292BCA2F |
| 1180:0552 | 17aa:201e | Ricoh      | R5C552 IEEE 1394 Controller  | 1     |            | F08ACC6929 |
| 1180:0832 | 1043:1877 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     | fwohci     | 2FD46CB7C7 |
| 1180:e832 | 17aa:2136 | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 1     |            | 0087B62853 |
| 1180:e832 | 17aa:21ce | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 1     |            | 05ED5EB1E4 |
| 1217:13f7 | 1028:053e | O2 Micro   | 1394 OHCI Compliant Host ... | 1     |            | A7761EE829 |
| 197b:2380 | 103c:1631 | JMicron... | IEEE 1394 Host Controller    | 1     |            | C240E3A1EA |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0166 | 17aa:21fb | Intel      | 3rd Gen Core processor Gr... | 3     | vgapci     | F4E8FFB5DC |
| 8086:0046 | 17aa:21c1 | Intel      | Core Processor Integrated... | 2     | vgapci     | 6394AE37A8 |
| 8086:0126 | 17aa:21da | Intel      | 2nd Generation Core Proce... | 2     | vgapci     | A95465CDDA |
| 8086:5916 | 1028:075b | Intel      | HD Graphics 620              | 2     | vgapci     | 1887B030C4 |
| 1002:15dd | 17aa:5122 | AMD        | Raven Ridge [Radeon Vega ... | 1     | vgapci     | 010DB0AED4 |
| 1002:6841 | 104d:90ac | AMD        | Thames [Radeon HD 7550M/7... | 1     | vgapci     | 9A751DDFD8 |
| 1002:687f | 1025:1246 | AMD        | Vega 10 XL/XT [Radeon RX ... | 1     | vgapci     | 310BD9E4AF |
| 1002:68e4 | 17aa:397a | AMD        | Robson CE [Radeon HD 6370... | 1     | vgapci     | 7042848932 |
| 1002:7149 | 17aa:2005 | AMD        | RV515/M52 [Mobility Radeo... | 1     | vgapci     | EE60EB3DC8 |
| 1002:9553 | 1043:1c42 | AMD        | RV710/M92 [Mobility Radeo... | 1     | vgapci     | 6A6B06FC67 |
| 1002:9613 | 1179:ff6a | AMD        | RS780MC [Mobility Radeon ... | 1     | vgapci     | E8BED535A9 |
| 1039:6330 | 1043:1921 | Silicon... | 661/741/760 PCI/AGP or 66... | 1     | vgapci     | 1F098AC490 |
| 10de:06e9 | 1043:19b2 | Nvidia     | G98M [GeForce 9300M GS]      | 1     | vgapci     | 2FD46CB7C7 |
| 10de:0dfa | 103c:1631 | Nvidia     | GF108GLM [Quadro 1000M]      | 1     | vgapci     | C240E3A1EA |
| 10de:0dfc | 1028:1535 | Nvidia     | GF108GLM [NVS 5200M]         | 1     | vgapci     | 04CD35A77B |
| 10de:0ffc | 1028:053e | Nvidia     | GK107GLM [Quadro K1000M]     | 1     | vgapci     | A7761EE829 |
| 10de:1056 | 1028:0493 | Nvidia     | GF119M [NVS 4200M]           | 1     | vgapci     | 7C8A68918A |
| 10de:1140 | 1028:0655 | Nvidia     | GF117M [GeForce 610M/710M... | 1     | vgapci     | B38C2A2E8F |
| 10de:134d | 17aa:5050 | Nvidia     | GM108M [GeForce 940MX]       | 1     | vgapci     | DFD9A97EFC |
| 10de:1436 | 17aa:2251 | Nvidia     | GM206GLM [Quadro M2200 Mo... | 1     | vgapci     | 81EFA4B3D3 |
| 10de:1c8c | 1043:15e0 | Nvidia     | GP107M [GeForce GTX 1050 ... | 1     | vgapci     | DC7BB56859 |
| 10de:1f10 | 1558:65d1 | Nvidia     | TU106M [GeForce RTX 2070 ... | 1     | vgapci     | 96FCD8FC28 |
| 10de:1f36 | 1028:1926 | Nvidia     | TU106GLM [Quadro RTX 3000... | 1     | vgapci     | AA891D8F27 |
| 8086:0046 | 1025:0358 | Intel      | Core Processor Integrated... | 1     | vgapci     | 239EEA83C6 |
| 8086:0046 | 17aa:215a | Intel      | Core Processor Integrated... | 1     | vgapci     | 0087B62853 |
| 8086:0116 | 17aa:397a | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 7042848932 |
| 8086:0116 | 17aa:397d | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 9728D93191 |
| 8086:0126 | 1043:1467 | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | D14C9C0372 |
| 8086:0126 | 17aa:21ce | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 05ED5EB1E4 |
| 8086:0166 | 1028:0535 | Intel      | 3rd Gen Core processor Gr... | 1     | vgapci     | 04CD35A77B |
| 8086:0166 | 17aa:21f9 | Intel      | 3rd Gen Core processor Gr... | 1     | vgapci     | 8ED0FEE673 |
| 8086:0166 | 17aa:21fa | Intel      | 3rd Gen Core processor Gr... | 1     | vgapci     | 8060B3FFE1 |
| 8086:0416 | 103c:1909 | Intel      | 4th Gen Core Processor In... | 1     | vgapci     | 3E9076F244 |
| 8086:0416 | 17aa:220e | Intel      | 4th Gen Core Processor In... | 1     | vgapci     | 9001A6EA5B |
| 8086:0a16 | 17aa:2214 | Intel      | Haswell-ULT Integrated Gr... | 1     | vgapci     | C65CDB97DE |
| 8086:1606 | 1028:0655 | Intel      | HD Graphics                  | 1     | vgapci     | B38C2A2E8F |
| 8086:1916 | 103c:8079 | Intel      | Skylake GT2 [HD Graphics ... | 1     | vgapci     | 6C7374D0AB |
| 8086:1916 | 17aa:2238 | Intel      | Skylake GT2 [HD Graphics ... | 1     | vgapci     | 68840C222B |
| 8086:191b | 1028:06de | Intel      | HD Graphics 530              | 1     | vgapci     | 1A7976D306 |
| 8086:191b | 17aa:5050 | Intel      | HD Graphics 530              | 1     | vgapci     | DFD9A97EFC |
| 8086:1921 | 17aa:39c5 | Intel      | HD Graphics 520              | 1     | vgapci     | 709A3DB7DE |
| 8086:27a2 | 17aa:201a | Intel      | Mobile 945GM/GMS, 943/940... | 1     | vgapci     | F08ACC6929 |
| 8086:27a6 | 17aa:201a | Intel      | Mobile 945GM/GMS/GME, 943... | 1     | vgapci     | F08ACC6929 |
| 8086:3582 | 1043:1712 | Intel      | 82852/855GM Integrated Gr... | 1     |            | 0D292BCA2F |
| 8086:3e9b | 1558:65d1 | Intel      | UHD Graphics 630 (Mobile)    | 1     | vgapci     | 96FCD8FC28 |
| 8086:5916 | 17aa:224f | Intel      | HD Graphics 620              | 1     | vgapci     | BB2FCF8D92 |
| 8086:5916 | 17aa:5062 | Intel      | HD Graphics 620              | 1     | vgapci     | 7DEF094AFB |
| 8086:5917 | 1558:1313 | Intel      | UHD Graphics 620             | 1     | vgapci     | 9649F2D700 |
| 8086:591b | 1043:15e0 | Intel      | HD Graphics 630              | 1     | vgapci     | DC7BB56859 |
| 8086:a011 | 104d:9075 | Intel      | Atom Processor D4xx/D5xx/... | 1     | vgapci     | 1E5D0A4D7A |
| 8086:a012 | 104d:9075 | Intel      | Atom Processor D4xx/D5xx/... | 1     | vgapci     | 1E5D0A4D7A |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 1028:075b | Intel      | Sunrise Point-LP PMC         | 2     |            | 1887B030C4 |
| 8086:9d21 | 103c:8079 | Intel      | Sunrise Point-LP PMC         | 1     |            | 6C7374D0AB |
| 8086:9d21 | 1558:1313 | Intel      | Sunrise Point-LP PMC         | 1     |            | 9649F2D700 |
| 8086:9d21 | 17aa:2238 | Intel      | Sunrise Point-LP PMC         | 1     |            | 68840C222B |
| 8086:9d21 | 17aa:224f | Intel      | Sunrise Point-LP PMC         | 1     |            | BB2FCF8D92 |
| 8086:9d21 | 17aa:3844 | Intel      | Sunrise Point-LP PMC         | 1     |            | 709A3DB7DE |
| 8086:9d21 | 17aa:5062 | Intel      | Sunrise Point-LP PMC         | 1     |            | 7DEF094AFB |
| 8086:9def | 17aa:2279 | Intel      | Cannon Point-LP Shared SRAM  | 1     |            | 90E2B57F16 |
| 8086:a121 | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a121 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DC7BB56859 |
| 8086:a121 | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     |            | 81EFA4B3D3 |
| 8086:a121 | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DFD9A97EFC |
| 8086:a36f | 1028:0926 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | AA891D8F27 |
| 8086:a36f | 1558:65d1 | Intel      | Cannon Lake PCH Shared SRAM  | 1     |            | 96FCD8FC28 |

### Modem (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1039:7013 | 1043:1816 | Silicon... | AC'97 Modem Controller       | 1     |            | 1F098AC490 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:24fd | 8086:0010 | Intel      | Wireless 8265 / 8275         | 5     | iwm        | 2D0DC32CED |
| 8086:0085 | 8086:1311 | Intel      | Centrino Advanced-N 6205 ... | 4     | iwn        | 05ED5EB1E4 |
| 8086:1502 | 17aa:21ce | Intel      | 82579LM Gigabit Network C... | 4     | em         | 9BA8051E48 |
| 8086:1502 | 17aa:21f3 | Intel      | 82579LM Gigabit Network C... | 4     | em         | F4E8FFB5DC |
| 8086:4238 | 8086:1111 | Intel      | Centrino Ultimate-N 6300     | 4     | iwn        | 9BA8051E48 |
| 8086:0082 | 8086:1321 | Intel      | Centrino Advanced-N 6205 ... | 3     | iwn        | 2EBFA76C28 |
| 8086:10ea | 17aa:2153 | Intel      | 82577LM Gigabit Network C... | 3     | em         | 0087B62853 |
| 10ec:8176 | 10ec:8195 | Realtek... | RTL8188CE 802.11b/g/n WiF... | 2     | rtwn       | F4E8FFB5DC |
| 8086:08b2 | 8086:c270 | Intel      | Wireless 7260                | 2     | iwm        | C65CDB97DE |
| 8086:1502 | 1028:0493 | Intel      | 82579LM Gigabit Network C... | 2     | em         | 324265FE3F |
| 8086:24f3 | 8086:0130 | Intel      | Wireless 8260                | 2     | iwm        | 68840C222B |
| 8086:24fd | 8086:0110 | Intel      | Wireless 8265 / 8275         | 2     | iwm        | 7B85836A46 |
| 1039:0191 | 1043:1815 | Silicon... | 191 Gigabit Ethernet Adapter | 1     | sge        | 2FD46CB7C7 |
| 1039:0900 | 1043:1455 | Silicon... | SiS900 PCI Fast Ethernet     | 1     | sis        | 1F098AC490 |
| 10ec:8136 | 1019:90c9 | Realtek... | RTL810xE PCI Express Fast... | 1     | re         | 57FDAB151E |
| 10ec:8136 | 1028:0655 | Realtek... | RTL810xE PCI Express Fast... | 1     | re         | B38C2A2E8F |
| 10ec:8136 | 1179:ff6a | Realtek... | RTL810xE PCI Express Fast... | 1     | re         | E8BED535A9 |
| 10ec:8136 | 17aa:3975 | Realtek... | RTL810xE PCI Express Fast... | 1     | re         | 9728D93191 |
| 10ec:8139 | 1043:1045 | Realtek    | RTL-8100/8101L/8139 PCI F... | 1     | rl         | 0D292BCA2F |
| 10ec:8168 | 1043:200f | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | DC7BB56859 |
| 10ec:8168 | 104d:90ac | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 9A751DDFD8 |
| 10ec:8168 | 1558:1313 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 9649F2D700 |
| 10ec:8168 | 1558:65d1 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 96FCD8FC28 |
| 10ec:8168 | 17aa:3812 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 56D1B97DC1 |
| 10ec:8168 | 17aa:388a | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 709A3DB7DE |
| 10ec:8168 | 17aa:5122 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 010DB0AED4 |
| 10ec:8172 | 10ec:8172 | Realtek... | RTL8191SEvB Wireless LAN ... | 1     |            | 57FDAB151E |
| 14e4:1680 | 1028:0262 | Broadco... | NetXtreme BCM5761e Gigabi... | 1     | bge        | 54854343E4 |
| 14e4:169c | 103c:30aa | Broadco... | NetXtreme BCM5788 Gigabit... | 1     | bge        | 256E0AE719 |
| 14e4:4727 | 1028:0010 | Broadco... | BCM4313 802.11bgn Wireles... | 1     |            | 324265FE3F |
| 168c:001a | 168c:2052 | Atheros    | AR2413/AR2414 Wireless Ne... | 1     | ath        | 0D292BCA2F |
| 168c:001c | 144f:7128 | Qualcom... | AR242x / AR542x Wireless ... | 1     | ath        | E8BED535A9 |
| 168c:002a | 1a3b:1067 | Qualcom... | AR928X Wireless Network A... | 1     | ath        | 2FD46CB7C7 |
| 168c:002b | 105b:e035 | Qualcom... | AR9285 Wireless Network A... | 1     | ath        | 239EEA83C6 |
| 168c:002b | 17aa:30a1 | Qualcom... | AR9285 Wireless Network A... | 1     | ath        | 9728D93191 |
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 1     | ath        | 6A6B06FC67 |
| 168c:0032 | 103c:1838 | Qualcom... | AR9485 Wireless Network A... | 1     | ath        | 996540C1DC |
| 168c:0032 | 105b:e044 | Qualcom... | AR9485 Wireless Network A... | 1     | ath        | 9A751DDFD8 |
| 168c:0032 | 11ad:6628 | Qualcom... | AR9485 Wireless Network A... | 1     | ath        | B9058F83DB |
| 168c:0034 | 1028:020d | Qualcom... | AR9462 Wireless Network A... | 1     | ath        | 1DE87C0000 |
| 168c:0036 | 17aa:4026 | Qualcom... | QCA9565 / AR9565 Wireless... | 1     | ath        | 56D1B97DC1 |
| 168c:003e | 1028:0310 | Qualcom... | QCA6174 802.11ac Wireless... | 1     |            | AA891D8F27 |
| 168c:1014 | 1014:058a | Qualcom... | AR5212 802.11abg NIC         | 1     | ath        | F08ACC6929 |
| 1814:3090 | 1814:3090 | Ralink     | RT3090 Wireless 802.11n 1... | 1     | ral        | 1E5D0A4D7A |
| 1969:1073 | 1025:0359 | Qualcom... | AR8151 v1.0 Gigabit Ethernet | 1     | alc        | 239EEA83C6 |
| 1969:1083 | 1043:1467 | Qualcom... | AR8151 v2.0 Gigabit Ethernet | 1     | alc        | D14C9C0372 |
| 1969:1090 | 1043:200f | Qualcom... | AR8162 Fast Ethernet         | 1     | alc        | B9058F83DB |
| 1969:2062 | 17aa:3979 | Qualcom... | AR8152 v2.0 Fast Ethernet    | 1     | alc        | 7042848932 |
| 1969:e0b1 | 1025:1246 | Qualcom... | Killer E2500 Gigabit Ethe... | 1     | alc        | 310BD9E4AF |
| 197b:0250 | 1043:1905 | JMicron... | JMC250 PCI Express Gigabi... | 1     | jme        | 6A6B06FC67 |
| 197b:0260 | 104d:9075 | JMicron... | JMC260 PCI Express Fast E... | 1     | jme        | 1E5D0A4D7A |
| 8086:0084 | 8086:1315 | Intel      | Centrino Wireless-N 1000 ... | 1     | iwn        | A95465CDDA |
| 8086:0085 | 8086:c220 | Intel      | Centrino Advanced-N 6205 ... | 1     | iwn        | 8ED0FEE673 |
| 8086:0885 | 8086:1305 | Intel      | Centrino Wireless-N 6150     | 1     | iwn        | 7042848932 |
| 8086:0887 | 8086:4062 | Intel      | Centrino Wireless-N 2230     | 1     | iwn        | D14C9C0372 |
| 8086:088e | 8086:4060 | Intel      | Centrino Advanced-N 6235     | 1     | iwn        | 3E9076F244 |
| 8086:08b1 | 8086:c070 | Intel      | Wireless 7260                | 1     | iwm        | D615B5020D |
| 8086:095a | 8086:5010 | Intel      | Wireless 7265                | 1     | iwm        | DC7BB56859 |
| 8086:095b | 8086:5210 | Intel      | Wireless 7265                | 1     | iwm        | F83F765AB3 |
| 8086:109a | 17aa:2001 | Intel      | 82573L Gigabit Ethernet C... | 1     | em         | EE60EB3DC8 |
| 8086:109a | 17aa:207e | Intel      | 82573L Gigabit Ethernet C... | 1     | em         | F08ACC6929 |
| 8086:10ea | 1028:040a | Intel      | 82577LM Gigabit Network C... | 1     | em         | 996540C1DC |
| 8086:1502 | 1028:0492 | Intel      | 82579LM Gigabit Network C... | 1     | em         | 2EBFA76C28 |
| 8086:1502 | 1028:0535 | Intel      | 82579LM Gigabit Network C... | 1     | em         | 04CD35A77B |
| 8086:1502 | 1028:053e | Intel      | 82579LM Gigabit Network C... | 1     | em         | A7761EE829 |
| 8086:1502 | 103c:1631 | Intel      | 82579LM Gigabit Network C... | 1     | em         | C240E3A1EA |
| 8086:153a | 103c:1909 | Intel      | Ethernet Connection I217-LM  | 1     | em         | 3E9076F244 |
| 8086:153a | 103c:2253 | Intel      | Ethernet Connection I217-LM  | 1     | em         | D615B5020D |
| 8086:153a | 17aa:220e | Intel      | Ethernet Connection I217-LM  | 1     | em         | 9001A6EA5B |
| 8086:155a | 1028:05ca | Intel      | Ethernet Connection I218-LM  | 1     | em         | 1DE87C0000 |
| 8086:155a | 17aa:2214 | Intel      | Ethernet Connection I218-LM  | 1     | em         | C65CDB97DE |
| 8086:156f | 17aa:2233 | Intel      | Ethernet Connection I219-LM  | 1     | em         | 68840C222B |
| 8086:1570 | 103c:8079 | Intel      | Ethernet Connection I219-V   | 1     | em         | 6C7374D0AB |
| 8086:15a2 | 17aa:2226 | Intel      | Ethernet Connection (3) I... | 1     | em         | F83F765AB3 |
| 8086:15b7 | 1028:06de | Intel      | Ethernet Connection (2) I... | 1     | em         | 1A7976D306 |
| 8086:15b7 | 17aa:5050 | Intel      | Ethernet Connection (2) I... | 1     | em         | DFD9A97EFC |
| 8086:15bb | 1028:0926 | Intel      | Ethernet Connection (7) I... | 1     | em         | AA891D8F27 |
| 8086:15be | 17aa:2279 | Intel      | Ethernet Connection (6) I... | 1     | em         | 90E2B57F16 |
| 8086:15d7 | 17aa:5062 | Intel      | Ethernet Connection (4) I... | 1     | em         | 7DEF094AFB |
| 8086:15d8 | 17aa:224f | Intel      | Ethernet Connection (4) I... | 1     | em         | BB2FCF8D92 |
| 8086:15d8 | 17aa:2258 | Intel      | Ethernet Connection (4) I... | 1     | em         | 2D0DC32CED |
| 8086:15e3 | 17aa:224d | Intel      | Ethernet Connection (5) I... | 1     | em         | 81EFA4B3D3 |
| 8086:24f3 | 8086:1010 | Intel      | Wireless 8260                | 1     | iwm        | 6C7374D0AB |
| 8086:24fd | 8086:1010 | Intel      | Wireless 8265 / 8275         | 1     | iwm        | 9649F2D700 |
| 8086:24fd | 8086:1130 | Intel      | Wireless 8265 / 8275         | 1     | iwm        | BB2FCF8D92 |
| 8086:2723 | 8086:0084 | Intel      | Wi-Fi 6 AX200                | 1     |            | 96FCD8FC28 |
| 8086:3166 | 8086:4210 | Intel      | Dual Band Wireless-AC 316... | 1     | iwm        | 709A3DB7DE |
| 8086:4222 | 103c:135c | Intel      | PRO/Wireless 3945ABG [Gol... | 1     | wpi        | 256E0AE719 |
| 8086:4227 | 8086:1011 | Intel      | PRO/Wireless 3945ABG [Gol... | 1     | wpi        | EE60EB3DC8 |
| 8086:422b | 8086:1121 | Intel      | Centrino Ultimate-N 6300     | 1     | iwn        | 04CD35A77B |
| 8086:422c | 8086:1321 | Intel      | Centrino Advanced-N 6200     | 1     | iwn        | B38C2A2E8F |
| 8086:4232 | 8086:1326 | Intel      | WiFi Link 5100               | 1     | iwn        | 54854343E4 |
| 8086:4239 | 8086:1311 | Intel      | Centrino Advanced-N 6200     | 1     | iwn        | 0087B62853 |
| 8086:9df0 | 8086:0034 | Intel      | Cannon Point-LP CNVi [Wir... | 1     | iwm        | 90E2B57F16 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1217:8221 | 1028:0493 | O2 Micro   | OZ600FJ0/OZ900FJ0/OZ600FJ... | 2     | sdhci_pci  | 324265FE3F |
| 104c:803c | 103c:30aa | Texas I... | PCIxx12 SDA Standard Comp... | 1     | sdhci_pci  | 256E0AE719 |
| 1180:0822 | 1043:1197 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 1F098AC490 |
| 1180:0822 | 1043:1877 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 2FD46CB7C7 |
| 1180:0822 | 17aa:201d | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | F08ACC6929 |
| 1217:8321 | 1028:053e | O2 Micro   | OZ600RJ0/OZ900RJ0/OZ600RJ... | 1     | sdhci_pci  | A7761EE829 |
| 17a0:9750 | 17aa:2279 | Genesys... | GL9750 SD Host Controller    | 1     |            | 90E2B57F16 |
| 197b:2381 | 1043:1a07 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 6A6B06FC67 |
| 197b:2381 | 104d:9075 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | 1E5D0A4D7A |
| 197b:2391 | 103c:1631 | JMicron... | Standard SD Host Controller  | 1     | sdhci_pci  | C240E3A1EA |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:1adb |           | Nvidia     | TU106 USB Type-C UCSI Con... | 2     |            | 96FCD8FC28 |
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
| 8086:9d31 | 1028:075b | Intel      | Sunrise Point-LP Thermal ... | 2     |            | 1887B030C4 |
| 8086:9d60 | 1028:075b | Intel      | Sunrise Point-LP Serial I... | 2     |            | 1887B030C4 |
| 8086:9d61 | 1028:075b | Intel      | Sunrise Point-LP Serial I... | 2     |            | 1887B030C4 |
| 8086:1903 | 1028:06de | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 1A7976D306 |
| 8086:1903 | 1028:0926 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | AA891D8F27 |
| 8086:3b32 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 239EEA83C6 |
| 8086:3b32 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 6A6B06FC67 |
| 8086:9d31 | 103c:8079 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 6C7374D0AB |
| 8086:9d31 | 1558:1313 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 9649F2D700 |
| 8086:9d31 | 17aa:2238 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 68840C222B |
| 8086:9d31 | 17aa:224f | Intel      | Sunrise Point-LP Thermal ... | 1     |            | BB2FCF8D92 |
| 8086:9d31 | 17aa:3837 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 709A3DB7DE |
| 8086:9d31 | 17aa:5062 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 7DEF094AFB |
| 8086:9d60 | 103c:8079 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 6C7374D0AB |
| 8086:9d60 | 17aa:383c | Intel      | Sunrise Point-LP Serial I... | 1     | ig4iic     | 709A3DB7DE |
| 8086:9d60 | 17aa:5062 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 7DEF094AFB |
| 8086:9d61 | 17aa:5062 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 7DEF094AFB |
| 8086:a131 | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a131 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     | pchtherm   | DC7BB56859 |
| 8086:a131 | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     |            | 81EFA4B3D3 |
| 8086:a131 | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DFD9A97EFC |
| 8086:a160 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     | ig4iic     | DC7BB56859 |
| 8086:a160 | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     | ig4iic     | 81EFA4B3D3 |
| 8086:a379 | 1028:0926 | Intel      | Cannon Lake PCH Thermal C... | 1     |            | AA891D8F27 |
| 8086:a379 | 1558:65d1 | Intel      | Cannon Lake PCH Thermal C... | 1     |            | 96FCD8FC28 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e22 | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     |            | F4E8FFB5DC |
| 8086:3b30 | 17aa:2167 | Intel      | 5 Series/3400 Series Chip... | 3     |            | 0087B62853 |
| 8086:1c22 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     |            | 324265FE3F |
| 8086:1c22 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     |            | A95465CDDA |
| 8086:1c22 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     |            | 7042848932 |
| 8086:27da | 17aa:200f | Intel      | NM10/ICH7 Family SMBus Co... | 2     |            | EE60EB3DC8 |
| 8086:9d23 | 1028:075b | Intel      | Sunrise Point-LP SMBus       | 2     |            | 1887B030C4 |
| 1002:4385 | 1179:ff6a | AMD        | SBx00 SMBus Controller       | 1     |            | E8BED535A9 |
| 1022:790b | 1025:1246 | AMD        | FCH SMBus Controller         | 1     | intsmb     | 310BD9E4AF |
| 1022:790b | 17aa:5122 | AMD        | FCH SMBus Controller         | 1     |            | 010DB0AED4 |
| 8086:1c22 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     |            | 05ED5EB1E4 |
| 8086:1e22 | 1028:0535 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 04CD35A77B |
| 8086:1e22 | 1028:053e | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | A7761EE829 |
| 8086:1e22 | 1043:1467 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | D14C9C0372 |
| 8086:1e22 | 104d:90ac | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 9A751DDFD8 |
| 8086:1e22 | 17aa:21f9 | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 8ED0FEE673 |
| 8086:1e22 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | 8060B3FFE1 |
| 8086:27da | 104d:9075 | Intel      | NM10/ICH7 Family SMBus Co... | 1     |            | 1E5D0A4D7A |
| 8086:3b30 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 239EEA83C6 |
| 8086:3b30 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     | ichsmb     | 6A6B06FC67 |
| 8086:8c22 | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 3E9076F244 |
| 8086:8c22 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     |            | 9001A6EA5B |
| 8086:9c22 | 17aa:2214 | Intel      | 8 Series SMBus Controller    | 1     | ichsmb     | C65CDB97DE |
| 8086:9ca2 | 1028:0655 | Intel      | Wildcat Point-LP SMBus Co... | 1     |            | B38C2A2E8F |
| 8086:9d23 | 103c:8079 | Intel      | Sunrise Point-LP SMBus       | 1     | ichsmb     | 6C7374D0AB |
| 8086:9d23 | 1558:1313 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 9649F2D700 |
| 8086:9d23 | 17aa:2238 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 68840C222B |
| 8086:9d23 | 17aa:224f | Intel      | Sunrise Point-LP SMBus       | 1     | ichsmb     | BB2FCF8D92 |
| 8086:9d23 | 17aa:3842 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 709A3DB7DE |
| 8086:9d23 | 17aa:5062 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 7DEF094AFB |
| 8086:a123 | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     |            | 1A7976D306 |
| 8086:a123 | 1043:15e0 | Intel      | 100 Series/C230 Series Ch... | 1     | ichsmb     | DC7BB56859 |
| 8086:a123 | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     |            | 81EFA4B3D3 |
| 8086:a123 | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     |            | DFD9A97EFC |
| 8086:a323 | 1028:0926 | Intel      | Cannon Lake PCH SMBus Con... | 1     |            | AA891D8F27 |
| 8086:a323 | 1558:65d1 | Intel      | Cannon Lake PCH SMBus Con... | 1     |            | 96FCD8FC28 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e20 | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     | hdac       | F4E8FFB5DC |
| 8086:1c20 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | hdac       | 324265FE3F |
| 8086:1c20 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | hdac       | A95465CDDA |
| 8086:1c20 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | hdac       | 7042848932 |
| 8086:27d8 | 17aa:2010 | Intel      | NM10/ICH7 Family High Def... | 2     | hdac       | EE60EB3DC8 |
| 8086:3b57 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 2     | hdac       | 6394AE37A8 |
| 8086:9d71 | 1028:075b | Intel      | Sunrise Point-LP HD Audio    | 2     | hdac       | 1887B030C4 |
| 1002:15de | 17aa:5122 | AMD        | Raven/Raven2/Fenghuang HD... | 1     | hdac       | 010DB0AED4 |
| 1002:4383 | 1179:ff6a | AMD        | SBx00 Azalia (Intel HDA)     | 1     |            | E8BED535A9 |
| 1002:aa38 | 1043:aa38 | AMD        | RV710/730 HDMI Audio [Rad... | 1     | hdac       | 6A6B06FC67 |
| 1002:aa90 | 104d:90ac | AMD        | Turks HDMI Audio [Radeon ... | 1     | hdac       | 9A751DDFD8 |
| 1002:aaf8 | 1025:1246 | AMD        | Vega 10 HDMI Audio [Radeo... | 1     | hdac       | 310BD9E4AF |
| 1022:1457 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 1     | hdac       | 310BD9E4AF |
| 1022:15e3 | 17aa:5122 | AMD        | Family 17h (Models 10h-1f... | 1     | hdac       | 010DB0AED4 |
| 1039:7012 | 1043:1193 | Silicon... | SiS7012 AC'97 Sound Contr... | 1     | pcm        | 1F098AC490 |
| 1039:7502 | 1043:1963 | Silicon... | Azalia Audio Controller      | 1     | hdac       | 2FD46CB7C7 |
| 10de:0bea | 103c:1631 | Nvidia     | GF108 High Definition Aud... | 1     | hdac       | C240E3A1EA |
| 10de:0e08 | 1028:0493 | Nvidia     | GF119 HDMI Audio Controller  | 1     | hdac       | 7C8A68918A |
| 10de:0e1b | 1028:053e | Nvidia     | GK107 HDMI Audio Controller  | 1     | hdac       | A7761EE829 |
| 10de:10f9 | 1028:1926 | Nvidia     | TU106 High Definition Aud... | 1     | hdac       | AA891D8F27 |
| 10de:10f9 | 1558:65d1 | Nvidia     | TU106 High Definition Aud... | 1     | hdac       | 96FCD8FC28 |
| 8086:0a0c | 17aa:2214 | Intel      | Haswell-ULT HD Audio Cont... | 1     | hdac       | C65CDB97DE |
| 8086:0c0c | 17aa:220e | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | hdac       | 9001A6EA5B |
| 8086:160c | 1028:0655 | Intel      | Broadwell-U Audio Controller | 1     | hdac       | B38C2A2E8F |
| 8086:1c20 | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 2EBFA76C28 |
| 8086:1c20 | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | C240E3A1EA |
| 8086:1c20 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 05ED5EB1E4 |
| 8086:1c20 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | 9BA8051E48 |
| 8086:1e20 | 1028:0535 | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 04CD35A77B |
| 8086:1e20 | 1028:053e | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | A7761EE829 |
| 8086:1e20 | 1043:108d | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | B9058F83DB |
| 8086:1e20 | 1043:1467 | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | D14C9C0372 |
| 8086:1e20 | 104d:90ac | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 9A751DDFD8 |
| 8086:1e20 | 17aa:21f9 | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 8ED0FEE673 |
| 8086:1e20 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 1     | hdac       | 8060B3FFE1 |
| 8086:24c5 | 1043:1893 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     |            | 0D292BCA2F |
| 8086:27d8 | 1019:90c9 | Intel      | NM10/ICH7 Family High Def... | 1     | hdac       | 57FDAB151E |
| 8086:27d8 | 103c:30aa | Intel      | NM10/ICH7 Family High Def... | 1     | hdac       | 256E0AE719 |
| 8086:27d8 | 104d:9075 | Intel      | NM10/ICH7 Family High Def... | 1     | hdac       | 1E5D0A4D7A |
| 8086:3b56 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     | hdac       | 239EEA83C6 |
| 8086:3b56 | 1043:1643 | Intel      | 5 Series/3400 Series Chip... | 1     | hdac       | 6A6B06FC67 |
| 8086:3b56 | 17aa:215e | Intel      | 5 Series/3400 Series Chip... | 1     | hdac       | 0087B62853 |
| 8086:8c20 | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     | hdac       | 3E9076F244 |
| 8086:8c20 | 103c:2255 | Intel      | 8 Series/C220 Series Chip... | 1     | hdac       | D615B5020D |
| 8086:8c20 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     | hdac       | 9001A6EA5B |
| 8086:9c20 | 17aa:2214 | Intel      | 8 Series HD Audio Controller | 1     | hdac       | C65CDB97DE |
| 8086:9ca0 | 1028:0655 | Intel      | Wildcat Point-LP High Def... | 1     | hdac       | B38C2A2E8F |
| 8086:9ca0 | 17aa:5036 | Intel      | Wildcat Point-LP High Def... | 1     | hdac       | F83F765AB3 |
| 8086:9d70 | 103c:8079 | Intel      | Sunrise Point-LP HD Audio    | 1     | hdac       | 6C7374D0AB |
| 8086:9d70 | 17aa:2238 | Intel      | Sunrise Point-LP HD Audio    | 1     | hdac       | 68840C222B |
| 8086:9d70 | 17aa:3843 | Intel      | Sunrise Point-LP HD Audio    | 1     | hdac       | 709A3DB7DE |
| 8086:9d71 | 1558:1314 | Intel      | Sunrise Point-LP HD Audio    | 1     | hdac       | 9649F2D700 |
| 8086:9d71 | 17aa:224f | Intel      | Sunrise Point-LP HD Audio    | 1     | hdac       | BB2FCF8D92 |
| 8086:9d71 | 17aa:5062 | Intel      | Sunrise Point-LP HD Audio    | 1     | hdac       | 7DEF094AFB |
| 8086:9dc8 | 17aa:2279 | Intel      | Cannon Point-LP High Defi... | 1     |            | 90E2B57F16 |
| 8086:a170 | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     | hdac       | 1A7976D306 |
| 8086:a170 | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     | hdac       | DFD9A97EFC |
| 8086:a171 | 1043:15e0 | Intel      | CM238 HD Audio Controller    | 1     | hdac       | DC7BB56859 |
| 8086:a171 | 17aa:224d | Intel      | CM238 HD Audio Controller    | 1     | hdac       | 81EFA4B3D3 |
| 8086:a348 | 1028:0926 | Intel      | Cannon Lake PCH cAVS         | 1     | hdac       | AA891D8F27 |
| 8086:a348 | 1558:65d1 | Intel      | Cannon Lake PCH cAVS         | 1     | hdac       | 96FCD8FC28 |

### Storage (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1217:8231 | 1028:0493 | O2 Micro   | O2Micro Integrated MS/MSP... | 2     |            | 324265FE3F |
| 104c:803b | 103c:30aa | Texas I... | PCIxx12 Flash Media Contr... | 1     |            | 256E0AE719 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e03 | 17aa:21fb | Intel      | 7 Series Chipset Family 6... | 3     | ahci       | F4E8FFB5DC |
| 8086:3b2f | 17aa:2168 | Intel      | 5 Series/3400 Series Chip... | 3     | ahci       | 0087B62853 |
| 8086:1c03 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 324265FE3F |
| 8086:1c03 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | A95465CDDA |
| 8086:1c03 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 7042848932 |
| 8086:27c5 | 17aa:200d | Intel      | 82801GBM/GHM (ICH7-M Fami... | 2     | ahci       | EE60EB3DC8 |
| 1002:4391 | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | E8BED535A9 |
| 1022:43c8 | 1025:1246 | AMD        | 400 Series Chipset SATA C... | 1     | ahci       | 310BD9E4AF |
| 1022:7801 | 17aa:3801 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 56D1B97DC1 |
| 1022:7901 | 1025:1246 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 310BD9E4AF |
| 1022:7901 | 17aa:5122 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 010DB0AED4 |
| 8086:1c03 | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | C240E3A1EA |
| 8086:1c03 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 05ED5EB1E4 |
| 8086:1c03 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 9BA8051E48 |
| 8086:1e03 | 1028:0535 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 04CD35A77B |
| 8086:1e03 | 1028:053e | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | A7761EE829 |
| 8086:1e03 | 1043:108d | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | B9058F83DB |
| 8086:1e03 | 1043:1467 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | D14C9C0372 |
| 8086:1e03 | 104d:90ac | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 9A751DDFD8 |
| 8086:1e03 | 17aa:21f9 | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 8ED0FEE673 |
| 8086:1e03 | 17aa:21fa | Intel      | 7 Series Chipset Family 6... | 1     | ahci       | 8060B3FFE1 |
| 8086:27c1 | 1019:90c9 | Intel      | NM10/ICH7 Family SATA Con... | 1     | ahci       | 57FDAB151E |
| 8086:27c5 | 103c:30aa | Intel      | 82801GBM/GHM (ICH7-M Fami... | 1     | ahci       | 256E0AE719 |
| 8086:2929 | 1028:0262 | Intel      | 82801IBM/IEM (ICH9M/ICH9M... | 1     | ahci       | 54854343E4 |
| 8086:3b29 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 239EEA83C6 |
| 8086:3b29 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 6A6B06FC67 |
| 8086:8c03 | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 3E9076F244 |
| 8086:8c03 | 103c:2255 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | D615B5020D |
| 8086:8c03 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 9001A6EA5B |
| 8086:9c03 | 1028:05ca | Intel      | 8 Series SATA Controller ... | 1     | ahci       | 1DE87C0000 |
| 8086:9c03 | 17aa:2214 | Intel      | 8 Series SATA Controller ... | 1     | ahci       | C65CDB97DE |
| 8086:9c83 | 1028:0655 | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | B38C2A2E8F |
| 8086:9c83 | 17aa:5034 | Intel      | Wildcat Point-LP SATA Con... | 1     | ahci       | F83F765AB3 |
| 8086:9d03 | 103c:8079 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 6C7374D0AB |
| 8086:9d03 | 1558:1313 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 9649F2D700 |
| 8086:9d03 | 17aa:3840 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 709A3DB7DE |
| 8086:a102 | 1028:06de | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 1A7976D306 |
| 8086:a103 | 1043:15e0 | Intel      | HM170/QM170 Chipset SATA ... | 1     | ahci       | DC7BB56859 |
| 8086:a103 | 17aa:5050 | Intel      | HM170/QM170 Chipset SATA ... | 1     | ahci       | DFD9A97EFC |
| 8086:a353 | 1028:0926 | Intel      | Cannon Lake Mobile PCH SA... | 1     | ahci       | AA891D8F27 |
| 8086:a353 | 1558:65d1 | Intel      | Cannon Lake Mobile PCH SA... | 1     | ahci       | 96FCD8FC28 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27df | 17aa:200c | Intel      | 82801G (ICH7 Family) IDE ... | 2     | atapci     | EE60EB3DC8 |
| 1002:439c | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | atapci     | E8BED535A9 |
| 1039:1183 | 1043:1aa7 | Silicon... | SATA Controller / IDE mode   | 1     | atapci     | 2FD46CB7C7 |
| 1039:5513 | 1043:1197 | Silicon... | 5513 IDE Controller          | 1     | atapci     | 1F098AC490 |
| 1039:5513 | 1043:1aa7 | Silicon... | 5513 IDE Controller          | 1     | atapci     | 2FD46CB7C7 |
| 8086:24ca | 1043:1897 | Intel      | 82801DBM (ICH4-M) IDE Con... | 1     | atapci     | 0D292BCA2F |
| 8086:27c0 | 104d:9075 | Intel      | NM10/ICH7 Family SATA Con... | 1     | atapci     | 1E5D0A4D7A |
| 8086:27df | 103c:30aa | Intel      | 82801G (ICH7 Family) IDE ... | 1     | atapci     | 256E0AE719 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 2     | nvme       | 1887B030C4 |
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 2     | nvme       | BB2FCF8D92 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 2     | nvme       | 2D0DC32CED |
| 1179:0113 | 1179:0001 | Toshiba    | BG3 NVMe SSD Controller      | 1     | nvme       | 2D0DC32CED |
| 1179:0115 | 1179:0001 | Toshiba    | XG4 NVMe SSD Controller      | 1     | nvme       | 152F5CDA4C |
| 144d:a802 | 144d:a801 | Samsung... | NVMe SSD Controller SM951... | 1     | nvme       | 68840C222B |
| 1c5c:1504 | 0100:1093 | SK Hynix   | SC300 512GB M.2 2280 SATA... | 1     | nvme       | 310BD9E4AF |
| 1c5c:1627 | 1c5c:1627 | SK Hynix   |                              | 1     | nvme       | AA891D8F27 |
| 1cc1:8201 | 1cc1:8201 | ADATA T... | XPG SX8200 Pro PCIe Gen3x... | 1     | nvme       | 96FCD8FC28 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:282a | 1028:040a | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 996540C1DC |
| 8086:282a | 1028:0492 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 2EBFA76C28 |
| 8086:282a | 1043:1311 | Intel      | 82801 Mobile SATA Control... | 1     | ahci       | 7B85836A46 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1180:e823 | 17aa:21da | Ricoh      | PCIe SDXC/MMC Host Contro... | 2     | sdhci_pci  | A95465CDDA |
| 1022:1451 | 1025:1246 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 310BD9E4AF |
| 1022:15d1 | 1022:15d1 | AMD        | Raven/Raven2 IOMMU           | 1     |            | 010DB0AED4 |
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
| 8086:15e8 | 1558:65d1 | Intel      | JHL7540 Thunderbolt 3 NHI... | 1     |            | 96FCD8FC28 |
| 8086:15eb | 1028:0926 | Intel      | JHL7540 Thunderbolt 3 NHI... | 1     |            | AA891D8F27 |
| 8086:1911 | 1028:0926 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | AA891D8F27 |
| 8086:1911 | 1043:15e0 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | DC7BB56859 |
| 8086:1911 | 17aa:2238 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 68840C222B |
| 8086:1911 | 17aa:224d | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 81EFA4B3D3 |
| 8086:1911 | 17aa:224f | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | BB2FCF8D92 |
| 8086:3584 | 1043:1897 | Intel      | 82852/82855 GM/GME/PM/GMV... | 1     |            | 0D292BCA2F |
| 8086:3585 | 1043:1897 | Intel      | 82852/82855 GM/GME/PM/GMV... | 1     |            | 0D292BCA2F |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1e26 | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci       | F4E8FFB5DC |
| 8086:1e2d | 17aa:21fb | Intel      | 7 Series/C216 Chipset Fam... | 3     | ehci       | F4E8FFB5DC |
| 8086:1e31 | 17aa:21fb | Intel      | 7 Series/C210 Series Chip... | 3     | xhci       | F4E8FFB5DC |
| 8086:3b34 | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 3     | ehci       | 0087B62853 |
| 8086:3b3c | 17aa:2163 | Intel      | 5 Series/3400 Series Chip... | 3     | ehci       | 0087B62853 |
| 10de:1ada |           | Nvidia     | TU106 USB 3.1 Host Contro... | 2     | xhci       | 96FCD8FC28 |
| 8086:1c26 | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 324265FE3F |
| 8086:1c26 | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | A95465CDDA |
| 8086:1c26 | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 7042848932 |
| 8086:1c2d | 1028:0493 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 324265FE3F |
| 8086:1c2d | 17aa:21da | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | A95465CDDA |
| 8086:1c2d | 17aa:3975 | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 7042848932 |
| 8086:27c8 | 17aa:200a | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci       | EE60EB3DC8 |
| 8086:27c9 | 17aa:200a | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci       | EE60EB3DC8 |
| 8086:27ca | 17aa:200a | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci       | EE60EB3DC8 |
| 8086:27cb | 17aa:200a | Intel      | NM10/ICH7 Family USB UHCI... | 2     | uhci       | EE60EB3DC8 |
| 8086:27cc | 17aa:200b | Intel      | NM10/ICH7 Family USB2 EHC... | 2     | ehci       | EE60EB3DC8 |
| 8086:9d2f | 1028:075b | Intel      | Sunrise Point-LP USB 3.0 ... | 2     | xhci       | 1887B030C4 |
| 1002:4396 | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 USB EHC... | 1     | ehci       | E8BED535A9 |
| 1002:4397 | 1179:ff6a | AMD        | SB7x0/SB8x0/SB9x0 USB OHC... | 1     | ohci       | E8BED535A9 |
| 1002:4398 | 1179:ff6a | AMD        | SB7x0 USB OHCI1 Controller   | 1     | ohci       | E8BED535A9 |
| 1022:145f | 1025:1246 | AMD        | Zeppelin USB 3.0 Host con... | 1     | xhci       | 310BD9E4AF |
| 1022:15e0 | 17aa:5122 | AMD        | Raven USB 3.1                | 1     | xhci       | 010DB0AED4 |
| 1022:15e1 | 17aa:5122 | AMD        | Raven USB 3.1                | 1     | xhci       | 010DB0AED4 |
| 1022:43d5 | 1025:1246 | AMD        | 400 Series Chipset USB 3.... | 1     | xhci       | 310BD9E4AF |
| 1033:0194 | 103c:1631 | NEC Com... | uPD720200 USB 3.0 Host Co... | 1     | xhci       | C240E3A1EA |
| 1039:7001 | 1043:1197 | Silicon... | USB 1.1 Controller           | 1     | ohci       | 1F098AC490 |
| 1039:7001 | 1043:1aa7 | Silicon... | USB 1.1 Controller           | 1     | ohci       | 2FD46CB7C7 |
| 1039:7002 | 1043:1197 | Silicon... | USB 2.0 Controller           | 1     | ehci       | 1F098AC490 |
| 1039:7002 | 1043:1aa7 | Silicon... | USB 2.0 Controller           | 1     | ehci       | 2FD46CB7C7 |
| 10ec:816d | 17aa:5122 | Realtek... |                              | 1     | ehci       | 010DB0AED4 |
| 8086:15e9 | 1558:65d1 | Intel      | JHL7540 Thunderbolt 3 USB... | 1     | xhci       | 96FCD8FC28 |
| 8086:15ec | 1028:0926 | Intel      | JHL7540 Thunderbolt 3 USB... | 1     | xhci       | AA891D8F27 |
| 8086:1c26 | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | C240E3A1EA |
| 8086:1c26 | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 05ED5EB1E4 |
| 8086:1c2d | 103c:1631 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | C240E3A1EA |
| 8086:1c2d | 17aa:21ce | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 05ED5EB1E4 |
| 8086:1e26 | 1028:0535 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | 04CD35A77B |
| 8086:1e26 | 1028:053e | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | A7761EE829 |
| 8086:1e26 | 1043:1467 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | D14C9C0372 |
| 8086:1e26 | 104d:90ac | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | 9A751DDFD8 |
| 8086:1e26 | 17aa:21f9 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | 8ED0FEE673 |
| 8086:1e26 | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | 8060B3FFE1 |
| 8086:1e2d | 1028:0535 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | 04CD35A77B |
| 8086:1e2d | 1028:053e | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | A7761EE829 |
| 8086:1e2d | 1043:1467 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | D14C9C0372 |
| 8086:1e2d | 104d:90ac | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | 9A751DDFD8 |
| 8086:1e2d | 17aa:21f9 | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | 8ED0FEE673 |
| 8086:1e2d | 17aa:21fa | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | 8060B3FFE1 |
| 8086:1e31 | 1028:0535 | Intel      | 7 Series/C210 Series Chip... | 1     | xhci       | 04CD35A77B |
| 8086:1e31 | 1028:053e | Intel      | 7 Series/C210 Series Chip... | 1     | xhci       | A7761EE829 |
| 8086:1e31 | 1043:1467 | Intel      | 7 Series/C210 Series Chip... | 1     | xhci       | D14C9C0372 |
| 8086:1e31 | 104d:90ac | Intel      | 7 Series/C210 Series Chip... | 1     | xhci       | 9A751DDFD8 |
| 8086:1e31 | 17aa:21f9 | Intel      | 7 Series/C210 Series Chip... | 1     | xhci       | 8ED0FEE673 |
| 8086:1e31 | 17aa:21fa | Intel      | 7 Series/C210 Series Chip... | 1     | xhci       | 8060B3FFE1 |
| 8086:24c2 | 1043:1897 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | uhci       | 0D292BCA2F |
| 8086:24c4 | 1043:1897 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | uhci       | 0D292BCA2F |
| 8086:24c7 | 1043:1897 | Intel      | 82801DB/DBL/DBM (ICH4/ICH... | 1     | uhci       | 0D292BCA2F |
| 8086:24cd | 1043:1897 | Intel      | 82801DB/DBM (ICH4/ICH4-M)... | 1     | ehci       | 0D292BCA2F |
| 8086:27c8 | 104d:9075 | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci       | 1E5D0A4D7A |
| 8086:27c9 | 104d:9075 | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci       | 1E5D0A4D7A |
| 8086:27ca | 104d:9075 | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci       | 1E5D0A4D7A |
| 8086:27cb | 104d:9075 | Intel      | NM10/ICH7 Family USB UHCI... | 1     | uhci       | 1E5D0A4D7A |
| 8086:27cc | 104d:9075 | Intel      | NM10/ICH7 Family USB2 EHC... | 1     | ehci       | 1E5D0A4D7A |
| 8086:3b34 | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     | ehci       | 239EEA83C6 |
| 8086:3b34 | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     | ehci       | 6A6B06FC67 |
| 8086:3b3c | 1025:0359 | Intel      | 5 Series/3400 Series Chip... | 1     | ehci       | 239EEA83C6 |
| 8086:3b3c | 1043:1c77 | Intel      | 5 Series/3400 Series Chip... | 1     | ehci       | 6A6B06FC67 |
| 8086:8c26 | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     | ehci       | 3E9076F244 |
| 8086:8c26 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     | ehci       | 9001A6EA5B |
| 8086:8c2d | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     | ehci       | 3E9076F244 |
| 8086:8c2d | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     | ehci       | 9001A6EA5B |
| 8086:8c31 | 103c:1909 | Intel      | 8 Series/C220 Series Chip... | 1     | xhci       | 3E9076F244 |
| 8086:8c31 | 17aa:220e | Intel      | 8 Series/C220 Series Chip... | 1     | xhci       | 9001A6EA5B |
| 8086:9c26 | 17aa:2214 | Intel      | 8 Series USB EHCI #1         | 1     | ehci       | C65CDB97DE |
| 8086:9c31 | 17aa:2214 | Intel      | 8 Series USB xHCI HC         | 1     | xhci       | C65CDB97DE |
| 8086:9ca6 | 1028:0655 | Intel      | Wildcat Point-LP USB EHCI... | 1     | ehci       | B38C2A2E8F |
| 8086:9cb1 | 1028:0655 | Intel      | Wildcat Point-LP USB xHCI... | 1     | xhci       | B38C2A2E8F |
| 8086:9d2f | 103c:8079 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci       | 6C7374D0AB |
| 8086:9d2f | 1558:1313 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci       | 9649F2D700 |
| 8086:9d2f | 17aa:2238 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci       | 68840C222B |
| 8086:9d2f | 17aa:224f | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci       | BB2FCF8D92 |
| 8086:9d2f | 17aa:3845 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci       | 709A3DB7DE |
| 8086:9d2f | 17aa:5062 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci       | 7DEF094AFB |
| 8086:a12f | 1028:06de | Intel      | 100 Series/C230 Series Ch... | 1     | xhci       | 1A7976D306 |
| 8086:a12f | 1043:201f | Intel      | 100 Series/C230 Series Ch... | 1     | xhci       | DC7BB56859 |
| 8086:a12f | 17aa:224d | Intel      | 100 Series/C230 Series Ch... | 1     | xhci       | 81EFA4B3D3 |
| 8086:a12f | 17aa:5050 | Intel      | 100 Series/C230 Series Ch... | 1     | xhci       | DFD9A97EFC |
| 8086:a36d | 1028:0926 | Intel      | Cannon Lake PCH USB 3.1 x... | 1     | xhci       | AA891D8F27 |
| 8086:a36d | 1558:65d1 | Intel      | Cannon Lake PCH USB 3.1 x... | 1     | xhci       | 96FCD8FC28 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1002:9840 | 17aa:3801 | AMD        | Kabini HDMI/DP Audio         | 1     | hdac       | 56D1B97DC1 |
| 1002:9851 | 17aa:3801 | AMD        | Mullins [Radeon R4/R5 Gra... | 1     | vgapci     | 56D1B97DC1 |
| 1022:1439 | 17aa:3801 | AMD        | Family 16h Processor Func... | 1     | pcib       | 56D1B97DC1 |
| 1022:1455 | 1025:1246 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 310BD9E4AF |
| 1022:145a | 1025:1246 | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 310BD9E4AF |
| 1022:1537 | 17aa:3801 | AMD        | Kabini/Mullins PSP-Platfo... | 1     |            | 56D1B97DC1 |
| 1022:1566 | 17aa:3801 | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:156b |           | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:1580 |           | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:1581 |           | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:1582 |           | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:1583 |           | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:1584 |           | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:1585 |           | AMD        | Family 16h (Models 30h-3f... | 1     | hostb      | 56D1B97DC1 |
| 1022:7808 | 17aa:3801 | AMD        | FCH USB EHCI Controller      | 1     | ehci       | 56D1B97DC1 |
| 1022:780b | 17aa:3801 | AMD        | FCH SMBus Controller         | 1     | intsmb     | 56D1B97DC1 |
| 1022:780d | 17aa:3801 | AMD        | FCH Azalia Controller        | 1     | hdac       | 56D1B97DC1 |
| 1022:780e | 17aa:3801 | AMD        | FCH LPC Bridge               | 1     | isab       | 56D1B97DC1 |
| 1022:7813 | 17aa:3801 | AMD        | FCH SD Flash Controller      | 1     | sdhci_pci  | 56D1B97DC1 |
| 1022:7814 | 17aa:3801 | AMD        | FCH USB XHCI Controller      | 1     | xhci       | 56D1B97DC1 |
| 1033:0194 | 17aa:21cf | NEC Com... | uPD720200 USB 3.0 Host Co... | 1     | xhci       | 9BA8051E48 |
| 104c:8039 | 103c:30aa | Texas I... | PCIxx12 Cardbus Controller   | 1     | cbb        | 256E0AE719 |
| 104c:803a | 103c:30aa | Texas I... | PCIxx12 OHCI Compliant IE... | 1     |            | 256E0AE719 |
| 104c:803d | 103c:30aa | Texas I... | PCIxx12 GemCore based Sma... | 1     |            | 256E0AE719 |
| 10de:0e0a | 103c:2256 | Nvidia     | GK104 HDMI Audio Controller  | 1     | hdac       | D615B5020D |
| 10de:11b6 | 103c:2256 | Nvidia     | GK104GLM [Quadro K3100M]     | 1     | vgapci     | D615B5020D |
| 10de:174d | 1043:1a1e | Nvidia     | GM108M [GeForce MX130]       | 1     | vgapci     | 7B85836A46 |
| 10ec:b822 | 17aa:b024 | Realtek... | RTL8822BE 802.11a/b/g/n/a... | 1     |            | 010DB0AED4 |
| 1180:0476 | 1028:0262 | Ricoh      | RL5c476 II                   | 1     | cbb        | 54854343E4 |
| 1180:0822 | 1028:0262 | Ricoh      | R5C822 SD/SDIO/MMC/MS/MSP... | 1     | sdhci_pci  | 54854343E4 |
| 1180:0832 | 1028:0262 | Ricoh      | R5C832 IEEE 1394 Controller  | 1     |            | 54854343E4 |
| 1180:0843 | 1028:0262 | Ricoh      | R5C843 MMC Host Controller   | 1     |            | 54854343E4 |
| 1180:e822 | 1028:040a | Ricoh      | MMC/SD Host Controller       | 1     | sdhci_pci  | 996540C1DC |
| 1180:e823 | 17aa:21cf | Ricoh      | PCIe SDXC/MMC Host Contro... | 1     | sdhci_pci  | 9BA8051E48 |
| 1180:e832 | 1028:040a | Ricoh      | R5C832 PCIe IEEE 1394 Con... | 1     |            | 996540C1DC |
| 1ae9:0101 |           | Wilocity   | Wil6200 PCI Express Upstr... | 1     | pcib       | 1DE87C0000 |
| 1ae9:0201 |           | Wilocity   | Wil6200 Wireless PCI Expr... | 1     | pcib       | 1DE87C0000 |
| 8086:0044 | 1028:040a | Intel      | Core Processor DRAM Contr... | 1     | hostb      | 996540C1DC |
| 8086:0046 | 1028:040a | Intel      | Core Processor Integrated... | 1     | vgapci     | 996540C1DC |
| 8086:0104 | 1028:0492 | Intel      | 2nd Generation Core Proce... | 1     | hostb      | 2EBFA76C28 |
| 8086:0104 | 17aa:21cf | Intel      | 2nd Generation Core Proce... | 1     | hostb      | 9BA8051E48 |
| 8086:0126 | 1028:0492 | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 2EBFA76C28 |
| 8086:0126 | 1028:0493 | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 324265FE3F |
| 8086:0126 | 17aa:21d1 | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 9BA8051E48 |
| 8086:0153 | 1043:108d | Intel      | 3rd Gen Core Processor Th... | 1     |            | B9058F83DB |
| 8086:0154 | 1043:108d | Intel      | 3rd Gen Core processor DR... | 1     | hostb      | B9058F83DB |
| 8086:0166 | 1043:108d | Intel      | 3rd Gen Core processor Gr... | 1     | vgapci     | B9058F83DB |
| 8086:0a04 | 1028:05ca | Intel      | Haswell-ULT DRAM Controller  | 1     | hostb      | 1DE87C0000 |
| 8086:0a0c | 1028:05ca | Intel      | Haswell-ULT HD Audio Cont... | 1     | hdac       | 1DE87C0000 |
| 8086:0a16 | 1028:05ca | Intel      | Haswell-ULT Integrated Gr... | 1     | vgapci     | 1DE87C0000 |
| 8086:0c01 | 103c:2255 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | pcib       | D615B5020D |
| 8086:0c04 | 103c:2255 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | hostb      | D615B5020D |
| 8086:15bf | 17aa:2279 | Intel      | JHL6240 Thunderbolt 3 NHI... | 1     |            | 90E2B57F16 |
| 8086:15bf | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 NHI... | 1     |            | 2D0DC32CED |
| 8086:15c0 | 17aa:2279 | Intel      | JHL6240 Thunderbolt 3 Bri... | 1     | pcib       | 90E2B57F16 |
| 8086:15c0 | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 Bri... | 1     | pcib       | 2D0DC32CED |
| 8086:15c1 | 17aa:2279 | Intel      | JHL6240 Thunderbolt 3 USB... | 1     | xhci       | 90E2B57F16 |
| 8086:15c1 | 2222:1111 | Intel      | JHL6240 Thunderbolt 3 USB... | 1     | xhci       | 2D0DC32CED |
| 8086:1604 | 17aa:5034 | Intel      | Broadwell-U Host Bridge -OPI | 1     | hostb      | F83F765AB3 |
| 8086:160c | 17aa:5034 | Intel      | Broadwell-U Audio Controller | 1     | hdac       | F83F765AB3 |
| 8086:1616 | 17aa:5036 | Intel      | HD Graphics 5500             | 1     | vgapci     | F83F765AB3 |
| 8086:1903 | 1043:1311 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 7B85836A46 |
| 8086:1903 | 17aa:2258 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 2D0DC32CED |
| 8086:1903 | 17aa:2279 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     |            | 90E2B57F16 |
| 8086:1911 | 17aa:2258 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 2D0DC32CED |
| 8086:1911 | 17aa:2279 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 90E2B57F16 |
| 8086:1c10 | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 2EBFA76C28 |
| 8086:1c10 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 9BA8051E48 |
| 8086:1c12 | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 2EBFA76C28 |
| 8086:1c12 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 9BA8051E48 |
| 8086:1c14 | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 2EBFA76C28 |
| 8086:1c16 | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 2EBFA76C28 |
| 8086:1c16 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 9BA8051E48 |
| 8086:1c18 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 9BA8051E48 |
| 8086:1c1a | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 2EBFA76C28 |
| 8086:1c1c | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 9BA8051E48 |
| 8086:1c22 | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     |            | 2EBFA76C28 |
| 8086:1c22 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | ichsmb     | 9BA8051E48 |
| 8086:1c26 | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 2EBFA76C28 |
| 8086:1c26 | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 9BA8051E48 |
| 8086:1c2d | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 2EBFA76C28 |
| 8086:1c2d | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 9BA8051E48 |
| 8086:1c3a | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     |            | 2EBFA76C28 |
| 8086:1c3a | 17aa:21cf | Intel      | 6 Series/C200 Series Chip... | 1     |            | 9BA8051E48 |
| 8086:1c3d | 1028:0492 | Intel      | 6 Series/C200 Series Chip... | 1     | uart       | 2EBFA76C28 |
| 8086:1c4f | 1028:0492 | Intel      | QM67 Express Chipset LPC ... | 1     | isab       | 2EBFA76C28 |
| 8086:1c4f | 17aa:21cf | Intel      | QM67 Express Chipset LPC ... | 1     | isab       | 9BA8051E48 |
| 8086:1e10 | 1043:108d | Intel      | 7 Series/C216 Chipset Fam... | 1     | pcib       | B9058F83DB |
| 8086:1e12 | 1043:108d | Intel      | 7 Series/C210 Series Chip... | 1     | pcib       | B9058F83DB |
| 8086:1e16 | 1043:108d | Intel      | 7 Series/C216 Chipset Fam... | 1     | pcib       | B9058F83DB |
| 8086:1e22 | 1043:108d | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | B9058F83DB |
| 8086:1e24 | 1043:108d | Intel      | 7 Series/C210 Series Chip... | 1     |            | B9058F83DB |
| 8086:1e26 | 1043:108d | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | B9058F83DB |
| 8086:1e2d | 1043:108d | Intel      | 7 Series/C216 Chipset Fam... | 1     | ehci       | B9058F83DB |
| 8086:1e31 | 1043:108d | Intel      | 7 Series/C210 Series Chip... | 1     | xhci       | B9058F83DB |
| 8086:1e3a | 1043:108d | Intel      | 7 Series/C216 Chipset Fam... | 1     |            | B9058F83DB |
| 8086:1e59 | 1043:108d | Intel      | HM76 Express Chipset LPC ... | 1     | isab       | B9058F83DB |
| 8086:27a0 | 103c:30aa | Intel      | Mobile 945GM/PM/GMS, 943/... | 1     | hostb      | 256E0AE719 |
| 8086:27a2 | 103c:30aa | Intel      | Mobile 945GM/GMS, 943/940... | 1     | vgapci     | 256E0AE719 |
| 8086:27a6 | 103c:30aa | Intel      | Mobile 945GM/GMS/GME, 943... | 1     | vgapci     | 256E0AE719 |

