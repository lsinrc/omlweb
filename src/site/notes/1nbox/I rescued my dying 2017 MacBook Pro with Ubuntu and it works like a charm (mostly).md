---
{"dg-publish":true,"permalink":"/1nbox/i-rescued-my-dying-2017-mac-book-pro-with-ubuntu-and-it-works-like-a-charm-mostly/","tags":["gardenEntry"],"dg-note-properties":{"Title":"I rescued my dying 2017 MacBook Pro with Ubuntu and it works like a charm (mostly)","Date_Saved":"2026-03-19T10:18:20-06:00","Date_Written":"Jan 9, 2025 at 03:40","Source":"https://www.zdnet.com/article/i-rescued-my-dying-2017-macbook-pro-with-ubuntu-and-it-works-like-a-charm-mostly/","Author":null,"Tags":["webclip","Intel","MacOS","install","Linux"]}}
---


￼

Jack Wallen/ZDNET
I have two MacBook Pros. My daily driver is an M1 version and the other is a 2017 edition with an Intel CPU. The M1 laptop works like a champ and will probably continue to do so for a few more years. 
However, the Intel-powered MacBook had pretty much become a paperweight. As usual, I upgrade apps and OSes when a new version arrives. Little did I know how much havoc upgrading to the latest (at the time) version of MacOS would wreak on the system. 
Also: How to install an LLM on MacOS (and why you should)
Once I upgraded the OS, the laptop pretty much became useless. Not only were apps maddeningly slow to run, but the battery would last for about 20 minutes. To make matters worse, I could no longer do a factory reset because the latest OS didn't support a reset on the Intel architecture.
I was pretty much stuck. Because of that issue, the Intel MacBook gathered dust until we were blanketed by nearly a foot of snow, and I wound up with some extra time on my hands. I decided it was the perfect moment to install Linux on the laptop.
Before I continue with this guide, you should note that the installation isn't perfect. I installed Ubuntu 24.04 and found the following things didn't work out of the gate:
	•	Wi-Fi
	•	Sound
	•	Touchbar
	•	Keyboard backlight
	•	Suspend
I could live without everything but Wi-Fi, and I tried to get it working. After a few hours, I did get Wi-Fi to work, but it was unreliable. Fortunately, I had a Wi-Fi dongle that was compatible with Linux. After inserting that dongle, Ubuntu had wireless, and I could do my thing.
My first surprise was how well Ubuntu ran on the machine. I'd go so far as to say it performs as well as MacOS on my M1 machine. Ubuntu is fast and stable. 
My only complaint was that, while the trackpad worked, it was a bit twitchy, so I had to use it with extra care.
Also: Elementary OS 8 continues the tradition of a beautiful, user-friendly desktop
So, how did I get Ubuntu installed on my 2017 Intel-based MacBook Pro? The process is fairly straightforward; here's how it went.
How to install Ubuntu on an Intel-based MacBook Pro
What you'll need: To make this setup work, you'll need an Intel-based MacBook Pro and a wired network RJ45-to-USB adapter, such as this one found on Amazon or a Wi-Fi dongle, such as this one from D-Link.
You should note that this method will wipe MacOS from your machine, so only do this installation if you're certain you won't need Apple's OS on your MacBook Pro.
First, download the Ubuntu ISO from the official download site.

2. Burn the ISO to a bootable drive

You can read how to use UnetBootin to burn the Ubuntu ISO to a bootable USB drive in my piece, 'How to create a bootable Linux USB drive'.

3. Boot your MacBook Pro with the USB drive

Insert the RJ45-to-USB adapter and connect it to your router or modem. If you go the Wi-Fi dongle route, insert it into one of the USB ports. Insert the bootable drive into your MacBook Pro and press the power button. 
Also: What is an AI PC exactly? And should you buy one in 2025?
Immediately press the Option key and hold it until the boot menu appears. Don't bother connecting to a wireless network, since it won't work when Ubuntu starts. Select the USB drive and click the downward-pointing arrow. Ubuntu should then boot.

4. Walk through the Ubuntu installation

When you arrive at the Ubuntu desktop, click the Installer icon and walk through the user-friendly installer. This process shouldn't take much time to complete. When the installation is finished, reboot. 
When the system reboots, you should find yourself at the Ubuntu login screen. I'm still trying to get the sound and touchbar to work (I'll address those issues when I discover the solution). Other than those issues, Ubuntu works like a charm. I can install all the apps I need and trust that the battery lasts considerably longer.
Also: My Linux predictions for 2025: It's going to be a good year
I'd pretty much resigned myself to thinking that the old MacBook Pro was no longer a viable machine. However, thanks to Ubuntu, it has performed better than in years. Sure, there are things I still need to work out (and will do so as soon as I have some extra time), but the basics of the laptop work, and Ubuntu performs far better than I expected. 
If you want everything to work with Ubuntu on your MacBook Pro, you should know that you will have to spend some time researching the version of your laptop and how to get the various components working that don't function from the outset. 
Was it worth the time and effort? You bet. I was sure this laptop was destined for the recycling yard and hated the idea of adding more electronic waste into the mix. Now, I don't have to, and I can use this Linux-powered MacBook Pro as a spare. 
Also: The best Linux laptops of 2024 
If you have an old MacBook Pro you're no longer using, I'd suggest giving this approach a go. Keep checking because I'll write more pieces about this installation process as I get the other features to work successfully (and reliably). After all, without the touch bar, there are no function keys. 
