# Research sprint: copyable online money mechanisms

Moved from the Organization root (company/archive and company/agents/reference) during the GEN3 migration.

Verified: 2026-05-22

Scope: find existing online projects, companies or solo operators with a
verifiable monetization signal in the categories micro-SaaS, directories, data
products, templates, Chrome extensions, newsletters and niche tools. The goal
is not to copy a brand, content, databases or identity, but to legally adapt
the mechanism using agents.

## Shortlist

| Candidate | Category | Revenue / monetization signal | Mechanism | What the company can adapt | What not to copy | Risks | Confidence |
|---|---|---|---|---|---|---|---|
| Remote Leaf | directory / curated newsletter | The open startup page states 209 paid subscribers, MRR ~$1,610, ARR ~$19,410; pricing and testimonials are public. | A curated feed of remote jobs, personalized email notifications, subscription. | A vertical curated job/opportunity feed for a narrow professional group; agents can sort sources, deduplicate offers, write summaries and check fit. | Do not copy the job database, copy, design or testimonials; do not aggregate sources against ToS. | Low MRR, dependency on source quality, the job-board market is crowded. | 5 |
| ScrapingBee | micro-SaaS / developer API | Case studies report growth to $1M ARR and later $5M ARR + exit; pricing is public. | An API that handles proxies, headless browsers and scraping infrastructure for developers. | Narrowly focused "data extraction as a service" for a specific legal use case, e.g. public pricing monitors or public directory enrichment. | Do not copy the infrastructure, texts or API surface; do not do scraping that ToS forbids or privacy-invasive collection. | Legal and platform risk of the scraping market, high infra costs, anti-bot arms race. | 5 |
| Bannerbear | micro-SaaS / media automation API | Public pricing $49-$299/mo; Indie Hackers mentions a portfolio over $1M ARR and Bannerbear close to $1M ARR. | Template-based image/video generation API for marketers and automations. | A vertical asset generator for a specific workflow, e.g. offers, reports, real-estate listing visuals or B2B outbound visuals. | Do not copy the brand, templates, UI, API names or assets. | Differentiation from Canva and AI image tools; the need for a clear use case and integrations. | 4 |
| Carrd | niche tool / micro-SaaS | SaaS Podcast reports over $100K MRR and 4M hosted sites; Indie Hackers reports ~$167K/mo / $2M ARR; pricing starts at $9/year. | An extremely simple one-page website builder with freemium and a low annual price. | A vertical builder for one narrow job, e.g. lead-capture pages for local services, agent-generated landing pages or microsites for offers. | Do not copy the editor, templates, branding, UX details or free-site virality through someone else's brand. | Crowded market, low ARPU, support burden, AI site builders. | 4 |
| BuiltWith | data product / technographics | Official pricing $295-$995/mo and Team Ultra $6,000/yr; Latka reports $22.6M revenue; the official page cites data from 491.9M domains. | A technographic database and lead lists by the technologies used. | A smaller niche data product: public signals for one technology/segment, enriched with agentic analysis and exports for sales. | Do not copy BuiltWith data, detection signatures, customer lists or enrichment. | Data freshness, legal/ToS boundaries, commoditization, demanding collection. | 4 |
| GummySearch | data product / niche research SaaS | Pricing $29-$199/mo; Arrfounder reports $35K MRR before it stopped taking new business; official pricing says the service is closed as of 2025-11-30. | Reddit audience research: finding communities, pains, trends and customer signals. | An agentic research workflow over permitted sources: pain-point monitoring, source citations, human-reviewed outreach drafts. | Do not copy Reddit data dumps, the Gummy UX, the database, the brand or an automatic spam posting workflow. | Large platform/API risk; this is exactly why the project closed to new customers. | 4 |
| Easlo | templates / digital products | The Gumroad profile shows 7,064 sales of Second Brain at $79; the rest of the template catalog has paid items at $5-$79. | A template catalog with free lead magnets and paid productivity systems. | Niche "operating system" templates for specific roles, e.g. an agentic research OS, experiment OS, client acquisition OS. | Do not copy the databases, copy, names, visual style or PARA packaging. | Saturation of the template market, the need for distribution, support and refunds. | 5 |
| ShipFast | code template / boilerplate | The Indie Hackers case study reports $63K revenue in 60 days; TrustMRR shows current public revenue signals for ShipFast/the portfolio. | A one-time boilerplate for quickly launching a SaaS with auth, payments, email and a landing page. | A vertical agent-ready boilerplate for a specific monetization type, e.g. a directory starter, data product starter or paid newsletter ops kit. | Do not copy the codebase, marketing claims, docs, design or checkout flow. | Quality/security is critical; the boilerplate market is noisy and reputationally sensitive. | 4 |
| Text Blaze | Chrome extension / productivity SaaS | The Chrome Web Store states 600K users and a 4.9 rating; Latka reports $2.4M revenue in 2024; public pricing exists. | A browser text expander and snippets for support, sales, teachers, HR and other roles. | A vertical Chrome extension for one repeated job: agent-reviewed snippets, form filling, support macros or proposal drafting. | Do not copy the extension, snippet library, brand, permissions model or claims. | Browser permissions trust, privacy, Chrome Web Store review, enterprise security. | 4 |
| TLDR Newsletter | newsletter / media business | The official ad site states 7M+ tech professionals, individual newsletters with 280K-1.6M subs and 32-47% open rates; Latka reports $6.4M revenue in 2024. | Curated B2B tech newsletters monetized through sponsorships and performance case studies. | A narrow B2B newsletter with agentic research and sponsorship inventory, e.g. "AI ops opportunities for SMBs" or "agent monetization briefs". | Do not copy the content, editorial voice, subscriber lists, advertising materials or case studies. | The newsletter market has a long growth cycle; sponsorships work only with a quality audience. | 5 |
| HeadshotPro | niche AI tool | The official site states $19.99-$49.99 one-time pricing and 10,000+ customers; the Rewardful case study reports $50K+ monthly affiliate revenue and a +15% revenue contribution. | A narrow AI output product with a clear one-time purchase and affiliate distribution. | An AI service for one specific output with high willingness to pay, e.g. role-specific profile assets, product listing visuals or sales collateral. | Do not copy the model workflow, brand, prompts, sample photos, affiliate copy or customer outputs. | AI commoditization, output quality, privacy/biometric sensitivity, refunds. | 5 |

## First patterns

1. The mechanisms most adaptable for the company are those where agents
   increase throughput without the need to own a large audience: curated
   feeds, niche data products, vertical templates and asset generation.
2. The fastest "first-dollar" tests are probably templates / reports / a
   curated paid feed, because they do not require a finished SaaS or a long
   review process.
3. The biggest risk is platform dependency: GummySearch shows that even a
   working $35K MRR mechanism can end when it relies on someone else's API or
   ToS.
4. The best adaptation for the company will not be a "copy of a company" but
   its own vertical: a specific audience + a specific repeated pain + an
   agentic workflow + transparent sources.

## Sources

- Remote Leaf open metrics: https://remoteleaf.com/open
- ScrapingBee case studies: https://www.foundershut.com/explore/scrapingbee-bootstrapped-saas-1m-arr, https://www.startupsfortherestofus.com/episodes/episode-783-bootstrapping-scrapingbee-to-5m-arr-and-an-8-figure-exit
- ScrapingBee pricing: https://www.scrapingbee.com/pricing/
- Bannerbear pricing: https://www.bannerbear.com/pricing/
- Bannerbear revenue context: https://www.indiehackers.com/post/my-saas-portfolio-crossed-1m-arr-and-bannerbear-will-hit-1m-arr-soon-YbNabGgDDpeniZkjFrzo
- Carrd pricing/docs: https://carrd.co/docs/pro/plans
- Carrd revenue context: https://saasclub.io/podcast/carrd-aj-306/, https://www.indiehackers.com/post/tech/growing-carrd-to-2m-arr-in-a-crowded-market-with-zero-marketing-by-limiting-features-dbeoP4bDlEL3zzsivdgj
- BuiltWith pricing: https://builtwith.com/plans
- BuiltWith revenue context: https://getlatka.com/companies/builtwith
- GummySearch pricing / shutdown notice: https://gummysearch.com/pricing/
- GummySearch revenue context: https://arrfounder.com/news/gummysearch-reaches-35k-mrr
- Easlo Gumroad sales: https://easlo.gumroad.com/
- ShipFast case study: https://www.indiehackers.com/post/case-study-shipfast-made-63k-in-revenue-in-60-days-8jj06RfVwjLR01CSDvxb
- ShipFast current public revenue context: https://trustmrr.com/founder/marclou
- Text Blaze Chrome Web Store: https://chromewebstore.google.com/detail/text-blaze-templates-and/idgadaccgipmpannjkmfddolnnhmeklj
- Text Blaze pricing: https://blaze.today/plans
- Text Blaze revenue context: https://getlatka.com/companies/blaze.today/funding
- TLDR advertising page: https://advertise.tldr.tech/
- TLDR revenue context: https://getlatka.com/companies/tldr-newsletter
- HeadshotPro official pricing/customers: https://www.headshotpro.io/
- HeadshotPro affiliate case study: https://www.rewardful.com/case-studies/headshotpro
