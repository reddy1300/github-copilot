**What is Prompt Engineering?**
- Prompt Engineering is basically the art of crafting text prompts that can be used to control the output of large language models like ChatGPT, Google, and Bing Chat.

### The design considerations generally follow the rules of normal human language, involving:
1. **Clarity:** Unambiguous prompts
2. **Context:** Adequate context within the prompt for AI guidance.
3. **Precision:** Targeted information or desired output.
4. **Adaptability:** Flexibility with variuos AI models.

1. ### Persona Pattern
One of the most common pattern and a very effective pattern is the persona pattern.
- Its basically you want AI to pretend to be someone(A person)

**Fromat:**
- Act as Persona X
- Perform Task Y

You will need to replace "X" with an appropriate persona, such AI Engineer or Data Analyst then identify a task "Y"

Ex Prompt: Act as a AI Engineer and develop a complete project plan to develop a sudo game.

### Flipped Interaction Pattern
- The flipped interaction pattern is a way to get a large language model to ask you questions.
- This is useful when you don't know what questions to ask yurself, or when you want to be quizzed or tested on something.
- To use the flipped interaction pattern, you simply tell the large language model what topic you want to ask questions about.
- You can also tell the large language model how many questions you want it to ask, and how many questions you want it to ask at a time.
- One handy thing you can do is end the flipped interaction prompt with "ask me the first question".
- This will cause the large language model to ask you one question at a time and you can answer the questions as they are asked.

**Format:**
- I would like you to ask me questions to achieve X
- You should ask questions until condition Y is met or to achieve this goal (alternatively, forever)
- (Optional) ask me questions one at a time, two at a time, ask me the first question, etc.
- You will need to replace "X" with an appropriate goal, such as "creating a meal plan" or "creating variations of my marketing materials." You should specify when to stop asking questions with Y. Examples are "until you have sufficient information about my audience and goals" or until you know what i like to eat and my caloric targets."

### Cognitive Verifier Pattern
- The cognitive verifier pattern is a way to improve our interactions with large language models by asking them to break down questions into a series of sub-questions.
- This is useful because large language models can better understand and answer questions when they are broken down into smaller, more specific pieces.
- To use the cognitive verifier pattern, we simply tell the large language model to "generate a number of additional questions that would help more accurately answer the question."
- The large language model will then generate a series of sub-questions that it believes are relevant to the original question.
- We can then answer the sub-questions and the large language model will use our answers to generate a more accurate answer to the original question.
- The cognitive verifier pattern is a powerful tool that can help us get more out of our interactions with large language models.

**Format:**
- When you are asked a question, follow these rules.
- Generate additional questions that would help you more accurately answer the question. Combine the answers to the individual questions to produce the final answer to the overall question.

**Example:** 
I want focus on only one type of social media advertising to promote my online course company. Which one should i choose?

### Question Refinement Pattern
- The question refinement pattern is a way to improve our interations with large language models by asking them to suggest a better question that we should ask.
- To use the question refinement pattern, we simply tell the large language model to "suggest a better question and ask me if i would like to use it instead."
- This will prompt the large language model to generate a new question that it believes is more likely to get the desired output.
- We can then choose to use the new question or the original question.

**Format:**
**Step1:**
- From now on, Whenever i ask a question, suggest a better version of the question to use insteasd
- (Alternatively) From now on, Whenever i ask a question, suggest a better version of the question and ask me if i would like to use it instead.

**Step2:**
- Ask Your Question
	- Question: Should i invest in Apple stock?
	- Refined Question: What factors should i consider when deciding if i should invest in Apple stock and how do they relate to my overall investment portfolio?

### Audience Persona Pattern
- The audience persona pattern is a way to tell a large language model to produce an output that is tailored to a specific audience.
- To use the audience persona pattern, we simply tell the large language model the persona of the audience we want it to produce the output for.
- The audience persona pattern can be used to improve the communication between large language models and humans.
- It can also be used to generate creative and interesting outputs.
