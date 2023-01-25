This repository details how changes to Solid may be proposed and accepted.

# Solid Specification
The following describes how changes to the specifications in the Solid ecosystem may be proposed and accepted. Anyone may submit a proposal to alter this process; such proposals will be approved only by [Tim Berners-Lee](https://github.com/timbl), who is the Solid Director.

Development in the Solid ecosystem occurs in the [Solid Specifications](https://github.com/solid/specification) repository. The deprecated [Unofficial Draft](https://github.com/solid/solid-spec) predating current development is still available for historical reference.

Anyone may participate in this process. Please read the [Code of Conduct](code-of-conduct.md) before doing so.

## Editorial Team

The Solid [Editorial Team](https://github.com/orgs/solid/teams/editors) is responsible for the implementation of the Solid Specification process. Members of the Editorial Team are appointed by the Solid Director. The Editorial Team is comprised of all the Editors appointed by the Solid Director, who are listed at [editors.md](editors.md), along with their assignments, contact details, and affiliations. The Editorial Team shepherds Solid and coordinates with those who participate in [Solid Panels](#solid-panels) and with [Stakeholders](#stakeholders) and [Implementers](#implementers). The Solid Director may also appoint support personnel on an as-needed basis, such as a Release Manager, for organizing the workflow of the specification process.

Anyone may apply to be an Editor, and must include one or more requested editorial assignments as part of their application. These requests are reviewed only by the Solid Director. Editor applications that can demonstrate the support of a relevant panel or group of community members will be favorably considered.

## Contributors

Any individual who has been involved in proposals to improve the [Solid Specification](https://github.com/solid/specification) has provided a valuable service to the [Solid Project](https://www.solidproject.org) and is encouraged to continue.

Contributions are welcome, including identifying problems, asking questions, and proposing normative changes.

There are many topics, problems, or ideas best addressed by a group of contributors with specific domain expertise in [Solid Panels](#solid-panels).

### Solid Panels

Solid Panels are groups of contributors focused on a specific problem or domain relevant to Solid, with an aim to propose changes to the [Solid Specification](https://github.com/solid/specification). Domains may be technical, non-technical, or some combination of the two. For example, a Security Panel could focus on the evaluation and advancement of the Solid security model. Only those who have agreed to the [W3C Community Contributor License Agreement](https://www.w3.org/community/about/agreements/cla/) may participate in a Solid Panel.

New panels may be proposed by submitting an issue to the [solid/process](https://github.com/solid/process) repository. Establishing a new panel requires the endorsement of at least one member of the Editorial Team. To receive endorsement, the proposed panel submission must include:

1. A stated purpose
1. One or more initiatives that will be actively pursued and tracked in regular panel sessions to advance the stated purpose
1. Demonstrable support of at least five prospective participants

The panel proposal can be revised until at least one member of the Editorial Team endorses the proposal. Submissions that fail to receive endorsement may be removed by Solid Administrators after 3 months.

Any Editor endorsing a panel is expected to attend the panel regularly, and to provide the panel insight on specification priorities and support the work of the panel.

Each panel is chaired by one or more Panel Chairs. An Editorial Team member endorsing a panel is responsible for appointing the Panel Chairs, barring any objections from another Editor, another Panel Chair of the same panel, or objection from a majority of panel members. The Solid Director reserves the right to appoint and/or change Panel Chairs. In the event that an Editor is nominated as a Panel Chair, they must be appointed by another member of the Editorial Team.

 Responsibilities of a Panel Chair include but are not limited to:

- Coordinating and communicating panel initiatives
- Working with Editors on prioritizing panel initiatives
- Ensuring panel meetings are focused on advancing panel initiatives
- Ensuring every panel meeting has a clear goal and agenda
- Ensuring all actions arising from meetings are tracked to completion
- Ensuring target dates are set for objectives
- Ensuring panel decisions, activities, and achievements are tracked and communicated

Specification changes proposed by a panel are subject to the [proposal review process](#reviewing-proposals).

Those interested in participating in a panel can find a list of active panels at [panels.md](panels.md).

Panels may request to have a repository created within the [Solid Github Organization](https://github.com/solid) by creating an issue in [solid/process](https://github.com/solid/process). The request should include the proposed name of the repository and how it will be used. Any editor may reject a proposed name and request an alternative. All panel members will receive [_Maintain Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on the panel repository. Panel repositories that are inactive for more than six months may be archived by Solid Administrators.

Panels may request to have a gitter channel created within the [Solid Gitter Organization](https://gitter.im/solid) by creating an issue in [solid/process](https://github.com/solid/process).

Panels that become inactive can be closed by a majority vote of the Solid Editors.

## Stakeholders

Stakeholders are those affected by normative changes to the [Solid Specification](https://github.com/solid/specification). There are two types of Stakeholders: [Solid Users](#solid-users) and [Solid Implementers](#solid-implementers). It is important to consider them both when proposing changes, and adhering to the W3C Web Platform Design Principles' [Priority of Constituencies](https://www.w3.org/TR/design-principles/#priority-of-constituencies) is encouraged. A Stakeholder may be both a user and an implementer.

Stakeholders who have opted to identify themselves publicly are listed at [stakeholders.md](stakeholders.md). Anyone may decide to identify themselves publicly as a Solid Stakeholder, but it is not mandatory. Identified stakeholders may be consulted for feedback as part of the editorial process.

### Implementers

Solid Implementers are organizations who are implementing the [Solid Specification](https://github.com/solid/specification). A Solid Implementer may be any combination of Identity Provider, Pod Provider, Application Provider, or a provider of other Solid-related functionality.

## How to Make Changes

This section details how changes to the [Solid Specification](https://github.com/solid/specification) may be drafted, proposed, and accepted.

### Drafting proposals

Anyone may propose improvements to the [Solid Specification](https://github.com/solid/specification), which should be submitted as a pull request or issue on the [Solid Specification repository](https://github.com/solid/specification) in GitHub. Proposals for substantive changes to the [Solid Specification](https://github.com/solid/specification) go through an editorial review process. A change is considered substantive when it alters the normative text of the Solid Specification or the Solid Roadmap. Any proposal must be realistic and reasonable to implement, preferably with example implementations, and demonstrable support from Implementers.

Any proposal should also be accompanied with a reasonable explanation of the need for the proposed change. For example:

- Adding a new capability to satisfy one or more new use cases, or to reflect a capability that has already been implemented.
- Removing something because it was never adopted by Implementers for legitimate reasons, or because there has been a collective shift in focus away from that feature and it no longer makes sense to keep it.
- Changing something to a simpler design that is able to address the same use case(s) with less complexity, or a change that resolves one or more identified issues in real-world use.

A draft proposal often involves public discussion before being formally presented for review. Stakeholders and Panels may provide feedback on draft proposals.

### Reviewing proposals

Candidate proposals to the [Solid Specification](https://github.com/solid/specification) submitted for review go through an editorial process before they are accepted.

The [Solid Editors](https://github.com/orgs/solid/teams/editors) [maintain a monthly development cycle](solid-editors-tr-process.md) in which they select proposals and issues from the open issues and proposals for consideration. 

The Editors typically meet weekly, with an agenda put forward by the Solid Director with the help of other Editors and the Release Manager. In the interest of transparency, these meetings are to be recorded and made public within two days of the meeting.

To help broad consensus form, it is suggested that each proposal be brought to the attention of the Editors at some defined contact points during its life cycle. These contact points are:
1. When a reason to change or extend the specification is first encountered, an [issue can be created](https://github.com/solid/specification/issues/new). The issue can then be used for further communication with the Editors.
1. Panels may create or adopt issues, and Panels should notify Editors that such discussion has started.
1. When a Panel reaches rough consensus on an issue, the Panel should notify the Editors, indicating in informal text what the consensus entails and who participated in forming it.
1. When a Panel starts drafting the text of a proposal, the Panel should notify the Editors.

The above is not required and may be superfluous for small changes, but is likely to speed up the overall process for larger issues.

An Editor determines whether a Candidate Proposal includes a substantive change and marks it accordingly. If there is any disagreement among Editors, the Candidate Proposal will be automatically marked as including a substantive change.

When a proposal is first submitted, the Solid Editors will assign a single Editor as the shepherd for the proposal and assign a time window for review and its acceptance or rejection; the time window will be either 1 or 2 months from the date of proposal submission, depending on the complexity of the proposal. If an Editor is a contributor to the proposal, they will not be assigned as the proposal's shepherd. This time window includes all discussion and revision that may be needed to improve the proposal. The Solid Director, working with the Solid Editors and any administrative support personnel, will maintain a dashboard of open and closed proposals, time windows for review, and review status.

If a contributor disapproves of Candidate Proposal that is under consideration, they must provide substantive, written comments that contain proposed remedies to the Solid Editors at least 1 week before the end of the review time window. The Solid Editors will consider the comments and suggest possible remedies.

Candidate Proposals with substantive changes must be responsive to comments and objections. If rough consensus to approve the proposal cannot be reached among the Solid Editors, a vote must be taken during an Solid Editors meeting, and the advancement of the proposal can be blocked by a negative vote by 1/3 of all Editors. Once the Candidate Proposal has successfully passed editorial review, it is merged by its shepherd. The shepherd for a proposal is responsible for ensuring a resolution of the proposal within the time window, and if the shepherd is unable to complete the proposal review during the time window, the Solid Director will appoint a different Editor as shepherd and extend the time window for the proposal by 1 month. If a proposal is not approved, the proposer may resubmit it in revised form no sooner than one month after the final review by the Solid Editors.

Candidate Proposals without substantive changes require one Editor assigned to the material being modified to actively approve the proposal, with no Editors from the Editorial Team actively rejecting, and may be merged immediately by an assigned Editor. The assigned Editor who is shepherding may approve and merge their own non-substantive changes. Anyone from the Editorial Team has the right to revert a non-substantive change, but are encouraged to communicate with the assigned Editor who merged it first. Any revert must be accompanied by a reasonable explanation. If the change is reverted because they believe it to be substantive, that must be included in the explanation.

### Vocabulary Management

The [W3C Solid Community Group](https://www.w3.org/community/solid/) handles the management of Solid vocabularies under its responsibility through the [solid/vocab](https://github.com/solid/vocab) repository.

The policy for the management of Solid vocabularies under the W3C namespace is described in [Adding to W3C RDF Namespaces](https://www.w3.org/2016/08/namespaces/).

### Repositories

Repositories requiring editorial review are listed in [editors.md](editors.md#editorial-assignments). Each repository has one or more assigned editors, and only assigned editors are permitted to merge into the main branch of these repositories, per the [proposal review process](#reviewing-proposals).

Editors have [_Admin Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on the repositories they are assigned to, and are permitted to grant [_Write Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) to other contributing authors on the same. All Editors have [_Write Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on all repositories requiring editorial review listed in [editors.md](editors.md).

# Solid QA

Solid QA policy, processes, and procedures are developed through the [Test Suite Panel](https://github.com/solid/test-suite-panel/) as per the [Test Suite Panel Charter](https://github.com/solid/process/blob/main/test-suite-panel-charter.md) with the aim to give authors of technical reports and implementers of software confidence that they can rely on the Solid ecosystem to deliver on the promise of interoperability based on open standards.

# Administration

Administrators are granted privileged access to control the tools, systems, and services used for advancing the Solid. This includes the [Solid GitHub](https://github.com/solid) organization, [Solid Gitter](https://gitter.im/solid/home) channels, the [Solid Forum](https://forum.solidproject.org), and the [Solid Website](https://www.solidproject.org).

Administrators belong to the [Administrators Team](https://github.com/orgs/solid/teams/administrators) in the [Solid GitHub Organization](https://github.com/solid) and have [_Admin Permissions_](https://help.github.com/en/articles/repository-permission-levels-for-an-organization#permission-levels-for-repositories-owned-by-an-organization) on all repositories therein. Administrators have [_Owner Permissions_](https://help.github.com/en/articles/permission-levels-for-an-organization#permission-levels-for-an-organization) for the [Solid GitHub Organization](https://github.com/solid).

### Becoming an Administrator

Administrators are appointed by the Solid Director. Administrators are listed at [administrators.md](administrators.md) along with their contact details and affiliations. Anyone may apply to be an Administrator. Administrator applications are reviewed only by the Solid Director.

# Solidproject.org Website

[Creators](https://github.com/solid/process/blob/master/creators.md) independently assist with keeping [solidproject.org](https://solidproject.org/) up to date.

Anyone can make suggestions by creating issues or submitting pull requests
to the [solid/solidproject.org](https://github.com/solid/solidproject.org) repository.

Minor changes (such as spelling, grammar, and broken links) do not require review.
Larger chunks of texts should be reviewed by a Creator or Editor for technical correctness.
Changes to the main messaging require an approving review by the Director.

# Solidcommunity.net

[Solidcommunity.net](https://solidcommunity.net) is a free pod hosting service
maintained by the Solid Project for research, development, and experimental,
non-commercial use of Solid by community members.

It is administered by [System Operators](system-operators.md), with additional
support from Solid Project [Administrators](administrators). System Operators
are appointed by the Solid Director.
