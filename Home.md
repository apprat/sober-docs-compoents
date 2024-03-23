# 组件

组件名称均以为 `s` 开头，组件之间是相互解耦的，所以可以做到在按需引入时可以极大的减少体积。

#### 颜色和大小

大多数组件都支持使用 CSS 的 `color` 或 `background` 单独设置颜色，或者 `width` 、 `height` 设置大小，例如：

<section>
  <s-button style="background: #009688"> button </s-button>
  <s-checkbox checked="true" style="color: #e42241"></s-checkbox>
  <s-checkbox checked="true" style="color: #5b5bb7; width: 56px; height: 56px"></s-checkbox>
  <s-switch checked="true" style="color: #9fa42a"></s-switch>
  <s-switch checked="true" style="color: #8b54ba; width: 40px"></s-switch>
</section>

```html
<s-button style="background: #009688"> button </s-button>
<s-checkbox checked="true" style="color: #e42241"></s-checkbox>
<s-checkbox checked="true" style="color: #5b5bb7; width: 56px; height: 56px"></s-checkbox>
<s-switch checked="true" style="color: #009688"></s-switch>
<s-switch checked="true" style="color: #8b54ba; width: 40px"></s-switch>
```

# 事件
所有组件都继承自 `HTMLElement` ，这意味着所有组件都会触发 `HTMLElement` 能响应的事件，例如：`click`、`mousedown` 等。 

```html
<s-button onclick="console.log('click')">
  button
</s-button>
```

# 类型

组件的类型定义可以从 `HTMLElementTagNameMap` 中获取
```ts
type Button = HTMLElementTagNameMap['s-button']
```

或者使用 `import` 导入定义

```javascript
import { Button } from 'sober'
// 或者
import Button from 'sober/button'
```

# 属性

大多数组件都拥有一些额外属性，这些属性可以通过 DOM 属性直接设置
```html
<s-button type="outlined"> button </s-button>
```

也可以通过编程方式进行设置或者获取

```javascript
import { Button } from 'sober'

const button = new Button()
consoe.log(button.type)
button.type = 'outlined'
```

#### 属性类型

组件的属性可能为三种类型：`string`、`number`、`boolean`。  
在你通过属性设置时，组件会尝试转换为目标类型。

```html
<s-button id="button" disabled="true"> button </s-button>
<script>
  console.log(typeof document.querySelector('#button').disabled)  //输出 boolean
</script>
```


#### 同步属性

某些属性是同步的，在编程方式进行设置时，DOM 属性也会同步更新

```html
<s-button id="button"> button </s-button>
<script>
  document.querySelector('#button').type = 'outlined'
</script>
```

这时 `s-button` 会同步设置为 
```html
<s-button type="outlined"> button </s-button>
```

这使得我们可以做一些样式定义，如
```css
.button[type=outlined]{
  color: #009688;
}
```