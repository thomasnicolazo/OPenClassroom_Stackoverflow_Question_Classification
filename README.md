#  OpenClassroom_projet_5_openclassrooms-categoriser-automatiquement-des-questions

Ce projet a été réalisé dans le cadre de la fformation machine learning de la formation d'openclassroom.
L'objetcif est de mettre en place des méthodes de natural language processing (NPL) pour catégoriser des question de la plateforme [StackOverflow](https://stackoverflow.com/), afin de créer un système de suggestion de tags.
## les données
Les données seront fournies à partir de l’outil d’export de données  [StackOverflow Data Explorer](https://data.stackexchange.com/stackoverflow/query/new). Le jeu de données se compose de 50000 posts contenant la question, le titree ainsi que les tags associés. Toutes ces questions ont un nombre de vues et de favoris supérieur à 10, ainsi qu'un score supérieur à 5 (voir StackOverflow Data Explorer).
## Présentation
L'ensemble du projet est présenté sous la forme d'un notebook d'exploration et 4 méthoddes pour traiter les caractéristiques des questions:
 - bag of words (BOW)
 -  word2vec (W2V)
 - BERT
 -  Universal sentence encoder (USE)
 la métrique utilisée pour comparer ces 4 encodeurs est la F1 score.
 Une [API](https://github.com/thomasnicolazo/webapp_Stackoverflow_Question_Classification) de suggéstion de tags pour les questtions de stackOverflow avec l'encoder USE est disponible.
 
