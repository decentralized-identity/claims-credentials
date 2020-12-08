# VC Marketplace Work Item

## Owners

- Kishore Bhatia, Affinidi ([kishore@affinidi.com](mailto:kishore@affinidi.com), @kishorebhatia)
- Wayne Chang, Spruce Systems
- Rouven Heck, Consensys Mesh
- Martin Riedel, Consensys Mesh (martin.riedel@mesh.xyz)
- Sandeep Bajjuri ([sandeep.b@affinidi.com](mailto:sandeep.b@affinidi.com), @sandeepbajjuri)
- Stepan Gershuni (@gerstep, stepan.g@affinidi.com)

## Outcome

By establishing the reference architecture for a Verifiable Credentials Marketplace, we would be able to discover, save, share and verify verifiable credentials in an anonymized manner across networks. This enables us to increase the usability and value of VCs across networks

Consider the example of a migrant worker who doesn’t have the possibility to avail a loan due to missing Identification or credit score. With his income credentials generated from a particular employer he will be able to secure a loan from a different provider,

(Mechanics of a real world credential exchange (protocol) covering value exchange can be defined to establish the reference architecture for a Verifiable Credentials Marketplace.)

## Deliverables

High level architecture for Verifiable Credentials Marketplace independent from solution architecture / protocol design that covers the following items:

- Use cases of VC Marketplace
- VC metadata required to enable the Marketplace
- Discovery mechanisms:
    - Who are the issuers of credentials that I need?
    - What credentials do I need to receive service?
- Aggregated and anonymous tracking of VC Marketplace activity

The group believes that the VC Marketplace can be separated into three distinct parts around Discovery, (Credential) Exchange, and Payments. In the first iteration the group will concentrate on the Discovery aspect.

**Part 1: Discovery of Credential**

- Start with mission statement of this work and user journeys for several commercial use cases
    - Definition of Credential Metadata
    - Discovery of Interaction Partners by Credential Metadata
- How can this metadata be captured?
    - Leverage Credentials Manifest + Presentation Exchange and build upon
    - Issuer Manifest — specifying types of VCs that can be requested
    - Verifier Manifest — specifying types of VCs that are required to get services
    - Credential Manifest — VC metadata
- Some Example User Stories that the group will design:
    - Issuer: How to communicate business and technical credential requirements to prospective holders?
        - What Issuers do I accept?
        - What Compliance Level do I need (these could have technical implications)
            - What Regulation does the Credential need to adhere to?
        - Holder:
            - How to discover parties that accept my credentials?
            - Where can I use these credentials to avail services?
            - Where can I acquire credentials to get access to service X?
        - Verifiers / RP:
            - If holders are missing valid credentials to consume my service, how are holders redirected to a matching issuer. How much user-control choice? How is (unverified) subject-related data forwarded back into the issuance process.
            - There should NOT be a strong coupling between Verifier and Issuer in this process

**Part 2: Credential Exchange** (Out of scope for the first iteration)

- Credential exchange - separate category
- Value exchange - separate scope/category

**Part 3: Payments** (Out of scope for the first iteration)

- Payments - combined scope with Value exchange

Expected timeline

- 4 months: January 2021 — April 2021

Audience of the deliverables

- CnC WG tech partners (primary)
- Other DIF groups as needed

Related resources or standards from DIF or adjacent organizations

- CnC WG chair
- 2 collaborator entities
- CnC WG resources for meetings, IPR, Governance

## Meetings

Are there regular meetings? If so, when?

- Initial cadence: weekly 30-45 mins, and then make it bi-weekly based on clear goals
- Deliverables: Problem statements (w/ maybe prototypes)
- Kickoff w/ warm-up and continuing conversations along this group
- Add members early on but don’t stop clarifying the mission/problem-statement
- What are the goals of the meeting?
    - To identify the necessary technical components that are required for the functioning of the marketplace
    - Use case based discussion for each call to explore, verify and test from different perspectives

Do you have specific discussion topics in mind, or is it meant to move a deliverable forward?

- Topic to be defined on a bi-weekly basis?

Where are the notes and recordings published, if any?

- Github

Who might be interested in attending?

- Organizations creating/building use cases with ecosystem approach
