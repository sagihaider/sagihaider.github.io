---
layout: page
permalink: /research/
title: research
description: Different areas of my research
nav: true
nav_order: 4
---
My passion for Artificial Intelligence (AI) and Machine Learning sparked during my BTech Degree at Integral University, Lucknow, India, in the academic year 2007-2008. Since then, I have delved into various facets of AI. The word cloud presented below showcases the key themes and keywords encapsulating my research endeavors.

<!-- <img src="/assets/img/wordcloud.png" width="400" align="center">  -->

<p align="center">
  <img width="800" height="600" src="/assets/img/wordcloud.png">
</p>

The picture that changed my life is given below. The picture is from the book ``Artificial Intelligence: A Modern Approach`` by Stuart Russell and Peter Norvig. The first chapter of the book is an introduction to AI and I read it in 2007. I would say no one can explain it much better than this book.

***
The methodological contributions are given as follows:

1) **Domain Adaptation**: In the domain of machine learning, my focus has been on the convoluted field of Domain Adaptation, where I have contributed by developing innovative learning methods. The primary objective has been to develop models with the capability to adeptly navigate and adjust to non-stationary environments, effectively addressing the challenges posed by changing distributions. This involves creating adaptive mechanisms that allow the model to dynamically evolve and refine its understanding based on shifts in data patterns, ensuring robust performance across diverse scenarios. By delving into the intricacies of domain adaptation, my work strives to enhance the adaptability of machine learning models, making them more resilient and versatile in the face of evolving datasets and real-world fluctuations. <!-- [UKCI'14] , [BIBM'14], [IJCNN_1'15], [IJCNN_2'15], [SC'15], [IJCNN'16], [TCDS'17], [NC'18], [IJCNN'19], [IJCNN_1'20], [IJCNN_2'20]. 
 -->

2) **Change/Shift Detection**: My significant focus has been directed towards the development of a robust Change/Shift Detection method, a critical component in the domain of data analysis. This method is specifically designed to effectively identify covariate shifts within datasets, functioning seamlessly in both online and retrospective modes. The key objective is to create a sophisticated algorithm that can dynamically recognize alterations in the distribution or characteristics of the data, whether in real-time or during a retrospective analysis. This innovation contributes to the realm of adaptability in machine learning systems, ensuring that models are equipped to detect and respond to shifts in data patterns, thereby maintaining optimal performance across various scenarios. By addressing the challenges of covariate shift detection, my work aims to enhance the reliability and accuracy of machine learning models, making them more adept at navigating the dynamic nature of real-world data environments. <!-- [SMC'13](https://sagihaider.com/publication/2013_06_IEEE_SMC), [AIAI'13](https://sagihaider.com/publication/2013-06-EWMA_Springer), [PR'15](https://sagihaider.com/publication/2015_04_EWMA_Pattern_Recognition) -->

3) **Vision Transformers (ViTs)**: In the pursuit of advancing computer vision methodologies, my research has been centred around the development of innovative techniques for Vision Transformers (ViTs). Specifically, my focus extends beyond conventional practices that heavily rely on pre-trained ImageNet weights. Instead, I am actively engaged with my PhD students in the designing and implementation of methods to train lightweight ViTs from scratch. This approach not only aims to reduce reliance on generic pre-trained weights but also tailors the model to be more resource-efficient and adaptable to specific domains. Furthermore, recognizing the critical significance of healthcare imaging data, I am directing efforts towards the creation of a specialized ViTs model exclusively tailored for the complexities of medical imaging. This involves a detailed exploration of the unique characteristics and challenges posed by healthcare datasets, ensuring that the model is finely tuned to extract meaningful insights and patterns relevant to medical diagnostic applications. The overarching goal of this research is to contribute to the evolution of vision transformers, making them more versatile, domain-specific, and resource-efficient, particularly in the context of crucial domains such as healthcare.

*** 
The following are my areas of Applied AI research:

1. [EEG/MEG-based Brain-Computer Interfacing](#BCI)
2. [Healthcare and Predictive Analytics](#healthcare)
3. [Environmental Sciences and Agriculture](#env-agri)
4. [AI in Engineering and Architecture](#eng-arch)

*** 
**1. EEG/MEG-based Brain-Computer Interfacing <a name="BCI"></a>**

A major issue in bringing real-world applications of machine learning outside the laboratory is the difference in the data distributions between training and testing stages or domains. The diverging statistical properties in different domains can lead to decay the prediction performance. The technical term for a change in the distribution of features is covariate shift, which also happens to be a common challenge in electroencephalography (EEG) and Magnetoencephalography (MEG) based brain-computer interface (BCI); this is due to the presence of non-stationarities in the EEG/MEG signals. The non-stationary nature of EEG/MEG signals makes an EEG/MEG-based BCI a dynamic system, thus improving its performance is a challenging task. A lot of adaptive machine learning approaches have been developed and used previously to tackle this challenge such as passive and active approach for learning, domain adaptation, transfer learning, covariate shift minimization, deep learning, and more. I am particularly interested in developing methods for covariate shift adaptation in both EEG/MEG datasets. To visualize the covariate shift generally scatter plot and histogram are used. I am also interested in exploring new ways of analysing, visualizing, and measuring the covariate shift in data. 

<p align="center">
  <img width="600" height="250" src="/assets/img/bci.jpg">
</p>

Here is a list of key projects:

1. *EEG-based BCI*: EEG-based Brain-Computer Interface (BCI) is a technology that enables direct communication between the brain and external devices by interpreting and decoding electroencephalogram (EEG) signals. It allows users to control devices or applications using their brain activity, bypassing traditional motor pathways. However, there are several challenges in transitioning this technology from the laboratory to real-world applications, including signal quality and variability, spatial and temporal resolution, feature extraction, inter-subject variability, dataset and covariate shift, calibration, and training on non-stationary datasets. To address these challenges, I have made significant contributions to the field. Firstly, I helped develop a covariate shift detection test {% cite raza2015ewma %} and an adaptive learning algorithm {% cite raza2016adaptive %} to adapt to non-stationary datasets. Additionally, I proposed a novel framework, the covariate shift estimation-based adaptive ensemble learning, to handle non-stationarity in motor imagery-related EEG-based BCI {% cite raza2019covariate %}. The online BCI system developed through this research is still actively used by the BCI lab at Ulster University. Furthermore, I conducted an evaluation of four methods for frequency band selection in binary motor imagery classification, namely forward-addition (FA), backward-elimination (BE), the intersection, and the union of FA and BE. These methods automatically select and learn the most discriminative sets of frequency bands and their corresponding Common Spatial Pattern (CSP) features. The findings from this study were published in the proceedings of IEEE-IJCNN 2015 {% cite raza2015optimising %}. Through my research, I have made significant contributions to advancing the field of EEG-based Brain-Computer Interface technology, addressing key challenges, and developing novel methodologies. I won the best literature review award sponsored by McGraw Hill during my PhD degree at the Univerisity of Ulster. 

2. *MEG-based BCI*: MEG has several advantages over EEG. First, MEG provides more precise spatial localization of neural activity since magnetic fields are less distorted by the skull and scalp compared to electrical signals. Second, MEG has a higher temporal resolution, capturing neural activity in real-time with millisecond accuracy. Third, MEG is less susceptible to artifacts from muscle movements and has a better signal-to-noise ratio. MEG systems are expensive and hence MEG datasets are not readily available for researchers to develop effective and efficient BCI-related signal processing algorithms. In 2021, we released 306-channel MEG-BCI data recorded at 1KHz sampling frequency during four mental imagery tasks (i.e. hand imagery, feet imagery, subtraction imagery, and word generation imagery). The dataset contains two sessions of MEG recordings performed on separate days from 17 healthy participants using a typical BCI imagery paradigm. The recorded  dataset is the only publicly available MEG imagery BCI dataset as per our knowledge. The dataset can be used by the scientific community towards the development of novel pattern recognition machine learning methods to detect brain activities related to motor imagery and cognitive imagery tasks using MEG signals. This work was published in Scientific Data, Nature in 2021 {% cite rathee2021magnetoencephalography %}. Additionally, I collaborated with neuroscientists from the Basque Centre on Cognition, Brain and Language, Donostia/San Sebastian, Spain; Basque Foundation for Science, Bilbao, Spain; and Justus-Liebig-Universität Gießen, Gießen, Germany to decode numeracy and literacy in the Human Brain and we found that numbers are represented stronger single letters, but a string of letters is represented stronger than a string of numbers. The work has been accepted for publication in Scientific Report, Nature {% cite nara2022decoding %}.
        
3. **Stroke Rehabilitation**: The aim of the study was to design a BCI-operated neuro-rehabilitation system that would ensure recovery of the patient's finger motions so that the patients can get back their independence in performing their activities of daily life and improve their quality of life. We proposed a novel algorithm Cortico-Muscular-Coupling (CMC) {% cite chowdhury2019eeg %} and implemented it with covariate Shift Adaptation based BCI system for Personalized Neuro-Rehabilitation of Stroke Patients {% cite chowdhury2017online %}. With my team members at IIT-Kanpur, India, we have conducted experiments on $10$ healthy and $10$ stroke subjects. The activities involved in this project are the development of a CMC-based single-trial EEG classification method for decoding user intentions, a novel method for feature extraction using correlation in EEG and EMG signals, conducting experiments on healthy subjects \& stroke subjects, deriving results from the analysis, and finally, the impact on the patient {% cite chowdhury2018active %} to recover the motor activities. 

ey Publication in BCI and Neural Engineering:

*** 
**2. Healthcare and Predictive Analytics<a name="healthcare"></a>**

Healthcare analytics is the combination of data science and healthcare, where data analytics is used on healthcare data for offering insights into hospital management, patient records, costs, diagnoses, and more. The field covers a broad area of the healthcare industry, offering insights on both the macro and micro level. When combined with artificial intelligence and machine learning methods and data visualisation tools, healthcare analytics helps managers operate better by providing real-time information that can support decisions, predictive power, and deliver actionable insights. I am particularly interested in the following themes:


1. **Skin Cancer Detection (2022-2024)**: Secured £204,671.98 in research funding as the principal investigator (PI) from Innovate UK, in collaboration with Check4Cancer (UK), to develop a state-of-the-art AI engine for detecting melanoma-based skin cancer lesions. As part of this project, we have hired a post-doctoral researcher who is currently developing explainable Vision Transformers and other computer vision-based methods to launch a robust AI model within a mobile app, with a particular emphasis on minimizing false negatives. We have access to the Check4Cancer dataset, which consists of dermoscopic and digital images, along with metadata collected over the past two decades. The highlights of the project are available at the University of Essex webpages: [Blog 1](https://www.essex.ac.uk/research-projects/artificial-intelligence-for-diagnosis-of-skin-cancer),  [Blog 2](https://www.essex.ac.uk/news/2022/12/13/check4cancer-launches-skin-cancer-ai-project-with-the-university-of-essex), and Winner of the Best Partnership Award in 2024 [YouTube](https://www.youtube.com/watch?v=Ht4YC6A_TRA&pp=ygUnQ2hlY2s0Q2FuY2VyIEJlc3QgUGFydG5lcnNoaXAgS1RQIEVzc2V4).



2. **AI-assisted Patient Triaging in NHS (2017-2020)**: Secured £558,251.75 in research funding as the principal investigator (PI) from Innovate UK, in collaboration with Provide CIC, to develop the AI-Assisted Intelligent Triaging System for musculoskeletal services. In this research project, we designed, developed, and deployed the Smart Referral System, which provides several benefits to the company, including a significant reduction in clinician staff time and a highly efficient patient triage process. The project also contributed to the development of standardized referral pathways for 12 different clinical services. We have successfully completed the Provide CIC KTP project with several major contributions in AI-related healthcare. The KTP Project was able to adapt extremely successfully to the highly challenging conditions brought about by the global pandemic and the radical shift in care delivery. The developed novel AI-based architecture allows real-time patient triaging and directs them to appropriate clinical pathways accordingly. This has simultaneously reduced face-to-face appointments, which is crucial in the current conditions while providing patients with immediate access to self-management treatments. The creation of an entirely new approach to service delivery has revolutionized the clinical referral pathway, significantly reducing the time taken for triage decisions from weeks or months to just a few hours. All the required information is provided instantaneously to the key decision makers.The project has won several awards, which are given as follows:


    + Best Associate Award was secured by our post-doc (KTP associate: Dr Dheeraj Rathee) [Click here to read](https://www.essex.ac.uk/news/2021/10/21/essex-ktp-awards-2021)
    + I won the Best Academic Award for this project. [Click here to watch it on YouTube](https://www.youtube.com/watch?v=-7VJq4hC6cA).
    + Read the business case study [Click here to read](https://www.essex.ac.uk/business/expertise/case-studies/provide).
            

3. **Forensic Dentistry**: AI-driven algorithms have proven to outperform dentists in diagnosing tooth decay and predicting the need for tooth extraction, retention, or restorative treatment. I have collaborated with dentists from around the world, including Professor Akhilananda Chaurasia from the Department of Oral Medicine and Radiology at King George's Medical University, India, and Professor Rachel Sarig from the Goldschleger School of Dental Medicine, Sackler Faculty of Medicine, Tel Aviv University, Tel Aviv, Israel. We are working on a couple of research projects such as estimating the age and gender of living individuals using Molar teeth from OPG radiographs, collating first ever OPG dataset for mental foramen to be submitted in Scientific Data, and detecting and segmenting mental foramen from OPG radiographs. Our AI research focuses on various applications in dentistry, including periodontology, forensic dentistry, and dental radiography. The output from one of our research projects is submitted for publication in the Journal of Dentistry {% cite raza2017identification %}.


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


* AI-driven SMART Triage System [Provide CIC](https://providecommunity.org.uk/)

We are working on a project that will enable Provide CIC to improve their current clinical triage process in terms of significant reduction of processing time and better decision making. Moreover, the product has been designed in a commercial environment, hence capable of generating significant revenue through sales as a service to other healthcare service providers. 

* Artificial Intelligence for Diagnosis of Skin Cancer with [Check4Cancer](https://www.check4cancer.com/)

Rates of [melanoma](https://en.wikipedia.org/wiki/Melanoma) and [non-melanoma](https://www.nhs.uk/conditions/non-melanoma-skin-cancer/) skin cancer have been rising significantly during the last three decades, and waiting times for assessment of a suspicious skin lesion are long in both the NHS and the private health sector in the UK. By developing artificial intelligence-based computer vision algorithms we can improve the early detection rate, which gives a better outcome for the patient, and means resources can be effectively managed for more serious cases. [To read more](https://www.essex.ac.uk/research-projects/Artificial-Intelligence-for-Diagnosis-of-Skin-Cancer)

* Predictors of objectively measured physical activity in 12‐month‐old infants

Physical activity (PA) levels are associated with long-term health, and levels of PA when young are predictive of adult activity levels. We examined factors associated with PA levels in 12-month infants. 141 mother-infant pairs were recruited via a longitudinal birth cohort study (April 2010 to March 2013) at Wales. The PA level was collected using accelerometers and linked to postnatal notes and electronic medical records via the Secure Anonymised Information Linkage databank. Univariable and multivariable linear regressions were used to examine the factors associated with PA levels. We founds that the PA levels of infants were strongly associated with both gestational and postnatal environmental factors. Healthy behaviours appear to cluster, and a healthy diet was associated with a more active infant. Boys were substantially more active than girls, even at age 12 months. These findings can help inform interventions to promote healthier lives for infants and to understand the determinants of their PA levels {%cite }

*** 
**3. Environmental Sciences and Agriculture<a name="env-agri"></a>**

Advances in AI could be one of the solutions to solving major global environmental crises--from climate change to agriculture. With advances in machine learning and deep learning, we can now tap the predictive power of AI to make better data-driven models of environmental processes to improve our ability to study current and future trends, including forest-fire, water availability, crop-monitoring, and ecosystems wellbeing. I am interested in bringing AI and ML to play a key role in enhancing environmental decision and policy-making work, by bringing algorithmic solutions to the following themes:

* Developing forest-fire prediction algorithm using IoT
* Image analysis for monitoring crops 

<!-- [Highlights](http://sagihaider.github.io/files/ForestFire.pdf), 2020 -->

*** 
**4. AI in Engineering and Architecture<a name="eng-arch"></a>**

<!-- <p align="center">
  <img width="600" height="250" src="/images/layout.gif">
</p> -->

Construction is one of the oldest professions as people have been building shelters and structures for millennia. However the industry has evolved quite a bit in the way they design, plan, and build structures. For decades, technology has been used in the construction industry to make jobs more efficient and construction projects and structures safer. In recent years, construction companies have increasingly started using AI in a range of ways to make construction more efficient and innovative. From optimizing work schedules to improving workplace safety to keeping a secure watch on construction facilities, AI in the construction industry is already proving its value. Construction managers have been finding value with AI and cognitive technologies to help automate many of the mundane but essential tasks to running their operations. They are finding AI helpful with scheduling related tasks in order to prevent delays, conflicts, and other issues. This is both on the staff level of scheduling and on the project and materials side. Keeping this in mind, we have recently collaborated with [Mersea Homes](https://www.merseahomes.co.uk/) using Knowledge Transfer Partnership. The company are currently operating an outdated paper system for creating, communicating and updating site plans. The intention of this project is to develop an intelligent digital system using the combined expertise of IoT and data science specialists which can provide our site workers with real-time live updates to project plans using embedded sensors and smart phones receiving personalised live updates from our centralised server. Data-sharing will be based on an intelligent system driven by a machine learning algorithm, which will learn and anticipate which contractors and staff need particular information.

