# COVID-19-Images-Classification

The purpose of this repository is to review different approaches to COVID-19 images classification problem.

## Notebook COVID19_3D_NIfTI_images_classification.ipynb: 

The dataset of human lung CT scans in NIfTI format with and without COVID-19 findings was used in this project;  
Data were obtained between 1st of March, 2020 and 25th of April, 2020, and provided by municipal hospitals in Moscow, Russia.
There are 1110 studies in dataset:
Population: 1110 persons, males – 42%, females – 56%, other/unknown – 2%; age from 18 to 97 years, median – 47 years. 
Current experiment is using a subset of this dataset:
*  CT-0 file without Covid-19 findings (100 cases);
*  CT-23 file with Covid-19 findings (100 cases);

More information on the dataset is available at [this link](https://mosmed.ai/en/datasets/covid19_1110/) and at [this link](https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1);
The complete dataset is available for download at the [following link](https://mosmed.ai/datasets/сgovid19_1110/).
3D images classification problem solution is implemented as 3D CNN with data augmentation (rotation).
#### Reference:
"3D Image Classification from CT Scans" implementation by Hasib Zunair at the [following link](https://keras.io/examples/vision/3D_image_classification/);

