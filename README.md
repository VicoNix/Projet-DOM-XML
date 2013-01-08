Projet-DOM-XML
==============

Application Java permettant les fonctions suivantes :
-lancement d'un scénario quelconque (avec validation du fichier), en prévoyant des options de pause (enregistrer l'état d'avancement) et de réinitialisation; le déroulé d'un scénario devra être lui aussi enregsitré dans un fichier XML
-reprise d'un scénario existant
-consultation du déroulé (ce qui s'est déjà passé)
-exportation du déroulé (ou d'une partie sélectionnée par l'utilisateur) au format texte (feuilles de styles XSL)
-consultation de la base de données des scénarii au travers des requêtes XQuery

C'est un module d'utilisation

Remarques :
-l'élément traitement doit permettre d'analyser une réponse au travers des opérateurs classiques <,inférieur ou égal,supérieur ou égal, >, = et différent
-tous les fichiers manipulés par cette application doivent être codés en XML et validés par un schéma
-toutes les interrogation doivent être codées en utilisant XPath ou XQuery sauf contre indication de l'énoncé
