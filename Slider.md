# Slider
 
<section>
  <s-slider></s-slider>
</section>

```html
<s-slider></s-slider>
```

使用标签文本

<section>
  <s-slider labeled="true"></s-slider>
</section>

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
      <s-td>labeled</s-td>
      <s-td>是否开启文本标签</s-td>
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
    <s-tr>
      <s-td>max</s-td>
      <s-td>最大值</s-td>
      <s-td>number</s-td>
      <s-td>100</s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>min</s-td>
      <s-td>最小值</s-td>
      <s-td>number</s-td>
      <s-td>0</s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>step</s-td>
      <s-td>步进值</s-td>
      <s-td>number</s-td>
      <s-td>1</s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>value</s-td>
      <s-td>当前值</s-td>
      <s-td>number</s-td>
      <s-td>50</s-td>
      <s-td>否</s-td>
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
      <s-td>值变化后触发</s-td>
    </s-tr>
  </s-tbody>
</s-table>