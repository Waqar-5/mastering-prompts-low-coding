# Prompt Engineering 📌

Welcome to **Prompt Engineering**, the art and science of communicating effectively with AI!  
This repository is your **personal library for mastering prompts**, learning techniques, and storing examples for practical use.

---

## What is Prompt Engineering? 🤖

Prompt engineering is the **skill of crafting inputs (prompts) for AI models** to get the best possible output.  
It’s **not about memorizing text**, but about **learning how to guide AI** clearly and effectively.

> Example:
> - Weak prompt: `"Write something about dogs."`
> - Strong prompt: `"Write a fun 3-sentence story about a dog who learns to skateboard."`

---

## Why is it Important? 🌟

Modern AI models (like GPT, Claude, Gemini) are powerful but need **clear guidance**:

- Produces **accurate and relevant results**  
- Reduces **vague or incorrect outputs**  
- Enables **specific formats** (tables, bullet points, code)  
- Supports **creative, professional, or technical tasks**

---

## Components of a Strong Prompt 🛠️

1. **Instruction** – Tell AI exactly what to do  
   `"Summarize this article in 3 bullet points."`  

2. **Context** – Give AI background information  
   `"You are a history teacher. Explain the causes of World War II in simple words."`  

3. **Constraints / Format** – Set rules for output  
   `"Write a 4-line poem about spring using rhyming words."`  

4. **Examples (Few-Shot Learning)** – Show what correct output looks like  


AI continues: `"Amo programar"`

---

## Types of Prompting 📚

| Type | Description | Example |
|------|-------------|---------|
| Zero-Shot | AI performs task without examples | `"Translate to French: 'Good morning'"` |
| One-Shot | AI given 1 example | `"Translate 'Hello' → 'Bonjour'. Now translate 'Good morning'"` |
| Few-Shot | AI given multiple examples | See above example |
| Role-Based | AI acts as an expert | `"You are a career coach. Suggest a resume format."` |
| Chain-of-Thought | AI explains reasoning step by step | `"Solve 23 + 17. Show your steps."` |

---

## How Prompt Engineering Works 🔄

1. **Define your goal** – What do you want AI to do?  
2. **Craft your prompt** – Use instruction, context, examples, constraints.  
3. **Test it** – Check AI’s output.  
4. **Refine it** – Adjust wording or examples to improve output.  
5. **Repeat** – Iteratively improve until consistent results.

---

## Advanced Techniques ⚡

- **Prompt Chaining** → Break large tasks into smaller prompts  
- **Dynamic Prompting** → Adjust prompts based on previous AI responses  
- **Template Prompts** → Reusable prompt structures  
- **Safety & Bias Controls** → Ensure ethical and safe AI output

---

## Real-Life Example ✉️

**Task:** Write a professional resignation email  

- Weak Prompt: `"Write a resignation email."` → Too vague  
- Strong Prompt:  



- Output: Well-structured, professional email ready to use.

---

## Resources & References 🌐

**GitHub Repos:**  
- [Prompt Engineering mastering Guideline](https://github.com/panaversity/learn-low-code-agentic-ai/tree/main/00_prompt_engineering)
- [DAIR.AI Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)
- [Awesome Prompt Engineering](https://github.com/promptslab/Awesome-Prompt-Engineering)  
- [Anthropic Prompt Engineering Tutorial](https://github.com/anthropics/prompt-eng-interactive-tutorial)  

**Websites & Tutorials:**  
- [Learn Prompting](https://learnprompting.org)  
- [OpenAI Prompt Guide](https://platform.openai.com/docs/guides/prompt-engineering)  
- [Google Cloud Prompt Engineering](https://cloud.google.com/discover/what-is-prompt-engineering)

**Videos:**  
- [Panaversity YouTube Class Playlist](https://www.youtube.com/playlist?list=PL0vKVrkG4hWpeKmZyCRTpfRiLQ13b5uRX)
- [Prompt Engineering for Beginners – YouTube](https://www.youtube.com/watch?v=_ZvnD73m40o) 
- [Mastering ChatGPT Prompts – YouTube](https://www.youtube.com/watch?v=p09yRj47kNM)


---

## Tips for Mastery 🏆

1. Practice consistently – create, test, and refine prompts  
2. Use **role and context** for specialized tasks  
3. Keep **examples and templates** reusable  
4. Maintain a **personal library** (GitHub repo, Markdown files)  
5. Stay updated – AI and prompt strategies evolve quickly

---

**Conclusion:**  
Prompt engineering is **a skill, not memorization**.  
With practice, you can **guide AI to produce exactly what you want**, for writing, coding, creativity, and more!  

---


# Prompt Engineering vs Context Engineering 📌

In AI development, especially with **Large Language Models (LLMs)** like GPT, Claude, or Gemini, two important concepts often come up: **Prompt Engineering** and **Context Engineering**.  
While they are related, they serve different purposes and work together to guide AI effectively.

---

## 1️⃣ What is Prompt Engineering?

**Prompt Engineering** is the **art and science of designing the input you give to an AI model** to get the best possible output.  

- Focus: **The instructions you provide**  
- Goal: Make AI understand **what task to perform and how to perform it**  
- Example:  
  ```text
  Task: Summarize an article
  Weak Prompt: "Summarize this."
  Strong Prompt: "You are a professional editor. Summarize this article in 5 bullet points using clear, concise sentences."
Key Point: Prompt engineering is about crafting effective instructions and examples.

2️⃣ What is Context Engineering?
Context Engineering is the technique of providing relevant background, information, or memory so the AI can give better results.

Focus: The information AI uses to make decisions

Goal: Make AI understand the situation, history, or details before generating output

Example:

text
Copy code
You want AI to continue a conversation with a user:
Context: Previous messages, user preferences, or prior knowledge
Key Point: Context engineering is about what the AI knows and remembers when processing the prompt.

3️⃣ Main Differences at a Glance
Feature	Prompt Engineering	Context Engineering
Focus	How you ask the AI	What AI knows before answering
Purpose	Guide AI to perform a task effectively	Provide AI with relevant background or history
Components	Instructions, constraints, examples	Previous conversation, memory, documents, data
Example	"Write a 3-line poem about spring"	Including previous chat or document: "User prefers rhyming poems"
Key Skill	Writing precise prompts	Providing and organizing relevant information

4️⃣ How They Work Together
Prompt engineering tells the AI what to do

Context engineering tells the AI what it should know before doing it

Example:
Task: Write a personalized story for a child
Context: "Child’s name is Sara, age 8, loves space and animals."
Prompt: "Write a fun bedtime story for Sara that includes a spaceship and a cat."
Result: AI generates a story tailored specifically for Sara.

5️⃣ Key Takeaways
Prompt Engineering → “How to ask”

Context Engineering → “What AI knows when answering”

Both are essential for effective AI applications

Mastering both lets you build powerful, personalized, and accurate AI outputs

🔧 Practical Tip for GitHub Repo
Prompt Examples Folder: Store all your prompt engineering tests

Context Examples Folder: Store your context files, memory setups, or document references

Keep them linked together for experiments

Conclusion:
Prompt engineering is about instruction, while context engineering is about information.
Together, they make AI more accurate, relevant, and creative.

