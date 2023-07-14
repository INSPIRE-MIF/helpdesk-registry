# Release strategy

## Table of contents

  - [Introduction](#introduction)
  - [Objective and Summary](#objective-and-summary)
  - [Release Planning & Milestones](#release-planning-&-milestones)
  - [Release Delivery](#release-delivery)

## Introduction

This document illustrates the release planning strategy for the INSPIRE Registry, including all its elements. The document explains the 
rationale behind the plan and details the foreseen release dates throughout the year together with their main expected changes. It also lists a number of resources for 
users to get informed on the future expected changes (future releases) in the INSPIRE Registry and to check in detail the content of each released version (past releases).

## Objective and Summary

The objective of this document is to explain the release planning process for the INSPIRE Registry in an open, clear and transparent way to the community 
in order to ensure that stable validation criteria are provided and communicated efficiently. The release plan is beneficial to the whole community.

Two releases are proposed to be distributed over the year to process the change proposals gathered through the [issue tracker](https://github.com/INSPIRE-MIF/helpdesk-registry/issues).
Each release includes all the fixed issues and change proposals until that date. Releases are coordinated with those of the [INSPIRE Validator](https://github.com/INSPIRE-MIF/helpdesk-validator/tree/master/release%20strategy),
so they will take place one month in advance.

No release is proposed at the end of the year, to avoid undesired interferences in the INSPIRE Monitoring and Reporting process.

## Release Planning & Milestones

As mentioned above, several releases of the INSPIRE Registry are scheduled each year.
The releases for the INSPIRE Registry are aligned with the releases of the rest of INSPIRE artefacts - See [INSPIRE Calendar](https://inspire.ec.europa.eu/calendar).

The schedule of releases of the INSPIRE Registry adhere the following general pattern: 
- First annual release 202x.01 (January).
- Second (and last) annual release 202x.02 (July).

**Release plan for 2023 and 2024**
For illustration, the INSPIRE Registry releases for the years 2023 and 2024 are described below:

<u>2023</u>:
- First annual release 2023.01 (See NOTE 1) - 31/01/2023
- Second (and last) annual release 2023.02 - 31/07/2023

NOTE 1: This release did not take place, since the Control Body was only reactivated in the 74 MIG-T Meeting (28.04.2023).

<u>2024</u>:
- First annual release 2024.01 - 31/01/2024
- Second (and last) annual release 2024.02 - 31/07/2024
  
To guide users in advance about when the solution to an specific issue will be included in one of the releases of the INSPIRE Registry, each issue and change proposal is assigned to a specific milestone.

The Milestones adhere the following general pattern: 
- Milestone 202x.01: Issues collected between 01/08 and 31/11 of the year preceding milestone 202x.01, will be (in principle) considered in such release. 
- Milestone 202x.02: Issues collected between 01/02 and 31/05 of the year of milestone 202x.02, will be (in principle) considered in such release.

**Milestones for 2023 and 2024**
For illustration, the milestones for the years 2023 and 2024 are described below:

- Milestone 2023.01 (See NOTE 2) 
- Milestone 2023.02: Issues collected until 31/05 of the year 2023, to be delivered in release 2023.02
  
- Milestone 2024.01: Issues collected between 01/08 and 31/11 of the year 2023, to be delivered in release 2024.01
- Milestone 2024.02: Issues collected between 01/02 and 31/05 of the year 2024, to be delivered in release 2024.02

NOTE 2: This milestone did not exist, since release 2023.01 did not take place (as explained in Note 1 above).

Milestones are listed on [this page](https://github.com/INSPIRE-MIF/helpdesk-registry/milestones). Once a new version of the INSPIRE Registry is released, the corresponding milestone is closed and moved to the list of closed milestones.

The milestone ends about two months before the meeting of the MIWP Sub-Group 2.3.1 Governance of INSPIRE artefacts in which the corresponding set of change proposals will be discussed, according to the INSPIRE Registry governance workflow. During this meeting, collected change proposals will be filtered and analysed by the sub-group, in preparation of the subsequent meeting of the **Control Body** (currently represented by INSPIRE MIG-T / MIG). A final decision will be reached after the MIG-T meeting and the MIG objection period (including the objection process, if any). 

## Release Delivery

Each release of the INSPIRE Registry is fully managed and made available to the INSPIRE community through the following set of GitHub artifacts:

- A GitHub milestone, named v202x.0y and published on the Milestones section of the community repository; the milestone lists the issues whose solutions are included in the corresponding v202x.0y release.

- A GitHub release, named v202x.0y and published on the Release section of the community repository. The release notes include:

  - a list of aproved change proposals
  - a list of fixed issues
  - a list of the enhancements
  - the new documentation produced, if any
 
- Update of the GitHub issue tracker of the community repository by closing the issues with label "ACCEPTED FIX" and "APPROVED" and the corresponding milestone.
The issues with "REJECTED" label will be closed and consequently re-moved from the milestone.

- Create announcements in [GitHub](https://github.com/INSPIRE-MIF/helpdesk-registry/discussions/categories/announcements) and in [joinup](https://joinup.ec.europa.eu/collection/are3na/solution/re3gistry) related to the release.

