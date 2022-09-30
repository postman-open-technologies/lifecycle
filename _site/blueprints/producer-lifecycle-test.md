# Test
Defining, documenting, and automating the testing of the underlying contract for each API, understanding the overall performance of the API, integration, and other types of tests. Providing supporting automation to properly test the entire surface area of each API, as well as the operations.

## Artifacts

- **Collections - Using collections to define one or a sequence of many API requests, establishing a modular, collaborative, and executable artifact used across API testing.
- **Scripts - Defining folder level, pre-request, or post-request scripts that run to configure request, validate responses, and automate testing to iterate and behave as consumers.

## Types

- **Contract - Using OpenAPI and AsyncAPI contracts to ensure 100% of the surface area of an API is being tested and behavior reflects the contract between producer and consumer.
- **Performance - Testing specific paths for each API to understand the performance of an API, gateway, and network from multiple regions to ensure the desired performance exists.

## Use Cases

- **Mocking - Leverage mock servers generated from the API contract, but then augmenting with examples for specific use cases, testing for specific outcomes.
- **Data - Injecting CSV or JSON data as part of the testing process making sure API requests reflect specific business workflows and outcomes, testing real-world API-driven scenarios.

## Automation

- **Monitor - Scheduling monitors of tests to run on a schedule that reflects the business needs of the API, but also the type of test being run, allowing testing to be automated by teams.
- **CI/CD Pipeline - Baking tests into CI/CD pipelines, ensuring that all tests run when APIs are being built, ensuring that no API goes into production with the tests being executed.

