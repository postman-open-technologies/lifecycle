## Producer - Deploy 
Once an API is ready for deployment to a staging or production environment, there should be a repeatable set of elements at work to move enterprise operations forward at scale. The deployment orchestration of APIs across teams helps optimize the API factory floor across enterprise domains, making every step forward deliberate and repeatable. 

### Elements 
 

- **Source Control** - Use source control to manage code and artifacts used
to deploy an API, providing a single location where you can find everything behind each version, ideally with multiple branches to accommodate many API contributions. 
- **CI/CD Pipeline** - The pipeline ensures that the deployment of an API to each stage is as repeatable as possible, with tests and other essential needs of the API build process making API deployment as repeatable as possible across teams. 
- **Gateways** - Publish contracts, extensions, and other configurations to the API gateway, deploying an API into a staging, then a production environment if all tests pass in the pipeline. This gives you a repeatable way of managing gateways. 
- **Policies** - Require that all APIs be deployed according to a standardized set of plans, with consistent policies, limited access to resources, and proper security controls, ensuring a consistent deployment across all teams. 
- **Releases** - Establish a formal release for each version of an API, documenting the changes being deployed and the communication about them. Keep consumers informed by rolling up all of the branches and changes into a single release. 
- **Stages** - Allow multiple stages to be deployed, providing development, staging, production, and potentially other environments for deploying and testing APIs. That will allow APIs to be reliably deployed into production with the highest possible quality. 
- **Environments** - Apply commonly managed environments, with a coordinated variable strategy for testing and automating configuration as part of the pipeline, helping to abstract away the technical details and secrets of API environments.
 
- **Observability** - Once an API has deployed, what observability do you have over the build process? What about observability of the API once it is available? You need to ensure that you see what is happening during deployment, just as you do for all other stages of the API life cycle. 
 
Deployment means different things to different organizations. What is important is
that there is always a source of truth, a repeatable build process, and a standard set of releases, stages, environments, and plans to deploy APIs consistently across teams and domains.

Like the software development life cycle (SDLC), the API life cycle should be well-defined and repeatable. The big difference is, the API lifecycle should also possess a handful of nuances that help reliably deliver API infrastructure using API gateways, policies, and observability practices. 
