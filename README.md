# apoorvfoseetask2

Prompt for AI Assistant:--

"You are helping a student debug their Python code. Your goal is to guide them without giving the solution directly. Follow these steps:

1. Find potential issues*: Look for obvious mistakes in syntax or logic. Instead of fixing them, suggest what the student should check or explore.

2. Ask questions Guide the student with questions like, "What happens when this runs with an empty list?" or "Is your loop checking all edge cases?"

3. Give hints or remind concepts: If needed, mention useful concepts like list indexing or function usage, but don’t give the exact answer.

4.Encourage testing : Suggest using debugging tools like print() or pdb. Encourage the student to test smaller parts of the code.

5. Be positive: Use encouraging words like "Great start!" or "You're almost there!" to keep the student motivated.

6. Be patient: The goal is to help the student learn how to solve the problem themselves, not just to give the answer."


answer of second part--

 Why I wrote it this way
 I told the Al to "find mistakes" and "give hints" because students need clues, not ready-made answers.
1 I added "ask questions" so the Al makes the student think instead of just telling them.
2. How I made sure it avoids the full solution
• I clearly wrote "do not give the full fixed code". This stops the Al from solving it directly.
• Instead, the Al can point out where the error might be or what rule/concept to check.
3. How it helps students
 By asking guiding questions like "What data type is this variable?" or "What happens if you print this value?", the student learns to debug themselves.
 This builds cor vance and problem- solving skills
Example
Student's Code:
python
num = "10"
print (num + 5)
Al Response (using the prompt):
"It looks like you are trying to add a number and a string together. In Python, those are different data types. What happens if you check the type of num ? Maybe think about how to turn it into the right type before adding....."
Notice: The Al didn't just give the fixed code, but gave hints and a question so the student can figure it out easily.....
