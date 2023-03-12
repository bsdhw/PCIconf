Most popular PCI devices in All In Ones
=======================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in All In Ones ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
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
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
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
| 10de:0aab | 10de:cb79 | Nvidia           | MCP79 PCI Bridge                     | 11    | pcib       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0ac4 |           | Nvidia           | MCP79 PCI Express Bridge             | 11    | pcib       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0ac6 |           | Nvidia           | MCP79 PCI Express Bridge             | 11    | pcib       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0ac7 |           | Nvidia           | MCP79 PCI Express Bridge             | 11    | pcib       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0aa0 |           | Nvidia           | MCP79 PCI Express Bridge             | 9     | pcib       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0a82 |           | Nvidia           | MCP79 Host Bridge                    | 7     | hostb      | [64B17B1B35](<All In One/Apple/iMac9/iMac9,1/89C4A7761383/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/64B17B1B35>) |
| 10de:0aae | 10de:cb79 | Nvidia           | MCP79 LPC Bridge                     | 7     | isab       | [64B17B1B35](<All In One/Apple/iMac9/iMac9,1/89C4A7761383/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/64B17B1B35>) |
| 8086:2448 |           | Intel            | 82801 Mobile PCI Bridge              | 6     | pcib       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 104c:823e |           | Texas Instrum... | XIO2213A/B/XIO2221 PCI Express to... | 5     | pcib       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0aac | 10de:cb79 | Nvidia           | MCP79 LPC Bridge                     | 4     | isab       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:1604 | 8086:1604 | Intel            | Broadwell-U Host Bridge -OPI         | 4     | hostb      | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:2815 | 106b:00a0 | Intel            | 82801HM (ICH8M) LPC Interface Con... | 4     | isab       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:283f |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 4     | pcib       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2845 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 4     | pcib       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2847 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 4     | pcib       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2849 |           | Intel            | 82801H (ICH8 Family) PCI Express ... | 4     | pcib       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2a00 | 106b:00a0 | Intel            | Mobile PM965/GM965/GL960 Memory C... | 4     | hostb      | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2a01 |           | Intel            | Mobile PM965/GM965/GL960 PCI Expr... | 4     | pcib       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:9c94 | 8086:9c94 | Intel            | Wildcat Point-LP PCI Express Root... | 4     | pcib       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:9c96 | 8086:9c96 | Intel            | Wildcat Point-LP PCI Express Root... | 4     | pcib       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:9c9a | 8086:9c9a | Intel            | Wildcat Point-LP PCI Express Root... | 4     | pcib       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:9cc3 | 8086:9cc3 | Intel            | Wildcat Point-LP LPC Controller      | 4     | isab       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 10de:0a80 |           | Nvidia           | MCP79 Host Bridge                    | 3     | hostb      | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 1022:1452 |           | AMD              | Family 17h (Models 00h-1fh) PCIe ... | 2     | hostb      | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 8086:1578 |           | Intel            | DSL6540 Thunderbolt 3 Bridge [Alp... | 2     | pcib       | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:15d3 |           | Intel            | JHL6540 Thunderbolt 3 Bridge (C s... | 2     | pcib       | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:1c10 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pcib       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:1c12 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pcib       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:1c14 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pcib       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:1c18 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pcib       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:1c44 | 8086:7270 | Intel            | Z68 Express Chipset LPC Controller   | 2     | isab       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:244e | 8086:7270 | Intel            | 82801 PCI Bridge                     | 2     | pcib       | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 8086:27a0 | 8086:7270 | Intel            | Mobile 945GM/PM/GMS, 943/940GML a... | 2     | hostb      | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27a1 |           | Intel            | Mobile 945GM/PM/GMS, 943/940GML a... | 2     | pcib       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27b9 | 8086:7270 | Intel            | 82801GBM (ICH7-M) LPC Interface B... | 2     | isab       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27d0 |           | Intel            | NM10/ICH7 Family PCI Express Port 1  | 2     | pcib       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27d2 |           | Intel            | NM10/ICH7 Family PCI Express Port 2  | 2     | pcib       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:3ec2 | 1028:084c | Intel            | 8th Gen Core Processor Host Bridg... | 2     | hostb      | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 8086:4384 | 1028:0a48 | Intel            | 500 Series Chipset Family LPC Con... | 2     | isab       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:43bb | 1028:0a48 | Intel            | 500 Series Chipset Family PCIe Po... | 2     | pcib       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:43c4 | 1028:0a48 | Intel            | 500 Series Chipset Family SCS1: eMMC | 2     | pcib       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:9b53 | 1028:0a48 | Intel            | Comet Lake-S 6c Host Bridge/DRAM ... | 2     | hostb      | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:a110 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | pcib       | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:a111 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | pcib       | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:a145 | 8086:7270 | Intel            | Z170 Chipset LPC/eSPI Controller     | 2     | isab       | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:a306 | 1028:084c | Intel            | Q370 Chipset LPC/eSPI Controller     | 2     | isab       | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 8086:a33d | 1028:084c | Intel            | Cannon Lake PCH PCI Express Root ... | 2     | pcib       | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 1022:1450 | 1022:1450 | AMD              | Family 17h (Models 00h-0fh) Root ... | 1     | hostb      | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:1453 | 1022:1453 | AMD              | Family 17h (Models 00h-0fh) PCIe ... | 1     | pcib       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:1454 | 1022:1454 | AMD              | Family 17h (Models 00h-0fh) Inter... | 1     | pcib       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:525a | 1028:084c | Realtek Semic... | RTS525A PCI Express Card Reader      | 2     | rtsx       | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 10ec:525a | 1028:0a48 | Realtek Semic... | RTS525A PCI Express Card Reader      | 2     | rtsx       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 10ec:5229 | 17aa:3636 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     |            | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 10ec:5229 | 17aa:365e | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx       | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 10ec:5229 | 17aa:36d0 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     | rtsx       | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 10ec:522a | 1028:06d0 | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     |            | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 10ec:525a | 1028:0934 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx       | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 11    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9cba | 8086:9cba | Intel            | Wildcat Point-LP MEI Controller #1   | 4     |            | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     |            | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:43e0 | 1028:0a48 | Intel            | Tiger Lake-H Management Engine In... | 2     |            | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:a13a | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:a360 | 1028:084c | Intel            | Cannon Lake PCH HECI Controller      | 2     |            | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 10ec:816a | 10ec:8168 | Realtek Semic... | RTL8111xP UART #1                    | 1     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:02e0 | 1028:0953 | Intel            | Comet Lake Management Engine Inte... | 1     |            | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:1c3a | 1043:1c3a | Intel            | 6 Series/C200 Series Chipset Fami... | 1     |            | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:1c3a | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     |            | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 8086:1e3a | 1043:844d | Intel            | 7 Series/C216 Chipset Family MEI ... | 1     |            | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 1     |            | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 1     |            | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 8086:8c3a | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     |            | [951EB91342](<All In One/Acidanthera/iMac15/iMac15,1/EC96C3DF5397/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/951EB91342>) |
| 8086:8c3a | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     |            | [DBEE391B8D](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/0790B41B771D/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DBEE391B8D>) |
| 8086:8c3a | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     |            | [07DC4A3178](<All In One/Apple/iMac14/iMac14,2/07EF6154280E/FREEBSD-13.1/13.1-RELEASE/AMD64/07DC4A3178>) |
| 8086:8c3d | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | uart       | [951EB91342](<All In One/Acidanthera/iMac15/iMac15,1/EC96C3DF5397/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/951EB91342>) |
| 8086:8c3d | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | uart       | [DBEE391B8D](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/0790B41B771D/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DBEE391B8D>) |
| 8086:9d3a | 1028:06d0 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 8086:9d3a | 103c:81ba | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [C2204A3DD2](<All In One/Hewlett-Packard/24/24-g038ur/39C749CF5A44/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/C2204A3DD2>) |
| 8086:9d3a | 1462:aec1 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:9d3a | 8086:7270 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:9d3a | 8086:9d3a | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:a13a | 17aa:3636 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 8086:a13a | 17aa:36cc | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 8086:a2ba | 1043:8694 | Intel            | 200 Series PCH CSME HECI #1          | 1     |            | [D1CC7C07E0](<All In One/Philips/AIO/AIO/BEB0605E57DD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D1CC7C07E0>) |
| 8086:a360 | 1028:0934 | Intel            | Cannon Lake PCH HECI Controller      | 1     |            | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:a360 | 1043:8694 | Intel            | Cannon Lake PCH HECI Controller      | 1     |            | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| 8086:a360 | 1849:a360 | Intel            | Cannon Lake PCH HECI Controller      | 1     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:a363 | 1028:0934 | Intel            | Cannon Lake PCH Active Management... | 1     |            | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:a3ba | 8086:7270 | Intel            | Comet Lake PCH-V HECI Controller     | 1     |            | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:1578 | 103c:8430 | AMD              | Carrizo Platform Security Processor  | 1     |            | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 1022:15df | 1043:876b | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 13    | fwohci     | [64B17B1B35](<All In One/Apple/iMac9/iMac9,1/89C4A7761383/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/64B17B1B35>) |
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 5     | fwohci     | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 11c1:5811 | 11c1:5811 | LSI              | FW322/323 [TrueFire] 1394a Contro... | 2     | fwohci     | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0867 | 106b:00ad | Nvidia           | C79 [GeForce 9400]                   | 6     | nvidia     | [64B17B1B35](<All In One/Apple/iMac9/iMac9,1/89C4A7761383/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/64B17B1B35>) |
| 8086:162b | 1e50:8002 | Intel            | Iris Graphics 6100                   | 4     | vgapci     | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 1002:94c8 | 106b:0084 | AMD              | RV610/M74 [Mobility Radeon HD 240... | 3     | vgapci     | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 10de:0869 | 106b:00b4 | Nvidia           | MCP7A [GeForce 9400]                 | 3     | nvidia     | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 1002:71c5 | 106b:0080 | AMD              | RV530/M56-P [Mobility Radeon X1600]  | 2     | radeon     | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:3e92 | 1028:084c | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 2     | i915       | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 8086:9bc8 | 1028:0a48 | Intel            | CometLake-S GT2 [UHD Graphics 630]   | 2     | i915       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 1002:6665 | 103c:8430 | AMD              | Jet PRO [Radeon R5 M230 / R7 M260... | 1     | vgapci     | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 1002:6720 | 106b:0b00 | AMD              | Blackcomb [Radeon HD 6970M/6990M]    | 1     | radeon     | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 1002:6740 | 106b:6740 | AMD              | Whistler [Radeon HD 6730M/6770M/7... | 1     | vgapci     | [C9A8D5ADE5](<All In One/Apple/iMac12/iMac12,1/E13BF4839DA0/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C9A8D5ADE5>) |
| 1002:67df | 148c:2372 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 1     | amdgpu     | [1917CD73E1](<All In One/Acidanthera/iMac15/iMac15,1/CBF8089199B1/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1917CD73E1>) |
| 1002:67df | 1682:9480 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 1     | amdgpu     | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1002:67df | 1682:c580 | AMD              | Ellesmere [Radeon RX 470/480/570/... | 1     | amdgpu     | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 1002:67ef | 106b:016b | AMD              | Baffin [Radeon RX 460/560D / Pro ... | 1     | amdgpu     | [7B20265C8E](<All In One/Apple/iMac18/iMac18,2/47800D718E3D/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/7B20265C8E>) |
| 1002:6819 | 106b:014e | AMD              | Pitcairn PRO [Radeon HD 7850 / R7... | 1     | amdgpu     | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 1002:68a1 | 106b:00cc | AMD              | Broadway PRO [Mobility Radeon HD ... | 1     | radeon     | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 1002:9488 | 106b:00b6 | AMD              | RV730/M96-XT [Mobility Radeon HD ... | 1     | radeon     | [73912D5852](<All In One/Apple/iMac10/iMac10,1/079C33A20928/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/73912D5852>) |
| 1002:9583 | 106b:0083 | AMD              | RV630/M76 [Mobility Radeon HD 260... | 1     | vgapci     | [99F564E44A](<All In One/Apple/iMac7/iMac7,1/637536FD9638/FREEBSD-12.3/12.3-RELEASE/AMD64/99F564E44A>) |
| 1002:98e4 | 103c:8430 | AMD              | Stoney [Radeon R2/R3/R4/R5 Graphics] | 1     | vgapci     | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 10de:062e | 106b:0605 | Nvidia           | G94 [GeForce 9600 GT]                | 1     | nvidia     | [7154BEA350](<All In One/Apple/iMac9/iMac9,1/459A03988F01/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/7154BEA350>) |
| 10de:0dea | 17aa:365e | Nvidia           | GF108M [GeForce 610M]                | 1     | nvidia     | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 10de:0fe0 | 106b:010b | Nvidia           | GK107M [GeForce GTX 660M Mac Edit... | 1     | nvidia     | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 10de:0fea | 106b:011f | Nvidia           | GK107M [GeForce GT 755M Mac Edition] | 1     | nvidia     | [07DC4A3178](<All In One/Apple/iMac14/iMac14,2/07EF6154280E/FREEBSD-13.1/13.1-RELEASE/AMD64/07DC4A3178>) |
| 10de:128b | 1462:8c93 | Nvidia           | GK208B [GeForce GT 710]              | 1     | vgapci     | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 10de:1346 | 17aa:3636 | Nvidia           | GM108M [GeForce 930M]                | 1     | vgapci     | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 10de:134e | 1043:1a50 | Nvidia           | GM108M [GeForce 930MX]               | 1     | vgapci     | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 10de:174e | 1028:0953 | Nvidia           | GM108M [GeForce MX110]               | 1     | vgapci     | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:0102 |           | Intel            | 2nd Generation Core Processor Fam... | 1     | vgapci     | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:0102 | 8086:2010 | Intel            | 2nd Generation Core Processor Fam... | 1     | vgapci     | [C9A8D5ADE5](<All In One/Apple/iMac12/iMac12,1/E13BF4839DA0/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C9A8D5ADE5>) |
| 8086:0106 | 1043:844d | Intel            | 2nd Generation Core Processor Fam... | 1     | vgapci     | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 8086:0152 | 1043:0152 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 1     | i915       | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:0412 | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | i915       | [951EB91342](<All In One/Acidanthera/iMac15/iMac15,1/EC96C3DF5397/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/951EB91342>) |
| 8086:0412 | 103c:18e6 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | i915       | [DBEE391B8D](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/0790B41B771D/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DBEE391B8D>) |
| 8086:1912 | 17aa:3636 | Intel            | HD Graphics 530                      | 1     | i915       | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 8086:1912 | 17aa:36cc | Intel            | HD Graphics 530                      | 1     | i915       | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 8086:1916 | 1028:06d0 | Intel            | Skylake GT2 [HD Graphics 520]        | 1     | i915       | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 8086:1916 | 103c:81ba | Intel            | Skylake GT2 [HD Graphics 520]        | 1     | i915       | [C2204A3DD2](<All In One/Hewlett-Packard/24/24-g038ur/39C749CF5A44/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/C2204A3DD2>) |
| 8086:3185 | 0000:2212 | Intel            | GeminiLake [UHD Graphics 600]        | 1     | i915       | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 8086:3e92 | 1028:0934 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 1     | i915       | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:3e92 | 1043:8694 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 1     | i915       | [D1CC7C07E0](<All In One/Philips/AIO/AIO/BEB0605E57DD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D1CC7C07E0>) |
| 8086:3e98 | 1043:8694 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 1     | i915       | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| 8086:3e98 | 1849:3e98 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 1     | i915       | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:5906 | 1462:aec1 | Intel            | HD Graphics 610                      | 1     | vgapci     | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:5917 | 1043:1a50 | Intel            | UHD Graphics 620                     | 1     | i915       | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:5926 | 106b:017e | Intel            | Iris Plus Graphics 640               | 1     | i915       | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:9b41 | 1028:0953 | Intel            | CometLake-U GT2 [UHD Graphics]       | 1     | i915       | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:9bc8 | 8086:2212 | Intel            | CometLake-S GT2 [UHD Graphics 630]   | 1     | i915       | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 11    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 11    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 11    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 11    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 3     |            | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:43ef | 1028:0a48 | Intel            | Tiger Lake-H Shared SRAM             | 2     |            | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:02ef | 1028:0953 | Intel            | Comet Lake PCH-LP Shared SRAM        | 1     |            | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:9d21 | 1028:06d0 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 8086:9d21 | 103c:81ba | Intel            | Sunrise Point-LP PMC                 | 1     |            | [C2204A3DD2](<All In One/Hewlett-Packard/24/24-g038ur/39C749CF5A44/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/C2204A3DD2>) |
| 8086:9d21 | 1462:aec1 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:9d21 | 8086:9d21 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:a121 | 17aa:3636 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 8086:a121 | 17aa:36cc | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 8086:a2a1 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family Po... | 1     |            | [D1CC7C07E0](<All In One/Philips/AIO/AIO/BEB0605E57DD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D1CC7C07E0>) |
| 8086:a36f | 1043:8694 | Intel            | Cannon Lake PCH Shared SRAM          | 1     |            | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| 8086:a36f | 1849:a36f | Intel            | Cannon Lake PCH Shared SRAM          | 1     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:a3a1 | 8086:7270 | Intel            | Cannon Lake PCH Power Management ... | 1     |            | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 11    | nfe        | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 11ab:436a | 11ab:00ba | Marvell Techn... | 88E8058 PCI-E Gigabit Ethernet Co... | 4     | mskc       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 4     | bge        | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 11ab:4362 | 11ab:5321 | Marvell Techn... | 88E8053 PCI-E Gigabit Ethernet Co... | 2     | mskc       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:15bc | 1028:084c | Intel            | Ethernet Connection (7) I219-V       | 2     | em         | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 8086:15f9 | 1028:0a48 | Intel            | Ethernet Connection (14) I219-LM     | 2     | em         | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 10ec:8168 | 1028:06d0 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 10ec:8168 | 1028:0953 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 10ec:8168 | 103c:81ba | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [C2204A3DD2](<All In One/Hewlett-Packard/24/24-g038ur/39C749CF5A44/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/C2204A3DD2>) |
| 10ec:8168 | 103c:8430 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 10ec:8168 | 1043:205f | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 10ec:8168 | 1043:84cd | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 10ec:8168 | 1462:aec1 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 10ec:8168 | 17aa:3636 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 10ec:8168 | 17aa:365e | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 10ec:8168 | 17aa:36cc | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 14e4:1684 | 14e4:1684 | Broadcom         | NetXtreme BCM5764M Gigabit Ethern... | 1     | bge        | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 14e4:1686 | 106b:0110 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 1     | bge        | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:1533 | 8086:0001 | Intel            | I210 Gigabit Network Connection      | 1     | igb        | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:153a | 103c:18e6 | Intel            | Ethernet Connection I217-LM          | 1     | em         | [DBEE391B8D](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/0790B41B771D/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DBEE391B8D>) |
| 8086:153b | 1458:e000 | Intel            | Ethernet Connection I217-V           | 1     | em         | [1917CD73E1](<All In One/Acidanthera/iMac15/iMac15,1/CBF8089199B1/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1917CD73E1>) |
| 8086:15bb | 1028:0934 | Intel            | Ethernet Connection (7) I219-LM      | 1     | em         | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:432b | 106b:008e | Broadcom         | BCM4322 802.11a/b/g/n Wireless LA... | 7     | bwn_pci    | [64B17B1B35](<All In One/Apple/iMac9/iMac9,1/89C4A7761383/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/64B17B1B35>) |
| 168c:002a | 106b:008f | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 5     | ath        | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 4     |            | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 14e4:4328 | 106b:0088 | Broadcom         | BCM4321 802.11a/b/g/n                | 3     | bwn_pci    | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 14e4:4328 | 106b:0087 | Broadcom         | BCM4321 802.11a/b/g/n                | 2     | bwn_pci    | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 168c:0030 | 106b:009a | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 2     | ath        | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:43f0 | 8086:4070 | Intel            | Tiger Lake PCH CNVi WiFi             | 2     | iwlwifi    | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:a370 | 8086:4030 | Intel            | Cannon Lake PCH CNVi WiFi            | 2     | iwm        | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 10ec:8812 | 10ec:8203 | Realtek Semic... | RTL8812AE 802.11ac PCIe Wireless ... | 1     |            | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 10ec:b723 | 103c:81c1 | Realtek Semic... | RTL8723BE PCIe Wireless Network A... | 1     |            | [C2204A3DD2](<All In One/Hewlett-Packard/24/24-g038ur/39C749CF5A44/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/C2204A3DD2>) |
| 10ec:c821 | 103c:831a | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 1     |            | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 10ec:c821 | 10ec:c821 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 1     |            | [D1CC7C07E0](<All In One/Philips/AIO/AIO/BEB0605E57DD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D1CC7C07E0>) |
| 14e4:4328 | 106b:008c | Broadcom         | BCM4321 802.11a/b/g/n                | 1     | bwn_pci    | [4986CC83B9](<All In One/Apple/iMac8/iMac8,1/85EEAFCC93F0/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/4986CC83B9>) |
| 14e4:4331 | 106b:00f4 | Broadcom         | BCM4331 802.11a/b/g/n                | 1     | bwn_pci    | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 14e4:4365 | 11ad:6655 | Broadcom         | BCM43142 802.11b/g/n                 | 1     |            | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 14e4:43a0 | 106b:0111 | Broadcom         | BCM4360 802.11ac Wireless Network... | 1     |            | [07DC4A3178](<All In One/Apple/iMac14/iMac14,2/07EF6154280E/FREEBSD-13.1/13.1-RELEASE/AMD64/07DC4A3178>) |
| 14e4:43ba | 106b:014a | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 1     |            | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 14e4:43ba | 106b:016d | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 1     |            | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 14e4:43ba | 106b:016e | Broadcom         | BCM43602 802.11ac Wireless LAN SoC   | 1     |            | [7B20265C8E](<All In One/Apple/iMac18/iMac18,2/47800D718E3D/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/7B20265C8E>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 1     | ath        | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 168c:0032 | 17aa:3118 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 1     | ath        | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 168c:0032 | 1a3b:1f86 | Qualcomm Atheros | AR9485 Wireless Network Adapter      | 1     | ath        | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 168c:0042 | 17aa:4035 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     |            | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 168c:0042 | 1a3b:2231 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:02f0 | 8086:42a4 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 1     | iwlwifi    | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:08b3 | 8086:8470 | Intel            | Wireless 3160                        | 1     | iwm        | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 1     | iwm        | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 1     | iwm        | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:3166 | 8086:4210 | Intel            | Dual Band Wireless-AC 3165 Plus B... | 1     | iwm        | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | re         | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 10ec:8168 | 1043:8677 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2     | re         | [D1CC7C07E0](<All In One/Philips/AIO/AIO/BEB0605E57DD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D1CC7C07E0>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 2     | bge        | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 10ec:8168 | 1043:8432 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 10ec:8168 | 1458:e000 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 10ec:8168 | 1849:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:153a | 1028:05a4 | Intel            | Ethernet Connection I217-LM          | 1     | em         | [951EB91342](<All In One/Acidanthera/iMac15/iMac15,1/EC96C3DF5397/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/951EB91342>) |
| 8086:15bc | 1043:8672 | Intel            | Ethernet Connection (7) I219-V       | 1     | em         | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 14e4:16bc |           | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 5     | sdhci_pci  | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 197b:2391 | 1043:84c1 | JMicron Techn... | Standard SD Host Controller          | 1     | sdhci_pci  | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 8086:31d0 | 8086:31d0 | Intel            | Celeron/Pentium Silver SD Host Co... | 1     | sdhci_pci  | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:43a4 | 1028:0a48 | Intel            | Tiger Lake-H SPI Controller          | 2     |            | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:a324 | 1028:084c | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 10ec:816c | 10ec:8168 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:02a4 | 1028:0953 | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:a324 | 1028:0934 | Intel            | Cannon Lake PCH SPI Controller       | 1     |            | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:a324 | 1043:8694 | Intel            | Cannon Lake PCH SPI Controller       | 1     |            | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| 8086:a324 | 1849:a324 | Intel            | Cannon Lake PCH SPI Controller       | 1     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:27a3 |           | Intel            | 945GM/GU Chipset Hardware Monitor... | 2     |            | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:a379 | 1028:084c | Intel            | Cannon Lake PCH Thermal Controller   | 2     |            | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 8086:02f9 | 1028:0953 | Intel            | Comet Lake Thermal Subsytem          | 1     | pchtherm   | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:1903 | 8086:1903 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:3b32 |           | Intel            | 5 Series/3400 Series Chipset Ther... | 1     |            | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 8086:9d31 | 1028:06d0 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     |            | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 8086:9d31 | 1462:aec1 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     | pchtherm   | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:9d31 | 8086:9d31 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:9d60 | 8086:9d60 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:9d61 | 8086:9d61 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:a131 | 17aa:3636 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 8086:a131 | 17aa:36cc | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | pchtherm   | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 8086:a379 | 1028:0934 | Intel            | Cannon Lake PCH Thermal Controller   | 1     | pchtherm   | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:a379 | 1849:a379 | Intel            | Cannon Lake PCH Thermal Controller   | 1     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:a3b1 | 8086:7270 | Intel            | Comet Lake PCH-V Thermal Subsystem   | 1     |            | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 11    |            | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:283e | 106b:00a0 | Intel            | 82801H (ICH8 Family) SMBus Contro... | 4     | ichsmb     | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:9ca2 | 8086:9ca2 | Intel            | Wildcat Point-LP SMBus Controller    | 4     | ichsmb     | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ichsmb     | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:27da | 8086:7270 | Intel            | NM10/ICH7 Family SMBus Controller    | 2     | ichsmb     | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:43a3 | 1028:0a48 | Intel            | Tiger Lake-H SMBus Controller        | 2     | ichsmb     | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | ichsmb     | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:a323 | 1028:084c | Intel            | Cannon Lake PCH SMBus Controller     | 2     |            | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 1022:790b | 103c:8430 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 1022:790b | 1043:876b | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 1022:790b | 1458:5001 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 8086:02a3 | 1028:0953 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 1     | ichsmb     | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:1c22 | 1043:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ichsmb     | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:1c22 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ichsmb     | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 8086:1e22 | 1043:844d | Intel            | 7 Series/C216 Chipset Family SMBu... | 1     | ichsmb     | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 1     |            | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 1     | ichsmb     | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 8086:3b30 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset SMBu... | 1     |            | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 8086:8c22 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ichsmb     | [951EB91342](<All In One/Acidanthera/iMac15/iMac15,1/EC96C3DF5397/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/951EB91342>) |
| 8086:8c22 | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ichsmb     | [DBEE391B8D](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/0790B41B771D/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DBEE391B8D>) |
| 8086:8c22 | 1458:5001 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     |            | [1917CD73E1](<All In One/Acidanthera/iMac15/iMac15,1/CBF8089199B1/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1917CD73E1>) |
| 8086:8c22 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ichsmb     | [07DC4A3178](<All In One/Apple/iMac14/iMac14,2/07EF6154280E/FREEBSD-13.1/13.1-RELEASE/AMD64/07DC4A3178>) |
| 8086:9d23 | 1028:06d0 | Intel            | Sunrise Point-LP SMBus               | 1     |            | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 8086:9d23 | 103c:81ba | Intel            | Sunrise Point-LP SMBus               | 1     |            | [C2204A3DD2](<All In One/Hewlett-Packard/24/24-g038ur/39C749CF5A44/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/C2204A3DD2>) |
| 8086:9d23 | 1462:aec1 | Intel            | Sunrise Point-LP SMBus               | 1     | ichsmb     | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 1     | ichsmb     | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:9d23 | 8086:9d23 | Intel            | Sunrise Point-LP SMBus               | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:a123 | 17aa:3636 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 8086:a123 | 17aa:36cc | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | ichsmb     | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 8086:a2a3 | 1043:8694 | Intel            | 200 Series/Z370 Chipset Family SM... | 1     | ichsmb     | [D1CC7C07E0](<All In One/Philips/AIO/AIO/BEB0605E57DD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D1CC7C07E0>) |
| 8086:a323 | 1028:0934 | Intel            | Cannon Lake PCH SMBus Controller     | 1     | ichsmb     | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:a323 | 1043:8694 | Intel            | Cannon Lake PCH SMBus Controller     | 1     | ichsmb     | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| 8086:a323 | 1849:a323 | Intel            | Cannon Lake PCH SMBus Controller     | 1     | ichsmb     | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:a3a3 | 8086:7270 | Intel            | Comet Lake PCH-V SMBus Host Contr... | 1     |            | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 11    | hdac       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:160c | 111e:10ec | Intel            | Broadwell-U Audio Controller         | 4     | hdac       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:284b | 106b:00a0 | Intel            | 82801H (ICH8 Family) HD Audio Con... | 4     | hdac       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:9ca0 | 8086:9ca0 | Intel            | Wildcat Point-LP High Definition ... | 4     | hdac       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 1002:aaf0 | 1682:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 2     | hdac       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | hdac       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:27d8 | 8384:7680 | Intel            | NM10/ICH7 Family High Definition ... | 2     | hdac       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | hdac       | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:a348 | 1028:084c | Intel            | Cannon Lake PCH cAVS                 | 2     | hdac       | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 8086:f0c8 | 1028:0a48 | Intel            | Smart Sound Technology (SST) Audi... | 2     | hdac       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 1002:15b3 | 103c:8430 | AMD              | High Definition Audio Controller     | 1     | hdac       | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 1002:aa38 | 106b:aa38 | AMD              | RV710/730 HDMI Audio [Radeon HD 4... | 1     | hdac       | [73912D5852](<All In One/Apple/iMac10/iMac10,1/079C33A20928/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/73912D5852>) |
| 1002:aa58 | 106b:aa58 | AMD              | Juniper HDMI Audio [Radeon HD 570... | 1     | hdac       | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 1002:aa88 | 106b:aa88 | AMD              | Barts HDMI Audio [Radeon HD 6790/... | 1     | hdac       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 1002:aa90 | 106b:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 1     | hdac       | [C9A8D5ADE5](<All In One/Apple/iMac12/iMac12,1/E13BF4839DA0/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/C9A8D5ADE5>) |
| 1002:aab0 | 0000:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 1     |            | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 1002:aae0 | 1002:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 1     | hdac       | [7B20265C8E](<All In One/Apple/iMac18/iMac18,2/47800D718E3D/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/7B20265C8E>) |
| 1002:aaf0 | 148c:aaf0 | AMD              | Ellesmere HDMI Audio [Radeon RX 4... | 1     | hdac       | [1917CD73E1](<All In One/Acidanthera/iMac15/iMac15,1/CBF8089199B1/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1917CD73E1>) |
| 1022:1457 | 1458:a182 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 1     | hdac       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:157a | 103c:8430 | AMD              | Family 15h (Models 60h-6fh) Audio... | 1     | hdac       | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 10de:0bea | 17aa:365e | Nvidia           | GF108 High Definition Audio Contr... | 1     | hdac       | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 10de:0e0f | 1462:8c93 | Nvidia           | GK208 HDMI/DP Audio Controller       | 1     | hdac       | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 10de:0e1b |           | Nvidia           | GK107 HDMI Audio Controller          | 1     | hdac       | [07DC4A3178](<All In One/Apple/iMac14/iMac14,2/07EF6154280E/FREEBSD-13.1/13.1-RELEASE/AMD64/07DC4A3178>) |
| 10de:0e1b | 106b:010b | Nvidia           | GK107 HDMI Audio Controller          | 1     | hdac       | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:02c8 | 1028:0953 | Intel            | Comet Lake PCH-LP cAVS               | 1     | hdac       | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:0c0c | 1028:05a4 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | hdac       | [951EB91342](<All In One/Acidanthera/iMac15/iMac15,1/EC96C3DF5397/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/951EB91342>) |
| 8086:0c0c | 103c:18e6 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | hdac       | [DBEE391B8D](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/0790B41B771D/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DBEE391B8D>) |
| 8086:1c20 | 1043:8519 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | hdac       | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:1c20 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | hdac       | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 8086:1e20 | 1043:84f5 | Intel            | 7 Series/C216 Chipset Family High... | 1     | hdac       | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 1     | hdac       | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:3198 | 1c6c:010e | Intel            | Celeron/Pentium Silver Processor ... | 1     | hdac       | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 8086:3b56 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset High... | 1     | hdac       | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 8086:8c20 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset High... | 1     | hdac       | [951EB91342](<All In One/Acidanthera/iMac15/iMac15,1/EC96C3DF5397/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/951EB91342>) |
| 8086:8c20 | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset High... | 1     | hdac       | [DBEE391B8D](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/0790B41B771D/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DBEE391B8D>) |
| 8086:8c20 | 1458:a002 | Intel            | 8 Series/C220 Series Chipset High... | 1     | hdac       | [1917CD73E1](<All In One/Acidanthera/iMac15/iMac15,1/CBF8089199B1/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1917CD73E1>) |
| 8086:8c20 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset High... | 1     | hdac       | [07DC4A3178](<All In One/Apple/iMac14/iMac14,2/07EF6154280E/FREEBSD-13.1/13.1-RELEASE/AMD64/07DC4A3178>) |
| 8086:9d70 | 1028:06d0 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 8086:9d70 | 103c:81ba | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [C2204A3DD2](<All In One/Hewlett-Packard/24/24-g038ur/39C749CF5A44/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/C2204A3DD2>) |
| 8086:9d71 | 1043:30c0 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:9d71 | 1462:aec1 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:a170 | 17aa:3636 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | hdac       | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 8086:a170 | 17aa:36cc | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | hdac       | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 8086:a2f0 | 1043:8701 | Intel            | 200 Series PCH HD Audio              | 1     | hdac       | [D1CC7C07E0](<All In One/Philips/AIO/AIO/BEB0605E57DD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D1CC7C07E0>) |
| 8086:a348 | 1028:0934 | Intel            | Cannon Lake PCH cAVS                 | 1     | hdac       | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:a348 | 1043:8724 | Intel            | Cannon Lake PCH cAVS                 | 1     | hdac       | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| 8086:a348 | 1849:388a | Intel            | Cannon Lake PCH cAVS                 | 1     | hdac       | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:a3f0 | 8086:7270 | Intel            | Comet Lake PCH-V cAVS                | 1     | hdac       | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 10    | ahci       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:2829 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 4     | ahci       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:9c83 | 8086:9c83 | Intel            | Wildcat Point-LP SATA Controller ... | 4     | ahci       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:1c02 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ahci       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:43d2 | 1028:0a48 | Intel            | 500 Series Chipset Family SATA AH... | 2     | ahci       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 2     | ahci       | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 1022:43b8 | 1b21:1062 | AMD              | FCH SATA Controller D                | 1     | ahci       | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 1022:43c8 | 1b21:1062 | AMD              | 400 Series Chipset SATA Controller   | 1     | ahci       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:7901 | 103c:8430 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 1022:7901 | 1043:876b | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 1022:7901 | 1458:b002 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1b4b:9172 | 1458:b000 | Marvell Techn... | 88SE9172 SATA 6Gb/s Controller       | 1     | ahci       | [1917CD73E1](<All In One/Acidanthera/iMac15/iMac15,1/CBF8089199B1/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1917CD73E1>) |
| 8086:02d3 | 1028:0953 | Intel            | Comet Lake SATA AHCI Controller      | 1     | ahci       | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:1c02 | 1043:1c02 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ahci       | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:1c02 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ahci       | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 8086:1e02 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | ahci       | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:1e03 | 1043:844d | Intel            | 7 Series Chipset Family 6-port SA... | 1     | ahci       | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 1     | ahci       | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 8086:3b22 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset 6 po... | 1     | ahci       | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 8086:8c02 | 1028:05a4 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ahci       | [951EB91342](<All In One/Acidanthera/iMac15/iMac15,1/EC96C3DF5397/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/951EB91342>) |
| 8086:8c02 | 103c:18e6 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ahci       | [DBEE391B8D](<All In One/Hewlett-Packard/EliteOne/EliteOne 800 G1 AiO/0790B41B771D/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/DBEE391B8D>) |
| 8086:8c02 | 1458:b005 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ahci       | [1917CD73E1](<All In One/Acidanthera/iMac15/iMac15,1/CBF8089199B1/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1917CD73E1>) |
| 8086:8c02 | 8086:7270 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ahci       | [07DC4A3178](<All In One/Apple/iMac14/iMac14,2/07EF6154280E/FREEBSD-13.1/13.1-RELEASE/AMD64/07DC4A3178>) |
| 8086:9d03 | 1028:06d0 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [D21F14C779](<All In One/Dell/Inspiron/Inspiron 24-3459/D5FAD644929A/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/D21F14C779>) |
| 8086:9d03 | 103c:81ba | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [C2204A3DD2](<All In One/Hewlett-Packard/24/24-g038ur/39C749CF5A44/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/C2204A3DD2>) |
| 8086:9d03 | 1462:aec1 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:9d03 | 8086:9d03 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:a102 | 17aa:3636 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 1     | ahci       | [37E51C01A1](<All In One/Lenovo/IdeaCentre/IdeaCentre AIO 700-22ISH F0BF000WGE/84BEF77142E1/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/37E51C01A1>) |
| 8086:a102 | 17aa:36cc | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 1     | ahci       | [725797B27E](<All In One/Lenovo/SKYBAY/SKYBAY 31900002 WIN 1801931923964/E5BBD8484B41/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/725797B27E>) |
| 8086:a282 | 1043:8694 | Intel            | 200 Series PCH SATA controller [A... | 1     | ahci       | [D1CC7C07E0](<All In One/Philips/AIO/AIO/BEB0605E57DD/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/D1CC7C07E0>) |
| 8086:a352 | 1043:8694 | Intel            | Cannon Lake PCH SATA AHCI Controller | 1     | ahci       | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| 8086:a352 | 1849:a352 | Intel            | Cannon Lake PCH SATA AHCI Controller | 1     | ahci       | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 8086:a382 | 8086:7270 | Intel            | 400 Series Chipset Family SATA AH... | 1     | ahci       | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2850 | 106b:00a0 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 4     | atapci     | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:27c4 | 8086:7270 | Intel            | 82801GBM/GHM (ICH7-M Family) SATA... | 2     | atapci     | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27df | 8086:7270 | Intel            | 82801G (ICH7 Family) IDE Controller  | 2     | atapci     | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 10de:0ab5 | 10de:cb79 | Nvidia           | MCP79 SATA Controller                | 1     | ahci       | [73912D5852](<All In One/Apple/iMac10/iMac10,1/079C33A20928/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/73912D5852>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 2     | nvme       | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| 106b:2001 | 106b:2001 | Apple            | S1X NVMe Controller                  | 1     |            | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 1179:011a | 1179:0001 | Toshiba          | XG6 NVMe SSD Controller              | 1     | nvme       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 1     | nvme       | [7B20265C8E](<All In One/Apple/iMac18/iMac18,2/47800D718E3D/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/7B20265C8E>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 1     | nvme       | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 1     | nvme       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1e95:9100 | 126f:2263 | Solid State S... |                                      | 1     | nvme       | [30432DACCB](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/7C4592247A2D/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/30432DACCB>) |
| 2646:500e | 2646:500e | Kingston Tech... | SNVS2000G [NV1 NVMe PCIe SSD 2TB]    | 1     | nvme       | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 1     | nvme       | [1917CD73E1](<All In One/Acidanthera/iMac15/iMac15,1/CBF8089199B1/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/1917CD73E1>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 1     | nvme       | [3492D9A849](<All In One/Acidanthera/iMac19/iMac19,1/0E3AB23CF5CC/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/3492D9A849>) |
| c0a9:2263 | c0a9:2263 | Micron/Crucia... | P1 NVMe PCIe SSD                     | 1     | nvme       | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2822 | 1028:084c | Intel            | SATA Controller [RAID mode]          | 2     | ahci       | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 8086:2822 | 1028:0934 | Intel            | SATA Controller [RAID mode]          | 1     | ahci       | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:15d2 |           | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 2     |            | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:1911 | 1028:084c | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 1022:1451 | 1022:1451 | AMD              | Family 17h (Models 00h-0fh) I/O M... | 1     |            | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:1577 | 1022:1577 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1     |            | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 1022:15d1 | 1022:15d1 | AMD              | Raven/Raven2 IOMMU                   | 1     |            | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 197b:2392 | 1043:84c1 | JMicron Techn... | SD/MMC Host Controller               | 1     |            | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 1     |            | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:1911 | 1028:0934 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [5F271A82BF](<All In One/Dell/OptiPlex/OptiPlex 7770 AIO/845B0BD08F32/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/5F271A82BF>) |
| 8086:1911 | 1028:0953 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:1911 | 1462:aec1 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [7863616B75](<All In One/MSI/KBL-U/KBL-U Pro PRO24X/2B3FD03F8476/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7863616B75>) |
| 8086:1911 | 8086:1911 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [F21ADEB92C](<All In One/ASUSTek Computer/V241/V241ICR-R/A83E837A2495/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/F21ADEB92C>) |
| 8086:1911 | 8086:7270 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [732A9DF612](<All In One/Others/Others/Others/1576FFBF3562/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/732A9DF612>) |
| 8086:3190 | 8086:3190 | Intel            | Celeron/Pentium Silver Processor ... | 1     |            | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 8086:d150 |           | Intel            | Core Processor QPI Link              | 1     |            | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 8086:d151 |           | Intel            | Core Processor QPI Routing and Pr... | 1     |            | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 11    | ohci       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0aa6 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 11    | ehci       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0aa7 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 11    | ohci       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 10de:0aa9 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 11    | ehci       | [970F35AF17](<All In One/Apple/iMac10/iMac10,1/67709B10CE79/FREEBSD-13.1-P7/13.1-RELEASE-P6/AMD64/970F35AF17>) |
| 8086:2830 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 4     | uhci       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2831 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 4     | uhci       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2832 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 4     | uhci       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2834 |           | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 4     | uhci       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2835 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 4     | uhci       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:2836 | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 4     | ehci       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:283a | 106b:00a0 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 4     | ehci       | [1DD1823662](<All In One/Apple/iMac7/iMac7,1/F31079EF6FED/FREEBSD-13.0-P10/13.0-RELEASE-P8/AMD64/1DD1823662>) |
| 8086:9ca6 | 8086:9ca6 | Intel            | Wildcat Point-LP USB EHCI Controller | 4     | ehci       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:9cb1 | 8086:9cb1 | Intel            | Wildcat Point-LP USB xHCI Controller | 4     | xhci       | [EC5B4884A7](<All In One/BESSTAR Tech/U/U700/EA5F96B729D4/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/EC5B4884A7>) |
| 8086:15d4 |           | Intel            | JHL6540 Thunderbolt 3 USB Control... | 2     | xhci       | [367EDC6620](<All In One/Apple/iMac18/iMac18,1/86461CD48EA7/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/367EDC6620>) |
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ehci       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | uhci       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | uhci       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ehci       | [D26A6C8990](<All In One/Apple/iMac12/iMac12,2/CE2CF674E0E5/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/D26A6C8990>) |
| 8086:27c8 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 2     | uhci       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27c9 | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 2     | uhci       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27ca | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 2     | uhci       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27cb | 8086:7270 | Intel            | NM10/ICH7 Family USB UHCI Control... | 2     | uhci       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:27cc | 8086:7270 | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 2     | ehci       | [35B4547CF0](<All In One/Apple/iMac5/iMac5,1/6DA923511077/FREEBSD-12.2-P9/12.2-RELEASE-P7/I386/35B4547CF0>) |
| 8086:43ed | 1028:0a48 | Intel            | Tiger Lake-H USB 3.2 Gen 2x1 xHCI... | 2     | xhci       | [75132E6886](<All In One/Dell/OptiPlex/OptiPlex 5490 AIO/FD1839F1D47B/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/75132E6886>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | xhci       | [2506316700](<All In One/Apple/iMac17/iMac17,1/465559F6AD83/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/2506316700>) |
| 8086:a36d | 1028:084c | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 2     | xhci       | [9468EEEF92](<All In One/Dell/OptiPlex/OptiPlex 5260 AIO/91EAE2D1FC30/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/9468EEEF92>) |
| 1022:145f | 1458:5007 | AMD              | Zeppelin USB 3.0 xHCI Compliant H... | 1     | xhci       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:15e0 | 1043:876b | AMD              | Raven USB 3.1                        | 1     | xhci       | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 1022:15e1 | 1043:876b | AMD              | Raven USB 3.1                        | 1     | xhci       | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 1022:43bc | 1b21:1142 | AMD              | A320 USB 3.1 XHCI Host Controller    | 1     | xhci       | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 1022:43d5 | 1b21:1142 | AMD              | 400 Series Chipset USB 3.1 xHCI C... | 1     | xhci       | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:7908 | 103c:8430 | AMD              | FCH USB EHCI Controller              | 1     | ehci       | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 1022:7914 | 103c:8430 | AMD              | FCH USB XHCI Controller              | 1     | xhci       | [0D21E083F4](<All In One/Hewlett-Packard/All-in-One/All-in-One 22-c0xx/19C72E266C63/FREEBSD-13.0/13.0-RELEASE/AMD64/0D21E083F4>) |
| 10ec:816d | 10ec:8168 | Realtek Semic... | RTL811x EHCI host controller         | 1     | ehci       | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |
| 1b21:1042 | 1043:102b | ASMedia Techn... | ASM1042 SuperSpeed USB Host Contr... | 1     | xhci       | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:02ed | 1028:0953 | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 1     | xhci       | [589F10057F](<All In One/Dell/Inspiron/Inspiron 5490 AIO/DED288B166FA/GHOSTBSD-22.02.26/13.0-STABLE/AMD64/589F10057F>) |
| 8086:1c26 | 1043:1c26 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci       | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:1c26 | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci       | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 8086:1c2d | 1043:1c2d | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci       | [FB186DA68E](<All In One/ASUSTek Computer/ET2411/ET2411_W8/1B8E9987FB7C/HELLOSYSTEM-0.7.0/13.0-RELEASE-P8/AMD64/FB186DA68E>) |
| 8086:1c2d | 17aa:365e | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci       | [A9189728E3](<All In One/Lenovo/C440/C440 10104/391A896A775D/FREEBSD-13.1/13.1-RELEASE/AMD64/A9189728E3>) |
| 8086:1e26 | 1043:844d | Intel            | 7 Series/C216 Chipset Family USB ... | 1     | ehci       | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 8086:1e26 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 1     | ehci       | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:1e2d | 1043:844d | Intel            | 7 Series/C216 Chipset Family USB ... | 1     | ehci       | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 8086:1e2d | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 1     | ehci       | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:1e31 | 1043:844d | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | xhci       | [7E39E23232](<All In One/ASUSTek Computer/EB/EB1035/9B09D62159BE/OPNSENSE-22.7.11/13.1-RELEASE-P5/AMD64/7E39E23232>) |
| 8086:1e31 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | xhci       | [4E217288FE](<All In One/Apple/iMac13/iMac13,2/9FFA83A419BC/FREEBSD-12.2/12.2-RELEASE/AMD64/4E217288FE>) |
| 8086:31a8 | 8086:31a8 | Intel            | Celeron/Pentium Silver Processor ... | 1     | xhci       | [C44AC785CC](<All In One/Others/TJ41G-A80/TJ41G-A80 v2 Series/743D0EBF8EF3/HELLOSYSTEM-0.8.0/13.1-RELEASE/AMD64/C44AC785CC>) |
| 8086:3b34 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB2... | 1     | ehci       | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 8086:3b36 | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB ... | 1     |            | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |
| 8086:3b3b | 8086:7270 | Intel            | 5 Series/3400 Series Chipset USB ... | 1     |            | [D7CCA96F72](<All In One/Apple/iMac11/iMac11,3/AFD49E659ABF/HELLOSYSTEM-0.3.0/12.1-RELEASE/AMD64/D7CCA96F72>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [B6329AA072](<All In One/Acidanthera/iMacPro1/iMacPro1,1/7BDC1EF97D67/FREEBSD-13.0-P7/13.0-RELEASE-P6/AMD64/B6329AA072>) |
| 1022:145a | 1043:876b | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [4055806819](<All In One/Acidanthera/iMacPro1/iMacPro1,1/D760EDFD13FF/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/4055806819>) |
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 1     |            | [73076DD5DE](<All In One/Acidanthera/iMac19/iMac19,1/25FC2A3A3DAA/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/73076DD5DE>) |

