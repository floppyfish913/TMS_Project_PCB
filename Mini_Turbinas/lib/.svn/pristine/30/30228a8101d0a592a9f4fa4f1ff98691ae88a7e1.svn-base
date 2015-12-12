This project is collected the Thor group Altium sch and pcb libraries.

Editing style of the schematic component:

Designator:
	resistor - R
	capacitor - C
	inductor - L
	connector - J
	integrated circuit - U
	transistor - Q
	diode - D


Add this lines to the parameter list:

	Distributor: Lomex/Digikey/Farnell/TME/etc.
	Order ID: order code/designator of the appropriate distributor
	Price: Price must be hungarian forint. If the price is given in USD,EUR etc, it must convert to hungarion forint with that day's exchange rate. 
		It is not necessary to keep the price up to date because it is just an informal value, but correct it if the difference is significant.
	Value: examples below

Schematic component editing examples:

	resistor:
		Value: 3R60 1% (0.125W optional if the information is important) 
		
		description: 3R60 0603 1% CR-03FL7---3R6 0.1W (TCL) [80-15-94] (full description of the part)

	capacitor:
		value: 1uF 25V (1% X5R optional if the information is important)
		
		description: 1uF 0603 10% 25V X5R CL10A105KA8NNNC (SAM) [82-07-86] (full description of the part)

	inductor:
		value: 150uH 1.5A (DC resistance etc.. optional)

		description: MULTICOMP - MCBF7330-151MU - INDUCTOR, 150UH, 20%, SMD

	connector:
		value: NCW396-03R

		description: TÁPCSATL. 3.96mm 3P APA 90° NCW396-03R (G-S) [43-12-67] (full description of the part)

	integrated circuit:
		value:	ATxmega32A4-AU

		description: ATMEL - ATXMEGA32A4-AU - MCU, 8/16BIT, XMEGA, 32K FLASH, 44TQFP  (full description of the part)

	transistor:
		value: TSM2307CX

		description: TAIWAN SEMICONDUCTOR - TSM2307CX - MOSFET,P CH,30V,3A,SOT23  (full description of the part)

	diod:
		value: SK24A (forward/zener voltage optional, current optional)
		
		dascription: 2A 40V DO-214AC SCH.RECT. SK24A (TSC) SMA [83-01-18] (full description of the part)


Editing style of the pcb component:
	Name:	Must be a standard well known name. F.e.: 0603...

	Height:	Improtant information by pcb design.

	Description: Write some usefull information f.e.: power footprint read datasheet etc.




passive.schlib
	resistor
	capacitor
	inductor

connector.schlib
	connector
	
misc.schlib
	fuse
	crystal
	switch
	push button

active.schlib
	transistor
	diod
	led

ic.schlib
	microcontroller
	comparator
	op amp
	voltage reference
	fpga
	cpld
	regulator
	switching power
	level converter
	communication bridge
	all integrated circuit


footprints:

passive.pcblib
	resistor
	capacitor
	inductor

connector_misc.pcblib
	connector	
	fuse
	crystal
	switch
	push button

active_ic.pcblib
	transistor
	diod
	led
	microcontroller
	comparator
	op amp
	voltage reference
	fpga
	cpld
	regulator
	switching power
	level converter
	communication bridge
	all integrated circuit


