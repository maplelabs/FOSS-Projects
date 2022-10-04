# Proposing Projects, application, tools, utilities, etc to go as Free / open-source through MapleLabs

## Introduction

Ideas to develop different kinds of software (application, tool, utility, plugin, etc ) with open-source approach through MapleLabs needs to go through the proposal process and only acceped Ideas would be taken up for implementation. 
This document describes the process for proposing an idea.


## The Proposal Process

The proposal process is the process for reviewing a proposal and reaching
a decision about whether to accept or decline the proposal.

1. The proposal author [creates an issue]( https://github.com/maplelabs/FOSS-Proposals/issues/new ) describing the proposal with below sections:
- Proposal description
- Key pain points or opportunity details
- Objective of the proposed project
- Existing alternatives & why I think they are not enough (with links to those projects)
- Ballpark effort estimate ( X engineers for Y Months)
- Expected number of users/organizations of the proposed project (Submit supporting material, if it exists). .\
   
2. A discussion on the issue tracker aims to triage the proposal into one of the four outcomes:
     - Accept proposal, or
     - decline proposal, or
     - ask for more information, or
     - on-hold

   If the proposal is accepted or declined, the process is done.
   Otherwise the discussion is expected to identify concerns that should be addressed.

3. The proposal author may have to write a [detailed proposal doc](#proposal-document) to address the concerns raised in the discussion.

4. Once comments and revisions on the detailed proposal doc wind down, there is a final
   discussion on the issue, to reach one of two outcomes:
    - Accept proposal or
    - decline proposal.

Once the proposal is accepted (whether after step 2 or step 4), implementation of the proposal is initiated.

## Detail

### Definitions

- A **proposal** is a suggestion filed as a GitHub issue
- A **proposal doc** is the expanded form of a proposal, written when the
  proposal needs more explanation and consideration.

### Proposal Document

Some (but not all) proposals need to be elaborated in a proposal document.

- The proposal doc should be checked in to [the proposal repository]( https://github.com/maplelabs/FOSS-Proposals/tree/master/proposal-docs/ ) as `proposal-docs/NNNN-shortname.md`,
where `NNNN` is the GitHub issue number and `shortname` is a short name
(a few dash-separated words at most).

- The proposal doc should follow [the template]( https://github.com/maplelabs/FOSS-Proposals/blob/master/proposal-docs/Template.md ).

- The proposal doc should address any specific concerns raised during the discussion.

- It is possible that the proposal doc may go through multiple checked-in revisions.

### Proposal Review

A group of MapleLabs team members holds “proposal review meetings” to review pending proposals.

The principal goal of the review meeting is to make sure that proposals
are receiving attention from the right people,
by cc'ing relevant stakeholders, raising important questions,
pinging lapsed discussions, and generally trying to guide discussion
toward agreement about the outcome.
The discussion itself is expected to happen on the issue tracker,
so that anyone can take part.

The proposal review meetings also identify issues where
consensus has been reached and the process can be
advanced to the next step (by marking the proposal accepted
or declined or by asking for a proposal doc).

Proposal issues are tracked in the
[FOSS Proposals Dashboard project]( https://github.com/orgs/maplelabs/projects/4/views/1 ).
The current state of the proposal is captured by the columns in that project,
as described below.

## Help

If you need help with this process, please post a question in “help-needed” channel in MapleLabs discord server (https://discord.gg/Dq6CPHB4Fe ).
