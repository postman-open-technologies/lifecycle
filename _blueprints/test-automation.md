---
name: Test Automation
description: Test automation is essential for delivering reliable and consistent APIs at scale across the enterprise. This is a blueprint for walking through the base of how test automation can work as part of a well defined API lifecycle, helping teams standardize how they approach testing APIs.
conclusion: This blueprint is meant to provide a standardized approach to automating the testing of APIs across operations as part of a standardized API lifecycle. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: test-automation.png
tags:
  - OpenAPI
  - Design-First
stage: Automation
type: sync
order: 1
maturity: stable
version: 2021-09-11
areas:  
   
  - label: Test
    image: images/lifecycle-arrow-test.png
    description: A test-driven API lifecycle ensures that each API accomplishes the intended purpose it was developed for, providing manual and automated ways to ensure an API hasn't changed unexpectedly, is as performant as required, and meets the security expectations of everyone involved, helping establish a high quality of service consistently across all APIs.
    elements:
      - name: Contract Testing
        label: Contract Testing        
  - label: Monitor
    image: images/lifecycle-arrow-monitor.png
    description: All tests applied to an API should be monitored on a logical schedule and from relevant geographic regions, monitoring that APIs aren't breaking their contract, falling below their agreed upon service level agreement (SLA), or becoming a security risk, helping automate the quality of service across APIs in a way that allows teams to be as productive as possible.
    elements:
      - name: Monitor
        label: Monitor
      - name: Contract Testing Monitor
        label: Contract Testing Monitor  
      - name: Contract Testing Monitor Results
        label: Contract Testing Monitor Results   
  - label: Deploy
    image: images/lifecycle-arrow-deploy.png
    description: Tests can be automated using a CI/CD pipeline, allowing for test to be executed every time a commit or pull request is made against a repo. Allowing tests to be run against any instance of an API, ensuring that any API being deployed has not broken it's contract, and the API does what is expected.
    elements:
      - name: CI/CD Pipeline
        label: CI/CD Pipeline
        context: 1  
      - name: Newman
        label: Newman
        context: 1                                                
  - label: Observability
    image: images/lifecycle-arrow-observability.png
    description: Tapping into the outputs available across API operations to understand what is happening with individual APIs throughout their lifecycle, but also in aggregate for domains, teams, and other logical groups, helping make API operations more visible in real time.
    elements:   
      - name: Contract Testing Monitor Report
        label: Contract Testing Monitor Report           
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/33
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/test-automation.md
...
This blueprint focuses just on the test automation portion of the API lifecycle, highlighting the different types of tests that can be run, how monitors can be used to automate those tests on a schedule from multiple regions, and then how to tap into the observability opportunities that exist when it comes to test automation. Test automation should provide you with a 50K foot view of how testing works in conjunction with monitors, and what observability is available by default, published using visualizer, or introduced through integrations with external solutions, providing many different ways of being able to see and understand test automation for API operations.