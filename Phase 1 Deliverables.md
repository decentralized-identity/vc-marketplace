## Goals

1. Create 5+ relatable use cases that demonstrate need in the VC Marketplace specification and high-level user journeys
    - Employment - Finance
    - Education - HR
    - AML
    - Healthcare - Travel
    - and others
2. Propose solutions for the following design questions

    **Verifier**

    - How to discover what credential types are available in the ecosystem?
    - Trust registry (verifiable data registry*?*)
        - How can I trust that this issuer is a particular organization? (KYI)
        - How do I trust they DID / public key?
        - How do I trust that they are allowed to issue particular VC types?
    - How do I verify if credentials are not revoked (across many revocation mechanisms)?
    - How do I direct holders to the right issuers (if they are missing creds)?
    - How can I anonymously poll holders for specific VC types? How can I do this publicly (if communication is not initiated by the holder)?

    **Issuer**

    - How to communicate business and technical credential requirements to prospective holders?
    - What Regulation does the Credential need to adhere to?

    **Holder**

    - How to discover parties that accept credentials of the types that I have?
    - Where can I use these credentials to avail services?
    - Where can I acquire credentials to get access to specific service?

    **Ecosystem**

    - How to ensure that Marketplace is decentralized / does not create vendor lock-in?
    - How build a system that will incentivize issuers / supply side?
    - How all of the above works while preserving privacy and data protection regulation?

### 01.26 Notes

- Align with Credential Manifest group
- As a holder, how do I discover list of know issuers?
- Can we come up with the syntax of describing services and issuers?
    - It's OK to start centralized
    - Interfaces should be standardized (PE, CM, data registry)
- Adoption vs. Decentralization
    - It's important on what level the decentralization is happening? Having decentralization higher up results in poorer UX.
    - Example: Blockstack. Fully integrated ⇒ impairs developers
    - Standardised data model but customized UX layer
- Starting points for the VCM work:
    - CM, DID interop work, did:web
- What are the group short-term deliverables?
    - **Architecture**
    - **Use Cases**
    - **List of pain points per persona**

## Proposed High-level schema

![https://github.com/decentralized-identity/vc-marketplace/blob/d2c2014e508d9bcf86120c3efdf94762edb2d905/VC%20Marketplace%20Design%20-%20User%20Stories%20(1).jpg?raw=true](https://github.com/decentralized-identity/vc-marketplace/blob/d2c2014e508d9bcf86120c3efdf94762edb2d905/VC%20Marketplace%20Design%20-%20User%20Stories%20(1).jpg?raw=true)
