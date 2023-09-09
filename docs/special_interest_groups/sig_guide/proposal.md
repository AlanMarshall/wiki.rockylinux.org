---
title: Proposing a SIG
---

This page goes over proposing a Special Interest Group for the Rocky ecosystem.
Anyone can propose or participate in a Special Interest Group.

## Proposal

Creating a new Special Interest Group requires participation from a member of the Rocky teams or a member of the Rocky Linux project board. A SIG must meet these requirements:

* The group should be related to Rocky or a use-case for Rocky or Enterprise Linux as a whole
* There must be feedback and control into the Rocky community
* All communication as to the work of the SIG should be public - Some matters may have to be private, and as such should be out of band

    * It is expected that each SIG will have a public channel as `SIG/name` in mattermost. Optionally an IRC channel can also be assigned.

* Code produced within the SIG must be compatible with a FOSS license presently used by Rocky and [upstream](https://docs.fedoraproject.org/en-US/legal/) - If a new license is wanted and is not available in the upstream list, consult with Release Engineering/Core or `~Legal` in Mattermost.
* All documentation produced within the SIG must be a compatible documentation license.

    * The group will receive a wiki that they can manage their documentation and group information on the RESF Git Service (using `sig-X.rocky.page` domain)

* Groups should be aware/watchful of the direction from the Release Engineering team/Core as it can affect how SIGs operate if they are producing compiled software.
* A member of the SIG should also come from the Core/RelEng team, in the case that the SIG produces packages for use on a Rocky system.
* General reports, requests, and communication, on at least a quarterly basis, will be required with the Rocky Linux project board

It is also highly recommended to have packaged software (if applicable) to present in the proposal, e.g. on a Fedora Copr project or another setting.

## Proposal Process

It is up to the requestor to:

* Check and verify that the topic of interest is already covered by an existing Special Interest Group within Rocky or CentOS Stream
* Post an introductory RFC message:

    * As an email to the rocky-devel mailing list and ask for comments or...
    * As a message to `SIG/general` in mattermost

Upon approval or general acceptance, it is up to the requestor or a Core/RelEng member to open a ticket for creating the initial resources at the [SIG/Core Tracker](https://git.resf.org/sig_core/meta/issues) using a predefined template. Click "new issue" and then "Requests for SIG Proposal" will take you to the template to fill out, which includes:

  * An introduction of yourself and the request for resources for the SIG
  * The initial proposal (this can be a copy and paste of the original proposal or another version related to the original request)
  * The initial asks, such as groups in Rocky Account Services, RESF Git Service Organization, channels in mattermost, and a release package if required
  * A checklist, which includes that you have read this guide                                                                                                                                                        

## Acceptance

Upon acceptance, the request for resources will be completed and the ticket will be closed out.

(To be continued)

{% include "releng/resources_bottom.md" %}
