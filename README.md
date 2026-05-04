# MJRManager

**MJRManager** is a powerful tool for working with JAR archives, featuring decompiler integration, source code editing, and Java class recompilation within a modern graphical interface.

[![Java](https://img.shields.io/badge/Java-21-orange)](https://www.oracle.com/java/technologies/downloads/)
[![JavaFX](https://img.shields.io/badge/JavaFX-21.0.6-blue)](https://openjfx.io/)

## 🚀 Features

- **📦 Archive Support** — Open JAR/WAR/EAR archives and explore their structure in a convenient tree view.
- **🔍 Decompilation** — Automatic `.class` file decompilation using the **CFR Decompiler**.
- **✏️ Source Editor** — Built-in code editor with Java syntax highlighting.
- **⚙️ Recompilation** — Dual compiler support:
  - **Eclipse JDT** (Soft mode) — Compiles even if the code has minor errors.
  - **javac** (Strict mode) — Standard Java compiler.
- **💾 Safe Saving** — Update JAR archives with automatic backup creation.
- **🔎 Quick Search** — Fast class lookup within the project tree.
- **📜 File History** — Recent files list for quick access.
- **🐛 Debug Console** — Integrated logger to monitor all background operations.
- **👁️ Bytecode Viewer** — Hex-dump view for `.class` files.

### ✨ Advanced Capabilities

- **🔍 Global Search** (`Ctrl+Shift+F`) — Full-text search across all classes in the JAR with Regex support.
- **📄 Manifest Editor** — Seamlessly edit `META-INF/MANIFEST.MF`.
- **➕ File Management** — Add or remove files and resources inside the archive.
- **📦 Export to Source** (`Ctrl+E`) — Decompile the entire archive into a structured source project.

## 🔧 Installation & Setup

### Clone the Repository

```bash
git clone [https://github.com/oladikezz/java-ui-decompiler-editor.git]
cd java-ui-decompiler-editor
