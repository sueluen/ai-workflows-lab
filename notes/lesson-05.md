# Lesson 05 — Advanced Prompt Engineering

## Core Concepts
- Prompt engineering is iterative optimization
- Better prompts create more reliable outputs
- LLMs are stochastic and non-deterministic
- Different prompting strategies improve reasoning quality

## Important Prompting Techniques

### Zero-shot Prompting
- Single instruction without examples
- Fast but less controlled

### Few-shot Prompting
- Provide examples to guide output style and structure
- Improves consistency and formatting

### Chain-of-Thought (CoT)
- Forces step-by-step reasoning
- Strongly improves logical and math-related tasks

### Generated Knowledge
- Inject external/company-specific data into prompts
- Foundation for enterprise AI workflows

### Least-to-Most
- Break large problems into smaller sequential tasks
- Useful for planning and agent systems

### Self-Refine
- Ask the model to critique and improve its own answer
- Useful for coding, writing, and analysis

### Maieutic Prompting
- Ask the model to explain its reasoning
- Helps detect inconsistencies and hallucinations

## Temperature
- Low temperature = deterministic / stable outputs
- High temperature = creative / varied outputs
- Choose depending on business need

## Prompt Engineering Best Practices
- Provide clear context
- Specify output format and constraints
- Use examples when possible
- Use templates for reusable workflows
- Iterate and validate outputs

## Real-World Insights
- AI output quality heavily depends on prompt design
- Enterprise AI systems rely on structured prompting
- Many modern AI agents use self-refine and chain-of-thought internally

## Assignment Insight
- The Flask example was not about learning Flask
- The real goal was understanding iterative AI improvement
- Self-refine = generate → critique → improve loop

## Questions
- How do modern AI agents combine CoT and self-refine?
- When should RAG be preferred over generated knowledge prompting?
