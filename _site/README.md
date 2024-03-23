## Ajouter des posts

 - Ajouter un fichier **.markdown** dans le dossier **/_posts**
 - Le nom du fichier doit commencer par la date suivi du nom du fichier
 > **Exemple**: 2022-09-11-forum-associations.markdown
 - Si le post doit relier vers un document PDF > Ajouter les deux paramètres **button_name** et **doclink**. Les fichiers PDF sont à ajouter dans le dossier **/doc**
 - Si le post doit être rattaché à un tag > Ajouter les deux paramètres **tags** et **tag_url** . Les tags disponibles sont dans le dossier **/tag/**
 - Si le post n'a pas besoin de relier vers un document PDF > changer le paramètre  **category**  en 'message'
 
 Ci-dessous un exemple de post récent qui peut servir de template : 
 

    layout: default
    date: 2022-09-11
    img: 
    category: info
    title: "Participation au forum des associations 2022"
    description: "Voici ci-joint le compte-rendu de notre journée au forum des associations de la ville de Septèmes. Bonne 
    lecture !"
    tags: association
    tag_url: /association/
    button_name: Lire le compte-rendu
    doclink: "doc/forum_associations_2022.pdf"
    meta: "noindex"
