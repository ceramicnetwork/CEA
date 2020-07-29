# Charter for Identity Working Group

## Purpose

The Identity Working Group exists to define the initial set of Ceramic documents, standards and protocols that enable a flexible, modular, powerful, and platform-agnostic identity standard used by projects working with Ceramic. 

The first phase (V1) of this working group will be focused on  use cases from technology providers, infrastructure services, and app builders to ensure an interoperable standard that meets unmet needs for these developers. 

## Goals

The goals of the Identity Working Group are to create, review, iterate, and formalize Ceramic community standards for:

- Authentication to a DID from one or many different accounts 
- Public profiles
- Verified links to external accounts, including both cryptographic and other accounts 
- Various types of social graph information 
- Indexing for external resources (e.g., databases) around a DID
- Indexing for external services or agents of the identity

Additionally, the working group will provide input to the core and community developers to produce a library that implements the standard.

## Deliverables

**Create a widely supported DID-agnostic standard for decentralized identity**

The first focus of the Identity Working Group will be on the first two CIPs corresponding to the above goals: 

- [CIP 11 - IDX](https://github.com/ceramicnetwork/CIP/issues/3)
- [CIP 12 - Root Index](https://github.com/ceramicnetwork/CIP/issues/21)

This will subsequently include discussion of and then focus on  the subdirectories of the root index, including: 
- [Profiles Index (CIP-13)](https://github.com/ceramicnetwork/CIP/issues/12), a subdirectory for a DID's profiles
- [Keychains Index (CIP-15)](https://github.com/ceramicnetwork/CIP/issues/13), a subdirectory for a DID's keychains
- [Accounts Index (CIP-14)](https://github.com/ceramicnetwork/CIP/issues/14), a subdirectory for a DID's linked accounts (i.e. crypto & Oauth)
- [Connections Index (CIP-18)](https://github.com/ceramicnetwork/CIP/issues/17), a subdirectory for a DID's social connections (i.e. follows)
- [Collections Index (CIP-16)](https://github.com/ceramicnetwork/CIP/issues/26), a subdirectory for a DID's data collections (i.e. app data)
- [Services Index (CIP-17)](https://github.com/ceramicnetwork/CIP/issues/19), a subdirectory for a DID's services (i.e. notifications or backup) 
- [Settings Index (CIP-24)](https://github.com/ceramicnetwork/CIP/issues/57), a subdirectory for a DID's global settings (i.e. internationalization) 


**Implentation of a library that implements the standard**

- tentatively named IDp2p

## Success

We will know that this working group has been successful when the above deliverables have been met, and when the process has been derisked/validated through testing. Additionally, members in the working group will be actively implementing these standards. 


## Organization

- **Membership**: Anyone interested in providing constructive feedback, helping spec, or implementing the identity standards as an early user can participate in the working group if they have [joined the CEA](https://github.com/ceramicnetwork/CEA#join-the-cea)

- **Meeting Schedule**: The group will meet via video once every two weeks for a 60 minute call. These calls can be found on the CEA calendar and are named "Ceramic Governance WG". Anyone in the CEA can view the calendar and attend the calls.

- **Meeting Notes**: Meeting minutes will be captured for every meeting, recorded using the [Meeting Notes Template](templates/meeting-notes-template.md) and stored in the [Ceramic Governance V1/Meetings](working-groups/ceramic-governance/meetings) folder.

- **Discussions**: The group will use the [#ceramic-governance-wg](https://discord.gg/s5TfHct) Discord channel on the Ceramic Discord server for discussions and chat. This channel is available to anyone in the CEA.

- **Proposals**: The group will produce official Ceramic Governance proposals in the form of [CIPs](http://github.com/ceramicnetwork/cip).


## Sponsors

- Michael Sena ([@michaelsena](http://github.com/michaelsena))
- Joel Thorstensson ([@oed](http://github.com/oed))
