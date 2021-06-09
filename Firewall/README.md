Most popular PCI devices in Firewalls
=====================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Firewalls ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Signal processing ](#signal-processing-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/ide ](#storageide-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1f13 | 8086:8086 | Intel      | Atom processor C2000 PCIe... | 8     | pcib       | 8D2F78F042 |
| 8086:1f14 |           | Intel      | Atom processor C2000 RAS     | 8     | hostb      | 8D2F78F042 |
| 1a03:1150 | 1a03:1150 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 7     | pcib       | B6099E8EAD |
| 8086:0c01 | 8086:0c01 | Intel      | Xeon E3-1200 v3/4th Gen C... | 7     | pcib       | 88EA908224 |
| 8086:8c10 | 8086:8c10 | Intel      | 8 Series/C220 Series Chip... | 7     | pcib       | 88EA908224 |
| 8086:8c18 | 8086:8c18 | Intel      | 8 Series/C220 Series Chip... | 7     | pcib       | 88EA908224 |
| 8086:1f0e |           | Intel      | Atom processor C2000 SoC ... | 6     | hostb      | 12B400125A |
| 8086:8c12 | 8086:8c12 | Intel      | 8 Series/C220 Series Chip... | 6     | pcib       | 428B16A419 |
| 8086:8c14 | 8086:8c14 | Intel      | 8 Series/C220 Series Chip... | 6     | pcib       | 428B16A419 |
| 8086:8c16 | 8086:8c16 | Intel      | 8 Series/C220 Series Chip... | 6     | pcib       | 428B16A419 |
| 8086:8c1a | 8086:8c1a | Intel      | 8 Series/C220 Series Chip... | 6     | pcib       | 428B16A419 |
| 8086:0c00 | 8086:0c00 | Intel      | 4th Gen Core Processor DR... | 5     | hostb      | 428B16A419 |
| 8086:1f10 | 8086:7270 | Intel      | Atom processor C2000 PCIe... | 5     | pcib       | 8D2F78F042 |
| 8086:1f11 | 8086:7270 | Intel      | Atom processor C2000 PCIe... | 5     | pcib       | 8D2F78F042 |
| 8086:1f12 | 8086:7270 | Intel      | Atom processor C2000 PCIe... | 5     | pcib       | 8D2F78F042 |
| 8086:1f38 | 8086:7270 | Intel      | Atom processor C2000 PCU     | 5     | isab       | 8D2F78F042 |
| 8086:8c5c | 8086:8c5c | Intel      | H81 Express LPC Controller   | 5     | isab       | 428B16A419 |
| 8086:244e | 8086:244e | Intel      | 82801 PCI Bridge             | 4     | pcib       | B8F4885EF9 |
| 8086:5ad8 |           | Intel      | Celeron N3350/Pentium N42... | 4     | pcib       | 6324A2A9A9 |
| 8086:5ad9 |           | Intel      | Celeron N3350/Pentium N42... | 4     | pcib       | 6324A2A9A9 |
| 8086:5ada |           | Intel      | Celeron N3350/Pentium N42... | 4     | pcib       | 6324A2A9A9 |
| 8086:5adb |           | Intel      | Celeron N3350/Pentium N42... | 4     | pcib       | 6324A2A9A9 |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | isab       | 6324A2A9A9 |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | hostb      | 6324A2A9A9 |
| 10b5:8604 | 10b5:8604 | PLX Tec... | PEX 8604 4-lane, 4-Port P... | 3     | pcib       | B8F4885EF9 |
| 10b5:8605 | 10b5:8605 | PLX Tec... | PEX 8605 PCI Express 4-po... | 3     | pcib       | 8D2F78F042 |
| 8086:1901 | 8086:2015 | Intel      | 6th-10th Gen Core Process... | 3     | pcib       | DA48CA6303 |
| 8086:1f10 | 1462:1401 | Intel      | Atom processor C2000 PCIe... | 3     | pcib       | 12B400125A |
| 8086:1f11 | 1462:1401 | Intel      | Atom processor C2000 PCIe... | 3     | pcib       | 12B400125A |
| 8086:1f12 | 1462:1401 | Intel      | Atom processor C2000 PCIe... | 3     | pcib       | 12B400125A |
| 8086:1f38 | 1462:1401 | Intel      | Atom processor C2000 PCU     | 3     | isab       | 12B400125A |
| 8086:27b8 | 8086:27b8 | Intel      | 82801GB/GR (ICH7 Family) ... | 3     | isab       | B8F4885EF9 |
| 8086:27d0 | 8086:27d0 | Intel      | NM10/ICH7 Family PCI Expr... | 3     | pcib       | B8F4885EF9 |
| 8086:27d2 | 8086:27d2 | Intel      | NM10/ICH7 Family PCI Expr... | 3     | pcib       | B8F4885EF9 |
| 8086:27d4 | 8086:27d4 | Intel      | NM10/ICH7 Family PCI Expr... | 3     | pcib       | B8F4885EF9 |
| 8086:27d6 | 8086:27d6 | Intel      | NM10/ICH7 Family PCI Expr... | 3     | pcib       | B8F4885EF9 |
| 8086:27e0 | 8086:27e0 | Intel      | 82801GR/GH/GHM (ICH7 Fami... | 3     | pcib       | B8F4885EF9 |
| 8086:27e2 | 8086:27e2 | Intel      | 82801GR/GH/GHM (ICH7 Fami... | 3     | pcib       | B8F4885EF9 |
| 8086:2e30 | 8086:2e30 | Intel      | 4 Series Chipset DRAM Con... | 3     | hostb      | B8F4885EF9 |
| 8086:a114 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | pcib       | DA48CA6303 |
| 8086:a115 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | pcib       | DA48CA6303 |
| 8086:a116 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | pcib       | DA48CA6303 |
| 8086:a117 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | pcib       | DA48CA6303 |
| 8086:a118 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | pcib       | DA48CA6303 |
| 12d8:2404 |           | Pericom... | PI7C9X2G404 EL/SL PCIe2 4... | 2     | pcib       | DA48CA6303 |
| 8086:0c08 | 8086:0c08 | Intel      | Xeon E3-1200 v3 Processor... | 2     | hostb      | 88EA908224 |
| 8086:190f | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 2     | hostb      | DA48CA6303 |
| 8086:1f0b |           | Intel      | Atom processor C2000 SoC ... | 2     | hostb      | 8D2F78F042 |
| 8086:8c1c | 8086:8c1c | Intel      | 8 Series/C220 Series Chip... | 2     | pcib       | 88EA908224 |
| 8086:a119 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 2     | pcib       | DA48CA6303 |
| 8086:a143 | 8086:7270 | Intel      | H110 Chipset LPC/eSPI Con... | 2     | isab       | DA48CA6303 |
| 10b5:8616 | 10b5:8616 | PLX Tec... | PEX 8616 16-lane, 4-Port ... | 1     | pcib       | 88EA908224 |
| 8086:0100 | 8086:0100 | Intel      | 2nd Generation Core Proce... | 1     | hostb      | 8B25E6B31B |
| 8086:0101 | 8086:0101 | Intel      | Xeon E3-1200/2nd Generati... | 1     | pcib       | 8B25E6B31B |
| 8086:0105 | 8086:0105 | Intel      | Xeon E3-1200/2nd Generati... | 1     | pcib       | 8B25E6B31B |
| 8086:0c05 | 8086:0c05 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | pcib       | 88EA908224 |
| 8086:0c09 | 8086:0c09 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | pcib       | 88EA908224 |
| 8086:0f00 | 8086:0f31 | Intel      | Atom Processor Z36xxx/Z37... | 1     | hostb      | 6F058F9A0C |
| 8086:0f1c | 8086:0f1c | Intel      | Atom Processor Z36xxx/Z37... | 1     | isab       | 6F058F9A0C |
| 8086:0f48 | 8086:0f48 | Intel      | Atom Processor E3800 Seri... | 1     | pcib       | 6F058F9A0C |
| 8086:0f4a | 8086:0f4a | Intel      | Atom Processor E3800 Seri... | 1     | pcib       | 6F058F9A0C |
| 8086:0f4c | 8086:0f4c | Intel      | Atom Processor E3800 Seri... | 1     | pcib       | 6F058F9A0C |
| 8086:0f4e | 8086:0f4e | Intel      | Atom Processor E3800 Seri... | 1     | pcib       | 6F058F9A0C |
| 8086:1905 | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | pcib       | C7392A1F0D |
| 8086:191f | 8086:2015 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | hostb      | 31F0629346 |
| 8086:1980 | 8086:1999 | Intel      | Atom Processor C3000 Seri... | 1     | hostb      | B6099E8EAD |
| 8086:19a1 |           | Intel      | Atom Processor C3000 Seri... | 1     | hostb      | B6099E8EAD |
| 8086:19a3 |           | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19a4 |           | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19a5 | 8086:19a5 | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19a6 | 8086:19a6 | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19a7 | 8086:19a7 | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19a8 | 8086:19a8 | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19a9 | 8086:19a9 | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19aa | 8086:19aa | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19ab | 8086:19ab | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19d1 |           | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19d2 |           | Intel      | Atom Processor C3000 Seri... | 1     | pcib       | B6099E8EAD |
| 8086:19dc | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 1     | isab       | B6099E8EAD |
| 8086:1c10 | 8086:1c10 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 8B25E6B31B |
| 8086:1c18 | 8086:1c18 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 8B25E6B31B |
| 8086:1c56 | 8086:1c56 | Intel      | C206 Chipset LPC Controller  | 1     | isab       | 8B25E6B31B |
| 8086:2448 | 8086:2448 | Intel      | 82801 Mobile PCI Bridge      | 1     | pcib       | D7E1C83CA8 |
| 8086:2815 | 8086:2815 | Intel      | 82801HM (ICH8M) LPC Inter... | 1     | isab       | D7E1C83CA8 |
| 8086:283f | 8086:283f | Intel      | 82801H (ICH8 Family) PCI ... | 1     | pcib       | D7E1C83CA8 |
| 8086:2841 | 8086:2841 | Intel      | 82801H (ICH8 Family) PCI ... | 1     | pcib       | D7E1C83CA8 |
| 8086:2843 | 8086:2843 | Intel      | 82801H (ICH8 Family) PCI ... | 1     | pcib       | D7E1C83CA8 |
| 8086:2845 | 8086:2845 | Intel      | 82801H (ICH8 Family) PCI ... | 1     | pcib       | D7E1C83CA8 |
| 8086:8c1e | 8086:8c1e | Intel      | 8 Series/C220 Series Chip... | 1     | pcib       | C6D1DB88BF |
| 8086:8c4e | 8086:8c4e | Intel      | Q87 Express LPC Controller   | 1     | isab       | C6D1DB88BF |
| 8086:8c56 | 8086:8c56 | Intel      | C226 Series Chipset Famil... | 1     | isab       | 88EA908224 |
| 8086:a010 | 8086:a010 | Intel      | Atom Processor D4xx/D5xx/... | 1     | hostb      | D7E1C83CA8 |
| 8086:a110 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | C7392A1F0D |
| 8086:a111 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | C7392A1F0D |
| 8086:a112 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | C7392A1F0D |
| 8086:a113 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | C7392A1F0D |
| 8086:a11a | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | C7392A1F0D |
| 8086:a11b | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | C7392A1F0D |
| 8086:a11c | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | C7392A1F0D |
| 8086:a146 | 8086:7270 | Intel      | Q170 Chipset LPC/eSPI Con... | 1     | isab       | C7392A1F0D |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1f18 |           | Intel      | Atom processor C2000 QAT     | 8     |            | 8D2F78F042 |
| 8086:19e2 |           | Intel      | Atom Processor C3000 Seri... | 1     |            | B6099E8EAD |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     |            | 6324A2A9A9 |
| 8086:5a9c | 8086:7270 | Intel      |                              | 4     |            | 6324A2A9A9 |
| 8086:5a9e | 8086:7270 | Intel      |                              | 4     |            | 6324A2A9A9 |
| 8086:a13a | 8086:1999 | Intel      | 100 Series/C230 Series Ch... | 3     |            | DA48CA6303 |
| 8086:19d3 | 8086:19d3 | Intel      | Atom Processor C3000 Seri... | 1     |            | B6099E8EAD |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0f18 | 8086:0f18 | Intel      | Atom Processor Z36xxx/Z37... | 1     |            | 6F058F9A0C |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 7     | vgapci     | B6099E8EAD |
| 8086:0402 | 8086:0402 | Intel      | Xeon E3-1200 v3/4th Gen C... | 4     | vgapci     | 428B16A419 |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 4     | vgapci     | 6324A2A9A9 |
| 8086:2e32 | 8086:2e32 | Intel      | 4 Series Chipset Integrat... | 3     | agp        | B8F4885EF9 |
| 8086:2e33 | 8086:2e32 | Intel      | 4 Series Chipset Integrat... | 3     | vgapci     | B8F4885EF9 |
| 8086:1912 |           | Intel      | HD Graphics 530              | 2     | vgapci     | 31F0629346 |
| 8086:0102 | 8086:0102 | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | 8B25E6B31B |
| 8086:0412 | 8086:0412 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     | vgapci     | C6D1DB88BF |
| 8086:041a | 8086:041a | Intel      | Xeon E3-1200 v3 Processor... | 1     | vgapci     | 88EA908224 |
| 8086:1902 |           | Intel      | HD Graphics 510              | 1     | vgapci     | DA48CA6303 |
| 8086:a011 | 8086:a011 | Intel      | Atom Processor D4xx/D5xx/... | 1     | agp        | D7E1C83CA8 |
| 8086:a012 | 8086:a011 | Intel      | Atom Processor D4xx/D5xx/... | 1     | vgapci     | D7E1C83CA8 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     |            | DA48CA6303 |
| 8086:19de | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 1     |            | B6099E8EAD |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1533 |           | Intel      | I210 Gigabit Network Conn... | 8     | igb        | 428B16A419 |
| 8086:1533 | 15bb:30e0 | Intel      | I210 Gigabit Network Conn... | 6     | igb        | 428B16A419 |
| 8086:1536 |           | Intel      | I210 Gigabit Fiber Networ... | 4     | igb        | B6099E8EAD |
| 8086:1539 | 15bb:34e6 | Intel      | I211 Gigabit Network Conn... | 3     | igb        | DA48CA6303 |
| 8086:10c6 | 1374:0203 | Intel      | 82598EB 10-Gigabit AF Dua... | 1     | ix         | C6D1DB88BF |
| 8086:10c9 |           | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 8B25E6B31B |
| 8086:10e6 |           | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 8B25E6B31B |
| 8086:10fb |           | Intel      | 82599ES 10-Gigabit SFI/SF... | 1     | ix         | C7392A1F0D |
| 8086:150c |           | Intel      | 82583V Gigabit Network Co... | 1     | em         | D7E1C83CA8 |
| 8086:1521 |           | Intel      | I350 Gigabit Network Conn... | 1     | igb        | C6D1DB88BF |
| 8086:1521 | 15bb:0008 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 88EA908224 |
| 8086:1522 |           | Intel      | I350 Gigabit Fiber Networ... | 1     | igb        | C6D1DB88BF |
| 8086:1539 | 10f3:0101 | Intel      | I211 Gigabit Network Conn... | 1     | igb        | 6324A2A9A9 |
| 8086:15e4 |           | Intel      | Ethernet Connection X553 ... | 1     | ix         | B6099E8EAD |
| 8086:15e5 |           | Intel      | Ethernet Connection X553 ... | 1     | ix         | B6099E8EAD |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:0030 | 168c:3116 | Qualcom... | AR93xx Wireless Network A... | 1     | ath        | 2654C6E951 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1539 |           | Intel      | I211 Gigabit Network Conn... | 13    | igb        | 6324A2A9A9 |
| 8086:1f41 | 8086:1f41 | Intel      | Ethernet Connection I354     | 8     | igb        | 8D2F78F042 |
| 8086:10d3 |           | Intel      | 82574L Gigabit Network Co... | 3     | em         | B8F4885EF9 |
| 8086:1531 |           | Intel      | I210 Gigabit Unprogrammed    | 1     |            | 3131AAE37B |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     |            | 6324A2A9A9 |
| 8086:19e0 | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 1     |            | B6099E8EAD |

### Signal processing (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a131 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     |            | DA48CA6303 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c22 | 8086:8c22 | Intel      | 8 Series/C220 Series Chip... | 7     |            | 88EA908224 |
| 8086:1f3c | 8086:7270 | Intel      | Atom processor C2000 PCU ... | 5     |            | 8D2F78F042 |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     |            | 6324A2A9A9 |
| 8086:1f3c | 1462:1401 | Intel      | Atom processor C2000 PCU ... | 3     |            | 12B400125A |
| 8086:27da | 8086:27da | Intel      | NM10/ICH7 Family SMBus Co... | 3     |            | B8F4885EF9 |
| 8086:a123 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     |            | DA48CA6303 |
| 8086:0f12 | 8086:0f12 | Intel      | Atom Processor E3800 Seri... | 1     |            | 6F058F9A0C |
| 8086:19df | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 1     |            | B6099E8EAD |
| 8086:1c22 | 8086:1c22 | Intel      | 6 Series/C200 Series Chip... | 1     |            | 8B25E6B31B |
| 8086:283e | 8086:283e | Intel      | 82801H (ICH8 Family) SMBu... | 1     |            | D7E1C83CA8 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:0c0c | 8086:0c0c | Intel      | Xeon E3-1200 v3/4th Gen C... | 5     | hdac       | 428B16A419 |
| 8086:a170 | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | hdac       | DA48CA6303 |
| 8086:0f04 | 8086:7270 | Intel      | Atom Processor Z36xxx/Z37... | 1     | hdac       | 6F058F9A0C |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c02 | 8086:8c02 | Intel      | 8 Series/C220 Series Chip... | 7     | ahci       | 88EA908224 |
| 8086:1f32 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 5     | ahci       | 8D2F78F042 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | ahci       | 6324A2A9A9 |
| 8086:1f32 | 1462:1401 | Intel      | Atom processor C2000 AHCI... | 3     | ahci       | 12B400125A |
| 8086:27c1 | 8086:27c0 | Intel      | NM10/ICH7 Family SATA Con... | 3     | ahci       | B8F4885EF9 |
| 8086:a102 | 8086:7270 | Intel      | Q170/Q150/B150/H170/H110/... | 3     | ahci       | DA48CA6303 |
| 8086:1f22 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 2     | ahci       | 7B7714416C |
| 8086:0f23 | 8086:0f23 | Intel      | Atom Processor E3800 Seri... | 1     | ahci       | 6F058F9A0C |
| 8086:19b2 | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 1     | ahci       | B6099E8EAD |
| 8086:1c02 | 8086:1c02 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 8B25E6B31B |
| 8086:2829 | 8086:2829 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 1     | ahci       | D7E1C83CA8 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:27df | 8086:27df | Intel      | 82801G (ICH7 Family) IDE ... | 2     | atapci     | B8F4885EF9 |
| 8086:2850 | 8086:2850 | Intel      | 82801HM/HEM (ICH8M/ICH8M-... | 1     | atapci     | D7E1C83CA8 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1f15 |           | Intel      | Atom processor C2000 SMBu... | 8     |            | 8D2F78F042 |
| 8086:1f16 |           | Intel      | Atom processor C2000 RCEC    | 8     |            | 8D2F78F042 |
| 8086:19a2 |           | Intel      | Atom Processor C3000 Seri... | 1     |            | B6099E8EAD |
| 8086:19ac |           | Intel      | Atom Processor C3000 Seri... | 1     |            | B6099E8EAD |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c26 | 8086:8c26 | Intel      | 8 Series/C220 Series Chip... | 7     | ehci       | 88EA908224 |
| 8086:8c2d | 8086:8c2d | Intel      | 8 Series/C220 Series Chip... | 7     | ehci       | 88EA908224 |
| 8086:8c31 | 8086:8c31 | Intel      | 8 Series/C220 Series Chip... | 7     | xhci       | 88EA908224 |
| 8086:1f2c | 8086:7270 | Intel      | Atom processor C2000 USB ... | 5     | ehci       | 8D2F78F042 |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 4     | xhci       | 6324A2A9A9 |
| 8086:1f2c | 1462:1401 | Intel      | Atom processor C2000 USB ... | 3     | ehci       | 12B400125A |
| 8086:27c8 | 8086:27c8 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci       | B8F4885EF9 |
| 8086:27c9 | 8086:27c9 | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci       | B8F4885EF9 |
| 8086:27ca | 8086:27ca | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci       | B8F4885EF9 |
| 8086:27cb | 8086:27cb | Intel      | NM10/ICH7 Family USB UHCI... | 3     | uhci       | B8F4885EF9 |
| 8086:27cc | 8086:27cc | Intel      | NM10/ICH7 Family USB2 EHC... | 3     | ehci       | B8F4885EF9 |
| 8086:a12f | 8086:7270 | Intel      | 100 Series/C230 Series Ch... | 3     | xhci       | DA48CA6303 |
| 8086:0f35 | 8086:0f35 | Intel      | Atom Processor Z36xxx/Z37... | 1     | xhci       | 6F058F9A0C |
| 8086:19d0 | 8086:7270 | Intel      | Atom Processor C3000 Seri... | 1     | xhci       | B6099E8EAD |
| 8086:1c26 | 8086:1c26 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 8B25E6B31B |
| 8086:1c2d | 8086:1c2d | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 8B25E6B31B |
| 8086:2830 | 8086:2830 | Intel      | 82801H (ICH8 Family) USB ... | 1     | uhci       | D7E1C83CA8 |
| 8086:2831 | 8086:2831 | Intel      | 82801H (ICH8 Family) USB ... | 1     | uhci       | D7E1C83CA8 |
| 8086:2836 | 8086:2836 | Intel      | 82801H (ICH8 Family) USB2... | 1     | ehci       | D7E1C83CA8 |

