# Twitter discourse reveals geographical and temporal variation in concerns about COVID-19 Vaccines in the United States.

A set of 100 COVID-19 vaccine-related topics derived from Twitter between December 2020 and February 2021. 

Read the full publication [here](https://authors.elsevier.com/sd/article/S0264-410X(21)00738-6). 

## Topics

There are two files in this data:

### covidVax100US_cp
This file is used to extract topic prevalence.

* `id`: auto-incremented numeric row id
* `term`: unigram in topic
* `category`: Numeric topic id (from 0 to 99)
* `weight`: Conditional probability of the topic given the unigram, as derived through the LDA process. 

### covidVax100US_freq_t50ll
This file is used to visualize top words in each topic.

* `id`: auto-incremented numeric row id 
* `term`: unigram in topic
* `category`: Numeric topic id (from 0 to 100)
* `weight`: Posterior likelihood

## Citation

Please cite the following paper if you use this data. 
Sharath Chandra Guntuku, Alison M. Buttenheim, Garrick Sherman, Raina M. Merchant, Twitter discourse reveals geographical and temporal variation in concerns about COVID-19 Vaccines in the United States, Vaccine, 2021,

```
@article{guntuku2021twittervaccine,
title = {Twitter discourse reveals geographical and temporal variation in concerns about COVID-19 Vaccines in the United States},
journal = {Vaccine},
year = {2021},
issn = {0264-410X},
doi = {https://doi.org/10.1016/j.vaccine.2021.06.014},
url = {https://www.sciencedirect.com/science/article/pii/S0264410X21007386},
author = {Sharath {Chandra Guntuku} and Alison M. Buttenheim and Garrick Sherman and Raina M. Merchant}
}
```

## Contact

Please contact sharathg [at] cis [dot] upenn [dot] edu with any questions.

## License

Licensed under a GNU General Public License v3 (GPLv3).
