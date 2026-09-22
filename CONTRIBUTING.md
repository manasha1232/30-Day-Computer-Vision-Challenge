# 🤝 Contributing to 30-Day Computer Vision Challenge

Thank you for your interest in contributing to the **30-Day Computer Vision Challenge**! We welcome open-source contributions from developers, researchers, and computer vision enthusiasts.

---

## 🚀 How to Contribute

### 1️⃣ Submit a Bug Fix or Enhancement
1. **Fork the Repository**: Click the `Fork` button at the top right of this repository.
2. **Clone your Fork**:
   ```bash
   git clone https://github.com/YOUR-USERNAME/30-Day-Computer-Vision-Challenge.git
   cd 30-Day-Computer-Vision-Challenge
   ```
3. **Create a Feature Branch**:
   ```bash
   git checkout -b feature/day-XX-enhancement
   ```
4. **Make & Test your Changes**: Ensure all Python scripts run cleanly and output structured JSON telemetry logs.
5. **Commit & Push**:
   ```bash
   git commit -m "feat: enhance Day XX landmark tracking smoothing"
   git push origin feature/day-XX-enhancement
   ```
6. **Open a Pull Request**: Submit your PR against the `main` branch.

---

## 🛠️ Code Style Guidelines

- Follow **PEP 8** conventions for Python code formatting.
- Ensure all public functions include clear docstrings.
- Avoid hardcoding absolute local path strings; use `os.path.join()` or relative directory parameters.
- Always cast NumPy types (`np.float32`, `np.int64`) to standard Python types (`float()`, `int()`) before serializing JSON logs.

---

## 📄 License
By contributing, you agree that your contributions will be licensed under the project's [MIT License](LICENSE).
