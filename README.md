#  🎯 Prompt Engineering Guide
### Production-ready techniques for building reliable LLM applications

A comprehensive collection of prompt engineering patterns
used in production AI systems — with working code examples
across Anthropic Claude, OpenAI GPT, and Groq Llama.

Built by an AI Engineer for AI Engineers and startup founders
who need prompts that actually work in production.

---

## Why This Exists

Most prompt engineering resources show toy examples.
This repository shows production patterns — the kind
used in real AI products handling real user requests.

Every technique includes:
- What it is and when to use it
- Working Python code you can copy
- Real world startup use case
- Common mistakes and how to avoid them

---

## Quick Start
```bash
git clone https://github.com/yourusername/prompt-engineering-guide
cd prompt-engineering-guide
pip install -r requirements.txt
cp .env.example .env
# Add your API keys to .env
python 01_basics/zero_shot.py
```

---

## Techniques Covered

| Technique | When to Use | File |
|-----------|-------------|------|
| Zero Shot | Simple tasks | 01_basics/zero_shot.py |
| Few Shot | Consistent formatting | 01_basics/few_shot.py |
| Chain of Thought | Complex reasoning | 02_advanced/chain_of_thought.py |
| Structured Output | JSON extraction | 03_output_control/structured_outputs.py |
| Self Consistency | High accuracy needed | 02_advanced/self_consistency.py |

---

## Real World Templates

Built for common startup use cases:

- Customer Support Agent
- Content Generation Pipeline
- Data Extraction from Documents
- Code Review Assistant
- Classification at Scale

---

## Supported Providers

- Anthropic Claude (Haiku and Sonnet)
- OpenAI GPT-4o Mini
- Groq Llama 3.1 70B (FREE)

---

## Who This Is For

- Founders building AI products
- Engineers integrating LLMs
- Anyone tired of prompts that work
  sometimes but not always

---

## Connect

Built by Rohan Patil — AI Engineer
LinkedIn: linkedin.com/in/rohan-patil-ai

## 📁 Project Structure

```plaintext
prompt-engineering-guide/
│
├── README.md                    # Main guide
├── requirements.txt             # Dependencies
├── .env.example                 # API key template
├── .gitignore                   # Never commit .env
│
├── 01_basics/
│   ├── README.md
│   ├── zero_shot.py
│   ├── few_shot.py
│   └── system_prompts.py
│
├── 02_advanced/
│   ├── README.md
│   ├── chain_of_thought.py
│   ├── tree_of_thought.py
│   └── self_consistency.py
│
├── 03_output_control/
│   ├── README.md
│   ├── structured_outputs.py
│   ├── json_extraction.py
│   └── formatting_control.py
│
├── 04_real_world_templates/
│   ├── README.md
│   ├── summarization.py
│   ├── classification.py
│   ├── extraction.py
│   ├── question_answering.py
│   └── code_generation.py
│
├── 05_multi_provider/
│   ├── README.md
│   ├── anthropic_examples.py
│   ├── openai_examples.py
│   └── groq_examples.py
│
├── 06_evaluation/
│   ├── README.md
│   └── prompt_evaluation.py
│
└── examples/
    ├── startup_use_cases/
    │   ├── customer_support.py
    │   ├── content_generation.py
    │   ├── data_extraction.py
    │   └── code_review.py
    └── notebooks/
        └── prompt_playground.ipynb
