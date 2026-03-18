# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it? At first glance, the game looked fine, and when started to play, noticed some small issues. 
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").
First, the hints didn't match the input and expected output. for example if the guess was smaller than goal, instead of saying too low, go higher, it would say the other way. Second, when clicked on the new game, it didn't seem to open a new game correctly. the message will not show up correctly and values wouldn't refresh correctly. Third, the enable and disable button wouldn't do anything in the game.
---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)? Claude, Copilot and Gemini
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).When encountered the enable/disable issue and asked the AI, it guided me correctly about the position of that specific part of code, and when I moved to the correct place, it worked fine.
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
When encountered with the issue of wrong hints of lower/ higher and Too Low/ Too high, at first ai chat removed half of the hints, meaning only using too low and too high. Even though the basic logic was correct, it wouldn't consider that either of those can show up. So I added them to the logic with an "," so it keeps the original format intact while correcting the logic.

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
