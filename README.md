# devops-test


L'objectif de l'exercice est de construire totalement via cloudformation les éléments présents
sur le schéma devops.png. Il y a plusieurs façon de faire, et l'organisation choisie
sera un critère de jugement du travail fourni.
2 app de tests sont fournis dans le dossier service. Il faudra mettre (entre autres choses) en output de stack 
un lien vers les 2 apps déployées sur ECS. Il sera également attendu de déployer une lambda (vous avez le choix du langage) afin de gérer les hooks de lifecycle quand une instance est mise dans l'état "Terminated". Comme le reste, cette lambda devra être incluse dans une stack.
XXXeu-west-1-alb.amazonaws.com/ ==> website service
XXXeu-west-1-alb.amazonaws.com/products ==> ... product service

Certains éléments implicites peuvent ne pas être indiquées sur le schéma.
Par ailleurs, le schéma présente le traffic entrant. Il faudra également inclure dans votre travail tout éléments nécessaire à prendre en charge le traffic sortant si nécessaire.
Absoluement tous les éléments doivent être mis sous forme de stack cloudformation : infra, lambda, services, logs, autorisations iam etc ...
Vous avez à disposition un compte de test sur lequel vous avez des droits d'admin et vous pouvez donc utiliser ce qu'il vous semblera nécessaire pour mener à bien la tâche (bucket, EC2, pusher les builds dans ECR etc ...).
L'exercice est faisable en 2h environ. Des identifiants, ainsi que des ACCESS KEY ID et SECRET KEY ID vous seront fournis par mail. Le travail se fera sur la zone eu-west-1.


![test architecture](/devops_test/devops.png)
