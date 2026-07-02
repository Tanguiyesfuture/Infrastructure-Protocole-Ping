# Le Protocole Ping

Le Protocole Ping est une infrastructure décentralisée conçue pour automatiser la rencontre, l'accord de licence et la redistribution transparente de valeur entre les **Ayants Droit** d'œuvres culturelles et les **Créateurs** de contenus dérivés.

---

## 🗺️ Cartographie Documentaire

*   [**Phase 1 : L'Ayant Droit**](docs/01_ayant_droit.md)
*   [**Phase 2 : Le Créateur**](docs/02_createur.md)
*   [**Phase 3 : L'Infrastructure**](docs/03_infrastructure.md)

---

## ⚙️ La Séquence Technique (Les 9 Actes)

```mermaid
graph TD
    classDef ayantDroit fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#1e3a8a;
    classDef createur fill:#dcfce7,stroke:#16a34a,stroke-width:2px,color:#14532d;
    classDef infra fill:#ffedd5,stroke:#ea580c,stroke-width:2px,color:#7c2d12;

    subgraph P1 [Phase 1 : Ayant Droit]
        A1[1. Cultural ID]:::ayantDroit
        A2[2. Paramétrage IA]:::ayantDroit
    end

    subgraph P2 [Phase 2 : Créateur]
        A3[3. Le Ping]:::createur
    end

    subgraph P3 [Phase 3 : Infrastructure]
        A4[4. License Engine]:::infra
        A5[5. Smart Contract]:::infra
        A6[6. Fingerprint]:::infra
        A7[7. Oracle Network]:::infra
        A8[8. Exécution]:::infra
        A9[9. Redistribution]:::infra
    end

    A1 --> A2 --> A3 --> A4 --> A5 --> A6 --> A7 --> A8 --> A9
