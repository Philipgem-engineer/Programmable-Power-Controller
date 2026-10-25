# PROGRAMMABLE DUAL-CHANNEL POWER CONTROLLER
This repository contains the schematic and PCB design of a programmable dual-channel power controller featuring two power outlets, configurable operating modes, and timer-based control.

##  FEATURES
- Dual power outlets
- Programmable timer-based control
- Configurable operating modes
- Relay-based power switching
- Custom-designed PCB
- Embedded control system

## SPONSOR
[<img width="200" height="69" alt="NextPCB" src="https://github.com/user-attachments/assets/f6b9bda9-1b32-4372-8df8-b126741eb5a7">](https://www.nextpcb.com/?code=Philip)

This project is proudly sponsored by [NextPCB](https://www.nextpcb.com/?code=Philip). I'm grateful for the support that helped bring this hardware design from concept to a physical prototype.

If you’re planning to build your own PCB, [NextPCB](https://www.nextpcb.com/?code=Philip) offers reliable PCB fabrication and assembly services with fast turnaround times and competitive pricing, making it easier to bring your electronics projects from idea to reality.

##  TOOLS USED:
- Schematic & PCB Design: KiCad
- PCB Fabrication & Component Library: NextPCB

## SCHEMATIC
<img width="2481" height="1754" alt="Aircon   Fan Smart Controller_page-0001" src="https://github.com/user-attachments/assets/9a898275-fce0-4903-a85c-399965b3b4c1" />
## SCHEMATIC OVERVIEW

The PROGRAMMABLE DUAL-CHANNEL POWER CONTROLLER is built around an ESP32-S2 microcontroller, integrating programmable control, timing functions, and dual-channel AC switching.

* **Microcontroller:** ESP32-S2 for control logic, timing, and user input processing.
* **Power Supply:** 230 VAC to 5 VDC conversion, with a 3.3 V regulator for the digital circuitry.
* **Dual-Channel Switching:** Two independently controlled relays driven by transistor-based switching circuits.
* **User Interface:** Three function keys and an OLED display interface.
* **USB Type-C:** USB connectivity with supporting configuration and protection components.
* **External Flash:** SPI flash memory for non-volatile data storage.
* **Filtering & Decoupling:** Capacitors for power supply stability and noise reduction.


## PCB
<img width="518" height="527" alt="image" src="https://github.com/user-attachments/assets/3582d32e-bd0d-4176-9150-55001388164a" />


##  PCB 3D VIEW
<img width="566" height="571" alt="image" src="https://github.com/user-attachments/assets/cace3693-88ac-4a2c-8e26-39b0444e5d2e" />
<img width="673" height="586" alt="image" src="https://github.com/user-attachments/assets/7a34d6d9-a0d3-40d0-af47-b3f3d8594211" />


## MANUFACTURED PCB
<img width="2396" height="1536" alt="54f83a58-bfc9-46cf-a3cf-78c3728c47b0 (1)" src="https://github.com/user-attachments/assets/ca3caba9-83e0-4e8a-8026-de131a2bb373" />
<img width="561" height="537" alt="image" src="https://github.com/user-attachments/assets/9de49252-5266-43e6-83e1-a3d74fe1a700" />
<img width="522" height="452" alt="image" src="https://github.com/user-attachments/assets/78aee860-7558-4565-b3fd-90f6f44f1d6f" />

## 📁 File Structure

<details>
  <summary>PROGRAMMABLE DUAL-CHANNEL POWER CONTROLLER</summary>
  <ul>
    <li>
      Media/
      <ul>
        <li>(PDF, images, and videos of prototype)</li>
      </ul>
    </li>
    <li>
      Production Files/
      <ul>
        <li>(Gerber, BOM, positions)</li>
      </ul>
    </li>
    <li>
      KiCad Files/
      <ul>
        <li>(Schematic, PCB, library)</li>
      </ul>
    </li>
  </ul>
</details>





