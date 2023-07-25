# Projet 7 : Implémentez un modèle de scoring

Vous êtes Data Scientist au sein d'une société financière, nommée "Prêt à dépenser", qui propose des crédits à la consommation pour des personnes ayant peu ou pas du tout d'historique de prêt.

L’entreprise souhaite mettre en œuvre un outil de “scoring crédit” pour calculer la probabilité qu’un client rembourse son crédit, puis classifie la demande en crédit accordé ou refusé. Elle souhaite donc développer un algorithme de classification en s’appuyant sur des sources de données variées (données comportementales, données provenant d'autres institutions financières, etc.).

De plus, les chargés de relation client ont fait remonter le fait que les clients sont de plus en plus demandeurs de transparence vis-à-vis des décisions d’octroi de crédit. Cette demande de transparence des clients va tout à fait dans le sens des valeurs que l’entreprise veut incarner.

Prêt à dépenser décide donc de développer un dashboard interactif pour que les chargés de relation client puissent à la fois expliquer de façon la plus transparente possible les décisions d’octroi de crédit, mais également permettre à leurs clients de disposer de leurs informations personnelles et de les explorer facilement.

Les données Voici les données dont vous aurez besoin pour réaliser le dashboard. Pour plus de simplicité, vous pouvez les télécharger à cette adresse.

Vous aurez sûrement besoin de joindre les différentes tables entre elles.

Votre mission :

Construire un modèle de scoring qui donnera une prédiction sur la probabilité de faillite d'un client de façon automatique.
Construire un dashboard interactif à destination des gestionnaires de la relation client permettant d'interpréter les prédictions faites par le modèle, et d’améliorer la connaissance client des chargés de relation client.
Mettre en production le modèle de scoring de prédiction à l’aide d’une API, ainsi que le dashboard interactif qui appelle l’API pour les prédictions.


# Evaluation

Compétences évaluées

En vous basant sur les critères d’évaluation dans le guide mentor du projet, définissez le statut d'acquisition de chaque compétence listée ci-dessous :

Validé - Expliquez pourquoi en partageant des retours constructifs

Non validé - Expliquez de façon constructive pourquoi et comment l’étudiant peut s’améliorer, en vous appuyant sur les critères d’évaluations

Compétences évaluées

En vous basant sur les critères d’évaluation dans le guide mentor du projet, définissez le statut d'acquisition de chaque compétence listée ci-dessous :

Validé - Expliquez pourquoi en partageant des retours constructifs

Non validé - Expliquez de façon constructive pourquoi et comment l’étudiant peut s’améliorer, en vous appuyant sur les critères d’évaluations

1. Définir et mettre en œuvre une stratégie de suivi de la performance d’un modèle

Validé

Commentaires :

- Attendus respectés .

2. Évaluer les performances des modèles d’apprentissage supervisé

Validé

Commentaires :

- Bonne réfléxion sur les scores.

- Bonne présentation des résultats.

3. Utiliser un logiciel de version de code pour assurer l’intégration du modèle

Validé

Commentaires :

- Attendus validés

- Ne pas hésiter à créer des branches ou à donner des messages significatifs aux commits ==> les commentaires Add files, Delete, Create sont plus des commentaires automatiques de l'interface github.

- Git est un outil essentiel : ne pas hésiter à approfondir ce sujet.

- Attention : https://github.com/GregoryBuriez/Flask-P7 & https://github.com/GregoryBuriez/Streamlit-P7 => pas de REAMDE.md == > CE4 Le candidat a rédigé un fichier introductif permettant de comprendre l'objectif du projet et le découpage des dossiers. ==> MAJ Dans la v2.

4. Définir la stratégie d’élaboration d’un modèle d’apprentissage supervisé

Validé

Commentaires :

- Attendus validés .

5. Réaliser un dashboard pour présenter son travail de modélisation

Validé

Commentaires :

- Test dashboard apres la soutenance OK

- Rendu général OK

- Attention : pas de read csv dans ce fichier ! (même si -- au final -- c'est bien l'api qui lit les données)

6. Rédiger une note méthodologique afin de communiquer sa démarche de modélisation

Validé

Commentaires :

- Document très serieux et qualitatif.

7. Présenter son travail de modélisation à l'oral

Validé

Commentaires :

- Attendus validés .

- De très bonne capacités de vulgraisation et didactiques. Cela pourra être très utile sur des postes de chef de projet, de management ou à composante commerciales.

- Attention à la partie Q&A => Certaines réponses longues et peu ciblées peuvent laisser un sentiment de déception.

8. Déployer un modèle via une API dans le Web

Validé

Commentaires :

- CI CD OK

- Attention : pas besoin de front pour l'API ! ==> regarder eventuellement fast.api pour la doc ou une UI.

- Test OK

- Indépendance Dashboard API

9. Définir et mettre en œuvre un pipeline d’entraînement des modèles

Validé

Commentaires :

- ML Flow utilisé

- Evidently OK

- Dans l'ideal ML run dans le cloud et tout y est stocké. La MAJ des modèles est faite en auto depuis les push de ML Flow à l'API (non spécifiquement demandé).

Livrable

Points forts :

- code OK

- PPT / Docs OK

Axes d'amélioration :

-

Soutenance

Remarques : 

- Dans l'ensemble un travail conforme aux (nombreuses) attentes !

- Respect du temps de présentation.

- Soutenance orale de bonne qualité : un talent certain pour la didactique et la vulgraisation. Attention à ne pas "trop" en faire vis à vi sd'un public "sachant", privilégier ces compétences pour les clients ou le management.

- La partie Q&A souffre de ne pas avoir des réponses concises et précises. Attention à ne pas trop contourner les questions.

- La notion de MLOps est "respectée" au sens des critères du projet mais mériterait d'être approfondie. C'est un sujet clé de nos jours. La formation OC ne l'aborde pas de facon "officielle", même si on y trouve des éléments dans ce projet. Une recherche personnelle sur le sujet peut être à effectuer.

-Idem un travail d'approfondissement pourra être à mener pour bien maitrise le logiciel git et adopter les bonnes pratiques terme de branches, de commits etc etc. 
