# Metabolomics_Seminar_Topic_10

From the paper entitled "Compendium of specialized metabolite biosynthetic diversity encoded in bacterial genomes"; the figures;

* FIGURE 1
    * A
    * B
    * C
* FIGURE 3
    * A
    * B
        * i
        * ii
        * iii
        * iv
* FIGURE 5
    * A
    * B
    * C
        * i
        * ii

This repository contains efforts to reproduce these figures from scratch. The dataset used in this study includes these resources from the paper;

* FIGURE 1 -- Table_1 [Source Data 1](https://static-content.springer.com/esm/art%3A10.1038%2Fs41564-022-01110-2/MediaObjects/41564_2022_1110_MOESM5_ESM.xlsx "Source Data 1").
* FIGURE 3 -- Table_3  [Source Data 3](https://static-content.springer.com/esm/art%3A10.1038%2Fs41564-022-01110-2/MediaObjects/41564_2022_1110_MOESM7_ESM.xlsx "Source Data 3").
* FIGURE 5 -- Table_5 [Source Data 5](https://static-content.springer.com/esm/art%3A10.1038%2Fs41564-022-01110-2/MediaObjects/41564_2022_1110_MOESM9_ESM.xlsx "Source Data 5").

## Installing Manually From Source

**This repository compiles under Python == 3.9.18, to install Python --> [pyenv](https://github.com/pyenv/pyenv)**

Clone the repository

```
git clone https://github.com/SinaBerkGolech/Metabolomics_Seminar_Topic_10.git --recursive
```

Create the Python virtual environment.  Install virtualenv first if needed with `python3 -m pip install virtualenv`.
```
cd Metabolomics_Seminar_Topic_10
virtualenv -p python3 metabolomics_seminar_env
source metabolomics_seminar_env/bin/activate
python3 -m pip install -U setuptools pip wheel
python3 -m pip install -U -r requirement.txt
```

> [1] Gavriilidou, A., Kautsar, S.A., Zaburannyi, N. et al. Compendium of specialized metabolite biosynthetic diversity encoded in bacterial genomes. Nat Microbiol 7, 726–735 (2022). (https://doi.org/10.1038/s41564-022-01110-2)

> [2] Allen M, Poggiali D, Whitaker K et al. Raincloud plots: a multi-platform tool for robust data visualization [version 2; peer review: 2 approved]. Wellcome Open Res 2021, 4:63 (https://doi.org/10.12688/wellcomeopenres.15191.2)

