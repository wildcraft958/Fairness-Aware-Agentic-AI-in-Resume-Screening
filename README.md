# 🧠 Project Setup: Data Analytics (Miniconda) + App Dev (pyenv + uv)

This project uses two separate environments for clean and focused workflows:

- 🧪 **Miniconda** — for data analytics and notebook work
- 🛠️ **pyenv + uv** — for app development and production code

...

## 🧰 Example Folder Structure

```
myproject/
├── .python-version
├── .venv/                  # uv venv
├── notebooks/              # Conda use
│   └── analysis.ipynb
├── app/                    # FastAPI, etc.
│   └── main.py
├── requirements.txt
├── environment.yml         # (Optional backup for conda)
└── README.md
```
