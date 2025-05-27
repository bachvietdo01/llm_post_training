# LLM Post-Training 

This repository contains workflows for post-training large language models (LLMs), specifically focusing on fine-tuning and preference alignment methods using Meta's `llama3.2-1B-Instruct` as the base model.

## Notebooks Overview

### `fine_tuning_sft.ipynb`

Performs **Supervised Fine-Tuning (SFT)** on the `llama3.2-1B-Instruct` model using a dataset of Docker command instructions. This notebook demonstrates how to guide the model to follow task-specific instructions more accurately.

### `preference_alignment_dpo.ipynb`

Applies **Direct Preference Optimization (DPO)** to align the base model’s outputs with human preferences. This method helps refine model behavior beyond standard supervised learning.

### `preference_alignment_ppo.ipynb`

Uses **Proximal Policy Optimization (PPO)** for preference alignment on the `gsm8k` dataset. PPO is a reinforcement learning method that fine-tunes the model to generate more desirable outputs based on reward signals.
