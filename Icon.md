# Icon

我们推荐你使用 `svg` 作为图标，`icon` 组件作为 `svg` 的容器使用，图标的颜色使用 `color` 指定。
<section>
  <s-icon>
    <svg viewBox="0 -960 960 960">
      <path d="M240-200h120v-240h240v240h120v-360L480-740 240-560v360Zm-80 80v-480l320-240 320 240v480H520v-240h-80v240H160Zm320-350Z"></path>
    </svg>
  </s-icon>
</section>

```html
<s-icon>
  <svg viewBox="0 -960 960 960">
    <path d="M240-200h120v-240h240v240h120v-360L480-740 240-560v360Zm-80 80v-480l320-240 320 240v480H520v-240h-80v240H160Zm320-350Z"></path>
  </svg>
</s-icon>
```

#### 图标源

我们推荐你访问 [Google Fonts](https://fonts.google.com/icons) 获取图标、或者使用[阿里巴巴矢量图标库](https://www.iconfont.cn)。

#### 自带图标

为了方便使用和出于体积考虑，`icon` 自带了一些常用的图标，你可以使用 `type` 指定图标

<section>
  <s-icon type="add"></s-icon>
  <s-icon type="search"></s-icon>
  <s-icon type="menu"></s-icon>
  <s-icon type="arrow_back"></s-icon>
  <s-icon type="arrow_forward"></s-icon>
  <s-icon type="arrow_drop_up"></s-icon>
  <s-icon type="arrow_drop_down"></s-icon>
  <s-icon type="arrow_drop_left"></s-icon>
  <s-icon type="arrow_drop_right"></s-icon>
  <s-icon type="more_vert"></s-icon>
  <s-icon type="more_horiz"></s-icon>
  <s-icon type="close"></s-icon>
  <s-icon type="done"></s-icon>
  <s-icon type="chevron_up"></s-icon>
  <s-icon type="chevron_down"></s-icon>
  <s-icon type="chevron_left"></s-icon>
  <s-icon type="chevron_right"></s-icon>
  <s-icon type="light_mode"></s-icon>
  <s-icon type="dark_mode"></s-icon>
  <s-icon type="visibility"></s-icon>
  <s-icon type="visibility_off"></s-icon>
</section>

```html
<s-icon type="add"></s-icon>
<s-icon type="search"></s-icon>
<s-icon type="menu"></s-icon>
<s-icon type="arrow_back"></s-icon>
<s-icon type="arrow_forward"></s-icon>
<s-icon type="arrow_drop_up"></s-icon>
<s-icon type="arrow_drop_down"></s-icon>
<s-icon type="arrow_drop_left"></s-icon>
<s-icon type="arrow_drop_right"></s-icon>
<s-icon type="more_vert"></s-icon>
<s-icon type="more_horiz"></s-icon>
<s-icon type="close"></s-icon>
<s-icon type="done"></s-icon>
<s-icon type="chevron_up"></s-icon>
<s-icon type="chevron_down"></s-icon>
<s-icon type="chevron_left"></s-icon>
<s-icon type="chevron_right"></s-icon>
<s-icon type="light_mode"></s-icon>
<s-icon type="dark_mode"></s-icon>
<s-icon type="visibility"></s-icon>
<s-icon type="visibility_off"></s-icon>
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
      <s-td>type</s-td>
      <s-td>图标名称</s-td>
      <s-td>
        none, add, search, menu, arrow_back, arrow_forward, arrow_drop_up, arrow_drop_down, arrow_drop_left, arrow_drop_right, more_vert, <br>
        more_horiz, close, done, chevron_up, chevron_down, chevron_left, chevron_right, light_mode, dark_mode, visibility, visibility_off
      </s-td>
      <s-td>none</s-td>
      <s-td>是</s-td>
    </s-tr>
  </s-tbody>
</s-table>