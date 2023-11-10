## 1 Questions de compréhension

``1.`` Dans la définition du code d'une classe. Par exemple :
```java
class Student {
    String firstName;
    String lastName;
    String address;
    ...
}
```
 
``2.`` Non, il faut impérativement utiliser le nom des attributs.
 
``3.`` Non, elle dépend du nombre d'attributs.
 
``4.`` Oui, une classe **SchoolClass** peut contenir un tableau de **Student** par exemple :
```java
class SchoolClass {
    String name;
    Student[] students;
    ...
}
```
 
``5.`` Non *voir exemple ci-dessus*
 
``6.`` 
    ``a.`` L'avantage de cette approche est qu'il est plus simple à utiliser, à stocker et garantie que chaque point soit bien enregistré (que l'on ai bien (x, y, z) pour tous les points et non (z, x, y) ou des valeurs supperflux).
        L'inconvénéant est qu'on ne peut pas utiliser de boucles pour parcourir les valeurs. 
    
    ``b.`` On peut créer un tableau de Point, dans ce cas on peut itérer chacun de nos points, mais nous devrons tout de même appeler les attributs x, y ou z pour obtenir une coordonnée précise.
