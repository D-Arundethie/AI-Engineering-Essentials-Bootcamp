# AI-Engineering-Essentials-Bootcamp
AI Engineering Essentials Bootcamp _ft_ Zuu Crew

## Week 01 - Prompt Engineering Essentials

### 1. Zero-Shot Learning (ZSL)
The model performs a task **without seeing any examples** of that task beforehand.
- Relies entirely on *instructions or prompts*
- No labeled examples are provided
- Works if the model has general knowledge from pretraining  

**Use case:** Classifying sentiment of a sentence just by asking _“Is this positive, negative, or neutral?”_

### 2. Few-Shot Learning (FSL)
The model is given a **few examples** to learn a task before performing it.  
- Usually use 2–10 examples  
- Helps model understand task format and context  
- More reliable for complex tasks

**Use case:** Converting dates from MM/DD/YYYY to YYYY-MM-DD by showing 3–5 examples in the prompt

### 3. Chain-of-Thought (CoT)
The model explains its reasoning **step by step** before giving the final answer.
- Useful for *complex reasoning* tasks
- Reduces errors in math and logic problems
- Can be used with zero-shot or few-shot prompts

**Use case:** Solving math word problems or logical puzzles

### 4. Tree-of-Thought (ToT)
An advanced reasoning technique where the model explores **multiple reasoning paths** (like a tree) before choosing the best solution.
- Builds on CoT but *considers alternatives*, not just one path  
- Useful for decision-making, planning, or hard logic puzzles  
- Helps improve *accuracy and creativity* in decision-making

## Week 02 - LLM Fine Tuning
