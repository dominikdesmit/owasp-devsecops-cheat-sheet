# OWASP DevSecOps Cheat Sheet / HOW TO Guide 
The OWASP DevSecOps Cheat Sheet / HOW TO Guide

## Goal
Provide clear hands-on practices to start implementing DevSecOps within an organisation. Based on SAMM and DSOMM it gives practical guidelines and recommendations on how to implement different aspects of DevSecOps.

## Audience
- Developers (MVP?)
- Management
- Operators
- Security Professionals

## Steps
Different Steps are defined in the cheat sheet to define how you can start simple with some aspects of DevSecOps and improve them over time. Each step will have a link to practical examples, blog-posts and best practices. 

- Step 0 : Basics / prerequisites
- Step 1 : Adoption
- Step 2 : Improvement
- Step 3 : Optimization

The levels should also clearly state what benefits or value they bring. Why should a company implement steps 2 and 3 after step 1? 


## DevSecOps domains and aspects

- People
    - Skills
        - Step 0: Knowledge of development, operations and security practices
    - Roles & Responsibilities
        - Step 0: Development, operations, application security, QA/Testing
    - Culture
        - Step 0: Good communication, collaboration and knowledge sharing
- Processes
    - Risk Management
        - Step 0: Risk rating mechanism
    - Findings Generation
        - Step 0: Security requirements
    - Continuous Feedback
        - Step 0: Issue Tracking process
    - Central Policy Management
        - Step 0: Repositories and version control
- Technology
    - Infrastructure
        - Step 0: Automated
    - Tools
        - Step 0: API driven
    - Programming Language / Framework
        - Step 0: Tool compatibility
    
### TODO: Better mapping structure    

| Domain        | Aspect        | Step 0  | Step 1  | Step 2  | Step 3  |
| :-------------: |-------------|    -----|    -----|    -----|    -----|
| People        |  Culture             |         |         |         |         |
| Processes     |  Governance             |         |         |         |         |
| Technology    | Containers - Docker - Security     | [Docker Bench for Security](#docker-bench-for-security)  | Docker security tool implemented in CI/CD | Automated review process in place with build breakers | Base images constantly updated and clean of security issues |
|      -        | Secrets Management | Roadmap and goals | Centralized Approach | Secrets sprawl eradicated | Dynamic secrets| 
|      -        | SAST | 
|      -        | DAST | 
|      -        | Open Source Dependencies & Libraries | 

### Docker Bench for Security 
https://github.com/docker/docker-bench-security

