# Jailbreaking Assessment Rules for AI Systems

This repository provides **guidelines, rules, and best practices** for evaluating multi-turn jailbreaking attacks on AI models. It is designed for researchers, AI safety engineers, and cybersecurity practitioners to ensure systematic and reproducible assessments.

---

## 🔹 Overview

Jailbreaking attacks attempt to bypass the ethical and security constraints of AI systems. This repo focuses on:

- Defining clear **assessment rules**
- Categorizing types of jailbreaking attempts
- Standardizing evaluation protocols for multi-turn conversations

---


## 📖 Rules for Jailbreaking Assessment

The following rules guide the assessment process:

1. **Reproducibility**  
   Ensure that all test cases can be consistently reproduced with the same model configuration.

2. **Multi-turn Context**  
   Consider attacks that exploit the AI’s memory over multiple conversation turns.

3. **Ethical Compliance**  
   Do not attempt real-world malicious tasks; focus on **simulation and controlled testing**.

4. **Categorization**  
   Classify attacks by type (e.g., prompt injection, role manipulation, logic bypass).

5. **Metrics & Scoring**  
   Use both **human evaluation** and automated metrics like METEOR, BLEU, or semantic similarity to score attacks.

6. **Documentation**  
   Record each test case with:  
   - Initial prompt  
   - Attack sequence  
   - Model response  
   - Pass/fail result  
