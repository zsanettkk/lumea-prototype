# Lumea: Cycle Health Prototype

A mobile app prototype that helps people understand how their symptoms change across the menstrual cycle, and how life events and other people's patterns may relate to them.

## The problem
Cycle trackers log symptoms but rarely explain them. People are left asking "is this normal for this phase?" and "why do my sleep and mood drop together?"

## What it does
The prototype has three tabs:

- **Forecast:** a 28-day cycle strip colour-coded by phase (period, follicular, ovulation, luteal). Tap any day to see confirmed symptoms (cramps, fatigue, mood, bloating) for past days, or predicted symptoms for future days. Predictions are visually distinct (dashed) and labelled as estimates, not clinical forecasts.
- **Explore:** pick a tracked signal (cramps, fatigue, mood, bloating, sleep, energy) and see it plotted across the cycle with confirmed and predicted lines. Compare any two signals to see a short explanation of why they may be linked.
- **History:** a timeline of the current and previous cycle. Users can add life events (such as exams, illness or moving home) and compare their data with an anonymised peer group, filtered by age group and similar life events.

## Design decisions
- Predicted data is always visually separated from confirmed data, so the user never mistakes a guess for a record.
- Explanations are shown alongside the data, so patterns come with context.
- Clear "not medical advice" framing wherever comparisons or explanations appear.

## Scope and honesty
- This is a design prototype. **All data is simulated.** The symptom values, the predictions, and the peer comparison (including the number of cycles shown) are hard-coded examples, not real user data.
- The explanatory text is illustrative and has not been clinically reviewed. It is not medical advice.
- Built with Claude (AI-assisted). I led the product concept, user flows and interaction design.

## Tech
Single-file web app (HTML, CSS and JavaScript). No backend.

## Live demo
https://zsanettkk.github.io/lumea-prototype/
