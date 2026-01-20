![Build Status](https://img.shields.io/github/actions/workflow/status/sharmake121/cicdpipe/node.js.yml?branch=main)
![Node Version](https://img.shields.io/badge/node-%3E%3D16-green)
![License](https://img.shields.io/badge/license-MIT-blue)


# CI/CD Pipeline with Node.js, Jest, and GitHub Actions

A clean, production‑ready CI pipeline built with **Node.js**, **Jest**, and **GitHub Actions**.  
This project demonstrates automated testing, workflow orchestration, and modern DevOps practices suitable for real‑world engineering environments.

---

## 🚀 Features

- Automated CI pipeline using **GitHub Actions**
- Unit testing with **Jest**
- Dependency installation, caching, and test execution
- Clean Git workflow with proper branching and merge handling
- Recruiter‑friendly structure showcasing DevOps fundamentals

---

## 🛠️ Tech Stack

| Component        | Technology |
|------------------|------------|
| Language         | Node.js    |
| Testing Framework| Jest       |
| CI Engine        | GitHub Actions |
| Version Control  | Git & GitHub |

---

## 📦 Project Structure

---

## ⚙️ CI Pipeline Overview
## 🧩 CI/CD Architecture Diagram
       +---------------------+
       |     Developer       |
       |   (Commit / Push)   |
       +----------+----------+
                  |
                  v
       +---------------------+
       |   GitHub Actions    |
       |  CI Workflow Triggers|
       +----------+----------+
                  |
    +-------------+-------------+
    |                           |
    v                           v
    +---------------+          +------------------+ | Install Deps  |          |     Run Tests    | |  (npm install)|          |     (Jest)       | +-------+-------+          +--------+---------+ |                            | +-------------+--------------+ | v +---------------------+ |   Build Status     | |  (Pass / Fail)     | +---------------------+

This diagram shows the flow from commit → CI → test → status.

---

# 🟦 **3. Skills Demonstrated (Dubai/GCC Recruiter‑Optimized)**

This section highlights your DevOps capabilities in a way that aligns with UAE hiring expectations.

Add this near the bottom of your README:

```markdown
## 🧠 Skills Demonstrated

This project showcases practical DevOps and Cloud Engineering capabilities, including:

### 🔹 CI/CD & Automation
- Designing automated pipelines using GitHub Actions
- Implementing test‑driven workflows with Jest
- Ensuring code quality through automated validation
- Managing non‑fast‑forward merges and Git conflicts professionally

### 🔹 Git & Version Control
- Clean branching strategy (main + feature branches)
- Handling merge conflicts, rebasing, and history alignment
- Professional commit hygiene and repo structure

### 🔹 Node.js Engineering
- Modular application structure
- Automated dependency management
- Unit testing and test coverage

### 🔹 DevOps Mindset
- Pipeline reliability and repeatability
- Workflow orchestration
- Clear documentation and project visibility
- Recruiter‑friendly presentation for Dubai/GCC markets

### 🔹 Soft Skills (Highly valued in UAE)
- Attention to detail
- Ownership of technical workflows
- Ability to troubleshoot real‑world CI/CD issues
- Strong communication through documentation
The GitHub Actions workflow performs:

1. **Checkout** the repository  
2. **Set up Node.js**  
3. **Install dependencies**  
4. **Run Jest tests**  
5. **Report build status**  

This ensures every commit is validated automatically.

---

## 🧪 Running Tests Locally

```bash
npm install
npm test