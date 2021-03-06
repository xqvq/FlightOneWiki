# GPS

- [GPS](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Features/GPS)
    - [GPS Modules](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Features/GPS#gps-modules)
    - Connect GPS
        - [Lightning H7](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Flightcontrollers/Lightning%20H7/Connection/GPS)
        - [RevoltOSD](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Flightcontrollers/RevoltOSD/Connection/GPS)
        - [MillivoltOSD](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Flightcontrollers/MillivoltOSD/Connection/GPS)
        - [Third-Party Targets](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Flightcontrollers/Third-Party%20Targets)
            - [MAMBAF411](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Flightcontrollers/Third-Party%20Targets/MAMBAF411/Connection/GPS)
                - [MAMBA F411 AIO](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Flightcontrollers/Third-Party%20Targets/MAMABAF411/Flightcontrollers/MAMBA%20F411%20AIO/Connection/GPS)
            - [MATEKF411](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Flightcontrollers/Third-Party%20Targets/MATEKF411/Connection/GPS)
                - [Aurora RC](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Flightcontrollers/Third-Party%20Targets/MATEKF411/Flightcontrollers/AuroraRC%20F411%20AIO/Connection/GPS)
    - Enable GPS
        - [FalcoX](https://github.com/fl1wiki-mrteel/FlightOneWiki/tree/main/Features/GPS)

# Enable GPS (FalcoX)

## RTH Wizard

! This guide requires you to hover your quadcopter for 5 sec!
- You can always change the throttle percent for hover after the wizard finishes

Double check that GPS is found on a UART

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_001.JPG)

Run the "Detect GPS" Wizard

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_002.JPG)

Run the "RTH Setup Wizard"

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_003.JPG)

"Yaw Right" to continue

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_004.JPG)

Select size of prop:
- "Roll Right" for 3"-7"
- "Roll Left" for 8" or larger

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_005.JPG)

Change the RTH Altitude (feet/meter) to fit your needs (Number corresponds to your selected mesurement, Imperial/Metric)
 - "Yaw Right" for Next wizard page
 - "Yaw Left" To exit wizard

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_006.JPG)

Enable RTH on failsafe:
- "Roll Right" to enable RTH on failsafe (Default)
- "Roll Left" to disable RTH on failsafe

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_007.JPG)

Calibrate Accelerometer:
- Lay quad on flat surface and roll right

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_008.JPG)

This step requires you to hover your quadcopter, do it in a safe way.
- Battery is connected and Props on:
    - "Roll Right and Yaw Left" at the same time to confirm

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_009.JPG)

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_010.JPG)

![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/GPS_Setup_011.JPG)

## GPS Modules

TBS M8.2 </br>
![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/TBS_M8.2.JPG)
 </br>
Beitian BN-180 Micro GPS </br>
![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/BN-180.JPG)
 </br>
Beitian BN-220 Micro GPS </br>
![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/BN-220.JPG)
 </br>
Matek Systems M8Q-5883 SAM-M8Q GPS & QMC5883L Compass Module </br>
![Image](https://github.com/fl1wiki-mrteel/FlightOneWiki/blob/main/IMG/MATEKSYS-M8Q-5883.JPG)
 </br>

## External links
 
 - [FlightOne FalcoX GPS Setup & Test](https://youtu.be/XMA5rCQJrnQ)