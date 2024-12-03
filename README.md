# cjvm
A Version Manager for Cangjie Language. [Cangjie](https://cangjie-lang.cn)

Inspired by:
- Node Version Manager [nvm-sh/nvm](https://github.com/nvm-sh/nvm)
- Go Version Manager [moovweb/gvm](https://github.com/moovweb/gvm)
- Simple Python Version Management [pyenv/pyenv](https://github.com/pyenv/pyenv)
- ...

# Features
- Support multiple platforms:
  - Linux: **amd64** / **arm64**
  - macOS: **Intel** / **Apple Silicon**
- SDK downloaded from official website
  - currently only *0.53.13* available

# Installing
To install:
```bash
bash < <(curl -s -S -L https://raw.githubusercontent.com/ChaosJohn/cjvm/master/cjvm-installer)
```
> If you encounter network problem when accessing Github, switch to Gitcode instead. 
> ```bash
> export GIT_PROVIDER=gitcode.com
> bash < <(curl -s -S -L https://raw.gitcode.com/ChaosJohn/cjvm/raw/master/cjvm-installer)
> ```

# Usage
```bash
$ cjvm
Usage: cjvm [command]

Description: 
  A Version Manager for Cangjie Language

Commands:
  list    - list all remote versions (prints ✔ if installed)
  install - install specified version, e.g., `cjvm install 0.53.13`
  use     - activate specified version, e.g., `cjvm use 0.53.13`
```