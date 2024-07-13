This work improves phishing detection on local websites in these countries
- Czech Republic (CZ)
- Denmark (DK)
- Estonia (EE)
- Croatia (HR)
- Hungary (HU)
- Lithuania (LT)
- Latvia (LV)
- Poland (PL)
- Romania (RO)
- Serbia (RS)
- Slovakia (SK)
- Slovenia (SI)

# Instructions to reproduce the results

1. Clone the repository

2. Install Jupyter notebook

3. Run notebook phishing-detection-language.ipynb

# Content

## Source code

[phishing-detection-language.ipynb](phishing-detection-language.ipynb) - Python source code

## Results

[result-raw](result-raw) - detailed phishing detection outcomes for each URL, organized by country

[result-figures](result-figures) - confusion matrices, word clouds, and analyses of false positives, categorized by country

[result-improved](result-improved) - webpages with refined phishing predictions

[result-reports](result-reports) - full phishing detection reports for each country

## Datasets

[benign-urls/urls-*country](benign-urls) - 2 million benign webpage URLs, categorized by country

[benign-urls/urls-GENERIC](benign-urls) - 1 million generic webpage URLs

[phishing-urls](phishing-urls) - 1 million phishing webpage URLs

# Acknowledgements

Benign URLs from [Common Crawl](https://commoncrawl.org/terms-of-use)

Phishing URLs from [Phishing.Database](https://github.com/mitchellkrogza/Phishing.Database)