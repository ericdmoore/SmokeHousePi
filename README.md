# SmokeHousePi
The Open Source BBQ Computer.

<img width="100%" alt="SmokeHousePi Logo" src="/art/exports/Rect2x1.svg"/>

## Introduction

Living in Texas, perhaps it goes with out saying that I <3 BBQ. I love eating it, smelling it, making it, the sides that accompany, I love the labor of love that goes into it all (well kinda).

For me great BBQ often falls into category of things in life where its better to have a friend who is way into it than doing it yourself (think boats, beach homes, and plenty other pinkies-out possessions) its so demanding to do-it-yourself. And as the owner of a BigGreenEgg I want to like it. I really do. However, once you break down and by some type of BBQ compauter... you realize that these things are "not desgined by Apple" to say the least...

I get it. BBQ is a time consuming art that is learned over time, but cmon its the 21st century and this seems like a pretty basic task. Thus as a way of taking [Atwood's Law](//blog.codinghorror.com/the-principle-of-least-power/) to extremes - I bring you `SmokeHousePi`

## BYO Hardware

### Required Minimum

1. [Raspbery Pi + Wifi Connection + Power Supply](//amzn.to/2XtNlak)
2. [High Temp Pit Temp Sensor](//www.sparkfun.com/products/13715)
3. Bring Your Own smoker/fire cooker
    - Examples: will be down with a Komodo/BigGreenEgg-style cooker, but webber-style dome grills are simple to retrofit too.
    - Offset Smoker rigs are possible to automate (stay tuned for equipment recommendations)

### Optional But Helpful

1. [Variable Speed Cage Fan](//www.sparkfun.com/products/11270)
1. Top Vent Spin Controller (Work in Progress)
1. Top Vent Position Controller (Work in Progress)

## Inputs

### Sensors

1. [Pit temp](//www.sparkfun.com/products/13715)
2. [Meat temp](//www.thermoworks.com/THS-113-177)
3. [Lid open](https://www.sparkfun.com/products/15244)
5. Smoke type/quality Imaging (Work In Progress)
4. Meat Picture Upload

## Outputs

### Possible Actuators
- Top vent control % (Work in Progress)
- Top vent position % (Work in Progress)
- [Variable Speed Cage Fan](//www.sparkfun.com/products/11270)


### Possible Displays

[LCD Display](//www.sparkfun.com/products/14040)

Toggle Through:
- IP address
- pit: Current Temp
- Food: Current temp
- Time Chart of Pit Temp vs Food Temp
```
320
|           _____
|   __     /     \    ___ 302
| -/  \___/       \__/
|
280 _________________________
```

### Local Application (Coming Soon)
0. Home WiFi setup with web app via rpi 
1. Monitor BBQ Pit Temp from anywhere on your own Wifi Network

### Global Application (Coming Soon Too)

1. User Notifications for intervention
1. Set temp profile (initial support for only flat-liners)
1. Monitor Variance from anywhere
1. Create Recipies
1. Record actual and target timeseries temperature data (annotated user events)


## Bill of Materials:
| Setup | Price |   Item |
| ---- |-------|-------------|
| min | $55 USD |  [Raspberr Pi + Power Supply](//amzn.to/2XtNlak) | 
| min| $ 5 USD |  [Pit Probe](//www.sparkfun.com/products/13715) | 
| half | $22 USD |  [Weather Proof Case](//amzn.to/2JlQ2H1) | 
| half | $6 USD | [Fire Breather Fan/Blower](//www.sparkfun.com/products/11270) |
| full  | $27 USD | [LCD Display](//www.sparkfun.com/products/14040) |
| full  | $52 USD | [Food Probe ](www.thermoworks.com/THS-113-177) |
| full  | $50 USD | [Open Lid Sensor ](https://www.sparkfun.com/products/15244) |
| TOTAL | $60 USD + tax | Minimum Setup |
| TOTAL | $88 USD + tax |   Half Monty Setup |
| TOTAL | $217 USD + tax |  Full Monty Setup |

But perhaps you have a raspbery Pi laying around, not doing much - give it a new smokey purpose: **fire box duty!**

At around $5 to get started, or less than $30 for a pretty nice setup,isn't that worth a try to see what kind of smoke ring you can get on your brisket for $30?

## One More Thing: OpenBBQ.org

The `SmokeHousePi` will be publishing an open data standard for sharing ~~recipies~~ __cooking profiles__. SmokeHousePi users  can import and share profiles from others that make award winning slow cooked, or hot-fired BBQ. 

All this will be accomplished over the `OpenBBQ.org` network (Coming Sooon)
