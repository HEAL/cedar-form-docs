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
    
    > This field allows multiple answer selections from a response set, including: Female, Female-to-male transexual, Intersexed, Male, Male-to-female transexual, Other 
    
    > If your study has **clear special applicability** to humans of a specific gender identity or identities, <u>mark all that apply</u>
    
    > Examples of studies with **clear special applicability**:
    >> * a basic science study using biochemstry experiments to investigate potential molecular interactions between puberty-blocking drugs and opioid receptor pathways, and using animal model experiments to investigate the impact of co-administration of puberty-blocking drugs and opioids in an adolescent mouse injury pain model on opioid-induced pain-relief and on risk of opioid addiction &rarr; **this study may choose "Female-to-male transexual", "Male-to-female transexual", and "Other"** (puberty blockers can be prescribed to early-adolescents who consider their gender identity to be trans OR non-binary; non-binary would be covered under the "Other" category)    
    * a clinical trial investigating the efficacy of adding a physical therapy and swim exercise therapy regimen to short-course opioids to prevent transition of acute post-surgical pain to chronic pain in cisgender women and transgender men following surgical mastectomy &rarr; **this study may choose "Female" and "Female-to-male transexual"** 

    
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
    **How to answer**
    
    **How this field will be used**
    

??? note "To humans of which biological sexes do study results apply"
    **How to answer**
    
    **How this field will be used**
    
??? note "To humans of which age/developmental stage do study results apply"
    **How to answer**
    

    **How this field will be used**
    

??? note "To humans in which special vulnerability categories do study results apply"
    **How to answer**
    

    **How this field will be used**
    

??? note "To humans in which geographical locations do the study results apply"
    **How to answer**
    

    **How this field will be used**
    

Once complete, [collapse](expand-or-collapse-cedar-form-section.md) the Human Subject Applicability section and [save](save-cedar-form.md) your form.
