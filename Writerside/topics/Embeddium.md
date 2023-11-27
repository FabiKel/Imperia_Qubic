# Embeddium
<img src="embeddium-image.png" alt="embeddium-image.png" width="50" />

Embeddium ist ein inoffizieller Fork von Sodium, basierend auf Rubidium, mit zusätzlichen Änderungen und Bugfixes, um
es in das Forge Modding Ökosystem zu integrieren.

`nur Client` [Website](https://www.curseforge.com/minecraft/mc-mods/embeddium) [Wiki](https://github.com/embeddedt/embeddium/wiki)

### Featureliste (Rubidium)

- Eine moderne OpenGL-Rendering-Pipeline für das Chunk-Rendering, die Multi-Draw-Techniken nutzt und beim Rendern der
  Welt eine signifikante Reduzierung des CPU-Overhead (~ 90%) ermöglicht. Dies kann einen großen Unterschied bei den
  Bildraten für die meisten Computer bewirken, die nicht von der GPU oder anderen Komponenten mit Flaschenhals versehen
  sind. Selbst wenn Ihre GPU nicht mithalten kann, werden Sie viel stabilere Bildzeiten erleben, da die CPU in der Lage
  ist, andere Rendering-Aufgaben zu bearbeiten, während sie wartet.
- Vertex-Daten für gerenderte Blöcke werden viel kompakter, sodass die Anforderungen an Videospeicher und Bandbreite um
  fast 40% reduziert werden können.
- Blockaktualisierungen in der Nähe nutzen jetzt das Multithreading und reduzieren so die Verzögerungsspitzen, die durch
  zu aktualisierende Brocken verursacht werden.
- Chunk-Flächen, die nicht sichtbar sind (oder von der Kamera weg zeigen), werden sehr früh im Rendervorgang
  ausgesondert, wodurch eine Menge Geometrie eliminiert wird, die auf der GPU verarbeitet werden müsste, um sofort
  verworfen zu werden. Bei integrierten GPUs kann dies die Anforderungen an die Speicherbandbreite erheblich reduzieren
  und eine bescheidene Beschleunigung bieten, selbst wenn die GPU gebunden ist.
- Zahlreiche Optimierungen für das Laden von Stücken und das Rendern von Blöcken, wodurch das Laden von Stücken
  erheblich schneller und weniger schädlich für die Bildraten wird.
- Viele Optimierungen für Scheitelpunkt- und Matrix-Transformationen, die die Blockentität, den Mob und das Rendern von
  Elementen beschleunigen, wenn Sie mitgerissen werden und zu viele Truhen in einem Raum platzieren.
- Viele Verbesserungen bei der Verwaltung des Speichers durch das Spiel und der Zuweisung von Objekten, was wiederum den
  Speicherverbrauch und die durch die Aktivität des Müllsammlers verursachten Verzögerungsspitzen verringert.
- Viele grafische Korrekturen für reibungslose Lichteffekte, die das Spiel verbessern und gleichzeitig eine gesunde
  Optimierung anwenden.
- Reibungslose Beleuchtung für Flüssigkeiten und andere Spezialblöcke.
- Glatte Biomischung für Blöcke und Flüssigkeiten, die eine stark verbesserte grafische Qualität bietet, die wesentlich
  weniger rechnerisch intensiv ist.
- Animierte Texturen, die weltweit nicht sichtbar sind, werden nicht aktualisiert, was die Aktualisierung der Textur auf
  den meisten Hardware-Karten (insbesondere AMD-Karten) beschleunigt.)