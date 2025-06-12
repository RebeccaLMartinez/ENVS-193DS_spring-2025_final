# ENVS-193DS Final Project

## General Information

This repository contains the final project for **ENVS-193DS: Data Science in Environmental Studies**, completed by **Rebecca Martinez**.

This project explores several environmental data analysis tasks and includes a written reflection on statistical communication. The broad research questions include:

- How does agricultural runoff affect nitrogen load in the San Joaquin River Delta?
- What trends are visible in sea surface temperature from 2018 to 2023 in the Santa Barbara Channel?
- What environmental factors predict Swift Parrot nest box occupancy?

All analyses were conducted in R using Quarto, with version control tracked using Git and GitHub.

**Data sources include:**

- Santa Barbara Coastal Long Term Ecological Research (LTER)
- Stojanovic, Dejan et al. (2021). *Restoration Ecology* — [Dryad dataset](https://doi.org/10.5061/dryad.83bk3j9sb)
- Saleh, Dina and Joseph Domagalski. (2021). “Concentrations, Loads, and Associated Trends of Nutrients Entering the Sacramento–San Joaquin Delta, California.” *San Francisco Estuary and Watershed Science*. DOI: [10.15447/sfews.2021v19iss4art6](https://doi.org/10.15447/sfews.2021v19iss4art6)

---

## Data and File Information

### File Structure

```plaintext
ENVS-193DS-final/
├── README.md  
├── code/  
│   ├── ENVS-193DS-final.qmd  
│   ├── ENVS-193DS-final.html  
│   └── ENVS-193DS-final_files/  
├── data/  
│   ├── occdist.csv  
│   └── SST_update2023.csv  
```
### Description

**`/data/` folder**
- `occdist.csv`: Nest box occupancy data (Swift Parrots and competitors), from Stojanovic et al. (2021)
- `SST_update2023.csv`: Monthly sea surface temperature data from SBC LTER (2018–2023)

**`/code/` folder**
- `ENVS-193DS-final.qmd`: Main Quarto document containing all code, figures, and narrative
- `ENVS-193DS-final.html`: Rendered HTML report for easy viewing
- `ENVS-193DS-final_files/`: Automatically generated rendering support files

---

## Rendered Output

View the final rendered HTML document here:  
🔗 [ENVS-193DS-final.html](https://rebeccalmartinez.github.io/ENVS-193DS_spring-2025_final/code/ENVS-193DS_final.html)

---
