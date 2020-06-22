Most popular PCI devices in Servers
===================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Servers ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Network ](#network-pci)
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

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:1150 | 15d9:0884 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 2     | pcib       | 18EA6EC987 |
| 8086:244e | 1028:02f1 | Intel      | 82801 PCI Bridge             | 2     | pcib       | D224B1F8E0 |
| 8086:a110 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     | pcib       | 18EA6EC987 |
| 8086:a111 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     | pcib       | 18EA6EC987 |
| 8086:a114 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     | pcib       | 18EA6EC987 |
| 8086:a116 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     | pcib       | 18EA6EC987 |
| 8086:a149 | 15d9:0884 | Intel      | C236 Chipset LPC/eSPI Con... | 2     | isab       | 18EA6EC987 |
| 1022:1200 |           | AMD        | Family 10h Processor Hype... | 1     | hostb      | 4EBC960E9C |
| 1022:1201 |           | AMD        | Family 10h Processor Addr... | 1     | hostb      | 4EBC960E9C |
| 1022:1202 |           | AMD        | Family 10h Processor DRAM... | 1     | hostb      | 4EBC960E9C |
| 1022:1203 |           | AMD        | Family 10h Processor Misc... | 1     | hostb      | 4EBC960E9C |
| 1022:1204 |           | AMD        | Family 10h Processor Link... | 1     | hostb      | 4EBC960E9C |
| 10de:0370 | 10de:cb84 | Nvidia     | MCP55 PCI bridge             | 1     | pcib       | 970467EFEF |
| 1166:0036 | 103c:3110 | Broadcom   | BCM5785 [HT1000] PCI/PCI-... | 1     | pcib       | 4EBC960E9C |
| 1166:0103 |           | Broadcom   | EPB PCI-Express to PCI-X ... | 1     | pcib       | 4EBC960E9C |
| 1166:0104 | 103c:3111 | Broadcom   | BCM5785 [HT1000] PCI/PCI-... | 1     | pcib       | 4EBC960E9C |
| 1166:0140 | 103c:3113 | Broadcom   | HT2100 PCI-Express Bridge    | 1     | pcib       | 4EBC960E9C |
| 1166:0142 | 103c:3114 | Broadcom   | HT2100 PCI-Express Bridge    | 1     | pcib       | 4EBC960E9C |
| 1166:0142 | 103c:3116 | Broadcom   | HT2100 PCI-Express Bridge    | 1     | pcib       | 4EBC960E9C |
| 1166:0144 | 103c:3115 | Broadcom   | HT2100 PCI-Express Bridge    | 1     | pcib       | 4EBC960E9C |
| 1166:0144 | 103c:3117 | Broadcom   | HT2100 PCI-Express Bridge    | 1     | pcib       | 4EBC960E9C |
| 1166:0205 | 1166:0201 | Broadcom   | BCM5785 [HT1000] Legacy S... | 1     | hostb      | 4EBC960E9C |
| 1166:0234 | 1166:0230 | Broadcom   | BCM5785 [HT1000] LPC         | 1     | isab       | 4EBC960E9C |
| 1912:001a | 1912:001a | Renesas... | SH7758 PCIe-PCI Bridge [PPB] | 1     | pcib       | E59AEBEE71 |
| 1912:001d | 1912:001d | Renesas... | SH7758 PCIe Switch [PS]      | 1     | pcib       | E59AEBEE71 |
| 8086:0108 | 1734:11b9 | Intel      | Xeon E3-1200 Processor Fa... | 1     | hostb      | 6CF7F9EA4B |
| 8086:0e00 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | hostb      | 1F4D1E4607 |
| 8086:0e01 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | pcib       | 1F4D1E4607 |
| 8086:0e02 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | pcib       | 1F4D1E4607 |
| 8086:0e03 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | pcib       | 1F4D1E4607 |
| 8086:0e08 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | pcib       | 1F4D1E4607 |
| 8086:0e0a | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     | pcib       | 1F4D1E4607 |
| 8086:1901 | 1028:06aa | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | pcib       | E59AEBEE71 |
| 8086:1901 | 15d9:0884 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | pcib       | 360E63CC66 |
| 8086:1909 | 1028:06aa | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | pcib       | E59AEBEE71 |
| 8086:1918 | 15d9:0884 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | hostb      | 360E63CC66 |
| 8086:1c10 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 6CF7F9EA4B |
| 8086:1c18 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 6CF7F9EA4B |
| 8086:1c1c | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 6CF7F9EA4B |
| 8086:1c1e | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | 6CF7F9EA4B |
| 8086:1c52 | 1734:11cb | Intel      | C202 Chipset LPC Controller  | 1     | isab       | 6CF7F9EA4B |
| 8086:1d10 | 15d9:0703 | Intel      | C600/X79 series chipset P... | 1     | pcib       | 1F4D1E4607 |
| 8086:1d12 | 15d9:0703 | Intel      | C600/X79 series chipset P... | 1     | pcib       | 1F4D1E4607 |
| 8086:1d3e | 15d9:0703 | Intel      | C600/X79 series chipset P... | 1     | pcib       | 1F4D1E4607 |
| 8086:1d41 | 15d9:0703 | Intel      | C600/X79 series chipset L... | 1     | isab       | 1F4D1E4607 |
| 8086:244e | 1028:0235 | Intel      | 82801 PCI Bridge             | 1     | pcib       | E2AB2682CB |
| 8086:244e | 1028:02a4 | Intel      | 82801 PCI Bridge             | 1     | pcib       | 245D470945 |
| 8086:244e | 15d9:0703 | Intel      | 82801 PCI Bridge             | 1     | pcib       | 1F4D1E4607 |
| 8086:244e | 1734:11cb | Intel      | 82801 PCI Bridge             | 1     | pcib       | 6CF7F9EA4B |
| 8086:244e | 8086:3476 | Intel      | 82801 PCI Bridge             | 1     | pcib       | 9A893E2CC9 |
| 8086:244e | 8086:34ec | Intel      | 82801 PCI Bridge             | 1     | pcib       | 6B7FBA08DD |
| 8086:25d8 | 8086:3476 | Intel      | 5000P Chipset Memory Cont... | 1     | hostb      | 9A893E2CC9 |
| 8086:25e3 |           | Intel      | 5000 Series Chipset PCI E... | 1     | pcib       | 9A893E2CC9 |
| 8086:25e5 |           | Intel      | 5000 Series Chipset PCI E... | 1     | pcib       | 9A893E2CC9 |
| 8086:25e7 |           | Intel      | 5000 Series Chipset PCI E... | 1     | pcib       | 9A893E2CC9 |
| 8086:25f0 | 8086:3476 | Intel      | 5000 Series Chipset FSB R... | 1     | hostb      | 9A893E2CC9 |
| 8086:25f1 | 8086:3476 | Intel      | 5000 Series Chipset Reser... | 1     | hostb      | 9A893E2CC9 |
| 8086:25f3 | 8086:3476 | Intel      | 5000 Series Chipset Reser... | 1     | hostb      | 9A893E2CC9 |
| 8086:25f5 | 8086:3476 | Intel      | 5000 Series Chipset FBD R... | 1     | hostb      | 9A893E2CC9 |
| 8086:25f6 | 8086:3476 | Intel      | 5000 Series Chipset FBD R... | 1     | hostb      | 9A893E2CC9 |
| 8086:25f7 |           | Intel      | 5000 Series Chipset PCI E... | 1     | pcib       | 9A893E2CC9 |
| 8086:25f8 |           | Intel      | 5000 Series Chipset PCI E... | 1     | pcib       | 9A893E2CC9 |
| 8086:25f9 |           | Intel      | 5000 Series Chipset PCI E... | 1     | pcib       | 9A893E2CC9 |
| 8086:2670 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | isab       | 9A893E2CC9 |
| 8086:2690 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | pcib       | 9A893E2CC9 |
| 8086:2918 | 1028:0235 | Intel      | 82801IB (ICH9) LPC Interf... | 1     | isab       | E2AB2682CB |
| 8086:3406 | 1028:0235 | Intel      | 5520 I/O Hub to ESI Port     | 1     | hostb      | E2AB2682CB |
| 8086:340c | 1028:0235 | Intel      | 5520/X58 I/O Hub PCI Expr... | 1     | pcib       | E2AB2682CB |
| 8086:340d | 1028:0235 | Intel      | 5520/X58 I/O Hub PCI Expr... | 1     | pcib       | E2AB2682CB |
| 8086:340e | 1028:0235 | Intel      | 5520/5500/X58 I/O Hub PCI... | 1     | pcib       | E2AB2682CB |
| 8086:3500 | 8086:3476 | Intel      | 6311ESB/6321ESB PCI Expre... | 1     | pcib       | 9A893E2CC9 |
| 8086:350c | 8086:3476 | Intel      | 6311ESB/6321ESB PCI Expre... | 1     | pcib       | 9A893E2CC9 |
| 8086:3510 | 8086:3476 | Intel      | 6311ESB/6321ESB PCI Expre... | 1     | pcib       | 9A893E2CC9 |
| 8086:3518 | 8086:3476 | Intel      | 6311ESB/6321ESB PCI Expre... | 1     | pcib       | 9A893E2CC9 |
| 8086:3b14 | 8086:34ec | Intel      | 3420 Chipset LPC Interfac... | 1     | isab       | 6B7FBA08DD |
| 8086:3b42 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | pcib       | 6B7FBA08DD |
| 8086:3b4a | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | pcib       | 6B7FBA08DD |
| 8086:3b4e | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | pcib       | 6B7FBA08DD |
| 8086:3b50 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | pcib       | 6B7FBA08DD |
| 8086:5918 | 1028:06aa | Intel      | Xeon E3-1200 v6/7th Gen C... | 1     | hostb      | E59AEBEE71 |
| 8086:a118 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | E59AEBEE71 |
| 8086:a11a | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | E59AEBEE71 |
| 8086:a149 | 1028:06aa | Intel      | C236 Chipset LPC/eSPI Con... | 1     | isab       | E59AEBEE71 |
| 8086:d130 |           | Intel      | Core Processor DMI           | 1     | hostb      | 6B7FBA08DD |
| 8086:d138 |           | Intel      | Core Processor PCI Expres... | 1     | pcib       | 6B7FBA08DD |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a13a | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:a13b | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:1c3a | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     |            | 6CF7F9EA4B |
| 8086:1c3b | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     |            | 6CF7F9EA4B |
| 8086:1d3a | 15d9:0703 | Intel      | C600/X79 series chipset M... | 1     |            | 1F4D1E4607 |
| 8086:1d3b | 15d9:0703 | Intel      | C600/X79 series chipset M... | 1     |            | 1F4D1E4607 |
| 8086:a13a | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |
| 8086:a13b | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:2000 | 15d9:0884 | ASPEED ... | ASPEED Graphics Family       | 2     | vgapci     | 18EA6EC987 |
| 1002:515e | 103c:31fb | AMD        | ES1000                       | 1     | vgapci     | 4EBC960E9C |
| 1002:515e | 8086:3476 | AMD        | ES1000                       | 1     | vgapci     | 9A893E2CC9 |
| 102b:0522 | 1734:11cc | Matrox ... | MGA G200e [Pilot] ServerE... | 1     | vgapci     | 6CF7F9EA4B |
| 102b:0522 | 8086:0101 | Matrox ... | MGA G200e [Pilot] ServerE... | 1     | vgapci     | 6B7FBA08DD |
| 102b:0532 | 1028:0235 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | E2AB2682CB |
| 102b:0532 | 15d9:0703 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 1F4D1E4607 |
| 102b:0534 | 1028:06aa | Matrox ... | G200eR2                      | 1     | vgapci     | E59AEBEE71 |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 1     | vgapci     | 360E63CC66 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a121 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 10de:0361 | 108e:6676 | Nvidia     | MCP55 LPC Bridge             | 1     |            | 970467EFEF |
| 10de:0369 | 108e:6676 | Nvidia     | MCP55 Memory Controller      | 1     |            | 970467EFEF |
| 10de:036a | 108e:6676 | Nvidia     | MCP55 Memory Controller      | 1     |            | 970467EFEF |
| 8086:a121 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 3     | igb        | 18EA6EC987 |
| 14e4:163b | 1028:02f1 | Broadco... | NetXtreme II BCM5716 Giga... | 2     | bce        | D224B1F8E0 |
| 14e4:1639 | 1028:0235 | Broadco... | NetXtreme II BCM5709 Giga... | 1     | bce        | E2AB2682CB |
| 14e4:1639 | 14e4:1917 | Broadco... | NetXtreme II BCM5709 Giga... | 1     | bce        | 245D470945 |
| 14e4:163b | 1028:02a4 | Broadco... | NetXtreme II BCM5716 Giga... | 1     | bce        | 245D470945 |
| 14e4:164c | 103c:7037 | Broadco... | NetXtreme II BCM5708 Giga... | 1     | bce        | 4EBC960E9C |
| 14e4:164c | 103c:7038 | Broadco... | NetXtreme II BCM5708 Giga... | 1     | bce        | 4EBC960E9C |
| 14e4:165f | 1028:06a7 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | bge        | E59AEBEE71 |
| 14e4:165f | 103c:22e8 | Broadco... | NetXtreme BCM5720 2-port ... | 1     | bge        | BE41B5CD29 |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 1     | ath        | F6CF8F7870 |
| 8086:105e | 8086:135e | Intel      | 82571EB/82571GB Gigabit E... | 1     | em         | 61271EAE5D |
| 8086:1096 | 8086:3476 | Intel      | 80003ES2LAN Gigabit Ether... | 1     | em         | 9A893E2CC9 |
| 8086:10b9 | 8086:1083 | Intel      | 82572EI Gigabit Ethernet ... | 1     | em         | D224B1F8E0 |
| 8086:10d3 |           | Intel      | 82574L Gigabit Network Co... | 1     | em         | 1F4D1E4607 |
| 8086:10d3 | 1734:1192 | Intel      | 82574L Gigabit Network Co... | 1     | em         | 6CF7F9EA4B |
| 8086:10d3 | 8086:34ec | Intel      | 82574L Gigabit Network Co... | 1     | em         | 6B7FBA08DD |
| 8086:10ef | 8086:34ec | Intel      | 82578DM Gigabit Network C... | 1     | em         | 6B7FBA08DD |
| 8086:1502 | 1734:11b7 | Intel      | 82579LM Gigabit Network C... | 1     | em         | 6CF7F9EA4B |
| 8086:1521 | 8086:0002 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 6B7FBA08DD |
| 8086:1521 | 8086:00a2 | Intel      | I350 Gigabit Network Conn... | 1     | igb        | 6CF7F9EA4B |
| 8086:1533 | 8086:35ba | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 2793B07B38 |
| 8086:15b7 | 15d9:15b7 | Intel      | Ethernet Connection (2) I... | 1     | em         | F6CF8F7870 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 1     |            | 4EBC960E9C |

### Signal processing (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a131 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:0e30 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e34 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e36 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:1d24 | 15d9:0703 | Intel      | C600/X79 series chipset T... | 1     |            | 1F4D1E4607 |
| 8086:a131 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a123 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     |            | 18EA6EC987 |
| 8086:1c22 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     |            | 6CF7F9EA4B |
| 8086:1d22 | 15d9:0703 | Intel      | C600/X79 series chipset S... | 1     |            | 1F4D1E4607 |
| 8086:269b | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | ichsmb     | 9A893E2CC9 |
| 8086:3b30 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ichsmb     | 6B7FBA08DD |
| 8086:a123 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     |            | E59AEBEE71 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:0fb9 | 1462:8c96 | Nvidia     | GP107GL High Definition A... | 1     | hdac       | 360E63CC66 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a102 | 15d9:0884 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | 18EA6EC987 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | BE41B5CD29 |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe SATA 6Gb/s ... | 1     | ahci       | BE41B5CD29 |
| 8086:1c02 | 1734:11b8 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 6CF7F9EA4B |
| 8086:1d02 | 15d9:0703 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | 1F4D1E4607 |
| 8086:2681 | 8086:3476 | Intel      | 631xESB/632xESB SATA AHCI... | 1     | ahci       | 9A893E2CC9 |
| 8086:3b22 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 6B7FBA08DD |
| 8086:8c02 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 2793B07B38 |
| 8086:a102 | 1028:06aa | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | E59AEBEE71 |
| 8086:a102 | 15d9:089f | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | F6CF8F7870 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10de:036e | 108e:6676 | Nvidia     | MCP55 IDE                    | 1     | atapci     | 970467EFEF |
| 10de:037f | 108e:6676 | Nvidia     | MCP55 SATA Controller        | 1     | atapci     | 970467EFEF |
| 1166:0214 | 103c:320b | Broadcom   | BCM5785 [HT1000] IDE         | 1     | atapci     | 4EBC960E9C |
| 8086:269e | 8086:3476 | Intel      | 631xESB/632xESB IDE Contr... | 1     | atapci     | 9A893E2CC9 |
| 8086:2921 | 1028:0235 | Intel      | 82801IB (ICH9) 2 port SAT... | 1     | atapci     | E2AB2682CB |
| 8086:3b20 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | atapci     | AB1D30ED74 |
| 8086:3b26 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | atapci     | AB1D30ED74 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 1     | nvme       | 970467EFEF |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 1     | nvme       | 18EA6EC987 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 1     | nvme       | 360E63CC66 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3230 | 103c:3235 | Hewlett... | Smart Array Controller       | 1     | ciss       | 4EBC960E9C |
| 17d3:1680 | 17d3:1212 | Areca T... | ARC-1680 series PCIe to S... | 1     | arcmsr     | 6B7FBA08DD |
| 8086:3b25 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 245D470945 |
| 9005:028b | 9005:0301 | Adaptec    | Series 6 - 6G SAS/PCIe 2     | 1     | aacraid    | 1F4D1E4607 |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0072 | 1028:1f1c | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 61271EAE5D |
| 1000:0072 | 1028:1f1d | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | D224B1F8E0 |
| 1000:0072 | 1028:1f1e | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | E2AB2682CB |
| 8086:1d6b | 15d9:0703 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1F4D1E4607 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0030 | 1000:10b0 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mpt        | 970467EFEF |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | D224B1F8E0 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | D224B1F8E0 |
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 3     |            | D224B1F8E0 |
| 0e11:b203 | 103c:3305 | Compaq ... | Integrated Lights Out Con... | 1     |            | 4EBC960E9C |
| 0e11:b204 | 103c:3305 | Compaq ... | Integrated Lights Out  Pr... | 1     |            | 4EBC960E9C |
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
| 8086:0eab | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eac | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ead | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eb0 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eb1 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eb2 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eb3 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eb4 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eb5 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eb6 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eb7 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ec0 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ec1 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ec2 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ec3 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ec8 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ec9 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0eca | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ee0 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ee1 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ee2 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0ee3 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:1a38 | 8086:3476 | Intel      | 5000 Series Chipset DMA E... | 1     |            | 9A893E2CC9 |
| 8086:d150 | 0086:00ec | Intel      | Core Processor QPI Link      | 1     |            | 6B7FBA08DD |
| 8086:d151 | 0086:00ec | Intel      | Core Processor QPI Routin... | 1     |            | 6B7FBA08DD |
| 8086:d155 | 0086:00ec | Intel      | Core Processor System Man... | 1     |            | 6B7FBA08DD |
| 8086:d156 | 0086:00ec | Intel      | Core Processor Semaphore ... | 1     |            | 6B7FBA08DD |
| 8086:d157 | 0086:00ec | Intel      | Core Processor System Con... | 1     |            | 6B7FBA08DD |
| 8086:d158 | 0086:00ec | Intel      | Core Processor Miscellane... | 1     |            | 6B7FBA08DD |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:a12f | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 2     | xhci       | 18EA6EC987 |
| 103c:3300 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 1     | uhci       | 4EBC960E9C |
| 1106:3104 | 1106:3104 | VIA Tec... | USB 2.0                      | 1     | ehci       | 970467EFEF |
| 1166:0223 | 103c:320c | Broadcom   | BCM5785 [HT1000] USB         | 1     | ohci       | 4EBC960E9C |
| 1166:0223 | 103c:320d | Broadcom   | BCM5785 [HT1000] USB         | 1     | ehci       | 4EBC960E9C |
| 8086:1c26 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 6CF7F9EA4B |
| 8086:1c2d | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | 6CF7F9EA4B |
| 8086:1d26 | 15d9:0703 | Intel      | C600/X79 series chipset U... | 1     | ehci       | 1F4D1E4607 |
| 8086:1d2d | 15d9:0703 | Intel      | C600/X79 series chipset U... | 1     | ehci       | 1F4D1E4607 |
| 8086:2688 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | uhci       | 9A893E2CC9 |
| 8086:2689 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | uhci       | 9A893E2CC9 |
| 8086:268a | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | uhci       | 9A893E2CC9 |
| 8086:268b | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | uhci       | 9A893E2CC9 |
| 8086:268c | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | ehci       | 9A893E2CC9 |
| 8086:2934 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 1     | uhci       | E2AB2682CB |
| 8086:2935 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 1     | uhci       | E2AB2682CB |
| 8086:2937 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 1     | uhci       | E2AB2682CB |
| 8086:2938 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 1     | uhci       | E2AB2682CB |
| 8086:293a | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 1     | ehci       | E2AB2682CB |
| 8086:293c | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 1     | ehci       | E2AB2682CB |
| 8086:3b34 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ehci       | 6B7FBA08DD |
| 8086:3b3c | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ehci       | 6B7FBA08DD |
| 8086:a12f | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 1     | xhci       | E59AEBEE71 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
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
| 1002:9874 | 1002:1871 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 1     | vgapci     | BE41B5CD29 |
| 1022:1100 |           | AMD        | K8 [Athlon64/Opteron] Hyp... | 1     | hostb      | 970467EFEF |
| 1022:1101 |           | AMD        | K8 [Athlon64/Opteron] Add... | 1     | hostb      | 970467EFEF |
| 1022:1102 |           | AMD        | K8 [Athlon64/Opteron] DRA... | 1     | hostb      | 970467EFEF |
| 1022:1103 |           | AMD        | K8 [Athlon64/Opteron] Mis... | 1     | hostb      | 970467EFEF |
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
| 1022:7908 | 1022:7908 | AMD        | FCH USB EHCI Controller      | 1     | ehci       | BE41B5CD29 |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 1     | intsmb     | BE41B5CD29 |
| 1022:790e | 1022:790e | AMD        | FCH LPC Bridge               | 1     | isab       | BE41B5CD29 |
| 1022:7914 | 1022:7914 | AMD        | FCH USB XHCI Controller      | 1     | xhci       | BE41B5CD29 |
| 102b:0522 | 8086:0103 | Matrox ... | MGA G200e [Pilot] ServerE... | 1     | vgapci     | 2793B07B38 |
| 102b:0532 | 1028:02a4 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 245D470945 |
| 104c:8023 | 108e:6676 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     |            | 970467EFEF |
| 10b5:8114 |           | PLX Tec... | PEX 8114 PCI Express-to-P... | 1     | pcib       | 970467EFEF |
| 10de:0165 | 10de:0334 | Nvidia     | NV44 [Quadro NVS 285]        | 1     | vgapci     | 970467EFEF |
| 10de:0364 | 108e:6676 | Nvidia     | MCP55 LPC Bridge             | 1     | isab       | 970467EFEF |
| 10de:0368 | 108e:6676 | Nvidia     | MCP55 SMBus Controller       | 1     |            | 970467EFEF |
| 10de:036c | 108e:6676 | Nvidia     | MCP55 USB Controller         | 1     | ohci       | 970467EFEF |
| 10de:036d | 108e:6676 | Nvidia     | MCP55 USB Controller         | 1     | ehci       | 970467EFEF |
| 10de:0371 | 108e:6676 | Nvidia     | MCP55 High Definition Audio  | 1     | hdac       | 970467EFEF |
| 10de:0373 | 108e:6676 | Nvidia     | MCP55 Ethernet               | 1     | nfe        | 970467EFEF |
| 10de:0374 |           | Nvidia     | MCP55 PCI Express bridge     | 1     | pcib       | 970467EFEF |
| 10de:0375 |           | Nvidia     | MCP55 PCI Express bridge     | 1     | pcib       | 970467EFEF |
| 10de:0376 |           | Nvidia     | MCP55 PCI Express bridge     | 1     | pcib       | 970467EFEF |
| 10de:0377 |           | Nvidia     | MCP55 PCI Express bridge     | 1     | pcib       | 970467EFEF |
| 10de:0378 |           | Nvidia     | MCP55 PCI Express bridge     | 1     | pcib       | 970467EFEF |
| 10e3:8113 | 15d9:089f | Tundra ... |                              | 1     | pcib       | F6CF8F7870 |
| 1106:3038 | 1106:3038 | VIA Tec... | VT82xx/62xx UHCI USB 1.1 ... | 1     | uhci       | 970467EFEF |
| 1b21:1242 | 15d9:089f | ASMedia... | ASM1142 USB 3.1 Host Cont... | 1     | xhci       | F6CF8F7870 |
| 8086:0c08 | 8086:2010 | Intel      | Xeon E3-1200 v3 Processor... | 1     | hostb      | 2793B07B38 |
| 8086:3b14 | 1028:02a4 | Intel      | 3420 Chipset LPC Interfac... | 1     | isab       | 245D470945 |
| 8086:3b34 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | ehci       | 245D470945 |
| 8086:3b3c | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | ehci       | 245D470945 |
| 8086:3b42 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | pcib       | 245D470945 |
| 8086:3b46 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | pcib       | 245D470945 |
| 8086:3b48 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | pcib       | 245D470945 |
| 8086:3b4a | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | pcib       | 245D470945 |
| 8086:5918 | 15d9:0884 | Intel      | Xeon E3-1200 v6/7th Gen C... | 1     | hostb      | 18EA6EC987 |
| 8086:5918 | 15d9:089f | Intel      | Xeon E3-1200 v6/7th Gen C... | 1     | hostb      | F6CF8F7870 |
| 8086:591d | 15d9:0884 | Intel      | HD Graphics P630             | 1     | vgapci     | 18EA6EC987 |
| 8086:591d | 15d9:089f | Intel      | HD Graphics P630             | 1     | ppt        | F6CF8F7870 |
| 8086:8c10 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | pcib       | 2793B07B38 |
| 8086:8c12 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | pcib       | 2793B07B38 |
| 8086:8c14 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | pcib       | 2793B07B38 |
| 8086:8c22 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 2793B07B38 |
| 8086:8c24 |           | Intel      | 8 Series Chipset Family T... | 1     |            | 2793B07B38 |
| 8086:8c26 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | ehci       | 2793B07B38 |
| 8086:8c2d | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | ehci       | 2793B07B38 |
| 8086:8c31 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | xhci       | 2793B07B38 |
| 8086:8c54 | 8086:35b9 | Intel      | C224 Series Chipset Famil... | 1     | isab       | 2793B07B38 |
| 8086:a110 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | F6CF8F7870 |
| 8086:a115 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | F6CF8F7870 |
| 8086:a116 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | F6CF8F7870 |
| 8086:a117 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | F6CF8F7870 |
| 8086:a118 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | pcib       | F6CF8F7870 |
| 8086:a121 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a123 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a12f | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | ppt        | F6CF8F7870 |
| 8086:a131 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 18EA6EC987 |
| 8086:a13a | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a13d | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a149 | 15d9:089f | Intel      | C236 Chipset LPC/eSPI Con... | 1     | isab       | F6CF8F7870 |
| 8086:a160 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a161 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a170 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | hdac       | F6CF8F7870 |
| 8086:d130 | 1028:02a4 | Intel      | Core Processor DMI           | 1     | hostb      | 245D470945 |
| 8086:d150 |           | Intel      | Core Processor QPI Link      | 1     |            | 245D470945 |
| 8086:d151 |           | Intel      | Core Processor QPI Routin... | 1     |            | 245D470945 |
| 8086:d155 |           | Intel      | Core Processor System Man... | 1     |            | 245D470945 |

