# Develop Application Systems For Multiple User Tenants

## Design Patterns

* Pooled Resource Multi-Tenant Architecture
* Siloed Resource Multi-Tenant Architecture

* Isolate by separate public IaaS account per tenant
* Isolate by separate public IaaS VPC per tenant
* Isolate by separate public IaaS VPC subnet per tenant

* Isolate by separate application database per tenant
* Isolate by separate application database table per tenant
* Isolate by database table row level authorization per tenant

## Principles

* Do not trust application code to enforce isolation rules
* Implement data repository level policy enforcement

## Resources

* [Beyond Multitenancy: Introducing A New Container-Based Application Factory](https://learning.oreilly.com/videos/oreilly-software-architecture/9781491976142/)
* [Effective Multi-Tenant Distributed Systems](https://learning.oreilly.com/library/view/effective-multi-tenant-distributed/9781492042839/)
* [AWS SaaS Facotry SaaS Architecture Overview](https://aws.amazon.com/partners/programs/saas-factory/saas-architecture-overview/)
* [AWS re:INVENT 2018: Deconstructing SaaS: A Deep Dive Into Building Multi-tenant Solutions On AWS (Tod Golding)](https://youtu.be/mwQ5lipGTBI)
* [AWS re:INVENT 2019: SaaS Tenant Isolation Patterns](https://youtu.be/fuDZq-EspNA)
* [How To Build Modern SaaS Applications On AWS](https://www.youtube.com/watch?v=mPXxypb5UJg)
* [AWS re:INVENT 2019: Microservices Decomposition For SaaS Environments](https://www.youtube.com/watch?v=AOfuZN5yo38)
* [AWS re:INVENT 2019: Primary Storage For SaaS Solutions](https://www.youtube.com/watch?v=LWJb5qEIXxg)
* [AWS re:INVENT 2020: Inside Amazon EKS SaaS: Building Multi-Tenant Solutions With EKS](https://www.youtube.com/watch?v=a7gwxoMufeM)
* [AWS re:INVENT 2020: SaaS Boost: Using Open Source To Accelerate SaaS Adoption](https://www.youtube.com/watch?v=Ed59QyyXUvM)
* [GOTO 2020: SaaS Deep Dive: Designing And Buiding Multi-Tenant Solutions (Tod Golding)](https://youtu.be/joz0DoSQDNw)
* [Developing Your App, From Front To Back (Building A SaaS, Part 2)](https://youtu.be/KzEo82xcRSI)