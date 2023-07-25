# ESPHome Smart Curtains

Using an ESP32, a stepper motor and driver, ESPHome, and Home Assistant, I created a set of completely do it yourself smart curtains. This was based on existing smart curtain projects such as those done by Everything Smart Home on YouTube. This DIY method proved to be much less expensive than commercial options for smart curtains, which range from $90 - $250.

These curtains are one of my favorite DIY projects as there are very few good commercial alternatives and are so convenient:

-   Opens automatically in the morning.
-   Closes at night when I go to sleep.
-   Closes when I turn on home theater mode in my living room.

## Prerequisite Software

This project uses [ESPHome](https://esphome.io/index.html) hosted on [Home Assistant](https://www.home-assistant.io/). I highly recommend both for controlling your smart home and DIY projects. Home Assistant gives you full local control over your smart devices, and ESPHome makes creating DIY smart devices super easy.

## Parts and Tools

While you don't have to use these exact ones, these are the ones I used:

-   [NEMA 17 Stepper Motors](https://www.amazon.com/gp/product/B0B38H2ZMR/)
-   [Stepper Motor Mounting Brackets](https://www.amazon.com/gp/product/B092ZSF899/)
-   [TMC2209 Stepper Motor Drivers](https://www.amazon.com/gp/product/B08M9J8SB7/)
-   [GT2 Timing Belt Kit](https://www.amazon.com/gp/product/B08SMFM3Z6/)
-   [ESP32 Development Boards](https://www.amazon.com/gp/product/B086MGH7JV/) - any should work, this listing says ESP-WROOM-32 but they're actually copies of the DOIT ESP32 DevKit V1
-   [Breadboards](https://www.amazon.com/gp/product/B07LFD4LT6/) - for prototyping
-   [Protoboards](https://www.amazon.com/gp/product/B07ZYPCXZ3) - for the finished circuit
-   [Project Boxes](https://www.amazon.com/gp/product/B07G8S6XLV/) - for protecting the finished circuit
-   [Power Supplies](https://www.amazon.com/gp/product/B086JLYBQ7) - the stepper motors I used require at least 12V and 1.5A
-   [DC to DC Buck Converters](https://www.amazon.com/gp/product/B08Q3TKJH5/) - much better and safer than voltage regulators
-   [Various](https://www.amazon.com/gp/product/B07PBQXQNQ/) [Capacitors](https://www.amazon.com/gp/product/B07117K2ND/) - either should work
-   [Blackout Curtains](https://www.amazon.com/gp/product/B07RZBRQDQ/) - grommets allow it to easily slide along the curtain rod
-   [Curtain Rods](https://www.amazon.com/gp/product/B07D5CMLF7/)
-   [Kevlar Cord](https://www.amazon.com/gp/product/B082VWRZXP/) - the stronger the better here
-   [Super Glue](https://www.amazon.com/gp/product/B000LGPD64/)
-   [Screws](https://www.lowes.com/pd/Fas-n-Tite-8-x-3-in-Bugle-Coarse-Thread-Drywall-Screws-1-lb/999996464) - for study mounting everything
-   A drill or impact driver, screw driver, and stud finder

## Circuit Diagram

TODO

## Completed Circuit

<img src="SmartCurtainCircuit.jpg" alt="ESP32 Stepper Motor Driver Circuit" width=500/>
