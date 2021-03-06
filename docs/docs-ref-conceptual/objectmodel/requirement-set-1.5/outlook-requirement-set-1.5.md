# <a name="outlook-add-in-api-requirement-set-15"></a>Outlook 外接程序 API 要求集 1.5

Outlook 加载项 API 子集的 JavaScript API for Office 包括对象、 方法、 属性和事件，您可以在 Outlook 中使用外接程序。

> [!NOTE]
> 本文档是[要求设置](/javascript/office/requirement-sets/outlook-api-requirement-sets)而不是最新的要求集。

## <a name="whats-new-in-15"></a>1.5 中的新增功能有哪些？

要求集 1.5 包括[要求集 1.4](../requirement-set-1.4/outlook-requirement-set-1.4.md) 的所有功能。它添加了下列功能。

- 添加了对[可固定任务窗格](https://docs.microsoft.com/outlook/add-ins/pinnable-taskpane)的支持。
- 添加了对 [REST API](https://docs.microsoft.com/outlook/add-ins/use-rest-api) 调用的支持。
- 添加了将附件标记为内联的功能。
- 添加了关闭任务窗格或对话框的功能。

### <a name="change-log"></a>更改日志

- 添加了 [Office.context.mailbox.addHandlerAsync](office.context.mailbox.md#addhandlerasynceventtype-handler-options-callback)：添加支持事件的事件处理程序。
- 添加[Office.EventType](office.md#eventtype-string)： 指定事件处理程序相关联的事件，并且包括 ItemChanged 事件的支持。
- 添加了 [Office.context.mailbox.restUrl](office.context.mailbox.md#resturl-string)：获取此电子邮件帐户的 REST 终结点的 URL。
- 修改了 [Office.context.mailbox.getCallbackTokenAsync](office.context.mailbox.md#getcallbacktokenasyncoptions-callback)：添加了此方法的新版本（具有新签名） (`getCallbackTokenAsync([options], callback)`)。原始版本仍可用且未更改。
- 添加了的[Office.context.ui.closeContainer](/javascript/api/office/office.ui#closecontainer--)。
- 修改了 [Office.context.mailbox.item.addFileAttachmentAsync](office.context.mailbox.item.md#addfileattachmentasyncuri-attachmentname-options-callback)：`options` 字典中的新值调用 `isInline`，用于指定在邮件正文中内联使用了一个图像。
- 修改了 [Office.context.mailbox.item.displayReplyAllForm](office.context.mailbox.item.md#displayreplyallformformdata)：`formData.attachments` 字典中的新值调用 `isInline`，用于指定在邮件正文中内联使用了一个图像。
- 修改了 [Office.context.mailbox.item.displayReplyForm](office.context.mailbox.item.md#displayreplyformformdata)：`formData.attachments` 字典中的新值调用 `isInline`，用于指定在邮件正文中内联使用了一个图像。

## <a name="see-also"></a>另请参阅

- [Outlook 外接程序](https://docs.microsoft.com/outlook/add-ins/)
- [Outlook 外接程序代码示例](https://developer.microsoft.com/outlook/gallery/?filterBy=Outlook,Samples,Add-ins)
- [入门](https://docs.microsoft.com/outlook/add-ins/quick-start)