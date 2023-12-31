## 1. Payload Development Kit Main PCB
The main PCB provides the connectivity between the payload under development and the microcontroller development board (dev board) running the Binar Spacecraft Emulator Software. It also provides connections for power from either a benchtop or 2.1 mm centre positive barrel jack power supply and a STLINK debugger for programming the payload.

If you have been provided with a Binar Payload Development Kit by the Binar Space Program, you already have this component.

If you haven't been provided with a kit, you can find instructions for ordering and assembling the main PCB here: [Fabrication and Assembly.md](Fabrication and Assembly.md).

## 2. STMicroelectronics NUCLEO-H743ZI2 Microcontroller Development Board
The [STMicroelectronics NUCLEO-H743ZI2 Development Board](https://www.st.com/en/evaluation-tools/nucleo-h743zi.html) is a microcontroller development board for the [STM32H743ZIT6](https://www.st.com/en/microcontrollers-microprocessors/stm32h743zi.html) STM32 family microcontroller. It plugs into the four 0.1" header receptacles at the top of the Payload Development Kit Main PCB and runs the Binar Spacecraft Emulator Software which simulates the operation of the Binar spacecraft during the development of your payload.

If you have been provided with a Binar Payload Development Kit by the Binar Space Program, you already have this component and it is already plugged into your Payload Development Kit Main PCB. It will also already have been flashed with the Binar Spacecraft Emulator Software.

If you haven't been provided with a kit, you will need to source the STMicroelectronics NUCLEO-H743ZI2 Microcontroller Development Board and flash it with the Binar Spacecraft Emulator Software yourself.

| Manufacturer | Mfr Part Number | Qty | Supplier 1 | Supplier 1 PN | Supplier 2 | Supplier 2 PN |
|--------------|-----------------|-----|------------|---------------|------------|---------------|
| STMicroelectronics | [NUCLEO-H743ZI2](https://www.st.com/en/evaluation-tools/nucleo-h743zi.html) | 1 | Mouser | [511-NUCLEO-H743ZI2](https://www.mouser.com/ProductDetail/STMicroelectronics/NUCLEO-H743ZI2) | Digikey | [497-19452-ND](https://www.digikey.com/en/products/detail/stmicroelectronics/NUCLEO-H743ZI2/10130892)|

## 3. Power Supply
You can power the board with either a benchtop power supply or a 2.1 mm centre positive barrel jack power supply.

If you have been provided with a Binar Payload Development Kit by the Binar Space Program you may have been provided with a 9V 2A DC Power Supply with a 2.1 mm centre positive barrel jack. You can use this to start your payload development, but in order to replicate operation accross a more realistic range of voltages you may want to procure a benchtop power supply in the future.

If you haven't been provided with a kit, you will need to source one of either type of power supply yourself.

### Barrel Jack Power Supply (or similar alternative)
| Manufacturer | Mfr Part Number | Qty | Supplier 1 | Supplier 1 PN | Supplier 2 | Supplier 2 PN |
|--------------|-----------------|-----|------------|---------------|------------|---------------|
| Powertran | [M8925D](https://www.altronics.com.au/p/m8925d-powertran-9v-dc-2a-fixed-2.1mm-tip-appliance-plugpack/) | 1 | Altronics | [M8925D](https://www.altronics.com.au/p/m8925d-powertran-9v-dc-2a-fixed-2.1mm-tip-appliance-plugpack/) | | |

### 30V 3A Benchtop Power Supply (or similar alternative)
| Manufacturer | Mfr Part Number | Qty | Supplier 1 | Supplier 1 PN | Supplier 2 | Supplier 2 PN |
|--------------|-----------------|-----|------------|---------------|------------|---------------|
| TENMA | [	72-2685](https://au.element14.com/tenma/72-2685/bench-power-supply-1-ch-30v-3a/dp/256398101) | 1 | element14 | [256398101](https://au.element14.com/tenma/72-2685/bench-power-supply-1-ch-30v-3a/dp/256398101) | | |

### 4mm Banana Plug Test Lead, 1m, Black (or similar alternative)
| Manufacturer | Mfr Part Number | Qty | Supplier 1 | Supplier 1 PN | Supplier 2 | Supplier 2 PN |
|--------------|-----------------|-----|------------|---------------|------------|---------------|
| Hirschmann Test and Measurement | [934063100](https://www.sks-kontakt.de/en/test-measurement/products/product?nr=9340631) | 1 | element 14 | [4017882](https://au.element14.com/hirschmann-testmeasurement/934063100/test-lead-blk-1m-60v-32a/dp/4017882) | | |

### 4mm Banana Plug Test Lead, 1m, Red (or similar alternative)
| Manufacturer | Mfr Part Number | Qty | Supplier 1 | Supplier 1 PN | Supplier 2 | Supplier 2 PN |
|--------------|-----------------|-----|------------|---------------|------------|---------------|
| Hirschmann Test and Measurement | [934063101](https://www.sks-kontakt.de/en/test-measurement/products/product?nr=9340631) | 1 | element 14 | [4017870](https://au.element14.com/hirschmann-testmeasurement/934063101/test-lead-red-1m-60v-32a/dp/4017870) | | |

## 4. STMicroelectronics In-Circuit Debugger and Programmer for STM32 Microcontrollers
In order to program the microcontroller controlling your payload with software, and debug the software during development a debugger is required.

A STDC14 connector is provided on the left hand side of the Payload Development Kit Main PCB for connection of an STLINK debugger (if using an STM32 microcontroller on your payload). This is routed to a on piece connecter beneath the payload board for conveinient programming without the need to add a connector to your payload. Please see the PCB design files the pinout of this connector if you wish to use it.

If you have been provided with a Binar Payload Development Kit by the Binar Space Program, you may have been provided with a [STLINK-V3MINIE](https://www.st.com/en/development-tools/stlink-v3minie.html).

If you haven't been provided with a kit, you will need to source one yourself (if developing your payload with an STM32 microcontroller).

| Manufacturer | Mfr Part Number | Qty | Supplier 1 | Supplier 1 PN | Supplier 2 | Supplier 2 PN |
|--------------|-----------------|-----|------------|---------------|------------|---------------|
| STMicroelectronics | [STLINK-V3MINIE](https://www.st.com/en/development-tools/stlink-v3minie.html) | 1 | Mouser | [511-STLINK-V3MINIE](https://au.mouser.com/ProductDetail/511-STLINK-V3MINIE) | Digikey | [497-STLINK-V3MINIE-ND](https://www.digikey.com.au/en/products/detail/stmicroelectronics/STLINK-V3MINIE/16284301)|
