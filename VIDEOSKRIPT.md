# Videoskript – LehrerPlan (max. 3:00, 720p MP4, ≤ 45 MB)

**OBS-Einstellungen:** Einstellungen → Video → Ausgabeauflösung 1280x720, 30 FPS. Ausgabe → Aufnahmeformat MP4 (oder MKV und danach „Aufnahmen remuxen“), Bitrate ca. 1500 kbps (≈ 35 MB bei 3 min). Quelle: Bildschirmaufnahme, Mikrofon an.
Dateiname bei der Abgabe: `01-25-LehrerplanNov.mp4`

## 0:00 – 0:40 · Projekt vorstellen (Simon)
Bild: Unity, Game-Ansicht mit Gang B und C.
> „Unser LehrerPlan ist ein digitaler Nachbau von Gang B und C im 3. Stock der HTL Salzburg. Er ist für Schülerinnen, Schüler und Eltern gedacht, die wissen wollen, welche Lehrkraft in welchem Raum sitzt, wann Sprechstunde ist und unter welcher Nummer man anrufen kann. Die Daten holen wir live per Webrequest und Regex von der Lehrerseite der Schulhomepage.“

## 0:40 – 1:30 · Anwendung zeigen (Yohannes)
Bild: Play drücken, Schilder zeigen „Lädt …“ und füllen sich. Dann ins Schild B303 hineinzoomen.
> „Wenn man Play drückt, steht auf allen Türschildern zuerst ‚Lädt …‘. Das Programm lädt die Lehrerliste, ordnet jede Lehrkraft über den Link ihrem Raum zu und lädt dann die Detailseiten. Um die Informationen zu einem Raum zu sehen, geht man einfach zum Türschild – hier B303: oben fett die Raumnummer, darunter die Lehrkräfte mit Sprechstunde und unten die Telefonnummer des Raums.“

## 1:30 – 2:45 · Test 7 vorführen (Simon)  ← Zeitmarke für das Issue: **1:30**
Bild: WLAN in der Taskleiste ausschalten, Console leeren, Play drücken.
> „Wir zeigen Test 7: Was passiert, wenn die Übersicht nicht erreichbar ist? Erwartet wird: Auf den Schildern steht ‚Keine Verbindung‘ und in der Console ‚Fehler beim Laden: …‘. Wir schalten jetzt das WLAN aus und starten die Szene.“
(warten, Console und Schilder zeigen)
> „Alle Schilder zeigen ihre Raumnummer und ‚Keine Verbindung‘, in der Console steht ‚Fehler beim Laden: Cannot resolve destination host‘, und Unity läuft weiter. Test 7 ist damit bestanden.“

## 2:45 – 3:00 · Abschluss (Yohannes)
> „Alle sieben Tests und ihre Ergebnisse stehen in unserer TESTPROTOKOLL.md auf GitHub. Danke fürs Zuschauen!“

---

**Issue-Kommentar (nach dem Schnitt Zeitmarke prüfen):**

```
Testprotokoll: [TESTPROTOKOLL.md](./TESTPROTOKOLL.md)
Im Video gezeigter Test: Test 7 ab 1:30
```
