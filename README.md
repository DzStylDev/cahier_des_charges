<p style="color:blue">**1. Cadrer un Projet et Conceptualiser une Solution Web**</p>

Cahier des charges

**Introduction**

   **Projet** :

    le projet s'appelle portfoliov2 en comparaison au portfolio de la version 1 fait en html / css et javascript

    Description : portfolio contenant l'ensemble de mes compétences, , de tout ce que j'ai accompli durant mes 2 années à Epitech.

**Contexte**:

    Le projet répond au besoin des personnes voulant visualiser le portfolio , il contient tout ce que j'ai accomplie durant c'est 2 année sous forme de différent section permettant au personne d'en savoir plus sur mon parcours.

**Objectif généraux :**
 
    Les buts de ce projet est de présenter les compétences, les expériences , les centre d'intérêt , les hobbies , les langues , une courte description de qui je suis et ce que je fait actuellement , les projets fait à epitech durant mes 2 années

**2. Objectifs et Enjeux**
   
    Objectif spécifiques : L'objectif de ce portfolio est d'avoir des animation fait avec framer-motion pour avoir une bonne fluidité d'animation et un pilotage complet , de mettre en avant ses compétences et ses expériences
    Enjeux: Créer un portfolio en react , ajouter des animation avec framer-motion.

**Spécifications Fonctionnelles**

**Structure du site:**

    - Section Compétences : Cette section regroupe toute les compétences que j'ai acquis durant c'est 2 années.

    - Section Expériences : Cette section comporte toute les expérience que j'ai réaliser que ce soit en formation ou en stage , ou en entreprise.

    - Section Contact: Section permetttant de me contacter.

    - Section A propos de moi: Section contenant les informations de la personnes.

    - Section projet : Section contenant 6 de mes projets ainsi que le language associer et le lien github.
  
    -Section CV: Cv téléchargeable.

**Fonctionnalités :**
    
     - Téléchargement du cv 
     - Lien vers le github.
     - Formulaire de contact fonctionnel.
     - Mise en place d'un modal permettant d'ajouter des projets à la section.
     - Utilisation de firebase pour stocker les données.
     - Navigation entre différentes catégories de compétences via une méthode scrollToSection.
     - Responsive (mobile-first).
     - Stockage permettant de stocker les images pour chaque projet ajouté via le Storag de firebase.

**Interface utilisateur:** 

    Utilisation de figma
    Utilisation de composant pour créer rendre la section compétences dynamqique à chaque fois qu'on séléctionne une catégorie.

**Spécifications Techniques:**

    Technlogies à utiliser : J'utilise React pour le front-end et firebase pour le back-end , pour le design j'utilise tailwind css.
    Compatibilité: adaptabilité mobile (responsive design)
    Hébergement: Netlify
    Budget: Aucun
    Délais : 20/30 min , 1H tout dépend de la fonctionnalité à mettre en place
    Contraintes techniques: Utilisation de React.

**Phases du développement:**

    Calendrier : Tous les jours je développe une fonctionnalités sur le portfolio , ça peut généralement me prendre 10/15/20/30 min selon la feature
    Isoler toute les parties intéressante d'un portoflio pour ma part les sections AProposDeMoi , Centre_Interet , Compétences , Contact , Projects , Header , Footer
    Mise en place du header , ajout d'onglets permettant de naviger sur différente sections.
    Création du composant AProposDeMoi , Centre_Intéret , Compétences  , Contact , Projects
    Ajout du back pour le formulaire d'envoi du composant Contact
    Répartition des tâches : Le projet est réaliser individuellement

**7.  Livrables Attendues**

    Portfolio final : 
    
    Le produit est un portfolio développer avec react et héberger en ligne sur la plateforme netlify , il est accessible en ligne.

    Documentation technique : 
    
    Le code est répartie en plusieurs composants , il y'a un composant qui permet de zoomer une compétence au survol , une detection d'image ou d'icone envoyé en props dans le composant , un systeme de gallerie permettant de visualiser les images lier au projet , boutton de suppression du projet 
    Les technologies sont React , Firebase , tailwindcss ,
    librairie utilisé : 
      - FontAwsomeIcon
      - sweetalert2
      - yet-another-react-lightbox
      - react-hot-toast
    Systeme de message via l'api web3form 
    
**Rapport de projet :**

    - Initialisation du portoflio-v2 avec npx create-react-app
    - Ajout de multiple section pour le portfolio
    - Ajout d'une homepage
    - Avancement du portfolio (Changement de couleur d'icone , ajout d'icone avec fontAwesome)
    - Ajout d'une section compétences contenant toute mes compétences
    - Ajout d'une icone svg pour la section compétence et ajout de multiple composant pour la hiérarchie.
    - Ajout d'une nouvelle methode pour faire en sorte qu'au survol des icones , elles se zoom (scale)
    - Refonte de plusieurs sections : contacte moi , centre d'intérêt , langues , project , diplome et expérience
    - Ajout de la configuration firebase , et du fichier .env
    - Ajout d'un .gitignore for ignorer ces fichiers (.env)
    - Ajout d'une variable d'environnement , et de la configuration pour firebase.
    - Ajout de deux librairie (@@headlessui/react et @heroicons/react)
    - Ajout d'un composant Projects permettant de créer un projet dynamique en mettant les information dans le formulaire
    - Création du fichier firebaseConfig.js (Object contant les configuration permettant d'interagir avec firebase)
    - Méthode permettant de lire tous les projets
    - Refonte de la section (ajout de style)
    - Modification du fichier README.md
    - Ajout de plusieurs icones provenant du site svgrepo.com (Modification de la taille des images)
    - Ajout du lien vers mon cv au clique du boutton.

**8. Critères de Réussite**

      Objectif principal : Attirer des clients potentiels.
      Qualité visuelle et technique : Redéfinir le design system avec des sections distinctes, animations en utilisant Motion Framer, onglets de navigation pour compétences, et une navigation fluide avec effet de scroll        vers des sections spécifiques.
      Contenu pertinent : Galerie d’images, titre, description, langages utilisés, et liens vers les projets GitHub.
      Feedback : Obtenir des retours de professionnels.
      Résultats concrets : Propositions de missions, embauches ou collaborations.

**9. Ressources Nécessaires**

      Équipement : Outils logiciels et matériels nécessaires (ordinateurs, éditeurs de code, accès internet).
   
      Editeur de code utilisé : VSCODE , nous somme connecté au réseaux epitech , le projet est développer en REACT
      Compétences : Connaissances requises (développement web, design UX/UI, gestion de projet).
      Temps : 1h / 2h

**10. Risques et Gestion des Risques**
   
    Risques identifiés : Difficultés possibles (retards, problèmes techniques, bugs).
    Plans de mitigation : Solutions prévues pour gérer les risques (tests réguliers, révisions de planning).

- Rédaction des spécifications techniques :

   1. Introduction
   
               Ce document décrit les spécifications techniques d'un projet de portfolio développé en React pour le front-end et Firebase pour le back-end. Le portfolio comprend plusieurs sections : un header, une section "À propos", compétences, expériences          professionnelles, formations, Projects , Centre_Intéret , contacts, et un footer.

   2. Architecture Générale

               L'application suit une architecture client-serveur avec un front-end basé sur React qui interagit avec Firebase pour la gestion des données.

               Technologie front-end : React.js
               Technologie back-end : Firebase (RealiTime Database, Storage)
               Hébergement : Netlify
               Base de données : Firestore (NoSQL)

   3. Structure et Composants
   
            Header : Contient la navigation principale avec des liens vers les sections du site.
            Footer : Contient des liens vers les réseaux sociaux.
            Section "À propos" : Texte de présentation et image.
            Section Compétences : Liste interactive des compétences avec un système de "tabs" permettant la navigation entre différentes catégories.
            Section Expériences et Formations : Affiche une chronologie des expériences professionnelles et des formations.
            Section Contact : Formulaire de contact permettant l’envoi d’un message. Les données du formulaire sont envoyées via Firebase.
            Section Projects : Liste tous les projets créer via le boutton "ajouter un projet" , Les données sont stockées grace à firebase dans la section Realtime Database et récupérées dynamiquement

   5. Technologies Utilisées
   
            React.js : Pour le rendu des composants, la gestion des états et l'interactivité.
            firebase/database :Pour gérer les traitements complexes, comme l'ajout de projet dans firebase ,  la suppression d'un projet (liste de méthode utilisé push() , ref() , set() , get() , remove() ).
            firebase/storage : Pour le téléchargement d'images  liste des références de chaque projet contenant chaque images, suppession du projet séléctionner avec la méthode deleteObject()
            Netlify : Pour l'hébergement du site web.

   7. Comportement et Fonctionnalités

            Récupération des données : La section Project doit charger les données dynamiquement depuis database de firebase..
            Navigation fluide : Utilisation de scrollTo pour une navigation fluide entre les différentes sections.
            Animation avec Framer Motion : Les transitions entre les sections ou l'apparition de contenus sont animées pour améliorer l'expérience utilisateur.
            Formulaire de contact : Validation des données côté client (React) avant envoi à Realtime Database.

   9. Performance et Sécurité

            Optimisation du chargement : Utilisation de techniques de lazy loading pour les sections qui ne sont pas visibles dès le chargement initial.
            Sécurité : Protection des données utilisateurs via Firebase Authentication (si gestion d’utilisateurs) et règles de sécurité Firestore pour s'assurer que seules les données autorisées sont accessibles.

   11. Contraintes

            Compatibilité Navigateur : Le site doit être compatible avec les dernières versions des principaux navigateurs (Chrome, Firefox, Edge).
            Responsiveness : Le site doit être entièrement responsive, avec une bonne adaptation mobile et desktop.
            Accessibilité : Respecter les normes d'accessibilité (WCAG 2.1) en veillant à une bonne visibilité des textes et des interactions accessibles au clavier.
       
   13. Livrables

            Code source de l'application React
            Fichiers de configuration Firebase
            Documentation d'installation et de maintenance

   15. Tests

            Tests Unitaires : Utilisation de Jest pour tester les composants React.
            Tests Fonctionnels : requête pour l'envoi du formulaire via web3forms.

   17. Suivi et Maintenance

             Le projet sera versionné sous GitHub avec une documentation complète pour faciliter les futures mises à jour et la maintenance.

- Déploiement d'un environnement de travail avec des outils de versionnage, de partage et de collaboration/communication :

   Outils de versionnage :

      Utiliser Git pour la gestion de versions du code.

   Partage et collaboration :

      Intégrer des systèmes comme Trello ou Jira pour la gestion des tâches.
      Utiliser des fonctionnalités de pull request et code review pour collaborer efficacement.

   Zoom ou Google Meet pour les réunions et collaborations à distance.

   Documentation :

      Créer des documentations partagées via Confluence ou Notion pour centraliser les informations du projet.

 - Réalisation d'une maquette

         Maquette fait sur figma le lien se trouve sur le portofoliov2 public dans le README.MD

 - Identification des fonctionnalités à développer pour structurer l'architecture de la solution web et de la base de données :

   Définir les objectifs

         Lister les fonctionnalités principales à intégrer (ex. : gestion de contenu, formulaire de contact).
         Diviser en modules : Segmenter les fonctionnalités en modules comme gestion des utilisateurs, des projets, ou des commentaires.
         Concevoir la base de données : Créer un modèle de données avec les entités et leurs relations (ex. : utilisateurs, projets, messages).
         Planifier les interactions : Définir les interactions entre le front-end et le back-end (ex. : API pour chaque fonctionnalité).

- Rédaction d'une présentation pour présenter les choix techniques, les maquettes et le schéma de la solution web :

   1. Choix Techniques :
           
          Front-end : React.js a été choisi pour sa flexibilité, son architecture modulaire et sa capacité à créer des interfaces utilisateur dynamiques et performantes. Il permet également un rendu optimisé et une meilleure gestion des états via des hooks.
          Back-end : Firebase a été sélectionné pour gérer la base de données (RealTime Database) Firebase permet une intégration fluide avec React grâce à sa structure NoSQL et ses fonctionnalités comme la sauvegarde de donnée à travers la database (Realtime Database).

   Design System
  
        Nous avons adopté une approche mobile-first avec un design responsive, afin de garantir une expérience utilisateur optimale sur tous les appareils. Les animations sont gérées via Framer Motion, offrant une navigation fluide et dynamique entre les sections.

   2. Maquettes :
   
            Outils utilisés : Les maquettes ont été créées avec Figma pour visualiser la disposition des sections (header, à propos, compétences, expérience, formation, contact, footer). Chaque composant a été soigneusement conçu pour offrir une expérience utilisateur claire et intuitive.

            Navigation : Nous avons conçu une interface simple avec un menu de navigation en tête de page, permettant de naviguer vers chaque section par ancre. La section compétences inclut un système de "tabs" pour basculer entre différentes catégories.

   3. Schéma de l'Architecture :
      
            L'architecture de la solution est répartie en plusieurs couches pour garantir la modularité et la réutilisabilité :
            Front-end (React) : Gestion de l’interface utilisateur et de la navigation via des composants réactifs. Chaque section du portfolio est un composant distinct (AProposDeMoi, DEProfessionnel , Centre_Interet, Projects, Contact ,Foooter , Header).
            Back-end (Firebase) : Gestion des projets (ajout , suppression , listing) via RealTime Database
            Base de données Firebase/Database : Stockage des données pour la secton Projects dans une base de données NoSQL.
            Hébergement : Le site est déployé sur netlify, assurant un déploiement rapide et sécurisé.

<p style="color:blue">**2. Développer une Solution Web**</p>

* Développement du prototype de la solution web

      Initialisation du projet : Configurer un environnement de développement (ex. React pour le front-end, Firebase pour le back-end).
      Création des composants : Développer chaque composant du site (header, sections à propos, compétences, footer , contact , centre d'intérêts , Projects) avec des données statiques ou dynamiques provenant de Firebase.
      Intégration des services Firebase : Ajouter RealTime Database pour stocker les données.
      Tests et validation : Tester l’application pour s’assurer que toutes les fonctionnalités fonctionnent correctement (interaction via le formulaire de contact).

 * Rédaction du code de la solution en transcrivant les fonctionnalités du Cahier des Charges

 *  Initialisation du Projet (React + Firebase) :
      
         Créer un projet avec create-react-app.
         Configurer Firebase pour le projet ( Hosting).

      
      ```bash
      npx create-react-app portfoliov2
      npm install firebase
      ```

   2. Création des Composants (Front-End) :
      
Chaque section sera un composant React.

Section "À propos de moi" :
```jsx

import React from 'react'
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import { faGithub } from '@fortawesome/free-brands-svg-icons';
import { motion } from 'framer-motion'
import revealText from '../utils/revelText';
import revelText from '../utils/revelText';
import { faFilePdf } from '@fortawesome/free-regular-svg-icons';

export default function AProposDeMoi({ refSection }) {

  let text = `
    J'ai 26 ans , je développe depuis 4 ans et je suis en deuxième année de web@academie
    J'ai commencé par développer des plugins minecraft, des bots discord et quelques sites (front-end, back-end)
  `
  let cite = "Travailleur , autonome et motivé , possèdant une très bonne faculté d'adaptation et un sens relationnel développé"

  const textChars = revealText(text);
  const citeChar = revelText(cite)

  const charVariants = {
    hidden: {
      opacity: 0,
    },
    reveal: {
      opacity: 1
    }
  }
  return (
    <div 
      ref={refSection}
       className='py-6 px-8 md:px-32'>
      <div className='flex'>
        <p className="mb-3 mt-3 font-bold text-white">A propos de moi</p>
      </div>
      <div>
        <div className='text-[.9rem] leading-7'>
          <motion.p
            initial="hidden"
            whileInView="reveal"
            transition={{ staggerChildren: .01 }}
            className='text-white'
          >
            {textChars.map((char, index) => (
              <motion.span
                key={index}
                transition={{
                  duration: 0.2,
                }}
                variants={charVariants}
              >
                {char}
              </motion.span>
            ))}
          </motion.p>
          <motion.p
            initial="hidden"
            whileInView="reveal"  
            transition={{ staggerChildren: .02 }}
             className='text-white'
          >
            {citeChar.map((cite, index) => (
              <motion.cite
              key={index}
              transition={{
                duration: 0.2,
              }}
              variants={charVariants}
              >
                {cite}
              </motion.cite>
            )
            )}
          </motion.p>


          <div className='mb-3 mt-6'>
            <a
            download={true}
            href='../assets/Cv amine v2.pdf'
            rel="noreferrer"
              className='inline-flex items-center justify-between min-w-40 gap-2 px-5 py-2 text-sm font-medium text-center text-white rounded-lg bg-button-bg hover:bg-button-hover-bg  transition-all ease-in-out delay-75'>
                <div  className='text-white'>Télécharger mon cv</div>
                <FontAwesomeIcon icon={faFilePdf} size='xl' />
              </a>
          </div>

          <button>
            <div className='flex'>
              <p className='mb-3 mt-3 font-bold text-white'>Ou me trouver</p>
            </div>
            <div>
              <div className='flex'>
              <a
            href='http://github.com/DzStylDev'
            target='_blank'
            rel="noreferrer"
              className='inline-flex items-center px-4 py-2 text-sm font-medium text-center text-white rounded-lg bg-button-bg hover:bg-button-hover-bg  transition-all ease-in-out delay-75 justify-between gap-2'>
                <div>GitHub</div>
                <FontAwesomeIcon icon={faGithub} size='xl' />
              </a>
              </div>
            </div>

          </button>

        </div>
      </div>
    </div>
  )
}
```
Section "Centre intérets" :
```jsx
import React from 'react'

export default function Centre_Interet() {
  return (
    <div className='bg-button-bg rounded-lg'>
      <div className=" p-4 rounded-lg md:p-8 dark:bg-gray-800 bg-gradient-to-tr bg-button-bg mt-5 mb-2" id="statistics" role="tabpanel" aria-labelledby="statistics-tab">
                <dl className="grid max-w-screen-xl grid-cols-2 gap-8 p-4 mx-auto text-gray-900 sm:grid-cols-3 xl:grid-cols-2 dark:text-white sm:p-8 text-center">
                    <div className="flex flex-col">
                        <dt className="mb-2 text-3xl font-extrabold">Centre d'interêts</dt>
                        <dd className="text-gray-500 dark:text-gray-400">Informatique</dd>
                        <dd className="text-gray-500 dark:text-gray-400">Sport (Football , karaté et taekwondo)</dd>
                    </div>
                    <div className="flex flex-col">
                        <dt className="mb-2 text-3xl font-extrabold">Langues</dt>
                        <dd className="text-gray-500 dark:text-gray-400">Anglais Intermédiaire</dd>
                        <dd className="text-gray-500 dark:text-gray-400">Arabe: courant</dd>
                    </div>
                </dl>
            </div>
    </div>
  )
}

```

Section "Compétences" :
```jsx
import React from 'react'
import { faBootstrap, faJava, faLaravel, faPhp, faSymfony, faJs, faDocker } from '@fortawesome/free-brands-svg-icons';
import { motion } from "framer-motion"
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome';

function hoverCompetence(icon, tag, color = null, boolImgOrIcon) {
  return (
    <>
      <motion.div whileHover={{ scale: 1.2 }} className="flex flex-col align-middle items-center justify-center">

        {
          boolImgOrIcon === true ?
            <FontAwesomeIcon icon={icon} color={color} fontSize={50} />
            :
            <img src={`../assets/images/${icon}`} alt="" height={50} width={50} />
        }
        <div>{tag}</div>
      </motion.div>
    </>
  )
}

export default function Competences() {
  let variants = {
    hidden: {
      opacity: 0,
    },
    visible: {
      opacity: 1,
    }
  }
  return (

    <div className='py-6 px-8 md:px-32'>
      <div

        className='font-bold mb-2 text-white'>
        Compétences
      </div>

      <div
        className="w-full bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <motion.ul
          initial={{
            opacity: 0
          }}
          whileInView={{
            opacity: 1
          }}
          transition={{
            ease: 'easeIn',
            duration: 1,
            delay: .5
          }}

          className="flex flex-wrap text-sm font-medium text-center border-b border-gray-200 rounded-t-lg bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:bg-gray-800" id="defaultTab" data-tabs-toggle="#defaultTabContent" role="tablist" aria-label='tabs'>
          <li>
            <button id="framework-tab" data-tabs-target="#framework" type="button" role="tab" aria-controls="framework" aria-selected="true" className="inline-block p-4 rounded-ss-lg hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700 transition-all duration-75 ease-in-out">Framework</button>
          </li>
          <li>
            <button id="versionning-tab" data-tabs-target="#versionning" type="button" role="tab" aria-controls="versionning" aria-selected="false" className="inline-block p-4 rounded-ss-lg hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700  transition-all duration-75 ease-in-out">Outils de versionning</button>
          </li>
          <li>
            <button id="front-end-tab" data-tabs-target="#front-end" type="button" role="tab" aria-controls="front-end" aria-selected="false" className="inline-block p-4 rounded-ss-lg hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700  transition-all duration-75 ease-in-out">Language Front-End</button>
          </li>
          <li>
            <button id="back-end-tab" data-tabs-target="#back-end" type="button" role="tab" aria-controls="back-end" aria-selected="false" className="inline-block p-4 rounded-ss-lg hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700  transition-all duration-75 ease-in-out">Language Back-End</button>
          </li>
          <li>
            <button id="bdd-tab" data-tabs-target="#bdd" type="button" role="tab" aria-controls="bdd" aria-selected="false" className="inline-block p-4 rounded-ss-lg hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700  transition-all duration-75 ease-in-out">Base de donnée</button>
          </li>
          <li>
            <button id="ed-tab" data-tabs-target="#ed" type="button" role="tab" aria-controls="ed" aria-selected="false" className="inline-block p-4 rounded-ss-lg hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700  transition-all duration-75 ease-in-out">Environnement d’exécution </button>
          </li>
          <li>
            <button id="lb-tab" data-tabs-target="#lb" type="button" role="tab" aria-controls="lb" aria-selected="false" className="inline-block p-4 rounded-ss-lg hover:bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700  transition-all duration-75 ease-in-out">Librairie Javascript</button>
          </li>
        </motion.ul>
        <div id="defaultTabContent">
          <div className=" p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800 transition-all duration-300 ease-in-out"

            id="framework" role="tabpanel" aria-labelledby="framework-tab">
            <motion.div variants={variants}
              initial="hidden"
              whileInView="visible"
              transition={{
                ease: 'easeIn',
                duration: 1,
                delay: .1
              }} className="grid grid-flow-col md:grid-cols-5 gap-5 py-4 text-white">
              {hoverCompetence(faLaravel, 'Laravel', 'red', true)}
              {hoverCompetence(faSymfony, 'Symfony', 'mintcream', true)}
              {hoverCompetence(faBootstrap, 'BootStrap', '#7E13F8', true)}
            </motion.div>
          </div>
          <div className="p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800 invisible hidden opacity-0 transition-all duration-300 ease-in-out" id="versionning" role="tabpanel" aria-labelledby="versionning-tab">
            <motion.div variants={variants}
              initial="hidden"
              whileInView="visible"
              transition={{
                ease: 'easeIn',
                duration: 1,
                delay: .1
              }} className="grid grid-cols-3 md:grid-cols-9 py-4 text-white gap-5">
              {hoverCompetence('git.svg', 'Git', null, false)}
              {hoverCompetence('gitlab.svg', 'GitLab', null, false)}
            </motion.div>
          </div>
          <div className="p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800 invisible hidden opacity-0 transition-all duration-300 ease-in-out" id="front-end" role="tabpanel" aria-labelledby="front-end-tab">
            <motion.div variants={variants}
              initial="hidden"
              whileInView="visible"
              transition={{
                ease: 'easeIn',
                duration: 1,
                delay: .1
              }
              } className="grid grid-cols-3 md:grid-cols-5 gap-5 py-4 text-white">
              {hoverCompetence('react-svgrepo-com.svg', 'React', null, false)}
              {hoverCompetence(faJs, 'JavaScript', '#F7DF1E', true)}
              {hoverCompetence('css3-svgrepo-com.svg', 'Css', null, false)}
              {hoverCompetence('vue-9-logo-svgrepo-com.svg', 'Vue', null, false)}
              {hoverCompetence('sass-svgrepo-com.svg', 'SASS', null, false)}
              {hoverCompetence('html-5-svgrepo-com.svg', 'HTML', null, false)}
              {hoverCompetence('jquery.svg', 'Jquery', null, false)}
              {hoverCompetence('typescript.svg', 'Typescript', null, false)}
              {hoverCompetence('node-js-svgrepo-com.svg', 'NodeJs', null, false)}
            </motion.div>
          </div>
          <div className="p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800 invisible hidden opacity-0 transition-all duration-300 ease-in-out" id="back-end" role="tabpanel" aria-labelledby="back-end-tab">
            <motion.div variants={variants}
              initial="hidden"
              whileInView="visible"
              transition={{
                ease: 'easeIn',
                duration: 1,
                delay: .1
              }
              } className="grid grid-cols-3 md:grid-cols-5 py-4 text-white gap-5">
              {hoverCompetence(faJs, 'Javascript', '#F7DF1E', true)}
              {hoverCompetence(faJava, 'Java', '#d82222', true)}
              {hoverCompetence('python-svgrepo-com.svg', 'Python', null, false)}
              {hoverCompetence('ruby.svg', 'Ruby', null, false)}
              {hoverCompetence(faPhp, 'PHP', '#777bb3', true)}
              {hoverCompetence('typescript.svg', 'Typescript', null, false)}
              {hoverCompetence('node-js-svgrepo-com.svg', 'NodeJs', null, false)}
            </motion.div>
          </div>

          <div className="p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800 invisible hidden opacity-0 transition-all duration-300 ease-in-out" id="bdd" role="tabpanel" aria-labelledby="bdd-tab">
            <motion.div variants={variants}
              initial="hidden"
              whileInView="visible"
              transition={{
                ease: 'easeIn',
                duration: 1,
                delay: .1
              }} className="grid grid-cols-3 md:grid-cols-5 py-4 text-white gap-5">
              {hoverCompetence('mysql-logo-svgrepo-com.svg', 'Mysql', null, false)}
              {hoverCompetence('mongo-svgrepo-com.svg', 'Mongo DB', null, false)}
            </motion.div>
          </div>

          <div className="p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800 invisible hidden opacity-0 transition-all duration-300 ease-in-out" id="ed" role="tabpanel" aria-labelledby="ed-tab">
            <motion.div variants={variants}
              initial="hidden"
              whileInView="visible"
              transition={{
                ease: 'easeIn',
                duration: 1,
                delay: .1
              }} className="grid grid-cols-3 md:grid-cols-5 py-4 text-white gap-5">
              {hoverCompetence(faDocker, 'Docker', "#2396ed", true)}
              {hoverCompetence('linux-svgrepo-com.svg', 'Linux', null, false)}
            </motion.div>
          </div>
          <div className=" p-4 bg-white rounded-lg md:p-8 dark:bg-gray-800 hidden transition-all duration-300 ease-in-out" id="lb" role="tabpanel" aria-labelledby="lb-tab">
            <motion.div
              variants={variants}
              initial="hidden"
              whileInView="visible"
              transition={{
                ease: 'easeIn',
                duration: 1,
                delay: .1
              }}
              className="grid grid-cols-3 md:grid-cols-5 py-4 text-white gap-5">
              {hoverCompetence('Threejs-logo.svg', 'ThreeJS', null, false)}
            </motion.div>
          </div>
        </div>
      </div>



    </div>
  )
}

```

Section "Contact" :
```jsx

import { faEnvelope } from '@fortawesome/free-regular-svg-icons'
import { faMobilePhone } from '@fortawesome/free-solid-svg-icons'
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import React, { useState } from 'react'
import Swal from "sweetalert2"

export default function Contact() {
  const [name, setName] = useState("")
  const [email, setEmail] = useState("")
  const [message, setMessage] = useState("")

  const onSubmit = async (event) => {
    event.preventDefault();

    const formData = new FormData(event.target);

    if(name !== "" && email !== "" && message !== ""){

    formData.append("access_key", process.env.REACT_APP_ACCESS_KEY);

    const response = await fetch("https://api.web3forms.com/submit", {
      method: "POST",
      body: formData
    });

    const data = await response.json();
   
    if (data.success) {
      Swal.fire({
        title: "Message Envoyé",
        text: "Ton message à était envoyé avec success",
        icon: 'success'
      })
    } else {
      Swal.fire({
        title: "Message non envoyé",
        text: "Ton message n'à  pas pus etre envoyé car clé manquante pour l'api web3form",
        icon: 'error'
      })

    }
  } else {
    Swal.fire({
      title: "Message non envoyé",
      text: "Ton message n'à  pas pus etre envoyé car le formulaire est incomplet",
      icon: 'error'
    })
  }
  event.target.reset();
  };
  
  return (
    <div className='py-6 px-8 md:px-32 text-white'>
    <div className='mt-5 p-1'>
          <h1 className="text-1xl font-bold text-mintcream my-auto">Contacte-moi</h1>
          <div className="text-sm font-light text-[#5b85c0] pb-8 ">Envie de me recontrer ou de discuté avec moi</div>
    </div>  
    <div className='rounded-sm p-1'>
      <div className="flex flex-col md:flex-row  w-full mx-auto rounded-2xl gap-5">
        <form className="w-full grid grid-cols-1 gap-5 bg-gray-800 rounded-xl p-4"  onSubmit={onSubmit} method='POST'>
         <div className='flex gap-2 w-full'> 
          <input type="hidden" name="access_key" value={process.env.REACT_APP_ACCESS_KEY} className='w-full' />
            <div className="pb-6 w-full">
              <label htmlFor="prenom" className="block mb-2 text-sm font-medium text-mintcream">Name</label>
              <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
              </svg>
              </span>
                <input type="text" name="prenom" id="prenom" placeholder="Enter Name" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-prenom" onChange={(e) => setName(e.currentTarget.value)} />
              </div>
            </div>
            <div className="pb-6 w-full">
              <label htmlFor="email" className="block mb-2 text-sm font-medium text-mintcream">Email</label>
              <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                <path strokeLinecap="round" strokeLinejoin="round" d="M2.25 13.5h3.86a2.25 2.25 0 0 1 2.012 1.244l.256.512a2.25 2.25 0 0 0 2.013 1.244h3.218a2.25 2.25 0 0 0 2.013-1.244l.256-.512a2.25 2.25 0 0 1 2.013-1.244h3.859m-19.5.338V18a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18v-4.162c0-.224-.034-.447-.1-.661L19.24 5.338a2.25 2.25 0 0 0-2.15-1.588H6.911a2.25 2.25 0 0 0-2.15 1.588L2.35 13.177a2.25 2.25 0 0 0-.1.661Z" />
              </svg>
              </span>
                <input type="email" name="email" id="email" placeholder="Enter Email" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-email" onChange={(e) => setEmail(e.currentTarget.value)}/>
              </div>
            </div>
         </div>
            <div className="pb-6">
            <label htmlFor="message" className="block mb-2 text-sm font-medium text-mintcream">Message</label>
            <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="lucide lucide-mail"><rect width="20" height="16" x="2" y="4" rx="2"></rect><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path></svg></span>
              <input type="text" name="message" id="message" placeholder="Enter Message" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-message" onChange={(e) => setMessage(e.currentTarget.value)}/>
            </div>
          </div>
          <button type="submit" className="w-full text-[#ffffff] bg-button-hover-bg hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mb-6 transition-all duration-75 ease-out">Envoyé</button>

        </form> 
        <div className='w-full'>
       
       <div className='bg-gray-800 rounded-xl p-4 flex flex-col justify-between gap-2'>
          
            <div className='flex items-center gap-5'>
              <FontAwesomeIcon icon={faEnvelope} color='mintcream' className='text-[1.4em]' />
              <span>amine.meddour@epitech.eu</span>
            </div>
            
            <div className='flex items-center gap-5'>
              <FontAwesomeIcon icon={faMobilePhone} color='mintcream' className='text-[1.4em]' />
              <span>+33 04 45 21 56 36</span>
            </div>

       </div>
        </div>
      </div>
    </div>
    </div>
  )
}
```

Section "DEProfesionnel" :
```jsx

import React from 'react'
export default function DEProfessionnel() {
  return (
    <div className='py-6 px-8 md:px-32'>
      <div className='font-bold mb-2 text-white'>Mes Diplôme et mes expériences</div>
      
    <div className='flex flex-col md:flex-row w-full justify-between rounded-lg gap-2'>
        <div className='border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 w-full'>
       
          <div className='gap-2 flex h-full'>
            <div className='flex rounded-lg shadow-xl"
                hover:opacity-50
                hover:shadow-md 
                bg-button-bg
                py-6 px-5
                w-full
                '>
              <div className="flex flex-col py-2 w-full">
                <div className=" text-[#ffffff]">
                  <div className='font-bold mb-2 text-xl' >Diplômes</div>

                  <div className="flex flex-col justify-center">
                      
                      <div className="py-2">
                        <p className="text-white text-sm font-bold">DEVELOPPEUR-INTEGRATEUR WEB (Titre 5 RNCP - BAC +2)</p>
                        <p className="text-gray-400 text-xs mt-2">2022 / 2024</p>
                        <img src="../assets/images/webacademy.svg" alt='webacademy-img' />
                        <div className="flex items-center align-middle gap-1">
                          <img src="../assets/images/epitech.svg" alt='epitech-img' />
                          <p>- Paris</p>                          
                        </div>
                        <div className="border-b-[#324b76] border mt-2"></div>

                      </div>

                      <div className="">
                        <p className="text-white text-sm font-bold">BAC PRO Electrotechnique</p>
                        <p className="text-gray-400 text-xs mt-2">2018 / 2019</p>
                        <div className="flex items-center align-middle gap-1">
                          <p>Lycée Louis Armand</p>
                          <p>- Paris</p>
                        </div>
                        <div className="border-b-[#324b76] border mt-2"></div>

                      </div>
                      
                      <div className="mt-2">
                        <p className="text-white text-sm font-bold">BEP Electrotechnique</p>
                        <p className="text-gray-400 text-xs mt-2">2016 / 2017</p>
                        <div className="flex items-center align-middle gap-1">
                          <p>Lycée Louis Armand</p>
                          <p>- Paris</p>
                        </div>
                        <div className="border-b-[#324b76] border mt-2"></div>

                      </div>
                      
                  </div>

                </div>
              </div>
            </div>
            
          </div>
        </div>

        <div
        className='border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700 w-full'>
          <div className='gap-2 flex'>
            <div className='flex shadow-xl"
                hover:opacity-50
                hover:shadow-md 
                px-5 py-6
                rounded-lg
                bg-button-bg
                w-full'>
              <div className="flex flex-col py-2 w-full">
                <div className=" text-[#ffffff]">
                  <div className='font-bold mb-2 text-xl' >Mes Expériences</div>

                  <div className="flex flex-col justify-center">
                      
                      <div className="py-2">
                        <p className="text-white text-sm font-bold">Stage de 8 semaines en Electrotechnique à Energilec</p>
                        <p className="text-gray-400 text-xs mt-2">2018</p>
                        <p className="text-gray-400 text-xs mt-2">Compréhension d'un schéma éléctrique</p>                          
                        <p>Saint-Cloud</p>
                        <div className="border-b-[#324b76] border mt-2"></div>

                      </div>

                      <div className="">
                        <p className="text-white text-sm font-bold"> Stage de 8 semaines en Electrotechnique à Sarl Satlec</p>
                        <p className="text-gray-400 text-xs mt-2">2017</p>
                        <p className="text-gray-400 text-xs mt-2">Installation des lampes . Cablage éléctrique</p>
                        <p>Paris</p>
                        <div className="border-b-[#324b76] border mt-2"></div>
                      </div>
                      
                      <div className="mt-2">
                        <p className="text-white text-sm font-bold">Stage de 6 semaines en Electronique à NK Electronique</p>
                        <p className="text-gray-400 text-xs mt-2">2015</p>
                        <p className="text-gray-400 text-xs mt-2">Démontage d'ordinateurs et de télévisions</p>
                          <p>Paris</p>
                        <div className="border-b-[#324b76] border mt-2"></div>

                      </div>

                      <div className="mt-2">
                        <p className="text-white text-sm font-bold">Stage de 6 semaines en électrotechnique à SBD (Self blanc drug)</p>
                        <p className="text-gray-400 text-xs mt-2">2015</p>
                        <p className="text-gray-400 text-xs mt-2">Réparation des laveries</p>
                          <p>Paris</p>
                        <div className="border-b-[#324b76] border mt-2"></div>

                      </div>
                      
                  </div>

                </div>
              </div>
            </div>
            
          </div>
        </div>
    </div>
    </div>
  )
}

```
Section "Footer" :
```jsx
import React from 'react'
export default function Footer() {

    
    return (
        <div className='py-6 px-8 md:px-32 text-white'>
            <div className="rounded-lg to py-2 mx-auto my-5  bg-button-bg text-[#ffffff]font-bold text-1xl text-center ">Designed and Developed by Amine . Copyright © 2024 All Rights Reserved</div>
        </div>
    )
}
```
Section "Header" :
```jsx
import React, { useState } from 'react'
import { AnimatePresence, motion } from 'framer-motion'
import { Squash as Hamburger } from "hamburger-react"

export default function Header({ scrollToSection }) {

  const [menuVisible, setMenuVisible] = useState(false)

  return (
    <div className='w-full h-full absolute bg-[linear-gradient(to_right,_#1f2937,_#2e3f5c)] header'>
      <motion.header
        initial={{
          y: -29,
          opacity: 0
        }}
        animate={{
          y: 0,
          opacity: 100
        }}
        transition={{
          ease: 'easeIn',
          duration: 2
        }} className='flex justify-between items-center py-6 px-8 md:px-32  fixed z-40 w-full [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] backdrop-blur-sm bg-[rgba(0,_0,_0,_0.5)] text-white drop-shadow-md'>
        <div>
          <div className='text-white'>Amine Meddour</div>
          <span className='text-white'>DEVELOPPEUR WEB FULLSTACK</span>
        </div>


        <ul className={`hidden xl:flex items-center gap-12 font-semibold text-sm`} style={{ transition: "transform 0.3s ease, opacity 0.3s ease" }} >
          <button className='p-3 hover:bg-white hover:text-[#243147] rounded-md transition-all cursor-pointer'>
            Accueil
          </button>
          <button onClick={() => scrollToSection('about')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            A propos
          </button>
          <button onClick={() => scrollToSection('competences')} className='p-3 cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            Compétences
          </button>
          <button onClick={() => scrollToSection('projects')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            Projets
          </button>
          <button onClick={() => scrollToSection('contact')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            <span>Contact</span>
          </button>
        </ul>
        
        <div className='xl:hidden flex text-5xl cursor-pointer'>
          <Hamburger toggled={menuVisible} size={25} toggle={setMenuVisible} color='white' />
        </div>

        <AnimatePresence>
          {menuVisible && (
            <motion.div
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            exit={{ opacity: 0 }}
            transition={{ duration: 0.5 }}
              className={`absolute xl:hidden top-24 left-0 w-full [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] backdrop-blur-sm bg-[rgba(0,_0,_0,_0.5)] flex flex-col items-center gap-6 font-semibold text-lg transform z-40 transition-transform`}
              style={{ transition: "transform 0.3s ease , opacity .3s ease" }}
            >
              <motion.button
               initial={{ scale: 0, opacity: 0 }}
               animate={{ scale: 1, opacity: 1 }}
               transition={{
                 type: "spring",
                 stiffness: 260,
                 damping: 20,
                 delay: 0.1 + 0 / 10,
               }} 
                onClick={() => setMenuVisible(!menuVisible)} className='p-4 w-full list-none hover:bg-white hover:text-[#243147] transition-all cursor-pointer text-center [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Accueil
              </motion.button>
              <motion.button
               initial={{ scale: 0, opacity: 0 }}
               animate={{ scale: 1, opacity: 1 }}
               transition={{
                 type: "spring",
                 stiffness: 260,
                 damping: 20,
                 delay: 0.1 + 1 / 10,
               }}  
                onClick={() => {
                scrollToSection('about')
                setMenuVisible(!menuVisible)
              }
              } className='p-4 list-none text-center w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                A propos
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 2 / 10,
                }}  
                onClick={() => {
                  scrollToSection('competences')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center list-none w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Compétences
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 3 / 10,
                }}  
                onClick={() => {
                  scrollToSection('projects')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center w-full list-none hover:bg-white hover:text-[#243147] rounded-md transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Projets
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 4 / 10,
                }}  
                onClick={() => {
                  scrollToSection('contact')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center list-none w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                <span>Contact</span>
              </motion.button>
            </motion.div>
          )}
        </AnimatePresence >


      </motion.header>
    </div>
  )
}
 ```
Section "Projects" :
```jsx

import React, { useState } from 'react'
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import { faBootstrap , faGithub, faJava, faLaravel, faPhp, faSymfony, faJs, faDocker } from '@fortawesome/free-brands-svg-icons';
import { Dialog, DialogBackdrop, DialogPanel, DialogTitle } from '@headlessui/react';
import { PlusIcon } from '@heroicons/react/24/solid';
import { getDatabase, push, ref as dbRef, set, get, remove } from 'firebase/database'
import { getDownloadURL, list, ref as storageRef, uploadBytes, getStorage, listAll , deleteObject} from 'firebase/storage'
import app, { imageDB } from "../firebaseConfig"
import toast from 'react-hot-toast';
import { useEffect } from 'react';
import Lightbox from "yet-another-react-lightbox";
import 'yet-another-react-lightbox/styles.css';
import { Counter, Download, Fullscreen, Thumbnails, Zoom} from 'yet-another-react-lightbox/plugins';
import 'yet-another-react-lightbox/plugins/captions.css';
import 'yet-another-react-lightbox/plugins/thumbnails.css';
import "yet-another-react-lightbox/plugins/counter.css";
import { faImages } from '@fortawesome/free-regular-svg-icons';

export default function Projects({ title }) {
  const [toggle, setToggle] = useState(false)
  const [titre, setTitre] = useState('')
  const [description, setDescription] = useState('')
  const [images, setImages] = useState("")
  const [projects, setProjects] = useState([])
  const [color, setColor] = useState("")
  const [linkGitHub, setLinkGitHub] = useState("")
  const [member, setMember] = useState('')
  const [openGallerie, setOpenGallerie] = useState(null)
  const [checkedValue, setCheckedValue] = useState(null);

  const iconMap = {
    faLaravel: faLaravel,
    faSymfony: faSymfony,
    faBootstrap: faBootstrap,
    faGit: "git.svg",
    faGitlab: "gitlab.svg",
    faReact: "react-svgrepo-com.svg",
    faJS: faJs,
    faJava: faJava,
    faCss3: "css3-svgrepo-com.svg",
    faVuejs: "vue-9-logo-svgrepo-com.svg",
    faSass: "sass-svgrepo-com.svg",
    faHtml5: "html-5-svgrepo-com.svg",
    faJquery: "jquery.svg",
    faTypescript: "typescript.svg",
    faNodeJs: "node-js-svgrepo-com.svg",
    faPython: "python-svgrepo-com.svg",
    faRuby: "ruby.svg",
    faPhp: faPhp,
    faMysql: "mysql-logo-svgrepo-com.svg",
    faMongoDB: "mongo-svgrepo-com.svg",
    faDocker: faDocker,
    faLinux: "linux-svgrepo-com.svg",
    threeJS: "Threejs-logo.svg"

  };


  const toggleProject = () => {
    setToggle(!toggle)
  }
  const createProject = async (e) => {
    e.preventDefault()
    const db = getDatabase(app)
    const newDocRef = push(dbRef(db, "projects"))

    set(newDocRef, {
      titre,
      description,
      iconeName: document.getElementById('icones').value,
      icon: iconMap[document.getElementById('icones').value],
      color,
      link: linkGitHub,
      member: member
    }).then(() => {
      toast.success('Le projet à était créer avec success')
      toggleProject()
    }).catch(error => {
      console.log(error.message)
    })


    for (let index = 0; index < images.length; index++) {
      const imageListRef = storageRef(imageDB, `${titre}_images/${images[index].name}`)

      if (images === null) return;

      uploadBytes(imageListRef, images[index]).then(snapchot => {
        getDownloadURL(snapchot.ref)
      })
    }


  }

  const deleteProject = async (keyItem, item) => {

    if (!keyItem) {
      console.error("Erreur : keyItem est undefined ou null");
      return;
  }
    const db = getDatabase(app)
    const getProjectDB = dbRef(db, `projects/${keyItem}`)

    const storage = getStorage(app);
    const getStorageDB = storageRef(storage, `${item.titre}_images`)

    try {
    let { items } = await listAll(getStorageDB)
      if (items.length === 0) {
        console.error("Aucun fichier trouvé dans ce chemin.");
      } else {
          console.log("Fichiers trouvés :", items);
          const deletePromises = items.map(async (itemRef) => await deleteObject(itemRef));

          await Promise.all(deletePromises);

          console.log("Tous les fichiers dans le dossier ont été supprimés avec succès !");
      }
    } catch (error) {
      console.error("Erreur lors de la vérification des fichiers :", error);
    }

    remove(getProjectDB)
     .then(() => {
         console.log("Projet supprimé avec succès");
         toast.success('Le projet à était supprimer avec success')
     })
     .catch((error) => {
         console.error("Erreur lors de la suppression du projet :", error);
     });

  }
  const getMember = (e) => {
    setMember(e.target.value)
  }
  const readProjectFile = async (projects) => {
    const storage = getStorage(app);

    let addFiles = []
    let files = []

    projects.map((projet, index) => {

      addFiles.push(storageRef(storage, `${projet.titre}_images`))
      return addFiles
    })

    let promises = addFiles.map((reference, index) => {
      let path = reference._location.path

      let getReference = list(reference)

      files[path] = [{}]


      return getReference.then(result => {
        result.items.forEach((item, indexImage) => {
          let url = 'https://firebasestorage.googleapis.com/v0/b/' + item._location.bucket + '/o/' + item._location.path.replace('/', '%2F') + '?alt=media'

          files[path].push({
            src: url.replace(' ', '%20'),
            description: projects[index].description,
            title: "Image " + (indexImage + 1),
          })
        })
        files[path].splice(0, 1)

      })
    })

    Promise.all(promises).then(() => {
      return files
    }).catch(err => {
      console.error("Une erreur est survenue: ", err);
    });

    return files
  }
  const handleCheckboxChange = (value) => {
    setCheckedValue(value)
  }
  useEffect(() => {
    const fetchProjects = async () => {
      const db = getDatabase(app)
      const refDB = dbRef(db, 'projects')
      const snapshot = await get(refDB)

      if (snapshot.exists()) {
        let idKeys = Object.keys(snapshot.val())
        let projects = Object.values(snapshot.val())
        let getAllProject = await readProjectFile(projects)

        let projectsAll = getAllProject


        let project = projects.map((project, index) => { 
          return {
            keyID: idKeys[index],
            titre: project.titre,
            description: project.description,
            checkGallerie: projectsAll[project.titre + '_images'],
            icon: project.icon,
            color: project.color,
            link: project.link,
            member: project.member
          }
        })

        
        setProjects(project)
      }
    };

    fetchProjects()
  }, [])
  let toggleButton = true
  return (
    <div className='py-6 px-8 md:px-32 text-white'>
      <div  
    className='font-bold mb-2 flex items-center align-middle justify-between'>
        <span>{title}</span>
        {
          title === "Mes Projets" ? (
            toggleButton && (
              <button onClick={toggleProject} className="relative inline-flex items-center justify-center p-0.5 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br from-[#5b637a] to-[#3f5081] group-hover:from-[#5b637a] group-hover:to-[#3f5081] hover:text-white dark:text-white focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800">
              <span className="relative px-5 py-2.5 transition-all ease-in duration-75 bg-[#272e3e] rounded-md group-hover:bg-opacity-0">
                Ajouter un projet
              </span>
            </button>)
            )
            :
            <></>
        }

      </div>


      
      <div className="grid grid-cols-1 md:grid-cols-2 sm:grid-cols-2 gap-3.5 items-center align-middle h-full">
      
     
      
        {projects.length > 0 && projects.map((item, index) => (
          <div
            key={index} className='flex w-full flex-wrap bg-button-bg gap-5 justify-center h-full border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700'>
        <button style={{ marginTop: '1em' }} onClick={() => setOpenGallerie(index)}>
        <FontAwesomeIcon icon={faImages} color='#4a596e' fontSize={30} className='text-[#4a596e] hover:text-blue-200 transition-all duration-300 ease-in-out' />
        </button>

        { openGallerie === index && (
          <Lightbox 
              plugins={[ Download, Fullscreen, Zoom, Thumbnails, Counter]}
              counter={{ 
                container: { 
                  style: { 
                    top: 0, 
                    bottom: 0 
                  } 
                } 
              }}
              captions={{
                showToggle: true,
                descriptionTextAlign: 'end'
              }}
              open={true}
              close={() => setOpenGallerie(null)}  
              slides={item.checkGallerie}
            />
          )}
            <div className="flex flex-col rounded-lg w-full p-5">
              <div className="text-2xl font-bold text-white pb-6">
                <div className='flex justify-between item'>
                  <p>{item.titre}</p>
                </div>
              </div>
              <div className=" text-[.9em]  text-[#6a7c97]">
                {item.description}
              </div>
              <div className="flex pt-2 gap-2 items-center align-middle">
                <div>
                  <button href="#" className="bg-primary-bg text-[#ffffff] px-3 py-2 rounded-lg inline-flex items-center align-middle">
                    {
                      item.member === "one"
                        ?
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" className="size-5">
                          <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                        </svg>
                        :
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" className="size-5">
                          <path strokeLinecap="round" strokeLinejoin="round" d="M15 19.128a9.38 9.38 0 0 0 2.625.372 9.337 9.337 0 0 0 4.121-.952 4.125 4.125 0 0 0-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 0 1 8.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07M12 6.375a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z" />
                        </svg>
                    }
                    <span className='ml-2'>{item.member === "one" ? '1' : 'Plusieurs'}</span>
                  </button>
                </div>
                <div className='flex items-center align-middle'>
                  <button href="#" className='bg-gradient-to-tr bg-primary-bg text-[#ffffff] px-3 py-2 rounded-lg inline-flex items-center align-middle '>
                    <span>
                      {
                        typeof item.icon === "object"
                          ?
                          <FontAwesomeIcon icon={item.icon} color={item.color} fontSize={20} />
                          :
                          <img src={`../assets/images/${item.icon}`} alt="" />
                      }
                    </span>
                  </button>
                  <a href={item.link} target='_blank' rel="noreferrer" className='ml-2 bg-gradient-to-tr bg-primary-bg hover:bg-button-hover-bg cursor-pointer transition-all duration-300 ease-out text-[#ffffff] px-3 py-2 rounded-lg inline-flex items-center align-middle '>
                    <FontAwesomeIcon icon={faGithub} fontSize={25} />
                  </a>
                </div>
                
              </div>
              <div className='mt-2 flex'>
              { item.titre !== "RPGGames" && item.titre !== "Restaurant" && item.titre !== "Events"  && item.titre !== "Auto Ecole" && item.titre !== "html5gaming" ?
                  <button onClick={() => deleteProject(item.keyID, item)} className='bg-red-400 px-5 py-2 rounded-md text-sm cursor-pointer transition-all duration-200 ease-in-out hover:text-red-500 hover:bg-white'>Supprimer ce project</button>
                  : 
                  ''
                }
                </div>
            </div>
          </div>

        ))}

      </div>
        
      <div>
        {
          toggle && (
            <Dialog open={toggle} onClose={toggleProject} className="relative z-10">
              <DialogBackdrop
                transition
                className="fixed inset-0 bg-gray-500 bg-opacity-75 transition-opacity data-[closed]:opacity-0 data-[enter]:duration-300 data-[leave]:duration-200 data-[enter]:ease-out data-[leave]:ease-in"
              />

              <div className="fixed inset-0 z-10 overflow-y-auto">
                <div className="flex justify-center p-4 text-center">
                  <DialogPanel
                    transition
                    className="relative transform overflow-hidden rounded-lg bg-gray-800 text-left shadow-xl transition-all data-[closed]:translate-y-4 data-[closed]:opacity-0 data-[enter]:duration-300 data-[leave]:duration-200 data-[enter]:ease-out data-[leave]:ease-in sm:my-16 sm:w-full sm:max-w-lg data-[closed]:sm:translate-y-0 data-[closed]:sm:scale-95"
                  >
                    <div className="bg-bg-gray-800 px-4 pb-4 pt-5 sm:p-6 sm:pb-4">
                      <div className="sm:flex sm:items-start">
                        <div className="mx-auto flex h-12 w-12 flex-shrink-0 items-center justify-center rounded-full bg-white sm:mx-0 sm:h-10 sm:w-10">
                          <PlusIcon aria-hidden="true" className="h-6 w-6 text-orange-600" fill='#3d4858' />
                        </div>
                        <div className="mb-5 text-center sm:ml-4 sm:mt-0 sm:text-left">
                          <DialogTitle as="h3" className="text-base font-semibold leading-6 text-gray-400">
                            Ajout d'un projet
                          </DialogTitle>
                          <div className="">
                            <p className="text-sm text-gray-500">
                              Les projets ajouter seront afficher dans la rubrique 'projet afficher'
                            </p>
                          </div>
                        </div>


                      </div>
                      <div className='p-1 rounded-sm'>
                        <div className="mx-auto 3xl:p-14 rounded-2xl gap-5">
                          <form className="w-full grid grid-cols-1 xl:grid-cols-1 bg-gray-800 rounded-xl">
                            <div className='flex flex-col md:flex-row gap-2'>
                              <div className="">
                                <label htmlFor="title" className="block mb-2 text-sm font-medium text-white">Titre du projet</label>
                                <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                                  <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                </svg>
                                </span>
                                  <input type="text" name="title" id="title" placeholder="Entrer le titre du projet" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="title" onChange={(e) => setTitre(e.target.value)} />
                                </div>
                              </div>
                              <div className="">
                                <label htmlFor="desc" className="block mb-2 text-sm font-medium text-white">Description du projet</label>
                                <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                                  <path strokeLinecap="round" strokeLinejoin="round" d="M2.25 13.5h3.86a2.25 2.25 0 0 1 2.012 1.244l.256.512a2.25 2.25 0 0 0 2.013 1.244h3.218a2.25 2.25 0 0 0 2.013-1.244l.256-.512a2.25 2.25 0 0 1 2.013-1.244h3.859m-19.5.338V18a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18v-4.162c0-.224-.034-.447-.1-.661L19.24 5.338a2.25 2.25 0 0 0-2.15-1.588H6.911a2.25 2.25 0 0 0-2.15 1.588L2.35 13.177a2.25 2.25 0 0 0-.1.661Z" />
                                </svg>
                                </span>
                                  <input type="desc" name="desc" id="desc" placeholder="Entrer la description du projet" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="desc" onChange={(e) => setDescription(e.target.value)} />
                                </div>
                              </div>
                            </div>
                            <div className="">
                              <label htmlFor="images" className="block mb-2 text-sm font-medium text-white">Image du projet</label>
                              <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" strokeWidth="1.5" className="size-6">
                                <path d="M9.97.97a.75.75 0 0 1 1.06 0l3 3a.75.75 0 0 1-1.06 1.06l-1.72-1.72v3.44h-1.5V3.31L8.03 5.03a.75.75 0 0 1-1.06-1.06l3-3ZM9.75 6.75v6a.75.75 0 0 0 1.5 0v-6h3a3 3 0 0 1 3 3v7.5a3 3 0 0 1-3 3h-7.5a3 3 0 0 1-3-3v-7.5a3 3 0 0 1 3-3h3Z" />
                                <path d="M7.151 21.75a2.999 2.999 0 0 0 2.599 1.5h7.5a3 3 0 0 0 3-3v-7.5c0-1.11-.603-2.08-1.5-2.599v7.099a4.5 4.5 0 0 1-4.5 4.5H7.151Z" />
                              </svg>
                              </span>
                                <input type="file" multiple name="images" id="images" placeholder="Insérer des images lier au projet" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" onChange={(e) => setImages(e.target.files)} />
                              </div>
                            </div>
                            <div className="">
                              <label htmlFor="icones" className="block mb-2 text-sm font-medium text-white">Icones</label>

                              <div className="">

                                <label htmlFor="icones" className="sr-only">Selectionne le language</label>
                                <select id="icones"
                                  className="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-e-lg border-s-gray-100 dark:border-s-gray-700 border-s-2 focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                >

                                  <option value="">Séléctionne le language</option>
                                  <option value="faHtml5">HTML</option>
                                  <option value="faLaravel">Laravel</option>
                                  <option value="faSymfony">Symfony</option>
                                  <option value="faNodeJs">Node JS</option>
                                  <option value="faReact">React</option>
                                  <option value="faPhp">PHP</option>
                                  <option value="faPython">Python</option>
                                  <option value="faRuby">Ruby</option>
                                  <option value="faVuejs">Vue</option>
                                  <option value="faCss3">CSS</option>
                                  <option value="faJS">Javascript</option>
                                  <option value="faJava">Java</option>
                                  <option value="faBootstrap">Bootstrap</option>
                                  <option value="faTypescript">Typescript</option>
                                  <option value="threeJS">ThreeJS</option>
                                </select>
                              </div>
                            </div>
                            <div className="">
                              <label htmlFor="color_icones" className="block mb-2 text-sm font-medium text-white">Couleur de l'icone du projet</label>
                              <div className="text-gray-400">
                                <input type="color" name="color_icones" id="color_icones" placeholder="#fff" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block p-2.5 rounded-l-lg py-3 px-4" onChange={(e) => setColor(e.target.value)} />
                              </div>
                            </div>
                            <div className="flex justify-between items-center align-middle">
                              <ul className="grid gap-6 md:grid-cols-2 grid-cols-2" onChange={getMember}>
                                <li>
                                  <input type="checkbox" id="option-1" value="one" className="hidden peer" required="" onChange={() => handleCheckboxChange('one')} checked={checkedValue === "one"} />
                                  <label htmlFor="option-1" className="inline-flex items-center justify-between w-full p-5 text-gray-500 bg-white border-2 border-gray-200 rounded-lg cursor-pointer dark:hover:text-gray-300 dark:border-gray-700 peer-checked:border-white hover:text-gray-600 dark:peer-checked:text-gray-300 peer-checked:text-gray-600 hover:bg-gray-50 dark:text-gray-400 dark:bg-gray-800 dark:hover:bg-gray-700">
                                    <div className="block">
                                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-5" name='test'>
                                        <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                      </svg>
                                      <div className="w-full text-xs font-semibold">1 personne</div>
                                    </div>
                                  </label>
                                </li>
                                <li>
                                  <input type="checkbox" id="option-2" value="all" className="hidden peer" required="" onChange={() => handleCheckboxChange('all')} checked={checkedValue === "all"}/>
                                  <label htmlFor="option-2" className="inline-flex items-center justify-between w-full p-5 text-gray-500 bg-white border-2 border-gray-200 rounded-lg cursor-pointer dark:hover:text-gray-300 dark:border-gray-700 peer-checked:border-white hover:text-gray-600 dark:peer-checked:text-gray-300 peer-checked:text-gray-600 hover:bg-gray-50 dark:text-gray-400 dark:bg-gray-800 dark:hover:bg-gray-700">
                                    <div className="block">
                                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                                        <path strokeLinecap="round" strokeLinejoin="round" d="M15 19.128a9.38 9.38 0 0 0 2.625.372 9.337 9.337 0 0 0 4.121-.952 4.125 4.125 0 0 0-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 0 1 8.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07M12 6.375a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z" />
                                      </svg>

                                      <div className="w-full text-xs font-semibold">Plusieur personne</div>
                                    </div>
                                  </label>
                                </li>
                              </ul>
                            </div>
                            <label htmlFor="github" className="block mb-2 text-sm font-medium text-white">Lien github</label>
                            <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3">
                              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                                <path strokeLinecap="round" strokeLinejoin="round" d="M13.19 8.688a4.5 4.5 0 0 1 1.242 7.244l-4.5 4.5a4.5 4.5 0 0 1-6.364-6.364l1.757-1.757m13.35-.622 1.757-1.757a4.5 4.5 0 0 0-6.364-6.364l-4.5 4.5a4.5 4.5 0 0 0 1.242 7.244" />
                              </svg>
                            </span>
                              <input type="github" name="github" id="github" placeholder="Entrer le lien github" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="github" onChange={(e) => setLinkGitHub(e.target.value)} />
                            </div>
                            <button type="submit"
                              className="w-full text-[#ffffff] bg-button-hover-bg hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mb-6 transition-all duration-75 ease-out"
                              onClick={createProject}>Ajouter le projet</button>

                          </form>
                        </div>
                      </div>
                    </div>
                    <div className="px-4 py-3 sm:flex sm:flex-row-reverse sm:px-6">
                      <button
                        type="button"
                        data-autofocus
                        onClick={toggleProject}
                        className="mt-3 inline-flex w-full justify-center rounded-md bg-white px-3 py-2 text-sm font-semibold text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 hover:bg-gray-50 sm:mt-0 sm:w-auto"
                      >
                        Fermer
                      </button>
                    </div>
                  </DialogPanel>
                </div>
              </div>
            </Dialog>
          )
        }
      </div>

    </div>
  )
}

```


3. Connexion avec Firebase (Back-End) :
Configurer Firebase dans le fichier (frebaseConfig.js) pour la base de données.

```jsx

import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
import { getStorage } from "firebase/storage";
const firebaseConfig = {
  apiKey: process.env.REACT_APP_FIREBASE_API_KEY,
  authDomain: process.env.REACT_APP_FIREBASE_AUTH_DOMAIN,
  databaseURL: process.env.REACT_APP_FIREBASE_DATABASE_URL,
  projectId: process.env.REACT_APP_FIREBASE_PROJECT_Id,
  storageBucket: process.env.REACT_APP_FIREBASE_STORAGE_BUCKET,
  messagingSenderId: process.env.REACT_APP_FIREBASE_MESSAGING_SENDER_ID,
  appId: process.env.REACT_APP_FIREBASE_APP_ID,
  measurementId: process.env.REACT_APP_FIREBASE_MEASUREMENTID
};
const app = initializeApp(firebaseConfig);
getAnalytics(app);

export const imageDB = getStorage(app)
export default app
```

4. Intégration des Données Firebase :

Ajout de chaque images pour la création du projet  , chaque projet est une réferences contenant des images importer depuis la modal lors de la création du projet

```jsx
 const readProjectFile = async (projects) => {
    const storage = getStorage(app);

    let addFiles = []
    let files = []

    projects.map((projet, index) => {

      addFiles.push(storageRef(storage, `${projet.titre}_images`))
      return addFiles
    })

    let promises = addFiles.map((reference, index) => {
      let path = reference._location.path

      let getReference = list(reference)

      files[path] = [{}]


      return getReference.then(result => {
        result.items.forEach((item, indexImage) => {
          let url = 'https://firebasestorage.googleapis.com/v0/b/' + item._location.bucket + '/o/' + item._location.path.replace('/', '%2F') + '?alt=media'

          files[path].push({
            src: url.replace(' ', '%20'),
            description: projects[index].description,
            title: "Image " + (indexImage + 1),
          })
        })
        files[path].splice(0, 1)

      })
    })

    Promise.all(promises).then(() => {
      return files
    }).catch(err => {
      console.error("Une erreur est survenue: ", err);
    });

    return files
  }
```
Récupérer des données Firestore pour la section "Projects" :
```jsx

useEffect(() => {
    const fetchProjects = async () => {
      const db = getDatabase(app)
      const refDB = dbRef(db, 'projects')
      const snapshot = await get(refDB)

      if (snapshot.exists()) {
        let idKeys = Object.keys(snapshot.val())
        let projects = Object.values(snapshot.val())
        let getAllProject = await readProjectFile(projects)

        let projectsAll = getAllProject


        let project = projects.map((project, index) => { 
          return {
            keyID: idKeys[index],
            titre: project.titre,
            description: project.description,
            checkGallerie: projectsAll[project.titre + '_images'],
            icon: project.icon,
            color: project.color,
            link: project.link,
            member: project.member
          }
        })

        
        setProjects(project)
      }
    };

    fetchProjects()
  }, [])
  let toggleButton = true
  return (
    <div className='py-6 px-8 md:px-32 text-white'>
      <div  
    className='font-bold mb-2 flex items-center align-middle justify-between'>
        <span>{title}</span>
        {
          title === "Mes Projets" ? (
            toggleButton && (
              <button onClick={toggleProject} className="relative inline-flex items-center justify-center p-0.5 overflow-hidden text-sm font-medium text-gray-900 rounded-lg group bg-gradient-to-br from-[#5b637a] to-[#3f5081] group-hover:from-[#5b637a] group-hover:to-[#3f5081] hover:text-white dark:text-white focus:outline-none focus:ring-blue-300 dark:focus:ring-blue-800">
              <span className="relative px-5 py-2.5 transition-all ease-in duration-75 bg-[#272e3e] rounded-md group-hover:bg-opacity-0">
                Ajouter un projet
              </span>
            </button>)
            )
            :
            <></>
        }

      </div>


      
      <div className="grid grid-cols-1 md:grid-cols-2 sm:grid-cols-2 gap-3.5 items-center align-middle h-full">
      
     
      
        {projects.length > 0 && projects.map((item, index) => (
          <div
            key={index} className='flex w-full flex-wrap bg-button-bg gap-5 justify-center h-full border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700'>
        <button style={{ marginTop: '1em' }} onClick={() => setOpenGallerie(index)}>
        <FontAwesomeIcon icon={faImages} color='#4a596e' fontSize={30} className='text-[#4a596e] hover:text-blue-200 transition-all duration-300 ease-in-out' />
        </button>

        { openGallerie === index && (
          <Lightbox 
              plugins={[ Download, Fullscreen, Zoom, Thumbnails, Counter]}
              counter={{ 
                container: { 
                  style: { 
                    top: 0, 
                    bottom: 0 
                  } 
                } 
              }}
              captions={{
                showToggle: true,
                descriptionTextAlign: 'end'
              }}
              open={true}
              close={() => setOpenGallerie(null)}  
              slides={item.checkGallerie}
            />
          )}
            <div className="flex flex-col rounded-lg w-full p-5">
              <div className="text-2xl font-bold text-white pb-6">
                <div className='flex justify-between item'>
                  <p>{item.titre}</p>
                </div>
              </div>
              <div className=" text-[.9em]  text-[#6a7c97]">
                {item.description}
              </div>
              <div className="flex pt-2 gap-2 items-center align-middle">
                <div>
                  <button href="#" className="bg-primary-bg text-[#ffffff] px-3 py-2 rounded-lg inline-flex items-center align-middle">
                    {
                      item.member === "one"
                        ?
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" className="size-5">
                          <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                        </svg>
                        :
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth={1.5} stroke="currentColor" className="size-5">
                          <path strokeLinecap="round" strokeLinejoin="round" d="M15 19.128a9.38 9.38 0 0 0 2.625.372 9.337 9.337 0 0 0 4.121-.952 4.125 4.125 0 0 0-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 0 1 8.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07M12 6.375a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z" />
                        </svg>
                    }
                    <span className='ml-2'>{item.member === "one" ? '1' : 'Plusieurs'}</span>
                  </button>
                </div>
                <div className='flex items-center align-middle'>
                  <button href="#" className='bg-gradient-to-tr bg-primary-bg text-[#ffffff] px-3 py-2 rounded-lg inline-flex items-center align-middle '>
                    <span>
                      {
                        typeof item.icon === "object"
                          ?
                          <FontAwesomeIcon icon={item.icon} color={item.color} fontSize={20} />
                          :
                          <img src={`../assets/images/${item.icon}`} alt="" />
                      }
                    </span>
                  </button>
                  <a href={item.link} target='_blank' rel="noreferrer" className='ml-2 bg-gradient-to-tr bg-primary-bg hover:bg-button-hover-bg cursor-pointer transition-all duration-300 ease-out text-[#ffffff] px-3 py-2 rounded-lg inline-flex items-center align-middle '>
                    <FontAwesomeIcon icon={faGithub} fontSize={25} />
                  </a>
                </div>
                
              </div>
              <div className='mt-2 flex'>
              { item.titre !== "RPGGames" && item.titre !== "Restaurant" && item.titre !== "Events"  && item.titre !== "Auto Ecole" && item.titre !== "html5gaming" ?
                  <button onClick={() => deleteProject(item.keyID, item)} className='bg-red-400 px-5 py-2 rounded-md text-sm cursor-pointer transition-all duration-200 ease-in-out hover:text-red-500 hover:bg-white'>Supprimer ce project</button>
                  : 
                  ''
                }
                </div>
            </div>
          </div>

        ))}

      </div>
        
      <div>
        {
          toggle && (
            <Dialog open={toggle} onClose={toggleProject} className="relative z-10">
              <DialogBackdrop
                transition
                className="fixed inset-0 bg-gray-500 bg-opacity-75 transition-opacity data-[closed]:opacity-0 data-[enter]:duration-300 data-[leave]:duration-200 data-[enter]:ease-out data-[leave]:ease-in"
              />

              <div className="fixed inset-0 z-10 overflow-y-auto">
                <div className="flex justify-center p-4 text-center">
                  <DialogPanel
                    transition
                    className="relative transform overflow-hidden rounded-lg bg-gray-800 text-left shadow-xl transition-all data-[closed]:translate-y-4 data-[closed]:opacity-0 data-[enter]:duration-300 data-[leave]:duration-200 data-[enter]:ease-out data-[leave]:ease-in sm:my-16 sm:w-full sm:max-w-lg data-[closed]:sm:translate-y-0 data-[closed]:sm:scale-95"
                  >
                    <div className="bg-bg-gray-800 px-4 pb-4 pt-5 sm:p-6 sm:pb-4">
                      <div className="sm:flex sm:items-start">
                        <div className="mx-auto flex h-12 w-12 flex-shrink-0 items-center justify-center rounded-full bg-white sm:mx-0 sm:h-10 sm:w-10">
                          <PlusIcon aria-hidden="true" className="h-6 w-6 text-orange-600" fill='#3d4858' />
                        </div>
                        <div className="mb-5 text-center sm:ml-4 sm:mt-0 sm:text-left">
                          <DialogTitle as="h3" className="text-base font-semibold leading-6 text-gray-400">
                            Ajout d'un projet
                          </DialogTitle>
                          <div className="">
                            <p className="text-sm text-gray-500">
                              Les projets ajouter seront afficher dans la rubrique 'projet afficher'
                            </p>
                          </div>
                        </div>


                      </div>
                      <div className='p-1 rounded-sm'>
                        <div className="mx-auto 3xl:p-14 rounded-2xl gap-5">
                          <form className="w-full grid grid-cols-1 xl:grid-cols-1 bg-gray-800 rounded-xl">
                            <div className='flex flex-col md:flex-row gap-2'>
                              <div className="">
                                <label htmlFor="title" className="block mb-2 text-sm font-medium text-white">Titre du projet</label>
                                <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                                  <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                </svg>
                                </span>
                                  <input type="text" name="title" id="title" placeholder="Entrer le titre du projet" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="title" onChange={(e) => setTitre(e.target.value)} />
                                </div>
                              </div>
                              <div className="">
                                <label htmlFor="desc" className="block mb-2 text-sm font-medium text-white">Description du projet</label>
                                <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                                  <path strokeLinecap="round" strokeLinejoin="round" d="M2.25 13.5h3.86a2.25 2.25 0 0 1 2.012 1.244l.256.512a2.25 2.25 0 0 0 2.013 1.244h3.218a2.25 2.25 0 0 0 2.013-1.244l.256-.512a2.25 2.25 0 0 1 2.013-1.244h3.859m-19.5.338V18a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18v-4.162c0-.224-.034-.447-.1-.661L19.24 5.338a2.25 2.25 0 0 0-2.15-1.588H6.911a2.25 2.25 0 0 0-2.15 1.588L2.35 13.177a2.25 2.25 0 0 0-.1.661Z" />
                                </svg>
                                </span>
                                  <input type="desc" name="desc" id="desc" placeholder="Entrer la description du projet" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="desc" onChange={(e) => setDescription(e.target.value)} />
                                </div>
                              </div>
                            </div>
                            <div className="">
                              <label htmlFor="images" className="block mb-2 text-sm font-medium text-white">Image du projet</label>
                              <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" strokeWidth="1.5" className="size-6">
                                <path d="M9.97.97a.75.75 0 0 1 1.06 0l3 3a.75.75 0 0 1-1.06 1.06l-1.72-1.72v3.44h-1.5V3.31L8.03 5.03a.75.75 0 0 1-1.06-1.06l3-3ZM9.75 6.75v6a.75.75 0 0 0 1.5 0v-6h3a3 3 0 0 1 3 3v7.5a3 3 0 0 1-3 3h-7.5a3 3 0 0 1-3-3v-7.5a3 3 0 0 1 3-3h3Z" />
                                <path d="M7.151 21.75a2.999 2.999 0 0 0 2.599 1.5h7.5a3 3 0 0 0 3-3v-7.5c0-1.11-.603-2.08-1.5-2.599v7.099a4.5 4.5 0 0 1-4.5 4.5H7.151Z" />
                              </svg>
                              </span>
                                <input type="file" multiple name="images" id="images" placeholder="Insérer des images lier au projet" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" onChange={(e) => setImages(e.target.files)} />
                              </div>
                            </div>
                            <div className="">
                              <label htmlFor="icones" className="block mb-2 text-sm font-medium text-white">Icones</label>

                              <div className="">

                                <label htmlFor="icones" className="sr-only">Selectionne le language</label>
                                <select id="icones"
                                  className="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-e-lg border-s-gray-100 dark:border-s-gray-700 border-s-2 focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                                >

                                  <option value="">Séléctionne le language</option>
                                  <option value="faHtml5">HTML</option>
                                  <option value="faLaravel">Laravel</option>
                                  <option value="faSymfony">Symfony</option>
                                  <option value="faNodeJs">Node JS</option>
                                  <option value="faReact">React</option>
                                  <option value="faPhp">PHP</option>
                                  <option value="faPython">Python</option>
                                  <option value="faRuby">Ruby</option>
                                  <option value="faVuejs">Vue</option>
                                  <option value="faCss3">CSS</option>
                                  <option value="faJS">Javascript</option>
                                  <option value="faJava">Java</option>
                                  <option value="faBootstrap">Bootstrap</option>
                                  <option value="faTypescript">Typescript</option>
                                  <option value="threeJS">ThreeJS</option>
                                </select>
                              </div>
                            </div>
                            <div className="">
                              <label htmlFor="color_icones" className="block mb-2 text-sm font-medium text-white">Couleur de l'icone du projet</label>
                              <div className="text-gray-400">
                                <input type="color" name="color_icones" id="color_icones" placeholder="#fff" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block p-2.5 rounded-l-lg py-3 px-4" onChange={(e) => setColor(e.target.value)} />
                              </div>
                            </div>
                            <div className="flex justify-between items-center align-middle">
                              <ul className="grid gap-6 md:grid-cols-2 grid-cols-2" onChange={getMember}>
                                <li>
                                  <input type="checkbox" id="option-1" value="one" className="hidden peer" required="" onChange={() => handleCheckboxChange('one')} checked={checkedValue === "one"} />
                                  <label htmlFor="option-1" className="inline-flex items-center justify-between w-full p-5 text-gray-500 bg-white border-2 border-gray-200 rounded-lg cursor-pointer dark:hover:text-gray-300 dark:border-gray-700 peer-checked:border-white hover:text-gray-600 dark:peer-checked:text-gray-300 peer-checked:text-gray-600 hover:bg-gray-50 dark:text-gray-400 dark:bg-gray-800 dark:hover:bg-gray-700">
                                    <div className="block">
                                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-5" name='test'>
                                        <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
                                      </svg>
                                      <div className="w-full text-xs font-semibold">1 personne</div>
                                    </div>
                                  </label>
                                </li>
                                <li>
                                  <input type="checkbox" id="option-2" value="all" className="hidden peer" required="" onChange={() => handleCheckboxChange('all')} checked={checkedValue === "all"}/>
                                  <label htmlFor="option-2" className="inline-flex items-center justify-between w-full p-5 text-gray-500 bg-white border-2 border-gray-200 rounded-lg cursor-pointer dark:hover:text-gray-300 dark:border-gray-700 peer-checked:border-white hover:text-gray-600 dark:peer-checked:text-gray-300 peer-checked:text-gray-600 hover:bg-gray-50 dark:text-gray-400 dark:bg-gray-800 dark:hover:bg-gray-700">
                                    <div className="block">
                                      <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                                        <path strokeLinecap="round" strokeLinejoin="round" d="M15 19.128a9.38 9.38 0 0 0 2.625.372 9.337 9.337 0 0 0 4.121-.952 4.125 4.125 0 0 0-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 0 1 8.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07M12 6.375a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z" />
                                      </svg>

                                      <div className="w-full text-xs font-semibold">Plusieur personne</div>
                                    </div>
                                  </label>
                                </li>
                              </ul>
                            </div>
                            <label htmlFor="github" className="block mb-2 text-sm font-medium text-white">Lien github</label>
                            <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3">
                              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                                <path strokeLinecap="round" strokeLinejoin="round" d="M13.19 8.688a4.5 4.5 0 0 1 1.242 7.244l-4.5 4.5a4.5 4.5 0 0 1-6.364-6.364l1.757-1.757m13.35-.622 1.757-1.757a4.5 4.5 0 0 0-6.364-6.364l-4.5 4.5a4.5 4.5 0 0 0 1.242 7.244" />
                              </svg>
                            </span>
                              <input type="github" name="github" id="github" placeholder="Entrer le lien github" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="github" onChange={(e) => setLinkGitHub(e.target.value)} />
                            </div>
                            <button type="submit"
                              className="w-full text-[#ffffff] bg-button-hover-bg hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mb-6 transition-all duration-75 ease-out"
                              onClick={createProject}>Ajouter le projet</button>

                          </form>
                        </div>
                      </div>
                    </div>
                    <div className="px-4 py-3 sm:flex sm:flex-row-reverse sm:px-6">
                      <button
                        type="button"
                        data-autofocus
                        onClick={toggleProject}
                        className="mt-3 inline-flex w-full justify-center rounded-md bg-white px-3 py-2 text-sm font-semibold text-gray-900 shadow-sm ring-1 ring-inset ring-gray-300 hover:bg-gray-50 sm:mt-0 sm:w-auto"
                      >
                        Fermer
                      </button>
                    </div>
                  </DialogPanel>
                </div>
              </div>
            </Dialog>
          )
        }
      </div>

    </div>
  )
}
```

5. Ajout des Animations avec Framer Motion :
   
Ajouter des animations pour la navigation fluide entre sections :

```jsx

import React, { useState } from 'react'
import { AnimatePresence, motion } from 'framer-motion'
import { Squash as Hamburger } from "hamburger-react"

export default function Header({ scrollToSection }) {

  const [menuVisible, setMenuVisible] = useState(false)

  return (
    <div className='w-full h-full absolute bg-[linear-gradient(to_right,_#1f2937,_#2e3f5c)] header'>
      <motion.header
        initial={{
          y: -29,
          opacity: 0
        }}
        animate={{
          y: 0,
          opacity: 100
        }}
        transition={{
          ease: 'easeIn',
          duration: 2
        }} className='flex justify-between items-center py-6 px-8 md:px-32  fixed z-40 w-full [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] backdrop-blur-sm bg-[rgba(0,_0,_0,_0.5)] text-white drop-shadow-md'>
        <div>
          <div className='text-white'>Amine Meddour</div>
          <span className='text-white'>DEVELOPPEUR WEB FULLSTACK</span>
        </div>


        <ul className={`hidden xl:flex items-center gap-12 font-semibold text-sm`} style={{ transition: "transform 0.3s ease, opacity 0.3s ease" }} >
          <button className='p-3 hover:bg-white hover:text-[#243147] rounded-md transition-all cursor-pointer'>
            Accueil
          </button>
          <button onClick={() => scrollToSection('about')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            A propos
          </button>
          <button onClick={() => scrollToSection('competences')} className='p-3 cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            Compétences
          </button>
          <button onClick={() => scrollToSection('projects')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            Projets
          </button>
          <button onClick={() => scrollToSection('contact')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            <span>Contact</span>
          </button>
        </ul>
        
        <div className='xl:hidden flex text-5xl cursor-pointer'>
          <Hamburger toggled={menuVisible} size={25} toggle={setMenuVisible} color='white' />
        </div>

        <AnimatePresence>
          {menuVisible && (
            <motion.div
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            exit={{ opacity: 0 }}
            transition={{ duration: 0.5 }}
              className={`absolute xl:hidden top-24 left-0 w-full [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] backdrop-blur-sm bg-[rgba(0,_0,_0,_0.5)] flex flex-col items-center gap-6 font-semibold text-lg transform z-40 transition-transform`}
              style={{ transition: "transform 0.3s ease , opacity .3s ease" }}
            >
              <motion.button
               initial={{ scale: 0, opacity: 0 }}
               animate={{ scale: 1, opacity: 1 }}
               transition={{
                 type: "spring",
                 stiffness: 260,
                 damping: 20,
                 delay: 0.1 + 0 / 10,
               }} 
                onClick={() => setMenuVisible(!menuVisible)} className='p-4 w-full list-none hover:bg-white hover:text-[#243147] transition-all cursor-pointer text-center [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Accueil
              </motion.button>
              <motion.button
               initial={{ scale: 0, opacity: 0 }}
               animate={{ scale: 1, opacity: 1 }}
               transition={{
                 type: "spring",
                 stiffness: 260,
                 damping: 20,
                 delay: 0.1 + 1 / 10,
               }}  
                onClick={() => {
                scrollToSection('about')
                setMenuVisible(!menuVisible)
              }
              } className='p-4 list-none text-center w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                A propos
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 2 / 10,
                }}  
                onClick={() => {
                  scrollToSection('competences')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center list-none w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Compétences
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 3 / 10,
                }}  
                onClick={() => {
                  scrollToSection('projects')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center w-full list-none hover:bg-white hover:text-[#243147] rounded-md transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Projets
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 4 / 10,
                }}  
                onClick={() => {
                  scrollToSection('contact')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center list-none w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                <span>Contact</span>
              </motion.button>
            </motion.div>
          )}
        </AnimatePresence >


      </motion.header>
    </div>
  )
}
```

Ajout d'une fonction permettant d'agrandir l'image via framer-motion au moment ou on survole la compétence
La fonctionne detecte automatiquement si on passe une image ou une icone en paramètre grace au 4 ème paramètre
```jsx
function hoverCompetence(icon, tag, color = null, boolImgOrIcon) {
  return (
    <>
      <motion.div whileHover={{ scale: 1.2 }} className="flex flex-col align-middle items-center justify-center">

        {
          boolImgOrIcon === true ?
            <FontAwesomeIcon icon={icon} color={color} fontSize={50} />
            :
            <img src={`../assets/images/${icon}`} alt="" height={50} width={50} />
        }
        <div>{tag}</div>
      </motion.div>
    </>
  )
}
```

6. Formulaire de Contact via l'api web3form :
```jsx
import { faEnvelope } from '@fortawesome/free-regular-svg-icons'
import { faMobilePhone } from '@fortawesome/free-solid-svg-icons'
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import React, { useState } from 'react'
import Swal from "sweetalert2"

export default function Contact() {
  const [name, setName] = useState("")
  const [email, setEmail] = useState("")
  const [message, setMessage] = useState("")

  const onSubmit = async (event) => {
    event.preventDefault();

    const formData = new FormData(event.target);

    if(name !== "" && email !== "" && message !== ""){

    formData.append("access_key", process.env.REACT_APP_ACCESS_KEY);

    const response = await fetch("https://api.web3forms.com/submit", {
      method: "POST",
      body: formData
    });

    const data = await response.json();
   
    if (data.success) {
      Swal.fire({
        title: "Message Envoyé",
        text: "Ton message à était envoyé avec success",
        icon: 'success'
      })
    } else {
      Swal.fire({
        title: "Message non envoyé",
        text: "Ton message n'à  pas pus etre envoyé car clé manquante pour l'api web3form",
        icon: 'error'
      })

    }
  } else {
    Swal.fire({
      title: "Message non envoyé",
      text: "Ton message n'à  pas pus etre envoyé car le formulaire est incomplet",
      icon: 'error'
    })
  }
  event.target.reset();
  };
  
  return (
    <div className='py-6 px-8 md:px-32 text-white'>
    <div className='mt-5 p-1'>
          <h1 className="text-1xl font-bold text-mintcream my-auto">Contacte-moi</h1>
          <div className="text-sm font-light text-[#5b85c0] pb-8 ">Envie de me recontrer ou de discuté avec moi</div>
    </div>  
    <div className='rounded-sm p-1'>
      <div className="flex flex-col md:flex-row  w-full mx-auto rounded-2xl gap-5">
        <form className="w-full grid grid-cols-1 gap-5 bg-gray-800 rounded-xl p-4"  onSubmit={onSubmit} method='POST'>
         <div className='flex gap-2 w-full'> 
          <input type="hidden" name="access_key" value={process.env.REACT_APP_ACCESS_KEY} className='w-full' />
            <div className="pb-6 w-full">
              <label htmlFor="prenom" className="block mb-2 text-sm font-medium text-mintcream">Name</label>
              <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
              </svg>
              </span>
                <input type="text" name="prenom" id="prenom" placeholder="Enter Name" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-prenom" onChange={(e) => setName(e.currentTarget.value)} />
              </div>
            </div>
            <div className="pb-6 w-full">
              <label htmlFor="email" className="block mb-2 text-sm font-medium text-mintcream">Email</label>
              <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                <path strokeLinecap="round" strokeLinejoin="round" d="M2.25 13.5h3.86a2.25 2.25 0 0 1 2.012 1.244l.256.512a2.25 2.25 0 0 0 2.013 1.244h3.218a2.25 2.25 0 0 0 2.013-1.244l.256-.512a2.25 2.25 0 0 1 2.013-1.244h3.859m-19.5.338V18a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18v-4.162c0-.224-.034-.447-.1-.661L19.24 5.338a2.25 2.25 0 0 0-2.15-1.588H6.911a2.25 2.25 0 0 0-2.15 1.588L2.35 13.177a2.25 2.25 0 0 0-.1.661Z" />
              </svg>
              </span>
                <input type="email" name="email" id="email" placeholder="Enter Email" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-email" onChange={(e) => setEmail(e.currentTarget.value)}/>
              </div>
            </div>
         </div>
            <div className="pb-6">
            <label htmlFor="message" className="block mb-2 text-sm font-medium text-mintcream">Message</label>
            <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="lucide lucide-mail"><rect width="20" height="16" x="2" y="4" rx="2"></rect><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path></svg></span>
              <input type="text" name="message" id="message" placeholder="Enter Message" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-message" onChange={(e) => setMessage(e.currentTarget.value)}/>
            </div>
          </div>
          <button type="submit" className="w-full text-[#ffffff] bg-button-hover-bg hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mb-6 transition-all duration-75 ease-out">Envoyé</button>

        </form> 
        <div className='w-full'>
       
       <div className='bg-gray-800 rounded-xl p-4 flex flex-col justify-between gap-2'>
          
            <div className='flex items-center gap-5'>
              <FontAwesomeIcon icon={faEnvelope} color='mintcream' className='text-[1.4em]' />
              <span>amine.meddour@epitech.eu</span>
            </div>
            
            <div className='flex items-center gap-5'>
              <FontAwesomeIcon icon={faMobilePhone} color='mintcream' className='text-[1.4em]' />
              <span>+33 04 45 21 56 36</span>
            </div>

       </div>
        </div>
      </div>
    </div>
    </div>
  )
}
```

7. Tests et Validation :
   Utilisatation de Jest et React Testing Library pour tester la soumission du formulaire.

```jsx
import { render, screen, fireEvent, waitFor } from "@testing-library/react"
import { act } from "react"
import Contact from "../components/Contact"

beforeEach(() => {
    // Mock de fetch pour tous les tests
    global.fetch = jest.fn(() =>
      Promise.resolve({
        ok: true,
        json: () => Promise.resolve({ message: 'Success' }),
      })
    );
  });
  
  afterEach(() => {
    jest.clearAllMocks(); // Réinitialise les mocks après chaque test
  });

test("Envoye d'email via une soumission d'un formulaire", async () => {
    
    
    await act(async () => {
            const onSubmit = jest.fn(); // Fonction mock pour tester la soumission
            render(<Contact onSubmit={onSubmit} />); // Rendu du composant
            
        });


        let nameVal = "John Doe"
        let emailVal = "john@tes.fr"
        let messageVal = "Test message"

        const input =  await screen.findByPlaceholderText('Enter Name');
        const email =  await screen.findByPlaceholderText('Enter Email');
        const message =  await screen.findByPlaceholderText('Enter Message');

        
        fireEvent.change(input, { target: { value: nameVal } });
        fireEvent.change(email, { target: { value: emailVal } });
        fireEvent.change(message, { target: { value: messageVal  } });

        const button = screen.getByRole('button', { name: "Envoyé"})
        fireEvent.click(button)


        await waitFor(() => expect(global.fetch).toHaveBeenCalledTimes(1));

        const fetchCall = global.fetch.mock.calls[0];
        const url = fetchCall[0];
        const options = fetchCall[1];

        expect(url).toBe('https://api.web3forms.com/submit');
        expect(options.method).toBe('POST');

        const formData = options.body;
        expect(formData instanceof FormData).toBe(true);

        expect(formData.get('prenom')).toBe(nameVal); 
        expect(formData.get('email')).toBe(emailVal);
        expect(formData.get('message')).toBe(messageVal);

})
```

 * Intégration des différents éléments de la solution web

         1. Structure du Projet :
         React pour la gestion des composants côté front-end.
         Firebase pour la gestion des données et services back-end.
         2. Intégration des Composants React :
         Créer des composants pour chaque section (header, about, skills, experience, contact).
         Utiliser des routes pour naviguer entre ces sections, si nécessaire.
         3. Connexion Firebase :
         Utiliser Firebase pour l'authentification et les données de Firestore. Chaque composant peut faire appel à des services Firebase pour récupérer ou envoyer des données (ex. : liste des compétences, formulaire de contact).
         4. Ajout des Animations :
         Implémenter des transitions fluides et animations avec Framer Motion ou une autre bibliothèque d’animations.
         5. Gestion du Contenu Dynamique :
         Utiliser les services Firebase pour stocker et récupérer dynamiquement les données telles que les projets, expériences professionnelles, et compétences.
         6. Formulaire de Contact :
         Utiliser un composant pour gérer l’envoi de données (message, coordonnées) via Firebase Firestore, et créer un système d’alerte ou de validation après soumission.
         7. Test et Validation :
         Tester les différentes fonctionnalités (affichage des sections, navigation, récupération de données, soumission de formulaire).
         8. Déploiement :
         Déployer l'application via Firebase Hosting, s’assurer que tous les services sont correctement configurés pour la production.

 * Implémentation de la partie "front-end"

      Initialisation du Projet :

               Créer le projet avec npx create-react-app pour générer la structure de base.
               Organiser les dossiers en séparant les composants, styles, et le test unitaire.
   
      2. Création des Composants :

               Header : Créer un composant qui contient la barre de navigation (ex. : "À propos", "Compétences", "Contact", "Acceuil", "Projets", "Contact").
               Sections : Pour le composant Project, Compétences et Contact créer des composants React autonomes.
         
```jsx
import React, { useState } from 'react'
import { AnimatePresence, motion } from 'framer-motion'
import { Squash as Hamburger } from "hamburger-react"

export default function Header({ scrollToSection }) {

  const [menuVisible, setMenuVisible] = useState(false)

  return (
    <div className='w-full h-full absolute bg-[linear-gradient(to_right,_#1f2937,_#2e3f5c)] header'>
      <motion.header
        initial={{
          y: -29,
          opacity: 0
        }}
        animate={{
          y: 0,
          opacity: 100
        }}
        transition={{
          ease: 'easeIn',
          duration: 2
        }} className='flex justify-between items-center py-6 px-8 md:px-32  fixed z-40 w-full [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] backdrop-blur-sm bg-[rgba(0,_0,_0,_0.5)] text-white drop-shadow-md'>
        <div>
          <div className='text-white'>Amine Meddour</div>
          <span className='text-white'>DEVELOPPEUR WEB FULLSTACK</span>
        </div>


        <ul className={`hidden xl:flex items-center gap-12 font-semibold text-sm`} style={{ transition: "transform 0.3s ease, opacity 0.3s ease" }} >
          <button className='p-3 hover:bg-white hover:text-[#243147] rounded-md transition-all cursor-pointer'>
            Accueil
          </button>
          <button onClick={() => scrollToSection('about')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            A propos
          </button>
          <button onClick={() => scrollToSection('competences')} className='p-3 cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            Compétences
          </button>
          <button onClick={() => scrollToSection('projects')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            Projets
          </button>
          <button onClick={() => scrollToSection('contact')} className='p-3  cursor-pointer hover:bg-white hover:text-[#243147] rounded-md transition-all'>
            <span>Contact</span>
          </button>
        </ul>
        
        <div className='xl:hidden flex text-5xl cursor-pointer'>
          <Hamburger toggled={menuVisible} size={25} toggle={setMenuVisible} color='white' />
        </div>

        <AnimatePresence>
          {menuVisible && (
            <motion.div
            initial={{ opacity: 0 }}
            animate={{ opacity: 1 }}
            exit={{ opacity: 0 }}
            transition={{ duration: 0.5 }}
              className={`absolute xl:hidden top-24 left-0 w-full [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] backdrop-blur-sm bg-[rgba(0,_0,_0,_0.5)] flex flex-col items-center gap-6 font-semibold text-lg transform z-40 transition-transform`}
              style={{ transition: "transform 0.3s ease , opacity .3s ease" }}
            >
              <motion.button
               initial={{ scale: 0, opacity: 0 }}
               animate={{ scale: 1, opacity: 1 }}
               transition={{
                 type: "spring",
                 stiffness: 260,
                 damping: 20,
                 delay: 0.1 + 0 / 10,
               }} 
                onClick={() => setMenuVisible(!menuVisible)} className='p-4 w-full list-none hover:bg-white hover:text-[#243147] transition-all cursor-pointer text-center [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Accueil
              </motion.button>
              <motion.button
               initial={{ scale: 0, opacity: 0 }}
               animate={{ scale: 1, opacity: 1 }}
               transition={{
                 type: "spring",
                 stiffness: 260,
                 damping: 20,
                 delay: 0.1 + 1 / 10,
               }}  
                onClick={() => {
                scrollToSection('about')
                setMenuVisible(!menuVisible)
              }
              } className='p-4 list-none text-center w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                A propos
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 2 / 10,
                }}  
                onClick={() => {
                  scrollToSection('competences')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center list-none w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Compétences
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 3 / 10,
                }}  
                onClick={() => {
                  scrollToSection('projects')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center w-full list-none hover:bg-white hover:text-[#243147] rounded-md transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                Projets
              </motion.button>
              <motion.button
                initial={{ scale: 0, opacity: 0 }}
                animate={{ scale: 1, opacity: 1 }}
                transition={{
                  type: "spring",
                  stiffness: 260,
                  damping: 20,
                  delay: 0.1 + 4 / 10,
                }}  
                onClick={() => {
                  scrollToSection('contact')
                  setMenuVisible(!menuVisible)
              }
              } className='p-4 text-center list-none w-full hover:bg-white hover:text-[#243147] transition-all cursor-pointer [box-shadow:0_2px_4px_rgba(0,_0,_0,_0.5)] bg-[rgba(38,49,80,0.5)]'>
                <span>Contact</span>
              </motion.button>
            </motion.div>
          )}
        </AnimatePresence >


      </motion.header>
    </div>
  )
}
```

3. Gestion des Données Dynamiques :

Récupération dynamiquement de tous les projets via la base de donnée de firebase.

```jsx
const fetchProjects = async () => {
      const db = getDatabase(app)
      const refDB = dbRef(db, 'projects')
      const snapshot = await get(refDB)

      if (snapshot.exists()) {
        let idKeys = Object.keys(snapshot.val())
        let projects = Object.values(snapshot.val())
        let getAllProject = await readProjectFile(projects)

        let projectsAll = getAllProject


        let project = projects.map((project, index) => { 
          return {
            keyID: idKeys[index],
            titre: project.titre,
            description: project.description,
            checkGallerie: projectsAll[project.titre + '_images'],
            icon: project.icon,
            color: project.color,
            link: project.link,
            member: project.member
          }
        })

        
        setProjects(project)
      }
    };

    fetchProjects()
  }, [])
```

4. Ajout de l'Interactivité (Formulaire de Contact) :
Créer un formulaire qui envoie les données à l'api web3form :
```jsx
import { faEnvelope } from '@fortawesome/free-regular-svg-icons'
import { faMobilePhone } from '@fortawesome/free-solid-svg-icons'
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import React, { useState } from 'react'
import Swal from "sweetalert2"

export default function Contact() {
  const [name, setName] = useState("")
  const [email, setEmail] = useState("")
  const [message, setMessage] = useState("")

  const onSubmit = async (event) => {
    event.preventDefault();

    const formData = new FormData(event.target);

    if(name !== "" && email !== "" && message !== ""){

    formData.append("access_key", process.env.REACT_APP_ACCESS_KEY);

    const response = await fetch("https://api.web3forms.com/submit", {
      method: "POST",
      body: formData
    });

    const data = await response.json();
   
    if (data.success) {
      Swal.fire({
        title: "Message Envoyé",
        text: "Ton message à était envoyé avec success",
        icon: 'success'
      })
    } else {
      Swal.fire({
        title: "Message non envoyé",
        text: "Ton message n'à  pas pus etre envoyé car clé manquante pour l'api web3form",
        icon: 'error'
      })

    }
  } else {
    Swal.fire({
      title: "Message non envoyé",
      text: "Ton message n'à  pas pus etre envoyé car le formulaire est incomplet",
      icon: 'error'
    })
  }
  event.target.reset();
  };
  
  return (
    <div className='py-6 px-8 md:px-32 text-white'>
    <div className='mt-5 p-1'>
          <h1 className="text-1xl font-bold text-mintcream my-auto">Contacte-moi</h1>
          <div className="text-sm font-light text-[#5b85c0] pb-8 ">Envie de me recontrer ou de discuté avec moi</div>
    </div>  
    <div className='rounded-sm p-1'>
      <div className="flex flex-col md:flex-row  w-full mx-auto rounded-2xl gap-5">
        <form className="w-full grid grid-cols-1 gap-5 bg-gray-800 rounded-xl p-4"  onSubmit={onSubmit} method='POST'>
         <div className='flex gap-2 w-full'> 
          <input type="hidden" name="access_key" value={process.env.REACT_APP_ACCESS_KEY} className='w-full' />
            <div className="pb-6 w-full">
              <label htmlFor="prenom" className="block mb-2 text-sm font-medium text-mintcream">Name</label>
              <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                <path strokeLinecap="round" strokeLinejoin="round" d="M15.75 6a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0ZM4.501 20.118a7.5 7.5 0 0 1 14.998 0A17.933 17.933 0 0 1 12 21.75c-2.676 0-5.216-.584-7.499-1.632Z" />
              </svg>
              </span>
                <input type="text" name="prenom" id="prenom" placeholder="Enter Name" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-prenom" onChange={(e) => setName(e.currentTarget.value)} />
              </div>
            </div>
            <div className="pb-6 w-full">
              <label htmlFor="email" className="block mb-2 text-sm font-medium text-mintcream">Email</label>
              <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" strokeWidth="1.5" stroke="currentColor" className="size-6">
                <path strokeLinecap="round" strokeLinejoin="round" d="M2.25 13.5h3.86a2.25 2.25 0 0 1 2.012 1.244l.256.512a2.25 2.25 0 0 0 2.013 1.244h3.218a2.25 2.25 0 0 0 2.013-1.244l.256-.512a2.25 2.25 0 0 1 2.013-1.244h3.859m-19.5.338V18a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18v-4.162c0-.224-.034-.447-.1-.661L19.24 5.338a2.25 2.25 0 0 0-2.15-1.588H6.911a2.25 2.25 0 0 0-2.15 1.588L2.35 13.177a2.25 2.25 0 0 0-.1.661Z" />
              </svg>
              </span>
                <input type="email" name="email" id="email" placeholder="Enter Email" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-email" onChange={(e) => setEmail(e.currentTarget.value)}/>
              </div>
            </div>
         </div>
            <div className="pb-6">
            <label htmlFor="message" className="block mb-2 text-sm font-medium text-mintcream">Message</label>
            <div className="relative text-gray-400"><span className="absolute inset-y-0 left-0 flex items-center p-1 pl-3"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className="lucide lucide-mail"><rect width="20" height="16" x="2" y="4" rx="2"></rect><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path></svg></span>
              <input type="text" name="message" id="message" placeholder="Enter Message" className="pl-12 mb-2 bg-gray-50 text-gray-600 border focus:border-transparent border-gray-300 sm:text-sm rounded-lg ring ring-transparent focus:ring-1 focus:outline-none focus:ring-gray-400 block w-full p-2.5 rounded-l-lg py-3 px-4" autoComplete="new-message" onChange={(e) => setMessage(e.currentTarget.value)}/>
            </div>
          </div>
          <button type="submit" className="w-full text-[#ffffff] bg-button-hover-bg hover:bg-gray-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mb-6 transition-all duration-75 ease-out">Envoyé</button>

        </form> 
        <div className='w-full'>
       
       <div className='bg-gray-800 rounded-xl p-4 flex flex-col justify-between gap-2'>
          
            <div className='flex items-center gap-5'>
              <FontAwesomeIcon icon={faEnvelope} color='mintcream' className='text-[1.4em]' />
              <span>amine.meddour@epitech.eu</span>
            </div>
            
            <div className='flex items-center gap-5'>
              <FontAwesomeIcon icon={faMobilePhone} color='mintcream' className='text-[1.4em]' />
              <span>+33 04 45 21 56 36</span>
            </div>

       </div>
        </div>
      </div>
    </div>
    </div>
  )
}
```


6. Test et Optimisation :

         Tester l'envoi d'email via web3form.
   
8. Déploiement du Front-End :

Déployement du site web via netlify , ajout de github  action via le deploy.yml

```yml

name: Deploy react app portfolio

on:
  push:
    branches:
      - main
  release:
      types: [created]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        
        with:
          node-version: 20
          registry-url: 'https://registry.npmjs.org/'

      - name: Authenticate to npm
        run: echo "//registry.npmjs.org/:_authToken=${{ secrets.NPM_TOKEN }}" > ~/.npmrc
      - run: npm ci
      - run: npm test
      - name: Deploy React Portfolio app
        run: curl -X POST -d {} ${{ secrets.NETLIFY_BUILD_HOOK }}
```

 * Implémentation de la logique et de la base de données

 * Implémentation des règles d'authentification

 * Déploiement d'une application web en utilisant un serveur

      1. Préparation de l'Environnement :
         
               Installer un serveur (Apache)
               Configurer l’environnement en installant les dépendances requises (Node.js).
         
      3. Transfert des Fichiers :
      
               Envoyer les fichiers du projet vers le serveur, par exemple via FTP ou SCP.
      
      4. Configuration du Serveur :

               Configurer le serveur pour pointer vers le répertoire de l’application et gérer les routes.
               Installer un certificat SSL pour la sécurité (Let's Encrypt).

      4. Base de Données :

               L'application utilise une base de données, configure et migre les données vers le serveur de production MySQL.

      5. Déploiement Automatisé (optionnel) :

               Utilisation de GitHub Actions pour automatiser les déploiements.




Lancement de l’Application :
Lancer le serveur Node.js sur le port défini (ici 3000) :

```bash
npm start
```
Après configuration, l'application sera accessible via http://localhost:3000.

<p style="color:blue">**3. Déployer un Système d’Assurance Qualité tout au long du Cycle de Vie d’une Solution Web**</p>


 * Rédaction d'une documentation technique à destination des équipes parties prenantes :
1. Introduction
Cette documentation présente les aspects techniques du projet, incluant l'architecture, les technologies utilisées, et les processus de développement. Elle est destinée aux équipes et parties prenantes impliquées dans le projet.

2. Architecture de la Solution
Front-end : Développé avec React.
Back-end : Utilisation de Firebase pour la gestion des données et de l'authentification.
Structure des Sections :
Header
À propos
Compétences
Expériences Professionnelles et Formations
Contact
Footer
3. Technologies Utilisées
Langages : JavaScript, HTML, CSS.
Bibliothèques : React, Firebase, Framer Motion pour les animations.
Outils : Git pour le versionnage, Visual Studio Code pour le développement.
4. Processus de Développement
Environnement de travail : Mise en place d'outils de collaboration (Slack, Trello).
Gestion des versions : Utilisation de Git avec des branches pour les nouvelles fonctionnalités.
5. Déploiement
Hébergement : Déploiement sur Firebase Hosting.
Configuration : Assurer que les routes et les services sont correctement configurés.
6. Tests et Validation
Tests unitaires : Utilisation de Jest pour tester les composants.
Tests fonctionnels : Vérification du fonctionnement global de l’application.

 * Rédaction d'une documentation utilisateur pour apporter un support aux utilisateurs :

1. Accès à l'Application
URL de Connexion : [Lien vers l'application]
Création d'un Compte : Instructions pour l'inscription et l'authentification.
2. Navigation dans l'Application
Interface Utilisateur : Description des différentes sections (Header, À propos, Compétences, Expériences, Contact, Footer).
Comment Naviguer : Explication sur la façon d'accéder aux différentes sections.
3. Utilisation des Fonctionnalités
Ajouter une Compétence : Étapes pour ajouter une compétence via le formulaire.
Envoyer un Message : Instructions pour remplir et envoyer le formulaire de contact.
4. Résolution des Problèmes
FAQ : Réponses aux questions courantes.
Contact Support : Informations pour contacter le support technique (email, téléphone).
5. Mises à Jour et Feedback
Mises à Jour de l'Application : Comment recevoir des notifications sur les nouvelles fonctionnalités.
Donner son Avis : Procédure pour soumettre des commentaires sur l'application.

 * Monitoring du lancement d'une solution web, en recueillant les retours utilisateurs :

1. Métriques de Performance
Suivre les indicateurs clés (temps de chargement, taux d'engagement).
Utiliser des outils d'analyse (Google Analytics, Hotjar).
2. Collecte de Retours Utilisateurs
Sondages et Questionnaires : Envoyer des formulaires après utilisation pour recueillir des avis.
Feedback Direct : Intégrer un bouton de retour sur l'interface utilisateur pour faciliter les commentaires.
3. Analyse des Retours
Regrouper et analyser les retours pour identifier les points à améliorer.
Évaluer la satisfaction générale des utilisateurs et ajuster les fonctionnalités en conséquence.
4. Rapports de Suivi
Rédiger des rapports réguliers pour partager les résultats avec les parties prenantes.
Discuter des améliorations à apporter basées sur les données collectées.

 * Identification des améliorations qualitatives et de performance d'une solution web :

Optimisation des Temps de Chargement :

Réduire la taille des fichiers (images, scripts).
Utiliser le caching et un CDN (Content Delivery Network).
Amélioration de l'Interface Utilisateur (UI) :

Simplifier la navigation et améliorer l'ergonomie.
Intégrer des animations fluides pour une meilleure expérience.
Accessibilité :

Assurer que la solution respecte les normes d'accessibilité (WCAG).
Ajouter des alternatives textuelles pour les médias.
Sécurité :

Mettre à jour régulièrement les dépendances.
Implémenter des mesures de sécurité robustes (SSL, protections contre les attaques).
Feedback Utilisateur :

Collecter des retours sur l'utilisation de l'application pour identifier les points d'amélioration.
Analyser les données d’utilisation pour optimiser les fonctionnalités.
Tests et Validation :

Réaliser des tests A/B pour évaluer l'efficacité des modifications.
Suivre les erreurs et les problèmes rapportés par les utilisateurs pour ajuster rapidement la solution.

 * Analyse de la qualité de l’ergonomie et de l’accessibilité de la solution :

1. Ergonomie
Navigation Intuitive : Vérifier si les utilisateurs peuvent trouver facilement les informations.
Clarté des Éléments : S’assurer que les boutons et liens sont clairement identifiables.
Retour Visuel : Fournir des indications visuelles lors des interactions (hover, clic).
2. Accessibilité
Conformité aux Normes WCAG : Évaluer la solution par rapport aux niveaux AA ou AAA des WCAG.
Utilisation de Couleurs Contrastées : Vérifier la lisibilité pour les utilisateurs malvoyants.
Navigation au Clavier : Tester si toutes les fonctionnalités sont accessibles via le clavier.
3. Tests Utilisateurs
Réaliser des tests avec des utilisateurs ayant différents niveaux de compétences et handicaps pour recueillir des feedbacks sur l’ergonomie et l’accessibilité.

 * Rédaction d'un document argumentatif en listant des propositions d'améliorations :

Document Argumentatif : Propositions d'Améliorations pour la Solution Web
Introduction
Dans le cadre de l'optimisation de notre solution web, plusieurs axes d'amélioration ont été identifiés. Ces propositions visent à améliorer l'ergonomie, la performance et l'accessibilité de l'application, tout en répondant aux besoins des utilisateurs.

Propositions d'Amélioration
Optimisation des Temps de Chargement

Compression des Images : Réduire la taille des fichiers pour accélérer le chargement.
Mise en Cache : Utiliser des techniques de mise en cache pour diminuer le temps d'accès aux ressources.
Amélioration de l'Interface Utilisateur (UI)

Refonte du Design : Moderniser l'interface pour rendre la navigation plus intuitive.
Consistance des Éléments Visuels : Assurer que tous les éléments respectent une charte graphique cohérente.
Accessibilité Renforcée

Tests d'Accessibilité : Effectuer des audits pour identifier et corriger les barrières d'accès.
Alternatives Textuelles : Ajouter des descriptions pour les images et les médias afin de soutenir les utilisateurs malvoyants.
Collecte de Feedback Utilisateur

Sondages Intégrés : Mettre en place des formulaires de feedback directement dans l'application.
Analyse des Données d'Utilisation : Étudier les comportements des utilisateurs pour identifier les points de friction.
Formation et Support

Documentation Utilisateur : Créer des guides détaillés pour aider les utilisateurs à naviguer dans la solution.
Sessions de Formation : Proposer des formations pour familiariser les utilisateurs avec les nouvelles fonctionnalités.
