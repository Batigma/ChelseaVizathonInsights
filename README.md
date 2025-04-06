# ⚽ Chelsea FC Performance Insights Vizathon – Power BI Dashboard

## Contexte
Dans le cadre du **Chelsea FC Performance Insights Vizathon**, ce projet explore les données de récupération, de performance physique **et de positionnement GPS** des joueurs, afin de fournir des insights exploitables à l’encadrement technique et médical du club.

---

## Objectifs
- Identifier les axes d’optimisation dans le suivi de récupération.
- Visualiser les benchmarks de performance physique sur une période étendue.
- Analyser le **positionnement et les zones d’effort sur le terrain** via les données GPS.
- Mettre en évidence les déséquilibres ou zones de sous-performance.

---

## Approche Méthodologique

- **Outil :** Power BI  
- **Techniques :**
  - Transformation via **Power Query**
  - Modélisation des données relationnelles
  - Formules **DAX** pour KPI dynamiques et benchmarks
  - Visualisations avancées : `Radar Charts`, `Time Series`, `KPI Cards`, `Heatmaps GPS`

- **Sources de données :**
  - Récupération subjective (Soreness, Sleep, Bio, etc.)
  - Données de performance physique (Agility, Acceleration, Max Velocity, etc.)
  - **CFC GPS Data** (latitude, longitude, vitesse, distance, intensité, etc.)

---

## Insights Majeurs

### Récupération
- `Subjective` et `Soreness` dominent la saisie.
- Faible volume de données sur `bio` et `joint_range` : amélioration possible dans le suivi médical.
- Analyse temporelle utile pour détecter les phases de sous-performance.
  https://app.powerbi.com/reportEmbed?reportId=7551b878-3ae3-409a-bae1-59feab90ead5&autoAuth=true&ctid=901cb4ca-b862-4029-9306-e5cd0f6d9f86
![image](https://github.com/user-attachments/assets/92c2bfae-b99c-4492-ba63-1fd750cacc2c)

### Performance Physique
- Excellente performance sur `Agility` et `Sprint`.
- `Max Velocity` reste inférieure aux attentes = **levier d’entraînement**.
- `Deceleration` et `Acceleration` maîtrisées, `Grapple` et `Rotate` à renforcer.
![image](https://github.com/user-attachments/assets/ec682bae-19b2-424a-9dfa-c25ca483af61)



### CFC GPS Insights
- Analyse de **la couverture terrain** via cartes de chaleur et trajectoires.
- Détection des **zones d’activité intense** et corrélation avec les performances physiques.
- Certains joueurs présentent des **zones de repli fréquentes**, potentiellement liées à leur rôle ou à une fatigue récurrente.
  ![image](https://github.com/user-attachments/assets/8487f163-c937-43be-9050-60a46e3897a4)
---

## Recommandations
- Renforcer la collecte de données manquantes (`bio`, `sleep`, `GPS partiel`).
- Intégrer la donnée GPS dans les plans d’entraînement personnalisés.
- Créer des **dashboards individuels** croisant performances et positionnements.
- Focus sur les mouvements spécifiques (`grapple`, `rotate`, `velocity peaks`).

---

## Livrables
- Fichier Power BI `.pbix`
- Résumé du projet (.docx & .md)
- Fichier PDF avec les insights relvés


---

## Conclusion
Ce tableau de bord propose une **vue holistique et intégrée** des performances des joueurs de Chelsea FC, combinant **données physiques, de récupération et GPS**. Il offre des insights concrets et actionnables pour améliorer la performance, prévenir les blessures et affiner la tactique d’équipe.

---
