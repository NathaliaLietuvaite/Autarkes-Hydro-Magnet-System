# Technische Spezifikationen  
**Systembezeichnung:** Autarkes Hydro-Magnet-System  
**Funktionsprinzip:** Energiegewinn durch phasengetaktete Auftriebs-Magnet-Resonanz

---

## 1. Gehäuse und Struktur
- **Gesamtdurchmesser:** 250 cm
- **Zentralkörper (Hauptzylinder):**  
  - Material: Acrylglas (transparent)  
  - Durchmesser: 20 cm  
  - Höhe: 250 cm  
  - Umgebung: Vakuumkammer (~10⁻³ mbar)

- **Rotorarme:**  
  - Anzahl: 6 (symmetrisch radial angeordnet, 60° Abstand)  
  - Länge: 100 cm  
  - Durchmesser: variabel, typ. 5–8 cm  
  - Material: Acrylglas, gefüllt mit niedrigviskoser Dielektrikumsflüssigkeit  
  - Medium: Deionisiertes Wasser mit Antiturbulenz-Additiven  

---

## 2. Auftriebseinheit (Innenelement pro Rotorarm)
- **Körper:** Strömungsoptimierte Auftriebskapsel  
- **Masse:** 1 kg (variable Schwerpunktverlagerung intern)  
- **Auftriebselement:** Wasserfüllung mit Dichtegradient  
- **Magnetkern:** Neodym-Elemente (Position intern steuerbar)  
- **Reibungsführung:** Wandnahe Neodym-Führung, nahezu reibungsfrei

---

## 3. Rotornarbe & Lagerung
- **Zentrallager:** Nahezu reibungslose Magnetschwebelagerung  
- **Durchmesser:** 10 cm  
- **Drehbereich:** 0–30 U/min (je nach Modus)  
- **Geometrie:** Nabe erlaubt phasensynchrone Masseverlagerung zur Trägheitsoptimierung  
- **Verstärkungsstruktur:** Optimiert für Sechsersymmetrie, gleichmäßige Momentverteilung

---

## 4. Impulszonen
- **Positionen:**  
  - **6 Uhr:** Axialer Impuls → Beschleunigung zur Nabe  
  - **12 Uhr:** Radialer Impuls → Beschleunigung zum höchsten Punkt  

- **Impulse:**  
  - Art: Getaktete elektromagnetische Felder oder mechanisch synchronisierte Magnetkontakte  
  - Dauer: ≤ 0,2 s pro Zyklus  
  - Energie pro Impuls: ca. 1,75 J  
  - Frequenz: 2 Impulse pro Umdrehung × 6 Rotoren = **12 Impulse/Zyklus**

---

## 5. Energiehaushalt (ideales System)
- **Energieeintrag pro Zyklus:**  
  - Auftrieb + Magnetimpuls (2× pro Rotor × 6 Rotoren): ~**21,0 J**  
- **Friction Losses:**  
  - Gesamtverlust durch Lager + Mediumreibung: ≤ **6,0 J**  
- **Nettoenergie verfügbar:**  
  - ~**15,0 J pro Zyklus** (im optimalen Betrieb)  
- **Energieauskopplung:**  
  - Methode: Ringförmiger Induktionsgenerator (Kupferwicklung außen)  
  - Wirkprinzip: Rotierendes Feld erzeugt Wechselspannung über Magnetkerne

---

## 6. Kontroll- und Sensorsystem
- **Steuerung:**  
  - Echtzeit-Phasencontroller (FPGA-basiert)  
  - Synchronisierung der Impulsaktivierung an 6/12 Uhr
- **Sensorik:**  
  - Feldstärkesensoren  
  - Rotationspositionierung  
  - Massenschwerpunktdetektion (inertialsensorgestützt)

---

## 7. Visualisierung & Design
- **Feldlinienanzeige:**  
  - LED-basierte Flux-Vektoren (blau)  
- **Indikatoren:**  
  - Mikroblasen-Tracer in den Flüssigkeitskammern  
  - Pulslicht an 6/12 Uhr bei Impulsaktivierung  
- **Optional:**  
  - Holografisches Energieströmungsdisplay (für Präsentationsbetrieb)

---

## 8. Sicherheits- & Testumgebung
- **Betriebsumgebung:**  
  - Vakuum- oder Niederdruck-Kammer  
  - Temperaturstabil: ±1 K  
- **Zugänglichkeit:**  
  - Vollständig abnehmbares Außengehäuse für Wartung  
- **Testlaufzeit:**  
  - 24h Dauerbetrieb mit Impulsfrequenzüberwachung

---

> ⚠️ *Diese Spezifikation beschreibt ein hochdynamisches, resonanzbasiertes Mehrrotorsystem. Energieextraktion und Effizienz hängen entscheidend von der Taktsteuerung und der phasenrichtigen Ausführung aller Feldimpulse ab.*
