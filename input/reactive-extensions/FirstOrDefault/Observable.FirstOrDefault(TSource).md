title: Observable.FirstOrDefault<TSource>(IObservable<TSource>, Func<TSource, Boolean>)
---
# Observable.FirstOrDefault\<TSource\> Method (IObservable\<TSource\>, Func\<TSource, Boolean\>)

Returns the first element of an observable sequence that matches the predicate, or a default value if no value is found.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FirstOrDefault(Of TSource) ( _
    source As IObservable(Of TSource), _
    predicate As Func(Of TSource, Boolean) _
) As TSource
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim predicate As Func(Of TSource, Boolean)
Dim returnValue As TSource

returnValue = source.FirstOrDefault(predicate)
```

```csharp
public static TSource FirstOrDefault<TSource>(
    this IObservable<TSource> source,
    Func<TSource, bool> predicate
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static TSource FirstOrDefault(
    IObservable<TSource>^ source, 
    Func<TSource, bool>^ predicate
)
```

```fsharp
static member FirstOrDefault : 
        source:IObservable<'TSource> * 
        predicate:Func<'TSource, bool> -> 'TSource 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source observable sequence.

- predicate  
  Type: [System.Func](https://msdn.microsoft.com/en-us/library/Bb549151)\<TSource, [Boolean](https://msdn.microsoft.com/en-us/library/a28wyd50)\>  
  A predicate function to evaluate for elements in the sequence.

#### Return Value

Type: TSource  
The first element in the observable sequence for which the predicate holds, or a default value if no value is found.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[FirstOrDefault Overload](FirstOrDefault/Observable.FirstOrDefault)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)









# Observable.FirstOrDefault\<TSource\> Method (IObservable\<TSource\>)

Returns the first element of an observable sequence, or a default value if no value is found.

**Namespace:**  [System.Reactive.Linq](System.Reactive.Linq/System.Reactive.Linq)  
**Assembly:**  System.Reactive (in System.Reactive.dll)

## Syntax

```vb
'Declaration
<ExtensionAttribute> _
Public Shared Function FirstOrDefault(Of TSource) ( _
    source As IObservable(Of TSource) _
) As TSource
```

```vb
'Usage
Dim source As IObservable(Of TSource)
Dim returnValue As TSource

returnValue = source.FirstOrDefault()
```

```csharp
public static TSource FirstOrDefault<TSource>(
    this IObservable<TSource> source
)
```

```c++
[ExtensionAttribute]
public:
generic<typename TSource>
static TSource FirstOrDefault(
    IObservable<TSource>^ source
)
```

```fsharp
static member FirstOrDefault : 
        source:IObservable<'TSource> -> 'TSource 
```

```javascript
JScript does not support generic types and methods.
```

#### Type Parameters

- TSource  
  The type of source.

#### Parameters

- source  
  Type: [System.IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>  
  The source observable sequence.

#### Return Value

Type: TSource  
The first element in the observable sequence, or a default value if no value is found.

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [IObservable](https://msdn.microsoft.com/en-us/library/Dd990377)\<TSource\>. When you use instance method syntax to call this method, omit the first parameter. For more information, see [](https://msdn.microsoft.com/en-us/library/Bb384936) or [](https://msdn.microsoft.com/en-us/library/Bb383977).

## See Also

#### Reference

[Observable Class](Observable/Observable)

[FirstOrDefault Overload](FirstOrDefault/Observable.FirstOrDefault)

[System.Reactive.Linq Namespace](System.Reactive.Linq/System.Reactive.Linq)








