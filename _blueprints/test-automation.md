---
name: Test Automation
description: A blueprint for understanding the different aspects of API test automation.
image: test-automation.png
tags:
  - OpenAPI
  - Design-First
stage: Automation
type: sync
order: 1
maturity: draft
areas:  
   
  - label: Test
    image: images/lifecycle-arrow-test.png
    description: A test-driven API lifecycle ensures that each API accomplishes the intended purpose it was developed for, providing manual and automated ways to ensure an API hasn't changed unexpectedly, is as performant as required, and meets the security expectations of everyone involved, helping establish a high quality of service consistently across all APIs.
    elements:
      - name: Contract Testing
        label: Contract Testing   
      - name: Performance Testing
        label: Performance Testing       
      - name: Uptime Testing
        label: Uptime Testing       
      - name: Integration Testing
        label: Integration Testing      
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
      - name: Performance Testing Monitor
        label: Performance Testing Monitor  
      - name: Performance Testing Monitor Results   
        label: Performance Testing Monitor Results                             
      - name: Integration Testing Monitor
        label: Integration Testing Monitor   
      - name: Integration Testing Monitor Results
        label: Integration Testing Monitor Results   
      - name: Uptime Testing Monitor Results
        label: Uptime Testing Monitor Results                           
  - label: Observability
    image: images/lifecycle-arrow-observability.png
    description: Tapping into the outputs available across API operations to understand what is happening with individual APIs throughout their lifecycle, but also in aggregate for domains, teams, and other logical groups, helping make API operations more visible in real time.
    elements:
      - name: Activity
        label: Activity 
      - name: Reports
        label: Reports
      - name: Change Log
        label: Change Log      
      - name: Uptime Monitor Report
        label: Uptime Monitor Report   
      - name: Contract Testing Monitor Report
        label: Contract Testing Monitor Report    
      - name: Performance Monitor Report
        label: Performance Monitor Report   
      - name: Integration Monitor Report
        label: Integration Monitor Report           
      - name: Application Performance Management (APM)  
        label: Application Performance Management (APM)          
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/33
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/test-automation.md
...
This blueprint focuses just on the test automation portion of the API lifecycle, highlighting the different types of tests that can be run, how monitors can be used to automate those tests on a schedule from multiple regions, and then how to tap into the observability opportunities that exist when it comes to test automation. Test automation should provide you with a 50K foot view of how testing works in conjunction with monitors, and what observability is available by default, published using visualizer, or introduced through integrations with external solutions, providing many different ways of being able to see and understand test automation for API operations.