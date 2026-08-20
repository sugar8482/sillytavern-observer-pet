# Observer Pet / 剧情旁观小团子

一个住在 SillyTavern 页面上的小小旁观聊天伙伴。它会读取你授权的最近剧情，在独立小窗里陪你吐槽、分析和接梗，不会写入角色剧情。

## 初版功能

- 可拖动、会眨眼的蓝色小团子图标。
- 点击图标打开可拖动的独立聊天窗；电脑端可调整窗口大小。
- 通过 SillyTavern Connection Manager 选择独立 API / 模型，不另行保存密钥。
- 可设置最近剧情消息数、旁观对话历史数、角色卡、用户人设、作者注、输出长度和温度。
- 可在发送前预览小团子会看到的内容。
- 旁观对话按 SillyTavern 聊天分开，保存到聊天 metadata；界面位置仅保存在当前设备。
- 支持流式输出与中途停止。

## 安装

在 SillyTavern 的扩展页选择“安装扩展”，粘贴：

```text
https://github.com/sugar8482/sillytavern-observer-pet
```

本地测试时，也可将整个目录放入：

```text
SillyTavern/data/<用户>/extensions/sillytavern-observer-pet/
```

然后重启 SillyTavern 或重载页面。

## API 配置

1. 先在 SillyTavern 的 **Connection Manager** 中建立一个可用连接配置。
2. 点击小团子，再点右上角齿轮。
3. 选择一个连接配置，或让它跟随酒馆当前配置。

扩展不保存 API Key，也不会把旁观者回复写进角色对话。

## 兼容性

初版针对 SillyTavern 1.18.x 开发。

## License

MIT
