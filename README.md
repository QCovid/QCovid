# QCovid®

QCovid® is an evidence-based model that uses a range of factors such as age, sex, ethnicity and existing medical conditions to predict risk of death or hospitalisation from COVID-19.

It provides nuanced information on people’s risk of serious illness due to COVID-19 and has the potential to help patients and doctors reach a shared understanding of risk.

## QCovid.org
An implementation of the QCovid® algorithm can be found on https://qcovid.org. This website was created to provide a reference implementation of QCovid®. On this website you will also find further information on the algorithm, FAQs and links to our publications.

## QCovid® and the NHS
The NHS are using QCovid® to perform population risk assessment and clinical risk assessment. More information about how the NHS is using QCovid® can be found at https://digital.nhs.uk/coronavirus/risk-assessment

## QCovid® on GitHub
QCovid® has been made available on GitHub to improve transparency, flexibility and accountability.

The open source version of QCovid® has not been certified for clinical use, and **must not be used for supporting or informing clinical decision-making**.

### Repositories

#### QCovidEngine
This is the core component of QCovid®. The engine wraps the University of Oxford algorithm as a .Net Standard 2.0 DLL. This DLL provides a robust and easy to use interface for the QCovid® algorithm.

#### QCovidEngine-TestCases
Test cases have been provided by the University of Oxford for testing QCovid® against their research data. Before any release of QCovid® all test cases are executed.

#### QCovid-ClinicalCodeGroups
These CSV files contain the mapping information used by QCovid® to convert between NHS SNOMED and Read2 codes, and the QCovid® codes. These mappings allow QCovid® to process NHS medical records.

### Discussions
The [discussions board](https://github.com/QCovid/QCovid/discussions) is open for discussions about the QCovid® code and suggestions on how we could improve the QCovid® code base.

### Bug reports
In the unlikely event that you discover a bug in QCovid® we have enabled the creation of Bug Reports as Issues. We will evaluate any bug reports and take appropriate action.

### Pull requests
If you would like to suggest a change to QCovid® then you can create a pull request, but please follow our contribution guides.

## Licensing QCovid® for medical use
In order to use QCovid® for medical use, a license for the full version of QCovid® is required. This may be purchased from University of Oxford. Please contact enquiries@innovation.ox.ac.uk quoting reference 17939.

The licensed version of QCovid® is has been registered with the Medical and Healthcare products Regulatory Agency (MHRA) and categorised as a Class 1 medical device.

QCovid® is available as a .Net Standard 2.0 DLL, suitable for running in both Windows and Linux environments. It is distributed with 2 SQL databases suitable for either SQL Server or PostgreSQL. Requests to distribute QCovid® in a different form will be considered.

## Authors
### Oxford Computer Consultants
[Oxford Computer Consultants](https://www.oxfordcc.co.uk/) are a software house providing original, robust and flexible software for clients across the public and private sector. We provide a highly skilled custom software development service. We have decades of experience in science, engineering and medical sectors. Visit our website to see oru full range of services and case examples of other projects we have delivered.
