
# **Create a Python Virtual Environment on Windows**

## **1. Make sure Python is installed**
Open **Command Prompt** or **PowerShell** and run:

```
python --version
```

If this doesn’t return a version, install Python from the Microsoft Store or python.org and check **“Add Python to PATH”** during installation.

---

## **2. Navigate to your project folder**
Example:

```
cd C:\Users\Tahmina\Documents\my_project
```

---

## **3. Create the virtual environment**
Use Python’s built‑in `venv` module:

```
python -m venv venv
```

This creates a folder named **venv** containing your isolated environment.

---

## **4. Activate the environment**
On Windows:

```
venv\Scripts\activate
```

Once activated, your terminal prompt will show:

```
(venv)
```

---

## **5. Install packages inside the environment**
Now anything you install stays isolated:

```
pip install requests
pip install langchain
pip install openai
```

---

## **6. Deactivate when you're done**
```
deactivate
```

---

# **Quick Tip for You, Tahmina**
Since you're working with LangChain, n8n, and Python agents, it’s smart to create a separate environment for each experiment. It keeps dependencies clean and avoids version conflicts—especially with AI libraries that update frequently.

If you want, I can also show you:
- how to create a **requirements.txt**
- how to use **conda** instead of venv
- how to set up a **virtual environment in VS Code** for smoother development

Just tell me what direction you want to take next.
