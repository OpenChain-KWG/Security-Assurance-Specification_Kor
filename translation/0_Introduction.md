# Open Source Security Assurance Guide v1.0

오픈소스 보안 보증 가이드 버전 1.0

## Introduction

소개

The OpenChain Specification working group’s core mission is to develop Program standards that establish trust in the Open Source from which modern-day software solutions are built. The OpenChain project’s flagship specification, ISO 5230 International Standard for Open Source Compliance, focuses on establishing trust around Open Source license compliance. A natural next step in support of the broader mission was to develop a guide to identify and present the minimum core set of requirements every Security Assurance program should satisfy with respect to the use of Open Source software. Initially the scope is limited to ensuring that an organization vets the Open Source with regard to known publicly available security vulnerability issues (e.g., CVEs, GitHub/GitLab vulnerability alerts, package manager alerts and so forth).  The guide’s scope may expand overtime based on community feedback. 

OpenChain Specification 워킹 그룹의 핵심 역할은 현대의 소프트웨어 솔루션을 개발하는데 있어서 오픈소스에 대한 신뢰를 확립하는 프로그램 표준을 개발하는 것이다. OpenChain 프로젝트의 대표 규격인 ISO 5230 국제 표준은 현재 오픈소스 라이선스 컴플라이언스를 중심으로 신뢰를 구축하는데 중점을 두고 있다. 보다 넓은 범위의 역할을 지원하기 위한 다음 단계는 오픈소스 사용과 관련하여 모든 보안 보증 프로그램이 충족해야 할 최소 핵심 요구 사항을 식별하고 제시하는 가이드를 개발하는 것이었다. 우선 오픈소스에서 알려진 공개 보안 취약성 문제(예: CVE, GitHub/GitLab 취약성 경고, 패키지 관리자 경고 등)가 있는지 확인하는 것으로 범위를 한정한다. 이러한 가이드의 범위는 시간이 지남에 따라 커뮤니티 피드백을 반영하여 확장할 수 있다. 

Conformance with this reference guide provides assurance that an organization has a Program in place that takes the expected steps necessary to establish a trusted level of Security Assurance with respect to the Open Source used. This document focuses on the “what” and “why” aspects of a Program rather than the “how” and “when”. This ensures flexibility for different organizations of different sizes in different industries to choose specific policy and process content that fits their size, goals and Program scope. For instance, a conformant Program may address a single product line or the entire organization.

이 참조 가이드를 준수한다는 것은 조직이 사용하는 오픈소스와 관련하여 신뢰할 수 있는 수준의 보안 보증<sub>Security Assurance</sub>을 구축하기 위해 필요한 단계를 수행하는 프로그램을 갖추었음을 보증한다. 이 문서는 프로그램의 "How"와 "When"보다는 "What"과 "Why" 측면에 중점을 둔다. 이를 통해 다양한 산업에서 각기 다른 조직의 규모, 목표, 프로그램 범위에 맞는 구체적인 정책과 프로세스 콘텐츠를 선택할 수 있는 유연성을 보장한다. 예를 들어, OpenChain 적합 프로그램은 단일 제품군 또는 전체 조직을 대상으로 적용할 수 있다.

This introduction describes the guide’s purpose. Section 2 defines key terms used throughout this document. Section 3 defines the requirements that a program must satisfy to achieve a sufficient level of security assurance. Each requirement consists of one or more verification materials (i.e., records) that must be produced to satisfy the requirement. Verification materials are not required to be made public, though an organization may choose to provide them to others, potentially under a Non-Disclosure Agreement (NDA). 

이 소개에서는 가이드의 목적을 설명한다. 2장에서는 이 문서 전체에서 사용되는 주요 용어를 정의한다. 3장에서는 프로그램이 핵심 수준의 보안 보증을 달성하기 위해 충족해야 하는 요구 사항을 정의한다. 각 요구 사항은 이를 충족하기 위해 생성해야 하는 하나 이상의 입증 자료(문서 등)를 포함한다. 입증 자료를 공개해야 하는 것은 아니지만, 필요할 경우 NDA(Non-Disclosure Agreement)를 맺고 다른 조직에 제공할 수 있다.

This reference guide is licensed under [Creative Commons Attribution License 4.0](https://creativecommons.org/licenses/by/4.0/) (CC-BY-4.0).

이 참고 가이드는 Creative Commons Attribution License 4.0 (CC-BY-4.0)에 따라 라이선스가 부여된다.