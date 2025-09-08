# Immigrant-Health-CDS
This CDS Module contains the instructions for building an Immigrant Health CDS Toolkit within the Epic EHR
These CDS was developed based upon the AAP Immigrant Health Toolkit and guidance from national experts and a representative user/patient base.
It contains a list of orders, a documentation prompt, and an inline (non-interruptive) alert. 
The documentation prompt is intended to collect the minimum information needed to determine health screening needs and intentionally avoids creating strucutred data to limit discoverability of potentially sensitive information.
Please note: This CDS does not provide guidence for travel medicine or for management of the newly arrived refugee patient. 

# General Information 
## Artifact Type
Order Set with Documentation Template
## Creation Date
01/01/202
## Last Update Date
01/15/2024

## Publisher
Children's Hospital of Philadelphia
## Authors
Michel JJ, Karavite D, White D, Mudenge N, Dawson-Hahn E, Yun K.
## Contributors 
We are deeply appreciative of the key informants who shared their time, experience, and guidance with our team, including those who wish to remain anonymous.
## Funding
This project was funded by the National Institutes of Health through award #R21AI169560. 
# Usage
## Purpose
The purpose of this intervention is to encourage evidence-based, standardized care across institutions for immigrant children while providing culturally sensitive care.

## Intended Population
These artifacts are intended for use with patients of all children who arrive in the United States without refugee status.
These artifacts are intended for use in the outpatient setting in a primary care office or public health.

##Usage
These artifacts have been test installed at two institutions, we ask that organizations that install this work contact our team and provide feedback on the tools, the installation process, and recommendations for updates/changes.

# Supporting Evidence
Key guidance for the care of immigrant children was derived from:
Meneses C, Chilton L, Duffee J, et al. Immigrant Child Health Toolkit. Available from: https://www.aap.org/en-us/advocacy-and-policy/aap-health-initiatives/Immigrant-Child-Health-Toolkit/Pages/Immigrant-Child-Health-Toolkit.aspx

For a description of the project development see: 
Michel JJ, Karavite D, White D, Mudenge N, Dawson-Hahn E, Yun K. Development and Evaluation of Clinical Decision Support for Immigrant Child Health Screening in Primary Care. Appl Clin Inform. 2025 Aug;16(4):961-973. doi: 10.1055/a-2594-3633. Epub 2025 Apr 28. PMID: 40294632; PMCID: PMC12396900. DOI: 10.1055/a-2594-3633

# Installation and Use
## Triggers
This CDS alert is triggered to display as a non-interruptive alert during well child visits (preventative care visits). 
The immigrant health order set is alway available in the outpatient setting for selection from the list of order sets. It can be promoted as a suggested order set using the same display logic.
The documentation prompt can be added within any documentation template. Based on informant feedback we suggest insertion in sections where other social history content is collect.
## Inclusions
All patients are included in the display. This is intentional to avoid the appearance of profiling.
## Exclusions
We restrict the display of the CDS in patients with evidence of highly likely US birth (e.g. office visit within the first 4 weeks of life).
To avoid overapplication of the CDS we restricted display to patients with an office visit more than 2 years before the current event.
## Interventions and Actions
Alert actions include opening or not opening the order set. Acknowledge reasons include 'Not applicable' or 'Immigrant Health Screening Completed'
Order set infromation includes diagnosis assosciations with respective screening diagnoses to support efficiency.
A negative feedback loop turns of the alert and documentation prompt once completion of the intervention is established.