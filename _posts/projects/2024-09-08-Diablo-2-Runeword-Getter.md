---
layout: post
description: 'A handy runeword calculator for Diablo 2'
date: 2024-09-08 17:12:37 -05:00
category: project
---

## Finally something useful

I've been programming for over a year now and while I've built a few things already, I haven't really forseen anyone else using them but myself. This time however is slightly different as I can see someone else getting some decent use out of this one.

## Runeword calculator

The app functions soley as a calculator for runeword matches based on your current inventory, which you can add to or remove runes from using the point and click GUI. Clicking on a desired runeword will 'build' it whilst subtracting the required runes from your inventory.

## WIP

This is technically my first Electron app that compiles - a previous RSS Feeds app that I haven't quite decyphered the build process on yet - and it's a work-in-progress. It's far from being a polished alpha in that case; there are some current issues with it I should mention:

- Rune icons don't load as expected outside of dev mode
- The app's icon is clipped at the top for some reason
- Layout and design need some serious thought and consideration

## Summary

All in all - and I can't believe I'm saying this - I'm satisfied with the app in it's current state. Despite a few bugs the actual matching alogorithm works as expected with the current interface, which is all I really need from the app when I'm running Diablo 2 and have this clipped to the side of my bottom screen next to the [Pure Diablo Wiki](https://www.purediablo.com/).

> I would like to mention that the match algorithm was originally written in Python and ran on the command line and that's perfectly fine too. This was a good time to learn a new framework and practice my JavaScript skills :)

Simply download [tool](https://github.com/officialBeebe/d2-runeword-getter) somehow and follow the instructions in the README!

**Happy gaming!**
