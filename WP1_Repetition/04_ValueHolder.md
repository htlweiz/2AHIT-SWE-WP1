# ValueHolder

## Aufgabenstellung

Erstellen Sie ein Programm und fügen Sie dem Programm eine Klasse __ValueHolder__ hinzu.

Erweitern Sie die Klasse um ein Member (Eine Eigenschaft) des Types Int32 mit dem Namen __value__.

Erweitern Sie die Klasse um die folgenden beiden (Getter/Setter) Methoden.

``` CSharp
public void setValue(Int32 value) { ... }
public Int32 getValue() { ... }
```

Erweitern Sie Ihr Programm um die Instanziierung zweier ValueHolder Objekte und deren Anwendung in folgender Form.

``` CSharp
ValueHolder value1 = new ValueHolder();
ValueHolder value2 = new ValueHolder();

value1.setValue(2);
value2.setValue(3);

Console.WriteLine("value1 is {0}", value1.getValue());
Console.WriteLine("value2 is {0}", value2.getValue());
```
