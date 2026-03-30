# Scenario Templates

Each template defines: context setup, persona-specific prediction logic, and strategy output format.

---

## Workplace — Collaboration

### deadline-slip
**Setup:** You need to inform [persona] that a deadline will slip by [duration].
**Persona Variables:** conflict_style, stress_response, trust_level, motivation_driver
**Prediction Logic:**
- If D-type + Competing → Immediate blame-seeking, demands alternatives
- If C-type + Avoiding → Silent frustration, passive withdrawal
- If S-type + Accommodating → Accepts but builds resentment
**Output:** Predicted reaction + timing strategy + message draft + follow-up plan

### resource-request
**Setup:** You need [persona] to allocate resources (people/budget/time) to your project.
**Persona Variables:** motivation_driver, decision_style, power_dynamics
**Prediction Logic:**
- If motivated by Recognition → Frame as visibility opportunity
- If motivated by Security → Show low-risk, high-precedent approach
- If motivated by Power → Show how it expands their influence

### cross-team-dependency
**Setup:** Your project depends on [persona]'s team delivering something, and they're not prioritizing it.
**Persona Variables:** conflict_style, motivation_driver, hierarchy_behavior
**Strategy Options:**
1. Direct pressure (works for D-types, backfires for S-types)
2. Create shared accountability (works for C-types)
3. Escalate through mutual management (nuclear option)
4. Make their delivery a visible win for them (works universally)

### scope-change
**Setup:** You need to propose a significant scope change to [persona] who owns the current plan.
**Persona Variables:** openness, conscientiousness, territory_sensitivity
**Prediction Logic:**
- High Openness + Low Territory → Receptive to new ideas
- Low Openness + High Territory → Will resist; needs data and time

---

## Workplace — Conflict

### credit-dispute
**Setup:** [Persona] is claiming credit for work you did (or contributed significantly to).
**Strategy Tiers:**
1. Soft: Create visibility through follow-up documentation
2. Medium: Direct private conversation with specific examples
3. Hard: Escalate to shared management with evidence

### blame-deflection
**Setup:** [Persona] is deflecting blame for a failure onto you or your team.
**Counter-Strategy by Type:**
- Against Blame Shifter: Pre-document the timeline; send "alignment" emails before failures
- Against Political Player: Build alliances before the blame game starts
- Against Micromanager: Over-document your communications and decisions

### territory-invasion
**Setup:** [Persona] is attempting to take over ownership of your project/area.
**Defense Framework:**
1. Stakeholder lock: Ensure key stakeholders identify you as owner
2. Knowledge moat: Be the irreplaceable expert
3. Narrative control: Tell the story of this project to leadership before they do
4. Negotiate terms: If takeover is inevitable, negotiate conditions

### public-disagreement
**Setup:** [Persona] disagrees with you in a group meeting.
**Response by Persona Type:**
- D-type: Don't back down publicly; propose to "take it offline" with data
- I-type: Acknowledge their point, redirect to shared goals
- S-type: Rarely happens; if it does, it's serious — take very seriously
- C-type: Welcome the detail discussion; agree to review data together

---

## Workplace — Career

### promotion-ask
**Setup:** You want [persona] (your manager) to support your promotion.
**Framework:**
1. Build the case before the ask (evidence file)
2. Understand their promotion philosophy (merit vs loyalty vs visibility)
3. Make it easy: provide them the exact talking points they'd use
4. Timing: After a visible win, not during crises

### salary-negotiation
**Setup:** You're negotiating compensation with [persona].
**Persona-Adapted Approach:**
- Data-driven persona: Bring market data, comp surveys, competing offers
- Relationship persona: Frame as long-term partnership investment
- Power persona: Create perceived BATNA (best alternative)

**Deep-Dive: Salary Negotiation Playbook**

*Timing Decision Tree:*
- Company just had layoffs → Wait 6-8 weeks minimum, then frame: "I'm committed to this team. I want to make sure my compensation reflects my expanded role."
- Strong performance review → Strike within 2 weeks while data is fresh
- Budget cycle starting → Get your ask in BEFORE allocations are decided
- Boss is stressed/overwhelmed → Wait for a calm week, not a crisis week

*If Rejected — Recovery Scripts:*
- "I understand. Can we set a specific date to revisit? I'd like to know what milestones would make this possible."
- "If a salary increase isn't possible right now, could we discuss [equity/bonus/title/remote flexibility/conference budget]?"
- "What would need to be true in 6 months for you to say yes?"
- For D-type boss: "I want to make sure we're aligned on what success looks like for this role. Can we define the criteria for the next level?"
- For S-type boss: "I completely understand the constraints. I appreciate you hearing me out. Can I check back in [timeframe]?"

*Brag Sheet Framework:*
1. Revenue/impact: "I [action] which resulted in [measurable outcome]"
2. Scope expansion: "My responsibilities now include [X, Y, Z] which are [level above] responsibilities"
3. Market data: "Comparable roles at [companies] pay [$range]"
4. Retention argument: "Investing in my compensation is more cost-effective than replacement cost"

### skip-level-meeting
**Setup:** You have a meeting with [persona], who is your manager's manager.
**Preparation by Persona Type:**
- D-type skip: Be concise, lead with impact, have specific asks ready
- I-type skip: Be personable, share enthusiasm, connect your work to vision
- C-type skip: Be precise, bring data, show thoroughness

---

## Workplace — Boundary Setting (New Section)

### saying-no-to-boss
**Setup:** Your boss asks you to take on additional work that exceeds your capacity.
**Scripts by Boss Persona:**
- D-type boss: "I can take this on if we deprioritize [X]. Which would you prefer?" (Give them control over the tradeoff)
- I-type boss: "I love the idea! To do it justice, I'd need to move [X] to next sprint. Does that work?"
- S-type boss: "I want to make sure I deliver quality on everything. Can we look at the timeline together?"
- C-type boss: "Here's my current capacity: [list]. Adding this means [specific tradeoff]. What's the priority order?"

### pushing-back-on-deadline
**Setup:** You've been given an unrealistic deadline by [persona].
**Framework:**
1. Acknowledge the urgency (don't dismiss their timeline)
2. Show the scope vs time tradeoff with specifics
3. Offer alternatives: "I can deliver [reduced scope] by [their date] or [full scope] by [realistic date]"
4. For D-types: Be direct about what won't get done, they respect honesty
5. For S-types: Emphasize quality concerns, they care about doing it right

### scope-creep-defense
**Setup:** Your project scope keeps expanding without timeline/resource adjustments.
**Strategy:**
1. Document every scope addition with date and who requested it
2. Create a visible "scope tracker" that shows original vs current
3. Frame to boss: "The project has grown by 40% since kickoff. To maintain quality, we need either [more time/more people/reduced scope]"
4. For political-player requesters: "Happy to add this — just need sign-off from [their boss] on the timeline impact"

### protecting-work-life-balance
**Setup:** [Persona] regularly contacts you outside work hours or expects always-on availability.
**Scripts:**
- Setting the boundary: "I'm most effective during [hours]. I'll respond to after-hours messages first thing the next morning unless it's truly urgent."
- When they ignore it: "I saw your 11pm message and responded first thing this morning. For true emergencies, please text me directly."
- For D-type boundary-crossers: "I want to give you my best work. That means I need to protect my focused hours."
- Cultural layer (Chinese tech): 加班 culture is real; frame boundaries as efficiency, not laziness: "我在休息好的时候效率最高"

### performance-review
**Setup:** You're giving or receiving a performance review with [persona].
**Giving to High-D:** Be direct, specific, future-focused. Don't soften too much.
**Giving to High-S:** Be gentle, acknowledge effort, give time to process.
**Receiving from anyone:** Listen fully before responding; ask for specific examples.

**Deep-Dive: Performance Review Playbook**

*Writing Self-Review Calibrated to Boss Persona:*
- D-type boss reads self-reviews? Lead with impact numbers. "Delivered X, resulting in $Y revenue / Z% improvement." Cut the narrative.
- I-type boss? Tell the story of your wins. Show enthusiasm. Connect to team vision.
- S-type boss? Acknowledge team contributions alongside yours. Show growth trajectory.
- C-type boss? Be precise. Quantify everything. Reference specific metrics and goals.

*Pre-Review Intelligence Gathering:*
- Ask your boss 2 weeks before: "Is there anything specific you'd like me to prepare for our review?" (This reveals what they're planning to discuss)
- Ask peers: "If you were writing my review, what would you highlight?" (This gives you ammunition AND reveals blind spots)

*Handling Negative Feedback by Boss Type:*
- From D-type: Don't get defensive. Say: "I hear you. What does 'good' look like in this area? Give me a specific target."
- From I-type: They'll soften it so much you might miss it. Listen for "one area to consider" = this is important to them.
- From S-type: They'll avoid saying anything harsh. Ask directly: "What's the one thing I should change? I'd rather hear it from you."
- From C-type: They'll have detailed notes. Take them seriously. Say: "Can I have a copy of your notes so I can address each point?"

*Post-Review Follow-Up (within 48 hours):*
Send an email summarizing: (1) Key strengths acknowledged, (2) Areas for growth discussed, (3) Your specific action plan, (4) Timeline for check-in.
This creates a written record and shows proactive follow-through.

---

## Personal — Family

### financial-discussion
**Setup:** You need to discuss a significant financial decision with [persona] (partner/family).
**Framework:**
- Frame as shared goal, not unilateral decision
- Use concrete scenarios, not abstract principles
- Start small (pilot approach) to reduce resistance
- Respect their risk tolerance as valid, not wrong

### parenting-disagreement
**Setup:** You and [persona] disagree on a parenting approach.
**Framework:**
- Focus on the child's outcome, not who's "right"
- Acknowledge what the other approach gets right
- Propose a trial period rather than permanent change
- United front: "Let's decide together, then present together"

### boundary-setting
**Setup:** You need to set a boundary with [persona] (parent/sibling/friend).
**Framework by Attachment Style:**
- Secure: Direct statement, they'll respect it
- Anxious: Reassure the relationship isn't threatened, then state boundary
- Avoidant: Be clear and brief; don't over-explain (they'll withdraw)

---

## Output Format for All Scenarios

```markdown
## Scenario Analysis: [scenario_name]

### Predicted Reaction
Based on [persona]'s profile ([key traits]), they will most likely:
- Immediate reaction: [prediction]
- Within 24 hours: [prediction]
- Long-term pattern: [prediction]
- Confidence: [high/medium/low]

### Recommended Strategy
**Approach: [strategy_label]**
- Timing: [when to act]
- Channel: [how — email, Slack, 1:1, group]
- Framing: [how to position your message]
- Key phrases to use: [specific language]
- Things to avoid: [specific pitfalls]

### Ready-to-Use Script
[Draft message / talking points / email template]

### If It Doesn't Go As Predicted
- Plan B: [alternative approach]
- Escalation path: [when and how to escalate]
- Warning signs: [behaviors that indicate strategy isn't working]
```
