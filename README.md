# Umair Ali Shah

Senior Java Backend Engineer — 17+ years building and supporting enterprise and government backend systems, now relocating internationally and building hands-on depth in the modern cloud-native Java stack.

**Currently:** Senior Software Engineer at Everteam/Intalio, supporting EDMS and Correspondence Tracking System platforms for a multi-site government client.

**Core background:** Java, J2EE, Spring / Spring Boot, REST & SOAP integration, Oracle/SQL Server/MySQL, production support for systems with zero tolerance for downtime.

**Actively building:** Spring Boot 3, Docker, Kubernetes, CI/CD — see docmanager-api below, a document/correspondence-management REST API that re-implements the core of my production EDMS work on a modern stack.

**Open to relocation** with visa/work-permit sponsorship — no location preference.

---

### Featured projects

**docmanager-api** — Spring Boot 3, PostgreSQL, Docker, GitHub Actions CI
Repo: https://github.com/hunairali/docmanager-api
A document/correspondence management REST API with a review-approval workflow, built to demonstrate the modern stack alongside 17 years of enterprise Java/EDMS experience. Full test suite (JUnit 5, Mockito, WebMvcTest, DataJpaTest), OpenAPI docs, multi-stage Dockerfile, and a CI pipeline that builds and tests on every push.

**cts-auth-service** — Spring Boot 3, Spring Security 6, JWT, Docker, GitHub Actions CI
Repo: https://github.com/hunairali/cts-auth-service
Standalone JWT authentication microservice — registration, login, and token issuance/validation with Spring Security 6, built to sit in front of other services (like docmanager-api) needing centralized auth. Unit, service, and controller test coverage, a multi-stage Dockerfile, and a CI pipeline that runs the full Maven verify plus a Docker build on every push.

**docmanager-k8s** — Kubernetes, Kustomize, GitHub Actions (kubeconform)
Repo: https://github.com/hunairali/docmanager-k8s
Kubernetes manifests to deploy docmanager-api and its Postgres database: Namespace, ConfigMap/Secret, PVC, Deployments and Services, an Ingress, and an HPA, tied together with Kustomize. CI validates every manifest with kubeconform and dry-runs the Kustomize build on every push.

---

### Connect

LinkedIn: https://www.linkedin.com/in/umairalishah
Email: se.umair.ali@gmail.com

