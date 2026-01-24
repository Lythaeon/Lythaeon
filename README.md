<p align="left">
  <img src="https://komarev.com/ghpvc/?username=CelestialAC&label=Profile%20views&color=03f0fc&style=flat" alt="CelestialAC Profile Views" />
  &nbsp;<img src="https://img.shields.io/github/followers/CelestialAC?label=Followers&style=flat&color=03f0fc" alt="CelestialAC Followers" />
</p>

---

### 👋 Hello, I’m Wladimir

Freelance backend engineer building production-grade backend systems for teams that need reliability, performance, and long-term evolvability.

I specialize in **Node.js/TypeScript** and **Rust**, working on APIs, event-driven systems, and low-latency backend services that hold up under real workloads. My focus is correctness, clear domain boundaries, and architectures that scale without constant rewrites.

I’m currently leading a production rewrite from Node.js to Rust, working with geo-distributed state, async workflows, and infrastructure designed to scale across regions without surprises.

If your backend feels fragile, slow to change, or risky to scale, that’s usually where I’m brought in.


## 🛠️ Core Stack

### Languages  
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node-dot-js&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white)

### Backend & Architecture  
![Event Driven](https://img.shields.io/badge/Event--Driven-000000?style=for-the-badge)
![Async](https://img.shields.io/badge/Async-2C2D72?style=for-the-badge)
![REST APIs](https://img.shields.io/badge/REST_APIs-000000?style=for-the-badge)
![gRPC](https://img.shields.io/badge/gRPC-2DA3E2?style=for-the-badge&logo=grpc&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### Datastores & Messaging  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redpanda](https://img.shields.io/badge/Redpanda-CB1E1E?style=for-the-badge&logo=redpanda&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Pulsar](https://img.shields.io/badge/Pulsar-188FFF?style=for-the-badge&logo=apachepulsar&logoColor=white)

### Tooling & Platform  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Kong](https://img.shields.io/badge/Kong_Gateway-002659?style=for-the-badge&logo=kong&logoColor=white)
![HashiCorp Vault](https://img.shields.io/badge/HashiCorp_Vault-000000?style=for-the-badge&logo=vault&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=white)
![AWS S3](https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazon-aws&logoColor=white)

## 🚀 Latest Project: stexs-spike

**stexs-spike** is a backend platform for multiplayer games providing authentication, user management, and inventory systems as long-running services.

The current iteration includes:
- Authentication and user accounts  
- Player inventories and cross-inventory systems  
- OAuth2 integrations  
- Web platform for profiles, social features, purchases, and achievements  

This project is used to validate architecture choices for production backends: async workflows, event-driven coordination, and clear domain ownership.

## 🔄 Upcoming Architecture: STEXS Platform

**STEXS** is a backend infrastructure platform for multiplayer games, designed to provide shared services such as authentication, inventory, and storage without vendor lock-in.

The platform is backend-first, with architecture defined before feature scale. It is built around correctness, clear domain ownership, and long-term evolvability.

**Key design principles:**
- Rust-based core with strong type safety and async workflows  
- Intent-driven APIs aligned with real business actions  
- Vertical slice architecture with explicit domain boundaries  
- Event-driven core using Redpanda for loose coupling and auditability  
- Distributed SQL via YugabyteDB for global ACID state  
- Low-latency caching using Garnet  
- Edge request handling with Pingora for validation, rate limiting, and JWT caching  

This iteration focuses on building infrastructure that can evolve without breaking existing integrations.

## 💼 Work With Me

I design and build production-grade backend systems, including APIs, async workers, data pipelines, and event-driven services.

I work with founders and teams on:
- New backend projects and MVPs  
- Backend rewrites (e.g., Node.js → Rust)  
- Performance-critical backend components  
- Event-driven systems and message processing  
- Data ingestion and processing pipelines  

If you need a backend that is reliable under real load and designed to scale without constant rewrites, reach out via LinkedIn or Fiverr.
