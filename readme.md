# OpenCore-ASRock-Z490M-ITX-ac
### 2+ Month review
 - working everyday without any problems.
 - Put it to sleep eveyday it wakes up next morning.
 - Never crashed (yet :)
 - It works just fine

 Was it worth it compared to buying a normal Apple device?
This table can give you an idea, but for me it was. At least for the time being
|   Device   |        Specs        | Geekbench  MultiCore |  Price  |
|:----------:|:-------------------:|:--------------------:|:-------:|
|  I5 10600  | 500GB NVME 16GB RAM |         6269         |  600GBP |
| M1 MacMini | 512GB NVME 16GB RAM |         7385         | 1099GBP |

## Working:
- Sleep/awake
- Bluetooth
- Wifi with BCM9460CS2
- HDMI PORT 
-HDMI - DP Audio
- DP PORT
- On-Board Rear Audio
 
## Not Tested

- Well I have no ideia if iMessage and those sort of things are working because I dont use them.
- dGPU as I dont use any.
- USB Type-C port speed, works fine with an Type-A to Type-C adapter though.
- Front panel audio

## Software

- OpenCore 0.6.3
- MacOS Big Sur 11.0.1 (20B29)
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
 

