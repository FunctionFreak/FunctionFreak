<h1 align="center">Hi, I'm Ashish 👋</h1>

<p align="center">
  <b>Founder of <a href="https://github.com/ComputerUseAgent/AutoCua">AutoCua</a></b> · AI Engineer · London, UK
</p>

<p align="center">
  <a href="https://github.com/ComputerUseAgent/AutoCua"><img src="https://img.shields.io/github/stars/ComputerUseAgent/AutoCua?style=for-the-badge&logo=github&label=AutoCua%20stars&color=8b5cf6" alt="AutoCua stars"></a>
  <a href="https://pypi.org/project/AutoCua/"><img src="https://img.shields.io/pypi/v/AutoCua?style=for-the-badge&logo=pypi&logoColor=white&label=pip%20install%20AutoCua&color=3776ab" alt="PyPI"></a>
  <a href="https://www.linkedin.com/in/ashish-yadav-b33020193"><img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

### About me

- 🚀 Building **AutoCua**, an open-source computer-use agent: one agent that drives every screen you own
- 🧠 AI engineer by day, working on agentic systems for testing automation
- 🔬 Training a small, locally run model for GUI grounding so agents need fewer cloud calls
- 📚 Mostly self-taught, through research papers, YouTube and shipping things. MSc Computer Science, University of East London
- 🇮🇳 → 🇬🇧 Grew up in an army family across India, now based in London

---

## AutoCua — one agent, every computer

> **A team of AI agents that works your Mac, Windows, Linux, phone and browser.**
> It sees the screen, clicks, types, browses and writes the code too.

```bash
pip install AutoCua
```

```python
from AutoCua.agent_launcher import run_agent

run_agent(mode="web use", provider="openrouter", model="gemini-3.8-flash",
          task="Open wikipedia.org and summarise today's featured article.")
```

One string, `mode`, decides what the agent drives. Everything else stays the same.

| Surface | What it does | Platforms |
|---|---|---|
| 🖥️ **Computer use** | Any desktop app, with real mouse and keyboard input | macOS · Windows · Linux |
| 🌐 **Web use** | Your own Chrome through the AutoCua extension, so it keeps your logins | Any host with Chrome |
| 💻 **Shell use** | A coding agent in a real terminal that sends sub-agents to explore codebases | macOS · Windows · Linux |
| 📱 **iPhone & iPad** | iOS Simulator or a real device, over USB or Wi-Fi | macOS host |
| 🤖 **Android** | Emulator or a real phone, over USB or Wi-Fi | macOS · Windows · Linux |
| 🔗 **Daisy chain** | The desktop agent hands phone work to iOS and Android sub-agents in the same run | All |
| 💬 **Remote control** | Send it tasks from Telegram | All |

### Why it holds up on real software

- **No pixel guessing.** The model picks numbered elements from a view that fuses the OS accessibility tree with OCR. A number it never saw is rejected before anything moves.
- **Real input, no debugging port.** Events go in at the OS input layer, with a kernel driver on Windows that can even answer UAC prompts.
- **A team, not one loop.** A parent agent owns the screen and delegates to coder, browser, iOS and Android agents, with read-only "minions" exploring code in parallel.
- **Runs in parallel.** `extra_tasks=[...]` runs many tasks at once: a tab, simulator or emulator each.
- **No context wall.** A compression agent summarises mid-run so long tasks finish.
- **No telemetry.** Nothing leaves your machine except calls to the model provider you chose.
- **Bring any model.** Anthropic, OpenRouter, Gemini, Vertex AI, Groq and more.
- **Built in Python + Rust.** The browser and Android agents are pure Rust.

👉 **[See the repo](https://github.com/ComputerUseAgent/AutoCua)** · MIT licensed

---

### What I'm working on now

- 🔁 **Self-learning runs**: AutoCua remembers the steps of a task after the first run and replays them, aiming to cut most LLM calls
- 📊 **Benchmarks**: publishing the web agent's results on Online-Mind2Web
- 🧪 **Local model**: distilling a small vision-language model for on-device GUI grounding

---

### Tech I use

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat-square&logo=anthropic&logoColor=white)

---

### Let's talk

Open to collaborators, contributors and fellow founders building in computer use.
📧 aashish16yadav@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/ashish-yadav-b33020193)

<p align="center"><i>⭐ If AutoCua saves you a few clicks, a star helps a lot.</i></p>
