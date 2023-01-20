# nicu_hrv_analysis
## Abstract
Sepsis is a leading cause of death for preterm infants. Researchers have sought to develop methods for the early detection of sepsis using vital sign measurements. One area that has shown promise is heart rate variability. This project attempts to answer the question: Do heart rate variability metrics show signatures that indicate sepsis? This project’s answer to the question is negative, but there is much room for improvement.

The intended audience of this project consists of two groups.

The first group is Dr. Chang, Dr. Groves, and any undergraduates of theirs who may find themselves working on this problem. The detailed presentation of the methods section will hopefully help them to quickly solve some of the issues I encountered. An algorithmic proposal in the discussion section may also be of assistance in solving a problem with RR intervals being too long due to undetected beats.

The second group is potential employers in data science who want to see a demonstration of my skills. For them, the materials, methods, results, and discussion sections will demonstrate a proficiency in data cleaning. Additionally, the figures demonstrate that the validity of the pipeline processes was checked along the way. My goal was to illustrate the story of how I cleaned this data and to provide actionable suggestions to improve these procedures.

## Details

A full report of this project is provided in the pdf "Analysis of Heart Rate Variability to Predict Sepsis in Preterm Neonates". This is intended for my academic colleagues as well as potential employers.

The code itself is in the folder "notebooks2". Note that the first part of the pipeline in the notebook "01-pipeline-ecg-to-clean-rr" will not work on your machine because you don't have access to the ECG data. It was not practical to upload the data to this repository, as I would have to split it into thousands of files. If you're in the academic audience, you likely have your own ECG data to work with. If you're in the professional audience, then note that the second part of the pipeline should still work, although it is a very slow process.

The other notebooks should work just fine.
