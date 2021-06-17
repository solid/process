# Solid Editors’ Technical Report Development Process

## Introduction

The present document outlines a process in which the [Solid Editors](https://github.com/orgs/solid/teams/editors)
group (hereafter simply “Editors”) intends to operate as a governing
body to improve the speed of Solid Technical Report Development. The
group will operate on a monthly cycle, in which it will process issues
that are already on the Solid roadmap and that have been reported to
the relevant Github repositories. Initially, the scope is limited to
the [specification](https://github.com/solid/specification) repository, 
but it is expected that the scope will be widened.

Editors will recruit contributors, including authors and reviewers,
from the community, in addition to performing some of these roles
themselves as appropriate. Even if a certain phase has a single
assignee, this assignee may be any member of the community, and other
contributors are welcome to assist.

The Editors will examine open issues on a monthly basis, triage and
prioritize them based on feedback from the community and an overall
understanding of the ecosystem, and categorise them into phases
depending on the maturity of the discussion of the issue(s). The Solid
Roadmap influences the issues selected but changing the roadmap is not
in the scope of this process.


## Issue Phases

Open issues may be in one of several phases, and each phase has a
different purpose and dynamic. Sometimes, the consensus is already
sufficiently clear to enter the drafting phase, in which case a formal text
is drafted. In most cases, consensus has not yet been reached, so
a consensus-building phase is required. It is not generally a good
idea to rush into a drafting phase, as a formal text is harder to
write than an informal text that is sufficient for reaching
consensus. In some cases, consensus cannot be reached because the use
cases and requirements are unclear, in which a formal Use Cases and
Requirements (UCR) phase is needed before the consensus process can
progress. Identifying the need for a UCR phase can happen
before or during the consensus phase. Sometimes, the issue is unclear
because there is insufficient implementation experience or doubt of
the long-term scalability of the proposal, in which case an
assessment phase is needed.

This process does not replace the process for submitting and deciding
upon issues; it mainly guides how and when Solid Editors will engage
on certain issues and/or rally support for resolution within a given
time frame.

The phases described below are sorted by shortest path to completion.
Mature issues may be ready to enter the drafting phase immediately,
with a quick route to being finished. In other cases, an issue may
arise during the consensus phase, or earlier, in the UCR phase. Thus,
this process differs from a conventional software development process
that usually starts with a UCR phase. The following figure describes
this in more detail:

![Phases of the Solid Editors Process](solid-editors-tr-phases.svg)


### Description of the Phases

For an issue to be considered by the Editors, it must have been
submitted [according to the process](https://github.com/solid/process#drafting-proposals).
For now, the Editors' scope will be limited to issues in the
[specification repository](https://github.com/solid/specification). 
Individual issues are often part of a larger problem space or feature
set; in such case, the Editors may decide to group them.

#### Drafting Phase

##### Purpose

Produce a GitHub Pull Request to incorporate a formal text into a
specification.

##### Entry 

An issue can enter the drafting phase if either of the following is met:

* A rough consensus has been recorded on an issue or a set of issues. 
* A Solid Editor has deemed that the prior experience on the issue,
  particularly by existing implementations, is sufficient for drafting
  to begin.


##### Exit

* An issue exits the drafting phase successfully once it has passed
  the [review process](https://github.com/solid/process#reviewing-proposals).
* If the draft is met with significant opposition, it can exit
  unsuccessfully through mechanisms detailed in 
  [Actions if rough consensus cannot be reached](#actions-if-rough-consensus-cannot-be-reached).
* Solid Editors can decide that a draft can exit successfully or
  unsuccessfully in the end-of-month meeting.

##### Assignee Role

The assignee in the drafting phase is responsible for being the
primary author of the draft.


#### Consensus Phase

##### Purpose

Lead the community to form a rough consensus to resolve an outstanding
issue.

##### Entry

* Solid Editors will decide to enter an issue into the consensus
  phase based on three factors:
  1. How much discussion about the issue has already taken place
     among the community on GitHub
  2. The Editors' overall estimation of the position of the issue
     in the dependency tree of the overall ecosystem
  3. The commitment of resources made to its resolution by actors
     in the community

##### Exit

* An issue may successfully exit the consensus phase after an Editor
  records a rough consensus by posting a summary of the consensus in
  an issue comment. If the consensus was reached in a discussion that
  happened outside of the issue comments (e.g., in a face to face
  meeting, a scheduled video chat), the Editor must record the forum
  where the final discussion was held, who was present, and when it
  was decided.
* In some cases, consensus cannot be reached, in which case,
  the issue may have an unsuccessful exit through the mechanisms
  detailed in [Actions if rough consensus cannot be reached](#actions-if-rough-consensus-cannot-be-reached). 

##### Assignee Role

The assignee in the consensus phase is responsible for facilitating
the discussion. This may include summarizing different viewpoints,
seeking to identify contentious points that can be discussed in
separate issues, opening such issues if appropriate, scheduling
higher-bandwidth conversations, and recruiting reviewers, among
other things.

#### Use Cases and Requirements phase

##### Purpose

Clarify expectations for how a certain feature will be used in
practice.

##### Entry

* Community members may start a standardization process by offering a
  UCR document. 
* If rough consensus hasn't been reached in a consensus phase,
  one of the actions that the Editors may take is to [exit the
  consensus phase and enter a UCR phase](#actions-if-rough-consensus-cannot-be-reached) 
  for the issue.
  
##### Exit

* Solid Editors will review suggested requirements and/or use cases
  and decide whether the issue can progress to the next phase.

##### Assignee Role

The assignee in the UCR phase is responsible for compiling and writing
requirements and use cases that are relevant to the issue.

#### Assessment Phase

##### Purpose

Clarify how a suggested feature can be implemented without
compromising the overall quality of the ecosystem.

##### Entry

* Editors will review the discussion of the consensus phase to see whether 
  community members have voiced reservations that need further assessment. 
  Editors will record a comment detailing any open question(s) needing to
  be investigated.

##### Exit

* An issue exits the assessment phase when a comment is posted
  detailing the results of the investigation.

##### Assignee Role

The assignee in the assessment phase is responsible for making an
investigation into the question that has been posted, and writing the
comment listing the investigation details.


## Actions if rough consensus cannot be reached

* Assignee should attempt to convene a higher-bandwidth conversation,
  such as a scheduled video conference.
* Editors should actively seek consensus on subissues, and see if
  consensus can be recorded on these and new issues opened for the
  subissues.
* Editors should assess from whence disagreement has stemmed. 
   * An issue may exit unsuccessfully and be moved back to the backlog
     if disagreement stems from, for instance, insufficient
     implementation experience or performance considerations. 
   * If disagreements stem from a lack of clarity in use cases or
     requirements, then Editors should exit the current phase and
     enter a UCR phase. 
* Ultimately, some issues will need to be decided in face-to-face
  meetings, as only that format can provide sufficient emotional and
  conversational bandwidth.
  
## Within monthly cycles

Solid Editors will maintain a monthly cycle.

### Nomination

The cycle begins with Editors nominating issues from those registered
on Github for consideration for the different phases of the following
cycle. The community will have a comment period during which they may
support or refute whether entrance criteria has been met by each issue
for the relevant phase. During this period, the community is also 
expected to commit resources to help progress the issues through the 
phases. As the community commits resources, they may also timebox their 
efforts and thereby set effective due dates for the resolution or
phase-advance of issues.

A summary of the selected issues will be written, targeting a 
technical audience that does not follow the work closely.

### Weekly Assessment

Solid Editors will convene weekly to assess issue progress, and may in
those meetings re-phase issues depending on their progress, as well as
discuss using the measures detailed in the above process.

### End of Month

Solid Editors will convene monthly to review the achievements of the 
preceding month. The Editors will also attempt to reach conclusion on 
any issues that have not yet been resolved in the consensus phase.

A summary of the latest month’s achievements will be written,
targeting a non-technical audience, explaining the anticipated
benefits for users, organizations, and developers.
