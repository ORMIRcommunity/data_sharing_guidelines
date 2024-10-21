(dua)=
# Data User Agreements

A Data Use Agreement (DUA) is a formal contract between a data provider---usually a repository---and a data recipient---usually a researcher using the data---that outlines the **specific terms and conditions under which the data can be accessed, shared, and used**. It defines the responsibilities of both parties, establishes privacy and security requirements, and specifies any restrictions on how the data may be used

```{important}
A Data Use Agreement allows controlling **what happens to the data when it is shared** in a repository. It does not provide a legal basis to share personal data---the informed consent does. 
<!-- It can be a legal instrument if the data are shared for further processing with similar purposes as the original research project---it gives a legal basis to the secondary data user.  -->
```

```{figure} ./figures/dua.png
:label: dua
:alt: dua
:height: 300px
:align: center
```

## What's the difference between a DUA and a license?

A Data Use Agreement is a more specific type of contract than a general license and is better suited for sharing data. Unlike commonly used licenses like GPL, MIT, or CC-BY, a **DUA** is designed for data and considers **both the rights of the data provider** (e.g., researcher or university) **and the rights of participants**, such as concerns about re-identification. While you could call the agreement between a data provider and downloader a *license*, using the term DUA makes it clear that it applies to data, not to creative works like text or code. It is **generally recommended to use a DUA instead of a license** when sharing data {cite:p}`dua_openbrain`.


## Templates of Data User Agreements

:::{admonition} DGPR Data User Agreement
:class: note
:class: dropdown
The following example was adapted from the Open Brain [Consent Data User Agreement](https://open-brain-consent.readthedocs.io/en/stable/gdpr/data_user_agreement.html) for accessing identifiable human data compatibly with the European GDPR (Version: OBC-GDPR-DUA 1.0.0). The proposed DUA requires the researcher applying for access to participant data to confirm that they will **not redistribute the data nor try to re-identify participant**. It also states that once an applicant (within or outside the European Union) downloads the data, they **become the data controller**, that is, responsible for determining how the data is used and ensuring that the agreed terms are followed. When using this DUA, please cite {cite:p}`Bannier2021`.

<div style="background-color: #f4f4f4; padding: 15px;">

I request access to the data collected in the digital repository of the \<DEPARTMENT\>, part of the \<INSTITUTION\>, established at \<CITY\>, \<COUNTRY\> (hereinafter referred to as the \<INSTITUTION SHORTNAME\>).

By accepting this agreement, I become the data controller (as defined under the GDPR) of the data that I have access to, and am responsible that I access these data under the following terms:

1.  I will comply with all relevant rules and regulations imposed by my institution and my government. Rules established in this agreement thus take place in addition to existing general data protection regulations that are applicable in my country.
2.  I will not attempt to establish or retrieve the identity of the study participants. I will not link these data to any other database in a way that could provide identifying information. I shall not request the pseudonymisation key that would link these data to an individual's personal information, nor will I accept any additional information about individual participants under this Data Use Agreement.
3.  I will not redistribute these data or share access to these data with others, unless they have independently applied and been granted access to these data, i.e., signed this Data Use Agreement. This includes individuals in my institution.
4.  [OPTIONAL] When sharing secondary or derivative data (e.g. group statistical maps or templates), I will only do so if they are on a group level, and cannot be deduced information from individual participants.
5.  I will reference the specific source of the accessed data when publicly presenting any results or algorithms that benefited from their use: (a) Papers, book chapters, books, posters, oral presentations, and all other presentations of results derived from the data should acknowledge the origin of the data as follows: "Data were provided (in part) by <Research centre/University Department> \<University, Country\>". (b) Authors of publications or presentations using the data should cite relevant publications describing the methods developed and used by the <Research centre/University Department> to acquire and process the data. The specific publications that are appropriate to cite in any given study will depend on what the data were used and for what purposes. When applicable, a list of publications will be included in the collection. (c) Neither the <Research centre/University Department> or <University>, nor the researchers that provide this data will be liable for any results and/or derived data. They shall not be included as an author of publications or presentations without consent.
6.  Failure to abide by these guidelines will result in termination of my privileges to access these data.

</div>
:::

---