# AideaTabs
Like its name, Aidea is born of an idea. It has simple pages, supports dark color mode, and has rich shortcut keys. You can use it to customize your own search methods.

新版本对软件整体进行优化，之前的功能也随之进行了变动

1. 从 0.1.5 版本开始，取消所有默认的快捷键搜索引擎，全部更改为自定义。
2. 根据用户反馈，增加了关闭快捷键的按钮，让不需要快捷键成为一种选择，默认开启快捷键，需要手动关闭。
3. 修改了自定义搜索的 URL 格式，将原来的 *word=* 更改为了 *word=%s*，用 *%s* 作为占位符来表示搜索内容，这样就可以适应各种情况复杂的URL。
4. 优化外观细节，修改配色，提升视觉效果

### 地址栏搜索
在地址栏中输入 *a* 再按 <kbd>tab</kbd> 键即可在一些常用平台进行搜索

### 划词搜索
在网页中选中内容，右键打开菜单，点击菜单中的 *搜索：xxx* 内容，可以使用不同搜索引擎对选中的内容进行搜索

### 鼠标键操作
- **左键选择**：左键用于点击和选择，与大家平时的使用习惯并无差异
- **右键更改**：右键用于更改，右键点击标签页图标可以将图标进行自定义，右键点击默认搜索中的选项按钮可以更改按钮的URL，常用于自定义按钮的搜索引擎
- **中键重置**：中键用于重置，中键点击标签页图标可以将图标恢复为默认图标，中键点击默认搜索选项按钮可以将按钮恢复为默认状态

> 普通搜索模式下，右键点击搜索框或将图片或其他文件拖拽到搜索框中，文件将转换为base64；文本和链接也可以通过拖拽的方式输入搜索框
>
> 智慧搜索模式下，右键点击搜索框或将图片或其他文件拖拽到搜索框中，文本暂不进行处理

### 键盘快捷键

- <kbd>Alt</kbd> + <kbd> 0 </kbd> ~ <kbd>9</kbd> 快捷键搜索（若搜索框无内容时默认访问对应搜索引擎的一级域名）
- <kbd>Del</kbd> 清空搜索框内容
- <kbd>Alt</kbd> + <kbd>H</kbd> 在搜索框输入上次搜索的内容
- <kbd>Ctrl</kbd> + <kbd>1</kbd> ~ <kbd>6</kbd> 重置快捷键搜索
- <kbd>Alt</kbd> + <kbd>G</kbd> 开启编辑模式，可以自由编辑网页内容。再次按下快捷键 <kbd>Alt</kbd> + <kbd>G</kbd> 即可关闭编辑模式