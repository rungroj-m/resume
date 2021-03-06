---
title: Automated identification of on-hold self-admitted technical debt
publication_types:
  - "1"
authors:
  - Rungroj Maipradit
  - Bin Lin
  - Csaba Nagy
  - Gabriele Bavota
  - Michele Lanza
  - Hideaki Hata
  - Kenichi Matsumoto
author_notes: []
doi: 10.1109/SCAM51674.2020.00011
publication: IEEE 20th International Working Conference on Source Code Analysis
  and Manipulation
publication_short: SCAM 2020
abstract: >
  Modern software is developed under considerable time pressure, which implies
  that developers more often than not have to resort to compromises when it
  comes to code that is well written and code that just does the job. This has
  led over the past decades to the concept of “technical debt”, a short-term
  hack that potentially generates long-term maintenance problems. Self-admitted
  technical debt (SATD) is a particular form of technical debt: developers
  consciously perform the hack but also document it in the code by adding
  comments as a reminder (or as an admission of guilt). We focus on a specific
  type of SATD, namely “On-hold” SATD, in which developers document in their
  comments the need to halt an implementation task due to conditions outside of
  their scope of work (e.g., an open issue must be closed before a function can
  be implemented).We present an approach, based on regular expressions and
  machine learning, which is able to detect issues referenced in code comments,
  and to automatically classify the detected instances as either “On-hold” (the
  issue is referenced to indicate the need to wait for its resolution before
  completing a task), or as “cross-reference”, (the issue is referenced to
  document the code, for example to explain the rationale behind an
  implementation choice). Our approach also mines the issue tracker of the
  projects to check if the On-hold SATD instances are “superfluous” and can be
  removed (i.e., the referenced issue has been closed, but the SATD is still in
  the code). Our evaluation confirms that our approach can indeed identify
  relevant instances of On-hold SATD. We illustrate its usefulness by
  identifying superfluous On-hold SATD instances in open source projects as
  confirmed by the original developers.
draft: false
featured: false
image:
  filename: ""
  focal_point: ""
  preview_only: false
date: 2020-09-01T00:00:00.000Z
---
