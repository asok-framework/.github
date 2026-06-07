<p align="center">
  <img src="https://raw.githubusercontent.com/asok-framework/asok/main/icons/logo.svg" alt="Asok Framework Logo" width="400" />
</p>

<p align="center">
  <a href="https://github.com/asok-framework/asok/stargazers"><img src="https://img.shields.io/github/stars/asok-framework/asok?style=for-the-badge&color=ffd700" alt="GitHub Stars"></a>
  <a href="https://github.com/asok-framework/asok/blob/main/LICENSE"><img src="https://img.shields.io/github/license/asok-framework/asok?style=for-the-badge&color=4169e1" alt="License"></a>
  <a href="https://pypi.org/project/asok/"><img src="https://img.shields.io/pypi/v/asok?style=for-the-badge&color=228b22" alt="PyPI Version"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/python-3.10+-3776ab?style=for-the-badge&logo=python&logoColor=white" alt="Python Version"></a>
</p>

<p align="center">
  <strong>Asok</strong> is a cohesive, full-stack Python web framework designed for developer speed, elegant architecture, and security-conscious defaults. Built around a "zero-runtime-dependency" philosophy, it unifies server-side logic and client-side reactivity into a single, high-performance package, offering a streamlined development experience from the first line of code.
</p>

<p align="center">
  <a href="https://asok-framework.com/">
    <img src="https://img.shields.io/badge/Website-asok--framework.com-1abc9c?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://asok-framework.com/docs/01-getting-started">
    <img src="https://img.shields.io/badge/Docs-Quick%20Start-34495e?style=flat-square&logo=gitbook&logoColor=white" alt="Docs" />
  </a>
  <a href="https://discord.com/invite/aYYkuPT3qR">
    <img src="https://img.shields.io/badge/Discord-Join%20Chat-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" />
  </a>
  <a href="https://www.youtube.com/@asok-framework">
    <img src="https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
</p>

---

## ⚡ Key Highlights

* **Zero Runtime Dependencies**: No Werkzeug, no Jinja2, no SQLAlchemy. Built purely on top of the Python standard library—making it ultra-lightweight (~360KB), secure, and immune to supply chain attacks.
* **Islands Architecture**: Selective hydration of reactive client-side components combined with Static Site Generation (SSG) and Incremental Static Regeneration (ISR).
* **Native Reactive UI**: Build stateful, live-updated templates without Vue, React, or heavy NPM build pipelines.
* **Cohesive Ecosystem**: Complete with a built-in DB/ORM (SQLite, PG, MySQL), migration engine, automatic admin panel, OpenAPI auto-documentation, and vector search.

---

## 🚀 Quick Start (60 Seconds)

1. **Install Asok** :
   ```bash
   pip install asok
   ```
2. **Create a page controller** (`src/pages/page.py`) :
   ```python
   from asok import Request

   def render(request: Request):
       return "Hello, Asok! Zero dependencies, pure speed."
   ```
3. **Run in development** :
   ```bash
   asok dev
   ```

---

## 📁 Ecosystem Repositories

| Repository | Status | Purpose |
| :--- | :--- | :--- |
| 📦 **[asok](https://github.com/asok-framework/asok)** | [![PyPI](https://img.shields.io/pypi/v/asok?color=blue)](https://pypi.org/project/asok/) | Core framework engine (routing, DB/ORM, WSGI/ASGI server). |
| 📖 **[asok-docs](https://github.com/asok-framework/asok-docs)** | [![Documentation](https://img.shields.io/badge/docs-v0.4.0-success)](https://github.com/asok-framework/asok-docs) | Official handbook, cookbooks, and step-by-step guides. |
| 🔌 **[asok-lucide](https://github.com/codewithmpia/asok-lucide)** | [![PyPI](https://img.shields.io/pypi/v/asok-lucide?color=orange)](https://pypi.org/project/asok-lucide/) | Server-side SVG Lucide Icons renderer extension. |
| 💻 **[asok-vscode](https://github.com/asok-framework/asok-vscode)** | [![VS Code](https://img.shields.io/badge/VS%20Code-Extension-blueviolet)](https://github.com/asok-framework/asok-vscode) | Autocomplete, snippets, and routing helper extension. |
| 💡 **[asok-awesome](https://github.com/asok-framework/asok-awesome)** | [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/asok-framework/asok-awesome) | Showcase list of community plugins, tutorials, and templates. |
| 🌟 **[asok-examples](https://github.com/asok-framework/asok-examples)** | [![Examples](https://img.shields.io/badge/Examples-Ready--to--use-9b59b6)](https://github.com/asok-framework/asok-examples) | Boilerplates, templates, and starter projects. |

---

## 🤝 Join the Community

We are building a modern, independent Python web ecosystem.
* **Help others**: Answer questions in [Discussions](https://github.com/asok-framework/asok/discussions).
* **Contribute**: Read our [Contribution Guide](https://github.com/asok-framework/asok/blob/main/CONTRIBUTING.md) to start hacking on core features.
* **Build Extensions**: Read the [Extension Documentation](https://github.com/asok-framework/asok-docs/blob/main/docs/54-extension-system.md) and list your creations in [asok-awesome](https://github.com/asok-framework/asok-awesome)!
