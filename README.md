# Awesome Pain Intensity Classification Papers
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
<!-- ![Stars](https://img.shields.io/github/stars/zhenyuanlu/awesome-pain-intensity-classification-papers)
[![Visits Badge](https://badges.pufler.dev/visits/zhenyuanlu/awesome-pain-intensity-classification-papers)](https://badges.pufler.dev/zhenyuanlu/awesome-pain-intensity-classification-papers) -->
<!-- ![Forks](https://img.shields.io/github/forks/zhenyuanlu/awesome-pain-intensity-classification-papers) -->

(to be updated)

### A comprehensive list of pain intensity classification papers and the dataset used.

#### Any contribution is welcome!

## Latest Review/Survey papers
Year | Topic
------------ | -------------
2023  | [Review and Analysis of Pain Research Literature through Keyword Co-occurrence Networks](https://journals.plos.org/digitalhealth/article?id=10.1371/journal.pdig.0000331)<br>*Plos Digital Health*
2023 | [Artificial Intelligence for Automatic Pain Assessment: Research Methods and Perspectives](https://onlinelibrary.wiley.com/doi/full/10.1155/2023/6018736)<br>*Pain Research and Management*
2021 | [Pain and Stress Detection Using Wearable Sensors and Devices—A Review](https://www.mdpi.com/1424-8220/21/4/1030/htm) <br>*sensors*|
2021 | [Machine Learning in Pain Medicine: An Up-To-Date Systematic Review](https://link.springer.com/article/10.1007/s40122-021-00324-2) <br>*Pain and Therapy*| 
2020 | [Sensor Technologies to Manage the Physiological Traits of Chronic Pain: A Review](https://www.mdpi.com/1424-8220/20/2/365) <br>*sensors*| 
2020 | [Innovations in Electrodermal Activity Data Collection and Signal Processing: A Systematic Review](https://www.mdpi.com/1424-8220/20/2/479)<br>*sensors* | EDA
2019  | [Automatic Recognition Methods Supporting Pain Assessment: A Survey](https://ieeexplore.ieee.org/document/8865626) <br/> *IEEE Transactions on Affective Computing*
2018 | [A Review of Automated Pain Assessment in Infants: Features, Classification Tasks, and Databases](https://ieeexplore.ieee.org/abstract/document/8120021?casa_token=vlTu8ZNya2cAAAAA:1lVPRHsReLitOUv33Eyz2LQomFrskQwKLoE-w7op_c3u3sdCcJFgLYlT4vMmDJE-mSQjxvivlSY)  <br/> *IEEE Reviews in Biomedical Engineering*



## Pain Classification Papers

Year | Topic | Model | Signal | Dataset 
------- | ------- | ------- | ------- | ------- 
2023 | [Transformer Encoder with Multiscale Deep Learning for Pain Classification Using Physiological Signals](https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2023.1294577/full) <br> *Frontiers in Physiology* | Transformer Encoder+Temporal Conv+SEResNet; <br> Code: [github](https://github.com/zhenyuanlu/PainAttnNet)  | EDA | BioVid |
2022 | [Personalized Deep Bi-LSTM RNN Based Model for Pain Intensity Classification Using EDA Signal](https://www.mdpi.com/1424-8220/22/21/8087)<br>*sensors*  | BiLSTM + XGBoost  | EDA  | Proprietary Dataset: Cold Pain Data  |  
2022 | [Tree-Based Models for Pain Detection from Biomedical Signals](https://link.springer.com/chapter/10.1007/978-3-031-09593-1_14)<br>*ICOST 2022*  | AdaBoost, XGBoost, TabNet, Random Forest (RF) | EDA,ECG | BioVid | 
2021 | [Multi-Modal Pain Intensity Assessment Based on Physiological Signals: A Deep Learning Perspective](https://www.frontiersin.org/articles/10.3389/fphys.2021.720464/full) <br> *Frontiers in Physiology* | Self-supervised Learning, Auto-Encoder | EMG + ECG + EDA | BioVid; SenseEmotion | 
2021 | [Automated Nociceptive Pain Assessment Using Physiological Signals and a Hybrid Deep Learning Network](https://ieeexplore.ieee.org/document/9194710)  <br> *IEEE Sensors Journal*  | CNN + LSTM | EDA, ECG |BioVid; Proprietary Dataset: Real-time Data  | 
2021 | [Comparison of Feature Extraction Methods for Physiological Signals for Heat-Based Pain Recognition](https://www.mdpi.com/1424-8220/21/14/4838) <br> *sensors*| MLP | EDA | BioVid | 
2021 | [Pain Recognition With Electrocardiographic Features in Postoperative Patients: Method Validation Study](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8196363/) <br>*JMIR*| ADABoost, XGBoost, random forest, SVM, KNN |ECG |BioVid as baseline; UCI_iHurtDB |
2021  | [Exploration of physiological sensors, features, and machine learning models for pain intensity estimation](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0254108)<br>*PLOS ONE*  | SVM  | EDA | BioVid   | 
2021 | [Objective Pain Assessment Using Wrist-based PPG Signals: A Respiratory Rate Based Method](https://ieeexplore.ieee.org/abstract/document/9630002)<br>*EMBC* | ADABoost, XGBoost, random forest, SVM, KNN |PPG | UCI_iHurtDB |
2021 | [Machine learning suggests sleep as a core factor in chronic pain](https://journals.lww.com/pain/fulltext/2021/01000/machine_learning_suggests_sleep_as_a_core_factor.10.aspx?casa_token=rhg7opmfjzoAAAAA:kS04Z1pUWEpjuhkEDKcBstA31CrxlXLLIbcyzmTRduH4r_lN6NFCFuFzGOkuuW6Xasgvib1xOFWqPii7khZDlw) <br>*Pain* | CART, PART, RF |  Mul-Sources Parametes |  Proprietary Dataset: chronic pain, Finland|
2021 | [Assessment of thoracic pain using machine learning: a case study from Baja California, Mexico](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7926745/)<br>*Environmental Research and Public Health* | Tree classification, RF, SVM, Logistic regression, kNN | AMI	and FRCV Six Factors| Proprietary Dataset: Thoracic Pain |
2021 | [Prediction of breakthrough pain during labour neuraxial analgesia: comparison of machine learning and multivariable regression approaches](https://www.sciencedirect.com/science/article/abs/pii/S0959289X20301151?casa_token=jXEcGgvqyE8AAAAA:5XiqzTZmAbo9OiHdEB4jI75HTYoaDZIwt0DCCiX4jygCaN1NwLLkB4ff7BDI_7MlvNkHGIk323c) <br>*Obstetric Anesthesia* | RF, XGBoost, Logistic Regression | Medical Record  | Proprietary Dataset: breakthrough pain during labour, Singapore|
2020  | [Hybrid RNN-ANN Based Deep Physiological Network for Pain Recognition](https://ieeexplore.ieee.org/abstract/document/9175247)<br>*EMBC 2020*  | BiLSTM  | EDA, ECG, EMG  | BioVid  | 
2020 | [Pain phenotypes classified by machine learning using electroencephalography features](https://www.sciencedirect.com/science/article/pii/S1053811920307424) <br>*NeuroImage* | SVM | EEG, VAS | Proprietary Dataset: Chronic lumbar pain | 
2020 | [Machine-learning-based knowledge discovery in rheumatoid arthritis-related registry data to identify predictors of persistent pain](https://journals.lww.com/pain/fulltext/2020/01000/machine_learning_based_knowledge_discovery_in.13.aspx?casa_token=EwPFUNHkjFYAAAAA:j21Y3hnnx7ajXLCmkzGtcKpJe6gtAyFvST30vjN3QIArI0n4k-MDzce_hP1YdOuVqBlEBGI2gFnSRyLUMBvbuw) <br>*Pain* | CART, kNN, MLP, SVM, Naive Bayes | Multi-sources Parameters | Proprietary Dataset: Rheumatoid arthritis |
2020  | [Diverse frequency band-based convolutional neural networks for tonic cold pain assessment using EEG](https://doi.org/10.1016/j.neucom.2019.10.023) <br> *Neurocomputing* | CNN | EEG | Proprietary Dataset: Cold Pain Data | 
2020 | [Using a motion sensor to categorize nonspecific low back pain patients: a machine learning approach](https://scholar.google.com/scholar_lookup?title=Using%20a%20motion%20sensor%20to%20categorize%20nonspecific%20low%20back%20pain%20patients%3A%20a%20machine%20learning%20approach&journal=Sensors&doi=10.3390%2Fs20123600&volume=20&issue=12&publication_year=2020&author=Abdollahi%2CM&author=Ashouri%2CS&author=Abedi%2CM) <br>*sensors* | SVM, MLP |Trunk kinematic data | Propritary Dataset: Nonspecific low back pain |
2020 | [Identifying predictive factors for neuropathic pain after breast cancer surgery using machine learning](https://www.sciencedirect.com/science/article/pii/S1386505619311554) <br>*International Journal of Medical Informatics* | RF, Linear Regression, Elastic Net, Ridge Regression, Gradient Boosting, Neural Net | Questionnaires before and after surgery  | [Prospective Cohort Study](https://www.sciencedirect.com/topics/nursing-and-health-professions/prospective-cohort-study), Neuropathic pain|
2020 | [Interpretable machine learning models for classifying low back pain status using functional physiological variables](https://link.springer.com/article/10.1007/s00586-020-06356-0) <br>*European Spine Journal* |Functional Data Boosting (FDboost) | EMG | Proprietary Dataset: Low Back Pain |
2020  | [Diverse frequency band-based convolutional neural networks for tonic cold pain assessment using EEG](https://doi.org/10.1016/j.neucom.2019.10.023) <br> *Neurocomputing* | CNN | EEG | Proprietary Dataset: Cold Pain Data | 
2020 | [Medical expert system for low back pain management: design issues and conflict resolution with Bayesian network](https://link.springer.com/article/10.1007/s11517-020-02222-9) <br>*Medical & Biological Engineering & Computing* | Bayes  | Clinical Records | Proprietary Dataset: Low back pain|
2019 | [Feature extraction and selection for pain recognition using peripheral physiological signals](https://www.frontiersin.org/articles/10.3389/fnins.2019.00437/full) <br> *Frontiers in Neuroscience* | SVM | EMG, SCL, ECG | BioVid |
2019 | [Predicting inadequate postoperative pain management in depressed patients: a machine learning approach](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0210575) <br>*Plos ONE* | Elastic Net, NLP (NegEx) | 65 predictive features from EHR | Proprietary Dataset: EHR |
2019 | [Exploring Deep Physiological Models for Nociceptive Pain Recognition](https://www.mdpi.com/1424-8220/19/20/4503) <br> *sensors* | CNN | EDA, ECG  | BioVid | 
2019  | [A Deep Neural Network-Based Pain Classifier Using a Photoplethysmography Signal](https://www.mdpi.com/1424-8220/19/2/384)  <br> *sensors* | Deep Belief Network, MLP, SVM | PPG | Proprietary Dataset: Pre-/Post-operation of Surgery   | 
2019  | [Acute pain intensity monitoring with the classification of multiple physiological parameters](https://link.springer.com/article/10.1007/s10877-018-0174-8) <br> *Journal of Clinical Monitoring and Computing* | MLP | HR, BR, GSR, EMG | Proprietary Dataset: Heat and Electrical Stimuli | 
2019 | [Machine learning-based prediction of clinical pain using multimodal neuroimaging and autonomic metrics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6377310/) <br> *Pain* | SVM | Neuroimages  | Proprietary Dataset: Chronic Low Back Pain | 
2019 | [Exploring Deep Physiological Models for Nociceptive Pain Recognition](https://www.mdpi.com/1424-8220/19/20/4503) <br> *sensors* | CNN | EDA, ECG  | BioVid | 
2019  | [Acute pain intensity monitoring with the classification of multiple physiological parameters](https://link.springer.com/article/10.1007/s10877-018-0174-8) <br> *Journal of Clinical Monitoring and Computing* | MLP | HR, Breath Rate, GSR, EMG | Proprietary Dataset, HR, BR, GSR, Facial | 
2019 | 	[A joint deep neural network model for pain recognition from face](https://ieeexplore.ieee.org/abstract/document/8821779) <br> *ICCCS 2019* | RNN+VGGFace CNN | Facial Images | UNBC-McMaster Shoulder Pain |
2018 | [Deep Multimodal Pain Recognition: A Database and Comparison of Spatio-Temporal Visual Modalities](https://ieeexplore.ieee.org/document/8373837) <br>*FG 2018* | CNN+LSTM | RGBDT (RGB, Depth, Thermal) | Multimodal Intensity Pain (MIntPAIN) |
2018 | [Continuous Pain Intensity Estimation from Autonomic Signals with Recurrent Neural Networks](https://ieeexplore.ieee.org/abstract/document/8513575?casa_token=6heJe82tPUYAAAAA:wrd62Nde2jJ6nS_i-KEfpF5lI7fqLinKc4At1SgZRM-xAHV1r6Adc5I5B_eSjAHg8lHj09DLsz8)<br>*EMBCC 2018* | LSTM-NN| EDA, HR | BioVid
2018 | [Deep learning model for detection of pain intensity from facial expression](https://link.springer.com/chapter/10.1007/978-3-319-94523-1_22) <br>*ICOST 2018*| BiLSTM-CNN-VSL-CRF | Facial Expressions | - |
2018 | [Improving pain management in patients with sickle cell disease from physiological measures using machine learning techniques](https://www.sciencedirect.com/science/article/pii/S2352648317300727?casa_token=eOG5Q_GEbIUAAAAA:JrDR3_nnZzl_AkB9c6x1-kzsPmEjBlWRRSixh3FoKDrBfnwnbBIjfWg1HMhMonNdrE4Mrp_zzkc)<br>*Smart Health* | RF, kNN, SVM, Multinomial logistic regression | Peripheral capillary oxygen saturation, systolic blood pressure, diastolic blood pressure, heart rate, respiratory rate, temperature   | Proprietary Dataset: SCD patients, Duke Hospital|
2017 | [Prediction effects of personal, psychosocial, and occupational risk factors on low back pain severity using artificial neural networks approach in industrial workers](https://www.sciencedirect.com/science/article/pii/S0161475416301440?casa_token=ehnZMh2tcWEAAAAA:5eBmlLVs2CtHNNhUW6x07RDeQNiHsX6IoWT4TEp8NTbKkKQDfdQZCOPPx-FsxT4YyF0pjyZaZi8)<br>*Manipulative and Physiological Therapeutics* | MLP, kNN, Logistic Regression | BVP, ECG, SCL | Proprietary Dataset: Low back pain|
2017  | [Multi-task neural networks for personalized pain recognition from physiological signals](https://ieeexplore.ieee.org/abstract/document/8272611)<br>*ACIIW 2017*  | MLP  | EDA, ECG  | BioVid  | 
2017 | [Physiological Signal-Based Method for Measurement of Pain Intensity](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5445136/) <br>*Front Neurosci.* | KNN, SVM, LDA | BVP, ECG, SCL | Proprietary Dataset: Electrical stimulation | 
2017  | [Multi-task neural networks for personalized pain recognition from physiological signals](https://ieeexplore.ieee.org/abstract/document/8272611)<br>*ACIIW 2017*  | MLP  | EDA, ECG | BioVid  | 
2015  | [Multimodal Data Fusion for Person-Independent, Continuous Estimation of Pain Intensity](https://link.springer.com/chapter/10.1007/978-3-319-23983-5_26)<br>*EANN 2015*  | Random Forest  | EDA, ECG, EMG, Videos | BioVid  |
2014  | [Automatic Pain Recognition from Video and Biomedical Signals](https://ieeexplore.ieee.org/abstract/document/6977497)<br> *International Conference on Pattern Recognition*  | Random Forest  | EDA, ECG, EMG, Videos  | BioVid  | 



<!-- &plusmn; -->


## Datasets Mentioned Above 
Year | Name | Dataset
------------ | ------------- | ------------
2005 | Infant database: COPE/iCOPE | http://www.brahnam.info/papers/EN2031.pdf
2011 | UNBC-McMaster Shoulder Pain | http://www.jeffcohn.net/Resources/
2013  | BioVid Heat Pain Database| https://www.nit.ovgu.de/BioVid.html
2016  | PPG Signals  | http://cris.nih.go.kr Registration Number: KCT0002080 https://cris.nih.go.kr/cris/search/detailSearch.do/6638
2017  | SenseEmotion | -
2018 | Multimodal Intensity Pain (MIntPAIN) | https://vap.aau.dk/mintpain-database/

## Other Public Pain Databases Collection
[List of Publicly Available Pain Recognition Databases](https://github.com/philippwerner/pain-database-list)  Collected by Philipp Werner.


<br>
<br>

## License

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
