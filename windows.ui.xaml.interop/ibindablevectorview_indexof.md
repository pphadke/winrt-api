---
-api-id: M:Windows.UI.Xaml.Interop.IBindableVectorView.IndexOf(System.Object,System.UInt32@)
-api-type: winrt method
---

<!-- Method syntax
public bool IndexOf(System.Object value, System.UInt32 index)
-->

# Windows.UI.Xaml.Interop.IBindableVectorView.IndexOf

## -description
Returns the index of a specified item in the vector.

## -parameters
### -param value
The item to find in the vector.

### -param index
The zero-based index of the item if found. 0 is returned if the item is not found, so be sure to check the return value.

## -returns
**true** if the item is found; **false** if the item is not found.

## -remarks
This interface supports the creation of data bindable collections in C++. When programming with .NET, you should use [ObservableCollection(Of T)](XREF:TODO:T:System.Collections.ObjectModel.ObservableCollection`1) or implement [IList](https://msdn.microsoft.com/library/system.collections.ilist.aspx) and [INotifyCollectionChanged](https://msdn.microsoft.com/library/system.collections.specialized.inotifycollectionchanged.aspx).

## -examples

## -see-also
[XAML data binding sample](http://go.microsoft.com/fwlink/p/?linkid=226854)