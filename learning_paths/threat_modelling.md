# Threat Modelling
1. [Step 1 (Scope and Decomposition)](#step-1-scope-and-decomposition)
2. [Step 2 (Draw)](#step-2-draw) 
3. [Step 3 (Analyse Drawings)](#step-3-analyse-drawings)
4. [Step 4 (Mitigate)](#step-4-mitigate)
5. [Step 5 (Document)](#step-5-document)
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

## Threat modelling process

### Scope -> determine what is the scope of the threat model (whole feature, subsystem etc)

### Draw -> draw a simple diagram with team of whatever it is that is being threat model.

### Analyse -> analyse the individual threats.

### Mitigation -> how to make the threats go away.

### Document -> write down what was discussed and found out during process.

#### Remember
> Threat modelling is not an exact science; different people will come up with different potential threats.
>
> Threat model will never be complete; no such thing as perfect model but the process should help to expand thinking around what potential threats might be.
>
> Iterative process, rinse, and repeat.
>
> Reviewed at proper interval (the interval is determined by the team)

 
## Tools 

**Note:** the following list is not exhaustive and just provides examples of what could be used to threat model.
- Whiteboarding
- MS TM Tool
- Irius risk

 

Four questions approach to threat model (see also - [Threat Modelling Manfesto](https://www.threatmodelingmanifesto.org/))

·      What are we building? (scope/draw)

·      What can go wrong? (Analyse)

·      What are we going to do about it? (Mitigate)

·      Did we do a good job? (document)

 
## Step 1 (Scope and Decomposition)

## Step 2 (Draw) 

## Step 3 (Analyse Drawings)

## Step 4 (Mitigate)

## Step 5 (Document) 

## Useful Links
- [Threat Modelling Manifesto](https://www.threatmodelingmanifesto.org/) 
- [Building a Security Operations Centre - Threat modelling ](https://www.ncsc.gov.uk/collection/building-a-security-operations-centre/onboarding-systems-and-log-sources/threat-modelling)
- [Threat Modelling | NCSC ](https://www.ncsc.gov.uk/collection/risk-management/threat-modelling) 
- [Threat Modelling | OWASP Foundation](https://owasp.org/www-community/Threat_Modeling) 
- [STIX V2.1 and TAXII V2.1 OASIS Standards are published - OASIS Open](https://www.oasis-open.org/2021/06/23/stix-v2-1-and-taxii-v2-1-oasis-standards-are-published/ )
- [MITRE ATT&CK®](https://attack.mitre.org/)
- [Cyber Kill Chain®](https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html)
