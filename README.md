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

## Extras

- 🥮 Baklava = 1 Punkt · 🍯 Gold-Tablett = 3 Punkte · ☕ Çay-Glas = +6 Sekunden
- 🔥 Combo-Multiplikator (×2 ab 5, ×3 ab 12 Treffern in Folge)
- 🐻 Yuffibären-Treffer kosten Punkte – schnell essen lohnt sich!

## Spielen

Einfach `index.html` im Browser öffnen – mehr braucht es nicht.

### Auf GitHub Pages veröffentlichen

GitHub Pages ist bei **privaten** Repos nur mit GitHub Pro verfügbar. So geht's kostenlos:

1. Repo öffentlich machen: **Settings → General → Danger Zone → Change visibility → Public**
2. Diesen Branch nach `main` mergen
3. Der Workflow `.github/workflows/deploy-pages.yml` aktiviert Pages automatisch und deployt

Danach ist das Spiel erreichbar unter: **https://mademtek.github.io/testgame/**
