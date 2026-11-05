# Peng Li — CV for FOI

Application for **Forskare inom undervattensakustik med inriktning mot modellering**, reference **FOI-PERS-2026-1039**, Stockholm–Kista.

- [CV (PDF)](Peng_Li_CV_FOI.pdf)
- [Editable LaTeX source](Peng_Li_CV_FOI.tex)
- [Vacancy](https://foi.easycruit.com/vacancy/3675433/12384)

The CV follows the supplied A4, 10-point template and emphasises acoustic modelling, CFD, and fluid–structure interaction. It states the scheduled defence date of 4 December 2026 and Swedish level A2, and lists unpublished manuscripts separately from journal publications.

Build with a standard TeX Live or MiKTeX installation:

```sh
pdflatex -interaction=nonstopmode -halt-on-error Peng_Li_CV_FOI.tex
pdflatex -interaction=nonstopmode -halt-on-error Peng_Li_CV_FOI.tex
```

The default is the version without a photo. To enable the optional photo, supply `me.jpg` and change `\withphotofalse` to `\withphototrue`.
