# Top App Bar

Top App Bar 的表现更像一个容器，它没有事件和行为。   
在屏幕宽度小于 `840px` 时，它的高度会变为 `56px`。

<section>
  <s-top-app-bar>
    <s-icon-button slot="navigation">
      <s-icon type="menu"></s-icon>
    </s-icon-button>
    <div slot="headline"> Title </div>
    <s-icon-button slot="action">
      <s-icon type="search"></s-icon>
    </s-icon-button>
  </s-top-app-bar>
</section>

```html
<s-top-app-bar>
  <!--左侧菜单按钮-->
  <s-icon-button slot="navigation">
    <s-icon type="menu"></s-icon>
  </s-icon-button>
  <!--标题-->
  <div slot="headline"> Title </div>
  <!--右侧操作按钮-->
  <s-icon-button slot="action">
    <s-icon type="search"></s-icon>
  </s-icon-button>
</s-top-app-bar>
```

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
      <s-td>navigation</s-td>
      <s-td>导航</s-td>
    </s-tr>
    <s-tr>
      <s-td>headline</s-td>
      <s-td>标题</s-td>
    </s-tr>
    <s-tr>
      <s-td>action</s-td>
      <s-td>操作</s-td>
    </s-tr>
  </s-tbody>
</s-table>