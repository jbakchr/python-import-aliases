<p align="center">
  <img src="https://img.shields.io/github/stars/jbakchr/python-import-aliases?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/jbakchr/python-import-aliases?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Made%20with%E2%9D%A4%EF%B8%8F-in%20Denmark-red?style=for-the-badge" />
</p>

# python-import-aliases

_**A concise, community‑maintained reference of the most common and widely accepted Python import aliases (e.g., `np`, `pd`, `plt`). Quick to browse, easy to search, and organized by domain for fast lookup.**_

## 📑 Table of Contents

1. [Why Python Import Aliases Matter](#--why-python-import-aliases-matter)
2. [Goal of This Repository](#-goal-of-this-repository)
3. [Contents](#-contents)
4. [Example: Scientific Computing Aliases](#️-example-scientific-computing-aliases)
5. [Why Use Aliases?](#-why-use-aliases)
6. [When Not to Use Aliases](#️-when-not-to-use-aliases)
7. [Contributing](#-contributing)
8. [License](#-license)
9. [Acknowledgements](#-acknowledgements)

## 👉 💡 Why Python Import Aliases Matter

Python developers frequently use short, conventional aliases when importing popular libraries—for example:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

These conventions:

- improve readability
- reduce typing
- match the broader Python ecosystem’s style

Many of them are widely recognized across:

- tutorials
- documentation
- data science communities

This repository collects, organizes, and documents these aliases in one central, easy‑to‑reference place.

## 🎯 Goal of This Repository

- Provide a canonical, community-maintained reference for Python alias conventions.
- Help beginners understand which aliases are standard vs. uncommon.
- Improve code readability and consistency across teams and projects.
- Serve as an “alias encyclopedia” for Python libraries of all kinds.

This project is not prescriptive. Some developers prefer full module names, and many discussions highlight that excessive alias usage can reduce readability.

Our purpose is simply to **document what the community already does**, not to dictate style.

## 📚 Contents

Aliases are organized by domain:

- **Scientific Computing**<br>
  NumPy, pandas, matplotlib, SciPy, seaborn, xarray, etc.

- **Machine Learning & AI**<br>
  TensorFlow, PyTorch, scikit‑learn, Theano, JAX, etc.

- **Data Engineering & Big Data**<br>
  PySpark, Dask, Polars, etc.

- **Web Development**<br>
  Flask, Django, FastAPI, Requests, etc.

- **Miscellaneous & Utilities**<br>
  Standard library modules, general-purpose libraries, small tools.

Each category lives in its own markdown file under the aliases/ directory.

## 🗂️ Example: Scientific Computing Aliases

A taste of what you’ll find inside:

| **Package**       | **Alias** | **Import Example**              |
| ----------------- | --------- | ------------------------------- |
| NumPy             | np        | import numpy as np              |
| pandas            | pd        | import pandas as pd             |
| matplotlib.pyplot | plt       | import matplotlib.pyplot as plt |
| seaborn           | sns       | import seaborn as sns           |
| xarray            | xr        | import xarray as xr             |
| plotly.express    | px        | import plotly.express as px     |

Many of these appear frequently in community-driven alias lists.

## 🧠 Why Use Aliases?

Common reasons include:

- **Shorter code**<br>
  Using np.array() is cleaner than numpy.array().<br>
  Common alias examples include packages like numpy → np, pandas → pd.

- **Community standards**<br>
  Many libraries have widely accepted conventional aliases.

- **Consistency**<br>
  Predictable naming across projects helps new contributors onboard faster.

- **Readability for heavy‑use modules**<br>
  For frequently used namespaces, aliases reduce clutter.

## ⚠️ When Not to Use Aliases

Aliases aren’t always the best choice:

- If a module is rarely used
- When the alias isn’t well-known or obvious
- If it makes the code harder for newcomers to understand
- In teams that enforce a “full namespace” policy

Multiple community discussions raise concerns about over-aliasing making code harder to follow. [reddit.com]

Use aliases thoughtfully.

## 🤝 Contributing

We welcome contributions!

If you'd like to add or correct aliases:

- Fork the repo
- Add or modify entries in aliases/
- Submit a pull request

Guidelines:

- Only add aliases that are in real-world use
- Mark non-standard aliases clearly
- Add references where applicable (tutorials, documentation, etc.)

## 📄 License

This project is released under the MIT License.

Feel free to use, copy, and adapt this for your own projects.

## ⭐ Acknowledgements

Thanks to the Python community, tutorials, articles, and discussions that inspired this repository. The idea of collecting alias conventions is supported by numerous posts and guides that highlight common module abbreviations and best practices.
