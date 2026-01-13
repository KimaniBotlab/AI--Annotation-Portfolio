# Annotator Rating Rubric - Sentiment Classification

## Evaluation Criteria

1. **Label Accuracy**
   - Pass: Labels match gold standard with clear justification.
   - Partial: Minor inconsistency, mostly correct.
   - Fail: Labels frequently conflict with guidelines.

2. **Guideline Consistency**
   - Pass: All labels follow mini-guidelines precisely.
   - Partial: Occasional deviation without extreme error.
   - Fail: Personal interpretation overrides rules.

3. **Handling Sarcasm**
   - Pass: Sarcasm detected and labeled correctly.
   - Partial: Some sarcasm missed.
   - Fail: Sarcasm consistently mis-labeled.

4. **Ambiguity Management**
   - Pass: Ambiguous text flagged or labeled neutral per guideline.
   - Partial: Occasional guessing.
   - Fail: Guesses dominate, no justification.

5. **Use of Neutral Label**
   - Pass: Neutral used correctly for informational or balanced content.
   - Partial: Overused in some cases.
   - Fail: Ignored or misapplied consistently.

## Common Failure Patterns
- Overusing Positive or Negative for unclear cases.
- Ignoring sarcasm or edge-case context.
- Mixing personal opinion with label decision.
- Prioritizing speed over accuracy or justification.

## Reviewer Notes
- QA reviewers focus on reasoning, not just label.  
- Clear notes on ambiguous cases and guideline adherence are the strongest signal.  
- The portfolio is scored as “production-ready” if ≥90% labels align with guidelines and edge cases are correctly flagged.
