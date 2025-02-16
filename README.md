## Project

This code is written for a thesis for a masters degree in Computational Science at the UvA and VU.
The thesis is titled Multivariate Rough Volatility: Applications to Financial Risk
Management.
It expands on the seminal paper of Gatheral et al., Volatility is rough (2018).
The paper of Gatheral et al. found that volatility is much rougher than previous literature showed.
Previous literature used fractional Brownian motion (fBm) with a much higher Hurst parameter to simulate the volatility process.
In the paper of Jaber et al., Affine Volterra Processes (2019), a multivariate model is established based on Volterra Processes.
The code in this repository is based on Jaber et al., Markowitz portfolio selection for multivariate affine and quadratic Volterra models.

## Getting Started

### Prerequisites

This code base is written in Python 3.8.3 and up, except for the data cleaning which is written in R version 4.1.2.
For Python, other requirements such as packages, can be installed by entering the following command:

```
pip3 install -r requirements.txt
```

Or using conda:

```
conda install --file requirements.txt
```

The R code mainly relies on the highfrequency package.
Which can be installed through:
```
install.packages('highfrequency')
```

### Structure

The most important code, data and directories can be found below:

- **/Models**: contains the code for all the models.
  - **/README.md**: overview of different models used.
- **/Data**: contains the code to retrieve and clean the data.
  - **/Data.R**: cleans TAQ data from WRDS
  - **/Data.ipynb**: data cleaning and preperation
  - **/Results/: contains the results of the analysis
- **/Plots**: Contains all the figures used in the report.
  

### Author
- Sjoerd Dronkers
