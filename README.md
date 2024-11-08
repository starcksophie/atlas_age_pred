# Atlas-Based Interpretable Age Prediction In Whole-Body MR Images

## Overview

Age prediction is an important part of medical assessments and research. It can aid in detecting diseases as well as abnormal ageing by highlighting potential discrepancies between chronological and biological age. To improve understanding of age-related changes in various body parts, we investigate the ageing of the human body on a large scale by using whole-body 3D images. 
We utilise the Grad-CAM method to determine the body areas most predictive of a person's age. In order to expand our analysis beyond individual subjects, we employ registration techniques to generate population-wide importance maps that show the most predictive areas in the body for a whole cohort of subjects.
We show that the investigation of the full 3D volume of the whole body and the population-wide analysis can give important insights into which body parts play the most important roles in predicting a person's age. Our findings reveal three primary areas of interest: the spine, the autochthonous back muscles, and the cardiac region, which exhibits the highest importance. Finally, we investigate differences between subjects that show accelerated and decelerated ageing.

## Data

The code uses magnetic resonance imaging (MRI) data from the UK Biobank dataset. Due to data sharing agreements, the original UK Biobank data cannot be redistributed. It can, however be accessed upon registration [here](www.ukbiobank.ac.uk).

## Requirements

- Python 3.11.3
- Install required packages using the `requirements.txt` file:
  ```bash
  pip install -r requirements.txt
  ```

## Citation
```
  @article{melba:2024:029:starck,
    title = "Atlas-Based Interpretable Age Prediction In Whole-Body MR Images",
    author = "Starck, Sophie and Kini, Yadunandan Vivekanand and Ritter, Jessica J. M. and Braren, Rickmer and Rueckert, Daniel and Mueller, Tamara T.",
    journal = "Machine Learning for Biomedical Imaging",
    volume = "3",
    issue = "iMIMIC 2023 special issue",
    year = "2024",
    pages = "2247--2267",
    issn = "2766-905X",
    doi = "https://doi.org/10.59275/j.melba.2024-682e",
    url = "https://melba-journal.org/"
}
```
## Acknowledgements
This repo makes extensive usage of the VoxelMorph library: https://github.com/YaduKini/AgeFormer

## Contact

For any questions you can contact Sophie Starck (sophie.starck@tum.de).
