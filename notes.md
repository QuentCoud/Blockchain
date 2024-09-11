# Blockchain

## Cours 1 - Présentation

- **Fonction de hashage** : maintient l'intégrité des bases de données de la blockchain.
- **Clé publique / clé privée** : mécanismes cryptographiques pour sécuriser les transactions.
- **Blockchain** : registre numérique public, indélébile et décentralisé.
- **Système distribué** : base de données présente sur plusieurs serveurs appelés "nœuds", garantissant la sécurité et la pérennité des données.
- Il est uniquement possible de **lire et écrire** sur une base de données de blockchain.
- **Transaction**: écriture dans la BDD.
- **Bloc** : groupement de transactions, il permet également de retracer l'historique des transactions.
  - Un bloc contient le **hash** du bloc précédent, un **Nonce**, et une **liste de transactions**.
- **Méthode de consensus**: Algo qui vérifie que les transactions de chaque blocs sont identique pour les valider
- Celui qui résout le nœud en trouvant la **Proof of Work** (preuve de travail) obtient une récompense (1 token).
- **Nonce**: Prédiction du Hash du prochain bloc

## Cours 2 - Mise en place de l'environnement de dev
