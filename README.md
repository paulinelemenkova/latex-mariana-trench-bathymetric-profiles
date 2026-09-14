# LaTeX / TikZ Bathymetric Cross-Profiles of the Mariana Trench

Reproducible **LaTeX** source (TikZ / pgfplots) that renders a series of
1000-km-wide bathymetric cross-profiles of the Mariana Trench directly from
tabular data, together with the compiled figures. A vector-quality, fully
typeset alternative to raster plotting of topographic and bathymetric profiles.

## Contents

- `1000kmProfile-*.tex`, `Profiles-*.tex` - TikZ / pgfplots profile definitions.
- `MyTab*.csv` - the 25 bathymetric data tables plotted by the profiles.
- `*.pdf` - the compiled profile figures.

## Technologies

LaTeX / TeX with TikZ and pgfplots; CSV data.

## Usage

Compile any profile `.tex` with `pdflatex` or `lualatex`, keeping the CSV tables
in the same folder. Plotting parameters in the `.tex` files control the styling.

## Author

**Polina Lemenkova**  
ORCID: https://orcid.org/0000-0002-5759-1089

## License

Released under the MIT License (see `LICENSE`).

## Citation & reuse

This repository accompanies the author's scientific work and is shared for open,
reproducible research. If you use the code, data or figures, please cite the
associated publication where applicable and link back to this repository and to
the author's ORCID.
