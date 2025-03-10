# About
In this repository, I classify, annotate, and document my thoughts on papers I read. I learned this organization from Fredrik K. Gustafsson[@fregu856](https://github.com/fregu856).

## Bookmarks

| **Books**                     | **Biostatistics**             | **Epidemiology**              | **Health Economics**              | **Chronic Myeloid Leukemia**      |
|-------------------------------|-------------------------------|-------------------------------|-----------------------------------|-----------------------------------|
| [Books, Biostatistics]         | [Biostatistics]               | [Epidemiology]                | [Health economics]                | [CML]                             |
| [Books, Health Economics]      | [Flexible parametric models]  | [Causal inference]            | [HTA guidelines]                  | [CML, treatment]                  |
| [Books, Epidemiology]          | [Multistate models]           | [Regression standardization]  | [Health economic modelling]       | [CML, TKI discontinuation]        |
|                               | [Cure modeling]               |  [Registry-based studies]      | [Survival Extrapolation]          | [CML, health economics]           |
|                               | [Microsimulation]             |                               | [Health state values]             |                                   |
|                               | [PIAMOD/MIAMOD]               |                               | [Economic burden of disease]      |                                   |
|                               | [Clinical trials]             |                               | [Swedish healthcare costs]        |                                   |
|                               | [Software packages]           |                               |                                   |                                   |

## Papers
##### [25-Mar-10][paper9]
- Living, not just surviving, with chronic myeloid leukemia – quality of life to the front of the line
- Lipton2025
- `Leukemia`[[doi]](https://doi.org/10.1038/s41375-025-02548-z)
- [CML]
<div style="max-width:100%; word-wrap:break-word;">
This paper highlighted that the goal for treating CML patients is not just the restoration of normal life expectancy but also the restoration of various aspects of the patient's life. 
One thing clinicians could do is to have better communication with patients. The authors cited, “And in the end, it's not the years in your life that count. It's the life in your years.” - Abraham Lincoln
</div>

##### [25-Feb-20][paper8]
- European LeukemiaNet laboratory recommendations for the diagnosis and management of chronic myeloid leukemia
- Cross2023
- `Leukemia`[[doi]](https://doi.org/10.1038/s41375-023-02048-y)
- [CML]
<div style="max-width:100%; word-wrap:break-word;">
This paper gives an introduction to CML focused more on the moelcular aspects of the disease.
"Chronic myeloid leukemia (CML) is characterized by the Philadelphia (Ph) chromosome, 
described in 1960 as the first recurrent chromosome abnormality associated with a human malignancy [1]. 
The Ph chromosome, or more correctly the der22,t(9;22)(q34;q11), is the smaller derivative of a somatically 
acquired reciprocal translocation between chromosomes 9 and 22 [2], 
which leads to fusion of the Breakpoint Cluster Region (BCR) gene at 22q11 and the Abelson Proto-oncogene 1 Nonreceptor Tyrosine Kinase (ABL1) gene at 9q34 [3]. 
The resulting BCR::ABL1 fusion, located on the Ph chromosome, encodes a chimeric BCR::ABL1 protein with deregulated tyrosine kinase activity 
that is the primary driver of the pathogenesis of CML."
</div>

##### [25-Feb-20][paper7]
- Chronic myeloid leukaemia: ESMO Clinical Practice Guidelines for diagnosis, treatment and follow-up
- Hochhaus2017 
- `Annals of Oncology`[[doi]](10.1093/annonc/mdx219)
- [CML]
<div style="max-width:100%; word-wrap:break-word;">
ESMO guidelines (2017) recommended frequent molecular monitoring for patients with CML. 
Time since TKI discontinuation: Month 1-6 monthly molecular monitoring, Month 7-12 every 6 weeks, Month 13+ every 3 months.
</div>

##### [25-01-17][paper6]
- Finding the health-care expenditure that drives variation in cancer survival
- Rutherford2024
- `The Lancet Oncology`[[doi]](https://www.thelancet.com/journals/lanonc/article/PIIS1470-2045(24)00187-6/fulltext)
-[Health economics]
<div style="max-width:100%; word-wrap:break-word;">
Rutherford M. commented that it might not be optimal to correlate total national health expenditure with cancer survival. (Sant et al.'s work, a part of EURO-CARE6, on linking survival of patients with lymphoid neoplasms with health expenditure. Understanding the determinants of survival
differences is important, e.g., stage at diagnosis, late diagnosis, etc.
</div>


##### [25-01-16][paper5]
- European LeukemiaNet laboratory recommendations for the diagnosis and management of chronic myeloid leukemia
- Cross2023[[doi]](https://doi.org/10.1038/s41375-023-02048-y)
- `Leukemia`
- [CML]
<div style="max-width:100%; word-wrap:break-word;">
The treatment goals for CML have evolved from focusing on survival to molecular assessments of the depth and stability of remission, and the possibility of achieving treatment-free remission (TFR).
</div>

##### [25-01-16][paper4]
- European LeukemiaNet 2020 recommendations for treating chronic myeloid leukemia
- Hochhaus2020[[doi]](https://doi.org/10.1038/s41375-020-0776-2)
- `Leukemia`
- [CML]
* ELN2020 recommendations. 
* MMR: BCR-ABL1 ≤ 0.1% IS. MR4: BCR-ABL1 ≤ 0.01% IS. MR4.5: BCR-ABL1 ≤ 0.0032% IS. MR5: BCR-ABL1 ≤ 0.001% IS. Whatever below MR4 is DMR.
* Generic IMA is the most cost-effective initial treatment.
* 80% of CML patients won't achieve a TFR.
* 80% of CML patients who achieve a TFR will have recurrences within 6-8 months; hence, require frequent monitoring
* Some patients who are eligible for TFR may not want to discontinue TKI treatment.

##### [24-12-03][paper3]
- Estimation and projections of cancer prevalence from cancer registry data
- Verdecchia2002[[doi]](https://doi.org/10.1002/sim.1304)
- `Statistics in Medicine`-
- [PIAMOD/MIAMOD][Registry-based studies]
<div style="max-width:100%; word-wrap:break-word;">
Original PIAMOD paper. Recommend reading with the illness-death model figure from the original MIAMOD paper (Verdecchia1989). 
There are main two big families of methods to estimate prevalence: direct vs. indirect methods. PIAMOD adopts "indirect" approaches: use the inter-relationship between cancer mortality and survival to back-calculate cancer incidence and prevalence.
</div>

##### [24-12-03][paper2]
- Partitioned Survival and State Transition Models for Healthcare Decision Making in Oncology: Where Are We Now?
- Woods2020[[doi]](https://doi.org/10.1016/j.jval.2020.08.2094)
- `Value in Health`
- [Multistate models]
<div style="max-width:100%; word-wrap:break-word;">
Well-written paper about the relationship between partitioned survival models vs. state-transition models. Figure 1 is informative and pedagogical.
</div>

##### [24-12-03][paper1]
- Extrapolating clinical evidence within economic evaluations.
- Coyle2023[[doi]](https://www.cda-amc.ca/sites/default/files/attachments/2023-05/MH0011-Extrapolating%20Clinical%20Evidence%20Within%20Economic%20Evaluations_0.pdf)
- `Canadian Journal of Health Technologies`
- [HTA Guidelines]
<div style="max-width:100%; word-wrap:break-word;">
Mark and I discussed this guideline. It has various recommendation on health economics modelling practices. Recommendation 9--CADTH guidance says, "A partition survival model structure is not recommended as it relies on an assumption of independence between curves." We are wondering whether this statement is true or not. What is the difference between using a partitioned survival vs. an illness-death model. This might be an interesting topic to explore further to compare 1) K-M ; 2) ; 3) Partitioned survival
</div>

