# 📝 TaskTracker: Simple Task Management Tool

![Python Badge](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🌟 About TaskTracker

TaskTracker is a lightweight and user-friendly Command Line Interface (CLI) tool for managing your daily tasks. It helps you create your to-do list, mark tasks as complete, and view pending tasks. Designed for simplicity and efficiency, so you can focus on your important work without wasting time.

---

## ✨ Key Features

* **Add New Tasks:** Easily add tasks to your list.
* **Mark Tasks as Done:** Mark completed tasks as "Done."
* **View Task List:** See all pending or completed tasks.
* **Delete Tasks:** Remove tasks from your list.
* **Persistent Storage:** Your tasks are saved in a local file so they remain available even after closing the program.

---

## 🚀 How to Install

To install TaskTracker, ensure **Python 3.9** or higher is installed on your system.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/TaskTracker.git](https://github.com/YourUsername/TaskTracker.git)
    cd TaskTracker
    ```

2.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    (If you have a `requirements.txt` file. Otherwise, skip this step.)

---

## 💡 How to Use

After installation, you can run TaskTracker with the following commands:

* **Add a Task:**
    ```bash
    python main.py add "Buy groceries"
    ```

* **View All Tasks:**
    ```bash
    python main.py list
    ```
    Or only pending tasks:
    ```bash
    python main.py list --pending
    ```

* **Mark Task as Done (using row number):**
    ```bash
    python main.py complete 1
    ```
    (Number 1 refers to the first task in the `list` output.)

* **Delete Task (using row number):**
    ```bash
    python main.py delete 2
    ```

---

## 🤝 Contributing

We welcome any contributions to improve TaskTracker! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your changes (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push your changes to your fork's main branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## ✉️ Contact Us

If you have any questions or suggestions, feel free to contact me via email at [your.email@example.com](mailto:your.email@example.com).
