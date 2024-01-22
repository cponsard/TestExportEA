# Process View

![Create project](Createproject.png)

Le premier processus d�crit la cr�ation d'un projet et le lancement d'un crawl et continue jusqu'� obtenir les insights n�cessaires.
Dans ce processus nous avons 4 acteurs principaux:

* L'utilisateur
* L'interface utlisateur qui repr�sente l'application, s�par� en back-end et front-end.
* Le crawler
* L'API Facebook qui est la source des donn�es.

![Recrawl](Recrawl.png)

Dans le cadre de la vue de processus, le diagramme de s�quence UML montre (en plus de ce que nous voyons dans les diagrammes pr�c�dents) certaines des r�ponses que l'utilisateur voit sur l'�cran de l'interface utilisateur pendant qu'un processus est en cours d'ex�cution. Le processus en question est Le recrawl d'un projet ce qu'un utilisateur fait lorsqu'une mise � jour des informations est n�cessaire, l'utilisateur lance donc un nouveau crawl pour obtenir plus de donn�es et plus des insights.
Dans ce processus nous avons 7 acteurs principaux:

* L'utilisateur.
* L'interface utilisateur.
* Metric Computation .
* Application Management.
* Le crawler
* La base des donn�es.
* Le cache.


## Activity Retrieval of crawling results


## ActivityPartition User


## ActivityPartition User Interface


## ActivityPartition Crawler


## ActivityPartition Facebook API


## Actor User


## Sequence Application Mngt


## Sequence Cache


## Sequence Crawler


## Sequence DB


## Sequence Front-end


## Sequence Metric Computation

