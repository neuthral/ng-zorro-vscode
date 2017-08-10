# ng-zorro 的 vscode 代码片断

![Plugin in action](help.gif)

请至[Issuses](https://github.com/cipchk/ng-zorro-vscode/issues)提交可能遇到的问题或期望增加的代码片断。

## 安装扩展

按 `F1` 输入 `ext install ng-zorro-vscode` 后回车。

## 如何使用?

你可以任意 `.html`、`.ts` 文件，输入 `nz-` 开头会自动出现在智能提醒列表当中；仅此而已！

## 文档

更多API接口请参考[ng-zorro-antd](https://github.com/NG-ZORRO/ng-zorro-antd)。

### 根组件

Trigger | Description
--- | ---
root | 根组件只能引入一次，所有ng-zorro组件都应该包裹在下面
### 常规

Trigger | Description
--- | ---
button | 按钮（只含type&amp;size）
button-full | 一个完整指令的按钮
button-icon-text-left | 文本在左边的图标按钮
button-icon-text-right | 文本在右边的图标按钮
button-icon | 图标按钮
icon | Icon图标
### 布局

Trigger | Description
--- | ---
grid-col | 栅格：一列（含：nzSpan、nzOffset）
grid | 栅格：一行一列
grid-row-flex | 栅格：一行flex（含：nzAlign、nzJustify）
grid-row | 栅格：一行
layout | 上中下 Layout 布局
layout-sider | 侧边栏
### 导航

Trigger | Description
--- | ---
breadcrumb | 面包屑
dropdown-button-full | 按钮式下拉菜单（含一个菜单）
dropdown-button | 按钮式下拉菜单
dropdown | 下拉菜单
dropdown-full | 下拉菜单（含一个菜单）
menu | 导航菜单
menu-group | 分组菜单
menu-item-divider | 菜单项分割线
menu-item | 菜单项
menu-submenu | 子菜单
pagination | 分页
steps | 整体步骤条
steps-step-icon | 步骤条内的每一个步骤（自定义图标）
steps-step | 步骤条内的每一个步骤
### 数据录入

Trigger | Description
--- | ---
checkbox-all | 多选框（全选）
checkbox | 多选框
checkbox-group | 多选框组
datepicker | 日期选择框
datepicker-format | 日期选择框（指定时间格式）
datepicker-time | 日期时间选择框
form-control | 表单控制区域，通常用于放置input，select等组件
form | 原生form的增强，用于加强form的样式
form-explain | 用于显示提示信息，会根据当前&#x60;nzValidateStatus&#x60;显示不同的颜色
form-extra | 用于显示表单额外提示信息
form-item-required | 给label添加require样式
form-item | 用于标定一个form item区域
form-label | 用于标定label区域
form-split | 用于显示 &#x60;-&#x60; 分隔符
input-add-on | 带有前后置标签的输入框
input | 输入框
input-group | 输入框组合
input-input-add-on-after | 带有前缀图标的输入框
input-input-add-on-before | 带有后缀图标的输入框
input-input-prefix-suffix | 带有前后缀图标的输入框
input-number | 带数字输入框
input-prefix | 带有前缀图标的输入框
input-suffix | 带有后缀图标的输入框
input-textarea | 多行输入框
rate | 评分组件
radio-button | 按钮样式的单选组合
radio | 单选框（注：必须配合nz-radio-group使用）
radio-group | 单选框组合，用于包裹一组 nz-radio/nz-radio-button
select | 选择器
select-search | 搜索框选择器
slider | 滑动输入条
switch | 开关选择器
switch-icon | 开关选择器（带图标）
switch-text | 开关选择器（带文本）
timepicker | 输入或选择时间的控件
timepicker-format | 输入或选择时间的控件（指定时间格式）
### 数据显示

Trigger | Description
--- | ---
badge | 徽标数
badge-dot | 徽标数（只有小圆点）
badge-standalone | 徽标数（独立使用，不包裹任何元素）
calendar | 日历
card | 卡片
card-full | 卡片（完整结构）
card-image | 卡片（带图片）
carousel | 走马灯（旋转木马，一组轮播的区域。）
collapse | 折叠面板的项
collapse-full | 折叠面板（带*ngFor）
collapse-set | 折叠面板
popover | 气泡卡片
popover-full | 气泡卡片（完整结构）
table-ajax | 表格（远程异步数据）
table | 表格
table-divider | 表格：td中分隔数据
table-footer | 表格：标定footer（需要在 nz-table 设定 nzShowFooter 才会生效）
table-full | 表格（完成所有结构）
table-selection | 表格（带选择框操作）
table-sort | 表格：嵌入th中显示排序状态
table-tbody-tr | 表格：标定tbody中tr
table-tbody | 表格：标定tbody
table-td-active-more | 表格：构建带有功能按钮及更多选项的td
table-td-active | 表格：构建带有功能按钮的td
table-td-checkbox | 表格：标定td且含有checkbox
table-td | 表格：标定td
table-th | 表格：标定th
table-thead | 表格：标定thead
tabs | 标签页
tabs-tab | 标签页：选项卡
timeline | 时间轴
timeline-item | 时间轴：项
timeline-pending | 时间轴：幽灵节点（表示时间轴未完成）必须放在nz-timeline下
tooltip | 文字提示
tooltip-full | 文字提示（完整结构）
### 反馈

Trigger | Description
--- | ---
alert-body | 警告提示（标题与内容使用ng-template格式）
alert | 警告提示
alert-full | 警告提示（完整结构）
modal | 对话框（完整结构，因为需要放置HTML的情况时，认为是比较特别的需求；平常尽可能采用NzModalService服务调用方式）
popconfirm | 气泡确认框
popconfirm-full | 气泡确认框（完整结构）
progress-circle | 进度条（圈形）
progress | 进度条（完整结构）
progress-line | 进度条（线形）
spin | 加载中（用于页面和区块的加载中状态）

## 更新日志

见[CHANGELOG.md](CHANGELOG.md)
