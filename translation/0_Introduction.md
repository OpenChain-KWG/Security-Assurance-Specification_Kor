# OpenChain Security Assurance Reference Guide version 0.1

OpenChain 보안 보증 참고 가이드 버전 0.1

## Introduction

소개

The OpenChain Specification working group’s core mission is to develop program standards that establish trust in the open source from which modern-day software solutions are built. The OpenChain project’s flagship specification, ISO 5230 International Standard, is currently focused on establishing trust around open source license compliance. In support of its mission, the working group has embarked on an exploratory initiative to develop a set of requirements that serve as a benchmark every quality open-source security assurance program would satisfy. 

OpenChain Specification 워킹 그룹의 핵심 역할은 현대의 소프트웨어 솔루션을 개발하는데 있어서 오픈소스에 대한 신뢰를 확립하는 프로그램 표준을 개발하는 것이다. OpenChain 프로젝트의 대표 규격인 ISO 5230 국제 표준은 현재 오픈소스 라이선스 컴플라이언스를 중심으로 신뢰를 구축하는데 중점을 두고 있다. 워킹 그룹은 자신의 역할 수행을 위해 수준있는 오픈소스 보안 보증 프로그램이 갖춰야할 벤치마크 역할을 하는 일련의 요구 사항 개발을 위한 실험적 초기 작업에 착수하였다.  

Conformance with this reference guide provides assurance that an organization has a program in place that takes the expected steps necessary to establish a high level of security assurance with respect to the open source used. This document focuses on the “what” and “why” aspects of a program rather than the “how” and “when”. This ensures flexibility for different organizations of different sizes in different markets to choose specific policy and process content that fits their size, goals and scope. For instance, a conformant program may address a single product line or the entire organization.

이 참조 가이드를 준수한다는 것은 조직이 사용하는 오픈소스와 관련하여 높은 수준의 보안 보증<sub>Security Assurance</sub>을 구축하기 위해 필요한 단계를 수행하는 프로그램을 갖추었음을 보증한다. 이 문서는 프로그램의 "How"와 "When"보다는 "What"과 "Why" 측면에 중점을 둔다. 이를 통해 시장 규모에 따라 각기 다른 조직의 규모, 목표, 범위에 맞는 구체적인 정책과 프로세스 콘텐츠를 선택할 수 있는 유연성을 보장한다. 예를 들어, OpenChain 적합 프로그램은 단일 제품군 또는 전체 조직을 대상으로 적용할 수 있다.

This introduction provides the context for all potential users. Section 2 defines key terms used throughout this document. Section 3 defines the requirements that a program must satisfy to achieve a sufficient level of security assurance. Each requirement consists of one or more verification materials (i.e., records) that must be produced to satisfy the requirement. Verification materials are not required to be made public, though an organization may choose to provide them to others, potentially under a Non-Disclosure Agreement (NDA). 

이 소개에서는 모든 잠재적 사용자를 위한 개요를 제공한다. 2장에서는 이 문서 전체에서 사용되는 주요 용어를 정의한다. 3장에서는 프로그램이 충분한 수준의 보안 보증을 달성하기 위해 충족해야 하는 요구 사항을 정의한다. 각 요구 사항은 이를 충족하기 위해 생성해야 하는 하나 이상의 입증 자료(문서 등)를 포함한다. 입증 자료를 공개해야 하는 것은 아니지만, 필요할 경우 NDA(Non-Disclosure Agreement)를 맺고 다른 조직에 제공할 수 있다.

This reference guide is licensed under [Creative Commons Attribution License 4.0](https://creativecommons.org/licenses/by/4.0/) (CC-BY-4.0).

이 참고 가이드는 Creative Commons Attribution License 4.0 (CC-BY-4.0)에 따라 라이선스가 부여된다.