# New_Inconel_Grades
Using ML to predict performance of new Inconel grades 

# Problem Statement:

To evaluate Machine Learning Models to predict SRR and MRR based on Chemical compositions, Voltage, Ton, Toff, Amperes. Since data is labelled, it is a Supervised Machine Learning. Moreover the predict vaiables are continuous and numeric so models applied, are of regression.

# Data:

### Features:
We had 23 independent variables, including 19 chemical compositions (Ni, Cr, Fe ...) and 4 measurements (Voltage, Ampere, Time On, Time off).

### Targets:
We had two target vaiables namely SRR and MRR.
SRR is the surface roughness meaured in micro meters.
MRR is the volumn of metal disintegrate per minute, measured in mm^3/min.


### Steps in Model Selection:

1) We applied 4 algorithms, among them RF yielded the best results.
2) We then cross validated(by keeping default parameters) all four algorithms and again RF was the best.
3) We tuned RF and 20 trees gave best results.
4) We cross validated RF with 20 trees.
5) We selected RF with 20 trees for final model testing.
6) We tested RF with 20 trees on the test dataset.
7) We retrained RF with 20 trees (But this time provided the whole dataset)
8) We took predictions on New Grades with RF 20.



###### More details on the documentation coming soon.
