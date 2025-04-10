!!! warning "Need Help?"
	If you need technical assistance or more information on a product that is not working as you expected, we recommend heading over to the [SparkFun Technical Assistance](https://www.sparkfun.com/technical_assistance) page for some initial troubleshooting.

	<center>
	[SparkFun Technical Assistance Page](https://www.sparkfun.com/technical_assistance){ .md-button .md-button--primary }
	</center>

	If you can't find what you need there, the [SparkFun Forums](https://forum.sparkfun.com/index.php) is a great place to search product forums and ask questions.

	!!! info "Account Registration Required"
		If this is your first visit to our forum, you'll need to create a [Forum Account](https://forum.sparkfun.com/ucp.php?mode=register) to post questions.


## Getting Started with the Arduino IDE
This guide assumes users are utilizing the latest version of the Arduino IDE on your desktop. If this is your first time using Arduino IDE, library, or board add-on, please review the following tutorials:

- [Installing the Arduino IDE](https://learn.sparkfun.com/tutorials/installing-arduino-ide)
- [Installing an Arduino Library](https://learn.sparkfun.com/tutorials/installing-an-arduino-library)
- [Installing Board Definitions in the Arduino IDE](https://learn.sparkfun.com/tutorials/installing-board-definitions-in-the-arduino-ide)



## 5V Power Limitation
We recommend users limit the load current on the `5V` output supply voltage to a maximum of ~100mA.

This should not be considered as a limitation dictated by the junction temperature of the AP3012. The limitation is driven by the power supply for the Qwiic connect system and the load being placed on the boost circuit. In order to compensate for the increased current, the supply voltage from the AP3012 boost converter will begin to drop as the current draw increases.
