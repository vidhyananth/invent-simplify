# Invent & Simplify

patents-approved

METHOD FOR DETERMINING BATTERY AVAILABLE POWER FOR AN ELECTRONIC DEVICE
-----------------------------------------------------------------------
Patent dateIssued Jan 5, 2021  Patent issuer and number US10884475B1

This patent relates to accurate calculation of battery resistance that enables better power management for portable devices. 
The battery resistance estimation is performed using a recursive updating algorithm. Once determined, 
the battery resistance is used to determine an amount of power that the battery can supply. 
When it is determined that power usage is approaching the estimated maximum available power in the battery, 
non-critical device components and functions can be disabled in order to reduce the power usage, and the user can optionally be notified. 
Power usage may also be reduced when it is determined that a time-critical task being performed by an application running on the device 
cannot be completed within an estimated remaining device runtime, and the user can optionally be notified. 
Overall this enhances the user experience and prolongs the usable battery power.

=========================================================================================

DATE-BASED COMPUTING DEVICE CHARGE MANAGEMENT
---------------------------------------------
Patent dateIssued Sep 17, 2019  Patent issuer and number US-10416753B1

This patent relates to a method to determine an optimal time to notify a user before the device reaches an inoperable state. 
For example, if a user does not charge a device for a long period of time, there is a danger that the battery may discharge to a level 
where the battery completely fails and cannot be charged again. According to the technique described in the patent, 
a current state of charge is determined and a first time period until the battery reaches a minimal/critical state of charge is calculated. 
The device/backend system informs the user of a date by which they should charge the device to avoid reaching that minimal state of charge. 
Additionally, a second time period until the battery reaches a 0V lockout state (unrecoverable state) is also calculated. 
A second notification is provided to the user to inform them of a date by which they should charge the device to avoid reaching the 0V lockout state, 
which will render the battery unrecoverable and thus make the device unusable.

===========================================================================================

EXPEDITED RESUME PROCESS FROM LOW BATTERY
-----------------------------------------
Patent dateIssued Aug 13, 2019  Patent issuer and number US-10379874

This patent relates to enabling a battery powered, electrophoretic display device (EPD), such as a Kindle, 
to allow a user to use the Kindle while charging a dead battery. By way of background, Kindles, like other E-Ink display-based devices, 
were constrained to not allow boot-up until battery power reached a certain minimum level of charge (~10%) to keep the Kindle from dying 
after begin unplugged before there was enough battery power to properly shut down and render an appropriate screen. To improve boot times and 
improve access to the Kindle while charging, this covers an approach where the Kindle loads from hibernation (instead of a full reboot) and 
displays content with a watermark or other notification indicating that the Kindle has critical battery power. 
This helps the customer understand that the device cannot be unplugged from the wall charger or, if unplugged, provides a visual indication 
as to why the device is not responding to user inputs despite displaying content. 
This is accomplished by the device saving a snapshot of memory contents/system settings when entering hibernation. 
When the device wakes up while not charging, it displays a critical battery screen and resumes hibernation. 
When the device wakes up while charging, it resumes from the snapshot and continues normal operation. 
While the battery is below the critical threshold (e.g., 10%), the device indicates that it needs to be plugged in.

===========================================================================================

DYNAMIC CURRENT DISTRIBUTION FOR PORTABLE ELECTRONIC DEVICES
------------------------------------------------------------
Patent dateIssued Jun 4, 2019  Patent issuer and numberus US10312697

This patent relates to dynamic current redistribution between an e-reader device and its auxiliary battery (e.g., Whiskey and Soda devices) 
based on whether or not the e-reader device is connected to an external power source. 
The dynamic current redistribution system implements a set of policies for each state of the e-reader device. 
Depending on the device state, the dynamic current redistribution system identifies one or more specific policies to be implemented, and 
directs current according to those policies. For example, the e-reader device may be connected to the auxiliary battery (i.e. Soda), or a wall charger or both. 
The current redistribution system will determine the charge state of the e-reader device and based on that determine how to direct power. 
For example, if the e-reader device is connected to a wall charger and the auxiliary battery, the system may direct a large portion of current, 
from the available current, to the battery via the e-reader device depending on the battery's charge level. 
This ensures the most efficient use of available charging energy for optimal operation of the device.

===========================================================================================

SYSTEMS AND METHODS FOR DYNAMIC CONFIGURATION AND CONTROL OF BUS INTERFACE
--------------------------------------------------------------------------
Patent dateIssued May 21, 2019  Patent issuer and number US 10298028

This patent relates to dynamic configuration and control of I2C (inter IC) bus interface between a Whiskey and Soda device. 
The serial data line (SDA) of the I2C interface is configured such that it can detect an interrupt as well as operate in a data mode. 
In the interrupt mode, the Whiskey device is able to detect when the Soda is connected to the Whiskey device based on a specific data being received over the I2C bus interface. 
In a data operation mode, the Whiskey device is able to communicate battery charge and other control data to and from the Soda device over the same I2C interface. 
This dual use of the SDA line of the I2C bus enables reduction in the number of the pins on the connector connecting the Whiskey and Soda device from five to four. 
In an alternative embodiment, the serial clock line (SCL) can also be configured in a similar fashion. This reduces the cost of the device and increases reliability.

===========================================================================================

SMART DIAGNOSTICS FOR HOT-PLUGGABLE BATTERY SYSTEMS
---------------------------------------------------
Patent dateIssued May 7, 2019  Patent issuer and number US-10283975

This patent relates to a modular charging system, such as that used by the original Kindle Oasis or a smartphone, 
where a device containing an internal battery performs diagnostics on an external battery pack, such as that in a charging case. 
The diagnostics include determining whether the battery pack is dead, low on power, broken, or otherwise invalid/unauthorized for use with the device.
The device can also determine whether there is a mechanical fault in the electrical connection between the device and the battery pack. 
Only after determining the battery pack is operational and authorized will the battery be charged from the external battery pack.

===========================================================================================

DYNAMIC POWER OPTIMIZATION WHEN TRANSFERRING POWER BETWEEN BATTERIES
--------------------------------------------------------------------
Patent dateIssued Nov 27, 2018  Patent issuer and number US-10141756

This patent relates to a modular charging system where a larger battery is used to charge a smaller battery, 
such as that implemented by Kindle Oasis and it's battery cover. The device having the smaller battery manages the charge cycle 
based on threshold levels to preserve the life of the larger battery and increase efficiency. The device uses a state machine and 
selectively ignores threshold transition signals, allowing the device to maintain a low-power state until an event occurs that necessitates changing states. 
A hardware interrupt that indicates a first battery is below a certain charge level can also cause the device to mask further such interrupts 
until the first battery is sufficiently charged, thus preventing regular interruptions resulting from the low battery level.

===========================================================================================

QUICK BOOT FROM HALT BY HALL SENSOR SMART COVER
-----------------------------------------------
Patent dateIssued May 15, 2018  Patent issuer and number US-9971608-B1

This patent relates to smart covers for tablets and e-reader devices that can be used to save battery consumption 
by automatically causing a device to enter a hibernate or suspend mode when the cover is closed over the device display. 
When the cover is opened, the device is woken up. The covers can be customized so that a device won't enter a suspend or hibernate state until the cover has been closed for a user-specific length of time. The device state information and other configuration parameters are stored in the memory for quick boot-up from the sleep state.

===========================================================================================

Adaptive Battery Management
---------------------------
Patent dateIssued Feb 13, 2018  Patent issuer and number US9892691-B1

Systems and methods are provided for optimizing battery life in an electronic device. 
The device is configured to make periodic assessments of battery capacity by measuring the DC resistance value of the battery cell 
during the execution of a power-consuming operation. If the measured DC resistance value reaches a threshold level, 
the device can initiate a power-saving mode in which an operating parameter of the device is adjusted to decrease power consumption.

===========================================================================================

LOW CAPACITY, LOW AREA-SPECIFIC RESISTANCE BATTERY CELL FOR ELECTRONIC DEVICES
------------------------------------------------------------------------------
Patent dateIssued Dec 5, 2017  Patent issuer and number US-9837681

The patent relates to a small capacity battery cell with a low DC resistance area-specific resistance (ASR). 
Utilizing batteries having a DC resistance ASR less than or equal to about 55 Ohm-cm^2 measured at 0.5A, 23°C +/- 2°C for a 50 msec pulse at 4.0V 
open circuit voltage or less than 85% state-of-charge can provide improved battery life, particular when the device experiences periodic spikes in high current draw. 
Conventional small capacity batteries perform poorly during such spikes, which tends to cause such batteries to shut down prematurely.

===========================================================================================

EVENT-BASED TRIGGER FOR MANAGING BATTERY CONSUMPTION
----------------------------------------------------
Patent dateIssued Dec 5, 2017  Patent issuer and numberus 9,836,114

Patent descriptionThe patent relates to power management techniques for e-reader devices. 
When the e-reader executes a power-consuming operation (e.g., a page turn), an average current load and average voltage drop is 
measured during the execution of the power-consuming operation. The average current load and average voltage drop are used to calculate a 
DC resistance of the battery cell. If the calculated DC resistance is above a threshold DC resistance value indicating a low power condition of the battery, 
a power-saving mode is initiated (e.g., a brightness of the display is decreased or a transmission power of the e-book reader is reduced). 
Operations that produce a consistent power load signature, such as page turn operations, are particularly well-suited for this type of monitoring.

===========================================================================================

DYNAMIC CURRENT REDISTRIBUTION FOR PORTABLE ELECTRONIC DEVICES
--------------------------------------------------------------
Patent dateIssued Nov 7, 2017  Patent issuer and numberus 9,812,878

This patent relates to maximizing current draw from charging adapters so as to minimize the amount of time needed to charge device batteries. 
Users may use multiple types of wall adapters to charge their devices. However, different wall adapters have different charging capabilities. 
Often times, wall adapters may be able to provide more current than what is being drawn. Using the technology described in this patent, 
the maximum current a wall adapter can provide is supplied to devices, such that the device batteries can be charged as fast as possible, 
resulting in an improved user experience.

===========================================================================================

SELECTIVE POWERING OFF OF HARDWARE COMPONENTS FOR BATTERY MANAGEMENT IN MOBILE DEVICES
--------------------------------------------------------------------------------------
Patent dateIssued Apr 11, 2017  Patent issuer and numberus Patent # 9,619,010

A processing device of a mobile device determines an activity level for a hardware component of the mobile device based on 
activity information associated with the hardware component. The processing device computes a score for the hardware component 
based on the activity level and a power consumption value of the hardware component, wherein the power consumption value indicates 
an amount of power used by the hardware component. The processing device determines whether to deactivate the hardware component based on the score.

===========================================================================================

Unique Event Identification
---------------------------
Patent dateIssued Jan 13, 2015  Patent issuer and number US8,935,710

Embodiments of methods, systems and storage medium associated with generating and storing a unique event identifier (UEID) associated with a 
type of an event of a module of a computing system are disclosed herein. Specifically, a centralized UEID storage may include one or more event nodes 
configured to associate a UEID with a type of an event handled by or occurring at an owner module. 
The centralized UEID storage may be further configured to associate, using the UEID, 
the type of the event with one or more callback functions of one or more client modules. 
Upon occurrence of the type of the event, the callback functions may be identified and invoked using the UEID.

===========================================================================================

System and Method for Photo-Image Discovery and Storage
-------------------------------------------------------
Patent dateIssued Nov 4, 2010  Patent issuer and number US20100277597 A1

A system and method are provided for automatic photo-image discovery and storage. 
A photo-image discovery device scans communication interfaces for photo-capable devices. 
The photo-image discovery device is capable of concurrently scanning wireless and hardwired connector interfaces. 
A determination is made of whether the detected photo-capable devices have stored electronically formatted photo-images, 
which may be either still or video images. The photo-images are acquired into the photo-image discovery device. 
Then, the acquired photo-images are automatically uploaded to a network-connected storage site.

===========================================================================================

System and Method for Virtual Kiosk Stored Photo-image Reproduction
-------------------------------------------------------------------
Patent dateIssued Nov 4, 2010  Patent issuer and number US20100281424 A1

A virtual kiosk system and method are provided for stored photo-image reproduction. 
A photo-image discovery device, having no dedicated display, scans communication interfaces for photo-capable devices, and 
determines if detected photo-capable devices have stored electronically formatted photo-images. 
The photo-images are acquired into the photo-image discovery device, and the acquired photo-images are uploaded to a network-connected storage site. 
Subsequently, the photo discovery device may be interfaced to a display monitor. 
A menu of photo-image user prompt options is depicted on the display monitor, originating from the photo discovery device. 
The storage site is accessed from the photo discovery device in response to a first user prompt. 
In response to a second user prompt, a stored photo-image is selected. 
In one aspect a delivery option for the selected photo-image is selected in response to an additional user prompt.

===========================================================================================

