# gricean-sincerity-llm-evaluation
Evaluating apology sincerity in LLM outputs using Gricean maxims — a computational pragmatics framework with human vs. LLM annotation comparison. Presented at LSA 2026.
# Gricean Sincerity and Computational Cues
### Diagnosing Genuine Apologies through Pragmatic Maxims on WhatsApp

Presented at the **LSA Annual Meeting 2026**, New Orleans.

## Overview
This project introduces a transparent, feature-based computational model 
for evaluating apology sincerity in LLM-generated outputs. It compares 
human and LLM sincerity judgments using Gricean maxims (Quality & Relation) 
as the theoretical foundation.

## Key Finding
LLMs consistently assign lower sincerity scores than human annotators 
and never overestimate sincerity — suggesting a conservative pragmatic 
bias, particularly around responsibility acceptance and corrective intent.

## Research Questions
- Can chatbot-generated apologies be evaluated for sincerity using a 
  computational scoring model?
- Do violations of Gricean Maxims correlate with lower perceived sincerity?
- Which linguistic cues most accurately predict sincerity across human 
  and algorithmic evaluations?

## Methodology
- Stage 1: Published apology corpus compiled from customer service data
- Stage 2: Chatbot response corpus (WhatsApp-style interactions)
- Binary feature scoring schema (A–E)
- Human annotation vs. LLM evaluation comparison
- Dataset: 50 items

## Results
| Metric | Score |
|--------|-------|
| Exact match | 4 (8%) |
| LLM lower than human | 46 (92%) |
| MAE | 1.54 |
| Pearson r | 0.35 |

## Repository Contents
- `/poster` — LSA 2026 conference poster
- `/data` — Sample annotations
- `/annotation` — Scoring schema and guidelines

## Author
**Mushaal AlBugami**
GitHub: [@malbugami](https://github.com/malbugami)
PhD Student, Department of Modern Languages, University of Mississippi

## References
Bach & Harnish (1979); Grice (1975); Ju
