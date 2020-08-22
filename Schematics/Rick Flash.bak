EESchema Schematic File Version 4
LIBS:Rick Flash-cache
EELAYER 29 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "Rick Flash"
Date "2020-08-21"
Rev " 1.1"
Comp "Rectified Tech"
Comment1 "Added via to fix ground plane disconnect"
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L Connector_Generic:Conn_02x38_Odd_Even J1
U 1 1 5EE342B8
P 10500 4350
F 0 "J1" H 10550 2225 50  0000 C CNN
F 1 "M.2 Edge Connector" H 10550 2316 50  0000 C CNN
F 2 "Custom Footprints:NGFF_B+M" H 10500 4350 50  0001 C CNN
F 3 "~" H 10500 4350 50  0001 C CNN
	1    10500 4350
	-1   0    0    1   
$EndComp
$Comp
L power:+3.3V #PWR01
U 1 1 5EE41DD0
P 7650 2400
F 0 "#PWR01" H 7650 2250 50  0001 C CNN
F 1 "+3.3V" H 7665 2573 50  0000 C CNN
F 2 "" H 7650 2400 50  0001 C CNN
F 3 "" H 7650 2400 50  0001 C CNN
	1    7650 2400
	1    0    0    -1  
$EndComp
$Comp
L power:+3.3V #PWR03
U 1 1 5EE426D9
P 9900 2450
F 0 "#PWR03" H 9900 2300 50  0001 C CNN
F 1 "+3.3V" H 9915 2623 50  0000 C CNN
F 2 "" H 9900 2450 50  0001 C CNN
F 3 "" H 9900 2450 50  0001 C CNN
	1    9900 2450
	1    0    0    -1  
$EndComp
Wire Wire Line
	10200 2750 9900 2750
Wire Wire Line
	9900 2750 9900 2650
Wire Wire Line
	10200 2650 9900 2650
Connection ~ 9900 2650
Wire Wire Line
	9900 2650 9900 2550
Wire Wire Line
	10200 2550 9900 2550
Connection ~ 9900 2550
Wire Wire Line
	9900 2550 9900 2450
$Comp
L power:GND #PWR04
U 1 1 5EE437C0
P 10950 2800
F 0 "#PWR04" H 10950 2550 50  0001 C CNN
F 1 "GND" H 10955 2627 50  0000 C CNN
F 2 "" H 10950 2800 50  0001 C CNN
F 3 "" H 10950 2800 50  0001 C CNN
	1    10950 2800
	1    0    0    -1  
$EndComp
Wire Wire Line
	10700 2650 10950 2650
Wire Wire Line
	10950 2650 10950 2800
$Comp
L Switch:SW_DPDT_x2 SW1
U 1 1 5EE472AE
P 7650 2600
F 0 "SW1" V 7604 2748 50  0000 L CNN
F 1 "POWER SW" V 7695 2748 50  0000 L CNN
F 2 "Button_Switch_SMD:SW_SPDT_PCM12" H 7650 2600 50  0001 C CNN
F 3 "~" H 7650 2600 50  0001 C CNN
	1    7650 2600
	0    1    1    0   
$EndComp
$Comp
L RF_Module:ESP-12E U10
U 1 1 5EDBE48C
P 7550 4050
F 0 "U10" H 7550 5031 50  0000 C CNN
F 1 "ESP-12E" H 7550 4940 50  0000 C CNN
F 2 "RF_Module:ESP-12E" H 7550 4050 50  0001 C CNN
F 3 "http://wiki.ai-thinker.com/_media/esp8266/esp8266_series_modules_user_manual_v1.1.pdf" H 7200 4150 50  0001 C CNN
	1    7550 4050
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U2
U 1 1 5EE71C01
P 1500 6550
F 0 "U2" H 1500 7531 50  0000 C CNN
F 1 "4017" H 1500 7440 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 1500 6550 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 1500 6550 50  0001 C CNN
	1    1500 6550
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U5
U 1 1 5EE71C07
P 2500 6550
F 0 "U5" H 2500 7531 50  0000 C CNN
F 1 "4017" H 2500 7440 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 2500 6550 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 2500 6550 50  0001 C CNN
	1    2500 6550
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U7
U 1 1 5EE71C0D
P 3500 6550
F 0 "U7" H 3500 7531 50  0000 C CNN
F 1 "4017" H 3500 7440 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 3500 6550 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 3500 6550 50  0001 C CNN
	1    3500 6550
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U9
U 1 1 5EE71C13
P 4500 6550
F 0 "U9" H 4500 7531 50  0000 C CNN
F 1 "4017" H 4500 7440 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 4500 6550 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 4500 6550 50  0001 C CNN
	1    4500 6550
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U1
U 1 1 5EE71C19
P 1500 4850
F 0 "U1" H 1500 5831 50  0000 C CNN
F 1 "4017" H 1500 5740 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 1500 4850 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 1500 4850 50  0001 C CNN
	1    1500 4850
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U4
U 1 1 5EE71C1F
P 2500 4850
F 0 "U4" H 2500 5831 50  0000 C CNN
F 1 "4017" H 2500 5740 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 2500 4850 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 2500 4850 50  0001 C CNN
	1    2500 4850
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U6
U 1 1 5EE71C25
P 3500 4850
F 0 "U6" H 3500 5831 50  0000 C CNN
F 1 "4017" H 3500 5740 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 3500 4850 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 3500 4850 50  0001 C CNN
	1    3500 4850
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U8
U 1 1 5EE71C2B
P 4500 4850
F 0 "U8" H 4500 5831 50  0000 C CNN
F 1 "4017" H 4500 5740 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 4500 4850 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 4500 4850 50  0001 C CNN
	1    4500 4850
	1    0    0    -1  
$EndComp
$Comp
L 4xxx:4017 U3
U 1 1 5EEC54BE
P 5500 6550
F 0 "U3" H 5500 7531 50  0000 C CNN
F 1 "4017" H 5500 7440 50  0000 C CNN
F 2 "Package_SO:SOP-16_4.4x10.4mm_P1.27mm" H 5500 6550 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4017bms-22bms.pdf" H 5500 6550 50  0001 C CNN
	1    5500 6550
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole H1
U 1 1 5EEEEEED
P 7800 6250
F 0 "H1" H 7900 6296 50  0000 L CNN
F 1 "MountingHole" H 7900 6205 50  0000 L CNN
F 2 "Mounting Holes:MountingHole_3.2mm_M3_Pad_Via" H 7800 6250 50  0001 C CNN
F 3 "~" H 7800 6250 50  0001 C CNN
	1    7800 6250
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0101
U 1 1 5EEF1292
P 7550 4800
F 0 "#PWR0101" H 7550 4550 50  0001 C CNN
F 1 "GND" H 7555 4627 50  0000 C CNN
F 2 "" H 7550 4800 50  0001 C CNN
F 3 "" H 7550 4800 50  0001 C CNN
	1    7550 4800
	1    0    0    -1  
$EndComp
Wire Wire Line
	7550 4750 7550 4800
$Comp
L Connector_Generic:Conn_01x06 J2
U 1 1 5EEF26B7
P 7900 5450
F 0 "J2" H 7980 5442 50  0000 L CNN
F 1 "ICSP_NODEMCU" H 7980 5351 50  0000 L CNN
F 2 "Custom Footprints:6pin 1.27mm ICSP Pad" H 7900 5450 50  0001 C CNN
F 3 "~" H 7900 5450 50  0001 C CNN
	1    7900 5450
	1    0    0    -1  
$EndComp
Text GLabel 7700 5350 0    50   Input ~ 0
GPIO-0
Text GLabel 7700 5550 0    50   Input ~ 0
TX
Text GLabel 7700 5650 0    50   Input ~ 0
RX
Text GLabel 7700 5750 0    50   Input ~ 0
RESET
Wire Wire Line
	7700 5250 7100 5250
Wire Wire Line
	7100 5250 7100 5400
Wire Wire Line
	7550 3250 7550 2950
Text GLabel 7700 5450 0    50   Input ~ 0
ESP_3V3
Text GLabel 7650 2950 2    50   Input ~ 0
ESP_3V3
Wire Wire Line
	7650 2950 7550 2950
Connection ~ 7550 2950
Wire Wire Line
	7550 2950 7550 2800
Text GLabel 8450 3250 2    50   Input ~ 0
GPIO-0
Text GLabel 8150 3550 2    50   Input ~ 0
TX
Text GLabel 8150 3750 2    50   Input ~ 0
RX
Text GLabel 6600 3450 0    50   Input ~ 0
RESET
NoConn ~ 7750 2800
$Comp
L power:GND #PWR0102
U 1 1 5EEF3A29
P 7100 5400
F 0 "#PWR0102" H 7100 5150 50  0001 C CNN
F 1 "GND" H 7105 5227 50  0000 C CNN
F 2 "" H 7100 5400 50  0001 C CNN
F 3 "" H 7100 5400 50  0001 C CNN
	1    7100 5400
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR0103
U 1 1 5EEFCC2B
P 7100 3000
F 0 "#PWR0103" H 7100 2750 50  0001 C CNN
F 1 "GND" H 7105 2827 50  0000 C CNN
F 2 "" H 7100 3000 50  0001 C CNN
F 3 "" H 7100 3000 50  0001 C CNN
	1    7100 3000
	1    0    0    -1  
$EndComp
Wire Wire Line
	7150 2950 7100 2950
Wire Wire Line
	7100 2950 7100 3000
$Comp
L Device:C C1
U 1 1 5EEFB974
P 7300 2950
F 0 "C1" V 7048 2950 50  0000 C CNN
F 1 "1uF" V 7139 2950 50  0000 C CNN
F 2 "Capacitor_SMD:C_0805_2012Metric" H 7338 2800 50  0001 C CNN
F 3 "~" H 7300 2950 50  0001 C CNN
	1    7300 2950
	0    1    1    0   
$EndComp
Wire Wire Line
	7450 2950 7550 2950
Wire Wire Line
	10700 2550 10950 2550
Wire Wire Line
	10950 2550 10950 2650
Connection ~ 10950 2650
$Comp
L Device:R R3
U 1 1 5EF2633E
P 8400 4350
F 0 "R3" V 8300 4350 50  0000 C CNN
F 1 "10k" V 8400 4350 50  0000 C CNN
F 2 "Resistor_SMD:R_0805_2012Metric" V 8330 4350 50  0001 C CNN
F 3 "~" H 8400 4350 50  0001 C CNN
	1    8400 4350
	0    1    1    0   
$EndComp
Wire Wire Line
	8150 4350 8250 4350
Text GLabel 8850 3450 2    50   Input ~ 0
ESP_3V3
$Comp
L power:GND #PWR0104
U 1 1 5EF2800C
P 9300 4600
F 0 "#PWR0104" H 9300 4350 50  0001 C CNN
F 1 "GND" H 9305 4427 50  0000 C CNN
F 2 "" H 9300 4600 50  0001 C CNN
F 3 "" H 9300 4600 50  0001 C CNN
	1    9300 4600
	1    0    0    -1  
$EndComp
Wire Wire Line
	8550 4350 8600 4350
Wire Wire Line
	9300 4350 9300 4600
$Comp
L Device:R R4
U 1 1 5EF2AEE8
P 8550 3450
F 0 "R4" V 8450 3450 50  0000 C CNN
F 1 "10k" V 8550 3450 50  0000 C CNN
F 2 "Resistor_SMD:R_0805_2012Metric" V 8480 3450 50  0001 C CNN
F 3 "~" H 8550 3450 50  0001 C CNN
	1    8550 3450
	0    1    1    0   
$EndComp
Text GLabel 6500 3650 0    50   Input ~ 0
ESP_3V3
$Comp
L Device:R R2
U 1 1 5EF302BA
P 6700 3650
F 0 "R2" V 6600 3650 50  0000 C CNN
F 1 "10k" V 6700 3650 50  0000 C CNN
F 2 "Resistor_SMD:R_0805_2012Metric" V 6630 3650 50  0001 C CNN
F 3 "~" H 6700 3650 50  0001 C CNN
	1    6700 3650
	0    1    1    0   
$EndComp
Wire Wire Line
	6600 3450 6850 3450
Text GLabel 6500 3250 0    50   Input ~ 0
ESP_3V3
Wire Wire Line
	6850 3250 6850 3450
Connection ~ 6850 3450
Wire Wire Line
	6850 3450 6950 3450
Wire Wire Line
	8400 3450 8300 3450
Wire Wire Line
	8450 3250 8300 3250
Wire Wire Line
	8300 3250 8300 3450
Connection ~ 8300 3450
Wire Wire Line
	8300 3450 8150 3450
Wire Wire Line
	6550 3650 6500 3650
Wire Wire Line
	6800 3250 6850 3250
$Comp
L Device:R R1
U 1 1 5EF4588B
P 6650 3250
F 0 "R1" V 6550 3250 50  0000 C CNN
F 1 "10k" V 6650 3250 50  0000 C CNN
F 2 "Resistor_SMD:R_0805_2012Metric" V 6580 3250 50  0001 C CNN
F 3 "~" H 6650 3250 50  0001 C CNN
	1    6650 3250
	0    1    1    0   
$EndComp
Wire Wire Line
	6850 3650 6950 3650
$Comp
L Device:Buzzer BZ1
U 1 1 5EE302BC
P 8700 4050
F 0 "BZ1" H 8852 4079 50  0000 L CNN
F 1 "Buzzer" H 8852 3988 50  0000 L CNN
F 2 "Buzzer_Beeper:PUIAudio_SMT_0825_S_4_R" V 8675 4150 50  0001 C CNN
F 3 "~" V 8675 4150 50  0001 C CNN
	1    8700 4050
	1    0    0    -1  
$EndComp
Wire Wire Line
	8600 3950 8250 3950
Wire Wire Line
	8250 3950 8250 4250
Wire Wire Line
	8250 4250 8150 4250
Wire Wire Line
	8600 4150 8600 4350
Connection ~ 8600 4350
Wire Wire Line
	8600 4350 9300 4350
Wire Wire Line
	8700 3450 8850 3450
NoConn ~ 8150 3650
NoConn ~ 8150 3850
NoConn ~ 8150 3950
NoConn ~ 8150 4050
NoConn ~ 8150 4150
NoConn ~ 8150 4450
NoConn ~ 6950 3850
NoConn ~ 6950 4050
NoConn ~ 6950 4150
NoConn ~ 6950 4250
NoConn ~ 6950 4350
NoConn ~ 6950 4450
NoConn ~ 6950 4550
$EndSCHEMATC
