# DIF Claims & Credentials Working Group

The Claims & Credentials Working Group exists to develop interoperable formats
for broad adoption around Claim & Credential processes within SSI.

## Resources
- [Website](https://identity.foundation/working-groups/claims-credentials.html)
- [Meeting recordings](https://docs.google.com/spreadsheets/d/1wgccmMvIImx30qVE9GhRKWWv3vmL2ZyUauuKx3IfRmA/edit#gid=1252135265)
- The group's [Charter](https://github.com/decentralized-identity/org/blob/master/Org%20documents/WG%20documents/DIF_CC_WG_charter_v1.pdf) and [Operating Addendum](https://github.com/decentralized-identity/org/blob/master/Org%20documents/WG%20documents/DIF_CC_WG_Operating_Addendum_V1.pdf)
- [Notion Page](https://www.notion.so/dif/Claims-and-Credentials-d236ac4366d54c76ba85c2f521c003e0): This page is used for taking meeting notes and collaborating around non-code/specification-based work items within the group. Code/specification-based work items should exist in their own repository, such as in the case of [Presentation Exchange](https://github.com/decentralized-identity/presentation-exchange).
- [Mailing List](https://lists.identity.foundation/g/cc-wg): Receive the latest updates here.

## Creating a new work item

1. Ensure that you have completed the DIF IPR process. You must have at least
   two co-owners from different organizations for your work item to be
   considered.
2. Fork this repository to your GitHub account and clone the fork to your local
   machine.
3. In the project directory on your local machine, copy
   `templates/work_item.md` into lowercase snakecase "short name" for your work
   item in `work_items/`. For example, `cp templates/work_item.md
   work_items/credential_revocation.md`. Add your work item to the list of
   active work items in `work_items/README.md`.
4. Populate your work item by completing all the sections in the template,
   including answering all the questions.
5. Commit your changes locally and push to your GitHub account's fork of this
   repository.
6. Create a Pull Request against the parent repository including your local
   changes, and await a decision by the chairs, which is conducted using
   majority approval across an odd number of chairs. Your item co-owners
   **must** express in the Pull Request via GitHub comment that they accept the
   responsbilities of work item ownership.
7. Upon approval via merging, begin an email thread with the chairs or discuss
   asynchronously if you require any administrative resources from DIF, such as
   a regularly scheduled Zoom meeting link, inclusion on the
   [DIF calendar](mailto:decentralized.identity@gmail.com), a subpage in Notion
   to store notes and recordings, or any other help facilitating your work
   item.

## Work item ownership responsibilities
As a work item owner, you will have the following responsibilities:
- Timely response to questions and status check-ins about the work item by the
  chairs and other DIF members.
- Commitment to designating and sending a work item representative for all C&C
  WG twice-monthly meetings who can speak on the status of the work item and
  summary of events.
- Commitment to timelines and scope of deliverables and/or meetings, and being
  proactive in communications to the chairs and the group upon any changes to
  these. Changes to the work item are made and approved in the same Pull
  Request process described above, except the PR should contain changes to the
  work item markdown file instead of adding a new one.

## Types of working items
We informally recognize a few main formats for work items and recommend the
following conduct for each:
- A **Standards-Track Specification** is meant to describe curated lists or
  data formats that will enable interoperability across systems. It should have
  a destination in mind, such as the W3C Credentials Community Group.
- A **Round Table** is an ongoing discussion with specific topics with the goal
  to solicit broad participation towards consensus-informed community
  viewpoints or the exploration and rank ordering of potential future work
  items.
