---
title: "In India, modding is your (statutory) right"
description: "\"erm yes hacking software is cool, but is it legal? 🤓☝️\""
author: "Derpitron"
heroImage: "./hero.png"
pubDate: 2026-10-17
---
# Introduction

With the rapid rise of LLM-driven software drafting, reverse engineering, decompilation, and crossporting/compatibility layer drafting ([and its' discontents](https://jpeisach.github.io/blog/ai/legoisland/decompilation/porting/reverse-engineering/2026/10/16/decomps-clout-consoom.html)), more and more people are exposed to the possibilities of modding their software and games. There is also a growing desire for people to run software of their own, free from dependency on foreign control.

In this post I want to bring awareness about some of India's copyright laws and user-rights, with respect to software. We need to be aware of our rights, and teach them to each other too, so that we have the confidence to do more and better hacking, and make software work the way *we* want.

## Section 52 of the Copyright Act of India: Your software rights

(1) You have the right to do the following to any computer program (as long as you didn't pirate it):

(aa) copy or mod it how you want, just to repair it or temporarily save backup copies, but it must run the way the manufacturer wants

(ab) hack it however you need, to connect it with other programs, if it doesn't have an API

(ac) reverse-engineer it however you want, to understand how it works, but only while running it the way the manufacturer wants

(ad) copy or mod it how you want, but only for personal and non-commercial use, and only if the way you obtained the program was through personal, not corporate means (i.e not a corporate license)

[You can do these even if any EULA or contract forbids you,](https://indiankanoon.org/doc/164343914/#:~:text=17%2E-,I,anyone%2E) because [these are your rights as a user!](https://indiankanoon.org/doc/93327052/#:~:text=167%2E-,In,interpretation%2E) 

This is a *public* right, so feel free to share what you learn and do with these rights with other people too. (e.g form a reverse-engineering or modding community for a videogame) Just as long as you're all following the law.

You can do these for however serious or pointless of a usecase you want, from open-source solar panel firmware to videogame hacking. It does not matter.

## Section 65A: What you are not allowed to do with a computer program

You are not allowed to circumvent a DRM/content protection technology because you want to pirate it. But you are allowed to do it, if your intentions are anything other than piracy (e.g disabling spyware, reverse-engineering it for fun and learning, making the software more modding-friendly, or repairing it if it's outdated.)

It's legal to make and publicly share DRM breaking tools (i.e cracks, mod tools, unlockers, jailbreaks, etc) too.

### Examples of Section 52 conduct

These are a few common examples I could think of. Obviously there may be a lot more acts that go beyond this, but I hope you can understand the sense.

If you bought a game in 2010 that requires a connection to a remote server, but that server went down in 2013 because the company went bankrupt, then **(aa) allows you** to patch out that requirement, because you're just trying to repair the software so it works the way it was marketed to you.

If you want to connect your smartwatch's heart health data to your custom web dashboard, then **(ab) allows you** to reverse engineer how the heart health monitor's software works, create an unofficial API/data trace, and connect it (i.e interoperate it) with your own dashboard using that unofficial API or data collection layer.

If you think your electric car's battery management system is really cool and efficient, then **(ac) allows you** to crack it open in a decompiler software such as Ghidra, find the algorithm which controls it, and understand how it works.

If you're feeling bored, and want to make DOOM run in Adobe Photoshop's Colour Picker window, **(ad) allows you** to do that. But you can't do this if you want to do it in the copy of Adobe Photoshop that your graphic design studio purchased (because that's a commercially obtained copy), and you can't then sell this cool little mod for money on Patreon, or make a business out of installing DOOM on other bored workers' Adobe Photoshop apps (because those are commercial uses).

### Example of Section 65A conduct

E.g if you want to add a new car to a racing videogame, but the videogame blocks you from modding its' code with a protective DRM, then **it's legal** for you to disable or remove that DRM, because you only want to mod it.

If you paid for software in 2010 that requires a connection to a remote server for authentication, but the software vendor went bankrupt in 2013 and thus their server shut down, then **it's legal** for you to patch out that server connection requirement, because you're only trying to get it working.

But if you disable or remove DRM because you're actually trying to copy the software and share it to your friend who doesn't want to pay for it, then **that's illegal**, because you're doing it with an intention of piracy.

If you remove the watermark or DRM from a movie file because you're trying to share the movie online to the public, without the creator's permission, then **that's illegal**, because it's done with the intention of piracy.

# How are you sure about all this?

I'm not. None of the software-rights interpretations here have been tested in any Court in India yet, unfortunately. [However, the courts have on occasion given comments that affirm this spirit](https://indiankanoon.org/doc/164343914/#:~:text=17.-,I,anyone.), which I believe [could give credence to a more broad, liberal interpretation software-users' rights.](https://indiankanoon.org/doc/93327052/#:~:text=167.-,In,interpretation.)

There might also be conflicts with other laws, such as cyber-crime (The IT Act, 2000), contract law (The Indian Contract Act) or data privacy (Digital Personal Data Protection Act), that have yet to be ironed out.

Future court cases, or laws might contradict what I've written here, in which case I would update any claims or examples as and when they develop.

# Why should I care?
Software hacking is cool and empowering, and technical artistry at its' best.

But none of this can exist if people don't have the legal right to modify their software. If it was illegal, or if contracts were allowed to ban you from doing it, then anybody who hacks or mods their software (or any software-based device, such as a [tractor](https://www.wired.com/2015/04/dmca-ownership-john-deere/), [game console](https://en.wikipedia.org/wiki/Sony_Computer_Entertainment_America,_Inc._v._Hotz), [calculator,](https://www.theregister.com/offbeat/2009/09/23/texas-instruments-aims-lawyers-at-calculator-hackers/1455704) or smart-fridge) would be at risk of a lawsuit, discouraging them from running their computers and software how they want.

> Commonly, only Free software would give you the right to do this; the point of Free Software is that you have the right to do anything you want with it. This was one measure that user-rights activists used to promote and secure software freedom. However, a full legal right to freedom that everybody has is far more helpful to the cause than just individual contracts that guarantee freedom, which is why statutory rights as the EU and India have provided are so important.

Knowing our rights lets us hack and mod, and share our knowledge and techniques with each other, with confidence. People could expand the craziness or reach of their mods, with full knowledge and confidence that it's legal. It might even permit us to create tools to eventually escape Walled Garden platforms, if we don't like them. ([Or at least use them on *our* terms, not *theirs*](https://github.com/lugvitc/whats4linux))

\- Written by [Derpitron](https://5rupee.co.in)

# Source?

[The Copyright Act 2012, of India](https://indiacode.gov.in/act/6b893162-631a-453b-a7b9-89685716889b/)

*[Image source](https://www.tumblr.com/itrunsdoom/146488499533/the-sony-ericsson-k800i-and-others-yeah-it)*