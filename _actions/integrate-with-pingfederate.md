---
name: Integrate with PingFederate
description: PingFederate is an enterprise federation server that enables user authentication and single sign-on.
links:
    - title: PingFederate
      url: https://www.pingidentity.com/en/software/pingfederate.html
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com            
video: ''      
issue: https://github.com/postman-open-technologies/lifecycle/issues/54
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_actions/integrate-with-pig-federate.md
...
PingFederate is an enterprise federation server that enables user authentication and single sign-on. It serves as a global authentication authority that allows employees, customers and partners to securely access all the applications they need from any device. PingFederate easily integrates with applications across the enterprise, third-party authentication sources, diverse user directories and existing IAM systems, all while supporting current and past versions of identity standards like OAuth, OpenID Connect, SAML and WS-Federation. And it can be deployed on-premises or in the cloud, so you can support today’s needs and future-proof your business for tomorrow’s requirements.

Postman does not have a direct integration for PingFederate currently, but there are other options for connecting with PingFederate as part of your operations until there is a first-class integration as part of the Postman platform. Here is what is currently available to support PingFederate on the Postman platform:

- [PingFederate Admin API Postman Collection](https://github.com/pingidentity/Postman-Calls/tree/master/PingFederate%20Admin%20API) - This existing Postman collection can be used to integrate into PingFederate, then when applied with a specific environment can be used to manually or automatically orchestrate using PingFederate via it's API.
- [Official Ping Public Workspace](https://www.postman.com/ping-identity/workspace/pingone/overview) - Ping has a public workspace where it makes collections available for commenting and forking, providing additional resources that can be used to put PingFederate to work via Postman.

There is no [Github Issue submitted requesting an integration with Postman](https://github.com/postmanlabs/postman-app-support/issues?q=is%3Aissue+is%3Aopen+pingfederate), and if this is something your organization would like to see happen we recommend you [submit an issue](https://github.com/postmanlabs/postman-app-support/issues/new/choose) to help inform our product team--community feedback via Github issues is a main driver of what features and integrations happen next. As we see changes in the support of PingFederate, or find more collections, articles, or videos that help work with PingFederate, we will update this element.