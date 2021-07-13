#  Technologies
Here are the technologies that drive our ability to continue to extend the 
capabilities we continue to deliver:

## Integration
Ties back to <a href="https://www.redhat.com/en/technologies/jboss-middleware/fuse" target="_blank">Red Hat’s Fuse</a> and its upstream
vibrant <a href="https://camel.apache.org/" target="_blank">Apache Camel</a>  community. This technology is backed by 
one of the most active communities and continues to grow and expand this technology for well over a decade. As part of 
its commitment there are thousands of implementations of all sizes, types and scale levels in numerous industries with 
some of them growing to support 1 billion daily transactions. As part of its growth are the hundred plus connectors that
it natively supports, this will be very beneficial as connectivity will continue to be extended to more and more platforms.
## Business Rules, Workflow</td>
This capability is supported by <a href="https://www.redhat.com/en/technologies/jboss-middleware/decision-manager" target="_blank">Decision Manager</a>
and the upstream <a href="https://www.drools.org/" target="_blank">Drools</a> community. This technology is very largely adopted and implemented throughout
the community. Drools has a very large footprint in organizations all over the world delivering expert based solutions and capabilities.
#ż Complex Event Processing</td>
This capability is supported by <a href="https://access.redhat.com/products/red-hat-process-automation-manager" target="_blank">Process Automation Manager</a>
and the upstream <a href="https://www.drools.org/" target="_blank">Drools</a> community.  The specific technology within the Drools community is called Drools Fusion. 
This technology is very largely adopted and implemented throughout
the community. Drools has a very large footprint in organizations all over the world delivering expert based solutions and capabilities.
## Data Streaming
A key effort for us is enabling and building a high end data streaming and distribution platform. This capability is being supported
by <a href="https://www.redhat.com/en/technologies/jboss-middleware/amq" target="_blank">AMQ-Streams</a> and the upstream
<a href="https://kafka.apache.org/" target="_blank">Kafka</a> community. We are also looking at future implementations with other distributed queuing
technologies. As a side note, within the codebase there is a codebase
built atop Apache-MQ; however, we maintain the code ONLY for resources that would rather leverage that technology.
## APIs
For APIs we have two implementations: APIs for the iDaaS design pattern and APIs to demonstrate end to end FHIR capabilities. For all API management we
have leveraged <a href="https://www.redhat.com/en/technologies/jboss-middleware/3scale" target="_blank">3Scale</a>.
## Data                    
We currently are moving to support DDLs for multiple RDBMS platforms starting with Maria DB (MySQL) and Postgres. This is 
because there is wide adoption of these within healthcare. The first few implementations with be SQL Server DDL centric as 
well finalize data model validation. We also intend to expand towards NoSQL standards
quickly as we continue to implement new features. Connected Health/iDaaS overall objective 
is to ensure we help define data as an asset.
# Hybrid-Cloud
When and where possible this reference aarchitecture/design pattern is completely designed to be cloud native. The ONLY exception is when we have to deal with specific
industry needs that cannot be done with a cloud native manner. In healthcare this refers specifically to HL7 v2 messaging. The reason is this form of messaging is legacy based on
the client-server socket paradigm and is meant to be long running. However, ALL any FHIR components are cloud native by design. For our container capabilities we focused
around the industry leading <a href="https://www.redhat.com/en/technologies/cloud-computing/openshift" target="_blank">Openshift</a> and all the supporting OpenShift technologies.
