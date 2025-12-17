**Characterization of Outcomes in Patients with Chronic Obstructive Pulmonary Disease (COPD) visiting the Emergency Department**
=============
 <img src="https://img.shields.io/badge/Study%20Status-Repo%20Created-lightgray.svg" alt="Study Status: Repo Created"> 

- Analytics use case(s): `Characterization`
- Study type: `Clinical Application`
- Tags: 'COPD'
- Study lead: **Dr. Isabel Pimenta**
- Study lead forums tag: **-**
- Study start date: **October 17, 2025**
- Study end date: **-**
- Protocol: [LINK to the protocol](https://github.com/OHDSI-JHU/Pulm_Outcomes/blob/main/Document/ResearchProtocol.pdf)
- Publications: **-**
- Results explorer: **-**

**Description** </n>

Chronic obstructive pulmonary disease (COPD) is a highly prevalent chronic respiratory disease worldwide and a major contributor to global morbidity and mortality.[1,2] COPD is characterized by persistent respiratory symptoms and chronic airflow limitation.[3] It also imposes substantial health-system burden through frequent acute-care utilization and hospital-based treatment.[2,4,5] Despite advances in chronic management, acute exacerbations of COPD (AECOPD) commonly prompt emergency department (ED) evaluation and often lead to hospitalization.[4,5] These exacerbations are pivotal events in the disease course and can require high-cost and invasive interventions, including non-invasive ventilation and endotracheal intubation with invasive mechanical ventilation in severe cases.[5–7]

Understanding the landscape of AECOPD treatment, such as acute medication use, oxygen requirements, escalation of respiratory support, and discharge management, can identify disparities and opportunities for quality improvement.[8–10] Multi-institution comparisons have been used to highlight variation in care processes and outcomes and can serve as a foundation for designing effective interventions and future predictive or population-level analyses.[8–10] This **project aims at charaterizing adults presenting to the emergency department with CPOD exacerbation, describing their treatment pattern, and compare the difference between a major academic hospital in the United States and a private non-profit multi-specialty hospital in Brazil**.

       

## Elements in the README template

| Element | Description |
| ------- | ----------- |
| [Study title]      | Characterization of Outcomes in Patients with Chronic Obstructive Pulmonary Disease (COPD) visiting the Emergency Department   |    
| Study status badge | <img src="https://img.shields.io/badge/Study%20Status-Repo%20Created-lightgray.svg" alt="Study Status: Repo Created">  |
| Next Steps |  Recruit network study partners|
| Research Question | What are the risk factors of ED patients with an acute COPD exacerbation regarding hospital admission, oxygen support requirement and 30-day reutilization?|
| Analytics use case | [Characterization](#analytics-use-cases) |
| Study type | [Clinical Application](#study-types) |
| Tags | Chronic Obstructive Pulmonary Disease |
| Study lead | Isabel Pimenta |
| Study lead forums tag | - |
| Study team | Rahul Gorijavolu, Yun-Chung (Murphy) Liu, Jessica Messier, Matthew Pham |
| Phenotype Development | Identify phenotype definitions |
| Phenotype Evaluation | Indicating dataset used and steps to evaluate phenotype validity. Identify the "noisy positive" (highly specific) and "noisy negative" (highly sensitive) cohorts used for phenotype evaluation. |
| Cohort Definitions | A brief description of the exposure and outcome cohorts and delineation of the JSON definitions included in the _Phenotypes_ and _Cohorts_ folders |
| Cohort Diagnostics | A hyperlink to the R Shiny app where the cohort diagnostics results can be viewed. |
| Analysis Specifications | A brief description of the analysis design choices made by the study team. A detailed description of the study design should be included in the study protocol document. |
| HADES Packages | List the HADES software packages required for network study execution. |
| Study Sites | Johns Hopkins Hospital, Albert Einstein Hospital (Brazil) |
| Results explorer | A hyperlink to a web app (e.g. a Shiny app) where the results of the study can be explored. |
| Study start date | October 17, 2025|
| Study end date | To be diceded | 
| Protocol | LINK. | 
| Publications | N/A. | 


### Study Progress

| Study Attribute | Value |
| ------- | ----------- |
| IRB materials sufficient for review | No, Yes |
| Cohort definition available | **Yes** |
| Data partner recruitment status | **Open** |
| Deadline for adding new data partners | MM/DD/YYYY |
| Protocol building team recrutiment status | **Open** |
| Deadline for adding new protocol building team members | MM/DD/YYYY |
| Manuscript preparation team recruitment status | Not Ready, Open, Closed |
| Deadline for adding new manuscript preparation team members | MM/DD/YYYY |

### Challenges:
  
* The inclusion criteria include ED visit, which is very compute intensive when calculating patient count across network.
* COPD is heterogenous, so it can be challenging to generalize findings in the larger study population to every patient
* Practice of medicine differs between study settings, patients with COPD may be managed outpatient on different medications 
* The way data is captured in EHR is different between study sites, so our cohort definition may not be generalizable perfectly between both sites
* Defining and distinguishing COPD exacerbations from other similarly presenting states, such as heart failure exacerbation, or fluid overload
* Coordinating input from external experts for a specialized disease area is logistically complex.

### Next steps:

1. Review concept IDs corresponding counts to finalize cohort definition. 
2.	Use the finalized inclusion and exclusion criteria to validate initial study population on Hopkins data.
3.	Recruit additional study sites/network partners to increase study population size. 
4.	Work on finetuning cohort definition with added data/networks partners and sites. 
5.	Finalize concept IDs for outcome and predictors with added data/networks partners and sites.
6.	Conduct clinical characterization analyses at Hopkins for validation of the study design.
7.	Validate study population and clinical characterization analyses at external site.
8.	Perform the study and analysis using data from all study sites with clinical characterization code piloted at Hopkins.



### References

1.	Adeloye D, Song P, Zhu Y, Campbell H, Sheikh A, Rudan I; NIHR RESPIRE Global Respiratory Health Unit. Global, regional, and national prevalence of, and risk factors for, chronic obstructive pulmonary disease (COPD) in 2019: a systematic review and modelling analysis. Lancet Respir Med. 2022 May;10(5):447-458. doi: 10.1016/S2213-2600(21)00511-7. Epub 2022 Mar 10. PMID: 35279265; PMCID: PMC9050565.
2.	GBD Chronic Respiratory Disease Collaborators. Prevalence and attributable health burden of chronic respiratory diseases, 1990-2017: a systematic analysis for the Global Burden of Disease Study 2017. Lancet Respir Med. 2020 Jun;8(6):585-596. doi: 10.1016/S2213-2600(20)30105-3. PMID: 32526187; PMCID: PMC7284317.
3.	Agustí A, Celli BR, Criner GJ, Halpin D, Anzueto A, Barnes P, Bourbeau J, Han MK, Martinez FJ, Montes de Oca M, Mortimer K, Papi A, Pavord I, Roche N, Salvi S, Sin DD, Singh D, Stockley R, López Varela MV, Wedzicha JA, Vogelmeier CF. Global Initiative for Chronic Obstructive Lung Disease 2023 Report: GOLD Executive Summary. Eur Respir J. 2023 Apr 1;61(4):2300239. doi: 10.1183/13993003.00239-2023. PMID: 36858443; PMCID: PMC10066569.
4.	Liew CQ, Hsu SH, Ko CH, Chou EH, Herrala J, Lu TC, Wang CH, Huang CH, Tsai CL. Acute exacerbation of chronic obstructive pulmonary disease in United States emergency departments, 2010-2018. BMC Pulm Med. 2023 Jun 20;23(1):217. doi: 10.1186/s12890-023-02518-0. PMID: 37340379; PMCID: PMC10283236.
5.	Perera PN, Armstrong EP, Sherrill DL, Skrepnek GH. Acute exacerbations of COPD in the United States: inpatient burden and predictors of costs and mortality. COPD. 2012 Apr;9(2):131-41. doi: 10.3109/15412555.2011.650239. Epub 2012 Mar 12. PMID: 22409371.
6.	Lindenauer PK, Stefan MS, Shieh MS, Pekow PS, Rothberg MB, Hill NS. Outcomes associated with invasive and noninvasive ventilation among patients hospitalized with exacerbations of chronic obstructive pulmonary disease. JAMA Intern Med. 2014 Dec;174(12):1982-93. doi: 10.1001/jamainternmed.2014.5430. PMID: 25347545; PMCID: PMC4501470.
7.	Stefan MS, Shieh MS, Pekow PS, Hill N, Rothberg MB, Lindenauer PK. Trends in mechanical ventilation among patients hospitalized with acute exacerbations of COPD in the United States, 2001 to 2011. Chest. 2015 Apr;147(4):959-968. doi: 10.1378/chest.14-1216. PMID: 25375230; PMCID: PMC4388126.
8.	Roberts CM, Lopez-Campos JL, Pozo-Rodriguez F, Hartl S; European COPD Audit team. European hospital adherence to GOLD recommendations for chronic obstructive pulmonary disease (COPD) exacerbation admissions. Thorax. 2013 Dec;68(12):1169-71. doi: 10.1136/thoraxjnl-2013-203465. Epub 2013 Jun 1. PMID: 23729193.
9.	Lindenauer PK, Stefan MS, Shieh MS, Pekow PS, Rothberg MB, Hill NS. Hospital patterns of mechanical ventilation for patients with exacerbations of COPD. Ann Am Thorac Soc. 2015 Mar;12(3):402-9. doi: 10.1513/AnnalsATS.201407-293OC. PMID: 25654431; PMCID: PMC4418316.
10.	Jacobs DM, Noyes K, Zhao J, Gibson W, Murphy TF, Sethi S, Ochs-Balcom HM. Early Hospital Readmissions after an Acute Exacerbation of Chronic Obstructive Pulmonary Disease in the Nationwide Readmissions Database. Ann Am Thorac Soc. 2018 Jul;15(7):837-845. doi: 10.1513/AnnalsATS.201712-913OC. PMID: 29611719; PMCID: PMC6207114.





