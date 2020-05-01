# Predicting liver cytosol stability of small molecules

This is the official repository for the supporting information for the article '[Predicting liver cytosol stability of small molecules](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00426-7)', published at Journal of Cheminformatics.

## Abstract

Over the last few decades, chemists have become skilled at designing compounds that avoid cytochrome P (CYP) 450 mediated metabolism. Typical screening assays are performed in liver microsomal fractions and it is possible to overlook the contribution of cytosolic enzymes until much later in the drug discovery process. Few data exist on cytosolic enzyme-mediated metabolism and no reliable tools are available to chemists to help design away from such liabilities. In this study, we screened 1450 compounds for liver cytosol-mediated metabolic stability and extracted transformation rules that might help medicinal chemists in optimizing compounds with these liabilities. In vitro half-life data were collected by performing in-house experiments in mouse (CD-1 male) and human (mixed gender) cytosol fractions. Matched molecular pairs analysis was performed in conjunction with qualitative-structure activity relationship modeling to identify chemical structure transformations affecting cytosolic stability. The transformation rules were prospectively validated on the test set. In addition, selected rules were validated on a diverse chemical library and the resulting pairs were experimentally tested to confirm whether the identified transformations could be generalized. The validation results, comprising nearly 250 library compounds and corresponding half-life data, are made publicly available. The datasets were also used to generate in silico classification models, based on different molecular descriptors and machine learning methods, to predict cytosol-mediated liabilities. To the best of our knowledge, this is the first systematic in silico effort to address cytosolic enzyme-mediated liabilities.

## Links to files in supporting information

1. [Additional file 1](https://static-content.springer.com/esm/art%3A10.1186%2Fs13321-020-00426-7/MediaObjects/13321_2020_426_MOESM1_ESM.docx) - contains Additional figures and tables.
2. [Additional file 2](https://static-content.springer.com/esm/art%3A10.1186%2Fs13321-020-00426-7/MediaObjects/13321_2020_426_MOESM2_ESM.knwf) - contains MMPA KNIME workflow
3. [Additional file 3](https://static-content.springer.com/esm/art%3A10.1186%2Fs13321-020-00426-7/MediaObjects/13321_2020_426_MOESM3_ESM.xls) - contains External validation results
4. The input data for Additional file 2 can be found in this repo: `supporting_material/Input_MMP.csv`

## Contact

Should you have questions, please contact: Dac-Trung Nguyen (email: nguyenda@mail.nih.gov)