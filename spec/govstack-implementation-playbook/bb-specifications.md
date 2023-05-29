---
description: Version for TAC Review
---

# BB specifications

**Building blocks** (BBs) are software modules that can be deployed and combined in a standardized manner. Each building block is capable of working independently, but they can be combined to do much more.

Building blocks are composable, interoperable software modules that can be used across a variety of use cases. They are standards-based, preferably open-source, and designed for scale.

Each building block exposes a set of services in the form of REST APIs that can be consumed by other building blocks or applications.

In this release of the GovStack specification, the following building blocks and their corresponding policy and governance recommendations are provided below:

<details>

<summary>Information Mediation</summary>

**Specifications**

The [Information Mediator](https://govstack.gitbook.io/bb-information-mediation) provides a gateway between external digital applications and other ICT Building Blocks, thereby ensuring interoperability and implementation of standards, which is essential for integrating various ICT Building Blocks and applications.

**Policy recommendations**&#x20;

* Interoperability should be a transversal mandate that applies to all government entities (With no exceptions). These types of mandates can be implemented using General laws and/or presidential/secretarial decrees regulating the following principles:
  * 'Only one principle' states that citizens should be required to provide information once to the government.
  * No government entity can request information from a citizen or interested party that other government entity already has.
  * Citizens or interested parties should give consent for their information to be exchanged and or consulted in order to access government services according to data protection law applicable in the country.
* Examples of regulations:
  * [Estonia](https://www.stat.ee/sites/default/files/2022-11/Estonian%20IT%20Interoperability%20Framework%20-%20Abridgement%20of%20Version%203.0.pdf)
  * [Mexico](https://www.gob.mx/wikiguias/articulos/decreto-por-el-que-se-establece-la-ventanilla-unica-nacional-para-los-tramites-e-informacion-del-gobierno-173691?state=published)

&#x20;**Governance recommendations**&#x20;

* Digital authorities should have the transversal mandate to coordinate the implementation of the aforementioned policy at the political, organizational, and technical levels ensuring service-level agreements that can guarantee continuity in service provision across all government entities.
* Digital authorities are encouraged to have a shared service team to support the development, maintenance, and update of APIs as with any other Building Block within the government stack.

</details>

{% hint style="info" %}
Estonia uses an open source information mediator platform called '[X-Road](https://e-estonia.com/solutions/interoperability-services/x-road/)' to enable secure and private data exchange between public and private entities. Funding to develop and maintain X-Road is provided by the Governments of Estonia, Finland, and Iceland through [Nordic Interoperability Institute](https://www.niis.org/).
{% endhint %}

{% embed url="https://youtu.be/9PaHinkJlvA" %}
Source: [https://e-estonia.com/solutions/interoperability-services/x-road/](https://e-estonia.com/solutions/interoperability-services/x-road/)
{% endembed %}

<details>

<summary><a href="https://govstack.gitbook.io/bb-registration">Registration</a></summary>

Records identifiers and other general information about a person, place or other entity, typically for the purpose of registration or enrollment in specific services or programmes and tracking of that entity over time.

</details>

<details>

<summary><a href="https://govstack.gitbook.io/bb-digital-registries">Digital Registries</a></summary>

Registries are centrally managed databases that uniquely identify persons, vendors, facilities, procedures, products and sites related to an organization, industry or activity.

</details>

<details>

<summary><a href="https://govstack.gitbook.io/bb-identity">Identity</a></summary>

Enables unique identification and authentication of users, organizations and other entities.

</details>

<details>

<summary><a href="https://govstack.gitbook.io/bb-payments">Payments</a></summary>

Implements financial transactions such as remittances, insurance claims, product purchases and payments of service fees, along with the logging of related transactional information. It also provides utilities for tracking costs and extracting audit trials.

</details>

<details>

<summary><a href="https://govstack.gitbook.io/bb-consent">Consent</a></summary>

Manages a set of policies allowing users to determine the information that will be accessible to specific potential information consumers, for which purpose, for how long and whether this information can be shared further.

</details>

<details>

<summary><a href="https://govstack.gitbook.io/bb-workflow">Workflow</a></summary>

Helps to optimize business processes by specifying rules that govern the sequence of activities to be executed as well as the type of information exchanged in order to orchestrate the process flow from its initiation to completion.

</details>

<details>

<summary><a href="https://govstack.gitbook.io/bb-messaging/">Messaging</a></summary>

Facilitates notifications, alerts and two-way communications between applications and communications services, including short message service (SMS), unstructured supplementary service data (USSD), interactive voice response (IVR), email and social media platforms.

</details>

<details>

<summary><a href="https://govstack.gitbook.io/bb-scheduler/">Scheduling</a></summary>

Provides an engine for setting up events based on regular intervals or specific combinations of status of several parameters in order to trigger specific tasks in an automated business process.

</details>
