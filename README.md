# GH-drum-kit-to-PC
Hi, in this project we will be turning our playstation ( or Xbox ) Guitar Hero Drum Kit to an electronic drum kit which we can control and play it with our PC.
I have tried quite few methods over time and some are work for my PC's and some are didn't. So I'll show you the latests version that worked for me.

**Requirements**:
- MIDI to USB connector [something like this](https://www.amazon.com/Interface-Converter-Adapter-Indicator-Keyboard/dp/B087G7L7J2/ref=sr_1_1_sspa?dchild=1&keywords=usb+midi+cable&qid=1628748250&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUE0OVFMSTk5MThSQk4mZW5jcnlwdGVkSWQ9QTAxMDczNzVDRVFEV1hJTENFWFcmZW5jcnlwdGVkQWRJZD1BMDAyODI4ODFUSVFKVzhOTjdZQlMmd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)
- Guitar Hero Drum Kit and its connecto. [This part](https://i.ebayimg.com/images/g/eZsAAOSwU9xUPSLg/s-l400.jpg)

**Step 1** Downloading FL Studio;

This is the DAW ( Digital Audio Workstation) we are goin to use. Download the program from this [*LINK*](https://www.image-line.com/fl-studio-download/) and set up to your PC.

![Image of Yaktocat](https://www.seekpng.com/png/small/177-1777099_skills-fl-studio-logo-transparent.png)

**Step 2** Downloading Addictive Drums 2;

This is the main program we are going to use. It is the interface between our GH-Drums and PC. 
[*Addictive Drums*](https://www.youtube.com/watch?v=52-ESQODJJw)

![Image of Yaktocat](https://assets.xlnaudio.com/products/icons/303/BUADTOTA.jpg)

**Step 3** Combining programs;

**Setting the kit:** Open FL studio, *Options > MIDI settings > Under the 'Input' sellect the kit*

**Setting addictive drums:** Open FL studio,  *Add > Refresh plugin list*

You shoul see the plugin under *Plugin Database > Installed > Generators > VST > Addictive Drums 2 x64*

**Step 4** Connecting kit to PC;

Connect the '*MIDI out*' of the drum to '*MIDI in*' of the connector and '*MIDI in*' of the drum to '*MIDI out*' of the MIDI to USB connector and than plug the connector to the Guitar Hero Drum Kit connector and than plug that connector to the USB port of the PC. Here is a visual diagrame of it.

![GH-diagram](https://user-images.githubusercontent.com/88151522/129150944-2050a51c-4b73-41ae-81aa-848228ee0fb5.png)

**NOTE!** If this doesn't work try pluging in the connectors to the seperate USB ports of the PC.

**Step 5** 

In FL Studio open channel rack![image](https://user-images.githubusercontent.com/88151522/129152471-330fa9db-55a4-4b6c-bf61-2671f5c0002d.png)

On the bottom-left side of the picture you see the Addictive drums, drag it and drop it to the rack.
Once it is opened you can close the channel rack, and click the question mark on the top-right corner
![image](https://user-images.githubusercontent.com/88151522/129153302-cfc9cf15-fe2a-4b4f-b4d4-9c99d330a5b2.png)

