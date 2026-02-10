## Cachydots

**Cachydots** regroupe mes fichiers de configuration (dotfiles) pour mon environnement CachyOS, basé sur le compositeur `niri` et le shell `noctalia`.  
Chaque sous-dossier contient la configuration d’une application ou d’un composant précis.

### Structure du dépôt

- **`niri/`** : configuration principale du compositeur `niri`.
  - `config.kdl` : configuration de base.
  - `noctalia.kdl` : intégration avec le shell Noctalia (thème, invites, etc.).
  - `cfg/` : fichiers KDL séparés par rôle (`animation.kdl`, `autostart.kdl`, `display.kdl`, `input.kdl`, `keybinds.kdl`, `layout.kdl`, `misc.kdl`, `rules.kdl`) pour une configuration modulaire.

- **`noctalia/`** : configuration du shell Noctalia.
  - `colors.json` : palette de couleurs.
  - `plugins.json` : plugins activés.
  - `settings.json` : options générales du shell.

- **`fish/`** : configuration du shell `fish`.
  - `config.fish` : configuration principale (alias, fonctions, etc.).
  - `fish_variables` : variables et état interne de fish.

- **`alacritty/`** : configuration du terminal `alacritty`.
  - `alacritty.toml` : configuration principale.
  - `themes/` : thèmes, dont `noctalia.toml` pour adapter Alacritty au thème Noctalia.

- **`kitty/`** : thèmes pour le terminal `kitty`.
  - `themes/noctalia.conf` : thème Noctalia pour kitty.

- **`btop/`** : thème pour le moniteur système `btop`.
  - `themes/noctalia.theme` : thème Noctalia.

- **`helix/`** : configuration du thème pour l’éditeur `helix`.
  - `themes/noctalia.toml` : thème Noctalia pour helix.

- **`micro/`** : configuration de l’éditeur `micro`.
  - `bindings.json` : raccourcis personnalisés.
  - `settings.json` : options de l’éditeur.
  - `colorschemes/` : jeux de couleurs (catppuccin, etc.).
  - `syntax/` : fichiers de définition de syntaxe (copiés/adaptés depuis le projet micro).

- **`gtk-3.0/`** et **`gtk-4.0/`** : configuration des thèmes GTK.
  - `noctalia.css` / `gtk.css` : styles pour intégrer l’interface graphique au thème Noctalia.
  - `settings.ini` : paramètres GTK (thème, icônes, police, etc.).

- **`Kvantum/`** : configuration du moteur de thèmes Qt Kvantum.
  - `kvantum.kvconfig` : profil Kvantum à utiliser.

- **`qt5ct/`** et **`qt6ct/`** : configuration pour les applications Qt5 et Qt6.
  - `colors/noctalia.conf` : palette Noctalia pour Qt.
  - `qt5ct.conf` : configuration générale de qt5ct.

- **`yazi/`** : configuration du gestionnaire de fichiers en terminal `yazi`.
  - `theme.toml` : thème global.
  - `flavors/noctalia.yazi/` : variante de thème Noctalia pour yazi.

- **`zed/`** : thèmes pour l’éditeur `Zed`.
  - `themes/noctalia.json` : thème Noctalia pour Zed.

### Utilisation

- **Sauvegarde personnelle** : ce dépôt me sert à versionner et sauvegarder mes dotfiles.
- **Réutilisation** : vous pouvez cloner ce dépôt et copier les dossiers ou fichiers qui vous intéressent dans vos propres répertoires de configuration (en adaptant les chemins propres à votre système).
- **Inspiration** : libre à vous de reprendre les idées de structure, de thèmes ou de séparation des fichiers.
