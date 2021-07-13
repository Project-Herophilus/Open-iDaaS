---
layout: default
title: General Capabilities
parent: Design Principles
nav_order: 5
description: "General Capabilities"
---

# Detailed Capabilities

| Capability | Capability Area  | Description  |
|---|---|---|
| Receive | Integration | Receive data from various formats. We have branded this capability iDaaS Connect. iDaaS Connect has seevral specific projects to ensure focus on delivering specific capabilities. These capabilities extend from receiving data we focus on industry standards to third party connectivity. Industry standards support include HL7 v2, FHIR, and EDI Claims. There are potential future plans for NCPDP and HL7 v3 message support being discussed. From a third party connectivity perspective we focus on building an on-ramp for data to be leveraged within iDaaS for over 75 common protocols like: JDBC data sources, File, FTP, SFTP, FTPS, APIs, WSDL, AS400, Mongo, Kafka, numerous cloud platforms and many more. |
| Route/Data Queuing | Data Routing | Enable data to be routed to many sources. For this capability we have focused on building out several specific components such as healthcare event builder (both code and integration) to form the intelligent healthcare data router. In order to demonstrate this, our focus was on building a reusable repeatable enterprise application integration message pattern along with the ability for organizations to build and deliver healthcare even streaming | 
| Run/Revise | Ability to Process/Parsing/Transform| This is one of the most exciting capabilities we are enabling. This is done through our DREAM component(s). DREAM, Data Realtime Management, is all about driving change in the healthcare community and building out a value exchange that can be used by anyone implementing iDaaS to add new capabilities in a low latency and very low risk. You would build a component that has the capability of acting on streaming information and being invoked in a real-time manner. These activities could include areas like event population and building, business rules enablement, third party application integration, AI, ML, dynamic mapping of data sources, cross mapping codes and many other potential examples. |
| Resolve/Research| Data Insight| Enable error handling and insight to resolve potential processing issues. Also, the need to replay messages for new needs.| 

