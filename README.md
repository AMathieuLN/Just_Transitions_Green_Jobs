# Replication Code for: "Thinking Just Transitions in the Global South: Quantification Challenges for Green Job Policies"

## Description

This repository accompanies the publication "Thinking Just Transitions in the Global South: Quantification Challenges for Green Job Policies" by Alexandre Mathieu and Yanis Rihi.

***Contacts :***

Alexandre Mathieu :

-   [alexandre.mathieu\@universite-paris-saclay.fr]{.underline}

-   <https://amathieuln.github.io/CV_AM/>

Yanis Rihi :

-   [yanis.rihi\@universite-paris-saclay.fr]{.underline}

-   <https://www.umi-source.uvsq.fr/m-yanis-rihi>

## Project Structure

```{r}
Just_Transitions_Green_Jobs/
├── data/
│   ├── JTS_SP.xlsx       # Raw data for JTS scores
│   ├── IV.rds            # Country identification variables
│   ├── WDI_GDPPC.xlsx    # GDP per capita data
├── outputs/
│   ├── JTS_SP_IV.rds            # Merged data (JTS and IV)
│   ├── JTS_SP_IV_GDPpc.rds      # Merged data with GDP per capita
│   ├── scatter_plot.png         # Graph 1: Quadratic relationship between JTS and GDP per capita
│   ├── boxplot_with_outliers_fr.png  # Graph 2: Boxplot of outliers
│   ├── trend_plot_fr.png        # Graph 3: JTS evolution by country
├── requirements.R        # List of required packages for the project
├── README.md             # Detailed documentation
└── JT_GJ.Rproj           # RStudio project file
```

## Prerequisites

Ensure that the latest versions of R and RStudio are installed on your system.

## Steps for Replication

1.  From your RStudio "Terminal," clone the repository:

-   First, type: *git clone https://github.com/AMathieuLN/Just_Transitions_Green_Jobs.git*

-   Then: *cd Just_Transitions_Green_Jobs*

2.  Open the **JT_GJ.Rproj** file in RStudio.

3.  Run the **requirements.R** script to install dependencies. You can do this directly in the console:

```{r}
source("requirements.R")
```

4.  Execute the analyses by following the scripts, available in your language of choice, within the "script/" folder.

5.  Transformed files and generated graphs are saved in the "outputs/" folder.

6.  Each graph is saved in PNG format, ready for use in publications.
