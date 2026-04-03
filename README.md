# Dashboard Bancaire & Crédit au Maroc
Tableau de bord interactif réalisé avec Power BI, basé sur 800 clients bancaires couvrant 8 villes marocaines, 7 banques et 5 types de crédit sur la période 2020–2024.

### Contenu du projet
FichierDescriptionDashboard_Bancaire_Crédit_Maroc.pbixFichier Power BI principaldataset_bancaire_maroc.xlsxDataset source (800 clients)

#### KPIs Clés
IndicateurValeur
Nombre de clients800
Total crédits accordés393 M MAD
Total dépôts191 M MAD
Mensualité moyenne6 290 MAD
Taux de défaut2.13%
Score risque moyen575 / 850

#### Pages du Dashboard
###  Page 1 — Vue Générale & KPIs
Aperçu global du portefeuille crédits : répartition par type, segment, statut et montants accordés.
Visualisations :

5 KPI Cards : Nombre clients / Total crédits / Total dépôts / Taux défaut / Mensualité moyenne
Donut Chart : Répartition par Type_Crédit — Immobilier 32.25%, Personnel 24.25%, Auto 19.13%
Donut Chart : Répartition par Segment — Particulier 84%, PME 11.38%, Corporate 4.62%
Bar Chart horizontal : Total crédits par Type_Crédit — l'Immobilier domine largement
Donut Chart : Statut des crédits — Actif 85.88%, Remboursé 8%, En retard 4%, Défaut 2.13%

Insights :

Le crédit Immobilier représente la part la plus élevée du portefeuille en volume
85.88% des crédits sont actifs — portefeuille sain
Le segment Particulier représente 84% de la clientèle


### Page 2 — Géographie & Agences
Analyse territoriale de la distribution des crédits et performance des agences.
Visualisations :

Bar Chart : Total crédits par Ville — Casablanca en tête, suivie de Rabat et Fes
Bar Chart : Total dépôts par Ville — même hiérarchie que les crédits
Table : Top agences — Nombre clients / Total crédits / Mensualité moyenne
Treemap : Nombre clients par Région — Grand Casablanca domine
Bar Chart : Total crédits par Banque — Crédit Agricole en tête

Insights :

Casablanca concentre le plus grand volume de crédits (~0.1Md MAD)
Agence Guéliz (Marrakech) a la mensualité moyenne la plus élevée : 8 399 MAD
Crédit Agricole et Attijariwafa Bank sont les banques les plus actives
Grand Casablanca et Rabat-Salé dominent la carte régionale


### Page 3 — Risque & Performance
Analyse du risque crédit, des défauts de paiement et de la performance par segment.
Visualisations :

3 KPI Cards : Score risque moyen (575) / Clients en défaut (17) / Taux défaut (2.13%)
Scatter Plot : Score risque vs Montant crédit par Type_Crédit
Bar Chart : Clients en défaut par Région — Grand Casablanca en tête
Stacked Bar : Statut crédit par Type_Crédit — visualise la qualité par segment
Column Chart : Score risque moyen par Segment — PME > Corporate > Particulier
Column Chart : Taux d'intérêt moyen par Type_Crédit — Personnel le plus élevé (~10%)

Insights :

Le taux de défaut de 2.13% est dans la norme du secteur bancaire marocain
Le crédit Personnel a le taux d'intérêt le plus élevé (~10%)
Le crédit Étudiant a le taux le plus bas (~4%)
Les PME ont un meilleur score risque moyen que les Particuliers


### Page 4 — Profil Clients & Tendances
Analyse démographique de la clientèle et évolution temporelle des crédits.
Visualisations :

Donut Chart : Répartition par Genre — quasi-équilibrée (F 50.75% / M 49.25%)
Column Chart : Distribution des clients par Âge — pic entre 30 et 45 ans
Line Chart : Évolution mensuelle des crédits accordés — entre 20M et 40M MAD/mois
Column Chart : Durée moyenne par Type_Crédit — Immobilier ~210 mois, Étudiant ~24 mois
Column Chart : Revenu moyen par Segment — Corporate > PME > Particulier
Scatter : Revenu mensuel vs Montant crédit par Segment

Insights :

Répartition parfaitement équilibrée entre hommes et femmes
La tranche d'âge 30–45 ans est la plus emprunteuse
Les crédits Corporate ont les revenus et montants les plus élevés
L'évolution mensuelle montre une activité régulière sans saisonnalité marquée


### Technologies utilisées

Power BI Desktop
Microsoft Excel (source de données)
Dataset : 800 clients bancaires — Maroc 2020–2024 (données simulées basées sur le marché réel)


### Comment utiliser ce projet

Cloner le repository :

bashgit clone https://github.com/Faridoumnay/ Analyse de Bancaire & Crédit au Maroc.git

Ouvrir Dashboard_Bancaire_Crédit_Maroc.pbix avec Power BI Desktop
Re-lier le dataset si nécessaire : Transform Data → Data Source Settings
Explorer les 4 pages avec les slicers disponibles


### Auteur
Farid Oumnay — Junior Data Analyst

 faridoumnay.github.io
 
 linkedin.com/in/farid-oumnay
 
 github.com/Faridoumnay
