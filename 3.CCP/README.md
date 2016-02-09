# INF1076

## Configurer CCP en allumant le service HTTP

```
Router(config)# ip http server
Router(config)# ip http secure-server
Router(config)# ip http authentication local
Router(config)# username <username> privilege 15 password 0 <password>
Router(config)# line vty 0 4
Router(config-line)# privilege level 15
Router(config-line)# login local
Router(config-line)# transport input telnet
Router(config-line)# transport input telnet ssh
Router(config-line)# exit
```

## CCP (Cisco Configuration Professional) 2.5
- Installation de CCP sur Windows 7 et 10
- Configuration du Routeur
- Démo de CCP
- Profils Utilisateurs
- Création de modèles (templates)
- Autosecure et LockDown
