# Atelier éco-conception

L'objectif est de mettre en pratique ce que vous avez pu découvrir en ma compagnie ! 🥳

Avant de commencer, vous pouvez retrouver la plupart des chiffres indiqués dans les slides avec leurs sources sur le [site de la fevad](https://www.fevad.com/les-chiffres-leco-conception-web/).

## On commence par un petit jeu

Vous allez commencer par mettre en pratique vos nouvelles connaissances sur le jeu **[50 nuances de Green](https://jeu.digital.green/)** dont l'objectif est de réaliser le site avec le plus faible impact environnemental !

Vous allez obtenir un score (à prendre en screenshot et à m'envoyer) et pouvoir accéder à la correction qui regorge d'informations pour vos futurs développements verts !

## Expression des besoins & conception

Vous allez devoir créer le design d'un [site onepage](https://fr.wix.com/blog/comment-creer-site-one-page#viewer-boj1r) (ce lien sert juste à définir ce que c'est si jamais vous l'ignorez) qui va devoir respecter au mieux les principe d'éco-conception que vous avez pu découvrir.

Le scénario : Vous êtes maintenant un(e) développeu(r-se) aguerri(e) dans l'éco-conception et vous souhaitez faire profiter de votre expérience à d'autres entreprises pour un monde meilleur 🤩 Vous voulez donc créer un site qui montre vos talents de développeur ET d'éco-concepteur qui va permettre de vous contacter pour travailler avec vous.

Vous allez donc devoir **réaliser le wireframe puis la maquette** (mockup) de votre site en version mobile et desktop de façon plus ou moins libre puisque vous devrez respecter les contraintes suivantes pour leurs structures :

- un header avec le logo du site (à vous de le créer) et des liens qui peuvent mener aux différentes sections de la page
- une section pour présenter votre site avec [une vidéo](./assets/nature.mp4) en arrière-plan
- une section avec [quelques images](./assets) pour montrer notre belle nature (vous pouvez rajouter des textes etc.. si vous vous sentez inspiré)
- une section pour contacter l'entreprise afin de faire appel à ses services si un client souhaite profiter de notre expertise en éco-conception
- un footer avec les liens vers les réseaux sociaux

Votre page devra forcément inclure les 4 images et la vidéo fournies dans le dossier [/assets](./assets) de cet atelier.

Avant de passer à la suite, vous devez me faire valider votre design et les justifications de vos choix afin que je puisse vous faire un retour sur celui-ci.

## Des assets optimisés pour notre futur site

Maintenant que la maquette de votre site est prête, on va devoir préparer les ressources dans le dossier `/assets` pour que celui-ci soit le plus éco-responsable possible.

Il va donc falloir les alléger au maximum en terme de poids via des outils adaptés !

**Pour les images** : Vous allez devoir créer des versions réduites (en largeur x hauteur) de toutes les images à 25%, 50% et 75% de la taille initiale et réduire leurs poids le plus possible au format WebP.

Pourquoi avoir nos images en plusieurs format de tailles ?

Depuis plusieurs années, [les navigateurs permettent de choisir la source](https://developer.mozilla.org/fr/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) pour une image en fonction de la place disponible pour l'afficher. Sur un écran de téléphone, l'oeil humain ne saura pas faire la différence entre une image de très grande taille réduite par ma zone d'affichage et une image dans une taille faite pour celle-ci. Par contre, si votre image de grande taille fait 4 fois le poids de la plus petite, l'humain, la planète ou les bots des moteurs de recherche vont bien s'en rendre compte ! ☠️

Le [logiciel gratuit RIOT](https://riot-optimizer.com/) vous permettra d'arriver à vos fins. Pensez à jouer sur les paramétrages pour obtenir les fichiers les plus légers sans perte de qualité apparente.

**Pour le CSS et le JS** : Vous allez devoir utiliser des minifiers pour densifier votre code au maximum et réduire son poids. Pour l'instant, je vous invite à utiliser des minifiers en ligne pour réduire [votre CSS](https://www.toptal.com/developers/cssminifier) et [votre JS](https://www.toptal.com/developers/javascript-minifier) mais je vous conseille à terme d'installer des minifiers en local (quand vous maîtriserez NPM 👀)

**Pour les vidéos** : Vous allez également devoir les enregistrer en différentes résolutions (480p, 720p et 1080p) pour qu'elles puissent être adaptées à tous les types d'écrans et le débit descendant de vos visiteurs. Vous pourrez faire tout ça avec l'incroyable [HandBrake](https://handbrake.fr/) (les vidéos pourront être au format MP4 ou WebM).

A la fin de cette étape, envoyez-moi une capture d'écran du poids/taille de chaque fichier pour qu'on la valide 🤩

## Un peu de lecture

GREEN IT a écrit un super article "[Empreinte environnementale du numérique mondial](https://www.greenit.fr/etude-empreinte-environnementale-du-numerique-mondial/)" qui est une mine d'information ! Je vous invite à terminer cette journée d'éco-conception en le lisant avec attention pour en comprendre les enjeux !
