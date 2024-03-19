---
layout: post
title: Security Monitoring and SIEM fundamentals
categories: [SIEM, Elastic Stack, Kibana]

---

**Elastic Stack**

Elastic stack can be used as a SIEM solution to collect, store, analyse and visualise security-related data from various sources. 
Such as: 
- firewalls
- IDS/IPS
- endpoints (using Logstash)

ElasticSearch configured to store and index security data, perform searches and correlations on collected security data.
Kibana used to create custom dashboards and visualisation to provide insights into security events. 

Kibana Query Language(KQL) query language designed for searching and analysing.
"More intuitive" than Elasticsearch Query DSL.

(While both KQL and regex involve pattern matching, they serve different purposes and have different syntax. KQL is more specialized for querying structured data in Elasticsearch, while regex is a more general-purpose tool for pattern matching in text data. However, some concepts, such as wildcard matching and character classes, are shared between the two, though they might be expressed differently in each language.)

The lab included a quick search exercise for disabled accounts and extracting log info.

Moving along to MITRE attack framework introduction.

Finally with SIEM use case development. 

How To Build SIEM Use Cases
Comprehend your needs, risks, and establish alerts for monitoring all necessary systems accordingly.

Determine the priority and impact, then map the alert to the kill chain or MITRE framework.

Establish the Time to Detection (TTD) and Time to Response (TTR) for the alert to assess the SIEM's effectiveness and analysts' performance.

Create a Standard Operating Procedure (SOP) for managing alerts.

Outline the process for refining alerts based on SIEM monitoring.

Develop an Incident Response Plan (IRP) to address true positive incidents.

Set Service Level Agreements (SLAs) and Operational Level Agreements (OLAs) between teams for handling alerts and following the IRP.

Implement and maintain an audit process for managing alerts and incident reporting by analysts.

Create documentation to review the logging status of machines or systems, the basis for creating alerts, and their triggering frequency.

Establish a knowledge base document for essential information and updates to case management tools.


