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
| 8086:0c01 | 8086:0c01 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 21    | pcib       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:8c10 | 8086:8c10 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | pcib       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:8c18 | 8086:8c18 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | pcib       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:8c12 | 8086:8c12 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | pcib       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:8c14 | 8086:8c14 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | pcib       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:8c16 | 8086:8c16 | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | pcib       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:8c1a | 8086:8c1a | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | pcib       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:0c00 | 8086:0c00 | Intel            | 4th Gen Core Processor DRAM Contr... | 18    | hostb      | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:1f13 | 8086:8086 | Intel            | Atom processor C2000 PCIe Root Po... | 18    | pcib       | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |
| 8086:1f14 |           | Intel            | Atom processor C2000 RAS             | 18    | hostb      | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 15    | pcib       | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |
| 8086:8c5c | 8086:8c5c | Intel            | H81 Express LPC Controller           | 13    | isab       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:1f10 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 12    | pcib       | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:1f11 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 12    | pcib       | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:1f12 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 12    | pcib       | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:1f38 | 8086:7270 | Intel            | Atom processor C2000 PCU             | 12    | isab       | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:1901 | 8086:2015 | Intel            | 6th-10th Gen Core Processor PCIe ... | 9     | pcib       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:1f0b |           | Intel            | Atom processor C2000 SoC Transact... | 9     | hostb      | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:5ad8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | pcib       | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:5ad9 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | pcib       | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:5ada |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | pcib       | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:5adb |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | pcib       | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | isab       | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | hostb      | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:a114 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | pcib       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:a115 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | pcib       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:a116 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | pcib       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:a117 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | pcib       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:a118 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | pcib       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:244e | 8086:244e | Intel            | 82801 PCI Bridge                     | 8     | pcib       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:8c1c | 8086:8c1c | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | pcib       | [666D1539EE](<Firewall/Sophos/XG/XG/91AE93A7F534/OPNSENSE-22.1/13.0-STABLE/AMD64/666D1539EE>) |
| 8086:1f0e |           | Intel            | Atom processor C2000 SoC Transact... | 7     | hostb      | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:8c1e | 8086:8c1e | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | pcib       | [666D1539EE](<Firewall/Sophos/XG/XG/91AE93A7F534/OPNSENSE-22.1/13.0-STABLE/AMD64/666D1539EE>) |
| 8086:8c4e | 8086:8c4e | Intel            | Q87 Express LPC Controller           | 7     | isab       | [666D1539EE](<Firewall/Sophos/XG/XG/91AE93A7F534/OPNSENSE-22.1/13.0-STABLE/AMD64/666D1539EE>) |
| 10b5:8604 | 10b5:8604 | PLX Technology   | PEX 8604 4-lane, 4-Port PCI Expre... | 6     | pcib       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:2448 | 8086:2448 | Intel            | 82801 Mobile PCI Bridge              | 6     | pcib       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:27b8 | 8086:27b8 | Intel            | 82801GB/GR (ICH7 Family) LPC Inte... | 6     | isab       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27d0 | 8086:27d0 | Intel            | NM10/ICH7 Family PCI Express Port 1  | 6     | pcib       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27d2 | 8086:27d2 | Intel            | NM10/ICH7 Family PCI Express Port 2  | 6     | pcib       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27d4 | 8086:27d4 | Intel            | NM10/ICH7 Family PCI Express Port 3  | 6     | pcib       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27d6 | 8086:27d6 | Intel            | NM10/ICH7 Family PCI Express Port 4  | 6     | pcib       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27e0 | 8086:27e0 | Intel            | 82801GR/GH/GHM (ICH7 Family) PCI ... | 6     | pcib       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27e2 | 8086:27e2 | Intel            | 82801GR/GH/GHM (ICH7 Family) PCI ... | 6     | pcib       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:2815 | 8086:2815 | Intel            | 82801HM (ICH8M) LPC Interface Con... | 6     | isab       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:283f | 8086:283f | Intel            | 82801H (ICH8 Family) PCI Express ... | 6     | pcib       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:2841 | 8086:2841 | Intel            | 82801H (ICH8 Family) PCI Express ... | 6     | pcib       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:2843 | 8086:2843 | Intel            | 82801H (ICH8 Family) PCI Express ... | 6     | pcib       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:2845 | 8086:2845 | Intel            | 82801H (ICH8 Family) PCI Express ... | 6     | pcib       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:2e30 | 8086:2e30 | Intel            | 4 Series Chipset DRAM Controller     | 6     | hostb      | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:a010 | 8086:a010 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 6     | hostb      | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 10b5:8605 | 10b5:8605 | PLX Technology   | PEX 8605 PCI Express 4-port Gen2 ... | 5     | pcib       | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 12d8:2404 |           | Pericom Semic... | PI7C9X2G404 EL/SL PCIe2 4-Port/4-... | 5     | pcib       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:191f | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 5     | hostb      | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:1f10 | 1462:1401 | Intel            | Atom processor C2000 PCIe Root Po... | 5     | pcib       | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:1f11 | 1462:1401 | Intel            | Atom processor C2000 PCIe Root Po... | 5     | pcib       | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:1f12 | 1462:1401 | Intel            | Atom processor C2000 PCIe Root Po... | 5     | pcib       | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:1f38 | 1462:1401 | Intel            | Atom processor C2000 PCU             | 5     | isab       | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:a119 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 5     | pcib       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:a143 | 8086:7270 | Intel            | H110 Chipset LPC/eSPI Controller     | 5     | isab       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:0c08 | 8086:0c08 | Intel            | Xeon E3-1200 v3 Processor DRAM Co... | 4     | hostb      | [335E21CBAF](<Firewall/Sophos/XG/XG/35124F675647/OPNSENSE-22.1/13.0-STABLE/AMD64/335E21CBAF>) |
| 8086:1905 | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 4     | pcib       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:190f | 8086:2015 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 4     | hostb      | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:1980 | 8086:1999 | Intel            | Atom Processor C3000 Series Syste... | 4     | hostb      | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19a1 |           | Intel            | Atom Processor C3000 Series Error... | 4     | hostb      | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19a3 |           | Intel            | Atom Processor C3000 Series Integ... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19a4 |           | Intel            | Atom Processor C3000 Series PCI E... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19a5 | 8086:19a5 | Intel            | Atom Processor C3000 Series PCI E... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19a6 | 8086:19a6 | Intel            | Atom Processor C3000 Series PCI E... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19a7 | 8086:19a7 | Intel            | Atom Processor C3000 Series PCI E... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19a8 | 8086:19a8 | Intel            | Atom Processor C3000 Series PCI E... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19a9 | 8086:19a9 | Intel            | Atom Processor C3000 Series PCI E... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19aa | 8086:19aa | Intel            | Atom Processor C3000 Series PCI E... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19ab | 8086:19ab | Intel            | Atom Processor C3000 Series PCI E... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19d1 |           | Intel            | Atom Processor C3000 Series Integ... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19d2 |           | Intel            | Atom Processor C3000 Series Integ... | 4     | pcib       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19dc | 8086:7270 | Intel            | Atom Processor C3000 Series LPC o... | 4     | isab       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:a110 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | pcib       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:a111 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | pcib       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:a112 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | pcib       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:a113 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | pcib       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:a11a | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | pcib       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:a11b | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | pcib       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:a11c | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | pcib       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:a146 | 8086:7270 | Intel            | Q170 Chipset LPC/eSPI Controller     | 4     | isab       | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 10b5:8616 | 10b5:8616 | PLX Technology   | PEX 8616 16-lane, 4-Port PCI Expr... | 3     | pcib       | [3C6601BF94](<Firewall/Sophos/SG/SG/DCFCE49A1589/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/3C6601BF94>) |
| 8086:0100 | 8086:0100 | Intel            | 2nd Generation Core Processor Fam... | 2     | hostb      | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:0101 | 8086:0101 | Intel            | Xeon E3-1200/2nd Generation Core ... | 2     | pcib       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:0105 | 8086:0105 | Intel            | Xeon E3-1200/2nd Generation Core ... | 2     | pcib       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:1c10 | 8086:1c10 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pcib       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:1c18 | 8086:1c18 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | pcib       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:1c56 | 8086:1c56 | Intel            | C206 Chipset LPC Controller          | 2     | isab       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:5ad6 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | pcib       | [BE5BC3FCB9](<Firewall/Sophos/XG/XG/DA8FF58CC73B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/BE5BC3FCB9>) |
| 10b5:8603 | 10b5:8603 | PLX Technology   | PEX 8603 3-lane, 3-Port PCI Expre... | 1     | pcib       | [3E1240D256](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F280b/FD4F56C6620A/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/3E1240D256>) |
| 10b5:8624 | 10b5:8624 | PLX Technology   | PEX 8624 24-lane, 6-Port PCI Expr... | 1     | pcib       | [EF2F5519D8](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/EF2F5519D8>) |
| 12d8:2304 |           | Pericom Semic... | PI7C9X2G304 EL/SL PCIe2 3-Port/4-... | 1     | pcib       | [084A4A00DE](<Firewall/Sophos/XG/XG/98212BC11D44/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/084A4A00DE>) |
| 1b21:1182 | 1b21:118f | ASMedia Techn... | ASM1182e 2-Port PCIe x1 Gen2 Pack... | 1     | pcib       | [9ED491D56A](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F180/AF2B6B5BDFD0/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/9ED491D56A>) |
| 8086:0c05 | 8086:0c05 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | pcib       | [88EA908224](<Firewall/Sophos/SG/SG/C680308560C6/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/88EA908224>) |
| 8086:0c09 | 8086:0c09 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | pcib       | [88EA908224](<Firewall/Sophos/SG/SG/C680308560C6/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/88EA908224>) |
| 8086:0f00 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | hostb      | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | isab       | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 17    |            | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:19e2 |           | Intel            | Atom Processor C3000 Series Quick... | 4     |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     |            | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:a13a | 8086:1999 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:5a9c | 8086:7270 | Intel            |                                      | 8     |            | [BE5BC3FCB9](<Firewall/Sophos/XG/XG/DA8FF58CC73B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/BE5BC3FCB9>) |
| 8086:5a9e | 8086:7270 | Intel            |                                      | 8     |            | [BE5BC3FCB9](<Firewall/Sophos/XG/XG/DA8FF58CC73B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/BE5BC3FCB9>) |
| 8086:19d3 | 8086:19d3 | Intel            | Atom Processor C3000 Series ME HE... | 4     |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 14    | vgapci     | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:0402 | 8086:0402 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 10    | vgapci     | [80702937FF](<Firewall/Sophos/SG/SG/298F8B128A1A/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/80702937FF>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 9     | vgapci     | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:0412 | 8086:0412 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 8     | vgapci     | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:1912 |           | Intel            | HD Graphics 530                      | 6     | vgapci     | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:2e32 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 6     | agp        | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:2e33 | 8086:2e32 | Intel            | 4 Series Chipset Integrated Graph... | 6     | vgapci     | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:a011 | 8086:a011 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 6     | agp        | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:a012 | 8086:a011 | Intel            | Atom Processor D4xx/D5xx/N4xx/N5x... | 6     | vgapci     | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:041a | 8086:041a | Intel            | Xeon E3-1200 v3 Processor Integra... | 3     | vgapci     | [335E21CBAF](<Firewall/Sophos/XG/XG/35124F675647/OPNSENSE-22.1/13.0-STABLE/AMD64/335E21CBAF>) |
| 8086:1902 |           | Intel            | HD Graphics 510                      | 3     | vgapci     | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:0102 | 8086:0102 | Intel            | 2nd Generation Core Processor Fam... | 2     | vgapci     | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 1a03:2000 | 1043:84eb | ASPEED Techno... | ASPEED Graphics Family               | 1     | vgapci     | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:19de | 8086:7270 | Intel            | Atom Processor C3000 Series Power... | 4     |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 25    | igb        | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:1533 | 15bb:30e0 | Intel            | I210 Gigabit Network Connection      | 20    | igb        | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:1536 |           | Intel            | I210 Gigabit Fiber Network Connec... | 13    | igb        | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:1522 |           | Intel            | I350 Gigabit Fiber Network Connec... | 9     | igb        | [666D1539EE](<Firewall/Sophos/XG/XG/91AE93A7F534/OPNSENSE-22.1/13.0-STABLE/AMD64/666D1539EE>) |
| 8086:1539 | 15bb:34e6 | Intel            | I211 Gigabit Network Connection      | 9     | igb        | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:1521 |           | Intel            | I350 Gigabit Network Connection      | 7     | igb        | [666D1539EE](<Firewall/Sophos/XG/XG/91AE93A7F534/OPNSENSE-22.1/13.0-STABLE/AMD64/666D1539EE>) |
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 6     | em         | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:10fb |           | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 4     | ix         | [0108191DEC](<Firewall/Sophos/XG/XG/86CD90ACBE23/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0108191DEC>) |
| 8086:15e5 |           | Intel            | Ethernet Connection X553 1GbE        | 4     | ix         | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:10c9 |           | Intel            | 82576 Gigabit Network Connection     | 2     | igb        | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:10e6 |           | Intel            | 82576 Gigabit Network Connection     | 2     | igb        | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:15e4 |           | Intel            | Ethernet Connection X553 1GbE        | 2     | ix         | [59485A80E1](<Firewall/Sophos/XG/XG/C4DFF7E3BAFC/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/59485A80E1>) |
| 8086:1f41 | 15bb:1f41 | Intel            | Ethernet Connection I354             | 2     | igb        | [68B230DF84](<Firewall/CheckPoint/PB-10/PB-10-00/22C5CECF7E1D/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/68B230DF84>) |
| 8086:10c6 | 1374:0203 | Intel            | 82598EB 10-Gigabit AF Dual Port N... | 1     | ix         | [C6D1DB88BF](<Firewall/Sophos/SG/SG/822D9E620119/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/C6D1DB88BF>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 1     | ix         | [EF2F5519D8](<Firewall/Sophos/SG/SG/938D53E00DCC/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/EF2F5519D8>) |
| 8086:150e | 15bb:2002 | Intel            | 82580 Gigabit Network Connection     | 1     | igb        | [335E21CBAF](<Firewall/Sophos/XG/XG/35124F675647/OPNSENSE-22.1/13.0-STABLE/AMD64/335E21CBAF>) |
| 8086:1521 | 15bb:0008 | Intel            | I350 Gigabit Network Connection      | 1     | igb        | [88EA908224](<Firewall/Sophos/SG/SG/C680308560C6/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/88EA908224>) |
| 8086:1539 | 10f3:0101 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [6324A2A9A9](<Firewall/Sophos/XG/XG/EDE223463E7F/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/6324A2A9A9>) |
| 8086:1f41 | 1043:8638 | Intel            | Ethernet Connection I354             | 1     | igb        | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 168c:0030 | 168c:3116 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 3     | ath        | [9ED491D56A](<Firewall/Barracuda Networks/Barracuda/Barracuda NG Firewall F180/AF2B6B5BDFD0/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/9ED491D56A>) |
| 10ec:8178 | 10ec:8189 | Realtek Semic... | RTL8192CE PCIe Wireless Network A... | 2     |            | [AC861C4550](<Firewall/Others/Others/Others/5129D737B158/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/AC861C4550>) |
| 168c:003c |           | Qualcomm Atheros | QCA986x/988x 802.11ac Wireless Ne... | 2     |            | [96C65BE177](<Firewall/Sophos/XG/XG/5CABD49F0ECE/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/96C65BE177>) |
| 10ec:8176 | 10ec:8181 | Realtek Semic... | RTL8188CE 802.11b/g/n WiFi Adapter   | 1     |            | [FB003E1617](<Firewall/Lanner/Others/Others/3D71DCC655DC/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/FB003E1617>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 29    | igb        | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:1f41 | 8086:1f41 | Intel            | Ethernet Connection I354             | 15    | igb        | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 6     | em         | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2     | re         | [BE5BC3FCB9](<Firewall/Sophos/XG/XG/DA8FF58CC73B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/BE5BC3FCB9>) |
| 8086:1531 |           | Intel            | I210 Gigabit Unprogrammed            | 1     |            | [3131AAE37B](<Firewall/Sophos/SG/SG/3E6356D8BD10/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/3131AAE37B>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | sdhci_pci  | [BE5BC3FCB9](<Firewall/Sophos/XG/XG/DA8FF58CC73B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/BE5BC3FCB9>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 7     |            | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:19e0 | 8086:7270 | Intel            | Atom Processor C3000 Series SPI C... | 4     |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:a131 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | ichsmb     | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 12    | ichsmb     | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     |            | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     |            | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:27da | 8086:27da | Intel            | NM10/ICH7 Family SMBus Controller    | 6     | ichsmb     | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:283e | 8086:283e | Intel            | 82801H (ICH8 Family) SMBus Contro... | 6     | ichsmb     | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:1f3c | 1462:1401 | Intel            | Atom processor C2000 PCU SMBus       | 5     | ichsmb     | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:19df | 8086:7270 | Intel            | Atom Processor C3000 Series SMBus... | 4     | ichsmb     | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:1c22 | 8086:1c22 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     |            | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 1     |            | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:1f3c | 1043:8646 | Intel            | Atom processor C2000 PCU SMBus       | 1     | ichsmb     | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0c0c | 8086:0c0c | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 19    | hdac       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:a170 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | hdac       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | hdac       | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:284b | 8086:284b | Intel            | 82801H (ICH8 Family) HD Audio Con... | 1     | hdac       | [A7AF4807B0](<Firewall/Sophos/UTM/UTM/93BFB06184EC/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/A7AF4807B0>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | ahci       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 12    | ahci       | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | ahci       | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:a102 | 8086:7270 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 9     | ahci       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:27c1 | 8086:27c0 | Intel            | NM10/ICH7 Family SATA Controller ... | 6     | ahci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:2829 | 8086:2829 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) SATA ... | 6     | ahci       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:1f22 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA2 C... | 5     | ahci       | [AC861C4550](<Firewall/Others/Others/Others/5129D737B158/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/AC861C4550>) |
| 8086:1f32 | 1462:1401 | Intel            | Atom processor C2000 AHCI SATA3 C... | 5     | ahci       | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:19b2 | 8086:7270 | Intel            | Atom Processor C3000 Series SATA ... | 4     | ahci       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:1c02 | 8086:1c02 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ahci       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ahci       | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:1f32 | 1043:8646 | Intel            | Atom processor C2000 AHCI SATA3 C... | 1     | ahci       | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2850 | 8086:2850 | Intel            | 82801HM/HEM (ICH8M/ICH8M-E) IDE C... | 6     | atapci     | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:27df | 8086:27df | Intel            | 82801G (ICH7 Family) IDE Controller  | 5     | atapci     | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f15 |           | Intel            | Atom processor C2000 SMBus 2.0       | 18    |            | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |
| 8086:1f16 |           | Intel            | Atom processor C2000 RCEC            | 18    |            | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |
| 8086:19a2 |           | Intel            | Atom Processor C3000 Series Root ... | 4     |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:19ac |           | Intel            | Atom Processor C3000 Series SMBus... | 4     |            | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c26 | 8086:8c26 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | ehci       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:8c2d | 8086:8c2d | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | ehci       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:8c31 | 8086:8c31 | Intel            | 8 Series/C220 Series Chipset Fami... | 21    | xhci       | [70D42D9A3A](<Firewall/Sophos/SG/SG/CF3530F1EDC6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/70D42D9A3A>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 12    | ehci       | [52B212DF0E](<Firewall/Sophos/SG/SG/6D67E9999ACD/OPNSENSE-22.1.1/13.0-STABLE/AMD64/52B212DF0E>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | xhci       | [C5CDB64FD0](<Firewall/Sophos/XG/XG/4E72527C8D00/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C5CDB64FD0>) |
| 8086:a12f | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 9     | xhci       | [35F890B945](<Firewall/Sophos/XG/XG/3B6B0D432816/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/35F890B945>) |
| 8086:27c8 | 8086:27c8 | Intel            | NM10/ICH7 Family USB UHCI Control... | 6     | uhci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27c9 | 8086:27c9 | Intel            | NM10/ICH7 Family USB UHCI Control... | 6     | uhci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27ca | 8086:27ca | Intel            | NM10/ICH7 Family USB UHCI Control... | 6     | uhci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27cb | 8086:27cb | Intel            | NM10/ICH7 Family USB UHCI Control... | 6     | uhci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:27cc | 8086:27cc | Intel            | NM10/ICH7 Family USB2 EHCI Contro... | 6     | ehci       | [49C7A56907](<Firewall/Sophos/UTM/UTM/9A78F7D13F17/OPNSENSE-22.1.1/13.0-STABLE/AMD64/49C7A56907>) |
| 8086:2830 | 8086:2830 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 6     | uhci       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:2831 | 8086:2831 | Intel            | 82801H (ICH8 Family) USB UHCI Con... | 6     | uhci       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:2836 | 8086:2836 | Intel            | 82801H (ICH8 Family) USB2 EHCI Co... | 6     | ehci       | [03A19078C1](<Firewall/Sophos/UTM/UTM/9053032F18B2/OPNSENSE-22.1/13.0-STABLE/AMD64/03A19078C1>) |
| 8086:1f2c | 1462:1401 | Intel            | Atom processor C2000 USB Enhanced... | 5     | ehci       | [9097F70CC6](<Firewall/Barracuda Networks/Barracuda/Barracuda Firewall X50/D51DE416B663/OPNSENSE-22.1.2/13.0-STABLE/AMD64/9097F70CC6>) |
| 8086:19d0 | 8086:7270 | Intel            | Atom Processor C3000 Series USB 3... | 4     | xhci       | [44C92BAFFD](<Firewall/Sophos/XG/XG/2BF8A0B49C5F/OPNSENSE-22.1.1/13.0-STABLE/AMD64/44C92BAFFD>) |
| 8086:1c26 | 8086:1c26 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ehci       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:1c2d | 8086:1c2d | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ehci       | [F922A987E6](<Firewall/Sophos/UTM/UTM/9E7A4E2F0627/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F922A987E6>) |
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 1     | xhci       | [6F058F9A0C](<Firewall/Silver Peak Systems/Network/Network Appliance Platform/D40883DD1E15/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/6F058F9A0C>) |
| 8086:1f2c | 1043:8646 | Intel            | Atom processor C2000 USB Enhanced... | 1     | ehci       | [E2D107E38A](<Firewall/Thomas-Krenn.AG/P9/P9A-I-C2750-4L/7EE03EDB819C/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E2D107E38A>) |

