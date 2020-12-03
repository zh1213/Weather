### Weather 使用教程

- 下载Scriptable：https://apps.apple.com/cn/app/id1405459188

- 保存Weather脚本：https://github.com/imqimu/Weather/blob/master/Weather.js
  - 在Safari中打开，长按`Raw`点击`下载链接文件`保存在系统文件中`Scriptable`文件夹内

#### 准备工作

- 下载成功后在右上角`Settings`中选择`Editor`打开`Show Line Numbers`

#### 相关设置

1. 在`openweathermap.org/appid`注册并获取apiKey，填写到脚本的第11行引号`""`内
2. 脚本23行修改背景，`true`or`false`
3. 脚本26行重置背景，修改后需要改为`false`
4. 可以在51-53行内修改的显示内容为`日期:date` 、`电量:battery `、 `日出:sunrise`、 `问候语:grreeting `、`未来温度:future`、`当前温度:current`、`活动事件:events`

#### 完成

- 在桌面添加Scriptable小组件，长按`编辑“Scriptable”`，在第一行选择`Weather`