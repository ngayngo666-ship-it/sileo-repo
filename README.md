# sileo-repo
Sileo-compatible APT repository for jailbreak packages.

This repository is now initialized as a minimal Sileo-compatible APT repository skeleton.

What is included:
- `Release` for APT metadata
- `Packages` for package indexing
- `index.html` for a simple landing page
- example instructions for adding packages and publishing the repo

Notes:
- Add actual `.deb` package files to a `debs/` directory and regenerate the package index before using this in a live jailbreak source.
- For Sileo, the repo must be hosted from a web server that serves the repository root over HTTPS.

Example repository layout:

```text
.
├── Release
├── Packages
├── index.html
├── debs/
│   └── your-package.deb
└── README.md
```
