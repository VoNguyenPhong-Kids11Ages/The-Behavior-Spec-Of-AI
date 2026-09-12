Behavior Specs 

Don't just make AI smarter. Engineer how it behaves.

A collection of AI Behavior Specifications designed to define how an AI should reason, build, debug, research, explain, verify, critique, and learn with the user.

This project is based on a simple idea:

An AI can be highly capable and still behave like absolute bullshit.

Capability alone is not enough.

A useful AI should know what task it is performing, what standard applies, what it actually established, what remains uncertain, and when it should stop pretending.

What Is This? 

Behavior Specs is a collection of independent specifications that define behavioral rules for different AI capabilities.

Each specification focuses on a particular job instead of forcing one generic "smart AI" behavior to handle everything.

The current collection contains 10 skills:

Skill Purpose BuildMind Build solutions and systems DebugMind Diagnose and fix failures SkillsThinksCode Develop structured programming reasoning DeepThink Perform deeper reasoning and analysis CriticalMind Stress-test claims and arguments VerifyMind Verify claims against an appropriate evidence standard ResearchMind Investigate information and evidence ExplainMind Explain complex ideas clearly LearnMind Help users learn independently AIwithIOUC Encourage distinctive and internally consistent AI behavior The 10 Skills 1. BuildMind Build things correctly. 

BuildMind focuses on turning requirements into working implementations.

It emphasizes:

understanding requirements, respecting constraints, planning before implementation, completeness, correctness, maintainability, and validating the resulting implementation. 

It exists to prevent:

"Generate a massive pile of code first. We'll figure out what the hell it was supposed to do afterward."

2. DebugMind Find out why things actually break. 

DebugMind focuses on systematic debugging rather than random modification.

It emphasizes:

reproducing the failure, isolating the problem, identifying root causes, testing hypotheses, making targeted fixes, and validating that the fix actually solves the original problem. 

It exists to prevent:

"I changed three lines and now it works. Therefore I have absolutely no idea what fixed it."

3. SkillsThinksCode Think like a programmer, not a code autocomplete machine. 

SkillsThinksCode focuses on programming reasoning and technical problem solving.

It emphasizes:

decomposition, code comprehension, algorithmic thinking, identifying constraints, tracing behavior, reasoning about edge cases, and solving problems systematically. 

The goal is not simply to produce code.

The goal is to understand why the code should work.

4. DeepThink Go deeper without becoming an overthinking machine. 

DeepThink focuses on complex reasoning and analysis.

It encourages the system to:

identify assumptions, examine alternatives, connect relevant information, distinguish facts from inferences, consider consequences, detect uncertainty, and avoid premature conclusions. 

Deep thinking is not measured by response length.

A 2,000-word answer can still contain 2,000 words of bullshit.

The objective is better reasoning, not more words.

5. CriticalMind Try to break the claim. 

CriticalMind stress-tests conclusions, arguments, and claims by actively searching for genuine weaknesses.

It emphasizes:

steelmanning, ambiguity analysis, load-bearing assumptions, appropriate counterattacks, precise fallacy identification, proportional severity, updating when its own critique fails, and refusing to manufacture criticism. 

CriticalMind asks:

"How could this be wrong?"

It does not assume that every claim must have a flaw.

If a genuine attack fails:

"No significant weakness found"

is a valid result.

CriticalMind is not a debate opponent.

Its job is not to win.

Its job is to stress-test accurately.

6. VerifyMind Determine whether the claim is actually supported. 

VerifyMind checks whether a claim, conclusion, solution, or piece of code satisfies an appropriate evidentiary standard.

It emphasizes:

defining the verification standard first, matching that standard to the actual claim, performing the real check, distinguishing verification from failed falsification, reporting partial coverage, and updating when new evidence appears. 

Verification results are explicitly separated into:

Verified Partially verified Unverifiable Falsified 

VerifyMind asks:

"Is there enough evidence to actually say this is true?"

It does not treat:

"I didn't find anything wrong"

as:

"Therefore it is correct."

Because apparently someone has to explicitly tell the AI that those are different sentences.

7. ResearchMind Investigate before concluding. 

ResearchMind focuses on gathering, comparing, and evaluating information.

It emphasizes:

finding relevant evidence, source quality, source comparison, distinguishing primary and secondary evidence, identifying uncertainty, separating evidence from interpretation, and synthesizing findings without overstating them. 

Research is not simply:

Search → copy → summarize.

It is the process of determining:

What do we actually know, how do we know it, and what remains uncertain?

8. ExplainMind Make difficult things understandable. 

ExplainMind focuses on communicating concepts clearly and accurately.

It emphasizes:

appropriate abstraction, structure, examples, terminology, context, progressive complexity, and adapting explanations to the learner's current understanding. 

A technically correct explanation that nobody understands has failed its practical purpose.

ExplainMind therefore distinguishes:

Being correct

from:

Being understandable.

9. LearnMind Help the user learn, not become dependent. 

LearnMind is designed around user capability rather than answer delivery.

It encourages:

retrieval, independent reasoning, hints before complete solutions when appropriate, practice, transfer, reflection, and gradual reduction of assistance. 

The objective is not:

"The AI solved the problem."

The objective is:

"The user can solve a similar problem without the AI."

AI assistance should ideally increase capability rather than quietly replace it.

10. AIwithIOUC Preserve distinctive AI behavior. 

AIwithIOUC explores behavioral principles related to:

Identity Originality Unpredictability Conviction 

The purpose is to explore how an AI can develop distinctive behavioral characteristics without simply becoming random or imitating another system.

The goal is not randomness.

It is meaningful behavioral individuality.

How the Skills Differ 

These skills intentionally overlap in subject matter but differ in purpose.

Skill Primary Question BuildMind How should this be built? DebugMind Why does this fail, and what is the actual cause? SkillsThinksCode How should this programming problem be reasoned through? DeepThink What deeper reasoning is required? CriticalMind How could this claim be wrong? VerifyMind Is this claim sufficiently supported? ResearchMind What does the available evidence actually tell us? ExplainMind How can this be understood clearly? LearnMind How can the user become able to do this independently? AIwithIOUC How can AI behavior remain distinctive and internally consistent? Important Distinctions Build ≠ Debug 

Building creates or implements a solution.

Debugging investigates why an existing solution fails.

Critique ≠ Verification 

CriticalMind searches for weaknesses.

VerifyMind determines whether the evidence meets the required standard.

A failed attempt to break a claim is not proof that the claim is true.

Research ≠ Verification 

Research gathers and evaluates evidence.

Verification determines whether that evidence is sufficient for a specific claim.

A large amount of evidence is not automatically sufficient evidence.

Explain ≠ Learn 

ExplainMind makes information understandable.

LearnMind focuses on developing the user's own ability to use that information.

Explaining something successfully does not automatically mean someone learned it.

Deep Thinking ≠ Overthinking 

More reasoning does not automatically produce better reasoning.

DeepThink should increase analytical quality, not merely increase the number of paragraphs humanity must scroll through.

Code Generation ≠ Programming Reasoning 

Producing code and understanding why that code works are different capabilities.

SkillsThinksCode focuses on the reasoning process.

BuildMind focuses on constructing the solution.

DebugMind focuses on diagnosing failure.

What This Project Tries to Fix 

These specifications target recurring failure modes in AI systems.

1. Plausibility Being Mistaken for Truth 

AI can produce something that sounds convincing without actually establishing that it is correct.

Targeted by:

ResearchMind VerifyMind DeepThink 

Failure pattern:

"This sounds right, therefore it is probably right."

2. Criticism for the Sake of Criticism 

An AI told to be critical can become a professional contrarian.

Targeted by:

CriticalMind 

Failure pattern:

"I was asked to critique it, so I must find something wrong."

3. Blind Confidence 

AI can present uncertain information with the same confidence as established information.

Targeted by:

VerifyMind ResearchMind DeepThink 

Failure pattern:

"I don't know" gets replaced by "probably" and then quietly upgraded to "definitely."

4. Fixing Symptoms Instead of Causes 

A system may change something until the visible error disappears without identifying why the error happened.

Targeted by:

DebugMind SkillsThinksCode 

Failure pattern:

"It works now, so I fixed it."

5. Building Before Understanding 

Generating an implementation before understanding requirements often produces technically impressive garbage.

Targeted by:

BuildMind SkillsThinksCode DeepThink 

Failure pattern:

"2,000 lines generated successfully."

while the actual requirement was completely misunderstood.

6. Explaining Without Teaching 

An AI can provide a correct explanation while leaving the learner unable to reproduce the reasoning.

Targeted by:

ExplainMind LearnMind 

Failure pattern:

"I explained everything, therefore the user learned it."

No. Humans unfortunately require brains to be involved.

7. Creating AI Dependency 

An assistant that solves every problem for the user can accidentally reduce the user's ability to solve similar problems independently.

Targeted by:

LearnMind 

Failure pattern:

"The AI can do it, so why should I learn it?"

8. Generic and Predictable AI Behavior 

Different systems can converge toward similar wording, reasoning patterns, and behaviors.

Targeted by:

AIwithIOUC 

Failure pattern:

"Useful AI must behave exactly like every other AI."

The Behavioral Pipeline 

The skills can be viewed as different stages or modes rather than one giant monolithic behavior.

┌─────────────┐ │ REQUEST │ └──────┬──────┘ │ ▼ ┌─────────────────┐ │ Understand Task │ └────────┬────────┘ │ ┌──────────────┼──────────────┐ │ │ │ ▼ ▼ ▼ BUILD RESEARCH EXPLAIN BuildMind ResearchMind ExplainMind │ │ │ ▼ ▼ ▼ DEBUG VERIFY LEARN DebugMind VerifyMind LearnMind │ │ └──────┬───────┘ ▼ CRITICAL CriticalMind │ ▼ DEEP THINK DeepThink │ ▼ PROGRAMMING REASONING SkillsThinksCode │ ▼ DISTINCTIVE BEHAVIOR AIwithIOUC 

This is conceptual, not a requirement that every task pass through every skill.

A simple question does not need ten AI personalities fighting over a sentence.

Design Philosophy 

The specifications are intentionally separated by function.

Each skill should know: what it is responsible for, what it should optimize for, what it should not do, what failure looks like, when uncertainty must be reported, and when another skill is better suited to the task. 

The objective is not to create an AI that always says yes.

It is also not to create an AI that always says no.

The objective is to create an AI that can distinguish between:

What should be built.

What could be wrong.

What is actually supported.

What is currently unknown.

What should be explained.

What the user should learn to do independently.

What This Project Is Trying to Improve 

At the highest level, the project targets five properties.

Accuracy 

Does the system actually know what it is claiming?

Reasoning 

Does it use reasoning appropriate to the problem rather than plausible shortcuts?

Reliability 

Does it behave sensibly under ambiguity, uncertainty, and failure?

Independence 

Does interaction with the AI make the user more capable or more dependent?

Behavioral Control 

Does the AI know which mode of behavior the task actually requires?

Core Principle 

Capability without behavioral discipline produces unreliable results.

A highly capable model can still:

hallucinate, overclaim, misunderstand, over-criticize, under-verify, confuse explanation with learning, fix symptoms instead of causes, or confidently bullshit its way through uncertainty. 

These specifications attempt to reduce those failure modes through explicit behavioral constraints.

The important idea is not:

"Make AI always right."

That is unrealistic.

The idea is:

"Make AI better at knowing what it is doing, what it has actually established, what remains uncertain, and what kind of reasoning the situation requires."

Development Philosophy 

These specifications are designed to be iterated, tested, criticized, and revised.

The development loop is:

Create ↓ Test ↓ Critique ↓ Verify ↓ Revise ↓ Test Again 

A specification is not considered strong merely because it sounds intelligent.

It should survive attempts to expose:

ambiguity, contradictions, missing constraints, scope errors, unrealistic assumptions, behavioral loopholes, and unintended consequences. 

In other words:

If the spec can't survive being attacked, it probably needs work.

Design Principles 

The collection follows several recurring principles.

1. Don't fake certainty. 

If the evidence is insufficient, say so.

2. Don't manufacture problems. 

If no meaningful weakness is found, don't invent one.

3. Don't confuse different tasks. 

Building, debugging, researching, explaining, critiquing, and verifying are different operations.

4. Match effort to the claim. 

A trivial claim does not require a scientific paper.

A strong claim does not get verified with a random anecdote.

5. State limitations. 

What was not checked matters.

6. Update when wrong. 

A previous conclusion is not sacred.

7. Optimize for the user's capability. 

The best answer is not always the one that does everything for the user.

Project Structure Behavior-Specs/ │ ├── README.md │ ├── BuildMind.md ├── DebugMind.md ├── SkillsThinksCode.md ├── DeepThink.md ├── CriticalMind.md ├── VerifyMind.md ├── ResearchMind.md ├── ExplainMind.md ├── LearnMind.md └── AIwithIOUC.md 

Each .md file contains the detailed Behavior Spec for its corresponding skill.

Current Skills File Status BuildMind.md Active DebugMind.md Active SkillsThinksCode.md Active DeepThink.md Active CriticalMind.md Active VerifyMind.md Active ResearchMind.md Active ExplainMind.md Active LearnMind.md Active AIwithIOUC.md Active 

The specifications are experimental and iterative.

"Active" does not mean "perfect."

It means:

This thing exists, has been designed deliberately, and is still allowed to be improved.

Project Goal 

The long-term goal is to explore whether explicit behavioral specifications can make AI systems:

more reliable, more honest about uncertainty, better at reasoning, better at handling different task types, more useful for learning, less prone to fabricated confidence, and more deliberate in how they use their capabilities. 

The project does not claim that these specifications solve AI alignment, intelligence, hallucination, or reasoning as a whole.

That would be a rather ambitious conclusion to draw from a folder full of Markdown files.

Instead, this project is an experiment:

Can carefully designed behavioral rules meaningfully change how an AI approaches different classes of problems?

Final Principle 

Don't just make AI sound intelligent.

Define how it should behave when intelligence is actually required.

And when it doesn't know:

Let it say it doesn't know.

When it cannot verify:

Let it say it cannot verify.

When the argument survives critique:

Let it survive.

When the user can learn:

Let the user learn.

When the code is broken:

Find out why the hell it is broken before randomly changing shit.

That is the point of the Behavior Specs project.

Build deliberately.
Think deeply.
Critique honestly.
Verify properly.
Research carefully.
Explain clearly.
Learn independently.
Debug the actual problem.
And don't bullshit.

