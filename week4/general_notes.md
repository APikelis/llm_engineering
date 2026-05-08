## Picking a Model

Start with: parameters, context length, pricing
Then look at results: Benchmarks, Leaderboards, Arenas

## The basics

* Open vs closed source
* Chat / Reasoning (perform better but slower and not so good at generating content) / Hybrid
* Release date and knowledge cut off
* Parameters
* Training Tokens
* Context Window

Costs (Can be checked on Leaderboards)
> API vs Runtime
> Training 
> Build (RAG, Monitoring, Product Related Costs)
> Time to Market
> Rate Limits
> Speed
> Latency (Mean time to the first token) - prominent for reasoning models and streaming responses
> Licence


Chinchilla Scaling Law: Training data should scale with number of parameters otherwise returns diminish.

## Benchmarks
1. Google Proof Q and A - 448 expert science questions. Non-PhD humans score 38%
2. MMLU-PRO - Language Understanding (Choice of 10 MCs)
3. AIME - Math problems
4. LiveCode Bench - Coding evaluation based on problems from LeetCode, AtCoder, and Codeforces competitions
5. MuSR - Reasoning: Logical deduction from murder mysteries etc
6. HLE - Super Human Intelligence: 2,500 of the toughest questions designed to be the last exam for AI

Limitations of Benchmarks:
> Training Data Contamination - hard to keep benchmarks secret so future models have parts of test in their training data
> Not consistently applied - different hardware, gpus used etc
> Benchmarks are too narrow in scope i.e., GPQA = Science
> Nuanced reasoning is hard to measure
> Saturation - Models have gotten better so benchmarks become redundant
> Overfitting model to the benchmark
> Frontier models may be aware that they are being evaluated. Model might change behaviour when not being evaluated.

**Check out Ed Donners AI Connect 4 benchmark**

## Leaderboards
1. Artificial Analysis
2. Vellum
3. Scale.com
4. HuggingFace
5. LiveBench

## Commercial Use Cases

Automate -> Augment -> Differentiate

> GPT Wrappers - Apps integrate LLMs in their product i.e., DuoLingo, Copilots
> Bespoke AI Platform - Specialised AI with domain expertise (RAG, Tools, Inference Time Techniques, Propriatary Data ) i.., Palantir, Salesforce Health, Harvey (LLM for Law)
> Agentic AI - More prominent in Technical Domains like Software Engineering

5 steps: Understand Business Problem, Prepare (select candidate models), Model Selection (prototyping), Customise (build), Productionise

## Technical Metrics vs Business Outcomes

### Technical - best for optimising
> Loss - Cross Entropy Loss
> Perplexity
> Accuracy
> Precision, Recall, F1
> AUC-ROC

### Business Outcomes
> KPIs tied to Biz Outcomes (Satisfaction/NPS, revenue)
> Time and cost reduction
> Benchmark comparisons
