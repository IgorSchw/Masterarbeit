# Masterarbeit: Optimierung der räumlichen Positionierung eines Roboterarms für den vollautomatischen Spritzbetonauftrag

Dieses Repository enthält die im Rahmen meiner Masterarbeit erstellten Python-Skripte und Jupyter Notebooks. Die Arbeit wurde am Management Center Innsbruck im Studiengang Umwelt-, Verfahrens- und Energietechnik (berufsbegleitend) angefertigt.

## 📚 Thema der Masterarbeit

Ziel dieser Masterarbeit war die Entwicklung eines Korrekturmodells für das kinematische Modell einer Maschine zum vollautomatischen Spritzbetonauftrag, sowie die Ausarbeitung eines robusten Einmessverfahrens, zur Referenzierung der Maschinenposition nach jeder Umpositionierung. Das finale Ergebnis der Automatisierung, des Korrekturmodells und des Einmessverfahrens wurde anhand eines vollautomatisch gefahrenen Pfades an einer Versuchswand untersucht. Dies erfolgte auf zwei Weisen. Einmal durch die Vermessung des Spritzpfades (ohne Spritzbetonauftrag) mithilfe eines Kamerasystems und durch finale Spritzversuche, bei welchen Spritzbeton unter sich ändernden Spritzparametern auf eine Versuchswand aufgetragen wurde. 

Zur Interpretation der Ergebnisse, zur Ermittlung von Transformationen und zur Visualisierung bestimmter Ergebnisse wurden verschiedene Python-Skripte und Jupyter Notebooks entwickelt.

## 📁 Struktur des Repositories

- `data/` – Rohdaten im `.csv`-Format
- `notebooks/` – Jupyter Notebooks für Auswertungen, Analysen und Visualisierungen  
- `results/` – erzeugte Abbildungen, Diagramme und Ergebnis-Exports  
- `requirements.txt` – Liste der verwendeten Python-Bibliotheken  
- `LICENSE` – Lizenzinformationen  
- `README.md` – dieses Dokument

## ⚙️ Verwendung

1. **Repository klonen:**
   ```bash
   git clone https://github.com/dein-nutzername/masterarbeit-code.git
   cd masterarbeit-code
