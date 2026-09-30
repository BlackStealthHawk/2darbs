# Nosacījumu eksperiments

`Player.cs` nosacījuma Python versija:

```python
health = 100

if health <= 0:
    print("Spēle beigusies")
elif health < 30:
    print("Uzmanību!")
else:
    print("Viss kārtībā")
```

## Trīs sintakses atšķirības

1. C# izmanto `else if`, bet Python — `elif`.
2. C# koda blokus norobežo ar `{}`; Python blokus nosaka atkāpes.
3. C# mainīgo deklarē ar tipu, piemēram, `int health = 100;`; Python piešķir vērtību bez atsevišķas tipa deklarācijas: `health = 100`.

Šis ir tikai nosacījumu sintakses eksperiments. Dzīvību sistēma pamatspēlei nav vajadzīga, un šis piemērs to neievieš.
