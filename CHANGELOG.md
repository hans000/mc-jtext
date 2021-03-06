# 更新日志

## 2020-08-12
- 修复转义字符的bug

## 2020-07-21
- 仓库添加合并功能
- 仓库添加了输出模板可编辑
- 对仓库操作按钮布局微调

## 2020-07-21
- 添加对1.16十六进制颜色的支持
- 修复一些bug

## 2020-05-01
- 使用mojangson-parser2.0，修复由于1.16新nbt格式导致的显示问题

## 2020-04-17

- 引入新的parser，mojangson-parser
- 牌子和成书的生成使用单引号
- nbt解析可以解析单引号的文本

## 2020-04-03

- 添加标签功能，用于快速填写备注
- 快捷键调整，删除线ctrl + s -> ctrl + shift + s；暂存ctrl + shift + s ->ctrl + s
- 仓库管理进一步加强，添加了备注筛选、按时间排序和预览功能
- 加入本地存储功能，标签和仓库数据会实时缓存到本地，关闭浏览器再次打开会自动加载缓存数据

## 2020-03-28

- 调整页面
- 添加用户引导功能

## 2020-03-22

- 添加nbt解析功能，解决nbt路径不会书写的问题，新手也可以快速实现nbt路径书写。当nbt为实体且entity选项为空时会自动填充一个默认的选择器；当nbt为物品且block选项为空时会自动填充解析的坐标

- 页面字段调整，「保存」->「暂存」，「输出」->「仓库」

- 页面添加了快捷键提示，鼠标选停展示

- 增强表格操作，添加「移动」「整理」「删除」「hover」

  - 「移动」将勾选项向上移动一位，操作对象为勾选项中第一项至最后一项之间的数据
  - 「整理」将勾选项拼接到一起，按第一项的位置依次排列
  - 「删除」可以批量删除
  - 「hover」启用hover的高级模式，并将当前项填充

## 2020-03-19
- 操作体验优化，默认文本框自动获取焦点，点击预览的tile对应的输入框会自动获取焦点
- 修复「拆分」bug

## 2020-03-18
- 移除「插入」「克隆」功能，添加更为强大的「拆分」功能

## 2020-03-15
- 添加高亮动画
- UI 微调，界面更简洁
- 添加更新日志链接

## 2020-03-05
- 颜色选择组件有下拉框改为色块形式