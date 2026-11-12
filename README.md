# ATSRP Tools

一个用于**录制并回放操作**的小工具（Windows / Qt 构建）。

## 运行

1. 克隆或下载本仓库
2. 双击 `ATSRP_Tool.exe`

> 仓库里的 `Qt6*.dll`、`opengl32sw.dll`、`platforms/`、`styles/`、`imageformats/` 等是 Qt 运行时依赖，
> **必须和 `ATSRP_Tool.exe` 放在同一目录**；移动时请整体移动，单独拷 exe 无法启动。

## 目录说明

| 路径 | 说明 |
| --- | --- |
| `ATSRP_Tool.exe` | 主程序 |
| `platforms/`、`styles/`、`imageformats/`、`iconengines/` | Qt 插件 |
| `*.dll` | Qt 与图形运行时依赖 |
| `translations/` | Qt 界面翻译 |

## 注意

- 仅支持 Windows
- 录制前请确认画面中不含密码、私密窗口等敏感信息
