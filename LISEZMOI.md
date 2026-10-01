# MUD en Dart — TP5

Dépôt de départ du TP5. L'énoncé complet est dans `TP5.pdf`.

```bash
dart pub get     # télécharge les dépendances (une seule fois)
dart run         # lance bin/mud.dart
dart test        # lance tous les tests du dossier test/
```

- `lib/`  : le code de la bibliothèque (vos classes `Box`, `Thing`…)
- `test/` : les tests (un fichier `*_test.dart` par classe)
- `bin/`  : le programme principal

## Travailler dans le navigateur (GitHub Codespaces)

Sans Dart sur votre ordinateur, ouvrez **votre** dépôt sur GitHub, puis
**Code** > **Codespaces** > **Create codespace on main**. Un VS Code
s'ouvre dans le navigateur, avec Dart déjà installé : `dart test`,
`dart run` et git fonctionnent comme au lycée.

**À la fin de chaque séance : push, puis Stop.**

1. `git status`, puis `git push` : ce qui n'est pas poussé ne reste que
   dans le codespace.
2. Arrêtez le codespace : `Ctrl+Maj+P` > **Codespaces: Stop Current
   Codespace**, ou sur <https://github.com/codespaces> : **…** >
   **Stop codespace**. Fermer l'onglet ne suffit pas : il continuerait de
   consommer votre temps gratuit pendant 30 minutes.
3. Une fois le travail poussé, vous pouvez aussi le supprimer (**…** >
   **Delete**) : il suffira d'en recréer un la prochaine fois.
