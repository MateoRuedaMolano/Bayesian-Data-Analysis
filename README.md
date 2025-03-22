# Bayesian Data Analysis
**CS-E5710 @ Aalto University**
Final project for the Bayesian Data Analysis course by ** Aki Vehtari **

# Project: Perinatal and Neonatal Mortality Modeling 
📍 **Colombia vs USA//
This project models the probability of **perinatal and late neonatal mortality** across regions in **Colombia** and compares it with **U.S.** states, focusing on socioeconomically disadvantaged areas. The analysis uses a **beta-binomial model** to capture regional variation in mortality rates, based on epidemiological and infant death data from 2007–2020.
## Motivation
Neonatal and perinatal mortality remain critical indicators of healthcare quality and socio-economic disparities. This project aims to highlight patterns and differences in mortality rates between a developing country (Colombia) and a developed one (USA), emphasizing how poverty levels influence health outcomes.
## 📊 Data Sources
*	**Colombia:** Instituto Nacional de Salud (INS)
*	**USA:** CDC Wonder
*	**Time period:** {2007–2020} 
*	**Includes:** Epidemiological reports and infant death records
## Methodology
*	**Beta-binomial modeling** to estimate the probability of mortality events
*	Deaths treated as "successes", births as "trials"
*	Regional analysis across:
  *	32 Colombian departments
  *	50 U.S. States
## 📁 Files
| File | Description |
| -------- | ------- |
| project.Rmd |	💻 R code and analysis with inline comments |
| project.pdf |	📄 Full written report with modeling details |
| projectPresentation.pdf	| Slide deck summarizing key insights |
## How to Use
To understand the methodology and key findings:
*	**Start with projectPresentation.pdf** for a visual summary
*	Explore project.pdf for in-depth analysis of the models, experiments and results
*	Use project.Rmd to review the code and replicate the analysis
## 🔍 Key Insights
*	Higher perinatal and neonatal mortality rates are strongly associated with poorer regions in both countries
	The beta-binomial model captures regional heterogeneity and uncertainty better than simpler models (e.g. hierarchical).

