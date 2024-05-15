# b2-open-source

## 1. Licences

- a) Quelle licence serait appropriée si je veux une licence permissive ?
il existe plusieur licenses : MIT License, BSD License, Apache License 2.0, ISC License, CC0 1.0 Universal
- b) Quelle licence serait appropriée si je veux que les projets utilisant ma solution soient obligatoirement open source eux aussi ?
  GNU General Public License (GPL) , GNU Affero General Public License (AGPL), Mozilla Public License (MPL) , Eclipse Public License (EPL) , Common Development and Distribution License (CDDL)
- c) Quelles sont mes obligations si j'utilise un projet sous licence `Creative Commons Attribution 4.0 International` ?
      Attribution : Vous devez donner le crédit approprié à l'auteur original de l'œuvre. Cela signifie que vous devez fournir un lien vers la licence, indiquer si des modifications ont été apportées à l'œuvre et inclure le nom de l'auteur.

    Pas de restrictions supplémentaires : Vous ne pouvez pas ajouter de restrictions supplémentaires à l'œuvre qui seraient contraires aux termes de la licence CC BY 4.0.

    Liberté d'utilisation : Vous êtes libre d'utiliser, de partager et d'adapter l'œuvre à des fins personnelles ou commerciales, tant que vous respectez les conditions de la licence.

    Distribution sous la même licence : Si vous remixez, transformez ou créez à partir de l'œuvre originale, vous devez distribuer votre contribution sous la même licence CC BY 4.0.

    Indication des changements : Si vous apportez des modifications à l'œuvre originale, vous devez indiquer clairement quels changements ont été effectués.
- d) Qu'appelle-t-on une licence "contagieuse" ?
  une licence open source qui impose des obligations spécifiques aux projets dérivés ou aux œuvres qui utilisent du code sous cette licence. Ces obligations peuvent inclure la nécessité de publier le code source de toute œuvre dérivée ou de toute application qui utilise le code sous cette licence.

> Ressources :
> - https://choosealicense.com/
> - https://www.tldrlegal.com/

## 2. Solutions propriétaires vs open source

### Bruno vs Postman

- a) Quelles raisons ont poussé beaucoup d'utilisateurs à chercher une alternative à Postman ?
Les raisons sont les coûts, limite des fonctionnalités dans la versions gratuites, etprobleme de confidentialité des données.
- b) Quels sont les avantages de Bruno ?
  bruno est open source, gratuit, et est sans les limitations

> Ressources :
> - https://www.usebruno.com/compare/bruno-vs-postman
> - https://star-history.com/#usebruno/bruno&Date
> - [Post Reddit 1](https://www.reddit.com/r/webdev/comments/17wqn5a/fuck_you_postman/)
> - [Post Reddit 2](https://www.reddit.com/r/webdev/comments/16tq1eh/now_that_postman_sucks_is_there_a_good_alternative/)
> - [Post Reddit 3](https://www.reddit.com/r/webdev/comments/16yxy43/what_are_people_using_instead_of_postman/)

### Twitter vs Mastodon

- c) À votre avis, quelles raisons ont poussé beaucoup d'utilisateurs à chercher une alternative à Twitter (ou X) ?
la modération des contenus, la confidentialité des données, et les changements de politique de la plateforme
> Ressources :
> - https://star-history.com/#mastodon/mastodon&Date

### Animejs, GSAP & rémunération

- d) Quelles sont les différences entre Animejs et GSAP, 2 librairies utilisées pour faire des animations web ?
- performance, syntaxe, dependance
- e) Pourquoi GSAP a choisi une licence moins permissive ?
  pour générer des revenus avec les utilisateurs commerciaux.
- f) Comment les projets open source peuvent être rémunérés et donc maintenus correctement ?
les sponsors, les dons, les services associés et les licences commerciales pour les utilisateurs professionnels

> Ressources :
> - https://gsap.com/pricing/
> - https://gsap.com/blog/why-license
> - https://github.com/juliangarnier/anime/
> - https://strapi.io/pricing-cloud

### Le cas de Meta

- g) Qu'est-ce qui a poussé Meta à changer la licence de React ?
  les critiques et les clauses de la licence précédente controversées.

> Ressources :
> - [Article Medium](https://medium.com/@raulk/if-youre-a-startup-you-should-not-use-react-reflecting-on-the-bsd-patents-license-b049d4a67dd2)

## 3. Quand ça tourne mal

### colors & faker.js

- a) Résumer brièvement ce qui s'est passé sur ces 2 packages
  Le développeur a saboté ses propres bibliothèques, ce qui fait que les bibliotheque dependante sont casser.
- b) En quoi était-ce une faille importante ?
  c'etait important car c'est grace a cette faille que on a decouvert l'ampleur des dependance inter bibliotheques
- c) Quelles sont les solutions pour se prémunir de ce genre de faille ?
  verfier regulierement les dependance de notre code, et faire des mise a jour en collaboration

> Ressources :
> - https://snyk.io/blog/open-source-npm-packages-colors-faker/
> - https://www.bleepingcomputer.com/news/security/dev-corrupts-npm-libs-colors-and-faker-breaking-thousands-of-apps/
> - https://www.youtube.com/watch?v=R6S-b_k-ZKY

### XZ backdoor

- d) À votre avis, quels sont les avantages d'avoir une faille dans une solution open source plutôt que propriétaire ?
lavantage davoir une faille dans une solution open source est que les faille sont detecter plus raipdement et elle peuvent etre reparer par tous le mondes. ce qui permet une total trasparence sur le code.
> Ressources :
> - https://www.youtube.com/watch?v=bS9em7Bg0iU
> - https://fr.wikipedia.org/wiki/Attaque_de_XZ_Utils_par_porte_d%C3%A9rob%C3%A9e


---

LICENSE: CC-BY-SA-4.0
