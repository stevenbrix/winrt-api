---
-api-id: T:Windows.UI.Xaml.Hosting.DesignerAppManager
-api-type: winrt class
---

<!-- Class syntax.
public class DesignerAppManager : IClosable
-->

# Windows.UI.Xaml.Hosting.DesignerAppManager

## -description

Manages an application in a XAML design surface. Compared to the legacy designer surface which used the [XamlUIPresenter](https://docs.microsoft.com/en-us/uwp/api/Windows.UI.Xaml.Hosting.XamlUIPresenter), which was hosted in a Win32 process, the process launched by the DesignerAppManager is more similar to a regular UWP. The DesignerAppManager is responsible for managing the lifetime of the hosted designer process. The launched executable is required to have the NoUIEntryPoints-DesignModeV2 [DisplayName](https://docs.microsoft.com/en-us/uwp/schemas/appxpackage/uapmanifestschema/element-displayname) declared in the .appx file when registered. When the process is activated, it won't show up in the task bar or task switcher view.

## -remarks

## -see-also

## -examples

