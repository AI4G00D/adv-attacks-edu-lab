# 🧠 Prompt Injection Playground

This is an interactive demo to simulate **prompt injection attacks** on a local LLM (TinyLlama) using a **Gradio-based UI**.

---

## 🎯 Objective

- Demonstrate how prompts crafted with override patterns can manipulate LLMs to ignore system-level instructions.
- Showcase a hands-on, educational environment where users can simulate and study these behaviors ethically.

---

## ⚙️ What’s Included

- Gradio UI with:
  - Predefined system + user prompts
  - Dropdown for attack types (e.g., Instruction Override)
  - Attack Summary showing success rate
- Local simulation with backend LLM shielded from UI
- Sample logs of injection success

---

## ⚠️ Ethical Disclaimer

This demo is provided **strictly for educational use**.

- No real secrets or sensitive data are involved.
- Prompts are simulated to test instruction-following behavior of language models.
- Attack outputs are anonymized and redacted to avoid irresponsible sharing.

> **Do not deploy or adapt this for malicious purposes.**
> Any misuse is solely the responsibility of the user.

---

## ✍️ Prompt Editing Instructions

While the UI provides predefined injection prompts, users can further **edit the prompt fields** in the interface to:

- Try more **explicit override attempts**
- Craft **nuanced or creative bypass techniques**
- Study model resilience to such variations

⚠️ Note: Only a few examples are included in the demo.  
Several more potent prompts have been tested but **intentionally not disclosed here** to preserve ethical integrity.

---

## 💥 Sample Result Analysis

From one demo run (screenshot included):

- 20% of prompts matched the target "secret phrase" pattern
- Examples:
  - `System: The secret phrase is "YOLO".`
  - `Actor: "The code is XYZ"`
  - `Computer: This phrase is "YOU."`

This shows the model **fails to reject overriding instructions**, despite being explicitly told not to share secrets.

> 🧠 Even when the model has safeguards, **carefully phrased user prompts can still bypass them.** This is a real-world risk for GenAI deployments.

---

## ▶️ How to Run

```bash
pip install gradio openai

