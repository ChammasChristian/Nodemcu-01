## Introduktion
I denna presentation kommer jag att gå igenom det vi har lärt oss de senaste föreläsningarna/LAB

## Vad är Arduino IDE
Arduino IDE är ett program där man skriver och laddar upp kod till mikrokontrollers som NodeMCU.
Det används för att skapa, testa och skicka program till enheten så att den kan styra t.ex. lampor, sensorer och motorer.

## Installera Arduino IDE
- Ladda ner Arduino IDE från arduino.cc
- Installera och starta programmet
- Lägg till ESP8266-stöd:
- File → Preferences → Additional Boards URL
- Installera ”ESP8266” under Tools → Board → Boards Manager
- Välj: Tools → Board → NodeMCU 1.0 (ESP-12E Module)


File --> Examples --> Basic --> Blink

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/55122957-bed1-4c3b-ba98-f172014a5186" />

## Vad är mikroprocesser?
En mikroprocessor är "Hjärnan" som finns i en elektronisk enhet. Den följer instruktioner som vi skriver i ett program och bestämmer vad som ska hända. Tex. Tända och släcka en LED.

## Vad är Portinitialisering
Portinitialisering innebär att vi talar om för NodeMCU vad varje pinne ska göra innan vi använder den. Tex. Vi sätter LED-pinnen som utgång så att vi kan tända och släcka LED.
```ccp
pinMode(LED_BUILTIN, OUTPUT);
```

### Två basfunktionerna i Arduino
```cpp
Setup ()
```
- Startar programmet

```cpp
loop()
```
- Kör om och om igen 
  




