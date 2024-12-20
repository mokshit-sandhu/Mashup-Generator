## Project Setup Instructions

Follow these steps to set up and run the project on your local machine.

### 1️⃣ **Clone the Repository**
Run the following command to clone the repository to your local machine:
```bash
git clone https://github.com/mokshit-sandhu/Image-Generator
```

### 2️⃣ **Navigate to the Project Directory**
Change your current directory to the root of the project:
```bash
cd <repository-folder>
```
> Replace `<repository-folder>` with the name of the folder created by `git clone`.

### 3️⃣ **Install Required Packages**
Install all the necessary dependencies listed in the `requirements.txt` file:
```bash
pip install -r requirements.txt
```
This will install all the required libraries and packages for the project.

### 4️⃣ **Run the Application**
Run the application using the following command:
```bash
python app.py
```
This will start the application, and you should see output indicating that the application is running.

---

### ⚠️ **Prerequisites**
- Make sure you have **Python 3.x** installed on your machine.
- It is recommended to use a **virtual environment** to avoid package conflicts. You can create one using the following commands:
  ```bash
  python -m venv venv  # Create a virtual environment
  source venv/bin/activate  # Activate it on macOS/Linux
  .\venv\Scripts\activate  # Activate it on Windows
  ```

---

### 📚 **Helpful Commands**
- **Check installed packages**:
  ```bash
  pip list
  ```
- **Update packages**:
  ```bash
  pip install --upgrade -r requirements.txt
  ```

---
