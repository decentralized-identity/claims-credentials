# DIF Credential Manifest

## Work Item Owners
- Dan Buchner (@csuwildcat)
- Gabe Cohen (@decentralgabe)
- Mike Ebert (@mikekebert)
- Juan Caballero (@bumblefudge)

## Outcome
**When your work item is successful, then what will have changed in the world? What
will we be able to do that wasn't possible do before or vice versa?**

The DIF Credential Manifest specifies a data format that credential issuers can use to announce their capabilities (e.g. supported credentials and associated requirements (see Presentation Exchange)) to a third party. Credential Agent Implementations consume the Credential Manifest as one of the primary steps of interacting with an issuer. The Workitem will build on top of the current [(Strawman) Specification](https://identity.foundation/credential-manifest/).

Our interested protocols include DIDComm, CHAPI,
OpenID Connect, and others. Our interested formats include W3C Verifiable
Credentials, Verifiable Presentations, OpenID Connect Identity Tokens, and
ad-hoc JSON signed with the JSON-LD Signature or JWT specifications.


## Deliverables
- **Does your work item have any deliverables? These include code projects,
  standards-track specifications, reports, registries, summaries, blog posts,
  and anything else that is instantiable and publishable in written form to a
  broader audience.**

We are writing a standards-track specification.

- **What's the expected timeline?**

We will releease a stable specification until end of Q2/2021

- **Who's the audience of your deliverables?**

Audiance are developers implementing issuer-subject interactions around the discovery and issuance of Verifiable Credentials.

- **What are related resources or standards from DIF or adjacent
  organizations?**

DIF Presentation Exchange, W3C Verifiable Credentials, JSON-LD Signatures, JWT, OpenID Connect, CHAPI, and DID-SIOP.

## Meetings
- **Are there regular meetings? If so, when?**

Yes, Thursdays at 10 AM PT/1 PM ET at [this Zoom link](https://us02web.zoom.us/j/81365508259?pwd=MVlIanQydUYycG1rTlVkZHBDRERtZz09).

- **What are the goals of the meeting?**

To further work on the specification.

- **Do you have specific discussion topics in mind, or is it meant to move a
  deliverable forward?**

To move our deliverable forward, we will review the outstanding GitHub issues in the order of least recently updated, using [this link](https://github.com/decentralized-identity/credential-manifest/issues).

When we have specific goals such as a release target (e.g., `v0.1`) or items
labeled "High Priority", then we may add additional filters for going through
issues first.

- **Where are the notes and recordings published, if any?**

The recordings are published in the #general channel on the DIF Slack. There
are no notes, however automated transcription is a possibility and actions are
mainly taken in GitHub issues.

- **Who might be interested in attending?**

Anyone interested in the discovery and issuance of credentials, especially people
working on wallets and issuers.
