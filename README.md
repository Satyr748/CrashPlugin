# CrashPlugin

Ein kleines Paper-Plugin mit `/crash <Spieler>`. Der Befehl trennt den ausgewählten Spieler vom Server; er verursacht keinen Client- oder Serverabsturz.

## Voraussetzungen

- Minecraft Java-Server mit Paper 1.21.x
- Java JDK 21
- Gradle (oder IntelliJ IDEA mit Gradle-Unterstützung)

## Bauen

Im Projektordner ausführen:

```bash
gradle build
```

Die JAR-Datei findest du anschließend unter `build/libs/CrashPlugin-1.0.0.jar`.

## Installieren

1. Server stoppen.
2. JAR-Datei in den Serverordner `plugins/` kopieren.
3. Server starten.
4. Als Operator ausführen: `/crash Spielername`

Nur Operatoren haben standardmäßig die Berechtigung `crashplugin.use`.

## In IntelliJ IDEA

1. `settings.gradle` öffnen bzw. den Projektordner als Gradle-Projekt importieren.
2. JDK 21 auswählen.
3. Gradle-Aufgabe `build` starten.
4. Die erzeugte JAR-Datei aus `build/libs/` in `plugins/` kopieren.
