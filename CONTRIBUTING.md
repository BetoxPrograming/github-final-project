# 🤝 Contributing Guide

All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.

> [!IMPORTANT]
> Before contributing, please review the [Code of Conduct](CODE_OF_CONDUCT.md) and the project [License](LICENSE).  
> This repository is part of the **IBM Git and GitHub Basics** final project, so contributions should stay within the scope of a learning repository.

---

## ✅ General Contribution Rules

Keep contributions clear, focused, and easy to review.

Use simple language when writing documentation.

Avoid mixing unrelated changes in the same pull request.

Test your changes before submitting them.

Respect the existing project structure and naming style.

---

## 💡 Suggestions and Ideas

Suggestions are welcome when they improve clarity, documentation, code quality, or learning value.

When suggesting a change, explain:

| Field | What to include |
|---|---|
| Problem | What is unclear, broken, missing, or improvable |
| Suggestion | What change you propose |
| Reason | Why the change would improve the repository |

Example:

```text
Problem: The README does not explain the course context clearly.
Suggestion: Add a short student note at the top.
Reason: It helps visitors understand that this is a learning project.
```

---

## 🔀 Pull Request Guide

A pull request should represent one complete and reviewable change.

Use a clear title.

Explain what changed and why.

Mention if the change affects documentation, code, tests, or repository structure.

### Recommended Pull Request Title

```text
✨ feat(calculator): add simple interest calculator
```

### Recommended Pull Request Description

```text
This pull request adds a simple interest calculator using principal, annual rate of interest, and time period in years.

It also supports the IBM Git and GitHub Basics final project workflow by practicing branches, commits, pull requests, and merging changes into main.
```

> [!NOTE]
> A pull request can contain multiple commits, but all of them should belong to the same task or improvement.

---

## 🧾 Git Commit Message Style

Use short, clear, and descriptive commit messages.

### Recommended Format

```text
<emoji> <type>(<scope>): <action> <object>
```

### Structure

| Part | Meaning | Example |
|---|---|---|
| Emoji | Visual category | `📝` |
| Type | Kind of change | `docs` |
| Scope | File, module, or area changed | `readme` |
| Action + Object | What changed | `add course context` |

### Good Examples

```text
📝 docs(readme): add course project context
✨ feat(calculator): add simple interest calculator
🐛 fix(calculator): correct interest formula
```

---

## 🧩 Commit Types

| Emoji | Type | Use when... |
|---|---|---|
| 📝 | docs | Updating README, guides, comments, or documentation |
| ✨ | feat | Adding a new feature or functionality |
| 🐛 | fix | Fixing a bug or incorrect behavior |
| 🎨 | style | Improving format or structure without changing logic |
| ♻️ | refactor | Improving code without changing behavior |
| ✅ | test | Adding or updating tests |
| 🔥 | remove | Removing code, files, or unused content |
| 🔒 | security | Improving security or handling sensitive logic |
| ⬆️ | deps | Upgrading dependencies |
| ⬇️ | deps | Downgrading dependencies |
| 🧹 | chore | Repository maintenance, setup, or configuration |

---

## ✅ Commit Rules

Write commits in English.

Use present tense.

Use imperative mood.

Keep the first line under 72 characters.

Use lowercase commit types.

Use a clear scope, such as `readme`, `calculator`, `license`, `conduct`, or `contributing`.

Avoid vague messages.

### Avoid

```text
update
changes
final version
new file
fix stuff
```

### Prefer

```text
📝 docs(contributing): add commit message guide
✨ feat(calculator): add user input handling
🐛 fix(calculator): correct output formatting
```

---

## 📌 Extended Commit Description

Use an extended description when the commit needs more context.

A short commit title is enough for small or obvious changes.

Use an extended description when you need to explain what changed, why it changed, or how it improves the project.

### Recommended Format

```text
<emoji> <type>(<scope>): <action> <object>

Explain what changed.

Explain why the change was needed or how it improves the project.
```

### Example

```text
📝 docs(readme): add course project context

Add a short note explaining that this repository was created as part of the IBM Git and GitHub Basics final project.

This helps visitors understand that the repository is a learning project and that the base instructions were provided by the course platform.
```

> [!TIP]
> In the GitHub UI, the first field is the commit title. The larger field below it can be used for the extended description.

---

## 📝 Documentation Style

Documentation should be easy to scan, clear, and visually organized.

Use headings to separate sections.

Use short paragraphs.

Use tables when comparing options, rules, variables, or examples.

Use code blocks for commands, formulas, file names, and commit examples.

Use emojis only when they improve readability.

Use GitHub alerts for important notes.

### Recommended Alerts

```markdown
> [!NOTE]
> Use this for useful extra information.
```

```markdown
> [!TIP]
> Use this for practical recommendations.
```

```markdown
> [!IMPORTANT]
> Use this for key rules or required information.
```

```markdown
> [!WARNING]
> Use this for possible risks or mistakes.
```

---

## 🎨 Visual Style Rules

Keep the design clean.

Do not overload sections with too many emojis.

Use one emoji per heading when useful.

Use tables for quick scanning.

Use `---` to separate major sections.

Keep examples realistic and related to the repository.

Avoid decorative text that does not add information.

---

## 🧪 Testing Notes

Before opening a pull request, test your changes manually.

For calculator changes, include the values tested when relevant.

Example:

```text
p = 1000
t = 2
r = 5
simple interest = 100
```

> [!TIP]
> If the calculator logic changes, include the tested input and expected output in the pull request description.

---

## 📌 Additional Notes

This repository is mainly for learning and practice.

Clear documentation is valued as much as working code.

Small, focused improvements are better than large unclear changes.

When in doubt, explain the reason behind your change in the pull request description.
