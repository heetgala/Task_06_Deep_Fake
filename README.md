Lacrosse Dataset Deep Fake Video Project
1. Objective

The goal of this project was to take insights from an Lacrosse matches dataset and transform them into a short, AI-generated “deep fake” style interview video. I used Google Flow (Labs) to create cinematic interview clips where a news anchor asks questions and a Lacrosse coach provides data-driven answers.


2. Workflow

Narrative to Script

I wrote interview-style dialogues with an anchor and a coach.

Example: “Coach, which team grabbed the most Player of the Match awards this season?” → “One side led the way with 11 awards, showing their high-impact performers.”

Video Creation in Google Flow

Input the script as text prompts.

Used “Anchor in studio” + “Coach with chart/graphic” as scene instructions.

Added overlays like “6 Wins Chasing” or “11 Awards”.

Policy Challenges

Flow flagged some scripts because they included real player or team names.

Solution: Rephrased scripts to use neutral terms like “one side” or “star performer”.

7-Second Limit

Flow automatically rendered most clips at around 7 seconds.

To adapt, I trimmed scripts into short, punchy Q&A segments.

Example: Anchor asks in one line, Coach answers in one line (total ≈7s).

Post-Production Option

To make longer videos, I exported multiple 7-second clips and planned to stitch them together in a free editor like DaVinci Resolve or CapCut.

3. Challenges & Learnings


Length Restriction: Each generated video capped around 7 seconds. Needed to break analysis into micro-clips.

Scene Design: Flow responded better when I clearly described scenes (“Anchor in studio with logo”, “Coach with chart animation”).

4. Final Outcome

Created multiple 7-second interview clips covering dataset insights.

Clips can be stitched together to form a highlight reel (1–2 minutes).

Each video clearly labels as “AI-Generated Data Insights” to maintain transparency.

5. Future Improvements

Explore chaining multiple scenes in Flow if extended length becomes available.

Automate subtitle generation with Whisper for accessibility.

Experiment with external editors to build a complete news-show style episode.
