# icons

使用方法：

将icons.svg拷贝之项目文件中，然后在html中通过svg标签调用，以home图标为例：

```html
<svg class="icon-svg icon-home"><use xlink:href="images/icons.svg#icon-home"></use></svg>
```

svg的class由`icon-svg`和`icon-id`组成，xlink:href地址由两部分组成，`#`前面为所使用的svg的路径，后面为所使用图标的id.(每个图标的id在svg文件中都有定义)

注：demo请在服务器中访问，可使用express搭建本地服务器（不然svg icon不显示）
