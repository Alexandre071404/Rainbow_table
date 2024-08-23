• Titre : Tables arc-en-ciel

Les rainbow tables sont des outils utilisés pour découvrir des mots de passe en utilisant des "hash". Un hash est une sorte d'empreinte numérique d'un mot de passe, créée par des algorithmes spéciaux.

Imaginons que vous avez un mot de passe, comme "motdepasse123". Lorsqu'il est transformé en hash, il ressemble à une chaîne de caractères très longue et compliquée. Les rainbow tables sont des listes de ces chaînes longues, pour de nombreux mots de passe possibles.

Au lieu de recalculer le hash pour chaque mot de passe, ce qui prend du temps, les rainbow tables vous permettent de comparer directement les hash pour voir s'ils correspondent à celui que vous cherchez. Elles rendent le processus beaucoup plus rapide en utilisant des données pré-calculées.




• Comment exécuter le projet

Avant de d'éxécuter les commandes il faut se placer dans le dossier fauquette-rabot-mahier-transon.

Lancer l'application (initialisation + compilation + test unitaire + exécution) :
- ant run
Lancer les tests (initialisation + compilation) :
- ant test
Générer la javadoc : 
- ant javadoc
Générer l'archive jar :
- ant packaging

• Contributeurs :

- MAHIER Awen
- FAUQUETTE Mael
- RABOT Valentin
- TRANSON Alexandre



Title: Rainbow Tables

Rainbow tables are tools used to find passwords using "hashes." A hash is a type of digital fingerprint of a password, created by special algorithms.

Imagine you have a password, like "password123." When it is turned into a hash, it looks like a very long and complicated string of characters. Rainbow tables are lists of these long strings for many possible passwords.

Instead of recalculating the hash for each password, which takes time, rainbow tables let you directly compare the hashes to see if they match the one you are looking for. They make the process much faster by using pre-calculated data.

How to Run the Project

Before running the commands, go to the fauquette-rabot-mahier-transon folder.

To run the application (initialization + compilation + unit test + execution):

ant run
To run the tests (initialization + compilation):

ant test
To generate the javadoc:

ant javadoc
To create the jar archive:

ant packaging


• Contributors :

- MAHIER Awen
- FAUQUETTE Mael
- RABOT Valentin
- TRANSON Alexandre