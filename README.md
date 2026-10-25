# BIO 3352 Bioinformatics II: Student Files

This repository holds the Google Colab notebooks for the lab activities of BIO 3352 (Bioinformatics II: Protein Structure, Prediction, and Simulation) at New York City College of Technology, CUNY. The course pages, book chapters and lab instructions are on the [BIO 3352 OER site](https://openlab.citytech.cuny.edu/bio3352-oer/).

Open a notebook with its link below. Colab opens your own copy, so your changes do not affect anyone else. Choose File, Save a copy in Drive if you want to keep your work.

| Module | Lab activity | Notebook |
|---|---|---|
| 5 | [Building and evaluating homology models of myoglobin](https://openlab.citytech.cuny.edu/bio3352-oer/lab-activity-5/) | [Open in Colab](https://colab.research.google.com/github/Mai-Zahran/BIO3352-Bioinformatics-II-ForStudents/blob/main/contents/module5/notebooks/lab_activity5.ipynb) |
| 6 | [Predicting structures with ColabFold](https://openlab.citytech.cuny.edu/bio3352-oer/lab-activity-6/) | [Open in Colab](https://colab.research.google.com/github/Mai-Zahran/BIO3352-Bioinformatics-II-ForStudents/blob/main/contents/module6/notebooks/lab_activity6_colabfold.ipynb) |
| 7 | [Simulating ubiquitin with GROMACS](https://openlab.citytech.cuny.edu/bio3352-oer/lab-activity-7/) | [Open in Colab](https://colab.research.google.com/github/Mai-Zahran/BIO3352-Bioinformatics-II-ForStudents/blob/main/contents/module7/notebooks/lab_activity7.ipynb) |

## Before you run a notebook

- Read the lab page first. The notebook has the code; the page has the steps, the checks and the questions.
- Labs 6 and 7 need a GPU: Runtime, Change runtime type, T4 GPU.
- Lab 5 needs your own Modeller license key, from [salilab.org/modeller/registration.html](https://salilab.org/modeller/registration.html). Paste it only in the first cell and never share a notebook that contains it.

## Sources and license

The notebooks of Labs 5 and 7 follow the lab pages of the BIO 3352 OER. Their Modeller and GROMACS installation cells and the GROMACS parameter files are adapted from the [IBM3202 course notebooks](https://github.com/pb3lab/ibm3202) (PB3 Lab, Pontificia Universidad Cat&oacute;lica de Chile, MIT License).

The Lab 6 notebook is a copy of the public [ColabFold](https://github.com/sokrypton/ColabFold) v1.6.3 notebook (MIT License, see `contents/module6/notebooks/COLABFOLD_LICENSE.txt`), with the horse myoglobin sequence and the job name filled in. Please cite M. Mirdita and others, ColabFold: making protein folding accessible to all, *Nature Methods* 19, 679 (2022).

"Bioinformatics II: Protein Structure, Prediction, and Simulation" OER by Mai Zahran is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Funded in part by the CUNY OER Initiative.
