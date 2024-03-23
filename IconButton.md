# Icon Button
图标按钮始终为圆形

<section>
  <s-icon-button>
    <s-icon type="search"></s-icon>
  </s-icon-button>
  <s-icon-button type="filled">
    <s-icon type="search"></s-icon>
  </s-icon-button>
  <s-icon-button type="filled-tonal">
    <s-icon type="search"></s-icon>
  </s-icon-button>
  <s-icon-button type="outlined">
    <s-icon type="search"></s-icon>
  </s-icon-button>
</section>

```html
<s-icon-button>
  <s-icon type="search"></s-icon>
</s-icon-button>
<s-icon-button type="filled">
  <s-icon type="search"></s-icon>
</s-icon-button>
<s-icon-button type="filled-tonal">
  <s-icon type="search"></s-icon>
</s-icon-button>
<s-icon-button type="outlined">
  <s-icon type="search"></s-icon>
</s-icon-button>
```

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
      <s-td>type</s-td>
      <s-td>按钮样式</s-td>
      <s-td>text, filled, filled-tonal, outlined</s-td>
      <s-td>text</s-td>
      <s-td>是</s-td>
    </s-tr>
    <s-tr>
      <s-td>disabled</s-td>
      <s-td>是否禁用</s-td>
      <s-td>boolean</s-td>
      <s-td>false</s-td>
      <s-td>是</s-td>
    </s-tr>
  </s-tbody>
</s-table>