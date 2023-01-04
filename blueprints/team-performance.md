## Team Performance 
The performance of teams can be best understood using a platform approach, mixing native platform reporting and capabilities alongside platform-level testing that is observed through a balance of producer and consumer perspectives, helping us establish an awareness of how teams operate. 

### API Producers 
DORA metrics lay our foundation, with two additional human considerations added in to prove a balanced look at how team performance can be measured as part of platform operations. 

- **Deployment Frequency** - How often a version of API is released. 
- **Lead Time for Changes** - How long until new version is in production. 
- **Time to Restore Service** - How long it takes to recover from a problem. 
- **Change Failure Rate** - How often does an API deployment fail. 
- **Satisfaction & Well-Being** - How are your actual team members doing. 
- **Communication & Collaboration** - Are teams working together on APIs. 
 
### API Consumers 
\Onboarding and moving consumers forward with each version in unison is an extremely important aspect of understanding not just performance but the value of forward motion to business. 

- **Time to First Call** - How long for a new consumer to make API request. 
- **Time to Value ** - Time to generating value for producer and consumer. 
- **Time to Upgrade** - How long does it take for consumers to upgrade. 
- **Satisfaction & Awareness** - What is the overall satisfaction of consumers. 
 
### Platform Tests 
Leveraging collections to test the platform for specific states, using the same infrastructure we use to test each instance of our APis, but here we are testing team performance. 

- **Builder** - Test for new API contract version using Postman API. 
- **CI/CD** - Test for successful CI/CD builds using CI/CD API. 
- **Gateways** - Test for new user, API, and versions using gateway API. 
- **Survey** - Test for team satisfaction and well being using survey API. 
- **Message** - Test for new lifecycle activity via team message API. 
 
### Aggregate Data 
Publishing the results of of platform tests to aggregate locations for reporting upon, understanding the state of team performance across domains, APIs, and all development teams. 

- **Source Control** - Publish platform tests results to source control. 
- **Database** - Publish platform tests results to a database. 
- **Data Lake** - Publish platform tests results to the desired data lake. 
- **Application Performance Management (APM)** - Publish platform tests results to an existing APM solution. 
 
### Observability 
Understanding the state of team performance using a mix of approaches that include native enterprise platform reporting, visualizer reports, and using the existing enterprise APM solution. 

- **Platform Reporting** - Team, workspace, API, and security reporting. 
- **Application Performance Management (APM)** - Dashboards via existing APM solutions for observability..
 
 
Like API performance, understanding team performance as part of the API lifecycle requires a mix of metrics, automation, and observability, combined with the ability to run the tests we need and aggregate the data needed to understand exactly what team performance means. 
