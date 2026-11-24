# The EDA Question Set

*A reader of your EDA should be able to answer every one of these without opening the data file.*

This is the contract for the EDA assignment: your notebook works if a reader — a classmate in the Module 4 class, me at grading time — can answer this whole list using only what you wrote. It's also the seed of your **personal EDA guide**: you'll extend it with dataset-specific questions here (Part 3 of the assignment), and the growing list travels with you throughout the course. If you're doing the Choose Your Own Hypothesis assignment, you'll need to use this file in that work as well.  

## Provenance & scope

1. Where did this data come from — who collected it, how, and why?
2. What does one row represent?
3. How big is it, and what time period / geography / population does it cover?
4. What could this data plausibly generalize to — and what tempting question can it *not* answer?

## Structure & quality

5. What are the important variables, and what type is each (categorical, continuous, datetime, text, ID)?
6. What's missing — and if nothing, how do you know? Completeness is a claim that must be earned: "no missing values (verified)" is real communication work. If something *is* missing, does it have a pattern?
7. Are there duplicates, impossible values, or suspicious encodings (999s, "unknown", mixed units)?
8. What variables did the author create or transform, and why?

## Distributions & relationships

9. What does each key variable look like — shape, center, spread, outliers? *Do this with plots, but then also with words; do the work of interpretation for your audience.*
10. What are the two or three most important relationships in the data, shown and interpreted?
11. What's surprising here — what didn't the author expect to find?

## Readiness

12. If I wanted to run an analysis tomorrow, what would I still have to do to this data?
13. What analyses is this dataset ready to support?

## Your questions (14, 15, …)

Every dataset forces questions this list doesn't ask — datetime quirks, geographic coverage, class imbalance, a weird unit. Add yours at the end of your notebook, numbered and flagged as your own. This is the part of the list that makes it *yours*.
