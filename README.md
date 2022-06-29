# Bioinformatics Project
 
# Predicting Cis Regulatory Regions in HepG2 Cells

This project aims to design a good experimental setup for a classification problem. The project focuses on learning how to design a model and train it to predict the regulatory regions in the cell.

## Dataset

- [hg38 UCSC Genome Browser](https://genome.ucsc.edu/)
- [HepG2 Using Epigenomic_dataset](https://github.com/AnacletoLAB/epigenomic_dataset)

The project should be run in order from 1 to 4.

Since the epigenomes folder created by the code is too big to upload to GitHub, it can be acces using [this](https://drive.google.com/drive/folders/1H5HEQRTwYOrFAwnBe-81G8zjFOUuPro8?usp=sharing) link.

## Tests

```bash 
# 1. Retrieving_Information.ipynb
test_drop_costant_features (__main__.Test) ... ok
test_knn (__main__.Test) ... ok

----------------------------------------------------------------------
Ran 2 tests in 84.363s

OK
<unittest.main.TestProgram at 0x7fdab4e29840>
```
```bash 
# 3.Data_Visualization.ipynb
test_get_pca_decomposition (__main__.Test) ... ok
test_get_tsne_decomposition (__main__.Test) ... ok

----------------------------------------------------------------------
Ran 2 tests in 10.875s

OK
<unittest.main.TestProgram at 0x7f263e2e3670>
```
