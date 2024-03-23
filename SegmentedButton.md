# Segmented Button

<section>
  <s-segmented-button>
    <s-segmented-button-item>
      <s-icon slot="start" type="done"></s-icon>
      Home
    </s-segmented-button-item>
    <s-segmented-button-item checked="true">
      Finds
    </s-segmented-button-item>
    <s-segmented-button-item>
      Posts
    </s-segmented-button-item>
    <s-segmented-button-item>
      <s-icon slot="start" type="search"></s-icon>
      Users
    </s-segmented-button-item>
  </s-segmented-button>
</section>

```html
<s-segmented-button>
  <s-segmented-button-item>
    <s-icon slot="start" type="done"></s-icon>
    Home
  </s-segmented-button-item>
  <s-segmented-button-item checked="true">
    Finds
  </s-segmented-button-item>
  <s-segmented-button-item>
    Posts
  </s-segmented-button-item>
  <s-segmented-button-item>
    <s-icon slot="start" type="search"></s-icon>
    Users
  </s-segmented-button-item>
</s-segmented-button>
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
      <s-td>mode</s-td>
      <s-td>模式</s-td>
      <s-td>scrollable, fixed</s-td>
      <s-td>scrollable</s-td>
      <s-td>是</s-td>
    </s-tr>
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

# Segmented Button Item

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
  </s-tbody>
</s-table>