# Blinkprogram - NodeMCU (ESP8266)
## Vad är ett blinkprogram?
Ett blinkprogram är ett program mellan dator-microkontroller som får en indikator att blinka med bestämd intervall. Detta är oftast det man brukar testa först när man använder sig av Arduino. 

<img width="170" height="170" alt="Skärmavbild 2025-12-04 kl  09 09 40" src="https://github.com/user-attachments/assets/c86e11a5-0301-49bf-9d5a-03e861a991fb" />

## Microprocessorn 
I NodeMCU - Plusivokit använder man en microkontroller som kallas för ESP8266. Det är ett energieffektivt chip som har inbyggd WiFi med olika "portar" som styrs via Arduino. Vid användningen av Node MCU finns det redan en inbyggd LED som i Arduino kallas för LED_BUILTIN. 

<img width="170" height="170" alt="Skärmavbild 2025-12-04 kl  09 18 20" src="https://github.com/user-attachments/assets/b42040d9-c057-44a4-a205-fd45af0b8e18" />

## Två viktiga funktioner
 1. _Setup_ - Denna funktion körs endast en gång och det är när mikrokontrollen kommer igång. Det är i detta stadie som man väljer om en port ska ingång eller utgång. 
 3. _Loop_ - Här körs programmet om och om igen. Det är i denna funktion som det faktiskt sker något, i detta fall tänder och släcker lampan så att den börjar blinka. 

## Portinitialisering
Första steget i blinkprogrammet är att tala om för mikrokontrollern att pinnen LED:en tillhör är en utgång. Detta sker i "SETUP". 

<img width="391" height="55" alt="Skärmavbild 2025-11-28 kl  11 52 43" src="https://github.com/user-attachments/assets/c3ea834f-95b7-4e69-9849-0eb999b73d5a" />

## Blinkkod 

<img width="540" height="254" alt="Skärmavbild 2025-11-28 kl  11 56 34" src="https://github.com/user-attachments/assets/4cb846c4-7f64-4f36-b6de-d1a36e66401a" />

## Det vi lärt oss! 😄
 - ESP8266
 - Vad SETUP och LOOP innebär    
 - Initialisering av port 
 - Hur man kodar ett blinkprogram 
