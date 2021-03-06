## Data use
|  Feature | Status | Next step | HELP! |
| :--- | :--- | :--- | :--- |
|  Machine readable consent clauses (MRCC) using DUO |![done](assets/img/done.png)  | Unanimously approved SC July 2020 | Apply to a new (virtual/synthetic) or emerging cohort with e.g. EU 1 million genomes, Covid-19 portal, CINECA etc. |
|  Publicize/promote MRCC | ![in progress](assets/img/green_dot.png)  | Share examples of MRCC-enabled consent forms in use<br/><br/>Request IRBs, institutions, and government funders to share templates or examples of consent forms using MRCC language<br/><br/>Jacqueline Lane’s Circadian Rhythms study is one of the first adopters of the MRCC guidance, and used it to draft the study consent form | **Early adopters** |
|  User experience to improve understanding and adoption of DUO | ![in progress](assets/img/green_dot.png) | Research plan being prepared. Interviews planned around Oct/Nov | Write a template section to be included in the researcher data management plan - how DUO should be used in the (regulated) data created by a project? |
|  Expand DUO Documentation for easier use | ![in progress](assets/img/green_dot.png) | Use of Mondo guideline including mapping to other ontologies. Needs to be published once UX done for better guidance. |  |
|  ‘Code your Dataset with DUO’ tool | ![in progress](assets/img/green_dot.png) |  |  |
|  International Language Representation | ![in progress](assets/img/green_dot.png) | Moving forward with Japanese, Spanish, French, and German translations of the DUO | **French, German, Spanish?** |
|  SchemaBlocks Representation & tooling | ![attention required](assets/img/orange_dot.jpg) | Schema available. No implementation at the moment. Status of SchemaBlock unclear. |  |
|  DUO updates | ![attention required](assets/img/orange_dot.jpg) | Acknowledged need and initial discussions. Needs more planning.<br/>Separate categories for Permissions vs. Modifiers<br/><br/>Move POA from Permission to Modifier<br/><br/>Create NPU and NCU separate sub-terms for NPU as-is |  |
|  Work with FHIR Resource Consent to have them embed/map to DUO terms- xSDO activity | ![attention required](assets/img/orange_dot.jpg) | Initial discussions with a group interested in bridge FIHR-DUO. Needs expertise from FHIR. | **FIHR expert** |
|  Separate purposes from other specific information | ![attention required](assets/img/orange_dot.jpg) | Needs driving use case and task lead |  |
|  Specification of data storage period | ![attention required](assets/img/orange_dot.jpg) | Needs driving use case and task lead |  |
|  Specification of legal basis | ![attention required](assets/img/orange_dot.jpg) | Needs driving use case and task lead |  |
|  Introduce Risk levels or modifiers within the DUO-Passport interoperability plan. | ![non goal](assets/img/non_goal.png) |  |  |
|  Specifications <ul><li>for personal data and source of personal data <li>of processing operation and method</li> <li>of recipients of personal data</li> <li>of recipient country</li> <li>of risks</li></ul> | ![non goal](assets/img/non_goal.png) |  |  |
|  Information on quality requirements for clause, consent dialogue design and consent choices | ![non goal](assets/img/non_goal.png) |  |  |
|  Accessibility quality requirements for clauses, consent dialogue design and consent choices | ![non goal](assets/img/non_goal.png) |  |  |


## Researcher Identities
|  Feature | Example | Status | Next step |
| :--- | :--- | :--- | :--- |
|  Additional Role Values | ga4gh.clinical-care-professional@example.org | ![non goal](assets/img/non_goal.png) | * Clinical Care Professionals & Industry researchers<br/><br/> * Explore the model of Institutional Signing Official status visa in their Passport to indicate that the holder of this visa is an institutional SO and can co-sign a data access agreement/application together with the researcher. Find a solution to making researcher verification as lightweight as possible. |
|  Passport v1.1 | scoped down passports for specific use cases | ![in progress](assets/img/green_dot.png) | Additional guidance as required for enhancements to Passports spec & Driver adoption, e.g. broader trust framework:<br/> * Assurance levels (identity proofing) -- with DSWS<br/> * Visa flow into and out of the EU regarding Researcher PII<br/> * Audit logging<br/> --Requirements scoping<br/> -- Mechanism for logging<br/> -- What gets audited? Policy of exposure.<br/> * Data sensitivity guidance for access policy<br/> * Example implementations, testbeds, explanatory documentation or users and brokers |
|  Passport Journal Paper |  | ![attention required](assets/img/orange_dot.jpg) | Publish a Passport paper in a journal discussing the research goals, technical challenges, and approach to overcome those challenges. |
|  Passport v1.2 or v1.3 |  | ![blocked](assets/img/red_dot.png) | Connect with Discovery, Beacon, Cloud & other GA4GH APIs that expect an access token. Details forthcoming<br/><br/>Create end-to-end technical demonstration with these teams<br/><br/>Take feedback and enhance Passport spec as needed to clarify how to use with FASP scenarios |
|  DUO-Passport Connector |  | ![in progress](assets/img/green_dot.png) | Streamlining DAC review processes using DUO codes and Passports together as part of the application<br/><br/>Passports used by DACs for applicant “identity” information<br/><br/>DACs issue ControlledAccessGrant Visas<br/><br/>SO pre-approval visa for PIs to apply to DAC (see Library Cards)<br/><br/>Partner engagement Cohorts/DACs/data holders NHGRI, Sanger, THL, AGHA, CanDIG, MSSNG, AMED/GEM etc. Collect technical resources from the DPs: main contact, contact for data access procedures, key adoption contacts <br/><br/>Possibly build an integrated solution for use cases from national and continental scale (e.g. Cohorts surveyed in the CINECA project) |
|  Passport v2.0 | "passport": {<br/> ver: 2.0,<br/> visas: {<br/> "example.org": {<br/> "value1": [<v1>,<v2>]<br/> }<br/> }<br/>} | ![in progress](assets/img/green_dot.png) | Rework Passport visa container structure (is a list in v1.0) to improve inspection/unpacking and versioning.<br/><br/>Change rules for how to handle missing Visa fields to improve future backwards compatibility. |
|   |  |  |  |
|   |  |  |  |
  
done: ![done](assets/img/done.png) 

In progess: ![in progress](assets/img/green_dot.png)

Attention required: ![attention required](assets/img/orange_dot.jpg)

Non-goal: ![non goal](assets/img/non_goal.png)

Blocked: ![blocked](assets/img/red_dot.png)
