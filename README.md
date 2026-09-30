# dsh-chat-character

在 DeepSeek Harness（DSH）左侧边栏左下角放置一张角色立绘图片的客户端插件。

## 安装

```bash
dsh plugin --profile <你的profile> add https://codeload.github.com/Sanksu/dsh-chat-character/tar.gz/refs/heads/main
```

或在 profile 的 `package.json` 中声明：

```json
{
  "dependencies": {
    "dsh-chat-character": "https://codeload.github.com/Sanksu/dsh-chat-character/tar.gz/refs/heads/main"
  }
}
```

## 配置

角色图片位于 `assets/character.png`，替换该文件即可更换立绘。
