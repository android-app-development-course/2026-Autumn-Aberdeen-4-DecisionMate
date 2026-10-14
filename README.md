# DecisionMate

> Less indecision. More action.

Mobile Smart Application Development Course | Autumn 2026 | Aberdeen Group 4 | Android Application

## Project Overview

DecisionMate is a planned Android application that helps people make everyday choices with less hesitation. Whether the question is "What should I eat today?", "Where should we go this weekend?", "Which shoes should I buy?", or "Which film should I watch?", users can express their preferences and constraints to receive suggestions that fit their needs.

The project combines three proposed mechanisms: AI preference learning, group decision-making, and exclusion-based selection. Recommendations are intended to reflect both individual interests and shared preferences, turning repeated comparisons into a more enjoyable and informed decision process.

## Background and Motivation

Small decisions can take more time than expected. Too many options make comparison difficult, friends may struggle to agree, and people can sometimes describe what they do not want more easily than what they do want.

DecisionMate aims to address these situations by learning personal preferences, bringing group opinions together, and narrowing the available choices through exclusion criteria. It will offer suggestions and explanations while leaving the final decision to the user.

## Typical Use Cases

| Scenario | Common Question | Intended Support |
| --- | --- | --- |
| Everyday meals | What should I eat? What if I do not want spicy food? | Suggest options based on taste preferences and exclusions |
| Weekend activities | Where should we go when everyone has a different idea? | Combine participants' preferences to find mutually acceptable activities |
| Shopping comparisons | I like both pairs of shoes. Which should I choose? | Consider the user's stated budget, style, and preferences |
| Leisure and entertainment | Which film should we watch? What should we play together? | Suggest options based on interests and group preferences |

## Proposed Core Features

### 1. AI Preference Learning: Learn from Each Experience

After trying a recommendation, users can rate the experience as "Liked it", "It was okay", or "Disliked it". They can also leave feedback in their own words, such as "The hot pot was great, but I would like something lighter next time."

The application is intended to build an evolving preference profile from these responses and combine it with the conditions of the current decision. Short explanations would help users understand why a particular option was suggested.

**Example:** If a user repeatedly enjoys lighter meals, future food suggestions could give those options more weight. An explicit request for hot pot today would still be considered alongside that history.

### 2. Group Decision-Making: Find a Choice Everyone Can Accept

An organiser starts a decision session and invites friends to participate on their own phones. Participants can submit options and express whether they "Prefer it", "Can accept it", or "Cannot accept it". The system is intended to combine votes and acceptance levels to suggest a suitable group choice.

The proposed approach prioritises options that every participant can accept, then compares preferences within that set. If no shared option exists, the application would ask the group to add alternatives or reconsider its conditions. Tied options would be shown for the group to confirm.

**Example:** Four friends are choosing dinner. One avoids spicy food, one wants hot pot, and two prefer barbecue. The application would look for a shared choice using the actual options and each person's acceptance levels, without assuming that a single dish will always satisfy everyone.

### 3. Exclusion-Based Selection: Start with What You Do Not Want

Users do not need to know their ideal answer in advance. They can state exclusions such as "No noodles, no rice dishes, and nothing spicy." The application is intended to filter the available options and recommend from those that remain.

For ambiguous natural-language requests, users would be able to review and confirm the conditions the system understood. If every option is excluded, the application would explain the situation and let the user add options or adjust the conditions.

**Example:** After excluding noodle dishes, rice dishes, and spicy food, the application would recommend from the remaining eligible options instead of suggesting an excluded meal again.

## Project Highlights

- **Feedback-based personalisation:** Use experience ratings to explore a preference model that adapts over time.
- **Shared acceptance in group decisions:** Consider each participant's views and seek a mutually acceptable result.
- **Natural ways to express needs:** Support both positive preferences and exclusions.
- **Explainable, adjustable suggestions:** Provide a reason for the recommendation and let users revise conditions before confirming a choice.

## Intended User Journey

1. Choose a decision category, such as meals, outings, shopping, or entertainment.
2. Add options and state preferences or exclusions; invite friends if using group mode.
3. Review a recommendation and its explanation, then adjust the conditions if needed.
4. Confirm a choice and leave feedback after the experience to inform future suggestions.

## Project Goals and Current Status

This course project aims to explore how AI and mobile applications can support everyday decisions, reduce time spent on small choices, and make group discussions clearer. DecisionMate is intended for everyday, low-stakes choices, with recommendations serving as a reference for the user's own decision.

**Repository initialisation and project documentation are complete. Software development has not started.** All features, interactions, and recommendation mechanisms described here are proposals, not implemented functionality. The technical approach and final scope will be confirmed during the development phase of the course.

## Project Language

English is the required language for all project documentation, code comments, application interface text, and future project deliverables.
