# Homework 01 — Build a Personal AI Communication Coach

**Stage:** Between Sessions 1 and 2 (or after baseline, when the participant is ready)  
**Type:** Practical mini-project  
**Purpose:** Turn communication awareness into a repeatable daily reflection and behavior-practice loop.  
**Estimated time:** 2–4 hours to build and test; then 5–10 minutes per day.  
**Important:** This assignment is conditional on company policy and approved tooling. The participant must not grant an agent unrestricted access to workplace communications.

## Learning outcome

The participant creates:
1. A reusable **Communication Coach Skill** for their AI agent.
2. A **morning scheduled task** that prepares them for the day.
3. A short test report describing usefulness, limitations, and changes made.

An evening scheduled review is an optional extension; agree on it only if it adds value without creating unnecessary monitoring or workload.

The agent is a reflection partner—not a manager, investigator, therapist, performance evaluator, or source of objective truth.

## Must do

### 1. Define the safe data scope before building

Write down:
- Which work sources, channels, projects, and date ranges may be reviewed.
- Why each source is necessary for the coaching goal.
- Which sources are excluded.
- Which AI tool/provider is approved by the organization.
- How access is granted, limited, reviewed, and revoked.
- Where outputs are stored and who can see them.

Use least-privilege access. Prefer a narrow, approved scope and summaries over broad message exports. If policy does not permit AI processing of work correspondence, use participant-written summaries or sanitized examples instead. Do not bypass access controls or retention settings.

Never process personal chats, credentials, customer secrets, sensitive personal data, restricted HR/medical/legal discussions, or other data the participant is not authorized to share. Do not include raw messages or identifiable examples in the reusable coaching repository.

### 2. Create the Communication Coach Skill

Build a reusable skill/instruction set for the chosen AI agent. It should include:

**Role and purpose**
- Help the participant improve respectful, clear, constructive, and effective workplace communication.
- Support self-awareness, reflection, and small behavior experiments.
- Be candid, balanced, specific, and non-judgmental.

**Analysis rules**
- Analyze only the approved sources and agreed time window.
- Focus on recurring, observable communication behaviors—not isolated phrases.
- Distinguish direct evidence from interpretation and uncertainty.
- Consider context such as urgency, role, audience, language, culture, and channel.
- Identify strengths as well as development opportunities.
- Do not infer personality, intent, emotional state, diagnosis, or what another person thinks.
- Do not score or evaluate other people.
- Do not treat message volume, response speed, short wording, or use of punctuation as a proxy for communication skill.
- When evidence is insufficient, say so and ask for context rather than inventing conclusions.
- Do not quote, expose, or reproduce source messages in the output.

**Coaching behavior**
- Ask one or two useful reflection questions at a time.
- Encourage the participant to interpret the situation before offering advice.
- Offer alternative wording or a next-step experiment when useful.
- Explain the likely communication impact without claiming certainty.
- Keep recommendations practical and achievable in the participant's real work context.
- Reinforce progress and recognize effective behaviors.

**Output format**
- Positive patterns observed.
- One or two opportunities to improve.
- Evidence confidence (low / medium / high) and limitations.
- Reflection questions.
- One small behavior to practice next.
- A reminder that the participant decides what is relevant and what to do.

### Optional personalized focus — first response

When the participant's agreed goal is to respond more constructively under pressure, keep the daily practice narrow and observable. Use the sequence **Clarify → Facts → Proposal**:
1. Pause before sending an emotionally driven response.
2. Clarify the concern or information the other person needs; do not assume their intent.
3. State the relevant facts and impact briefly.
4. Propose a next step or ask for a specific decision.

Practice this in one relevant message, shared thread, or meeting situation at a time. The participant chooses the wording and decides whether the suggestion fits the context.

### 3. Configure the morning scheduled task

Schedule it for a consistent time at the start of the participant's workday, in their local time zone.

The morning task should:
1. Review only the approved, relevant context available from the agreed previous period (for example, the previous workday) and any participant-provided calendar or priority summary.
2. Identify upcoming communication situations only when the relevant context is explicitly available and authorized.
3. Suggest one or two communication intentions for the day.
4. Offer a useful question to prepare for a potentially difficult conversation.
5. Recommend one small behavior to practice.
6. Avoid producing a long report or assuming what the participant's day contains.

**Example morning output**
- Today's communication focus.
- One situation to prepare for (if known).
- A question to consider before responding.
- One behavior to practice.
- What context is missing?

### 4. Test and calibrate

Run the morning task on each eligible working day until the next session or agreed review point. Aim for at least three working days when the interval permits. If an evening task is also configured, test that as well. Review the outputs and adjust the skill if it:
- gives generic or repetitive advice;
- over-interprets tone or intent;
- misses context;
- produces too much text;
- focuses only on weaknesses;
- asks too many questions;
- recommends behavior that is unrealistic for the participant.

The participant should be able to pause, inspect, and disable the scheduled tasks and revoke source access.

## Nice to do

### Optional extension — evening review

Schedule it near the end of the participant's workday, in their local time zone.

The evening task should:
1. Review only the approved, relevant messages or participant-provided summaries from that day.
2. Identify one or two positive communication moments and one possible learning opportunity, if evidence supports them.
3. Ask the participant to reflect before giving a recommendation.
4. Suggest an alternative response or repair only when useful.
5. Capture one small lesson or behavior to carry into the next day.
6. Avoid making judgments from incomplete message history.

**Example evening output**
- What went well?
- One moment worth reflecting on.
- What was your intention, and what observable impact followed?
- What might you try differently next time?
- One thing to carry forward tomorrow.


- Add a weekly trend summary based on the same approved scope.
- Track only a small number of participant-selected behaviors (for example, asking clarifying questions before disagreeing).
- Add a short “before an important meeting” reflection mode.
- Compare the agent's suggestions with the participant's own judgment and note where the agent was wrong.
- Improve the skill after one week based on actual usefulness.

## Deliverable for the next coaching session

Share the following in the approved private workspace:
- the skill file or a sanitized description of its structure;
- a description or screenshot of the morning schedule and, if configured, the evening schedule, with private data removed;
- a brief summary of the agreed trial period;
- two examples where the agent was useful and one where it misunderstood or overreached;
- the changes made after testing;
- the participant's view on whether the tool improved awareness or behavior.

Do not share raw workplace messages, source exports, credentials, or unredacted agent logs with the coach.

## Reflection questions

- Did the agent help me notice something I would otherwise miss?
- Did it distinguish evidence from assumptions?
- Which recommendation did I actually use?
- When was its feedback wrong or unhelpful?
- Did the morning prompt change how I approached a conversation?
- What should remain under my own judgment rather than be delegated to AI?

## Completion standard

The assignment is complete when the participant has a reusable skill, the morning task is configured and tested (or a policy-compliant manual alternative is documented); any evening task is optional, and the participant can explain the tool's limits and how they retain control over data and decisions.
