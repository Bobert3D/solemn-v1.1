# solemn-v1.1

```mermaid
flowchart TD
    A[Ergogen Config] -->|Generate PCB| B[KiCad Layout]
    B --> C[Route Matrix & MCU]
    C --> D[Wire 4-Pin I2C OLED]
    D --> E{Run KiCad DRC}
    E -->|Errors Found| C
    E -->|0 Errors| F[Export Gerbers & Drill Files]
    F --> G[Order PCB]
    G --> H[Solder Diodes on B.Cu & Switches on F.Cu]
    H --> I[Flash Firmware & Test]
```
Just a cute lil keyboard that has 58 keys and some chill shapes! Onshape is: [Here](https://cad.onshape.com/documents/ffab3b96c6b14c6fbbbecfbc/w/70f0d4490e4bad1a7a011e3c/e/34635d68136bf4fd29bb578f?renderMode=0&uiState=6afcf95aaa4e5ee795028a4b)
<img width="1920" height="1200" alt="Screenshot 2026-11-17 5 56 51 PM" src="https://github.com/user-attachments/assets/96c6c51c-3c82-4862-9768-a607659884d1" />

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/eb5562bd-3ebb-4c7c-b991-8114b94c05ef" />
