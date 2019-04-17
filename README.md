# devops-test


L'objectif de l'exercice est de construire totalement via cloudformation les éléments présents
sur le schéma devops.png. Il y a plusieurs façon de faire, et l'organisation choisie
sera un critère de jugement du travail fourni.
2 app de tests sont fournis dans le dossier service. Tu mettras en output de ta/tes stack(s) 
un lien vers les 2 apps (des makefile sont fournis pour un build local)
XXXeu-west-1-alb.amazonaws.com/ ==> website service
XXXeu-west-1-alb.amazonaws.com/products ==> ... product service

Absoluement tous les éléments doivent être cloudformation-isé : infra, lambda, services etc ...
Tu as un compte et peut utiliser n'importe quel produit au besoin (bucket, EC2, etc ...).
L'exercice est faisable en 2h environ.
