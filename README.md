# REMIX Illuminated Moon Wall Lamp (Small Version) 🌙💡

Eine atemberaubende 2D Topographie des Mondes, die von hinten mit adressierbaren LEDs beleuchtet wird und per Smartphone gesteuert werden kann.  
Die perfekte Kombination aus Kunst, Wissenschaft und Smart Home Technologie!

---

## 🌕 Beschreibung

Diese beleuchtete Mond Wandlampe zeigt die detaillierte Oberflächenstruktur des Mondes als Topographie.  
Durch die **RGB LED Hintergrundbeleuchtung** kannst du Farbe, Helligkeit und Lichteffekte vollständig vom Smartphone aus steuern – **ohne App-Installation!**  
Das elegante Web Interface macht die Steuerung intuitiv und komfortabel.

Die 3D gedruckte Topographie wirft je nach Beleuchtungswinkel und Farbe verschiedene Schatten und hebt die Krater, Maria (dunkle Ebenen) und Hochländer des Mondes plastisch hervor.  
Ein echtes Highlight für jeden Weltraum-Enthusiasten!  

---

## ✨ Features

- Detaillierte Oberflächenstruktur des Mondes  
- 💡 **RGB LED Hintergrundbeleuchtung** (21 adressierbare WS2812B LEDs)  
- 📱 **WiFi-Steuerung**, Vollständige Kontrolle per Smartphone/Tablet  
- 🎨 **Millionen von Farben** – Echtzeit-Farbauswahl mit Color Picker  
- 🌈 **Dynamische Effekte**: Regenbogen & Fade Animationen  
- 💫 Einstellbare **Helligkeit**: 0–100%  
- ⚡ **Fade-Geschwindigkeit**: Animationsgeschwindigkeit anpassbar  
- 🌙 Edles Dark-Mode Interface (Anthrazit-Design mit blauen Akzenten)  
- 🔌 **mDNS-Support**: Zugriff über `ledlampe.local` ohne IP-Adresse  
- 🖼 **Wandmontage**: Integrierte Aufhängung auf der Rückseite  

---

## 🛠 Verwendete Materialien

### 3D-Druck
- **Filament**: PLA oder PETG (weiß, grau oder transluzent empfohlen)  
- **Menge**: ca. 150g (abhängig von Größe & Infill)  
- **Druckzeit**: 6–7 Stunden  

### Elektronik
- 1x ESP32 Development Board (ESP32 DevKit V1 oder ähnlich)  
- 1x WS2812B LED Strip (5V, 21 LEDs, Länge anpassbar)  
- 1x USB-Kabel  
- Optional: Streufolie/Diffusor für gleichmäßigeres Licht  

### Software
- Arduino IDE (Version 1.8.x oder 2.x)  
- ESP32 Board Support Package  
- Adafruit NeoPixel Library  
- ESPmDNS Library  

### Werkzeug & Zubehör
- Lötkolben (optional)  
- Kabel / Draht  
- Heißkleber, Sekundenkleber oder doppelseitiges Klebeband  
- Kabelkanäle (optional)  
- Schrauben/Dübel/Nagel für Wandmontage  

---

## 🖨 Druckeinstellungen

**Empfohlen:**  
- Layer Height: 0.2mm (0.12mm für mehr Detail)  
- Infill: 15–20% (Gyroid oder Grid)  
- Supports: Nein (optional, abhängig vom Drucker)  
- Brim/Raft: Optional  
- Wandstärke: 3–4 Perimeter  
- Top/Bottom Layers: 4–5  

**Material-Tipps:**  
- Weiß/Graues PLA: Klassischer Mond-Look  
- Transluzentes Filament: Weicherer Lichteffekt  
- Silk/Pearlescent PLA: Schimmernd, mystisch  
- PETG: Robuster & hitzebeständig  

---

## 🔌 Verkabelung

LED Strip DIN   → ESP32 GPIO 16
LED Strip 5V   → Netzteil 5V+
LED Strip GND  → GND
ESP32 GND      → Netzteil GND (bei >25 LEDs)
