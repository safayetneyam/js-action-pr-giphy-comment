# JS Action: PR Giphy Comment

Adds a random Giphy “thank you” GIF comment to pull requests.

---

## Setup

```bash
npm init -y
# Initialize a new Node.js project

npm i @actions/core@1.10.0
# Core toolkit for GitHub Actions

npm i @actions/github@5.1.1
# Access GitHub context and API

npm i @octokit/rest@20.0.1
# GitHub REST API client

npm i giphy-api@2.0.2
# Fetch random GIFs from Giphy

npm install @vercel/ncc@0.38.0
# Install NCC locally to bundle code

# or
npm install -g @vercel/ncc
# Install NCC globally

ncc build index.js -o dist
# Compile and bundle action into dist/
```

---

## Usage (Workflow)

```yaml
- name: KodeKloud Giphy PR Comment by Neyam
  uses: safayetneyam/js-action-pr-giphy-comment@1.0.0-alpha
```