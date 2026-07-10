# Professor Outreach Value-Add Packet

## Bottom Line

This repository is currently a **research proposal and execution scaffold**, not a completed result. Use it to show Professor Joachims that you understand the research area and can contribute a concrete, reproducible artifact.

## Target Professor

- **Professor:** Thorsten Joachims
- **University:** Cornell University
- **Program:** Computer Science
- **Research area from CSV:** ML, information retrieval, learning-to-rank, SVMs
- **Representative paper from CSV:** Optimizing Search Engines using Clickthrough Data; 2002; KDD
- **Scholar link:** https://scholar.google.com/scholar?q=Optimizing+Search+Engines+using+Clickthrough+Data

## Proposed Value Add

Build **a transparent ranking or recommendation system with user-controllable evidence** focused on **information retrieval**.

### What You Can Contribute

- Add explanation and control mechanisms to a retrieval/recommendation baseline.
- Evaluate whether users or simulated users can correct bad rankings.
- Measure ranking quality, diversity, drift robustness, and explanation usefulness together.

## Concrete Starter Project

Build a BEIR/MovieLens-style baseline and add counterfactual explanations or preference controls with a small evaluation protocol.

## 30/60/90-Day Plan

### First 30 Days

- Re-read 3-5 recent lab papers and write a one-page problem framing memo.
- Build the first dataset or evaluation slice with documented source provenance.
- Reproduce one credible baseline and record exact commands.
- Create a failure bank with at least 20 concrete examples.

### Days 31-60

- Add the proposed method or evaluation contribution.
- Run ablations that isolate the contribution from data scale and model-size effects.
- Add robustness, temporal, domain-shift, or subgroup tests where relevant.
- Write interim results as a short lab-note style report.

### Days 61-90

- Expand the benchmark to 50-100 examples or the equivalent for the domain.
- Run statistical checks, seed variance checks, and cost/runtime analysis.
- Convert results into a paper-style technical report.
- Package the repo so another student can reproduce the main table.

## Deliverables To Offer The Professor

- Baseline ranking system with reproducible metrics.
- Control/explanation module with ablations.
- Preference-drift or counterfactual evaluation.
- Report on quality-control tradeoffs.

## Skills This Demonstrates

IR/recommender evaluation, ranking metrics, explanation design, user-centered protocol design.

## Honest Outreach Framing

Do **not** claim this is finished. The honest claim is:

> I prepared a concrete research scaffold aligned with your work and would like to turn it into a reproducible contribution if it matches your lab's current priorities.

## Sharing Note

This GitHub repository is public. Before emailing, verify the professor's current work, personalize the email, and be ready to explain exactly what is implemented versus planned.
