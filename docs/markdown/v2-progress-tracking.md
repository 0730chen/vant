# Vant 2.0 改动一览

## 不兼容更新

在 2.0 版本中，我们对组件和 API 进行重命名，以更加符合业界的命名规范，同时移除了少量不常用的属性，具体改动如下：

### Actionsheet

- 重命名为`ActionSheet`

### Button

- 移除`bottom-action`属性，请使用`square`和`size`代替

### Field

- 移除`on-icon-click`属性，请使用`click-right-icon`事件代替
- `icon`属性重命名为`right-icon`
- `icon`插槽重命名为`right-icon`
- `click-icon`事件重命名为`click-right-icon`

### GoodsAction

- `GoodsActionBigBtn`重命名为`GoodsActionButton`
- `GoodsActionMiniBtn`重命名为`GoodsActionIcon`
- `GoodsActionBigBtn`移除`primary`属性，请使用`type`属性代替

### Step

- 移除`icon`属性
- 移除`title`属性
- 移除`icon-class`属性
- 移除`description`属性
- 移除`message-extra`插槽

### Badge

- `BadgeGroup`重命名为`Sidebar`
- `Badge`重命名为`SlideBarItem`

### Loading

- 移除`circle`类型
- 移除`gradient-circle`类型

### Waterfall

- 移除在 1.0 版本废弃的 Waterfall 组件，请使用`List`组件代替，或使用独立的[@vant/waterfall](https://github.com/chenjiahan/vant-waterfall)包。

---

## 新特性

- 新增`Skeleton`骨架屏组件
- 新增`IndexBar`、`IndexAnchor`索引栏组件
- 新增`DropdownMenu`、`DropdownItem`下拉菜单组件

### ActionSheet

- 新增`close-on-click-action`属性
- 支持同时使用`title`和`actions`属性

### Button

- 新增`loading-type`属性

### Checkbox

- 新增`icon-size`属性

### Field

- 新增`label-class`属性

### Icon

- 支持`Number`类型的`size`属性

### Loading

- 新增`default`插槽
- 新增`vertical`属性
- 新增`text-size`属性
- 支持`Number`类型的`size`属性

### Notify

- 新增`onClick`属性

### NoticeBar

- 新增`left-icon`插槽
- 新增`right-icon`插槽

### Popup

- 新增`click`事件
- 新增`duration`属性

### Radio

- 新增`icon-size`属性

### SubmitBar

- 新增`tip-icon`属性

### Steps

- 新增`inactive-icon`属性
- 新增`inactive-icon`插槽

### SwitchCell

- 新增`border`属性
- 新增`cell-size`属性

### Sku

- 新增`preview-open`事件
- 新增`preview-close`事件

### Tabbar

- 新增`inactive-color`属性
