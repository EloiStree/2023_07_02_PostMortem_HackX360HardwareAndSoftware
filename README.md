# 2023_07_02_PostMortem_HackX360HardwareAndSoftware

Let's do a postmortem write up of the last two weeks before my brain forget what I have learn.

End of June I was preparing OMI for Diablo 4.
When the game was out, I realized that most of the action that I want to automate are more easy to do with Xbox360 that with mouse and keyboard due to the simplicity of a Xbox360 menu.

So I rework a code of mine that can create simulation of a controller.
After realizing that is work well. I tried on several computer and realized that I don't have enough computer but my Xbox S <200€.

So I started to user a old computer with Xbox compagnon to control it. But it means that I will use lot's of electricity for one account.

The idea came to me to use fake usb key that send input to the Xbox with Zen or Brook. 
I bought a Brook to make test. It works. 

But cheapter that Brook adapter  and more official are the Window Adaptive controller and the hack of a real controller bought on Ebay at the right timing.
So I bought one and start to understand how it work.

I learn to hack an real Xbox controller and to understand the Adaptive Controller.

Hacking the Xbox was a lot's of learning that diserve a workshop.

Hacking the Adpative Controller was too.
You have two ways of doing it:
- By doing hardware connection in audio jack at disposal.
- By Simulated two HID gamepad that you put in the left and right usb port of the adaptive... That stupid, welcome in the microsoft team.


All that to say.
The good idea to work on the Xbox part of the toolbox is that it is one that won't change in a decat or two.
So I decided to works on it hard.

It also allows me to work a bit on the serial port connection that I stopped to work on since I learn MIDI.


## Related Git

When I started to work on the topic I was writing down what I learn to prepare a future workshop:
- https://github.com/EloiStree/2023_06_23_ArduinoToDroneAndXboxHardware
- Find some of my road note here:
  - https://github.com/EloiStree/2023_06_23_ArduinoToDroneAndXboxHardware/blob/main/FullNote.md

- 2023_06_21_ArduinoToX360 
  - This code allows to simulate wiht UART connection an X360 controller.
  - https://github.com/EloiStree/2023_06_21_ArduinoToX360
- 2023_06_29_MicroPythonUART2PinOnOff
  - While hacking Around I realize that it is easier to have a pin on off from serial that having to change the code all the tim on the Arduino or Micro Python so I started to do a lib to use from OMI
  - https://github.com/EloiStree/2023_06_29_MicroPythonUART2PinOnOff

- 2023_10_20_CircuitPythonToX360
  - The idea here was to simulate X360 for Brook. But i realized that it is not so easy. In the same time I realized that you can simulate HID joystick, keyboard and mouse. And that a good news.
  - https://github.com/EloiStree/2023_10_20_CircuitPythonToX360
  - Note: I did not succed to simuate the the trigger of the joystick HID.

If you want to simulate an X360 from Adaptive controller or real on, you will need to learn to hack buttons and digital potentiometer.
- 2023_06_28_RasperryPiPicoToRemoteControlRCExostCar
  - Learn to hack with Raspberry Pi Pico a RC car made of 5 buttons 
  - https://github.com/EloiStree/2023_06_28_RasperryPiPicoToRemoteControlRCExostCar
- https://github.com/EloiStree/2023_06_26_MegaToJoystickAndTrigger
  - X360 has to many button and joystick so I with to Mega Arduino and learn the X3C that you must learn to use
  - X3C are digital potentiometer that allows to simulate the trigger and joystick
  - https://github.com/EloiStree/2023_06_26_MegaToJoystickAndTrigger


I created this git to put a workshop about how to use the adaptive controller.
But I still need some hardware to fully hack it and also without good luck on Ebay it is too expensive.
 - https://github.com/EloiStree/2023_06_22_XboxAdaptiveToX360
 - Note: Adafruit did a wonderful tutorial on the subject any way. I put a backup pdf in case the website remove it.


Unity package: https://github.com/EloiStree/2023_07_01_SerialPortGateUnityWindow
