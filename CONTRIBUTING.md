# 👐 Contributing to python-import-aliases

Thank you for your interest in contributing! 💚

This project aims to build a clear, community‑maintained reference of commonly used Python import aliases — from well‑established conventions like `import numpy as np` to domain‑specific abbreviations used across scientific computing, machine learning, data engineering, and more.

Some community discussions highlight the prevalence of common aliases such as those used for pandas and numpy, showing the value of documenting such conventions.

Additionally, community threads list popular abbreviations and emphasize the importance of avoiding confusion and maintaining readability.

Contributions of all kinds are welcome — new aliases, improvements to documentation, fixes, or suggestions.

Please read the guidelines below before submitting a pull request.

## 📌 How to Contribute

### 1. Fork the repository

Click the Fork button on GitHub to create your own copy of the project.

### 2. Clone your fork

```bash
git clone https://github.com/<your-username>/python-import-aliases.git
cd python-import-aliases
```

### 3. Create a new branch

```bash
git checkout -b add-new-alias
```

Use a descriptive name that reflects your contribution.

## 🧩 Adding or Updating Aliases

### ✔ Where to add aliases

Aliases should be added to the appropriate file in the `aliases/` directory:

- scientific.md
- machine-learning.md
- data-engineering.md
- web-frameworks.md
- miscellaneous.md

If your alias doesn’t clearly belong in an existing category, feel free to place it in miscellaneous.md.

## 📏 Required Format for Alias Entries

Each alias entry should follow this structure:

````
## Library name → `alias`

**Import**
```python
import library_name as xyz
```

**Notes (optional)**
Notes about why alias is commonly used with links to relevant documentation or examples

````

## ✔ Alias Entry Examples

### pandas

````
## pandas → `pd`

**Import**
```python
  import pandas as pd
```

**Notes**
A widely recognized community convention used across tutorials and documentation.

````

## 🧹 Contribution Guidelines

Please review these before opening a PR:

### ✔ Only add aliases that are actually used in real‑world code

This repo documents _existing_ conventions, not theoretical ones.

### ✔ Avoid overly obscure or personal aliases

For example:  
❌ `import numpy as n` (**not** widely used, **not** meaningful)

### ✔ Add notes when an alias is not universally recognized

This helps readers understand context and avoid misuse.

### ✔ Keep entries alphabetically arranged within each category

This makes browsing easier.

### ✔ Maintain consistent formatting

Follow the template shown above.

## 🧪 Testing + Validation

Since this repository is documentation‑based:

- No automated testing is required
- But please **preview your Markdown** before submitting
- Ensure headings, code blocks, and lists render properly
- Validate that all links (if any) work

## 📩 Submitting a Pull Request

Once your changes are ready:

```bash
git commit -m "Add alias for <library>"
git push origin <branch-name>
```

Then go to your fork on GitHub and open a **Pull Request**.

Your PR should include:

- A clear title (e.g., “Add alias for xarray (xr)”)
- A brief description of what you changed and why
- Any references (official docs, community usage examples)

## 🗣️ Code of Conduct

Please be respectful and constructive.

Opinions on aliasing vary across the community — discussions are welcome, but keep them kind and collaborative.

## 🙌 Thank You

Every contribution helps make this resource more useful for the entire Python community.

Thanks for taking the time to contribute and help others write cleaner, more consistent, and more readable code!

If you have questions, feel free to open an issue or start a discussion anytime.
