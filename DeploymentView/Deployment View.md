# Deployment View

![Deployment View](DeploymentView.png)



## ExecutionEnvironment Kubernetes
Kubernetes (commun�ment appel� &#171; K8s2 &#187;) est un syst�me open source qui vise � fournir une &#171; plate-forme permettant d'automatiser le d�ploiement, la mont�e en charge et la mise en �uvre de conteneurs d'application sur des grappes de serveurs3 &#187;. Il fonctionne avec toute une s�rie de technologies de conteneurisation, et est souvent utilis� avec Docker.
https://kubernetes.io

## Node Master
Le ma�tre Kubernetes est l'unit� de contr�le principale qui g�re la charge de travail et dirige les communications dans le syst�me. Le plan de contr�le de Kubernetes consiste en plusieurs composants, chacun ayant son propre processus, qui peuvent s'ex�cuter sur un seul n�ud ma�tre ou sur plusieurs ma�tres permettant de cr�er des clusters haute disponibilit�.

## Node Node1
POD: partie front-end

## Node Node2
POD: metric computation

## Node Node3
POD: crawler orchestrator

## Node Node4
POD: data storage
