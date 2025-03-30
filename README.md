# TPS

Phase 1 - Vorbereitung

Engine auswählen	Unity (empfohlen) oder Unreal Engine installieren /
Projekt erstellen	Neues 3D-Projekt anlegen

Asset-Bibliothek	Kostenlos im Asset Store: Character Models, Guns, Sounds, etc.

Phase 2 - Spieler-Controller
Third Person Controller	Template aus Unity Asset Store oder selbst bauen
Kamera	Third-Person Kamera, folgt dem Spieler
Bewegung	WASD + Maus zum Drehen
Animationen	Laufen, Springen, Idle (Standard-Animationen verwenden)

Phase 3 - Shooter-Mechanik
Waffe	Simple 3D-Model (Cube = Platzhalter) an der Hand des Spielers
Schießen	Mit Linksklick einen Raycast nach vorne schießen
Mündungseffekt	Muzzle Flash + Schuss Sound
Treffer	Raycast trifft Gegner → Schaden zufügen

Phase 4 - Gegner
Gegner Prefab	Simple Gegner mit Collider & Health System
AI	Gegner läuft zum Spieler mit NavMeshAgent
Sterben	Gegner verschwindet oder spielt Sterbeanimation ab
Respawn	Optional: Gegner respawnt nach Zeit

Phase 5 - HUD
Lebensanzeige	Health-Bar für den Spieler
Munition	Anzeige der Munition im Magazin
Fadenkreuz	Einfaches UI-Fadenkreuz in der Bildschirmmitte
Nachladen	Taste R = Nachladen (optional)

Phase 6 - Level Design
Terrain	Erstelle ein einfaches Gelände
Hindernisse	Steine, Mauern, Deckungen
Licht	Beleuchtung für Atmosphäre

Phase 7 - Feinschliff
Sounds	Schritte, Schüsse, Treffer, Tod
Effekte	Partikel (Rauch, Blut, Explosion)
Kamera-Shake	Für Schussgefühl

Phase 8 - Build & Export
Fehler testen	Funktioniert alles?
Export	Windows Build oder WebGL Export
Teilen	Du kannst es Freunden zeigen oder sogar veröffentlichen
