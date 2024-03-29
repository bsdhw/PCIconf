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
   * [ Sd host controller ](#sd-host-controller-pci)
   * [ Serial bus controller ](#serial-bus-controller-pci)
   * [ Signal processing ](#signal-processing-pci)
   * [ Smbus ](#smbus-pci)
   * [ Sound ](#sound-pci)
   * [ Storage/ata ](#storageata-pci)
   * [ Storage/ide ](#storageide-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 39    | pcib       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1f13 | 8086:8086 | Intel            | Atom processor C2000 PCIe Root Po... | 36    | pcib       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1f14 |           | Intel            | Atom processor C2000 RAS             | 36    | hostb      | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:0c01 | 8086:0c01 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 34    | pcib       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:8c10 | 8086:8c10 | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | pcib       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:8c18 | 8086:8c18 | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | pcib       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:8c12 | 8086:8c12 | Intel            | 8 Series/C220 Series Chipset Fami... | 33    | pcib       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:8c14 | 8086:8c14 | Intel            | 8 Series/C220 Series Chipset Fami... | 33    | pcib       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:8c16 | 8086:8c16 | Intel            | 8 Series/C220 Series Chipset Fami... | 33    | pcib       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:8c1a | 8086:8c1a | Intel            | 8 Series/C220 Series Chipset Fami... | 33    | pcib       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:0c00 | 8086:0c00 | Intel            | 4th Gen Core Processor DRAM Contr... | 31    | hostb      | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:1f10 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 29    | pcib       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1f11 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 29    | pcib       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1f12 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 29    | pcib       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1f38 | 8086:7270 | Intel            | Atom processor C2000 PCU             | 29    | isab       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:8c5c | 8086:8c5c | Intel            | H81 Express LPC Controller           | 21    | isab       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:1f0b |           | Intel            | Atom processor C2000 SoC Transact... | 19    | hostb      | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 10b5:8605 | 10b5:8605 | PLX Technology   | PEX 8605 PCI Express 4-port Gen2 ... | 18    | pcib       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:5ad8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | pcib       | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:5ad9 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | pcib       | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:5ada |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | pcib       | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:5adb |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | pcib       | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | isab       | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | hostb      | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:1901 | 8086:2015 | Intel            | 6th-10th Gen Core Processor PCIe ... | 13    | pcib       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:1980 | 8086:1999 | Intel            | Atom Processor C3000 Series Syste... | 13    | hostb      | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19a1 |           | Intel            | Atom Processor C3000 Series Error... | 13    | hostb      | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19a3 |           | Intel            | Atom Processor C3000 Series Integ... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19a4 |           | Intel            | Atom Processor C3000 Series PCI E... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19a5 | 8086:19a5 | Intel            | Atom Processor C3000 Series PCI E... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19a6 | 8086:19a6 | Intel            | Atom Processor C3000 Series PCI E... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19a7 | 8086:19a7 | Intel            | Atom Processor C3000 Series PCI E... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19a8 | 8086:19a8 | Intel            | Atom Processor C3000 Series PCI E... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19a9 | 8086:19a9 | Intel            | Atom Processor C3000 Series PCI E... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19aa | 8086:19aa | Intel            | Atom Processor C3000 Series PCI E... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19ab | 8086:19ab | Intel            | Atom Processor C3000 Series PCI E... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19d1 |           | Intel            | Atom Processor C3000 Series Integ... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19d2 |           | Intel            | Atom Processor C3000 Series Integ... | 13    | pcib       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19dc | 8086:7270 | Intel            | Atom Processor C3000 Series LPC o... | 13    | isab       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:1f0e |           | Intel            | Atom processor C2000 SoC Transact... | 13    | hostb      | [0B353ACC9F](<Firewall/Sophos/SG/SG/1592D21853FE/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/0B353ACC9F>) |
| 8086:8c1c | 8086:8c1c | Intel            | 8 Series/C220 Series Chipset Fami... | 13    | pcib       | [08B02DFC2D](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/08B02DFC2D>) |
| 8086:a114 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | pcib       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:a115 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | pcib       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:a116 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | pcib       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:a117 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | pcib       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:a118 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | pcib       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:2448 | 8086:2448 | Intel            | 82801 Mobile PCI Bridge              | 12    | pcib       | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:244e | 8086:244e | Intel            | 82801 PCI Bridge                     | 12    | pcib       | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:2815 | 8086:2815 | Intel            | 82801HM (ICH8M) LPC Interface Con... | 12    | isab       | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:283f | 8086:283f | Intel            | 82801H (ICH8 Family) PCI Express ... | 12    | pcib       | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 34    | qat        | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:19e2 |           | Intel            | Atom Processor C3000 Series Quick... | 13    | qat        | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:5a9c | 8086:7270 | Intel            |                                      | 16    |            | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:5a9e | 8086:7270 | Intel            |                                      | 16    |            | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:19d3 | 8086:19d3 | Intel            | Atom Processor C3000 Series ME HE... | 13    |            | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    |            | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [E7D2DCA92D](<Firewall/Firewalla/FirewallaGold/FirewallaGold/AEC015EAF4EC/OPNSENSE-22.1.9/13.0-STABLE/AMD64/E7D2DCA92D>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 37    | vgapci     | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:0402 | 8086:0402 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 18    | vgapci     | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 18    | vgapci     | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:0412 | 8086:0412 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 13    | vgapci     | [08B02DFC2D](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/08B02DFC2D>) |
| 8086:a011 | 8086:a011 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 12    | agp        | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:a012 | 8086:a011 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 12    | vgapci     | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:2e32 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 10    | agp        | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:2e33 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 10    | vgapci     | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:1912 |           | Intel            | HD Graphics 530                      | 7     | vgapci     | [53BA75464F](<Firewall/Sophos/SG/SG/341245A9A67B/OPNSENSE-22.1.5/13.0-STABLE/AMD64/53BA75464F>) |
| 8086:041a | 8086:041a | Intel            | Xeon E3-1200 v3 Processor Integra... | 5     | vgapci     | [F21B92F971](<Firewall/Sophos/SG/SG/63F6B2274EB7/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/F21B92F971>) |
| 8086:1902 |           | Intel            | HD Graphics 510                      | 5     | vgapci     | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 1a03:2000 | 1043:84eb | ASPEED Techno... | ASPEED Graphics Family               | 2     | vgapci     | [6BEC1EC37D](<Firewall/Thomas-Krenn.AG/P9/P9A-I-2550-4L/78DDC6BDB185/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/6BEC1EC37D>) |
| 8086:0102 | 8086:0102 | Intel            | 2nd Generation Core Processor Fam... | 2     | vgapci     | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:041e | 8086:041e | Intel            | 4th Generation Core Processor Fam... | 1     | vgapci     | [5109C6E2E4](<Firewall/Sophos/SG/SG/D46DBAD9D2F7/OPNSENSE-22.1.6/13.0-STABLE/AMD64/5109C6E2E4>) |
| 8086:191d |           | Intel            | HD Graphics P530                     | 1     | vgapci     | [96D3E064B2](<Firewall/Sophos/SG/SG/EFA303374041/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/96D3E064B2>) |
| 8086:22b1 | 8086:22b1 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | vgapci     | [E7D2DCA92D](<Firewall/Firewalla/FirewallaGold/FirewallaGold/AEC015EAF4EC/OPNSENSE-22.1.9/13.0-STABLE/AMD64/E7D2DCA92D>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:19de | 8086:7270 | Intel            | Atom Processor C3000 Series Power... | 13    |            | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    |            | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 40    | igb        | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:1533 | 15bb:30e0 | Intel            | I210 Gigabit Network Connection      | 33    | igb        | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:1536 |           | Intel            | I210 Gigabit Fiber Network Connec... | 25    | igb        | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:1522 |           | Intel            | I350 Gigabit Fiber Network Connec... | 14    | igb        | [08B02DFC2D](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/08B02DFC2D>) |
| 8086:1539 | 15bb:34e6 | Intel            | I211 Gigabit Network Connection      | 13    | igb        | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:15e5 |           | Intel            | Ethernet Connection X553 1GbE        | 13    | ix         | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 12    | em         | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:1521 |           | Intel            | I350 Gigabit Network Connection      | 12    | igb        | [08B02DFC2D](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/08B02DFC2D>) |
| 8086:10fb |           | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 6     | ix         | [96D3E064B2](<Firewall/Sophos/SG/SG/EFA303374041/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/96D3E064B2>) |
| 8086:1539 | 10f3:0101 | Intel            | I211 Gigabit Network Connection      | 5     | igb        | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 8086:15e4 |           | Intel            | Ethernet Connection X553 1GbE        | 4     | ix         | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:10c9 |           | Intel            | 82576 Gigabit Network Connection     | 2     | igb        | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:10e6 |           | Intel            | 82576 Gigabit Network Connection     | 2     | igb        | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:150e | 15bb:2002 | Intel            | 82580 Gigabit Network Connection     | 2     | igb        | [5109C6E2E4](<Firewall/Sophos/SG/SG/D46DBAD9D2F7/OPNSENSE-22.1.6/13.0-STABLE/AMD64/5109C6E2E4>) |
| 8086:1f41 | 1043:8638 | Intel            | Ethernet Connection I354             | 2     | igb        | [6BEC1EC37D](<Firewall/Thomas-Krenn.AG/P9/P9A-I-2550-4L/78DDC6BDB185/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/6BEC1EC37D>) |
| 8086:1f41 | 15bb:1f41 | Intel            | Ethernet Connection I354             | 2     | igb        | [68B230DF84](<Firewall/CheckPoint/PB-10/PB-10-00/22C5CECF7E1D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/68B230DF84>) |
| 14e4:165f | 14e4:2009 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 1     | bge        | [6BEC1EC37D](<Firewall/Thomas-Krenn.AG/P9/P9A-I-2550-4L/78DDC6BDB185/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/6BEC1EC37D>) |
| 8086:10c6 | 1374:0203 | Intel            | 82598EB 10-Gigabit AF Dual Port N... | 1     | ix         | [C6D1DB88BF](<Firewall/Sophos/SG/SG/822D9E620119/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/C6D1DB88BF>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 1     | ix         | [08B02DFC2D](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/08B02DFC2D>) |
| 8086:10fb | ffff:ffff | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 1     | ix         | [96D3E064B2](<Firewall/Sophos/SG/SG/EFA303374041/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/96D3E064B2>) |
| 8086:1521 | 15bb:0008 | Intel            | I350 Gigabit Network Connection      | 1     | igb        | [88EA908224](<Firewall/Sophos/SG/SG/C680308560C6/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/88EA908224>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 168c:003c |           | Qualcomm Atheros | QCA986x/988x 802.11ac Wireless Ne... | 6     |            | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 168c:0030 | 168c:3116 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 3     | ath        | [9ED491D56A](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F180/AF2B6B5BDFD0/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/9ED491D56A>) |
| 10ec:8178 | 10ec:8189 | Realtek Semic... | RTL8192CE PCIe Wireless Network A... | 2     |            | [AC861C4550](<Firewall/Others/Others/Others/5129D737B158/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/AC861C4550>) |
| 10ec:8176 | 10ec:8181 | Realtek Semic... | RTL8188CE 802.11b/g/n WiFi Adapter   | 1     |            | [FB003E1617](<Firewall/Lanner/Others/Others/3D71DCC655DC/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/FB003E1617>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 65    | igb        | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 32    | igb        | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 10    | em         | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2     | re         | [3F4D847974](<Firewall/Sophos/XG/XG/DA8FF58CC73B/OPNSENSE-22.1.10/13.0-STABLE/AMD64/3F4D847974>) |
| 8086:1531 |           | Intel            | I210 Gigabit Unprogrammed            | 1     |            | [3131AAE37B](<Firewall/Sophos/SG/SG/3E6356D8BD10/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/3131AAE37B>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [3F4D847974](<Firewall/Sophos/XG/XG/DA8FF58CC73B/OPNSENSE-22.1.10/13.0-STABLE/AMD64/3F4D847974>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    |            | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:19e0 | 8086:7270 | Intel            | Atom Processor C3000 Series SPI C... | 13    |            | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | pchtherm   | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | ichsmb     | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 29    | ichsmb     | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:19df | 8086:7270 | Intel            | Atom Processor C3000 Series SMBus... | 13    | ichsmb     | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | ichsmb     | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:283e | 8086:283e | Intel            | 82801H (ICH8 Family) SMBus Contro... | 12    | ichsmb     | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:27da | 8086:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 10    | ichsmb     | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:1f3c | 1462:1401 | Intel            | Atom processor C2000 PCU SMBus       | 5     | ichsmb     | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     |            | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:1f3c | 1043:8646 | Intel            | Atom processor C2000 PCU SMBus       | 2     | ichsmb     | [6BEC1EC37D](<Firewall/Thomas-Krenn.AG/P9/P9A-I-2550-4L/78DDC6BDB185/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/6BEC1EC37D>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 1     |            | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:2292 | 8086:2292 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | ichsmb     | [E7D2DCA92D](<Firewall/Firewalla/FirewallaGold/FirewallaGold/AEC015EAF4EC/OPNSENSE-22.1.9/13.0-STABLE/AMD64/E7D2DCA92D>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0c0c | 8086:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 32    | hdac       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | hdac       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:284b | 8086:284b | Intel            | 82801H (ICH8 Family) HD Audio Con... | 2     | hdac       | [785BB6C2A0](<Firewall/Sophos/UTM/UTM/C0D72EB7E27E/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/785BB6C2A0>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | hdac       | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:2284 | 8086:2284 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | hdac       | [E7D2DCA92D](<Firewall/Firewalla/FirewallaGold/FirewallaGold/AEC015EAF4EC/OPNSENSE-22.1.9/13.0-STABLE/AMD64/E7D2DCA92D>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | ahci       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 29    | ahci       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | ahci       | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:19b2 | 8086:7270 | Intel            | Atom Processor C3000 Series SATA ... | 13    | ahci       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:2829 | 8086:2829 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 12    | ahci       | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 12    | ahci       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:27c1 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 10    | ahci       | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:1f22 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA2 C... | 9     | ahci       | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 8086:1f32 | 1462:1401 | Intel            | Atom processor C2000 AHCI SATA3 C... | 5     | ahci       | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:1c02 | 8086:1c02 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ahci       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:1f32 | 1043:8646 | Intel            | Atom processor C2000 AHCI SATA3 C... | 2     | ahci       | [6BEC1EC37D](<Firewall/Thomas-Krenn.AG/P9/P9A-I-2550-4L/78DDC6BDB185/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/6BEC1EC37D>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ahci       | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:22a3 | 8086:22a3 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | ahci       | [E7D2DCA92D](<Firewall/Firewalla/FirewallaGold/FirewallaGold/AEC015EAF4EC/OPNSENSE-22.1.9/13.0-STABLE/AMD64/E7D2DCA92D>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2850 | 8086:2850 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 12    | atapci     | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 9     | atapci     | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2822 | 8086:7270 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [96D3E064B2](<Firewall/Sophos/SG/SG/EFA303374041/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/96D3E064B2>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f15 |           | Intel            | Atom processor C2000 SMBus 2.0       | 36    |            | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1f16 |           | Intel            | Atom processor C2000 RCEC            | 36    |            | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:19a2 |           | Intel            | Atom Processor C3000 Series Root ... | 13    |            | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:19ac |           | Intel            | Atom Processor C3000 Series SMBus... | 13    |            | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c26 | 8086:8c26 | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | ehci       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:8c2d | 8086:8c2d | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | ehci       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:8c31 | 8086:8c31 | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | xhci       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 29    | ehci       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    | xhci       | [26CD20E559](<Firewall/Sophos/SG/SG/810780DBBB1C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/26CD20E559>) |
| 8086:19d0 | 8086:7270 | Intel            | Atom Processor C3000 Series USB 3... | 13    | xhci       | [8BF27537E4](<Firewall/Sophos/XG/XG/F30F4F255A8F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8BF27537E4>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 13    | xhci       | [7E05FCAF2B](<Firewall/Sophos/SG/SG/1ED9533B827A/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E05FCAF2B>) |
| 8086:2830 | 8086:2830 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 12    | uhci       | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:2831 | 8086:2831 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 12    | uhci       | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:2836 | 8086:2836 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 12    | ehci       | [806A078730](<Firewall/Sophos/UTM/UTM/EFBED6E2C955/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/806A078730>) |
| 8086:27c8 | 8086:27c8 | Intel            | NM10/ICH7 Family USB UHCI Control... | 10    | uhci       | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:27c9 | 8086:27c9 | Intel            | NM10/ICH7 Family USB UHCI Control... | 10    | uhci       | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:27ca | 8086:27ca | Intel            | NM10/ICH7 Family USB UHCI Control... | 10    | uhci       | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:27cb | 8086:27cb | Intel            | NM10/ICH7 Family USB UHCI Control... | 10    | uhci       | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:27cc | 8086:27cc | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 10    | ehci       | [4B0EACE553](<Firewall/Sophos/UTM/UTM/5C52545E635C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4B0EACE553>) |
| 8086:1f2c | 1462:1401 | Intel            | Atom processor C2000 USB Enhanced... | 5     | ehci       | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:1c26 | 8086:1c26 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ehci       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:1c2d | 8086:1c2d | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ehci       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:1f2c | 1043:8646 | Intel            | Atom processor C2000 USB Enhanced... | 2     | ehci       | [6BEC1EC37D](<Firewall/Thomas-Krenn.AG/P9/P9A-I-2550-4L/78DDC6BDB185/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/6BEC1EC37D>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 1     | xhci       | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:22b5 | 8086:22b5 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | xhci       | [E7D2DCA92D](<Firewall/Firewalla/FirewallaGold/FirewallaGold/AEC015EAF4EC/OPNSENSE-22.1.9/13.0-STABLE/AMD64/E7D2DCA92D>) |

