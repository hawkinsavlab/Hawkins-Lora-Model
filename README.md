# 🚲 Hawkins, Indiana - Architecture & Atmosphere LoRA

![Model Version](https://img.shields.io/badge/version-v1.0-red) ![Base Model](https://img.shields.io/badge/version-Stable-Diffusion-2.1-blue) ![Subject](https://img.shields.io/badge/Subject-Hawkins-black)

## 📄 Project Description
This is a **Multi-Concept LoRA** trained on Stable Diffusion 2.1, designed to capture the iconic 1980s aesthetic and specific landmarks of the fictional town of **Hawkins, Indiana**.

The model is trained to recognize specific locations (like the Mall or the Lab) as well as the general atmospheric style of the *Stranger Things* universe, including the "Upside Down."

## 🗝️ Trigger Words & Concepts
This model uses a **Master Trigger** combined with **Sub-Triggers** to summon specific locations.

| Location / Concept | Trigger Word | Description |
| :--- | :--- | :--- |
| **General Vibe** | `Hawkins Indiana` | The main trigger. Use this for streets, houses, and the general 80s mood. |
| **Starcourt Mall** | `Starcourt Mall` | The neon-soaked, multi-level shopping mall (Season 3 aesthetic). |
| **Hawkins Lab** | `Hawkins Lab` | The brutalist, concrete government building (exterior). |
| **Downtown Hawkins** | `Downtown Hawkins` | The Heart Of hawkiks (Exterior) |
| **The Upside Down** | `The Upside down` | Adds dark blue/red lighting, floating spores, and vines. |

---

## 🔧 How to Use

1.  **Download** the `.safetensors` file.
2.  **Place** it in your `models/Lora` directory.
3.  **Prompting:** Use the trigger word `hawkins_indiana` + the specific location trigger you want.

### 🎨 Example Prompts

**1. Starcourt Mall (Neon Style)**
```text
hawkins indiana, starcourt mall, wide angle interior shot of a busy 1980s shopping mall, bright neon signs, checkered floor, crowd of teenagers, cinematic lighting, 4k, <lora:Hawkins_Indiana_v1:0.8>
