# EntityCulling

Ermöglicht es durch asynchrones Path-Tracing Blöcke und Entitäten welche im Sichtradius, aber nicht sichtbar sind NICHT
zu rendern. Dadurch erhöht sich die FPS des Clients.

`nur Client` [Website](https://www.curseforge.com/minecraft/mc-mods/entityculling)

### Funktion

Minecraft überspringt das Rendern von Dingen, die sich hinter dir befinden. Warum also rendert es alles, was nicht
gesehen wird, wenn eine Wand im Weg ist? Dieser Mod nutzt die anderen CPU-Kerne/Threads, um ein wirklich schnelles
Path-Tracing von der Charakter Kamera zu allen Blöcken/Entitäten durchzuführen, um zu bestimmen, ob sie sichtbar sind
oder nicht. Während des Renderings werden die nicht sichtbaren Objekte übersprungen, genauso wie die Objekte hinter dem
Charakter.
