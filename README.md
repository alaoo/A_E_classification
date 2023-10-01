# A_E_classification
The Classification Problem
The datasets for this competition relate to Accident and Emergency activity. You're tasked with exploring this data and, as one component of the challenge, you must predict whether patients have been admitted i.e. Admitted_Flag is 1 (Admitted) or 0 (Not Admitted).

This will be scored based on Admitted_Flag field only.

The dataset
You will be given one data files (csv) to train your data

training_set
These relate to 100k patients.

After exploring this you must use it to build your classification model. You then apply the model to the other datafile to predict the whether the patient was admitted.

test_set (without the Admitted_Flag field)
You will notice this test dataset does not have a Admitted_Flag field. This is withheld so that we can compare against your predictions and measure your accuracy.


The answers you submit (whether for final or provisional) must only contain only the "Record_ID" field and the outcome field named "Admitted_Flag", populated with your predictions '1' or '0'. This is demonstrated by the 'example answer sheet'. You will have to make predictions for all 50k patients in the test set, so your file should resemble the 'skinny_unanswered_set' before you input your predictions.



Understanding the data
To understand the variable names, responses and many acronyms, most health datasets come with a supporting data dictionary. A data dictionary is available in the attached docs.

This data was created mainly from HES APC and HES A&E datasets, however it has gone through some minimisation and suppression, with some fields derived from elsewhere as well. This means you will need to approximate the definitions of some fields based on other codes and sets, and take the initiative to search for these yourself.

To help get you started here are some links that might prove useful:

https://en.wikipedia.org/wiki/ICD-10
https://www.datadictionary.nhs.uk/index.html
https://www.datadictionary.nhs.uk/supporting_information/main_specialty_and_treatment_function_codes_table.html
