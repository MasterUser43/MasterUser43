# MasterUser43 | Electrical Engineering @ ASU

*Firmware, FPGAs & test automation for rockets and solar cells.*

Working on rev3 and the liquids DAQ at [**Sun Devil Rocketry**](https://github.com/SunDevilRocketry) and building measurement tools for perovskite solar cells at the [**Rolston Lab**](https://rolston.lab.asu.edu/), with memristor work next.

[![Sun Devil Rocketry](https://img.shields.io/badge/Sun%20Devil%20Rocketry-8C1D40?style=for-the-badge&logo=rocket&logoColor=white)](https://github.com/SunDevilRocketry)
[![Rolston Lab](https://img.shields.io/badge/Rolston%20Lab-00A3E0?style=for-the-badge&logo=google-scholar&logoColor=white)](https://rolston.lab.asu.edu/)

---

### Projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/SunDevilRocketry/LQD-DAQ"><img src="assets/lqd-daq.jpg" alt="LabJack T7 and wiring on the liquids test stand" width="100%"></a>
<br><b><a href="https://github.com/SunDevilRocketry/LQD-DAQ">LQD-DAQ</a></b> (Sun Devil Rocketry)
<br>Ground DAQ and sequencing service for the liquid engine feed system.
<br><img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54" alt="Python"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/LabJack%20T7-555555?style=flat-square" alt="LabJack T7">
</td>
<td width="50%" valign="top">
<a href="https://github.com/rolston-lab-asu/PixelMux"><img src="assets/pixelmux.gif" alt="Pixel Mux running a voltage sweep on a Keithley SMU" width="100%"></a>
<br><b><a href="https://github.com/rolston-lab-asu/PixelMux">Pixel Mux</a></b> (Rolston Lab)
<br>Automated measurements for perovskite solar cells.
<br><img src="https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54" alt="Python"> <img src="https://img.shields.io/badge/PyVISA-555555?style=flat-square" alt="PyVISA"> <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6">
</td>
</tr>
</table>

<table>
<tr>
<td valign="top">
<a href="https://github.com/SunDevilRocketry/FPGABoard"><img src="assets/fpga-sim.png" alt="GTKWave simulation of the PicoRV32 SoC booting from SPI flash and printing over UART" width="100%"></a>
<br><b><a href="https://github.com/SunDevilRocketry/FPGABoard">FPGABoard</a></b> (Sun Devil Rocketry)
<br>iCE40 softcore-processor for the flight computer.
<br><img src="https://img.shields.io/badge/SystemVerilog-6A1B9A?style=flat-square" alt="SystemVerilog"> <img src="https://img.shields.io/badge/PicoRV32-283272?style=flat-square&logo=riscv&logoColor=F9C33D" alt="PicoRV32 RISC-V"> <img src="https://img.shields.io/badge/iCE40UP5K-555555?style=flat-square" alt="iCE40UP5K">
</td>
</tr>
</table>

---

### Tech stack

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SystemVerilog](https://img.shields.io/badge/systemverilog-6A1B9A?style=for-the-badge)
![STM32](https://img.shields.io/badge/stm32-%2303234b.svg?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![RISC-V](https://img.shields.io/badge/risc--v-283272?style=for-the-badge&logo=riscv&logoColor=F9C33D)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

**Embedded:** `STM32 (H7/F4)` `DMA` `SPI` `I2C` `UART` `USB-CDC` `libusb`\
**FPGA:** `iCE40UP5K` `PicoRV32` `Apio (Yosys, nextpnr)` `Icarus Verilog` `GTKWave`\
**Scientific:** `PyVISA` `NumPy/SciPy` `PySide6` `pyqtgraph`
