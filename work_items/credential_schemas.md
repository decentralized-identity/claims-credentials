# Credential Schemas

This work item proposes to develop and publish credential schemas to support interoperability in decentralized identity ecosystems. This work item strives to attract an interdisciplinary group of experts to ensure use case fit and acceptance.

## Work Item Owners
- Otto Mora (@ottomorac)
- TODO

## Outcome
**When your work item is successful, then what will have changed in the world? What
will we be able to do that wasn't possible do before or vice versa?**

Identify standardized credential schemas for a variety of use cases including: Basic KYC, AML, Proof of Humanity, and Proof of Age among others.

## Deliverables
- **Does your work item have any deliverables? These include code projects,
  standards-track specifications, reports, registries, summaries, blog posts,
  and anything else that is instantiable and publishable in written form to a
  broader audience.**

This work item will deliver schemas and related documentation. At a later point, this work item may develop a registry to enable discoverability. 

The initial schemas of focus include Basic KYC, AML, Proof of Person, Proof of Age.

Deliverables will specifically include:
- Purpose, use, alignment, recommendations
- Abstract data model
- Mapped schemas for different formats (JSON Schema, ...) and other variations
- JSON-LD contexts

Out of scope:
- Definition of verification processes: Schemas reflect the output of a verification process, rather than details of the process itself. The details of the process are out of scope for this work item.
In many cases, the schemas must align with certain requirements or frameworks (such as assurance levels). These design goals are not mutually exclusive
- Trust frameworks: Trust frameworks are referenced and aligned with where relevant, but definition is out of scope for this work item

- **What's the expected timeline?**

Roughly 3-6 months per schema

- **Who's the audience of your deliverables?**

- Developers who will use these schemas in their implementations
- Compliance and product roles who are focused on acceptance criteria

- **What are related resources or standards from DIF or adjacent organizations?**

## Meetings
- **Are there regular meetings? If so, when?**

Meetings will occur every other week at a time TBD (TODO)

- **What are the goals of the meeting?**

Credential schemas will be worked on, in priority order (as determined by the partipants). 

For each schema, the group will proceed as follows:
- Beginning: Identify, elaborate, and document the following:
    - Focal use cases, clarifying use of the credential by 3 parties
    - Related work
    - Scope, including relevant regulations, jurisdictional variability, and trust frameworks
    - Whether additional expertise is needed
- Ongoing 
    - Review the current schema status, consider improvement proposals, and work towards completion until WG approval
- Wrap up
    - Finalize schema documentation and prepare for release 

- **Do you have specific discussion topics in mind, or is it meant to move a
  deliverable forward?**

It's meant to move credential schema deliverables forward

- **Where are the notes and recordings published, if any?**

- The standard DIF zoom recordings.
- AGENDA.md file in https://github.com/decentralized-identity/credential-schemas

- **Who might be interested in attending?**

Developers, product, compliance, and implementors in general
