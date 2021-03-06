# <a name="add-in-commands-requirement-sets"></a>加载项命令要求集

要求集是指各组已命名的 API 成员。 Office 加载项使用清单中指定要求集，或使用运行时检查以确定是否的 Office 主机支持外接程序需要的 Api。 有关详细信息，请参阅[Office 版本和要求集](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets)。

外接程序命令是 UI 元素，可扩展 Office UI，并在外接程序中启动操作。可以使用加载项命令在功能区上添加按钮，也可以向上下文菜单添加项。有关详细信息，请参阅 [Excel、Word 和 PowerPoint 的加载项命令](https://docs.microsoft.com/office/dev/add-ins/design/add-in-commands)和 [Outlook 的加载项命令](https://docs.microsoft.com/outlook/add-ins/add-in-commands-for-outlook)。

外接程序命令的初始版本没有相应的要求集（即，没有 AddinCommands 1.0 要求集）。下表列出了支持初始版本的 Office 主机应用程序，以及这些应用程序的内部版本或版本号。  

| 发布   |  Office 2013 for Windows | Office 2016 windows （非订阅） | 用于 Windows 的 office 365   |  Office 365 for iPad  |  Office 365 for Mac  | Office Online  |  
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
| 外接程序命令（初始版本，无要求集） | 不适用 | 16.0.4678.1000*在仅限 Outlook 中受支持* |版本 1603（内部版本 6769.0000）或更高版本 | 不适用 | 15.33 或更高版本| 2016 年 1 月 | |

外接程序命令 1.1 要求集介绍了[随文档自动打开任务窗格](https://docs.microsoft.com/office/dev/add-ins/develop/automatically-open-a-task-pane-with-a-document)的功能。

下表列出了外接程序命令 1.1 要求集、支持该要求集的 Office 主机应用程序，以及 Office 应用程序的内部版本或版本号。 

|  要求集  |  Office 2013 for Windows | Office 2016 windows （非订阅） | 用于 Windows 的 office 365   |  Office 365 for iPad  |  Office 365 for Mac  | Office Online  |  
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
| AddinCommands 1.1  | 不适用 | 16.0.4678.1000*在仅限 Outlook 中受支持*  | 版本 1705（内部版本 8121.1000）或更高版本 | 不适用 | 15.34 或更高版本| 2017 年 5 月 | |

若要详细了解版本、内部版本号和 Office Online Server，请参阅：

- [更新频道发布的 Office 365 客户端版本号和内部版本号](https://support.office.com/article/version-and-build-numbers-of-update-channel-releases-ae942449-1fca-4484-898b-a933ea23def7)
- [使用的是哪一版 Office？](https://support.office.com/article/What-version-of-Office-am-I-using-932788b8-a3ce-44bf-bb09-e334518b8b19)
- [在哪里可以找到 Office 365 客户端应用程序的版本号和内部版本号](https://support.office.com/article/version-and-build-numbers-of-update-channel-releases-ae942449-1fca-4484-898b-a933ea23def7)
- 
  [Office Online Server 概述](https://docs.microsoft.com/officeonlineserver/office-online-server-overview)

## <a name="office-common-api-requirement-sets"></a>Office 通用 API 要求集

有关公用 API 要求集的信息，请参阅 [Office 公用 API 要求集](office-add-in-requirement-sets.md)。

## <a name="see-also"></a>另请参阅

- [Office 版本和要求集](https://docs.microsoft.com/office/dev/add-ins/develop/office-versions-and-requirement-sets)
- [指定 Office 主机和 API 要求](https://docs.microsoft.com/office/dev/add-ins/develop/specify-office-hosts-and-api-requirements)
- [Office 外接程序 XML 清单](https://docs.microsoft.com/office/dev/add-ins/develop/add-in-manifests)
