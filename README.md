# Docklens
Container/Docker image vulnerability scanner

A Python CLI tool that:
- Takes a Docker image
- Analyses the installed packages
- Compares them with a CVE database
- Classifies vulnerabilities by severity
- Suggests patches/upgrades
- Displays everything in a clean terminal menu

# Environnement
install devbox
```
curl -fsSL https://get.jetify.com/devbox | bash
```
run devbox
```
devbox shell
```

# Pre-commit Hooks
With every new commit, verification hooks will be executed. To bypass them, run the following command: 
```
git commit -m "what my commit does blablabla" --no-verify
```
### Pre-commit tools
**black**: code auto-formatting
-> https://github.com/psf/black

**isort**: automatic sorting of imports
-> https://pycqa.github.io/isort/index.html

**ruff**: error detection
-> https://docs.astral.sh/ruff/

**mypy**: type checking

## License

This project is licensed under a Non-Commercial license.
Commercial use (including SaaS, resale, or paid services) requires prior written permission from the author.
See LICENSE for details.
