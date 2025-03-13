---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: "text-center"
highlighter: shiki
lineNumbers: true
info: |
  ## Modern Developer Tools
  Essential tools for productive development
drawings:
  persist: false
css: unocss
---

# Modern Developer Tools

Essential tools for the productive developer

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

---
layout: default
---

# Oh My Zsh

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Framework for managing Zsh configuration
- Extensive plugin ecosystem
- Theme support
- Easy customization

## Popular Plugins

- git
- docker
- kubectl
- npm
- python

</div>

---
layout: default
---

# Powerlevel10k

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Fast and feature-rich theme
- Customizable prompts
- Git status integration
- Command execution time
- Directory depth
- Background jobs

## Configuration

```bash
ZSH_THEME="powerlevel10k/powerlevel10k"
```

</div>

---
layout: default
---

# fzf

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Key Features

- Fuzzy finder for command line
- Fast and intuitive search
- Integration with shell history
- File and directory navigation

## Key Bindings

```bash
# History search
ctrl-r

# File search
ctrl-t

# Directory navigation
alt-c
```

</div>

---
layout: default
---

# Zoxide

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Smart directory jumper
- Learning algorithm
- Fast navigation
- Interactive mode

## Usage

```bash
z project    # Jump to project
zi          # Interactive selection
z -         # Go back
z -l        # List all directories
```

</div>

---
layout: default
---

# The Fuck

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Corrects your previous command
- Multiple correction rules
- Custom rules support
- Language agnostic

## Usage

```bash
$ apt-get install python
# Permission denied
$ fuck
sudo apt-get install python
```

</div>

---
layout: default
---

# kubectx & kubens

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Fast context switching
- Namespace management
- Command completion
- History tracking

## Usage

```bash
# Context switching
kubectx minikube
kubectx prod

# Namespace switching
kubens default
kubens kube-system
```

</div>

---
layout: default
---

# Bat

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Syntax highlighting
- Git integration
- Line numbers
- Paging support
- Multiple themes

## Usage

```bash
bat script.sh
bat --style=numbers,changes,header file.txt
bat --theme=TwoDark file.py
```

</div>

---
layout: default
---

# Eza

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Modern ls replacement
- Color coding
- Git status integration
- Extended attributes
- Tree view

## Usage

```bash
eza --long --git
eza --tree --level=2
eza --icons
```

</div>

---
layout: default
---

# Ripgrep

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Lightning fast search
- Respects .gitignore
- Type filtering
- Context lines
- Hidden files support

## Usage

```bash
rg "pattern" --type rust
rg -i "pattern" --context 2
rg --files-with-matches "pattern"
```

</div>

---
layout: default
---

# Tldr

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Practical examples
- Community-driven
- Concise format
- Multiple languages
- Offline support

## Usage

```bash
tldr tar
tldr docker
tldr --update
```

</div>

---
layout: default
---

# Devbox

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Features

- Nix-based development environments
- Reproducible builds
- Package management
- Project isolation
- Cross-platform

## Usage

```bash
devbox init
devbox add nodejs
devbox shell
devbox run start
```

</div>

---
layout: default
---

# Git Tools

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Essential Aliases

```bash
gco = git checkout
gst = git status
gaa = git add --all
gcm = git commit -m
gpl = git pull
gps = git push
glog = git log --oneline
gdiff = git diff
```

## Popular Tools

- GitLens (VS Code)
- Git Graph
- GitKraken
- SourceTree

</div>

---
layout: default
---

# Docker Tools

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Essential Aliases

```bash
dps = docker ps
dex = docker exec -it
dc = docker-compose
dcup = docker-compose up -d
dcdown = docker-compose down
dclogs = docker-compose logs -f
dcrebuild = docker-compose up -d --build
```

## Popular Tools

- Portainer
- Docker Desktop
- Lens (K8s IDE)
- Rancher Desktop

</div>

---
layout: default
---

# Terraform Tools

<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Essential Aliases

```bash
tf = terraform
tfi = terraform init
tfp = terraform plan
tfa = terraform apply
tfd = terraform destroy
```

## Best Practices

- State management
- Module organization
- Variable management
- Workspace usage

## Related Tools

- AWS CLI
- Azure CLI
- GCloud SDK
- Pulumi

</div>

---
layout: end
---

# Thank You!

<div class="grid grid-cols-2 gap-8">
<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Resources

- [Slidev Documentation](https://sli.dev)
- [GitHub Repository](https://github.com/slidevjs/slidev)
- [Modern CLI Tools](https://github.com/topics/cli-tools)

</div>
<div class="p-4 rounded-lg bg-gray-800 bg-opacity-50">

## Stay Connected

- Follow for updates
- Share your tools
- Contribute to the community

</div>
</div>
