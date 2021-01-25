# Property&lt;T&gt;.Register&lt;TObject&gt; method

Registers this property descriptor and creates the correct GProperty into the GLib type of *TObject*.

```csharp
public static Property Register<TObject>(string name, string propertyName, 
    Func<TObject, T> get = null, Action<TObject, T> set = null)
    where TObject : Object
```

| parameter | description |
| --- | --- |
| TObject | The type of the object on which this property will be registered. |
| name | The name of the GProperty to create. |
| propertyName | The name of the C# property which serves as the proxy of this GProperty |
| get | The function called when retrieving the value of this property in bindings. |
| set | The function called when defining the value of this property in bindings. |

## Return Value

An instance of [`Property`](../Property-1.md) representing the GProperty description.

## See Also

* class [Object](../Object.md)
* class [Property&lt;T&gt;](../Property-1.md)
* namespace [GObject](../../GObject.md)

<!-- DO NOT EDIT: generated by xmldocmd for GObject.dll -->