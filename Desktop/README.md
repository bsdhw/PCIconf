Most popular PCI devices in Desktops
====================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Desktops ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Infiniband ](#infiniband-pci)
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
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1439 | 1022:1234 | AMD              | Family 16h Processor Functions 5:1   | 401   | pcib       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:156b |           | AMD              | Family 16h (Models 30h-3fh) Host ... | 282   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1580 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 282   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1581 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 282   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1582 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 282   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1583 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 282   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1584 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 282   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1585 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 282   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:780e | 1022:780e | AMD              | FCH LPC Bridge                       | 279   | isab       | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:1566 | 1022:1566 | AMD              | Family 16h (Models 30h-3fh) Proce... | 248   | hostb      | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:9d13 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 237   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:9d12 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 234   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:9d14 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 232   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:9d11 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 229   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:9d10 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 228   | pcib       | [DDF2BCB808](<Desktop/Protectli/FW/FW6/51B65D660F9A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/DDF2BCB808>) |
| 8086:9d15 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 227   | pcib       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 222   | isab       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:31d8 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 220   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 1022:1452 |           | AMD              | Family 17h (Models 00h-1fh) PCIe ... | 217   | hostb      | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1002:4384 |           | AMD              | SBx00 PCI to PCI Bridge              | 201   | pcib       | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 178   | isab       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 178   | pcib       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 177   | hostb      | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:31d6 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 177   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:31d9 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 177   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 176   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:22ca | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 174   | pcib       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:31d7 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 171   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 111d:8018 |           | Microsemi / P... | PES12N3A 12-lane 3-Port PCI Expre... | 170   | pcib       | [3D912F92AA](<Desktop/Fujitsu/FUTRO/FUTRO S920/A1AC5CC7301E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3D912F92AA>) |
| 8086:31f0 |           | Intel            | Gemini Lake Host Bridge              | 166   | hostb      | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 164   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:5904 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 160   | hostb      | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 1022:1440 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 158   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:1441 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 158   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:1442 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 158   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:1443 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 158   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:1444 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 158   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:1445 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 158   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:1446 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 158   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:1447 |           | AMD              | Matisse/Vermeer Data Fabric: Devi... | 158   | hostb      | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:22cc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 151   | pcib       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:31db | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 148   | pcib       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:22ce | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 147   | pcib       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:4d87 | 8086:7270 | Intel            | Jasper Lake LPC Controller/eSPI C... | 147   | isab       | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:4dbe | 8086:7270 | Intel            | Jasper Lake PCIe Port #7             | 144   | pcib       | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 1022:1530 |           | AMD              | Family 16h Processor Function 0      | 143   | hostb      | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:1531 |           | AMD              | Family 16h Processor Function 1      | 143   | hostb      | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:1532 |           | AMD              | Family 16h Processor Function 2      | 143   | hostb      | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:1533 |           | AMD              | Family 16h Processor Function 3      | 143   | hostb      | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1022:1534 |           | AMD              | Family 16h Processor Function 4      | 143   | hostb      | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 8     | rtsx       | [1B938AA1A4](<Desktop/Shuttle/DH/DH370/7C934F0402CA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/1B938AA1A4>) |
| 10ec:522a | 1458:1000 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [752F962123](<Desktop/Gigabyte Technology/GB-BACE-3000/GB-BACE-3000-SBE/A8A80797C4EA/OPNSENSE-22.1.5/13.0-STABLE/AMD64/752F962123>) |
| 10ec:5209 | 1025:8020 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx       | [0C23FFDC5A](<Desktop/Acer/Revo/Revo 70/261B9131F0BC/OPNSENSE-22.1.10/13.0-STABLE/AMD64/0C23FFDC5A>) |
| 10ec:5209 | 103c:2ac7 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx       | [1A831A1D34](<Desktop/Hewlett-Packard/120/120-1135/CCE480D5F4F8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/1A831A1D34>) |
| 10ec:5209 | 103c:2af5 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     |            | [172F23EFAC](<Desktop/Hewlett-Packard/120/120-1333w/CF46E5F843F4/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/172F23EFAC>) |
| 10ec:5209 | 103c:3399 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     | rtsx       | [B11946A41A](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 Touch All-in-One PC/C898525C3ABA/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/B11946A41A>) |
| 10ec:5229 | 1025:0946 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx       | [A1E32DE7DA](<Desktop/Acer/RevoOne/RevoOne RL85/937E718E5858/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A1E32DE7DA>) |
| 10ec:5229 | 103c:2b3c | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     |            | [6C628D33AB](<Desktop/Hewlett-Packard/23/23-r103la/BA7ECECD07E8/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/6C628D33AB>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx       | [77E235D9F8](<Desktop/Dell/Inspiron/Inspiron 3050/EF4E88174903/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/77E235D9F8>) |
| 10ec:5229 | 17aa:3658 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx       | [2F13D4A946](<Desktop/Lenovo/IdeaCentre/IdeaCentre B545 10100/4154E650F617/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2F13D4A946>) |
| 10ec:5249 | 10cf:188a | Realtek Semic... | RTS5249 PCI Express Card Reader      | 1     | rtsx       | [7A69B91093](<Desktop/Fujitsu/FMVW77/FMVW77MB/31A33F545802/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/7A69B91093>) |
| 10ec:525a | 1028:06b9 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     |            | [A96DA2B00A](<Desktop/Dell/OptiPlex/OptiPlex 7040/3E1B177D4A77/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/A96DA2B00A>) |
| 10ec:525a | 1028:0a54 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx       | [8DE9FA2319](<Desktop/Dell/OptiPlex/OptiPlex 5090/00EAFA5318E9/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/8DE9FA2319>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx       | [794FE8EB65](<Desktop/Dell/XPS/XPS 8950/759E5D9BB90A/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/794FE8EB65>) |
| 10ec:525a | 1734:122e | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     |            | [8891E427E1](<Desktop/Fujitsu/CELSIUS/CELSIUS W570power/707C7BBA0561/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/8891E427E1>) |
| 10ec:525a | 1734:1249 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     |            | [2A0187EF7A](<Desktop/Fujitsu/CELSIUS/CELSIUS W580/2A362A4FB03E/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/2A0187EF7A>) |
| 10ec:5287 | 1025:1264 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 1     | rtsx       | [74B11992D7](<Desktop/Others/Others/Others/A81E0F9F7C65/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/74B11992D7>) |
| 10ec:5289 | 10ec:5289 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 1     |            | [0D40B0F9EB](<Desktop/Shuttle/XS35/XS35V3/463A73A74C81/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/0D40B0F9EB>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:19e2 |           | Intel            | Atom Processor C3000 Series Quick... | 34    | qat        | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 13    | qat        | [D28D10F385](<Desktop/ADI Engineering/RCC/RCC/6F22C4CD7334/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/D28D10F385>) |
| 8086:0434 |           | Intel            | DH89XXCC Series QAT                  | 12    |            | [2B70FDB96A](<Desktop/Intel/DENLOW_WS/DENLOW_WS/634E1D4A13FA/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2B70FDB96A>) |
| 8086:37c8 |           | Intel            | C62x Chipset QuickAssist Technology  | 7     | qat        | [5070C11C54](<Desktop/Dell/VEP-4600/VEP-4600-V910/BAE5F41CA0D2/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/5070C11C54>) |
| 8086:19e2 | 8086:19e2 | Intel            | Atom Processor C3000 Series Quick... | 3     | qat        | [547B59BE2B](<Desktop/Netgate/6100/6100/C1D72F5D06FF/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/547B59BE2B>) |
| 1000:0a05 | 1000:0a09 | Broadcom / LSI   |                                      | 2     |            | [5A8641FC9D](<Desktop/Cisco/SALEEN/SALEEN/40F23693CE8F/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/5A8641FC9D>) |
| 10de:03f4 |           | Nvidia           | MCP61 SMU                            | 1     |            | [009BC44D12](<Desktop/ONDA/N78G5D3/N78G5D3 Ver:5.00/8C38C68857FC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/009BC44D12>) |
| 10de:03f4 | 1462:7597 | Nvidia           | MCP61 SMU                            | 1     |            | [6BE2D8AEC7](<Desktop/MSI/MS/MS-7597/30A30607F88A/FREEBSD-12.2/12.2-RELEASE/AMD64/6BE2D8AEC7>) |
| 10de:0753 | 1025:0157 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 1     |            | [DB1E7A52B9](<Desktop/Acer/Aspire/Aspire X3200/F5C25C81945B/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/DB1E7A52B9>) |
| 10de:0753 | 1025:0228 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 1     |            | [FA59D6AA07](<Desktop/Acer/Aspire/Aspire X3400/DD3C224FC323/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/FA59D6AA07>) |
| 10de:07da | 1025:0137 | Nvidia           | MCP73 Co-processor                   | 1     |            | [6C169BDB6A](<Desktop/Dell/OptiPlex/OptiPlex 7040/D9A5C4B626A4/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/6C169BDB6A>) |
| 10de:0aa3 | 105b:0d52 | Nvidia           | MCP79 Co-processor                   | 1     |            | [79AB8EFB37](<Desktop/Foxconn/nT-330/nT-330i/70806ED76AFE/FREEBSD-12.1-P6/12.1-RELEASE-P6/AMD64/79AB8EFB37>) |
| 10de:0aa3 | 19da:a108 | Nvidia           | MCP79 Co-processor                   | 1     |            | [623EA6A889](<Desktop/Others/Others/Others/2BBBCF62335B/FREEBSD-12.1--HBSD/12.1-RELEASE-P7-HBSD/AMD64/623EA6A889>) |
| 19a2:0800 | 1734:11cc | Emulex           | ServerView iRMC HTI                  | 1     |            | [DAE7027898](<Desktop/Fujitsu/PRIMERGY/PRIMERGY TX2560 M1/4C2638BCEE71/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/DAE7027898>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 212   |            | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 193   |            | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:4de0 | 8086:7270 | Intel            | Management Engine Interface          | 146   |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 68    |            | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 55    |            | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 8086:8c3a | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    |            | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 42    |            | [DDF2BCB808](<Desktop/Protectli/FW/FW6/51B65D660F9A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/DDF2BCB808>) |
| 8086:8c3a | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 41    |            | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c3a | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 38    |            | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:1c3a | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 37    |            | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:1c3a | 1458:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 35    |            | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 8086:a13a | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 35    |            | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 8086:8c3d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | uart       | [A477C2B046](<Desktop/Dell/OptiPlex/OptiPlex 9020/C840DA9F22BC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A477C2B046>) |
| 8086:1e3a | 1043:84ca | Intel            | 7 Series/C216 Chipset Family MEI ... | 32    |            | [A2873D7C87](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/A2873D7C87>) |
| 8086:1e3a | 1028:0577 | Intel            | 7 Series/C216 Chipset Family MEI ... | 30    |            | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:1e3a | 1458:1c3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 28    |            | [D8C78B92A7](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4DBEA0F75A7B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D8C78B92A7>) |
| 8086:9de0 | 8086:7270 | Intel            | Cannon Point-LP MEI Controller #1    | 27    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:a360 | 1043:8694 | Intel            | Cannon Lake PCH HECI Controller      | 26    |            | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 25    |            | [B639F4670E](<Desktop/Intel/CNCTION-IAF/CNCTION-IAF/23F29A5F79A0/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B639F4670E>) |
| 8086:8c3a | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:8c3a | 1458:1c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 8086:8c3d | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | uart       | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:a2ba | 1043:8694 | Intel            | 200 Series PCH CSME HECI #1          | 25    |            | [FD39A615DE](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-K R2.0/7D5721B3D945/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD39A615DE>) |
| 8086:19d3 | 8086:19d3 | Intel            | Atom Processor C3000 Series ME HE... | 24    |            | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:5a9a | 1849:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 23    |            | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 8086:1c3a | 8086:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 22    |            | [B2176FAFCF](<Desktop/Intel/MAHOBAY/MAHOBAY/0D48ADEA90BB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2176FAFCF>) |
| 8086:8c3a | 1849:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 20    |            | [28E606751F](<Desktop/ASRock/H81/H81M-HDS/255D1BAAA00A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/28E606751F>) |
| 8086:a13a | 1458:1c3a | Intel            | 100 Series/C230 Series Chipset Fa... | 20    |            | [FB5A559634](<Desktop/Gigabyte Technology/B150/B150-HD3P/7B89078673EA/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/FB5A559634>) |
| 8086:a2ba | 1458:1c3a | Intel            | 200 Series PCH CSME HECI #1          | 20    |            | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 8086:1e3d | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 19    | uart       | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:8c3a | 8086:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 19    |            | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 8086:a360 | 1458:1c3a | Intel            | Cannon Lake PCH HECI Controller      | 19    |            | [6AC60B8104](<Desktop/Gigabyte Technology/B360/B360M-D2V/F8AFE9A62606/FREEBSD-13.1/13.1-RELEASE/AMD64/6AC60B8104>) |
| 8086:1c3a | 1028:04ad | Intel            | 6 Series/C200 Series Chipset Fami... | 18    |            | [B8DC69069D](<Desktop/Dell/OptiPlex/OptiPlex 790/E7BEAAFD5268/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/B8DC69069D>) |
| 8086:4b70 | 8086:7270 | Intel            | Elkhart Lake Management Engine In... | 18    |            | [21D2214DA6](<Desktop/Protectli/VP/VP2420/F9E7BE26C82B/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/21D2214DA6>) |
| 8086:5a9a | 8086:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 18    |            | [E9E179E9AC](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 832 ZMB/574A3DFD4C34/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E9E179E9AC>) |
| 8086:8cba | 1043:8534 | Intel            | 9 Series Chipset Family ME Interf... | 18    |            | [EC33F29DC0](<Desktop/ASUSTek Computer/All/All Series/9506DED5E0BD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/EC33F29DC0>) |
| 8086:8cba | 1458:1c3a | Intel            | 9 Series Chipset Family ME Interf... | 18    |            | [77A58527DA](<Desktop/Gigabyte Technology/H97/H97M-HD3/E5275305C703/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/77A58527DA>) |
| 8086:02e0 | 8086:7270 | Intel            | Comet Lake Management Engine Inte... | 17    |            | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:319a | 1849:319a | Intel            | Celeron/Pentium Silver Processor ... | 17    |            | [C4BF6A3B8C](<Desktop/ASRock/J4005/J4005B-ITX/BFD6E10C2B45/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/C4BF6A3B8C>) |
| 8086:a2ba | 1849:a2ba | Intel            | 200 Series PCH CSME HECI #1          | 17    |            | [0B7DACF902](<Desktop/ASRock/X299/X299E-ITX-ac/78187292FFBE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0B7DACF902>) |
| 8086:1e3a | 8086:1e3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 16    |            | [AE6EA07868](<Desktop/Advantech/UTC-520/UTC-520C/92E6177F9568/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/AE6EA07868>) |
| 8086:8c3a | 17aa:30a3 | Intel            | 8 Series/C220 Series Chipset Fami... | 16    |            | [61C0604160](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AB000KUS/F5B923B560C8/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/61C0604160>) |
| 8086:a360 | 1849:a360 | Intel            | Cannon Lake PCH HECI Controller      | 16    |            | [0E0C795886](<Desktop/ASRock/H310/H310M-ITX-ac/1C596F08C310/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0E0C795886>) |
| 8086:1e3a | 103c:3397 | Intel            | 7 Series/C216 Chipset Family MEI ... | 15    |            | [8B231FD832](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/E655728809C3/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/8B231FD832>) |
| 8086:1e3d | 103c:3397 | Intel            | 7 Series/C210 Series Chipset Fami... | 15    | uart       | [8B231FD832](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/E655728809C3/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/8B231FD832>) |
| 8086:a13a | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 15    |            | [D69ABA5432](<Desktop/Fujitsu/ESPRIMO/ESPRIMO Q956/C9D1C0D177A5/FREEBSD-13.1/13.1-RELEASE/AMD64/D69ABA5432>) |
| 8086:1c3a | 1028:0585 | Intel            | 6 Series/C200 Series Chipset Fami... | 14    |            | [C2FF0BC0B9](<Desktop/Dell/OptiPlex/OptiPlex 3010/5908ED233A1E/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C2FF0BC0B9>) |
| 8086:1e3a | 1028:052c | Intel            | 7 Series/C216 Chipset Family MEI ... | 14    |            | [986F18FA08](<Desktop/Dell/OptiPlex/OptiPlex 9010/1A8752C8E9E4/OPNSENSE-22.1.10/13.0-STABLE/AMD64/986F18FA08>) |
| 8086:43e0 | 1043:8694 | Intel            | Tiger Lake-H Management Engine In... | 14    |            | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:8c3a | 103c:18e7 | Intel            | 8 Series/C220 Series Chipset Fami... | 14    |            | [0B962B9400](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/AC9F58576E1B/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/0B962B9400>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 281   |            | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 133   |            | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 106   |            | [2A6207FB45](<Desktop/ASRock/X300/X300M-STX/6196E1492AD8/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2A6207FB45>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 88    |            | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 80    |            | [FBFF29A62A](<Desktop/ASRock/X470/X470 Gaming K4/FFA88723BDD5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/FBFF29A62A>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 79    |            | [D675A5BAB2](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/D675A5BAB2>) |
| 1022:1486 | 1043:87c0 | AMD              | Starship/Matisse Cryptographic Co... | 42    |            | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 177d:0010 | 177d:0001 | Cavium           | CN15XX/CN16XX [Nitrox PX]            | 28    |            | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 1022:1456 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) Platf... | 27    |            | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 8086:0f18 | 1849:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 19    |            | [5D0F6C2276](<Desktop/ASRock/Q1900/Q1900M/5C14E92D5780/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5D0F6C2276>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 19    |            | [1015EF5E66](<Desktop/Protectli/FW/FW1/9EA6C310067A/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/1015EF5E66>) |
| 1022:15df | 1043:876b | AMD              | Family 17h (Models 10h-1fh) Platf... | 18    |            | [652B3323C6](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-R/60899A106B63/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/652B3323C6>) |
| 1022:1486 | 1043:8808 | AMD              | Starship/Matisse Cryptographic Co... | 16    |            | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 16    |            | [B2540F3BEB](<Desktop/Micro Computer (HK) Tech Limited/MT4/MT4UB1/0EF0D2083CC5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2540F3BEB>) |
| 1022:15df | 1043:8809 | AMD              | Family 17h (Models 10h-1fh) Platf... | 15    |            | [3548F4EFA2](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/75E66F2BE030/FREEBSD-13.2-STABLE/13.2-STABLE/AMD64/3548F4EFA2>) |
| 8086:2298 | 1849:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     |            | [80C809E992](<Desktop/ASRock/N3710-NUC/N3710-NUC IPC/E0800AE12493/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/80C809E992>) |
| 8086:0f18 | 1458:1c3a | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 8     |            | [E2AD4D8035](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/FC5120937F9C/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/E2AD4D8035>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 8     |            | [2690C2A8DF](<Desktop/NU941/1/1.0/5ECD4B5CC634/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/2690C2A8DF>) |
| 1022:15df | 1849:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 7     |            | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 6     |            | [D675A5BAB2](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/D675A5BAB2>) |
| 8086:2298 | 1043:8534 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     |            | [7D6E696FB4](<Desktop/ASUSTek Computer/All/All Series/A477A77FB147/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/7D6E696FB4>) |
| 1022:1486 | 1462:7c02 | AMD              | Starship/Matisse Cryptographic Co... | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 8086:2298 | 1458:1000 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [752F962123](<Desktop/Gigabyte Technology/GB-BACE-3000/GB-BACE-3000-SBE/A8A80797C4EA/OPNSENSE-22.1.5/13.0-STABLE/AMD64/752F962123>) |
| 8086:2298 | 1458:1c3a | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [C84BEDC821](<Desktop/Gigabyte Technology/N3160/N3160ND3V/B01DE72F7AFE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C84BEDC821>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [0ADF0CA671](<Desktop/ZOTAC/Others/Others/6E70FB5A2725/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0ADF0CA671>) |
| 8086:0f18 | 1043:8534 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     |            | [27EA626000](<Desktop/ASUSTek Computer/All/All Series/3184501520E4/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/27EA626000>) |
| 8086:2298 | 1565:3112 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     |            | [4520B5034E](<Desktop/ASRock/E350/E350M1/790F04D92088/FREEBSD-13.1-RC6/13.1-RC6/AMD64/4520B5034E>) |
| 1022:1456 | 1462:7b86 | AMD              | Family 17h (Models 00h-0fh) Platf... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:15df | 1462:7b89 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     |            | [EC37957AED](<Desktop/MSI/MS-7/MS-7B89/27DA135076D6/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/EC37957AED>) |
| 8086:0f18 | 8086:2055 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [DD0D96422F](<Desktop/Intel/DN2820FYK/DN2820FYK H24582-203/B4FE012ED3BF/FREEBSD-13.2-BETA2/13.2-BETA2/AMD64/DD0D96422F>) |
| 8086:2298 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     |            | [4C7F997199](<Desktop/Supermicro/SYS-E200/SYS-E200-9B/583D5ED0D54C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/4C7F997199>) |
| 1022:1456 | 1462:7b89 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     |            | [8B3A234691](<Desktop/MSI/MS-7/MS-7B89/C8A1522450C9/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/8B3A234691>) |
| 1022:1486 | 1043:87cb | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:1486 | 1462:7b86 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 1022:1486 | 1462:7c95 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 1022:1578 | 17aa:364f | AMD              | Carrizo Platform Security Processor  | 2     |            | [C43975A08F](<Desktop/Lenovo/IdeaCentre/IdeaCentre 310S-08ASR 90G90068US/439AD74C89CD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/C43975A08F>) |
| 1022:15df | 103c:87d6 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [FFA88D066B](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-1xxx/96EB6BA29D47/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/FFA88D066B>) |
| 1022:15df | 1043:87e1 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [4C3B92BB42](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/8A74BD626C47/MYBEE-13.1-P3/13.1-RELEASE-P3/AMD64/4C3B92BB42>) |
| 1022:15df | 17aa:32e1 | AMD              | Family 17h (Models 10h-1fh) Platf... | 2     |            | [820B3D1A1B](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s Gen 2 11R8000JUS/C14D7D997EB5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/820B3D1A1B>) |
| 1022:2082 | 1022:2082 | AMD              | Geode LX AES Security Block          | 2     | glxsb      | [A38FF8331A](<Desktop/Others/AMD-GX/AMD-GX3/16AA023F9007/FREEBSD-12.3-STABLE/12.3-STABLE/I386/A38FF8331A>) |
| 8086:0f18 | a0a0:1001 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     |            | [50AC5C0AAF](<Desktop/AOpen/DE/DE3250/F1FEE1273B8A/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/50AC5C0AAF>) |
| 1022:13ec |           | AMD              | Ariel Cryptographic Coprocessor      | 1     |            | [F2A26E2ADC](<Desktop/Others/Others/Others/AE6E4E1C2159/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/F2A26E2ADC>) |
| 1022:1456 | 1462:7a38 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [54E4202BC7](<Desktop/MSI/MS-7/MS-7A38/DB12760FCE4D/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/54E4202BC7>) |
| 1022:1456 | 1462:7a40 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [43388A27A4](<Desktop/MSI/MS-7/MS-7A40/9E0B5CDB5278/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/43388A27A4>) |
| 1022:1456 | 1462:7b90 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [E7BC61FACB](<Desktop/MSI/MS-7/MS-7B90/0D0E7C3B4D7C/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/E7BC61FACB>) |
| 1022:1456 | 1462:7c02 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [A87473149B](<Desktop/MSI/MS-7/MS-7C02/55874FBE1F48/FREEBSD-13.0/13.0-RELEASE/AMD64/A87473149B>) |
| 1022:1486 | 1043:87e2 | AMD              | Starship/Matisse Cryptographic Co... | 1     |            | [94C953E866](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PLUS/11439D70F63B/FREEBSD-12.2/12.2-RELEASE/AMD64/94C953E866>) |
| 1022:1486 | 1043:8815 | AMD              | Starship/Matisse Cryptographic Co... | 1     |            | [95EBD841B2](<Desktop/ASUSTek Computer/Pro/Pro WS WRX80E-SAGE SE WIFI/E11B0B370472/FREEBSD-13.1/13.1-RELEASE/AMD64/95EBD841B2>) |
| 1022:1486 | 1462:7b85 | AMD              | Starship/Matisse Cryptographic Co... | 1     |            | [544B83DA9F](<Desktop/MSI/MS-7/MS-7B85/D34DFF9973E4/OPNSENSE-22.1.6/13.0-STABLE/AMD64/544B83DA9F>) |
| 1022:1486 | 1462:7b89 | AMD              | Starship/Matisse Cryptographic Co... | 1     |            | [6BFF2DB7E3](<Desktop/MSI/MS-7/MS-7B89/528C430BAE24/FREEBSD-12.1/12.1-RELEASE/AMD64/6BFF2DB7E3>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1106:3044 | 1043:81fe | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 13    | fwohci     | [DD9685A909](<Desktop/ASUSTek Computer/P7P55D/P7P55D DELUXE/12FEB991B761/FREEBSD-13.1-P6/13.1-RELEASE-P6/AMD64/DD9685A909>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 11    | fwohci     | [556E872FFE](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/556E872FFE>) |
| 1106:3044 | 1458:1000 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 10    | fwohci     | [70C9122B95](<Desktop/Gigabyte Technology/Z87/Z87X-UD5H/D76966E3C571/OPNSENSE-22.1.10/13.0-STABLE/AMD64/70C9122B95>) |
| 11c1:5811 | 103c:1589 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 10    | fwohci     | [8A927B43CB](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D768D5739884/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/8A927B43CB>) |
| 104c:8024 | 1458:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 8     | fwohci     | [6B63A16799](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/CA4B1CA9726F/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6B63A16799>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 8     | fwohci     | [2A03C05CCE](<Desktop/Equus Computer Systems/Nobilis/Nobilis/67B3FC31A85D/FREEBSD-12.3/12.3-RELEASE/AMD64/2A03C05CCE>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 7     | fwohci     | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 11c1:5811 | 1043:8294 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 7     | fwohci     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 11c1:5811 | 103c:158a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 5     | fwohci     | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 4     | fwohci     | [F65675C771](<Desktop/ASUSTek Computer/P8Z68/P8Z68 DELUXE/63B9369E8108/FREEBSD-13.1/13.1-RELEASE/AMD64/F65675C771>) |
| 11c1:5811 | 1028:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 4     | fwohci     | [5899533EDD](<Desktop/Dell/OptiPlex/OptiPlex 780/1CFDAF3517CA/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5899533EDD>) |
| 104c:8023 | 1043:815b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 3     | fwohci     | [87D7D4435B](<Desktop/ASUSTek Computer/P5/P5B-Deluxe/5AB2F7FF0FA3/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/87D7D4435B>) |
| 1106:3403 | 1849:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 3     |            | [CD85D68DCD](<Desktop/ASRock/X79/X79 Extreme6-GB/34806081C0EC/OPNSENSE-22.1.6/13.0-STABLE/AMD64/CD85D68DCD>) |
| 197b:2380 | 1043:8313 | JMicron Techn... | IEEE 1394 Host Controller            | 3     | fwohci     | [5999E0EBFB](<Desktop/ASUSTek Computer/P5P43TD/P5P43TD PRO/CAA935C7EB09/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5999E0EBFB>) |
| 104c:8024 | 1019:8056 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 2     | fwohci     | [3B8D6CB36E](<Desktop/Acer/Aspire/Aspire T180/7F825E5A8956/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3B8D6CB36E>) |
| 104c:8024 | 1028:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 2     |            | [EDEF5C789D](<Desktop/Dell/Studio/Studio XPS 9100/AEDEA8FF9972/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/EDEF5C789D>) |
| 1106:3044 | 1849:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 2     |            | [19BA4D2EE9](<Desktop/ASRock/Z77/Z77 Extreme6/929553D2B892/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19BA4D2EE9>) |
| 1106:3403 | 1025:0250 | VIA Technologies | VT6315 Series Firewire Controller    | 2     |            | [D316352C20](<Desktop/Acer/Aspire/Aspire X5810/21552B3F601D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D316352C20>) |
| 1106:3403 | 1028:040d | VIA Technologies | VT6315 Series Firewire Controller    | 2     |            | [7F75F30B75](<Desktop/Dell/Studio/Studio XPS 8100/AF73B07C29DA/FREEBSD-12.2/12.2-RELEASE/AMD64/7F75F30B75>) |
| 1106:3403 | 1043:8374 | VIA Technologies | VT6315 Series Firewire Controller    | 2     | fwohci     | [1C30F7523F](<Desktop/ASUSTek Computer/M4A88TD-V/M4A88TD-V EVO-USB3/0638EC1B243E/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/1C30F7523F>) |
| 1106:3403 | 1106:3403 | VIA Technologies | VT6315 Series Firewire Controller    | 2     | fwohci     | [40687B0E17](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X79/23AA4FC47B92/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/40687B0E17>) |
| 11c1:5811 | 103c:1309 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     | fwohci     | [3F170BDEE6](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/645388D505B6/GHOSTBSD-22.04.22/13.0-STABLE/AMD64/3F170BDEE6>) |
| 11c1:5811 | 103c:130a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     |            | [A24F08281D](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/A24F08281D>) |
| 11c1:5811 | 103c:130b | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     |            | [25B7A10166](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/79ADC3087F2D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/25B7A10166>) |
| 11c1:5901 | 1b5b:803b | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 2     |            | [0696D30D3F](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/0696D30D3F>) |
| 1033:00cd | 12ee:8010 | NEC Computers    | uPD72870 [Firewarden] IEEE1394a O... | 1     | fwohci     | [E34B6118A2](<Desktop/Hewlett-Packard/Compaq/Compaq 505B Microtower PC/0EF9A1953E0E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E34B6118A2>) |
| 104c:8020 | 15c5:8010 | Texas Instrum... | TSB12LV26 IEEE-1394 Controller (L... | 1     |            | [7E27B1BC46](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/28DD15B58DF2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/7E27B1BC46>) |
| 104c:8023 | 1028:021d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [E78392BC4C](<Desktop/Dell/Precision/Precision WorkStation T7400/1BAEE5C9C3FB/HELLOSYSTEM-0.5.0/12.2-RELEASE-P4/AMD64/E78392BC4C>) |
| 104c:8023 | 103c:1306 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [655FC531FB](<Desktop/Hewlett-Packard/xw8600/xw8600 Workstation/0566D4E23583/OPNSENSE-22.1.9/13.0-STABLE/AMD64/655FC531FB>) |
| 104c:8023 | 1043:808b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [5B1DC84DA5](<Desktop/ASUSTek Computer/P5/P5GD2-Deluxe/30982A88A2F4/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/5B1DC84DA5>) |
| 104c:8023 | 108e:5354 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [DDAE563E41](<Desktop/Sun Microsystems/Ultra/Ultra 27/33F836C0D1ED/FREENAS-11.3-P11/11.3-RELEASE-P11/AMD64/DDAE563E41>) |
| 104c:8023 | 108e:6676 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [AD993A51ED](<Desktop/ASUSTek Computer/TUF/TUF Gaming X570-PRO/16A2E5FCDB6A/FREEBSD-12.1/12.1-RELEASE/AMD64/AD993A51ED>) |
| 104c:8023 | 15d9:062c | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [EB73C9D13D](<Desktop/Supermicro/X9/X9DAi/558BB9BB7FC9/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/EB73C9D13D>) |
| 104c:8023 | 17aa:101c | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [428F39CBFF](<Desktop/Lenovo/ThinkStation/ThinkStation S10 6483CTO/53B2C53532C0/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/428F39CBFF>) |
| 104c:8023 | 17aa:101d | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [526E5EEA0B](<Desktop/Lenovo/ThinkStation/ThinkStation D10 6493WEU/6A717F675FF7/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/526E5EEA0B>) |
| 104c:8023 | 1849:8023 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [CAF005ED95](<Desktop/ASRock/ConRoeXFire-eSATA/ConRoeXFire-eSATA2/CBD19986C01C/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/CAF005ED95>) |
| 104c:8023 | 8086:5044 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     | fwohci     | [E8F4F644E3](<Desktop/Intel/DG33BU/DG33BU AAD79951-408/9D3335CFA220/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/E8F4F644E3>) |
| 104c:8024 |           | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     |            | [1170B4BFD8](<Desktop/Dell/OptiPlex/OptiPlex 745/0BAF0103F9F5/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/1170B4BFD8>) |
| 104c:8024 | 107b:604e | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     |            | [322450B653](<Desktop/Intel/D945GCF/D945GCF AAD73937-203/02CFC76F026F/FREEBSD-12.1/12.1-RELEASE/AMD64/322450B653>) |
| 104c:8024 | 1b5b:010a | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 1     | fwohci     | [23DF6B2E94](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/2ECB6CBE56F2/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/23DF6B2E94>) |
| 104c:8235 | 104c:2200 | Texas Instrum... | XIO2200A IEEE-1394a-2000 Controll... | 1     |            | [F308AE78EA](<Desktop/Comptronic/pczB/pczB0111/15D6B8B43FFA/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/F308AE78EA>) |
| 104c:823f | 3412:7856 | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 1     |            | [EF29C46355](<Desktop/ASRock/B450M/B450M Pro4/6CB7F35E1FD1/HELLOSYSTEM-0.5.0/12.1-RELEASE/AMD64/EF29C46355>) |
| 106b:0031 | 106b:5811 | Apple            | UniNorth 2 FireWire                  | 1     | fwohci     | [4B7ABCF4FB](<Desktop/Others/Others/Others/6B0A05EBCFE5/FREEBSD-12.1/12.1-RELEASE/POWERPC/4B7ABCF4FB>) |
| 106b:0052 | 106b:5811 | Apple            | Shasta Firewire                      | 1     | fwohci     | [223D74D547](<Desktop/Others/Others/Others/CEAA04E886E8/FREEBSD-12.2/12.2-RELEASE/POWERPC/223D74D547>) |
| 1106:3044 | 02f3:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [A38FF8331A](<Desktop/Others/AMD-GX/AMD-GX3/16AA023F9007/FREEBSD-12.3-STABLE/12.3-STABLE/I386/A38FF8331A>) |
| 1106:3044 | 103c:2a2b | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [C93B86B3BA](<Desktop/Hewlett-Packard/ER904AA-ABA/ER904AA-ABA A1440N/99A7FE8ABBAC/NOMADBSD-1.3.2/12.1-RELEASE-P6/I386/C93B86B3BA>) |
| 1106:3044 | 103c:2a61 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [BEF9700756](<Desktop/ABIT/NF-M2/NF-M2S/7E4365BA84C0/FREEBSD-13.1/13.1-RELEASE/AMD64/BEF9700756>) |
| 1106:3044 | 103c:2a64 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [2A7CB7B214](<Desktop/Hewlett-Packard/Napa/Napa/C99FF842177B/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/2A7CB7B214>) |
| 1106:3044 | 103c:2a92 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [DA467830AF](<Desktop/Hewlett-Packard/HPE-570/HPE-570f/D6775F31A0B7/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/DA467830AF>) |
| 1106:3044 | 10f1:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 1     |            | [BBD42243AE](<Desktop/TYAN Computer/Tiger/Tiger K8W Dual AMD Opteron, S2875/A029250D83FC/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/BBD42243AE>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 173   | vgapci     | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 143   | vgapci     | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:4e61 | 8086:2212 | Intel            | JasperLake [UHD Graphics]            | 127   | vgapci     | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 78    | vgapci     | [D7B171D0BB](<Desktop/Others/Others/Others/E869214B6318/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/D7B171D0BB>) |
| 8086:5916 | 8086:2015 | Intel            | HD Graphics 620                      | 63    | vgapci     | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 60    | vgapci     | [12AC44CBF7](<Desktop/Others/Others/Others/B6CD8CD35969/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/12AC44CBF7>) |
| 8086:0f31 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 52    | vgapci     | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 1002:9831 | 103c:213d | AMD              | Kabini [Radeon HD 8400E]             | 51    | vgapci     | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 8086:0a16 | 8086:0a16 | Intel            | Haswell-ULT Integrated Graphics C... | 44    | vgapci     | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 42    | vgapci     | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:a001 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 38    | agp        | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:1616 | 8086:1616 | Intel            | HD Graphics 5500                     | 37    | vgapci     | [7D6E899ADB](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/03D7E19416AB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7D6E899ADB>) |
| 8086:a002 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 37    | vgapci     | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 36    | nvidia     | [1E97EE1C05](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/98235472B8D9/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/1E97EE1C05>) |
| 8086:0412 | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 35    | vgapci     | [EC33F29DC0](<Desktop/ASUSTek Computer/All/All Series/9506DED5E0BD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/EC33F29DC0>) |
| 8086:5917 | 8086:2015 | Intel            | UHD Graphics 620                     | 34    | vgapci     | [516C778D65](<Desktop/Yanling/YL-KBR6/YL-KBR6L/0108DB586B13/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/516C778D65>) |
| 1002:9833 | 1734:1202 | AMD              | Kabini [Radeon HD 8330E]             | 33    | vgapci     | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:0412 | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 33    | vgapci     | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 1002:9851 | 1734:1202 | AMD              | Mullins [Radeon R4/R5 Graphics]      | 31    | vgapci     | [DFBD35D47F](<Desktop/Fujitsu/FUTRO/FUTRO S920/3A4A89D57DB6/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/DFBD35D47F>) |
| 102b:0532 | 15d9:0624 | Matrox Electr... | MGA G200eW WPCM450                   | 31    | vgapci     | [904FDE472A](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/904FDE472A>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 31    | vgapci     | [409D119307](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/36E7C68AA33D/FREEBSD-12.4/12.4-RELEASE/AMD64/409D119307>) |
| 8086:0412 | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 28    | vgapci     | [31ED952F9C](<Desktop/Dell/OptiPlex/OptiPlex 3020/B41A8964B213/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/31ED952F9C>) |
| 8086:1626 | 8086:1626 | Intel            | HD Graphics 6000                     | 28    | vgapci     | [6BEC4024A8](<Desktop/Intel/QHSW/QHSW02/C9D03D675712/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/6BEC4024A8>) |
| 8086:5916 |           | Intel            | HD Graphics 620                      | 28    | vgapci     | [882F0868FE](<Desktop/Protectli/FW/FW6/484652E02452/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/882F0868FE>) |
| 8086:2e32 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 27    | agp        | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:0412 | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 25    | vgapci     | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:3ea0 | 8086:2212 | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 23    | vgapci     | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:0152 | 1028:0577 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 22    | vgapci     | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:5916 | 8086:2212 | Intel            | HD Graphics 620                      | 22    | vgapci     | [DDF2BCB808](<Desktop/Protectli/FW/FW6/51B65D660F9A/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/DDF2BCB808>) |
| 1002:15d8 | 1002:15d8 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 21    | vgapci     | [02970305DB](<Desktop/Gigabyte Technology/A320/A320M-H/6997E8A1E1D6/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/02970305DB>) |
| 1a03:2000 | 1849:2000 | ASPEED Techno... | ASPEED Graphics Family               | 21    | vgapci     | [5DFCF8051D](<Desktop/ASRock/E3/E3C226D2I/CDCF2A093383/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5DFCF8051D>) |
| 8086:0412 | 1458:d000 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 21    | vgapci     | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 8086:5a85 | 1849:5a85 | Intel            | HD Graphics 500                      | 21    | vgapci     | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 21    | vgapci     | [8537AC75A1](<Desktop/AAEON/UP-APL/UP-APL01/605633FC34DD/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8537AC75A1>) |
| 8086:5a85 | 8086:5a85 | Intel            | HD Graphics 500                      | 21    | vgapci     | [16FA0B0102](<Desktop/NF692/1/1.0/9852CE16A74F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16FA0B0102>) |
| 8086:4555 | 8086:7270 | Intel            | Elkhart Lake [UHD Graphics Gen11 ... | 18    | vgapci     | [21D2214DA6](<Desktop/Protectli/VP/VP2420/F9E7BE26C82B/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/21D2214DA6>) |
| 8086:4e71 | 8086:2212 | Intel            | JasperLake [UHD Graphics]            | 18    | vgapci     | [E09800B936](<Desktop/maiyunda/www.maiyunda.com/www.maiyunda.com/5F223CD2630E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E09800B936>) |
| 8086:0f31 | 1849:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 17    | vgapci     | [42A53E5201](<Desktop/ASRock/Q2900/Q2900M/76BCB5ECE4E0/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/42A53E5201>) |
| 1002:15dd | 1002:15dd | AMD              | Raven Ridge [Radeon Vega Series /... | 16    | vgapci     | [593F6FF02D](<Desktop/MSI/MS-7/MS-7C51/435F418C7DE2/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/593F6FF02D>) |
| 8086:5917 | 8086:2212 | Intel            | UHD Graphics 620                     | 16    | vgapci     | [606F595213](<Desktop/Protectli/FW/FW6/99AFD594764D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/606F595213>) |
| 1002:9616 | 1043:8388 | AMD              | RS780L [Radeon 3000]                 | 15    | vgapci     | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |
| 8086:0102 | 1028:04ad | Intel            | 2nd Generation Core Processor Fam... | 15    | vgapci     | [B8DC69069D](<Desktop/Dell/OptiPlex/OptiPlex 790/E7BEAAFD5268/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/B8DC69069D>) |
| 8086:0152 | 1458:d000 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 15    | vgapci     | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 1002:1638 | 1002:1636 | AMD              | Cezanne [Radeon Vega Series / Rad... | 14    | vgapci     | [2A6207FB45](<Desktop/ASRock/X300/X300M-STX/6196E1492AD8/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2A6207FB45>) |
| 8086:1912 | 1043:8694 | Intel            | HD Graphics 530                      | 14    | vgapci     | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 8086:1916 | 8086:2015 | Intel            | Skylake GT2 [HD Graphics 520]        | 14    | vgapci     | [D3750005C2](<Desktop/Others/Others/Others/C14747EBBA5F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/D3750005C2>) |
| 8086:5906 | 8086:2015 | Intel            | HD Graphics 610                      | 14    | vgapci     | [47E6A4FA8B](<Desktop/Others/Others/Others/FB66AAFE303C/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/47E6A4FA8B>) |
| 8086:9b41 | 8086:2212 | Intel            | CometLake-U GT2 [UHD Graphics]       | 14    | vgapci     | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 1002:1638 | 1043:8809 | AMD              | Cezanne [Radeon Vega Series / Rad... | 13    | vgapci     | [3548F4EFA2](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/75E66F2BE030/FREEBSD-13.2-STABLE/13.2-STABLE/AMD64/3548F4EFA2>) |
| 8086:0162 | 1043:84ca | Intel            | IvyBridge GT2 [HD Graphics 4000]     | 13    | vgapci     | [88929A3594](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH Z77/46CCAEB3C831/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/88929A3594>) |

### Infiniband (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 15b3:6274 | 15b3:6274 | Mellanox Tech... | MT25204 [InfiniHost III Lx HCA]      | 1     |            | [DF55C76E1E](<Desktop/Intel/S3000PT/S3000PT D60097-206/DD8508FCC40C/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/DF55C76E1E>) |

### Input (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 7     | emujoy     | [2A03C05CCE](<Desktop/Equus Computer Systems/Nobilis/Nobilis/67B3FC31A85D/FREEBSD-12.3/12.3-RELEASE/AMD64/2A03C05CCE>) |
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 3     |            | [2620FD3511](<Desktop/ASUSTek Computer/P8/P8B75-M/D6575EA2BF9C/FREEBSD-13.1/13.1-RELEASE/AMD64/2620FD3511>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 239   |            | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM Controller   | 147   |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 90    |            | [53FA01007B](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/53FA01007B>) |
| 8086:a121 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    |            | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 36    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:a36f | 1043:8694 | Intel            | Cannon Lake PCH Shared SRAM          | 26    |            | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 25    |            | [FD39A615DE](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-K R2.0/7D5721B3D945/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD39A615DE>) |
| 8086:19de | 8086:7270 | Intel            | Atom Processor C3000 Series Power... | 24    |            | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 22    |            | [85628154A2](<Desktop/Gigabyte Technology/H510M/H510M S2H V2/D6902D5FE2E5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/85628154A2>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 21    |            | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:a2a1 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family Po... | 21    |            | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 8086:a121 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 20    |            | [FB5A559634](<Desktop/Gigabyte Technology/B150/B150-HD3P/7B89078673EA/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/FB5A559634>) |
| 8086:4b7f | 8086:7270 | Intel            | Elkhart Lake PMC SRAM                | 18    |            | [21D2214DA6](<Desktop/Protectli/VP/VP2420/F9E7BE26C82B/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/21D2214DA6>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 17    |            | [DF7F4524D7](<Desktop/Others/SKYBAY/SKYBAY/A6E8FBDE5F97/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DF7F4524D7>) |
| 8086:a2a1 | 1849:a2a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 17    |            | [0B7DACF902](<Desktop/ASRock/X299/X299E-ITX-ac/78187292FFBE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0B7DACF902>) |
| 8086:a36f | 1849:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 16    |            | [0E0C795886](<Desktop/ASRock/H310/H310M-ITX-ac/1C596F08C310/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0E0C795886>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 15    |            | [6F8AD1A8B9](<Desktop/Gigabyte Technology/Z490/Z490 VISION G/61A52C9709E8/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6F8AD1A8B9>) |
| 8086:a121 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 15    |            | [D69ABA5432](<Desktop/Fujitsu/ESPRIMO/ESPRIMO Q956/C9D1C0D177A5/FREEBSD-13.1/13.1-RELEASE/AMD64/D69ABA5432>) |
| 8086:43ef | 1043:8694 | Intel            | Tiger Lake-H Shared SRAM             | 14    |            | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 14    |            | [B08FD92E36](<Desktop/MSI/MS-7/MS-7D46/C894FC6BA535/MYBEE-13.2-RC2/13.2-RC2/AMD64/B08FD92E36>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 14    |            | [F58E088DF2](<Desktop/Others/Others/Others/E49A78BE4C54/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F58E088DF2>) |
| 8086:a0ef | 8086:7270 | Intel            | Tiger Lake-LP Shared SRAM            | 12    |            | [5082B8203B](<Desktop/Others/Others/Others/AB924515ADF1/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/5082B8203B>) |
| 8086:a121 | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [226F25A086](<Desktop/Dell/OptiPlex/OptiPlex 7040/DD40E35F79F7/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/226F25A086>) |
| 8086:a121 | 1028:06bb | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [C51A264E20](<Desktop/Dell/OptiPlex/OptiPlex 3040/3E96FED82A87/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C51A264E20>) |
| 8086:a121 | 1849:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [7CC4B63834](<Desktop/ASRock/H110/H110 Pro BTC+/CB21DA586B1D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CC4B63834>) |
| 8086:a1a1 | 15d9:0986 | Intel            | C620 Series Chipset Family Power ... | 12    |            | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 11    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:a121 | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 11    |            | [7A7DD659C8](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/AAEB268489C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7A7DD659C8>) |
| 8086:a2a1 | 1028:07a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 11    |            | [22A1B812F8](<Desktop/Dell/OptiPlex/OptiPlex 7050/CB83CBBB388D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/22A1B812F8>) |
| 8086:a121 | 1028:06ba | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [82F4B97203](<Desktop/Dell/OptiPlex/OptiPlex 5040/641267472D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/82F4B97203>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [78975E45B7](<Desktop/Thomas-Krenn.AG/P10S-M/P10S-M Series/A864089E016F/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/78975E45B7>) |
| 8086:a3a1 | 1043:8694 | Intel            | Cannon Lake PCH Power Management ... | 9     |            | [A3F77B82CC](<Desktop/ASUSTek Computer/PRO/PRO B460M-C/9D195AD59D5D/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/A3F77B82CC>) |
| 10de:03e2 | 1849:03e2 | Nvidia           | MCP61 Host Bridge                    | 8     |            | [04F43C3D70](<Desktop/ASRock/N68-S/N68-S UCC/59DCE7CA2B79/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/04F43C3D70>) |
| 10de:03f5 | 1849:03eb | Nvidia           | MCP61 Memory Controller              | 8     |            | [04F43C3D70](<Desktop/ASRock/N68-S/N68-S UCC/59DCE7CA2B79/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/04F43C3D70>) |
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 8     |            | [9CD1C1FC21](<Desktop/Supermicro/SYS-E200/SYS-E200-9A/41FCF82CB6BD/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/9CD1C1FC21>) |
| 8086:a121 | 103c:8169 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [E80C8A40A5](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/EF032CAD06FB/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/E80C8A40A5>) |
| 8086:a2a1 | 103c:8299 | Intel            | 200 Series/Z370 Chipset Family Po... | 8     |            | [61B1C41F22](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/AABFEF40A2A3/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/61B1C41F22>) |
| 8086:7aa7 | 1043:8694 | Intel            | Alder Lake-S PCH Shared SRAM         | 7     |            | [C3281EB186](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/967511C3CD54/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/C3281EB186>) |
| 8086:a121 | 1028:07c5 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [50FBB0435C](<Desktop/Dell/PowerEdge/PowerEdge T30/8C16168DE41F/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/50FBB0435C>) |
| 8086:a2a1 | 1028:07a2 | Intel            | 200 Series/Z370 Chipset Family Po... | 7     |            | [95A8784D4A](<Desktop/Dell/OptiPlex/OptiPlex 5050/F67D392AB919/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/95A8784D4A>) |
| 8086:a2a1 | 1028:07a3 | Intel            | 200 Series/Z370 Chipset Family Po... | 7     |            | [1C4EDF62E6](<Desktop/Dell/OptiPlex/OptiPlex 3050/64C57B471C1A/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/1C4EDF62E6>) |
| 8086:a121 | 103c:8055 | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [FAADCD3E41](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 DM 35W/700E5ED9C506/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FAADCD3E41>) |
| 8086:a121 | 103c:805d | Intel            | 100 Series/C230 Series Chipset Fa... | 6     |            | [4912CA5CD6](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 SFF/AA674AC623BE/PFSENSE-2.6.0/12.3-STABLE/AMD64/4912CA5CD6>) |
| 8086:a2a1 | 1043:872f | Intel            | 200 Series/Z370 Chipset Family Po... | 6     |            | [6F4B514959](<Desktop/ASUSTek Computer/STRIX/STRIX Z270F GAMING/9FCEC82B3F4D/FREEBSD-13.1/13.1-RELEASE/AMD64/6F4B514959>) |
| 8086:a3a1 | 1849:a3a1 | Intel            | Cannon Lake PCH Power Management ... | 6     |            | [C1A691F99C](<Desktop/ASRock/B460/B460M-ITX-ac/0A0BCA0A718C/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/C1A691F99C>) |
| 8086:06ef | 1849:06ef | Intel            | Comet Lake PCH Shared SRAM           | 5     |            | [98096ADFAA](<Desktop/ASRock/H470/H470M-STX/9AABBF15235B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/98096ADFAA>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 5     |            | [E27931F082](<Desktop/BESSTAR Tech/TH/TH50/1DD7349765D5/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/E27931F082>) |
| 8086:a121 | 103c:802e | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [914384FCA0](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/C940FCA75474/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/914384FCA0>) |
| 8086:a121 | 17aa:30d9 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     |            | [C3864D9D51](<Desktop/Lenovo/10GSS1/10GSS1X/E3D644BC61B5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C3864D9D51>) |
| 8086:a2a1 | 103c:82a2 | Intel            | 200 Series/Z370 Chipset Family Po... | 5     |            | [4E5C9DE512](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G4 SFF/3E588DE12A62/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4E5C9DE512>) |

### Modem (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1057:3052 | 1057:3020 | Motorola         | SM56 Data Fax Modem                  | 1     |            | [96A8673B26](<Desktop/Hewlett-Packard/Compaq/Compaq 500B Microtower/7E9B580A3747/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/96A8673B26>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 20    |            | [E376971BD6](<Desktop/ChangWang/CW56/CW56-58/7AC0129D343D/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E376971BD6>) |
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 14    |            | [B686FDF1C1](<Desktop/Protectli/FW/FW6/AA9E145E9412/OPNSENSE-22.7/13.1-RELEASE/AMD64/B686FDF1C1>) |
| 1022:15e2 | 1849:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 7     |            | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:15e2 | 17aa:32e1 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [820B3D1A1B](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s Gen 2 11R8000JUS/C14D7D997EB5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/820B3D1A1B>) |
| 1022:15e2 | 103c:8433 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [5A242D9C9E](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0CFBD160A1EE/FREEBSD-12.2/12.2-RELEASE/AMD64/5A242D9C9E>) |
| 1022:15e2 | 1458:1000 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [817CB3E603](<Desktop/Gigabyte Technology/BSRE/BSRE-1605/493093EBE60A/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/817CB3E603>) |
| 1022:15e2 | 17aa:318e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [115F2C7B35](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75t Gen 2 11KECTO1WW/85187679911A/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/115F2C7B35>) |
| 1022:15e2 | 17aa:3708 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [E68D7A5DFF](<Desktop/Lenovo/IdeaCentre/IdeaCentre 3 07ADA05 90MV007UGE/ECBF6B871AD1/OPNSENSE-22.1.9/13.0-STABLE/AMD64/E68D7A5DFF>) |
| 1022:15e2 | 17aa:3728 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [7BA1CCC40D](<Desktop/Lenovo/IdeaCentre/IdeaCentre 5 14ARE05 90Q30008US/2ECD21E7A105/FREEBSD-12.2-P8/12.2-RELEASE-P8/AMD64/7BA1CCC40D>) |
| 1131:7130 |           | Philips Semic... | SAA7130 Video Broadcast Decoder      | 1     |            | [C6DA80D54B](<Desktop/Gigabyte Technology/H61/H61M-D2P-B3/BC7CD91E287F/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C6DA80D54B>) |
| 1131:7130 | 5168:0138 | Philips Semic... | SAA7130 Video Broadcast Decoder      | 1     |            | [CAF005ED95](<Desktop/ASRock/ConRoeXFire-eSATA/ConRoeXFire-eSATA2/CBD19986C01C/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/CAF005ED95>) |
| 1131:7133 | 1043:4876 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 1     |            | [F521976730](<Desktop/ASUSTek Computer/M3A78/M3A78 PRO/F18AAB4E7AFE/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/F521976730>) |
| 1131:7133 | 16be:0010 | Philips Semic... | SAA7131/SAA7133/SAA7135 Video Bro... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 1131:7146 | 13c2:101a | Philips Semic... | SAA7146                              | 1     |            | [8CF113AC55](<Desktop/ASUSTek Computer/V-P7/V-P7H55E/0AE0678A444E/NOMADBSD-5806F915/13.0-RELEASE/AMD64/8CF113AC55>) |
| 1131:7160 | 1043:48b5 | Philips Semic... | SAA7160                              | 1     |            | [5FE1A9E521](<Desktop/ASUSTek Computer/P7H55-M/P7H55-M LX/B84E7E871D43/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/5FE1A9E521>) |
| 1131:7160 | 1461:2655 | Philips Semic... | SAA7160                              | 1     |            | [13371B2AB8](<Desktop/Gigabyte Technology/Z370/Z370 AORUS ULTRAGAMING WIFI-OP/7CB030D59E17/NOMADBSD-5806F915/13.0-RELEASE/AMD64/13371B2AB8>) |
| 1131:7231 | 1461:180f | Philips Semic... | SAA7231                              | 1     |            | [1D2E9E175C](<Desktop/Gateway/DX/DX4840/E79C6FD7005F/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/1D2E9E175C>) |
| 11bd:bede | 11bd:0023 | Pinnacle Systems | AV/DV Studio Capture Card            | 1     |            | [CF1C018EDE](<Desktop/ASRock/A770/A770DE+/772FD18ED013/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CF1C018EDE>) |
| 14f1:8802 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 14f1:8804 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 14f1:8811 | 0070:3401 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [1BC05B5951](<Desktop/Dell/Precision/Precision WorkStation T3400/ADEEA3484D9F/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1BC05B5951>) |
| 14f1:8811 | 0070:6906 | Conexant Systems | CX23880/1/2/3 PCI Video and Audio... | 1     |            | [F2367A4249](<Desktop/Intel/DH67CL/DH67CL AAG10212-206/0F5A1250DD36/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/F2367A4249>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [380B54B271](<Desktop/AMI/PA_1900/PA_1900SL/619CDF31C1E6/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/380B54B271>) |
| 8086:0f38 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [0C6C98CBD3](<Desktop/Silicom/Minnowboard/Minnowboard Turbot D0-D1 PLATFORM/0EBCE3D07DDB/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/0C6C98CBD3>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [688C95BDA6](<Desktop/Radxa/ROCK/ROCK Pi X/A5A9E33E38CF/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/688C95BDA6>) |
| 8086:5a88 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B9F23EE753](<Desktop/AZW/BT3/BT3 X/F6FE61B4FFA6/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/B9F23EE753>) |
| 8086:9a19 | 8086:7270 | Intel            | Core i9/i7/i5/Xeon Imaging Signal... | 1     |            | [FDFFBDB940](<Desktop/Others/Others/Others/0D6620BFC4C8/PFSENSE-12.3-STABLE/12.3-STABLE/AMD64/FDFFBDB940>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:15f3 |           | Intel            | Ethernet Controller I225-V           | 197   | igc        | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 156   | em         | [12AC44CBF7](<Desktop/Others/Others/Others/B6CD8CD35969/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/12AC44CBF7>) |
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 91    | igb        | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:125c |           | Intel            | Ethernet Controller I226-V           | 88    | igc        | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 10ec:8168 | 1734:11ff | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 79    | re         | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 71    | re         | [2E40DF5A32](<Desktop/WYSE/Z/Z CLASS/76E6DE34A38F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E40DF5A32>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 68    | re         | [34CF4827D7](<Desktop/Hardkernel/ODROID-H/ODROID-H3/174DBB630022/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/34CF4827D7>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 64    | re         | [BD041B2E20](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G1 SFF/8E20AC0EE415/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/BD041B2E20>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 59    | igb        | [FBFF29A62A](<Desktop/ASRock/X470/X470 Gaming K4/FFA88723BDD5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/FBFF29A62A>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 57    | igb        | [DCF3F03DDC](<Desktop/Fujitsu/FUTRO/FUTRO S930/6C3424C08936/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/DCF3F03DDC>) |
| 8086:10bc | 103c:704b | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 50    | em         | [2E40DF5A32](<Desktop/WYSE/Z/Z CLASS/76E6DE34A38F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E40DF5A32>) |
| 8086:1521 | 8086:5001 | Intel            | I350 Gigabit Network Connection      | 49    | igb        | [2D9FF025FF](<Desktop/ASRock/B450M/B450M Pro4/8123071B0896/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/2D9FF025FF>) |
| 8086:150e | 103c:1780 | Intel            | 82580 Gigabit Network Connection     | 48    | igb        | [A8B5C70376](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/CFD7F415A438/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/A8B5C70376>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 46    | em         | [986F18FA08](<Desktop/Dell/OptiPlex/OptiPlex 9010/1A8752C8E9E4/OPNSENSE-22.1.10/13.0-STABLE/AMD64/986F18FA08>) |
| 8086:105e | 8086:125e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 40    | em         | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 38    | igb        | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 10ec:8168 | 1028:0612 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 37    | re         | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:10e8 | 8086:a02c | Intel            | 82576 Gigabit Network Connection     | 37    | igb        | [1F347F15E2](<Desktop/ASUSTek Computer/H110I-PLUS/H110I-PLUS D3/584D4BE57ECB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/1F347F15E2>) |
| 8086:10c9 | 8086:a02f | Intel            | 82576 Gigabit Network Connection     | 31    | igb        | [27E756F63D](<Desktop/Fujitsu/FUTRO/FUTRO S920/6E2617BD266B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/27E756F63D>) |
| 8086:1521 |           | Intel            | I350 Gigabit Network Connection      | 31    | igb        | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:15b8 | 1043:8672 | Intel            | Ethernet Connection (2) I219-V       | 29    | em         | [6F4B514959](<Desktop/ASUSTek Computer/STRIX/STRIX Z270F GAMING/9FCEC82B3F4D/FREEBSD-13.1/13.1-RELEASE/AMD64/6F4B514959>) |
| 8086:10bc | 8086:11bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 27    | em         | [84AD5CFA43](<Desktop/Dell/OptiPlex/OptiPlex 7010/60064609B838/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/84AD5CFA43>) |
| 10ec:8169 | 10ec:8169 | Realtek Semic... | RTL8169 PCI Gigabit Ethernet Cont... | 26    | re         | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:1502 | 15d9:1502 | Intel            | 82579LM Gigabit Network Connectio... | 26    | em         | [96ACEB6D32](<Desktop/Supermicro/X9/X9SCL-X9SCM/1D10666FC295/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/96ACEB6D32>) |
| 8086:153a | 103c:1998 | Intel            | Ethernet Connection I217-LM          | 26    | em         | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:15f3 | 1043:87d2 | Intel            | Ethernet Controller I225-V           | 22    | igc        | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 8086:15e4 |           | Intel            | Ethernet Connection X553 1GbE        | 21    | ix         | [86C132C242](<Desktop/Others/Others/Others/23C67704FCED/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/86C132C242>) |
| 8086:10bc | 8086:10bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 20    | em         | [3D912F92AA](<Desktop/Fujitsu/FUTRO/FUTRO S920/A1AC5CC7301E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3D912F92AA>) |
| 8086:15a1 | 1043:85c4 | Intel            | Ethernet Connection (2) I218-V       | 20    | em         | [EC33F29DC0](<Desktop/ASUSTek Computer/All/All Series/9506DED5E0BD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/EC33F29DC0>) |
| 8086:15b8 | 1849:15b8 | Intel            | Ethernet Connection (2) I219-V       | 20    | em         | [0B7DACF902](<Desktop/ASRock/X299/X299E-ITX-ac/78187292FFBE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0B7DACF902>) |
| 14e4:165b | 103c:705d | Broadcom         | NetXtreme BCM5723 Gigabit Etherne... | 19    | bge        | [50C8CB79F7](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.4/12.4-RELEASE/AMD64/50C8CB79F7>) |
| 8086:10d6 | 8086:145a | Intel            | 82575GB Gigabit Network Connection   | 19    | igb        | [F3C3E6ECB5](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10A8S16X0J/968E3838A942/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F3C3E6ECB5>) |
| 8086:15e5 |           | Intel            | Ethernet Connection X553 1GbE        | 19    | ix         | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:10c9 | 1dcf:0319 | Intel            | 82576 Gigabit Network Connection     | 18    | igb        | [25528A00F3](<Desktop/Lenovo/ThinkCentre/ThinkCentre M91p 7033A2G/E4BF25D116F4/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/25528A00F3>) |
| 10ec:8168 | 1043:83a3 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | re         | [29AD0E1044](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/4235E38A16E7/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/29AD0E1044>) |
| 10ec:8168 | 1565:2312 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | re         | [0A39FFA716](<Desktop/Biostar/TB250/TB250-BTC+/A8163A94649F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0A39FFA716>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 17    | ix         | [D1E71EFFC5](<Desktop/Dell/OptiPlex/OptiPlex 7060/08DB7CD25B19/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/D1E71EFFC5>) |
| 8086:1516 | 8086:12b2 | Intel            | 82580 Gigabit Network Connection     | 17    | igb        | [904FDE472A](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/904FDE472A>) |
| 8086:153a | 103c:18e7 | Intel            | Ethernet Connection I217-LM          | 17    | em         | [0B962B9400](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/AC9F58576E1B/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/0B962B9400>) |
| 8086:153b | 1458:e000 | Intel            | Ethernet Connection I217-V           | 17    | em         | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 8086:27dc | 8086:27dc | Intel            | NM10/ICH7 Family LAN Controller      | 17    | fxp        | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:10a7 |           | Intel            | 82575EB Gigabit Network Connection   | 16    | igb        | [6819027308](<Desktop/Dell/Inspiron/Inspiron 3268/5A953B1C086E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/6819027308>) |
| 8086:1502 | 103c:3397 | Intel            | 82579LM Gigabit Network Connectio... | 16    | em         | [8B231FD832](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/E655728809C3/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/8B231FD832>) |
| 8086:1528 | 8086:0001 | Intel            | Ethernet Controller 10-Gigabit X5... | 16    | ix         | [FA12EA67EB](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/837435F7D2A1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/FA12EA67EB>) |
| 8086:153a | 17aa:30a3 | Intel            | Ethernet Connection I217-LM          | 16    | em         | [61C0604160](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AB000KUS/F5B923B560C8/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/61C0604160>) |
| 8086:1572 |           | Intel            | Ethernet Controller X710 for 10Gb... | 16    | ixl        | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 10ec:8125 | 1043:87d7 | Realtek Semic... | RTL8125 2.5GbE Controller            | 15    | re         | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1186:4300 | 1186:4300 | D-Link System    | DGE-528T Gigabit Ethernet Adapter    | 15    | re         | [05CF3DAF4E](<Desktop/Dell/Precision/Precision WorkStation T3500/71ACCE4AED93/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/05CF3DAF4E>) |
| 8086:1503 | 1043:849c | Intel            | 82579V Gigabit Network Connection    | 15    | em         | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:107d | 8086:1082 | Intel            | 82572EI Gigabit Ethernet Controll... | 14    | em         | [6A91635684](<Desktop/exone/X7/X7SPA-HF/881B5CC94BD2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6A91635684>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 91    | iwlwifi    | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 44    | iwm        | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 168c:002a | 168c:3099 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 25    | ath        | [0D1561FEA9](<Desktop/PC Engines/apu/apu4/7545D6E348E1/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0D1561FEA9>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 22    | iwm        | [3F78B1A6C7](<Desktop/Fujitsu/FUTRO/FUTRO S940/BB89053F9D4A/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3F78B1A6C7>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 21    | iwlwifi    | [F07E092146](<Desktop/Techvision/TVI7309/TVI7309X/432837343A25/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F07E092146>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 18    | iwm        | [B2540F3BEB](<Desktop/Micro Computer (HK) Tech Limited/MT4/MT4UB1/0EF0D2083CC5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2540F3BEB>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 18    | iwm        | [C22EE2E279](<Desktop/AZW/GK/GK55/8FD2B3239B52/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C22EE2E279>) |
| 8086:31dc | 8086:0034 | Intel            | Gemini Lake PCH CNVi WiFi            | 18    | iwm        | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 168c:003c |           | Qualcomm Atheros | QCA986x/988x 802.11ac Wireless Ne... | 16    |            | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 15    | ath        | [227C78F3C1](<Desktop/MSI/MS/MS-7788/BD1A816BB8CA/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/227C78F3C1>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 15    | iwm        | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 14    |            | [5AB1DADBAB](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F54ADC493621/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5AB1DADBAB>) |
| 8086:088e | 8086:4060 | Intel            | Centrino Advanced-N 6235             | 14    | iwn        | [D7B171D0BB](<Desktop/Others/Others/Others/E869214B6318/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/D7B171D0BB>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 12    | iwm        | [0ADF0CA671](<Desktop/ZOTAC/Others/Others/6E70FB5A2725/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0ADF0CA671>) |
| 14e4:4359 | 14e4:05e2 | Broadcom         | BCM43228 802.11a/b/g/n               | 11    |            | [659939CC8B](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/5AE79326B5C6/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/659939CC8B>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 11    | ath        | [B080710198](<Desktop/PC Engines/APU/APU3/BA51930F350D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B080710198>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 11    | iwm        | [33C1878560](<Desktop/Brian Kabela/Game/Game Station 1/A3F0D23DEDB7/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/33C1878560>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 10    | iwm        | [2E3026E0FD](<Desktop/Gigabyte Technology/Z390/Z390 I AORUS PRO WIFI/CB785A37BC49/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E3026E0FD>) |
| 14c3:0608 | 14c3:0608 | MediaTek         | MT7921K (RZ608) Wi-Fi 6E 80MHz       | 9     |            | [E27931F082](<Desktop/BESSTAR Tech/TH/TH50/1DD7349765D5/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/E27931F082>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 9     | iwm        | [0B7DACF902](<Desktop/ASRock/X299/X299E-ITX-ac/78187292FFBE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0B7DACF902>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 8     | ath        | [F27FF1A7C3](<Desktop/Intel/D2500CC/D2500CC AAG81477-401/EE968EA9F06D/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/F27FF1A7C3>) |
| 10ec:c821 | 1a3b:3043 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 7     |            | [0F1E027B35](<Desktop/Shuttle/DS10/DS10U/EB8F6226ED0B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/0F1E027B35>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 7     | iwm        | [A52D7DDA08](<Desktop/Protectli/FW/FW6/6CB55FAF44C3/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A52D7DDA08>) |
| 10ec:8179 | 10ec:8197 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 6     | rtwn       | [BD041B2E20](<Desktop/Hewlett-Packard/ProDesk/ProDesk 400 G1 SFF/8E20AC0EE415/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/BD041B2E20>) |
| 14e4:4353 | 14e4:04d8 | Broadcom         | BCM43224 802.11a/b/g/n               | 6     | bwn_pci    | [79504FCF66](<Desktop/AMI/PB_1900/PB_1900A/92B93DFA0309/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/79504FCF66>) |
| 168c:002a | 103c:3041 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 6     | ath        | [5B73E61A78](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/929707184B01/PFSENSE-2.6.0/12.3-STABLE/AMD64/5B73E61A78>) |
| 168c:002d | 168c:0300 | Qualcomm Atheros | AR9227 Wireless Network Adapter      | 6     | ath        | [BBE7B327FD](<Desktop/MSI/MS/MS-7918/84CABFE0CD6A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BBE7B327FD>) |
| 168c:0030 | 168c:3116 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 6     | ath        | [1E3EBDE983](<Desktop/Others/Others/Others/C88327626057/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/1E3EBDE983>) |
| 168c:0032 | 168c:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 6     | ath        | [CA70BCEB83](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-E/964B28FB1DE0/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CA70BCEB83>) |
| 8086:0887 | 8086:4062 | Intel            | Centrino Wireless-N 2230             | 6     | iwn        | [D8C78B92A7](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4DBEA0F75A7B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D8C78B92A7>) |
| 8086:2723 | 1a56:1654 | Intel            | Wi-Fi 6 AX200                        | 6     | iwlwifi    | [8EB068A097](<Desktop/ASRock/X570/X570 Taichi/627244F84DF9/FREEBSD-13.1/13.1-RELEASE/AMD64/8EB068A097>) |
| 10ec:8821 | 1a3b:216a | Realtek Semic... | RTL8821AE 802.11ac PCIe Wireless ... | 5     |            | [B1C784D41A](<Desktop/Thomas-Krenn.AG/LES/LES network/56DBE8BE7C78/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/B1C784D41A>) |
| 10ec:b723 | 1a3b:2159 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 5     |            | [E558435C70](<Desktop/OEM/NU93/NU93 Series/6E692C4E5275/OPNSENSE-22.1.5/13.0-STABLE/AMD64/E558435C70>) |
| 10ec:b822 | 1043:8746 | Realtek Semic... | RTL8822BE 802.11a/b/g/n/ac WiFi a... | 5     |            | [936AFA4DE3](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z370-E GAMING/DABD658BAA97/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/936AFA4DE3>) |
| 10ec:c822 | 103c:85f7 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 5     |            | [9D98B3BAA4](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-1xxx/316ACA3FC06A/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/9D98B3BAA4>) |
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 5     | bwn_pci    | [556E872FFE](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/556E872FFE>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 5     | ath        | [A629BF3445](<Desktop/Dell/Inspiron/Inspiron 3470/F855695C070F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A629BF3445>) |
| 1814:539b | 103c:18ed | Ralink           | RT5390R 802.11bgn PCIe Wireless N... | 5     | ral        | [9FF97B3D86](<Desktop/Hewlett-Packard/p6/p6-2330/4194D8B9EFDB/OPNSENSE-22.1.6/13.0-STABLE/AMD64/9FF97B3D86>) |
| 8086:0082 | 8086:1301 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 5     | iwn        | [7488AFC0A7](<Desktop/Others/Others/Others/8FCB69CC5037/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7488AFC0A7>) |
| 8086:0895 | 8086:0222 | Intel            | Centrino Wireless-N 105              | 5     | iwn        | [61C0604160](<Desktop/Lenovo/ThinkCentre/ThinkCentre M93p 10AB000KUS/F5B923B560C8/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/61C0604160>) |
| 8086:24f3 | 8086:0010 | Intel            | Wireless 8260                        | 5     | iwm        | [43D56964B9](<Desktop/MSI/MS/MS-7923/2447DC6632F6/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/43D56964B9>) |
| 10ec:8179 | 1a3b:219a | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 4     | rtwn       | [4598A5F9D1](<Desktop/Shuttle/DS77/DS77U/C35E4E98851B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4598A5F9D1>) |
| 10ec:818b | 10ec:8196 | Realtek Semic... | RTL8192EE PCIe Wireless Network A... | 4     |            | [B9D64A7496](<Desktop/ASRock/Z390/Z390 Pro4/9E602FC15610/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/B9D64A7496>) |
| 10ec:8812 | 10ec:8203 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 4     |            | [EACE523F17](<Desktop/ASRock/G41/G41M-GS3/A906B312696E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/EACE523F17>) |
| 10ec:8821 | 1a3b:2161 | Realtek Semic... | RTL8821AE 802.11ac PCIe Wireless ... | 4     |            | [5D287163C9](<Desktop/Gigabyte Technology/GB-BXi7/GB-BXi7-5775R/BF425CFC0EFE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5D287163C9>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 4     |            | [1587EA95DA](<Desktop/Intel/Jasper/Jasper Lake Client Platform/059B9BBEDEFA/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/1587EA95DA>) |
| 14e4:43a0 | 1043:8659 | Broadcom         | BCM4360 802.11ac Wireless Network... | 4     |            | [ABE21B9C9E](<Desktop/ASUSTek Computer/All/All Series/E6AD36953D33/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/ABE21B9C9E>) |
| 14e4:43a0 | 106b:0111 | Broadcom         | BCM4360 802.11ac Wireless Network... | 4     |            | [8DE53AC515](<Desktop/Gigabyte Technology/H410M/H410M S2 V2/D8FA2A70CF0A/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/8DE53AC515>) |
| 168c:0030 | 10cf:16a8 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 4     | ath        | [8D9829BABC](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/4558F6AA9DFB/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/8D9829BABC>) |
| 168c:0032 | 103c:1838 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 4     | ath        | [2D9FF025FF](<Desktop/ASRock/B450M/B450M Pro4/8123071B0896/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/2D9FF025FF>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 661   | igb        | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 321   | re         | [58090B9DBF](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/8550845C82E4/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/58090B9DBF>) |
| 8086:157b |           | Intel            | I210 Gigabit Network Connection      | 260   | igb        | [BD7676AFFA](<Desktop/PC Engines/APU/APU2/1A431BAA436D/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/BD7676AFFA>) |
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 222   | re         | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 10ec:8168 | 1849:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 175   | re         | [5D0F6C2276](<Desktop/ASRock/Q1900/Q1900M/5C14E92D5780/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5D0F6C2276>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 129   | em         | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 120   | em         | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 115   | re         | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 106   | re         | [1C8295549C](<Desktop/Intel/DP55WB/DP55WB AAE64798-207/2CE77B662F6E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/1C8295549C>) |
| 10ec:8168 | 1043:8505 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 54    | re         | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 8086:153a | 1028:05a4 | Intel            | Ethernet Connection I217-LM          | 54    | em         | [69DB0AC0A4](<Desktop/Dell/OptiPlex/OptiPlex 7020/C7649894A9FD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/69DB0AC0A4>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 50    | re         | [6A15F7D4A1](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX PLUS R2.0/5AD7ACB63A8F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/6A15F7D4A1>) |
| 10ec:8168 | 103c:213d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 46    | re         | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 8086:150e | 8086:12a2 | Intel            | 82580 Gigabit Network Connection     | 43    | igb        | [D8C78B92A7](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4DBEA0F75A7B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D8C78B92A7>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 41    | igb        | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 38    | igb        | [9CD4D2810A](<Desktop/Gigabyte Technology/GA-990X-Gaming/GA-990X-Gaming SLI-CF/4C8CFDE62DD1/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9CD4D2810A>) |
| 8086:105e | 103c:7044 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 36    | em         | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 10ec:8139 | 10ec:8139 | Realtek Semic... | RTL-8100/8101L/8139 PCI Fast Ethe... | 34    | rl         | [5FC3D86BAC](<Desktop/ASUSTek Computer/A8/A8N-E/8A09F644DB88/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5FC3D86BAC>) |
| 10ec:8168 | 1043:8554 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 32    | re         | [27EA626000](<Desktop/ASUSTek Computer/All/All Series/3184501520E4/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/27EA626000>) |
| 8086:1502 | 1028:047e | Intel            | 82579LM Gigabit Network Connectio... | 32    | em         | [B8DC69069D](<Desktop/Dell/OptiPlex/OptiPlex 790/E7BEAAFD5268/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/B8DC69069D>) |
| 8086:105e | 8086:115e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 29    | em         | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:1521 | 8086:0002 | Intel            | I350 Gigabit Network Connection      | 27    | igb        | [820B3D1A1B](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s Gen 2 11R8000JUS/C14D7D997EB5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/820B3D1A1B>) |
| 14e4:165f | 103c:2133 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 26    | bge        | [409D119307](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/36E7C68AA33D/FREEBSD-12.4/12.4-RELEASE/AMD64/409D119307>) |
| 8086:105e | 8086:135e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 25    | em         | [2E3026E0FD](<Desktop/Gigabyte Technology/Z390/Z390 I AORUS PRO WIFI/CB785A37BC49/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E3026E0FD>) |
| 8086:1533 | 1849:1533 | Intel            | I210 Gigabit Network Connection      | 25    | igb        | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 21    | em         | [6A91635684](<Desktop/exone/X7/X7SPA-HF/881B5CC94BD2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6A91635684>) |
| 8086:107c | 8086:1376 | Intel            | 82541PI Gigabit Ethernet Controller  | 20    | em         | [9C526B27DD](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/93F9F29A0DC5/OPNSENSE-22.1.10/13.0-STABLE/AMD64/9C526B27DD>) |
| 10ec:8168 | 1043:859e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 19    | re         | [07982549AC](<Desktop/ASUSTek Computer/All/All Series/B3B28DAE60A0/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/07982549AC>) |
| 11ab:4364 | 1043:81f8 | Marvell Techn... | 88E8056 PCI-E Gigabit Ethernet Co... | 19    | mskc       | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 8086:15b8 | 1458:e000 | Intel            | Ethernet Connection (2) I219-V       | 18    | em         | [A15EEE8687](<Desktop/Gigabyte Technology/H270/H270-HD3/FE961B3E9735/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A15EEE8687>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 17    | ixl        | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 10ec:8125 | 1849:8125 | Realtek Semic... | RTL8125 2.5GbE Controller            | 16    | re         | [4EBEAC2699](<Desktop/ASRock/H570/H570M-ITX-ac/7252CA256A2E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/4EBEAC2699>) |
| 8086:15bc | 1043:8672 | Intel            | Ethernet Connection (7) I219-V       | 16    | em         | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 10ec:8125 | 1458:e000 | Realtek Semic... | RTL8125 2.5GbE Controller            | 15    | re         | [8D1496F3A9](<Desktop/Gigabyte Technology/X570S/X570S AORUS ELITE/BD973F606A9D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/8D1496F3A9>) |
| 8086:10fb | 8086:0003 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 14    | ix         | [0E5ED7F4DE](<Desktop/Jingsha/x79-P3/x79-P3 by xUz/7C3BC7FA7C2C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0E5ED7F4DE>) |
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 14    | igb        | [24FAA4663C](<Desktop/Supermicro/SYS-5019/SYS-5019S-L/F5044524E444/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/24FAA4663C>) |
| 10ec:8168 | 1028:0585 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 13    | re         | [C2FF0BC0B9](<Desktop/Dell/OptiPlex/OptiPlex 3010/5908ED233A1E/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C2FF0BC0B9>) |
| 15b3:1003 | 15b3:0055 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 13    | mlx4_core  | [8EB068A097](<Desktop/ASRock/X570/X570 Taichi/627244F84DF9/FREEBSD-13.1/13.1-RELEASE/AMD64/8EB068A097>) |
| 8086:153b | 1043:859f | Intel            | Ethernet Connection I217-V           | 12    | em         | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:15b7 |           | Intel            | Ethernet Connection (2) I219-LM      | 12    | em         | [0A40B02AEB](<Desktop/Others/Others/Others/FB93D11DB736/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0A40B02AEB>) |
| 11ab:4320 | 1043:811a | Marvell Techn... | 88E8001 Gigabit Ethernet Controller  | 11    | skc        | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 1969:1091 | 1458:e000 | Qualcomm Atheros | AR8161 Gigabit Ethernet              | 11    | alc        | [29290B1B9C](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2P/EC084C5059C4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/29290B1B9C>) |
| 8086:150e | 1734:11a8 | Intel            | 82580 Gigabit Network Connection     | 11    | igb        | [A3F77B82CC](<Desktop/ASUSTek Computer/PRO/PRO B460M-C/9D195AD59D5D/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/A3F77B82CC>) |
| 8086:1528 | 8086:5003 | Intel            | Ethernet Controller 10-Gigabit X5... | 11    | ix         | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 11    | igb        | [D28D10F385](<Desktop/ADI Engineering/RCC/RCC/6F22C4CD7334/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/D28D10F385>) |
| 8086:10f6 |           | Intel            | 82574L Gigabit Network Connection    | 10    | em         | [556E872FFE](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/556E872FFE>) |
| 8086:1559 | 8086:2054 | Intel            | Ethernet Connection I218-V           | 10    | em         | [F3B09CFB70](<Desktop/Intel/D54250WYK/D54250WYK H13922-303/3042A48B20AE/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/F3B09CFB70>) |
| 14e4:1657 | 14e4:1904 | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 9     | bge        | [0A9A676D17](<Desktop/Dell/Inspiron/Inspiron 3470/A0F3B9E10A40/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0A9A676D17>) |
| 10ec:8168 | 1462:7817 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 8     | re         | [12DBC1A2B3](<Desktop/MSI/MS/MS-7817/D510A20C35C7/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/12DBC1A2B3>) |
| 15b3:6750 | 15b3:0015 | Mellanox Tech... | MT26448 [ConnectX EN 10GigE, PCIe... | 8     | mlx4_core  | [947038B1F9](<Desktop/Supermicro/X9/X9SCL-X9SCM/82A38D26E59D/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/947038B1F9>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 255   | sdhci_pci  | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 81    | sdhci_pci  | [C22EE2E279](<Desktop/AZW/GK/GK55/8FD2B3239B52/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C22EE2E279>) |
| 8086:4df8 | 8086:7270 | Intel            | SD Host Controller                   | 60    | sdhci_pci  | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:31d0 | 8086:7270 | Intel            | Celeron/Pentium Silver SD Host Co... | 23    | sdhci_pci  | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 21    | sdhci_pci  | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 8086:9dc4 | 8086:7270 | Intel            | Cannon Point-LP SD Host Controller   | 21    | sdhci_pci  | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:9df5 | 8086:7270 | Intel            | BayHubTech Integrated SD controller  | 21    | sdhci_pci  | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | sdhci_pci  | [8537AC75A1](<Desktop/AAEON/UP-APL/UP-APL01/605633FC34DD/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8537AC75A1>) |
| 8086:19db | 8086:7270 | Intel            | Atom Processor C3000 Series SD Ho... | 18    | sdhci_pci  | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 10    | sdhci_pci  | [E9E179E9AC](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 832 ZMB/574A3DFD4C34/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E9E179E9AC>) |
| 8086:02c4 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS1: eMMC         | 7     | sdhci_pci  | [44B691E7B8](<Desktop/Protectli/VP/VP4650/6092756008BB/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/44B691E7B8>) |
| 8086:4dc4 | 8086:7270 | Intel            | Jasper Lake SCS1: eMMC Controller    | 7     | sdhci_pci  | [B815AE3950](<Desktop/GoWin Solution/R86/R86S/057DBA2F6645/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B815AE3950>) |
| 8086:a375 | 103c:843f | Intel            | 300 Series Chipset Family SD Host... | 6     | sdhci_pci  | [23D8A9BDA7](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/BD57B07B0D05/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/23D8A9BDA7>) |
| 1022:7806 | 1022:7806 | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [7058138064](<Desktop/Hewlett-Packard/p7/p7-1154/9A6BFC6540AF/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/7058138064>) |
| 8086:02f5 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS3               | 5     | sdhci_pci  | [F31F4C00CD](<Desktop/Others/Others/Others/072D58D76F08/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/F31F4C00CD>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 5     | sdhci_pci  | [8537AC75A1](<Desktop/AAEON/UP-APL/UP-APL01/605633FC34DD/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8537AC75A1>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 4     | sdhci_pci  | [C3FFB2C87D](<Desktop/AMI/PEISIA/PEISIA E3845 VER1.0/F1AF209585D4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C3FFB2C87D>) |
| 8086:9d2b | 8086:7270 | Intel            | Skylake-U/Y SCC: eMMC                | 4     | sdhci_pci  | [796FE84E29](<Desktop/Others/Others/Others/4F168F055C91/OPNSENSE-22.1.7/13.0-STABLE/AMD64/796FE84E29>) |
| 8086:06f5 | 8086:7270 | Intel            | 400 Series Chipset Family SD Host... | 3     | sdhci_pci  | [B9994AA302](<Desktop/Others/Others/Others/0043505011B9/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/B9994AA302>) |
| 8086:2294 | 8086:2294 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [C84BEDC821](<Desktop/Gigabyte Technology/N3160/N3160ND3V/B01DE72F7AFE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C84BEDC821>) |
| 8086:2296 | 8086:2296 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [C84BEDC821](<Desktop/Gigabyte Technology/N3160/N3160ND3V/B01DE72F7AFE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C84BEDC821>) |
| 8086:a375 | 103c:843b | Intel            | 300 Series Chipset Family SD Host... | 3     | sdhci_pci  | [C1886BCD29](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0FC3EEDA5ED5/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/C1886BCD29>) |
| 1022:7813 | 1022:7813 | AMD              | FCH SD Flash Controller              | 2     | sdhci_pci  | [8B9A301B47](<Desktop/M613/G420/G420N1WNS/19C20EF0FF54/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8B9A301B47>) |
| 8086:06f5 | 103c:8767 | Intel            | 400 Series Chipset Family SD Host... | 2     | sdhci_pci  | [9D98B3BAA4](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-1xxx/316ACA3FC06A/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/9D98B3BAA4>) |
| 8086:2294 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | sdhci_pci  | [0ADF0CA671](<Desktop/ZOTAC/Others/Others/6E70FB5A2725/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/0ADF0CA671>) |
| 8086:2294 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | sdhci_pci  | [5673B5C8E8](<Desktop/WesternDigital/WDBNFA0320/WDBNFA0320KBK-40/56D38F05606E/OPNSENSE-22.7/13.1-RELEASE/AMD64/5673B5C8E8>) |
| 8086:2296 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | sdhci_pci  | [5673B5C8E8](<Desktop/WesternDigital/WDBNFA0320/WDBNFA0320KBK-40/56D38F05606E/OPNSENSE-22.7/13.1-RELEASE/AMD64/5673B5C8E8>) |
| 8086:31cc | 1458:1000 | Intel            | Celeron/Pentium Silver Processor ... | 2     | sdhci_pci  | [F54F8DB756](<Desktop/Gigabyte Technology/MZGLKDP/MZGLKDP-00/58918403E428/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/F54F8DB756>) |
| 8086:31d0 | 1458:1000 | Intel            | Celeron/Pentium Silver SD Host Co... | 2     | sdhci_pci  | [F54F8DB756](<Desktop/Gigabyte Technology/MZGLKDP/MZGLKDP-00/58918403E428/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/F54F8DB756>) |
| 8086:4b47 | 8086:7270 | Intel            | Atom SD Host Controller              | 2     | sdhci_pci  | [AC2228FA2B](<Desktop/Protectli/VP/VP2420/E90D8EE114FD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC2228FA2B>) |
| 8086:4dc4 |           | Intel            | Jasper Lake SCS1: eMMC Controller    | 2     | sdhci_pci  | [8C983F91E4](<Desktop/AWOW/AK/AK50/7E18C0CE25A5/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8C983F91E4>) |
| 8086:4df8 |           | Intel            | SD Host Controller                   | 2     | sdhci_pci  | [8C983F91E4](<Desktop/AWOW/AK/AK50/7E18C0CE25A5/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8C983F91E4>) |
| 8086:9d2d | 8086:7270 | Intel            | Sunrise Point-LP Secure Digital I... | 2     | sdhci_pci  | [796FE84E29](<Desktop/Others/Others/Others/4F168F055C91/OPNSENSE-22.1.7/13.0-STABLE/AMD64/796FE84E29>) |
| 1022:7906 | 1022:7906 | AMD              | FCH SD Flash Controller              | 1     | sdhci_pci  | [B2540F3BEB](<Desktop/Micro Computer (HK) Tech Limited/MT4/MT4UB1/0EF0D2083CC5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2540F3BEB>) |
| 10ec:5209 | 10ec:5209 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 1     |            | [FA57448331](<Desktop/Acer/Veriton/Veriton N2620G/A3AD7EE84FF2/HELLOSYSTEM-0.8.1/13.1-RELEASE-P6/AMD64/FA57448331>) |
| 8086:0f15 | 8086:0f15 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | sdhci_pci  | [7763F089A3](<Desktop/CNCTION-IAF-E3845/Others/Others/FABA34AD5631/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/7763F089A3>) |
| 8086:5aca | 1071:0787 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [00E52DF710](<Desktop/MiTAC/UltraPoint/UltraPoint/4F52B749418F/OPNSENSE-22.1.10/13.0-STABLE/AMD64/00E52DF710>) |
| 8086:5acc | 1019:9cc7 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [D091F171B7](<Desktop/ULTRATOP/C2017/C2017-LIVA-ZE/DB17C050528F/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/D091F171B7>) |
| 8086:5acc | 1071:0787 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [00E52DF710](<Desktop/MiTAC/UltraPoint/UltraPoint/4F52B749418F/OPNSENSE-22.1.10/13.0-STABLE/AMD64/00E52DF710>) |
| 8086:5acc | 8086:2071 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [DEF5A082BE](<Desktop/Intel/CD1/CD1C64GK/27C02BE03675/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/DEF5A082BE>) |
| 8086:a375 | 103c:844c | Intel            | 300 Series Chipset Family SD Host... | 1     | sdhci_pci  | [FB7D8EAF5D](<Desktop/Hewlett-Packard/844/844C/26AC45136BF9/HELLOSYSTEM-0.7.0/12.2-RELEASE/AMD64/FB7D8EAF5D>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:4da4 | 8086:7270 | Intel            | Jasper Lake SPI Controller           | 147   |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:4de8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 70    |            | [E09800B936](<Desktop/maiyunda/www.maiyunda.com/www.maiyunda.com/5F223CD2630E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E09800B936>) |
| 8086:4dea | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 67    |            | [E09800B936](<Desktop/maiyunda/www.maiyunda.com/www.maiyunda.com/5F223CD2630E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E09800B936>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 30    |            | [6AC60B8104](<Desktop/Gigabyte Technology/B360/B360M-D2V/F8AFE9A62606/FREEBSD-13.1/13.1-RELEASE/AMD64/6AC60B8104>) |
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 27    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:a324 | 1043:8694 | Intel            | Cannon Lake PCH SPI Controller       | 26    |            | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 8086:19e0 | 8086:7270 | Intel            | Atom Processor C3000 Series SPI C... | 24    |            | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:9dc5 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 21    | ig4iic     | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:9de8 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 21    | ig4iic     | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:9de9 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 21    | ig4iic     | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 18    |            | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:4b24 | 8086:7270 | Intel            | Elkhart Lake SPI (Flash) Controller  | 18    |            | [21D2214DA6](<Desktop/Protectli/VP/VP2420/F9E7BE26C82B/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/21D2214DA6>) |
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 16    |            | [B639F4670E](<Desktop/Intel/CNCTION-IAF/CNCTION-IAF/23F29A5F79A0/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B639F4670E>) |
| 8086:a324 | 1849:a324 | Intel            | Cannon Lake PCH SPI Controller       | 16    |            | [0E0C795886](<Desktop/ASRock/H310/H310M-ITX-ac/1C596F08C310/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0E0C795886>) |
| 8086:43a4 | 1043:8694 | Intel            | Tiger Lake-H SPI Controller          | 14    |            | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:43e8 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 14    | ig4iic     | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:22c2 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 13    | ig4iic     | [34B349EEAD](<Desktop/Protectli/FW2/FW2B/EE3235442DAF/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/34B349EEAD>) |
| 8086:4de9 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 13    |            | [34CF4827D7](<Desktop/Hardkernel/ODROID-H/ODROID-H3/174DBB630022/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/34CF4827D7>) |
| 8086:22c1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 12    | ig4iic     | [34B349EEAD](<Desktop/Protectli/FW2/FW2B/EE3235442DAF/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/34B349EEAD>) |
| 8086:43e9 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 12    | ig4iic     | [55AFDE6894](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z590-PLUS/BD8BD7D4DA30/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/55AFDE6894>) |
| 8086:a0a4 | 8086:7270 | Intel            | Tiger Lake-LP SPI Controller         | 12    |            | [5082B8203B](<Desktop/Others/Others/Others/AB924515ADF1/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/5082B8203B>) |
| 8086:a1a4 | 15d9:0986 | Intel            | C620 Series Chipset Family SPI Co... | 12    |            | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 11    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:34ab | 8086:7270 | Intel            | Ice Lake-LP Serial IO SPI Control... | 11    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 11    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:4dab | 8086:7270 | Intel            | Jasper Lake LPSS: SPI Controller #1  | 11    |            | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 8086:4dc5 | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 11    |            | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 8086:4dc6 | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 11    |            | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 10    |            | [6F8AD1A8B9](<Desktop/Gigabyte Technology/Z490/Z490 VISION G/61A52C9709E8/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6F8AD1A8B9>) |
| 8086:4deb | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #3  | 10    |            | [A4E906C608](<Desktop/AZW/U/U59/C3F2FFC219C7/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/A4E906C608>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 8     |            | [9CD1C1FC21](<Desktop/Supermicro/SYS-E200/SYS-E200-9A/41FCF82CB6BD/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/9CD1C1FC21>) |
| 8086:43a4 | 1849:43a4 | Intel            | Tiger Lake-H SPI Controller          | 8     |            | [4EBEAC2699](<Desktop/ASRock/H570/H570M-ITX-ac/7252CA256A2E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/4EBEAC2699>) |
| 8086:9da4 | 1297:4076 | Intel            | Cannon Point-LP SPI Controller       | 8     |            | [0F1E027B35](<Desktop/Shuttle/DS10/DS10U/EB8F6226ED0B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/0F1E027B35>) |
| 8086:a324 | 1028:085a | Intel            | Cannon Lake PCH SPI Controller       | 8     |            | [53FA01007B](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/53FA01007B>) |
| 8086:a368 | 1028:085a | Intel            | Cannon Lake PCH Serial IO I2C Con... | 8     | ig4iic     | [53FA01007B](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/53FA01007B>) |
| 8086:a368 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 8     | ig4iic     | [80814C04B6](<Desktop/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/D5B76A2D718E/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/80814C04B6>) |
| 8086:a369 | 8086:7270 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 8     | ig4iic     | [80814C04B6](<Desktop/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/D5B76A2D718E/OPNSENSE-22.10.2/13.1-RELEASE-P7/AMD64/80814C04B6>) |
| 8086:43a4 |           | Intel            | Tiger Lake-H SPI Controller          | 7     |            | [85628154A2](<Desktop/Gigabyte Technology/H510M/H510M S2H V2/D6902D5FE2E5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/85628154A2>) |
| 8086:7aa4 | 1043:8694 | Intel            | Alder Lake-S PCH SPI Controller      | 7     |            | [C3281EB186](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/967511C3CD54/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/C3281EB186>) |
| 8086:7aa4 | 1849:7aa4 | Intel            | Alder Lake-S PCH SPI Controller      | 7     |            | [98FE8CC428](<Desktop/ASRock/H610M-HVS-M.2/H610M-HVS-M.2 R2.0/57BE5CD5A2D2/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/98FE8CC428>) |
| 8086:7acc | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | ig4iic     | [C3281EB186](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/967511C3CD54/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/C3281EB186>) |
| 8086:7acc | 1849:7acc | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 7     | ig4iic     | [98FE8CC428](<Desktop/ASRock/H610M-HVS-M.2/H610M-HVS-M.2 R2.0/57BE5CD5A2D2/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/98FE8CC428>) |
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 6     |            | [4E059E9162](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/4E059E9162>) |
| 8086:02c5 | 8086:7270 | Intel            | Comet Lake Serial IO I2C Host Con... | 6     | ig4iic     | [768A10819B](<Desktop/Others/QD-CMU/QD-CMU01/23D04D465989/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/768A10819B>) |
| 8086:7acd | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 6     | ig4iic     | [C3281EB186](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/967511C3CD54/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/C3281EB186>) |
| 8086:7ace | 1043:8694 | Intel            | Alder Lake-S PCH Serial IO I2C Co... | 6     | ig4iic     | [C3281EB186](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/967511C3CD54/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/C3281EB186>) |
| 8086:a324 | 103c:843f | Intel            | Cannon Lake PCH SPI Controller       | 6     |            | [23D8A9BDA7](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/BD57B07B0D05/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/23D8A9BDA7>) |
| 8086:a368 | 103c:843f | Intel            | Cannon Lake PCH Serial IO I2C Con... | 6     | ig4iic     | [23D8A9BDA7](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/BD57B07B0D05/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/23D8A9BDA7>) |
| 8086:a369 | 103c:843f | Intel            | Cannon Lake PCH Serial IO I2C Con... | 6     | ig4iic     | [23D8A9BDA7](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/BD57B07B0D05/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/23D8A9BDA7>) |
| 1425:4601 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 5     |            | [6905821659](<Desktop/ASRock/X99/X99 Extreme4/3BEC2E139880/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/6905821659>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 156   | pchtherm   | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:4e03 | 8086:7270 | Intel            | Dynamic Tuning service               | 92    |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 84    |            | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 82    | ig4iic     | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 82    | ig4iic     | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 53    | ig4iic     | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 52    | ig4iic     | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 52    | ig4iic     | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 49    |            | [D7B171D0BB](<Desktop/Others/Others/Others/E869214B6318/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/D7B171D0BB>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 30    | ig4iic     | [BD675A503D](<Desktop/Hardkernel/ODROID-H/ODROID-H2/D15B59962C50/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/BD675A503D>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2015 |           | Intel            | Sky Lake-E Ubox Registers            | 27    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 8086:204d |           | Intel            | Sky Lake-E M3KTI Registers           | 27    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 27    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 27    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:9df9 | 8086:7270 | Intel            | Cannon Point-LP Thermal Controller   | 27    | pchtherm   | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 26    | uart       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 26    | uart       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 26    | uart       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 26    |            | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 26    | uart       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:204c |           | Intel            | Sky Lake-E M3KTI Registers           | 25    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 8086:1903 | 8086:7270 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 24    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:1903 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 22    |            | [95C62844DE](<Desktop/Others/Others/Others/722F4261A23A/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/95C62844DE>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 20    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 20    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 20    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 20    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 20    |            | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 19    | ig4iic     | [8537AC75A1](<Desktop/AAEON/UP-APL/UP-APL01/605633FC34DD/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8537AC75A1>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 19    | ig4iic     | [8537AC75A1](<Desktop/AAEON/UP-APL/UP-APL01/605633FC34DD/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/8537AC75A1>) |
| 8086:a379 | 1458:8888 | Intel            | Cannon Lake PCH Thermal Controller   | 19    | pchtherm   | [6AC60B8104](<Desktop/Gigabyte Technology/B360/B360M-D2V/F8AFE9A62606/FREEBSD-13.1/13.1-RELEASE/AMD64/6AC60B8104>) |
| 8086:02f9 | 8086:7270 | Intel            | Comet Lake Thermal Subsytem          | 18    | pchtherm   | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:318c | 1849:318c | Intel            | Celeron/Pentium Silver Processor ... | 17    |            | [C4BF6A3B8C](<Desktop/ASRock/J4005/J4005B-ITX/BFD6E10C2B45/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/C4BF6A3B8C>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 17    | pchtherm   | [DF7F4524D7](<Desktop/Others/SKYBAY/SKYBAY/A6E8FBDE5F97/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DF7F4524D7>) |
| 8086:a2b1 | 1849:a2b1 | Intel            | 200 Series PCH Thermal Subsystem     | 17    |            | [0B7DACF902](<Desktop/ASRock/X299/X299E-ITX-ac/78187292FFBE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0B7DACF902>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 16    | ig4iic     | [F5DA027D84](<Desktop/AZW/Green/Green G1/80E61ECB6F78/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F5DA027D84>) |
| 8086:a379 | 1849:a379 | Intel            | Cannon Lake PCH Thermal Controller   | 16    | pchtherm   | [0E0C795886](<Desktop/ASRock/H310/H310M-ITX-ac/1C596F08C310/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/0E0C795886>) |
| 8086:a131 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 15    | pchtherm   | [D69ABA5432](<Desktop/Fujitsu/ESPRIMO/ESPRIMO Q956/C9D1C0D177A5/FREEBSD-13.1/13.1-RELEASE/AMD64/D69ABA5432>) |
| 8086:8c24 | 1734:11ea | Intel            | 8 Series Chipset Family Thermal M... | 14    | pchtherm   | [C34D5E6357](<Desktop/Fujitsu/ESPRIMO/ESPRIMO C720/D59156C0581D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C34D5E6357>) |
| 8086:9d31 | 8086:9d31 | Intel            | Sunrise Point-LP Thermal subsystem   | 14    | pchtherm   | [F58E088DF2](<Desktop/Others/Others/Others/E49A78BE4C54/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F58E088DF2>) |
| 8086:a131 | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    | pchtherm   | [226F25A086](<Desktop/Dell/OptiPlex/OptiPlex 7040/DD40E35F79F7/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/226F25A086>) |
| 8086:a131 | 1028:06bb | Intel            | 100 Series/C230 Series Chipset Fa... | 12    | pchtherm   | [C51A264E20](<Desktop/Dell/OptiPlex/OptiPlex 3040/3E96FED82A87/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C51A264E20>) |
| 8086:a131 | 1849:a131 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    | pchtherm   | [7CC4B63834](<Desktop/ASRock/H110/H110 Pro BTC+/CB21DA586B1D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CC4B63834>) |
| 8086:a1b1 | 15d9:0986 | Intel            | C620 Series Chipset Family Therma... | 12    | pchtherm   | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 8086:a131 | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 11    | pchtherm   | [7A7DD659C8](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/AAEB268489C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7A7DD659C8>) |
| 8086:a2b1 | 1028:07a1 | Intel            | 200 Series PCH Thermal Subsystem     | 11    |            | [22A1B812F8](<Desktop/Dell/OptiPlex/OptiPlex 7050/CB83CBBB388D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/22A1B812F8>) |
| 8086:a2e0 | 1028:07a1 | Intel            | 200 Series PCH Serial IO I2C Cont... | 11    |            | [22A1B812F8](<Desktop/Dell/OptiPlex/OptiPlex 7050/CB83CBBB388D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/22A1B812F8>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 278   | intsmb     | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 239   | ichsmb     | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 212   | ichsmb     | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 174   | ichsmb     | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:4da3 | 8086:7270 | Intel            | Jasper Lake SMBus                    | 147   |            | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 93    | ichsmb     | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 1022:790b | 1458:5001 | AMD              | FCH SMBus Controller                 | 80    | intsmb     | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1022:780b | 1734:1202 | AMD              | FCH SMBus Controller                 | 74    | intsmb     | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 68    | ichsmb     | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 1022:790b | 1849:ffff | AMD              | FCH SMBus Controller                 | 66    | intsmb     | [2A6207FB45](<Desktop/ASRock/X300/X300M-STX/6196E1492AD8/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2A6207FB45>) |
| 1022:790b | 1043:87c0 | AMD              | FCH SMBus Controller                 | 57    | intsmb     | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:790b | 1849:790b | AMD              | FCH SMBus Controller                 | 55    | intsmb     | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 55    | ichsmb     | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1022:780b | 103c:213d | AMD              | FCH SMBus Controller                 | 51    | intsmb     | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 44    | intsmb     | [E376971BD6](<Desktop/ChangWang/CW56/CW56-58/7AC0129D343D/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E376971BD6>) |
| 1002:4385 | 1002:4385 | AMD              | SBx00 SMBus Controller               | 42    | intsmb     | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 8086:283e | 8086:283e | Intel            | 82801H (ICH8 Family) SMBus Contro... | 42    | ichsmb     | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:8c22 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | ichsmb     | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c22 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | ichsmb     | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:27da | 8086:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 40    | ichsmb     | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:8c22 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 38    | ichsmb     | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:a123 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | ichsmb     | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 8086:1c22 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | ichsmb     | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 1022:790b | 1043:8747 | AMD              | FCH SMBus Controller                 | 35    | intsmb     | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 8086:1c22 | 1458:5001 | Intel            | 6 Series/C200 Series Chipset Fami... | 35    | ichsmb     | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 34    | intsmb     | [2E40DF5A32](<Desktop/WYSE/Z/Z CLASS/76E6DE34A38F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E40DF5A32>) |
| 8086:1e22 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family SMBu... | 34    | ichsmb     | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:1e22 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family SMBu... | 32    | ichsmb     | [A2873D7C87](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/A2873D7C87>) |
| 8086:1c22 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 31    | ichsmb     | [904FDE472A](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/904FDE472A>) |
| 8086:1e22 | 1458:5001 | Intel            | 7 Series/C216 Chipset Family SMBu... | 30    | ichsmb     | [D8C78B92A7](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4DBEA0F75A7B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D8C78B92A7>) |
| 8086:3a30 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 30    | ichsmb     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 28    | ichsmb     | [B2176FAFCF](<Desktop/Intel/MAHOBAY/MAHOBAY/0D48ADEA90BB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2176FAFCF>) |
| 8086:9da3 | 8086:7270 | Intel            | Cannon Point-LP SMBus Controller     | 27    |            | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 1002:4385 | 1022:1510 | AMD              | SBx00 SMBus Controller               | 26    | intsmb     | [1162545537](<Desktop/PC Engines/APU/APU/87128D66CD5A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/1162545537>) |
| 1002:4385 | 1043:8389 | AMD              | SBx00 SMBus Controller               | 26    | intsmb     | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |
| 8086:8c22 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 26    | ichsmb     | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:a323 | 1043:8694 | Intel            | Cannon Lake PCH SMBus Controller     | 26    | ichsmb     | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 25    | ichsmb     | [B639F4670E](<Desktop/Intel/CNCTION-IAF/CNCTION-IAF/23F29A5F79A0/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B639F4670E>) |
| 8086:8c22 | 1458:5001 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | ichsmb     | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 8086:a2a3 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family SM... | 25    | ichsmb     | [FD39A615DE](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-K R2.0/7D5721B3D945/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD39A615DE>) |
| 8086:19df | 8086:7270 | Intel            | Atom Processor C3000 Series SMBus... | 24    | ichsmb     | [6FAF4AED53](<Desktop/Dell EMC/VEP1425/VEP1425-V210/3D854A7B1556/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6FAF4AED53>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 24    | ichsmb     | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 23    | ichsmb     | [1F55DB62CC](<Desktop/Others/YL-1900/YL-1900L4-V2/8B6BEEBE711D/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/1F55DB62CC>) |
| 8086:5ad4 | 1849:5ad4 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 23    |            | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 8086:1e22 | 8086:1e22 | Intel            | 7 Series/C216 Chipset Family SMBu... | 21    | ichsmb     | [AE6EA07868](<Desktop/Advantech/UTC-520/UTC-520C/92E6177F9568/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/AE6EA07868>) |
| 8086:a2a3 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family SM... | 21    | ichsmb     | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 1002:4385 | 1849:4385 | AMD              | SBx00 SMBus Controller               | 20    | intsmb     | [461F8CCA23](<Desktop/ASRock/E350/E350M1/DA069FB4F97A/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/461F8CCA23>) |
| 1022:790b | 1043:876b | AMD              | FCH SMBus Controller                 | 20    | intsmb     | [CA70BCEB83](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-E/964B28FB1DE0/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CA70BCEB83>) |
| 8086:8c22 | 1849:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ichsmb     | [28E606751F](<Desktop/ASRock/H81/H81M-HDS/255D1BAAA00A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/28E606751F>) |
| 8086:a123 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 20    | ichsmb     | [FB5A559634](<Desktop/Gigabyte Technology/B150/B150-HD3P/7B89078673EA/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/FB5A559634>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 184   | hdac       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 163   | hdac       | [F75FEE2A2D](<Desktop/Others/YL-J3160/YL-J3160L4/124BE58E7612/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F75FEE2A2D>) |
| 8086:4dc8 | 8086:7270 | Intel            | Jasper Lake HD Audio                 | 146   | hdac       | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 127   | hdac       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 1002:9840 | 1734:1202 | AMD              | Kabini HDMI/DP Audio                 | 74    | hdac       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:160c | 8086:160c | Intel            | Broadwell-U Audio Controller         | 62    | hdac       | [C5769BCAE3](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/C647CFB929B6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C5769BCAE3>) |
| 8086:9ca0 | 8086:7270 | Intel            | Wildcat Point-LP High Definition ... | 62    | hdac       | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 57    | hdac       | [85AECF8C3F](<Desktop/MSI/MS-7/MS-7A38/2325A856795F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/85AECF8C3F>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 53    | hdac       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 8086:0a0c | 8086:0a0c | Intel            | Haswell-ULT HD Audio Controller      | 52    | hdac       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1002:9840 | 103c:213d | AMD              | Kabini HDMI/DP Audio                 | 51    | hdac       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:780d | 103c:213d | AMD              | FCH Azalia Controller                | 47    | hdac       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:780d | 1734:1203 | AMD              | FCH Azalia Controller                | 46    | hdac       | [6729453203](<Desktop/Fujitsu/FUTRO/FUTRO S920/ED892B6BC60E/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/6729453203>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 42    | hdac       | [77A58527DA](<Desktop/Gigabyte Technology/H97/H97M-HD3/E5275305C703/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/77A58527DA>) |
| 8086:8c20 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset High... | 42    | hdac       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:0c0c | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 40    | hdac       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 39    | hdac       | [52186B4343](<Desktop/CNCTION-IAF-E3845/Others/Others/DDE5F157AE2B/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/52186B4343>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 37    | hdac       | [2A6207FB45](<Desktop/ASRock/X300/X300M-STX/6196E1492AD8/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2A6207FB45>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 36    | hdac       | [1E97EE1C05](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/98235472B8D9/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/1E97EE1C05>) |
| 8086:0c0c | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 36    | hdac       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c20 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset High... | 36    | hdac       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:0c0c | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 34    | hdac       | [EC33F29DC0](<Desktop/ASUSTek Computer/All/All Series/9506DED5E0BD/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/EC33F29DC0>) |
| 8086:1e20 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family High... | 29    | hdac       | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 8086:0c0c | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 26    | hdac       | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:9dc8 | 8086:7270 | Intel            | Cannon Point-LP High Definition A... | 26    | hdac       | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 25    | hdac       | [12AC44CBF7](<Desktop/Others/Others/Others/B6CD8CD35969/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/12AC44CBF7>) |
| 8086:8c20 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset High... | 25    | hdac       | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:1c20 | 1458:a002 | Intel            | 6 Series/C200 Series Chipset Fami... | 22    | hdac       | [33AF90DD93](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/954969B6DBB2/FREEBSD-13.1/13.1-RELEASE/AMD64/33AF90DD93>) |
| 1002:aaf0 | 1da2:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 21    | hdac       | [6F8AD1A8B9](<Desktop/Gigabyte Technology/Z490/Z490 VISION G/61A52C9709E8/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6F8AD1A8B9>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 21    | hdac       | [B639F4670E](<Desktop/Intel/CNCTION-IAF/CNCTION-IAF/23F29A5F79A0/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B639F4670E>) |
| 1002:ab28 | 1002:ab28 | AMD              | Navi 21/23 HDMI/DP Audio Controller  | 19    | hdac       | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 8086:8c20 | 1458:a002 | Intel            | 8 Series/C220 Series Chipset High... | 19    | hdac       | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 1002:15de | 1043:876b | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 18    | hdac       | [CA70BCEB83](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-E/964B28FB1DE0/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CA70BCEB83>) |
| 8086:3198 | 10ec:115a | Intel            | Celeron/Pentium Silver Processor ... | 18    | hdac       | [B2681FDFB4](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/80E9D30F1713/FREEBSD-13.1/13.1-RELEASE/AMD64/B2681FDFB4>) |
| 8086:9d70 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 18    | hdac       | [D3750005C2](<Desktop/Others/Others/Others/C14747EBBA5F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/D3750005C2>) |
| 1002:ab38 | 1002:ab38 | AMD              | Navi 10 HDMI Audio                   | 17    | hdac       | [0A39FFA716](<Desktop/Biostar/TB250/TB250-BTC+/A8163A94649F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/0A39FFA716>) |
| 1022:780d | 1022:780d | AMD              | FCH Azalia Controller                | 17    | hdac       | [8B9A301B47](<Desktop/M613/G420/G420N1WNS/19C20EF0FF54/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/8B9A301B47>) |
| 8086:02c8 | 8086:7270 | Intel            | Comet Lake PCH-LP cAVS               | 17    | hdac       | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:1c20 | 1028:04ad | Intel            | 6 Series/C200 Series Chipset Fami... | 17    | hdac       | [B8DC69069D](<Desktop/Dell/OptiPlex/OptiPlex 790/E7BEAAFD5268/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/B8DC69069D>) |
| 8086:1e20 | 103c:3397 | Intel            | 7 Series/C216 Chipset Family High... | 17    | hdac       | [8B231FD832](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 SFF/E655728809C3/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/8B231FD832>) |
| 8086:4b58 | 8086:7270 | Intel            | Elkhart Lake High Density Audio b... | 17    | hdac       | [21D2214DA6](<Desktop/Protectli/VP/VP2420/F9E7BE26C82B/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/21D2214DA6>) |
| 8086:8c20 | 103c:18e7 | Intel            | 8 Series/C220 Series Chipset High... | 17    | hdac       | [0B962B9400](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/AC9F58576E1B/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/0B962B9400>) |
| 8086:8c20 | 1043:8576 | Intel            | 8 Series/C220 Series Chipset High... | 17    | hdac       | [07982549AC](<Desktop/ASUSTek Computer/All/All Series/B3B28DAE60A0/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/07982549AC>) |
| 8086:a2f0 | 1458:a182 | Intel            | 200 Series PCH HD Audio              | 17    | hdac       | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 8086:0c0c | 103c:18e7 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 16    | hdac       | [0B962B9400](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G1 SFF/AC9F58576E1B/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/0B962B9400>) |
| 8086:1e20 | 8086:1e20 | Intel            | 7 Series/C216 Chipset Family High... | 16    | hdac       | [AE6EA07868](<Desktop/Advantech/UTC-520/UTC-520C/92E6177F9568/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/AE6EA07868>) |
| 1002:1637 | 1043:8809 | AMD              | Renoir Radeon High Definition Aud... | 15    | hdac       | [3548F4EFA2](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/75E66F2BE030/FREEBSD-13.2-STABLE/13.2-STABLE/AMD64/3548F4EFA2>) |
| 1022:1457 | 1458:a182 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 15    | hdac       | [51EC4CE710](<Desktop/Gigabyte Technology/B450M/B450M DS3H/84ACADF7AB31/GHOSTBSD-22.10.12/13.1-STABLE/AMD64/51EC4CE710>) |
| 1022:1487 | 1043:8797 | AMD              | Starship/Matisse HD Audio Controller | 15    | hdac       | [5507E05838](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PRO S/A08B3D208635/FREEBSD-13.1-P6/13.1-RELEASE-P6/AMD64/5507E05838>) |
| 1022:15e3 | 1043:86c7 | AMD              | Family 17h/19h HD Audio Controller   | 15    | hdac       | [CA70BCEB83](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-E/964B28FB1DE0/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CA70BCEB83>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1283:8211 | 1283:8211 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 2     | atapci     | [BA1D9A51C2](<Desktop/Intel/Bearlake/Bearlake Bearlake Fab A/57F476905C38/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/BA1D9A51C2>) |
| 105a:4d30 | 105a:4d33 | Promise Techn... | PDC20267 (FastTrak100/Ultra100)      | 1     | atapci     | [D99AE1AAD1](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX PLUS/627BCCBE6A6E/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/D99AE1AAD1>) |
| 105a:4d69 | 105a:4d68 | Promise Techn... | 20269                                | 1     | atapci     | [8D99F317E4](<Desktop/TYAN Computer/Intel/Intel 440BX-GX Rev. 4/05C7EC931544/FREEBSD-13.1-P2/13.1-RELEASE-P2/I386/8D99F317E4>) |
| 1283:8211 | 1043:8138 | Integrated Te... | ITE 8211F Single Channel UDMA 133    | 1     | atapci     | [A2B5067552](<Desktop/ASUSTek Computer/P5/P5WD2-Premium/EB10AF6202CE/OPNSENSE-22.1.4/13.0-STABLE/AMD64/A2B5067552>) |
| 1aed:1005 | 1aed:1010 | SanDisk          | ioDimm3                              | 1     | fct        | [6905821659](<Desktop/ASRock/X99/X99 Extreme4/3BEC2E139880/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/6905821659>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 238   | ahci       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 220   | ahci       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 174   | ahci       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 1022:7801 | 1022:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 169   | ahci       | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 136   | ahci       | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:4dd3 | 8086:7270 | Intel            | Jasper Lake SATA AHCI Controller     | 131   | ahci       | [F07E092146](<Desktop/Techvision/TVI7309/TVI7309X/432837343A25/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F07E092146>) |
| 1022:43c8 | 1b21:1062 | AMD              | 400 Series Chipset SATA Controller   | 120   | ahci       | [85AECF8C3F](<Desktop/MSI/MS-7/MS-7A38/2325A856795F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/85AECF8C3F>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 93    | ahci       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 1022:7801 | 1734:1202 | AMD              | FCH SATA Controller [AHCI mode]      | 73    | ahci       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 68    | ahci       | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 1022:43eb | 1b21:1062 | AMD              | 500 Series Chipset SATA Controller   | 61    | ahci       | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 55    | ahci       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1b21:0612 | 1849:0612 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 53    | ahci       | [48C80BBB1F](<Desktop/ASRock/H61/H61M-U3S3/5FF9535C321A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/48C80BBB1F>) |
| 1022:7801 | 103c:213d | AMD              | FCH SATA Controller [AHCI mode]      | 51    | ahci       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:7901 | 1849:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 51    | ahci       | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 1022:7901 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 50    | ahci       | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 44    | ahci       | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:8c02 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 41    | ahci       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 40    | ahci       | [2E40DF5A32](<Desktop/WYSE/Z/Z CLASS/76E6DE34A38F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2E40DF5A32>) |
| 8086:a102 | 1043:8694 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 38    | ahci       | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 1022:43b8 | 1b21:1062 | AMD              | FCH SATA Controller D                | 37    | ahci       | [593F6FF02D](<Desktop/MSI/MS-7/MS-7C51/435F418C7DE2/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/593F6FF02D>) |
| 8086:8c02 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 36    | ahci       | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:1e02 | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 33    | ahci       | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |
| 1022:7901 | 1043:8747 | AMD              | FCH SATA Controller [AHCI mode]      | 31    | ahci       | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 1022:7901 | 1849:ffff | AMD              | FCH SATA Controller [AHCI mode]      | 30    | ahci       | [2A6207FB45](<Desktop/ASRock/X300/X300M-STX/6196E1492AD8/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2A6207FB45>) |
| 8086:1c02 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 28    | ahci       | [904FDE472A](<Desktop/Seneca/Pro/Pro546267/7046F64B97D5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/904FDE472A>) |
| 8086:1c02 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 27    | ahci       | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:1e02 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 27    | ahci       | [A2873D7C87](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/A2873D7C87>) |
| 8086:9dd3 | 8086:7270 | Intel            | Cannon Point-LP SATA Controller [... | 27    | ahci       | [DBE1C51575](<Desktop/Others/Others/Others/7A14B1FE5621/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DBE1C51575>) |
| 8086:8c02 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 26    | ahci       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 1b21:0612 | 1043:84b7 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 25    | ahci       | [A2873D7C87](<Desktop/ASUSTek Computer/P8Z77-V/P8Z77-V PREMIUM/3577E3899A73/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/A2873D7C87>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 25    | ahci       | [B639F4670E](<Desktop/Intel/CNCTION-IAF/CNCTION-IAF/23F29A5F79A0/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B639F4670E>) |
| 8086:a352 | 1043:8694 | Intel            | Cannon Lake PCH SATA AHCI Controller | 25    | ahci       | [BE81F2675F](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z390-E GAMING/58D30859C03A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/BE81F2675F>) |
| 8086:8c02 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 24    | ahci       | [E0AB2D859C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/67C824D37259/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/E0AB2D859C>) |
| 8086:a282 | 1043:8694 | Intel            | 200 Series PCH SATA controller [A... | 24    | ahci       | [FD39A615DE](<Desktop/ASUSTek Computer/PRIME/PRIME H310M-K R2.0/7D5721B3D945/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD39A615DE>) |
| 8086:1c02 | 1458:b005 | Intel            | 6 Series/C200 Series Chipset Fami... | 23    | ahci       | [33AF90DD93](<Desktop/Gigabyte Technology/H61/H61M-S2V-B3/954969B6DBB2/FREEBSD-13.1/13.1-RELEASE/AMD64/33AF90DD93>) |
| 8086:5ae3 | 1849:5ae3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 23    | ahci       | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 8086:8c02 | 1458:b005 | Intel            | 8 Series/C220 Series Chipset Fami... | 23    | ahci       | [DCA82C50D0](<Desktop/Gigabyte Technology/Z87/Z87X-OC/F384AE9DE012/FREEBSD-13.1-P7/13.1-RELEASE-P3/AMD64/DCA82C50D0>) |
| 1022:43b7 | 1b21:1062 | AMD              | 300 Series Chipset SATA Controller   | 22    | ahci       | [547E5E3CE1](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop PC 570-p0xx/55AF64665E6B/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/547E5E3CE1>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 22    | ahci       | [1F55DB62CC](<Desktop/Others/YL-1900/YL-1900L4-V2/8B6BEEBE711D/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/1F55DB62CC>) |
| 1002:4391 | 1043:84dd | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 21    | ahci       | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 1002:4391 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 21    | ahci       | [29290B1B9C](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2P/EC084C5059C4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/29290B1B9C>) |
| 8086:1e02 | 1458:b005 | Intel            | 7 Series/C210 Series Chipset Fami... | 21    | ahci       | [D8C78B92A7](<Desktop/Gigabyte Technology/H77/H77N-WIFI/4DBEA0F75A7B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D8C78B92A7>) |
| 8086:1c02 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 20    | ahci       | [409D119307](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/36E7C68AA33D/FREEBSD-12.4/12.4-RELEASE/AMD64/409D119307>) |
| 8086:3a22 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 20    | ahci       | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 8086:5ae3 | 8086:5ae3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 20    | ahci       | [16FA0B0102](<Desktop/NF692/1/1.0/9852CE16A74F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16FA0B0102>) |
| 8086:8c02 | 1849:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ahci       | [28E606751F](<Desktop/ASRock/H81/H81M-HDS/255D1BAAA00A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/28E606751F>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ahci       | [AEBF680E82](<Desktop/Axiomtek/IMB/IMB211/47EF00941221/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/AEBF680E82>) |
| 8086:a102 | 1458:b005 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 20    | ahci       | [FB5A559634](<Desktop/Gigabyte Technology/B150/B150-HD3P/7B89078673EA/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/FB5A559634>) |
| 1022:7901 | 1043:87c0 | AMD              | FCH SATA Controller [AHCI mode]      | 19    | ahci       | [9FA1054078](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/EF0D0832952B/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/9FA1054078>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7800 | 1022:7800 | AMD              | FCH SATA Controller [IDE mode]       | 80    | ahci       | [FD6E7FA3AF](<Desktop/PC Engines/APU/APU2/FC8FDE81560C/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/FD6E7FA3AF>) |
| 8086:2850 | 8086:2850 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 40    | atapci     | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 30    | atapci     | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:2828 | 8086:2828 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 29    | atapci     | [866FF788F9](<Desktop/Others/Others/Others/5B265979975E/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/866FF788F9>) |
| 8086:27df | 1043:8179 | Intel            | 82801G (ICH7 Family) IDE Controller  | 27    | atapci     | [29AD0E1044](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/4235E38A16E7/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/29AD0E1044>) |
| 1002:439c | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 26    | atapci     | [B297748CDF](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M PLUS-USB3/88A73B2C8E7E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/B297748CDF>) |
| 8086:27c0 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 24    | atapci     | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:27c0 | 1043:8179 | Intel            | NM10/ICH7 Family SATA Controller ... | 20    | atapci     | [29AD0E1044](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/4235E38A16E7/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/29AD0E1044>) |
| 1002:439c | 1458:5002 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 19    | atapci     | [29290B1B9C](<Desktop/Gigabyte Technology/GA-78/GA-78LMT-S2P/EC084C5059C4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/29290B1B9C>) |
| 1002:439c | 1849:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 16    | atapci     | [461F8CCA23](<Desktop/ASRock/E350/E350M1/DA069FB4F97A/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/461F8CCA23>) |
| 8086:27c0 | 1458:b002 | Intel            | NM10/ICH7 Family SATA Controller ... | 15    | atapci     | [C55B1DD170](<Desktop/Gigabyte Technology/G31/G31M-ES2L/B1A7D0E55D2F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/C55B1DD170>) |
| 1002:4390 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 14    | ahci       | [9AF803F850](<Desktop/ASUSTek Computer/M5A78L-M/M5A78L-M LX3/3E9A6AB48C81/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9AF803F850>) |
| 8086:1c00 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | atapci     | [4BB9A9324B](<Desktop/Dell/OptiPlex/OptiPlex 390/EB6E3143EA5A/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/4BB9A9324B>) |
| 8086:1c08 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | atapci     | [4BB9A9324B](<Desktop/Dell/OptiPlex/OptiPlex 390/EB6E3143EA5A/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/4BB9A9324B>) |
| 8086:1c00 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | atapci     | [76ECD68FF6](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/76ECD68FF6>) |
| 8086:1c08 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | atapci     | [76ECD68FF6](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/76ECD68FF6>) |
| 8086:3a20 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 11    | atapci     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 8086:3a26 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 11    | atapci     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 1002:4390 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 10    | ahci       | [6B63A16799](<Desktop/Gigabyte Technology/GA-MA770/GA-MA770T-UD3/CA4B1CA9726F/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/6B63A16799>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 10    | atapci     | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 8086:27c0 | 1849:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 10    | atapci     | [EACE523F17](<Desktop/ASRock/G41/G41M-GS3/A906B312696E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/EACE523F17>) |
| 8086:27df | 1849:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 10    | atapci     | [EACE523F17](<Desktop/ASRock/G41/G41M-GS3/A906B312696E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/EACE523F17>) |
| 197b:2363 | 1043:824f | JMicron Techn... | JMB363 SATA/IDE Controller           | 9     | atapci     | [DD9685A909](<Desktop/ASUSTek Computer/P7P55D/P7P55D DELUXE/12FEB991B761/FREEBSD-13.1-P6/13.1-RELEASE-P6/AMD64/DD9685A909>) |
| 8086:29b6 | 1028:0211 | Intel            | 82Q35 Express PT IDER Controller     | 9     | atapci     | [03BCC500C0](<Desktop/Dell/OptiPlex/OptiPlex 755/63258707728A/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/03BCC500C0>) |
| 1002:439c | 103c:1609 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 8     | atapci     | [50C8CB79F7](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.4/12.4-RELEASE/AMD64/50C8CB79F7>) |
| 10de:03f6 | 1849:03f6 | Nvidia           | MCP61 SATA Controller                | 8     | atapci     | [04F43C3D70](<Desktop/ASRock/N68-S/N68-S UCC/59DCE7CA2B79/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/04F43C3D70>) |
| 1106:0415 | 1043:838f | VIA Technologies | VT6415 PATA IDE Host Controller      | 8     | atapci     | [3C78171104](<Desktop/ASUSTek Computer/P7/P7H55/A27D3F7702D0/HELLOSYSTEM-0.8.0/13.1-RELEASE-P6/AMD64/3C78171104>) |
| 197b:2363 | 1458:b000 | JMicron Techn... | JMB363 SATA/IDE Controller           | 8     | atapci     | [3EE914E3A0](<Desktop/Gigabyte Technology/GA-890/GA-890FXA-UD5/0D93685E30B3/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/3EE914E3A0>) |
| 8086:1d3c | 103c:1589 | Intel            | C600/X79 series chipset IDE-r Con... | 8     | atapci     | [0696D30D3F](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/0696D30D3F>) |
| 10de:03ec | 1849:03ec | Nvidia           | MCP61 IDE                            | 7     | atapci     | [04F43C3D70](<Desktop/ASRock/N68-S/N68-S UCC/59DCE7CA2B79/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/04F43C3D70>) |
| 8086:27c0 | 1028:0400 | Intel            | NM10/ICH7 Family SATA Controller ... | 7     | atapci     | [42DA900D88](<Desktop/Dell/OptiPlex/OptiPlex 380/C67C08C62EEE/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/42DA900D88>) |
| 8086:27df | 1028:0400 | Intel            | 82801G (ICH7 Family) IDE Controller  | 7     | atapci     | [42DA900D88](<Desktop/Dell/OptiPlex/OptiPlex 380/C67C08C62EEE/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/42DA900D88>) |
| 8086:2920 | 15d9:060a | Intel            | 82801IR/IO/IH (ICH9R/DO/DH) 4 por... | 7     | atapci     | [6A91635684](<Desktop/exone/X7/X7SPA-HF/881B5CC94BD2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6A91635684>) |
| 8086:2926 | 15d9:060a | Intel            | 82801I (ICH9 Family) 2 port SATA ... | 7     | atapci     | [6A91635684](<Desktop/exone/X7/X7SPA-HF/881B5CC94BD2/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/6A91635684>) |
| 1022:7800 | 1458:b002 | AMD              | FCH SATA Controller [IDE mode]       | 6     | ahci       | [DAED3F9401](<Desktop/Gigabyte Technology/F2/F2A68HM-H/3B216ACDFEA8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DAED3F9401>) |
| 11ab:6121 | 1043:8212 | Marvell Techn... | 88SE6111/6121 SATA II / PATA Cont... | 6     | atapci     | [BCD9058821](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/BCD9058821>) |
| 197b:2362 | 1043:8460 | JMicron Techn... | JMB362 SATA Controller               | 6     | ahci       | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 8086:1c00 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | atapci     | [1EC1683ACD](<Desktop/Gigabyte Technology/P61/P61-USB3-B3/CFEE4BCC2A88/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/1EC1683ACD>) |
| 8086:1e00 | 8086:1e00 | Intel            | 7 Series/C210 Series Chipset Fami... | 6     | atapci     | [A469AD62A4](<Desktop/Intel/H67/H67SL_VER1.2A/6298E03FFAD2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A469AD62A4>) |
| 8086:1e08 | 8086:1e08 | Intel            | 7 Series/C210 Series Chipset Fami... | 6     | atapci     | [A469AD62A4](<Desktop/Intel/H67/H67SL_VER1.2A/6298E03FFAD2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A469AD62A4>) |
| 8086:27c0 | 1462:7592 | Intel            | NM10/ICH7 Family SATA Controller ... | 6     | atapci     | [DCE400CB30](<Desktop/MSI/MS/MS-7592/688D31F208BD/OPNSENSE-22.1.8/13.0-STABLE/AMD64/DCE400CB30>) |
| 8086:27c0 | 1b0a:0005 | Intel            | NM10/ICH7 Family SATA Controller ... | 6     | atapci     | [898F645E32](<Desktop/Pegatron/IPM41/IPM41-D3/1AFE69015387/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/898F645E32>) |
| 8086:2e16 | 1028:0276 | Intel            | 4 Series Chipset PT IDER Controller  | 6     | atapci     | [24B9490C77](<Desktop/Dell/OptiPlex/OptiPlex 960/07A3501CD581/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/24B9490C77>) |
| 1002:439c | 1002:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 5     | atapci     | [5D27C08853](<Desktop/AMD/Inagua/Inagua CRB/843D1BB11D3A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/5D27C08853>) |
| 1022:780c | 1458:5002 | AMD              | FCH IDE Controller                   | 5     | atapci     | [4770B980D6](<Desktop/Gigabyte Technology/F2/F2A75M-HD2/9CEA0783B402/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/4770B980D6>) |
| 8086:1c00 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | atapci     | [4B3B7A0929](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/830DACE8E0B6/OPNSENSE-22.1.8/13.0-STABLE/AMD64/4B3B7A0929>) |
| 8086:1c00 | 8086:1c00 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | atapci     | [B2176FAFCF](<Desktop/Intel/MAHOBAY/MAHOBAY/0D48ADEA90BB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2176FAFCF>) |
| 8086:1c08 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | atapci     | [4B3B7A0929](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/830DACE8E0B6/OPNSENSE-22.1.8/13.0-STABLE/AMD64/4B3B7A0929>) |
| 8086:1c08 | 8086:1c08 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | atapci     | [B2176FAFCF](<Desktop/Intel/MAHOBAY/MAHOBAY/0D48ADEA90BB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B2176FAFCF>) |
| 8086:27c0 | 1043:2601 | Intel            | NM10/ICH7 Family SATA Controller ... | 5     | atapci     | [D7C3749EBA](<Desktop/ASUSTek Computer/P5L-VM/P5L-VM 1394/B719CAD52536/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D7C3749EBA>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 140   | nvme       | [EA8759F206](<Desktop/Dell/OptiPlex/OptiPlex 7060/09CD68C8BFFB/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EA8759F206>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 71    | nvme       | [B08FD92E36](<Desktop/MSI/MS-7/MS-7D46/C894FC6BA535/MYBEE-13.2-RC2/13.2-RC2/AMD64/B08FD92E36>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 47    | nvme       | [442643937E](<Desktop/Intel/CW-J6-5L/CW-J6-5L 2C/7DD0D2CA65C5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/442643937E>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 42    | nvme       | [C1886BCD29](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0FC3EEDA5ED5/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/C1886BCD29>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 41    | nvme       | [F45A92348A](<Desktop/Dell/OptiPlex/OptiPlex 3070/AD9E7BA16449/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F45A92348A>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 38    | nvme       | [A0A26F529C](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/BB7614C3933F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A0A26F529C>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 26    | nvme       | [6F8AD1A8B9](<Desktop/Gigabyte Technology/Z490/Z490 VISION G/61A52C9709E8/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/6F8AD1A8B9>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 26    | nvme       | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 24    | nvme       | [F6D1BD5479](<Desktop/Techvision/TVI7309/TVI7309X/859216D2030F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/F6D1BD5479>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 24    | nvme       | [638E327C4E](<Desktop/MSI/CML-U/CML-U PRO Cubi 5/110C3F90DC1E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638E327C4E>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 22    | nvme       | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 22    | nvme       | [8404060D9E](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/AEA0FAD54FAE/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/8404060D9E>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 16    | nvme       | [8EB068A097](<Desktop/ASRock/X570/X570 Taichi/627244F84DF9/FREEBSD-13.1/13.1-RELEASE/AMD64/8EB068A097>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 15    | nvme       | [95C62844DE](<Desktop/Others/Others/Others/722F4261A23A/MYBEE-13.1-P7/13.1-RELEASE-P7/AMD64/95C62844DE>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 13    | nvme       | [054D55B3C1](<Desktop/ASRock/X570S/X570S PG Riptide/CA69BE9A5534/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/054D55B3C1>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 12    | nvme       | [2D9FF025FF](<Desktop/ASRock/B450M/B450M Pro4/8123071B0896/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/2D9FF025FF>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 12    | nvme       | [2588C37FC2](<Desktop/Intel/HM/HM570/5D3A61A4DC00/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/2588C37FC2>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202          | 12    | nvme       | [E09800B936](<Desktop/maiyunda/www.maiyunda.com/www.maiyunda.com/5F223CD2630E/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E09800B936>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 12    | nvme       | [E27931F082](<Desktop/BESSTAR Tech/TH/TH50/1DD7349765D5/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/E27931F082>) |
| 2646:500f | 2646:500f | Kingston Tech... | NVMe Controller                      | 11    | nvme       | [913946CCC9](<Desktop/Others/Others/Others/1C189F0E990E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/913946CCC9>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 10    | nvme       | [D6AB3464C6](<Desktop/Supermicro/SYS-E200/SYS-E200-8D/318BF91088B4/OPNSENSE-21.7.8/12.1-RELEASE-P7-HBSD/AMD64/D6AB3464C6>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 9     | nvme       | [1758C6207C](<Desktop/Techvision/TVI7309/TVI7309X/9E24DE23C8EE/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/1758C6207C>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 8     | nvme       | [4EBEAC2699](<Desktop/ASRock/H570/H570M-ITX-ac/7252CA256A2E/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/4EBEAC2699>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 8     | nvme       | [CB5BB2C3B5](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML310e Gen8/13FA018AB210/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/CB5BB2C3B5>) |
| 15b7:5017 | 15b7:5017 | Sandisk          | NVMe Controller                      | 7     | nvme       | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1c5c:1327 |           | SK hynix         | BC501 NVMe Solid State Drive         | 6     | nvme       | [222DA5A477](<Desktop/Techvision/TVI7309/TVI7309X/432837343A25/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/222DA5A477>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 6     | nvme       | [E4B77410C6](<Desktop/Others/Others/Others/182B4E9CFE0C/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/E4B77410C6>) |
| 10ec:5763 | 10ec:5763 | Realtek Semic... | NVMe Controller                      | 5     | nvme       | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 1179:0116 | 1179:0001 | Toshiba          | XG5 NVMe SSD Controller              | 5     | nvme       | [3E96602A8F](<Desktop/Dell/OptiPlex/OptiPlex 7060/6BC81BE1C8AC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/3E96602A8F>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 5     | nvme       | [1B218204B8](<Desktop/Biostar/H410MH/H410MH S2/01E021A001A5/OPNSENSE-22.1.7/13.0-STABLE/AMD64/1B218204B8>) |
| 1344:5410 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 5     | nvme       | [5AB1DADBAB](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F54ADC493621/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5AB1DADBAB>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 5     | nvme       | [52CC45ABA9](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/28ABD5EC0B9C/GHOSTBSD-22.07.16/13.1-STABLE/AMD64/52CC45ABA9>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4              | 5     | nvme       | [E80C8A40A5](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/EF032CAD06FB/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/E80C8A40A5>) |
| 2646:5019 | 2646:5019 | Kingston Tech... |                                      | 5     | nvme       | [34AFE9E044](<Desktop/Gigabyte Technology/B250/B250M-DS3H/3256005C34E3/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/34AFE9E044>) |
| 8086:2522 | 8086:3806 | Intel            | NVMe Optane Memory Series            | 5     | nvme       | [53C643DC95](<Desktop/CncTion/Jasper-4/Jasper-4L/E64EE31D78D3/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/53C643DC95>) |
| 1179:0115 | 1179:0001 | Toshiba          | XG4 NVMe SSD Controller              | 4     | nvme       | [9805FE9459](<Desktop/Lenovo/V520S-08IKL/V520S-08IKL Desktop 10NNS04A00/0138F543D0DE/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/9805FE9459>) |
| 1344:5405 | 1344:0100 | Micron Techno... | NVMe Storage Controller              | 4     | nvme       | [1AA5CED5A0](<Desktop/ASUSTek Computer/PRIME/PRIME Z590-A/98A2A0675D76/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1AA5CED5A0>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 4     | nvme       | [45D6590312](<Desktop/CncTion/N5105/N5105-4L/05C6F394D27E/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/45D6590312>) |
| 1d97:1160 | 1d97:1160 | Shenzhen Long... | unknown                              | 4     | nvme       | [78BCCCDA01](<Desktop/CncTion/N5105/N5105-4L/667B90399F5F/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/78BCCCDA01>) |
| 1e0f:0009 | 1e0f:0032 | KIOXIA           | NVMe SSD                             | 4     | nvme       | [A3F77B82CC](<Desktop/ASUSTek Computer/PRO/PRO B460M-C/9D195AD59D5D/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/A3F77B82CC>) |
| 2646:5013 | 2646:5013 | Kingston Tech... |                                      | 4     | nvme       | [82AB576C6C](<Desktop/MSI/MS-7/MS-7C91/30A1CCEF9C6D/FREEBSD-13.1/13.1-RELEASE/AMD64/82AB576C6C>) |
| 8086:2522 | 8086:3810 | Intel            | NVMe Optane Memory Series            | 4     | nvme       | [F222AF4098](<Desktop/JGINYUE/H97I/H97I GAMING V1.0/1B791608ADBF/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/F222AF4098>) |
| 10ec:5765 | 10ec:5765 | Realtek Semic... | NVMe Controller                      | 3     | nvme       | [9CD4D2810A](<Desktop/Gigabyte Technology/GA-990X-Gaming/GA-990X-Gaming SLI-CF/4C8CFDE62DD1/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/9CD4D2810A>) |
| 15b7:5019 | 15b7:5019 | SanDisk          | unknown                              | 3     | nvme       | [8AD31CC470](<Desktop/Gigabyte Technology/H510M/H510M H/393AB907B7B8/GHOSTBSD-22.09.16/13.1-STABLE/AMD64/8AD31CC470>) |
| 1c5c:1639 | 1c5c:1639 | SK hynix         | hynix unknown                        | 3     | nvme       | [9478973D4C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M70s 11EX000LGE/DFD126BDDFCE/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/9478973D4C>) |
| 1d97:2263 | 1d97:2263 | Shenzhen Long... | SM2263EN/SM2263XT-based OEM SSD      | 3     | nvme       | [9701222998](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-K/7BD1289ACA54/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/9701222998>) |
| 1d97:5216 | 1dbe:5216 | Shenzhen Long... |                                      | 3     | nvme       | [85628154A2](<Desktop/Gigabyte Technology/H510M/H510M S2H V2/D6902D5FE2E5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/85628154A2>) |
| 1e95:9100 | 126f:2263 | Solid State S... |                                      | 3     | nvme       | [11948A0AB1](<Desktop/CncTion/N5105/N5105-4L/DD5670647EE0/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/11948A0AB1>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 3     | nvme       | [77D3019212](<Desktop/Hardkernel/ODROID-H/ODROID-H2/397877110852/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/77D3019212>) |
| 2646:500a | 2646:500a | Kingston Tech... |                                      | 3     | nvme       | [DF7F4524D7](<Desktop/Others/SKYBAY/SKYBAY/A6E8FBDE5F97/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DF7F4524D7>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2822 | 1028:05a4 | Intel            | SATA Controller [RAID mode]          | 16    | ahci       | [A477C2B046](<Desktop/Dell/OptiPlex/OptiPlex 9020/C840DA9F22BC/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A477C2B046>) |
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 11    | ahci       | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:2822 | 1028:052c | Intel            | SATA Controller [RAID mode]          | 9     | ahci       | [986F18FA08](<Desktop/Dell/OptiPlex/OptiPlex 9010/1A8752C8E9E4/OPNSENSE-22.1.10/13.0-STABLE/AMD64/986F18FA08>) |
| 8086:2822 | 1028:047e | Intel            | SATA Controller [RAID mode]          | 7     | ahci       | [B71ECDF543](<Desktop/Dell/OptiPlex/OptiPlex 990/A3ED196F0551/OPNSENSE-22.1.8/13.0-STABLE/AMD64/B71ECDF543>) |
| 8086:2826 | 103c:1589 | Intel            | C600/X79 series chipset SATA RAID... | 7     | ahci       | [3F9D19B372](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.10/13.0-STABLE/AMD64/3F9D19B372>) |
| 1000:0072 | 1734:1177 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 6     | mps        | [A0A26F529C](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/BB7614C3933F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A0A26F529C>) |
| 8086:2822 | 1458:b005 | Intel            | SATA Controller [RAID mode]          | 6     | ahci       | [8D278732DD](<Desktop/Gigabyte Technology/Z390/Z390 UD/0B8E30771563/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/8D278732DD>) |
| 8086:467f | 1043:8694 | Intel            | Volume Management Device NVMe RAI... | 6     | pcib       | [C3281EB186](<Desktop/ASUSTek Computer/TUF/TUF Gaming Z690-PLUS WIFI D4/967511C3CD54/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/C3281EB186>) |
| 8086:2822 | 1028:07c5 | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [50FBB0435C](<Desktop/Dell/PowerEdge/PowerEdge T30/8C16168DE41F/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/50FBB0435C>) |
| 8086:2822 | 103c:130a | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [A24F08281D](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/A24F08281D>) |
| 8086:2826 | 103c:158a | Intel            | C600/X79 series chipset SATA RAID... | 4     | ahci       | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 3     | ciss       | [FBD2ABDA35](<Desktop/NetGear/ReadyDATA/ReadyDATA 5200/2E63D7AE698C/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBD2ABDA35>) |
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 3     | ciss       | [4E059E9162](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/4E059E9162>) |
| 1095:3114 | 1095:3114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 3     | atapci     | [BBD42243AE](<Desktop/TYAN Computer/Tiger/Tiger K8W Dual AMD Opteron, S2875/A029250D83FC/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/BBD42243AE>) |
| 13c1:1004 | 13c1:1004 | 3ware            | 9650SE SATA-II RAID PCIe             | 3     | twa        | [01898B2FFB](<Desktop/ACMA/X8/X8SIE/EDFA6F8E9EEC/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/01898B2FFB>) |
| 8086:2822 | 1028:0276 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [24B9490C77](<Desktop/Dell/OptiPlex/OptiPlex 960/07A3501CD581/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/24B9490C77>) |
| 8086:2822 | 1028:0620 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [BB86FB3E67](<Desktop/Dell/PowerEdge/PowerEdge T20/C68E45CBB411/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BB86FB3E67>) |
| 8086:2822 | 1028:06ba | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [D06E05C67A](<Desktop/Dell/OptiPlex/OptiPlex 5040/6A6458ACB6C7/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/D06E05C67A>) |
| 8086:2822 | 1028:07a3 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [0D13116822](<Desktop/Dell/OptiPlex/OptiPlex 3050/7C6D11637F94/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D13116822>) |
| 8086:2822 | 1028:085b | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [3A6606E75A](<Desktop/Dell/OptiPlex/OptiPlex 5060/E8B372160376/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3A6606E75A>) |
| 8086:2822 | 103c:8768 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [5AB1DADBAB](<Desktop/Hewlett-Packard/Slim/Slim Desktop S01-pF1xxx/F54ADC493621/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/5AB1DADBAB>) |
| 8086:2822 | 1849:a282 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [803B44339B](<Desktop/ASRock/B250/B250M-HDV/BD56D24CB794/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/803B44339B>) |
| 8086:2826 | 1028:0617 | Intel            | C600/X79 series chipset SATA RAID... | 3     | ahci       | [FFBB7E1A96](<Desktop/Dell/Precision/Precision Tower 5810/6B5E6CCB6269/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/FFBB7E1A96>) |
| 105a:5275 | 1462:1290 | Promise Techn... | PDC20276 (MBFastTrak133 Lite)        | 2     | atapci     | [4AB900BDA7](<Desktop/MSI/MS/MS-9129/FE70FB1F858A/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/4AB900BDA7>) |
| 1095:3112 | 1095:3112 | Silicon Image    | SiI 3112 [SATALink/SATARaid] Seri... | 2     | atapci     | [4AB900BDA7](<Desktop/MSI/MS/MS-9129/FE70FB1F858A/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/4AB900BDA7>) |
| 1095:3114 | 1095:7114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 2     | atapci     | [4C9B877754](<Desktop/Gigabyte Technology/Z77/Z77X-UD3H/1B931DE47D32/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/4C9B877754>) |
| 1095:3124 | 1095:7124 | Silicon Image    | SiI 3124 PCI-X Serial ATA Controller | 2     | siis       | [84F2AFEFF4](<Desktop/Intel/D945GCLF2/D945GCLF2 AAE46416-104/DD320FDAC75E/FREEBSD-13.1/13.1-RELEASE/AMD64/84F2AFEFF4>) |
| 1103:2760 |           | HighPoint Tec... | RocketRAID 2760 SAS Controller       | 2     | hpt27xx    | [378021707A](<Desktop/Gigabyte Technology/990/990FXA-UD3/DEF0CE06BB18/TRUENAS-12.2-P12/12.2-RELEASE-P12/AMD64/378021707A>) |
| 1106:3249 | 1106:3249 | VIA Technologies | VT6421 IDE/SATA Controller           | 2     | atapci     | [5ABCE24217](<Desktop/ASRock/N68C-GS4/N68C-GS4 FX/E2B5288E6A1C/NOMADBSD-1.4-RC1/12.2-RELEASE-P7/AMD64/5ABCE24217>) |
| 8086:2822 | 1028:02da | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [F735EE3C9E](<Desktop/Dell/OptiPlex/OptiPlex 980/093C6BC1C724/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/F735EE3C9E>) |
| 8086:2822 | 1028:0420 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [FCBFBC2DFA](<Desktop/Dell/OptiPlex/OptiPlex 780/1E135D2838C7/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/FCBFBC2DFA>) |
| 8086:2822 | 1028:06b9 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [226F25A086](<Desktop/Dell/OptiPlex/OptiPlex 7040/DD40E35F79F7/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/226F25A086>) |
| 8086:2822 | 1028:085a | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [53FA01007B](<Desktop/Dell/OptiPlex/OptiPlex 7060/DA2700E6778C/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/53FA01007B>) |
| 8086:2822 | 1028:0871 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [290F10C785](<Desktop/Dell/Precision/Precision 3630 Tower/703F414672AD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/290F10C785>) |
| 8086:2822 | 103c:1309 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [3F170BDEE6](<Desktop/Hewlett-Packard/Z400/Z400 Workstation/645388D505B6/GHOSTBSD-22.04.22/13.0-STABLE/AMD64/3F170BDEE6>) |
| 8086:2822 | 103c:130b | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [25B7A10166](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/79ADC3087F2D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/25B7A10166>) |
| 8086:2822 | 103c:1495 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [385D212BBF](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/103902608515/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/385D212BBF>) |
| 8086:2822 | 103c:802e | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [914384FCA0](<Desktop/Hewlett-Packard/Z240/Z240 SFF Workstation/C940FCA75474/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/914384FCA0>) |
| 8086:2822 | 103c:8767 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [9D98B3BAA4](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop TP01-1xxx/316ACA3FC06A/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/9D98B3BAA4>) |
| 8086:2822 | 1043:8534 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [84D7FB3F1E](<Desktop/ASUSTek Computer/All/All Series/46CAE9B0FE93/GHOSTBSD-22.01.28/13.0-STABLE/AMD64/84D7FB3F1E>) |
| 8086:2822 | 1043:8694 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [26375BAE48](<Desktop/ASUSTek Computer/TUF/TUF B360M-E GAMING/1191521842E8/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/26375BAE48>) |
| 8086:2822 | 1458:b000 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 8086:2822 | 8086:2822 | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [21243CAD5F](<Desktop/Others/V0/V0.9x/C0DD4C709478/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/21243CAD5F>) |
| 8086:9a0b | 8086:7270 | Intel            | Volume Management Device NVMe RAI... | 2     | pcib       | [0958A64385](<Desktop/Others/Others/Others/B9869A361E2B/OPNSENSE-22.1.7/13.0-STABLE/AMD64/0958A64385>) |
| 9005:028b | 9005:0200 | Adaptec          | Series 6 - 6G SAS/PCIe 2             | 2     | aacraid    | [238A9E47BF](<Desktop/MSI/MS/MS-7891/AA5249EEE69B/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/238A9E47BF>) |
| 1000:005b | 1000:8081 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mrsas      | [3956AD0525](<Desktop/Cisco Systems/UCSC-C240/UCSC-C240-M3L/39FFEFE18EB4/FREEBSD-13.0/13.0-RELEASE/AMD64/3956AD0525>) |
| 1000:005b | 1000:9266 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mfi        | [E40B569FF7](<Desktop/Supermicro/X7/X7DWE/F929A356E7D3/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/E40B569FF7>) |
| 1000:005b | 1000:9271 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mrsas      | [3956AD0525](<Desktop/Cisco Systems/UCSC-C240/UCSC-C240-M3L/39FFEFE18EB4/FREEBSD-13.0/13.0-RELEASE/AMD64/3956AD0525>) |
| 1000:005b | 1014:040b | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mfi        | [C5D29CC6B3](<Desktop/OEM/B85/B85 JHS359/20D271635E67/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/C5D29CC6B3>) |
| 1000:005d | 1000:9363 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mfi        | [205D6E0194](<Desktop/Wortmann AG/TERRA_SERVER/TERRA_SERVER/4BE5147F2077/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/205D6E0194>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1000:3020 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 16    | mps        | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 8086:1d6b | 103c:1589 | Intel            | C602 chipset 4-Port SATA Storage ... | 10    | isci       | [8A927B43CB](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D768D5739884/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/8A927B43CB>) |
| 1000:0087 | 1000:3020 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 5     | mps        | [CA71C8AB2B](<Desktop/Dell/OptiPlex/OptiPlex 790/987AF9001591/TRUENAS-13.1-P2/13.1-RELEASE-P2/AMD64/CA71C8AB2B>) |
| 8086:1d6b | 103c:158a | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 1000:0072 | 1028:1f1c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 4     | mps        | [AE260E17EB](<Desktop/Dell/Precision/Precision T3600/F63EFF7105B7/FREEBSD-13.1/13.1-RELEASE/AMD64/AE260E17EB>) |
| 1000:0097 | 1000:30e0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 3     | mpr        | [84C360AD02](<Desktop/Supermicro/SSG-5028/SSG-5028R-E1CR12L-CE010/BC525F547480/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/84C360AD02>) |
| 1000:0070 | 1000:3010 | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 2     | mps        | [0EEA35E069](<Desktop/Dell/Precision/Precision WorkStation T3500/2B5473C76A7D/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/0EEA35E069>) |
| 1000:0072 | 1000:0072 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [F7DE46B627](<Desktop/CIARA TECHNOLOGIES/1X8-X6/1X8-X6 CACHEH/CAC8276E190F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/F7DE46B627>) |
| 1000:0072 | 1000:3040 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [37CC045649](<Desktop/Gigabyte Technology/Z68/Z68X-UD7-B3/0B598C0816A1/FREEBSD-13.0-P5/13.0-RELEASE-P5/AMD64/37CC045649>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [DC582EA4D3](<Desktop/ASRock/B550M/B550M Pro4/6D75D10E9FEA/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/DC582EA4D3>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [1DB4784753](<Desktop/Supermicro/SSG-6029/SSG-6029P-E1CR12L/A25F2BC1A98D/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/1DB4784753>) |
| 1000:0097 | 1849:0097 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [C04BBD635B](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/6457E123E761/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/C04BBD635B>) |
| 8086:1d6b | 1028:0497 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [C8993DCCA5](<Desktop/Dell/Precision/Precision T3600/1BDA06E274A1/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/C8993DCCA5>) |
| 8086:1d6b | 15d9:0628 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [B8C89BDCA8](<Desktop/Supermicro/X9/X9DR3-F/3573CEE1CD7B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8C89BDCA8>) |
| 8086:1d6b | 17aa:1026 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [1EC71F814B](<Desktop/Lenovo/ThinkStation/ThinkStation S30 43511K5/E8B0027862B5/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1EC71F814B>) |
| 1000:005d | 15d9:0a09 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [B44FE94131](<Desktop/Supermicro/SSG-2028/SSG-2028R-E1CR24N/201BEB766364/FREENAS-11.3-P9/11.3-RELEASE-P9/AMD64/B44FE94131>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mps        | [4DCA0D2AA4](<Desktop/ASUSTek Computer/All/All Series/0AB137A413F8/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/4DCA0D2AA4>) |
| 1000:0072 | 1000:3050 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [28FDD2C2DC](<Desktop/Supermicro/X9/X9SCL-X9SCM/70812EDDCEB0/FREENAS-11.2-STABLE/11.2-STABLE/AMD64/28FDD2C2DC>) |
| 1000:0072 | 1000:30f0 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [90C27497D9](<Desktop/ASUSTek Computer/Crosshair/Crosshair V Formula/08D4551A4F47/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/90C27497D9>) |
| 1000:0072 | 1028:1f1d | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [05D3AB8D4B](<Desktop/ASRock/B360/B360 Pro4/68A525A70C29/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/05D3AB8D4B>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [FBD2ABDA35](<Desktop/NetGear/ReadyDATA/ReadyDATA 5200/2E63D7AE698C/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBD2ABDA35>) |
| 1000:0086 | 103c:158b | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [EA62F49750](<Desktop/Supermicro/X9/X9DRD-7LN4F/97D90A6AA706/TRUENAS-12.2-P10/12.2-RELEASE-P10/AMD64/EA62F49750>) |
| 1000:0097 | 1028:0619 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [DDDF168DB9](<Desktop/Dell/Precision/Precision Tower 7910/9E71C365962A/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/DDDF168DB9>) |
| 1000:00ac | 1000:3000 | Broadcom / LSI   | SAS3416 Fusion-MPT Tri-Mode I/O C... | 1     | mpr        | [23196AA66B](<Desktop/ASRock/Z390/Z390M-ITX-ac/40E52D5C50CF/FREEBSD-12.2-P5/12.2-RELEASE-P4/AMD64/23196AA66B>) |
| 8086:1d60 | 1028:0496 | Intel            | C608 chipset Dual 4-Port SATA/SAS... | 1     | isci       | [D9D86D5BFD](<Desktop/Dell/Precision/Precision T5600/ADD168454A3E/GHOSTBSD-22.04.06/13.0-STABLE/AMD64/D9D86D5BFD>) |
| 8086:1d60 | 1028:0497 | Intel            | C608 chipset Dual 4-Port SATA/SAS... | 1     | isci       | [B6044FB84C](<Desktop/ASRock/G41/G41M-VS3/F606D604CBAF/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/B6044FB84C>) |
| 8086:1d69 | 17aa:1026 | Intel            | C604/X79 series chipset 4-Port SA... | 1     | isci       | [DD545FB588](<Desktop/Lenovo/ThinkStation/ThinkStation S30 0569A93/3A5A3AB166EF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DD545FB588>) |
| 8086:1d6b | 103c:158b | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 8086:1d6b | 15d9:0635 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [EF1F3DA3CE](<Desktop/Supermicro/X9/X9DAL/0410EAD24B29/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/EF1F3DA3CE>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [0F3EE4CAAB](<Desktop/Fujitsu/CELSIUS/CELSIUS M720/7B5122D4B3E4/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/0F3EE4CAAB>) |
| 9005:028f | 103c:0651 | Adaptec          | Smart Storage PQI SAS                | 1     | smartpqi   | [F1B45790D4](<Desktop/HPE/ProLiant/ProLiant ML30 Gen10/93F91BA1C4A9/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/F1B45790D4>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1425:4501 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 5     |            | [6905821659](<Desktop/ASRock/X99/X99 Extreme4/3BEC2E139880/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/6905821659>) |
| 1425:5501 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 5     |            | [2AC306B67F](<Desktop/Dell/OptiPlex/OptiPlex 5050/E3ED1B71BC40/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2AC306B67F>) |
| 17d3:1300 | 17d3:1300 | Areca Technology | ARC-1300ix-16 16-Port PCI-Express... | 4     | arcsas     | [66BBED8D59](<Desktop/ASUSTek Computer/P6T/P6T SE/9C422F2B290E/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/66BBED8D59>) |
| 9004:8178 |           | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 4     | ahc        | [459C674B3B](<Desktop/ASRock/Z77/Z77 Extreme4/4A8FC6177080/FREEBSD-12.3/12.3-RELEASE/AMD64/459C674B3B>) |
| 1425:5503 |           | Chelsio Commu... | T540-CR Unified Wire Storage Cont... | 3     |            | [21E7190FF2](<Desktop/Supermicro/AS/AS -5019D-FTN4/86486880485E/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/21E7190FF2>) |
| 1000:0058 | 1028:1f0e | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mpt        | [B4234170E8](<Desktop/ASUSTek Computer/P5Q/P5Q DELUXE/E1D558665C0F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B4234170E8>) |
| 1000:0058 | 103c:130b | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mpt        | [25B7A10166](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/79ADC3087F2D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/25B7A10166>) |
| 1425:5507 |           | Chelsio Commu... | T520-SO Unified Wire Storage Cont... | 2     |            | [A0A26F529C](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/BB7614C3933F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/A0A26F529C>) |
| 1425:6508 |           | Chelsio Commu... | T62100-SO-CR Unified Wire Storage... | 2     |            | [D120C268F7](<Desktop/Supermicro/SYS-6028/SYS-6028R-T/789334D78445/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/D120C268F7>) |
| 5853:0001 | 5853:0001 | XenSource        | Xen Platform Device                  | 2     | xenpci     | [FFB1FD95D3](<Desktop/PC Engines/apu/apu4/8CB6C93947A1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/FFB1FD95D3>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 2     | ahc        | [C67CCF8BC6](<Desktop/Dell/Inspiron/Inspiron 530/3762C968ACCD/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C67CCF8BC6>) |
| 1000:0001 | 1000:1000 | Broadcom / LSI   | 53c810                               | 1     | sym        | [4EE625240F](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VII HERO/37724E1F8F3B/FREEBSD-12.1-STABLE/12.1-STABLE-20200612/AMD64/4EE625240F>) |
| 1000:000f | 1000:1000 | Broadcom / LSI   | 53c875                               | 1     | sym        | [DAE16641BB](<Desktop/ASUSTek Computer/M2/M2NPV-MX/14DC624B8825/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/DAE16641BB>) |
| 1000:0030 | 103c:322a | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [2F26C69137](<Desktop/Dell/OptiPlex/OptiPlex 390/A5CC20B80AD3/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/2F26C69137>) |
| 1000:0054 | 103c:0a98 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mpt        | [655FC531FB](<Desktop/Hewlett-Packard/xw8600/xw8600 Workstation/0566D4E23583/OPNSENSE-22.1.9/13.0-STABLE/AMD64/655FC531FB>) |
| 1000:0056 | 1000:1000 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [7B2DE50C60](<Desktop/Apple/Xserve3/Xserve3,1/D499BA477C7F/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/7B2DE50C60>) |
| 1000:0056 | 1734:1131 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [FF2213E848](<Desktop/Fujitsu/CELSIUS/CELSIUS M470-2/50E1DC1E3DE9/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/FF2213E848>) |
| 1000:0058 | 15d9:a480 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [27FC294BCA](<Desktop/Supermicro/X7/X7DCL/3D21E845B8F9/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/27FC294BCA>) |
| 1000:0058 | 17aa:101d | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [526E5EEA0B](<Desktop/Lenovo/ThinkStation/ThinkStation D10 6493WEU/6A717F675FF7/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/526E5EEA0B>) |
| 1000:0059 | 15d9:0004 | Broadcom / LSI   | MegaRAID SAS 8208ELP/8208ELP         | 1     | mpt        | [7D0E121099](<Desktop/Supermicro/X8/X8STi/00B85E5857AF/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/7D0E121099>) |
| 1103:2300 | 11ab:11ab | HighPoint Tec... | RocketRAID 230x 4 Port SATA-II Co... | 1     | hptrr      | [AA29EB9C75](<Desktop/Gigabyte Technology/H67/H67A-UD3H-B3/48803C404D01/GHOSTBSD-20.04.02/12.1-STABLE/AMD64/AA29EB9C75>) |
| 1425:4502 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Storage Cont... | 1     |            | [BD9D4BB7A3](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/10EF43C278BD/OPNSENSE-22.1.4/13.0-STABLE/AMD64/BD9D4BB7A3>) |
| 1425:5511 |           | Chelsio Commu... | T520-LL-CR Unified Wire Storage C... | 1     |            | [3A61EB7BAE](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite CMT PC/C55069592DD2/OPNSENSE-22.1.9/13.0-STABLE/AMD64/3A61EB7BAE>) |
| 1425:5583 |           | Chelsio Commu... | T540-5083 Unified Wire Storage Co... | 1     |            | [55E9734C09](<Desktop/JGINYUE/B85I/B85I PLUS V1.0/C745913DBF54/OPNSENSE-22.1.6/13.0-STABLE/AMD64/55E9734C09>) |
| 1425:5584 |           | Chelsio Commu... | T540-5084 Unified Wire Storage Co... | 1     |            | [2BBA0377AE](<Desktop/MSI/MS/MS-7733/A84A1CCB8340/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/2BBA0377AE>) |
| 1425:6503 |           | Chelsio Commu... | T6425-CR Unified Wire Storage Con... | 1     |            | [17A763A917](<Desktop/MSI/MS-7/MS-7B24/D5C8F44D7DED/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/17A763A917>) |
| 9004:3860 | 9004:3869 | Adaptec          | AHA-2930CU                           | 1     | ahc        | [C7D877A988](<Desktop/Supermicro/X7/X7SBL/725A0E7344D4/FREEBSD-12.3/12.3-RELEASE/AMD64/C7D877A988>) |
| 9004:5078 |           | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 1     | ahc        | [1BC05B5951](<Desktop/Dell/Precision/Precision WorkStation T3400/ADEEA3484D9F/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1BC05B5951>) |
| 9004:8178 | 9004:7881 | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 1     | ahc        | [75E86A92F7](<Desktop/ASUSTek Computer/All/All Series/07E6A3D81A80/FREEBSD-12.2-P1/12.2-RELEASE-P1/AMD64/75E86A92F7>) |
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 1     | ahd        | [EB73C9D13D](<Desktop/Supermicro/X9/X9DAi/558BB9BB7FC9/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/EB73C9D13D>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1567 | 1022:1567 | AMD              | Mullins IOMMU                        | 166   |            | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 130   |            | [486646710B](<Desktop/Others/Others/Others/6B1DED8023A3/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/486646710B>) |
| 1022:1481 | 1022:1481 | AMD              | Starship/Matisse IOMMU               | 63    | amdiommu   | [8EB068A097](<Desktop/ASRock/X570/X570 Taichi/627244F84DF9/FREEBSD-13.1/13.1-RELEASE/AMD64/8EB068A097>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 59    | amdiommu   | [CA70BCEB83](<Desktop/ASUSTek Computer/PRIME/PRIME A320M-E/964B28FB1DE0/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CA70BCEB83>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 56    | amdiommu   | [D675A5BAB2](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/D675A5BAB2>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 53    |            | [2A55137E71](<Desktop/Others/Others/Others/E5E4D871BE14/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/2A55137E71>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 47    |            | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 47    |            | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 1022:1481 | 1043:87c0 | AMD              | Starship/Matisse IOMMU               | 42    | amdiommu   | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:2f88 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 40    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f8a |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 VCU    | 40    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fae |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 40    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2faf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 40    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fbe |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 40    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fbf |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 40    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2ff8 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Buf... | 40    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2ff9 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Buf... | 40    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f6e |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 38    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f6f |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 38    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fb8 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 38    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fb9 |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 38    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fba |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 38    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fbb |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 38    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 37    |            | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 8086:3438 |           | Intel            | 7500/5520/5500/X58 I/O Hub Thrott... | 34    |            | [37E1562772](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH X58/48051B2A112E/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/37E1562772>) |
| 1022:1451 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 33    |            | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 103c:3306 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Sl... | 32    |            | [409D119307](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/36E7C68AA33D/FREEBSD-12.4/12.4-RELEASE/AMD64/409D119307>) |
| 103c:3307 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Ma... | 32    |            | [409D119307](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/36E7C68AA33D/FREEBSD-12.4/12.4-RELEASE/AMD64/409D119307>) |
| 8086:2fbc |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 32    |            | [58090B9DBF](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/8550845C82E4/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/58090B9DBF>) |
| 8086:2fbd |           | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 DDR... | 32    |            | [58090B9DBF](<Desktop/Huanan/X99-QD4/X99-QD4 V1.0/8550845C82E4/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/58090B9DBF>) |
| 8086:2018 |           | Intel            | Sky Lake-E M2PCI Registers           | 29    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 8086:2f1d | 8086:2f1d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f1e | 8086:2f1e | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f1f | 8086:2f1f | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f71 | 8086:2f71 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f98 | 8086:2f98 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f99 | 8086:2f99 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f9a | 8086:2f9a | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2f9c | 8086:2f9c | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fa0 | 8086:2fa0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fa8 | 8086:2fa8 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2faa | 8086:2faa | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fab | 8086:2fab | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fb0 | 8086:2fb0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fb1 | 8086:2fb1 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fb2 | 8086:2fb2 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fb3 | 8086:2fb3 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Int... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2fc0 | 8086:2fc0 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Pow... | 29    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:2025 |           | Intel            | Sky Lake-E RAS                       | 28    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |
| 8086:2035 |           | Intel            | Sky Lake-E RAS Configuration Regi... | 28    |            | [0CEBC094CA](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/0CEBC094CA>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7808 | 1022:7808 | AMD              | FCH USB EHCI Controller              | 264   | ehci       | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 1022:7814 | 1022:1410 | AMD              | FCH USB XHCI Controller              | 252   | xhci       | [C8008161B0](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/C8008161B0>) |
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 239   | xhci       | [82759EFF54](<Desktop/Others/Others/Others/0D6CEE283756/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/82759EFF54>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 212   | xhci       | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 178   | xhci       | [98F6C8F34B](<Desktop/Protectli/FW4/FW4B/B25C41355D12/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/98F6C8F34B>) |
| 8086:4ded | 8086:7270 | Intel            | Jasper Lake USB 3.1 XHCI Host Con... | 147   | xhci       | [83FA5B5A27](<Desktop/Others/Others/Others/7B7F81AC1DFE/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/83FA5B5A27>) |
| 1022:149c | 1022:148c | AMD              | Matisse USB 3.0 Host Controller      | 105   | xhci       | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:43d5 | 1b21:1142 | AMD              | 400 Series Chipset USB 3.1 xHCI C... | 98    | xhci       | [85AECF8C3F](<Desktop/MSI/MS-7/MS-7A38/2325A856795F/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/85AECF8C3F>) |
| 1022:7808 | 1734:1202 | AMD              | FCH USB EHCI Controller              | 74    | ehci       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 73    | xhci       | [52CDEB023E](<Desktop/AMI/MNHO/MNHO-048/DA0DE8A52BA6/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/52CDEB023E>) |
| 1022:7814 | 1734:1202 | AMD              | FCH USB XHCI Controller              | 70    | xhci       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 69    | ehci       | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 8086:9ca6 | 8086:7270 | Intel            | Wildcat Point-LP USB EHCI Controller | 68    | ehci       | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 1002:4397 | 1002:4397 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 66    | ohci       | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 1022:149c | 1022:1486 | AMD              | Matisse USB 3.0 Host Controller      | 66    | xhci       | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 8086:9cb1 | 8086:7270 | Intel            | Wildcat Point-LP USB xHCI Controller | 65    | xhci       | [639886B591](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B2D974E7849B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/639886B591>) |
| 1002:4399 | 1002:4399 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 58    | ohci       | [C8ABF1F5BF](<Desktop/ASUSTek Computer/M5A97/M5A97 LE R2.0/CC460235E058/FREEBSD-13.1-P7/13.1-RELEASE/AMD64/C8ABF1F5BF>) |
| 1022:149c | 1043:87c0 | AMD              | Matisse USB 3.0 Host Controller      | 57    | xhci       | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:9c26 | 8086:7270 | Intel            | 8 Series USB EHCI #1                 | 55    | ehci       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 55    | xhci       | [3C5F826544](<Desktop/Intel/CRESCENTBAY/CRESCENTBAY/574B8D8CFA38/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/3C5F826544>) |
| 1022:43ee | 1b21:1142 | AMD              | 500 Series Chipset USB 3.1 XHCI C... | 54    | xhci       | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 1022:7807 | 103c:213d | AMD              | FCH USB OHCI Controller              | 51    | ohci       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:7808 | 103c:213d | AMD              | FCH USB EHCI Controller              | 51    | ehci       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1022:7814 | 103c:213d | AMD              | FCH USB XHCI Controller              | 51    | xhci       | [DEA507EBE0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/2691FA941D87/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/DEA507EBE0>) |
| 1b21:1042 | 1043:8488 | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 46    | xhci       | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 1022:7807 | 1734:1202 | AMD              | FCH USB OHCI Controller              | 43    | ohci       | [E8204EFCA6](<Desktop/Fujitsu/FUTRO/FUTRO S920/582E158CFA66/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/E8204EFCA6>) |
| 8086:2830 | 8086:2830 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 42    | uhci       | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:2836 | 8086:2836 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 42    | ehci       | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:8c26 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | ehci       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c26 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | ehci       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:8c2d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | ehci       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c2d | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | ehci       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:8c31 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | xhci       | [AC0118B05E](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AC0118B05E>) |
| 8086:8c31 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 42    | xhci       | [38AF3096A6](<Desktop/Dell/OptiPlex/OptiPlex 3020/422496C48BF5/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/38AF3096A6>) |
| 8086:2831 | 8086:2831 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 41    | uhci       | [E8A2206AD2](<Desktop/Stonesoft/FW-315/FW-315-C1/773B06736C0B/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/E8A2206AD2>) |
| 8086:27c8 | 8086:27c8 | Intel            | NM10/ICH7 Family USB UHCI Control... | 40    | uhci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:27c9 | 8086:27c9 | Intel            | NM10/ICH7 Family USB UHCI Control... | 39    | uhci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:27cc | 8086:27cc | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 38    | ehci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:8c26 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 38    | ehci       | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:a12f | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 38    | xhci       | [8736B12C9A](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/8736B12C9A>) |
| 1022:43bc | 1b21:1142 | AMD              | A320 USB 3.1 XHCI Host Controller    | 37    | xhci       | [593F6FF02D](<Desktop/MSI/MS-7/MS-7C51/435F418C7DE2/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/593F6FF02D>) |
| 8086:1c26 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | ehci       | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:1c2d | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | ehci       | [3D8EF63E18](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/3D8EF63E18>) |
| 8086:8c2d | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 37    | ehci       | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:8c31 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 37    | xhci       | [B9166D8134](<Desktop/ASUSTek Computer/K30/K30AD_M31AD_M51AD/8FD3FBA66C15/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/B9166D8134>) |
| 8086:27ca | 8086:27ca | Intel            | NM10/ICH7 Family USB UHCI Control... | 36    | uhci       | [815CD70E71](<Desktop/Others/Others/Others/90F085143625/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/815CD70E71>) |
| 8086:1c26 | 1458:5006 | Intel            | 6 Series/C200 Series Chipset Fami... | 35    | ehci       | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 8086:1c2d | 1458:5006 | Intel            | 6 Series/C200 Series Chipset Fami... | 35    | ehci       | [B42E3649A3](<Desktop/ITMediaConsult/Pentino/Pentino Mini/BE04B6AE4F14/GHOSTBSD-23.02.02/13.1-STABLE/AMD64/B42E3649A3>) |
| 8086:2832 | 8086:2832 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 35    | uhci       | [866FF788F9](<Desktop/Others/Others/Others/5B265979975E/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/866FF788F9>) |
| 8086:1e26 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family USB ... | 34    | ehci       | [72D45455A5](<Desktop/Dell/OptiPlex/OptiPlex 7010/DFDBA5E1859E/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/72D45455A5>) |

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

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 108   |            | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 87    |            | [FBFF29A62A](<Desktop/ASRock/X470/X470 Gaming K4/FFA88723BDD5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/FBFF29A62A>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 79    |            | [D675A5BAB2](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/D675A5BAB2>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 79    |            | [D675A5BAB2](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/D675A5BAB2>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 42    |            | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 42    |            | [D93AE717CC](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/D93AE717CC>) |
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 36    |            | [AD6F854637](<Desktop/MW/GMLK-2/GMLK-2_5G4L/74BD25C36E56/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/AD6F854637>) |
| 1022:1455 | 1043:8747 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 27    |            | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 1022:145a | 1043:8747 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 27    |            | [B3F41E1CB4](<Desktop/ASUSTek Computer/PRIME/PRIME X370-PRO/69AAAA30BEFA/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B3F41E1CB4>) |
| 0000:0000 |           |                  | Device                               | 17    |            | [F5ACB2D032](<Desktop/Acer/Veriton/Veriton X2120G/4BA6B6BAA584/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/F5ACB2D032>) |
| 1022:1485 | 1043:8808 | AMD              | Starship/Matisse Reserved SPP        | 16    |            | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 1022:148a | 1043:8808 | AMD              | Starship/Matisse PCIe Dummy Function | 16    |            | [37EE7B4F47](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/846C1320086A/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/37EE7B4F47>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 13    |            | [B7E599F99D](<Desktop/BESSTAR Tech/UM/UM350/13DA4A6E533F/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/B7E599F99D>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 12    |            | [EC7A5F05FD](<Desktop/CheckPoint/PH-30/PH-30-00/006D640A4E82/OPNSENSE-23.1.2/13.1-RELEASE-P7/AMD64/EC7A5F05FD>) |
| 8086:a1ec | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 0    | 12    |            | [D0BF3EB35D](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/5565DD11099D/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/D0BF3EB35D>) |
| 8086:a1ed | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 1    | 9     |            | [2CBA6FBBB7](<Desktop/Supermicro/SYS-5019/SYS-5019D-FN8TP-2-NC041/F87B609ACF03/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/2CBA6FBBB7>) |
| 8086:8d7c | 1043:8600 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [006553F965](<Desktop/ASUSTek Computer/All/All Series/5FA8341B7ABC/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/006553F965>) |
| 1022:145a | 1002:15dd | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 6     |            | [38D7F55EF7](<Desktop/ASRockRack/X470/X470D4U/8404FC50C36B/FREEBSD-12.3-P8/12.3-RELEASE-P6/AMD64/38D7F55EF7>) |
| 8086:8d7c | 1028:0617 | Intel            | C610/X99 series chipset SPSR         | 6     |            | [FFBB7E1A96](<Desktop/Dell/Precision/Precision Tower 5810/6B5E6CCB6269/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/FFBB7E1A96>) |
| 8086:8d7c | 103c:212b | Intel            | C610/X99 series chipset SPSR         | 6     |            | [185934706D](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/5A7566F8C0EA/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/185934706D>) |
| 1022:1485 | 1462:7c02 | AMD              | Starship/Matisse Reserved SPP        | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 1022:148a | 1462:7c02 | AMD              | Starship/Matisse PCIe Dummy Function | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 8086:8d7c | 1849:8d7c | Intel            | C610/X99 series chipset SPSR         | 5     |            | [30A582FCCB](<Desktop/ASRockRack/EP2/EP2C612D16FM/194ABDFCA96A/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/30A582FCCB>) |
| 1022:15e6 | 1849:15e6 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 4     |            | [F0582D78BF](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-23.1.3/13.1-RELEASE-P7/AMD64/F0582D78BF>) |
| 8086:5aa2 | 8086:5aa2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     |            | [16FA0B0102](<Desktop/NF692/1/1.0/9852CE16A74F/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16FA0B0102>) |
| 1022:1455 | 1462:7b86 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:145a | 1002:15d8 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [127E0126D1](<Desktop/ASRock/B450/B450 Gaming K4/ED84CEC3B15B/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/127E0126D1>) |
| 1022:145a | 1458:d000 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [13E4D3CE10](<Desktop/Gigabyte Technology/X570/X570 UD/4EC4B3A73B66/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/13E4D3CE10>) |
| 1022:145a | 1462:7b86 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 15ec:5000 | 15ec:5000 | Beckhoff         |                                      | 3     |            | [6DB720018B](<Desktop/Beckhoff Automation/CBxx/CBxx63/D2340951707E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6DB720018B>) |
| 8086:8d7c | 15d9:0844 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [1FFD63A929](<Desktop/Supermicro/PIO-618/PIO-618U-T4T+-ST031/E62C2994F73D/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1FFD63A929>) |
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [5070C11C54](<Desktop/Dell/VEP-4600/VEP-4600-V910/BAE5F41CA0D2/OPNSENSE-23.1.1/13.1-RELEASE-P6/AMD64/5070C11C54>) |
| 1022:1455 | 1462:7b89 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 2     |            | [8B3A234691](<Desktop/MSI/MS-7/MS-7B89/C8A1522450C9/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/8B3A234691>) |
| 1022:145a | 1043:876b | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [92EAB8D065](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING II/1AD27D04291F/HELLOSYSTEM-0.7.0/13.1-RELEASE-P3/AMD64/92EAB8D065>) |
| 1022:145a | 1043:8809 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [335C3C990A](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/0FA0882C4877/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/335C3C990A>) |
| 1022:145a | 1462:7a38 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [54E4202BC7](<Desktop/MSI/MS-7/MS-7A38/DB12760FCE4D/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/54E4202BC7>) |
| 1022:145a | 1462:7b89 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 2     |            | [8B3A234691](<Desktop/MSI/MS-7/MS-7B89/C8A1522450C9/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/8B3A234691>) |
| 1022:1485 | 1043:87cb | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:1485 | 1043:8809 | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [232A81D2ED](<Desktop/ASUSTek Computer/PRIME/PRIME X570-P/2E6510A36D4C/OPNSENSE-22.10/13.1-RELEASE-P5/AMD64/232A81D2ED>) |
| 1022:1485 | 1462:7b86 | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 1022:1485 | 1462:7c95 | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 1022:148a | 1043:87cb | AMD              | Starship/Matisse PCIe Dummy Function | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:148a | 1462:7b86 | AMD              | Starship/Matisse PCIe Dummy Function | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 1022:148a | 1462:7c95 | AMD              | Starship/Matisse PCIe Dummy Function | 2     |            | [EDEDC04017](<Desktop/MSI/MS-7/MS-7C95/ED8AECDC8540/HELLOSYSTEM-0.8.1/13.1-RELEASE/AMD64/EDEDC04017>) |
| 8086:8d7c | 1458:7270 | Intel            | C610/X99 series chipset SPSR         | 2     |            | [DE5BF4B420](<Desktop/Gigabyte Technology/X99-Designare/X99-Designare EX-CF/DEC9F2C04D03/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/DE5BF4B420>) |
| 8086:8d7c | 1462:7885 | Intel            | C610/X99 series chipset SPSR         | 2     |            | [BA0AC00CF6](<Desktop/MSI/MS/MS-7885/A9957445CE5D/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/BA0AC00CF6>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [EBB920C0C4](<Desktop/Supermicro/SYS-5019/SYS-5019S-ML/9095F638CA6D/FREEBSD-12.1-P9/12.1-RELEASE-P9/AMD64/EBB920C0C4>) |
| 8086:a1ec | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 0    | 2     |            | [1DB4784753](<Desktop/Supermicro/SSG-6029/SSG-6029P-E1CR12L/A25F2BC1A98D/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/1DB4784753>) |
| 8086:a1ec | 15d9:1b35 | Intel            | C620 Series Chipset Family MROM 0    | 2     |            | [84A08C6936](<Desktop/Supermicro/SYS-1019/SYS-1019D-4C-FHN13TP/423D360F9B47/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/84A08C6936>) |
| 8086:a1ed | 15d9:0981 | Intel            | C620 Series Chipset Family MROM 1    | 2     |            | [1DB4784753](<Desktop/Supermicro/SSG-6029/SSG-6029P-E1CR12L/A25F2BC1A98D/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/1DB4784753>) |

