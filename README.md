# 📊 MLOps-Studie: Datenanalyse & Auswertung  

Dieses Repository enthält den Code und die Ergebnisse der Datenanalyse im Rahmen der Bachelorarbeit **"MLOps in der Praxis: Eine Analyse des Reifegrades deutscher Unternehmen"**.  

## 📁 Verzeichnisstruktur  

- **`src/`** → Enthält den Quellcode der Analyse  
- **`results.csv`** → Enthält die gesammelten Umfrageergebnisse als CSV-Datei  
- **`requirements.txt`** → Listet alle benötigten Python-Pakete für die Analyse  
- **`Datenanalyse_Skript.ipynb`** → Jupyter Notebook mit der vollständigen Datenanalyse  
- **`Datenanalyse_Auswertung.pdf`** → Exportierte Version der Ergebnisse als PDF  

## 🚀 Installation & Nutzung  

### 1️⃣ Virtuelle Umgebung erstellen (optional)  
Falls eine virtuelle Umgebung genutzt werden soll, kann diese mit folgendem Befehl erstellt werden:  
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate  # Windows

2️⃣ Benötigte Pakete installieren
Die notwendigen Bibliotheken können mit folgendem Befehl installiert werden:
pip install -r requirements.txt

3️⃣ Jupyter Notebook starten
Falls Jupyter nicht installiert ist, kann es mit folgendem Befehl hinzugefügt werden:
pip install jupyter

Das Notebook kann dann mit folgendem Befehl ausgeführt werden:
jupyter notebook Datenanalyse_Skript.ipynb
