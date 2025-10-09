# 🧩 JacLang + Python Development Setup in GitHub Codespaces

This repository provides a ready-to-use **GitHub Codespace environment**
for developing with **JacLang** and **Python** --- including virtual
environment setup, automatic formatting, linting, build/run tasks, and
debug configuration.

------------------------------------------------------------------------

## 🚀 Features

  Feature                        Description
  ------------------------------ ---------------------------------------
  🐍 Python 3.12                 Runs in a prebuilt dev container
  🧠 JacLang + byLLM             Installed automatically in venv
  ⚙️ Auto venv activation        Activated in every Codespace terminal
  🧼 Code formatting & linting   `black`, `flake8`, and Jac formatter
  ⚡ One-click build & run       Via VS Code Tasks
  🪄 Debug integration           Run Jac scripts from the Debug panel

## 📁 Folder Structure

    jaclang-project/
    │
    ├── .devcontainer/
    │   └── devcontainer.json
    │
    ├── .vscode/
    │   ├── tasks.json
    │   └── launch.json
    │
    ├── guess_game.jac
  

------------------------------------------------------------------------

## 🧹 Troubleshooting

  ---------------------------------------------------------------------------------------------
  Problem                           Solution
  --------------------------------- -----------------------------------------------------------
  `jac: command not found`          pip install jaclang

  `byLLM` not found                 pip install byLLM
    ---------------------------------------------------------------------------------------------


## 🪄 Credits

-   **JacLang:** <https://github.com/Jaseci-Labs/jaclang>\

------------------------------------------------------------------------

## ✅ Summary

You now have a fully configured **JacLang + Python development
environment** in GitHub Codespaces: - Auto-activated virtual
environment\
- JacLang build/run tasks\
- Debugging support\
- Auto-formatting and linting\
- Works seamlessly in the cloud ☁️
