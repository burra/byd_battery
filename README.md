# BYD battery

Reverse engineering a 11kWh BYD HVM battery system, connected to a Fronius Gen24 Symo 5.0 Hybrid inverter

## Blockshema

Open .odg with e.g LibreOffice Draw

## Logfiles

Open with HHD Device Monitoring Studio
<https://www.hhdsoftware.com/device-monitoring-studio>

## Modbus RTU Registers

Open .ods file with your favourite spreadsheet tool (e.g. LibreOffice Calc)
The Battery has registers that the Fronius Inverter requests to read. There is also a write event that periodically appears (see logs)
During startup more bus activity is present compared to sitting idle. This is most likely due to pre-charge handshake.

## Pictures

Internal pictures from when BYD box was opened

## byd_be_connect

Windows program for connecting to BYD battery and doing firmware update and diagnostics over WIFI

## Manuals

Usefull manuals from BYD webpage.
