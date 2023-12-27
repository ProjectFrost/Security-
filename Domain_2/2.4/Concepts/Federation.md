Federation in authentication involves centralized trust for secure access. Key concepts include:

1. **Single Sign-On ([[SSO]]):**
    
    - Users authenticate once and gain access to multiple connected systems without re-entering credentials.
2. **Identity Providers ([[IdP|IdPs]]):**
    
    - Centralized entities managing user identities and authentication, providing tokens to access various services.
3. **Service Providers ([[SP|SPs|]]):**
    
    - Systems relying on an identity provider for authentication, trusting assertions or tokens from the IdP.
4. **[[SAML]] (Security Assertion Markup Language):**
    
    - Protocol enabling the exchange of authentication and authorization data between parties, often used in federation.
5. **[[OAuth]] (Open Authorization):**
    
    - Framework facilitating delegated access, allowing third-party services to access resources on behalf of a user.
6. **[[OpenID Connect]]:**
    
    - Authentication layer built on top of OAuth, providing identity information in the form of JSON Web Tokens (JWT).
7. **Trust Relationships:**
    
    - Agreements and configurations establishing trust between identity providers and service providers.
8. **Attribute Mapping:**
    
    - Defining how user attributes from the identity provider are mapped and used by service providers.
9. **Federation Standards:**
    
    - Adherence to industry standards ensures interoperability, with SAML and OAuth being commonly used standards.
10. **Cross-Domain Authentication:**
    
    - Extending authentication across different domains or organizations, allowing seamless access to shared resources.

Understanding these concepts is vital for implementing secure and efficient federated authentication, enabling users to access diverse services with a single set of credentials.