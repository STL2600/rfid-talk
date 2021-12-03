% RFID
% https://github.com/STL2600/rfid-talk

# Intro / History

# Basic Tech

## Tag / Reader Types

## Active Reader - Passive Tag

 - By far the most common type of system
 - Uses a powered reader and an unpowered transponder

## Active Reader - Active Tag

 - Both the reader and the tag are powered
 - Reader sends out a signal and transponder responds

## Passive Reader - Active Tag

 - The reader does not transmit and only listens
 - Transponders continually emit ID signals

## Inductive Coupling

 - Used for passive tags
 - The reader and the transponder both have coils of wire (inductors)
 - A current in one coil induces a current in the other
 - By varying the load on the transponder coil, the two can communicate

## Frequencies

## Low Frequency - 120-150 kHz

 - Mostly used for access control, IDs, etc.

## High Frequency - 13.56 MHz

 - Most NFC tags you’d see for things like automation
 - Most payment systems

## Ultra High Frequency - 433 MHz, 865-868 MHz, 902-928 MHz

 - Active trackers for automotive and military uses
 - Bluetooth / WiFi spectrum devices

# Use Cases

## Access Control

 - Active Reader / Passive Tag 
 - 120-150 kHz
 - Most cards are read only
 - Range of 10cm under most conditions

## Access Control

 - HID Cards (AR Uses These)
 - Use the Wiegand Interface
 - Security is based on difficulty of reading

## Payments

## Asset Tracking

## Road / Bridge Tolling

 - Active Reader / Active Tag
 - 915 Mhz
 - Almost all systems are technically the same as E-ZPass
 - Range of 100m

## Road / Bridge Tolling

 - Some systems have switches for additional info (HOV, Ride Share, etc.)
 - Pseudo-anonymous ID which is consistent, so can be used for tracking

## Animal Tracking

 - Active Reader and Active or Passive Tags
 - 120-150 kHz

## Passports

## Cyborgs

# Demos

## Home Automation

## Proxmark


