# VisionBreaker

This repository is the public version of the **VisionBreaker** project, which is actively under development.

### Project Overview

VisionBreaker aims to systematically uncover weaknesses in VLMs by simulating a wide range of attacks under different threat models. In addition, the project introduces a novel **Vulnerability Scale**, a metric that quantifies how susceptible a model is to various forms of adversarial manipulation.

The project includes:

- **Adversarial Attack Evaluation**: Applying both known and novel attacks to assess weaknesses.
- **Threat Model Classification**: Covering white-box, black-box, and gray-box attack settings.
- **Defense Strategy Testing**: Measuring how models react to mitigation mechanisms.
- **Vulnerability Scoring**: Introducing a reproducible framework to rate model robustness.

### Research Topics Covered

- **White-box Attacks**  
  Direct gradient-based attacks leveraging internal model parameters.

- **Black-box Attacks**  
  Query-based and zero-access attacks, including multi-query adaptive perturbations.

- **Gray-box Attacks**  
  Intermediate threat models with partial access to embeddings or output scores.

- **Typographic and Prompt-based Perturbations**  
  Adversarial examples targeting tokenization, visual OCR, and prompt injection.

- **Poisoning and Data Injection**  
  Training-set attacks aimed at injecting hidden behaviors or degrading performance.

- **Multi-stage and Multi-modal Attacks**  
  Combining textual and visual manipulations to exploit the multimodal structure of VLMs.

- **Robustness and Defense Strategies**  
  Evaluating model behavior under defense mechanisms such as input filtering, fine-tuning, and robust training.

- **Jailbreak Techniques**  
  Circumventing safety filters to elicit harmful, unethical, or restricted outputs.

- **Furnace Testing**
A comprehensive stress-testing framework to evaluate model behavior under adversarial pressure and misalignment attempts, inspired by advanced probing techniques.


### Team

**King's College London (Informatics Department):**

- Karine Even-Mendoza

**Ariel University (Computer Science Department):**

- Harel Berger
- Ofek Bar-Shalom
- Meir Shuker


### Vulnerability Scale

We introduce a **Vulnerability Scale** — a unified metric under development to quantify a VLM’s susceptibility across different attack dimensions:


### Tested Models

The initial experiments cover a wide range of publicly available VLMs:

- **BLIP-2**, **InstructBLIP**
- **MiniGPT-4**, **LLaVA**
- **Salesforce/instructblip-flan-t5-xl**

More models will be added as the evaluation pipeline expands.
