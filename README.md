# DAA Algorithm Visualizer

A collaborative project for visualizing Design and Analysis of Algorithms (DAA) concepts. Teams contribute algorithm visualizations as HTML files, which are hosted on GitHub Pages after their pull requests are accepted.

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Contribution Guidelines](#contribution-guidelines)
- [File Structure](#file-structure)
- [Creating Your Algorithm Visualizer](#creating-your-algorithm-visualizer)
- [Submitting Your Work](#submitting-your-work)
- [GitHub Pages Hosting](#github-pages-hosting)
- [License](#license)

---

## 📖 About the Project

This repository serves as a platform for students to create and share algorithm visualizations as part of their DAA assignment. Each team creates an HTML file that demonstrates the working of a specific algorithm through interactive visualizations.

---

## 🛠️ Prerequisites

Before you begin, ensure you have the following:

1. **Git** installed on your local machine
   - Download from: [https://git-scm.com/downloads](https://git-scm.com/downloads)
   
2. **GitHub Account**
   - Create one at: [https://github.com/join](https://github.com/join)

3. **Text Editor/IDE**
   - Recommended: VS Code, Sublime Text, or any editor of your choice

4. **Basic Knowledge of:**
   - HTML, CSS, JavaScript
   - Git commands
   - The algorithm you want to visualize

---

## 🚀 Getting Started

### Step 1: Fork the Repository

1. Navigate to the repository: [https://github.com/1AdityaX/DAA_Algo_visualizer](https://github.com/1AdityaX/DAA_Algo_visualizer)
2. Click the **"Fork"** button in the top-right corner
3. This creates a copy of the repository in your GitHub account

### Step 2: Clone Your Forked Repository

```bash
git clone https://github.com/<your-username>/DAA_Algo_visualizer.git
```

Replace `<your-username>` with your GitHub username.

### Step 3: Navigate to the Project Directory

```bash
cd DAA_Algo_visualizer
```

### Step 4: Create a New Branch

```bash
git checkout -b <algorithm-name>-visualizer
```

Example:
```bash
git checkout -b bubble-sort-visualizer
```

---

## 📝 Contribution Guidelines

### Naming Conventions

- Use **lowercase** letters for file names
- Use **hyphens** (-) to separate words
- File names should be descriptive of the algorithm

**Examples:**
- `bubble-sort.html`
- `binary-search.html`
- `dijkstra-algorithm.html`
- `merge-sort.html`

### Code Quality Standards

1. Write clean, readable, and well-commented code
2. Use meaningful variable and function names
3. Ensure your visualizer is responsive and works on different screen sizes
4. Test your HTML file in multiple browsers (Chrome, Firefox, Edge)

---

## 📁 File Structure

Your HTML file should follow this structure:

```
DAA_Algo_visualizer/
├── README.md
├── LICENSE
├── index.html (main landing page - managed by repository maintainer)
├── bubble-sort.html (your contribution)
├── quick-sort.html (another team's contribution)
└── ... (other algorithm visualizers)
```

> **Note:** The `index.html` file serves as the main landing page and will be managed by the repository maintainer. Contributors only need to add their individual algorithm HTML files.

---

### Requirements for Your Visualizer

1. **Title Section:** Clear title with algorithm name
2. **Description:** Brief explanation of the algorithm
3. **Visualization Area:** Interactive canvas/div to show the algorithm working
4. **Controls:** Buttons to start, pause, reset, and adjust speed
5. **Team Information:** Names of team members
6. **Time & Space Complexity:** Display the algorithm's complexity

---

## 📤 Submitting Your Work

### Step 1: Add Your Changes

```bash
git add <your-algorithm-name>.html
```

Or add all changes:
```bash
git add .
```

### Step 2: Commit Your Changes

```bash
git commit -m "Add [Algorithm Name] visualizer"
```

Example:
```bash
git commit -m "Add Bubble Sort visualizer"
```

### Step 3: Push to Your Fork

```bash
git push origin <your-branch-name>
```

Example:
```bash
git push origin bubble-sort-visualizer
```

### Step 4: Create a Pull Request

1. Go to your forked repository on GitHub
2. Click **"Compare & pull request"** button
3. Ensure the base repository is `1AdityaX/DAA_Algo_visualizer` and base branch is `main`
4. Fill in the pull request template:
   - **Title:** Add [Algorithm Name] Visualizer
   - **Description:** 
     - Brief description of the algorithm
     - Team name and members
     - Any special features or instructions
5. Click **"Create pull request"**

### Step 5: Wait for Review

- The repository maintainer will review your pull request
- Make any requested changes if needed
- Once approved, your PR will be merged

---

## 🌍 GitHub Pages Hosting

### How It Works

1. Once your pull request is accepted and merged to the `main` branch
2. GitHub Pages automatically deploys the changes
3. Your visualizer becomes accessible at:
   ```
   https://1adityax.github.io/DAA_Algo_visualizer/<your-file-name>.html
   ```

### Example URLs

- Bubble Sort: `https://1adityax.github.io/DAA_Algo_visualizer/bubble-sort.html`
- Binary Search: `https://1adityax.github.io/DAA_Algo_visualizer/binary-search.html`
- Quick Sort: `https://1adityax.github.io/DAA_Algo_visualizer/quick-sort.html`

---

## ❓ Troubleshooting

### Common Issues

1. **Merge Conflicts**
   - Pull latest changes from upstream before pushing:
     ```bash
     git remote add upstream https://github.com/1AdityaX/DAA_Algo_visualizer.git
     git fetch upstream
     git merge upstream/main
     ```

2. **Fork Not Updated**
   - Sync your fork with the original repository using the steps above

3. **HTML Not Rendering**
   - Ensure all file paths are relative
   - Check for syntax errors in your HTML/CSS/JavaScript

---

## 📞 Contact

For any questions or issues, please:
1. Open an issue in the repository
2. Contact the repository maintainer

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- All contributing teams and students
- DAA Course Instructors
- Open source community for inspiration

---

**Happy Coding! 🎉**
