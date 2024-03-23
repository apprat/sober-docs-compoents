# Radio Button

单选按钮需要设置一个唯一的 `name` 作为分组才能执行单选。

<section>
  <s-radio-button name="group"></s-radio-button>
  <s-radio-button name="group" checked="true"></s-radio-button>
  <s-radio-button name="group" disabled="true"></s-radio-button>
</section>

```html
<s-radio-button name="group"></s-radio-button>
<s-radio-button name="group" checked="true"></s-radio-button>
<s-radio-button name="group" disabled="true"></s-radio-button>
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
      <s-td>name</s-td>
      <s-td>名称</s-td>
      <s-td>string</s-td>
      <s-td></s-td>
      <s-td>是</s-td>
    </s-tr>
    <s-tr>
      <s-td>checked</s-td>
      <s-td>是否选中</s-td>
      <s-td>boolean</s-td>
      <s-td>false</s-td>
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

## 事件
<s-table>
  <s-thead>
    <s-tr>
      <s-th>名称</s-th>
      <s-th>介绍</s-th>
    </s-tr>
  </s-thead>
  <s-tbody>
    <s-tr>
      <s-td>change</s-td>
      <s-td>选中变化后触发</s-td>
    </s-tr>
  </s-tbody>
</s-table>