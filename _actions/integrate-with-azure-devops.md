---
name: Integrate with Azure DevOps
description: Azure DevOps Server is a Microsoft product that provides version control, reporting, requirements management, project management, automated builds, testing and release management capabilities.
links:
    - title: Azure DevOps
      url: https://azure.microsoft.com/en-us/services/devops/
    - title: Workspace
      url: https://api-evangelist.postman.co/workspace/Azure-DevOps~261535e3-3f7c-4373-b04d-96704545a682/overview
    - title: Collections
      url: https://github.com/hkamel/azuredevops-postman-collections           
video: ''
tools:
    - title: Open Source Tool
      description: This is a description of this open source tool, and how it helps.
      url: http://example.com
    - title: Open Source Tool
      description: This is a description of this open source tool, and how it helps.
      url: http://example.com
    - title: Open Source Tool
      description: This is a description of this open source tool, and how it helps.
      url: http://example.com        
issue: https://github.com/postman-open-technologies/lifecycle/issues/52
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_actions/integrate-with-azure-devops.md
...
Azure DevOps Server (formerly Team Foundation Server (TFS) and Visual Studio Team System (VSTS)) is a Microsoft product that provides version control (either with Team Foundation Version Control (TFVC) or Git), reporting, requirements management, project management (for both agile software development and waterfall teams), automated builds, testing and release management capabilities. It covers the entire application lifecycle, and enables DevOps capabilities. Azure DevOps can be used as a back-end to numerous integrated development environments (IDEs) but is tailored for Microsoft Visual Studio and Eclipse on all platforms.

Postman does not have a direct integration for Azure DevOps or any of it's sub-systems currently, but there are other options for connecting with Azure DevOps as part of your operations until there is a first-class integration as part of the Postman platform. Here is what is currently available to support Azure DevOps on the Postman platform:

- [Public Workspace](https://api-evangelist.postman.co/workspace/Azure-DevOps~261535e3-3f7c-4373-b04d-96704545a682/overview) - We have created an unofficial workspace where you can find an OpenAPI and collections for Azure DevOps as well as Visual Studio related APIs. These collections can be used to integrate and automate using the Azure and Visual Studio APIs, providing a variety of ways to put Azure DevOps to work via the Postman platform.
- [Azure DevOps Collections](https://github.com/hkamel/azuredevops-postman-collections) - An additional set of existing Postman collections for working with Azure DevOps.

A while back we did some research into how folks are using Azure Devops in conjunction with the Postman platform and published this story:

- [Three Ways to Use Postman and Azure DevOps](https://apievangelist.com/2020/01/22/three-ways-to-use-postman-and-azure-devops/)

Additionally, we found this two part series on conducting testing with Postman and Azure DevOps to be very useful:

- [Integration Test with Postman in Azure DevOps Pipeline: Part 1](https://dev.to/kenakamu/integration-test-with-postman-in-azure-devops-pipeline-part-1-2h5j)
- [Integration Test with Postman in Azure DevOps Pipeline: Part 2](https://dev.to/kenakamu/integration-test-with-postman-in-azure-devops-pipeline-part-2-nfk)

There are [multiple Github Issue submitted requesting an Azure DevOps integration with Postman](https://github.com/postmanlabs/postman-app-support/issues?q=is%3Aissue+is%3Aopen+azure+devops). We recommend you find the existing issue that closely matches what you are looking for and vote up, comment, and make it known you are interested in tighter integration. Our engineering team uses these issues to guide the road map, and without your submission it might now happen. As we see changes in the support of Azure DevOps, or find more collections, articles, or videos that help work with Azure DevOps, we will update this element.