# High-Density VEP Set-Up Checklist

## AMPLIFIER

- In 120G Chandlee remove cables from amplifier and connect them to pegs on wall.
 
![Rear of NetAmps 200](imgs/rear-of-amplifier.pictClipping.jpg)

- Wheel amp between the monitor and the subject chair so that it is to the right of the subject chair. 

- Plug the 4 cords from the wall ports connecting rooms G and H into respective ports (Digital input, USB, and TTL input external timebase) of the amplifier. Turn power on 
(I = on).

![Rear of NetAmps 200 Data Cables](imgs/rear-of-amplifier-data-cables.pictClipping.jpg)

 
## COMPUTERS
- Turn on CRT Monitor in room 120G.

- In 120H Switch on power of large surge protector on bottom left shelf.

- Switch on power of smaller, thin surge protector on second shelf (ignore lights; always on).

- Turn on PD Video and NetStation computers, and both monitors.

- If either monitor screen is unresponsive, you may need to toggle to the correct computer via the gray KVM switches on the top left (PD Video / Link 15) and right (NetStation  / PD Host) shelf.

- Turn on external timebase, behind the monitors (switch is back, right side).

- Remove the plug from the external timebase outlet labeled OUT. (Clock Out stays in).
 
![Rear of External Timebase](imgs/rear-of-ext-timebase.pictClipping.jpg)

- Make sure that white round switch on top of the left KVM switch is set to B.

- On PD Video computer, open Power Diva Video 3.4 software. (icon label says alias)

![Power Diva Video icon](imgs/power-diva-video-icon.pictClipping.jpg)
 
- In Power Diva Video, go to Configuration --> Video Manager. In "Mode" window, make sure the calibrated video setting is selected: 

	- "800 x 600, 72 Hz, 8 bit" is a common mode. 
 
 ![Power Diva Video Manager](imgs/power-diva-video-manager.pictClipping.jpg)

- In Run mode (pull-down tab), choose Auto Sequence. In Msg mode (pull-down tab), choose Net Station.
 
- Go to Open, and choose the appropriate stimulus set.

![Open Stimulus Set](imgs/power-diva-video-stim-set.pictClipping.jpg)

- Press the Run button. In the DAQ Rate Settings window, there is a binary code to confirm. On the side of the external time box facing you, there are silver switches (up = 1, down = 0). Read the binary code in the PD Video window from right to left, and check to make sure that the switches on the timing box correspond to this code. If they don't match, notify the PI. If they do, press Cancel.

![Determine Time Base Code](imgs/power-diva-autorun.pictClipping.jpg)

- Go to the Net Station computer and log in with the gilmorelab account (w/ lab password - 0baby- ).
	
- In the dock at the bottom of the screen, click on the icon for Net Station (purple icon) to open the program.
 
![NetStation icon](imgs/start-netstation.pictClipping.jpg)

- When the window pops up, there should be a key symbol with the words “Wenger 5” on the bottom left-hand side. If it is not there, this means that the NS HASP key is not plugged in.

- In the Net Station window, click New Session, and select the session template labeled Power Diva Adult Set Up.
	 

## AFTER PARTICIPANT ARRIVES

- Enter participant ID, date of birth, experiment name, and net serial number. Lab uses the following standard ID number for each session: YYMMDD_HHMM.

![Enter participant session info](imgs/ns-enter-session-info.pictClipping.jpg)

- Begin Session.

- Run Zeros and Gains (should run automatically).

![Gains and Zeros](imgs/gains-zeros-window.pictClipping.jpg)
  
- After netting, plug the articulating arm into the amp, and the net into the articulating arm.

![Connect arm to amp](imgs/connect-net-to-arm.pictClipping.jpg)

- Measure Impedance. Adjust channels as necessary. Save and close when satisfactory.

![Measure Impedance](imgs/measure-impedance-window.pictClipping.jpg)

- Choose Dense Waveform Display in the Panels window of Net Station.

![Dense waveform](imgs/dense-waveform-display.pictClipping.jpg)

- Turn small switch on amplifier to “External Time Base.”

![External Time Base](imgs/external-timebase-switch-on-amp.pictClipping.jpg)

- In Power Diva Video, press the Run button. Check off the box in the Net Station Recording control window labeled “Start/Continue Net Station Recording,” and press Run.

![Run Session](imgs/power-diva-autorun.pictClipping.jpg)

- On the Net Station computer, make sure the “Recording” symbol is displayed on the upper left-hand side of the screen. Also, make sure the event flag labeled “DIN4” is present, as well as a flag below this with the condition number (e.g., “c004”).

## AFTER SESSION

- Once recording is complete, select the close session button on the Net Station computer (this saves the session).

- Return computers and other devices to their default settings.

- Return and replug amplifier to its default setup.

- Clean net and begin [data export](ssvep-data-export.md) (separate protocols).
