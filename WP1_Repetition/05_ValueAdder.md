# ValueAdder

## Aufgabenstellung

Erstellen Sie ein Programm und fügen Sie dem Programm eine Klasse __ValueAdder__ hinzu.

Erweitern Sie die Klasse um zwei Member des Types Int32 mit den Namen __valueA__ und __valueB__.

Erweitern Sie die Klasse um die folgenden (Getter/Setter) Methoden.

``` CSharp
public void setValueA(Int32 value) { ... }
public Int32 getValueA() { ... }
public void setValueB(Int32 value) { ... }
public Int32 getValueB() { ... }
```

Erweitern Sie die Klasse um eine Methode __calculateSum__ welche das Ergebnis der Addition retourniert.

``` CSharp
public Int32 calculateSum() { ... }
```

Erweitern Sie Ihr Programm um die Instanziierung zweier ValueAdder Objekte und deren Anwendung in folgender Form.

``` CSharp
ValueAdder value1 = new ValueAdder();
ValueAdder value2 = new ValueAdder();

value1.setValueA(2);
value1.setValueB(3);
value2.setValueA(4);
value2.setValueB(5);

Console.WriteLine("Sum of {0}+{1} is {2}", value1.getValueA(), value1.getValueB(), value1.calculateSum());
Console.WriteLine("Sum of {0}+{1} is {2}", value2.getValueA(), value2.getValueB(), value2.calculateSum());
```
