Most popular PCI devices in System On Chips
===========================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in System On Chips ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Network ](#network-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  — number of computers with this device installed,
Driver — driver in use for this device,
Probe  — latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 14e4:2711 |           | Broadcom   | BCM2711 PCIe Bridge          | 7     | pcib       | 951C3E534C |
| 1d87:0100 |           | Fuzhou ... | RK3399 PCI Express Root Port | 2     | pcib       | D96ADE87E5 |
| 1022:1a00 | 1022:1a00 | AMD        |                              | 1     | hostb      | 608812BDE1 |
| 1022:1a01 |           | AMD        |                              | 1     | hostb      | 608812BDE1 |
| 1022:1a02 | 1022:1234 | AMD        |                              | 1     | pcib       | 608812BDE1 |
| 11ab:0110 |           | Marvell... |                              | 1     | pcib       | C7564F242A |
| 1957:8d80 |           | Freesca... |                              | 1     | pcib       | 9C6094360F |
| 1a03:1150 | 1a03:1150 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 1     | pcib       | E3F20F8770 |
| 1d0f:0200 |           | Amazon.com |                              | 1     | hostb      | 7A05270DDB |
| 1def:e005 |           | Ampere ... | eMAG PCI Express Root Port 0 | 1     | pcib       | E3F20F8770 |
| 1def:e007 |           | Ampere ... | eMAG PCI Express Root Port 2 | 1     | pcib       | E3F20F8770 |
| 1def:e008 |           | Ampere ... | eMAG PCI Express Root Port 3 | 1     | pcib       | E3F20F8770 |
| 1def:e009 |           | Ampere ... | eMAG PCI Express Root Port 4 | 1     | pcib       | E3F20F8770 |
| 1def:e00a |           | Ampere ... | eMAG PCI Express Root Port 5 | 1     | pcib       | E3F20F8770 |
| 1def:e00b |           | Ampere ... | eMAG PCI Express Root Port 6 | 1     | pcib       | E3F20F8770 |
| 1def:e00c |           | Ampere ... | eMAG PCI Express Root Port 7 | 1     | pcib       | E3F20F8770 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1d0f:8250 |           | Amazon.com |                              | 1     | uart       | 7A05270DDB |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | E3F20F8770 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 11ab:4381 | 11ab:4381 | Marvell... | Yukon Optima 88E8059 [PCI... | 1     | mskc       | 608812BDE1 |
| 19a2:0710 | 10df:e729 | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | oce        | 4E4F164625 |
| 1d0f:ec20 | 1d0f:ec20 | Amazon.com | Elastic Network Adapter (... | 1     | ena        | 7A05270DDB |
| 8086:1521 | 1734:11cf | Intel      | I350 Gigabit Network Conn... | 1     | igb        | C7564F242A |
| 8086:1533 | 8086:0001 | Intel      | I210 Gigabit Network Conn... | 1     | igb        | E3F20F8770 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | 9C6094360F |
| 15b3:1015 | 15b3:0057 | Mellano... | MT27710 Family [ConnectX-... | 1     | mlx5_core  | E3F20F8770 |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:293e | 1ab8:0400 | Intel      | 82801I (ICH9 Family) HD A... | 1     | hdac       | 807A4B063F |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 1     | nvme       | E1B15635FF |
| 1d0f:8061 |           | Amazon.com | NVMe EBS Controller          | 1     | nvme       | 7A05270DDB |
| 8086:2522 | 8086:3810 | Intel      | NVMe Optane Memory Series    | 1     | nvme       | 4E4F164625 |
| 8086:f1a6 | 8086:390b | Intel      | SSD Pro 7600p/760p/E 6100... | 1     | nvme       | 9C6094360F |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1106:3483 | 1106:3483 | VIA Tec... | VL805/806 xHCI USB 3.0 Co... | 7     | bcm_xhci   | 951C3E534C |
| 1033:0194 | 1ab8:0400 | NEC Com... | uPD720200 USB 3.0 Host Co... | 1     | xhci       | 807A4B063F |
| 1b73:1009 |           | Fresco ... | FL1009 USB 3.0 Host Contr... | 1     | xhci       | 608812BDE1 |
| 8086:265c | 1ab8:0400 | Intel      | 82801FB/FBM/FR/FW/FRW (IC... | 1     | ehci       | 807A4B063F |

