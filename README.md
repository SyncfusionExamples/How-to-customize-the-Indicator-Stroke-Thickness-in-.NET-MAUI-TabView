# -How-to-customize-the-Indicator-Stroke-Thickness-in-.NET-MAUI-TabView
This repository contains a sample explaining how to Customize the Indicator Stroke Thickness in .NET MAUI TabView.

### IndicatorStrokeThickness support in .NET MAUI TabView

The `IndicatorStrokeThickness` property allows you to customize the thickness of the indicator stroke in the TabView control.

The following code example illustrate how to Customize IndicatorStrokeThickness in SfTabView.

### XAML

```
    <Grid VerticalOptions="FillAndExpand">
    <tabView:SfTabView IndicatorStrokeThickness="7" x:Name="tabview">
        <tabView:SfTabItem Header="Dashboard" FontSize="18">
            <StackLayout Padding="15">
                <Label Text="View your dashboard insights!" 
                   FontSize="16" 
                   HorizontalOptions="Center" />
            </StackLayout>
        </tabView:SfTabItem>

        <tabView:SfTabItem Header="Notifications" FontSize="18">
            <StackLayout Padding="15">
                <Label Text="Check your recent notifications." 
                   FontSize="16" 
                   HorizontalOptions="Center" />
            </StackLayout>
        </tabView:SfTabItem>
    </tabView:SfTabView>
    <Grid>
```

### C#

```
    var tabView = new SfTabView();
    tabView.IndicatorStrokeThickness  = 7; 
```
