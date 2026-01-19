<div align="center">
  <a href="#-english">🇺🇸 <b>English</b></a>
  <span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
  <a href="#-русский">🇷🇺 <b>Русский</b></a>
</div>

---

<div id="-english"></div>

# Andrey Urakov

> **Applied AI • ML Engineering • Local-First Systems • Reliability Mindset**

Student at UrFU (Applied AI, 2024–2028).

I build things that don't break in real-world scenarios. I focus on ML pipelines and systems with strict specifications and predictable behavior. No "it works on my machine" magic.

**Goals:** Studies, but I am open to interesting offers — from helping with a cool project to joining a startup (or launching one).

---

### ⚡ Principles
* **Reliability:** I like systems that recover from errors. State must be transparent, not magical.
* **Architecture First:** I design the data flow and structure before writing code. I prefer explicit logic over "figuring it out along the way".
* **Tech Coordination:** Coordinated development in small teams (4-5 people): code reviews, architectural decisions, and integration quality control.

---

### 🧰 Tech Stack
* **Languages:** Python (AsyncIO / Multiprocessing), SQL (SQLite)
* **ML/Data:** PyTorch, CNNs, LLM integrations, Data Annotation
* **Engineering:** Git, Linux (WSL environment), Event-driven, IPC/Queues

---

### 💻 The Lab (Hardware Constraints)
My environment for testing and local training. I optimize my code to run here.

| Resource | Spec |
| :--- | :--- |
| **GPU** | RTX 3060 Ti (8GB) |
| **RAM** | 32 GB DDR4 |
| **OS** | WSL2 / Ubuntu |

---

### 🛠 Selected Projects

#### [Dennett: Local-First AI Agent Hub](https://github.com/Andrey-Good/Dennett-AI-Agent-Hub)
*Role: Architecture Author & Tech Lead*
A system for autonomous agents that does not crash easily.
* **Architecture:** Designed a **Reconcile Loop** to restore state after restarts.
* **Safety:** Task scheduler uses **SQLite WAL** (atomic operations) to prevent data corruption.
* **Performance:** Hybrid storage — metadata in DB, large files in the file system.
* **UI:** Prototype (WIP); main logic is in the Backend/API.

#### [Mr. Mole: Melanoma Detection System](https://github.com/Andrey-Good/Mr.-Mole)
*Role: ML Engineer*
Image classification optimized for simple hardware.
* **Engineering:** Full cycle of CNN training. Converted to **ONNX** and quantized for mobile CPU/NPU.
* **Data:** Data augmentation and fixing class imbalance.
* **Result:** 1st place at UrFU project defense (98/100).

#### [RevAI: Review Summarizer Extension](https://github.com/Andrey-Good/RevAI)
*Role: Backend Lead*
Chrome Extension (Manifest v3) for content summary.
* **Optimization:** Implemented caching on the backend to save LLM tokens (money) on duplicate requests.
* **Core:** Custom DOM-parser to extract text from pages.

---

### 🧠 Engineering Mindset
1.  **Simplicity > Magic.** Explicit logic is better than complex hidden links.
2.  **Failure Modes.** Every feature starts with a question: "How will this break, and how do we fix it automatically?"
3.  **Pragmatism.** Performance is important, but correct data is more important.

---

### 📡 Contact
Please provide context when writing.

* **Telegram:** [@andrey_urakov_ml](https://t.me/andrey_urakov_ml)
* **Email:** urakov18.a@gmail.com

<br>
<br>
<br>
<br> ---

<div id="-русский"></div>

# Андрей Ураков

> **Applied AI • ML Engineering • Local-First Systems • Reliability Mindset**

Студент УрФУ (Прикладной ИИ, 2024–2028).

Делаю вещи, которые не разваливаются от первого же реального сценария. Строю ML-пайплайны и прикладные системы с упором на воспроизводимость, жесткие спецификации и предсказуемое поведение, а не на "вроде работает".

**Цели:** учёба, но открыт к любым интересным предложениям — от помощи в интересном проекте до участия/работы в стартапе (или совместного запуска).

---

### ⚡ Принципы работы
* **Reliability:** Люблю системы с восстановлением после сбоев и конкурентным выполнением задач. Состояние должно быть прозрачным, а не "магическим".
* **Architecture First:** Продумываю архитектуру и потоки данных до написания кода. Предпочитаю сначала спроектировать, потом кодить, чтобы не переписывать ядро трижды.
* **Tech Coordination:** Координировал разработку в небольших группах (4-5 человек): архитектурные решения, код-ревью и контроль качества интеграции.

---

### 🧰 Стек
* **Languages:** Python (AsyncIO / Multiprocessing), SQL (SQLite)
* **ML/Data:** PyTorch, CNNs, LLM integrations, Data Annotation
* **Engineering:** Git, Linux (WSL environment), Event-driven подход, IPC/Queues

---

### 💻 The Lab (Hardware Constraints)
Моя среда для тестов и локального обучения. Ориентир по ограничениям, под которые я оптимизирую обучение/инференс и систему в целом.

| Resource | Spec |
| :--- | :--- |
| **GPU** | RTX 3060 Ti (8GB) |
| **RAM** | 32 GB DDR4 |
| **OS** | WSL2 / Ubuntu |

---

### 🛠 Избранные проекты

#### [Dennett: Local-First AI Agent Hub](https://github.com/Andrey-Good/Dennett-AI-Agent-Hub)
*Role: Architecture Author & Tech Lead*
Система для автономных агентов, устойчивая к падениям.
* **Architecture:** Спроектировал **Reconcile Loop** для приведения системы к целевому состоянию при перезапуске.
* **Safety:** Планировщик задач на базе **SQLite WAL** (атомарные операции) для защиты от гонок данных и коррупции файлов.
* **Performance:** Гибридное хранение — метаданные в ACID БД, блобы в файловой системе.
* **UI:** Прототип интерфейса (WIP); основная функциональность — в backend/API.

#### [Mr. Mole: Melanoma Detection System](https://github.com/Andrey-Good/Mr.-Mole)
*Role: ML Engineer*
Классификация изображений, оптимизированная под слабое железо.
* **Engineering:** Полный цикл обучения CNN. Конвертация в **ONNX** и квантизация для запуска на мобильных CPU/NPU.
* **Data:** Пайплайн аугментации и устранение дисбаланса классов.
* **Result:** 1-е место на защите проектов УрФУ (98/100).

#### [RevAI: Review Summarizer Extension](https://github.com/Andrey-Good/RevAI)
*Role: Backend Lead*
Расширение (Manifest v3) для саммаризации контента.
* **Optimization:** Реализовал кэширование (хэширование запросов) на бэкенде, чтобы не жечь токены LLM на дубликаты.
* **Core:** Кастомный DOM-парсер для извлечения полезной нагрузки со страниц.

---

### 🧠 Инженерное мышление
1.  **Простота > Магия.** Явные инварианты лучше сложных неявных связей.
2.  **Failure Modes.** Любая фича начинается с вопроса: "Как это сломается и как мы это починим автоматически?"
3.  **Pragmatism.** Производительность важна, но корректность данных важнее.

---

### 📡 Контакт
Если пишешь по делу — сразу давай контекст.

* **Telegram:** [@andrey_urakov_ml](https://t.me/andrey_urakov_ml)
* **Email:** urakov18.a@gmail.com