# JWT-VC Interoperability Profile

The goal is to achieve interoperability among independent Verifiable Credentials implementations by agreeing on an interoperability profile document
that has made specific choices within the standards composing a Verifiable Credential(VC) technology stack,
which implementers, decision-makers and architects can refer to.

## Work Item Owners
- Daniel McGrogan (@dtmcg)
- Jeremie Miller (@quartzjer)
- Kristina Yasuda (@Sakurann)

## Outcome
**When your work item is successful, then what will have changed in the world? What
will we be able to do that wasn't possible do before or vice versa?**
We will have an interoperability profile that has made specific choices within the standards composing a Verifiable Credential(VC) technology stack 
that implementers can use to achieve interoperability across independent implementations.

## Deliverables
- **Does your work item have any deliverables? These include code projects,
  standards-track specifications, reports, registries, summaries, blog posts,
  and anything else that is instantiable and publishable in written form to a
  broader audience.**
We are writing an interoperability profile document, which is not a standards-track specification, 
but explains which of the options defined within each of the specifications composing Verifiable Credential technology stack should be used
to achieve interoperability across independent implementations. A set of test vectors is included.
  
- **What's the expected timeline?**
  - Stage 1 (Summer 2022): Presentation - Enable Holder B to present a compliant VC to Verifier C
  - Stage 2 (Winter 2022): Issuance​ - Enable Issuer A to issue credential to Holder B
  - Stage 3 (Early 2023): Portability - Enable movement of the credentials across wallets

- **Who's the audience of your deliverables?**
implementers, decision-makers and architects who want to build interoperable VC implementations.

- **What are related resources or standards from DIF or adjacent organizations?**
* [W3C VC-DATA-MODEL v1.1](https://www.w3.org/TR/2022/REC-vc-data-model-20220303/)
* [OIDF Self-Issued OpenID Connect Provider v2](https://bitbucket.org/openid/connect/src/master/openid-connect-self-issued-v2/openid-connect-self-issued-v2-1_0.md)
* [OIDF OpenID Connect for Verifiable Presentations](https://bitbucket.org/openid/connect/src/master/openid-connect-4-verifiable-presentations/openid-connect-4-verifiable-presentations-1_0.md)
* [DIF Presentation Exchange](https://identity.foundation/presentation-exchange/)
* [W3C DID-CORE v1.0 CR Draft](https://www.w3.org/TR/2021/PR-did-core-20210803/)
* [DIF Well-Known DID Configuration](https://identity.foundation/.well-known/resources/did-configuration/)
* [W3C CCG Status List 2021](https://w3c-ccg.github.io/vc-status-list-2021/)
* [DIF Decentralized Web Node, fka Identity Hubs]()

## Meetings
- **Are there regular meetings? If so, when?**
Every 4 weeks, starting Wednesday 25 May, at 11PM PST

- **What are the goals of the meeting?**
Get implementer's feedback and improve the interoperability profiles' documentation:
* Presentation Profile - [underway](https://github.com/decentralized-identity/jwt-vc-presentation-profile)
* Additional Profiles - future 

- **Do you have specific discussion topics in mind, or is it meant to move a deliverable forward?**
To move a deliverable forward by reviewing GitHub issues and PRs.

- **Where are the notes and recordings published, if any?**
The recordings are published in the #general channel on the DIF Slack and on the Meeting Records spreadsheet. Agendas are entirely GitHub driven, so no separate agenda/minutes documents will be generated; questions and input requests are best directed to GitHub issues.

- **Who might be interested in attending?**
implementers, decision-makers and architects who want to build interoperable VC implementations.
