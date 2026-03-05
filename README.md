# 🚀 GHFLOW - GitHub Terminal Workflow Tool

`GHFLOW` ist ein interaktives Batch-Tool für Windows, das Git-Workflows für Einsteiger und Profis gleichermaßen vereinfacht. Es automatisiert gängige Aufgaben und bietet eine benutzerfreundliche Oberfläche direkt im Terminal.

---

## ✨ Features

*   **🛠️ Repo-Management:** Automatische Initialisierung (`git init`) und einfaches Setzen der Remote-URL.
*   **📊 Status auf einen Blick:** Aktueller Branch, Remote-URL und Anzahl der geänderten Dateien werden ständig angezeigt.
*   **💾 Commit & Push:** Interaktives Staging, anpassbare Commit-Nachrichten und automatischer Upstream-Push.
*   **🔄 Vollsync:** Ein-Klick-Lösung, um alle Änderungen zu stagen, zu committen und zu pushen.
*   **🌿 Branch-Verwaltung:** Einfaches Wechseln zwischen Branches oder Erstellen neuer Features-Branches.
*   **🧹 Repository-Cleaning:**
    *   **Untrack:** Dateien aus dem Git-Tracking entfernen, ohne sie lokal zu löschen.
    *   **History Purge:** Dateien (wie versehentlich gepushte Secrets) aus der kompletten Git-Historie entfernen.
*   **📝 .gitignore Generator:** Erstellt auf Knopfdruck eine vorkonfigurierte `.gitignore`-Datei für moderne Web- und Softwareprojekte.

---

## 🚀 Installation & Nutzung

1.  Lade die `ghflow.bat` in dein Projektverzeichnis herunter.
2.  Starte das Tool durch einen Doppelklick auf `ghflow.bat` oder über das Terminal:
    ```cmd
    ghflow.bat
    ```
3.  Folge dem interaktiven Menü.

---

## 🛠️ Menü-Optionen

1.  **Status anzeigen:** Detaillierte Übersicht der geänderten Dateien.
2.  **Commit + Push:** Dateien stagen, Nachricht eingeben und ab zu GitHub.
3.  **Pull:** Änderungen vom Server holen.
4.  **Branch wechseln / neu:** Navigation durch deine Branches.
5.  **Vollsync:** Der "Quick-Fix" – alles stagen und pushen.
6.  **Untrack:** Entfernt Dateien aus dem Repo (gut für `.env` oder große Binärdaten).
7.  **History Purge:** ⚠️ *Fortgeschritten* – Löscht eine Datei unwiderruflich aus allen vergangenen Commits.
8.  **.gitignore erstellen:** Erstellt eine solide Basis für dein Projekt.
9.  **Beenden:** Schließt das Programm.

---

## ⚠️ Wichtige Hinweise

*   **History Purge:** Diese Aktion schreibt die Git-Historie neu. Nach der Anwendung ist ein `force-push` erforderlich. Nutze dies mit Vorsicht, besonders in Team-Projekten.


---

*Entwickelt für einen simplen und schnellen GitHub-Workflow.*
