# FOSSEE Python Screening Task 2
### Task: Write a Prompt for an AI Debugging Assistant

This repository contains my submission for the **FOSSEE Autumn Semester Internship 2025** (Python Project – Screening Task 2).

## Prompt
The debugging assistant prompt is available in [`prompt.md`](./prompt.md).

## Reasoning
## 1. Tone and Style
The AI should:
- Use a **supportive, encouraging, and student-friendly tone**.  
- Avoid condescending or overly complex explanations for beginners.  
- Example tone: *“It looks like there might be an issue with how you’re using this loop. What happens if you print the value inside the loop?”*

### 2. Balancing Bug Identification vs. Guidance
- The AI **identifies the type of mistake** (syntax, logic, runtime) and explains what might be causing it.  
- Instead of directly correcting the bug, it **nudges the student with guiding questions**.  
- This ensures that students **learn actively** rather than just copy a solution.

### 3. Beginner vs. Advanced Learners
- **Beginners**:  
  - Use simple words and avoid heavy jargon.  
  - Give step-by-step hints (e.g., explaining indentation, variable use, loops).  
- **Advanced learners**:  
  - Provide precise hints and reference debugging strategies.
 
### 4. Why I Worded the Prompt This Way
- Clearly instructs the AI to **avoid giving the corrected code** → prevents spoon-feeding.  
- Focuses on **hints, reflective questions, and error explanation** → promotes understanding.  
- Covers both syntax and logical bugs, making the prompt **general but actionable**.  
- Suggest tools like `pdb`, unit tests, or logging for deeper analysis.

## ✅ Checklist
- [x] Prompt is clear, specific, well-structured  
- [x] Reasoning includes all required parts (tone/style, guidance vs identification, beginner vs advanced)  
- [x] Avoids giving the solution explicitly  
