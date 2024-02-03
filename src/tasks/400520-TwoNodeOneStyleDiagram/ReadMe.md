
## 
1. Need to understand resources ResourceDictionary and MergedDictionaries.
   1. https://learn.microsoft.com/en-us/dotnet/desktop/wpf/systems/xaml-resources-merged-dictionaries
   2. https://learn.microsoft.com/en-us/dotnet/api/system.windows.resourcedictionary.mergeddictionaries


```xml
<Window.Resources>
    <ResourceDictionary>
        <ResourceDictionary.MergedDictionaries>
            <ResourceDictionary Source="/Syncfusion.SfDiagram.Wpf;component/Resources/BasicShapes.xaml" />
        </ResourceDictionary.MergedDictionaries>
    </ResourceDictionary>
</Window.Resources>
```

2. Reference: https://help.syncfusion.com/wpf/diagram/getting-started

3. So here we have two nodes added to the nodes collection. Then a single style ShapeStyleForBothNodes which is present as a static resource, is applied to both the nodes.

