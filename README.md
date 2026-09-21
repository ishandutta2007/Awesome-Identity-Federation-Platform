# Awesome-Identity-Federation-Platform

## Top Identity Federation Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on SSO, Federation, SAML/OIDC, Identity Brokering, Workforce & Customer Identity*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Identity Federation**. These systems enable single sign-on (SSO), federate identities across applications and organizations, support SAML, OpenID Connect, and OAuth, and act as identity providers or brokers for workforce and customer use cases.



**Examples** include Ping Identity, Okta, Microsoft Entra ID, Auth0, Keycloak, ForgeRock, OneLogin, IBM Security Verify, WSO2 Identity Server, and Oracle Identity Cloud (the category leaders).



**Open-source emphasis**: Identity federation has excellent open-source options. **Keycloak** (CNCF), **Authentik**, **Ory**, and **WSO2 Identity Server** provide production-grade SSO, federation, and identity management. Commercial platforms still lead in pre-built app catalogs, support, and global scale. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Ping Identity](https://www.pingidentity.com/)**  

  Enterprise identity platform offering SSO, federation, access management, and customer identity solutions for complex hybrid environments.



- **[Okta](https://www.okta.com/)**  

  Leading cloud identity platform for workforce and customer identity, with extensive application integrations, SSO, MFA, and lifecycle management.



- **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  

  Microsoft’s cloud identity and access management service (formerly Azure AD) providing SSO, federation, conditional access, and directory services.



- **[Auth0 (Okta Customer Identity)](https://auth0.com/)**  

  Developer-focused identity platform for customer-facing applications, supporting social login, passwordless, and extensible authentication flows.



- **[Keycloak (Red Hat build / enterprise support)](https://www.keycloak.org/)**  

  Open-source identity and access management solution widely deployed for SSO and federation; enterprise support available via Red Hat and partners.



- **[ForgeRock (Ping Identity portfolio)](https://www.pingidentity.com/)**  

  Enterprise identity platform historically strong in large-scale CIAM and workforce identity; now part of the broader Ping ecosystem.



- **[OneLogin (One Identity)](https://www.onelogin.com/)**  

  Cloud IAM platform providing SSO, MFA, and directory integration for workforce identity.



- **[IBM Security Verify](https://www.ibm.com/products/verify-identity)**  

  IBM’s identity and access management offerings for workforce and consumer identity, including federation and risk-based access.



- **[WSO2 Identity Server (enterprise options)](https://wso2.com/identity-server/)**  

  Open-source and commercial identity and access management platform supporting SSO, federation, and API security.



- **[Oracle Identity Cloud Service / OCI IAM](https://www.oracle.com/security/identity-management/)**  

  Oracle’s cloud identity services for SSO, federation, and identity lifecycle across Oracle and third-party applications.



## Open-Source GitHub Projects

- **[Keycloak](https://github.com/keycloak/keycloak)**  

  Leading open-source identity and access management solution (CNCF) supporting SSO, identity brokering, user federation (LDAP/AD), SAML, OIDC, and fine-grained authorization.



- **[Authentik](https://github.com/goauthentik/authentik)**  

  Modern open-source identity provider with visual auth flows, SAML, OIDC, LDAP, RADIUS, application proxy, and a strong self-hosted focus.



- **[Ory (Kratos, Hydra, Keto, Oathkeeper)](https://github.com/ory)**  

  Cloud-native open-source identity stack: user management (Kratos), OAuth2/OIDC (Hydra), permissions (Keto), and zero-trust proxy (Oathkeeper).



- **[WSO2 Identity Server](https://github.com/wso2/product-is)**  

  Full-featured open-source IAM platform supporting SSO, federation, adaptive authentication, and API security.



- **[FreeIPA](https://www.freeipa.org/)**  

  Open-source integrated identity management combining Linux, Kerberos, DNS, and certificate services—strong for Unix/Linux environments.



- **[LemonLDAP::NG](https://lemonldap-ng.org/)**  

  Open-source WebSSO and access management solution supporting SAML, OIDC, CAS, and reverse-proxy based federation.



- **[Authelia](https://github.com/authelia/authelia)**  

  Open-source authentication and authorization server providing 2FA and single sign-on for applications via reverse proxy.



- **[Gluu / Janssen Project](https://github.com/JanssenProject)**  

  Open-source digital identity platform focused on large-scale IAM and federation (evolution of Gluu Server).



- **[Casdoor](https://github.com/casdoor/casdoor)**  

  Open-source UI-first Identity and Access Management (IAM) / Single-Sign-On (SSO) platform with web UI and multi-language support.



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  Open-source identity infrastructure with a focus on modern APIs, multi-tenancy, and cloud-native deployment.



### Additional Strong Open-Source Options

- Deploying **Keycloak** as the default open-source choice for enterprise SSO and federation.

- Choosing **Authentik** for a modern UI, visual flows, and broader built-in protocol set.

- Using **Ory** when a headless, API-first, cloud-native identity architecture is preferred.

- Combining open IdPs with commercial directories (Okta, Entra) as brokers or upstream sources.

- Accepting that the largest pre-built SaaS app catalogs, global support, and turnkey compliance packages still favor commercial platforms (Okta, Entra ID, Ping, Auth0, etc.).

- Focusing open-source efforts on data sovereignty, air-gapped deployments, and freedom from per-user pricing.



**Frameworks for building custom systems**: Deploy Keycloak or Authentik → federate LDAP/AD and external IdPs → protect apps via SAML/OIDC → add MFA and adaptive policies → integrate with existing directories. Suitable for organizations with platform/ops capacity. Many enterprises still standardize on commercial IdPs for workforce SSO breadth and support while using open source for customer identity or specialized environments.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Identity systems are security-critical. Open-source deployments require hardened configuration, regular patching, secure secrets management, and proper high-availability design. Misconfiguration can lead to serious breaches. This list is not security or compliance advice.



---

**Made for identity architects, security engineers, and platform teams implementing SSO and federation.**

Let's keep identity secure, standards-based, and as open as practical.
