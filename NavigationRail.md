# Navigation Rail

<section>
  <s-navigation-rail>
    <s-icon-button slot="menu">
      <s-icon type="add"></s-icon>
    </s-icon-button>
    <s-navigation-rail-item checked="true">
      <s-icon type="add" slot="icon"></s-icon>
      <div slot="text">Item 1</div>
      <s-badge slot="badge">2</s-badge>
    </s-navigation-rail-item>
    <s-navigation-rail-item>
      <s-icon type="search" slot="icon"></s-icon>
      <div slot="text">Item 2</div>
    </s-navigation-rail-item>
    <s-navigation-rail-item>
      <s-icon type="dark_mode" slot="icon"></s-icon>
      <div slot="text">Item 3</div>
    </s-navigation-rail-item>
    <s-navigation-rail-item>
      <s-icon type="light_mode" slot="icon"></s-icon>
      <div slot="text">Item 4</div>
    </s-navigation-rail-item>
  </s-navigation-rail>
</section>

```html
<s-navigation-rail>
  <s-icon-button slot="menu">
    <s-icon type="add"></s-icon>
  </s-icon-button>
  <s-navigation-rail-item checked="true">
    <s-icon type="add" slot="icon"></s-icon>
    <div slot="text">Item 1</div>
    <s-badge slot="badge">2</s-badge>
  </s-navigation-rail-item>
  <s-navigation-rail-item>
    <s-icon type="search" slot="icon"></s-icon>
    <div slot="text">Item 2</div>
  </s-navigation-rail-item>
  <s-navigation-rail-item>
    <s-icon type="dark_mode" slot="icon"></s-icon>
    <div slot="text">Item 3</div>
  </s-navigation-rail-item>
  <s-navigation-rail-item>
    <s-icon type="light_mode" slot="icon"></s-icon>
    <div slot="text">Item 4</div>
  </s-navigation-rail-item>
</s-navigation-rail>
```

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
      <s-td>options<span class="tag">只读</span></s-td>
      <s-td>子项目</s-td>
      <s-td>Item[]</s-td>
      <s-td>[]</s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>selectIndex<span class="tag">只读</span></s-td>
      <s-td>当前选中下标</s-td>
      <s-td>number</s-td>
      <s-td>-1</s-td>
      <s-td>否</s-td>
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
      <s-td>menu</s-td>
      <s-td>菜单</s-td>
    </s-tr>
    <s-tr>
      <s-td>end</s-td>
      <s-td>结束</s-td>
    </s-tr>
  </s-tbody>
</s-table>

# Navigation Rail Item

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
      <s-td>checked</s-td>
      <s-td>是否选中</s-td>
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
      <s-td>icon</s-td>
      <s-td>图标</s-td>
    </s-tr>
    <s-tr>
      <s-td>text</s-td>
      <s-td>文本</s-td>
    </s-tr>
    <s-tr>
      <s-td>badge</s-td>
      <s-td>徽章</s-td>
    </s-tr>
  </s-tbody>
</s-table>