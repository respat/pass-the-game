# 🌑 Project: DARKROOM (Godot Dev Challenge)

**Project: DARKROOM** is a collaborative game development experiment using **Godot 4.x**. Two developers take turns building a single game in 5-day sprints, following a strict "Zero Communication" policy.

---

## 📜 The Core Concept
The goal is to see how a game evolves when two different visions clash without verbal or written coordination. The only way to influence the project is through **code** and **daily mechanical challenges**.

---

## 🛠 Rules of Engagement

### 1. Sprint Cycles
* **Duration:** 5-day sprints. One person is the **Developer**, the other is the **Mentor**.
* **Zero Communication:** Zero discussion about the game. No Slacks, no calls, no spoilers.
* **Handover:** At the end of Day 5, the Developer pushes the code. The next person pulls and starts Day 1.

### 2. Daily Challenges
* Every morning, the Mentor writes a mandatory task in `CHALLENGES.txt`.
* **The Bad Luck Factor:** If a challenge asks for something already implemented, the Developer must refine, polish, or add a twist to the existing mechanic.
* **Complexity Rule:** If a task is marked as a **"2-day challenge"**, the following day's task must be a minor one (implementable under 30 minutes).

### 3. Development Constraints
* **English Only:** All code, node names, variables, and comments must be in **English**.
* **No AI Code Gen:** No full scripts from AI. AI is only allowed for bug fixing or refining existing logic.
* **Shader Exception:** Shaders are complex! AI generation for shader code is permitted.
* **Frankenstein Method:** Most code should be "frankensteined" from tutorials and documentation.
* **Clean Hierarchy:** Every Node must be named properly in English (e.g., `PlayerController`).

### 4. Visuals (Art & Assets)
* **Hand-drawn Placeholders:** Main entities (characters, key objects) must use **hand-drawn placeholders** created by the Developer for the final push of each sprint.
* **Generic Assets:** Basic UI elements (buttons, progress bars) can use default Godot nodes.

### 5. Documentation & Logging
* **Work Log:** Update `work_log.txt` with the date and hours spent.
* **Strict No-Spoiler Policy:** Do NOT describe features in the work log or commit messages. Keep it vague (e.g., `2026.01.22 | 2.5 hours`).

### 6. Special Mechanics
* **The [LOCK] Rule:** Once per sprint, a Developer can mark one script as `[LOCK]`. The next person cannot delete or fundamentally refactor that file.
* **Emergency Break:** If the project is technically broken, a single 5-minute technical sync is allowed.

---

## 📂 Repository Structure
* `/project_files`: The Godot project folder.
* `CHALLENGES.txt`: The current and past daily tasks.
* `work_log.txt`: Time tracking (Date | Hours).

---

> **"In the Darkroom, we don't talk. We code."**
