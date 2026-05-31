# 🕸️ Interaktives CSS Grid-Labor

Ein praktisches Cheat-Sheet und interaktives Labor, um die Logik hinter dem zweidimensionalen CSS Grid-System spielerisch zu verstehen. Erschaffe komplexe Web-Layouts mit nur wenigen Zeilen Code!

> 💻 **Tipp für das beste Lernergebnis:**
> Obwohl dieses Tutorial komplett responsiv ist und auf dem Smartphone sauber angezeigt wird, solltest du es **am besten am PC oder Laptop nutzen**. Nur so kannst du den Code nebenbei in einem Editor öffnen, Werte verändern und die Experimente aktiv ausprobieren!

---

## 🚀 Was ist CSS Grid?

Im Gegensatz zu Flexbox (das vor allem für eindimensionale Zeilen oder Spalten gedacht ist) ist CSS Grid für **zweidimensionale Layouts** gebaut. Das bedeutet, du kontrollierst Spalten (*Columns*) und Zeilen (*Rows*) gleichzeitig. Es bildet das moderne Fundament für komplexe Website-Strukturen, Dashboards und Bildergalerien.

### Wichtige Grundbegriffe:
* **Grid-Container:** Das Eltern-Element, auf dem `display: grid;` aktiviert wird.
* **Grid-Item:** Die direkten Kind-Elemente innerhalb des Rasters.
* **Fraction (`fr`):** Eine flexible Grid-Maßeinheit. `1fr` bedeutet "ein Bruchteil des verfügbaren Platzes".

---

## 🛠️ Experimente für dein Tutorial

Lade dieses Repository herunter und öffne die `index.html` in deinem Texteditor. Springe im `<style>`-Bereich zum Punkt `2. DAS GRID-CONTAINER LABOR` und modifiziere das Raster:

* **Mehr Spalten bauen:** Ändere `grid-template-columns: repeat(3, 1fr);` zu `repeat(4, 1fr);`. Das Raster ordnet deine 6 Boxen blitzschnell in ein 4-Spalten-Layout um.
* **Asymmetrisches Layout:** Ändere die Zeile zu `250px 1fr 1fr;`. Die erste Spalte ist nun fest auf 250 Pixel fixiert, während die anderen beiden sich den restlichen Platz dynamisch teilen.
* **Das Element strecken (Spanning):** Gehe im CSS zur Klasse `.item-featured` (Zeile 85) und entferne die Kommentarzeichen (`/* */`) bei `grid-column: span 2;`. Schau im Browser nach: Box 1 erstreckt sich nun elegant über zwei Spaltenbreiten!

---

## 🌐 Live-Demo

Schau dir das Grid-Labor direkt live im Browser an:
👉 **[HIER DEINEN GITHUB-PAGES-LINK EINFÜGEN]**

---

## 📄 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Siehe die Datei [LICENSE](LICENSE) für Details.