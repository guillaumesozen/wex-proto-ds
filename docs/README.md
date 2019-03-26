# Bienvenue

Hello ! Vous retrouverez ici toutes les infos pour utiliser le **Design System Wexperience**. N'hésitez pas à **contribuer** via notre ce repo git public.

# Commencer

1. Installer la librairie **wex-proto-ds** :

Avec NPM (https://www.npmjs.com/package/wex-proto-ds) : 

`npm i wex-proto-ds`


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

![](https://i.ibb.co/xC0wJNP/Capture-d-e-cran-2019-03-26-a-20-45-30.png)


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

![](https://i.ibb.co/6HW4hJy/Capture-d-e-cran-2019-03-26-a-21-08-38.png)

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

![](https://i.ibb.co/TMPf76K/Capture-d-e-cran-2019-03-26-a-21-10-13.png)

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
