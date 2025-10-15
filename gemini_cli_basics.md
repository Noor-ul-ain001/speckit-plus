

### ⚙️ **1. Installation and Version Check**

* **Command:** `npm install -g @google/gemini-cli`
* **Check version:** `gemini -v` (e.g., `0.8.2`)
  **Purpose:** To install Gemini CLI globally and verify it’s correctly installed.

---

### 💻 **2. Launching Gemini CLI**

* **Command:** `gemini`
* **Prompts:** Choose a **theme** and an **authentication method** (Google login or API key).
  **Purpose:** To start the Gemini terminal client and authenticate your session for access.

---

### 🔐 **3. Authentication Options**

* **Google Login:** Free tier — 60 requests/minute, 1000 model requests/day.
* **API Key / Vertex AI:** For higher usage quotas.
  **Purpose:** To securely connect the CLI to your Google account or cloud project.

---

### 🧭 **4. Gemini CLI Interface Overview**

* **Bottom Status Bar Shows:**

  * Current folder
  * Active model (e.g., `gemini-2.5-pro`)
  * Remaining context
  * Sandbox status
    **Purpose:** To help monitor the environment, model, and session details while using Gemini.

---

### 🧰 **5. Basic CLI Commands**

* `/help` — View all commands and shortcuts.
* `/docs` — Opens Gemini CLI documentation.
* `/stats` — View session statistics (tokens, duration).
* `/quit` or **Ctrl+C twice** — Exit CLI.
  **Purpose:** To manage, learn, and exit the CLI easily.

---

### 🛠️ **6. Built-in Tools**

* **Command:** `/tools`
* **Function:** Lists tools available to Gemini (like `GoogleSearch`).
  **Purpose:** To show what internal tools Gemini can use and request permission to execute tasks.

---

### 🧑‍💻 **7. Shell Mode**

* **Command:** `!` — Toggles shell mode (e.g., `! pwd` to check directory).
* **Exit:** Press `ESC`.
  **Purpose:** To run terminal commands directly inside Gemini without leaving the interface.

---

### 📁 **8. Launch Gemini in a Project Folder**

* **Tip:** Start Gemini from the project folder you want to work in.
  Example: `/Users/romin/gemini-cli-projects/cli-series`
  **Purpose:** Gemini CLI is **project-based**; it uses your current directory context for file creation and operations.

---

### 🧩 **9. Example Task — Build a Python Flask App**

* **Prompt Example:**

  > “Create a Python Flask Application that shows live cricket scores using the RSS feed: [https://static.cricinfo.com/rss/livescores.xml”](https://static.cricinfo.com/rss/livescores.xml”)
* **Gemini Actions:**

  * Creates project folder
  * Writes necessary files (`app.py`, `index.html`)
  * Installs dependencies (`Flask`, `requests`, `feedparser`)
  * Starts Flask server
    **Purpose:** Demonstrates how Gemini CLI can **auto-generate code**, manage dependencies, and set up a local app.

---

### 🧾 **10. Example Flask Code Summary**

* **`app.py`** — Fetches RSS feed, parses it, and displays scores.
* **`index.html`** — Uses Bootstrap to list live match scores.
  **Purpose:** To show how Gemini automates end-to-end app creation, from backend logic to frontend display.

---

### 🚀 **11. Future Learning**

* **Next steps:**

  * Configure `settings.json`, `GEMINI.md`, etc.
  * Add more context and custom configurations.
  * Integrate MCP Servers or custom commands.
    **Purpose:** To expand Gemini CLI functionality for more advanced and personalized workflows.

---

### ✅ **In Summary**

| Key Area               | Purpose                                |
| ---------------------- | -------------------------------------- |
| Installation & Auth    | Set up Gemini CLI and connect securely |
| Interface Commands     | Navigate and manage your AI terminal   |
| Tools & Permissions    | Control what Gemini can do             |
| Shell Integration      | Run system commands directly           |
| Project-Based Workflow | Keep tasks organized within folders    |
| Code Generation        | Automate app and file creation         |
| Future Customization   | Extend Gemini CLI’s capabilities       |

---


