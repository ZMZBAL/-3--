自动完成崩崩崩视觉小说成就的JavaScript脚本

## Usage
* 使用浏览器(Chrome kernel)登录 https://event.bh3.com/avgAntiEntropy/index.php?auth_key=XXX&sign=XXX
* **随意点开一章，阅读几页，以便自动初始化部分全局变量**
* F12进入开发者模式
* **Ctrl+F8 取消所有断点调试。即toggle Activate breakpoint**
* **再次刷新页面 或 按F8 或 点击蓝色箭头 继续脚本执行**
* 在Console键入js内的代码并回车。**若出现操作频繁等问题，请参考Notice部分**

## Notice

**若出现操作频繁等问题，请手动修改上方代码最后一个for循环的起始及终止条件，间隔一段时间（半小时以上）分批次提交成就**

**例如**
```
for (let i = 1; i <= 8; i++) {
    galgame(i);
}
```
**代表本次仅完成1-8章的所有成就
