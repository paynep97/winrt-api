---
-api-id: T:Windows.UI.WebUI.WebUIBackgroundTaskInstanceRuntimeClass
-api-type: winrt class
---

<!-- Class syntax.
public class WebUIBackgroundTaskInstanceRuntimeClass : Windows.ApplicationModel.Background.IBackgroundTaskInstance, Windows.UI.WebUI.IWebUIBackgroundTaskInstance
-->

# Windows.UI.WebUI.WebUIBackgroundTaskInstanceRuntimeClass

## -description
Provides access to an instance of a background task.

> [!NOTE]
> A background task must explicitly call the Web Workers [close](http://msdn.microsoft.com/en-us/library/hh673568(v=VS.85).aspx) method to terminate itself after the task has completed.

## -remarks
To retrieve this object, use the [WebUIBackgroundTaskInstance.current](webuibackgroundtaskinstance_current.md) property.



> [!NOTE]
> : This class is not agile, which means that you need to consider its threading model and marshaling behavior. For more info, see [Threading and Marshaling (C++/CX)](http://msdn.microsoft.com/en-us/library/windows/apps/hh771042.aspx)
<!--[jjacks - removed this link (https://go.microsoft.com/fwlink/p/?linkid=258277 404->http://msdn.microsoft.com/library/windows/apps/jj157115.aspx) because it doesn't work] and Using Windows Runtime objects in a multithreaded environment (.NET)-->
.

## -examples

## -see-also
