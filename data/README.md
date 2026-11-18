# Données

Les deux fichiers CSV de l'expérimentation ont été fournis par l'enseignant sur le portail du cours. Ils ne sont pas redistribués ici. Le notebook les lit depuis Google Drive (`/content/drive/MyDrive/`).

**`program-measures.csv`** — 12 lignes, une par programme (mesures Visual Studio, voir [Code metrics values](https://learn.microsoft.com/en-us/visualstudio/code-quality/code-metrics-values)) :

| Colonne | Description |
|---|---|
| `Group` | 0 = groupe de contrôle, 1 = groupe de traitement |
| `Project ID` | identifiant du projet dans son groupe |
| `MI` | indice de maintenabilité (plus élevé = mieux) |
| `CC` | complexité cyclomatique totale |
| `DIT` | profondeur maximale de l'arbre d'héritage |
| `CBO` | couplage entre objets |
| `NLoC` | lignes de code, commentaires et lignes vides compris |
| `NLoCExec` | lignes de code exécutables |

**`survey-data.csv`** — 10 lignes, une par participant : `group`, puis `workload`, `difficulty`, `complexity`, `mental.demand`, `physical.demand`, `temporal.demand`, `performance`, `effort`, `frustration` (échelles ordinales).

---

The two CSV files were provided through the course portal and are not redistributed; their columns are described above.
