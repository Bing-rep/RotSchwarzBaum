# Red-Black Tree Visualizer

Ein interaktiver, webbasierter Visualisierer für **Rot-Schwarz-Bäume**. Dieses Tool hilft dabei, die komplexen Balancing-Operationen (Rotationen und Umfärbungen) eines der wichtigsten selbstbalancierenden binären Suchbäume zu verstehen.

## ✨ Features

* **Interaktive Animationen:** Verfolge das Einfügen von Knoten Schritt für Schritt. Jede Rotation und Umfärbung wird logisch erklärt.
* **Regel-Check:** Validierung der RSB-Eigenschaften (Wurzel-Farbe, rote Kinder, Schwarzhöhe) in Echtzeit.
* **Preorder-Import:** Lade ganze Baumstrukturen über eine einfache Text-Syntax (z.B. `10S 5R 15R`).
* **Quiz-Modus:** Generiere zufällige Bäume ohne Farben und versuche, sie selbst korrekt nach den RSB-Regeln einzufärben.
* **Analyse-Tools:** Anzeige von Schwarzhöhe, Gesamthöhe und verschiedenen Traversierungen (Inorder, Preorder, Postorder).
* **Modernes UI:** Responsives Dark-Design mit Zoom- und Pan-Funktion für große Baumstrukturen.

## 🚀 Live Demo

Du kannst den Visualizer direkt im Browser nutzen:
**[https://bing-rep.github.io/RotSchwarzBaum/]**

## 🛠️ Bedienung

1.  **Einfügen:** Nutze entweder das Feld für Einzelknoten (mit Animation) oder das Textfeld für Preorder-Listen.
2.  **Bearbeiten:** Klicke auf einen Knoten, um seine **Farbe manuell zu ändern**, oder mache einen Doppelklick, um den **Wert zu bearbeiten**.
3.  **NIL-Blätter:** Klicke auf die kleinen NIL-Knoten, um direkt an dieser Stelle einen neuen Wert einzufügen.
4.  **Navigation:** Nutze das Mausrad zum Zoomen und ziehe die Arbeitsfläche mit der Maus, um den Fokus zu verschieben.

## 💻 Tech Stack

* **HTML5 / CSS3:** Custom Properties für das Theme und CSS-Animationen.
* **SVG:** Dynamische Generierung der Baumstruktur und Verbindungen.
* **Vanilla JavaScript:** Die gesamte Logik (Einfügen, Löschen, Rotationen) ist in nativem JS geschrieben – keine externen Frameworks oder Libraries nötig.

## 📖 RSB-Regeln (Kurzreferenz)

Das Tool prüft automatisch gegen diese fünf Standard-Eigenschaften:
1. Jeder Knoten ist entweder **rot** oder **schwarz**.
2. Die **Wurzel** ist immer schwarz.
3. Alle **Blätter (NIL)** sind schwarz.
4. Wenn ein Knoten rot ist, müssen seine Kinder schwarz sein (**keine zwei roten Knoten hintereinander**).
5. Jeder Pfad von einem Knoten zu seinen Nachfahren-Blättern enthält die **gleiche Anzahl schwarzer Knoten**.

---

*Erstellt für Bildungszwecke im Bereich Algorithmen und Datenstrukturen.*

---
