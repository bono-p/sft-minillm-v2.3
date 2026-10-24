# SFT miniLLM v2.3 — notebook robuste

Notebook de SFT révisé pour [bonopassale/miniLLM_v2.2-49M-50200it_3.29Btoks_1.0ep_20261005](https://huggingface.co/bonopassale/miniLLM_v2.2-49M-50200it_3.29Btoks_1.0ep_20261005),
pensé pour mieux extraire les connaissances accumulées au pré-entraînement (Wikipédia FR + FineWeb-2 FR)
plutôt que de simplement imiter un style d'instructions génériques.

Voir les commentaires du notebook pour le détail : architecture, plan de données par quotas,
filtres qualité, jeu de sondage factuel tenu à l'écart du SFT pour le choix du checkpoint.

À ouvrir dans Google Colab (GPU T4 recommandé).
