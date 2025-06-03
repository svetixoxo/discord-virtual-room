# Discord Virtual Room (Prototyp)

**Experimenteller Ansatz für räumliche Stimmenverteilung in Discord-Sprachkanälen**

Dies ist ein frühes Konzept für ein Tool, das es ermöglichen soll, Stimmen in einem Discord-Sprachkanal räumlich zu positionieren. Ziel ist es, ein Gefühl zu erzeugen, als säßen die Teilnehmer gemeinsam in einem Raum – durch räumlich verteilte Audiowiedergabe (zB via Stereo-Panorama, Surround uÄ).

## Ziel des Projekts

Das Tool soll zwei zentrale Funktionen ermöglichen:

1. **Individuelle Raumwahrnehmung**  
   Jeder Nutzer kann festlegen, wo er andere Teilnehmer im Raum hört (bspw. links, rechts, vorne, hinten).

2. **Globale Kanal-Konfiguration**  
   Es kann auch serverseitig (bspw. durch bestimmte Benutzer/Rollen oder Bots) definiert werden, welche Stimme aus welcher Richtung kommt, für eine sinnvolle Raumanordnung.

## Idee im Detail

- Die Stimmen der Teilnehmer werden einzeln verarbeitet.
- Über Audiopanning oder räumliche Filter wird jedem eine Position im Raum zugewiesen.
- Ziel ist ein realistischer, räumlicher Höreindruck durch eine natürliche Klangverteilung.
- Die Umsetzung kann bspw. über einen Discord-Bot oder externe Software für Audio-Routing erfolgen.
