---
title: "Request For Comment: \ Alternative Options for Communication"
subtitle: "RFC0001"
author:
  - Richard B. Wagner <breckwagner@gmail.com>
  - Francis Richards <rickarichards@gmail.com>
date: "2018-03-21"
tags:
  - proposal
  - communication
  - community engagement
  - strategic planning
abstract: |
  We propose the adoption of a new on-line software, Disclosure, which will better meet the needs for broad-based communication between NBC community members.
---

Motivation
================================================================================

History
--------------------------------------------------------------------------------
Over the last couple of years the Narragansett Boat Club has been expanding to the point where current communication methods that members use have become stifling to community growth and effective, efficient communication. The current platforms available to membership include direct communication (signs/mail/meetings/etc), vanilla email, Google Groups, the rownbc.org website, social media accounts, and miscellaneous out of band communications. Additionally, at the latest Board of Governors meeting, it was discussed that the club both needs and intends to change the structure of governance. To accomplish this, one step that may be made is the establishment or adoption of a permanent communication platform that would promote transparency, participative leadership, upward communication, organizational identification and could be leverage the skill variety of the membership as well as better orient and engage new members.

Background: Communication Software Platforms
--------------------------------------------------------------------------------

In the research field of Computer Supported Collaborative Work, several heuristics can be used for the evaluation of platforms and software. Particularly important is the measurement of synchronicity. In this example optimal synchronicity would allow communication between members in a computer supported collaborative network in real time. See Appendix A for a list of potential communication platforms including Discourse.

### Potential Communication Platforms:

#### Discourse
![Discourse Logo][discourse-image]
[discourse.org](https://www.discourse.org/)  
Discourse is an example of an *asynchronous distributed* communication platform which lends itself out of band communication. It operates similar to a forum but lends itself to extensibility. It has a plugin framework that is actively being expanded and developed. It has search functionality and highly usable clean user interface.

#### Slack
![Slack Logo][slack-image]
[slack.com](https://slack.com/)  
Slack is an example of a *synchronous distributed* communication platform which lends itself to realtime communication. It solves a different problem then discourse and is only available as a service without a self hosting option however there are equivalent platforms that do support self hosting.

#### Google Groups
Google Groups like Discourse is also an example of an *asynchronous distributed* communication platform. Unlike Discourse, Google Groups is not conducive to searching old conversations and conversations easily become disjoint. Conversations also lack visual queues to indicate the importance of a thread and no ability to pin threads

Potential Drawbacks
--------------------------------------------------------------------------------

Cost: Free for workspaces with 250 or less (active) members. and an 85% discount for workspaces above that size.  The estimated cost is negligible other than time to manage the platform (estimated as periodic time to troubleshoot any hardware issues involving the internet).([Slack for Nonprofits](https://get.slack.help/hc/en-us/articles/204368833-Slack-for-Nonprofits)) and

Unresolved Questions
--------------------------------------------------------------------------------

Who will be responsible for maintaining the platform?  

What degree of openness should the platform have? E.g. should it be possible for non members to access it as a way for them to evaluate the benefits of membership?   



APPENDIX A: Type of Communication
================================================================================

 - **Synchronicity** `synchronous` vs `asynchronous`: describes the immediacy of communication. An analogy might be a telephone conversation contrasted to a mailed a letter.  
 - **Locality** `colocated` vs `distributed`: describes the relative locality of participants. An analogy might be an in person meeting contrasted with an instant messaging conversation.

| Type | Example |
| ---- | --- |
| Synchronous Colocated | face-to-face meeting such as quarterly meetings or informal in-person communication|
| Synchronous Distributed | telephone call or other real time messaging application |
| Asynchronous Colocated | message board at the clubhouse, do not row labels, etc. |
| Asynchronous Distributed | Forums and Email *(Primary interest of proposal)* |




APPENDIX B: Feature/Cost Matrix
================================================================================
> Electrical cost estimate based on 0.14 $/kWh and 24 hour/day operation and a 200 W load.  

#### Asynchronous Distributed Platforms


![][discourse]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Self-Hosted**             | cost of power `< 245.45 $/yr`   |
| **Cloud**                   | `$5-$25/mo`                     |


![][flarum]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Self-Hosted**             | cost of power `< 245.45 $/yr`   |
| **Cloud**                   | `$5-$25/mo`                     |


![][nodebb]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Self-Hosted**             | cost of power `< 245.45 $/yr`   |
| **Cloud**                   | `$5-$25/mo`                     |


![][google-groups]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Cloud**                   | `$0`                            |


#### Synchronous Distributed Platforms

![][slack]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Free**                    | free 10K message archive limit  |
| **Standard**                | free `<250` else `$1.2/user/mo` |

![][stride]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Free**                    | free 25K message archive limit  |
| **Standard**                | possibly free                   |

![][hipchat]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Free**                    | free 25K message archive limit  |
| **Standard**                | possibly free                   |

![][mattermost]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Self-Hosted**             | cost of power `< 245.45 $/yr`   |
| **Cloud**                   | `$5-$25/mo`                     |

![][rocketchat]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Self-Hosted**             | cost of power `< 245.45 $/yr`   |
| **Cloud**                   | `$5-$25/mo`                     |

![][zulip] ![][zulip2]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Self-Hosted**             | cost of power `< 245.45 $/yr`   |
| **Cloud**                   | `$5-$25/mo`                     |

![][matrix]

| Option                      | Cost                            |
| --------------------------- | ------------------------------- |
| **Self-Hosted**             | cost of power `< 245.45 $/yr`   |
| **Riot.im**                 | `decentralized self-hosted`     |




[google-groups]:assets/google-groups.png { height=32px }
[slack]:assets/slack.png { height=32px }
[flarum]:assets/flarum.png { height=32px }
[nodebb]:assets/nodebb.png { height=32px }
[discourse]:assets/discourse.png { height=32px }
[stride]:assets/stride.png { height=32px }
[hipchat]:assets/hipchat.png { height=32px }
[zulip]:assets/zulip.png { height=32px }
[zulip2]:assets/zulip2.png { height=32px }
[rocketchat]:assets/rocketchat.png { height=32px }
[matrix]:assets/matrix.png { height=32px }
[mattermost]:assets/mattermost.png { height=32px }
