GYM TRACKER – PWA INSTALLATION (kostenlos)

Enthaltene Dateien:
- index.html – die App
- manifest.webmanifest – macht die Website installierbar
- service-worker.js – Offline-Funktion und Updates
- icon-192.png / icon-512.png / apple-touch-icon.png – App-Symbole

WICHTIG:
- Die App selbst enthält keine Trainings- oder Gewichtsdaten.
- Beim ersten Start dieser Produktivversion werden nur eventuell noch vorhandene Test-Trainings, Test-Gewichte und ein offenes Test-Workout einmalig entfernt.
- Danach bleiben echte Daten bei späteren Code-Updates erhalten.
- Trainingsdaten liegen lokal auf jedem iPhone und werden nicht zwischen Nutzern geteilt.

Kostenloses Hosting mit GitHub Pages:
1. Kostenloses Konto auf github.com anlegen/anmelden.
2. Neues PUBLIC Repository erstellen, z.B. gym-tracker.
3. Diese Dateien aus dem ZIP in die oberste Ebene des Repositorys hochladen.
4. Repository: Settings > Pages.
5. Unter Build and deployment: Source = Deploy from a branch.
6. Branch = main, Ordner = /(root), Save.
7. Nach der Veröffentlichung die angezeigte https://...github.io/gym-tracker/ Adresse öffnen.

Auf dem iPhone:
1. Die GitHub-Pages-Adresse in Safari öffnen.
2. Teilen > Zum Home-Bildschirm hinzufügen.
3. „Als Web-App öffnen“ aktivieren.
4. Hinzufügen.
5. Danach über das Gym-Icon starten. Safari-Leisten werden dann nicht angezeigt.

Updates:
- Bei späteren Änderungen einfach index.html und ggf. service-worker.js im selben Repository ersetzen.
- Immer dieselbe GitHub-Pages-Adresse behalten.
- Lokale Trainingsdaten bleiben erhalten.
- Vor größeren Updates trotzdem in der App ein Daten-Backup exportieren.
