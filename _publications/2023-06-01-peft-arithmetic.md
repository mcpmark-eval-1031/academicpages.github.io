---
title: "Composing Parameter-Efficient Modules with Arithmetic Operations"
collection: publications
category: conferences
permalink: /publication/2023-06-01-peft-arithmetic
excerpt: 'We explore a simple yet effective paradigm for composing parameter-efficient fine-tuning (PEFT) modules (such as LoRA adapters) using arithmetic operations—addition, subtraction, and scaling—enabling flexible multi-task and multi-domain model composition without full retraining.'
date: 2023-06-01
venue: 'NeurIPS 2023'
paperurl: 'https://arxiv.org/abs/2306.14870'
citation: 'Jinghan Zhang, Shiqi Chen, Junteng Liu, Junxian He. (2023). &quot;Composing Parameter-Efficient Modules with Arithmetic Operations.&quot; <i>NeurIPS 2023</i>.'
---

This paper proposes a novel paradigm for **composing parameter-efficient fine-tuning (PEFT) modules** — such as LoRA adapters, (IA)³ vectors, and task arithmetic vectors — through simple arithmetic operations including addition, subtraction, and scaling in weight space.

**Key contributions:**
- Arithmetic composition (add/subtract/scale) of PEFT modules for flexible multi-task transfer
- Task vector arithmetic enables model merging without access to original training data
- Demonstrated on multi-task learning, domain adaptation, and style transfer scenarios
- Provides theoretical analysis of why arithmetic operations work for module composition
- Eliminates the need for joint retraining while achieving competitive performance

Published at **NeurIPS 2023**.

**Authors:** Jinghan Zhang, Shiqi Chen, Junteng Liu, Junxian He
