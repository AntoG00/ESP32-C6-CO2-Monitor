# Hardware V2 – ESP32‑C6 + SEN66 + 4.2" E‑Ink

This is the second hardware revision of the project. V2 replaces the SCD43 + SHT45 combo with a single Sensirion **SEN66** environmental sensor and upgrades the display.

## Main Components

- **MCU:** Espressif **ESP32‑C6 Mini**
  - Wi‑Fi 6 + BLE / 802.15.4 capable (WiFi 6, Zigbee, Thread)
- **Sensor:** Sensirion **SEN66**
  - PM1, PM2.5, PM4, PM10
  - Temperature, Relative Humidity
  - VOC Index, NOx Index, CO₂
- **Display:** Pervasive Displays **4.2" Spectra E2417QS0A3**
  - 3‑color E‑Ink
- **Status LED:** Inolux **IN‑PI33TBTPRPGPB** multi‑color LED
  - Used for debug / status indication via color patterns
