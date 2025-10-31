# 404README✨

![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-hotpink?style=for-the-badge)
![Python](https://img.shields.io/badge/Built%20with-Python-3776AB?style=for-the-badge&logo=python)
![CLI](https://img.shields.io/badge/Type-CLI-orange?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/404AB/404README?style=for-the-badge)


**A fast, emoji-and-badge powered README.md generator for projects and GitHub profiles. It features a huge banner, interactive menu, and non-interactive flags for automation.**

-------------------------------------

- ✨ Generates Project or Profile READMEs
- 🏷️ Auto-includes Shields.io badges and emojis
- 🎨 Big banner header with attribution
- 🧭 Interactive wizard with preview and save (asks for filename at the end)
- ⚙️ Non-interactive mode via flags

## 🚀 Quick Start
Interactive menu:

```
./404README/404README
```

Non-interactive examples:

```
# Project README
./404README/404README --type project --non-interactive \
  --title "My App" --description "Fast API" --author "You" \
  --repo you/my-app --techs "Python;Docker;PostgreSQL" -o README.md

# Profile README
./404README/404README --type profile --non-interactive \
  --name "404AB" --tagline "Builder" --github-user 404AB -o PROFILE.md
```

## 📦 Installation
See INSTALL.md for step-by-step instructions, or run locally without installing:

```
chmod +x ./404README/404README
./404README/404README
```

## 🧭 Menu Overview
- 1) Create Project README (wizard)
- 2) Create Profile README (wizard)
- 3) Change default output path
- 4) Preview last generated
- 5) Save last generated (you’ll be asked for the final filename)

## 🤝 Contributing
PRs and issues are welcome. Open a discussion to propose features or improvements.

## 🛡️ License ##
**MIT LICENSE**


---
Made with ❤️ using 404README
