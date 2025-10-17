# DevOps CI Demo

This repository demonstrates a simple Continuous Integration (CI) setup using **GitHub Actions**.  
The project includes a basic HTML, CSS, and JavaScript calculator application. Click here to see a [Live Demo](https://jaffar-kazmi.github.io/DevOps-CI-Demo)

## Project Overview

The goal of this project is to show how to:
1. Create and manage feature branches in Git.
2. Set up a GitHub Actions workflow for CI.
3. Run automated tests or scripts on every push and pull request.
4. Merge tested code safely into the main branch.

## Features

- Simple calculator built with HTML, CSS, and JavaScript.
- Organized branch workflow (`main` and `feature-update`).
- GitHub Actions workflow to automatically run a CI job.
- Example of best practices for a small DevOps project.

## How It Works

1. When code is pushed or a pull request is created, GitHub Actions automatically triggers the CI workflow.
2. The workflow checks out the repository and runs a simple test or script.
3. If the workflow completes successfully, the changes can be safely merged into the main branch.

## Git Workflow

- `main` — Stable production-ready branch.
- `feature-update` — Development branch for new features or updates.

### Steps to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/Jaffar-Kazmi/DevOps-CI-Demo.git
   ```
2. Switch to the feature branch:
   ```
   git switch feature-update
   ```
3. Make your changes and push:
   ```
   git add .
   git commit -m "Update feature"
   git push origin feature-update
   
4. Open a Pull Request to merge into main.

