# AGS Jason

Projekt do AGS v Jasonu

Kompilace aStar.java:
```
javac -classpath <path to jason.jar>:. aStar/aStar.java -Xlint:unchecked
javac -classpath ../../../Jason-1.4.2/Jason-1.4.2/lib/jason.jar:. aStar/aStar.java -Xlint:unchecked
```

`-Xlint:unchecked` ignoruje některé warningy (`List` vs `ArrayList`)

## Zadání projektu
https://wis.fit.vutbr.cz/FIT/st/cwk.php?title=AGS:Pokyny_2017&csid=629343&id=11316


## Ideál 

### Slow (bystrozraký)

* pouze prochází celou mapu (systematicky)
* posílá broadcast zprávy o pozicích zlata, dřeva, překážek

### Middle (široký)

* komunikuje s Fast a sbírá suroviny

### Fast (dlouhý)

* komunikuje s Middle a sbírá suroviny