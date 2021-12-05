# Du piano au clavier midi
## Le piano
### L'histoire
En 1711, l'écrivain italien Scipione Maffei publie la première version du piano incluant son mécanisme (gravecembalo col piano e forte) qu'il a observé 2 ans avant. Les premiers exemplaires connus ont été fabriqués par Bartolomeo Cristofori à Florence.

![piano ancien](medias/piano_histoire.jpeg)
> Piano-forte de Bartolomeo Cristofori (1720)

### Le clavier
Il est composé de 88 touches. Les 52 touches blanches représentent la gamme diatonique(Do-ré-mi-fa-sol-la-si-do) de do majeur et les 36 touches noires aux cinq notes nécessaires pour finir la gamme chromatique. Généralement, le clavier contient 7 octaves et quart. 

![gamme chromatique](medias/gamme_chromatique.png)
> Gamme chromatique

### Le mécanisme
le marteau est propulsé avec une pièce en forme d'équerre (le bâton d'échappement) qui bascule en arrière lorsque sa partie horizontale atteint le bouton d'échappement. Ainsi le marteau est libre de repartir en arrière dès qu'il a touché la corde, qui peut alors vibrer sans être étouffée.

![mécanisme](medias/mecanisme.png)
> Mécanisme d'un piano à queue

## Le synthétiseur
### L'histoire
En 1874, Elisha Gray invente le télégraphe musical. Il est constitué de deux octaves et utilise à travers des électro-aimants les vibrations de lamelles métalliques. La diffusion est assurée par le réseau téléphonique. La première version du synthétiseur.

![premier synthétiseur](medias/synthetiseur_premier.jpeg)
> Le premier synthétiseur commercialisé (1964)

### Les contrôleurs
Un clavier peut être utilisé mais un séquenceur, un contrôleur à ruban tactile, ou grâce à des capteurs détectant la position de la main. 

![séquenceur](medias/sequenceur.jpeg)
> Un séquenceur

![contrôleur à ruban tactile](medias/controleur.png)
> Un contrôleur à ruban tactile

Le clavier est utilisé majoritairement lorsque le synthétiseur est sous forme physique. Certains peuvent avoir l'ajout d'un clavier compatible à l'interface MIDI ou CV/Gate. Avec le clavier, le synthétiseur propose un ensemble de potentiomètres (un type de résistance variable à trois bornes) et de faders (permet de contrôler les périphériques externes) pour le réglage du son.

### Le fonctionnement
Le son créé de manière analogique grâce à des circuits électroniques à comportement continu, de manière numérique à l'aide de circuits numériques ou à l'aide de ces deux technologies. En 1995, les microprocesseurs ont permis d'ouvrir une nouvelle voie. La synthèse sonore sur des ordinateurs personnels. L'une des méthodes consiste à reproduire les structures de synthèse d'origine en créant numériquement les circuits analogiques pour créer ou modifier des sons musicaux. 

### Les synthèses
Les plus courants, les synthèses analogiques soustractive et additive. Elles se basent sur des ondes simples. 
(Une onde sonore correspond à la propagation de perturbations mécaniques dans un milieu élastique.)
La synthèse additive combine différentes ondes sinusoïdales. (type d'ondes)

![ondes sinusoïdales](medias/onde_sinu.jpeg)
> Ondes sinusoïdales

Les synthèses soustractives utilise des signaux riches en harmoniques, et nécessite des filtres pour ajuster le ton.

### Les modules
Des modules connectés électroniquement entre-eux génèrent des sons par des circuits électroniques. Les plus récent utilise des processeurs avec l'architecture analogique. 

Les VCO, oscillateurs (la fonction est de produire un signal électrique périodique) qui créent les sons de base avec une tonalité qui dépend de la méthode de synthèse.(ensemble de techniques permettant la génération de signaux sonores)

Les VCF, filtres pour transformer le son en filtrant certaines fréquences.

Les VCA, amplificateur permettant de varier le volume.

Certains composants permettent de moduler les modules.
Les générateurs d'enveloppes permettent de moduler le son au début et à la fin d'une note.

Les LFO, permettent de moduler le son de manière périodique comme pour avoir un *vibrato* ou un *tremolo*.
(transmettre un signal par la modulation de la fréquence d'un signal porteur)

![architecture typique d'un synthétiseur modulaire](medias/architecture.png)
> Architecture typique d'un synthétiseur modulaire 
