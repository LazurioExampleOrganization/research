# Lazurio Example Organization research sprint: online projects with a monetization signal

Moved from the Organization root (company/archive and company/agents/reference) during the GEN3 migration.

Verification date: 2026-05-22

Scope: a first public scan of projects from which a monetization mechanism can
be legally adapted for Lazurio Example Organization. The goal is not to copy a
brand, content, accounts, customer data or non-public know-how. The goal is to
break down where the money is made, which part of the workflow can be done by
agents and what smallest test could be launched after human confirmation.

## Methodology

Source types used:

- verified revenue databases and marketplace profiles: TrustMRR, ProvenMRR,
  Surgent, RankYourApp
- founder case studies: Indie Hackers, Starter Story, MRR Story, The Futur
- official/company pages where they show pricing, customers or the model

Confidence:

- 5: payment data declared as verified through a payment API, or an official
  company revenue statement
- 4: credible founder/case-study source with specific numbers
- 3: secondary case study or database without direct payment-proof detail
- 2: weaker public signal, use only as inspiration and verify again

## Top candidates for the first deep dive

1. **Chatwith / Chatbase pattern**: white-label AI chatbots for agencies.
   Reason: a clear B2B buyer, high agentic leverage, Chatwith has verified MRR
   and the founder explicitly describes the problem as a lack of sales
   capacity.
2. **Launch Club / Reddit-AI-search pattern**: managed brand visibility in
   channels that feed Google and AI answers. Reason: a high revenue signal,
   but it needs to be rewritten into a reputationally safe and transparent
   version.
3. **PipeLime / AI SDR pattern**: AI sales agents for research, enrichment,
   follow-up and booking meetings. Reason: it fits agentic workflow and B2B
   value directly, but must not slide into spam.
4. **Vid.AI / Vidgenie / Flibbo pattern**: AI video/content creation for
   short-form and the creator/business segment. Reason: large revenue signals,
   fast demand, a repeatable asset workflow.
5. **DesignJoy-for-automation pattern**: a productized service with one
   active request, asynchronous operation and a subscription price. Reason:
   the fastest path to the first invoice without building a full SaaS.

## Candidate longlist

| # | Project | Category | Monetization signal | Mechanism | What the company can adapt | What not to copy / risk | Confidence | Source |
|---|---|---|---|---|---|---|---:|---|
| 1 | Chatwith | AI customer support / white-label | TrustMRR shows all-time revenue 115k USD, MRR 5.9k USD, 62 subscriptions, Paddle verified | White-label chatbot builder for agencies that resell AI support to their clients | A vertical white-label agent for one agency niche, plus done-with-you sales onboarding | Do not copy the brand, UI, datasets or client bot templates | 5 | https://trustmrr.com/startup/chatwith |
| 2 | Chatbase | AI agents / customer support | Indie Hackers reports over 5M ARR and growth from 64k MRR | Self-serve AI chatbot, later agents/API/integrations for companies | A specialized support agent for a narrow segment, not a general chatbot builder | The market is crowded; a wrapper without distribution is not enough | 4 | https://www.indiehackers.com/post/from-viral-side-project-to-a-5m-yr-b2b-ai-platform-TpbhTVyp1sjBk0uzo4tR |
| 3 | Vid.AI | AI short-form video | TrustMRR shows all-time revenue 1.38M USD, MRR 95k USD, 1.5k subscriptions | Generating ready-to-post videos from an idea or a script | An agentic video factory for a B2B niche, not a general consumer tool | High AI costs, ad fatigue, copyright/likeness risks | 5 | https://trustmrr.com/startup/vidai-llc |
| 4 | Vidgenie.ai | AI video marketing | TrustMRR shows all-time revenue 558k USD, MRR 15k USD, 330 subscriptions | AI marketing videos for businesses and creators | Vertical video packages for one niche, for example local services or B2B SaaS | Do not copy templates, claims or marketing copy | 5 | https://trustmrr.com/startup/vidgenie-ai |
| 5 | Flibbo | AI mobile creator app | MRR Story reports 55k MRR, a peak of over 90k MRR and 500k users | An AI model wrapper in a mobile app, growth via TikTok/Reels and paywall testing | A mobile or web wrapper for a specific use case with hard paywall testing | Do not base the business only on paid virality; watch the unit economics of generation | 4 | https://www.mrrstory.com/stories/he-built-a-55k-mrr-ai-app-without-knowing-how-to-code |
| 6 | Cuppa.ai | AI SEO content | Indie Hackers reports 41-45k MRR for the SaaS and 13.5k MRR for the DFY service | AI article workflow for SEO, plus done-for-you agency automation | Agentic content operations for a narrow type of agency or publisher | SEO spam and low-quality AI content can damage reputation | 4 | https://www.indiehackers.com/post/tech/acquiring-an-ai-micro-saas-and-building-it-to-58k-mrr-within-two-years-kIRoiABUe3yTPC6AgvrN |
| 7 | Jenni AI | Academic writing SaaS | Sacra estimates 7.0M ARR in July 2025 | AI writing environment for academics, citations, research library, Word/LaTeX export | A vertical research assistant for legal, business or grant workflows | Academic integrity, plagiarism and school policy risks | 3 | https://sacra.com/c/jenni-ai/ |
| 8 | HeadshotPro | AI professional images | Starter Story / Startup Founder Stories report 300k monthly revenue | A practical AI image service with fast output and a clear willingness to pay | A B2B asset generator for a clear professional output: profile, listing, product image | Likeness consent, dataset rights, biometric/privacy risks | 4 | https://startupfounderstories.com/stories/danny-postma-headshotpro-100k-2-weeks |
| 9 | PhotoAI | AI photographer | Public build-in-public sources cite tens of thousands up to 150k MRR; needs to be verified again | Consumer AI photo generation via the web, frictionless upload-to-result | Mechanism only: a fast paid personal asset generator | The source is weaker; image rights and deepfake risks | 2 | https://www.indiehackers.com/post/how-to-build-ai-products-that-make-98cb49badb |
| 10 | Launch Club | Reddit / AI search visibility | TrustMRR shows all-time revenue 969k USD, MRR 45k USD, 18 subscriptions | Helps companies be visible in a Reddit/AI-search context, combines SaaS and a content service | A transparent research and content placement strategy for legitimate thought leadership | Do not copy astroturfing, aged accounts, fake engagement or manipulation | 5 | https://trustmrr.com/startup/launch-club |
| 11 | Reddit Agency | Productized Reddit marketing | TrustMRR shows all-time revenue 192k USD, MRR 10k USD | Done-for-you Reddit content, reputation and AI search support | Reputation/answer-engine optimization as a consulting service with disclosure rules | High ToS/reputational risk; do not adopt account farming or stealth posting | 5 | https://trustmrr.com/startup/reddit-agency |
| 12 | PipeLime | AI outbound sales agents | TrustMRR shows all-time revenue 47.9k USD, MRR 11.6k USD, 15 subscriptions | AI SDR: lead research, email verification, contextual outreach, follow-ups, meeting booking | Agentic B2B sales ops for one niche with a manual approval step | Spam, deliverability, GDPR/consent, platform ToS | 5 | https://trustmrr.com/startup/pipelime |
| 13 | 1Lookup | Data validation API | TrustMRR shows all-time revenue 3.35M USD, MRR 265k USD | API for phone/email/IP validation and fraud prevention | A data utility API for one painful B2B operations problem | Do not copy data; privacy and compliance are critical | 5 | https://trustmrr.com/startup/1lookup |
| 14 | SimpleWeb by @Yasers | Productized local websites | TrustMRR shows MRR 2.46k USD and 115 subscriptions | Automated one-page websites for small businesses, hosting as the recurring part | An agentic "website-in-24h" for one local niche with a clear scope | Low ARPU, support/revision creep, local compliance | 5 | https://trustmrr.com/startup/simpleweb-by-yasers |
| 15 | DesignJoy | Productized service | The Futur reports over 1M USD annual revenue, Starter Story 145k monthly revenue | One-person subscription agency, async, fixed scope, one active request | "DesignJoy for agent automations": subscription, async board, one active request | Do not copy the brand; the model depends on high delivery quality and trust | 4 | https://thefutur.com/content/productize-design |
| 16 | ShipFast | Boilerplate / digital product | Indie Hackers reports 63.6k USD revenue in less than two months | A one-time paid boilerplate that saves founders time | An agent-ready boilerplate or implementation kit for a very narrow workflow | Security quality, support debt, commoditization | 4 | https://www.indiehackers.com/post/case-study-shipfast-made-63k-in-revenue-in-60-days-8jj06RfVwjLR01CSDvxb |
| 17 | TrustMRR | Verified revenue database / marketplace | TrustMRR's own profile shows all-time revenue 191k USD, MRR 13k USD | Verified revenue data as a marketplace, lead-gen and trust layer | Revenue-verified opportunity intelligence for the company's research | Do not copy listing data at scale; respect ToS and attribution | 5 | https://trustmrr.com/startup/trustmrr |
| 18 | Plausible Analytics | Open-source SaaS | The official blog reports 1M ARR in 2022 and 7k+ paying subscribers | Open-source alternative + paid hosted service | A managed service on top of an open workflow for a privacy/ops niche | Takes longer to build; requires trust and technical quality | 5 | https://plausible.io/blog/open-source-saas |
| 19 | Bannerbear | API automation SaaS | FirstMRR reports 16k MRR, Indie Hackers milestone of 6k MRR | API for generating image/video assets, no-code integrations | An agentic asset generation API for marketing ops | Competition from Canva/AI tools; needs a clear integration | 4 | https://first-mrr.com/study/banner-bear |
| 20 | Rezi | AI resume builder | Surgent/TrustMRR data cite about 283k MRR and 8.7M all-time revenue | Product-led SEO for a specific job-seeker workflow | A vertical career agent for one profession or region | ATS/personal data, claims without evidence, a crowded market | 4 | https://surgent.dev/inspirations/rezi |
| 21 | Search+ | Ecommerce AI search | TrustMRR shows all-time revenue 28.8k USD, MRR 4.5k USD | AI search/personalization for ecommerce, B2B high-ticket subscriptions | An agentic conversion utility for Shopify/SMB ecommerce | Only 3 subscriptions; churn and acquisition need to be verified | 5 | https://trustmrr.com/startup/search |
| 22 | ToneAdapt | AI niche mobile app | MRR Story reports about 25k monthly revenue and 100k users | Translating a well-known guitar tone to the user's gear, a niche pain + app subscription | A highly niche "translate expert knowledge to user context" app | Source data, copyright associations with songs/artists, App Store dependency | 4 | https://www.mrrstory.com/stories/how-one-tiktok-video-brought-100000-users |
| 23 | Glamour | AI personal color analysis | RankYourApp reports verified MRR 14.5k USD and 865 active customers | AI selfie analysis for beauty/fashion advice, subscription | Niche visual analysis with a clear consumer willingness to pay | Face/photo privacy, accuracy claims, beauty sensitivity | 4 | https://www.rankyourapp.com/app/glamour |
| 24 | Private Location Intelligence API | Data/API | A TrustMRR search result reports MRR 6.9k USD, total 50k USD | API for foot-traffic/venue busyness data and city guides | An AI-ready public data API for one decision niche | Privacy, data licensing, location data compliance | 3 | https://trustmrr.com/startup/localweb |
| 25 | Cold email agency case | Productized B2B service | The anonymized Borks case reports 30k MRR in 6 months | Narrow ICP, fixed retainer, booked-call promise, outbound ops | A productized B2B appointment-setting experiment with manual approval | Anonymized source; cold email must address consent, deliverability and laws | 3 | https://borks.io/blog/cold-email-agency-case-study-30k-mrr |
| 26 | Crawlbyte | Web data extraction API | PolyMRR reports 47k total revenue and 1.7k MRR; the official site shows paid API pricing | No-code/API scraping and structured extraction | Agentic public-data extraction for permitted sources and a specific workflow | Do not cross robots/ToS; CAPTCHA bypass is a reputational and legal risk | 3 | https://www.polymrr.com/startups/crawlbyte |

## Recurring mechanisms

1. **White-label B2B tool for agencies**: Chatwith, Chatbase, ChatDash-like
   patterns. The company can start as a service wrapper and only then build a
   product.
2. **AI content/video app with a paywall**: Vid.AI, Vidgenie, Flibbo,
   HeadshotPro. It works when the output is visual, instant and easy to
   distribute.
3. **Productized service with async operation**: DesignJoy, cold email agency,
   Reddit/AI-search services. The fastest path to the first invoice.
4. **Data/API utility**: 1Lookup, Crawlbyte, location intelligence,
   Bannerbear. Higher B2B value, but more compliance and technical
   reliability.
5. **Verified database / opportunity marketplace**: TrustMRR. The data itself
   is the product if it solves trust, discovery and the transaction.
6. **Vertical expert translator**: ToneAdapt, Glamour, Rezi, Jenni. AI takes
   expert knowledge and translates it into the user's personal context.

## Recommended first experiments

### Experiment A: White-label AI support agent for agencies

- Inspiration: Chatwith, Chatbase
- Offer: "Within 72 hours we set up an AI support widget for an agency's
  client on top of the FAQ, the website and the ordering rules."
- Channel: direct outbound to small web/design/marketing agencies.
- Metric: 10 discovery calls or 1 paid setup.
- Guardrail: no training on other people's non-public data; every demo only
  with a public website or data provided with consent.

### Experiment B: Lazurio Example Organization AI visibility audit

- Inspiration: Launch Club, Reddit Agency, Peekaboo/AI visibility pattern
- Offer: "We find out where the brand appears in Google/Reddit/AI answers and
  propose a transparent content plan."
- Channel: founder-led outreach to B2B SaaS and agencies.
- Metric: 5 paid audits at a fixed price.
- Guardrail: no fake accounts, no fake engagement, no stealth testimonials.

### Experiment C: Productized agentic automation service

- Inspiration: DesignJoy, SimpleWeb, cold email agency
- Offer: "One active automation request queue for a monthly fee: research,
  enrichment, report, connecting to tools."
- Channel: personal network and companies that already want AI adoption.
- Metric: 1 paying subscription client or 3 paid pilots.
- Guardrail: external actions and outreach only after human approval.

## Next step

I propose opening a deep dive for three candidates:

1. Chatwith / Chatbase: B2B white-label agent.
2. Launch Club / AI visibility: a reputationally safe version of AI-search
   presence.
3. DesignJoy-for-automation: the fastest paid service without developing a
   SaaS.
