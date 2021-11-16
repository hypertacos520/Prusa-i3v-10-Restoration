# Prusa-i3v-Restoration

This repo is a compilation of all the info I gathered on the Prusa i3v 3D printer. I was using these files to restore the printer to working order. The project is still not completely finished, but I've documented as far as I was able to get here.

# Hardware Details

Arduino Mega 2560
RAMPS 1.4 Controller
Direct Drive Filament Feed
Heated Print Bed

Filament Diameter: 1.75mm (Speculated)

# Restoration Process

The 3D printer didn't come with a proper power suply but did come with a regular PC power supply. I was able to set up this power supply for the 3D printer by attaching it to one of the molex connections. I then designed a housing for the power supply so it wasn't just hanging off the back of the machine. The design I settled on looks like this: 

![Power Supply](https://github.com/hypertacos520/Prusa-i3v-Restoration/blob/main/Assets/PowerSupply.png?raw=true)

This design works and the PC power supply is neatly hidden behind the existing frame of the machine.

Once the machine was powered on, I quickly discovered not all its axis were functional. This is because half of the stepper motor drivers on the RAMPS board were fried. After replacing them, each axis functioned as expected. I went ahead and tightened each belt individually and recalibrated the steps per mm accordingly. After all this I wrapped all the cables and designed a housing for the main control board so it wasn't just and exposed mess of wires. The casing looked like this:

![Mainboard Casing](https://github.com/hypertacos520/Prusa-i3v-Restoration/blob/main/Assets/Mainboard.png?raw=true)

After all this the printer is looking significantly better than it did when I started. 