# Identity Working Group Charter (V1)

## Purpose

The Identity WG exists to define the initial set of Ceramic documents, standards and protocols that enable a flexible, modular, powerful, and platform-agnostic identity standard used by projects working with Ceramic. 

The first phase (V1) of this working group will be focused on  use cases from technology providers, infrastructure services, and app builders to ensure an interoperable standard that meets unmet needs for these developers. 

## Goals

The goals of the Identity Working Group are to create, review, iterate, and formalize Ceramic community standards for:

- Structuring an identity-centric index of a DID's resources to enable permissionless discovery and routing 
- Authentication to a DID from one or many different accounts 
- Public profiles, to enable contextualization of identity in a consistent way
- Linking to 3rd party accounts, including both cryptographic and other accounts 
- Various types of social graph information 
- Mapping to external resources (e.g., databases) and services (e.g., notifications) 

Additionally, the working group will provide input to the core and community developers to produce a library that implements the standard.

## Deliverables

**Create a widely supported DID-agnostic standard for decentralized identity**

The initial focus of the Identity Working Group will be on the first three CIPs corresponding to the above goals: 

- [3ID (DID) Doctype (CIP-6)](https://github.com/ceramicnetwork/CIP/issues/6)
- [Identity Index (IDX) (CIP-11)](https://github.com/ceramicnetwork/CIP/issues/3)
- [Root Index (CIP-12)](https://github.com/ceramicnetwork/CIP/issues/21)

This will  include discussion of and then subsequent focus on the subdirectories and documents linked in the IDX standard, including: 
- [Keychains Index (CIP-15)](https://github.com/ceramicnetwork/CIP/issues/13) and [Auth Keychain (CIP-20)](https://github.com/ceramicnetwork/CIP/issues/33), which together provide for a DID's linked keys
- [Profiles Index (CIP-13)](https://github.com/ceramicnetwork/CIP/issues/12) and [Basic Profile (CIP-19)](https://github.com/ceramicnetwork/CIP/issues/32), which together provide for a DID's profile information
- [Accounts Index (CIP-14)](https://github.com/ceramicnetwork/CIP/issues/14), [Crypto Account Links (CIP-21)](https://github.com/ceramicnetwork/CIP/issues/44), and [Social Account Links (CIP-22)](https://github.com/ceramicnetwork/CIP/issues/43), which together provide for a DID's linked accounts (i.e. crypto & Oauth)

Discussion may also touch on other parts of IDX, which will become a focus in future versions of the Identity WG. These include: 
- [Connections Index (CIP-18)](https://github.com/ceramicnetwork/CIP/issues/17), a subdirectory for a DID's social connections (i.e. follows)
- [Collections Index (CIP-16)](https://github.com/ceramicnetwork/CIP/issues/26), a subdirectory for a DID's data collections (i.e. app data)
- [Services Index (CIP-17)](https://github.com/ceramicnetwork/CIP/issues/19), a subdirectory for a DID's services (i.e. notifications or backup) 
- [Settings Index (CIP-24)](https://github.com/ceramicnetwork/CIP/issues/57), a subdirectory for a DID's global settings (i.e. internationalization) 


**Implentation of a library that implements the standard**

Work on this library, tentatively named idp2p, is being carreid out by Ceramic core developers. This working group wil inform that development, provide feedback on early iterations, and help test and implement production versions. 

## Success

We will know that this working group has been successful when the above deliverables have been met, and when the process has been derisked/validated through testing. Additionally, members in the working group will be actively implementing these standards. 

## Organization

- **Membership**: Anyone interested in providing constructive feedback, helping spec, or implementing the identity standards as an early user can participate in the working group if they have [joined the CEA](https://github.com/ceramicnetwork/CEA#join-the-cea)

- **Meeting Schedule**: The group will meet via video once every two weeks for a 90 minute call. These calls can be found on the CEA calendar and are named "Ceramic Identity WG". Anyone in the CEA can view the calendar and attend the calls.

- **Meeting Notes**: Meeting minutes will be captured for every meeting, recorded using the [Meeting Notes Template](templates/meeting-notes-template.md) and stored in the [Identity WG/Meetings](https://github.com/ceramicnetwork/CEA/tree/identity-wg-charter/working-groups/identity/meetings) folder.

- **Discussions**: The group will use the [#identity-wg](https://discord.gg/sdtGKCN) Discord channel on the Ceramic Discord server for discussions and chat. This channel is available to members of the CEA.

- **Proposals**: The group will produce official Ceramic Governance proposals in the form of [CIPs](http://github.com/ceramicnetwork/cip).


## Sponsors

- Michael Sena ([@michaelsena](http://github.com/michaelsena))
- Joel Thorstensson ([@oed](http://github.com/oed))
