# Super Spacecraft Simulator 3000
Because who doesn't want a modular spaceship in Python?

## About
This is a highly sophisticated, totally realistic (not really) spaceship system where you can swap parts, power up cores, and probably cause an intergalactic disaster.

## How It Works
Uses composition (ugh) to create a dynamic spaceship with modular systems.

Features engines, shields, and a power core (with a small "oops" in the code, but shh).

Swap, activate, and definitely not explode your ship.

## Usage
```
engine = Engine()
shields = Shields()
power_core = PowerCore()  # Ignore the echoing horror in the source code.

spaceship = Spacecraft([engine, shields, power_core])
spaceship.activate_all()
```
## Features
Modular components for all your spacefaring needs.

Pluggable systems because hardcoding is for Earthlings.

Mild chaos (accidental keyboard spam included).

## To-Do
Fix the PowerCoreeeeeeeeeeee incident.

Maybe add lasers? Pew pew. Im coming for you, andre.

Implement AI so the ship can judge your piloting skills.
