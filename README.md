# TPS

Phase 1 - Vorbereitung
Aufgabe	Beschreibung
Engine auswählen	Unity (empfohlen) oder Unreal Engine installieren
Projekt erstellen	Neues 3D-Projekt anlegen
Asset-Bibliothek	Kostenlos im Asset Store: Character Models, Guns, Sounds, etc.

Phase 2 - Spieler-Controller
Aufgabe	Beschreibung
Third Person Controller	Template aus Unity Asset Store oder selbst bauen
Kamera	Third-Person Kamera, folgt dem Spieler
Bewegung	WASD + Maus zum Drehen
Animationen	Laufen, Springen, Idle (Standard-Animationen verwenden)

Phase 3 - Shooter-Mechanik
Aufgabe	Beschreibung
Waffe	Simple 3D-Model (Cube = Platzhalter) an der Hand des Spielers
Schießen	Mit Linksklick einen Raycast nach vorne schießen
Mündungseffekt	Muzzle Flash + Schuss Sound
Treffer	Raycast trifft Gegner → Schaden zufügen

Phase 4 - Gegner
Aufgabe	Beschreibung
Gegner Prefab	Simple Gegner mit Collider & Health System
AI	Gegner läuft zum Spieler mit NavMeshAgent
Sterben	Gegner verschwindet oder spielt Sterbeanimation ab
Respawn	Optional: Gegner respawnt nach Zeit

Phase 5 - HUD
Aufgabe	Beschreibung
Lebensanzeige	Health-Bar für den Spieler
Munition	Anzeige der Munition im Magazin
Fadenkreuz	Einfaches UI-Fadenkreuz in der Bildschirmmitte
Nachladen	Taste R = Nachladen (optional)

Phase 6 - Level Design
Aufgabe	Beschreibung
Terrain	Erstelle ein einfaches Gelände
Hindernisse	Steine, Mauern, Deckungen
Licht	Beleuchtung für Atmosphäre

Phase 7 - Feinschliff
Aufgabe	Beschreibung
Sounds	Schritte, Schüsse, Treffer, Tod
Effekte	Partikel (Rauch, Blut, Explosion)
Kamera-Shake	Für Schussgefühl

Phase 8 - Build & Export
Aufgabe	Beschreibung
Fehler testen	Funktioniert alles?
Export	Windows Build oder WebGL Export
Teilen	Du kannst es Freunden zeigen oder sogar veröffentlichen
