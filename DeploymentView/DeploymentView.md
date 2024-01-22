# Deployment View

![Deployment View](DeploymentView.png)



## ExecutionEnvironment Kubernetes
Kubernetes (communément appelé &#171; K8s2 &#187;) est un système open source qui vise à fournir une &#171; plate-forme permettant d'automatiser le déploiement, la montée en charge et la mise en œuvre de conteneurs d'application sur des grappes de serveurs3 &#187;. Il fonctionne avec toute une série de technologies de conteneurisation, et est souvent utilisé avec Docker.
https://kubernetes.io

## Node Master
Le maître Kubernetes est l'unité de contrôle principale qui gère la charge de travail et dirige les communications dans le système. Le plan de contrôle de Kubernetes consiste en plusieurs composants, chacun ayant son propre processus, qui peuvent s'exécuter sur un seul nœud maître ou sur plusieurs maîtres permettant de créer des clusters haute disponibilité.

## Node Node1
POD: partie front-end

## Node Node2
POD: metric computation

## Node Node3
POD: crawler orchestrator

## Node Node4
POD: data storage
