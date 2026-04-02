# PM in the AI Era — Presenter Cheat Sheet
**UCLA MBA Guest Lecture | April 2026 | ~20 min + Q&A**

---

## Slide 0 — Title: Product Shaper in the AI Era
**Key message:** Frame the talk — this isn't about whether PM survives, it's about what the role *becomes*.
- "Job titles change. Core capabilities endure."
- Set expectation: personal journey + practical takeaways + honest AI-era perspective.

---

## Slide 1 — My Journey (DNA Helix)
**Key message:** AI and commerce have been intertwined throughout your career — this isn't a new topic for you.
- Walk through quickly: P&G (consumer insight, brand ownership) → Used Car Marketplace (startup growth) → VC (first AI spark — tried chatbot for food/grocery ordering, didn't work, but saw what was coming) → TikTok/ByteDance (AI to distribute and create content, connect info and humans) → Grad school (moved to the US) → Poshmark (search, reco, ML, short video, wholesale) → Founded KiwiDrop → South Park Commons (exploration) → Meta (Ads × Gen AI)
- **Don't linger** — 1 min max. The helix speaks visually.

---

## Slide 2 — Product = Total Customer Experience
**Key message:** Product isn't just software. PM isn't just a tech role.
- Product = the *total offering* a customer touches — pricing, packaging, service, returns, everything.
- PM = Product Shaper — the one who defines and makes the call. A *creator*, not a ticket writer.
- Origin: term popularized in Ruby on Rails era, but the function is ancient (P&G Brand Man, 1931).
- **Ask the audience:** "What's the 'product' at your company — is it just the app?"

---

## Slide 3 — Every Industry Has a Product Shaper
**Key message:** The job exists everywhere, just under different names.
- **Amazon Retail:** selection, Prime, returns policy, delivery speed — the "product" is the purchase experience. Shaper = Category Leader.
- **Pharma:** compound/asset is the product — dosage, efficacy, risk, target patient profile — every decision is a tradeoff. Shaper = Asset Lead.
- **KiwiDrop:** retention is the product — what makes a buyer come back? Shaper = Founder.
- **Takeaway:** Don't get hung up on the title "PM." Look for the product-shaping function.

---

## Slide 4 — "PM Is Gone." (Transition)
**Key message:** This is the anxiety in the room — name it directly.
- Provocative framing: companies are literally rewriting career pages.
- Pause here. Let it land.

---

## Slide 5 — Ramp: Builders Only (Browser Embed)
**Key message:** This is real. Ramp's career page says "We only hire builders."
- Point out: no department categories, employees listed by *what they shipped*, not their title.
- "Marketers are coding. PMs are rewriting copy. Devs are building their own agent."
- CEO Eric Glyman's filter: "If this person started a company, would we join them?"
- **Nuance to mention verbally:** Their Ashby job board *still* lists PM roles. The *marketing* is provocative, the reality is more nuanced. But the signal is real.

---

## Slide 6 — What's Actually Changing
**Key message:** Three concrete shifts that make old PM playbooks obsolete.
1. **Tasks automated:** Writing PRDs, prioritizing backlogs, alignment docs — AI can draft these. What's left?
2. **Models change daily:** Old assumption was "tech stays stable during a project." Now capabilities shift mid-sprint.
3. **Non-deterministic output:** AI doesn't produce the same result twice. You can't spec it like traditional software.
- **Key quote to say:** "The old assumption was: what's technically possible at the start of a project is roughly what's possible at the end. That's gone."

---

## Slide 7 — Try Faster. Build Earlier. Overturn Yourself More Often.
**Key message:** The PM response to these shifts — speed of iteration is everything.
- Mini prototypes, not 10-page PRDs. Get feasibility signal in hours.
- After every model release: re-evaluate old features. Workarounds designed for old limitations become unnecessary complexity.
- Unlearn priors. Yesterday's best practice can be today's tech debt.
- **Example:** Meta Ads creative team cut work cycles shorter, encouraged eng/design/DS/UXR/PM to all run small experiments *outside* the formal roadmap.

---

## Slide 8 — Eval = Trial and Error
**Key message:** Evaluation is the new core PM skill for AI products.
- **Prompt to audience:** "If you were the boss reviewing your employee's work, what would your rubric be? Write that rubric for the AI."
- Iteration method: run 100-150 samples, self-label, discover where your rubric is vague/contradictory, fix the eval *before* fixing the model.
- Mental model: think of it as onboarding a junior teammate — not a one-time doc, but continuous structured calibration.
- **This is hands-on. Offer to show a real eval after Q&A if anyone's interested.**

---

## Slide 9 — AI Breaks Your Intuition (Live Demo)
**Key message:** Understanding *why* AI fails counterintuitively is a PM skill.
- **The example:** Diffusion-based image models (like Flux) — it's *easy* to replace text content on an image, but *hard* to make existing text bigger/bolder.
- **Ask the audience first:** "Which do you think is easier?" Most will guess wrong.
- **Why:** In diffusion models, the compress-decompress process loses fine-grained spatial/style information for small text. Content is encoded semantically, so replacement works. But geometric transforms (size, weight) operate on pixel-level info that's been compressed away.
- **Takeaway:** Knowing the boundary turns a puzzling failure into a design decision. You route around it instead of fighting it.
- **Optional:** Show a real before/after if you have one prepared (Flux multilingual text generation is another good example).

---

## Slide 10 — Be Technical: Know the Boundaries
**Key message:** You don't need a PhD. You need to know *what's possible now* and *what's coming*.
- Level 1: What works today vs. what doesn't. (Table stakes.)
- Level 2: What gets unlocked in 3-6 months and *why*. → This tells you what to build *now* where need meets capability.
- **How to stay current:**
  - Papers: Abstract → Conclusion → body (if still curious). Most people don't need to read papers at all.
  - Best stuff isn't in papers anymore — follow X, Hacker News, builder communities.
  - **Try it first.** Before asking a human, ask ChatGPT/Claude. Hands-on > hearsay.
- **Example to mention verbally:** Why product packaging text is hard to preserve in AI-generated e-commerce ads — compression in the encode-decode pipeline loses small, high-frequency details.

---

## Slide 11 — Use AI Well: PRD for AI
**Key message:** The deliverable has changed. From PRD-for-engineers to PRD-for-AI.
- **Evolution:** Prompt → Context → Harness Engineering. Single-prompt chat is *not* the ceiling.
- What goes where: Claude.md (persistent instructions), Memory.md (learned context), Skills (reusable workflows).
- **Agent system design:**
  - Role patterns: Proposer + Red-team + Judge + Critic
  - Or domain-split: Safety agent, Performance agent, Maintainability agent
  - Vehicle choice: instructions in config, hooks, sub-agents, 3rd-party models
- **Where to start:** Pick a concrete project. Build it end-to-end with AI.
  - Ideas: baby tracker + growth coach, content assistant (idea → LinkedIn post)
- **Key line:** "The best way to understand AI capabilities is to ship something with it."

---

## Slide 12 — Core Capabilities Beyond Building
**Key message:** AI can build. These four things it can't easily replace.
1. **Domain Expertise** — useful for cold-start but the window is shrinking. LLMs learn what's public fast. Your *unique* insight bar keeps rising. Old best practices can become obsolete overnight, even across different domains.
2. **Taste** — "What's the best customer experience you've encountered?" You've seen great things. That calibration is lived, not prompted.
3. **Tinker** — learn fast by doing. Not reading docs — building, hitting walls, iterating. This is the muscle.
4. **Architecture** — design systems, not patches. Patches don't compound. Architecture does.
- **Key provocation:** "Your domain expertise gives you a head start, but that head start is getting shorter every month."

---

## Slide 13 — What Hasn't Changed
**Key message:** Despite all the change, the human fundamentals are constant.
1. **Curiosity & User Empathy** — the starting point for every great product. No model can simulate genuine curiosity.
2. **Think Deeper / Synthesize** — see the essence of a problem, extract structure, design the system. AI generates; you *synthesize*.
3. **Influence & Persuasion** — attention is more expensive than ever, supply of content is near-infinite, GTM is the bottleneck. Content = product. Being able to convince humans to act is irreplaceable.
- **Provocation:** "Should you become a salesperson? Maybe. The line between product and sales is blurring."

---

## Slide 14 — What to Do Now
**Key message:** Practical, actionable closing.
- **Short term:** Make yourself a one-person powerhouse. Close the loop end-to-end. Be 60% competent at every function — design, code, data, growth. You don't need to be an expert at all of them, but you need to be able to *do* all of them.
- **Long term:** Don't cling to the title "Product Manager." Be a product shaper. Focus on what matters *beyond* just building — taste, strategy, influence. These compound. Titles don't.

---

## Slide 15 — Thank You. Let's Chat.
- Open Q&A. 
- Encourage any question — PM, AI, career, life.
- jaggiechu@gmail.com for follow-ups.

---

## Timing Guide
| Slides | Topic | Target |
|--------|-------|--------|
| 0-1 | Intro + journey | 2 min |
| 2-3 | What is product / PM | 3 min |
| 4-5 | PM is gone + Ramp | 2 min |
| 6-7 | What's changing + response | 4 min |
| 8-9 | Eval + intuition demo | 4 min |
| 10-11 | Be technical + use AI | 4 min |
| 12-14 | Capabilities + closing | 3 min |
| **Total** | | **~22 min** |
