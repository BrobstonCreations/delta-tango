# Delta Tango

This project contains most everything needed to 3D print, assemble, and flash an ESPHome Delta T monitoring tool. This measures the temperature difference between HVAC return air and supply air. 

![PXL_20220904_192132391~2](https://user-images.githubusercontent.com/4724577/188345113-22dde111-477e-4e54-903d-98896514ac9e.jpg)

## Getting Started
1. Electronics:
    - Components (below are some Amazon Affiliate links, they help me support this project at no cost to you):
        - [D1 Mini ESP8266](https://amzn.to/3AmQJJu)
        - [D1 Mini DC Power Shield](https://amzn.to/3AiCEwD)
        - DS18B20 Temperature Sensor Probes
        - Power Source Options:
            - [AC Adapter](https://amzn.to/3Ctc5ri)
            - Centralized Power Supply Components (consult an electrician if needed) (eventually I'll put out an STL for an enclosure for the Power Supply):
                - [DC 24V15A 360W Switching Power Supply](https://amzn.to/3Am2Er9)
                - [Power Supply Fused Power Injection Board](https://www.holidaycoro.com/product-p/1308.htm) (needs testing)
                - [IEC Fused Power Socket and Switch](https://amzn.to/3chQffL)
                - [IEC Power Cable 5ft](https://amzn.to/3pHTsZc)
                - Fork spade crimp terminals, fully insulated female spade terminal, and some stranded wire for load/neutral/ground between the IEC Socket and the Power Supply.
                - [Wiring to run through duct work](https://github.com/TonyBrobston/yet-another-smart-vent/issues/7#issuecomment-1221660336).
            - [Battery Pack](https://amzn.to/3AHrQd2) (not currently recommended, needs development for power saving mode).
    - [Assembly Instructions](/docs/ELECTRONICS_ASSEMBLY.md)
2. 3D Printing:
    - [Printing Advice](/docs/PRINTING_ADVICE.md)
    - [STLs](https://www.printables.com/social/337332-tonyb/collections/241144?o=download_count):
        - [Delta Tango](https://www.printables.com/model/271418)
    - [Assembly Instructions](/docs/PRINT_ASSEMBLY.md)
3. [Compile and Upload Instructions](/docs/COMPILE_AND_UPLOAD.md)
4. [Setup](/docs/SETUP.md)
5. [Testing](/docs/TESTING.md)
6. [Implementation Options](/docs/IMPLEMENTATION_OPTIONS.md)

## Philosophy
- Local Control
- External Integration
- Easy of Use
- Community Feedback
- Community Contributions
- Agile, Lean, and Extreme Programming Practices
- Mostly Decentralized Manufacturing.

## Pull Requests
Pull Requests are always welcome. I would recommend starting with an [issue](https://github.com/TonyBrobston/delta-tango/issues), so that we can discuss viability and implementation.

## Issues
Feel free to open an [issue](https://github.com/TonyBrobston/delta-tango/issues) and I will respond as I have time. The hope is to create a system that gives consumers what they want, your feedback is important. 
