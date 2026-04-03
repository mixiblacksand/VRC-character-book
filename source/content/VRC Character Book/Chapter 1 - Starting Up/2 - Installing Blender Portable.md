# Goal
To make sure we all start from the same blank canvas, I'll begin with installing Blender Portable and making it use a unique configuration folder. Even if you have an existing Blender install you like, if you do this, you can experiment with this portable install without affecting the one you're used to.

>[!info] Version Matters
>This book will be using version 5.1. We will be using features new to this version, so make sure you're using 5.1 at minimum.
# Download and Unzip
Go to https://blender.org/ , click the Download button, and choose the 'other versions' dropdown.

![](Attachments/Pasted%20image%2020260401204313.png)

Unzip it somewhere you like. Go to the extracted folder where blender.exe is and make a new folder called 'portable.'

![](Attachments/Pasted%20image%2020260401204446.png)

Now any time we run that blender.exe, all of our configuration will be stored in the portable folder instead of in the OS user folder.

>[!warning]
>Linux users, you're on your own here. Blender works great on Linux, but I can't speak to how configuration files are stored in that environment.
# Configuration
When you first open Blender you'll be greeted with this splash screen:

![](Attachments/Pasted%20image%2020260401205025.png)

Click 'continue' to accept the defaults. Click outside the next splash screen to dismiss it.

Click Edit > Properties and click the System tab. At the top is a selection for Cycles Render Device. 

![](Attachments/Pasted%20image%2020260401205215.png)

Cycles is the name of Blender's raytracing rendering engine. This will come into play for us eventually, so make sure this is set:
	CUDA for non-RTX Nvidia GPUs
	OptiX for RTX Nvidia GPUs
	HIP for AMD GPUs
	oneAPI for Intel GPUs

Close Preferences when you're done and they will auto save.