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

Three releases are proposed to be distribute over the year to process the change proposals gathered through the [issue tracker](https://github.com/INSPIRE-MIF/helpdesk-registry/issues).
Each release includes all the fixed issues and change proposals until that date. Releases are coordinated with those of the [INSPIRE Validator](https://github.com/INSPIRE-MIF/helpdesk-validator/tree/master/release%20strategy),
so they will take place one month in advance.

No release is proposed on the end of the year, to avoid undesired interferences in the INSPIRE Monitoring and Reporting process.

## Release Planning & Milestones

As mentioned above, several releases of the Re3gistry software are scheduled each year.

To inform users in advance about when the solution to each issue will be included in the release of the INSPIRE Registry, each issue and change proposal is assigned to a specific milestone.
The milestone ends about a month before its corresponding release to allow time for the control body to reach a decision.

- Milestone 202x.01 16/07-15/01 
- Milestone 202x.02 16/01-15/04
- Milestone 202x.03 16/04-15/07

Milestones are listed on [this page](https://github.com/INSPIRE-MIF/helpdesk-registry/milestones). Once a new version of the INSPIRE Registry is released, the corresponding milestone is closed and moved to the list of closed milestones.

Schedule of next releases of the INSPIRE Registry. 

- First annual release 202x.02 (February).
- Second annual release 202x.05 (May).
- Last annual release 202x.08 (August).

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

