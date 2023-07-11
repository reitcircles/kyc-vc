# kyc-vc
 proper published Schema for all KYC providers so that they can easily implement to provide an SSI compatible Verifiable credential for the Cardano ecosystem.

# KYC standard proposal

## Contextualization of "The Problem" or Why:
The ability to check the legitimacy of personal identifiers
is a crucial component in the chain of trust and risk assessment of many solutions that deal with identities. Know Your Customer (KYC) is the de-facto practice in many mature industries
that require identity validation. Currently, there are many trusted KYC vendors fulfilling this role in the market inside federated and centralized ecosystems. The participation of KYC vendors supporting Self-Sovereign Identities (SSI) is fundamental for the adoption of this technology by mature industries inside decentralized ecosystems.
 Current efforts in this matter lack a unifying standard to define KYC Verifiable Credentials (VC). We believe that the definition of a standard specification schema for KYC interactions will benefit both existing actors that need KYC checks and also help reduce entry barriers for KYC vendors that wish to participate inside the SSI ecosystem, but most importantly, the standard can enable KYC credentials to be reused by the user; improving user experience, reducing KYC costs, saving time, among other benefits.

(1): E.g. birth certificates, passports, driver's license, etc
(2): E.g. banking, real estate, recruitment, insurance, etc

## The "What" or proposed solution:
## A standard specification schema for SSI - KYC interactions that enables reusable VC with a known set of claims.

The "How" are we achieving the solution:
We will initially research KYC vendors across different markets and find common ground in their capabilities and claims, enabling us to define common terminology and create an extensive list of claims.
Then based on the above inputs we will create a KYC VC document standard schema.
Given the standard succeeds and it's widely adopted– KYC vendors that wish to support SSI  will naturally issue the VC directly following the same standard. In both cases the KYC VC can be reused by the user for future interactions.
As an example to support the issuance flow shown in diagram below, we will create an example of creation of a VC (simulating an issuer and using an assumed DID of an issuer on cardano) using the Aries framework.
