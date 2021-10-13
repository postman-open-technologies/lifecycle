---
name: Low Level API Governance
description: A blueprint for approach the governance of APIs beginning with each individual API by individual developers, setting API governance into motion at the lowest level by a single or group of developers, acknowledging that governance will only get you so far at this level, but in many organizations it might sense to start at this level.
conclusion: This blueprint looks at how you can approach API governance as an individual, learning about the building blocks of how governance can be applied when it comes to designing, developing, and operating individual APIs. Each element within this blueprint works to provide a simple overview of what is involved across the entire life of an API, with more detail present on the detail page for each element (if you are viewing this on the API lifecycle project site). If you are reading this via a PDF or printed version you can visit the landing page for this blueprint to access more information and view specific actions you might possibly consider taking as part of applying each element of this proposed lifecycle within your own operations. This blueprint is a living document and will continue to evolve and be added to over time based upon feedback from readers. If you have any questions, feedback, or feel like there is more information you need, feel free to jump on the Github discussion for this blueprint, or any of the individual elements present--the value this blueprint provides is actively defined by the feedback community members like you.
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

  - label: Definition
    description: You can't govern what you don't have define, and to be able to begin governing the design of your APIs you will need to have machine readable artifacts that you can lint as part of the design, develop, or build process. Establishing a set of artifacts that help drive the API lifecycle, but also make it something that can be measured and reported upon as part of governance activities.
    image: images/lifecycle-arrow-define.png
    elements:
      - name: OpenAPI
        label: OpenAPI
      - name: AsyncAPI
        label: AsyncAPI        
  - label: Application
    image: images/lifecycle-arrow-design.png
    description: Once you have an OpenAPI, AsyncAPI, or other artifact that you would like to apply governance too, there are a handful of ways in which you can execute governance as part of your regular work. Depending on your goals with governing the design of an API you can apply each of these elements helping manual or automatically identify problems with the design of your API. These approaches to execution are potentially dependent on other rules, as well as the approach you take to automating the application of governance.
    elements:
      - name: Rules-Based Linting
        label: Rules-Based Linting
      - name: Script-Based Governance
        label: Script-Based Governance               
  - label: Rules
    image: images/lifecycle-arrow-document.png
    description: API governance rules codifies what API governance is as it is applied as part of the design, development and build process on the ground floor of API operations. Rules provide the benchmark for what governance is across teams, and provide an artifact that can be applied across the API lifecycle by individual designers and developers, and eventually baked into the pipelines that move API infrastructure forward. Rules should reflect what is happening on the ground today, but apply enforcement as part of a forward motion, acknowledging that legacy APIs may not always rise to the level governance an organization is moving towards.
    elements:
      - name: Info Governance Rules
        label: Info Governance Rules
      - name: Contact Governance Rules
        label: Contact Governance Rules   
      - name: Versioning Governance Rules
        label: Versioning Governance Rules           
      - name: Path Governance Rules
        label: Path Governance Rules  
      - name: Operations Governance Rules
        label: Operations Governance Rules           
      - name: Parameter Governance Rules
        label: Parameter Governance Rules 
      - name: Request Bodies Governance Rules
        label: Request Bodies Governance Rules   
      - name: Response Governance Rules
        label: Response Governance Rules                            
      - name: Schema Governance Rules
        label: Schema Governance Rules    
      - name: Tags Governance Rules
        label: Tags Governance Rules                                                                 
  - label: Automation
    image: images/lifecycle-arrow-test.png
    description: To realize governance across operations it is important that governance is applied in automated ways at different areas of the API lifecycle, helping ensure API governance can be applied early on in the lifecycle, but is also available throughout the development and delivery of aPIs, and when it makes sense bake it into the build process ensuring that governance is applied by default as every API moves into production. Helping ensure that teams aren't doing extra work to realize governance across operations, and it is just at their fingertips as they are design, developing, and building APIs as part of their regular day.
    elements:
      - name: Design Time Governance
        label: Design Time Governance
      - name: Collection Governance
        label: Collection Governance 
      - name: CLI Governance
        label: CLI Governance  
      - name: IDE Governance
        label: IDE Governance 
      - name: Pipeline Governance
        label: Pipeline Governance
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
discussion: https://github.com/postman-open-technologies/lifecycle/discussions/44
yaml: https://github.com/postman-open-technologies/lifecycle/blob/main/_blueprints/low-level-governance.md
...
Governance is best developed from the top town, establishing common processes, rules, and guidance that reflect the architectural and business interests of leadership, but governance is realized at the lowest levels on the ground floor of operations, and it also makes sense in many organizations to set in motion some low-level governance patterns while higher level governance is being established. This blueprint is meant to walk through how your average API developer might approach governance as part of their regular work, helping them design and deliver more consistence APIs as part of a more high level governance approach or in absence of a more high level governance approach. Helping API teams learn how to step back and look at how they can define what a good API is and then deliver on that vision consistently as part of a high velocity release schedule. Setting the stage for a low level approach to implementing API governance that can work in alignment with higher level strategy, or begin moving the API governance from the bottom up.
