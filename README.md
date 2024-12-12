# -How-to-customize-the-Indicator-Stroke-Thickness-in-.NET-MAUI-TabView
This repository contains a sample explaining how to Customize the Indicator Stroke Thickness in .NET MAUI TabView.

### IndicatorStrokeThickness support in .NET MAUI TabView

The `IndicatorStrokeThickness` property allows you to customize the thickness of the indicator stroke in the TabView control

The following code example illustrate how to Customize IndicatorStrokeThickness in SfTabView.

### XAML

```
    <tabView:SfTabView IndicatorStrokeThickness ="7">
    </tabView:SfTabView> 
```

### C#

```
    var tabView = new SfTabView();
    tabView.IndicatorStrokeThickness  = 7; 
```
