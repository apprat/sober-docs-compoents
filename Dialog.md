# Dialog

对话框的 `trigger` 插槽并不是必须的，有些时候动态调用 `show()` 方法也许更方便。

<section>
  <s-dialog negative="取消" positive="确定">
    <!--触发按钮-->
    <s-button slot="trigger"> Dailog </s-button>
    <!--标题-->
    <div slot="headline"> Title </div>
    <!--内容-->
    <div slot="text">问人生、头白京国，算来何事消得。不如罨画清溪上，蓑笠扁舟一只。人不识，且笑煮、鲈鱼趁著莼丝碧。无端酸鼻，向岐路消魂，征轮驿骑，断雁西风急。
      英雄辈，事业东西南北。临风因甚泣。酬知有愿频挥手，零雨凄其此日。休太息，须信道、诸公衮衮皆虚掷。年来踪迹。有多少雄心，几翻恶梦，泪点霜华织。
    </div>
  </s-dialog>
</section>

```html
<s-dialog negative="取消" positive="确定">
  <!--触发按钮-->
  <s-button slot="trigger"> Dailog </s-button>
  <!--标题-->
  <div slot="headline"> Title </div>
  <!--内容-->
  <div slot="text">问人生、头白京国，算来何事消得。不如罨画清溪上，蓑笠扁舟一只。人不识，且笑煮、鲈鱼趁著莼丝碧。无端酸鼻，向岐路消魂，征轮驿骑，断雁西风急。
    英雄辈，事业东西南北。临风因甚泣。酬知有愿频挥手，零雨凄其此日。休太息，须信道、诸公衮衮皆虚掷。年来踪迹。有多少雄心，几翻恶梦，泪点霜华织。
  </div>
</s-dialog>
```

自定义布局

<section>
  <s-dialog>
    <!--触发按钮-->
    <s-button slot="trigger"> Dailog </s-button>
    <div style="padding: 24px">
      <s-circular-progress indeterminate="true"></s-circular-progress>
    </div>
  </s-dialog>
</section>

```html
<s-dialog>
  <!--触发按钮-->
  <s-button slot="trigger"> Dailog </s-button>
  <!--自定义布局-->
  <div style="padding: 24px">
    <s-circular-progress indeterminate="true"></s-circular-progress>
  </div>
</s-dialog>
```

对话框嵌套

<section>
  <s-dialog>
    <!--触发按钮-->
    <s-button slot="trigger"> Dailog </s-button>
    <div style="padding: 24px">
      <s-dialog>
        <s-button slot="trigger"> open </s-button>
        <div slot="headline">对话框嵌套</div>
        <div slot="text">对话内容</div>
      </s-dialog>
    </div>
  </s-dialog>
</section>

```html
<s-dialog>
  <!--触发按钮-->
  <s-button slot="trigger"> Dailog </s-button>
  <!--嵌套-->
  <div style="padding: 24px">
    <s-dialog>
      <s-button slot="trigger"> open </s-button>
      <div slot="headline">对话框嵌套</div>
      <div slot="text">对话内容</div>
    </s-dialog>
  </div>
</s-dialog>
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
      <s-td>positive</s-td>
      <s-td>积极按钮点击后触发</s-td>
    </s-tr>
    <s-tr>
      <s-td>negative</s-td>
      <s-td>消极按钮点击后触发</s-td>
    </s-tr>
    <s-tr>
      <s-td>show</s-td>
      <s-td>对话框开始显示时触发</s-td>
    </s-tr>
    <s-tr>
      <s-td>showed</s-td>
      <s-td>对话框显示后触发（动画结束）</s-td>
    </s-tr>
    <s-tr>
      <s-td>dismiss</s-td>
      <s-td>对话框开始隐藏时触发</s-td>
    </s-tr>
    <s-tr>
      <s-td>dismissed</s-td>
      <s-td>对话框隐藏后触发（动画结束）</s-td>
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
      <s-td>size</s-td>
      <s-td>对话框尺寸</s-td>
      <s-td>basic, vertical, horizontal, large, full</s-td>
      <s-td>basic</s-td>
      <s-td>是</s-td>
    </s-tr>
    <s-tr>
      <s-td>positive</s-td>
      <s-td>积极按钮文本</s-td>
      <s-td>string</s-td>
      <s-td></s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>negative</s-td>
      <s-td>消极按钮文本</s-td>
      <s-td>string</s-td>
      <s-td></s-td>
      <s-td>否</s-td>
    </s-tr> 
    <s-tr>
      <s-td>show()<span class="tag">只读</span></s-td>
      <s-td>显示对话框</s-td>
      <s-td>Function</s-td>
      <s-td>Function</s-td>
      <s-td>否</s-td>
    </s-tr>
    <s-tr>
      <s-td>dismiss()<span class="tag">只读</span></s-td>
      <s-td>隐藏对话框</s-td>
      <s-td>Function</s-td>
      <s-td>Function</s-td>
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
      <s-td>trigger</s-td>
      <s-td>触发器</s-td>
    </s-tr>
    <s-tr>
      <s-td>headline</s-td>
      <s-td>标题</s-td>
    </s-tr>
    <s-tr>
      <s-td>text</s-td>
      <s-td>文本内容</s-td>
    </s-tr>
  </s-tbody>
</s-table>
