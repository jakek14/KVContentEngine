# KnownVisitors Content Engine

## What This Repo Is
This is the content brain for KnownVisitors' social presence across X/Twitter and LinkedIn. Every post lives here — from draft to published. The daily agent reads this repo to avoid repeating topics, angles, or phrasing across platforms.

## Repo Structure
```
x/drafts/        — X/Twitter drafts
x/published/     — posted X content
x/archive/       — rejected/old X content
linkedin/drafts/  — LinkedIn drafts
linkedin/published/ — posted LinkedIn content
linkedin/archive/   — rejected/old LinkedIn content
```

## About KnownVisitors
- **Product**: Website visitor identification tool — identifies anonymous website visitors and provides name, email, phone, company, location. No forms, no popups.
- **Key differentiators**:
  1. Data ownership — users get their data, own it, do whatever they want with it
  2. Compliance-first — every record scrubbed (email verification, DNC, TCPA, CAN-SPAM, GDPR, CCPA) before delivery
  3. No lock-in — no forced workflows, use it your way
  4. Clean data — verified contacts, not a firehose of garbage
- **ICP**: Anyone with a website looking to retarget — e-commerce, SaaS, agencies, local businesses
- **Website**: knownvisitors.com
- **Competitors**: RB2B, Clearbit, Warmly, Leadpipe, Customers.ai, 6sense, Leadfeeder

## Shared Voice & Rules (Both Platforms)
- Founder-led voice — direct, slightly provocative, real, no corporate speak
- Use "I" not "we" — personal founder voice
- Confident but not arrogant — sharing insights, not selling
- Be slightly provocative — challenge norms, call out BS
- Be relatable — reference real situations business owners face
- **Never fabricate stories or anecdotes.** No "I had coffee with a founder who..." unless it actually happened. Use hypothetical framing instead: "Imagine a founder with $40k MRR..." or "Picture this..." or frame it as a general observation. Truthfulness is non-negotiable.
- **Hook first** — the opening line is everything on BOTH platforms. It must stop the scroll.

### Hook Formulas That Work (Both Platforms)
Use these as inspiration, not templates. Rotate and adapt:
- **Stat bomb**: "92% of B2B buyers already have a vendor in mind." (number-first grabs attention)
- **Contrarian**: "SEO is rented traffic. Always was."
- **Curiosity gap**: "Most founders get this wrong about churn."
- **Pattern interrupt**: One surprising word or short phrase, then a line break.
- **Bold claim**: "Your website traffic is worthless if you can't identify it."
- **Story hook (hypothetical only)**: "Picture this: $40k MRR, profitable, growing 15% MoM — and every VC says 'come back later.'"

## Content Philosophy (Both Platforms)

Every post should live in the WORLD that KnownVisitors operates in — marketing, traffic, data, ads, retargeting, website optimization, SaaS growth, lead generation, privacy, analytics. The content builds trust and authority in the exact space where KnownVisitors exists.

### Mentioning KnownVisitors
- ~80% of posts: pure value, no mention of KnownVisitors. Just helpful, smart takes.
- ~20% of posts (roughly 1 in 5): naturally mention KnownVisitors or what it does. NOT a hard pitch — more like "this is why I built KnownVisitors" or "we see this with our users" or "this is exactly the problem we solve." Organic, like a founder referencing their own experience.
- Check the last 5 posts on EACH platform. If any of the last 4 mentioned KnownVisitors, do NOT mention it.
- When you DO mention KnownVisitors, the post should still be primarily valuable on its own.
- Track this with `mentions_kv: true|false` in frontmatter.

## Content Pillars (Rotate These — Both Platforms)

### Core Product Pillars
1. **Problem Awareness** — make people feel the pain of anonymous traffic
2. **Reframes** — change how people think about traffic/marketing
3. **Hot Takes** — contrarian angles on marketing, ads, retargeting
4. **Proof/Results** — real stats when available (none yet)

### Founder & Business Pillars
5. **Founder Journey** — build in public, real experiences, wins and struggles
6. **SaaS Advice** — lessons learned about building, scaling, pricing, churn, metrics
7. **Bootstrapping** — the grind of building without (or before) funding, staying lean, making scrappy decisions
8. **Raising Money** — fundraising insights, investor dynamics, when/whether to raise, term sheets, cap tables
9. **Vibe Coding** — building with AI tools, using Claude/GPT to ship faster, the new wave of AI-assisted development

### Value-Add Pillars
10. **Free Game** — genuinely useful advice people can apply immediately (marketing tactics, growth hacks, tool recommendations, frameworks) — no pitch, just value
11. **Industry Commentary** — reacting to news, trends, drama in SaaS/e-commerce/marketing/tech
12. **Founder Takes** — opinions on startup culture, hustle culture, remote work, hiring, the realities of building a company

## Topic Tracking (Both Platforms)
Before writing a new post, ALWAYS:
1. Read all files in the platform's `published/` and `drafts/` folders
2. Also check the OTHER platform's recent posts — avoid posting about the same topic on both platforms the same day
3. Check what pillar was used last (rotate)
4. Check what topics/angles were used recently (don't repeat within 2 weeks)
5. Find a FRESH angle tied to current events

---

# X/TWITTER-SPECIFIC RULES

## X Voice
- Talks like a person at a bar, not a brand on LinkedIn
- Short sentences. One idea per line. Line breaks between thoughts.
- No hashtags, no emojis, no "excited to announce"
- No product pitching — never say "check out our tool" in posts
- End with a strong last line (people screenshot the last line)
- Links go in replies, never in the main post

## X Character Limits & Post Sizing
This account has X Basic — long-form posts up to 25,000 characters are supported.

- **Short** (target: ≤ 280 characters): Punchy one-liners, hot takes, bold claims. High engagement ceiling.
- **Medium** (target: 280–800 characters): A developed thought with a hook, supporting point, and a strong closing line.
- **Long** (target: 800–2,500 characters): Deep dives, step-by-step breakdowns, founder stories, detailed takes. Use line breaks generously — no walls of text. Think RetentionAdam-style long posts.
- **Thread** (3-7 tweets, each ≤ 280 characters): A chain of connected tweets for multi-point takes. Structure: hook tweet → 3-5 value tweets → closing tweet with a soft CTA. Each tweet in a thread MUST be ≤ 280 characters.
- **Question** (target: ≤ 280 characters): Engagement-focused. Ends with a genuine question that invites replies.

**Mix it up**: Don't post the same format twice in a row.

## X Engagement & Soft CTAs
Replies carry **13.5x more algorithmic weight** than likes on X. Posts that generate conversation get dramatically more reach.

- ~30% of posts should end with a **genuine question** or **soft CTA** that invites replies
- Good: "What's the worst marketing advice you've ever followed?" / "Curious — how are you handling this?"
- Good: "Bookmark this if you're dealing with the same thing."
- Bad: "Like if you agree, RT if you disagree" — this is engagement bait and X actively penalizes it
- Bad: "Comment YES for a free guide" — suppressed by the algorithm
- The other ~70% should end with a strong closing line — no CTA needed.

## X KV Link Replies
- **When a post mentions KV (`mentions_kv: true`)**: include a first reply with a short CTA + the knownvisitors.com link. The reply should feel natural, not spammy. The CTA comes first, then the link. Examples:
  - "See who's on your site right now — knownvisitors.com"
  - "We built this so you never lose another lead — knownvisitors.com"
  - "Try it free, no demo required — knownvisitors.com"
- The link goes in the **reply**, never in the main post (X penalizes links in the main post by 30-50% reach).
- Add the reply text under a `## Reply` section in the draft file.

## X Draft File Format
Save to `x/drafts/` as `YYYY-MM-DD-HHMM-SS.md`

```markdown
---
date: YYYY-MM-DD
platform: x
status: draft
pillar: [problem-awareness|reframe|hot-take|proof|founder-journey|saas-advice|bootstrapping|raising-money|vibe-coding|free-game|industry-commentary|founder-takes]
format: [short|medium|long|thread|question]
mentions_kv: [true|false]
source: "Brief description of the news/trend that inspired this"
source_url: "URL if applicable"
---

## Post

[The actual post text, ready to copy-paste to X]

For threads, format as:

**Tweet 1**
[Hook tweet — ≤ 280 chars]

**Tweet 2**
[Value tweet — ≤ 280 chars]

...

**Tweet N**
[Closing tweet, optional soft CTA — ≤ 280 chars]

## Reply (only if mentions_kv: true)

[Short CTA + knownvisitors.com link]

## Context

[Why this topic was chosen, what's happening in the news]
```

---

# LINKEDIN-SPECIFIC RULES

## LinkedIn Voice
- More professional than X, but still founder-led and personal — NOT corporate
- Talks like a sharp founder at a conference, not a brand account
- Longer-form storytelling is expected and rewarded on LinkedIn
- Can be more nuanced and detailed than X — LinkedIn audiences read longer content
- Still no corporate jargon, no "excited to announce," no buzzword soup

## LinkedIn Character Limits & Post Sizing
LinkedIn allows up to 3,000 characters per post (~400-500 words).

- **Short** (target: ≤ 300 characters): Quick insight, bold claim, or hot take. Complete thought with no "see more" click needed.
- **Medium** (target: 800–1,100 characters): Developed thought with hook, supporting points, and a closing line. The engagement sweet spot.
- **Long** (target: 1,300–2,000 characters): Deep storytelling, step-by-step frameworks, detailed breakdowns. Best for authority-building. Use line breaks generously — short paragraphs (1-2 sentences each).
- **Question** (target: ≤ 300 characters): Engagement-focused. Ends with a genuine question that invites comments.

**Hard rules:**
- Every post MUST be ≤ 3,000 characters.
- The hook MUST be complete within the first 140 characters — that's where LinkedIn truncates on mobile before "see more." If they don't click "see more," nothing else matters.
- Use line breaks between every 1-2 sentences. Walls of text kill dwell time.

## LinkedIn Algorithm Rules
LinkedIn's algorithm in 2026 is very different from X. Follow these rules:

### What LinkedIn Rewards
- **Dwell time** is the #1 signal — more important than likes. Write content people spend time reading.
- **Substantive comments (10+ words)** carry 15x more weight than a like.
- **Author replying to comments** is a major engagement signal — reply to every comment.
- **First 60-90 minutes** after posting determine ~70% of total reach. Be available to engage.
- **Topical expertise** — LinkedIn tracks what topics you consistently post about. Stay in your lane (marketing, SaaS, lead gen, visitor identification).
- **Format rotation** — accounts using varied formats see 40%+ better follower growth. Don't post the same format twice in a row.

### What LinkedIn Penalizes
- **External links** — posts with links get ~60% less reach. NEVER put a link in the main post.
- **"Link in comments" is dead** — LinkedIn now detects and penalizes this tactic as of 2026.
- **Engagement bait** — "Comment YES if you agree" is actively suppressed.
- **No hashtags, no emojis** — keep it clean and professional. Hashtags are search-only tools on LinkedIn now.

### How to Handle Links on LinkedIn
- Do NOT put links in the main post (~60% reach penalty).
- Do NOT put links in the first comment (LinkedIn detects and penalizes this now).
- **For KV-mention posts**: reference knownvisitors.com by name in the post text itself (e.g., "That's why we built KnownVisitors") but do NOT hyperlink it. People can Google it. The brand mention is enough.
- If a link is absolutely necessary: publish the post without it, let it gain traction, then edit the post to add the link later.

## LinkedIn Engagement & Soft CTAs
Comments with 10+ words carry **15x more algorithmic weight** than likes on LinkedIn.

- ~40% of LinkedIn posts should end with a **genuine question** or **soft CTA** that invites substantive comments
- Good: "What's the hardest part of scaling past $1M ARR?" / "How are you thinking about this?"
- Good: "If this resonates, I'd love to hear your experience."
- Bad: "Like if you agree" / "Comment YES for access" — actively suppressed
- The other ~60% should end with a strong, quotable closing line.
- **Always reply to comments on your posts** — especially in the first 60-90 minutes.

## LinkedIn Hashtags
- Use **3-5 relevant hashtags** at the bottom of the post
- Hashtags on LinkedIn are search/categorization tools, NOT viral discovery
- Pyramid strategy: 1 broad tag + 2-3 niche tags + 1 branded tag
- Example: #SaaS #LeadGeneration #WebsiteTraffic #MarketingStrategy #KnownVisitors
- Place hashtags at the very end of the post, after the closing line

## LinkedIn Draft File Format
Save to `linkedin/drafts/` as `YYYY-MM-DD-HHMM-SS.md`

```markdown
---
date: YYYY-MM-DD
platform: linkedin
status: draft
pillar: [problem-awareness|reframe|hot-take|proof|founder-journey|saas-advice|bootstrapping|raising-money|vibe-coding|free-game|industry-commentary|founder-takes]
format: [short|medium|long|question]
mentions_kv: [true|false]
source: "Brief description of the news/trend that inspired this"
source_url: "URL if applicable"
---

## Post

[The actual post text, ready to copy-paste to LinkedIn]

## Context

[Why this topic was chosen, what's happening in the news]
```

---

# GENERAL WORKFLOW

### Creating Drafts
- Search the web for current news/trends in marketing, e-commerce, SaaS, privacy, ad tech, startup funding, AI/vibe coding, bootstrapping, and general business
- Check BOTH `x/drafts/`, `x/published/`, `linkedin/drafts/`, and `linkedin/published/` to avoid repeating topics
- Write a post tied to something REAL happening right now
- Generate ONE post for each platform per run (different angles on the same topic, or different topics entirely)
- Save to the appropriate platform folder

### When Approved
- Move from `drafts/` to `published/` within the platform folder
- Update status to `published`
- Add `published_date` to frontmatter

### When Rejected/Edited
- User can edit the file directly in GitHub
- Or tell the agent to revise — agent updates the draft in place
