## **Accès à distance en SSH**

1 - Taper les commandes suivantes :

```
line vty 0 4
 password <motdepasse>
 login local
 transport input ssh
exit
```

```
aaa authentication login default local
aaa authorization exec default local
```