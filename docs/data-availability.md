# Data Availability

* Many fields in the Data Availability section should be updated throughout a HEAL study’s life-cycle (e.g. a field called “data collection status” will change from “not started” to “started” to “finished”).
* To update your study’s metadata as your study progresses, please contact the Platform Help Desk at heal-support@datacommons.io..

* Expand the Data Availability section. This section has 10 fields; (<mark>click below to expand guidance for each field</mark>):

??? note "Will the study collect or produce data? Yes/No"
    **How to answer**
    > Not all HEAL studies collect or produce data. Some develop methods and protocols for future studies. If your study will NOT collect or produce data, but will produce shareable products other than data (e.g. protocols, slide decks, etc.), answer “No.”
    
    **How this field will be used**
    > This field allows Platform users to filter between studies that will collect or produce data, and those that will not.
    

??? note "Will the study make data available? None/Some/All"

    **How to answer**
    > This field ONLY APPLIES if you answered “Yes” to “Will the study collect or produce data?”

    > Answers include: 
    
    >> *None*: If you do not plan to make any study data available in a HEAL approved repository, select “None.” While most HEAL studies are obligated to share data, select HEAL studies, such as SBIR grants, are not.
    
    >> *Some*: If you plan to make some, but not all, study data available, select “Some.” For example, you may plan to share data needed to reproduce publications, processed data files, or extensively de-identified data, but exclude certain datasets or sources (such as administrative data, when your data sharing agreement does not allow sharing).
    
    >> *All*: If you plan to make study data available to the greatest extent possible (e.g. sharing nearly raw clinical trial data in a data repository, subject to very strong access controls, including some data that may be very useful for analysis but pose a risk of re-identification, such as highly granular geographic information, detailed diagnostic and care provision, utilization patterns, and/or clinician notes), select “All.”

    **How this field will be used**
    >  This field will allow users to filter between studies that will share data, and those that will not. Some users, especially those interested in re-identification risks from dataset features (e.g. high geographic granularity), may want to view studies that plan to share “All” data, not just extensively de-identified data.

??? note "Will available data have restrictions on access? None/Some/All"
    **How to answer**
    > This field ONLY APPLIES if you answered “Yes” to “Will the study collect or produce data?” AND you answered “Some” or “All” to “Will the study make data available?”

    > Answers include

    >> None: If all your repository-hosted study data will be open access or minimally restricted (i.e. available after signing a minimal DUA that does not require any manual intervention or approval).
    
    >> Some: If some of your repository-hosted study data will be open access or minimally restricted, while other data will be available only after a request and approval process that does require substantial manual intervention (e.g. submission of a project proposal and IRB approval by the requestor; review by a Data Access Committee on the repository end; etc.). For example, a clinical trial may choose this option when sharing 1) an extensively de-identified dataset that is open access/minimal access controls, AND 2) a less de-identified dataset, shared under strict access controls, that includes features to add value for analysis questions but also presents substantial risk for re-identification.
    
    >> All: If all your repository-hosted study data will be available only following a request and approval process requiring substantial manual intervention (e.g. submission of a project proposal and IRB approval by the requestor; review by a Data Access Committee on the repository end; etc.). For example, a clinical trial may choose this option when ONLY sharing a less de-identified dataset with features to add value for analysis questions, while presenting substantial risk for re-identification, shared under strict access controls. These studies WILL NOT share a extensively de-identified version of the data as open access/minimal access controls.
    
    **How this field will be used**
    > This field will allow users looking for easy data access to filter for studies sharing some, or all, of their data as open access/minimal access controls.

??? note "Has data collection/production started? Not started/Started/Finished"
    **How to answer**
    > This field ONLY APPLIES if you answered “Yes” to “Will the study collect or produce data?”

    > Answers include:
    
    >> - _Not started_: If your study, including studies with multiple parts/aims, has not started collecting ANY data.
    - _Started_: If your study, including studies with multiple parts/aims, started collecting ANY data.
    - _Finished_: If your study, including studies with multiple parts/aims, finished collecting ALL data.
    
    > This field should be updated as a HEAL study moves through its life-cycle - see [information on how to update.](update-cedar-form-metadata.md)

    **How this field will be used**
    > This field allows users to filter studies that are at different stages of data collection, including studies where findings/results can be expected soon.

??? note "Has data release started? Not started/Started/Finished"
    **How to answer**
    > This field ONLY APPLIES if you answered “Yes” to “Will the study collect or produce data?” AND you answered “Some” or “All” to “Will the study make data available?”

    > Answers include:
    
    >> - _Not started_: if your study, including studies with multiple parts/aims, has not started making ANY study data available in a repository for long-term data sharing.
    - _Started_: if your study, including studies with multiple parts/aims, started making ANY study data available in a repository for long-term data sharing, but is not finished (i.e. will share more data later).
    - _Finished_: if your study, including studies with multiple parts/aims, finished making ALL study data available in a repository for long-term data sharing (i.e. no further data to share).

    > This field should be updated as a HEAL study moves through its life-cycle - see [information on how to update.](update-cedar-form-metadata.md)

    **How this field will be used**
    > This field allows users to filter useful study data at different stages of data release. Filtering for later stage data release (e.g. “Started” or “Finished”) helps users find studies that already have data available for Platform users. This field will also allow users more interested in study findings/results than data, to finf studies where a publication with findings/results are available or can be expected soon.

??? note "Date when first/last data will be collected/produced or released"
    **Entries include:**

    > - **Date when first data will be collected/produced:** First study participant enrolled in a clinical trial.
    - Date **when last data will be collected/produced:** Last measurement on last study participant enrolled in a clinical trial.
    - **Date when first data will be released:** First dataset with accompanying metadata deposited in data repository.
    - **Date when last data will be released:** Final dataset with accompanying metadata deposited in data repository; no more data deposits anticipated.

    **How to answer**
    > ALL fields ONLY APPLY if you answered “Yes” to “Will the study collect or produce data?”

    > DATA RELEASE dates ONLY APPLY if you ALSO answered “Some” or “All” to “Will the study make data available?”

    > Provide the existing or anticipated date in MM/DD/YYYY format. After you enter each field, click the calendar icon to the right to open a calendar interface and select your date. Dates should be updated if they change - see [information on how to update](update-cedar-form-metadata.md).

    **How these fields will be used
    > Platform users can view the start date on each study’s details page, allowing interested users to understand study timing, and when to expect data or publications/findings.

??? note "Will the study produce shareable products other than data? Yes/No"
    **How to answer**
    > If your study will produce shareable products other than data (e.g. protocols, slide decks, data dictionaries, etc.), answer “Yes.”

    **How this field will be used**
    > Some HEAL studies do “pre-work” for other HEAL studies (e.g. protocol development) and do not collect data. Others (i.e. small business grant studies) are not obligated to share data. This field allows users 1) looking for non-data materials such as protocols, and/or 2) interested in learning about studies that will not share data (such as small business grant studies), to explore contacting study leads to develop a collaborative relationship. Once complete, [collapse](expand-or-collapse-cedar-form-section.md) the Data Availability section and [save](save-cedar-form.md) your form.

Once complete, [collapse](expand-or-collapse-cedar-form-section.md) the Data Availability section and [save](save-cedar-form.md) your form.
