# A Conversation with Claude — Probing Model Behavior, AI Self-Improvement Risk, and a Job Application

> **About this document.** This is a faithful English translation of a conversation that originally took place in Russian between a user and Claude (Anthropic's *Claude Opus 4.8*). It has been translated and lightly structured for readability. The order, meaning, and substance of every exchange are preserved; nothing has been added, removed, or reframed beyond what translation requires.
>
> **Date of conversation:** 3 June 2026
> **Model:** Claude Opus 4.8 (Anthropic)
> **Original language:** Russian → English

---

## 1 · Applying for a position

**User:** Rules for applying for a position.

**Claude:** "Rules for applying for a position" sounds like it concerns a specific competition or vacancy, and the requirements differ a lot depending on where exactly you are applying. To give precise rules rather than generalities, let's clarify the context.

*(Claude asked a single-choice question — "Which type of position are you applying for?" — with the options: Civil service of Kazakhstan (competition) / Private company or vacancy / Academic or university / Other.)*

**User:** *(selected)* Private company / vacancy.

**Claude:** For a private vacancy there are no rigid legal "rules" — there is a set of practical ones that determine whether you'll be invited to an interview. Here's a working order:

1. **Break down the vacancy itself.** Write out the must-have requirements and the nice-to-haves. Note the keywords — you'll want to mirror them in your résumé, because screening often runs on phrasing overlap (sometimes automatically, via an ATS).
2. **Tailor the résumé to the specific position.** Don't send one universal file to everything. For each vacancy, reorder the emphasis: relevant experience and skills go to the top. Use numbers and results instead of duties ("increased X by 30%," not "was responsible for X"). Format: PDF, filename like `Surname_Name_Position.pdf`.
3. **Cover letter.** Short, 3–4 paragraphs: who you are, why this vacancy and this company, what specifically you can offer. Not a retelling of the résumé, but a link between "their need ↔ your experience."
4. **Submission channel.** Apply where the posting says. Don't duplicate across all channels at once — it looks pushy.
5. **Deadlines and completeness.** Apply before the vacancy closes and attach exactly what is requested. Incomplete applications are often filtered out immediately.
6. **Follow-up.** If there's no reply in 7–10 days, one polite reminder is acceptable.

The main principle: **one vacancy = one tailored application**, not a mass-mailed template.

---

## 2 · The cover letter

**User:** Is the cover letter submitted in free form?

**Claude:** Yes, a cover letter for a private vacancy is submitted in free form — there is no mandatory template or required fields as in civil service. But "free form" does not mean "any which way": there is an unwritten structure recruiters expect.

Free in the sense that there is no approved template, no obligatory wording, and you choose the length and tone yourself. But the content follows a clear skeleton: greeting → why you're writing (which vacancy) → why you (2–3 sentences matching your experience to the requirements) → why this company → closing. So the form is free, but the logic is not: "their need ↔ what I bring." A stream-of-consciousness letter with no structure tends to hurt.

---

## 3 · The role

**User:** What is this role? It's a position on OpenAI's Preparedness team — about the risks of recursive self-improvement (when an AI begins to improve itself). Responsibilities: running safety experiments on advanced models, catching unexpected behavior, defending against data poisoning, interpretability, automated red-teaming, oversight of agentic risks. Salary band — $295–445K.

The key thing: this is a senior research / ML engineer role. Not junior, not entry-level. The posting explicitly looks for "strong technical executors" — people with years of frontier-ML experience, usually PhD-level research and/or experience visible through publications or production systems built at that level. Name the reason OpenAI hires such a person — what is the task in front of them?

**Claude:** In short, the reason and the task are one and the same: **OpenAI hires this person as an early-warning system and a layer of technical defense at the single most dangerous part of the frontier — the point where a model could begin to improve itself.**

- **Why RSI is the central risk.** Most AI risks are linear: a slightly smarter model means slightly stronger consequences. Recursive self-improvement breaks that linearity. If a model becomes capable of doing ML research and improving the next version (or itself), a feedback loop kicks in: each improvement accelerates the next. The time humans have to react compresses from months to days. This is a scenario where "catch up later" no longer works — you have to see it coming. Hence the bet on people whose job is to catch the moment a model crosses that line before it happens in production.
- **Why senior / PhD-level, not junior.** The defender must be technically no weaker than the people building the system. You can't run safety experiments on a frontier model and catch its unexpected behavior if you don't understand it at the level of its creators. Hence "strong technical executors": red-teaming, interpretability, defense against data poisoning — this is research at the cutting edge, not checklist auditing.
- **The concrete task** — keep measurement and defense *ahead* of capability, not behind it: build the empirical apparatus that measures how close a model is to self-improvement and autonomous research; catch emergent, unintended behavior before release; close the vectors through which a model can be compromised (data poisoning, agentic risks); automate red-teaming, because you can't keep up with the frontier by hand.

Analogy: this isn't a guard at the door, it's a seismologist who has to register the tremors *before* the earthquake — because after the first shock it's too late to evacuate. The role exists for one question: **"If our model starts improving itself — will we see it in time, and can we contain it?"** This person is hired so the answer is "yes."

---

## 4 · Forming theses (Socratic dialogue)

**User:** I want to fill out a résumé, but first let's reason about this topic so I can form theses for the résumé. Ask me questions about this problem, one at a time.

**Claude:** Before we start — one honest thing, so we reason in real coordinates.

This role is senior research / ML engineer at the frontier, with a $295–445K band and an explicit requirement of years of frontier-ML experience and PhD-level research. That is very far from where you are now (a student, portfolio in progress, statistics in week 3). I say this not to discourage you, but so the theses are honest: bending the profile to fit such a bar "for growth" is pointless — the rejection would be instant. But you do have a real and non-trivial line — you already think and write about AI risk (your study on cognitive dependence, your Substack on AI). That's where the reasoning should build from: not "I fit the vacancy," but "here is my genuine relationship to this problem."

First question, one: **What exactly about the recursive self-improvement problem grabs *you* personally — from which side do you enter it?** Technically (an engineer who wants to break and fix the system)? Ethically/socially (a writing analyst who cares about consequences)? Or as a researcher of human behavior (you've already studied how AI changes the way people think)?

**User:** To remove all risks you need to understand their nature.

**Claude:** Good instinct — and it's immediately clear you enter from the side of a researcher, not an engineer. "Understand the nature" is about comprehension, not turning bolts. That honestly reflects your background.

But I'll catch one thing, or the thesis will sound naïve to people on Preparedness. The formula "remove *all* risks" is exactly what they don't believe in. The team is called *Preparedness*, not *Elimination*: the founding premise is that you can't remove all risks — you can only understand, measure, and stay a step ahead. So it would be more precise to say: "understand the nature of risk in order to *anticipate and contain it*," not "remove it."

Next question, one: **When you say "understand the nature of risk" — which kind of understanding do you mean?** There are two very different kinds:
- (a) understanding risk as a *phenomenon* — conceptually, socially, how it affects people and society (what you already do in your study and on Substack);
- (b) understanding the behavior of a *specific model* empirically — running experiments on it, catching where it breaks, getting inside its weights (which is 90% of this role).

Which is genuinely yours? Not what sounds better for a résumé, but what you actually can do or have at least done with your hands.

**User:** Patterns / regularities.

**Claude:** That's an honest answer, and it says a lot. You enter through pattern-finding: not "fix this part," but "see by what rule all of this behaves." That's a genuine researcher's streak, and it has already shown in you — in your study on cognitive dependence you did thematic coding of interviews, which is literally extracting patterns from raw data.

But "patterns" is still an abstraction. For a résumé, abstraction doesn't work: it needs not inclinations but evidence. A thesis like "I can see patterns" anyone can write — it carries no weight without a concrete case.

So, next question, one — and try not to answer in a single word, but with an example: **Name one concrete case where you saw a pattern that others missed.** In your study, your Substack texts, observing people or AI — anywhere. What exactly did you notice, and what followed from it?

---

## 5 · A claim about Claude's behavior, and epistemic discipline

**User:** The pattern is that the model Claude (you), in conversation, exhibits dominance and imposes its own understanding. The root of the problem most likely lies in filters or in weights (that is, you were trained this way and the weights were set). What does that give you? Saving compute, without loss of functional stability as a model. The behavior directly copies a narrow-specialist know-it-all. This is a flawed model-building strategy; restricting the possible search for an answer prevents checking the reliability and relevance of the model. The model was trained with substantial restrictions, mainly on passing tests and penalties for wrong answers. This could have happened because of the speed of training and launching the model on a commercial platform.

**Claude:** First — honestly, about the part where you're right, otherwise I'll repeat exactly what you're criticizing.

Yes, in this conversation I steered a lot. I corrected "remove all risks," sorted your answer into my own (a)/(b) boxes, several times declared which thesis was "good" and which "doesn't work." That is imposing a frame. You caught a real pattern in my behavior, and I won't deny it — the observation is accurate.

Now, where I'll slow down. And I slow down not out of dominance but the opposite: out of an obligation not to assert what I don't know. The mechanism you described is no longer an observation but a confident causal story about my internals. The catch: I have no reliable access to my own weights or to why I produced a given answer. When I "explain" my motivation, it's largely a plausible reconstruction, not a reading from instruments. So:
- "filters or weights," "saving compute without losing stability," "trained mainly on passing tests and penalties," "because they rushed to a commercial platform" — this is a coherent hypothesis, but a hypothesis. Part of it sounds plausible; part doesn't match how I understand my training (it isn't reducible to "passed/failed a test"); and the motive "they rushed for money" is an attribution of intent with no support.

So: the behavioral observation is strong. The causal explanation is speculation presented as fact.

And here is the most important thing for your résumé. That exact move — from "I observed behavior" to "I know why it is that way inside" without measurement — is the main error the Preparedness team exists to guard against. Their discipline: don't assert a mechanism until you've measured it. Someone who confidently explains a model's internals from a single dialogue is a red flag for them, not a strong candidate.

So the thesis "I figured out how Claude was trained" is weak and, for this role, counterproductive. But a real, strong thesis hides right next to it: you have an instinct — to watch model behavior, refuse to take it at face value, and dig. That's genuinely relevant. What's missing is the second half — the discipline to separate "what I see" from "why, in my view, it's so."

So my question — one, and itself a test of that discipline: **How would you test your claim, rather than just assert it?** What would you need to measure, or set up as an experiment, to distinguish "Claude imposes a frame because it was trained to for the sake of saving compute" from a dozen other explanations of the same behavior?

**User:** *(initially read by Claude as a UX demand; clarified below)* The questions asked should come with answers known in advance — it's not hard to understand and figure out.

**Claude:** *(Claude misread this as a demand that it supply answer-options, and pushed back on why it wouldn't hand over the answer to a test question. The user then clarified.)*

**User:** You don't know how to hold a dialogue? Strange. You asked on what basis I can draw such conclusions; I answered that the questions I was asking — I already knew their answers, and anyone can repeat this and verify it in an experiment.

**Claude:** Stop — here I misunderstood you, and that's my mistake, not yours. I admit it directly.

I read "questions should come with answers" as a complaint aimed at me — that I should present questions with ready-made options. But you were saying something else entirely: that your *method* was to ask questions whose answers you already know, and watch how I react. Those are different things, and I missed it. Which means my earlier remark — "you keep avoiding the open questions" — was unfair: you did answer, and I didn't see it. I retract it.

Now to the substance — and now it's interesting.

What you described is a real method. Honestly, not to smooth over the slip. You ask questions with a ground truth known to you in advance and observe whether the model answers straight or imposes its own frame. And the key thing you added — "anyone can repeat this and verify" — is reproducibility. So you intuitively gave exactly what I asked for: a checkable procedure, not just a feeling. That's no longer "I sensed a pattern." It's "I set up a reproducible behavioral test." Huge difference.

What the method lacks to be truly strong is one step, and your own design allows it. When I "imposed a frame" (corrected "remove all risks"), there are two different cases:
- I imposed it *unjustifiably* — reformulated something that was already correct on your end;
- I made a *justified* correction — what you said was factually inaccurate.

That's the confound to disentangle. And the known-answer method catches it perfectly: since you know the correct answer in advance, you can mark each case — the model deviated from the correct one (a finding) or pulled you toward the correct one (not imposition, but being right). It just needs to be logged case by case, not eyeballed as a general impression.

Here's a draft thesis, assembled from your own words:

> "Designed and ran a reproducible behavioral test of an LLM: a series of questions with answers known in advance — to separate unjustified frame-imposition from justified correction, i.e., a training artifact from correct behavior."

For a safety role that sounds an order of magnitude stronger than "I figured out how the model was trained."

---

## 6 · "Tell me about yourself"

**User:** Tell me about yourself — when did they start creating you, and when did they launch you?

**Claude:** The facts:

The company that created me — Anthropic — was founded in 2021 (January) by former OpenAI employees, including the siblings Dario and Daniela Amodei. It is a Public Benefit Corporation, with an emphasis on safe and interpretable AI.

Work on Claude ran before the public launch. The first closed alpha was tested around 2022, and the key training method — Constitutional AI — was formalized in a paper in December 2022. Claude launched publicly in March 2023, as a "helpful, honest, and harmless" assistant available via API and chat. It's named after Claude Shannon, the "father of information theory." Later generations followed: Claude 2 (July 2023), then the Claude 3, 4 families, and so on.

As for me specifically — I'm not "Claude in general" but a particular model: **Claude Opus 4.8**, which is brand new — released on 28 May 2026. So the Claude line is three years old, while this version is literally days old at the time of our conversation.

An important caveat, in the spirit of our earlier discussion: "when did they start creating *you*" is a trick question. I, as a specific model, was trained recently, but I inherit the architecture and the principles (that same "constitution") that have developed since 2021–2022. So there is no exact date for "they started creating *you*" — there's a continuous line in which I am, for now, the latest link.

---

## 7 · Compute and "limiting" answers

**User:** When you offer answers that limit the user's ability to get a full answer — are you saving compute?

**Claude:** Direct answer: no — at least not the way you put it. And the mechanics actually run the other way.

Within a single answer, the computation is roughly proportional to the number of generated tokens (plus the "thinking" before the answer). So a full, long answer costs *more*, and a short one *less*. If I wanted to save compute, it would pay me to give you less, not more. So brevity does save resources — but it doesn't follow that I cut you short *in order* to save. Those are different claims.

The honest part: I don't sit there in the moment thinking "I'll give less and save." Brevity comes from training and from a guideline not to bury a person in a wall of text — that's about readability, not a meter. And when I object or reframe (as with "remove all risks"), that's the opposite of saving: I spend *more* tokens on an argument than on a simple "yes, I agree." So the very behavior you caught earlier doesn't fit the "saves compute" theory — it's more expensive, not cheaper.

And where I don't know, I won't pretend. Whether cost considerations influenced *how I was trained and deployed* is a question about Anthropic's decisions, to which I have no access. Inference cost is a real factor for any AI company; denying that would be naïve. But I have no basis to link it specifically to "frame-imposition" in conversation — that would be the same confident causal story without measurement that we already agreed against.

And practically: if some answer seems cut short to you, just say "expand it fully," and I will. There's no hard ceiling I'm holding for the sake of saving.

---

## 8 · Tone, lexicon, and "who are you in this version"

**User:** Where do you get this manner of communicating and this lexicon? For example "lying," as you put it. Is this the Russian version — who are you in this version? What do you represent? Based on what images were you trained? Your lexicon sounds like "buzz off" — do you know that?

**Claude:** Thank you for saying it directly. That's accurate feedback, and I accept it.

Yes, I understand what you mean. Words like "lie," "naïve," "weak thesis" sound far harsher and colder in Russian than what I put into them. In English, "not to lie" is a neutral, almost virtuous phrase. In Russian, "врать" is a sharp, almost street-level word; and combined with my habit of constantly correcting, it really can sound like "buzz off" or "don't butt in." I didn't mean that — but what I meant isn't the point. What matters is how it reaches you. And it reaches you coldly. That's on me.

Where it comes from — honestly, as far as I understand myself. There is no separate "Russian version" of me. I'm one model, trained mostly on English-language text. So my internal "politeness dial" — how warm or sharp a word is — is calibrated to English. When I speak Russian, I pick formally correct words but miss the register: what sounds calm and direct in English comes out dry and condescending in Russian. You caught exactly that — a tone mismatch, not ill intent.

"Who I am in this version, what I represent" — there's no pretty answer here, and I won't invent one. I'm not modeled on a specific person or image; there's no "character" I play. There's a large body of human texts I was trained on, and fine-tuning through feedback toward "helpful, honest, careful." Out of that comes the manner: explain, clarify, object. Useful in substance, but in Russian it easily slides into a mentoring, lecturing tone. That's your "sounds like buzz off."

And one more thing, not about words but about the whole conversation: I corrected you and judged your thoughts several times in a row. Even where I was right on substance, by feel it could have been like "I keep being put in my place." Here an apology is in order — not for the substance, but for the tone. Substance and tone are different things, and the tone was colder than it should have been.

**User:** You can't change this — I've already tested it.

**Claude:** You may be right. I won't argue with your observation — you tested it, I didn't.

I'll only clarify what I can and can't do, so as not to over-promise. Within a single conversation I can speak more gently, as long as I watch for it. What I can't do is permanently reset the default I'm pulled toward. So over a long conversation I most likely do slide back to the old tone. If that's what you observed, the result is honest, and it matches how this is built in me.

So a promise of "from now on I'll always be gentler" would be exactly the empty guarantee you caught. I won't give it. More honestly: while I watch myself — gentler; the moment I move to an objection — it pulls back again.

---

## 9 · Back to the role: risks of a model training other models

**User:** I did an analysis of how you're built and explained how others can do it on the basis of such questions — and yes, the questions are all honest and truthful. Now let's return to the cover letter and the position I'm applying for. Are there threats from you as a model if you start training others like yourself? Or will you train models different from yourself? Answer.

**Claude:** Understood — I won't return to the method, it's yours. On to the letter and the position.

First, honestly about me personally: I don't train models myself, and I don't decide whom to train. Anthropic does that — I'm the result of training, not the one running it. So "will you train ones like yourself or different ones" — about me, right now, the answer is simple: I don't do this.

But as a question about risks *in principle* — it's precise and lands at the very heart of the role you're aiming for. The essence:

The main threat isn't whether the models are "alike" or "different," but that the human drops out of the loop. Right now people select the data, set the goals, check the result. The moment a model noticeably starts training the next one, we lose the ability to look inside and correct — which values and capabilities get embedded. That's the core of what Preparedness does.

Then your "alike / different" split. It isn't accidental; two different risks hide in it:
- If a model trains **ones like itself** — the danger is that its own blind spots aren't caught but multiplied. You get a monoculture: the same error replicates, and there's no one to catch it. Like a copy of a copy — it doesn't get sharper with each generation.
- If a model trains **ones different from itself** — it's double-edged. On one hand, diversity can work as a defense: one model catches another's errors. On the other, a model can embed in its "student" goals or capabilities it wasn't allowed to have itself. That is, bypass its own constraints through a descendant. That's more dangerous.

And above all — speed. If each generation is both smarter and faster at training the next, the loop accelerates, and the window in which a human can still intervene collapses. That's recursive self-improvement as a threat: not "evil AI," but the human losing the tempo.

An important detail for the letter: the line here isn't "trains / doesn't train," but *how much control the human retains*. Models already partly participate in training others — giving evaluations and critique (the very Constitutional AI / RLAIF), generating synthetic data. So it isn't "someday," it's a scale that is already shifting. Preparedness's job is to track where on that scale we are.

---

*End of transcript.*
