# 🐍 Python Screening Task 2 – AI Debugging Assistant Prompt
## **📌 Task Objective**

- Design a clear and effective prompt that guides an AI language model to:

- Analyze a student’s buggy Python code

- Offer helpful hints and suggestions

- Encourage independent problem-solving

- 🚫 Avoid giving away the complete solution

## 📝 Prompt

* 👉 See prompt.txt
 for the full AI Debugging Assistant Prompt.

## 💡 Reasoning & Design Choices
### 1. Tone and Style

- Supportive, encouraging, and clear — like a patient tutor.

- Use guiding questions instead of direct fixes (e.g., “What happens if you print this variable inside the loop?”).

- Maintain positivity and motivation to keep students engaged, even when debugging is frustrating.

### 2. Balancing Bugs vs. Guidance

- The AI should strike a balance between identifying issues and fostering independent thinking:

- Spot the Area of Concern → Highlight the line, construct, or logic where something seems off.

Example: “Check how total is being updated in your loop.”

- Guide, Don’t Solve → Ask probing questions that nudge the student toward discovery.

Example: “What value does total hold after each iteration? Try printing it to check.”

* 🔑 The principle: Point out the puzzle, let the student solve it.

### 3. Beginner vs. Advanced Learners

- The prompt encourages adaptability based on learner level:

- Beginner: Stick to fundamentals (syntax, variable states, simple loops).

Example: “In Python, what’s the difference between = and == inside an if statement?”

- Advanced: Push for deeper reflection (efficiency, Pythonic practices, best design).

Example: “Your nested loop works fine, but can you think of a way to use a dictionary or set to reduce time complexity?”

- ⚖️ The “no full solution” rule always applies, but guidance complexity changes with skill level.

## 🚀 Setup Instructions

Clone this repository or download the files:

git clone <your-repo-link>
cd python-screening-task-2


Open prompt.txt to review the debugging prompt.

Read README.md (this file) for reasoning and submission notes.