# Hi, I'm Nikhilesh Singh

### Software Engineer · Backend Systems & Security

I build backend systems and automation for cybersecurity products at **CYFIRMA**, working with **Java, Spring Boot and Python**. My focus is APIs, cloud discovery and security automation, with an interest in how systems behave under concurrency, failures and uncertain inputs.

[LinkedIn](https://www.linkedin.com/in/nikhileshsingh06/) · [Email](mailto:nikhileshsingh045@gmail.com)

## What I work on

- **Backend APIs:** Java/Spring Boot multi-tenant REST APIs, organization-scoped access controls, and integrations across MongoDB and MySQL.
- **Cloud discovery:** Python systems that separate resource discovery, exposure verification and ownership attribution, preserving the evidence behind a finding.
- **Developer automation:** Python SDKs, API-driven workflows, automated testing and CI/CD security controls.
- **Security engineering:** Cloud security and IAM, vulnerability remediation, secrets management and cloud storage exposure detection.

## Selected projects

### [REST API Gateway](https://github.com/Niksinikhilesh045/api-gateway-fastapi)

A FastAPI reverse-proxy gateway for authentication, rate limiting and request routing.

- JWT and API-key authentication, with prefix-based routing to upstream services.
- Token-bucket rate limiting with in-memory and Redis backends; a Lua script coordinates the read, refill, check and update within Redis.
- Upstream timeouts, a circuit breaker, structured errors and request IDs.
- Automated tests, Docker Compose, and Prometheus/Grafana configuration.

**Explore the implementation:** [Redis token-bucket script](https://github.com/Niksinikhilesh045/api-gateway-fastapi/blob/004b2796a62d107d1585cef98748a81ab46e5405/middleware/rate_limit_store.py#L15-L78)

**Stack:** Python · FastAPI · Redis · Docker · pytest

### [Automated Security Scanning / DevSecOps CI/CD](https://github.com/Niksinikhilesh045/automated-security-scanning-devsecops)

A GitHub Actions pipeline that brings security checks and developer feedback into a containerized application's workflow.

- Integrates code, dependency, secret and container scanning with tools including CodeQL, Snyk, Gitleaks and Trivy.
- Includes Dockerfile/image checks, OWASP ZAP baseline web scanning, scan reports and Slack notifications.
- Automates container builds and image publishing.

My focus was the pipeline and security automation. [Harsh Chauhan](https://github.com/Harsh2509) contributed significantly to the application development.

**Stack:** GitHub Actions · Docker · CodeQL · Snyk · Trivy · OWASP ZAP

### [Malware Detection and Analysis](https://github.com/Niksinikhilesh045/Malware-Detection-and-Analysis)

A Python machine-learning project exploring malware classification using static features from Portable Executable (PE) files, model comparison and file-analysis workflows.

This is an experimental project; detection results depend on the dataset, evaluation setup and inputs.

**Stack:** Python · scikit-learn · pandas · NumPy

## Tools I use

| Area | Technologies |
| --- | --- |
| Backend | Java, Spring Boot, Python, FastAPI, REST APIs |
| Data | MongoDB, MySQL, SQL, Redis |
| Delivery and testing | Git, Docker, GitHub Actions, CI/CD, JUnit, pytest |
| Systems and security | Linux, Bash, cloud storage, IAM, authentication and authorization, security automation |
| Additional programming | C++, C |

## What I'm developing next

I'm deepening my understanding of distributed systems, cloud infrastructure and backend reliability. I'm also learning to build AI-enabled applications on top of that backend foundation.

I share project breakdowns and engineering notes on [LinkedIn](https://www.linkedin.com/in/nikhileshsingh06/), including the implementation choices, tradeoffs and limitations behind the work.

## Writing and credentials

I have written technical articles for upGrad KnowledgeHut, including [What is Tor in Cybersecurity?](https://www.knowledgehut.com/blog/security/what-is-tor-in-cyber-security).

Credential verification links:
- [Certified Ethical Hacker (CEH)](https://aspen.eccouncil.org/VerifyBadge?type=certification&a=seYJXFBB5L37ScZF3bq4kBSODNMNjc78Ll7VvZ12khc=)
- [Network Defence Essentials (NDE v1)](https://aspen.eccouncil.org/VerifyBadge?type=certification&a=QGFV1K0UM2Fu8+a3T+07+yPMjL1ClOh0w7K5h3WEHpA=)

## Let's connect

I'm interested in **Software Engineer, Backend Engineer and Software Engineer – Security** opportunities at product, SaaS, fintech and cybersecurity companies, and startups building useful software.

**Preferred location:** Bengaluru. Open to suitable opportunities elsewhere in India and remote or hybrid teams.

Reach me on [LinkedIn](https://www.linkedin.com/in/nikhileshsingh06/) or at [nikhileshsingh045@gmail.com](mailto:nikhileshsingh045@gmail.com).
