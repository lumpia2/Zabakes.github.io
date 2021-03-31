---
layout: post
categories: posts
title: ZMAC Mouse
tags: [Projects]
date-string: 
featured-image: \images\20150629_005942_123-removebg-preview.png
---

<left>
My friend Zac wrote this script to use dynamic keyboard layers on my MMO mouse. It's completely configurable so if you wanted to you could use it on a standard Numpad. I have been the project manager of this project. The team consists on Zac, Michael, Cody, and I, hence ZMAC. Zac and Cody are computer engineers while Michael and I are civil engineers. Zac and Cody focus a lot on the coding and software part, and now starting to work on a hardware for a future prototype. Michael and I take care of the marketing portion and now working to get a patent. Additionally, as project manager, I always keep the team in check and make sure things run smoothly.
</left>
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
A lot of this post is taken from zacharycolimon.com, make sure to check his website for more!
</p>

</center>