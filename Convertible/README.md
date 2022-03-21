Most popular PCI devices in Convertibles
========================================

See more info in the [README](https://github.com/bsdhw/LsPCI).

Contents
--------

1. [ PCI Devices in Convertibles ](#pci-devices)
   * [ Bridge ](#bridge-pci)
   * [ Card reader ](#card-reader-pci)
   * [ Communication controller ](#communication-controller-pci)
   * [ Encryption controller ](#encryption-controller-pci)
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
   * [ Storage/nvme ](#storagenvme-pci)
   * [ Storage/raid ](#storageraid-pci)
   * [ System peripheral ](#system-peripheral-pci)
   * [ Usb controller ](#usb-controller-pci)
   * [ Wireless controller ](#wireless-controller-pci)
   * [ Others ](#others-pci)

PCI Devices
-----------

Count  - number of computers with this device installed,
Driver - driver in use for this device,
Probe  - latest probe ID of this device.

### Bridge (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5914 | 17aa:2259 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 3     | hostb      | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:5914 | 17aa:506d | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 3     | hostb      | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d10 | 17aa:2259 | Intel            | Sunrise Point-LP PCI Express Root... | 3     | pcib       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d10 | 17aa:506d | Intel            | Sunrise Point-LP PCI Express Root... | 3     | pcib       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d12 | 17aa:506d | Intel            | Sunrise Point-LP PCI Express Root... | 3     | pcib       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d14 | 17aa:2259 | Intel            | Sunrise Point-LP PCI Express Root... | 3     | pcib       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d14 | 17aa:506d | Intel            | Sunrise Point-LP PCI Express Root... | 3     | pcib       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d18 | 17aa:2259 | Intel            | Sunrise Point-LP PCI Express Root... | 3     | pcib       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d18 | 17aa:506d | Intel            | Sunrise Point-LP PCI Express Root... | 3     | pcib       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d4e | 17aa:2259 | Intel            | Sunrise Point LPC Controller/eSPI... | 3     | isab       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d4e | 17aa:506d | Intel            | Sunrise Point LPC Controller/eSPI... | 3     | isab       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:15d3 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 Bridge (C s... | 2     | pcib       | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:1904 | 17aa:2238 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 2     | hostb      | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:5914 | 103c:83c8 | Intel            | Xeon E3-1200 v6/7th Gen Core Proc... | 2     | hostb      | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d10 | 17aa:2238 | Intel            | Sunrise Point-LP PCI Express Root... | 2     | pcib       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:9d12 | 17aa:2238 | Intel            | Sunrise Point-LP PCI Express Root... | 2     | pcib       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:9d12 | 17aa:2259 | Intel            | Sunrise Point-LP PCI Express Root... | 2     | pcib       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d18 | 103c:83c8 | Intel            | Sunrise Point-LP PCI Express Root... | 2     | pcib       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d19 | 103c:83c8 | Intel            | Sunrise Point-LP PCI Express Root... | 2     | pcib       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d48 | 17aa:2238 | Intel            | Sunrise Point-LP LPC Controller      | 2     | isab       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:9d4e | 103c:83c8 | Intel            | Sunrise Point LPC Controller/eSPI... | 2     | isab       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 1022:1448 |           | AMD              | Renoir Device 24: Function 0         | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:1449 |           | AMD              | Renoir Device 24: Function 1         | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:144a |           | AMD              | Renoir Device 24: Function 2         | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:144b |           | AMD              | Renoir Device 24: Function 3         | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:144c |           | AMD              | Renoir Device 24: Function 4         | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:144d |           | AMD              | Renoir Device 24: Function 5         | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:144e |           | AMD              | Renoir Device 24: Function 6         | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:144f |           | AMD              | Renoir Device 24: Function 7         | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:1576 | 1028:0944 | AMD              | Family 15h (Models 60h-6fh) Proce... | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:157b |           | AMD              | Family 15h (Models 60h-6fh) Host ... | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:157c | 1028:0944 | AMD              | Family 15h (Models 60h-6fh) Proce... | 1     | pcib       | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:157d |           | AMD              | Carrizo Audio Dummy Host Bridge      | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:15b0 |           | AMD              | Stoney HT Configuration              | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:15b1 |           | AMD              | Stoney Address Maps                  | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:15b2 |           | AMD              | Stoney DRAM Configuration            | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:15b3 |           | AMD              | Stoney Miscellaneous Configuration   | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:15b4 |           | AMD              | Stoney PM Configuration              | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:15b5 |           | AMD              | Stoney NB Performance Monitor        | 1     | hostb      | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:1630 | 103c:888a | AMD              | Renoir/Cezanne Root Complex          | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:1632 |           | AMD              | Renoir PCIe Dummy Host Bridge        | 1     | hostb      | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:1634 | 1022:1453 | AMD              | Renoir/Cezanne PCIe GPP Bridge       | 1     | pcib       | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:1635 | 1022:1635 | AMD              | Renoir Internal PCIe GPP Bridge t... | 1     | pcib       | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:790e | 1028:0944 | AMD              | FCH LPC Bridge                       | 1     | isab       | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:790e | 103c:888a | AMD              | FCH LPC Bridge                       | 1     | isab       | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:0284 | 10f7:8338 | Intel            | Comet Lake PCH-LP LPC Premium Con... | 1     | isab       | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:0284 | 17aa:22ad | Intel            | Comet Lake PCH-LP LPC Premium Con... | 1     | isab       | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:02b0 | 17aa:22ad | Intel            | Comet Lake PCI Express Root Port #9  | 1     | pcib       | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:02b2 | 10f7:8338 | Intel            | Comet Lake PCH-LP PCIe Port #11      | 1     | pcib       | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02b4 | 10f7:8338 | Intel            | Comet Lake PCI Express Root Port #13 | 1     | pcib       | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |

### Card reader (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 10ec:522a | 17aa:506d | Realtek Semic... | RTS522A PCI Express Card Reader      | 3     | rtsx       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 10ec:522a | 103c:83c8 | Realtek Semic... | RTS522A PCI Express Card Reader      | 2     | rtsx       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 10ec:5229 | 103c:8074 | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     |            | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 10ec:5229 | 17aa:381b | Realtek Semic... | RTS5229 PCI Express Card Reader      | 1     |            | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 10ec:522a | 103c:81a9 | Realtek Semic... | RTS522A PCI Express Card Reader      | 1     |            | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 10ec:525a | 1028:08b0 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx       | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 10ec:525a | 103c:8514 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     |            | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 10ec:525a | 103c:86fa | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx       | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 10ec:525a | 17aa:2238 | Realtek Semic... | RTS525A PCI Express Card Reader      | 1     | rtsx       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |

### Communication controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d3a | 17aa:2259 | Intel            | Sunrise Point-LP CSME HECI #1        | 3     |            | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d3a | 17aa:506d | Intel            | Sunrise Point-LP CSME HECI #1        | 3     |            | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d3a | 103c:83c8 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     |            | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d3a | 17aa:2238 | Intel            | Sunrise Point-LP CSME HECI #1        | 2     |            | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:02e0 | 10f7:8338 | Intel            | Comet Lake Management Engine Inte... | 1     |            | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02e0 | 17aa:22ad | Intel            | Comet Lake Management Engine Inte... | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:02e3 | 10f7:8338 | Intel            | Comet Lake PCH-LP Keyboard and Te... | 1     |            | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02e3 | 17aa:22ad | Intel            | Comet Lake PCH-LP Keyboard and Te... | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:02fc | 10f7:8338 | Intel            | Comet Lake Integrated Sensor Solu... | 1     |            | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02fc | 17aa:22ad | Intel            | Comet Lake Integrated Sensor Solu... | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:34e0 | 1028:08b0 | Intel            | Ice Lake-LP Management Engine        | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34e0 | 103c:86fa | Intel            | Ice Lake-LP Management Engine        | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:34fc | 1028:08b0 | Intel            | Ice Lake-LP Integrated Sensor Sol... | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34fc | 103c:86fa | Intel            | Ice Lake-LP Integrated Sensor Sol... | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:5a9a | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5a9a | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:9c3a | 17aa:3978 | Intel            | 8 Series HECI #0                     | 1     |            | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:9d3a | 1028:07eb | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:9d3a | 103c:81a9 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:9d3a | 103c:827e | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:9d3a | 103c:8438 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:9d3a | 103c:86d0 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:9d3a | 1043:1b00 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:9d3a | 1179:0001 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:9d3a | 152d:1147 | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:9d3a | 17aa:380d | Intel            | Sunrise Point-LP CSME HECI #1        | 1     |            | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 8086:9d3d | 17aa:2259 | Intel            | Sunrise Point-LP Active Managemen... | 1     |            | [6C55FC2866](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LDS1CG00/3C69EF28289E/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/6C55FC2866>) |
| 8086:9d3d | 17aa:506d | Intel            | Sunrise Point-LP Active Managemen... | 1     |            | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9de0 | 103c:8514 | Intel            | Cannon Point-LP MEI Controller #1    | 1     |            | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:9dfc | 103c:8514 | Intel            | Cannon Point-LP Integrated Sensor... | 1     |            | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:a13a | 17aa:3809 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |

### Encryption controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:1578 | 1028:0944 | AMD              | Carrizo Platform Security Processor  | 1     |            | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:15df | 103c:888a | AMD              | Family 17h (Models 10h-1fh) Platf... | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:2298 | 103c:8074 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |

### Graphics card (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:5917 | 17aa:2259 | Intel            | UHD Graphics 620                     | 3     | i915       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:5917 | 17aa:506d | Intel            | UHD Graphics 620                     | 3     | i915       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:1916 | 17aa:2238 | Intel            | Skylake GT2 [HD Graphics 520]        | 2     | i915       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:5917 | 103c:83c8 | Intel            | UHD Graphics 620                     | 2     | i915       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 1002:164c | 103c:888a | AMD              | Lucienne                             | 1     | vgapci     | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1002:98e4 | 1028:0944 | AMD              | Stoney [Radeon R2/R3/R4/R5 Graphics] | 1     | amdgpu     | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 10de:1c8d | 17aa:39cb | Nvidia           | GP107M [GeForce GTX 1050 Mobile]     | 1     | vgapci     | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |
| 8086:0a1e | 17aa:3978 | Intel            | Haswell-ULT High Definition Audio... | 1     | i915       | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:22b1 | 103c:8074 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | i915       | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 8086:3ea0 | 103c:8514 | Intel            | WhiskeyLake-U GT2 [UHD Graphics 620] | 1     | i915       | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:5916 | 103c:81a9 | Intel            | HD Graphics 620                      | 1     | i915       | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:5916 | 103c:827e | Intel            | HD Graphics 620                      | 1     | i915       | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:5916 | 1179:0001 | Intel            | HD Graphics 620                      | 1     | i915       | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:5916 | 152d:1147 | Intel            | HD Graphics 620                      | 1     | i915       | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:5916 | 17aa:39fd | Intel            | HD Graphics 620                      | 1     | vgapci     | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 8086:5917 | 1028:07eb | Intel            | UHD Graphics 620                     | 1     | i915       | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:5917 | 103c:8438 | Intel            | UHD Graphics 620                     | 1     | vgapci     | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:5917 | 1043:1b00 | Intel            | UHD Graphics 620                     | 1     | i915       | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:591b | 17aa:39cb | Intel            | HD Graphics 630                      | 1     | i915       | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |
| 8086:5a84 | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | i915       | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5a84 | 1025:1222 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | i915       | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:87ca | 103c:86d0 | Intel            | UHD Graphics 615                     | 1     | i915       | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:8a52 | 1028:08b0 | Intel            | Iris Plus Graphics G7                | 1     | vgapci     | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:8a52 | 103c:86fa | Intel            | Iris Plus Graphics G7                | 1     | i915       | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:9b41 | 17aa:22ad | Intel            | CometLake-U GT2 [UHD Graphics]       | 1     | acpi_vi... | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:9bca | 10f7:8354 | Intel            | Comet Lake UHD Graphics              | 1     | i915       | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |

### Memory controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d21 | 17aa:2259 | Intel            | Sunrise Point-LP PMC                 | 3     |            | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d21 | 17aa:506d | Intel            | Sunrise Point-LP PMC                 | 3     |            | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d21 | 103c:83c8 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d21 | 17aa:2238 | Intel            | Sunrise Point-LP PMC                 | 2     |            | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:02ef | 10f7:8338 | Intel            | Comet Lake PCH-LP Shared SRAM        | 1     |            | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02ef | 17aa:22ad | Intel            | Comet Lake PCH-LP Shared SRAM        | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:34ef |           | Intel            | Ice Lake-LP DRAM Controller          | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34ef | 103c:86fa | Intel            | Ice Lake-LP DRAM Controller          | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:9d21 | 1028:07eb | Intel            | Sunrise Point-LP PMC                 | 1     |            | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:9d21 | 103c:81a9 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:9d21 | 103c:827e | Intel            | Sunrise Point-LP PMC                 | 1     |            | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:9d21 | 103c:8438 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:9d21 | 103c:86d0 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:9d21 | 1043:1b00 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:9d21 | 1179:0001 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:9d21 | 152d:1147 | Intel            | Sunrise Point-LP PMC                 | 1     |            | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:9d21 | 17aa:380b | Intel            | Sunrise Point-LP PMC                 | 1     |            | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 8086:9def | 103c:8514 | Intel            | Cannon Point-LP Shared SRAM          | 1     |            | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:a121 | 17aa:380f | Intel            | 100 Series/C230 Series Chipset Fa... | 1     |            | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |

### Multimedia (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1022:15e2 | 103c:888a | AMD              | ACP/ACP3X/ACP6x Audio Coprocessor    | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:8a19 | 1028:08b0 | Intel            | Image Signal Processor               | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |

### Net/ethernet (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:15d7 | 17aa:2259 | Intel            | Ethernet Connection (4) I219-LM      | 2     | em         | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:15d7 | 17aa:506d | Intel            | Ethernet Connection (4) I219-LM      | 2     | em         | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 10ec:8136 | 103c:8074 | Realtek Semic... | RTL810xE PCI Express Fast Etherne... | 1     | re         | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 10ec:8168 | 1025:1198 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 10ec:8168 | 103c:86d0 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 10ec:8168 | 17aa:3848 | Realtek Semic... | RTL8111/8168/8411 PCI Express Gig... | 1     | re         | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 8086:0d4e | 10f7:8338 | Intel            | Ethernet Connection (10) I219-LM     | 1     | em         | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:0d4e | 17aa:22ad | Intel            | Ethernet Connection (10) I219-LM     | 1     | em         | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:15d8 | 17aa:2259 | Intel            | Ethernet Connection (4) I219-V       | 1     | em         | [9773669778](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LD003JGE/F342FD7F8B52/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/9773669778>) |
| 8086:15d8 | 17aa:506d | Intel            | Ethernet Connection (4) I219-V       | 1     | em         | [6EC28A973A](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga 20LH000NPG/BAC09486393D/FREEBSD-13.0/13.0-RELEASE/AMD64/6EC28A973A>) |

### Net/wireless (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:24fd | 8086:0010 | Intel            | Wireless 8265 / 8275                 | 7     | iwm        | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:095a | 8086:5010 | Intel            | Wireless 7265                        | 4     | iwm        | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:02f0 | 8086:0070 | Intel            | Comet Lake PCH-LP CNVi WiFi          | 2     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:24fd | 8086:1010 | Intel            | Wireless 8265 / 8275                 | 2     | iwm        | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |
| 168c:0036 | 1028:020e | Qualcomm Atheros | QCA9565 / AR9565 Wireless Network... | 1     | ath        | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 168c:0042 | 17aa:0901 | Qualcomm Atheros | QCA9377 802.11ac Wireless Network... | 1     |            | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 8086:095a | 8086:5410 | Intel            | Wireless 7265                        | 1     | iwm        | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:095a | 8086:9010 | Intel            | Wireless 7265                        | 1     | iwm        | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:24f3 | 8086:0130 | Intel            | Wireless 8260                        | 1     | iwm        | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:24f3 | 8086:1130 | Intel            | Wireless 8260                        | 1     | iwm        | [B6CB68C67D](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FQ000RUS/3759C2190863/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/B6CB68C67D>) |
| 8086:24f3 | 8086:9010 | Intel            | Wireless 8260                        | 1     | iwm        | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:24fb | 8086:2110 | Intel            | Dual Band Wireless-AC 3168NGW [St... | 1     | iwm        | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 8086:24fd | 8086:0110 | Intel            | Wireless 8265 / 8275                 | 1     | iwm        | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:2526 | 8086:0014 | Intel            | Wireless-AC 9260                     | 1     | iwm        | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:2723 | 8086:0084 | Intel            | Wi-Fi 6 AX200                        | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:34f0 | 1a56:1651 | Intel            | Ice Lake-LP PCH CNVi WiFi            | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34f0 | 8086:0074 | Intel            | Ice Lake-LP PCH CNVi WiFi            | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:9df0 | 8086:0034 | Intel            | Cannon Point-LP CNVi [Wireless-AC]   | 1     | iwm        | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |

### Network (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:156f | 17aa:2233 | Intel            | Ethernet Connection I219-LM          | 1     | em         | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |

### Sd host controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 1217:8520 | 1217:0002 | O2 Micro         | SD/MMC Card Reader Controller        | 1     | sdhci_pci  | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 1217:8620 | 1028:0944 | O2 Micro         | BayHubTech/O2Micro Integrated MMC... | 1     | sdhci_pci  | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 17a0:9750 | 17a0:9750 | Genesys Logic    | GL9750 SD Host Controller            | 1     | sdhci_pci  | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:5aca | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:5acc | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | sdhci_pci  | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |

### Serial bus controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:02a4 | 10f7:8338 | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02a4 | 17aa:22ad | Intel            | Comet Lake SPI (flash) Controller    | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:02e8 | 10f7:8338 | Intel            | Serial IO I2C Host Controller        | 1     | ig4iic     | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02ea | 10f7:8338 | Intel            | Comet Lake PCH-LP LPSS: I2C Contr... | 1     | ig4iic     | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:34a4 | 1028:08b0 | Intel            | Ice Lake-LP SPI Controller           | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34a4 | 103c:86fa | Intel            | Ice Lake-LP SPI Controller           | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:34e8 | 1028:08b0 | Intel            | Ice Lake-LP Serial IO I2C Control... | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34e8 | 103c:86fa | Intel            | Ice Lake-LP Serial IO I2C Control... | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:34e9 | 1028:08b0 | Intel            | Ice Lake-LP Serial IO I2C Control... | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34e9 | 103c:86fa | Intel            | Ice Lake-LP Serial IO I2C Control... | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:34eb | 1028:08b0 | Intel            | Ice Lake-LP Serial IO I2C Control... | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:9da4 | 103c:8514 | Intel            | Cannon Point-LP SPI Controller       | 1     |            | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:9de8 | 103c:8514 | Intel            | Cannon Point-LP Serial IO I2C Con... | 1     | ig4iic     | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:9de9 | 103c:8514 | Intel            | Cannon Point-LP Serial IO I2C Con... | 1     | ig4iic     | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |

### Signal processing (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1903 | 17aa:2259 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 3     |            | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:1903 | 17aa:506d | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 3     |            | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d31 | 17aa:2259 | Intel            | Sunrise Point-LP Thermal subsystem   | 3     | pchtherm   | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d31 | 17aa:506d | Intel            | Sunrise Point-LP Thermal subsystem   | 3     | pchtherm   | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d60 | 17aa:2259 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 3     | ig4iic     | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:1903 | 103c:83c8 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 2     |            | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d31 | 103c:83c8 | Intel            | Sunrise Point-LP Thermal subsystem   | 2     | pchtherm   | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d31 | 17aa:2238 | Intel            | Sunrise Point-LP Thermal subsystem   | 2     | pchtherm   | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:9d60 | 103c:83c8 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 2     | ig4iic     | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d61 | 103c:83c8 | Intel            | Sunrise Point-LP Serial IO I2C Co... | 2     | ig4iic     | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 1022:15e4 | 103c:888a | AMD              | Sensor Fusion Hub                    | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:02f9 | 10f7:8338 | Intel            | Comet Lake Thermal Subsytem          | 1     | pchtherm   | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02f9 | 17aa:22ad | Intel            | Comet Lake Thermal Subsytem          | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:0a03 | 17aa:3978 | Intel            | Haswell-ULT Thermal Subsystem        | 1     |            | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:1903 | 1028:07eb | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:1903 | 103c:81a9 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:1903 | 103c:827e | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:1903 | 103c:8438 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:1903 | 103c:8514 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:1903 | 103c:86d0 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:1903 | 1043:1b00 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:1903 | 10f7:8338 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:1903 | 152d:1147 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:1903 | 17aa:22ad | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:1903 | 17aa:3809 | Intel            | Xeon E3-1200 v5/E3-1500 v5/6th Ge... | 1     |            | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |
| 8086:22dc | 103c:8074 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 8086:5a8c | 1025:1198 | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 1     |            | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5a8c | 8086:7270 | Intel            | Atom/Celeron/Pentium Dynamic Plat... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:5aac | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ig4iic     | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5aac | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:5aae | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ig4iic     | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5ab2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:5ab4 | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ig4iic     | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5ab4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:5ab6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:5ac2 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:5ac4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:5ac6 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:8a03 | 1028:08b0 | Intel            | Ice Lake Dynamic Platform and The... | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:8a03 | 103c:86fa | Intel            | Ice Lake Dynamic Platform and The... | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:9c24 | 17aa:3978 | Intel            | 8 Series Thermal                     | 1     | pchtherm   | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:9d31 | 1028:07eb | Intel            | Sunrise Point-LP Thermal subsystem   | 1     |            | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:9d31 | 103c:81a9 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     |            | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:9d31 | 103c:827e | Intel            | Sunrise Point-LP Thermal subsystem   | 1     |            | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:9d31 | 103c:8438 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     | pchtherm   | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:9d31 | 103c:86d0 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     | pchtherm   | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:9d31 | 1043:1b00 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     | pchtherm   | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:9d31 | 1179:0001 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     | pchtherm   | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:9d31 | 152d:1147 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     |            | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:9d31 | 17aa:3808 | Intel            | Sunrise Point-LP Thermal subsystem   | 1     |            | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |

### Smbus (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d23 | 17aa:2259 | Intel            | Sunrise Point-LP SMBus               | 3     | ichsmb     | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d23 | 17aa:506d | Intel            | Sunrise Point-LP SMBus               | 3     | ichsmb     | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d23 | 103c:83c8 | Intel            | Sunrise Point-LP SMBus               | 2     | ichsmb     | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d23 | 17aa:2238 | Intel            | Sunrise Point-LP SMBus               | 2     | ichsmb     | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 1022:790b | 1028:0944 | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:790b | 103c:888a | AMD              | FCH SMBus Controller                 | 1     | intsmb     | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:02a3 | 10f7:8338 | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 1     | ichsmb     | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02a3 | 17aa:22ad | Intel            | Comet Lake PCH-LP SMBus Host Cont... | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:2292 | 103c:8074 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     |            | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 8086:34a3 | 1028:08b0 | Intel            | Ice Lake-LP SMBus Controller         | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34a3 | 103c:86fa | Intel            | Ice Lake-LP SMBus Controller         | 1     |            | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:5ad4 | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5ad4 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     |            | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:9c22 | 17aa:3978 | Intel            | 8 Series SMBus Controller            | 1     | ichsmb     | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:9d23 | 1028:07eb | Intel            | Sunrise Point-LP SMBus               | 1     |            | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:9d23 | 103c:81a9 | Intel            | Sunrise Point-LP SMBus               | 1     |            | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:9d23 | 103c:827e | Intel            | Sunrise Point-LP SMBus               | 1     |            | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:9d23 | 103c:8438 | Intel            | Sunrise Point-LP SMBus               | 1     | ichsmb     | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:9d23 | 103c:86d0 | Intel            | Sunrise Point-LP SMBus               | 1     | ichsmb     | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:9d23 | 1043:1b00 | Intel            | Sunrise Point-LP SMBus               | 1     | ichsmb     | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:9d23 | 1179:0001 | Intel            | Sunrise Point-LP SMBus               | 1     | ichsmb     | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:9d23 | 152d:1147 | Intel            | Sunrise Point-LP SMBus               | 1     |            | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:9d23 | 17aa:380b | Intel            | Sunrise Point-LP SMBus               | 1     |            | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 8086:9da3 | 103c:8514 | Intel            | Cannon Point-LP SMBus Controller     | 1     |            | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:a123 | 17aa:3810 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | ichsmb     | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |

### Sound (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d71 | 17aa:2259 | Intel            | Sunrise Point-LP HD Audio            | 3     | hdac       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d71 | 17aa:506d | Intel            | Sunrise Point-LP HD Audio            | 3     | hdac       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d70 | 17aa:2238 | Intel            | Sunrise Point-LP HD Audio            | 2     | hdac       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:9d71 | 103c:83c8 | Intel            | Sunrise Point-LP HD Audio            | 2     | hdac       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 1002:15b3 | 1028:0944 | AMD              | High Definition Audio Controller     | 1     | hdac       | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1002:1637 | 103c:888a | AMD              | Renoir Radeon High Definition Aud... | 1     | hdac       | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:157a | 1028:0944 | AMD              | Family 15h (Models 60h-6fh) Audio... | 1     | hdac       | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:15e3 | 103c:888a | AMD              | Family 17h/19h HD Audio Controller   | 1     | hdac       | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:02c8 | 10f7:836d | Intel            | Comet Lake PCH-LP cAVS               | 1     | hdac       | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02c8 | 17aa:22ad | Intel            | Comet Lake PCH-LP cAVS               | 1     | hdac       | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:0a0c | 17aa:3978 | Intel            | Haswell-ULT HD Audio Controller      | 1     | hdac       | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:2284 | 103c:8074 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | hdac       | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 8086:34c8 | 1028:08b0 | Intel            | Ice Lake-LP Smart Sound Technolog... | 1     | hdac       | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34c8 | 103c:86fa | Intel            | Ice Lake-LP Smart Sound Technolog... | 1     | hdac       | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:5a98 | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | hdac       | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5a98 | 1025:1222 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | hdac       | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:9c20 | 17aa:3978 | Intel            | 8 Series HD Audio Controller         | 1     | hdac       | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:9d71 | 1028:07eb | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:9d71 | 103c:81a9 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:9d71 | 103c:827e | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:9d71 | 103c:86d0 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:9d71 | 1043:1b00 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:9d71 | 1179:0001 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:9d71 | 152d:1147 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:9d71 | 17aa:3804 | Intel            | Sunrise Point-LP HD Audio            | 1     | hdac       | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 8086:9dc8 | 103c:8514 | Intel            | Cannon Point-LP High Definition A... | 1     | hdac       | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:a171 | 17aa:380e | Intel            | CM238 HD Audio Controller            | 1     | hdac       | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |

### Storage/ata (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d03 | 103c:83c8 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d03 | 17aa:2238 | Intel            | Sunrise Point-LP SATA Controller ... | 2     | ahci       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 1022:7901 | 1028:0944 | AMD              | FCH SATA Controller [AHCI mode]      | 1     | ahci       | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 8086:02d3 | 10f7:8338 | Intel            | Comet Lake SATA AHCI Controller      | 1     | ahci       | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:22a3 | 103c:8074 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | ahci       | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 8086:5ae3 | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ahci       | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5ae3 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | ahci       | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:9c03 | 17aa:3978 | Intel            | 8 Series SATA Controller 1 [AHCI ... | 1     | ahci       | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:9d03 | 1028:07eb | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:9d03 | 103c:81a9 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:9d03 | 1043:1b00 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:9d03 | 1179:0001 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:9d03 | 17aa:3810 | Intel            | Sunrise Point-LP SATA Controller ... | 1     | ahci       | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |

### Storage/nvme (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 144d:a808 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM981/PM981/P... | 6     | nvme       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 1c5c:1327 |           | SK Hynix         | BC501 NVMe Solid State Drive         | 2     | nvme       | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 1e0f:0001 | 1e0f:0001 | KIOXIA           | unknown                              | 2     | nvme       | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:0975 | 8086:8410 | Intel            |                                      | 2     | nvme       | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:0975 | 8086:8510 | Intel            |                                      | 2     | nvme       | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 1179:0116 | 1179:0001 | Toshiba          | unknown                              | 1     | nvme       | [DAB0CA2417](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga 20LJ000WUK/15E84FE4987E/NOMADBSD-5806F915/13.0-RELEASE/AMD64/DAB0CA2417>) |
| 144d:a804 | 144d:a801 | Samsung Elect... | NVMe SSD Controller SM961/PM961/S... | 1     | nvme       | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 144d:a809 | 144d:a801 | Samsung Elect... | NVMe SSD Controller 980              | 1     | nvme       | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 17aa:0003 | 17aa:1003 | Lenovo           | unknown                              | 1     | nvme       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 1c5c:1339 |           | SK Hynix         | BC511                                | 1     | nvme       | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:f1a5 | 8086:390a | Intel            | SSD 600P Series                      | 1     | nvme       | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |

### Storage/raid (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:282a | 103c:8514 | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:282a | 103c:86fa | Intel            | 82801 Mobile SATA Controller [RAI... | 1     | ahci       | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |

### System peripheral (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:1911 | 17aa:2259 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:1911 | 17aa:506d | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 3     |            | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:1911 | 17aa:2238 | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 2     |            | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 8086:8a17 |           | Intel            | Ice Lake Thunderbolt 3 NHI #0        | 2     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 1022:1577 | 1028:0944 | AMD              | Family 15h (Models 60h-6fh) I/O M... | 1     |            | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:1631 | 103c:888a | AMD              | Renoir/Cezanne IOMMU                 | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:15bf | 17aa:22ad | Intel            | JHL6240 Thunderbolt 3 NHI (Low Po... | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:15d2 | 103c:8438 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 1     |            | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:15d2 | 103c:8514 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 1     |            | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:15d2 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 NHI (C step... | 1     |            | [6C55FC2866](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LDS1CG00/3C69EF28289E/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/6C55FC2866>) |
| 8086:15e8 | 1189:0009 | Intel            | JHL7540 Thunderbolt 3 NHI [Titan ... | 1     |            | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:1911 | 17aa:22ad | Intel            | Xeon E3-1200 v5/v6 / E3-1500 v5 /... | 1     |            | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:8a0d |           | Intel            | Ice Lake Thunderbolt 3 NHI #1        | 1     |            | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |

### Usb controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d2f | 17aa:2259 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 3     | xhci       | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d2f | 17aa:506d | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 3     | xhci       | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:15d4 | 2222:1111 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 2     | xhci       | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:9d2f | 103c:83c8 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 2     | xhci       | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d2f | 17aa:2238 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 2     | xhci       | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 1022:1639 | 103c:888a | AMD              | Renoir/Cezanne USB 3.1               | 1     | xhci       | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 1022:7908 | 1028:0944 | AMD              | FCH USB EHCI Controller              | 1     | ehci       | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 1022:7914 | 1028:0944 | AMD              | FCH USB XHCI Controller              | 1     | xhci       | [8BBD2C16F7](<Convertible/Dell/Inspiron/Inspiron 3195/1FD15A29A7BA/HELLOSYSTEM-0.6.0/12.2-RELEASE/AMD64/8BBD2C16F7>) |
| 8086:02ed | 10f7:8338 | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 1     | xhci       | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:02ed | 17aa:22ad | Intel            | Comet Lake PCH-LP USB 3.1 xHCI Ho... | 1     | xhci       | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:15c1 |           | Intel            | JHL6240 Thunderbolt 3 USB 3.1 Con... | 1     | xhci       | [DAB0CA2417](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga 20LJ000WUK/15E84FE4987E/NOMADBSD-5806F915/13.0-RELEASE/AMD64/DAB0CA2417>) |
| 8086:15c1 | 17aa:22ad | Intel            | JHL6240 Thunderbolt 3 USB 3.1 Con... | 1     | xhci       | [8818F01FF2](<Convertible/Lenovo/ThinkPad/ThinkPad X13 Yoga Gen 1 20SYS22H00/627303CC1970/NOMADBSD-1.4/12.2-RELEASE-P4/AMD64/8818F01FF2>) |
| 8086:15c1 | 2222:1111 | Intel            | JHL6240 Thunderbolt 3 USB 3.1 Con... | 1     | xhci       | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |
| 8086:15d4 | 103c:8438 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 1     | xhci       | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:15d4 | 103c:8514 | Intel            | JHL6540 Thunderbolt 3 USB Control... | 1     | xhci       | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:15e9 | 1189:0009 | Intel            | JHL7540 Thunderbolt 3 USB Control... | 1     | xhci       | [BB08E98562](<Convertible/Panasonic/CFQV9/CFQV9-1/DC9CF1A795CF/FREEBSD-13.0-STABLE/13.0-STABLE/AMD64/BB08E98562>) |
| 8086:22b5 | 103c:8074 | Intel            | Atom/Celeron/Pentium Processor x5... | 1     | xhci       | [40624B04C0](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/B0C33DEC21E3/HELLOSYSTEM-0.5.0/12.2-RELEASE/AMD64/40624B04C0>) |
| 8086:34ed | 1028:08b0 | Intel            | Ice Lake-LP USB 3.1 xHCI Host Con... | 1     | xhci       | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:34ed | 103c:86fa | Intel            | Ice Lake-LP USB 3.1 xHCI Host Con... | 1     | xhci       | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:5aa8 | 1025:1198 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | xhci       | [C3ACC4D372](<Convertible/Acer/TravelMate/TravelMate Spin B118-RN/0E35B0D93894/FREEBSD-12.2/12.2-RELEASE/AMD64/C3ACC4D372>) |
| 8086:5aa8 | 8086:7270 | Intel            | Celeron N3350/Pentium N4200/Atom ... | 1     | xhci       | [B8FDB26064](<Convertible/Acer/Spin/Spin SP111-32N/B81A60A9C555/FREEBSD-12.1/12.1-RELEASE/AMD64/B8FDB26064>) |
| 8086:8a13 |           | Intel            | Ice Lake Thunderbolt 3 USB Contro... | 1     | xhci       | [CC8C604FA6](<Convertible/Dell/XPS/XPS 13 7390 2-in-1/84AAC084FB8A/FREEBSD-13.0/13.0-RELEASE/AMD64/CC8C604FA6>) |
| 8086:8a13 | 103c:86fa | Intel            | Ice Lake Thunderbolt 3 USB Contro... | 1     | xhci       | [1B230DBC6A](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/1B230DBC6A>) |
| 8086:9c26 | 17aa:3978 | Intel            | 8 Series USB EHCI #1                 | 1     | ehci       | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:9c31 | 17aa:3978 | Intel            | 8 Series USB xHCI HC                 | 1     | xhci       | [547171EF28](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-aw0xxx/D2292E0C5E07/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/547171EF28>) |
| 8086:9d2f | 1028:07eb | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:9d2f | 103c:81a9 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:9d2f | 103c:827e | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:9d2f | 103c:8438 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:9d2f | 103c:86d0 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:9d2f | 1043:201f | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |
| 8086:9d2f | 1179:0001 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:9d2f | 152d:1147 | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:9d2f | 17aa:380b | Intel            | Sunrise Point-LP USB 3.0 xHCI Con... | 1     | xhci       | [E4C678AFD8](<Convertible/Lenovo/Yoga/Yoga 510-14IKB 80VB/388990F14895/OPNSENSE-21.1.1/12.1-RELEASE-P13-HBSD/AMD64/E4C678AFD8>) |
| 8086:9ded | 103c:8514 | Intel            | Cannon Point-LP USB 3.1 xHCI Cont... | 1     | xhci       | [3AE7EEBB87](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-ap0xxx/B8A790D1EBD9/FREEBSD-13.0-CURRENT/13.0-CURRENT/AMD64/3AE7EEBB87>) |
| 8086:a12f | 17aa:3807 | Intel            | 100 Series/C230 Series Chipset Fa... | 1     | xhci       | [7782674614](<Convertible/Lenovo/Yoga/Yoga 720-15IKB 80X7/3A2DC6377655/FREEBSD-13.0/13.0-RELEASE/AMD64/7782674614>) |

### Wireless controller (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:7360 | 8086:0020 | Intel            | XMM7360 LTE Advanced Modem           | 2     |            | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |

### Others (PCI)

| ID        | Subsystem | MFG              | Name                                 | Count | Driver     | Probe |
|-----------|-----------|------------------|--------------------------------------|-------|------------|-------|
| 8086:9d35 | 17aa:2259 | Intel            | Sunrise Point-LP Integrated Senso... | 3     |            | [F8801C62BC](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 3rd 20LES2RG1A/4CA8BC93BA74/FREEBSD-13.0/13.0-RELEASE/AMD64/F8801C62BC>) |
| 8086:9d35 | 17aa:506d | Intel            | Sunrise Point-LP Integrated Senso... | 3     |            | [C27BA488AA](<Convertible/Lenovo/ThinkPad/ThinkPad X380 Yoga S1 20LJS1FD01/D81D33E2E1D9/FREEBSD-13.0/13.0-RELEASE/AMD64/C27BA488AA>) |
| 8086:9d35 | 103c:83c8 | Intel            | Sunrise Point-LP Integrated Senso... | 2     |            | [F45A4133BC](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-bp1xx/ED10BE22E759/FREEBSD-13.0-P4/13.0-RELEASE-P4/AMD64/F45A4133BC>) |
| 8086:9d35 | 17aa:2238 | Intel            | Sunrise Point-LP Integrated Senso... | 2     |            | [9C85F07244](<Convertible/Lenovo/ThinkPad/ThinkPad X1 Yoga 1st 20FRS11T00/E9F382722DB5/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/9C85F07244>) |
| 10ec:5228 | 103c:888a | Realtek Semic... |                                      | 1     |            | [40A0D1E964](<Convertible/Hewlett-Packard/ENVY/ENVY x360 Convertible 15m-eu0xxx/10767F7842A6/FREEBSD-13.0-P5/13.0-RELEASE-P4/AMD64/40A0D1E964>) |
| 8086:9d35 | 1028:07eb | Intel            | Sunrise Point-LP Integrated Senso... | 1     |            | [DC37C53E48](<Convertible/Dell/Inspiron/Inspiron 7373/57D978268D1A/HELLOSYSTEM-0.4.0/12.1-RELEASE/AMD64/DC37C53E48>) |
| 8086:9d35 | 103c:81a9 | Intel            | Sunrise Point-LP Integrated Senso... | 1     |            | [F27578615F](<Convertible/Hewlett-Packard/Pavilion/Pavilion x360 Convertible/4D2AD3FEA517/GHOSTBSD-20.04.02/12.2-STABLE/AMD64/F27578615F>) |
| 8086:9d35 | 103c:827e | Intel            | Sunrise Point-LP Integrated Senso... | 1     |            | [C8C11A071D](<Convertible/Hewlett-Packard/Spectre/Spectre x360 Convertible 13-w0XX/B2A7EF892BF2/NOMADBSD-1.3.2/12.1-RELEASE-P6/AMD64/C8C11A071D>) |
| 8086:9d35 | 103c:8438 | Intel            | Sunrise Point-LP Integrated Senso... | 1     |            | [130803FAD8](<Convertible/Hewlett-Packard/EliteBook/EliteBook x360 1030 G3/525A7550FBBE/OPNSENSE-22.1.2/13.0-STABLE/AMD64/130803FAD8>) |
| 8086:9d35 | 103c:86d0 | Intel            | Sunrise Point-LP Integrated Senso... | 1     |            | [7EAFF44A64](<Convertible/Hewlett-Packard/ProBook/ProBook x360 11 G6 EE/260F7492B758/NOMADBSD-5806F915/13.0-RELEASE-P4/AMD64/7EAFF44A64>) |
| 8086:9d35 | 1179:0001 | Intel            | Sunrise Point-LP Integrated Senso... | 1     |            | [1E5DC453F6](<Convertible/Toshiba/PORTEGE/PORTEGE X20W-D/AC89E117C881/FREEBSD-13.0/13.0-RELEASE/AMD64/1E5DC453F6>) |
| 8086:9d35 | 152d:1147 | Intel            | Sunrise Point-LP Integrated Senso... | 1     |            | [E550E3BA04](<Convertible/PORSCHE DESIGN/BOOK/BOOK ONE/12662DEA3048/FREEBSD-12.2-P3/12.2-RELEASE-P3/AMD64/E550E3BA04>) |
| 8086:9d35 | 8086:9d35 | Intel            | Sunrise Point-LP Integrated Senso... | 1     |            | [B745DEE7D6](<Convertible/ASUSTek Computer/Q505/Q505UAR/CE9AA325EF53/HELLOSYSTEM-0.6.0/13.0-RELEASE/AMD64/B745DEE7D6>) |

