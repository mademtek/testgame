# 🥮 Baklavabauch

Ein 3D-Handyspiel in einer einzigen `index.html` – komplett self-contained, ohne externe Bibliotheken.

**Iss so viel Baklava wie möglich, bevor die Zeit abläuft – aber pass auf die Yuffibären auf!** Sie hüpfen wie die Gummibärenbande auf dich zu und klauen dir Punkte.

## Charaktere

| Charakter | Stil | Spezialfähigkeit |
|---|---|---|
| ⚡ **El Yas Amin** | Der Blitz | Superschnell, kurze Dash-Abklingzeit |
| 🧲 **Dr. Serkanovic** | Der Süßologe | Baklava-Magnet – zieht Süßes magisch an |
| 🛡️ **Ahmet Soldjar** | Der Panzer | Verliert kaum Punkte, sein Dash schleudert Yuffibären durch die Luft |

## Steuerung (Handy)

- 🕹️ **Linke Bildschirmhälfte**: Daumen auflegen und ziehen = laufen
- ⚡ **Rechts tippen**: Dash (macht kurz unverwundbar und schleudert Bären weg)
- Auf dem Desktop: WASD/Pfeiltasten + Leertaste

## 5 Level

Erreiche das Baklava-Ziel, bevor die Zeit abläuft, und steig auf ins nächste Level – jedes mit eigener Welt und mehr Yuffibären:

1. **Basar** – der klassische Sonnenuntergang-Basar
2. **Nachtbasar** – Sternenhimmel, mehr Bären
3. **Wüste** – heller Tag, offene Dünen
4. **Hamam** – rutschiger Marmorboden mit aufsteigendem Dampf
5. **Sultanspalast** – das goldene Finale

Wer alle fünf schafft, wird **Sultan von Baklavistan** 👑.

## Power-Ups & Extras

- 🥮 Baklava = 1 Punkt · 🍯 Gold-Tablett = 3 Punkte
- ☕ **Çay-Glas** = +6 Sekunden
- 🌶️ **Chili** = Turbo-Tempo für 6 Sekunden
- 🧿 **Nazar** = Schutzschild gegen den nächsten Bären-Treffer
- 🍯 **Honig** = zieht 8 Sekunden lang alles Baklava magisch an
- ⭐ **Goldener Yuffibär** = per Dash weggeschleudert bringt er 10 Punkte
- 🔥 Combo-Multiplikator (×2 ab 5, ×3 ab 12 Treffern in Folge)

## 📡 2-Spieler-Multiplayer (Peer-to-Peer)

Zwei Handys spielen 90 Sekunden gegeneinander – wer mehr Baklava isst, gewinnt.
Die Verbindung läuft **direkt von Handy zu Handy über WebRTC**, es gibt keinen
eigenen Spiel-Server. So geht's:

1. Spieler A tippt auf **📡 2 SPIELER → RAUM ERSTELLEN** und bekommt einen 4-stelligen Code.
2. Spieler B tippt den Code ein und auf **BEITRETEN**.
3. Fertig – der Host startet das Duell.

> Für den reinen Verbindungsaufbau (das „Händeschütteln") wird der kostenlose,
> öffentliche PeerJS-Broker genutzt. Danach fließen alle Spieldaten direkt
> zwischen den beiden Geräten. Es muss also **kein eigener Server betrieben
> werden**, und das Spiel läuft komplett auf GitHub Pages. Beide Geräte
> brauchen nur eine Internetverbindung.

## Spielen

Einfach `index.html` im Browser öffnen – mehr braucht es nicht.

### GitHub Pages

Das Spiel läuft unter: **https://mademtek.github.io/testgame/**

Bei jedem Push auf `main` spiegelt der Workflow `.github/workflows/deploy-pages.yml` den Stand automatisch auf den `gh-pages`-Branch, von dem GitHub Pages ausliefert.
