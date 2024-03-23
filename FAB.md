# Floating Action Button

<section>
  <s-fab>
    <s-icon type="search"></s-icon>
  </s-fab>
</section>

```html
<s-fab>
  <s-icon type="search"></s-icon>
</s-fab>
```

<section>
  <s-fab extended="true">
    <s-icon type="search" slot="start"></s-icon>
    Floating Action Button
  </s-fab>
</section>

```html
<s-fab extended="true">
  <s-icon type="search" slot="start"></s-icon>
  Floating Action Button
</s-fab>
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
      <s-td>size</s-td>
      <s-td>按钮大小</s-td>
      <s-td>medium, small, large</s-td>
      <s-td>medium</s-td>
      <s-td>是</s-td>
    </s-tr>
    <s-tr>
      <s-td>extended</s-td>
      <s-td>是否为扩展按钮</s-td>
      <s-td>boolean</s-td>
      <s-td>false</s-td>
      <s-td>是</s-td>
    </s-tr>
  </s-tbody>
</s-table>

## 插槽
<s-table>
  <s-thead>
    <s-tr>
      <s-th>名称</s-th>
      <s-th>介绍</s-th>
    </s-tr>
  </s-thead>
  <s-tbody>
    <s-tr>
      <s-td>start</s-td>
      <s-td>开始插槽</s-td>
    </s-tr>
    <s-tr>
      <s-td>end</s-td>
      <s-td>结束插槽</s-td>
    </s-tr>
  </s-tbody>
</s-table>