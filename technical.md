 Aspekt / Fragestellung           | Konsequenz bei keiner oder zu später Berücksichtigung  
--- | ---
Prototyping / PoC zu komplexen Themen aber dabei auch klare Grenzen, wann Prototyping aufhört und Entwicklung anfängt | Sonst arbeitet man oft in die falsche Richtung uns muss dann wieder umkehren 
Basisarchitektur (Microservices, SOA/Rest)      |
Technologiestacks definieren (Auswahl von Werkzeugen, Frameworks, Libraries, Patterns) | Umwege 
Branching-Konzept      |    Kopfschmerzen :D
Welche Deployment-Artefakte will man (perspektivisch) <br>Welche Umgebungen für welche Zwecke benötigt man | Chaos, unnötige Arbeit 
Was sind die Rahmenbedingungen der produktiven Zielinfrastruktur (Firewalls) |
Absprache mit Schnittstellenpartnern (Testdaten, Zugriffsrechte …) |
Test frühzeitig automatisieren, Teststufen in die CI-Pipelines integrieren | Man weiß nicht, ob die Tests aufgrund der eigenen Entwicklung fehlschlagen oder schon vorher kaputt waren <br> Häufig wird lokale Ausführung vergessen
Struktur von Verzeichnissen, Modulen, Packages, grundlegendes Codegerüst | Einheitlichkeit und Verständlichkeit leidet
Namingconventions, einheitliche Benennung | Nachträgliche Änderungen an allen Stellen aufwändig und fehleranfällig
Art und Weise wie Exception-Handling und Logging umgesetzt werden soll definieren und gleich in Implementierungen berücksichtigen (nicht aufgrund von schnellem Working Skeleton in die Zukunft verschieben) | Nachträglicher Einbau wird womöglich vergessen
Konzept zur technische Umsetzung von Rechte/Rollen, Authentifizierung/Authorisierung | Nachträglicher Einbau ist aufwändig
 