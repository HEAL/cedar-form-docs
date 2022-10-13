# Human Treatment Applicability

**Resources:**

* See the full metadata model in [PDF](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.pdf) or [Markdown](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md).
* See the [Human Treatment Applicability](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=human_treatment_applicability) element of the full metadata model.
* See guidance to respond to each field, and their use cases, by clicking the arrow to the left of the bold field names below.

**Extra context:**

* This section will apply to your study <u>even if your study is not a human subjects study</u>
* This section **ONLY APPLIES** to studies that listed their [Study Translational Focus](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=study_translational_focus%20(string)%3A) as “Treatment of a Condition”. 
* Studies that are not focused on studying <u>treatment</u> of a human pain or opioid use condition (e.g. studies that are instead focused on studying the condition itself) should skip this section. Contact heal-support@datacommons.io for questions or support.

**Fill out this section of the CEDAR form:**

[Expand](expand-or-collapse-cedar-form-section.md) the Human Treatment Applicablity section. This section has five fields; click below to expand guidance for each field: 

??? note "Treatment Investigation Stage or Type"
    **How to answer**
    > This field allows multiple answer selections from a response set, including:
    
    > * Target Discovery
    * Target Mechanism
    * Treatment Discovery
    * Treatment Mechanism
    * Treatment Efficacy
    * Differential Treatment Efficacy
    * Treatment Implementation
    * Treatment Availability or Accessibility.

    > Select all that apply.

    > **For example:**

    > **Target discovery:**
    >> * A study focused on identifying a molecular target that treats pain but is not in the brain, to avoid neurological/addictive effects, or a study focused on identification of a specific social determinant of health that is most impactful on post-surgical pain outcome.
    * A study that developed RNAi reagents against several different proteins in the nociception signaling pathway and is using them to knockdown each protein and observe resulting modifications to pain response, in mice, to determine which protein(s) may be good drug or other intervention targets to modify human pain perception.
    * A longitudinal cohort study following adults at high risk of injury (e.g. construction workers), that 1) measures aspects of mental health, social support and connectivity, economic stability, political engagement, sense of agency, physical environment, etc.; 2) uses multiple metrics at regular time points; and 3) will investigate relationships between these broad sectors and incidence of injury and/or post-injury transitions from acute to chronic pain, to determine possible intervention targets to modify injury risks or post-injury transitions from acute to chronic pain.

    > **Target mechanism:**
    >> * A basic science study using RNAseq and/or mass spectrometry on extracts of cultured mouse DRG neurons, 1) before and after exposure to an in vitro heat pain stimulus model ([ref](https://www.pnas.org/doi/epdf/10.1073/pnas.93.26.15435)), and 2) with or without application of RNAi or a chemical inhibitor of a target molecule in the nociception pathway, to investigate the role of the target molecule in modulating the level and state of mRNA and proteins in neurons, following a pain stimulus.
    * A qualitative study, using focus groups and interviews, to investigate why certain aspects of a person’s economic stability and/or physical environment (e.g. access to green space and well-maintained walkways, etc.) seems to correspond with lower risk of transition from acute to chronic pain in adults with lower back injuries

    > **Treatment discovery:**
    >> * A small molecule screen to identify a drug to inhibit the enzymatic activity of a molecular protein signaling target in the nociception signaling pathway
    * A study identifying groups of adults 1) at high risk of injury and 2) exposed to different (or no) environmental interventions impacting access to green space, to follow incidence of injury and rates of conversion from acute to chronic pain and investigate environmental interventions that may reduce injury risks and/or post-injury acute to chronic pain conversion risks.

    > **Treatment mechanism:**
    >> * A basic science study investigating molecular mechanism opioid vaccine immune responses that are not B-cell/antibody-mediated
    * A study testing efficacy of 1) nurse home visits and/or 2) monthly unconditional cash transfers to new mothers, to improve child development outcomes in newborns exposed to opioids in utero, while parsing the role of each intervention in driving outcomes (select “Treatment Mechanism” and “Treatment Efficacy”)

    > **Treatment efficacy:**
    >> * A stage 3 clinical randomized control trial, randomizing half of individuals to use of a minimally invasive, implanted MOUD-dispensing device plus daily dummy MOUD pills and half to use a dummy device and real MOUD pills to test efficacy of the device in preventing OUD relapse
    * A natural experiment, benefiting from the temporal difference in adoption of the Medicaid expansion across states, to test the efficacy of the Medicaid expansion as an intervention to increase the rate at which individuals with OUD are given and fill a prescription for MOUD

    > **Treatment implementation:**
    >> * A study testing efficacy of a mental health and social determinants screening to guide OUD treatment decisions in community hospital-based physician practices, while collecting qualitative and quantitative data on various aspects and metrics of screening implementation to aid others in the future (select “Treatment Implementation” AND “Treatment Efficacy”).
    * A pilot study testing efficacy of a novel, minimally invasive, implanted MOUD dispensing device to treat OUD patients at high risk of relapse, that also collects qualitative and quantitative data to aid others implementing this type of intervention in the future, including: 1) screening implementation to identify appropriate patients, 2) communication content and delivery to advise patients of their options, 3) protocols and procedures for implantation and follow-up appointments, 4) care and contact with the patient, and 5) any differences based on site of implantation, (select “Treatment Implementation” AND “Treatment Efficacy”).
    * A pilot study testing efficacy of setting up community-based safe injection facilities, while collecting implementation data to aid others with similar interventions (select “Treatment Implementation” AND “Treatment Efficacy”).
    
    > **Treatment availability or accessibility:**
    
    >> * A study surveying all federally funded substance use facilities in the country about their OUD treatment offerings, modes of treatment (e.g. in/outpatient, MOUD/methadone/buprenorphine), and permitted patients (e.g. are there restrictions based on gender, age, health insurance, co-occurring mental health conditions, etc.)
    * A study using EHR and claims data to investigate sociodemographic disparities in how frequently OUD patients are given or fill a MOUD prescription

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, and will allow users to quickly find broad, relevant studies, study data, or study-generated knowledge. Individuals may include:

    > **Target discovery:**

    >> * A pharmacology scientist, with capacity to do high throughput screens for drug library impacts on a target of interest, wants to be up on the research and discovery of novel targets for pain or opioid use treatment to begin designing a screen to figure out how to drug those targets.
    * A local public health official or politician seeks to implement policies or resources to address opioid use relapse in their community and wants to see if specific social or mental/behavioral determinants have been identified as good targets for relapse prevention.
    
    > **Target mechanism:**

    >> * A pain researcher, researching the target mechanism for a biomolecule, wants to learn from other potential research on the mechanism, or understand assays to adopt in their own target mechanism research.
    * A pharmacology scientist’s preliminary research to drug one target failed, due to unacceptable toxicity, and they want to learn more about the original biomolecule target mechanism to see if there is another possible biomolecule in the original target mechanism pathway that they can attempt to drug instead, with acceptable toxicity levels.
    
    > **Treatment discovery:**

    >> * An OUD sufferer is allergic to methadone and has trouble remembering to take buprenorphine to stay in remission, so their family member seeks research on developmental new treatments for OUD that might work better.
    * A clinician treating pain or OUD patients wants to understand recent treatment research, so they can ensure patients access the best treatment in a timely manner.
    
    > **Treatment mechanism:**

    >> * A pain or OUD patient’s doctor prescribed a new medication, and they are curious how it works.
    * A clinician wants to keep up to date on research about the treatments they prescribe, to understand who a treatment may work best for or whether there might be contraindications (due to drug interactions, etc.).
    * A pharmacology researcher wants to learn how a drug works to consider developing new drugs, or formulations of the same drug, that may increase efficacy and/or decrease side-effects.
    
    > **Treatment efficacy:**

    >> * A pain or opioid use patient heard about a novel treatment for their condition and wants to find studies on the treatment’s efficacy or even differential efficacy, to determine if it might be effective/ineffective for them.
    * A researcher is trying to collate all evidence available on a specific treatment/intervention efficacy for a meta-analysis.
    
    > **Treatment implementation:**

    >> * A clinician or administrator at a clinic or jail wants to implement a specific intervention protocol for opioid overdose prevention at their facility and seeks information about protocol implementation best practices.

    > **Treatment availability or accessibility:**

    >> * A pain or opioid use patient and wants to find nearby treatment facilities that offer a specific type of treatment (e.g. MAT with buprenorphine).
    * A researcher wants to understand the impact of treatment/intervention accessibility on uptake, efficacy of the treatment, and how to use the relative availability or non-availability of a treatment, across locations, to design a natural experiment examining the efficacy.

??? note "Treatment Mode"
    **How to answer**
    > This field allows multiple selections from a response set, including “Preventive,"“Therapeutic," “Harm Reduction." Select all that apply. **Descriptions and examples include:**
    
    > **Preventive**: Prevents condition occurrence (e.g. development of a non-opioid drug for pain to prevent opioid exposure and addiction, case management and MAT for pregnant women to prevent in utero exposure to opioids, safe injection and needle exchange center to prevent overdose and spread of blood borne diseases among people using heroin), including:

    >>
    * A basic science or clinical study developing or testing efficacy of an opioid vaccine to promote opioid antibody development of opioid and prevent overdose when the patient is exposed to opioids
    * A randomized control trial cluster testing the efficacy of school-based after-school programming for junior high school students alone, versus after-school programming plus a monthly unconditional cash transfer to the child’s family to prevent future opioid use and dependence.
    * A natural experiment study using medicaid expansion implementation (or not) and differential implementation timing, across states, to investigate a potential role for medicaid expansion in preventing transition from acute to chronic pain in patients with low back injury.
    
    > **Therapeutic**: Treats a condition occurrence (e.g. naloxone to treat opioid overdose, physical therapy to treat existing pain from a back injury), including:

    >>
    * A small molecule screen to identify a chemical drug capable of inhibiting the enzymatic activity of a molecular protein signaling target in the nociception signaling pathway.
    * A stage 3 clinical randomized control trial, randomizing half of individuals to use of a minimally invasive, implanted MOUD-dispensing device plus daily dummy MOUD pills and half to use a dummy device and real MOUD pills to test efficacy of the device in preventing OUD relapse.
    
    > **Harm Reduction:** Is a harm reduction mechanism (e.g. a safe injection and needle exchange site that reduces harm associated with heroin addiction/use, decriminalization of heroin possession or use to reduce the harm associated with heroin addiction/use), including:

    >>
    * A pilot study testing the efficacy of community-based safe injection facilities while collecting implementation data to aid others in the future (select “Treatment Implementation” AND “Treatment Efficacy”).
    * A qualitative study using focus groups to understand why naloxone use, to reverse opioid overdoses, remains low in a community where it is freely available, if picked up at a police station or emergency room facility.

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. **For example:**

    >> **Specifically looking for preventive:**

    >>>
    * A public health official, with money to address local opioid use, seeks a public health intervention to address existing (therapeutic) and prevent future (preventive) OUD harms to individuals in their community.
    * A parent of a student athlete who suffered a sports injury, experiences residual pain, and is being prescribed opioids, seeks information on preventing OUD development during opioid-based pain intervention.
    
    >> **Specifically looking for therapeutic:**

    >>>
    * A clinician seeks therapeutic interventions for their patients.
    * A fibromyalgia patient, with poorly controlled pain, seeks novel pain therapies.
    
    >> **Specifically looking for harm reduction:**

    >>>
    * A clinician treating patients with OUD, some of whom are at high risk of relapse, seeks harm reduction approaches to offer these high risk patients.
    * A mayor of a town with crisis opioid overdose rates and drug-injection associated blood-borne diseases (Hepatitis C and HIV) outbreaks seeks interventions to reduce these concerns as soon as possible.


??? note "Treatment Novelty"
    **How to answer**
    > This field allows multiple answer selections, including “Novel," “Novel, added to established," “Established," and “Established, used in novel population, setting or combination." Select all that apply. **For example:**

    > **Novel:**

    >>
    * A basic science study focused on in vitro and animal model testing of novel mRNA editing to modify molecular pathways for pain signaling in humans
    
    > **Novel, added to established:**

    >>
    * A study testing efficacy of adding opt-in novel support service access (help obtaining housing, food benefits, official identification records, legal advice, free phones, etc.) at safe injection and needle exchange sites (an established harm-reduction intervention)
    
    > **Established:**

    >>
    * A replication study testing efficacy of MOUD for OUD patients
    * A meta-analysis of trials that tested efficacy of an established back surgery to reduce chronic pain in those with low back injuries
    * A study documenting implementation and efficacy for outcomes of established harm reduction strategies, such as community-based safe injection and needle-exchange sites
    
    > **Established, used in novel population, setting or combination:**

    >>
    * A study investigating efficacy of a MAT and community support navigator intervention to reduce risks for those leaving the emergency room following opioid overdose, when the efficacy of this intervention has already been well-established for individuals with history of OUD leaving jail

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, and will allow users to quickly find broad, relevant studies, study data, or study-generated knowledge. **For example:**

    > **Specifically looking for novel:**

    >> * A journalist wants to write a splashy article on novel treatment development or novel uses of established treatments.
    
    > **Specifically looking for novel, added to established:**

    >> * A chronic pain patient on physical therapy and low dose opioids, seeks studies that add to the established treatments for better results
    * A community-based org, running a safe injection and needle exchange site, wants to keep up to date on novel innovations in other communities to add to or modify this established effective intervention
    
    > **Specifically looking for established:**

    >>
    * A public health official, with money to address local opioid use, seeks to ensure funding an evidence-based established intervention.
    
    > **Specifically looking for established, used in novel population, setting or combination:**

    >>
    * A journalist wants to write a splashy article on novel treatment development or novel uses of established treatments.

??? note "Is the Treatment given/applied to individuals or populations?"
    **How to answer**
    > This field allows multiple selections, including “Individual" or “Population." Select all that apply. If the treatment, intervention, or solution is applied individually (e.g. a doctor’s prescription for their patient) or at the population/community/group level (e.g. a city changes good samaritan naloxone laws, implements a safe needle exchange center or education campaign, or adds a park maintenance budget to provide more outdoor exercise access)?

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, allowing users to quickly find broad, relevant studies, study data, or study-generated knowledge. 

    > **For example:**

    >> * **Specifically looking for individual:** A pain or OUD patient seeks treatments that are relevant to the individual.
    * **Specifically looking for population:** A public health official, with money to address local opioid use, wants to allocate the money to population/community level interventions.

??? note "Treatment Type"
    **How to answer**
    > This field allows multiple selections, included in the full metadata model [definitions](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=treatment_type). Select all that apply and classify the treatment, intervention, or solution your by the broad type of intervention

    **How this field will be used**
    > These values will likely be filterable under “Advanced Search” on the HEAL Platform Discovery page, and will allow users to quickly find broad, relevant studies, study data, or study-generated knowledge. **For example:**

    > * A clinician treating pain patients wants to keep up to date on research and development of non-opioid pain drugs and/or non-drug pain treatments.
    * A pain patient read physical therapy, exercise, and/or electrotherapy may help, and seeks research/evidence on these interventions.

Once complete, [collapse](expand-or-collapse-cedar-form-section.md) the Human Treatment Applicability section and [save](save-cedar-form.md) your form.
