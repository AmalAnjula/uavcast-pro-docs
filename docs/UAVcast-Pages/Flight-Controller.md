#Flight Controller
<!-- !['Flight Controller'](/images/pages/Flight-Controller/overview.jpg) -->
Configure the connection between RPI and the FC.


##Controller Type##
* Default value: `None`
* Options: `Ardupilot / Px4, Navio (Not yet supported), Navio+ (Not yet supported)`

Choose the board you want to use. for Pixhawk, APM, Cube,  select Ardupilot / Px4

   
##Connection Method##

* GPIO

!['Gpio'](/images/pages/Flight-Controller/rpi.jpg)

* USB

!['Usb'](/images/pages/Flight-Controller/rpi-usb.jpg)

##Baud rate##
* Default value: `57600`
* Options: `9600, 57600, 115200`

Select a baud rate you want to use for the telemetry stream.
