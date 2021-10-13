---
name: High Level API Governance
description: A blueprint for approach the governance of APIs from the top down, establishing a higher level strategy for defining what governance is, and then helping spread guidance across teams that helps enable them to deliver more consistent APIs across a more consistent API lifecycle no matter what type of API they are delivering.
conclusion: This blueprint looks at how you can approach API governance as an organization, establishing high level strategy and practices that can be used to direct governance efforts across teams. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
image: governance.png
tags:
  - OpenAPI
  - Governance
stage: Governance
type: sync
order: 1
maturity: draft
version: 2021-09-12
areas:  

  - label: Define
    description: 
    image: images/lifecycle-arrow-define.png
    description: API governance needs to be well defined, beginning with defining the overall API lifecycle, which this project is dedicated to doing, and the establishment of a formal strategy. Without properly defining of what governance is, and how it will be applied across the API lifecycle, it will never be realized. To establish API governance at the highest levels within an organization you need a well defined view of what is happening today across operations, and coherent articulation of where we should be going. This definition will not every e complete, but more of an ongoing journey for an organization to define itself.
    elements: 
      - name: API Lifecycle
        label: API Lifecycle    
      - name: Governance Strategy
        label: Governance Strategy
  - label: Organization
    image: images/lifecycle-arrow-design.png
    description: The structure and leadership of governance will need to be established for API governance to move forward at the highest levels, otherwise it will just be a low-level vision that a handful of teams are able to realize. The organization of governance needs to reflect the organization where it is being applied in order to have greatest impact. To do this, you have to invest resources, time, and people to helping organize, lead, and guide teams in learning about, understanding, applying, reporting, and providing feedback on what is working and what is not working when it comes to governance.
    elements:
      - name: Governance Structure
        label: Governance Structure
      - name: Governance Leadership
        label: Governance Leadership    
      - name: Governance Guidelines
        label: Governance Guidelines                     
  - label: Rules
    image: images/lifecycle-arrow-document.png
    description: API governance rules codifies what API governance is as it is applied as part of the design, development and build process on the ground floor of API operations. Rules provide the benchmark for what governance is across teams, and provide an artifact that can be applied across the API lifecycle by individual designers and developers, and eventually baked into the pipelines that move API infrastructure forward. Rules should reflect what is happening on the ground today, but apply enforcement as part of a forward motion, acknowledging that legacy APIs may not always rise to the level governance an organization is moving towards.
    elements:
      - name: Design Rules
        label: Design Rules
      - name: Documentation Rules
        label: Documentation Rules     
      - name: Management Rules
        label: Management Rules              
      - name: Testing Rules
        label: Testing Rules                          
  - label: Reporting
    image: images/lifecycle-arrow-monitor.png
    description: Reporting on the realities and outcomes of API governance across the API lifecycle is needed to make it more visual and tangible for everyone involved. Reporting across governance being applied to individual APIs, groups of APIs, and overall operations can be realized as part of native platform reporting, customized, localized or in aggregate with Postman Visualizer, or made seamless with existing operations by piping data into APM and other systems to make available for reporting and visualizations via dashboards.
    elements:
      - name: Reports
        label: Reports
      - name: Visualizer
        label: Visualizer  
      - name: Application Performance Management (APM)  
        label: Application Performance Management (APM)                                            
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/45
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/low-level-governance.md
...
A standardized API lifecycle can be applied to the design, development, and usage of API business workflows that are defined as machine readable collections which can be automated using monitors and CI/CD pipelines. Postman collections provide a versatile approach to defining multiple individual API requests that include authentication, parameters, headers, and other details, then organize into folders and specific sequences. Providing a format for defining, documenting, but then also executing common business workflows across many internal, partner, or external APIs. Something becomes endlessly useful when managed as part of a well defined lifecycle, equipping developers with what they need to define and design the workflows, but also maintain them, execute them, and use them to automate a variety of business tasks that exist in their worlds.
