---
layout: post
title: "Just Checking: Information Seeking and Trust in the Age of Generative AI"
date: 2025-12-29
description: "A review of recent research on how generative AI is reshaping information seeking behaviour, trust dynamics and verification strategies."
publication_type: scholarly-article
tags: [generative-ai, information-seeking, trust, verification, research]
categories: [AI, Information Management]
author: ["Lewis Dryburgh"]
permalink: /2025-12-29-just-checking
---

Eight years ago I completed a master's in Information Management, studying how people capture and share knowledge in digital environments. For my dissertation, I interviewed and shadowed startup founders to understand their information behaviours. I wrote it up as ['Do you even document bro?'](https://lewisdryburgh.com/2017-11-30-do-you-even-document) which I was lucky enough to present a few times. After that, I lectured for a couple of terms at the University of Technology Sydney before kids, covid and life intervened. I haven't meaningfully engaged in any study or research since then.

But I'm on my summer holidays and my kids are (slightly) more self sufficient. I've been working through a pile of recent papers to understand how generative AI is changing information seeking. In 2017, the problem on my mind was getting people to externalise knowledge in a way it could be easily retrieved. Now information is being generated faster than anyone can verify it, by systems that feel authoritative but may not be. I thought I'd attempt a desktop literature review of what's happening in the research, as a way of flexing some old muscles and attempting to stay current.

<img src="{{ '/assets/images/tatsuo.jpeg' | relative_url }}" alt="Tatsuo Miyajima, Connecting with Everything, 2017" style="width: 85%; display: block; margin: 0 auto;"> 
<p style="text-align: center;"><em>Tatsuo Miyajima, Connecting with Everything, 2017</em></p>

Like many people, I'm sure we're in an *AI bubble*. Companies are laying off staff with pomp and press releases to replace them with bots, then [quietly hiring the humans back](https://www.theinformation.com/articles/story-salesforces-declining-trust-llms-hit-nerve). Tech giants are capitalising on AI infrastructure then sheepishly [dropping sales targets for products people aren't buying](https://arstechnica.com/ai/2025/12/microsoft-slashes-ai-sales-growth-targets-as-customers-resist-unproven-agents/). That said, I feel that the use of generative AI for search and retrieval is impactful and likely here to stay.

To find out what's happening, I searched for open-access empirical research published since 2023: research that measured what people do with generative AI tools. That gave me roughly a dozen studies spanning experiments, surveys, physiological measurements and observation.

I think we're in the middle of a serious shift and we're not handling it well.

What I've found is that we're trusting AI systems in ways that don't match their actual reliability. We trust citations that don't exist, we trust conversational interfaces more than accurate ones, and we trust unlabelled AI content more than the same content when we know it came from AI. The research shows our traditional credibility markers (citations, confident tone, apparent understanding) are failing us because they've been decoupled from actual human judgment and comprehension. Different user groups face different vulnerabilities: some trust too much without enough experience to calibrate that trust, while frequent users anthropomorphise systems in ways that blur appropriate boundaries. I'll argue that while individual verification strategies matter, the problem is fundamentally systemic. It requires rethinking interface design, updating our verification practices for AI-mediated information environments, and establishing governance frameworks that address the equity implications of differential AI performance across languages and contexts.

### Jump to

- [We're Not Searching Anymore, We're Conversing](#were-not-searching-anymore-were-conversing)
- [Why We Trust (and Maybe Shouldn't)](#why-we-trust-and-maybe-shouldnt)
  - [The Citation Problem](#the-citation-problem)
  - [When AI Feels Human](#when-ai-feels-human)
  - [What Happens When We Know It's AI](#what-happens-when-we-know-its-ai)
  - [Trust at the Physiological Level](#trust-at-the-physiological-level)
- [The Problem With Saying 'I Don't Know'](#the-problem-with-saying-i-dont-know)
- [Who Gets It Wrong (and Who Pays the Price)](#who-gets-it-wrong-and-who-pays-the-price)
- [The Systemic Stakes: Verification at Scale](#the-systemic-stakes-verification-at-scale)
- [The Psychological Dimension](#the-psychological-dimension)
- [What the Research Tells Us (So Far)](#what-the-research-tells-us-so-far)
- [The Verification Crisis](#the-verification-crisis)
- [What Should Happen Next](#what-should-happen-next)
  - [For Designers: Navigating Impossible Trade-offs](#for-designers-navigating-impossible-trade-offs)
  - [For Users: New Verification Strategies That Actually Work](#for-users-new-verification-strategies-that-actually-work)
  - [For Institutions: Governance That Addresses Differential Harm](#for-institutions-governance-that-addresses-differential-harm)
- [Bringing It Back](#bringing-it-back)

### We're Not Searching Anymore, We're Conversing
Search behaviour is changing. Mayerhofer et al. (2025) describe what they call 'blending' behaviour: users don't just search anymore, they toggle between traditional search engines and conversational AI, often using one to verify the other. Their research shows people asking Google to fact-check ChatGPT or using ChatGPT to synthesise results from a Google search. It's a hybrid approach that suggests we haven't quite figured out which tool to trust for what.

This change is about more than just switching tools. Pham et al. (2024) found that in e-commerce contexts, people use longer and more conversational queries when interacting with AI chatbots compared to traditional search. Instead of typing 'wireless headphones under $100', users are more likely to ask 'what are some good quality wireless headphones I can get for under $100?'. The interaction mirrors how you'd ask a shop assistant, rather than query a database.

This conversational style matters because it changes what we're doing cognitively. Traditional search required what researchers call 'berrypicking' (Bates, 1989): you'd try different search terms, scan results, refine your query and gradually home in on what you needed. It was iterative and required you to stay critically engaged with whether you were finding good information. Conversation, by contrast, feels more passive. You ask, the AI answers. The loop closes.

We're dealing with what philosopher Luciano Floridi (2024) calls a fundamental 'decoupling' between agency and intelligence. Gen AI systems act as autonomous agents. They can perform complex tasks, generate responses and cite sources, but they have no understanding of what they're doing. For us as information seekers, this means we can't rely on the usual signals. A citation doesn't mean someone read and understood a source. A confident tone doesn't mean comprehension. We're interacting with something that *acts* intelligent without *being* intelligent, Our credibility senses weren't built for that.

The blending behaviours documented by Mayerhofer et al. (2025) are an adaptive response to an environment where the traditional markers of human intent and accountability have been severed. We're trying to restore verification processes by cross-referencing AI with traditional search, but even that strategy has limits when both increasingly draw from overlapping, AI-mediated sources.

### Why We Trust (and Maybe Shouldn't)
This brings us to the question of trust. If we're treating AI systems more like conversational partners than search tools, are we applying the same critical scrutiny?

#### The Citation Problem

Li and Aral (2025) found that when AI-generated content includes citations and reference links, people trust it more, even when those citations are incorrect or completely fabricated. The formal markers of credibility (footnotes, links, an academic appearance) override our instinct to verify the actual content.

This is another instance of Floridi's decoupling. In traditional information environments, citations indicated that someone, a person with agency *and* intelligence, had consulted and evaluated those sources. That signal carried meaning. Now we have systems that can generate citation-like elements without any underlying consultation or understanding. The rule of thumb that worked before (citations = credible) fails because the relationship between form and function has broken down.

#### When AI Feels Human

This vulnerability is compounded by anthropomorphism. When AI systems feel more human-like, whether through conversational tone or interface design, we trust them more (Yazan et al., 2025; Huschens et al., 2023). We're also more willing to trade accuracy for personalisation and conversational flow. If the AI sounds friendly and seems to understand us, we tend to forgive it for being wrong.

This creates a genuine design tension: creating engaging, natural interactions makes systems feel more trustworthy, but that trust may not be justified. We're extending social trust: rapport, conversational flow, apparent understanding, to non-social entities.

#### What Happens When We Know It's AI

Sun et al. (2024, 2025) explored this dynamic in health information seeking, a domain where being wrong has real consequences. Their research revealed a mismatch: when people don't know the source of health information, they trust AI-generated content more than human-generated content. But when information is explicitly labelled as coming from AI, people trust it less than human-attributed content.

This suggests that transparency matters enormously. We adjust our trust based on what we think we're dealing with, but we're not very good at identifying AI content in the wild. Unlabelled AI content may be trusted more than it should be, while honest labelling reduces trust even in accurate information.

#### Trust at the Physiological Level

Sun et al. (2025) used eye-tracking, ECG, skin conductance and temperature sensors to measure physiological responses to health information. Machine learning models trained on these signals could predict whether someone trusted the information with 73% accuracy. They also found these responses could identify whether someone identified the content as AI or human-generated with 65% accuracy.

These numbers are specific to their lab setting and need validation in real-world contexts, but they point to something important: our bodies respond to credibility cues before our conscious minds catch up. Trust operates at multiple levels simultaneously, beyond just cognition. Interface design, credibility rules we've carried over from other contexts and unconscious physiological responses are all shaping whether we believe what we're reading.

### The Problem With Saying 'I Don't Know'

One design solution you might think would help is having AI systems signal uncertainty. If the model's not confident, it should say so.

Li and Aral (2025) found that signalling uncertainty reduces trust and may discourage users from relying on correct information. The effect appears context-dependent, but honesty ("I'm not sure about this") conflicts with user expectations for responsive, confident assistance.

Huang et al. (2025) propose a more sophisticated approach called *'confidence-based response abstinence'*, where AI systems decline to answer when uncertainty is high. But this requires accurate self-assessment from the model, which is not guaranteed. It also risks frustrating users who expect an answer.

This creates a genuine design dilemma. Systems that admit uncertainty are more responsible but less trusted. Systems that project confidence are more persuasive but potentially misleading. There's no obvious way to square this circle and it's a direct consequence of the decoupling between agency and intelligence. We want systems that *act* like knowledgeable advisors but can't ground their responses in genuine understanding.

### Who Gets It Wrong (and Who Pays the Price)

Trust dynamics also vary across different user groups. These patterns matter because they suggest different populations face different vulnerabilities.

Yazan et al. (2025) found that middle-aged adults show a potentially vulnerable pattern: they express higher trust in ChatGPT but use it less frequently than younger users. This means they have less opportunity to develop calibrated expectations through experience. They're trusting, but not practised.

Meanwhile, users who employ both ChatGPT and traditional search daily show higher trust and greater anthropomorphisation of AI systems. It's unclear whether frequent use causes this, or whether people who are already predisposed to trust AI use it more often.

These patterns matter because they suggest different user groups need different kinds of support. Designing one-size-fits-all AI interfaces assumes everyone brings the same scepticism and verification habits to the table. The research suggests they don't. Some groups are trusting without sufficient experience to calibrate that trust. Others are acclimated to anthropomorphic interactions that may blur appropriate boundaries.

### The Systemic Stakes: Verification at Scale

Beyond individual trust calibration, there are broader concerns about AI as an information intermediary. When generative AI sits between us and information sources, it shapes what we're exposed to and potentially amplifies or mitigates misinformation (Hirvonen et al., 2024; Jarrahi et al., 2025).

Kuznetsova et al. (2025) tested this directly by asking LLM-based chatbots to verify political statements. ChatGPT correctly evaluated approximately 72% of tested claims on their dataset, with substantial variability across languages and topics. High-resource languages like English performed better than low-resource languages, raising equity concerns.

If AI systems are going to serve as fact-checkers or information gatekeepers, differential performance across linguistic communities means some populations face higher misinformation vulnerability than others. The populations already disadvantaged by language and resource constraints face systematically worse AI performance, compounding existing information inequalities.

This challenge is further amplified by training data overlap. When multiple AI systems draw from overlapping datasets, the traditional verification strategy of cross-referencing multiple sources becomes less effective. If all the sources consulted the same underlying information (or misinformation), checking three AI-generated answers won't help you triangulate truth. The appearance of independent verification masks shared foundational errors.

### What the Research Tells Us (So Far)

I summarised the key research and findings along with their main limitations. Most of this research is less than a year old, much of it is still in preprint and the methods vary significantly. This is emerging evidence, but the field is moving quickly.

| Study | Study Type | What They Looked At | Main Finding | Important Caveats |
|-------|------------|---------------------|--------------|-------------------|
| Mayerhofer et al., 2025 | Observational | How people use search vs chat | Users blend both and toggle between them for verification | Preprint; limited platform diversity; self-reported behaviour |
| Pham et al., 2024 | Experimental | E-commerce search behaviour | Longer, conversational queries with chatbots | Domain-specific to shopping; controlled setting |
| Li & Aral, 2025 | Experiment | Trust in AI search results | Citations increase trust even when incorrect | Preprint; experimental setting; needs replication |
| Sun et al., 2024/2025 | Physiological/Survey | Health information trust | AI content trusted more when source is unknown; labelling matters | Lab-based measures; 2025 paper is advance copy; specific to health domain |
| Kuznetsova et al., 2025 | Evaluation study | Political fact-checking by chatbots | ~72% accuracy; varies by language and topic | Performance sensitive to task framing; limited to political claims |
| Huang et al., 2025 | Conceptual/Design | Managing AI uncertainty | Proposes systems should refuse to answer when uncertain | Requires robust uncertainty estimates; theoretical proposal |
| Yazan et al., 2025 | Survey | Trust patterns across user groups | Middle-aged users trust more but use less; frequent users anthropomorphise more | Correlation not causation; self-reported trust measures |

### The Verification Crisis

Across all these studies, there's a consistent pattern: our credibility judgements are shaped as much by interface signals and situational context as by informational accuracy. We trust citations even when they're wrong. We trust friendly-sounding AI more than cold search results. We trust unlabelled AI content more than labelled AI content. We verify less when we're anxious or when the conversational flow feels natural.

These are predictable vulnerabilities arising from the interaction between human psychology and AI interface design. Traditional credibility markers fail in generative AI contexts

Floridi's framework helps explain why: we're dealing with agents that perform informational tasks without semantic grasp. The 'semantic capital' of the information ecosystem is at risk. As the infosphere fills with persuasive but non-intelligent agents, the burden of sense-making shifts entirely to us. But we're not equipped with the cognitive tools or interface affordances to carry that burden effectively.

### What Should Happen Next

The research points to practical directions, though they're easier to identify than to implement. The challenges span interface design, user capacity and systemic governance.

#### For Designers: Navigating Impossible Trade-offs

We need better ways to show people where information is coming from and how confident the AI actually is about its answer. But as the research showed, signalling uncertainty makes people trust the system less, even when it's being more honest. *How do you design interfaces that communicate "I'm not totally sure about this" without undermining the entire interaction?*

One possibility is contextual calibration: perhaps uncertainty signals should be presented differently depending on domain risk (health vs. entertainment), user experience level, or query type. But this requires sophisticated user modelling and risks creating inconsistent experiences that confuse rather than clarify.

Citation practices present another design challenge. If users trust citations without verifying them, systems must either ensure all citations are genuine and relevant or avoid citation-like elements entirely. The current middle ground: where systems can generate plausible but fabricated references is the worst possible outcome. But guaranteeing citation accuracy is technically demanding. Removing citations might reduce the perceived credibility of accurate information.

The anthropomorphism dilemma is perhaps the trickiest. Conversational, human-like interfaces increase engagement and user satisfaction but also increase misplaced trust. Do we design systems to feel less human-like, knowing this will reduce usability? Or do we accept the trust inflation as a cost of good user experience? There's no neutral ground. Every design choice has impacts.

#### For Users: New Verification Strategies That Actually Work

Traditional information literacy emphasises source evaluation and cross-referencing multiple independent sources. These strategies need adaptation for AI-mediated information environments.

Users need frameworks for:
- **Recognising AI-generated content even when unlabelled.** This requires understanding stylistic tells, inconsistency patterns and checking for telltale signs like plausible but non-existent citations.
- **Verifying citations provided by AI systems.** Don't trust that a citation exists or says what the AI claims it says. When stakes are high, check the source directly.
- **Understanding the limitations of cross-referencing.** When multiple AI systems draw from similar training data, apparent consensus may reflect shared errors rather than independent confirmation.
- **Maintaining critical distance despite conversational design.** Actively remind yourself that conversational flow doesn't imply understanding, and that a friendly tone isn't a proxy for accuracy.

Educational interventions should address not only technical understanding of AI systems but also awareness of how conversational design influences trust. We need training that makes the invisible visible: helping people recognise when they're being swayed by interface features rather than information quality.

But individual verification strategies only scale so far. Not everyone has the time, skills or motivation to fact-check AI responses rigorously. Placing the entire burden on users is neither realistic nor equitable.

#### For Institutions: Governance That Addresses Differential Harm

At a systemic level, if AI systems increasingly mediate access to information, performance disparities across languages, topics and cultural contexts create equity concerns that can't be solved by better design or user education alone.

Governance frameworks need to address:

**Transparency and Attribution Standards:** Regulatory requirements for labelling AI-generated content and disclosing training data sources. This enables informed trust calibration but requires enforcement mechanisms and international coordination.

**Performance Requirements Across Contexts:** Kuznetsova et al. (2025) showed that AI performance varies massively by language and topic. Any governance system needs to account for that, or we're building infrastructure that works well for English-speakers asking about Western political contexts while everyone else gets left with worse information. This means setting performance thresholds that account for linguistic and cultural equity, not just aggregate accuracy.

**Audit and Accountability Mechanisms:** When AI systems provide misinformation, who is accountable? Current liability frameworks weren't designed for systems that generate novel content without explicit programming. We need mechanisms for identifying harm, attributing responsibility and providing remedy.

**Citation and Credibility Policies:** Industry standards or regulatory requirements regarding citation practices. If systems provide citations, those must be verifiable. If systems can't reliably provide accurate citations, perhaps they shouldn't provide them at all.

The methodological challenges are significant too. Most research reviewed here is either experimental (artificial lab settings) or survey-based (what people say they do, not what they actually do). We need longitudinal studies that follow people over time, cross-cultural work that doesn't assume everyone behaves like Western educated populations, and studies that actually measure verification behaviour in natural contexts.

### Bringing It Back

When I was researching startup founders eight years ago, the challenge was getting people to document what they knew. Knowledge management felt like a problem of capture and retrieval: making tacit knowledge explicit, building systems where people could find what others had learned. The cognitive work was in *getting* information into systems where it could be found.

Now we're drowning in confident-sounding information from systems that don't know anything. The research suggests we haven't figured out how to navigate this environment yet. We're trusting the wrong signals: citations that mean nothing, conversational warmth that implies understanding that isn't there, formal presentation that masks fabrication. We're verifying less than we should, doing so unevenly across different populations. We face systemic vulnerabilities that individual scepticism can't fully address. The cognitive work has flipped: instead of focusing on capture, we now need to verify and sense-make in an environment where information is abundant but accountability is absent.

The practical work ahead isn't mysterious. We need:
- better interface design that balances honesty with usability
- smarter literacy programs that teach verification strategies for AI-mediated information
- governance frameworks that address transparency and differential harm

My information management training emphasised context, provenance and the socio-technical systems that shape how knowledge flows through organisations. Those frameworks feel newly relevant. Understanding where information comes from, who generated it and for what purpose are of critical importance.

We're entering a context where information can be generated by agents that act without understanding, where credibility markers can be fabricated, where verification strategies that worked for human-generated content fail systematically. 

We are probably in a bubble. Companies will continue quietly walking back their AI promises. But whether the bubble bursts or not or not, a change in how we seek and trust information is here to stay.


---

**AI assistance disclosure**: While the analysis and perspectives here are mine, I did use some generative AI tools. I used Google's Notebook LM to help with coding some of the papers I'd collated. I used Anthropic's Claude Opus 4.5 to fact check my interpretations and format the references. All the sources below are real, non-hallucinated, open-access* research papers. 

(* With the exception of Bates' berrypicking, which is a classic.)

---


### References
Bates, M. J. (1989). The design of browsing and berrypicking techniques for the online search interface. *Online Review, 13*(5), 407–424. [https://doi.org/10.1108/eb024320](https://doi.org/10.1108/eb024320)

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