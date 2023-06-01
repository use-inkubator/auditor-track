# ink!ubator: Auditor Track

The ink!ubator's Auditor Track is an initiative designed to introduce experienced
auditors in other smart contract ecosystems to ink! and `pallet-contracts` with the
ultimate goal of helping bootstrap a self-sufficient auditing ecosystem.

The Auditor Track is part of the **ink!ubator**, a holistic bounty program with the goal
of furthering the ink! smart contracting ecosystem. This bounty program is funded by the
Polkadot treasury with the support of the community.

The bounty includes Curators from the following Polkadot ecosystem teams:
- [Astar Network](https://astar.network/)
- [Parity](https://www.parity.io/)
- [Phala Network](https://www.phala.network/en/)
- [Brushfam](https://brushfam.io/)
- [Aleph Zero](https://alephzero.org/)

The Auditor Track is only one aspect of the ink!ubator. For more details on the rest of
the initiative see the
[Polkadot Treasury Bounty Proposal](https://polkadot.polkassembly.io/bounty/19).

## Table of Contents
- [Open Questions](#open-questions)
- [Goals](#goals)
- [Non-Goals](#non-goals)
- [Track Overview](#track-overview)
- [Expectations](#expectations-for-participants)
- [Relation to Builder and Grants Tracks](#relation-to-builder-and-grants-tracks)
- [Success Metrics](#success-metrics)
- [Funding Available](#funding-available)
- [Timelines (2023)](#timelines-2023)
- [Guidelines for Curators](#guidelines-for-curators)

## Open Questions
- What risks are auditing teams concerned with when entering a new ecosystem?
    - What are ways we can help out in mitigating them?
- What do we need to provide in terms of educational materials and technical support to
  get auditing teams up to speed with ink! and `pallet-contracts`?
- What deliverables can we have the auditing teams produce which will: help reinforce the
  concepts they're learning, as well as produce a basin of knowledge for the
  ink!cosystem.
- What can we do to help set teams up for sustainable businesses around auditing in the
  ink! ecosystem?

## Goals
- Teach experienced smart contract auditors about ink! and `pallet-contracts`
- Provide non-trivial, low-stakes code for auditors to get familiar with the ecosystem
    - Done through the Builder and Grant tracks
- Provide funding to auditors to ensure that their entry into the ecosystem is
  financially viable
- Produce a basin of knowledge around smart contract security for the community

## Non-Goals
- To be a bootcamp for non-auditors to become auditors
    - The funding allocated towards something like this could shift in the future, but as
      it stands we only want experienced auditors coming through

## Track Overview
- Teams apply to become part of the Auditor Track
- The Curators will pick one or two teams to join
- Developers from Curator-affiliated teams will work closely with auditing teams to get
  them up to speed with ink! and `pallet-contracts`
    - Concurrently, audit teams should produce security related materials which can be
      beneficial to the ecosystem
    - Concurrently, teams in the Builder and Grants tracks are working on contracts
- Once Builder and Grant contracts are ready, an auditor team (or maybe both, depending
  on funding available) from the cohort will review contracts
- Auditor teams share their review reports publicly

## Expectations for Participants
- Teams will be expected to create educational content related to smart contract security
    - The medium is flexible, as long as it's free, accessible, and high quality
- Teams will be expected to perform code reviews and auditors for teams in other tracks
  of the ink!ubator
    - Any learnings and findings should be made public

## Relation to Builder and Grants Tracks
- Auditors will provide reviews or audits to teams going through the Builder and Grant
  tracks

## Success Metrics
By the end of 2023 we should have:
- Two teams which are technically capable to audit production grade smart contracts
- Publicly accessible learning resources around security in ink!
    - E.g: A web search for "ink contract security best practices" should return blogs,
      videos, etc.

## Funding Available
- Around $500k USD for the first cohort
- This may be for audits of the Builder and Grants tracks, as well as for audit related
  activities
    - Audit related activities could be: building tooling or producing educational
      materials
- Rough Breakdown:
    - $50k-100k per Builder Track Team (x2)
    - $50k-100k per Grants Track Team (x5)
    - Spend of $75k/project * 7 projects = $525k

## Timelines (2023)
- End of March: ink!ubator website live
    - Marketing campaign can begin
- Early/Mid April: Review applications for Builder and Grant tracks
- Mid/Late April: Start working with Builder and Grant teams
    - Concurrently, start working with auditors to get them up to speed with ink!
- June/July/August: Builder and Grant teams have contracts which are ready for review
    - Concurrently: Auditor teams start reviewing contracts

## Guidelines for Curators

This section contains a set of rough guidelines on how the Curators should approach
decision making related to the Auditor Track. This isn't meant to be prescriptive, so use
your judgement when making decisions.

Teams going through any of the tracks of the ink!ubator may also find these guidelines
useful.

### Funding

**_What is the budget of the Auditor Track?_**

As of this writing, it is roughly $500k USD. See the [Funding Available](#funding-available)
section for a breakdown.

This is subject to change as the program progresses. This includes the current cohort, as
well as any future cohorts (since we'll need to ask the Polkadot Treasury for more
funding at that point).

The number of audits as well as the cost per audit is subject to change based off things
like: project complexity, negotiated audit rate, number of quality projects, etc.

**_How will auditing rates be negotiated?_**

The Curators will be the ones responsible for negotiating a rate for an audit.

However, this process will necessarily involve all parties.

As Curators we will need to negotiate a rough rate (e.g cost per audit week) with the
auditors ahead of time. We will also want to communicate our budget with auditors to make
sure that everybody's expectations are aligned.

The Curators will need to make sure that Builder and Grant teams are in light
communication with auditing teams during their development process. This is to ensure
that they are producing code which is in an auditable state. If teams produce code that
is of low quality, or otherwise difficult to audit, they **should not** receive funding
for an audit.

By keeping the auditors in communication with the development teams they will be able to
give the Curators a more accurate quote for an audit.

Curators will then negotiate with the auditors on a project-by-project basis. They should
make sure that the audits fit the rough budget from earlier, that the timelines for an
audit are reasonable, the scope of the audit makes sense, etc.

In order to make sure that an audit fits into our budget and timeline there are some
knobs that you may want to play around with:
- Scope of the audit
    - Make sure to identify key or interesting components worth of an audit, don't just
      blanket audit everything
- Number of auditors
    - Do we _need_ four auditors looking over a simple contract?
- Number of audit days
    - Can we compromise on how long the audit will take, trading off technical depth?
- Expectations surrounding an audit report 
    - Does a report _need_ to be written, or are GitHub issues with vulnerabilities enough?

Make sure to talk with the auditing teams to see what other solutions can be arranged. We
are all working towards the same goals here.

**_How should payments to auditors be made?_**

Auditors typically expect a portion up front and a portion afterwards. We can follow this
model, or choose to pay everything afterwards.

Before coming to a decision on this we should discuss with the auditing team to see what
their terms typically are.

We should also be consistent between teams in the auditor track (e.g pay both teams in a
portioned way, or pay both in a lump sum).

**_How will we pair auditors to projects?_**

Tbh, it's still a bit unclear how the auditor to project pairings will be done. However,
there are a few things we need to keep in mind while figuring this out:
- Pairing should be done at the discretion of the Curators, **not** project teams
- We need to ensure that the teams in the Auditor track get roughly equal payout at the
  end of it all
- We need to make sure that we don't overextend ourselves budget wise

**_How many projects will we pay to audit?_**

This will depend on the cohort, but we want to pay for as many projects as the budget
will allow.

One of the goals of the Auditor track is to have auditors look at as much code as
possible, so if we can afford to pay for an audit we should try and do it.

Once we run out of funds it's time for a new cohort (so a new group of Builder, Auditor,
and Grant track projects).

### Expectations for Project Teams

**_What do we expect from teams receiving an audit?_**

We expect that any team which receives an audit to:
- Be concious of the time they are receiving with the auditors
- Follow all best practices pre-audit to make sure that the audit process is smooth
- Make a reasonable effort to address any issues brought up in the audit

**_Will milestone payouts be withheld if teams don't fix audit issues?_**

No, this doesn't seem fair. While we do expect teams to at least make an effort to
address issues, they are free to mark everything as "won't fix" and move on.

The rational here is that we are already getting value by using their codebase as a
training ground for auditors.

That said though, there is a lot of potential learning to be had from the back and forth
between project teams and auditors. For example, discussing why a certain issue is or
isn't considered high severity can lead to both sides learning something interesting.

**_Should we pay project teams for the time they spend fixing audit issues?_**

No. They are receiving a free audit, so it seems fair that they would spend their own
time to fix any issues raised.
