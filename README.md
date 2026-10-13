# Buddy

Buddy t'aide à progresser sur tes objectifs du semestre, depuis la barre de menus de ton Mac. Il remarque ce que tu fais (agenda, Slack, GitHub, Claude Code), le range dans tes objectifs, et c'est toi qui valides.

## Installer

Ouvre le Terminal (⌘ Espace, puis « Terminal ») et colle cette ligne :

```
curl -fsSL https://github.com/simoncdna/buddy-releases/releases/latest/download/install.sh | zsh
```

Buddy s'installe dans le dossier Applications de ton compte et s'ouvre. Pour le mettre à jour, relance la même ligne.

## Ce qu'il te faut

- macOS 26 (Tahoe) ou plus récent ;
- un abonnement Claude qui inclut Claude Code (le plan gratuit ne suffit pas) : au premier lancement, Buddy te propose de connecter ton compte, dans ton navigateur ;
- tes objectifs du semestre, dans Elevo.

## Désinstaller

```
rm -rf ~/Applications/Buddy.app ~/.local/bin/buddy
```

Tes données restent dans le dossier `~/Buddy` : supprime-le pour tout effacer.
