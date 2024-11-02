# generateur_eval_verbes_irreguliers
Generateur d'evaluation sur les verbes irréguliers

## Prérequis

Pour pouvoir l'utiliser, il vous faudra:

1. [Python](https://www.python.org/downloads/)
2. La bibliothèque [python-docx](https://python-docx.readthedocs.io/en/latest/user/install.html#install)
3. Un editeur de texte ([VSCode par exemple](https://code.visualstudio.com/))

## Télécharger le programme

Téléchargez le programme en cliquant sur `<> Code ▼` puis `Télécharger ZIP`

Un fois téléchargé, décompréssez-le.


## Générer l'évaluation

### Configuration

Pour configurer le programme, ouvrez le fichier `generateur.py` avec l'editeur de texte choisi et vous verrez trois variables importantes:

1. `nom_du_fichier_doc`
Vous l'aurez deviner, il s'agit du nom du fichier Word qui va être généré
2. `nombre_de_copies`
Le nombre de copies qui vont être généré (chaque copie sera différente, cela evite le triche)
3. `verbes`
Le nerf de la guerre, les verbes irréguliers.
Ils doivent être écrit suivant la syntaxe suivante :

```json
{
    "infinif": "cost",
    "preterit": "cost",
    "p.passe": "cost",
    "francais": "coûter"
},
```
> **Important : N'oubliez pas la virgule à la fin de chaque accolade fermé**

### Utilisation Windows

Sur le fichier `generateur.py`, faites `clique-droit`>`Exécuter avec python`.

Vous trouverez le fichier `.docx` généré dans le même dossier que le programme

### Utilisation GNU/Linux

Ouvrez votre terminal, rendez-vous dans le dossier où se trouve le programme lances la commande `python3 ./generateur.py`.

Vous trouverez le fichier `.docx` généré dans le même dossier que le programme