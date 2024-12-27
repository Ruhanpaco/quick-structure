
# quick-structure

🚀 **A CLI tool for automating folder and file structures.**  
Perfect for Next.js projects, **quick-structure** saves time by automating repetitive scaffolding tasks, letting you focus on building great apps.

---

## ✨ Features

- **Predefined Templates**: Choose from ready-to-use templates for quick project setups.
- **Customizable Structures**: Automatically create folders, files, and components.
- **Interactive CLI**: Select templates and manage options interactively.
- **Progress Tracking**: See real-time progress and logs during creation.
- **Cleanup Option**: Easily delete generated structures if needed.

---

## 📦 Installation

Install **quick-structure** globally via npm:

```bash
npm install -g quick-structure
```

---

## 🚀 Usage

### **List Available Templates**
Display all available templates in a table format:

```bash
quick-structure list
```

### **Create a Structure from a Template**
Choose a template interactively:
```bash
quick-structure
```
or create a structure directly by template ID:
```bash
quick-structure structure [ID]
```

### **Delete Generated Structure**
After creating a structure, you can delete it interactively by confirming the prompt. Alternatively, delete the folders/files manually.

---

## 🛠 Example Workflow

1. List templates:
    ```bash
    quick-structure list
    ```
2. Select a template (e.g., ID 1):
    ```bash
    quick-structure structure 1
    ```
3. Follow the progress logs to see folders/files being created.
4. Optionally delete the generated structure if you don't need it.

---

## 📂 Example Output

### **Folder Structure Created with Template ID 1:**
```
src/
└── app/
    ├── about/
    │   └── page.tsx
    ├── contact/
    │   └── page.tsx
public/
└── assets/
    └── images/
API/
├── GET/
├── POST/
├── PUT/
└── DELETE/
```

---

## 💻 Commands

### `quick-structure list`
Lists all available templates.

### `quick-structure structure [ID]`
Generates a folder/file structure based on a template. Replace `[ID]` with the template ID.

### `quick-structure --version`
Displays the current version of the tool.

### `quick-structure --help` or `-h`
Shows a help message with all available commands.

---

## ❤️ Thank You

Thank you for using **quick-structure**! We’d love to hear your feedback and ideas for improvement.

- **NPM**: [https://www.npmjs.com/package/quick-structure](https://www.npmjs.com/package/quick-structure)
