# Service blueprint

Service blueprints are companions to user journeys. They help organizations see the big picture of how a service is implemented and used. They pinpoint dependencies between user journeys of the service providers/government entities and users in the same visualization. They are instrumental in identifying and optimizing complex interactions, ultimately saving money for the organization and improving the experience for its users.

Service blueprints are created using To-Be [user journeys](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/learning-and-exchange/artefacts#user-journey-request-for-information-rfi-5) developed in the previous step. They comprise a series of diagrams that visualize the relationship between:

* Actions and goals of service stakeholders and users
* Different service users and entities involved in providing the service
* Generic workflows
* [Building Blocks](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/3-terminology#building-block)\


{% embed url="https://www.figma.com/file/v7rPzabWWEhGQcMfrsS4cM?fuid=1031671042446937934&prev-org-id=external-teams&prev-selected-view=recentsAndSharing&prev-tab=recently-viewed" %}
Service Blueprint of Construction Permit
{% endembed %}

<details>

<summary>Benefits of service blueprint</summary>

* Identify weaknesses in the user interface: Blueprinting exposes the big picture and offers a map of dependencies, thus allowing a service designer to discover a weak leak at its roots.
* Identity opportunity for optimization: The visualization of relationships in blueprints uncovers potential improvements and ways to eliminate redundancy.&#x20;
* Coordinating complex services by bridging cross-dependent efforts. Blueprinting forces service designers to capture what occurs internally throughout the totality of the user journey, giving them insight into overlaps and dependencies that departments/ministries alone could not identify.

</details>

Source: [Nielsen Norman Group](https://www.nngroup.com/articles/service-blueprints-definition/)

{% tabs %}
{% tab title="Activites/resources" %}
* Study the user journeys of the service
* Chart all the steps covered in the user journeys on the Service Blueprint template.
* For each step on the service blueprint:
  * Map the goals and actions performed by each service user, provider, and stakeholders
  * Data Input: Data required from the service users, providers, and stakeholders
  * Data output: Data presented to the service users, providers, and stakeholders at the completion of the step.
  * Identify and list the generic workflows that can facilitate the step
  * Based on the generic workflows and the GovStack technical specifications, list the potential set of Building Blocks that are required for the step.
* Upon completion of the service blueprint, map the generic design patterns to the steps on the blueprint.
{% endtab %}

{% tab title="Responsabilites" %}
Who does what:&#x20;

* [Service designer](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/annex/govstack-user-profiles-taxonomy#service-designer) - Lead the co-design of the service blueprint
* [Product owners](https://govstack.gitbook.io/bb-workflow/v/development-6/) - Oversee the development of the service blueprint, provide input when required, and review the final blueprint.
* [User needs researchers](broken-reference) – provide the service users' perspective when developing the service blueprint.
* [Back-end developer](https://govstack.gitbook.io/implementation-playbook/govstack-implementation-playbook/annex/govstack-user-profiles-taxonomy#back-end-developers) - assists in the identification and mapping of generic workflows and Building Blocks
* [UX/UI Designers](broken-reference) -assist in identifying the design patterns for each step in the service blueprint to later use in the development of wireframes.
{% endtab %}

{% tab title="Deliverables" %}
* Completed Service Blueprint with:
  * Goals and actions of each service user, provider, and stakeholder for each step
  * Generic workflows and Building Blocks required to facilitate the service
  * Set of Design patterns required to develop the wireframes
{% endtab %}
{% endtabs %}
