# Le Protocole Ping

Le Protocole Ping est une infrastructure décentralisée conçue pour automatiser la rencontre, l'accord de licence et la redistribution transparente de valeur entre les **Ayants Droit** d'œuvres culturelles et les **Créateurs** de contenus dérivés.

Ce dépôt centralise l'architecture documentaire et les spécifications techniques du protocole.

---

## 🗺️ Cartographie Documentaire

L'ensemble des spécifications est découpé selon les trois grands blocs de responsabilité du protocole :

*   [**Phase 1 : L'Ayant Droit**](docs/01_ayant_droit.md) — Gestion de l'identité de l'œuvre (*Cultural ID / Work ID*) et paramétrage intelligent des règles d'usage par IA.
*   [**Phase 2 : Le Créateur**](docs/02_createur.md) — Expression de l'intention créative et déclenchement du protocole d'accord (*Le Ping*).
*   [**Phase 3 : L'Infrastructure**](docs/03_infrastructure.md) — Moteur de licence, déploiement des *Smart Contracts*, marquage (*Fingerprinting*), suivi via oracles et redistribution automatisée.

---

## ⚙️ La Séquence Technique (Les 9 Actes)

Le protocole s'exécute de bout en bout en 9 étapes automatisées, faisant le pont entre le langage naturel des créateurs et l'exécution cryptographique de la blockchain.

```mermaid
graph TD
    %% Définition des styles de couleurs demandés
    classDef ayantDroit fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a;
    classDef createur fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d;
    classDef infra fill:#ffedd5,stroke:#ea580c,stroke-width:2px,color:#7c2d12;

    %% Actes
    subgraph Phase 1 : Ayant Droit
        A1[1. Cultural ID / Work ID]:::ayantDroit
        A2[2. Paramétrage sous Agent IA]:::ayantDroit
    end

    subgraph Phase 2 : Créateur
        A3[3. Le Ping — Intention Créative]:::createur
    end

    subgraph Phase 3 : L'Infrastructure Autonome
        A4[4. License Engine — License ID]:::infra
        A5[5. Smart Contract — Déploiement]:::infra
        A6[6. Fingerprint / Filigrane]:::infra
        A7[7. Oracle Network — Captation]:::infra
        A8[8. Exécution du Contrat]:::infra
        A9[9. Redistribution Automatique]:::infra
    end

    %% Flux
    A1 --> A2
    A2 --> A3
    A3 --> A4
    A4 --> A5
    A5 --> A6
    A6 --> A7
    A7 --> A8
    A8 --> A9

    %% Note sur les rôles de l'IA et de la boucle
    style Phase 1 : Ayant Droit color:#1e3a8a,stroke:#2563eb,stroke-dasharray: 5 5
    style Phase 2 : Créateur color:#14532d,stroke:#16a34a,stroke-dasharray: 5 5
    style Phase 3 : L'Infrastructure Autonome color:#7c2d12,stroke:#ea580c,stroke-dasharray: 5 5
