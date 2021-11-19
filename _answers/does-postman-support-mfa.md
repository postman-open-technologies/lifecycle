---
name: Does Postman support MFA?
description:  Providing appropriate access to sensitive information, like that offered by APIs, is vital to companies. Multi-factor Authentication (MFA), as part of a single sign-on (SSO) approach, helps ensure authentication is handled correctly. 
...
The larger the company, the more software systems users have to access to do their jobs productively. An email or username and password to access Postman is just one more thing to remember. Further, companies may require multiple authentication factors, beyond a password, for further securing Postman accounts. In those cases, a company should consider implementing a [SSO service](https://apis.how/elements/sso/) across all their SaaS products, including Postman.  

[Postman works with a variety of identity providers (IdP)](https://learning.postman.com/docs/administration/sso/intro-sso/). The IdP can then provide the appropriate [MFA approach](https://apis.how/elements/mfa/) that works across the organization. IdPs include:

- Okta
- OneLogin
- Duo
- Ping Identity
- GSuite

Setting up SSO for SAML 2.0 compliant IdPs can be done by configuring SSO in the Edit Team Page. Additional information about [setting up SSO is available](https://learning.postman.com/docs/administration/sso/admin-sso/). Once SSO is properly configured, please work with the IdP to configure the MFA approach that works best for your organization. 
