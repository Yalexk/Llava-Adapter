# Llava-domain-adaptation

This project aims to investigate the effectiveness of parameter efficient fine tuning (PEFT) on multimodal language models for different visual domains. Using LLaVA as a baseline, the project evaluates LoRA and adapter based PEFT on fine grained datasets, comparing performance across methodology and domain type.

Current domains being explored:
- Birds
- Cars

## Basic setup

From the project root, run:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Then open the notebook files in the baseline folder and run the cells in order.

## Environment variables

Include the huggingface token in the .env file for logging in