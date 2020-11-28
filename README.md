# MiniShell
Le but de ce projet est de réaliser un minishell via la programmation système en C surtout manipuler les processus,les pipes,les signaux.

<ul>
  <li><h5>Réalisations</h5>
    <ol>
      <li><b>commande simple :</b> Utilisation des entrées stockées dans le champs seq de la structure cmdline
      </li>
      <li><b>rédirections entrée/sortie:</b>Remplacements des E/S standards par les descripteurs de fichier cibles
      </li>
      <li><b>pipelines</b>: Exécution parallèle des différentes commandes</li>
      <li><b>E/S sur pipelines :</b>La rédirection en E se fait sur la première commande ,et celle S depuis le résultat obtenu après la dernière commande</li>
      <li><b>Gestion des erreurs</b></li>
      <li><b>Commande en arrière plan bg</b></li>
      <li><b>Gestion des zombies</b></li>
      <li><b>Gestion des jobs</b></li>
      <li><b>Commande fg et stop</b></li>
    </ol>
  </li>
  <li><h5>Description des tests:</h5></li>
</ul>
