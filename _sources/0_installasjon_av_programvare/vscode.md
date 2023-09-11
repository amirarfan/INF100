---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
---
# Installasjon av Visual Studio Code og Julia Extension

Denne guiden vil hjelpe deg med å installere Visual Studio Code (VS Code) og Julia Extension på din personlige datamaskin.

## Installere Visual Studio Code

### Windows:

1. Gå til [VS Code nedlastingsside](https://code.visualstudio.com/Download).
2. Klikk på "Windows" for å laste ned installasjonsfilen.
3. Åpne den nedlastede filen og følg instruksjonene på skjermen for å installere.

### Mac (Både Intel og Apple Silicon):

1. Gå til [VS Code nedlastingsside](https://code.visualstudio.com/Download).
2. Velg enten "Mac Universal" (for begge typer Mac) eller "Mac Intel" / "Mac ARM" basert på din Mac-type.
3. Etter nedlasting, åpne `.zip`-filen for å ekstrahere VS Code.
4. Dra VS Code-ikonet til "Programmer"-mappen på din Mac.

## Installere Julia Extension

1. Åpne Visual Studio Code.
2. Klikk på ikonet som ser ut som firkanter (extensions) på venstre side.

```{image} ../images/vscodeextension.png
:alt: vscodeextension
:class: bg-primary mb-1
:width: 200px
:align: center
```
3. Søk etter "Julia" i søkefeltet.

```{image} ../images/vscodejuliasearch.png
:alt: extensionsearch
:class: bg-primary mb-1
:width: 400px
:align: center
```

4. Klikk på "Install" på Julia extension som tilbys av "julialang".

```{image} ../images/julialang.png
:alt: extensionsearch
:class: bg-primary mb-1
:width: 400px
:align: center
```
5. Etter installasjonen er ferdig, vil du være klar til å begynne å kode i Julia i VS Code!

## Bruke Visual Studio Code for å Skrive og Kjøre Julia Kode

### Introduksjon til VS Code

Visual Studio Code er som et avansert tekstbehandlingsprogram (som Word), men det er designet for å skrive, redigere og kjøre kode. Det gir funksjoner som syntaksutheving, kodeutfylling og integrert terminal, noe som gjør det enklere å skrive og kjøre kode.

### Hvordan Opprette Kodefiler

1. Åpne VS Code.
2. Gå til "File" i menylinjen og velg "New File" (eller bruk hurtigtasten `Ctrl+N` på Windows, `Cmd+N` på Mac).
3. Lagre filen med en `.jl`-endelse for å indikere at det er en Julia-kodefil. Du kan gjøre dette ved å gå til "File" > "Save As" og deretter skrive inn et navn med `.jl`-endelsen (for eksempel `mitt_første_program.jl`).

### Hvordan Kjøre Kodefiler i Julia

1. Åpne den `.jl`-filen du har opprettet i VS Code.
2. Åpne en terminal i VS Code ved å gå til "View" > "Terminal" (eller bruk hurtigtasten `Ctrl+` ` på Windows, `Cmd+` ` på Mac).
3. I terminalen, skriv `julia` etterfulgt av mellomrom og filnavnet, og trykk Enter for å kjøre koden. For eksempel: `julia mitt_første_program.jl`.

### Starte Julia REPL i VS Code

REPL står for "Read-Eval-Print Loop", og det er et interaktivt programmeringsmiljø hvor du kan skrive og kjøre Julia-kode linje for linje.

1. Med VS Code åpen, trykk `Ctrl+Shift+P` (på Windows) eller `Cmd+Shift+P` (på Mac) for å åpne kommandopanelet.
2. Skriv "Julia" i søkefeltet som dukker opp, og velg "Start REPL" fra rullegardinlisten.
3. Dette vil åpne en ny terminal nederst i vinduet med Julia REPL kjørende.

### Kjøre Kode i Julia REPL

1. Skriv Julia-koden din i en `.jl`-fil i VS Code.
2. Marker koden du ønsker å kjøre.
3. Med koden markert, trykk `Ctrl+Enter` (på Windows) eller `Cmd+Enter` (på Mac) for å sende den markerte koden til Julia REPL og kjøre den.
4. Resultatet av koden vil vises i REPL-terminalen.


```{image} ../images/replexample.png
:alt: replexample
:class: bg-primary mb-1
:width: 400px
:align: center
```

Dette gir deg muligheten til å kjøre små biter av koden din interaktivt, noe som er spesielt nyttig for testing, feilsøking, eller når du utforsker nye biblioteker og funksjoner.

### Hvorfor Skrive Kode i en Editor og Utføre den i en Terminal

Når du skriver kode i en editor, kan du enkelt redigere, organisere og gjennomgå koden din før du kjører den. Dette gir deg muligheten til å strukturere koden din på en måte som er lett å forstå og vedlikeholde. 

Å utføre koden i en terminal gir deg muligheten til å se resultatene av koden din i sanntid, samt å interagere med koden din gjennom kommandolinjen. Dette er en vanlig praksis i programvareutvikling som gir en effektiv arbeidsflyt for å skrive, teste og feilsøke kode.

## Avsluttende tanker

Gratulerer! Du har nå installert Visual Studio Code og Julia Extension på din datamaskin, og har en grunnleggende forståelse av hvordan du bruker dem for å skrive og kjøre Julia-kode. Lykke til med kodingen!