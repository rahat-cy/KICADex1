EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Device:R 33k1
U 1 1 6154788B
P 4250 4250
F 0 "33k1" H 4320 4296 50  0000 L CNN
F 1 "R" H 5850 4400 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P1.90mm_Vertical" V 4180 4250 50  0001 C CNN
F 3 "~" H 4250 4250 50  0001 C CNN
	1    4250 4250
	0    -1   -1   0   
$EndComp
$Comp
L Device:Thermistor TH1
U 1 1 61548050
P 2650 2300
F 0 "TH1" H 2755 2346 50  0000 L CNN
F 1 "5k" H 2755 2255 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P1.90mm_Vertical" H 2650 2300 50  0001 C CNN
F 3 "~" H 2650 2300 50  0001 C CNN
	1    2650 2300
	1    0    0    -1  
$EndComp
$Comp
L pspice:CAP C1
U 1 1 6154A6CB
P 3550 5350
F 0 "C1" H 3728 5396 50  0000 L CNN
F 1 "10uF" H 3728 5305 50  0000 L CNN
F 2 "Capacitor_THT:CP_Axial_L11.0mm_D8.0mm_P15.00mm_Horizontal" H 3550 5350 50  0001 C CNN
F 3 "~" H 3550 5350 50  0001 C CNN
	1    3550 5350
	1    0    0    -1  
$EndComp
$Comp
L Device:Buzzer BZ1
U 1 1 6154B37D
P 5400 2550
F 0 "BZ1" H 5552 2579 50  0000 L CNN
F 1 "Buzzer" H 5552 2488 50  0000 L CNN
F 2 "Buzzer_Beeper:Buzzer_Mallory_AST1109MLTRQ" V 5375 2650 50  0001 C CNN
F 3 "~" V 5375 2650 50  0001 C CNN
	1    5400 2550
	1    0    0    -1  
$EndComp
$Comp
L Transistor_BJT:2N2219 Q1
U 1 1 6154BA71
P 5450 4200
F 0 "Q1" H 5640 4246 50  0000 L CNN
F 1 "2N2219" H 5640 4155 50  0000 L CNN
F 2 "Package_TO_SOT_THT:TO-92L" H 5650 4125 50  0001 L CIN
F 3 "http://www.onsemi.com/pub_link/Collateral/2N2219-D.PDF" H 5450 4200 50  0001 L CNN
	1    5450 4200
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x03_Male J1
U 1 1 6154F096
P 900 4200
F 0 "J1" H 1008 4481 50  0000 C CNN
F 1 "Conn_01x03_Male" H 1008 4390 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x03_P2.54mm_Vertical" H 900 4200 50  0001 C CNN
F 3 "~" H 900 4200 50  0001 C CNN
	1    900  4200
	1    0    0    -1  
$EndComp
Wire Wire Line
	1100 4100 1600 4100
Wire Wire Line
	1600 4100 1600 1550
Wire Wire Line
	1600 1550 2650 1550
Wire Wire Line
	5200 1550 5200 2450
Wire Wire Line
	5200 2450 5300 2450
Wire Wire Line
	2650 2100 2650 1550
Connection ~ 2650 1550
Wire Wire Line
	2650 1550 5200 1550
Wire Wire Line
	5300 2650 5000 2650
Wire Wire Line
	5000 2650 5000 3800
Wire Wire Line
	5000 3800 5550 3800
Wire Wire Line
	5550 3800 5550 4000
Wire Wire Line
	1150 4200 2050 4200
Wire Wire Line
	2050 4200 2050 6000
Wire Wire Line
	2050 6000 3550 6000
Wire Wire Line
	5550 6000 5550 4400
Wire Wire Line
	3550 5600 3550 6000
Connection ~ 3550 6000
Wire Wire Line
	3550 6000 5550 6000
Wire Wire Line
	5250 4200 4550 4200
Wire Wire Line
	4550 4200 4550 4250
Wire Wire Line
	4550 4250 4400 4250
$Comp
L Simulation_SPICE:DIODE D1
U 1 1 6157F271
P 3350 4250
F 0 "D1" H 3350 4467 50  0000 C CNN
F 1 "1N4007" H 3350 4376 50  0000 C CNN
F 2 "Diode_THT:D_5KP_P7.62mm_Vertical_AnodeUp" H 3350 4250 50  0001 C CNN
F 3 "~" H 3350 4250 50  0001 C CNN
F 4 "Y" H 3350 4250 50  0001 L CNN "Spice_Netlist_Enabled"
F 5 "D" H 3350 4250 50  0001 L CNN "Spice_Primitive"
	1    3350 4250
	1    0    0    -1  
$EndComp
Wire Wire Line
	3500 4250 3850 4250
Wire Wire Line
	2650 4250 3200 4250
Wire Wire Line
	2650 2450 2650 2500
Connection ~ 2650 2500
Wire Wire Line
	2650 2500 2650 4250
Wire Wire Line
	3850 4250 3850 5100
Wire Wire Line
	3550 5100 3850 5100
Connection ~ 3850 4250
Wire Wire Line
	3850 4250 4100 4250
$EndSCHEMATC
