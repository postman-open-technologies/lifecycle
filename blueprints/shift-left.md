# Shift Left

In the early years of software development, applications were typically programmed and tested by the same people. Over the years, organizations started to add more planning and structure to the way they managed the software development lifecycle, breaking it down into concrete phases so that different steps could be handled by different teams. After following this model for a decade or two, many companies began to realize the cost of having the testing phase so late in the lifecycle, and started to shift testing to the left by integrating it into the earlier phases of development.

## Software Development Lifecycle Evolution

- **Waterfall** - The waterfall model comes from industries such as construction and manufacturing, where the cost of materials is a major consideration. In the 1970s, many organizations started to adopt the waterfall model for their software development lifecycle. In this model, a project is broken down into several phases, and progress flows in one direction. Each phase must be complete before the project can move on to the next phase. The waterfall model phases include defining requirements, analysis, design, coding, testing, and deployment. The different phases can be handled by various teams or roles, including product managers, designers, engineering, quality assurance (QA) testing, and user experience (UX). The waterfall model allows for a small amount of overlap between phases. For example, when QA testers find a defect, the developers go back to the engineering phase to fix the defect before moving on to the next phase. Waterfall became the dominant model for software companies during the 1970s and 1980s, and is still used by many organizations.
- **Shorter cycles** - In the mid-1980s, other software development models began to emerge that organized the work into short cycles. For example, the iterative and incremental development model begins with early planning, and the next phase is a repeatable cycle that includes more detailed planning, defining requirements, analysis, design, development, testing, and evaluation. This iterative cycle continues until the application is ready for deployment. In contrast to the waterfall model, the iterative and incremental model allows testing and evaluation to lead to additional planning. Because this model leaves room for major changes to design and implementation while development work is well underway, it lends itself to working on small, incremental parts of an application, and also allows multiple development teams to work on different parts of the application at the same time.
- **Shifting left** - The software development lifecycle continued to evolve through the 1980s, 1990s, and early 2000s, each time placing more emphasis on testing and user feedback. This trend became known as "shifting left" because it moves testing out of its fixed position near the right side of the process diagram and into the earlier phases on the left side. Using the shift-left testing model, tests are run early and often so that bugs and vulnerabilities are found and resolved faster. The shift-left model is more proactive than earlier models because testing focuses on problem prevention throughout the development process rather than problem detection at the end.

## Shift Left Models

- **Traditional Shift Left**
- **Incremental Shift Left**
- **Agile Shift Left**
- **Model-based Shift Left**

## Why Shift Left?

- **Cost** - Bugs and security vulnerabilities can be expensive to fix. By shifting testing earlier in the development process, testers have more opportunities to identify these issues so that they can be fixed before an application is deployed. Based on a [2020 case study performed by the Ponemon Institute](https://www.ibm.com/account/reg/us-en/signup?formid=urx-46992), a vulnerability costs about $80 to fix during development, while that same vulnerability would cost about $7,600 to fix in production.
- **Speed** - When you include testing in the earlier phases of development, you can identify and resolve issues when they are still small and isolated. By running integration tests, functional tests, and unit tests while development is still in progress, issues can be fixed right away. Developers can use the early feedback from these test results to adapt to changes in requirements or expectations, which saves a significant amount of time compared to making the same changes to a more mature product. Fixing bugs early in the process can also prevent the need for developers to resolve issues in a rush before a product deadline.
- **Automation** - Shifting left can create more opportunities to automate testing. Static code analysis tools, including linters, can check code for programming and style errors without running it, which results in more consistent code. Automated testing leaves less room for human error because the tests are consistent. By integrating automated testing earlier in the CI/CD pipeline, failures appear earlier and can be fixed earlier. When testing is automated, multiple tests can run on the same code at the same time. Automation also requires less time from manual QA testers, which frees them up to work on more valuable tasks. 
- **Security**

## What Can Shift Left

- **API contracts**
- **Design**
- **Testing**
- **Deployment**
- **Security**
- **IT services**

## How to Start Shifting Left

- **High-level testing strategy**
- **Code reviews**
- **Scripted configurations**
- **Monitoring**
- **Collaboration across teams**

## What is Shifting Right?

- **Performance testing**
- **Chaos testing**
- **User experience testing**
- **Blue-green deployment**
- **Security testing**
