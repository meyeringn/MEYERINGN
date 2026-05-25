# Lessons Learned — Equitech Futures CTI 2026

This document reflects on what I learned — and
what I'm still figuring out — from the Equitech
Futures Civic Tech Institute 2026 cohort.

I'm writing it publicly because I think civic
tech practitioners should document their learning
the same way they document their code. Openly.
With the bugs included.

---

## What I Came In Thinking

I came into CTI 2026 believing that the main
barrier to good civic tech was technical capacity.
That if we just had better data, better models,
and better tools, cities would make better
decisions for the communities most at risk.

I was partially right and mostly incomplete.

---

## What I Actually Learned

**1. The gap is not usually technical.**

The communities most vulnerable to heat illness,
transit inaccessibility, and climate risk are
not underserved because no one has built a
prediction model yet. They are underserved because
the systems that would use such a model — city
agencies, public health departments, transit
authorities — are under-resourced, risk-averse,
and often structurally resistant to acting on
data that challenges existing resource allocation.

A better model without a path to adoption is
a research paper, not a civic tool.

The hardest part of building SustAInable was not
the XGBoost architecture. It was thinking honestly
about how a city OEM director would actually
encounter this tool at 7am the week before a
heat event — and what would make them use it
rather than the map they already have on the wall.

**2. Explainability is harder than accuracy.**

I spent a lot of time thinking about model
performance metrics — AUC-ROC, recall, F2-Score.
I spent less time than I should have thinking
about what a community health worker in North
Philadelphia would actually do with a SHAP
output summary.

Technical explainability and community
legibility are not the same thing. A model
that can explain itself to another data
scientist has not solved the problem.

**3. Lived experience is a design input,
not a credential.**

I am Disabled. My wife is chronically ill.
I came into this work thinking that my lived
experience was a source of motivation —
something that told me *why* to build these
tools.

What I learned is that it's also a source of
*what* to build and *how*. The specific design
decisions in SustAInable — the asymmetric error
cost framework, the community challenge mechanism,
the decision threshold at 0.30 instead of 0.50 —
came directly from thinking about what it would
mean for a tool like this to fail someone like
me or my wife.

That's not sentiment. That's engineering.

**4. The question I can't fully answer yet:**
How do you build trust with communities that have
every reason not to trust a new data-driven tool
built by someone who doesn't live in the
highest-risk ZIP codes?

My answer so far: you don't build trust.
You show up consistently, you name the limitations
honestly, you build in the ability to be challenged,
and you let trust accumulate over time through
demonstrated accountability.

I don't think there's a technical shortcut to that.

---

## What I'd Do Differently

**I would have talked to more residents sooner.**

I spent the first half of the CTI cohort in
design mode — feature schemas, algorithm selection,
evaluation frameworks. I talked to a lot of people
who work in public health and civic tech.

I should have talked earlier and more often to
people who live in the ZIP codes I'm trying to help.
Not to validate my design decisions. To find out
whether I was asking the right questions at all.

**I would have scoped smaller first.**

SustAInable is designed for national coverage.
UpLift is designed to scale to any transit system
on earth. Those are the right long-term goals.

But the right first question is: can I make this
work for one ZIP code in Philadelphia? Can I make
it work for one elevator at 15th Street Station?

I got excited about scale before I had earned it.

---

## What I'm Still Figuring Out

- How to build a community challenge mechanism
that is meaningful without being gameable
- How to talk to city agencies about piloting
tools that implicitly critique their current
resource allocation
- Whether UpLift and SustAInable are the right
tools, or whether I've fallen in love with
my own solution before fully understanding
the problem
- How to keep building in public when the
work is incomplete and the stakes are real

---

## Why I'm Writing This Here

GitHub is where technical work lives.
Most of the README files on this profile are
about what I built and how it works.

This one is about what I'm still learning.

I think that's worth documenting too.
Especially if I'm asking cities, communities,
and fellowship programs to trust me with
problems that matter.

---

**Nico Meyering, MPA** · Philadelphia, PA
meyeringn@gmail.com ·
[LinkedIn](https://www.linkedin.com/in/nicolasmeyering)

*Chairman, Philadelphia Mayor's Commission on
People with Disabilities*
*VP of Growth & Partnerships, Net Impact Philadelphia*
*Equitech Futures Civic Tech Institute, CTI 2026*
