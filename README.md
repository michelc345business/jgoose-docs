# JGOOSE - Documento de Instruções

Install Python via asdf

```
pip install mkdocs
pip install mkdocs-material
mkdocs new jgoose-docs
cd jgoose-docs

git init

git remote add origin https://github.com/michelc345business/jgoose-docs
git add .
git commit -m "2026-10-15"
git log
git push origin main
mkdocs gh-deploy
```