# AI Campus Hub

AI Campus Hub is a full-stack campus application available through an Emergent preview deployment.

---

## Table of Contents

- [Live Demo](#live-demo)
- [Repository Status](#repository-status)
- [Recommended Structure](#recommended-structure)
- [Git Commands](#git-commands)
- [Adding the Real Source](#adding-the-real-source)
- [Security](#security)
- [Project Link](#project-link)

---

## Live Demo

https://ai-campus-hub-26.preview.emergentagent.com/

## Repository Status

This repository package is prepared for GitHub, but the original application source code was not exposed by the public preview URL. The preview currently serves a JavaScript application shell, so the exact frontend/backend source cannot be recovered reliably from the URL alone.

**Do not treat this repository as a source-code clone of the live application.** Export the project source from Emergent and place it into this repository before pushing the complete application.

## Recommended structure

```text
AI-Campus-Hub/
├── README.md
├── .gitignore
├── LICENSE
├── frontend/
├── backend/
├── public/
├── src/
├── docs/
└── screenshots/
```

## Git commands

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/spjayesh2005-ui/AI-Campus-Hub.git
git push -u origin main
```

## Adding the real source

1. Export/download the source code from the Emergent project.
2. Extract it into this repository.
3. Keep the existing README and `.gitignore` or merge them with the exported project files.
4. Check that no API keys, passwords, tokens, or environment secrets are included.
5. Run the project locally.
6. Commit and push the complete source.

## Security

Never commit `.env` files containing real credentials.

## Project link

Live application:  
https://ai-campus-hub-26.preview.emergentagent.com/
