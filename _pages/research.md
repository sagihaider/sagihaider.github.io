---
layout: single
title: "Research"
permalink: /research/
bibliography: references.bib
author_profile: true
---

My interest in Artificial Intelligence (AI) and Machine Learning begins when I was doing my BTech Degree at Integral University, Lucknow, India in the academic year 2007-2008. Since then I have been working on several areas of AI. The word cloud given below highlights the keywords related to my research directions. 

<!-- <img src="/images/wordcloud.png" width="600" align="center">  -->

<p align="center">
  <img width="600" height="600" src="/images/wordcloud.png">
</p>

The picture that changed my life is given below. The picture is from the book ``Artificial Intelligence: A Modern Approach`` by Stuart Russell and Peter Norvig. The first chapter of the book is an introduction to AI and I read it in 2007. I would say no one can explain it much better than this book.

<p align="center">
  <img width="500" height="500" src="/images/AI_4Pillars.png">
</p>

*** 
The following are my areas of research:


1. [EEG/MEG-based Brain-Computer Interfacing](#BCI)
2. [Healthcare and Predictive Analytics](#healthcare)
3. [Environmental Sciences and Agriculture](#env-agri)
4. [AI in Engineering and Architecture](#eng-arch)


*** 
**1. EEG/MEG-based Brain-Computer Interfacing <a name="BCI"></a>**

A major issue in bringing real-world applications of machine learning outside the laboratory is the difference in the data distributions between training and testing stages or domains. The diverging statistical properties in different domains can lead to decay the prediction performance. The technical term for a change in the distribution of features is covariate shift, which also happens to be a common challenge in electroencephalography (EEG) and Magnetoencephalography (MEG) based brain-computer interface (BCI); this is due to the presence of non-stationarities in the EEG/MEG signals. The non-stationary nature of EEG/MEG signals makes an EEG/MEG-based BCI a dynamic system, thus improving its performance is a challenging task. A lot of adaptive machine learning approaches have been developed and used previously to tackle this challenge such as passive and active approach for learning, domain adaptation, transfer learning, covariate shift minimization, deep learning, and more. I am particularly interested in developing methods for covariate shift adaptation in both EEG/MEG datasets. To visualize the covariate shift generally scatter plot and histogram are used. I am also interested in exploring new ways of analysing, visualizing, and measuring the covariate shift in data. 

<p align="center">
  <img width="600" height="250" src="/images/bci.jpg">
</p>

Here is a list of key publications:

* [Soft Computing, 2016](https://link.springer.com/article/10.1007/s00500-015-1937-5)
* [IEEE TCDS, 2017](https://ieeexplore.ieee.org/abstract/document/8239668)
* [IEEE JBHI, 2019](https://ieeexplore.ieee.org/abstract/document/8424844)
* [Neurocomputing, 2019](https://doi.org/10.1016/j.neucom.2018.04.087)
* [Scientific Data, Nature, 2021](https://doi.org/10.1038/s41597-021-00899-7)



*** 
**2. Healthcare and Predictive Analytics<a name="healthcare"></a>**

Healthcare analytics is the combination of data science and healthcare, where data analytics is used on healthcare data for offering insights into hospital management, patient records, costs, diagnoses, and more. The field covers a broad area of the healthcare industry, offering insights on both the macro and micro level. When combined with artificial intelligence and machine learning methods and data visualisation tools, healthcare analytics helps managers operate better by providing real-time information that can support decisions, predictive power, and deliver actionable insights. I am particularly interested in the following themes:


1. **Skin Cancer Detection (2022-2024)**: Secured £204,671.98 in research funding as the principal investigator (PI) from Innovate UK, in collaboration with Check4Cancer (UK), to develop a state-of-the-art AI engine for detecting melanoma-based skin cancer lesions. As part of this project, we have hired a post-doctoral researcher who is currently developing explainable Vision Transformers and other computer vision-based methods to launch a robust AI model within a mobile app, with a particular emphasis on minimizing false negatives. We have access to the Check4Cancer dataset, which consists of dermoscopic and digital images, along with metadata collected over the past two decades. The highlights of the project are available at the University of Essex webpages: [Blog 1](https://www.essex.ac.uk/research-projects/artificial-intelligence-for-diagnosis-of-skin-cancer) and [Blog 2](https://www.essex.ac.uk/news/2022/12/13/check4cancer-launches-skin-cancer-ai-project-with-the-university-of-essex).



2. **AI-assisted Patient Triaging in NHS (2017-2020)**: Secured £558,251.75 in research funding as the principal investigator (PI) from Innovate UK, in collaboration with Provide CIC, to develop the AI-Assisted Intelligent Triaging System for musculoskeletal services. In this research project, we designed, developed, and deployed the Smart Referral System, which provides several benefits to the company, including a significant reduction in clinician staff time and a highly efficient patient triage process. The project also contributed to the development of standardized referral pathways for 12 different clinical services. We have successfully completed the Provide CIC KTP project with several major contributions in AI-related healthcare. The KTP Project was able to adapt extremely successfully to the highly challenging conditions brought about by the global pandemic and the radical shift in care delivery. The developed novel AI-based architecture allows real-time patient triaging and directs them to appropriate clinical pathways accordingly. This has simultaneously reduced face-to-face appointments, which is crucial in the current conditions while providing patients with immediate access to self-management treatments. The creation of an entirely new approach to service delivery has revolutionized the clinical referral pathway, significantly reducing the time taken for triage decisions from weeks or months to just a few hours. All the required information is provided instantaneously to the key decision makers.The project has won several awards, which are given as follows:


    + Best Associate Award was secured by our post-doc (KTP associate: Dr Dheeraj Rathee) [Click here to read](https://www.essex.ac.uk/news/2021/10/21/essex-ktp-awards-2021)
    + I won the Best Academic Award for this project. [Click here to watch it on YouTube](https://www.youtube.com/watch?v=-7VJq4hC6cA).
    + Read the business case study [Click here to read](https://www.essex.ac.uk/business/expertise/case-studies/provide).
            

3. **Forensic Dentistry**: AI-driven algorithms have proven to outperform dentists in diagnosing tooth decay and predicting the need for tooth extraction, retention, or restorative treatment. I have collaborated with dentists from around the world, including Professor Akhilananda Chaurasia from the Department of Oral Medicine and Radiology at King George's Medical University, India, and Professor Rachel Sarig from the Goldschleger School of Dental Medicine, Sackler Faculty of Medicine, Tel Aviv University, Tel Aviv, Israel. We are working on a couple of research projects such as estimating the age and gender of living individuals using Molar teeth from OPG radiographs, collating first ever OPG dataset for mental foramen to be submitted in Scientific Data, and detecting and segmenting mental foramen from OPG radiographs. Our AI research focuses on various applications in dentistry, including periodontology, forensic dentistry, and dental radiography. The output from one of our research projects is submitted for publication in the Journal of Dentistry [@Raza2023].


* AI & data-driven SMART triage system 
* AI Pathway with an intelligent decision support system
* Technology and digital transformation for future healthcare
* Predictive Modelling using Electronic Health Records 

Here is a list of the projects:

* Computer Vision in Dentistry:

Radiography, intraoral scans, and facial scans often present dental practitioners with a quantity of overwhelming and unstructured data. AI-driven dental imaging solutions can help us to make an informed decisions quickly and efficiently. AI driven algorithms have proved to outperform dentists in diagnosing tooth decay or predicting whether a tooth should be extracted, retained, or have restorative treatment. We are focusing on a range of dentistry applications:

1. Periodontology
2. Forensic dentistry 
3. Dental radiography 


* AI-driven SMART Triage System [Provide CIC](https://www.provide.org.uk/)

We are working on a project that will enable Provide CIC to improve their current clinical triage process in terms of significant reduction of processing time and better decision making. Moreover, the product has been designed in a commercial environment, hence capable of generating significant revenue through sales as a service to other healthcare service providers. 

* Artificial Intelligence for Diagnosis of Skin Cancer with [Check4Cancer](https://www.check4cancer.com/)

Rates of [melanoma](https://en.wikipedia.org/wiki/Melanoma) and [non-melanoma](https://www.nhs.uk/conditions/non-melanoma-skin-cancer/) skin cancer have been rising significantly during the last three decades, and waiting times for assessment of a suspicious skin lesion are long in both the NHS and the private health sector in the UK. By developing artificial intelligence-based computer vision algorithms we can improve the early detection rate, which gives a better outcome for the patient, and means resources can be effectively managed for more serious cases. [To read more](https://www.essex.ac.uk/research-projects/Artificial-Intelligence-for-Diagnosis-of-Skin-Cancer)

* Predictors of objectively measured physical activity in 12‐month‐old infants

Physical activity (PA) levels are associated with long-term health, and levels of PA when young are predictive of adult activity levels. We examined factors associated with PA levels in 12-month infants. 141 mother-infant pairs were recruited via a longitudinal birth cohort study (April 2010 to March 2013) at Wales. The PA level was collected using accelerometers and linked to postnatal notes and electronic medical records via the Secure Anonymised Information Linkage databank. Univariable and multivariable linear regressions were used to examine the factors associated with PA levels. We founds that the PA levels of infants were strongly associated with both gestational and postnatal environmental factors. Healthy behaviours appear to cluster, and a healthy diet was associated with a more active infant. Boys were substantially more active than girls, even at age 12 months. These findings can help inform interventions to promote healthier lives for infants and to understand the determinants of their PA levels. [To read more](https://doi.org/10.1111/ijpo.12512)

*** 
**3. Environmental Sciences and Agriculture<a name="env-agri"></a>**

Advances in AI could be one of the solutions to solving major global environmental crises--from climate change to agriculture. With advances in machine learning and deep learning, we can now tap the predictive power of AI to make better data-driven models of environmental processes to improve our ability to study current and future trends, including forest-fire, water availability, crop-monitoring, and ecosystems wellbeing. I am interested in bringing AI and ML to play a key role in enhancing environmental decision and policy-making work, by bringing algorithmic solutions to the following themes:

* Developing forest-fire prediction algorithm using IoT
* Image analysis for monitoring crops 

[Highlights](http://sagihaider.github.io/files/ForestFire.pdf), 2020

*** 
**4. AI in Engineering and Architecture<a name="eng-arch"></a>**

<p align="center">
  <img width="600" height="250" src="/images/layout.gif">
</p>

Construction is one of the oldest professions as people have been building shelters and structures for millennia. However the industry has evolved quite a bit in the way they design, plan, and build structures. For decades, technology has been used in the construction industry to make jobs more efficient and construction projects and structures safer. In recent years, construction companies have increasingly started using AI in a range of ways to make construction more efficient and innovative. From optimizing work schedules to improving workplace safety to keeping a secure watch on construction facilities, AI in the construction industry is already proving its value. Construction managers have been finding value with AI and cognitive technologies to help automate many of the mundane but essential tasks to running their operations. They are finding AI helpful with scheduling related tasks in order to prevent delays, conflicts, and other issues. This is both on the staff level of scheduling and on the project and materials side. Keeping this in mind, we have recently collaborated with [Mersea Homes](https://www.merseahomes.co.uk/) using Knowledge Transfer Partnership. The company are currently operating an outdated paper system for creating, communicating and updating site plans. The intention of this project is to develop an intelligent digital system using the combined expertise of IoT and data science specialists which can provide our site workers with real-time live updates to project plans using embedded sensors and smart phones receiving personalised live updates from our centralised server. Data-sharing will be based on an intelligent system driven by a machine learning algorithm, which will learn and anticipate which contractors and staff need particular information.

