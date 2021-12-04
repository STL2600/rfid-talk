% RFID
% https://github.com/STL2600/rfid-talk

# What is RFID?

- Radio-frequency identification (RFID) uses electromagnetic fields to automatically identify and track tags attached to objects.

## What is NFC?

- Near-Field Communication is a set of communication protocols that operate over RFID technologies.

# History of RFID

## Crystal Radios

![Crystal Radio][stand1.jpg]

## Crystal Radios
- Simple radio receiver that can be built with as little as 3 parts
  - Antenna
  - Tuning Coil
  - Semiconducting crystal or a diode

## The "Thing"

![The Thing][thing.jpg]

## The "Thing"

- Carved wooden plaque of the Great Seal of the United States to the US Ambassador as a “gesture of friendship” in 1945, before WWII.
- Wasn’t discovered to be a bug until 1952, seven years later.

## Identification, Friend or Foe (IFF)

![radar][radar.jpg]

## Identification, Friend or Foe (IFF)

- IFF are transponders on military aircraft to distinguish between friendly aircraft and enemy aircraft on radar.
- Would feed a signal back into a received radar signal, identifying the craft.
- Basically functioned as a radio repeater, but tweaking the signal just enough to change the radar blip.

## First RFID Tag

- Demoed at Los Alamos National Laboratory in 1973.
- Same technique is used in most RFID systems today.
- Operated at 915 MHz and could transmit 12-bits


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

- EMV Standard
- Also applies to CHIP transactions
- HF Frequency
- Range between 1 - 1.5 meters

## Payments

Highly Simplified Process Overview
- Terminal asks what the card can do
- Cryptogram containing transaction details is signed
- Cryptogram is sent to processor
- Approval sent back
- Also a bunch of diagnostic stuff

## Payments

Tokenization Method
- Updated EMV Standard
- Also used by Apple Pay and Google Pay.
- On smart phones, biometrics are used to secure keys

## Payment

Transaction overview:
- Device creates DAN and a Private Key during setup
- DAN and Private Key sent to card issuer
- Encrypted transaction details are sent to the card issuer.
- Card issuer decrypts the details and processes the transaction

## Asset Tracking

For Individual Items
- Electronic Product Codes (EPC)
- Contains URI representing the product
- EPCglobal network is a giant product database
- Used by Walmart in conjuction with UPCs
- Generally LF
- DoS-able network backend

## Asset Tracking

For Bulk Items
- Lots of commercial logistic options
- Can be LF or HF, depending on the applicaton
- Usually an active tag for longer range
- LF can be read up to 2000 meters
- HF is used with NFC when additional details are required

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


