# Drawer

抽屉使用左中右，三个插槽布局。它有两种显示模式，默认为 `static`，在屏幕宽度大于 `840px` 时，自动切换到 `fixed` 模式。   
在 `fixed` 模式下，`start` 和 `end` 插槽会默认隐藏。

<section>
  <s-drawer id="test-drawer" style="height: 320px">
    <div slot="start"> Start </div>
    <div> Main </div>
    <div slot="end"> Start </div>
  </s-drawer>
</section>

```html
<s-drawer>
  <div slot="start"> Start </div>
  <div> Main </div>
  <div slot="end"> Start </div>
</s-drawer>
```

<section>
  <s-button onclick="document.querySelector('#test-drawer').toggle()"> 切换Start </s-button>
  <s-button onclick="document.querySelector('#test-drawer').toggle('end')"> 切换End </s-button>
</section>

建议通过 `toggle` 方法控制显示和隐藏

```javascript
document.querySelector('#test-drawer').toggle()
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
      <s-td>start</s-td>
      <s-td>开始插槽</s-td>
    </s-tr>
    <s-tr>
      <s-td>end</s-td>
      <s-td>结束插槽</s-td>
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
      <s-td>mode<span class="tag">只读</span></s-td>
      <s-td>模式</s-td>
      <s-td>static, fixed</s-td>
      <s-td>static</s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>show(type, mode)<span class="tag">只读</span></s-td>
      <s-td>
        展开抽屉
      </s-td>
      <s-td>Function</s-td>
      <s-td>Function</s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>dismiss(type, mode)<span class="tag">只读</span></s-td>
      <s-td>
        隐藏抽屉
      </s-td>
      <s-td>Function</s-td>
      <s-td>Function</s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>toggle(type, mode)<span class="tag">只读</span></s-td>
      <s-td>
        切换抽屉
      </s-td>
      <s-td>Function</s-td>
      <s-td>Function</s-td>
      <s-td>否</s-td>
    </s-tr>
  </s-tbody>
</s-table>

```ts
type Type = 'start' | 'end'
type Mode = 'static' | 'fixed' | undefined
```