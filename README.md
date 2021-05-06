# FID3 algorithm
Update of WDBC.zip (Breast cancer disease classification using fuzzy-ID3 algorithm with FUZZYDBD method: automatic fuzzy database definition). 

## Update of WDBC.zip
Actual source code of **WDBC.zip** in article paper: (**Breast cancer disease classification using fuzzy-ID3 algorithm with FUZZYDBD method: automatic fuzzy database definition**) 

-The actual code is given here:

1) The update for Supplemental file (source code): WDBC.zip. 

- Nevertheless, this code generates **similar** results with the non-updated code version (accidentally submitted to PeerJ CS), which the accuracy results averaging of the ten runs and above most commonly hit 94.534% (can be ± 0.250 depends on the runs due to not fixed random state value), and the same with precision, recall and f1-measure which the average runs can be ±0.250.

- **This code update information is for notification and studies purpose. Use this version :)**

-The use of the WDBC dataset is to show the ability of the method that capable of handling continuous data. Code:
[WDBC - Update.zip](https://github.com/farah96xxx/FID3algorithm/files/6430918/WDBC.-.Update.zip)


## Additional info about Coimbra.zip
- The code glucose.ipynb ->'low': [10.5, 60, 130.5],\n", suppose to be 'low': [-10.5, 60, 130.5],\n",. But this **doesnt affect** any membership value because actually no data ever hit lower than the peak of most left membership function: minimum value -> 60. The boundary just acts a control. As **no** membership value affected, so it **does not affect** the transformation of data at all. Hence, this does **not affect** anything.

## Code and data information

- Page 11 sentence suppose to be: The mean, standard error and worst (mean of three largest values reading) are computed for each features leading the dataset to have 32 attributes, including the non-predictive attribute, ID and the class attribute.

- All the given codes released are the prototypes. Updates of the codes are released here due to wrong folder submission before.

- All the acquired k-fold results are averaged over ten runs for every dataset to obtain the final result as this technique ensure stable results attain.

- The results (average between 10 runs and above) may be slightly different (in decimal places) received by the users for the given codes (WDBC-Update.zip, WBCD.zip, Coimbra.zip) due to non-fixed random state value nature. The random state (concept based on Sklearn) did not specify in this experiments, and the averaging results technique applied to prevent bias in the model's result. 

- Averaging runs of 10, 20, and 30 were carried out, but the method's results started to stabilize with just ten runs needed.

- All datasets gathered from UCI machine learning repository: https://archive.ics.uci.edu/ml/datasets.php

## Authors

Code and paper author - Nur Farahaina Idris (farahainaidris@gmail.com) 

Paper author- Mohd Arfian Ismail

Email the author (Nur Farahaina Idris) regarding the code or paper.
