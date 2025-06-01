# 修改日志

## 2023年11月9日

### 修改内容：在main_page.html中添加顶栏

1. 在main_page.html中添加了顶栏，参考generate_page.html的顶栏设计
2. 修改了body标签的class，从`flex h-screen overflow-hidden`改为`flex flex-col h-screen overflow-hidden`
3. 添加了header元素，包含标题"AI 生成页面"和图标
4. 调整了整体布局结构，将原有内容包裹在一个flex容器中
5. 确保了HTML结构的完整性，添加了必要的闭合标签

## 2023年11月10日

### 修改内容：统一两个页面的排版和字体大小

1. 修改了左侧边栏的宽度，从`w-60`改为`w-56`，与generate_page.html保持一致
2. 修改了左侧边栏的内部间距，从`space-y-4`改为`space-y-3`
3. 修改了左侧边栏按钮的样式，使其与generate_page.html保持一致
4. 修改了左侧导航菜单项的样式，包括内边距和文字颜色
5. 修改了.page-item.active的样式，使其与generate_page.html保持一致
6. 修改了页面背景色，使用与generate_page.html相同的背景色
7. 添加了main-content-bg类，使主内容区域的背景与generate_page.html保持一致