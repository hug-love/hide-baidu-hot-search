# chrome插件 隐藏百度热搜

## 通过注入css实现，隐藏 `FYB_RD` 元素

```css
.FYB_RD {
  display: none!important;
}
```

## 使用方式
![chrome插件页](./chrome.png)

- 打开chrome上的插件页面（可以翻设置，也可以地址栏直接输入图片上的链接 `chrome://extensions`）
- 打开开发者模式
- 加载已解压的扩展程序