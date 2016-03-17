## Présentation de Syslog

Les périphériques réseau disposent de mécanismes fiables permettant d'envoyer à l'administrateur des messages système détaillés lors de l'occurrence de certains événements se produisant sur le réseau. Ces messages peuvent être non critiques ou significatifs. Les administrateurs réseau disposent de diverses options permettant de stocker, d'interpréter et d'afficher ces messages, ainsi que pour être alertés des messages susceptibles d'avoir le plus d'impact sur l'infrastructure réseau.

La méthode d'accès aux messages système la plus couramment utilisée et fournie par les périphériques réseau est un protocole appelé Syslog.

De nombreux périphériques réseau prennent en charge le protocole Syslog, comme les routeurs, les commutateurs, les serveurs d'applications, les pare-feu et d'autres dispositifs réseau. Le protocole Syslog permet aux périphériques réseau d'envoyer leurs messages système sur le réseau aux serveurs Syslog.

Le service de journalisation du protocole Syslog assume trois fonctions principales :

. La capacité à collecter les informations de journalisation pour la surveillance et le dépannage
. La capacité à sélectionner le type d'information de journalisation capturé 
. La capacité à spécifier les destinations des messages Syslog capturés

### Observation: 
packet tracer ne permet pas de personnaliser le niveau de controle afin de limiter les message a un niveau souhaité , je vais essayer de faire le meme lab sur gns3 qui permet cela.

Ne pas omettre de :


Cmde a retenir : 

```
Router> show clock
```

```
Router> show ntp status
```
fait par: Samir SM
