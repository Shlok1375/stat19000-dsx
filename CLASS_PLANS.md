# Data Science Through Experimentation - Class-by-Class Prep

Each entry below assumes a 75-minute class period and includes: the objective, a rough timing
breakdown, materials needed, and what the instructor needs to prep beforehand. This document is
a working plan and will be refined as the course develops; it exists to show that every session
has a concrete run-of-show, not just a topic label.

---

## Class 1: Course Introduction & Orientation (Tue, Jan 12)
**Objective:** Set expectations, build buy-in, remove first-day anxiety.
**Timing:** Welcome and why this course exists (15 min) / Syllabus, grading, AI policy walk-through (15 min) / Icebreaker: two truths and a data lie (20 min) / Preview of Class 2's coin activity, no spoilers (10 min) / Q&A (15 min)
**Materials:** Syllabus handout, slide deck, icebreaker prompts
**Instructor Prep:** Finalize slide deck; prepare icebreaker prompt cards; confirm Brightspace shell is live

## Class 2: The Coin Flip That Wasn't Fair (Thu, Jan 14)
**Objective:** Create the "aha" moment that hooks students on the course's core idea.
**Timing:** Setup and rules (10 min) / Small-group coin flip trials, some coins secretly weighted (25 min) / Groups present their guesses and reasoning (20 min) / Reveal and debrief: what patterns actually gave it away (20 min)
**Materials:** Weighted and fair coins (enough sets for small groups), recording sheets
**Instructor Prep:** Acquire/weight coins in advance; test weighting produces a detectable but non-obvious skew; print recording sheets

## Class 3: What Makes a Question Answerable (Tue, Jan 19)
**Objective:** Teach the difference between an interesting question and an answerable one.
**Timing:** Examples of vague vs. answerable questions (15 min) / Guided practice reshaping vague questions (25 min) / Intro to the semester's shared practice dataset (20 min) / Preview Thursday's workshop (15 min)
**Materials:** Slide deck with example questions, shared class dataset
**Instructor Prep:** Select and lightly clean the shared practice dataset; prepare 8 to 10 example questions of varying quality

## Class 4: Speed-Dating Question Workshop (Thu, Jan 21)
**Objective:** Sharpen individual questions through rapid peer feedback.
**Timing:** Explain format (5 min) / Rotation 1: pitch to 3 classmates, 2 min each (20 min) / Revise (10 min) / Rotation 2: repeat with new partners (20 min) / Share best revisions with class (20 min)
**Materials:** Timer, pitch feedback cards
**Instructor Prep:** Print feedback cards; plan rotation logistics for class size

## Class 5: Intro to EDA in Python (Tue, Jan 26)
**Objective:** Reinforce existing Python skills applied to real exploratory analysis.
**Timing:** Live-coded pandas walkthrough (30 min) / Guided practice on shared dataset (30 min) / Discuss what EDA can and can't tell you (15 min)
**Materials:** Jupyter/Colab notebook template, shared dataset
**Instructor Prep:** Build and test the starter notebook; confirm Colab access for all students

## Class 6: Cold Dataset Challenge (Thu, Jan 28)
**Objective:** Practice EDA under time pressure on an unfamiliar dataset.
**Timing:** Reveal dataset, explain challenge (5 min) / Team exploration sprint (30 min) / Teams present one real finding and one "looked interesting but isn't" (30 min) / Debrief (10 min)
**Materials:** A new, previously unseen dataset per team
**Instructor Prep:** Select and clean a fresh dataset with at least one genuine finding and one plausible red herring

## Class 7: Confounding, Explained Through Absurd Examples (Tue, Feb 2)
**Objective:** Build intuition for confounding through memorable, ridiculous real correlations.
**Timing:** Warm-up with 3 to 4 absurd spurious correlations (15 min) / Explain the mechanism (20 min) / Guided practice identifying confounders in new examples (25 min) / Wrap-up (15 min)
**Materials:** Slide deck of spurious correlation examples
**Instructor Prep:** Curate examples; prepare 4 to 5 new practice cases with a clear confounder

## Class 8: Spot the Confounder (Thu, Feb 4)
**Objective:** Reinforce confounding identification through competition.
**Timing:** Explain Kahoot format (5 min) / Game rounds using real headlines (40 min) / Debrief the trickiest rounds (20 min) / Leaderboard and wrap (10 min)
**Materials:** Kahoot (or similar) quiz built in advance, real headline sources
**Instructor Prep:** Build the quiz; source and vet 10 to 12 real headlines with identifiable confounders

## Class 9: Why Before/After Comparisons Mislead (Tue, Feb 9)
**Objective:** Introduce selection effects and regression to the mean.
**Timing:** Motivating example (15 min) / Concept walkthrough (25 min) / Guided practice (20 min) / Preview Thursday's debate topics (15 min)
**Materials:** Slide deck, 2 real "before/after" claims for Thursday
**Instructor Prep:** Select and prep two debatable before/after claims with real data behind them

## Class 10: The Before/After Debate (Thu, Feb 11)
**Objective:** Apply the week's concepts under debate pressure.
**Timing:** Assign teams and sides (5 min) / Prep time (15 min) / Debate 1 (15 min) / Debate 2 (15 min) / Class vote and reveal (15 min) / Debrief (10 min)
**Materials:** Debate prompt handouts, timer
**Instructor Prep:** Finalize debate prompts and the "reveal" data for each

## Class 11: What a Hypothesis Test Actually Answers (Tue, Feb 16)
**Objective:** Build intuition for hypothesis testing via simulation, not formulas.
**Timing:** Motivating question (10 min) / Simulation walkthrough in Python (30 min) / Guided practice (25 min) / Wrap-up (10 min)
**Materials:** Simulation notebook template
**Instructor Prep:** Build and test the simulation notebook in advance

## Class 12: Run Your Own Live Experiment (Thu, Feb 18)
**Objective:** Experience the full hypothesis-testing pipeline on data the class generates itself.
**Timing:** Explain the live experiment (10 min) / Run the experiment as a class (20 min) / Analyze the class's own data together (30 min) / Discuss results and surprises (15 min)
**Materials:** Whatever the chosen live experiment requires (e.g., stopwatches, puzzle sheets, music)
**Instructor Prep:** Finalize and pilot-test the experiment design beforehand to confirm it's feasible in-class

## Class 13: What a Confidence Interval Really Means (Tue, Feb 23)
**Objective:** Correct the common misinterpretation of confidence intervals.
**Timing:** Common misconceptions (15 min) / Correct interpretation, taught visually (25 min) / Guided practice reinterpreting real reported intervals (25 min) / Wrap-up (10 min)
**Materials:** Slide deck, real examples of reported confidence intervals from news/studies
**Instructor Prep:** Source 3 to 4 real reported intervals, at least one commonly misreported in media

## Class 14: Guess the Range (Thu, Feb 25)
**Objective:** Practice honest uncertainty estimation.
**Timing:** Explain scoring (5 min) / Estimation rounds on hidden quantities (35 min) / Scoring and leaderboard (15 min) / Debrief on overconfidence (20 min)
**Materials:** Prepared hidden-quantity questions with known true values
**Instructor Prep:** Prepare 8 to 10 quantity-guessing questions with verified true values

## Class 15: Anatomy of a Clean Experiment (Tue, Mar 2)
**Objective:** Teach the core components of valid experimental design.
**Timing:** What can go wrong without control/randomization (15 min) / Core concepts (25 min) / Guided practice designing a simple experiment (25 min) / Preview Thursday's game (10 min)
**Materials:** Slide deck, practice design worksheet
**Instructor Prep:** Prepare worksheet and a model "good" experiment design for reference

## Class 16: Design-a-Flaw Game (Thu, Mar 4)
**Objective:** Reinforce experiment design principles by spotting flaws in others' designs.
**Timing:** Explain game (5 min) / Teams review "finished" flawed designs (25 min) / Teams present the flaw they found (30 min) / Reveal intended flaws and discuss any missed (15 min)
**Materials:** 4 to 5 pre-written flawed experiment designs
**Instructor Prep:** Write flawed designs in advance, each with at least one clear, findable issue

## Class 17: Scoping a Project You Can Actually Finish (Tue, Mar 9)
**Objective:** Prevent overly ambitious or vague capstone proposals.
**Timing:** What makes a good capstone scope (15 min) / Examples of well-scoped vs. poorly-scoped past projects (20 min) / Individual scoping worksheet time with instructor circulating (30 min) / Wrap-up (10 min)
**Materials:** Scoping worksheet, example project list
**Instructor Prep:** Prepare example projects (can be hypothetical for a first offering); prepare scoping worksheet

## Class 18: Rapid-Fire Proposal Pitches (Thu, Mar 11)
**Objective:** Force clarity through time pressure before the proposal deadline.
**Timing:** Explain format (5 min) / Pitches, 2 min each plus 1 min feedback (roughly 50 min depending on class size) / Wrap-up and final proposal reminders (10 min)
**Materials:** Timer, sign-up order
**Instructor Prep:** Set pitch order in advance; prepare quick feedback prompts for instructor use

*Milestone: Capstone proposal due by end of week.*

## Class 19: Open Lab, Part 1 (Tue, Mar 23)
**Objective:** Dedicated build time with support.
**Timing:** Quick check-in on proposal status (10 min) / Open work time with instructor circulating (55 min) / End-of-class status share (10 min)
**Materials:** None beyond student laptops
**Instructor Prep:** Review all submitted proposals beforehand to anticipate where students will get stuck

## Class 20: Open Lab, Part 2 / Troubleshooting Clinic (Thu, Mar 25)
**Objective:** Address common real-data problems as a group.
**Timing:** Common problems mini-lesson (missing data, outliers, small samples) (20 min) / Open work time (45 min) / Wrap-up (10 min)
**Materials:** Slide deck of common data problems and quick fixes
**Instructor Prep:** Prepare mini-lesson based on issues observed in Class 19

## Class 21: How AI Reasons About Statistics, and Where It Fails (Tue, Mar 30)
**Objective:** Set up the AI Jury assignment with concrete failure examples.
**Timing:** Examples of AI statistical reasoning errors (25 min) / Discussion: why these happen (20 min) / Explain jury assignment logistics (15 min) / Assign juries and cases (15 min)
**Materials:** Pre-generated flawed AI analyses (one per jury), jury assignment sheet
**Instructor Prep:** Generate and vet several flawed AI analyses in advance, matched to datasets students have seen

## Class 22: AI Jury Trials (Thu, Apr 1)
**Objective:** Apply critical evaluation skills under a fun, structured format.
**Timing:** Jury deliberation time (25 min) / Trials: each jury presents its verdict and reasoning (35 min) / Instructor reveal of intended flaws (15 min)
**Materials:** Jury case materials from Class 21
**Instructor Prep:** Prepare "judge's notes" on the intended flaws in each case for the reveal

## Class 23: Open Lab, Part 3 (Tue, Apr 6)
**Objective:** Continued build time ahead of peer review.
**Timing:** Status check-in (10 min) / Open work time (55 min) / Prep for peer review format (10 min)
**Materials:** None beyond student laptops
**Instructor Prep:** Review progress; identify students who may need extra support before peer review

## Class 24: Peer Review Speed Rounds (Thu, Apr 8)
**Objective:** Give every student structured, useful feedback before finalizing their capstone.
**Timing:** Explain format and rubric (10 min) / Review round 1 (25 min) / Review round 2 (25 min) / Debrief on common feedback themes (15 min)
**Materials:** Peer review rubric/checklist
**Instructor Prep:** Finalize peer review rubric; plan pairing/rotation logistics

## Class 25: Explaining Results Without Jargon (Tue, Apr 13)
**Objective:** Teach clear communication of statistical findings to non-technical audiences.
**Timing:** Examples of jargon-heavy vs. clear explanations (20 min) / Guided practice rewriting jargon-heavy summaries (30 min) / Preview Thursday's lightning round (10 min) / Wrap-up (15 min)
**Materials:** Slide deck with before/after explanation examples
**Instructor Prep:** Prepare jargon-heavy example summaries and their clear rewrites

## Class 26: Explain It to a Freshman, Lightning Round (Thu, Apr 15)
**Objective:** Practice concise, jargon-free explanation under time pressure.
**Timing:** Explain format (5 min) / Lightning rounds, 90 sec per person (roughly 45 to 55 min depending on class size) / Wrap-up and final capstone reminders (15 min)
**Materials:** Timer
**Instructor Prep:** Set speaking order in advance

*Milestone: Final capstone analysis due by end of week.*

## Class 27: Presentation Skills Workshop (Tue, Apr 20)
**Objective:** Teach structure and delivery for the capstone showcase.
**Timing:** What makes a presentation land (20 min) / Model presentation walkthrough (20 min) / Individual outline time with instructor circulating (25 min) / Wrap-up (10 min)
**Materials:** Slide deck, presentation outline template
**Instructor Prep:** Prepare or find a strong model presentation example to walk through

## Class 28: Dry-Run Gauntlet (Thu, Apr 22)
**Objective:** Stress-test presentations before the real showcase.
**Timing:** Explain hot-seat format (5 min) / Dry runs with rotating panel questions (60 min, depending on class size) / Wrap-up and final notes (10 min)
**Materials:** Timer, hot-seat question prompts
**Instructor Prep:** Prepare a bank of challenging but fair hot-seat questions

## Class 29: Capstone Showcase, Part 1 (Tue, Apr 27)
**Objective:** First half of final presentations.
**Timing:** Presentations, roughly 6 min each including Q&A (full period, presenter count dependent)
**Materials:** Presentation equipment, scoring rubric
**Instructor Prep:** Finalize presentation order; invite guests (TAs, faculty) if desired

## Class 30: Capstone Showcase, Part 2, and Course Wrap-Up (Thu, Apr 29)
**Objective:** Conclude presentations and close the semester's throughline.
**Timing:** Remaining presentations (roughly 45 to 55 min) / Course wrap-up and reflection, from Class 2's coin flip to today (15 min) / Final Q&A and course feedback (10 min)
**Materials:** Presentation equipment, course feedback form
**Instructor Prep:** Prepare closing reflection remarks; finalize course feedback form
