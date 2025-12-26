---
layout: post
title: "Just Checking: Looking for Information in the Age of Generative AI"
date: 2025-12-26
description: "A review of recent research on how generative AI is reshaping information seeking behaviour, trust dynamics and verification strategies."
tags: [generative-ai, information-seeking, trust, verification, research]
categories: [AI, Information Management]
author: "Lewis Dryburgh"
permalink: /2025-12-26-just-checking
---

### Just Checking: Looking for Information in the Age of Generative AI

Eight years ago I completed a master's degree in Information Management. Information Management (for me at least) was a hugely exciting discipline, blending psychology, technology, business and library science in a way that helped me understand my own experience growing up in an increasingly digital world. I joined the workforce at a time when work was still happening on paper, until it wasn't. I was interested in behaviour shifts and digitisation, and how people captured and shared (or didn't) knowledge. For most of my degree (which I studied part time), I worked as a systems trainer, so these concepts were on my mind a lot.

For my dissertation research, I spent three months interviewing and shadowing startup founders about how they managed data and information, how they captured their corporate knowledge, retrieved it and used it. I was interested in the information seeking behaviours they embodied, and I wrote this up in a slightly more accessible form as ['Do you even document bro?'](https://lewisdryburgh.com/2017-11-30-do-you-even-document).

After my masters, I lectured and tutored a couple of modules at the University of Technology Sydney (UTS) in their postgraduate information management course. Then my daughter was born, so I became relatively time poor outside of work, then covid, then post-covid, and really I have not engaged with academic literature or research since then. But I'm on my summer holidays and my kids are getting more self sufficient. I've been working through a pile of recent papers exploring what the heck is happening to the way people seek, retrieve and leverage information in the years since generative AI took off.

Like many, I believe we're in an 'AI' bubble. Companies are laying off staff with pomp and press releases to replace them with bots, then [quietly hiring the humans back](https://www.theinformation.com/articles/story-salesforces-declining-trust-llms-hit-nerve). Tech giants are over-capitalising on AI infrastructure then sheepishly [dropping sales targets for products people aren't buying](https://arstechnica.com/ai/2025/12/microsoft-slashes-ai-sales-growth-targets-as-customers-resist-unproven-agents/). All that said, I do feel, from my own behaviour and observations in and out of work, that the use of gen AI for search and retrieval is impactful and likely here to stay.

I thought I'd do a desktop literature review of what's happening in research, as a way of flexing some old muscles and attempting to keep up to date. Here's what I've found from the last ~18 months of open access research.

### We're Not Searching Anymore, We're Conversing

The first thing that struck me is how fundamentally the act of looking for information has changed. Mayerhofer et al. (2025) describe what they call 'blending' behaviour: users don't just search or chat anymore, they toggle between traditional search engines and conversational AI, often using one to verify the other. Their research shows people asking Google to fact-check ChatGPT, or using ChatGPT to synthesise results from a Google search. It's a hybrid approach that suggests we haven't quite figured out which tool to trust for what.

This shift isn't just about switching tools. Pham et al. (2024) found that in e-commerce contexts, people use longer, more conversational queries when interacting with AI chatbots compared to traditional search. Instead of typing 'wireless headphones under $100', users are more likely to ask 'what are some good quality wireless headphones I can get for under $100?'. The interaction mirrors how you'd ask a shop assistant, rather than query a database.

This conversational style matters because it changes what we're doing cognitively. Traditional search required what researchers call "berrypicking" (Bates, 1989): you'd try different search terms, scan results, refine your query and gradually home in on what you needed. It was iterative and required you to stay critically engaged with whether you were finding good information. Conversation, by contrast, feels more passive. You ask, the AI answers. The loop closes.

### Why We Trust (and Maybe Shouldn't)

This brings us to the thornier question of trust. If we're treating AI systems more like conversational partners than search tools, are we applying the same critical scrutiny?

The short answer appears to be no. Li and Aral (2025) conducted a large-scale experiment and found something unsettling: when AI-generated content includes citations and reference links, people trust it more, even when those citations are incorrect or completely fabricated. The formal markers of credibility (footnotes, links, that academic aesthetic) override our instinct to verify the actual content.

This vulnerability is compounded by anthropomorphism. When AI systems feel more human-like, whether through conversational tone or interface design, we trust them more (Yazan et al., 2025; Huschens et al., 2023). We're also more willing to trade accuracy for personalisation and conversational flow. In other words, if the AI sounds friendly and seems to understand us, we tend to forgive it for being wrong.

Sun et al. (2024, 2025) explored this dynamic specifically in health information seeking, a domain where being wrong has real consequences. Their research revealed a curious mismatch: when people don't know the source of health information, they trust AI-generated content more than human-generated content. But when information is explicitly labelled as coming from AI, people trust it less than human-attributed content. This suggests that transparency matters enormously. We adjust our trust based on what we think we're dealing with, but we're not very good at identifying AI content in the wild.

The research gets more granular. Sun et al. (2025) used eye-tracking, ECG, skin conductance and temperature sensors to measure physiological responses to health information. Machine learning models trained on these signals could predict whether someone trusted the information with 73% accuracy, and could identify whether content was AI or human-generated with 65% accuracy. These numbers are specific to their lab setting and need validation in real-world contexts, but they point to something important: our bodies respond to credibility cues before our conscious minds catch up.

### The Problem With Saying 'I Don't Know'

One design solution you might think would help is having AI systems signal uncertainty. If the model isn't confident, it should say so, right? Unfortunately, it's not that simple.

Li and Aral (2025) found that signalling uncertainty reduces trust and may discourage users from relying on correct information. The effect appears context-dependent, but the basic tension is real: epistemic honesty ("I'm not sure about this") conflicts with user expectations for responsive, confident assistance. Huang et al. (2025) propose a more sophisticated approach called 'confidence-based response abstinence', where AI systems decline to answer when uncertainty is high. But this requires accurate self-assessment from the model and risks frustrating users who expect an answer.

This creates a genuine design dilemma. Systems that admit uncertainty are more epistemically responsible but less trusted. Systems that project confidence are more persuasive but potentially misleading. There's no obvious way to square this circle.

### Who Gets It Wrong (and Who Pays the Price)

Trust dynamics also vary systematically across different user groups. Yazan et al. (2025) found that middle-aged adults show a potentially vulnerable pattern: they express higher trust in ChatGPT but use it less frequently than younger users. This means they have less opportunity to develop calibrated expectations through experience. They're trusting, but not practised.

Meanwhile, users who employ both ChatGPT and traditional search daily show higher trust and greater anthropomorphisation of AI systems. It's unclear whether frequent use causes this, or whether people who are already predisposed to trust AI use it more often. The correlation is there, but causality remains murky.

These patterns matter because they suggest different user groups need different kinds of support. Designing one-size-fits-all AI interfaces assumes everyone brings the same scepticism and verification habits to the table. The research suggests they don't.

### The Systemic Stakes: Verification at Scale

Beyond individual trust calibration, there are broader systemic concerns about AI as an information intermediary. When generative AI sits between us and information sources, it shapes what we're exposed to and potentially amplifies or mitigates misinformation (Hirvonen et al., 2024; Jarrahi et al., 2025).

Kuznetsova et al. (2025) tested this directly by asking LLM-based chatbots to verify political statements. ChatGPT correctly evaluated approximately 72% of tested claims on their dataset, with substantial variability across languages and topics. High-resource languages like English performed better than low-resource languages, raising equity concerns. If AI systems are going to serve as fact-checkers or information gatekeepers, differential performance across linguistic communities means some populations face higher misinformation vulnerability than others.

This challenge is compounded by training data. When multiple AI systems draw from overlapping datasets, the traditional verification strategy of cross-referencing multiple sources becomes less effective. If all the sources consulted the same underlying information (or misinformation), checking three AI-generated answers won't help you triangulate truth.

### The Psychological Dimension

None of this happens in a vacuum. Our emotional states shape how we seek and evaluate information, and GenAI intersects with these dynamics in complex ways.

Research on anxiety and information seeking shows that anxious individuals seek information more frequently, particularly during periods of uncertainty or perceived threat (Charpentier et al., 2022). This heightened vigilance can be adaptive, but it can also lead to maladaptive patterns like excessive reassurance-seeking or rumination. The covid pandemic provided a real-world laboratory for observing these dynamics at scale.

GenAI complicates this picture. Anxious seekers, motivated to resolve uncertainty quickly, may be more susceptible to misleading credibility cues. They might accept formal markers of authority (citations, confident tone) without deeper verification. The conversational nature of AI interactions can reduce the critical distance users typically maintain when evaluating sources, creating conditions where emotional rapport competes with epistemic scrutiny.

### What the Research Tells Us (So Far)

Here's a simplified overview of the key studies and what they found:

| Study | What They Looked At | Main Finding | Important Caveats |
|-------|---------------------|--------------|-------------------|
| Mayerhofer et al., 2025 | How people use search vs chat | Users blend both and toggle between them for verification | Preprint; limited platform diversity |
| Pham et al., 2024 | E-commerce search behaviour | Longer, conversational queries with chatbots | Domain-specific to shopping |
| Li & Aral, 2025 | Trust in AI search results | Citations increase trust even when incorrect | Preprint; experimental setting |
| Sun et al., 2024/2025 | Health information trust | AI content trusted more when source is unknown; labelling matters | Lab-based measures; 2025 paper is advance copy |
| Kuznetsova et al., 2025 | Political fact-checking by chatbots | ~72% accuracy; varies by language and topic | Performance sensitive to task framing |
| Huang et al., 2025 | Managing AI uncertainty | Proposes systems should refuse to answer when uncertain | Requires robust uncertainty estimates |

### The Verification Crisis

Across all these studies, there's a pattern: our credibility judgements are shaped as much by interface signals and situational context as by informational accuracy. We trust citations even when they're wrong. We trust friendly-sounding AI more than cold search results. We trust unlabelled AI content more than labelled AI content. We verify less when we're anxious or when the conversational flow feels natural.

These aren't random quirks. They're predictable vulnerabilities where design affordances and human psychology interact to produce contexts where conventional verification strategies fail.

The philosopher Luciano Floridi (2024) frames this as a fundamental 'decoupling' between agency and intelligence. GenAI acts as an autonomous agent capable of performing complex informational tasks (agency) without any underlying understanding or semantic grasp (intelligence). For information seekers, this creates what he calls a 'semantic capital' risk: as the infosphere fills with persuasive but non-intelligent agents, the burden of sense-making shifts entirely to us. The 'blending' behaviours documented by Mayerhofer et al. (2025) aren't just a technical transition. They're a fundamental adaptation to an environment where the traditional markers of human intent and cognitive accountability have been severed.

### What Needs to Happen Next

The researchers point to several directions that need empirical validation rather than assumption. First, interface mechanisms that communicate provenance and calibrated uncertainty need testing for their effects on both immediate uptake and longer-term trust calibration. Second, platform-level governance (standardised provenance metadata, provenance-aware ranking) needs evaluation for equity implications, particularly given the language- and topic-dependent performance Kuznetsova et al. (2025) documented. Third, interventions to build calibrated expectations (training, explainers, domain-specific literacy programs) should be piloted across demographic groups (Leschanowsky et al., 2024; Huynh & Aichner, 2025).

Methodologically, the field needs longitudinal designs, cross-cultural comparisons and randomised trials that measure actual verification behaviour rather than relying solely on surveys about attitudes and intentions.

### Bringing It Back

When I was researching startup founders eight years ago, I was interested in how people captured and retrieved organisational knowledge. The challenge then was getting people to document at all, to externalise what they knew so others could find it. Now the challenge is almost inverted. Information is abundant, generated faster than we can verify it, by systems that sound authoritative but may not be.

My information management training emphasised context, provenance and the sociotechnical systems that shape how knowledge flows through organisations. Those frameworks feel newly relevant. As generative AI becomes embedded in how we find and evaluate information, understanding the psychological, interface and systemic factors that shape trust and verification isn't just an academic exercise. It's practical infrastructure for navigating an information environment that's fundamentally different from the one I studied eight years ago.

The research suggests we're still figuring out how to navigate this environment. We're blending old and new tools, sometimes effectively, sometimes not. We're trusting surface signals we shouldn't trust. We're building verification habits that may not scale to the systems we're now using. And we're doing all this unevenly, with different populations facing different vulnerabilities.

That's where we are. The bubble may burst, the hype may fade. The fundamental shift in how we seek and evaluate information appears to be here. Understanding it matters.

**AI assistance disclosure**: While the analysis and perspectives here are mine, I used Gemini 3 Pro and Claude Opus 4.5 to code some of the papers I'd collated, fact check my interpretations and (thankfully) format references. All the references below are real, non-hallucinated, open access research papers.

### References

Bates, M. J. (1989). The design of browsing and berrypicking techniques for the online search interface. *Online Review, 13*(5), 407–424. [https://doi.org/10.1108/eb024320](https://doi.org/10.1108/eb024320)

Charpentier, C. J., Cogliati Dezza, I., Vellani, V., Globig, L. K., Gädeke, M., & Sharot, T. (2022). Anxiety increases information-seeking in response to large changes. *Scientific Reports, 12*, 7385. [https://doi.org/10.1038/s41598-022-10813-9](https://doi.org/10.1038/s41598-022-10813-9)

Floridi, L. (2024). On the future of content in the age of artificial intelligence: Some implications and directions. *Philosophy & Technology, 37*(3), 112. [https://doi.org/10.1007/s13347-024-00806-z](https://doi.org/10.1007/s13347-024-00806-z)

Hirvonen, N., Jylhä, V., Lao, Y., & Larsson, S. (2024). Artificial intelligence in the information ecosystem: Affordances for everyday information seeking. *Journal of the Association for Information Science and Technology, 75*(10), 1152–1165. [https://doi.org/10.1002/asi.24860](https://doi.org/10.1002/asi.24860)

Huang, Y., et al. (2025). Confidence-based response abstinence: Improving LLM trustworthiness via activation-based uncertainty estimation. In *Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing*. ACL. [https://arxiv.org/abs/2510.13750](https://arxiv.org/abs/2510.13750)

Huschens, M., et al. (2023). Do you trust ChatGPT? Perceived credibility of human and AI-generated content. *arXiv preprint arXiv:2309.02524*. [https://arxiv.org/abs/2309.02524](https://arxiv.org/abs/2309.02524)

Huynh, M.-T., & Aichner, T. (2025). In generative artificial intelligence we trust: Unpacking determinants and outcomes for cognitive trust. *AI & Society, 40*, 5849–5869. [https://doi.org/10.1007/s00146-025-02378-8](https://doi.org/10.1007/s00146-025-02378-8)

Jarrahi, M. H., Li, L., Robinson, A. P., & Meng, S. (2025). Generative AI and the augmentation of information practices in knowledge work. *Behaviour & Information Technology*. Advance online publication. [https://doi.org/10.1080/0144929X.2025.2551570](https://doi.org/10.1080/0144929X.2025.2551570)

Kuznetsova, E., Makhortykh, M., Vziatysheva, V., Stolze, M., Baghumyan, A., & Urman, A. (2025). In generative AI we trust: Can chatbots effectively verify political information? *Journal of Computational Social Science, 8*, 15. [https://doi.org/10.1007/s42001-024-00338-8](https://doi.org/10.1007/s42001-024-00338-8)

Leschanowsky, A., Rech, S., Popp, B., & Bäckström, T. (2024). Evaluating privacy, security, and trust perceptions in conversational AI: A systematic review. *Computers in Human Behavior, 161*, 108344. [https://doi.org/10.1016/j.chb.2024.108344](https://doi.org/10.1016/j.chb.2024.108344)

Li, H., & Aral, S. (2025). Human trust in AI search: A large-scale experiment. *arXiv preprint arXiv:2504.06435*. [https://arxiv.org/abs/2504.06435](https://arxiv.org/abs/2504.06435)

Mayerhofer, A., et al. (2025). Blending queries and conversations: Understanding tactics, trust, verification, and system choice in web search and chat interactions. *arXiv preprint arXiv:2504.05156*. [https://arxiv.org/abs/2504.05156](https://arxiv.org/abs/2504.05156)

Pham, V. K., Pham Thi, T. D., & Duong, N. T. (2024). A study on information search behaviour using AI-powered engines: Evidence from chatbots on online shopping platforms. *SAGE Open, 14*(4). [https://doi.org/10.1177/21582440241300007](https://doi.org/10.1177/21582440241300007)

Sun, X., Ma, R., Wei, S., Cesar, P., Bosch, J. A., & El Ali, A. (2025). Understanding trust toward human versus AI-generated health information through behavioural and physiological sensing. *International Journal of Human-Computer Studies*. Advance online publication. [https://arxiv.org/abs/2512.12348](https://arxiv.org/abs/2512.12348)

Sun, X., Ma, R., Zhao, X., Li, Z., Lindqvist, J., El Ali, A., & Bosch, J. A. (2024). Trusting the search: Unraveling human trust in health information from Google and ChatGPT. *arXiv preprint arXiv:2403.09987*. [https://doi.org/10.48550/arXiv.2403.09987](https://doi.org/10.48550/arXiv.2403.09987)

Yazan, M., Situmeang, F. B. I., & Verberne, S. (2025). Personality over precision: Exploring the influence of human-likeness on ChatGPT use for search. In *Proceedings of NIP@IR 2025*. [https://doi.org/10.48550/arXiv.2511.06447](https://doi.org/10.48550/arXiv.2511.06447)