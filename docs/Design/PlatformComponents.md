---
layout: default
title: Platform Components
parent: Design Principles
nav_order: 6
description: "Platform Components"
---

# Platform Components
 iDaaS is a series of accelerators, because of this component based design, building with it or atop it is straight forward, repeatable and reusable. Within each iDaaS component there is an implementation/running specific set of instructions.  <br />
<i>Each component contains a link to the public Git Hub code repositories!!!</i>

# Platform Repositories
These are very specific repositories meant to showcase the capability with a limited set of features. In January 2021 we focused on consolidating almost thirty repositories to less than ten. We did this to ensure we simplified the development and implementation experience.

| Capability | Capability Area   | Description  |
|---|---|---|
|Demo-iDaaS| <a href="https://github.com/RedHat-Healthcare/iDaaS-Demos" target="_blank">iDaaS Demos| This repository is specifically designed to to maintain all the iDaaS platform demos. This repository contains demos for BlueButton, EDI, DREAM, FHIR, HL7, Route Data Distribution, and Third Party.|
|iDaaS Connect|<a href="https://github.com/RedHat-Healthcare/iDaaS-Connect" target="_blank">iDaaS Connect </a>|This repository is specifically designed to to maintain all the iDaaS Connect components. This repository contains iDaaS Connect components for Audit and Compliance, BlueButton, EDI,  FHIR, HL7,, and Third Party.|
|iDaaS Route|<a href="https://github.com/RedHat-Healthcare/iDaaS-Route" target="_blank">iDaaS Route - Data Distribution|This repository is specifically designed to test a subset of iDaaS Route components and capabilities.|
|iDaaS DREAM|<a href="https://github.com/RedHat-Healthcare/iDAAS-DREAM" target="_blank">iDaaS DREAM Platform</a>|This repository is specifically designed for iDaaS DREAM components and capabilities.  Within this repository the is also the iDaaS Event Builder parsing, builder and generator code base.|
|iDaaS KIC|<a href="https://github.com/RedHat-Healthcare/iDaaS-KIC" target="_blank">iDaaS KIC (Knowledge, Insight and Conformance)</a>|This repository is specifically designed to specifically support all needed components for iDaaS KIC (Knowledge, Insight and Conformance). This specific capability is intended to enable auditing and reconciliation of anything the iDaaS platform is engaged in leveraging.|

For more specific details and common technical use cases please feel free to visit [Platform Specific Use Cases](../docs/UseCases/PlatformComponents-Specific.md).