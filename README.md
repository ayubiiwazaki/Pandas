# Pandas code

this my project to upskill and grow my skill

## Table of Contents

- [Introduction](#introduction)
- [Files](#files)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

this my project to upskill and grow my skill

## Files

- **.ipynb**: Jupyter Notebook file containing the Pandas code.
- **csv,excel**: Dataset file used in the project.


## Usage

explore,sorting data ,filtering data.all that use for analys and gain insight from data set.


![image](https://github.com/ayubiiwazaki/Pandas/assets/139350745/2165c216-2c64-40ee-945d-66d7e8458d84)
```bash
df2 = df.groupby("Continent")['1970 Population',
       '1980 Population', '1990 Population', '2000 Population',
       '2010 Population', '2015 Population', '2020 Population',
       '2022 Population'].mean().sort_values (by="2022 Population",ascending=False)

