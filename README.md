Projet Tableau : Analyse des Facteurs du Bonheur dans le Monde 🌍

Contexte du Projet : 


Dans ce petit projet de 3 heures, j'ai exploré un ensemble de données sur le bonheur des pays à travers différents indicateurs économiques et sociaux. L'objectif était d'analyser les facteurs influençant le bonheur dans divers pays et régions, en utilisant Tableau Desktop pour la visualisation.

Les données utilisées incluent les variables suivantes :

Overall rank : Classement global du bonheur par pays.
Country or region : Nom du pays.
Score : Score global du bonheur.
GDP per capita : Produit intérieur brut par habitant.
Social support : Soutien social ressenti.
Healthy life expectancy : Espérance de vie en bonne santé.
Freedom to make life choices : Liberté de choix de vie.
Generosity : Générosité.
Perceptions of corruption : Perception de la corruption.

1.  Deux Carte Choroplèthe : Visualisation des Scores de Bonheur par Pays / perception de la corruption par Pays 
Objectif : Montrer la répartition géographique des scores de bonheur / la corruption 
Réalisation : Utilisation d'une carte choroplèthe pour visualiser les scores par pays, avec des couleurs plus intenses pour indiquer des scores plus élevés.

2. Classement Global des Pays
Objectif : Classer les pays en fonction de leur score de bonheur.
Réalisation : Graphique en barres verticales trié par la variable "Overall rank", permettant de voir les pays les mieux classés.

Il y a les 20 premiers et les 20 derniers dans mon tableau de bord. 

3. Analyse des Facteurs Clés à l'Aide de Box Plots
Objectif : Analyser la répartition des scores par facteur dans différents pays.

Réalisation : Box Plot pour la Générosité : Analyse de la distribution des scores de Generosity par pays.
Titre : "Distribution de la Générosité par Pays"

Box Plot pour la Liberté de Faire des Choix de Vie : Visualisation des scores pour Freedom to make life choices.
Titre : "Répartition de la Liberté de Choix dans la Vie par Pays"

4. Deux Scatter Plots pour Analyser les Corrélations entre Variables
Objectif : Examiner la relation entre différents facteurs pour évaluer leur impact sur le bonheur.

Réalisation : Scatter Plot : Corrélation entre le PIB par Habitant et le Soutien Social 
Axes : "GDP per capita" (axe X) et "Social support" (axe Y).
Détail : Chaque point représente un pays, avec une ligne de tendance pour visualiser la corrélation.
Titre : "Relation entre le Soutien Social et le PIB par Habitant : Analyse de la Corrélation"

Scatter Plot : Corrélation entre le PIB par Habitant et l'espérence de vie
Axe : "GDP per capita" (axes X) et "Healthy life expectancy" (axe Y). 
Détail : Chaque point représente un pays, avec une ligne de tendance pour visualiser la corrélation.
Titre : "Relation entre le PIB par Habitant et l'espérence de vie par Pays"

Interprétation : 

Dans le cadre de cette analyse, nous avons étudié les relations entre le PIB par Habitant de différents pays et deux indicateurs de bien-être : le Soutien Social et l'Espérance de Vie en Bonne Santé. L'objectif était de comprendre comment la richesse d'un pays peut influencer ces deux aspects du bien-être de sa population.

1. Relation entre le Soutien Social et le PIB par Habitant

Le premier scatter plot a révélé un coefficient de détermination (R²) de 0,569, indiquant que 56,9 % de la variation du Soutien Social est expliquée par le PIB par Habitant. Ce résultat suggère une corrélation modérée : les pays plus riches tendent à offrir un soutien social plus élevé, mais ce n'est pas le seul facteur influençant cette dimension. La p-value extrêmement faible (< 0,0001) confirme que cette relation est statistiquement significative, ce qui signifie qu'il est peu probable que ce lien soit dû au hasard. Toutefois, environ 43,1 % de la variation du Soutien Social reste inexpliquée, suggérant que d'autres facteurs (tels que les politiques sociales ou culturelles) jouent également un rôle.

2. Relation entre l'Espérance de Vie en Bonne Santé et le PIB par Habitant

Le second scatter plot a montré un coefficient de détermination (R²) de 0,697, ce qui signifie que 69,7 % de la variation de l'Espérance de Vie en Bonne Santé est expliquée par le PIB par Habitant. Ici, la corrélation est plus forte, suggérant que le niveau de richesse d'un pays a un impact significatif sur la longévité en bonne santé de sa population. Comme pour l'analyse précédente, la p-value obtenue est inférieure à 0,0001, indiquant une très forte signification statistique de la relation. Cela implique que les pays plus riches bénéficient généralement d'une meilleure espérance de vie en raison d'un accès accru aux soins de santé, d'une nutrition de qualité, et de meilleures conditions de vie. Cependant, 30,3 % de la variation reste inexpliquée, ce qui souligne l'importance d'autres déterminants, tels que l'environnement, les politiques de santé publique, et les habitudes de vie.

Conclusion : 

Ces deux analyses montrent que, bien que le PIB par Habitant joue un rôle important dans l'amélioration du Soutien Social et de l'Espérance de Vie en Bonne Santé, il n'explique pas tout. D'autres facteurs, probablement liés aux politiques gouvernementales, aux systèmes de santé, et à la culture, influencent également ces dimensions du bien-être. Ces résultats mettent en évidence que la croissance économique, bien qu'importante, doit être accompagnée de politiques ciblées pour maximiser son impact sur le bien-être de la population.











