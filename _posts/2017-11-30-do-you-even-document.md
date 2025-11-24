---
layout: post
title: "Do You Even Document, Bro?"
date: 2017-09-05
---


## Do you even document, bro? Data and information management in early-stage technology start-ups.

This paper is based on research originally conducted in partial fulfilment of the requirements for the Master of Science degree in Information Management at The Robert Gordon University, completed in May 2017 under the supervision of Dr Graeme Baxter. The original dissertation has been adapted while maintaining the integrity of the research findings and methodology.

If for any reason you'd like to read my original dissertation, please get in touch.


## Abstract

This paper investigates how early-stage technology start-ups manage internal business data and information. Semi-structured interviews were conducted with five founders across four Sydney-based start-ups, complemented by observation of routine information retrieval. Guided by grounded theory analysis, three characteristics of start-up information management were identified: use of consumer-level cloud SaaS, informal and culturally mediated governance and a strong orientation toward collaborative knowledge capture. Two novel practices emerged: extensive wiki-based documentation and automated enforcement of code conventions through linters. These practices appear to enable functional governance in resource-constrained environments, though questions remain about scalability, fragmentation and long-term retention. Implications for practice and future research directions are provided.

**Keywords:** information management; ; data management; start-ups; information governance; knowledge sharing; cloud collaboration

---

## 1. Introduction

Information is a core organisational resource, shaping performance and capabilities (Smallwood 2014). Research on information governance, knowledge management and organisational learning has largely centred on established firms with formal structures. In contrast, start-ups operate under constraints of speed, uncertainty and scarcity, typically lacking procedural maturity. Understanding how start-ups manage business-critical data and information is therefore an unresolved problem.

This exploratory study examines the internal data and information practices of four Australian technology start-ups. The concept of business information refers to internal documentation, organisational knowledge and operational records, distinct from customer-facing product or service data. The study asks two core questions:

- How do technology start-ups create, store, retrieve and dispose of internal business information?
- Which practices or structures, if any, represent innovative approaches to information governance?

---

## 2. Literature Review

### 2.1 Defining Start-ups

Definitions of "start-up" are plural and contested. Zaech and Baldegger (2017) note the absence of any consensus definition. This study adopts a pragmatic approach aligned with Ries (2011), defining the start-up as a human institution oriented toward creation of new products or services under high uncertainty. Operational criteria supplement this definition: self-identification as a start-up, organisational age below five years, staff count below ten and pursuit of scalable software products.

### 2.2 Information Management in Small Organisations

Research addressing internal information management in very small or early-stage firms is limited. Related scholarship emphasises knowledge acquisition (Sullivan and Marvel 2011), absorptive capacity (Debrulle et al. 2014) and technology adoption (Mladenow et al. 2012), but rarely examines the internal practices by which business information is stored, retrieved and governed. Centobelli et al. (2017) conclude that knowledge management literature in start-ups remains fragmented and under-theorised.

### 2.3 Methodological Precedent

Qualitative approaches are central to examining information practices. Grounded theory has been used to investigate information architectures (Burford 2014) and organisational information systems (Urquhart et al. 2010; Mattarelli et al. 2013). Its bottom-up analytic logic is suited to emergent socio-technical phenomena where formal structures are absent or immature.

---

## 3. Methodology

### 3.1 Research Design

A qualitative research design was used, consisting of semi-structured interviews and in-situ observation. Grounded theory principles (Strauss and Corbin 1994) guided coding and theme development. The study privileged the participants' descriptions of their lived information practices rather than evaluating them against normative frameworks.

### 3.2 Participants and Sampling

Purposive sampling identified four Sydney-based start-ups whose core products involve information-intensive services. All organisations met the operational criteria and self-identified as start-ups. Five founders participated in total.

Pseudonyms based on chemical elements were used to protect confidentiality; individuals were named after associated discoverers.

**Table 1. Participating organisations**

| Organisation | Product Type | Employees |
|--------------|--------------|-----------|
| Sodium | Recruitment platform | 6 (mostly part-time) |
| Lithium | Asset management software | 3 |
| Caesium | Business intelligence software | 3 |
| Rubidium | Real-time transport software | 3 |

### 3.3 Data Collection

Semi-structured interviews (45–75 minutes) followed a simplified information lifecycle model: creation, storage, retrieval and destruction. Interviews were audio-recorded and transcribed verbatim. Observation tasks involved participants demonstrating how they locate specific information within existing systems.

### 3.4 Data Analysis

Two-stage coding was applied:

- **Open coding:** descriptive and concept-level codes per transcript
- **Focused coding:** aggregation into cross-case thematic categories aligned with the research questions

Data were iteratively compared, refined and re-coded following grounded theory practice.

### 3.5 Ethics

Ethical approval was obtained from the host institution. Participation was voluntary and confidential and observation components were optional. No commercially sensitive or proprietary data were requested or retained.

---

## 4. Results

The findings reveal six core themes that jointly characterise information management in the participating organisations.

### 4.1 Cloud-first, fully digital information environments

All firms operated exclusively with digital information. No physical files or paper systems were reported. Participants associated the digital-first stance with mobility, searchability and multi-user access.

> "We never use paper. If something isn't online, it doesn't exist." (Carl, Caesium)

Cloud-based tools formed the backbone of organisational information systems. Storage and communication relied on consumer SaaS: Google Drive, Dropbox, Slack, Facebook Messenger, Xero, InVision and Confluence.

A consequence of this digital-first ecology was the normalised assumption that every artefact should be stored centrally and remain accessible to the whole team.

> "We don't really think about where things go, we just put it in Drive and people can get it." (Alex, Sodium)

### 4.2 Chat-centric communication instead of email

All organisations expressed a preference for persistent chat systems. Email was reserved for external-facing communication or formal interactions. Slack and Messenger played dual roles as communication channels and ad hoc knowledge repositories.

> "Email just slows things down. If we're trying to get something done, it's Slack." (Max, Rubidium)

One participant described Slack history as "half our documentation," reflecting the porous boundary between synchronous interaction and knowledge capture.

### 4.3 Informal governance anchored in cultural norms

No organisation had a formal information policy or documented governance framework. Governance practices were implicitly embedded through shared expectations, workplace trust and founder preferences.

> "We just assume people will be sensible. If something is important, you'll put it somewhere where others can find it." (Pierre, Lithium)

Despite the informal nature of governance, no participant reported incidents of permanent data loss. Participants framed governance as a cultural matter, not a procedural one.

### 4.4 Search-first retrieval with ad hoc taxonomies

Search constituted the default retrieval strategy. Participants seldom navigated folder hierarchies; they issued keywords to system-level search boxes. When search failed, they asked colleagues.

> "The challenge is if you don't know it exists you can't search for it." (Carl, Caesium)

Folder hierarchies existed but functioned as subjective taxonomies under the control of whoever created them. Naming conventions varied by individual or team and were rarely documented.

### 4.5 Retention by default and minimal deletion

Deletion was infrequent and often avoided. Storage was viewed as inexpensive and future value unpredictable.

> "Why delete something? Storage is cheap and you never know when you'll need it." (Alex, Sodium)

The exception was Rubidium, which deliberately deleted user analytics after thirty days to prioritise privacy and reject monetisation strategies incompatible with organisational values.

### 4.6 Novel governance practices: Wiki-based knowledge capture and automated linters

Two distinctive practices emerged.

**Comprehensive wiki.** Rubidium maintained a Confluence wiki containing technical notes, deployment procedures, design decisions and incidental knowledge. Contribution was actively encouraged.

> "The smallest bit of info might save someone hours later — put it in the wiki." (Max, Rubidium)

**Automated linters.** One organisation enforced more than 200 coding standards through a linter that blocked non-compliant commits. This embedded organisational rules into development workflows.

> "If the code doesn't pass the linter, it doesn't get committed. That's the rule." (Pierre, Lithium)

These mechanisms served as tool-based governance, bypassing formal policy artefacts.

**Table 2. Themes, empirical indicators and illustrative quotations**

| Theme | Empirical indicators | Illustrative quotations |
|-------|---------------------|------------------------|
| Digital-only ecosystem | No paper files; SaaS platforms (Drive, Dropbox, Confluence) | "If something isn't online, it doesn't exist." (Caesium) |
| Chat over email | Slack or Messenger as primary workspace | "Email just slows things down." (Rubidium) |
| Informal governance | Norm-based expectations; trust | "We just assume people will be sensible." (Lithium) |
| Search-based retrieval | Keyword-first; fallback to colleagues | "If you don't know it exists you can't search for it." (Caesium) |
| Retention culture | Avoiding deletion; cheap storage | "Why delete something? Storage is cheap." (Sodium) |
| Tool-enabled governance | Confluence wiki; linter enforcing rules | "If the code doesn't pass the linter, it doesn't get committed." (Lithium) |

---

## 5. Discussion

Start-ups in this study display a consistent pattern of cloud-first, tool-mediated information management. Rather than documenting governance, they rely on tacit conventions and embedding of rules into digital tools. These practices enable coordination with minimal overhead and reduce cognitive burden in contexts of limited time and staffing.

The strong cultural emphasis on openness and shared access aligns with literature on entrepreneurial collaboration. However, search fragmentation, reliance on individual taxonomies and undocumented conventions may hinder scaling, onboarding and auditability.

Automated code governance and wiki-led incidental knowledge capture represent defensible innovations. They point toward a broader concept of governance by automation, where tools perform regulatory functions typically reserved for policy and compliance documents.

---

## 6. Limitations and Future Research

The study involves a small, geographically localised sample of male founders and may not generalise to other cultural or organisational contexts. Future work should:

- Track longitudinal change as start-ups grow and formalise structures
- Include non-founder employees and cross-functional roles
- Investigate automation in information governance at scale
- Examine how retention cultures adapt to regulatory or investor pressure

---

## 7. Conclusion

Technology start-ups manage business information using lightweight, tool-centric systems that prioritise collaboration, speed and accessibility. Formal governance frameworks are substituted by norms and automation. Cloud services, searchable communication platforms and wikis provide sufficient operational capability for small teams, though scalability risks remain. Understanding these practices expands knowledge of information management in emerging organisations and suggests new research trajectories for governance automation and digital-first knowledge capture.

---

## References

Burford, S. (2014). A grounded theory of the practice of web information architecture in large organizations. *Journal of the Association for Information Science and Technology*, 65(10), 2017–2034.

Centobelli, P., Cerchione, R., and Esposito, E. (2017). Knowledge management in startups: systematic literature review and future research agenda. *Sustainability*, 9(3), 361.

Cooper, A. C., Gimeno-Gascon, F. J., and Woo, C. Y. (1994). Initial human and financial capital as predictors of new venture performance. *Journal of Business Venturing*, 9(5), 371–395.

Debrulle, J., Maes, J., and Sels, L. (2014). Start-up absorptive capacity: Does the owner's human and social capital matter? *International Small Business Journal*, 32(7), 777–801.

Mattarelli, E., Bertolotti, F., and Macrì, D. M. (2013). The use of ethnography and grounded theory in the development of a management information system. *European Journal of Information Systems*, 22(1), 26–44.

Mladenow, A., Bauer, C., Strauss, C., and Decker, H. (2012). Value creation using clouds: Analysis of value drivers for start-ups and SMEs in the textile industry. *Advanced Information Networking and Applications Workshops (WAINA)*, 1215–1220.

Ries, E. (2011). *The Lean Startup: How today's entrepreneurs use continuous innovation to create radically successful businesses*. Crown Business.

Smallwood, R. F. (2014). *Information Governance: Concepts, Strategies, and Best Practices*. John Wiley & Sons.

Strauss, A. and Corbin, J. (1994). Grounded theory methodology. In *Handbook of Qualitative Research*, 17, 273–285.

Sullivan, D. M. and Marvel, M. R. (2011). Knowledge acquisition, network reliance, and early-stage technology venture outcomes. *Journal of Management Studies*, 48(6), 1169–1193.

Urquhart, C., Lehmann, H., and Myers, M. D. (2010). Putting the theory back into grounded theory: Guidelines for grounded theory studies in information systems. *Information Systems Journal*, 20(4), 357–381.

Zaech, S. and Baldegger, U. (2017). Leadership in start-ups. *International Small Business Journal*, 35(2), 157–177.