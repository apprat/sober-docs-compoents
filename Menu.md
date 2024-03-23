# Menu

大多数情况下你无需关心菜单出现的位置，它会自动找寻合适的位置停靠。   
如果你希望菜单出现在指定位置，你可以尝试调用 `show()` 方法

<section>
  <s-menu>
    <s-button slot="trigger">菜单</s-button>
    <s-menu-item>选项1</s-menu-item>
    <s-menu-item>选项2</s-menu-item>
    <s-menu-item>选项3</s-menu-item>
    <s-menu-item>选项4</s-menu-item>
    <s-menu-item>选项5</s-menu-item>
  </s-menu>
</section>

```html
<s-menu>
  <s-button slot="trigger">菜单</s-button>
  <s-menu-item>选项1</s-menu-item>
  <s-menu-item>选项2</s-menu-item>
  <s-menu-item>选项3</s-menu-item>
  <s-menu-item>选项4</s-menu-item>
  <s-menu-item>选项5</s-menu-item>
</s-menu>
```

子菜单

<section>
  <s-menu>
    <s-button slot="trigger">菜单</s-button>
    <s-menu-item>选项1</s-menu-item>
    <s-menu-item>选项2</s-menu-item>
    <s-menu-item>选项3</s-menu-item>
    <s-menu>
      <s-menu-item slot="trigger">
        子菜单
        <s-icon slot="end" type="arrow_drop_right"></s-icon>
      </s-menu-item>
      <s-menu-item>选项1</s-menu-item>
      <s-menu-item>选项2</s-menu-item>
      <s-menu-item>选项3</s-menu-item>
      <s-menu-item>选项4</s-menu-item>
      <s-menu-item>选项5</s-menu-item>
    </s-menu>
    <s-menu-item>选项5</s-menu-item>
  </s-menu>
</section>

```html
<s-menu>
  <s-button slot="trigger">菜单</s-button>
  <s-menu-item>选项1</s-menu-item>
  <s-menu-item>选项2</s-menu-item>
  <s-menu-item>选项3</s-menu-item>
  <s-menu>
    <s-menu-item slot="trigger">
      子菜单
      <s-icon slot="end" type="arrow_drop_right"></s-icon>
    </s-menu-item>
    <s-menu-item>选项1</s-menu-item>
    <s-menu-item>选项2</s-menu-item>
    <s-menu-item>选项3</s-menu-item>
    <s-menu-item>选项4</s-menu-item>
    <s-menu-item>选项5</s-menu-item>
  </s-menu>
  <s-menu-item>选项5</s-menu-item>
</s-menu>
```

# Menu Item

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