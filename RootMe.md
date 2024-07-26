# Challenge RootMe SIP Authentification

## Énoncé

* Retrouvez le mot de passe utilisé pour s’authentifier sur l’infrastructure SIP.

[Uploading Challe[InternetShortcut]
URL=https://www.root-me.org/fr/Challenges/Reseau/SIP-Authentification
nges_Réseau SIP - Authentification [Root Me plateforme d'apprentissage dédiée au Hacking et à la Sécurité de l'Information.url…]()


## Conclusion

la premiere ligne de code indique un mot de passe NON chiffré (plain) qui a pour fonction REGISTER(authentification) le mot de passe est donc 1234 comme indiqué.


# Le SIP c'est quoi ?

Le Session Initiation Protocol (SIP) gère la mise en place et la suppression des connexions audio et vidéo en temps réel. Il est notamment utilisé dans la téléphonie en VoIP.

Au bureau comme à la maison, la vie quotidienne est de plus en plus rythmée par les vidéoconférences, messages instantanés, fichiers partagés, appels téléphoniques par VoIP ou toute autre forme de communication en temps réel. Une seule et unique technologie permet toutes ces applications : le Session Initiation Protocol ou protocole SIP. 

Ce protocole réseau est très important pour l’établissement de la communication, la commande et la suppression ultérieure des conversations audio ou vidéo par VoIP (Voice over IP) avec deux membres au moins. Le protocole SIP, composant de premier plan dans le domaine de la communication en temps réel, tient compte des particularités des réseaux IP.

L’introduction du protocole SIP, spécifié dans la RFC 3261, a fait de la téléphonie sur Internet une véritable alternative aux appels téléphoniques traditionnels par système téléphonique matériel. Avec le protocole SIP, tout le monde profite d’une mobilité beaucoup plus grande et d’une économie financière non négligeable. Ces deux avantages déterminants ont permis au SIP de jouer un rôle croissant depuis son introduction en 2004 jusqu’à aujourd’hui. Il va même jusqu’à remplacer presque complètement les lignes téléphoniques fixes.

Le Session Initiation Protocol se base sur le texte, d’une manière comparable au HTTP (Hypertext Transfer Protocol) pour le Web et au SMTP (Simple Mail Transfer Protocol) pour la communication électronique.

## Quelles sont les fonctions du protocole SIP ?
Comme les deux autres protocoles, SIP fonctionne sur la cinquième couche du modèle OSI, à savoir la couche session (en anglais Session Layer). La tâche du protocole SIP ressemble à celle d’un tableau commutateur des débuts du téléphone. À l’époque, le rôle des standardistes consistait d’abord à établir la ligne pour un appel entre deux personnes. La ligne ouverte était maintenue au cours de la conversation puis interrompue à la fin de la discussion entre les deux parties, la laissant à nouveau libre pour d’autres appels. Ce rôle est aujourd’hui rempli par le SIP. En revanche, le Session Initiation Protocol ne gère aucune autre facette de la communication.

L’extension SIPS (pour Session Initiation Protocol Secure) permet au protocole SIP d’établir des lignes pour des conversations sécurisées et chiffrées. Comme la session et le média sont deux choses différentes, leurs flux de données respectifs peuvent en théorie être chiffrés de manière indépendante. Quelques autres protocoles permettent la transmission des seules données vocales, par exemple le Real Time Transport Protocol (RTP) et le Session Description Protocol (SDP), qui fournit des adresses IP.

## Comment fonctionne le protocole SIP ?
Le protocole SIP utilise une architecture client-serveur traditionnelle. Le protocole de base fonctionne par requêtes et réponses, le Session Initiation Protocol agissant comme intermédiaire entre les terminaux connectés. Cela peut concerner presque n’importe quel appareil connecté à Internet. SIP reçoit alors les requêtes des clients ou des clients de l’agent utilisateur (UAC) et les réponses des serveurs ou des serveurs de l’agent utilisateur (UAS) et l’interface [Trunk SIP] met à disposition les numéros d’appel. Les autres protocoles mentionnés permettent toutefois l’échange de données proprement dit. Les serveurs proxy et autres passerelles font aussi partie des composants pour la communication avec le protocole SIP.

Pour établir la connexion, le Session Description Protocol détermine le type de connexion possible et règle ses modalités. Ces différentes méthodes portent aussi le nom de codec. Les adresses réseau qui doivent être utilisées sont également définies par le SDP. Une fois cette question réglée, un protocole tel que RTP assure la transmission des données proprement dites. Lorsque la session est terminée, le protocole SIP met fin à la connexion.

## Protocole SIP : quel système d’adressage ?
Pour un adressage correct, le protocole SIP utilise l’Uniform Resource Identifier (URI) ainsi que le Domain Name System (DNS). La structure des adresses ainsi attribuées à chaque participant ressemble à celle des adresses e-mail ordinaires. Comme pour une adresse électronique, une adresse SIP se compose de deux éléments : un nom d’utilisateur ou un numéro de téléphone au début et le réseau correspondant derrière. Les numéros de téléphone sont notamment très courants sur les appareils qui proposent une interface avec les réseaux téléphoniques.

## Quelles sont les différentes requêtes SIP ?
Le protocole SIP fonctionne avec différentes requêtes (ou Requests) auxquelles il réagit ensuite par des réponses (ou Responses). Ces réponses utilisent les codes de statut HTTP. Les requêtes des protocoles SIP sont divisées en requêtes SIP de base et requêtes SIP avancées. Les voici en détail :

### Requêtes SIP de base

ACK: confirme la réception d’une requête ou d’une réponse ;

BYE: met fin correctement une session active ;

SIP CANCEL: annule une requête en attente ;

INVITE:* envoie une demande à un serveur pour ouvrir une session ;

OPTIONS: indique aux terminaux les spécifications des autres périphériques impliqués ;

REGISTER: enregistre un appareil auprès du fournisseur de services.

### Requêtes SIP avancées

INFO: transmet des informations non directement liées à la session SIP ;

MESSAGE: transmet un message texte à un appareil ;

NOTIFY: vérifie l’état de la connexion et envoie des notifications en cas de changement ;

PRACK: confirme une requête de manière provisoire ;

REFER: transmet une connexion existante à une autre personne ;

SUBSCRIBE: envoie un message à l’occurrence d’un événement particulier ;

UPDATE: modifie le statut d’un appel.

## Quelles sont les différentes réponses SIP ?
Les réponses SIP permettent de répondre aux requêtes SIP listées ci-dessus. On les divise en six catégories :

1xx: indique que le serveur a bien reçu la requête et fournit aussi des informations provisoires sur l’état ;

2xx: indique l’aboutissement de la requête ;

3xx: informe des redirections possibles ou nécessaires ;

4xx: indique qu’une requête n’a pas pu être traitée ;

5xx: informe d’une défaillance côté serveur ;

6xx: indique que le serveur a pu être contacté, mais que la transaction n’a pas pu avoir lieu pour d’autres raisons.
