# CA2
---
## Content
- [Problem Statement](https://github.com/stupidbutsmart/PDAS-CA2/edit/main/README.md#problem-statement)
- [Datasets](https://github.com/stupidbutsmart/PDAS-CA2/edit/main/README.md#datasets)
- [Working with Data](https://github.com/stupidbutsmart/PDAS-CA2/edit/main/README.md#ideas-on-working-with-data)
- [Usage](https://github.com/stupidbutsmart/PDAS-CA2/edit/main/README.md#usage)
- [Coding Standards/Rules](https://github.com/stupidbutsmart/PDAS-CA2/edit/main/README.md#rulesets)
---

## Problem Statement
Which industry allows fresh grads to develop the best?

---

## Datasets
1. [Mom Section I](https://stats.mom.gov.sg/Pages/employment-Tables2023.aspx)
  - Shows Job Stability / forward job potential
2. [Kaggle Corporate Work Life Balance](https://www.kaggle.com/datasets/ashaychoudhary/corporate-stress-dataset-insights-into-workplace)
  - Shows work culture based on corporate roles
3. [Kaggle Indeed Reviews Singapore Companies](https://www.kaggle.com/datasets/akbarazad/webscraping-indeedcom-singapore-company-reviews)
  - Shows work culture based on companies
---

## Ideas on Working with Data
### Salary
> Try to standardize salary to be by `month/hour`

### Industry
> Natural Language Process data

### Age
> Account for 23-37 years of age (range of typical graduate age from 2013)

### Worklife Balance
> Get keywords from company reviews

---

## Usage
Open a new folder in your terminal
```pwsh
mkdir PDAS_CA2
cd PDAS_CA2
```

Clone the repository
```pwsh
git clone https://github.com/stupidbutsmart/pookie
cd pookie
```

Pull from main branch
```pwsh
git checkout main
git pull origin main
```

Create a new branch for what you are working on
```pwsh
git checkout -b feature/<name of feature>
```

**When you create a new feature and want to commit**
```pwsh
git checkout feature/<name of feature>
git add .
git commit -m '<commit message>'
git push origin feature/<name of feature>
```

Go to repository to send a **Pull Request** _(PR)_

**How to sync with main**  
When changes are made in main, run the following code
```pwsh
git pull origin main
```
---

## Rulesets
- All features are to be written in `.ipynb` files
- The main `index.ipynb` file will be a notebook to show our analysis
- **ALL** function , variable names are to follow `snake_case`
- **ALL** classes are to follow `PascalCase`
- **ALL** class or object **constant attributes** are to follow `snake_case` with a trailing underscore `_`
- **ALL** identifiers are to be **verbose and meaningful** (no skibidi sigma)
- **DATASETS ARE TO BE STORED IN A DEDICATED `./Datasets` FOLDER**
