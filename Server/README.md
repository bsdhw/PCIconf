Most popular PCI devices in Servers
===================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Servers ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Co-processor ](#co-processor-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
   * [ Firewire controller ](#firewire-controller-pci)
   * [ Graphics card ](#graphics-card-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
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
| 1912:0012 | 1912:0012 | Renesas... | SH7757 PCIe-PCI Bridge [PPB] | 23    | pcib       | 7CEC65D8F8 |
| 1912:0013 | 1912:0013 | Renesas... | SH7757 PCIe Switch [PS]      | 23    | pcib       | 7CEC65D8F8 |
| 8086:1c10 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 19    | pcib       | 9301BD0E0F |
| 8086:1c52 | 1028:04dd | Intel      | C202 Chipset LPC Controller  | 19    | isab       | 9301BD0E0F |
| 8086:244e | 1028:04dd | Intel      | 82801 PCI Bridge             | 19    | pcib       | 9301BD0E0F |
| 1a03:1150 | 1a03:1150 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 15    | pcib       | FE8DC15588 |
| 8086:244e | 103c:330d | Intel      | 82801 PCI Bridge             | 14    | pcib       | 82D00F440D |
| 8086:3419 |           | Intel      | 7500/5520/5500 Physical L... | 14    | hostb      | 82D00F440D |
| 8086:341a |           | Intel      | 7500/5520/5500/X58 Unknown   | 14    | hostb      | 82D00F440D |
| 8086:341c |           | Intel      | 7500/5520/5500/X58 Unknown   | 14    | hostb      | 82D00F440D |
| 8086:341e |           | Intel      | 7500/5520/5500/X58 Unknown   | 14    | hostb      | 82D00F440D |
| 8086:3439 |           | Intel      | 7500/5520/5500/X58 Unknown   | 14    | hostb      | 82D00F440D |
| 8086:343d |           | Intel      | 7500/5520/5500/X58 Unknown   | 14    | hostb      | 82D00F440D |
| 111d:8018 |           | Microse... | PES12N3A 12-lane 3-Port P... | 12    | pcib       | 77475B714A |
| 8086:2030 |           | Intel      | Sky Lake-E PCI Express Ro... | 12    | pcib       | 6460F775B0 |
| 8086:2032 |           | Intel      | Sky Lake-E PCI Express Ro... | 12    | pcib       | 6460F775B0 |
| 8086:3406 | 103c:330b | Intel      | 5520 I/O Hub to ESI Port     | 12    | hostb      | 82D00F440D |
| 8086:341f |           | Intel      | 7500/5520/5500/X58 Unknown   | 12    | hostb      | 82D00F440D |
| 8086:343a |           | Intel      | 7500/5520/5500/X58 Unknown   | 12    | hostb      | 82D00F440D |
| 1912:001a | 1912:001a | Renesas... | SH7758 PCIe-PCI Bridge [PPB] | 11    | pcib       | 5ACC629D2E |
| 1912:001d | 1912:001d | Renesas... | SH7758 PCIe Switch [PS]      | 11    | pcib       | 5ACC629D2E |
| 1a03:1150 | 15d9:0921 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 11    | pcib       | F2C6B4AA4D |
| 8086:0108 | 1028:04dd | Intel      | Xeon E3-1200 Processor Fa... | 11    | hostb      | 9301BD0E0F |
| 8086:340a | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 11    | pcib       | 82D00F440D |
| 8086:340e | 103c:330b | Intel      | 5520/5500/X58 I/O Hub PCI... | 11    | pcib       | 82D00F440D |
| 8086:3410 | 103c:330b | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    | pcib       | 82D00F440D |
| 8086:3411 | 103c:330b | Intel      | 7500/5520/5500/X58 I/O Hu... | 11    | pcib       | 82D00F440D |
| 8086:6f00 | 15d9:0921 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | hostb      | F2C6B4AA4D |
| 8086:6f02 | 15d9:0921 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | pcib       | F2C6B4AA4D |
| 8086:6f03 | 15d9:0921 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | pcib       | F2C6B4AA4D |
| 8086:6f04 | 15d9:0921 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | pcib       | F2C6B4AA4D |
| 8086:6f06 | 15d9:0921 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | pcib       | F2C6B4AA4D |
| 8086:6f08 | 15d9:0921 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | pcib       | F2C6B4AA4D |
| 8086:6f0a | 15d9:0921 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 11    | pcib       | F2C6B4AA4D |
| 8086:8c10 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | pcib       | F2C6B4AA4D |
| 8086:8c12 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | pcib       | F2C6B4AA4D |
| 8086:8c16 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | pcib       | F2C6B4AA4D |
| 8086:8c54 | 15d9:0921 | Intel      | C224 Series Chipset Famil... | 11    | isab       | F2C6B4AA4D |
| 1166:0103 |           | Broadcom   | EPB PCI-Express to PCI-X ... | 10    | pcib       | F3854BA6E8 |
| 1556:be00 |           | PLDA       | PCI Express Bridge           | 10    | pcib       | 25E20C3F35 |
| 8086:1d10 | 1028:0528 | Intel      | C600/X79 series chipset P... | 10    | pcib       | 7CEC65D8F8 |
| 8086:1d1e | 1028:0528 | Intel      | C600/X79 series chipset P... | 10    | pcib       | 7CEC65D8F8 |
| 8086:1d3e | 1028:0528 | Intel      | C600/X79 series chipset P... | 10    | pcib       | 7CEC65D8F8 |
| 8086:1d41 | 1028:0528 | Intel      | C600/X79 series chipset L... | 10    | isab       | 7CEC65D8F8 |
| 8086:2020 |           | Intel      | Sky Lake-E DMI3 Registers    | 10    | hostb      | 6460F775B0 |
| 8086:244e | 1028:0528 | Intel      | 82801 PCI Bridge             | 10    | pcib       | 7CEC65D8F8 |
| 8086:340c | 103c:330b | Intel      | 5520/X58 I/O Hub PCI Expr... | 10    | pcib       | 82D00F440D |
| 8086:340d | 103c:330b | Intel      | 5520/X58 I/O Hub PCI Expr... | 10    | pcib       | 82D00F440D |
| 8086:3a18 |           | Intel      | 82801JIB (ICH10) LPC Inte... | 10    | isab       | 82D00F440D |
| 8086:8c18 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 10    | pcib       | F2C6B4AA4D |
| 8086:0101 | 1028:04dd | Intel      | Xeon E3-1200/2nd Generati... | 9     | pcib       | 9301BD0E0F |
| 8086:244e | 1028:0236 | Intel      | 82801 PCI Bridge             | 9     | pcib       | 9EE7FF6592 |
| 8086:25e3 |           | Intel      | 5000 Series Chipset PCI E... | 9     | pcib       | F3854BA6E8 |
| 8086:2918 | 1028:0236 | Intel      | 82801IB (ICH9) LPC Interf... | 9     | isab       | 9EE7FF6592 |
| 8086:2940 | 1028:0236 | Intel      | 82801I (ICH9 Family) PCI ... | 9     | pcib       | 9EE7FF6592 |
| 8086:3403 | 1028:0236 | Intel      | 5500 I/O Hub to ESI Port     | 9     | hostb      | 9EE7FF6592 |
| 8086:3a40 | 103c:330d | Intel      | 82801JI (ICH10 Family) PC... | 9     | pcib       | 82D00F440D |
| 12d8:2608 |           | Pericom... | PI7C9X2G608GP PCIe2 6-Por... | 8     | pcib       | CE87A10F79 |
| 1a03:1150 | 15d9:086d | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 8     | pcib       | 12E3F4C980 |
| 1a03:1150 | 15d9:0969 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 8     | pcib       | E6D9E7AF4E |
| 8086:0e00 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | hostb      | 8F4B51DABD |
| 8086:0e02 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | pcib       | 8F4B51DABD |
| 8086:0e03 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | pcib       | 8F4B51DABD |
| 8086:0e04 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | pcib       | 8F4B51DABD |
| 8086:0e06 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | pcib       | 8F4B51DABD |
| 8086:0e08 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | pcib       | 8F4B51DABD |
| 8086:0e0a | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     | pcib       | 8F4B51DABD |
| 8086:1980 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     | hostb      | E6D9E7AF4E |
| 8086:19a1 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     | hostb      | E6D9E7AF4E |
| 8086:19ab | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     | pcib       | E6D9E7AF4E |
| 8086:19d1 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     | pcib       | E6D9E7AF4E |
| 8086:19d2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     | pcib       | E6D9E7AF4E |
| 8086:19dc | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     | isab       | E6D9E7AF4E |
| 8086:2280 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     | hostb      | CE87A10F79 |
| 8086:229c | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     | isab       | CE87A10F79 |
| 8086:22c8 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     | pcib       | CE87A10F79 |
| 8086:22ca | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     | pcib       | CE87A10F79 |
| 8086:22cc | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     | pcib       | CE87A10F79 |
| 8086:244e |           | Intel      | 82801 PCI Bridge             | 8     | pcib       | F3854BA6E8 |
| 8086:244e | 1028:0235 | Intel      | 82801 PCI Bridge             | 8     | pcib       | A2B6B36770 |
| 8086:25e5 |           | Intel      | 5000 Series Chipset PCI E... | 8     | pcib       | F3854BA6E8 |
| 8086:25e7 |           | Intel      | 5000 Series Chipset PCI E... | 8     | pcib       | F3854BA6E8 |
| 8086:25f8 |           | Intel      | 5000 Series Chipset PCI E... | 8     | pcib       | F3854BA6E8 |
| 8086:2918 | 1028:0235 | Intel      | 82801IB (ICH9) LPC Interf... | 8     | isab       | A2B6B36770 |
| 8086:3406 | 1028:0235 | Intel      | 5520 I/O Hub to ESI Port     | 8     | hostb      | A2B6B36770 |
| 8086:340c | 1028:0235 | Intel      | 5520/X58 I/O Hub PCI Expr... | 8     | pcib       | A2B6B36770 |
| 8086:340d | 1028:0235 | Intel      | 5520/X58 I/O Hub PCI Expr... | 8     | pcib       | A2B6B36770 |
| 8086:340e | 1028:0235 | Intel      | 5520/5500/X58 I/O Hub PCI... | 8     | pcib       | A2B6B36770 |
| 8086:6f00 | 15d9:086d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 8     | hostb      | 12E3F4C980 |
| 8086:6f02 | 15d9:086d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 8     | pcib       | 12E3F4C980 |
| 8086:6f04 | 15d9:086d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 8     | pcib       | 12E3F4C980 |
| 8086:6f06 | 15d9:086d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 8     | pcib       | 12E3F4C980 |
| 8086:6f08 | 15d9:086d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 8     | pcib       | 12E3F4C980 |
| 8086:8c10 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     | pcib       | 12E3F4C980 |
| 8086:8c18 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     | pcib       | 12E3F4C980 |
| 8086:8c54 | 15d9:086d | Intel      | C224 Series Chipset Famil... | 8     | isab       | 12E3F4C980 |
| 1a03:1150 | 15d9:0891 | ASPEED ... | AST1150 PCI-to-PCI Bridge    | 7     | pcib       | CE87A10F79 |
| 8086:0158 | 1028:04dd | Intel      | Xeon E3-1200 v2/Ivy Bridg... | 7     | hostb      | EDE56150A6 |
| 8086:19a3 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 7     | pcib       | E6D9E7AF4E |
| 8086:22ce | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 7     | pcib       | CE87A10F79 |

### Co-processor (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:19e2 |           | Intel      | Atom Processor C3000 Seri... | 8     |            | E6D9E7AF4E |
| 19a2:0800 | 1734:11cc | Emulex     | ServerView iRMC HTI          | 3     |            | A9D034FE42 |
| 1734:1228 | 1734:1256 | Fujitsu... |                              | 2     |            | 6460F775B0 |
| 1734:1228 | 1734:1229 | Fujitsu... |                              | 1     |            | 6E6F1B0F99 |
| 8086:1f18 |           | Intel      | Atom processor C2000 QAT     | 1     |            | 640B454366 |

### Communication controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8c3a | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    |            | F2C6B4AA4D |
| 8086:8c3b | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    |            | F2C6B4AA4D |
| 8086:1d3a | 1028:0528 | Intel      | C600/X79 series chipset M... | 10    |            | 7CEC65D8F8 |
| 8086:1d3b | 1028:0528 | Intel      | C600/X79 series chipset M... | 10    |            | 7CEC65D8F8 |
| 8086:19d3 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     |            | E6D9E7AF4E |
| 8086:8c3a | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     |            | 12E3F4C980 |
| 8086:8c3b | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     |            | 12E3F4C980 |
| 8086:1d3a | 1028:04f7 | Intel      | C600/X79 series chipset M... | 4     |            | 77475B714A |
| 8086:1d3b | 1028:04f7 | Intel      | C600/X79 series chipset M... | 4     |            | 77475B714A |
| 8086:8d3a | 1028:0601 | Intel      | C610/X99 series chipset M... | 4     |            | 5ACC629D2E |
| 8086:8d3b | 1028:0601 | Intel      | C610/X99 series chipset M... | 4     |            | 5ACC629D2E |
| 8086:a13a | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 4     |            | 9D69197550 |
| 8086:a13b | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 4     |            | 9D69197550 |
| 8086:1d3a | 1028:04f8 | Intel      | C600/X79 series chipset M... | 3     |            | 92A93D51C5 |
| 8086:1d3b | 1028:04f8 | Intel      | C600/X79 series chipset M... | 3     |            | 92A93D51C5 |
| 8086:8c3a | 15d9:0842 | Intel      | 8 Series/C220 Series Chip... | 3     |            | 0C0FE552AA |
| 8086:8c3b | 15d9:0842 | Intel      | 8 Series/C220 Series Chip... | 3     |            | 0C0FE552AA |
| 8086:8d3a | 15d9:0832 | Intel      | C610/X99 series chipset M... | 3     |            | F36F748797 |
| 8086:8d3b | 15d9:0832 | Intel      | C610/X99 series chipset M... | 3     |            | F36F748797 |
| 8086:a13a | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 3     |            | EFE3DBF989 |
| 8086:a13b | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 3     |            | EFE3DBF989 |
| 8086:a1ba | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1ba | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a1bb | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1bb | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a1be | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1be | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a328 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 3     |            | 70B8F97D6C |
| 8086:a360 | 15d9:1b0e | Intel      | Cannon Lake PCH HECI Cont... | 3     |            | 70B8F97D6C |
| 8086:a364 | 15d9:1b0e | Intel      | Cannon Lake PCH HECI Cont... | 3     |            | 70B8F97D6C |
| 8086:8c3a | 15d9:0803 | Intel      | 8 Series/C220 Series Chip... | 2     |            | FC4265EB19 |
| 8086:8c3a | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 2     |            | 2758B438C6 |
| 8086:8c3a | 17aa:30b0 | Intel      | 8 Series/C220 Series Chip... | 2     |            | DABCAB55BB |
| 8086:8c3b | 15d9:0803 | Intel      | 8 Series/C220 Series Chip... | 2     |            | FC4265EB19 |
| 8086:8c3d | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 2     | uart       | 2758B438C6 |
| 8086:8c3d | 17aa:30b0 | Intel      | 8 Series/C220 Series Chip... | 2     | uart       | DABCAB55BB |
| 8086:8d3a | 1734:1201 | Intel      | C610/X99 series chipset M... | 2     |            | 7A9D95B303 |
| 8086:8d3b | 1734:1201 | Intel      | C610/X99 series chipset M... | 2     |            | 7A9D95B303 |
| 8086:a13a | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 2     |            | B34EE32475 |
| 8086:a13b | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 2     |            | B34EE32475 |
| 8086:a1ba | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1ba | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1ba | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a1bb | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1bb | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1bb | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a1be | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1be | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1be | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a328 | 1028:088f | Intel      | Cannon Lake PCH Serial IO... | 2     |            | EBC09E92EB |
| 8086:a360 | 1028:088f | Intel      | Cannon Lake PCH HECI Cont... | 2     |            | EBC09E92EB |
| 8086:a364 | 1028:088f | Intel      | Cannon Lake PCH HECI Cont... | 2     |            | EBC09E92EB |
| 8086:19d3 | 15d9:0982 | Intel      | Atom Processor C3000 Seri... | 1     |            | AC3F761F23 |
| 8086:1c3a | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 1     |            | F60388BF6A |
| 8086:1c3a | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     |            | 6CF7F9EA4B |
| 8086:1c3b | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     |            | 6CF7F9EA4B |
| 8086:1d3a | 1028:048c | Intel      | C600/X79 series chipset M... | 1     |            | EDA4A540C7 |
| 8086:1d3a | 1028:0518 | Intel      | C600/X79 series chipset M... | 1     |            | 813CC71069 |
| 8086:1d3a | 1043:84ef | Intel      | C600/X79 series chipset M... | 1     |            | C1D4BBD74E |
| 8086:1d3a | 152d:899b | Intel      | C600/X79 series chipset M... | 1     |            | A4980E3EA4 |
| 8086:1d3a | 15d9:062f | Intel      | C600/X79 series chipset M... | 1     |            | A3BCB2FCF1 |
| 8086:1d3a | 15d9:0703 | Intel      | C600/X79 series chipset M... | 1     |            | 1F4D1E4607 |
| 8086:1d3a | 1734:11c2 | Intel      | C600/X79 series chipset M... | 1     |            | A9D034FE42 |
| 8086:1d3a | 8086:3582 | Intel      | C600/X79 series chipset M... | 1     |            | 474B0E44EA |
| 8086:1d3b | 1028:048c | Intel      | C600/X79 series chipset M... | 1     |            | EDA4A540C7 |
| 8086:1d3b | 1028:0518 | Intel      | C600/X79 series chipset M... | 1     |            | 813CC71069 |
| 8086:1d3b | 1043:84ef | Intel      | C600/X79 series chipset M... | 1     |            | C1D4BBD74E |
| 8086:1d3b | 152d:899b | Intel      | C600/X79 series chipset M... | 1     |            | A4980E3EA4 |
| 8086:1d3b | 15d9:062f | Intel      | C600/X79 series chipset M... | 1     |            | A3BCB2FCF1 |
| 8086:1d3b | 15d9:0703 | Intel      | C600/X79 series chipset M... | 1     |            | 1F4D1E4607 |
| 8086:1d3b | 1734:11c2 | Intel      | C600/X79 series chipset M... | 1     |            | A9D034FE42 |
| 8086:1d3b | 8086:3582 | Intel      | C600/X79 series chipset M... | 1     |            | 474B0E44EA |
| 8086:3435 |           | Intel      |                              | 1     |            | CCAF608BD7 |
| 8086:8d3a | 1028:0600 | Intel      | C610/X99 series chipset M... | 1     |            | 4389B1CE81 |
| 8086:8d3a | 1028:061a | Intel      | C610/X99 series chipset M... | 1     |            | FCD1A34E85 |
| 8086:8d3a | 1028:0627 | Intel      | C610/X99 series chipset M... | 1     |            | 4710D6000D |
| 8086:8d3a | 15d9:0821 | Intel      | C610/X99 series chipset M... | 1     |            | 3C7D64A2CB |
| 8086:8d3a | 15d9:0831 | Intel      | C610/X99 series chipset M... | 1     |            | 223968434F |
| 8086:8d3a | 15d9:0834 | Intel      | C610/X99 series chipset M... | 1     |            | 81DB3F5BE2 |
| 8086:8d3a | 1849:8d3a | Intel      | C610/X99 series chipset M... | 1     |            | 79A07689EC |
| 8086:8d3a | 19e5:2060 | Intel      | C610/X99 series chipset M... | 1     |            | AC2C7107D3 |
| 8086:8d3a | 8086:35c5 | Intel      | C610/X99 series chipset M... | 1     |            | 289D61B1B2 |
| 8086:8d3a | 8086:7270 | Intel      | C610/X99 series chipset M... | 1     |            | 93A8B87E1C |
| 8086:8d3b | 1028:0600 | Intel      | C610/X99 series chipset M... | 1     |            | 4389B1CE81 |
| 8086:8d3b | 1028:061a | Intel      | C610/X99 series chipset M... | 1     |            | FCD1A34E85 |
| 8086:8d3b | 1028:0627 | Intel      | C610/X99 series chipset M... | 1     |            | 4710D6000D |
| 8086:8d3b | 15d9:0821 | Intel      | C610/X99 series chipset M... | 1     |            | 3C7D64A2CB |
| 8086:8d3b | 15d9:0831 | Intel      | C610/X99 series chipset M... | 1     |            | 223968434F |
| 8086:8d3b | 15d9:0834 | Intel      | C610/X99 series chipset M... | 1     |            | 81DB3F5BE2 |
| 8086:8d3b | 1849:8d3b | Intel      | C610/X99 series chipset M... | 1     |            | 79A07689EC |
| 8086:8d3b | 19e5:2060 | Intel      | C610/X99 series chipset M... | 1     |            | AC2C7107D3 |
| 8086:8d3b | 8086:35c5 | Intel      | C610/X99 series chipset M... | 1     |            | 289D61B1B2 |
| 8086:8d3b | 8086:7270 | Intel      | C610/X99 series chipset M... | 1     |            | 93A8B87E1C |
| 8086:a13a | 1028:06a6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 997DA6A5C6 |
| 8086:a13a | 103c:8165 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 0D13EC7AC2 |
| 8086:a13a | 15d9:0896 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5044047B6E |
| 8086:a13a | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a13a | 15d9:0902 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 9F6632DE8B |
| 8086:a13b | 1028:06a6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 997DA6A5C6 |
| 8086:a13b | 15d9:0896 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5044047B6E |

### Encryption controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2298 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     |            | CE87A10F79 |
| 1022:1578 | 1022:1578 | AMD        | Carrizo Platform Security... | 2     |            | C42933F9FD |
| 1022:1456 | 1022:1456 | AMD        | Family 17h (Models 00h-0f... | 1     |            | 4228478ECF |
| 1022:1468 | 1022:1468 | AMD        | Zeppelin Cryptographic Co... | 1     |            | 4228478ECF |
| 1022:1486 | 1022:1486 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 6C4D7ACEEC |
| 1022:1486 | 1458:1000 | AMD        | Starship/Matisse Cryptogr... | 1     |            | 93E2466FC6 |
| 1022:1498 | 1022:1498 | AMD        | Starship/Matisse PTDMA       | 1     |            | 6C4D7ACEEC |
| 1022:1498 | 1458:1000 | AMD        | Starship/Matisse PTDMA       | 1     |            | 93E2466FC6 |

### Firewire controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 104c:8023 | 15d9:0805 | Texas I... | TSB43AB22A IEEE-1394a-200... | 2     |            | 2758B438C6 |
| 104c:8023 | 108e:6676 | Texas I... | TSB43AB22A IEEE-1394a-200... | 1     |            | 970467EFEF |

### Graphics card (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 102b:0532 | 1028:04dd | Matrox ... | MGA G200eW WPCM450           | 19    | vgapci     | 9301BD0E0F |
| 1002:515e | 103c:31fb | AMD        | ES1000                       | 17    | vgapci     | 82D00F440D |
| 102b:0533 | 103c:3381 | Matrox ... | MGA G200EH                   | 11    | vgapci     | 39B99E57AF |
| 1a03:2000 | 15d9:0921 | ASPEED ... | ASPEED Graphics Family       | 11    | vgapci     | F2C6B4AA4D |
| 102b:0534 | 1028:0528 | Matrox ... | G200eR2                      | 10    | vgapci     | 7CEC65D8F8 |
| 102b:0532 | 1028:0236 | Matrox ... | MGA G200eW WPCM450           | 9     | vgapci     | 9EE7FF6592 |
| 102b:0532 | 1028:0235 | Matrox ... | MGA G200eW WPCM450           | 8     | vgapci     | A2B6B36770 |
| 1a03:2000 | 15d9:086d | ASPEED ... | ASPEED Graphics Family       | 8     | vgapci     | 12E3F4C980 |
| 1a03:2000 | 15d9:0969 | ASPEED ... | ASPEED Graphics Family       | 8     | vgapci     | E6D9E7AF4E |
| 8086:22b1 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     | vgapci     | CE87A10F79 |
| 1a03:2000 | 15d9:0891 | ASPEED ... | ASPEED Graphics Family       | 7     | vgapci     | CE87A10F79 |
| 102b:0522 | 1734:11cc | Matrox ... | MGA G200e [Pilot] ServerE... | 6     | vgapci     | A9D034FE42 |
| 102b:0530 | 1014:0369 | Matrox ... | MGA G200EV                   | 6     | vgapci     | 5F9F2C2232 |
| 102b:0522 | 8086:0103 | Matrox ... | MGA G200e [Pilot] ServerE... | 4     | vgapci     | 289D61B1B2 |
| 102b:0534 | 1028:04f7 | Matrox ... | G200eR2                      | 4     | vgapci     | 77475B714A |
| 102b:0534 | 1028:05e5 | Matrox ... | G200eR2                      | 4     | vgapci     | 6CBE8CABB7 |
| 102b:0534 | 1028:0601 | Matrox ... | G200eR2                      | 4     | vgapci     | 5ACC629D2E |
| 1a03:2000 | 15d9:0884 | ASPEED ... | ASPEED Graphics Family       | 4     | vgapci     | 9D69197550 |
| 102b:0522 | 1734:1229 | Matrox ... | MGA G200e [Pilot] ServerE... | 3     | vgapci     | 6460F775B0 |
| 102b:0522 | 8086:0101 | Matrox ... | MGA G200e [Pilot] ServerE... | 3     | vgapci     | 044617A994 |
| 102b:0532 | 1028:02f1 | Matrox ... | MGA G200eW WPCM450           | 3     | vgapci     | F23BF8E1A7 |
| 102b:0534 | 1028:04f8 | Matrox ... | G200eR2                      | 3     | vgapci     | 92A93D51C5 |
| 102b:0534 | 1028:06aa | Matrox ... | G200eR2                      | 3     | vgapci     | EFE3DBF989 |
| 102b:0536 |           | Matrox ... | Integrated Matrox G200eW3... | 3     | vgapci     | 25E20C3F35 |
| 102b:0536 | 1028:0716 | Matrox ... | Integrated Matrox G200eW3... | 3     | vgapci     | 55C1BD261F |
| 1a03:2000 | 15d9:0801 | ASPEED ... | ASPEED Graphics Family       | 3     | vgapci     | CF2E66B6AA |
| 1a03:2000 | 15d9:0842 | ASPEED ... | ASPEED Graphics Family       | 3     | vgapci     | 0C0FE552AA |
| 1a03:2000 | 15d9:1b0e | ASPEED ... | ASPEED Graphics Family       | 3     | vgapci     | 70B8F97D6C |
| 1a03:2000 | 1a03:2000 | ASPEED ... | ASPEED Graphics Family       | 3     | vgapci     | F60388BF6A |
| 1002:515e | 1028:01b2 | AMD        | ES1000                       | 2     | vgapci     | F3854BA6E8 |
| 1002:515e | 1028:023c | AMD        | ES1000                       | 2     | vgapci     | 411477E260 |
| 1002:515e | 8086:3476 | AMD        | ES1000                       | 2     | vgapci     | 411F470773 |
| 1002:9874 | 1002:1871 | AMD        | Wani [Radeon R5/R6/R7 Gra... | 2     | vgapci     | C42933F9FD |
| 102b:0522 | 103c:0100 | Matrox ... | MGA G200e [Pilot] ServerE... | 2     | vgapci     | B1F7A57B01 |
| 102b:0532 | 1028:02a5 | Matrox ... | MGA G200eW WPCM450           | 2     | vgapci     | 56A394AC67 |
| 102b:0532 | 1028:02a6 | Matrox ... | MGA G200eW WPCM450           | 2     | vgapci     | A2EE02F234 |
| 102b:0532 | 1028:04de | Matrox ... | MGA G200eW WPCM450           | 2     | vgapci     | 3881A96CEE |
| 102b:0533 | 103c:330e | Matrox ... | MGA G200EH                   | 2     | vgapci     | 1EBF1B71BD |
| 102b:0536 | 1028:0737 | Matrox ... | Integrated Matrox G200eW3... | 2     | vgapci     | B062E0F4E4 |
| 102b:0536 | 1028:07ca | Matrox ... | Integrated Matrox G200eW3... | 2     | vgapci     | 32F145EA04 |
| 1a03:2000 | 1043:8373 | ASPEED ... | ASPEED Graphics Family       | 2     | vgapci     | 04C5C07D61 |
| 1a03:2000 | 15d9:0803 | ASPEED ... | ASPEED Graphics Family       | 2     | vgapci     | FC4265EB19 |
| 1a03:2000 | 15d9:0832 | ASPEED ... | ASPEED Graphics Family       | 2     | vgapci     | F36F748797 |
| 1a03:2000 | 15d9:0886 | ASPEED ... | ASPEED Graphics Family       | 2     | vgapci     | B34EE32475 |
| 8086:041a | 17aa:30b0 | Intel      | Xeon E3-1200 v3 Processor... | 2     | vgapci     | DABCAB55BB |
| 1002:4752 | 1734:1041 | AMD        | Rage 3 [Rage XL PCI]         | 1     | vgapci     | ADB972BF8E |
| 1002:5159 | 1028:016c | AMD        | RV100 [Radeon 7000 / Rade... | 1     | vgapci     | BB83934454 |
| 1002:515e | 1028:01b9 | AMD        | ES1000                       | 1     | vgapci     | F181777604 |
| 1002:515e | 1028:01eb | AMD        | ES1000                       | 1     | vgapci     | E98F23CD45 |
| 1002:515e | 8086:3478 | AMD        | ES1000                       | 1     | vgapci     | 0546131058 |
| 1002:6611 | 1642:1871 | AMD        | Oland [Radeon HD 8570 / R... | 1     | vgapci     | FFAA30BC08 |
| 102b:0522 | 8086:0102 | Matrox ... | MGA G200e [Pilot] ServerE... | 1     | vgapci     | F88EAF06AC |
| 102b:0532 | 1028:028c | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | A9CF80B10F |
| 102b:0532 | 1028:02a3 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | D3FE07511A |
| 102b:0532 | 1028:02a4 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 245D470945 |
| 102b:0532 | 1028:0488 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | FD37374E7B |
| 102b:0532 | 15d9:0001 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 0A771C7B0E |
| 102b:0532 | 15d9:0400 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 9EA2AEEB86 |
| 102b:0532 | 15d9:0404 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 6ACB4D8445 |
| 102b:0532 | 15d9:0600 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 6DD2D44AA1 |
| 102b:0532 | 15d9:060c | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | CCAF608BD7 |
| 102b:0532 | 15d9:062f | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | A3BCB2FCF1 |
| 102b:0532 | 15d9:0703 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 1F4D1E4607 |
| 102b:0532 | 15d9:a811 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 58A580DD6B |
| 102b:0532 | 15d9:ba11 | Matrox ... | MGA G200eW WPCM450           | 1     | vgapci     | 98F39AFF26 |
| 102b:0534 | 1014:0405 | Matrox ... | G200eR2                      | 1     | vgapci     | 350DBDBDC6 |
| 102b:0534 | 1028:048c | Matrox ... | G200eR2                      | 1     | vgapci     | EDA4A540C7 |
| 102b:0534 | 1028:0600 | Matrox ... | G200eR2                      | 1     | vgapci     | 4389B1CE81 |
| 102b:0534 | 1028:061a | Matrox ... | G200eR2                      | 1     | vgapci     | FCD1A34E85 |
| 102b:0534 | 1028:0627 | Matrox ... | G200eR2                      | 1     | vgapci     | 4710D6000D |
| 102b:0534 | 1028:06a6 | Matrox ... | G200eR2                      | 1     | vgapci     | 997DA6A5C6 |
| 10de:0165 | 10de:0334 | Nvidia     | NV44 [Quadro NVS 285]        | 1     | vgapci     | 970467EFEF |
| 10de:0a65 | 10de:0847 | Nvidia     | GT218 [GeForce 210]          | 1     | vgapci     | F60388BF6A |
| 10de:0a65 | 3842:1311 | Nvidia     | GT218 [GeForce 210]          | 1     | vgapci     | C1638ADFA6 |
| 10de:128b | 1043:8572 | Nvidia     | GK208B [GeForce GT 710]      | 1     | vgapci     | C1D4BBD74E |
| 10de:128b | 3842:2717 | Nvidia     | GK208B [GeForce GT 710]      | 1     | vgapci     | 1EB3ED1B04 |
| 10de:13f1 | 103c:1153 | Nvidia     | GM204GL [Quadro M4000]       | 1     | nvidia     | 93A8B87E1C |
| 10de:1402 | 3842:2951 | Nvidia     | GM206 [GeForce GTX 950]      | 1     | nvidia     | 9F6632DE8B |
| 10de:1bb3 | 10de:11d8 | Nvidia     | GP104GL [Tesla P4]           | 1     | ppt        | AC2C7107D3 |
| 10de:1c82 | 10de:1c82 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 1     | nvidia     | 14A919AB3F |
| 10de:1c82 | 1462:8c96 | Nvidia     | GP107 [GeForce GTX 1050 Ti]  | 1     | nvidia     | 360E63CC66 |
| 10de:1cb3 | 10de:11be | Nvidia     | GP107GL [Quadro P400]        | 1     | nvidia     | 4DA7433E8B |
| 19e5:1711 |           | Huawei ... | Hi171x Series [iBMC Intel... | 1     | vgapci     | AC2C7107D3 |
| 1a03:2000 | 1028:0518 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 813CC71069 |
| 1a03:2000 | 1043:84eb | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | FE8DC15588 |
| 1a03:2000 | 108e:4843 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 806421299D |
| 1a03:2000 | 108e:534b | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 1D2D5F5A1F |
| 1a03:2000 | 1458:1000 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 93E2466FC6 |
| 1a03:2000 | 152d:899b | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | A4980E3EA4 |
| 1a03:2000 | 15d9:0728 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 93A8B87E1C |
| 1a03:2000 | 15d9:0804 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | B6DF404FEA |
| 1a03:2000 | 15d9:0821 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 3C7D64A2CB |
| 1a03:2000 | 15d9:0831 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 223968434F |
| 1a03:2000 | 15d9:0834 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 81DB3F5BE2 |
| 1a03:2000 | 15d9:0857 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 14A919AB3F |
| 1a03:2000 | 15d9:0896 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 5044047B6E |
| 1a03:2000 | 15d9:096e | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | CA41B3F700 |
| 1a03:2000 | 15d9:0982 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | AC3F761F23 |
| 1a03:2000 | 15d9:0986 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | 91B07FA8B9 |
| 1a03:2000 | 15d9:1b09 | ASPEED ... | ASPEED Graphics Family       | 1     | vgapci     | C9ABEB0DFE |

### Memory controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:19de | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     |            | E6D9E7AF4E |
| 1912:0011 |           | Renesas... | SH7757 PCIe End-Point [PBI]  | 4     |            | 6CBE8CABB7 |
| 8086:a121 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 4     |            | 9D69197550 |
| 8086:a36f | 8086:7270 | Intel      | Cannon Lake PCH Shared SRAM  | 4     |            | C9ABEB0DFE |
| 8086:a121 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 3     |            | EFE3DBF989 |
| 8086:a1a1 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1a1 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a36f |           | Intel      | Cannon Lake PCH Shared SRAM  | 3     |            | 25E20C3F35 |
| 8086:a121 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 2     |            | B34EE32475 |
| 8086:a1a1 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1a1 | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1a1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 10de:0361 | 108e:6676 | Nvidia     | MCP55 LPC Bridge             | 1     |            | 970467EFEF |
| 10de:0369 | 108e:534b | Nvidia     | MCP55 Memory Controller      | 1     |            | 1D2D5F5A1F |
| 10de:0369 | 108e:6676 | Nvidia     | MCP55 Memory Controller      | 1     |            | 970467EFEF |
| 10de:036a | 108e:6676 | Nvidia     | MCP55 Memory Controller      | 1     |            | 970467EFEF |
| 8086:19de | 15d9:0982 | Intel      | Atom Processor C3000 Seri... | 1     |            | AC3F761F23 |
| 8086:a121 | 1028:06a6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 997DA6A5C6 |
| 8086:a121 | 103c:8165 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 0D13EC7AC2 |
| 8086:a121 | 15d9:0896 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5044047B6E |
| 8086:a121 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a121 | 15d9:0902 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 9F6632DE8B |
| 8086:a1a1 | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | CA41B3F700 |
| 8086:a1a1 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 91B07FA8B9 |
| 8086:a1a1 | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | FFAA30BC08 |
| 8086:a2a1 | 15d9:093f | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 825EC10782 |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1521 | 15d9:1521 | Intel      | I350 Gigabit Network Conn... | 21    | igb        | F2C6B4AA4D |
| 14e4:163b | 1028:04dd | Broadcom   | NetXtreme II BCM5716 Giga... | 19    | bce        | 9301BD0E0F |
| 14e4:165f | 1028:1f5b | Broadcom   | NetXtreme BCM5720 Gigabit... | 15    | bge        | 7CEC65D8F8 |
| 8086:15ac | 15d9:15ac | Intel      | Ethernet Connection X552 ... | 12    | ix         | F2C6B4AA4D |
| 8086:1572 |           | Intel      | Ethernet Controller X710 ... | 10    | ixl        | 94F3A7B95A |
| 14e4:1639 | 103c:7055 | Broadcom   | NetXtreme II BCM5709 Giga... | 9     | bce        | 82D00F440D |
| 14e4:1639 | 1028:0236 | Broadcom   | NetXtreme II BCM5709 Giga... | 8     | bce        | 9EE7FF6592 |
| 8086:10e8 | 8086:a02c | Intel      | 82576 Gigabit Network Con... | 8     | igb        | 77475B714A |
| 8086:15ad | 15d9:15ad | Intel      | Ethernet Connection X552/... | 7     | ix         | 12E3F4C980 |
| 8086:15e5 |           | Intel      | Ethernet Connection X553 ... | 7     | ix         | 6BD9AC14E6 |
| 8086:15e4 |           | Intel      | Ethernet Connection X553 ... | 6     | ix         | 6BD9AC14E6 |
| 14e4:1639 | 1014:03a9 | Broadcom   | NetXtreme II BCM5709 Giga... | 5     | bce        | 5F9F2C2232 |
| 8086:1521 | 8086:5001 | Intel      | I350 Gigabit Network Conn... | 5     | igb        | 6CBE8CABB7 |
| 8086:153a | 15d9:153a | Intel      | Ethernet Connection I217-LM  | 5     | em         | CF2E66B6AA |
| 14e4:165f | 1028:04f7 | Broadcom   | NetXtreme BCM5720 Gigabit... | 4     | bge        | 77475B714A |
| 14e4:165f | 1028:05e5 | Broadcom   | NetXtreme BCM5720 Gigabit... | 4     | bge        | 6CBE8CABB7 |
| 8086:1521 | 1734:11ce | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 6460F775B0 |
| 14e4:1639 | 14e4:0907 | Broadcom   | NetXtreme II BCM5709 Giga... | 3     | bce        | 411477E260 |
| 14e4:1657 | 103c:169d | Broadcom   | NetXtreme BCM5719 Gigabit... | 3     | bge        | 39B99E57AF |
| 14e4:1657 | 103c:22be | Broadcom   | NetXtreme BCM5719 Gigabit... | 3     | bge        | C2BB148E8A |
| 14e4:165f | 1028:04f8 | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | bge        | 92A93D51C5 |
| 8086:10c9 | 103c:323f | Intel      | 82576 Gigabit Network Con... | 3     | igb        | B1F7A57B01 |
| 8086:10fb | 8086:7a11 | Intel      | 82599ES 10-Gigabit SFI/SF... | 3     | ix         | EDE56150A6 |
| 8086:1521 | 8086:0001 | Intel      | I350 Gigabit Network Conn... | 3     | igb        | 6BD9AC14E6 |
| 8086:37d1 | 1734:1230 | Intel      | Ethernet Connection X722 ... | 3     | ixl        | 6460F775B0 |
| 1077:8020 | 103c:3733 | QLogic     | cLOM8214 1/10GbE Controller  | 2     | ql         | A2B6B36770 |
| 14e4:163b | 1028:02a5 | Broadcom   | NetXtreme II BCM5716 Giga... | 2     | bce        | 56A394AC67 |
| 14e4:164c | 1028:01b2 | Broadcom   | NetXtreme II BCM5708 Giga... | 2     | bce        | F3854BA6E8 |
| 14e4:1659 | 1028:023c | Broadcom   | NetXtreme BCM5721 Gigabit... | 2     | bge        | 411477E260 |
| 14e4:165a | 1028:02a6 | Broadcom   | NetXtreme BCM5722 Gigabit... | 2     | bge        | A2EE02F234 |
| 14e4:165a | 1028:04de | Broadcom   | NetXtreme BCM5722 Gigabit... | 2     | bge        | 3881A96CEE |
| 14e4:165f | 1028:088f | Broadcom   | NetXtreme BCM5720 Gigabit... | 2     | bge        | EBC09E92EB |
| 14e4:168e | 103c:339d | Broadcom   | NetXtreme II BCM57810 10 ... | 2     | bxe        | F587BDDFBD |
| 8086:10bc | 103c:704b | Intel      | 82571EB/82571GB Gigabit E... | 2     | em         | 928F9FA905 |
| 8086:10c9 | 8086:a04c | Intel      | 82576 Gigabit Network Con... | 2     | igb        | A1C753E9D7 |
| 8086:10d3 | 1014:03bd | Intel      | 82574L Gigabit Network Co... | 2     | em         | 14DABA3BDE |
| 8086:150e | 8086:12a1 | Intel      | 82580 Gigabit Network Con... | 2     | igb        | 9F13074B78 |
| 8086:1516 | 8086:12b2 | Intel      | 82580 Gigabit Network Con... | 2     | igb        | DB450EAFB5 |
| 8086:1521 |           | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 813CC71069 |
| 8086:1521 | 1028:1f60 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 4710D6000D |
| 8086:1521 | 1028:1faa | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 55C1BD261F |
| 8086:1521 | 103c:3380 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 54FD4A89D8 |
| 8086:1533 | 17aa:30b0 | Intel      | I210 Gigabit Network Conn... | 2     | igb        | DABCAB55BB |
| 8086:154d | 8086:7b11 | Intel      | Ethernet 10G 2P X520 Adapter | 2     | ix         | EDA4A540C7 |
| 8086:1563 | 1028:1fa8 | Intel      | Ethernet Controller 10G X... | 2     | ix         | 55C1BD261F |
| 8086:1563 | 8086:0001 | Intel      | Ethernet Controller 10G X... | 2     | ix         | EBC09E92EB |
| 8086:1563 | 8086:001d | Intel      | Ethernet Controller 10G X... | 2     | ix         | 32F145EA04 |
| 8086:1572 | 8086:0006 | Intel      | Ethernet Controller X710 ... | 2     | ixl        | 0BBF4A51BB |
| 8086:1572 | 8086:0007 | Intel      | Ethernet Controller X710 ... | 2     | ixl        | 9D69197550 |
| 8086:15b8 | 15d9:15b8 | Intel      | Ethernet Connection (2) I... | 2     | em         | 9F6632DE8B |
| 1077:8020 | 1077:0228 | QLogic     | cLOM8214 1/10GbE Controller  | 1     | ql         | A9CF80B10F |
| 10df:0720 | 1734:120d | Emulex     | OneConnect NIC (Skyhawk)     | 1     | oce        | 0F4461E95F |
| 10ec:8125 | 10ec:0123 | Realtek... | RTL8125 2.5GbE Controller    | 1     | re         | E7A9A290CB |
| 1106:3106 | 1186:1403 | VIA Tec... | VT6105/VT6106S [Rhine-III]   | 1     | vr         | F60388BF6A |
| 1425:4001 |           | Chelsio... | T420-CR Unified Wire Ethe... | 1     | t4iov      | 9EA2AEEB86 |
| 1425:4401 |           | Chelsio... | T420-CR Unified Wire Ethe... | 1     | t4nex      | 9EA2AEEB86 |
| 14e4:1639 | 103c:7059 | Broadcom   | NetXtreme II BCM5709 Giga... | 1     | bce        | 3C7D64A2CB |
| 14e4:163b | 1028:028c | Broadcom   | NetXtreme II BCM5716 Giga... | 1     | bce        | A9CF80B10F |
| 14e4:163b | 1028:02a3 | Broadcom   | NetXtreme II BCM5716 Giga... | 1     | bce        | D3FE07511A |
| 14e4:163b | 1028:0488 | Broadcom   | NetXtreme II BCM5716 Giga... | 1     | bce        | FD37374E7B |
| 14e4:164c | 14e4:164c | Broadcom   | NetXtreme II BCM5708 Giga... | 1     | bce        | 14DABA3BDE |
| 14e4:1650 | 103c:7058 | Broadcom   | NetXtreme II BCM57711E 10... | 1     | bxe        | 2B539FCF18 |
| 14e4:1657 | 1014:0420 | Broadcom   | NetXtreme BCM5719 Gigabit... | 1     | bge        | BE9AFF90C7 |
| 14e4:1657 | 103c:3383 | Broadcom   | NetXtreme BCM5719 Gigabit... | 1     | bge        | 0D13EC7AC2 |
| 14e4:1659 | 1028:01eb | Broadcom   | NetXtreme BCM5721 Gigabit... | 1     | bge        | E98F23CD45 |
| 14e4:165f | 1028:000a | Broadcom   | NetXtreme BCM5720 Gigabit... | 1     | bge        | 32F145EA04 |
| 14e4:165f | 1028:001f | Broadcom   | NetXtreme BCM5720 Gigabit... | 1     | bge        | E37DE1CD8C |
| 14e4:165f | 1028:06a6 | Broadcom   | NetXtreme BCM5720 Gigabit... | 1     | bge        | 997DA6A5C6 |
| 14e4:165f | 1028:0891 | Broadcom   | NetXtreme BCM5720 Gigabit... | 1     | bge        | 25E20C3F35 |
| 14e4:165f | 15d9:165f | Broadcom   | NetXtreme BCM5720 Gigabit... | 1     | bge        | 6C4D7ACEEC |
| 14e4:1668 | 103c:7039 | Broadcom   | NetXtreme BCM5714 Gigabit... | 1     | bge        | D6114DE1CC |
| 14e4:1677 | 1028:01b9 | Broadcom   | NetXtreme BCM5751 Gigabit... | 1     | bge        | F181777604 |
| 14e4:1678 | 103c:703e | Broadcom   | NetXtreme BCM5715 Gigabit... | 1     | bge        | CD1101B9A1 |
| 14e4:1678 | 108e:534b | Broadcom   | NetXtreme BCM5715 Gigabit... | 1     | bge        | 1D2D5F5A1F |
| 14e4:168e | 14e4:1000 | Broadcom   | NetXtreme II BCM57810 10 ... | 1     | bxe        | FC4265EB19 |
| 14e4:168e | 14e4:1006 | Broadcom   | NetXtreme II BCM57810 10 ... | 1     | bxe        | 77F48D8337 |
| 14e4:168e | 14e4:1008 | Broadcom   | NetXtreme II BCM57810 10 ... | 1     | bxe        | AC57AB9EF6 |
| 14e4:168e | 14e4:e31f | Broadcom   | NetXtreme II BCM57810 10 ... | 1     | bxe        | 7CEC65D8F8 |
| 1924:0803 | 1924:6206 | Solarfl... | SFC9020 10G Ethernet Cont... | 1     |            | 1EB3ED1B04 |
| 1924:0903 | 1924:8002 | Solarfl... | SFC9120 10G Ethernet Cont... | 1     |            | 1EB3ED1B04 |
| 19a2:0700 | 103c:1747 | Emulex     | OneConnect OCe10100/OCe10... | 1     | oce        | 149B6DB16F |
| 19a2:0710 | 103c:3340 | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | oce        | 7553078A58 |
| 19a2:0710 | 10df:e729 | Emulex     | OneConnect 10Gb NIC (be3)    | 1     | oce        | 31B6E52CF4 |
| 8086:101d | 8086:1000 | Intel      | 82546EB Gigabit Ethernet ... | 1     | em         | BB83934454 |
| 8086:105e | 108e:125e | Intel      | 82571EB/82571GB Gigabit E... | 1     | em         | 806421299D |
| 8086:105e | 8086:125e | Intel      | 82571EB/82571GB Gigabit E... | 1     | em         | A3BCB2FCF1 |
| 8086:1076 | 1028:016d | Intel      | 82541GI Gigabit Ethernet ... | 1     | em         | BB83934454 |
| 8086:1079 | 1734:1041 | Intel      | 82546GB Gigabit Ethernet ... | 1     | em         | ADB972BF8E |
| 8086:107d | 8086:1082 | Intel      | 82572EI Gigabit Ethernet ... | 1     | em         | 4907DD5D8F |
| 8086:107d | 8086:1084 | Intel      | 82572EI Gigabit Ethernet ... | 1     | em         | A4980E3EA4 |
| 8086:1096 | 108e:4843 | Intel      | 80003ES2LAN Gigabit Ether... | 1     | em         | 806421299D |
| 8086:10a7 | 8086:34dc | Intel      | 82575EB Gigabit Network C... | 1     | igb        | F54B954AC8 |
| 8086:10bc | 8086:11bc | Intel      | 82571EB/82571GB Gigabit E... | 1     | em         | F587BDDFBD |
| 8086:10c9 | 15d9:0100 | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 6DD2D44AA1 |
| 8086:10c9 | 15d9:0400 | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 9EA2AEEB86 |
| 8086:10c9 | 15d9:060c | Intel      | 82576 Gigabit Network Con... | 1     | igb        | CCAF608BD7 |
| 8086:10c9 | 15d9:10c9 | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 0A771C7B0E |
| 8086:10c9 | 15d9:ab11 | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 58A580DD6B |
| 8086:10c9 | 1fc1:008e | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 98F39AFF26 |
| 8086:10c9 | 8086:34f2 | Intel      | 82576 Gigabit Network Con... | 1     | igb        | 044617A994 |

### Net/wireless (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 168c:002b | 1a3b:1089 | Qualcom... | AR9285 Wireless Network A... | 1     | ath        | F60388BF6A |
| 168c:0030 | 168c:3112 | Qualcom... | AR93xx Wireless Network A... | 1     | ath        | F6CF8F7870 |

### Network (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1533 | 15d9:1533 | Intel      | I210 Gigabit Network Conn... | 48    | igb        | F2C6B4AA4D |
| 14e4:1639 | 1028:0235 | Broadcom   | NetXtreme II BCM5709 Giga... | 8     | bce        | A2B6B36770 |
| 8086:105e | 8086:135e | Intel      | 82571EB/82571GB Gigabit E... | 6     | em         | 25E20C3F35 |
| 14e4:164c | 103c:7038 | Broadcom   | NetXtreme II BCM5708 Giga... | 4     | bce        | 658BE87971 |
| 8086:10d3 | 1043:8369 | Intel      | 82574L Gigabit Network Co... | 4     | em         | F60388BF6A |
| 8086:1521 | 8086:0002 | Intel      | I350 Gigabit Network Conn... | 4     | igb        | 1EBF1B71BD |
| 14e4:163b | 1028:02f1 | Broadcom   | NetXtreme II BCM5716 Giga... | 3     | bce        | F23BF8E1A7 |
| 14e4:165f | 1028:06a7 | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | bge        | EFE3DBF989 |
| 14e4:165f | 103c:22e8 | Broadcom   | NetXtreme BCM5720 Gigabit... | 3     | bge        | C42933F9FD |
| 8086:1096 | 8086:3476 | Intel      | 80003ES2LAN Gigabit Ether... | 3     | em         | 411F470773 |
| 8086:1528 | 15d9:1528 | Intel      | Ethernet Controller 10-Gi... | 3     | ix         | 0C0FE552AA |
| 8086:37d2 | 15d9:37d2 | Intel      | Ethernet Connection X722 ... | 3     | ixl        | 91B07FA8B9 |
| 1425:0031 | 1425:0001 | Chelsio... | T320 10GbE Dual Port Adapter | 2     | cxgbc      | 350AB9E6FD |
| 14e4:1639 | 14e4:1917 | Broadcom   | NetXtreme II BCM5709 Giga... | 2     | bce        | CF40865774 |
| 14e4:165f | 103c:2133 | Broadcom   | NetXtreme BCM5720 Gigabit... | 2     | bge        | 39B99E57AF |
| 15b3:1003 | 15b3:0055 | Mellano... | MT27500 Family [ConnectX-3]  | 2     | mlx4_core  | 5044047B6E |
| 8086:105e | 103c:7044 | Intel      | 82571EB/82571GB Gigabit E... | 2     | em         | 4EBCBDC297 |
| 8086:10d3 | 103c:1785 | Intel      | 82574L Gigabit Network Co... | 2     | em         | 1EBF1B71BD |
| 8086:10d3 | 15d9:10d3 | Intel      | 82574L Gigabit Network Co... | 2     | em         | 98F39AFF26 |
| 8086:10d3 | 1734:1192 | Intel      | 82574L Gigabit Network Co... | 2     | em         | EBCDA9A77F |
| 8086:10d3 | 8086:a01f | Intel      | 82574L Gigabit Network Co... | 2     | em         | EBCDA9A77F |
| 8086:10fb | 8086:0006 | Intel      | 82599ES 10-Gigabit SFI/SF... | 2     | ix         | 92A93D51C5 |
| 8086:1502 | 1734:11b7 | Intel      | 82579LM Gigabit Network C... | 2     | em         | EBCDA9A77F |
| 8086:150e | 8086:12a2 | Intel      | 82580 Gigabit Network Con... | 2     | igb        | 5F9F2C2232 |
| 8086:1521 | 8086:00a2 | Intel      | I350 Gigabit Network Conn... | 2     | igb        | 7A9D95B303 |
| 8086:153a | 17aa:30a6 | Intel      | Ethernet Connection I217-LM  | 2     | em         | DABCAB55BB |
| 10ec:8168 | 7470:3468 | Realtek... | RTL8111/8168/8411 PCI Exp... | 1     | re         | EFE3DBF989 |
| 1425:0000 |           | Chelsio... |                              | 1     |            | 9EA2AEEB86 |
| 14e4:163b | 1028:02a4 | Broadcom   | NetXtreme II BCM5716 Giga... | 1     | bce        | 245D470945 |
| 14e4:164c | 103c:7037 | Broadcom   | NetXtreme II BCM5708 Giga... | 1     | bce        | 4EBC960E9C |
| 14e4:1659 | 14e4:1659 | Broadcom   | NetXtreme BCM5721 Gigabit... | 1     | bge        | F3854BA6E8 |
| 15b3:1003 | 15b3:0129 | Mellano... | MT27500 Family [ConnectX-3]  | 1     |            | 39B99E57AF |
| 15b3:1013 | 15b3:0008 | Mellano... | MT27700 Family [ConnectX-4]  | 1     | mlx5_core  | 93A8B87E1C |
| 15b3:1015 | 15b3:0003 | Mellano... | MT27710 Family [ConnectX-... | 1     | mlx5_core  | 93428C6E97 |
| 15b3:1017 | 15b3:0020 | Mellano... | MT27800 Family [ConnectX-5]  | 1     | mlx5_core  | D6AFDBD24B |
| 15b3:6750 | 15b3:0015 | Mellano... | MT26448 [ConnectX EN 10Gi... | 1     | mlx4_core  | C1D4BBD74E |
| 15b3:6750 | 15b3:0021 | Mellano... | MT26448 [ConnectX EN 10Gi... | 1     | mlx4_core  | 5008BC3F03 |
| 4040:0100 | 103c:1740 | NetXen ... | NX3031 Multifunction 1/10... | 1     |            | CD1101B9A1 |
| 4040:0100 | 103c:705b | NetXen ... | NX3031 Multifunction 1/10... | 1     |            | 917AB2C4E6 |
| 8086:105e | 8086:115e | Intel      | 82571EB/82571GB Gigabit E... | 1     | em         | 4E074CB643 |
| 8086:10b9 | 8086:1083 | Intel      | 82572EI Gigabit Ethernet ... | 1     | em         | D224B1F8E0 |
| 8086:10d3 |           | Intel      | 82574L Gigabit Network Co... | 1     | em         | 1F4D1E4607 |
| 8086:10d3 | 8086:34ec | Intel      | 82574L Gigabit Network Co... | 1     | em         | 6B7FBA08DD |
| 8086:10ef | 8086:34ec | Intel      | 82578DM Gigabit Network C... | 1     | em         | 6B7FBA08DD |
| 8086:150e | 1734:11a8 | Intel      | 82580 Gigabit Network Con... | 1     | igb        | A9D034FE42 |
| 8086:1533 | 8086:35ba | Intel      | I210 Gigabit Network Conn... | 1     | igb        | 2793B07B38 |
| 8086:15b7 | 15d9:15b7 | Intel      | Ethernet Connection (2) I... | 1     | em         | F6CF8F7870 |
| 8086:1f41 | 8086:1f41 | Intel      | Ethernet Connection I354     | 1     | igb        | 640B454366 |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 103c:3302 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 13    | ipmi       | 82D00F440D |
| 8086:19e0 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     |            | E6D9E7AF4E |
| 8086:a1a4 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1a4 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a324 | 15d9:1b0e | Intel      | Cannon Lake PCH SPI Contr... | 3     |            | 70B8F97D6C |
| 8086:a368 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 3     |            | 70B8F97D6C |
| 8086:a369 | 15d9:1b0e | Intel      | Cannon Lake PCH Serial IO... | 3     |            | 70B8F97D6C |
| 1077:2532 | 103c:3262 | QLogic     | ISP2532-based 8Gb Fibre C... | 2     | isp        | D35F62BA44 |
| 8086:a1a4 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1a4 | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1a4 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a324 | 1028:088f | Intel      | Cannon Lake PCH SPI Contr... | 2     |            | EBC09E92EB |
| 1077:2432 | 103c:7040 | QLogic     | ISP2432-based 4Gb Fibre C... | 1     |            | 7CC48A8D08 |
| 10df:fe00 | 103c:1708 | Emulex     | Zephyr-X LightPulse Fibre... | 1     |            | 2B539FCF18 |
| 1425:4601 |           | Chelsio... | T420-CR Unified Wire Stor... | 1     |            | 9EA2AEEB86 |
| 8086:19e0 | 15d9:0982 | Intel      | Atom Processor C3000 Seri... | 1     |            | AC3F761F23 |
| 8086:a1a4 | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | CA41B3F700 |
| 8086:a1a4 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 91B07FA8B9 |
| 8086:a1a4 | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | FFAA30BC08 |
| 8086:a324 | 1028:0891 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | 25E20C3F35 |
| 8086:a324 | 15d9:1b09 | Intel      | Cannon Lake PCH SPI Contr... | 1     |            | C9ABEB0DFE |
| 8086:a368 | 15d9:1b09 | Intel      | Cannon Lake PCH Serial IO... | 1     |            | C9ABEB0DFE |
| 8086:a369 | 15d9:1b09 | Intel      | Cannon Lake PCH Serial IO... | 1     |            | C9ABEB0DFE |

### Signal processing (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:6f30 | 8086:6f30 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f34 | 8086:6f34 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f36 | 8086:6f36 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f37 | 8086:6f37 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f7d | 8086:6f7d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:204d |           | Intel      | Sky Lake-E M3KTI Registers   | 14    |            | 6460F775B0 |
| 8086:2058 |           | Intel      | Sky Lake-E KTI 0             | 13    |            | 6460F775B0 |
| 8086:2015 |           | Intel      | Sky Lake-E Ubox Registers    | 11    |            | 91B07FA8B9 |
| 8086:8c24 | 15d9:0921 | Intel      | 8 Series Chipset Family T... | 11    |            | F2C6B4AA4D |
| 8086:0e30 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     |            | 8F4B51DABD |
| 8086:0e34 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     |            | 8F4B51DABD |
| 8086:0e36 | 1028:0528 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 8     |            | 8F4B51DABD |
| 8086:2088 |           | Intel      | Sky Lake-E DDRIO Registers   | 8     |            | 6460F775B0 |
| 8086:2f30 | 8086:2f30 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 5ACC629D2E |
| 8086:2f32 | 8086:2f32 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 5ACC629D2E |
| 8086:2f34 | 8086:2f34 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 5ACC629D2E |
| 8086:2f36 | 8086:2f36 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 5ACC629D2E |
| 8086:2f37 | 8086:2f37 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 5ACC629D2E |
| 8086:2f7d | 8086:2f7d | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 8     |            | 5ACC629D2E |
| 8086:8c24 | 15d9:086d | Intel      | 8 Series Chipset Family T... | 8     |            | 12E3F4C980 |
| 8086:2f33 | 8086:2f33 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 7     |            | 5ACC629D2E |
| 8086:204c |           | Intel      | Sky Lake-E M3KTI Registers   | 5     |            | 91B07FA8B9 |
| 8086:3c43 | 1028:04f7 | Intel      | Xeon E5/Core i7 Ring to P... | 4     |            | 77475B714A |
| 8086:3c44 | 1028:04f7 | Intel      | Xeon E5/Core i7 Ring to Q... | 4     |            | 77475B714A |
| 8086:3c46 | 1028:04f7 | Intel      | Xeon E5/Core i7 Processor... | 4     |            | 77475B714A |
| 8086:3ce6 | 1028:04f7 | Intel      | Xeon E5/Core i7 QuickPath... | 4     |            | 77475B714A |
| 8086:a131 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 4     |            | 9D69197550 |
| 8086:0e30 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 92A93D51C5 |
| 8086:0e34 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 92A93D51C5 |
| 8086:0e36 | 1028:04f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 3     |            | 92A93D51C5 |
| 8086:2015 | 1734:122f | Intel      | Sky Lake-E Ubox Registers    | 3     |            | 6460F775B0 |
| 8086:2f30 | 15d9:0832 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | F36F748797 |
| 8086:2f34 | 15d9:0832 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | F36F748797 |
| 8086:2f36 | 15d9:0832 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | F36F748797 |
| 8086:2f37 | 15d9:0832 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | F36F748797 |
| 8086:2f7d | 15d9:0832 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 3     |            | F36F748797 |
| 8086:8c24 | 15d9:0801 | Intel      | 8 Series Chipset Family T... | 3     |            | CF2E66B6AA |
| 8086:8c24 | 15d9:0842 | Intel      | 8 Series Chipset Family T... | 3     |            | 0C0FE552AA |
| 8086:a131 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 3     |            | EFE3DBF989 |
| 8086:a1b1 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1b1 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a379 | 15d9:1b0e | Intel      | Cannon Lake PCH Thermal C... | 3     |            | 70B8F97D6C |
| 8086:2f30 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 533B1E078E |
| 8086:2f34 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 533B1E078E |
| 8086:2f36 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 533B1E078E |
| 8086:2f37 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 533B1E078E |
| 8086:2f7d | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 2     |            | 533B1E078E |
| 8086:3c43 | 1028:0528 | Intel      | Xeon E5/Core i7 Ring to P... | 2     |            | 7CEC65D8F8 |
| 8086:3c44 | 1028:0528 | Intel      | Xeon E5/Core i7 Ring to Q... | 2     |            | 7CEC65D8F8 |
| 8086:3c46 | 1028:0528 | Intel      | Xeon E5/Core i7 Processor... | 2     |            | 7CEC65D8F8 |
| 8086:3ce6 | 1028:0528 | Intel      | Xeon E5/Core i7 QuickPath... | 2     |            | 7CEC65D8F8 |
| 8086:6f30 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | C2BB148E8A |
| 8086:6f34 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | C2BB148E8A |
| 8086:6f36 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | C2BB148E8A |
| 8086:6f37 | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | C2BB148E8A |
| 8086:6f7d | 103c:21ea | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 2     |            | C2BB148E8A |
| 8086:8c24 | 15d9:0803 | Intel      | 8 Series Chipset Family T... | 2     |            | FC4265EB19 |
| 8086:8c24 | 15d9:0805 | Intel      | 8 Series Chipset Family T... | 2     |            | 2758B438C6 |
| 8086:8d24 | 15d9:0857 | Intel      | C610/X99 series chipset T... | 2     |            | 14A919AB3F |
| 8086:a131 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 2     |            | B34EE32475 |
| 8086:a1b1 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1b1 | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1b1 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a379 | 1028:088f | Intel      | Cannon Lake PCH Thermal C... | 2     |            | EBC09E92EB |
| 8086:0e30 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | C1D4BBD74E |
| 8086:0e30 | 152d:899b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | A4980E3EA4 |
| 8086:0e30 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e30 | 1734:11f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | A9D034FE42 |
| 8086:0e34 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | C1D4BBD74E |
| 8086:0e34 | 152d:899b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | A4980E3EA4 |
| 8086:0e34 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e34 | 1734:11f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | A9D034FE42 |
| 8086:0e36 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | C1D4BBD74E |
| 8086:0e36 | 152d:899b | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | A4980E3EA4 |
| 8086:0e36 | 15d9:0703 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | 1F4D1E4607 |
| 8086:0e36 | 1734:11f8 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | A9D034FE42 |
| 8086:0e38 | 1043:84f0 | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 1     |            | C1D4BBD74E |
| 8086:1d24 | 152d:899b | Intel      | C600/X79 series chipset T... | 1     |            | A4980E3EA4 |
| 8086:1d24 | 15d9:062f | Intel      | C600/X79 series chipset T... | 1     |            | A3BCB2FCF1 |
| 8086:1d24 | 15d9:0703 | Intel      | C600/X79 series chipset T... | 1     |            | 1F4D1E4607 |
| 8086:2015 | 17aa:1037 | Intel      | Sky Lake-E Ubox Registers    | 1     |            | FFAA30BC08 |
| 8086:204c | 17aa:1037 | Intel      | Sky Lake-E M3KTI Registers   | 1     |            | FFAA30BC08 |
| 8086:204d | 17aa:1037 | Intel      | Sky Lake-E M3KTI Registers   | 1     |            | FFAA30BC08 |
| 8086:2058 | 17aa:1037 | Intel      | Sky Lake-E KTI 0             | 1     |            | FFAA30BC08 |
| 8086:2088 | 17aa:1037 | Intel      | Sky Lake-E DDRIO Registers   | 1     |            | FFAA30BC08 |
| 8086:2f30 | 15d9:0821 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3C7D64A2CB |
| 8086:2f32 | 15d9:0821 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3C7D64A2CB |
| 8086:2f34 | 15d9:0821 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3C7D64A2CB |
| 8086:2f36 | 15d9:0821 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3C7D64A2CB |
| 8086:2f37 | 15d9:0821 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3C7D64A2CB |
| 8086:2f38 | 103c:21ea | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | B5BF9162B0 |
| 8086:2f38 | 8086:2f38 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 93A8B87E1C |
| 8086:2f7d | 15d9:0821 | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 1     |            | 3C7D64A2CB |
| 8086:3c43 | 1028:048c | Intel      | Xeon E5/Core i7 Ring to P... | 1     |            | EDA4A540C7 |
| 8086:3c43 | 1028:0518 | Intel      | Xeon E5/Core i7 Ring to P... | 1     |            | 813CC71069 |
| 8086:3c43 | 15d9:062f | Intel      | Xeon E5/Core i7 Ring to P... | 1     |            | A3BCB2FCF1 |
| 8086:3c43 | 1734:11b5 | Intel      | Xeon E5/Core i7 Ring to P... | 1     |            | D6AFDBD24B |
| 8086:3c43 | 8086:3582 | Intel      | Xeon E5/Core i7 Ring to P... | 1     |            | 474B0E44EA |
| 8086:3c44 | 1028:048c | Intel      | Xeon E5/Core i7 Ring to Q... | 1     |            | EDA4A540C7 |
| 8086:3c44 | 1028:0518 | Intel      | Xeon E5/Core i7 Ring to Q... | 1     |            | 813CC71069 |

### Smbus (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c22 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 19    | ichsmb     | 9301BD0E0F |
| 8086:8c22 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    |            | F2C6B4AA4D |
| 8086:19df | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     |            | E6D9E7AF4E |
| 8086:2292 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     |            | CE87A10F79 |
| 8086:8c22 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     |            | 12E3F4C980 |
| 8086:3a30 | 1014:3a30 | Intel      | 82801JI (ICH10 Family) SM... | 5     |            | 5F9F2C2232 |
| 8086:8c22 | 1028:05e5 | Intel      | 8 Series/C220 Series Chip... | 4     |            | 6CBE8CABB7 |
| 8086:8d22 | 103c:8030 | Intel      | C610/X99 series chipset S... | 4     |            | 533B1E078E |
| 8086:a123 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 4     |            | 9D69197550 |
| 8086:1c22 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 3     |            | F60388BF6A |
| 8086:8c22 | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 3     |            | CF2E66B6AA |
| 8086:8c22 | 15d9:0842 | Intel      | 8 Series/C220 Series Chip... | 3     |            | 0C0FE552AA |
| 8086:8d22 | 15d9:0832 | Intel      | C610/X99 series chipset S... | 3     |            | F36F748797 |
| 8086:a123 | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 3     |            | EFE3DBF989 |
| 8086:a1a3 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1a3 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a323 | 15d9:1b0e | Intel      | Cannon Lake PCH SMBus Con... | 3     |            | 70B8F97D6C |
| 1022:790b | 1022:790b | AMD        | FCH SMBus Controller         | 2     | intsmb     | C42933F9FD |
| 1022:790b | 15d9:790b | AMD        | FCH SMBus Controller         | 2     | intsmb     | 4228478ECF |
| 8086:1c22 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 2     |            | 3881A96CEE |
| 8086:1c22 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 2     |            | EBCDA9A77F |
| 8086:1d70 | 1734:11b6 | Intel      | C600/X79 series chipset S... | 2     |            | A9D034FE42 |
| 8086:269b | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | ichsmb     | 411F470773 |
| 8086:8c22 | 15d9:0803 | Intel      | 8 Series/C220 Series Chip... | 2     |            | FC4265EB19 |
| 8086:8c22 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 2     |            | 2758B438C6 |
| 8086:8c22 | 17aa:30b0 | Intel      | 8 Series/C220 Series Chip... | 2     |            | DABCAB55BB |
| 8086:8d22 | 15d9:0857 | Intel      | C610/X99 series chipset S... | 2     | ichsmb     | 14A919AB3F |
| 8086:8d22 | 1734:1201 | Intel      | C610/X99 series chipset S... | 2     |            | 7A9D95B303 |
| 8086:a123 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 2     |            | B34EE32475 |
| 8086:a1a3 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1a3 | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1a3 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     | ichsmb     | D088FBCF53 |
| 8086:a323 | 1028:088f | Intel      | Cannon Lake PCH SMBus Con... | 2     |            | EBC09E92EB |
| 1002:4385 | 1028:0488 | AMD        | SBx00 SMBus Controller       | 1     | intsmb     | FD37374E7B |
| 1002:4385 | 15d9:a811 | AMD        | SBx00 SMBus Controller       | 1     | intsmb     | 58A580DD6B |
| 1002:4385 | 15d9:ba11 | AMD        | SBx00 SMBus Controller       | 1     | intsmb     | 98F39AFF26 |
| 1022:790b | 1458:1000 | AMD        | FCH SMBus Controller         | 1     | intsmb     | 93E2466FC6 |
| 10de:0368 | 108e:534b | Nvidia     | MCP55 SMBus Controller       | 1     |            | 1D2D5F5A1F |
| 10de:0368 | 108e:6676 | Nvidia     | MCP55 SMBus Controller       | 1     |            | 970467EFEF |
| 8086:19df | 15d9:0982 | Intel      | Atom Processor C3000 Seri... | 1     |            | AC3F761F23 |
| 8086:1c22 | 1014:3a30 | Intel      | 6 Series/C200 Series Chip... | 1     |            | 350DBDBDC6 |
| 8086:1c22 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     |            | F88EAF06AC |
| 8086:1d22 | 1028:0518 | Intel      | C600/X79 series chipset S... | 1     |            | 813CC71069 |
| 8086:1d22 | 1043:84ef | Intel      | C600/X79 series chipset S... | 1     | ichsmb     | C1D4BBD74E |
| 8086:1d22 | 152d:899b | Intel      | C600/X79 series chipset S... | 1     |            | A4980E3EA4 |
| 8086:1d22 | 15d9:062f | Intel      | C600/X79 series chipset S... | 1     |            | A3BCB2FCF1 |
| 8086:1d22 | 15d9:0703 | Intel      | C600/X79 series chipset S... | 1     |            | 1F4D1E4607 |
| 8086:1d22 | 1734:11b6 | Intel      | C600/X79 series chipset S... | 1     |            | D6AFDBD24B |
| 8086:1d22 | 1734:11c2 | Intel      | C600/X79 series chipset S... | 1     |            | A9D034FE42 |
| 8086:1d22 | 8086:3582 | Intel      | C600/X79 series chipset S... | 1     |            | 474B0E44EA |
| 8086:1d70 | 152d:899b | Intel      | C600/X79 series chipset S... | 1     |            | A4980E3EA4 |
| 8086:1d70 | 8086:3582 | Intel      | C600/X79 series chipset S... | 1     |            | 474B0E44EA |
| 8086:1d71 | 8086:3582 | Intel      | C608/C606/X79 series chip... | 1     |            | 474B0E44EA |
| 8086:1f3c | 8086:7270 | Intel      | Atom processor C2000 PCU ... | 1     |            | 640B454366 |
| 8086:24d3 | 1734:1041 | Intel      | 82801EB/ER (ICH5/ICH5R) S... | 1     |            | ADB972BF8E |
| 8086:269b | 108e:4843 | Intel      | 631xESB/632xESB/3100 Chip... | 1     |            | 806421299D |
| 8086:269b | 8086:3478 | Intel      | 631xESB/632xESB/3100 Chip... | 1     |            | 0546131058 |
| 8086:3a30 | 15d9:0001 | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | 0A771C7B0E |
| 8086:3a30 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) SM... | 1     | ichsmb     | 9EA2AEEB86 |
| 8086:3a30 | 15d9:0404 | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | 6ACB4D8445 |
| 8086:3a30 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | 6DD2D44AA1 |
| 8086:3a30 | 15d9:060c | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | CCAF608BD7 |
| 8086:3a30 | 8086:34dc | Intel      | 82801JI (ICH10 Family) SM... | 1     |            | F54B954AC8 |
| 8086:3b30 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 14DABA3BDE |
| 8086:3b30 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ichsmb     | 6B7FBA08DD |
| 8086:3b30 | 8086:34f2 | Intel      | 5 Series/3400 Series Chip... | 1     |            | 044617A994 |
| 8086:8c22 | 15d9:0804 | Intel      | 8 Series/C220 Series Chip... | 1     |            | B6DF404FEA |
| 8086:8c22 | 8086:35b7 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 49AD4461DC |
| 8086:8c22 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     |            | 2793B07B38 |
| 8086:8c22 | 8086:8c22 | Intel      | 8 Series/C220 Series Chip... | 1     |            | FE8DC15588 |
| 8086:8d22 | 15d9:0821 | Intel      | C610/X99 series chipset S... | 1     |            | 3C7D64A2CB |
| 8086:8d22 | 15d9:0831 | Intel      | C610/X99 series chipset S... | 1     |            | 223968434F |
| 8086:8d22 | 15d9:0834 | Intel      | C610/X99 series chipset S... | 1     |            | 81DB3F5BE2 |
| 8086:8d22 | 1849:8d22 | Intel      | C610/X99 series chipset S... | 1     |            | 79A07689EC |
| 8086:8d22 | 19e5:2060 | Intel      | C610/X99 series chipset S... | 1     |            | AC2C7107D3 |
| 8086:8d22 | 8086:35c5 | Intel      | C610/X99 series chipset S... | 1     | ichsmb     | 289D61B1B2 |
| 8086:8d22 | 8086:7270 | Intel      | C610/X99 series chipset S... | 1     | ichsmb     | 93A8B87E1C |
| 8086:8d7d | 8086:35c5 | Intel      | C610/X99 series chipset M... | 1     |            | 289D61B1B2 |
| 8086:a123 | 1028:06a6 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 997DA6A5C6 |
| 8086:a123 | 103c:8165 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 0D13EC7AC2 |
| 8086:a123 | 15d9:0896 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5044047B6E |
| 8086:a123 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     |            | F6CF8F7870 |
| 8086:a123 | 15d9:0902 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 9F6632DE8B |
| 8086:a1a3 | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | CA41B3F700 |
| 8086:a1a3 | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 91B07FA8B9 |
| 8086:a1a3 | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     | ichsmb     | FFAA30BC08 |
| 8086:a2a3 | 15d9:093f | Intel      | 200 Series/Z370 Chipset F... | 1     |            | 825EC10782 |
| 8086:a323 | 1028:0891 | Intel      | Cannon Lake PCH SMBus Con... | 1     |            | 25E20C3F35 |
| 8086:a323 | 15d9:1b09 | Intel      | Cannon Lake PCH SMBus Con... | 1     |            | C9ABEB0DFE |

### Sound (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:2284 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 4     | hdac       | CE87A10F79 |
| 8086:0c0c | 17aa:30b0 | Intel      | Xeon E3-1200 v3/4th Gen C... | 2     | hdac       | DABCAB55BB |
| 8086:8c20 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 2     | hdac       | 2758B438C6 |
| 8086:8d20 | 15d9:0857 | Intel      | C610/X99 series chipset H... | 2     | hdac       | 14A919AB3F |
| 1002:aab0 | 1642:aab0 | AMD        | Oland/Hainan/Cape Verde/P... | 1     |            | FFAA30BC08 |
| 10de:0371 | 108e:6676 | Nvidia     | MCP55 High Definition Audio  | 1     | hdac       | 970467EFEF |
| 10de:0be3 | 10de:0847 | Nvidia     | High Definition Audio Con... | 1     | hdac       | F60388BF6A |
| 10de:0be3 | 3842:1311 | Nvidia     | High Definition Audio Con... | 1     | hdac       | C1638ADFA6 |
| 10de:0e0f | 1043:8572 | Nvidia     | GK208 HDMI/DP Audio Contr... | 1     | hdac       | C1D4BBD74E |
| 10de:0e0f | 3842:2717 | Nvidia     | GK208 HDMI/DP Audio Contr... | 1     | hdac       | 1EB3ED1B04 |
| 10de:0fb9 | 10de:11be | Nvidia     | GP107GL High Definition A... | 1     | hdac       | 4DA7433E8B |
| 10de:0fb9 | 10de:1c82 | Nvidia     | GP107GL High Definition A... | 1     | hdac       | 14A919AB3F |
| 10de:0fb9 | 1462:8c96 | Nvidia     | GP107GL High Definition A... | 1     | hdac       | 360E63CC66 |
| 10de:0fba | 3842:2951 | Nvidia     | GM206 High Definition Aud... | 1     | hdac       | 9F6632DE8B |
| 10de:0fbb | 103c:1153 | Nvidia     | GM204 High Definition Aud... | 1     | hdac       | 93A8B87E1C |
| 13f6:0111 | 153b:1144 | C-Media... | CMI8738/CMI8768 PCI Audio    | 1     | pcm        | F60388BF6A |
| 8086:0c0c | 15d9:0805 | Intel      | Xeon E3-1200 v3/4th Gen C... | 1     |            | 2758B438C6 |
| 8086:160c | 15d9:0805 | Intel      | Broadwell-U Audio Controller | 1     | hdac       | D29048AE5D |
| 8086:a170 | 15d9:089f | Intel      | 100 Series/C230 Series Ch... | 1     | hdac       | F6CF8F7870 |
| 8086:a170 | 15d9:0902 | Intel      | 100 Series/C230 Series Ch... | 1     | hdac       | 9F6632DE8B |
| 8086:a1f0 | 17aa:1037 | Intel      | Lewisburg MROM 0             | 1     | hdac       | FFAA30BC08 |
| 8086:a348 | 15d9:1b09 | Intel      | Cannon Lake PCH cAVS         | 1     | hdac       | C9ABEB0DFE |

### Storage/ata (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c02 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 16    | ahci       | 9301BD0E0F |
| 8086:8c02 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | ahci       | F2C6B4AA4D |
| 8086:19c2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     | ahci       | E6D9E7AF4E |
| 8086:22a3 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     | ahci       | CE87A10F79 |
| 8086:8c02 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     | ahci       | 12E3F4C980 |
| 8086:19b2 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 5     | ahci       | E6D9E7AF4E |
| 1b4b:9230 | 1028:1fe2 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 4     | ahci       | 55C1BD261F |
| 8086:1d02 | 1028:04f7 | Intel      | C600/X79 series chipset 6... | 4     | ahci       | 77475B714A |
| 8086:8c02 | 1028:05e5 | Intel      | 8 Series/C220 Series Chip... | 4     | ahci       | 6CBE8CABB7 |
| 8086:a102 | 15d9:0884 | Intel      | Q170/Q150/B150/H170/H110/... | 4     | ahci       | 9D69197550 |
| 8086:8c02 | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | CF2E66B6AA |
| 8086:8c02 | 15d9:0842 | Intel      | 8 Series/C220 Series Chip... | 3     | ahci       | 0C0FE552AA |
| 8086:8d02 | 1028:0601 | Intel      | C610/X99 series chipset 6... | 3     | ahci       | 5ACC629D2E |
| 8086:8d02 | 15d9:0832 | Intel      | C610/X99 series chipset 6... | 3     | ahci       | F36F748797 |
| 8086:8d62 | 1028:0601 | Intel      | C610/X99 series chipset s... | 3     | ahci       | 5ACC629D2E |
| 8086:a102 | 1028:06aa | Intel      | Q170/Q150/B150/H170/H110/... | 3     | ahci       | EFE3DBF989 |
| 8086:a182 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 55C1BD261F |
| 8086:a182 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 6460F775B0 |
| 8086:a1d2 | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 55C1BD261F |
| 8086:a1d2 | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     | ahci       | 6460F775B0 |
| 1022:7901 | 1022:7901 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | C42933F9FD |
| 1022:7901 | 15d9:7901 | AMD        | FCH SATA Controller [AHCI... | 2     | ahci       | 4228478ECF |
| 1b21:0612 | 15d9:0805 | ASMedia... | ASM1062 Serial ATA Contro... | 2     | ahci       | 2758B438C6 |
| 1b4b:9230 | 1b4b:9230 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 2     | ahci       | C42933F9FD |
| 8086:1c02 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 2     | ahci       | 3881A96CEE |
| 8086:1d02 | 1028:04f8 | Intel      | C600/X79 series chipset 6... | 2     | ahci       | 77F48D8337 |
| 8086:1d02 | 103c:18a9 | Intel      | C600/X79 series chipset 6... | 2     | ahci       | 996A6207DC |
| 8086:2681 | 8086:3476 | Intel      | 631xESB/632xESB SATA AHCI... | 2     | ahci       | 411F470773 |
| 8086:3a22 | 103c:330b | Intel      | 82801JI (ICH10 Family) SA... | 2     | ahci       | B1F7A57B01 |
| 8086:3b22 | 1028:02a5 | Intel      | 5 Series/3400 Series Chip... | 2     | ahci       | 56A394AC67 |
| 8086:3b22 | 1028:02a6 | Intel      | 5 Series/3400 Series Chip... | 2     | ahci       | A2EE02F234 |
| 8086:8c02 | 103c:330d | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 39B99E57AF |
| 8086:8c02 | 15d9:0805 | Intel      | 8 Series/C220 Series Chip... | 2     | ahci       | 2758B438C6 |
| 8086:8d02 | 15d9:0857 | Intel      | C610/X99 series chipset 6... | 2     | ahci       | 14A919AB3F |
| 8086:8d02 | 1734:1201 | Intel      | C610/X99 series chipset 6... | 2     | ahci       | 7A9D95B303 |
| 8086:8d62 | 15d9:0832 | Intel      | C610/X99 series chipset s... | 2     | ahci       | F36F748797 |
| 8086:8d62 | 1734:1201 | Intel      | C610/X99 series chipset s... | 2     | ahci       | 7A9D95B303 |
| 8086:a102 | 15d9:0886 | Intel      | Q170/Q150/B150/H170/H110/... | 2     | ahci       | B34EE32475 |
| 8086:a182 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     | ahci       | B062E0F4E4 |
| 8086:a182 | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     | ahci       | 32F145EA04 |
| 8086:a182 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     | ahci       | D088FBCF53 |
| 8086:a1d2 | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     | ahci       | B062E0F4E4 |
| 8086:a1d2 | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     | ahci       | 32F145EA04 |
| 8086:a1d2 | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     | ahci       | D088FBCF53 |
| 8086:a352 | 15d9:1b0e | Intel      | Cannon Lake PCH SATA AHCI... | 2     | ahci       | 70B8F97D6C |
| 1002:4391 | 1002:4391 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 58A580DD6B |
| 1022:7901 | 1458:1000 | AMD        | FCH SATA Controller [AHCI... | 1     | ahci       | 93E2466FC6 |
| 1b21:0612 | 1b21:1060 | ASMedia... | ASM1062 Serial ATA Contro... | 1     | ahci       | E59D5D41A5 |
| 1b4b:9230 | 1028:1fd6 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 1     | ahci       | B062E0F4E4 |
| 1b4b:9230 | 1138:9230 | Marvell... | 88SE9230 PCIe 2.0 x2 4-po... | 1     | ahci       | 9EA2AEEB86 |
| 2646:0010 | 2646:0100 | Kingsto... | HyperX Predator PCIe AHCI... | 1     | ahci       | 6C4D7ACEEC |
| 8086:19c2 | 15d9:0982 | Intel      | Atom Processor C3000 Seri... | 1     | ahci       | AC3F761F23 |
| 8086:1c02 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 8960A05012 |
| 8086:1c02 | 1734:11b8 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | 6CF7F9EA4B |
| 8086:1c02 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | EBCDA9A77F |
| 8086:1c02 | 8086:7270 | Intel      | 6 Series/C200 Series Chip... | 1     | ahci       | F88EAF06AC |
| 8086:1d02 | 1028:048c | Intel      | C600/X79 series chipset 6... | 1     | ahci       | EDA4A540C7 |
| 8086:1d02 | 1028:0518 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | 813CC71069 |
| 8086:1d02 | 1043:84ef | Intel      | C600/X79 series chipset 6... | 1     | ahci       | C1D4BBD74E |
| 8086:1d02 | 152d:899b | Intel      | C600/X79 series chipset 6... | 1     | ahci       | A4980E3EA4 |
| 8086:1d02 | 15d9:062f | Intel      | C600/X79 series chipset 6... | 1     | ahci       | A3BCB2FCF1 |
| 8086:1d02 | 15d9:0703 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | 1F4D1E4607 |
| 8086:1d02 | 1734:11b6 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | D6AFDBD24B |
| 8086:1d02 | 1734:11c2 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | A9D034FE42 |
| 8086:1d02 | 8086:3582 | Intel      | C600/X79 series chipset 6... | 1     | ahci       | 474B0E44EA |
| 8086:1f22 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 1     | ahci       | 640B454366 |
| 8086:1f32 | 8086:7270 | Intel      | Atom processor C2000 AHCI... | 1     | ahci       | 640B454366 |
| 8086:2681 | 108e:4843 | Intel      | 631xESB/632xESB SATA AHCI... | 1     | ahci       | 806421299D |
| 8086:3a22 | 15d9:0001 | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | 0A771C7B0E |
| 8086:3a22 | 15d9:0400 | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | 9EA2AEEB86 |
| 8086:3a22 | 15d9:0404 | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | 6ACB4D8445 |
| 8086:3a22 | 15d9:060c | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | CCAF608BD7 |
| 8086:3a22 | 8086:34dc | Intel      | 82801JI (ICH10 Family) SA... | 1     | ahci       | F54B954AC8 |
| 8086:3b22 | 8086:34ec | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 6B7FBA08DD |
| 8086:8c02 | 15d9:0803 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 0006D96181 |
| 8086:8c02 | 15d9:0804 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | B6DF404FEA |
| 8086:8c02 | 8086:35b7 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 49AD4461DC |
| 8086:8c02 | 8086:35b9 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | 2793B07B38 |
| 8086:8c02 | 8086:8c02 | Intel      | 8 Series/C220 Series Chip... | 1     | ahci       | FE8DC15588 |
| 8086:8d02 | 1028:0600 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 4389B1CE81 |
| 8086:8d02 | 1028:061a | Intel      | C610/X99 series chipset 6... | 1     | ahci       | FCD1A34E85 |
| 8086:8d02 | 1028:0627 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 4710D6000D |
| 8086:8d02 | 103c:8030 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | C2BB148E8A |
| 8086:8d02 | 15d9:0831 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 223968434F |
| 8086:8d02 | 15d9:0834 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 81DB3F5BE2 |
| 8086:8d02 | 1849:8d02 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 79A07689EC |
| 8086:8d02 | 8086:35c5 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 289D61B1B2 |
| 8086:8d02 | 8086:7270 | Intel      | C610/X99 series chipset 6... | 1     | ahci       | 93A8B87E1C |
| 8086:8d62 | 1028:0600 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 4389B1CE81 |
| 8086:8d62 | 1028:061a | Intel      | C610/X99 series chipset s... | 1     | ahci       | FCD1A34E85 |
| 8086:8d62 | 1028:0627 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 4710D6000D |
| 8086:8d62 | 103c:8030 | Intel      | C610/X99 series chipset s... | 1     | ahci       | C2BB148E8A |
| 8086:8d62 | 15d9:0831 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 223968434F |
| 8086:8d62 | 15d9:0857 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 14A919AB3F |
| 8086:8d62 | 1849:8d62 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 79A07689EC |
| 8086:8d62 | 19e5:2060 | Intel      | C610/X99 series chipset s... | 1     | ahci       | AC2C7107D3 |
| 8086:8d62 | 8086:35c5 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 289D61B1B2 |
| 8086:8d62 | 8086:7270 | Intel      | C610/X99 series chipset s... | 1     | ahci       | 93A8B87E1C |
| 8086:a102 | 1028:06a6 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 997DA6A5C6 |
| 8086:a102 | 103c:8165 | Intel      | Q170/Q150/B150/H170/H110/... | 1     | ahci       | 0D13EC7AC2 |

### Storage/ide (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3a20 | 103c:330d | Intel      | 82801JI (ICH10 Family) 4 ... | 8     | atapci     | 467F7683F6 |
| 8086:2921 | 1028:0236 | Intel      | 82801IB (ICH9) 2 port SAT... | 5     | atapci     | 9EE7FF6592 |
| 8086:3a20 | 1014:3a20 | Intel      | 82801JI (ICH10 Family) 4 ... | 5     | atapci     | 5F9F2C2232 |
| 8086:3a26 | 1014:3a26 | Intel      | 82801JI (ICH10 Family) 2 ... | 5     | atapci     | 5F9F2C2232 |
| 8086:2921 | 1028:0235 | Intel      | 82801IB (ICH9) 2 port SAT... | 4     | atapci     | A2B6B36770 |
| 1166:0214 | 103c:320b | Broadcom   | BCM5785 [HT1000] IDE         | 2     | atapci     | 8A7564245E |
| 8086:1c08 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 2     | atapci     | F60388BF6A |
| 8086:269e | 1028:01b2 | Intel      | 631xESB/632xESB IDE Contr... | 2     | atapci     | F3854BA6E8 |
| 8086:269e | 103c:31fe | Intel      | 631xESB/632xESB IDE Contr... | 2     | atapci     | 658BE87971 |
| 8086:269e | 8086:3476 | Intel      | 631xESB/632xESB IDE Contr... | 2     | atapci     | 411F470773 |
| 8086:3a26 | 103c:330d | Intel      | 82801JI (ICH10 Family) 2 ... | 2     | atapci     | CD1101B9A1 |
| 1002:4390 | 15d9:ba11 | AMD        | SB7x0/SB8x0/SB9x0 SATA Co... | 1     | ahci       | 98F39AFF26 |
| 1002:439c | 15d9:ba11 | AMD        | SB7x0/SB8x0/SB9x0 IDE Con... | 1     | atapci     | 98F39AFF26 |
| 1095:0680 | 1095:0680 | Silicon... | PCI0680 Ultra ATA-133 Hos... | 1     | atapci     | BB83934454 |
| 10de:036e | 108e:534b | Nvidia     | MCP55 IDE                    | 1     | atapci     | 1D2D5F5A1F |
| 10de:036e | 108e:6676 | Nvidia     | MCP55 IDE                    | 1     | atapci     | 970467EFEF |
| 10de:037f | 108e:534b | Nvidia     | MCP55 SATA Controller        | 1     | atapci     | 1D2D5F5A1F |
| 10de:037f | 108e:6676 | Nvidia     | MCP55 SATA Controller        | 1     | atapci     | 970467EFEF |
| 1166:0214 | 1028:01eb | Broadcom   | BCM5785 [HT1000] IDE         | 1     | atapci     | E98F23CD45 |
| 1166:024b | 1028:01eb | Broadcom   | BCM5785 [HT1000] SATA (PA... | 1     | atapci     | E98F23CD45 |
| 8086:1c00 | 1014:3a20 | Intel      | 6 Series/C200 Series Chip... | 1     | atapci     | 350DBDBDC6 |
| 8086:1c00 | 103c:330d | Intel      | 6 Series/C200 Series Chip... | 1     | atapci     | 1EBF1B71BD |
| 8086:1c00 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 1     | atapci     | F60388BF6A |
| 8086:1c00 | 1043:8498 | Intel      | 6 Series/C200 Series Chip... | 1     | atapci     | 04C5C07D61 |
| 8086:1c08 | 1014:3a26 | Intel      | 6 Series/C200 Series Chip... | 1     | atapci     | 350DBDBDC6 |
| 8086:1c08 | 103c:330d | Intel      | 6 Series/C200 Series Chip... | 1     | atapci     | 1EBF1B71BD |
| 8086:1d00 | 103c:18a9 | Intel      | C600/X79 series chipset 4... | 1     | atapci     | 1E629D4C5A |
| 8086:24db | 1028:016c | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 1     | atapci     | BB83934454 |
| 8086:24db | 1734:1041 | Intel      | 82801EB/ER (ICH5/ICH5R) I... | 1     | atapci     | ADB972BF8E |
| 8086:2680 | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | atapci     | F3854BA6E8 |
| 8086:2680 | 1028:01b9 | Intel      | 631xESB/632xESB/3100 Chip... | 1     | atapci     | F181777604 |
| 8086:269e | 1028:01b9 | Intel      | 631xESB/632xESB IDE Contr... | 1     | atapci     | F181777604 |
| 8086:269e | 108e:4843 | Intel      | 631xESB/632xESB IDE Contr... | 1     | atapci     | 806421299D |
| 8086:27df | 103c:31fe | Intel      | 82801G (ICH7 Family) IDE ... | 1     | atapci     | D6114DE1CC |
| 8086:2920 | 1028:023c | Intel      | 82801IR/IO/IH (ICH9R/DO/D... | 1     | atapci     | 6A1CB01323 |
| 8086:3a20 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | atapci     | F23BF8E1A7 |
| 8086:3a20 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) 4 ... | 1     | atapci     | 6DD2D44AA1 |
| 8086:3a26 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) 2 ... | 1     | atapci     | F23BF8E1A7 |
| 8086:3a26 | 15d9:0600 | Intel      | 82801JI (ICH10 Family) 2 ... | 1     | atapci     | 6DD2D44AA1 |
| 8086:3b20 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 1     | atapci     | 14DABA3BDE |
| 8086:3b20 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | atapci     | AB1D30ED74 |
| 8086:3b26 | 1014:0377 | Intel      | 5 Series/3400 Series Chip... | 1     | atapci     | 14DABA3BDE |
| 8086:3b26 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | atapci     | AB1D30ED74 |
| 8086:a1bc | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | FFAA30BC08 |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 144d:a808 | 144d:a801 | Samsung... | NVMe SSD Controller SM981... | 6     | nvme       | FFAA30BC08 |
| 144d:a804 | 144d:a801 | Samsung... | NVMe SSD Controller SM961... | 4     | nvme       | B34EE32475 |
| 14a4:22f1 | 1b4b:1093 | Lite-On... | M8Pe Series NVMe SSD         | 2     | nvme       | D6312ECF58 |
| 1987:5012 | 1987:5012 | Phison ... | E12 NVMe Controller          | 2     | nvme       | A7DA701FBD |
| 1db2:2302 | 1db2:2302 | ATP ELE... |                              | 2     | nvme       | 9D69197550 |
| 8086:0953 | 8086:370d | Intel      | PCIe Data Center SSD         | 2     | nvme       | 4710D6000D |
| 8086:2522 | 8086:3806 | Intel      | NVMe Optane Memory Series    | 2     | nvme       | FC4265EB19 |
| 126f:2262 | 126f:2262 | Silicon... | SM2262/SM2262EN SSD Contr... | 1     | nvme       | 93A8B87E1C |
| 15b7:5002 | 15b7:5002 | Sandisk    | WD Black 2018/SN750 / PC ... | 1     | nvme       | FB3F2294AB |
| 15b7:5009 | 15b7:5009 | Sandisk    | WD Blue SN550 NVMe SSD       | 1     | nvme       | 12E3F4C980 |
| 1987:5008 | 1987:5008 | Phison ... | NVMe Storage Controller      | 1     | nvme       | 18EA6EC987 |
| 1dee:2262 | 1dee:1dee | Biwin S... |                              | 1     | nvme       | 93A8B87E1C |
| 2646:5008 | 2646:5008 | Kingsto... | U-SNS8154P3 NVMe SSD         | 1     | nvme       | 89C0064AEB |
| 8086:0953 | 108e:370b | Intel      | PCIe Data Center SSD         | 1     | nvme       | 7CEC65D8F8 |
| 8086:f1a5 | 8086:390a | Intel      | SSD 600P Series              | 1     | nvme       | C42933F9FD |
| 8086:f1a8 | 8086:390d | Intel      | SSD 660P Series              | 1     | nvme       | CF2E66B6AA |
| c0a9:5403 | c0a9:2100 | Micron/... | NVMe Controller              | 1     | nvme       | C41D989A06 |

### Storage/raid (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0060 | 1028:1f0c | Broadco... | MegaRAID SAS 1078            | 11    | mfi        | A2B6B36770 |
| 103c:323a | 103c:3245 | Hewlett... | Smart Array G6 controllers   | 10    | ciss       | 82D00F440D |
| 1000:005b | 1028:1f34 | Broadco... | MegaRAID SAS 2208 [Thunde... | 8     | mfi        | 8F4B51DABD |
| 1000:005b | 1028:1f38 | Broadco... | MegaRAID SAS 2208 [Thunde... | 4     | mfi        | 77F48D8337 |
| 1000:005f | 1028:1f44 | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 4     | mfi        | 997DA6A5C6 |
| 1000:005f | 1028:1f4b | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 4     | mfi        | 5ACC629D2E |
| 1000:0079 | 1028:1f17 | Broadco... | MegaRAID SAS 2108 [Libera... | 4     | mfi        | 149B6DB16F |
| 1000:0073 | 1028:1f51 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 3     | mfi        | 77475B714A |
| 1000:0079 | 1014:03c7 | Broadco... | MegaRAID SAS 2108 [Libera... | 3     | mfi        | 8BBC599CDD |
| 8086:1c04 | 1028:04dd | Intel      | 6 Series/C200 Series Desk... | 3     | ahci       | 668C05619B |
| 1000:0014 | 1734:1238 | Broadco... | MegaRAID Tri-Mode SAS3516    | 2     | mrsas      | 6460F775B0 |
| 1000:005d | 1028:1f49 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 2     | mfi        | 94F3A7B95A |
| 1000:0073 | 1014:03b1 | Broadco... | MegaRAID SAS 2008 [Falcon]   | 2     | mfi        | 71D412D254 |
| 103c:3230 | 103c:3234 | Hewlett... | Smart Array Controller       | 2     | ciss       | 658BE87971 |
| 103c:3230 | 103c:3235 | Hewlett... | Smart Array Controller       | 2     | ciss       | 710C4F4AAB |
| 103c:3239 | 103c:21c5 | Hewlett... | Smart Array Gen9 Controllers | 2     | ciss       | D35F62BA44 |
| 103c:3239 | 103c:21cb | Hewlett... | Smart Array Gen9 Controllers | 2     | ciss       | D35F62BA44 |
| 103c:323a | 103c:3243 | Hewlett... | Smart Array G6 controllers   | 2     | ciss       | 4907DD5D8F |
| 103c:323b | 103c:3354 | Hewlett... | Smart Array Gen8 Controllers | 2     | ciss       | 996A6207DC |
| 8086:2826 | 17aa:30b0 | Intel      | C600/X79 series chipset S... | 2     | ahci       | DABCAB55BB |
| 9005:028b | 9005:0301 | Adaptec    | Series 6 - 6G SAS/PCIe 2     | 2     | aacraid    | 0546131058 |
| 1000:0017 | 17aa:103a | Broadco... | MegaRAID Tri-Mode SAS3408    | 1     | mrsas      | FFAA30BC08 |
| 1000:005b | 1028:1f2d | Broadco... | MegaRAID SAS 2208 [Thunde... | 1     | mrsas      | AC57AB9EF6 |
| 1000:005d | 1000:9363 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mfi        | 0573099467 |
| 1000:005d | 1028:1f41 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mrsas      | 32F145EA04 |
| 1000:005d | 1028:1f42 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mrsas      | 32F145EA04 |
| 1000:005d | 1028:1f47 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mfi        | 55C1BD261F |
| 1000:005f | 1734:1211 | Broadco... | MegaRAID SAS-3 3008 [Fury]   | 1     | mfi        | 0F4461E95F |
| 1000:0072 | 1028:1f51 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 7CEC65D8F8 |
| 1000:0072 | 1734:1177 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | D6AFDBD24B |
| 1000:0079 | 1000:9260 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | mfi        | 6DD2D44AA1 |
| 1000:0079 | 1000:9261 | Broadco... | MegaRAID SAS 2108 [Libera... | 1     | mfi        | 474B0E44EA |
| 1028:0013 | 1028:016c | Dell       | PowerEdge Expandable RAID... | 1     | amr        | BB83934454 |
| 1028:0015 | 1028:1f03 | Dell       | PowerEdge Expandable RAID... | 1     | mfi        | F3854BA6E8 |
| 103c:3220 | 103c:3225 | Hewlett... | Smart Array P600             | 1     | ciss       | 8A7564245E |
| 103c:3230 | 103c:3223 | Hewlett... | Smart Array Controller       | 1     | ciss       | 658BE87971 |
| 103c:323a | 103c:3241 | Hewlett... | Smart Array G6 controllers   | 1     | ciss       | B1F7A57B01 |
| 103c:323a | 103c:3249 | Hewlett... | Smart Array G6 controllers   | 1     | ciss       | 7CC48A8D08 |
| 103c:323b | 103c:3351 | Hewlett... | Smart Array Gen8 Controllers | 1     | ciss       | 54FD4A89D8 |
| 13c1:1004 | 13c1:1004 | 3ware      | 9650SE SATA-II RAID PCIe     | 1     | twa        | CF2E66B6AA |
| 17d3:1680 | 17d3:1212 | Areca T... | ARC-1680 series PCIe to S... | 1     | arcmsr     | 6B7FBA08DD |
| 8086:27c3 | 103c:3206 | Intel      | 82801GR/GDH (ICH7R/ICH7DH... | 1     | ahci       | D6114DE1CC |
| 8086:2826 | 15d9:0821 | Intel      | C600/X79 series chipset S... | 1     | ahci       | 3C7D64A2CB |
| 8086:2826 | 17aa:1037 | Intel      | C600/X79 series chipset S... | 1     | ahci       | FFAA30BC08 |
| 8086:2826 | 8086:7270 | Intel      | C600/X79 series chipset S... | 1     | ahci       | 91B07FA8B9 |
| 8086:3b25 | 1028:02a4 | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 245D470945 |
| 8086:3b25 | 8086:34ed | Intel      | 5 Series/3400 Series Chip... | 1     | ahci       | 044617A994 |
| 8086:8d06 | 1590:009c | Intel      | C610/X99 series chipset S... | 1     | ahci       | 533B1E078E |
| 8086:8d66 | 1590:009d | Intel      | C610/X99 series chipset s... | 1     | ahci       | 533B1E078E |
| 8086:a356 | 1028:088f | Intel      | 300 Series Chipset Family... | 1     |            | B72DB7DF7F |

### Storage/sas (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0072 | 1000:3020 | Broadco... | SAS2008 PCI-Express Fusio... | 10    | mps        | F36F748797 |
| 1000:0072 | 1028:1f1c | Broadco... | SAS2008 PCI-Express Fusio... | 4     | mps        | F23BF8E1A7 |
| 1000:0072 | 1028:1f1d | Broadco... | SAS2008 PCI-Express Fusio... | 4     | mps        | 9301BD0E0F |
| 1000:0072 | 1028:1f1e | Broadco... | SAS2008 PCI-Express Fusio... | 3     | mps        | 27B11C7A56 |
| 1000:0016 | 1028:1fcd | Broadco... | MegaRAID Tri-Mode SAS3508    | 2     | mrsas      | AA44179A5F |
| 1000:0087 | 1000:3020 | Broadco... | SAS2308 PCI-Express Fusio... | 2     | mps        | 0A771C7B0E |
| 1000:0097 | 1028:1f53 | Broadco... | SAS3008 PCI-Express Fusio... | 2     | mpr        | B062E0F4E4 |
| 1000:0016 | 1028:1fcb | Broadco... | MegaRAID Tri-Mode SAS3508    | 1     | mrsas      | E37DE1CD8C |
| 1000:005d | 19e5:da07 | Broadco... | MegaRAID SAS-3 3108 [Inva... | 1     | mrsas      | AC2C7107D3 |
| 1000:0064 | 1000:30d0 | Broadco... | SAS2116 PCI-Express Fusio... | 1     | mps        | CF2E66B6AA |
| 1000:0072 | 1000:0072 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 7CC48A8D08 |
| 1000:0072 | 1000:3040 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 49AD4461DC |
| 1000:0072 | 1000:3060 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | F88EAF06AC |
| 1000:0072 | 15d9:0400 | Broadco... | SAS2008 PCI-Express Fusio... | 1     | mps        | 6ACB4D8445 |
| 1000:0087 | 1000:3030 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mps        | E59D5D41A5 |
| 1000:0087 | 1028:1f38 | Broadco... | SAS2308 PCI-Express Fusio... | 1     | mps        | 92A93D51C5 |
| 1000:0097 | 1000:30e0 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpr        | 93E2466FC6 |
| 1000:0097 | 15d9:0808 | Broadco... | SAS3008 PCI-Express Fusio... | 1     | mpr        | 6C4D7ACEEC |
| 103c:3239 | 103c:21c7 | Hewlett... | Smart Array Gen9 Controllers | 1     | ciss       | 533B1E078E |
| 103c:3239 | 103c:21c8 | Hewlett... | Smart Array Gen9 Controllers | 1     | ciss       | C2BB148E8A |
| 8086:1d6a | 8086:3583 | Intel      | C600/X79 series chipset D... | 1     | isci       | 474B0E44EA |
| 8086:1d6b | 152d:899b | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | A4980E3EA4 |
| 8086:1d6b | 15d9:062f | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | A3BCB2FCF1 |
| 8086:1d6b | 15d9:0703 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | 1F4D1E4607 |
| 8086:1d6b | 1734:11b6 | Intel      | C602 chipset 4-Port SATA ... | 1     | isci       | D6AFDBD24B |
| 8086:1d6f | 1734:11b6 | Intel      | C600/X79 series chipset 4... | 1     | isci       | A9D034FE42 |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 1000:0058 | 1014:0394 | Broadco... | SAS1068E PCI-Express Fusi... | 3     | mpt        | 5F9F2C2232 |
| 1000:0058 | 1028:1f0f | Broadco... | SAS1068E PCI-Express Fusi... | 3     | mpt        | A9CF80B10F |
| 1000:0054 | 1028:1f09 | Broadco... | SAS1068 PCI-X Fusion-MPT SAS | 2     | mpt        | E98F23CD45 |
| 1000:0058 | 1028:1f0e | Broadco... | SAS1068E PCI-Express Fusi... | 2     | mpt        | 411477E260 |
| 1000:0030 | 1000:10b0 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mpt        | 970467EFEF |
| 1000:0030 | 103c:322a | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mpt        | 8A7564245E |
| 1000:0030 | 1734:1041 | Broadco... | 53c1030 PCI-X Fusion-MPT ... | 1     | mpt        | ADB972BF8E |
| 1425:4501 |           | Chelsio... | T420-CR Unified Wire Stor... | 1     |            | 9EA2AEEB86 |

### System peripheral (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:3422 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 31    |            | CCAF608BD7 |
| 8086:3423 |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 31    |            | CCAF608BD7 |
| 8086:342e |           | Intel      | 7500/5520/5500/X58 I/O Hu... | 29    |            | CCAF608BD7 |
| 8086:6f76 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 29    |            | 289D61B1B2 |
| 8086:6f88 |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6f8a |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6fae |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6faf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6fbc |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6fbd |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6fbe |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6fbf |           | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 28    |            | 289D61B1B2 |
| 8086:6f1d | 8086:6f1d | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f1e | 8086:6f1e | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f1f | 8086:6f1f | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f71 | 8086:6f71 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f98 | 8086:6f98 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f99 | 8086:6f99 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f9a | 8086:6f9a | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f9c | 8086:6f9c | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fa0 | 8086:6fa0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fa8 | 8086:6fa8 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6faa | 8086:6faa | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fab | 8086:6fab | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fac | 8086:6fac | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fad | 8086:6fad | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fb0 | 8086:6fb0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fb1 | 8086:6fb1 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fb2 | 8086:6fb2 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fb3 | 8086:6fb3 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fb4 | 8086:6fb4 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fb5 | 8086:6fb5 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fb6 | 8086:6fb6 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fb7 | 8086:6fb7 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fc0 | 8086:6fc0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fe0 | 8086:6fe0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6fe1 | 8086:6fe1 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6ff8 | 8086:6ff8 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6ffc | 8086:6fe0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6ffd | 8086:6fe0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6ffe | 8086:6fe0 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 23    |            | 289D61B1B2 |
| 8086:6f81 | 8086:6f81 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    |            | 289D61B1B2 |
| 8086:6fe2 | 8086:6fe2 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    |            | 289D61B1B2 |
| 8086:6fe3 | 8086:6fe3 | Intel      | Xeon E7 v4/Xeon E5 v4/Xeo... | 22    |            | 289D61B1B2 |
| 8086:2018 |           | Intel      | Sky Lake-E M2PCI Registers   | 14    |            | 6460F775B0 |
| 8086:2024 |           | Intel      | Sky Lake-E MM/Vt-d Config... | 14    |            | 6460F775B0 |
| 8086:2026 | 8086:2026 | Intel      | Sky Lake-E IOAPIC            | 14    | ioapic     | 6460F775B0 |
| 8086:2034 |           | Intel      | Sky Lake-E VT-d              | 14    |            | 6460F775B0 |
| 8086:2035 |           | Intel      | Sky Lake-E RAS Configurat... | 14    |            | 6460F775B0 |
| 8086:2036 | 8086:2036 | Intel      | Sky Lake-E IOxAPIC Config... | 14    | ioapic     | 6460F775B0 |
| 8086:2040 |           | Intel      | Sky Lake-E Integrated Mem... | 14    |            | 6460F775B0 |
| 8086:2041 |           | Intel      | Sky Lake-E Integrated Mem... | 14    |            | 6460F775B0 |
| 8086:2042 |           | Intel      | Sky Lake-E Integrated Mem... | 14    |            | 6460F775B0 |
| 8086:2043 |           | Intel      | Sky Lake-E Integrated Mem... | 14    |            | 6460F775B0 |
| 8086:2044 |           | Intel      | Sky Lake-E Integrated Mem... | 14    |            | 6460F775B0 |
| 8086:2045 |           | Intel      | Sky Lake-E LM Channel 1      | 14    |            | 6460F775B0 |
| 8086:2046 |           | Intel      | Sky Lake-E LMS Channel 1     | 14    |            | 6460F775B0 |
| 8086:2047 |           | Intel      | Sky Lake-E LMDP Channel 1    | 14    |            | 6460F775B0 |
| 8086:2048 |           | Intel      | Sky Lake-E DECS Channel 2    | 14    |            | 6460F775B0 |
| 8086:2049 |           | Intel      | Sky Lake-E LM Channel 2      | 14    |            | 6460F775B0 |
| 8086:204a |           | Intel      | Sky Lake-E LMS Channel 2     | 14    |            | 6460F775B0 |
| 8086:204b |           | Intel      | Sky Lake-E LMDP Channel 2    | 14    |            | 6460F775B0 |
| 8086:204e |           | Intel      | Sky Lake-E M3KTI Registers   | 14    |            | 6460F775B0 |
| 8086:2066 |           | Intel      | Sky Lake-E Integrated Mem... | 14    |            | 6460F775B0 |
| 8086:2f6e |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2f6f |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2f88 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2f8a |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2fae |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2faf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2fb8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2fb9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2fba |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2fbb |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2fbe |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2fbf |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2ff8 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:2ff9 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 14    |            | 5ACC629D2E |
| 8086:3422 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 14    |            | 82D00F440D |
| 8086:3423 | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 14    |            | 82D00F440D |
| 8086:342e | 003c:000b | Intel      | 7500/5520/5500/X58 I/O Hu... | 14    |            | 82D00F440D |
| 0e11:b203 | 103c:3305 | Compaq ... | Integrated Lights Out Con... | 13    |            | 82D00F440D |
| 0e11:b204 | 103c:3305 | Compaq ... | Integrated Lights Out  Pr... | 13    |            | 82D00F440D |
| 8086:2059 |           | Intel      | Sky Lake-E UPI Registers     | 13    |            | 6460F775B0 |
| 8086:2f68 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 12    |            | 5ACC629D2E |
| 8086:2fbc |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 12    |            | 5ACC629D2E |
| 8086:2fbd |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 12    |            | 5ACC629D2E |
| 8086:2fd0 |           | Intel      | Xeon E7 v3/Xeon E5 v3/Cor... | 12    |            | 5ACC629D2E |
| 103c:3306 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 11    |            | 39B99E57AF |
| 103c:3307 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 11    |            | 39B99E57AF |
| 8086:0e1d |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0e1e |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0e1f |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0e71 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0e80 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0e90 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0ea8 |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0eaa |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0eab |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |
| 8086:0eac |           | Intel      | Xeon E7 v2/Xeon E5 v2/Cor... | 11    |            | 92A93D51C5 |

### Usb controller (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:1c26 | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 19    | ehci       | 9301BD0E0F |
| 8086:1c2d | 1028:04dd | Intel      | 6 Series/C200 Series Chip... | 19    | ehci       | 9301BD0E0F |
| 103c:3300 | 103c:3305 | Hewlett... | Integrated Lights-Out Sta... | 13    | uhci       | 82D00F440D |
| 8086:3a34 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 12    | uhci       | 82D00F440D |
| 8086:3a35 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 12    | uhci       | 82D00F440D |
| 8086:3a36 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 12    | uhci       | 82D00F440D |
| 8086:3a3a | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 12    | ehci       | 82D00F440D |
| 103c:3300 | 103c:3381 | Hewlett... | Integrated Lights-Out Sta... | 11    | uhci       | 39B99E57AF |
| 8086:3a39 | 103c:330d | Intel      | 82801JI (ICH10 Family) US... | 11    | uhci       | 82D00F440D |
| 8086:8c26 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | ehci       | F2C6B4AA4D |
| 8086:8c2d | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | ehci       | F2C6B4AA4D |
| 8086:8c31 | 15d9:0921 | Intel      | 8 Series/C220 Series Chip... | 11    | xhci       | F2C6B4AA4D |
| 8086:1d26 | 1028:0528 | Intel      | C600/X79 series chipset U... | 10    | ehci       | 7CEC65D8F8 |
| 8086:1d2d | 1028:0528 | Intel      | C600/X79 series chipset U... | 10    | ehci       | 7CEC65D8F8 |
| 8086:2934 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 9     | uhci       | 9EE7FF6592 |
| 8086:2935 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 9     | uhci       | 9EE7FF6592 |
| 8086:2937 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 9     | uhci       | 9EE7FF6592 |
| 8086:2938 | 1028:0236 | Intel      | 82801I (ICH9 Family) USB ... | 9     | uhci       | 9EE7FF6592 |
| 8086:293a | 1028:0236 | Intel      | 82801I (ICH9 Family) USB2... | 9     | ehci       | 9EE7FF6592 |
| 8086:293c | 1028:0236 | Intel      | 82801I (ICH9 Family) USB2... | 9     | ehci       | 9EE7FF6592 |
| 8086:19d0 | 15d9:0969 | Intel      | Atom Processor C3000 Seri... | 8     | xhci       | E6D9E7AF4E |
| 8086:22b5 | 15d9:0891 | Intel      | Atom/Celeron/Pentium Proc... | 8     | xhci       | CE87A10F79 |
| 8086:2934 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 8     | uhci       | A2B6B36770 |
| 8086:2935 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 8     | uhci       | A2B6B36770 |
| 8086:2937 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 8     | uhci       | A2B6B36770 |
| 8086:2938 | 1028:0235 | Intel      | 82801I (ICH9 Family) USB ... | 8     | uhci       | A2B6B36770 |
| 8086:293a | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 8     | ehci       | A2B6B36770 |
| 8086:293c | 1028:0235 | Intel      | 82801I (ICH9 Family) USB2... | 8     | ehci       | A2B6B36770 |
| 8086:8c26 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     | ehci       | 12E3F4C980 |
| 8086:8c2d | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     | ehci       | 12E3F4C980 |
| 8086:8c31 | 15d9:086d | Intel      | 8 Series/C220 Series Chip... | 8     | xhci       | 12E3F4C980 |
| 8086:3a34 | 1014:3a34 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 5F9F2C2232 |
| 8086:3a35 | 1014:3a35 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 5F9F2C2232 |
| 8086:3a36 | 1014:3a36 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 5F9F2C2232 |
| 8086:3a37 | 1014:3a37 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 5F9F2C2232 |
| 8086:3a38 | 1014:3a38 | Intel      | 82801JI (ICH10 Family) US... | 5     | uhci       | 5F9F2C2232 |
| 8086:3a3a | 1014:3a3a | Intel      | 82801JI (ICH10 Family) US... | 5     | ehci       | 5F9F2C2232 |
| 8086:3a3c | 1014:3a3c | Intel      | 82801JI (ICH10 Family) US... | 5     | ehci       | 5F9F2C2232 |
| 103c:3300 | 103c:3309 | Hewlett... | Integrated Lights-Out Sta... | 4     | uhci       | 7031B0ED1E |
| 8086:1d26 | 1028:04f7 | Intel      | C600/X79 series chipset U... | 4     | ehci       | 77475B714A |
| 8086:1d26 | 103c:18a9 | Intel      | C600/X79 series chipset U... | 4     | ehci       | 54FD4A89D8 |
| 8086:1d2d | 1028:04f7 | Intel      | C600/X79 series chipset U... | 4     | ehci       | 77475B714A |
| 8086:1d2d | 103c:18a9 | Intel      | C600/X79 series chipset U... | 4     | ehci       | 54FD4A89D8 |
| 8086:8c26 | 1028:05e5 | Intel      | 8 Series/C220 Series Chip... | 4     | ehci       | 6CBE8CABB7 |
| 8086:8c2d | 1028:05e5 | Intel      | 8 Series/C220 Series Chip... | 4     | ehci       | 6CBE8CABB7 |
| 8086:8c31 | 1028:05e5 | Intel      | 8 Series/C220 Series Chip... | 4     | xhci       | 6CBE8CABB7 |
| 8086:8d26 | 1028:0601 | Intel      | C610/X99 series chipset U... | 4     | ehci       | 5ACC629D2E |
| 8086:8d26 | 103c:8030 | Intel      | C610/X99 series chipset U... | 4     | ehci       | 533B1E078E |
| 8086:8d2d | 1028:0601 | Intel      | C610/X99 series chipset U... | 4     | ehci       | 5ACC629D2E |
| 8086:8d2d | 103c:8030 | Intel      | C610/X99 series chipset U... | 4     | ehci       | 533B1E078E |
| 8086:8d31 | 103c:8030 | Intel      | C610/X99 series chipset U... | 4     | xhci       | 533B1E078E |
| 8086:a12f | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 4     | xhci       | 9D69197550 |
| 1b21:1142 | 1b21:1142 | ASMedia... | ASM1042A USB 3.0 Host Con... | 3     | xhci       | 14A919AB3F |
| 8086:1c26 | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci       | F60388BF6A |
| 8086:1c2d | 1043:8497 | Intel      | 6 Series/C200 Series Chip... | 3     | ehci       | F60388BF6A |
| 8086:1d26 | 1028:04f8 | Intel      | C600/X79 series chipset U... | 3     | ehci       | 92A93D51C5 |
| 8086:1d2d | 1028:04f8 | Intel      | C600/X79 series chipset U... | 3     | ehci       | 92A93D51C5 |
| 8086:3a34 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci       | F23BF8E1A7 |
| 8086:3a35 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci       | F23BF8E1A7 |
| 8086:3a36 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci       | F23BF8E1A7 |
| 8086:3a37 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci       | F23BF8E1A7 |
| 8086:3a38 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci       | F23BF8E1A7 |
| 8086:3a39 | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 3     | uhci       | F23BF8E1A7 |
| 8086:3a3a | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 3     | ehci       | F23BF8E1A7 |
| 8086:3a3c | 1028:02f1 | Intel      | 82801JI (ICH10 Family) US... | 3     | ehci       | F23BF8E1A7 |
| 8086:8c26 | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 3     | ehci       | CF2E66B6AA |
| 8086:8c26 | 15d9:0842 | Intel      | 8 Series/C220 Series Chip... | 3     | ehci       | 0C0FE552AA |
| 8086:8c2d | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 3     | ehci       | CF2E66B6AA |
| 8086:8c2d | 15d9:0842 | Intel      | 8 Series/C220 Series Chip... | 3     | ehci       | 0C0FE552AA |
| 8086:8c31 | 15d9:0801 | Intel      | 8 Series/C220 Series Chip... | 3     | xhci       | CF2E66B6AA |
| 8086:8c31 | 15d9:0842 | Intel      | 8 Series/C220 Series Chip... | 3     | xhci       | 0C0FE552AA |
| 8086:8d31 | 15d9:0832 | Intel      | C610/X99 series chipset U... | 3     | xhci       | F36F748797 |
| 8086:a12f | 1028:06aa | Intel      | 100 Series/C230 Series Ch... | 3     | xhci       | EFE3DBF989 |
| 8086:a1af | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     | xhci       | 55C1BD261F |
| 8086:a1af | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     | xhci       | 6460F775B0 |
| 8086:a36d | 15d9:1b0e | Intel      | Cannon Lake PCH USB 3.1 x... | 3     | xhci       | 70B8F97D6C |
| 1022:7908 | 1022:7908 | AMD        | FCH USB EHCI Controller      | 2     | ehci       | C42933F9FD |
| 1022:7914 | 1022:7914 | AMD        | FCH USB XHCI Controller      | 2     | xhci       | C42933F9FD |
| 103c:3300 | 103c:330e | Hewlett... | Integrated Lights-Out Sta... | 2     | uhci       | 1EBF1B71BD |
| 1166:0223 | 103c:320c | Broadcom   | BCM5785 [HT1000] USB         | 2     | ohci       | 8A7564245E |
| 1166:0223 | 103c:320d | Broadcom   | BCM5785 [HT1000] USB         | 2     | ehci       | 8A7564245E |
| 1912:0015 | 15d9:0805 | Renesas... | uPD720202 USB 3.0 Host Co... | 2     | xhci       | 2758B438C6 |
| 8086:1c26 | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 3881A96CEE |
| 8086:1c26 | 103c:330d | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 1EBF1B71BD |
| 8086:1c26 | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | EBCDA9A77F |
| 8086:1c2d | 1028:04de | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 3881A96CEE |
| 8086:1c2d | 103c:330d | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | 1EBF1B71BD |
| 8086:1c2d | 1734:11cb | Intel      | 6 Series/C200 Series Chip... | 2     | ehci       | EBCDA9A77F |
| 8086:1d26 | 1734:11b6 | Intel      | C600/X79 series chipset U... | 2     | ehci       | A9D034FE42 |
| 8086:1d2d | 1734:11b6 | Intel      | C600/X79 series chipset U... | 2     | ehci       | A9D034FE42 |
| 8086:2688 | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | F3854BA6E8 |
| 8086:2688 | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | 658BE87971 |
| 8086:2688 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | 411F470773 |
| 8086:2689 | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | F3854BA6E8 |
| 8086:2689 | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | 658BE87971 |
| 8086:2689 | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | 411F470773 |
| 8086:268a | 1028:01b2 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | F3854BA6E8 |
| 8086:268a | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | 658BE87971 |
| 8086:268a | 8086:3476 | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | 411F470773 |
| 8086:268b | 103c:31fe | Intel      | 631xESB/632xESB/3100 Chip... | 2     | uhci       | 658BE87971 |

### Others (PCI)

| ID        | Subsystem | MFG        | Name                         | Count | Driver     | Probe      |
|-----------|-----------|------------|------------------------------|-------|------------|------------|
| 8086:8d7c | 1028:0601 | Intel      | C610/X99 series chipset SPSR | 4     |            | 5ACC629D2E |
| 8086:8d7c | 103c:8030 | Intel      | C610/X99 series chipset SPSR | 4     |            | 533B1E078E |
| 8086:8d7c | 15d9:0832 | Intel      | C610/X99 series chipset SPSR | 3     |            | F36F748797 |
| 8086:a135 | 15d9:0884 | Intel      | 100 Series/C230 Series Ch... | 3     |            | 9D69197550 |
| 8086:a1ec | 1028:0716 | Intel      | C620 Series Chipset Famil... | 3     |            | 55C1BD261F |
| 8086:a1ec | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:a1ed | 1734:1230 | Intel      | C620 Series Chipset Famil... | 3     |            | 6460F775B0 |
| 8086:8d7c |           | Intel      | C610/X99 series chipset SPSR | 2     |            | 289D61B1B2 |
| 8086:8d7c | 15d9:0857 | Intel      | C610/X99 series chipset SPSR | 2     |            | 14A919AB3F |
| 8086:8d7c | 1734:1201 | Intel      | C610/X99 series chipset SPSR | 2     |            | 7A9D95B303 |
| 8086:a135 | 15d9:0886 | Intel      | 100 Series/C230 Series Ch... | 2     |            | B34EE32475 |
| 8086:a1ec | 1028:0737 | Intel      | C620 Series Chipset Famil... | 2     |            | B062E0F4E4 |
| 8086:a1ec | 1028:07ca | Intel      | C620 Series Chipset Famil... | 2     |            | 32F145EA04 |
| 8086:a1ec | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 8086:a1ed | 8086:7270 | Intel      | C620 Series Chipset Famil... | 2     |            | D088FBCF53 |
| 0000:0000 |           |            |                              | 1     |            | 79A07689EC |
| 1022:1455 | 1022:1455 | AMD        | Zeppelin/Renoir PCIe Dumm... | 1     |            | 4228478ECF |
| 1022:145a | 1022:145a | AMD        | Zeppelin/Raven/Raven2 PCI... | 1     |            | 4228478ECF |
| 1022:1485 | 1022:1485 | AMD        | Starship/Matisse Reserved... | 1     |            | 6C4D7ACEEC |
| 1022:1485 | 1458:1000 | AMD        | Starship/Matisse Reserved... | 1     |            | 93E2466FC6 |
| 1022:148a | 1022:148a | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 6C4D7ACEEC |
| 1022:148a | 1458:1000 | AMD        | Starship/Matisse PCIe Dum... | 1     |            | 93E2466FC6 |
| 1028:0011 | 1028:0011 | Dell       | Remote Access Card 4 Daug... | 1     |            | BB83934454 |
| 1028:0012 | 1028:0012 | Dell       | Remote Access Card 4 Daug... | 1     | uart       | BB83934454 |
| 1028:0014 | 1028:0014 | Dell       | Remote Access Card 4 Daug... | 1     |            | BB83934454 |
| 103c:193f | 103c:3381 | Hewlett... | Dynamic Smart Array B140i    | 1     |            | 533B1E078E |
| 8086:3591 | 1734:1041 | Intel      | E7525/E7520 Error Reporti... | 1     |            | ADB972BF8E |
| 8086:8d7c | 1028:0600 | Intel      | C610/X99 series chipset SPSR | 1     |            | 4389B1CE81 |
| 8086:8d7c | 1028:061a | Intel      | C610/X99 series chipset SPSR | 1     |            | FCD1A34E85 |
| 8086:8d7c | 1028:0627 | Intel      | C610/X99 series chipset SPSR | 1     |            | 4710D6000D |
| 8086:8d7c | 15d9:0821 | Intel      | C610/X99 series chipset SPSR | 1     |            | 3C7D64A2CB |
| 8086:8d7c | 15d9:0831 | Intel      | C610/X99 series chipset SPSR | 1     |            | 223968434F |
| 8086:8d7c | 15d9:0834 | Intel      | C610/X99 series chipset SPSR | 1     |            | 81DB3F5BE2 |
| 8086:8d7c | 1849:8d7c | Intel      | C610/X99 series chipset SPSR | 1     |            | 79A07689EC |
| 8086:8d7c | 8086:7270 | Intel      | C610/X99 series chipset SPSR | 1     |            | 93A8B87E1C |
| 8086:a135 | 15d9:0896 | Intel      | 100 Series/C230 Series Ch... | 1     |            | 5044047B6E |
| 8086:a1ec | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | CA41B3F700 |
| 8086:a1ec | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 91B07FA8B9 |
| 8086:a1ec | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | FFAA30BC08 |
| 8086:a1ed | 15d9:096e | Intel      | C620 Series Chipset Famil... | 1     |            | CA41B3F700 |
| 8086:a1ed | 15d9:0986 | Intel      | C620 Series Chipset Famil... | 1     |            | 91B07FA8B9 |
| 8086:a1ed | 17aa:1037 | Intel      | C620 Series Chipset Famil... | 1     |            | FFAA30BC08 |

