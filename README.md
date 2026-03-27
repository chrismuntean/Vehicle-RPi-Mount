<div align="center">

# Mobile P25 phase 1 & 2 trunked radio decoder

</div>

<br><br>

## Current BOM (for my custom install)

**Note:** Some products may differ slightly from my actual install as I bought some things in stores. The wiring configuration using the switches is not included here since that is highly variable from vehicle to vehicle. Constant cigarrette outlet power is assumed here.

| Hardware | Specs | Notes / Reasoning | Manufacturer / Supplier | Required | MOQ | Single Unit Cost (pre-tax) |
|----------|-------|-------------------|-------------------------|----------|-----|----------------------------|
| Raspberry Pi 3 Model B+ | [Specs](https://pip-assets.raspberrypi.com/categories/532-raspberry-pi-3-model-b/documents/RP-008338-DS-2-raspberry-pi-3-b-plus-product-brief.pdf?disposition=inline) | Maybe slightly overkill to run [op25](https://github.com/boatbod/op25) on | [Amazon](https://a.co/d/01LudnAc) | Yes | 1 | $53.89 |
| 5 Inch RPI MIPI DSI Touchscreen | [Download specs](https://github.com/Hosyond/5-inch-DSI-Display/archive/refs/heads/main.zip) | Just to display talkgroups, touchscreen functionality not enabled | [Amazon](https://a.co/d/0dWo5RfP) | | 1 | $34.99 |
| RTL-SDR v4 | [Datasheet](https://www.rtl-sdr.com/wp-content/uploads/2024/12/RTLSDR_V4_Datasheet_V_1_0.pdf) | Antenna module | [Amazon](https://a.co/d/0eHCQDrK) | Yes | 1 | $39.95 |
| 2.4/ 5/ 5.8 GHz SMA Antenna | | DO NOT USE, not the right antenna for the frequency range | [Amazon](https://a.co/d/04dhBlB6) | Yes | 2 | $4.445 |
| Rolls DU30b Audio Ducker | [Specs](https://www.rolls.com/product/DU30b) | Audio ducking module to play music through traditional aux while listening | [Amazon](https://a.co/d/0cZq54Nk) | | 1 | $109.00 |
| Small Wireless Keyboard with USB-A Male TX | | For bugfixing/ configuring only | [Amazon](https://a.co/d/07ieI7Oj) | | 1 | $35.99 |
| Cigarette Lighter Male to DC **5.5 x 2.1mm** Male | | Cigarette outlet power for the audio ducker | [Amazon](https://a.co/d/06b2rsRH) | | 1 | $9.99 |
| Cigarette Lighter Male to USB-A Female | **3 amp** | Power for the RPI spliced into headliner, REPLACE WITH PROPER POWER MODULE TO AVOID BOOT ISSUES | [Amazon](https://a.co/d/08eeDdht) | Yes | 2 | $4.99 |
| Short USB-A Male to Micro USB Male Cable (angled) | 9" | Power cable for the RPI, angled for smaller profile in housing, short for modularization | [Amazon](https://a.co/d/006erI2H) | Yes | 2 | $4.49 |
| Short USB 3.0 Male to Female Extension (angled) | 8" | USB extender for the RPI to RTL-SDR, angled for smaller profile in housing, short for modularization | [Amazon](https://a.co/d/08npQkfG) | | 2 | $4.00 |
| SMA Female to Female Socket Connector Panel Chassis Mount | | For mounting the antenna internally | [Amazon](https://a.co/d/04dCBRTu) | | 2 | $2.99 |
| Short SMA Male to Male Cable | 6" | SMA extender cable, short for modularization | [Amazon](https://a.co/d/0hwI1OAl) | | 4 | $1.75 |
| Short 3.5mm Male to Male Cable (angled) | 6" | 3.mm extender for the RPI to audio configuration, angled for smaller profile in housing, short for modularization | [Amazon](https://a.co/d/0hwsC2ki) | Yes* (audio output required someway if not using ducker) | 1 | $6.99 |
| 3.5mm Female to RCA Male Cable | 8" | For Raspberry Pi to audio ducker input | [Amazon](https://a.co/d/0hutorhY) | | 2 | $2.995 |
| USB-C Male to RCA Male Cable | 6' | For phone (music) to audio ducker input | [Amazon](https://a.co/d/09z71wBZ) | | 1 | $9.99 |
| RCA Male to 3.5mm Male Cable | 6.6' | For audio ducker output to vehicle aux input | [Amazon](https://a.co/d/0iSsj9Lk) | | 1 | $6.79 |
| **Total (optional)** | | | | | | **$362.40** |
| **Total (required)** | | | | | | **$128.68** |

<br><br>

## Pre-built BOM (in progress)
| Hardware | Specs | Notes / Reasoning | Manufacturer / Supplier | Required | MOQ | Single Unit Cost (pre-tax) |
|----------|-------|-------------------|-------------------------|----------|-----|----------------------------|