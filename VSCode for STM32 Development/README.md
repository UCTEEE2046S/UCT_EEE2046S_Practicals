# VSCode for STM32 Development
Prerequisite: 
- VSCode installation
- STM32CubeProgrammer downloaded onto the PC that will be used to program

First attempt Method 1 below, and if, at any point, you experience issues, move to Method 2. Method 1 is easier to install, but can present more issues during installation.

# Method 1
Video guide availible at: [Installing stm-32-for-vscode on VSCode](https://youtu.be/_jt3rf3F7mg?si=u_sil4GarOMNESst)

**Note:** this method does not work on Mac OS devices and you will need to use Method 2
        
## Get stm32-for-vscode extension
Navigate to the Extensions tab in VScode and install the stm32-for-vscode extension
<img width="552" alt="stm32Extension" src="https://user-images.githubusercontent.com/15980541/231163351-1b747808-ca5e-4e39-8222-affb2877c4e8.PNG">

**Note:** throughout this process, if you get a pop-up window in the bottom right corner asking you to install reccomended build tools - install them

## Download the template provided in this repository 
1. To download the template, you will need to either download the entire repo or clone the entire repo
2. This template contains all the required files needed to start programming your STM32. 
3. In Core > Src there is a file called main.c - this is where you will be coding.
4. The code in the main.c file displays a "Hello World! :)" onto your LCD screen.

## Building and flashing your demo program
1. Once you have made changes to your code you will need to save everything and navigate to the STM32 tab in VSCode
<img width="227" alt="stm32Env" src="https://user-images.githubusercontent.com/15980541/231162914-8e7c5383-5801-4b5a-a456-ce18ea40541d.PNG">
2. Select "Build" to compile your code
3. After building, you can flash this code to your board by selecting "Flash STM32"
4. You should see "Hello World! :)" onto your LCD screen.

# Method 2 (not as lightweight, but more reliable)
Video guide availible at: [Installing PlatformIO on VSCode](https://youtu.be/n-_z2OFj0LA?si=837ICKfUeuPFD827)


You are now ready to start programming your board with your own code :) 
