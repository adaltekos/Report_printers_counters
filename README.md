# Report printers counters

## Description
This PowerShell script extracts the number of printed pages and scans from Konica Minolta printers using SNMP protocol and saves the data to an Excel file. The script is prepared to work with three printers.

## Prerequisites
- This script requires snmpget.exe in C:\usr\bin\. You can download it from https://ezfive.com/snmpsoft-tools/snmp-get/.
- PowerShell v3 or later.

## Configuration
Before running the script, update the following variables:
- `$excel`: complete with the location of the Excel file where you want to save the data (ex. C:\liczniki\Raport_licznikow_z_drukarek.xlsx).
- `$printer1`: complete with the IP of the Konica Minolta printer (ex. 192.168.0.0).
- `$printer2`: complete with the IP of the Konica Minolta printer (ex. 192.168.0.0).
- `$printer3`: complete with the IP of the Konica Minolta printer (ex. 192.168.0.0).
