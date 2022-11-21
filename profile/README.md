# Pocket LoC
<img align = "right" src="https://user-images.githubusercontent.com/42568983/202521498-0bb95a05-1dd4-4db9-ad12-fc51b9aba1ed.jpg" width="40%" /> 
Lab-on-chip (LoC) technology is becoming increasingly relevant, especially in the field of medicine. However, often LoC setups rely on complex lab equipment for operation. The aim of this project is to create an affordable and portable LoC setup as a proof-of-concept for truly pocket-sized LoC - the Pocket LoC.

Pocket LoC can be assembled with standard equipment found in a typcial engineering lab (such as a maker space or FabLab). Once assembled, Pocket LoC is fully portable and only needs a PC to operate.

The various components of Pocket LoC, instructions, assembly guides and usage examples can be found in the different repositories. These are mainly:

### [Housing](https://github.com/Pocket-LoC/Housing)
This should be the starting point for learning about Pocket LoC. The repository contains the assembly instructions and a component overview for Pocket LoC.

### [Pump Controller](https://github.com/Pocket-LoC/Pump-Controller)
The pump controller is used to actuate the Pocket LoC. It is designed to work with commercial micropumps from Bartels and can be programmed easily like an Arduino device. The repository contains all the files needed to make your own controller and some sample code to operate it.

### [Sensor](https://github.com/Pocket-LoC/Sensor)
The optical spectral sensor can detect and analyse coloured droplets in your microfluidic chip. As for the pump controller, the sensor can be used like an Arduino. The repository contains all the files needed to make your own sensor and some sample code to operate it.

### [Chip](https://github.com/Pocket-LoC/Chip)
Depending on your application, you may want to make your own microfluidic chips in a specific way. This repository provides a starting point with instructions and hints for one possible way to make your chip. Generally, any chip that operates with coloured output and transparent channels can be used with Pocket LoC.
