# Comment afficher le site web localement

Prérequis : Ruby, RubyGems, Jekyll

## Windows

on peut utilisé chocolatey pour installer Jekyll

dans le terminal en mode administrateur, exécuter la commande suivante pour installer chocolatey

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

puis installer Jekyll

```bash
choco install jekyll
```

## Mac

Installer Jekyll avec brew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install jekyll
```

# Lancer le site web

```bash
bundle exec jekyll serve
```
