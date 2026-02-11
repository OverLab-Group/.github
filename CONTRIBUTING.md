# 🤝 Contributing to OverLab Projects

First off, thanks for being here.  
OverLab is built by people like you — rebels, builders, and breakers who give a damn.  
Whether you’re fixing a typo, tackling a bug, or shipping a shiny new feature, **you** make this community what it is.

Please take a moment to read this guide. It’s not here to scare you off — it’s here to make sure we build great stuff, together.

---

## 🧭 Before You Start

### 1. Open an Issue First
**Every pull request must be backed by an issue.**  
This isn’t bureaucracy — it’s communication.

- Open a **detailed issue** describing what you want to do.
- Include **concrete code examples** if possible.
- Wait for a maintainer to acknowledge it before you start coding.

This saves you from spending hours on something that might not fit the project’s direction.

### 2. Use the Pull Request Template
When you’re ready to submit, use the **standard PR template**.  
It’s designed to capture all the information reviewers need — no guesswork.

---

## 🛠️ Pull Request Requirements

| Area | Requirement |
|------|-------------|
| **Code Quality** | Clean, simple, and self‑documenting. Follow **DRY** (Don’t Repeat Yourself) and **KISS** (Keep It Simple, Stupid). |
| **Malicious Code** | Absolutely **zero tolerance**. Any PR found to contain intentional backdoors, data exfiltration, or harmful logic will be rejected and the contributor banned. |
| **Cross‑Platform** | Must work on **all platforms and architectures listed in the repository’s README**. |
| **Testing** | Not mandatory, but **PRs with tests get priority review**. If you add tests, they must be meaningful. |
| **Benchmarking** | **Required for any performance‑sensitive change.** Provide before/after metrics (see below). |
| **Backward Compatibility** | Breaking changes require an **RFC** (see “Major & Minor Changes”). |

---

## 📊 Benchmark Metrics

When submitting a change that may affect performance, **measure these metrics before and after**:

- ✅ **Memory usage** (peak / average)
- ✅ **Execution speed** (operations per second, total runtime)
- ✅ **Startup time**
- ✅ **Code size** (lines of code, bundle size)
- ✅ **Output file size** (binary, distribution, etc.)
- ✅ **Bugs, warnings, errors** (compiler/linter output)
- ✅ **Optimization hints** (e.g., compiler remarks, clippy lints)
- ✅ **Number of files / directories** (if structural changes are involved)

Include a **summary table** in your PR comment.  
If you’re unsure how to benchmark, ask in the issue — we’ll help.

---

## 📦 Major Changes — RFC Required

If your change introduces a **breaking change (MAJOR)**, you **must** submit an RFC before writing code.

**RFC = Request for Comments**

1. Write a clear description of the change, its motivation, and its impact.
2. Send it to: **overlab.group@gmail.com**  
   Subject: `[RFC] Project Name - MAJOR`
3. Wait for the core team to review and respond (usually within 5 business days).

Minor features (backward‑compatible) do **not** require an RFC — just open an issue and discuss it with the community.  
But if you’re unsure whether your change is MAJOR or MINOR, ask first in the issue.

---

## 🧪 Code Style & Philosophy

- **Readability > cleverness** – Your code will be read more often than it’s written.
- **Consistency** – Follow the existing style of the project. We don’t enforce a single “perfect” style, but please don’t mix tabs and spaces.
- **Comments** – Explain *why*, not *what*. The code should already say what it does.
- **Commit messages** – Use clear, concise messages.  
  [Conventional Commits](https://www.conventionalcommits.org/) are welcome but not mandatory.

---

## 🔍 Review Process

- At least one **code owner** (`@JavadInteger` or `@OverLab-Group/overlab-dev-team`) must approve your PR.
- Reviews are constructive, not personal. We’re all here to learn.
- If changes are requested, don’t take it personally — iterate and push again.

---

## 🌍 Community & Conduct

We strive to be a welcoming, inclusive space.  
By contributing, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 🖤 Final Words

You’re not just writing code — you’re shaping the future of OverLab.  
Every issue, every PR, every line matters.

**Welcome to the movement.** 🚀
