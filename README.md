🧠 L'IA au service de la Santé Mentale : Détecter les Risques Invisibles
Peut-on être en danger alors que tous les voyants semblent au vert ? Dans le cadre de mon dernier projet en Data Science, j'ai voulu explorer cette zone grise où les adolescents déclarent un bien-être "correct" malgré des habitudes de vie alarmantes. 🛡️

🔎 Le Problème : Le "Risque Silencieux"
Les questionnaires de santé mentale classiques reposent sur l'auto-déclaration. Mais la donnée comportementale (sommeil, temps d'écran, stress) raconte souvent une autre histoire. Mon objectif : utiliser le Machine Learning pour identifier ces profils atypiques.

🛠️ Ma démarche technique (Pipeline de A à Z)
Phase 1 & 2 : Détection d'Anomalies 🚨
Utilisation de l'Isolation Forest pour isoler les individus dont les comportements divergent radicalement de la norme, même si leur score d'anxiété déclaré reste bas.

Phase 3 : Clustering & Archétypes 👥
Grâce à K-Means, j'ai regroupé ces profils à risque en 3 familles distinctes : les "Insomniaques Numériques", les "Actifs Stressés" et les "Profils Isolés".

Phase 4 : IA Explicable (XAI) 🔑
Utilisation des valeurs SHAP pour ouvrir la "boîte noire" du modèle. Pourquoi ce jeune est-il à risque ? Le graphique SHAP révèle l'impact précis de chaque facteur (ex: manque de sommeil vs temps d'écran).

Phase 5 & 6 : Du Code à l'Action 🎯
Création d'un Score de Priorité pour aider à l'intervention précoce et d'un Simulateur de Risque visuel pour cartographier les zones de danger en temps réel.# D-tecterl-Invisible-Utiliser-l-IApourIdentifierLesrisquesdesant-mentalesilencieuxchezlesadolescents.
