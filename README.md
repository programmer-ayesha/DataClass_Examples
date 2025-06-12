# DataClass_Examples
Learn core Python concepts like dataclass, default_factory with clear examples. Perfect for OpenAI SDK beginners!


# Understanding Python `@dataclass`, `field(default_factory=...)`, and Callable 🔍

This mini project explains key Python concepts with real-world examples:
- ✅ How `@dataclass` simplifies class writing
- ✅ Why `field(default_factory=list)` is used to avoid shared memory references
- ✅ What `Callable` is and how it's used in practice

Perfect for beginners trying to build a solid foundation in Python before using OpenAI SDK, LangChain, or agent-based systems.

---

## 📘 Notebook Overview

This notebook contains:
- A `Person` class using `@dataclass` to auto-generate boilerplate code
- Explanation of Python’s memory reference behavior for mutable types like lists
- Use of `field(default_factory=list)` to fix shared memory issues
- A function to test behavior of multiple class instances
- Clear demonstration of `Callable` usage in function typing

---

## 🚀 How to Use This Notebook

1. Open this notebook in Colab:  
   [▶️ View on Colab](https://colab.research.google.com/drive/1WpWtgeLA4CCgCcR_bA01vVXo4SPdC-kk?usp=sharing)

2. Run the code cells one by one and read inline comments for clarity.

3. Modify the `Person` class or `demo_good_usage()` function to experiment and learn more.

---

## 🔥 Key Concepts Explained

### `@dataclass`
Auto-generates `__init__`, `__repr__`, `__eq__`, etc., reducing boilerplate.

### `field(default_factory=list)`
Avoids the bug where all instances of a class share the same list due to Python’s memory reference behavior for mutable defaults.

### `Callable`
Used to declare that a variable is a function with specific input and output types.

---

## 💡 Use Case

This project is part of Ayesha Shahzad's learning path to build a real-world AI product using the OpenAI SDK.  
It helps in understanding core Python topics that are critical for:
- Agent design
- OpenAI SDK workflows
- LangGraph
- Real estate ad generation automation

---

## ✍️ Author

**Ayesha Shahzad**  
AI Engineer in training | Learning Python, OpenAI SDK, and Generative Agents  
🌐 Connect on (https://www.linkedin.com/in/ayesha-shahzad-7b999332a/) | 💻 GitHub: (https://github.com/programmer-ayesha)

