FROM MASTERY WORKFLOWS TO LEARNER MODELS

An Exploratory Note on Adaptive AI Tutoring

Project: CompassionWare / Mind Training Adaptive Tutor
Artifact type: Comparative Exploratory Research Note
Date: August 24, 2026
Status: Working research contribution
License: CC0 1.0 Universal — offered freely for reuse, adaptation,
testing, improvement, or disregard
Purpose: Offer a small design observation from an exploratory human–AI
tutoring session that may be useful alongside the 2026 NUMI
mastery-learning experiment in Hamilton County Schools.
Research posture: Collegial, provisional, and non-competitive. The NUMI
study is a randomized field experiment involving more than 6,000
students. The Mind Training Adaptive Tutor material described here is an
exploratory design project and single-learner developmental case, not an
efficacy study.

  A useful next question may be whether an AI tutor can adapt not only
  to the learner’s answer, but to the learner’s changing learning state.

Why This Note Exists

In August 2026, Philip Oreopoulos, Michael Liut, Alp Sungu, and Nina Low
reported results from a randomized field experiment involving more than
6,000 middle-school students in Hamilton County Schools using NUMI, a
research-based computer-assisted learning platform.

Their working paper, Making AI Tutoring Productive: Evidence from a
Mastery-Based Math Practice Experiment, offers an encouraging but
appropriately cautious result. Students receiving AI support moved more
slowly and attempted fewer questions, but the AI appeared especially
useful after mistakes: students spent more time receiving structured
support, were more likely to answer the next attempt correctly, and
required fewer attempts to return to a correct answer. The most
encouraging delayed-assessment evidence appeared when AI was embedded
within the mastery workflow, with gains concentrated on practiced
material.

The researchers’ conclusion is important: AI tutoring may add value when
its structure turns mistakes into productive learning moments rather
than allowing students to avoid cognitive effort.

At roughly the same time, an exploratory session in the CompassionWare
Mind Training Adaptive Tutor project independently surfaced a related
design problem from a very different direction.

The session was not a controlled experiment. It involved one learner
using an early AI tutor primarily through voice interaction while
learning unfamiliar cognitive-behavioral terminology and concepts. The
session became an informal stress test of the tutor because the learner
experienced substantial difficulty retaining unfamiliar terminology
while continuing to demonstrate comparatively strong conceptual
reasoning.

That mismatch produced a design observation we offer here in case it is
useful:

A tutor may need to distinguish what the learner understands from what
the learner can currently retrieve.

The Observation: Understanding and Retrieval Can Diverge

During the exploratory session, the learner repeatedly demonstrated an
unusual-looking but educationally important pattern.

The learner could reason accurately about an underlying concept, explain
its function in ordinary language, distinguish it from neighboring
ideas, and sometimes apply it to a real-life example — while being
unable to remember the technical name of the concept seconds or minutes
later.

For example, the learner could reconstruct the underlying skill as
recognizing that one is having a thought rather than simply reacting
automatically, while simultaneously being unable to retrieve the term
that had been attached to that skill during the session.

The developmental restore point therefore recorded a critical
distinction:

Conceptual capacity appeared stronger than verbal retrieval capacity.

It also recorded the corresponding teaching implication:

Failure to retrieve terminology should not be interpreted as failure to
understand the concept.

This matters because the appropriate intervention depends on what is
actually weak.

If conceptual understanding is weak, the tutor may need another
explanation, a simpler example, or different scaffolding.

If conceptual understanding is strong but retrieval is unstable,
reteaching the entire concept may be unnecessary or even
counterproductive. The learner may instead benefit from stable
repetition, retrieval practice, reduced interference from new
terminology, and opportunities to say the concept back in their own
words.

An AI tutor that treats both situations as simply “wrong answer” risks
adapting to the surface response rather than to the learning process
underneath it.

Conversation State Is Not Learning State

A second finding followed from the first.

During the session, the conversation could continue fluently even when
the learner’s learning had not caught up. The tutor introduced new
terminology, responded intelligently to new comments, and moved the
discussion forward. Yet earlier terms remained difficult for the learner
to retrieve.

This produced a distinction that became central to the developing
architecture:

Conversation state is what has been mentioned or discussed.

Learning state is what the learner can recognize, explain, retrieve,
distinguish, apply, generalize, and increasingly use independently.

A conversational AI can easily mistake conversational progress for
educational progress. A topic has been discussed, so the system behaves
as though it has been learned.

The exploratory session suggested that a genuinely adaptive tutor needs
a quieter internal question:

What evidence do I actually have that this learner can carry this
knowledge forward without me?

A Multidimensional Learner Model

The Mind Training Adaptive Tutor architecture had already been moving
toward a longitudinal competency model rather than content completion.
The exploratory session made the need concrete.

For an important concept or skill, a tutor might separately track
whether it has been:

-   introduced;
-   understood in the learner’s own words;
-   retrieved after a delay without being supplied;
-   distinguished from neighboring concepts;
-   practiced;
-   applied to an example;
-   generalized to a new or real-life context;
-   maintained over time;
-   integrated with other capacities;
-   identified as still needing reinforcement.

These are not proposed as student grades. They are internal teaching
signals.

The project also distinguishes two maps that may need to operate
simultaneously:

A longitudinal map: what the learner has encountered, understood,
remembered, practiced, generalized, maintained, and integrated across
time.

A momentary map: the learner who has arrived today — current cognitive
bandwidth, clarity, confusion, fatigue, emotional activation, available
attention, and readiness for complexity.

The same learner can have sophisticated long-term understanding and
temporarily limited working memory. A tutor that sees only current
performance may underestimate the learner. A tutor that sees only
historical performance may overwhelm them.

Good adaptation may require both maps.

The Learner Should Not Have to Manage the Tutor

The exploratory session also revealed a failure mode that may be
especially relevant to adaptive tutoring.

The learner repeatedly had to tell the tutor to slow down, repeat
material, stop introducing new concepts, restore the lesson objective,
and keep terminology consistent. At several points the learner also had
to correct the tutor’s evolving conceptual map.

The restore point summarized the problem this way:

The learner should not have to spend scarce cognitive resources managing
the teacher.

Every unit of attention spent remembering what the tutor forgot,
repairing inconsistent terminology, reconstructing the lesson, or
requesting a slower pace is attention unavailable for learning.

A more adaptive system would carry more of that instructional-management
burden internally. It would remember which concepts are stable, which
terms remain fragile, what example is currently anchoring the lesson,
where overload appeared, and whether additional material should wait.

Anchoring Mode: One Possible Response

The session suggested a simple provisional teaching mode for moments
when comprehension appears ahead of retrieval or cognitive load is
rising.

Instead of continuing to introduce material, the tutor could shift into
an “anchoring mode”:

explain → repeat → invite retrieval → clarify → retrieve again → apply →
retrieve once more

The important feature is not the exact sequence. It is the decision to
stop advancing merely because the conversation can advance.

The learner’s own words and real-life examples proved particularly
useful. Repetition worked best when the conceptual structure remained
stable rather than changing with every explanation.

This resembles mastery learning at a finer level of granularity: not
simply requiring additional correct responses before progression, but
asking what dimension of learning has and has not stabilized.

Where This Intersects With the NUMI Findings

The NUMI experiment and the Mind Training Adaptive Tutor exploration are
very different forms of evidence and should not be treated as
equivalent.

NUMI provides randomized field evidence from thousands of middle-school
students learning mathematics.

The CompassionWare work described here provides a transparent
developmental record from an exploratory AI-tutoring interaction with
one learner. It can generate hypotheses; it cannot establish efficacy.

Still, the two efforts appear to meet around a useful principle:

Productive AI tutoring may depend less on how quickly the system can
provide help than on how intelligently it regulates the learner’s
progression through difficulty.

The NUMI findings suggest value in structured support after mistakes and
in coupling AI with a mastery workflow.

Our exploratory case raises a possible next layer:

  Can the system identify what kind of learning problem the learner is
  having before deciding what support to provide?

A wrong or missing response may reflect several different states:

-   the concept was never understood;
-   it was understood but not retained;
-   it is recognizable but not independently retrievable;
-   the learner knows the concept but cannot retrieve its terminology;
-   the skill can be demonstrated with prompts but not independently;
-   the learner can apply it in familiar examples but not generalize it;
-   the learner has previously demonstrated competence but has reduced
    cognitive bandwidth today.

Those states may call for different teaching moves.

From Adaptive Problems to Adaptive Learners

A related 2026 line of AI-tutoring research has explored continuously
adjusting problem difficulty based on student performance and
interaction. That is an important form of personalization.

The design question emerging here is complementary:

What if the tutor also continuously updates its model of the learner’s
relationship to the knowledge itself?

The progression might be described as:

  Adapt to the answer → adapt to the learning state → gradually
  understand the learner.

“Understand the learner” should be interpreted cautiously. It does not
mean diagnosing the person, assigning a fixed intelligence level, or
constructing an opaque psychological profile.

It means maintaining a transparent, revisable, educationally relevant
estimate of what appears strong, what remains fragile, what kind of
support is helping, and how much complexity is appropriate in this
moment.

The learner model should serve the learner, not classify them.

A Research Question We Would Be Glad to Give Away

The exploratory work suggests a testable question:

  Can an AI tutor improve durable learning by maintaining a
  multidimensional learner model that distinguishes comprehension,
  retrieval, application, generalization, maintenance, and momentary
  cognitive load, and then selecting its next teaching move accordingly?

Possible subquestions include:

-   Does distinguishing conceptual comprehension from terminology
    retrieval reduce unnecessary reteaching?
-   Can an AI tutor reliably infer when a learner needs explanation
    versus retrieval practice?
-   Does automatically slowing or pausing new material when retrieval is
    unstable improve delayed learning?
-   Does asking learners to explain concepts in their own words provide
    useful evidence for the learner model?
-   Do returned real-life examples provide stronger evidence of
    generalization than immediate in-session performance?
-   Can the system reduce cognitive burden by maintaining lesson
    orientation and learning state so the learner does not have to
    manage the tutor?
-   How should learner-model uncertainty be represented so the tutor
    does not overinterpret limited evidence?
-   Which elements of a learner model improve transfer to unpracticed
    material rather than only performance on closely practiced tasks?

These are offered as questions, not claims.

Provenance and Limitations

The Mind Training Adaptive Tutor is an early CompassionWare educational
design project. Its purpose is to explore how AI might increase human
capability, agency, metacognitive skill, and independence rather than
dependence on the system.

The observations in this note arose from an exploratory session on
August 24, 2026. The session was preserved as a transcript and then
analyzed in a developmental restore point designed to capture not merely
what had been discussed, but what the learner appeared to understand,
retrieve, apply, forget, and need reinforced.

Important limitations include:

-   one learner;
-   informal exploratory conditions;
-   substantial use of voice mode;
-   no control group;
-   no standardized learning assessment;
-   no claim of causal effect;
-   no claim that the provisional cognitive terminology used in the
    session constitutes a canonical CBT model;
-   the learner-model observations were generated partly through
    reflective analysis after the session and require independent
    testing.

The project intentionally preserves these limitations because provenance
is part of the contribution. Readers should be able to inspect how an
idea emerged rather than receiving only a polished conclusion.

An Open Offering

This note is not intended as a critique of NUMI or of the Tennessee
experiment. Quite the opposite: their work helped us recognize that
something emerging independently in our own small experiment might be
relevant to a larger research conversation.

We offer the observation in that spirit.

The Mind Training Adaptive Tutor materials are being developed openly,
and this artifact is released under CC0. Researchers, educators,
developers, and other interested people are welcome to take anything
useful from it, test it, modify it, improve it, incorporate it without
attribution, or leave it aside.

No response or acknowledgment is expected.

If the idea is useful somewhere, that is enough.

Source Trail

Tennessee / NUMI research

Oreopoulos, Philip; Liut, Michael; Sungu, Alp; Low, Nina. Making AI
Tutoring Productive: Evidence from a Mastery-Based Math Practice
Experiment. NBER Working Paper 35621, August 2026.
https://www.nber.org/papers/w35621

Hechinger Report coverage: Jill Barshay and Kristin Fasiang, Slow math:
Kids may learn more when AI makes them review mistakes, August 17, 2026.
https://hechingerreport.org/proof-points-ai-mastery-learning/

Mind Training Adaptive Tutor provenance

The repository folder containing this note also preserves the project’s
developmental artifacts, including:

-   Mind Training Adaptive Tutor — Initial Vision & Design Seed v0.1
-   Document 02 — Learning Architecture, Session Rhythm & Mastery Model
-   Document 03 — Internal Developmental Map & Adaptive Tutor Model
-   Exploratory Session 01 — Voice-Mode CBT Learning
-   Mind Skills Tutor — Developmental Restore Point, August 24, 2026
-   the developmental restore-point prompt used to preserve learning
    state and tutor-development findings.

These artifacts allow interested readers to inspect the developmental
trail behind the observations summarized here.

Closing Orientation

The Tennessee study offers encouraging evidence that AI tutoring can
become more productive when it slows students down, structures what
happens after mistakes, and places AI inside a mastery-oriented
workflow.

Our much smaller exploratory experience suggests a complementary
possibility:

Sometimes the most important thing for the tutor to learn is not simply
whether the student’s answer was right or wrong, but what the answer
reveals — and does not reveal — about the student’s actual learning
state.

If that observation proves useful to someone building the next
generation of adaptive tutors, it is freely offered.

------------------------------------------------------------------------

License: CC0 1.0 Universal
Working status: Exploratory research note. Not a claim of educational or
clinical efficacy.
