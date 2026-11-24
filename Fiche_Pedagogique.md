# DAD-NNN-Chae-ryoung

# Fiche Pédagogique

## Informations étudiant·e
- **Nom :** JANG
- **Prénom :** Chae-ryoung

---

## Profil et connaissances

### Présentation personnelle
Étudiante en 3ème année en Design et Arts Numériques (DAD), je m'intéresse aux croisements entre le design graphique, la typographie et les outils numériques interactifs. À court terme, mon objectif est de développer des systèmes visuels et sonores génératifs autour de la notion de « trace », qui serviront également de base de recherche pour mon projet de diplôme (DNA). À plus long terme, je souhaite approfondir cette pratique hybride mêlant édition, code créatif et installation.

### Compétences
- **CODE CRÉATIF :** Bases en HTML, CSS et JavaScript. Je souhaite approfondir la programmation générative (p5.js) ainsi que la synthèse sonore sur le web.
- **GIT ET VERSIONING :** Découverte de GitHub dans le cadre de ce cours pour structurer et documenter quotidiennement l'avancement de mes recherches.
- **INTERACTIVITÉ ET RENDU TEMPS RÉEL :** Premières expériences d'interactions simples, mais j'ai encore besoin de pratiquer le rendu et la génération en temps réel (visuel et sonore).
- **INSTALLATION ET MISE EN ESPACE :** Expérience dans la mise en espace graphique et éditoriale ; je souhaite explorer comment matérialiser un dispositif web dans un espace physique d'exposition.
- **PRÉSENTATION ET ARGUMENTATION :** Capabilité à structurer mes recherches et références, avec l'objectif de gagner en aisance à l'oral lors des échanges et questions spontanées.

---

## Projets

### Projet 1

#### Sujet du projet
- **Titre du projet :** Trace Synthesizer
- **Description du projet (environ 150 mots) :** Ce projet interroge la distinction entre l’*usure* (altération lente et durable) et la *trace* (apparition légère, éphémère et destinée à disparaître : buée, empreinte dans la poussière, trace humide, auréole)[cite: 6, 7]. À partir d'une collecte photographique de ces traces éphémères du quotidien, je conçois un site web d'édition participative[cite: 8, 12]. L'utilisateur sélectionne 2 ou 3 textures et les fusionne en temps réel via différents modes (contraste, tissage slit-scan, déformation par données lumineuses) tout en générant des sons (bruits, ondes) liés aux contrastes de l'image[cite: 12]. Lors de la sauvegarde, l'image créée rejoint une archive commune où elle s'efface progressivement avec le temps, comme une trace physique[cite: 14, 15]. Toutefois, sa « recette » (combinaison et réglages) demeure enregistrée, permettant aux visiteurs suivants de rejouer et modifier les créations des autres[cite: 14].

#### Thématiques de recherche
- **Thématiques que vous souhaitez explorer :** La trace éphémère comme matière graphique et sonore ; la mémoire numérique, l'effacement et l'édition participative sur le web[cite: 7, 14].
- **Pourquoi cette thématique vous intéresse-t-elle ? (environ 100 mots) :** Je m'intéresse à la fragilité des traces quotidiennes qui n'existent que par la photographie avant de s'évaporer ou d'être effacées[cite: 7, 8]. Plutôt que de considérer le web comme une galerie figée où tout s'accumule indéfiniment, je souhaite l'aborder comme un milieu vivant soumis au temps : un espace d'édition ouverte où les images créées s'estompent, mais où les gestes et réglages des utilisateurs se transmettent et se réactivent collectivement[cite: 14, 15].

#### Outils et techniques
- **Outils que vous comptez utiliser (logiciels, langages de programmation, etc.) :** HTML/CSS, JavaScript, p5.js (et p5.sound / Web Audio API), GitHub, base de données légère (ou localStorage) pour l'archivage des recettes.
- **Techniques spécifiques que vous souhaitez maîtriser ou expérimenter :** Fusion et manipulation d'images par pixels (`pixels[]`, slit-scan, displacement mapping), synthèse sonore interactive selon les valeurs lumineuses, gestion temporelle de l'opacité et sauvegarde de paramètres au format JSON[cite: 8, 14, 15].

#### Références artistiques
- **Argumentaire expliquant la pertinence de votre projet (environ 150 mots) :** Dans la vie réelle, une trace éphémère disparaît avec le temps et ne peut être reproduite à l'identique[cite: 14, 15]. Le médium web permet ici d'inventer une mécanique propre : si le résultat visuel s'évapore progressivement dans l'archive commune, le code conserve la mémoire de sa fabrication (la recette)[cite: 14, 15]. En réactivant la recette d'un autre visiteur, l'utilisateur génère une nouvelle itération qui n'est plus l'original, mais une réinterprétation collective[cite: 14]. Ce système répond directement à l'enjeu de l'édition participative : chacun devient co-éditeur d'une matière visuelle et sonore en perpétuelle transformation, reliant l'observation sensible du quotidien à la logique algorithmique du réseau.
- **Références artistiques qui inspirent votre travail (livres, artistes, œuvres, etc.) :** 
  - *Références théoriques :* Walter Benjamin (*Paris, capitale du XIXe siècle*, distinction entre *trace* et *aura*)[cite: 9] ; Georges Didi-Huberman (*La Ressemblance par contact*, sur l'empreinte et le geste)[cite: 9, 10].
  - *Références visuelles et plastiques :* Man Ray et Marcel Duchamp, *Élevage de poussière* (1920), pour la captation photographique d'une matière fragile et destinée à être effacée[cite: 10] ; Richard Long, *A Line Made by Walking* (1967), où la photographie est l'unique archive d'un passage éphémère[cite: 10] ; Francis Alÿs, *Paradox of Praxis 1* (1997), sur l'enregistrement d'une action qui s'efface[cite: 10].
  - *Références web et participatives :* Martine Neddam, *Mouchette*, pour l'implication active du visiteur comme co-auteur[cite: 10] ; *r/place* (Reddit), pour la logique de mur commun en constante réécriture[cite: 11, 13].

---

## Actions

### Présentation orale d'un sujet artistique ou design (documentation de recherche)
// Sujet choisi, membres du groupe, date de passage et lien vers votre présentation :

### Accrochage de rendu
Mise en place d'un poste interactif (ordinateur et casque audio) permettant aux visiteurs de manipuler directement le site web en temps réel (sélection des traces, mixage visuel et sonore, archivage). À côté de l'écran, une sélection de résultats générés dans l'archive commune sera imprimée sous forme d'affiches / fiches éditoriales et accrochée au mur, accompagnée de leurs recettes respectives pour matérialiser le passage du numérique à l'édition papier.

### Contribution au logiciel
Conception d'un outil web d'édition participative permettant à chaque utilisateur de combiner des textures photographiques, d'expérimenter des algorithmes de fusion en temps réel et de partager ses paramètres de création (recettes JSON) pour que d'autres puissent les prolonger[cite: 12, 14].

---

## Planification

### Planning de travail
- **Étape 1 (23/11 - 27/11) :** Collecte photographique de traces éphémères (buée, poussière, traces humides, etc.), normalisation des images, réalisation des croquis d'interface (3 écrans) et prototypage de base sur p5.js[cite: 8, 13].
- **Étape 2 (30/11 - 04/12) :** Bilan de mi-parcours (01/12), développement des modes de fusion (contraste, slit-scan, mapping), intégration de la synthèse sonore et du système de sauvegarde/rechargement des recettes[cite: 12, 14].
- **Étape 3 (07/12 - 11/12) :** Implémentation de l'effacement progressif dans l'archive, test écrit de code (10/12), impression des affiches issues de l'archive et installation pour l'accrochage final (11/12)[cite: 14, 15].

---

## Commentaires et questions
// Avez-vous des questions ou des préoccupations à propos du cours ou de vos projets ? :

---

## Journal de bord
*Ajoutez une entrée à chaque jour de cours, la plus récente en haut.*

### 24/11/2026
- **Ce que j'ai fait :** Échange avec l'enseignant permettant de clarifier la distinction conceptuelle entre *usure* (durable) et *trace* (éphémère). Redéfinition du corpus photographique vers des traces passagères, réalisation des premiers croquis / notes visuelles et conception du système d'archive éphémère avec conservation des « recettes » de création.
- **Problèmes rencontrés :** Nécessité de rendre le dispositif immédiatement lisible visuellement (maquettes d'interface) et d'ancrer la disparition des images dans une logique cohérente avec le médium web.
- **Prochaine étape :** Réaliser les maquettes détaillées des 3 écrans du site, photographier une première série de traces éphémères et coder le prototype de fusion d'images sur p5.js.
- **Captures / liens :**

![Note de recherche 1](img/note_1.jpg)
![Note de recherche 2](img/note_2.jpg)
![Note de recherche 3](img/note_3.jpg)
![Note de recherche 4](img/note_4.jpg)

### 23/11/2026
- **Ce que j'ai fait :** Première présentation de l'idée autour de la collecte de textures de traces et de la génération procédurale visuelle et sonore. Réception des premiers retours sur l'édition participative et la pertinence du web.
- **Problèmes rencontrés :** Sujet initial trop large (« trace » en général) et besoin de justifier pourquoi le web est le médium le plus adapté.
- **Prochaine étape :** Affiner le périmètre de collecte et structurer la logique participative du site.
- **Captures / liens :**