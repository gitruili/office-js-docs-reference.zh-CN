# <a name="sourcelocation-element"></a><span data-ttu-id="1ce52-101">SourceLocation 元素</span><span class="sxs-lookup"><span data-stu-id="1ce52-101">SourceLocation element</span></span>

<span data-ttu-id="1ce52-102">定义 Excel 中自定义函数所使用的 Script 或 Page 元素所需的资源的位置。</span><span class="sxs-lookup"><span data-stu-id="1ce52-102">Defines the location of a resource needed by the Script or Page elements used by custom functions in Excel.</span></span>

## <a name="attributes"></a><span data-ttu-id="1ce52-103">Attributes</span><span class="sxs-lookup"><span data-stu-id="1ce52-103">Attributes</span></span>

| <span data-ttu-id="1ce52-104">**属性**</span><span class="sxs-lookup"><span data-stu-id="1ce52-104">**Attribute**</span></span> | <span data-ttu-id="1ce52-105">**必需**</span><span class="sxs-lookup"><span data-stu-id="1ce52-105">**Required**</span></span> | <span data-ttu-id="1ce52-106">**说明**</span><span class="sxs-lookup"><span data-stu-id="1ce52-106">**Description**</span></span>                                                                      |
|---------------|--------------|--------------------------------------------------------------------------------------|
| <span data-ttu-id="1ce52-107">resid</span><span class="sxs-lookup"><span data-stu-id="1ce52-107">resid</span></span>         | <span data-ttu-id="1ce52-108">是</span><span class="sxs-lookup"><span data-stu-id="1ce52-108">Yes</span></span>          | <span data-ttu-id="1ce52-109">清单的&lt;资源&gt;部分中所定义的 URL 资源的名称。</span><span class="sxs-lookup"><span data-stu-id="1ce52-109">The name of a URL resource defined in the &lt;Resources&gt; section of the manifest.</span></span> |

## <a name="child-elements"></a><span data-ttu-id="1ce52-110">子元素</span><span class="sxs-lookup"><span data-stu-id="1ce52-110">Child elements</span></span>

<span data-ttu-id="1ce52-111">无</span><span class="sxs-lookup"><span data-stu-id="1ce52-111">None</span></span>

## <a name="example"></a><span data-ttu-id="1ce52-112">示例</span><span class="sxs-lookup"><span data-stu-id="1ce52-112">Example</span></span>

```xml
<SourceLocation resid="pageURL"/>
```