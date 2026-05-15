# Alejandro Achinelli — Desarrollador Backend .NET

**Backend Senior · Arquitectura cloud · Rosario, Argentina**

6 años construyendo APIs REST y microservicios .NET en producción para sectores de energía, seguros, fintech y gobierno. Co-diseñé un API Gateway multi-tenant que hoy sirve a 5+ distribuidoras eléctricas nacionales. Migré sistemas legados a .NET 8 con Clean Architecture, CQRS y DDD en tres empresas distintas. Implementé arquitectura cloud completa en Azure para plataforma con 5M de usuarios potenciales.

Estoy orientando mi carrera hacia arquitecto de software: estudiando patrones avanzados, construyendo proyectos de portfolio con documentación arquitectónica real y usando IA como herramienta de desarrollo cotidiano.

---

## Lo que hago bien

**Backend y arquitectura**
- C# / .NET 8 — APIs REST, microservicios, Clean Architecture, CQRS, DDD
- API Gateway multi-tenant, autenticación JWT + Redis blacklist, OAuth2, SSO
- SQL Server avanzado · PostgreSQL · EF Core (escrituras) + Dapper (lecturas)
- Redis · Serilog · correlación distribuida

**Cloud y DevOps**
- Azure: App Services, Front Door, Application Gateway, AKS, VNet, NSG
- Docker · CI/CD en Azure DevOps y GitHub Actions
- Observabilidad: Grafana + Loki + Prometheus

**Frontend**
- React + TypeScript · Redux (experiencia real en proyectos bancarios y de seguros)

---

## Proyectos de portfolio

### nexa-learn — Arquitectura limpia con .NET 8
API REST de gestión de cursos construida de cero para demostrar arquitectura de software con criterio real. Clean Architecture, CQRS con MediatR, DDD, Outbox Pattern para domain events, tests por capas con Testcontainers, CI/CD con GitHub Actions y documentación arquitectónica completa.

[![CI](https://github.com/alejandroachinelli/nexa-learn/actions/workflows/ci.yml/badge.svg)](https://github.com/alejandroachinelli/nexa-learn)
[![Ver repositorio](https://img.shields.io/badge/ver_repositorio-black?style=flat&logo=github)](https://github.com/alejandroachinelli/nexa-learn)

`.NET 8` `PostgreSQL` `EF Core` `MediatR` `FluentValidation` `Testcontainers` `OpenTelemetry` `GitHub Actions`

---

## En producción real

**API Gateway Multi-tenant — Storey** *(en producción)*
.NET 8 orquestando peticiones a 6 providers especializados para 5+ distribuidoras eléctricas nacionales. JWT + Redis blacklist + Firebase Auth, logging HTTP con Correlation ID, observabilidad con Grafana + Loki + Prometheus.

**Arquitectura cloud Azure — Storey** *(en producción)*
Diseño e implementación de infraestructura cloud para plataforma multi-tenant con 5M de usuarios potenciales. Azure Front Door como entrada global con SSL wildcard, Application Gateway para balanceo de carga, App Services para microservicios .NET 8, configuración de VNet, NSG y health probes en UAT y producción.

**Migraciones legacy → .NET 8** *(Ensitech + Redbrow)*
Migración de sistemas .NET Framework 4.8 a microservicios .NET 8 con DDD, CQRS y Clean Architecture. Aplicado en dos empresas en dominios de seguros y fintech. Infraestructura completa por microservicio: Docker, Azure AKS, CI/CD.

---

## Cómo trabajo

Cada proyecto tiene spec aprobada antes de escribir código, ADRs documentando decisiones de arquitectura, tests por capas con criterio de aislamiento explícito y CI verde en cada commit. Uso Claude CLI como herramienta de desarrollo: spec-driven development, red-green-refactor y documentación generada desde el código real.

---

## Aprendiendo ahora

- Arquitecturas avanzadas: gRPC, Kafka, service mesh
- Node.js y Python para ampliar el stack backend
- Next.js 14 App Router
- Inglés técnico — nivel A2, en progreso

---

## Contacto

📧 alejandromartin.achinelli@gmail.com
💼 [linkedin.com/in/alejandroachinelli](https://linkedin.com/in/alejandroachinelli)