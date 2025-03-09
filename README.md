# 🚀 CrabNote

Welcome to CrabNote—a fun, experimental project exploring the idea of interactive computing with Rust! 🚀

We love Python, Jupyter, Google Colab, and other great interactive computing tools, but we also love Rust. While Python has an incredible ecosystem for data science and AI, Rust brings performance, safety, and modern tooling that could open new doors for interactive computing. So, why not see what happens when we mix Rust with a notebook-style environment?

## 🎯 What is CrabNote?

CrabNote is a web-based, interactive Rust notebook environment built with:

- 🦀 `Yew` – A frontend framework for building modern web apps in Rust.
- ⚡ `WASM-EVCXR` – A WebAssembly-powered EvCxR kernel for executing Rust code directly in the browser, eliminating the need for hefty cloud infrastructure.
- 📜 `.rsnb` (Rust Notebook) – A lightweight, Rust-native format for interactive coding.
  The goal is simple: make it easy and fun to write, run, and share Rust code in a notebook-style interface. _If it works well, great! If not, we still learn something cool along the way._

## 🌍 Why Are We Doing This?

We recognize that many developers have explored ways to integrate Rust with Jupyter Notebooks, such as through Anaconda setups and evcxr_jupyter kernels. These efforts are fantastic and have helped bring Rust into interactive computing spaces.

Our approach with CrabNote is different: we are starting with a Rust-first, browser-native environment powered by WebAssembly (WASM). Instead of relying on traditional Jupyter backends (no offense to Jupyter, we just want to try a different approach!), we want to explore what a truly Rust-powered notebook experience can look like.

1. **_Exploration_** – Python has built an amazing ecosystem for notebooks, but we’re curious to see how Rust could fit into this space.

2. **_Performance_** – Rust’s speed and memory safety could unlock new efficiencies in interactive computing.

3. **_WebAssembly Potential_** – Running Rust in-browser with `WASM` might provide a lightweight alternative to traditional server-based execution—browser today, IoT tomorrow?

4. **_AI/ML in Rust?_** – Libraries like `burn`, `tch-rs`, and `linfa` are evolving, and better tooling could make them more accessible.

5. **_For the Fun of It_** – No pressure, no expectations—just a fun project to learn, explore, and see where it takes us!

## 🛠️ What We're Building

- A Yew-based notebook UI with a clean, intuitive experience.
- WASM-EVCXR-powered execution to run Rust interactively in-browser.
- Local storage for Rust notebooks (.rsnb) so users can save and load their work.
- Potential AI/ML integration to experiment with Rust-based learning.

## 💡 Future Possibilities (No Pressure!)

Right now, CrabNote is just for fun. But who knows? Maybe it evolves into something even more helpful down the road. Or maybe we just have a good time experimenting and learning new things. Either way, it's a win!
For now? We build, we explore, and we see what happens.

## 🚀 Get Started: Your First Lap

1. Clone the repo: `git clone https://github.com/crabnote/crabnote.git`
2. Install Rust: `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
3. Build the frontend: `cd frontend/crabnote-ui && trunk serve`
4. Open `http://localhost:8080`—run “Hello, CrabNote!” in a code cell and join the fun!
5. Check out Issues on GitHub for quick tasks (e.g., “Add syntax highlighting to CodeCell”).

## 🦀 Community Vibes

- **GitHub**: `github.com/crabnote/crabnote`—open issues, PRs, or star us!
- **Discord**: Join our channel (link TBD)—chat, laugh, and brainstorm.
- **Newsletter**: Sign up at CrabNote.org for updates (coming soon!).

## 📜 License

CrabNote is open-source under the Apache-2.0 license—free to use, modify, and share, just like a road trip with friends!

## 🛠️ Want to Hack on This? If you love Rust, notebooks, or just messing around with new ideas, feel free to join in! 🚀
