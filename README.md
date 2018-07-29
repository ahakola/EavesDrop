# EavesDrop

## Update for BfA

Original addon: https://www.curseforge.com/wow/addons/eaves-drop

This updates the version 2.59 for BfA. Updated to support API changes BfA introduced and fixed an old bug that has been around years. Everything should work, even energy gains.

Replace `EavesDrop.lua` in your `\World of Warcraft\Interface\AddOns\EavesDrop` folder with the one provided here and you are good to go. Remember to update the first line of `EavesDrop.toc` to say `## Interface: 80000` or enable `Load out of date AddOns` ingame.

Replacing your `EavesDropStats.lua` isn't needed, but I uploaded it here because it was leaking some commonly named globals and the version here patches that.