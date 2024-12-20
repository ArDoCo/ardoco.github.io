---
layout: page
permalink: /c/icsa25
title: Enabling Architecture Traceability by LLM-based Architecture Component Name Extraction
description:
publication: fuchss_enabling_2025
---

by Dominik Fuchß <a href="https://orcid.org/0000-0001-6410-6769"><i class="fa-brands fa-orcid"></i></a>, Haoyu Liu <a href="https://orcid.org/0009-0002-7676-5010"><i class="fa-brands fa-orcid"></i></a>, Tobias Hey <a href="https://orcid.org/0000-0003-0381-1020"><i class="fa-brands fa-orcid"></i></a>, Jan Keim <a href="https://orcid.org/0000-0002-8899-7081"><i class="fa-brands fa-orcid"></i></a>, and Anne Koziolek <a href="https://orcid.org/0000-0002-1593-3394"><i class="fa-brands fa-orcid"></i></a>

To be published at the [22nd IEEE International Conference on Software Architecture (ICSA 2025), March 31 - April 04 2025](https://conf.researchr.org/home/icsa-2025/).

![Approach Overview](/assets/img/icsa25-approach.svg){:width="100%"}

## Abstract

Traceability Link Recovery (TLR) is an enabler for various software engineering tasks.
One important task is the recovery of trace links between Software Architecture Documentation (SAD) and source code.
Here, the main challenge is the semantic gap between the two artifact types.
Recent research has shown that this semantic gap can be bridged by using Software Architecture Models (SAMs) as intermediates.
However, the creation of SAMs is a manual and time-consuming task.
This paper investigates the use of Large Language Models (LLMs) to extract component names as simple SAMs for TLR based on SAD and source code.
By doing so, we aim to bridge the semantic gap between SAD and source code without the need for manual SAM creation.
We compare our approach to the state-of-the-art TLR approaches TransArC and ArDoCode.
TransArC is the currently best-performing approach for TLR between SAD and source code, but it requires SAMs as an additional artifact.
Our evaluation shows that our approach performs comparable to TransArC (weighted average F1 with GPT-4o: 0.86 vs. TransArC's 0.87), while only needing the SAD and source code.
Moreover, our approach significantly outperforms the best baseline that does not need SAMs (weighted average F1 with GPT-4o: 0.86 vs. ArDoCode's 0.62).
In summary, our approach shows that LLMs can be used to make TLR between SAD and source code more applicable by extracting component names and omitting the need for manually created SAMs.

## Links

- Paper on [KITopen](https://publikationen.bibliothek.kit.edu/1000177521)
- Replication Package on [Zenodo](https://doi.org/10.5281/zenodo.14506935) and the corresponding [GitHub repository](https://github.com/ArDoCo/ReplicationPackage-EnablingArchitectureTraceabilitybyLLM-basedArchitectureComponentNameExtraction)
