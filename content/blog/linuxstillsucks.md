---
title: "Linux still sucks—here's why you should use it"
date: 2026-03-01
authors:
  - name: typewatch
    link: https://github.com/typewatch/
    image: https://github.com/typewatch.png
tags:
  - linux
  - microsoft
  - arch
  - coding
---

Over the last few months, Microsoft has been flooring it on their way to enshittify everything they touch. Is it finally time for Linux to shine?

<!--more-->

The short answer: No, not really. Linux still has a ways to go, and it is *just not ready yet* for the average consumer.

The long answer: Windows—historically plagued by bad updates and bloat—has been getting useless AI features hammered into it non-stop since last year.

First came copilot (Microsoft's in-house multimodal AI model) and along with it preceded a ton of useless AI integrations into every nook and cranny of Windows: if you were to do a fresh install of Windows right now, it will include about a dozen different instances of copilot scattered around almost all major apps, from basic daily-use apps like Edge Browser and the settings app all the way to something as simple as Notepad. It is **everywhere**.

Starting last year, they even began shipping out computers with a dedicated copilot key for "easy access" to an AI app that was [meant to spy on you.](https://support.microsoft.com/en-us/windows/retrace-your-steps-with-recall-aa03f8a0-a78b-4b3e-b0a1-2eb8ac48701c)

Oh and by the way, you can't uninstall it. Windows is really picky regarding what system packages you are able to remove, and as such, they make it nearly impossible to delete a feature you don't want from your own computer. Fortunately, you are able to disable some parts of it temporarily, whatever that means.

All of this fueled a new wave of criticism and overall bad sentiments towards Microsoft and its products, recently gaining it the nickname of "Microslop". After all of these events, many life-long Windows users looked towards Linux as a simpler alternative.

## The alternative
Actually, there are two alternatives, but both differ in that one lets you reuse your hardware and the other requires you to buy a very expensive machine and pledge allegiance to the fruit. You can guess which one we'll be skipping today.

When people refer to "Linux", most mean GNU/Linux. Linux itself is not an OS, but a kernel, which is the baseline layer within an operating system that talks to hardware and manages processes. GNU/Linux is a combination of this kernel plus a bunch of utilities like a shell (a command-line interface and command interpreter), file and text manipulation tools and other stuff.

Then this is divided further into distributions, or "distros". Every distribution adds or removes software to fit specific use cases, or improve general usability. Modern Linux distros are carefully designed combinations of the kernel, basic GNU utilities, plus a desktop environment and additional applications. Some contain more software than others by default, but it all depends on that specific distro's use case and ideology.

Linux is one of the most prevalent examples of open source software and collaboration. Originally created by Linus Torvalds, it is now maintained by multiple users throughout the world. The grand majority of distributions follow this mindset, being FOSS (free and open source software) oriented.

It has been the dominant OS on the enterprise sector, running in most servers and supercomputers, but it just hasn't gotten its time in the consumer spotlight.

Despite its dominance outside the consumer sector, for years Linux has been trying to increase its stake in the consumer OS market. Unfortunately, it hasn't been able to gain more than 5% of the consumer desktop OS market since its appearance. This is fantastic for such niche software, but 5% isn't enough to be competitive with bigger sharks like Windows' menacing 65% and macOS's 15%.

Linux has not been around as long as others have, and isn't as widely recognized, but the public opinion on it has been growing stronger every year, and with recent improvements it finally looks like it might just be about time for it to claim more territory.

## I don't like Windows
I have technically been a Linux user for years, having my first taste when I put raspbian on a raspberry pi as a kid. Since then, I've tried several distros and have been running Linux on my homelab for a while.

However, I can't actually say I have *used* Linux, as I've been a Windows person since my first interaction with a computer. I have considered switching before, but I never actually went through with it. Switching's not hard if you've got a good guide and some base knowledge, but it does take some time and preparation—even more so if it'll be your main OS—which I am too lazy to do. So I put it off, and off again, and then off again again.

And a year or two later, I've stopped the perpetual OS migration procrastination. I was already up to my wits end with a number of issues and bugs and nitpicks which Windows has that, albeit minor, make you go crazy over time. But that wasn't enough to make me go over the trouble of switching. I thought the final straw would be the rollout of AI features, but it seems I was too hesitant to go ahead and spend a whole weekend sorting my files and transfering them over, so I put the switch off again.

The next final straw was when Windows started having tons of system stability issues out of the blue; programs kept hanging, microstutters galore, crashes were aplenty, and even random system-wide freezings occurred for no apparent reason. It was hard to notice at times, but it was still there. I did some digging, and turns out this was caused by the (forced) rollout of a faulty system update. I was mad. This however, was not yet enough for me to switch over.

What it did do was compel me to perform a "tiny experiment" (or so I thought); I had never put Linux on my main computer, so I figured I should just to give it a try. "It'll take no longer than an hour or two" I thought, so I went ahead with it, and set up a lightweight Arch system on a mini-partition. 

Immediately after logging into the DE, something felt off.

It was not the similar yet unfamiliar Plasma environment, nor the different fonts, or the completely unique Linux-only software. It was the smoothness and snappiness of Linux. After working on Windows for so long, I had grown used to the myriad of issues it had; and Linux was a breath of fresh air from the massive disaster that is Windows. This was the real final straw.

That same evening I backed all of my data up, and settled into my distro of choice: Arch Linux.

## I switched to Linux, and it's...
Depending on your chosen distro, the switch can be either stupidly simple or akin to rocket surgery.

In the distro I chose, you have two main ways to install the OS onto your computer, and both require quite a bit of manual labor and thinking before you can use your new operating system. You have to specify through the commandline where to install, what to install, how to install, for who to install, and a bunch of other stuff. For an experienced tech, it is a piece of cake, but for the average joe, it can be a little jarring and off-putting.

I had no issues with my installation; with my important files taken care of, all I had to do was plug in a boot thumb drive, do a quick install config and let it do its thing. In less than an hour, I already had a somewhat batteries-included system. I still needed some extra stuff, but it was practically ready-to-use for basic things. Other, more mainstream distros are easier to install and come with even more useful software out of the box. This is great as people short of time or tech knowledge can quickly set up a basic Linux system by themselves and get up and running in no time. 

Then comes the bad part; Linux lacks the widespread compatibility that other operating systems like Windows or macOS have out of the box, so you will eventually need to install a couple of drivers to make sure Linux can interact with certain hardware, and then a few more to make sure your hardware runs properly. The download and install of drivers in Linux is a very quick process, but it can take hours of messing around to find exactly what you need and test it. It took around an hour to get my printer working.

After that, you get to tune everything by hand for hours (yay!). Since Linux distros are meant to be installed on all kinds of systems, they have to be built with a catch-all mindset. This means that even if you install the appropriate drivers for Linux to talk to your computer and peripherals, you still have to configure most of them so they work at peak performance with your specific system specs. 

For instance, while in Windows my laptop gave me around 4 hours of runtime, Linux out of the box barely gave me 2. However, after taking some measurements and installing a specialized tool for power management, I quintupled my out-of-the-box runtime to 10 hours. The good part about having Linux's forced fine-tuning is that you can control everything. And when say everything, I really mean everything. I can even disable my GPU now!

And after that, comes the fun part. Well, fun-ish.

Remember how I said you can control everything? You can even change the look of your OS; from fonts and custom colors all the way to system-wide themes. Of course, like all things Linux, it takes a while and you might break something in the process, but in the end you can achieve very nice results.

Finally, you have a complete Linux system. Some parts you can skip, others (usually the worse ones) you can't. All in all it takes around a day or two before you reach the end, but once you do, it feels very nice to have an OS customized to your specific wants and needs, by you. It's one of those things that brings out a little smile when it works just as you wanted it to.

As for usage, it's not much different. Yes, you can't run .exe files the same way you can't use .dmg files on Windows, you can't use certain software as it was not designed for Linux, and a couple other things that vary between distros, but you can still do normal computer tasks the same way (or better) with alternative software.

I like it. I won't be moving OSs any time soon.

## Penguins are flightless birds
Just as how penguins are really cute birds, but have one major flaw (they can't fly), Linux is an overall great OS, but has one big issue.

As of 2026, there are still plenty of roadblocks that prevent most users from jumping over. As you might remember, I mentioned "alternative software" in the previous section. What did I mean by this? Oh boy.

For some reason or another, major software corporations like Adobe, Dassault Systémes and Epic Games cannot be bothered to port their fantastic software to Linux. They have done so for multiple Windows and macOS versions, but they just can't for Linux. This makes for a big bump in the relatively smooth OS transition road, as most users prefer to stick to what they've already used to and know works for them. Alternatives exist, but none are perfect copies of other software.

Compatibility has always been a problem in Linux, but fortunately is less widespread nowadays thanks to the development of compatibility layers like Proton (a "translator" software of sorts that allows Windows games to run on Linux) or Wine (~~an emulator~~ another translator but for Windows apps in general). In some cases, software designed for Windows ends up running better in Linux even through a translation layer.

Then there's office essentials like Microsoft 365 (Word, PowerPoint, Excel) that cannot run in Linux. Even though some workarounds exist, it is quite difficult to get these working properly. Again, alternatives exist, but they won't be exactly the same as the original tools.

There are plenty more compatibility problems that all boil down to the software publisher's fault, and for most conflicts there is no better solution but to switch to another software completely. Despite this, many people have done the switch successfully, and prefer the alternative software (often FOSS, meaning you aren't locked into it) over their original selection.

## Why you should switch
My reasons to switch were already there for a long time, and the sentiment too. All it took was one last thing to switch over.

It's different for everyone, but I can almost guarantee you already have one or more reasons to hate Windows. And if not—trust me—you will. The community agrees that modern Linux distros are very flexible and can be used by anyone given sufficient time to get the gist of things, but for people like old gramps that just wants to check his Facebook once a month, it may not be the best pick *yet*. 

Windows has been getting significantly worse over time as of late. If you're able to make the switch, you should go for it; maybe not towards a complex distro like Arch if you don't feel very comfortable with setting everything up from scratch or using the command-line, but towards a simpler, more streamlined one like Fedora or Ubuntu, which come with plenty of batteries out of the box and have a fancy graphical installer.

Linux may not be the best, but the tradeoff is definitely worth it for the customizability, stability and pure freedom it provides. With alternative operating systems losing scope and falling for profiteering over user comfort, Linux is one of, if not the best options for an OS out there.