---
title: "Détails des objectifs du TIPE"
description: "Modélisation d'un problème d'optimisation"
pubDate: "Jul 10 2023"
heroImage: "/post_img.webp"
---


# La ville et ses réseaux de transport

La mise en place de tels réseaux de transport doit répondre à une multifactorialité de
contraintes qui en font un problème d’optimisation intéressant, tant dans les potentialités de
calculs, que dans l’amplitude des paramètres dont il tient compte.
Les transports en commun font partie intégrante du paysage fonctionnel urbain car ils sont un
outil nécessaire aux déplacements de population. En effet, ils répondent à des besoins toujours
plus importants en termes d’efficience dans la fluidification des flux et réduction des conflits d’
usages.

## Positionnement thématique (ÉTAPE 1) :
- INFORMATIQUE (Informatique pratique)
- MATHEMATIQUES (Autres)

## Mots-clés (ÉTAPE 1) :

- optimisation
- réseaux
- transports
- graphe
- heuristique

## Bibliographie commentée
La désertification des campagnes au profit de vies citadines et d’une urbanisation toujours plus
importante au fil des ans a suscité le développement de moyens de transport cohérents faces
aux nécessités multifactorielles de nos vies. En effet, la compacité des villes a rendu les
déplacements
individuels au moyen d’une automobile inadéquats, voire impossibles[^1]. C’est au 17ème siècle
qu’apparaît la volonté d’aménager le territoire urbain, toutefois, celle-ci n’est vraiment mise en
oeuvre qu’au 20ème siècle face à la crise pétrolière de 1973, à la pollution importante de nos
locomotions, ainsi qu’à leur inefficience dès lors que la densité du flux augmente. Autant de
phénomènes, encore actuels et dont il ne fait aucun doute qu’ils se feront plus pressants dans les
années à venir, qui ont conduit à l’émergence de réseaux de transport en commun. Nous voilà
donc face à l’obligation de concevoir et optimiser ces modes déplacement pour répondre aux
enjeux de nos vies citadines.
Pour ce faire, nous disposons d’algorithmes qui nous permettent après modélisation de la
situation, de proposer une solution au problème qui nous est donné : c’est-à-dire concevoir un
réseau de transport en proposant un placement des stations dans la ville. En effet, la
modélisation du problème réside en l’établissement d’un graphe basé sur la topologie routière[^2]
d’une ville, auquel on adjoint une densité de population. Ce problème attrait alors à tout un
pan de l’informatique, et des mathématiques : l’optimisation. En vue de son traitement, nous
disposons d’un ensemble de méthodes où leur diversité même apparaît déterminante dans la
confrontation des solutions calculées. C’est bien dans le champ de l’heuristique[3], ou bien par le
biais d’algorithmes évolutionnistes[^4], que s’épanchent nos perspectives de travail. En effet, les
potentialités que nous ouvrent ces algorithmes sont de l’ordre de l’approximation d’une solution
réalisable en des temps de calculs décents.
Problématique retenue
Comment créer et optimiser un réseau de transport en commun?

## Objectifs personnels du TIPE 
Pré-traitement d’une base de donnée représentant un filaire de voirie: conversion en un jeu de
données utilisable. Modélisation du problème par le biais d’un graphe à partir du traitement des
données récoltées. Établissement de la fonction objectif et mise en forme des résultats.



[^1]: RALPH HENSON : Conception, organisation et évaluation de réseaux de transport locaux
durables : Revue internationale des sciences sociales 2003/2 (n° 176), pages 243 à 260
[^2]: TOULOUSE MÉTROPOLE : Filaire de voirie - Toulouse Métropole : https://www.data.toulouse-metropole.fr/explore/dataset/filaire-de-voirie/information/
[^3]: PIERRE-EDOUARD PORTIER : Recuit simulé - Cours : https://perso.liris.cnrs.fr/pierreedouard.portier/teaching20152016/ia/sima/sima.html
[^4]: CHARLES FLEURENT : Algorithmes génétiques : https://accromath.uqam.ca/2019/10
/algorithmes-genetiques/