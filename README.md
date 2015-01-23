Using an Arduino, a Smartphone, a Bluetooth module and a Bike with Shimanos Di2 to create an automatic gear shifting bike.

What does it do? With the right wiring of the above mentioned components, the code of this project, enables one to build a bike that will always shift into the fitting gear in respective to the chosen target crank frequency and your current speed.

The code is well commented. This code is more aimed at inspiring others to build an own automatic gear shifting bike, rather than being an step by step instruction how to do that. If someone actually wants do that and needs more help, you can still ask me. E-mail is in the header of the code files.

The behaviour of the shifing system also was simulated with MATLAB/SIMULINK, so that it is not necessary to test small logic changes at the bike directly. The arduino code "shiftingTestWithBluetoothComunication.ino" as also the Matlab code "steuerung.c" uses the header file "usedMethods.h". In MATLAB the logical part is implemented as an s-Function block, which uses "steuerung.c" and exactly reacts like the original Arduino code.

The code for the mentioned app, which is necessary for changing settings without having to compile a new scetch might be uploaded soon.