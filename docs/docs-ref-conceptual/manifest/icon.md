# <a name="icon-element"></a>Icon 元素

定义“[按钮](control.md#button-control)”或“[菜单](control.md#menu-dropdown-button-controls)”控件的 **Image** 元素。

## <a name="attributes"></a>属性

|  属性  |  必需  |  说明  |
|:-----|:-----|:-----|
|  **xsi:type**  |  否  | 正在定义的图标类型。这仅适用于移动外形规格中的图标。[MobileFormFactor](mobileformfactor.md) 元素中所包含的 **Icon** 元素必须将此属性设置为 `bt:MobileIconList`。 |

## <a name="child-elements"></a>子元素

|  元素 |  必需  |  说明  |
|:-----|:-----|:-----|
|  [图像](#image)        | 是 |   要使用的图像的 resid         |

### <a name="image"></a>图像

按钮的图像。**resid** 属性必须设置为 **Images** 元素（位于 **Resources** 元素）中 **Image** 元素的 [id](resources.md) 属性的值。**size** 属性指示图像的大小，以像素为单位。有三个图像大小是必需的（16、32 和 80 像素），此外还支持五个其他大小（20、24、40、48 和 64 像素）。|

```xml
<Icon>
  <bt:Image size="16" resid="blue-icon-16" />
  <bt:Image size="32" resid="blue-icon-32" />
  <bt:Image size="80" resid="blue-icon-80" />
</Icon>
```

## <a name="additional-requirements-for-mobile-form-factors"></a>移动外形规格的其他要求

当父 **Icon** 元素是 [MobileFormFactor](mobileformfactor.md) 元素的后代时，所要求的最小大小会略有不同。清单必须至少提供 25、32 和 48 像素大小。所提供的每个大小必须出现三次，并将 `scale` 属性设置为 `1`、`2` 或 `3`。

```xml
<Icon xsi:type="bt:MobileIconList">
  <bt:Image resid="blue-icon-16-1" size="25" scale="1" />
  <bt:Image resid="blue-icon-16-2" size="25" scale="2" />
  <bt:Image resid="blue-icon-16-3" size="25" scale="3" />
  <bt:Image resid="blue-icon-32-1" size="32" scale="1" />
  <bt:Image resid="blue-icon-32-2" size="32" scale="2" />
  <bt:Image resid="blue-icon-32-3" size="32" scale="3" />
  <bt:Image resid="blue-icon-80-1" size="48" scale="1" />
  <bt:Image resid="blue-icon-80-2" size="48" scale="2" />
  <bt:Image resid="blue-icon-80-3" size="48" scale="3" />
</Icon>
```