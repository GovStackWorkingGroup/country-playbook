---
description: Version for TAC Review
---

# Prototype

## Develop, test, and iterate a functional prototype.

Once the [wireframe ](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/design-and-delivery/wireframes)[and/or voice command flow](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/design-and-delivery/wireframes) is approved, we are ready to start developing and orchestrating a functional prototype of the service. Digital teams can either use GovStack sandbox or their own infrastructure. Since GovStack is currently in the process of developing the sandbox, future versions of the playbook will describe the processes to use GovStack sandbox to deploy the functional prototype.&#x20;

The prototype is iteratively developed. Each successive iteration adds new functionalities and refines the prototype based on user feedback. This results in a service that meets the desired level of functionality and usability. Following are the stages of prototyping a digital government service, from α version to the Launch version:

| α version prototype                                                                                                                                                                                                                                                                                                                                                                     | β version prototype                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Pilot version                                                                                                                                                                                                                                                                                                                         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| α version is a rough functional prototype used to test the initial concept and get feedback from a limited number of users and stakeholders. The duration for the α version must be agreed upon between service owners and stakeholders. It usually lasts between a few weeks and months. α version can be hosted in a testing environment that may or may not be the GovStack Sandbox. | <p>Once the α version is tested and feedback is collected, the β version is developed. This prototype is more refined and is closer to the final digital service. It includes more features and functionalities and is tested by a larger group of users or stakeholders to identify any final issues before launching the next iteration.</p><p>In case the β version is hosted on GovStack Sandbox, preparations must be made to deploy it on the country's cloud infrastructure/ production environment.</p> | The launch version is the first version of the service that is released to the public. It includes the core features and functionalities that meet the needs of the users and further iterated based on future user feedback. It is deployed, operated, and maintained on the country's cloud infrastructure/ production environment. |



<figure><img src="../../.gitbook/assets/Protype (8).png" alt=""><figcaption></figcaption></figure>

If the launch version is decided to be deployed on the country's cloud and infrastructure/ production environment, it can be configured following GovStack enterprise architecture.

<figure><img src="../../.gitbook/assets/53.-Functional-prototype.jpg" alt=""><figcaption><p>Options for countries to deploy the functional prototype.</p></figcaption></figure>

{% tabs %}
{% tab title="Activities  / Resources" %}
How to get there:

* Develop Product and Technical specifications for the service.
* Develop the front end and back end of the service according to the Product and Technical specifications and approved wireframes and/or voice command flow. &#x20;
* Develop a test script considering all the branches of "to-be" user journey. &#x20;
* Prepare and implement test scripts
* Prepare the security and quality assurance checklist &#x20;
* Prepare the digital service release plan &#x20;
* Prepare the stabilization and maintenance routine &#x20;
* Launch α, β versions to a limited set of citizens/business users, admins, and public officials.&#x20;
* Collect their feedback on the functional prototype and identify concrete steps to improve it.
* Iteratively developed and deliver the launch version that meets the requirements and needs of citizens/business users, admins, and public officials.
* Prepare and implement a cutover plan.
* Next steps:
  * Prepare the migration plan for the launch version into the country's cloud and infrastructure/ production environment.&#x20;
  * Prepare the launch of the service.
  * Stabilize the service
{% endtab %}

{% tab title="Responsibilities" %}
Who does what

* [Service designer](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/annex/govstack-user-profiles-taxonomy#service-designer) – Lead the service co-design journey&#x20;
* [Product Owner](http://127.0.0.1:5000/o/pxmRWOPoaU8fUAbbcrus/s/zdXe8NbIMZIv5sydPBf6/) – Lead software product development according  to the service blueprint &#x20;
* [Front-end developer](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/annex/govstack-user-profiles-taxonomy#front-end-developer) – Develops front-end applications following UX/UI style guide &#x20;
* [Solution architect](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/annex/govstack-user-profiles-taxonomy#solution-architect) – Architects the service according to the BB integration plan &#x20;
* [Back-end developer](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/annex/govstack-user-profiles-taxonomy#back-end-developers) –  Adjust BB, connects legacy systems, and test the application&#x20;
* [Digital security manager](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/annex/govstack-user-profiles-taxonomy#digital-security-manager) - validates compliance with digital security policy
* [Cloud architect](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/annex/govstack-user-profiles-taxonomy#cloud-architect) - Designs cloud strategy and microservices architecture that supports the digitalisation of government services
{% endtab %}

{% tab title="Deliverables" %}
Since GovStack is starting it's reference implementations in countries, the following resources will be linked as soon as they are generated:

* GitHub repository with code documented according to Country Digital Service Standard
* Front-end design manual &#x20;
* Admin manual &#x20;
* User manual &#x20;
* Solution architecture manual&#x20;
* Test plan & results report &#x20;
* Security & QA checklists & results report &#x20;
* Training plan and support strategy per role &#x20;
* Release plan &#x20;
* Stabilization and maintenance routine &#x20;

Deliver a functional prototype of the service which:

* Complies with the approved 'To-be user journey' and wireframe and/or voice command flow
* Complies to Country digital service design standards. This includes standards for:&#x20;
  * [Service information sheet](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/learning-and-exchange/artefacts#information-service-sheets)
  * [Downloadable forms](broken-reference)
  * [Web forms](broken-reference)
  * [Electronic documents](broken-reference)
  * [Notifications](broken-reference)
  * [Performance analytics](broken-reference)
  * [Citizen satisfaction survey](broken-reference)
  * [Accessibility ](broken-reference)
* Complies with Country enterprise architecture, including digital security protocols approved by the country technical team&#x20;
{% endtab %}
{% endtabs %}

