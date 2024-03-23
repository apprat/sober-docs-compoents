# Page

建议作为页面根容器的组件，页面的样式由它控制。所有样式 CSS 变量都挂载在 `page` 中，你可以在[样式](/style)中查阅 CSS 变量值。

<section>
  <s-page style="padding: 24px">
    <s-button> Page </s-button>
  </s-page>
</section>

```html
<s-page style="padding: 24px">
  <s-button> Page </s-button>
</s-page>
```

使用暗色主题

<section>
  <s-page theme="dark" style="padding: 24px">
    <s-button> Page </s-button>
  </s-page>
</section>

```html
<s-page theme="dark" style="padding: 24px">
  <s-button> Page </s-button>
</s-page>
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
      <s-td>theme</s-td>
      <s-td>主题</s-td>
      <s-td>light, dark, auto</s-td>
      <s-td>light</s-td>
      <s-td>是</s-td>
    </s-tr>
  </s-tbody>
</s-table>
