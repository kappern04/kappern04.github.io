# Refleksjonsnotat - IDATT1003 Programmering 1

## 1. Hva var oppgaven?

I prosjektet skulle vi utvikle et program for å administrere matvarer i et kjøleskap. Hovedfokuset var å bruke objektorienterte prinsipper til å modellere matvarer og håndtere interaksjonene mellom objektene. Prosjektet inkluderte:
- Implementering av klasser for ulike matvarer.
- Håndtering av best-før datoer.
- Bruk av lister for lagring og organisering av matvarer.

Dette gav meg innsikt i hvordan OOP kan strukturere komplekse systemer på en lettfattelig måte.

## 2. Hva lærte jeg?

### Kunnskap om OOP

Gjennom prosjektet lærte jeg hvordan objektorientert programmering (OOP) gir mulighet for effektiv kodeorganisering og vedlikehold. Jeg fikk praktisk erfaring med:
- **Innkapsling**: For eksempel skjulte vi detaljer som best-før datoene i matvareklassene, og interagerte kun med metodene for å få eller oppdatere disse dataene.
- **Modularisering**: Hver matvare og kjøleskap ble modellert som egne klasser, noe som gjorde det lettere å utvikle og teste.
- **Samhandling mellom objekter**: Objektene, som matvarer og kjøleskap, kommuniserte ved å sende meldinger som "leggTilMatvare" eller "sjekkBestForDato".

### Programdesign og arkitektur
Jeg fikk dypere innsikt i **lagdelt arkitektur** og hvordan det gjør det lettere å isolere og endre spesifikke deler av programmet. For eksempel ble forretningslogikken separert fra grensesnittet ved at kjøleskapet og matvarer ble behandlet i egne moduler.

## 3. Hva var mitt bidrag i gruppearbeidet?

Jeg utviklet hovedlogikken i systemet, inkludert funksjonaliteten for å legge til matvarer, sjekke best-før datoer og oppdatere mengder. Jeg var også ansvarlig for å implementere enhetstester som sikret at programmet håndterte både vanlige og ekstreme tilfeller korrekt, som f.eks. utløpne best-før datoer.

## 4. Hvordan kan jeg bruke det jeg har lært i en jobb kontekst?

Det jeg har lært kan direkte anvendes i profesjonell programvareutvikling:
- **Objektorientert design** gir meg verktøy for å strukturere store, modulære systemer, som i webapplikasjoner eller programvare for kompleks databehandling.
- Jeg kan bruke **testdrevet utvikling** (TDD) for å utvikle robust kode og sikre at funksjonalitet alltid fungerer som forventet før implementering i produksjon.
- Kunnskap om **versjonskontroll (Git)** er uvurderlig når man jobber i team for å koordinere endringer og sikre at kode alltid kan rulles tilbake ved behov.

## 5. Læringsutbytte

### Kunnskap
- Objektorientert programmering (OOP): Prinsipper som innkapsling, modularisering og samhandling mellom objekter.
- Forståelse av lagdelt arkitektur og betydningen av god kodeorganisering.
- Kunnskap om god kodedesign, som kobling og kohesjon, og hvordan disse prinsippene gir mer robust og vedlikeholdbar kode.

### Ferdigheter
- Erfaring med OOP for å løse praktiske problemer.
- Bruk av profesjonelle verktøy som Git for versjonskontroll og testing for kodekvalitet.
- Evnen til å skrive robust kode, inkludert unntakshåndtering og feilsøking.

### Generell kompetanse
- Evnen til å anvende min kunnskap om OOP og programdesign til å løse praktiske programmeringsproblemer.
- Forståelse av hvordan man utvikler og leverer kode som kan brukes i en profesjonell programvareutviklingskontekst.
