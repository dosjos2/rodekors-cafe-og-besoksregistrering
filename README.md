# Røde Kors – kafé og besøksregistrering

En samling C#-skrivebordsprosjekter for Røde Kors, med besøksregistrering og kafédrift. Løsningen inneholder salgsregistrering, varer, brukere, svinn, rapporter og regnskap.

## Innhold

- `RodeKors.sln`: Visual Studio-løsning.
- `Besøks registrering 2/`: besøksregistrering.
- `CafeTerminal/`: kaféterminal med blant annet salg, varer og rapporter.
- `CafeRegnskap/`: regnskapsdel.
- `DomainObjects/`, `DomainObjecsSalg/` og `DomainObjectSalg2/`: domenemodeller og databasemapping.
- `dlls/` og `packages/`: medfølgende biblioteker og pakker.

## Åpne prosjektet

Åpne `RodeKors.sln` i Visual Studio med støtte for Windows Forms og .NET Framework. Kaféterminalen retter seg mot .NET Framework 4.0. Løsningen inneholder ulike generasjoner av datatilgang, blant annet Entity Framework og NHibernate; kontroller konfigurasjon og databasekrav for hvert prosjekt.

Det opprinnelige navnet `rpdekors` er erstattet med `rodekors-cafe-og-besoksregistrering`.

## Opphav og historikk

- Opprinnelig repo: [dosjos/rpdekors](https://github.com/dosjos/rpdekors).
- Opprinnelig opprettet på GitHub: **2012-10-02 04:15:44 UTC** (GitHubs metadata for kilderepoet).
- Denne kopien: [dosjos2/rodekors-cafe-og-besoksregistrering](https://github.com/dosjos2/rodekors-cafe-og-besoksregistrering).

Flyttet fra `dosjos` til `dosjos2` fordi eieren mistet tilgangen til den opprinnelige kontoen. Eksisterende Git-historikk, forfattere, grener og tags er bevart; README-oppdateringen er en ny commit. GitHub-opprettelsesdatoen for denne kopien er datoen for flyttingen, og erstatter ikke datoen ovenfor.

Beskrivelsen er basert på kildekoden og prosjektfilene. Bygg og kjøring av de historiske prosjektene er ikke verifisert ved flyttingen. Eksisterende lisensfiler og krediteringer gjelder fortsatt.
