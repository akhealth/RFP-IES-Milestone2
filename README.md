## Instructions

This repository will be used to handle Q/A, and will serve as the repository for the IES Milestone 2 project RFP release from the Alaska Department of Health (DOH) Division of Public Assistance (DPA).

### RFP Schedule
The RFP schedule set out herein represents the State of Alaska's best
estimate of the schedule that will be followed. If a component of this
schedule, such as the deadline for receipt of proposals, is delayed, the
rest of the schedule may be shifted by the same number of days. **All
times are Alaska Prevailing Time**.


-   Issue RFP on XXXXXX

-   Deadline for receipt of questions on XXXXX

-   Deadline for receipt of proposals on XXXX

-   Proposal Evaluation Committee complete evaluation XXXX

-   State of Alaska issues Notice of Intent to Award a Contract by XXXXX

-   State of Alaska issues contract on XXXXX

-   Contract begins XXXXX


All Questions must be received by **XXXXX** in the form of an issue posted to this repository. 



## Important note about referenced documentation

You'll notice that we link to a number of working documents in our RFP and related materials.  Interested vendors should be aware that all of these documents are subject to change because Alaska is continuing to learn more as we continue prototyping and working with various elements of the existing system to build out our DevSecOps capabilities.  In addition to paying close attention to this repository, we encourage interested vendors to "Watch" what's going on in [the DPA Eligibility Modernization repo](https://github.com/akhealth/EIS-Modernization).  We don't anticipate anything that we learn or change in this environment to alter how an interested vendor would staff up their proposed teams.  As discussed throughout the RFP, we are interested in vendors that are open to such changes without requiring a static set of requirements at the time of the RFP.

### Background Information

Alaska Statute
[47.05.010](https://www.akleg.gov/basis/statutes.asp#47.05.010)
designates Department of Health (DOH), Division of Public Assistance
(DPA) as having responsibility for determining eligibility and
administration of Alaska’s public assistance programs. As a part of this
designation, DPA is charged with determining eligibility for each of the
programs based on state and federal regulation, governed by Alaska
Administrative Code, [Title
7](https://www.akleg.gov/basis/aac.asp#1.05). Our mission is to “promote
self-sufficiency and provide basic living expenses to Alaskans in need.”

This includes the following programs:

- Adult Public Assistance (APA)
- Alaska Temporary Assistance Program (ATAP)
- ATAP Work Services
- Childcare
- Chronic and Acute Medical Assistance (CAMA)
- Family Nutrition
- General Relief Assistance
- Heating Assistance
- Interim Assistance
- Medicaid
  - Modified Adjusted Gross Income (MAGI)
  - Denali KidCare (SCHIP)
  - Aged, Disabled, Blind, and Long-Term Care
- Permanent Fund Dividend Hold-Harmless
- Senior Benefits
- Supplement Nutrition Assistance Program (SNAP) (aka food stamps)
- SNAP Employment and Training
- Tribal Assistance for Needy Families (TANF)
- Women, Infants, and Children Program (WIC)

DPA has federal partners, including the Centers for Medicare & Medicaid
Services (CMS), Food and Nutrition Services (FNS), and Administration of
Children and Families (ACF), who we work with to implement regulations
and program rules.

To perform this work, DPA uses several technical systems. These include
a legacy mainframe system (EIS), as well as a modern Modified Adjusted
Gross Income (MAGI) Medicaid determination platform, known as Alaska's
Resource for Integrated Eligibility Services (ARIES).

While EIS has effectively supported program administration and benefit
delivery for over 40 years, the technology on which it is based (IBM
mainframe platform, COBOL software development language and ADABAS
database management system) is becoming increasingly difficult to
maintain. Many significant changes in Public Assistance programs and
program administration have occurred since the system was placed into
production in 1984. Mandatory Federal Medicaid provisions of the ACA,
Welfare Reform, new program demands, and the continued growth and
complexity in public assistance programs are creating a shift in
business needs. The system is currently functioning well beyond the
capacity for which it was designed and does not provide the flexibility
needed to implement mandatory federal provisions.

The modern system, called ARIES, is used by over 400 users consisting of
eligibility technicians, administrative staff, and management personnel
within DPA, and contains over 200,000 benefit recipients. In addition to
these users there are multiple contractors and community partners that
access the system to assist in the public assistance program
administration. In total the ARIES system is used by over 700 users.

Greater system flexibility and robust reporting capabilities are needed
to accommodate changes driven by federal and state laws and to ensure
the long-term ability of DPA to provide efficient, economical, and
effective administration of its programs. The Division needs to pursue
implementation of a more advanced software application based on current
technology and Service Oriented Architecture (SOA) that aligns with the
Medicaid Information Technology Architecture (MITA) and compliance with
the CMS Seven Standards and Conditions. This will ensure a successful
implementation of the mandatory federal Medicaid provisions.

In addition, DPA needs a user-friendly and adaptable system to gain
efficiencies, reduce system maintenance costs, respond to increasing
service demands, improve customer service, and better support the
timeliness and accuracy of eligibility decisions.

DPA is developing a modern, integrated eligibility system that enables
staff to more efficiently issue correct and timely benefits to Alaskans
who need help meeting their basic needs. Utilizing agile development
methods and modular procurements, DPA has the goal of implementing an
eligibility system that not only meets state and federal standards, but
is user friendly for clients, eligibility staff, and technical staff.

DPA has moved away from a "big bang" waterfall acquisitions process to a
more modular approach, emphasizing user centered design, agile product
development, and DevSecOps practices. We integrate user experience,
security, and privacy into all our development work. More information
about the Eligibility Modernization project can be found
[here](https://github.com/Akhealth/EIS-Modernization/) (**be sure to add
yourself as a watcher on the overall eligibility modernization
repository to automatically get updates about changes and upcoming
procurements**). The goal of this approach is to incrementally improve
the current situation in a measurable and sustainable way, and
eventually allow the continued migration of programs away from the
previous eligibility system and onto something more modern, flexible and
maintainable.

Offerors should review this repository for information that will be
critical in constructing a quality proposal.

Of specific interest are:

[Procurement
strategy](https://github.com/akhealth/EIS-Modernization/blob/master/procurement-strategy.md)

[Modular product design
strategy](https://github.com/akhealth/EIS-Modernization/blob/master/modular-experience.md)
and our [Modular Experience and API Framework
Prototype](https://github.com/akhealth/ProtoModExp)

[How We
Work](https://github.com/akhealth/EIS-Modernization/blob/master/how-we-work.md)

[EIS Modernization Project Technical
Strategy](https://github.com/akhealth/EIS-Modernization/blob/master/tech-strategy.md)

This approach to ensuring continuing progress towards the DPA roadmap
goals is to organize product teams to work on the individual
procurements and product increments. These teams work together with the
selected vendor to complete work organized by regular sprints. These
sprints include activities like a daily or regular standup, a
retrospective held at the end of each sprint, a sprint review of work
completed, sprint planning and backlog grooming sessions.

The first product increments were improvements to the worker experience
in the ARIES System in addition to stabilizing the underlying
infrastructure (Milestone 1). In this acquisition, Milestone 2
Increments 1-5, we are looking to move the remaining Medicaid categories
off the legacy mainframe to a modern system exercising our user centered
design practices, modern software development methods and security
focused continuous deployment processes. 
(**make sure to add yourself as a watcher to receive updates**).

### What we're planning to achieve as a result of this acquisition
The Department wants assistance in replacing an aging automated eligibility information system (EIS) with a more efficient system that will more effectively meet the changing needs of the State of Alaska. Other key objectives include the following:

- Develop and deploy an Integrated Eligibility System (IES) or module that facilitates administering the following public assistance programs: Aged Blind and Disabled, Long Term Care, Waiver Medicaid, TEFRA, Additional Medicaid categories (Title IV-E, Residential Psychiatric Treatment, and MAGI-Spousal Support), and Hospital Presumptive Eligibility.
- Design and develop a new front-end portal, replacing the existing ARIES portal with a modern solution
- The system must integrate with ARIES, Genesys (call-center), ILINX (document management and e-Form(s) (public facing eligibility application)), Current (workflow management), Alaska Connect - Engage (client portal), IEVS (eligibility verification), etc.
- Integration is intended to be performed via APIs that interact with the existing Azure integration services. These will need to be developed as a part of this procurement.
- System or module provides Alaska the flexibility to meet the challenges of the Affordable Care Act (ACA) including additional service integration with the Federal Data Services Hub;
- Develop and deploy a system or module that meets all current and applicable Federal guidelines, deadlines, and standards to include HIPAA, MITA 3.0, emerging standards and guidelines related to ACA, and compliance with the CMS Seven Standards & Conditions and Streamlined Modular Certification (SMC);
- Optimize application maintenance costs;
- Optimize long-term operational costs;
- Enhance program uniformity;
- Improve customer service;
- Allow for greater flexibility;
- Easy to use, maintain, and configure;
- Easy to expand system capabilities to support future requirements;
- Function based on a comprehensive, easily updateable rules engine.


### How to respond or ask questions

We've made every effort to allow for less burden in what we require from interested vendors.  Although the RFP might seem to be pretty extensive, we're asking for questions that will better enable us to clarify parts of this RFP that might be unclear. please use [the built in GitHub Q/A](https://github.com/akhealth/RFP-IES-Milestone2/issues/new/choose) to ask questions, make suggestions, or provide feedback. We intend to review feedback and make RFP amendments and updates as needed.

### Budget

We estimate a budget of XXXX dollars for the completion of this project as outlined in the RFP. Proposals priced at more than this amount will be considered non-responsive.  This will be a time and materials contract.

### Contract Term

This contract term is planned to be XXXXX

## Contributing
See [CONTRIBUTING](https://github.com/akhealth/RFP-IES-Milestone2/blob/main/Contributing) for additional information.
