# VizieR-Stellar-Catalog-2
This project conducted exploratory data analysis, luminosity calculations, stellar classification, and machine learning modeling on astronomical data to gain insights into celestial objects and demonstrate the efficacy of data-driven techniques in astronomy.

# VizieR : Stellar Classification Dataset

#### About Dataset
###### Context
Stellar Classification uses the spectral data of stars to categorize them into different categories. The modern stellar classification system is known as the Morgan–Keenan (MK) classification system. It uses the old HR classification system to categorize stars with their chromaticity and uses Roman numerals to categorize the star’s size.
In this Dataset, we will be using Absolute Magnitude and B-V Color Index to Identify Giants and Dwarfs.

https://vizier.cds.unistra.fr/

##### Acknowledgements
###### Vizier
This research has made use of the VizieR catalogue access tool, CDS, Strasbourg, France (DOI: 10.26093/cds/vizier). The original description of the VizieR service was published in A&AS 143, 23
The Hipparcos and Tycho Catalogues (ESA 1997)

#### Citing
If you use this repository in your research, consider citing it using the following Bibtex entry:

@misc{Ku_KaggleStellar,

    author={Wing-Fung Ku},

    title={Star Categorization Giants And Dwarfs Dataset, vinesmsuic},

    month={Jul},

    year={2020}

We have a dataset with several columns related to stellar properties. Here's a breakdown of each column based on the information you've provided:

1. **Vmag:** This likely stands for "Visual Magnitude," which is a measure of the brightness of a star as seen from Earth in the visible spectrum.

2. **Plx:** This could represent "Parallax," which is a measurement of the apparent shift in a star's position due to Earth's orbit around the Sun. It's used to calculate distances to stars.

3. **e_Plx:** This might be the uncertainty or error associated with the parallax measurement (Plx).

4. **B-V:** This refers to the "Color Index," specifically the difference in magnitude between a star's brightness in blue (B) and visual (V) wavelengths. It's often used to estimate a star's temperature and classify its spectral type.

5. **SpType:** This stands for "Spectral Type," which is a classification system that categorizes stars based on their spectral characteristics, such as the absorption lines present in their spectra.

6. **Amag:** This could represent "Absolute Magnitude," which is the apparent magnitude a star would have if it were placed at a standard distance of 10 parsecs (32.6 light-years) from Earth. It's a measure of a star's intrinsic brightness.

7. **TargetClass:** This column likely indicates the target class or category to which each star belongs. This could be based on specific criteria or classifications related to stellar properties or behaviors.
