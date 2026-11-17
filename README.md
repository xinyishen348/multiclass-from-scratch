# Multiclass Classification from Scratch

One-vs-Rest (OvR) and One-vs-One (OvO) multiclass classification built on
L2-regularized binary logistic regression, implemented from scratch with NumPy.
Our implementation reproduces scikit-learn's `OneVsRestClassifier` and
`OneVsOneClassifier` on the Palmer Penguins dataset.

DATA2060 Final Project, Brown University, Fall 2026.

## Repository structure

```
├── data/          Palmer Penguins dataset
├── src/           Report notebook (math overview, model, tests, sklearn comparison)
├── figures/       Figures used in the report and slides
├── environment.yml
├── LICENSE
├── README.md
├── presentation.pdf
└── report.pdf
```

## Reproducing the results

```bash
conda env create -f environment.yml
conda activate data2060
jupyter notebook src/final_project.ipynb
```

Developed with Python 3.14.7, NumPy 2.5.2, pandas 3.0.5, scikit-learn 1.9.0,
matplotlib 3.11.1 and pytest 9.1.1.

## Data

`data/penguins.csv` was exported from the `palmerpenguins` Python package
(Horst, Hill and Gorman, 2020): 344 penguins from three species (Adelie,
Chinstrap, Gentoo) with bill, flipper and body-mass measurements.

## Authors

- Xinyi Shen (xinyi_shen1@brown.edu)
- Xinyi Song (xinyi_song1@brown.edu)
- Yixin Zhang (yixin_zhang1@brown.edu)

## License

Released under the MIT License. See `LICENSE`.
