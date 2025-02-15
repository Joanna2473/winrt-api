---
-api-id: T:Windows.UI.Xaml.Controls.RefreshVisualizer
-api-type: winrt class
---

<!-- Class syntax.
public class RefreshVisualizer : Control, Control
-->

# Windows.UI.Xaml.Controls.RefreshVisualizer

## -description

Represents a control that provides animated state indicators for content refresh.

Equivalent **WinUI 2 API for UWP**: [Microsoft.UI.Xaml.Controls.RefreshVisualizer](/windows/winui/api/microsoft.ui.xaml.controls.refreshvisualizer) (for WinUI in the [Windows App SDK](/windows/apps/windows-app-sdk/), see the **[Windows App SDK namespaces](/windows/windows-app-sdk/api/winrt/)**).

## -remarks

### Control style and template

You can modify the default [Style](../windows.ui.xaml/style.md) and [ControlTemplate](controltemplate.md) to give the control a unique appearance. For information about modifying a control's style and template, see [XAML styles](/windows/apps/design/style/xaml-styles). XAML also includes resources that you can use to modify the colors of a control in different visual states without modifying the control template. Modifying these resources is preferred to setting properties such as [Background](control_background.md) and [Foreground](control_foreground.md). For more info, see the [Light-weight styling](/windows/apps/design/style/xaml-styles#lightweight-styling) section of the [XAML styles](/windows/apps/design/style/xaml-styles) article.

**WinUI Styles (recommended):** Use [Microsoft.UI.Xaml.Controls.RefreshVisualizer](/windows/winui/api/microsoft.ui.xaml.controls.refreshvisualizer).

**Non-WinUI styles:** When you use the built-in styles, the default style, template, and resources that define the look of the control are included in the generic.xaml file. For design purposes, generic.xaml is available in the \(Program Files)\Windows Kits\10\DesignTime\CommonConfiguration\Neutral\UAP\ &lt;SDK version&gt;\Generic folder from a Windows SDK installation. Light-weight styling resources are available starting in Windows 10, version 1607 (SDK 14393). Styles and resources from different versions of the SDK might have different values.

## -see-also

[Pull to refresh overview](/windows/uwp/design/controls-and-patterns/pull-to-refresh)

## -examples

> [!TIP]
> For more info, design guidance, and code examples, see [Pull to refresh](/windows/uwp/design/controls-and-patterns/pull-to-refresh).
>
> If you have the **WinUI 2 Gallery** app installed, click here to [open the app and see pull-to-refresh in action](winui2gallery:/item/PullToRefresh).
> + [Get the WinUI 2 Gallery app (Microsoft Store)](https://www.microsoft.com/store/productId/9MSVH128X2ZT)
> + [Get the source code (GitHub)](https://github.com/Microsoft/WinUI-Gallery)
