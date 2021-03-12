# OpenCore-ASRock-Z490M-ITX-ac

## Working:

- Sleep/awake
- Bluetooth
- Wifi with BCM9460CS2
- HDMI PORT
- DP PORT
- On-Board Rear Audio

## NOT working

- HDMI - DP Audio

## Not Tested

- dGPU as I dont use any.
- USB Type-C port speed, works fine with an Type-A to Type-C adapter though.
- Front panel audio

## Software

- OpenCore 0.6.7
- MacOS Big Sur
- SMBios: IMac20,1 (opencore recomendation for comet lake)

## Kexts

- Beaware the USBMap.kext that I mapped using the USBMapTool disables all from usb headers. If you need them. Replace this with InjectUSBAll and do the proper mapping using the USBMapTool. I will probably change this as soon as I get a new case.

## Hardware List

- [ASRock Z490M ITX ac](https://www.asrock.com/mb/Intel/Z490M-ITXac/index.asp)
- CPU 10600 (non k) stock cooler
- Kingston HyperX 2x8GB 2400Mhz (could be better )
- [Sabrent Rocket NVME 4.0 512GB](https://www.sabrent.com/product/SB-ROCKET-NVMe4-500/500gb-rocket-nvme-pcie-4-0-m-2-2280-internal-ssd-maximum-performance-solid-state-drive/)
- Wifi /BT Card [BCM9460CS2 on Ebay](https://www.ebay.co.uk/sch/i.html?_from=R40&_trksid=p2047675.m570.l1313&_nkw=+Z653-0023&_sacat=0)
- Wifi Adapter [M.2 key E adapter](https://www.amazon.co.uk/gp/product/B07G2Z2SZ6/ref=ppx_yo_dt_b_asin_title_o07_s00?ie=UTF8&psc=1)

- GPU: iGPU Intel 630
