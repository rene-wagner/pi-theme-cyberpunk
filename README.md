# Cyberpunk-Theme für Pi

Ein dunkler Pi-Theme-Prototyp mit Neonpink, Cyan und Gelb auf dunkelblauen Flächen. Er färbt Oberfläche, Markdown, Syntax und HTML-Export; die Terminal-Hintergrundfarbe selbst bleibt beim Terminal.

## Ausprobieren

Im Projektverzeichnis:

```sh
pi --approve --use-theme cyberpunk
```

`--approve` erlaubt Pi, das Projekt-Theme aus `.pi/themes/cyberpunk.json` für diesen Aufruf zu laden. Alternativ im laufenden Pi nach erteiltem Projektvertrauen über `/settings` das Theme **cyberpunk** auswählen. Nach Änderungen am Projekt-Theme `/reload` ausführen.

Für die Nutzung außerhalb dieses Projekts die Datei nach `~/.pi/agent/themes/cyberpunk.json` kopieren und anschließend `pi --use-theme cyberpunk` starten. Bei sehr hell eingestelltem Terminal-Hintergrund empfiehlt sich ein dunkles Terminalprofil.
