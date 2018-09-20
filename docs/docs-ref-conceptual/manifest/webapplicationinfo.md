# <a name="webapplicationinfo-element"></a><span data-ttu-id="2d3b4-101">WebApplicationInfo 元素</span><span class="sxs-lookup"><span data-stu-id="2d3b4-101">WebApplicationInfo element</span></span>

<span data-ttu-id="2d3b4-102">支持 Office 外接程序中的单一登录 (SSO)。此元素包含外接程序中的信息，如下所示：</span><span class="sxs-lookup"><span data-stu-id="2d3b4-102">Supports single sign-on (SSO) in Office Add-ins. This element contains information for the add-in as both:</span></span>

- <span data-ttu-id="2d3b4-103">OAuth 2.0 *资源*，Office 主机应用程序可能需要访问该资源的权限。</span><span class="sxs-lookup"><span data-stu-id="2d3b4-103">An OAuth 2.0 *resource* to which the Office host application might need permissions.</span></span>
- <span data-ttu-id="2d3b4-104">OAuth 2.0 *客户端*，可能需要访问 Microsoft Graph 的权限。</span><span class="sxs-lookup"><span data-stu-id="2d3b4-104">An OAuth 2.0 *client* that might need permissions to Microsoft Graph.</span></span>

<span data-ttu-id="2d3b4-105">**WebApplicationInfo** 是清单中的 [VersionOverrides](versionoverrides.md) 元素的子元素。</span><span class="sxs-lookup"><span data-stu-id="2d3b4-105">**WebApplicationInfo** is a child element of the [VersionOverrides](versionoverrides.md) element in the manifest.</span></span>  

## <a name="child-elements"></a><span data-ttu-id="2d3b4-106">子元素</span><span class="sxs-lookup"><span data-stu-id="2d3b4-106">Child elements</span></span>

|  <span data-ttu-id="2d3b4-107">元素</span><span class="sxs-lookup"><span data-stu-id="2d3b4-107">Element</span></span> |  <span data-ttu-id="2d3b4-108">必需</span><span class="sxs-lookup"><span data-stu-id="2d3b4-108">Required</span></span>  |  <span data-ttu-id="2d3b4-109">说明</span><span class="sxs-lookup"><span data-stu-id="2d3b4-109">Description</span></span>  |
|:-----|:-----|:-----|
|  <span data-ttu-id="2d3b4-110">**Id**</span><span class="sxs-lookup"><span data-stu-id="2d3b4-110">**Id**</span></span>    |  <span data-ttu-id="2d3b4-111">是</span><span class="sxs-lookup"><span data-stu-id="2d3b4-111">Yes</span></span>   |  <span data-ttu-id="2d3b4-112">在 Azure Active Directory v2.0 终结点中注册的加载项关联服务的**应用程序 ID**。</span><span class="sxs-lookup"><span data-stu-id="2d3b4-112">The **Application Id** of the add-in's associated service as registered in the Azure Active Directory v 2.0 endpoint.</span></span>|
|  <span data-ttu-id="2d3b4-113">**Resource**</span><span class="sxs-lookup"><span data-stu-id="2d3b4-113">**Resource**</span></span>  |  <span data-ttu-id="2d3b4-114">是</span><span class="sxs-lookup"><span data-stu-id="2d3b4-114">Yes</span></span>   |  <span data-ttu-id="2d3b4-115">指定在 Azure Active Directory v2.0 终结点中注册的加载项的**应用程序 ID URI**。</span><span class="sxs-lookup"><span data-stu-id="2d3b4-115">Specifies the **Application ID URI** of the add-in as registered in the Azure Active Directory v 2.0 endpoint.</span></span>|
|  [<span data-ttu-id="2d3b4-116">Scopes</span><span class="sxs-lookup"><span data-stu-id="2d3b4-116">Scopes</span></span>](scopes.md)                |  <span data-ttu-id="2d3b4-117">否</span><span class="sxs-lookup"><span data-stu-id="2d3b4-117">No</span></span>  |  <span data-ttu-id="2d3b4-118">指定加载项需要拥有的对 Microsoft Graph 的访问权限。</span><span class="sxs-lookup"><span data-stu-id="2d3b4-118">Specifies the permissions that the add-in needs to Microsoft Graph.</span></span>  |

> [!NOTE] 
> <span data-ttu-id="2d3b4-119">目前，必要时外, 接程序的资源相匹配时其主机。</span><span class="sxs-lookup"><span data-stu-id="2d3b4-119">Currently, it's necessary that your add-in's Resource matches its Host.</span></span> <span data-ttu-id="2d3b4-120">Office 不会请求获取加载项令牌，除非可以证明所有权。目前，这是通过在 Resource 的完全限定的域名下托管加载项来完成。</span><span class="sxs-lookup"><span data-stu-id="2d3b4-120">Office will not request a Token for an add-in unless it can prove ownership, and today this is done by hosting the add-in under the Resource's fully-qualified domain name.</span></span>

## <a name="webapplicationinfo-example"></a><span data-ttu-id="2d3b4-121">WebApplicationInfo 示例</span><span class="sxs-lookup"><span data-stu-id="2d3b4-121">WebApplicationInfo example</span></span>

```xml
<OfficeApp>
...
  <VersionOverrides xmlns="http://schemas.microsoft.com/office/mailappversionoverrides" xsi:type="VersionOverridesV1_0">
    ...
    <WebApplicationInfo>
      <Id>12345678-abcd-1234-efab-123456789abc</Id>
      <Resource>api://myDomain.com/12345678-abcd-1234-efab-123456789abc<Resource>
      <Scopes>
        <Scope>Files.Read.All</Scope>
        <Scope>offline_access</Scope>
        <Scope>openid</Scope>
        <Scope>profile</Scope>        
      </Scopes>
    </WebApplicationInfo>
  </VersionOverrides>
...
</OfficeApp>
```