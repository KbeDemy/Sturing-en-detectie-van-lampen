# I2C Uitbreiding bord - Lamp sturing & Detectie

Expansion board voor lampenbeheer. Bedoeld voor gebruik met een externe microcontroller (ESP32) via I2C.

## Specificaties
- **I/O Expander:** MCP23017 (I2C).
- **Input:** 230V AC detectie via LTV-814 optocouplers.
- **Output:** 30V AC sturing voor Eltako relais via Omron G5V-1 relais.
- **Indicatie:** Debug-LED's voor logica en relaisstatus.


## Pinout & Adressen
- **I2C Adres:** Standaard 0x20 (instelbaar via A0, A1, A2).
- **Signaal/voeding - niveaus:** 
    - 3.3VDC logic
    - 5VDC aansturen relais
    - 30VAC aansturen omron
    - 230VAC uitlezen status lamp
      


