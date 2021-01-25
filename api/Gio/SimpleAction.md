# SimpleAction class

```csharp
public class SimpleAction : Object, Action
```

## Public Members

| name | description |
| --- | --- |
| [Enabled](SimpleAction/Enabled.md) { get; set; } |  |
| [Item](SimpleAction/Item.md) { set; } | Indexer to connect ActivateSignal with a SignalHandler&lt;SimpleAction, ActivateSignalArgs&gt; (2 indexers) |
| [Name](SimpleAction/Name.md) { get; set; } |  |
| [ParameterType](SimpleAction/ParameterType.md) { get; set; } |  |
| [State](SimpleAction/State.md) { get; set; } |  |
| [StateType](SimpleAction/StateType.md) { get; set; } |  |
| event [OnActivate](SimpleAction/OnActivate.md) |  |
| event [OnChangeState](SimpleAction/OnChangeState.md) |  |
| static readonly [ActivateSignal](SimpleAction/ActivateSignal.md) | Signal Descriptor for OnActivate. |
| static readonly [ChangeStateSignal](SimpleAction/ChangeStateSignal.md) | Signal Descriptor for OnChangeState. |
| class [ActivateSignalArgs](SimpleAction.ActivateSignalArgs.md) | Signal (Event) Arguments for OnActivate |
| class [ChangeStateSignalArgs](SimpleAction.ChangeStateSignalArgs.md) | Signal (Event) Arguments for OnChangeState |

## See Also

* interface [Action](Action.md)
* namespace [Gio](../Gio.md)

<!-- DO NOT EDIT: generated by xmldocmd for Gio.dll -->