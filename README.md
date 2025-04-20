## How to Contribute

Thank you for your interest in contributing! Follow the steps below to fork the repository, make changes, and submit a Pull Request (PR).

---

### 1. Fork the Repository
Go to [this repository](https://github.com/hasan-mehedii/Graph-Algorithms) and click the **Fork** button in the top right. This creates a copy under your GitHub account.

---

### 2. Clone Your Fork
Open a terminal and run:
```bash
git clone https://github.com/hasan-mehedii/Graph-Algorithms.git
cd Graph-Algorithms 
```

---

### 3. Add the Original Repository as a Remote
This allows you to keep your fork in sync with the original project.
```bash
git remote add upstream https://github.com/hasan-mehedii/Graph-Algorithms.git
```

To verify the remotes:
```bash
git remote -v
```

---

### 4. Create a New Branch
It's a good practice to make changes in a separate branch.
```bash
git checkout -b feature-branch-name
```
Replace `feature-branch-name` with something meaningful like `fix-typo`, `add-login-page`, etc.

---

### 5. Make Your Changes
Make the necessary changes in your code editor or IDE.

---

### 6. Stage and Commit the Changes
```bash
git add .
git commit -m "Describe the changes you made"
```

Use a clear and concise commit message.

---

### 7. Push Changes to Your Fork
```bash
git push origin feature-branch-name
```

---

### 8. Create a Pull Request
1. Go to your fork on GitHub.
2. Click on the **"Compare & pull request"** button.
3. Add a title and detailed description of your changes.
4. Click **"Create pull request"** to submit.

---

### Optional: Keep Your Fork Updated
To sync your fork with the original repository:
```bash
git checkout main
git pull upstream main
git push origin main
```

---

**Thanks again for contributing!**
