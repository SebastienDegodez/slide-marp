# Bienvenue dans le projet Slide-MARP

Ce projet contient les diapositives pour une présentation utilisant MARP, un outil de création de diapositives en Markdown.

## Comment utiliser ce projet

1. Clonez ce dépôt sur votre machine locale.
2. Ouvrez le fichier `slides.md` dans votre éditeur de texte préféré.
3. Modifiez les diapositives en utilisant la syntaxe Markdown.
4. Lancez MARP pour générer les diapositives au format PDF ou HTML.

## Syntaxe Markdown

La syntaxe Markdown est simple et intuitive. Vous pouvez utiliser des balises pour formater le texte, insérer des images, créer des listes et bien plus encore. Consultez la documentation de Markdown pour en savoir plus sur toutes les possibilités.

## Générer les présentations

Pour générer les diapositives, vous devez avoir Docker installés sur votre machine. Suivez les instructions d'installation fournies dans la documentation officielle de MARP.

Une fois que vous avez installé Docker, exécutez la commande suivante dans le répertoire du projet :

```bash
docker run --rm -v $pwd/presentation/:/home/marp/app/ -e LANG=$LANG marpteam/marp-cli slides.md --pdf -o output.pdf
```

Cela générera un fichier PDF contenant les diapositives.

N'hésitez pas à ouvrir une pull request si vous souhaitez contribuer à ce projet. Nous serons ravis de recevoir vos suggestions et améliorations.

Une liste de tâche est présente pour vscode dans Terminal >> Run Task.

## Contribuer

Si vous souhaitez contribuer à ce projet, n'hésitez pas à ouvrir une pull request. Nous serons ravis de recevoir vos suggestions et améliorations.
