# Bayesian Data Analysis
BDA - Aalto University
This repository contains the final project of the CS-E5710 Bayesian Data Analysis course taught by Aki Vehtari. 

# Perinatal and Neonatal Mortality Modeling (Colombia vs US)
This project models the probability of \textbf{perinatal and late neonatal mortality} across regions in \textbf{Colombia} and compares it with \textbf{U.S.} states, focusing on socioeconomically disadvantaged areas. The analysis uses a beta-binomial model to capture regional variation in mortality rates, based on epidemiological and infant death data from 2007–2020.
## Motivation
Neonatal and perinatal mortality remain critical indicators of healthcare quality and socio-economic disparities. This project aims to highlight patterns and differences in mortality rates between a developing country (Colombia) and a developed one (USA), emphasizing how poverty levels influence health outcomes.
## Data Sources
*	\textbf{Colombia:} Instituto Nacional de Salud (INS)
*	\textbf{USA:} CDC Wonder
*	\textbf{Time period:} {2007–2020} 
*	\textbf{Includes:} Epidemiological reports and infant death records
## Methodology
*	\textbf{Beta-binomial modeling} to estimate the probability of mortality events
*	Deaths treated as "successes", births as "trials"
*	Regional analysis across:
  *	32 Colombian departments
  *	50 U.S. States
## Files
*	project.Rmd: Code and analysis with embedded commentary
*	project.pdf: Full written report detailing data, modeling, and findings
*	projectPresentation.pdf: Slide deck summarizing the project
## How to Use
To understand the methodology and key findings:
*	\textbf{Start with projectPresentation.pdf} for a visual summary
*	Explore project.pdf for in-depth analysis of the models, experiments and results
*	Use project.Rmd to review the code and replicate the analysis
## Key Insights
*	Higher perinatal and neonatal mortality rates are strongly associated with poorer regions in both countries
	The beta-binomial model captures regional heterogeneity and uncertainty better than simpler models (e.g. hierarchical).

