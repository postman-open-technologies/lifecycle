## Testing Landscape 
This is a blueprint attempting to capture the 500K view of API testing to help show the entire landscape. 

### Doorway to Testing 
Testing means different things to different people, but these three dimensions are the common doors people walk in through. 

- **Kicking the Tires** - Testing an API to understand what it does and how it works for consumer. 
- **Prototyping** - Mocking an example of an API test out an idea that you have for an API solution. 
- **Formal** - Testing an instance of an API to ensure it is operating as expected by producer and consumer. 
The kicking the tires and prototyping cover much of the landscape, with more formal testing being where the rubber meets the road. 
### Essential Testing 
These are the areas that every API should have testing. Of course, there are additional areas to consider, but this is a good place to start. 

- **Contract Testing** - Deriving specific business contracts for an API and testing them out. 
- **Performance Testing** - Overlapping with load testing, but benchmarking the API performance. 
- **Uptime Testing** - Doing the bases and making sure an API is up or down and reporting on it. 
- **Security Testing** - A broad umbrella for testing the layers of API security that is present. 
Once you have a baseline set here, then you can consider looking add the aditional dimensions of testing each API across environments. 
### Additional Testing 
This is a mix of the different ways that testing service providers and practitioners describe the types of tests they are applying to APIs. 

- **Functional Testing ** - Adopted as part of code testing practices, applied to unit of code. 
- **Unit Testing** - The process of confirming that a single endpoint returns the correct response to a given request.  
- **Component Testing** - Similar to functional, but testing based upon small unit of compute. 
- **User Interface Testing ** - Testing of the API in the context of the end user interface. 
- **Load Testing** - Seeing how many requests each API is able to handle in a timeframe. 
- **Reliability Testing** - Understanding the overall reliability of each individual API. 
- **Runtime Error Detection** - Focusing specifically on errors encountered at runtime. 
- **Authorization Testing** - Focused on testing the authentication for each individual API. 
- **Penetration Testing** - Seeing you can actually get into an API through alternate ways. 
- **Fuzz Testing** - Blasting an API with garbage, noise, and other junk to see what it does. 
- **Interoperability Testing** - Testing how well an API plays with other external APIs. 
- **Integration Testing** - Testing an API based upon its dependency on external APIs. 
- **Behavioral Testing ** - Driving testing based upon external views of what is expected of the API. 
- **Acceptance Tests** - Tested defined by the consumer based upon what is meaningful to them. 
- **End-to-End Testing** - Testing the entire API stack from backend to front, and back again. 
- **Omni-Channel Tests** -  Testing out multiple channels of consumption like web, mobile, and devices. 
This should probably be rendered as a sort of Venn Diagram of tests, providing some contours to how some of these areas overlap. 
### Use Case Testing 
Next, let's get focused on specific business outcomes with a mix of testing that stitches many API calls together into a single Flow. 

- **Data-Driven Testing** - Relying on data to define and drive the testing of each API. 
- **Scenario Testing** - Building tests that reflect specific business scenarios that are relied upon. 
- **Workflow Testing** - Another way to define a test for a series of API calls that reflect a business need. 
These tests can be applied across many internal and external APIs, modeling common business practices and then applying tests. 
### Governance “Testing” 
With governance, we are testing the surface area of an API instead of the instance of an API, linting and testing the contract and configuration of an API. 

- **Design Testing** - Testing the surface area of an API for specific patterns that should exist. 
- **Documentation Testing** - Testing the documentation for an API to make sure it is complete. 
- **Testing Testing** - Testing that specific types of tests exists for each API in production. 
- **Gateway Testing** - Testing the gateway to ensure each API is properly deployed and managed. 
- **Workspace Testing** - Testing the workspace where an API is managed for specific elements. 
Governance spans multiple stages of the API lifecycle, helping test the operations surrounding each API to ensure everything is operating as desired. 
### Contracts 
Machine-readable artifacts and contracts help provide more structure and repeatability across different areas of testing, helping standardize and stabilize tests. 

- **OpenAPI** - Utilizing an OpenAPI as the source of truth, or contract of what an API does. 
- **AsyncAPI** - Utilizing an AsyncAPI as the source of truth, or contract of what an API does. 
- **JSON Schema** - Using JSON Schema to model and validate the shape of objects. 
- **Collections** - Utilizing an collection as the source of truth, or contract of what an API does. 
It is common for one or more of these contracts to be used as the source of truth behind a mix of tests, describing the surface area of an API. 
### Management 
More APIs means more API tests, and having a strategy for how you will manage your tests, execute them, and evolve is essential to achieving the desired outcomes. 

- **Maintainable** - Ensuring that your tests are easily maintained throughout their use. 
- **Modular** - Keeping your tests as modular as possible so they are individual applicable. 
- **Reusable** - Working to make test scripts as reusable as possible across APIs by teams. 
- **Organized** - Organizing tests into folders so that they are logically structured for use. 
- **Owned** - There is always an owner for a test, making sure there is someone who cares. 
- **Documented** - Make sure that tests are well documented so their use is easy to follow. 
- **Lifecycle** - Allow tests to be manually run or automated at any stage of the API Lifecycle. 
- **Dependencies** - Always definite the dependencies that exist for each test being executed. 
A little bit of guidance here goes a long way, helping establish a common language for the management of quality across teams and the APIs they own. 
### Automation 
Test automation is essential to scaling to meet the quality demands of API infrastructure today, with a handful of proven ways to automate all of your tests using a single platform. 

- **Runners** - Execute tests manually using runners to apply testing to each individual API. 
- **Monitors** - Schedule tests to be run across any region to properly automate testing. 
- **CI/CD** - Embed relevant tests into CI/CD pipelines to automate testing into the build process. 
Collections combined with environments provide the machine-readable and executable unit of test needed to automate quality on a schedule or as part of the build process. 
### Execution 
Tests are applied across multiple environments, requiring artifacts and definitions of how each API progresses as part of development. 

- **Environments** - Having each of your environments defined for reuse across APIs. 
- **Stages** - Applying tests to a specific stage of an API being developed and delivered. 
Environments regulate where you are executing your tests, making switching between development, staging, and produce environments easy. 
### Scopes 
This testing landscape covers three distinct scopes of an API, going well beyond what just looking at each instance and better understanding API operations at scale. 

- **Instance** - Testing the request and response of a specific API instance. 
- **Surface** - Testing the design and surface area of each individual API. 
- **Operations** - Testing the operations that exist around all APIs. 
All three of these scopes drive API governance, but they also reflect what is needed to scale API operations consistently, taking testing to the next level(s). 
This blueprint will be reduced into other smaller more precise blueprints focusing on specific areas. 
