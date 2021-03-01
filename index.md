## Setting up the Live USB

The first step is to find a USB with atleast 32GB on it. 64GB or more is prefered.

### WintoUSB

WinToUSB is a program that allows for you to install Windows 10 to a USB for free. 
[Download WinToUSB](https://www.easyuefi.com/wintousb/downloads/WinToUSB_Free.exe)

### Windows 10 ISO

The next step is to get a Windows 10 ISO file to flash onto the USB. The iso can be downloaded [here](https://www.microsoft.com/en-us/software-download/windows10).

**EDIT**: To download the ISO instead of the Media Creation Tool, you must be using any device that is not Windows. However, if all you have is Windows PCs, [follow these instructions](https://www.howtogeek.com/427223/how-to-download-a-windows-10-iso-without-the-media-creation-tool/)

### Flashing the Windows 10 ISO

This is where you will begin setting up the computer for use.
- Plug the USB into your computer and open **WinToUSB**. 
- On the first page, find and select your Windows 10 ISO you downloaded.
![Image](https://raw.githubusercontent.com/itzrae1/schoolusb/gh-pages/InkedCapture1_LI.png)
- Next, Select the drive you wish to install the ISO to. (Select the USB)
![Image](https://raw.githubusercontent.com/itzrae1/schoolusb/gh-pages/InkedCapture2_LI.png)

**NOTE**: You will be asked to select a version, as I didn't upload the ISO I do not have this list. Select Windows 10 Home.
- On the next page you will get a list of options, select **Legacy** and **GPT for EUFI**.
- Wait for the process to reach 100% done, then eject your USB.

## Booting to the Live USB

The next step in the process is to boot to the USB after setting it up.

### Start Up & Setup

**Instructions**:
- Restart your laptop.
- When you see it start to boot up, press F9 until you get a boot device selection window.
- Select your USB from the list and wait for the computer to start.
- Next you will have to go through the Windows 10 Setup. This will take about 20-30 min.

### Sidenote

You will have to repeat this process everytime you wish to boot to the USB. 

Do not unplug the USB while using it, this will crash the system, and potentially corrupt data.

## Installing Software

Installing software is important to do so you can disguise this liveUSB as a school computer, while bypassing the school's blocking system.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/itzrae1/schoolusb/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
