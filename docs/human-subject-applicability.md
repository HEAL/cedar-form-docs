# Human Subject Applicability

**Resources:**

* See the full metadata model in [PDF](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.pdf) or [Markdown](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md).
* See the full metadata model [Human Subject Applicability](https://github.com/HEAL/heal-metadata-schemas/blob/main/for-investigators-how-to/study-level-metadata-fields/study-metadata-schema-for-humans.md#:~:text=human_subject_applicability) element.
* See guidance to respond to each field, and their use cases, by clicking the arrow to the left of the bold field names below.

**Extra context:**

* Most of the fields in this section will apply to your study <u>even if your study is not a human subjects study</u> 
* The fields in this section will provide metadata that will allow Platform Users to filter to: 

??? note "[Exclusive] Find studies that will have *clear special applicability* to human populations with specific demographic characteristics that are of interest to the Platform User"
    
    <br>
    **Example**

    > A Platform User wants to find studies that specifically study treatment of pain in <u>women</u>, or prevention of opioid use disorder in <u>adolescents</u> - 
    > Results could respectively include:
    
    >>* a basic science trial studying the differential impact of an opioid drug on pain/nociception signaling pathways in the presence versus absence of estrogen, and 
    * a school-based cluster randomized control trial in high schools testing impact of a combination opioid use disorder education curriculum and peer counseling intervention on opioid use disorder incidence)
    
<!-- <div align="center">OR</div> -->

??? note "[Inclusive] Find studies that *may apply* to human populations with specific demographic characteristics that are of interest to the Platform User because they are conducted either without regard to specific demographic characteristics or are conducted in a manner that is inclusive of the full range of a specific demographic characteristic"

    <br>
    **Example**
    
    > Here the Platform User from the [Exclusive] condition above could broaden their search to find studies that are not super specific to their population of interest but still may have applicable findings and insights; 
    > the Platform User may take this approach if, for example, a more specific [Exclusive] search yields few results - 
    > results could respectively include:
    
    >>* a basic science trial studying the impact of an opioid drug on pain/nociception signaling pathways in a mouse model of lower back injury where both male and female mice are included in the experiments, and 
    * a community-based cluster randomized control trial testing impact of a community-wide postering/flyering communications campaign intervention on opioid use disorder incidence)    
* If your study has **clear special applicability** with respect to a specific demographic characteristic (e.g. biological sex, gender or sexual identity, age), mark all value options within that characteristic category field for which your study has clear special applicability
* If your study **may apply** with respect to a specific demographic characteristic (e.g. biological sex, gender or sexual identity, age) because it is conducted either without regard to that specific demographic characteristics or is conducted in a manner that is inclusive of the full range of that specific demographic characteristic, skip that characteristic category field (mark NONE)
    

**Fill out this section of the CEDAR form:**

[Expand](expand-or-collapse-cedar-form-section.md) the Human Condition Applicability section. This section has seven fields; click below to expand guidance for each field:
 

??? note "To humans of which gender identity(ies) do study results apply"
    
    <br>
    <mark style="background-color: #FFFF00">**How to answer**</mark>
    
    > This field allows multiple answer selections from a response set, including: 'Female', 'Female-to-male transsexual', 'Intersexed', 'Male', 'Male-to-female transsexual', 'Other' 
    
    > If your study has **clear special applicability** to humans of a specific gender identity or identities, <u>mark all that apply</u>
    
    > Examples of studies with **clear special applicability**:
    >> * a basic science study using biochemstry experiments to investigate potential molecular interactions between puberty-blocking drugs and opioid receptor pathways, and using animal model experiments to investigate the impact of co-administration of puberty-blocking drugs and opioids in an adolescent mouse injury pain model on opioid-induced pain-relief and on risk of opioid addiction &rarr; **this study may choose 'Female-to-male transexual', 'Male-to-female transexual', and 'Other'** (puberty blockers can be prescribed to early-adolescents who consider their gender identity to be trans OR non-binary; non-binary would be covered under the 'Other' category)    
    * a clinical trial investigating the efficacy of adding a physical therapy and swim exercise therapy regimen to short-course opioids to prevent transition of acute post-surgical pain to chronic pain in cisgender women and transgender men following surgical mastectomy &rarr; **this study may choose 'Female' and 'Female-to-male transexual'** 

    
    > If your study **may apply** to humans of a specific gender identity or identities because it is conducted either without regard to gender identity or is conducted in a manner that is inclusive of the full range of gender identities, <u>mark NONE of the value options</u>

    > Examples of studies that **may apply**:
    >> * a basic science study using biochemstry experiments to investigate potential molecular interactions between a novel non-opioid analgesic drug and opioid receptor pathways, and using animal model experiments to investigate the impact of co-administration of the novel non-opioid analgesic drug and opioids in an adolescent mouse injury pain model on overall pain-relief and on risk of opioid addiction &rarr; **this study should skip this field, choosing none of the available options** 
    * a clinical trial investigating the efficacy of adding a physical therapy and swim exercise therapy regimen to short-course opioids to prevent transition of acute post-surgical pain to chronic pain in older adults following hip replacement surgery &rarr; **this study should skip this field, choosing none of the available options** 
 

    <mark style="background-color: #FFFF00">**How this field will be used**</mark>

    > The values from this field will likely be available as an "Advanced Search" filter on the HEAL Platform Discovery page, and will allow Platform users to quickly filter down to the broad type of study, study data, or study-generated knowledge in which they are most interested. 
    
    > Example use cases where a Platform User is looking for studies with **clear special applicability** include:

    >> * I am a program manager for a community-based after-school sports program for adolescents that is specifically welcoming to adolescents across the gender-identity spectrum - I know that risk of opioid exposure and addiction once exposed differ and tend to be higher for individuals in a gender identity minority as compared to individuals in a gender identity majority (i.e. cis male or cis female) - I am looking for studies that specifically investigate prevention of opioid use disorder in gender-identity minority adolescents, either in general, or specifically following treatment for pain due to a sports injury. To find such studies, I would filter on the gender identity field, choosing all of the gender identity minority options (i.e. **'Female-to-male transsexual', 'Intersexed', 'Male-to-female transsexual', 'Other'**) or the subset of gender identity minority options I am most interested in (e.g. If several of the program participants are trans boys and I am particulary focused on that group I might just choose **'Female-to-male transsexual'**)
    * I am a clinician that treats trans patients with hormone therapy and gender affirming surgical care - Some of my patients come to me while on meds for maintenance of opioid use disorder remission, or start on these meds while in my care - I am looking for studies that specifically investigate risk factors and mechanisms to address risk for opioid use disorder relapse in trans patients. To find such studies, I would filter on the gender identity field, choosing **'Female-to-male transsexual'** and **'Male-to-female transsexual'**    
        * If I don't find many studies of interest when using these limiting gender identity filters, I may want to expand my search to look for all studies that **may apply** to my population of interest because they are conducted either without regard to gender identity or are conducted in a manner that is inclusive of the full range of gender identities. 
        * To find such studies, I would filter on the gender identity field and choose the **'Conducted without regard to gender identity'** and/or **'Inclusive of all gender identities'** value options. 
        * This filter setting will return studies that indicated their study was conducted without regard to gender identity or inclusive of all gender identities by selecting NONE of the gender identity value options 
       
    

??? note "To humans of which sexual identity(ies) do study results apply"
    
    <br>
    <mark style="background-color: #FFFF00">**How to answer**</mark>
    
    > This field allows multiple answer selections from a response set, including: 'Heterosexual', 'Homosexual (gay/lesbian)', 'Bisexual', 'Asexual', 'Other' 
    
    > If your study has **clear special applicability** to humans of a specific sexual identity or identities, <u>mark all that apply</u>
    
    > Examples of studies with **clear special applicability**:
    >> * a survey of gay and bisexual adults to assess 1) to what extent they have experienced negative reactions among healthcare providers to their sexual identity, 2) to what extent such experiences cause them to delay or forgo healthcare in general, or mental healthcare or pain healthcare in particular, 3) whether they have ever self-medicated to treat mental health or pain issues, and 4) what self-medication mechanisms they have used &rarr; **this study may choose 'Homosexual (gay/lesbian)', and 'Bisexual'**    
    * a basic science study using mouse model experiments to investigate potential changes to mechanism, side-effects, or efficacy of medication such as methadone or buprenorphine for maintaining remission of opioid use disorder when co-administered with a new formulation of PrEP (pre-exposure prophylaxis, to prevent acquisition of HIV) that has [only been approved in men who have sex with men](https://www.reuters.com/article/us-gilead-sciences-fda/fda-panel-backs-gileads-hiv-prevention-drug-descovy-except-in-women-idUSKCN1UX2DD) &rarr; **this study may choose 'Homosexual (gay/lesbian)', 'Bisexual', and maybe 'Other'** 

    
    > If your study **may apply** to humans of a specific sexual identity or identities because it is conducted either without regard to sexual identity or is conducted in a manner that is inclusive of the full range of sexual identities, <u>mark NONE of the value options</u>

    > Examples of studies that **may apply**:
    >> * a survey of a nationally representative sample of US adults to assess 1) to what extent they have experienced negative reactions among healthcare providers to any aspect of their identity including education level, class, race, age, sexual or gender identity, etc., 2) to what extent such experiences cause them to delay or forgo healthcare in general, or mental healthcare or pain healthcare in particular &rarr; **this study should skip this field, choosing none of the available options** 
    * a basic science study using mouse model experiments to investigate potential changes to mechanism, side-effects, or efficacy of medication such as methadone or buprenorphine for maintaining remission of opioid use disorder when co-administered with a standard formulation of PrEP (pre-exposure prophylaxis, to prevent acquisition of HIV) that has been approved for the general adult population &rarr; **this study should skip this field, choosing none of the available options** 
 

    <mark style="background-color: #FFFF00">**How this field will be used**</mark>

    > The values from this field will likely be available as an "Advanced Search" filter on the HEAL Platform Discovery page, and will allow Platform users to quickly filter down to the broad type of study, study data, or study-generated knowledge in which they are most interested. 
    
    > Example use cases where a Platform User is looking for studies with **clear special applicability** include:

    >> * I am a public health official in a community that has evidence that an uptick in opioid overdoses among older gay adults may be partially attributed to self-medicating chronic pain with street opioids - I am looking for studies that specifically investigate risk factors for self-medicating chronic pain in older gay adults. To find such studies, I would filter on the sexual identity field, choosing **'Homosexual (gay/lesbian)'**
    * I am the parent of a teenager who has just come out as gay - There's been a spate of opioid overdoses at my kid's highschool, so I'm already concerned about them, and I've heard that gay teenagers are at higher risk of substance use in general - I am looking for studies that specifically investigate whether there is a differential risk for opioid use in gay versus straight teenagers, or that look at risk factors and mechanisms to address risk for opioid first use, opioid addiction, and opioid overdose specifically in gay teenagers. To find such studies, I would filter on the sexual identity field, choosing **'Homosexual (gay/lesbian)'**    
        * If I don't find many studies of interest when using these limiting gender identity filters, I may want to expand my search to look for all studies that **may apply** to my population of interest because they are conducted either without regard to sexual identity or are conducted in a manner that is inclusive of the full range of sexual identities. 
        * To find such studies, I would filter on the sexual identity field and choose the **'Conducted without regard to sexual identity'** and/or **'Inclusive of all sexual identities'** value options. 
        * This filter setting will return studies that indicated their study was conducted without regard to sexual identity or inclusive of all sexual identities by selecting NONE of the sexual identity value options 
    

??? note "To humans of which biological sexes do study results apply"

    <br>
    <mark style="background-color: #FFFF00">**How to answer**</mark>
    
    > This field allows multiple answer selections from a response set, including: 'Ambiguous', 'Female', 'Male' 
    
    > If your study has **clear special applicability** to humans of a specific biological sex, <u>mark all that apply</u>
    
    > Examples of studies with **clear special applicability**:
    >> * a basic science trial studying the differential impact of an opioid drug on pain/nociception signaling pathways in the presence versus absence of estrogen to investigate potential differences in pain relief achieved in men versus women &rarr; **this study may choose 'Female'**    
    * a clinical trial to test the efficacy of treating migraine pain in pregnant women with a combination of water/swim and massage therapy &rarr; **this study may choose 'Female'**  

    
    > If your study **may apply** to humans of a specific biological sex or sexes because it is conducted either without regard to biological sex or is conducted in a manner that is inclusive of the full range of biological sex, <u>mark NONE of the value options</u>

    > Examples of studies that **may apply**:
    >> * a basic science trial studying the molecular mechanism of an opioid drug on pain/nociception signaling pathways in the presence of cytokines involved in acute versus chronic inflammatory responses to investigate potential differences in pain relief and mechanisms of that pain relief achieved in acute versus chronic pain conditions &rarr; **this study should skip this field, choosing none of the available options** 
    * a clinical trial to test the efficacy of treating migraine pain in older adults with a combination of water/swim and massage therapy &rarr; **this study should skip this field, choosing none of the available options** 
 

    <mark style="background-color: #FFFF00">**How this field will be used**</mark>

    > The values from this field will likely be available as an "Advanced Search" filter on the HEAL Platform Discovery page, and will allow Platform users to quickly filter down to the broad type of study, study data, or study-generated knowledge in which they are most interested. 
    
    > Example use cases where a Platform User is looking for studies with **clear special applicability** include:

    >> * I am a urologist who performs vasectomies regularly - Some of my patients complain of severe pain following the procedure, and I know that some of my colleagues prescribe opioids for post-surgical pain following vasectomy - I am looking for studies that specifically investigate the efficacy of opioids in relieving post-surgical pain in men following outpatient surgical procedures, as well as studies looking at risk of addiction and risk factors for addiction in this population under these opioid prescription circumstances. To find such studies, I would filter on the biological sex field, choosing **'Male'**
    * I am a women's swim coach and have several members of my team who deal with chronic pain from sports injuries - I am looking for studies that specifically investigate treatment for chronic pain caused by sports injuries in women, and maybe also for studies that investigate risk factors for, and how to prevent, conversion of acute pain from a sports injury to chronic pain so that I can help/inform my team members who suffer an injury while on my team. To find such studies, I would filter on the biological sex field, choosing **'Female'**    
        * If I don't find many studies of interest when using these limiting biological sex filters, I may want to expand my search to look for all studies that **may apply** to my population of interest because they are conducted either without regard to biological sex or are conducted in a manner that is inclusive of the full range of biological sex. 
        * To find such studies, I would filter on the biological sex field and choose the **'Conducted without regard to biological sex'** and/or **'Inclusive of all biological sex'** value options. 
        * This filter setting will return studies that indicated their study was conducted without regard to biological sex or inclusive of all biological sex by selecting NONE of the biological sex value options 
    
??? note "To humans of which age/developmental stage do study results apply"

    <br>
    <mark style="background-color: #FFFF00">**How to answer**</mark>
    
    > This field allows multiple answer selections from a response set, including: 'Fetus', 'Infant, newborn (Birth to 1 month)', 'Infant (1 to 23 months)', 'Child, preschool (2 to 5 years)', 'Child (6 to 12 years)', 'Adolescent (13 to 18 years)', 'Adult (19 to 44 years)', 'Middle aged adult (45 to 64 years)', 'Aged adult (65 to 79 years)', 'Aged, 80 and over (80 years and over)' 
    
    > If your study has **clear special applicability** to humans of a specific age/developmental stage, <u>mark all that apply</u>
    
    > Examples of studies with **clear special applicability**:
    >> * a basic science trial looking to develop an in vitro tissue chip model of an innervated joint to study the development and treatment of osteoarthritic pain due to chronic mechanical and other stresses on the joint, where the joint tissue in the model is explicitly formulated to mimic joint tissue in older adults (e.g. less synovial fluid, thinner cartilage layer, etc.) in order to specifically study this process in older adults &rarr; **this study may choose 'Aged adult (65 to 79 years)', and 'Aged, 80 and over (80 years and over)'**    
    * a clinical trial to test the efficacy of treating migraine pain in adolescents with a combination of water/swim and massage therapy &rarr; **this study may choose 'Adolescent (13 to 18 years)'**  

    
    > If your study **may apply** to humans of a specific age/developmental stage or stages because it is conducted either without regard to age/developmental stage or is conducted in a manner that is inclusive of the full range of age/developmental stage, <u>mark NONE of the value options</u>

    > Examples of studies that **may apply**:
    >> * a basic science study looking to develop an in vitro tissue chip model of an innervated joint to study the development and treatment of osteoarthritic pain due to chronic mechanical and other stresses on the joint, where the joint tissue in the model is explicitly formulated to mimic joint tissue in the 'average' human &rarr; **this study should skip this field, choosing none of the available options** 
    * a clinical trial to test the efficacy of treating migraine pain in adults (no age exclusions other than over 18) with a combination of water/swim and massage therapy &rarr; **this study should skip this field, choosing none of the available options** 
 

    <mark style="background-color: #FFFF00">**How this field will be used**</mark>

    > The values from this field will likely be available as an "Advanced Search" filter on the HEAL Platform Discovery page, and will allow Platform users to quickly filter down to the broad type of study, study data, or study-generated knowledge in which they are most interested. 
    
    > Example use cases where a Platform User is looking for studies with **clear special applicability** include:

    >> * I am an older adult (just had my 85th birthday!) who has dealt with chronic pain for decades - I feel like the treatment regimen that used to work for me no longer does and I think it may be because of my advancing age, including just normal changes to my body and complications from other health conditions and drugs I take for those conditions that have cropped up over the years - I am looking for studies that specifically investigate treatments for chronic pain in older people. To find such studies, I would filter on the age/developmental stage field, choosing **'Aged adult (65 to 79 years)', and/or 'Aged, 80 and over (80 years and over)'**
    * I am the parent of an elementary-school aged child who is scheduled for a serious surgery - I've been advised that my child will be in a lot of pain after the surgery and will be prescribed opioids to manage the pain - I am looking for studies that specifically investigate severity of post-surgical pain in children following surgery of similar types to the kind my child will undergo, how to treat post-surgical pain in children, and risks associated with taking opioids for post-surgical pain in children my child's age. To find such studies, I would filter on the age/developmental stage field, choosing **'Child (6 to 12 years)'**    
        * If I don't find many studies of interest when using these limiting biological sex filters, I may want to expand my search to look for all studies that **may apply** to my population of interest because they are conducted either without regard to age/developmental stage or are conducted in a manner that is inclusive of the full range of age/developmental stage. 
        * To find such studies, I would filter on the age/developmental stage field and choose the **'Conducted without regard to age/developmental stage'** and/or **'Inclusive of all age/developmental stage'** value options. 
        * This filter setting will return studies that indicated their study was conducted without regard to age/developmental stage or inclusive of all age/developmental stage by selecting NONE of the age/developmental stage value options 
    

??? note "To humans in which special vulnerability categories do study results apply"

    <br>
    <mark style="background-color: #FFFF00">**How to answer**</mark>
    
    > This field allows multiple answer selections from a response set, including: 'Pregnant women', 'Human fetuses', 'Neonates', 'Prisoners', 'Children', 'Individuals with physical disabilities', 'Individuals with mental disabilities or cognitive impairments', 'Economically disadvantaged', 'Socially disadvantaged', 'Terminally ill or very sick', 'Racial or ethnic minorities', 'Institutionalized persons (for example, persons in correctional facilities, nursing homes or mental health facilities)'
    
    > If your study has **clear special applicability** to humans of a specific special vulnerability category, <u>mark all that apply</u>
    
    > Examples of studies with **clear special applicability**:
    >> * a basic science study using a mouse model of endometriosis in female mice pre/post and +/- being impregnated to investigate the impact of pregnancy on pain caused by endometriosis and on efficacy of a panel of accepted treatments for endometriosis pain &rarr; **this study may choose 'Pregnant women'**
    * a basic science study using a mouse model of migraine pain in the context of a mouse model of social stress/isolation (e.g. identification of 'socially dominant' and 'socially subordinate mice' within the population) to investigate the impact of social stress/isolation on pain caused by migraine and on efficacy of a panel of accepted treatments for migraine pain &rarr; **this study may choose 'Socially disadvantaged'**
    * a clinical trial enrolling neonates exposed to opioids in utero to test efficacy of a treatment to prevent developmental delays caused by in utero exposure &rarr; **this study may choose 'Neonates'** 
    * a cluster randomized control trial at the community level testing the efficacy of establishing high quality, free or low cost child care centers for younger children and community centers with after-school programming and supervised outdoor and indoor open spaces for older children and adolescents to prevent opioid exposure and opioid overdose in children and teens    in the community, where communities targeted must have a median income 30% lower than the median income of the city/metro area in which it is located &rarr; **this study may choose 'Economically disadvantaged'**   
    * a randomized control trial investigating the efficacy of providing community resource connection support plus gauranteed  MAT (medication assisted treatment) to individuals with a history of opioid use disorder as they exit a jail or prison institution to prevent opioid overdose events in this population &rarr; **this study may choose 'Institutionalized persons (for example, persons in correctional facilities, nursing homes or mental health facilities)'**  

    
    > If your study **may apply** to humans of a specific special vulnerability category or categories because it is conducted either without regard to special vulnerability category or is conducted in a manner that is inclusive of the full range of special vulnerability categories, <u>mark NONE of the value options</u>

    > Examples of studies that **may apply**:
    >> * a basic science study using a mouse model of endometriosis in female mice to investigate the risk factors for and mechanism of development of pain caused by endometriosis, and to investigate the potential efficacy of a novel vibration therapy device to prevent and treat endometriosis pain &rarr; **this study should skip this field, choosing none of the available options** 
    * a randomized control trial investigating the efficacy of offering community resource connection support plus gauranteed MAT (medication assisted treatment) to individuals with opioid use disorder (OUD) as soon as they consult a physician about OUD concerns, or as they exit an emergency room following an ER visit for opioid overdose &rarr; **this study should skip this field, choosing none of the available options** 
 

    <mark style="background-color: #FFFF00">**How this field will be used**</mark>

    > The values from this field will likely be available as an "Advanced Search" filter on the HEAL Platform Discovery page, and will allow Platform users to quickly filter down to the broad type of study, study data, or study-generated knowledge in which they are most interested. 
    
    > Example use cases where a Platform User is looking for studies with **clear special applicability** include:

    >> * I am a midwife at a community hospital where I see a lot of women give birth to infants who have been exposed to opioids in utero - I want to design and propose a program to hospital management that will help support pregnant women in achieving or maintaining remission of existing opioid use disorder (OUD) during and after their pregnancy - I am looking for studies that specifically investigate treatments or interventions for OUD in pregnant women and risk factors for OUD relapse in pregnant women to help me design an appropriate intervention and think about the best targeting approach if the program is approved but spaces in the program are limited due to resource constraints. To find such studies, I would filter on the special vulnerability categories field, choosing **'Pregnant women'**
    * I am the warden of a county jail - the county department of public health has contacted me to let me know that they have seen a large number of opioid overdose deaths of individuals who overdose just days after being released from the county jail - I am looking for studies that specifically investigate therapeutic interventions that might lead to durable remission of opioid use disorder (OUD) in individuals who are currently incarcerated and/or therapeutic interventions that might prevent OUD relapse upon release from jail and/or harm reduction interventions that might prevent opioid overdose upon release from jail even in the face of OUD relapse. To find such studies, I would filter on the special vulnerability categories field, choosing **'Institutionalized persons (for example, persons in correctional facilities, nursing homes or mental health facilities)'**    
        * If I don't find many studies of interest when using these limiting special vulnerability category filters, I may want to expand my search to look for all studies that **may apply** to my population of interest because they are conducted either without regard to special vulnerability category or are conducted in a manner that is inclusive of the full range of special vulnerability categories. 
        * To find such studies, I would filter on the special vulnerability category field and choose the **'Conducted without regard to special vulnerability category'** and/or **'Inclusive of all special vulnerability categories'** value options. 
        * This filter setting will return studies that indicated their study was conducted without regard to special vulnerability category or inclusive of all special vulnerability categories by selecting NONE of the special vulnerability category value options 
   
    

??? note "To humans in which geographical locations do the study results apply"

    <br>
    <mark style="background-color: #FFFF00">**How to answer**</mark>
    
    > This field only applies if your study enrolls or considers human subject. If your study does not enroll human subjects skip this field, leaving it blank.

    > This field allows multiple answer selections from a response set, including: 'Non US', 'US - National', 'US - Specific States', 'US - Specific Counties', 'AK', 'AL', 'AR', 'AZ', 'CA', 'CO', 'CT', 'DE', 'FL', 'GA', 'HI', 'IA', 'ID', 'IL', 'IN', 'KS', 'KY', 'LA', 'MA', 'MD', 'ME', 'MI', 'MN', 'MO', 'MS', 'MT', 'NC', 'ND', 'NE', 'NH', 'NJ', 'NM', 'NV', 'NY', 'OH', 'OK', 'OR', 'PA', 'RI', 'SC', 'SD', 'TN', 'TX', 'UT', 'VA', 'VT', 'WA', 'WI', 'WV', 'WY'

    > For studies with human subjects, from which geographic location(s) are subjects recruited?
    >> * If subjects are recruited from anywhere in the US without further restriction on geographic location, choose only 'US - National'. 
    * If subjects are recruited in the US only in specific state(s), choose 'US - Specific States', then also select the abbreviation of each of the specific states from which subjects are recruited. 
    * If subjects are recruited in the US from specific county(ies) within specific state(s), please choose 'US - Specific States' and 'US - Specific Counties', then also select the abbreviation of each of the specific states from which subjects are recruited.
    
    > Examples:
    >> * a school-based cluster-randomized control trial within the city of Atlanta that randomizes all of the high schools in Atlanta to test the efficacy of full versus partial subsidization of high quality after-school programming to increase participation in after-school programming, and to prevent opioid exposure, opioid use disorder, and opioid overdose in high school students through graduation and in the 2 years following graduation &rarr; **this study may choose 'US - Specific States', and 'US - Specific Counties' and 'GA'**    
    * a multi-site state prison-based trial targeting individuals leaving prison who have a history of opioid use disorder (OUD), and testing efficacy of providing connection to a local social worker and other local community resources to prevent OUD relapse and opioid overdose in the year after prison exit, where prisons participating are in Illinois, Kentucky, Maryland, Massachusetts, and Nebraska &rarr; **this study may choose 'US - Specific States', and 'IL', 'KY', 'MD', 'MA', and 'NE** 
    * a nationally representative survey of US adults to assess their attitudes towards opioid use disorder and individuals with opioid use disorder &rarr; **this study may choose 'US - National'** 

    

    <mark style="background-color: #FFFF00">**How this field will be used**</mark>

    > The values from this field will be accessible to browse on the study's HEAL Data Platform study page and will give Platform users who find the study a sense for how generalizable the study may be. For example, if a community based trial of an intervention for OUD shows great results but it was tested in NYC and I'm looking for an intervention that will work in a small town in the midwest, I may want to really consider if/how the results will translate across contexts.

    > These values may also provide information that will aid a Platform user looking to perform a meta-analysis of study results to synthesize across and provide more generalizable conclustions or to create a synthetic cohort across similar studies consisting of enrolled human subjects in different geographic locations again, at least in part, to provide answers to similar questions as the originating studies but with more generalizability

    > These values may also provide information that will aid a Platform user looking to ask research questions about how state level policies or other state-level environmental factors may play a role/impact results of a specific study interventions approach (e.g. an intervention that provides connection to a social worker to individuals with history of OUD upon exit from prison may be very effective in a state that 1) has a strong educational infrastructure to train social workers, 2) provides loan forgiveness or other financial supports/incentives to social workers, 3) has policies in place to fully fund community health centers that have providers licensed to prescribe buprenorphine, etc. - the same intervention may be totally ineffective in a state where these conditions do not exist, perhaps making social workers scarce, overloaded, and unable to find resources for their clients) 
       
    

Once complete, [collapse](expand-or-collapse-cedar-form-section.md) the Human Subject Applicability section and [save](save-cedar-form.md) your form.
