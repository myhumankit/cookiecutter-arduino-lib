# {{cookiecutter.project_name}}
{{cookiecutter.project_short_description}}

{% if cookiecutter.language_code == 'fr-fr' -%}
## Fonctionnalités
 * (...)

## Démarrage rapide

### Prérequis
 * (...)

### Installation
[Téléchargez ce dépôt](https://github.com/{{cookiecutter.github_organization}}/{{cookiecutter.repository_name}}/archive/master.zip) et décompressez le dans le répertoire de bibliothèques Arduino de votre ordinateur. Renommez le dossier `{{cookiecutter.repository_name}}-master` en `{{cookiecutter.repository_name}}`.

Il est possible de cloner directement le dépôt git dans le répertoire de bibliothèques Arduino de votre ordinateur :

```
git clone git@github.com:{{cookiecutter.github_organization}}/{{cookiecutter.repository_name}}.git
```

Dans l'IDE Arduino, explorez les exemples du dossier `File/Examples/{{cookiecutter.library_name}}`.

## Briques technologiques utilisées
 * [Arduino](https://www.arduino.cc/) ;

## Gestion de version
La gestion de version repose sur le système [SemVer](http://semver.org/). Voir le fichier [CHANGELOG.md](CHANGELOG.md) pour plus de détails.

## Contribuer
Si vous souhaitez contribuer au projet, merci de créer une _issue_ ou de _forker_ ce projet et de créer une nouvelle branche. Toutes les _pull requests_ sont les bienvenues !

## Licence
Ce projet est diffusé sous la licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de details.

## Contributeurs
 * **{{cookiecutter.full_name}}** - [{{cookiecutter.github_username}}](https://github.com/{{cookiecutter.github_username}})
{% else -%}
## Features
 * (...)

## Getting started

### Requirements
 * (...)

### Installation
[Download this repository](https://github.com/{{cookiecutter.github_organization}}/{{cookiecutter.repository_name}}/archive/master.zip) and unzip it into the Arduino libraries folder on your computer. You should rename the folder `{{cookiecutter.repository_name}}-master` in `{{cookiecutter.repository_name}}`.

Or clone the repository directly in the Arduino libraries folder:

```
git clone git@github.com:{{cookiecutter.github_organization}}/{{cookiecutter.repository_name}}.git
```

In the Arduino IDE, look at `File/Examples/{{cookiecutter.library_name}}` folder to load an example sketch.

## Technologie used
 * [Arduino](https://www.arduino.cc/);

## Versioning
We use [SemVer](http://semver.org/) for versioning. See the [CHANGELOG.md](CHANGELOG.md) file for details.

## Contributing
If you'd like to contribute, please raise an issue or fork the repository and use a feature branch. Pull requests are warmly welcome.

## Licensing
The code in this project is licensed under MIT license. See the [LICENSE](LICENSE) file for details.

## Contributors
 * **{{cookiecutter.full_name}}** - [{{cookiecutter.github_username}}](https://github.com/{{cookiecutter.github_username}})
{%- endif %}
