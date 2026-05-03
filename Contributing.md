# Contributing to PocketCloud

First off, thanks for taking the time to contribute! 🎉

---

## How to contribute

### Reporting bugs

1. Check if the bug is already reported in [Issues](https://github.com/Tpskevin13/PocketCloud/issues)
2. If not, open a new issue with:
   - A clear title
   - Steps to reproduce the bug
   - Expected vs actual behavior
   - Your Android version and device model
   - Logcat output if possible

### Suggesting features

1. Open an issue with the label `enhancement`
2. Describe the feature and why it would be useful
3. If possible, include mockups or examples

### Contributing code

1. Fork the repository
2. Clone your fork:
git clone https://github.com/YOUR_USERNAME/PocketCloud.git
3. Create a new branch:
   git checkout -b feature/your-feature-name
4. Make your changes
5. Test on a real Android device (min SDK 31)
6. 6. Commit with a clear message:
   git commit -m "Add: your feature description"
7. Push to your fork:
   git push origin feature/your-feature-name
8. Open a Pull Request against the `main` branch

---

## Code style

- Follow existing Kotlin code conventions
- Use Jetpack Compose for all UI
- Keep clean architecture: data → domain → presentation
- All network calls must run on Dispatchers.IO
- Comment complex logic

---

## Questions?

Open an issue or reach out via [GitHub](https://github.com/Tpskevin13/PocketCloud).

Thank you for helping make PocketCloud better ☁️
