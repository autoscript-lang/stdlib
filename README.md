# AutoScript Standard Library & Registry

Welcome to the official repository for the **AutoScript Standard Library**. This repository serves as a monorepo containing all modules for the AutoScript language.

## 📦 Using Libraries

You can search for and install any library in this repository directly from the AutoScript CLI.

### Search for a library
```bash
autoscript search std
```

### Install a library
```bash
autoscript install std/math
autoscript install std/fs
```

### Automatic Dependency Restore
If your project has an `autos.json` file, you can restore all dependencies at once:
```bash
autoscript build
```

---

## 📚 Available Libraries

| Package Name | File Name | Description |
|--------------|-----------|-------------|
| `std/ai` | `AutosAI.autos` | Mock AI assistance and test generation. |
| `std/collections` | `AutosCollections.autos` | Advanced data structures (Stacks, Queues). |
| `std/console` | `AutosConsole.autos` | Rich console output and formatting. |
| `std/database` | `AutosDatabase.autos` | Unified Async DB access (SQLite, Postgres). |
| `std/fs` | `AutosFS.autos` | Async File System operations. |
| `std/gui` | `AutosGUI.autos` | Native WebView bridge for UI applications. |
| `std/json` | `AutosJson.autos` | High-performance JSON serialization. |
| `std/math` | `AutosMath.autos` | Complex mathematical functions and constants. |
| `std/ml` | `AutosML.autos` | Native bindings for Tensors and ONNX models. |
| `std/orm` | `AutosORM.autos` | Multi-backend Object-Relational Mapper. |
| `std/security` | `AutosSecurity.autos` | Modern Cryptography (AES, RSA, PBKDF2). |
| `std/web` | `AutosWeb.autos` | High-performance HTTP/Web server framework. |
| ... and many more. | | |

---
