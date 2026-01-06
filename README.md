# Tastmota SML ESP8266 Build

Download firmware.bin

Flash with ESPHomeFlasher or [ESPHomeWeb](https://web.esphome.io/)

[Download Firmware](/firmware.bin)

Example Script for my Meter:
```
>D
; aktuelle Version unter https://bitshake.de/skripte
>B
=>sensor53 r
>M 1
+1,5,s,0,9600,eHZ,4
1,=soC,1024,0
1,=so1,00010800,63,5,63,5,000f0700
1,77070100010800ff@1000,Verbrauch,kWh,E_in,3
1,77070100010801ff@1000,Verbrauch HT,kWh,E_inHT,3
1,77070100010802ff@1000,Verbrauch NT,kWh,E_inNT,3
1,77070100020800ff@1000,Einspeisung,kWh,E_out,3
1,77070100100700ff@1,akt. Leistung,W,Power,0
1,770701000f0700ff@1,akt. Leistung2,W,Power2,0
#>D
; aktuelle Version unter https://bitshake.de/skripte
>B
=>sensor53 r
>M 1
+1,5,s,0,9600,eHZ,4
1,=soC,1024,0
1,=so1,00010800,63,5,63,5,000f0700
1,77070100010800ff@1000,Verbrauch,kWh,E_in,3
1,77070100010801ff@1000,Verbrauch HT,kWh,E_inHT,3
1,77070100010802ff@1000,Verbrauch NT,kWh,E_inNT,3
1,77070100020800ff@1000,Einspeisung,kWh,E_out,3
1,77070100100700ff@1,akt. Leistung,W,Power,0
1,770701000f0700ff@1,akt. Leistung2,W,Power2,0
#
```
Credits: https://bitshake.de/skripte
