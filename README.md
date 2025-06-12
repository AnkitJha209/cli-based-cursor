# 🤖 CLI-Based Cursor — Agentic AI Terminal Assistant

A CLI-powered Agentic AI assistant that can analyze your query, plan its approach, take actions using tools like `runCommand` and `writeCode`, and build code projects step-by-step — all from your terminal.

---

## 🧠 What is Agentic AI?

Agentic AI is about giving AI the power not just to respond, but to **act** — by using tools, executing commands, and manipulating files — just like how a human brain uses hands to build things.

This project implements that idea in a CLI, making the AI a real-time assistant capable of helping you build apps by simply describing your intention.

---

## 🚀 Getting Started

Follow the steps below to set up and run the project locally.

---

### 📥 Step 1: Clone the Repository

```bash
git clone https://github.com/ankitjha209/cli-based-cursor.git
cd cli-based-cursor
```

---

### 📦 Step 2: Install Dependencies

Make sure you have [Node.js](https://nodejs.org/) installed (v18+ recommended).

Then, install the required dependencies using:

```bash
npm install
```

---

### 🔐 Step 3: Configure Environment Variables

Create a `.env` file in the root directory:

```bash
touch .env
```

```env
API_KEY=your_openai_api_key
```

---

### 🚦 Step 4: Run the Assistant

Start the CLI agent using the following command:

```bash
npm run dev
```

```bash
> write what you want to build here?
```
