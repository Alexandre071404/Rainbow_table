• Titre : Tables arc-en-ciel

Les rainbow tables sont des outils utilisés pour découvrir des mots de passe en utilisant des "hash". Un hash est une sorte d'empreinte numérique d'un mot de passe, créée par des algorithmes spéciaux.

Imaginons que vous avez un mot de passe, comme "motdepasse123". Lorsqu'il est transformé en hash, il ressemble à une chaîne de caractères très longue et compliquée. Les rainbow tables sont des listes de ces chaînes longues, pour de nombreux mots de passe possibles.

Au lieu de recalculer le hash pour chaque mot de passe, ce qui prend du temps, les rainbow tables vous permettent de comparer directement les hash pour voir s'ils correspondent à celui que vous cherchez. Elles rendent le processus beaucoup plus rapide en utilisant des données pré-calculées.

Le concept de couleur dans les rainbow tables est un peu lié à leur nom, mais il est plus technique que simplement esthétique.

Explications: 

Hashing et Réduction : Pour créer une rainbow table, on utilise un processus qui consiste à transformer un mot de passe en une chaîne de caractères (le hash) et à la réduire à une autre forme pour créer une nouvelle chaîne, puis à répéter ce processus plusieurs fois. Chaque fois qu'on transforme le mot de passe en hash, on le passe à travers une fonction de réduction pour obtenir une nouvelle chaîne.

Chaînes de Réduction : Imaginez une chaîne où chaque maillon est une version hashée du mot de passe, réduite pour être utilisée comme point de départ pour générer un nouveau hash. Cela forme une séquence de hash et de mots de passe réduits.

Tables de Couleurs : Dans les rainbow tables, chaque couleur représente une chaîne unique de réductions, avec un point de départ et un point d'arrivée. Plutôt que de stocker chaque hash possible, la table stocke seulement les points de départ et d'arrivée de ces chaînes, ce qui réduit la quantité de données nécessaires.

Effet des Couleurs : En utilisant ces chaînes, les rainbow tables permettent de retrouver plus rapidement le mot de passe original en comparant les hash obtenus avec ceux stockés dans la table. Le terme "rainbow" (arc-en-ciel) fait référence à la variété des couleurs (chaînes) utilisées dans ce processus pour rendre la recherche plus efficace.


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

The concept of color in rainbow tables is somewhat related to their name, but it's more technical than just aesthetic.

Explanation:

Hashing and Reduction: To create a rainbow table, you use a process that turns a password into a string of characters (the hash) and then reduces it to another form to create a new string. This process is repeated many times. Each time you turn the password into a hash, you pass it through a reduction function to get a new string.

Reduction Chains: Imagine a chain where each link is a hashed version of the password, reduced to be used as a starting point for generating a new hash. This forms a sequence of hashes and reduced passwords.

Color Tables: In rainbow tables, each color represents a unique reduction chain, with a starting point and an ending point. Instead of storing every possible hash, the table only stores the starting and ending points of these chains, which reduces the amount of data needed.

Effect of Colors: By using these chains, rainbow tables allow you to find the original password more quickly by comparing the obtained hashes with those stored in the table. The term "rainbow" refers to the variety of colors (chains) used in this process to make the search more efficient.


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