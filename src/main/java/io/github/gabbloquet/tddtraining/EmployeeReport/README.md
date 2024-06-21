# Employee Report

## Problème

Vous construisez un système de gestion des employés d'une épicerie locale.   
Le propriétaire du magasin souhaite ouvrir le magasin le dimanche et, en raison de restrictions légales, les employés de moins de 18 ans ne sont pas autorisés à travailler le dimanche.  
L'employée demande une fonctionnalité d'établissement de rapports afin de pouvoir planifier les horaires de travail. 

_Tous les employés sont déjà stockés quelque part et ont les propriétés suivantes :_  
**Name** : chaîne de caractères (le nom de l'employé)  
**Âge** : nombre (l'âge en années de l'employé)


```javascript
const employees = [
  { name: 'Max', age: 17 },
  { name: 'Sepp', age: 18 },
  { name: 'Nina', age: 15 },
  { name: 'Mike', age: 51 },
];
```

## Les règles :

1. En tant que propriétaire d'un magasin, je souhaite afficher la liste de tous les employés âgés de plus de 18 ans, afin de savoir qui est autorisé à travailler le dimanche.
2. En tant que propriétaire de magasin, je veux que la liste des employés soit triée par leur nom, afin de pouvoir les retrouver plus facilement.
3. En tant que propriétaire du magasin, je souhaite que la liste des employés soit écrite en majuscules, afin que je puisse la lire plus facilement.