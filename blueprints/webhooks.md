## Webhooks 
API requests trigger some sort of event in a system adding or updating data. Webhooks do the reverse, making a call to any URL when one of these events occurs. A webhook is the trigger that results when different types of API requests or message publishing occurs, which can set in motion any other API-driven action, making operations more event-driven. 

### Elements 
 

- **URL** - Each webhook has a URL property, allowing it to have the address of the resulting call that should be made when each event is triggered, automating any workflow. 
- **Payload** - A payload provides data to send with each event triggered, sending static or dynamic data to the URL for each webhook and adding more context to the event. 
- **Events** - Events provide a meaningful name and description of each moment triggered when an API call is made.
 
- **Emails** - It is common to allow emails to be sent to one or many addresses when an event is triggered, adding another layer of system or human messaging. 
- **Logging** - Like other API infrastructure, the logging of webhook calls is a common part of system operation, providing a record of every webhook transaction that occurs. 
- **Notifications** - For some events, there may be an additional need to send a notification using another API, or some native application mechanism. 
- **Retry** - Not all webhooks will execute successfully, so it is common to build in the ability to retry one or many times, allowing outcomes to be eventually realized. 
 
Webhooks are one of the most useful but overlooked and underutilized tools in the toolbox. They are the poor man’s event-driven architecture. Like APIs, webhooks use simple, low-cost web infrastructure, but they use it to help make APIs more resilient and event-driven.
The most common way webhooks are used is as a relief valve for API producers when API consumers poll an API too many times. A webhook tells API consumers to stop requesting an API when looking for new or updated information, indicating we’ll tell you when something changes or when a specific event occurs.
Webhooks can make operations much closer to real-time with very few additional resources and skills required. With proper management tools and analytics, API providers can significantly improve the overall efficiency of their API operations. 
