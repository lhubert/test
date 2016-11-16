#HSLIDE
Compte rendu d'expertise

Audit du cluster de production

Laurence.Hubert@hurence.com

15 Septembre 2016

#HSLIDE

## Actions menées

- Audit des queues de traitement configurées
- Audit de la mémoire consommée sur 24 heures
- Audit de la CPU consommée sur 24 heures
- Audit de la conception des projets utilisant la capacité à plein

#HSLIDE
## Audit des queues de traitement
- 85% de la capacité du cluster est réservée aux projets 
- 1 queue par projet
- chaque projet a un faible pourcentage de la capacité 
- l'elasticité est telle sorte que tout projet peut déborder
   jusqu'à utiliser 100% du cluster si aucun autre traitement ne l'empêche
dit de la conception des projets utilisant la capacité à plein
 
