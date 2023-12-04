# README

Dans cet exercice, on va créer ton propre coach personnel.
Malheureusement, ton coach est un peu stupide et uniquement capable de se comporter de la façon suivante :

  1. Si tu te contentes de lui dire au lieu de lui demander quelque chose (exemple : `"I met a girl last night"`), ton coach répondra simplement `"I don’t care, get dressed and go to 
     work!"`
  2. Si tu lui poses une question (exemple : `"Can I eat some pizza?"`), ton coach ne sera pas d’une grande aide non plus et te répondra `"Silly question, get dressed and go to work!"`
  3. La seule façon de te débarrasser de ton coach est de lui dire ce qu’il a envie d’entendre : `"I am going to work right now!"`.

Comparons le **monde réel** et le **monde du code**.

  • ***Monde réel*** : Réveil   
***Monde du code*** : Exécuter `ruby lib/interface.rb` dans le terminal
                                                     
  • ***Monde réel*** : Parler à ton coach    
***Monde du code*** : Écrire une string dans le terminal et appuyer sur Entrée

  • ***Monde réel*** : Faire parler ton coach	   
***Monde du code*** : Lire la réponse de ton coach imprimée sur le terminal avec `puts`

  • ***Monde réel*** : Poser une question	   
***Monde du code*** : Écrire une phrase se terminant par `?` et appuyer sur Entrée

  • ***Monde réel*** : Te débarrasser de ton coach     
***Monde du code*** : Saisir le `"I am going to work right now!"`, appuyer sur Entrée. Le programme doit se fermer.

Les objectifs de cet exercice sont les suivants :

  • Comprendre le flux d’éxecution (**execution flow**) d’un programme et apprendre à « lire » dans ton code, ligne par ligne

  • Découvrir les **conditions**

  • Découvrir les structures de code qui permettent de modifier le flux d’exécution de ton programme : `if/unless..else..end, while/until..end`, etc. Ce sont des structures de contrôle


**Spécifications**

**Réponse de ton coach**

⚠️ Avant de commencer, assure-toi d’exécuter `rake` et de lire attentivement les spécifications. Ça te donnera une vision claire du résultat attendu pour chacune des méthodes.

Le fichier `lib/coach_answer.rb` contient la définition de la méthode pour `coach_answer`. Cette méthode prend un argument, `your_message`, qui correspond à la phrase que tu dis à ton coach. La méthode doit retourner une `String` (à savoir la réponse de ton coach), qui dépendra de la valeur passée dans `your_message`.

Nous allons maintenant créer une version améliorée de ton coach avec la méthode `coach_answer_enhanced`. Si tu t’adresses à ton coach **EN CRIANT**, il appréciera et ajoutera `“I can feel your motivation!”` avant sa réponse habituelle. Souviens-toi que pour crier sur Internet, il faut écrire en **MAJUSCULES** ! Et si tu cries `“I AM GOING TO WORK RIGHT NOW!”`, alors ton coach te laissera tranquille.

**Programme interactif**
  • Écris le code qui te permettra d’interagir avec ton coach par l’intermédiaire du terminal.
  
  • **contrainte** : Ce programme doit s’exécuter en **boucle**. Ton coach doit répondre à ton message et attendre le suivant jusqu’à ce que tu décides de t’en débarrasser. Utilise `while..end` ou `until..end` pour cela.

Si tu te retrouves coincé dans une **boucle infinie**, appuie simplement sur `Ctrl` + `C` ! Le programme arrêtera de s’exécuter.

⚠️ L’exercice n’est pas terminé que lorsque rake est complètement vert ! Tu dois aussi t’assurer de vraiment pouvoir poser des questions à ton coach en exécutant `ruby lib/interface.rb` 😉

**Enseignements clés**
  
  • Quel est le flux d’éxecution (execution flow) habituel d’un programme ?
  
  • Comment des structures de type `if..else..end` or `while..end` modifient-elles ce flux ?
  
  • Comment ces structures fonctionnent-elles ?
  
  • Qu’est-ce qu’une condition ? Quelles valeurs peut-elle prendre ? Quelle est la différence entre `=` et `==` ?
  
  • Est-ce qu’un simple appel de méthode simple peut modifier le flux de ton programme ?
