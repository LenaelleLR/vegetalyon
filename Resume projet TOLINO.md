# Résumé mémoire Barbara TOLINO

## Introduction 

**Objectif du projet :** analyse quantitative de potentiel aménagement et/ou végétalisation des toîts Nantais à partir de la BD TOPO 2D et d'une image satellite 3D. 
**Produit final :** outil automatique ou semi-automatique pour déterminer le "potentiel" d'un toît. 

## Chapitre 1 : Contexte 

**Problème :** îlots de chaleur urbains. Mais lorsque les villes sont déjà denses, il est compliqué de créer de nouvelles constructions et de développer de nouveaux espaces au sol. 
**Solution :** développer l'intéret des toîts.
On a ensuite un historique de l'utilisation des toîts (solariums fin XIXème, jardin suspendu chez Le Corbusier etc.).

**Aujourd'hui :** grand nombre de toîts inexploités, "non résolus" et souvent plats alors qu'ils possèdent un grand potentiel de vue, ensoleillement et ventilation. 
Plusieurs types d'aménagements possibles : espaces verts, de loisir, bar, restaurants, agriculture urbaine etc. 

**Nouvel enjeu :** déterminer automatiquement la forme du toît pour pouvoir analyser ses potentialités. 

### Différentes solutions existantes
Etude à Genève pour des panneaux solaires. Différents indicateurs : la surface, la pente, la luminosité, la présence d'une végétation déjà existante. 

Projet de recherche déjà mis en oeuvre à Lisbonne (Santos et al., 2016) : mesure de la couverture végétale du sol et estimation du potentiel de végétalisation du toît avec des données 3D obtenues par LIDAR. **Important de modérer les données 2D avec des données 3D**

Encore à Lisbonne (Silva et al.,Naing et al.) : analyse multi-critère avec 19 indicateurs. Objectif principal : identifier les zones prioritaires pour la végétalisation des toîts. 

### Positionnement de ce projet

1. Définir les bases d'une méthode d'analyse du potentiel de réaménagement des toîts à l'échelle de la ville. 
2. Analyse du potentiel individuellement pour chaque bâtiment par une analyse multi-critère des besoins et des avantages de ce toît. 

**Quatre étapes :**

1. Identification des toits plats
2. Repérage des exigences et besoins de la programmation choisie (végétalisation,énergétique etc.)
3. Analyse des indicateurs : quantifier les avantages et exigences de chaque toit
4. Détermination du potentiel par analyse multi-critère

**Hypothèses :**
git push -f origin master
- pas de prise en compte des critères techniques, socio-économiques, météorologiques
- uniquement toits plats et à végétaliser
- uniquement à l'intérieur de la ville de Nantes 

## Chapitre 2 : Usage multiples des toits

**Classification des toits en trois catégories** : Energétique (panneaux solaires, éoliennes...), Habité (nouveaux logements, espaces pour des commerces...) et Vert (Végétation, Agriculture, Fermes aquaponiques, Bassins etc.)

*Description des toits energétiques et habités (peu pertinent dans le cadre de notre étude)* 

### Toits verts 

**Economiquement** : alternative à la rénovation pour la gestion des eaux pluviales et la ventilation (albédo important)

![Fonctionnement toits verts](https://www.guidebatimentdurable.brussels/servlet/Repository/65770.jpg?ID=65770)