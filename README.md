# Mini-Project--scrubble
Premier project realisé par moi et Thomas  Marcheschi à HETIC
 un projet de pseudo mini scrabble. La partie se joue en 3 manches à la difficulté croissante, chacunes pouvant faire gagner de 1 à 3 points.
Au début de chaque manche, une liste de lettres est présentée au joueur et le joueur doit trouver jusqu'à trois mots dedans, pour chaque mot trouvé il gagne un point. Pour générer ces lettre il faudra puiser les 3 réponses dans une liste de mots cachées au joueur et mélanger leurs lettres en un seul endroit. Si les lettres des 3 mots se répète il faudra supprimer les doublons.
Exemple de partie :
Liste de départ -> nuit, jour, lune, haut, petit
récupération de 3 mots aléatoirement -> nuit, lune, petit
On mélange les lettres et on enlève les doublons -> nlueitp
Maintenant c'est au joueur de retrouver les 3 mots cachés, si il ne trouve pas il peut faire "Quit" pour passer à la prochaine manche 
