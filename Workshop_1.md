**Cura setup Instructions for Printers in the Monash Makerspace: Design and Build Studios**

This Instruction sheet will walk through the steps needed to set up Cura slicer with the correct profiles and settings for CR-10, CR-5 PRO, Ender 7 and Ender 6 3D printers.

All instructions and images are representative of Cura version 4.13.1 and may be slightly different in other versions of the software.

**1. Adding the Printer**

When selecting and adding a new printer into Cura, it is important to use the correct preset, which captures the correct dimensions of the machine and informs Cura of the limits of the sliced file that it can create.

![](media/b7a2924478e529e9144a67192f19c5e4.png)

1a) Select **Add printer** from the top left dropdown bar

![](media/f306a5652f0e9f2479095b736e192df3.png)

1b) Select **Add a Non-networked Printer**

![](media/de94b6b7685b74e475877a20d39972fd.png)

1c)

i. For the CR-10 machine, Cura has a premade machine configuration available.

Just Select **Creality CR-10S5** from the list of printers under the manufacturer **Creality3D.**

You can skip step 1d if a preset is selected.

ii. As of Cura version 4.13.1, there aren’t premade configurations available for the CR-5, Ender 6 and Ender 7 Machines. So a custom configuration will be made. Select **Custom FFF Printer** under the **Custom** dropdown.![](media/9f095233301c4949d0fb35c33546d819.png)

Rename the Printer to reflect the printer being set up.

1d) After a Printer is added it will prompt you to change machine settings. These are values which correspond to the physical dimensions and capabilities of the printer and will control how Cura slices objects. It is important to have the correct settings for each printer as a wrong value here may create files which will damage the printer.

![](media/11acebec63c097ea10c72b211aba256f.png)

For **ENDER 6**:

Printer Settings

X(Width) : 280

Y(Depth) : 280

Z(Height) : 400

Check **Heated Bed**

Printhead settings

X min : -24

Y min : -40

X max : 35

Y max : 18

Gantry Height : 25

For **ENDER 7**:![](media/c4b66f976f51d9214bf6f16fc340f7a4.png)

Printer Settings

X(Width) : 252

Y(Depth) : 252

Z(Height) : 302

Check **Heated Bed**

Printhead settings

X min : -40

Y min : -50

X max : 40

Y max : 35

Gantry Height : 22

![](media/e833506dd0c7fc13e31caf517420b74c.png)

For **CR-5 PRO**:

Printer Settings

X(Width) : 300

Y(Depth) : 225

Z(Height) : 380

Check **Heated Bed**

Printhead Settings

X min : -26

Y min : -32

X max : 32

Y max : 34

Gantry Height : 25

1e) Cura will apply a section of **Start G-code** to the beginning of every Gcode file that is created. This is machine specific and usually controls preheating, bed levelling and nozzle priming. The default start gcode is quite basic, so we will be applying a custom gcode to increase the performance of the printers.

Simply copy and paste the machine specific text files from below into the **Start G-code** field.

**Ensure that all the default code is deleted first.**

End G-code does not need to be changed.

[Replace Start G-code with replacement code here!](https://drive.google.com/drive/folders/1Crsnob01E0vaBf2aZJ7CydhCzflpdmhN?usp=sharingviL_xwdAGePcmdVv/view?usp=sharing)

1f) The **Extruder** tab of the settings page holds settings that are specific to extruders, such as nozzle size, filament diameter, and any extruder specific Gcode.![](media/aff11b08750b9283dc0eb15b4e476559.png)

Each Printer is set up with a different nozzle size. Input the correct nozzle size for the printer being configured. Take note of any labels or notices on the printer or nozzle which may indicate that a specific printer has had its nozzle size changed.

Ender 7 (Stock) : 0.4mm

Ender 7 (Mosquito) : 0.8mm

Ender 6 : 0.6mm

CR-5 PRO : 0.4mm

CR-10S5 : 1.0mm

Material Diameter : 1.75mm (on all Printers)

Once the Machine Settings have been changed , you can close the settings window by clicking **Next** or **Close.**

**2. Download and Import custom CURA profiles**

Custom Profiles have been created for each specific printer in the Makerspace. These profiles have been tested and should provide a successful print in most cases. If changes do need to be made to these profiles, refer to the [Print Settings Matrix](https://docs.google.com/spreadsheets/d/1NvhUbym7CkRxWnFIceyPgOaa5SF-kolUbchRHCo7O_k/edit?usp=sharing) to check the allowable changes for each printer.

![](media/935bd5c84b330d0d1172dbd96cb83009.png)

2a) Download the specific profile for the printer from the [**Profiles folder**](https://drive.google.com/drive/folders/1B2cRtHTtfF2BTpv8xk8EjrmIXciB4UUY?usp=sharing)

2b) Navigate to the **Profile manager** in Cura and **import** the downloaded profile. Make sure the correct printer is active in Cura with the correct nozzle size. In the Profile Manager, import the downloaded profile into Cura.

![](media/974d40dd666a539a8e1a636bfcc1eeb5.png)

**3. Verify settings**

The custom profiles provided are a good base and should work for most geometries. But some settings may need to be changed depending on the specific model being printed.

**Supports** - add supports if there are any overhangs or unsupported model features

**Infill density / pattern** - infill density and patterns affect the rigidity and isotropy of printed parts

**Wall thickness / Top and bottom layers** - affect rigidity of the outer shell

**Bed adhesion** - useful for parts with a small bed surface area

Other settings can be changed to customise the profile for specific geometries.

Refer to the [**Print Settings Matrix**](https://docs.google.com/spreadsheets/d/1NvhUbym7CkRxWnFIceyPgOaa5SF-kolUbchRHCo7O_k/edit?usp=sharing) for allowable changes to print settings.
