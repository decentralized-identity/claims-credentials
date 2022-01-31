# Data Agreement

## Work ItemParticipants
- iGrant.io (Lal Chandran)
- Gataca (Jose San Juan)
- Human Colossus (Paul Knowles)

## Work Item Owners
- Jan Lindquist (jan@linaltec.com) 
- Jose San Juan (jose@gataca.io) 

## Outcome
**When your work item is successful, then what will have changed in the world? What will we be able to do that wasn't possible do before or vice versa?**
The goal of the work item is to have a standard means of exchanging a data agreement between actors in DLT, a Holder and Issuer/Verifier. The data agreement shall be interoperable between suppliers. Main focus for DIF is to define one or more “profiles” of existing protocols that would enable an end-to-end data agreement reference implementation for one or more use-cases and the data model previously defined and potentially being iterated here. For example, a data agreement reference implementation may use a specific profile of the presentation exchange protocol based on a specific DID method, without making presentation exchange or that DID method a normative requirement of the data agreement data model. The content of the data agreement may continue to be  worked on, together with privacy and consent experts (for example, Kantara may provide guidance on how to use their relevant ratified outputs, or contribute directly to the group as consent experts via membership or feedback agreement), respecting the IPR boundaries of DIF and any other IPR-protected collaborative organizations.

## Terminology

Data Agreement: A data agreement is a record on how an organization processes personal data in accordance with privacy regulation (GDPR, CCPA, etc) similar to a privacy policy but using a standard privacy ontology and an immutable record. The record can be shared with an individual in the form of digital receipt when creating verifiable credentials or sharing personal data in a proof presentation. Data agreement is intended to be compliant with Kantara Consent Receipt and future standard ISO 27560.

## Deliverables
- **Does your work item have any deliverables? These include code projects, standards-track specifications, reports, registries, summaries, and publishable in written form to a broader audience.**

Main contribution will be
- Data Agreement Data Model specification
- Data Agreement protocol profile

And desirable deliverables (but depending on collab):
- reference implementation (Gataca may contribute data model lib and even maybe protocol application over golang; iGrant has a reference implementation that will be used as input)
- blog posts

- **What's the expected timeline?**

Goal is to have a main profile within 3 to 6 months with interoperability within 1 year.

- **Who's the audience of your deliverables?**

Implementers or DLT or data intermediaries or MyData Operators

- **What are related resources or standards from DIF or adjacent organizations?**

Hyperledger Aries, Kantara, ISO, W3C Data Privacy Vocabulary, MyData, Govstack

- **Meetings**

Are there regular meetings? If so, when?
Weekly Thursday 14:00 -15:00 CET

- **What are the goals of the meeting?**

Develop Data Agreement specification and protocol profile based on input from eSSIF-lab. Opportunity for DIF members to influence.

- **Do you have specific discussion topics in mind, or is it meant to move a deliverable forward?**

Agree on a reference implementation for the DID Method as a starting point and further develop the protocol profile.

- **Where are the notes and recordings published, if any?**

Notes will be taken into github. Recordings is an open questions.

- **Who might be interested in attending?**

Developers of SSI who need GDPR compliance and method for creating immutable records of consent records (data agreements) for using personal data.


## Input
The work done under NGI eSSIF-lab will be used as starting point for the work item.

[1] Data Agreements for enabling auditable personal data exchange
https://github.com/decentralised-dataexchange/automated-data-agreements

[2] DIF data agreement demo
https://youtu.be/Mq4oXEaOTwg
