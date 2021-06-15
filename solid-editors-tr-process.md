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
different purpose and dynamic. In some cases, the consensus is already
sufficiently clear to enter the drafting phase, in which a formal text
is drafted. In most cases, consensus has not yet been reached, and so
a consensus-building phase is required. It is not necessarily a good
idea to rush into a drafting phase, as a formal text is harder to
write than an informal text that is sufficient for reaching
consensus. In some cases, consensus cannot be reached because the use
cases and requirements are unclear, in which a formal Use Cases and
Requirements (UCR) phase is needed before the consensus process can
progress. That the need for a UCR phase is identified can happen
before or within the consensus phase. Sometimes, the issue is unclear
because there is insufficient implementation experience or doubts as
to the long-term scalability of the proposal, in which case an
assessment phase is needed.

Moreover, this process does not replace the process for submitting and
deciding upon issues, it mainly guides how and when Solid Editors will
engage certain issues and rally support for resolution within a given
time frame.

In the following, the phases are sorted by shortest path to
completion. Mature issues may be ready to enter the drafting phase
immediately, and so they have a quick route to be finished. In other
cases, an issue may arise from the consensus or earlier in the UCR
phase. As such, it differs from a conventional software development
process that usually starts with a UCR phase. The following figure
describes this in more detail:

![Phases of the Solid Editors Process](solid-editors-tr-phases.svg)


### Description of the Phases

For an issue to be considered by the Editors, it must have been
submitted [according to the process](https://github.com/solid/process#drafting-proposals), 
but for now the Editors scope will be limited to issues in the
[specification repository](https://github.com/solid/specification). 
Often, individual issues are often a part of a larger problem space or
feature set, and so, Editors may decide to group them.

#### Drafting Phase

##### Purpose

Produce a GitHub Pull Request to incorporate a formal text into a
specification.

##### Entry 

An issue can enter drafting phase if any of the following are met:

* A rough consensus has been recorded on an issue or a set of issues. 
* A Solid Editor has deemed that the prior experience on the issue is
  sufficient, in particular by existing implementations,
  that drafting can begin.


##### Exit

* An issue exits the drafting phase successfully once it has passed
  the [review process](https://github.com/solid/process#reviewing-proposals).
* If the draft is met with significant opposition, it can exit
  unsuccessfully through mechanisms detailed in 
  [Actions if rough consensus cannot be reached](#actions-if-rough-consensus-cannot-be-reached)
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
  1. That significant discussion has happened in the community
     on the issue on GitHub already.
  2. An overall estimation of the position of the issue in the
     dependency tree of the overall ecosystem.
  3. A commitment of resources to its resolution by actors in
     the community.

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
the discussion. This includes summarizing different viewpoints,
seeking to identify contentious points that can be discussed in
separate issues, open such issues if appropriate, schedule
higher-bandwidth conversations and recruit reviewers.

#### Use Cases and Requirements phase

##### Purpose

Clarify expectations for how a certain feature will be used in
practice.

##### Entry

* Community members may start a standardization process by offering an
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

* Editors will review the discussion in the consensus phase to see whether 
  community members have voiced reservations that need further assessment. 
  Editors will record a comment that details what open question needs to
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
  like a scheduled video conference.
* Editors should actively seek consensus on subissues, and see if
  consensus can be recorded on these and new issues opened for the
  subissues.
* Editors should assess where disagreement stems from. 
   * An issue may exit unsuccessfully and be moved back to the backlog
     if disagreement stems from e.g. insufficient implementation
     experience or performance considerations. 
   * If use cases or requirements are unclear and disagreements stem
     from this, then Editors should exit the current phase and enter
     a UCR phase. 
* Ultimately, some issues will need to be decided in a face-to-face
  meeting, as only that format can provide sufficient emotional and
  conversational bandwidth.
  
## Within monthly cycles

Solid Editors will maintain a monthly cycle.

### Nomination

The cycle begins with Editors nominating issues registered with Github
for consideration for the different phases within the following
cycle. The community should comment on whether they think entrance
criteria are met as stipulated by the Editors. The community should
also commit resources to help resolve the issues within the phases. As
the community commits resources, they may also timebox their efforts
and therefore set due dates for the resolution of issues.

A summary of the selected issues should be written for a technical
audience that does not follow the work closely.

### Weekly Assessment

Solid Editors will convene weekly to assess the progress, and may in
that meeting rephase issues depending on the progress, as well as
discuss using the measures detailed in the above process.

### End of Month

Solid Editors will convene at the end of the month to review the
achievements of the last month. The Editors will also attempt to
conclude on issues that have not yet been resolved in the consensus
phase.

A summary of the last month’s achievements should be written for a
non-technical audience showing the potential benefit for users,
organizations and developers. 
