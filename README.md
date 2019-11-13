# Nosql

1 -Definition

NoSQL désigne une famille de systèmes de gestion de base de données (SGBD) qui s'écarte du paradigme classique des bases relationnelles. L'explicitation du terme la plus populaire de l'acronyme est Not only SQL (« pas seulement SQL » en anglais).
Les SGBD relationnels créés dans les années 1970 se sont progressivement imposés jusqu'à devenir le paradigme de bases de données très largement dominant au début des années 1990.
 
 C'est dans le courant des années 2000 avec le développement de grandes entreprises internet (Google, Amazon, eBay…) brassant des quantités énormes de données et le développement de l'informatique en grappes que la domination sans partage du modèle relationnel a été remise en question car souffrant de limites rédhibitoires pour ces nouvelles pratiques.
 
 
2- Les pionniers du modèle NoSQL

Afin de répondre à ces limites des SGBD relationnels, certaines grandes entreprises ont commencé à développer leurs propres systèmes de gestion de bases de données pouvant fonctionner sur des architectures matérielles distribuées et permettant de traiter des volumes de données importants. Les systèmes propriétaires qui en ont résulté, 

- __BigTable__ developpé par Google   
-  __Dynamo (en)__, Amazon, 
- __Voldemort__, LinkedIn,  
- __Cassandra puis HBase__, Facebook, 
- __MongoDB__,SourceForge.net, 
- __CouchDB__, Ubuntu One,  
- __Hypertable__,  Baidu

3- Nosql avantage

Les caractéristiques principales des SGBD NoSQL sont de permettre la manipulation de volumes de données importants et de permettre une scalabilité horizontale. Ces systèmes ne respectent en général pas les standards des SGBD relationnels, mais il ne s'agit pas à proprement parler d'une propriété recherchée mais plus d'une concession permettant des traitements plus rapides pour certains types d'applications.
On pourrait dire que l’implémentation de bases de données NoSQL de source ouverte est rentable. Puisqu’ils n’ont pas besoin de frais de licence et peuvent fonctionner sur du matériel économique.

Un modèle typique en NoSQL est le système clé-valeur, avec une base de données pouvant se résumer topologiquement à un simple tableau associatif unidimensionnel avec des millions — voire des milliards — d'entrées. Parmi les applications typiques, on retrouve des analyses temps-réel, statistiques, du stockage de logs (journaux), etc.

4- Types de stockage de données NoSQL

- Entrepôt de valeurs clé
Dans l’entrepôt du type valeur clé, une table de hachage est utilisée dans laquelle une clé unique pointe vers un élément.
Les clés peuvent être organisées par groupes clé logiques. Seulement ces clés doivent être uniques dans leur propre groupe. Cela permet d’avoir des clés identiques dans différents groupes logiques.

- Entrepôt de documents
Les entrepôts de documents sont similaires aux entrepôts de valeurs clés, car ils ne possèdent pas de schéma et sont basés sur un modèle de valeur clé. Les deux manquent de cohérence au niveau de la base de données, ce qui permet aux applications de fournir plus de fiabilité.

Les différences les plus significatives sont:

– Dans l’entrepôt de documents, les valeurs (documents) fournissent un codage XML, JSON ou BSON (binaire codé JSON) pour les données stockées.

L’application de base de données la plus populaire, basée sur un entrepôt de documents, est MongoDB.

- Stockage en colonnes
Les données sont stockées dans des colonnes au lieu d’être stockées dans des lignes (comme c’est le cas de la plupart des systèmes de gestion de base de données relationnelles).

Un entrepôt de colonnes est composé d’une ou de plusieurs familles de colonnes regroupées de manière logique dans certaines colonnes de la base de données. Une clé est utilisée pour identifier et pointer un certain nombre de colonnes dans la base de données. Chaque colonne contient des lignes de noms ou des nuplets, ainsi que des valeurs, ordonnées et séparées par des virgules.

Les entrepôts de colonnes ont un accès rapide de lecture et écriture aux données stockées. Dans un entrepôt de colonnes, les lignes correspondant à une seule colonne sont stockées sous la forme d’une seule entrée de disque, ce qui facilite l’accès lors des opérations de lecture et d’écriture.

Les bases de données les plus populaires qui utilisent l’entrepôt de colonnes incluent Google BigTable, HBase et Cassandra.

-Base graphique
Dans un graphe d’une base de données NoSQL, une « structure de graphe dirigée » est utilisée pour représenter les données. Le graphique est composé d’arêtes et de nœuds.

Formellement, un graphique est une représentation d’un ensemble d’objets dont certaines paires d’objets sont reliées par des liens. Les objets interconnectés sont représentés par des abstractions mathématiques, appelées sommets, et les liens qui connectent certaines paires de sommets sont appelés des arêtes. Donc un graphique est un type de représentation de données composé d’un ensemble de sommets et d’arêtes se connectant les uns aux autres, montrant visuellement leur relation mathématique.

4- Eemple de NoSQL

- __Accumulo__, fondation Apache, Licence Apache 2.0, dérivé d'Hadoop avec des fonctions de sécurité augmentées
- __Berkeley DB__, Oracle Corporation, il existe deux versions en licence libre et propriétaire
-__BigTable__, Google, privé, depuis mai 2015 il existe une version publique sous licence propriétaire
- __Hypertable__, Zvents, GNU GPL 2.0, sponsorisé par Baidu depuis 2009
- __Cassandra__, fondation Apache, Licence Apache 2.0, utilisé par Twitter, Digg...
 - __CouchDB__, fondation Apache, Licence Apache 2.0, NoSQL orienté-document
- __DEX/Sparksee__, Sparsity Technologies, propriétaire, NoSQL orienté graphe
- __DocumentDB__, Microsoft Azure, propriétaire
- __DynamoDB (en)__, Amazon, propriétaire, utilisable essentiellement via Amazon Web Services
- __Elassandra__, version augmentée de Cassandra intégrant un moteur de recherche Elasticsearch, sous Licence Apache 2.0
- __HBase__, fondation Apache, Licence Apache 2.0, dérivé d'Hadoop, utilisé notamment par Facebook
- __MongoDB__, MongoDB Inc., GNU AGPL, NoSQL orienté-document
- __Neo4j__, Neo Technology Inc, GNU GPLv3 et GNU AGPLv3, NoSQL orienté graphe
- __OrientDB__, OrientDB Ltd, Licence Apache 2.0, NoSQL orienté graphe
- __projet Voldemort__, LinkedIn, privé avec versions publiques sous Apache License 2, stockage de données distribué
- __Redis__, Salvatore Sanfilippo sponsorisé par RedisLab, licence BSD
- __Riak__, Basho Technologies, Licence Apache 2.0 avec modules complémentaires payants (propriétaires), inspiré de DynamoDB
- __SimpleDB__ (Amazon.com), mis à disposition via Amazon Web Services
- __Oracle NoSQL (en)__, Oracle Corporation, propriétaire
