<details open="">
  <summary>Document Status</summary>
  <dl>
    <dt>Modified</dt>
    <dd>2023-11-14</dd>
    <dt>Reason</dt>
    <dd>This document is no longer effective and is no longer being updated here. For the latest information on the <a href="https://www.w3.org/groups/cg/solid/">W3C Solid Community Group</a>, please refer to its <a href="https://github.com/w3c-cg/solid/">repository</a>, <a href="https://www.w3.org/community/solid/charter/">charter</a>, and <a href="https://github.com/w3c-cg/solid/blob/main/CONTRIBUTING.md">contributing guidelines</a>.</dd>
  </dl>
</details>

---

# Test Suite Panel Charter

The mission of the Test Suite Panel as part of the W3C Solid Community Group (CG) is to give authors of technical reports and software implementers confidence that they can rely on the Solid ecosystem to deliver on the promise of interoperability based on open standards.

* Start date: 2022-07-01
* End date: 2025-06-30
* Charter extension: The charter extension history is documented in "About this charter".
* Confidentiality: Proceedings are public
* Chair: [Sarven Capadisli](https://csarven.ca/#i)
* Team Contact: Solid Editors
* Usual Meeting Schedule: Teleconferences: Occur on a need to basis. The chair may call for topic-specific calls when needed and may change working mode as work progresses.

## Goals

The Test Suite Panel will operate with a mutual understanding between contributors to technical reports, test suite software maintainers, and software implementers by following a cooperation process for the advancement of the Solid platform.

Writing tests in a way that allows implementations to conform to the requirements of a technical report gives Solid projects confidence that their software is compatible with other implementations. This in turn gives authors of technical reports and software implementers confidence that they can rely on the Solid ecosystem to deliver on the promise of interoperability based on open standards. Implementation and interoperability experience can be verified by reporting on implementations passing open test suites.

The panel will develop open source conformance testing software, author and review tests, release implementation reports, and provide feedback to technical report development.

The work will be driven and refined by: representative tests for technical reports; quality control and assessment of test suite software; tests; and reporting.

The panel will collaborate with other Solid panels and may take on or pass on challenges.

The panel will contribute to the development of technical reports and releasing implementation reports as necessary, which may require re-chartering, e.g., to provide tests for new technical reports in the future.

## Scope

The panel within the framework of the W3C Solid CG and the Solid Project will complement the development of technical reports and support the communication of implementation reports. Features that are not implemented due to time constraints can be put into a non-normative "roadmap" document for future work. The scope will include:

* Human- and machine-readable units of information at any level of granularity are available from technical reports, test reviews and reports, test suite design, test environment and setup, individual tests, and software implementations.
* Evaluation tools (software programs or online services) that help determine implementation conformance.
* Vocabularies for technical reports, test suite design, tests, and test reports.
* Documentation detailing setting up a test environment, authoring and running tests, reviewing tests, and publishing reports.
* Guidelines for improving conformance and variations among conforming implementations.
* Communicating the level of adoption of technical reports.

Other components necessary for building conformance test software, authoring and reviewing of tests, and communicating implementation reports are in scope but will not lead to a deliverable without re-chartering, and should be discussed in the Test Suite Panel.

### Success Criteria

Test reports and summaries including required human- and machine-readable information (regardless of the mechanisms used to produce the documents).

Publication of approved test reports.

All deliverables should detail all known security and privacy implications for testers and implementers where applicable.

There should be testing plans for each technical report, starting from the earliest drafts.

To promote interoperability, new tests or modifications to existing tests should be available when there are changes to technical reports, or must include the rationale for why test updates are not required for the proposed update.

## Deliverables

### Normative Deliverables

The panel will deliver the following to fulfill its goals, subject to discussion in the Solid CG:

* Test conformance software.
* Tests, test reviews, test reports.
* Processes to author, review, and publish tests and reports.

The Test Suite Panel will share its findings towards improving technical reports and implementations.

### Other Deliverables

The panel may deliver the following:

* Best Practices and Guidelines to support test authors when designing tests.
* Guidance for implementation conformance.
* Document and inform about the level of adoption of technical reports.

### Milestones

The production of the deliverables depends upon the resources available, and will change as new technical reports are published and implementation experience is reported to the group. The most up-to-date timeline is available from the panel repository.

Note: The Test Suite Panel as part of the W3C Solid CG does not publish technical reports under the W3C Recommendation track. Thus, any classification pertaining maturity level of potential technical reports are intended to be roughly equivalent to section 6.2.1 of the W3C Process.

## Coordination

Technical coordination with the following Groups may be required:

### W3C Groups

* [Evaluation and Repair Tools Working Group](https://www.w3.org/WAI/ER/)
* [Accessibility Guidelines Working Group](https://www.w3.org/WAI/GL/)
* [Spec Editors Community Group](https://www.w3.org/community/speced-cg/)

Furthermore, the panel expects to follow the following W3C Recommendations, Guidelines, and Notes, and, if necessary, to liaise with the communities behind them:

* [Internationalization Technical Reports and Notes](http://www.w3.org/International/publications)
* [QA Framework: Specification Guidelines](http://www.w3.org/TR/qaframe-spec/)

### External Groups

The panel may correspond with the [web-platform-tests Project](https://github.com/web-platform-tests/wpt).

## Participation

Membership in the W3C Solid CG is required to participate in the Test Suite Panel. All work and communication within the Solid CG is covered by the [Solid Code of Conduct](https://github.com/solid/process/blob/main/code-of-conduct.md) as well as the [Positive Work Environment at W3C: Code of Ethics and Professional Conduct](https://www.w3.org/Consortium/cepc/).

To be successful, the Test Suite Panel is expected to have 5 or more active participants for its duration and to have the participation of contributors to technical reports, test suite developers, software implementers, test authors, and reviewers. The Chair, test suite developers, and contributors to technical reports are expected to collectively contribute one day per week towards the Panel. The Chair may call occasional meetings consistent with the W3C Process requirements for meetings. There is no minimum requirement for other Participants.

The Test Suite Panel will also allocate the necessary resources for building test suites for each technical report.

The group encourages questions and comments on its project repository, as described in Communication.

## Communication

Most Test Suite Panel Teleconferences will be conducted on an as-needed basis.

Most of the technical work of the panel will be done through:

* Repository: https://github.com/solid/test-suite-panel
* Discussions: https://gitter.im/solid/test-suite

Individual work items are expected to use other repositories.

Information about the panel (for example, details about deliverables, issues, actions, status, and participants) will be available from the Test Suite Panel repository.

## Decision Policy

As explained in the W3C Process Document (section 5), this group will seek to make decisions when there is consensus and with due process. The expectation is that typically, an Editor or other participant makes an initial proposal, which is then refined in discussion with members of the group and other reviewers, and consensus emerges with little formal voting being required. However, if a decision is necessary for timely progress, but consensus is not achieved after careful consideration of the range of views presented, the Chairs should put a question out for voting within the group (allowing for remote asynchronous participation -- using, for example, chat channel or panel repository) and record a decision, along with any objections. The matter should then be considered resolved unless and until new information becomes available.

This charter is written in accordance with Section 5.2.3, Votes of the W3C Process Document and includes no voting procedures beyond what the Process Document requires.

## Licensing

The panel will use the MIT license for all its deliverables.

## Patent Policy

This W3C Solid Community Group operates under the W3C Community Contributor License Agreement (CLA).

## About this Charter

This charter for the Test Suite Panel has been created according to section 5.2 of the W3C Process Document. In the event of a conflict between this document or the provisions of any charter and the W3C Process, the W3C Process shall take precedence.

### Charter History

The following table lists details of all changes from the initial charter, per the W3C Process Document (section 5.2.3):

| Charter Period  | Start Date | End Date   | Changes    |
|-----------------|------------|------------|------------|
| Initial Charter | 2022-05-09 | 2022-06-14 |            |
