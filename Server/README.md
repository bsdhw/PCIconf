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
   * [ Infiniband ](#infiniband-pci)
   * [ Memory controller ](#memory-controller-pci)
   * [ Net/ethernet ](#netethernet-pci)
   * [ Net/wireless ](#netwireless-pci)
   * [ Network ](#network-pci)
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
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1912:0012 | 1912:0012 | Renesas Techn... | SH7757 PCIe-PCI Bridge [PPB]         | 72    | pcib       | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 1912:0013 | 1912:0013 | Renesas Techn... | SH7757 PCIe Switch [PS]              | 72    | pcib       | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 53    | pcib       | [638B27BC34](<Server/Supermicro/Super/Super Server/CF1692AC0104/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638B27BC34>) |
| 8086:1c10 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 42    | pcib       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:1c52 | 1028:04dd | Intel            | C202 Chipset LPC Controller          | 42    | isab       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:244e | 1028:04dd | Intel            | 82801 PCI Bridge                     | 42    | pcib       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:2030 |           | Intel            | Sky Lake-E PCI Express Root Port A   | 32    | pcib       | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 111d:8018 |           | Microsemi / P... | PES12N3A 12-lane 3-Port PCI Expre... | 30    | pcib       | [A12907D76A](<Server/Dell/PowerEdge/PowerEdge R200/4AC27B58A736/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A12907D76A>) |
| 8086:3419 |           | Intel            | 7500/5520/5500 Physical Layer Port 1 | 30    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:341a |           | Intel            | 7500/5520/5500/X58 Unknown           | 30    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:341c |           | Intel            | 7500/5520/5500/X58 Unknown           | 30    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:341e |           | Intel            | 7500/5520/5500/X58 Unknown           | 30    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:3439 |           | Intel            | 7500/5520/5500/X58 Unknown           | 30    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:343d |           | Intel            | 7500/5520/5500/X58 Unknown           | 30    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 1556:be00 |           | PLDA             | PCI Express Bridge                   | 29    | pcib       | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2032 |           | Intel            | Sky Lake-E PCI Express Root Port C   | 28    | pcib       | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:244e | 103c:330d | Intel            | 82801 PCI Bridge                     | 27    | pcib       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:25e3 |           | Intel            | 5000 Series Chipset PCI Express x... | 27    | pcib       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:3406 | 103c:330b | Intel            | 5520 I/O Hub to ESI Port             | 27    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:343a |           | Intel            | 7500/5520/5500/X58 Unknown           | 27    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:25e5 |           | Intel            | 5000 Series Chipset PCI Express x... | 26    | pcib       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:25e7 |           | Intel            | 5000 Series Chipset PCI Express x... | 26    | pcib       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:340a | 103c:330b | Intel            | 5520/5500/X58 I/O Hub PCI Express... | 26    | pcib       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:340e | 103c:330b | Intel            | 5520/5500/X58 I/O Hub PCI Express... | 26    | pcib       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:3410 | 103c:330b | Intel            | 7500/5520/5500/X58 I/O Hub PCI Ex... | 26    | pcib       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 1166:0103 |           | Broadcom         | EPB PCI-Express to PCI-X Bridge      | 25    | pcib       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 1912:001a | 1912:001a | Renesas Techn... | SH7758 PCIe-PCI Bridge [PPB]         | 25    | pcib       | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 1912:001d | 1912:001d | Renesas Techn... | SH7758 PCIe Switch [PS]              | 25    | pcib       | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 1a03:1150 | 15d9:0921 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:3411 | 103c:330b | Intel            | 7500/5520/5500/X58 I/O Hub PCI Ex... | 25    | pcib       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:341f |           | Intel            | 7500/5520/5500/X58 Unknown           | 25    | hostb      | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:6f00 | 15d9:0921 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 25    | hostb      | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f02 | 15d9:0921 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f03 | 15d9:0921 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f04 | 15d9:0921 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f06 | 15d9:0921 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f08 | 15d9:0921 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f0a | 15d9:0921 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c10 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c12 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c16 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c54 | 15d9:0921 | Intel            | C224 Series Chipset Family Server... | 25    | isab       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:0108 | 1028:04dd | Intel            | Xeon E3-1200 Processor Family DRA... | 24    | hostb      | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:25f8 |           | Intel            | 5000 Series Chipset PCI Express x... | 24    | pcib       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:8c18 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 24    | pcib       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:2020 |           | Intel            | Sky Lake-E DMI3 Registers            | 23    | hostb      | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:340c | 103c:330b | Intel            | 5520/X58 I/O Hub PCI Express Root... | 23    | pcib       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:340d | 103c:330b | Intel            | 5520/X58 I/O Hub PCI Express Root... | 23    | pcib       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:3a18 |           | Intel            | 82801JIB (ICH10) LPC Interface Co... | 23    | isab       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:25e2 |           | Intel            | 5000 Series Chipset PCI Express x... | 21    | pcib       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:19e2 |           | Intel            | Atom Processor C3000 Series Quick... | 16    | qat        | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 19a2:0800 | 1734:11cc | Emulex           | ServerView iRMC HTI                  | 5     |            | [9E972FD1A1](<Server/Fujitsu/PRIMERGY/PRIMERGY TX1320 M2/0C5BD48E99F3/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/9E972FD1A1>) |
| 1734:1228 | 1734:1256 | Fujitsu Techn... |                                      | 3     |            | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 8086:1f18 | 15d9:0820 | Intel            | Atom processor C2000 QAT             | 3     | qat        | [FB96378782](<Server/Supermicro/A1/A1SRM-2758F/F38A17AAB757/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FB96378782>) |
| 1734:1228 | 1734:1229 | Fujitsu Techn... |                                      | 1     |            | [6E6F1B0F99](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M4/BA1E3C5B14F6/HARDENEDBSD-12.2--HBSD/12.2-STABLE-HBSD/AMD64/6E6F1B0F99>) |
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 1     |            | [640B454366](<Server/Advantech/FWA/FWA-2320/FB850ABD5985/OPNSENSE-21.7/12.1-RELEASE-P16-HBSD/AMD64/640B454366>) |
| 8086:37c8 | 8086:0001 | Intel            | C62x Chipset QuickAssist Technology  | 1     | qat        | [638B27BC34](<Server/Supermicro/Super/Super Server/CF1692AC0104/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638B27BC34>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8c3a | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c3b | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c3a | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 20    |            | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c3b | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 20    |            | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c3a | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 19    |            | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:8c3b | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 19    |            | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:19d3 | 15d9:0969 | Intel            | Atom Processor C3000 Series ME HE... | 18    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:1d3a | 1028:0528 | Intel            | C600/X79 series chipset MEI Contr... | 17    |            | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:1d3b | 1028:0528 | Intel            | C600/X79 series chipset MEI Contr... | 17    |            | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:8d3a | 1028:0601 | Intel            | C610/X99 series chipset MEI Contr... | 11    |            | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:8d3b | 1028:0601 | Intel            | C610/X99 series chipset MEI Contr... | 11    |            | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:1d3a | 1028:04f8 | Intel            | C600/X79 series chipset MEI Contr... | 10    |            | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:1d3b | 1028:04f8 | Intel            | C600/X79 series chipset MEI Contr... | 10    |            | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:a13a | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 8086:a13b | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 8086:1d3a | 1028:04ce | Intel            | C600/X79 series chipset MEI Contr... | 9     |            | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 8086:1d3b | 1028:04ce | Intel            | C600/X79 series chipset MEI Contr... | 9     |            | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 8086:1d3a | 1028:04f7 | Intel            | C600/X79 series chipset MEI Contr... | 8     |            | [A1A15662D0](<Server/Dell/PowerEdge/PowerEdge R320/0A57FAA417FF/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/A1A15662D0>) |
| 8086:1d3b | 1028:04f7 | Intel            | C600/X79 series chipset MEI Contr... | 8     |            | [A1A15662D0](<Server/Dell/PowerEdge/PowerEdge R320/0A57FAA417FF/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/A1A15662D0>) |
| 8086:8c3a | 15d9:0803 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     |            | [6F95477DF3](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/6F95477DF3>) |
| 8086:8c3b | 15d9:0803 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     |            | [6F95477DF3](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/6F95477DF3>) |
| 8086:a328 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO UART Ho... | 8     |            | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:a360 | 15d9:1b0e | Intel            | Cannon Lake PCH HECI Controller      | 8     |            | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:a364 | 15d9:1b0e | Intel            | Cannon Lake PCH HECI Controller #2   | 8     |            | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:1d3a | 1028:048c | Intel            | C600/X79 series chipset MEI Contr... | 7     |            | [B74220AEE1](<Server/Dell/PowerEdge/PowerEdge R720/886063A9496D/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/B74220AEE1>) |
| 8086:1d3b | 1028:048c | Intel            | C600/X79 series chipset MEI Contr... | 7     |            | [B74220AEE1](<Server/Dell/PowerEdge/PowerEdge R720/886063A9496D/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/B74220AEE1>) |
| 8086:a1ba | 1028:07c9 | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1ba | 15d9:0986 | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 8086:a1bb | 1028:07c9 | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1bb | 15d9:0986 | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 8086:a1be | 1028:07c9 | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1be | 15d9:0986 | Intel            | C620 Series Chipset Family MEI Co... | 7     |            | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 8086:1d3a | 15d9:0660 | Intel            | C600/X79 series chipset MEI Contr... | 6     |            | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 8086:1d3b | 15d9:0660 | Intel            | C600/X79 series chipset MEI Contr... | 6     |            | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 8086:8d3a | 8086:7270 | Intel            | C610/X99 series chipset MEI Contr... | 6     |            | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 8086:8d3b | 8086:7270 | Intel            | C610/X99 series chipset MEI Contr... | 6     |            | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 8086:8d3a | 15d9:0834 | Intel            | C610/X99 series chipset MEI Contr... | 5     |            | [59FF2014E5](<Server/Supermicro/Super/Super Server/C53FD6545133/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/59FF2014E5>) |
| 8086:8d3b | 15d9:0834 | Intel            | C610/X99 series chipset MEI Contr... | 5     |            | [59FF2014E5](<Server/Supermicro/Super/Super Server/C53FD6545133/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/59FF2014E5>) |
| 8086:a328 | 1028:088f | Intel            | Cannon Lake PCH Serial IO UART Ho... | 5     |            | [545DACB881](<Server/Dell/PowerEdge/PowerEdge R240/19A6101614C9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/545DACB881>) |
| 8086:a360 | 1028:088f | Intel            | Cannon Lake PCH HECI Controller      | 5     |            | [545DACB881](<Server/Dell/PowerEdge/PowerEdge R240/19A6101614C9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/545DACB881>) |
| 8086:a364 | 1028:088f | Intel            | Cannon Lake PCH HECI Controller #2   | 5     |            | [545DACB881](<Server/Dell/PowerEdge/PowerEdge R240/19A6101614C9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/545DACB881>) |
| 8086:8c3a | 15d9:0806 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     |            | [319819F81D](<Server/Supermicro/X10/X10SLM+-LN4F/9396CB95C705/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/319819F81D>) |
| 8086:8c3b | 15d9:0806 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     |            | [319819F81D](<Server/Supermicro/X10/X10SLM+-LN4F/9396CB95C705/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/319819F81D>) |
| 8086:8d3a | 15d9:0832 | Intel            | C610/X99 series chipset MEI Contr... | 4     |            | [1499A2903D](<Server/Supermicro/Super/Super Server/7E6D506E6800/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1499A2903D>) |
| 8086:8d3b | 15d9:0832 | Intel            | C610/X99 series chipset MEI Contr... | 4     |            | [1499A2903D](<Server/Supermicro/Super/Super Server/7E6D506E6800/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1499A2903D>) |
| 8086:a13a | 103c:8165 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [32E9F95095](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/013B4CDFD8CC/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/32E9F95095>) |
| 8086:a1ba | 1028:0716 | Intel            | C620 Series Chipset Family MEI Co... | 4     |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:a1bb | 1028:0716 | Intel            | C620 Series Chipset Family MEI Co... | 4     |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:a1be | 1028:0716 | Intel            | C620 Series Chipset Family MEI Co... | 4     |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:8c3a | 17aa:30b0 | Intel            | 8 Series/C220 Series Chipset Fami... | 3     |            | [D6111B8FF1](<Server/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/C9B365EFBC6F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D6111B8FF1>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2298 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     |            | [649D525FDB](<Server/Supermicro/Super/Super Server/A4D89EA96DC4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/649D525FDB>) |
| 1022:1456 | 1022:1456 | AMD              | Family 17h (Models 00h-0fh) Platf... | 6     |            | [76519F54E9](<Server/Supermicro/Super/Super Server/B6CF39D94613/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/76519F54E9>) |
| 1022:1468 | 1022:1468 | AMD              | Zeppelin Cryptographic Coprocesso... | 6     |            | [76519F54E9](<Server/Supermicro/Super/Super Server/B6CF39D94613/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/76519F54E9>) |
| 1022:1498 | 1022:1498 | AMD              | Starship/Matisse PTDMA               | 4     |            | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |
| 1022:1578 | 1022:1578 | AMD              | Carrizo Platform Security Processor  | 4     |            | [57721BF0F2](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/734A66ADD4EA/OPNSENSE-22.1/13.0-STABLE/AMD64/57721BF0F2>) |
| 1022:1486 | 1022:1486 | AMD              | Starship/Matisse Cryptographic Co... | 3     |            | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |
| 8086:0f18 | 15d9:0816 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 3     |            | [5A733D841D](<Server/XQAND/X10/X10SBA-L/C31CA5CEBF82/OPNSENSE-22.7/13.1-RELEASE/AMD64/5A733D841D>) |
| 1022:1486 | 1458:1000 | AMD              | Starship/Matisse Cryptographic Co... | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1022:1498 | 1458:1000 | AMD              | Starship/Matisse PTDMA               | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1022:1456 | 1028:07f7 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [DE85A76391](<Server/Dell/PowerEdge/PowerEdge R7415/A26D4916788B/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/DE85A76391>) |
| 1022:1456 | 1028:07f9 | AMD              | Family 17h (Models 00h-0fh) Platf... | 1     |            | [C34D5C2BE3](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C34D5C2BE3>) |
| 1022:1468 | 1028:07f7 | AMD              | Zeppelin Cryptographic Coprocesso... | 1     |            | [DE85A76391](<Server/Dell/PowerEdge/PowerEdge R7415/A26D4916788B/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/DE85A76391>) |
| 1022:1468 | 1028:07f9 | AMD              | Zeppelin Cryptographic Coprocesso... | 1     |            | [C34D5C2BE3](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C34D5C2BE3>) |
| 1022:1486 | 1028:08fd | AMD              | Starship/Matisse Cryptographic Co... | 1     |            | [D778079C7F](<Server/Dell/PowerEdge/PowerEdge R7515/23F1145279FD/HARDENEDBSD-13.0-STABLE-HBSD/13.0-STABLE-HBSD/AMD64/D778079C7F>) |
| 1022:1498 | 1028:08fd | AMD              | Starship/Matisse PTDMA               | 1     |            | [D778079C7F](<Server/Dell/PowerEdge/PowerEdge R7515/23F1145279FD/HARDENEDBSD-13.0-STABLE-HBSD/13.0-STABLE-HBSD/AMD64/D778079C7F>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 104c:8023 | 15d9:0805 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 2     |            | [2758B438C6](<Server/Supermicro/X10/X10SAE/4A17C592FC65/TRUENAS-12.2-P2/12.2-RELEASE-P2/AMD64/2758B438C6>) |
| 104c:8023 | 108e:6676 | Texas Instrum... | TSB43AB22A IEEE-1394a-2000 Contro... | 1     |            | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 102b:0532 | 1028:04dd | Matrox Electr... | MGA G200eW WPCM450                   | 42    | vgapci     | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 1002:515e | 103c:31fb | AMD              | ES1000                               | 36    | vgapci     | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 102b:0533 | 103c:3381 | Matrox Electr... | MGA G200EH                           | 31    | vgapci     | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 1a03:2000 | 15d9:0921 | ASPEED Techno... | ASPEED Graphics Family               | 25    | vgapci     | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 1a03:2000 | 15d9:086d | ASPEED Techno... | ASPEED Graphics Family               | 20    | vgapci     | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 1a03:2000 | 15d9:0842 | ASPEED Techno... | ASPEED Graphics Family               | 19    | vgapci     | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 102b:0532 | 1028:0235 | Matrox Electr... | MGA G200eW WPCM450                   | 18    | vgapci     | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 1a03:2000 | 15d9:0969 | ASPEED Techno... | ASPEED Graphics Family               | 18    | vgapci     | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 102b:0532 | 1028:0236 | Matrox Electr... | MGA G200eW WPCM450                   | 17    | vgapci     | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 102b:0534 | 1028:0528 | Matrox Electr... | G200eR2                              | 17    | vgapci     | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 102b:0534 | 1028:05e5 | Matrox Electr... | G200eR2                              | 15    | vgapci     | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 102b:0536 |           | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 12    | vgapci     | [C5AF7BF9E5](<Server/Dell/PowerEdge/PowerEdge R340/3C18F7464176/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C5AF7BF9E5>) |
| 102b:0534 | 1028:0601 | Matrox Electr... | G200eR2                              | 11    | vgapci     | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 1a03:2000 | 15d9:0801 | ASPEED Techno... | ASPEED Graphics Family               | 11    | vgapci     | [7D80C62813](<Server/Supermicro/X10/X10SLL-F/A4ACF508F8E6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7D80C62813>) |
| 102b:0522 | 1734:11cc | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 10    | vgapci     | [9E972FD1A1](<Server/Fujitsu/PRIMERGY/PRIMERGY TX1320 M2/0C5BD48E99F3/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/9E972FD1A1>) |
| 102b:0534 | 1028:04f8 | Matrox Electr... | G200eR2                              | 10    | vgapci     | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 1a03:2000 | 15d9:0884 | ASPEED Techno... | ASPEED Graphics Family               | 10    | vgapci     | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 102b:0530 | 1014:0369 | Matrox Electr... | MGA G200EV                           | 9     | vgapci     | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 102b:0532 | 1028:02a5 | Matrox Electr... | MGA G200eW WPCM450                   | 9     | vgapci     | [340DC7255C](<Server/Dell/PowerEdge/PowerEdge R210/5E68DB36191B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/340DC7255C>) |
| 102b:0534 | 1028:04ce | Matrox Electr... | G200eR2                              | 9     | vgapci     | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 8086:22b1 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | vgapci     | [649D525FDB](<Server/Supermicro/Super/Super Server/A4D89EA96DC4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/649D525FDB>) |
| 102b:0534 | 1028:04f7 | Matrox Electr... | G200eR2                              | 8     | vgapci     | [A1A15662D0](<Server/Dell/PowerEdge/PowerEdge R320/0A57FAA417FF/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/A1A15662D0>) |
| 1a03:2000 | 15d9:0803 | ASPEED Techno... | ASPEED Graphics Family               | 8     | vgapci     | [10CA365B40](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/10CA365B40>) |
| 1a03:2000 | 15d9:0891 | ASPEED Techno... | ASPEED Graphics Family               | 8     | vgapci     | [649D525FDB](<Server/Supermicro/Super/Super Server/A4D89EA96DC4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/649D525FDB>) |
| 1a03:2000 | 15d9:1b0e | ASPEED Techno... | ASPEED Graphics Family               | 8     | vgapci     | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 102b:0522 | 8086:0101 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 7     | vgapci     | [C614A1E46F](<Server/Intel/S3420/S3420GP/3AA435A1E08F/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C614A1E46F>) |
| 102b:0532 | 1028:028c | Matrox Electr... | MGA G200eW WPCM450                   | 7     | vgapci     | [33AED2A5C1](<Server/Dell/PowerEdge/PowerEdge R410/74D50A975822/OPNSENSE-22.7/13.1-RELEASE/AMD64/33AED2A5C1>) |
| 102b:0534 | 1028:048c | Matrox Electr... | G200eR2                              | 7     | vgapci     | [B74220AEE1](<Server/Dell/PowerEdge/PowerEdge R720/886063A9496D/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/B74220AEE1>) |
| 102b:0536 | 1028:07c9 | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 7     | vgapci     | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 1a03:2000 | 15d9:0986 | ASPEED Techno... | ASPEED Graphics Family               | 7     | vgapci     | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 102b:0522 | 1137:0101 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 6     | vgapci     | [2633EAF68B](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M5SX/41B605A42DA4/OPNSENSE-22.10/13.1-RELEASE-P2/AMD64/2633EAF68B>) |
| 102b:0522 | 8086:0103 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 6     | vgapci     | [4763FE7595](<Server/Intel/S1200/S1200RP_SE/4DF73AF97478/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/4763FE7595>) |
| 102b:0532 | 15d9:0660 | Matrox Electr... | MGA G200eW WPCM450                   | 6     | vgapci     | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 1a03:2000 | 15d9:1b2d | ASPEED Techno... | ASPEED Graphics Family               | 6     | vgapci     | [76519F54E9](<Server/Supermicro/Super/Super Server/B6CF39D94613/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/76519F54E9>) |
| 1a03:2000 | 1a03:2000 | ASPEED Techno... | ASPEED Graphics Family               | 6     | vgapci     | [BD71D84CF2](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/D0E7C21FF9A1/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/BD71D84CF2>) |
| 1002:515e | 1014:0305 | AMD              | ES1000                               | 5     | vgapci     | [41D40D8752](<Server/IBM/System/System x3650 -[797941Y]-/B6A5CBBF3013/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/41D40D8752>) |
| 102b:0532 | 1028:04de | Matrox Electr... | MGA G200eW WPCM450                   | 5     | vgapci     | [4D371914ED](<Server/Dell/PowerEdge/PowerEdge T110 II/1BB4A8B14EA4/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/4D371914ED>) |
| 102b:0538 | 1590:00e4 | Matrox Electr... | MGA G200eH3                          | 5     | vgapci     | [3A932D738C](<Server/HPE/ProLiant/ProLiant ML110 Gen10/819B1E7CD686/OPNSENSE-22.1.6/13.0-STABLE/AMD64/3A932D738C>) |
| 1a03:2000 | 15d9:0834 | ASPEED Techno... | ASPEED Graphics Family               | 5     | vgapci     | [59FF2014E5](<Server/Supermicro/Super/Super Server/C53FD6545133/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/59FF2014E5>) |
| 1002:515e | 1028:01b2 | AMD              | ES1000                               | 4     | vgapci     | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 1002:515e | 1028:023c | AMD              | ES1000                               | 4     | vgapci     | [A12907D76A](<Server/Dell/PowerEdge/PowerEdge R200/4AC27B58A736/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A12907D76A>) |
| 1002:9874 | 1002:1871 | AMD              | Wani [Radeon R5/R6/R7 Graphics]      | 4     | vgapci     | [57721BF0F2](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/734A66ADD4EA/OPNSENSE-22.1/13.0-STABLE/AMD64/57721BF0F2>) |
| 102b:0522 | 1734:1229 | Matrox Electr... | MGA G200e [Pilot] ServerEngines (... | 4     | vgapci     | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 102b:0532 | 1028:02a6 | Matrox Electr... | MGA G200eW WPCM450                   | 4     | vgapci     | [C63D853ABC](<Server/Dell/PowerEdge/PowerEdge T110/ECD9FAFE3AEB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C63D853ABC>) |
| 102b:0534 | 1014:0405 | Matrox Electr... | G200eR2                              | 4     | vgapci     | [7F8395E815](<Server/IBM/System/System x3250 M5: -[5458Z1P]-/EABBAC4B4C68/OPNSENSE-22.1.7/13.0-STABLE/AMD64/7F8395E815>) |
| 102b:0536 | 1028:0716 | Matrox Electr... | Integrated Matrox G200eW3 Graphic... | 4     | vgapci     | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 1a03:2000 | 1043:8373 | ASPEED Techno... | ASPEED Graphics Family               | 4     | vgapci     | [1347F15B56](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/36C252462A40/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/1347F15B56>) |
| 1a03:2000 | 108e:4843 | ASPEED Techno... | ASPEED Graphics Family               | 4     | vgapci     | [51E87104A0](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/51E87104A0>) |
| 1a03:2000 | 15d9:0806 | ASPEED Techno... | ASPEED Graphics Family               | 4     | vgapci     | [319819F81D](<Server/Supermicro/X10/X10SLM+-LN4F/9396CB95C705/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/319819F81D>) |
| 1a03:2000 | 15d9:0820 | ASPEED Techno... | ASPEED Graphics Family               | 4     | vgapci     | [FB96378782](<Server/Supermicro/A1/A1SRM-2758F/F38A17AAB757/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FB96378782>) |

### Infiniband (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 15b3:1003 | 15b3:0090 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 1     | mlx4_core  | [430341D742](<Server/Supermicro/Super/Super Server/E8E99CD65247/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/430341D742>) |
| 15b3:673c | 15b3:673c | Mellanox Tech... | MT25408A0-FCC-QI ConnectX, Dual P... | 1     |            | [9EEBD2154D](<Server/Dell/PowerEdge/PowerEdge R420/36AA4C03BAD4/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9EEBD2154D>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:19de | 15d9:0969 | Intel            | Atom Processor C3000 Series Power... | 18    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 1912:0011 |           | Renesas Techn... | SH7757 PCIe End-Point [PBI]          | 15    |            | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 15    |            | [638B27BC34](<Server/Supermicro/Super/Super Server/CF1692AC0104/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638B27BC34>) |
| 8086:a121 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    |            | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 8086:a36f |           | Intel            | Cannon Lake PCH Shared SRAM          | 10    |            | [C5AF7BF9E5](<Server/Dell/PowerEdge/PowerEdge R340/3C18F7464176/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C5AF7BF9E5>) |
| 8086:a1a1 | 1028:07c9 | Intel            | C620 Series Chipset Family Power ... | 7     |            | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1a1 | 15d9:0986 | Intel            | C620 Series Chipset Family Power ... | 7     |            | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 8086:a121 | 103c:8165 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     |            | [32E9F95095](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/013B4CDFD8CC/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/32E9F95095>) |
| 8086:a1a1 | 1028:0716 | Intel            | C620 Series Chipset Family Power ... | 4     |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 1590:005f | 1590:005f | HPE              |                                      | 3     |            | [0DA59DFF8F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/5D50CBD4DBDB/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/0DA59DFF8F>) |
| 8086:a121 | 1028:06aa | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [EFE3DBF989](<Server/Dell/PowerEdge/PowerEdge T130/1A6400B5BD8F/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/EFE3DBF989>) |
| 8086:a121 | 15d9:0896 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [A1DC602460](<Server/Supermicro/Super/Super Server/C3EAB3B58C16/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/A1DC602460>) |
| 8086:a121 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [7BD99B62AB](<Server/Supermicro/Super/Super Server/A912B2977FCE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7BD99B62AB>) |
| 8086:a121 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [AB6E70ABCA](<Server/Intel/S1200/S1200SP/BF2910D7912E/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/AB6E70ABCA>) |
| 8086:a1a1 | 1028:07ca | Intel            | C620 Series Chipset Family Power ... | 3     |            | [0B239C3286](<Server/Dell/PowerEdge/PowerEdge R540/34807F166517/OPNSENSE-22.1.7/13.0-STABLE/AMD64/0B239C3286>) |
| 8086:a1a1 | 1590:00eb | Intel            | C620 Series Chipset Family Power ... | 3     |            | [3A932D738C](<Server/HPE/ProLiant/ProLiant ML110 Gen10/819B1E7CD686/OPNSENSE-22.1.6/13.0-STABLE/AMD64/3A932D738C>) |
| 8086:a1a1 | 1734:1230 | Intel            | C620 Series Chipset Family Power ... | 3     |            | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 8086:43ef |           | Intel            | Tiger Lake-H Shared SRAM             | 2     |            | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 8086:43ef | 1458:1000 | Intel            | Tiger Lake-H Shared SRAM             | 2     |            | [BD71D84CF2](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/D0E7C21FF9A1/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/BD71D84CF2>) |
| 8086:a121 | 1028:06a5 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [6484798368](<Server/Dell/PowerEdge/PowerEdge R230/1310AA45E34E/OPNSENSE-22.7.4/13.1-RELEASE/AMD64/6484798368>) |
| 8086:a121 | 1028:06a6 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [7713DA37A9](<Server/Dell/PowerEdge/PowerEdge R330/4C0E1074252E/OPNSENSE-22.1.9/13.0-STABLE/AMD64/7713DA37A9>) |
| 8086:a121 | 15d9:0886 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [B34EE32475](<Server/Supermicro/Super/Super Server/76C4250B92CF/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/B34EE32475>) |
| 8086:a121 | 1734:1222 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [9E972FD1A1](<Server/Fujitsu/PRIMERGY/PRIMERGY TX1320 M2/0C5BD48E99F3/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/9E972FD1A1>) |
| 8086:a1a1 | 1028:0737 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [B062E0F4E4](<Server/Dell/PowerEdge/PowerEdge R740xd/3E6753E4D93A/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/B062E0F4E4>) |
| 8086:a1a1 | 1137:0101 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [2633EAF68B](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M5SX/41B605A42DA4/OPNSENSE-22.10/13.1-RELEASE-P2/AMD64/2633EAF68B>) |
| 8086:a1a1 | 8086:7270 | Intel            | C620 Series Chipset Family Power ... | 2     |            | [D088FBCF53](<Server/Supermicro/X11/X11DPi-N/9D541BB80ABA/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/D088FBCF53>) |
| 10de:0361 | 108e:6676 | Nvidia           | MCP55 LPC Bridge                     | 1     |            | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 10de:0369 | 108e:534b | Nvidia           | MCP55 Memory Controller              | 1     |            | [1D2D5F5A1F](<Server/Sun Microsystems/Sun/Sun Fire X2200 M2/ADF2AE13F3B1/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/1D2D5F5A1F>) |
| 10de:0369 | 108e:6676 | Nvidia           | MCP55 Memory Controller              | 1     |            | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 10de:036a | 108e:6676 | Nvidia           | MCP55 Memory Controller              | 1     |            | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 10ee:1500 | 10ee:5050 | Xilinx           |                                      | 1     |            | [000910EEFA](<Server/Intel/S5000/S5000PAL/D69F0664ED6E/OPNSENSE-22.1.8/13.0-STABLE/AMD64/000910EEFA>) |
| 8086:06ef | 15d9:1b6e | Intel            | Comet Lake PCH Shared SRAM           | 1     |            | [2A9AC1E6EE](<Server/Supermicro/Super/Super Server/224D290BC26B/OPNSENSE-22.1.6/13.0-STABLE/AMD64/2A9AC1E6EE>) |
| 8086:19de | 15d9:0982 | Intel            | Atom Processor C3000 Series Power... | 1     |            | [AC3F761F23](<Server/Supermicro/Super/Super Server/708682545862/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/AC3F761F23>) |
| 8086:43ef | 1028:0a91 | Intel            | Tiger Lake-H Shared SRAM             | 1     |            | [DDE6AF4613](<Server/Dell/PowerEdge/PowerEdge T150/140EB7015AAB/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/DDE6AF4613>) |
| 8086:9d21 | 15d9:098b | Intel            | Sunrise Point-LP PMC                 | 1     |            | [2EFE92BBA7](<Server/Supermicro/X11/X11SSN-L/BAB347016D47/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/2EFE92BBA7>) |
| 8086:a121 | 15d9:089b | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [766C25105D](<Server/Supermicro/Super/Super Server/61BB0DAECFF4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/766C25105D>) |
| 8086:a121 | 15d9:089f | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [F6CF8F7870](<Server/Supermicro/Super/Super Server/862E0901E10C/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/F6CF8F7870>) |
| 8086:a121 | 15d9:0902 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [9F6632DE8B](<Server/Supermicro/C7/C7Z170-OCE/1CCBCBB542C8/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/9F6632DE8B>) |
| 8086:a121 | 15d9:0907 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [A888AE8488](<Server/Supermicro/Super/Super Server/1FD8A6B1831A/FURYBSD-13.0-P10/13.0-RELEASE-P8/AMD64/A888AE8488>) |
| 8086:a121 | 15d9:0930 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [6244E44F35](<Server/Supermicro/X11/X11SSQ-L/64AECCC810F9/OPNSENSE-22.1.9/13.0-STABLE/AMD64/6244E44F35>) |
| 8086:a121 | 8086:a121 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [49D9F0E06A](<Server/Neousys Technology/Nuvo/Nuvo-5000/D47A2E3C3BC2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/49D9F0E06A>) |
| 8086:a1a1 | 1028:0739 | Intel            | C620 Series Chipset Family Power ... | 1     |            | [C8DDB7DAE6](<Server/Dell/Precision/Precision 7820 Tower/4877A83C2118/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/C8DDB7DAE6>) |
| 8086:a1a1 | 1028:07e5 | Intel            | C620 Series Chipset Family Power ... | 1     |            | [F315C33E95](<Server/Dell/PowerEdge/PowerEdge T640/0C0E2AFF67BB/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/F315C33E95>) |
| 8086:a1a1 | 10cf:19b6 | Intel            | C620 Series Chipset Family Power ... | 1     |            | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 8086:a1a1 | 15d9:096e | Intel            | C620 Series Chipset Family Power ... | 1     |            | [CA41B3F700](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1104H+ Server/5119C74221C5/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/CA41B3F700>) |
| 8086:a1a1 | 15d9:0987 | Intel            | C620 Series Chipset Family Power ... | 1     |            | [E1FCEAABC0](<Server/Supermicro/Super/Super Server/2C4DC94123A5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E1FCEAABC0>) |
| 8086:a1a1 | 15d9:1b28 | Intel            | C620 Series Chipset Family Power ... | 1     |            | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 8086:a1a1 | 17aa:1037 | Intel            | C620 Series Chipset Family Power ... | 1     |            | [FFAA30BC08](<Server/Lenovo/ThinkStation/ThinkStation P720 30BAS1HX00/DE50C8A519F5/FREEBSD-13.0/13.0-RELEASE/AMD64/FFAA30BC08>) |
| 8086:a1a1 | 17aa:7800 | Intel            | C620 Series Chipset Family Power ... | 1     |            | [311C32E56E](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/C2AF82A6E1C5/FREEBSD-13.1/13.1-RELEASE/AMD64/311C32E56E>) |
| 8086:a1a1 | 17aa:7801 | Intel            | C620 Series Chipset Family Power ... | 1     |            | [46C59D0DE8](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/EF5F31DB406A/OPNSENSE-22.1.5/13.0-STABLE/AMD64/46C59D0DE8>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1521 | 15d9:1521 | Intel            | I350 Gigabit Network Connection      | 66    | igb        | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 14e4:163b | 1028:04dd | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 42    | bce        | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:15ac | 15d9:15ac | Intel            | Ethernet Connection X552 10 GbE SFP+ | 31    | ix         | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 14e4:165f | 1028:1f5b | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 26    | bge        | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:1572 |           | Intel            | Ethernet Controller X710 for 10Gb... | 24    | ixl        | [53A90A6C63](<Server/Supermicro/X10/X10SLH-N6-ST031/CB0CBEB38B08/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/53A90A6C63>) |
| 14e4:1639 | 103c:7055 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 22    | bce        | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:10e8 | 8086:a02c | Intel            | 82576 Gigabit Network Connection     | 18    | igb        | [C5B09B219B](<Server/Dell/PowerEdge/PowerEdge R815/3734F0F11574/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/C5B09B219B>) |
| 14e4:1639 | 1028:0236 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 16    | bce        | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 14e4:165f | 1028:05e5 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 14    | bge        | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:15ad | 15d9:15ad | Intel            | Ethernet Connection X552/X557-AT ... | 14    | ix         | [C0C8D1F85E](<Server/Supermicro/Super/Super Server/73426A08BED9/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C0C8D1F85E>) |
| 8086:15e4 |           | Intel            | Ethernet Connection X553 1GbE        | 14    | ix         | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:15e5 |           | Intel            | Ethernet Connection X553 1GbE        | 14    | ix         | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:153a | 15d9:153a | Intel            | Ethernet Connection I217-LM          | 13    | em         | [7D80C62813](<Server/Supermicro/X10/X10SLL-F/A4ACF508F8E6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7D80C62813>) |
| 8086:1521 | 8086:5001 | Intel            | I350 Gigabit Network Connection      | 11    | igb        | [7713DA37A9](<Server/Dell/PowerEdge/PowerEdge R330/4C0E1074252E/OPNSENSE-22.1.9/13.0-STABLE/AMD64/7713DA37A9>) |
| 8086:154d | 8086:7b11 | Intel            | Ethernet 10G 2P X520 Adapter         | 11    | ix         | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 14e4:165f | 1028:04f8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 10    | bge        | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 10    | igb        | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 14e4:163b | 1028:02a5 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 9     | bce        | [340DC7255C](<Server/Dell/PowerEdge/PowerEdge R210/5E68DB36191B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/340DC7255C>) |
| 14e4:165f | 1028:001f | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 9     | bge        | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 14e4:1639 | 1014:03a9 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 8     | bce        | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 14e4:165f | 1028:04f7 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 8     | bge        | [A1A15662D0](<Server/Dell/PowerEdge/PowerEdge R320/0A57FAA417FF/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/A1A15662D0>) |
| 8086:10fb | 8086:000c | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 8     | ix         | [2633EAF68B](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M5SX/41B605A42DA4/OPNSENSE-22.10/13.1-RELEASE-P2/AMD64/2633EAF68B>) |
| 8086:1521 | 1028:1f60 | Intel            | I350 Gigabit Network Connection      | 8     | igb        | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 14e4:1639 | 14e4:0907 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 7     | bce        | [F1232F79C4](<Server/Dell/PowerEdge/PowerEdge R210/4BB9442C6B5F/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/F1232F79C4>) |
| 14e4:1657 | 103c:22be | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 7     | bge        | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:37d0 | 15d9:37d0 | Intel            | Ethernet Connection X722 for 10Gb... | 7     | ixl        | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 14e4:163b | 1028:028c | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 6     | bce        | [847CA0ACB9](<Server/Dell/PowerEdge/PowerEdge R410/AA3B52468CEC/OPNSENSE-22.1.6/13.0-STABLE/AMD64/847CA0ACB9>) |
| 14e4:168e | 14e4:1008 | Broadcom         | NetXtreme II BCM57810 10 Gigabit ... | 6     | bxe        | [C5B09B219B](<Server/Dell/PowerEdge/PowerEdge R815/3734F0F11574/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/C5B09B219B>) |
| 1425:5001 |           | Chelsio Commu... | T520-CR Unified Wire Ethernet Con... | 5     | t5iov      | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 1425:5401 |           | Chelsio Commu... | T520-CR Unified Wire Ethernet Con... | 5     | t5nex      | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 14e4:164c | 1014:0342 | Broadcom         | NetXtreme II BCM5708 Gigabit Ethe... | 5     | bce        | [41D40D8752](<Server/IBM/System/System x3650 -[797941Y]-/B6A5CBBF3013/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/41D40D8752>) |
| 14e4:1657 | 103c:169d | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 5     | bge        | [01945539D9](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/C4DE94754B80/OPNSENSE-22.1.6/13.0-STABLE/AMD64/01945539D9>) |
| 14e4:165a | 1028:04de | Broadcom         | NetXtreme BCM5722 Gigabit Etherne... | 5     | bge        | [4D371914ED](<Server/Dell/PowerEdge/PowerEdge T110 II/1BB4A8B14EA4/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/4D371914ED>) |
| 14e4:165f | 1028:088f | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 5     | bge        | [545DACB881](<Server/Dell/PowerEdge/PowerEdge R240/19A6101614C9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/545DACB881>) |
| 14e4:168e | 14e4:1006 | Broadcom         | NetXtreme II BCM57810 10 Gigabit ... | 5     | bxe        | [B9DF714117](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/0FE7DBEBF7BB/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B9DF714117>) |
| 8086:10c9 | 103c:323f | Intel            | 82576 Gigabit Network Connection     | 5     | igb        | [289D2F383B](<Server/Hewlett-Packard/ProLiant/ProLiant DL180 G6/8E2A024CC455/FREEBSD-12.3-P7/12.3-RELEASE-P6/AMD64/289D2F383B>) |
| 8086:10fb | 1028:1f72 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 5     | ix         | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:10fb | 8086:7a11 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 5     | ix         | [20F8611419](<Server/Dell/PowerEdge/PowerEdge R220/ED9B8275AF71/OPNSENSE-22.1.4/13.0-STABLE/AMD64/20F8611419>) |
| 8086:1521 |           | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [5671721752](<Server/Supermicro/Super/Super Server/4826F7074630/OPNSENSE-22.7/13.1-RELEASE/AMD64/5671721752>) |
| 8086:1521 | 1028:1f73 | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:1521 | 103c:3380 | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [0DA59DFF8F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/5D50CBD4DBDB/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/0DA59DFF8F>) |
| 8086:1521 | 15d9:1b12 | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:1521 | 8086:5002 | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:1528 | 8086:0001 | Intel            | Ethernet Controller 10-Gigabit X5... | 5     | ix         | [7C432603CF](<Server/Dell/PowerEdge/PowerEdge R630/DD6247153B27/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/7C432603CF>) |
| 8086:1572 | 8086:0007 | Intel            | Ethernet Controller X710 for 10Gb... | 5     | ixl        | [66C10B64CB](<Server/Supermicro/Super/Super Server/972BB3DC5295/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/66C10B64CB>) |
| 1077:8020 | 103c:3733 | QLogic           | cLOM8214 1/10GbE Controller          | 4     | ql         | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 14e4:164c | 1028:01b2 | Broadcom         | NetXtreme II BCM5708 Gigabit Ethe... | 4     | bce        | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 14e4:1659 | 1028:023c | Broadcom         | NetXtreme BCM5721 Gigabit Etherne... | 4     | bge        | [A12907D76A](<Server/Dell/PowerEdge/PowerEdge R200/4AC27B58A736/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A12907D76A>) |
| 14e4:165a | 1028:02a6 | Broadcom         | NetXtreme BCM5722 Gigabit Etherne... | 4     | bge        | [C63D853ABC](<Server/Dell/PowerEdge/PowerEdge T110/ECD9FAFE3AEB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C63D853ABC>) |
| 14e4:168e | 103c:339d | Broadcom         | NetXtreme II BCM57810 10 Gigabit ... | 4     | bxe        | [DB0E0DBB14](<Server/Dell/PowerEdge/PowerEdge R210 II/91BA892D2460/OPNSENSE-22.1.1/13.0-STABLE/AMD64/DB0E0DBB14>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 1     | ath        | [1E7D58CD40](<Server/ASUSTek Computer/P8B-X/P8B-X series/5BF171BFBCD4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/1E7D58CD40>) |
| 168c:0030 | 168c:3112 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 1     | ath        | [F6CF8F7870](<Server/Supermicro/Super/Super Server/862E0901E10C/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/F6CF8F7870>) |
| 168c:0033 | 19b6:d057 | Qualcomm Atheros | AR958x 802.11abgn Wireless Networ... | 1     | ath        | [A1DC602460](<Server/Supermicro/Super/Super Server/C3EAB3B58C16/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/A1DC602460>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1533 | 15d9:1533 | Intel            | I210 Gigabit Network Connection      | 116   | igb        | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 8086:1528 | 15d9:1528 | Intel            | Ethernet Controller 10-Gigabit X5... | 19    | ix         | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 14e4:1639 | 1028:0235 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 18    | bce        | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 14e4:164c | 103c:7038 | Broadcom         | NetXtreme II BCM5708 Gigabit Ethe... | 10    | bce        | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 14e4:165f | 103c:22e8 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 10    | bge        | [32E9F95095](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/013B4CDFD8CC/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/32E9F95095>) |
| 8086:37d2 | 15d9:37d2 | Intel            | Ethernet Connection X722 for 10GB... | 10    | ixl        | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 8086:105e | 8086:135e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 9     | em         | [9DB5CC48B8](<Server/Dell/PowerEdge/PowerEdge T110 II/D80DD6DA02C2/OPNSENSE-22.1.8/13.0-STABLE/AMD64/9DB5CC48B8>) |
| 14e4:1639 | 14e4:1917 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 8     | bce        | [9C2CA983AC](<Server/Dell/PowerEdge/PowerEdge R320/7B1C75B3FBB5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/9C2CA983AC>) |
| 8086:10d3 | 8086:a01f | Intel            | 82574L Gigabit Network Connection    | 7     | em         | [6454631448](<Server/Dell/PowerEdge/PowerEdge R220/C306D0A87402/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/6454631448>) |
| 8086:105e | 103c:7044 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 6     | em         | [B0AF5D8891](<Server/Dell/PowerEdge/PowerEdge R420/54B10CEE65CE/OPNSENSE-22.1/13.0-STABLE/AMD64/B0AF5D8891>) |
| 8086:10d3 | 1043:8369 | Intel            | 82574L Gigabit Network Connection    | 6     | em         | [1347F15B56](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/36C252462A40/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/1347F15B56>) |
| 8086:10fb | 8086:0003 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 6     | ix         | [387E5946F7](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/440E19CD2833/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/387E5946F7>) |
| 1425:0031 | 1425:0001 | Chelsio Commu... | T320 10GbE Dual Port Adapter         | 5     | cxgbc      | [4763FE7595](<Server/Intel/S1200/S1200RP_SE/4DF73AF97478/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/4763FE7595>) |
| 14e4:165f | 103c:2133 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 5     | bge        | [6DE7C9CBA0](<Server/Hewlett-Packard/ProLiant/ProLiant DL320e Gen8 v2/52B6B236C9FB/OPNSENSE-22.1.5/13.0-STABLE/AMD64/6DE7C9CBA0>) |
| 8086:10d3 | 15d9:10d3 | Intel            | 82574L Gigabit Network Connection    | 5     | em         | [E7536E4A4C](<Server/Citrix/NSMPX/NSMPX-17500/A5177682AF7A/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/E7536E4A4C>) |
| 8086:10d3 | 1734:1192 | Intel            | 82574L Gigabit Network Connection    | 5     | em         | [1B27159E27](<Server/Fujitsu/PRIMERGY/PRIMERGY TX120 S3/23E5EBA2A16E/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/1B27159E27>) |
| 8086:1521 | 8086:0002 | Intel            | I350 Gigabit Network Connection      | 5     | igb        | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 14e4:1657 | 14e4:1904 | Broadcom         | NetXtreme BCM5719 Gigabit Etherne... | 4     | bge        | [633B9A5425](<Server/Supermicro/Super/Super Server/0549358E2062/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/633B9A5425>) |
| 15b3:1003 | 15b3:0055 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 4     | mlx4_core  | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 8086:1502 | 1734:11b7 | Intel            | 82579LM Gigabit Network Connectio... | 4     | em         | [1B27159E27](<Server/Fujitsu/PRIMERGY/PRIMERGY TX120 S3/23E5EBA2A16E/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/1B27159E27>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 3     | re         | [D2D859C434](<Server/Dell/PowerEdge/PowerEdge 1900/003DCEEEE034/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/D2D859C434>) |
| 1425:0000 |           | Chelsio Commu... |                                      | 3     |            | [70A786B8B5](<Server/Supermicro/X10/X10SLM+-LN4F/F4A1F01A1AAE/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/70A786B8B5>) |
| 14e4:163b | 1028:02f1 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 3     | bce        | [F23BF8E1A7](<Server/Dell/PowerEdge/PowerEdge R510/4EF43D83F096/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/F23BF8E1A7>) |
| 14e4:165f | 1028:06a7 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 3     | bge        | [EFE3DBF989](<Server/Dell/PowerEdge/PowerEdge T130/1A6400B5BD8F/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/EFE3DBF989>) |
| 8086:1096 | 8086:3476 | Intel            | 80003ES2LAN Gigabit Ethernet Cont... | 3     | em         | [411F470773](<Server/Intel/S5000/S5000PSL/8B6E5700823E/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/411F470773>) |
| 8086:10fb | 8086:0006 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 3     | ix         | [913791B3CC](<Server/Dell/PowerEdge/PowerEdge R220/6D7609593826/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/913791B3CC>) |
| 8086:150e | 1734:11a8 | Intel            | 82580 Gigabit Network Connection     | 3     | igb        | [1B27159E27](<Server/Fujitsu/PRIMERGY/PRIMERGY TX120 S3/23E5EBA2A16E/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/1B27159E27>) |
| 8086:150e | 8086:12a2 | Intel            | 82580 Gigabit Network Connection     | 3     | igb        | [7024873A21](<Server/Dell/PowerEdge/PowerEdge R210 II/021A694865C9/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/7024873A21>) |
| 8086:1521 | 8086:00a2 | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [F96CB98005](<Server/Dell/PowerEdge/PowerEdge R420/93ABA978B199/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/F96CB98005>) |
| 8086:153a | 17aa:30a6 | Intel            | Ethernet Connection I217-LM          | 3     | em         | [D6111B8FF1](<Server/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/C9B365EFBC6F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D6111B8FF1>) |
| 8086:15b7 | 15d9:15b7 | Intel            | Ethernet Connection (2) I219-LM      | 3     | em         | [6244E44F35](<Server/Supermicro/X11/X11SSQ-L/64AECCC810F9/OPNSENSE-22.1.9/13.0-STABLE/AMD64/6244E44F35>) |
| 10ec:8139 | 10ec:8139 | Realtek Semic... | RTL-8100/8101L/8139 PCI Fast Ethe... | 2     | rl         | [DD33780E1B](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY ECONEL 50/B268E1785214/OPNSENSE-22.1/13.0-STABLE/AMD64/DD33780E1B>) |
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 2     | re         | [1AD1A2496B](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/89644753963D/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1AD1A2496B>) |
| 14e4:163b | 1028:02a4 | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 2     | bce        | [8460816B1F](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/TRUENAS-12.2-P12/12.2-RELEASE-P12/AMD64/8460816B1F>) |
| 14e4:1659 | 14e4:1659 | Broadcom         | NetXtreme BCM5721 Gigabit Etherne... | 2     | bge        | [E988626E65](<Server/Dell/PowerEdge/PowerEdge 850/7C1FFD13EA06/OPNSENSE-21.7.3/12.1-RELEASE-P19-HBSD/AMD64/E988626E65>) |
| 15b3:1003 | 15b3:0050 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 2     | mlx4_core  | [B9DF714117](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/0FE7DBEBF7BB/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B9DF714117>) |
| 15b3:1007 | 15b3:0079 | Mellanox Tech... | MT27520 Family [ConnectX-3 Pro]      | 2     | mlx4_core  | [1BC8C02062](<Server/Dell/PowerEdge/PowerEdge R630/685D8E49B8EC/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1BC8C02062>) |
| 15b3:6750 | 15b3:0021 | Mellanox Tech... | MT26448 [ConnectX EN 10GigE, PCIe... | 2     | mlx4_core  | [7326628267](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/7326628267>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 2     | em         | [F1E7CB51D7](<Server/Gigabyte Technology/GA-6/GA-6UPCP2-4-5/9FBC80D6457F/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/F1E7CB51D7>) |
| 8086:10d3 | 103c:1785 | Intel            | 82574L Gigabit Network Connection    | 2     | em         | [1EBF1B71BD](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 G7/C0A00A1DE91B/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/1EBF1B71BD>) |
| 8086:10d3 | 8086:34ec | Intel            | 82574L Gigabit Network Connection    | 2     | em         | [C614A1E46F](<Server/Intel/S3420/S3420GP/3AA435A1E08F/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C614A1E46F>) |
| 8086:10ef | 8086:34ec | Intel            | 82578DM Gigabit Network Connection   | 2     | em         | [C614A1E46F](<Server/Intel/S3420/S3420GP/3AA435A1E08F/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C614A1E46F>) |
| 8086:1563 |           | Intel            | Ethernet Controller X550             | 2     | ix         | [EE37B7ABF2](<Server/Supermicro/Super/Super Server/8C220E4D92D8/OPNSENSE-22.1.3/13.0-STABLE/AMD64/EE37B7ABF2>) |
| 8086:15b7 |           | Intel            | Ethernet Connection (2) I219-LM      | 2     | em         | [49D9F0E06A](<Server/Neousys Technology/Nuvo/Nuvo-5000/D47A2E3C3BC2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/49D9F0E06A>) |
| 1077:4032 | 1077:0158 | QLogic           | ISP4032-based iSCSI TOE IPv6 HBA     | 1     |            | [76A17B83E5](<Server/IBM/System/System x3650 M4: -[7915AC1]-/9CD691E97074/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/76A17B83E5>) |
| 1425:0030 | 1014:038c | Chelsio Commu... | T310 10GbE Single Port Adapter       | 1     | cxgbc      | [4D3D23FBD1](<Server/Supermicro/X10/X10SLH-N6-ST031/D0126CBC581E/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/4D3D23FBD1>) |
| 14c1:0008 | 14c1:000a | MYRICOM          | Myri-10G Dual-Protocol NIC           | 1     | mxge       | [2BD1529913](<Server/Supermicro/MBD-X8/MBD-X8DT6-A-IS018/9FC8D16648D3/FREEBSD-13.1/13.1-RELEASE/AMD64/2BD1529913>) |
| 14e4:164c | 103c:7037 | Broadcom         | NetXtreme II BCM5708 Gigabit Ethe... | 1     | bce        | [4EBC960E9C](<Server/Hewlett-Packard/ProLiant/ProLiant DL365 G5/F4B3B0B8D289/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/4EBC960E9C>) |
| 14e4:165f | 1028:04fa | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 1     | bge        | [68C4DD4311](<Server/Dell/PowerEdge/PowerEdge T320/3F64A0C690AD/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/68C4DD4311>) |
| 15b3:1003 | 15b3:0077 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 1     | mlx4_core  | [ADDCB4CB9B](<Server/Dell/PowerEdge/PowerEdge R210 II/1B5E8D217C69/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/ADDCB4CB9B>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 103c:3302 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard KC... | 23    | ipmi       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:19e0 | 15d9:0969 | Intel            | Atom Processor C3000 Series SPI C... | 18    |            | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:a324 | 15d9:1b0e | Intel            | Cannon Lake PCH SPI Controller       | 8     |            | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:a368 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 8     | ig4iic     | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:a369 | 15d9:1b0e | Intel            | Cannon Lake PCH Serial IO I2C Con... | 8     | ig4iic     | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:a1a4 | 1028:07c9 | Intel            | C620 Series Chipset Family SPI Co... | 7     |            | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1a4 | 15d9:0986 | Intel            | C620 Series Chipset Family SPI Co... | 7     |            | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 1425:5601 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 5     |            | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 8086:a324 | 1028:088f | Intel            | Cannon Lake PCH SPI Controller       | 5     |            | [545DACB881](<Server/Dell/PowerEdge/PowerEdge R240/19A6101614C9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/545DACB881>) |
| 8086:a1a4 | 1028:0716 | Intel            | C620 Series Chipset Family SPI Co... | 4     |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 1425:4601 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 3     |            | [70A786B8B5](<Server/Supermicro/X10/X10SLM+-LN4F/F4A1F01A1AAE/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/70A786B8B5>) |
| 8086:a1a4 | 1028:07ca | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [0B239C3286](<Server/Dell/PowerEdge/PowerEdge R540/34807F166517/OPNSENSE-22.1.7/13.0-STABLE/AMD64/0B239C3286>) |
| 8086:a1a4 | 1734:1230 | Intel            | C620 Series Chipset Family SPI Co... | 3     |            | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 8086:a324 | 15d9:1b11 | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [1AD1A2496B](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/89644753963D/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1AD1A2496B>) |
| 8086:a368 | 15d9:1b11 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | ig4iic     | [1AD1A2496B](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/89644753963D/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1AD1A2496B>) |
| 8086:a369 | 15d9:1b11 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 3     | ig4iic     | [1AD1A2496B](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/89644753963D/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1AD1A2496B>) |
| 1077:2031 | 1077:0257 | QLogic           | ISP8324-based 16Gb Fibre Channel ... | 2     | isp        | [C5B09B219B](<Server/Dell/PowerEdge/PowerEdge R815/3734F0F11574/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/C5B09B219B>) |
| 1077:2532 | 103c:3262 | QLogic           | ISP2532-based 8Gb Fibre Channel t... | 2     | isp        | [D35F62BA44](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/F3C30038FE1D/FREEBSD-12.1-P6/12.1-RELEASE-P1/AMD64/D35F62BA44>) |
| 8086:43a4 | 1458:1000 | Intel            | Tiger Lake-H SPI Controller          | 2     |            | [BD71D84CF2](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/D0E7C21FF9A1/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/BD71D84CF2>) |
| 8086:43a4 | 15d9:1c3b | Intel            | Tiger Lake-H SPI Controller          | 2     |            | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 8086:43ad | 15d9:1c3b | Intel            | 500 Series Chipset Family PCIe Po... | 2     | ig4iic     | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 8086:43ae | 15d9:1c3b | Intel            | 500 Series Chipset Family PCIe Po... | 2     | ig4iic     | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 8086:43e8 | 1458:1000 | Intel            | Tiger Lake-H Serial IO I2C Contro... | 2     | ig4iic     | [BD71D84CF2](<Server/Gigabyte Technology/MX33/MX33-BS1-V1/D0E7C21FF9A1/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/BD71D84CF2>) |
| 8086:43e8 | 15d9:1c3b | Intel            | Tiger Lake-H Serial IO I2C Contro... | 2     | ig4iic     | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 8086:43e9 | 15d9:1c3b | Intel            | Tiger Lake-H Serial IO I2C Contro... | 2     | ig4iic     | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 8086:43eb | 15d9:1c3b | Intel            | 500 Series Chipset Family LPSS: I... | 2     | ig4iic     | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 8086:a1a4 | 1028:0737 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [B062E0F4E4](<Server/Dell/PowerEdge/PowerEdge R740xd/3E6753E4D93A/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/B062E0F4E4>) |
| 8086:a1a4 | 1137:0101 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [2633EAF68B](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M5SX/41B605A42DA4/OPNSENSE-22.10/13.1-RELEASE-P2/AMD64/2633EAF68B>) |
| 8086:a1a4 | 8086:7270 | Intel            | C620 Series Chipset Family SPI Co... | 2     |            | [D088FBCF53](<Server/Supermicro/X11/X11DPi-N/9D541BB80ABA/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/D088FBCF53>) |
| 8086:a324 | 1028:088e | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [C5AF7BF9E5](<Server/Dell/PowerEdge/PowerEdge R340/3C18F7464176/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C5AF7BF9E5>) |
| 8086:a324 | 1590:028d | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [2B827CE498](<Server/HPE/ProLiant/ProLiant DL20 Gen10/59AD6BA78D10/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/2B827CE498>) |
| 1077:2432 | 103c:7040 | QLogic           | ISP2432-based 4Gb Fibre Channel t... | 1     |            | [7CC48A8D08](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/9E11D24B206A/FREEBSD-12.1/12.1-RELEASE/AMD64/7CC48A8D08>) |
| 10df:f100 | 10df:f100 | Emulex           | LPe12000 Series 8Gb Fibre Channel... | 1     |            | [5CEACE59C1](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S6/A4AE3CCBC16C/FREEBSD-13.1-P1/13.1-RELEASE/AMD64/5CEACE59C1>) |
| 10df:f400 | 10df:f402 | Emulex           | LPe35000/LPe36000 Series 32Gb/64G... | 1     |            | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 10df:f400 | 10df:f410 | Emulex           | LPe35000/LPe36000 Series 32Gb/64G... | 1     |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 10df:fe00 | 103c:1708 | Emulex           | Zephyr-X LightPulse Fibre Channel... | 1     |            | [2B539FCF18](<Server/Hewlett-Packard/ProLiant/ProLiant BL460c G6/88EB39748DFF/FREEBSD-13.0/13.0-RELEASE/AMD64/2B539FCF18>) |
| 1137:0045 | 1137:0085 | Cisco Systems    | VIC FCoE HBA                         | 1     |            | [1B3588AB2F](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0/13.0-RELEASE/AMD64/1B3588AB2F>) |
| 1137:0045 | 1137:0157 | Cisco Systems    | VIC FCoE HBA                         | 1     |            | [95C7AED281](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/FF220973685E/FREEBSD-13.0/13.0-RELEASE/AMD64/95C7AED281>) |
| 1425:5683 |           | Chelsio Commu... | T540-5083 Unified Wire Storage Co... | 1     |            | [A1CF339702](<Server/Supermicro/Super/Super Server/AEAD0BFD0A36/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/A1CF339702>) |
| 8086:06a4 | 15d9:1b6e | Intel            | Comet Lake PCH SPI Controller        | 1     |            | [2A9AC1E6EE](<Server/Supermicro/Super/Super Server/224D290BC26B/OPNSENSE-22.1.6/13.0-STABLE/AMD64/2A9AC1E6EE>) |
| 8086:19e0 | 15d9:0982 | Intel            | Atom Processor C3000 Series SPI C... | 1     |            | [AC3F761F23](<Server/Supermicro/Super/Super Server/708682545862/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/AC3F761F23>) |
| 8086:43a4 | 1028:0a91 | Intel            | Tiger Lake-H SPI Controller          | 1     |            | [DDE6AF4613](<Server/Dell/PowerEdge/PowerEdge T150/140EB7015AAB/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/DDE6AF4613>) |
| 8086:a1a4 | 1028:0739 | Intel            | C620 Series Chipset Family SPI Co... | 1     |            | [C8DDB7DAE6](<Server/Dell/Precision/Precision 7820 Tower/4877A83C2118/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/C8DDB7DAE6>) |
| 8086:a1a4 | 1028:07e5 | Intel            | C620 Series Chipset Family SPI Co... | 1     |            | [F315C33E95](<Server/Dell/PowerEdge/PowerEdge T640/0C0E2AFF67BB/FREEBSD-13.0-P7/13.0-RELEASE-P4/AMD64/F315C33E95>) |
| 8086:a1a4 | 10cf:19b6 | Intel            | C620 Series Chipset Family SPI Co... | 1     |            | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 8086:a1a4 | 15d9:096e | Intel            | C620 Series Chipset Family SPI Co... | 1     |            | [CA41B3F700](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1104H+ Server/5119C74221C5/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/CA41B3F700>) |
| 8086:a1a4 | 15d9:0987 | Intel            | C620 Series Chipset Family SPI Co... | 1     |            | [E1FCEAABC0](<Server/Supermicro/Super/Super Server/2C4DC94123A5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/E1FCEAABC0>) |
| 8086:a1a4 | 15d9:1b28 | Intel            | C620 Series Chipset Family SPI Co... | 1     |            | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 8086:a1a4 | 17aa:1037 | Intel            | C620 Series Chipset Family SPI Co... | 1     |            | [FFAA30BC08](<Server/Lenovo/ThinkStation/ThinkStation P720 30BAS1HX00/DE50C8A519F5/FREEBSD-13.0/13.0-RELEASE/AMD64/FFAA30BC08>) |
| 8086:a1a4 | 17aa:7800 | Intel            | C620 Series Chipset Family SPI Co... | 1     |            | [311C32E56E](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/C2AF82A6E1C5/FREEBSD-13.1/13.1-RELEASE/AMD64/311C32E56E>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:6f30 | 8086:6f30 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f34 | 8086:6f34 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f36 | 8086:6f36 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f37 | 8086:6f37 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f7d | 8086:6f7d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:204d |           | Intel            | Sky Lake-E M3KTI Registers           | 35    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2015 |           | Intel            | Sky Lake-E Ubox Registers            | 32    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2058 |           | Intel            | Sky Lake-E KTI 0                     | 28    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:8c24 | 15d9:0921 | Intel            | 8 Series Chipset Family Thermal M... | 25    | pchtherm   | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:204c |           | Intel            | Sky Lake-E M3KTI Registers           | 24    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:8c24 | 15d9:086d | Intel            | 8 Series Chipset Family Thermal M... | 20    | pchtherm   | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:2088 |           | Intel            | Sky Lake-E DDRIO Registers           | 19    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:8c24 | 15d9:0842 | Intel            | 8 Series Chipset Family Thermal M... | 19    | pchtherm   | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:2f30 | 8086:2f30 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 18    |            | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 8086:2f34 | 8086:2f34 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 18    |            | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 8086:2f36 | 8086:2f36 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 18    |            | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 8086:2f37 | 8086:2f37 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 18    |            | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 8086:2f7d | 8086:2f7d | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 18    |            | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 8086:0e30 | 1028:0528 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 13    |            | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:0e34 | 1028:0528 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 13    |            | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:0e36 | 1028:0528 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 13    |            | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:2f32 | 8086:2f32 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 13    |            | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:2f33 | 8086:2f33 | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 QPI... | 12    |            | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:8c24 | 15d9:0801 | Intel            | 8 Series Chipset Family Thermal M... | 11    | pchtherm   | [7D80C62813](<Server/Supermicro/X10/X10SLL-F/A4ACF508F8E6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7D80C62813>) |
| 8086:a131 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | pchtherm   | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 8086:6f32 | 8086:6f32 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 8     |            | [1BC8C02062](<Server/Dell/PowerEdge/PowerEdge R630/685D8E49B8EC/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1BC8C02062>) |
| 8086:6f33 | 8086:6f33 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 8     |            | [1BC8C02062](<Server/Dell/PowerEdge/PowerEdge R630/685D8E49B8EC/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/1BC8C02062>) |
| 8086:8c24 | 15d9:0803 | Intel            | 8 Series Chipset Family Thermal M... | 8     | pchtherm   | [6F95477DF3](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/6F95477DF3>) |
| 8086:a379 | 15d9:1b0e | Intel            | Cannon Lake PCH Thermal Controller   | 8     | pchtherm   | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:0e30 | 1028:04f8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 7     |            | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:0e34 | 1028:04f8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 7     |            | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:0e36 | 1028:04f8 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 7     |            | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:a1b1 | 1028:07c9 | Intel            | C620 Series Chipset Family Therma... | 7     | pchtherm   | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1b1 | 15d9:0986 | Intel            | C620 Series Chipset Family Therma... | 7     | pchtherm   | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 8086:0e30 | 1028:04ce | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 6     |            | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 8086:0e30 | 15d9:0660 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 Hom... | 6     |            | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 8086:0e34 | 1028:04ce | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 6     |            | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 8086:0e34 | 15d9:0660 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 R2PCIe | 6     |            | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 8086:0e36 | 1028:04ce | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 6     |            | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 8086:0e36 | 15d9:0660 | Intel            | Xeon E7 v2/Xeon E5 v2/Core i7 QPI... | 6     |            | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 8086:1d24 | 15d9:0660 | Intel            | C600/X79 series chipset Thermal M... | 6     |            | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 8086:3c43 | 1028:04f7 | Intel            | Xeon E5/Core i7 Ring to PCI Expre... | 6     |            | [9C2CA983AC](<Server/Dell/PowerEdge/PowerEdge R320/7B1C75B3FBB5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/9C2CA983AC>) |
| 8086:3c44 | 1028:04f7 | Intel            | Xeon E5/Core i7 Ring to QuickPath... | 6     |            | [9C2CA983AC](<Server/Dell/PowerEdge/PowerEdge R320/7B1C75B3FBB5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/9C2CA983AC>) |
| 8086:3c46 | 1028:04f7 | Intel            | Xeon E5/Core i7 Processor Home Ag... | 6     |            | [9C2CA983AC](<Server/Dell/PowerEdge/PowerEdge R320/7B1C75B3FBB5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/9C2CA983AC>) |
| 8086:3ce6 | 1028:04f7 | Intel            | Xeon E5/Core i7 QuickPath Interco... | 6     |            | [9C2CA983AC](<Server/Dell/PowerEdge/PowerEdge R320/7B1C75B3FBB5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/9C2CA983AC>) |
| 8086:2f30 | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Hom... | 5     |            | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:2f34 | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 PCI... | 5     |            | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:2f36 | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 5     |            | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:2f37 | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 R3 ... | 5     |            | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:2f7d | 103c:21ea | Intel            | Xeon E7 v3/Xeon E5 v3/Core i7 Scr... | 5     |            | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c22 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 42    | ichsmb     | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:8c22 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | ichsmb     | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c22 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ichsmb     | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c22 | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 19    | ichsmb     | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:19df | 15d9:0969 | Intel            | Atom Processor C3000 Series SMBus... | 18    | ichsmb     | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:8c22 | 1028:05e5 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | ichsmb     | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:8c22 | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | ichsmb     | [7D80C62813](<Server/Supermicro/X10/X10SLL-F/A4ACF508F8E6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7D80C62813>) |
| 8086:a123 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 10    | ichsmb     | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 1022:790b | 15d9:790b | AMD              | FCH SMBus Controller                 | 9     | intsmb     | [76519F54E9](<Server/Supermicro/Super/Super Server/B6CF39D94613/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/76519F54E9>) |
| 8086:2292 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | ichsmb     | [649D525FDB](<Server/Supermicro/Super/Super Server/A4D89EA96DC4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/649D525FDB>) |
| 8086:3a30 | 1014:3a30 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 8     | ichsmb     | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 8086:8c22 | 15d9:0803 | Intel            | 8 Series/C220 Series Chipset Fami... | 8     | ichsmb     | [6F95477DF3](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/6F95477DF3>) |
| 8086:8d22 | 103c:8030 | Intel            | C610/X99 series chipset SMBus Con... | 8     | ichsmb     | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:a323 | 15d9:1b0e | Intel            | Cannon Lake PCH SMBus Controller     | 8     | ichsmb     | [94FF07CDD9](<Server/Supermicro/Super/Super Server/2F00F106DE5D/OPNSENSE-22.1.7/13.0-STABLE/AMD64/94FF07CDD9>) |
| 8086:a1a3 | 1028:07c9 | Intel            | C620 Series Chipset Family SMBus     | 7     | ichsmb     | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1a3 | 15d9:0986 | Intel            | C620 Series Chipset Family SMBus     | 7     | ichsmb     | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 8086:1d22 | 15d9:0660 | Intel            | C600/X79 series chipset SMBus Hos... | 6     | ichsmb     | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 8086:1c22 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | ichsmb     | [4D371914ED](<Server/Dell/PowerEdge/PowerEdge T110 II/1BB4A8B14EA4/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/4D371914ED>) |
| 8086:1c22 | 1043:8497 | Intel            | 6 Series/C200 Series Chipset Fami... | 5     | ichsmb     | [1347F15B56](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G6/36C252462A40/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/1347F15B56>) |
| 8086:269b | 1014:02dd | Intel            | 631xESB/632xESB/3100 Chipset SMBu... | 5     | ichsmb     | [41D40D8752](<Server/IBM/System/System x3650 -[797941Y]-/B6A5CBBF3013/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/41D40D8752>) |
| 8086:8d22 | 15d9:0834 | Intel            | C610/X99 series chipset SMBus Con... | 5     | ichsmb     | [59FF2014E5](<Server/Supermicro/Super/Super Server/C53FD6545133/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/59FF2014E5>) |
| 8086:a323 | 1028:088f | Intel            | Cannon Lake PCH SMBus Controller     | 5     |            | [545DACB881](<Server/Dell/PowerEdge/PowerEdge R240/19A6101614C9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/545DACB881>) |
| 1022:790b | 1022:790b | AMD              | FCH SMBus Controller                 | 4     | intsmb     | [57721BF0F2](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/734A66ADD4EA/OPNSENSE-22.1/13.0-STABLE/AMD64/57721BF0F2>) |
| 8086:1c22 | 1734:11cb | Intel            | 6 Series/C200 Series Chipset Fami... | 4     | ichsmb     | [1B27159E27](<Server/Fujitsu/PRIMERGY/PRIMERGY TX120 S3/23E5EBA2A16E/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/1B27159E27>) |
| 8086:1f3c | 15d9:0820 | Intel            | Atom processor C2000 PCU SMBus       | 4     | ichsmb     | [FB96378782](<Server/Supermicro/A1/A1SRM-2758F/F38A17AAB757/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FB96378782>) |
| 8086:269b | 108e:4843 | Intel            | 631xESB/632xESB/3100 Chipset SMBu... | 4     |            | [51E87104A0](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/51E87104A0>) |
| 8086:8c22 | 15d9:0806 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     | ichsmb     | [319819F81D](<Server/Supermicro/X10/X10SLM+-LN4F/9396CB95C705/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/319819F81D>) |
| 8086:8c22 | 8086:8c22 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     | ichsmb     | [3494695F54](<Server/ASUSTek Computer/P9D-X/P9D-X Series/9942A2F29F13/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/3494695F54>) |
| 8086:8d22 | 15d9:0832 | Intel            | C610/X99 series chipset SMBus Con... | 4     | ichsmb     | [1499A2903D](<Server/Supermicro/Super/Super Server/7E6D506E6800/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1499A2903D>) |
| 8086:a123 | 103c:8165 | Intel            | 100 Series/C230 Series Chipset Fa... | 4     | ichsmb     | [32E9F95095](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/013B4CDFD8CC/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/32E9F95095>) |
| 8086:a1a3 | 1028:0716 | Intel            | C620 Series Chipset Family SMBus     | 4     | ichsmb     | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:0f12 | 15d9:0816 | Intel            | Atom Processor E3800/CE2700 Serie... | 3     | ichsmb     | [5A733D841D](<Server/XQAND/X10/X10SBA-L/C31CA5CEBF82/OPNSENSE-22.7/13.1-RELEASE/AMD64/5A733D841D>) |
| 8086:3a30 | 15d9:0404 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 3     | ichsmb     | [E7536E4A4C](<Server/Citrix/NSMPX/NSMPX-17500/A5177682AF7A/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/E7536E4A4C>) |
| 8086:8c22 | 17aa:30b0 | Intel            | 8 Series/C220 Series Chipset Fami... | 3     | ichsmb     | [D6111B8FF1](<Server/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/C9B365EFBC6F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D6111B8FF1>) |
| 8086:8d22 | 15d9:0857 | Intel            | C610/X99 series chipset SMBus Con... | 3     | ichsmb     | [E1EBA3B8F0](<Server/Supermicro/X10/X10SRA/0AF208B6DAE7/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E1EBA3B8F0>) |
| 8086:a123 | 1028:06aa | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [EFE3DBF989](<Server/Dell/PowerEdge/PowerEdge T130/1A6400B5BD8F/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/EFE3DBF989>) |
| 8086:a123 | 15d9:0896 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | ichsmb     | [A1DC602460](<Server/Supermicro/Super/Super Server/C3EAB3B58C16/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/A1DC602460>) |
| 8086:a123 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 3     | ichsmb     | [7BD99B62AB](<Server/Supermicro/Super/Super Server/A912B2977FCE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7BD99B62AB>) |
| 8086:a123 | 8086:7270 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [AB6E70ABCA](<Server/Intel/S1200/S1200SP/BF2910D7912E/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/AB6E70ABCA>) |
| 8086:a1a3 | 1028:07ca | Intel            | C620 Series Chipset Family SMBus     | 3     | ichsmb     | [0B239C3286](<Server/Dell/PowerEdge/PowerEdge R540/34807F166517/OPNSENSE-22.1.7/13.0-STABLE/AMD64/0B239C3286>) |
| 8086:a1a3 | 1734:1230 | Intel            | C620 Series Chipset Family SMBus     | 3     |            | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 8086:a323 | 15d9:1b11 | Intel            | Cannon Lake PCH SMBus Controller     | 3     | ichsmb     | [1AD1A2496B](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/89644753963D/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1AD1A2496B>) |
| 1002:4385 | 1028:0444 | AMD              | SBx00 SMBus Controller               | 2     | intsmb     | [C5B09B219B](<Server/Dell/PowerEdge/PowerEdge R815/3734F0F11574/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/C5B09B219B>) |
| 1002:4385 | 15d9:a811 | AMD              | SBx00 SMBus Controller               | 2     | intsmb     | [172BFE70B5](<Server/Supermicro/H8/H8DGU/D233858B79FC/MYBEE-13.1/13.1-RELEASE/AMD64/172BFE70B5>) |
| 1022:790b | 1458:1000 | AMD              | FCH SMBus Controller                 | 2     | intsmb     | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | ichsmb     | [D1CA9353B9](<Server/Intel/S1200/S1200BTL/35CEDE19C783/OPNSENSE-22.1/13.0-STABLE/AMD64/D1CA9353B9>) |
| 8086:1d70 | 1734:11b6 | Intel            | C600/X79 series chipset SMBus Con... | 2     |            | [A9D034FE42](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S8/2FAA16863AF6/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/A9D034FE42>) |
| 8086:269b | 8086:3476 | Intel            | 631xESB/632xESB/3100 Chipset SMBu... | 2     | ichsmb     | [411F470773](<Server/Intel/S5000/S5000PSL/8B6E5700823E/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/411F470773>) |
| 8086:3a30 | 15d9:0001 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 2     |            | [EDA1DF037B](<Server/Supermicro/X8/X8DT3/E3D8BF5430E2/FREEBSD-12.3-P5/12.2-RELEASE-P10/AMD64/EDA1DF037B>) |
| 8086:3a30 | 15d9:0400 | Intel            | 82801JI (ICH10 Family) SMBus Cont... | 2     | ichsmb     | [2F589ABF33](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/0AEF40CD9E4E/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/2F589ABF33>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:2284 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | hdac       | [5E635ADA09](<Server/Supermicro/Super/Super Server/0CBE12BB922F/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/5E635ADA09>) |
| 8086:0c0c | 17aa:30b0 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 3     | hdac       | [D6111B8FF1](<Server/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/C9B365EFBC6F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D6111B8FF1>) |
| 8086:8d20 | 15d9:0857 | Intel            | C610/X99 series chipset HD Audio ... | 3     | hdac       | [E1EBA3B8F0](<Server/Supermicro/X10/X10SRA/0AF208B6DAE7/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E1EBA3B8F0>) |
| 1002:aae0 | 1028:aae0 | AMD              | Baffin HDMI/DP Audio [Radeon RX 5... | 2     | hdac       | [C8DDB7DAE6](<Server/Dell/Precision/Precision 7820 Tower/4877A83C2118/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/C8DDB7DAE6>) |
| 8086:0f04 | 15d9:0816 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 2     | hdac       | [5A733D841D](<Server/XQAND/X10/X10SBA-L/C31CA5CEBF82/OPNSENSE-22.7/13.1-RELEASE/AMD64/5A733D841D>) |
| 8086:8c20 | 15d9:0805 | Intel            | 8 Series/C220 Series Chipset High... | 2     | hdac       | [2758B438C6](<Server/Supermicro/X10/X10SAE/4A17C592FC65/TRUENAS-12.2-P2/12.2-RELEASE-P2/AMD64/2758B438C6>) |
| 1002:aa38 | 1028:aa38 | AMD              | RV710/730 HDMI Audio [Radeon HD 4... | 1     | hdac       | [7E51DD7048](<Server/Supermicro/Super/Super Server/436CD64AB3E6/FREEBSD-12.3/12.3-RELEASE/AMD64/7E51DD7048>) |
| 1002:aab0 | 1043:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 1     |            | [6F95477DF3](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/6F95477DF3>) |
| 1002:aab0 | 1642:aab0 | AMD              | Oland/Hainan/Cape Verde/Pitcairn ... | 1     |            | [FFAA30BC08](<Server/Lenovo/ThinkStation/ThinkStation P720 30BAS1HX00/DE50C8A519F5/FREEBSD-13.0/13.0-RELEASE/AMD64/FFAA30BC08>) |
| 1022:1457 | 1022:1457 | AMD              | Family 17h (Models 00h-0fh) HD Au... | 1     | hdac       | [2C44E568EA](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/2C44E568EA>) |
| 10de:0371 | 108e:6676 | Nvidia           | MCP55 High Definition Audio          | 1     | hdac       | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 10de:0be3 | 10de:0847 | Nvidia           | High Definition Audio Controller     | 1     | hdac       | [1E7D58CD40](<Server/ASUSTek Computer/P8B-X/P8B-X series/5BF171BFBCD4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/1E7D58CD40>) |
| 10de:0be3 | 3842:1311 | Nvidia           | High Definition Audio Controller     | 1     | hdac       | [C1638ADFA6](<Server/Dell/PowerEdge/PowerEdge R210 II/BA8805CDE18D/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/C1638ADFA6>) |
| 10de:0beb | 19da:3166 | Nvidia           | GF104 High Definition Audio Contr... | 1     | hdac       | [E1EBA3B8F0](<Server/Supermicro/X10/X10SRA/0AF208B6DAE7/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E1EBA3B8F0>) |
| 10de:0e0b | 103c:079c | Nvidia           | GK106 HDMI Audio Controller          | 1     | hdac       | [A888AE8488](<Server/Supermicro/Super/Super Server/1FD8A6B1831A/FURYBSD-13.0-P10/13.0-RELEASE-P8/AMD64/A888AE8488>) |
| 10de:0e0b | 10de:097c | Nvidia           | GK106 HDMI Audio Controller          | 1     | hdac       | [B4999CA89F](<Server/Thomas-Krenn.AG/X10/X10DRi/E9E43391A317/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/B4999CA89F>) |
| 10de:0e0f | 1043:8572 | Nvidia           | GK208 HDMI/DP Audio Controller       | 1     | hdac       | [C1D4BBD74E](<Server/PSSC Labs/PowerServe/PowerServe/51E5C5BD0714/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/C1D4BBD74E>) |
| 10de:0e0f | 3842:2717 | Nvidia           | GK208 HDMI/DP Audio Controller       | 1     | hdac       | [1EB3ED1B04](<Server/Supermicro/Super/Super Server/A7D9FF96E34A/FREEBSD-12.1-P7/12.1-RELEASE/AMD64/1EB3ED1B04>) |
| 10de:0fb9 | 10de:11be | Nvidia           | GP107GL High Definition Audio Con... | 1     | hdac       | [4DA7433E8B](<Server/Supermicro/X10/X10SRA/901ACAE2F222/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/4DA7433E8B>) |
| 10de:0fb9 | 10de:1264 | Nvidia           | GP107GL High Definition Audio Con... | 1     | hdac       | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 10de:0fb9 | 10de:1c82 | Nvidia           | GP107GL High Definition Audio Con... | 1     | hdac       | [14A919AB3F](<Server/iXsystems/IXWS-733/IXWS-733TQ-665B-IXN/B02452E2BF49/FREEBSD-13.0-RC2/13.0-RC2/AMD64/14A919AB3F>) |
| 10de:0fb9 | 1462:8c96 | Nvidia           | GP107GL High Definition Audio Con... | 1     | hdac       | [360E63CC66](<Server/Supermicro/Super/Super Server/B1D111C1E9F6/FREEBSD-12.1-P2/12.1-RELEASE-P2/AMD64/360E63CC66>) |
| 10de:0fba | 3842:2951 | Nvidia           | GM206 High Definition Audio Contr... | 1     | hdac       | [9F6632DE8B](<Server/Supermicro/C7/C7Z170-OCE/1CCBCBB542C8/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/9F6632DE8B>) |
| 10de:0fbb | 103c:1153 | Nvidia           | GM204 High Definition Audio Contr... | 1     | hdac       | [93A8B87E1C](<Server/Supermicro/X10/X10DRi/4A89D595337C/HARDENEDBSD-13.0-ALPHA1-HBSD/13.0-ALPHA1-HBSD/AMD64/93A8B87E1C>) |
| 13f6:0111 | 13f6:0111 | C-Media Elect... | CMI8738/CMI8768 PCI Audio            | 1     | pcm        | [B4999CA89F](<Server/Thomas-Krenn.AG/X10/X10DRi/E9E43391A317/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/B4999CA89F>) |
| 13f6:0111 | 153b:1144 | C-Media Elect... | CMI8738/CMI8768 PCI Audio            | 1     | pcm        | [1E7D58CD40](<Server/ASUSTek Computer/P8B-X/P8B-X series/5BF171BFBCD4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/1E7D58CD40>) |
| 8086:06c8 | 15d9:1b6e | Intel            | Comet Lake PCH cAVS                  | 1     | hdac       | [2A9AC1E6EE](<Server/Supermicro/Super/Super Server/224D290BC26B/OPNSENSE-22.1.6/13.0-STABLE/AMD64/2A9AC1E6EE>) |
| 8086:0c0c | 15d9:0654 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | hdac       | [94E031B1E8](<Server/Supermicro/X10/X10SLQ/4CFBE661EBE9/OPNSENSE-22.1.6/13.0-STABLE/AMD64/94E031B1E8>) |
| 8086:0c0c | 15d9:0805 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     |            | [2758B438C6](<Server/Supermicro/X10/X10SAE/4A17C592FC65/TRUENAS-12.2-P2/12.2-RELEASE-P2/AMD64/2758B438C6>) |
| 8086:0c0c | 15d9:0842 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | hdac       | [734C98D27F](<Server/Supermicro/X10/X10SLH-N6-ST031/63E8035E3567/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/734C98D27F>) |
| 8086:160c | 15d9:0805 | Intel            | Broadwell-U Audio Controller         | 1     | hdac       | [D29048AE5D](<Server/Supermicro/X10/X10SAE/94D753821F6F/FREEBSD-12.2/12.2-RELEASE/AMD64/D29048AE5D>) |
| 8086:3a3e | 15d9:0006 | Intel            | 82801JI (ICH10 Family) HD Audio C... | 1     | hdac       | [37350B3AC0](<Server/Supermicro/X8/X8DTL/86E57128AC4E/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/37350B3AC0>) |
| 8086:8c20 | 15d9:0654 | Intel            | 8 Series/C220 Series Chipset High... | 1     | hdac       | [94E031B1E8](<Server/Supermicro/X10/X10SLQ/4CFBE661EBE9/OPNSENSE-22.1.6/13.0-STABLE/AMD64/94E031B1E8>) |
| 8086:9d71 | 15d9:098b | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [2EFE92BBA7](<Server/Supermicro/X11/X11SSN-L/BAB347016D47/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/2EFE92BBA7>) |
| 8086:a170 | 15d9:089f | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | hdac       | [F6CF8F7870](<Server/Supermicro/Super/Super Server/862E0901E10C/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/F6CF8F7870>) |
| 8086:a170 | 15d9:0902 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | hdac       | [9F6632DE8B](<Server/Supermicro/C7/C7Z170-OCE/1CCBCBB542C8/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/9F6632DE8B>) |
| 8086:a170 | 15d9:0907 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | hdac       | [A888AE8488](<Server/Supermicro/Super/Super Server/1FD8A6B1831A/FURYBSD-13.0-P10/13.0-RELEASE-P8/AMD64/A888AE8488>) |
| 8086:a170 | 15d9:0930 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | hdac       | [6244E44F35](<Server/Supermicro/X11/X11SSQ-L/64AECCC810F9/OPNSENSE-22.1.9/13.0-STABLE/AMD64/6244E44F35>) |
| 8086:a170 | 8086:a170 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | hdac       | [49D9F0E06A](<Server/Neousys Technology/Nuvo/Nuvo-5000/D47A2E3C3BC2/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/49D9F0E06A>) |
| 8086:a1f0 | 1028:0739 | Intel            | Lewisburg MROM 0                     | 1     | hdac       | [C8DDB7DAE6](<Server/Dell/Precision/Precision 7820 Tower/4877A83C2118/FREEBSD-13.1-STABLE/13.1-STABLE/AMD64/C8DDB7DAE6>) |
| 8086:a1f0 | 15d9:1b28 | Intel            | Lewisburg MROM 0                     | 1     | hdac       | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 8086:a1f0 | 17aa:1037 | Intel            | Lewisburg MROM 0                     | 1     | hdac       | [FFAA30BC08](<Server/Lenovo/ThinkStation/ThinkStation P720 30BAS1HX00/DE50C8A519F5/FREEBSD-13.0/13.0-RELEASE/AMD64/FFAA30BC08>) |
| 8086:a2f0 | 1028:07a2 | Intel            | 200 Series PCH HD Audio              | 1     | hdac       | [87EA02111D](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.1.8/13.0-STABLE/AMD64/87EA02111D>) |
| 8086:a348 | 15d9:1b09 | Intel            | Cannon Lake PCH cAVS                 | 1     | hdac       | [C9ABEB0DFE](<Server/Supermicro/Super/Super Server/DC73323CFA0B/OPNSENSE-20.7/12.1-RELEASE-P7-HBSD/AMD64/C9ABEB0DFE>) |

### Storage (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:c010 | 1000:00b2 | Broadcom / LSI   | PEX880xx PCIe Gen 4 Switch           | 1     |            | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 19a2:0712 | 103c:3376 | Emulex           | OneConnect 10Gb iSCSI Initiator (... | 1     |            | [74A4364A7F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/2AF460D1EA85/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/74A4364A7F>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c02 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 37    | ahci       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:8c02 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 23    | ahci       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c02 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ahci       | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c02 | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 19    | ahci       | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:19c2 | 15d9:0969 | Intel            | Atom Processor C3000 Series SATA ... | 18    | ahci       | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:8c02 | 1028:05e5 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | ahci       | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:19b2 | 15d9:0969 | Intel            | Atom Processor C3000 Series SATA ... | 14    | ahci       | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:8c02 | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | ahci       | [7D80C62813](<Server/Supermicro/X10/X10SLL-F/A4ACF508F8E6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7D80C62813>) |
| 8086:8d02 | 1028:0601 | Intel            | C610/X99 series chipset 6-Port SA... | 10    | ahci       | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:8d62 | 1028:0601 | Intel            | C610/X99 series chipset sSATA Con... | 10    | ahci       | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 1022:7901 | 15d9:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 9     | ahci       | [76519F54E9](<Server/Supermicro/Super/Super Server/B6CF39D94613/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/76519F54E9>) |
| 8086:22a3 | 15d9:0891 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | ahci       | [649D525FDB](<Server/Supermicro/Super/Super Server/A4D89EA96DC4/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/649D525FDB>) |
| 8086:a102 | 15d9:0884 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 9     | ahci       | [5E84D1A402](<Server/Supermicro/Super/Super Server/CD4E2EE0D75D/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/5E84D1A402>) |
| 8086:1d02 | 1028:04f8 | Intel            | C600/X79 series chipset 6-Port SA... | 8     | ahci       | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:3b22 | 1028:02a5 | Intel            | 5 Series/3400 Series Chipset 6 po... | 8     | ahci       | [340DC7255C](<Server/Dell/PowerEdge/PowerEdge R210/5E68DB36191B/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/340DC7255C>) |
| 8086:1d02 | 1028:04f7 | Intel            | C600/X79 series chipset 6-Port SA... | 7     | ahci       | [A1A15662D0](<Server/Dell/PowerEdge/PowerEdge R320/0A57FAA417FF/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/A1A15662D0>) |
| 8086:8c02 | 15d9:0803 | Intel            | 8 Series/C220 Series Chipset Fami... | 7     | ahci       | [6F95477DF3](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/6F95477DF3>) |
| 8086:a182 | 1028:07c9 | Intel            | C620 Series Chipset Family SATA C... | 7     | ahci       | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1d2 | 1028:07c9 | Intel            | C620 Series Chipset Family SSATA ... | 7     | ahci       | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1d2 | 15d9:0986 | Intel            | C620 Series Chipset Family SSATA ... | 7     | ahci       | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 1b4b:9230 | 1028:1fe2 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 6     | ahci       | [C34D5C2BE3](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C34D5C2BE3>) |
| 8086:1d02 | 1028:048c | Intel            | C600/X79 series chipset 6-Port SA... | 6     | ahci       | [B74220AEE1](<Server/Dell/PowerEdge/PowerEdge R720/886063A9496D/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/B74220AEE1>) |
| 8086:1d02 | 1028:04ce | Intel            | C600/X79 series chipset 6-Port SA... | 6     | ahci       | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 8086:a182 | 15d9:0986 | Intel            | C620 Series Chipset Family SATA C... | 6     | ahci       | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 1b4b:9230 | 1b4b:9230 | Marvell Techn... | 88SE9230 PCIe 2.0 x2 4-port SATA ... | 5     | ahci       | [588A497894](<Server/Supermicro/X10/X10SBA/D6CCFE818C24/OPNSENSE-22.1.9/13.0-STABLE/AMD64/588A497894>) |
| 8086:1d02 | 103c:18a9 | Intel            | C600/X79 series chipset 6-Port SA... | 5     | ahci       | [B9DF714117](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/0FE7DBEBF7BB/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B9DF714117>) |
| 8086:1d02 | 15d9:0660 | Intel            | C600/X79 series chipset 6-Port SA... | 5     | ahci       | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 8086:8d02 | 15d9:0834 | Intel            | C610/X99 series chipset 6-Port SA... | 5     | ahci       | [59FF2014E5](<Server/Supermicro/Super/Super Server/C53FD6545133/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/59FF2014E5>) |
| 8086:a352 | 15d9:1b0e | Intel            | Cannon Lake PCH SATA AHCI Controller | 5     | ahci       | [0D1EFA6544](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1101H-F Server/8F136F399B8E/OPNSENSE-22.1.3/13.0-STABLE/AMD64/0D1EFA6544>) |
| 1022:7901 | 1022:7901 | AMD              | FCH SATA Controller [AHCI mode]      | 4     | ahci       | [57721BF0F2](<Server/HPE/ProLiant/ProLiant MicroServer Gen10/734A66ADD4EA/OPNSENSE-22.1/13.0-STABLE/AMD64/57721BF0F2>) |
| 8086:1c02 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 4     | ahci       | [4D371914ED](<Server/Dell/PowerEdge/PowerEdge T110 II/1BB4A8B14EA4/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/4D371914ED>) |
| 8086:1f22 | 15d9:0820 | Intel            | Atom processor C2000 AHCI SATA2 C... | 4     | ahci       | [FB96378782](<Server/Supermicro/A1/A1SRM-2758F/F38A17AAB757/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FB96378782>) |
| 8086:1f32 | 15d9:0820 | Intel            | Atom processor C2000 AHCI SATA3 C... | 4     | ahci       | [FB96378782](<Server/Supermicro/A1/A1SRM-2758F/F38A17AAB757/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/FB96378782>) |
| 8086:2681 | 108e:4843 | Intel            | 631xESB/632xESB SATA AHCI Controller | 4     | ahci       | [51E87104A0](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/51E87104A0>) |
| 8086:3b22 | 1028:02a6 | Intel            | 5 Series/3400 Series Chipset 6 po... | 4     | ahci       | [C63D853ABC](<Server/Dell/PowerEdge/PowerEdge T110/ECD9FAFE3AEB/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/C63D853ABC>) |
| 8086:8c02 | 103c:330d | Intel            | 8 Series/C220 Series Chipset Fami... | 4     | ahci       | [6DE7C9CBA0](<Server/Hewlett-Packard/ProLiant/ProLiant DL320e Gen8 v2/52B6B236C9FB/OPNSENSE-22.1.5/13.0-STABLE/AMD64/6DE7C9CBA0>) |
| 8086:8c02 | 15d9:0806 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     | ahci       | [319819F81D](<Server/Supermicro/X10/X10SLM+-LN4F/9396CB95C705/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/319819F81D>) |
| 8086:8c02 | 8086:8c02 | Intel            | 8 Series/C220 Series Chipset Fami... | 4     | ahci       | [3494695F54](<Server/ASUSTek Computer/P9D-X/P9D-X Series/9942A2F29F13/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/3494695F54>) |
| 8086:8d02 | 1137:0067 | Intel            | C610/X99 series chipset 6-Port SA... | 4     | ahci       | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 8086:a102 | 103c:8165 | Intel            | Q170/Q150/B150/H170/H110/Z170/CM2... | 4     | ahci       | [32E9F95095](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/013B4CDFD8CC/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/32E9F95095>) |
| 8086:a182 | 1028:0716 | Intel            | C620 Series Chipset Family SATA C... | 4     | ahci       | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:a1d2 | 1028:0716 | Intel            | C620 Series Chipset Family SSATA ... | 4     | ahci       | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:a352 | 1028:088f | Intel            | Cannon Lake PCH SATA AHCI Controller | 4     | ahci       | [545DACB881](<Server/Dell/PowerEdge/PowerEdge R240/19A6101614C9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/545DACB881>) |
| 8086:3a22 | 1028:028c | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 3     | ahci       | [33AED2A5C1](<Server/Dell/PowerEdge/PowerEdge R410/74D50A975822/OPNSENSE-22.7/13.1-RELEASE/AMD64/33AED2A5C1>) |
| 8086:3a22 | 103c:330b | Intel            | 82801JI (ICH10 Family) SATA AHCI ... | 3     | ahci       | [289D2F383B](<Server/Hewlett-Packard/ProLiant/ProLiant DL180 G6/8E2A024CC455/FREEBSD-12.3-P7/12.3-RELEASE-P6/AMD64/289D2F383B>) |
| 8086:8d02 | 1028:0639 | Intel            | C610/X99 series chipset 6-Port SA... | 3     | ahci       | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 8086:8d02 | 103c:8030 | Intel            | C610/X99 series chipset 6-Port SA... | 3     | ahci       | [94513A53F8](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 Gen9/BABA8FFCB654/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/94513A53F8>) |
| 8086:8d02 | 15d9:0832 | Intel            | C610/X99 series chipset 6-Port SA... | 3     | ahci       | [331947AFE1](<Server/Supermicro/Super/Super Server/3657A16097B3/FREEBSD-13.0-P11/13.0-RELEASE-P7/AMD64/331947AFE1>) |
| 8086:8d02 | 15d9:0857 | Intel            | C610/X99 series chipset 6-Port SA... | 3     | ahci       | [E1EBA3B8F0](<Server/Supermicro/X10/X10SRA/0AF208B6DAE7/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E1EBA3B8F0>) |
| 8086:8d62 | 1028:0639 | Intel            | C610/X99 series chipset sSATA Con... | 3     | ahci       | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3a20 | 103c:330d | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 17    | atapci     | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:2921 | 1028:0235 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 14    | atapci     | [655A9E7AF2](<Server/Dell/PowerEdge/PowerEdge R710/14070C55BFA0/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/655A9E7AF2>) |
| 8086:2921 | 1028:0236 | Intel            | 82801IB (ICH9) 2 port SATA Contro... | 13    | atapci     | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:269e | 103c:31fe | Intel            | 631xESB/632xESB IDE Controller       | 10    | atapci     | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:3a20 | 1014:3a20 | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 8     | atapci     | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 8086:3a26 | 1014:3a26 | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 8     | atapci     | [1BC9E20B16](<Server/IBM/System/System x3550 M2 -[7946AC1]-/04590BF16709/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/1BC9E20B16>) |
| 8086:1d00 | 103c:18a9 | Intel            | C600/X79 series chipset 4-Port SA... | 6     | atapci     | [A5514D3F4B](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/6173205D3B06/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/A5514D3F4B>) |
| 8086:269e | 1028:01b2 | Intel            | 631xESB/632xESB IDE Controller       | 4     | atapci     | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 8086:269e | 108e:4843 | Intel            | 631xESB/632xESB IDE Controller       | 4     | atapci     | [51E87104A0](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/51E87104A0>) |
| 1095:0680 | 1095:0680 | Silicon Image    | PCI0680 Ultra ATA-133 Host Contro... | 3     | atapci     | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 8086:2680 | 1014:02dd | Intel            | 631xESB/632xESB/3100 Chipset SATA... | 3     | atapci     | [41D40D8752](<Server/IBM/System/System x3650 -[797941Y]-/B6A5CBBF3013/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/41D40D8752>) |
| 8086:2920 | 1028:023c | Intel            | 82801IR/IO/IH (ICH9R/DO/DH) 4 por... | 3     | atapci     | [A12907D76A](<Server/Dell/PowerEdge/PowerEdge R200/4AC27B58A736/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/A12907D76A>) |
| 1002:4390 | 1028:0444 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 2     | ahci       | [C5B09B219B](<Server/Dell/PowerEdge/PowerEdge R815/3734F0F11574/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/C5B09B219B>) |
| 1166:0214 | 103c:320b | Broadcom         | BCM5785 [HT1000] IDE                 | 2     | atapci     | [8A7564245E](<Server/Hewlett-Packard/ProLiant/ProLiant DL385 G2/F3AFD0BBC580/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/8A7564245E>) |
| 8086:1c00 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | atapci     | [6EBCD7C974](<Server/Dell/PowerEdge/PowerEdge R210 II/486BAFEA7B6D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/6EBCD7C974>) |
| 8086:1c08 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | atapci     | [6EBCD7C974](<Server/Dell/PowerEdge/PowerEdge R210 II/486BAFEA7B6D/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/6EBCD7C974>) |
| 8086:1c08 | 1043:8497 | Intel            | 6 Series/C200 Series Chipset Fami... | 2     | atapci     | [1E7D58CD40](<Server/ASUSTek Computer/P8B-X/P8B-X series/5BF171BFBCD4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/1E7D58CD40>) |
| 8086:24db | 1028:016c | Intel            | 82801EB/ER (ICH5/ICH5R) IDE Contr... | 2     | atapci     | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 8086:269e | 1014:02dd | Intel            | 631xESB/632xESB IDE Controller       | 2     | atapci     | [29C13EFBCC](<Server/IBM/System/System x3550 -[7978KLG]-/FD6E514E9ECE/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/29C13EFBCC>) |
| 8086:269e | 8086:3476 | Intel            | 631xESB/632xESB IDE Controller       | 2     | atapci     | [411F470773](<Server/Intel/S5000/S5000PSL/8B6E5700823E/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/411F470773>) |
| 8086:3a20 | 1028:028c | Intel            | 82801JI (ICH10 Family) 4 port SAT... | 2     | atapci     | [376AD93033](<Server/Dell/PowerEdge/PowerEdge R410/5CE12CC4F59C/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/376AD93033>) |
| 8086:3a26 | 1028:028c | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 2     | atapci     | [376AD93033](<Server/Dell/PowerEdge/PowerEdge R410/5CE12CC4F59C/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/376AD93033>) |
| 8086:3a26 | 103c:330d | Intel            | 82801JI (ICH10 Family) 2 port SAT... | 2     | atapci     | [CD1101B9A1](<Server/Hewlett-Packard/ProLiant/ProLiant DL320 G6/1008C35888CD/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/CD1101B9A1>) |
| 8086:3b20 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset 4 po... | 2     | atapci     | [8460816B1F](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/TRUENAS-12.2-P12/12.2-RELEASE-P12/AMD64/8460816B1F>) |
| 8086:3b26 | 1028:02a4 | Intel            | 5 Series/3400 Series Chipset 2 po... | 2     | atapci     | [8460816B1F](<Server/Dell/PowerEdge/PowerEdge T310/0EAF01173A25/TRUENAS-12.2-P12/12.2-RELEASE-P12/AMD64/8460816B1F>) |
| 1002:4390 | 15d9:ba11 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1     | ahci       | [98F39AFF26](<Server/Supermicro/H8/H8SCM/FA0A06B9AA5C/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/98F39AFF26>) |
| 1002:439c | 15d9:ba11 | AMD              | SB7x0/SB8x0/SB9x0 IDE Controller     | 1     | atapci     | [98F39AFF26](<Server/Supermicro/H8/H8SCM/FA0A06B9AA5C/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/98F39AFF26>) |
| 10de:036e | 108e:534b | Nvidia           | MCP55 IDE                            | 1     | atapci     | [1D2D5F5A1F](<Server/Sun Microsystems/Sun/Sun Fire X2200 M2/ADF2AE13F3B1/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/1D2D5F5A1F>) |
| 10de:036e | 108e:6676 | Nvidia           | MCP55 IDE                            | 1     | atapci     | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 10de:037f | 108e:534b | Nvidia           | MCP55 SATA Controller                | 1     | atapci     | [1D2D5F5A1F](<Server/Sun Microsystems/Sun/Sun Fire X2200 M2/ADF2AE13F3B1/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/1D2D5F5A1F>) |
| 10de:037f | 108e:6676 | Nvidia           | MCP55 SATA Controller                | 1     | atapci     | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 1166:0214 | 1028:01eb | Broadcom         | BCM5785 [HT1000] IDE                 | 1     | atapci     | [E98F23CD45](<Server/Dell/PowerEdge/PowerEdge SC1435/269A637D74C2/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/E98F23CD45>) |
| 1166:024b | 1028:01eb | Broadcom         | BCM5785 [HT1000] SATA (PATA/IDE M... | 1     | atapci     | [E98F23CD45](<Server/Dell/PowerEdge/PowerEdge SC1435/269A637D74C2/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/E98F23CD45>) |
| 197b:2368 | 197b:2368 | JMicron Techn... | JMB368 IDE controller                | 1     | atapci     | [F1E7CB51D7](<Server/Gigabyte Technology/GA-6/GA-6UPCP2-4-5/9FBC80D6457F/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/F1E7CB51D7>) |
| 8086:0f21 | 15d9:0816 | Intel            | Atom Processor E3800 Series SATA ... | 1     | atapci     | [5A733D841D](<Server/XQAND/X10/X10SBA-L/C31CA5CEBF82/OPNSENSE-22.7/13.1-RELEASE/AMD64/5A733D841D>) |
| 8086:1c00 | 1014:3a20 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | atapci     | [350DBDBDC6](<Server/IBM/System/System X3250 M4 -[2583B2A]-/4FFCD9BD27AF/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/350DBDBDC6>) |
| 8086:1c00 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | atapci     | [74A0F773FB](<Server/Dell/PowerEdge/PowerEdge T110 II/445D304675FA/OPNSENSE-22.1/13.0-STABLE/AMD64/74A0F773FB>) |
| 8086:1c00 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | atapci     | [1EBF1B71BD](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 G7/C0A00A1DE91B/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/1EBF1B71BD>) |
| 8086:1c00 | 1043:8497 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | atapci     | [1E7D58CD40](<Server/ASUSTek Computer/P8B-X/P8B-X series/5BF171BFBCD4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/1E7D58CD40>) |
| 8086:1c00 | 1043:8498 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | atapci     | [04C5C07D61](<Server/ASUSTek Computer/RS100/RS100-E7-PI2/7AD54C6BDDC2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/04C5C07D61>) |
| 8086:1c08 | 1014:3a26 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | atapci     | [350DBDBDC6](<Server/IBM/System/System X3250 M4 -[2583B2A]-/4FFCD9BD27AF/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/350DBDBDC6>) |
| 8086:1c08 | 1028:04de | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | atapci     | [74A0F773FB](<Server/Dell/PowerEdge/PowerEdge T110 II/445D304675FA/OPNSENSE-22.1/13.0-STABLE/AMD64/74A0F773FB>) |
| 8086:1c08 | 103c:330d | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | atapci     | [1EBF1B71BD](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 G7/C0A00A1DE91B/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/1EBF1B71BD>) |
| 8086:1d00 | 1028:048c | Intel            | C600/X79 series chipset 4-Port SA... | 1     | atapci     | [AB1C1B4AAD](<Server/Dell/PowerEdge/PowerEdge R720/5F41D08F8322/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/AB1C1B4AAD>) |
| 8086:1d00 | 1028:04ce | Intel            | C600/X79 series chipset 4-Port SA... | 1     | atapci     | [7CD73D4820](<Server/Others/0H47HH/0H47HH A07/82377467A588/OPNSENSE-22.1.2/13.0-STABLE/AMD64/7CD73D4820>) |
| 8086:1d00 | 1028:04f7 | Intel            | C600/X79 series chipset 4-Port SA... | 1     | atapci     | [9C2CA983AC](<Server/Dell/PowerEdge/PowerEdge R320/7B1C75B3FBB5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/9C2CA983AC>) |
| 8086:1d08 | 1028:048c | Intel            | C600/X79 series chipset 2-Port SA... | 1     | atapci     | [AB1C1B4AAD](<Server/Dell/PowerEdge/PowerEdge R720/5F41D08F8322/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/AB1C1B4AAD>) |
| 8086:1d08 | 1028:04ce | Intel            | C600/X79 series chipset 2-Port SA... | 1     | atapci     | [7CD73D4820](<Server/Others/0H47HH/0H47HH A07/82377467A588/OPNSENSE-22.1.2/13.0-STABLE/AMD64/7CD73D4820>) |
| 8086:1d08 | 1028:04f7 | Intel            | C600/X79 series chipset 2-Port SA... | 1     | atapci     | [9C2CA983AC](<Server/Dell/PowerEdge/PowerEdge R320/7B1C75B3FBB5/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/9C2CA983AC>) |
| 8086:24d1 | 1028:019a | Intel            | 82801EB (ICH5) SATA Controller       | 1     | atapci     | [8A115F25D1](<Server/Dell/PowerEdge/PowerEdge SC1425/4AE65F34FF47/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/8A115F25D1>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 12    | nvme       | [7BD99B62AB](<Server/Supermicro/Super/Super Server/A912B2977FCE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7BD99B62AB>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 5     | nvme       | [295FC511A6](<Server/Supermicro/Super/Super Server/F577C1A59868/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/295FC511A6>) |
| 144d:a80a | 144d:a801 | Samsung Elect... | NVMe SSD Controller PM9A1/PM9A3/9... | 5     | nvme       | [3B99C8F471](<Server/Supermicro/SYS-5018/SYS-5018D-FN8T/0D4712A5C4AC/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/3B99C8F471>) |
| 1db2:2302 | 1db2:2302 | ATP ELECTRONICS  |                                      | 5     | nvme       | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 3     | nvme       | [7622059198](<Server/Supermicro/Super/Super Server/D4840699C030/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/7622059198>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 2     | nvme       | [EE37B7ABF2](<Server/Supermicro/Super/Super Server/8C220E4D92D8/OPNSENSE-22.1.3/13.0-STABLE/AMD64/EE37B7ABF2>) |
| 14a4:22f1 | 1b4b:1093 | Lite-On Techn... | M8Pe Series NVMe SSD                 | 2     | nvme       | [D6312ECF58](<Server/Dell/PowerEdge/PowerEdge R210 II/2A7410DE6C46/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/D6312ECF58>) |
| 15b7:5002 | 15b7:5002 | SanDisk          | WD Black 2018/SN750 / PC SN720 NV... | 2     | nvme       | [A1CF339702](<Server/Supermicro/Super/Super Server/AEAD0BFD0A36/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/A1CF339702>) |
| 15b7:5006 | 15b7:5006 | SanDisk          | WD Black SN750 / PC SN730 NVMe SSD   | 2     | nvme       | [2A9AC1E6EE](<Server/Supermicro/Super/Super Server/224D290BC26B/OPNSENSE-22.1.6/13.0-STABLE/AMD64/2A9AC1E6EE>) |
| 8086:0953 | 8086:370d | Intel            | PCIe Data Center SSD                 | 2     | nvme       | [4710D6000D](<Server/Dell/PowerEdge/PowerEdge R730xd/A61A7DA79985/FREEBSD-11.4-P6/11.4-RELEASE-P5/AMD64/4710D6000D>) |
| 8086:2522 | 8086:3806 | Intel            | NVMe Optane Memory Series            | 2     | nvme       | [FC4265EB19](<Server/Supermicro/X10/X10SLH-F-X10SLM+-F/81F3BF3499E5/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/FC4265EB19>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 2     | nvme       | [C0C8D1F85E](<Server/Supermicro/Super/Super Server/73426A08BED9/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/C0C8D1F85E>) |
| 126f:2262 | 126f:2262 | Silicon Motion   | SM2262/SM2262EN SSD Controller       | 1     | nvme       | [93A8B87E1C](<Server/Supermicro/X10/X10DRi/4A89D595337C/HARDENEDBSD-13.0-ALPHA1-HBSD/13.0-ALPHA1-HBSD/AMD64/93A8B87E1C>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 1     | nvme       | [D3BA57CF29](<Server/Supermicro/Super/Super Server/98DE5D3C503D/OPNSENSE-22.1.8/13.0-STABLE/AMD64/D3BA57CF29>) |
| 1344:51a3 | 1344:1100 | Micron Techno... | 7300 MAX NVMe SSD                    | 1     | nvme       | [CE8759E747](<Server/Supermicro/Super/Super Server/413709855C98/FREEBSD-13.0-P6/13.0-RELEASE-P6/AMD64/CE8759E747>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 1     | nvme       | [E7B4F8151A](<Server/Supermicro/Super/Super Server/A22FC2D5FFA0/OPNSENSE-22.1.1/13.0-STABLE/AMD64/E7B4F8151A>) |
| 15b7:5003 | 15b7:5003 | SanDisk          | WD Blue SN500 / PC SN520 NVMe SSD    | 1     | nvme       | [76519F54E9](<Server/Supermicro/Super/Super Server/B6CF39D94613/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/76519F54E9>) |
| 15b7:5008 | 15b7:5008 | SanDisk          | PC SN530                             | 1     | nvme       | [1AD1A2496B](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102H-XE Server/89644753963D/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1AD1A2496B>) |
| 15b7:5009 | 15b7:5009 | SanDisk          | WD Blue SN550 NVMe SSD               | 1     | nvme       | [12E3F4C980](<Server/Supermicro/Super/Super Server/D5DD6E86EDD9/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/12E3F4C980>) |
| 1987:5008 | 1987:5008 | Phison Electr... | NVMe Storage Controller              | 1     | nvme       | [18EA6EC987](<Server/Supermicro/Super/Super Server/12E764A08838/FREENAS-11.3-P9/11.3-RELEASE-P9/AMD64/18EA6EC987>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 1     | nvme       | [15ACB1B742](<Server/Supermicro/Super/Super Server/D8406F1CBCAE/OPNSENSE-22.1.3/13.0-STABLE/AMD64/15ACB1B742>) |
| 1bb1:5018 | 1bb1:5018 | Seagate Techn... | FireCuda 530 SSD                     | 1     | nvme       | [BCF17B19EC](<Server/Supermicro/Super/Super Server/97EA669C2FE7/FREEBSD-13.1-P4/13.1-RELEASE/AMD64/BCF17B19EC>) |
| 1c5c:174a | 1c5c:174a | SK hynix         | Gold P31/PC711 NVMe Solid State D... | 1     | nvme       | [66C10B64CB](<Server/Supermicro/Super/Super Server/972BB3DC5295/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/66C10B64CB>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1     | nvme       | [B9B71BFB18](<Server/Supermicro/Super/Super Server/4AFA75DABEAB/OPNSENSE-22.1/13.0-STABLE/AMD64/B9B71BFB18>) |
| 1d97:1160 | 1d97:1160 | Shenzhen Long... | unknown                              | 1     | nvme       | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 1dee:2262 | 1dee:1dee | Biwin Storage... |                                      | 1     | nvme       | [93A8B87E1C](<Server/Supermicro/X10/X10DRi/4A89D595337C/HARDENEDBSD-13.0-ALPHA1-HBSD/13.0-ALPHA1-HBSD/AMD64/93A8B87E1C>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller BG4              | 1     | nvme       | [BB5A9B3A6F](<Server/Supermicro/Super/Super Server/218F10B4705D/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/BB5A9B3A6F>) |
| 1e0f:0007 | 1e0f:0001 | KIOXIA           | NVMe SSD Controller Cx6              | 1     | nvme       | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 2646:5008 | 2646:5008 | Kingston Tech... | U-SNS8154P3 NVMe SSD                 | 1     | nvme       | [89C0064AEB](<Server/Supermicro/Super/Super Server/038CA4B887EB/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/89C0064AEB>) |
| 2646:500e | 2646:500e | Kingston Tech... | SNVS2000G [NV1 NVMe PCIe SSD 2TB]    | 1     | nvme       | [32E9F95095](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/013B4CDFD8CC/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/32E9F95095>) |
| 8086:0953 | 108e:370b | Intel            | PCIe Data Center SSD                 | 1     | nvme       | [7CEC65D8F8](<Server/Dell/PowerEdge/PowerEdge R720xd/A57D7CC55C88/TRUENAS-12.2-P6/12.2-RELEASE-P6/AMD64/7CEC65D8F8>) |
| 8086:0953 | 8086:3705 | Intel            | PCIe Data Center SSD                 | 1     | nvme       | [0E21A1EEB0](<Server/Supermicro/Super/Super Server/59CFCF60EA83/MYBEE-13.1/13.1-RELEASE/AMD64/0E21A1EEB0>) |
| 8086:2525 | 8086:380a | Intel            |                                      | 1     | nvme       | [638B27BC34](<Server/Supermicro/Super/Super Server/CF1692AC0104/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/638B27BC34>) |
| 8086:2700 | 8086:3900 | Intel            | Optane SSD 900P Series               | 1     | nvme       | [2F589ABF33](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/0AEF40CD9E4E/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/2F589ABF33>) |
| 8086:2700 | 8086:3901 | Intel            | Optane SSD 900P Series               | 1     | nvme       | [D778079C7F](<Server/Dell/PowerEdge/PowerEdge R7515/23F1145279FD/HARDENEDBSD-13.0-STABLE-HBSD/13.0-STABLE-HBSD/AMD64/D778079C7F>) |
| 8086:f1a6 | 8086:390b | Intel            | SSD Pro 7600p/760p/E 6100p Series    | 1     | nvme       | [4BCC55D57F](<Server/Supermicro/SYS-E300/SYS-E300-8D/37053876BD86/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/4BCC55D57F>) |
| 8086:f1a8 | 8086:390d | Intel            | SSD 660P Series                      | 1     | nvme       | [CF2E66B6AA](<Server/Supermicro/X10/X10SLL-F/A57790A3890F/FREEBSD-12.2/12.2-RELEASE/AMD64/CF2E66B6AA>) |
| c0a9:5403 | c0a9:1100 | Micron/Crucia... | NVMe Controller                      | 1     | nvme       | [2C44E568EA](<Server/Supermicro/Super/Super Server/CA85E9DB0093/OPNSENSE-22.1/13.0-STABLE/AMD64/2C44E568EA>) |
| c0a9:5403 | c0a9:2100 | Micron/Crucia... | NVMe Controller                      | 1     | nvme       | [C41D989A06](<Server/Supermicro/Super/Super Server/0EDACDF894F4/FREEBSD-12.2/12.2-RELEASE/AMD64/C41D989A06>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 1     | nvme       | [872A05C140](<Server/Supermicro/Super/Super Server/AB927389C02E/OPNSENSE-22.1.5/13.0-STABLE/AMD64/872A05C140>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0060 | 1028:1f0c | Broadcom / LSI   | MegaRAID SAS 1078                    | 23    | mfi        | [2779D78756](<Server/Dell/PowerEdge/PowerEdge R710/EB4913CD4F4F/FREEBSD-13.1-P2/13.1-RELEASE-P1/AMD64/2779D78756>) |
| 103c:323a | 103c:3245 | Hewlett-Packard  | Smart Array G6 controllers           | 23    | ciss       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 1000:005b | 1028:1f34 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 16    | mfi        | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 1000:005b | 1028:1f38 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 14    | mfi        | [6EFD22E598](<Server/Dell/PowerEdge/PowerEdge R420/787A628CC8C0/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/6EFD22E598>) |
| 1000:0079 | 1028:1f17 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 13    | mfi        | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 1000:0073 | 1028:1f51 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 11    | mfi        | [AD01FBD5A3](<Server/Dell/PowerEdge/PowerEdge R620/C6E9475E3E9E/OPNSENSE-22.1.10/13.0-STABLE/AMD64/AD01FBD5A3>) |
| 1000:005f | 1028:1f44 | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 10    | mfi        | [C5AF7BF9E5](<Server/Dell/PowerEdge/PowerEdge R340/3C18F7464176/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/C5AF7BF9E5>) |
| 103c:323b | 103c:3354 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 9     | ciss       | [B9DF714117](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/0FE7DBEBF7BB/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B9DF714117>) |
| 1000:005d | 1028:1f49 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 8     | mfi        | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 1000:005d | 1028:1f47 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 6     | mfi        | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 1000:005f | 1028:1f4b | Broadcom / LSI   | MegaRAID SAS-3 3008 [Fury]           | 6     | mfi        | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 103c:3230 | 103c:3235 | Hewlett-Packard  | Smart Array Controller               | 6     | ciss       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 9005:0286 | 1014:9580 | Adaptec          | AAC-RAID (Rocket)                    | 5     | aac        | [41D40D8752](<Server/IBM/System/System x3650 -[797941Y]-/B6A5CBBF3013/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/41D40D8752>) |
| 1000:0072 | 1734:1177 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 4     | mps        | [A760A87C5D](<Server/Swyx Solutions/SwyxExpress/SwyxExpress/0631091053FD/FREEBSD-13.1-P1/13.1-RELEASE/AMD64/A760A87C5D>) |
| 103c:3230 | 103c:3234 | Hewlett-Packard  | Smart Array Controller               | 4     | ciss       | [1A754B2A9E](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 G5/851ACF3B4A4E/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/1A754B2A9E>) |
| 103c:323a | 103c:3243 | Hewlett-Packard  | Smart Array G6 controllers           | 4     | ciss       | [289D2F383B](<Server/Hewlett-Packard/ProLiant/ProLiant DL180 G6/8E2A024CC455/FREEBSD-12.3-P7/12.3-RELEASE-P6/AMD64/289D2F383B>) |
| 8086:1c04 | 1028:04dd | Intel            | 6 Series/C200 Series Desktop SATA... | 4     | ahci       | [0325ADE874](<Server/Dell/PowerEdge/PowerEdge R210 II/092D9B4C961E/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/0325ADE874>) |
| 1000:005d | 1028:1f42 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 3     | mrsas      | [0B239C3286](<Server/Dell/PowerEdge/PowerEdge R540/34807F166517/OPNSENSE-22.1.7/13.0-STABLE/AMD64/0B239C3286>) |
| 1000:0079 | 1014:03c7 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 3     | mfi        | [8BBC599CDD](<Server/IBM/System/System x3650 M3 -[7945K3G]-/4E22FDB71865/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/8BBC599CDD>) |
| 1000:10e2 | 1028:2176 | Broadcom / LSI   | MegaRAID 12GSAS/PCIe Secure SAS39xx  | 3     | mrsas      | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 103c:323b | 103c:3351 | Hewlett-Packard  | Smart Array Gen8 Controllers         | 3     | ciss       | [0DA59DFF8F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360e Gen8/5D50CBD4DBDB/OPNSENSE-22.7.5/13.1-RELEASE-P2/AMD64/0DA59DFF8F>) |
| 8086:2826 | 17aa:30b0 | Intel            | C600/X79 series chipset SATA RAID... | 3     | ahci       | [D6111B8FF1](<Server/Lenovo/70F8S01E00/70F8S01E00 ThinkServer RS140/C9B365EFBC6F/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D6111B8FF1>) |
| 9005:0285 | 108e:0286 | Adaptec          | AAC-RAID                             | 3     | aac        | [51E87104A0](<Server/Sun Microsystems/Sun/Sun Fire X4150/551885437D04/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/51E87104A0>) |
| 1000:0014 | 1734:1238 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3516            | 2     | mrsas      | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 1000:0016 | 1137:0210 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [2633EAF68B](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M5SX/41B605A42DA4/OPNSENSE-22.10/13.1-RELEASE-P2/AMD64/2633EAF68B>) |
| 1000:005d | 1000:9363 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 2     | mfi        | [AB6E70ABCA](<Server/Intel/S1200/S1200SP/BF2910D7912E/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/AB6E70ABCA>) |
| 1000:0073 | 1014:03b1 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 2     | mfi        | [71D412D254](<Server/IBM/System/System x3250 M3 -[4252K3G]-/0EA3D6B9F663/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/71D412D254>) |
| 1000:0073 | 1734:1177 | Broadcom / LSI   | MegaRAID SAS 2008 [Falcon]           | 2     | mfi        | [3D46E0EACE](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S6/02405A2DD385/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/3D46E0EACE>) |
| 1000:0079 | 1014:03b2 | Broadcom / LSI   | MegaRAID SAS 2108 [Liberator]        | 2     | mfi        | [F723CAE263](<Server/IBM/System/System x3550 M3 -[7944ZJN]-/B6E6FA55AFB2/FREEBSD-12.2-P6/12.2-RELEASE-P3/AMD64/F723CAE263>) |
| 1000:00ce | 1137:0197 | Broadcom / LSI   | MegaRAID SAS-3 3316 [Intruder]       | 2     | mrsas      | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 1028:0015 | 1028:1f03 | Dell             | PowerEdge Expandable RAID control... | 2     | mfi        | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 103c:3230 | 103c:3223 | Hewlett-Packard  | Smart Array Controller               | 2     | ciss       | [7DFAEC9B01](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/1062B96A5966/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/7DFAEC9B01>) |
| 103c:3239 | 103c:21c5 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 2     | ciss       | [D35F62BA44](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/F3C30038FE1D/FREEBSD-12.1-P6/12.1-RELEASE-P1/AMD64/D35F62BA44>) |
| 103c:3239 | 103c:21cb | Hewlett-Packard  | Smart Array Gen9 Controllers         | 2     | ciss       | [D35F62BA44](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/F3C30038FE1D/FREEBSD-12.1-P6/12.1-RELEASE-P1/AMD64/D35F62BA44>) |
| 103c:323a | 103c:3241 | Hewlett-Packard  | Smart Array G6 controllers           | 2     | ciss       | [379FCF9804](<Server/Hewlett-Packard/ProLiant/ProLiant DL120 G6/8034C079A069/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/379FCF9804>) |
| 13c1:1004 | 13c1:1004 | 3ware            | 9650SE SATA-II RAID PCIe             | 2     | twa        | [EDA1DF037B](<Server/Supermicro/X8/X8DT3/E3D8BF5430E2/FREEBSD-12.3-P5/12.2-RELEASE-P10/AMD64/EDA1DF037B>) |
| 8086:2826 | 15d9:0921 | Intel            | C600/X79 series chipset SATA RAID... | 2     | ahci       | [3B99C8F471](<Server/Supermicro/SYS-5018/SYS-5018D-FN8T/0D4712A5C4AC/OPNSENSE-22.7.1/13.1-RELEASE/AMD64/3B99C8F471>) |
| 8086:2826 | 8086:7270 | Intel            | C600/X79 series chipset SATA RAID... | 2     | ahci       | [E8F3ACF486](<Server/Supermicro/Super/Super Server/6BC8D1FC3293/OPNSENSE-22.1.8/13.0-STABLE/AMD64/E8F3ACF486>) |
| 8086:8d06 | 1590:009c | Intel            | C610/X99 series chipset SATA Cont... | 2     | ahci       | [F91D50AB48](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/10EC3EA2C607/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F91D50AB48>) |
| 8086:8d66 | 1590:009d | Intel            | C610/X99 series chipset sSATA Con... | 2     | ahci       | [F91D50AB48](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/10EC3EA2C607/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F91D50AB48>) |
| 8086:a186 | 1137:0101 | Intel            | C620 Series Chipset Family SATA C... | 2     | ahci       | [2633EAF68B](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M5SX/41B605A42DA4/OPNSENSE-22.10/13.1-RELEASE-P2/AMD64/2633EAF68B>) |
| 9005:028b | 9005:0301 | Adaptec          | Series 6 - 6G SAS/PCIe 2             | 2     | aacraid    | [0546131058](<Server/Intel/S5000/S5000PSL/96DC9B4589D1/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/0546131058>) |
| 1000:0016 | 1d49:0601 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 1     | mrsas      | [311C32E56E](<Server/Lenovo/ThinkSystem/ThinkSystem SR650 -[7X06CTO1WW]-/C2AF82A6E1C5/FREEBSD-13.1/13.1-RELEASE/AMD64/311C32E56E>) |
| 1000:0017 | 17aa:103a | Broadcom / LSI   | MegaRAID Tri-Mode SAS3408            | 1     | mrsas      | [FFAA30BC08](<Server/Lenovo/ThinkStation/ThinkStation P720 30BAS1HX00/DE50C8A519F5/FREEBSD-13.0/13.0-RELEASE/AMD64/FFAA30BC08>) |
| 1000:0017 | 1d49:0500 | Broadcom / LSI   | MegaRAID Tri-Mode SAS3408            | 1     | mrsas      | [46C59D0DE8](<Server/Lenovo/ThinkSystem/ThinkSystem SR530 -[7X08CTO1WW]-/EF5F31DB406A/OPNSENSE-22.1.5/13.0-STABLE/AMD64/46C59D0DE8>) |
| 1000:005b | 1000:9291 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mrsas      | [DDE6AF4613](<Server/Dell/PowerEdge/PowerEdge T150/140EB7015AAB/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/DDE6AF4613>) |
| 1000:005b | 1014:0412 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mfi        | [92ED5993F4](<Server/IBM/System/System x3650 M4: -[7915AC1]-/9CD691E97074/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/92ED5993F4>) |
| 1000:005b | 1028:1f2d | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mrsas      | [AC57AB9EF6](<Server/Dell/PowerVault/PowerVault NX3200/EF19A7A28AB2/FREEBSD-11.4-P4/11.4-RELEASE-P3/AMD64/AC57AB9EF6>) |
| 1000:005b | 1734:11d3 | Broadcom / LSI   | MegaRAID SAS 2208 [Thunderbolt]      | 1     | mfi        | [ADE1272EE4](<Server/Fujitsu/PRIMERGY/PRIMERGY TX120 S3p/6465FC336AEC/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/ADE1272EE4>) |
| 1000:005d | 1000:9361 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mfi        | [B4999CA89F](<Server/Thomas-Krenn.AG/X10/X10DRi/E9E43391A317/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/B4999CA89F>) |

### Storage/sas (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0072 | 1000:3020 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 11    | mps        | [2BD1529913](<Server/Supermicro/MBD-X8/MBD-X8DT6-A-IS018/9FC8D16648D3/FREEBSD-13.1/13.1-RELEASE/AMD64/2BD1529913>) |
| 1000:0072 | 1028:1f1c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 8     | mps        | [10CA365B40](<Server/EXTRA Computer/X10/X10SLH-F-X10SLM+-F/6AAC242150BC/FREEBSD-13.1-P1/13.1-RELEASE-P1/AMD64/10CA365B40>) |
| 8086:1d6b | 15d9:0660 | Intel            | C602 chipset 4-Port SATA Storage ... | 6     | isci       | [D21C2D1A10](<Server/SYNNEX/HYVE-ZEUS/HYVE-ZEUS/2A05CA1BF242/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/D21C2D1A10>) |
| 1000:0072 | 1028:1f1d | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mps        | [0C40D38F1D](<Server/Dell/PowerEdge/PowerEdge R310/FA9EEF8E1FF1/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/0C40D38F1D>) |
| 1000:0072 | 1028:1f1e | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 5     | mps        | [655A9E7AF2](<Server/Dell/PowerEdge/PowerEdge R710/14070C55BFA0/OPNSENSE-22.7.7/13.1-RELEASE-P3/AMD64/655A9E7AF2>) |
| 1000:0097 | 1028:1f53 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 4     | mpr        | [30602E7478](<Server/Dell/PowerEdge/PowerEdge R630/24116AF6B008/OPNSENSE-22.1.10/13.0-STABLE/AMD64/30602E7478>) |
| 1000:0087 | 1028:1f38 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 3     | mps        | [8E2465430E](<Server/Dell/PowerEdge/PowerEdge R620/23D3D26B3084/OPNSENSE-22.7.6/13.1-RELEASE/AMD64/8E2465430E>) |
| 1000:0016 | 1028:1fcb | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [C34D5C2BE3](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C34D5C2BE3>) |
| 1000:0016 | 1028:1fcd | Broadcom / LSI   | MegaRAID Tri-Mode SAS3508            | 2     | mrsas      | [AA44179A5F](<Server/Dell/PowerEdge/PowerEdge R640/FB4118FD56BA/FREEBSD-12.2-P1/12.2-RELEASE-P1/AMD64/AA44179A5F>) |
| 1000:0072 | 103c:3371 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [D1FDEF3D4D](<Server/Dell/PowerEdge/PowerEdge 2950/CCD12DA5863D/TRUENAS-12.2-P11/12.2-RELEASE-P11/AMD64/D1FDEF3D4D>) |
| 1000:0072 | 15d9:0400 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 2     | mps        | [2BD1529913](<Server/Supermicro/MBD-X8/MBD-X8DT6-A-IS018/9FC8D16648D3/FREEBSD-13.1/13.1-RELEASE/AMD64/2BD1529913>) |
| 1000:0087 | 1000:3020 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mps        | [0A771C7B0E](<Server/Supermicro/X8/X8DT3/E0F35359D04C/FREEBSD-12.1-P10/12.1-RELEASE/AMD64/0A771C7B0E>) |
| 1000:0087 | 1028:1f34 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 2     | mps        | [FBCC442D47](<Server/Dell/PowerEdge/PowerEdge R720xd/9494C365C719/TRUENAS-12.2-P9/12.2-RELEASE-P9/AMD64/FBCC442D47>) |
| 1000:0097 | 1028:1f46 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 2     | mpr        | [BA13BBECFD](<Server/Dell/PowerEdge/PowerEdge R730/BC55DA270D03/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/BA13BBECFD>) |
| 103c:3239 | 103c:21c7 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 2     | ciss       | [F91D50AB48](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/10EC3EA2C607/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F91D50AB48>) |
| 1000:005d | 19e5:da07 | Broadcom / LSI   | MegaRAID SAS-3 3108 [Invader]        | 1     | mrsas      | [AC2C7107D3](<Server/HUAWEI/RH2288H/RH2288H V3/FFCB8F761596/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/AC2C7107D3>) |
| 1000:0064 | 1000:30c0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mps        | [2F589ABF33](<Server/Supermicro/X8/X8DTH-i-6-iF-6F/0AEF40CD9E4E/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/2F589ABF33>) |
| 1000:0064 | 1000:30d0 | Broadcom / LSI   | SAS2116 PCI-Express Fusion-MPT SA... | 1     | mps        | [CF2E66B6AA](<Server/Supermicro/X10/X10SLL-F/A57790A3890F/FREEBSD-12.2/12.2-RELEASE/AMD64/CF2E66B6AA>) |
| 1000:0070 | 1000:3010 | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 1     | mps        | [E83E6A0CD8](<Server/Supermicro/X8/X8DTU/BFC393DAED02/FREEBSD-13.0-P4/13.0-RELEASE-P3/AMD64/E83E6A0CD8>) |
| 1000:0070 | 1014:040e | Broadcom / LSI   | SAS2004 PCI-Express Fusion-MPT SA... | 1     | mps        | [7F8395E815](<Server/IBM/System/System x3250 M5: -[5458Z1P]-/EABBAC4B4C68/OPNSENSE-22.1.7/13.0-STABLE/AMD64/7F8395E815>) |
| 1000:0072 | 1000:0072 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [7CC48A8D08](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G7/9E11D24B206A/FREEBSD-12.1/12.1-RELEASE/AMD64/7CC48A8D08>) |
| 1000:0072 | 1000:3040 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [4763FE7595](<Server/Intel/S1200/S1200RP_SE/4DF73AF97478/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/4763FE7595>) |
| 1000:0072 | 1000:3060 | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [F88EAF06AC](<Server/Intel/S1200/S1200BTL/BD51E5A20141/FREEBSD-12.1-P8/12.1-RELEASE-P8/AMD64/F88EAF06AC>) |
| 1000:0072 | 1014:03cb | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [16C4967DC7](<Server/Dell/PowerEdge/PowerEdge R720/2B0C8CA5C01F/FREEBSD-13.0-P3/13.0-RELEASE-P3/AMD64/16C4967DC7>) |
| 1000:0072 | 1043:843c | Broadcom / LSI   | SAS2008 PCI-Express Fusion-MPT SA... | 1     | mps        | [D50484387C](<Server/ASUSTek Computer/P8B-E/P8B-E Series/9F223A3AC70D/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/D50484387C>) |
| 1000:0086 | 15d9:0691 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [D26EBDBB9F](<Server/Supermicro/X10/X10SL7-F/17461935FBAF/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/D26EBDBB9F>) |
| 1000:0087 | 1000:3030 | Broadcom / LSI   | SAS2308 PCI-Express Fusion-MPT SAS-2 | 1     | mps        | [E59D5D41A5](<Server/Hewlett-Packard/ProLiant/ProLiant SE326M1R2/9702C33A6606/FREENAS-11.3-P7/11.3-RELEASE-P7/AMD64/E59D5D41A5>) |
| 1000:0090 | 1137:0155 | Broadcom / LSI   | SAS3108 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [5D94552E31](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/5D94552E31>) |
| 1000:0097 | 1000:30e0 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [93E2466FC6](<Server/Gigabyte Technology/R272/R272-Z31-00/48F7A95BD754/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/93E2466FC6>) |
| 1000:0097 | 15d9:0808 | Broadcom / LSI   | SAS3008 PCI-Express Fusion-MPT SAS-3 | 1     | mpr        | [6C4D7ACEEC](<Server/Supermicro/Super/Super Server/B1D0F2EE5D00/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/6C4D7ACEEC>) |
| 103c:3239 | 103c:21c8 | Hewlett-Packard  | Smart Array Gen9 Controllers         | 1     | ciss       | [C2BB148E8A](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 Gen9/37E855C98CE1/FREEBSD-12.2-P2/12.2-RELEASE-P2/AMD64/C2BB148E8A>) |
| 8086:1d6a | 8086:3583 | Intel            | C600/X79 series chipset Dual 4-Po... | 1     | isci       | [474B0E44EA](<Server/Wortmann AG/TERRA/TERRA Server/8361012A53E8/FREEBSD-12.1-P10/12.1-RELEASE-P10/AMD64/474B0E44EA>) |
| 8086:1d6b | 152d:899b | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [A4980E3EA4](<Server/Quanta/JASPER/JASPER12/E990713EF0FC/FREEBSD-12.2-P6/12.2-RELEASE-P4/AMD64/A4980E3EA4>) |
| 8086:1d6b | 15d9:062f | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [A3BCB2FCF1](<Server/Bull SAS/bullx/bullx/4C113D9600C5/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/A3BCB2FCF1>) |
| 8086:1d6b | 15d9:0636 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [BDFCE3DEFF](<Server/Supermicro/X9/X9DRW/6E67CB72AA76/OPNSENSE-22.1.8/13.0-STABLE/AMD64/BDFCE3DEFF>) |
| 8086:1d6b | 15d9:0663 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [89DA730497](<Server/Supermicro/X9/X9SRW-F/7C541E7162CF/FREEBSD-13.0-P11/13.0-RELEASE-P11/AMD64/89DA730497>) |
| 8086:1d6b | 15d9:0703 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [1F4D1E4607](<Server/Supermicro/X9/X9DBL-3F-X9DBL-iF/C3731809970F/FREEBSD-12.1-P4/12.1-RELEASE-P3/AMD64/1F4D1E4607>) |
| 8086:1d6b | 1734:11b6 | Intel            | C602 chipset 4-Port SATA Storage ... | 1     | isci       | [D6AFDBD24B](<Server/Fujitsu/PRIMERGY/PRIMERGY RX300 S7/88B18CA93984/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/D6AFDBD24B>) |
| 8086:1d6f | 1734:11b6 | Intel            | C600/X79 series chipset 4-Port SA... | 1     | isci       | [A9D034FE42](<Server/Fujitsu/PRIMERGY/PRIMERGY RX200 S8/2FAA16863AF6/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/A9D034FE42>) |
| 9005:028f | 103c:0600 | Adaptec          | Smart Storage PQI SAS                | 1     | smartpqi   | [3A932D738C](<Server/HPE/ProLiant/ProLiant ML110 Gen10/819B1E7CD686/OPNSENSE-22.1.6/13.0-STABLE/AMD64/3A932D738C>) |
| 9005:028f | 103c:0602 | Adaptec          | Smart Storage PQI SAS                | 1     | smartpqi   | [01594B89A6](<Server/HPE/ProLiant/ProLiant DL380 Gen10/7D92A29D1AAE/OPNSENSE-21.1.9/12.1-RELEASE-P19-HBSD/AMD64/01594B89A6>) |
| 9005:028f | 103c:0654 | Adaptec          | Smart Storage PQI SAS                | 1     | smartpqi   | [9C250AE514](<Server/HPE/ProLiant/ProLiant DL20 Gen10/E599CE82055D/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/9C250AE514>) |
| 9005:028f | 103c:1100 | Adaptec          | Smart Storage PQI SAS                | 1     | smartpqi   | [D1E6144816](<Server/HPE/ProLiant/ProLiant DL380 Gen10/208B63D62A2B/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/D1E6144816>) |
| 9005:8081 | 9005:0800 | Adaptec          | PMC-Sierra PM8001 SAS HBA [Series... | 1     |            | [3494695F54](<Server/ASUSTek Computer/P9D-X/P9D-X Series/9942A2F29F13/FREEBSD-13.1-P2/13.1-RELEASE-P2/AMD64/3494695F54>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1000:0058 | 1028:1f0f | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 5     | mpt        | [847CA0ACB9](<Server/Dell/PowerEdge/PowerEdge R410/AA3B52468CEC/OPNSENSE-22.1.6/13.0-STABLE/AMD64/847CA0ACB9>) |
| 1425:5501 |           | Chelsio Commu... | T520-CR Unified Wire Storage Cont... | 5     |            | [1EB31C7E35](<Server/Hewlett-Packard/ProLiant/ProLiant DL20 Gen9/48782FD0A577/OPNSENSE-22.7.3/13.1-RELEASE-P2/AMD64/1EB31C7E35>) |
| 1000:0058 | 1014:0394 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mpt        | [5F9F2C2232](<Server/IBM/System/System x -[79463ag]-/9FE86345EDC2/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/5F9F2C2232>) |
| 1000:0058 | 1028:1f0e | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 3     | mpt        | [1AEB1BF3BF](<Server/Dell/PowerEdge/PowerEdge R200/7889930FFF0B/OPNSENSE-22.1.8/13.0-STABLE/AMD64/1AEB1BF3BF>) |
| 1425:4501 |           | Chelsio Commu... | T420-CR Unified Wire Storage Cont... | 3     |            | [70A786B8B5](<Server/Supermicro/X10/X10SLM+-LN4F/F4A1F01A1AAE/OPNSENSE-22.7.2/13.1-RELEASE-P1/AMD64/70A786B8B5>) |
| 1000:0054 | 1028:1f09 | Broadcom / LSI   | SAS1068 PCI-X Fusion-MPT SAS         | 2     | mpt        | [E98F23CD45](<Server/Dell/PowerEdge/PowerEdge SC1435/269A637D74C2/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/E98F23CD45>) |
| 1000:0058 | 1028:1f10 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 2     | mpt        | [5D650E34E4](<Server/Dell/PowerEdge/PowerEdge R410/E1AADBB39AD2/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/5D650E34E4>) |
| 1000:0030 | 1000:10b0 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [970467EFEF](<Server/Sun Microsystems/Sun/Sun Ultra 40 M2 Workstation/C6534686A372/FREEBSD-12.1-P5/12.1-RELEASE-P5/AMD64/970467EFEF>) |
| 1000:0030 | 1000:50c0 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [7E51DD7048](<Server/Supermicro/Super/Super Server/436CD64AB3E6/FREEBSD-12.3/12.3-RELEASE/AMD64/7E51DD7048>) |
| 1000:0030 | 1028:016c | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 1000:0030 | 103c:322a | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [8A7564245E](<Server/Hewlett-Packard/ProLiant/ProLiant DL385 G2/F3AFD0BBC580/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/8A7564245E>) |
| 1000:0030 | 1734:1041 | Broadcom / LSI   | 53c1030 PCI-X Fusion-MPT Dual Ult... | 1     | mpt        | [ADB972BF8E](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX200S2/C657395B089D/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/ADB972BF8E>) |
| 1000:0058 | 103c:3229 | Broadcom / LSI   | SAS1068E PCI-Express Fusion-MPT SAS  | 1     | mpt        | [AE37F4EB2D](<Server/Hewlett-Packard/ProLiant/ProLiant DL380 G5/2E9FE6581089/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/AE37F4EB2D>) |
| 1425:5583 |           | Chelsio Commu... | T540-5083 Unified Wire Storage Co... | 1     |            | [A1CF339702](<Server/Supermicro/Super/Super Server/AEAD0BFD0A36/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/A1CF339702>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3422 |           | Intel            | 7500/5520/5500/X58 I/O Hub GPIO a... | 68    |            | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:3423 |           | Intel            | 7500/5520/5500/X58 I/O Hub Contro... | 68    |            | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:6f76 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 68    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f88 |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 67    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f8a |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 67    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fae |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 67    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6faf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 67    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fbc |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 66    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fbd |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 66    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fbe |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 66    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fbf |           | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 66    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:342e |           | Intel            | 7500/5520/5500/X58 I/O Hub System... | 65    |            | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:6f1d | 8086:6f1d | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f1e | 8086:6f1e | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f1f | 8086:6f1f | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f71 | 8086:6f71 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f98 | 8086:6f98 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f99 | 8086:6f99 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f9a | 8086:6f9a | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f9c | 8086:6f9c | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fa0 | 8086:6fa0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fa8 | 8086:6fa8 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6faa | 8086:6faa | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fab | 8086:6fab | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fc0 | 8086:6fc0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fe0 | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fe1 | 8086:6fe1 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6ff8 | 8086:6ff8 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6ffc | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6ffd | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6ffe | 8086:6fe0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 56    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6f81 | 8086:6f81 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb0 | 8086:6fb0 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb1 | 8086:6fb1 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb2 | 8086:6fb2 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb3 | 8086:6fb3 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fe2 | 8086:6fe2 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fe3 | 8086:6fe3 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 55    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fac | 8086:6fac | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 52    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fad | 8086:6fad | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 52    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb4 | 8086:6fb4 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 51    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb5 | 8086:6fb5 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 51    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb6 | 8086:6fb6 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 51    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:6fb7 | 8086:6fb7 | Intel            | Xeon E7 v4/Xeon E5 v4/Xeon E3 v4/... | 51    |            | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:2018 |           | Intel            | Sky Lake-E M2PCI Registers           | 35    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2024 |           | Intel            | Sky Lake-E MM/Vt-d Configuration ... | 35    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2026 | 8086:2026 | Intel            | Sky Lake-E IOAPIC                    | 35    | ioapic     | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2034 |           | Intel            | Sky Lake-E VT-d                      | 35    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2035 |           | Intel            | Sky Lake-E RAS Configuration Regi... | 35    |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 8086:2036 | 8086:2036 | Intel            | Sky Lake-E IOxAPIC Configuration ... | 35    | ioapic     | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1c26 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 42    | ehci       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 8086:1c2d | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 42    | ehci       | [52327286E4](<Server/Dell/PowerEdge/PowerEdge R210 II/6874D632F3F4/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/52327286E4>) |
| 103c:3300 | 103c:3381 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 31    | uhci       | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:3a34 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 25    | uhci       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:3a35 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 25    | uhci       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:3a36 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 25    | uhci       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:3a3a | 103c:330d | Intel            | 82801JI (ICH10 Family) USB2 EHCI ... | 25    | ehci       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:8c26 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | ehci       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c2d | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | ehci       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:8c31 | 15d9:0921 | Intel            | 8 Series/C220 Series Chipset Fami... | 25    | xhci       | [16DACA3076](<Server/Thomas-Krenn.AG/1HE/1HE Intel Single-CPU RI1102D-F Server/B4996F8C95EB/OPNSENSE-23.1/13.1-RELEASE-P5/AMD64/16DACA3076>) |
| 8086:3a39 | 103c:330d | Intel            | 82801JI (ICH10 Family) USB UHCI C... | 24    | uhci       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 103c:3300 | 103c:3305 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 23    | uhci       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:8c26 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ehci       | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c2d | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | ehci       | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c31 | 15d9:086d | Intel            | 8 Series/C220 Series Chipset Fami... | 20    | xhci       | [D4460F8031](<Server/Supermicro/Super/Super Server/76ABD3C2521A/OPNSENSE-22.7.10/13.1-RELEASE-P5/AMD64/D4460F8031>) |
| 8086:8c31 | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 19    | xhci       | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:19d0 | 15d9:0969 | Intel            | Atom Processor C3000 Series USB 3... | 18    | xhci       | [BF83FC6CDB](<Server/Supermicro/A2/A2SDi-4C-HLN4F/60AB8F278277/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/BF83FC6CDB>) |
| 8086:2934 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 18    | uhci       | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 8086:2935 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 18    | uhci       | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 8086:2937 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 18    | uhci       | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 8086:2938 | 1028:0235 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 18    | uhci       | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 8086:293a | 1028:0235 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 18    | ehci       | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 8086:293c | 1028:0235 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 18    | ehci       | [8ADC53C921](<Server/Dell/PowerEdge/PowerEdge R710/1C862C6C9C8A/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8ADC53C921>) |
| 8086:8c26 | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 18    | ehci       | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:8c2d | 15d9:0842 | Intel            | 8 Series/C220 Series Chipset Fami... | 18    | ehci       | [16F59F69DC](<Server/Supermicro/X10/X10SLH-N6-ST031/0217AA257958/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/16F59F69DC>) |
| 8086:1d26 | 1028:0528 | Intel            | C600/X79 series chipset USB2 Enha... | 17    | ehci       | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:1d2d | 1028:0528 | Intel            | C600/X79 series chipset USB2 Enha... | 17    | ehci       | [5048D00FD8](<Server/Dell/OEM-R/OEM-R 720xd/2173A116CDDD/FREEBSD-12.1-P13/12.1-RELEASE-P13/AMD64/5048D00FD8>) |
| 8086:2934 | 1028:0236 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 17    | uhci       | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:2935 | 1028:0236 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 17    | uhci       | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:2937 | 1028:0236 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 17    | uhci       | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:2938 | 1028:0236 | Intel            | 82801I (ICH9 Family) USB UHCI Con... | 17    | uhci       | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:293a | 1028:0236 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 17    | ehci       | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:293c | 1028:0236 | Intel            | 82801I (ICH9 Family) USB2 EHCI Co... | 17    | ehci       | [1D71D3C9E7](<Server/Dell/PowerEdge/PowerEdge R610/221C4084D635/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/1D71D3C9E7>) |
| 8086:8c26 | 1028:05e5 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | ehci       | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:8c2d | 1028:05e5 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | ehci       | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:8c31 | 1028:05e5 | Intel            | 8 Series/C220 Series Chipset Fami... | 15    | xhci       | [07F21AFACC](<Server/Others/A/A04/9E8019EC4938/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/07F21AFACC>) |
| 8086:1d26 | 103c:18a9 | Intel            | C600/X79 series chipset USB2 Enha... | 14    | ehci       | [B9DF714117](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/0FE7DBEBF7BB/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B9DF714117>) |
| 8086:1d2d | 103c:18a9 | Intel            | C600/X79 series chipset USB2 Enha... | 14    | ehci       | [B9DF714117](<Server/Hewlett-Packard/ProLiant/ProLiant DL360p Gen8/0FE7DBEBF7BB/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/B9DF714117>) |
| 103c:3300 | 103c:3309 | Hewlett-Packard  | Integrated Lights-Out Standard Vi... | 13    | uhci       | [B666129E73](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G7/11E7797BD62C/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/B666129E73>) |
| 8086:8c26 | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | ehci       | [7D80C62813](<Server/Supermicro/X10/X10SLL-F/A4ACF508F8E6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7D80C62813>) |
| 8086:8c2d | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | ehci       | [7D80C62813](<Server/Supermicro/X10/X10SLL-F/A4ACF508F8E6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7D80C62813>) |
| 8086:8c31 | 15d9:0801 | Intel            | 8 Series/C220 Series Chipset Fami... | 11    | xhci       | [7D80C62813](<Server/Supermicro/X10/X10SLL-F/A4ACF508F8E6/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7D80C62813>) |
| 8086:8d26 | 1028:0601 | Intel            | C610/X99 series chipset USB Enhan... | 11    | ehci       | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:8d2d | 1028:0601 | Intel            | C610/X99 series chipset USB Enhan... | 11    | ehci       | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:1d26 | 1028:04f8 | Intel            | C600/X79 series chipset USB2 Enha... | 10    | ehci       | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:1d2d | 1028:04f8 | Intel            | C600/X79 series chipset USB2 Enha... | 10    | ehci       | [07852BF200](<Server/Dell/PowerEdge/PowerEdge R420/27E9EA276EEA/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/07852BF200>) |
| 8086:2688 | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 10    | uhci       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:2689 | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 10    | uhci       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:268a | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 10    | uhci       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |
| 8086:268b | 103c:31fe | Intel            | 631xESB/632xESB/3100 Chipset UHCI... | 10    | uhci       | [4A44193C5F](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 G5/FFA4A8B12A92/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/4A44193C5F>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:8d7c | 1028:0601 | Intel            | C610/X99 series chipset SPSR         | 11    |            | [38A54BC15C](<Server/Dell/PowerEdge/PowerEdge R630/B5BCD1914560/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/38A54BC15C>) |
| 8086:8d7c | 103c:8030 | Intel            | C610/X99 series chipset SPSR         | 8     |            | [17DDF8C2E1](<Server/Hewlett-Packard/ProLiant/ProLiant DL360 Gen9/30895685ED0C/OPNSENSE-22.1.10/13.0-STABLE/AMD64/17DDF8C2E1>) |
| 8086:a135 | 15d9:0884 | Intel            | 100 Series/C230 Series Chipset Fa... | 7     |            | [66C10B64CB](<Server/Supermicro/Super/Super Server/972BB3DC5295/OPNSENSE-22.7.6/13.1-RELEASE-P2/AMD64/66C10B64CB>) |
| 8086:a1ec | 1028:07c9 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [FF8F57EE67](<Server/Dell/PowerEdge/PowerEdge R440/05C2E2D7ED98/OPNSENSE-22.1.9/13.0-STABLE/AMD64/FF8F57EE67>) |
| 8086:a1ec | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 0    | 7     |            | [EB4105A1BA](<Server/Supermicro/Super/Super Server/D1F5127040E5/OPNSENSE-22.7/13.0-STABLE/AMD64/EB4105A1BA>) |
| 1022:1455 | 1022:1455 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 6     |            | [76519F54E9](<Server/Supermicro/Super/Super Server/B6CF39D94613/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/76519F54E9>) |
| 1022:145a | 1022:145a | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 6     |            | [76519F54E9](<Server/Supermicro/Super/Super Server/B6CF39D94613/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/76519F54E9>) |
| 8086:8d7c | 8086:7270 | Intel            | C610/X99 series chipset SPSR         | 6     |            | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 8086:8d7c | 15d9:0834 | Intel            | C610/X99 series chipset SPSR         | 5     |            | [59FF2014E5](<Server/Supermicro/Super/Super Server/C53FD6545133/FREEBSD-12.3-P5/12.3-RELEASE-P3/AMD64/59FF2014E5>) |
| 8086:a1ed | 15d9:0986 | Intel            | C620 Series Chipset Family MROM 1    | 5     |            | [872A05C140](<Server/Supermicro/Super/Super Server/AB927389C02E/OPNSENSE-22.1.5/13.0-STABLE/AMD64/872A05C140>) |
| 8086:8d7c | 15d9:0832 | Intel            | C610/X99 series chipset SPSR         | 4     |            | [1499A2903D](<Server/Supermicro/Super/Super Server/7E6D506E6800/OPNSENSE-22.1.9/13.0-STABLE/AMD64/1499A2903D>) |
| 8086:a1ec | 1028:0716 | Intel            | C620 Series Chipset Family MROM 0    | 4     |            | [8E22402D9E](<Server/Dell/PowerEdge/PowerEdge R640/B8B62F634D86/FREEBSD-13.1-P5/13.1-RELEASE-P5/AMD64/8E22402D9E>) |
| 1022:1485 | 1022:1485 | AMD              | Starship/Matisse Reserved SPP        | 3     |            | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |
| 1022:148a | 1022:148a | AMD              | Starship/Matisse PCIe Dummy Function | 3     |            | [2E389DB2DD](<Server/Thomas-Krenn.AG/1HE/1HE AMD Single-CPU RA1104-SMEPFH/871500B0E5B0/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/2E389DB2DD>) |
| 1028:0012 | 1028:0012 | Dell             | Remote Access Card 4 Daughter Car... | 3     | uart       | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 1028:0014 | 1028:0014 | Dell             | Remote Access Card 4 Daughter Car... | 3     |            | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 8086:8d7c | 1028:0639 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [CA48FF12D3](<Server/Dell/PowerEdge/PowerEdge R430/95126A9F3C9D/OPNSENSE-22.7.8/13.1-RELEASE-P3/AMD64/CA48FF12D3>) |
| 8086:8d7c | 15d9:0857 | Intel            | C610/X99 series chipset SPSR         | 3     |            | [E1EBA3B8F0](<Server/Supermicro/X10/X10SRA/0AF208B6DAE7/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E1EBA3B8F0>) |
| 8086:a135 | 15d9:0896 | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [A1DC602460](<Server/Supermicro/Super/Super Server/C3EAB3B58C16/OPNSENSE-22.7.4/13.1-RELEASE-P2/AMD64/A1DC602460>) |
| 8086:a135 | 15d9:089a | Intel            | 100 Series/C230 Series Chipset Fa... | 3     |            | [7BD99B62AB](<Server/Supermicro/Super/Super Server/A912B2977FCE/OPNSENSE-22.7.9/13.1-RELEASE-P5/AMD64/7BD99B62AB>) |
| 8086:a1ec | 1028:07ca | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [0B239C3286](<Server/Dell/PowerEdge/PowerEdge R540/34807F166517/OPNSENSE-22.1.7/13.0-STABLE/AMD64/0B239C3286>) |
| 8086:a1ec | 1590:00eb | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [3A932D738C](<Server/HPE/ProLiant/ProLiant ML110 Gen10/819B1E7CD686/OPNSENSE-22.1.6/13.0-STABLE/AMD64/3A932D738C>) |
| 8086:a1ec | 1734:1230 | Intel            | C620 Series Chipset Family MROM 0    | 3     |            | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 8086:a1ed | 1590:00eb | Intel            | C620 Series Chipset Family MROM 1    | 3     |            | [3A932D738C](<Server/HPE/ProLiant/ProLiant ML110 Gen10/819B1E7CD686/OPNSENSE-22.1.6/13.0-STABLE/AMD64/3A932D738C>) |
| 8086:a1ed | 1734:1230 | Intel            | C620 Series Chipset Family MROM 1    | 3     |            | [6460F775B0](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2530 M5/DD70B201449B/FREEBSD-11.4-P9/11.4-RELEASE-P2/AMD64/6460F775B0>) |
| 1022:1485 | 1458:1000 | AMD              | Starship/Matisse Reserved SPP        | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1022:148a | 1458:1000 | AMD              | Starship/Matisse PCIe Dummy Function | 2     |            | [15B7679CA1](<Server/Gigabyte Technology/MZ32/MZ32-AR0-00/C09C7E5CCF9F/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/15B7679CA1>) |
| 1028:0011 | 1028:0011 | Dell             | Remote Access Card 4 Daughter Card   | 2     |            | [8B59F71F96](<Server/Dell/PowerEdge/PowerEdge 1850/B4DF5516E374/OPNSENSE-22.1.8/13.0-STABLE/AMD64/8B59F71F96>) |
| 103c:193f | 103c:3381 | Hewlett-Packard  | Dynamic Smart Array B140i            | 2     |            | [F91D50AB48](<Server/Hewlett-Packard/ProLiant/ProLiant DL160 Gen9/10EC3EA2C607/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F91D50AB48>) |
| 1137:0042 | 1137:0157 | Cisco Systems    | VIC Management Controller            | 2     |            | [F168E21DD6](<Server/Cisco Systems/UCSC-C3/UCSC-C3K-M4SRB/71609C39CE05/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/F168E21DD6>) |
| 8086:8d7c |           | Intel            | C610/X99 series chipset SPSR         | 2     |            | [CE1988C8FF](<Server/Intel/S2600/S2600WTTR/EEB099E74D02/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/CE1988C8FF>) |
| 8086:8d7c | 1028:0600 | Intel            | C610/X99 series chipset SPSR         | 2     |            | [BA13BBECFD](<Server/Dell/PowerEdge/PowerEdge R730/BC55DA270D03/FREEBSD-12.3-STABLE/12.3-STABLE/AMD64/BA13BBECFD>) |
| 8086:8d7c | 15d9:0831 | Intel            | C610/X99 series chipset SPSR         | 2     |            | [DE856F28A4](<Server/Supermicro/Super/Super Server/5B3EF5C06A0F/DRAGONFLY-6.3-DEVELOPMENT/6.3-DEVELOPMENT/AMD64/DE856F28A4>) |
| 8086:8d7c | 1734:1201 | Intel            | C610/X99 series chipset SPSR         | 2     |            | [7A9D95B303](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2510 M2/3D0D1241B185/HARDENEDBSD-12.2--HBSD/12.2-STABLE-HBSD/AMD64/7A9D95B303>) |
| 8086:a135 | 15d9:0886 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [B34EE32475](<Server/Supermicro/Super/Super Server/76C4250B92CF/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/B34EE32475>) |
| 8086:a1ec | 1028:0737 | Intel            | C620 Series Chipset Family MROM 0    | 2     |            | [B062E0F4E4](<Server/Dell/PowerEdge/PowerEdge R740xd/3E6753E4D93A/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/B062E0F4E4>) |
| 8086:a1ec | 1137:0101 | Intel            | C620 Series Chipset Family MROM 0    | 2     |            | [2633EAF68B](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M5SX/41B605A42DA4/OPNSENSE-22.10/13.1-RELEASE-P2/AMD64/2633EAF68B>) |
| 8086:a1ec | 8086:7270 | Intel            | C620 Series Chipset Family MROM 0    | 2     |            | [D088FBCF53](<Server/Supermicro/X11/X11DPi-N/9D541BB80ABA/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/D088FBCF53>) |
| 8086:a1ed | 8086:7270 | Intel            | C620 Series Chipset Family MROM 1    | 2     |            | [D088FBCF53](<Server/Supermicro/X11/X11DPi-N/9D541BB80ABA/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/D088FBCF53>) |
| 0000:0000 |           |                  |                                      | 1     |            | [79A07689EC](<Server/ASRockRack/2U4/2U4N-F-X200/43B38B6A585F/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/79A07689EC>) |
| 1022:1455 | 1028:07f7 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [DE85A76391](<Server/Dell/PowerEdge/PowerEdge R7415/A26D4916788B/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/DE85A76391>) |
| 1022:1455 | 1028:07f9 | AMD              | Zeppelin/Renoir PCIe Dummy Function  | 1     |            | [C34D5C2BE3](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C34D5C2BE3>) |
| 1022:145a | 1028:07f7 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [DE85A76391](<Server/Dell/PowerEdge/PowerEdge R7415/A26D4916788B/FREEBSD-12.3-P3/12.3-RELEASE-P3/AMD64/DE85A76391>) |
| 1022:145a | 1028:07f9 | AMD              | Zeppelin/Raven/Raven2 PCIe Dummy ... | 1     |            | [C34D5C2BE3](<Server/Dell/PowerEdge/PowerEdge R7425/F0F0BC7915A2/OPNSENSE-22.1.4/13.0-STABLE/AMD64/C34D5C2BE3>) |
| 1022:1485 | 1028:08fd | AMD              | Starship/Matisse Reserved SPP        | 1     |            | [D778079C7F](<Server/Dell/PowerEdge/PowerEdge R7515/23F1145279FD/HARDENEDBSD-13.0-STABLE-HBSD/13.0-STABLE-HBSD/AMD64/D778079C7F>) |
| 1022:148a | 1028:08fd | AMD              | Starship/Matisse PCIe Dummy Function | 1     |            | [D778079C7F](<Server/Dell/PowerEdge/PowerEdge R7515/23F1145279FD/HARDENEDBSD-13.0-STABLE-HBSD/13.0-STABLE-HBSD/AMD64/D778079C7F>) |
| 1028:0010 | 1028:0010 | Dell             | Remote Access Card 4                 | 1     |            | [E988626E65](<Server/Dell/PowerEdge/PowerEdge 850/7C1FFD13EA06/OPNSENSE-21.7.3/12.1-RELEASE-P19-HBSD/AMD64/E988626E65>) |
| 1137:0042 | 1137:0085 | Cisco Systems    | VIC Management Controller            | 1     |            | [1B3588AB2F](<Server/Cisco Systems/UCSC-C240/UCSC-C240-M4L/647219C1BB29/FREEBSD-13.0/13.0-RELEASE/AMD64/1B3588AB2F>) |
| 8086:3456 |           | Intel            | Ice Lake NorthPeak                   | 1     |            | [1E2811020E](<Server/Fujitsu/PRIMERGY/PRIMERGY RX2540 M6/107195EF3348/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/1E2811020E>) |
| 8086:3591 | 1734:1041 | Intel            | E7525/E7520 Error Reporting Regis... | 1     |            | [ADB972BF8E](<Server/Fujitsu Siemens/PRIMERGY/PRIMERGY RX200S2/C657395B089D/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/ADB972BF8E>) |

