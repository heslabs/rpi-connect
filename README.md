# Raspberry Pi Cloud

Reference: https://www.raspberrypi.com/documentation/services/connect.html

<br/>
<img src="https://github.com/user-attachments/assets/0d6b97b2-66a5-4dba-a273-7d4cf5afd5fa" width=850>

<img src="https://github.com/user-attachments/assets/edaafe6f-e6c0-4abd-8030-0b50799e08c9" width=250>
<img src="https://github.com/user-attachments/assets/4405fabf-e08b-4a2c-89f0-d832f51fe990" width=300>

---
### Target Users
Academic AI SoC developers

---
### Learning Aims:
Knowledge and understanding of:
Embedded Linux OS and AI applications
Software stack for running AI Arm Cortex-A processor
Software stack for running AI PCIe M.2 AI accelerator
AI vision pipeline optimization on edge device
LLM practice and examples on edge device
Develope and deploy of AIoT applications
AI performance and power benchmarks on edge device


---
### Raspberry Pi 5
Tech Spec: https://www.raspberrypi.com/products/raspberry-pi-5/
* Broadcom **BCM2712** 2.4GHz quad-core 64-bit **Arm Cortex-A76** CPU, with cryptography extensions, 512KB per-core L2 caches and a 2MB shared L3 cache
* VideoCore VII **GPU**, supporting OpenGL ES 3.1, Vulkan 1.2
* **Dual 4Kp60 HDMI®** display output with HDR support, 4Kp60 HEVC decoder
* LPDDR4X-4267 SDRAM (2GB, 4GB, and **8GB**)
* Dual-band 802.11ac **Wi-Fi®**, Bluetooth 5.0 / Bluetooth Low Energy (BLE)
* microSD card slot, with support for high-speed SDR104 mode
* 2 × **USB 3.0** ports, 2 × USB 2.0 ports
* Gigabit Ethernet, with PoE+ support (requires separate PoE+ HAT)
* 2 × 4-lane **MIPI camera**/display transceivers
* **PCIe 2.0** x1 interface for fast peripherals (requires separate **M.2 HAT** or other adapter)
* 5V/5A DC power via **USB-C**, with Power Delivery support
* Raspberry Pi OS (previously called Raspbian)
* **Raspberry Pi Connect** provides to access your Raspberry Pi from anywhere


---
## Access your Raspberry Pi device

#### 1. Visit "connect.raspberrypi.com" on any computer

<br/>
<img src="https://github.com/user-attachments/assets/3ea95d2a-e8fe-458c-aa74-0610cd56fade" width=450>

 
---
#### 2. Sign in with your Raspberry Pi ID

<br/>
<img src="https://github.com/user-attachments/assets/e0de9205-6aaa-406e-8099-d3a570473671" width=450>

 
---
#### 3. Select your device and connect it via Screen sharing 

* Click the Connect via button to the right of the device you would like to access
* Select the Screen sharing option from the menu
* This opens a browser window that displays your device’s desktop
  
<br/>
<img src="https://github.com/user-attachments/assets/10ef7f7a-be3a-43d9-baf2-c99157c95dc6" width=550>


---
#### 4. Use your device as you use it locally with GUI interface

<br/>
<img src="https://github.com/user-attachments/assets/2df40ec8-179f-4132-94ba-de29069f94c2" width=850>

---
#### 5. Open the Linux terminal and launch script for running your applications

```
$ make run
```

<img src="https://github.com/user-attachments/assets/d3a4221f-a31d-4a9a-b7da-3b940f885ee6" width=850>
 
---
#### 6. Check the application results on the shared screen session

* The demo will be stopped automatically after few seconds

<br/>
<img src="https://github.com/user-attachments/assets/2ff10d5d-bb2d-4118-a40d-a900fcd44cfd" width=850>


---
### 7. End your remote shell session

* To close a remote shell session, click the **button "Disconect"** in top-left or click "**close the window**" in top right corner
 
 
