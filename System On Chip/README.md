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
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:2711 |           | Broadcom         | BCM2711 PCIe Bridge                  | 17    | pcib       | [840C7F2142](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E2EEB2EBEC28/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/840C7F2142>) |
| 1d87:0100 |           | Fuzhou Rockch... | RK3399 PCI Express Root Port         | 2     | pcib       | [D96ADE87E5](<System On Chip/Others/Others/Others/6D58F26372BC/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/D96ADE87E5>) |
| 1022:1a00 | 1022:1a00 | AMD              |                                      | 1     | hostb      | [608812BDE1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/95B932C60F7C/HARDENEDBSD-14.0-CURRENT-HBSD/14.0-CURRENT-HBSD/ARM64/608812BDE1>) |
| 1022:1a01 |           | AMD              |                                      | 1     | hostb      | [608812BDE1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/95B932C60F7C/HARDENEDBSD-14.0-CURRENT-HBSD/14.0-CURRENT-HBSD/ARM64/608812BDE1>) |
| 1022:1a02 | 1022:1234 | AMD              |                                      | 1     | pcib       | [608812BDE1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/95B932C60F7C/HARDENEDBSD-14.0-CURRENT-HBSD/14.0-CURRENT-HBSD/ARM64/608812BDE1>) |
| 11ab:0110 |           | Marvell Techn... | 88F60x0/88F70x0/88F80x0/CN913x AR... | 1     | pcib       | [C7564F242A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F1C9C341F427/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/C7564F242A>) |
| 1957:8d80 |           | Freescale Sem... |                                      | 1     | pcib       | [9C6094360F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/ED12AFB3B398/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/9C6094360F>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 1     | pcib       | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |
| 1d0f:0200 |           | Amazon.com       |                                      | 1     | hostb      | [7A05270DDB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/26A7313AD2FD/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/7A05270DDB>) |
| 1def:e005 |           | Ampere Computing | eMAG PCI Express Root Port 0         | 1     | pcib       | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |
| 1def:e007 |           | Ampere Computing | eMAG PCI Express Root Port 2         | 1     | pcib       | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |
| 1def:e008 |           | Ampere Computing | eMAG PCI Express Root Port 3         | 1     | pcib       | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |
| 1def:e009 |           | Ampere Computing | eMAG PCI Express Root Port 4         | 1     | pcib       | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |
| 1def:e00a |           | Ampere Computing | eMAG PCI Express Root Port 5         | 1     | pcib       | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |
| 1def:e00b |           | Ampere Computing | eMAG PCI Express Root Port 6         | 1     | pcib       | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |
| 1def:e00c |           | Ampere Computing | eMAG PCI Express Root Port 7         | 1     | pcib       | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1d0f:8250 |           | Amazon.com       |                                      | 1     | uart       | [7A05270DDB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/26A7313AD2FD/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/7A05270DDB>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 1     | vgapci     | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11ab:4381 | 11ab:4381 | Marvell Techn... | Yukon Optima 88E8059 [PCIe Gigabi... | 1     | mskc       | [608812BDE1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/95B932C60F7C/HARDENEDBSD-14.0-CURRENT-HBSD/14.0-CURRENT-HBSD/ARM64/608812BDE1>) |
| 19a2:0710 | 10df:e729 | Emulex           | OneConnect 10Gb NIC (be3)            | 1     | oce        | [4E4F164625](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9C45D78BD256/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/4E4F164625>) |
| 1d0f:ec20 | 1d0f:ec20 | Amazon.com       | Elastic Network Adapter (ENA)        | 1     | ena        | [7A05270DDB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/26A7313AD2FD/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/7A05270DDB>) |
| 8086:1521 | 1734:11cf | Intel            | I350 Gigabit Network Connection      | 1     | igb        | [C7564F242A](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/F1C9C341F427/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/C7564F242A>) |
| 8086:1533 | 8086:0001 | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [9C6094360F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/ED12AFB3B398/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/9C6094360F>) |
| 15b3:1015 | 15b3:0057 | Mellanox Tech... | MT27710 Family [ConnectX-4 Lx]       | 1     | mlx5_core  | [E3F20F8770](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/DFD7AA82A0DA/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/E3F20F8770>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 2     | nvme       | [B5C6AA26DE](<System On Chip/Firefly/ROC-RK3566/ROC-RK3566-PC/FAAF4C74704D/HELLOSYSTEM-13.0-STABLE/13.0-STABLE/ARM64/B5C6AA26DE>) |
| 15b7:5009 | 15b7:5009 | Sandisk          | WD Blue SN550 NVMe SSD               | 1     | nvme       | [E1B15635FF](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/D264F258A580/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/E1B15635FF>) |
| 1d0f:8061 |           | Amazon.com       | NVMe EBS Controller                  | 1     | nvme       | [7A05270DDB](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/26A7313AD2FD/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/7A05270DDB>) |
| 8086:2522 | 8086:3810 | Intel            | NVMe Optane Memory Series            | 1     | nvme       | [4E4F164625](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/9C45D78BD256/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/4E4F164625>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 1     | nvme       | [9C6094360F](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/ED12AFB3B398/FREEBSD-13.0-CURRENT/13.0-CURRENT/ARM64/9C6094360F>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 17    | bcm_xhci   | [840C7F2142](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/E2EEB2EBEC28/FREEBSD-14.0-CURRENT/14.0-CURRENT/ARM64/840C7F2142>) |
| 1b73:1009 |           | Fresco Logic     | FL1009 USB 3.0 Host Controller       | 1     | xhci       | [608812BDE1](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/95B932C60F7C/HARDENEDBSD-14.0-CURRENT-HBSD/14.0-CURRENT-HBSD/ARM64/608812BDE1>) |

