---
description: Version for TAC Review October 2022
---

# Accompany Country team in migration of a functional prototype into the local infrastructure/cloud.

If the functional prototype has been developed and tested in the GovStack Sandbox, it is necessary to migrate the functional prototype into the Country local infrastructure/cloud.

{% tabs %}
{% tab title="Scope of work" %}
A good migration should:

* Follow a migration plan
{% endtab %}

{% tab title="Activities" %}
How to get there

*   Develop the front end of the service according to Country Digital Service Standard &#x20;

    Information service sheets,&#x20;

    * Downloadable forms, &#x20;
    * Web forms, &#x20;
    * Electronic documents, &#x20;
    * Notifications, &#x20;
    * Performance analytics, &#x20;
    * Citizen satisfaction survey, &#x20;
    * Accessibility &#x20;
* Orchestrate the back end of the service according to business blue print (BPMN), and BB integration map, configure connectors where need it &#x20;
* Prepare a test script considering compliance with technical specs as well as in the context of the entire "to-be" user journey. &#x20;
* Prepare the security and quality assurance check list &#x20;
* Prepare the digital service release plan &#x20;
* Prepare the stabilization and maintenance routine &#x20;

The MVP Deployment Process involves the following main steps ([vmware.com](https://www.vmware.com/topics/glossary/content/application-deployment.html)):&#x20;

1. Plan. Map out the deployment schedule assessing the current country infrastructure, and implement changes if necessary.&#x20;
2. Build and Release Automation. Enabling automation is key to a successful app deployment process, as the possibility for human error needs to be decreased as much as possible. Developing script and hearty servers will help ease deployment across the network later. (Potential example: [Ansible](https://www.ansible.com/use-cases/application-deployment))&#x20;
3. Develop Continuous Integration / Continuous Delivery (CI/CD). Working to reduce the degree of change in each application update will help teams spot breakdowns in the future. When deployments are minimally impactful, the digital services will be able to carry out more frequent updates easier.&#x20;
4. Create and Test Scripts. Identify environmental changes and differences by running test scripts on a backup copy of production before moving to the final release.&#x20;
5. Identify Key Metrics. Make sure your team is clear on key performance indicators (KPIs) from one application to another. This step is simple: make sure KPIs are set, visibility is enabled, and any potential errors in the application set are troubleshot swiftly.&#x20;
6. Test. Set up synthetic transaction tests, and make sure key items like log-in pages are working correctly. Go into your deployment with confidence.&#x20;
7. Develop Deployment Tracking. Enable and implement tracking services to make sure ops teams can easily track when deployments occur (or when they’re scheduled to), and to immediately identify when errors occur and how to fix them.&#x20;
8. Alert Users and Colleagues. This is an often-overlooked step, but when it applies, alert necessary service stakeholders as to when a service is expected to deploy. This will help coordinate throughout the process, set expectations, and backtrack if there were any errors.&#x20;
9. Monitor and Iterate. Once the service is deployed, it will be as equally as important to monitor deployment and correct as needed.&#x20;

&#x20;
{% endtab %}

{% tab title="Digital team" %}
Who does what

* Service designer – Lead the service co-design journey&#x20;
* Product Owner – Lead software product development according &#x20;

to service blue print &#x20;

* Fron end developer – Develops front end application following &#x20;

UX/UI style guide &#x20;

* Solution architect – Architects the service according to BB integration plan &#x20;
* Back end developer –  Adjust BB, connects legacy systems and test the application&#x20;
{% endtab %}

{% tab title="Untitled" %}
* GitHub repository with code documented according to Country Digital Service Standard &#x20;
* Front end design manual &#x20;
* Admin manual &#x20;
* User manual &#x20;
* Solution architecture manual&#x20;
* Test plan & results report &#x20;
* Security & QA check lists & results report &#x20;
* Stabilization and maintenance routine &#x20;
{% endtab %}

{% tab title="Next steps" %}
What to do next&#x20;

* Present functional prototype with users, the service community and relevant stakeholders &#x20;
* Gather feedback and iterate &#x20;
* Prepare hand over plan to migrate the prototype to the Country SandBox&#x20;
* Prepare Digital Service Design Journey Memoir &#x20;
* Put service in the run & maintain a service journal &#x20;
{% endtab %}

{% tab title="Resources" %}
LMS Modules: 1, 2, 3 &#x20;

* Use the cross building block integration diagram template&#x20;
* Use the GovStack test scripts template &#x20;
* Use the GovStack security and QA check list &#x20;
* Use the GovStack digital service release plan template &#x20;
* Use the GovStack GitHub repository guidelines &#x20;
* Use the GovStack Front end design manual &#x20;
* Use the GovStack &#x20;
  * Users (Admin, user, public servant, among others) manual &#x20;
* Use the GovStack Solution architecture manual&#x20;
* Use the GovStack Test plan & results report &#x20;
* Use the GovStack Security & QA check lists & results report &#x20;
* Use the GovStack Stabilization and maintenance routine &#x20;



GovStack specifications - Cloud and Infrastructure (Wave 3)



Skill building:&#x20;

* Basics of Cloud Infrastructure&#x20;
  * Ansible ([Red Hat Course](https://www.redhat.com/en/services/training/do007-ansible-essentials-simplicity-automation-technical-overview?extIdCarryOver=true\&intcmp=7013a000002pwDlAAI\&sc\_cid=7013a000002pgyuAAA))&#x20;
  * CI/CD ([Red Hat Course](https://www.redhat.com/en/services/training/do400-red-hat-devops-pipelines-and-processes-with-jenkins-git-and-test-driven-development))&#x20;
{% endtab %}
{% endtabs %}
