# Phase 1 : L'Ayant Droit (Ancrage et Volonté)

Cette première phase décrit comment l'œuvre originale est protégée et comment les intentions de l'auteur sont traduites pour le système.

## Acte 1 — Cultural ID (L'Identité)
* **Objectif :** Établir une identité unique, inviolable et traçable pour l'œuvre et son propriétaire.
* **Le principe :** L'auteur dépose son œuvre sur l'interface (comme IRL.art). Le système calcule une empreinte numérique unique (un hash SHA-256) à partir du fichier et des métadonnées (titre, auteur, date). L'ensemble est signé avec la clé de l'ayant droit et inscrit de manière immuable sur le registre partagé.
* **Résultat :** Obtention d'un *Work ID* (identifiant de l'œuvre) et d'un *Cultural ID* (identifiant de l'auteur).

## Acte 2 — Paramétrage Intelligent (Les Règles)
* **Objectif :** Traduire les règles de l'ayant droit dans un format lisible par le système.
* **Le principe :** L'auteur exprime ses conditions d'autorisation en langage naturel (ex: *"J'autorise les mèmes et les edits sur TikTok, partage des revenus à 50/50"*). Un agent IA dédié traduit cette phrase en paramètres structurés (territoires, plateformes autorisées, durée, modèle économique). L'IA ne décide rien : elle propose une traduction, et l'ayant droit valide explicitement par sa signature.
* **Résultat :** Création du *Policy Set* (le catalogue des droits de l'œuvre).
