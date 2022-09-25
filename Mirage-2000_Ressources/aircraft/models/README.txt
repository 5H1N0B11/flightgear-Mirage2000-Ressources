hardball 2022-09-25
===================

Some changes made to be compatible with blender 2.83.5 (no more layers and changes on texture system).


**exporter [lang=FR]**

Le fichier m2000B-3.blend contient quasiment tous les modèles 3d utilisés pour le mirage 2000.

Je fais exception de certains modèles distinct (feux de vol en formation, trappe "pin=up") ou de sous modèles (emports).

Comme il y a beaucoup de modèles, pour s'y retrouver et travailler plus facilement, j'ai regroupé certains objets en collections.

Pour exporter les fichiers .ac, il faut s'aider du nom que j'ai donné aux collections :

- la première partie donne le nom du fichier (relatif à Mirage-2000/Models/)
- la partie (optionnelle) entre parenthèses signale si il faut afficher plusieurs collections pour générer le fichier .ac
- la partie (optionnelle) entre crochets donne des informations sur la collection
- cas particulier pour `Interior/Instruments/*/*.ac`, voir plus bas

Exemple

pour créer le fichier `m2000-5.ac` :

1. cacher toutes les collections
2. afficher les collections
    - m2000-5.ac(1/3)[common objects]
    - m2000-5.ac(2/3)[biplace objects]
    - m2000-5.ac(3/3)[monoplace objects]
3. exporter
4. enregistrer sous : `Mirage-2000/Models/m2000-5.ac`


Cas particulier pour la collection `Interior/Instruments/*/*.ac`, chaque groupe correspond à un fichier.

1. cacher toutes les collections
2. afficher uniquement la collection Interior/Instruments/*/*.ac
3. afficher uniquement `group-adi`
4. exporter 
5. enregistrer sous : `Interior/Instruments/adi/adi.ac`













