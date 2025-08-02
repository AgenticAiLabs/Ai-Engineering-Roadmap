# Prompt Engineering

Prompt engineering is the practice of designing effective inputs (prompts) to guide large language models (LLMs) in generating accurate, useful, or creative outputs. As models grow in capability, good prompts become the key to unlocking their full potential.

## Learning Objectives

By the end of this module, you should be able to:

- Understand different prompt formats and strategies
- Apply prompting techniques like zero-shot, few-shot, and chain-of-thought
- Use structured prompting, templates, and prompt chaining
- Evaluate and iterate on prompts for consistent results

## Why It’s Important

Prompting is often more powerful than fine-tuning. It allows you to leverage pretrained models effectively without modifying them — ideal for prototyping, RAG, and agent-based systems.

## Core Topics & Resources

### 1. Foundations of Prompting

- [Prompt Engineering Guide](https://www.promptingguide.ai/) — **Free**
- [OpenAI Prompt Examples](https://platform.openai.com/examples) — **Free**
- [Google Prompt Engineering Crash Course (YouTube)](https://www.youtube.com/watch?v=qw1pV_q3-ZA) — **Free**

Covers:
- Basic prompt structure
- Instruct vs. completion models
- Few-shot examples and prompt format

### 2. Prompting Techniques

- [Chain of Thought Prompting Paper](https://arxiv.org/abs/2201.11903) — **Free**
- [ReAct Prompting (Reason + Act)](https://arxiv.org/abs/2210.03629) — **Free**
- [Guidelines for Iterative Prompting](https://github.com/dair-ai/Prompt-Engineering-Guide) — **Free**

Techniques:
- **Zero-shot prompting**  
- **Few-shot prompting**
- **Chain-of-thought reasoning**
- **Self-consistency** prompting
- **Toolformer-style** tool-aware prompting

### 3. Prompt Tools & Frameworks

- [PromptLayer](https://www.promptlayer.com/) — Logging and debugging for prompts  
- [LangChain Prompt Templates](https://docs.langchain.com/docs/components/prompts/) — **Free**
- [Prompt Engineering in LangChain (Docs)](https://docs.langchain.com/docs/guides/prompts) — **Free**

Covers:
- Prompt templating and variable injection
- Prompt chaining (outputs feeding next prompts)
- Prompt evaluation at scale

### 4. Evaluation & Safety

- [Evaluating Prompt Quality (Google DeepMind)](https://arxiv.org/abs/2302.09604) — **Free**
- [OpenAI Moderation API](https://platform.openai.com/docs/guides/moderation) — **Free**

Covers:
- Prompt debugging and output consistency
- Prompt sensitivity, bias, hallucination
- Output scoring and A/B testing

### 5. Advanced Prompt Engineering Resources

- [Awesome Prompt Engineering (GitHub)](https://github.com/promptslab/awesome-prompt-engineering) — **Curated list**
- [Prompt Engineering Papers (arXiv)](https://arxiv.org/search/?query=prompt+engineering&searchtype=all) — **Free**
- [Prompt Engineering for Developers (DeepLearning.AI)](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) — **Free**
- [Prompt Engineering Leaderboard (Hugging Face)](https://huggingface.co/spaces/mteb/leaderboard) — **Free**

Covers:
- Research papers and leaderboards
- Advanced prompt design and evaluation
- Community-curated resources

## Suggested Projects & Practice

- Build a prompt that explains a concept at beginner and expert levels
- Design a prompt that generates test questions from documents
- Compare outputs from zero-shot vs. chain-of-thought
- Use LangChain to create a multi-step prompt workflow


## Checkpoint: Before You Move On

You should now be able to:

- Craft effective prompts for different tasks
- Use advanced prompting strategies to improve output quality
- Integrate prompts into chains and RAG systems
- Evaluate and debug prompts methodically

🔗 Next: [AI Tooling →](./05_ai-tooling.md)
