
# <a name="context"></a>context

### <a name="officeofficemdcontext"></a>[Office](Office.md).context

Office.context 命名空间提供所有 Office 应用中的外接程序所使用的共享接口。此列表仅记录 Outlook 外接程序所使用的接口。有关 Office.context 命名空间的完整列表，请参阅[共享 API 中的 Office.context 引用](/javascript/api/office/office.context)。

##### <a name="requirements"></a>要求

|要求| 值|
|---|---|
|[最低版本的邮箱要求集](/javascript/office/requirement-sets/outlook-api-requirement-sets)| 1.0|
|[适用的 Outlook 模式](https://docs.microsoft.com/outlook/add-ins/#extension-points)| 撰写或阅读|

##### <a name="members-and-methods"></a>成员和方法

| 成员 | 类型 |
|--------|------|
| [displayLanguage](#displaylanguage-string) | 成员 |
| [officeTheme](#officetheme-object) | 成员 |
| [roamingSettings](#roamingsettings-roamingsettingsjavascriptapioutlook17officeroamingsettings) | 成员 |

### <a name="namespaces"></a>命名空间

[邮箱](office.context.mailbox.md)： Microsoft Outlook 和 Microsoft Outlook on the web 提供对 Outlook 加载项对象模型的访问。

### <a name="members"></a>成员

####  <a name="displaylanguage-string"></a>displayLanguage :String

获取用户针对 Office 主机应用程序的 UI 指定的 RFC 1766 语言标记格式的区域设置（语言）。

`displayLanguage` 值反映在 Office 主机应用程序中通过“**文件 > 选项 > 语言**”指定的当前“**显示语言**”设置。

##### <a name="type"></a>类型：

*   String

##### <a name="requirements"></a>要求

|要求| 值|
|---|---|
|[最低版本的邮箱要求集](/javascript/office/requirement-sets/outlook-api-requirement-sets)| 1.0|
|[适用的 Outlook 模式](https://docs.microsoft.com/outlook/add-ins/#extension-points)| 撰写或阅读|

##### <a name="example"></a>示例

```js
function sayHelloWithDisplayLanguage() {
  var myDisplayLanguage = Office.context.displayLanguage;
  switch (myDisplayLanguage) {
    case 'en-US':
      write('Hello!');
      break;
    case 'en-NZ':
      write('G\'day mate!');
      break;
  }
}
// Function that writes to a div with id='message' on the page.
function write(message){
  document.getElementById('message').innerText += message;
}
```

####  <a name="officetheme-object"></a>officeTheme :Object

提供了访问 Office 主题颜色的属性。

> [!NOTE]
> 此成员不支持适用于 iOS 的 Outlook 或 Outlook for Android。

通过使用 Office 主题颜色，你可以使外接程序的配色方案与用户（通过 **“文件”>“Office 帐户”>“Office 主题”UI**）选择的当前 Office 主题协调一致，这种做法适用于所有 Office 主机应用程序。使用 Office 主题颜色适用于邮件和任务窗格外接程序。

##### <a name="type"></a>类型：

*   对象

##### <a name="properties"></a>属性：

|名称| 类型| 说明|
|---|---|---|
|`bodyBackgroundColor`| String|获取十六进制三原色形式的 Office 主题正文背景色。|
|`bodyForegroundColor`| String|获取十六进制三原色形式的 Office 主题正文前景色。|
|`controlBackgroundColor`| 字符串|获取十六进制三原色形式的 Office 主题控制背景色。|
|`controlForegroundColor`| 字符串|获取十六进制三原色形式的 Office 主题正文控制颜色。|

##### <a name="requirements"></a>要求

|要求| 值|
|---|---|
|[最低版本的邮箱要求集](/javascript/office/requirement-sets/outlook-api-requirement-sets)| 1.3|
|[适用的 Outlook 模式](https://docs.microsoft.com/outlook/add-ins/#extension-points)| 撰写或阅读|

##### <a name="example"></a>示例

```js
function applyOfficeTheme(){
  // Get office theme colors.
  var bodyBackgroundColor = Office.context.officeTheme.bodyBackgroundColor;
  var bodyForegroundColor = Office.context.officeTheme.bodyForegroundColor;
  var controlBackgroundColor = Office.context.officeTheme.controlBackgroundColor
  var controlForegroundColor = Office.context.officeTheme.controlForegroundColor;

  // Apply body background color to a CSS class.
  $('.body').css('background-color', bodyBackgroundColor);
}
```

####  <a name="roamingsettings-roamingsettingsjavascriptapioutlook17officeroamingsettings"></a>roamingSettings :[RoamingSettings](/javascript/api/outlook_1_7/office.RoamingSettings)

获取一个对象，它表示保存到用户邮箱的邮件外接程序的自定义设置或状态。

`RoamingSettings` 对象允许您存储和访问用户邮箱中存储的邮件外接程序的数据，以便从用于访问该邮箱的任何主机客户端应用程序中运行该外接程序时，该外接程序可以使用该数据。

##### <a name="type"></a>类型:

*   [RoamingSettings](/javascript/api/outlook_1_7/office.RoamingSettings)

##### <a name="requirements"></a>要求

|要求| 值|
|---|---|
|[最低版本的邮箱要求集](/javascript/office/requirement-sets/outlook-api-requirement-sets)| 1.0|
|[最低权限级别](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| 受限|
|[适用的 Outlook 模式](https://docs.microsoft.com/outlook/add-ins/#extension-points)| 撰写或阅读|