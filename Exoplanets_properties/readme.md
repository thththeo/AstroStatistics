This is a project in exploring a multivariate dataset of random variables. The steps taken in the analysis are as follows:

- 1) __Download dataset__ Obtain an ASCII multivariate dataset from The Extrasolar Planets Encyclopedia (http://exoplanet.eu/catalog.php (http://exoplanet.eu/catalog.php)). Select variables of interest of both the planet and host star

- 2) __Univariate analysis__ Present the mass distribution of known exoplanets. Consider stratifying by discovery method (radial velocity vs. transits). Try making pretty overlapping histograms with unsaturated colors from the ColorBrewer palette. [boxplot, hist, density]

- 3) __Bivariate analysis__ Examine the relationship between two interesting variables, perhaps semi-major vs. eccentricity or (for transiting planets) planet mass vs. planet radius. [plot, boxplot with cut or split, cor,
scatter.smooth/kde2d/ supersmu/loess/ash, lm/residual analysis]

- 4) __Prepare multivariate analysis__ Remove outliers and standardize variables. Add a new binary variable indicator for multiple planets. [boxplot, pairs, is.na. scale, cbind]

- 5) __Multivariate analysis__ Search for linear and nonlinear structure among the transiting planets. Reduce dimensionality: remove variables of no apparent interest, and create new linear combinations of variables. Choose a response variable for multiple regression. [princomp and plots, lm/plots, earth]

- 6) __Machine learning__ Try some modern methods for nonlinear dimensionality reduction and visualization such as Self-Organizing Maps, Isomap, diffusion maps, Local Linear Embedding, Stochastic Neighborhood Embedding. CRAN packages kohonen, dimRed, diffusionMap, etc.
