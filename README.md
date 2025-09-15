# ronni_cardealer (inklusive ronni_platesystem)

## Deutsch 🇩🇪

Dies ist das **ronni_cardealer Script**, entwickelt mit Unterstützung von ChatGPT.  
Es kombiniert ein realistisches **Autohaus-/Händler-System** mit integriertem **ronni_platesystem** und unterstützt **sh59_keysystem + esx_carlock** für Schlüsselverwaltung.  

Das Script ist **Open Source** und kann frei genutzt und angepasst werden.  

---

### 🚀 Features
- 🏢 **Showroom-System**: Fahrzeuge können im Showroom (via `vector4`) ausgestellt werden.  
- 📖 **Fahrzeug-Katalog**: Spieler können Fahrzeuge durchblättern und ansehen (nicht einsteigen).  
- 🤝 **Vertragsbasiertes Verkaufssystem**:  
  - Spieler können Fahrzeuge nur mit einem **Contract-Item** verkaufen.  
  - Händler-Jobs (z. B. `cardealer`) können ohne Contract verkaufen.  
- 🔑 **Schlüssel-Integration**: Automatische Schlüsselübergabe mit **sh59_keysystem** + **esx_carlock**.  
- 🚗 **Kennzeichen-System** (via `ronni_platesystem`):  
  - Vorläufige Kennzeichen bei Autohaus-Kauf (7 Tage gültig).  
  - Wunschkennzeichen oder Zufallskombination.  
  - Möglichkeit, Kennzeichen mit Item („Klebeband“) abzudecken.  
- 👔 **Boss-Menü**: Geld einzahlen/auszahlen, Job-Kasse verwalten.  
- ⚙️ **Konfigurierbar**:  
  - Inventarsystem (ox_inventory oder ESX Inventory).  
  - Job-Restriktionen.  
  - Showroom-Positionen, Katalog-Fahrzeuge und mehr.  
- 💾 **Persistente Speicherung**: Fahrzeuge bleiben nach Neustart im Besitz.  

---

### 📦 Voraussetzungen
- **FiveM Server** (aktuelle Version)  
- **ESX** (aktuelle Version)  
- **oxmysql**  
- **ronni_platesystem** (für Kennzeichenverwaltung)  
- **sh59_keysystem** + **esx_carlock Fork** (für Fahrzeugschlüssel)  

---

### ⚙️ Installation
1. Lade das Script in deinen `resources`-Ordner.  
2. Stelle sicher, dass **ronni_platesystem**, **sh59_keysystem** und **esx_carlock** installiert sind.  
3. Importiere die SQL-Dateien (Items wie „vertrag“, optional Icons in ox_inventory).  
4. Trage das Script in deiner `server.cfg` ein:  
   ```cfg
   ensure ronni_cardealer
