# Hook rate, attention and viewer retention in video advertising — and how Apple's ads relate to these mechanics

Research date: November 2026. Method note for the report writer: findings below come from web-search result summaries (22 tool calls). I could not open most primary pages in full; system1group.com was unreachable from this session (network allowlist), so System1 figures are taken from search excerpts and trade press. Reliability labels used throughout: **[P]** platform-published, **[R]** research firm / academic, **[T]** trade press, **[A]** agency or ad-tech vendor blog (lower reliability), **[P-comm]** platform-commissioned study (vendor interest; treat as directional).

## 1. Definitions and benchmarks: hook rate, hold rate, thumb-stop, view-through, YouTube retention, skip rates

### Takeaway
No platform publishes an official hook-rate or hold-rate benchmark; every circulating number is a vendor/agency figure, and they disagree. The only large dataset with a stated method puts average Meta hook rate around 25%; cross-platform comparison is invalid because each platform counts a "view" differently (Meta 3s, TikTok 2s/6s, LinkedIn 2s, YouTube 30s).

### Cited Findings
**Definitions**
- Hook rate = 3-second video views ÷ impressions; hold rate = ThruPlays ÷ 3-second views. Both are calculated (custom) metrics, not native Meta columns. [A] — [Billo](https://billo.app/blog/hook-rate-to-hold-rate)
- "Thumb-stop ratio" is used by vendors as a synonym for hook rate (same formula). [A] — [Motion](https://motionapp.com/blog/key-creative-performance-metrics)
- YouTube: a view on a skippable in-stream ad is counted when the viewer watches 30 seconds or to the end, whichever comes first (or interacts). View rate = views ÷ impressions. [P] — [Google Ads Help](https://support.google.com/google-ads/answer/2375431?hl=en)
- LinkedIn: View rate = views ÷ impressions × 100; completion rate = completions ÷ video impressions. In March 2025 LinkedIn changed the completion-rate denominator from plays to impressions to align with the MRC video view rate standard, so pre-2025 benchmarks are not comparable. [P] — [LinkedIn Help](https://www.linkedin.com/help/linkedin/answer/85305)
- TikTok: a "6-second video view" counts plays of at least 6 seconds, full plays of shorter videos, or an engagement within the first 6 seconds. [A, citing TikTok definition] — [Strike Social](https://strikesocial.com/blog/tiktok-video-view-ads-metrics/)
- TikTok counts a view at 2 seconds, so its rates run structurally higher than Meta's for identical creative; do not compare across platforms. [A] — [Billo](https://billo.app/blog/hook-rate-to-hold-rate)

**Meta benchmarks (all agency/vendor — lower reliability)**
- Largest dataset with a published method: 88,329 sales-objective Meta video ads, H1 2026, average hook rate 25.44% (up from 24.42% in H2 2025). Caveat: Billo's own customer panel, sales objective only, skewed to UGC/DTC. [A] — [Billo](https://billo.app/blog/hook-rate-to-hold-rate)
- Billo explicitly declines to publish a hold-rate benchmark because it found no large panel with a stated method. [A] — [Billo](https://billo.app/blog/hook-rate-to-hold-rate)
- Other vendor bands in circulation: hook rate 20–25% "typical", 30–40% as a target zone attributed to Motion, 40%+ "elite"; hold rate 40–50% "typical", with another source calling ~25% "good" and under 30% "weak" — i.e. the bands contradict each other. Exact attribution of each band to a specific blog was not verified. [A] — [Motion](https://motionapp.com/blog/key-creative-performance-metrics); [Vaizle](https://insights.vaizle.com/hook-rate-hold-rate/); [Madgicx](https://madgicx.com/glossary/hook-rate)
- Several vendors recommend benchmarking against the account's own trailing 90-day average rather than published bands. [A] — [Webtonic](https://www.webtonic.io/blog/how-to-read-creative-fatigue-hook-hold-rate)

**YouTube skippable in-stream**
- Cross-industry average view rate 31.8% on TrueView in-stream (30s-view definition), implying roughly two-thirds of impressions end without a counted view. Vendor report, 2026. [A] — [Digital Applied](https://www.digitalapplied.com/blog/youtube-ads-benchmarks-2026-cpv-cpm-ctr-industry)
- WebFX gives 15–25% view rate for skippable ads. [A] — [WebFX](https://www.webfx.com/blog/marketing/youtube-ad-benchmarks/)
- Strike Social reports much higher figures (64.9% view rate in 2024, up from 61.98% in 2023; 74.0% for skippable CPV campaigns in Q2 2025) — almost certainly a different campaign mix/buying type, so not comparable with the above. Linked PDF is the likely source document; not opened. [A] — [Strike Social benchmark PDF](https://cdnc.heyzine.com/flip-book/pdf/11f948d5f9723a1c88c204e911506de3ff0d9018.pdf)

**TikTok**
- No official 6-second view-rate benchmark found. Vendor rules of thumb range from "aim for 20%+" to "40%+" of impressions reaching 6s; another calls >10% good and >20% excellent. [A] — [Dataslayer](https://www.dataslayer.ai/blog/tiktok-ads-reporting-metrics-dashboards-2025); [Affect Group](https://affectgroup.com/blog/tiktok-ads-video-metrics-how-to-measure-analyze-and-improve-performance/)
- Organic context: on average only ~10% of users watch a full TikTok (Dash Social 2025 benchmark report, brand organic content). [A] — [Dash Social](https://www.dashsocial.com/blog/tiktok-benchmarks)

**LinkedIn**
- No official LinkedIn video benchmark. ZenABM 2026 dataset: median view-through rate 39.5% (view = 2s playback with ≥50% of pixels in view). [A] — [ZenABM](https://zenabm.com/blog/linkedIn-video-ads-benchmarks/)
- Another guide: 20–30% of impressions become 3s+ views; videos under 30s see 35–45% completion. Differences are mostly definitional. [A] — [NAV43](https://nav43.com/blog/linkedin-video-ads-benchmarks-specs-strategies-for-2025/)
- LinkedIn's own material gives relative lifts only (e.g. time-sensitive offers drive 1.2× average video completion rate; playbook dated 2022). [P] — [LinkedIn Video Ads Playbook](https://business.linkedin.com/content/dam/me/business/en-us/amp/marketing-solutions/pdf/NAMER_Video-Ads-Playbook-v02-03-2022.pdf)

### Inferences
- Working ranges a small advertiser can use as a sanity check, not a target: Meta hook rate ~25% average / 30%+ good; YouTube skippable view rate ~15–32%; LinkedIn 2s view rate ~40% median. All are vendor numbers.
- The defensible practice is internal: track hook rate, hold rate and a cost metric per creative against the account's own trailing average, and compare creatives only within one platform and placement.
- Hook and hold rate diagnose different problems: low hook = opening frame/first line fails; good hook with low hold = the body does not pay off the opening.

### Gaps
- No platform-published absolute benchmark for hook rate, hold rate, or 6s view rate on any platform was found.
- No authoritative published "typical" YouTube audience-retention curve for ads (the Rise of Viewer Choice research PDF exists at thinkwithgoogle.com but was not opened). YouTube skip-rate figures are derived from view rates, not stated directly.
- Hold-rate benchmarks are essentially unsupported by any transparent dataset.

## 2. Attention research: how attention converts into memory and sales

### Takeaway
Independent attention research agrees on three things: most digital impressions get almost no active attention; format sets the ceiling on attention more than creative does; and seconds of attention relate to recall and choice with diminishing returns. The "8-second goldfish attention span" is a myth with no traceable evidence.

### Cited Findings
- Karen Nelson-Field (Amplified Intelligence) describes 2.5 seconds of active attention as the "attention memory threshold" that has held across years of research. [R, via interview] — [Creative Salon](https://creative.salon/articles/features/vccp-media-dr-karen-nelson-field-hacking-the-attention-economy)
- Nelson-Field: 85% of digital impressions receive less than 2.5 seconds, i.e. below the level needed to form or refresh memory. [R, via trade press] — [Bizcommunity](https://www.bizcommunity.com/article/karen-nielsen-field-the-attention-deficit-how-to-overcome-it-510470a)
- Platform ceilings quoted by Nelson-Field: roughly 2 seconds on Facebook, 3.5 on TikTok, 10+ on YouTube. Secondhand interview quote; underlying study not located. [R, via trade press] — [Bizcommunity](https://www.bizcommunity.com/article/karen-nielsen-field-the-attention-deficit-how-to-overcome-it-510470a)
- Qualification: VCCP Media / Amplified research found that distinctive brand assets can build recognition in about 1.5 seconds — but without distinctive assets a brand is not remembered at 1.5 seconds. [R, agency co-authored] — [Creative Salon](https://creative.salon/articles/features/vccp-media-dr-karen-nelson-field-hacking-the-attention-economy); [Think with Google](https://business.google.com/in/think/future-of-marketing/future-of-attention-human-centric-ai-marketing/)
- Amplified states that active attention seconds predict mental availability better than impressions or viewability. [R, own claim] — [Amplified](https://www.amplified.co/insight/how-attention-fuels-mental-availability)
- Dentsu Attention Economy (from 2018, with Lumen eye-tracking): attention predicts outcomes three times better than viewability; UK controlled tests had a total sample of over 2,600. [R, agency-led] — [Dentsu](https://www.dentsu.com/sg/en/insights/attention-economy-2021); [Lumen Research](https://lumen-research.com/?p=1325)
- Dentsu experiments (UK, US, Australia), as reported by Mark Ritson: 2 seconds of dwell time corresponds to 28% prompted recall; 14 seconds almost doubles it. [T, citing R] — [Marketing Week](https://www.marketingweek.com/ritson-pay-attention-to-attention/)
- Dentsu 2019 US study: recall 21% for ads viewed under one second versus 41% for ads watched more than 10 seconds. Regional blog; methodology may differ from the global study. [R, agency blog] — [Dentsu](https://www.dentsu.com/sg/en/blog/boosting-consumer-engagement-in-a-distracted-world)
- Dentsu "The Brand Reset" (April 2026, with Kantar and Lumen) claims the first quantified link between attention, brand equity and short- and long-term sales; returns diminish beyond approximately 20 seconds of active viewing. [R, agency-led] — [Dentsu Brand Reset PDF](https://s3.amazonaws.com/media.mediapost.com/uploads/DENTSU__Brand_Reset_April_2026.pdf)
- Ebiquity "The Challenge of Attention" (with Lumen and TVision) combines Ebiquity cost data, Lumen digital attention and TVision TV attention into aCPM — cost per thousand seconds of attention. [R] — [Ebiquity](https://ebiquity.com/news-insights/research/the-challenge-of-attention/)
- Goldfish myth: the BBC's 2017 investigation found the widely cited Microsoft Canada report was not the origin of the 8-second statistic; it traced to "Statistics Brain" with no traceable study. Sources conflict on whether the Microsoft report displayed the figure in a graphic. No evidence goldfish have short attention spans. [R/T] — [Univ. of Wisconsin course document](https://internet.psych.wisc.edu/wp-content/uploads/532-Master/532-UnitPages/Unit-09/Goldfish_MythBusting.pdf); [ScienceBlog](https://scienceblog.com/t-humans-eight-second-attention-span-goldfish-myth/)
- Psychologist Michael Posner: no real evidence that human ability to pay attention has changed since it was first studied in the late 1800s. [R, via T] — [ScienceBlog](https://scienceblog.com/t-humans-eight-second-attention-span-goldfish-myth/)
- Nielsen Catalina Solutions (≈500 campaigns, 2016–early 2017): creative accounted for 47% of sales contribution from advertising (a later NCS cut cites 49%: 47% message/quality + 2% context). CPG TV-heavy sample; dated. [R] — [Nielsen](https://www.nielsen.com/insights/2017/when-it-comes-to-advertising-effectiveness-what-is-key/?lang=en-US); [MarketingCharts](https://www.marketingcharts.com/television-80662)

### Inferences
- The practical reading of "2.5 seconds" for a small advertiser: assume most viewers give under 2–3 seconds, so the brand/product must be identifiable inside that window. A 3-second view (the hook-rate numerator) is roughly the threshold at which memory formation becomes plausible, which is why hook rate is a meaningful proxy rather than a vanity metric.
- Apple can be recognised in ~1.5 seconds because it owns distinctive assets (product silhouettes, typography, white space, sound). A small unknown brand does not have these and must state the brand explicitly and early.
- Attention shows diminishing returns (Dentsu: beyond ~20 seconds); for a small budget, more reach at 3–10 attentive seconds likely beats fewer long views.

### Gaps
- Amplified Intelligence's primary platform-by-platform attention-seconds dataset was not located; figures here are secondhand quotes.
- TVision-specific numbers and Lumen's published attention norms by format were not retrieved.
- Thales Teixeira's HBS work on the rising cost of attention was not retrieved.

## 3. Platform-published creative guidance and its evidence

### Takeaway
Google, Meta and TikTok converge on the same rules: hook in the first 3–6 seconds, brand early, design for sound-off and vertical, show people. The lift figures behind those rules are almost all platform-commissioned and model-predicted rather than independently measured sales results.

### Cited Findings
**Google / YouTube ABCD**
- ABCD = Attention, Branding, Connection, Direction. Google cites a 30% lift in short-term sales likelihood and a 17% lift in long-term brand contribution (Google/Kantar, "The Short & the Long of ABCDs Effectiveness", Global, April 2021). [P-comm] — [YouTube Ads](https://www.youtube.com/intl/en_ae/ads/abcds-of-effective-video-ads)
- Methodology: Kantar scored 11,000 ads through Link AI and analysed 180 creative features; results are predicted outcomes from Kantar's model, not measured campaign sales. [R, commissioned] — [Kantar](https://www.kantar.com/Industries/Technology-and-Telecoms/Validating-Googles-ABCD-framework-with-the-power-of-artificial-intelligence)
- Inconsistency: Google's Help page says "as much as a 30% lift" while Think with Google says "on average … a 30% lift". [P] — [Google Ads Help](https://support.google.com/google-ads/answer/14783551); [Think with Google](https://business.google.com/us/think/future-of-marketing/youtube-video-ad-creative/)

**Meta**
- Core guidance as summarised by third parties: communicate product/brand in the first 3 seconds, design to be understood without sound (feed autoplays muted), use captions/on-screen text, produce 9:16 for Stories/Reels plus 1:1 and 16:9 variants, keep videos short (sources vary: under 15s, or 5–10s). [A, summarising P] — [Brandwatch](https://www.brandwatch.com/blog/facebook-video-ads-best-practices/); [QuickFrame](https://help.quickframe.com/en/articles/8395265-meta-creative-best-practices); [Social Media Today](https://www.socialmediatoday.com/news/Meta-Shares-Key-Video-Ad-Tips/638814/)
- Reported lifts (secondary guide hosted on a third-party site, attributing to Meta): ads designed for sound-off drive 38% more brand interest; showing the brand in the first three seconds drives 44% more brand interest. Not verified against a Meta primary page. [A, citing P] — [Lumanu guide](https://coda.io/@haley-omick/lumanu-bca-external-guide/best-practices-9)

**TikTok**
- Official help page: land the hook in the first 6 seconds using suspense, surprise or emotion; state the proposition within the first 3 seconds; text overlays at 5–10 words per second. [P] — [TikTok Ads Help](https://ads.tiktok.com/help/article/creative-best-practices?lang=en)
- TikTok Creative Codes (2022–2023): ~90% of ad recall impact and ~80% of awareness impact are captured within the first 6 seconds; suspense early in a story +16% watch time; surprise 1.7× view-through rate. [P] — [TikTok Creative Codes PDF](https://www.tiktok.com/business/library/Creative_Codes_May_2023.pdf)
- TikTok × Metrixlab hook analysis (2023, hosted by VidMob): certain visual elements doubled engagement and raised purchase intent by 43% in the first six seconds; human + product together in the first 6 seconds gave +5% 6-second view-through versus average; on-screen logos were perceived as "too commercial". [P-comm] — [VidMob × TikTok PDF](https://www.vidmob.com/wp-content/uploads/2024/02/Vidmob-x-Tik-Tok-Hook-Analysis-.pdf)
- TikTok × CreatorIQ report: showing a creator or any person in the first couple of seconds increases "hooking power" by 50% and ad recognition by 32%. [T, citing P-comm] — [Marketing Brew](https://www.marketingbrew.com/stories/2023/12/18/pay-attention-to-me-report-shares-brand-tips-for-catching-users-interest-on-tiktok)

**System1 (with TikTok) on short-form — "The Long and Short (form) of it"**
- Sample: 8,000 heavy TikTok users across US, UK, DE, FR, IT, ES. Brand recognition in the first two seconds: 57% more happiness and 19% less attention decay; well-branded early content +25% brand choice. [P-comm] — [TikTok for Business](https://ads.tiktok.com/business/en-US/blog/creative-effectiveness)
- Sonic brand assets within the first two seconds had the biggest effect on brand awareness lift (+191%). [T] — [B&T](https://www.bandt.com.au/attention-is-skippable-system1-reveals-how-to-harness-the-magic-of-tiktok/)
- Fluent characters (brand mascots in a role): +57% per [Chief Marketer](https://chiefmarketer.com/system1-tiktok-study-branding-elements-and-creator-led-content-improve-short-form-video-ads/); +67% per [B&T](https://www.bandt.com.au/attention-is-skippable-system1-reveals-how-to-harness-the-magic-of-tiktok/) — sources conflict.
- 4- and 5-star (high-emotion) ads: 1.7× ad recall lift, 2.5× awareness lift, 2.9× association lift; ads creating happiness and surprise show +15% emotional intensity. [P-comm] — [TikTok for Business](https://ads.tiktok.com/business/en-US/blog/creative-effectiveness)

### Inferences
- There is a real tension inside TikTok's own evidence: logos read as "too commercial" (Metrixlab) yet brand recognition in the first 2 seconds improves emotion and brand choice (System1). The reconciliation is that the brand should enter through native elements — product in hand, person, sound, a recognisable visual style — rather than a logo slate.
- Because ABCD and similar lifts are model-predicted and platform-commissioned, they are best treated as a checklist of low-cost hygiene factors, not as a forecast of sales uplift.

### Gaps
- Meta's own primary best-practice pages and their lift statistics were not retrieved; a widely repeated claim that 65% of people who watch the first 3 seconds watch at least 10 seconds is attributed to Meta in secondary articles but I could not tie it to a primary URL.
- Kantar and Ipsos stand-alone findings on storytelling arcs, music and humour (outside the ABCD validation) were not retrieved.

## 4. Narrative devices that sustain watching: evidence versus folklore

### Takeaway
The best academic evidence (Teixeira, Wedel & Pieters) supports surprise to gain attention, repeated rising bursts of joy to retain viewers, and brief repeated brand appearances instead of long logo holds. "Open loops" and "pattern interrupts" are supported by theory and platform-commissioned data, but no study measuring them directly against ad watch time or skip rate was found.

### Cited Findings
- Teixeira, Wedel & Pieters, "Emotion-Induced Engagement in Internet Video Advertisements" (Journal of Marketing Research, 2012): used facial-expression tracking, eye tracking and zapping behaviour. The level of surprise most affects attention concentration; the velocity (rate of increase) of joy most affects viewer retention; the joy effect is asymmetric (gains from increases exceed losses from decreases). [R] — [Tilburg University](https://research.tilburguniversity.edu/en/publications/emotion-induced-engagement-in-internet-video-ads/)
- Same work, HBS summary: ads retain viewers better with several short snippets of joy in succession than with one sustained period of joy. [R] — [HBS Working Knowledge](https://www.library.hbs.edu/working-knowledge/creating-online-ads-we-want-to-watch)
- Teixeira, Wedel & Pieters, "Moment-to-Moment Optimal Branding in TV Commercials" (Marketing Science, 2010): eye-tracking and zapping data on 31 commercials; "brand pulsing" (brief repeated brand appearances, holding total brand exposure constant) significantly reduces commercial avoidance; attention dispersion strongly predicts avoidance. [R] — [Tilburg University](https://research.tilburguniversity.edu/en/publications/moment-to-moment-optimal-branding-in-tv-commercials-preventing-av/); [HBS Working Knowledge](https://www.library.hbs.edu/working-knowledge/improving-brand-recognition-in-tv-ads)
- Information-gap theory in current form: Golman, Loewenstein, Molnar & Saccardo (CMU, 2021) model curiosity as a drive to close specific, salient unanswered questions; a decision-research study, not an ad study. [R] — [CMU](https://www.cmu.edu/dietrich/sds/docs/golman/the-demand-for__and-avoidance-of__information.pdf)
- Closest ad-specific curiosity evidence: a 2024 Frontiers in Psychology paper (five experiments) found incomplete gameplay video ads — especially ones showing failure — raised willingness to play versus complete "win" videos, mediated by curiosity; outcome was download intent, not watch time. [R] — [Frontiers in Psychology](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2024.1374649/full)
- Platform-reported (not peer-reviewed): suspense early in a story +16% watch time; surprise 1.7× view-through on TikTok. [P] — [TikTok Creative Codes PDF](https://www.tiktok.com/business/library/Creative_Codes_May_2023.pdf)
- Creator folklore: the claim that a curiosity gap must be paid off because YouTube limits reach for high click-through with low watch time comes from a practitioner blog, not a study. [A] — [Descript](https://www.descript.com/blog/article/the-youtubers-guide-to-the-curiosity-gap-how-to-keep-your-audiences-interest)

### Inferences
- Evidence ranking: (1) surprise early, joy in rising pulses, brand pulsing — peer-reviewed with behavioural data, though from 2010–2012 desktop/TV contexts; (2) suspense/surprise/people-first openings — platform data, directionally consistent; (3) specific cut-frequency rules ("change the shot every 2 seconds"), "pattern interrupt" formulas and exact payoff timing — no evidence found, treat as folklore to be A/B tested.
- The app-ad finding (showing an unfinished or failing attempt beats showing a polished win) is directly transferable to software demos: open on the problem or an unresolved state, not on the finished dashboard.

### Gaps
- No study found that measures open loops, pattern interrupts, visual change frequency or sound design against skip rate or retention curves in ads.
- Loewenstein's original 1994 paper was not retrieved directly; only the 2021 successor paper.

## 5. Apple specifically: how its ads relate to these mechanics, and what data exists

### Takeaway
There is no reliable public data on Apple's hook rate, hold rate or watch-through on any platform — any such number would be invention. The available proxies (System1 emotional-response scores, YouTube Leaderboard placement, award-entry claims) show that Apple's results are uneven: its celebrated craft films often score low on emotional-response testing, while its warm, character-led films score at the top.

### Cited Findings
- System1 on "The Underdogs" (2019): scored only 1 star despite being celebrated and awarded; the 2020 work-from-home sequel scored 2 stars. System1 notes many of Apple's most celebrated ads score low. Via search excerpt; page not opened. [R] — [System1](https://system1group.com/blog/apple-unpeeled-what-can-brands-learn-from-its-ads)
- "Crush" (iPad Pro, May 2024): 1.9 stars on System1 Test Your Ad (scale 1.0–5.9; 1.0–1.9 is "low"); a reversed cut scored 1.8. [T, citing R] — [LBBOnline](https://lbbonline.com/news/apple-crush-scores-19-stars-with-system1)
- Follow-up iPad Pro ad "Worlds Made on iPad": 1.5 stars, lower than "Crush". [T, citing R] — [LBBOnline](https://lbbonline.com/news/new-ipad-pro-ad-scores-worse-than-crush); [Marketing Beat](https://www.marketing-beat.co.uk/2024/06/05/apple-ipad-system1)
- High scorers: "The Invincibles" 5.4 stars and "The Greatest" 3.8 stars per trade coverage of the "Crush" comparison; System1 describes "The Invincibles" as Apple's first 5-star ad in its database. [T/R] — [LBBOnline](https://lbbonline.com/news/apple-crush-scores-19-stars-with-system1); [System1](https://system1group.com/?p=14479)
- Holiday film "A Critter Carol" (2025) is reported at an "exceptional" 5.4 stars in System1's top global ads of 2025. Note: the same 5.4 figure appears for two different Apple ads across sources — verify before quoting. [T, citing R] — [Advanced Television](https://www.advanced-television.com/2026/01/06/system1-top-10-global-ads-from-2025)
- Kantar assessed that the Apple brand was not materially damaged by "Crush". [R] — [Kantar](https://www.kantar.com/north-america/Inspiration/Brands/Apple-brand-far-from-crushed-by-the-iPad-ad-stumble)
- YouTube Ads Leaderboard: Apple's "Escape from the Office" (the Underdogs series, 2022) was the eighth most-watched YouTube ad of its year. [T] — [MacMagazine](https://macmagazine.com.br/post/2022/06/20/apple-emplaca-anuncio-entre-os-mais-assistidos-do-youtube/)
- Apple appeared at the top of System1's monthly most-effective US ads lists in 2022–2023. [T] — [The Drum, Aug 2023](https://www.thedrum.com/news/2023/08/31/apple-wins-out-the-top-5-us-ads-august); [The Drum, June 2022](https://www.thedrum.com/opinion/2022/06/29/apple-aviation-gin-junes-5-most-effective-us-ads)
- Vertical: "Shot on iPhone — Vertical Cinema" (2020), a nine-minute film directed by Damien Chazelle on iPhone 11 Pro, shot entirely in vertical. [T] — [MacRumors](https://www.macrumors.com/2020/08/05/apple-shares-vertical-shot-on-iphone-video/)
- Award-entry claims (self-reported by Apple/agency, unaudited): student vertical shorts were released on Apple's Instagram handle "to 25 million people", and campaign content was the most popular in Apple's history on the platform. [T, self-reported] — [Cannes Lions / Love the Work](https://lovethework.com/work-awards/campaigns/shot-on-iphone-by-damien-chazellevertical-cinema-705165)
- The Shot on iPhone film series continues: "Big Man" (June 2025), shot on iPhone 16 Pro, directed by Aneil Karia. [P/T] — [Apple Newsroom](https://www.apple.com/uk/newsroom/2025/06/apple-presents-big-man-a-short-film-shot-on-iphone-16-pro); [MacRumors](https://www.macrumors.com/2025/06/18/apple-shot-on-iphone-16-pro-short-film/)
- Apple Search Ads (Apple as ad platform, relevant if Ampeon ships an iOS app). 2025 search-results campaigns: average tap-through rate 9.7%, conversion rate 66.2%, cost per tap $2.25 (top 15 categories), cost per acquisition $3.76; Finance $13.28 and Sports $19.74 CPA at the expensive end. Vendor data from SplitMetrics' own customers. [A] — [SplitMetrics](https://splitmetrics.com/blog/apple-search-ads-cost)
- MobileAction: conversion rate 65.82% at end of 2025 (66.70% in 2024); CPT from $1.26 in Q2 to $1.88 in Q4. AppTweak: US median CPT $1.91, median CPI $1.80. Definitions differ between vendors. [A] — [MobileAction](https://www.mobileaction.co/report/apple-search-ads-2025-benchmark-report/metrics-analysis-of-search-results-ads/); [AppTweak](https://www.apptweak.com/en/aso-blog/apple-ads-benchmarks)

### Inferences
- Apple does break the performance rules — long films (several to nine-plus minutes), late or minimal logo, often no voiceover, story before product. It can because (a) its distinctive assets make it identifiable in ~1.5 seconds without a logo (see section 2), (b) it has near-universal awareness, so late branding does not cause misattribution, (c) it buys and earns reach at a scale where completion rate matters less, and (d) owned channels and press coverage distribute long films to people who chose to watch. None of these conditions holds for a small software company.
- The System1 pattern is the useful lesson: Apple's product-as-hero spectacle ("Crush", "Worlds Made on iPad") and insider-humour films ("The Underdogs") test poorly with the general public, while human, warm, character-driven work ("The Invincibles", "A Critter Carol") tests at the top. Craft and awards are not the same as broad emotional response. What transfers from Apple is one idea per film, people before product, product shown doing the job, strong sound — not the long running time or the late reveal.
- "The Underdogs" is evidence that a niche-audience film can be effective for a specific segment (business buyers) despite low mass-audience scores — relevant for B2B, but this is my inference, not a measured result.

### Gaps
- No public data on Apple's hook rate, hold rate, view-through rate, skip rate or audience-retention curves. Apple does not disclose these and no third party publishes them.
- View counts and watch-through for "The Underdogs", Shot on iPhone films and holiday films were not retrieved; YouTube public view counts mix paid and organic views and would be a weak proxy in any case.
- No iSpot or DAIVID attention/emotion scores for Apple spots were found in this session.
- Current @apple follower counts on Instagram/TikTok and #ShotOniPhone post volume were not found; these change constantly and should be read from the live profiles.
- No YouTube Ads Leaderboard entry for Apple in 2024 or 2025 was confirmed.
- A systematic analysis of how Apple structures the first 3 seconds of its social cuts was not found; this would require first-hand viewing and coding of the ads.
- system1group.com could not be opened from this session; it has to be allowed in the session's network settings to verify the System1 figures at source.

## 6. Short-term performance versus long-term brand creative; priorities for a small B2B / software advertiser

### Takeaway
The evidence base recommends roughly balanced brand and activation spend in B2B (about 46/54) because most buyers are not in-market at any moment, and "creative fatigue" is far rarer than performance marketers assume — the usual problem is audience saturation. A small advertiser should make a few distinctive, clearly branded ads and keep running them, rather than churn new variants.

### Cited Findings
- Binet & Field for the LinkedIn B2B Institute (2019): B2B businesses grew best with about 46% of budget on brand building and 54% on activation; 10 points of extra share of voice was associated with 0.7 points more market share. Based on award-entered case studies (IPA Databank) — correlational, a guide not a law. [R, platform-sponsored] — [The Drum](https://www.thedrum.com/opinion/2019/05/23/exclusive-look-binet-and-field-s-new-b2b-marketing-research); [LinkedIn](https://business.linkedin.com/en-uk/marketing-solutions/blog/posts/B2B-Marketing/2019/How-B2B-marketing-really-drives-growth)
- The B2C reference point from the same authors is roughly 60/40 brand to activation; 46/54 is the B2B adjustment. [A, summarising R] — [Blck Alpaca](https://blckalpaca.at/en/knowledge-base/social-media/social-media-fundamentals-strategy/brand-vs-performance-marketing-95-5-rule)
- 95-5 rule (LinkedIn B2B Institute): about 95% of B2B buyers are out-of-market at any time and 5% in-market, so lead-generation creative addresses only a small slice. [P/R] — [LinkedIn B2B Institute whitepaper](https://business.linkedin.com/content/dam/lem/business/en/advertise/resources/b2b-institute/b2branding-whitepaper-final.pdf)
- Creative wear-out: Analytic Partners analysed 51,218 pieces of creative and found genuine wear-out in only 14. [R, via T] — [Advertising Week](https://advertisingweek.com/aw360/news/when-more-becomes-less-debunking-the-advertising-wear-out-fallacy/6053/); [Marketing Week](https://www.marketingweek.com/consumers-tired-ads-marketers/)
- The argument that social suffers from audience saturation rather than creative wear-out. [T] — [Mediaweek](https://www.mediaweek.com.au/social-isnt-suffering-from-creative-wear-out-its-suffering-from-audience-saturation)
- Counter-evidence from Meta: an Analytics @ Meta regression analysis (cited as May 2023; another article dates it 2022) found a 45% average drop in conversion likelihood after four repeated exposures to the same ad; in high-fatigue cases adding new creative variations lifted conversion rate by an average of 8%. Platform-interested; the average ignores time window and placement. [P, via T] — [AdNews](https://adnews.com.au/news/when-every-marketing-dollar-matters-don-t-waste-yours-on-fatigued-creative)
- LinkedIn frames 2-second view rate as an upper-funnel awareness metric and completion rate as the more relevant metric for brand campaigns. [P] — [LinkedIn Help](https://www.linkedin.com/help/linkedin/answer/85305)
- App-install context: Apple Search Ads converts at ~66% tap-to-install because it captures existing intent, at $1.80–$3.76 per install on average. [A] — [SplitMetrics](https://splitmetrics.com/blog/apple-search-ads-cost); [AppTweak](https://www.apptweak.com/en/aso-blog/apple-ads-benchmarks)

### Inferences
- The two fatigue findings are compatible: frequency against the same small audience depresses response (Meta), but the creative itself rarely wears out across a market (Analytic Partners). A small advertiser with narrow targeting hits saturation quickly; the remedy is broader reach or a few variants of the same idea, not abandoning a working ad.
- Suggested priority order for a small software company: (1) one clear idea with the brand and product identifiable in the first 2–3 seconds, sound-off legible, vertical-first; (2) capture existing demand cheaply (search, Apple Search Ads if applicable) before paying for attention; (3) a small always-on brand layer aimed at the 95% not in-market, measured on reach, hook rate and completion rather than leads; (4) test hooks (first 3 seconds) before testing bodies, since hook rate caps everything downstream.
- Suggested measurement set: hook rate (3s views ÷ impressions), hold rate (ThruPlay ÷ 3s views), cost per ThruPlay, click-through and cost per qualified action — each compared with the account's own trailing 90-day average, per platform.

### Gaps
- No study found that tests brand/performance splits specifically for small-budget software companies; Binet & Field's data come from large award-entered campaigns.
- The Meta 45% fatigue figure could not be traced to a primary Meta publication, and its date is inconsistent across sources.
- No independent evidence specific to B2B SaaS video hook or hold rates was found.
