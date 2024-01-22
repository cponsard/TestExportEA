# Logical View

![Logical View](LogicalView.png)

Cette vue introduit les composants logiques, de haut niveau, de l'architecture de fa&#231;on statique et ind�pendamment de toutes impl�mentations techniques. Elle permet d'identifier les diff�rents composants et m�canismes du syst�me � r�aliser et de d�finir pour chacun d�eux leur(s) r�le(s) technologique(s)

## Front-end

### Module Crawlers
g�re les crawlers  (d�marrage/arr�t) et vide les files d'attente.

### Module Insights


### Module Persona


### Module Projects


### Module Tags


## Back-end

### Module Cache Mngt


### Module Crawler Orchestrator


### Module Insights Mngt
le composant qui cr�e les insights

### Module Metric computation
le composant qui traite les donn�es crawl�es en effectuant des calculs et des statistiques.

### Module Persona Mngt
 le composant qui cr�e un persona et permet � l'utilisateur de voir et de modifier des personas.

### Module Project Mngt
le composant qui cr�e les entreprises et les g�re (ajout/suppression des membres, etc.).

### Module Tag Mngt
le composant qui cr�e les tags et les g�re (ajout de crit�res / suppression de tag).

### Module User Mngt
le composant qui cr�e les utilisateurs et les g�re (cr�er / supprimer / modifier).

## Data Retrieval

## Data Storage

### Module Cache
emplacement de stockage r�serv� qui collecte les donn�es calcul�e

### Module Config files
les fichiers de configuration du syst�me.

### Module Crawled Data
donn�es stock�es par les crawlers provenant de sources de donn�es tierces.

### Module Internal Data
les donn�es internes du syst�me telles que les companies,les utilisateurs, les projets, etc.
