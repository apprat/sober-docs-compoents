# Snackbar

<section>
  <s-snackbar action="关闭">
    <s-button slot="trigger"> Snackbar </s-button>
    Snackbar Message
  </s-snackbar>
</section>

```html
<s-snackbar action="关闭">
  <s-button slot="trigger"> Snackbar </s-button>
  Snackbar Message
</s-snackbar>
```

#### 静态方法调用

## 静态方法

<s-table>
  <s-thead>
    <s-tr>
      <s-th>名称</s-th>
      <s-th class="min-content">介绍</s-th>
      <s-th class="min-content">参数</s-th>
      <s-th class="min-content">返回值</s-th>
    </s-tr>
  </s-thead>
  <s-tbody>
    <s-tr>
      <s-td>show()<span class="tag">只读</span></s-td>
      <s-td>显示提示框</s-td>
      <s-td>string | object</s-td>
      <s-td>void</s-td>
    </s-tr>
  </s-tbody>
</s-table>

> 静态方法挂载在组件对象中，通过 import 引入组件调用。