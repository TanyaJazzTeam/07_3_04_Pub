# SI playbook 003

## Scope of a SIG 001

TensorFlow héberge *des groupes d'intérêts spéciaux* (GIS) pour concentrer la collaboration sur des domaines particuliers. Les SIG font leur travail en public. Pour rejoindre et contribuer, passez en revue le travail du groupe et entrez en contact avec le leader SIG. Les politiques d'adhésion varient d'un SIG à l'autre.

Le périmètre idéal d'un SIG répond à un domaine bien défini, où la majorité de la participation est issue de la communauté. De plus, il doit y avoir suffisamment de preuves que des membres de la communauté sont prêts à s'engager et à contribuer si le groupe d'intérêt est établi.

Tous les SIG n'auront pas le même niveau d'énergie, la même portée ou les mêmes modèles de gouvernance, alors attendez-vous à une certaine variabilité.

Consultez la liste complète des [SIG TensorFlow](https://github.com/tensorflow/community/tree/master/sigs) .

### 002 Non-goals: What a SIG is *not*

Les SIG sont destinés à faciliter la collaboration sur le travail partagé. Un SIG c'est donc :

- *Pas un forum de support* : une liste de diffusion et un SIG ce n'est pas la même chose.
- *Pas immédiatement requis* : au début de la vie d'un projet, vous ne savez peut-être pas si vous avez partagé du travail ou des collaborateurs.
- *Travail non gratuit* : il faut de l'énergie pour grandir et coordonner le travail en collaboration.

Notre approche de la création de SIG sera conservatrice : grâce à la facilité de démarrage de projets sur GitHub, il existe de nombreuses possibilités de collaboration sans avoir besoin d'un SIG.

## SIG lifecycle 004

### Research and consultation 005

Les proposants de groupes doivent rassembler des preuves pour approbation, comme indiqué ci-dessous. Voici quelques pistes possibles à considérer :

- Un problème bien défini ou un ensemble de problèmes que le groupe résoudrait.
- Consultation avec les membres de la communauté qui en bénéficieraient, évaluant à la fois le bénéfice et leur volonté de s'engager.
- Pour les projets existants, preuve à partir des problèmes et des relations publiques que les contributeurs se soucient du sujet.
- Objectifs potentiels que le groupe doit atteindre.
- Besoins en ressources pour faire fonctionner le groupe.

Même si la nécessité d'un SIG semble aller de soi, la recherche et la consultation sont toujours importantes pour le succès du groupe.

### Création du nouveau groupe 006

Le nouveau groupe doit suivre le processus ci-dessous pour l'affrètement. Il doit notamment démontrer :

- Un objectif et un avantage clairs pour TensorFlow (que ce soit autour d'un sous-projet ou d'un domaine d'application)
- Deux contributeurs ou plus désireux d'agir en tant que chefs de groupe, existence d'autres contributeurs et preuve de la demande pour le groupe
- Les ressources dont il aura besoin initialement (généralement, une liste de diffusion et un appel VC régulier.)

L'approbation du groupe sera donnée par une décision de l'équipe communautaire TF, définie comme étant les mainteneurs du projet tensorflow/communautaire. L'équipe consultera d'autres parties prenantes si nécessaire.

Avant d'entrer dans les parties formelles du processus, il est conseillé de consulter l'équipe de la communauté TensorFlow, community-team@tensorflow.org. Il est fort probable qu'une conversation et une itération seront nécessaires avant que la demande SIG ne soit prête.

La demande formelle pour le nouveau groupe se fait en soumettant une charte en tant que PR à tensorflow/community, et en incluant la demande dans les commentaires sur le PR (voir modèle ci-dessous). Après approbation, le PR du groupe sera fusionné et les ressources nécessaires créées.

### Modèle de demande de nouveau SIG

Ce modèle sera disponible dans le dépôt de la communauté : [SIG-request-template.md](https://github.com/tensorflow/community/blob/master/governance/SIG-request-template.md) .

### Affrètement

Chaque groupe sera établi avec une charte et sera régi par le code de conduite TensorFlow. Les archives du groupe seront publiques. L'adhésion peut être soit ouverte à tous sans approbation, soit disponible sur demande, en attendant l'approbation de l'administrateur du groupe.

La charte doit nommer un administrateur. En plus d'un administrateur, le groupe doit inclure au moins une personne en tant que responsable (il peut s'agir de la même personne), qui servira de point de contact pour la coordination requise avec l'équipe de la communauté TensorFlow.

Cette charte sera publiée dans un premier temps sur la liste de diffusion du groupe. Le référentiel communautaire de l'organisation TensorFlow GitHub archivera ces documents et politiques ( [exemple de Kubernetes](https://github.com/kubernetes/community) ). À mesure qu'un groupe fait évoluer ses pratiques et ses conventions, nous nous attendons à ce qu'il les documente dans la partie pertinente du référentiel communautaire.

### Collaboration et inclusion

Bien que cela ne soit pas obligatoire, le groupe doit choisir d'utiliser la collaboration via des conférences téléphoniques programmées ou des canaux de discussion pour organiser des réunions. Toute réunion de ce type doit être annoncée sur la liste de diffusion et les notes postées sur la liste de diffusion par la suite. Des réunions régulières contribuent à la responsabilisation et au progrès dans un SIG.

Les membres de l'équipe de la communauté TensorFlow surveilleront de manière proactive et encourageront le groupe à discuter et à agir, le cas échéant.

### Lancement

Activités requises :

- Notification des groupes de discussion généraux de TensorFlow ( [discussion@](https://groups.google.com/a/tensorflow.org/forum/#!forum/discuss) , [développeurs@](https://groups.google.com/a/tensorflow.org/forum/#!forum/developers) ).
- Ajout de SIG aux pages de la communauté sur le site Web de TensorFlow.

Activités optionnelles :

- Création d'un article de blog pour la communauté de blogs TensorFlow.

### Santé et résiliation des SIG

L'équipe de la communauté TensorFlow fera de son mieux pour assurer la santé des SIG. De temps en temps, il demandera au responsable du SIG de fournir un rapport sur le travail du SIG, qui sera utilisé pour informer la communauté TensorFlow au sens large de l'activité du groupe.

Si un SIG n'a plus de but utile ou de communauté intéressée, il peut être archivé et cesser ses activités. L'équipe de la communauté TF se réserve le droit d'archiver ces SIG inactifs, afin de maintenir la santé du projet dans son ensemble, bien que ce soit un résultat moins préférable. Un SIG peut également choisir de se dissoudre s'il reconnaît qu'il a atteint la fin de sa vie utile.
