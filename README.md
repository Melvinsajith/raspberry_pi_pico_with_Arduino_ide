# raspberry_pi_pico_with_Arduino_ide
How to Program Raspberry Pi Pico using Arduino IDE 

All errors fixed 
Let me show you how to program Raspberry Pi Pico using Arduino IDE. This is a very simple process and we will show you step-by-step instructions to set it up.

How to Program Raspberry Pi Pico using Arduino IDE?

Step 1 – Prepare your PC
In order to Program Raspberry Pi Pico using Arduino IDE, you will need to download and install various tools and software on your PC. To make sure everything goes well, free up at least 400MB of disk space in your PC. Also, make sure no unwanted software is running in the background.

Step 2 – Download and Install the Pico Tools
Next, we need to install a package that will install and setup all the necessary components that you need to have to connect to your computer and communicate with Pico.

![image](https://user-images.githubusercontent.com/75600365/113472429-c95d6d00-9480-11eb-93bd-441dd650e555.png)

Click here to Download Pico-Setup-Windows installer - https://github.com/ndabas/pico-setup-windows/releases

While installing, make sure you include all the components inside the list. Once the installation process has started, it’s gonna take a while to finish.

![image](https://user-images.githubusercontent.com/75600365/113472464-1ccfbb00-9481-11eb-94e7-66afeba2516b.png)

Step 3 – Adding the Board URL

The next two steps are crucial. In order to program Raspberry Pi Pico using Arduino IDE, we need to add the URL to the board details in the Arduino IDE. For that, open up Arduino IDE, go to File >> Preferences
![image](https://user-images.githubusercontent.com/75600365/113472493-3a048980-9481-11eb-8087-5b7dea163db5.png)

There, you will see a text box where you can add Additional Board Manager URL. On that text box, paste the below code

https://github.com/earlephilhower/arduino-pico/releases/download/global/package_rp2040_index.json

Step 4 – Install Raspberry Pi Pico Board from Board Manager
Once you have done that, Go to Tools >> Board >> Boards Manager. There, in the text box, Enter Raspberry Pi Pico or just Pico. If everything you have done till now is correct, you should see the board – Raspberry Pi Pico / RP2040 under the text box.

![image](https://user-images.githubusercontent.com/75600365/113472569-e181bc00-9481-11eb-8a3f-29921e4c2c7c.png)

Once you got that, go ahead and install the board.
This one is also gonna be a huge download.

Its gonna take a lot of time.

Step 5 – Is it really there?
Once the installation is completed, you can close that window. Now, we need to check whether the board is installed correctly. For that, Go to Tools >> Board

There, you should be able to see Raspberry Pi RP2040 Boards and inside that, you should see Raspberry Pi Pico.

![image](https://user-images.githubusercontent.com/75600365/113472650-3d4c4500-9482-11eb-97db-020a8d9232a4.png)



