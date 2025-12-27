# 🛠️ FocusShell

**FocusShell** — A C-based command-line tool that lets users *forcefully shut down specified applications (e.g., games)* and block them from restarting for a set duration to help improve focus and productivity.

---

## 🚀 Overview

FocusShell is designed to help users stay focused by temporarily preventing distraction-causing software from running.  
Instead of waiting for “perfect” code, this repo shows your progress through iterative commits, clean structure, and clear intentions — exactly what interviewers and collaborators love to see.

---

## 🔍 Features

✔ Force terminate a process by name  
✔ Prevent the process from relaunching for a defined time period  
✔ Simple and intuitive CLI interface  
✔ Cross-platform goals (initial support targets macOS/Linux with Windows planned)  
✔ Iterative and extensible development structure

---

## 📦 Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/FocusShell.git
cd FocusShell
````

### Build with CMake (recommended)

```bash
mkdir build
cd build
cmake ..
make
```

### Or build with Makefile

```bash
make
```

---

## 🚀 Usage

Run the tool from your terminal:

```bash
# Example: force shutdown “game” and block for 60 minutes
./focusshell shut game 60
```

Expected output:

```
[FocusShell] Terminated process “game”
[FocusShell] Blocking restart for 60 minutes…
```

---

## 📁 Suggested Project Structure

```
FocusShell/
├── src/
│   ├── main.c
│   ├── cli.c
│   └── process.c
├── include/
│   ├── cli.h
│   └── process.h
├── tests/
├── README.md
├── LICENSE
├── .gitignore
├── Makefile
└── CMakeLists.txt
```

---

## 🧠 Current Status

🚧 **Work In Progress** — Early development stage.
This project is intentionally structured to show incremental progress through commits and milestones.

---

## 🗺️ Milestones / Roadmap

| Milestone                   | Status |
| --------------------------- | ------ |
| CLI parsing                 | ✅      |
| Basic process termination   | 🚧     |
| Cross-platform support      | ⬜      |
| Timer & scheduler module    | ⬜      |
| Persistent logging & config | ⬜      |
| Unit tests + CI             | ⬜      |

---

## 📌 Contributing

Contributions are welcome!
Please follow:

1. Fork the repository
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes with clear messages
4. Open a pull request describing your improvements

---

## 🧪 Testing

Add tests inside the `tests/` directory as the project grows.
Include unit tests, edge case checks, and CI integration when ready.

---

## 📄 License

This project is released under the **MIT License** — check the `LICENSE` file for details.
、
