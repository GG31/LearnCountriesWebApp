# LearnCountriesWebApp
Lancer le serveur corese avec le chargement des fichiers du dossier rdf
java -jar corese-server.jar -load fichierN3.nt

Ouvrir cours.html ou exercice.html

# Arborescence du projet
HTML
  |
  ----->Cours.html  (Page web contenant les cours)
  ----->Exercices.html   (Page web contenant les exercices)
RDF
  |
  ----->ontologie.rdfs   (Contient l'ontologie des pays que nous avons définis)
  ----->pays.nt   (Contient notre description des pays sous la forme turtle)
  ----->pays.rdf   (Contient notre description des pays sous la forme XML)
  ----->pays-withRules.nt   (Contient notre description des pays ET les noeuds créés grace aux regles définies)