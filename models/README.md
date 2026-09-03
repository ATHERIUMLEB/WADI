# Modèles sauvegardés

Ce dossier est créé à l'exécution de la **section 7** du notebook.

| Fichier | Description |
|---------|-------------|
| `best_model.pkl` | Meilleur modèle (Random Forest ou XGBoost) sauvegardé avec `joblib` |

Pour recharger :

```python
import joblib
model = joblib.load("models/best_model.pkl")
```
