---
layout: post
title: "Echo Show Hacking"
date: 2026-11-14 16:24:00 -0000
description: "How to open hidden apps in the Echo Show 8 (2nd Gen)"
tags: [discovery, notes]
---
# Echo Show Hacking!
## I have a *Echo Show 8 2nd gen* and I've found some ways to open some hidden apps on it! 
The Echo Show 8, and all the Echo Shows **run a locked down, stripped down version of Android with their own application layer and custom apps**. 

***
*This is not generated/helped with AI. It's written by a real human with a cheap, but good keyboard :P*

**Best discovery (as of now) at the bottom!**

***

**To check the Android version of your Show**;

- You can open the Amazon's proprietary **Silk browser** by saying, "Alexa, open Silk"
- Open **Settings**
- Click on **Advanced settings**
- Click on **About Silk**

There you'd found the Silk (Chromium ig) version, and Android Version. For my case it's Android 9. 

***

### Discovery 1 (Stock E-mail client)

I found that there's a preloaded Stock (AOSP) E-mail client on there. To open it, 

- Open the **Silk Browser**
- Go to any web address with a E-mail hyperlink. For example, https://aftvnews.com/contact
- Click on the hyperlink and you'll successfully open the Stock client!

(I haven't tried configuring any real E-mail on there. As of now, **Disroot is experiencing some storage problems, Outlook is down *(I love you Microslop, and I don't use it either)*, Google *(Sorry, no thanks)* and Microsoft are being dogshit, and I don't want to set anything else up.** But the client is there, so that's interesting.)

### Discovery 2 (Stock calendar)

- Open the **Silk Browser** (everything happens through there)
- Type any date in **dd/mm/yyyy** format (example 9 November 2011) 
- Now hold the date to select it (after searching)
- Now you'll see some options like copy, paste, etc. and also "View"
- Click on that "View" and you'll see the **Stock Calendar** app (Android 4 design)

### Discovery 3 (continued from Stock Calendar app, open the hidden Stock File Manager)

- Now that you've opened the calendar, click on the upper right three dots
- Click on **Settings**
- Then **General Settings**
- Swipe down untill you see the **Notifications & Reminders** section
- Click on **Sound**. There you'll see stock Android ringtones and sounds
- Now swipe down in the Sound window untill you see the **Add ringtone** button
- Click and you'll see the File Manager!
- Click on the upper three dots in the File Manager and click **Show internal storage**

However the file manager only allows selection of some ringtones and nothing else. But atleast we can see the files and the storage.

### Conclusion

The Echo Show is definitely more like a locked-down Android device than a simple smart display. There are still hidden system apps and parts of the stock Android layer exposed through browser interactions and the download flow.

I don't think it's powerful enough yet to do anything dangerous, but it does show Amazon's custom shell is not as airtight as it looks.

If I find a real app launcher or something crazy, I'll post it here.
