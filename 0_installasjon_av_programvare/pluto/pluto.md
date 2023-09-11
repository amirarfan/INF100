---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
---
# Introduksjon til Pluto Notebooks i Julia

Velkommen til en grunnleggende guide om hvordan du bruker Pluto notebooks i Julia via VSCode!

## Hva er Pluto?

Pluto er en interaktiv notebook for Julia programmeringsspråk. Med Pluto kan du skrive og kjøre Julia-kode i en interaktiv stil, noe som gjør det enkelt å eksperimentere, visualisere data og dele resultater.

## Hvorfor Pluto i dette faget?

- **Interaktivitet**: Pluto lar deg kjøre kodeblokker individuelt, noe som gir umiddelbar tilbakemelding.
- **Visualisering**: Enkelt å lage og vise grafer og data.
- **Dokumentasjon**: Kombiner kode, resultater og tekst i ett dokument.

## Sjekk om du har Pluto installert

Selv om du kanskje allerede har installert Pluto, la oss sørge for at alt er på plass:

1. Åpne VSCode.
2. Start Julia terminalen ved å trykke `Ctrl+J` og deretter `Ctrl+O` (for Windows) eller `Cmd+J` og deretter `Cmd+O` (for Mac).
3. Skriv inn følgende kommando:

```julia
using Pkg
Pkg.installed()["Pluto"]
```

Hvis du får en versjonsnummer tilbake, betyr det at Pluto er installert. Hvis ikke, følg neste trinn.

```julia
using Pkg
Pkg.add("Pluto") # Bemerk at add er med en liten a, alt er case-sensitivt.
```

## Starte Pluto fra VSCode

1. I Julia terminalen i VSCode, skriv:

```julia
using Pluto
Pluto.run()
```

Dette vil starte Pluto serveren, og en nettleserfane skal åpne med Pluto-grensesnittet.