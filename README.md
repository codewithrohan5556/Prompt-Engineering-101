# 🎯 Prompt Engineering Mastery

A comprehensive collection of prompt engineering techniques, templates, and best practices for optimizing Large Language Model (LLM) outputs.

---

## 📚 What's Inside

| Category | Topics Covered |
|----------|----------------|
| **Basic Techniques** | Zero-shot, Few-shot, Instruction-based prompting |
| **Advanced Methods** | Chain-of-Thought (CoT), Tree-of-Thoughts (ToT), ReAct |
| **Role Prompting** | System prompts, Persona-based, Expert role-playing |
| **Output Formatting** | JSON mode, Structured data extraction, Code generation |
| **Optimization** | Temperature tuning, Token management, Iterative refinement |

---

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
