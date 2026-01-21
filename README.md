# EconoLLM-Tracer: Affordable LLM Fine-Tuning for Enterprise Traceability Data

## Project Overview
##### EconoLLM-Tracer demonstrates how enterprises can leverage affordable consumer-grade GPUs to fine-tune Large Language Models (LLMs) for specialized business applications. This project focuses on extracting structured traceability data from unstructured text – a common requirement in subscription analytics, supply chain tracking, and compliance reporting.

---

## Key Innovation
##### Traditionally, enterprise-grade AI required expensive infrastructure ($20,000+ GPUs) and specialized expertise. This project proves that:

- Consumer GPUs (RTX 3060/4060, ~$300-500) are sufficient for many enterprise LLM applications

- 4-bit quantization (via Unsloth) reduces memory requirements by 75%

- LoRA fine-tuning trains only 0.1% of model parameters, slashing training time and cost

- Ollama deployment enables local, secure, and cost-free inference

---
> [!IMPORTANT]
>
> ### <ins>Technical Achievement </ins>
>
> Fine-tuned TinyLlama (1.1B parameters) to extract structured JSON from subscription traceability data with >95% accuracy, using only 4GB VRAM and 30 minutes of training time on consumer hardware.
> 

