To make sure everyone starts from the same place, we're going to begin by creating a self-contained version of Blender. This will have its own config file that does not affect any existing installation you may have or want to make in the future. 

This tutorial is being written for Blender 5.1. We will be using some features new to 5.1, so please make sure you are using at least that version if not newer.
## Download and Install

Go to <http://blender.org> and click the Download Blender button. Click on the 'macOS, Linux, and other versions button.' Choose the Portable zip.

![[Pasted image 20260331100526.png]]

Download and extract the zip to wherever is convenient for you. Browse to the extracted folder where `blender.exe` resides and create a folder named `portable`. The `portable` folder will contain all configuration files and extensions for this version of Blender.

![[Pasted image 20260331100838.png]]

## Configure

![](https://youtu.be/XXgOQnvUiEU)

---

Upon opening Blender the first time, it will present some options. Accept the defaults.

![[Pasted image 20260331104331.png]]

Under Edit > Preferences > Get Extensions, click Allow Online Access. Throughout this course we'll use a few free addons to streamline our process, but for now we'll just enable the option.

![[Pasted image 20260331104434.png]]

Under Keymap, enable Tab for Pie Menu. This will swap the functions of `Tab` and `Ctrl-Tab` from their defaults. We'll be using this pie menu extensively, so it makes sense to have it on `Tab`.

![[Pasted image 20260331104617.png]]

Under System, we need to tell Blender what kind of GPU we have. CUDA is for non-RTX Nvidia cards. OptiX is for RTX Nvidia cards. HIP is for AMD cards. oneAPI is for Intel cards.

![[Pasted image 20260331104726.png]]

