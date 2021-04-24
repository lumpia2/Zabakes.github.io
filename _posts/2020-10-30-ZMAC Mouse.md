---
layout: post
categories: posts
title: ZMAC Adapt
tags: [Projects]
date-string: 
featured-image: \images\20150629_005942_123-removebg-preview.png
---

<p>
To shortly describe what the ZMAC Adapt does, it basically configures a typical MMO mouse which can then adapt a set of hotkeys assigned to it depending on the application that the user is working on during that time. The script for this idea was written by a friend of mine, <a href="https://zacharycolimon.com"> <u> Zachary Colimon</u> </a>, who would later ask <a href="https://arielholstein.com"> <u>Ariel Holstein</u> </a>, Michael Akinsola, and me to be a part of this creation. Our team consists of two computer engineers, Zac and I, who will focus on optimizing the code and designing the hardware to be used specifically with the software. Ariel and Michael will focus on the CAD and business aspect of the project which involve promotions and collecting user data.
</p>

<center>

<H1>USE</H1>
<img src="\images\20150629_005942_123-removebg-preview.png" alt="Hotkey setter GUI">
<p>
Using the script is complicated to explain but simple in practice. The idea behind the script is a dynamic keyboard layer based on the active application. This can be broken down into two parts. 
</p>
<p>
The first is the idea of a keyboard layer. "Layer refers to a set of additional key bindings achieved by holding down a modifier key on the keyboard." (deskthority). The most basic example of this is the shift key. Normally all the letters are mapped to their lowercase variants, but when the shift key is held the "uppercase layer" is activated and KEYS BECOME MAPPED TO UPPERCASE LETTERS. The mouse script works the same way, when the toggle key is held the keys to toggle (as specified in config) get mapped to a dynamic layer. 
</p>
<img src="\images\ZmacDemo.gif" alt="Example">
<p>
<p>
This layer is dynamic because it changes based on the active application. If you're using Chrome "6" might be mapped to change tabs on this layer. If you're using VSCode instead "6" might be mapped to the hotkey for selecting the current line. This is completely customizable using the configuration utility. In the example above you can see 6 mapped to camera controls in CAD then mapped to change tabs in firefox.
</p>

<center>
<H1>Configuration</H1>
<img src="\images\Hotkey_Setter_8k3CyImyNy.png" alt="Hotkey setter GUI">
<p>
The configuration of the script is handled in a septate script called "Hotkey Setter.exe". This script has a GUI that allows a user to set up custom hotkeys for applications of their choice. 
</p>
<p>
The window Title box is what allows the user to specify the application they want the background layer to be used on. The file name option allows users to specify the name of the file that this configuration should be saved in. Each number corresponds to a physical button on the input device in my case a mouse. The top box specifies the action to take when a key is pressed down, while the bottom box specifies the action to take when the key is released. 
</p>
<p>
The config checkbox in the top left lets the user specify what keys to toggle on. The toggle key can be specified here in a box labeled toggle key. In this mode the top box lets you specify the key to toggle on and the bottom box defines what that key is mapped to by default. This allows the script to be versatile and work with any buttons the user wants.
</p>
<p><a href="https://github.com/Zabakes/togle-script/releases" target="_blank">Download from github</a></p>

<p>
A lot of this post is taken from <a href="https://zacharycolimon.com"> <u> zacharycolimon.com </u> </a>, make sure to check his website for more!
</p>

</center>