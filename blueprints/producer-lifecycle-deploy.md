## Deploy
Once an API is ready for deployment to a staging or production environment, there should be a repeatable set of elements at work to move enterprise operations forward at scale. The deployment orchestration of APIs across teams help optimize the API factory floor across enterprise domains, making every step forward more deliberate and repeatable.

- **Source Control** - Using source control to manage code and artifacts used to deploy an API, providing a single location to find everything behind each version of an API.
- **CI/CD Pipeline** - The pipeline ensures that the deployment of an API to each stage is as repeatable as possible, with tests  and other essential needs of the PI build process.
- **Gateway** - Publishing contracts, policies, and other configurations to the API gateway, deploying an API into a staging or production enviironment if all tests pass in the pipeline.
- **Releases** - Establishing a formal release for this version of an API, documenting the changes being deployed, and communication around it, keeping consumers informed.
- **Stages** - Allowing for multiple stages to be deployed, providing development, staging, production, and potentially other environments for deploying and testing APIs within.
- **Environments -Applying commonly managed environments, with a coordinated variable strategy, applying when testing and automating configuration as part of the pipeline.
- **Plans** - Requiring that all APIs be deployed into a standardized set of plans, with consistent policies applied, limiting access to resources, and applying proper security.

Deployment will mean different things to different organizations, what is important is that there is always a source of truth, a repeatable build process, and a standards set of releases, stages, environments, and plans are leveraged to deploy APIs consistently across teams and domains.
