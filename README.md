# Otázky SZMGR-SWE (DEV)

Oficiální link s otázkami: [https://www.fi.muni.cz/studies/fe-mgr/swe2021.html](https://www.fi.muni.cz/studies/fe-mgr/swe2021.html)

Za správnost/aktuálnost neručím, jako příklady jsem používal technologie mně blízké. Občas jsou v materiálech informace navíc (z jiných předmětů/zdrojů). Pokud najdete chybu/nepřesnost, feel free to PR. Občas míchám pojmy jako struktura a třída, myslím tím v podstatě to samé (rust/go struktury víceméně odpovídají java/c# třídám). Odkazy na zdroje v ISu vám nemusí fungovat, pokud jste v daném období předmět neměli... v takovém případě by mělo stačit přepsat období v linku.

Sepsáno na základě přednášek, osobních zkušeností, praxe, a samozřejmě drobné pomoci ChatGPT :) Pro rychlé pochopení základních konceptů dané technologie doporučuju mrknout na [Fireship](https://www.youtube.com/@Fireship) a jeho `in 100 seconds` videa.

## Core

1. [Programming and software development](./1_programovani_a_softwarovy_vyvoj.md) (PA165 || **PV179**)
    - [ ] Development of software solutions, specifics of implementing web-based information systems.
    - [ ] Tools and environments for software development of large-scale systems.
    - [ ] Basic concepts of software architectures from an implementation perspective.
    - [ ] Multilayer architecture of modern information systems, model-view-controller architecture.
    - [ ] Persistence, ORM.
    - [ ] Practical examples for all of the above.
2. [Code quality](./2_kvalita_kodu.md) (**PV260**, **PA017**, **PA103**)
   - [ ] Quality in software systems development, quality attributes and software metrics.
   - [ ] Tactics for quality assurance at the level of individual quality attributes.
   - [ ] Clean Code and SOLID principles, code refactoring.
   - [ ] Code testing, unit tests, integration tests, user and acceptance tests.
   - [ ] Debugging and performance testing.
   - [ ] Quality management process in software systems development.
   - [ ] Practical examples for all of the above.
3. [Software Engineering](./3_softwarove_inzenyrstvi.md) (**PA017**)
   - [ ] Software life cycle, software development process and software development management.
   - [ ] (Rational) Unified Process (UP, RUP), agile methodologies and principles of agile software development.
   - [ ] Deployment and operation of software systems.
   - [ ] Maintenance of software systems, reusability.
   - [ ] Practical examples for all of the above.
4. [Project Management](./4_projektove_rizeni.md) (**PA179**)
   - [ ] Planning, risk management, role of models in project management.
   - [ ] Gantt charts, network analysis, critical path method (CPM), Program Evaluation and Review Technique (PERT).
   - [ ] International standards and methodologies for project management (PMI Project Management Body of Knowledge, PRINCE 2).
   - [ ] Practical examples for all of the above.
5. [Databases](./5_databaze.md) (PV003 || PV062 || **PA152**)
   - [x] Principles of data storage, databases and file systems.
   - [ ] Data encoding and compression.
   - [x] Architecture of relational databases, SQL query language and its parts (definitions, manipulation, transactions).
   - [x] Data schema definition language, DDL.
   - [x] Data manipulation language, DML.
   - [x] Relational algebra, integrity constraints, transaction control.
   - [x] Indexing, hashing.
   - [x] Practical examples for all of the above.
6. [Computer networks](./6_pocitacove_site.md) (**PA159**, PA191) - IMPORTANT
   - [x] Concepts, principles, architectures.
   - [x] ISO/OSI and TCP/IP model, IP protocol, transport protocols (TCP, UDP).
   - [x] Network layer protocols, IPv4 features, advanced IPv6 features.
   - [x] Peer-to-peer (P2P) networks, ad-hoc/sensor networks, high-speed networks, computer networks and multimedia.
   - [x] Practical examples for all of the above.
7. [Distributed Systems](./7_distribuovane_systemy.md) (**PA053**)
   - [x] Basic concepts, principles.
   - [x] Difference between centralized and distributed system architecture, disadvantages of both and how to overcome them.
   - [x] Replication, data sharing.
   - [x] Service-oriented architecture (SOA), web services.
   - [x] Examples of existing technologies and their use.
   - [x] Practical examples for all of the above.

## DEV

1. [Analysis and design of systems](./dev_1_analyza_a_navrh.md) (**PA103**, **PV167**, PV258)
   - [x] Object-oriented methods of information systems design.
   - [x] Requirements specification and management.
   - [x] Software architectures, component systems.
   - [x] Design and architectural patterns.
   - [x] Component interfaces, interface level contracts, OCL.
   - [x] Software system models, UML.
   - [x] Practical examples for all of the above.
2. [Data processing](./dev_2_zpracovani_dat.md) (**PA220**, **PA036**)
   - [x] Basic concepts and principles of data warehousing, data analytics and business intelligence.
   - [x] Data warehouse lifecycle.
   - [x] Big data analytics, languages for implementing analytic tasks, database-level analytics.
   - [x] Advanced data processing techniques, performance aspects of big data processing.
   - [x] Practical examples for all of the above.
3. [Secure Code](./dev_3_bezpecny_kod.md) (**PV157**, PA193, PV276, **PV017**) - IMPORTANT
   - [x] Authentication and access control methods.
   - [x] Biometric authentication methods, their implications and problems.
   - [x] Electronic signature and its use.
   - [x] Authentication of machines and applications.
   - [ ] Principles and principles of secure code.
   - [ ] Typical code-level security vulnerabilities, concurrency, input treatment.
   - [ ] Security vulnerability detection, penetration testing.
   - [ ] Practical examples for all of the above.
4. [User interfaces](./dev_4_uzivatelska_rozhrani.md) (**PV182** || PV247 || PV278)
   - [ ] Principles of user interface design and development in modern software systems, including web, mobile.
   - [ ] User interface development process and quality principles.
   - [ ] User experience (UX), interaction design, prototyping, wireframing, user research, usability testing.
   - [ ] Technologies and tools.
   - [ ] Practical examples for all of the above.
