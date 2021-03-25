# QCovid® Calculation Engine

QCovid® Calculation Engine is an evidence-based model that uses a range of factors such as age, sex, ethnicity and existing medical conditions to predict risk of death or hospitalisation from COVID-19.

It provides nuanced information on people’s risk of serious illness due to COVID-19 and has the potential to help patients and doctors reach a shared understanding of risk.

## QCovid.org
An implementation of the QCovid® algorithm can be found on https://qcovid.org. This website was created to provide a reference implementation of QCovid®. On this website you will also find further information on the algorithm, FAQs and links to our publications.

## QCovid® Calculation Engine and the NHS
The NHS are using QCovid® Calculation Engine to perform both population level risk stratification and to provide a web tool for individual COVID-19 risk assessment by clinicians. More information about how the NHS is using QCovid® Calculation Engine can be found at https://digital.nhs.uk/coronavirus/risk-assessment

## QCovid® Calculation Engine on GitHub
 QCovid® Calculation Engine is Copyright © 2020 Oxford University Innovation Limited.
 
The source code to QCovid® Calculation Engine has been made available on GitHub, under the terms of the Affero GPL v3.0 licence to improve transparency, flexibility and accountability. 

**In its compiled form, QCovid@ Calculation Engine is a Class I Medical Device and is covered by the Medical Device Regulations 2002 (as amended). Modification of the source code and subsequently placing that modified code on the market may make that person/entity a legal manufacturer of a medical device and so subject to the requirements listed in Medical Device Regulations 2002 (as amended). Failure to comply with these regulations (for example, failure to comply with the relevant registration requirements or failure to meet the relevant essential requirements) may result in prosecution and a penalty of an unlimited fine and/or 6 months’ imprisonment.** 

This source code version of QCovid® Calculation Engine is provided as is,and **has not been certified for clinical use, and must not be used for supporting or informing clinical decision-making**.

### Repositories

#### QCovidCalculationEngine
This is the core component of QCovid® Calculation Engine. The QCovid® Calculation Engine wraps the University of Oxford QCovid® algorithm (published in the the British Medical Journal as a peer reviewed paper (https://www.bmj.com/content/371/bmj.m3731) as a .Net Standard 2.0 DLL. This DLL provides a robust and easy to use interface for the QCovid® algorithm.

#### QCovidCalculationEngine-TestCases
These test cases have been provided by the University of Oxford as part of the CE Marking process for QCovid® Calculation Engine to validate it against the QCovid® algorithm as published in the BMJ. Before any CE Marked release of QCovid® Calculation Engine, all test cases are executed and must be passed. The same test cases have been used by licensees of the CE Marked version to ensure it is functioning correctly as installed on their own platforms and in their specific software environments.

These test cases are synthetic data, presenting as broad a range of combined parameters as possible, and designed to _validate_ the implementation, and ensure the QCovid® Calculation Engine functions identically to the published algorithm. They were not used in the original QCovid® algorithm development.

#### QCovid-ClinicalCodeGroups
These CSV files contain the mapping information used by QCovid® to convert between SNOMED-CT clincal codes, and the QCovid® algorithm input parameters. These mappings allow QCovid® Calculation Engine to process patient records coded using SNOMED-CT. 

Two mapping files exist, SnomedCodes.csv and SnomedCodes-expanded.csv. The first is those codes that were identified in the dataset originally used to develop the QCovid® algorithm, the second was created in collaboration with NHS Digital to create an expanded set of SNOMED codes, covering all the possible ways a condition might be coded, to ensure relevant conditions were not missed due to potential differences in local clinical coding practices. This expanded list is what QCovid® Calculation Engine accepts as input parameters.  

### Discussions
The [discussions board](https://github.com/QCovid/QCovid/discussions) is open for discussions about the QCovid® Calculation Engine code and suggestions on how we could improve the QCovid® Calculation Engine code base.

### Bug reports
In the unlikely event that you discover a bug in QCovid® Calculation Engine source code, we have enabled the creation of Bug Reports as Issues. 
We will evaluate any bug reports and take appropriate action.

### Pull requests
If you would like to suggest a change to QCovid® Calculation Engine, then you can create a pull request, but please follow our contribution guides.

## Licensing QCovid® Calculation Engine for clinical use
In order to use QCovid® Calculation Engine for clinical use in the UK and Europe, the full, CE Marked version of QCovid® Calculation Engine can be licensed from Oxford University Innovation. Please contact enquiries@innovation.ox.ac.uk quoting reference 17939.

The CE Marked version of QCovid® Calculation Engine has been registered with the Medical and Healthcare products Regulatory Agency (MHRA) and categorised as a Class 1 medical device.

QCovid® Calculation Engine is available as a .Net Standard 2.0 DLL, suitable for running in both Windows and Linux environments. It is distributed with 2 SQL databases suitable for either SQL Server or PostgreSQL. Requests to distribute QCovid® Calculation Engine in a different form will be considered.

## QCovid® trade mark
QCovid® is a registered trade mark of Oxford University Innovation. No rights are granted for any use of the QCovid® trade mark by any licensee of this source code version of QCovid® Calculation Engine under the Affero GPL v3 licence. 

Curently, use of QCovid® as a trade mark is reserved to licensees of the CE Marked version of the QCovid Calculation Engine, as licensed by Oxford University Innovation. For permission to use QCovid® as a trade mark in your product, or to licence the CE Marked version, please contact enquiries@innovation.ox.ac.uk quoting reference 17939. 

## Authors
### Professor Julia Hippisley-Cox
[Professor Julia Hippisley-Cox] (https://www.phc.ox.ac.uk/team/julia-hippisley-cox)is Professor of Clinical Epidemiology & General Practice in the Nuffield Department of Primary Care at the University of Oxford and the principle investigator on the NIHR funded research programme that led to the development of QCovid® Algorithm. She is also lead author of the peer reviewed paper in the BMJ (https://www.bmj.com/content/371/bmj.m3731), that describes the methodology used to develop QCovid®.

### Oxford Computer Consultants
[Oxford Computer Consultants](https://www.oxfordcc.co.uk/) are a software house providing original, robust and flexible software for clients across the public and private sector. We provide a highly skilled custom software development service. We have decades of experience in science, engineering and medical sectors. Visit our website to see our full range of services and case examples of other projects we have delivered.

### Oxford University Innovation Limited
[Oxford University Innovation Limited] (https://www.innovation.ox.ac.uk) are a wholly-owned subsidiary of the University of Oxford. We manage the University’s technology transfer and consulting activities. We are the MHRA-registered Medical Device Manufacturer for the CE Marked version of QCovid® Calculation Engine as supplied to NHS Digital and other healthcare organisations. All requests for licensing should be sent to enquiries@innovation.ox.ac.uk, quoting 17939.
