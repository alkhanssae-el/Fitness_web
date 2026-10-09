# Élan Fitness 🏋️

## À propos du projet

Élan Fitness est un petit site web de salle de sport que j’ai créé pour pratiquer HTML et CSS. Le site présente une salle de sport fictive située à Casablanca. Il donne aux visiteurs des informations sur la salle, ses programmes, ses tarifs et les moyens de la contacter.

J’ai essayé de garder un design simple et sportif, avec des détails orange, des photos, des cartes et le même menu de navigation sur chaque page.

## Les pages du projet

- **`index.html`** : la page d’accueil. Elle présente la salle et contient des liens vers les autres pages.
- **`about.html`** : explique les valeurs de la salle et présente quelques-uns de ses avantages.
- **`program.html`** : présente les différentes activités et les formules d’abonnement.
- **`contact.html`** : contient un formulaire de contact.
- **`style.css`** : contient le CSS utilisé pour mettre en forme les pages.
- **`planification.md`** : contient les notes prises pendant la préparation du projet.
- **`img/`** : contient le logo, les photos et les icônes SVG utilisées sur le site.

## Programmes et tarifs

Les programmes présentés sur le site sont :

| Programme | Durée | Niveau indiqué |
| --- | ---: | --- |
| Musculation | 60 minutes | Tous les niveaux |
| Yoga | 75 minutes | Débutant |
| Entraînement cardio | 45 minutes | Intermédiaire |
| Boxe fitness | 50 minutes | Intermédiaire |

Les cartes d’abonnement affichent les tarifs suivants :

| Formule | Prix | Ce qui est inclus |
| --- | ---: | --- |
| Essentiel | 250 MAD/mois | Accès à la salle et deux cours collectifs par semaine |
| Premium | 400 MAD/mois | Accès à la salle, cours collectifs illimités et une évaluation avec un coach |
| Duo | 650 MAD/mois | Accès pour deux personnes et cours collectifs illimités |

Ces tarifs sont des exemples utilisés pour la démonstration. Le site est un projet scolaire/de pratique, pas un vrai service de réservation pour une salle de sport.

## Pourquoi j’ai utilisé ces balises HTML

J’ai utilisé différentes balises HTML pour organiser le contenu et rendre chaque page plus facile à comprendre. Voici à quoi servent les principales balises dans ce projet.

### Structure de base d’une page

| Balise | Pourquoi je l’ai utilisée |
| --- | --- |
| `<!DOCTYPE html>` | Indique au navigateur que le document utilise HTML5. |
| `<html>` | Contient tout le code HTML de la page. L’attribut `lang="fr"` indique au navigateur que le contenu de la page est en français. |
| `<head>` | Contient les informations sur la page qui ne sont pas affichées comme du contenu normal. |
| `<meta>` | Fournit des informations comme l’encodage des caractères, les réglages d’affichage sur mobile et la description de la page. |
| `<title>` | Définit le titre affiché dans l’onglet du navigateur. |
| `<link>` | Relie la page à des fichiers ou ressources externes. Dans ce projet, il permet de charger le CSS, les polices et le favicon. |
| `<body>` | Contient le contenu visible par les visiteurs. |

### Mise en page et contenu

| Balise | Pourquoi je l’ai utilisée |
| --- | --- |
| `<header>` | Contient la partie supérieure de la page, notamment le logo et le menu principal. |
| `<nav>` | Regroupe les liens de navigation pour permettre aux visiteurs de passer d’une page à l’autre. Je l’utilise aussi pour les liens du pied de page. |
| `<main>` | Contient le contenu principal de chaque page, séparé de l’en-tête et du pied de page. |
| `<section>` | Regroupe des éléments qui vont ensemble, comme la section d’accueil ou celle des programmes. |
| `<div>` | Sert de conteneur général. Je l’utilise pour regrouper des éléments afin de pouvoir les organiser et les mettre en forme avec CSS. Cette balise n’a pas de signification particulière à elle seule. |
| `<article>` | Encadre un bloc de contenu qui peut être compris séparément, comme une carte de programme ou d’abonnement. |
| `<footer>` | Contient la partie inférieure de la page, avec des liens supplémentaires et les informations sur le projet ou l’adresse. |

### Textes et listes

| Balise | Pourquoi je l’ai utilisée |
| --- | --- |
| `<h1>` | Définit le titre principal de la page d’accueil. En général, une page doit avoir un titre principal qui indique son sujet. |
| `<h2>` | Définit le titre d’une section principale, comme le formulaire de contact ou une section de page. |
| `<h3>` | Définit un sous-titre pour les éléments d’une section, comme les avantages ou les programmes. |
| `<h4>` | Sert à afficher les noms des formules d’abonnement. |
| `<p>` | Contient des paragraphes et de courts textes, par exemple des descriptions, des libellés et des prix. |
| `<ul>` | Crée une liste à puces. Je l’utilise pour le menu de navigation et les listes des avantages des abonnements. |
| `<li>` | Représente un élément dans une liste, par exemple un lien de navigation ou un avantage d’une formule. |
| `<span>` | Entoure une petite partie du texte pour pouvoir la mettre en forme séparément, par exemple « / mois » à côté d’un prix. |
| `<hr>` | Crée une ligne horizontale. Elle sert de séparation visuelle dans la section de contact. |

### Liens, images et éléments de formulaire

| Balise | Pourquoi je l’ai utilisée |
| --- | --- |
| `<a>` | Crée un lien vers une autre page ou vers une section de la même page. L’attribut `href` indique la destination du lien. |
| `<img>` | Affiche une image, comme le logo, les photos de la salle ou de petites icônes. L’attribut `src` indique le chemin de l’image et `alt` fournit une description si l’image ne peut pas être vue ou ne se charge pas. |
| `<form>` | Regroupe les champs que le visiteur remplit pour envoyer un message. |
| `<input>` | Crée un champ pour saisir des informations comme un nom ou une adresse e-mail. L’attribut `type` détermine le type de champ. |
| `<button>` | Crée un bouton cliquable. Dans le formulaire de contact, il sert à envoyer le formulaire. |

Quelques balises, comme `<link>` et `<meta>`, se trouvent dans `<head>`. La plupart des autres balises sont placées dans `<body>`. Des balises comme `<img>`, `<input>`, `<meta>` et `<link>` n’ont pas besoin de balise de fermeture.

## Comment fonctionne le CSS

Les quatre pages HTML utilisent le même fichier `style.css`. Cela me permet de modifier le style commun à un seul endroit, au lieu de répéter les mêmes règles sur chaque page.

Le CSS sert notamment à gérer :

- les couleurs et les polices ;
- l’en-tête, le menu de navigation et le pied de page ;
- les espacements et la disposition des pages ;
- les cartes des programmes et des abonnements ;
- les boutons, les images et le formulaire de contact.

La couleur principale est l’orange (`#FF6B2C`). Le projet utilise Poppins pour les titres et Inter pour le texte courant. Ces polices sont chargées depuis Google Fonts : elles peuvent donc ne pas s’afficher sans connexion Internet.

## Ce que je pourrais améliorer

Si je continuais ce projet, voici quelques points que j’améliorerais :

- Vérifier que la mise en page fonctionne bien sur les différentes tailles d’écran, notamment sur mobile et tablette.
- Relier le formulaire de contact à un backend ou à un service de formulaire. Pour le moment, il n’envoie pas les messages vers une vraie boîte mail.
- Corriger les liens de contact sur la page Programmes, car la cible `#contact` ne correspond pas actuellement à une section de contact sur cette page.
- Utiliser une balise `<textarea>` pour le message plutôt qu’un `<input>`, car un message peut contenir plusieurs lignes.
- Afficher un message clair lorsque le formulaire est envoyé avec succès ou lorsqu’une erreur se produit.
- Vérifier les descriptions des images pour s’assurer qu’elles sont utiles.
- Remplacer les informations fictives de la salle par des informations réelles avant d’utiliser le site pour une vraie activité.

## Pour terminer

Ce projet m’a permis de pratiquer l’organisation d’un site web en plusieurs pages HTML et l’utilisation d’un seul fichier CSS pour garder un style cohérent. Il s’agit encore d’un projet front-end : il ne comprend pas de comptes membres, de paiements en ligne, de réservations de cours ni de système de contact fonctionnel.