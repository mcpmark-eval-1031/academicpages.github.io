---
title: "In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation"
collection: publications
category: conferences
permalink: /publication/2024-03-01-incontext-sharpness
excerpt: 'We introduce In-Context Sharpness (ICS), a novel metric derived from the internal representations of LLMs that serves as an effective alert signal for detecting and mitigating hallucinations. ICS measures the sharpness of token prediction distributions in context, providing a lightweight and model-agnostic hallucination indicator.'
date: 2024-03-01
venue: 'ICML 2024'
paperurl: 'https://arxiv.org/abs/2403.01548'
citation: 'Shiqi Chen, Miao Xiong, Junteng Liu, Zhengxuan Wu, Teng Xiao, Siyang Gao, Junxian He. (2024). &quot;In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation.&quot; <i>Proceedings of ICML 2024</i>.'
---

This paper introduces **In-Context Sharpness (ICS)**, a novel inner-representation-based signal for detecting and mitigating hallucinations in large language models. ICS measures the sharpness (peakedness) of token prediction distributions conditioned on context, serving as a lightweight alert when the model is about to generate uncertain or potentially hallucinated content.

**Key contributions:**
- Novel ICS metric derived from LLM internal representations without external retrieval
- ICS provides effective alerts that correlate with hallucination occurrence
- Plug-and-play integration into decoding strategies to reduce hallucination rates
- Extensive evaluation on knowledge-intensive QA and open-domain generation tasks

Published at **ICML 2024**.

**Authors:** Shiqi Chen, Miao Xiong, Junteng Liu, Zhengxuan Wu, Teng Xiao, Siyang Gao, Junxian He
