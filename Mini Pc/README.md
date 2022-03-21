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
| 8086:0f00 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 65    | hostb      | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:0f1c | 8086:0f1c | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 64    | isab       | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:0f48 | 8086:0f48 | Intel            | Atom Processor E3800 Series PCI E... | 64    | pcib       | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:0f4a | 8086:0f4a | Intel            | Atom Processor E3800 Series PCI E... | 64    | pcib       | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:0f4c | 8086:0f4c | Intel            | Atom Processor E3800 Series PCI E... | 64    | pcib       | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:0f4e | 8086:0f4e | Intel            | Atom Processor E3800 Series PCI E... | 63    | pcib       | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:31f0 |           | Intel            | Gemini Lake Host Bridge              | 40    | hostb      | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:5ad9 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | pcib       | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:5ada |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | pcib       | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:5ae8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | isab       | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:5af0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | hostb      | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 1022:141a |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 24    | hostb      | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:141b |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 24    | hostb      | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:141c |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 24    | hostb      | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:141d |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 24    | hostb      | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:141e |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 24    | hostb      | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:141f |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 24    | hostb      | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:1422 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) Proce... | 24    | hostb      | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:1424 |           | AMD              | Family 15h (Models 30h-3fh) Proce... | 24    | hostb      | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:1425 | 103c:8103 | AMD              | Kaveri P2P Bridge for GFX PCIe Po... | 24    | pcib       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:780e | 103c:8103 | AMD              | FCH LPC Bridge                       | 24    | isab       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:780f |           | AMD              | FCH PCI Bridge                       | 24    | pcib       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:5ad8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 24    | pcib       | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 1022:1426 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) Proce... | 22    | pcib       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1a03:1150 | 1a03:1150 | ASPEED Techno... | AST1150 PCI-to-PCI Bridge            | 19    | pcib       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1f10 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 19    | pcib       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1f11 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 19    | pcib       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1f12 | 8086:7270 | Intel            | Atom processor C2000 PCIe Root Po... | 19    | pcib       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1f14 |           | Intel            | Atom processor C2000 RAS             | 19    | hostb      | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1f38 | 8086:7270 | Intel            | Atom processor C2000 PCU             | 19    | isab       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:2280 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | hostb      | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:229c | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | isab       | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:22c8 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | pcib       | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:22ca | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | pcib       | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:31d6 | 8086:31d6 | Intel            | Gemini Lake PCI Express Root Port    | 17    | pcib       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:31d7 | 8086:31d7 | Intel            | Gemini Lake PCI Express Root Port    | 17    | pcib       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:31d8 | 8086:31d8 | Intel            | Gemini Lake PCI Express Root Port    | 17    | pcib       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:31d9 | 8086:31d9 | Intel            | Gemini Lake PCI Express Root Port    | 17    | pcib       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:31da | 8086:31da | Intel            | Gemini Lake PCI Express Root Port    | 17    | pcib       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:31e8 | 8086:31e8 | Intel            | Celeron/Pentium Silver Processor ... | 17    | isab       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:5af0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 14    | hostb      | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:0f1c | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 13    | isab       | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:0f48 | 8086:7270 | Intel            | Atom Processor E3800 Series PCI E... | 13    | pcib       | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:0f4a | 8086:7270 | Intel            | Atom Processor E3800 Series PCI E... | 13    | pcib       | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:0f4c | 8086:7270 | Intel            | Atom Processor E3800 Series PCI E... | 13    | pcib       | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:0f4e | 8086:7270 | Intel            | Atom Processor E3800 Series PCI E... | 13    | pcib       | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:0f00 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | hostb      | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:22cc | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 12    | pcib       | [D180B0D394](<Mini Pc/AMI/Aptio/Aptio CRB/C88F6ADFB7E1/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D180B0D394>) |
| 8086:31da | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 12    | pcib       | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:31e8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | isab       | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:2280 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | hostb      | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:229c | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | isab       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:22c8 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | pcib       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:22ca | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | pcib       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:22cc | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | pcib       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:31d9 | 8086:7270 | Intel            | Gemini Lake PCI Express Root Port    | 11    | pcib       | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:5ad7 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | pcib       | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:5ad8 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | pcib       | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:5ada | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | pcib       | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:5ae8 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | isab       | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:22ce | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | pcib       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:22ce | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 9     | pcib       | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:9d84 | 8086:2074 | Intel            | Cannon Point-LP LPC Controller       | 9     | isab       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:1604 | 8086:2057 | Intel            | Broadwell-U Host Bridge -OPI         | 8     | hostb      | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:5904 | 8086:2068 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 8     | hostb      | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:9c90 | 8086:2057 | Intel            | Wildcat Point-LP PCI Express Root... | 8     | pcib       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:9c96 | 8086:2057 | Intel            | Wildcat Point-LP PCI Express Root... | 8     | pcib       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:9d10 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 8     | pcib       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:9d15 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 8     | pcib       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:9d17 | 8086:2068 | Intel            | Sunrise Point-LP PCI Express Root... | 8     | pcib       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:9d4e | 8086:2068 | Intel            | Sunrise Point LPC Controller/eSPI... | 8     | isab       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:9db0 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 8     | pcib       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:9db8 | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 8     | pcib       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:9dbc | 8086:2074 | Intel            | Cannon Point-LP PCI Express Root ... | 8     | pcib       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 104c:823e |           | Texas Instrum... | XIO2213A/B/XIO2221 PCI Express to... | 7     | pcib       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:31da | 8086:2072 | Intel            | Gemini Lake PCI Express Root Port    | 7     | pcib       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:31e8 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     | isab       | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:31e8 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 7     | isab       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:31f0 | 8086:2072 | Intel            | Gemini Lake Host Bridge              | 7     | hostb      | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:3ed0 | 8086:2074 | Intel            | 8th Gen Core Processor Host Bridg... | 7     | hostb      | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:9cc3 | 8086:2057 | Intel            | Wildcat Point-LP LPC Controller      | 7     | isab       | [1486DC195E](<Mini Pc/Intel/NUC5i3RYB/NUC5i3RYB H41000-502/3AFA134D91CD/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/1486DC195E>) |
| 1022:1448 |           | AMD              | Renoir Device 24: Function 0         | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:1449 |           | AMD              | Renoir Device 24: Function 1         | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:144a |           | AMD              | Renoir Device 24: Function 2         | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:144b |           | AMD              | Renoir Device 24: Function 3         | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:144c |           | AMD              | Renoir Device 24: Function 4         | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:144d |           | AMD              | Renoir Device 24: Function 5         | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:144e |           | AMD              | Renoir Device 24: Function 6         | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:144f |           | AMD              | Renoir Device 24: Function 7         | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1022:1632 |           | AMD              | Renoir PCIe Dummy Host Bridge        | 6     | hostb      | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 10b5:8603 | 10b5:8603 | PLX Technology   | PEX 8603 3-lane, 3-Port PCI Expre... | 6     | pcib       | [0DD02A3DDF](<Mini Pc/Sophos/XG/XG/AB8EC8CFBC85/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/0DD02A3DDF>) |
| 8086:0284 | 8086:2081 | Intel            | Comet Lake PCH-LP LPC Premium Con... | 6     | isab       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:02b0 | 8086:2081 | Intel            | Comet Lake PCI Express Root Port #9  | 6     | pcib       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:02b5 | 8086:2081 | Intel            | Comet Lake PCH-LP PCIe Port #14      | 6     | pcib       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:02bc | 8086:2081 | Intel            | Comet Lake PCI Express Root Port #5  | 6     | pcib       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:15e7 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 Bridge [Tit... | 6     | pcib       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:1c10 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | pcib       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:1c12 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | pcib       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:1c14 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | pcib       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:1c49 | 8086:7270 | Intel            | HM65 Express Chipset LPC Controller  | 6     | isab       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:5229 | 8086:2068 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 8     | rtsx       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 10ec:5229 | 8086:2072 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 6     | rtsx       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 10ec:522a | 8086:2074 | Realtek Semic... | RTS522A PCI Express Card Reader      | 5     | rtsx       | [CCDA2302CF](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/41E25502F0FC/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/CCDA2302CF>) |
| 10ec:5229 | 8086:2067 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 2     |            | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |

### Co-processor (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1f18 |           | Intel            | Atom processor C2000 QAT             | 12    |            | [7E87CEEA76](<Mini Pc/Supermicro/A1/A1SAi/9D30C6309EE3/OPNSENSE-22.1.1/13.0-STABLE/AMD64/7E87CEEA76>) |
| 10de:0aa3 | 10de:cb79 | Nvidia           | MCP79 Co-processor                   | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0d7a | 10de:cb89 | Nvidia           | MCP89 Co-Processor                   | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    |            | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:319a | 8086:319a | Intel            | Celeron/Pentium Silver Processor ... | 17    |            | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:5a9a |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 14    |            | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:319a | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:9de0 | 8086:2074 | Intel            | Cannon Point-LP MEI Controller #1    | 9     |            | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:9cba | 8086:2057 | Intel            | Wildcat Point-LP MEI Controller #1   | 8     |            | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:9d3a | 8086:2068 | Intel            | Sunrise Point-LP CSME HECI #1        | 8     |            | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:319a | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     |            | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:319a | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 7     |            | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:5a9c | 8086:7270 | Intel            |                                      | 7     |            | [038B174183](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-22.1/13.0-STABLE/AMD64/038B174183>) |
| 8086:5a9e | 8086:7270 | Intel            |                                      | 7     |            | [038B174183](<Mini Pc/CompuLab/fitlet/fitlet2/BD28BE46F65E/OPNSENSE-22.1/13.0-STABLE/AMD64/038B174183>) |
| 8086:02e0 | 8086:2081 | Intel            | Comet Lake Management Engine Inte... | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:1c3a | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     |            | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:9d3a | 8086:1999 | Intel            | Sunrise Point-LP CSME HECI #1        | 6     |            | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 8086:9c3a | 8086:7270 | Intel            | 8 Series HECI #0                     | 5     |            | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 8086:9de0 | 17aa:314d | Intel            | Cannon Point-LP MEI Controller #1    | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 10ec:816a | 1043:85b5 | Realtek Semic... | RTL8111xP UART #1                    | 4     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 10ec:816b | 1043:85b5 | Realtek Semic... | RTL8111xP UART #2                    | 4     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:319a | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 4     |            | [E186D750D0](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/05311AA67241/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E186D750D0>) |
| 8086:1e3a | 8086:7270 | Intel            | 7 Series/C216 Chipset Family MEI ... | 3     |            | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:9d3a | 8086:2063 | Intel            | Sunrise Point-LP CSME HECI #1        | 3     |            | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:a2ba | 103c:829a | Intel            | 200 Series PCH CSME HECI #1          | 3     |            | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:a2bd | 103c:829a | Intel            | 200 Series Chipset Family KT Redi... | 3     |            | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:a360 | 17aa:312d | Intel            | Cannon Lake PCH HECI Controller      | 3     |            | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 8086:06e0 | 17aa:3172 | Intel            | Comet Lake HECI Controller           | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:06e3 | 17aa:3172 | Intel            | Comet Lake Keyboard and Text (KT)... | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:5a9c |           | Intel            |                                      | 2     |            | [09AB9EA6C6](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/C4ACAAC0F1A7/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/09AB9EA6C6>) |
| 8086:5a9e |           | Intel            | unknown                              | 2     |            | [09AB9EA6C6](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/C4ACAAC0F1A7/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/09AB9EA6C6>) |
| 8086:9cba | 8086:7270 | Intel            | Wildcat Point-LP MEI Controller #1   | 2     |            | [4CF0FFCBF6](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.1/13.0-STABLE/AMD64/4CF0FFCBF6>) |
| 8086:9d3a | 8086:2070 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a13a | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a328 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO UART Ho... | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:a360 | 17aa:3136 | Intel            | Cannon Lake PCH HECI Controller      | 2     |            | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:a360 | 8086:2089 | Intel            | Cannon Lake PCH HECI Controller      | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:a363 | 17aa:3136 | Intel            | Cannon Lake PCH Active Management... | 2     |            | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 10ec:816a | 103c:8522 | Realtek Semic... | RTL8111xP UART #1                    | 1     |            | [CAE055641A](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/CAE055641A>) |
| 10ec:816a | 103c:8523 | Realtek Semic... | RTL8111xP UART #1                    | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 10ec:816b | 103c:8522 | Realtek Semic... | RTL8111xP UART #2                    | 1     |            | [CAE055641A](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/CAE055641A>) |
| 10ec:816b | 103c:8523 | Realtek Semic... | RTL8111xP UART #2                    | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1415:c118 | 1415:c118 | Oxford Semico... | OXPCIe952 Parallel Port              | 1     |            | [77708F4E37](<Mini Pc/AMI/Aptio/Aptio CRB/7C6EDFADB996/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/77708F4E37>) |
| 1415:c11b | 1415:c11b | Oxford Semico... | OXPCIe952 Native 950 UART            | 1     | puc        | [77708F4E37](<Mini Pc/AMI/Aptio/Aptio CRB/7C6EDFADB996/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/77708F4E37>) |
| 8086:02e0 | 19da:b426 | Intel            | Comet Lake Management Engine Inte... | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:1c3a | 19da:b202 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     |            | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 8086:1e3a | 19da:a247 | Intel            | 7 Series/C216 Chipset Family MEI ... | 1     |            | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:1e3d | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | uart       | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:5a9a | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:8c3a | 19da:b220 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     |            | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:9c3a | 19da:b213 | Intel            | 8 Series HECI #0                     | 1     |            | [9BCBD09882](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9BCBD09882>) |
| 8086:9c3a | 19da:b246 | Intel            | 8 Series HECI #0                     | 1     |            | [F3E8035461](<Mini Pc/ZOTAC/ZBOX-CI321/ZBOX-CI321NANO/82AF0F92C578/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F3E8035461>) |
| 8086:9c3d | 8086:7270 | Intel            | 8 Series HECI KT                     | 1     | uart       | [39EE26926C](<Mini Pc/CompuLab/Intense-PC/Intense-PC2/084450D07AD2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/39EE26926C>) |
| 8086:9cba | 8086:2058 | Intel            | Wildcat Point-LP MEI Controller #1   | 1     |            | [8BE9390356](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/232CA933512D/FREEBSD-13.0-P4/13.0-RELEASE/AMD64/8BE9390356>) |
| 8086:9cba | 8086:9cba | Intel            | Wildcat Point-LP MEI Controller #1   | 1     |            | [E2B78B7ADA](<Mini Pc/BESSTAR Tech/U500/U500-H/2C1737B432F1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/E2B78B7ADA>) |
| 8086:9cbd | 8086:2058 | Intel            | Wildcat Point-LP KT Controller       | 1     |            | [8BE9390356](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/232CA933512D/FREEBSD-13.0-P4/13.0-RELEASE/AMD64/8BE9390356>) |
| 8086:9d3d | 8086:2070 | Intel            | Sunrise Point-LP Active Managemen... | 1     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a13a | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 8086:a360 | 17aa:3135 | Intel            | Cannon Lake PCH HECI Controller      | 1     |            | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |
| 8086:a363 | 17aa:3135 | Intel            | Cannon Lake PCH Active Management... | 1     |            | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f18 | 8086:0f18 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 64    |            | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:2298 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    |            | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:0f18 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 13    |            | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:2298 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    |            | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 1022:15df | 1022:15df | AMD              | Family 17h (Models 10h-1fh) Platf... | 6     |            | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 8086:2298 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     |            | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 1022:1537 | 1022:1537 | AMD              | Kabini/Mullins PSP-Platform Secur... | 1     |            | [D018E86EA8](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/FDAAE32B0FE7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D018E86EA8>) |
| 1022:15df | 103c:8522 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15df | 103c:8523 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:15df | 17aa:3190 | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 8086:0f18 | 1071:0740 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     |            | [D514362239](<Mini Pc/AMI/Aptio/Aptio CRB/7AF86A68764E/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/D514362239>) |
| 8086:2298 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [BFD71EFA3B](<Mini Pc/Shuttle/XS35/XS35V5/34C200C6C0F7/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BFD71EFA3B>) |

### Firewire controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 104c:823f |           | Texas Instrum... | XIO2213A/B/XIO2221 IEEE-1394b OHC... | 7     | fwohci     | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 11c1:5901 | 11c1:5900 | LSI              | FW643 [TrueFire] PCIe 1394b Contr... | 5     | fwohci     | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f31 | 8086:0f31 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 65    | vgapci     | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:5a85 | 8086:2212 | Intel            | HD Graphics 500                      | 28    | vgapci     | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 1002:131c | 103c:8103 | AMD              | Kaveri [Radeon R7 Graphics]          | 24    | vgapci     | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1a03:2000 | 15d9:0813 | ASPEED Techno... | ASPEED Graphics Family               | 19    | vgapci     | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:22b1 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | vgapci     | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:3185 |           | Intel            | GeminiLake [UHD Graphics 600]        | 16    | vgapci     | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:3185 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 600]        | 16    | vgapci     | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:0f31 | 8086:2212 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 12    | vgapci     | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:22b1 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | vgapci     | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:5a85 | 19da:b325 | Intel            | HD Graphics 500                      | 11    | vgapci     | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:3ea5 | 8086:2074 | Intel            | CoffeeLake-U GT3e [Iris Plus Grap... | 9     | i915       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:1616 | 8086:2057 | Intel            | HD Graphics 5500                     | 6     | i915       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:22b1 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | vgapci     | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 8086:3184 | 1028:080c | Intel            | GeminiLake [UHD Graphics 605]        | 6     | vgapci     | [71F763E932](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/1D5380207E8B/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/71F763E932>) |
| 1002:1636 | 1043:87e7 | AMD              | Renoir                               | 5     | vgapci     | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:3ea0 | 17aa:314d | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 5     | vgapci     | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:3185 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 600]        | 4     | vgapci     | [C55F468566](<Mini Pc/Intel/NUC7/NUC7CJYS/683FDC0E9AB5/FREEBSD-13.0/13.0-RELEASE/AMD64/C55F468566>) |
| 8086:5917 | 8086:2015 | Intel            | UHD Graphics 620                     | 4     | vgapci     | [8B09F64067](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/534B30206DF1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/8B09F64067>) |
| 8086:9bca | 8086:2081 | Intel            | Comet Lake UHD Graphics              | 4     | i915       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 10de:0861 | 106b:00ae | Nvidia           | C79 [GeForce 9400]                   | 3     | nvidia     | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:0126 | 106b:00e6 | Intel            | 2nd Generation Core Processor Fam... | 3     | vgapci     | [8CD83326F3](<Mini Pc/Apple/Macmini5/Macmini5,1/FA1265ADE548/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8CD83326F3>) |
| 8086:0a2e | 106b:0141 | Intel            | Haswell-ULT Integrated Graphics C... | 3     | vgapci     | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 8086:1912 | 103c:829a | Intel            | HD Graphics 530                      | 3     | i915       | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:3184 | 8086:2072 | Intel            | GeminiLake [UHD Graphics 605]        | 3     | i915       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:5916 | 8086:2068 | Intel            | HD Graphics 620                      | 3     | vgapci     | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:5927 | 8086:2068 | Intel            | Iris Plus Graphics 650               | 3     | vgapci     | [ABAAFD0A1E](<Mini Pc/Intel/NUC7i7BNB/NUC7i7BNB J31145-304/EA65C8660734/FREEBSD-12.2-STABLE/12.2-STABLE/AMD64/ABAAFD0A1E>) |
| 8086:5a84 | 8086:2212 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | vgapci     | [18CE49973D](<Mini Pc/CompuLab/fitlet/fitlet2/7A6D68504727/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/18CE49973D>) |
| 8086:5a85 | 8086:2067 | Intel            | HD Graphics 500                      | 3     | vgapci     | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 1002:6741 | 106b:00e8 | AMD              | Whistler [Radeon HD 6630M/6650M/6... | 2     | vgapci     | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 1002:9806 | 103c:17e2 | AMD              | Wrestler [Radeon HD 6320]            | 2     | vgapci     | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 8086:0126 | 106b:00f0 | Intel            | 2nd Generation Core Processor Fam... | 2     | vgapci     | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:0166 | 106b:0101 | Intel            | 3rd Gen Core processor Graphics C... | 2     | i915       | [AC585B4E0D](<Mini Pc/Apple/Macmini6/Macmini6,2/FAC8616568BC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/AC585B4E0D>) |
| 8086:1616 | 19da:b246 | Intel            | HD Graphics 5500                     | 2     | vgapci     | [4CF0FFCBF6](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.1/13.0-STABLE/AMD64/4CF0FFCBF6>) |
| 8086:1626 | 8086:2057 | Intel            | HD Graphics 6000                     | 2     | i915       | [F76929B920](<Mini Pc/Intel/NUC5i5RYB/NUC5i5RYB H40999-503/9144D4C72B3C/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/F76929B920>) |
| 8086:1926 | 8086:2063 | Intel            | Iris Graphics 540                    | 2     | vgapci     | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:3e92 | 17aa:312d | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 2     | vgapci     | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 8086:3e92 | 17aa:3136 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 2     | vgapci     | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:3e9b | 8086:2089 | Intel            | CoffeeLake-H GT2 [UHD Graphics 630]  | 2     | vgapci     | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:5916 |           | Intel            | HD Graphics 620                      | 2     | vgapci     | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 8086:591b | 8086:2073 | Intel            | HD Graphics 630                      | 2     | i915       | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:5926 | 8086:2068 | Intel            | Iris Plus Graphics 640               | 2     | i915       | [26C56BCF3D](<Mini Pc/Intel/NUC7/NUC7i5BNK/676EDD2CB530/FREEBSD-12.2-P6/12.2-RELEASE-P6/AMD64/26C56BCF3D>) |
| 8086:9b41 | 8086:2081 | Intel            | CometLake-U GT2 [UHD Graphics]       | 2     | vgapci     | [A09FBE5FCC](<Mini Pc/Intel Client Systems/NUC10/NUC10i5FNH/1FFBE51038AD/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/A09FBE5FCC>) |
| 8086:9bc5 | 17aa:3172 | Intel            | CometLake-S GT2 [UHD Graphics 630]   | 2     | vgapci     | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 1002:15d8 | 1002:0123 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 1     | vgapci     | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 1002:15d8 | 103c:8523 | AMD              | Picasso/Raven 2 [Radeon Vega Seri... | 1     | vgapci     | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1002:15dd | 103c:8522 | AMD              | Raven Ridge [Radeon Vega Series /... | 1     | vgapci     | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1002:1636 | 17aa:3190 | AMD              | Renoir                               | 1     | amdgpu     | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1002:694c | 8086:2073 | AMD              | Polaris 22 XT [Radeon RX Vega M GH]  | 1     | vgapci     | [3AB33909B0](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3AB33909B0>) |
| 1002:694e | 8086:2073 | AMD              | Polaris 22 XL [Radeon RX Vega M GL]  | 1     | vgapci     | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 1002:9831 | 1022:1234 | AMD              | Kabini [Radeon HD 8400E]             | 1     | vgapci     | [4433B8842F](<Mini Pc/CompuLab/fit-PC/fit-PC4/EAC3D2695650/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/4433B8842F>) |
| 1002:9832 | 1002:0123 | AMD              | Kabini [Radeon HD 8330]              | 1     | vgapci     | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 1002:9851 | 1022:1234 | AMD              | Mullins [Radeon R4/R5 Graphics]      | 1     | vgapci     | [D018E86EA8](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/FDAAE32B0FE7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D018E86EA8>) |
| 102b:0532 | 1028:04dd | Matrox Electr... | MGA G200eW WPCM450                   | 1     | vgapci     | [5F293A8796](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/59BF64F0C06D/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/5F293A8796>) |
| 10de:08a4 | 106b:00c0 | Nvidia           | MCP89 [GeForce 320M]                 | 1     | vgapci     | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 8086:0116 | 106b:00e7 | Intel            | 2nd Generation Core Processor Fam... | 1     | vgapci     | [C3394665A0](<Mini Pc/Apple/Macmini5/Macmini5,3/D92D3031168A/OPNSENSE-22.1/13.0-STABLE/AMD64/C3394665A0>) |
| 8086:0152 | 19da:b202 | Intel            | Xeon E3-1200 v2/3rd Gen Core proc... | 1     | vgapci     | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 8086:0166 | 19da:2111 | Intel            | 3rd Gen Core processor Graphics C... | 1     | vgapci     | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:0166 | 8086:2211 | Intel            | 3rd Gen Core processor Graphics C... | 1     | vgapci     | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:0412 | 19da:b220 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | vgapci     | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:0a0e | 19da:b246 | Intel            | Haswell-ULT High Definition Audio... | 1     | vgapci     | [F3E8035461](<Mini Pc/ZOTAC/ZBOX-CI321/ZBOX-CI321NANO/82AF0F92C578/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F3E8035461>) |
| 8086:0a0e | 19da:b281 | Intel            | Haswell-ULT High Definition Audio... | 1     | vgapci     | [D8343DC26F](<Mini Pc/ZOTAC/ZBOX-RI323/ZBOX-RI323NANO/7D57F802F474/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/D8343DC26F>) |
| 8086:0a16 | 19da:b213 | Intel            | Haswell-ULT Integrated Graphics C... | 1     | vgapci     | [9BCBD09882](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9BCBD09882>) |
| 8086:0a16 | 8086:2010 | Intel            | Haswell-ULT Integrated Graphics C... | 1     | vgapci     | [39EE26926C](<Mini Pc/CompuLab/Intense-PC/Intense-PC2/084450D07AD2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/39EE26926C>) |
| 8086:0f31 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | vgapci     | [D156760FE8](<Mini Pc/WYSE/Dell/Dell Wyse Thin Client Desktop 3290/AF0EBE39FF8F/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/D156760FE8>) |
| 8086:1616 | 1e50:8002 | Intel            | HD Graphics 5500                     | 1     | vgapci     | [E2B78B7ADA](<Mini Pc/BESSTAR Tech/U500/U500-H/2C1737B432F1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/E2B78B7ADA>) |
| 8086:1616 | 8086:2058 | Intel            | HD Graphics 5500                     | 1     | vgapci     | [8BE9390356](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/232CA933512D/FREEBSD-13.0-P4/13.0-RELEASE/AMD64/8BE9390356>) |
| 8086:1916 | 8086:2063 | Intel            | Skylake GT2 [HD Graphics 520]        | 1     | vgapci     | [E057495CA3](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/E0C236805F04/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/E057495CA3>) |
| 8086:193b | 8086:2064 | Intel            | Iris Pro Graphics 580                | 1     | i915       | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 8086:22b1 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | vgapci     | [85C4302966](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/C965A3AF570B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/85C4302966>) |
| 8086:22b1 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | vgapci     | [BFD71EFA3B](<Mini Pc/Shuttle/XS35/XS35V5/34C200C6C0F7/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BFD71EFA3B>) |
| 8086:3184 | 1e50:8003 | Intel            | GeminiLake [UHD Graphics 605]        | 1     | vgapci     | [EE64289B31](<Mini Pc/BESSTAR Tech/GK/GK50/5F875D6566AB/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/EE64289B31>) |
| 8086:3185 | 1028:080c | Intel            | GeminiLake [UHD Graphics 600]        | 1     | vgapci     | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:3e91 | 17aa:312d | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 1     | vgapci     | [D15116D2EB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7CTO1WW/2D340AE8DBBC/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/D15116D2EB>) |
| 8086:3e92 | 17aa:3135 | Intel            | CoffeeLake-S GT2 [UHD Graphics 630]  | 1     | vgapci     | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |
| 8086:5916 | 8086:2070 | Intel            | HD Graphics 620                      | 1     | i915       | [06BEB9AD2C](<Mini Pc/Intel Client Systems/NUC7/NUC7i3DNHE/F93E47848AEB/FREEBSD-12.1-P6/12.1-RELEASE-P6/AMD64/06BEB9AD2C>) |
| 8086:5917 | 8086:2070 | Intel            | UHD Graphics 620                     | 1     | i915       | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:5a84 | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | vgapci     | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:5a85 | 8086:2112 | Intel            | HD Graphics 500                      | 1     | vgapci     | [9FDA2F2DA0](<Mini Pc/AMI/Aptio/Aptio CRB/43D0EDFED15F/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/9FDA2F2DA0>) |
| 8086:9b41 | 19da:b426 | Intel            | CometLake-U GT2 [UHD Graphics]       | 1     | vgapci     | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9def | 8086:2074 | Intel            | Cannon Point-LP Shared SRAM          | 9     |            | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:9d21 | 8086:2068 | Intel            | Sunrise Point-LP PMC                 | 8     |            | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:02ef | 8086:2081 | Intel            | Comet Lake PCH-LP Shared SRAM        | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:9d21 | 8086:7270 | Intel            | Sunrise Point-LP PMC                 | 6     |            | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 8086:9def | 17aa:314d | Intel            | Cannon Point-LP Shared SRAM          | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 10de:0a88 |           | Nvidia           | MCP79 Memory Controller              | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0a89 |           | Nvidia           | MCP79 Memory Controller              | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0a98 | 10de:cb79 | Nvidia           | MCP79 Memory Controller              | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0aa4 |           | Nvidia           | MCP79 Memory Controller              | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:9d21 | 8086:2063 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:a2a1 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family Po... | 3     |            | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:a36f | 17aa:312d | Intel            | Cannon Lake PCH Shared SRAM          | 3     |            | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 8086:06ef | 17aa:3172 | Intel            | Comet Lake PCH Shared SRAM           | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:9d21 | 8086:2070 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a121 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a36f | 17aa:3136 | Intel            | Cannon Lake PCH Shared SRAM          | 2     |            | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:a36f | 8086:7270 | Intel            | Cannon Lake PCH Shared SRAM          | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 10de:0d68 |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d69 |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d6d |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d6e |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d6f |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d70 |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d71 |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d72 |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d75 |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d7b |           | Nvidia           | MCP89 Memory Controller              | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 8086:02ef | 8086:7270 | Intel            | Comet Lake PCH-LP Shared SRAM        | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
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
| 10ec:8168 | 103c:8103 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 21    | re         | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:1f41 | 15d9:1f41 | Intel            | Ethernet Connection I354             | 19    | igb        | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 10ec:8168 | 19da:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 10    | re         | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:1533 |           | Intel            | I210 Gigabit Network Connection      | 9     | igb        | [19ED08C39C](<Mini Pc/AMI/Aptio/Aptio CRB/B514BDB172DC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19ED08C39C>) |
| 8086:15be | 8086:2074 | Intel            | Ethernet Connection (6) I219-V       | 9     | em         | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:1521 | 8086:5001 | Intel            | I350 Gigabit Network Connection      | 8     | igb        | [6A0515C9EA](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/503BC5DCB26E/OPNSENSE-22.1.1/13.0-STABLE/AMD64/6A0515C9EA>) |
| 8086:15d8 | 8086:2068 | Intel            | Ethernet Connection (4) I219-V       | 8     | em         | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:150c | 1462:6c40 | Intel            | 82583V Gigabit Network Connection    | 7     | em         | [5D39002367](<Mini Pc/AMI/Aptio/Aptio CRB/F4919BE5C566/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5D39002367>) |
| 10ec:8168 | 1028:080c | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | re         | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:0d4f | 8086:2081 | Intel            | Ethernet Connection (10) I219-V      | 6     | em         | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 10ec:8168 | 17aa:314d | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 5     | re         | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 14e4:1682 | 106b:00f6 | Broadcom         | NetXtreme BCM57762 Gigabit Ethern... | 5     | bge        | [8CD83326F3](<Mini Pc/Apple/Macmini5/Macmini5,1/FA1265ADE548/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8CD83326F3>) |
| 14e4:1686 | 14e4:1686 | Broadcom         | NetXtreme BCM57766 Gigabit Ethern... | 5     | bge        | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 10ec:8168 | 1043:85b5 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | re         | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 10ec:8168 | 1854:0309 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 4     | re         | [E186D750D0](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/05311AA67241/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E186D750D0>) |
| 10de:0ab0 | 10de:cb79 | Nvidia           | MCP79 Ethernet                       | 3     | nfe        | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10ec:8168 | 8086:2067 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 3     | re         | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:1521 | 8086:0001 | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 8086:1521 | 8086:00a1 | Intel            | I350 Gigabit Network Connection      | 3     | igb        | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:15bc | 17aa:312d | Intel            | Ethernet Connection (7) I219-V       | 3     | em         | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 8086:15e3 | 103c:829a | Intel            | Ethernet Connection (5) I219-LM      | 3     | em         | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 14e4:165f | 14e4:2003 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 2     | bge        | [364241899F](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E658728E0DEE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/364241899F>) |
| 14e4:16b1 | 103c:17e2 | Broadcom         | NetLink BCM57781 Gigabit Ethernet... | 2     | bge        | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 8086:0d4c | 17aa:3172 | Intel            | Ethernet Connection (11) I219-LM     | 2     | em         | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:150a | 1734:11a7 | Intel            | 82576NS Gigabit Network Connection   | 2     | igb        | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:150e | 103c:1780 | Intel            | 82580 Gigabit Network Connection     | 2     | igb        | [A6C494CC8F](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/418B34FA353A/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/A6C494CC8F>) |
| 8086:1521 | 108e:7b18 | Intel            | I350 Gigabit Network Connection      | 2     | igb        | [71F763E932](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/1D5380207E8B/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/71F763E932>) |
| 8086:156f |           | Intel            | Ethernet Connection I219-LM          | 2     | em         | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 8086:15bb |           | Intel            | Ethernet Connection (7) I219-LM      | 2     | em         | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:15bb | 17aa:3136 | Intel            | Ethernet Connection (7) I219-LM      | 2     | em         | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 10ec:8125 | 1043:87d7 | Realtek Semic... | RTL8125 2.5GbE Controller            | 1     | re         | [2781B31F9B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50-E1/A2FA457F7B31/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/2781B31F9B>) |
| 10ec:8161 | 10ec:8168 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [BBD5813F92](<Mini Pc/Hewlett-Packard/t610/t610 PLUS WW Thin Client/7275C6CFC845/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BBD5813F92>) |
| 10ec:8168 | 1019:a6e2 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 10ec:8168 | 103c:8522 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 10ec:8168 | 103c:8523 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 10ec:8168 | 1170:af06 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [D018E86EA8](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/FDAAE32B0FE7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D018E86EA8>) |
| 10ec:8168 | 17aa:3190 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1425:4002 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Ethernet Con... | 1     | t4iov      | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1425:4402 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Ethernet Con... | 1     | t4nex      | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 14e4:1639 | 103c:7059 | Broadcom         | NetXtreme II BCM5709 Gigabit Ethe... | 1     | bce        | [C7329E8EC2](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/A4733F4EB410/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/C7329E8EC2>) |
| 14e4:163b | 1028:04dd | Broadcom         | NetXtreme II BCM5716 Gigabit Ethe... | 1     | bce        | [5F293A8796](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/59BF64F0C06D/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/5F293A8796>) |
| 14e4:165f | 103c:1786 | Broadcom         | NetXtreme BCM5720 Gigabit Etherne... | 1     | bge        | [12763190F5](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/92380BE13EFA/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/12763190F5>) |
| 14e4:1682 | 103c:2344 | Broadcom         | NetXtreme BCM57762 Gigabit Ethern... | 1     | bge        | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 8086:10c9 | 1dcf:0319 | Intel            | 82576 Gigabit Network Connection     | 1     | igb        | [D7790B678B](<Mini Pc/AMI/Aptio/Aptio CRB/B68ECC7BE0C6/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/D7790B678B>) |
| 8086:10d6 | 8086:145a | Intel            | 82575GB Gigabit Network Connection   | 1     | igb        | [0138A82561](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/64235D97E708/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/0138A82561>) |
| 8086:10fb | 108e:7b11 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 1     | ix         | [BAB9A21997](<Mini Pc/Supermicro/A1/A1SAi/1EA14E13E7FB/OPNSENSE-22.1/13.0-STABLE/AMD64/BAB9A21997>) |
| 8086:10fb | 8086:7a11 | Intel            | 82599ES 10-Gigabit SFI/SFP+ Netwo... | 1     | ix         | [32D6C89C7F](<Mini Pc/Supermicro/A1/A1SAi/1BB83BD43BBF/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/32D6C89C7F>) |
| 8086:1502 |           | Intel            | 82579LM Gigabit Network Connectio... | 1     | em         | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:150c |           | Intel            | 82583V Gigabit Network Connection    | 1     | em         | [98CEFDDB1B](<Mini Pc/AMI/Aptio/Aptio CRB/DE2086254754/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/98CEFDDB1B>) |
| 8086:150e | 8086:12a1 | Intel            | 82580 Gigabit Network Connection     | 1     | igb        | [341CA2F887](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/23B4F081BD2A/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/341CA2F887>) |
| 8086:1521 | 103c:339e | Intel            | I350 Gigabit Network Connection      | 1     | igb        | [00384BEC4A](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/B4145F2E38EF/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/00384BEC4A>) |
| 8086:1521 | 8086:5002 | Intel            | I350 Gigabit Network Connection      | 1     | igb        | [732A50AF16](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/59BF64F0C06D/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/732A50AF16>) |
| 8086:1528 | 8086:0001 | Intel            | Ethernet Controller 10-Gigabit X5... | 1     | ix         | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |
| 8086:1536 |           | Intel            | I210 Gigabit Fiber Network Connec... | 1     | igb        | [87CF6A7EDD](<Mini Pc/Barracuda Networks/Barracuda/Barracuda NG Firewall F180R/86991565E608/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/87CF6A7EDD>) |
| 8086:1539 | 1297:4033 | Intel            | I211 Gigabit Network Connection      | 1     | igb        | [BFD71EFA3B](<Mini Pc/Shuttle/XS35/XS35V5/34C200C6C0F7/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BFD71EFA3B>) |
| 8086:15a2 | 8086:2058 | Intel            | Ethernet Connection (3) I218-LM      | 1     | em         | [8BE9390356](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/232CA933512D/FREEBSD-13.0-P4/13.0-RELEASE/AMD64/8BE9390356>) |
| 8086:15bb | 17aa:3135 | Intel            | Ethernet Connection (7) I219-LM      | 1     | em         | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:3165 | 8086:4010 | Intel            | Wireless 3165                        | 33    | iwm        | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 8086:31dc | 8086:02a4 | Intel            | Gemini Lake PCH CNVi WiFi            | 17    | iwm        | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 12    | iwm        | [BD63B06EA9](<Mini Pc/AWOW/PC/PC BOX/C22C936E0B18/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/BD63B06EA9>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 12    | iwm        | [CCDA2302CF](<Mini Pc/Intel Client Systems/NUC8/NUC8i7BEH/41E25502F0FC/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/CCDA2302CF>) |
| 168c:0042 | 1a3b:2b51 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 11    |            | [23FAF80BFE](<Mini Pc/BESSTAR Tech/GK/GK41/CA411C944153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23FAF80BFE>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 9     | iwm        | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:08b3 | 8086:8070 | Intel            | Wireless 3160                        | 8     | iwm        | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:24fd | 8086:9010 | Intel            | Wireless 8265 / 8275                 | 8     | iwm        | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 14e4:4331 | 14e4:4331 | Broadcom         | BCM4331 802.11a/b/g/n                | 6     | bwn_pci    | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:02f0 | 8086:0074 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:08b3 | 8086:0070 | Intel            | Wireless 3160                        | 6     | iwm        | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 5     |            | [BFC921BFBB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T700A9GE/621CFA7E8D6B/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/BFC921BFBB>) |
| 10ec:c822 | 1a3b:4210 | Realtek Semic... | RTL8822CE 802.11ac PCIe Wireless ... | 4     |            | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:24f3 | 8086:9010 | Intel            | Wireless 8260                        | 4     | iwm        | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 4     | iwm        | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 14e4:4328 | 106b:0090 | Broadcom         | BCM4321 802.11a/b/g/n                | 3     | bwn_pci    | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 14e4:4359 | 103c:8088 | Broadcom         | BCM43228 802.11a/b/g/n               | 3     |            | [860E4A3D12](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/FC364ADF0FF9/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/860E4A3D12>) |
| 14e4:43a0 | 106b:013b | Broadcom         | BCM4360 802.11ac Wireless Network... | 3     |            | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 8086:24f3 | 8086:1010 | Intel            | Wireless 8260                        | 3     | iwm        | [1BD135DA09](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/580E60F5A312/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/1BD135DA09>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 3     | iwm        | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:31dc | 8086:4030 | Intel            | Gemini Lake PCH CNVi WiFi            | 3     |            | [29FC97472B](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/16D19D798898/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/29FC97472B>) |
| 14e4:4331 | 106b:010e | Broadcom         | BCM4331 802.11a/b/g/n                | 2     | bwn_pci    | [AC585B4E0D](<Mini Pc/Apple/Macmini6/Macmini6,2/FAC8616568BC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/AC585B4E0D>) |
| 168c:003e | 11ad:0513 | Qualcomm Atheros | QCA6174 802.11ac Wireless Network... | 2     |            | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:2723 | 8086:008c | Intel            | Wi-Fi 6 AX200                        | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:3165 | 8086:8110 | Intel            | Wireless 3165                        | 2     | iwm        | [6696106165](<Mini Pc/BESSTAR Tech/N/N40/ADBB2D7261B8/OPNSENSE-22.1.1/13.0-STABLE/AMD64/6696106165>) |
| 8086:4232 | 8086:1201 | Intel            | WiFi Link 5100                       | 2     | iwn        | [D180B0D394](<Mini Pc/AMI/Aptio/Aptio CRB/C88F6ADFB7E1/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D180B0D394>) |
| 10ec:8172 | 10ec:e020 | Realtek Semic... | RTL8191SEvB Wireless LAN Controller  | 1     |            | [EF9E76D0EA](<Mini Pc/AMI/Aptio/Aptio CRB/DBF8308BC7DC/DRAGONFLY-5.9-DEVELOPMENT/5.9-DEVELOPMENT/AMD64/EF9E76D0EA>) |
| 10ec:8179 | 10ec:8179 | Realtek Semic... | RTL8188EE Wireless Network Adapter   | 1     |            | [BFD71EFA3B](<Mini Pc/Shuttle/XS35/XS35V5/34C200C6C0F7/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BFD71EFA3B>) |
| 10ec:8723 | 10ec:0733 | Realtek Semic... | RTL8723AE PCIe Wireless Network A... | 1     |            | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 10ec:c821 | 1a3b:3043 | Realtek Semic... | RTL8821CE 802.11ac PCIe Wireless ... | 1     |            | [BEF9A78364](<Mini Pc/GEEK+/G/G34/15C7CD0CFC4F/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/BEF9A78364>) |
| 14e4:4353 | 106b:0093 | Broadcom         | BCM43224 802.11a/b/g/n               | 1     | bwn_pci    | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 168c:002a | 168c:3099 | Qualcomm Atheros | AR928X Wireless Network Adapter (... | 1     | ath        | [7623C94BA1](<Mini Pc/AMI/Aptio/Aptio CRB/2A6D86CEBF47/OPNSENSE-21.1.7/12.1-RELEASE-P18-HBSD/AMD64/7623C94BA1>) |
| 168c:002b | 103c:3040 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 1     | ath        | [76D7C47FFA](<Mini Pc/AMI/Aptio/Aptio CRB/4FD96BBACDAA/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/76D7C47FFA>) |
| 168c:002b | 1a3b:1089 | Qualcomm Atheros | AR9285 Wireless Network Adapter (... | 1     | ath        | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 168c:0030 | 168c:3110 | Qualcomm Atheros | AR93xx Wireless Network Adapter      | 1     | ath        | [6821383A38](<Mini Pc/Sophos/XG/XG/9DA2AF4CD9CC/OPNSENSE-20.7.7/12.1-RELEASE-P11-HBSD/AMD64/6821383A38>) |
| 1814:3090 | 1814:3090 | Ralink           | RT3090 Wireless 802.11n 1T/1R PCIe   | 1     | ral        | [448AB4ED58](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/448AB4ED58>) |
| 8086:02f0 | 8086:0264 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:0885 | 8086:1305 | Intel            | Centrino Wireless-N 6150             | 1     | iwn        | [7AAAAFCB77](<Mini Pc/AMI/Aptio/Aptio CRB/D0E7A6A12AB4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/7AAAAFCB77>) |
| 8086:0887 | 8086:4062 | Intel            | Centrino Wireless-N 2230             | 1     | iwn        | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:0892 | 8086:0062 | Intel            | Centrino Wireless-N 135              | 1     | iwn        | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 8086:08b1 | 8086:c070 | Intel            | Wireless 7260                        | 1     | iwm        | [EDE207C6DF](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 65W/B2EEDA3475A3/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/EDE207C6DF>) |
| 8086:24f3 | 8086:0050 | Intel            | Wireless 8260                        | 1     | iwm        | [12763190F5](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/92380BE13EFA/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/12763190F5>) |
| 8086:24f3 | 8086:10b0 | Intel            | Wireless 8260                        | 1     | iwm        | [39EE26926C](<Mini Pc/CompuLab/Intense-PC/Intense-PC2/084450D07AD2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/39EE26926C>) |
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 1     | iwm        | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:2723 | 8086:4080 | Intel            | Wi-Fi 6 AX200                        | 1     |            | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |
| 8086:3165 | 8086:8010 | Intel            | Wireless 3165                        | 1     | iwm        | [E2B78B7ADA](<Mini Pc/BESSTAR Tech/U500/U500-H/2C1737B432F1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/E2B78B7ADA>) |
| 8086:4232 | 8086:1321 | Intel            | WiFi Link 5100                       | 1     | iwn        | [C1A950C4B9](<Mini Pc/AMI/Aptio/Aptio CRB/B68ECC7BE0C6/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/C1A950C4B9>) |
| 8086:a370 | 8086:0030 | Intel            | Cannon Lake PCH CNVi WiFi            | 1     | iwm        | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:8168 | 10ec:0123 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 96    | re         | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:1539 |           | Intel            | I211 Gigabit Network Connection      | 72    | igb        | [2ECB6FABA3](<Mini Pc/AMI/Aptio/Aptio CRB/FEA9A2F7C9FB/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2ECB6FABA3>) |
| 8086:157b |           | Intel            | I210 Gigabit Network Connection      | 9     | igb        | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:15a3 | 8086:2057 | Intel            | Ethernet Connection (3) I218-V       | 8     | em         | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 10ec:8168 | 8086:2072 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 7     | re         | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 14e4:16b4 | 14e4:16b4 | Broadcom         | NetXtreme BCM57765 Gigabit Ethern... | 7     | bge        | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 10ec:8168 | 8086:2060 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 6     | re         | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 8086:1570 | 8086:2063 | Intel            | Ethernet Connection I219-V           | 3     | em         | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:150e | 1734:11a8 | Intel            | 82580 Gigabit Network Connection     | 2     | igb        | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 8086:156f | 8086:2070 | Intel            | Ethernet Connection I219-LM          | 2     | em         | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:15b7 |           | Intel            | Ethernet Connection (2) I219-LM      | 2     | em         | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 10ec:8168 | 7470:3468 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [55C7D22C4D](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/957721D5B2BA/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/55C7D22C4D>) |
| 1425:0000 | 1014:03e5 | Chelsio Commu... |                                      | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1425:4102 | 1014:03e5 | Chelsio Commu... |                                      | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 15b3:1003 | 15b3:0050 | Mellanox Tech... | MT27500 Family [ConnectX-3]          | 1     | mlx4_core  | [0585732860](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/F0BCA0A99F84/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/0585732860>) |
| 15b3:6750 | 15b3:0015 | Mellanox Tech... | MT26448 [ConnectX EN 10GigE, PCIe... | 1     | mlx4_core  | [CF9CB3DFCF](<Mini Pc/Supermicro/A1/A1SAi/EF132EE4A24F/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/CF9CB3DFCF>) |
| 8086:105e | 103c:7044 | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 1     | em         | [EF3E506A31](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/341C876B1CAB/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/EF3E506A31>) |
| 8086:105e | 8086:115e | Intel            | 82571EB/82571GB Gigabit Ethernet ... | 1     | em         | [DA8A373D43](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/D73E5B91D8AA/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/DA8A373D43>) |
| 8086:10d3 |           | Intel            | 82574L Gigabit Network Connection    | 1     | em         | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:150e | 8086:12a2 | Intel            | 82580 Gigabit Network Connection     | 1     | igb        | [4846F1C003](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/6DD1917C72F2/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/4846F1C003>) |
| 8086:155a |           | Intel            | Ethernet Connection I218-LM          | 1     | em         | [39EE26926C](<Mini Pc/CompuLab/Intense-PC/Intense-PC2/084450D07AD2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/39EE26926C>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 24    | sdhci_pci  | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:31cc | 8086:31cc | Intel            | Celeron/Pentium Silver Processor ... | 15    | sdhci_pci  | [23FAF80BFE](<Mini Pc/BESSTAR Tech/GK/GK41/CA411C944153/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23FAF80BFE>) |
| 14e4:16bc |           | Broadcom         | BCM57765/57785 SDXC/MMC Card Reader  | 12    | sdhci_pci  | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:5ad0 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 12    | sdhci_pci  | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:31d0 | 8086:7270 | Intel            | SD Host Controller                   | 11    | sdhci_pci  | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:5acc | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | sdhci_pci  | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:31cc | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     | sdhci_pci  | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 17a0:9755 | 8086:2081 | Genesys Logic    | GL9755 SD Host Controller            | 6     | sdhci_pci  | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:31cc | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 6     | sdhci_pci  | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:5ad0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 6     | sdhci_pci  | [482C5CBF99](<Mini Pc/CompuLab/fitlet/fitlet2/16123572AAD5/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/482C5CBF99>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     | sdhci_pci  | [3FE694D1C9](<Mini Pc/CompuLab/fitlet/fitlet2/4EEC0856A319/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/3FE694D1C9>) |
| 8086:2294 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 3     | sdhci_pci  | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 1217:8621 | 8086:2073 | O2 Micro         | SD/MMC Card Reader Controller        | 2     | sdhci_pci  | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:2296 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | sdhci_pci  | [BCA2FBA811](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-107/EE9273A450D4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/BCA2FBA811>) |
| 8086:9d2d | 8086:2063 | Intel            | Sunrise Point-LP Secure Digital I... | 2     | sdhci_pci  | [55045AA9E5](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-12.2-P4/12.2-RELEASE-P4/AMD64/55045AA9E5>) |
| 1022:7813 | 1022:7806 | AMD              | FCH SD Flash Controller              | 1     | sdhci_pci  | [4433B8842F](<Mini Pc/CompuLab/fit-PC/fit-PC4/EAC3D2695650/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/4433B8842F>) |
| 1217:8620 | 1217:0002 | O2 Micro         | BayHubTech/O2Micro Integrated MMC... | 1     | sdhci_pci  | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1217:8621 | 8086:2064 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 8086:0f16 | 8086:0f16 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | sdhci_pci  | [C577B93FEB](<Mini Pc/AMI/Aptio/Aptio CRB/0928F5EC9BF4/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/C577B93FEB>) |
| 8086:0f50 |           | Intel            | Atom Processor E3800 Series eMMC ... | 1     | sdhci_pci  | [19ED08C39C](<Mini Pc/AMI/Aptio/Aptio CRB/B514BDB172DC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19ED08C39C>) |
| 8086:2294 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | sdhci_pci  | [2C106472CB](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-107/ACD48A55CB15/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/2C106472CB>) |
| 8086:31cc | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 1     | sdhci_pci  | [A9FC936957](<Mini Pc/Fanless Mini PC/Quieter/Quieter2/11504DDAB29B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/A9FC936957>) |
| 8086:5aca | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:5acc | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5ac8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     |            | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:9da4 | 8086:2074 | Intel            | Cannon Point-LP SPI Controller       | 9     |            | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:02a4 | 8086:2081 | Intel            | Comet Lake SPI (flash) Controller    | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:02e8 | 8086:2081 | Intel            | Serial IO I2C Host Controller        | 6     | ig4iic     | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:02ea | 8086:2081 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 6     | ig4iic     | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:9da4 | 17aa:314d | Intel            | Cannon Point-LP SPI Controller       | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 10ec:816c | 1043:85b5 | Realtek Semic... | RTL8111xP IPMI interface             | 4     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:5ac8 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 4     |            | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:a324 | 17aa:312d | Intel            | Cannon Lake PCH SPI Controller       | 3     |            | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 8086:06a4 | 17aa:3172 | Intel            | Comet Lake PCH SPI Controller        | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:22c6 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     |            | [BCA2FBA811](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-107/EE9273A450D4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/BCA2FBA811>) |
| 8086:22c7 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     |            | [BCA2FBA811](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-107/EE9273A450D4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/BCA2FBA811>) |
| 8086:a324 | 17aa:3136 | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:a324 | 8086:2089 | Intel            | Cannon Lake PCH SPI Controller       | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:a368 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:a369 | 8086:2089 | Intel            | Cannon Lake PCH Serial IO I2C Con... | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 10ec:816c | 103c:8522 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [CAE055641A](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/CAE055641A>) |
| 10ec:816c | 103c:8523 | Realtek Semic... | RTL8111xP IPMI interface             | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1425:4602 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Storage Cont... | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 8086:02a4 | 19da:b426 | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:9de8 | 17aa:314d | Intel            | Cannon Point-LP Serial IO I2C Con... | 1     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:a324 | 17aa:3135 | Intel            | Cannon Lake PCH SPI Controller       | 1     |            | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5a8c |           | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 19    |            | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:318c | 8086:318c | Intel            | Celeron/Pentium Silver Processor ... | 17    |            | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:31ac | 8086:31ac | Intel            | Celeron/Pentium Silver Processor ... | 17    | ig4iic     | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:31b2 | 8086:31b2 | Intel            | Celeron/Pentium Silver Processor ... | 17    | ig4iic     | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:5abc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | uart       | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5abe | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | uart       | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5ac0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | uart       | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5aee | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 13    | uart       | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:318c | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 12    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5ab0 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 12    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:31c2 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 11    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:31c4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 11    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:31c6 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 11    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:5aae | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5ab8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:5aba | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | ig4iic     | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:9df9 | 8086:2074 | Intel            | Cannon Point-LP Thermal Controller   | 9     | pchtherm   | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:9d31 | 8086:2068 | Intel            | Sunrise Point-LP Thermal subsystem   | 8     | pchtherm   | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:31b4 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     | ig4iic     | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:31ba | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     | ig4iic     | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:02f9 | 8086:2081 | Intel            | Comet Lake Thermal Subsytem          | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:9d31 | 8086:7270 | Intel            | Sunrise Point-LP Thermal subsystem   | 6     |            | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 1022:15e4 | 1022:15e4 | AMD              | Sensor Fusion Hub                    | 5     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:1903 | 17aa:314d | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:9df9 | 17aa:314d | Intel            | Cannon Point-LP Thermal Controller   | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:318c | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 4     |            | [E186D750D0](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/05311AA67241/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E186D750D0>) |
| 8086:31ac | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 3     |            | [A9FC936957](<Mini Pc/Fanless Mini PC/Quieter/Quieter2/11504DDAB29B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/A9FC936957>) |
| 8086:5aac | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | ig4iic     | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:5abc |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     |            | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:5ac2 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     |            | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:5ac4 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     |            | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:5ac6 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     |            | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:9d27 | 8086:2063 | Intel            | Sunrise Point-LP Serial IO UART C... | 3     |            | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:9d31 | 8086:2063 | Intel            | Sunrise Point-LP Thermal subsystem   | 3     | pchtherm   | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:a2b1 | 103c:829a | Intel            | 200 Series PCH Thermal Subsystem     | 3     |            | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
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
| 8086:9d60 | 8086:2070 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:9d61 | 8086:2070 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a127 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a131 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | pchtherm   | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a160 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | ig4iic     | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a161 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | ig4iic     | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a162 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     |            | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a379 | 8086:2089 | Intel            | Cannon Lake PCH Thermal Controller   | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:02f9 | 19da:b426 | Intel            | Comet Lake Thermal Subsytem          | 1     | pchtherm   | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:1e24 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     |            | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:5aac | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:a131 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | pchtherm   | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f12 | 8086:0f12 | Intel            | Atom Processor E3800/CE2700 Serie... | 64    | ichsmb     | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | ichsmb     | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 1022:780b | 103c:8103 | AMD              | FCH SMBus Controller                 | 24    | intsmb     | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:1f3c | 8086:7270 | Intel            | Atom processor C2000 PCU SMBus       | 19    | ichsmb     | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:2292 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | ichsmb     | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:31d4 | 8086:31d4 | Intel            | Celeron/Pentium Silver Processor ... | 17    | ichsmb     | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:0f12 | 8086:7270 | Intel            | Atom Processor E3800/CE2700 Serie... | 13    | ichsmb     | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:31d4 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | ichsmb     | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:2292 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    |            | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:5ad4 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    |            | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:9da3 | 8086:2074 | Intel            | Cannon Point-LP SMBus Controller     | 9     |            | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:9ca2 | 8086:2057 | Intel            | Wildcat Point-LP SMBus Controller    | 8     | ichsmb     | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:9d23 | 8086:2068 | Intel            | Sunrise Point-LP SMBus               | 8     | ichsmb     | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:31d4 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     | ichsmb     | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:31d4 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 7     | ichsmb     | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:02a3 | 8086:2081 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:1c22 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | ichsmb     | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:2292 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | ichsmb     | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 8086:9d23 | 8086:7270 | Intel            | Sunrise Point-LP SMBus               | 6     |            | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 1022:790b | 1043:87e7 | AMD              | FCH SMBus Controller                 | 5     | intsmb     | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:9c22 | 8086:7270 | Intel            | 8 Series SMBus Controller            | 5     | ichsmb     | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 8086:9da3 | 17aa:314d | Intel            | Cannon Point-LP SMBus Controller     | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:31d4 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 4     |            | [E186D750D0](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/05311AA67241/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E186D750D0>) |
| 10de:0aa2 | 10de:cb79 | Nvidia           | MCP79 SMBus                          | 3     |            | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:1e22 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family SMBu... | 3     | ichsmb     | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:5ad4 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     |            | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:9d23 | 8086:2063 | Intel            | Sunrise Point-LP SMBus               | 3     | ichsmb     | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:a2a3 | 103c:829a | Intel            | 200 Series/Z370 Chipset Family SM... | 3     | ichsmb     | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:a323 | 17aa:312d | Intel            | Cannon Lake PCH SMBus Controller     | 3     | ichsmb     | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 1002:4385 | 103c:17e2 | AMD              | SBx00 SMBus Controller               | 2     | intsmb     | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 1022:780b | 1022:780b | AMD              | FCH SMBus Controller                 | 2     | intsmb     | [D018E86EA8](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/FDAAE32B0FE7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D018E86EA8>) |
| 8086:06a3 | 17aa:3172 | Intel            | Comet Lake PCH SMBus Controller      | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:9ca2 | 8086:7270 | Intel            | Wildcat Point-LP SMBus Controller    | 2     | ichsmb     | [4CF0FFCBF6](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.1/13.0-STABLE/AMD64/4CF0FFCBF6>) |
| 8086:9d23 | 8086:2070 | Intel            | Sunrise Point-LP SMBus               | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a123 | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | ichsmb     | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a323 | 17aa:3136 | Intel            | Cannon Lake PCH SMBus Controller     | 2     | ichsmb     | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:a323 | 8086:2089 | Intel            | Cannon Lake PCH SMBus Controller     | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 1022:780b | 19da:b208 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 1022:790b | 103c:8522 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:790b | 103c:8523 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:790b | 17aa:3190 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1022:790b | 1854:0309 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 10de:0d79 | 10de:cb89 | Nvidia           | MCP89 SMBus                          | 1     |            | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 8086:02a3 | 19da:b426 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 1     | ichsmb     | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:0f12 | 1071:0740 | Intel            | Atom Processor E3800/CE2700 Serie... | 1     |            | [D514362239](<Mini Pc/AMI/Aptio/Aptio CRB/7AF86A68764E/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/D514362239>) |
| 8086:1c22 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 1     |            | [5F293A8796](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/59BF64F0C06D/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/5F293A8796>) |
| 8086:1c22 | 19da:b202 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     |            | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 8086:1e22 | 19da:a247 | Intel            | 7 Series/C216 Chipset Family SMBu... | 1     |            | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:2292 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [BFD71EFA3B](<Mini Pc/Shuttle/XS35/XS35V5/34C200C6C0F7/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BFD71EFA3B>) |
| 8086:5ad4 | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:8c22 | 19da:b220 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ichsmb     | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:9c22 | 19da:b213 | Intel            | 8 Series SMBus Controller            | 1     |            | [9BCBD09882](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9BCBD09882>) |
| 8086:9c22 | 19da:b246 | Intel            | 8 Series SMBus Controller            | 1     |            | [F3E8035461](<Mini Pc/ZOTAC/ZBOX-CI321/ZBOX-CI321NANO/82AF0F92C578/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F3E8035461>) |
| 8086:9ca2 | 8086:2058 | Intel            | Wildcat Point-LP SMBus Controller    | 1     | ichsmb     | [8BE9390356](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/232CA933512D/FREEBSD-13.0-P4/13.0-RELEASE/AMD64/8BE9390356>) |
| 8086:9ca2 | 8086:9ca2 | Intel            | Wildcat Point-LP SMBus Controller    | 1     |            | [E2B78B7ADA](<Mini Pc/BESSTAR Tech/U500/U500-H/2C1737B432F1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/E2B78B7ADA>) |
| 8086:a123 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | ichsmb     | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 8086:a323 | 17aa:3135 | Intel            | Cannon Lake PCH SMBus Controller     | 1     |            | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f04 | 8086:0f04 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 45    | hdac       | [5D39002367](<Mini Pc/AMI/Aptio/Aptio CRB/F4919BE5C566/OPNSENSE-22.1.1/13.0-STABLE/AMD64/5D39002367>) |
| 8086:5a98 |           | Intel            | Celeron N3350/Pentium N4200/Atom ... | 29    | hdac       | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 1002:1308 | 103c:8103 | AMD              | Kaveri HDMI/DP Audio Controller      | 24    | hdac       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:780d | 103c:8103 | AMD              | FCH Azalia Controller                | 20    | hdac       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:2284 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 16    | hdac       | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:3198 | 10ec:119e | Intel            | Celeron/Pentium Silver Processor ... | 16    | hdac       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:0f04 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 14    | hdac       | [19ED08C39C](<Mini Pc/AMI/Aptio/Aptio CRB/B514BDB172DC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19ED08C39C>) |
| 8086:2284 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | hdac       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:3198 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 11    | hdac       | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:5a98 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 9     | hdac       | [FD3CF39D29](<Mini Pc/CompuLab/fitlet/fitlet2/833E5514E5F2/OPNSENSE-22.1.1/13.0-STABLE/AMD64/FD3CF39D29>) |
| 8086:3198 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 7     | hdac       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:9d71 | 8086:2068 | Intel            | Sunrise Point-LP HD Audio            | 7     | hdac       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:160c | 8086:2057 | Intel            | Broadwell-U Audio Controller         | 6     | hdac       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:1c20 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | hdac       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:3198 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 6     | hdac       | [71F763E932](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/1D5380207E8B/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/71F763E932>) |
| 8086:9ca0 | 8086:2057 | Intel            | Wildcat Point-LP High Definition ... | 6     | hdac       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:9dc8 | 8086:2074 | Intel            | Cannon Point-LP High Definition A... | 6     | hdac       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 1002:1637 | 1002:1637 | AMD              | Renoir Radeon High Definition Aud... | 5     | hdac       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:2284 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 5     | hdac       | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 1022:15e3 | 1043:87bc | AMD              | Family 17h/19h HD Audio Controller   | 4     | hdac       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:3198 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 4     | hdac       | [E186D750D0](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/05311AA67241/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E186D750D0>) |
| 8086:9c20 | 8086:7270 | Intel            | 8 Series HD Audio Controller         | 4     | hdac       | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 8086:9dc8 | 17aa:314d | Intel            | Cannon Point-LP High Definition A... | 4     | hdac       | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 1002:15de | 1002:15de | AMD              | Raven/Raven2/Fenghuang HDMI/DP Au... | 3     | hdac       | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 10de:0ac0 | 10de:cb79 | Nvidia           | MCP79 High Definition Audio          | 3     | hdac       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:02c8 | 8086:2081 | Intel            | Comet Lake PCH-LP cAVS               | 3     | hdac       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:0a0c | 106b:0141 | Intel            | Haswell-ULT HD Audio Controller      | 3     | hdac       | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 8086:1e20 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family High... | 3     | hdac       | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:9d71 | 8086:7270 | Intel            | Sunrise Point-LP HD Audio            | 3     | hdac       | [8B09F64067](<Mini Pc/ZOTAC/ZBOX-MI640/ZBOX-MI640-MI660-MI620NANO/534B30206DF1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/8B09F64067>) |
| 8086:a2f0 | 103c:829a | Intel            | 200 Series PCH HD Audio              | 3     | hdac       | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:a348 | 17aa:312d | Intel            | Cannon Lake PCH cAVS                 | 3     | hdac       | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 1002:1314 | 103c:17e2 | AMD              | Wrestler HDMI Audio                  | 2     | hdac       | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 1002:4383 | 103c:17e2 | AMD              | SBx00 Azalia (Intel HDA)             | 2     | hdac       | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 1002:9840 | 1002:9840 | AMD              | Kabini HDMI/DP Audio                 | 2     | hdac       | [D018E86EA8](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/FDAAE32B0FE7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D018E86EA8>) |
| 1002:aa90 | 0000:aa90 | AMD              | Turks HDMI Audio [Radeon HD 6500/... | 2     | hdac       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 1002:ab08 | 8086:2073 | AMD              | Polaris 22 HDMI Audio                | 2     | hdac       | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:160c | 19da:b246 | Intel            | Broadwell-U Audio Controller         | 2     | hdac       | [4CF0FFCBF6](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.1/13.0-STABLE/AMD64/4CF0FFCBF6>) |
| 8086:5a98 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 2     | hdac       | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:9ca0 | 8086:7270 | Intel            | Wildcat Point-LP High Definition ... | 2     | hdac       | [4CF0FFCBF6](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.1/13.0-STABLE/AMD64/4CF0FFCBF6>) |
| 8086:9d70 | 8086:2063 | Intel            | Sunrise Point-LP HD Audio            | 2     | hdac       | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:9d71 | 8086:2070 | Intel            | Sunrise Point-LP HD Audio            | 2     | hdac       | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a171 | 8086:2073 | Intel            | CM238 HD Audio Controller            | 2     | hdac       | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a348 | 17aa:3136 | Intel            | Cannon Lake PCH cAVS                 | 2     | hdac       | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:a348 | 8086:2089 | Intel            | Cannon Lake PCH cAVS                 | 2     | hdac       | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 1002:1637 | 17aa:3190 | AMD              | Renoir Radeon High Definition Aud... | 1     | hdac       | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1002:9840 | 19da:b208 | AMD              | Kabini HDMI/DP Audio                 | 1     | hdac       | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 1022:15e3 | 103c:8522 | AMD              | Family 17h/19h HD Audio Controller   | 1     | hdac       | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15e3 | 103c:8523 | AMD              | Family 17h/19h HD Audio Controller   | 1     | hdac       | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:15e3 | 1043:8820 | AMD              | Family 17h/19h HD Audio Controller   | 1     | hdac       | [2781B31F9B](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50-E1/A2FA457F7B31/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/2781B31F9B>) |
| 1022:15e3 | 17aa:3190 | AMD              | Family 17h/19h HD Audio Controller   | 1     | hdac       | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1022:15e3 | 1854:0309 | AMD              | Family 17h/19h HD Audio Controller   | 1     | hdac       | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 1022:780d | 1022:780d | AMD              | FCH Azalia Controller                | 1     | hdac       | [4433B8842F](<Mini Pc/CompuLab/fit-PC/fit-PC4/EAC3D2695650/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/4433B8842F>) |
| 1022:780d | 19da:b208 | AMD              | FCH Azalia Controller                | 1     | hdac       | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 10de:0d94 | 10de:cb89 | Nvidia           | MCP89 High Definition Audio          | 1     | hdac       | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 8086:02c8 | 19da:b426 | Intel            | Comet Lake PCH-LP cAVS               | 1     | hdac       | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:06c8 | 17aa:3172 | Intel            | Comet Lake PCH cAVS                  | 1     | hdac       | [3004D2300D](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFCTO1WW/36D1FBCE4F17/FREEBSD-12.2-P2/12.2-RELEASE-P1/AMD64/3004D2300D>) |
| 8086:0a0c | 19da:b213 | Intel            | Haswell-ULT HD Audio Controller      | 1     | hdac       | [9BCBD09882](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9BCBD09882>) |
| 8086:0a0c | 19da:b246 | Intel            | Haswell-ULT HD Audio Controller      | 1     | hdac       | [F3E8035461](<Mini Pc/ZOTAC/ZBOX-CI321/ZBOX-CI321NANO/82AF0F92C578/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F3E8035461>) |
| 8086:0a0c | 8086:2010 | Intel            | Haswell-ULT HD Audio Controller      | 1     | hdac       | [39EE26926C](<Mini Pc/CompuLab/Intense-PC/Intense-PC2/084450D07AD2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/39EE26926C>) |
| 8086:0c0c | 19da:b220 | Intel            | Xeon E3-1200 v3/4th Gen Core Proc... | 1     | hdac       | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:0f04 | 1071:0740 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | hdac       | [D514362239](<Mini Pc/AMI/Aptio/Aptio CRB/7AF86A68764E/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/D514362239>) |
| 8086:0f04 | 1170:0530 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 1     | hdac       | [D156760FE8](<Mini Pc/WYSE/Dell/Dell Wyse Thin Client Desktop 3290/AF0EBE39FF8F/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/D156760FE8>) |
| 8086:160c | 111e:10ec | Intel            | Broadwell-U Audio Controller         | 1     | hdac       | [E2B78B7ADA](<Mini Pc/BESSTAR Tech/U500/U500-H/2C1737B432F1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/E2B78B7ADA>) |
| 8086:160c | 8086:2058 | Intel            | Broadwell-U Audio Controller         | 1     | hdac       | [8BE9390356](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/232CA933512D/FREEBSD-13.0-P4/13.0-RELEASE/AMD64/8BE9390356>) |
| 8086:1c20 | 19da:b202 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | hdac       | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 8086:1e20 | 19da:a247 | Intel            | 7 Series/C216 Chipset Family High... | 1     | hdac       | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:3198 | 10ec:111c | Intel            | Celeron/Pentium Silver Processor ... | 1     |            | [A9FC936957](<Mini Pc/Fanless Mini PC/Quieter/Quieter2/11504DDAB29B/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/A9FC936957>) |
| 8086:3198 | 8086:3198 | Intel            | Celeron/Pentium Silver Processor ... | 1     | hdac       | [F6164BCE3E](<Mini Pc/Chuwi/HeroBox/HeroBox/2E4DCA84F178/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/F6164BCE3E>) |
| 8086:5a98 | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | hdac       | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:8c20 | 19da:b220 | Intel            | 8 Series/C220 Series Chipset High... | 1     | hdac       | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:9c20 | 19da:b213 | Intel            | 8 Series HD Audio Controller         | 1     | hdac       | [9BCBD09882](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9BCBD09882>) |
| 8086:9c20 | 19da:b246 | Intel            | 8 Series HD Audio Controller         | 1     | hdac       | [F3E8035461](<Mini Pc/ZOTAC/ZBOX-CI321/ZBOX-CI321NANO/82AF0F92C578/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F3E8035461>) |
| 8086:9ca0 | 8086:2058 | Intel            | Wildcat Point-LP High Definition ... | 1     | hdac       | [8BE9390356](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/232CA933512D/FREEBSD-13.0-P4/13.0-RELEASE/AMD64/8BE9390356>) |
| 8086:9ca0 | 8086:9ca0 | Intel            | Wildcat Point-LP High Definition ... | 1     | hdac       | [E2B78B7ADA](<Mini Pc/BESSTAR Tech/U500/U500-H/2C1737B432F1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/E2B78B7ADA>) |
| 8086:a170 | 8086:2064 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | hdac       | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 8086:a348 | 17aa:3135 | Intel            | Cannon Lake PCH cAVS                 | 1     | hdac       | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f23 | 8086:0f23 | Intel            | Atom Processor E3800 Series SATA ... | 63    | ahci       | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | ahci       | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 1022:7801 | 103c:8103 | AMD              | FCH SATA Controller [AHCI mode]      | 23    | ahci       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:1f32 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA3 C... | 18    | ahci       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:22a3 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | ahci       | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:1f22 | 8086:7270 | Intel            | Atom processor C2000 AHCI SATA2 C... | 17    | ahci       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:31e3 | 8086:31e3 | Intel            | Celeron/Pentium Silver Processor ... | 17    | ahci       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:0f23 | 8086:7270 | Intel            | Atom Processor E3800 Series SATA ... | 13    | ahci       | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:31e3 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | ahci       | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:22a3 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | ahci       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:5ae3 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | ahci       | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:9c83 | 8086:2057 | Intel            | Wildcat Point-LP SATA Controller ... | 8     | ahci       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:9d03 | 8086:2068 | Intel            | Sunrise Point-LP SATA Controller ... | 8     | ahci       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:9dd3 | 8086:2074 | Intel            | Cannon Point-LP SATA Controller [... | 8     | ahci       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:31e3 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     | ahci       | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:31e3 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 7     | ahci       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:1c03 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | ahci       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:22a3 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 6     | ahci       | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 8086:9d03 | 8086:7270 | Intel            | Sunrise Point-LP SATA Controller ... | 6     | ahci       | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 1022:7901 | 1043:87e7 | AMD              | FCH SATA Controller [AHCI mode]      | 5     | ahci       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:9c03 | 8086:7270 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 5     | ahci       | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 10de:0ab9 | 10de:cb79 | Nvidia           | MCP79 AHCI Controller                | 3     | ahci       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:02d3 | 8086:2081 | Intel            | Comet Lake SATA AHCI Controller      | 3     | ahci       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:31e3 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 3     | ahci       | [E186D750D0](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/05311AA67241/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E186D750D0>) |
| 8086:5ae3 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | ahci       | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:a282 | 103c:829a | Intel            | 200 Series PCH SATA controller [A... | 3     | ahci       | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:a352 | 17aa:312d | Intel            | Cannon Lake PCH SATA AHCI Controller | 3     | ahci       | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 1022:7801 | 1022:7801 | AMD              | FCH SATA Controller [AHCI mode]      | 2     | ahci       | [D018E86EA8](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/FDAAE32B0FE7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D018E86EA8>) |
| 8086:06d2 | 17aa:3172 | Intel            | Comet Lake SATA AHCI Controller      | 2     | ahci       | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:1e03 | 8086:7270 | Intel            | 7 Series Chipset Family 6-port SA... | 2     | ahci       | [AC585B4E0D](<Mini Pc/Apple/Macmini6/Macmini6,2/FAC8616568BC/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/AC585B4E0D>) |
| 8086:9c83 | 8086:7270 | Intel            | Wildcat Point-LP SATA Controller ... | 2     | ahci       | [4CF0FFCBF6](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.1/13.0-STABLE/AMD64/4CF0FFCBF6>) |
| 8086:9d03 | 8086:2063 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:9d03 | 8086:2070 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a352 | 17aa:3136 | Intel            | Cannon Lake PCH SATA AHCI Controller | 2     | ahci       | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:a353 | 8086:2089 | Intel            | Cannon Lake Mobile PCH SATA AHCI ... | 2     | ahci       | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 1002:4391 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1     | ahci       | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 1022:7801 | 19da:b208 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 1022:7901 | 103c:8522 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:7901 | 1854:0309 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 10de:0d88 | 106b:cb89 | Nvidia           | MCP89 SATA Controller (AHCI mode)    | 1     | ahci       | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 1b21:0612 | 1b21:1060 | ASMedia Techn... | ASM1062 Serial ATA Controller        | 1     | ahci       | [B86C21F11A](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/3BC14659C185/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/B86C21F11A>) |
| 1b4b:9215 | 1b4b:9215 | Marvell Techn... | 88SE9215 PCIe 2.0 x1 4-port SATA ... | 1     | ahci       | [C577B93FEB](<Mini Pc/AMI/Aptio/Aptio CRB/0928F5EC9BF4/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/C577B93FEB>) |
| 8086:0f23 | 1071:0740 | Intel            | Atom Processor E3800 Series SATA ... | 1     | ahci       | [D514362239](<Mini Pc/AMI/Aptio/Aptio CRB/7AF86A68764E/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/D514362239>) |
| 8086:1c02 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ahci       | [5F293A8796](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/59BF64F0C06D/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/5F293A8796>) |
| 8086:1c02 | 19da:b202 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ahci       | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 8086:1e03 | 19da:a247 | Intel            | 7 Series Chipset Family 6-port SA... | 1     | ahci       | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:22a3 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | ahci       | [BFD71EFA3B](<Mini Pc/Shuttle/XS35/XS35V5/34C200C6C0F7/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BFD71EFA3B>) |
| 8086:8c02 | 19da:b220 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ahci       | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:9c03 | 19da:b213 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 1     | ahci       | [9BCBD09882](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9BCBD09882>) |
| 8086:9c03 | 19da:b246 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 1     | ahci       | [F3E8035461](<Mini Pc/ZOTAC/ZBOX-CI321/ZBOX-CI321NANO/82AF0F92C578/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F3E8035461>) |
| 8086:9c83 | 8086:2058 | Intel            | Wildcat Point-LP SATA Controller ... | 1     | ahci       | [8BE9390356](<Mini Pc/Intel/NUC5i5MYBE/NUC5i5MYBE H47797-205/232CA933512D/FREEBSD-13.0-P4/13.0-RELEASE/AMD64/8BE9390356>) |
| 8086:9c83 | 8086:9c83 | Intel            | Wildcat Point-LP SATA Controller ... | 1     | ahci       | [E2B78B7ADA](<Mini Pc/BESSTAR Tech/U500/U500-H/2C1737B432F1/OPNSENSE-21.7.2/12.1-RELEASE-P20-HBSD/AMD64/E2B78B7ADA>) |
| 8086:a352 | 17aa:3135 | Intel            | Cannon Lake PCH SATA AHCI Controller | 1     | ahci       | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |

### Storage/ide (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:780c | 103c:8103 | AMD              | FCH IDE Controller                   | 24    | atapci     | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1002:4390 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 SATA Controller... | 1     | ahci       | [BBD5813F92](<Mini Pc/Hewlett-Packard/t610/t610 PLUS WW Thin Client/7275C6CFC845/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BBD5813F92>) |
| 1022:7800 | 103c:8103 | AMD              | FCH SATA Controller [IDE mode]       | 1     | ahci       | [364241899F](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/E658728E0DEE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/364241899F>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 11    | nvme       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 7     | nvme       | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 4     | nvme       | [8CE7E3A180](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AHS0B200/FCC1BB1C23E5/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/8CE7E3A180>) |
| 126f:2263 | 126f:2263 | Silicon Motion   | SM2263EN/SM2263XT SSD Controller     | 3     | nvme       | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 1bb1:5016 | 1bb1:5016 | Seagate Techn... | FireCuda 520 SSD                     | 2     | nvme       | [A09FBE5FCC](<Mini Pc/Intel Client Systems/NUC10/NUC10i5FNH/1FFBE51038AD/OPNSENSE-21.1.5/12.1-RELEASE-P16-HBSD/AMD64/A09FBE5FCC>) |
| 1179:0113 | 1179:0001 | Toshiba          | BG3 NVMe SSD Controller              | 1     | nvme       | [E057495CA3](<Mini Pc/Intel/NUC6i3SYB/NUC6i3SYB H81132-505/E0C236805F04/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/E057495CA3>) |
| 144d:a802 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM951/PM951      | 1     | nvme       | [8A7B8618BF](<Mini Pc/Intel/NUC5i5RYB/NUC5i5RYB H40999-506/6D0E5ABCF660/FREEBSD-12.2/12.2-RELEASE/AMD64/8A7B8618BF>) |
| 15b7:5002 | 15b7:5002 | Sandisk          | WD Black 2018/SN750 / PC SN720 NV... | 1     | nvme       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 15b7:5005 | 15b7:5005 | Sandisk          | PC SN520 NVMe SSD                    | 1     | nvme       | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 15b7:5006 | 15b7:5006 | Sandisk          | WD Black SN750 / PC SN730 NVMe SSD   | 1     | nvme       | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |
| 1987:5012 | 1987:5012 | Phison Electr... | E12 NVMe Controller                  | 1     | nvme       | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 1987:5013 | 1987:5013 | Phison Electr... | PS5013 E13 NVMe Controller           | 1     | nvme       | [5A0B61AC41](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3102303AC861/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/5A0B61AC41>) |
| 1b85:6018 | 1b85:6018 | OCZ Technolog... | RD400/400A SSD                       | 1     | nvme       | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 1bb1:5012 | 1bb1:5012 | Seagate Techn... | FireCuda 510 SSD                     | 1     | nvme       | [07221FC111](<Mini Pc/Intel Client Systems/NUC8/NUC8i3BEH/1BC2519D6516/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/07221FC111>) |
| 1c5c:1627 | 1c5c:1627 | SK Hynix         | hynix unknown                        | 1     | nvme       | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 1c5c:174a | 1c5c:174a | SK Hynix         | Gold P31 SSD                         | 1     | nvme       | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1cc1:8201 | 1cc1:8201 | ADATA Technology | XPG SX8200 Pro PCIe Gen3x4 M.2 22... | 1     | nvme       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 1cc4:17ab | 1cc4:1007 | Union Memory ... | NVMe 256G SSD device                 | 1     | nvme       | [D15116D2EB](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T7CTO1WW/2D340AE8DBBC/OPNSENSE-20.7.8/12.1-RELEASE-P12-HBSD/AMD64/D15116D2EB>) |
| 1d79:2263 | 1d79:2263 |                  |                                      | 1     | nvme       | [3AB33909B0](<Mini Pc/Intel/NUC8/NUC8i7HVK/2CD30E743AF3/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/3AB33909B0>) |
| 2646:2262 | 2646:2262 | Kingston Tech... | KC2000 NVMe SSD                      | 1     | nvme       | [DBACAA5C65](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/074E7A095987/OPNSENSE-21.1.8/12.1-RELEASE-P19-HBSD/AMD64/DBACAA5C65>) |
| 2646:2263 | 2646:2263 | Kingston Tech... | A2000 NVMe SSD                       | 1     | nvme       | [CCC091CDC9](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNK/F06FF3B14557/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/CCC091CDC9>) |
| c0a9:540a | c0a9:540a | Micron/Crucia... | P2 NVMe PCIe SSD                     | 1     | nvme       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:282a | 8086:7270 | Intel            | 82801 Mobile SATA Controller [RAI... | 2     | ahci       | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:282a | 8086:2081 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [A15B01E8FA](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/D6C049FF87E6/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/A15B01E8FA>) |

### Storage/scsi (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1425:4502 | 1014:03e5 | Chelsio Commu... | T422-CR Unified Wire Storage Cont... | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1423 | 103c:8103 | AMD              | Family 15h (Models 30h-3fh) I/O M... | 24    |            | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:1f15 |           | Intel            | Atom processor C2000 SMBus 2.0       | 19    |            | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:1f16 |           | Intel            | Atom processor C2000 RCEC            | 19    |            | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:3190 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 11    |            | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:1911 | 8086:2074 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 9     |            | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:1911 | 8086:2068 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 8     |            | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:3190 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     |            | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:1911 | 8086:2015 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 8086:1911 | 8086:2081 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 6     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 1022:1631 | 1022:1631 | AMD              | Renoir/Cezanne IOMMU                 | 5     |            | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:15e8 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 5     |            | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:1911 | 17aa:314d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 5     |            | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 8086:3190 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 4     |            | [E186D750D0](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/05311AA67241/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E186D750D0>) |
| 8086:1513 | 2222:1111 | Intel            | CV82524 Thunderbolt Controller [L... | 3     |            | [8CD83326F3](<Mini Pc/Apple/Macmini5/Macmini5,1/FA1265ADE548/OPNSENSE-22.1.1/13.0-STABLE/AMD64/8CD83326F3>) |
| 8086:156c |           | Intel            | DSL5520 Thunderbolt 2 NHI [Falcon... | 3     |            | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 8086:1911 | 17aa:312d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 8086:15eb | 8086:2088 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:1911 | 17aa:3136 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:1911 | 17aa:3172 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:1911 | 8086:2070 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:1911 | 8086:2073 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:1911 | 8086:2089 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:22c0 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     |            | [BCA2FBA811](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-107/EE9273A450D4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/BCA2FBA811>) |
| 1022:15d1 | 103c:8522 | AMD              | Raven/Raven2 IOMMU                   | 1     |            | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15d1 | 103c:8523 | AMD              | Raven/Raven2 IOMMU                   | 1     |            | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:1631 | 17aa:3190 | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 8086:1911 | 17aa:3135 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [497DD29170](<Mini Pc/Lenovo/ThinkStation/ThinkStation P330 Tiny 30CF000BUS/7284B3B90AF9/OPNSENSE-21.7.5/12.1-RELEASE-P21-HBSD/AMD64/497DD29170>) |
| 8086:1911 | 19da:b426 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:1911 | 8086:2064 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [6F89733E13](<Mini Pc/Intel/NUC6i7KYB/NUC6i7KYB H90766-402/3020FDAFF6F6/GHOSTBSD-20.04.02/13.0-STABLE/AMD64/6F89733E13>) |
| 8086:3190 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 1     |            | [D910596224](<Mini Pc/Intel Client Systems/NUC7/NUC7CJYH/FF6AA98E51FB/FREEBSD-12.1-P5/12.1-RELEASE-P3/AMD64/D910596224>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:0f35 | 8086:0f35 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 57    | xhci       | [25F6419F30](<Mini Pc/AMI/Aptio/Aptio CRB/E8776A861ADD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/25F6419F30>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 32    | xhci       | [6024B9491D](<Mini Pc/AWOW/PC/PC BOX/E8F03AADB8BD/OPNSENSE-22.1.2/13.0-STABLE/AMD64/6024B9491D>) |
| 8086:0f34 | 8086:0f34 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 28    | ehci       | [19ED08C39C](<Mini Pc/AMI/Aptio/Aptio CRB/B514BDB172DC/OPNSENSE-22.1.2/13.0-STABLE/AMD64/19ED08C39C>) |
| 1022:7807 | 103c:8103 | AMD              | FCH USB OHCI Controller              | 24    | ohci       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:7808 | 103c:8103 | AMD              | FCH USB EHCI Controller              | 24    | ehci       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 1022:7814 | 103c:8103 | AMD              | FCH USB XHCI Controller              | 24    | xhci       | [23B35E5B18](<Mini Pc/Hewlett-Packard/t730/t730 Thin Client/ED606F23D5B5/OPNSENSE-22.1.2/13.0-STABLE/AMD64/23B35E5B18>) |
| 8086:1f2c | 8086:7270 | Intel            | Atom processor C2000 USB Enhanced... | 19    | ehci       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 1912:0014 | 15d9:0813 | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 18    | xhci       | [0F1362E9A9](<Mini Pc/Supermicro/SYS-5018/SYS-5018A-TN4/DB4E9ECD1274/OPNSENSE-22.1.2/13.0-STABLE/AMD64/0F1362E9A9>) |
| 8086:22b5 | 8086:7270 | Intel            | Atom/Celeron/Pentium Processor x5... | 18    | xhci       | [C6CAEFEBE6](<Mini Pc/AMI/Aptio/Aptio CRB/E84779F8F0F6/OPNSENSE-22.1.1/13.0-STABLE/AMD64/C6CAEFEBE6>) |
| 8086:31a8 | 8086:31a8 | Intel            | Celeron/Pentium Silver Processor ... | 17    | xhci       | [BB895C5DF3](<Mini Pc/BESSTAR Tech/N/N40/1960C8C916FA/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/BB895C5DF3>) |
| 8086:0f35 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 12    | xhci       | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:31a8 | 8086:7270 | Intel            | Celeron/Pentium Silver Processor ... | 12    | xhci       | [73726DFE1A](<Mini Pc/ZOTAC/ZBOX-CI329/ZBOX-CI329NANO/E3DDA56CAF35/OPNSENSE-22.1.2/13.0-STABLE/AMD64/73726DFE1A>) |
| 8086:22b5 | 19da:b301 | Intel            | Atom/Celeron/Pentium Processor x5... | 11    | xhci       | [59CEE41440](<Mini Pc/ZOTAC/ZBOX-CI323/ZBOX-CI323NANO/F4E62A371E22/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/59CEE41440>) |
| 8086:5aa8 | 19da:b325 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 11    | xhci       | [C6A0BD2277](<Mini Pc/ZOTAC/ZBOX-CI327/ZBOX-CI327NANO-GS-01/2D5523DF5C7C/OPNSENSE-22.1/13.0-STABLE/AMD64/C6A0BD2277>) |
| 8086:0f34 | 8086:7270 | Intel            | Atom Processor Z36xxx/Z37xxx Seri... | 9     | ehci       | [3CFEB5C1B0](<Mini Pc/AMI/Aptio/Aptio CRB/702045BCBCE6/OPNSENSE-22.1.2/13.0-STABLE/AMD64/3CFEB5C1B0>) |
| 8086:9ded | 8086:2074 | Intel            | Cannon Point-LP USB 3.1 xHCI Cont... | 9     | xhci       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:9ca6 | 8086:2057 | Intel            | Wildcat Point-LP USB EHCI Controller | 8     | ehci       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:9cb1 | 8086:2057 | Intel            | Wildcat Point-LP USB xHCI Controller | 8     | xhci       | [342915FCCD](<Mini Pc/Intel Client Systems/NUC5/NUC5i3RYH/E6CECB6E29C9/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/342915FCCD>) |
| 8086:9d2f | 8086:2068 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 8     | xhci       | [BF63607CD6](<Mini Pc/Intel/NUC7/NUC7i3BNK/449CF79D838D/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/BF63607CD6>) |
| 8086:31a8 | 1028:080c | Intel            | Celeron/Pentium Silver Processor ... | 7     | xhci       | [AC38D3156D](<Mini Pc/Dell/Wyse/Wyse 5070 Thin Client/6159C9CD886E/OPNSENSE-22.1.2/13.0-STABLE/AMD64/AC38D3156D>) |
| 8086:31a8 | 8086:2072 | Intel            | Celeron/Pentium Silver Processor ... | 7     | xhci       | [5F657BDB2A](<Mini Pc/Intel/NUC7/NUC7PJYH/00FA66A2DAAA/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/5F657BDB2A>) |
| 8086:02ed | 8086:2081 | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 6     | xhci       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:15e9 | 8086:2081 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 6     | xhci       | [839EED529D](<Mini Pc/Intel Client Systems/NUC10/NUC10i7FNH/0DAB18E95372/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/839EED529D>) |
| 8086:1c26 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | ehci       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:1c27 | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | uhci       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:1c2c | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | uhci       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:1c2d | 8086:7270 | Intel            | 6 Series/C200 Series Chipset Fami... | 6     | ehci       | [D73D3760CE](<Mini Pc/Apple/Macmini5/Macmini5,2/0B1FF4B63B01/OPNSENSE-21.7.8/12.1-RELEASE-P22-HBSD/AMD64/D73D3760CE>) |
| 8086:9d2f | 8086:7270 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 6     | xhci       | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 1022:1639 | 1043:87e7 | AMD              | Renoir/Cezanne USB 3.1               | 5     | xhci       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1b21:1142 | 1043:85bf | ASMedia Techn... | ASM1042A USB 3.0 Host Controller     | 5     | xhci       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 1b21:2142 | 1b21:2142 | ASMedia Techn... | ASM2142 USB 3.1 Host Controller      | 5     | xhci       | [C301B3F8F3](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547/38AFFE393D61/OPNSENSE-22.1/12.1-RELEASE-P21-HBSD/AMD64/C301B3F8F3>) |
| 8086:9c31 | 8086:7270 | Intel            | 8 Series USB xHCI HC                 | 5     | xhci       | [52F4BDD7D0](<Mini Pc/Apple/Macmini7/Macmini7,1/2E29BB8A95CD/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/52F4BDD7D0>) |
| 8086:9ded | 17aa:314d | Intel            | Cannon Point-LP USB 3.1 xHCI Cont... | 5     | xhci       | [34DCF2865B](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M90n-1 11AH000UUS/8B5C11A17DC9/OPNSENSE-21.7.4/12.1-RELEASE-P20-HBSD/AMD64/34DCF2865B>) |
| 10ec:816d | 1043:85b5 | Realtek Semic... | RTL811x EHCI host controller         | 4     | ehci       | [7EA8DAAE8D](<Mini Pc/ASUSTek Computer/MINIPC/MINIPC PN50/3509F5558F2E/FREEBSD-14.0-CURRENT/14.0-CURRENT/AMD64/7EA8DAAE8D>) |
| 8086:22b5 |           | Intel            | Atom/Celeron/Pentium Processor x5... | 4     | xhci       | [5F4E1C30B8](<Mini Pc/Intel/NUC5CPYB/NUC5CPYB H61145-404/7C93D5BC2B5B/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/5F4E1C30B8>) |
| 8086:31a8 | 19da:b423 | Intel            | Celeron/Pentium Silver Processor ... | 4     | xhci       | [E186D750D0](<Mini Pc/ZOTAC/ZBOX-CI/ZBOX-CI341/05311AA67241/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/E186D750D0>) |
| 10de:0aa5 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 3     | ohci       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0aa6 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 3     | ehci       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0aa7 | 10de:cb79 | Nvidia           | MCP79 OHCI USB 1.1 Controller        | 3     | ohci       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 10de:0aa9 | 10de:cb79 | Nvidia           | MCP79 EHCI USB 2.0 Controller        | 3     | ehci       | [3ADA7B4079](<Mini Pc/Apple/Macmini3/Macmini3,1/351DAEE883C8/GHOSTBSD-21.08.27/13.0-STABLE/AMD64/3ADA7B4079>) |
| 8086:1e26 | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 3     | ehci       | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:1e2d | 8086:7270 | Intel            | 7 Series/C216 Chipset Family USB ... | 3     | ehci       | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:1e31 | 8086:7270 | Intel            | 7 Series/C210 Series Chipset Fami... | 3     | xhci       | [9AFA228B2A](<Mini Pc/CompuLab/1160405/1160405-00003/F23C44F7BDBE/OPNSENSE-22.1/13.0-STABLE/AMD64/9AFA228B2A>) |
| 8086:5aa8 | 8086:2067 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 3     | xhci       | [97FA44AFB7](<Mini Pc/Intel/NUC6CAYB/NUC6CAYB J23203-403/6BF8DE639918/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/97FA44AFB7>) |
| 8086:9d2f | 8086:2063 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 3     | xhci       | [946C9ACC2E](<Mini Pc/Intel/NUC6i5SYB/NUC6i5SYB H81131-503/D0730AF2AA43/FREEBSD-13.0-P7/13.0-RELEASE-P7/AMD64/946C9ACC2E>) |
| 8086:a2af | 103c:829a | Intel            | 200 Series/Z370 Chipset Family US... | 3     | xhci       | [43609B166F](<Mini Pc/Hewlett-Packard/EliteDesk/EliteDesk 800 G3 DM 35W/4E1CCB5274C9/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/43609B166F>) |
| 8086:a36d | 17aa:312d | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 3     | xhci       | [72B461DED3](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M720q 10T8S2A30S/60973AF7BC90/OPNSENSE-22.1/13.0-STABLE/AMD64/72B461DED3>) |
| 1002:4396 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB EHCI Contro... | 2     | ehci       | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 1002:4397 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI0 Contr... | 2     | ohci       | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 1022:7808 | 1022:7808 | AMD              | FCH USB EHCI Controller              | 2     | ehci       | [D018E86EA8](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/FDAAE32B0FE7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D018E86EA8>) |
| 1022:7814 | 1022:7812 | AMD              | FCH USB XHCI Controller              | 2     | xhci       | [D018E86EA8](<Mini Pc/WYSE/Dell/Dell Thin Client Desktop 5060/FDAAE32B0FE7/OPNSENSE-22.1.2/13.0-STABLE/AMD64/D018E86EA8>) |
| 104c:8241 | 103c:17e2 | Texas Instrum... | TUSB73x0 SuperSpeed USB 3.0 xHCI ... | 2     | xhci       | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 1b21:2142 | 8086:2073 | ASMedia Techn... | ASM2142 USB 3.1 Host Controller      | 2     | xhci       | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:06ed | 17aa:3172 | Intel            | Comet Lake USB 3.1 xHCI Host Cont... | 2     | xhci       | [1F7035C993](<Mini Pc/Lenovo/ThinkStation/ThinkStation P340 Tiny 30DFS05W00/1D77AB0A5D68/OPNSENSE-12.1-P15-HBSD/12.1-RELEASE-P15-HBSD/AMD64/1F7035C993>) |
| 8086:15ec | 8086:2088 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 2     | xhci       | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 8086:22b5 | 8086:2060 | Intel            | Atom/Celeron/Pentium Processor x5... | 2     | xhci       | [BCA2FBA811](<Mini Pc/Intel/NUC5PPYB/NUC5PPYB H76558-107/EE9273A450D4/OPNSENSE-21.7.1/12.1-RELEASE-P19-HBSD/AMD64/BCA2FBA811>) |
| 8086:5aaa | 8086:7270 | Intel            |                                      | 2     |            | [424CA8F515](<Mini Pc/CompuLab/fitlet/fitlet2/FF55AE2FA95D/OPNSENSE-21.1.3/12.1-RELEASE-P14-HBSD/AMD64/424CA8F515>) |
| 8086:9c26 | 8086:7270 | Intel            | 8 Series USB EHCI #1                 | 2     | ehci       | [D8343DC26F](<Mini Pc/ZOTAC/ZBOX-RI323/ZBOX-RI323NANO/7D57F802F474/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/D8343DC26F>) |
| 8086:9ca6 | 8086:7270 | Intel            | Wildcat Point-LP USB EHCI Controller | 2     | ehci       | [4CF0FFCBF6](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.1/13.0-STABLE/AMD64/4CF0FFCBF6>) |
| 8086:9cb1 | 8086:7270 | Intel            | Wildcat Point-LP USB xHCI Controller | 2     | xhci       | [4CF0FFCBF6](<Mini Pc/ZOTAC/ZBOX-MI522/ZBOX-MI522NANO-MI542NANO/447A83A6AB0A/OPNSENSE-22.1/13.0-STABLE/AMD64/4CF0FFCBF6>) |
| 8086:9d2f | 8086:2070 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 2     | xhci       | [3802B33F17](<Mini Pc/Intel/NUC7/NUC7i7DNKE/375B9D3350D3/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/3802B33F17>) |
| 8086:a12f | 8086:2073 | Intel            | 100 Series/C230 Series Chipset Fa... | 2     | xhci       | [7467D71C8D](<Mini Pc/Intel/NUC8/NUC8i7HNK/50716B377685/FREEBSD-13.0/13.0-RELEASE/AMD64/7467D71C8D>) |
| 8086:a36d | 17aa:3136 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 2     | xhci       | [F1892CD12C](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M920q 10RRS5S500/D2CB8BAABEFC/OPNSENSE-22.1.1/13.0-STABLE/AMD64/F1892CD12C>) |
| 8086:a36d | 8086:2089 | Intel            | Cannon Lake PCH USB 3.1 xHCI Host... | 2     | xhci       | [FC0AEA9E0B](<Mini Pc/Intel Client Systems/NUC9/NUC9i5QNX/45746E40B377/OPNSENSE-21.7.3/12.1-RELEASE-P20-HBSD/AMD64/FC0AEA9E0B>) |
| 1002:4399 | 103c:17e2 | AMD              | SB7x0/SB8x0/SB9x0 USB OHCI2 Contr... | 1     | ohci       | [FCB0A5FF87](<Mini Pc/Hewlett-Packard/t610/t610 WW Thin Client/EB715773B3C8/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/FCB0A5FF87>) |
| 1022:15e0 | 103c:8522 | AMD              | Raven USB 3.1                        | 1     | xhci       | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15e0 | 1854:0309 | AMD              | Raven USB 3.1                        | 1     | xhci       | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 1022:15e1 | 103c:8522 | AMD              | Raven USB 3.1                        | 1     | xhci       | [3CC1BA3677](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/3CC1BA3677>) |
| 1022:15e1 | 1854:0309 | AMD              | Raven USB 3.1                        | 1     | xhci       | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 1022:15e5 | 103c:8523 | AMD              | Raven2 USB 3.1                       | 1     | xhci       | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1022:1639 | 17aa:3190 | AMD              | Renoir/Cezanne USB 3.1               | 1     | xhci       | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |
| 1022:7807 | 1022:7807 | AMD              | FCH USB OHCI Controller              | 1     | ohci       | [4433B8842F](<Mini Pc/CompuLab/fit-PC/fit-PC4/EAC3D2695650/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/4433B8842F>) |
| 1022:7807 | 19da:b208 | AMD              | FCH USB OHCI Controller              | 1     | ohci       | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 1022:7808 | 19da:b208 | AMD              | FCH USB EHCI Controller              | 1     | ehci       | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 1022:7814 | 19da:b208 | AMD              | FCH USB XHCI Controller              | 1     | xhci       | [78D3AE05F0](<Mini Pc/ZOTAC/ZBOXNANO-AQ/ZBOXNANO-AQ01/A7BED4F9CF55/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/78D3AE05F0>) |
| 10de:0d9c | 10de:cb89 | Nvidia           | MCP89 OHCI USB 1.1 Controller        | 1     | ohci       | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10de:0d9d | 10de:cb89 | Nvidia           | MCP89 EHCI USB 2.0 Controller        | 1     | ehci       | [4979175779](<Mini Pc/Apple/Macmini4/Macmini4,1/C751E92B8FCE/HELLOSYSTEM-0.7.0/13.0-RELEASE/AMD64/4979175779>) |
| 10ec:816d | 103c:8522 | Realtek Semic... | RTL811x EHCI host controller         | 1     | ehci       | [CAE055641A](<Mini Pc/Hewlett-Packard/t740/t740 Thin Client/E4EB2EC0B3CF/OPNSENSE-22.1/13.0-STABLE/AMD64/CAE055641A>) |
| 10ec:816d | 103c:8523 | Realtek Semic... | RTL811x EHCI host controller         | 1     | ehci       | [D563D65A91](<Mini Pc/Hewlett-Packard/t640/t640 Thin Client/12BD2451B96B/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/D563D65A91>) |
| 1912:0014 |           | Renesas Techn... | uPD720201 USB 3.0 Host Controller    | 1     | xhci       | [DCDC6B58D1](<Mini Pc/Supermicro/A1/A1SAi/56E92D07B5A4/OPNSENSE-21.1.4/12.1-RELEASE-P15-HBSD/AMD64/DCDC6B58D1>) |
| 1912:0015 | 19da:0194 | Renesas Techn... | uPD720202 USB 3.0 Host Controller    | 1     | xhci       | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 1b21:1242 | 1b21:1242 | ASMedia Techn... | ASM1142 USB 3.1 Host Controller      | 1     | xhci       | [6CA50F8007](<Mini Pc/ZOTAC/ZBOX-CI527/ZBOX-CI527-CI547NANO/62C3CCD104D2/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/6CA50F8007>) |
| 8086:02ed | 19da:b426 | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 1     | xhci       | [3A72557967](<Mini Pc/ZOTAC/ZBOX-MI623/ZBOX-MI623-MI643/5CF3A794DCC6/OPNSENSE-22.1/13.0-STABLE/AMD64/3A72557967>) |
| 8086:0f35 | 1071:0740 | Intel            | Atom Processor Z36xxx/Z37xxx, Cel... | 1     | xhci       | [D514362239](<Mini Pc/AMI/Aptio/Aptio CRB/7AF86A68764E/OPNSENSE-21.7/12.1-RELEASE-P19-HBSD/AMD64/D514362239>) |
| 8086:15db | 8086:2074 | Intel            | JHL6340 Thunderbolt 3 USB 3.1 Con... | 1     | xhci       | [B137B25594](<Mini Pc/Intel Client Systems/NUC8/NUC8i5BEH/ABE20D4E9177/FREEBSD-13.1-BETA1/13.1-BETA1/AMD64/B137B25594>) |
| 8086:1c26 | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci       | [5F293A8796](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/59BF64F0C06D/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/5F293A8796>) |
| 8086:1c26 | 19da:b202 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci       | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 8086:1c2d | 1028:04dd | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci       | [5F293A8796](<Mini Pc/Dell/Wyse/Wyse 5070 Extended Thin Client/59BF64F0C06D/OPNSENSE-21.1/12.1-RELEASE-P12-HBSD/AMD64/5F293A8796>) |
| 8086:1c2d | 19da:b202 | Intel            | 6 Series/C200 Series Chipset Fami... | 1     | ehci       | [5056D58118](<Mini Pc/ZOTAC/ZBOX-ID88/ZBOX-ID88-ID89-ID90/38B3B4BCB4F1/OPNSENSE-21.1.2/12.1-RELEASE-P13-HBSD/AMD64/5056D58118>) |
| 8086:1e26 | 19da:a247 | Intel            | 7 Series/C216 Chipset Family USB ... | 1     | ehci       | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:1e2d | 19da:a247 | Intel            | 7 Series/C216 Chipset Family USB ... | 1     | ehci       | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:1e31 | 19da:a247 | Intel            | 7 Series/C210 Series Chipset Fami... | 1     | xhci       | [D8D2CEA545](<Mini Pc/ZOTAC/ZBOXNANO-ID63/ZBOXNANO-ID63-ID64-ID65/B45D5D5687A2/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/D8D2CEA545>) |
| 8086:22b5 | 1297:4033 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | xhci       | [BFD71EFA3B](<Mini Pc/Shuttle/XS35/XS35V5/34C200C6C0F7/OPNSENSE-21.1.6/12.1-RELEASE-P16-HBSD/AMD64/BFD71EFA3B>) |
| 8086:5aa8 | 1019:a6e2 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | xhci       | [8C6988DBE2](<Mini Pc/Ultra Tiny PC/LIVA/LIVA Q1L/10E140342B30/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/8C6988DBE2>) |
| 8086:8c26 | 19da:b220 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ehci       | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:8c2d | 19da:b220 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | ehci       | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:8c31 | 19da:b220 | Intel            | 8 Series/C220 Series Chipset Fami... | 1     | xhci       | [2C65CBD768](<Mini Pc/ZOTAC/ZBOX-ID92/ZBOX-ID92-ZBOX-IQ01/3ADD60929530/OPNSENSE-22.1.2/13.0-STABLE/AMD64/2C65CBD768>) |
| 8086:9c26 | 19da:b213 | Intel            | 8 Series USB EHCI #1                 | 1     | ehci       | [9BCBD09882](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9BCBD09882>) |
| 8086:9c26 | 19da:b246 | Intel            | 8 Series USB EHCI #1                 | 1     | ehci       | [F3E8035461](<Mini Pc/ZOTAC/ZBOX-CI321/ZBOX-CI321NANO/82AF0F92C578/OPNSENSE-21.7.6/12.1-RELEASE-P21-HBSD/AMD64/F3E8035461>) |
| 8086:9c31 | 19da:b213 | Intel            | 8 Series USB xHCI HC                 | 1     | xhci       | [9BCBD09882](<Mini Pc/ZOTAC/ZBOXNANO-ID67/ZBOXNANO-ID67-ID68-ID69/2A9F2B9082A0/OPNSENSE-21.7.7/12.1-RELEASE-P21-HBSD/AMD64/9BCBD09882>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e6 | 1022:15e4 | AMD              | Raven/Raven2/Renoir Non-Sensor Fu... | 1     |            | [9CF5790022](<Mini Pc/ZOTAC/B/B410/5472E9DDAC21/OPNSENSE-22.1/13.0-STABLE/AMD64/9CF5790022>) |
| 10ec:816e | 10ec:8168 | Realtek Semic... | RealManage BMC                       | 1     |            | [93F9E34D05](<Mini Pc/Lenovo/ThinkCentre/ThinkCentre M75q Gen 2 11JJS00200/7D31210701DF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/93F9E34D05>) |

