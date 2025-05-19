
# 🧠 Forward Propagation Exercise — Perceptron Simulation

This project is part of a take-home assignment for a Curriculum Engineer role at DeepLearning.AI.

It contains a Jupyter notebook where learners implement a simple forward propagation function using a single perceptron, including weight initialization and the sigmoid activation function.


---

## 🚀 How to Use This Repository

Follow these steps to run the Jupyter notebook inside a Docker container with JupyterLab.

### 🔁 Step 1: Clone the repository

```bash
git clone https://github.com/alejo1630/assessment_NN.git
cd assessment_NN
```

---

### 🐳 Step 2: Build the Docker image

```bash
docker build -t forward-propagation .
```

This will:
- Install Python
- Install all required libraries (`jupyterlab`, `numpy`, etc.)
- Copy the notebook into the Docker container

---

### ▶️ Step 3: Run the Docker container

```bash
docker run -p 8888:8888 forward-propagation
```

This starts a JupyterLab server. After a few seconds, you'll see a URL like this in the terminal:

```
http://127.0.0.1:8888/lab?token=YOUR_TOKEN
```

Copy and paste that link into your browser to open JupyterLab and access the notebook.

---

## 📌 Notes

- The default notebook should be visible at the root inside JupyterLab.
- The container does **not save changes** unless you map a local volume (optional).
- To stop the server, press `CTRL+C` in the terminal.

---

## 🧪 Requirements (already handled by Docker)

If you want to run the notebook locally without Docker, install the dependencies manually:

```bash
pip install -r requirements.txt
```


---

This project was assisted using ChatGPT. See `llm_chat_log.txt` for reference.
