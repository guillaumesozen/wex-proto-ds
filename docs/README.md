# Bienvenue

N'hésitez pas à **contribuer** via notre repo public : https://github.com/guillaumesozen/wex-proto-ds (:

# Release notes

A venir...

# Commencer

1. Installer la librairie **wex-proto-ds** :

Avec NPM (https://www.npmjs.com/package/wex-proto-ds) : 

`npm i wex-proto-ds`

Vous pouvez préciser une version spécifique si vous le souhaitez : 

`npm install wex-proto-ds@1.0.2`


Avec Bower :

`A venir...`

2. Récupérer l'asset "styles.css" dans le dossier `node_modules/wex-proto-ds/dist` et copier le au sein de votre projet.

3. Ajouter une balise link dans la partie `<head>` de votre page web : 

        <head>
        <link rel="stylesheet" href="[_chemin_vers_le_fichier_]/styles.css"  media="all"  />
        </head>


4. Utiliser les composants ci-dessous en copiant / collant le HTML renseigné dans la documentation dans votre page web.

# Composants



## Boutons

![](https://i.ibb.co/9WGSDLN/Capture-d-e-cran-2019-03-27-a-00-23-54.png)


<!-- tabs:start -->

#### ** Code **

Normal :

    <button class="o-btn">
    <span class="o-btn__text">Normal</span>
    </button>

Success :

    <button class="o-btn o-btn--success">
    <span class="btn__text">Success</span>
    </button>

Warning : 

    <button class="o-btn o-btn--warning">
    <span class="o-btn__text">Warning</span>
    </button>

Danger :

    <button class="o-btn o-btn--danger">
    <span class="o-btn__text">Danger</span>
    </button>

Disabled

    <button class="o-btn" disabled>
    <span class="o-btn__text">Disabled</span>
    </button>

#### ** Usage **

| ClassName                         |Usage                         |
|-------------------------------|-----------------------------|
|`o-btn`            |Bouton normal            |
|`o-btn o-btn--success`            |Bouton avec action positive            |
|`o-btn o-btn--warning`|Bouton de prévention|
|`o-btn o-btn--danger`|Bouton avec action négative|


<!-- tabs:end -->


## Nav

![](https://i.ibb.co/HTwvL3b/Capture-d-e-cran-2019-03-27-a-00-24-06.png)

    <nav class="l-nav">
      <ul class="l-nav__list">
        <li class="l-nav__item">
          <a class="l-nav__link" href="#">Accueil</a>
        </li>
        <li class="l-nav__item">
          <a class="l-nav__link" href="#">A propos</a>
        </li>
        <li class="l-nav__item">
          <a class="l-nav__link" href="#">Contact</a>
        </li>
      </ul>
    </nav>

![](https://i.ibb.co/5Ry7hTY/Capture-d-e-cran-2019-03-27-a-00-24-38.png)

    <nav class="l-nav">
      <ul class="l-nav__list">
        <li class="l-nav__item">
          <a class="l-nav__link" href="#">Accueil</a>
        </li>
        <li class="l-nav__item">
          <a class="l-nav__link" href="#">A propos</a>
          <ul class="l-nav__list  l-nav__list--is-sub">
            <li class="l-nav__item">
              <a class="l-nav__link" href="#">Mission</a>
            </li>
            <li class="l-nav__item">
              <a class="l-nav__link" href="#">Culture</a>
            </li>
          </ul>
        </li>
        <li class="l-nav__item">
          <a class="l-nav__link" href="#">Contact</a>
        </li>
      </ul>
    </nav>

## SearchBar

A venir...