# DevSecOps

## DevSecOPS (Development Security Operations)
“DevSecOps is about built-in security, not security that functions as a perimeter around apps and data.

“Environment and data security

- **Standardize and automate the environment**: Each service should have the least privilege possible to minimize unauthorized connections and access.

- **Centralize user identity and access control capabilities**: Tight access control and centralized authentication mechanisms are essential for securing micro-services, since authentication is initiated at multiple points.

- **Isolate containers running micro-services from each other and the network**: This includes both in transit and at rest data, since both can represent high-value targets for attackers.

- **Encrypt data between apps and services**: A container orchestration platform with integrated security features helps minimize the chance of unauthorized access.

- **Introduce secure API gateways**: Secure APIs increase authorization and routing visibility. By reducing exposed APIs, organizations can reduce surfaces of attacks.”

[What is DevSecOps | Red Hat](https://www.redhat.com/en/topics/devops/what-is-devsecops)

### The secure development machine

Developers → Process → Tools → Run time
- Developers
  - Secure coding knowledge
- Process
  - Secure Development Lifecycle (SDLC), secure coding standards
- Tools
  - Code repositories, SAST (Static Application Security Testing) and DAST (Dynamic Application Security Testing)
- Run time
  - AWS/Azure/G Cloud, IAST (Interactive Application Security Testing)

### Responsibilities
- Keep knowledge of threats and vulnerabilities up to date → follow industry sources and news etc

- Produce clean and maintainable code → Define and enforce coding standards, peer code reviews to an agreed standard

- Secure development environment → protect development environment to the same standard as production environment

- Protect your code repository → evaluate and improve repository security

- Secure build and deployment pipelines → Enforce testing and security checks at deploy time

### Advantages

- Speed and security are combined, reducing time (and cost).

- Security is not an after thought, number of bugs is reduced

- Any issues are identified and can be mitigated much earlier in the development cycle

- No surprises - if all of the relevant teams are collaborating from the beginning then response times and knowledge are greatly improved

- Compliance is simplified - as this can be monitored on an iterative basis, rather than retro-fitting security to parts of the system that are not compliant after development.

- Ability to identify and patch vulnerable components is increased via scanning in pipelines

## Good Practices

- “shift left” - moving checking of security issues to the beginning of the process rather than after the fact.

- Automate scanning for vulnerabilities and integrate into the build process.

- Promote a strong security culture.

