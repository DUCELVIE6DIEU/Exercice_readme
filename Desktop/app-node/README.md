#Exercice Utilisation readline
Cet exercice a pour but de demander à l'utilisateur de saisir un nombre dans le terminal et ensuite afficher ce nombre. Ce code suit une logique très naturelle : on prépare les outils, on ouvre la discussion, on pose une question, on transforme la réponse, on affiche le résultat et on raccroche.

##Objectifs de l'exercice

Une fois l'outil importé, on crée une interface de communication. On explique au programme que l'entrée des données se fera par le clavier, c'est le process.stdin, et que la sortie se fera sur l'écran, c'est le process.stdout. C'est comme si on ouvrait une ligne téléphonique entre l'ordinateur et l'utilisateur.

Ensuite, on pose la question. Le programme affiche à l'écran le message "entrez un nombre:" et se met en attente. Quand l'utilisateur tape sa réponse et appuie sur Entrée, cette réponse est stockée dans une variable qui s'appelle answer. À ce stade, la réponse est encore du texte.

C'est pour cela que l'étape suivante est de convertir ce texte en un vrai nombre grâce à Number(answer). On range ce vrai nombre dans une nouvelle variable number. Après cela, on affiche simplement le résultat à l'écran avec un console.log.

Enfin, pour terminer proprement, on ferme la communication avec rl.close(). Si on oublie cette étape, le programme reste bloqué et ne se ferme jamais.

