Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed pciconf reports collected by BSD users at https://bsd-hardware.info.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 14527.

Contents
--------

1. [ About ](#about)
2. [ PCI Devices ](#pci-devices)
   * [ Bluetooth ](#bluetooth-pci)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Input ](#input-pci)
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
   * [ Video ](#video-pci)
   * [ Wireless controller ](#wireless-controller-pci)
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

Top 50 most popular devices in each category.

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bluetooth (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1814:3298 | 103c:18ec | Ralink           | RT3290 Bluetooth                     | 8     |            | [402494618A](<Notebook/Hewlett-Packard/ENVY/ENVY TS m6 Sleekbook/A23261B65D41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/402494618A>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1439 | 1022:1234 | AMD              | Family 16h Processor Functions 5:1   | 428   | pcib       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:1452 |           | AMD              | Family 17h (Models 00h-1fh) PCIe ... | 336   | hostb      | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 1022:156b |           | AMD              | Family 16h (Models 30h-3fh) Host ... | 302   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1580 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 302   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1581 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 302   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1582 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 302   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1583 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 302   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1584 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 302   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1585 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 302   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:780e | 1022:780e | AMD              | FCH LPC Bridge                       | 293   | isab       | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1566 | 1022:1566 | AMD              | Family 16h (Models 30h-3fh) Proce... | 257   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:31f0 |           | Intel            | Gemini Lake Host Bridge              | 251   | hostb      | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:9d13 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 251   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 248   | isab       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:9d14 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 247   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:9d12 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 245   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 1002:4384 |           | AMD              | SBx00 PCI to PCI Bridge              | 240   | pcib       | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |
| 8086:9d10 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 234   | pcib       | [DDF2BCB808](<Desktop/Protectli/FW/FW6/51B65D660F9A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/DDF2BCB808>) |
| 8086:9d11 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 230   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:9d15 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 229   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:31d8 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 227   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 219   | isab       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 218   | pcib       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 217   | hostb      | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 111d:8018 |           | Microsemi / P... | PES12N3A 12-lane 3-Port PCI Expre... | 211   | pcib       | [E975D67484](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E975D67484>) |
| 8086:22ca | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 208   | pcib       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 201   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:31d9 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 200   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 192   | pcib       | [80814C04B6](<Desktop/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/D5B76A2D718E/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/80814C04B6>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 192   | isab       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:0f48 | 8086:0f48 | Intel            | Atom Processor E3800 Series PCI E... | 191   | pcib       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:0f4a | 8086:0f4a | Intel            | Atom Processor E3800 Series PCI E... | 191   | pcib       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:0f4c | 8086:0f4c | Intel            | Atom Processor E3800 Series PCI E... | 189   | pcib       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:0f4e | 8086:0f4e | Intel            | Atom Processor E3800 Series PCI E... | 188   | pcib       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:22cc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 182   | pcib       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 1022:15e8 |           | AMD              | Raven/Raven2 Device 24: Function 0   | 180   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15e9 |           | AMD              | Raven/Raven2 Device 24: Function 1   | 180   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15ea |           | AMD              | Raven/Raven2 Device 24: Function 2   | 180   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15eb |           | AMD              | Raven/Raven2 Device 24: Function 3   | 180   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15ec |           | AMD              | Raven/Raven2 Device 24: Function 4   | 180   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15ed |           | AMD              | Raven/Raven2 Device 24: Function 5   | 180   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15ee |           | AMD              | Raven/Raven2 Device 24: Function 6   | 180   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15ef |           | AMD              | Raven/Raven2 Device 24: Function 7   | 180   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 8086:31d6 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 177   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:22ce | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 173   | pcib       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 172   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:31d7 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 172   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:5904 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 169   | hostb      | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:0f00 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 162   | hostb      | [12AC44CBF7](<Desktop/Others/Others/Others/B6CD8CD35969/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/12AC44CBF7>) |
| 1022:1440 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 160   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5227 | 17aa:2226 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 14    | rtsx       | [10619AC217](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLS5BU00/75926791E302/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/10619AC217>) |
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 13    | rtsx       | [ACA9E2885D](<Mini Pc/Intel/NUC7i3BNB/NUC7i3BNB J22859-307/2278924F334A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/ACA9E2885D>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 13    | rtsx       | [8A2BBA8635](<Notebook/Notebook/NV4/NV4XMB,ME,MZ/7D4BDB21ACF4/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/8A2BBA8635>) |
| 10ec:5227 | 17aa:220e | Realtek Semic... | RTS5227 PCI Express Card Reader      | 12    | rtsx       | [0883806434](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AN007FGE/4DC9DD36405E/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0883806434>) |
| 10ec:522a | 17aa:5062 | Realtek Semic... | RTS522A PCI Express Card Reader      | 12    | rtsx       | [8257D11669](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S0PY04/60067DC63CDD/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/8257D11669>) |
| 10ec:5227 | 17aa:220c | Realtek Semic... | RTS5227 PCI Express Card Reader      | 11    | rtsx       | [7750C38CD0](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ005SUS/DC9FF593E3E2/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/7750C38CD0>) |
| 10ec:522a | 17aa:5053 | Realtek Semic... | RTS522A PCI Express Card Reader      | 10    | rtsx       | [C85F94D574](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FMS3320G/9452E5197178/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/C85F94D574>) |
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 10    | rtsx       | [17F444775B](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/9A43951EB263/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/17F444775B>) |
| 10ec:5227 | 17aa:5034 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 9     | rtsx       | [7708C4BB19](<Notebook/Lenovo/ThinkPad/ThinkPad T450s 20BXCTO1WW/C49A61555568/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7708C4BB19>) |
| 10ec:5227 | 10cf:187f | Realtek Semic... | RTS5227 PCI Express Card Reader      | 8     | rtsx       | [D2292BBCDA](<Notebook/Fujitsu/CELSIUS/CELSIUS H730/646ECE0C848D/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/D2292BBCDA>) |
| 10ec:5229 | 8086:2072 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx       | [C30DD3FBCA](<Mini Pc/Intel Client Systems/NUC7/NUC7PJYH/CB2E3B8CA357/FREEBSD-13.2-BETA2/13.2-BETA2/AMD64/C30DD3FBCA>) |
| 10ec:522a | 103c:8079 | Realtek Semic... | RTS522A PCI Express Card Reader      | 8     | rtsx       | [92C676E033](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/BA8494C9E0E5/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/92C676E033>) |
| 1217:8520 | 1028:05ca | O2 Micro         | SD/MMC Card Reader Controller        | 8     | sdhci_pci  | [EA99621380](<Notebook/Dell/Latitude/Latitude E7240/4A55E51D2962/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/EA99621380>) |
| 10ec:5227 | 17aa:2214 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 6     | rtsx       | [6E38EB1A4E](<Notebook/Lenovo/ThinkPad/ThinkPad X240 20AMS1YG01/5FCC7C04EE41/OPNSENSE-22.1.6/13.0-STABLE/AMD64/6E38EB1A4E>) |
| 10ec:525a | 17aa:2238 | Realtek Semic... | RTS525A PCI Express Card Reader      | 6     | rtsx       | [4CBD9F9314](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FQ000QUS/A325841E215E/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/4CBD9F9314>) |
| 10ec:522a | 1458:1000 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [752F962123](<Desktop/Gigabyte Technology/GB-BACE-3000/GB-BACE-3000-SBE/A8A80797C4EA/OPNSENSE-22.1.5/13.0-STABLE/AMD64/752F962123>) |
| 10ec:522a | 17aa:504a | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [117014D55F](<Notebook/Lenovo/ThinkPad/ThinkPad X260 20F6S0KA00/10FFFAF37956/FREEBSD-13.1/13.1-RELEASE/AMD64/117014D55F>) |
| 10ec:522a | 17aa:5050 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [932E722B2D](<Notebook/Lenovo/ThinkPad/ThinkPad T460p 20FW0018AD/4ACA9C3EF664/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/932E722B2D>) |
| 10ec:525a | 1028:06de | Realtek Semic... | RTS525A PCI Express Card Reader      | 5     | rtsx       | [9E798CBFC8](<Notebook/Dell/Latitude/Latitude E5470/B6D6813652AE/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/9E798CBFC8>) |
| 10ec:525a | 1028:08b8 | Realtek Semic... | RTS525A PCI Express Card Reader      | 5     | rtsx       | [A266199ACE](<Notebook/Dell/Latitude/Latitude 5400/EF7826F49036/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/A266199ACE>) |
| 10ec:5227 | 1179:0001 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 4     | rtsx       | [C41C3ADFA4](<Notebook/Toshiba/dynabook/dynabook R63-P/5718430B3004/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C41C3ADFA4>) |
| 10ec:5229 | 8086:2067 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx       | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 10ec:522a | 17aa:2279 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 10ec:522a | 17aa:506d | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [27702234CC](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga 20LH0018US/096E6C9C912E/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/27702234CC>) |
| 10ec:522a | 17aa:5082 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [CF5F498572](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 1 20UF000QRT/28FFDBA7F5C3/FREEBSD-13.1/13.1-RELEASE/AMD64/CF5F498572>) |
| 10ec:522a | 17aa:5122 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [683591700F](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MVS0LG00/F4E54EA14D75/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/683591700F>) |
| 10ec:522a | 17aa:5125 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [AF190C38E9](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS0HN1N/FFA6D6E4D3C7/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/AF190C38E9>) |
| 10ec:525a | 1028:06da | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx       | [4C4937D824](<Notebook/Dell/Precision/Precision 7710/60C3A4533903/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4C4937D824>) |
| 10ec:525a | 1028:06df | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx       | [C214CE4AB0](<Notebook/Dell/Latitude/Latitude E5570/27A2311855F4/FREEBSD-13.0-P10/13.0-RELEASE-P10/AMD64/C214CE4AB0>) |
| 10ec:525a | 17aa:224f | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx       | [0B48F96D1E](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 5th 20HR002MAT/E3D319A5E924/FREEBSD-13.1/13.1-RELEASE/AMD64/0B48F96D1E>) |
| 10ec:5209 | 104d:90b8 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx       | [D0A9E97993](<Notebook/Sony/SVF1421/SVF1421E4E/014FCDB3718D/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/D0A9E97993>) |
| 10ec:5209 | 17aa:21dd | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx       | [A697BE2AA9](<Notebook/Lenovo/ThinkPad/ThinkPad L420 7829WDY/20348E698FCF/FREEBSD-13.1/13.1-RELEASE/AMD64/A697BE2AA9>) |
| 10ec:5227 | 103c:1991 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 3     | rtsx       | [362940ACBB](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G1/43570E209C4E/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/362940ACBB>) |
| 10ec:5227 | 17aa:2217 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 3     | rtsx       | [17FD94A4C0](<Notebook/Lenovo/ThinkPad/ThinkPad S1 Yoga 20CD0038MB/84732EE686BD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/17FD94A4C0>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx       | [77E235D9F8](<Desktop/Dell/Inspiron/Inspiron 3050/EF4E88174903/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/77E235D9F8>) |
| 10ec:522a | 1558:a500 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [E6AD419F5E](<Notebook/TUXEDO/Aura/Aura 15 Gen1/1A68AD0FF8B9/GHOSTBSD-23.01.13/13.1-STABLE/AMD64/E6AD419F5E>) |
| 10ec:522a | 17aa:2233 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [56FA0D4656](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2BR00/E2372EFC6D66/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/56FA0D4656>) |
| 10ec:5249 | 1028:0665 | Realtek Semic... | RTS5249 PCI Express Card Reader      | 3     | rtsx       | [8EC61DB3F0](<Notebook/Dell/XPS/XPS 13 9343/F0F9A27ADDEB/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/8EC61DB3F0>) |
| 10ec:5249 | 17aa:3801 | Realtek Semic... | RTS5249 PCI Express Card Reader      | 3     | rtsx       | [1FEB455E8C](<Notebook/Lenovo/Y50-70/Y50-70 20378/45CB117B153A/OPNSENSE-21.7.7/12.1-RELEASE-P19-HBSD/AMD64/1FEB455E8C>) |
| 10ec:525a | 1028:079f | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [089B61BB38](<Notebook/Dell/Latitude/Latitude 7280/E9E3F30F4DB0/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/089B61BB38>) |
| 10ec:525a | 1028:081b | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [BC5EB8E237](<Notebook/Dell/Latitude/Latitude 7390/7E111470199B/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/BC5EB8E237>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [794FE8EB65](<Desktop/Dell/XPS/XPS 8950/759E5D9BB90A/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/794FE8EB65>) |
| 10ec:525a | 17aa:222e | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [8CB09E34EC](<Notebook/Lenovo/ThinkPad/ThinkPad P50 20EN0008GE/B44D5B9E19B9/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/8CB09E34EC>) |
| 10ec:525a | 17aa:224d | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [59E609FBB2](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HH001RMX/6C6441A8C24D/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/59E609FBB2>) |
| 10ec:5287 | 1043:202f | Realtek Semic... | RTL8411B PCI Express Card Reader     | 3     | rtsx       | [5624C69D4B](<Notebook/ASUSTek Computer/G551/G551JW/B7E7048EB864/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/5624C69D4B>) |
| 10ec:5287 | 1558:1313 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 3     | rtsx       | [8986953ACD](<Notebook/Notebook/N13/N13xWU/7DA387D7ADEA/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/8986953ACD>) |
| 10ec:5289 | 1043:1457 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 3     | rtsx       | [6FA29C4E4D](<Notebook/ASUSTek Computer/K55/K55VD/47D6D2467DC8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/6FA29C4E4D>) |
| 10ec:5209 | 103c:3577 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     |            | [F83C769501](<Notebook/Hewlett-Packard/2000/2000/5F42EBFDBCAE/FREEBSD-12.2/12.2-RELEASE/AMD64/F83C769501>) |
| 10ec:5227 | 103c:2246 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx       | [DA49561A8F](<Notebook/Hewlett-Packard/ProBook/ProBook 430 G2/0B9FDF5DA838/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/DA49561A8F>) |
| 10ec:5227 | 103c:2248 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx       | [ACFF807555](<Notebook/Hewlett-Packard/ProBook/ProBook 450 G2/C7626B6ED29D/FREEBSD-13.1/13.1-RELEASE/AMD64/ACFF807555>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 65    | qat        | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:19e2 |           | Intel            | Atom Processor C3000 Series Quick... | 63    | qat        | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 34    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:0434 |           | Intel            | DH89XXCC Series QAT                  | 14    |            | [2B70FDB96A](<Desktop/Intel/DENLOW_WS/DENLOW_WS/634E1D4A13FA/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2B70FDB96A>) |
| 19a2:0800 | 1734:11cc | Emulex           | ServerView iRMC HTI                  | 7     |            | [D05D07CA61](<Server/Fujitsu/PRIMERGY/PRIMERGY RX100 S8/84A39098466A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/D05D07CA61>) |
| 8086:37c8 |           | Intel            | C62x Chipset QuickAssist Technology  | 7     | qat        | [5070C11C54](<Desktop/Dell/VEP-4600/VEP-4600-V910/BAE5F41CA0D2/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/5070C11C54>) |
| 1734:1228 | 1734:1256 | Fujitsu Techn... |                                      | 4     |            | [68B3F4E862](<Server/Fujitsu/D3890-A1/D3890-A1 S26361-D3890-A100 WGS01 GS01/B57F2C826570/OPNSENSE-22.1.10/13.0-STABLE/AMD64/68B3F4E862>) |
| 8086:19e2 | 8086:19e2 | Intel            | Atom Processor C3000 Series Quick... | 3     | qat        | [547B59BE2B](<Desktop/Netgate/6100/6100/C1D72F5D06FF/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/547B59BE2B>) |
| 8086:1f18 | 15d9:0820 | Intel            | Atom processor C2000 QAT             | 3     | qat        | [FB96378782](<Server/Supermicro/A1/A1SRM-2758F/F38A17AAB757/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FB96378782>) |
| 1000:0a05 | 1000:0a09 | Broadcom / LSI   |                                      | 2     |            | [5A8641FC9D](<Desktop/Cisco/SALEEN/SALEEN/40F23693CE8F/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/5A8641FC9D>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 10de:03f4 |           | Nvidia           | MCP61 SMU                            | 1     |            | [009BC44D12](<Desktop/ONDA/N78G5D3/N78G5D3 Ver:5.00/8C38C68857FC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/009BC44D12>) |
| 10de:03f4 | 1462:7597 | Nvidia           | MCP61 SMU                            | 1     |            | [6BE2D8AEC7](<Desktop/MSI/MS/MS-7597/30A30607F88A/FREEBSD-12.2/12.2-RELEASE/AMD64/6BE2D8AEC7>) |
| 10de:0753 | 1025:0157 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 1     |            | [DB1E7A52B9](<Desktop/Acer/Aspire/Aspire X3200/F5C25C81945B/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/DB1E7A52B9>) |
| 10de:0753 | 1025:0228 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 1     |            | [FA59D6AA07](<Desktop/Acer/Aspire/Aspire X3400/DD3C224FC323/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/FA59D6AA07>) |
| 10de:07da | 1025:0137 | Nvidia           | MCP73 Co-processor                   | 1     |            | [6C169BDB6A](<Desktop/Dell/OptiPlex/OptiPlex 7040/D9A5C4B626A4/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/6C169BDB6A>) |
| 10de:0aa3 | 1028:0271 | Nvidia           | MCP79 Co-processor                   | 1     |            | [642DA98E96](<Notebook/Dell/Studio/Studio XPS 1340/ACFB55475A2B/FREEBSD-13.1/13.1-RELEASE/AMD64/642DA98E96>) |
| 10de:0aa3 | 1043:1cf7 | Nvidia           | MCP79 Co-processor                   | 1     |            | [6F7A8F3338](<Notebook/ASUSTek Computer/K50/K50IN/649EA35E6EC2/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6F7A8F3338>) |
| 10de:0aa3 | 1043:8402 | Nvidia           | MCP79 Co-processor                   | 1     |            | [5DC595EB79](<Notebook/ASUSTek Computer/1201/1201N/5335B46C2398/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5DC595EB79>) |
| 10de:0aa3 | 105b:0d52 | Nvidia           | MCP79 Co-processor                   | 1     |            | [79AB8EFB37](<Desktop/Foxconn/nT-330/nT-330i/70806ED76AFE/FREEBSD-12.1-P6/12.1-RELEASE-P6/AMD64/79AB8EFB37>) |
| 10de:0aa3 | 19da:a108 | Nvidia           | MCP79 Co-processor                   | 1     |            | [623EA6A889](<Desktop/Others/Others/Others/2BBBCF62335B/FREEBSD-12.1--HBSD/12.1-RELEASE-P7-HBSD/AMD64/623EA6A889>) |
| 13a3:0020 |           | Hifn             | 7955 Security Processor              | 1     | hifn       | [11BC81EF41](<Server/Intel/S1200/S1200BTL/C865C7CEDA20/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/11BC81EF41>) |
| 1734:1228 | 1734:1229 | Fujitsu Techn... |                                      | 1     |            | [6E6F1B0F99](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M4/BA1E3C5B14F6/HARDENEDBSD-12.2--HBSD/12.2-STABLE-HBSD/AMD64/6E6F1B0F99>) |
| 8086:18a0 |           | Intel            | C4xxx Series QAT                     | 1     |            | [1CFE8960A1](<Server/Supermicro/Super/Super Server/574FD572E67A/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/1CFE8960A1>) |
| 8086:37c8 | 8086:0001 | Intel            | C62x Chipset QuickAssist Technology  | 1     | qat        | [638B27BC34](<Server/Supermicro/Super/Super Server/CF1692AC0104/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638B27BC34>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 239   |            | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 205   |            | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:4de0 | 8086:7270 | Intel            | Management Engine Interface          | 146   |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 103   |            | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 79    |            | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 77    |            | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 45    |            | [DDF2BCB808](<Desktop/Protectli/FW/FW6/51B65D660F9A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/DDF2BCB808>) |
| 8086:8c3a | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    |            | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c3a | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    |            | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:8c3a | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 38    |            | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:19d3 | 8086:19d3 | Intel            | Atom Processor C3000 Series ME HE... | 37    |            | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:1c3a | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 37    |            | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:1c3a | 1458:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 35    |            | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 8086:8c3d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 35    | uart       | [A477C2B046](<Desktop/Dell/OptiPlex/OptiPlex 9020/C840DA9F22BC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A477C2B046>) |
| 8086:a13a | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 35    |            | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 8086:1e3a | 1043:84ca | Intel            | 7 Series/C216 Chipset Family MEI ... | 32    |            | [A2873D7C87](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/A2873D7C87>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 31    |            | [C258B4972C](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/C258B4972C>) |
| 8086:1e3a | 1028:0577 | Intel            | 7 Series/C216 Chipset Family MEI ... | 30    |            | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:9de0 | 8086:7270 | Intel            | Cannon Point-LP MEI Controller #1    | 30    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:8c3a | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 29    |            | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 8086:8c3b | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 29    |            | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 29    |            | [6283151877](<Server/HPE/MM10/MM10Gen9/C96A2A643802/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6283151877>) |
| 8086:1c3a | 8086:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 28    |            | [B2176FAFCF](<Desktop/Intel/MAHOBAY/MAHOBAY/0D48ADEA90BB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2176FAFCF>) |
| 8086:1e3a | 1458:1c3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 28    |            | [D8C78B92A7](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4DBEA0F75A7B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D8C78B92A7>) |
| 8086:5a9c | 8086:7270 | Intel            |                                      | 28    |            | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:5a9e | 8086:7270 | Intel            |                                      | 28    |            | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:319a | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 27    |            | [DF7A30FC45](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/53D0F9939362/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/DF7A30FC45>) |
| 8086:a360 | 1043:8694 | Intel            | Cannon Lake PCH HECI Controller      | 27    |            | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 8086:19d3 | 15d9:0969 | Intel            | Atom Processor C3000 Series ME HE... | 26    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:8c3a | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 26    |            | [E766835AB5](<Server/Supermicro/Super/Super Server/ACA476C2CF6E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E766835AB5>) |
| 8086:8c3b | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 26    |            | [E766835AB5](<Server/Supermicro/Super/Super Server/ACA476C2CF6E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E766835AB5>) |
| 8086:a2ba | 1043:8694 | Intel            | 200 Series PCH CSME HECI #1          | 26    |            | [FD39A615DE](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-K R2.0/7D5721B3D945/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD39A615DE>) |
| 8086:3b64 | 17aa:215f | Intel            | 5 Series/3400 Series Chipset HECI... | 25    |            | [9F9CB3E201](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537B94/CDBD8C566708/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9F9CB3E201>) |
| 8086:5a9a |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 25    |            | [16FA0B0102](<Desktop/NF692/1/1.0/9852CE16A74F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16FA0B0102>) |
| 8086:8c3a | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:8c3a | 1458:1c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 8086:8c3d | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | uart       | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:1c3a | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 23    |            | [E5A43DD311](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4286CTO/3C1927176580/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/E5A43DD311>) |
| 8086:5a9a | 1849:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 23    |            | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 8086:8c3a | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 23    |            | [64D844777A](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/64D844777A>) |
| 8086:8c3b | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 23    |            | [64D844777A](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/64D844777A>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 22    |            | [6CD6B15A60](<Convertible/Medion/S4401/S4401 MD61519/EC479CD0D4FD/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6CD6B15A60>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 21    |            | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 8086:1e3a | 8086:1e3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 21    |            | [C2735D8120](<Notebook/Others/Others/Others/E349DD8616DA/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/C2735D8120>) |
| 8086:8c3a | 1849:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 21    |            | [28E606751F](<Desktop/ASRock/H81/H81M-HDS/255D1BAAA00A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/28E606751F>) |
| 8086:8c3a | 8086:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 21    |            | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 8086:02e0 | 8086:7270 | Intel            | Comet Lake Management Engine Inte... | 20    |            | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:a13a | 1458:1c3a | Intel            | 100 Series/C230 Series Chipset Fa... | 20    |            | [FB5A559634](<Desktop/Gigabyte Technology/B150/B150-HD3P/7B89078673EA/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/FB5A559634>) |
| 8086:a2ba | 1458:1c3a | Intel            | 200 Series PCH CSME HECI #1          | 20    |            | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 19    |            | [951295643C](<Mini Pc/Apple/Macmini6/Macmini6,2/8C16AF9DDE18/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/951295643C>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 292   |            | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 188   |            | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 172   |            | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 164   |            | [1CCA4A556D](<Notebook/Deciso/OPNsense/OPNsense Appliance/2DD46B265269/OPNSENSE-23.1.1/13.1-RELEASE-P7/AMD64/1CCA4A556D>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 116   | ccp        | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 84    |            | [FBFF29A62A](<Desktop/ASRock/X470/X470 Gaming K4/FFA88723BDD5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/FBFF29A62A>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 45    |            | [8D052CBF4C](<Mini Pc/Broachlink/NOAH/NOAH V2 E3845/AF93BF149B22/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/8D052CBF4C>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 42    | ccp        | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 1022:1486 | 1043:87c0 | AMD              | Starship/Matisse Cryptographic Co... | 42    |            | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 177d:0010 | 177d:0001 | Cavium           | CN15XX/CN16XX [Nitrox PX]            | 28    |            | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 1022:1456 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) Platf... | 27    |            | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 25    |            | [021F9A6E74](<Mini Pc/Hewlett-Packard/t630/t630 Thin Client/844C0829389E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/021F9A6E74>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 21    |            | [0ADF0CA671](<Desktop/ZOTAC/Others/Others/6E70FB5A2725/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0ADF0CA671>) |
| 1022:15df | 1043:876b | AMD              | Family 17h (Models 10h-1fh) Platf... | 19    |            | [652B3323C6](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-R/60899A106B63/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/652B3323C6>) |
| 8086:0f18 | 1849:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 19    |            | [5D0F6C2276](<Desktop/ASRock/Q1900/Q1900M/5C14E92D5780/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5D0F6C2276>) |
| 1022:1486 | 1043:8808 | AMD              | Starship/Matisse Cryptographic Co... | 16    |            | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 1022:15df | 1043:8809 | AMD              | Family 17h (Models 10h-1fh) Platf... | 15    |            | [3548F4EFA2](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/75E66F2BE030/FREEBSD-13.2-STABLE/13.2-STABLE/AMD64/3548F4EFA2>) |
| 8086:2298 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    |            | [1A107A7C43](<Server/Supermicro/Super/Super Server/08DBAE3B5E67/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/1A107A7C43>) |
| 8086:2298 | 1849:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     |            | [80C809E992](<Desktop/ASRock/N3710-NUC/N3710-NUC IPC/E0800AE12493/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/80C809E992>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     |            | [2690C2A8DF](<Desktop/NU941/1/1.0/5ECD4B5CC634/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/2690C2A8DF>) |
| 8086:0f18 | 1458:1c3a | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 8     |            | [E2AD4D8035](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/FC5120937F9C/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/E2AD4D8035>) |
| 1022:15df | 1849:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 7     |            | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 8086:2298 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     |            | [A27331804B](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-102/8054EC01AC51/FREEBSD-13.2-BETA2/13.2-BETA2/AMD64/A27331804B>) |
| 8086:2298 | 1043:8534 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     |            | [7D6E696FB4](<Desktop/ASUSTek Computer/All/All Series/A477A77FB147/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/7D6E696FB4>) |
| 1022:1486 | 1462:7c02 | AMD              | Starship/Matisse Cryptographic Co... | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 1022:15df | 17aa:5125 | AMD              | Family 17h (Models 10h-1fh) Platf... | 5     |            | [AF190C38E9](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS0HN1N/FFA6D6E4D3C7/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/AF190C38E9>) |
| 8086:2298 | 1458:1000 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [752F962123](<Desktop/Gigabyte Technology/GB-BACE-3000/GB-BACE-3000-SBE/A8A80797C4EA/OPNSENSE-22.1.5/13.0-STABLE/AMD64/752F962123>) |
| 8086:2298 | 1458:1c3a | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [C84BEDC821](<Desktop/Gigabyte Technology/N3160/N3160ND3V/B01DE72F7AFE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C84BEDC821>) |
| 1022:1498 | 1022:1498 | AMD              | Starship/Matisse PTDMA               | 4     |            | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |
| 1022:1578 | 103c:84ac | AMD              | Carrizo Platform Security Processor  | 4     |            | [766E62F699](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/3E8F8F48759C/NOMADBSD-5806F915/13.0-RELEASE/AMD64/766E62F699>) |
| 1022:15df | 17aa:3834 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [4C83122CC0](<Notebook/Lenovo/Yoga/Yoga Slim 7 Pro 14ACH5 O 82N5/C4F4168282ED/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/4C83122CC0>) |
| 1022:15df | 17aa:5097 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [278A2A11CD](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/278A2A11CD>) |
| 1022:15df | 17aa:5122 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [247370372D](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MVS0LG00/F4E54EA14D75/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/247370372D>) |
| 1022:15df | 1d05:109f | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [5EDF8A1BEF](<Notebook/TUXEDO/Pulse/Pulse 14 Gen1/B37BF57882B7/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/5EDF8A1BEF>) |
| 8086:0f18 | 1043:8534 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     |            | [27EA626000](<Desktop/ASUSTek Computer/All/All Series/3184501520E4/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/27EA626000>) |
| 8086:2298 | 1565:3112 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     |            | [4520B5034E](<Desktop/ASRock/E350/E350M1/790F04D92088/FREEBSD-13.1-RC6/13.1-RC6/AMD64/4520B5034E>) |
| 1022:1456 | 1462:7b86 | AMD              | Family 17h (Models 00h-0fh) Platf... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:1537 | 17aa:3801 | AMD              | Kabini/Mullins PSP-Platform Secur... | 3     |            | [6E31B5F45B](<Notebook/Lenovo/G40-45/G40-45 80E1/EA83D0EBE432/FREEBSD-13.1/13.1-RELEASE/AMD64/6E31B5F45B>) |
| 1022:15df | 1462:7b89 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     |            | [EC37957AED](<Desktop/MSI/MS-7/MS-7B89/27DA135076D6/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/EC37957AED>) |
| 1022:15df | 1558:a500 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     |            | [E6AD419F5E](<Notebook/TUXEDO/Aura/Aura 15 Gen1/1A68AD0FF8B9/GHOSTBSD-23.01.13/13.1-STABLE/AMD64/E6AD419F5E>) |
| 1022:15df | 17aa:5082 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [CF5F498572](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 1 20UF000QRT/28FFDBA7F5C3/FREEBSD-13.1/13.1-RELEASE/AMD64/CF5F498572>) |
| 8086:0f18 | 1071:0730 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [294F283D65](<Mini Pc/AMI/Aptio/Aptio CRB/293083C7BA4B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/294F283D65>) |
| 8086:0f18 | 15d9:0816 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [D22806833A](<Server/Supermicro/X10/X10SBA/D6CCFE818C24/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/D22806833A>) |
| 8086:0f18 | 8086:2055 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [DD0D96422F](<Desktop/Intel/DN2820FYK/DN2820FYK H24582-203/B4FE012ED3BF/FREEBSD-13.2-BETA2/13.2-BETA2/AMD64/DD0D96422F>) |
| 1022:1456 | 1025:1246 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     |            | [9E03A76684](<Notebook/Acer/Predator/Predator PH517-61/401258E70C57/FREEBSD-13.0/13.0-RELEASE/AMD64/9E03A76684>) |
| 1022:1456 | 1462:7b89 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     |            | [8B3A234691](<Desktop/MSI/MS-7/MS-7B89/C8A1522450C9/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/8B3A234691>) |
| 1022:1486 | 1043:87cb | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:1486 | 1458:1000 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1022:1486 | 1462:7b86 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 1022:1486 | 1462:7c95 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 46    | fwohci     | [4284C60268](<Mini Pc/Apple/Macmini3/Macmini3,1/2E022B995A59/FREEBSD-13.1/14.0-CURRENT/AMD64/4284C60268>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 26    | fwohci     | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 1180:0832 | 17aa:20c7 | Ricoh            | R5C832 IEEE 1394 Controller          | 21    | fwohci     | [67B2E8DB2B](<Notebook/Lenovo/ThinkPad/ThinkPad T61p 6457UN2/ABBAD64ECA84/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/67B2E8DB2B>) |
| 1180:e832 | 17aa:2136 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 14    | fwohci     | [9F9CB3E201](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537B94/CDBD8C566708/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9F9CB3E201>) |
| 1106:3044 | 1043:81fe | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 13    | fwohci     | [DD9685A909](<Desktop/ASUSTek Computer/P7P55D/P7P55D DELUXE/12FEB991B761/FREEBSD-13.1-P6/13.1-RELEASE-P6/AMD64/DD9685A909>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 11    | fwohci     | [7AEF0A996B](<Notebook/Apple/MacBook3/MacBook3,1/B75216EE3719/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7AEF0A996B>) |
| 1106:3044 | 1458:1000 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 10    | fwohci     | [70C9122B95](<Desktop/Gigabyte Technology/Z87/Z87X-UD5H/D76966E3C571/OPNSENSE-22.1.10/13.0-STABLE/AMD64/70C9122B95>) |
| 11c1:5811 | 103c:1589 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 10    | fwohci     | [8A927B43CB](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D768D5739884/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/8A927B43CB>) |
| 104c:8024 | 1458:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 8     | fwohci     | [6B63A16799](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/CA4B1CA9726F/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6B63A16799>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 8     | fwohci     | [2A03C05CCE](<Desktop/Equus Computer Systems/Nobilis/Nobilis/67B3FC31A85D/FREEBSD-12.3/12.3-RELEASE/AMD64/2A03C05CCE>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 8     | fwohci     | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 1180:e832 | 17aa:21ce | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 7     | fwohci     | [4067CE2036](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236C92/28F77ADEDD67/FREEBSD-13.1/13.1-RELEASE/AMD64/4067CE2036>) |
| 1180:e832 | 17aa:21cf | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 7     |            | [BAA0E928A8](<Notebook/Lenovo/ThinkPad/ThinkPad W520 427638U/E6F9611374C5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/BAA0E928A8>) |
| 11c1:5811 | 1043:8294 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 7     | fwohci     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 1180:e832 | 17aa:21f6 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 6     | fwohci     | [97D9B10C8A](<Notebook/Lenovo/ThinkPad/ThinkPad T530 24297XG/7B74CE72D78E/FREEBSD-12.3-P1/12.3-RELEASE-P1/AMD64/97D9B10C8A>) |
| 11c1:5811 | 103c:158a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 5     | fwohci     | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 104c:8025 |           | Texas Instrum... | TSB82AA2 IEEE-1394b Link Layer Co... | 4     | fwohci     | [912D02AEC2](<Notebook/Apple/MacBookPro3/MacBookPro3,1/F5F1B1FD305E/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/912D02AEC2>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 4     | fwohci     | [F65675C771](<Desktop/ASUSTek Computer/P8Z68/P8Z68 DELUXE/63B9369E8108/FREEBSD-13.1/13.1-RELEASE/AMD64/F65675C771>) |
| 1180:e832 | 1028:040a | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 4     | fwohci     | [8C904D84E0](<Notebook/Dell/Latitude/Latitude E6410/D86C1197F0AC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/8C904D84E0>) |
| 11c1:5811 | 1028:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 4     | fwohci     | [5899533EDD](<Desktop/Dell/OptiPlex/OptiPlex 780/1CFDAF3517CA/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5899533EDD>) |
| 1217:13f7 | 1028:049b | O2 Micro         | 1394 OHCI Compliant Host Controller  | 4     | fwohci     | [524AB094E1](<Notebook/Dell/Latitude/Latitude E5420/15C36179305C/FREEBSD-13.1/13.1-RELEASE/AMD64/524AB094E1>) |
| 104c:8023 | 1043:815b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 3     | fwohci     | [87D7D4435B](<Desktop/ASUSTek Computer/P5/P5B-Deluxe/5AB2F7FF0FA3/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/87D7D4435B>) |
| 1106:3403 | 1849:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 3     |            | [CD85D68DCD](<Desktop/ASRock/X79/X79 Extreme6-GB/34806081C0EC/OPNSENSE-22.1.6/13.0-STABLE/AMD64/CD85D68DCD>) |
| 1180:0832 | 1028:024d | Ricoh            | R5C832 IEEE 1394 Controller          | 3     | fwohci     | [FDB3DE3036](<Notebook/Dell/Latitude/Latitude E4300/B023391CA6F2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/FDB3DE3036>) |
| 1217:00f7 | 1179:ff50 | O2 Micro         | Firewire (IEEE 1394)                 | 3     | fwohci     | [E057898546](<Notebook/Toshiba/Satellite/Satellite A300/72110BAFD1E3/FREEBSD-12.3-STABLE/12.3-STABLE/I386/E057898546>) |
| 197b:2380 | 1043:8313 | JMicron Techn... | IEEE 1394 Host Controller            | 3     | fwohci     | [5999E0EBFB](<Desktop/ASUSTek Computer/P5P43TD/P5P43TD PRO/CAA935C7EB09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5999E0EBFB>) |
| 104c:8023 | 108e:6676 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 2     |            | [AD993A51ED](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/16A2E5FCDB6A/FREEBSD-12.1/12.1-RELEASE/AMD64/AD993A51ED>) |
| 104c:8023 | 15d9:0805 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 2     |            | [2758B438C6](<Server/Supermicro/X10/X10SAE/4A17C592FC65/TRUENAS-12.2-P2/12.2-RELEASE-P2/AMD64/2758B438C6>) |
| 104c:8024 | 1019:8056 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 2     | fwohci     | [3B8D6CB36E](<Desktop/Acer/Aspire/Aspire T180/7F825E5A8956/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3B8D6CB36E>) |
| 104c:8024 | 1028:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 2     |            | [EDEF5C789D](<Desktop/Dell/Studio/Studio XPS 9100/AEDEA8FF9972/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/EDEF5C789D>) |
| 104c:803a | 1179:ff00 | Texas Instrum... | PCIxx12 OHCI Compliant IEEE 1394 ... | 2     |            | [860AEA3CE4](<Notebook/Toshiba/Satellite/Satellite A200/CC9CFD7250FC/FREEBSD-13.1-P2/13.1-RELEASE-P2/I386/860AEA3CE4>) |
| 1106:3044 | 1849:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 2     |            | [19BA4D2EE9](<Desktop/ASRock/Z77/Z77 Extreme6/929553D2B892/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19BA4D2EE9>) |
| 1106:3403 | 1025:0250 | VIA Technologies | VT6315 Series Firewire Controller    | 2     |            | [D316352C20](<Desktop/Acer/Aspire/Aspire X5810/21552B3F601D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D316352C20>) |
| 1106:3403 | 1028:040d | VIA Technologies | VT6315 Series Firewire Controller    | 2     |            | [7F75F30B75](<Desktop/Dell/Studio/Studio XPS 8100/AF73B07C29DA/FREEBSD-12.2/12.2-RELEASE/AMD64/7F75F30B75>) |
| 1106:3403 | 1043:8374 | VIA Technologies | VT6315 Series Firewire Controller    | 2     | fwohci     | [1C30F7523F](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/0638EC1B243E/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/1C30F7523F>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 2     | fwohci     | [40687B0E17](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/23AA4FC47B92/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/40687B0E17>) |
| 1180:0832 | 1028:024f | Ricoh            | R5C832 IEEE 1394 Controller          | 2     | fwohci     | [5FAD69BBF0](<Notebook/Dell/Latitude/Latitude E6500/2F32EC7D1696/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/5FAD69BBF0>) |
| 1180:0832 | 1028:029f | Ricoh            | R5C832 IEEE 1394 Controller          | 2     | fwohci     | [A185649600](<Notebook/Dell/Studio/Studio 1537/0D2F6FFDCD3E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A185649600>) |
| 1180:0832 | 103c:1521 | Ricoh            | R5C832 IEEE 1394 Controller          | 2     |            | [0063369C40](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8540w/243CB86EF384/MYBEE-13.1/13.1-RELEASE/AMD64/0063369C40>) |
| 1180:0832 | 103c:30cc | Ricoh            | R5C832 IEEE 1394 Controller          | 2     |            | [F3058F97F9](<Notebook/Hewlett-Packard/Pavilion/Pavilion dv6700/BB8C0CF6CF49/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/F3058F97F9>) |
| 1180:0832 | 1043:1877 | Ricoh            | R5C832 IEEE 1394 Controller          | 2     | fwohci     | [883DED6CB1](<Notebook/ASUSTek Computer/N50/N50Vc/77A5AA89F908/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/883DED6CB1>) |
| 1180:e832 | 1028:040c | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 2     |            | [66DED228EA](<Notebook/Dell/Precision/Precision M4500/BFBE547F5F92/FREEBSD-13.1/13.1-RELEASE/AMD64/66DED228EA>) |
| 11c1:5811 | 103c:1309 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     | fwohci     | [3F170BDEE6](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/645388D505B6/GHOSTBSD-22.04.22/13.0-STABLE/AMD64/3F170BDEE6>) |
| 11c1:5811 | 103c:130a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     |            | [A24F08281D](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/A24F08281D>) |
| 11c1:5811 | 103c:130b | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     |            | [25B7A10166](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/79ADC3087F2D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/25B7A10166>) |
| 11c1:5901 | 1b5b:803b | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 2     |            | [0696D30D3F](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/0696D30D3F>) |
| 11c1:5903 | 11c1:5900 | LSI              | FW533 [TrueFire] PCIe 1394a Contr... | 2     | fwohci     | [79503C0635](<Notebook/Apple/MacBook5/MacBook5,2/98FAA840F548/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/79503C0635>) |
| 1217:00f7 | 1028:01f9 | O2 Micro         | Firewire (IEEE 1394)                 | 2     | fwohci     | [1C600CC283](<Notebook/Dell/Latitude/Latitude D630/6FCFB35F2ECF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/1C600CC283>) |
| 197b:2380 | 103c:17a7 | JMicron Techn... | IEEE 1394 Host Controller            | 2     | fwohci     | [462FC329A9](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570p/8F084339058D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/462FC329A9>) |
| 1033:00cd | 12ee:8010 | NEC Computers    | uPD72870 [Firewarden] IEEE1394a O... | 1     | fwohci     | [E34B6118A2](<Desktop/Hewlett-Packard/Compaq/Compaq 505B Microtower PC/0EF9A1953E0E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E34B6118A2>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 210   | vgapci     | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 174   | vgapci     | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 159   | vgapci     | [12AC44CBF7](<Desktop/Others/Others/Others/B6CD8CD35969/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/12AC44CBF7>) |
| 8086:4e61 | 8086:2212 | Intel            | JasperLake [UHD Graphics]            | 127   | vgapci     | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 89    | vgapci     | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 88    | vgapci     | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 78    | vgapci     | [D7B171D0BB](<Desktop/Others/Others/Others/E869214B6318/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/D7B171D0BB>) |
| 8086:0f31 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 77    | vgapci     | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 65    | vgapci     | [43C3EAFD9D](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen8/98A8C2381905/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/43C3EAFD9D>) |
| 8086:5916 | 8086:2015 | Intel            | HD Graphics 620                      | 63    | vgapci     | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:0a16 | 8086:0a16 | Intel            | Haswell-ULT Integrated Graphics C... | 55    | vgapci     | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1002:9831 | 103c:213d | AMD              | Kabini [Radeon HD 8400E]             | 51    | vgapci     | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1002:515e | 103c:31fb | AMD              | ES1000                               | 44    | vgapci     | [B281EEC189](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/D6765403633D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/B281EEC189>) |
| 102b:0532 | 1028:04dd | Matrox Electr... | MGA G200eW WPCM450                   | 44    | vgapci     | [E975D67484](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E975D67484>) |
| 1002:131c | 103c:8103 | AMD              | Kaveri [Radeon R7 Graphics]          | 43    | vgapci     | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 8086:5917 | 8086:2015 | Intel            | UHD Graphics 620                     | 42    | vgapci     | [516C778D65](<Desktop/Yanling/YL-KBR6/YL-KBR6L/0108DB586B13/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/516C778D65>) |
| 8086:1616 | 8086:1616 | Intel            | HD Graphics 5500                     | 41    | vgapci     | [CF598483CF](<Notebook/Google/Lulu/Lulu/69AC5E94B55B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CF598483CF>) |
| 8086:a001 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 38    | agp        | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 37    | nvidia     | [1E97EE1C05](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/98235472B8D9/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/1E97EE1C05>) |
| 8086:2e32 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 37    | agp        | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:a002 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 37    | vgapci     | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:0412 | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 35    | vgapci     | [EC33F29DC0](<Desktop/ASUSTek Computer/All/All Series/9506DED5E0BD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/EC33F29DC0>) |
| 8086:0412 | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 34    | vgapci     | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 1002:9833 | 1734:1202 | AMD              | Kabini [Radeon HD 8330E]             | 33    | vgapci     | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1002:9851 | 1734:1202 | AMD              | Mullins [Radeon R4/R5 Graphics]      | 31    | vgapci     | [DFBD35D47F](<Desktop/Fujitsu/FUTRO/FUTRO S920/3A4A89D57DB6/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/DFBD35D47F>) |
| 102b:0532 | 15d9:0624 | Matrox Electr... | MGA G200eW WPCM450                   | 31    | vgapci     | [904FDE472A](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/904FDE472A>) |
| 8086:5916 |           | Intel            | HD Graphics 620                      | 31    | vgapci     | [882F0868FE](<Desktop/Protectli/FW/FW6/484652E02452/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/882F0868FE>) |
| 1a03:2000 | 15d9:086d | ASPEED Techno... | ASPEED Graphics Family               | 29    | vgapci     | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 8086:0412 | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 28    | vgapci     | [31ED952F9C](<Desktop/Dell/OptiPlex/OptiPlex 3020/B41A8964B213/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/31ED952F9C>) |
| 8086:1626 | 8086:1626 | Intel            | HD Graphics 6000                     | 28    | vgapci     | [6BEC4024A8](<Desktop/Intel/QHSW/QHSW02/C9D03D675712/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6BEC4024A8>) |
| 1a03:2000 | 15d9:0813 | ASPEED Techno... | ASPEED Graphics Family               | 26    | vgapci     | [D179977442](<Mini Pc/Supermicro/A1/A1SAi/DEFEE5630512/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D179977442>) |
| 1a03:2000 | 15d9:0921 | ASPEED Techno... | ASPEED Graphics Family               | 26    | vgapci     | [E766835AB5](<Server/Supermicro/Super/Super Server/ACA476C2CF6E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E766835AB5>) |
| 1a03:2000 | 15d9:0969 | ASPEED Techno... | ASPEED Graphics Family               | 26    | vgapci     | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:0412 | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 25    | vgapci     | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:0412 | 8086:0412 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 25    | vgapci     | [2B70FDB96A](<Desktop/Intel/DENLOW_WS/DENLOW_WS/634E1D4A13FA/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2B70FDB96A>) |
| 1a03:2000 | 15d9:0842 | ASPEED Techno... | ASPEED Graphics Family               | 24    | vgapci     | [64D844777A](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/64D844777A>) |
| 8086:0402 | 8086:0402 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 24    | vgapci     | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 23    | vgapci     | [F67CE5D559](<Mini Pc/BESSTAR Tech/GK/GK41/6643A2716B62/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/F67CE5D559>) |
| 8086:3ea0 | 8086:2212 | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 23    | vgapci     | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 1002:15d8 | 1002:15d8 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 22    | vgapci     | [02970305DB](<Desktop/Gigabyte Technology/A320/A320M-H/6997E8A1E1D6/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/02970305DB>) |
| 1a03:2000 | 1849:2000 | ASPEED Techno... | ASPEED Graphics Family               | 22    | vgapci     | [5DFCF8051D](<Desktop/ASRock/E3/E3C226D2I/CDCF2A093383/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5DFCF8051D>) |
| 8086:0152 | 1028:0577 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 22    | vgapci     | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:3184 | 1028:080c | Intel            | GeminiLake [UHD Graphics 605]        | 22    | vgapci     | [DF7A30FC45](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/53D0F9939362/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/DF7A30FC45>) |
| 8086:5916 | 8086:2212 | Intel            | HD Graphics 620                      | 22    | vgapci     | [DDF2BCB808](<Desktop/Protectli/FW/FW6/51B65D660F9A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/DDF2BCB808>) |
| 8086:0046 | 17aa:215a | Intel            | Core Processor Integrated Graphic... | 21    | i915       | [9F9CB3E201](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537B94/CDBD8C566708/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9F9CB3E201>) |
| 8086:0412 | 1458:d000 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 21    | vgapci     | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 8086:22b1 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 21    | vgapci     | [0ADF0CA671](<Desktop/ZOTAC/Others/Others/6E70FB5A2725/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0ADF0CA671>) |
| 8086:5a85 | 1849:5a85 | Intel            | HD Graphics 500                      | 21    | vgapci     | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 8086:5a85 | 8086:5a85 | Intel            | HD Graphics 500                      | 21    | vgapci     | [16FA0B0102](<Desktop/NF692/1/1.0/9852CE16A74F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16FA0B0102>) |
| 8086:0126 | 17aa:21da | Intel            | 2nd Generation Core Processor Fam... | 20    | i915       | [E5A43DD311](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4286CTO/3C1927176580/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/E5A43DD311>) |

### Input (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 7     | emujoy     | [2A03C05CCE](<Desktop/Equus Computer Systems/Nobilis/Nobilis/67B3FC31A85D/FREEBSD-12.3/12.3-RELEASE/AMD64/2A03C05CCE>) |
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 3     |            | [2620FD3511](<Desktop/ASUSTek Computer/P8/P8B75-M/D6575EA2BF9C/FREEBSD-13.1/13.1-RELEASE/AMD64/2620FD3511>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 256   |            | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM Controller   | 147   |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 121   |            | [53FA01007B](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/53FA01007B>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 41    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:a121 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    |            | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 8086:19de | 8086:7270 | Intel            | Atom Processor C3000 Series Power... | 37    |            | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 36    |            | [6283151877](<Server/HPE/MM10/MM10Gen9/C96A2A643802/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6283151877>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 35    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 34    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 34    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 34    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 33    |            | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 27    |            | [F9DB95D778](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming F15 FX506LH_FX506LH/1C68DE0A8C5A/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/F9DB95D778>) |
| 8086:a36f | 1043:8694 | Intel            | Cannon Lake PCH Shared SRAM          | 27    |            | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 26    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 26    |            | [FD39A615DE](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-K R2.0/7D5721B3D945/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD39A615DE>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 24    |            | [85628154A2](<Desktop/Gigabyte Technology/H510M/H510M S2H V2/D6902D5FE2E5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/85628154A2>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 24    |            | [6CD6B15A60](<Convertible/Medion/S4401/S4401 MD61519/EC479CD0D4FD/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6CD6B15A60>) |
| 8086:a2a1 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family Po... | 21    |            | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 8086:a121 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 20    |            | [FB5A559634](<Desktop/Gigabyte Technology/B150/B150-HD3P/7B89078673EA/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/FB5A559634>) |
| 8086:a1a1 | 15d9:0986 | Intel            | C620 Series Chipset Family Power ... | 19    |            | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 8086:4b7f | 8086:7270 | Intel            | Elkhart Lake PMC SRAM                | 18    |            | [21D2214DA6](<Desktop/Protectli/VP/VP2420/F9E7BE26C82B/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/21D2214DA6>) |
| 8086:a2a1 | 1849:a2a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 17    |            | [0B7DACF902](<Desktop/ASRock/X299/X299E-ITX-ac/78187292FFBE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0B7DACF902>) |
| 8086:a36f | 1849:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 17    |            | [0E0C795886](<Desktop/ASRock/H310/H310M-ITX-ac/1C596F08C310/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0E0C795886>) |
| 1912:0011 |           | Renesas Techn... | SH7757 PCIe End-Point [PBI]          | 15    |            | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 15    |            | [E27931F082](<Desktop/BESSTAR Tech/TH/TH50/1DD7349765D5/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/E27931F082>) |
| 8086:a121 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 15    |            | [D69ABA5432](<Desktop/Fujitsu/ESPRIMO/ESPRIMO Q956/C9D1C0D177A5/FREEBSD-13.1/13.1-RELEASE/AMD64/D69ABA5432>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 15    |            | [936CB33704](<Desktop/HPE/ProLiant/ProLiant MicroServer Gen10 Plus/8ADCB2DEFF43/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/936CB33704>) |
| 8086:43ef | 1043:8694 | Intel            | Tiger Lake-H Shared SRAM             | 14    |            | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 14    |            | [B08FD92E36](<Desktop/MSI/MS-7/MS-7D46/C894FC6BA535/MYBEE-13.2-RC2/13.2-RC2/AMD64/B08FD92E36>) |
| 8086:9def | 8086:2074 | Intel            | Cannon Point-LP Shared SRAM          | 14    |            | [B2784F4025](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/B2784F4025>) |
| 8086:a121 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 14    |            | [7AB6080DFE](<Server/Supermicro/Super/Super Server/EF3360E50027/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/7AB6080DFE>) |
| 8086:a36f | 17aa:312d | Intel            | Cannon Lake PCH Shared SRAM          | 14    |            | [867C14F8D1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7003HUS/E865EFD8EF3C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/867C14F8D1>) |
| 8086:9d21 | 8086:2068 | Intel            | Sunrise Point-LP PMC                 | 13    |            | [ACA9E2885D](<Mini Pc/Intel/NUC7i3BNB/NUC7i3BNB J22859-307/2278924F334A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/ACA9E2885D>) |
| 8086:9def |           | Intel            | Cannon Point-LP Shared SRAM          | 13    |            | [8D49D50738](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 7th 20QES53R00/AB4C518C252E/FREEBSD-13.1/13.1-RELEASE/AMD64/8D49D50738>) |
| 8086:a0ef | 8086:7270 | Intel            | Tiger Lake-LP Shared SRAM            | 13    |            | [80F6445F54](<Notebook/Star Labs/StarBook/StarBook/2BCE064BBD99/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/80F6445F54>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 12    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:9d21 | 17aa:5062 | Intel            | Sunrise Point-LP PMC                 | 12    |            | [8257D11669](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S0PY04/60067DC63CDD/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/8257D11669>) |
| 8086:a121 | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [226F25A086](<Desktop/Dell/OptiPlex/OptiPlex 7040/DD40E35F79F7/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/226F25A086>) |
| 8086:a121 | 1028:06bb | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [C51A264E20](<Desktop/Dell/OptiPlex/OptiPlex 3040/3E96FED82A87/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C51A264E20>) |
| 8086:a121 | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [7A7DD659C8](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/AAEB268489C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7A7DD659C8>) |
| 8086:a121 | 1849:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [7CC4B63834](<Desktop/ASRock/H110/H110 Pro BTC+/CB21DA586B1D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CC4B63834>) |
| 8086:9d21 | 17aa:5053 | Intel            | Sunrise Point-LP PMC                 | 11    |            | [7D7FA2BBC9](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FMS06V00/672ABD4473C3/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/7D7FA2BBC9>) |
| 8086:a2a1 | 1028:07a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 11    |            | [22A1B812F8](<Desktop/Dell/OptiPlex/OptiPlex 7050/CB83CBBB388D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/22A1B812F8>) |
| 8086:a121 | 1028:06ba | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [82F4B97203](<Desktop/Dell/OptiPlex/OptiPlex 5040/641267472D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/82F4B97203>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [78975E45B7](<Desktop/Thomas-Krenn.AG/P10S-M/P10S-M Series/A864089E016F/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/78975E45B7>) |
| 8086:4def |           | Intel            | Jasper Lake Shared SRAM Controller   | 9     |            | [88DE48013C](<Notebook/Intel/Jasper/Jasper Lake Client Platform/443F4759AD66/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/88DE48013C>) |
| 8086:9d21 | 103c:8079 | Intel            | Sunrise Point-LP PMC                 | 9     |            | [92C676E033](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/BA8494C9E0E5/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/92C676E033>) |
| 8086:a3a1 | 1043:8694 | Intel            | Cannon Lake PCH Power Management ... | 9     |            | [A3F77B82CC](<Desktop/ASUSTek Computer/PRO/PRO B460M-C/9D195AD59D5D/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/A3F77B82CC>) |
| 10de:03e2 | 1849:03e2 | Nvidia           | MCP61 Host Bridge                    | 8     |            | [04F43C3D70](<Desktop/ASRock/N68-S/N68-S UCC/59DCE7CA2B79/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/04F43C3D70>) |

### Modem (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:266d | 1014:0574 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 3     |            | [6FD6FD89C5](<Notebook/IBM/ThinkPad/ThinkPad R52 185869G/DED57F076B3E/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/6FD6FD89C5>) |
| 1039:7013 | 1043:1816 | Silicon Integ... | AC'97 Modem Controller               | 1     |            | [83106A58EF](<Notebook/ASUSTek Computer/A/A9T/CD438D683462/FREEBSD-13.0-P4/13.0-RELEASE-P4/I386/83106A58EF>) |
| 1039:7013 | 14c0:0012 | Silicon Integ... | AC'97 Modem Controller               | 1     |            | [56A5581907](<Notebook/Acer/TravelMate/TravelMate 270/A6730E9E5FB4/FREEBSD-12.1-P10/12.1-RELEASE-P9/I386/56A5581907>) |
| 1057:3052 | 1057:3020 | Motorola         | SM56 Data Fax Modem                  | 1     |            | [96A8673B26](<Desktop/Hewlett-Packard/Compaq/Compaq 500B Microtower/7E9B580A3747/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/96A8673B26>) |
| 10b9:5457 | 103c:0850 | ULi Electronics  | M5457 AC'97 Modem Controller         | 1     |            | [B7C0CB252F](<Notebook/Hewlett-Packard/nx/nx9010/C0E10A77D690/FREEBSD-12.1-P10/12.1-RELEASE-P9/I386/B7C0CB252F>) |
| 8086:2486 | 144f:1050 | Intel            | 82801CA/CAM AC'97 Modem Controller   | 1     |            | [41E40C653E](<Notebook/Gateway/Solo/Solo 450/3E11C9EAD72B/FREEBSD-12.2-P4/12.2-RELEASE-P4/I386/41E40C653E>) |
| 8086:24c6 | 1014:0524 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 1     |            | [DFC9B64DA2](<Notebook/IBM/ThinkPad/ThinkPad T40 23737CG/24E5DFFD7536/FREEBSD-12.3-P7/12.3-RELEASE-P6/I386/DFC9B64DA2>) |
| 8086:24c6 | 1014:0559 | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 1     |            | [ACF931A3E0](<Notebook/IBM/ThinkPad/ThinkPad T42 2374K46/696337B58774/FREEBSD-13.0-P2/13.0-RELEASE-P1/I386/ACF931A3E0>) |
| 8086:24c6 | 104d:818c | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 1     |            | [F2F3923EA6](<Notebook/Sony/VGN-S/VGN-S150/194677ED6A48/FREEBSD-13.0-CURRENT/13.0-CURRENT/I386/F2F3923EA6>) |
| 8086:24c6 | 10f7:834b | Intel            | 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4... | 1     |            | [F6EC2858A5](<Notebook/Matsushita Electric Industrial/CF-T2/CF-T2BW1AXR/C85EB722BC8F/FREEBSD-14.0-CURRENT/14.0-CURRENT/I386/F6EC2858A5>) |
| 8086:24d6 | 1179:0001 | Intel            | 82801EB/ER (ICH5/ICH5R) AC'97 Mod... | 1     |            | [6A920E9C8A](<Notebook/Toshiba/Satellite/Satellite P25/AE04E5C13B2D/FREEBSD-13.0-P11/13.0-RELEASE-P11/I386/6A920E9C8A>) |
| 8086:266d | 1014:0576 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 1     |            | [5FD9A63834](<Notebook/IBM/ThinkPad/ThinkPad T43 18714AG/A6C6FCC9536B/FREEBSD-13.1-P2/13.1-RELEASE-P2/I386/5FD9A63834>) |
| 8086:266d | 14f1:5423 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 1     |            | [D2CBB1F229](<Notebook/Dell/Latitude/Latitude D610/65F95AF4AC23/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/D2CBB1F229>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 62    |            | [1CCA4A556D](<Notebook/Deciso/OPNsense/OPNsense Appliance/2DD46B265269/OPNSENSE-23.1.1/13.1-RELEASE-P7/AMD64/1CCA4A556D>) |
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 14    |            | [B686FDF1C1](<Desktop/Protectli/FW/FW6/AA9E145E9412/OPNSENSE-22.7/13.1-RELEASE/AMD64/B686FDF1C1>) |
| 14e4:1570 | 14e4:1570 | Broadcom         | 720p FaceTime HD Camera              | 11    |            | [5234A39100](<Notebook/Apple/MacBookPro14/MacBookPro14,1/E5CBB76DCE97/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/5234A39100>) |
| 1022:15e2 | 1849:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 7     |            | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15e2 | 17aa:5125 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 5     |            | [AF190C38E9](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS0HN1N/FFA6D6E4D3C7/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/AF190C38E9>) |
| 1022:15e2 | 17aa:3836 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     |            | [4C83122CC0](<Notebook/Lenovo/Yoga/Yoga Slim 7 Pro 14ACH5 O 82N5/C4F4168282ED/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/4C83122CC0>) |
| 1022:15e2 | 17aa:5097 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     |            | [278A2A11CD](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/278A2A11CD>) |
| 1022:15e2 | 1d05:109f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     |            | [5EDF8A1BEF](<Notebook/TUXEDO/Pulse/Pulse 14 Gen1/B37BF57882B7/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/5EDF8A1BEF>) |
| 1022:15e2 | 1558:a500 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     |            | [E6AD419F5E](<Notebook/TUXEDO/Aura/Aura 15 Gen1/1A68AD0FF8B9/GHOSTBSD-23.01.13/13.1-STABLE/AMD64/E6AD419F5E>) |
| 1022:15e2 | 17aa:5082 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     |            | [CF5F498572](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 1 20UF000QRT/28FFDBA7F5C3/FREEBSD-13.1/13.1-RELEASE/AMD64/CF5F498572>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     |            | [3454B5492B](<Notebook/AZW/BT3/BT3 PRO/8FB6E0960427/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/3454B5492B>) |
| 1022:15e2 | 1025:142b | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [AA89C48CB7](<Notebook/Acer/Swift/Swift SF314-42/98026F7F98B8/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AA89C48CB7>) |
| 1022:15e2 | 1028:0a12 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [EAD2595782](<Notebook/Dell/Inspiron/Inspiron 3505/FD4D73324C8E/GHOSTBSD-22.07.16/13.1-STABLE/AMD64/EAD2595782>) |
| 1022:15e2 | 103c:8522 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [9CC3FAA610](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/9A7311DE9B92/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/9CC3FAA610>) |
| 1022:15e2 | 103c:85e0 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [E7B40F6E3B](<Notebook/Hewlett-Packard/Laptop/Laptop 14-dk0xxx/60E15DE8A8F4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E7B40F6E3B>) |
| 1022:15e2 | 103c:8730 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [C6944AFE69](<Notebook/Hewlett-Packard/ProBook/ProBook 455 G7/54DBBDB85625/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/C6944AFE69>) |
| 1022:15e2 | 103c:8786 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [19F307FF6D](<Notebook/Hewlett-Packard/OMEN/OMEN Laptop 15-en0xxx/99830226F687/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/19F307FF6D>) |
| 1022:15e2 | 103c:87b1 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [B8408CB369](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec1xxx/447033DB0DB6/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/B8408CB369>) |
| 1022:15e2 | 103c:88dd | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [7859F220B9](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec2xxx/32343F8FB2CF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7859F220B9>) |
| 1022:15e2 | 1043:115f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [2048FF5F71](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX325UA_UM325UA/49BFF737ADD5/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/2048FF5F71>) |
| 1022:15e2 | 17aa:32e1 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [820B3D1A1B](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s Gen 2 11R8000JUS/C14D7D997EB5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/820B3D1A1B>) |
| 1022:15e2 | 17aa:381c | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [21398109DC](<Notebook/Lenovo/Legion/Legion 5 15ARH05 82B5/9065FFB3AD54/FREEBSD-13.1/13.1-RELEASE/AMD64/21398109DC>) |
| 1022:15e2 | 17aa:3838 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [4F31F81571](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ACH6 82K2/F2EDB3DDA79E/GHOSTBSD-22.08.23/13.1-STABLE/AMD64/4F31F81571>) |
| 1022:15e2 | 17aa:5081 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [D910C79D75](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y1CTO1WW/5E03AED6E452/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D910C79D75>) |
| 1022:15e2 | 17aa:5126 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [D7812A2905](<Notebook/Lenovo/ThinkPad/ThinkPad X395 20NL000GPG/878AD42630E7/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D7812A2905>) |
| 1022:15e2 | 1d05:115d | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [8083410C50](<Notebook/SLIMBOOK/PROX-AMD/PROX-AMD5/EBC51BB666AB/HELLOSYSTEM-0.8.0/13.1-RELEASE-P3/AMD64/8083410C50>) |
| 1022:15e2 | 1e21:1043 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [C176577762](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506II_FA506II/6CEA289E0B55/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/C176577762>) |
| 1022:15e2 | 1ec9:3e3a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [CED12F0B41](<Notebook/HUAWEI/CREM-WXX/CREM-WXX9/2FA12EEB45B2/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/CED12F0B41>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     |            | [2ECB6FABA3](<Mini Pc/AMI/Aptio/Aptio CRB/FEA9A2F7C9FB/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2ECB6FABA3>) |
| 1022:15e2 | 1025:134d | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [1AC21E1660](<Notebook/Acer/Aspire/Aspire A315-42/DE5FD26538FB/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1AC21E1660>) |
| 1022:15e2 | 1025:1456 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [7FB743C654](<Notebook/Acer/Aspire/Aspire A315-23/F20A633E5003/FREEBSD-13.0/13.0-RELEASE/AMD64/7FB743C654>) |
| 1022:15e2 | 1025:1524 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [991F67362F](<Notebook/Acer/Aspire/Aspire A715-42G/87795F16AC00/FREEBSD-13.1-RC6/13.1-RC6/AMD64/991F67362F>) |
| 1022:15e2 | 1028:09f5 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [9933A09C4F](<Notebook/Dell/G5/G5 5505/919E52ABE5A8/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/9933A09C4F>) |
| 1022:15e2 | 1028:0a79 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [EF6D4EE660](<Notebook/Dell/Vostro/Vostro 5415/1C3D260A91E2/FREEBSD-13.1/13.1-RELEASE/AMD64/EF6D4EE660>) |
| 1022:15e2 | 1028:0ab4 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [B480A98B22](<Notebook/Dell/Inspiron/Inspiron 15 3515/7BE55D17C0FF/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/B480A98B22>) |
| 1022:15e2 | 103c:8433 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [5A242D9C9E](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0CFBD160A1EE/FREEBSD-12.2/12.2-RELEASE/AMD64/5A242D9C9E>) |
| 1022:15e2 | 103c:8523 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:15e2 | 103c:85b3 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [ECF07AD5FE](<Notebook/Hewlett-Packard/Laptop/Laptop 17-ca1xxx/17899E306221/FREEBSD-12.2-P2/12.2-RELEASE/AMD64/ECF07AD5FE>) |
| 1022:15e2 | 103c:876e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [EEC9546431](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 13-ay0xxx/4A78C43B26DF/FREEBSD-13.1-P1/13.1-RELEASE/AMD64/EEC9546431>) |
| 1022:15e2 | 103c:87b0 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [3C11FC31B2](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec1xxx/E24767B1152C/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3C11FC31B2>) |
| 1022:15e2 | 103c:87b7 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [920A2FE2E9](<Notebook/Hewlett-Packard/Laptop/Laptop 14s-fq0xxx/0E6414342B08/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/920A2FE2E9>) |
| 1022:15e2 | 103c:887c | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [1603F38C4C](<Notebook/Hewlett-Packard/Laptop/Laptop 14s-fq1xxx/B1AAF63EEE99/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/1603F38C4C>) |
| 1022:15e2 | 103c:888a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:15e2 | 103c:88ed | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [B2ED608DA5](<Notebook/Hewlett-Packard/Victus/Victus by Laptop 16-e0xxx/EFBDDFE44A6B/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/B2ED608DA5>) |
| 1022:15e2 | 103c:8905 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [F9851A3257](<Notebook/Hewlett-Packard/255/255 G8 Notebook PC/A80D2FBEF333/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/F9851A3257>) |
| 1022:15e2 | 1043:1862 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [CF360A6098](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X515UA_M515UA/E0D904EE5AF7/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/CF360A6098>) |
| 1022:15e2 | 1043:1d42 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [20CDC9D999](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA402RJ_GA402RJ/8B17C1C0752C/FREEBSD-13.0/13.0-RELEASE/AMD64/20CDC9D999>) |
| 1022:15e2 | 1458:1000 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [817CB3E603](<Desktop/Gigabyte Technology/BSRE/BSRE-1605/493093EBE60A/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/817CB3E603>) |
| 1022:15e2 | 1462:12b5 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [1868573E9A](<Notebook/MSI/Bravo/Bravo 15 A4DDR/3C4CE3C2FC4B/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1868573E9A>) |
| 1022:15e2 | 1462:1310 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [AFDA1BCF60](<Notebook/MSI/Modern/Modern 15 A5M/C1DBD6A7226C/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/AFDA1BCF60>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:15f3 |           | Intel            | Ethernet Controller I225-V           | 215   | igc        | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 175   | em         | [12AC44CBF7](<Desktop/Others/Others/Others/B6CD8CD35969/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/12AC44CBF7>) |
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 155   | igb        | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 109   | igb        | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 8086:125c |           | Intel            | Ethernet Controller I226-V           | 88    | igc        | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 10ec:8168 | 1734:11ff | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 80    | re         | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 75    | re         | [2E40DF5A32](<Desktop/WYSE/Z/Z CLASS/76E6DE34A38F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E40DF5A32>) |
| 8086:1521 | 8086:5001 | Intel            | I350 Gigabit Network Connection      | 74    | igb        | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 73    | re         | [34CF4827D7](<Desktop/Hardkernel/ODROID-H/ODROID-H3/174DBB630022/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/34CF4827D7>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 71    | igb        | [2B2B508432](<Server/Intel/S1200/S1200RP_SE/4DF73AF97478/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/2B2B508432>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 68    | re         | [BD041B2E20](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G1 SFF/8E20AC0EE415/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/BD041B2E20>) |
| 8086:10bc | 103c:704b | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 59    | em         | [2E40DF5A32](<Desktop/WYSE/Z/Z CLASS/76E6DE34A38F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E40DF5A32>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 59    | igb        | [FBFF29A62A](<Desktop/ASRock/X470/X470 Gaming K4/FFA88723BDD5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/FBFF29A62A>) |
| 8086:150e | 103c:1780 | Intel            | 82580 Gigabit Network Connection     | 58    | igb        | [A8B5C70376](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/CFD7F415A438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/A8B5C70376>) |
| 8086:10e8 | 8086:a02c | Intel            | 82576 Gigabit Network Connection     | 56    | igb        | [E975D67484](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E975D67484>) |
| 1022:1458 | 1022:1458 | AMD              | Family 17h Processor 10 Gb Ethern... | 54    | ax         | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 8086:1521 |           | Intel            | I350 Gigabit Network Connection      | 50    | igb        | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 46    | em         | [986F18FA08](<Desktop/Dell/OptiPlex/OptiPlex 9010/1A8752C8E9E4/OPNSENSE-22.1.10/13.0-STABLE/AMD64/986F18FA08>) |
| 8086:15e5 |           | Intel            | Ethernet Connection X553 1GbE        | 46    | ix         | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 14e4:163b | 1028:04dd | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 44    | bce        | [E975D67484](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E975D67484>) |
| 8086:105e | 8086:125e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 44    | em         | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:1572 |           | Intel            | Ethernet Controller X710 for 10Gb... | 41    | ixl        | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:1536 |           | Intel            | I210 Gigabit Fiber Network Connec... | 39    | igb        | [86C132C242](<Desktop/Others/Others/Others/23C67704FCED/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/86C132C242>) |
| 8086:15e4 |           | Intel            | Ethernet Connection X553 1GbE        | 39    | ix         | [86C132C242](<Desktop/Others/Others/Others/23C67704FCED/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/86C132C242>) |
| 10ec:8168 | 103c:8103 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 38    | re         | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 10ec:8168 | 1028:0612 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 37    | re         | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:1533 | 15bb:30e0 | Intel            | I210 Gigabit Network Connection      | 36    | igb        | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 34    | nfe        | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:15ac | 15d9:15ac | Intel            | Ethernet Connection X552 10 GbE SFP+ | 32    | ix         | [E766835AB5](<Server/Supermicro/Super/Super Server/ACA476C2CF6E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E766835AB5>) |
| 8086:10c9 | 8086:a02f | Intel            | 82576 Gigabit Network Connection     | 31    | igb        | [27E756F63D](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/27E756F63D>) |
| 8086:1f41 | 15d9:1f41 | Intel            | Ethernet Connection I354             | 31    | igb        | [D179977442](<Mini Pc/Supermicro/A1/A1SAi/DEFEE5630512/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D179977442>) |
| 8086:10bc | 8086:11bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 30    | em         | [84AD5CFA43](<Desktop/Dell/OptiPlex/OptiPlex 7010/60064609B838/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/84AD5CFA43>) |
| 8086:15b8 | 1043:8672 | Intel            | Ethernet Connection (2) I219-V       | 29    | em         | [6F4B514959](<Desktop/ASUSTek Computer/STRIX/STRIX Z270F GAMING/9FCEC82B3F4D/FREEBSD-13.1/13.1-RELEASE/AMD64/6F4B514959>) |
| 10ec:8169 | 10ec:8169 | Realtek Semic... | RTL8169 PCI Gigabit Ethernet Cont... | 28    | re         | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 27    | ix         | [08B02DFC2D](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/08B02DFC2D>) |
| 14e4:165f | 1028:1f5b | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 26    | bge        | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:1502 | 15d9:1502 | Intel            | 82579LM Gigabit Network Connectio... | 26    | em         | [96ACEB6D32](<Desktop/Supermicro/X9/X9SCL-X9SCM/1D10666FC295/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/96ACEB6D32>) |
| 8086:153a | 103c:1998 | Intel            | Ethernet Connection I217-LM          | 26    | em         | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 14e4:1639 | 103c:7055 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 25    | bce        | [B281EEC189](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/D6765403633D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/B281EEC189>) |
| 10ec:8168 | 1028:080c | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 24    | re         | [D6F24A2C50](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/A940BF140853/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D6F24A2C50>) |
| 10ec:8168 | 19da:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 24    | re         | [CB4C316A05](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.9/12.1-RELEASE-P19-HBSD/AMD64/CB4C316A05>) |
| 8086:10c9 | 1dcf:0319 | Intel            | 82576 Gigabit Network Connection     | 24    | igb        | [25528A00F3](<Desktop/Lenovo/ThinkCentre/ThinkCentre M91p 7033A2G/E4BF25D116F4/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/25528A00F3>) |
| 8086:10bc | 8086:10bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 23    | em         | [3D912F92AA](<Desktop/Fujitsu/FUTRO/FUTRO S920/A1AC5CC7301E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3D912F92AA>) |
| 8086:10d6 | 8086:145a | Intel            | 82575GB Gigabit Network Connection   | 23    | igb        | [F3C3E6ECB5](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8S16X0J/968E3838A942/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F3C3E6ECB5>) |
| 8086:154d | 8086:7b11 | Intel            | Ethernet 10G 2P X520 Adapter         | 23    | ix         | [B0020C937B](<Desktop/Dell/OptiPlex/OptiPlex 7050/3C676EC0E951/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B0020C937B>) |
| 8086:15ad | 15d9:15ad | Intel            | Ethernet Connection X552/X557-AT ... | 23    | ix         | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 8086:1522 |           | Intel            | I350 Gigabit Fiber Network Connec... | 22    | igb        | [08B02DFC2D](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/08B02DFC2D>) |
| 8086:1528 | 8086:0001 | Intel            | Ethernet Controller 10-Gigabit X5... | 22    | ix         | [FA12EA67EB](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/837435F7D2A1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/FA12EA67EB>) |
| 8086:15f3 | 1043:87d2 | Intel            | Ethernet Controller I225-V           | 22    | igc        | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 8086:1516 | 8086:12b2 | Intel            | 82580 Gigabit Network Connection     | 21    | igb        | [904FDE472A](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/904FDE472A>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 135   | iwlwifi    | [6E97A003EC](<Notebook/Acer/Nitro/Nitro AN515-54/753EE6D71A9C/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/6E97A003EC>) |
| 8086:0085 | 8086:1311 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 85    | iwn        | [2FF46D6B7C](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252G8/0189D3C3009B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/2FF46D6B7C>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 77    | iwm        | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 75    | iwm        | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 68    | iwm        | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 52    | iwm        | [80DD48BCA9](<Notebook/Lenovo/ThinkPad/ThinkPad P52s 20LBS0FH00/BD0ED8EF7DB5/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/80DD48BCA9>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 49    | iwm        | [AF190C38E9](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS0HN1N/FFA6D6E4D3C7/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/AF190C38E9>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 44    | iwm        | [9545F36DEE](<Notebook/Notebook/N2/N2x0WU/2AD926AC2B39/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9545F36DEE>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 34    | iwlwifi    | [F07E092146](<Desktop/Techvision/TVI7309/TVI7309X/432837343A25/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F07E092146>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 33    | iwm        | [B2784F4025](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/B2784F4025>) |
| 8086:088e | 8086:4060 | Intel            | Centrino Advanced-N 6235             | 32    | iwn        | [D7B171D0BB](<Desktop/Others/Others/Others/E869214B6318/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/D7B171D0BB>) |
| 8086:08b2 | 8086:c270 | Intel            | Wireless 7260                        | 32    | iwm        | [7750C38CD0](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ005SUS/DC9FF593E3E2/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/7750C38CD0>) |
| 8086:095b | 8086:5210 | Intel            | Wireless 7265                        | 29    | iwm        | [06E5309C55](<Notebook/Lenovo/ThinkPad/ThinkPad L450 20DSS1S402/0FD1E037978C/HELLOSYSTEM-0.8.0/13.1-RELEASE-P6/AMD64/06E5309C55>) |
| 8086:24f3 | 8086:0130 | Intel            | Wireless 8260                        | 29    | iwm        | [56FA0D4656](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2BR00/E2372EFC6D66/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/56FA0D4656>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 28    | rtw        | [5AB1DADBAB](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F54ADC493621/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5AB1DADBAB>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 28    | iwm        | [9AEC93F312](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/B565A5A319EC/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/9AEC93F312>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 27    | ath        | [D58C178C51](<Notebook/ASUSTek Computer/K84/K84L/22162705C664/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/D58C178C51>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 27    | iwm        | [2E3026E0FD](<Desktop/Gigabyte Technology/Z390/Z390 I AORUS PRO WIFI/CB785A37BC49/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E3026E0FD>) |
| 168c:002a | 168c:3099 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 26    | ath        | [0D1561FEA9](<Desktop/PC Engines/apu/apu4/7545D6E348E1/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0D1561FEA9>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 24    | iwm        | [E5A43DD311](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4286CTO/3C1927176580/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/E5A43DD311>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 24    | iwm        | [0ADF0CA671](<Desktop/ZOTAC/Others/Others/6E70FB5A2725/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0ADF0CA671>) |
| 8086:24f3 | 8086:1010 | Intel            | Wireless 8260                        | 24    | iwm        | [7BE10E8844](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/35A52D87DAA0/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/7BE10E8844>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 24    | iwm        | [C22EE2E279](<Desktop/AZW/GK/GK55/8FD2B3239B52/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C22EE2E279>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 24    | iwm        | [0C9CF4E002](<Notebook/Lenovo/IdeaPad/IdeaPad Y700-15ISK 80NV/2BD0319875C3/FREEBSD-13.2-PRERELEASE/13.2-PRERELEASE/AMD64/0C9CF4E002>) |
| 8086:24f3 | 8086:0010 | Intel            | Wireless 8260                        | 23    | iwm        | [FF6DDB74BB](<Notebook/Hewlett-Packard/ZBook/ZBook 15 G3/39095FD3D22D/FURYBSD-13.1-P5/13.1-RELEASE-P3/AMD64/FF6DDB74BB>) |
| 8086:24fd | 8086:0050 | Intel            | Wireless 8265 / 8275                 | 23    | iwm        | [01F5F21B76](<Notebook/Dell/Precision/Precision 7720/A27F623F9015/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/01F5F21B76>) |
| 168c:003c |           | Qualcomm Atheros | QCA986x/988x 802.11ac Wireless Ne... | 22    |            | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:31dc | 8086:0034 | Intel            | Gemini Lake PCH CNVi WiFi            | 21    | iwm        | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 20    | iwlwifi    | [88491D298E](<Notebook/Google/Kohaku/Kohaku/5F2605C0CFF4/FREEBSD-13.1/13.1-RELEASE/AMD64/88491D298E>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 20    | iwm        | [ACFF807555](<Notebook/Hewlett-Packard/ProBook/ProBook 450 G2/C7626B6ED29D/FREEBSD-13.1/13.1-RELEASE/AMD64/ACFF807555>) |
| 168c:0036 | 1028:020c | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 19    | ath        | [A180A149F5](<Notebook/Dell/Latitude/Latitude 3540/E7764A5A3B91/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/A180A149F5>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 19    |            | [14F174BD7C](<Mini Pc/BESSTAR Tech/GK/GK41/46F6D804D9F8/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/14F174BD7C>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 19    | iwm        | [9954516F1A](<Mini Pc/Intel/NUC5i7RYB/NUC5i7RYB H73774-101/9E7CEC011874/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/9954516F1A>) |
| 8086:24f3 | 8086:0050 | Intel            | Wireless 8260                        | 19    | iwm        | [E08C408CED](<Desktop/Lenovo/ThinkCentre/ThinkCentre M920s 10SJ0011US/88754028E03C/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/E08C408CED>) |
| 8086:a0f0 | 8086:0074 | Intel            | Wi-Fi 6 AX201                        | 18    | iwlwifi    | [80F6445F54](<Notebook/Star Labs/StarBook/StarBook/2BCE064BBD99/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/80F6445F54>) |
| 8086:0084 | 8086:1315 | Intel            | Centrino Wireless-N 1000 [Condor ... | 17    | iwn        | [9F9CB3E201](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537B94/CDBD8C566708/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9F9CB3E201>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 17    | iwm        | [5787EDA5AC](<Desktop/Wortmann AG/TERRA_PC/TERRA_PC/A38917BDA879/OPNSENSE-23.7/13.1-RELEASE-P6/AMD64/5787EDA5AC>) |
| 8086:3165 | 8086:4410 | Intel            | Wireless 3165                        | 17    | iwm        | [C6946F5300](<Desktop/Dell/Inspiron/Inspiron 3880/DECD973F3D35/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C6946F5300>) |
| 8086:4238 | 8086:1111 | Intel            | Centrino Ultimate-N 6300             | 17    | iwn        | [124B3BDB95](<Notebook/Lenovo/ThinkPad/ThinkPad X230 2324A14/CFC3AD368BAB/FREEBSD-13.1/13.1-RELEASE/AMD64/124B3BDB95>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 16    | ath        | [A629BF3445](<Desktop/Dell/Inspiron/Inspiron 3470/F855695C070F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A629BF3445>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 16    | iwm        | [ACA9E2885D](<Mini Pc/Intel/NUC7i3BNB/NUC7i3BNB J22859-307/2278924F334A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/ACA9E2885D>) |
| 14e4:4331 | 14e4:4331 | Broadcom         | BCM4331 802.11a/b/g/n                | 15    | bwn_pci    | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 14e4:4359 | 14e4:05e2 | Broadcom         | BCM43228 802.11a/b/g/n               | 15    |            | [0480CE43F2](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G1/620307FCA7D4/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/0480CE43F2>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 15    | ath        | [227C78F3C1](<Desktop/MSI/MS/MS-7788/BD1A816BB8CA/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/227C78F3C1>) |
| 8086:0082 | 8086:1321 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 15    | iwn        | [CB7B02C421](<Notebook/Dell/Latitude/Latitude E6420/814FB112DD83/FREEBSD-13.1/13.1-RELEASE/AMD64/CB7B02C421>) |
| 8086:4237 | 8086:1211 | Intel            | PRO/Wireless 5100 AGN [Shiloh] Ne... | 15    | iwn        | [3C404C9D20](<Notebook/Hewlett-Packard/EliteBook/EliteBook 2730p/B68F2E5FEB46/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3C404C9D20>) |
| 8086:4239 | 8086:1311 | Intel            | Centrino Advanced-N 6200             | 15    | iwn        | [D732F4D6C4](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8440p/4ABF7CCD3BA6/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/D732F4D6C4>) |
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 14    | bwn_pci    | [556E872FFE](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/556E872FFE>) |
| 8086:0082 | 8086:1301 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 14    | iwn        | [1A4897CB53](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570p/6FBB1F806232/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1A4897CB53>) |
| 8086:06f0 | 8086:0074 | Intel            | Comet Lake PCH CNVi WiFi             | 14    | iwlwifi    | [3E58DA5C30](<Notebook/Monster/ABRA/ABRA A7 V11.2/71CCA11D28B6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3E58DA5C30>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 871   | igb        | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 523   | re         | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:157b |           | Intel            | I210 Gigabit Network Connection      | 308   | igb        | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 225   | re         | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 10ec:8168 | 1849:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 176   | re         | [5D0F6C2276](<Desktop/ASRock/Q1900/Q1900M/5C14E92D5780/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5D0F6C2276>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 138   | em         | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 138   | igb        | [C9DDD32406](<Server/Supermicro/Super/Super Server/A912B2977FCE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/C9DDD32406>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 137   | em         | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 117   | re         | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 114   | re         | [1C8295549C](<Desktop/Intel/DP55WB/DP55WB AAE64798-207/2CE77B662F6E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/1C8295549C>) |
| 8086:1502 | 17aa:21ce | Intel            | 82579LM Gigabit Network Connectio... | 56    | em         | [E5A43DD311](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4286CTO/3C1927176580/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/E5A43DD311>) |
| 8086:153a | 1028:05a4 | Intel            | Ethernet Connection I217-LM          | 55    | em         | [69DB0AC0A4](<Desktop/Dell/OptiPlex/OptiPlex 7020/C7649894A9FD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/69DB0AC0A4>) |
| 10ec:8168 | 1043:8505 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 54    | re         | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 8086:1502 | 17aa:21f3 | Intel            | 82579LM Gigabit Network Connectio... | 52    | em         | [2FF46D6B7C](<Notebook/Lenovo/ThinkPad/ThinkPad X230 23252G8/0189D3C3009B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/2FF46D6B7C>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 51    | re         | [6A15F7D4A1](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX PLUS R2.0/5AD7ACB63A8F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/6A15F7D4A1>) |
| 8086:150e | 8086:12a2 | Intel            | 82580 Gigabit Network Connection     | 51    | igb        | [D8C78B92A7](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4DBEA0F75A7B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D8C78B92A7>) |
| 10ec:8168 | 103c:213d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 46    | re         | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 8086:105e | 103c:7044 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 44    | em         | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 44    | igb        | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 41    | igb        | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 38    | igb        | [9CD4D2810A](<Desktop/Gigabyte Technology/GA-990X-Gaming/GA-990X-Gaming SLI-CF/4C8CFDE62DD1/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9CD4D2810A>) |
| 10ec:8139 | 10ec:8139 | Realtek Semic... | RTL-8100/8101L/8139 PCI Fast Ethe... | 36    | rl         | [5FC3D86BAC](<Desktop/ASUSTek Computer/A8/A8N-E/8A09F644DB88/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5FC3D86BAC>) |
| 8086:105e | 8086:135e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 36    | em         | [6283151877](<Server/HPE/MM10/MM10Gen9/C96A2A643802/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6283151877>) |
| 8086:105e | 8086:115e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 34    | em         | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:1521 | 8086:0002 | Intel            | I350 Gigabit Network Connection      | 34    | igb        | [820B3D1A1B](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s Gen 2 11R8000JUS/C14D7D997EB5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/820B3D1A1B>) |
| 10ec:8168 | 1043:8554 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 32    | re         | [27EA626000](<Desktop/ASUSTek Computer/All/All Series/3184501520E4/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/27EA626000>) |
| 8086:1502 | 1028:047e | Intel            | 82579LM Gigabit Network Connectio... | 32    | em         | [B8DC69069D](<Desktop/Dell/OptiPlex/OptiPlex 790/E7BEAAFD5268/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/B8DC69069D>) |
| 14e4:165f | 103c:2133 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 31    | bge        | [409D119307](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/36E7C68AA33D/FREEBSD-12.4/12.4-RELEASE/AMD64/409D119307>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 29    | ixl        | [09E5FC33AD](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/01D46C98F610/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/09E5FC33AD>) |
| 8086:1528 | 15d9:1528 | Intel            | Ethernet Controller 10-Gigabit X5... | 28    | ix         | [64D844777A](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/64D844777A>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 27    | bge        | [AACCB6DF1A](<Notebook/Apple/MacBookPro9/MacBookPro9,2/C8ACF1830354/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/AACCB6DF1A>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 26    | em         | [6A91635684](<Desktop/exone/X7/X7SPA-HF/881B5CC94BD2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6A91635684>) |
| 8086:1533 | 1849:1533 | Intel            | I210 Gigabit Network Connection      | 25    | igb        | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 8086:156f | 17aa:2233 | Intel            | Ethernet Connection I219-LM          | 23    | em         | [56FA0D4656](<Notebook/Lenovo/ThinkPad/ThinkPad T460s 20FAS2BR00/E2372EFC6D66/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/56FA0D4656>) |
| 8086:15a2 | 17aa:2226 | Intel            | Ethernet Connection (3) I218-LM      | 23    | em         | [10619AC217](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLS5BU00/75926791E302/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/10619AC217>) |
| 8086:10ea | 17aa:2153 | Intel            | 82577LM Gigabit Network Connection   | 22    | em         | [9F9CB3E201](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537B94/CDBD8C566708/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9F9CB3E201>) |
| 8086:107c | 8086:1376 | Intel            | 82541PI Gigabit Ethernet Controller  | 20    | em         | [9C526B27DD](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/93F9F29A0DC5/OPNSENSE-22.1.10/13.0-STABLE/AMD64/9C526B27DD>) |
| 8086:10fb | 8086:0003 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 20    | ix         | [0E5ED7F4DE](<Desktop/Jingsha/x79-P3/x79-P3 by xUz/7C3BC7FA7C2C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0E5ED7F4DE>) |
| 10ec:8168 | 1043:859e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 19    | re         | [07982549AC](<Desktop/ASUSTek Computer/All/All Series/B3B28DAE60A0/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/07982549AC>) |
| 11ab:4364 | 1043:81f8 | Marvell Techn... | 88E8056 PCI-E Gigabit Ethernet Co... | 19    | mskc       | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 14e4:1639 | 1028:0235 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 19    | bce        | [5D6BABDA3E](<Server/Dell/PowerEdge/PowerEdge R710/209AA94D6139/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/5D6BABDA3E>) |
| 8086:15b8 | 1458:e000 | Intel            | Ethernet Connection (2) I219-V       | 18    | em         | [A15EEE8687](<Desktop/Gigabyte Technology/H270/H270-HD3/FE961B3E9735/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A15EEE8687>) |
| 10ec:8168 | 1043:200f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | re         | [431AD10AB2](<Notebook/ASUSTek Computer/X455/X455LJ/388EF8EA953C/FREEBSD-13.1/13.1-RELEASE/AMD64/431AD10AB2>) |
| 14e4:165f | 103c:22e8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 17    | bge        | [F1B45790D4](<Desktop/HPE/ProLiant/ProLiant ML30 Gen10/93F91BA1C4A9/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/F1B45790D4>) |
| 15b3:1003 | 15b3:0055 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 17    | mlx4_core  | [8EB068A097](<Desktop/ASRock/X570/X570 Taichi/627244F84DF9/FREEBSD-13.1/13.1-RELEASE/AMD64/8EB068A097>) |
| 8086:150e | 1734:11a8 | Intel            | 82580 Gigabit Network Connection     | 17    | igb        | [B077E8E71A](<Server/Fujitsu/PRIMERGY/PRIMERGY TX120 S3/23E5EBA2A16E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/B077E8E71A>) |
| 8086:15b7 |           | Intel            | Ethernet Connection (2) I219-LM      | 17    | em         | [6283151877](<Server/HPE/MM10/MM10Gen9/C96A2A643802/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6283151877>) |
| 8086:15bc | 1043:8672 | Intel            | Ethernet Connection (7) I219-V       | 17    | em         | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 10ec:8125 | 1849:8125 | Realtek Semic... | RTL8125 2.5GbE Controller            | 16    | re         | [4EBEAC2699](<Desktop/ASRock/H570/H570M-ITX-ac/7252CA256A2E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/4EBEAC2699>) |
| 8086:155a | 17aa:2214 | Intel            | Ethernet Connection I218-LM          | 16    | em         | [7750C38CD0](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AQ005SUS/DC9FF593E3E2/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/7750C38CD0>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 257   | sdhci_pci  | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 87    | sdhci_pci  | [C22EE2E279](<Desktop/AZW/GK/GK55/8FD2B3239B52/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C22EE2E279>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 70    | sdhci_pci  | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:4df8 | 8086:7270 | Intel            | SD Host Controller                   | 60    | sdhci_pci  | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 45    | sdhci_pci  | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 14e4:16bc |           | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 35    | sdhci_pci  | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:31cc | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 27    | sdhci_pci  | [DF7A30FC45](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/53D0F9939362/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/DF7A30FC45>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 25    | sdhci_pci  | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 25    | sdhci_pci  | [C258B4972C](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/C258B4972C>) |
| 8086:9dc4 | 8086:7270 | Intel            | Cannon Point-LP SD Host Controller   | 24    | sdhci_pci  | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:9df5 | 8086:7270 | Intel            | BayHubTech Integrated SD controller  | 24    | sdhci_pci  | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:19db | 8086:7270 | Intel            | Atom Processor C3000 Series SD Ho... | 18    | sdhci_pci  | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | sdhci_pci  | [CFFEC30B6B](<Mini Pc/EXTRA Computer/exone/exone Business 5501/8D2CC3B43BC9/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/CFFEC30B6B>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | sdhci_pci  | [8537AC75A1](<Desktop/AAEON/UP-APL/UP-APL01/605633FC34DD/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8537AC75A1>) |
| 1180:0822 | 17aa:20c8 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 14    | sdhci_pci  | [67B2E8DB2B](<Notebook/Lenovo/ThinkPad/ThinkPad T61p 6457UN2/ABBAD64ECA84/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/67B2E8DB2B>) |
| 8086:5acc | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | sdhci_pci  | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | sdhci_pci  | [E9E179E9AC](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 832 ZMB/574A3DFD4C34/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E9E179E9AC>) |
| 8086:02c4 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS1: eMMC         | 10    | sdhci_pci  | [44B691E7B8](<Desktop/Protectli/VP/VP4650/6092756008BB/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/44B691E7B8>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | sdhci_pci  | [EBEDB51D2F](<Mini Pc/CompuLab/fitlet/fitlet2/66D2086CBC5D/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/EBEDB51D2F>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 8     | sdhci_pci  | [5C2047356D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/5C2047356D>) |
| 8086:31cc | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 8     | sdhci_pci  | [C30DD3FBCA](<Mini Pc/Intel Client Systems/NUC7/NUC7PJYH/CB2E3B8CA357/FREEBSD-13.2-BETA2/13.2-BETA2/AMD64/C30DD3FBCA>) |
| 1022:7806 | 1022:7806 | AMD              | FCH SD Flash Controller              | 7     | sdhci_pci  | [5BCD236C4A](<Notebook/Samsung Electronics/305E4/305E4A-305E5A-305E7A/116CFBBA835E/HELLOSYSTEM-0.8.1/13.1-RELEASE-P6/AMD64/5BCD236C4A>) |
| 1217:8221 | 1028:0493 | O2 Micro         | OZ600FJ0/OZ900FJ0/OZ600FJS SD/MMC... | 7     | sdhci_pci  | [CB7B02C421](<Notebook/Dell/Latitude/Latitude E6420/814FB112DD83/FREEBSD-13.1/13.1-RELEASE/AMD64/CB7B02C421>) |
| 197b:2381 | 17aa:212d | JMicron Techn... | Standard SD Host Controller          | 7     | sdhci_pci  | [CBA0FC2340](<Notebook/Lenovo/ThinkPad/ThinkPad L412 0585AD9/A37928EB0C1B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/CBA0FC2340>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | sdhci_pci  | [C3FFB2C87D](<Desktop/AMI/PEISIA/PEISIA E3845 VER1.0/F1AF209585D4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C3FFB2C87D>) |
| 8086:2294 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     | sdhci_pci  | [0ADF0CA671](<Desktop/ZOTAC/Others/Others/6E70FB5A2725/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0ADF0CA671>) |
| 8086:4dc4 | 8086:7270 | Intel            | Jasper Lake SCS1: eMMC Controller    | 7     | sdhci_pci  | [B815AE3950](<Desktop/GoWin Solution/R86/R86S/057DBA2F6645/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B815AE3950>) |
| 1180:e822 | 1179:0001 | Ricoh            | MMC/SD Host Controller               | 6     | sdhci_pci  | [10B85ECCAE](<Notebook/Toshiba/PORTEGE/PORTEGE R700/AC5712689798/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/10B85ECCAE>) |
| 1217:8221 | 1028:0534 | O2 Micro         | OZ600FJ0/OZ900FJ0/OZ600FJS SD/MMC... | 6     | sdhci_pci  | [B8F950DE05](<Notebook/Dell/Latitude/Latitude E6430/286A8E5F2DC1/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8F950DE05>) |
| 8086:02f5 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS3               | 6     | sdhci_pci  | [E467080570](<Notebook/Medion/E/E15415/B5081BB45457/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/E467080570>) |
| 8086:4dc4 |           | Intel            | Jasper Lake SCS1: eMMC Controller    | 6     | sdhci_pci  | [88DE48013C](<Notebook/Intel/Jasper/Jasper Lake Client Platform/443F4759AD66/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/88DE48013C>) |
| 8086:a375 | 103c:843f | Intel            | 300 Series Chipset Family SD Host... | 6     | sdhci_pci  | [23D8A9BDA7](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/BD57B07B0D05/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/23D8A9BDA7>) |
| 1022:7813 | 1022:7813 | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [8B9A301B47](<Desktop/M613/G420/G420N1WNS/19C20EF0FF54/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8B9A301B47>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | sdhci_pci  | [318A750368](<Notebook/Google/Edgar/Edgar/5B7B2DE88CCD/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/318A750368>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 5     | sdhci_pci  | [796FE84E29](<Desktop/Others/Others/Others/4F168F055C91/OPNSENSE-22.1.7/13.0-STABLE/AMD64/796FE84E29>) |
| 1180:e822 | 1028:040a | Ricoh            | MMC/SD Host Controller               | 4     | sdhci_pci  | [8C904D84E0](<Notebook/Dell/Latitude/Latitude E6410/D86C1197F0AC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/8C904D84E0>) |
| 1217:8321 | 1028:049b | O2 Micro         | OZ600RJ0/OZ900RJ0/OZ600RJS SD/MMC... | 4     | sdhci_pci  | [524AB094E1](<Notebook/Dell/Latitude/Latitude E5420/15C36179305C/FREEBSD-13.1/13.1-RELEASE/AMD64/524AB094E1>) |
| 1217:8520 | 1028:05be | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [70871CF070](<Notebook/Dell/Latitude/Latitude E6540/FB7DA94D59D1/FREEBSD-13.1/13.1-RELEASE/AMD64/70871CF070>) |
| 1217:8520 | 1028:05cb | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [03497B7B2A](<Notebook/Dell/Latitude/Latitude E7440/D5F7C41FF257/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/03497B7B2A>) |
| 1217:8520 | 1028:05cc | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [B7A834C4D0](<Notebook/Dell/Precision/Precision M4800/278DE0A5A86F/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B7A834C4D0>) |
| 1217:8621 | 17aa:5068 | O2 Micro         | SD/MMC Card Reader Controller        | 4     | sdhci_pci  | [BE311B6A34](<Notebook/Lenovo/ThinkPad/ThinkPad E580 20KSCTO1WW/FE16B0524669/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/BE311B6A34>) |
| 14e4:16bc | 1025:0504 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 4     | sdhci_pci  | [BD22FC8A49](<Notebook/Acer/Aspire/Aspire 5750G/1FF59E502D89/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/BD22FC8A49>) |
| 14e4:16bc | 1025:0775 | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 4     | sdhci_pci  | [3D62C50607](<Notebook/Acer/Aspire/Aspire E1-570/70AD51287914/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/3D62C50607>) |
| 8086:4df8 |           | Intel            | SD Host Controller                   | 4     | sdhci_pci  | [8C983F91E4](<Desktop/AWOW/AK/AK50/7E18C0CE25A5/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8C983F91E4>) |
| 8086:5acc | 1025:1084 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [D2652B76CF](<Notebook/Acer/Aspire/Aspire ES1-533/244A81EC59B3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/D2652B76CF>) |
| 8086:9d2b | 8086:9d2b | Intel            | Skylake-U/Y SCC: eMMC                | 4     | sdhci_pci  | [4130B19CFA](<Notebook/Google/Lars/Lars/CCB0F65C765F/FREEBSD-13.1/13.1-RELEASE/AMD64/4130B19CFA>) |
| 1022:7813 | 17aa:3801 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [6E31B5F45B](<Notebook/Lenovo/G40-45/G40-45 80E1/EA83D0EBE432/FREEBSD-13.1/13.1-RELEASE/AMD64/6E31B5F45B>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     |            | [FA57448331](<Desktop/Acer/Veriton/Veriton N2620G/A3AD7EE84FF2/HELLOSYSTEM-0.8.1/13.1-RELEASE-P6/AMD64/FA57448331>) |
| 1180:0822 | 1028:024d | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 3     | sdhci_pci  | [FDB3DE3036](<Notebook/Dell/Latitude/Latitude E4300/B023391CA6F2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/FDB3DE3036>) |
| 1180:e823 | 10f7:8338 | Ricoh            | PCIe SDXC/MMC Host Controller        | 3     | sdhci_pci  | [D129D929AC](<Notebook/Panasonic/CF-C1/CF-C1BWFAZ1M/B2A6BD13F362/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/D129D929AC>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:4da4 | 8086:7270 | Intel            | Jasper Lake SPI Controller           | 147   |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:4de8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 70    |            | [E09800B936](<Desktop/maiyunda/www.maiyunda.com/www.maiyunda.com/5F223CD2630E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E09800B936>) |
| 8086:4dea | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 67    |            | [E09800B936](<Desktop/maiyunda/www.maiyunda.com/www.maiyunda.com/5F223CD2630E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E09800B936>) |
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 49    |            | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:19e0 | 8086:7270 | Intel            | Atom Processor C3000 Series SPI C... | 37    |            | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 33    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 30    | ipmi       | [5D0701D0A8](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/B1E7272301E9/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/5D0701D0A8>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 30    |            | [6AC60B8104](<Desktop/Gigabyte Technology/B360/B360M-D2V/F8AFE9A62606/FREEBSD-13.1/13.1-RELEASE/AMD64/6AC60B8104>) |
| 8086:a324 | 1043:8694 | Intel            | Cannon Lake PCH SPI Controller       | 27    |            | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 26    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 25    |            | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:9dc5 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 24    | ig4iic     | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:9de8 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 24    | ig4iic     | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:9de9 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 24    | ig4iic     | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:a1a4 | 15d9:0986 | Intel            | C620 Series Chipset Family SPI Co... | 19    |            | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 8086:4b24 | 8086:7270 | Intel            | Elkhart Lake SPI (Flash) Controller  | 18    |            | [21D2214DA6](<Desktop/Protectli/VP/VP2420/F9E7BE26C82B/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/21D2214DA6>) |
| 8086:a324 | 1849:a324 | Intel            | Cannon Lake PCH SPI Controller       | 17    |            | [0E0C795886](<Desktop/ASRock/H310/H310M-ITX-ac/1C596F08C310/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0E0C795886>) |
| 8086:43a4 | 1043:8694 | Intel            | Tiger Lake-H SPI Controller          | 14    |            | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:43e8 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 14    | ig4iic     | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 14    |            | [B2784F4025](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/B2784F4025>) |
| 8086:a324 | 17aa:312d | Intel            | Cannon Lake PCH SPI Controller       | 14    |            | [867C14F8D1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7003HUS/E865EFD8EF3C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/867C14F8D1>) |
| 8086:22c2 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | ig4iic     | [34B349EEAD](<Desktop/Protectli/FW2/FW2B/EE3235442DAF/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/34B349EEAD>) |
| 8086:4de9 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 13    |            | [34CF4827D7](<Desktop/Hardkernel/ODROID-H/ODROID-H3/174DBB630022/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/34CF4827D7>) |
| 8086:a0a4 | 8086:7270 | Intel            | Tiger Lake-LP SPI Controller         | 13    |            | [80F6445F54](<Notebook/Star Labs/StarBook/StarBook/2BCE064BBD99/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/80F6445F54>) |
| 8086:22c1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 12    | ig4iic     | [34B349EEAD](<Desktop/Protectli/FW2/FW2B/EE3235442DAF/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/34B349EEAD>) |
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 12    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:34ab | 8086:7270 | Intel            | Ice Lake-LP Serial IO SPI Control... | 12    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 12    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:43e9 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 12    | ig4iic     | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:02c5 | 8086:7270 | Intel            | Comet Lake Serial IO I2C Host Con... | 11    | ig4iic     | [768A10819B](<Desktop/Others/QD-CMU/QD-CMU01/23D04D465989/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/768A10819B>) |
| 8086:4dab | 8086:7270 | Intel            | Jasper Lake LPSS: SPI Controller #1  | 11    |            | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 8086:4dc5 | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 11    |            | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 8086:4dc6 | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 11    |            | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 1425:5601 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 10    |            | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 8086:02e8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 10    | ig4iic     | [362A33BD50](<Mini Pc/AZW/SEi/SEi/DFE79546C13E/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/362A33BD50>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 10    |            | [6F8AD1A8B9](<Desktop/Gigabyte Technology/Z490/Z490 VISION G/61A52C9709E8/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6F8AD1A8B9>) |
| 8086:4deb | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #3  | 10    |            | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 8086:a324 | 15d9:1b0e | Intel            | Cannon Lake PCH SPI Controller       | 10    |            | [FEBC7F7A94](<Server/Supermicro/Super/Super Server/BA81BAF3CD4C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FEBC7F7A94>) |
| 8086:a368 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 10    | ig4iic     | [FEBC7F7A94](<Server/Supermicro/Super/Super Server/BA81BAF3CD4C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FEBC7F7A94>) |
| 8086:a369 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 10    | ig4iic     | [FEBC7F7A94](<Server/Supermicro/Super/Super Server/BA81BAF3CD4C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FEBC7F7A94>) |
| 8086:5ac8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     |            | [00E52DF710](<Desktop/MiTAC/UltraPoint/UltraPoint/4F52B749418F/OPNSENSE-22.1.10/13.0-STABLE/AMD64/00E52DF710>) |
| 1425:4601 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 8     |            | [70A786B8B5](<Server/Supermicro/X10/X10SLM+-LN4F/F4A1F01A1AAE/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/70A786B8B5>) |
| 8086:02a4 | 8086:2081 | Intel            | Comet Lake SPI (flash) Controller    | 8     |            | [5C2047356D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/5C2047356D>) |
| 8086:02e8 | 8086:2081 | Intel            | Serial IO I2C Host Controller        | 8     | ig4iic     | [5C2047356D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/5C2047356D>) |
| 8086:02ea | 8086:2081 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 8     | ig4iic     | [5C2047356D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/5C2047356D>) |
| 8086:43a4 | 1849:43a4 | Intel            | Tiger Lake-H SPI Controller          | 8     |            | [4EBEAC2699](<Desktop/ASRock/H570/H570M-ITX-ac/7252CA256A2E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/4EBEAC2699>) |
| 8086:9da4 | 1297:4076 | Intel            | Cannon Point-LP SPI Controller       | 8     |            | [0F1E027B35](<Desktop/Shuttle/DS10/DS10U/EB8F6226ED0B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/0F1E027B35>) |
| 8086:9da4 | 17aa:2279 | Intel            | Cannon Point-LP SPI Controller       | 8     |            | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 8086:9de8 | 17aa:2279 | Intel            | Cannon Point-LP Serial IO I2C Con... | 8     | ig4iic     | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 8086:a324 | 1028:085a | Intel            | Cannon Lake PCH SPI Controller       | 8     |            | [53FA01007B](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/53FA01007B>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 170   | pchtherm   | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:4e03 | 8086:7270 | Intel            | Dynamic Tuning service               | 92    |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 87    |            | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 84    | ig4iic     | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 83    | ig4iic     | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 75    |            | [D7B171D0BB](<Desktop/Others/Others/Others/E869214B6318/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/D7B171D0BB>) |
| 8086:204d |           | Intel            | Sky Lake-E M3KTI Registers           | 67    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 8086:2015 |           | Intel            | Sky Lake-E Ubox Registers            | 64    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 58    | ig4iic     | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 57    | ig4iic     | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 57    | ig4iic     | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:204c |           | Intel            | Sky Lake-E M3KTI Registers           | 54    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 51    |            | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 49    | ig4iic     | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 47    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 47    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 47    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 45    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 45    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 40    | ig4iic     | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 39    |            | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 37    |            | [B31BCF2087](<Desktop/Protectli/VP/VP2410/7C5B3D7D01BD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/B31BCF2087>) |
| 8086:2058 |           | Intel            | Sky Lake-E KTI 0                     | 35    |            | [09E5FC33AD](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/01D46C98F610/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/09E5FC33AD>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 35    | ig4iic     | [BD675A503D](<Desktop/Hardkernel/ODROID-H/ODROID-H2/D15B59962C50/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/BD675A503D>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 35    | ig4iic     | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 34    | pchtherm   | [6283151877](<Server/HPE/MM10/MM10Gen9/C96A2A643802/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6283151877>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | uart       | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | uart       | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | ig4iic     | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | ig4iic     | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | ig4iic     | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:9df9 | 8086:7270 | Intel            | Cannon Point-LP Thermal Controller   | 30    | pchtherm   | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 29    | uart       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 29    | uart       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 29    | uart       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 29    | uart       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:8c24 | 15d9:086d | Intel            | 8 Series Chipset Family Thermal M... | 29    | pchtherm   | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | ig4iic     | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | ig4iic     | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:31b4 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 27    | ig4iic     | [DF7A30FC45](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/53D0F9939362/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/DF7A30FC45>) |
| 8086:31ba | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 27    | ig4iic     | [DF7A30FC45](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/53D0F9939362/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/DF7A30FC45>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 27    |            | [9AEC93F312](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/B565A5A319EC/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/9AEC93F312>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 27    |            | [9AEC93F312](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/B565A5A319EC/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/9AEC93F312>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 27    | uart       | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 27    | uart       | [2E616F1AD4](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/2E616F1AD4>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 292   | intsmb     | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 256   | ichsmb     | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 238   | ichsmb     | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 210   | ichsmb     | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 191   | ichsmb     | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:4da3 | 8086:7270 | Intel            | Jasper Lake SMBus                    | 147   |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 115   | intsmb     | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 103   | ichsmb     | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 1022:790b | 1458:5001 | AMD              | FCH SMBus Controller                 | 81    | intsmb     | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 81    | ichsmb     | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 77    | ichsmb     | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 1022:780b | 1734:1202 | AMD              | FCH SMBus Controller                 | 74    | intsmb     | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:790b | 1849:ffff | AMD              | FCH SMBus Controller                 | 66    | intsmb     | [2A6207FB45](<Desktop/ASRock/X300/X300M-STX/6196E1492AD8/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2A6207FB45>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 62    | ichsmb     | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 60    | ichsmb     | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 1022:790b | 1043:87c0 | AMD              | FCH SMBus Controller                 | 57    | intsmb     | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:790b | 1849:790b | AMD              | FCH SMBus Controller                 | 55    | intsmb     | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 8086:283e | 8086:283e | Intel            | 82801H (ICH8 Family) SMBus Contro... | 54    | ichsmb     | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 1022:780b | 103c:213d | AMD              | FCH SMBus Controller                 | 51    | intsmb     | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 50    | ichsmb     | [8D052CBF4C](<Mini Pc/Broachlink/NOAH/NOAH V2 E3845/AF93BF149B22/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/8D052CBF4C>) |
| 8086:27da | 8086:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 50    | ichsmb     | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 1002:4385 | 1002:4385 | AMD              | SBx00 SMBus Controller               | 46    | intsmb     | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 8086:1c22 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 44    | ichsmb     | [E975D67484](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E975D67484>) |
| 1022:780b | 103c:8103 | AMD              | FCH SMBus Controller                 | 43    | intsmb     | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 8086:8c22 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 43    | ichsmb     | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c22 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | ichsmb     | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 39    | ichsmb     | [B31BCF2087](<Desktop/Protectli/VP/VP2410/7C5B3D7D01BD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/B31BCF2087>) |
| 8086:8c22 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 38    | ichsmb     | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:a123 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | ichsmb     | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 37    | intsmb     | [2E40DF5A32](<Desktop/WYSE/Z/Z CLASS/76E6DE34A38F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E40DF5A32>) |
| 8086:19df | 8086:7270 | Intel            | Atom Processor C3000 Series SMBus... | 37    | ichsmb     | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:1c22 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | ichsmb     | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 36    | ichsmb     | [B2176FAFCF](<Desktop/Intel/MAHOBAY/MAHOBAY/0D48ADEA90BB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2176FAFCF>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 36    | ichsmb     | [6283151877](<Server/HPE/MM10/MM10Gen9/C96A2A643802/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6283151877>) |
| 1022:790b | 1043:8747 | AMD              | FCH SMBus Controller                 | 35    | intsmb     | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 8086:1c22 | 1458:5001 | Intel            | 6 Series/C200 Series Chipset Fami... | 35    | ichsmb     | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 34    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:1e22 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family SMBu... | 34    | ichsmb     | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:1e22 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family SMBu... | 32    | ichsmb     | [A2873D7C87](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/A2873D7C87>) |
| 8086:1c22 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 31    | ichsmb     | [904FDE472A](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/904FDE472A>) |
| 8086:1e22 | 1458:5001 | Intel            | 7 Series/C216 Chipset Family SMBu... | 30    | ichsmb     | [D8C78B92A7](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4DBEA0F75A7B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D8C78B92A7>) |
| 8086:3a30 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 30    | ichsmb     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 8086:9da3 | 8086:7270 | Intel            | Cannon Point-LP SMBus Controller     | 30    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:1e22 | 8086:1e22 | Intel            | 7 Series/C216 Chipset Family SMBu... | 29    | ichsmb     | [C2735D8120](<Notebook/Others/Others/Others/E349DD8616DA/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/C2735D8120>) |
| 8086:8c22 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 29    | ichsmb     | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 27    | ichsmb     | [31989714D5](<Server/Intel/S1200/S1200BTL/6890D5FE82C7/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/31989714D5>) |
| 8086:31d4 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 27    | ichsmb     | [DF7A30FC45](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/53D0F9939362/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/DF7A30FC45>) |
| 8086:a323 | 1043:8694 | Intel            | Cannon Lake PCH SMBus Controller     | 27    | ichsmb     | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 1002:4385 | 1022:1510 | AMD              | SBx00 SMBus Controller               | 26    | intsmb     | [1162545537](<Desktop/PC Engines/APU/APU/87128D66CD5A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/1162545537>) |
| 1002:4385 | 1043:8389 | AMD              | SBx00 SMBus Controller               | 26    | intsmb     | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 204   | hdac       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 198   | hdac       | [F75FEE2A2D](<Desktop/Others/YL-J3160/YL-J3160L4/124BE58E7612/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F75FEE2A2D>) |
| 8086:4dc8 | 8086:7270 | Intel            | Jasper Lake HD Audio                 | 146   | hdac       | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 137   | hdac       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 84    | hdac       | [12AC44CBF7](<Desktop/Others/Others/Others/B6CD8CD35969/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/12AC44CBF7>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 77    | hdac       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1002:9840 | 1734:1202 | AMD              | Kabini HDMI/DP Audio                 | 74    | hdac       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:0a0c | 8086:0a0c | Intel            | Haswell-ULT HD Audio Controller      | 73    | hdac       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 8086:9ca0 | 8086:7270 | Intel            | Wildcat Point-LP High Definition ... | 71    | hdac       | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 70    | hdac       | [9CC3FAA610](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/9A7311DE9B92/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/9CC3FAA610>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 69    | hdac       | [57F357784C](<Mini Pc/AMI/Aptio/Aptio CRB/2CC23D52E14F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/57F357784C>) |
| 8086:160c | 8086:160c | Intel            | Broadwell-U Audio Controller         | 68    | hdac       | [CF598483CF](<Notebook/Google/Lulu/Lulu/69AC5E94B55B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CF598483CF>) |
| 1002:9840 | 103c:213d | AMD              | Kabini HDMI/DP Audio                 | 51    | hdac       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 48    | hdac       | [2A6207FB45](<Desktop/ASRock/X300/X300M-STX/6196E1492AD8/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2A6207FB45>) |
| 1022:780d | 103c:213d | AMD              | FCH Azalia Controller                | 47    | hdac       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 8086:0c0c | 8086:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 47    | hdac       | [6F8D299FFB](<Firewall/Sophos/SG/SG/4509562A3078/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6F8D299FFB>) |
| 1022:780d | 1734:1203 | AMD              | FCH Azalia Controller                | 46    | hdac       | [6729453203](<Desktop/Fujitsu/FUTRO/FUTRO S920/ED892B6BC60E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/6729453203>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 45    | hdac       | [77A58527DA](<Desktop/Gigabyte Technology/H97/H97M-HD3/E5275305C703/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/77A58527DA>) |
| 8086:5a98 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 45    | hdac       | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 1002:1308 | 103c:8103 | AMD              | Kaveri HDMI/DP Audio Controller      | 43    | hdac       | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 8086:8c20 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset High... | 43    | hdac       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:0c0c | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 40    | hdac       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 38    | hdac       | [8642FCACB2](<Mini Pc/CompuLab/fitlet/fitlet2/868EC53D2494/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8642FCACB2>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 37    | hdac       | [1E97EE1C05](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/98235472B8D9/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/1E97EE1C05>) |
| 8086:0c0c | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 37    | hdac       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c20 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset High... | 36    | hdac       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 34    | hdac       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:0c0c | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 34    | hdac       | [EC33F29DC0](<Desktop/ASUSTek Computer/All/All Series/9506DED5E0BD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/EC33F29DC0>) |
| 1022:780d | 103c:8103 | AMD              | FCH Azalia Controller                | 33    | hdac       | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 1022:15e3 | 1022:d001 | AMD              | Family 17h/19h HD Audio Controller   | 32    | hdac       | [1CCA4A556D](<Notebook/Deciso/OPNsense/OPNsense Appliance/2DD46B265269/OPNSENSE-23.1.1/13.1-RELEASE-P7/AMD64/1CCA4A556D>) |
| 1022:1457 | 1022:c950 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 30    | hdac       | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 8086:1e20 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family High... | 29    | hdac       | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 1022:780d | 1022:780d | AMD              | FCH Azalia Controller                | 27    | hdac       | [8B9A301B47](<Desktop/M613/G420/G420N1WNS/19C20EF0FF54/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8B9A301B47>) |
| 8086:0c0c | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 26    | hdac       | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:9dc8 | 8086:7270 | Intel            | Cannon Point-LP High Definition A... | 26    | hdac       | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:3198 | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 25    | hdac       | [C258B4972C](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/C258B4972C>) |
| 8086:8c20 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset High... | 25    | hdac       | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:02c8 | 8086:7270 | Intel            | Comet Lake PCH-LP cAVS               | 23    | hdac       | [88491D298E](<Notebook/Google/Kohaku/Kohaku/5F2605C0CFF4/FREEBSD-13.1/13.1-RELEASE/AMD64/88491D298E>) |
| 8086:1c20 | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 23    | hdac       | [E5A43DD311](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4286CTO/3C1927176580/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/E5A43DD311>) |
| 8086:3b56 | 17aa:215e | Intel            | 5 Series/3400 Series Chipset High... | 23    | hdac       | [9F9CB3E201](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2537B94/CDBD8C566708/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9F9CB3E201>) |
| 8086:1c20 | 1458:a002 | Intel            | 6 Series/C200 Series Chipset Fami... | 22    | hdac       | [33AF90DD93](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/954969B6DBB2/FREEBSD-13.1/13.1-RELEASE/AMD64/33AF90DD93>) |
| 8086:1e20 | 8086:1e20 | Intel            | 7 Series/C216 Chipset Family High... | 22    | hdac       | [AE6EA07868](<Desktop/Advantech/UTC-520/UTC-520C/92E6177F9568/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/AE6EA07868>) |
| 1002:9840 | 1002:9840 | AMD              | Kabini HDMI/DP Audio                 | 21    | hdac       | [3D2880DD30](<Notebook/Datto/1000/1000/B36CFEC6709D/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3D2880DD30>) |
| 1002:aaf0 | 1da2:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 21    | hdac       | [6F8AD1A8B9](<Desktop/Gigabyte Technology/Z490/Z490 VISION G/61A52C9709E8/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6F8AD1A8B9>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | hdac       | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 8086:2284 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 21    | hdac       | [0ADF0CA671](<Desktop/ZOTAC/Others/Others/6E70FB5A2725/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0ADF0CA671>) |
| 8086:9d70 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 21    | hdac       | [D3750005C2](<Desktop/Others/Others/Others/C14747EBBA5F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/D3750005C2>) |
| 1002:ab28 | 1002:ab28 | AMD              | Navi 21/23 HDMI/DP Audio Controller  | 20    | hdac       | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 8086:3198 | 10ec:115a | Intel            | Celeron/Pentium Silver Processor ... | 20    | hdac       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:8c20 | 1458:a002 | Intel            | 8 Series/C220 Series Chipset High... | 20    | hdac       | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8231 | 1028:0493 | O2 Micro         | Integrated MS/MSPRO Controller       | 7     |            | [CB7B02C421](<Notebook/Dell/Latitude/Latitude E6420/814FB112DD83/FREEBSD-13.1/13.1-RELEASE/AMD64/CB7B02C421>) |
| 1217:8331 | 1028:049b | O2 Micro         | O2 Flash Memory Card                 | 4     |            | [524AB094E1](<Notebook/Dell/Latitude/Latitude E5420/15C36179305C/FREEBSD-13.1/13.1-RELEASE/AMD64/524AB094E1>) |
| 1217:7130 | 1179:ff50 | O2 Micro         | Integrated MS/xD Controller          | 3     |            | [E057898546](<Notebook/Toshiba/Satellite/Satellite A300/72110BAFD1E3/FREEBSD-12.3-STABLE/12.3-STABLE/I386/E057898546>) |
| 104c:803b | 1179:ff00 | Texas Instrum... | PCIxx12 Flash Media Controller       | 2     |            | [860AEA3CE4](<Notebook/Toshiba/Satellite/Satellite A200/CC9CFD7250FC/FREEBSD-13.1-P2/13.1-RELEASE-P2/I386/860AEA3CE4>) |
| 1217:8330 | 1028:04a3 | O2 Micro         | OZ600 MS/xD Controller               | 2     |            | [2F848FD2C0](<Notebook/Dell/Precision/Precision M4600/B6B9C54EEBB2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/2F848FD2C0>) |
| 1283:8211 | 1283:8211 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 2     | atapci     | [BA1D9A51C2](<Desktop/Intel/Bearlake/Bearlake Bearlake Fab A/57F476905C38/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/BA1D9A51C2>) |
| 1000:c010 | 1000:00b2 | Broadcom / LSI   | PEX880xx PCIe Gen 4 Switch           | 1     |            | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 104c:803b | 1025:011f | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [5D6A8A51D0](<Notebook/Acer/Extensa/Extensa 5220/D9CE76F90EBD/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/5D6A8A51D0>) |
| 104c:803b | 103c:30aa | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [256E0AE719](<Notebook/Hewlett-Packard/Compaq/Compaq nc6320/BA8F7F88D1FF/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/256E0AE719>) |
| 104c:803b | 103c:30b1 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [F4E4E3826B](<Notebook/Hewlett-Packard/Compaq/Compaq tc4400/1707AEC93CCB/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/F4E4E3826B>) |
| 104c:803b | 104d:81e6 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [ACE534D784](<Notebook/Sony/VGN-SZ3/VGN-SZ3VWP_X/ECFA4AD781DF/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/ACE534D784>) |
| 104c:803b | 104d:8203 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [312DF080A7](<Notebook/Sony/VGN-UX1/VGN-UX1XRN/CF5AA44652B7/FREEBSD-12.3-P6/12.3-RELEASE-P6/I386/312DF080A7>) |
| 104c:803b | 104d:9016 | Texas Instrum... | PCIxx12 Flash Media Controller       | 1     |            | [B417DF513F](<Notebook/Sony/VGN-AR630/VGN-AR630E/0309566B32D1/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/B417DF513F>) |
| 104c:ac8f | 104d:8190 | Texas Instrum... | PCI7420/7620 SD/MS-Pro Controller    | 1     |            | [F2F3923EA6](<Notebook/Sony/VGN-S/VGN-S150/194677ED6A48/FREEBSD-13.0-CURRENT/13.0-CURRENT/I386/F2F3923EA6>) |
| 105a:4d30 | 105a:4d33 | Promise Techn... | PDC20267 (FastTrak100/Ultra100)      | 1     | atapci     | [D99AE1AAD1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX PLUS/627BCCBE6A6E/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/D99AE1AAD1>) |
| 105a:4d69 | 105a:4d68 | Promise Techn... | 20269                                | 1     | atapci     | [8D99F317E4](<Desktop/TYAN Computer/Intel/Intel 440BX-GX Rev. 4/05C7EC931544/FREEBSD-13.1-P2/13.1-RELEASE-P2/I386/8D99F317E4>) |
| 1217:7130 | 1028:0273 | O2 Micro         | Integrated MS/xD Controller          | 1     |            | [EF1C0E0F2E](<Notebook/Dell/Vostro/Vostro 1510/810B328E2D37/FREEBSD-12.2/12.2-RELEASE/AMD64/EF1C0E0F2E>) |
| 1217:7130 | 10cf:13c6 | O2 Micro         | Integrated MS/xD Controller          | 1     |            | [AC880C0076](<Notebook/Fujitsu/FMVNF70/FMVNF70YJ/2CAC733E41C3/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/AC880C0076>) |
| 1217:7130 | 1462:3ff3 | O2 Micro         | Integrated MS/xD Controller          | 1     |            | [7DB1345E97](<Notebook/LG Electronics/E500/E500-GP01A9/E9442CB525C8/FREEBSD-13.0-P2/13.0-RELEASE-P1/AMD64/7DB1345E97>) |
| 1217:8130 | 1028:02eb | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 1     |            | [7AE292B282](<Notebook/Dell/Studio/Studio 1747/121152236620/HELLOSYSTEM-0.8.0/13.1-RC3/AMD64/7AE292B282>) |
| 1217:8130 | 10cf:1568 | O2 Micro         | Integrated MS/MSPRO/xD Controller    | 1     |            | [51B5325C85](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK NH570/6DEB38A1F3EF/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/51B5325C85>) |
| 1217:8330 | 1028:04a4 | O2 Micro         | OZ600 MS/xD Controller               | 1     |            | [B6C974B8BD](<Notebook/Dell/Precision/Precision M6600/4B49B0BB08DA/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/B6C974B8BD>) |
| 1217:8331 | 1028:0494 | O2 Micro         | O2 Flash Memory Card                 | 1     |            | [C4AE703ADD](<Notebook/Dell/Latitude/Latitude E6520/51D725ABDAFA/FREEBSD-13.1-RC1/13.1-RC1/AMD64/C4AE703ADD>) |
| 1217:8331 | 1028:049a | O2 Micro         | O2 Flash Memory Card                 | 1     |            | [E0DD26220F](<Notebook/Dell/Latitude/Latitude E5520/15949FA8A5BD/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/E0DD26220F>) |
| 1283:8211 | 1043:8138 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 1     | atapci     | [A2B5067552](<Desktop/ASUSTek Computer/P5/P5WD2-Premium/EB10AF6202CE/OPNSENSE-22.1.4/13.0-STABLE/AMD64/A2B5067552>) |
| 19a2:0712 | 103c:3376 | Emulex           | OneConnect 10Gb iSCSI Initiator (... | 1     |            | [74A4364A7F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/2AF460D1EA85/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/74A4364A7F>) |
| 1aed:1005 | 1aed:1010 | SanDisk          | ioDimm3                              | 1     | fct        | [6905821659](<Desktop/ASRock/X99/X99 Extreme4/3BEC2E139880/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/6905821659>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 252   | ahci       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 246   | ahci       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 210   | ahci       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 188   | ahci       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 176   | ahci       | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:7801 | 1022:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 175   | ahci       | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:4dd3 | 8086:7270 | Intel            | Jasper Lake SATA AHCI Controller     | 131   | ahci       | [F07E092146](<Desktop/Techvision/TVI7309/TVI7309X/432837343A25/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F07E092146>) |
| 1022:43c8 | 1b21:1062 | AMD              | 400 Series Chipset SATA Controller   | 121   | ahci       | [85AECF8C3F](<Desktop/MSI/MS-7/MS-7A38/2325A856795F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/85AECF8C3F>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 104   | ahci       | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 80    | ahci       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 74    | ahci       | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 1022:7801 | 1734:1202 | AMD              | FCH SATA Controller [AHCI mode]      | 73    | ahci       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:43eb | 1b21:1062 | AMD              | 500 Series Chipset SATA Controller   | 62    | ahci       | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 58    | ahci       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 58    | ahci       | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 1b21:0612 | 1849:0612 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 53    | ahci       | [48C80BBB1F](<Desktop/ASRock/H61/H61M-U3S3/5FF9535C321A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/48C80BBB1F>) |
| 1022:7801 | 103c:213d | AMD              | FCH SATA Controller [AHCI mode]      | 51    | ahci       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:7901 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 51    | ahci       | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1022:7901 | 1849:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 51    | ahci       | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 49    | ahci       | [8D052CBF4C](<Mini Pc/Broachlink/NOAH/NOAH V2 E3845/AF93BF149B22/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/8D052CBF4C>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 46    | ahci       | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 44    | ahci       | [2E40DF5A32](<Desktop/WYSE/Z/Z CLASS/76E6DE34A38F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E40DF5A32>) |
| 8086:8c02 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 41    | ahci       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 1022:7801 | 103c:8103 | AMD              | FCH SATA Controller [AHCI mode]      | 40    | ahci       | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 8086:1c02 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 39    | ahci       | [E975D67484](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E975D67484>) |
| 1022:43b8 | 1b21:1062 | AMD              | FCH SATA Controller D                | 38    | ahci       | [593F6FF02D](<Desktop/MSI/MS-7/MS-7C51/435F418C7DE2/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/593F6FF02D>) |
| 8086:a102 | 1043:8694 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 38    | ahci       | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 8086:1f22 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA2 C... | 37    | ahci       | [6062F9823E](<Desktop/Others/Others/Others/A6DA96BC681E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6062F9823E>) |
| 8086:8c02 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 36    | ahci       | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 33    | ahci       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:1e02 | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 33    | ahci       | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 33    | ahci       | [6283151877](<Server/HPE/MM10/MM10Gen9/C96A2A643802/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6283151877>) |
| 8086:19b2 | 8086:7270 | Intel            | Atom Processor C3000 Series SATA ... | 32    | ahci       | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 1022:7901 | 1043:8747 | AMD              | FCH SATA Controller [AHCI mode]      | 31    | ahci       | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 1022:7901 | 1849:ffff | AMD              | FCH SATA Controller [AHCI mode]      | 30    | ahci       | [2A6207FB45](<Desktop/ASRock/X300/X300M-STX/6196E1492AD8/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2A6207FB45>) |
| 8086:9dd3 | 8086:7270 | Intel            | Cannon Point-LP SATA Controller [... | 30    | ahci       | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:1c02 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 28    | ahci       | [904FDE472A](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/904FDE472A>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 28    | ahci       | [C258B4972C](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/C258B4972C>) |
| 8086:1c02 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 27    | ahci       | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:1e02 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 27    | ahci       | [A2873D7C87](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/A2873D7C87>) |
| 8086:31e3 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 27    | ahci       | [DF7A30FC45](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/53D0F9939362/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/DF7A30FC45>) |
| 8086:8c02 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 27    | ahci       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c02 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 27    | ahci       | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 8086:19c2 | 15d9:0969 | Intel            | Atom Processor C3000 Series SATA ... | 26    | ahci       | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:a352 | 1043:8694 | Intel            | Cannon Lake PCH SATA AHCI Controller | 26    | ahci       | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 1b21:0612 | 1043:84b7 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 25    | ahci       | [A2873D7C87](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/A2873D7C87>) |
| 8086:a282 | 1043:8694 | Intel            | 200 Series PCH SATA controller [A... | 25    | ahci       | [FD39A615DE](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-K R2.0/7D5721B3D945/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD39A615DE>) |
| 8086:02d3 | 8086:7270 | Intel            | Comet Lake SATA AHCI Controller      | 24    | ahci       | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:8c02 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 24    | ahci       | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:8c02 | 1458:b005 | Intel            | 8 Series/C220 Series Chipset Fami... | 24    | ahci       | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7800 | 1022:7800 | AMD              | FCH SATA Controller [IDE mode]       | 81    | ahci       | [FD6E7FA3AF](<Desktop/PC Engines/APU/APU2/FC8FDE81560C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD6E7FA3AF>) |
| 8086:2850 | 8086:2850 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 52    | atapci     | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 1022:780c | 103c:8103 | AMD              | FCH IDE Controller                   | 43    | atapci     | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 39    | atapci     | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:2828 | 8086:2828 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 29    | atapci     | [866FF788F9](<Desktop/Others/Others/Others/5B265979975E/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/866FF788F9>) |
| 8086:27df | 1043:8179 | Intel            | 82801G (ICH7 Family) IDE Controller  | 27    | atapci     | [29AD0E1044](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/4235E38A16E7/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/29AD0E1044>) |
| 1002:439c | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 26    | atapci     | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |
| 8086:27c0 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 24    | atapci     | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:27c0 | 1043:8179 | Intel            | NM10/ICH7 Family SATA Controller ... | 20    | atapci     | [29AD0E1044](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/4235E38A16E7/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/29AD0E1044>) |
| 1002:439c | 1458:5002 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 19    | atapci     | [29290B1B9C](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2P/EC084C5059C4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/29290B1B9C>) |
| 8086:3a20 | 103c:330d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 19    | atapci     | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 1002:439c | 1849:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 16    | atapci     | [461F8CCA23](<Desktop/ASRock/E350/E350M1/DA069FB4F97A/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/461F8CCA23>) |
| 8086:27c0 | 1458:b002 | Intel            | NM10/ICH7 Family SATA Controller ... | 15    | atapci     | [C55B1DD170](<Desktop/Gigabyte Technology/G31/G31M-ES2L/B1A7D0E55D2F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C55B1DD170>) |
| 8086:2850 | 17aa:20a6 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 15    | atapci     | [67B2E8DB2B](<Notebook/Lenovo/ThinkPad/ThinkPad T61p 6457UN2/ABBAD64ECA84/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/67B2E8DB2B>) |
| 8086:2921 | 1028:0235 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 15    | atapci     | [5D6BABDA3E](<Server/Dell/PowerEdge/PowerEdge R710/209AA94D6139/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/5D6BABDA3E>) |
| 1002:4390 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 14    | ahci       | [9AF803F850](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/3E9A6AB48C81/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9AF803F850>) |
| 8086:1c00 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | atapci     | [4BB9A9324B](<Desktop/Dell/OptiPlex/OptiPlex 390/EB6E3143EA5A/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/4BB9A9324B>) |
| 8086:1c08 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | atapci     | [4BB9A9324B](<Desktop/Dell/OptiPlex/OptiPlex 390/EB6E3143EA5A/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/4BB9A9324B>) |
| 8086:2921 | 1028:0236 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 13    | atapci     | [299FCE37CB](<Server/Dell/PowerEdge/PowerEdge R610/C023161D22D2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/299FCE37CB>) |
| 8086:1c00 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | atapci     | [76ECD68FF6](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/76ECD68FF6>) |
| 8086:1c08 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | atapci     | [76ECD68FF6](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/76ECD68FF6>) |
| 8086:269e | 103c:31fe | Intel            | 631xESB/632xESB IDE Controller       | 11    | atapci     | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:3a20 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 11    | atapci     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 8086:3a26 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 11    | atapci     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 1002:4390 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 10    | ahci       | [6B63A16799](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/CA4B1CA9726F/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6B63A16799>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | atapci     | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 8086:27c0 | 1849:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 10    | atapci     | [EACE523F17](<Desktop/ASRock/G41/G41M-GS3/A906B312696E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/EACE523F17>) |
| 8086:27df | 1849:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 10    | atapci     | [EACE523F17](<Desktop/ASRock/G41/G41M-GS3/A906B312696E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/EACE523F17>) |
| 197b:2363 | 1043:824f | JMicron Techn... | JMB363 SATA/IDE Controller           | 9     | atapci     | [DD9685A909](<Desktop/ASUSTek Computer/P7P55D/P7P55D DELUXE/12FEB991B761/FREEBSD-13.1-P6/13.1-RELEASE-P6/AMD64/DD9685A909>) |
| 8086:2850 | 106b:00a1 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 9     | atapci     | [7AEF0A996B](<Notebook/Apple/MacBook3/MacBook3,1/B75216EE3719/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7AEF0A996B>) |
| 8086:29b6 | 1028:0211 | Intel            | 82Q35 Express PT IDER Controller     | 9     | atapci     | [03BCC500C0](<Desktop/Dell/OptiPlex/OptiPlex 755/63258707728A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/03BCC500C0>) |
| 1002:439c | 103c:1609 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 8     | atapci     | [50C8CB79F7](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.4/12.4-RELEASE/AMD64/50C8CB79F7>) |
| 10de:03f6 | 1849:03f6 | Nvidia           | MCP61 SATA Controller                | 8     | atapci     | [04F43C3D70](<Desktop/ASRock/N68-S/N68-S UCC/59DCE7CA2B79/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/04F43C3D70>) |
| 1106:0415 | 1043:838f | VIA Technologies | VT6415 PATA IDE Host Controller      | 8     | atapci     | [3C78171104](<Desktop/ASUSTek Computer/P7/P7H55/A27D3F7702D0/HELLOSYSTEM-0.8.0/13.1-RELEASE-P6/AMD64/3C78171104>) |
| 197b:2363 | 1458:b000 | JMicron Techn... | JMB363 SATA/IDE Controller           | 8     | atapci     | [3EE914E3A0](<Desktop/Gigabyte Technology/GA-890/GA-890FXA-UD5/0D93685E30B3/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/3EE914E3A0>) |
| 8086:1d3c | 103c:1589 | Intel            | C600/X79 series chipset IDE-r Con... | 8     | atapci     | [0696D30D3F](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/0696D30D3F>) |
| 8086:3a20 | 1014:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 8     | atapci     | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 8086:3a26 | 1014:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 8     | atapci     | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 10de:03ec | 1849:03ec | Nvidia           | MCP61 IDE                            | 7     | atapci     | [04F43C3D70](<Desktop/ASRock/N68-S/N68-S UCC/59DCE7CA2B79/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/04F43C3D70>) |
| 8086:1d00 | 103c:18a9 | Intel            | C600/X79 series chipset 4-Port SA... | 7     | atapci     | [A5514D3F4B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/6173205D3B06/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/A5514D3F4B>) |
| 8086:27c0 | 1028:0400 | Intel            | NM10/ICH7 Family SATA Controller ... | 7     | atapci     | [42DA900D88](<Desktop/Dell/OptiPlex/OptiPlex 380/C67C08C62EEE/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/42DA900D88>) |
| 8086:27df | 1028:0400 | Intel            | 82801G (ICH7 Family) IDE Controller  | 7     | atapci     | [42DA900D88](<Desktop/Dell/OptiPlex/OptiPlex 380/C67C08C62EEE/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/42DA900D88>) |
| 8086:2920 | 15d9:060a | Intel            | 82801IR/IO/IH (ICH9R/DO/DH) 4 por... | 7     | atapci     | [6A91635684](<Desktop/exone/X7/X7SPA-HF/881B5CC94BD2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6A91635684>) |
| 8086:2926 | 15d9:060a | Intel            | 82801I (ICH9 Family) 2 port SATA ... | 7     | atapci     | [6A91635684](<Desktop/exone/X7/X7SPA-HF/881B5CC94BD2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6A91635684>) |
| 8086:3a26 | 103c:330d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 7     | atapci     | [4E059E9162](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/4E059E9162>) |
| 1022:7800 | 1458:b002 | AMD              | FCH SATA Controller [IDE mode]       | 6     | ahci       | [DAED3F9401](<Desktop/Gigabyte Technology/F2/F2A68HM-H/3B216ACDFEA8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DAED3F9401>) |
| 11ab:6121 | 1043:8212 | Marvell Techn... | 88SE6111/6121 SATA II / PATA Cont... | 6     | atapci     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 197b:2362 | 1043:8460 | JMicron Techn... | JMB362 SATA Controller               | 6     | ahci       | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 8086:1c00 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | atapci     | [4B3B7A0929](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/830DACE8E0B6/OPNSENSE-22.1.8/13.0-STABLE/AMD64/4B3B7A0929>) |
| 8086:1c00 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | atapci     | [1EC1683ACD](<Desktop/Gigabyte Technology/P61/P61-USB3-B3/CFEE4BCC2A88/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/1EC1683ACD>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 266   | nvme       | [C9DDD32406](<Server/Supermicro/Super/Super Server/A912B2977FCE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/C9DDD32406>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 93    | nvme       | [B08FD92E36](<Desktop/MSI/MS-7/MS-7D46/C894FC6BA535/MYBEE-13.2-RC2/13.2-RC2/AMD64/B08FD92E36>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 88    | nvme       | [6D7B30D2C4](<Notebook/Lenovo/ThinkPad/ThinkPad T480 20L6S29E0T/988E312ED9CE/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/6D7B30D2C4>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 83    | nvme       | [6E97A003EC](<Notebook/Acer/Nitro/Nitro AN515-54/753EE6D71A9C/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/6E97A003EC>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 65    | nvme       | [AF190C38E9](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS0HN1N/FFA6D6E4D3C7/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/AF190C38E9>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 64    | nvme       | [C1886BCD29](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0FC3EEDA5ED5/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/C1886BCD29>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 56    | nvme       | [80F6445F54](<Notebook/Star Labs/StarBook/StarBook/2BCE064BBD99/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/80F6445F54>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 43    | nvme       | [C176577762](<Notebook/ASUSTek Computer/ASUS/ASUS TUF Gaming A15 FA506II_FA506II/6CEA289E0B55/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/C176577762>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 35    | nvme       | [01F5F21B76](<Notebook/Dell/Precision/Precision 7720/A27F623F9015/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/01F5F21B76>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 30    | nvme       | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 29    | nvme       | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 1d79:2263 | 1d79:2263 | Transcend        |                                      | 29    | nvme       | [1CCA4A556D](<Notebook/Deciso/OPNsense/OPNsense Appliance/2DD46B265269/OPNSENSE-23.1.1/13.1-RELEASE-P7/AMD64/1CCA4A556D>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 29    | nvme       | [E7EF795B9B](<Notebook/Gigabyte Technology/GB-BSi3/GB-BSi3A-6100/1279B1AC4E76/HELLOSYSTEM-0.8.0/13.1-RELEASE-P6/AMD64/E7EF795B9B>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 27    | nvme       | [95C62844DE](<Desktop/Others/Others/Others/722F4261A23A/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/95C62844DE>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 24    | nvme       | [054D55B3C1](<Desktop/ASRock/X570S/X570S PG Riptide/CA69BE9A5534/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/054D55B3C1>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4              | 23    | nvme       | [1603F38C4C](<Notebook/Hewlett-Packard/Laptop/Laptop 14s-fq1xxx/B1AAF63EEE99/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/1603F38C4C>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 22    | nvme       | [80DD48BCA9](<Notebook/Lenovo/ThinkPad/ThinkPad P52s 20LBS0FH00/BD0ED8EF7DB5/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/80DD48BCA9>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 21    | nvme       | [1758C6207C](<Desktop/Techvision/TVI7309/TVI7309X/9E24DE23C8EE/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/1758C6207C>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 20    | nvme       | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 19    | nvme       | [8EB068A097](<Desktop/ASRock/X570/X570 Taichi/627244F84DF9/FREEBSD-13.1/13.1-RELEASE/AMD64/8EB068A097>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 17    | nvme       | [2D9FF025FF](<Desktop/ASRock/B450M/B450M Pro4/8123071B0896/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/2D9FF025FF>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 16    | nvme       | [E27931F082](<Desktop/BESSTAR Tech/TH/TH50/1DD7349765D5/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/E27931F082>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 14    | nvme       | [2588C37FC2](<Desktop/Intel/HM/HM570/5D3A61A4DC00/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2588C37FC2>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202          | 14    | nvme       | [E09800B936](<Desktop/maiyunda/www.maiyunda.com/www.maiyunda.com/5F223CD2630E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E09800B936>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 14    | nvme       | [3DAE7E3EBB](<Notebook/Lenovo/ThinkPad/ThinkPad X280 20KFCTO1WW/09A24116A64A/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/3DAE7E3EBB>) |
| 1344:5410 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 13    | nvme       | [5AB1DADBAB](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F54ADC493621/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5AB1DADBAB>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 13    | nvme       | [59E609FBB2](<Notebook/Lenovo/ThinkPad/ThinkPad P51 20HH001RMX/6C6441A8C24D/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/59E609FBB2>) |
| 1c5c:1327 |           | SK hynix         | BC501 NVMe Solid State Drive         | 13    | nvme       | [222DA5A477](<Desktop/Techvision/TVI7309/TVI7309X/432837343A25/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/222DA5A477>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 13    | nvme       | [6E97A003EC](<Notebook/Acer/Nitro/Nitro AN515-54/753EE6D71A9C/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/6E97A003EC>) |
| 2646:500f | 2646:500f | Kingston Tech... | NVMe Controller                      | 13    | nvme       | [913946CCC9](<Desktop/Others/Others/Others/1C189F0E990E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/913946CCC9>) |
| 1179:0116 | 1179:0001 | Toshiba          | XG5 NVMe SSD Controller              | 12    | nvme       | [3E96602A8F](<Desktop/Dell/OptiPlex/OptiPlex 7060/6BC81BE1C8AC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/3E96602A8F>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 12    | nvme       | [57C3A4005A](<Notebook/Acidanthera/MacBookPro15/MacBookPro15,1/6C4D9581A214/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/57C3A4005A>) |
| 1e95:9100 | 126f:2263 | Solid State S... |                                      | 12    | nvme       | [88491D298E](<Notebook/Google/Kohaku/Kohaku/5F2605C0CFF4/FREEBSD-13.1/13.1-RELEASE/AMD64/88491D298E>) |
| 1179:0113 | 1179:0001 | Toshiba          | BG3 NVMe SSD Controller              | 11    | nvme       | [867C14F8D1](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7003HUS/E865EFD8EF3C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/867C14F8D1>) |
| 1179:011a | 1179:0001 | Toshiba          | XG6 NVMe SSD Controller              | 11    | nvme       | [568BC002E2](<Server/Supermicro/Super/Super Server/6EC6BA948517/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/568BC002E2>) |
| 1c5c:1339 |           | SK hynix         | BC511                                | 11    | nvme       | [DAE7027898](<Desktop/Fujitsu/PRIMERGY/PRIMERGY TX2560 M1/4C2638BCEE71/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/DAE7027898>) |
| 10ec:5763 | 10ec:5763 | Realtek Semic... | NVMe Controller                      | 10    | nvme       | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 1179:0115 | 1179:0001 | Toshiba          | XG4 NVMe SSD Controller              | 9     | nvme       | [9805FE9459](<Desktop/Lenovo/V520S-08IKL/V520S-08IKL Desktop 10NNS04A00/0138F543D0DE/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/9805FE9459>) |
| 1344:5405 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 9     | nvme       | [D2BF200529](<Notebook/Dell/Precision/Precision 7550/96BC4BFDCD0B/FREEBSD-13.1-P2/13.1-STABLE/AMD64/D2BF200529>) |
| 15b7:5017 | 15b7:5017 | Sandisk          | NVMe Controller                      | 7     | nvme       | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 7     | nvme       | [52CC45ABA9](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/28ABD5EC0B9C/GHOSTBSD-22.07.16/13.1-STABLE/AMD64/52CC45ABA9>) |
| 2646:500c | 2646:500c | Kingston Tech... |                                      | 7     | nvme       | [CFFED92600](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X515DAP_M515DA/606098250228/FREEBSD-13.1/13.1-RELEASE/AMD64/CFFED92600>) |
| 8086:2522 | 8086:3806 | Intel            | NVMe Optane Memory Series            | 7     | nvme       | [53C643DC95](<Desktop/CncTion/Jasper-4/Jasper-4L/E64EE31D78D3/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/53C643DC95>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 7     | nvme       | [D9746AD1C3](<Desktop/CncTion/N5105/N5105-4L/AD39769DC42D/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/D9746AD1C3>) |
| 15b7:5008 | 15b7:5008 | SanDisk          | NVMe Controller                      | 6     | nvme       | [EF722FC37B](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15IHU6 82K1/2EB06850DB75/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/EF722FC37B>) |
| 1d97:1160 | 1d97:1160 | Shenzhen Long... | unknown                              | 6     | nvme       | [78BCCCDA01](<Desktop/CncTion/N5105/N5105-4L/667B90399F5F/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/78BCCCDA01>) |
| 15b7:5019 | 15b7:5019 | SanDisk          | unknown                              | 5     | nvme       | [56BC3B04FD](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX434FL_UX434FL/D46D4BF5A008/FREEBSD-13.1/13.1-RELEASE/AMD64/56BC3B04FD>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 5     | nvme       | [45D6590312](<Desktop/CncTion/N5105/N5105-4L/05C6F394D27E/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/45D6590312>) |
| 1c5c:1627 | 1c5c:1627 | SK hynix         | hynix unknown                        | 5     | nvme       | [DE7AC2F8D1](<Notebook/Dell/Precision/Precision 5540/033785BEA91D/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/DE7AC2F8D1>) |
| 1db2:2302 | 1db2:2302 | ATP ELECTRONICS  |                                      | 5     | nvme       | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 29    | ciss       | [B281EEC189](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/D6765403633D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/B281EEC189>) |
| 1000:0060 | 1028:1f0c | Broadcom / LSI   | MegaRAID SAS 1078                    | 25    | mfi        | [5D6BABDA3E](<Server/Dell/PowerEdge/PowerEdge R710/209AA94D6139/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/5D6BABDA3E>) |
| 1000:005b | 1028:1f34 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 16    | mfi        | [5B86B7C534](<Server/Dell/PowerEdge/PowerEdge R320/7B1C75B3FBB5/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5B86B7C534>) |
| 8086:2822 | 1028:05a4 | Intel            | SATA Controller [RAID mode]          | 16    | ahci       | [A477C2B046](<Desktop/Dell/OptiPlex/OptiPlex 9020/C840DA9F22BC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A477C2B046>) |
| 1000:005b | 1028:1f38 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 14    | mfi        | [A4E6DB54D8](<Server/Dell/PowerEdge/PowerEdge R420/787A628CC8C0/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A4E6DB54D8>) |
| 1000:0079 | 1028:1f17 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 14    | mfi        | [51FBBAF053](<Server/Dell/PowerEdge/PowerEdge R410/8ACC974830FF/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/51FBBAF053>) |
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 13    | ahci       | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 1000:0073 | 1028:1f51 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 12    | mfi        | [8783F6CE77](<Server/Dell/PowerEdge/PowerEdge R320/13A9DFD95387/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/8783F6CE77>) |
| 1000:0072 | 1734:1177 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 11    | mps        | [A0A26F529C](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/BB7614C3933F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A0A26F529C>) |
| 1000:005f | 1028:1f44 | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 10    | mfi        | [C5AF7BF9E5](<Server/Dell/PowerEdge/PowerEdge R340/3C18F7464176/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C5AF7BF9E5>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 10    | ciss       | [B9DF714117](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/0FE7DBEBF7BB/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B9DF714117>) |
| 1000:005d | 1028:1f49 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 9     | mfi        | [7E2A57616B](<Server/Dell/PowerEdge/PowerEdge R640/2A30F8C38231/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/7E2A57616B>) |
| 8086:2822 | 1028:052c | Intel            | SATA Controller [RAID mode]          | 9     | ahci       | [986F18FA08](<Desktop/Dell/OptiPlex/OptiPlex 9010/1A8752C8E9E4/OPNSENSE-22.1.10/13.0-STABLE/AMD64/986F18FA08>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 7     | ciss       | [1A754B2A9E](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G5/851ACF3B4A4E/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/1A754B2A9E>) |
| 8086:2822 | 1028:047e | Intel            | SATA Controller [RAID mode]          | 7     | ahci       | [B71ECDF543](<Desktop/Dell/OptiPlex/OptiPlex 990/A3ED196F0551/OPNSENSE-22.1.8/13.0-STABLE/AMD64/B71ECDF543>) |
| 8086:2826 | 103c:1589 | Intel            | C600/X79 series chipset SATA RAID... | 7     | ahci       | [3F9D19B372](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.10/13.0-STABLE/AMD64/3F9D19B372>) |
| 1000:005d | 1028:1f47 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 6     | mfi        | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 1000:005f | 1028:1f4b | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 6     | mfi        | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 103c:3230 | 103c:3235 | Hewlett-Packard  | Smart Array Controller               | 6     | ciss       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:2822 | 1458:b005 | Intel            | SATA Controller [RAID mode]          | 6     | ahci       | [8D278732DD](<Desktop/Gigabyte Technology/Z390/Z390 UD/0B8E30771563/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/8D278732DD>) |
| 8086:467f | 1043:8694 | Intel            | Volume Management Device NVMe RAI... | 6     | pcib       | [C3281EB186](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/967511C3CD54/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/C3281EB186>) |
| 13c1:1004 | 13c1:1004 | 3ware            | 9650SE SATA-II RAID PCIe             | 5     | twa        | [01898B2FFB](<Desktop/ACMA/X8/X8SIE/EDFA6F8E9EEC/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/01898B2FFB>) |
| 9005:0286 | 1014:9580 | Adaptec          | AAC-RAID (Rocket)                    | 5     | aac        | [41D40D8752](<Server/IBM/System/System x3650 -[797941Y]-/B6A5CBBF3013/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/41D40D8752>) |
| 103c:323a | 103c:3243 | Hewlett-Packard  | Smart Array G6 controllers           | 4     | ciss       | [289D2F383B](<Server/Hewlett-Packard/ProLiant/ProLiant DL180 G6/8E2A024CC455/FREEBSD-12.3-P7/12.3-RELEASE-P6/AMD64/289D2F383B>) |
| 103c:323b | 103c:3351 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 4     | ciss       | [43C3EAFD9D](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen8/98A8C2381905/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/43C3EAFD9D>) |
| 8086:1c04 | 1028:04dd | Intel            | 6 Series/C200 Series Desktop SATA... | 4     | ahci       | [0325ADE874](<Server/Dell/PowerEdge/PowerEdge R210 II/092D9B4C961E/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/0325ADE874>) |
| 8086:2822 | 1028:07c5 | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [50FBB0435C](<Desktop/Dell/PowerEdge/PowerEdge T30/8C16168DE41F/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/50FBB0435C>) |
| 8086:2822 | 103c:130a | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [A24F08281D](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/A24F08281D>) |
| 8086:2826 | 103c:158a | Intel            | C600/X79 series chipset SATA RAID... | 4     | ahci       | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 8086:282a | 1028:05ca | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [970234B430](<Notebook/Dell/Latitude/Latitude E7240/1C50E392EFBF/FREEBSD-13.1/13.1-RELEASE/AMD64/970234B430>) |
| 1000:005d | 1000:9363 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 3     | mfi        | [AB6E70ABCA](<Server/Intel/S1200/S1200SP/BF2910D7912E/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/AB6E70ABCA>) |
| 1000:005d | 1028:1f42 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 3     | mrsas      | [0B239C3286](<Server/Dell/PowerEdge/PowerEdge R540/34807F166517/OPNSENSE-22.1.7/13.0-STABLE/AMD64/0B239C3286>) |
| 1000:0073 | 1734:1177 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 3     | mfi        | [3D46E0EACE](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S6/02405A2DD385/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/3D46E0EACE>) |
| 1000:0079 | 1014:03b2 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 3     | mfi        | [11BC81EF41](<Server/Intel/S1200/S1200BTL/C865C7CEDA20/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/11BC81EF41>) |
| 1000:0079 | 1014:03c7 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 3     | mfi        | [8BBC599CDD](<Server/IBM/System/System x3650 M3 -[7945K3G]-/4E22FDB71865/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/8BBC599CDD>) |
| 1000:10e2 | 1028:2176 | Broadcom / LSI   | MegaRAID 12GSAS/PCIe Secure SAS39xx  | 3     | mrsas      | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 103c:323a | 103c:3241 | Hewlett-Packard  | Smart Array G6 controllers           | 3     | ciss       | [379FCF9804](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 G6/8034C079A069/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/379FCF9804>) |
| 1095:3114 | 1095:3114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 3     | atapci     | [BBD42243AE](<Desktop/TYAN Computer/Tiger/Tiger K8W Dual AMD Opteron, S2875/A029250D83FC/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/BBD42243AE>) |
| 8086:2822 | 1028:0276 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [24B9490C77](<Desktop/Dell/OptiPlex/OptiPlex 960/07A3501CD581/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/24B9490C77>) |
| 8086:2822 | 1028:0620 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [BB86FB3E67](<Desktop/Dell/PowerEdge/PowerEdge T20/C68E45CBB411/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BB86FB3E67>) |
| 8086:2822 | 1028:06ba | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [D06E05C67A](<Desktop/Dell/OptiPlex/OptiPlex 5040/6A6458ACB6C7/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/D06E05C67A>) |
| 8086:2822 | 1028:07a3 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [0D13116822](<Desktop/Dell/OptiPlex/OptiPlex 3050/7C6D11637F94/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D13116822>) |
| 8086:2822 | 1028:085b | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [3A6606E75A](<Desktop/Dell/OptiPlex/OptiPlex 5060/E8B372160376/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3A6606E75A>) |
| 8086:2822 | 103c:8768 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [5AB1DADBAB](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F54ADC493621/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5AB1DADBAB>) |
| 8086:2822 | 1849:a282 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [803B44339B](<Desktop/ASRock/B250/B250M-HDV/BD56D24CB794/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/803B44339B>) |
| 8086:2826 | 1028:0617 | Intel            | C600/X79 series chipset SATA RAID... | 3     | ahci       | [FFBB7E1A96](<Desktop/Dell/Precision/Precision Tower 5810/6B5E6CCB6269/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/FFBB7E1A96>) |
| 8086:2826 | 17aa:30b0 | Intel            | C600/X79 series chipset SATA RAID... | 3     | ahci       | [D6111B8FF1](<Server/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/C9B365EFBC6F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D6111B8FF1>) |
| 8086:467f |           | Intel            | Volume Management Device NVMe RAI... | 3     | pcib       | [371F734E07](<Notebook/MSI/GF76/GF76 12UE/78E19812B122/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/371F734E07>) |
| 8086:8d06 | 1590:009c | Intel            | C610/X99 series chipset SATA Cont... | 3     | ahci       | [3797CBF278](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/3F969F9A8971/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/3797CBF278>) |
| 8086:8d66 | 1590:009d | Intel            | C610/X99 series chipset sSATA Con... | 3     | ahci       | [3797CBF278](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/3F969F9A8971/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/3797CBF278>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1000:3020 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 27    | mps        | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 1000:0072 | 1028:1f1c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 12    | mps        | [10CA365B40](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/10CA365B40>) |
| 8086:1d6b | 103c:1589 | Intel            | C602 chipset 4-Port SATA Storage ... | 10    | isci       | [8A927B43CB](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D768D5739884/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/8A927B43CB>) |
| 1000:0072 | 1028:1f1d | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 7     | mps        | [E93B47ED87](<Server/Dell/PowerEdge/PowerEdge R210 II/00CEB046891F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E93B47ED87>) |
| 1000:0087 | 1000:3020 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 7     | mps        | [CA71C8AB2B](<Desktop/Dell/OptiPlex/OptiPlex 790/987AF9001591/TRUENAS-13.1-P2/13.1-RELEASE-P2/AMD64/CA71C8AB2B>) |
| 1000:0072 | 1028:1f1e | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 6     | mps        | [299FCE37CB](<Server/Dell/PowerEdge/PowerEdge R610/C023161D22D2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/299FCE37CB>) |
| 1000:0097 | 1000:30e0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 6     | mpr        | [D32C9457B9](<Server/ASUSTek Computer/WS-C621E-SAGE/WS-C621E-SAGE Series/8BEB8E095C46/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/D32C9457B9>) |
| 8086:1d6b | 15d9:0660 | Intel            | C602 chipset 4-Port SATA Storage ... | 6     | isci       | [97E19B4CD1](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/1AF57826CF89/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/97E19B4CD1>) |
| 8086:1d6b | 103c:158a | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 1000:0097 | 1028:1f53 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 4     | mpr        | [30602E7478](<Server/Dell/PowerEdge/PowerEdge R630/24116AF6B008/OPNSENSE-22.1.10/13.0-STABLE/AMD64/30602E7478>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 4     | mpr        | [5E615ED399](<Server/Supermicro/SYS-5029/SYS-5029P-WTR/87F57A08C9C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/5E615ED399>) |
| 1000:0070 | 1000:3010 | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 3     | mps        | [0EEA35E069](<Desktop/Dell/Precision/Precision WorkStation T3500/2B5473C76A7D/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/0EEA35E069>) |
| 1000:0072 | 1000:0072 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [F7DE46B627](<Desktop/CIARA TECHNOLOGIES/1X8-X6/1X8-X6 CACHEH/CAC8276E190F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/F7DE46B627>) |
| 1000:0072 | 1000:3040 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [2B2B508432](<Server/Intel/S1200/S1200RP_SE/4DF73AF97478/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/2B2B508432>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [DC582EA4D3](<Desktop/ASRock/B550M/B550M Pro4/6D75D10E9FEA/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/DC582EA4D3>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [2BD1529913](<Server/Supermicro/MBD-X8/MBD-X8DT6-A-IS018/9FC8D16648D3/FREEBSD-13.1/13.1-RELEASE/AMD64/2BD1529913>) |
| 1000:0087 | 1028:1f38 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mps        | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 103c:3239 | 103c:21c7 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 3     | ciss       | [3A9EC9299C](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/96C75848A993/FREEBSD-13.1/13.1-RELEASE/AMD64/3A9EC9299C>) |
| 1000:0016 | 1028:1fcb | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [C34D5C2BE3](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C34D5C2BE3>) |
| 1000:0016 | 1028:1fcd | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [AA44179A5F](<Server/Dell/PowerEdge/PowerEdge R640/FB4118FD56BA/FREEBSD-12.2-P1/12.2-RELEASE-P1/AMD64/AA44179A5F>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 2     | mps        | [2F589ABF33](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/0AEF40CD9E4E/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/2F589ABF33>) |
| 1000:0070 | 1014:040e | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 2     | mps        | [80FA278909](<Server/IBM/System/System X3250 M5 -[5458E8G]-/01E6FA2422F0/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/80FA278909>) |
| 1000:0072 | 103c:3371 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mps        | [EA62F49750](<Desktop/Supermicro/X9/X9DRD-7LN4F/97D90A6AA706/TRUENAS-12.2-P10/12.2-RELEASE-P10/AMD64/EA62F49750>) |
| 1000:0087 | 1028:1f34 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mps        | [FBCC442D47](<Server/Dell/PowerEdge/PowerEdge R720xd/9494C365C719/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBCC442D47>) |
| 1000:0097 | 1028:1f46 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [BA13BBECFD](<Server/Dell/PowerEdge/PowerEdge R730/BC55DA270D03/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/BA13BBECFD>) |
| 1000:0097 | 1849:0097 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [C04BBD635B](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/6457E123E761/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/C04BBD635B>) |
| 8086:1d6b | 1028:0497 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [C8993DCCA5](<Desktop/Dell/Precision/Precision T3600/1BDA06E274A1/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/C8993DCCA5>) |
| 8086:1d6b | 15d9:0628 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [B8C89BDCA8](<Desktop/Supermicro/X9/X9DR3-F/3573CEE1CD7B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8C89BDCA8>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [0F3EE4CAAB](<Desktop/Fujitsu/CELSIUS/CELSIUS M720/7B5122D4B3E4/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/0F3EE4CAAB>) |
| 8086:1d6b | 17aa:1026 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [1EC71F814B](<Desktop/Lenovo/ThinkStation/ThinkStation S30 43511K5/E8B0027862B5/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1EC71F814B>) |
| 1000:005d | 15d9:0a09 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [B44FE94131](<Desktop/Supermicro/SSG-2028/SSG-2028R-E1CR24N/201BEB766364/FREENAS-11.3-P9/11.3-RELEASE-P9/AMD64/B44FE94131>) |
| 1000:005d | 19e5:da07 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [AC2C7107D3](<Server/HUAWEI/RH2288H/RH2288H V3/FFCB8F761596/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/AC2C7107D3>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mps        | [CF2E66B6AA](<Server/Supermicro/X10/X10SLL-F/A57790A3890F/FREEBSD-12.2/12.2-RELEASE/AMD64/CF2E66B6AA>) |
| 1000:0072 | 1000:3050 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [28FDD2C2DC](<Desktop/Supermicro/X9/X9SCL-X9SCM/70812EDDCEB0/FREENAS-11.2-STABLE/11.2-STABLE/AMD64/28FDD2C2DC>) |
| 1000:0072 | 1000:3060 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [F88EAF06AC](<Server/Intel/S1200/S1200BTL/BD51E5A20141/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/F88EAF06AC>) |
| 1000:0072 | 1000:30f0 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [90C27497D9](<Desktop/ASUSTek Computer/Crosshair/Crosshair V Formula/08D4551A4F47/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/90C27497D9>) |
| 1000:0072 | 1043:843c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [D50484387C](<Server/ASUSTek Computer/P8B-E/P8B-E Series/9F223A3AC70D/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/D50484387C>) |
| 1000:0086 | 103c:158b | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 1000:0087 | 1000:3030 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [E59D5D41A5](<Server/Hewlett-Packard/ProLiant/ProLiant SE326M1R2/9702C33A6606/FREENAS-11.3-P7/11.3-RELEASE-P7/AMD64/E59D5D41A5>) |
| 1000:0087 | 8086:3517 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [176C42716F](<Server/McAfee/Appliance/Appliance B4/0F673A2423F1/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/176C42716F>) |
| 1000:0090 | 1137:0155 | Broadcom / LSI   | SAS3108 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 1000:0097 | 1028:0619 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [DDDF168DB9](<Desktop/Dell/Precision/Precision Tower 7910/9E71C365962A/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/DDDF168DB9>) |
| 1000:00ac | 1000:3000 | Broadcom / LSI   | SAS3416 Fusion-MPT Tri-Mode I/O C... | 1     | mpr        | [23196AA66B](<Desktop/ASRock/Z390/Z390M-ITX-ac/40E52D5C50CF/FREEBSD-12.2-P5/12.2-RELEASE-P4/AMD64/23196AA66B>) |
| 103c:3239 | 103c:21c8 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 1     | ciss       | [C2BB148E8A](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/37E855C98CE1/FREEBSD-12.2-P2/12.2-RELEASE-P2/AMD64/C2BB148E8A>) |
| 8086:1d60 | 1028:0496 | Intel            | C608 chipset Dual 4-Port SATA/SAS... | 1     | isci       | [D9D86D5BFD](<Desktop/Dell/Precision/Precision T5600/ADD168454A3E/GHOSTBSD-22.04.06/13.0-STABLE/AMD64/D9D86D5BFD>) |
| 8086:1d60 | 1028:0497 | Intel            | C608 chipset Dual 4-Port SATA/SAS... | 1     | isci       | [B6044FB84C](<Desktop/ASRock/G41/G41M-VS3/F606D604CBAF/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/B6044FB84C>) |
| 8086:1d69 | 17aa:1026 | Intel            | C604/X79 series chipset 4-Port SA... | 1     | isci       | [DD545FB588](<Desktop/Lenovo/ThinkStation/ThinkStation S30 0569A93/3A5A3AB166EF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DD545FB588>) |
| 8086:1d6a | 8086:3583 | Intel            | C600/X79 series chipset Dual 4-Po... | 1     | isci       | [474B0E44EA](<Server/Wortmann AG/TERRA/TERRA Server/8361012A53E8/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/474B0E44EA>) |
| 8086:1d6b | 103c:158b | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1425:5501 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 10    |            | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 1425:4501 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 8     |            | [70A786B8B5](<Server/Supermicro/X10/X10SLM+-LN4F/F4A1F01A1AAE/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/70A786B8B5>) |
| 1000:0058 | 1028:1f0e | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 6     | mpt        | [CA78843973](<Server/Dell/PowerEdge/PowerEdge R710/58CE68FFFFBC/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CA78843973>) |
| 1000:0058 | 1028:1f0f | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 5     | mpt        | [847CA0ACB9](<Server/Dell/PowerEdge/PowerEdge R410/AA3B52468CEC/OPNSENSE-22.1.6/13.0-STABLE/AMD64/847CA0ACB9>) |
| 1425:5503 |           | Chelsio Commu... | T540-CR Unified Wire Storage Cont... | 4     |            | [1CFE8960A1](<Server/Supermicro/Super/Super Server/574FD572E67A/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/1CFE8960A1>) |
| 17d3:1300 | 17d3:1300 | Areca Technology | ARC-1300ix-16 16-Port PCI-Express... | 4     | arcsas     | [66BBED8D59](<Desktop/ASUSTek Computer/P6T/P6T SE/9C422F2B290E/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/66BBED8D59>) |
| 9004:8178 |           | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 4     | ahc        | [459C674B3B](<Desktop/ASRock/Z77/Z77 Extreme4/4A8FC6177080/FREEBSD-12.3/12.3-RELEASE/AMD64/459C674B3B>) |
| 1000:0058 | 1014:0394 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mpt        | [5F9F2C2232](<Server/IBM/System/System x -[79463ag]-/9FE86345EDC2/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/5F9F2C2232>) |
| 1000:0058 | 1028:1f10 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mpt        | [9F4AC237DB](<Server/Dell/PowerEdge/PowerEdge 1950/2213302D7B22/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/9F4AC237DB>) |
| 1000:0030 | 1000:50c0 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 2     | mpt        | [6D3E23081C](<Server/Others/CMB-A9/CMB-A9SC2/4FED9738980F/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6D3E23081C>) |
| 1000:0030 | 103c:322a | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 2     | mpt        | [2F26C69137](<Desktop/Dell/OptiPlex/OptiPlex 390/A5CC20B80AD3/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/2F26C69137>) |
| 1000:0054 | 1028:1f09 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mpt        | [E98F23CD45](<Server/Dell/PowerEdge/PowerEdge SC1435/269A637D74C2/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/E98F23CD45>) |
| 1000:0058 | 103c:130b | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mpt        | [25B7A10166](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/79ADC3087F2D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/25B7A10166>) |
| 1425:4502 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Storage Cont... | 2     |            | [BD9D4BB7A3](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/10EF43C278BD/OPNSENSE-22.1.4/13.0-STABLE/AMD64/BD9D4BB7A3>) |
| 1425:5507 |           | Chelsio Commu... | T520-SO Unified Wire Storage Cont... | 2     |            | [A0A26F529C](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/BB7614C3933F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A0A26F529C>) |
| 1425:5583 |           | Chelsio Commu... | T540-5083 Unified Wire Storage Co... | 2     |            | [55E9734C09](<Desktop/JGINYUE/B85I/B85I PLUS V1.0/C745913DBF54/OPNSENSE-22.1.6/13.0-STABLE/AMD64/55E9734C09>) |
| 1425:6508 |           | Chelsio Commu... | T62100-SO-CR Unified Wire Storage... | 2     |            | [D120C268F7](<Desktop/Supermicro/SYS-6028/SYS-6028R-T/789334D78445/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/D120C268F7>) |
| 5853:0001 | 5853:0001 | XenSource        | Xen Platform Device                  | 2     | xenpci     | [FFB1FD95D3](<Desktop/PC Engines/apu/apu4/8CB6C93947A1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/FFB1FD95D3>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 2     | ahc        | [C67CCF8BC6](<Desktop/Dell/Inspiron/Inspiron 530/3762C968ACCD/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C67CCF8BC6>) |
| 1000:0001 | 1000:1000 | Broadcom / LSI   | 53c810                               | 1     | sym        | [4EE625240F](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VII HERO/37724E1F8F3B/FREEBSD-12.1-STABLE/12.1-STABLE-20200612/AMD64/4EE625240F>) |
| 1000:000f | 1000:1000 | Broadcom / LSI   | 53c875                               | 1     | sym        | [DAE16641BB](<Desktop/ASUSTek Computer/M2/M2NPV-MX/14DC624B8825/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/DAE16641BB>) |
| 1000:0030 | 1000:10b0 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 1000:0030 | 1028:016c | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 1000:0030 | 1734:1041 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [ADB972BF8E](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX200S2/C657395B089D/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/ADB972BF8E>) |
| 1000:0054 | 103c:0a98 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mpt        | [655FC531FB](<Desktop/Hewlett-Packard/xw8600/xw8600 Workstation/0566D4E23583/OPNSENSE-22.1.9/13.0-STABLE/AMD64/655FC531FB>) |
| 1000:0056 | 1000:1000 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [7B2DE50C60](<Desktop/Apple/Xserve3/Xserve3,1/D499BA477C7F/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/7B2DE50C60>) |
| 1000:0056 | 1734:1131 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [FF2213E848](<Desktop/Fujitsu/CELSIUS/CELSIUS M470-2/50E1DC1E3DE9/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/FF2213E848>) |
| 1000:0058 | 103c:3229 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [AE37F4EB2D](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/2E9FE6581089/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/AE37F4EB2D>) |
| 1000:0058 | 15d9:a480 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [27FC294BCA](<Desktop/Supermicro/X7/X7DCL/3D21E845B8F9/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/27FC294BCA>) |
| 1000:0058 | 17aa:101d | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [526E5EEA0B](<Desktop/Lenovo/ThinkStation/ThinkStation D10 6493WEU/6A717F675FF7/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/526E5EEA0B>) |
| 1000:0059 | 15d9:0004 | Broadcom / LSI   | MegaRAID SAS 8208ELP/8208ELP         | 1     | mpt        | [7D0E121099](<Desktop/Supermicro/X8/X8STi/00B85E5857AF/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/7D0E121099>) |
| 1103:2300 | 11ab:11ab | HighPoint Tec... | RocketRAID 230x 4 Port SATA-II Co... | 1     | hptrr      | [AA29EB9C75](<Desktop/Gigabyte Technology/H67/H67A-UD3H-B3/48803C404D01/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/AA29EB9C75>) |
| 1425:5511 |           | Chelsio Commu... | T520-LL-CR Unified Wire Storage C... | 1     |            | [3A61EB7BAE](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/C55069592DD2/OPNSENSE-22.1.9/13.0-STABLE/AMD64/3A61EB7BAE>) |
| 1425:5584 |           | Chelsio Commu... | T540-5084 Unified Wire Storage Co... | 1     |            | [2BBA0377AE](<Desktop/MSI/MS/MS-7733/A84A1CCB8340/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2BBA0377AE>) |
| 1425:6503 |           | Chelsio Commu... | T6425-CR Unified Wire Storage Con... | 1     |            | [17A763A917](<Desktop/MSI/MS-7/MS-7B24/D5C8F44D7DED/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/17A763A917>) |
| 9004:3860 | 9004:3869 | Adaptec          | AHA-2930CU                           | 1     | ahc        | [C7D877A988](<Desktop/Supermicro/X7/X7SBL/725A0E7344D4/FREEBSD-12.3/12.3-RELEASE/AMD64/C7D877A988>) |
| 9004:5078 |           | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 1     | ahc        | [1BC05B5951](<Desktop/Dell/Precision/Precision WorkStation T3400/ADEEA3484D9F/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1BC05B5951>) |
| 9004:8178 | 9004:7881 | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 1     | ahc        | [75E86A92F7](<Desktop/ASUSTek Computer/All/All Series/07E6A3D81A80/FREEBSD-12.2-P1/12.2-RELEASE-P1/AMD64/75E86A92F7>) |
| 9005:0010 | 9005:a180 | Adaptec          | AHA-2940U2/U2W                       | 1     | ahc        | [6D3E23081C](<Server/Others/CMB-A9/CMB-A9SC2/4FED9738980F/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6D3E23081C>) |
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 1     | ahd        | [EB73C9D13D](<Desktop/Supermicro/X9/X9DAi/558BB9BB7FC9/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/EB73C9D13D>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1567 | 1022:1567 | AMD              | Mullins IOMMU                        | 166   |            | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 143   |            | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 117   |            | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 117   |            | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 104   |            | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 8086:6f76 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 97    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 96    | amdiommu   | [AF190C38E9](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NKS0HN1N/FFA6D6E4D3C7/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/AF190C38E9>) |
| 8086:6f88 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 96    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f8a |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 96    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fae |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 96    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6faf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 96    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fbc |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 94    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fbd |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 94    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fbe |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 94    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fbf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 94    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 87    | amdiommu   | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 8086:6f1d | 8086:6f1d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f1e | 8086:6f1e | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f1f | 8086:6f1f | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f71 | 8086:6f71 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f98 | 8086:6f98 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f99 | 8086:6f99 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f9a | 8086:6f9a | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f9c | 8086:6f9c | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fa0 | 8086:6fa0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fa8 | 8086:6fa8 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6faa | 8086:6faa | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fab | 8086:6fab | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fc0 | 8086:6fc0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fe0 | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fe1 | 8086:6fe1 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6ff8 | 8086:6ff8 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6ffc | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6ffd | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6ffe | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 80    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f81 | 8086:6f81 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 78    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fb0 | 8086:6fb0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 78    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fb1 | 8086:6fb1 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 78    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fb2 | 8086:6fb2 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 78    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fb3 | 8086:6fb3 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 78    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fe2 | 8086:6fe2 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 78    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6fe3 | 8086:6fe3 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 78    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:1f15 |           | Intel            | Atom processor C2000 SMBus 2.0       | 74    |            | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:1f16 |           | Intel            | Atom processor C2000 RCEC            | 74    |            | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:2f88 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 71    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f8a |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 71    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fae |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 71    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2faf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 71    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fbe |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 71    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fbf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 71    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7808 | 1022:7808 | AMD              | FCH USB EHCI Controller              | 278   | ehci       | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 256   | xhci       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 1022:7814 | 1022:1410 | AMD              | FCH USB XHCI Controller              | 252   | xhci       | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 237   | xhci       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 219   | xhci       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 154   | xhci       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:4ded | 8086:7270 | Intel            | Jasper Lake USB 3.1 XHCI Host Con... | 147   | xhci       | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 1022:149c | 1022:148c | AMD              | Matisse USB 3.0 Host Controller      | 107   | xhci       | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 104   | xhci       | [CDCCF8CECB](<Mini Pc/AWOW/AK/AK34/3487CD2A0FE8/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/CDCCF8CECB>) |
| 1022:43d5 | 1b21:1142 | AMD              | 400 Series Chipset USB 3.1 xHCI C... | 99    | xhci       | [85AECF8C3F](<Desktop/MSI/MS-7/MS-7A38/2325A856795F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/85AECF8C3F>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 81    | xhci       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 76    | ehci       | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 8086:9c26 | 8086:7270 | Intel            | 8 Series USB EHCI #1                 | 75    | ehci       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1022:7808 | 1734:1202 | AMD              | FCH USB EHCI Controller              | 74    | ehci       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:9ca6 | 8086:7270 | Intel            | Wildcat Point-LP USB EHCI Controller | 74    | ehci       | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 8086:9cb1 | 8086:7270 | Intel            | Wildcat Point-LP USB xHCI Controller | 74    | xhci       | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 8086:0f34 | 8086:0f34 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 72    | ehci       | [57F357784C](<Mini Pc/AMI/Aptio/Aptio CRB/2CC23D52E14F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/57F357784C>) |
| 1002:4397 | 1002:4397 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 71    | ohci       | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 1022:7814 | 1734:1202 | AMD              | FCH USB XHCI Controller              | 70    | xhci       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:149c | 1022:1486 | AMD              | Matisse USB 3.0 Host Controller      | 66    | xhci       | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 103c:3300 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 66    | uhci       | [43C3EAFD9D](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen8/98A8C2381905/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/43C3EAFD9D>) |
| 8086:8c26 | 8086:8c26 | Intel            | 8 Series/C220 Series Chipset Fami... | 61    | ehci       | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 8086:8c2d | 8086:8c2d | Intel            | 8 Series/C220 Series Chipset Fami... | 61    | ehci       | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 1002:4399 | 1002:4399 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 60    | ohci       | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 60    | ehci       | [19B95B3238](<Firewall/Sophos/SG/SG/565D06ED3C8E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/19B95B3238>) |
| 8086:8c31 | 8086:8c31 | Intel            | 8 Series/C220 Series Chipset Fami... | 58    | xhci       | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 1022:149c | 1043:87c0 | AMD              | Matisse USB 3.0 Host Controller      | 57    | xhci       | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:43ee | 1b21:1142 | AMD              | 500 Series Chipset USB 3.1 XHCI C... | 55    | xhci       | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 55    | xhci       | [62C09245A4](<System On Chip/Raspberry Pi Foundation/Raspberry/Raspberry Pi/69707B2A7C78/FREEBSD-13.1-P7/13.1-RELEASE-P6/ARM64/62C09245A4>) |
| 8086:2830 | 8086:2830 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 54    | uhci       | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:2836 | 8086:2836 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 54    | ehci       | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:2831 | 8086:2831 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 53    | uhci       | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 1022:7807 | 103c:213d | AMD              | FCH USB OHCI Controller              | 51    | ohci       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:7808 | 103c:213d | AMD              | FCH USB EHCI Controller              | 51    | ehci       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:7814 | 103c:213d | AMD              | FCH USB XHCI Controller              | 51    | xhci       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 8086:27c8 | 8086:27c8 | Intel            | NM10/ICH7 Family USB UHCI Control... | 50    | uhci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:27c9 | 8086:27c9 | Intel            | NM10/ICH7 Family USB UHCI Control... | 49    | uhci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 1b21:1042 | 1043:8488 | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 48    | xhci       | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:27cc | 8086:27cc | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 48    | ehci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:27ca | 8086:27ca | Intel            | NM10/ICH7 Family USB UHCI Control... | 46    | uhci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:0f35 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 45    | xhci       | [8D052CBF4C](<Mini Pc/Broachlink/NOAH/NOAH V2 E3845/AF93BF149B22/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/8D052CBF4C>) |
| 8086:1c26 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 44    | ehci       | [E975D67484](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E975D67484>) |
| 8086:1c2d | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 44    | ehci       | [E975D67484](<Server/Dell/PowerEdge/PowerEdge R210 II/58573A8F2438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E975D67484>) |
| 8086:27cb | 8086:27cb | Intel            | NM10/ICH7 Family USB UHCI Control... | 44    | uhci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 1022:7807 | 103c:8103 | AMD              | FCH USB OHCI Controller              | 43    | ohci       | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 1022:7807 | 1734:1202 | AMD              | FCH USB OHCI Controller              | 43    | ohci       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:7808 | 103c:8103 | AMD              | FCH USB EHCI Controller              | 43    | ehci       | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 1022:7814 | 103c:8103 | AMD              | FCH USB XHCI Controller              | 43    | xhci       | [ACB993FD8A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client TC/51D56BADAD82/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/ACB993FD8A>) |
| 8086:8c31 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 43    | xhci       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c26 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | ehci       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |

### Video (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14f1:8800 | 0070:3401 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [1BC05B5951](<Desktop/Dell/Precision/Precision WorkStation T3400/ADEEA3484D9F/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1BC05B5951>) |
| 14f1:8800 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 14f1:8852 | 0070:7911 | Conexant Systems | CX23885 PCI Video and Audio Decoder  | 1     |            | [436706F322](<Desktop/Lenovo/ThinkCentre/ThinkCentre M82 2756B94/2D6E0A36E7BA/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/436706F322>) |
| 14f1:8880 | 0070:2a38 | Conexant Systems | CX23887/8 PCIe Broadcast Audio an... | 1     |            | [C230C65919](<Desktop/BCM Advanced Research/MX81/MX81HV-MX81H/317BF301CDED/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/C230C65919>) |
| 1ade:3038 | 4254:5580 | Spin Master      | PCIe Video Bridge                    | 1     |            | [4A7705414F](<Desktop/Gigabyte Technology/H97/H97M-HD3/FDE04DEC0E85/FREEBSD-13.1/13.1-RELEASE/AMD64/4A7705414F>) |
| 1cd7:0004 |           | Nanjing Magew... |                                      | 1     |            | [A2270B6F09](<Desktop/ASUSTek Computer/PRIME/PRIME Z270-K/B28241EA93D9/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/A2270B6F09>) |
| 4444:0016 | 0070:8801 | Internext Com... | iTVC16 (CX23416) Video Decoder       | 1     |            | [64D4FB9B97](<Desktop/Hewlett-Packard/AY627AA-ABA/AY627AA-ABA a4313w/2B7EE5C08CC6/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/64D4FB9B97>) |
| bdbd:a10b | bdbd:a10b | Blackmagic De... | DeckLink                             | 1     |            | [020CCD74D8](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 CMT/D5FB9BCC8299/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/020CCD74D8>) |
| bdbd:a143 | bdbd:a143 | Blackmagic De... | DeckLink Mini Recorder 4K            | 1     |            | [30A582FCCB](<Desktop/ASRockRack/EP2/EP2C612D16FM/194ABDFCA96A/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/30A582FCCB>) |

### Wireless controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7360 | 8086:0020 | Intel            | XMM7360 LTE Advanced Modem           | 7     |            | [B2024820D1](<Notebook/Lenovo/ThinkPad/ThinkPad P53 20QNCTO1WW/EDACF56B05E1/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/B2024820D1>) |
| 8086:7360 | 1028:5820 | Intel            | XMM7360 LTE Advanced Modem           | 1     |            | [1BB6C1F63F](<Notebook/Dell/Latitude/Latitude 5400/418002D1A36C/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/1BB6C1F63F>) |
| 8086:7360 | 1cf8:8521 | Intel            | XMM7360 LTE Advanced Modem           | 1     |            | [8D49D50738](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 7th 20QES53R00/AB4C518C252E/FREEBSD-13.1/13.1-RELEASE/AMD64/8D49D50738>) |
| 8086:7560 | 1cf8:8654 | Intel            | XMM7560 LTE Advanced Pro Modem       | 1     |            | [809DA57D90](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon Gen 10 21CB000DUS/32571058500F/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/809DA57D90>) |
| 8086:7560 | 1cf8:8655 | Intel            | XMM7560 LTE Advanced Pro Modem       | 1     |            | [B7A491A010](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 3 21AK000GUK/B9EAF7E60D17/FREEBSD-13.1/13.1-RELEASE/AMD64/B7A491A010>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 116   |            | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 116   |            | [FAEBAB61F2](<Notebook/Deciso/OPNsense/OPNsense Appliance/2CF0D1993CCD/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/FAEBAB61F2>) |
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 112   |            | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 91    |            | [FBFF29A62A](<Desktop/ASRock/X470/X470 Gaming K4/FFA88723BDD5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/FBFF29A62A>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 42    |            | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 42    |            | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 41    |            | [1CCA4A556D](<Notebook/Deciso/OPNsense/OPNsense Appliance/2DD46B265269/OPNSENSE-23.1.1/13.1-RELEASE-P7/AMD64/1CCA4A556D>) |
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 36    |            | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 1022:1455 | 1043:8747 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 27    |            | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 1022:145a | 1043:8747 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 27    |            | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 1022:145a |           | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 26    |            | [1CCA4A556D](<Notebook/Deciso/OPNsense/OPNsense Appliance/2DD46B265269/OPNSENSE-23.1.1/13.1-RELEASE-P7/AMD64/1CCA4A556D>) |
| 1022:145a | 1022:7901 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 25    |            | [1CCA4A556D](<Notebook/Deciso/OPNsense/OPNsense Appliance/2DD46B265269/OPNSENSE-23.1.1/13.1-RELEASE-P7/AMD64/1CCA4A556D>) |
| 0000:0000 |           |                  | Device                               | 19    |            | [F5ACB2D032](<Desktop/Acer/Veriton/Veriton X2120G/4BA6B6BAA584/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F5ACB2D032>) |
| 8086:a1ec | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 0    | 19    |            | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 18    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 1022:1485 | 1043:8808 | AMD              | Starship/Matisse Reserved SPP        | 16    |            | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 1022:148a | 1043:8808 | AMD              | Starship/Matisse PCIe Dummy Function | 16    |            | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 8086:a1ed | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 1    | 14    |            | [2CBA6FBBB7](<Desktop/Supermicro/SYS-5019/SYS-5019D-FN8TP-2-NC041/F87B609ACF03/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/2CBA6FBBB7>) |
| 8086:8d7c | 1028:0601 | Intel            | C610/X99 series chipset SPSR         | 11    |            | [170F3CC041](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/170F3CC041>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 11    |            | [7AB6080DFE](<Server/Supermicro/Super/Super Server/EF3360E50027/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/7AB6080DFE>) |
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 10    |            | [3797CBF278](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/3F969F9A8971/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/3797CBF278>) |
| 8086:8d7c | 1043:8600 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [006553F965](<Desktop/ASUSTek Computer/All/All Series/5FA8341B7ABC/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/006553F965>) |
| 8086:9d35 | 17aa:2238 | Intel            | Sunrise Point-LP Integrated Senso... | 8     |            | [4CBD9F9314](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FQ000QUS/A325841E215E/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/4CBD9F9314>) |
| 8086:a1ec | 1028:07c9 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 1022:145a | 1002:15dd | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 6     |            | [38D7F55EF7](<Desktop/ASRockRack/X470/X470D4U/8404FC50C36B/FREEBSD-12.3-P8/12.3-RELEASE-P6/AMD64/38D7F55EF7>) |
| 8086:8d7c | 1028:0617 | Intel            | C610/X99 series chipset SPSR         | 6     |            | [FFBB7E1A96](<Desktop/Dell/Precision/Precision Tower 5810/6B5E6CCB6269/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/FFBB7E1A96>) |
| 8086:8d7c | 103c:212b | Intel            | C610/X99 series chipset SPSR         | 6     |            | [185934706D](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/5A7566F8C0EA/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/185934706D>) |
| 8086:8d7c | 15d9:0834 | Intel            | C610/X99 series chipset SPSR         | 6     |            | [59FF2014E5](<Server/Supermicro/Super/Super Server/C53FD6545133/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/59FF2014E5>) |
| 8086:8d7c | 1849:8d7c | Intel            | C610/X99 series chipset SPSR         | 6     |            | [30A582FCCB](<Desktop/ASRockRack/EP2/EP2C612D16FM/194ABDFCA96A/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/30A582FCCB>) |
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 6     |            | [5070C11C54](<Desktop/Dell/VEP-4600/VEP-4600-V910/BAE5F41CA0D2/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/5070C11C54>) |
| 1022:1485 | 1462:7c02 | AMD              | Starship/Matisse Reserved SPP        | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 1022:148a | 1462:7c02 | AMD              | Starship/Matisse PCIe Dummy Function | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 8086:8d7c | 15d9:0832 | Intel            | C610/X99 series chipset SPSR         | 5     |            | [49C49487E2](<Server/Supermicro/Super/Super Server/6694C5BBBD3A/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/49C49487E2>) |
| 8086:a1ec | 1028:0716 | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [7E2A57616B](<Server/Dell/PowerEdge/PowerEdge R640/2A30F8C38231/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/7E2A57616B>) |
| 1022:15e6 | 1849:15e6 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 4     |            | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 8086:5aa2 | 8086:5aa2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     |            | [16FA0B0102](<Desktop/NF692/1/1.0/9852CE16A74F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16FA0B0102>) |
| 8086:9d35 | 17aa:506d | Intel            | Sunrise Point-LP Integrated Senso... | 4     |            | [27702234CC](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga 20LH0018US/096E6C9C912E/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/27702234CC>) |
| 8086:a135 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [C9DDD32406](<Server/Supermicro/Super/Super Server/A912B2977FCE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/C9DDD32406>) |
| 8086:a1ed | 8086:7270 | Intel            | C620 Series Chipset Family MROM 1    | 4     |            | [851556AD46](<Server/TYAN Computer/B7109/B7109F77DV14HR-2T-N/A018E35F7CD3/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/851556AD46>) |
| 1022:1455 | 1462:7b86 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:145a | 1002:15d8 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [127E0126D1](<Desktop/ASRock/B450/B450 Gaming K4/ED84CEC3B15B/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/127E0126D1>) |
| 1022:145a | 1043:876b | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [92EAB8D065](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING II/1AD27D04291F/HELLOSYSTEM-0.7.0/13.1-RELEASE-P3/AMD64/92EAB8D065>) |
| 1022:145a | 1458:d000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1022:145a | 1462:7b86 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1028:0012 | 1028:0012 | Dell             | Remote Access Card 4 Daughter Car... | 3     | uart       | [F59F5613B3](<Server/Dell/PowerEdge/PowerEdge 1850/85B6D4D34540/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F59F5613B3>) |
| 1028:0014 | 1028:0014 | Dell             | Remote Access Card 4 Daughter Car... | 3     |            | [F59F5613B3](<Server/Dell/PowerEdge/PowerEdge 1850/85B6D4D34540/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F59F5613B3>) |
| 103c:193f | 103c:3381 | Hewlett-Packard  | Dynamic Smart Array B140i            | 3     |            | [3797CBF278](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/3F969F9A8971/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/3797CBF278>) |
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 3     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 15ec:5000 | 15ec:5000 | Beckhoff         |                                      | 3     |            | [6DB720018B](<Desktop/Beckhoff Automation/CBxx/CBxx63/D2340951707E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6DB720018B>) |
| 8086:3456 |           | Intel            | Ice Lake NorthPeak                   | 3     |            | [1CFE8960A1](<Server/Supermicro/Super/Super Server/574FD572E67A/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/1CFE8960A1>) |

