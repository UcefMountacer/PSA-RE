# Reverse engineering of PSA architectures

## Intro

This project is an effort to reverse engineer and document most of the architectures used in PSA (Peugeot/Citroen/DS) cars.
The goal is to enable anybody to explore their own cars and create cool DIY ECUs and tools.

## Cars covered by this project

All cars using the AEE2001 (VAN architecture), AEE2004 (first "FullCAN" architecture) and AEE2010 (current gen architecture), in theory all cars from the 1993 citroen XM (first car to use VAN) to the latest Peugeot, Citroen and DS cars should be covered.

## Ressources

* This repository contains yaml files using the [DBMUXE format](https://github.com/prototux/PSA-RE/tree/master/dbmuxev/doc) as well as proof of concept code
* The [issues](https://git.prototux.net/reverse-engineering/psa/canbus/-/issues) contains the current work in progress on specific can/van/diag frames
* The [wiki](https://github.com/prototux/PSA-RE/wiki) contains most of the information that isn't description of specific frames

## Contribute

If you have informations that aren't documented yet, please open an issue!
There's a channel open to dicuss the project on discord: psa-can-re @ [the nerds lair](https://discord.gg/uPykZ5W)

## Warning

This project is (of course!) non-official, an thus, informations here may be incorrect (even if we try to avoid this)  
Any modification you may do to your car, even based on the documentation from here, is your sole responsibility!  
Similarely, we didn't got any reaction from PSA (nor know their position about FOSS projects), we cannot say if they may or not DMCA takedown your project  
This project uses a mix of english and french, be prepared to use a translation tool if you don't speak both languages (and the jargon in both!)  
The reason for this is that we tend to work in english, but are native french, and PSA works using french internally, so we adapt to their jargon

## Thanks

* Wouter Bokslag for his awesome work on the [reverse engineering of the immobilizer](https://fahrplan.events.ccc.de/congress/2019/Fahrplan/events/11020.html)
* Alexandre Blin for his [tools](https://github.com/alexandreblin?tab=repositories), work on his 207 and for being a huge inspiration for this
* Peter Pinter for his huge work on his own [FullCAN to VAN bridge](https://github.com/morcibacsi?tab=repositories)
* All the people who leaked parts of PSA's designs all over the internet :)
