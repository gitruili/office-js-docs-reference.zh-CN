
# <a name="mailbox"></a><span data-ttu-id="280d2-101">mailbox</span><span class="sxs-lookup"><span data-stu-id="280d2-101">mailbox</span></span>

### <span data-ttu-id="280d2-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span><span class="sxs-lookup"><span data-stu-id="280d2-p101">[Office](Office.md)[.context](Office.context.md). mailbox</span></span>

<span data-ttu-id="280d2-104">Microsoft Outlook 和 Microsoft Outlook on the web 提供对 Outlook 加载项对象模型的访问。</span><span class="sxs-lookup"><span data-stu-id="280d2-104">Provides access to the Outlook add-in object model for Microsoft Outlook and Microsoft Outlook on the web.</span></span>

##### <a name="requirements"></a><span data-ttu-id="280d2-105">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-105">Requirements</span></span>

|<span data-ttu-id="280d2-106">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-106">Requirement</span></span>| <span data-ttu-id="280d2-107">值</span><span class="sxs-lookup"><span data-stu-id="280d2-107">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-108">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-108">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-109">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-109">1.0</span></span>|
|[<span data-ttu-id="280d2-110">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-110">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-111">受限</span><span class="sxs-lookup"><span data-stu-id="280d2-111">Restricted</span></span>|
|[<span data-ttu-id="280d2-112">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-112">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-113">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-113">Compose or read</span></span>|

##### <a name="members-and-methods"></a><span data-ttu-id="280d2-114">成员和方法</span><span class="sxs-lookup"><span data-stu-id="280d2-114">Members and methods</span></span>

| <span data-ttu-id="280d2-115">成员</span><span class="sxs-lookup"><span data-stu-id="280d2-115">Member</span></span> | <span data-ttu-id="280d2-116">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-116">Type</span></span> |
|--------|------|
| [<span data-ttu-id="280d2-117">ewsUrl</span><span class="sxs-lookup"><span data-stu-id="280d2-117">ewsUrl</span></span>](#ewsurl-string) | <span data-ttu-id="280d2-118">成员</span><span class="sxs-lookup"><span data-stu-id="280d2-118">Member</span></span> |
| [<span data-ttu-id="280d2-119">restUrl</span><span class="sxs-lookup"><span data-stu-id="280d2-119">restUrl</span></span>](#resturl-string) | <span data-ttu-id="280d2-120">成员</span><span class="sxs-lookup"><span data-stu-id="280d2-120">Member</span></span> |
| [<span data-ttu-id="280d2-121">addHandlerAsync</span><span class="sxs-lookup"><span data-stu-id="280d2-121">addHandlerAsync</span></span>](#addhandlerasynceventtype-handler-options-callback) | <span data-ttu-id="280d2-122">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-122">Method</span></span> |
| [<span data-ttu-id="280d2-123">convertToEwsId</span><span class="sxs-lookup"><span data-stu-id="280d2-123">convertToEwsId</span></span>](#converttoewsiditemid-restversion--string) | <span data-ttu-id="280d2-124">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-124">Method</span></span> |
| [<span data-ttu-id="280d2-125">convertToLocalClientTime</span><span class="sxs-lookup"><span data-stu-id="280d2-125">convertToLocalClientTime</span></span>](#converttolocalclienttimetimevalue--localclienttimejavascriptapioutlookofficelocalclienttime) | <span data-ttu-id="280d2-126">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-126">Method</span></span> |
| [<span data-ttu-id="280d2-127">convertToRestId</span><span class="sxs-lookup"><span data-stu-id="280d2-127">convertToRestId</span></span>](#converttorestiditemid-restversion--string) | <span data-ttu-id="280d2-128">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-128">Method</span></span> |
| [<span data-ttu-id="280d2-129">convertToUtcClientTime</span><span class="sxs-lookup"><span data-stu-id="280d2-129">convertToUtcClientTime</span></span>](#converttoutcclienttimeinput--date) | <span data-ttu-id="280d2-130">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-130">Method</span></span> |
| [<span data-ttu-id="280d2-131">displayAppointmentForm</span><span class="sxs-lookup"><span data-stu-id="280d2-131">displayAppointmentForm</span></span>](#displayappointmentformitemid) | <span data-ttu-id="280d2-132">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-132">Method</span></span> |
| [<span data-ttu-id="280d2-133">displayMessageForm</span><span class="sxs-lookup"><span data-stu-id="280d2-133">displayMessageForm</span></span>](#displaymessageformitemid) | <span data-ttu-id="280d2-134">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-134">Method</span></span> |
| [<span data-ttu-id="280d2-135">displayNewAppointmentForm</span><span class="sxs-lookup"><span data-stu-id="280d2-135">displayNewAppointmentForm</span></span>](#displaynewappointmentformparameters) | <span data-ttu-id="280d2-136">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-136">Method</span></span> |
| [<span data-ttu-id="280d2-137">displayNewMessageForm</span><span class="sxs-lookup"><span data-stu-id="280d2-137">displayNewMessageForm</span></span>](#displaynewmessageformparameters) | <span data-ttu-id="280d2-138">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-138">Method</span></span> |
| [<span data-ttu-id="280d2-139">getCallbackTokenAsync</span><span class="sxs-lookup"><span data-stu-id="280d2-139">getCallbackTokenAsync</span></span>](#getcallbacktokenasyncoptions-callback) | <span data-ttu-id="280d2-140">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-140">Method</span></span> |
| [<span data-ttu-id="280d2-141">getCallbackTokenAsync</span><span class="sxs-lookup"><span data-stu-id="280d2-141">getCallbackTokenAsync</span></span>](#getcallbacktokenasynccallback-usercontext) | <span data-ttu-id="280d2-142">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-142">Method</span></span> |
| [<span data-ttu-id="280d2-143">getUserIdentityTokenAsync</span><span class="sxs-lookup"><span data-stu-id="280d2-143">getUserIdentityTokenAsync</span></span>](#getuseridentitytokenasynccallback-usercontext) | <span data-ttu-id="280d2-144">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-144">Method</span></span> |
| [<span data-ttu-id="280d2-145">makeEwsRequestAsync</span><span class="sxs-lookup"><span data-stu-id="280d2-145">makeEwsRequestAsync</span></span>](#makeewsrequestasyncdata-callback-usercontext) | <span data-ttu-id="280d2-146">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-146">Method</span></span> |

### <a name="namespaces"></a><span data-ttu-id="280d2-147">命名空间</span><span class="sxs-lookup"><span data-stu-id="280d2-147">Namespaces</span></span>

<span data-ttu-id="280d2-148">[diagnostics](Office.context.mailbox.diagnostics.md)：将诊断信息提供给 Outlook 外接程序。</span><span class="sxs-lookup"><span data-stu-id="280d2-148">[diagnostics](Office.context.mailbox.diagnostics.md): Provides diagnostic information to an Outlook add-in.</span></span>

<span data-ttu-id="280d2-149">[item](Office.context.mailbox.item.md)：提供用于访问 Outlook 外接程序中的邮件或约会的方法和属性。</span><span class="sxs-lookup"><span data-stu-id="280d2-149">[item](Office.context.mailbox.item.md): Provides methods and properties for accessing a message or appointment in an Outlook add-in.</span></span>

<span data-ttu-id="280d2-150">[userProfile](Office.context.mailbox.userProfile.md)：提供有关 Outlook 外接程序中的用户的信息。</span><span class="sxs-lookup"><span data-stu-id="280d2-150">[userProfile](Office.context.mailbox.userProfile.md): Provides information about the user in an Outlook add-in.</span></span>

### <a name="members"></a><span data-ttu-id="280d2-151">成员</span><span class="sxs-lookup"><span data-stu-id="280d2-151">Members</span></span>

#### <a name="ewsurl-string"></a><span data-ttu-id="280d2-152">ewsUrl :String</span><span class="sxs-lookup"><span data-stu-id="280d2-152">ewsUrl :String</span></span>

<span data-ttu-id="280d2-p102">获取此电子邮件帐户的 Exchange Web 服务 (EWS) 终结点的 URL。仅限阅读模式。</span><span class="sxs-lookup"><span data-stu-id="280d2-p102">Gets the URL of the Exchange Web Services (EWS) endpoint for this email account. Read mode only.</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-155">此成员不支持适用于 iOS 的 Outlook 或 Outlook for Android。</span><span class="sxs-lookup"><span data-stu-id="280d2-155">This member is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="280d2-p103">远程服务可使用 `ewsUrl` 值对用户邮箱进行 EWS 调用。例如，可以创建远程服务来 [获取选定项目中的附件](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item)。</span><span class="sxs-lookup"><span data-stu-id="280d2-p103">The `ewsUrl` value can be used by a remote service to make EWS calls to the user's mailbox. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="280d2-158">应用必须在其清单中指定拥有 **ReadItem** 权限，才能调用阅读模式中的 `ewsUrl` 成员。</span><span class="sxs-lookup"><span data-stu-id="280d2-158">Your app must have the **ReadItem** permission specified in its manifest to call the `ewsUrl` member in read mode.</span></span>

<span data-ttu-id="280d2-p104">在撰写模式中，必须调用 [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) 方法，才能使用 `ewsUrl` 成员。应用必须具有调用 `saveAsync` 方法的 **ReadWriteItem** 权限。</span><span class="sxs-lookup"><span data-stu-id="280d2-p104">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `ewsUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="type"></a><span data-ttu-id="280d2-161">类型:</span><span class="sxs-lookup"><span data-stu-id="280d2-161">Type:</span></span>

*   <span data-ttu-id="280d2-162">String</span><span class="sxs-lookup"><span data-stu-id="280d2-162">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="280d2-163">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-163">Requirements</span></span>

|<span data-ttu-id="280d2-164">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-164">Requirement</span></span>| <span data-ttu-id="280d2-165">值</span><span class="sxs-lookup"><span data-stu-id="280d2-165">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-166">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-166">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-167">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-167">1.0</span></span>|
|[<span data-ttu-id="280d2-168">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-168">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-169">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-169">ReadItem</span></span>|
|[<span data-ttu-id="280d2-170">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-170">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-171">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-171">Compose or read</span></span>|

#### <a name="resturl-string"></a><span data-ttu-id="280d2-172">restUrl :String</span><span class="sxs-lookup"><span data-stu-id="280d2-172">restUrl :String</span></span>

<span data-ttu-id="280d2-173">获取此电子邮件帐户的 REST 终结点的 URL。</span><span class="sxs-lookup"><span data-stu-id="280d2-173">Gets the URL of the REST endpoint for this email account.</span></span>

<span data-ttu-id="280d2-174">`restUrl` 值可用于对用户邮箱进行 [REST API](https://docs.microsoft.com/outlook/rest/) 调用。</span><span class="sxs-lookup"><span data-stu-id="280d2-174">The `restUrl` value can be used to make [REST API](https://docs.microsoft.com/outlook/rest/) calls to the user's mailbox.</span></span>

<span data-ttu-id="280d2-175">应用必须在其清单中指定拥有 **ReadItem** 权限，才能调用阅读模式中的 `restUrl` 成员。</span><span class="sxs-lookup"><span data-stu-id="280d2-175">Your app must have the **ReadItem** permission specified in its manifest to call the `restUrl` member in read mode.</span></span>

<span data-ttu-id="280d2-p105">在撰写模式中，必须调用 [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) 方法，才能使用 `restUrl` 成员。应用必须具有调用 `saveAsync` 方法的 **ReadWriteItem** 权限。</span><span class="sxs-lookup"><span data-stu-id="280d2-p105">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method before you can use the `restUrl` member. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="type"></a><span data-ttu-id="280d2-178">类型:</span><span class="sxs-lookup"><span data-stu-id="280d2-178">Type:</span></span>

*   <span data-ttu-id="280d2-179">String</span><span class="sxs-lookup"><span data-stu-id="280d2-179">String</span></span>

##### <a name="requirements"></a><span data-ttu-id="280d2-180">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-180">Requirements</span></span>

|<span data-ttu-id="280d2-181">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-181">Requirement</span></span>| <span data-ttu-id="280d2-182">值</span><span class="sxs-lookup"><span data-stu-id="280d2-182">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-183">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-183">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-184">1.5</span><span class="sxs-lookup"><span data-stu-id="280d2-184">1.5</span></span> |
|[<span data-ttu-id="280d2-185">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-185">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-186">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-186">ReadItem</span></span>|
|[<span data-ttu-id="280d2-187">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-187">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-188">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-188">Compose or read</span></span>|

### <a name="methods"></a><span data-ttu-id="280d2-189">方法</span><span class="sxs-lookup"><span data-stu-id="280d2-189">Methods</span></span>

####  <a name="addhandlerasynceventtype-handler-options-callback"></a><span data-ttu-id="280d2-190">addHandlerAsync(eventType, handler, [options], [callback])</span><span class="sxs-lookup"><span data-stu-id="280d2-190">addHandlerAsync(eventType, handler, [options], [callback])</span></span>

<span data-ttu-id="280d2-191">添加支持事件的事件处理程序。</span><span class="sxs-lookup"><span data-stu-id="280d2-191">Adds an event handler for a supported event.</span></span>

<span data-ttu-id="280d2-192">目前，支持的事件类型的`Office.EventType.ItemChanged`和`Office.EventType.OfficeThemeChanged`。</span><span class="sxs-lookup"><span data-stu-id="280d2-192">Currently, the supported event types are `Office.EventType.ItemChanged` and `Office.EventType.OfficeThemeChanged`.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-193">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-193">Parameters:</span></span>

| <span data-ttu-id="280d2-194">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-194">Name</span></span> | <span data-ttu-id="280d2-195">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-195">Type</span></span> | <span data-ttu-id="280d2-196">属性</span><span class="sxs-lookup"><span data-stu-id="280d2-196">Attributes</span></span> | <span data-ttu-id="280d2-197">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-197">Description</span></span> |
|---|---|---|---|
| `eventType` | [<span data-ttu-id="280d2-198">Office.EventType</span><span class="sxs-lookup"><span data-stu-id="280d2-198">Office.EventType</span></span>](office.md#eventtype-string) || <span data-ttu-id="280d2-199">应调用处理程序的事件。</span><span class="sxs-lookup"><span data-stu-id="280d2-199">The event that should invoke the handler.</span></span> |
| `handler` | <span data-ttu-id="280d2-200">函数</span><span class="sxs-lookup"><span data-stu-id="280d2-200">Function</span></span> || <span data-ttu-id="280d2-p106">用于处理事件的函数。此函数必须接受一个参数，即对象文本。参数上的 `type` 属性将匹配传递给 `addHandlerAsync` 的 `eventType` 参数。</span><span class="sxs-lookup"><span data-stu-id="280d2-p106">The function to handle the event. The function must accept a single parameter, which is an object literal. The `type` property on the parameter will match the `eventType` parameter passed to `addHandlerAsync`.</span></span> |
| `options` | <span data-ttu-id="280d2-204">Object</span><span class="sxs-lookup"><span data-stu-id="280d2-204">Object</span></span> | <span data-ttu-id="280d2-205">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-205">&lt;optional&gt;</span></span> | <span data-ttu-id="280d2-206">包含一个或多个以下属性的对象文本。</span><span class="sxs-lookup"><span data-stu-id="280d2-206">An object literal that contains one or more of the following properties.</span></span> |
| `options.asyncContext` | <span data-ttu-id="280d2-207">对象</span><span class="sxs-lookup"><span data-stu-id="280d2-207">Object</span></span> | <span data-ttu-id="280d2-208">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-208">&lt;optional&gt;</span></span> | <span data-ttu-id="280d2-209">开发人员可以提供他们想要在回调方法中访问的任何对象。</span><span class="sxs-lookup"><span data-stu-id="280d2-209">Developers can provide any object they wish to access in the callback method.</span></span> |
| `callback` | <span data-ttu-id="280d2-210">函数</span><span class="sxs-lookup"><span data-stu-id="280d2-210">function</span></span>| <span data-ttu-id="280d2-211">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-211">&lt;optional&gt;</span></span>|<span data-ttu-id="280d2-212">方法完成后，使用单个参数 `callback`（一个 [`asyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `AsyncResult` 参数中传递的函数。</span><span class="sxs-lookup"><span data-stu-id="280d2-212">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-213">Requirements</span><span class="sxs-lookup"><span data-stu-id="280d2-213">Requirements</span></span>

|<span data-ttu-id="280d2-214">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-214">Requirement</span></span>| <span data-ttu-id="280d2-215">值</span><span class="sxs-lookup"><span data-stu-id="280d2-215">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-216">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-216">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-217">1.5</span><span class="sxs-lookup"><span data-stu-id="280d2-217">1.5</span></span> |
|[<span data-ttu-id="280d2-218">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-218">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-219">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-219">ReadItem</span></span> |
|[<span data-ttu-id="280d2-220">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-220">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-221">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-221">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-222">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-222">Example</span></span>

```
Office.initialize = function (reason) {
  $(document).ready(function () {
    Office.context.mailbox.addHandlerAsync(Office.EventType.ItemChanged, loadNewItem, function (result) {
      if (result.status === Office.AsyncResultStatus.Failed) {
        // Handle error
      }
    });
  });
};

function loadNewItem(eventArgs) {
  // Load the properties of the newly selected item
  loadProps(Office.context.mailbox.item);
};
```

####  <a name="converttoewsiditemid-restversion--string"></a><span data-ttu-id="280d2-223">convertToEwsId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="280d2-223">convertToEwsId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="280d2-224">将项目 ID 格式化（从 REST 转换为 EWS 格式）。</span><span class="sxs-lookup"><span data-stu-id="280d2-224">Converts an item ID formatted for REST into EWS format.</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-225">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="280d2-225">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="280d2-p107">通过 REST API 检索的项 ID（如 [Outlook 邮件 API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) 或 [Microsoft Graph](http://graph.microsoft.io/)）使用与 Exchange Web 服务 (EWS) 所使用格式不同的格式。`convertToEwsId` 方法将 REST 格式化的 ID 转换为正确的 EWS 格式。</span><span class="sxs-lookup"><span data-stu-id="280d2-p107">Item IDs retrieved via a REST API (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)) use a different format than the format used by Exchange Web Services (EWS). The `convertToEwsId` method converts a REST-formatted ID into the proper format for EWS.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-228">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-228">Parameters:</span></span>

|<span data-ttu-id="280d2-229">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-229">Name</span></span>| <span data-ttu-id="280d2-230">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-230">Type</span></span>| <span data-ttu-id="280d2-231">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-231">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="280d2-232">字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-232">String</span></span>|<span data-ttu-id="280d2-233">Outlook REST API 的格式化的项目 ID。</span><span class="sxs-lookup"><span data-stu-id="280d2-233">An item ID formatted for the Outlook REST APIs</span></span>|
|`restVersion`| [<span data-ttu-id="280d2-234">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="280d2-234">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook/office.mailboxenums.restversion)|<span data-ttu-id="280d2-235">指示用于检索项目 ID 的 Outlook REST API 的版本。</span><span class="sxs-lookup"><span data-stu-id="280d2-235">A value indicating the version of the Outlook REST API used to retrieve the item ID.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-236">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-236">Requirements</span></span>

|<span data-ttu-id="280d2-237">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-237">Requirement</span></span>| <span data-ttu-id="280d2-238">值</span><span class="sxs-lookup"><span data-stu-id="280d2-238">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-239">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-239">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-240">1.3</span><span class="sxs-lookup"><span data-stu-id="280d2-240">1.3</span></span>|
|[<span data-ttu-id="280d2-241">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-241">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-242">受限</span><span class="sxs-lookup"><span data-stu-id="280d2-242">Restricted</span></span>|
|[<span data-ttu-id="280d2-243">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-243">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-244">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-244">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="280d2-245">返回：</span><span class="sxs-lookup"><span data-stu-id="280d2-245">Returns:</span></span>

<span data-ttu-id="280d2-246">类型：字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-246">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="280d2-247">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-247">Example</span></span>

```
// Get an item's ID from a REST API
var restId = 'AAMkAGVlOTZjNTM3LW...';

// Treat restId as coming from the v2.0 version of the
// Outlook Mail API
var ewsId = Office.context.mailbox.convertToEwsId(restId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttolocalclienttimetimevalue--localclienttimejavascriptapioutlookofficelocalclienttime"></a><span data-ttu-id="280d2-248">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook/office.LocalClientTime)}</span><span class="sxs-lookup"><span data-stu-id="280d2-248">convertToLocalClientTime(timeValue) → {[LocalClientTime](/javascript/api/outlook/office.LocalClientTime)}</span></span>

<span data-ttu-id="280d2-249">获取包含以本地客户端时间表示的时间信息的字典。</span><span class="sxs-lookup"><span data-stu-id="280d2-249">Gets a dictionary containing time information in local client time.</span></span>

<span data-ttu-id="280d2-p108">Outlook 或 Outlook Web App 邮件应用程序的日期和时间可以使用不同的时区。Outlook 使用客户端计算机时区；Outlook Web App 使用 Exchange 管理中心 (EAC) 中设置的时区。应对日期和时间值进行处理，以便用户界面上显示的值始终与用户预期的时区一致。</span><span class="sxs-lookup"><span data-stu-id="280d2-p108">The dates and times used by a mail app for Outlook or Outlook Web App can use different time zones. Outlook uses the client computer time zone; Outlook Web App uses the time zone set on the Exchange Admin Center (EAC). You should handle date and time values so that the values you display on the user interface are always consistent with the time zone that the user expects.</span></span>

<span data-ttu-id="280d2-p109">如果邮件应用程序在 Outlook 中运行，`convertToLocalClientTime` 方法将返回一个值设置为客户端计算机时区的字典对象。如果邮件应用程序在 Outlook Web App 中运行，`convertToLocalClientTime` 方法将返回值设置为 EAC 中指定的时区的字典对象。</span><span class="sxs-lookup"><span data-stu-id="280d2-p109">If the mail app is running in Outlook, the `convertToLocalClientTime` method will return a dictionary object with the values set to the client computer time zone. If the mail app is running in Outlook Web App, the `convertToLocalClientTime` method will return a dictionary object with the values set to the time zone specified in the EAC.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-255">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-255">Parameters:</span></span>

|<span data-ttu-id="280d2-256">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-256">Name</span></span>| <span data-ttu-id="280d2-257">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-257">Type</span></span>| <span data-ttu-id="280d2-258">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-258">Description</span></span>|
|---|---|---|
|`timeValue`| <span data-ttu-id="280d2-259">日期</span><span class="sxs-lookup"><span data-stu-id="280d2-259">Date</span></span>|<span data-ttu-id="280d2-260">一个 Date 对象</span><span class="sxs-lookup"><span data-stu-id="280d2-260">A Date object</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-261">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-261">Requirements</span></span>

|<span data-ttu-id="280d2-262">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-262">Requirement</span></span>| <span data-ttu-id="280d2-263">值</span><span class="sxs-lookup"><span data-stu-id="280d2-263">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-264">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-264">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-265">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-265">1.0</span></span>|
|[<span data-ttu-id="280d2-266">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-266">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-267">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-267">ReadItem</span></span>|
|[<span data-ttu-id="280d2-268">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-268">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-269">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-269">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="280d2-270">返回：</span><span class="sxs-lookup"><span data-stu-id="280d2-270">Returns:</span></span>

<span data-ttu-id="280d2-271">类型：[LocalClientTime](/javascript/api/outlook/office.LocalClientTime)</span><span class="sxs-lookup"><span data-stu-id="280d2-271">Type: [LocalClientTime](/javascript/api/outlook/office.LocalClientTime)</span></span>

####  <a name="converttorestiditemid-restversion--string"></a><span data-ttu-id="280d2-272">convertToRestId(itemId, restVersion) → {String}</span><span class="sxs-lookup"><span data-stu-id="280d2-272">convertToRestId(itemId, restVersion) → {String}</span></span>

<span data-ttu-id="280d2-273">将项目 ID 格式化（从 EWS 转换为 REST 格式）。</span><span class="sxs-lookup"><span data-stu-id="280d2-273">Converts an item ID formatted for EWS into REST format.</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-274">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="280d2-274">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="280d2-p110">与 REST API 所使用的格式比较，通过 EWS 或通过 `itemId` 属性检索的项目 ID 使用不同的格式（例如 [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) 或 [Microsoft Graph](http://graph.microsoft.io/)）。`convertToRestId` 方法将 EWS 格式化的 ID 转换为正确的 REST 格式。</span><span class="sxs-lookup"><span data-stu-id="280d2-p110">Item IDs retrieved via EWS or via the `itemId` property use a different format than the format used by REST APIs (such as the [Outlook Mail API](https://docs.microsoft.com/previous-versions/office/office-365-api/api/version-2.0/mail-rest-operations) or the [Microsoft Graph](http://graph.microsoft.io/)). The `convertToRestId` method converts an EWS-formatted ID into the proper format for REST.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-277">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-277">Parameters:</span></span>

|<span data-ttu-id="280d2-278">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-278">Name</span></span>| <span data-ttu-id="280d2-279">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-279">Type</span></span>| <span data-ttu-id="280d2-280">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-280">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="280d2-281">字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-281">String</span></span>|<span data-ttu-id="280d2-282">适用于 Exchange Web 服务 (EWS) 的项目 ID 格式化。</span><span class="sxs-lookup"><span data-stu-id="280d2-282">An item ID formatted for Exchange Web Services (EWS)</span></span>|
|`restVersion`| [<span data-ttu-id="280d2-283">Office.MailboxEnums.RestVersion</span><span class="sxs-lookup"><span data-stu-id="280d2-283">Office.MailboxEnums.RestVersion</span></span>](/javascript/api/outlook/office.mailboxenums.restversion)|<span data-ttu-id="280d2-284">值指示转换的 ID 所使用的 Outlook REST API 的版本。</span><span class="sxs-lookup"><span data-stu-id="280d2-284">A value indicating the version of the Outlook REST API that the converted ID will be used with.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-285">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-285">Requirements</span></span>

|<span data-ttu-id="280d2-286">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-286">Requirement</span></span>| <span data-ttu-id="280d2-287">值</span><span class="sxs-lookup"><span data-stu-id="280d2-287">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-288">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-288">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-289">1.3</span><span class="sxs-lookup"><span data-stu-id="280d2-289">1.3</span></span>|
|[<span data-ttu-id="280d2-290">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-290">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-291">受限</span><span class="sxs-lookup"><span data-stu-id="280d2-291">Restricted</span></span>|
|[<span data-ttu-id="280d2-292">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-292">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-293">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-293">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="280d2-294">返回：</span><span class="sxs-lookup"><span data-stu-id="280d2-294">Returns:</span></span>

<span data-ttu-id="280d2-295">类型：字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-295">Type: String</span></span>

##### <a name="example"></a><span data-ttu-id="280d2-296">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-296">Example</span></span>

```
// Get the currently selected item's ID
var ewsId = Office.context.mailbox.item.itemId;

// Convert to a REST ID for the v2.0 version of the
// Outlook Mail API
var restId = Office.context.mailbox.convertToRestId(ewsId, Office.MailboxEnums.RestVersion.v2_0);
```

####  <a name="converttoutcclienttimeinput--date"></a><span data-ttu-id="280d2-297">convertToUtcClientTime(input) → {Date}</span><span class="sxs-lookup"><span data-stu-id="280d2-297">convertToUtcClientTime(input) → {Date}</span></span>

<span data-ttu-id="280d2-298">从包含时间信息的字典中获取 Date 对象。</span><span class="sxs-lookup"><span data-stu-id="280d2-298">Gets a Date object from a dictionary containing time information.</span></span>

<span data-ttu-id="280d2-299">`convertToUtcClientTime` 方法将包含本地日期和时间的字典转换为包含与本地日期和时间对应的正确值的 Date 对象。</span><span class="sxs-lookup"><span data-stu-id="280d2-299">The `convertToUtcClientTime` method converts a dictionary containing a local date and time to a Date object with the correct values for the local date and time.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-300">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-300">Parameters:</span></span>

|<span data-ttu-id="280d2-301">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-301">Name</span></span>| <span data-ttu-id="280d2-302">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-302">Type</span></span>| <span data-ttu-id="280d2-303">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-303">Description</span></span>|
|---|---|---|
|`input`| [<span data-ttu-id="280d2-304">LocalClientTime</span><span class="sxs-lookup"><span data-stu-id="280d2-304">LocalClientTime</span></span>](/javascript/api/outlook/office.LocalClientTime)|<span data-ttu-id="280d2-305">要转换的本地时间值。</span><span class="sxs-lookup"><span data-stu-id="280d2-305">The local time value to convert.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-306">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-306">Requirements</span></span>

|<span data-ttu-id="280d2-307">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-307">Requirement</span></span>| <span data-ttu-id="280d2-308">值</span><span class="sxs-lookup"><span data-stu-id="280d2-308">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-309">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-309">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-310">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-310">1.0</span></span>|
|[<span data-ttu-id="280d2-311">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-311">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-312">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-312">ReadItem</span></span>|
|[<span data-ttu-id="280d2-313">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-313">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-314">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-314">Compose or read</span></span>|

##### <a name="returns"></a><span data-ttu-id="280d2-315">返回：</span><span class="sxs-lookup"><span data-stu-id="280d2-315">Returns:</span></span>

<span data-ttu-id="280d2-316">包含以 UTC 表示的时间的 Date 对象。</span><span class="sxs-lookup"><span data-stu-id="280d2-316">A Date object with the time expressed in UTC.</span></span>

<dl class="param-type"><span data-ttu-id="280d2-317">

<dt>
类型</dt>


</span><span class="sxs-lookup"><span data-stu-id="280d2-317">

<dt>Type</dt>

</span></span><dd><span data-ttu-id="280d2-318">日期</span><span class="sxs-lookup"><span data-stu-id="280d2-318">Date</span></span></dd>

</dl>

####  <a name="displayappointmentformitemid"></a><span data-ttu-id="280d2-319">displayAppointmentForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="280d2-319">displayAppointmentForm(itemId)</span></span>

<span data-ttu-id="280d2-320">显示现有日历约会。</span><span class="sxs-lookup"><span data-stu-id="280d2-320">Displays an existing calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-321">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="280d2-321">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="280d2-322">`displayAppointmentForm` 方法将打开桌面新窗口中或移动设备对话框中的现有日历约会。</span><span class="sxs-lookup"><span data-stu-id="280d2-322">The `displayAppointmentForm` method opens an existing calendar appointment in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="280d2-p111">在 Outlook for Mac 中，您可以使用此方法来显示不属于定期系列的单个约会，或显示定期系列的主约会，但无法显示该系列的实例。这是因为在 Outlook for Mac 中，无法访问定期系列实例的属性（包括项目 ID）。</span><span class="sxs-lookup"><span data-stu-id="280d2-p111">In Outlook for Mac, you can use this method to display a single appointment that is not part of a recurring series, or the master appointment of a recurring series, but you cannot display an instance of the series. This is because in Outlook for Mac, you cannot access the properties (including the item ID) of instances of a recurring series.</span></span>

<span data-ttu-id="280d2-325">在 Outlook Web App 中，此方法仅在窗体正文小于或等于 32KB 字符数时，才会打开指定的窗体。</span><span class="sxs-lookup"><span data-stu-id="280d2-325">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32KB number of characters.</span></span>

<span data-ttu-id="280d2-326">如果指定的项标识符没有识别现有约会，将在客户端计算机或设备上打开一个空白窗格，并且不会返回错误消息。</span><span class="sxs-lookup"><span data-stu-id="280d2-326">If the specified item identifier does not identify an existing appointment, a blank pane opens on the client computer or device, and no error message will be returned.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-327">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-327">Parameters:</span></span>

|<span data-ttu-id="280d2-328">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-328">Name</span></span>| <span data-ttu-id="280d2-329">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-329">Type</span></span>| <span data-ttu-id="280d2-330">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-330">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="280d2-331">字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-331">String</span></span>|<span data-ttu-id="280d2-332">现有日历约会的 Exchange Web 服务 (EWS) 标识符。</span><span class="sxs-lookup"><span data-stu-id="280d2-332">The Exchange Web Services (EWS) identifier for an existing calendar appointment.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-333">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-333">Requirements</span></span>

|<span data-ttu-id="280d2-334">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-334">Requirement</span></span>| <span data-ttu-id="280d2-335">值</span><span class="sxs-lookup"><span data-stu-id="280d2-335">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-336">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-336">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-337">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-337">1.0</span></span>|
|[<span data-ttu-id="280d2-338">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-338">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-339">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-339">ReadItem</span></span>|
|[<span data-ttu-id="280d2-340">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-340">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-341">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-341">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-342">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-342">Example</span></span>

```
Office.context.mailbox.displayAppointmentForm(appointmentId);
```

####  <a name="displaymessageformitemid"></a><span data-ttu-id="280d2-343">displayMessageForm(itemId)</span><span class="sxs-lookup"><span data-stu-id="280d2-343">displayMessageForm(itemId)</span></span>

<span data-ttu-id="280d2-344">显示现有邮件。</span><span class="sxs-lookup"><span data-stu-id="280d2-344">Displays an existing message.</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-345">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="280d2-345">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="280d2-346">`displayMessageForm` 方法将打开桌面新窗口中或移动设备对话框中的现有邮件。</span><span class="sxs-lookup"><span data-stu-id="280d2-346">The `displayMessageForm` method opens an existing message in a new window on the desktop or in a dialog box on mobile devices.</span></span>

<span data-ttu-id="280d2-347">在 Outlook Web App 中，此方法仅在窗体正文小于或等于 32 KB 字符数时，才会打开指定的窗体。</span><span class="sxs-lookup"><span data-stu-id="280d2-347">In Outlook Web App, this method opens the specified form only if the body of the form is less than or equal to 32 KB number of characters.</span></span>

<span data-ttu-id="280d2-348">如果指定的项标识符未识别现有消息，则客户端计算机上不会显示任何消息，并且也不会返回错误消息。</span><span class="sxs-lookup"><span data-stu-id="280d2-348">If the specified item identifier does not identify an existing message, no message will be displayed on the client computer, and no error message will be returned.</span></span>

<span data-ttu-id="280d2-p112">不要使用包含表示约会的 `itemId` 的 `displayMessageForm`。使用 `displayAppointmentForm` 方法显示现有的约会，并使用 `displayNewAppointmentForm` 显示窗体以新建约会。</span><span class="sxs-lookup"><span data-stu-id="280d2-p112">Do not use the `displayMessageForm` with an `itemId` that represents an appointment. Use the `displayAppointmentForm` method to display an existing appointment, and `displayNewAppointmentForm` to display a form to create a new appointment.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-351">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-351">Parameters:</span></span>

|<span data-ttu-id="280d2-352">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-352">Name</span></span>| <span data-ttu-id="280d2-353">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-353">Type</span></span>| <span data-ttu-id="280d2-354">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-354">Description</span></span>|
|---|---|---|
|`itemId`| <span data-ttu-id="280d2-355">字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-355">String</span></span>|<span data-ttu-id="280d2-356">现有消息的 Exchange Web 服务 (EWS) 标识符。</span><span class="sxs-lookup"><span data-stu-id="280d2-356">The Exchange Web Services (EWS) identifier for an existing message.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-357">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-357">Requirements</span></span>

|<span data-ttu-id="280d2-358">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-358">Requirement</span></span>| <span data-ttu-id="280d2-359">值</span><span class="sxs-lookup"><span data-stu-id="280d2-359">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-360">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-360">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-361">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-361">1.0</span></span>|
|[<span data-ttu-id="280d2-362">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-362">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-363">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-363">ReadItem</span></span>|
|[<span data-ttu-id="280d2-364">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-364">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-365">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-365">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-366">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-366">Example</span></span>

```
Office.context.mailbox.displayMessageForm(messageId);
```

#### <a name="displaynewappointmentformparameters"></a><span data-ttu-id="280d2-367">displayNewAppointmentForm(parameters)</span><span class="sxs-lookup"><span data-stu-id="280d2-367">displayNewAppointmentForm(parameters)</span></span>

<span data-ttu-id="280d2-368">显示用于新建日历约会的表单。</span><span class="sxs-lookup"><span data-stu-id="280d2-368">Displays a form for creating a new calendar appointment.</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-369">在适用于 iOS 的 Outlook 或 Outlook for Android 中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="280d2-369">This method is not supported in Outlook for iOS or Outlook for Android.</span></span>

<span data-ttu-id="280d2-p113">`displayNewAppointmentForm` 方法打开可让用户新建约会或会议的窗体。如果指定了参数，将使用参数的内容自动填充约会窗体字段。</span><span class="sxs-lookup"><span data-stu-id="280d2-p113">The `displayNewAppointmentForm` method opens a form that enables the user to create a new appointment or meeting. If parameters are specified, the appointment form fields are automatically populated with the contents of the parameters.</span></span>

<span data-ttu-id="280d2-p114">在 Outlook Web App 和适用于设备的 OWA 中，此方法始终显示包含与会者字段的窗体。如果你未将任何与会者指定为输入参数，该方法将显示为一个包含“**保存**”按钮的窗体。如果已指定与会者，窗体将包含与会者和“**发送**”按钮。</span><span class="sxs-lookup"><span data-stu-id="280d2-p114">In Outlook Web App and OWA for Devices, this method always displays a form with an attendees field. If you do not specify any attendees as input arguments, the method displays a form with a **Save** button. If you have specified attendees, the form would include the attendees and a **Send** button.</span></span>

<span data-ttu-id="280d2-p115">在 Outlook 富客户端和 Outlook RT 中，如果在 `requiredAttendees`、`optionalAttendees` 或 `resources` 参数中指定任何与会者或资源，此方法将显示会议窗体，其中包含一个“**发送**”按钮。如果未指定任何收件人，此方法将显示一个包含“**保存并关闭**”按钮的约会窗体。</span><span class="sxs-lookup"><span data-stu-id="280d2-p115">In the Outlook rich client and Outlook RT, if you specify any attendees or resources in the `requiredAttendees`, `optionalAttendees`, or `resources` parameter, this method displays a meeting form with a **Send** button. If you don't specify any recipients, this method displays an appointment form with a **Save & Close** button.</span></span>

<span data-ttu-id="280d2-377">如果任何参数超过指定大小限制，或者指定了未知参数名称，则会引发异常。</span><span class="sxs-lookup"><span data-stu-id="280d2-377">If any of the parameters exceed the specified size limits, or if an unknown parameter name is specified, an exception is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-378">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-378">Parameters:</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-379">所有参数都是可选的。</span><span class="sxs-lookup"><span data-stu-id="280d2-379">All parameters are optional.</span></span>

|<span data-ttu-id="280d2-380">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-380">Name</span></span>| <span data-ttu-id="280d2-381">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-381">Type</span></span>| <span data-ttu-id="280d2-382">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-382">Description</span></span>|
|---|---|---|
| `parameters` | <span data-ttu-id="280d2-383">对象</span><span class="sxs-lookup"><span data-stu-id="280d2-383">Object</span></span> | <span data-ttu-id="280d2-384">描述新约会的参数字典。</span><span class="sxs-lookup"><span data-stu-id="280d2-384">A dictionary of parameters describing the new appointment.</span></span> |
| `parameters.requiredAttendees` | <span data-ttu-id="280d2-385">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-385">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="280d2-p116">包含电子邮件地址的字符串数组或包含约会的每个必需与会者的 `EmailAddressDetails` 对象的数组。数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="280d2-p116">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the required attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.optionalAttendees` | <span data-ttu-id="280d2-388">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-388">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="280d2-p117">包含电子邮件地址的字符串数组或包含约会的每个可选与会者的 `EmailAddressDetails` 对象的数组。数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="280d2-p117">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the optional attendees for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.start` | <span data-ttu-id="280d2-391">Date</span><span class="sxs-lookup"><span data-stu-id="280d2-391">Date</span></span> | <span data-ttu-id="280d2-392">指定约会的开始日期和时间的 `Date` 对象。</span><span class="sxs-lookup"><span data-stu-id="280d2-392">A `Date` object specifying the start date and time of the appointment.</span></span> |
| `parameters.end` | <span data-ttu-id="280d2-393">Date</span><span class="sxs-lookup"><span data-stu-id="280d2-393">Date</span></span> | <span data-ttu-id="280d2-394">指定约会的结束日期和时间的 `Date` 对象。</span><span class="sxs-lookup"><span data-stu-id="280d2-394">A `Date` object specifying the end date and time of the appointment.</span></span> |
| `parameters.location` | <span data-ttu-id="280d2-395">String</span><span class="sxs-lookup"><span data-stu-id="280d2-395">String</span></span> | <span data-ttu-id="280d2-p118">包含约会位置的字符串。字符串长度限制为最多 255 个字符。</span><span class="sxs-lookup"><span data-stu-id="280d2-p118">A string containing the location of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.resources` | <span data-ttu-id="280d2-398">Array.&lt;String&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-398">Array.&lt;String&gt;</span></span> | <span data-ttu-id="280d2-p119">包含约会所需资源的字符串数组。数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="280d2-p119">An array of strings containing the resources required for the appointment. The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.subject` | <span data-ttu-id="280d2-401">String</span><span class="sxs-lookup"><span data-stu-id="280d2-401">String</span></span> | <span data-ttu-id="280d2-p120">包含约会主题的字符串。字符串长度限制为最多 255 个字符。</span><span class="sxs-lookup"><span data-stu-id="280d2-p120">A string containing the subject of the appointment. The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.body` | <span data-ttu-id="280d2-404">String</span><span class="sxs-lookup"><span data-stu-id="280d2-404">String</span></span> | <span data-ttu-id="280d2-p121">约会的正文。正文内容限制为最大 32 KB。</span><span class="sxs-lookup"><span data-stu-id="280d2-p121">The body of the appointment. The body content is limited to a maximum size of 32 KB.</span></span> |

##### <a name="requirements"></a><span data-ttu-id="280d2-407">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-407">Requirements</span></span>

|<span data-ttu-id="280d2-408">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-408">Requirement</span></span>| <span data-ttu-id="280d2-409">值</span><span class="sxs-lookup"><span data-stu-id="280d2-409">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-410">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-410">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-411">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-411">1.0</span></span>|
|[<span data-ttu-id="280d2-412">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-412">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-413">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-413">ReadItem</span></span>|
|[<span data-ttu-id="280d2-414">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-414">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-415">阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-415">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-416">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-416">Example</span></span>

```
var start = new Date();
var end = new Date();
end.setHours(start.getHours() + 1);

Office.context.mailbox.displayNewAppointmentForm(
  {
    requiredAttendees: ['bob@contoso.com'],
    optionalAttendees: ['sam@contoso.com'],
    start: start,
    end: end,
    location: 'Home',
    resources: ['projector@contoso.com'],
    subject: 'meeting',
    body: 'Hello World!'
  });
```

#### <a name="displaynewmessageformparameters"></a><span data-ttu-id="280d2-417">displayNewMessageForm(parameters)</span><span class="sxs-lookup"><span data-stu-id="280d2-417">displayNewMessageForm(parameters)</span></span>

<span data-ttu-id="280d2-418">显示用于新建邮件的窗体。</span><span class="sxs-lookup"><span data-stu-id="280d2-418">Displays a form for creating a new message.</span></span>

<span data-ttu-id="280d2-419">`displayNewMessageForm` 方法将打开可让用户新建邮件的窗体。</span><span class="sxs-lookup"><span data-stu-id="280d2-419">The `displayNewMessageForm` method opens a form that enables the user to create a new message.</span></span> <span data-ttu-id="280d2-420">如果指定了参数，将使用参数的内容自动填充邮件窗体字段。</span><span class="sxs-lookup"><span data-stu-id="280d2-420">If parameters are specified, the message form fields are automatically populated with the contents of the parameters.</span></span>

<span data-ttu-id="280d2-421">如果任何参数超过指定大小限制，或者指定了未知参数名称，则会引发异常。</span><span class="sxs-lookup"><span data-stu-id="280d2-421">If any of the parameters exceed the specified size limits, or if an unknown parameter name is specified, an exception is thrown.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-422">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-422">Parameters:</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-423">所有参数都是可选的。</span><span class="sxs-lookup"><span data-stu-id="280d2-423">All parameters are optional.</span></span>

|<span data-ttu-id="280d2-424">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-424">Name</span></span>| <span data-ttu-id="280d2-425">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-425">Type</span></span>| <span data-ttu-id="280d2-426">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-426">Description</span></span>|
|---|---|---|
| `parameters` | <span data-ttu-id="280d2-427">对象</span><span class="sxs-lookup"><span data-stu-id="280d2-427">Object</span></span> | <span data-ttu-id="280d2-428">描述新邮件的参数字典。</span><span class="sxs-lookup"><span data-stu-id="280d2-428">A dictionary of parameters describing the new message.</span></span> |
| `parameters.toRecipients` | <span data-ttu-id="280d2-429">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-429">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="280d2-430">包含电子邮件地址的字符串数组或包含收件人行上每个收件人的 `EmailAddressDetails` 对象的数组。</span><span class="sxs-lookup"><span data-stu-id="280d2-430">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the To line.</span></span> <span data-ttu-id="280d2-431">数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="280d2-431">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.ccRecipients` | <span data-ttu-id="280d2-432">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-432">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="280d2-433">包含电子邮件地址的字符串数组或包含抄送行上每个收件人的 `EmailAddressDetails` 对象的数组。</span><span class="sxs-lookup"><span data-stu-id="280d2-433">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the Cc line.</span></span> <span data-ttu-id="280d2-434">数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="280d2-434">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.bccRecipients` | <span data-ttu-id="280d2-435">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-435">Array.&lt;String&gt; &#124; Array.&lt;[EmailAddressDetails](/javascript/api/outlook/office.emailaddressdetails)&gt;</span></span> | <span data-ttu-id="280d2-436">包含电子邮件地址的字符串数组或包含密件抄送行上每个收件人的 `EmailAddressDetails` 对象的数组。</span><span class="sxs-lookup"><span data-stu-id="280d2-436">An array of strings containing the email addresses or an array containing an `EmailAddressDetails` object for each of the recipients on the Bcc line.</span></span> <span data-ttu-id="280d2-437">数组限制为最多 100 个条目。</span><span class="sxs-lookup"><span data-stu-id="280d2-437">The array is limited to a maximum of 100 entries.</span></span> |
| `parameters.subject` | <span data-ttu-id="280d2-438">String</span><span class="sxs-lookup"><span data-stu-id="280d2-438">String</span></span> | <span data-ttu-id="280d2-439">包含邮件主题的字符串。</span><span class="sxs-lookup"><span data-stu-id="280d2-439">A string containing the subject of the message.</span></span> <span data-ttu-id="280d2-440">字符串长度限制为最多 255 个字符。</span><span class="sxs-lookup"><span data-stu-id="280d2-440">The string is limited to a maximum of 255 characters.</span></span> |
| `parameters.htmlBody` | <span data-ttu-id="280d2-441">String</span><span class="sxs-lookup"><span data-stu-id="280d2-441">String</span></span> | <span data-ttu-id="280d2-442">邮件的 HTML 正文。</span><span class="sxs-lookup"><span data-stu-id="280d2-442">The HTML body of the message.</span></span> <span data-ttu-id="280d2-443">正文内容限制为最大 32 KB。</span><span class="sxs-lookup"><span data-stu-id="280d2-443">The body content is limited to a maximum size of 32 KB.</span></span> |
| `parameters.attachments` | <span data-ttu-id="280d2-444">Array.&lt;Object&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-444">Array.&lt;Object&gt;</span></span> | <span data-ttu-id="280d2-445">JSON 对象（文件或项目附件）数组。</span><span class="sxs-lookup"><span data-stu-id="280d2-445">An array of JSON objects that are either file or item attachments.</span></span> |
| `parameters.attachments.type` | <span data-ttu-id="280d2-446">字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-446">String</span></span> | <span data-ttu-id="280d2-p128">指示附件的类型。必须是文件附件的 `file` 或项目附件的 `item`。</span><span class="sxs-lookup"><span data-stu-id="280d2-p128">Indicates the type of attachment. Must be `file` for a file attachment or `item` for an item attachment.</span></span> |
| `parameters.attachments.name` | <span data-ttu-id="280d2-449">字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-449">String</span></span> | <span data-ttu-id="280d2-450">一个包含附件的名称的字符串，最多包含 255 个字符。</span><span class="sxs-lookup"><span data-stu-id="280d2-450">A string that contains the name of the attachment, up to 255 characters in length.</span></span>|
| `parameters.attachments.url` | <span data-ttu-id="280d2-451">String</span><span class="sxs-lookup"><span data-stu-id="280d2-451">String</span></span> | <span data-ttu-id="280d2-p129">仅在将 `type` 设置为 `file` 时使用。文件的位置的 URI。</span><span class="sxs-lookup"><span data-stu-id="280d2-p129">Only used if `type` is set to `file`. The URI of the location for the file.</span></span> |
| `parameters.attachments.isInline` | <span data-ttu-id="280d2-454">Boolean</span><span class="sxs-lookup"><span data-stu-id="280d2-454">Boolean</span></span> | <span data-ttu-id="280d2-p130">仅在将 `type` 设置为 `file` 时使用。如果为 `true`，则表示附件将在邮件正文中内联显示，并且不应显示在附件列表中。</span><span class="sxs-lookup"><span data-stu-id="280d2-p130">Only used if `type` is set to `file`. If `true`, indicates that the attachment will be shown inline in the message body, and should not be displayed in the attachment list.</span></span> |
| `parameters.attachments.itemId` | <span data-ttu-id="280d2-457">String</span><span class="sxs-lookup"><span data-stu-id="280d2-457">String</span></span> | <span data-ttu-id="280d2-458">仅在 `type` 设置为 `item` 时使用。</span><span class="sxs-lookup"><span data-stu-id="280d2-458">Only used if `type` is set to `item`.</span></span> <span data-ttu-id="280d2-459">您想要附加到新邮件的现有电子邮件 EWS 项 id。</span><span class="sxs-lookup"><span data-stu-id="280d2-459">The EWS item id of the existing e-mail you want to attach to the new message.</span></span> <span data-ttu-id="280d2-460">字符串最长为 100 个字符。</span><span class="sxs-lookup"><span data-stu-id="280d2-460">This is a string up to 100 characters.</span></span> |


##### <a name="requirements"></a><span data-ttu-id="280d2-461">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-461">Requirements</span></span>

|<span data-ttu-id="280d2-462">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-462">Requirement</span></span>| <span data-ttu-id="280d2-463">值</span><span class="sxs-lookup"><span data-stu-id="280d2-463">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-464">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-464">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-465">1.6</span><span class="sxs-lookup"><span data-stu-id="280d2-465">1.6</span></span> |
|[<span data-ttu-id="280d2-466">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-466">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-467">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-467">ReadItem</span></span>|
|[<span data-ttu-id="280d2-468">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-468">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-469">阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-469">Read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-470">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-470">Example</span></span>

```
Office.context.mailbox.displayNewMessageForm(
  {
    toRecipients: Office.context.mailbox.item.to, // Copy the To line from current item
    ccRecipients: ['sam@contoso.com'],
    subject: 'Outlook add-ins are cool!',
    htmlBody: 'Hello <b>World</b>!<br/><img src="cid:image.png"></i>',
    attachments: [
      {
        type: 'file',
        name: 'image.png',
        url: 'http://contoso.com/image.png',
        isInline: true
      }
    ]
  });
```

#### <a name="getcallbacktokenasyncoptions-callback"></a><span data-ttu-id="280d2-471">getCallbackTokenAsync([options], callback)</span><span class="sxs-lookup"><span data-stu-id="280d2-471">getCallbackTokenAsync([options], callback)</span></span>

<span data-ttu-id="280d2-472">获取一个包含用于调用 REST API 或 Exchange Web 服务的令牌的字符串。</span><span class="sxs-lookup"><span data-stu-id="280d2-472">Gets a string that contains a token used to call REST APIs or Exchange Web Services.</span></span>

<span data-ttu-id="280d2-p132">`getCallbackTokenAsync` 方法进行异步调用，从托管用户邮箱的 Exchange Server 获取非跳转令牌。回调令牌的生存期为 5 分钟。</span><span class="sxs-lookup"><span data-stu-id="280d2-p132">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-475">建议外接程序而不是 Exchange Web 服务尽可能使用 REST Api。</span><span class="sxs-lookup"><span data-stu-id="280d2-475">It is recommended that add-ins use the REST APIs instead of Exchange Web Services whenever possible.</span></span> 

<span data-ttu-id="280d2-476">**REST 令牌**</span><span class="sxs-lookup"><span data-stu-id="280d2-476">**REST Tokens**</span></span>

<span data-ttu-id="280d2-p133">请求 REST 令牌时 (`options.isRest = true`) 时，生成的令牌将无法对 Exchange Web 服务调用进行身份验证。令牌的作用域限制为对当前项及其附件的只读访问，除非外接程序在其清单中指定了 [`ReadWriteMailbox`](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions#readwritemailbox-permission) 权限。如果指定了 `ReadWriteMailbox` 权限，则生成的令牌将授予对邮件、日历和联系人的读/写权限，包括发送邮件的功能。</span><span class="sxs-lookup"><span data-stu-id="280d2-p133">When a REST token is requested (`options.isRest = true`), the resulting token will not work to authenticate Exchange Web Services calls. The token will be limited in scope to read-only access to the current item and its attachments, unless the add-in has specified the [`ReadWriteMailbox`](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions#readwritemailbox-permission) permission in its manifest. If the `ReadWriteMailbox` permission is specified, the resulting token will grant read/write access to mail, calendar, and contacts, including the ability to send mail.</span></span>

<span data-ttu-id="280d2-480">在进行 REST API 调用时，外接程序应使用 `restUrl` 属性来确定要使用的正确 URL。</span><span class="sxs-lookup"><span data-stu-id="280d2-480">The add-in should use the `restUrl` property to determine the correct URL to use when making REST API calls.</span></span>

<span data-ttu-id="280d2-481">**EWS 令牌**</span><span class="sxs-lookup"><span data-stu-id="280d2-481">**EWS Tokens**</span></span>

<span data-ttu-id="280d2-p134">请求 EWS 令牌 (`options.isRest = false`) 时，生成的令牌将无法对 REST API 调用进行身份验证。令牌的作用域限制为访问当前项。</span><span class="sxs-lookup"><span data-stu-id="280d2-p134">When an EWS token is requested (`options.isRest = false`), the resulting token will not work to authenticate REST API calls. The token will be limited in scope to accessing the current item.</span></span>

<span data-ttu-id="280d2-484">外接程序应使用 `ewsUrl` 属性来确定进行 EWS 调用时要使用的正确 URL。</span><span class="sxs-lookup"><span data-stu-id="280d2-484">The add-in should use the `ewsUrl` property to determine the correct URL to use when making EWS calls.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-485">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-485">Parameters:</span></span>

|<span data-ttu-id="280d2-486">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-486">Name</span></span>| <span data-ttu-id="280d2-487">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-487">Type</span></span>| <span data-ttu-id="280d2-488">属性</span><span class="sxs-lookup"><span data-stu-id="280d2-488">Attributes</span></span>| <span data-ttu-id="280d2-489">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-489">Description</span></span>|
|---|---|---|---|
| `options` | <span data-ttu-id="280d2-490">对象</span><span class="sxs-lookup"><span data-stu-id="280d2-490">Object</span></span> | <span data-ttu-id="280d2-491">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-491">&lt;optional&gt;</span></span> | <span data-ttu-id="280d2-492">包含一个或多个以下属性的对象文本。</span><span class="sxs-lookup"><span data-stu-id="280d2-492">An object literal that contains one or more of the following properties.</span></span> |
| `options.isRest` | <span data-ttu-id="280d2-493">布尔值</span><span class="sxs-lookup"><span data-stu-id="280d2-493">Boolean</span></span> |  <span data-ttu-id="280d2-494">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-494">&lt;optional&gt;</span></span> | <span data-ttu-id="280d2-p135">确定所提供的令牌是否将用于 Outlook REST API 或 Exchange Web 服务。默认值为 `false`。</span><span class="sxs-lookup"><span data-stu-id="280d2-p135">Determines if the token provided will be used for the Outlook REST APIs or Exchange Web Services. Default value is `false`.</span></span> |
| `options.asyncContext` | <span data-ttu-id="280d2-497">对象</span><span class="sxs-lookup"><span data-stu-id="280d2-497">Object</span></span> |  <span data-ttu-id="280d2-498">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-498">&lt;optional&gt;</span></span> | <span data-ttu-id="280d2-499">传递给异步方法的任何状态数据。</span><span class="sxs-lookup"><span data-stu-id="280d2-499">Any state data that is passed to the asynchronous method.</span></span> |
|`callback`| <span data-ttu-id="280d2-500">函数</span><span class="sxs-lookup"><span data-stu-id="280d2-500">function</span></span>||<span data-ttu-id="280d2-p136">方法完成后，使用单个参数 `callback`（一个 [`asyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `AsyncResult` 参数中传递的函数。令牌作为 `asyncResult.value` 属性中的字符串提供。</span><span class="sxs-lookup"><span data-stu-id="280d2-p136">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-503">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-503">Requirements</span></span>

|<span data-ttu-id="280d2-504">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-504">Requirement</span></span>| <span data-ttu-id="280d2-505">值</span><span class="sxs-lookup"><span data-stu-id="280d2-505">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-506">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-506">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-507">1.5</span><span class="sxs-lookup"><span data-stu-id="280d2-507">1.5</span></span> |
|[<span data-ttu-id="280d2-508">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-508">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-509">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-509">ReadItem</span></span>|
|[<span data-ttu-id="280d2-510">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-510">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-511">撰写和阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-511">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-512">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-512">Example</span></span>

```js
function getCallbackToken() {
  var options = {
    isRest: true,
    asyncContext: { message: 'Hello World!' }
  };

  Office.context.mailbox.getCallbackTokenAsync(options, cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

#### <a name="getcallbacktokenasynccallback-usercontext"></a><span data-ttu-id="280d2-513">getCallbackTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="280d2-513">getCallbackTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="280d2-514">获取一个字符串，其中包含用于从 Exchange Server 获取附件或项目的令牌。</span><span class="sxs-lookup"><span data-stu-id="280d2-514">Gets a string that contains a token used to get an attachment or item from an Exchange Server.</span></span>

<span data-ttu-id="280d2-p137">`getCallbackTokenAsync` 方法进行异步调用，从托管用户邮箱的 Exchange Server 获取非跳转令牌。回调令牌的生存期为 5 分钟。</span><span class="sxs-lookup"><span data-stu-id="280d2-p137">The `getCallbackTokenAsync` method makes an asynchronous call to get an opaque token from the Exchange Server that hosts the user's mailbox. The lifetime of the callback token is 5 minutes.</span></span>

<span data-ttu-id="280d2-p138">可以将令牌和附件标识符或项标识符传递到第三方系统。第三方系统使用令牌作为持有者身份验证令牌调用 Exchange Web 服务 (EWS) [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) 或 [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation)，以返回附件或项目。例如，可以创建远程服务来[获取选定项目中的附件](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item)。</span><span class="sxs-lookup"><span data-stu-id="280d2-p138">You can pass the token and an attachment identifier or item identifier to a third-party system. The third-party system uses the token as a bearer authorization token to call the Exchange Web Services (EWS) [GetAttachment](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getattachment-operation) or [GetItem](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getitem-operation) operation to return an attachment or item. For example, you can create a remote service to [get attachments from the selected item](https://docs.microsoft.com/outlook/add-ins/get-attachments-of-an-outlook-item).</span></span>

<span data-ttu-id="280d2-520">应用必须在其清单中指定拥有 **ReadItem** 权限，才能调用阅读模式中的 `getCallbackTokenAsync` 方法。</span><span class="sxs-lookup"><span data-stu-id="280d2-520">Your app must have the **ReadItem** permission specified in its manifest to call the `getCallbackTokenAsync` method in read mode.</span></span>

<span data-ttu-id="280d2-p139">在撰写模式中，必须调用 [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) 方法来获取传递给 `getCallbackTokenAsync` 方法的项目标识符。应用必须具有调用 `saveAsync` 方法的 **ReadWriteItem** 权限。</span><span class="sxs-lookup"><span data-stu-id="280d2-p139">In compose mode you must call the [`saveAsync`](Office.context.mailbox.item.md#saveasyncoptions-callback) method to get an item identifier to pass to the `getCallbackTokenAsync` method. Your app must have **ReadWriteItem** permissions to call the `saveAsync` method.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-523">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-523">Parameters:</span></span>

|<span data-ttu-id="280d2-524">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-524">Name</span></span>| <span data-ttu-id="280d2-525">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-525">Type</span></span>| <span data-ttu-id="280d2-526">属性</span><span class="sxs-lookup"><span data-stu-id="280d2-526">Attributes</span></span>| <span data-ttu-id="280d2-527">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-527">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="280d2-528">函数</span><span class="sxs-lookup"><span data-stu-id="280d2-528">function</span></span>||<span data-ttu-id="280d2-p140">方法完成后，使用单个参数 `callback`（一个 [`asyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `AsyncResult` 参数中传递的函数。令牌作为 `asyncResult.value` 属性中的字符串提供。</span><span class="sxs-lookup"><span data-stu-id="280d2-p140">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object. The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="280d2-531">对象</span><span class="sxs-lookup"><span data-stu-id="280d2-531">Object</span></span>| <span data-ttu-id="280d2-532">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-532">&lt;optional&gt;</span></span>|<span data-ttu-id="280d2-533">传递给异步方法的任何状态数据。</span><span class="sxs-lookup"><span data-stu-id="280d2-533">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-534">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-534">Requirements</span></span>

|<span data-ttu-id="280d2-535">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-535">Requirement</span></span>| <span data-ttu-id="280d2-536">值</span><span class="sxs-lookup"><span data-stu-id="280d2-536">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-537">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-537">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-538">1.3</span><span class="sxs-lookup"><span data-stu-id="280d2-538">1.3</span></span>|
|[<span data-ttu-id="280d2-539">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-539">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-540">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-540">ReadItem</span></span>|
|[<span data-ttu-id="280d2-541">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-541">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-542">撰写和阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-542">Compose and read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-543">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-543">Example</span></span>

```js
function getCallbackToken() {
  Office.context.mailbox.getCallbackTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="getuseridentitytokenasynccallback-usercontext"></a><span data-ttu-id="280d2-544">getUserIdentityTokenAsync(callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="280d2-544">getUserIdentityTokenAsync(callback, [userContext])</span></span>

<span data-ttu-id="280d2-545">获取用于标识用户和 Office 外接程序的令牌。</span><span class="sxs-lookup"><span data-stu-id="280d2-545">Gets a token identifying the user and the Office Add-in.</span></span>

<span data-ttu-id="280d2-546">`getUserIdentityTokenAsync` 方法返回你可以用于在第三方系统上识别和 [验证外接程序和用户的令牌](https://docs.microsoft.com/outlook/add-ins/authentication)。</span><span class="sxs-lookup"><span data-stu-id="280d2-546">The `getUserIdentityTokenAsync` method returns a token that you can use to identify and [authenticate the add-in and user with a third-party system](https://docs.microsoft.com/outlook/add-ins/authentication).</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-547">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-547">Parameters:</span></span>

|<span data-ttu-id="280d2-548">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-548">Name</span></span>| <span data-ttu-id="280d2-549">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-549">Type</span></span>| <span data-ttu-id="280d2-550">属性</span><span class="sxs-lookup"><span data-stu-id="280d2-550">Attributes</span></span>| <span data-ttu-id="280d2-551">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-551">Description</span></span>|
|---|---|---|---|
|`callback`| <span data-ttu-id="280d2-552">函数</span><span class="sxs-lookup"><span data-stu-id="280d2-552">function</span></span>||<span data-ttu-id="280d2-553">方法完成后，使用单个参数 `asyncResult`（一个 [`AsyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `callback` 参数中传递的函数。</span><span class="sxs-lookup"><span data-stu-id="280d2-553">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="280d2-554">令牌作为 `asyncResult.value` 属性中的字符串提供。</span><span class="sxs-lookup"><span data-stu-id="280d2-554">The token is provided as a string in the `asyncResult.value` property.</span></span>|
|`userContext`| <span data-ttu-id="280d2-555">对象</span><span class="sxs-lookup"><span data-stu-id="280d2-555">Object</span></span>| <span data-ttu-id="280d2-556">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-556">&lt;optional&gt;</span></span>|<span data-ttu-id="280d2-557">传递给异步方法的任何状态数据。</span><span class="sxs-lookup"><span data-stu-id="280d2-557">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-558">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-558">Requirements</span></span>

|<span data-ttu-id="280d2-559">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-559">Requirement</span></span>| <span data-ttu-id="280d2-560">值</span><span class="sxs-lookup"><span data-stu-id="280d2-560">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-561">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-561">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-562">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-562">1.0</span></span>|
|[<span data-ttu-id="280d2-563">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-563">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-564">ReadItem</span><span class="sxs-lookup"><span data-stu-id="280d2-564">ReadItem</span></span>|
|[<span data-ttu-id="280d2-565">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-565">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-566">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-566">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-567">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-567">Example</span></span>

```js
function getIdentityToken() {
  Office.context.mailbox.getUserIdentityTokenAsync(cb);
}

function cb(asyncResult) {
  var token = asyncResult.value;
}
```

####  <a name="makeewsrequestasyncdata-callback-usercontext"></a><span data-ttu-id="280d2-568">makeEwsRequestAsync(data, callback, [userContext])</span><span class="sxs-lookup"><span data-stu-id="280d2-568">makeEwsRequestAsync(data, callback, [userContext])</span></span>

<span data-ttu-id="280d2-569">向托管用户邮箱的 Exchange 服务器上的 Exchange Web 服务 (EWS) 发出异步请求。</span><span class="sxs-lookup"><span data-stu-id="280d2-569">Makes an asynchronous request to an Exchange Web Services (EWS) service on the Exchange server that hosts the user’s mailbox.</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-570">在以下方案中不支持此方法。</span><span class="sxs-lookup"><span data-stu-id="280d2-570">This method is not supported in the following scenarios.</span></span>
> - <span data-ttu-id="280d2-571">在适用于 iOS 的 Outlook 或 Outlook for Android</span><span class="sxs-lookup"><span data-stu-id="280d2-571">In Outlook for iOS or Outlook for Android</span></span>
> - <span data-ttu-id="280d2-572">外接程序加载时在 Gmail 邮箱</span><span class="sxs-lookup"><span data-stu-id="280d2-572">When the add-in is loaded in a Gmail mailbox</span></span>
> 
> <span data-ttu-id="280d2-573">在这些情况下外, 接程序应[使用 REST Api](https://docs.microsoft.com/outlook/add-ins/use-rest-api)访问用户的邮箱，而是。</span><span class="sxs-lookup"><span data-stu-id="280d2-573">In these cases, add-ins should [use REST APIs](https://docs.microsoft.com/outlook/add-ins/use-rest-api) to access the user's mailbox instead.</span></span>

<span data-ttu-id="280d2-574">`makeEwsRequestAsync` 方法代表外接程序将 EWS 请求发送到 Exchange。</span><span class="sxs-lookup"><span data-stu-id="280d2-574">The `makeEwsRequestAsync` method sends an EWS request on behalf of the add-in to Exchange.</span></span> <span data-ttu-id="280d2-575">有关支持的 EWS 操作的列表，请参阅[调用 web 服务从 Outlook 外接程序](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support)。</span><span class="sxs-lookup"><span data-stu-id="280d2-575">See [Call web services from an Outlook add-in](https://docs.microsoft.com/outlook/add-ins/web-services#ews-operations-that-add-ins-support) for a list of the supported EWS operations.</span></span>

<span data-ttu-id="280d2-576">你不能使用 `makeEwsRequestAsync` 方法请求与文件夹关联的项目。</span><span class="sxs-lookup"><span data-stu-id="280d2-576">You cannot request Folder Associated Items with the `makeEwsRequestAsync` method.</span></span>

<span data-ttu-id="280d2-577">XML 请求必须指定 UTF-8 编码。</span><span class="sxs-lookup"><span data-stu-id="280d2-577">The XML request must specify UTF-8 encoding.</span></span>

```
<?xml version="1.0" encoding="utf-8"?>
```

<span data-ttu-id="280d2-p142">外接程序必须具有 **ReadWriteMailbox** 权限才能使用 `makeEwsRequestAsync` 方法。有关使用 **ReadWriteMailbox** 权限和可使用 `makeEwsRequestAsync` 方法调用 EWS 操作的信息，请参阅[指定访问用户邮箱的邮件外接程序的权限](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)。</span><span class="sxs-lookup"><span data-stu-id="280d2-p142">Your add-in must have the **ReadWriteMailbox** permission to use the `makeEwsRequestAsync` method. For information about using the **ReadWriteMailbox** permission and the EWS operations that you can call with the `makeEwsRequestAsync` method, see [Specify permissions for mail add-in access to the user's mailbox](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions).</span></span>

> [!NOTE]
> <span data-ttu-id="280d2-580">服务器管理员必须设置`OAuthAuthentication`为 true 时，要启用的客户端访问服务器 EWS 目录上`makeEwsRequestAsync`方法来发出 EWS 请求。</span><span class="sxs-lookup"><span data-stu-id="280d2-580">The server administrator must set `OAuthAuthentication` to true on the Client Access Server EWS directory to enable the `makeEwsRequestAsync` method to make EWS requests.</span></span>

##### <a name="version-differences"></a><span data-ttu-id="280d2-581">版本差异</span><span class="sxs-lookup"><span data-stu-id="280d2-581">Version differences</span></span>

<span data-ttu-id="280d2-582">当你在较 15.0.4535.1004 版本更早的 Outlook 版本中运行的邮件应用程序中使用 `makeEwsRequestAsync` 方法，应当将编码值设置为 `ISO-8859-1`。</span><span class="sxs-lookup"><span data-stu-id="280d2-582">When you use the `makeEwsRequestAsync` method in mail apps running in Outlook versions earlier than version 15.0.4535.1004, you should set the encoding value to `ISO-8859-1`.</span></span>

```
<?xml version="1.0" encoding="iso-8859-1"?>
```

<span data-ttu-id="280d2-p143">当邮件应用程序运行在 Outlook 网页版中时，您不需要设置编码值。可以通过使用 mailbox.diagnostics.hostName 属性来确定您的邮件应用程序在 Outlook 中还是 Outlook 网页版中运行。可以通过使用 mailbox.diagnostics.hostVersion 属性来确定正在运行的是 Outlook 的哪个版本。</span><span class="sxs-lookup"><span data-stu-id="280d2-p143">You do not need to set the encoding value when your mail app is running in Outlook on the web. You can determine whether your mail app is running in Outlook or Outlook on the web by using the mailbox.diagnostics.hostName property. You can determine what version of Outlook is running by using the mailbox.diagnostics.hostVersion property.</span></span>

##### <a name="parameters"></a><span data-ttu-id="280d2-586">参数：</span><span class="sxs-lookup"><span data-stu-id="280d2-586">Parameters:</span></span>

|<span data-ttu-id="280d2-587">名称</span><span class="sxs-lookup"><span data-stu-id="280d2-587">Name</span></span>| <span data-ttu-id="280d2-588">类型</span><span class="sxs-lookup"><span data-stu-id="280d2-588">Type</span></span>| <span data-ttu-id="280d2-589">属性</span><span class="sxs-lookup"><span data-stu-id="280d2-589">Attributes</span></span>| <span data-ttu-id="280d2-590">说明</span><span class="sxs-lookup"><span data-stu-id="280d2-590">Description</span></span>|
|---|---|---|---|
|`data`| <span data-ttu-id="280d2-591">字符串</span><span class="sxs-lookup"><span data-stu-id="280d2-591">String</span></span>||<span data-ttu-id="280d2-592">EWS 请求。</span><span class="sxs-lookup"><span data-stu-id="280d2-592">The EWS request.</span></span>|
|`callback`| <span data-ttu-id="280d2-593">函数</span><span class="sxs-lookup"><span data-stu-id="280d2-593">function</span></span>||<span data-ttu-id="280d2-594">方法完成后，使用单个参数 `callback`（一个 [`asyncResult`](/javascript/api/office/office.asyncresult) 对象）调用在 `AsyncResult` 参数中传递的函数。</span><span class="sxs-lookup"><span data-stu-id="280d2-594">When the method completes, the function passed in the `callback` parameter is called with a single parameter, `asyncResult`, which is an [`AsyncResult`](/javascript/api/office/office.asyncresult) object.</span></span><br/><br/><span data-ttu-id="280d2-595">EWS 调用的 XML 结果作为 `asyncResult.value` 属性中的字符串提供。</span><span class="sxs-lookup"><span data-stu-id="280d2-595">The XML result of the EWS call is provided as a string in the `asyncResult.value` property.</span></span> <span data-ttu-id="280d2-596">如果结果的大小超过 1 MB，而被返回一条错误消息。</span><span class="sxs-lookup"><span data-stu-id="280d2-596">If the result exceeds 1 MB in size, an error message is returned instead.</span></span>|
|`userContext`| <span data-ttu-id="280d2-597">对象</span><span class="sxs-lookup"><span data-stu-id="280d2-597">Object</span></span>| <span data-ttu-id="280d2-598">&lt;可选&gt;</span><span class="sxs-lookup"><span data-stu-id="280d2-598">&lt;optional&gt;</span></span>|<span data-ttu-id="280d2-599">传递给异步方法的任何状态数据。</span><span class="sxs-lookup"><span data-stu-id="280d2-599">Any state data that is passed to the asynchronous method.</span></span>|

##### <a name="requirements"></a><span data-ttu-id="280d2-600">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-600">Requirements</span></span>

|<span data-ttu-id="280d2-601">要求</span><span class="sxs-lookup"><span data-stu-id="280d2-601">Requirement</span></span>| <span data-ttu-id="280d2-602">值</span><span class="sxs-lookup"><span data-stu-id="280d2-602">Value</span></span>|
|---|---|
|[<span data-ttu-id="280d2-603">最低版本的邮箱要求集</span><span class="sxs-lookup"><span data-stu-id="280d2-603">Minimum mailbox requirement set version</span></span>](/javascript/office/requirement-sets/outlook-api-requirement-sets)| <span data-ttu-id="280d2-604">1.0</span><span class="sxs-lookup"><span data-stu-id="280d2-604">1.0</span></span>|
|[<span data-ttu-id="280d2-605">最低权限级别</span><span class="sxs-lookup"><span data-stu-id="280d2-605">Minimum permission level</span></span>](https://docs.microsoft.com/outlook/add-ins/understanding-outlook-add-in-permissions)| <span data-ttu-id="280d2-606">ReadWriteMailbox</span><span class="sxs-lookup"><span data-stu-id="280d2-606">ReadWriteMailbox</span></span>|
|[<span data-ttu-id="280d2-607">适用的 Outlook 模式</span><span class="sxs-lookup"><span data-stu-id="280d2-607">Applicable Outlook mode</span></span>](https://docs.microsoft.com/outlook/add-ins/#extension-points)| <span data-ttu-id="280d2-608">撰写或阅读</span><span class="sxs-lookup"><span data-stu-id="280d2-608">Compose or read</span></span>|

##### <a name="example"></a><span data-ttu-id="280d2-609">示例</span><span class="sxs-lookup"><span data-stu-id="280d2-609">Example</span></span>

<span data-ttu-id="280d2-610">下面的示例调用 `makeEwsRequestAsync` 以使用 `GetItem` 操作来获取项目的主题。</span><span class="sxs-lookup"><span data-stu-id="280d2-610">The following example calls `makeEwsRequestAsync` to use the `GetItem` operation to get the subject of an item.</span></span>

```js
function getSubjectRequest(id) {
   // Return a GetItem operation request for the subject of the specified item.
   var request =
    '<?xml version="1.0" encoding="utf-8"?>' +
    '<soap:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"' +
    '               xmlns:xsd="http://www.w3.org/2001/XMLSchema"' +
    '               xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/"' +
    '               xmlns:t="http://schemas.microsoft.com/exchange/services/2006/types">' +
    '  <soap:Header>' +
    '    <RequestServerVersion Version="Exchange2013" xmlns="http://schemas.microsoft.com/exchange/services/2006/types" soap:mustUnderstand="0" />' +
    '  </soap:Header>' +
    '  <soap:Body>' +
    '    <GetItem xmlns="http://schemas.microsoft.com/exchange/services/2006/messages">' +
    '      <ItemShape>' +
    '        <t:BaseShape>IdOnly</t:BaseShape>' +
    '        <t:AdditionalProperties>' +
    '            <t:FieldURI FieldURI="item:Subject"/>' +
    '        </t:AdditionalProperties>' +
    '      </ItemShape>' +
    '      <ItemIds><t:ItemId Id="' + id + '"/></ItemIds>' +
    '    </GetItem>' +
    '  </soap:Body>' +
    '</soap:Envelope>';

   return request;
}

function sendRequest() {
   // Create a local variable that contains the mailbox.
   Office.context.mailbox.makeEwsRequestAsync(
    getSubjectRequest(mailbox.item.itemId), callback);
}

function callback(asyncResult)  {
   var result = asyncResult.value;
   var context = asyncResult.asyncContext;

   // Process the returned response here.
}
```