# Peng Li — CV for Blykalla

Application for **Senior Thermohydraulic Analyst**, Fluid Systems Engineering, Stockholm.

- [CV (PDF)](Peng_Li_CV_Blykalla.pdf)
- [Editable LaTeX source](Peng_Li_CV_Blykalla.tex)
- [Official vacancy](https://careers.blykalla.com/jobs/8428493-senior-thermohydraulic-analyst)

The application emphasises conservation-based transient models, heat transfer, 0-D/3-D code coupling, OpenFOAM, scientific programming, parameter studies, and verification and validation. Nuclear system codes and reactor-specific safety methods are presented as development areas.

Ph.D. defence is scheduled for 4 December 2026. Swedish level is A2. The CV separates published papers from unpublished manuscripts.

Build with a standard TeX Live or MiKTeX installation:

```sh
pdflatex -interaction=nonstopmode -halt-on-error Peng_Li_CV_Blykalla.tex
pdflatex -interaction=nonstopmode -halt-on-error Peng_Li_CV_Blykalla.tex
```

[Previous CorPower application](https://github.com/PengLi2810/CV/blob/main/Peng_Li_CV_CorPower.pdf)

The CV uses the supplied A4, 10-point layout and defaults to no photo. To enable the optional photo, supply `me.jpg` and change `\withphotofalse` to `\withphototrue`.
