# Blinkprogram - NodeMCU (ESP8266)
## Vad är ett blinkprogram?
Ett blinkprogram är oftast det första man testar med Arduino eller ett microkontrollersystem samt går ut på att koden för att få en LED att blinka samt hur snabbt eller långsamt det sker. 

## Microprocessorn 
I NodeMCU använder man en microkontroller som kallas för ESP8266. Vad detta är för något är ett energieffektivt chip som har inbyggd WiFi med olika "portar" som styrs via Arduino. Vid användningen av Node MCU finns det redan en inbyggd LED som i Arduino kallas för LED_BUILTIN. 

## Två viktiga funktioner
 1. _Setup_ - Denna funktion körs endast en gång och det är när mikrokontrollen kommer igång. Det är i detta stade som man väljer som en port ska ingång eller utgång. 
 3. _Loop_ - Lite som namnet så körs detta om och om igen, alltså i en loop. Det är i denna funktion som det faktiskt sker något, i detta fall tänder och släcker lampan så att den börjar blinka. 

## Portinitialisering
Första steget i blinkprogrammet är att tala om för mikrokontrollern att pinnen LED:en tillhör är en utgång. Detta sker i "SETUP". 
<img width="391" height="55" alt="Skärmavbild 2025-11-28 kl  11 52 43" src="https://github.com/user-attachments/assets/c3ea834f-95b7-4e69-9849-0eb999b73d5a" />

## Blinkkod 
<img width="540" height="254" alt="Skärmavbild 2025-11-28 kl  11 56 34" src="https://github.com/user-attachments/assets/4cb846c4-7f64-4f36-b6de-d1a36e66401a" />

## Det vi lärt oss!
 - ESP8266
 - Vad SETUP och LOOP innebär
 - Initialisering av port
 - Hur man kodar ett blinkprogram 
