# POPregister


## Proof of Property Electoral Register

POPregister is a fully decentralized, permissionless, blockchain-based electoral register built on the Rootstock blockchain using smart contracts.

It allows anyone to self-register to vote by locking real digital property (rBTC) which can be obtained by exchanging Bitcoin 1:1 for rBTC and binding the locked funds to a single physical Solokey/SoloSeed authentication key.

There are:

- No administrators
- No identity databases
- No revocation powers
- No recovery systems
- No institutional gatekeepers

Only:
Code. Digital property. And a physical cryptographic key.



## Core Principle

«One Key. One Vote. One Election.»

- If you control the property → you can register.
- If you control the Solokey → you can vote.
- If you lose the key → you lose the vote.
- If your funds are locked → they stay locked until expiry.
- No one can override the rules.



## What POPregister Is

POPregister is not a voting system.

It is the public electoral roll that voting systems rely on.

It answers only one question:

«“Who is cryptographically eligible to vote in this election?”»

It does this by recording:

- A provable lock of real digital property (rBTC)
- A provable binding to a physical Solokey
- A provable time window of validity
- A provable election scope

All of this is enforced directly by Rootstock smart contracts.



## What POPregister Is Not

POPregister is not:

- A KYC system
- A digital ID system
- A biometric system
- A government registry
- A custodial service
- A recovery service
- A revocation authority
- A permissioned platform

It does not store:

- Names
- Addresses
- Phone numbers
- Passports
- National IDs
- Faces
- Biometrics

It only stores cryptographic facts about property and keys.



## Final System Rules

These rules are enforced by code and cannot be changed without deploying a new version:

- Minimum property threshold: "0.05 rBTC"
- Mandatory lock period: "21 days"
- Wallet type: Non-custodial only
- Voting model: One Solokey = One vote
- Registration timing: Allowed up to the last moment
- Confirmations: Same as standard payment finality
- Withdrawal: Not allowed before full expiry
- Key recovery: Not possible
- Credential revocation: Not possible
- Administrator powers: None
- Each election: Fully separate registration required



## How the Electoral Register Exists

There is no central voter database.

Instead:

- Every valid registration is written permanently to the blockchain
  
- Anyone in the world can rebuild the voter roll by reading those records
  
- Thousands of independent copies of the register can exist at once
  
- No single party controls who is on the roll

The blockchain is the register.



## High-Level Registration Flow

1. A person uses a non-custodial rBTC wallet
2. They connect a physical Solokey
3. They lock "0.05 rBTC" for "21 days"
4. The lock is bound to exactly one Solokey
5. The blockchain permanently records the registration
6. The person now exists on the public voter roll for that one election

No approval.
No accounts.
No identity checks.
No administrators.



## High-Level Voting Flow

1. The voting system sends a random challenge
2. The voter proves control of their Solokey
3. The voting system checks the public POPregister records
4. If the lock and key are valid → the vote is accepted

This allows:

- Geo-fenced elections
- Mobile voting
- Hardware-secured voting
- Fully auditable results



## Trust Model

POPregister replaces:

- Trust in governments
- Trust in election officials
- Trust in institutions

With:

- Trust in cryptography
- Trust in open-source code
- Trust in locked economic value

This is property-based suffrage enforced by math.



## Intended Use Cases

- City-state governance
- Charter communities
- Network states
- Digital shareholder voting
- Decentralized civic experiments
- High-trust on-chain governance



## Project Status

- ✅ System rules finalized
- ✅ Economic and security model defined
- ✅ Hardware constraint defined (Solokey)
- ✅ Custody model locked (non-custodial only)
- ✅ No admin / no revocation architecture finalized
- 🔄 Smart contracts in progress
- 🔄 Mobile wallet integration in progress
- 🔄 Public indexer in progress



## License & Ethos

POPregister is intended to be:

- Open source
- Publicly auditable
- Vendor-independent
- Resistant to capture
- Resistant to censorship

There is no privileged operator.



## Next Document

See "POPregister_v0.1.md" for:

- Complete technical architecture
- Smart contract logic
- Wallet + Solokey integration
- Hardware assumptions
- Indexer design
- Voting system interface



POPRegister — Trust the Code.
