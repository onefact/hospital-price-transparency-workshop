# hospital-price-transparency-workshop
Workshop on using natural language processing and deep learning applied to hospital price transparency data. 

## Day 1 of the workshop:

* recording: https://drive.google.com/drive/folders/1LNfvWzW3JMltGu1owV1830ko6SoDS1vi
* notebook: https://colab.research.google.com/drive/1L4QkgrOowrrQtC7jgVTv1p6DtFgpjXvx?usp=sharing
* whiteboard: https://app.excalidraw.com/l/1mBnVe9NaES/74OqBRSPJV9
* Dataframe we saved: https://github.com/onefact/hospital-price-transparency-workshop/blob/main/ohiohealth.com-out-of-pocket-estimates-31-4446959_obleness_standardcharges-xlsx-mapped-to-CMS-RVU-CPT-descriptions.csv

> Homework! Take a look at this file - and think about what health equity questions you might want to answer with it, or what datasets (like the census, or other things related to health equity/health outcomes / social determinants of health) we might be able to analyze concurrently - https://github.com/onefact/hospital-price-transparency-workshop/blob/main/ohiohealth.com-out-of-pocket-estimates-31-4446959_obleness_standardcharges-xlsx-mapped-to-CMS-RVU-CPT-descriptions.csv

Email your desired analyses to jaan@onefact.org.

## Day 2 of the workshop:

* notebook: https://colab.research.google.com/drive/1ko6z7Ypl2FXT3LK15AYArcZTYAL_QTPv?usp=sharing
* Dataframe we saved: https://github.com/onefact/hospital-price-transparency-workshop/blob/main/ohiohealth.com-out-of-pocket-estimates-31-4446959_obleness_standardcharges-xlsx-mapped-to-CMS-RVU-CPT-descriptions-with-vector-representations.csv

> Homework! * If you have taken or learned statistics: think about what methods you might use to predict hospital prices from count-valued random variables (like what we created in the vector representations of text)

> From a health equity point of view: what words, procedures, service classes (inpatient/outpatient/medication) would you expect to be correlated to a higher price? (Can we recover patterns we would expect from a health equity point of view from the machine learning model we will train tomorrow: for example, if outpatient procedures are unlikely to be covered by Medicare/Medicaid, are those more expensive?)

## Day 3 of the workshop:

* notebook: https://colab.research.google.com/drive/1nn59QGzuS6EVcQ6RgNWnfC7ETJFHLD7l?usp=sharing

> Homework! Fill in the pseudocode at the bottom of the notebook for implementing the two-layer neural network from scratch. Use the evaluation code we wrote (seeing how well the predicted price of a procedure matches the actual price) to predict hospital prices from their text descriptions. For bonus points, include the HCPCS description text we mapped the data to, which should improve the predictions (more data never hurts performance), or link the data to other datasets such as census info. 

Please email Jaan with any feedback from this workshop! jaan@onefact.org.
