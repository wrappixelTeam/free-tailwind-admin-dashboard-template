##  🤝  Contributing

We welcome contributions from the community to help improve the **Tailwind Admin Dashboard Template Free Version**. Whether it’s fixing bugs, adding new features, improving documentation, or sharing ideas — your input is appreciated!

### 🛠️ How to Contribute

Follow these simple steps to start contributing:

1. **Fork the Repository**  
   Click the **Fork** button on the top-right corner of this repo to create your own copy.

2. **Clone Your Fork**  
   Use the command below to clone your forked repository:
   ```bash
   git clone https://github.com/Tailwind-Admin/Tailwind-admin-free.git

3. **Create a New Branch**  
   Create a new branch to work on your feature or fix. This keeps your changes separate from the main branch:
   ```bash
   git checkout -b feature/your-feature-name

4. **Commit and Push Changes**  
   After making your changes, commit them with a meaningful message and push your branch to your fork:
   ```bash
   git commit -am "Add: Description of changes made"
   git push origin feature/your-feature-name

---

# Contributing to Tailwind Admin Templates

Thank you for your interest in contributing 🎉  
This repository contains Tailwind CSS–based Admin Templates for multiple frameworks.

---

## 📦 Templates in This Repository

- Angular – `tailwind-admin-angular-free`
- HTML – `tailwind-admin-html-free`
- Next.js – `tailwind-admin-nextjs-free`
- React – `tailwind-admin-reactjs-free`
- Vue.js – `tailwind-admin-vuejs-free`

Each template is an independent project.

---

## 📁 Folder Structure (Very Important)
```
Tailwind-Admin
├── tailwind-admin-angular-free/
│ └── packages/
├── tailwind-admin-html-free/
│ └── packages/
├── tailwind-admin-nextjs-free/
│ └── packages/
├── tailwind-admin-reactjs-free/
│ └── packages/
├── tailwind-admin-vuejs-free/
│ └── packages/
├── .github/
├── README.md
├── CONTRIBUTING.md
├── LICENSE.md
└── SECURITY.md
```

---

## ❗ Do NOT Change the Folder Structure

- Do not rename, move, or delete any template folder
- Do not remove, rename, or restructure the `packages/` folder
- The `packages/` folder contains core template code
- Each template must remain standalone

Pull requests that change the folder structure may be rejected.

---

## 🧑‍💻 Working Inside `packages/`

All code changes must be made inside the `packages/` folder of the relevant template.

### Allowed
- Bug fixes
- UI / UX improvements
- Tailwind CSS refinements
- Adding or improving components
- Safe refactoring

### Not Allowed
- Moving code outside `packages/`
- Sharing code between templates
- Introducing root-level shared packages

---

## 🎯 Framework-Specific Contributions

You only need to work on one template at a time.

Example:
```
tailwind-admin-reactjs-free/packages/
```

You do NOT need to update all templates in one pull request.

---

## 🔄 Cross-Framework Changes (Optional)

If a change is generic, you may apply it to multiple templates — but this is optional.

If you update only one template, please mention it clearly in the PR description.

---

## 🚀 Getting Started

Fork the repository and clone it locally.

```bash
git clone https://github.com/your-username/repo-name.git
cd repo-name
```

Install dependencies only for the template you are working on.

## 🎨 Tailwind CSS Guidelines
- Prefer Tailwind utility classes
- Avoid inline styles
- Keep spacing, typography, and colors consistent

## 📝 Commit Message Guidelines

feat(react): add collapsible sidebar
fix(nextjs): fix navbar hydration issue
docs: update contributing guide

## 📦 Pull Request Guidelines

Before submitting a PR:
- Test changes locally
- Keep PRs focused
- Do not change folder structure
- Add screenshots for UI changes if possible


PR Title Format

```csharp
[Framework] Short description
```

Example:

```csharp
[React] Improve dashboard spacing
```

## 🐛 Reporting Issues

Include:
- Template name
- Steps to reproduce
- Expected behavior
- Screenshots if applicable

## ❤️ Thank You

We appreciate your contributions and support 🚀

---