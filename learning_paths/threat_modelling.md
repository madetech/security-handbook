# Threat Modelling
## Summary
> "Threat modelling is a term applied to the techniques that are used to model and analyse technology systems and services to better understand how that system or service might be attacked or otherwise fail, and the measures or controls needed to manage the risk posed by such attacks or failings. Threat modelling techniques are best applied to inform the design and development phases of a technology system or service life cycle” [NCSC](https://www.ncsc.gov.uk/collection/risk-management/threat-modelling)

- Early and often, threat model all the time

- Results in fewer bugs, smaller attack surface

- About finding problems in the process early so they can be fixed

- Ensure security is fixed in the application as it is being developed.

- Encourages a security mindset in team members such as engineers and developers.

The following example provides a high level, simplification of what threat modelling is.

### Example
> When you leave the house with a child to walk them to school. As you leave you see cars driving past, a dog barking in the street, the sun is beating down with intense heat. So, you hold the child’s hand to cross the road (this is identifying a threat from vehicles), you might apply sunscreen to yourself or the child to prevent sunburn (threat from the heat identified). You might try to avoid the barking dog as it seems aggressive (threat identified).

## Security Feedback Loop
Identifying potential threats ->  evaluate mitigations ->  change the design 

![Security Feedback Loop](./diagrams/sec-feedback-loop.png)

The security feedback loop starts with threat identification. Once threats have been identified we can progress to evaluating potential mitigations and engineering fixes. This is done by perhaps changing the design, removing components, or adding new functionality. The loop then starts again, identifying if threats still exist or if any new threats have now arisen. This is an infinite process loop, with each phase intended to strengthen a given solution.

Threat modelling is part of the design phase, so it should ideally be done before any code is written (early and often).







## Useful Links
- [Threat Modelling Manifesto](https://www.threatmodelingmanifesto.org/) 
- [Building a Security Operations Centre - Threat modelling ](https://www.ncsc.gov.uk/collection/building-a-security-operations-centre/onboarding-systems-and-log-sources/threat-modelling)
- [Threat Modelling | NCSC ](https://www.ncsc.gov.uk/collection/risk-management/threat-modelling) 
- [Threat Modelling | OWASP Foundation](https://owasp.org/www-community/Threat_Modeling) 
- [STIX V2.1 and TAXII V2.1 OASIS Standards are published - OASIS Open](https://www.oasis-open.org/2021/06/23/stix-v2-1-and-taxii-v2-1-oasis-standards-are-published/ )
- [MITRE ATT&CK®](https://attack.mitre.org/)
- [Cyber Kill Chain®](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html)
