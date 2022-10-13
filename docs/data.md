# Data

**Resources:**

* See the full metadata model in [PDF](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.pdf) or [Markdown](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md).
* See the [Data](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=WV%27%2C%20%27WY%27%5D.-,data,-(object)) element of the full metadata model.
* See guidance to respond to each field, and their use cases, by clicking the arrow to the left of the bold field names below.

**Extra context:**

* This section ONLY APPLIES to studies answering “Yes” to “Will your study collect or produce data?” in the Data Availability form section. Contact heal-support@datacommons.io for questions or support.
* This section has 10 fields; 
    * The first 3 fields apply to your study even if your study is not a human subjects study
    * The final 7 fields apply to your study ONLY if your study is a human subject study

**Fill out this section of the CEDAR form:**

[Expand](expand-or-collapse-cedar-form-section.md) the Data section. This section has ten fields; click below to expand guidance for each field:


??? note "Is data quantitative or qualitative?"

    **How to answer**

    > This field allows multiple selections, included in the full metadata model [definitions](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=data_orientation). Select all that apply.
    
    > If your study will collect quantitative data (e.g., blood pressure reading, self-reported pain on a validated tool scale, community rate of opioid overdose, quantified numbers and intensity of DRG nerve action potentials following pain stimulus), select “Quantitative." If your study will collect qualitative data (e.g., structured focus group/interview notes and/or coding, medical chart notes), select “Qualitative." If your study will collect both, select both.

    
    **How this field will be used?**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. For **example:**

    >> * **Qualitative:** A pre-K/K school teacher knows their surrounding community has high rates of OUD and wonders if student behavioral issues can be attributed to in utero opioid exposure. They want to recognize exposure impacts and support intervention for students and their parents, while also finding narrative case studies, by medical or educational providers, describing interactions with, and behaviors of, young children impacted by in utero OUD exposure, to understand similarities in experiences.
    * **Quantitative:** A clinician treating OUD notices a high rate of relapse in patients. They have seen news stories and case studies suggesting OUD relapse risks related to anxiety and depression, and seek quantitative research data to better understand whether anxiety and depression are clear risk factors, and if so, whether these factors increase relapse risk by a clinically meaningful amount.

??? note "Source of data"

    **How to answer**
    > This field allows multiple selections, included in the full metadata model [definitions](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=data_source). Select all that apply. What is the source of your study data?
        
    > **While we appreciate feedback on all fields and allowed answer values, we are particularly interested in feedback on formatting and answer values for the “Source of data” (this field) and “Data type” (next field) fields.**

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page and will allow users to quickly find broad, relevant studies, study data, or study-generated knowledge. **Examples include:**

    >> * **Patient-reported:** A clinician treating OUD notices a high rate of relapse in patients. They have seen news stories and case studies suggesting OUD relapse risks related to anxiety and depression, and seeks any studies collecting patient-reported outcome measures related to OUD patient anxiety and depression, so they can design a secondary analysis study to investigate this relationship in a more systematic and rigorous manner.

??? note "Data type"

    **How to answer**
    
    > This field allows multiple selections, included in the full metadata model [definitions](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=data_type). Select all that apply. What type of the data does your study collect or produce?
    
    > **While we appreciate feedback on all fields and allowed answer values, we are particularly interested in feedback on formatting and answer values for the “Source of data” (this field) and “Data type” (next field) fields.**

    **How this field will be used**

    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. **For example:**

    >> * **Questionnaire/Survey/Assessment - validated instrument:** A researcher seeks studies to conduct a meta-analysis of studies looking at the impact of housing insecurity on OUD outcomes following completion of residential OUD treatment programs. They want to limit the studies to those that used a validated tool to measure housing status/insecurity.

??? note "Human Subject Data - Unit of Collection"

    **How to answer**
    > This field ONLY APPLIES studies that answered “Human” for study subject type in the Study Type section AND “Yes” to “Will your study collect or produce data?” in the Data Availability section. This field allows multiple selections, included in the full metadata model definitions. Select all that apply. For studies with human subjects, is the data collected at the individual or population level? **For example:**

    >> * **Individual**: A study with opioid overdose rate outcomes, following and measuring outcomes by obtaining individually identified healthcare provider and/or claims records for individuals during the study period.
    * **Population:** A study with opioid overdose rate outcomes, obtaining community counts of opioid overdose by measuring outcomes following a community-level intervention, while dividing the overdose counts by the total of relevant individuals.
    
    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. **For example:**

    >> * **Individual:** A researcher seeks studies to conduct a meta-analysis of studies looking at the impact of housing insecurity on OUD outcomes, following completion of residential OUD treatment programs. They want to limit studies to those collecting individual-level data, including high-resolution individual geographic data, so they can combine individual-level data, and will also correct for individual socio-environmental factors.

??? note "Human Subject Data - Expected Number of the Unit of Collection"

    **How to answer**
    > This field ONLY APPLIES if you answered “Human” to study subject type in the Study Type section AND “Yes” to “Will your study collect or produce data?” in the Data Availability section. This field allows integer entries. For studies with human subjects, on how many subjects do you plan to collect data? If the data collection unit is individuals, this is the expected number of individuals. If the data collection unit is populations/clusters, this is the expected number of populations/clusters. **For example:**

    >> * For a study with opioid overdose rate outcomes, following and measuring outcomes by obtaining individually identified healthcare provider and/or claims records for individuals during the study period, select the number of individuals enrolled in the study.
    * For a study with opioid overdose rate outcomes, obtaining community counts of opioid overdose by measuring outcomes following a community-level intervention, while dividing the overdose counts by the total of relevant individuals, select the number of communities enrolled in the study.
    
    **How this field will be used**
    > These values will likely be available, as text, on the HEAL study page, allowing users to quickly view how large a study is and decide how much power it has to detect an intervention's effect or to reflect observational metrics (e.g., prevalence, incidence, differential risk, etc.) accurately. For users seeking data to use in a secondary analysis, this may help get an aggregate count of relevant observations across studies on the HEAL Platform and/or to decide if a particular study is worth the effort to request study data access, if the data has substantial access restrictions and burdens. **For example:**

    >> * A researcher conducting a meta-analysis of studies on housing insecurity impacts on OUD outcomes, following residential OUD treatment, will limit studies to those collecting individual data, including high-resolution geographic data, to combine this data and correct for socio-environmental factors. Since high-resolution individual geographic information represents a substantial re-identification/disclosure risk, these studies will have significant access restrictions, requiring extensive work to gain access, so they will view the number of individuals in each study and limit themselves to studies with data for at least 50 individuals. After finding studies that meet most criteria, they can review each study page and manually filter out studies that expect fewer than 50 participants.

??? note "Human Subject Data - Unit of Analysis"

    **How to answer**
    > This field ONLY APPLIES if you answered “Human” to study subject type in the Study Type section AND “Yes” to “Will your study collect or produce data?” in the Data Availability section.

    > This field allows multiple selections, included in the full metadata model definitions. Select all that apply.

    > For studies with human subjects, is the data analyzed at the individual or population level? If you selected ONLY “Population” for the Unit of collection (above), select ONLY “Population” here. **For example:**

    >> * A randomized control trial of subjects (randomized at the individual level) across multiple clinics, collects data on each participant and analyzes intervention effects on the primary outcome, at the individual level, using a random-effects model to correct for intra-clinic/class correlation (Unit of collection: Individual; unit of analysis: Individual).
    * A cluster-randomized control trial (randomized at the clinic level) collects data at the individual level for each cluster/clinic but analyzes effect of the intervention on the primary outcome at the cluster/clinic level as to account for high intra-cluster/clinic correlation (Unit of collection: Individual; unit of analysis: Population)

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. They will also be easily accessible to viewers, as text, on the study page. **Examples include:**

    >> * **Population**: An educator seeking evidence on school-based interventions to prevent first opioid use in high school students to support a proposal (for their principal) requesting implementation funds and resources wants studies that are statistically sound and correct for the high intra-class correlation, generally found within schools and even classrooms, by analyzing the data grouped at one/both levels.
    * **Individual:** A researcher seeks individual data to include in a secondary analysis, and wants to know if it may be available from a particular study with a clear structure (e.g. correlations within subsets of the individuals) they will need to account for in their own analysis.

??? note "Human Subject Data - Expected Number of the Unit of Analysis"

    **How to answer**
    > This field ONLY APPLIES if you answered “Human” to the Study subject type in the Study Type section AND “Yes” to “Will your study collect or produce data?” in the Data Availability section.
    > This field allows integer entries. For studies with human subjects, on how many subjects do you plan to collect data? If the data collection unit is individuals, this is the expected number of individuals. If the data collection unit is populations/ clusters, this is the expected number of populations/clusters. **For example:**

    >> * For a randomized control trial of subjects (randomized at the individual level) across multiple clinics, collects data on each participant and analyzes intervention effects on the primary outcome, at the individual level, using a random-effects model to correct for intra-clinic/class correlation, select **the number of individuals enrolled in the study.**
    * For a cluster-randomized control trial (randomized at the clinic level) collects data at the individual level for each cluster/clinic but analyzes effect of the intervention on the primary outcome at the cluster/clinic level as to account for high intra-cluster/clinic correlation, select **the number of clusters/clinics enrolled in the study.**

    **How this field will be used**
    > These values will likely be available, as text, on the HEAL study page, allowing users to quickly view how large a study is and decide how much power it has to detect an intervention's effect or to reflect observational metrics (e.g., prevalence, incidence, differential risk, etc.) accurately. For users seeking data to use in a secondary analysis, this may help get an aggregate count of relevant observations across studies on the HEAL Platform and/or to decide if a particular study is worth the effort to request study data access, if the data has substantial access restrictions and burdens. **For example:**
    
    >> * A researcher conducting a meta-analysis of studies on housing insecurity impacts on OUD outcomes, following residential OUD treatment, will limit studies to those collecting individual data, including high-resolution geographic data, to combine this data and correct for socio-environmental factors. Since high-resolution individual geographic information represents a substantial re-identification/disclosure risk, these studies will have significant access restrictions, requiring extensive work to gain access. Because of this, they will determine: 1) How many individuals’ data is available in each study and 2) The degree to which underlying structures in the individual data (e.g. high correlations within individual subsets) effectively reduce this number. They will limit themself to studies with data for at least 50 individuals 5 clusters of 30 individuals. After finding studies that meet most criteria, they can **review each study’s page and manually filter out studies with: 1) Fewer than 50 units of collection OR 2) Fewer than 5 units of analysis.**

??? note "Human Subject Data - Individual or Aggregated Data made available?"

    **How to answer**
    > This field ONLY APPLIES if you answered “Human” to the study subject type in the Study Type section AND “Yes” to “Will your study collect or produce data?” in the Data Availability section. This field allows multiple selections, included in the full metadata model [definitions](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=subject_data_level_available). Select all that apply.

    > For studies with human subjects that will make at least some data available, will data be available at the individual or an aggregate level? **For example:**

    >> * **Individual-Unaggregated:** A study with opioid overdose rate outcomes follows and measures the outcome by obtaining individually identified healthcare provider and/or claims records, covering the study period for each individual, AND will make individual data available in a public data repository.

    >>> * **Individual-Aggregated:** The same study will ONLY or ALSO make aggregated data available.
    * Also select options to specifically describe the type(s) of aggregated data (e.g., if you will provide population summary statistics, select **“Aggregated, across all (population summary statistics)**”). * 

    >> * **Community, Group, Cluster, Population - Unaggregated:** A cluster- randomized control trial (randomization at the clinic level) that collects data at the individual-level for each cluster/clinic but analyzes the effect of the intervention on the primary outcome at the cluster/clinic level to account for high intra-cluster/clinic correlation, but will NOT make data available at the individual-level, AND will make data available at the cluster/clinic level in a public data repository.

    >>> * **Community, Group, Cluster, Population - Aggregated:** The same study will ONLY or ALSO make data aggregated across cluster/clinics available.
    * Also select options to specifically describe the type(s) of aggregated data (e.g., if you will provide data aggregated across all clusters broken out by treatment versus control intervention status/assignment, select **“Aggregated, by treatment/exposure group”**)

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. **For example:**

    >> * **Individual - Unaggregated:** A researcher conducting a meta-analysis of studies on housing insecurity impacts on OUD outcomes, following residential OUD treatment wants to limit studies to those that collected individual-level data and will make it available in a public data repository at the individual level, because they want to combine individual data.
    * **Aggregated; Aggregated, by demographic variable(s); OR Aggregated, by geographic variable(s):** A journalist without many analytic resources seeks study summary statistics to decide if the data is useful to a story and interesting enough to either: 1) Ask their news outlet to assign analytics staff to secure underlying data for a more in-depth analysis, OR 2) Use the summary statistics alone to tell a good story about sociodemographic disparities in access to MOUD

??? note "Human Subject Geographic Data - Collected at what level of detail?"

    **How to answer**
    > This field ONLY APPLIES if you answered “Human” to the study subject type in the Study Type section AND “Yes” to “Will your study collect or produce data?” in the Data Availability section.
    > This field allows multiple selections, included in the full metadata model [definitions](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=subject_geographic_data_level_collected). Select all that apply. For studies with human subjects, will geographic data be collected? If so, at what level of geographic detail? **For example:**

    >> * **Exact location:** Your study will collect exact address information for enrolled individuals.
    * **Zip code:** Your study will collect zip code information for enrolled individuals.

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. They will also appear, as text, on the HEAL Platform study page so users can easily access the information. **For example:**

    >> * **Exact location; Census block;** OR **Census tract** geographic data collected field: A researcher conducting a meta-analysis of studies on housing insecurity impacts on OUD outcomes, following residential OUD treatment, will limit studies to those collecting individual data, including high-resolution geographic data, to combine this data and correct for socio-environmental factors. They need geographic data at least as specific as the census tract. Even if the study isn’t currently making this data available in a public data repository, they may be able to contact the study authors to collaborate and access the data for their analysis.

??? note "Human Subject Geographic Data - Available at what level of detail?"

    **How to answer**
    > This field ONLY APPLIES if you answered “Human” to the study subject type question in the Study Type section AND “Yes” to “Will your study collect or produce data?” in the Data Availability section.

    > This field allows multiple selections, included in the full metadata model [definitions](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=subject_geographic_data_level_available). Select all that apply.

    > For studies with human subjects that collect geographic data and will make at least some data available, will geographic data be available? If so, what level of geographic detail? **For example:**

    >> * **Zip Code:** Your study will collect exact address information, but will only make zip code level geographic data available in a public repository.
    * **Zip Code AND State:** Your study will collect zip code information and make two distinct datasets available in a public repository, a restricted-access dataset with zip code information, and an open-access dataset with zip code information, coded up to the state-level.

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. They will also be available on individual HEAL Platform study pages, providing users with easy access. **For example:**

    >> * **Exact location; Census block; OR Census tract** for both geographic data collected AND geographic data available, or just for geographic data available field: A researcher conducting a meta-analysis of studies on housing insecurity impacts on OUD outcomes, following residential OUD treatment, will limit studies to those collecting individual data, including high-resolution geographic data, to combine this data and correct for socio-environmental factors. They need geographic data at least as specific as census tract, and only want to include data that is already available in a public data repository.

Once complete, [collapse](expand-or-collapse-cedar-form-section.md) the Data section and [save](save-cedar-form.md) your form.        
