Most popular PCI devices in Mini Pcs
====================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Mini Pcs ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Network ](#network-pci)
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Signal processing ](#signal-processing-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
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
| 8086:31d8 | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 2     | pcib       | E44A7E90E0 |
| 8086:31da | 8086:2072 | Intel      | Gemini Lake PCI Express R... | 2     | pcib       | E44A7E90E0 |
| 8086:31e8 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     | isab       | E44A7E90E0 |
| 8086:31f0 | 8086:2072 | Intel      | Gemini Lake Host Bridge      | 2     | hostb      | E44A7E90E0 |
| 104c:823e |           | Texas I... | XIO2213A/B/XIO2221 PCI Ex... | 1     | pcib       | DC34D6FD02 |
| 8086:0101 | 106b:00f0 | Intel      | Xeon E3-1200/2nd Generati... | 1     | pcib       | DC34D6FD02 |
| 8086:0104 | 106b:00f0 | Intel      | 2nd Generation Core Proce... | 1     | hostb      | DC34D6FD02 |
| 8086:0105 | 106b:00f0 | Intel      | Xeon E3-1200/2nd Generati... | 1     | pcib       | DC34D6FD02 |
| 8086:1904 | 8086:2063 | Intel      | Xeon E3-1200 v5/E3-1500 v... | 1     | hostb      | 6B854263E7 |
| 8086:1c10 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | DC34D6FD02 |
| 8086:1c12 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | DC34D6FD02 |
| 8086:1c14 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | pcib       | DC34D6FD02 |
| 8086:1c49 | 8086:7270 | Intel      | HM65 Express Chipset LPC ... | 1     | isab       | DC34D6FD02 |
| 8086:5ad8 |           | Intel      | Celeron N3350/Pentium N42... | 1     | pcib       | 00C1939EAC |
| 8086:5ad9 |           | Intel      | Celeron N3350/Pentium N42... | 1     | pcib       | 00C1939EAC |
| 8086:5ada |           | Intel      | Celeron N3350/Pentium N42... | 1     | pcib       | 00C1939EAC |
| 8086:5adb |           | Intel      | Celeron N3350/Pentium N42... | 1     | pcib       | 00C1939EAC |
| 8086:9d14 | 8086:2063 | Intel      | Sunrise Point-LP PCI Expr... | 1     | pcib       | 6B854263E7 |
| 8086:9d48 | 8086:2063 | Intel      | Sunrise Point-LP LPC Cont... | 1     | isab       | 6B854263E7 |

### Card reader (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:5229 | 8086:2072 | Realtek... | RTS5229 PCI Express Card ... | 2     |            | E44A7E90E0 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:319a | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | E44A7E90E0 |
| 8086:1c3a | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     |            | DC34D6FD02 |
| 8086:9d3a | 8086:2063 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 6B854263E7 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:823f |           | Texas I... | XIO2213A/B/XIO2221 IEEE-1... | 1     |            | DC34D6FD02 |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3185 | 8086:2072 | Intel      | UHD Graphics 605             | 2     | vgapci     | E44A7E90E0 |
| 1002:6741 | 106b:00e8 | AMD        | Whistler [Radeon HD 6630M... | 1     | vgapci     | DC34D6FD02 |
| 8086:0126 | 106b:00f0 | Intel      | 2nd Generation Core Proce... | 1     | vgapci     | DC34D6FD02 |
| 8086:1926 | 8086:2063 | Intel      | Iris Graphics 540            | 1     | vgapci     | 6B854263E7 |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d21 | 8086:2063 | Intel      | Sunrise Point-LP PMC         | 1     |            | 6B854263E7 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 8086:2072 | Realtek... | RTL8111/8168/8411 PCI Exp... | 2     | re         | E44A7E90E0 |
| 8086:31dc | 8086:02a4 | Intel      | Wireless-AC 1550i Wireles... | 2     |            | E44A7E90E0 |
| 10ec:8168 | 10ec:0123 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 215CEA62E1 |
| 10ec:8168 | 8086:2060 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | A24CFB5DF9 |
| 14e4:16b4 | 14e4:16b4 | Broadco... | NetXtreme BCM57765 Gigabi... | 1     | bge        | DC34D6FD02 |
| 14e4:4331 | 14e4:4331 | Broadco... | BCM4331 802.11a/b/g/n        | 1     | bwn_pci    | DC34D6FD02 |
| 8086:1539 |           | Intel      | I211 Gigabit Network Conn... | 1     | igb        | 00C1939EAC |
| 8086:156f | 8086:2070 | Intel      | Ethernet Connection I219-LM  | 1     | em         | 06BEB9AD2C |
| 8086:1570 | 8086:2063 | Intel      | Ethernet Connection I219-V   | 1     | em         | 6B854263E7 |
| 8086:24f3 | 8086:9010 | Intel      | Wireless 8260                | 1     | iwm        | 6B854263E7 |
| 8086:3165 | 8086:4010 | Intel      | Wireless 3165                | 1     |            | 215CEA62E1 |

### Sd host controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31cc | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     | sdhci_pci  | E44A7E90E0 |
| 14e4:16bc |           | Broadco... | BCM57765/57785 SDXC/MMC C... | 1     | sdhci_pci  | DC34D6FD02 |
| 8086:9d2d | 8086:2063 | Intel      | Sunrise Point-LP Secure D... | 1     | sdhci_pci  | 6B854263E7 |

### Signal processing (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:9d27 | 8086:2063 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 6B854263E7 |
| 8086:9d31 | 8086:2063 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 6B854263E7 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31d4 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     |            | E44A7E90E0 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     |            | DC34D6FD02 |
| 8086:9d23 | 8086:2063 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 6B854263E7 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3198 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 2     | hdac       | E44A7E90E0 |
| 1002:aa90 | 0000:aa90 | AMD        | Turks HDMI Audio [Radeon ... | 1     | hdac       | DC34D6FD02 |
| 8086:1c20 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | hdac       | DC34D6FD02 |
| 8086:2284 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | hdac       | 215CEA62E1 |
| 8086:2284 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     | hdac       | A24CFB5DF9 |
| 8086:9d70 | 8086:2063 | Intel      | Sunrise Point-LP HD Audio    | 1     | hdac       | 6B854263E7 |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31e3 | 8086:2072 | Intel      |                              | 2     | ahci       | E44A7E90E0 |
| 8086:1c03 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | DC34D6FD02 |
| 8086:22a3 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | 215CEA62E1 |
| 8086:22a3 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     | ahci       | A24CFB5DF9 |
| 8086:5ae3 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | ahci       | 00C1939EAC |
| 8086:9d03 | 8086:2063 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 6B854263E7 |
| 8086:9d03 | 8086:2070 | Intel      | Sunrise Point-LP SATA Con... | 1     | ahci       | 06BEB9AD2C |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3190 | 8086:2072 | Intel      | Celeron/Pentium Silver Pr... | 1     |            | D910596224 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:31a8 | 8086:2072 | Intel      |                              | 2     | xhci       | E44A7E90E0 |
| 8086:1c26 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | DC34D6FD02 |
| 8086:1c27 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | uhci       | DC34D6FD02 |
| 8086:1c2c | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | uhci       | DC34D6FD02 |
| 8086:1c2d | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | ehci       | DC34D6FD02 |
| 8086:22b5 |           | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci       | A24CFB5DF9 |
| 8086:9d2f | 8086:2063 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci       | 6B854263E7 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1911 | 8086:2070 | Intel      | Xeon E3-1200 v5/v6 / E3-1... | 1     |            | 06BEB9AD2C |
| 8086:2280 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | hostb      | 215CEA62E1 |
| 8086:2280 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     | hostb      | A24CFB5DF9 |
| 8086:2292 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 215CEA62E1 |
| 8086:2292 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | A24CFB5DF9 |
| 8086:2294 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | sdhci_pci  | 215CEA62E1 |
| 8086:2298 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | 215CEA62E1 |
| 8086:2298 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     |            | A24CFB5DF9 |
| 8086:229c | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | isab       | 215CEA62E1 |
| 8086:229c | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     | isab       | A24CFB5DF9 |
| 8086:22b1 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | vgapci     | 215CEA62E1 |
| 8086:22b1 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     | vgapci     | A24CFB5DF9 |
| 8086:22b5 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | xhci       | 215CEA62E1 |
| 8086:22c8 | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | pcib       | 215CEA62E1 |
| 8086:22c8 | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     | pcib       | A24CFB5DF9 |
| 8086:22ca | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | pcib       | 215CEA62E1 |
| 8086:22cc | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | pcib       | 215CEA62E1 |
| 8086:22cc | 8086:2060 | Intel      | Atom/Celeron/Pentium Proc... | 1     | pcib       | A24CFB5DF9 |
| 8086:22ce | 19da:b301 | Intel      | Atom/Celeron/Pentium Proc... | 1     | pcib       | 215CEA62E1 |
| 8086:5904 | 8086:2070 | Intel      | Xeon E3-1200 v6/7th Gen C... | 1     | hostb      | 06BEB9AD2C |
| 8086:5916 | 8086:2070 | Intel      | HD Graphics 620              | 1     | vgapci     | 06BEB9AD2C |
| 8086:5a85 | 8086:2212 | Intel      | HD Graphics 500              | 1     | vgapci     | 00C1939EAC |
| 8086:5a98 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | hdac       | 00C1939EAC |
| 8086:5a9a | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5aa8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | xhci       | 00C1939EAC |
| 8086:5aac | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5aae | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ab0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ab2 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ab4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ab6 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ab8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5aba | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5abc | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5abe | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ac0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ac8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ad4 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5ae8 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | isab       | 00C1939EAC |
| 8086:5aee | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     |            | 00C1939EAC |
| 8086:5af0 | 8086:7270 | Intel      | Celeron N3350/Pentium N42... | 1     | hostb      | 00C1939EAC |
| 8086:9d21 | 8086:2070 | Intel      | Sunrise Point-LP PMC         | 1     |            | 06BEB9AD2C |
| 8086:9d23 | 8086:2070 | Intel      | Sunrise Point-LP SMBus       | 1     |            | 06BEB9AD2C |
| 8086:9d2f | 8086:2070 | Intel      | Sunrise Point-LP USB 3.0 ... | 1     | xhci       | 06BEB9AD2C |
| 8086:9d31 | 8086:2070 | Intel      | Sunrise Point-LP Thermal ... | 1     |            | 06BEB9AD2C |
| 8086:9d3a | 8086:2070 | Intel      | Sunrise Point-LP CSME HEC... | 1     |            | 06BEB9AD2C |
| 8086:9d4e | 8086:2070 | Intel      | Sunrise Point LPC Control... | 1     | isab       | 06BEB9AD2C |
| 8086:9d60 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 06BEB9AD2C |
| 8086:9d61 | 8086:2070 | Intel      | Sunrise Point-LP Serial I... | 1     |            | 06BEB9AD2C |
| 8086:9d71 | 8086:2070 | Intel      | Sunrise Point-LP HD Audio    | 1     | hdac       | 06BEB9AD2C |

