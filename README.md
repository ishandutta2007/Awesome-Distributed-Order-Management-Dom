# Awesome-Distributed-Order-Management-Dom

## Top Distributed Order Management (DOM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Order Orchestration, Inventory Routing & Fulfillment Optimization*

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Distributed Order Management (DOM)**. These tools enable retailers, wholesalers, and enterprises to intelligently route orders across multiple fulfillment nodes, optimize inventory allocation, and orchestrate complex order lifecycles — reducing shipping costs and improving delivery speed.



**Examples** include Salesforce Order Management, Manhattan Associates Omni, Fluent Commerce, IBM Sterling Order Management, Blue Yonder OMS, Kibo Order Management, OneStock, Radial OMS, Deck Commerce, and Deposco OMS (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, event-driven order orchestration, and open fulfillment infrastructure — ideal for retailers, developers, and organizations seeking transparent, vendor-independent DOM solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform | Company Size (Revenue / Valuation) | Description | Pricing / Free Tier |
| :--- | :--- | :--- | :--- |
| **[Salesforce Order Management](https://www.salesforce.com/)** | ~$215B Market Cap / ~$41.5B Revenue | Native Salesforce DOM solution for B2C and B2B commerce. Features order capture, orchestration, fulfillment, and inventory visibility integrated with Commerce Cloud and Service Cloud. | Custom enterprise pricing (typically % of GMV or per-order fee). No free tier. |
| **[IBM Sterling Order Management](https://www.ibm.com/)** | ~$210B Market Cap / ~$62B Revenue | Enterprise DOM platform for omnichannel fulfillment. Features order orchestration, inventory sourcing, and returns management at scale. | Custom quote / enterprise licensing. No free tier. |
| **[Manhattan Associates Omni](https://www.manh.com/)** | ~$12B Market Cap / ~$1.13B Revenue | Enterprise omnichannel order management platform. Features distributed order management, store fulfillment, and inventory optimization for complex retail operations. | Custom quote / enterprise tier. No free tier. |
| **[Blue Yonder OMS](https://blueyonder.com/)** | ~$1.4B Revenue (Panasonic Subsidiary) | AI-powered order management solution. Features distributed order orchestration, inventory optimization, and fulfillment execution integrated with supply chain planning. | Custom enterprise pricing. No free tier. |
| **[Radial OMS](https://www.radial.com/)** | ~$1B Revenue ($820M Acquisition by bpost) | Omnichannel order management solution. Features enterprise-grade order orchestration, inventory management, and fulfillment for retail and B2B. | Custom quote / enterprise contracts. No free tier. |
| **[Kibo Order Management](https://kibocommerce.com/)** | ~$70M Revenue (Vista Equity Partners) | Composable commerce platform with DOM capabilities. Features order orchestration, inventory visibility, and fulfillment optimization. | Custom enterprise subscription. No free tier. |
| **[Deposco OMS](https://www.deposco.com/)** | ~$35M–$40M ARR / ~$35M+ Funding | Unified commerce platform with DOM capabilities. Features order orchestration, warehouse management, and fulfillment automation. | Custom quote / annual subscription. No free tier. |
| **[Fluent Commerce](https://fluentcommerce.com/)** | ~$25M–$30M Revenue / $46M+ Funding | Cloud-native distributed order management platform. Features real-time inventory visibility, intelligent order routing, and fulfillment orchestration across stores, warehouses, and dropship partners. | Custom enterprise pricing. No free tier. |
| **[OneStock](https://www.onestock-retail.com/)** | ~$26M ARR / $72M Growth Investment | Distributed order management platform for retail. Features ship-from-store, click-and-collect, and intelligent order routing to optimize inventory usage. | Custom quote based on order volume. No free tier. |
| **[Deck Commerce](https://www.deckcommerce.com/)** | ~$5M Revenue / ~$12.5M Funding | Order management system designed for direct-to-consumer brands. Features order orchestration, inventory management, and customer service tools. | Custom annual software subscription. No free tier. |

## Open-Source GitHub Projects



- **[Zentra Distributed OMS](https://github.com/print-ramcharan/distributed-oms)**  

  Production-grade, event-driven microservices ecosystem demonstrating **Saga Orchestration Pattern** (license varies). Built with Spring Boot 4.0, Apache Kafka, PostgreSQL, and Redis. Features real-time Control Center for monitoring distributed transaction lifecycles, Kafka event streams, and system capacity under sustained load. Includes 7 independent microservices, automated retries, Dead Letter Queues, and compensating transactions for failure scenarios .



- **[Distributed Commerce API](https://github.com/paulopacifico/distributed-commerce-api)**  

  Event-driven OMS demonstrating **Choreography Saga Pattern** and distributed tracing (license varies). Built with Java 21, Kotlin, Spring Boot, and Apache Kafka. Features order, inventory, payment, and shipment services communicating via 9 Kafka topics with compensation logic for failures (insufficient inventory, payment declined, shipment failed) .



- **[OpenOMS](https://github.com/openoms-org/openoms)**  

  Open-source Order Management System for e-commerce (ELv2 for API server, MIT for SDKs). Built with Go backend and Next.js dashboard. Features 463 API endpoints, 21 background workers, 27 SDK packages, Docker Compose and Helm chart deployment, and Prometheus metrics integration .



- **[Distributed Order Management System (AbhashK1)](https://github.com/AbhashK1/Distributed-Order-Management-System)**  

  Event-driven microservices architecture (license varies) built with Spring Boot, Kafka, Redis, and PostgreSQL. Features order service, inventory service (Redis atomic operations), payment service, and notification service. Includes Streamlit UI for visualizing the entire distributed order flow in real time .



- **[OrderRoute](https://pypi.org/project/syeedalireza-orderroute/)**  

  Smart logistics engine (license varies) that decides in real-time which warehouse should fulfill an order based on distance, stock availability, and shipping costs. Architecture includes Google OR-Tools for optimization, Celery & RabbitMQ for task queue, PostgreSQL with PostGIS for spatial queries, and Saga Pattern for distributed transactions .



- **[OpenB2B](https://github.com/deveasyclick/openb2b)**  

  Open-source, multi-tenant ordering and invoicing platform (license varies) for small wholesalers. Built with Go backend (Chi) and React frontend. Features order management with relational integrity, product management with SKU/inventory tracking, PDF invoice generation, multi-tenancy with Owner/Admin/Sales/Viewer roles, and basic reporting .



- **[Hyperrr](https://pkg.go.dev/github.com/GoHyperrr/hyperrr)**  

  AI-observable distributed commerce engine (license varies) designed as a modular monolith. Treats all commerce operations as deterministic, replayable DAG workflows connected by event fabric. Features declarative Sagas with compensation, GraphQL API gateway, Cobra CLI for system management, and Model Context Protocol (MCP) for AI agent observability .



- **[Craftplan](https://github.com/puemos/craftplan)**  

  Self-hosted ERP for small-batch, made-to-order manufacturers (license varies). Features order management with calendar view, recipe optimization with version control, inventory forecasting, iCalendar URL generation for Google Calendar/iOS, and Docker Compose deployment .



- **[FluteTracker](https://hub.docker.com/r/sohierc/flutetracker)**  

  Custom inventory and order management system (license varies) for flute makers. Features Kanban-style production pipeline, custom data attributes, intelligent pricing with attribute-based modifiers, sales library with templates, and CSV import/export .



- **[Inventoros](https://github.com/Inventoros/Inventoros)**  

  Open-source PHP-based Inventory/WMS management (license varies). Features orders with approve/reject workflows, payments with refunds/voids, shipments, product variants with stock adjustments, batch tracking, and REST API with Sanctum token authentication .



### Additional Strong Open-Source Options



- **[OpenBoxes](https://github.com/openboxes/openboxes)** — Open-source supply chain and inventory management system (EPL-1.0) for healthcare and distribution. Features purchase orders, stock management, shipment tracking, and REST APIs .

- **[Warehauser](https://github.com/warehauser/warehauser)** — Open-source warehouse management backend (Apache-2.0) written in Python/Django .

- **[myWMS](https://www.iml.fraunhofer.de/en/fields_of_activity/material-flow-systems/software_engineering/research1/mywms-open-source-warehouse-management-system.html)** — Open-source warehouse management system framework from Fraunhofer IML for customizable WMS and material flow control .

- Community **n8n** workflows for order event routing and fulfillment automation.



**Frameworks for building custom systems**: Combine **Zentra** or **Distributed Commerce API** as the event-driven orchestration engine with **OrderRoute** for intelligent warehouse routing, **OpenOMS** for API and dashboard infrastructure, and **PostgreSQL + Redis + Kafka** for persistence and messaging — creating a fully self-hosted, enterprise-grade distributed order management platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Order management systems handling customer data must comply with data protection regulations (GDPR, CCPA, PCI-DSS, etc.).

- Self-hosted open-source solutions require proper security hardening, message queue configuration, and ongoing maintenance for production reliability.



---



**Made for retail operations, supply chain teams, and developers building transparent distributed order management solutions.**

Let's make Distributed Order Management more open, data-driven, and efficient.
