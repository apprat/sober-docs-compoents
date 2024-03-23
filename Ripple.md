# Ripple
波纹是一个容器，它本身没有任何样式，且大多数组件都依赖了它
<section>
 <s-ripple style="padding: 24px">
    test
 </s-ripple>
</section>

```html
<s-ripple style="padding: 24px">
  test
</s-ripple>
```

波纹的颜色继承自 `color` 的值，并带有一定的不透明度，如果你希望自定义波纹颜色而不修改文本颜色，可考虑使用 CSS 变量进行设置

<section>
 <s-ripple style="padding: 24px; color: #009688">
    test
 </s-ripple>
  <s-ripple style="padding: 24px; --ripple-color: #336699">
    test2
 </s-ripple>
</section>

```html
<s-ripple style="padding: 24px; color: #009688">
  test
</s-ripple>
<s-ripple style="padding: 24px; --ripple-color: #336699">
  test2
</s-ripple>
```

#### 依附模式

它依附在容器中呈现，这时事件从容器上触发，某些情况下可能有妙用。

<section>
  <div style="padding: 24px; position: relative">
    my ripple
    <s-ripple attached="true"></s-ripple>
  </div>
</section>

```html
<div style="padding: 24px; position: relative">
  my ripple
  <s-ripple attached="true"></s-ripple>
</div>
```

由于 `ripple` 使用定位确定位置，所以容器的 `position` 必须设置为 `relative`、`absolute`、`sticky`、`fixed` 其中之一。

## 属性
<s-table>
  <s-thead>
    <s-tr>
      <s-th>名称</s-th>
      <s-th>介绍</s-th>
      <s-th class="min-content">类型</s-th>
      <s-th class="min-content">默认值</s-th>
      <s-th class="min-content">同步</s-th>
    </s-tr>
  </s-thead>
  <s-tbody>
    <s-tr>
      <s-td>centered</s-td>
      <s-td>波纹是否居中</s-td>
      <s-td>boolean</s-td>
      <s-td>false</s-td>
      <s-td>是</s-td>
    </s-tr>
    <s-tr>
      <s-td>attached</s-td>
      <s-td>是否设置为依附模式</s-td>
      <s-td>boolean</s-td>
      <s-td>false</s-td>
      <s-td>是</s-td>
    </s-tr>
  </s-tbody>
</s-table>

## CSS 变量
<s-table>
  <s-thead>
    <s-tr>
      <s-th>名称</s-th>
      <s-th>介绍</s-th>
      <s-th class="min-content">默认值</s-th>
    </s-tr>
  </s-thead>
  <s-tbody>
    <s-tr>
      <s-td>--ripple-color</s-td>
      <s-td>波纹颜色</s-td>
      <s-td>currentColor</s-td>
    </s-tr>
    <s-tr>
      <s-td>--ripple-opacity</s-td>
      <s-td>波纹颜色不透明度</s-td>
      <s-td>0.24</s-td>
    </s-tr>
  </s-tbody>
</s-table>