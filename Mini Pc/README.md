Most popular PCI devices in Mini Pcs
====================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Mini Pcs ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Multimedia ](#multimedia-pci)
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
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ Storage/scsi ](#storagescsi-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f00 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 96    | hostb      | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 92    | isab       | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:0f48 | 8086:0f48 | Intel            | Atom Processor E3800 Series PCI E... | 92    | pcib       | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:0f4a | 8086:0f4a | Intel            | Atom Processor E3800 Series PCI E... | 92    | pcib       | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:0f4c | 8086:0f4c | Intel            | Atom Processor E3800 Series PCI E... | 92    | pcib       | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:0f4e | 8086:0f4e | Intel            | Atom Processor E3800 Series PCI E... | 91    | pcib       | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:31f0 |           | Intel            | Gemini Lake Host Bridge              | 75    | hostb      | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:5ad9 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | pcib       | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:5ada |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | pcib       | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | isab       | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | hostb      | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:5ad8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    | pcib       | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 1022:141a |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 38    | hostb      | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:141b |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 38    | hostb      | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:141c |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 38    | hostb      | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:141d |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 38    | hostb      | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:141e |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 38    | hostb      | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:141f |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 38    | hostb      | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:1422 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) Proce... | 38    | hostb      | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:1424 |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 38    | hostb      | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:1425 | 103c:8103 | AMD              | Kaveri P2P Bridge for GFX PCIe Po... | 38    | pcib       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:780e | 103c:8103 | AMD              | FCH LPC Bridge                       | 38    | isab       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:780f |           | AMD              | FCH PCI Bridge                       | 38    | pcib       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:1426 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) Proce... | 35    | pcib       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    | hostb      | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    | isab       | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    | pcib       | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:22ca | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 30    | pcib       | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:31d6 | 8086:31d6 | Intel            | Gemini Lake PCI Express Root Port    | 25    | pcib       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31d7 | 8086:31d7 | Intel            | Gemini Lake PCI Express Root Port    | 25    | pcib       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31d8 | 8086:31d8 | Intel            | Gemini Lake PCI Express Root Port    | 25    | pcib       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31d9 | 8086:31d9 | Intel            | Gemini Lake PCI Express Root Port    | 25    | pcib       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31da | 8086:31da | Intel            | Gemini Lake PCI Express Root Port    | 25    | pcib       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31e8 | 8086:31e8 | Intel            | Celeron/Pentium Silver Processor ... | 25    | isab       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 24    | pcib       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:1f10 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 24    | pcib       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:1f11 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 24    | pcib       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:1f12 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 24    | pcib       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:1f14 |           | Intel            | Atom processor C2000 RAS             | 24    | hostb      | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:1f38 | 8086:7270 | Intel            | Atom processor C2000 PCU             | 24    | isab       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:22cc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 23    | pcib       | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:0f1c | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 22    | isab       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:0f48 | 8086:7270 | Intel            | Atom Processor E3800 Series PCI E... | 22    | pcib       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:0f4a | 8086:7270 | Intel            | Atom Processor E3800 Series PCI E... | 22    | pcib       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:0f4c | 8086:7270 | Intel            | Atom Processor E3800 Series PCI E... | 22    | pcib       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:0f4e | 8086:7270 | Intel            | Atom Processor E3800 Series PCI E... | 22    | pcib       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:31e8 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    | isab       | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:0f00 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 21    | hostb      | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 21    | pcib       | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 21    | isab       | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 11    | rtsx       | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 10    | rtsx       | [17F444775B](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/9A43951EB263/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/17F444775B>) |
| 10ec:5229 | 8086:2072 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx       | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 10ec:5229 | 8086:2067 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx       | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx       | [7C34BE7C2E](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/9D3A033CEC7D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7C34BE7C2E>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 17    | qat        | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 8086:0434 |           | Intel            | DH89XXCC Series QAT                  | 2     |            | [1EAA616342](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1EAA616342>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    |            | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 25    |            | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:319a | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    |            | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 21    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:5a9a |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:9de0 | 8086:2074 | Intel            | Cannon Point-LP MEI Controller #1    | 14    |            | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:a360 | 17aa:312d | Intel            | Cannon Lake PCH HECI Controller      | 13    |            | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:9d3a | 8086:2068 | Intel            | Sunrise Point-LP CSME HECI #1        | 11    |            | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:9cba | 8086:2057 | Intel            | Wildcat Point-LP MEI Controller #1   | 10    |            | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 10    |            | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:319a | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 9     |            | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:02e0 | 8086:2081 | Intel            | Comet Lake Management Engine Inte... | 8     |            | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     |            | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:5a9c | 8086:7270 | Intel            |                                      | 7     |            | [A6A5DE19AE](<Mini Pc/AWOW/PC/PC BOX/C22C936E0B18/OPNSENSE-22.1.9/13.0-STABLE/AMD64/A6A5DE19AE>) |
| 8086:5a9e | 8086:7270 | Intel            |                                      | 7     |            | [A6A5DE19AE](<Mini Pc/AWOW/PC/PC BOX/C22C936E0B18/OPNSENSE-22.1.9/13.0-STABLE/AMD64/A6A5DE19AE>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 7     |            | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 8086:319a | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 6     |            | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 8086:9d3a | 8086:2063 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     |            | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:9de0 | 17aa:314d | Intel            | Cannon Point-LP MEI Controller #1    | 6     |            | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 8086:a2ba | 103c:829a | Intel            | 200 Series PCH CSME HECI #1          | 5     |            | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 8086:a2bd | 103c:829a | Intel            | 200 Series Chipset Family KT Redi... | 5     |            | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 8086:a360 | 17aa:3136 | Intel            | Cannon Lake PCH HECI Controller      | 5     |            | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 10ec:816a | 1043:85b5 | Realtek Semic... | RTL8111xP UART #1                    | 4     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 10ec:816b | 1043:85b5 | Realtek Semic... | RTL8111xP UART #2                    | 4     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:a328 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 4     |            | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:a360 | 8086:2089 | Intel            | Cannon Lake PCH HECI Controller      | 4     |            | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 3     |            | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:5a9c |           | Intel            |                                      | 3     |            | [D42B40D22C](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/1A72333A0387/OPNSENSE-22.1.8/13.0-STABLE/AMD64/D42B40D22C>) |
| 8086:5a9e |           | Intel            | unknown                              | 3     |            | [D42B40D22C](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/1A72333A0387/OPNSENSE-22.1.8/13.0-STABLE/AMD64/D42B40D22C>) |
| 8086:a363 | 17aa:3136 | Intel            | Cannon Lake PCH Active Management... | 3     |            | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 8086:06e0 | 17aa:3172 | Intel            | Comet Lake HECI Controller           | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:06e3 | 17aa:3172 | Intel            | Comet Lake Keyboard and Text (KT)... | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 2     |            | [0D6E868D9C](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0D6E868D9C>) |
| 8086:9d3a | 8086:2070 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a13a | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 8086:a2ba | 17aa:310b | Intel            | 200 Series PCH CSME HECI #1          | 2     |            | [E0F08B66C2](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MV000NUS/1C0874D9DEC1/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/E0F08B66C2>) |
| 10ec:816a | 103c:8522 | Realtek Semic... | RTL8111xP UART #1                    | 1     |            | [CAE055641A](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/CAE055641A>) |
| 10ec:816a | 103c:8523 | Realtek Semic... | RTL8111xP UART #1                    | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 10ec:816b | 103c:8522 | Realtek Semic... | RTL8111xP UART #2                    | 1     |            | [CAE055641A](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/CAE055641A>) |
| 10ec:816b | 103c:8523 | Realtek Semic... | RTL8111xP UART #2                    | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1415:c118 | 1415:c118 | Oxford Semico... | OXPCIe952 Parallel Port              | 1     |            | [0AC430C0C9](<Mini Pc/AMI/Aptio/Aptio CRB/7C6EDFADB996/OPNSENSE-22.1.6/13.0-STABLE/AMD64/0AC430C0C9>) |
| 1415:c11b | 1415:c11b | Oxford Semico... | OXPCIe952 Native 950 UART            | 1     | puc        | [0AC430C0C9](<Mini Pc/AMI/Aptio/Aptio CRB/7C6EDFADB996/OPNSENSE-22.1.6/13.0-STABLE/AMD64/0AC430C0C9>) |
| 8086:02e0 | 19da:b418 | Intel            | Comet Lake Management Engine Inte... | 1     |            | [4C3BE7EC24](<Mini Pc/ZOTAC/ZBOX-CI622/ZBOX-CI622-CI642-CI662NANO/6C326764845F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4C3BE7EC24>) |
| 8086:02e0 | 19da:b426 | Intel            | Comet Lake Management Engine Inte... | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:06a8 | 19da:b429 | Intel            | Comet Lake PCH Serial IO UART Hos... | 1     |            | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:06e0 | 17aa:316a | Intel            | Comet Lake HECI Controller           | 1     |            | [26C9557A0A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90q 11DGS11W00/D40AF8580548/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/26C9557A0A>) |
| 8086:06e0 | 17aa:316e | Intel            | Comet Lake HECI Controller           | 1     |            | [2A7C8F55CB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUSBYK00/4E36DF922C91/FREEBSD-13.1/13.1-RELEASE/AMD64/2A7C8F55CB>) |
| 8086:06e0 | 19da:b429 | Intel            | Comet Lake HECI Controller           | 1     |            | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:06e3 | 17aa:316a | Intel            | Comet Lake Keyboard and Text (KT)... | 1     |            | [26C9557A0A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90q 11DGS11W00/D40AF8580548/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/26C9557A0A>) |
| 8086:1c3a | 19da:b202 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     |            | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 93    |            | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    |            | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 22    |            | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    |            | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
| 8086:2298 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     |            | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     |            | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 4     |            | [C233FA7D25](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/5DF17C3B70F0/FREEBSD-13.1/13.1-RELEASE/AMD64/C233FA7D25>) |
| 8086:0f18 | 1071:0730 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [294F283D65](<Mini Pc/AMI/Aptio/Aptio CRB/293083C7BA4B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/294F283D65>) |
| 8086:2298 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     |            | [8B634987B4](<Mini Pc/Shuttle/XS35/XS35V5/4F433C551703/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/8B634987B4>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 1     |            | [DE45E5A021](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/766906F5D7C3/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/DE45E5A021>) |
| 1022:15df | 103c:8522 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15df | 103c:8523 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:15df | 17aa:3190 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 8086:0f18 | 1028:0720 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [0AF7422E2F](<Mini Pc/Dell/Edge/Edge Gateway 5000/CAF5F709CDDF/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/0AF7422E2F>) |
| 8086:0f18 | 1071:0740 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [D514362239](<Mini Pc/AMI/Aptio/Aptio CRB/7AF86A68764E/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/D514362239>) |
| 8086:2298 | 1019:9af1 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [A2FC9672D6](<Mini Pc/AMI/Aptio/Aptio CRB/4B0558708572/OPNSENSE-22.1.6/13.0-STABLE/AMD64/A2FC9672D6>) |
| 8086:2298 | 1462:b120 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [AA27C1DFD0](<Mini Pc/MSI/MS-B/MS-B120/07E1FDD9727B/FREEBSD-13.1/13.1-RELEASE/AMD64/AA27C1DFD0>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 10    | fwohci     | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 5     | fwohci     | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 94    | vgapci     | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 44    | vgapci     | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 1002:131c | 103c:8103 | AMD              | Kaveri [Radeon R7 Graphics]          | 38    | vgapci     | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 30    | vgapci     | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 27    | vgapci     | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 1a03:2000 | 15d9:0813 | ASPEED Techno... | ASPEED Graphics Family               | 24    | vgapci     | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 23    | vgapci     | [14F174BD7C](<Mini Pc/BESSTAR Tech/GK/GK41/46F6D804D9F8/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/14F174BD7C>) |
| 8086:0f31 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 21    | vgapci     | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:3184 | 1028:080c | Intel            | GeminiLake [UHD Graphics 605]        | 18    | vgapci     | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:22b1 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | vgapci     | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
| 8086:3ea5 | 8086:2074 | Intel            | CoffeeLake-U GT3e [Iris Plus Grap... | 13    | vgapci     | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:5a85 | 19da:b325 | Intel            | HD Graphics 500                      | 13    | vgapci     | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 8086:3e92 | 17aa:312d | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 8     | vgapci     | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:5917 | 8086:2015 | Intel            | UHD Graphics 620                     | 8     | vgapci     | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:22b1 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | vgapci     | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:1616 | 8086:2057 | Intel            | HD Graphics 5500                     | 6     | i915       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:3185 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 600]        | 6     | vgapci     | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:3ea0 | 17aa:314d | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 6     | vgapci     | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 1002:1636 | 1043:87e7 | AMD              | Renoir                               | 5     | vgapci     | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1002:9806 | 103c:17e2 | AMD              | Wrestler [Radeon HD 6320]            | 5     | vgapci     | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 8086:5916 | 8086:2068 | Intel            | HD Graphics 620                      | 5     | vgapci     | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:5a84 | 8086:2212 | Intel            | Apollo Lake [HD Graphics 505]        | 5     | vgapci     | [ADC2C951C6](<Mini Pc/CompuLab/fitlet/fitlet2/9527BFA559DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/ADC2C951C6>) |
| 8086:5a85 | 8086:2067 | Intel            | HD Graphics 500                      | 5     | vgapci     | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:9bca | 8086:2081 | Intel            | Comet Lake UHD Graphics              | 5     | i915       | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:0126 | 106b:00e6 | Intel            | 2nd Generation Core Processor Fam... | 4     | vgapci     | [EE4D6D5761](<Mini Pc/Apple/Macmini5/Macmini5,1/FDCA8312B94D/FREEBSD-13.1/13.1-RELEASE/AMD64/EE4D6D5761>) |
| 8086:0a2e | 106b:0141 | Intel            | Haswell-ULT Integrated Graphics C... | 4     | vgapci     | [3FA9F3AA5C](<Mini Pc/Apple/Macmini7/Macmini7,1/1A649251B7BE/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/3FA9F3AA5C>) |
| 8086:1626 | 8086:2057 | Intel            | HD Graphics 6000                     | 4     | i915       | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:1926 | 8086:2063 | Intel            | Iris Graphics 540                    | 4     | vgapci     | [D448C2DD6C](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/ECD0E5CB4280/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/D448C2DD6C>) |
| 8086:3185 | 1028:080c | Intel            | GeminiLake [UHD Graphics 600]        | 4     | vgapci     | [29B3E0B639](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/C597086BD3D1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/29B3E0B639>) |
| 8086:3e92 | 17aa:3136 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 4     | vgapci     | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 8086:3e9b | 8086:2089 | Intel            | CoffeeLake-H GT2 [UHD Graphics 630]  | 4     | vgapci     | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 10de:0861 | 106b:00ae | Nvidia           | C79 [GeForce 9400]                   | 3     | nvidia     | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:1912 | 103c:829a | Intel            | HD Graphics 530                      | 3     | i915       | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:3184 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 605]        | 3     | vgapci     | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:3184 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 605]        | 3     | i915       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:3e91 | 17aa:312d | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 3     | vgapci     | [CC0380B2C6](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SSKB00/2C122F875084/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/CC0380B2C6>) |
| 8086:5926 | 8086:2068 | Intel            | Iris Plus Graphics 640               | 3     | i915       | [66F9B621BE](<Mini Pc/Intel/NUC7/NUC7i5BNK/DB7E10F2F9E0/FREEBSD-13.1/13.1-RELEASE/AMD64/66F9B621BE>) |
| 8086:5927 | 8086:2068 | Intel            | Iris Plus Graphics 650               | 3     | vgapci     | [934EDFE03D](<Mini Pc/Intel/NUC7/NUC7i7BNHXG/9373B98A6CA8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/934EDFE03D>) |
| 8086:9b41 | 8086:2081 | Intel            | CometLake-U GT2 [UHD Graphics]       | 3     | vgapci     | [7189B48418](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNH/2E0BD0D062A7/FREEBSD-13.1/13.1-RELEASE/AMD64/7189B48418>) |
| 1002:6741 | 106b:00e8 | AMD              | Whistler [Radeon HD 6630M/6650M/6... | 2     | vgapci     | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 1002:9831 | 1022:1234 | AMD              | Kabini [Radeon HD 8400E]             | 2     | vgapci     | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 1002:9851 | 1022:1234 | AMD              | Mullins [Radeon R4/R5 Graphics]      | 2     | radeon     | [C233FA7D25](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/5DF17C3B70F0/FREEBSD-13.1/13.1-RELEASE/AMD64/C233FA7D25>) |
| 10de:08a4 | 106b:00c0 | Nvidia           | MCP89 [GeForce 320M]                 | 2     | vgapci     | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 8086:0116 | 106b:00e7 | Intel            | 2nd Generation Core Processor Fam... | 2     | i915       | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:0126 | 106b:00f0 | Intel            | 2nd Generation Core Processor Fam... | 2     | vgapci     | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:0166 | 106b:0101 | Intel            | 3rd Gen Core processor Graphics C... | 2     | i915       | [AC585B4E0D](<Mini Pc/Apple/Macmini6/Macmini6,2/FAC8616568BC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/AC585B4E0D>) |
| 8086:1616 | 19da:b246 | Intel            | HD Graphics 5500                     | 2     | vgapci     | [0D6E868D9C](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0D6E868D9C>) |
| 8086:1916 | 8086:2063 | Intel            | Skylake GT2 [HD Graphics 520]        | 2     | vgapci     | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:22b1 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | vgapci     | [8253122F23](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/DDD09FCC3013/OPNSENSE-22.1.4/13.0-STABLE/AMD64/8253122F23>) |
| 8086:22b1 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | vgapci     | [8B634987B4](<Mini Pc/Shuttle/XS35/XS35V5/4F433C551703/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/8B634987B4>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9def | 8086:2074 | Intel            | Cannon Point-LP Shared SRAM          | 14    |            | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:a36f | 17aa:312d | Intel            | Cannon Lake PCH Shared SRAM          | 13    |            | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:9d21 | 8086:2068 | Intel            | Sunrise Point-LP PMC                 | 11    |            | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 10    |            | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:02ef | 8086:2081 | Intel            | Comet Lake PCH-LP Shared SRAM        | 8     |            | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:9d21 | 8086:2063 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:9def | 17aa:314d | Intel            | Cannon Point-LP Shared SRAM          | 6     |            | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 8086:a2a1 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family Po... | 5     |            | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 8086:a36f | 17aa:3136 | Intel            | Cannon Lake PCH Shared SRAM          | 5     |            | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 4     |            | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM Controller   | 3     |            | [353C3D5CEE](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/CCFFCDBA4F23/FREEBSD-13.1/13.1-RELEASE/AMD64/353C3D5CEE>) |
| 10de:0d68 |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d69 |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d6d |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d6e |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d6f |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d70 |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d71 |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d72 |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d75 |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:0d7b |           | Nvidia           | MCP89 Memory Controller              | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 2     |            | [4C3BE7EC24](<Mini Pc/ZOTAC/ZBOX-CI622/ZBOX-CI622-CI642-CI662NANO/6C326764845F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4C3BE7EC24>) |
| 8086:06ef | 17aa:3172 | Intel            | Comet Lake PCH Shared SRAM           | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:9d21 | 8086:2070 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 2     |            | [7C34BE7C2E](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/9D3A033CEC7D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7C34BE7C2E>) |
| 8086:a121 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 8086:a2a1 | 17aa:310b | Intel            | 200 Series/Z370 Chipset Family Po... | 2     |            | [E0F08B66C2](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MV000NUS/1C0874D9DEC1/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/E0F08B66C2>) |
| 8086:06ef | 17aa:316a | Intel            | Comet Lake PCH Shared SRAM           | 1     |            | [26C9557A0A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90q 11DGS11W00/D40AF8580548/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/26C9557A0A>) |
| 8086:06ef | 17aa:316e | Intel            | Comet Lake PCH Shared SRAM           | 1     |            | [2A7C8F55CB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUSBYK00/4E36DF922C91/FREEBSD-13.1/13.1-RELEASE/AMD64/2A7C8F55CB>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 1     |            | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 1     |            | [9E304DE7AD](<Mini Pc/Chuwi/CoreBox/CoreBox Pro/24BC2F453B95/OPNSENSE-22.7/13.1-RELEASE/AMD64/9E304DE7AD>) |
| 8086:9d21 | 103c:84f5 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [99C0387102](<Mini Pc/Hewlett-Packard/260/260 G3 DM/A07056395B55/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/99C0387102>) |
| 8086:a0ef | 17aa:319e | Intel            | Tiger Lake-LP Shared SRAM            | 1     |            | [33545A5181](<Mini Pc/Lenovo/ThinkEdge/ThinkEdge SE30 11NA0005UK/1A1BE0BDD989/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/33545A5181>) |
| 8086:a121 | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [EA77AA3506](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.1.4/13.0-STABLE/AMD64/EA77AA3506>) |
| 8086:a121 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 8086:a36f | 17aa:3135 | Intel            | Cannon Lake PCH Shared SRAM          | 1     |            | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 6     |            | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 1022:15e2 | 103c:8522 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15e2 | 103c:8523 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:15e2 | 17aa:3190 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [2ECB6FABA3](<Mini Pc/AMI/Aptio/Aptio CRB/FEA9A2F7C9FB/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2ECB6FABA3>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 103c:8103 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 34    | re         | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:1f41 | 15d9:1f41 | Intel            | Ethernet Connection I354             | 24    | igb        | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 10ec:8168 | 1028:080c | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 20    | re         | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 16    | igb        | [8B2537708C](<Mini Pc/AMI/Aptio/Aptio CRB/741B1A4C2989/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/8B2537708C>) |
| 8086:15be | 8086:2074 | Intel            | Ethernet Connection (6) I219-V       | 14    | em         | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 10ec:8168 | 19da:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | re         | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:1521 | 8086:5001 | Intel            | I350 Gigabit Network Connection      | 13    | igb        | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 8086:15bc | 17aa:312d | Intel            | Ethernet Connection (7) I219-V       | 13    | em         | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:150c | 1462:6c40 | Intel            | 82583V Gigabit Network Connection    | 12    | em         | [7B36D32911](<Mini Pc/AMI/Aptio/Aptio CRB/032FDEA67E2A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7B36D32911>) |
| 8086:15d8 | 8086:2068 | Intel            | Ethernet Connection (4) I219-V       | 11    | em         | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:15f3 |           | Intel            | Ethernet Controller I225-V           | 9     | igc        | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:0d4f | 8086:2081 | Intel            | Ethernet Connection (10) I219-V      | 8     | em         | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 7     | bge        | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 10ec:8168 | 1854:0309 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | re         | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 14e4:1682 | 106b:00f6 | Broadcom         | NetXtreme BCM57762 Gigabit Ethern... | 6     | bge        | [3FA9F3AA5C](<Mini Pc/Apple/Macmini7/Macmini7,1/1A649251B7BE/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/3FA9F3AA5C>) |
| 8086:150e | 103c:1780 | Intel            | 82580 Gigabit Network Connection     | 6     | igb        | [3502CB3D47](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/1F40335DE972/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3502CB3D47>) |
| 8086:1521 | 8086:00a1 | Intel            | I350 Gigabit Network Connection      | 6     | igb        | [799410C58F](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T70049PG/C18B8CE60627/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/799410C58F>) |
| 10ec:8168 | 17aa:314d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | re         | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 10ec:8168 | 8086:2067 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | re         | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 14e4:16b1 | 103c:17e2 | Broadcom         | NetLink BCM57781 Gigabit Ethernet... | 5     | bge        | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 8086:15e3 | 103c:829a | Intel            | Ethernet Connection (5) I219-LM      | 5     | em         | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 10ec:8168 | 1043:85b5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | re         | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 4     | igb        | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:15bb |           | Intel            | Ethernet Connection (7) I219-LM      | 4     | em         | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:15bb | 17aa:3136 | Intel            | Ethernet Connection (7) I219-LM      | 4     | em         | [69A9AE7BDE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS23202/A61F164E4C35/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/69A9AE7BDE>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 3     | nfe        | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:10bc | 103c:704b | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 3     | em         | [5C70BA3A0D](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/008D25A435CA/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/5C70BA3A0D>) |
| 8086:1521 | 108e:7b18 | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [D7DF2919B1](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/8CB303EC9705/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D7DF2919B1>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2     | re         | [C59E578A6F](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/AB7EFCE05228/OPNSENSE-22.1.10/13.0-STABLE/AMD64/C59E578A6F>) |
| 10ec:8168 | 1170:af06 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2     | re         | [C233FA7D25](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/5DF17C3B70F0/FREEBSD-13.1/13.1-RELEASE/AMD64/C233FA7D25>) |
| 14e4:165f | 14e4:2003 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 2     | bge        | [364241899F](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E658728E0DEE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/364241899F>) |
| 8086:0438 |           | Intel            | DH8900CC Series Gigabit Network C... | 2     | igb        | [1EAA616342](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1EAA616342>) |
| 8086:0d4c | 17aa:3172 | Intel            | Ethernet Connection (11) I219-LM     | 2     | em         | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:105e | 1014:0340 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 2     | em         | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:10fb | 8086:7a11 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 2     | ix         | [3DF56777E3](<Mini Pc/Supermicro/A1/A1SAi/B04DB45BDDAF/OPNSENSE-22.1.3/13.0-STABLE/AMD64/3DF56777E3>) |
| 8086:150a | 1734:11a7 | Intel            | 82576NS Gigabit Network Connection   | 2     | igb        | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 2     | em         | [49A60B6412](<Mini Pc/AMI/Aptio/Aptio CRB/22173DD6FB43/OPNSENSE-22.7/13.1-RELEASE/AMD64/49A60B6412>) |
| 8086:1539 | 1297:4033 | Intel            | I211 Gigabit Network Connection      | 2     | igb        | [8B634987B4](<Mini Pc/Shuttle/XS35/XS35V5/4F433C551703/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/8B634987B4>) |
| 8086:156f |           | Intel            | Ethernet Connection I219-LM          | 2     | em         | [231A0F9CE0](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/231A0F9CE0>) |
| 8086:15b7 | 17aa:310b | Intel            | Ethernet Connection (2) I219-LM      | 2     | em         | [E0F08B66C2](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MV000NUS/1C0874D9DEC1/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/E0F08B66C2>) |
| 1077:8020 | 103c:3733 | QLogic           | cLOM8214 1/10GbE Controller          | 1     |            | [97EF9E2512](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/FD006DFAF57D/OPNSENSE-22.1.8/13.0-STABLE/AMD64/97EF9E2512>) |
| 10ec:8125 | 1043:87d7 | Realtek Semic... | RTL8125 2.5GbE Controller            | 1     | re         | [2781B31F9B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50-E1/A2FA457F7B31/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/2781B31F9B>) |
| 10ec:8168 | 1019:a6e2 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 10ec:8168 | 1025:1124 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [F38B7DF811](<Mini Pc/Acer/Aptio/Aptio CRB/C56C7B1EE4CC/OPNSENSE-22.1.3/13.0-STABLE/AMD64/F38B7DF811>) |
| 10ec:8168 | 1028:0720 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [0AF7422E2F](<Mini Pc/Dell/Edge/Edge Gateway 5000/CAF5F709CDDF/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/0AF7422E2F>) |
| 10ec:8168 | 103c:8158 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [DE45E5A021](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/766906F5D7C3/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/DE45E5A021>) |
| 10ec:8168 | 103c:84f5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [99C0387102](<Mini Pc/Hewlett-Packard/260/260 G3 DM/A07056395B55/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/99C0387102>) |
| 10ec:8168 | 103c:8522 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 10ec:8168 | 103c:8523 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [34DD85F78D](<Mini Pc/CompuLab/fit-PC/fit-PC3/F6EE642348DC/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/34DD85F78D>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 46    | iwm        | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 26    | iwm        | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 21    | iwm        | [AC4F4B181A](<Mini Pc/AWOW/PC/PC BOX/8958FD020A20/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/AC4F4B181A>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 16    | iwm        | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 15    |            | [14F174BD7C](<Mini Pc/BESSTAR Tech/GK/GK41/46F6D804D9F8/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/14F174BD7C>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 11    | iwm        | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 10    | iwm        | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 9     | iwm        | [66F9B621BE](<Mini Pc/Intel/NUC7/NUC7i5BNK/DB7E10F2F9E0/FREEBSD-13.1/13.1-RELEASE/AMD64/66F9B621BE>) |
| 14e4:4331 | 14e4:4331 | Broadcom         | BCM4331 802.11a/b/g/n                | 8     | bwn_pci    | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 8     | iwlwifi    | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 8     | iwm        | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 10ec:c822 | 1a3b:4210 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 7     |            | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 7     | iwm        | [0D6E868D9C](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0D6E868D9C>) |
| 8086:31dc | 8086:4030 | Intel            | Gemini Lake PCH CNVi WiFi            | 7     | iwm        | [EFCAE22B58](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/BA5781C03C6E/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/EFCAE22B58>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 6     | iwm        | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 14e4:43a0 | 106b:013b | Broadcom         | BCM4360 802.11ac Wireless Network... | 5     |            | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 8086:24f3 | 8086:1010 | Intel            | Wireless 8260                        | 5     | iwm        | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:24f3 | 8086:9010 | Intel            | Wireless 8260                        | 5     | iwm        | [D448C2DD6C](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-505/ECD0E5CB4280/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/D448C2DD6C>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 5     |            | [BFC921BFBB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700A9GE/621CFA7E8D6B/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/BFC921BFBB>) |
| 14e4:4359 | 103c:8088 | Broadcom         | BCM43228 802.11a/b/g/n               | 4     |            | [F187229469](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/B08F81A68A52/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/F187229469>) |
| 8086:2723 | 8086:008c | Intel            | Wi-Fi 6 AX200                        | 4     | iwlwifi    | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 14e4:4328 | 106b:0090 | Broadcom         | BCM4321 802.11a/b/g/n                | 3     | bwn_pci    | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 3     | iwm        | [E0F08B66C2](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MV000NUS/1C0874D9DEC1/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/E0F08B66C2>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 3     | iwm        | [75EE70A8CD](<Mini Pc/BESSTAR Tech/GK/GK41/6643A2716B62/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/75EE70A8CD>) |
| 8086:3165 | 8086:8110 | Intel            | Wireless 3165                        | 3     | iwm        | [C50B531526](<Mini Pc/AZW/GK/GK mini/30D10F3BA4D9/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C50B531526>) |
| 8086:4232 | 8086:1201 | Intel            | WiFi Link 5100                       | 3     | iwn        | [A2FC9672D6](<Mini Pc/AMI/Aptio/Aptio CRB/4B0558708572/OPNSENSE-22.1.6/13.0-STABLE/AMD64/A2FC9672D6>) |
| 10ec:8723 | 10ec:0733 | Realtek Semic... | RTL8723AE PCIe Wireless Network A... | 2     |            | [34DD85F78D](<Mini Pc/CompuLab/fit-PC/fit-PC3/F6EE642348DC/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/34DD85F78D>) |
| 10ec:c821 | 1a3b:3043 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 2     |            | [74C2F601FD](<Mini Pc/GEEK+/G/G34/FF8C1DD2C8F0/OPNSENSE-22.1.3/13.0-STABLE/AMD64/74C2F601FD>) |
| 14e4:4331 | 106b:010e | Broadcom         | BCM4331 802.11a/b/g/n                | 2     | bwn_pci    | [AC585B4E0D](<Mini Pc/Apple/Macmini6/Macmini6,2/FAC8616568BC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/AC585B4E0D>) |
| 14e4:4353 | 106b:0093 | Broadcom         | BCM43224 802.11a/b/g/n               | 2     | bwn_pci    | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 168c:0030 | 168c:3110 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 2     | ath        | [02E11159F5](<Mini Pc/Sophos/SG/SG/C85DCE3C368F/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/02E11159F5>) |
| 168c:003e | 11ad:0513 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 2     |            | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 2     | iwm        | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:4df0 | 8086:02a4 | Intel            | Wi-Fi 6 AX201 160MHz                 | 2     | iwlwifi    | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:a370 | 8086:0030 | Intel            | Cannon Lake PCH CNVi WiFi            | 2     | iwm        | [E0F42A2BB2](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RS000UUS/EC738E37478F/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/E0F42A2BB2>) |
| 10ec:8172 | 10ec:e020 | Realtek Semic... | RTL8191SEvB Wireless LAN Controller  | 1     |            | [EF9E76D0EA](<Mini Pc/AMI/Aptio/Aptio CRB/DBF8308BC7DC/DRAGONFLY-5.9-DEVELOPMENT/5.9-DEVELOPMENT/AMD64/EF9E76D0EA>) |
| 10ec:8179 | 10ec:8179 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 1     |            | [BFD71EFA3B](<Mini Pc/Shuttle/XS35/XS35V5/34C200C6C0F7/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BFD71EFA3B>) |
| 10ec:8179 | 1a3b:219a | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 1     | rtwn       | [AA27C1DFD0](<Mini Pc/MSI/MS-B/MS-B120/07E1FDD9727B/FREEBSD-13.1/13.1-RELEASE/AMD64/AA27C1DFD0>) |
| 11ab:2b38 |           | Marvell Techn... | 88W8897 [AVASTAR] 802.11ac Wireless  | 1     |            | [0AF7422E2F](<Mini Pc/Dell/Edge/Edge Gateway 5000/CAF5F709CDDF/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/0AF7422E2F>) |
| 14e4:43a3 | 1028:0023 | Broadcom         | BCM4350 802.11ac Wireless Network... | 1     |            | [2BF8839D12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S1QK00/F7C05B0E5D6D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2BF8839D12>) |
| 168c:002a | 168c:3099 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 1     | ath        | [7623C94BA1](<Mini Pc/AMI/Aptio/Aptio CRB/2A6D86CEBF47/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/7623C94BA1>) |
| 168c:002b | 103c:3040 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 1     | ath        | [76D7C47FFA](<Mini Pc/AMI/Aptio/Aptio CRB/4FD96BBACDAA/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/76D7C47FFA>) |
| 168c:002b | 105b:e017 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 1     | ath        | [7DDE4D8C3E](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.6/13.0-STABLE/AMD64/7DDE4D8C3E>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 1     | ath        | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 1814:3090 | 1814:3090 | Ralink           | RT3090 Wireless 802.11n 1T/1R PCIe   | 1     | ral        | [448AB4ED58](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/448AB4ED58>) |
| 8086:02f0 | 8086:0264 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:02f0 | 8086:02a4 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 1     | iwlwifi    | [4C3BE7EC24](<Mini Pc/ZOTAC/ZBOX-CI622/ZBOX-CI622-CI642-CI662NANO/6C326764845F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4C3BE7EC24>) |
| 8086:0885 | 8086:1305 | Intel            | Centrino Wireless-N 6150             | 1     | iwn        | [7AAAAFCB77](<Mini Pc/AMI/Aptio/Aptio CRB/D0E7A6A12AB4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/7AAAAFCB77>) |
| 8086:0887 | 8086:4062 | Intel            | Centrino Wireless-N 2230             | 1     | iwn        | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:0892 | 8086:0062 | Intel            | Centrino Wireless-N 135              | 1     | iwn        | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 151   | re         | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 105   | igb        | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 10    | bge        | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 8086:15a3 | 8086:2057 | Intel            | Ethernet Connection (3) I218-V       | 10    | em         | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 10ec:8168 | 8086:2072 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 9     | re         | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:157b |           | Intel            | I210 Gigabit Network Connection      | 9     | igb        | [3F2F69321D](<Mini Pc/AMI/Aptio/Aptio CRB/475AD142906A/OPNSENSE-22.1.9/13.0-STABLE/AMD64/3F2F69321D>) |
| 10ec:8168 | 8086:2060 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | re         | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:1570 | 8086:2063 | Intel            | Ethernet Connection I219-V           | 6     | em         | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 3     | em         | [AC69A3ECEF](<Mini Pc/Stonesoft/1065/1065-1-C1/557CA49C63A4/OPNSENSE-22.7/13.1-RELEASE/AMD64/AC69A3ECEF>) |
| 8086:150e | 1734:11a8 | Intel            | 82580 Gigabit Network Connection     | 3     | igb        | [0A90B33AC1](<Mini Pc/Supermicro/A1/A1SAi/CCD1655E1820/FREEBSD-12.3-P4/12.3-RELEASE-P3/AMD64/0A90B33AC1>) |
| 8086:150e | 8086:12a2 | Intel            | 82580 Gigabit Network Connection     | 3     | igb        | [F187229469](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/B08F81A68A52/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/F187229469>) |
| 8086:105e | 8086:115e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 2     | em         | [97BF732BFE](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/C547B0AEDFE8/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/97BF732BFE>) |
| 8086:1521 | 8086:0002 | Intel            | I350 Gigabit Network Connection      | 2     | igb        | [A7C2E16F5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S3X100/D56992CB6612/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/A7C2E16F5C>) |
| 8086:156f | 8086:2070 | Intel            | Ethernet Connection I219-LM          | 2     | em         | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:15b7 |           | Intel            | Ethernet Connection (2) I219-LM      | 2     | em         | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 10ec:3000 | 1a56:3000 | Realtek Semic... | Killer E3000 2.5GbE Controller       | 1     |            | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [55C7D22C4D](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/957721D5B2BA/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/55C7D22C4D>) |
| 1425:0000 | 1014:03e5 | Chelsio Commu... |                                      | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1425:4102 | 1014:03e5 | Chelsio Commu... |                                      | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 14e4:1657 | 14e4:1904 | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 1     | bge        | [2BF8839D12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S1QK00/F7C05B0E5D6D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2BF8839D12>) |
| 15b3:1003 | 15b3:0050 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 1     | mlx4_core  | [0585732860](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/F0BCA0A99F84/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/0585732860>) |
| 15b3:6750 | 15b3:0015 | Mellanox Tech... | MT26448 [ConnectX EN 10GigE, PCIe... | 1     | mlx4_core  | [CF9CB3DFCF](<Mini Pc/Supermicro/A1/A1SAi/EF132EE4A24F/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/CF9CB3DFCF>) |
| 8086:105e | 103c:7044 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 1     | em         | [EF3E506A31](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/341C876B1CAB/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/EF3E506A31>) |
| 8086:105e | 8086:135e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 1     | em         | [DE20688262](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/270583FFA387/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/DE20688262>) |
| 8086:155a |           | Intel            | Ethernet Connection I218-LM          | 1     | em         | [39EE26926C](<Mini Pc/CompuLab/Intense-PC/Intense-PC2/084450D07AD2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/39EE26926C>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 38    | sdhci_pci  | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 23    | sdhci_pci  | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31cc | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    | sdhci_pci  | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:31d0 | 8086:7270 | Intel            | SD Host Controller                   | 18    | sdhci_pci  | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 14e4:16bc |           | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 17    | sdhci_pci  | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | sdhci_pci  | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 8086:5acc | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | sdhci_pci  | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 8     | sdhci_pci  | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:31cc | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 8     | sdhci_pci  | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 8     | sdhci_pci  | [EBEDB51D2F](<Mini Pc/CompuLab/fitlet/fitlet2/66D2086CBC5D/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/EBEDB51D2F>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | sdhci_pci  | [EBEDB51D2F](<Mini Pc/CompuLab/fitlet/fitlet2/66D2086CBC5D/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/EBEDB51D2F>) |
| 8086:2294 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | sdhci_pci  | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | sdhci_pci  | [6DFF6EC466](<Mini Pc/AMI/Aptio/Aptio CRB/42AC88DC5C6B/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/6DFF6EC466>) |
| 8086:2296 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     | sdhci_pci  | [70CC64BA78](<Mini Pc/AWOW/AK34/AK34Pro/202622C98BCE/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/70CC64BA78>) |
| 8086:9d2d | 8086:2063 | Intel            | Sunrise Point-LP Secure Digital I... | 3     | sdhci_pci  | [95646C7B48](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-502/E9BA54037A28/NOMADBSD-5806F915/13.0-RELEASE/AMD64/95646C7B48>) |
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 1022:7813 | 1022:7813 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [9772776314](<Mini Pc/CompuLab/fitlet/fitlet/4295E727D46A/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/9772776314>) |
| 1217:8621 | 8086:2073 | O2 Micro         | SD/MMC Card Reader Controller        | 2     | sdhci_pci  | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 2     | sdhci_pci  | [8956B895AB](<Mini Pc/Sophos/XG/XG/E8FA600ACE09/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/8956B895AB>) |
| 1217:8620 | 1217:0002 | O2 Micro         | BayHubTech/O2Micro Integrated MMC... | 1     | sdhci_pci  | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1217:8621 | 8086:2064 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 17a0:9755 | 8086:3004 | Genesys Logic    | GL9755 SD Host Controller            | 1     | sdhci_pci  | [81E9F8506F](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/523FF1AAC143/FREEBSD-13.1/13.1-RELEASE/AMD64/81E9F8506F>) |
| 8086:06f5 | 19da:b429 | Intel            | 400 Series Chipset Family SD Host... | 1     | sdhci_pci  | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:2294 | 1462:b120 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [AA27C1DFD0](<Mini Pc/MSI/MS-B/MS-B120/07E1FDD9727B/FREEBSD-13.1/13.1-RELEASE/AMD64/AA27C1DFD0>) |
| 8086:2294 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [2C106472CB](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-107/ACD48A55CB15/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/2C106472CB>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [96C3B75436](<Mini Pc/AMI/Aptio/Aptio CRB/EC4A43EE54F9/OPNSENSE-22.1.8/13.0-STABLE/AMD64/96C3B75436>) |
| 8086:31cc | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [75EE70A8CD](<Mini Pc/BESSTAR Tech/GK/GK41/6643A2716B62/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/75EE70A8CD>) |
| 8086:31cc | 1297:3008 | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [A537BCD507](<Mini Pc/Standard/SFFGL/SFFGL Series/94EE2C55ADBB/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/A537BCD507>) |
| 8086:31d0 | 10ec:119e | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [75EE70A8CD](<Mini Pc/BESSTAR Tech/GK/GK41/6643A2716B62/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/75EE70A8CD>) |
| 8086:4dc4 |           | Intel            | Jasper Lake SCS1: eMMC Controller    | 1     | sdhci_pci  | [353C3D5CEE](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/CCFFCDBA4F23/FREEBSD-13.1/13.1-RELEASE/AMD64/353C3D5CEE>) |
| 8086:4dc4 | 8086:3027 | Intel            | Jasper Lake SCS1: eMMC Controller    | 1     | sdhci_pci  | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:4df8 |           | Intel            | SD Host Controller                   | 1     | sdhci_pci  | [353C3D5CEE](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/CCFFCDBA4F23/FREEBSD-13.1/13.1-RELEASE/AMD64/353C3D5CEE>) |
| 8086:5aca | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:5aca | 8086:5aca | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [C597FB4337](<Mini Pc/EXTRA Computer/exone/exone Business 5501/8D2CC3B43BC9/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C597FB4337>) |
| 8086:5acc | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:5acc | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [534AF14A9F](<Mini Pc/Intel/NUC6/NUC6CAYS/A0827AC985C4/OPNSENSE-22.1.5/13.0-STABLE/AMD64/534AF14A9F>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [C597FB4337](<Mini Pc/EXTRA Computer/exone/exone Business 5501/8D2CC3B43BC9/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C597FB4337>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 14    |            | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 14    |            | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:a324 | 17aa:312d | Intel            | Cannon Lake PCH SPI Controller       | 13    |            | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:02a4 | 8086:2081 | Intel            | Comet Lake SPI (flash) Controller    | 8     |            | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:02e8 | 8086:2081 | Intel            | Serial IO I2C Host Controller        | 8     | ig4iic     | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:02ea | 8086:2081 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 8     | ig4iic     | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:5ac8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     |            | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:9da4 | 17aa:314d | Intel            | Cannon Point-LP SPI Controller       | 6     |            | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 8086:a324 | 17aa:3136 | Intel            | Cannon Lake PCH SPI Controller       | 5     |            | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 10ec:816c | 1043:85b5 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:a324 | 8086:2089 | Intel            | Cannon Lake PCH SPI Controller       | 4     |            | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:a368 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 4     | ig4iic     | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:a369 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 4     | ig4iic     | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:22c6 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | ig4iic     | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:22c7 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | ig4iic     | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:06a4 | 17aa:3172 | Intel            | Comet Lake PCH SPI Controller        | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 10de:1ad9 | 19da:7529 | Nvidia           | TU104 USB Type-C UCSI Controller     | 1     |            | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 10de:1adb | 8086:2090 | Nvidia           | TU106 USB Type-C UCSI Controller     | 1     |            | [7C34BE7C2E](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/9D3A033CEC7D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7C34BE7C2E>) |
| 10ec:816c | 103c:8522 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [CAE055641A](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/CAE055641A>) |
| 10ec:816c | 103c:8523 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1425:4602 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Storage Cont... | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 8086:02a4 | 19da:b418 | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [4C3BE7EC24](<Mini Pc/ZOTAC/ZBOX-CI622/ZBOX-CI622-CI642-CI662NANO/6C326764845F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4C3BE7EC24>) |
| 8086:02a4 | 19da:b426 | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:06a4 | 17aa:316a | Intel            | Comet Lake PCH SPI Controller        | 1     |            | [26C9557A0A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90q 11DGS11W00/D40AF8580548/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/26C9557A0A>) |
| 8086:06a4 | 17aa:316e | Intel            | Comet Lake PCH SPI Controller        | 1     |            | [2A7C8F55CB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUSBYK00/4E36DF922C91/FREEBSD-13.1/13.1-RELEASE/AMD64/2A7C8F55CB>) |
| 8086:06a4 | 19da:b429 | Intel            | Comet Lake PCH SPI Controller        | 1     |            | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:06e8 | 19da:b429 | Intel            | Comet Lake PCH Serial IO I2C Cont... | 1     | ig4iic     | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:06e9 | 19da:b429 | Intel            | Comet Lake PCH Serial IO I2C Cont... | 1     | ig4iic     | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 1     |            | [9E304DE7AD](<Mini Pc/Chuwi/CoreBox/CoreBox Pro/24BC2F453B95/OPNSENSE-22.7/13.1-RELEASE/AMD64/9E304DE7AD>) |
| 8086:34ab | 8086:7270 | Intel            | Ice Lake-LP Serial IO SPI Control... | 1     |            | [9E304DE7AD](<Mini Pc/Chuwi/CoreBox/CoreBox Pro/24BC2F453B95/OPNSENSE-22.7/13.1-RELEASE/AMD64/9E304DE7AD>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 1     |            | [9E304DE7AD](<Mini Pc/Chuwi/CoreBox/CoreBox Pro/24BC2F453B95/OPNSENSE-22.7/13.1-RELEASE/AMD64/9E304DE7AD>) |
| 8086:4da4 |           | Intel            | Jasper Lake SPI Controller           | 1     |            | [353C3D5CEE](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/CCFFCDBA4F23/FREEBSD-13.1/13.1-RELEASE/AMD64/353C3D5CEE>) |
| 8086:4da4 | 19da:b437 | Intel            | Jasper Lake SPI Controller           | 1     |            | [467D85355C](<Mini Pc/ZOTAC/ZBOX-CI331/ZBOX-CI331NANO/63CE16232598/OPNSENSE-22.1.8/13.0-STABLE/AMD64/467D85355C>) |
| 8086:4da4 | 8086:3027 | Intel            | Jasper Lake SPI Controller           | 1     |            | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:4dab |           | Intel            | Jasper Lake LPSS: SPI Controller #1  | 1     |            | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:4dab | 19da:b437 | Intel            | Jasper Lake LPSS: SPI Controller #1  | 1     |            | [467D85355C](<Mini Pc/ZOTAC/ZBOX-CI331/ZBOX-CI331NANO/63CE16232598/OPNSENSE-22.1.8/13.0-STABLE/AMD64/467D85355C>) |
| 8086:4dc5 | 19da:b437 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 1     |            | [467D85355C](<Mini Pc/ZOTAC/ZBOX-CI331/ZBOX-CI331NANO/63CE16232598/OPNSENSE-22.1.8/13.0-STABLE/AMD64/467D85355C>) |
| 8086:4dc5 | 8086:3027 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 1     |            | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:4dc6 | 19da:b437 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 1     |            | [467D85355C](<Mini Pc/ZOTAC/ZBOX-CI331/ZBOX-CI331NANO/63CE16232598/OPNSENSE-22.1.8/13.0-STABLE/AMD64/467D85355C>) |
| 8086:4dc6 | 8086:3027 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 1     |            | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:4de8 | 19da:b437 | Intel            | Serial IO I2C Host Controller        | 1     |            | [467D85355C](<Mini Pc/ZOTAC/ZBOX-CI331/ZBOX-CI331NANO/63CE16232598/OPNSENSE-22.1.8/13.0-STABLE/AMD64/467D85355C>) |
| 8086:4de8 | 8086:3027 | Intel            | Serial IO I2C Host Controller        | 1     |            | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:4dea | 19da:b437 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 1     |            | [467D85355C](<Mini Pc/ZOTAC/ZBOX-CI331/ZBOX-CI331NANO/63CE16232598/OPNSENSE-22.1.8/13.0-STABLE/AMD64/467D85355C>) |
| 8086:4dea | 8086:3027 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 1     |            | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:9de8 | 17aa:314d | Intel            | Cannon Point-LP Serial IO I2C Con... | 1     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:a0a4 | 17aa:319e | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [33545A5181](<Mini Pc/Lenovo/ThinkEdge/ThinkEdge SE30 11NA0005UK/1A1BE0BDD989/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/33545A5181>) |
| 8086:a0a4 | 8086:2090 | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [7C34BE7C2E](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/9D3A033CEC7D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7C34BE7C2E>) |
| 8086:a0a4 | 8086:3004 | Intel            | Tiger Lake-LP SPI Controller         | 1     |            | [81E9F8506F](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/523FF1AAC143/FREEBSD-13.1/13.1-RELEASE/AMD64/81E9F8506F>) |
| 8086:a0e8 | 8086:2090 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | ig4iic     | [7C34BE7C2E](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/9D3A033CEC7D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7C34BE7C2E>) |
| 8086:a0e8 | 8086:3004 | Intel            | Tiger Lake-LP Serial IO I2C Contr... | 1     | ig4iic     | [81E9F8506F](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/523FF1AAC143/FREEBSD-13.1/13.1-RELEASE/AMD64/81E9F8506F>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 31    |            | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 26    |            | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31ac | 8086:31ac | Intel            | Celeron/Pentium Silver Processor ... | 25    | ig4iic     | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31b2 | 8086:31b2 | Intel            | Celeron/Pentium Silver Processor ... | 25    | ig4iic     | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31b4 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    | ig4iic     | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:31ba | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    | ig4iic     | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 22    | ig4iic     | [D2D5364C96](<Mini Pc/AWOW/AK/AK34/6974B663417D/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D2D5364C96>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 22    | ig4iic     | [D2D5364C96](<Mini Pc/AWOW/AK/AK34/6974B663417D/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D2D5364C96>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 21    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 20    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 19    | uart       | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 19    | uart       | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 19    | uart       | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 19    | uart       | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    | ig4iic     | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    | ig4iic     | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    | ig4iic     | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    | ig4iic     | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    | ig4iic     | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    | ig4iic     | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:9df9 | 8086:2074 | Intel            | Cannon Point-LP Thermal Controller   | 14    | pchtherm   | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:9d31 | 8086:2068 | Intel            | Sunrise Point-LP Thermal subsystem   | 11    | pchtherm   | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 10    | pchtherm   | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:02f9 | 8086:2081 | Intel            | Comet Lake Thermal Subsytem          | 8     | pchtherm   | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:1903 | 17aa:314d | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 6     |            | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 8086:318c | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 6     |            | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 8086:5abc |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | uart       | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:5ac4 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     |            | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:5ac6 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     |            | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:9d27 | 8086:2063 | Intel            | Sunrise Point-LP Serial IO UART C... | 6     |            | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:9d31 | 8086:2063 | Intel            | Sunrise Point-LP Thermal subsystem   | 6     | pchtherm   | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:9df9 | 17aa:314d | Intel            | Cannon Point-LP Thermal Controller   | 6     | pchtherm   | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 1022:15e4 | 1022:15e4 | AMD              | Sensor Fusion Hub                    | 5     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 5     | ig4iic     | [70CC64BA78](<Mini Pc/AWOW/AK34/AK34Pro/202622C98BCE/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/70CC64BA78>) |
| 8086:5aac | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | ig4iic     | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:5ac2 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     |            | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:a2b1 | 103c:829a | Intel            | 200 Series PCH Thermal Subsystem     | 5     |            | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 8086:a379 | 8086:2089 | Intel            | Cannon Lake PCH Thermal Controller   | 4     | pchtherm   | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:06f9 | 17aa:3172 | Intel            | Comet Lake PCH Thermal Controller    | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:1903 | 17aa:3172 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:31ae | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [2DD1C94C37](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/D16A6E21B765/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2DD1C94C37>) |
| 8086:31b0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [2DD1C94C37](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/D16A6E21B765/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2DD1C94C37>) |
| 8086:31b2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [2DD1C94C37](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/D16A6E21B765/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2DD1C94C37>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [2DD1C94C37](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/D16A6E21B765/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2DD1C94C37>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [2DD1C94C37](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/D16A6E21B765/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2DD1C94C37>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [2DD1C94C37](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/D16A6E21B765/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2DD1C94C37>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [2DD1C94C37](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/D16A6E21B765/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2DD1C94C37>) |
| 8086:9d31 | 8086:2070 | Intel            | Sunrise Point-LP Thermal subsystem   | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 92    | ichsmb     | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | ichsmb     | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 1022:780b | 103c:8103 | AMD              | FCH SMBus Controller                 | 38    | intsmb     | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 30    | ichsmb     | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 25    | ichsmb     | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 24    | ichsmb     | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 22    | ichsmb     | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:31d4 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    | ichsmb     | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 21    | ichsmb     | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:9da3 | 8086:2074 | Intel            | Cannon Point-LP SMBus Controller     | 14    |            | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:2292 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | ichsmb     | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
| 8086:5ad4 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    |            | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 8086:a323 | 17aa:312d | Intel            | Cannon Lake PCH SMBus Controller     | 13    | ichsmb     | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:9d23 | 8086:2068 | Intel            | Sunrise Point-LP SMBus               | 11    | ichsmb     | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:9ca2 | 8086:2057 | Intel            | Wildcat Point-LP SMBus Controller    | 10    | ichsmb     | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 10    | ichsmb     | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:31d4 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 9     | ichsmb     | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:02a3 | 8086:2081 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 8     | ichsmb     | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | ichsmb     | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:2292 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | ichsmb     | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 7     | ichsmb     | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 6     | intsmb     | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:31d4 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 6     | ichsmb     | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 8086:9d23 | 8086:2063 | Intel            | Sunrise Point-LP SMBus               | 6     | ichsmb     | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:9da3 | 17aa:314d | Intel            | Cannon Point-LP SMBus Controller     | 6     |            | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 1002:4385 | 103c:17e2 | AMD              | SBx00 SMBus Controller               | 5     | intsmb     | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 1022:790b | 1043:87e7 | AMD              | FCH SMBus Controller                 | 5     | intsmb     | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:5ad4 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     |            | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:a2a3 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family SM... | 5     | ichsmb     | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 8086:a323 | 17aa:3136 | Intel            | Cannon Lake PCH SMBus Controller     | 5     | ichsmb     | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 8086:a323 | 8086:2089 | Intel            | Cannon Lake PCH SMBus Controller     | 4     | ichsmb     | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:0f12 | 1071:0730 | Intel            | Atom Processor E3800/CE2700 Serie... | 3     | ichsmb     | [294F283D65](<Mini Pc/AMI/Aptio/Aptio CRB/293083C7BA4B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/294F283D65>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 3     | ichsmb     | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 10de:0d79 | 10de:cb89 | Nvidia           | MCP89 SMBus                          | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 8086:06a3 | 17aa:3172 | Intel            | Comet Lake PCH SMBus Controller      | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:2292 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | ichsmb     | [8B634987B4](<Mini Pc/Shuttle/XS35/XS35V5/4F433C551703/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/8B634987B4>) |
| 8086:2330 | 8086:2330 | Intel            | DH89xxCC SMBus Controller            | 2     | ichsmb     | [1EAA616342](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1EAA616342>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 2     | ichsmb     | [0D6E868D9C](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0D6E868D9C>) |
| 8086:9d23 | 8086:2070 | Intel            | Sunrise Point-LP SMBus               | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a123 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | ichsmb     | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 8086:a2a3 | 17aa:310b | Intel            | 200 Series/Z370 Chipset Family SM... | 2     | ichsmb     | [E0F08B66C2](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MV000NUS/1C0874D9DEC1/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/E0F08B66C2>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 1     | intsmb     | [34DD85F78D](<Mini Pc/CompuLab/fit-PC/fit-PC3/F6EE642348DC/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/34DD85F78D>) |
| 1022:780b | 19da:b208 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 1022:790b | 103c:8158 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [DE45E5A021](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/766906F5D7C3/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/DE45E5A021>) |
| 1022:790b | 103c:8522 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:790b | 103c:8523 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:790b | 17aa:3190 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1022:790b | 1854:0309 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 8086:02a3 | 19da:b418 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 1     | ichsmb     | [4C3BE7EC24](<Mini Pc/ZOTAC/ZBOX-CI622/ZBOX-CI622-CI642-CI662NANO/6C326764845F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4C3BE7EC24>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 58    | hdac       | [64C549F3AE](<Mini Pc/AMI/Aptio/Aptio CRB/A3DBD4D871FE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/64C549F3AE>) |
| 8086:5a98 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 44    | hdac       | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 1002:1308 | 103c:8103 | AMD              | Kaveri HDMI/DP Audio Controller      | 38    | hdac       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:780d | 103c:8103 | AMD              | FCH Azalia Controller                | 30    | hdac       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 28    | hdac       | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 25    | hdac       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:3198 | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 25    | hdac       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    | hdac       | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:3198 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 15    | hdac       | [29B3E0B639](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/C597086BD3D1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/29B3E0B639>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 14    | hdac       | [ABCEADC2E3](<Mini Pc/CompuLab/fitlet/fitlet2/D5B693ADF911/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/ABCEADC2E3>) |
| 8086:2284 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | hdac       | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
| 8086:9dc8 | 8086:2074 | Intel            | Cannon Point-LP High Definition A... | 11    | hdac       | [17F444775B](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/9A43951EB263/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/17F444775B>) |
| 8086:a348 | 17aa:312d | Intel            | Cannon Lake PCH cAVS                 | 10    | hdac       | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:3198 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 9     | hdac       | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:160c | 8086:2057 | Intel            | Broadwell-U Audio Controller         | 8     | hdac       | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | hdac       | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:9ca0 | 8086:2057 | Intel            | Wildcat Point-LP High Definition ... | 8     | hdac       | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:9d71 | 8086:2068 | Intel            | Sunrise Point-LP HD Audio            | 8     | hdac       | [66F9B621BE](<Mini Pc/Intel/NUC7/NUC7i5BNK/DB7E10F2F9E0/FREEBSD-13.1/13.1-RELEASE/AMD64/66F9B621BE>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 7     | hdac       | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:2284 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | hdac       | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:3198 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 6     | hdac       | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 6     | hdac       | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 1002:1314 | 103c:17e2 | AMD              | Wrestler HDMI Audio                  | 5     | hdac       | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 5     | hdac       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1002:4383 | 103c:17e2 | AMD              | SBx00 Azalia (Intel HDA)             | 5     | hdac       | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 1002:9840 | 1002:9840 | AMD              | Kabini HDMI/DP Audio                 | 5     | hdac       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:02c8 | 8086:2081 | Intel            | Comet Lake PCH-LP cAVS               | 5     | hdac       | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:0a0c | 106b:0141 | Intel            | Haswell-ULT HD Audio Controller      | 5     | hdac       | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 8086:9dc8 | 17aa:314d | Intel            | Cannon Point-LP High Definition A... | 5     | hdac       | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 8086:a2f0 | 103c:829a | Intel            | 200 Series PCH HD Audio              | 5     | hdac       | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 8086:a348 | 17aa:3136 | Intel            | Cannon Lake PCH cAVS                 | 5     | hdac       | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 1022:15e3 | 1043:87bc | AMD              | Family 17h/19h HD Audio Controller   | 4     | hdac       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:780d | 1022:780d | AMD              | FCH Azalia Controller                | 4     | hdac       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:5a98 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | hdac       | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:a348 | 8086:2089 | Intel            | Cannon Lake PCH cAVS                 | 4     | hdac       | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 3     | hdac       | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 3     | hdac       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:0f04 | 1071:0730 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     | hdac       | [294F283D65](<Mini Pc/AMI/Aptio/Aptio CRB/293083C7BA4B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/294F283D65>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 3     | hdac       | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:9d70 | 8086:2063 | Intel            | Sunrise Point-LP HD Audio            | 3     | hdac       | [95646C7B48](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-502/E9BA54037A28/NOMADBSD-5806F915/13.0-RELEASE/AMD64/95646C7B48>) |
| 1002:aa90 | 0000:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 2     | hdac       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 1002:ab08 | 8086:2073 | AMD              | Polaris 22 HDMI Audio                | 2     | hdac       | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 10de:0d94 | 10de:cb89 | Nvidia           | MCP89 High Definition Audio          | 2     | hdac       | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 8086:160c | 19da:b246 | Intel            | Broadwell-U Audio Controller         | 2     | hdac       | [0D6E868D9C](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0D6E868D9C>) |
| 8086:3198 | 10ec:115a | Intel            | Celeron/Pentium Silver Processor ... | 2     | hdac       | [70CC64BA78](<Mini Pc/AWOW/AK34/AK34Pro/202622C98BCE/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/70CC64BA78>) |
| 8086:9ca0 | 8086:7270 | Intel            | Wildcat Point-LP High Definition ... | 2     | hdac       | [0D6E868D9C](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0D6E868D9C>) |
| 8086:9d71 | 8086:2070 | Intel            | Sunrise Point-LP HD Audio            | 2     | hdac       | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a171 | 8086:2073 | Intel            | CM238 HD Audio Controller            | 2     | hdac       | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 1002:1314 | 1002:1314 | AMD              | Wrestler HDMI Audio                  | 1     | hdac       | [34DD85F78D](<Mini Pc/CompuLab/fit-PC/fit-PC3/F6EE642348DC/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/34DD85F78D>) |
| 1002:1637 | 17aa:3190 | AMD              | Renoir Radeon High Definition Aud... | 1     | hdac       | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 89    | ahci       | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | ahci       | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 1022:7801 | 103c:8103 | AMD              | FCH SATA Controller [AHCI mode]      | 37    | ahci       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 30    | ahci       | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 25    | ahci       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 23    | ahci       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 22    | ahci       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:1f22 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA2 C... | 22    | ahci       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:31e3 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    | ahci       | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 21    | ahci       | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:22a3 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | ahci       | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
| 8086:5ae3 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | ahci       | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 8086:a352 | 17aa:312d | Intel            | Cannon Lake PCH SATA AHCI Controller | 13    | ahci       | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:9d03 | 8086:2068 | Intel            | Sunrise Point-LP SATA Controller ... | 11    | ahci       | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:9dd3 | 8086:2074 | Intel            | Cannon Point-LP SATA Controller [... | 11    | ahci       | [17F444775B](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/9A43951EB263/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/17F444775B>) |
| 8086:9c83 | 8086:2057 | Intel            | Wildcat Point-LP SATA Controller ... | 10    | ahci       | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 10    | ahci       | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:31e3 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 9     | ahci       | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:1c03 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | ahci       | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:22a3 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | ahci       | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 7     | ahci       | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 1022:7801 | 1022:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 5     | ahci       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 1022:7901 | 1043:87e7 | AMD              | FCH SATA Controller [AHCI mode]      | 5     | ahci       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:02d3 | 8086:2081 | Intel            | Comet Lake SATA AHCI Controller      | 5     | ahci       | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:31e3 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 5     | ahci       | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 8086:5ae3 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | ahci       | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:9d03 | 8086:2063 | Intel            | Sunrise Point-LP SATA Controller ... | 5     | ahci       | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:a282 | 103c:829a | Intel            | 200 Series PCH SATA controller [A... | 5     | ahci       | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 8086:a352 | 17aa:3136 | Intel            | Cannon Lake PCH SATA AHCI Controller | 5     | ahci       | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 1b4b:9215 | 1b4b:9215 | Marvell Techn... | 88SE9215 PCIe 2.0 x1 4-port SATA ... | 4     | ahci       | [6DFF6EC466](<Mini Pc/AMI/Aptio/Aptio CRB/42AC88DC5C6B/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/6DFF6EC466>) |
| 8086:a353 | 8086:2089 | Intel            | Cannon Lake Mobile PCH SATA AHCI ... | 4     | ahci       | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 3     | ahci       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:0f23 | 1071:0730 | Intel            | Atom Processor E3800 Series SATA ... | 3     | ahci       | [294F283D65](<Mini Pc/AMI/Aptio/Aptio CRB/293083C7BA4B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/294F283D65>) |
| 1002:4391 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 2     | ahci       | [AC74E1CC65](<Mini Pc/Hewlett-Packard/t610/t610 PLUS WW Thin Client/0FF0229E7C0B/OPNSENSE-22.1/13.0-STABLE/AMD64/AC74E1CC65>) |
| 10de:0d88 | 106b:cb89 | Nvidia           | MCP89 SATA Controller (AHCI mode)    | 2     | ahci       | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 8086:06d2 | 17aa:3172 | Intel            | Comet Lake SATA AHCI Controller      | 2     | ahci       | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:1e03 | 8086:7270 | Intel            | 7 Series Chipset Family 6-port SA... | 2     | ahci       | [AC585B4E0D](<Mini Pc/Apple/Macmini6/Macmini6,2/FAC8616568BC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/AC585B4E0D>) |
| 8086:22a3 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | ahci       | [8B634987B4](<Mini Pc/Shuttle/XS35/XS35V5/4F433C551703/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/8B634987B4>) |
| 8086:2323 | 8086:2321 | Intel            | DH89xxCC 4 Port SATA AHCI Controller | 2     | ahci       | [1EAA616342](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1EAA616342>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 2     | ahci       | [0D6E868D9C](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0D6E868D9C>) |
| 8086:9d03 | 8086:2070 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a282 | 17aa:310b | Intel            | 200 Series PCH SATA controller [A... | 2     | ahci       | [E0F08B66C2](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MV000NUS/1C0874D9DEC1/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/E0F08B66C2>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1     | ahci       | [34DD85F78D](<Mini Pc/CompuLab/fit-PC/fit-PC3/F6EE642348DC/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/34DD85F78D>) |
| 1022:7801 | 19da:b208 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 1022:7901 | 103c:8158 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [DE45E5A021](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/766906F5D7C3/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/DE45E5A021>) |
| 1022:7901 | 103c:8522 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:7901 | 1854:0309 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 1     | ahci       | [B86C21F11A](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/3BC14659C185/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/B86C21F11A>) |
| 8086:02d3 | 19da:b418 | Intel            | Comet Lake SATA AHCI Controller      | 1     | ahci       | [4C3BE7EC24](<Mini Pc/ZOTAC/ZBOX-CI622/ZBOX-CI622-CI642-CI662NANO/6C326764845F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4C3BE7EC24>) |
| 8086:06d2 | 17aa:316a | Intel            | Comet Lake SATA AHCI Controller      | 1     | ahci       | [26C9557A0A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90q 11DGS11W00/D40AF8580548/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/26C9557A0A>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:780c | 103c:8103 | AMD              | FCH IDE Controller                   | 38    | atapci     | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1002:4390 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 3     | ahci       | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 1022:7800 | 103c:8103 | AMD              | FCH SATA Controller [IDE mode]       | 1     | ahci       | [364241899F](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E658728E0DEE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/364241899F>) |
| 8086:0f21 | 8086:0f21 | Intel            | Atom Processor E3800 Series SATA ... | 1     | atapci     | [70AE301A10](<Mini Pc/AMI/Aptio/Aptio CRB/1F89AEBBE669/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/70AE301A10>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 17    | nvme       | [69A9AE7BDE](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS23202/A61F164E4C35/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/69A9AE7BDE>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 9     | nvme       | [E0F08B66C2](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MV000NUS/1C0874D9DEC1/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/E0F08B66C2>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 7     | nvme       | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 5     | nvme       | [2BF8839D12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S1QK00/F7C05B0E5D6D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2BF8839D12>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 4     | nvme       | [CC0380B2C6](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8SSKB00/2C122F875084/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/CC0380B2C6>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 4     | nvme       | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 2     | nvme       | [484E5520B7](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M910q 10MUS0RN00/7B280F856F75/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/484E5520B7>) |
| 15b7:5005 | 15b7:5005 | SanDisk          | PC SN520 NVMe SSD                    | 2     | nvme       | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 2     | nvme       | [A09FBE5FCC](<Mini Pc/Intel Client Systems/NUC10/NUC10i5FNH/1FFBE51038AD/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/A09FBE5FCC>) |
| 8086:0975 | 8086:8410 | Intel            |                                      | 2     | nvme       | [1751DE42DC](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/F8E61E16B1A3/OPNSENSE-22.1.8/13.0-STABLE/AMD64/1751DE42DC>) |
| c0a9:540a | c0a9:5021 | Micron/Crucia... | P2 NVMe PCIe SSD                     | 2     | nvme       | [353C3D5CEE](<Mini Pc/Fanless Mini PC/Quieter/Quieter 3/CCFFCDBA4F23/FREEBSD-13.1/13.1-RELEASE/AMD64/353C3D5CEE>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 2     | nvme       | [59C576A4BA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S9MV00/EF055ED713EB/OPNSENSE-22.1.10/13.0-STABLE/AMD64/59C576A4BA>) |
| 1179:0113 | 1179:0001 | Toshiba          | BG3 NVMe SSD Controller              | 1     | nvme       | [F346B8D7F0](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/E0C236805F04/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F346B8D7F0>) |
| 1344:5405 | 1344:0100 | Micron Techno... |                                      | 1     | nvme       | [92881489E1](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/D36E9B88E82A/FREEBSD-13.1/13.1-RELEASE/AMD64/92881489E1>) |
| 1344:6001 | 1344:0100 | Micron Techno... |                                      | 1     | nvme       | [33545A5181](<Mini Pc/Lenovo/ThinkEdge/ThinkEdge SE30 11NA0005UK/1A1BE0BDD989/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/33545A5181>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 1     | nvme       | [A7C2E16F5C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S3X100/D56992CB6612/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/A7C2E16F5C>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 1     | nvme       | [3502CB3D47](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/1F40335DE972/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3502CB3D47>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 1     | nvme       | [7C34BE7C2E](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/9D3A033CEC7D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7C34BE7C2E>) |
| 15b7:5019 | 15b7:5019 | SanDisk          | unknown                              | 1     | nvme       | [7189B48418](<Mini Pc/Intel Client Systems/NUC10/NUC10i3FNH/2E0BD0D062A7/FREEBSD-13.1/13.1-RELEASE/AMD64/7189B48418>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 1     | nvme       | [99C0387102](<Mini Pc/Hewlett-Packard/260/260 G3 DM/A07056395B55/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/99C0387102>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 1     | nvme       | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 1     | nvme       | [5A0B61AC41](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3102303AC861/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/5A0B61AC41>) |
| 1b85:6018 | 1b85:6018 | OCZ Technolog... | RD400/400A SSD                       | 1     | nvme       | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 1bb1:5012 | 1bb1:5012 | Seagate Techn... | FireCuda 510 SSD                     | 1     | nvme       | [07221FC111](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/1BC2519D6516/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/07221FC111>) |
| 1c5c:1627 | 1c5c:1627 | SK hynix         | hynix unknown                        | 1     | nvme       | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 1     | nvme       | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1     | nvme       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 1cc4:17ab | 1cc4:1007 | Union Memory ... | NVMe 256G SSD device                 | 1     | nvme       | [D15116D2EB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7CTO1WW/2D340AE8DBBC/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/D15116D2EB>) |
| 1d79:2263 | 1d79:2263 | Transcend        |                                      | 1     | nvme       | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 2646:2262 | 2646:2262 | Kingston Tech... | KC2000 NVMe SSD                      | 1     | nvme       | [DBACAA5C65](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/074E7A095987/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/DBACAA5C65>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 1     | nvme       | [CCC091CDC9](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/F06FF3B14557/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/CCC091CDC9>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 1     | nvme       | [9E304DE7AD](<Mini Pc/Chuwi/CoreBox/CoreBox Pro/24BC2F453B95/OPNSENSE-22.7/13.1-RELEASE/AMD64/9E304DE7AD>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 1     | nvme       | [3DE3724488](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEK/48AE9C026B00/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/3DE3724488>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:282a | 8086:2074 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [1751DE42DC](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/F8E61E16B1A3/OPNSENSE-22.1.8/13.0-STABLE/AMD64/1751DE42DC>) |
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:282a | 8086:2081 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [A15B01E8FA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D6C049FF87E6/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/A15B01E8FA>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1425:4502 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Storage Cont... | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1423 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 38    |            | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:1f15 |           | Intel            | Atom processor C2000 SMBus 2.0       | 24    |            | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:1f16 |           | Intel            | Atom processor C2000 RCEC            | 24    |            | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:3190 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    |            | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:3190 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 18    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:1911 | 8086:2074 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 14    |            | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:1911 | 17aa:312d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 13    |            | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:1911 | 8086:2068 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 11    |            | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 10    |            | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:1911 | 8086:2081 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 8     |            | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:15e8 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 7     |            | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:1911 | 17aa:314d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 8086:3190 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 6     |            | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 5     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 5     |            | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 8086:1911 | 17aa:3136 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 8086:15eb | 8086:2088 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 4     |            | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:1911 | 8086:2089 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 4     |            | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 3     |            | [8CD83326F3](<Mini Pc/Apple/Macmini5/Macmini5,1/FA1265ADE548/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8CD83326F3>) |
| 8086:22c0 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     |            | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:1911 | 17aa:3172 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:1911 | 8086:2070 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:1911 | 8086:2073 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [C84F270FBA](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/C84F270FBA>) |
| 8086:3190 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 2     |            | [E94A3A5A08](<Mini Pc/Intel/NUC7/NUC7CJYH/DC0B2C092D54/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E94A3A5A08>) |
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1     |            | [DE45E5A021](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/766906F5D7C3/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/DE45E5A021>) |
| 1022:15d1 | 103c:8522 | AMD              | Raven/Raven2 IOMMU                   | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15d1 | 103c:8523 | AMD              | Raven/Raven2 IOMMU                   | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:1631 | 17aa:3190 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 8086:1911 | 17aa:3135 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |
| 8086:1911 | 17aa:316a | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [26C9557A0A](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90q 11DGS11W00/D40AF8580548/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/26C9557A0A>) |
| 8086:1911 | 17aa:316e | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [2A7C8F55CB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M70q 11DUSBYK00/4E36DF922C91/FREEBSD-13.1/13.1-RELEASE/AMD64/2A7C8F55CB>) |
| 8086:1911 | 19da:b418 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [4C3BE7EC24](<Mini Pc/ZOTAC/ZBOX-CI622/ZBOX-CI622-CI642-CI662NANO/6C326764845F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4C3BE7EC24>) |
| 8086:1911 | 19da:b426 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:1911 | 19da:b429 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [62AB446B5D](<Mini Pc/ZOTAC/ZBOX-QCM7/ZBOX-QCM7T3000-EN072080S-EN072070S-EN052060C/C3C7681D8B56/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/62AB446B5D>) |
| 8086:1911 | 8086:2064 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 8086:2360 | 0015:4420 | Intel            | DH89xxCC Watchdog Timer              | 1     |            | [AC69A3ECEF](<Mini Pc/Stonesoft/1065/1065-1-C1/557CA49C63A4/OPNSENSE-22.7/13.1-RELEASE/AMD64/AC69A3ECEF>) |
| 8086:2360 | 2000:2814 | Intel            | DH89xxCC Watchdog Timer              | 1     |            | [9C419C5D32](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/9C419C5D32>) |
| 8086:2360 | 4401:2834 | Intel            | DH89xxCC Watchdog Timer              | 1     |            | [E7FE2F3A54](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/E7FE2F3A54>) |
| 8086:2360 | 4401:2870 | Intel            | DH89xxCC Watchdog Timer              | 1     |            | [303D15332F](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/303D15332F>) |
| 8086:2360 | 4401:2874 | Intel            | DH89xxCC Watchdog Timer              | 1     |            | [D50A6FC56E](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.1.9/13.0-STABLE/AMD64/D50A6FC56E>) |
| 8086:2360 | 4401:28b4 | Intel            | DH89xxCC Watchdog Timer              | 1     |            | [0C91327549](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0C91327549>) |
| 8086:2360 | 4508:48f0 | Intel            | DH89xxCC Watchdog Timer              | 1     |            | [6F087682A4](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/6F087682A4>) |
| 8086:2360 | 4522:a834 | Intel            | DH89xxCC Watchdog Timer              | 1     |            | [1EAA616342](<Mini Pc/Stonesoft/1035/1035-1-C1/C3FCB4EC4FB7/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1EAA616342>) |
| 8086:4e11 | 19da:b437 | Intel            |                                      | 1     |            | [467D85355C](<Mini Pc/ZOTAC/ZBOX-CI331/ZBOX-CI331NANO/63CE16232598/OPNSENSE-22.1.8/13.0-STABLE/AMD64/467D85355C>) |
| 8086:4e11 | 8086:3027 | Intel            |                                      | 1     |            | [6FE2BA74B7](<Mini Pc/Intel Client Systems/NUC11/NUC11ATKC4/ADA450EF27A0/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6FE2BA74B7>) |
| 8086:8a17 |           | Intel            | Ice Lake Thunderbolt 3 NHI #0        | 1     |            | [9E304DE7AD](<Mini Pc/Chuwi/CoreBox/CoreBox Pro/24BC2F453B95/OPNSENSE-22.7/13.1-RELEASE/AMD64/9E304DE7AD>) |
| 8086:9a11 | 8086:2090 | Intel            | GNA Scoring Accelerator module       | 1     |            | [7C34BE7C2E](<Mini Pc/Intel Client Systems/NUC11/NUC11PHi7/9D3A033CEC7D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7C34BE7C2E>) |
| 8086:9a11 | 8086:3004 | Intel            | GNA Scoring Accelerator module       | 1     |            | [81E9F8506F](<Mini Pc/Intel Client Systems/NUC11/NUC11PAHi5/523FF1AAC143/FREEBSD-13.1/13.1-RELEASE/AMD64/81E9F8506F>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 77    | xhci       | [7B36D32911](<Mini Pc/AMI/Aptio/Aptio CRB/032FDEA67E2A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7B36D32911>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 50    | xhci       | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:0f34 | 8086:0f34 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 42    | ehci       | [D3B1E89901](<Mini Pc/Sophos/SG/SG/2DF7928DB45B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3B1E89901>) |
| 1022:7807 | 103c:8103 | AMD              | FCH USB OHCI Controller              | 38    | ohci       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:7808 | 103c:8103 | AMD              | FCH USB EHCI Controller              | 38    | ehci       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:7814 | 103c:8103 | AMD              | FCH USB XHCI Controller              | 38    | xhci       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 31    | xhci       | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 8086:31a8 | 8086:31a8 | Intel            | Celeron/Pentium Silver Processor ... | 25    | xhci       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 24    | ehci       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 1912:0014 | 15d9:0813 | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 23    | xhci       | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 8086:31a8 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    | xhci       | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:0f35 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 21    | xhci       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 21    | xhci       | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:9ded | 8086:2074 | Intel            | Cannon Point-LP USB 3.1 xHCI Cont... | 14    | xhci       | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:22b5 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | xhci       | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
| 8086:5aa8 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | xhci       | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 8086:a36d | 17aa:312d | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 13    | xhci       | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:0f34 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | ehci       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 1b21:2142 | 1b21:2142 | ASMedia Techn... | ASM2142/ASM3142 USB 3.1 Host Cont... | 11    | xhci       | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:9d2f | 8086:2068 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 11    | xhci       | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:9ca6 | 8086:2057 | Intel            | Wildcat Point-LP USB EHCI Controller | 10    | ehci       | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:9cb1 | 8086:2057 | Intel            | Wildcat Point-LP USB xHCI Controller | 10    | xhci       | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 10    | xhci       | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:31a8 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 9     | xhci       | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:02ed | 8086:2081 | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 8     | xhci       | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:15e9 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 8     | xhci       | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | ehci       | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | uhci       | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | uhci       | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | ehci       | [B164BFCF33](<Mini Pc/Apple/Macmini5/Macmini5,3/6CA2A92EF19F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/B164BFCF33>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 7     | xhci       | [2FE9B1B8C9](<Mini Pc/Apple/Macmini7/Macmini7,1/405606998304/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2FE9B1B8C9>) |
| 1022:7808 | 1022:7808 | AMD              | FCH USB EHCI Controller              | 6     | ehci       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:31a8 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 6     | xhci       | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 8086:9d2f | 8086:2063 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci       | [C25D3DF4E2](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/8A65695FE5B2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C25D3DF4E2>) |
| 8086:9ded | 17aa:314d | Intel            | Cannon Point-LP USB 3.1 xHCI Cont... | 6     | xhci       | [8CB1F1A8EA](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AES1PA00/6E17CA251085/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8CB1F1A8EA>) |
| 1002:4396 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 5     | ehci       | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 1002:4397 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 5     | ohci       | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 1022:1639 | 1043:87e7 | AMD              | Renoir/Cezanne USB 3.1               | 5     | xhci       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 104c:8241 | 103c:17e2 | Texas Instrum... | TUSB73x0 SuperSpeed USB 3.0 xHCI ... | 5     | xhci       | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 1b21:1142 | 1043:85bf | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 5     | xhci       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:22b5 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | xhci       | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 8086:5aa8 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | xhci       | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:a2af | 103c:829a | Intel            | 200 Series/Z370 Chipset Family US... | 5     | xhci       | [22070DD05C](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/53D20DFD1409/OPNSENSE-22.1.5/13.0-STABLE/AMD64/22070DD05C>) |
| 8086:a36d | 17aa:3136 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 5     | xhci       | [9862C1B507](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS0GL00/C441D51BAD92/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9862C1B507>) |
| 1022:7814 | 1022:7812 | AMD              | FCH USB XHCI Controller              | 4     | xhci       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 10ec:816d | 1043:85b5 | Realtek Semic... | RTL811x EHCI host controller         | 4     | ehci       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:15ec | 8086:2088 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 4     | xhci       | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 8086:a36d | 8086:2089 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 4     | xhci       | [154DAD5874](<Mini Pc/Intel Client Systems/NUC9/NUC9i7QNX/90B9B48D8A4A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/154DAD5874>) |
| 1002:4399 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 3     | ohci       | [15EC4829CE](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/19D10D117729/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/15EC4829CE>) |
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 3     | ohci       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 0000:0000 |           |                  |                                      | 1     |            | [72072168CE](<Mini Pc/CompuLab/fitlet/fitlet/66920ACF1E1D/OPNSENSE-22.1.6/13.0-STABLE/AMD64/72072168CE>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 1     |            | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |

