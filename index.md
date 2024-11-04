# ORMIR Data Sharing Guidelines

<!-- 
```{note}
!!!This website is work in progress!!!
``` -->

**Sharing data** is an **essential** aspect of Open Science for **advancing scientific progress**, **fostering transparency** in research, and **maximizing the effective use** of public investments and research resources {cite:p}`Jwa2022`.

Sharing data is increasingly encouraged across various research fields and more and more required by funding agencies. In **Musculoskeletal (MSK) Imaging**, the amount of shared data is still limited. Some of the main **challenges** refer to the understanding of the **complex regulatory landscape**---particularly concerning ethical and legal issues, such as data privacy---and **technical competences**---including data de-identification, data anonymization, and choosing a data repository.  


In these **guidelines**, we aim to **clarify** the main aspects involved in sharing MSK Imaging data, with the **hope to facilitate data sharing** in the MSK imaging scientific community. We will often refer to the ongoing work in the Neuroimaging scientific community, where a more extensive body of literature and data repositories are already established.

```{important}
All the content in these guidelines is provided for **informational purposes only** and does ***not* constitute legal advice**. We recommend to **collaborate with your Institution and your local Ethical Committee** for legal advise  
```

These guidelines are curated by members of the [Open and Reproducible Musculoskeletal Imaging Research (ORMIR)](https://www.ormir.org/) community, who aims to promote a culture of openness and reproducibility in MSK imaging research through development of open and reproducible software, development of standardized acquisition and analysis workflows, and promotion of open data sharing practices. These guidelines were initiated during the 2nd ORMIR workshop [Sharing and Curating Open Data in Musculoskeletal Imaging Research](https://github.com/ORMIRcommunity/2024_2nd_ORMIR_WS/blob/main/README.md) held in January 2024, and are being updated periodically.

---

## What's the role of researchers in data sharing?

When researchers want to share MSK imaging data, they should **collaborate with their Institutions and local Ethical Committees** to prepare the following documents:
- An **consent form**, which provides participants detailed information about the study, including its purpose, procedures, potential risks, benefits, and their rights
- A **data *user* agreement**, which defines how users can access and utilize participants' data shared *in a data repository*
- A **data *sharing* agreement**, how users can access and utilize participants' data  shared *with another institution*

Note that:
- A *consent form* is a formal document between a researcher and a **participant**
- A *data user agreement* and a *data sharing agreement* are a formal documents between a researcher and **data users**

In addition, it is responsability of the researchers to **de-identify** or **anonymize the data** before sharing them with third parties, and to **choose** the appropriate **data repository**

```{figure} ./figures/framework.png
:label: framework
:alt: framework
:height: 300px
:align: center
```

---

## What's in these guidelines?

The material you'll find in these guidelines is meant to **support you in the conversation** with your Institution and your local Ethical Committee, so that you can share your study data with other researchers. 

```{important}
All guidelines refer to **research data**---that is, data collected during research studies to answer specific scientific questions or hypotheses---and ***not* clinical data**---that is, data collected as part of routine medical care 
```

In these guidelines, you will find:
- {ref}`Templates for Consent forms <consents>`
- {ref}`Templates for Data user agreements <dua>`
- {ref}`Templates for Data sharing agreements <dsa>`
- {ref}`Criteria to choose a data repository <repo>`
- {ref}`Guidelines for data de-identification or anonymization <anonymization>`
<!-- - Description of meta-data that can be submitted to the planned ORMIR Image Data Index -->

<!-- ```{note}
These guidelines refer to **secondary research**, which refers to research use of **data originally collected for other research studies** 
``` -->

---

## Variations among countries, states, and institutions

There are several differences among countries, states, and institutions about the legislation concerning data sharing. Here are some of the peculiarities for European Union and United States---if you want to add the documentation about your country, please contribute to this page!


### General regulations
In the **European Union**, data sharing is based on the [General Data Protection Regulation (GDPR)](https://gdpr-info.eu/), released in 2018 {cite:p}`Bannier2021`. The GDPR concerns data storage, transfer, and sharing both within and outside the European Union and gives the institutions a greater responsability to safeguard the privacy of personal data {cite:p}`White2022`.

In the **United States**, data sharing is based on the [Belmont Report: Ethical Principles and Guidelines for the Protection of Human Subjects of Research](https://www.hhs.gov/ohrp/regulations-and-policy/belmont-report/index.html) (National Commission for the Protection of Human Subjects of Biomedical and Biobehavioral Research, 1978), which laid out three core ethical principles, that is, respect for persons, beneficence, and justice. The implementation of the ethical principles of the Belmont Report resulted in a multitude of federal regulations and policies. Amont these, the [Common Rule](https://www.hhs.gov/ohrp/regulations-and-policy/regulations/common-rule/index.html)---codified by Department of Health and Human Services---was adopted by many federal departments and operates as the standard for ethical conduct and government-funded research {cite:p}`Jwa2022`. The [Health Insurance Portability and Accountability Act (HIPAA)](https://www.hhs.gov/hipaa/index.html) is a federal law enacted to protect the privacy and security of individuals' medical records and other personal health information. It governs how healthcare providers, insurance companies, and other entities handle patient data. For a complete overview of the legal landscape in the United States, we recommend the article by {cite:p}`Jwa2022`. 

**International** recommendations by the World Medical Association include the [Declaration of Helsinki](https://www.wma.net/policies-post/wma-declaration-of-helsinki-ethical-principles-for-medical-research-involving-human-subjects/) (2001), which defines ethical principles for medical research involving human subjects and the [Declaration of Taipei](https://www.wma.net/what-we-do/medical-ethics/declaration-of-taipei) (2017) which defines ethical principles for health databases, big data, and biobanks {cite:p}`Bannier2021`. 

### Data ownership
Knowing who owns the data is important because "whoever owns the data has control over the data, its dissemination, and the timing of dissimination" {cite:p}`White2022`. Owners can be:
- **Researchers and/or academic institutions** sponsoring research projects
- **Funding agencies** sponsoring research projects (e.g. NIH in the United States)
- **Study participants**. The European GDPR provides more rights to the individuals, including the "Right to be Forgotten", that is, the right to request to erase personal paper and electronic research history {cite:p}`White2022`

Currently, there is **no consensus** on data ownership.


---

