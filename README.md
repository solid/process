The github.com/solid/process repository details the governance of the [Solid Project Organisation](www.solidproject.org).

Anyone may submit proposal to alter the governance of Solid Project Organisation which will be reviewed only by [Tim Berners-Lee](https://github.com/timbl), who is the Solid Project Organisation Director. 

Contributors are encouraged to read the [Code of Conduct](code-of-conduct.md) before doing so.

The scope of the Solid Project Organisation is to govern the Solid specification, solidproject.org website, and Solid properties.

# What is Solid? 

Solid is a technology, like the Web, but a new level of standard which adds to the existing protocols to make it more powerful, particularly to empower individuals at home and at work. 
* Solid provides for the first time a single global logon system, so that when you log into any web site, instead of having  to log in with the usual 'f' and 'g' blue buttons, and then be tracked by Facebook and Google, you can log in with any Solid provider you trust, and that won't track you.
* Solid provides separate places ("pods") for you to store your data, a bit like Dropbox and GDrive and iCloud, but you have the power to share any file or folder or contact or event or whatever with anyone who has a solid id.  You store in data in any place you trust, (including your own computer).
* When Solid apps start, they just store all the data they need to work in your pod.  They don't store the data themselves at some computer run by the person who owns the app.  So by default you control all the data in your solid world.  This is a massive improvement to the privacy world.
* Solid app builders don't just store the data in your pod any old way.  They use solid standard formats.  This means that you and the people you work with can actually use many different apps -- at the same time even - to do stuff.

# Definitions

* SolidID or WebID: is a unique identifier used to identify a specific user. An example of what a WebID could look like is: https://fulano.pod.provider/profile/card#me. To share data with a third party, a user associates sharing preferences to the WebID of that third party. 
* Pod: A Pod is where data is stored on the Web with Solid. A user may store their data in one Pod or several Pods, and applications read and write data into the Pod depending on the authorisations granted by the user or users associated to that Pod.
* Solid App: an app that is compatible with the Solid specification 
* Solid community: individual and organisations who are either working on developing the Solid standard, implementing the Solid standard, or using Solid compatible software 
* Solid ecosystem: see Solid community 
* Solid Panels: groups of defined individuals who are working together to submit suggestions to improve the Solid standard for editorial review 
* Specification: a detailed precise presentation of something or of a plan or proposal for something
* Standard: something established by authority, custom, or general consent as a model or example
* Protocol: an original draft, minute, or record of a document or transaction. 
* Stakeholders: are those affected by normative changes to the [Solid Specification](https://github.com/solid/specification). There are two types of Stakeholders: Solid Users and Solid Implementers. A Stakeholder may be both a user and an implementer.
* Solid Users: are individuals, companies, or organizations who access data stored in a Solid Pod. 
* Solid Implementers: are companies or organisations who are implementing the [Solid Specification](https://github.com/solid/specification). A Solid Implementer may be any combination of Identity Provider, Pod Provider, and Application Provider.
* Contributor: anyone who contributes to Solid, for example, by identifying problems, asking questions, or proposing normative changes.

# The Solid Team 

The Solid Project Organisation is maintained by the Solid Team which is directed by Sir Tim Berners-Lee. 

There are several roles and responsibilities on the Solid Team which are described below. Individuals are appointed roles on the Solid Team by the Solid Director, Sir Tim Berners-Lee.  

All individuals are expected to attend a weekly Solid Team meeting.

The Solid Team are listed as Owners of the Solid GitHub in order to complete their appointed roles and responsibilities. 

Each of the Solid Team roles correspond to the [Solid GitHub teams](https://github.com/orgs/solid/teams) and there are lists of of appointed individuals to the roles [Manager](https://github.com/solid/process/blob/master/manager.md), [Administrators](https://github.com/solid/process/blob/master/administrators.md), [Editors](https://github.com/solid/process/blob/master/editors.md), [Creators](https://github.com/solid/process/blob/master/creators.md). 

## Solid Director 

The role of the Solid Director is to lead Solid by providing the vision. 

Specific responsibilities of the Solid Director include:
* Provide a clear written definition of the Solid vision including definition of key terms 
* Appoint individuals to roles on the Solid Team 
* Provide feedback to the Solid Manager on how best to implement the Solid vision 

## Solid Manager

The role of the Solid Manager is to implement the vision put forward by the Solid Director. 

Specific responsibilities of the Solid Manager include:
* Moderate the gitter and forum Solid chats
* Moderate the weekly Solid Team meeting 
* Moderate the webinar Solid World 
* Write and send the newsletter This Month in Solid 
* Tweet on behalf of Solid via @project_solid
* Support Administrators, Editors, and Creators to be able to carry out their responsibilities 
* Respond to the info@solidproject.org email on behalf of the Solid Team
* Collect applications to Solid Team roles and present them to the Solid Director for review and respond to the candidates
* Promote research on Solid by maintaining a public list of Solid Labs and communicating Solid Labs to potential research institutions who may be interested in researching on Solid
* Promoting companies to implement Solid to produce software that is Solid compatible 

## Administrators 

The role of the Administrators is to maintain Solid properties which covers tools, systems, and services used for advancing Solid. 

Specific responsibilities of the Administrators include:
Ensuring that all passwords of Solid properties are recorded and updated in the Solid 1Password account 
Ensure that all Administrators have access to the Solid 1Password account
Ensuring domain and hosting for solidproject.org are up and running 
Are Admins and Moderators on forum.solidproject.org 

## Editors 

The role of the Editors is to maintain the Solid standard by processing suggestions made by panellists. 

Specific responsibilities of the Editors include:
Ensuring that all suggestions to improve the Solid standard are collected as issues or pull requests in github.com/solid/specification 
Reviewing Solid standard proposals from panellists
Reviewing pull requests prepared by Creators to process suggestions to improve the solidproject.org website 

[Editors](https://github.com/solid/process/blob/master/editors.md) have [_Admin Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on [repositories tagged as ‘standard’](https://github.com/search?q=topic%3Aspecification+org%3Asolid&type=Repositories) to be able to carry out their Editorial responsibilities. 

## Creators

The role of the Creators is to maintain solidproject.org by processing suggestions to improve the website. 

Specific responsibilities of the Creators include:
Processing suggestions to improve solidproject.org to be recorded on the [website kanban board](https://github.com/solid/solidproject.org/projects/1) 
maintaining the listings of Solid apps, Pods, Solid identity providers and Solid developer tooling

[Creators](https://github.com/solid/process/blob/master/creators.md) have [_Admin Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on [repositories tagged as ‘website’](https://github.com/search?q=topic%3Awebsite+org%3Asolid&type=Repositories)

# The solidproject.org Website 

The solidproject.org website is linked to the [`master` branch of the GitHub repo solid/solidproject.org](https://github.com/solid/solidproject.org/tree/master). Draft versions of updates of the website are worked on in the [`staging` branch of the same repo](https://github.com/solid/solidproject.org/tree/staging). The draft work is documented on the [Creators project board](https://github.com/orgs/solid/projects/12). 

Anyone can make suggestions by commenting or submitting  pull requests to the [`staging` branch of solid/solidproject.org](https://github.com/solid/solidproject.org/tree/staging) to be reviewed by Editors, and be approved by the Solid Director before they go to `staging`.

Spelling, grammar, broken links, and other minor changes do not need to be approved by the Solid Director and can be updated or approved directly in `staging` by the Creators. Changes larger than that, but that do not significantly alter the website content (such as referencing community activity outside of the website) also do not need to be approved by the Solid Director in order to be applied to `staging`, as long as they have been approved by one of the [Editors](https://github.com/solid/process/blob/master/editors.md).

Creators can move changes in `staging` to `master` (and hence solidproject.org) at any time, since `staging` will only contain approved changes.

# The Solid Specification

The latest version of the Solid standard can be found on solidproject.org/standard which is linked to the [Solid standard repository](https://github.com/solid/specification) which allows for collaborative editing. 

The following is a description about how changes to the specifications in the Solid ecosystem may be proposed and accepted.

### Solid Panels

Solid Panels are groups of individuals focused on a specific problem or domain relevant to Solid, with an aim to propose changes to the [Solid Specification](https://github.com/solid/specification). Domains may be technical, non-technical, or some combination of the two. For example, a Security Panel could focus on the evaluation and advancement of the Solid security model. Only members of the [W3C Solid Community Group](https://www.w3.org/community/solid/), which anyone may join, and which operates under the [W3C Community Contributor License Agreement](https://www.w3.org/community/about/agreements/cla/), may become a member of a Solid Panel.

New panels may be proposed by submitting an issue to the [solid/process](https://github.com/solid/process) repository. Establishing a new panel requires the endorsement of at least one member of the [Editorial Team](https://github.com/orgs/solid/teams/editors). To receive endorsement, the proposed panel submission must include:

1. A stated purpose
1. One or more initiatives that will be actively pursued and tracked in regular panel sessions to advance the stated purpose
1. Demonstrable support of at least five prospective members

Any iteration on the stated purpose, initiatives, and supporting members should continue as needed until endorsement is received from at least one member of the Editorial Team. Submissions that fail to receive endorsement may be removed by Solid Administrators after six months.

Any Editor endorsing a panel is expected to attend regular sessions, and to provide the Panel Chairs and Panel with insight on specification priorities, as well as support work on any relevant initiatives in flight.

Each panel is chaired by one or more Panel Chairs. An Editorial Team member endorsing a panel is responsible for electing the Panel Chairs, barring any vetoes from another Editor, another Panel Chair of the same panel, or vetoes from a majority of panel members. The Solid Director reserves the right to elect and/or change Panel Chairs. In the event that an Editor should be nominated as a Panel Chair, they must be elected by another member of the Editorial Team.

 Responsibilities of a Panel Chair include but are not limited to:

- Coordinating and communicating panel initiatives
- Collaboaring with Editors on priority and direction of panel initiatives
- Ensuring panel meetings are focused on advancing panel initiatives
- Ensuring every Panel meeting has a clear goal and agenda
- Ensuring all actions arising from meetings are tracked to completion
- Ensuring target dates are set for outcomes
- Working with Panel members to achieve broad consensus on decisions, with a consistent aim towards unanimity, in general accordance with the W3C process for realizing [consensus](https://www.w3.org/2019/Process-20190301/#Consensus).
- Referring to the W3C process to [constructively manage dissent](https://www.w3.org/2019/Process-20190301/#managing-dissent) from panel members so that the group can continue to make progress in the absence of broad consensus.
- Ensuring panel decisions, activities, and achievements are tracked and communicated.

Decisions made by a Panel about proposed specification changes are subject to the [proposal review process](#reviewing-proposals).

A list of Solid Panels is maintained at [panels.md](panels.md). This listing helps people find panels they may want to participate in, and helps editors find panels to consult as part of the editorial process.

Panels may request to have a repository created within the [Solid Github Organization](https://github.com/solid). These requests should be made by submitting an issue to [solid/process](https://github.com/solid/process). The request should include the proposed name of the repository, and how it will be used. Any editor may reject a proposed name and request an alternative. All panel members will receive [_Maintain Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on the panel repository, unless it is subject to editorial review, which would require that it employ a [different permission structure](#repositories). Panel repositories that are inactive for more than six months may be archived by Solid Administrators.

Panels may request to have a gitter channel created within the [Solid Gitter Organization](https://gitter.im/solid). These requests should be made by submitting an issue to [solid/process](https://github.com/solid/process).

## How to Make Changes

This section details how changes to the [Solid Specification](https://github.com/solid/specification) may be drafted, proposed, and accepted.

Anyone may submit a proposal to alter this process. These proposals will not be reviewed by the editors. They will be reviewed only by [Tim Berners-Lee](https://github.com/timbl), who is the Solid Director.

### Drafting proposals

Anyone may propose improvements to the [Solid Specification](https://github.com/solid/specification). Here are some examples of different ways to contribute:

- Submit a pull request or issue on the [Solid Specification repository](https://github.com/solid/specification) in GitHub
- Make a suggestion to the Solid Authorization Panel chat room about a change you'd like to see in Web Access Control
- Make a suggestion on the Solid W3C Community Group mailing list to form a new Solid Panel, or join an existing Solid Panel
- Propose an item for the W3C Solid Community Group call

Proposals for substantive changes to the [Solid Specification](https://github.com/solid/specification) go through an editorial review process. A change is considered substantive when it alters the normative text of the Solid Specification or the Solid Roadmap. Any proposal must be realistic and reasonable to implement, preferably with example implementations, and demonstrable support from Implementers.

Any proposal should also be accompanied with a reasonable explanation of the need for the proposed change. For example:

- Adding a new capability that satisfies one or more new use cases, or to reflect a new capability already incorporated consistently into multiple implementations.
- Removing something because it was never adopted by Implementers for legitimate reasons, or because there has been a collective shift in focus away from that feature and it no longer makes sense to keep it.
- Changing something to a simpler design that is able to address the same use case(s) with less complexity, or a change that resolves one or more identified issues in real-world use.

A draft proposal often involves public discussion before being formally presented for review. After these discussions have occurred and a draft proposal has reached a sufficient level of maturity, it should be presented as a candidate proposal, asking Stakeholders and Panels if there are any major objections.

When there are objections, notify the Solid Panels and Stakeholders about the final proposal with an invitation to vote. If there are options, detail them along with the implications of the options. The final proposal needs to be open for one week to give others a chance to vote. To show your support for a proposal write +1. To show your disapproval for a proposal write -1 along with a detailed reason for the disapproval and a suggestion for a preferred alternative. To abstain type 0 when you have no opinion. If you do not vote by the end of the week it will be assumed that you abstain. At the end of the week anyone may publish an overview of the vote results per Solid Panel and Stakeholder.

### Reviewing proposals

Candidate proposals to the [Solid Specification](https://github.com/solid/specification) submitted for review go through an editorial process before they are accepted.
Candidate Proposals to change the Solid Specification must be submitted for editorial review before they are accepted, along with the results of any votes taken.

To help broad consensus form, it is suggested that each proposal be brought to the attention of the Editors at some defined contact points during its life cycle. These contact points are:
1. When a reason to change or extend the specification is first encountered, an [issue is opened](https://github.com/solid/specification/issues/new). The issue is then used for further communication with the Editors.
1. Panels may create or adopt issues, and Panels should notify Editors that such discussion has started.
1. When a Panel reaches rough consensus on an issue, the Panel should notify the Editors, indicating in informal text what the consensus entails and who participated in forming it.
1. When a Panel starts drafting the text of a proposal, the Panel should notify the Editors.

The above is not required and may be superfluous for small changes, but it is likely to speed up the overall process for larger issues.

An Editor determines whether a Candidate Proposal includes a substantive change and marks it accordingly. If there is any disagreement among Editors, the Candidate Proposal will be automatically marked as including a substantive change.

Candidate Proposals with substantive changes require three Editors who are assigned to the material being modified to actively approve the proposal, with no Editors from the Editorial Team actively rejecting. If there are less than three Editors assigned to the material being modified, then other Editors from the Editorial Team may participate.  Editors may abstain. Candidate Proposals with substantive changes must remain open for at least one week before final acceptance. If an Editor does not vote by the end of that week it will be assumed that they abstained, providing a good faith attempt has been made to involve those who may be likely to disagree. Once the Candidate Proposal has successfully passed editorial review and the specified wait-time has elapsed, it may be merged by an assigned Editor.

Candidate Proposals without substantive changes require one Editor assigned to the material being modified to actively approve the proposal, with no Editors from the Editorial Team actively rejecting, and may be merged immediately by an assigned Editor. An assigned Editor may approve and merge their own non-substantive changes. Anyone from the Editorial Team has the right to revert a non-substantive change, but are encouraged to communicate with the assigned Editor that merged it first. Any revert must be accompanied by a reasonable explanation. If the change is reverted because they believe it to be substantive, that must be included in the explanation.

# References

Solid culture documentation was put together with inspiration and learnings from the following resources.

* [W3C Good practice for running a group](https://www.w3.org/community/about/good-practice-for-running-a-group/)
* Python (2018) [Python Language](https://www.python.org/dev/peps/pep-0013/)
* Elinor Ostrom (2005) [Understanding Institutional Diversity](https://www.wtf.tw/ref/ostrom_2005.pdf).
* Chales M Schweik and Meelis Kitsting (2010) [Applying Elinor Ostrom’s Rule Classification Framework to the Analysis of Open Source Software Commons. Transnational Corporations Review](http://www.tnc-online.net/pic/2010032809124697.pdf)
* Sean McDonald (2019) [Reclaiming Data Trusts. CIGO](https://www.cigionline.org/articles/reclaiming-data-trusts)
* Aymeric Augustin [Django](https://docs.djangoproject.com/en/dev/internals/organization/)
* https://tc39.github.io/process-document/
