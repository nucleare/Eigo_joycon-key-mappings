/** Touch-up of the literal translation will be made in a later commit **/
================================================== ====================

                        JoyToKey Version 6.4.2

                     Copyright(C) 1999-2020, JTK

================================================== ====================


## ■ 1. Description of this software ##

This software converts the (Joycon Switch Controller) joystick input into keyboard inputs,
It allows you to operate various applications in a pseudo manner.
Especially for Windows software (apps) that does not support the joystick or other software on the web
Use this program when you want to play your PC games using the Joycon controllers.

Note: For Windows Vista, 7, 8, 10 JoyToKey may trigger security notifications.
Some features may not be available depending on your Windows security settings.
If this happens, please try running as administrator to resolve the issue.

/** Editor Marker for continuation **/

### <Main features>###

- Multiple setting files can be created and easily switched.
It is also possible to switch automatically for each target application.
- Make one button on the joystick correspond to multiple keys on the keyboard
 can do. (For example, set button 1 to "Alt+F4"...)
- Mouse input such as mouse cursor movement, wheel rotation, click, etc.
Emulation is also possible.
- It also supports the automatic continuous shooting function.
- In addition, you can switch the setting file with the button.

For example, usually assign the main operation key to the joystick 1 and use it
There is a virtual joystick 3 temporarily while button 5 is pressed
You can use the settings (such as function keys) in the sub, and the button 6
When pressed, it can be used, for example, by switching to mouse operation mode.


## ■2. How to install ## 

Please unzip the file and put it in an appropriate folder somewhere.
Place the shortcut on your desktop or at startup if necessary.

Note that the setting file is created in that folder, so write the folder
Must be possible.

If you want to uninstall it, delete the folder or shortcut.
(I don't use the registry)

You need Windows 2000 or later (DirectX 7.0 or later) to use JoyToKey.


## ■3. How to use ##

**For the time being, start it up and use it appropriately.**
First, we recommend that you try using simple software such as "Notepad". And
Don't know/If you want to use it more effectively, please read the following.
- Press the "New" button and give the new configuration file a name of your choice.
  Example: "Browser operation" "PowerPoint presentation settings" "○○○ for games" etc.
_Note: Since this is the file name as it is, "\*<>?|" etc. cannot be used._
- Select the joystick button you want to set and double-click or return.
Press the key to display the setting window. And for each button
Assign one of the following functions: keyboard, mouse, special.
- Alternatively, click the "Easy Setting Wizard" button to set easily.

** What you can set in the "Preferences" page **

1. You can change the number of joysticks to set (1 to 16) *(If you make it smaller, you can save some setting file size and processing speed.)*
Note that you can specify it regardless of the number of joysticks that are actually connected.
2. Whether to use other than X-Y axis (2nd stick, other 6 axes, etc.)
3. Whether to set a special key for diagonal input. 
- For example, I want to assign the cross key to 2,4,6,8 and the diagonal input to 1,3,7,9
Check in case, etc.
*(It is not necessary when diagonal input can be pressed simultaneously with 2-4, 4-8, 8-6, 6-2)*
4. Whether to use the POV switch (hat switch)
 *(You can choose whether to assign the key to 4 directions or 8 directions)*
5. Threshold for analog input
 *(For details, please see the item of Ver3.7 in the update history)*

The configuration file (*.cfg) is just a text file, same as JoyToKey.exe Generated in a folder. So, if you want to change the name of the setting file, duplicate it, ...
- Quit JoyToKey once and open the corresponding file in Explorer etc.
- All you have to do is change the name, make a copy, and so on.

If you are playing a game, etc. If you are in a sick state, tap the button repeatedly to fix it.


## ■4. Convenient usage ##

**If it is troublesome to run as an administrator every time on Windows Vista / 7, **
- Right-click JoyToKey.exe in Explorer and select Properties → Compatibility If you check "Run this program as an administrator" You can omit it from the next time.
- Or in Start Menu -> Accessories -> System Tools, Use Task Scheduler to check "Run with highest privileges"
- If you schedule it to run automatically when users log on, Set JoyToKey.exe to start automatically when the computer starts.

**You want to use this configuration file for a specific application.**
If you want to switch the setting file for each application frequently, By associating the application with the setting file in advance
Automatically setting JoyToKey every time the target application switches You can switch files.
* (Menu: “Settings” → “Associate with application”)*

**If you want to operate the browser with a joystick, use the simultaneous pressing of keys It can be realized by that.** 
For example, in the case of Internet Explorer,
_ “Return to previous”: Alt + ←
- ”Close window”: Alt + F + C
- ”Move to menu”: Alt + F
By assigning such as, you can operate in a pseudo manner. As well Then, you can operate other general Windows applications.

**When using the joystick instead of the mouse,** 
- press the acceleration/deceleration buttons.
- If you apply it, it will be easier to move.

**If you want to use many button settings,**
-  "Special settings" "Change settings to be used temporarily"
- It is convenient to use. This is only when a button is pressed
- It is possible to follow the joystick settings of other numbers.

For example, the joystick 1 usually emulates "↑↓→←ZX..." However, it is assigned to joystick 2 only while pressing button 4.
It is possible to press "F1, F2, F3, F4..." (here (Joystick 2 is a virtual joystick and is not actually connected)

Furthermore, it can be nested (what if button ○ and button ◎ were pressed...)
I think it is a difficult function to understand, but I think that the number of buttons that can be used is small If you have any questions, 
please give it a try and use it effectively.

**"Switch to other setting file" of "Special function"** You can do something similar to the above by using.
In this case, it will switch completely, so keep pressing the button It does not have to be. 
For example, 
- toggle the two settings each time you press the button ○.
- It is possible to go back and forth. However, if you
- It takes a moment to switch. Please choose the preferred one according to the situation.

"Everywhere Wheel" by araken when emulating a wheel
Http://www2k.biglobe.ne.jp/~araken/
If you use both at the same time, the application that does not support the wheel function. It is convenient because it can be rotated.

** (NEW) If you want to operate the mouse and keyboard with one button, Ver5.5**
It will be possible by using the button number assignment function added later.


## ■5. Other ##

This software was created based on ditk by Saka. He would like to take this opportunity to thank you.

In addition, this software is compatible with Machida-san's "Done Mouse." "Done Button +."Supports cooperation. Keyboard, mouse, gamepad for obstacles
Even if you can not operate, etc., input instructions such as switches and sensors I hope I can help you so that you can operate your computer through.
(When using for welfare purposes, JoyToKey is freely distributed, and the license is (You can use it for free without worrying about it)

Machida's site
http://dekimouse.org/


## ■6. About JoyToKey **~From the original author** ##

JoyToKey became shareware software from Version 4.0.
However, there are no functional restrictions or trial deadlines, so keep using it as before.
I would appreciate it.

(If there is more than enough development environment, and how many people
I also want to know if you are paying for it and using it regularly.
I hope that it can be used as a reference for the direction of new function development. )

The price is 734 yen (including consumption tax and fees).
Payment methods are currently via Vector and via Digital River's share*it!
Two types are supported. If you like JoyToKey, or if you would like to join us,
JoyToKey menu "Help" "Purchase license key"
You can pay from.

Please refer here for details.
https://joytokey.net/ja/purchase


If you want to reprint, distribute, or record in a magazine, please feel free to contact us.
(Thank you for contacting the author in advance)

In addition, even if the user suffers damage by using this software,
Please note that the author is exempt from any responsibility.
Please.

Also, this software does not work well for some software,
Please note that this is also a specification.

I've been busy these days and can't take a lot of time, so I basically support and reply to emails.
I think it's difficult to do, but after acknowledging that, there are requests and bug reports etc.
If you have any questions, please feel free to contact the author. Regarding requests from many people
Then, I would like to respond as much as possible
