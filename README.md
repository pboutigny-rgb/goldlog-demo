# GoldLog · version de démonstration

**[▶ Ouvrir la démo en ligne](https://VOTRE-PSEUDO.github.io/goldlog-demo/)** (aucune installation, fonctionne dans le navigateur)

GoldLog est un poste de pilotage logistique conçu pour une PME industrielle suisse qui exporte dans le monde entier. Il réunit en un seul outil ce qui était auparavant dispersé entre mails, tableurs et ERP : les demandes de transport des collègues, les packing lists, la douane, les retours fournisseurs et l'évacuation des déchets.

Ce dépôt contient **uniquement une version de démonstration** : une page web autonome qui reproduit les écrans et les principaux enchaînements de l'outil. **La société (Alpenklang SA), les personnes, les clients, les produits et tous les chiffres sont fictifs.** Le code de l'outil utilisé en production n'est pas publié.

![Accueil](captures/01-accueil.png)

## Le problème de départ

Dans une petite équipe logistique, une expédition internationale mobilise beaucoup d'allers-retours : un collègue envoie sa demande par mail, la logistique relance pour obtenir les dimensions ou la facture, consulte plusieurs transporteurs, ressaisit les informations dans la packing list puis dans les documents de douane, et le demandeur relance à son tour pour savoir où en est son envoi.

## Ce que GoldLog change

- **Un portail pour les demandeurs** : les collègues déposent leur demande dans un formulaire guidé (destinataire, marchandise, colis, urgence), suivent son avancement et ajoutent remarques et documents à toutes les étapes, sans échange de mails.
- **Une alerte dans GoldLog** à chaque nouvelle demande ou modification.
- **Un traitement par étapes** : brouillon de demande de cotation aux transporteurs, choix de l'offre, transport, départ validé en un clic. Les mails sont toujours préparés en brouillon et relus avant envoi.
- **Des dossiers reliés** : la demande de transport, la packing list et leurs pièces jointes forment un seul dossier.
- **La gestion des déchets illustrée** : déchet, contenant et quantité en quelques clics, brouillon prêt pour le prestataire.
- **Le pilotage** : tableau de bord des tâches du jour, traçabilité par numéro de série, statistiques de volumes et de coûts.

| Demandes de transport | Traitement d'une demande |
|---|---|
| ![Tableau de suivi](captures/02-demandes-transport.png) | ![Fiche de traitement](captures/03-traitement-demande.png) |

| Portail des demandeurs et alerte | Gestion des déchets |
|---|---|
| ![Portail](captures/04-portail-et-alerte.png) | ![Déchets](captures/05-gestion-dechets.png) |

## Parcourir la démo

1. Ouvrez la démo et cliquez sur **▶ Visite guidée** : neuf étapes commentées présentent les modules.
2. Dans **Portail des demandeurs**, déposez une demande ou ajoutez une remarque : l'alerte apparaît aussitôt côté logistique.
3. Dans **Demandes de transport**, ouvrez une demande, créez le brouillon de cotation, puis validez un départ.
4. **Réinitialiser la démo** remet les données de départ. Rien n'est envoyé ni enregistré : tout se passe dans votre navigateur.

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | La démo complète, en un seul fichier autonome |
| `captures/` | Captures d'écran utilisées dans cette page |

## Méthode

L'outil a été conçu par un responsable logistique, au plus près des besoins du terrain, et développé avec l'aide d'un assistant d'intelligence artificielle (Claude, d'Anthropic) : chaque évolution part d'un irritant opérationnel concret, est testée puis livrée par versions successives.

## Auteur et droits

Conçu par **Pierre-Damien Boutigny**, responsable logistique et entrepôt.
Version de démonstration publiée à titre de présentation. Tous droits réservés : merci de ne pas réutiliser ce contenu sans autorisation.
