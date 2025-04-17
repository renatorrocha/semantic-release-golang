# semantic-release-golang

This is a showcase repository demonstrating how to set up semantic-release in a Go project.

Although semantic-release is commonly used in JavaScript/TypeScript projects, it works just as well with other languages — this repo shows how to adapt it for Go with minimal setup (using bun btw).

💡 What's inside?
  A basic Go project

semantic-release configuration using .releaserc.json

A package.json just to support the tool (no Node.js code needed)

GitHub Actions workflow to:

* Analyze commit messages

* Automatically bump the version (vX.Y.Z)

* Generate changelogs

* Create and publish GitHub releases

🚀 Why?
To fully automate the release process:

* No manual versioning

* No hand-written changelogs

Just follow Conventional Commits, and everything else happens automagically ✨
