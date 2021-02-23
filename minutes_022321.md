# Marketplace VC 02/23/21

# Agreed Interfaces
## VC Registration / Issuer-Crawling
- Issuer Metadata (incl. Reputation information)
    - Issuer self-reported infortmation
    - Collected through crawling
    - Attestations about the Issuer from 3rd parties
- VC Type Metadata
    - what it's required for? (provided by Verifier)
    - where can get it? (provided by Issuer)
    - price

## Subject-initiated Issuer-Discovery
- What does the query look like?
- Incl. Issuer-Based Reputation Score

## Reputation
- Reputation for all entities


## Track Credential Issuance (& Payment Coordination)
- Transaction Record (Issuance)

## Track Credential Presentation (& Payment Coordination)
- Transaction Record (Presentation)

## Track Credential Reputation (& Payment Coordination)
- Transaction Record (Reputation)


# Discussion Points

### Reputation

- Should we add Reputation into the Marketplace UC?
- Indepenent of other things all Marketplaces need a standardized interface for issuers to register the Credential Capabilities
- These Capabilities
- Reputation "should be up the Marketplace". E.g. some may use token-based incentive Model. Others might use free market forces ("cheapest"), others might use "traditional web" reputation systems.
- How can an individual query different reputation systems in a standardized way?
- E.g. this group should define a standardized interface to be able to query reputation for a DID?
- 0-100 with the following distribution: normal?
- Marketplace can chose to not expose any reputation score.
- Can Reputation Systems be dynamically integrated into Marketplace implementations (e.g. plugs in external provider.)
- Reputation for Holder/Subject should be out-of-scope.
- Reputation Scope for Marketplace should be limited to Verifier/Issuer.
- For the Holder we might want to have p2p reputation proof
- Can we enable Reputation system with only using VCs but not designing the whole reputation methodology?
- Holder can issue their Reputation VC ad-hoc, compiling from data they already have

### Issuer Metadata

- Issuer Service: put it as a service endpoint in DID. Responsibility of the Issuer to host and maintain this information.
