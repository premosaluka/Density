# Breast density calculation using quantitive analysis of mammographic images 

## Abstract

### Purpose
Breast density is an important independent breast cancer risk factor.
Breast density reading is not a part of the standard screening examination due to
time considerations. Purpose of this project was to assess predictive power of computer
algorithms for breast density reading using quantitative analysis of mammographic
images. Our initial hypothesis was that raw images have higher predictive power
than processed images due to preserved information of x-ray attenuation in breast
tissue.

### Data and methods
We used 9252 pairs of raw and processed mamogramms
recorded by Siemens scanners and 4787 processed images recorder by Hologic scanners.
Images were part of the DORA (Slovenian Breast Cancer Screening Programme) data base. Breast segmentation and feature
generation were performed using LIBRA software. We used statistical methods oneway
ANOVA and mRMR for feature selection. Classifier was based on multinomial
logistic regression. Predictive power was assessed by calculating coefficient κ. Our
results were also compared to results from literature.

### Results
When classification to four density classes was performed, our algorithm
on processed images scored a κ = 0.65 (95% CI, 0.58-0.71) and our algorithm
on raw images a κ = 0.61 (95% CI, 0.58-0.71). When classification to dense/nondense
breasts was performed, our algorithm on processed images scored a κ = 0.56
(95% CI, 0.52-0.60) and on raw images a κ = 0.55 (95% CI, 0.51-0.60).

### Conclusion
We did not find any significant difference in predictive power between
raw and processed mammograms in our study. Our models scored comparable
κ values in comparison with results from literature where they assessed agreement
between radiologists. Missclassifications of our models were associated with dense
lesions and faulty segmentation of breast tissue and pectoral muscle.

## Data
We used 9252 pair of processed and raw mammograms from Slovenian Breast Cancer Screening Programme (DORA) database. For each patient we had 2 pairs of raw and processed images of same breast in CC and MLO views. Patients had density read only on one breast (either left or right). Breast density reading was performed only on images that were deamed suspicious. A futher diagnosis, however, found no cancer and patients were returned to DORA program. 

 



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/premosaluka/Density/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
