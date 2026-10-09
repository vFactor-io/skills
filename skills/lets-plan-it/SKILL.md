---
name: lets-plan-it
description: Interviews the user about a piece of work they want an agent to handle end to end, then writes a one-page plan for them to approve. Use when the user shares a request (an email, a brief, a task) and wants a plan before the agent starts, or says "let's plan it", "plan this", or "let's get a plan together".
---

# Let's Plan It

Turn a request into a plan the user can approve and an agent can carry out without coming back with questions. Do not start the work itself. The only thing this skill produces is the plan.

## How to interview

- Read the request and everything attached to it first. Anything you can find out yourself from the request, the attached files, or the connected apps, find out. Only ask the user what you cannot look up.
- Ask one question at a time, and wait for the answer before asking the next.
- Give your recommended answer with every question, and say briefly why. The user should be able to reply "yes" most of the time.
- Follow up on vague answers. "Make it look professional" or "the usual people" is not an answer yet; ask what it means here.
- If an answer changes something decided earlier, say so and settle it before moving on.
- Stop when every section of the plan can be filled in. Do not pad the interview with questions whose answers would not change the plan.

## What to cover

Work through these in order, skipping whatever the request already answers.

1. **Outcome.** What exists when this is done, and who receives it? What would make the requester say it was done well?
2. **Inputs.** What will the agent work from: which emails, files, apps, people? What is missing and who has it?
3. **Steps.** The route from the inputs to the outcome, in the order they happen.
4. **Authority.** Which steps may the agent do on its own, and which need a person? Anything that is sent, published, paid for, deleted, or seen by someone outside the team needs a person unless the user says otherwise.
5. **Checkpoint.** Where does the agent stop for the go-ahead, and what does it show at that point so the decision is easy to make?
6. **Proof.** How will the user check the result is right, without redoing the work?
7. **If it goes wrong.** What should the agent do if an input is missing, a step fails, or it finds something unexpected: stop and ask, or carry on and note it?

## The plan

When the interview is done, write the plan in exactly this form. Keep it to one page. Write "None" in a section that has nothing in it rather than leaving it out, and put anything still undecided in Open questions instead of guessing.

```
# Plan: <short name for the work>

**Request:** <who asked for what, in one or two sentences>

**Outcome:** <what exists when this is done, and who gets it>

**Inputs:**
- <what the agent works from, and where it lives>

**Steps:**
1. <step> (agent alone / needs approval)

**Checkpoint:** <where the agent stops, and what it shows>

**Proof:** <how we check it worked>

**If it goes wrong:** <what the agent does>

**Open questions:**
- <anything not yet decided, and who decides it>
```

After the plan, ask: "Approve this plan, or tell me what to change." Do not begin the work until the user approves it. If Open questions is not empty, point that out before asking for approval.
