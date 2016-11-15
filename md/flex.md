# binUi

根据个人对html及css开发习惯，开发的一套自己的移动端ui组件

# flex

class：bin_display_flex父级通用class。
class:bin_flex_1、bin_flex_2、bin_flex_3，目前定义3个弹性盒模型对象的子元素如何分配空间的class。

![calendar](https://github.com/yaob421123/binUi/blob/master/md/img/flex.png)


### 常用flex子元素布局
```bash
<div class="bin_display_flex" >
	<div class="bin_flex_1">...</div>
	<div class="bin_flex_2">...</div>
	<div class="bin_flex_3">...</div>
</div>
```

### flex子元素水平居中布局
```bash
<div class="bin_display_flex bin_flex_center" >
	<div>...</div>
	<div>...</div>
</div>
```

### flex子元素两端对齐布局
```bash
<div class="bin_display_flex bin_flex_sider" >
	<div>...</div>
	<div>...</div>
</div>
```

### flex子元素两端居中对齐布局
```bash
<div class="bin_display_flex bin_flex_around" >
	<div>...</div>
	<div>...</div>
</div>
```