# Einstellungen

Hier steht, was jede Einstellung im Shader-Menü von **Mystic Realism** macht. Du findest sie im Spiel unter **Optionen** → **Videoeinstellungen** → **Shaderpakete** → **Mystic_Realism_Shaders** → **Shader-Einstellungen**. Jede Einstellung hat dort auch eine Erklärung, wenn du mit der Maus darüberfährst.

Die Werte in der Spalte **Standard** gelten für das Profil *High*, mit dem der Shader startet.

[⬅️ Zurück zur Startseite / zum Download](README.md)

---

## Profil

Oben im Menü stellst du mit **Profil** alles auf einmal ein: *Very Low*, *Low*, *Mid*, *High* oder *Ultra*. Danach kannst du einzelne Werte trotzdem noch ändern.

| Einstellung | Very Low | Low | Mid | High | Ultra |
|---|---|---|---|---|---|
| Schattenauflösung | 1024 | 1024 | 2048 | 2048 | 4096 |
| Schattenreichweite | 64 | 96 | 96 | 128 | 192 |
| Schattenqualität (Samples) | 4 | 6 | 8 | 10 | 20 |
| Lichtstrahlen | aus | 0.5 | 1 | 1 | 1 |
| Nordlicht | aus | 0.5 | 1 | 1 | 1 |
| Realistisches Laub | aus | 0.5 | 1 | 1 | 1 |
| Wehende Pflanzen | aus | an | an | an | an |
| Spiegelungen im Wasser | aus | an | an | an | an |
| Bewegungsunschärfe | aus | aus | 0.05 | 0.1 | 0.1 |

## 🌫️ Atmosphäre (Nebel, Wetter, Himmel)

| Einstellung | Standard | Was sie macht |
|---|---|---|
| **Nebeldichte** | 1 | Dunst in der Ferne und in Tälern. 0 = klare Sicht, 2–3 = dichter, mystischer Nebel. Bei Regen und Dämmerung wird er automatisch dichter. |
| **Nebelhöhe (Talnebel)** | 28 | Wie hoch der Bodennebel reicht. Klein = nur dicht über dem Boden, groß = füllt auch Berghänge. |
| **Waldnebel** | 1 | Wabernder Bodennebel nur in Wald-, Taiga-, Dschungel-, Sumpf- und Kirschhain-Biomen. 0 = aus, 2 = dichter Märchenwald. In Höhlen bleibt er aus. |
| **Lichtstrahlen** | 1 | Sonnen- und Mondstrahlen durch Blätter, Wolken und Berge. 0 = aus, 2 = sehr kräftig. Etwas leistungshungrig. |
| **Nordlicht** | 1 | Grün-violettes Polarlicht, nur nachts und ohne Regen. 0 = aus, 2 = auffällig. |
| **Epischer Nachthimmel** | 1 | Milchstraße, zarte Nebel und funkelnde Sterne. 0 = nur Vanilla-Sterne, 2 = sehr viele helle Sterne. |
| **Wolken-Animation** | 1 | Wie schnell die Wolken ziehen und sich verformen. 0 = stehen still, 2 = Zeitraffer. |
| **Helligkeit bei Regen** | 1 | Höher = hellerer Regentag, niedriger = düster und dramatisch. |
| **Nebel bei Regen** | 0.3 | Wie dicht der Nebel bei Regen wird. 0 = kein Regennebel, 1.8 = sehr neblig. |

## 💧 Wasser

| Einstellung | Standard | Was sie macht |
|---|---|---|
| **Spiegelungen im Wasser** | an | Bäume, Ufer und Berge spiegeln sich im Wasser. Aus = nur der Himmel spiegelt sich, schneller. |
| **Spiegel-Qualität** | 24 | Mehr = genauere und weitere Spiegelungen, kostet Leistung. |
| **Wellen** | 1 | 0 = spiegelglatt, 2 = unruhig. |
| **Wassertrübung** | 1 | Wie schnell das Wasser mit der Tiefe dunkel wird. 0.5 = glasklar, 2 = trüb. |

## 🎬 Post-Processing & Color Grading

| Einstellung | Standard | Was sie macht |
|---|---|---|
| **Schärfe** | 0.8 | Schärft Kanten und feine Texturen. 0 = aus, 2 = sehr scharf (kann körnig wirken). |
| **Klarheit (lokaler Kontrast)** | 0.8 | Mehr Tiefe für Baumrinde, Gras, Stein und Wolkenränder. 2 = starker HDR-Look. |
| **Epic-Fantasy-Look** | 1 | Erdiger Herr-der-Ringe-/Skyrim-Look: olivgrün-goldenes Gras, gedämpfte Farben, goldene Lichter. 0 = kräftig und bunt. |
| **Bloom (Leuchten)** | 1.2 | Weicher Lichtschein um Sonne, Mond, Fackeln und Glowstone. 0 = aus, 3 = sehr starkes Glühen. |
| **Mystik-Farbstich** | 1 | Violett-türkiser Hauch in Schatten, Nebel und Nacht. 0 = neutral, 2 = sehr märchenhaft. |
| **Farbtemperatur (warm/kalt)** | 0.15 | −1 = eisig kalt, 0 = neutral, +1 = sehr warm. |
| **Cinematic-Farbtrennung** | 1 | Kino-Farben: Schatten türkis-violett, Lichter golden. 0 = aus, 2 = stark stilisiert. |
| **Kontrast** | 1.12 | 1 = unverändert, 1.4 = sehr kontrastreich. |
| **Sättigung** | 1.15 | 1 = natürlich, 0.6 = fast Schwarzweiß, 1.4 = knallig. |
| **Helligkeit (Belichtung)** | 1 | Gesamthelligkeit wie bei einer Kamera. Niedriger = dunkler und düsterer. |
| **Tonemapping** | Hable | *ACES* = kräftig, etwas flacher. *Hable* = filmisch weicher Übergang in helle Bereiche. |
| **Vignette** | 1 | Dunkelt die Bildränder ab. 0 = aus, 3 = sehr stark. |
| **Unschärfe am Rand** | 0 | Weichzeichnet nur die Ränder (Tilt-Shift-Look). Die Mitte bleibt scharf. |
| **Weichzeichner (ganzes Bild)** | 0 | Leichter, traumhafter Schimmer über das ganze Bild. 0.75 = sehr weich. |
| **Bewegungsunschärfe** | 0.1 | Verwischt das Bild bei schnellem Drehen. Hand und Hotbar bleiben scharf. 0 = aus. |
| **Filmkorn** | 0 | Feines Rauschen wie bei Analogfilm. 0 = aus, 2 = deutlich. |

## ⚡ Leistung & Qualität

| Einstellung | Standard | Was sie macht |
|---|---|---|
| **Schattenauflösung** | 2048 | Detailgrad der Schatten. 1024 = schnell und grob, 4096 = sehr scharf, braucht viel Grafikleistung. |
| **Schattenreichweite** | 128 | Bis zu wie vielen Blöcken Schatten berechnet werden. Weiter = mehr Leistung. |
| **Schattenqualität (Samples)** | 10 | Wie glatt weiche Schattenkanten sind. 4 = schnell, leicht körnig, 20 = sehr glatt. |
| **Schattenweichheit** | 1 | 0.5 = harte Schatten, 3 = sehr weiche, diffuse Schatten. |
| **Lichtstrahlen-Qualität** | 20 | 8 = schnell, leicht gestuft, 28 = sehr glatt. Wirkt nur, wenn Lichtstrahlen an sind. |
| **Waldnebel-Qualität** | 8 | 4 = schnell, leicht körnig, 12 = sehr weich. |
| **Wolken-Detail** | 5 | 3 = einfache Wolken (schnell), 6 = feinste Wolkenränder. |

## 🌳 Weitere Einstellungen

| Einstellung | Standard | Was sie macht |
|---|---|---|
| **Realistisches Laub** | 1 | Jedes Blatt-Cluster leicht anders gefärbt, Sonnenlicht scheint durchs Laub. Ideal mit einem Better-Leaves-Pack. 0 = aus, 2 = sehr ausgeprägt. |
| **Wehende Pflanzen/Laub** | an | Gras, Blumen und Blätter wiegen sich im Wind. Aus = ruhiges Bild, etwas mehr Leistung. |
| **Sonnenbahn-Neigung** | −25 | Neigung der Sonnen- und Mondbahn. 0 = Sonne mittags senkrecht, −25 = schräge, dramatische Schatten. |

---

Kostenlos. Weitergeben gern, aber nicht verkaufen.
