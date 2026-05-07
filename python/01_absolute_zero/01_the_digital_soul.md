# Level 1: The Digital Soul (How Python Thinks)

To become a Google Backend Engineer, you must stop seeing code as "text" and start seeing it as **instructions for electricity**. 

## 1. The Trinity of the Machine
Every line of code you write moves through three stages:
1. **The Code (You):** You write English-like words.
2. **The Interpreter (Python):** A program that translates your words into 1s and 0s.
3. **The CPU (Hardware):** The "Brain" that moves electricity to perform math.



## 2. Interactive Sandbox: Your First Command
The `print()` function sends data from the "Brain" (RAM) to the "Screen" (Standard Output).

**Your Task:** Change the text inside the quotes to `Initializing Google Backend...` and hit the button.

<html>
  <div style="background: #1e1e1e; padding: 20px; border-radius: 8px; border: 1px solid #333;">
    <label style="color: #007acc; font-weight: bold; display: block; margin-bottom: 5px;">Python Editor</label>
    <textarea id="code_01" style="width: 100%; height: 80px; font-family: 'Courier New', monospace; background: #2d2d2d; color: #f8f8f2; padding: 10px; border: 1px solid #444; border-radius: 4px; resize: none;">print("Hello")</textarea>
    <button onclick="runPython('code_01', 'out_01')" style="margin-top: 10px; padding: 10px 20px; background: #007acc; color: white; border: none; cursor: pointer; border-radius: 4px; font-weight: bold;">Execute Logic</button>
    <div style="margin-top: 15px;">
      <label style="color: #28a745; font-weight: bold; display: block; margin-bottom: 5px;">System Output</label>
      <pre id="out_01" style="background: #000; color: #0f0; padding: 15px; border-radius: 4px; overflow-x: auto; min-height: 40px; border: 1px solid #222;">Output will appear here...</pre>
    </div>
  </div>
</html>

## 3. Common Mistakes
* **The Quote Trap:** `print(Hello)` will crash because it thinks `Hello` is a variable.
* **Case Sensitivity:** `Print("Hello")` won't work. It must be lowercase.

<div style="margin-top: 30px; text-align: center;">
    <a href="02_the_megaphone_anatomy.md" style="padding: 15px 30px; background: #28a745; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; display: inline-block;">Next Lesson: 02 - The Megaphone Anatomy →</a>
</div>
