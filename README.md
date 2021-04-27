# Governance Overview

The OpenFn open-source integration toolkit (the "integration toolkit") is
governed by Open Function Group (OFG), LLC under the supervision of its Open
Source Steering Committee (OSSC).

Open Function Group and the OSSC are guided first and foremost by the project's
[Code of Conduct](CODE-OF-CONDUCT.md) and
[Mission and Values](MISSION-AND-VALUES.md). The remainder of this document lays
out how specific decisions are made.

## Open Function Group (OFG)

[Open Function Group](https://www.openfn.org) is a New York-based LLC which has
been building free and open source software (FOSS) for data integration projects
in the health, humanitarian, and international development sectors since
in 2014. Their software and services are now in use by governments, NGOs, and
impact-first businesses in over 40 countries.

OFG's first integration platform was entirely FOSS, but they soon shifted to an
["open-core"](https://en.wikipedia.org/wiki/Open-core_model) (think GitLab) in
order to sustain their impact-focused integration work. Their main hosted
offering, the OpenFn "platform", is _proprietary_ but makes extensive use of the
open-source integration toolkit; in fact, the "platform" may be thought of as an
enterprise/hosted layer running on-top of the basic, open-source building blocks
provided by the integration toolkit.

### The OpenFn integration-platform-as-a-service

Sometimes just referred to as "the platform", "the OpenFn platform" or "the
iPaaS", OpenFn's integration-plaform-as-a-service is a proprietary, enterprise
offering that provides a secure, stable, and scalable implementation pathway for
organizations to design, build, deploy, and manage enterprise-grade integration,
interoperability, and automation projects. It can be deployed locally or
accessed via the cloud.

### OFG's commitment to use and sustain the integration toolkit

Our mission is to make health & humanitarian interventions more efficient &
effective, and we see investment in the integration toolkit as strategic for
three main reasons.

1. Governments provide an important pathway to scale our work and many prefer
   open-source and locally deployed solutions.
2. We don’t intend to grow OFG into a large consulting shop and we think that a
   stronger open-source offering will create more independent implementers of
   our tools and decouple success in achieving our mission from our growth as a
   single firm.
3. As we’ve already started to see, other stakeholders may be able to build
   newer, better, more context-appropriate technologies with the applications,
   frameworks, and standards we’ve developed—a future where there are dozens of
   competing, interchangeable integration solutions connecting hundreds of now
   interoperable ICT4D technologies is one we want to be a part of.

OFG strives to preserve the integration toolkit as a healthy and bona fide open
source project and sustains its operations through business activities related
to the toolkit and their other proprietary and/or service offerings.

We have designed the tools in the toolkit to be useful as standalone pieces of
software _and_ as modules, used by other applications. Because a substantial
portion of OFG's revenue comes from contracts related to the platform, and
because the platform relies on OpenFn/core, OpenFn/engine, and the OpenFn
adaptors, we hope to ensure that OFG will always be incentivized to continue
their investment in the integration toolkit.

In other words, we're attempting to ensure that as OFG succeeds, they will
continue enhancing the open source integration toolkit regardless of whether or
not additional funders and/or stakeholders contribute to the project.

## The Integration Toolkit

Separate from "the platform", the integration toolkit is the suite of
applications and modules provided by OFG and the community which enable data
integration, interoperability, and automation solutions via OpenFn-compliant
jobs, triggers, and credentials. The key components of the toolkit are:

1. OpenFn/docs
2. OpenFn/core
3. OpenFn/engine
4. OpenFn/microservice
5. OpenFn/devtools
6. the OpenFn adaptors

Unless otherwise noted, all open-source repositories found at
https://www.github.com/openfn are part of the integration toolkit.

Unless otherwise noted, all of these applications and modules are LGPL licensed
to ensure that (a) derivative works of those applications will continue to be
open-source and (b) they may be used as sub-modules of proprietary applications,
such as "the platform" or any other software which the community may want to
build on top of this toolkit.

## Open Source Steering Committee (OSSC)

The Open Source Steering Committee (OSSC) represents the OpenFn community of end
users and implementers. It reviews and gives feedback on major roadmap
decisions, new designs, specifications, features, and protocol changes.

Concretely, its members will (1) prepare for and participate in a 60 minute
meeting once each month, (2) review our product roadmaps and implementation
plans for the toolkit, and then (3) help us prioritize our investments in a very
practical way—by thinking through their and their networks' project pipelines to
identify upcoming implementation opportunities and real functional, legal, and
technical requirements for those upcoming implementations.

The OSSC's membership and decision making process are defined in the
[OSSC's internal governance policy](OSSC.md).

## Code

As the integration toolkit is an open source project, anybody may file issues on
or propose code changes to any of the various integration toolkit repositories.
Proposed code changes must be approved by a project Committer.

Integration toolkit code is permissively licensed with code copyright remaining
with the original author. In this sense, no one entity "owns" the project's
intellectual assets.

### Committers

Committers are community members who have shown that they are committed to the
continued development of the project through ongoing engagement with the
community. Commit/write access allows contributors to more easily carry on with
their project-related activities by giving them direct access to the project's
resources.

OFG awards Committer status to individuals making significant and valuable
contributions to the project. Current Committers and the OSSC may also suggest
individuals deserving of Committer access, but OFG has final say.

_Note: If you make a significant contribution and are not considered for
commit/write access on the appropriate resource, file an issue, post on the
forum, or contact an OSSC member directly and it will be brought up at the next
OSSC meeting._

If a Committer becomes inactive, having not participated substantially in the
project for six months or more, their Committer status will be revoked. They may
regain status again by resuming substantial participation.

Notwithstanding any of the above, OFG may revoke the Committer status of any
Committer at its sole discretion.

### Change approval

Proposed code changes must be approved by a project Committer with sufficient
expertise who is able to take full responsibility for the change.

In the case of changes proposed by an existing Committer, an additional
Committer is required for review.

Committers should elevate significant or controversial modifications to the OSSC
for discussion. The OSSC should seek to achieve consensus on the question and
offer its recommendation.

As OFG has commit access and controls the release process for all tools, it
effectively has final say on any code changes. The above procedures are designed
to foster a collaborative, community-oriented process, and should be followed in
most cases.

## Roadmap

A "project roadmap" is the plan of upcoming changes to a project's code. In
integration toolkit projects, OFG and the OSSC collaborate to set the roadmap.
Suitability of items for the roadmap is determined by community need and the
availability of resources to support development.

As stated above, anybody may submit a pull request against any of the
repositories. The change approval section above covers how such pull requests
may be approved. It should be noted, though, that major changes to the project
stand a much better chance of being accepted if they are on the roadmap and/or
if OFG and the OSSC have agreed in advance they are a good fit for the project
and that the chosen design and implementation strategy are suitable.

## Amendments

Revisions to any document in this repository must be approved by both OFG and
the OSSC. Even though these documents exist within an integration toolkit
repository, this requirement supersedes the change approval policy above.
Committers should not effect changes to documents in this repository without the
approval of OFG and the OSSC. Exceptions may be made for small changes such as
typographical errors.

## Attribution

This a derivative work of the
[ODK Governance repository](https://github.com/getodk/governance/). Given
similarities between ODK's structure (a single entity driving most of the work,
but a responsibility to a large community of external stakeholders) and OFG's
structure, OFG feels that a similar governance model is a good place to start.
