# core-packages
 // Packages indispensables

Ne pas oublier de régénérer les sommes de controle dans les packages modifiés qui en possédent un. Ouvrez un terminal Dans le dossier du package et :

```
updpkgsums
```
Ensuite executez le script build.sh:
```
./build.sh
```

Une fois les paquets construits ils seront copiés dans le dépot de packages (dossier x86_64) si vous l'avez cloné.
