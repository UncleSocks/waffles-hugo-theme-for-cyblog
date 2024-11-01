+++
title = 'MEEPS Security'
date = 2024-11-01T20:36:32+08:00
author = "Waffles, UncleSocks"
draft = false
type = "posts"
+++

MEEPS SECURITY is a simulation game with horror elements designed to extend cybersecurity training and awareness by playing as an L1 Security Operation Center (SOC) analyst. Players handle incoming calls regarding cybersecurity incidents, evaluating and submitting the appropriate threat to the callers within the given service level agreement (SLA). The player must correctly resolve at least 80% of tickets to pass the assessment during the shift. 

This is named after one of my chows, named Meepo (Yes, the DOTA character).

**Note:** The game is playable but still under development.

## Prerequisites

Run `pip install -r requirements.txt` to install the tool's dependencies.

### Dependencies

MEEPS SECURITY is written in Python 3 using the `PyGame` and `PyGame GUI` libraries.

## Gameplay

The main menu has three buttons: START SHIFT, CREATE TICKETS, and LOG OFF. To play MEEPS SECURITY, select the "START SHIFT" button. This will take you to the main game loop, where you play as an L1 SOC analyst. 

MEEPS SECURITY also allows players to manage the tickets, including creating custom tickets by clicking the "MANAGE TICKET" button. At the time of wiring, threat management is still under development.


The "LOG OFF" button exits the game -- you can also click on the close window button.

### Starting Your Shift

When starting your shift, you will anticipate calls from various MEEPS SECURITY clients regarding cybersecurity incidents. 
