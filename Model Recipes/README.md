# SGL Model Recipes

This repository is a **community-maintained collection of reference recipes** for deploying and operating SGL across diverse environments.  

---

## Overview

The repository provides:

- **Curated configurations and scripts** for SGL deployment  
- **Usage guidelines and tuning notes** contributed by the community  
- Coverage across a broad range of **models, hardware platforms, and application scenarios**  

Each recipe is designed to be:

- **Reliable** – validated and tested in real environments  
- **Reproducible** – including environment details and exact launch commands  
- **Adaptable** – easy to extend for your own needs  

---

## Guides

### DeepSeek  

- DeepSeek Model Recipes
  Reference configurations and scripts for running DeepSeek models with SGL across different hardware setups.  

### GPT-OSS  

- GPT-OSS Model Recipes
  Reference configurations and scripts for running GPT-OSS models with SGL across different hardware setups.

### Llama4  

- Llama4 Model Recipes
  Reference configurations and scripts for running Llama4 models with SGL across different hardware setups.
  
---

## Contributing

We welcome contributions from the community!  

1. Start from the template in `recipes/_template/`.  
2. Include:  
   - **Environment details** (driver, CUDA, SGL version, OS)  
   - **Hardware description** (GPU type, count, interconnect)  
   - **Configuration** (key flags, parallelism, quantization, memory settings)  
   - **Reproducibility steps** (exact commands or YAMLs)  
   - **Results and benchmarks** (tokens/s, latency, throughput, etc.)  
   - **Known issues / caveats**  

3. Submit a PR with a short summary of:  
   - **What** you added  
   - **Why** it is useful  
   - **How** to reproduce the results 

---

> 🚀 Whether you’re running small experiments or scaling to production, these recipes are here to help you get the most out of **SGL**.
