# Arctic Fox Tutorials

<p align="center">
    <img src="https://icii.io/wp-content/uploads/2022/09/New-Arctic-Fox-Logo.Blue_.For-Animation.WithBehindForGaps-1.svg" alt="Arctic Fox Logo" style="width:300px;"/>
</p>

Welcome to Arctic Fox! This GitHub repo serves as a landing page for the Arctic Fox tutorials. Folow these tutorials to learn about Arctic Fox and how to automate Hardware Description Language (HDL) development and verification. 

<br>
<br>
<br>

### Table of Contents
1. [Tutorials List](#tutorials-list)
2. [How To Use Tutorials](#how-to-use-tutorials)
<br>
<br>
<br>

# Tutorials List
## [1) Getting Started](https://github.com/icii-arcticfox/GettingStartedTutorial1)
An introduction to Arctic Fox. We take you through the basics of adding automations to your code and running Arctic Fox. 

## [2) Debounce Circuit](https://github.com/icii-arcticfox/ArcticFox_Debounce_Tutorial)
Physical signals often contain noise and need pre-processing. Debouncing is one such example. This tutorial shows you thehow to use Arctic Fox to debounce a button press using a counter. 
- Automation Focus: Rising Edge, Counter, TestModule

## [3) Temperature Anomaly](https://github.com/icii-arcticfox/ArcticFox_TemperatureAnomaly_Tutorial)
Data from sensors can often contain anomalous values that need to be filtered out before processing data. This tutorial uses Arctic Fox to average past temperature readings to identify anomalous temperatures. We recommend you complete the Button Debounce tutorial first.  
- Automation Focus: SerialShifter, SetValue ($), always, Non-Blocking, Reset

## [4) Handwash Sensor](https://github.com/icii-arcticfox/ArcticFox_Handwash_Tutorial)
Physical signals often contain noise and need pre-processing. Debouncing is one such example. This tutorial shows you thehow to use Arctic Fox to debounce a button press using a counter. 
- Automation Focus: Calculate
- Automation API Focus: Dependencies, ApplyAutomation, Reg, CodeAfterNext

<br>
<br>
<br>

# How To Use Tutorials
We designed Arctic Fox and its tutorials to be simple to use. Follow the guide below to use Arctic Fox on Codespaces. If the below seems long, it's just because it's pictures. It is a rather short and simlpe process. 

<br/><br/>
Click the green code button at the top of the repo. 
![Step 1](https://icii.io/wp-content/uploads/2023/03/Screen-1.png)


<br/><br/>
Click the Codespaces tab.
![Step 2](https://icii.io/wp-content/uploads/2023/03/Screen-2.png)


<br/><br/>
Click the green "Create codespace on Step1_..." button. Use the default branch, which should start with Step1_.
![Step 3](https://icii.io/wp-content/uploads/2023/03/Screen-3.png)


<br/><br/>
The codespace will launch in a new tab. It will first show a window with a console, building the virtual machine (VM). Then, the VS Code window will be open. 

First, the Arctic Fox extension, and others, will be installed. While the blue stopwatch icon is shown, as highlighted below, extensions are being installed.  
![Step 4](https://icii.io/wp-content/uploads/2023/03/Screen-4.png)


<br/><br/>
Once the blue stopwatch is gone the Arctic Fox extension will be installed. Click the Arctic Fox icon on the left bar. 
![Step 5](https://icii.io/wp-content/uploads/2023/03/Screen-5.png)


<br/><br/>
Enter your Arctic Fox email and password. If you do not have an account, click the link under Create Account in the left pane.
![Step 6](https://icii.io/wp-content/uploads/2023/03/Screen-6.png)


<br/><br/>
Click the Activate Arctic Fox button. 
![Step 7](https://icii.io/wp-content/uploads/2023/03/Screen-7.png)


<br/><br/>
Arctic Fox will be activated. During this process, a blue wheel will be shown. After Arctic Fox is activated the VS Code window/tab will reload and refresh. 
![Step 8](https://icii.io/wp-content/uploads/2023/03/Screen-8.png)


<br/><br/>
Click the Arctic Fox icon on the left bar.
![Step 9](https://icii.io/wp-content/uploads/2023/03/Screen-9.png)


<br/><br/>
You will see that Arctic Fox is ready to run. If you are in a tutorial, the Tutorials section will be present. 

You can move between steps by selecting the step in the drop down and clicking the Switch button.

Open the Verilog and C# files to proceed through a tutorial. As you proceed to the next step, the correct code for the previous step will be shown. 
![Step 10](https://icii.io/wp-content/uploads/2023/03/Screen-10.png)