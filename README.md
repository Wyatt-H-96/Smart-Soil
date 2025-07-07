# Smart-Soil
A indoor plant watering an monitoring IoT system.



A project built on Raspberry pi 3b+ and Qt framework. The Qt dashbard can be viewed via the pi web server. 
You can access it through any device in your web browser as long as youre on the same netwrok. 
The project can be scaled to your liking and aslo viewed anyware in the world through a VPN if youd like.


Power supply:
    Raspberry pi{
        115v AC to 5v DC switching pwer supply with usb output.
        Usb to micro usb cord.
  }
  Periphrials{
        Dual in series regulated and protected 18650 battery pack with 5v DC output.
  }

Hardware:
    ///  I KNOW I COULD USE 1 PUMP AND SOLENOIDS FOR EACH WATER LINE INSTEAD OF 3 PUMPS
    IT WAS CHEAPER THIS WAY. THE CHEAP SOLENOIDS HAVE VERY BAD REVIEWS. THE GOOD ONES WERE $20+ PER SOLENOID.
    ITS A BUDGET PROJECT.
    ///
    Raspberry pi 3 b+.
    3x Digital Water Flow Sensors.
    3x 5v submersable water pumps.
    3x 5v soil moisture sensors.
    28 AWG stranded wire.
Software:
    Custom embedded C for periphrial comminications.
    Qt framework for the dashboard using C++.
Custom components:
    3D printed pi case.
    3D printed water resevour.
    3D printed water hose and wiring conduit.
