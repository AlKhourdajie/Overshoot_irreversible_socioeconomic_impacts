# Overshoot Impacts

*A Zenodo release and DOI will be added on publication.*

Scripts that generate the figures in the paper below. The figures are stylised illustrations of the paper's three-layer framework for assessing the consequences of temperature overshoot. They are not derived from empirical data or model output, and no external dataset is required to run them.

## Introduction

This repository contains the scripts that produce the figures in:

> Al Khourdajie, A., Andrijevic, M., Byers, E., Pathak, M., Pirani, A., Schleussner, C.-F., & Stuart-Smith, R. (2026). Overshoot pathways of 1.5°C: reversible biophysical change, irreversible socioeconomic impacts. Preprint, EarthArXiv. *[Add EarthArXiv DOI or URL.]*

The paper is under review at *Environmental Research Letters* (manuscript ERL-124808). This citation will be updated to the journal version on acceptance.

The paper proposes a three-layer framework distinguishing the hazard (the overshoot dimensions: magnitude, duration, rate of exceedance, and rate of decline), the biophysical response (reversible versus persistent change), and the socioeconomic outcome (reversible versus irreversible impact). It introduces the socioeconomic commitment threshold, the point beyond which cumulative overshoot effects commit socioeconomic losses that persist after temperatures decline. The figures illustrate this framework.

## Figures

The repository reproduces the two figures in the main text.

- **Figure 1** shows the three-layer framework: a stylised overshoot pathway and a permanent-exceedance counterfactual (hazard layer), post-peak biophysical response archetypes (biophysical layer), and divergent socioeconomic responses under differing adaptive capacity (socioeconomic layer).
- **Figure 2** shows the socioeconomic commitment threshold: illustrative S-curves giving the likelihood of crossing the threshold as a function of overshoot intensity, for systems of high, medium, and low adaptive capacity.

All curves are illustrative of qualitative behaviour. They are not empirical and not model output.

## Repository structure

*The layout below is a suggestion; replace the file names with the actual scripts once the repository is populated.*

- **`figure1_three_layer_framework`** produces Figure 1.
- **`figure2_commitment_threshold`** produces Figure 2.
- **`figures/`** holds the output figures.

Run the scripts to reproduce the figures.

## Requirements

*To complete: Python version and the key plotting packages (for example NumPy and Matplotlib), or a `requirements.txt` or `environment.yml` file that others can install from.*

## Citation

If you find this work useful, please cite the paper. Please do so also if you use the code or a variation of it.

> Al Khourdajie, A., Andrijevic, M., Byers, E., Pathak, M., Pirani, A., Schleussner, C.-F., & Stuart-Smith, R. (2026). Overshoot pathways of 1.5°C: reversible biophysical change, irreversible socioeconomic impacts. *Environmental Research Letters* (under review); preprint on EarthArXiv.

BibTeX:

```bibtex
@unpublished{AlKhourdajie2026_overshoot,
  author = {Al Khourdajie, Alaa and Andrijevic, Marina and Byers, Edward and Pathak, Minal and Pirani, Anna and Schleussner, Carl-Friedrich and Stuart-Smith, Rupert},
  title  = {Overshoot pathways of 1.5$^\circ$C: reversible biophysical change, irreversible socioeconomic impacts},
  year   = {2026},
  note   = {Preprint on EarthArXiv; under review at Environmental Research Letters}
}
```

## Acknowledgements

A.A.K. was supported by the European Union's Horizon Europe research and innovation programme under Grant Agreement No. 101081179 (DIAMOND). E.B. was supported by the European Union's Horizon Europe research and innovation programme under Grant Agreement No. 101081369 (SPARCCLE). R.F.S.-S. acknowledges funding from the Quadrature Climate Foundation and the Wellcome Trust Grant No. 309112/Z/24/Z (TACTIC).

## License

*To complete: add a licence so others know how they may use the code (for example MIT, BSD-3-Clause, or Apache-2.0), and include the corresponding LICENSE file.*

## Contact

For any question or feedback on the scripts, please get in touch: a.alkhourdajie@imperial.ac.uk (corresponding author).
