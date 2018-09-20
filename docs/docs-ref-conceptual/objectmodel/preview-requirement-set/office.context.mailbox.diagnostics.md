
# <a name="diagnostics"></a><span data-ttu-id="bbd32-101">diagnostics</span><span class="sxs-lookup"><span data-stu-id="bbd32-101">diagnostics</span></span>

### <span data-ttu-id="bbd32-p101">[Office](Office.md)[.context](Office.context.md)[.mailbox](Office.context.mailbox.md). diagnostics</span><span class="sxs-lookup"><span data-stu-id="bbd32-p101">[Office](Office.md)[.context](Office.context.md)[.mailbox](Office.context.mailbox.md). diagnostics</span></span>

<span data-ttu-id="bbd32-104">将诊断信息提供给 Outlook 外接程序。</span><span class="sxs-lookup"><span data-stu-id="bbd32-104">Provides diagnostic information to an Outlook add-in.</span></span>

##### <a name="requirements"></a><span data-ttu-id="bbd32-105">要求</span><span class="sxs-lookup"><span data-stu-id="bbd32-105">Requirements</span></span>

|<span data-ttu-id="bbd32-106">要求</span><span class="sxs-lookup"><span data-stu-id="bbd32-106">Requirement</span></span>| <span data-ttu-id="bbd32-107">值</span><span class="sxs-lookup"><span data-stu-id="bbd32-107">Value</span></span>|
|---|---|
|[<span data-ttu-id="bbd32-108">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="bbd32-108">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="bbd32-109">1.0</span><span class="sxs-lookup"><span data-stu-id="bbd32-109">1.0</span></span>|
|[<span data-ttu-id="bbd32-110">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="bbd32-110">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="bbd32-111">ReadItem</span><span class="sxs-lookup"><span data-stu-id="bbd32-111">ReadItem</span></span>|
|[<span data-ttu-id="bbd32-112">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="bbd32-112">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="bbd32-113">Compose 或 Read</span><span class="sxs-lookup"><span data-stu-id="bbd32-113">Compose or read</span></span>|

##### <a name="members-and-methods"></a><span data-ttu-id="bbd32-114">成员和方法</span><span class="sxs-lookup"><span data-stu-id="bbd32-114">Members and methods</span></span>

| <span data-ttu-id="bbd32-115">成员</span><span class="sxs-lookup"><span data-stu-id="bbd32-115">Member</span></span> | <span data-ttu-id="bbd32-116">类型</span><span class="sxs-lookup"><span data-stu-id="bbd32-116">Type</span></span> |
|--------|------|
| [<span data-ttu-id="bbd32-117">hostName</span><span class="sxs-lookup"><span data-stu-id="bbd32-117">hostName</span></span>](#hostname-string) | <span data-ttu-id="bbd32-118">成员</span><span class="sxs-lookup"><span data-stu-id="bbd32-118">Member</span></span> |
| [<span data-ttu-id="bbd32-119">hostVersion</span><span class="sxs-lookup"><span data-stu-id="bbd32-119">hostVersion</span></span>](#hostversion-string) | <span data-ttu-id="bbd32-120">成员</span><span class="sxs-lookup"><span data-stu-id="bbd32-120">Member</span></span> |
| [<span data-ttu-id="bbd32-121">OWAView</span><span class="sxs-lookup"><span data-stu-id="bbd32-121">OWAView</span></span>](#owaview-string) | <span data-ttu-id="bbd32-122">成员</span><span class="sxs-lookup"><span data-stu-id="bbd32-122">Member</span></span> |

### <a name="members"></a><span data-ttu-id="bbd32-123">成员</span><span class="sxs-lookup"><span data-stu-id="bbd32-123">Members</span></span>

####  <a name="hostname-string"></a><span data-ttu-id="bbd32-124">hostName :String</span><span class="sxs-lookup"><span data-stu-id="bbd32-124">hostName :String</span></span>

<span data-ttu-id="bbd32-125">获取表示主机应用程序的名称的字符串。</span><span class="sxs-lookup"><span data-stu-id="bbd32-125">Gets a string that represents the name of the host application.</span></span>

<span data-ttu-id="bbd32-126">可以是下列值之一的字符串：`Outlook`、`Mac Outlook`、`OutlookIOS` 或 `OutlookWebApp`。</span><span class="sxs-lookup"><span data-stu-id="bbd32-126">A string that can be one of the following values: `Outlook`, `Mac Outlook`, `OutlookIOS`, or `OutlookWebApp`.</span></span>

##### <a name="type"></a><span data-ttu-id="bbd32-127">类型:</span><span class="sxs-lookup"><span data-stu-id="bbd32-127">Type:</span></span>

*   <span data-ttu-id="bbd32-128">String</span><span class="sxs-lookup"><span data-stu-id="bbd32-128">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="bbd32-129">要求</span><span class="sxs-lookup"><span data-stu-id="bbd32-129">Requirements</span></span>

|<span data-ttu-id="bbd32-130">要求</span><span class="sxs-lookup"><span data-stu-id="bbd32-130">Requirement</span></span>| <span data-ttu-id="bbd32-131">值</span><span class="sxs-lookup"><span data-stu-id="bbd32-131">Value</span></span>|
|---|---|
|[<span data-ttu-id="bbd32-132">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="bbd32-132">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="bbd32-133">1.0</span><span class="sxs-lookup"><span data-stu-id="bbd32-133">1.0</span></span>|
|[<span data-ttu-id="bbd32-134">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="bbd32-134">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="bbd32-135">ReadItem</span><span class="sxs-lookup"><span data-stu-id="bbd32-135">ReadItem</span></span>|
|[<span data-ttu-id="bbd32-136">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="bbd32-136">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="bbd32-137">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="bbd32-137">Compose or read</span></span>|

####  <a name="hostversion-string"></a><span data-ttu-id="bbd32-138">hostVersion :String</span><span class="sxs-lookup"><span data-stu-id="bbd32-138">hostVersion :String</span></span>

<span data-ttu-id="bbd32-139">获取表示主机应用程序或 Exchange Server 的版本的字符串。</span><span class="sxs-lookup"><span data-stu-id="bbd32-139">Gets a string that represents the version of either the host application or the Exchange Server.</span></span>

<span data-ttu-id="bbd32-p102">如果邮件外接程序正在 Outlook 桌面客户端或 Outlook for iOS 上运行，则 `hostVersion` 属性返回主机应用程序版本 Outlook。在 Outlook Web App 中，属性返回 Exchange Server 的版本。其中的一个示例是字符串 `15.0.468.0`。</span><span class="sxs-lookup"><span data-stu-id="bbd32-p102">If the mail add-in is running on the Outlook desktop client or Outlook for iOS, the `hostVersion` property returns the version of the host application, Outlook. In Outlook Web App, the property returns the version of the Exchange Server. An example is the string `15.0.468.0`.</span></span>

##### <a name="type"></a><span data-ttu-id="bbd32-143">类型:</span><span class="sxs-lookup"><span data-stu-id="bbd32-143">Type:</span></span>

*   <span data-ttu-id="bbd32-144">String</span><span class="sxs-lookup"><span data-stu-id="bbd32-144">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="bbd32-145">要求</span><span class="sxs-lookup"><span data-stu-id="bbd32-145">Requirements</span></span>

|<span data-ttu-id="bbd32-146">要求</span><span class="sxs-lookup"><span data-stu-id="bbd32-146">Requirement</span></span>| <span data-ttu-id="bbd32-147">值</span><span class="sxs-lookup"><span data-stu-id="bbd32-147">Value</span></span>|
|---|---|
|[<span data-ttu-id="bbd32-148">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="bbd32-148">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="bbd32-149">1.0</span><span class="sxs-lookup"><span data-stu-id="bbd32-149">1.0</span></span>|
|[<span data-ttu-id="bbd32-150">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="bbd32-150">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="bbd32-151">ReadItem</span><span class="sxs-lookup"><span data-stu-id="bbd32-151">ReadItem</span></span>|
|[<span data-ttu-id="bbd32-152">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="bbd32-152">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="bbd32-153">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="bbd32-153">Compose or read</span></span>|

####  <a name="owaview-string"></a><span data-ttu-id="bbd32-154">OWAView :String</span><span class="sxs-lookup"><span data-stu-id="bbd32-154">OWAView :String</span></span>

<span data-ttu-id="bbd32-155">获取表示 Outlook Web App 的当前视图的字符串。</span><span class="sxs-lookup"><span data-stu-id="bbd32-155">Gets a string that represents the current view of Outlook Web App.</span></span>

<span data-ttu-id="bbd32-156">返回的字符串可以是下列值之一：`OneColumn`、`TwoColumns` 或 `ThreeColumns`。</span><span class="sxs-lookup"><span data-stu-id="bbd32-156">The returned string can be one of the following values: `OneColumn`, `TwoColumns`, or `ThreeColumns`.</span></span>

<span data-ttu-id="bbd32-157">如果主机应用程序不是 Outlook Web App，则访问此属性将导致返回 `undefined`。</span><span class="sxs-lookup"><span data-stu-id="bbd32-157">If the host application is not Outlook Web App, then accessing this property results in `undefined`.</span></span>

<span data-ttu-id="bbd32-158">Outlook Web App 具有三种视图，这些视图分别与屏幕和窗口的宽度以及可以显示的列数相对应：</span><span class="sxs-lookup"><span data-stu-id="bbd32-158">Outlook Web App has three views that correspond to the width of the screen and the window, and the number of columns that can be displayed:</span></span>

*   <span data-ttu-id="bbd32-p103">`OneColumn` 在屏幕较窄时显示。Outlook Web App 在智能手机的整个屏幕上使用此单列布局。</span><span class="sxs-lookup"><span data-stu-id="bbd32-p103">`OneColumn`, which is displayed when the screen is narrow. Outlook Web App uses this single-column layout on the entire screen of a smartphone.</span></span>
*   <span data-ttu-id="bbd32-p104">`TwoColumns` 在屏幕较宽时显示。Outlook Web App 在大多数平板电脑上使用此视图。</span><span class="sxs-lookup"><span data-stu-id="bbd32-p104">`TwoColumns`, which is displayed when the screen is wider. Outlook Web App uses this view on most tablets.</span></span>
*   <span data-ttu-id="bbd32-p105">`ThreeColumns` 在屏幕为宽屏时显示。例如，Outlook Web App 在台式机的全屏窗口中使用此视图。</span><span class="sxs-lookup"><span data-stu-id="bbd32-p105">`ThreeColumns`, which is displayed when the screen is wide. For example, Outlook Web App uses this view in a full screen window on a desktop computer.</span></span>

##### <a name="type"></a><span data-ttu-id="bbd32-165">类型：</span><span class="sxs-lookup"><span data-stu-id="bbd32-165">Type:</span></span>

*   <span data-ttu-id="bbd32-166">String</span><span class="sxs-lookup"><span data-stu-id="bbd32-166">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="bbd32-167">要求</span><span class="sxs-lookup"><span data-stu-id="bbd32-167">Requirements</span></span>

|<span data-ttu-id="bbd32-168">要求</span><span class="sxs-lookup"><span data-stu-id="bbd32-168">Requirement</span></span>| <span data-ttu-id="bbd32-169">值</span><span class="sxs-lookup"><span data-stu-id="bbd32-169">Value</span></span>|
|---|---|
|[<span data-ttu-id="bbd32-170">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="bbd32-170">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="bbd32-171">1.0</span><span class="sxs-lookup"><span data-stu-id="bbd32-171">1.0</span></span>|
|[<span data-ttu-id="bbd32-172">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="bbd32-172">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="bbd32-173">ReadItem</span><span class="sxs-lookup"><span data-stu-id="bbd32-173">ReadItem</span></span>|
|[<span data-ttu-id="bbd32-174">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="bbd32-174">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="bbd32-175">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="bbd32-175">Compose or read</span></span>|