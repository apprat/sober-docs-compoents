# Tab

<section>
  <s-tab>
    <s-tab-item>
      <div slot="text">Item 1</div>
      <s-badge slot="badge"></s-badge>
    </s-tab-item>
    <s-tab-item checked="true">
      <div slot="text">Item 2</div>
      <s-badge slot="badge">2</s-badge>
    </s-tab-item>
    <s-tab-item>
      <div slot="text">Item 3</div>
    </s-tab-item>
    <s-tab-item>
      <div slot="text">Item 5</div>
    </s-tab-item>
    <s-tab-item>
      <div slot="text">Item 6</div>
    </s-tab-item>
    <s-tab-item>
      <div slot="text">Item 7</div>
    </s-tab-item>
  </s-tab>
</section>

```html
<s-tab>
  <s-tab-item>
    <div slot="text">Item 1</div>
    <s-badge slot="badge"></s-badge>
  </s-tab-item>
  <s-tab-item checked="true">
    <div slot="text">Item 2</div>
    <s-badge slot="badge">2</s-badge>
  </s-tab-item>
  <s-tab-item>
    <div slot="text">Item 3</div>
  </s-tab-item>
  <s-tab-item>
    <div slot="text">Item 5</div>
  </s-tab-item>
  <s-tab-item>
    <div slot="text">Item 6</div>
  </s-tab-item>
  <s-tab-item>
    <div slot="text">Item 7</div>
  </s-tab-item>
</s-tab>
</s-tab>
```

使用 `fixed` 模式，在这个模式下 item 会均分占据 `tab` 宽度，并且不再支持滚动。

<section>
  <s-tab mode="fixed">
    <s-tab-item>
      <div slot="text">Item 1</div>
      <s-badge slot="badge"></s-badge>
    </s-tab-item>
    <s-tab-item checked="true">
      <div slot="text">Item 2</div>
      <s-badge slot="badge">2</s-badge>
    </s-tab-item>
    <s-tab-item>
      <div slot="text">Item 3</div>
    </s-tab-item>
    <s-tab-item>
      <div slot="text">Item 4</div>
    </s-tab-item>
  </s-tab>
</section>

```html
<s-tab mode="fixed">
  <s-tab-item>
    <div slot="text">Item 1</div>
    <s-badge slot="badge"></s-badge>
  </s-tab-item>
  <s-tab-item checked="true">
    <div slot="text">Item 2</div>
    <s-badge slot="badge">2</s-badge>
  </s-tab-item>
  <s-tab-item>
    <div slot="text">Item 3</div>
  </s-tab-item>
  <s-tab-item>
    <div slot="text">Item 4</div>
  </s-tab-item>
</s-tab>
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


# Tab Item

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