# stock-on-premise

historique

22-08-25 22h00 gmt+1
-a été uploadé dans le repertoire donc les differents diagrammes dont les mockup créé pendant la conception


Logiciel de gestion logistique & RH pour une ASBL humanitaire

Ce dépôt regroupe les annexes du TFE, les codes sources (applications desktop & Android) et les programmes/scripts d’installation du projet : « Réalisation d’un logiciel de gestion des opérations logistiques et des ressources humaines pour une ASBL humanitaire ». Les annexes incluent notamment le lexique, glossaire, diagrammes, wireframes, cas d’usage, RGPD, plan de tests et code source documenté. 

Pourquoi ce projet ?

Répondre à des besoins de terrain (planning bénévoles/bénéficiaires, stock vestiaire/brocante, traçabilité, sécurité des données). 

Fonctionner avec peu de moyens : matériel existant, Windows 10, Android pour l’envoi de SMS, SQLite offline + PostgreSQL central, Samba/AD, Mailcow, Proxmox. 

Offrir une solution modulaire et documentée : annexes, manuels, procédures d’installation/déploiement. 

Contenu du dépôt

doc/ — Tous les documents annexes (lexique, glossaire, figures, use cases, diagrammes d’activité & de séquence, wireframes, RGPD, plan de tests, etc.). contient aussi les manuels d'utilisation et de déploiement

source/

build/ — Programmes & scripts d’installation (serveur, clients, bases, services). 


Périmètre fonctionnel (aperçu)

S1 : Planification — Création d’événements, créneaux, rappels SMS.

S2 : Vestiaire/Brocante — Stocks, ventes, tickets, codes-barres, statistiques.

S3 : Local informatique — Postes reconditionnés, impression, proxy/filtrage.

S4 : Secrétariat — Accès à l’imprimante réseau.

S5 : Données & accès — Centralisation, VPN, serveur mail/scans. 

 
Statut & contributions

Le dépôt publie la version TFE .
