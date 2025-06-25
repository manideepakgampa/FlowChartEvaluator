# 🔄 theGnaN – Flowchart Evaluator

> 🎯 Visual logic. Validated.  
> A powerful drag-and-drop flowchart evaluator designed to help learners map logic, validate algorithms, and build programming fundamentals — visually.

---

## 🚀 What is this?

The **Flowchart Evaluator** is a key module of the [`VteacH`](https://github.com/theGnaNtechHub/VteacH) learning platform by **theGnaN**. It allows students to build logic flows using visual blocks, simulate the logic, detect errors, and (eventually) convert flowcharts into pseudo-code — bridging the gap between thinking and programming.

### 🌟 Core Highlights

- 🧩 **Drag-and-drop flowchart builder**
- 🛠️ **Real-time logic validation**
- ⚠️ **Flow & structure error detection**
- 🔄 (Phase 2) **Convert to pseudo-code**
- 🎓 Beginner-friendly and educational

---

## 🧑‍💻 Who is it for?

- Students learning algorithms visually
- Teachers who teach flowcharts before code
- Institutes integrating logic-first programming
- Anyone who loves to think in blocks before writing code

---

## 🛠️ Tech Stack

| Layer        | Technology                                  |
| ------------ | ------------------------------------------- |
| Frontend     | React.js, Tailwind CSS                      |
| Logic Engine | Custom-built Flow Validator (JS)            |
| Canvas UI    | React Flow / Konva / Custom (modular setup) |

> 🧠 Logic checking is fully frontend-driven for the MVP. Future versions will sync with pseudo-code via backend API (FastAPI).

## 📐 Key Functionalities

| Feature                  | Status      |
| ------------------------ | ----------- |
| Drag-and-drop nodes      | ✅ Done     |
| Connectors (edges/paths) | ✅ Done     |
| Error validation         | ✅ MVP      |
| Save/load diagrams       | 🔲 Coming   |
| Convert to pseudo-code   | 🔲 Phase 2  |
| Real-time sync           | 🔲 Optional |
| Zoom / Pan               | ✅ Basic    |
| Export flowchart         | 🔲 Optional |

---

## 📥 Getting Started

### 1. Clone the Repo

```
git clone https://github.com/manideepakgampa/FlowChartEvaluator.git
cd FlowChartEvaluator
```

2. Install Dependencies

```
npm install
```

3. Start the Dev Server

```
npm run dev
```

App will run locally at http://localhost:5173 (default Vite port).

🧪 Testing (WIP)
Testing architecture for:

Node placement validation

Flow loop detection

Execution simulation

```
npm run test
```

✨ Future Enhancements

- Convert flowchart to structured pseudo-code

- Add more logical shapes (Input, Output, Subroutine)

- User sessions & saving to DB

- Multi-step debugging mode

🧠 Educational Focus

- This module helps students:

- Understand flow before writing code

- Spot errors in logic visually

- Build confidence before syntax

- Ideal for early-stage programming learners in schools, colleges, and bootcamps.

🤝 Contributing
We welcome improvements, ideas, and pull requests!

🔍 Found a bug? Open an issue

🧠 Want to improve logic detection?

🎨 Suggest UI/UX tweaks? Fork and submit PRs

New? Check our CONTRIBUTING guide (coming soon)

📄 License
MIT License — open to fork, remix, and expand with attribution.

🔗 Project Links
👨‍🏫 Part Of theGnaN : [`VteacH`](https://github.com/theGnaNtechHub/VteacH)

🌐 [`theGnaN Official Website`](https://www.thegnan.in)

💬 Feedback? Open an Issue

🙌 Credits
Crafted with care by the theGnaN team.
Maintained by: @manideepakgampa and contributors.
