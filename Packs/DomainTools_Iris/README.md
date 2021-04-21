Together, DomainTools and Cortex XSOAR automate and orchestrate the incident response process with essential domain profile, web crawl, SSL and infrastructure data. SOCs can create custom, automated workflows to trigger Indicator of Compromise (IoC) investigations, block threats based on connected infrastructure, and identify potentially malicious incidents before weaponization.

##### What does this pack do?
Organizations will be able to fetch a complete profile for a domain name including:
- IP address and hostname details for the name servers, mail servers, and web server powering the domain
- SSL certificate details and tracking codes for the website hosted on the domain
- Email addresses extracted from DNS SOA record, and Whois records
- DomainTools Risk Score, with components & evidence

**Domain Risk Score**

DomainTools Risk Score predicts how likely a domain is to be malicious, often before it is weaponized. In Cortex XSOAR the DomainTools Iris API returns the Domain Risk Score, but also gives the individual scores for each machine-learning classifier, and insight into the evidence for the prediction.

**Guided Pivot Counts**

With Guided Pivot counts, the DomainTools Iris API displays which pivots are most likely to lead to relevant connections to reduce the number of clicks and dead-ends in an investigation. In the War-Room, organizations can investigate observables with the “DomainToolsIris-Pivot” command.

**Tagging**

Tags serve as a way for investigators to decorate data in an Iris investigation. Organizations can leverage their tags created in DomainTools Iris within Cortex XSOAR to expedite the triage process when needing additional context to inform the playbook across multiple departments.

_For more information, visit the [DomainTools API Documentation]( https://www.domaintools.com/resources/api-documentation)_
