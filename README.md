# scoop

自用 Scoop bucket 库。

## 使用方法

### 添加 bucket

```powershell
scoop bucket add FateArth https://github.com/FateArth/scoop
```

### 安装应用

```powershell
scoop install FateArth/<app-name>
```

### 搜索应用

```powershell
scoop search <app-name>
```

## 应用列表

| 应用 | 版本 | 描述 |
| ---- | ---- | ---- |
| weixin | 4.1.8 | Free messaging and calling app by Tencent (微信) |

## 贡献

欢迎提交 PR 或 Issue 来添加、更新应用。每个应用的 manifest 文件位于 [`bucket/`](./bucket/) 目录下。

## 参考资料

- [Scoop 官网](https://scoop.sh)
- [Scoop 文档](https://github.com/ScoopInstaller/Scoop/wiki)
- [App Manifests 格式](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
