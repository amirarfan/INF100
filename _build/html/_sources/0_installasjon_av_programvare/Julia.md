---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.11.5
kernelspec:
  display_name: Julia 1.9.3
  language: julia
  name: julia-1.9
---

# Installasjon av Julia på din personlige PC

Denne guiden vil hjelpe deg med å installere Julia på din PC, enten du bruker Windows eller Mac.

## Før du starter

Før du begynner installasjonen, er det viktig å vite hvilken type datamaskin du har. Hvis du bruker en Mac, må du finne ut om den er basert på Apple Silicon eller Intel.

### Hvordan sjekke om din Mac er basert på Apple Silicon eller Intel:

1. Klikk på Apple-ikonet øverst til venstre på skjermen.
2. Velg "Om denne Macen".
3. Under "Oversikt" vil du se en "Prosessor" eller "Chip"-detalj. Hvis det står "Intel", har du en Intel-basert Mac. Hvis det står "Apple M1" eller lignende, har du en Apple Silicon-basert Mac.

```{image} ../images/m1mac.png
:alt: m1mac
:class: bg-primary mb-1
:width: 400px
:align: center
```

## Installasjon på Windows

1. Gå til Julia's offisielle nedlastingsside: [Julia Downloads](https://julialang.org/downloads/)
2. Under "Current stable release" klikk på "Windows" og last ned den anbefalte versjonen for ditt system (vanligvis 64-bit). 

```{image} ../images/julia_windows_64bit.png
:alt: julia_windows64bit
:class: bg-primary mb-1
:width: 400px
:align: center
```
3. Åpne den nedlastede filen og følg instruksjonene på skjermen for å installere Julia.

<div style="display: flex; justify-content: space-between;">

```{image} ../images/julia_installason_windows_0.png
:alt: julia_windows_0
:class: bg-primary mb-1
:width: 400px
:align: left
```

```{image} ../images/julia_installasjon_windows_1.png
:alt: julia_windows_1
:class: bg-primary mb-1
:width: 400px
:align: right
```
</div>


## Installasjon på Mac (Intel)

1. Gå til Julia's offisielle nedlastingsside: [Julia Downloads](https://julialang.org/downloads/)
2. Under "Current stable release" klikk på "macOS" og last ned den anbefalte versjonen for Intel Macs.
3. Åpne den nedlastede .dmg-filen.
4. Dra Julia-ikonet til Applications-mappen.

## Installasjon på Mac (Apple Silicon)

1. Gå til Julia's offisielle nedlastingsside: [Julia Downloads](https://julialang.org/downloads/)
2. Under "Current stable release" klikk på "macOS" og last ned den anbefalte versjonen for Apple Silicon Macs.
3. Åpne den nedlastede .dmg-filen.
4. Dra Julia-ikonet til Applications-mappen.

## Etter installasjon

Når du har installert Julia, kan du starte programmet fra startmenyen (Windows) eller Applications-mappen (Mac). Du må også følge guiden for å installere Visual Studio Code og Julia Extensionen.

Etter å ha startet programmet må du skrive inn følgende kode for å installere pakkene MAT og Pluto: 

** Husk å trykk enter** 

```{code-cell}
:tags: [remove-output]
using Pkg;
Pkg.add(["MAT", "Pluto"])
```

Lykke til med programmeringen i Julia!

> HUSK: Visual Studio Code guiden må også følges!
