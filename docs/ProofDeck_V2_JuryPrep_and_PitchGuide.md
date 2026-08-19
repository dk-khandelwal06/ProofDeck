# ProofDeck V2 — Eureka Edition
### Jury Q&A Prep, 2-Minute Pitch Flow, and Verification Checklist

---

## 1. The 2-Minute Pitch Flow

Use this as your spoken script skeleton — not to memorize word-for-word, but to internalize the beats. Roughly 15–20 seconds per beat for a 2-minute pitch.

1. **Hook (Slide 2–3):** "A resume tells you what someone claims. It doesn't show you what they actually built. And AI just made writing convincing claims free — so proof is now the scarce thing."
2. **Solution (Slide 4):** "ProofDeck is the evidence layer between the two. Resume is the claim, GitHub is the build, ProofDeck connects them into an evidence-backed skill signal."
3. **How it works (Slide 5–6):** "Connect your project sources, we analyze them, structure the evidence, and generate a recruiter-ready profile — like this one."
4. **Who it's for (Slide 8):** "We start with technical students who have strong project work but weak conventional credentials, and expand toward placement cells and recruiters."
5. **Business model (Slide 9):** "Free for students, paid for recruiters who want to screen on verified skill instead of keywords — this is illustrative pricing we still need to validate."
6. **Why it's defensible (Slide 12):** "The moat isn't the analysis — it's the evidence graph that grows every time a student builds and every time a recruiter searches."
7. **Close (Slide 15):** "The future of hiring shouldn't be about who writes the best claims — it should be about who can show the best proof. That's ProofDeck."

---

## 2. Jury Q&A Preparation (25+ Questions)

### Problem & Why Now

**Q1. Why is this problem urgent right now, not five years ago?**
Generative AI has collapsed the cost of writing a polished, confident resume line to near zero. Five years ago, a well-written claim was itself a weak signal of effort and competence. Today it's the default output of a five-second prompt — so the claim carries almost no information, and the burden shifts to proof.

**Q2. Isn't "resume claims are unreliable" an old problem? What's actually new?**
The unreliability isn't new — the *scale and cheapness* of generating unreliable claims is. What's new is that recruiters can no longer use writing quality or claim confidence as even a weak filter, because AI writes every resume equally well.

**Q3. How big is this problem, really — do students genuinely struggle to communicate their skills?**
We don't have primary research on this yet — that's explicitly part of our validation roadmap (student interviews). What we can speak to directly is the founder's own experience: real project work (voice assistants, automation pipelines, analytics dashboards) sitting scattered across GitHub, Excel files, and folders with no structured way to present it credibly.

### Product & Technology

**Q4. What exactly does the "Analyze" step do — is there real AI here or just a UI wrapper on GitHub?**
Today, it's a conceptual MVP: the workflow (Connect → Analyze → Structure → Share) and the UI are defined and mocked up, but the underlying evidence-analysis engine has not been built as production AI yet. We're not claiming an AI capability that doesn't exist — the immediate build priority is a working analyzer that reads repo metadata, commit patterns, and code composition to produce a structured skill signal.

**Q5. What prevents someone from faking a GitHub history to game ProofDeck?**
This is a real, open risk we haven't solved yet — it belongs on our validation and R&D roadmap, not something we're claiming to have solved. Directionally, mitigations include analyzing contribution patterns over time (not just final code), cross-referencing commit cadence and complexity, and treating ProofDeck's signal as "evidence to inspect further," not a binary certification — recruiters still make the judgment call.

**Q6. What stops someone from using AI to generate fake or trivial projects just to pad their GitHub?**
Same category of risk as Q5. Our answer today is honesty, not a solved feature: contribution-context analysis (depth of commits, iteration history, complexity signals) is the direction, but it needs real R&D and testing before we can claim it's robust.

**Q7. Why can't a recruiter just look at the GitHub profile directly instead of using ProofDeck?**
They can, and many do — but GitHub isn't built for fast recruiter screening. It has no resume-claim linkage, no skill-level structuring, and reviewing a candidate's raw repo history takes far longer than scanning a structured evidence-backed profile. ProofDeck's job is compression and structure, not new data access.

**Q8. What does "evidence-backed" actually mean technically — what's the verification bar?**
Right now, conceptually, it means the skill claim is traceable to a specific artifact (a repo, a commit set, a notebook) rather than asserted in prose. It is not cryptographic proof of authorship or a guarantee of skill mastery — it's a transparency layer that lets a recruiter go one click deeper than a resume line.

### Market & Customers

**Q9. Who is the primary paying customer — students or recruiters?**
Recruiters are the more likely primary revenue source long-term (B2B willingness-to-pay is typically higher than B2C for career tools), but the business needs students first to create the evidence supply recruiters would pay to access. This is a two-sided model — we're intentionally sequencing student adoption before recruiter monetization.

**Q10. Why would a student use this instead of just polishing their LinkedIn or portfolio site?**
LinkedIn and portfolio sites are self-authored and self-reported — the same weakness as a resume. ProofDeck's differentiation is that the signal is derived from evidence, not written by the candidate, which is precisely what a portfolio site can't offer.

**Q11. What is your TAM/SAM/SOM?**
We've deliberately avoided a large, generic HR-market number because it wouldn't be honest about where we can actually compete first. Our market story is bottom-up: beachhead is technical students at IIT/NIT-tier and technical colleges seeking internships, expansion is university placement cells, and the long-term opportunity is recruiters hiring technical talent. We'd rather size the beachhead precisely once we have real usage data than quote an inflated top-down number today.

**Q12. Why would recruiters trust a third-party tool's assessment over their own screening process?**
They wouldn't be asked to fully trust it — ProofDeck is positioned as a faster way to get to the evidence they'd otherwise have to dig for themselves, not a replacement for their judgment. That's why the tagline is "we make claims inspectable," not "we certify skills."

**Q13. Why can't LinkedIn or GitHub just build this feature themselves?**
They could, and that's a real competitive risk worth naming honestly. Our bet is that neither has strong incentive to: LinkedIn's business model rewards engagement with self-reported content, and GitHub's core users are developers, not recruiters — evidence-to-recruiter translation isn't central to either company's roadmap today. That's a timing and focus argument, not a permanent moat.

**Q14. Why can't recruiters or ATS vendors build this internally?**
Some might, especially larger ATS players. Our advantage would be depth of focus — this is our only product — and starting with the technical-student niche where project evidence is richest and most structured (code, notebooks, commits), rather than trying to solve evidence-verification across every job category at once.

### Business Model & Financials

**Q15. Walk me through your revenue model in one sentence.**
Free evidence-backed profiles for students, paid premium analytics for students who want more, and B2B subscriptions for recruiters who want to search and filter by verified skill — all pricing is illustrative today and needs validation.

**Q16. What are your unit economics — CAC, LTV, margins?**
We don't have real data yet, and inventing numbers here would undercut our own credibility on a startup whose entire thesis is "don't trust unverified claims." What we can commit to is validating acquisition cost through low-cost, community-based channels (campus communities, hackathons) before scaling paid acquisition.

**Q17. When do you expect to be profitable?**
We're not going to project a date we can't defend. The near-term financial goal is proving a small number of recruiters will pay for evidence-backed search before scaling either side of the marketplace.

**Q18. What's your ask — funding, mentorship, or something else?**
At the idea-submission stage, the ask is validation support: access to student and recruiter interviews, mentorship on evidence-verification approaches, and, if the model proves out, early pilot introductions to placement cells.

### Scalability & Defensibility

**Q19. What's the actual moat here — what stops a well-funded competitor from copying this in six months?**
Today, honestly, not much beyond execution speed and founder focus — we're naming that directly rather than overclaiming a moat we haven't earned. Over time, the intended defensibility is the accumulated evidence-linked dataset (harder to replicate once thousands of verified profiles exist) and embedded recruiter workflows (once a recruiter's screening process depends on ProofDeck, switching has a real cost).

**Q20. How does the product get better as more people use it?**
Two-sided network effect: more student profiles give recruiters a deeper, more useful pool to search; more recruiter usage gives students a stronger reason to build out a verified profile instead of a plain resume.

**Q21. What happens if recruiters simply don't adopt this — what's your fallback?**
If B2B recruiter adoption stalls, the product still has standalone value as a premium student portfolio tool (B2C), though the more ambitious "hiring infrastructure" vision depends on recruiter-side traction — that's precisely why recruiter interviews are on our near-term validation list, not something we're assuming will just happen.

**Q22. How do you expand beyond students to a broader labor market later?**
The evidence-layer concept generalizes to any field with inspectable work artifacts — design portfolios, writing samples, open-source contributions in other domains — but we're deliberately not chasing that now. Proving the model in one focused, evidence-rich niche (technical students) comes first.

### Privacy, Trust & Risk

**Q23. How do you handle candidate privacy and consent around GitHub data?**
This needs a real policy before any public launch — at minimum, opt-in connection (candidates choose what to link), visibility controls over what's shared publicly versus with specific recruiters, and the ability to disconnect and remove a profile. We haven't built this yet; it's a stated pre-launch requirement, not a solved problem.

**Q24. What are the GitHub API rate limits and how do you handle them at scale?**
We haven't hit this constraint yet since there's no live product — but it's a known technical risk for any GitHub-analysis tool at scale, and the honest answer is that it needs real engineering evaluation (caching, authenticated rate limits, incremental sync) before this could support many concurrent users.

**Q25. What's the single biggest risk to this business?**
Two-sided marketplace cold-start: getting enough students to create profiles before there's recruiter demand to justify it, and vice versa. That's why go-to-market starts narrow — one campus community and a handful of recruiter pilots — rather than trying to launch both sides broadly at once.

### Founder & Team

**Q26. You're a solo founder — why are you the right person to build this, and how will you scale beyond just yourself?**
The problem is one I've lived directly — building real projects (an AI voice assistant, an LLM-integrated automation tool, a full analytics dashboard) and having no structured, credible way to present that work beyond a resume line. Technically, I can build the MVP myself (Python, data analysis, automation, AI integration). Scaling beyond solo work is a real gap I'm not pretending to have solved — it's a reason to seek co-founders, mentors, or early technical collaborators as the product matures past MVP.

**Q27. What's your realistic timeline to a working MVP beyond the conceptual mockups shown today?**
That depends on scope we haven't finalized publicly — the responsible answer in a pitch setting is to commit to validating the riskiest assumptions (will students connect their GitHub, will recruiters actually use evidence-backed search) before over-investing in a full build, rather than promising a hard ship date today.

---

## 3. Claims and Statistics That Require Verification Before Submission

- **"150 players across 10 IPL teams"** (founder slide, IPL Performance Analytics project) — confirm this figure matches your actual project scope before presenting it to judges.
- **"42 commits analyzed"** and other specific numbers on the product mockup (Slide 6) — these are illustrative UI content for the conceptual MVP, not real production data. Consider adding a verbal caveat ("this is a mockup, not live data") if a judge asks to see it live.
- **Any pricing figures** you decide to add later (subscription price points, freemium limits) — currently left as "illustrative" by design; do not firm these up in writing without genuine validation or at least clearly labeling them as assumptions.
- **Founder bio claims** (Slide 14) — confirm the three projects listed (Jarvis, AI-Chat-Automation-Bot, IPL Performance Analytics) are complete and presentable at time of pitching, since judges may ask to see them.
- **Competitive landscape table** (Slide 10) — this reflects your own positioning judgment, not published third-party research. If a judge challenges a specific cell (e.g., "why does GitHub score 'dash' on standardized format?"), be ready to explain the reasoning conversationally rather than citing it as an external fact.

---

## 4. Assumptions Still to Validate (Full List)

1. Technical students are willing to connect their GitHub account to a third-party evidence tool.
2. Students see enough value in an evidence-backed profile to use it over (or alongside) a resume/LinkedIn.
3. Recruiters would actually change screening behavior based on an evidence-backed signal rather than their existing process.
4. Recruiters would pay for evidence-backed search and screening support.
5. Placement cells would adopt or endorse ProofDeck profiles as part of their process.
6. An automated evidence-analysis engine can produce skill signals accurate and trustworthy enough to be useful (not yet built).
7. The two-sided marketplace can achieve cold-start without large paid acquisition spend.
8. Illustrative pricing (freemium tier, B2B subscription) reflects what each side would actually pay.

---

*Prepared for Eureka! 2026 — Idea Submission stage. Deck: `ProofDeck_V2_Eureka_Edition.pptx`.*
