 # Le Sceau — Temple des Anciens                                                                                       
   
  > Jeu de mémoire de séquences basé sur des glyphes. Cinq niveaux, cinq façons de mettre ta mémoire en défaut.         
                  
  **[▶ Jouer maintenant](https://bourvenfr-hub.github.io/le-sceau/)**                                                   
                  
  ---

  ## Le jeu

  Le Sceau est un jeu de mémoire visuelle dans lequel le joueur observe une séquence de glyphes, puis la reproduit de   
  mémoire.
                                                                                                                        
  Ce qui le distingue d'un jeu de mémoire classique : chaque niveau introduit une nouvelle contrainte cognitive —       
  inversion, leurres, chunking, mise à jour — qui force à traiter l'information différemment plutôt qu'à simplement la
  retenir plus longtemps. La difficulté monte non pas par la longueur des séquences, mais par la nature du traitement   
  requis.         

  Le projet est autant un outil d'entraînement cognitif qu'un jeu. Il cible explicitement la mémoire de travail et la   
  concentration soutenue.
                                                                                                                        
  ---             

  ## Niveaux et mécaniques cognitives

  | Niveau | Nom          | Mécanique principale                                              |                         
  |--------|--------------|-------------------------------------------------------------------|
  | L1     | Mémoire pure | Reproduire une séquence unique, sans piège                        |                         
  | L2     | Inversion    | La séquence à restituer est l'inverse de celle observée           |
  | L3     | Mise à jour  | Un glyphe change entre la phase d'observation et le rappel        |                         
  | L4     | Leurres      | Des distracteurs similaires s'ajoutent à la banque de glyphes     |
  | L5     | Chunking     | Les séquences longues doivent être regroupées pour être mémorisées |                        
                  
  Chaque niveau comporte 10 étapes. La difficulté augmente progressivement à l'intérieur de chaque niveau (longueur,    
  vitesse, densité des leurres).
                                                                                                                        
  ---             

  ## Fonctionnalités

  - 5 niveaux × 10 étapes, soit 50 challenges distincts
  - Difficulté adaptative à l'intérieur de chaque niveau
  - Pauses rappel aléatoires (L3+) pour solliciter la récupération active                                               
  - Système de progression et d'XP persistant (localStorage)
  - Feedback sonore et visuel à chaque interaction                                                                      
  - Aucune dépendance serveur — fonctionne entièrement en local
                                                                                                                        
  ---
                                                                                                                        
  ## Comment jouer

  1. Observe la séquence de glyphes affichée dans le portail central
  2. Mémorise l'ordre, puis restitue-la en plaçant les glyphes dans les emplacements
  3. Valide ta réponse — la correction est immédiate                                                                    
  4. Progresse à l'étape suivante ou recommence si nécessaire
                                                                                                                        
  Les règles spécifiques à chaque niveau s'affichent au démarrage du niveau concerné.                                   
   
  ---                                                                                                                   
                  
  ## Stack technique

  - **HTML / CSS / JS** — fichier unique, zéro dépendance
  - **SVG inline** pour tous les glyphes
  - **Web Audio API** pour les effets sonores générés dynamiquement
  - **localStorage** pour la persistance de la progression
  - Police : [Cinzel + Jost](https://fonts.google.com) via Google Fonts                                                 
   
  ---                                                                                                                   
                  
  ## Pistes d'évolution

  - Support clavier complet (accessibilité)
  - Mode démo découplé du gameplay principal
  - Animations de transition entre les phases observe → rappel                                                          
  - Difficulté adaptative inter-niveaux (ajustement selon les performances passées)
  - Export de progression / statistiques de session                                                                     
                  
  ---

  ## Licence

  Ce projet est distribué sous licence MIT.                                                                             
  