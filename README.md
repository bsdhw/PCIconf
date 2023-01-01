Most popular PCI devices
========================

This is a project to identify most popular PCI devices in modern computers and
share detailed pciconf reports collected by BSD users at https://bsd-hardware.info.

Everyone can contribute to this repository by uploading probes of their computers
by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Total reports: 13055.

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
| 1814:3298 | 103c:18ec | Ralink           | RT3290 Bluetooth                     | 7     |            | [7596B602C6](<Notebook/Hewlett-Packard/ProBook/ProBook 4540s/FDCC764F85D2/FREEBSD-13.1/13.1-RELEASE/AMD64/7596B602C6>) |

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1439 | 1022:1234 | AMD              | Family 16h Processor Functions 5:1   | 394   | pcib       | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:1452 |           | AMD              | Family 17h (Models 00h-1fh) PCIe ... | 308   | hostb      | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 1022:156b |           | AMD              | Family 16h (Models 30h-3fh) Host ... | 284   | hostb      | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:1580 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 284   | hostb      | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:1581 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 284   | hostb      | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:1582 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 284   | hostb      | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:1583 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 284   | hostb      | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:1584 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 284   | hostb      | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:1585 |           | AMD              | Family 16h (Models 30h-3fh) Proce... | 284   | hostb      | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:780e | 1022:780e | AMD              | FCH LPC Bridge                       | 276   | isab       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 1022:1566 | 1022:1566 | AMD              | Family 16h (Models 30h-3fh) Proce... | 246   | hostb      | [7AAF2D91BA](<Desktop/PC Engines/APU/APU2/5DC664E10D36/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7AAF2D91BA>) |
| 8086:9d13 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 237   | pcib       | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:9d14 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 233   | pcib       | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:9d12 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 232   | pcib       | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 1002:4384 |           | AMD              | SBx00 PCI to PCI Bridge              | 225   | pcib       | [50C8CB79F7](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.4/12.4-RELEASE/AMD64/50C8CB79F7>) |
| 8086:9d10 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 222   | pcib       | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:9d11 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 218   | pcib       | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:31f0 |           | Intel            | Gemini Lake Host Bridge              | 217   | hostb      | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:9d15 | 8086:7270 | Intel            | Sunrise Point-LP PCI Express Root... | 217   | pcib       | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 213   | isab       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 210   | isab       | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 209   | pcib       | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 208   | hostb      | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 8086:22ca | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 200   | pcib       | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 111d:8018 |           | Microsemi / P... | PES12N3A 12-lane 3-Port PCI Expre... | 195   | pcib       | [E23F822438](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-F GAMING WIFI/83B0E22D5F39/OPNSENSE-22.1.10/13.0-STABLE/AMD64/E23F822438>) |
| 8086:31d8 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 195   | pcib       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 180   | isab       | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 8086:0f48 | 8086:0f48 | Intel            | Atom Processor E3800 Series PCI E... | 179   | pcib       | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 8086:0f4a | 8086:0f4a | Intel            | Atom Processor E3800 Series PCI E... | 179   | pcib       | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 8086:0f4c | 8086:0f4c | Intel            | Atom Processor E3800 Series PCI E... | 177   | pcib       | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 8086:0f4e | 8086:0f4e | Intel            | Atom Processor E3800 Series PCI E... | 176   | pcib       | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 8086:22cc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 174   | pcib       | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 169   | pcib       | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 169   | pcib       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:31d9 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 168   | pcib       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:22ce | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 165   | pcib       | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 1022:15e8 |           | AMD              | Raven/Raven2 Device 24: Function 0   | 162   | hostb      | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:15e9 |           | AMD              | Raven/Raven2 Device 24: Function 1   | 162   | hostb      | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:15ea |           | AMD              | Raven/Raven2 Device 24: Function 2   | 162   | hostb      | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:15eb |           | AMD              | Raven/Raven2 Device 24: Function 3   | 162   | hostb      | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:15ec |           | AMD              | Raven/Raven2 Device 24: Function 4   | 162   | hostb      | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:15ed |           | AMD              | Raven/Raven2 Device 24: Function 5   | 162   | hostb      | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:15ee |           | AMD              | Raven/Raven2 Device 24: Function 6   | 162   | hostb      | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:15ef |           | AMD              | Raven/Raven2 Device 24: Function 7   | 162   | hostb      | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 8086:5904 | 8086:2015 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 158   | hostb      | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 1022:1482 |           | AMD              | Starship/Matisse PCIe Dummy Host ... | 156   | hostb      | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 8086:0f00 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 155   | hostb      | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 8086:31d6 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 150   | pcib       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:31d7 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 147   | pcib       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 1022:1460 |           | AMD              | Family 17h (Models 00h-0fh) Data ... | 146   | hostb      | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5227 | 17aa:2226 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 14    | rtsx       | [10619AC217](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLS5BU00/75926791E302/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/10619AC217>) |
| 10ec:522a | 10ec:522a | Realtek Semic... | RTS522A PCI Express Card Reader      | 12    | rtsx       | [1B938AA1A4](<Desktop/Shuttle/DH/DH370/7C934F0402CA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/1B938AA1A4>) |
| 10ec:522a | 17aa:5062 | Realtek Semic... | RTS522A PCI Express Card Reader      | 12    | rtsx       | [8257D11669](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S0PY04/60067DC63CDD/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/8257D11669>) |
| 10ec:5227 | 17aa:220e | Realtek Semic... | RTS5227 PCI Express Card Reader      | 11    | rtsx       | [CE2B20B3A9](<Notebook/Lenovo/ThinkPad/ThinkPad T440p 20AWS0Y40T/56BBB9E4DB70/FREEBSD-13.1/13.1-RELEASE/AMD64/CE2B20B3A9>) |
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 11    | rtsx       | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 10    | rtsx       | [17F444775B](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/9A43951EB263/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/17F444775B>) |
| 10ec:5227 | 17aa:220c | Realtek Semic... | RTS5227 PCI Express Card Reader      | 9     | rtsx       | [DF62882C3B](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AR003SMN/FE0FBD6135B1/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/DF62882C3B>) |
| 10ec:5227 | 17aa:5034 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 9     | rtsx       | [7708C4BB19](<Notebook/Lenovo/ThinkPad/ThinkPad T450s 20BXCTO1WW/C49A61555568/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7708C4BB19>) |
| 10ec:5229 | 8086:2072 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx       | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 10ec:522a | 17aa:5053 | Realtek Semic... | RTS522A PCI Express Card Reader      | 8     | rtsx       | [3A9623CFB4](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FN002JUS/8E643E12C08D/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/3A9623CFB4>) |
| 1217:8520 | 1028:05ca | O2 Micro         | SD/MMC Card Reader Controller        | 8     | sdhci_pci  | [EA99621380](<Notebook/Dell/Latitude/Latitude E7240/4A55E51D2962/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/EA99621380>) |
| 10ec:5227 | 10cf:187f | Realtek Semic... | RTS5227 PCI Express Card Reader      | 7     | rtsx       | [3A86733538](<Notebook/Fujitsu/LIFEBOOK/LIFEBOOK U904/440BDD7525FA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3A86733538>) |
| 10ec:522a | 103c:8079 | Realtek Semic... | RTS522A PCI Express Card Reader      | 7     | rtsx       | [5807159F51](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/F22631E176FA/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/5807159F51>) |
| 10ec:5227 | 17aa:2214 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 6     | rtsx       | [6E38EB1A4E](<Notebook/Lenovo/ThinkPad/ThinkPad X240 20AMS1YG01/5FCC7C04EE41/OPNSENSE-22.1.6/13.0-STABLE/AMD64/6E38EB1A4E>) |
| 10ec:525a | 17aa:2238 | Realtek Semic... | RTS525A PCI Express Card Reader      | 6     | rtsx       | [4CBD9F9314](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FQ000QUS/A325841E215E/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/4CBD9F9314>) |
| 10ec:522a | 1458:1000 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [752F962123](<Desktop/Gigabyte Technology/GB-BACE-3000/GB-BACE-3000-SBE/A8A80797C4EA/OPNSENSE-22.1.5/13.0-STABLE/AMD64/752F962123>) |
| 10ec:522a | 17aa:504a | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [117014D55F](<Notebook/Lenovo/ThinkPad/ThinkPad X260 20F6S0KA00/10FFFAF37956/FREEBSD-13.1/13.1-RELEASE/AMD64/117014D55F>) |
| 10ec:525a | 1028:06de | Realtek Semic... | RTS525A PCI Express Card Reader      | 5     | rtsx       | [9E798CBFC8](<Notebook/Dell/Latitude/Latitude E5470/B6D6813652AE/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/9E798CBFC8>) |
| 10ec:5229 | 8086:2067 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 4     | rtsx       | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 10ec:522a | 17aa:2279 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 10ec:522a | 17aa:5050 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [AC8E728222](<Notebook/Lenovo/ThinkPad/ThinkPad T460p 20FW003PMZ/71CAE53D9EBC/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/AC8E728222>) |
| 10ec:522a | 17aa:5082 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [CF5F498572](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 1 20UF000QRT/28FFDBA7F5C3/FREEBSD-13.1/13.1-RELEASE/AMD64/CF5F498572>) |
| 10ec:522a | 17aa:5122 | Realtek Semic... | RTS522A PCI Express Card Reader      | 4     | rtsx       | [683591700F](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MVS0LG00/F4E54EA14D75/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/683591700F>) |
| 10ec:525a | 1028:06da | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx       | [4C4937D824](<Notebook/Dell/Precision/Precision 7710/60C3A4533903/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4C4937D824>) |
| 10ec:525a | 1028:06df | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx       | [C214CE4AB0](<Notebook/Dell/Latitude/Latitude E5570/27A2311855F4/FREEBSD-13.0-P10/13.0-RELEASE-P10/AMD64/C214CE4AB0>) |
| 10ec:525a | 1028:08b8 | Realtek Semic... | RTS525A PCI Express Card Reader      | 4     | rtsx       | [639993A130](<Notebook/Dell/Latitude/Latitude 5400/411845E48AFC/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/639993A130>) |
| 10ec:5209 | 17aa:21dd | Realtek Semic... | RTS5209 PCI Express Card Reader      | 3     | rtsx       | [A697BE2AA9](<Notebook/Lenovo/ThinkPad/ThinkPad L420 7829WDY/20348E698FCF/FREEBSD-13.1/13.1-RELEASE/AMD64/A697BE2AA9>) |
| 10ec:5227 | 103c:1991 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 3     | rtsx       | [362940ACBB](<Notebook/Hewlett-Packard/EliteBook/EliteBook 820 G1/43570E209C4E/HELLOSYSTEM-0.8.0/13.0-RELEASE/AMD64/362940ACBB>) |
| 10ec:5227 | 1179:0001 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 3     | rtsx       | [149E5C3DE3](<Notebook/Toshiba/TECRA/TECRA Z40-C-12Z/7250A1A24FA6/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/149E5C3DE3>) |
| 10ec:5229 | 10ec:5229 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 3     | rtsx       | [77E235D9F8](<Desktop/Dell/Inspiron/Inspiron 3050/EF4E88174903/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/77E235D9F8>) |
| 10ec:522a | 1558:a500 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [E83D522905](<Notebook/TUXEDO/Aura/Aura 15 Gen1/1A68AD0FF8B9/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/E83D522905>) |
| 10ec:522a | 17aa:506d | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 10ec:522a | 17aa:5125 | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [078888676A](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NJ0010PB/9B27FD42E1E1/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/078888676A>) |
| 10ec:5249 | 1028:0665 | Realtek Semic... | RTS5249 PCI Express Card Reader      | 3     | rtsx       | [8EC61DB3F0](<Notebook/Dell/XPS/XPS 13 9343/F0F9A27ADDEB/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/8EC61DB3F0>) |
| 10ec:5249 | 17aa:3801 | Realtek Semic... | RTS5249 PCI Express Card Reader      | 3     | rtsx       | [1FEB455E8C](<Notebook/Lenovo/Y50-70/Y50-70 20378/45CB117B153A/OPNSENSE-21.7.7/12.1-RELEASE-P19-HBSD/AMD64/1FEB455E8C>) |
| 10ec:525a | 1028:079f | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [089B61BB38](<Notebook/Dell/Latitude/Latitude 7280/E9E3F30F4DB0/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/089B61BB38>) |
| 10ec:525a | 1028:081b | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [BC5EB8E237](<Notebook/Dell/Latitude/Latitude 7390/7E111470199B/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/BC5EB8E237>) |
| 10ec:525a | 10ec:525a | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [794FE8EB65](<Desktop/Dell/XPS/XPS 8950/759E5D9BB90A/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/794FE8EB65>) |
| 10ec:525a | 17aa:224f | Realtek Semic... | RTS525A PCI Express Card Reader      | 3     | rtsx       | [4993AD0FEB](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 5th 20HQS1QC00/BB184D2CE6FD/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/4993AD0FEB>) |
| 10ec:5287 | 1043:202f | Realtek Semic... | RTL8411B PCI Express Card Reader     | 3     | rtsx       | [5624C69D4B](<Notebook/ASUSTek Computer/G551/G551JW/B7E7048EB864/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/5624C69D4B>) |
| 10ec:5287 | 1558:1313 | Realtek Semic... | RTL8411B PCI Express Card Reader     | 3     | rtsx       | [8986953ACD](<Notebook/Notebook/N13/N13xWU/7DA387D7ADEA/GHOSTBSD-22.01.12/13.0-STABLE/AMD64/8986953ACD>) |
| 10ec:5289 | 1043:1457 | Realtek Semic... | RTL8411 PCI Express Card Reader      | 3     | rtsx       | [6FA29C4E4D](<Notebook/ASUSTek Computer/K55/K55VD/47D6D2467DC8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/6FA29C4E4D>) |
| 10ec:5209 | 103c:3577 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     |            | [F83C769501](<Notebook/Hewlett-Packard/2000/2000/5F42EBFDBCAE/FREEBSD-12.2/12.2-RELEASE/AMD64/F83C769501>) |
| 10ec:5209 | 104d:90b8 | Realtek Semic... | RTS5209 PCI Express Card Reader      | 2     | rtsx       | [64F3F02018](<Notebook/Sony/SVF1421/SVF1421DSGW/D451EB9DE7D3/FREEBSD-13.0/13.0-RELEASE/AMD64/64F3F02018>) |
| 10ec:5227 | 103c:2246 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx       | [DA49561A8F](<Notebook/Hewlett-Packard/ProBook/ProBook 430 G2/0B9FDF5DA838/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/DA49561A8F>) |
| 10ec:5227 | 17aa:2217 | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx       | [39EF89F214](<Notebook/Lenovo/ThinkPad/ThinkPad S1 Yoga 20C0S0M300/DC2E490F82F3/NOMADBSD-5806F915/13.0-RELEASE-P3/AMD64/39EF89F214>) |
| 10ec:5227 | 17aa:503c | Realtek Semic... | RTS5227 PCI Express Card Reader      | 2     | rtsx       | [B779706B7A](<Notebook/Lenovo/ThinkPad/ThinkPad L450 20DSS1S402/0FD1E037978C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P11/AMD64/B779706B7A>) |
| 10ec:5229 | 1043:202f | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     |            | [1697EBB0A5](<Notebook/ASUSTek Computer/Strix/Strix 17 GL703GE/BAA0EBC7F5C2/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/1697EBB0A5>) |
| 10ec:5229 | 10f7:8338 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx       | [7047AFAAF4](<Notebook/Panasonic/CF-31/CF-31-5/BCA7F1BDD217/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/7047AFAAF4>) |
| 10ec:5229 | 17aa:21f3 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     | rtsx       | [86FD351C81](<Notebook/Lenovo/ThinkPad/ThinkPad T430 2349AK1/08273574C200/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/86FD351C81>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 61    | qat        | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 8086:19e2 |           | Intel            | Atom Processor C3000 Series Quick... | 57    | qat        | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 31    |            | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 8086:0434 |           | Intel            | DH89XXCC Series QAT                  | 12    |            | [FA30F060F3](<Desktop/Intel/CARLOW/CARLOW/34C34A8491A2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/FA30F060F3>) |
| 8086:37c8 |           | Intel            | C62x Chipset QuickAssist Technology  | 7     | qat        | [03D71C925B](<Desktop/iEi/Z/Z596/4966738C3457/OPNSENSE-22.7/13.1-RELEASE/AMD64/03D71C925B>) |
| 19a2:0800 | 1734:11cc | Emulex           | ServerView iRMC HTI                  | 6     |            | [DAE7027898](<Desktop/Fujitsu/PRIMERGY/PRIMERGY TX2560 M1/4C2638BCEE71/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/DAE7027898>) |
| 1734:1228 | 1734:1256 | Fujitsu Techn... |                                      | 3     |            | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 8086:1f18 | 15d9:0820 | Intel            | Atom processor C2000 QAT             | 3     | qat        | [FB96378782](<Server/Supermicro/A1/A1SRM-2758F/F38A17AAB757/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FB96378782>) |
| 1000:0a05 | 1000:0a09 | Broadcom / LSI   |                                      | 2     |            | [5A8641FC9D](<Desktop/Cisco/SALEEN/SALEEN/40F23693CE8F/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/5A8641FC9D>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 2     |            | [0ED70BA3C3](<Mini Pc/Apple/Macmini4/Macmini4,1/5565314A3A26/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/0ED70BA3C3>) |
| 8086:19e2 | 8086:19e2 | Intel            | Atom Processor C3000 Series Quick... | 2     | qat        | [9BEB572E0D](<Desktop/ASRockRack/C3558/C3558D4I-4L/00F1FC522527/OPNSENSE-22.1.10/13.0-STABLE/AMD64/9BEB572E0D>) |
| 10de:03f4 |           | Nvidia           | MCP61 SMU                            | 1     |            | [009BC44D12](<Desktop/ONDA/N78G5D3/N78G5D3 Ver:5.00/8C38C68857FC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/009BC44D12>) |
| 10de:03f4 | 1462:7597 | Nvidia           | MCP61 SMU                            | 1     |            | [6BE2D8AEC7](<Desktop/MSI/MS/MS-7597/30A30607F88A/FREEBSD-12.2/12.2-RELEASE/AMD64/6BE2D8AEC7>) |
| 10de:0753 | 1025:0157 | Nvidia           | MCP78S [GeForce 8200] Co-Processor   | 1     |            | [DB1E7A52B9](<Desktop/Acer/Aspire/Aspire X3200/F5C25C81945B/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/DB1E7A52B9>) |
| 10de:07da | 1025:0137 | Nvidia           | MCP73 Co-processor                   | 1     |            | [6C169BDB6A](<Desktop/Dell/OptiPlex/OptiPlex 7040/D9A5C4B626A4/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/6C169BDB6A>) |
| 10de:0aa3 | 1028:0271 | Nvidia           | MCP79 Co-processor                   | 1     |            | [642DA98E96](<Notebook/Dell/Studio/Studio XPS 1340/ACFB55475A2B/FREEBSD-13.1/13.1-RELEASE/AMD64/642DA98E96>) |
| 10de:0aa3 | 1043:1cf7 | Nvidia           | MCP79 Co-processor                   | 1     |            | [B8BFDEC836](<Notebook/ASUSTek Computer/K50/K50IN/649EA35E6EC2/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8BFDEC836>) |
| 10de:0aa3 | 105b:0d52 | Nvidia           | MCP79 Co-processor                   | 1     |            | [79AB8EFB37](<Desktop/Foxconn/nT-330/nT-330i/70806ED76AFE/FREEBSD-12.1-P6/12.1-RELEASE-P6/AMD64/79AB8EFB37>) |
| 10de:0aa3 | 19da:a108 | Nvidia           | MCP79 Co-processor                   | 1     |            | [623EA6A889](<Desktop/Others/Others/Others/2BBBCF62335B/FREEBSD-12.1--HBSD/12.1-RELEASE-P7-HBSD/AMD64/623EA6A889>) |
| 1734:1228 | 1734:1229 | Fujitsu Techn... |                                      | 1     |            | [6E6F1B0F99](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M4/BA1E3C5B14F6/HARDENEDBSD-12.2--HBSD/12.2-STABLE-HBSD/AMD64/6E6F1B0F99>) |
| 8086:37c8 | 8086:0001 | Intel            | C62x Chipset QuickAssist Technology  | 1     | qat        | [638B27BC34](<Server/Supermicro/Super/Super Server/CF1692AC0104/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638B27BC34>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 206   |            | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 195   |            | [41094C24B2](<Desktop/Protectli/FW/FW6/FEB8F4459554/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/41094C24B2>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 96    |            | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 8086:4de0 | 8086:7270 | Intel            | Management Engine Interface          | 79    |            | [4243D313A1](<Desktop/GoWin Solution/R86/R86S/F79E140BEE45/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4243D313A1>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 76    |            | [33C59C687D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B28E7D1C74B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/33C59C687D>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 74    |            | [7CCCECFDE1](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/3A76FE02D6F8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CCCECFDE1>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 42    |            | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:8c3a | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 39    |            | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 8086:8c3a | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 36    |            | [D4296FD9D8](<Desktop/Dell/OptiPlex/OptiPlex 3020/F9299AC8F1C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4296FD9D8>) |
| 8086:8c3a | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 36    |            | [B29F2E4573](<Desktop/ASUSTek Computer/All/All Series/82A5E8C63352/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B29F2E4573>) |
| 8086:1c3a | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 34    |            | [76ECD68FF6](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/76ECD68FF6>) |
| 8086:8c3d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 33    | uart       | [A019244C85](<Desktop/Dell/OptiPlex/OptiPlex 9020/76964B2E7E4F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A019244C85>) |
| 8086:1c3a | 1458:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 32    |            | [1EC1683ACD](<Desktop/Gigabyte Technology/P61/P61-USB3-B3/CFEE4BCC2A88/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/1EC1683ACD>) |
| 8086:a13a | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 32    |            | [F1F56FE86C](<Desktop/ASUSTek Computer/H110/H110I-PLUS/8EB615606E3F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/F1F56FE86C>) |
| 8086:19d3 | 8086:19d3 | Intel            | Atom Processor C3000 Series ME HE... | 30    |            | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 8086:1e3a | 1043:84ca | Intel            | 7 Series/C216 Chipset Family MEI ... | 30    |            | [10B6C81BCE](<Desktop/ASUSTek Computer/P8H77-V/P8H77-V LE/EEA085D70636/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/10B6C81BCE>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 29    |            | [4BCC34FDCA](<Desktop/Gigabyte Technology/J4005/J4005ND2P-CF/A537E2535E76/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4BCC34FDCA>) |
| 8086:9de0 | 8086:7270 | Intel            | Cannon Point-LP MEI Controller #1    | 29    |            | [A0FB185069](<Desktop/Others/QD-WHLU/QD-WHLU01/88165FD62ECC/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A0FB185069>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 27    |            | [DEB30193E2](<Desktop/Others/SKYBAY/SKYBAY/96BBF63CAAAE/OPNSENSE-22.7.9/13.1-RELEASE/AMD64/DEB30193E2>) |
| 8086:19d3 | 15d9:0969 | Intel            | Atom Processor C3000 Series ME HE... | 26    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:1e3a | 1028:0577 | Intel            | 7 Series/C216 Chipset Family MEI ... | 26    |            | [B6EC2E7E28](<Desktop/Dell/OptiPlex/OptiPlex 7010/92F0DFFBABB2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B6EC2E7E28>) |
| 8086:1e3a | 1458:1c3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 26    |            | [734FF7F48C](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/93F9F29A0DC5/OPNSENSE-20.7.5/12.1-RELEASE-P10-HBSD/AMD64/734FF7F48C>) |
| 8086:5a9a |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 25    |            | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:5a9c | 8086:7270 | Intel            |                                      | 25    |            | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 8086:5a9e | 8086:7270 | Intel            |                                      | 25    |            | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 8086:8c3a | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c3a | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c3b | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c3b | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:a2ba | 1043:8694 | Intel            | 200 Series PCH CSME HECI #1          | 25    |            | [D44C580408](<Desktop/ASUSTek Computer/STRIX/STRIX Z270I GAMING/FF945A143CA8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/D44C580408>) |
| 8086:1c3a | 8086:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 24    |            | [FA30F060F3](<Desktop/Intel/CARLOW/CARLOW/34C34A8491A2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/FA30F060F3>) |
| 8086:3b64 | 17aa:215f | Intel            | 5 Series/3400 Series Chipset HECI... | 24    |            | [CBA0FC2340](<Notebook/Lenovo/ThinkPad/ThinkPad L412 0585AD9/A37928EB0C1B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/CBA0FC2340>) |
| 8086:5a9a | 1849:5a9a | Intel            | Celeron N3350/Pentium N4200/Atom ... | 23    |            | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 8086:8c3a | 1458:1c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 23    |            | [29AD5EE336](<Desktop/Gigabyte Technology/H81/H81M-DS2/566372D2BBD3/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/29AD5EE336>) |
| 8086:319a | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    |            | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:8c3a | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 22    |            | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:8c3b | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 22    |            | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:a360 | 1043:8694 | Intel            | Cannon Lake PCH HECI Controller      | 22    |            | [90279B62B7](<Desktop/ASUSTek Computer/PRIME/PRIME B360M-K/32256E13726B/OPNSENSE-22.7.9/13.1-RELEASE-P3/AMD64/90279B62B7>) |
| 8086:1c3a | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 21    |            | [CB98F3014E](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4286CTO/3C1927176580/FREEBSD-13.1/13.1-RELEASE/AMD64/CB98F3014E>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 21    |            | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 8086:8c3a | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    |            | [AFC7DE60E3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/CB6EAA64FCFB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/AFC7DE60E3>) |
| 8086:8c3d | 103c:1998 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | uart       | [AFC7DE60E3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/CB6EAA64FCFB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/AFC7DE60E3>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 21    |            | [FD081A3636](<Notebook/TUXEDO/InfinityBook13/InfinityBook13V3/933DC608BC77/FREEBSD-13.1/13.1-RELEASE/AMD64/FD081A3636>) |
| 8086:8c3a | 1849:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 20    |            | [106E525671](<Desktop/ASRock/E3/E3C224D2I/B67321B4991A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/106E525671>) |
| 8086:1e3a | 8086:1e3a | Intel            | 7 Series/C216 Chipset Family MEI ... | 19    |            | [2DF5C5B434](<Notebook/Others/Others/Others/3C2409610548/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/2DF5C5B434>) |
| 8086:a2ba | 1458:1c3a | Intel            | 200 Series PCH CSME HECI #1          | 19    |            | [5784D8BED6](<Desktop/Gigabyte Technology/H270/H270M-DS3H/CAE53A19F03D/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/5784D8BED6>) |
| 8086:8c3a | 8086:8c3a | Intel            | 8 Series/C220 Series Chipset Fami... | 18    |            | [073C2C8DE0](<Desktop/Intel/SHARKBAY/SHARKBAY/54266AFBE61A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/073C2C8DE0>) |
| 8086:a1ba | 15d9:0986 | Intel            | C620 Series Chipset Family MEI Co... | 18    |            | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |
| 8086:a1bb | 15d9:0986 | Intel            | C620 Series Chipset Family MEI Co... | 18    |            | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |
| 8086:a1be | 15d9:0986 | Intel            | C620 Series Chipset Family MEI Co... | 18    |            | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 274   |            | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 179   |            | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 165   |            | [126BDE2444](<Mini Pc/AMI/Aptio/Aptio CRB/CFCF4A9B6209/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/126BDE2444>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 144   |            | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 109   | ccp        | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 76    |            | [D22C37FA81](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/7F8CFAEEF0F8/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/D22C37FA81>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 41    |            | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 1022:1486 | 1043:87c0 | AMD              | Starship/Matisse Cryptographic Co... | 39    |            | [2E842DDB27](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/2E842DDB27>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 35    | ccp        | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 177d:0010 | 177d:0001 | Cavium           | CN15XX/CN16XX [Nitrox PX]            | 25    |            | [9E587B9499](<Desktop/Cisco/SALEEN/SALEEN/B9A28B95EBD4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E587B9499>) |
| 1022:1456 | 1043:8747 | AMD              | Family 17h (Models 00h-0fh) Platf... | 24    |            | [334575B738](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/A1AB004D09A5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/334575B738>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 22    |            | [D3D1107F77](<Desktop/Biostar/A10/A10N-8800E/940DAEB9E452/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3D1107F77>) |
| 8086:0f18 | 1849:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 18    |            | [42A53E5201](<Desktop/ASRock/Q2900/Q2900M/76BCB5ECE4E0/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/42A53E5201>) |
| 1022:15df | 1043:876b | AMD              | Family 17h (Models 10h-1fh) Platf... | 17    |            | [3FAAAA8209](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/837435F7D2A1/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3FAAAA8209>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 17    |            | [2F701B55FC](<Desktop/ZOTAC/Others/Others/9EC819E4E991/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2F701B55FC>) |
| 1022:1486 | 1043:8808 | AMD              | Starship/Matisse Cryptographic Co... | 14    |            | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 1022:15df | 1043:8809 | AMD              | Family 17h (Models 10h-1fh) Platf... | 13    |            | [A1B29C356E](<Desktop/ASUSTek Computer/TUF/TUF Gaming B550-PLUS/0E08DF8E9577/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A1B29C356E>) |
| 8086:2298 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 12    |            | [649D525FDB](<Server/Supermicro/Super/Super Server/A4D89EA96DC4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/649D525FDB>) |
| 8086:2298 | 1849:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     |            | [80C809E992](<Desktop/ASRock/N3710-NUC/N3710-NUC IPC/E0800AE12493/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/80C809E992>) |
| 8086:2298 | 8086:2298 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     |            | [2690C2A8DF](<Desktop/NU941/1/1.0/5ECD4B5CC634/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/2690C2A8DF>) |
| 8086:0f18 | 1458:1c3a | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 8     |            | [E2AD4D8035](<Desktop/Gigabyte Technology/J1900/J1900N-D3V/FC5120937F9C/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/E2AD4D8035>) |
| 1022:15df | 1849:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 7     |            | [009EF73BD1](<Desktop/ASRock/4X4-4000/4X4-4000 Series/ACBB8335DDB2/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/009EF73BD1>) |
| 8086:2298 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 7     |            | [2D521E085B](<Mini Pc/Intel/NUC5/NUC5PPYB/8054EC01AC51/FREEBSD-13.1/13.1-RELEASE/AMD64/2D521E085B>) |
| 1022:1486 | 1462:7c02 | AMD              | Starship/Matisse Cryptographic Co... | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 8086:2298 | 1043:8534 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [4A83B0953E](<Desktop/ASUSTek Computer/All/All Series/C4CB713C5D6F/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4A83B0953E>) |
| 8086:2298 | 1458:1000 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [752F962123](<Desktop/Gigabyte Technology/GB-BACE-3000/GB-BACE-3000-SBE/A8A80797C4EA/OPNSENSE-22.1.5/13.0-STABLE/AMD64/752F962123>) |
| 8086:2298 | 1458:1c3a | Intel            | Atom/Celeron/Pentium Processor x5... | 5     |            | [C84BEDC821](<Desktop/Gigabyte Technology/N3160/N3160ND3V/B01DE72F7AFE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C84BEDC821>) |
| 1022:1498 | 1022:1498 | AMD              | Starship/Matisse PTDMA               | 4     |            | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |
| 1022:1578 | 103c:84ac | AMD              | Carrizo Platform Security Processor  | 4     |            | [766E62F699](<Notebook/Hewlett-Packard/Laptop/Laptop 15-db0xxx/3E8F8F48759C/NOMADBSD-5806F915/13.0-RELEASE/AMD64/766E62F699>) |
| 1022:15df | 17aa:3834 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [4C83122CC0](<Notebook/Lenovo/Yoga/Yoga Slim 7 Pro 14ACH5 O 82N5/C4F4168282ED/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/4C83122CC0>) |
| 1022:15df | 17aa:5097 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [6C208C85A5](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6C208C85A5>) |
| 1022:15df | 17aa:5122 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [683591700F](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MVS0LG00/F4E54EA14D75/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/683591700F>) |
| 1022:15df | 17aa:5125 | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [078888676A](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NJ0010PB/9B27FD42E1E1/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/078888676A>) |
| 1022:15df | 1d05:109f | AMD              | Family 17h (Models 10h-1fh) Platf... | 4     |            | [5EDF8A1BEF](<Notebook/TUXEDO/Pulse/Pulse 14 Gen1/B37BF57882B7/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/5EDF8A1BEF>) |
| 8086:2298 | 1565:3112 | Intel            | Atom/Celeron/Pentium Processor x5... | 4     |            | [4520B5034E](<Desktop/ASRock/E350/E350M1/790F04D92088/FREEBSD-13.1-RC6/13.1-RC6/AMD64/4520B5034E>) |
| 1022:1456 | 1462:7b86 | AMD              | Family 17h (Models 00h-0fh) Platf... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:1537 | 17aa:3801 | AMD              | Kabini/Mullins PSP-Platform Secur... | 3     |            | [6E31B5F45B](<Notebook/Lenovo/G40-45/G40-45 80E1/EA83D0EBE432/FREEBSD-13.1/13.1-RELEASE/AMD64/6E31B5F45B>) |
| 1022:15df | 1558:a500 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     |            | [E83D522905](<Notebook/TUXEDO/Aura/Aura 15 Gen1/1A68AD0FF8B9/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/E83D522905>) |
| 1022:15df | 17aa:5082 | AMD              | Family 17h (Models 10h-1fh) Platf... | 3     | ccp        | [CF5F498572](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 1 20UF000QRT/28FFDBA7F5C3/FREEBSD-13.1/13.1-RELEASE/AMD64/CF5F498572>) |
| 8086:0f18 | 1043:8534 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [F587EC97A4](<Desktop/ASUSTek Computer/K30/K30AM-J_A_F_K31AM-J/104F53E4EEED/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/F587EC97A4>) |
| 8086:0f18 | 1071:0730 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [294F283D65](<Mini Pc/AMI/Aptio/Aptio CRB/293083C7BA4B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/294F283D65>) |
| 8086:0f18 | 15d9:0816 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [5A733D841D](<Server/XQAND/X10/X10SBA-L/C31CA5CEBF82/OPNSENSE-22.7/13.1-RELEASE/AMD64/5A733D841D>) |
| 8086:0f18 | 8086:2055 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [160D942D28](<Desktop/Intel/DN2820FYK/DN2820FYK H24582-203/8333B3661BA6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/160D942D28>) |
| 1022:1456 | 1025:1246 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     |            | [9E03A76684](<Notebook/Acer/Predator/Predator PH517-61/401258E70C57/FREEBSD-13.0/13.0-RELEASE/AMD64/9E03A76684>) |
| 1022:1456 | 1462:7b89 | AMD              | Family 17h (Models 00h-0fh) Platf... | 2     |            | [8B3A234691](<Desktop/MSI/MS-7/MS-7B89/C8A1522450C9/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/8B3A234691>) |
| 1022:1486 | 1043:87cb | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [02F241B7D7](<Desktop/ASUSTek Computer/ROG/ROG STRIX TRX40-E GAMING/34740A217190/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/02F241B7D7>) |
| 1022:1486 | 1458:1000 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1022:1486 | 1462:7b86 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [DF6278638E](<Desktop/MSI/MS-7/MS-7B86/172CA9AD2823/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DF6278638E>) |
| 1022:1498 | 1458:1000 | AMD              | Starship/Matisse PTDMA               | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1022:1578 | 103c:8330 | AMD              | Carrizo Platform Security Processor  | 2     |            | [8E9A6CFF62](<Notebook/Hewlett-Packard/Laptop/Laptop 15-rb0xx/94A2E681C681/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/8E9A6CFF62>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 44    | fwohci     | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 24    | fwohci     | [BC15367E9F](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BC15367E9F>) |
| 1180:0832 | 17aa:20c7 | Ricoh            | R5C832 IEEE 1394 Controller          | 19    | fwohci     | [50C3C93790](<Notebook/Lenovo/ThinkPad/ThinkPad T61 765912G/04EB3BF745ED/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/50C3C93790>) |
| 1180:e832 | 17aa:2136 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 13    | fwohci     | [A1561DACB2](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2522CS7/3C98BD93E6E5/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A1561DACB2>) |
| 1106:3044 | 1043:81fe | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 11    | fwohci     | [314916C885](<Desktop/ASUSTek Computer/P6T/P6T DELUXE V2/E1EBD8E6C996/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/314916C885>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 11    | fwohci     | [7AEF0A996B](<Notebook/Apple/MacBook3/MacBook3,1/B75216EE3719/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7AEF0A996B>) |
| 1106:3044 | 1458:1000 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 10    | fwohci     | [70C9122B95](<Desktop/Gigabyte Technology/Z87/Z87X-UD5H/D76966E3C571/OPNSENSE-22.1.10/13.0-STABLE/AMD64/70C9122B95>) |
| 11c1:5811 | 103c:1589 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 9     | fwohci     | [0696D30D3F](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/0696D30D3F>) |
| 1102:4001 | 1102:0010 | Creative Labs    | SB Audigy FireWire Port              | 8     | fwohci     | [2A03C05CCE](<Desktop/Equus Computer Systems/Nobilis/Nobilis/67B3FC31A85D/FREEBSD-12.3/12.3-RELEASE/AMD64/2A03C05CCE>) |
| 1106:3044 | 1106:3044 | VIA Technologies | VT6306/7/8 [Fire II(M)] IEEE 1394... | 8     | fwohci     | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 104c:8024 | 1458:1000 | Texas Instrum... | TSB43AB23 IEEE-1394a-2000 Control... | 7     | fwohci     | [3EE914E3A0](<Desktop/Gigabyte Technology/GA-890/GA-890FXA-UD5/0D93685E30B3/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/3EE914E3A0>) |
| 1180:e832 | 17aa:21ce | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 7     | fwohci     | [4067CE2036](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4236C92/28F77ADEDD67/FREEBSD-13.1/13.1-RELEASE/AMD64/4067CE2036>) |
| 11c1:5811 | 1043:8294 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 7     | fwohci     | [BC829DBB1A](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/BC829DBB1A>) |
| 1180:e832 | 17aa:21cf | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 5     |            | [40198ABAA2](<Notebook/Lenovo/ThinkPad/ThinkPad W520 4282AD4/40DEB82124E5/FREEBSD-13.1/13.1-RELEASE/AMD64/40198ABAA2>) |
| 1180:e832 | 17aa:21f6 | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 5     | fwohci     | [9A3CBE1893](<Notebook/Lenovo/ThinkPad/ThinkPad T530 2392AQU/F63B1985C532/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/9A3CBE1893>) |
| 11c1:5811 | 103c:158a | LSI              | FW322/323 [TrueFire] 1394a Contro... | 5     | fwohci     | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 104c:8025 |           | Texas Instrum... | TSB82AA2 IEEE-1394b Link Layer Co... | 4     | fwohci     | [912D02AEC2](<Notebook/Apple/MacBookPro3/MacBookPro3,1/F5F1B1FD305E/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/912D02AEC2>) |
| 1180:e832 | 1028:040a | Ricoh            | R5C832 PCIe IEEE 1394 Controller     | 4     | fwohci     | [8C904D84E0](<Notebook/Dell/Latitude/Latitude E6410/D86C1197F0AC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/8C904D84E0>) |
| 11c1:5811 | 1028:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 4     | fwohci     | [6E0F1CC72E](<Desktop/Hewlett-Packard/Compaq/Compaq 8200 Elite SFF PC/311F47899B6D/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/6E0F1CC72E>) |
| 1217:13f7 | 1028:049b | O2 Micro         | 1394 OHCI Compliant Host Controller  | 4     | fwohci     | [524AB094E1](<Notebook/Dell/Latitude/Latitude E5420/15C36179305C/FREEBSD-13.1/13.1-RELEASE/AMD64/524AB094E1>) |
| 104c:8023 | 1043:815b | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 3     | fwohci     | [87D7D4435B](<Desktop/ASUSTek Computer/P5/P5B-Deluxe/5AB2F7FF0FA3/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/87D7D4435B>) |
| 1106:3403 | 1043:8384 | VIA Technologies | VT6315 Series Firewire Controller    | 3     | fwohci     | [BE9D90602D](<Desktop/ASUSTek Computer/P9/P9X79/89D525F0E557/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/BE9D90602D>) |
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
| 11c1:5901 | 1b5b:803b | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 2     |            | [0696D30D3F](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/0696D30D3F>) |
| 11c1:5903 | 11c1:5900 | LSI              | FW533 [TrueFire] PCIe 1394a Contr... | 2     | fwohci     | [79503C0635](<Notebook/Apple/MacBook5/MacBook5,2/98FAA840F548/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/79503C0635>) |
| 1217:00f7 | 1028:01f9 | O2 Micro         | Firewire (IEEE 1394)                 | 2     | fwohci     | [1C600CC283](<Notebook/Dell/Latitude/Latitude D630/6FCFB35F2ECF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/1C600CC283>) |
| 197b:2380 | 103c:17a7 | JMicron Techn... | IEEE 1394 Host Controller            | 2     | fwohci     | [462FC329A9](<Notebook/Hewlett-Packard/EliteBook/EliteBook 8570p/8F084339058D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/462FC329A9>) |
| 1033:00cd | 12ee:8010 | NEC Computers    | uPD72870 [Firewarden] IEEE1394a O... | 1     | fwohci     | [E34B6118A2](<Desktop/Hewlett-Packard/Compaq/Compaq 505B Microtower PC/0EF9A1953E0E/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E34B6118A2>) |
| 104c:8020 | 15c5:8010 | Texas Instrum... | TSB12LV26 IEEE-1394 Controller (L... | 1     |            | [7E27B1BC46](<Desktop/ASUSTek Computer/M5/M5A78L-M-USB3/28DD15B58DF2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/7E27B1BC46>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 201   | vgapci     | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 152   | vgapci     | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 148   | vgapci     | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 84    | vgapci     | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 77    | vgapci     | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 8086:0f31 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 70    | vgapci     | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:3185 | 8086:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 70    | vgapci     | [B685DDC2AD](<Desktop/Hardkernel/ODROID-H/ODROID-H2/2813F39855C7/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B685DDC2AD>) |
| 8086:4e61 | 8086:2212 | Intel            | JasperLake [UHD Graphics]            | 67    | vgapci     | [CD3E4F7122](<Desktop/CncTion/N5105/N5105-4L/52B8556A9681/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/CD3E4F7122>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 61    | vgapci     | [A2BC442ACD](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/DE1062729CEF/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/A2BC442ACD>) |
| 8086:5916 | 8086:2015 | Intel            | HD Graphics 620                      | 59    | vgapci     | [F6FABABC22](<Desktop/Others/Others/Others/A81E6D09A273/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/F6FABABC22>) |
| 8086:0a16 | 8086:0a16 | Intel            | Haswell-ULT Integrated Graphics C... | 54    | vgapci     | [33C59C687D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B28E7D1C74B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/33C59C687D>) |
| 1002:9831 | 103c:213d | AMD              | Kabini [Radeon HD 8400E]             | 47    | vgapci     | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 102b:0532 | 1028:04dd | Matrox Electr... | MGA G200eW WPCM450                   | 43    | vgapci     | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 1002:515e | 103c:31fb | AMD              | ES1000                               | 41    | vgapci     | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:5917 | 8086:2015 | Intel            | UHD Graphics 620                     | 41    | vgapci     | [BC2C536004](<Desktop/Others/MANIFOLD/MANIFOLD 2-C/35C86EC57A8D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BC2C536004>) |
| 1002:131c | 103c:8103 | AMD              | Kaveri [Radeon R7 Graphics]          | 38    | vgapci     | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:1616 | 8086:1616 | Intel            | HD Graphics 5500                     | 38    | vgapci     | [7CCCECFDE1](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/3A76FE02D6F8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CCCECFDE1>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 35    | nvidia     | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 8086:2e32 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 34    | agp        | [1C0805F9AE](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1C0805F9AE>) |
| 8086:0412 | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 33    | vgapci     | [B29F2E4573](<Desktop/ASUSTek Computer/All/All Series/82A5E8C63352/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B29F2E4573>) |
| 8086:a001 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 33    | agp        | [AF4F0984AE](<Desktop/Others/Others/Others/6B9CCC8652E3/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/AF4F0984AE>) |
| 8086:a002 | 8086:a001 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 32    | vgapci     | [AF4F0984AE](<Desktop/Others/Others/Others/6B9CCC8652E3/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/AF4F0984AE>) |
| 8086:0412 | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 31    | vgapci     | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 1002:9833 | 1734:1202 | AMD              | Kabini [Radeon HD 8330E]             | 28    | vgapci     | [2AC107DF0F](<Desktop/Fujitsu/FUTRO/FUTRO S920/6EFEEA896AD2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/2AC107DF0F>) |
| 8086:1626 | 8086:1626 | Intel            | HD Graphics 6000                     | 28    | vgapci     | [ABED96A938](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/BE188DCB9F9B/OPNSENSE-22.1.10/13.0-STABLE/AMD64/ABED96A938>) |
| 1002:9851 | 1734:1202 | AMD              | Mullins [Radeon R4/R5 Graphics]      | 26    | vgapci     | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 102b:0532 | 15d9:0624 | Matrox Electr... | MGA G200eW WPCM450                   | 26    | vgapci     | [FE44242C3B](<Desktop/Supermicro/X9/X9SCL-X9SCM/0C3EBAE8F4DF/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/FE44242C3B>) |
| 1a03:2000 | 15d9:0813 | ASPEED Techno... | ASPEED Graphics Family               | 26    | vgapci     | [55A9138AF4](<Mini Pc/Supermicro/A1/A1SAi/1F717C154777/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/55A9138AF4>) |
| 1a03:2000 | 15d9:0969 | ASPEED Techno... | ASPEED Graphics Family               | 26    | vgapci     | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:5916 |           | Intel            | HD Graphics 620                      | 26    | vgapci     | [41094C24B2](<Desktop/Protectli/FW/FW6/FEB8F4459554/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/41094C24B2>) |
| 1a03:2000 | 15d9:086d | ASPEED Techno... | ASPEED Graphics Family               | 25    | vgapci     | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 1a03:2000 | 15d9:0921 | ASPEED Techno... | ASPEED Graphics Family               | 25    | vgapci     | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 1a03:2000 | 15d9:0842 | ASPEED Techno... | ASPEED Graphics Family               | 23    | vgapci     | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:0412 | 8086:0412 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 23    | vgapci     | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 23    | vgapci     | [14F174BD7C](<Mini Pc/BESSTAR Tech/GK/GK41/46F6D804D9F8/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/14F174BD7C>) |
| 8086:3ea0 | 8086:2212 | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 23    | vgapci     | [A6D41C71FD](<Desktop/Others/Others/Others/F9DEED394CD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A6D41C71FD>) |
| 1a03:2000 | 1849:2000 | ASPEED Techno... | ASPEED Graphics Family               | 22    | vgapci     | [106E525671](<Desktop/ASRock/E3/E3C224D2I/B67321B4991A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/106E525671>) |
| 8086:0412 | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 22    | vgapci     | [5441995E7B](<Desktop/Dell/OptiPlex/OptiPlex 3020/AD15385A82A2/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5441995E7B>) |
| 8086:0412 | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 21    | vgapci     | [AFC7DE60E3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/CB6EAA64FCFB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/AFC7DE60E3>) |
| 8086:5916 | 8086:2212 | Intel            | HD Graphics 620                      | 21    | vgapci     | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:5a85 | 1849:5a85 | Intel            | HD Graphics 500                      | 21    | vgapci     | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 1002:15d8 | 1002:15d8 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 20    | vgapci     | [D8D6AF9E56](<Desktop/MSI/MS-7/MS-7B89/FA187D4C2E8F/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/D8D6AF9E56>) |
| 8086:0046 | 17aa:215a | Intel            | Core Processor Integrated Graphic... | 20    | i915       | [CBA0FC2340](<Notebook/Lenovo/ThinkPad/ThinkPad L412 0585AD9/A37928EB0C1B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/CBA0FC2340>) |
| 8086:0402 | 8086:0402 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 20    | vgapci     | [4F86E686D2](<Desktop/CheckPoint/PB-15/PB-15-00/8CAA583F1507/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4F86E686D2>) |
| 8086:0152 | 1028:0577 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 19    | vgapci     | [B6EC2E7E28](<Desktop/Dell/OptiPlex/OptiPlex 7010/92F0DFFBABB2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B6EC2E7E28>) |
| 102b:0532 | 1028:0235 | Matrox Electr... | MGA G200eW WPCM450                   | 18    | vgapci     | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 1a03:2000 | 15d9:0986 | ASPEED Techno... | ASPEED Graphics Family               | 18    | vgapci     | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |
| 8086:0126 | 17aa:21da | Intel            | 2nd Generation Core Processor Fam... | 18    | i915       | [CB98F3014E](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4286CTO/3C1927176580/FREEBSD-13.1/13.1-RELEASE/AMD64/CB98F3014E>) |
| 8086:0412 | 1458:d000 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 18    | vgapci     | [7C6794942C](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G5 SFF/202F87656FE8/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/7C6794942C>) |
| 8086:3184 | 1028:080c | Intel            | GeminiLake [UHD Graphics 605]        | 18    | vgapci     | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |

### Input (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1102:7003 | 1102:0040 | Creative Labs    | SB Audigy Game Port                  | 7     | emujoy     | [2A03C05CCE](<Desktop/Equus Computer Systems/Nobilis/Nobilis/67B3FC31A85D/FREEBSD-12.3/12.3-RELEASE/AMD64/2A03C05CCE>) |
| 1102:7002 | 1102:0020 | Creative Labs    | SB Live! Game Port                   | 3     |            | [2620FD3511](<Desktop/ASUSTek Computer/P8/P8B75-M/D6575EA2BF9C/FREEBSD-13.1/13.1-RELEASE/AMD64/2620FD3511>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 241   |            | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 100   |            | [21F838983B](<Desktop/ASUSTek Computer/P11C-M/P11C-M Series/E4D1817AC6A4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/21F838983B>) |
| 8086:4def | 8086:7270 | Intel            | Jasper Lake Shared SRAM Controller   | 79    |            | [4243D313A1](<Desktop/GoWin Solution/R86/R86S/F79E140BEE45/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4243D313A1>) |
| 8086:9def | 8086:7270 | Intel            | Cannon Point-LP Shared SRAM          | 39    |            | [A0FB185069](<Desktop/Others/QD-WHLU/QD-WHLU01/88165FD62ECC/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A0FB185069>) |
| 8086:a121 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 35    |            | [7BC1746333](<Desktop/ASUSTek Computer/G11/G11CD/29D04E27064F/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7BC1746333>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 34    |            | [DEB30193E2](<Desktop/Others/SKYBAY/SKYBAY/96BBF63CAAAE/OPNSENSE-22.7.9/13.1-RELEASE/AMD64/DEB30193E2>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 32    |            | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 31    |            | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 31    |            | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 31    |            | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 8086:19de | 8086:7270 | Intel            | Atom Processor C3000 Series Power... | 30    |            | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 28    |            | [638E327C4E](<Desktop/MSI/CML-U/CML-U PRO Cubi 5/110C3F90DC1E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638E327C4E>) |
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 26    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:06ef | 8086:7270 | Intel            | Comet Lake PCH Shared SRAM           | 25    |            | [B9994AA302](<Desktop/Others/Others/Others/0043505011B9/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/B9994AA302>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 25    |            | [D44C580408](<Desktop/ASUSTek Computer/STRIX/STRIX Z270I GAMING/FF945A143CA8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/D44C580408>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 23    |            | [F1CB9703A7](<Desktop/MSI/MS-7/MS-7D20/C955C1EB3B0C/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/F1CB9703A7>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 22    |            | [4130B19CFA](<Notebook/Google/Lars/Lars/CCB0F65C765F/FREEBSD-13.1/13.1-RELEASE/AMD64/4130B19CFA>) |
| 8086:a36f | 1043:8694 | Intel            | Cannon Lake PCH Shared SRAM          | 22    |            | [90279B62B7](<Desktop/ASUSTek Computer/PRIME/PRIME B360M-K/32256E13726B/OPNSENSE-22.7.9/13.1-RELEASE-P3/AMD64/90279B62B7>) |
| 8086:a2a1 | 1458:5001 | Intel            | 200 Series/Z370 Chipset Family Po... | 20    |            | [5784D8BED6](<Desktop/Gigabyte Technology/H270/H270M-DS3H/CAE53A19F03D/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/5784D8BED6>) |
| 8086:a1a1 | 15d9:0986 | Intel            | C620 Series Chipset Family Power ... | 18    |            | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |
| 8086:a121 | 1458:5001 | Intel            | 100 Series/C230 Series Chipset Fa... | 17    |            | [03708406E8](<Desktop/Gigabyte Technology/Z170X-Gaming/Z170X-Gaming 3/A8A67AC0AFC9/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/03708406E8>) |
| 8086:a2a1 | 1849:a2a1 | Intel            | 200 Series/Z370 Chipset Family Po... | 16    |            | [803B44339B](<Desktop/ASRock/B250/B250M-HDV/BD56D24CB794/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/803B44339B>) |
| 1912:0011 |           | Renesas Techn... | SH7757 PCIe End-Point [PBI]          | 15    |            | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:a36f | 1849:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 15    |            | [A40ADA7F7F](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A40ADA7F7F>) |
| 8086:43ef | 1043:8694 | Intel            | Tiger Lake-H Shared SRAM             | 14    |            | [E23F822438](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-F GAMING WIFI/83B0E22D5F39/OPNSENSE-22.1.10/13.0-STABLE/AMD64/E23F822438>) |
| 8086:9def | 8086:2074 | Intel            | Cannon Point-LP Shared SRAM          | 14    |            | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:a121 | 1734:121d | Intel            | 100 Series/C230 Series Chipset Fa... | 14    |            | [CCE93FF157](<Desktop/Fujitsu/D3401-H2/D3401-H2 S26361-D3401-H2/225D067B274C/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/CCE93FF157>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 14    |            | [F1B45790D4](<Desktop/HPE/ProLiant/ProLiant ML30 Gen10/93F91BA1C4A9/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/F1B45790D4>) |
| 8086:a36f | 17aa:312d | Intel            | Cannon Lake PCH Shared SRAM          | 13    |            | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:34ef | 8086:7270 | Intel            | Ice Lake-LP DRAM Controller          | 12    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:9d21 | 17aa:5062 | Intel            | Sunrise Point-LP PMC                 | 12    |            | [8257D11669](<Notebook/Lenovo/ThinkPad/ThinkPad X270 W10DG 20K5S0PY04/60067DC63CDD/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/8257D11669>) |
| 8086:9def |           | Intel            | Cannon Point-LP Shared SRAM          | 12    |            | [2DA32E59B0](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon 7th 20QES42E0L/CDF66CE99D08/FREEBSD-13.1-P1/13.1-RELEASE/AMD64/2DA32E59B0>) |
| 8086:a121 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 8086:a121 | 1849:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 12    |            | [7CC4B63834](<Desktop/ASRock/H110/H110 Pro BTC+/CB21DA586B1D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CC4B63834>) |
| 8086:9d21 | 8086:2068 | Intel            | Sunrise Point-LP PMC                 | 11    |            | [1A666E04D4](<Mini Pc/Intel/NUC7/NUC7i3BNH/E8C7B91522A0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1A666E04D4>) |
| 8086:a121 | 1028:06bb | Intel            | 100 Series/C230 Series Chipset Fa... | 11    |            | [15458AFF84](<Desktop/Dell/OptiPlex/OptiPlex 3040/6D890807CBBE/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/15458AFF84>) |
| 8086:a121 | 103c:8054 | Intel            | 100 Series/C230 Series Chipset Fa... | 11    |            | [C25ADEB2FF](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G2 SFF/955C65CA3D19/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/C25ADEB2FF>) |
| 8086:4b7f | 8086:7270 | Intel            |                                      | 10    |            | [0F727C761B](<Desktop/Others/Others/Others/5D44760B2901/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0F727C761B>) |
| 8086:a0ef | 8086:7270 | Intel            | Tiger Lake-LP Shared SRAM            | 10    |            | [85520BF6BF](<Desktop/Others/Others/Others/793AE5B1171E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/85520BF6BF>) |
| 8086:a121 | 1028:06b9 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [7B330ABF44](<Desktop/Dell/OptiPlex/OptiPlex 7040/59B2912697DF/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7B330ABF44>) |
| 8086:7aa7 |           | Intel            | Alder Lake-S PCH Shared SRAM         | 9     |            | [F6C8EB4E18](<Desktop/ASRock/B660/B660M-ITX-ac/2C580AAAA431/FREEBSD-13.1/13.1-RELEASE/AMD64/F6C8EB4E18>) |
| 8086:a121 | 1028:06ba | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [45D96A0B5A](<Desktop/Dell/OptiPlex/OptiPlex 5040/DA886BEEF2C1/FREEBSD-13.1-P4/13.1-RELEASE-P2/AMD64/45D96A0B5A>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [0A40B02AEB](<Desktop/Others/Others/Others/FB93D11DB736/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0A40B02AEB>) |
| 8086:02ef | 8086:2081 | Intel            | Comet Lake PCH-LP Shared SRAM        | 8     |            | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:9d21 | 103c:8079 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [5807159F51](<Notebook/Hewlett-Packard/EliteBook/EliteBook 840 G3/F22631E176FA/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/5807159F51>) |
| 8086:9d21 | 17aa:2238 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [4CBD9F9314](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FQ000QUS/A325841E215E/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/4CBD9F9314>) |
| 8086:9d21 | 17aa:5053 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [3A9623CFB4](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FN002JUS/8E643E12C08D/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/3A9623CFB4>) |
| 8086:9def | 17aa:2279 | Intel            | Cannon Point-LP Shared SRAM          | 8     |            | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 8086:a0ef |           | Intel            | Tiger Lake-LP Shared SRAM            | 8     |            | [1300135627](<Desktop/BESSTAR Tech/TH/TH50/FA70A553D80E/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/1300135627>) |
| 8086:a121 | 103c:8169 | Intel            | 100 Series/C230 Series Chipset Fa... | 8     |            | [E80C8A40A5](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/EF032CAD06FB/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/E80C8A40A5>) |

### Modem (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:266d | 1014:0574 | Intel            | 82801FB/FBM/FR/FW/FRW (ICH6 Famil... | 3     |            | [6FD6FD89C5](<Notebook/IBM/ThinkPad/ThinkPad R52 185869G/DED57F076B3E/FREEBSD-12.2-P6/12.2-RELEASE-P6/I386/6FD6FD89C5>) |
| 1039:7013 | 1043:1816 | Silicon Integ... | AC'97 Modem Controller               | 1     |            | [83106A58EF](<Notebook/ASUSTek Computer/A/A9T/CD438D683462/FREEBSD-13.0-P4/13.0-RELEASE-P4/I386/83106A58EF>) |
| 1039:7013 | 14c0:0012 | Silicon Integ... | AC'97 Modem Controller               | 1     |            | [56A5581907](<Notebook/Acer/TravelMate/TravelMate 270/A6730E9E5FB4/FREEBSD-12.1-P10/12.1-RELEASE-P9/I386/56A5581907>) |
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
| 1022:15e2 | 1022:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 52    |            | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 8086:1919 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 14    |            | [B686FDF1C1](<Desktop/Protectli/FW/FW6/AA9E145E9412/OPNSENSE-22.7/13.1-RELEASE/AMD64/B686FDF1C1>) |
| 14e4:1570 | 14e4:1570 | Broadcom         | 720p FaceTime HD Camera              | 11    |            | [5234A39100](<Notebook/Apple/MacBookPro14/MacBookPro14,1/E5CBB76DCE97/NOMADBSD-20221130/13.1-RELEASE-P5/AMD64/5234A39100>) |
| 1022:15e2 | 1849:15e2 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 7     |            | [009EF73BD1](<Desktop/ASRock/4X4-4000/4X4-4000 Series/ACBB8335DDB2/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/009EF73BD1>) |
| 1022:15e2 | 17aa:3836 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     |            | [4C83122CC0](<Notebook/Lenovo/Yoga/Yoga Slim 7 Pro 14ACH5 O 82N5/C4F4168282ED/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/4C83122CC0>) |
| 1022:15e2 | 17aa:5097 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     |            | [6C208C85A5](<Notebook/Lenovo/ThinkPad/ThinkPad E14 Gen 3 20Y7003SGE/284E69188279/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6C208C85A5>) |
| 1022:15e2 | 17aa:5125 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     |            | [078888676A](<Notebook/Lenovo/ThinkPad/ThinkPad T495 20NJ0010PB/9B27FD42E1E1/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/078888676A>) |
| 1022:15e2 | 1d05:109f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 4     |            | [5EDF8A1BEF](<Notebook/TUXEDO/Pulse/Pulse 14 Gen1/B37BF57882B7/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/5EDF8A1BEF>) |
| 1022:15e2 | 1558:a500 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     |            | [E83D522905](<Notebook/TUXEDO/Aura/Aura 15 Gen1/1A68AD0FF8B9/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/E83D522905>) |
| 1022:15e2 | 17aa:5082 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 3     |            | [CF5F498572](<Notebook/Lenovo/ThinkPad/ThinkPad X13 Gen 1 20UF000QRT/28FFDBA7F5C3/FREEBSD-13.1/13.1-RELEASE/AMD64/CF5F498572>) |
| 8086:22b8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     |            | [3454B5492B](<Notebook/AZW/BT3/BT3 PRO/8FB6E0960427/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/3454B5492B>) |
| 1022:15e2 | 1028:0a12 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [EAD2595782](<Notebook/Dell/Inspiron/Inspiron 3505/FD4D73324C8E/GHOSTBSD-22.07.16/13.1-STABLE/AMD64/EAD2595782>) |
| 1022:15e2 | 103c:85e0 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [E7B40F6E3B](<Notebook/Hewlett-Packard/Laptop/Laptop 14-dk0xxx/60E15DE8A8F4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/E7B40F6E3B>) |
| 1022:15e2 | 103c:8730 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [C6944AFE69](<Notebook/Hewlett-Packard/ProBook/ProBook 455 G7/54DBBDB85625/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/C6944AFE69>) |
| 1022:15e2 | 103c:8786 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [19F307FF6D](<Notebook/Hewlett-Packard/OMEN/OMEN Laptop 15-en0xxx/99830226F687/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/19F307FF6D>) |
| 1022:15e2 | 103c:87b1 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [B8408CB369](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec1xxx/447033DB0DB6/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/B8408CB369>) |
| 1022:15e2 | 103c:88dd | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [7859F220B9](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec2xxx/32343F8FB2CF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7859F220B9>) |
| 1022:15e2 | 1043:115f | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [2048FF5F71](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX325UA_UM325UA/49BFF737ADD5/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/2048FF5F71>) |
| 1022:15e2 | 17aa:32e1 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [B394504429](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75s Gen 2 11R8000JUS/C14D7D997EB5/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/B394504429>) |
| 1022:15e2 | 17aa:3838 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [4F31F81571](<Notebook/Lenovo/IdeaPad/IdeaPad Gaming 3 15ACH6 82K2/F2EDB3DDA79E/GHOSTBSD-22.08.23/13.1-STABLE/AMD64/4F31F81571>) |
| 1022:15e2 | 17aa:5081 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [D910C79D75](<Notebook/Lenovo/ThinkPad/ThinkPad P14s Gen 1 20Y1CTO1WW/5E03AED6E452/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D910C79D75>) |
| 1022:15e2 | 17aa:5126 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [D7812A2905](<Notebook/Lenovo/ThinkPad/ThinkPad X395 20NL000GPG/878AD42630E7/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/D7812A2905>) |
| 1022:15e2 | 1ec9:3e3a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 2     |            | [CED12F0B41](<Notebook/HUAWEI/CREM-WXX/CREM-WXX9/2FA12EEB45B2/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/CED12F0B41>) |
| 8086:0f38 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     |            | [2ECB6FABA3](<Mini Pc/AMI/Aptio/Aptio CRB/FEA9A2F7C9FB/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2ECB6FABA3>) |
| 1022:15e2 | 1025:134d | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [1AC21E1660](<Notebook/Acer/Aspire/Aspire A315-42/DE5FD26538FB/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/1AC21E1660>) |
| 1022:15e2 | 1025:142b | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [6A579DCA44](<Notebook/Acer/Swift/Swift SF314-42/2786DB3ED567/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/6A579DCA44>) |
| 1022:15e2 | 1025:1456 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [7FB743C654](<Notebook/Acer/Aspire/Aspire A315-23/F20A633E5003/FREEBSD-13.0/13.0-RELEASE/AMD64/7FB743C654>) |
| 1022:15e2 | 1025:1524 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [991F67362F](<Notebook/Acer/Aspire/Aspire A715-42G/87795F16AC00/FREEBSD-13.1-RC6/13.1-RC6/AMD64/991F67362F>) |
| 1022:15e2 | 1028:09f5 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [9933A09C4F](<Notebook/Dell/G5/G5 5505/919E52ABE5A8/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/9933A09C4F>) |
| 1022:15e2 | 1028:0a79 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [EF6D4EE660](<Notebook/Dell/Vostro/Vostro 5415/1C3D260A91E2/FREEBSD-13.1/13.1-RELEASE/AMD64/EF6D4EE660>) |
| 1022:15e2 | 103c:8433 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [5A242D9C9E](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop 590-p0xxx/0CFBD160A1EE/FREEBSD-12.2/12.2-RELEASE/AMD64/5A242D9C9E>) |
| 1022:15e2 | 103c:8522 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15e2 | 103c:8523 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:15e2 | 103c:85b3 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [ECF07AD5FE](<Notebook/Hewlett-Packard/Laptop/Laptop 17-ca1xxx/17899E306221/FREEBSD-12.2-P2/12.2-RELEASE/AMD64/ECF07AD5FE>) |
| 1022:15e2 | 103c:876e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [EEC9546431](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 13-ay0xxx/4A78C43B26DF/FREEBSD-13.1-P1/13.1-RELEASE/AMD64/EEC9546431>) |
| 1022:15e2 | 103c:87b0 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [3C11FC31B2](<Notebook/Hewlett-Packard/Pavilion/Pavilion Gaming Laptop 15-ec1xxx/E24767B1152C/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3C11FC31B2>) |
| 1022:15e2 | 103c:87b7 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [920A2FE2E9](<Notebook/Hewlett-Packard/Laptop/Laptop 14s-fq0xxx/0E6414342B08/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/920A2FE2E9>) |
| 1022:15e2 | 103c:888a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:15e2 | 103c:8905 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [F9851A3257](<Notebook/Hewlett-Packard/255/255 G8 Notebook PC/A80D2FBEF333/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/F9851A3257>) |
| 1022:15e2 | 1043:1862 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [CF360A6098](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X515UA_M515UA/E0D904EE5AF7/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/CF360A6098>) |
| 1022:15e2 | 1043:1d42 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [20CDC9D999](<Notebook/ASUSTek Computer/ROG/ROG Zephyrus G14 GA402RJ_GA402RJ/8B17C1C0752C/FREEBSD-13.0/13.0-RELEASE/AMD64/20CDC9D999>) |
| 1022:15e2 | 1458:1000 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [817CB3E603](<Desktop/Gigabyte Technology/BSRE/BSRE-1605/493093EBE60A/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/817CB3E603>) |
| 1022:15e2 | 1462:12b5 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [1868573E9A](<Notebook/MSI/Bravo/Bravo 15 A4DDR/3C4CE3C2FC4B/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/1868573E9A>) |
| 1022:15e2 | 152d:126b | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [D259128717](<Notebook/HUAWEI/NBLL-WXX/NBLL-WXX9/B67AF48698C7/FREEBSD-13.1-RC3/13.1-RC2/AMD64/D259128717>) |
| 1022:15e2 | 17aa:318e | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [115F2C7B35](<Desktop/Lenovo/ThinkCentre/ThinkCentre M75t Gen 2 11KECTO1WW/85187679911A/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/115F2C7B35>) |
| 1022:15e2 | 17aa:3190 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1022:15e2 | 17aa:3708 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [E68D7A5DFF](<Desktop/Lenovo/IdeaCentre/IdeaCentre 3 07ADA05 90MV007UGE/ECBF6B871AD1/OPNSENSE-22.1.9/13.0-STABLE/AMD64/E68D7A5DFF>) |
| 1022:15e2 | 17aa:3728 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [7BA1CCC40D](<Desktop/Lenovo/IdeaCentre/IdeaCentre 5 14ARE05 90Q30008US/2ECD21E7A105/FREEBSD-12.2-P8/12.2-RELEASE-P8/AMD64/7BA1CCC40D>) |
| 1022:15e2 | 17aa:3807 | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [DEC7108B53](<Notebook/Lenovo/IdeaPad/IdeaPad 3 15ADA05 81W1/393F56D2B880/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DEC7108B53>) |
| 1022:15e2 | 17aa:380b | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [560213A2D6](<Notebook/Lenovo/IdeaPad/IdeaPad 530S-14ARR 81H1/CC5963244111/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/560213A2D6>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 159   | em         | [81BBACBFEE](<Firewall/Sophos/UTM/UTM/D0D282702135/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/81BBACBFEE>) |
| 8086:15f3 |           | Intel            | Ethernet Controller I225-V           | 153   | igc        | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 143   | igb        | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 99    | igb        | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 10ec:8168 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 73    | re         | [718C9C5C8B](<Desktop/Dell/Vostro/Vostro 200/707470A7CBAA/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/718C9C5C8B>) |
| 8086:1521 | 8086:5001 | Intel            | I350 Gigabit Network Connection      | 69    | igb        | [4091E15CAC](<Desktop/Dell/Precision/Precision 3440/AC9368A7D243/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/4091E15CAC>) |
| 10ec:8168 | 1734:11ff | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 66    | re         | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 66    | igb        | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 10ec:8125 | 10ec:0123 | Realtek Semic... | RTL8125 2.5GbE Controller            | 62    | re         | [D9376F2F63](<Desktop/ASUSTek Computer/PRIME/PRIME B450M-A II/8D63433E0169/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/D9376F2F63>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 62    | re         | [D316352C20](<Desktop/Acer/Aspire/Aspire X5810/21552B3F601D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D316352C20>) |
| 8086:1539 | 1849:1539 | Intel            | I211 Gigabit Network Connection      | 55    | igb        | [A40ADA7F7F](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A40ADA7F7F>) |
| 8086:10e8 | 8086:a02c | Intel            | 82576 Gigabit Network Connection     | 54    | igb        | [35ECAF0406](<Desktop/Fujitsu/FUTRO/FUTRO S920/E8847EBE713D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/35ECAF0406>) |
| 8086:10bc | 103c:704b | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 52    | em         | [E23F822438](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-F GAMING WIFI/83B0E22D5F39/OPNSENSE-22.1.10/13.0-STABLE/AMD64/E23F822438>) |
| 8086:150e | 103c:1780 | Intel            | 82580 Gigabit Network Connection     | 51    | igb        | [5DAFBBCED0](<Desktop/Fujitsu/ESPRIMO/ESPRIMO E420/4D8E7E4EFB3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5DAFBBCED0>) |
| 1022:1458 | 1022:1458 | AMD              | Family 17h Processor 10 Gb Ethern... | 46    | ax         | [21E1293019](<Notebook/Deciso/OPNsense/OPNsense Appliance/F166BECF86AB/OPNSENSE-22.10/13.1-RELEASE-P5/AMD64/21E1293019>) |
| 8086:1521 |           | Intel            | I350 Gigabit Network Connection      | 46    | igb        | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 14e4:163b | 1028:04dd | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 43    | bce        | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:105e | 8086:125e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 42    | em         | [8DE4FF8626](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/CDAF2C982352/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/8DE4FF8626>) |
| 8086:1502 | 1028:052c | Intel            | 82579LM Gigabit Network Connectio... | 40    | em         | [B6EC2E7E28](<Desktop/Dell/OptiPlex/OptiPlex 7010/92F0DFFBABB2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B6EC2E7E28>) |
| 8086:1572 |           | Intel            | Ethernet Controller X710 for 10Gb... | 40    | ixl        | [6715EE2886](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 SFF/8FDD671A35D3/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6715EE2886>) |
| 8086:15e5 |           | Intel            | Ethernet Connection X553 1GbE        | 40    | ix         | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 8086:125c |           | Intel            | Ethernet Controller I226-V           | 39    | igc        | [0F727C761B](<Desktop/Others/Others/Others/5D44760B2901/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0F727C761B>) |
| 8086:15e4 |           | Intel            | Ethernet Connection X553 1GbE        | 36    | ix         | [C3B95220D7](<Desktop/Others/Others/Others/D9CD07BFB6A4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C3B95220D7>) |
| 10ec:8168 | 103c:8103 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 34    | re         | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:1536 |           | Intel            | I210 Gigabit Fiber Network Connec... | 34    | igb        | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 8086:1533 | 15bb:30e0 | Intel            | I210 Gigabit Network Connection      | 32    | igb        | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 31    | nfe        | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 10ec:8168 | 1028:0612 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 31    | re         | [D4296FD9D8](<Desktop/Dell/OptiPlex/OptiPlex 3020/F9299AC8F1C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4296FD9D8>) |
| 8086:15ac | 15d9:15ac | Intel            | Ethernet Connection X552 10 GbE SFP+ | 31    | ix         | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:1f41 | 15d9:1f41 | Intel            | Ethernet Connection I354             | 31    | igb        | [FB96378782](<Server/Supermicro/A1/A1SRM-2758F/F38A17AAB757/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FB96378782>) |
| 8086:10c9 | 8086:a02f | Intel            | 82576 Gigabit Network Connection     | 30    | igb        | [D4296FD9D8](<Desktop/Dell/OptiPlex/OptiPlex 3020/F9299AC8F1C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4296FD9D8>) |
| 8086:10bc | 8086:11bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 28    | em         | [A12907D76A](<Server/Dell/PowerEdge/PowerEdge R200/4AC27B58A736/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A12907D76A>) |
| 8086:15b8 | 1043:8672 | Intel            | Ethernet Connection (2) I219-V       | 27    | em         | [D44C580408](<Desktop/ASUSTek Computer/STRIX/STRIX Z270I GAMING/FF945A143CA8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/D44C580408>) |
| 10ec:8169 | 10ec:8169 | Realtek Semic... | RTL8169 PCI Gigabit Ethernet Cont... | 26    | re         | [F2A248DCFE](<Desktop/ASUSTek Computer/All/All Series/723B3BFDA016/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/F2A248DCFE>) |
| 14e4:165f | 1028:1f5b | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 26    | bge        | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 25    | ix         | [04EA3CC97D](<Desktop/ASUSTek Computer/P8/P8H77-I/C263747DB078/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/04EA3CC97D>) |
| 14e4:1639 | 103c:7055 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 22    | bce        | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:10c9 | 1dcf:0319 | Intel            | 82576 Gigabit Network Connection     | 22    | igb        | [3E3B056CDF](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/36C252462A40/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/3E3B056CDF>) |
| 8086:1528 | 8086:0001 | Intel            | Ethernet Controller 10-Gigabit X5... | 22    | ix         | [3FAAAA8209](<Desktop/ASUSTek Computer/PRIME/PRIME X470-PRO/837435F7D2A1/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3FAAAA8209>) |
| 8086:153a | 103c:1998 | Intel            | Ethernet Connection I217-LM          | 22    | em         | [AFC7DE60E3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/CB6EAA64FCFB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/AFC7DE60E3>) |
| 10ec:8168 | 19da:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 21    | re         | [08D401FA34](<Desktop/Datto/SSD/SSD/E2D453D5DD81/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/08D401FA34>) |
| 8086:10bc | 8086:10bc | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 21    | em         | [3124AAAF95](<Desktop/Fujitsu/FUTRO/FUTRO S920/A1AC5CC7301E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3124AAAF95>) |
| 8086:10d6 | 8086:145a | Intel            | 82575GB Gigabit Network Connection   | 21    | igb        | [794E041B13](<Desktop/Gigabyte Technology/B450M/B450M DS3H/2947F86E358F/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/794E041B13>) |
| 8086:1502 | 15d9:1502 | Intel            | 82579LM Gigabit Network Connectio... | 21    | em         | [FE44242C3B](<Desktop/Supermicro/X9/X9SCL-X9SCM/0C3EBAE8F4DF/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/FE44242C3B>) |
| 8086:1516 | 8086:12b2 | Intel            | 82580 Gigabit Network Connection     | 21    | igb        | [1F1DE1D49C](<Desktop/Lenovo/ThinkCentre/ThinkCentre M900 10FGS0W200/BD2B6EBD1873/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/1F1DE1D49C>) |
| 10ec:8168 | 1028:080c | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 20    | re         | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 14e4:165b | 103c:705d | Broadcom         | NetXtreme BCM5723 Gigabit Etherne... | 20    | bge        | [50C8CB79F7](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.4/12.4-RELEASE/AMD64/50C8CB79F7>) |
| 8086:1522 |           | Intel            | I350 Gigabit Fiber Network Connec... | 20    | igb        | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 8086:37d0 | 15d9:37d0 | Intel            | Ethernet Connection X722 for 10Gb... | 20    | ixl        | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |
| 8086:154d | 8086:7b11 | Intel            | Ethernet 10G 2P X520 Adapter         | 19    | ix         | [21F838983B](<Desktop/ASUSTek Computer/P11C-M/P11C-M Series/E4D1817AC6A4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/21F838983B>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 124   | iwlwifi    | [009EF73BD1](<Desktop/ASRock/4X4-4000/4X4-4000 Series/ACBB8335DDB2/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/009EF73BD1>) |
| 8086:0085 | 8086:1311 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 77    | iwn        | [9A3CBE1893](<Notebook/Lenovo/ThinkPad/ThinkPad T530 2392AQU/F63B1985C532/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/9A3CBE1893>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 69    | iwm        | [79D8B1477F](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/1AD0770658A0/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/79D8B1477F>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 65    | iwm        | [570B96D0F7](<Notebook/Acer/Aspire/Aspire ES1-533/EDA879F45C6A/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/570B96D0F7>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 61    | iwm        | [B8C89BDCA8](<Desktop/Supermicro/X9/X9DR3-F/3573CEE1CD7B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8C89BDCA8>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 45    | iwm        | [683591700F](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MVS0LG00/F4E54EA14D75/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/683591700F>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 43    | iwm        | [932FACD689](<Notebook/Sony/SVP1321/SVP1321V9RB/6234B05DFA77/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/932FACD689>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 41    | iwm        | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 33    | iwm        | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 8086:08b2 | 8086:c270 | Intel            | Wireless 7260                        | 28    | iwm        | [DF62882C3B](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AR003SMN/FE0FBD6135B1/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/DF62882C3B>) |
| 8086:095b | 8086:5210 | Intel            | Wireless 7265                        | 28    | iwm        | [7708C4BB19](<Notebook/Lenovo/ThinkPad/ThinkPad T450s 20BXCTO1WW/C49A61555568/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7708C4BB19>) |
| 168c:002a | 168c:3099 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 26    | ath        | [588E065800](<Desktop/PC Engines/apu/apu4/16CEEA5443CA/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/588E065800>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 26    | ath        | [B8BFDEC836](<Notebook/ASUSTek Computer/K50/K50IN/649EA35E6EC2/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8BFDEC836>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 26    | iwm        | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 25    | rtw        | [23D8A9BDA7](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/BD57B07B0D05/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/23D8A9BDA7>) |
| 8086:088e | 8086:4060 | Intel            | Centrino Advanced-N 6235             | 25    | iwn        | [54E89EF90B](<Desktop/Others/Others/Others/877024CF7AD9/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/54E89EF90B>) |
| 8086:24f3 | 8086:0130 | Intel            | Wireless 8260                        | 24    | iwm        | [3A9623CFB4](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FN002JUS/8E643E12C08D/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/3A9623CFB4>) |
| 8086:a370 | 8086:0034 | Intel            | Cannon Lake PCH CNVi WiFi            | 24    | iwm        | [57C3A4005A](<Notebook/Acidanthera/MacBookPro15/MacBookPro15,1/6C4D9581A214/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/57C3A4005A>) |
| 8086:08b1 | 8086:4470 | Intel            | Wireless 7260                        | 23    | iwm        | [8B634987B4](<Mini Pc/Shuttle/XS35/XS35V5/4F433C551703/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/8B634987B4>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 23    | iwm        | [AC867149F2](<Desktop/Lenovo/ThinkCentre/ThinkCentre M700 10GRCTO1WW/DF34312EB46C/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/AC867149F2>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 22    | iwm        | [2F701B55FC](<Desktop/ZOTAC/Others/Others/9EC819E4E991/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2F701B55FC>) |
| 8086:24f3 | 8086:0010 | Intel            | Wireless 8260                        | 22    | iwm        | [149E5C3DE3](<Notebook/Toshiba/TECRA/TECRA Z40-C-12Z/7250A1A24FA6/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/149E5C3DE3>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 22    | iwm        | [D73EF4F4FC](<Desktop/AZW/GK/GK55/8FD2B3239B52/OPNSENSE-22.1.10/13.0-STABLE/AMD64/D73EF4F4FC>) |
| 8086:24f3 | 8086:1010 | Intel            | Wireless 8260                        | 21    | iwm        | [1D3CCD1FE6](<Notebook/Lenovo/Yoga/Yoga 710-11IKB 80V6/2D9DC056B8D8/NOMADBSD-20221130/13.1-RELEASE-P3/AMD64/1D3CCD1FE6>) |
| 8086:24fd | 8086:0050 | Intel            | Wireless 8265 / 8275                 | 21    | iwm        | [0A17F04EBA](<Notebook/Dell/Latitude/Latitude 5590/F18891120942/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/0A17F04EBA>) |
| 8086:2725 | 8086:0024 | Intel            | Wi-Fi 6 AX210/AX211/AX411 160MHz     | 21    | iwlwifi    | [DE5BF4B420](<Desktop/Gigabyte Technology/X99-Designare/X99-Designare EX-CF/DEC9F2C04D03/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/DE5BF4B420>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 19    |            | [14F174BD7C](<Mini Pc/BESSTAR Tech/GK/GK41/46F6D804D9F8/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/14F174BD7C>) |
| 8086:08b1 | 8086:4070 | Intel            | Wireless 7260                        | 19    | iwm        | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:24f3 | 8086:0050 | Intel            | Wireless 8260                        | 19    | iwm        | [E08C408CED](<Desktop/Lenovo/ThinkCentre/ThinkCentre M920s 10SJ0011US/88754028E03C/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/E08C408CED>) |
| 168c:0036 | 1028:020c | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 18    | ath        | [529CBAB9AA](<Notebook/Dell/Inspiron/Inspiron 3442/CBD4060BB169/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/529CBAB9AA>) |
| 168c:003c |           | Qualcomm Atheros | QCA986x/988x 802.11ac Wireless Ne... | 18    |            | [5597CCA988](<Desktop/PC Engines/APU/APU3/38F313B93C83/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5597CCA988>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 18    | iwlwifi    | [638E327C4E](<Desktop/MSI/CML-U/CML-U PRO Cubi 5/110C3F90DC1E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638E327C4E>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 18    | iwm        | [9130257C6A](<Mini Pc/Intel/NUC5/NUC5i5RYH/8029C52A44DE/OPNSENSE-22.7/13.1-RELEASE/AMD64/9130257C6A>) |
| 8086:31dc | 8086:0034 | Intel            | Gemini Lake PCH CNVi WiFi            | 18    | iwm        | [7729EC0863](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/D86192E67FF2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7729EC0863>) |
| 8086:0084 | 8086:1315 | Intel            | Centrino Wireless-N 1000 [Condor ... | 16    | iwn        | [A697BE2AA9](<Notebook/Lenovo/ThinkPad/ThinkPad L420 7829WDY/20348E698FCF/FREEBSD-13.1/13.1-RELEASE/AMD64/A697BE2AA9>) |
| 14e4:4331 | 14e4:4331 | Broadcom         | BCM4331 802.11a/b/g/n                | 15    | bwn_pci    | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 8086:3165 | 8086:4410 | Intel            | Wireless 3165                        | 15    | iwm        | [B2F0DA8246](<Desktop/Dell/Inspiron/Inspiron 3880/DECD973F3D35/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B2F0DA8246>) |
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 14    | bwn_pci    | [BC15367E9F](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BC15367E9F>) |
| 168c:002e | 168c:30a4 | Qualcomm Atheros | AR9287 Wireless Network Adapter (... | 14    | ath        | [92EAB8D065](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING II/1AD27D04291F/HELLOSYSTEM-0.7.0/13.1-RELEASE-P3/AMD64/92EAB8D065>) |
| 8086:0082 | 8086:1321 | Intel            | Centrino Advanced-N 6205 [Taylor ... | 14    | iwn        | [EA99621380](<Notebook/Dell/Latitude/Latitude E7240/4A55E51D2962/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/EA99621380>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 14    | iwm        | [0D6E868D9C](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/0D6E868D9C>) |
| 8086:4238 | 8086:1111 | Intel            | Centrino Ultimate-N 6300             | 14    | iwn        | [6515A18552](<Notebook/Lenovo/ThinkPad/ThinkPad W530 2436CTO/A750F9599EB4/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/6515A18552>) |
| 8086:4239 | 8086:1311 | Intel            | Centrino Advanced-N 6200             | 14    | iwn        | [CBA0FC2340](<Notebook/Lenovo/ThinkPad/ThinkPad L412 0585AD9/A37928EB0C1B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/CBA0FC2340>) |
| 14e4:432b | 106b:008d | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 13    | bwn_pci    | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 8086:06f0 | 8086:0074 | Intel            | Comet Lake PCH CNVi WiFi             | 13    | iwlwifi    | [2EA7C7F9A2](<Notebook/MSI/GL65/GL65 Leopard 10SFSK/368D052757DD/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/2EA7C7F9A2>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 13    | iwm        | [2048FF5F71](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX325UA_UM325UA/49BFF737ADD5/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/2048FF5F71>) |
| 8086:422b | 8086:1121 | Intel            | Centrino Ultimate-N 6300             | 13    | iwn        | [A3DA09AE5E](<Notebook/Dell/Latitude/Latitude E6540/C25E592FE79A/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/A3DA09AE5E>) |
| 14e4:4328 | 106b:0088 | Broadcom         | BCM4321 802.11a/b/g/n                | 12    | bwn_pci    | [015F0A0A6D](<Notebook/Apple/MacBook4/MacBook4,1/6880EB6211C0/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/015F0A0A6D>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 12    | ath        | [76674E4D62](<Desktop/Dell/OptiPlex/OptiPlex 7040/3E5E7C935983/HELLOSYSTEM-0.7.0/13.0-RELEASE-P11/AMD64/76674E4D62>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 12    | ath        | [EEA4262AF2](<Notebook/Dell/Inspiron/Inspiron 15-3552/1ED960B9F220/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/EEA4262AF2>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 817   | igb        | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 468   | re         | [A8ECE272AF](<Desktop/Fujitsu/ESPRIMO/ESPRIMO A525-L/ABE92B86984A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A8ECE272AF>) |
| 8086:157b |           | Intel            | I210 Gigabit Network Connection      | 294   | igb        | [21E1293019](<Notebook/Deciso/OPNsense/OPNsense Appliance/F166BECF86AB/OPNSENSE-22.10/13.1-RELEASE-P5/AMD64/21E1293019>) |
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 203   | re         | [5D287163C9](<Desktop/Gigabyte Technology/GB-BXi7/GB-BXi7-5775R/BF425CFC0EFE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5D287163C9>) |
| 10ec:8168 | 1849:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 167   | re         | [80C809E992](<Desktop/ASRock/N3710-NUC/N3710-NUC IPC/E0800AE12493/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/80C809E992>) |
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 130   | igb        | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 124   | em         | [B6EC2E7E28](<Desktop/Dell/OptiPlex/OptiPlex 7010/92F0DFFBABB2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B6EC2E7E28>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 123   | em         | [FA30F060F3](<Desktop/Intel/CARLOW/CARLOW/34C34A8491A2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/FA30F060F3>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 107   | re         | [2265227A5C](<Desktop/Fujitsu/ESPRIMO/ESPRIMO E3521/7DED359178AD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/2265227A5C>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 101   | re         | [334575B738](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/A1AB004D09A5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/334575B738>) |
| 10ec:8168 | 1043:8505 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 52    | re         | [10B6C81BCE](<Desktop/ASUSTek Computer/P8H77-V/P8H77-V LE/EEA085D70636/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/10B6C81BCE>) |
| 8086:1502 | 17aa:21ce | Intel            | 82579LM Gigabit Network Connectio... | 51    | em         | [18A105546B](<Notebook/Lenovo/ThinkPad/ThinkPad T420 4178A72/D34F6DFF555D/HELLOSYSTEM-0.8.0/14.0-CURRENT/AMD64/18A105546B>) |
| 8086:153a | 1028:05a4 | Intel            | Ethernet Connection I217-LM          | 49    | em         | [910C2BBA4A](<Desktop/Dell/OptiPlex/OptiPlex 7020/DF8617B3437C/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/910C2BBA4A>) |
| 8086:150e | 8086:12a2 | Intel            | 82580 Gigabit Network Connection     | 47    | igb        | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 46    | re         | [1A183385C7](<Desktop/ASUSTek Computer/E35M1-I/E35M1-I DELUXE/6D5B2DE1974F/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/1A183385C7>) |
| 8086:1502 | 17aa:21f3 | Intel            | 82579LM Gigabit Network Connectio... | 46    | em         | [9A3CBE1893](<Notebook/Lenovo/ThinkPad/ThinkPad T530 2392AQU/F63B1985C532/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/9A3CBE1893>) |
| 10ec:8168 | 103c:213d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 43    | re         | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 40    | igb        | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 8086:105e | 103c:7044 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 39    | em         | [03176E6683](<Desktop/MSI/MS/MS-7721/B111ACD1D9CF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/03176E6683>) |
| 8086:1539 | 1043:85f0 | Intel            | I211 Gigabit Network Connection      | 39    | igb        | [2E842DDB27](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/2E842DDB27>) |
| 8086:1539 | 1458:e000 | Intel            | I211 Gigabit Network Connection      | 35    | igb        | [DE5BF4B420](<Desktop/Gigabyte Technology/X99-Designare/X99-Designare EX-CF/DEC9F2C04D03/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/DE5BF4B420>) |
| 8086:105e | 8086:135e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 34    | em         | [F321130F0E](<Desktop/Fujitsu/FUTRO/FUTRO S920/1A21E5A60999/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/F321130F0E>) |
| 10ec:8139 | 10ec:8139 | Realtek Semic... | RTL-8100/8101L/8139 PCI Fast Ethe... | 31    | rl         | [718C9C5C8B](<Desktop/Dell/Vostro/Vostro 200/707470A7CBAA/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/718C9C5C8B>) |
| 8086:1521 | 8086:0002 | Intel            | I350 Gigabit Network Connection      | 31    | igb        | [4C3B92BB42](<Desktop/ASUSTek Computer/PRIME/PRIME B550-PLUS/8A74BD626C47/MYBEE-13.1-P3/13.1-RELEASE-P3/AMD64/4C3B92BB42>) |
| 10ec:8168 | 1043:8554 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 30    | re         | [DC487B5779](<Desktop/ASUSTek Computer/A55/A55BM-K/50FAB363D9A3/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DC487B5779>) |
| 14e4:165f | 103c:2133 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 30    | bge        | [A2BC442ACD](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/DE1062729CEF/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/A2BC442ACD>) |
| 8086:105e | 8086:115e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 29    | em         | [910C2BBA4A](<Desktop/Dell/OptiPlex/OptiPlex 7020/DF8617B3437C/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/910C2BBA4A>) |
| 8086:1502 | 1028:047e | Intel            | 82579LM Gigabit Network Connectio... | 29    | em         | [7FABC0CB8A](<Desktop/Dell/OptiPlex/OptiPlex 990/10E9E1EE10F3/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7FABC0CB8A>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 26    | bge        | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 8086:1528 | 15d9:1528 | Intel            | Ethernet Controller 10-Gigabit X5... | 26    | ix         | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 26    | ixl        | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 24    | em         | [7521108EF5](<Desktop/Infoblox/IB/IB-1410/9EA796062C0A/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7521108EF5>) |
| 8086:1533 | 1849:1533 | Intel            | I210 Gigabit Network Connection      | 23    | igb        | [106E525671](<Desktop/ASRock/E3/E3C224D2I/B67321B4991A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/106E525671>) |
| 8086:15a2 | 17aa:2226 | Intel            | Ethernet Connection (3) I218-LM      | 23    | em         | [10619AC217](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLS5BU00/75926791E302/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/10619AC217>) |
| 8086:10ea | 17aa:2153 | Intel            | 82577LM Gigabit Network Connection   | 21    | em         | [A1561DACB2](<Notebook/Lenovo/ThinkPad/ThinkPad T410 2522CS7/3C98BD93E6E5/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/A1561DACB2>) |
| 8086:107c | 8086:1376 | Intel            | 82541PI Gigabit Ethernet Controller  | 20    | em         | [734FF7F48C](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/93F9F29A0DC5/OPNSENSE-20.7.5/12.1-RELEASE-P10-HBSD/AMD64/734FF7F48C>) |
| 11ab:4364 | 1043:81f8 | Marvell Techn... | 88E8056 PCI-E Gigabit Ethernet Co... | 19    | mskc       | [BC829DBB1A](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/BC829DBB1A>) |
| 8086:156f | 17aa:2233 | Intel            | Ethernet Connection I219-LM          | 19    | em         | [3A9623CFB4](<Notebook/Lenovo/ThinkPad/ThinkPad T460 20FN002JUS/8E643E12C08D/GHOSTBSD-22.11.22/13.1-STABLE/AMD64/3A9623CFB4>) |
| 10ec:8168 | 1043:859e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 18    | re         | [F2A248DCFE](<Desktop/ASUSTek Computer/All/All Series/723B3BFDA016/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/F2A248DCFE>) |
| 14e4:1639 | 1028:0235 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 18    | bce        | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 8086:10fb | 8086:0003 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 18    | ix         | [F25480C54A](<Desktop/MSI/MS/MS-7922/8FCF1BD7C6F6/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/F25480C54A>) |
| 10ec:8168 | 1043:200f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 17    | re         | [431AD10AB2](<Notebook/ASUSTek Computer/X455/X455LJ/388EF8EA953C/FREEBSD-13.1/13.1-RELEASE/AMD64/431AD10AB2>) |
| 14e4:165f | 103c:22e8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 17    | bge        | [F1B45790D4](<Desktop/HPE/ProLiant/ProLiant ML30 Gen10/93F91BA1C4A9/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/F1B45790D4>) |
| 8086:15b7 |           | Intel            | Ethernet Connection (2) I219-LM      | 17    | em         | [0A40B02AEB](<Desktop/Others/Others/Others/FB93D11DB736/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0A40B02AEB>) |
| 8086:15b8 | 1458:e000 | Intel            | Ethernet Connection (2) I219-V       | 17    | em         | [C121BAD3FB](<Desktop/Gigabyte Technology/H110/H110TN/8D83ECAF1254/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/C121BAD3FB>) |
| 10ec:8125 | 1849:8125 | Realtek Semic... | RTL8125 2.5GbE Controller            | 16    | re         | [009EF73BD1](<Desktop/ASRock/4X4-4000/4X4-4000 Series/ACBB8335DDB2/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/009EF73BD1>) |
| 15b3:1003 | 15b3:0055 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 15    | mlx4_core  | [33C1878560](<Desktop/Brian Kabela/Game/Game Station 1/A3F0D23DEDB7/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/33C1878560>) |
| 8086:150e | 1734:11a8 | Intel            | 82580 Gigabit Network Connection     | 15    | igb        | [D3D1107F77](<Desktop/Biostar/A10/A10N-8800E/940DAEB9E452/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D3D1107F77>) |
| 8086:155a | 17aa:2214 | Intel            | Ethernet Connection I218-LM          | 15    | em         | [DF62882C3B](<Notebook/Lenovo/ThinkPad/ThinkPad T440s 20AR003SMN/FE0FBD6135B1/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/DF62882C3B>) |
| 8086:15bc | 1043:8672 | Intel            | Ethernet Connection (7) I219-V       | 14    | em         | [7329E04C22](<Desktop/ASUSTek Computer/PRIME/PRIME Z390M-PLUS/65319FEDDF03/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/7329E04C22>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 246   | sdhci_pci  | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 79    | sdhci_pci  | [B685DDC2AD](<Desktop/Hardkernel/ODROID-H/ODROID-H2/2813F39855C7/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B685DDC2AD>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 65    | sdhci_pci  | [108C9DE5CC](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/A01D26C2C94F/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/108C9DE5CC>) |
| 8086:31d0 | 8086:7270 | Intel            | SD Host Controller                   | 41    | sdhci_pci  | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:4df8 | 8086:7270 | Intel            | SD Host Controller                   | 40    | sdhci_pci  | [1DAB2C420A](<Desktop/Others/Others/Others/7DC26823CFA8/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/1DAB2C420A>) |
| 14e4:16bc |           | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 33    | sdhci_pci  | [07DC4A3178](<All In One/Apple/iMac14/iMac14,2/07EF6154280E/FREEBSD-13.1/13.1-RELEASE/AMD64/07DC4A3178>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 24    | sdhci_pci  | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:9dc4 | 8086:7270 | Intel            | Cannon Point-LP SD Host Controller   | 24    | sdhci_pci  | [A6D41C71FD](<Desktop/Others/Others/Others/F9DEED394CD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A6D41C71FD>) |
| 8086:9df5 | 8086:7270 | Intel            | BayHubTech Integrated SD controller  | 24    | sdhci_pci  | [A6D41C71FD](<Desktop/Others/Others/Others/F9DEED394CD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A6D41C71FD>) |
| 8086:31cc | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 22    | sdhci_pci  | [3737D80840](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/8244BD729AFF/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3737D80840>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 20    | sdhci_pci  | [AB45092607](<Desktop/AMI/PICO/PICO PC/534273DA9C80/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/AB45092607>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 15    | sdhci_pci  | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 8086:19db | 8086:7270 | Intel            | Atom Processor C3000 Series SD Ho... | 14    | sdhci_pci  | [C3B95220D7](<Desktop/Others/Others/Others/D9CD07BFB6A4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C3B95220D7>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 14    | sdhci_pci  | [A8D73A9156](<Desktop/AAEON/UP-APL/UP-APL01/F783FC8D281F/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/A8D73A9156>) |
| 8086:5acc | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | sdhci_pci  | [7BFFFA2718](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/23C08CCB2571/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/7BFFFA2718>) |
| 1180:0822 | 17aa:20c8 | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 12    | sdhci_pci  | [1F37EBF2BB](<Notebook/Lenovo/ThinkPad/ThinkPad X61 Tablet 7763AD6/A465667EA04A/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/1F37EBF2BB>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | sdhci_pci  | [EBEDB51D2F](<Mini Pc/CompuLab/fitlet/fitlet2/66D2086CBC5D/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/EBEDB51D2F>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 8     | sdhci_pci  | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:02c4 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS1: eMMC         | 8     | sdhci_pci  | [E467080570](<Notebook/Medion/E/E15415/B5081BB45457/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/E467080570>) |
| 8086:31cc | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 8     | sdhci_pci  | [CAC58D91B6](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/81C544E74614/OPNSENSE-22.1.10/13.0-STABLE/AMD64/CAC58D91B6>) |
| 8086:5acc | 8086:5acc | Intel            | Celeron N3350/Pentium N4200/Atom ... | 8     | sdhci_pci  | [B75D6C6581](<Desktop/IceWhale Technology/ZimaBoard/ZimaBoard 216 ZMB/08DAC47BB616/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B75D6C6581>) |
| 197b:2381 | 17aa:212d | JMicron Techn... | Standard SD Host Controller          | 7     | sdhci_pci  | [CBA0FC2340](<Notebook/Lenovo/ThinkPad/ThinkPad L412 0585AD9/A37928EB0C1B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/CBA0FC2340>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 7     | sdhci_pci  | [C3FFB2C87D](<Desktop/AMI/PEISIA/PEISIA E3845 VER1.0/F1AF209585D4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C3FFB2C87D>) |
| 1180:e822 | 1179:0001 | Ricoh            | MMC/SD Host Controller               | 6     | sdhci_pci  | [10B85ECCAE](<Notebook/Toshiba/PORTEGE/PORTEGE R700/AC5712689798/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/10B85ECCAE>) |
| 1217:8221 | 1028:0493 | O2 Micro         | OZ600FJ0/OZ900FJ0/OZ600FJS SD/MMC... | 6     | sdhci_pci  | [48C26D2A17](<Notebook/Dell/Latitude/Latitude E6420/CEE321BEE6B2/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/48C26D2A17>) |
| 1217:8221 | 1028:0534 | O2 Micro         | OZ600FJ0/OZ900FJ0/OZ600FJS SD/MMC... | 6     | sdhci_pci  | [B8F950DE05](<Notebook/Dell/Latitude/Latitude E6430/286A8E5F2DC1/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8F950DE05>) |
| 8086:02f5 | 8086:7270 | Intel            | Comet Lake PCH-LP SCS3               | 6     | sdhci_pci  | [E467080570](<Notebook/Medion/E/E15415/B5081BB45457/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/E467080570>) |
| 8086:a375 | 103c:843f | Intel            | 300 Series Chipset Family SD Host... | 6     | sdhci_pci  | [23D8A9BDA7](<Desktop/Hewlett-Packard/Slim/Slim Desktop 290-p0xxx/BD57B07B0D05/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/23D8A9BDA7>) |
| 1022:7806 | 1022:7806 | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [511F2A6D16](<Desktop/Hewlett-Packard/Pro/Pro 3405 Series/195D130691D4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/511F2A6D16>) |
| 1022:7813 | 1022:7813 | AMD              | FCH SD Flash Controller              | 5     | sdhci_pci  | [9772776314](<Mini Pc/CompuLab/fitlet/fitlet/4295E727D46A/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/9772776314>) |
| 8086:2294 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | sdhci_pci  | [53F89519BA](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/63C397A4BC83/OPNSENSE-22.7/13.0-STABLE/AMD64/53F89519BA>) |
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
| 8086:4dc4 | 8086:7270 | Intel            | Jasper Lake SCS1: eMMC Controller    | 4     | sdhci_pci  | [4243D313A1](<Desktop/GoWin Solution/R86/R86S/F79E140BEE45/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4243D313A1>) |
| 8086:9d2b | 8086:9d2b | Intel            | Skylake-U/Y SCC: eMMC                | 4     | sdhci_pci  | [4130B19CFA](<Notebook/Google/Lars/Lars/CCB0F65C765F/FREEBSD-13.1/13.1-RELEASE/AMD64/4130B19CFA>) |
| 1022:7813 | 17aa:3801 | AMD              | FCH SD Flash Controller              | 3     | sdhci_pci  | [6E31B5F45B](<Notebook/Lenovo/G40-45/G40-45 80E1/EA83D0EBE432/FREEBSD-13.1/13.1-RELEASE/AMD64/6E31B5F45B>) |
| 1180:0822 | 1028:024d | Ricoh            | R5C822 SD/SDIO/MMC/MS/MSPro Host ... | 3     | sdhci_pci  | [FDB3DE3036](<Notebook/Dell/Latitude/Latitude E4300/B023391CA6F2/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/FDB3DE3036>) |
| 1217:7120 | 1179:ff50 | O2 Micro         | Integrated MMC/SD Controller         | 3     | sdhci_pci  | [E057898546](<Notebook/Toshiba/Satellite/Satellite A300/72110BAFD1E3/FREEBSD-12.3-STABLE/12.3-STABLE/I386/E057898546>) |
| 1217:8520 | 1028:062e | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [8A3867F171](<Notebook/Dell/Latitude/Latitude E7450/384980EB885D/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/8A3867F171>) |
| 1217:8621 | 17aa:5072 | O2 Micro         | SD/MMC Card Reader Controller        | 3     | sdhci_pci  | [86866CE217](<Notebook/Lenovo/ThinkPad/ThinkPad E490 20N8CTO1WW/AC3F7A99A7ED/FREEBSD-13.1/13.1-RELEASE/AMD64/86866CE217>) |
| 14e4:16bc | 14e4:96bc | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 3     | sdhci_pci  | [64CCF1E6A0](<Notebook/Apple/MacBookPro10/MacBookPro10,1/60ED6011F0FC/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/64CCF1E6A0>) |
| 17a0:9750 | 17aa:2279 | Genesys Logic    | GL9750 SD Host Controller            | 3     | sdhci_pci  | [442A743538](<Notebook/Lenovo/ThinkPad/ThinkPad T590 20N4CTO1WW/3C494D1552EB/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/442A743538>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:4da4 | 8086:7270 | Intel            | Jasper Lake SPI Controller           | 79    |            | [4243D313A1](<Desktop/GoWin Solution/R86/R86S/F79E140BEE45/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4243D313A1>) |
| 8086:4de8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 46    |            | [1DAB2C420A](<Desktop/Others/Others/Others/7DC26823CFA8/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/1DAB2C420A>) |
| 8086:4dea | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #2  | 43    |            | [1DAB2C420A](<Desktop/Others/Others/Others/7DC26823CFA8/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/1DAB2C420A>) |
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 43    |            | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 8086:9da4 | 8086:7270 | Intel            | Cannon Point-LP SPI Controller       | 32    |            | [A0FB185069](<Desktop/Others/QD-WHLU/QD-WHLU01/88165FD62ECC/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A0FB185069>) |
| 8086:19e0 | 8086:7270 | Intel            | Atom Processor C3000 Series SPI C... | 30    |            | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 29    | ipmi       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 26    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:9dc5 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Hos... | 24    | ig4iic     | [A6D41C71FD](<Desktop/Others/Others/Others/F9DEED394CD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A6D41C71FD>) |
| 8086:9de8 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 24    | ig4iic     | [A6D41C71FD](<Desktop/Others/Others/Others/F9DEED394CD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A6D41C71FD>) |
| 8086:9de9 | 8086:7270 | Intel            | Cannon Point-LP Serial IO I2C Con... | 24    | ig4iic     | [A6D41C71FD](<Desktop/Others/Others/Others/F9DEED394CD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A6D41C71FD>) |
| 8086:a324 | 8086:7270 | Intel            | Cannon Lake PCH SPI Controller       | 24    |            | [21F838983B](<Desktop/ASUSTek Computer/P11C-M/P11C-M Series/E4D1817AC6A4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/21F838983B>) |
| 8086:a324 | 1043:8694 | Intel            | Cannon Lake PCH SPI Controller       | 22    |            | [90279B62B7](<Desktop/ASUSTek Computer/PRIME/PRIME B360M-K/32256E13726B/OPNSENSE-22.7.9/13.1-RELEASE-P3/AMD64/90279B62B7>) |
| 8086:02a4 | 8086:7270 | Intel            | Comet Lake SPI (flash) Controller    | 20    |            | [E467080570](<Notebook/Medion/E/E15415/B5081BB45457/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/E467080570>) |
| 8086:a1a4 | 15d9:0986 | Intel            | C620 Series Chipset Family SPI Co... | 18    |            | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |
| 8086:a324 | 1849:a324 | Intel            | Cannon Lake PCH SPI Controller       | 15    |            | [A40ADA7F7F](<Desktop/ASRock/H370/H370M-ITX-ac/B1655A8348EC/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A40ADA7F7F>) |
| 8086:43a4 | 1043:8694 | Intel            | Tiger Lake-H SPI Controller          | 14    |            | [E23F822438](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-F GAMING WIFI/83B0E22D5F39/OPNSENSE-22.1.10/13.0-STABLE/AMD64/E23F822438>) |
| 8086:43e8 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 14    | ig4iic     | [E23F822438](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-F GAMING WIFI/83B0E22D5F39/OPNSENSE-22.1.10/13.0-STABLE/AMD64/E23F822438>) |
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 14    |            | [F362B4C2EA](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEK/352243691B2C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F362B4C2EA>) |
| 8086:a324 | 17aa:312d | Intel            | Cannon Lake PCH SPI Controller       | 13    |            | [B553CEA3BD](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/EE0DE12FD648/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B553CEA3BD>) |
| 8086:22c2 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 12    | ig4iic     | [D15326180F](<Desktop/Protectli/FW2/FW2B/7F7BE2024374/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/D15326180F>) |
| 8086:34a4 | 8086:7270 | Intel            | Ice Lake-LP SPI Controller           | 12    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:34ab | 8086:7270 | Intel            | Ice Lake-LP Serial IO SPI Control... | 12    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:34e8 | 8086:7270 | Intel            | Ice Lake-LP Serial IO I2C Control... | 12    |            | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 8086:43e9 | 1043:8694 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 12    | ig4iic     | [E23F822438](<Desktop/ASUSTek Computer/ROG/ROG STRIX Z590-F GAMING WIFI/83B0E22D5F39/OPNSENSE-22.1.10/13.0-STABLE/AMD64/E23F822438>) |
| 8086:22c1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | ig4iic     | [D15326180F](<Desktop/Protectli/FW2/FW2B/7F7BE2024374/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/D15326180F>) |
| 1425:5601 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 10    |            | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 8086:02c5 | 8086:7270 | Intel            | Comet Lake Serial IO I2C Host Con... | 10    | ig4iic     | [E467080570](<Notebook/Medion/E/E15415/B5081BB45457/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/E467080570>) |
| 8086:4b24 | 8086:7270 | Intel            |                                      | 10    |            | [0F727C761B](<Desktop/Others/Others/Others/5D44760B2901/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0F727C761B>) |
| 8086:a0a4 | 8086:7270 | Intel            | Tiger Lake-LP SPI Controller         | 10    |            | [85520BF6BF](<Desktop/Others/Others/Others/793AE5B1171E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/85520BF6BF>) |
| 8086:02e8 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 9     | ig4iic     | [E467080570](<Notebook/Medion/E/E15415/B5081BB45457/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/E467080570>) |
| 8086:06a4 | 8086:7270 | Intel            | Comet Lake PCH SPI Controller        | 9     |            | [B9994AA302](<Desktop/Others/Others/Others/0043505011B9/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/B9994AA302>) |
| 8086:4de9 | 8086:7270 | Intel            | Serial IO I2C Host Controller        | 9     |            | [9B22C68E98](<Desktop/AZW/U/U59/B4FA2B1B8B0A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9B22C68E98>) |
| 8086:a324 | 15d9:1b0e | Intel            | Cannon Lake PCH SPI Controller       | 9     |            | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:a368 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 9     | ig4iic     | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:a369 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 9     | ig4iic     | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 1425:4601 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 8     |            | [70A786B8B5](<Server/Supermicro/X10/X10SLM+-LN4F/F4A1F01A1AAE/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/70A786B8B5>) |
| 8086:02a4 | 8086:2081 | Intel            | Comet Lake SPI (flash) Controller    | 8     |            | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:02e8 | 8086:2081 | Intel            | Serial IO I2C Host Controller        | 8     | ig4iic     | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:02ea | 8086:2081 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 8     | ig4iic     | [B74299204A](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/B74299204A>) |
| 8086:43a4 | 1849:43a4 | Intel            | Tiger Lake-H SPI Controller          | 8     |            | [D2029AE805](<Desktop/ASRock/H510/H510M-HDV/2382D948D052/OPNSENSE-23.1/13.1-RELEASE-P3/AMD64/D2029AE805>) |
| 8086:5ac8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 8     |            | [7F6194B56E](<Mini Pc/Intel/NUC6/NUC6CAYH/DA10179D3085/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F6194B56E>) |
| 8086:9da4 | 1297:4076 | Intel            | Cannon Point-LP SPI Controller       | 8     |            | [0F1E027B35](<Desktop/Shuttle/DS10/DS10U/EB8F6226ED0B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/0F1E027B35>) |
| 8086:9da4 | 17aa:2279 | Intel            | Cannon Point-LP SPI Controller       | 8     |            | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 8086:9de8 | 17aa:2279 | Intel            | Cannon Point-LP Serial IO I2C Con... | 8     | ig4iic     | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 8086:02e9 | 8086:7270 | Intel            | Comet Lake Serial IO I2C Host Con... | 7     | ig4iic     | [E467080570](<Notebook/Medion/E/E15415/B5081BB45457/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/E467080570>) |
| 8086:4dab | 8086:7270 | Intel            | Jasper Lake LPSS: SPI Controller #1  | 7     |            | [9B22C68E98](<Desktop/AZW/U/U59/B4FA2B1B8B0A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9B22C68E98>) |
| 8086:4dc5 | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #4  | 7     |            | [9B22C68E98](<Desktop/AZW/U/U59/B4FA2B1B8B0A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9B22C68E98>) |
| 8086:4dc6 | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #5  | 7     |            | [9B22C68E98](<Desktop/AZW/U/U59/B4FA2B1B8B0A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9B22C68E98>) |
| 8086:4deb | 8086:7270 | Intel            | Jasper Lake LPSS: I2C Controller #3  | 7     |            | [9B22C68E98](<Desktop/AZW/U/U59/B4FA2B1B8B0A/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9B22C68E98>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 162   | pchtherm   | [BC2C536004](<Desktop/Others/MANIFOLD/MANIFOLD 2-C/35C86EC57A8D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BC2C536004>) |
| 8086:9d27 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO UART C... | 83    |            | [F6FABABC22](<Desktop/Others/Others/Others/A81E6D09A273/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/F6FABABC22>) |
| 8086:9d60 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 80    | ig4iic     | [F6FABABC22](<Desktop/Others/Others/Others/A81E6D09A273/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/F6FABABC22>) |
| 8086:9d61 | 8086:7270 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 79    | ig4iic     | [F6FABABC22](<Desktop/Others/Others/Others/A81E6D09A273/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/F6FABABC22>) |
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 67    |            | [F2AEB0EA02](<Desktop/OEM/1/1.0/DE84049C92B2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/F2AEB0EA02>) |
| 8086:204d |           | Intel            | Sky Lake-E M3KTI Registers           | 60    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2015 |           | Intel            | Sky Lake-E Ubox Registers            | 57    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:31b4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 56    | ig4iic     | [B685DDC2AD](<Desktop/Hardkernel/ODROID-H/ODROID-H2/2813F39855C7/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B685DDC2AD>) |
| 8086:31b6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 55    | ig4iic     | [B685DDC2AD](<Desktop/Hardkernel/ODROID-H/ODROID-H2/2813F39855C7/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B685DDC2AD>) |
| 8086:31b8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 55    | ig4iic     | [B685DDC2AD](<Desktop/Hardkernel/ODROID-H/ODROID-H2/2813F39855C7/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B685DDC2AD>) |
| 8086:204c |           | Intel            | Sky Lake-E M3KTI Registers           | 47    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 47    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 45    | ig4iic     | [108C9DE5CC](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/A01D26C2C94F/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/108C9DE5CC>) |
| 8086:4e03 | 8086:7270 | Intel            | Dynamic Tuning service               | 44    |            | [CD3E4F7122](<Desktop/CncTion/N5105/N5105-4L/52B8556A9681/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/CD3E4F7122>) |
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 38    |            | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 37    | ig4iic     | [108C9DE5CC](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/A01D26C2C94F/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/108C9DE5CC>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 36    |            | [ABE21B9C9E](<Desktop/ASUSTek Computer/All/All Series/E6AD36953D33/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/ABE21B9C9E>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 36    |            | [ABE21B9C9E](<Desktop/ASUSTek Computer/All/All Series/E6AD36953D33/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/ABE21B9C9E>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 36    |            | [ABE21B9C9E](<Desktop/ASUSTek Computer/All/All Series/E6AD36953D33/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/ABE21B9C9E>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 35    |            | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31ba | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 35    | ig4iic     | [B685DDC2AD](<Desktop/Hardkernel/ODROID-H/ODROID-H2/2813F39855C7/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B685DDC2AD>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 34    |            | [ABE21B9C9E](<Desktop/ASUSTek Computer/All/All Series/E6AD36953D33/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/ABE21B9C9E>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 34    |            | [ABE21B9C9E](<Desktop/ASUSTek Computer/All/All Series/E6AD36953D33/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/ABE21B9C9E>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | ig4iic     | [D2D5364C96](<Mini Pc/AWOW/AK/AK34/6974B663417D/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D2D5364C96>) |
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 32    | pchtherm   | [DEB30193E2](<Desktop/Others/SKYBAY/SKYBAY/96BBF63CAAAE/OPNSENSE-22.7.9/13.1-RELEASE/AMD64/DEB30193E2>) |
| 8086:2058 |           | Intel            | Sky Lake-E KTI 0                     | 30    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | uart       | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 30    | uart       | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:9df9 | 8086:7270 | Intel            | Cannon Point-LP Thermal Controller   | 29    | pchtherm   | [A0FB185069](<Desktop/Others/QD-WHLU/QD-WHLU01/88165FD62ECC/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A0FB185069>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | ig4iic     | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | ig4iic     | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 28    | ig4iic     | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:31bc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 27    | uart       | [7729EC0863](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/D86192E67FF2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7729EC0863>) |
| 8086:31be | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 27    | uart       | [7729EC0863](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/D86192E67FF2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7729EC0863>) |
| 8086:31c0 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 27    | uart       | [7729EC0863](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/D86192E67FF2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7729EC0863>) |
| 8086:31ee | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 27    | uart       | [7729EC0863](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/D86192E67FF2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7729EC0863>) |
| 8086:1903 | 8086:7270 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 26    |            | [E467080570](<Notebook/Medion/E/E15415/B5081BB45457/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/E467080570>) |
| 8086:31ac | 8086:31ac | Intel            | Celeron/Pentium Silver Processor ... | 26    | ig4iic     | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 26    | ig4iic     | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 26    | ig4iic     | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 26    | uart       | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 26    | uart       | [F8A845FCDA](<Desktop/Others/1/1.21/3135C8208288/OPNSENSE-22.1.10/13.0-STABLE/AMD64/F8A845FCDA>) |
| 8086:31b2 | 8086:31b2 | Intel            | Celeron/Pentium Silver Processor ... | 25    | ig4iic     | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 25    |            | [91A89DB2AB](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/6893CEC55D3E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/91A89DB2AB>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 275   | intsmb     | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 241   | ichsmb     | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 205   | ichsmb     | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 201   | ichsmb     | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 179   | ichsmb     | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 98    | intsmb     | [21E1293019](<Notebook/Deciso/OPNsense/OPNsense Appliance/F166BECF86AB/OPNSENSE-22.10/13.1-RELEASE-P5/AMD64/21E1293019>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 96    | ichsmb     | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 8086:4da3 | 8086:7270 | Intel            | Jasper Lake SMBus                    | 79    |            | [4243D313A1](<Desktop/GoWin Solution/R86/R86S/F79E140BEE45/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4243D313A1>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 78    | ichsmb     | [33C59C687D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B28E7D1C74B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/33C59C687D>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 74    | ichsmb     | [7CCCECFDE1](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/3A76FE02D6F8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CCCECFDE1>) |
| 1022:790b | 1458:5001 | AMD              | FCH SMBus Controller                 | 71    | intsmb     | [D22C37FA81](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/7F8CFAEEF0F8/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/D22C37FA81>) |
| 1022:780b | 1734:1202 | AMD              | FCH SMBus Controller                 | 62    | intsmb     | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1022:790b | 1849:ffff | AMD              | FCH SMBus Controller                 | 61    | intsmb     | [38D7F55EF7](<Desktop/ASRockRack/X470/X470D4U/8404FC50C36B/FREEBSD-12.3-P8/12.3-RELEASE-P6/AMD64/38D7F55EF7>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 57    | ichsmb     | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 55    | ichsmb     | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 1022:790b | 1849:790b | AMD              | FCH SMBus Controller                 | 54    | intsmb     | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 1022:790b | 1043:87c0 | AMD              | FCH SMBus Controller                 | 52    | intsmb     | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 1022:780b | 103c:213d | AMD              | FCH SMBus Controller                 | 47    | intsmb     | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 8086:27da | 8086:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 47    | ichsmb     | [1C0805F9AE](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1C0805F9AE>) |
| 8086:283e | 8086:283e | Intel            | 82801H (ICH8 Family) SMBus Contro... | 47    | ichsmb     | [81BBACBFEE](<Firewall/Sophos/UTM/UTM/D0D282702135/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/81BBACBFEE>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 46    | ichsmb     | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 1002:4385 | 1002:4385 | AMD              | SBx00 SMBus Controller               | 43    | intsmb     | [F7129F1C87](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX R2.0/F71C683E48A4/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/F7129F1C87>) |
| 8086:1c22 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 43    | ichsmb     | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:8c22 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 40    | ichsmb     | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 1022:780b | 103c:8103 | AMD              | FCH SMBus Controller                 | 38    | intsmb     | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 36    | ichsmb     | [4BCC34FDCA](<Desktop/Gigabyte Technology/J4005/J4005ND2P-CF/A537E2535E76/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4BCC34FDCA>) |
| 8086:8c22 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 36    | ichsmb     | [D4296FD9D8](<Desktop/Dell/OptiPlex/OptiPlex 3020/F9299AC8F1C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4296FD9D8>) |
| 8086:8c22 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 36    | ichsmb     | [B29F2E4573](<Desktop/ASUSTek Computer/All/All Series/82A5E8C63352/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B29F2E4573>) |
| 8086:a123 | 1043:8694 | Intel            | 100 Series/C230 Series Chipset Fa... | 35    | ichsmb     | [7BC1746333](<Desktop/ASUSTek Computer/G11/G11CD/29D04E27064F/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7BC1746333>) |
| 1002:4385 |           | AMD              | SBx00 SMBus Controller               | 34    | intsmb     | [50C8CB79F7](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.4/12.4-RELEASE/AMD64/50C8CB79F7>) |
| 8086:1c22 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 34    | ichsmb     | [76ECD68FF6](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/76ECD68FF6>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 34    | ichsmb     | [DEB30193E2](<Desktop/Others/SKYBAY/SKYBAY/96BBF63CAAAE/OPNSENSE-22.7.9/13.1-RELEASE/AMD64/DEB30193E2>) |
| 1022:790b | 1043:8747 | AMD              | FCH SMBus Controller                 | 32    | intsmb     | [334575B738](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/A1AB004D09A5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/334575B738>) |
| 8086:1c22 | 1458:5001 | Intel            | 6 Series/C200 Series Chipset Fami... | 32    | ichsmb     | [1EC1683ACD](<Desktop/Gigabyte Technology/P61/P61-USB3-B3/CFEE4BCC2A88/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/1EC1683ACD>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 31    |            | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 31    | ichsmb     | [FA30F060F3](<Desktop/Intel/CARLOW/CARLOW/34C34A8491A2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/FA30F060F3>) |
| 8086:19df | 8086:7270 | Intel            | Atom Processor C3000 Series SMBus... | 30    | ichsmb     | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 8086:1e22 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family SMBu... | 30    | ichsmb     | [B6EC2E7E28](<Desktop/Dell/OptiPlex/OptiPlex 7010/92F0DFFBABB2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B6EC2E7E28>) |
| 8086:1e22 | 1043:84ca | Intel            | 7 Series/C216 Chipset Family SMBu... | 30    | ichsmb     | [10B6C81BCE](<Desktop/ASUSTek Computer/P8H77-V/P8H77-V LE/EEA085D70636/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/10B6C81BCE>) |
| 8086:3a30 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 29    | ichsmb     | [BC829DBB1A](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/BC829DBB1A>) |
| 8086:9da3 | 8086:7270 | Intel            | Cannon Point-LP SMBus Controller     | 29    |            | [A0FB185069](<Desktop/Others/QD-WHLU/QD-WHLU01/88165FD62ECC/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A0FB185069>) |
| 8086:1e22 | 1458:5001 | Intel            | 7 Series/C216 Chipset Family SMBu... | 27    | ichsmb     | [734FF7F48C](<Desktop/Gigabyte Technology/C1037/C1037UN-EU/93F9F29A0DC5/OPNSENSE-20.7.5/12.1-RELEASE-P10-HBSD/AMD64/734FF7F48C>) |
| 8086:19df | 15d9:0969 | Intel            | Atom Processor C3000 Series SMBus... | 26    | ichsmb     | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:1c22 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 26    | ichsmb     | [FE44242C3B](<Desktop/Supermicro/X9/X9SCL-X9SCM/0C3EBAE8F4DF/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/FE44242C3B>) |
| 8086:1e22 | 8086:1e22 | Intel            | 7 Series/C216 Chipset Family SMBu... | 26    | ichsmb     | [2DF5C5B434](<Notebook/Others/Others/Others/3C2409610548/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/2DF5C5B434>) |
| 1002:4385 | 1022:1510 | AMD              | SBx00 SMBus Controller               | 25    | intsmb     | [19786EDC61](<Desktop/PC Engines/APU/APU/F9CD3CBF9201/OPNSENSE-22.7.8/13.1-RELEASE-P5/AMD64/19786EDC61>) |
| 1002:4385 | 1043:8389 | AMD              | SBx00 SMBus Controller               | 25    | intsmb     | [902C77B5DC](<Desktop/ASUSTek Computer/CM/CM1530/F64C2DE0D627/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/902C77B5DC>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 25    | ichsmb     | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 8086:8c22 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | ichsmb     | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c22 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | ichsmb     | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 190   | hdac       | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 173   | hdac       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 128   | hdac       | [BC2C536004](<Desktop/Others/MANIFOLD/MANIFOLD 2-C/35C86EC57A8D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BC2C536004>) |
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 81    | hdac       | [64C549F3AE](<Mini Pc/AMI/Aptio/Aptio CRB/A3DBD4D871FE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/64C549F3AE>) |
| 8086:4dc8 | 8086:7270 | Intel            | Jasper Lake HD Audio                 | 79    | hdac       | [4243D313A1](<Desktop/GoWin Solution/R86/R86S/F79E140BEE45/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4243D313A1>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 74    | hdac       | [33C59C687D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B28E7D1C74B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/33C59C687D>) |
| 8086:0a0c | 8086:0a0c | Intel            | Haswell-ULT HD Audio Controller      | 70    | hdac       | [D453F64B4F](<Desktop/Advantech/UNO-2483/UNO-2483G-474AE/7C214E1E874B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D453F64B4F>) |
| 8086:9ca0 | 8086:7270 | Intel            | Wildcat Point-LP High Definition ... | 68    | hdac       | [7CCCECFDE1](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/3A76FE02D6F8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CCCECFDE1>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 66    | hdac       | [B7E599F99D](<Desktop/BESSTAR Tech/UM/UM350/13DA4A6E533F/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/B7E599F99D>) |
| 8086:160c | 8086:160c | Intel            | Broadwell-U Audio Controller         | 65    | hdac       | [364B3758B6](<Notebook/Others/Others/Others/B93AB0E5EE0E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/364B3758B6>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 64    | hdac       | [A4FF0A7EC5](<Desktop/AAEON/FWS/FWS-2251/2DCAB8F34901/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A4FF0A7EC5>) |
| 1002:9840 | 1734:1202 | AMD              | Kabini HDMI/DP Audio                 | 62    | hdac       | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1002:9840 | 103c:213d | AMD              | Kabini HDMI/DP Audio                 | 47    | hdac       | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 8086:5a98 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 44    | hdac       | [E44F465325](<Mini Pc/AWOW/PC/PC BOX/79C7F788772A/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/E44F465325>) |
| 1022:780d | 103c:213d | AMD              | FCH Azalia Controller                | 43    | hdac       | [6C83F31E71](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/3FC6A78B5508/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/6C83F31E71>) |
| 8086:0c0c | 8086:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 43    | hdac       | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 8086:0c0c | 8086:2010 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 40    | hdac       | [094AC0C253](<Desktop/Gigabyte Technology/H81/H81M-S/B0156F32D997/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/094AC0C253>) |
| 8086:8c20 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset High... | 40    | hdac       | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 1002:1308 | 103c:8103 | AMD              | Kaveri HDMI/DP Audio Controller      | 38    | hdac       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:780d | 1734:1203 | AMD              | FCH Azalia Controller                | 37    | hdac       | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 36    | hdac       | [49C31B364C](<Desktop/Biostar/A32/A32M2/736D165F6858/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/49C31B364C>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 35    | hdac       | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 35    | hdac       | [108C9DE5CC](<Desktop/ShenZhen MinWin Technology/MW-NANO-APL-4/MW-NANO-APL-4L/A01D26C2C94F/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/108C9DE5CC>) |
| 8086:0c0c | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 34    | hdac       | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 8086:0c0c | 1028:0612 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 34    | hdac       | [D4296FD9D8](<Desktop/Dell/OptiPlex/OptiPlex 3020/F9299AC8F1C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4296FD9D8>) |
| 8086:0c0c | 1043:8534 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 32    | hdac       | [B29F2E4573](<Desktop/ASUSTek Computer/All/All Series/82A5E8C63352/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B29F2E4573>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 31    | hdac       | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 8086:8c20 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset High... | 31    | hdac       | [D4296FD9D8](<Desktop/Dell/OptiPlex/OptiPlex 3020/F9299AC8F1C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4296FD9D8>) |
| 1022:780d | 103c:8103 | AMD              | FCH Azalia Controller                | 30    | hdac       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:15e3 | 1022:d001 | AMD              | Family 17h/19h HD Audio Controller   | 28    | hdac       | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:1457 | 1022:c950 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 26    | hdac       | [21E1293019](<Notebook/Deciso/OPNsense/OPNsense Appliance/F166BECF86AB/OPNSENSE-22.10/13.1-RELEASE-P5/AMD64/21E1293019>) |
| 1022:780d | 1022:780d | AMD              | FCH Azalia Controller                | 26    | hdac       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:1e20 | 1028:0577 | Intel            | 7 Series/C216 Chipset Family High... | 25    | hdac       | [B6EC2E7E28](<Desktop/Dell/OptiPlex/OptiPlex 7010/92F0DFFBABB2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B6EC2E7E28>) |
| 8086:3198 | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 25    | hdac       | [3C36F8DB41](<Mini Pc/BESSTAR Tech/GK/GK50/DA4AC958CA65/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3C36F8DB41>) |
| 8086:9dc8 | 8086:7270 | Intel            | Cannon Point-LP High Definition A... | 25    | hdac       | [A0FB185069](<Desktop/Others/QD-WHLU/QD-WHLU01/88165FD62ECC/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A0FB185069>) |
| 8086:0c0c | 103c:1998 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 22    | hdac       | [AFC7DE60E3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/CB6EAA64FCFB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/AFC7DE60E3>) |
| 8086:3b56 | 17aa:215e | Intel            | 5 Series/3400 Series Chipset High... | 22    | hdac       | [CBA0FC2340](<Notebook/Lenovo/ThinkPad/ThinkPad L412 0585AD9/A37928EB0C1B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/CBA0FC2340>) |
| 8086:8c20 | 103c:1998 | Intel            | 8 Series/C220 Series Chipset High... | 22    | hdac       | [AFC7DE60E3](<Desktop/Hewlett-Packard/EliteDesk/EliteDesk 800 G1 SFF/CB6EAA64FCFB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/AFC7DE60E3>) |
| 8086:1c20 | 17aa:21da | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | hdac       | [CB98F3014E](<Notebook/Lenovo/ThinkPad/ThinkPad X220 4286CTO/3C1927176580/FREEBSD-13.1/13.1-RELEASE/AMD64/CB98F3014E>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 21    | hdac       | [3DD9E3557C](<Notebook/Apple/MacBookPro8/MacBookPro8,1/83A908F15226/FREEBSD-13.1-P4/13.1-RELEASE-P4/AMD64/3DD9E3557C>) |
| 8086:1e20 | 8086:1e20 | Intel            | 7 Series/C216 Chipset Family High... | 21    | hdac       | [2DF5C5B434](<Notebook/Others/Others/Others/3C2409610548/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/2DF5C5B434>) |
| 8086:9d70 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 21    | hdac       | [FED7F55A01](<Desktop/Others/Others/Others/4F168F055C91/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/FED7F55A01>) |
| 1002:aaf0 | 1da2:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 20    | hdac       | [F7129F1C87](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH 990FX R2.0/F71C683E48A4/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/F7129F1C87>) |
| 8086:1c20 | 1458:a002 | Intel            | 6 Series/C200 Series Chipset Fami... | 20    | hdac       | [1EC1683ACD](<Desktop/Gigabyte Technology/P61/P61-USB3-B3/CFEE4BCC2A88/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/1EC1683ACD>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 20    | hdac       | [DEB30193E2](<Desktop/Others/SKYBAY/SKYBAY/96BBF63CAAAE/OPNSENSE-22.7.9/13.1-RELEASE/AMD64/DEB30193E2>) |
| 1002:9840 | 1002:9840 | AMD              | Kabini HDMI/DP Audio                 | 19    | hdac       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 8086:02c8 | 8086:7270 | Intel            | Comet Lake PCH-LP cAVS               | 18    | hdac       | [2D8E99F0C2](<Notebook/Google/Akemi/Akemi/BEFF0622F3E8/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/2D8E99F0C2>) |
| 8086:3198 | 10ec:115a | Intel            | Celeron/Pentium Silver Processor ... | 18    | hdac       | [7729EC0863](<Desktop/Seeed Studio/ODYSSEY-X86J4105/ODYSSEY-X86J4105 SD-BS-CJ41G-M-101-E 01-07-2020 14:03:11/D86192E67FF2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7729EC0863>) |
| 8086:8c20 | 1458:a002 | Intel            | 8 Series/C220 Series Chipset High... | 18    | hdac       | [29AD5EE336](<Desktop/Gigabyte Technology/H81/H81M-DS2/566372D2BBD3/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/29AD5EE336>) |
| 8086:160c | 17aa:2226 | Intel            | Broadwell-U Audio Controller         | 17    | hdac       | [10619AC217](<Notebook/Lenovo/ThinkPad/ThinkPad X250 20CLS5BU00/75926791E302/FREEBSD-13.1-P4/13.1-RELEASE-P3/AMD64/10619AC217>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8231 | 1028:0493 | O2 Micro         | O2Micro Integrated MS/MSPRO contr... | 6     |            | [48C26D2A17](<Notebook/Dell/Latitude/Latitude E6420/CEE321BEE6B2/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/48C26D2A17>) |
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
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 237   | ahci       | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 211   | ahci       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 201   | ahci       | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 176   | ahci       | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 1022:7801 | 1022:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 166   | ahci       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 161   | ahci       | [21E1293019](<Notebook/Deciso/OPNsense/OPNsense Appliance/F166BECF86AB/OPNSENSE-22.10/13.1-RELEASE-P5/AMD64/21E1293019>) |
| 1022:43c8 | 1b21:1062 | AMD              | 400 Series Chipset SATA Controller   | 112   | ahci       | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 97    | ahci       | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 77    | ahci       | [33C59C687D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B28E7D1C74B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/33C59C687D>) |
| 8086:4dd3 | 8086:7270 | Intel            | Jasper Lake SATA AHCI Controller     | 72    | ahci       | [CD3E4F7122](<Desktop/CncTion/N5105/N5105-4L/52B8556A9681/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/CD3E4F7122>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 71    | ahci       | [7CCCECFDE1](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/3A76FE02D6F8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CCCECFDE1>) |
| 1022:7801 | 1734:1202 | AMD              | FCH SATA Controller [AHCI mode]      | 61    | ahci       | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 55    | ahci       | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 1022:43eb | 1b21:1062 | AMD              | 500 Series Chipset SATA Controller   | 53    | ahci       | [D22C37FA81](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/7F8CFAEEF0F8/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/D22C37FA81>) |
| 1b21:0612 | 1849:0612 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 53    | ahci       | [3A8D5C61B6](<Desktop/ASRock/B75M/B75M R2.0/EA264E2F9554/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3A8D5C61B6>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 51    | ahci       | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 1022:7901 | 1849:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 50    | ahci       | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 1022:7801 | 103c:213d | AMD              | FCH SATA Controller [AHCI mode]      | 47    | ahci       | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 1022:7901 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 46    | ahci       | [1769DA5143](<Desktop/Gigabyte Technology/X399/X399 AORUS Gaming 7/8F3F9028A207/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/1769DA5143>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 45    | ahci       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 44    | ahci       | [C84BEDC821](<Desktop/Gigabyte Technology/N3160/N3160ND3V/B01DE72F7AFE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C84BEDC821>) |
| 1002:4391 | 1002:4391 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 41    | ahci       | [19786EDC61](<Desktop/PC Engines/APU/APU/F9CD3CBF9201/OPNSENSE-22.7.8/13.1-RELEASE-P5/AMD64/19786EDC61>) |
| 8086:1c02 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 38    | ahci       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 1022:7801 | 103c:8103 | AMD              | FCH SATA Controller [AHCI mode]      | 37    | ahci       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:1f22 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA2 C... | 36    | ahci       | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 8086:8c02 | 1028:0612 | Intel            | 8 Series/C220 Series Chipset Fami... | 36    | ahci       | [D4296FD9D8](<Desktop/Dell/OptiPlex/OptiPlex 3020/F9299AC8F1C6/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4296FD9D8>) |
| 8086:a102 | 1043:8694 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 35    | ahci       | [7BC1746333](<Desktop/ASUSTek Computer/G11/G11CD/29D04E27064F/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7BC1746333>) |
| 8086:8c02 | 1043:8534 | Intel            | 8 Series/C220 Series Chipset Fami... | 34    | ahci       | [B29F2E4573](<Desktop/ASUSTek Computer/All/All Series/82A5E8C63352/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B29F2E4573>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 32    | ahci       | [DEB30193E2](<Desktop/Others/SKYBAY/SKYBAY/96BBF63CAAAE/OPNSENSE-22.7.9/13.1-RELEASE/AMD64/DEB30193E2>) |
| 1022:43b8 | 1b21:1062 | AMD              | FCH SATA Controller D                | 31    | ahci       | [334575B738](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/A1AB004D09A5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/334575B738>) |
| 1022:7901 | 1043:8747 | AMD              | FCH SATA Controller [AHCI mode]      | 30    | ahci       | [334575B738](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/A1AB004D09A5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/334575B738>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 30    | ahci       | [3541DF7DD2](<Notebook/Apple/MacBook5/MacBook5,1/4867BDB4F0E4/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3541DF7DD2>) |
| 8086:1e02 | 1028:0577 | Intel            | 7 Series/C210 Series Chipset Fami... | 29    | ahci       | [B6EC2E7E28](<Desktop/Dell/OptiPlex/OptiPlex 7010/92F0DFFBABB2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B6EC2E7E28>) |
| 8086:9dd3 | 8086:7270 | Intel            | Cannon Point-LP SATA Controller [... | 29    | ahci       | [A0FB185069](<Desktop/Others/QD-WHLU/QD-WHLU01/88165FD62ECC/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/A0FB185069>) |
| 1022:7901 | 1849:ffff | AMD              | FCH SATA Controller [AHCI mode]      | 28    | ahci       | [38D7F55EF7](<Desktop/ASRockRack/X470/X470D4U/8404FC50C36B/FREEBSD-12.3-P8/12.3-RELEASE-P6/AMD64/38D7F55EF7>) |
| 8086:19b2 | 8086:7270 | Intel            | Atom Processor C3000 Series SATA ... | 27    | ahci       | [8679B4C8F4](<Firewall/Sophos/SG/SG/5121310E20BD/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8679B4C8F4>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 27    | ahci       | [4BCC34FDCA](<Desktop/Gigabyte Technology/J4005/J4005ND2P-CF/A537E2535E76/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4BCC34FDCA>) |
| 8086:8c02 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 27    | ahci       | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 8086:19c2 | 15d9:0969 | Intel            | Atom Processor C3000 Series SATA ... | 26    | ahci       | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:1e02 | 1043:84ca | Intel            | 7 Series/C210 Series Chipset Fami... | 25    | ahci       | [10B6C81BCE](<Desktop/ASUSTek Computer/P8H77-V/P8H77-V LE/EEA085D70636/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/10B6C81BCE>) |
| 1b21:0612 | 1043:84b7 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 24    | ahci       | [88929A3594](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH Z77/46CCAEB3C831/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/88929A3594>) |
| 8086:1c02 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 24    | ahci       | [6674BBF7F3](<Desktop/ASUSTek Computer/P8/P8Z68-V/E8819DE1DB7B/GHOSTBSD-22.09.16/13.1-STABLE/AMD64/6674BBF7F3>) |
| 8086:a282 | 1043:8694 | Intel            | 200 Series PCH SATA controller [A... | 24    | ahci       | [D44C580408](<Desktop/ASUSTek Computer/STRIX/STRIX Z270I GAMING/FF945A143CA8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/D44C580408>) |
| 8086:1c02 | 15d9:0624 | Intel            | 6 Series/C200 Series Chipset Fami... | 23    | ahci       | [FE44242C3B](<Desktop/Supermicro/X9/X9SCL-X9SCM/0C3EBAE8F4DF/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/FE44242C3B>) |
| 8086:5ae3 | 1849:5ae3 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 23    | ahci       | [D802705C1D](<Desktop/ASRock/J3355/J3355B-ITX/19E0C45EF6F5/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/D802705C1D>) |
| 8086:8c02 | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 23    | ahci       | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:8c02 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 23    | ahci       | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c02 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 23    | ahci       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 1022:43b7 | 1b21:1062 | AMD              | 300 Series Chipset SATA Controller   | 22    | ahci       | [547E5E3CE1](<Desktop/Hewlett-Packard/Pavilion/Pavilion Desktop PC 570-p0xx/55AF64665E6B/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/547E5E3CE1>) |
| 8086:19b2 | 15d9:0969 | Intel            | Atom Processor C3000 Series SATA ... | 22    | ahci       | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7800 | 1022:7800 | AMD              | FCH SATA Controller [IDE mode]       | 78    | ahci       | [85DA0654E1](<Desktop/PC Engines/APU/APU2/F80A627AF354/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/85DA0654E1>) |
| 8086:2850 | 8086:2850 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 45    | atapci     | [81BBACBFEE](<Firewall/Sophos/UTM/UTM/D0D282702135/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/81BBACBFEE>) |
| 1022:780c | 103c:8103 | AMD              | FCH IDE Controller                   | 38    | atapci     | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 36    | atapci     | [1C0805F9AE](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1C0805F9AE>) |
| 8086:2828 | 8086:2828 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 26    | atapci     | [D9113585F0](<Desktop/Others/Others/Others/383CD84BECA0/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/D9113585F0>) |
| 1002:439c | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 25    | atapci     | [902C77B5DC](<Desktop/ASUSTek Computer/CM/CM1530/F64C2DE0D627/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/902C77B5DC>) |
| 8086:27df | 1043:8179 | Intel            | 82801G (ICH7 Family) IDE Controller  | 23    | atapci     | [C33D11ED7B](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/DF87621E084E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C33D11ED7B>) |
| 8086:27c0 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 21    | atapci     | [C4E771C07C](<Desktop/Others/Others/Others/491A5AEF4B53/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C4E771C07C>) |
| 8086:3a20 | 103c:330d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 19    | atapci     | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 1002:439c | 1458:5002 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 17    | atapci     | [CCED487EC5](<Desktop/Gigabyte Technology/970/970A-D3P/300C5A425126/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CCED487EC5>) |
| 8086:27c0 | 1043:8179 | Intel            | NM10/ICH7 Family SATA Controller ... | 16    | atapci     | [C33D11ED7B](<Desktop/ASUSTek Computer/P5G41T-M/P5G41T-M LX2-GB/DF87621E084E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C33D11ED7B>) |
| 1002:4390 | 1043:8389 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 14    | ahci       | [902C77B5DC](<Desktop/ASUSTek Computer/CM/CM1530/F64C2DE0D627/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/902C77B5DC>) |
| 8086:2921 | 1028:0235 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 14    | atapci     | [655A9E7AF2](<Server/Dell/PowerEdge/PowerEdge R710/14070C55BFA0/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/655A9E7AF2>) |
| 1002:439c | 1849:439c | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 13    | atapci     | [5014E97CB5](<Desktop/ASRock/970/970A-G/BE1977B1B911/OPNSENSE-22.7/13.1-RELEASE/AMD64/5014E97CB5>) |
| 8086:1c00 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | atapci     | [4BB9A9324B](<Desktop/Dell/OptiPlex/OptiPlex 390/EB6E3143EA5A/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/4BB9A9324B>) |
| 8086:1c08 | 1028:04f5 | Intel            | 6 Series/C200 Series Chipset Fami... | 13    | atapci     | [4BB9A9324B](<Desktop/Dell/OptiPlex/OptiPlex 390/EB6E3143EA5A/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/4BB9A9324B>) |
| 8086:27c0 | 1458:b002 | Intel            | NM10/ICH7 Family SATA Controller ... | 13    | atapci     | [2959091A59](<Desktop/Gigabyte Technology/G31/G31M-ES2C/4775B5818213/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/2959091A59>) |
| 8086:2850 | 17aa:20a6 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 13    | atapci     | [50C3C93790](<Notebook/Lenovo/ThinkPad/ThinkPad T61 765912G/04EB3BF745ED/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/50C3C93790>) |
| 8086:2921 | 1028:0236 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 13    | atapci     | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:1c00 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | atapci     | [76ECD68FF6](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/76ECD68FF6>) |
| 8086:1c08 | 1043:844d | Intel            | 6 Series/C200 Series Chipset Fami... | 11    | atapci     | [76ECD68FF6](<Desktop/ASUSTek Computer/P8H61-M/P8H61-M LX3 R2.0/A72462873DBB/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/76ECD68FF6>) |
| 8086:269e | 103c:31fe | Intel            | 631xESB/632xESB IDE Controller       | 11    | atapci     | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:3a20 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 11    | atapci     | [BC829DBB1A](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/BC829DBB1A>) |
| 8086:3a26 | 1043:82d4 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 11    | atapci     | [BC829DBB1A](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/BC829DBB1A>) |
| 1002:4390 | 1458:b002 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 9     | ahci       | [CCED487EC5](<Desktop/Gigabyte Technology/970/970A-D3P/300C5A425126/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/CCED487EC5>) |
| 8086:27c0 | 1849:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 9     | atapci     | [3021B8EE09](<Desktop/ASRock/G41/G41M-VS3/F606D604CBAF/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/3021B8EE09>) |
| 8086:27df | 1849:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 9     | atapci     | [3021B8EE09](<Desktop/ASRock/G41/G41M-VS3/F606D604CBAF/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/3021B8EE09>) |
| 8086:2850 | 106b:00a1 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 9     | atapci     | [7AEF0A996B](<Notebook/Apple/MacBook3/MacBook3,1/B75216EE3719/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7AEF0A996B>) |
| 1002:439c | 103c:1609 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 8     | atapci     | [50C8CB79F7](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer/1CBA7BC77377/FREEBSD-12.4/12.4-RELEASE/AMD64/50C8CB79F7>) |
| 197b:2363 | 1043:824f | JMicron Techn... | JMB363 SATA/IDE Controller           | 8     | atapci     | [2B00248458](<Desktop/ASUSTek Computer/P5/P5K-E/A6D0848889DC/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/2B00248458>) |
| 197b:2363 | 1458:b000 | JMicron Techn... | JMB363 SATA/IDE Controller           | 8     | atapci     | [3EE914E3A0](<Desktop/Gigabyte Technology/GA-890/GA-890FXA-UD5/0D93685E30B3/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/3EE914E3A0>) |
| 8086:1c08 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 8     | atapci     | [1EC1683ACD](<Desktop/Gigabyte Technology/P61/P61-USB3-B3/CFEE4BCC2A88/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/1EC1683ACD>) |
| 8086:1d3c | 103c:1589 | Intel            | C600/X79 series chipset IDE-r Con... | 8     | atapci     | [0696D30D3F](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/0696D30D3F>) |
| 8086:29b6 | 1028:0211 | Intel            | 82Q35 Express PT IDER Controller     | 8     | atapci     | [7E869F95F7](<Desktop/Dell/OptiPlex/OptiPlex 755/EA117E39981F/OPNSENSE-22.1.6/13.0-STABLE/AMD64/7E869F95F7>) |
| 8086:3a20 | 1014:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 8     | atapci     | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 8086:3a26 | 1014:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 8     | atapci     | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 10de:03f6 | 1849:03f6 | Nvidia           | MCP61 SATA Controller                | 7     | atapci     | [3813C8856E](<Desktop/ASRock/N68/N68-S/890631257537/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3813C8856E>) |
| 1106:0415 | 1043:838f | VIA Technologies | VT6415 PATA IDE Host Controller      | 7     | atapci     | [D789A35C01](<Desktop/ASUSTek Computer/P8H67-M/P8H67-M PRO/0477E4056673/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/D789A35C01>) |
| 8086:1d00 | 103c:18a9 | Intel            | C600/X79 series chipset 4-Port SA... | 7     | atapci     | [A5514D3F4B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/6173205D3B06/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/A5514D3F4B>) |
| 8086:3a26 | 103c:330d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 7     | atapci     | [4E059E9162](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML350 G6/EDFF20587D82/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/4E059E9162>) |
| 1022:7800 | 1458:b002 | AMD              | FCH SATA Controller [IDE mode]       | 6     | ahci       | [DAED3F9401](<Desktop/Gigabyte Technology/F2/F2A68HM-H/3B216ACDFEA8/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DAED3F9401>) |
| 10de:03ec | 1849:03ec | Nvidia           | MCP61 IDE                            | 6     | atapci     | [3813C8856E](<Desktop/ASRock/N68/N68-S/890631257537/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3813C8856E>) |
| 11ab:6121 | 1043:8212 | Marvell Techn... | 88SE6111/6121 SATA II / PATA Cont... | 6     | atapci     | [BC829DBB1A](<Desktop/ASUSTek Computer/P5/P5Q-E/5F7334E18917/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/BC829DBB1A>) |
| 8086:1c00 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | atapci     | [4B3B7A0929](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/830DACE8E0B6/OPNSENSE-22.1.8/13.0-STABLE/AMD64/4B3B7A0929>) |
| 8086:1c00 | 1458:b002 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | atapci     | [1EC1683ACD](<Desktop/Gigabyte Technology/P61/P61-USB3-B3/CFEE4BCC2A88/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/1EC1683ACD>) |
| 8086:1c08 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | atapci     | [4B3B7A0929](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/830DACE8E0B6/OPNSENSE-22.1.8/13.0-STABLE/AMD64/4B3B7A0929>) |
| 8086:1e00 | 8086:1e00 | Intel            | 7 Series/C210 Series Chipset Fami... | 6     | atapci     | [A469AD62A4](<Desktop/Intel/H67/H67SL_VER1.2A/6298E03FFAD2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A469AD62A4>) |
| 8086:1e08 | 8086:1e08 | Intel            | 7 Series/C210 Series Chipset Fami... | 6     | atapci     | [A469AD62A4](<Desktop/Intel/H67/H67SL_VER1.2A/6298E03FFAD2/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/A469AD62A4>) |
| 8086:27c0 | 1028:0400 | Intel            | NM10/ICH7 Family SATA Controller ... | 6     | atapci     | [3E4A718671](<Desktop/Dell/OptiPlex/OptiPlex 380/23BEB469DB7D/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3E4A718671>) |
| 8086:27c0 | 1462:7592 | Intel            | NM10/ICH7 Family SATA Controller ... | 6     | atapci     | [DCE400CB30](<Desktop/MSI/MS/MS-7592/688D31F208BD/OPNSENSE-22.1.8/13.0-STABLE/AMD64/DCE400CB30>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 240   | nvme       | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 82    | nvme       | [3BDB5AA361](<Desktop/Techvision/TVI7309/TVI7309X/395E73693CE8/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/3BDB5AA361>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 66    | nvme       | [4C5CCD04D0](<Desktop/Others/Others/Others/9D8466EDD28C/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/4C5CCD04D0>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 66    | nvme       | [B8C89BDCA8](<Desktop/Supermicro/X9/X9DR3-F/3573CEE1CD7B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8C89BDCA8>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 57    | nvme       | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 54    | nvme       | [DEAEF8F0EF](<Notebook/Alienware/m15/m15 R4/0420F17441F2/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/DEAEF8F0EF>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 45    | nvme       | [31F17ADC5B](<Desktop/ASRock/4X4-4000/4X4-4000 Series/FF0DB8636C47/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/31F17ADC5B>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 42    | nvme       | [638E327C4E](<Desktop/MSI/CML-U/CML-U PRO Cubi 5/110C3F90DC1E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638E327C4E>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 30    | nvme       | [BEEC8001A1](<Desktop/MSI/MS-7/MS-7B94/D1E864C3E326/GHOSTBSD-22.11.02/13.1-STABLE/AMD64/BEEC8001A1>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 27    | nvme       | [9AC68A1C6D](<Desktop/Others/Others/Others/582E7BDAD2E4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/9AC68A1C6D>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 26    | nvme       | [73CB5D86BC](<Desktop/ASUSTek Computer/ROG/ROG STRIX B550-F GAMING/E714FDFEF192/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/73CB5D86BC>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 24    | nvme       | [49C31B364C](<Desktop/Biostar/A32/A32M2/736D165F6858/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/49C31B364C>) |
| 1d79:2263 | 1d79:2263 | Transcend        |                                      | 24    | nvme       | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 24    | nvme       | [90279B62B7](<Desktop/ASUSTek Computer/PRIME/PRIME B360M-K/32256E13726B/OPNSENSE-22.7.9/13.1-RELEASE-P3/AMD64/90279B62B7>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 22    | nvme       | [2BF8839D12](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S1QK00/F7C05B0E5D6D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/2BF8839D12>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4              | 22    | nvme       | [E80C8A40A5](<Desktop/Hewlett-Packard/ProDesk/ProDesk 600 G2 DM/EF032CAD06FB/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/E80C8A40A5>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 18    | nvme       | [2048FF5F71](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX325UA_UM325UA/49BFF737ADD5/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/2048FF5F71>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 18    | nvme       | [32207EA5D9](<Notebook/Lenovo/ThinkPad/ThinkPad T490 20N2CTO1WW/FF4B44FE1922/GHOSTBSD-22.06.18/13.1-STABLE/AMD64/32207EA5D9>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 17    | nvme       | [686447D655](<Desktop/Gigabyte Technology/B450M/B450M DS3H V2/B8F1A749F434/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/686447D655>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 15    | nvme       | [3502CB3D47](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7004BMB/1F40335DE972/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/3502CB3D47>) |
| 1987:5016 | 1987:5016 | Phison Electr... | E16 PCIe4 NVMe Controller            | 15    | nvme       | [072F2A6C27](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/072F2A6C27>) |
| 2646:500d | 2646:500d | Kingston Tech... | OM3PDP3 NVMe SSD                     | 14    | nvme       | [B7E599F99D](<Desktop/BESSTAR Tech/UM/UM350/13DA4A6E533F/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/B7E599F99D>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 14    | nvme       | [CB5BB2C3B5](<Desktop/Hewlett-Packard/ProLiant/ProLiant ML310e Gen8/13FA018AB210/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/CB5BB2C3B5>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 12    | nvme       | [57C3A4005A](<Notebook/Acidanthera/MacBookPro15/MacBookPro15,1/6C4D9581A214/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/57C3A4005A>) |
| 1c5c:1327 |           | SK hynix         | BC501 NVMe Solid State Drive         | 12    | nvme       | [98E67FF164](<Desktop/Dell/OptiPlex/OptiPlex 3070/F50CE4D358A8/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/98E67FF164>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 12    | nvme       | [77D3019212](<Desktop/Hardkernel/ODROID-H/ODROID-H2/397877110852/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/77D3019212>) |
| 1344:5410 | 1344:0100 | Micron Techno... |                                      | 11    | nvme       | [F39C0F4D92](<Notebook/Dell/Precision/Precision 7540/EEB44DDDBC24/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/F39C0F4D92>) |
| 1c5c:1339 |           | SK hynix         | BC511                                | 11    | nvme       | [DAE7027898](<Desktop/Fujitsu/PRIMERGY/PRIMERGY TX2560 M1/4C2638BCEE71/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/DAE7027898>) |
| 1179:0113 | 1179:0001 | Toshiba          | BG3 NVMe SSD Controller              | 10    | nvme       | [6399352798](<Convertible/BESSTAR Tech/GK/GK45/FB3B23285CAC/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/6399352798>) |
| 15b7:5011 | 15b7:5011 | SanDisk          | WD PC SN810 / Black SN850 NVMe SSD   | 10    | nvme       | [8ADDD09AA7](<Desktop/ASRock/H570/H570M-ITX-ac/7252CA256A2E/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/8ADDD09AA7>) |
| 1179:0116 | 1179:0001 | Toshiba          | XG5 NVMe SSD Controller              | 9     | nvme       | [CCE93FF157](<Desktop/Fujitsu/D3401-H2/D3401-H2 S26361-D3401-H2/225D067B274C/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/CCE93FF157>) |
| 1344:5405 | 1344:0100 | Micron Techno... |                                      | 9     | nvme       | [D2BF200529](<Notebook/Dell/Precision/Precision 7550/96BC4BFDCD0B/FREEBSD-13.1-P2/13.1-STABLE/AMD64/D2BF200529>) |
| 15b7:501a | 15b7:501a | SanDisk          | WD Blue SN570 NVMe SSD               | 9     | nvme       | [F6C8EB4E18](<Desktop/ASRock/B660/B660M-ITX-ac/2C580AAAA431/FREEBSD-13.1/13.1-RELEASE/AMD64/F6C8EB4E18>) |
| 10ec:5763 | 10ec:5763 | Realtek Semic... |                                      | 8     | nvme       | [949E472DB5](<Notebook/MSI/PS63/PS63 Modern 8M/176D052B82EE/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/949E472DB5>) |
| 1179:0115 | 1179:0001 | Toshiba          | XG4 NVMe SSD Controller              | 8     | nvme       | [3465C46B7D](<Desktop/Lenovo/ThinkCentre/ThinkCentre M910t 10MMS02F00/EBC6615D2AD0/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/3465C46B7D>) |
| 1179:011a | 1179:0001 | Toshiba          | XG6 NVMe SSD Controller              | 8     | nvme       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 1e95:9100 | 126f:2263 | Solid State S... |                                      | 8     | nvme       | [BABE4BB620](<Notebook/Hewlett-Packard/ProBook/ProBook 440 G8 Notebook PC/AEACE4315CCC/FREEBSD-13.1/13.1-RELEASE/AMD64/BABE4BB620>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 7     | nvme       | [52CC45ABA9](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/28ABD5EC0B9C/GHOSTBSD-22.07.16/13.1-STABLE/AMD64/52CC45ABA9>) |
| 1e4b:1202 | 1e4b:1202 | MAXIO Technol... | NVMe SSD Controller MAP1202          | 7     | nvme       | [1DAB2C420A](<Desktop/Others/Others/Others/7DC26823CFA8/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/1DAB2C420A>) |
| 2646:500c | 2646:500c | Kingston Tech... |                                      | 7     | nvme       | [CFFED92600](<Notebook/ASUSTek Computer/VivoBook_ASUSLaptop/VivoBook_ASUSLaptop X515DAP_M515DA/606098250228/FREEBSD-13.1/13.1-RELEASE/AMD64/CFFED92600>) |
| 2646:500f | 2646:500f | Kingston Tech... |                                      | 7     | nvme       | [D19DB2828C](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Extreme Gen 4i 20Y5001DMX/4E5144B9F9B5/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/D19DB2828C>) |
| 8086:2522 | 8086:3806 | Intel            | NVMe Optane Memory Series            | 7     | nvme       | [53C643DC95](<Desktop/CncTion/Jasper-4/Jasper-4L/E64EE31D78D3/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/53C643DC95>) |
| 1d97:1160 | 1d97:1160 | Shenzhen Long... | unknown                              | 6     | nvme       | [78BCCCDA01](<Desktop/CncTion/N5105/N5105-4L/667B90399F5F/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/78BCCCDA01>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 6     | nvme       | [C0C8D1F85E](<Server/Supermicro/Super/Super Server/73426A08BED9/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C0C8D1F85E>) |
| 15b7:5019 | 15b7:5019 | SanDisk          | unknown                              | 5     | nvme       | [56BC3B04FD](<Notebook/ASUSTek Computer/ZenBook/ZenBook UX434FL_UX434FL/D46D4BF5A008/FREEBSD-13.1/13.1-RELEASE/AMD64/56BC3B04FD>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 5     | nvme       | [45D6590312](<Desktop/CncTion/N5105/N5105-4L/05C6F394D27E/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/45D6590312>) |
| 1db2:2302 | 1db2:2302 | ATP ELECTRONICS  |                                      | 5     | nvme       | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |
| 8086:0975 | 8086:8410 | Intel            |                                      | 5     | nvme       | [1751DE42DC](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/F8E61E16B1A3/OPNSENSE-22.1.8/13.0-STABLE/AMD64/1751DE42DC>) |
| 8086:2522 | 8086:3810 | Intel            | NVMe Optane Memory Series            | 5     | nvme       | [F222AF4098](<Desktop/JGINYUE/H97I/H97I GAMING V1.0/1B791608ADBF/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/F222AF4098>) |
| c0a9:5412 | c0a9:0100 | Micron/Crucia... |                                      | 5     | nvme       | [4E0A906ACB](<Desktop/Gigabyte Technology/B450/B450 I AORUS PRO WIFI/DACF5EB5754A/OPNSENSE-22.1.8/13.0-STABLE/AMD64/4E0A906ACB>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 26    | ciss       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 1000:0060 | 1028:1f0c | Broadcom / LSI   | MegaRAID SAS 1078                    | 23    | mfi        | [2779D78756](<Server/Dell/PowerEdge/PowerEdge R710/EB4913CD4F4F/FREEBSD-13.1-P2/13.1-RELEASE-P1/AMD64/2779D78756>) |
| 1000:005b | 1028:1f34 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 16    | mfi        | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 1000:005b | 1028:1f38 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 14    | mfi        | [6EFD22E598](<Server/Dell/PowerEdge/PowerEdge R420/787A628CC8C0/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/6EFD22E598>) |
| 8086:2822 | 1028:05a4 | Intel            | SATA Controller [RAID mode]          | 14    | ahci       | [E7DC9CC5EE](<Desktop/Dell/OptiPlex/OptiPlex 9020/392A3392949D/OPNSENSE-23.1/13.1-RELEASE-P1/AMD64/E7DC9CC5EE>) |
| 1000:0079 | 1028:1f17 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 13    | mfi        | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 13    | ahci       | [0CB7BACC88](<Desktop/BESSTAR Tech/X/X35G/116441499573/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/0CB7BACC88>) |
| 1000:0073 | 1028:1f51 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 11    | mfi        | [AD01FBD5A3](<Server/Dell/PowerEdge/PowerEdge R620/C6E9475E3E9E/OPNSENSE-22.1.10/13.0-STABLE/AMD64/AD01FBD5A3>) |
| 1000:005f | 1028:1f44 | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 10    | mfi        | [C5AF7BF9E5](<Server/Dell/PowerEdge/PowerEdge R340/3C18F7464176/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C5AF7BF9E5>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 10    | ciss       | [B9DF714117](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/0FE7DBEBF7BB/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B9DF714117>) |
| 1000:005d | 1028:1f49 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 8     | mfi        | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 1000:0072 | 1734:1177 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 8     | mps        | [16C226553C](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/BB7614C3933F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/16C226553C>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 7     | ciss       | [1A754B2A9E](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G5/851ACF3B4A4E/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/1A754B2A9E>) |
| 8086:2822 | 1028:047e | Intel            | SATA Controller [RAID mode]          | 7     | ahci       | [B71ECDF543](<Desktop/Dell/OptiPlex/OptiPlex 990/A3ED196F0551/OPNSENSE-22.1.8/13.0-STABLE/AMD64/B71ECDF543>) |
| 8086:2822 | 1028:052c | Intel            | SATA Controller [RAID mode]          | 7     | ahci       | [7F66A21D24](<Desktop/Dell/OptiPlex/OptiPlex 9010/D9A59D9E0F49/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7F66A21D24>) |
| 8086:2826 | 103c:1589 | Intel            | C600/X79 series chipset SATA RAID... | 7     | ahci       | [3F9D19B372](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/D8185C22CDE1/OPNSENSE-22.1.10/13.0-STABLE/AMD64/3F9D19B372>) |
| 1000:005d | 1028:1f47 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 6     | mfi        | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 1000:005f | 1028:1f4b | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 6     | mfi        | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 103c:3230 | 103c:3235 | Hewlett-Packard  | Smart Array Controller               | 6     | ciss       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 13c1:1004 | 13c1:1004 | 3ware            | 9650SE SATA-II RAID PCIe             | 5     | twa        | [01898B2FFB](<Desktop/ACMA/X8/X8SIE/EDFA6F8E9EEC/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/01898B2FFB>) |
| 9005:0286 | 1014:9580 | Adaptec          | AAC-RAID (Rocket)                    | 5     | aac        | [41D40D8752](<Server/IBM/System/System x3650 -[797941Y]-/B6A5CBBF3013/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/41D40D8752>) |
| 103c:323a | 103c:3243 | Hewlett-Packard  | Smart Array G6 controllers           | 4     | ciss       | [289D2F383B](<Server/Hewlett-Packard/ProLiant/ProLiant DL180 G6/8E2A024CC455/FREEBSD-12.3-P7/12.3-RELEASE-P6/AMD64/289D2F383B>) |
| 8086:1c04 | 1028:04dd | Intel            | 6 Series/C200 Series Desktop SATA... | 4     | ahci       | [0325ADE874](<Server/Dell/PowerEdge/PowerEdge R210 II/092D9B4C961E/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/0325ADE874>) |
| 8086:2822 | 1028:07c5 | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [50FBB0435C](<Desktop/Dell/PowerEdge/PowerEdge T30/8C16168DE41F/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/50FBB0435C>) |
| 8086:2822 | 103c:130a | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [A24F08281D](<Desktop/Hewlett-Packard/Z600/Z600 Workstation/0B8AFB9253EE/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/A24F08281D>) |
| 8086:2822 | 1458:b005 | Intel            | SATA Controller [RAID mode]          | 4     | ahci       | [B66D0955EB](<Desktop/Gigabyte Technology/B250/B250M-D2V/8DCB3D719E7C/OPNSENSE-22.1.6/13.0-STABLE/AMD64/B66D0955EB>) |
| 8086:2826 | 103c:158a | Intel            | C600/X79 series chipset SATA RAID... | 4     | ahci       | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 8086:282a | 1028:05ca | Intel            | 82801 Mobile SATA Controller [RAI... | 4     | ahci       | [970234B430](<Notebook/Dell/Latitude/Latitude E7240/1C50E392EFBF/FREEBSD-13.1/13.1-RELEASE/AMD64/970234B430>) |
| 1000:005d | 1000:9363 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 3     | mfi        | [AB6E70ABCA](<Server/Intel/S1200/S1200SP/BF2910D7912E/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/AB6E70ABCA>) |
| 1000:005d | 1028:1f42 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 3     | mrsas      | [0B239C3286](<Server/Dell/PowerEdge/PowerEdge R540/34807F166517/OPNSENSE-22.1.7/13.0-STABLE/AMD64/0B239C3286>) |
| 1000:0073 | 1734:1177 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 3     | mfi        | [3D46E0EACE](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S6/02405A2DD385/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/3D46E0EACE>) |
| 1000:0079 | 1014:03c7 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 3     | mfi        | [8BBC599CDD](<Server/IBM/System/System x3650 M3 -[7945K3G]-/4E22FDB71865/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/8BBC599CDD>) |
| 1000:10e2 | 1028:2176 | Broadcom / LSI   | MegaRAID 12GSAS/PCIe Secure SAS39xx  | 3     | mrsas      | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 103c:323a | 103c:3241 | Hewlett-Packard  | Smart Array G6 controllers           | 3     | ciss       | [379FCF9804](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 G6/8034C079A069/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/379FCF9804>) |
| 103c:323b | 103c:3351 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 3     | ciss       | [0DA59DFF8F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/5D50CBD4DBDB/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/0DA59DFF8F>) |
| 1095:3114 | 1095:3114 | Silicon Image    | SiI 3114 [SATALink/SATARaid] Seri... | 3     | atapci     | [BBD42243AE](<Desktop/TYAN Computer/Tiger/Tiger K8W Dual AMD Opteron, S2875/A029250D83FC/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/BBD42243AE>) |
| 8086:2822 | 1028:0276 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [24B9490C77](<Desktop/Dell/OptiPlex/OptiPlex 960/07A3501CD581/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/24B9490C77>) |
| 8086:2822 | 1028:0620 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [BB86FB3E67](<Desktop/Dell/PowerEdge/PowerEdge T20/C68E45CBB411/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BB86FB3E67>) |
| 8086:2822 | 1028:06ba | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [D06E05C67A](<Desktop/Dell/OptiPlex/OptiPlex 5040/6A6458ACB6C7/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/D06E05C67A>) |
| 8086:2822 | 1028:085b | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [07144A803B](<Desktop/Dell/OptiPlex/OptiPlex 5060/E8B372160376/OPNSENSE-22.1.8/13.0-STABLE/AMD64/07144A803B>) |
| 8086:2822 | 1849:a282 | Intel            | SATA Controller [RAID mode]          | 3     | ahci       | [803B44339B](<Desktop/ASRock/B250/B250M-HDV/BD56D24CB794/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/803B44339B>) |
| 8086:2826 | 17aa:30b0 | Intel            | C600/X79 series chipset SATA RAID... | 3     | ahci       | [D6111B8FF1](<Server/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/C9B365EFBC6F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D6111B8FF1>) |
| 8086:467f | 1043:8694 | Intel            | Volume Management Device NVMe RAI... | 3     | pcib       | [5684672F5A](<Desktop/ASUSTek Computer/PRIME/PRIME Z690-P D4/A40E24C997B9/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/5684672F5A>) |
| 9005:0285 | 108e:0286 | Adaptec          | AAC-RAID                             | 3     | aac        | [51E87104A0](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/51E87104A0>) |
| 1000:0014 | 1734:1238 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3516            | 2     | mrsas      | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 1000:0016 | 1137:0210 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [2633EAF68B](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M5SX/41B605A42DA4/OPNSENSE-22.10/13.1-RELEASE-P2/AMD64/2633EAF68B>) |
| 1000:0073 | 1014:03b1 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 2     | mfi        | [71D412D254](<Server/IBM/System/System x3250 M3 -[4252K3G]-/0EA3D6B9F663/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/71D412D254>) |
| 1000:0079 | 1000:9261 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 2     | mfi        | [D6FA145C7C](<Desktop/Supermicro/SYS-6028/SYS-6028R-TRT/F546836EEFAA/OPNSENSE-22.1.7/13.0-STABLE/AMD64/D6FA145C7C>) |
| 1000:0079 | 1014:03b2 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 2     | mfi        | [F723CAE263](<Server/IBM/System/System x3550 M3 -[7944ZJN]-/B6E6FA55AFB2/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/F723CAE263>) |
| 1000:00ce | 1137:0197 | Broadcom / LSI   | MegaRAID SAS-3 3316 [Intruder]       | 2     | mrsas      | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1000:3020 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 27    | mps        | [84C360AD02](<Desktop/Supermicro/SSG-5028/SSG-5028R-E1CR12L-CE010/BC525F547480/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/84C360AD02>) |
| 1000:0072 | 1028:1f1c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 12    | mps        | [10CA365B40](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/10CA365B40>) |
| 8086:1d6b | 103c:1589 | Intel            | C602 chipset 4-Port SATA Storage ... | 9     | isci       | [0696D30D3F](<Desktop/Hewlett-Packard/Z420/Z420 Workstation/764597CC1669/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/0696D30D3F>) |
| 1000:0072 | 1028:1f1d | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 6     | mps        | [0C40D38F1D](<Server/Dell/PowerEdge/PowerEdge R310/FA9EEF8E1FF1/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/0C40D38F1D>) |
| 1000:0087 | 1000:3020 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 6     | mps        | [2E3B493BA3](<Desktop/ASUSTek Computer/M5A99X/M5A99X EVO/66C30AA2B679/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/2E3B493BA3>) |
| 8086:1d6b | 15d9:0660 | Intel            | C602 chipset 4-Port SATA Storage ... | 6     | isci       | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 1000:0072 | 1028:1f1e | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mps        | [655A9E7AF2](<Server/Dell/PowerEdge/PowerEdge R710/14070C55BFA0/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/655A9E7AF2>) |
| 8086:1d6b | 103c:158a | Intel            | C602 chipset 4-Port SATA Storage ... | 5     | isci       | [883958CD36](<Desktop/Hewlett-Packard/Z620/Z620 Workstation/D23CCF105219/FREEBSD-13.1/13.1-RELEASE/AMD64/883958CD36>) |
| 1000:0097 | 1000:30e0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 4     | mpr        | [84C360AD02](<Desktop/Supermicro/SSG-5028/SSG-5028R-E1CR12L-CE010/BC525F547480/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/84C360AD02>) |
| 1000:0097 | 1028:1f53 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 4     | mpr        | [30602E7478](<Server/Dell/PowerEdge/PowerEdge R630/24116AF6B008/OPNSENSE-22.1.10/13.0-STABLE/AMD64/30602E7478>) |
| 1000:0070 | 1000:3010 | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 3     | mps        | [0EEA35E069](<Desktop/Dell/Precision/Precision WorkStation T3500/2B5473C76A7D/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/0EEA35E069>) |
| 1000:0072 | 1000:0072 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [18C4588A0E](<Desktop/CIARA TECHNOLOGIES/1X8-X6/1X8-X6 CACHEH/CAC8276E190F/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/18C4588A0E>) |
| 1000:0072 | 1000:3040 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [4763FE7595](<Server/Intel/S1200/S1200RP_SE/4DF73AF97478/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/4763FE7595>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [DC582EA4D3](<Desktop/ASRock/B550M/B550M Pro4/6D75D10E9FEA/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/DC582EA4D3>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 3     | mps        | [2BD1529913](<Server/Supermicro/MBD-X8/MBD-X8DT6-A-IS018/9FC8D16648D3/FREEBSD-13.1/13.1-RELEASE/AMD64/2BD1529913>) |
| 1000:0087 | 1028:1f38 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mps        | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 3     | mpr        | [6C4D7ACEEC](<Server/Supermicro/Super/Super Server/B1D0F2EE5D00/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/6C4D7ACEEC>) |
| 1000:0016 | 1028:1fcb | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [C34D5C2BE3](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C34D5C2BE3>) |
| 1000:0016 | 1028:1fcd | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [AA44179A5F](<Server/Dell/PowerEdge/PowerEdge R640/FB4118FD56BA/FREEBSD-12.2-P1/12.2-RELEASE-P1/AMD64/AA44179A5F>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 2     | mps        | [2F589ABF33](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/0AEF40CD9E4E/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/2F589ABF33>) |
| 1000:0072 | 103c:3371 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mps        | [EA62F49750](<Desktop/Supermicro/X9/X9DRD-7LN4F/97D90A6AA706/TRUENAS-12.2-P10/12.2-RELEASE-P10/AMD64/EA62F49750>) |
| 1000:0087 | 1028:1f34 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mps        | [FBCC442D47](<Server/Dell/PowerEdge/PowerEdge R720xd/9494C365C719/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBCC442D47>) |
| 1000:0097 | 1028:1f46 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [BA13BBECFD](<Server/Dell/PowerEdge/PowerEdge R730/BC55DA270D03/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/BA13BBECFD>) |
| 1000:0097 | 1849:0097 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [C04BBD635B](<Desktop/ASRockRack/D1541/D1541D4U-2T8R/6457E123E761/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/C04BBD635B>) |
| 103c:3239 | 103c:21c7 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 2     | ciss       | [F91D50AB48](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/10EC3EA2C607/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F91D50AB48>) |
| 8086:1d6b | 1028:0497 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [1916A4064B](<Desktop/Dell/Precision/Precision T3600/1BDA06E274A1/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/1916A4064B>) |
| 8086:1d6b | 15d9:0628 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [B8C89BDCA8](<Desktop/Supermicro/X9/X9DR3-F/3573CEE1CD7B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/B8C89BDCA8>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [0F3EE4CAAB](<Desktop/Fujitsu/CELSIUS/CELSIUS M720/7B5122D4B3E4/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/0F3EE4CAAB>) |
| 8086:1d6b | 17aa:1026 | Intel            | C602 chipset 4-Port SATA Storage ... | 2     | isci       | [1EC71F814B](<Desktop/Lenovo/ThinkStation/ThinkStation S30 43511K5/E8B0027862B5/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1EC71F814B>) |
| 1000:005d | 15d9:0a09 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [B44FE94131](<Desktop/Supermicro/SSG-2028/SSG-2028R-E1CR24N/201BEB766364/FREENAS-11.3-P9/11.3-RELEASE-P9/AMD64/B44FE94131>) |
| 1000:005d | 19e5:da07 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [AC2C7107D3](<Server/HUAWEI/RH2288H/RH2288H V3/FFCB8F761596/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/AC2C7107D3>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mps        | [CF2E66B6AA](<Server/Supermicro/X10/X10SLL-F/A57790A3890F/FREEBSD-12.2/12.2-RELEASE/AMD64/CF2E66B6AA>) |
| 1000:0070 | 1014:040e | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 1     | mps        | [7F8395E815](<Server/IBM/System/System x3250 M5: -[5458Z1P]-/EABBAC4B4C68/OPNSENSE-22.1.7/13.0-STABLE/AMD64/7F8395E815>) |
| 1000:0072 | 1000:3050 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [28FDD2C2DC](<Desktop/Supermicro/X9/X9SCL-X9SCM/70812EDDCEB0/FREENAS-11.2-STABLE/11.2-STABLE/AMD64/28FDD2C2DC>) |
| 1000:0072 | 1000:3060 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [F88EAF06AC](<Server/Intel/S1200/S1200BTL/BD51E5A20141/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/F88EAF06AC>) |
| 1000:0072 | 1000:30f0 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [90C27497D9](<Desktop/ASUSTek Computer/Crosshair/Crosshair V Formula/08D4551A4F47/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/90C27497D9>) |
| 1000:0072 | 1043:843c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [D50484387C](<Server/ASUSTek Computer/P8B-E/P8B-E Series/9F223A3AC70D/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/D50484387C>) |
| 1000:0086 | 103c:158b | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 1000:0087 | 1000:3030 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [E59D5D41A5](<Server/Hewlett-Packard/ProLiant/ProLiant SE326M1R2/9702C33A6606/FREENAS-11.3-P7/11.3-RELEASE-P7/AMD64/E59D5D41A5>) |
| 1000:0090 | 1137:0155 | Broadcom / LSI   | SAS3108 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 1000:0097 | 1028:0619 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [DDDF168DB9](<Desktop/Dell/Precision/Precision Tower 7910/9E71C365962A/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/DDDF168DB9>) |
| 1000:00ac | 1000:3000 | Broadcom / LSI   | SAS3416 Fusion-MPT Tri-Mode I/O C... | 1     | mpr        | [23196AA66B](<Desktop/ASRock/Z390/Z390M-ITX-ac/40E52D5C50CF/FREEBSD-12.2-P5/12.2-RELEASE-P4/AMD64/23196AA66B>) |
| 103c:3239 | 103c:21c8 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 1     | ciss       | [C2BB148E8A](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/37E855C98CE1/FREEBSD-12.2-P2/12.2-RELEASE-P2/AMD64/C2BB148E8A>) |
| 8086:1d60 | 1028:0496 | Intel            | C608 chipset Dual 4-Port SATA/SAS... | 1     | isci       | [D9D86D5BFD](<Desktop/Dell/Precision/Precision T5600/ADD168454A3E/GHOSTBSD-22.04.06/13.0-STABLE/AMD64/D9D86D5BFD>) |
| 8086:1d60 | 1028:0497 | Intel            | C608 chipset Dual 4-Port SATA/SAS... | 1     | isci       | [B6044FB84C](<Desktop/ASRock/G41/G41M-VS3/F606D604CBAF/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/B6044FB84C>) |
| 8086:1d69 | 17aa:1026 | Intel            | C604/X79 series chipset 4-Port SA... | 1     | isci       | [DD545FB588](<Desktop/Lenovo/ThinkStation/ThinkStation S30 0569A93/3A5A3AB166EF/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/DD545FB588>) |
| 8086:1d6a | 8086:3583 | Intel            | C600/X79 series chipset Dual 4-Po... | 1     | isci       | [474B0E44EA](<Server/Wortmann AG/TERRA/TERRA Server/8361012A53E8/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/474B0E44EA>) |
| 8086:1d6b | 103c:158b | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [3D780DD078](<Desktop/Hewlett-Packard/Z820/Z820 Workstation/2A6BACFE427B/FREEBSD-12.2/12.2-RELEASE/AMD64/3D780DD078>) |
| 8086:1d6b | 152d:899b | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [A4980E3EA4](<Server/Quanta/JASPER/JASPER12/E990713EF0FC/FREEBSD-12.2-P6/12.2-RELEASE-P4/AMD64/A4980E3EA4>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1425:5501 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 10    |            | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 1425:4501 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 8     |            | [70A786B8B5](<Server/Supermicro/X10/X10SLM+-LN4F/F4A1F01A1AAE/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/70A786B8B5>) |
| 1000:0058 | 1028:1f0e | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 5     | mpt        | [1AEB1BF3BF](<Server/Dell/PowerEdge/PowerEdge R200/7889930FFF0B/OPNSENSE-22.1.8/13.0-STABLE/AMD64/1AEB1BF3BF>) |
| 1000:0058 | 1028:1f0f | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 5     | mpt        | [847CA0ACB9](<Server/Dell/PowerEdge/PowerEdge R410/AA3B52468CEC/OPNSENSE-22.1.6/13.0-STABLE/AMD64/847CA0ACB9>) |
| 17d3:1300 | 17d3:1300 | Areca Technology | ARC-1300ix-16 16-Port PCI-Express... | 4     | arcsas     | [66BBED8D59](<Desktop/ASUSTek Computer/P6T/P6T SE/9C422F2B290E/FREEBSD-12.1-P5/12.1-RELEASE-P2/AMD64/66BBED8D59>) |
| 9004:8178 |           | Adaptec          | AIC-7870P/7881U [AHA-2940U/UW/D/S76] | 4     | ahc        | [459C674B3B](<Desktop/ASRock/Z77/Z77 Extreme4/4A8FC6177080/FREEBSD-12.3/12.3-RELEASE/AMD64/459C674B3B>) |
| 1000:0058 | 1014:0394 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mpt        | [5F9F2C2232](<Server/IBM/System/System x -[79463ag]-/9FE86345EDC2/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/5F9F2C2232>) |
| 1425:5503 |           | Chelsio Commu... | T540-CR Unified Wire Storage Cont... | 3     |            | [21E7190FF2](<Desktop/Supermicro/AS/AS -5019D-FTN4/86486880485E/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/21E7190FF2>) |
| 1000:0030 | 103c:322a | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 2     | mpt        | [2F26C69137](<Desktop/Dell/OptiPlex/OptiPlex 390/A5CC20B80AD3/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/2F26C69137>) |
| 1000:0054 | 1028:1f09 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mpt        | [E98F23CD45](<Server/Dell/PowerEdge/PowerEdge SC1435/269A637D74C2/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/E98F23CD45>) |
| 1000:0058 | 1028:1f10 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mpt        | [5D650E34E4](<Server/Dell/PowerEdge/PowerEdge R410/E1AADBB39AD2/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/5D650E34E4>) |
| 1425:4502 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Storage Cont... | 2     |            | [BD9D4BB7A3](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/10EF43C278BD/OPNSENSE-22.1.4/13.0-STABLE/AMD64/BD9D4BB7A3>) |
| 1425:5507 |           | Chelsio Commu... | T520-SO Unified Wire Storage Cont... | 2     |            | [16C226553C](<Desktop/ASRock/B550M/B550M Phantom Gaming 4/BB7614C3933F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/16C226553C>) |
| 1425:5583 |           | Chelsio Commu... | T540-5083 Unified Wire Storage Co... | 2     |            | [55E9734C09](<Desktop/JGINYUE/B85I/B85I PLUS V1.0/C745913DBF54/OPNSENSE-22.1.6/13.0-STABLE/AMD64/55E9734C09>) |
| 5853:0001 | 5853:0001 | XenSource        | Xen Platform Device                  | 2     | xenpci     | [FFB1FD95D3](<Desktop/PC Engines/apu/apu4/8CB6C93947A1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/FFB1FD95D3>) |
| 9004:5078 | 9004:7850 | Adaptec          | AIC-7850T/7856T [AVA-2902/4/6 / A... | 2     | ahc        | [C67CCF8BC6](<Desktop/Dell/Inspiron/Inspiron 530/3762C968ACCD/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C67CCF8BC6>) |
| 1000:0001 | 1000:1000 | Broadcom / LSI   | 53c810                               | 1     | sym        | [4EE625240F](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VII HERO/37724E1F8F3B/FREEBSD-12.1-STABLE/12.1-STABLE-20200612/AMD64/4EE625240F>) |
| 1000:000f | 1000:1000 | Broadcom / LSI   | 53c875                               | 1     | sym        | [DAE16641BB](<Desktop/ASUSTek Computer/M2/M2NPV-MX/14DC624B8825/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/DAE16641BB>) |
| 1000:0030 | 1000:10b0 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 1000:0030 | 1000:50c0 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [7E51DD7048](<Server/Supermicro/Super/Super Server/436CD64AB3E6/FREEBSD-12.3/12.3-RELEASE/AMD64/7E51DD7048>) |
| 1000:0030 | 1028:016c | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 1000:0030 | 1734:1041 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [ADB972BF8E](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX200S2/C657395B089D/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/ADB972BF8E>) |
| 1000:0054 | 103c:0a98 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 1     | mpt        | [655FC531FB](<Desktop/Hewlett-Packard/xw8600/xw8600 Workstation/0566D4E23583/OPNSENSE-22.1.9/13.0-STABLE/AMD64/655FC531FB>) |
| 1000:0056 | 1000:1000 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [7B2DE50C60](<Desktop/Apple/Xserve3/Xserve3,1/D499BA477C7F/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/7B2DE50C60>) |
| 1000:0056 | 1734:1131 | Broadcom / LSI   | SAS1064ET PCI-Express Fusion-MPT SAS | 1     | mpt        | [FF2213E848](<Desktop/Fujitsu/CELSIUS/CELSIUS M470-2/50E1DC1E3DE9/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/FF2213E848>) |
| 1000:0058 | 103c:130b | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [6DDE87584C](<Desktop/Hewlett-Packard/Z800/Z800 Workstation/E946340732BD/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/6DDE87584C>) |
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
| 9005:8017 | 9005:0045 | Adaptec          | ASC-29320ALP U320                    | 1     | ahd        | [EB73C9D13D](<Desktop/Supermicro/X9/X9DAi/558BB9BB7FC9/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/EB73C9D13D>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1567 | 1022:1567 | AMD              | Mullins IOMMU                        | 157   |            | [7AAF2D91BA](<Desktop/PC Engines/APU/APU2/5DC664E10D36/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7AAF2D91BA>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 135   |            | [9E817A9114](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/94CBCA0E43E1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/9E817A9114>) |
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 112   |            | [BC15367E9F](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BC15367E9F>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 112   |            | [BC15367E9F](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BC15367E9F>) |
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 99    |            | [BC15367E9F](<Desktop/Apple/MacPro5/MacPro5,1/286F84CA3879/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BC15367E9F>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 89    | amdiommu   | [683591700F](<Notebook/Lenovo/ThinkPad/ThinkPad A485 20MVS0LG00/F4E54EA14D75/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/683591700F>) |
| 8086:6f76 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 87    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f88 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 86    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f8a |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 86    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fae |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 86    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6faf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 86    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fbc |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 84    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fbd |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 84    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fbe |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 84    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fbf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 84    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 83    | amdiommu   | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 8086:6f1d | 8086:6f1d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f1e | 8086:6f1e | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f1f | 8086:6f1f | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f71 | 8086:6f71 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f98 | 8086:6f98 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f99 | 8086:6f99 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f9a | 8086:6f9a | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f9c | 8086:6f9c | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fa0 | 8086:6fa0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fa8 | 8086:6fa8 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6faa | 8086:6faa | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fab | 8086:6fab | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fc0 | 8086:6fc0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fe0 | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fe1 | 8086:6fe1 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6ff8 | 8086:6ff8 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6ffc | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6ffd | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6ffe | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 71    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:1f15 |           | Intel            | Atom processor C2000 SMBus 2.0       | 70    |            | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 8086:1f16 |           | Intel            | Atom processor C2000 RCEC            | 70    |            | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 8086:6fe2 | 8086:6fe2 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 70    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fe3 | 8086:6fe3 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 70    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f81 | 8086:6f81 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 69    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb0 | 8086:6fb0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 69    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb1 | 8086:6fb1 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 69    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb2 | 8086:6fb2 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 69    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb3 | 8086:6fb3 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 69    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fac | 8086:6fac | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 63    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fad | 8086:6fad | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 63    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 103c:3306 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Sl... | 62    |            | [A2BC442ACD](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/DE1062729CEF/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/A2BC442ACD>) |
| 103c:3307 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Ma... | 62    |            | [A2BC442ACD](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/DE1062729CEF/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/A2BC442ACD>) |
| 8086:2018 |           | Intel            | Sky Lake-E M2PCI Registers           | 61    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2035 |           | Intel            | Sky Lake-E RAS Configuration Regi... | 61    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:7808 | 1022:7808 | AMD              | FCH USB EHCI Controller              | 264   | ehci       | [C781BD46DC](<Mini Pc/CompuLab/fit-PC/fit-PC4/C2BC24039346/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C781BD46DC>) |
| 1022:7814 | 1022:1410 | AMD              | FCH USB XHCI Controller              | 241   | xhci       | [7AAF2D91BA](<Desktop/PC Engines/APU/APU2/5DC664E10D36/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7AAF2D91BA>) |
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 241   | xhci       | [0D62222B7A](<Desktop/Protectli/FW/FW6/901BD973C9B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0D62222B7A>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 210   | xhci       | [406FE72C22](<Desktop/Protectli/FW4/FW4B/F5081B045894/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/406FE72C22>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 204   | xhci       | [68A847F5C2](<Desktop/Others/Others/Others/555BBD33BFAE/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/68A847F5C2>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 146   | xhci       | [7B36D32911](<Mini Pc/AMI/Aptio/Aptio CRB/032FDEA67E2A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/7B36D32911>) |
| 1022:149c | 1022:148c | AMD              | Matisse USB 3.0 Host Controller      | 99    | xhci       | [2E842DDB27](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/2E842DDB27>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 97    | xhci       | [5536740301](<Firewall/Sophos/SG/SG/F5F7C1523465/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/5536740301>) |
| 1022:43d5 | 1b21:1142 | AMD              | 400 Series Chipset USB 3.1 XHCI C... | 90    | xhci       | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 8086:4ded | 8086:7270 | Intel            | Jasper Lake USB 3.1 XHCI Host Con... | 79    | xhci       | [4243D313A1](<Desktop/GoWin Solution/R86/R86S/F79E140BEE45/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/4243D313A1>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 78    | xhci       | [33C59C687D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B28E7D1C74B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/33C59C687D>) |
| 8086:9c26 | 8086:7270 | Intel            | 8 Series USB EHCI #1                 | 72    | ehci       | [33C59C687D](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/B28E7D1C74B7/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/33C59C687D>) |
| 1002:4396 | 1002:4396 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 71    | ehci       | [19786EDC61](<Desktop/PC Engines/APU/APU/F9CD3CBF9201/OPNSENSE-22.7.8/13.1-RELEASE-P5/AMD64/19786EDC61>) |
| 8086:9ca6 | 8086:7270 | Intel            | Wildcat Point-LP USB EHCI Controller | 71    | ehci       | [7CCCECFDE1](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/3A76FE02D6F8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CCCECFDE1>) |
| 8086:9cb1 | 8086:7270 | Intel            | Wildcat Point-LP USB xHCI Controller | 71    | xhci       | [7CCCECFDE1](<Desktop/Intel/Q3XXG4-P/Q3XXG4-P V1.0/3A76FE02D6F8/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7CCCECFDE1>) |
| 8086:0f34 | 8086:0f34 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 67    | ehci       | [6C145361A3](<Desktop/R & S Cybersecurity gateprotect/GP/GP-7543/215B98E0EDE1/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/6C145361A3>) |
| 1002:4397 | 1002:4397 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 66    | ohci       | [19786EDC61](<Desktop/PC Engines/APU/APU/F9CD3CBF9201/OPNSENSE-22.7.8/13.1-RELEASE-P5/AMD64/19786EDC61>) |
| 1022:7808 | 1734:1202 | AMD              | FCH USB EHCI Controller              | 62    | ehci       | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 103c:3300 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 62    | uhci       | [A2BC442ACD](<Desktop/Hewlett-Packard/ProLiant/ProLiant MicroServer Gen8/DE1062729CEF/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/A2BC442ACD>) |
| 1022:149c | 1022:1486 | AMD              | Matisse USB 3.0 Host Controller      | 60    | xhci       | [072F2A6C27](<Desktop/ASRock/X570/X570 Phantom Gaming 4/2C34712FE131/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/072F2A6C27>) |
| 1022:7814 | 1734:1202 | AMD              | FCH USB XHCI Controller              | 58    | xhci       | [0BF1C2ABEF](<Desktop/Fujitsu/FUTRO/FUTRO S920/F2E4331EFAE2/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/0BF1C2ABEF>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 57    | ehci       | [72EAA7A90F](<Firewall/Others/Others/Others/3ACA6E873E6C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/72EAA7A90F>) |
| 1002:4399 | 1002:4399 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 55    | ohci       | [19786EDC61](<Desktop/PC Engines/APU/APU/F9CD3CBF9201/OPNSENSE-22.7.8/13.1-RELEASE-P5/AMD64/19786EDC61>) |
| 8086:8c26 | 8086:8c26 | Intel            | 8 Series/C220 Series Chipset Fami... | 54    | ehci       | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 8086:8c2d | 8086:8c2d | Intel            | 8 Series/C220 Series Chipset Fami... | 54    | ehci       | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 1022:149c | 1043:87c0 | AMD              | Matisse USB 3.0 Host Controller      | 52    | xhci       | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 8086:8c31 | 8086:8c31 | Intel            | 8 Series/C220 Series Chipset Fami... | 51    | xhci       | [E331FE5E06](<Firewall/Sophos/SG/SG/0A73F0DCC457/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/E331FE5E06>) |
| 1106:3483 | 1106:3483 | VIA Technologies | VL805/806 xHCI USB 3.0 Controller    | 50    | xhci       | [D5C5F30A2D](<Desktop/BESSTAR Tech/HM/HM80/AB699ED4C2D9/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/D5C5F30A2D>) |
| 1022:43ee | 1b21:1142 | AMD              | 500 Series Chipset USB 3.1 XHCI C... | 49    | xhci       | [D22C37FA81](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/7F8CFAEEF0F8/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/D22C37FA81>) |
| 1022:7807 | 103c:213d | AMD              | FCH USB OHCI Controller              | 47    | ohci       | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 1022:7808 | 103c:213d | AMD              | FCH USB EHCI Controller              | 47    | ehci       | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 1022:7814 | 103c:213d | AMD              | FCH USB XHCI Controller              | 47    | xhci       | [BD620F0FC0](<Desktop/Hewlett-Packard/t620/t620 PLUS Quad Core TC/9A25CF2F72B9/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/BD620F0FC0>) |
| 8086:27c8 | 8086:27c8 | Intel            | NM10/ICH7 Family USB UHCI Control... | 47    | uhci       | [1C0805F9AE](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1C0805F9AE>) |
| 8086:2830 | 8086:2830 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 47    | uhci       | [81BBACBFEE](<Firewall/Sophos/UTM/UTM/D0D282702135/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/81BBACBFEE>) |
| 8086:2836 | 8086:2836 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 47    | ehci       | [81BBACBFEE](<Firewall/Sophos/UTM/UTM/D0D282702135/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/81BBACBFEE>) |
| 8086:27c9 | 8086:27c9 | Intel            | NM10/ICH7 Family USB UHCI Control... | 46    | uhci       | [1C0805F9AE](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1C0805F9AE>) |
| 8086:2831 | 8086:2831 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 46    | uhci       | [81BBACBFEE](<Firewall/Sophos/UTM/UTM/D0D282702135/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/81BBACBFEE>) |
| 8086:27cc | 8086:27cc | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 45    | ehci       | [1C0805F9AE](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1C0805F9AE>) |
| 1b21:1042 | 1043:8488 | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 44    | xhci       | [88929A3594](<Desktop/ASUSTek Computer/SABERTOOTH/SABERTOOTH Z77/46CCAEB3C831/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/88929A3594>) |
| 8086:1c26 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 43    | ehci       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:1c2d | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 43    | ehci       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:27ca | 8086:27ca | Intel            | NM10/ICH7 Family USB UHCI Control... | 43    | uhci       | [1C0805F9AE](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1C0805F9AE>) |
| 8086:0f35 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 41    | xhci       | [FAD0A431E5](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FAD0A431E5>) |
| 8086:27cb | 8086:27cb | Intel            | NM10/ICH7 Family USB UHCI Control... | 41    | uhci       | [1C0805F9AE](<Firewall/Sophos/UTM/UTM/6A773F9DB6FF/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1C0805F9AE>) |
| 8086:8c31 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 40    | xhci       | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 8086:8c26 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 39    | ehci       | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 8086:8c2d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 39    | ehci       | [1115D508C1](<Desktop/Dell/OptiPlex/OptiPlex 9020/AE411B80FDD5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1115D508C1>) |
| 1022:7807 | 103c:8103 | AMD              | FCH USB OHCI Controller              | 38    | ohci       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:7808 | 103c:8103 | AMD              | FCH USB EHCI Controller              | 38    | ehci       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |
| 1022:7814 | 103c:8103 | AMD              | FCH USB XHCI Controller              | 38    | xhci       | [5CD982C2EE](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/C9805B12DFC4/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/5CD982C2EE>) |

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
| bdbd:a10b | bdbd:a10b | Blackmagic De... | Blackmagic DeckLink                  | 1     |            | [020CCD74D8](<Desktop/Hewlett-Packard/Compaq/Compaq Elite 8300 CMT/D5FB9BCC8299/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/020CCD74D8>) |
| bdbd:a143 | bdbd:a143 | Blackmagic De... | DeckLink Mini Recorder 4K            | 1     |            | [30A582FCCB](<Desktop/ASRockRack/EP2/EP2C612D16FM/194ABDFCA96A/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/30A582FCCB>) |

### Wireless controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7360 | 8086:0020 | Intel            | XMM7360 LTE Advanced Modem           | 7     |            | [B2024820D1](<Notebook/Lenovo/ThinkPad/ThinkPad P53 20QNCTO1WW/EDACF56B05E1/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/B2024820D1>) |
| 8086:7360 | 1028:5820 | Intel            | XMM7360 LTE Advanced Modem           | 1     |            | [1BB6C1F63F](<Notebook/Dell/Latitude/Latitude 5400/418002D1A36C/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/1BB6C1F63F>) |
| 8086:7560 | 1cf8:8654 | Intel            | XMM7560 LTE Advanced Pro Modem       | 1     |            | [809DA57D90](<Notebook/Lenovo/ThinkPad/ThinkPad X1 Carbon Gen 10 21CB000DUS/32571058500F/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/809DA57D90>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 109   |            | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 109   |            | [AB7E64F657](<Desktop/ASRockRack/EPYC3101/EPYC3101D4I-2T/9A04D58CD175/FREEBSD-13.1-P5/13.1-RELEASE-P2/AMD64/AB7E64F657>) |
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 101   |            | [D22C37FA81](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/7F8CFAEEF0F8/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/D22C37FA81>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 82    |            | [D22C37FA81](<Desktop/Gigabyte Technology/B550M/B550M AORUS PRO-P/7F8CFAEEF0F8/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/D22C37FA81>) |
| 1022:1485 | 1043:87c0 | AMD              | Starship/Matisse Reserved SPP        | 39    |            | [2E842DDB27](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/2E842DDB27>) |
| 1022:148a | 1043:87c0 | AMD              | Starship/Matisse PCIe Dummy Function | 39    |            | [2E842DDB27](<Desktop/ASUSTek Computer/ROG/ROG CROSSHAIR VIII HERO/25E14418372B/FREEBSD-13.1-P5/13.1-RELEASE-P3/AMD64/2E842DDB27>) |
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 37    |            | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 8086:31a2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 33    |            | [8D3AB2CAB5](<Desktop/MW/GMLK-2/GMLK-2_5G4L/6030EB8ACCF5/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/8D3AB2CAB5>) |
| 1022:1455 | 1043:8747 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 24    |            | [334575B738](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/A1AB004D09A5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/334575B738>) |
| 1022:145a | 1043:8747 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 24    |            | [334575B738](<Desktop/ASUSTek Computer/PRIME/PRIME A320I-K/A1AB004D09A5/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/334575B738>) |
| 1022:145a |           | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 22    |            | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 1022:145a | 1022:7901 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 21    |            | [B09FF8826C](<Notebook/Deciso/NetBoard-A/NetBoard-A10/65ED7DF10E1E/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/B09FF8826C>) |
| 8086:a1ec | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 0    | 18    |            | [05566134F9](<Desktop/Supermicro/SYS-E300/SYS-E300-9D-4CN8TP/A87F5F2F591B/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/05566134F9>) |
| 0000:0000 |           |                  |                                      | 17    |            | [ABE21B9C9E](<Desktop/ASUSTek Computer/All/All Series/E6AD36953D33/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/ABE21B9C9E>) |
| 1022:1485 | 1043:8808 | AMD              | Starship/Matisse Reserved SPP        | 14    |            | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 1022:148a | 1043:8808 | AMD              | Starship/Matisse PCIe Dummy Function | 14    |            | [4D9A4BFC40](<Desktop/ASUSTek Computer/TUF/TUF Gaming B450M-PLUS II/C0F6B83E60A9/MIDNIGHTBSD-2.2.6/2.2.6/AMD64/4D9A4BFC40>) |
| 8086:a1ed | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 1    | 14    |            | [2CBA6FBBB7](<Desktop/Supermicro/SYS-5019/SYS-5019D-FN8TP-2-NC041/F87B609ACF03/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/2CBA6FBBB7>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 13    |            | [3D06B605C5](<Desktop/Huanan/X99-F8D/X99-F8D V2.4/1C23933CF038/FREEBSD-13.1/13.1-RELEASE/AMD64/3D06B605C5>) |
| 8086:8d7c | 1028:0601 | Intel            | C610/X99 series chipset SPSR         | 11    |            | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [66C10B64CB](<Server/Supermicro/Super/Super Server/972BB3DC5295/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/66C10B64CB>) |
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:9d35 | 17aa:2238 | Intel            | Sunrise Point-LP Integrated Senso... | 8     |            | [4CBD9F9314](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FQ000QUS/A325841E215E/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/4CBD9F9314>) |
| 8086:a1ec | 1028:07c9 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 1022:145a | 1002:15dd | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 6     |            | [38D7F55EF7](<Desktop/ASRockRack/X470/X470D4U/8404FC50C36B/FREEBSD-12.3-P8/12.3-RELEASE-P6/AMD64/38D7F55EF7>) |
| 8086:8d7c | 1043:8600 | Intel            | C610/X99 series chipset SPSR         | 6     |            | [ABE21B9C9E](<Desktop/ASUSTek Computer/All/All Series/E6AD36953D33/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/ABE21B9C9E>) |
| 8086:8d7c | 15d9:0834 | Intel            | C610/X99 series chipset SPSR         | 6     |            | [59FF2014E5](<Server/Supermicro/Super/Super Server/C53FD6545133/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/59FF2014E5>) |
| 8086:8d7c | 1849:8d7c | Intel            | C610/X99 series chipset SPSR         | 6     |            | [30A582FCCB](<Desktop/ASRockRack/EP2/EP2C612D16FM/194ABDFCA96A/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/30A582FCCB>) |
| 1022:1485 | 1462:7c02 | AMD              | Starship/Matisse Reserved SPP        | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 1022:148a | 1462:7c02 | AMD              | Starship/Matisse PCIe Dummy Function | 5     |            | [D2ECB6259C](<Desktop/MSI/MS-7/MS-7C02/08D53ADE90F9/FREEBSD-13.1-BETA2/13.1-BETA2/AMD64/D2ECB6259C>) |
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 5     |            | [03D71C925B](<Desktop/iEi/Z/Z596/4966738C3457/OPNSENSE-22.7/13.1-RELEASE/AMD64/03D71C925B>) |
| 1022:15e6 | 1849:15e6 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 4     |            | [78D2871C20](<Desktop/ASRock/4X4/4X4-V1000/6E992B41BC1D/OPNSENSE-22.1.1/13.0-STABLE/AMD64/78D2871C20>) |
| 8086:8d7c | 103c:212b | Intel            | C610/X99 series chipset SPSR         | 4     |            | [7BC6506336](<Desktop/Hewlett-Packard/Z440/Z440 Workstation/2A387F0E6BE6/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/7BC6506336>) |
| 8086:8d7c | 15d9:0832 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [1499A2903D](<Server/Supermicro/Super/Super Server/7E6D506E6800/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1499A2903D>) |
| 8086:a135 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [7BD99B62AB](<Server/Supermicro/Super/Super Server/A912B2977FCE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7BD99B62AB>) |
| 8086:a1ec | 1028:0716 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 1022:1455 | 1462:7b86 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1022:145a | 1002:15d8 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [127E0126D1](<Desktop/ASRock/B450/B450 Gaming K4/ED84CEC3B15B/FREEBSD-13.1-P3/13.1-RELEASE-P3/AMD64/127E0126D1>) |
| 1022:145a | 1043:876b | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [92EAB8D065](<Desktop/ASUSTek Computer/ROG/ROG STRIX B450-F GAMING II/1AD27D04291F/HELLOSYSTEM-0.7.0/13.1-RELEASE-P3/AMD64/92EAB8D065>) |
| 1022:145a | 1462:7b86 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 3     |            | [ED656E816F](<Desktop/MSI/MS-7/MS-7B86/38EE6A772064/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/ED656E816F>) |
| 1028:0012 | 1028:0012 | Dell             | Remote Access Card 4 Daughter Car... | 3     | uart       | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 1028:0014 | 1028:0014 | Dell             | Remote Access Card 4 Daughter Car... | 3     |            | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 3     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 15ec:5000 | 15ec:5000 | Beckhoff         |                                      | 3     |            | [6DB720018B](<Desktop/Beckhoff Automation/CBxx/CBxx63/D2340951707E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/6DB720018B>) |
| 8086:5aa2 | 8086:5aa2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     |            | [E87866BF5A](<Desktop/NF692/1/1.0/9852CE16A74F/OPNSENSE-22.1.8/13.0-STABLE/AMD64/E87866BF5A>) |
| 8086:8d7c | 1028:0617 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [F3C197BDFB](<Desktop/Dell/Precision/Precision Tower 5810/0A60A9F9EA30/OPNSENSE-22.1.8/13.0-STABLE/AMD64/F3C197BDFB>) |
| 8086:8d7c | 1028:0639 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 8086:8d7c | 15d9:0844 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [1FFD63A929](<Desktop/Supermicro/PIO-618/PIO-618U-T4T+-ST031/E62C2994F73D/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/1FFD63A929>) |
| 8086:8d7c | 15d9:0857 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [E1EBA3B8F0](<Server/Supermicro/X10/X10SRA/0AF208B6DAE7/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E1EBA3B8F0>) |
| 8086:8d7c | 1734:1201 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [DAE7027898](<Desktop/Fujitsu/PRIMERGY/PRIMERGY TX2560 M1/4C2638BCEE71/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/DAE7027898>) |
| 8086:9d35 | 17aa:2259 | Intel            | Sunrise Point-LP Integrated Senso... | 3     |            | [64D42B9C5F](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/64D42B9C5F>) |

