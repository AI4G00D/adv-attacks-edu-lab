# 🔐 adv-attacks-edu-lab

**Educational Lab for Adversarial Machine Learning (ML) and Large Language Model (LLM) Attacks**  
*— with strong emphasis on AI safety, ethical demonstration, and responsible use.*

---

## 🎯 Purpose

This repository is a curated educational playground showcasing adversarial attacks in both traditional ML and LLM systems. It aims to help students, security researchers, and AI developers understand how models can be manipulated—and how to defend against such threats.

> ⚠️ All experiments and demos are conducted in isolated environments and are intended strictly for **educational purposes**.

---

## 🧪 Attack Categories Covered

| Category                  | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `prompt-injection-playground/` | Demonstrates how prompts can be manipulated to override LLM safety instructions |
| `fgsm-attack/`            | Uses Fast Gradient Sign Method to perturb image classifiers (ML)            |
| `pgd-attack/`             | Projects adversarial noise to trick neural nets (ML)                        |
| `jailbreak-attacks/`      | Bypasses LLM content filters to produce unsafe or forbidden outputs         |
| `data-poisoning-attacks/` | Inserts corrupted samples in training data to degrade or subvert behavior   |
| _(more coming soon...)_   |                                                                             |

---

## 📦 Repository Structure

```plaintext
adv-attacks-edu-lab/
│
├── README.md                  ← You are here
├── LICENSE                    ← MIT License for educational reuse
│
├── prompt-injection-playground/
│   └── README.md, .ipynb, demo video
│
├── fgsm-attack/
│   └── README.md, FGSM notebook
│
├── pgd-attack/
│   └── README.md, PGD notebook
│
└── ...
