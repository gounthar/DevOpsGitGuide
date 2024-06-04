Exercices [1](https://gounthar.github.io/learning-2024-devops/shell/#%F0%9F%A7%AA-exercise-1-file-system-management), [1-Bis](https://gounthar.github.io/learning-2024-devops/shell/#%F0%9F%A7%AA-exercise-1-bis-file-system-management), [2-Bis](https://gounthar.github.io/learning-2024-devops/shell/#%F0%9F%A7%AA-exercise-2-bis-cron-on-gitpod), [2-Ter](https://gounthar.github.io/learning-2024-devops/shell/#%F0%9F%A7%AA-exercise-2-ter-make-cron-available-on-gitpod-from-the-start) pour le [Shell](https://gounthar.github.io/learning-2024-devops/shell/), à rendre avant le 04 juin 2024.

# Projet DevOps 2024

## Objectifs

Ce projet a pour but de vous familiariser avec les concepts et outils DevOps, notamment Git, Bash et GitHub.
Vous allez travailler sur plusieurs tâches qui vous aideront à comprendre ces outils et à les utiliser efficacement dans vos futurs projets.

## Points d'attention

Pour chacune de ces tâches, créez une branche spécifique dans votre dépôt Git (`git checkout -b "branche-de-travail" origin/main`).
Une fois la tâche terminée, _committez_ (`git add` puis `git commit`), _pushez_ (`git push -u origin "branche-de-travail"`), ouvrez une Pull Request et faites le _merge_ vers `main`.
Ensuite, effacez votre branche de travail.

## En cas de difficulté

Je suis joignable sur la messagerie de l'école, sur Discord ou sur mon mail personnel.
N'hésitez pas à me contacter si vous avez des questions ou des difficultés.

## Tâches préliminaires

1. **Comprendre Git et GitHub :** Familiarisez-vous avec les concepts de base de Git et GitHub. Vous pouvez utiliser [ce lien](https://guides.github.com/introduction/git-handbook/) pour commencer.

2. **Apprendre le Bash :** Familiarisez-vous avec le langage de script Bash. Vous pouvez utiliser [ce lien](https://www.learnshell.org/) pour commencer.
Par la suite, [ce site](https://hangar118.sdf.org/p/bash-scripting-guide/) vous en apprendra plus.

3. **Créer un dépôt GitHub :** Créez un nouveau dépôt sur GitHub. Vous pouvez nommer le dépôt comme vous le souhaitez, mais assurez-vous que le nom est descriptif et concis.

4. **`.gitignore` :** Apprenez à utiliser le fichier `.gitignore` pour ignorer les fichiers et les dossiers qui ne devraient pas être suivis par Git (notamment ceux liés à votre IDE).
Il se peut que votre IDE ait déjà créé un fichier `.gitignore` pour vous. Si ce n'est pas le cas, vous pouvez en créer un vous-même.
Ajoutez un fichier `.gitignore` à votre dépôt. Vous pouvez en savoir plus sur .gitignore [ici](https://git-scm.com/docs/gitignore).

5. **Inclure une licence :** [Ajoutez un fichier de licence](https://docs.github.com/fr/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository) à votre dépôt. C'est une bonne pratique lorsque vous partagez du code publiquement, car cela indique aux autres ce qu'ils peuvent et ne peuvent pas faire avec le code.

6. **Ajouter un fichier README.md :** [Ajoutez un fichier README.md](https://docs.github.com/fr/repositories/creating-and-managing-repositories/best-practices-for-repositories#create-a-readme-file) à votre dépôt. Ce fichier devra par la suite contenir une description de votre projet, des instructions pour l'exécuter et des informations sur la manière de contribuer.
Il faudra aussi bien sûr me préciser votre nom dans le `README.md` car votre _handle_ GitHub ne me permet pas forcément de retrouver votre nom. :shrug:
7.  **Installer l'extension GitPod**: [Installer l'extension GitPod](https://www.gitpod.io/docs/introduction/getting-started#install-the-browser-extension) pour votre navigateur.

## Tâches du projet

1. **Créer un script** qui organise les fichiers dans un répertoire, liste les permissions et effectue des opérations de base comme décrit [ici](https://gounthar.github.io/learning-2024-devops/shell/#%F0%9F%A7%AA-exercise-1-file-system-management).
2. **Créer un script** qui effectue les changements sur les fichiers comme décrit [ici](https://gounthar.github.io/learning-2024-devops/shell/#%F0%9F%A7%AA-exercise-1-bis-file-system-management).
3. **Créer un script** qui ajoute une tâche `cron` comme décrit [ici](https://gounthar.github.io/learning-2024-devops/shell/#%F0%9F%A7%AA-exercise-2-bis-cron-on-gitpod).
4. **_"gitpodiser"_** le repository en créant deux fichier `.gitpod.Dockerfile` et `.gitpod.yml` comme décrit [ici](https://gounthar.github.io/learning-2024-devops/shell/#%F0%9F%A7%AA-exercise-2-ter-make-cron-available-on-gitpod-from-the-start).
5. **Ouvrir une Pull Request :** Une fois votre repository créé et les tâches précédentes terminées, ouvrez une [Pull Request sur ce repository](https://github.com/gounthar/DevOpsGitGuide/compare) pour que je puisse examiner votre travail.
Cette [PR](https://docs.github.com/fr/pull-requests) contiendra une modification de ce fichier README.md, où vous ajouterez le lien vers votre dépôt. N'oubliez pas de me donner les droits de lecture sur votre dépôt s'il n'est pas public.
Il faudra donc au préalable forker ce repository, le cloner en local, créer une branche, ajouter votre nom et le lien vers votre dépôt dans ce fichier README.md, _committer_, _pusher_ et enfin ouvrir une Pull Request depuis votre branche vers ma branche `main`.

N'oubliez pas, l'objectif est non seulement de vous familiariser avec Git et GitHub, mais aussi de suivre les meilleures pratiques lors de la réalisation d'un projet logiciel.

Bonne chance!

## Notation

1. **Comprendre Git et GitHub (2 points) :** Sera évalué en regardant votre historique de commits, l'utilisation des branches, et la gestion globale de votre dépôt.

2. **Apprendre le Bash (2 points) :** Sera évalué en examinant les scripts (syntaxe correcte, utilisation des variables).

3. **Créer un dépôt GitHub (1 point) :** 

4. **Utiliser `.gitignore` (1 point) :** Le fichier `.gitignore` devrait être présent dans le dépôt et devrait inclure des entrées pour les fichiers et dossiers qui ne sont généralement pas suivis dans un dépôt Git.

5. **Inclure une licence (1 point) :** Le fichier de licence devrait clairement indiquer les conditions sous lesquelles d'autres peuvent utiliser votre code.

6. **Ajouter un fichier `README.md` (1 point) :** Le fichier `README.md` devrait inclure une description du projet, des instructions pour l'exécuter, et des informations sur comment contribuer.

7. **Créer un script pour la gestion du système de fichiers (3 points) :** Efficacité et lisibilité. Le script devrait effectuer correctement les opérations du système de fichiers spécifiées.

8. **Créer un script pour les modifications de fichiers (3 points) :** Efficacité et lisibilité. Le script devrait effectuer correctement les modifications de fichiers spécifiées.

9. **Créer un script pour ajouter une tâche cron (3 points) :** Efficacité. Le script devrait correctement ajouter une tâche cron comme spécifié.

10. **"Gitpodiser" le dépôt (3 points) :** Création et configuration des fichiers `.gitpod.Dockerfile` et `.gitpod.yml`. L'espace de travail Gitpod devrait être correctement configuré avec les outils et configurations nécessaires.

Le nombre total de points que vous pouvez obtenir est de 20.

## Liste des repositories

1. BARBIER Lucas : https://github.com/lbarbier22/DevOpsTDRepo.git
2. Valentin Boulanger : https://github.com/ValaK47/TPDevOPS.git
3. Thomas KUREK : https://github.com/Thomask25/DevOpsTK
4. Antoine CABY : https://github.com/antoinecaby/devops
5. Hector ROUSSEL : https://github.com/Ryujin42/DevOps.git
6. Arthur Hallez : https://github.com/arthur59930/Devoir-Dev-SecOps
7. Quentin MOSKWA : https://github.com/QuentinMoskwa/DevOpsGitTP.git
8. Adrien DUPONT : https://github.com/Adrienfdupont/devops
9. Brandon MATHUREL : https://github.com/BdnKingOfApes/DevOps1
10. Jason HIBLOT : https://github.com/Poliuth/DevOps
11. Leeo JANON : https://github.com/lethmeshine/devops
12. Vincent MOYAUX : https://github.com/Vincent-M04/DevOps
13. Abdessalem Saadaoui : https://github.com/abdessalems/dev_ops_project
14. Mathys Caron : https://github.com/MathysCaron/projet-devops-2024
15. Benoît Lavoine: https://github.com/Tionebl/projet-devops-204
16. RIBOULET Tristan: https://github.com/TristanRib/DevOpsGit.git
17. Thomas Busin : https://github.com/ThomBsn/TDDevOps
18. Geoffrey Poiret : https://github.com/GeoGeo0059/DevOps_2024
19. Emma Salot : https://github.com/EmmaSalot/tp_devops
20. Amalric Vaurs : https://github.com/avaurs/devops.git
21. Tom Notebaert : https://github.com/Reacerre/TaskManager.git
22. Zakaria HAJJI : https://github.com/hajji01/Devops
23. Asmae MABROUK : https://github.com/Asmae-Mabrouk/Devops_Tp_1
24. Samuel Degrande : https://github.com/Algamor59/TPDevOPSDegrandeS
25. Romain BELHIS : https://github.com/Ro0M1/TpDevOps.git
