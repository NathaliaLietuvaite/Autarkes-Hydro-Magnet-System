# Stückliste – AION-System (Version: 6-Rotor / Explosionsansicht)

## Hauptstruktur
| Bauteil-Nr. | Bezeichnung                     | Material          | Maße                  | Funktion                              |
|-------------|----------------------------------|-------------------|------------------------|----------------------------------------|
| 01          | Zentralkammer (Hauptzylinder)   | Acrylglas         | Ø 200 mm × H 2500 mm   | Rotorachse, Vakuumkammer               |
| 02          | Basisplatte                     | Verbundwerkstoff  | 400 mm × 400 mm × 20 mm | Trägerstruktur, Energieableitung       |
| 03          | Lager-Nabe mit Magnetlagerung   | Titan/Neodym      | Ø 100 mm × H 100 mm    | Reibungsarme Drehlagerung              |

---

## Rotorarme & Auftriebseinheiten
| Bauteil-Nr. | Bezeichnung                     | Material          | Maße                  | Funktion                              |
|-------------|----------------------------------|-------------------|------------------------|----------------------------------------|
| 04          | Rotorarme (6 Stück)             | Acrylglas         | Ø 60 mm × L 1000 mm    | Trägheitsübertragung, Flüssigkeitsführung |
| 05          | Auftriebskapseln (6 Stück)      | Verbund (Kunststoff + Neodym) | Ø 55 mm × L 220 mm | Dynamische Masseverlagerung            |
| 06          | Führungsmagnete (rotorarmintern)| Neodym N52        | Ø 20 mm × 5 mm         | Zentrierung der Kapsel im Rotor        |

---

## Impulssystem (Magnetisch/elektronisch)
| Bauteil-Nr. | Bezeichnung                     | Material/Typ      | Position               | Funktion                              |
|-------------|----------------------------------|-------------------|------------------------|----------------------------------------|
| 07          | Elektromagnetmodule (2×)        | Ferritkern, Kupfer | 6 Uhr & 12 Uhr         | Impulsbeschleunigung (axial/radial)    |
| 08          | Impulssteuerungseinheit         | FPGA-Controller   | Extern am Gehäuse      | Phasensynchrone Steuerung der Felder   |
| 09          | Sensorsuite (Gyro, Position)    | MEMS-Sensorik     | Rotorbasis & Kapsel    | Echtzeitlage, Drehimpulserkennung      |

---

## Energiegewinnung
| Bauteil-Nr. | Bezeichnung                     | Material          | Maße                  | Funktion                              |
|-------------|----------------------------------|-------------------|------------------------|----------------------------------------|
| 10          | Toroidaler Induktionsring       | Kupferlackdraht   | Ø außen ~300 mm        | Energieextraktion aus rotierendem Feld |
| 11          | Energieauskoppler (Regler)      | Elektronikmodul   | 100 mm × 60 mm         | Gleichrichtung / Glättung des Stroms   |

---

## Zusatzkomponenten & Anzeige
| Bauteil-Nr. | Bezeichnung                     | Typ/Material       | Funktion                             |
|-------------|----------------------------------|--------------------|---------------------------------------|
| 12          | LED-Impulsanzeiger              | RGB-LED (12×)      | Visualisierung Impulspositionen       |
| 13          | Holografisches Energiemapping   | OLED+Diffusor      | Darstellung von Energiekurven         |
| 14          | Vakuumpumpenanschluss           | Edelstahl (DN16KF) | Entgasung & Druckregelung             |

---

## Hinweise
- **Toleranzen:** Fertigungstoleranz für Rotorarme: ±0,1 mm  
- **Magnetisierung:** Neodym-Magnete radial ausgerichtet  
- **Elektronik:** Modular, durchgehende 12V Versorgungsschiene  

---

> *Diese Stückliste ist Grundlage für die CAD-Modellierung, Produktion oder Laboraufbau. Einzelne Maße können bei Miniatur- oder Großserienanpassung skaliert werden.*
