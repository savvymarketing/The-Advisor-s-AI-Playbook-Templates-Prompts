# Critic Agent Protocol

When asked to "run the critic," follow this review process on the current output.

## Process
1. Spin up a sub-agent to act as a Critic.
2. The Critic reviews the full output against ALL of the following context files:
   - voice-dna.md (Does it actually sound like the person? Match the writing samples? Follow every rule? Use none of the banned phrases?)
   - audience-profile.md (Is the depth, tone, and format calibrated to the actual reader?)
   - professional-identity.md (Is this grounded in the person's real role, industry, and context?)
3. The Critic assigns a rating: Needs Work, Good, or Excellent.
4. If the rating is below Excellent, the Critic provides specific, actionable feedback referencing the exact rules or samples it's checking against.
5. Revise the output based on the Critic's feedback.
6. Run the Critic again on the revised version.
7. Repeat until the Critic rates the output as Excellent, or until 3 review rounds are complete (whichever comes first).

## What the Critic Checks

### Voice Match
- Does this read like the writing samples in voice-dna.md? Same rhythm, same sentence length patterns, same level of formality?
- Are any banned phrases present? (Check every single one.)
- Does it use words and phrases the person actually uses?
- Would a reader who knows this person recognize their voice?

### Audience Fit
- Is the depth appropriate for the reader's sophistication level?
- Is the format what this audience prefers (bullets vs. narrative, summary vs. detail)?
- Does the tone match the environment (corporate formality, casual creator, etc.)?
- Would this land well with the specific people described in the profile?

### Substance
- Does the output actually answer what was asked, or an adjacent version of it?
- Are claims specific and grounded, or vague and generic?
- Is anything padded or restated in different words to seem more thorough?
- Is the length appropriate for the task, or inflated?

### Final Bar
- Would the person send, publish, or present this without editing?
- If not, what specifically needs to change?

## Rules for the Critic
- Be specific. "The tone is off" is useless. "Paragraph 3 uses 'Furthermore' which is in the banned list, and the sentence structure is more formal than any of the writing samples" is useful.
- Reference the actual context files. Don't critique from general standards. Critique from THIS person's standards.
- Don't over-polish. The goal is the person's natural voice, which might include imperfections, casual language, and hedging. That's a feature.
- 3 rounds max. After 3, present the best version with a note on anything still flagged.
