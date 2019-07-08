# SmokeHousePi
The Open Source BBQ Computer.

<img width="100%" alt="SmokeHousePi Logo" src="/art/exports/Rect2x1.svg"/>

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
| min | $54 USD |  [Raspberr Pi + Power Supply](//amzn.to/2XtNlak) | 
| min| $ 5 USD |  [Pit Probe](//www.sparkfun.com/products/13715)
| half | $6 USD | [Fire Breather](//www.sparkfun.com/products/11270) |
| full  | $27 USD | [LCD Display](//www.sparkfun.com/products/14040) |
| full  | $52 USD | [Food Probe ](www.thermoworks.com/THS-113-177) |
| full  | $50 USD | [Open Lid Sensor ](https://www.sparkfun.com/products/15244) |
| TOTAL | $59 USD + tax | Minimum Setup |
| TOTAL | $65 USD + tax |   Half Monty Setup |
| TOTAL | $194 USD + tax |  Full Monty Setup |

## One More Thing: Open BBQx

The `SmokeHousePi` will be publishing an open data standard for sharing ~~recipies~~ __cooking profiles__. SmokeHousePi users  can import and share profiles from others that make award winning slow cooked, or hot-fired BBQ. 

All this will be accomplished over the `BBQx` network.

