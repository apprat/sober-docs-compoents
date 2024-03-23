# Button

基础按钮，如果你只需要一个拥有触摸反馈的容器，那么 [ripple](/component/ripple) 组件可能更适合你

<section>
  <s-button> button </s-button>
  <s-button disabled="true"> button </s-button>
</section>

```html
<s-button> button </s-button>
<s-button disabled="true"> button </s-button>
```

设置不同样式的按钮

<section>
  <s-button type="elevated"> button </s-button>
  <s-button type="filled-tonal"> button </s-button>
  <s-button type="outlined"> button </s-button>
  <s-button type="text"> button </s-button>
</section>

```html
<s-button type="elevated"> button </s-button>
<s-button type="filled-tonal"> button </s-button>
<s-button type="outlined"> button </s-button>
<s-button type="text"> button </s-button>
```

使用插槽

<section>
  <s-button>
    <s-icon type="search" slot="start"></s-icon>
    button
  </s-button>
  <s-button>
    <s-circular-progress indeterminate="true" slot="start"></s-circular-progress>
    loading
  </s-button>
</section>

```html
<s-button>
  <s-icon type="search" slot="start"></s-icon>
  button
</s-button>
<s-button>
  <s-circular-progress indeterminate="true" slot="start"></s-circular-progress>
  loading
</s-button>
```

自定义样式覆盖

<section>
  <s-button style="background: #009688; color: #fff; height: 32px; padding: 0 16px; border-radius: 4px"> button </s-button>
</section>

```html
<s-button style="background: #009688; color: #fff; height: 32px; padding: 0 16px; border-radius: 4px"> button </s-button>
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
      <s-td>filled, elevated, filled-tonal, outlined, text</s-td>
      <s-td>filled</s-td>
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
      <s-td>开始</s-td>
    </s-tr>
    <s-tr>
      <s-td>end</s-td>
      <s-td>结束</s-td>
    </s-tr>
  </s-tbody>
</s-table>