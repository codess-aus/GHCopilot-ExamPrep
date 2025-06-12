
```markdown
# 🧠 Interact with GitHub Copilot  
✅ Completed  
🎯 100 XP  
⏱️ 2 min

---

## 🚀 What’s This Unit About?  
Learn how to vibe with GitHub Copilot like a pro.  
Unlock shortcuts, features, and hacks to make your dev life smoother.

---

## ✨ Inline Suggestions = Instant Code Magic  
Copilot watches you type and drops code suggestions in real time.  
🧠 Predicts your next move.  
👀 Shows grayed-out text ahead of your cursor.

**Controls:**  
- `Tab` or `→` = Accept  
- `Esc` or keep typing = Reject

💡 Great for boilerplate or repetitive tasks.

```python
def calculate_average(numbers):
    # Start typing here and watch Copilot suggest the function body
```

---

## 🎛️ Command Palette = Shortcut Central  
Access Copilot’s powers with a few keystrokes.

**How to open:**  
- `Ctrl+Shift+P` (Windows/Linux)  
- `Cmd+Shift+P` (Mac)

**Try commands like:**  
- `Explain This`  
- `Generate Unit Tests`

---

## 💬 Copilot Chat = Talk to Your AI Buddy  
Ask questions in plain English. Copilot replies with code, fixes, or ideas.

**Example:**  
> "How do I implement a binary search in Python?"

```python
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return -1
```

---

## 🧩 Inline Chat = Code-Specific Conversations  
Chat with Copilot right inside your code.

**Shortcut:**  
- `Ctrl+I` (Windows/Linux)  
- `Cmd+I` (Mac)

**Use slash commands:**  
- `/explain` – What’s this code doing?  
- `/suggest` – Got better code?  
- `/tests` – Make unit tests  
- `/comment` – Turn comments into code

```python
# Select the function, use the shortcut to open the inline chat, and type: /explain
def calculate_average(numbers):
```

---

## 💬 Comments to Code = Natural Language Coding  
Write a comment → Copilot writes the code.

```python
# Function to reverse a string
def reverse_string(s):
    return s[::-1]
```

---

## 💡 Multiple Suggestions = Pick Your Flavor  
Copilot gives you options.

**Look for:**  
- 💡 Light bulb icon  
- `Alt+]` (Windows/Linux)  
- `Option+]` (Mac)

Cycle through different code styles and pick your fave.

---

## 📖 Explanations = Understand Code Fast  
Need help decoding someone else’s logic?

**How to use:**  
- Select code block  
- Right-click → `Copilot: Explain This`

Copilot breaks it down for you.

---

## 🧪 Automated Test Generation = Bug Catcher Mode  
Copilot writes unit tests so you don’t have to.

```python
def add(a, b):
    return a + b

# Copilot might generate:
def test_add():
    assert add(2, 3) == 5
    assert add(-1, 1) == 0
    assert add(0, 0) == 0
```

---

## 🧠 Pro Tip: Train Your Copilot  
The more you use it, the smarter it gets.  
🧼 Keep your code clean and well-commented for better suggestions.

```
