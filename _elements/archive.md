---
name: Archive
description: 
  - The archiving of an API that has been deprecated allows for everything used across the life of an API is properly archived and cataloged so that it can be referenced moving forward, utilized to inform future API development, or just provide an accurate record of the past, ensuring that if something needs to be recalled, there is always an archive to look to for satisfying requests. 
links:
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com
    - title: Link Title
      url: http://example.com            
video: ''
screenshots:
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png          
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png  
  - title: Screenshot Description
    url: https://postman-open-technologies.github.io/lifecycle//images/postman-screenshot.png   
...
Once an API has been retired and then reached the date of deprecation it should then be archived instead of deleted. Backing up any artifacts, policies, code, and data behind the API for future reference and even possibly putting back into production if needed. No API should be immediately deleted so that it can be referenced as part of audits and other activity, but from the view of consumers that API should be completely deleted from an servers, gateway, or any other API infrastructure. Ensuring that no deprecated APIs exist in production opening up an vulnerabilities, but deprecated APIs can be retrieved if needed, with a designated aging data that would indeed allow any long deprecated and archived API to be indeed delete when it is definitive that the API is not needed to support operations.
