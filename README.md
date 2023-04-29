# Typos
Typography focused minimal Hugo theme

## Getting started

Prerequisites:
- [Install Hugo](https://gohugo.io/installation/)
- [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Website creation/theme installation:
1. Create new hugo site
```bash
hugo new site <site-name> --format yaml
```

2. Enter directory
```bash
cd <site-name>
```
3. Create new git repo
```bash
git init
```
4. Add theme as git submodule
```bash
git submodule add https://github.com/eliaserland/typos.git themes/typos
```
5. Set active theme in website config
```bash
echo "theme: typos" >> config.yaml
```