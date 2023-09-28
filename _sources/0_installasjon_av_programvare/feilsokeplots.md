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

# Feilsøking av Plots pakken i Julia

Det er flere som opplever problemer med Plots pakken i Julia, her er noen løsninger du kan prøve:

## 1. Oppdatering av Plots pakken

```{code-cell}
:tags: [remove-output]
using Pkg;
Pkg.update("Plots")
```

## 2. Slette Plots pakken og installere fra Github

```{code-cell}
:tags: [remove-output]
using Pkg;
Pkg.rm("Plots")
Pkg.pkg"add Plots#master"
```

## 3. Bruke Plotly backend i Plots

```{code-cell}
:tags: [remove-output]
using Plots;
plotly()
```

