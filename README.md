# EuroAdmin BungeeCord Plugin

Een eenvoudige BungeeCord-plugin voor admins met een report-systeem.

## Functionaliteit
- `/report <speler> <reden>`: speler rapporteren.
- `/reports list [pagina]`: openstaande rapporten bekijken.
- `/reports view <id>`: details van een rapport bekijken.
- `/reports resolve <id> <reden>`: een rapport sluiten.

## Permissions
- `euroadmin.report`: spelers kunnen rapporteren.
- `euroadmin.admin`: admins kunnen rapporten bekijken en beheren.

## Builden
1. Installeer Maven.
2. Run `mvn package -Dmaven.test.skip=true`.

> Als de BungeeCord API niet wordt gevonden, moet je mogelijk een repository toevoegen of de juiste BungeeCord API-versie gebruiken in `pom.xml`.
