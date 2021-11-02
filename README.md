# dining-philosophers
Arduino implementation of Dining Philosophers problems using State Machines described in this 
[Application Note](https://www.state-machine.com/doc/AN_DPP.pdf) from Miro Samek of Quantum Leaps, the original author of the software.

I'm republishing the code here as part of an tutorial exercise to understand the various architectures offered by Quantum Leaps and
to develop techniques for using GitHUB together with scripted builds (including the code generation step). 

The target hardware for this project is the [Arduino Mega 1280](https://docs.platformio.org/en/latest/boards/atmelavr/megaatmega1280.html)

All code based on exampes code written by [Quantum Leaps](https://www.state-machine.com/)

## Build

* This project uses the [Quantum Leaps Real Time Embedded Framework (RTEF)](https://www.state-machine.com/products/qp)
* All code for the project is store in the [model file](./dpp.qm)
* This project utilises the [QEP Nano Framework](https://www.state-machine.com/qpn/index.html) and all code is written to
*  the [QEP Nano API](https://www.state-machine.com/qpn/index.html)
* C application code (the ``dpp.ino`` file) is generated using the [qm modelling tool](https://www.state-machine.com/products/qm/)
* Generated code is compiled and uploaded using the [Arduino IDE](https://www.arduino.cc/en/software)
