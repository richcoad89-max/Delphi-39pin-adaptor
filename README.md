# Delphi-39pin-adaptor
Adapt the 40pin IDE to a 39pin Delphi / FCI / SICMA 1.5

Setup as follows;

Speedy Pin #	Function	Function	Special notes	FCI pin
5	Injector 4 - Pin 1/2	Inj 4	1mm trace	A1
9	Ground	Ground Injectors	1mm trace	A2
11	MAP Sensor (0v-5v)	Not used	0.3mm trace	A3
15	 Fan	Fan relay	0.4mm trace	A4
17	 Tachometer		0.3mm trace	A5
19	Coolant (CLT)		0.3mm trace	A6
	Spare			A7
	Spare			A8
	Spare			A9
	Spare			A10
27	Crank Input / VR1- 	Crank Signal VR-	0.4mm trace	A11
	12v+			A12
	12v+			A13
3	Injector 3 - Pin 1/2	Inj 3	1mm trace	B1
2	Injector 2 - Pin 1/2	Inj 2	1mm trace	B2
7	Ignition 1	Ign 1	0.5mm trace	B3
13	5v	5v for relay	0.3mm trace	B4
	Spare			B5
16	Fuel Pump	Fuel pump relay	0.4mm trace	B6
20	Inlet Air Temp (IAT)		0.4mm trace	B7
24	Cam Input / VR2+	Cam signal	0.4mm trace	B8
34	Ignition 2	Ign 2	0.5mm trace	B9
38	VVT	Ign 4	0.5mm trace	B10
35	Boost	Boost solonoid	0.3mm trace	B11
21	O2 Sensor	PLX AFR	0.2mm trace	B12
	Ground			B13
1	Injector 1 - Pin 1/2	Inj 1	1mm trace	C1
4	Injector 3 - Pin 2/2	Inj 5	1mm trace	C2
8	Ignition 4	Ign 3	0.5mm trace	C3
	Spare			C4
14	Flex Sensor		0.4mm trace	C5
18	Clutch		0.4mm trace	C6
22	TPS input		0.4mm trace	C7
26	Cam Input / VR2-		0.4mm trace	C8
36	Idle 2 (For use with 3 wire idle valves)	IAC Close	1mm trace	C9
37	PWM Idle	IAC Open	1mm trace	C10
33	Ignition 3	Ign 5	0.5mm trace	C11
25	Crank Input / VR1+	Crank Signal VR+	0.4mm trace	C12
	Ground			C13
6	Injector 4 - Pin 2/2		1mm trace	Pad
10	Ground		Ground plane	
12	Ground		Ground plane	
23	Ground		Ground plane	
28	5v		0.2mm trace	Pad
29	Idle Stepper 2B		0.4mm trace	Pad
30	Idle Stepper 2A		0.4mm trace	Pad
31	Idle Stepper 1A		0.4mm trace	Pad
32	Idle Stepper 1B		0.4mm trace	Pad
39	Injector 2 - Pin 2/2		0.6mm trace	Pad
40	Injector 1 - Pin 2/2		0.6mm trace	Pad
<img width="923" height="1275" alt="image" src="https://github.com/user-attachments/assets/75486b69-695b-477f-88ee-5a052d934cb4" />

Uses following hardware;

Delphi 39pin FCI male
Keystone 3568 mini blade fuseholder
JWT 1x02 header for power/ground pins
PinSocket 2x20 P2.54mm 

Options to configure less commonly used functions such as stepper, secondary injector circuits or use spare pins of Delphi connector with specific through holes to solder to, keeping the design clean.
