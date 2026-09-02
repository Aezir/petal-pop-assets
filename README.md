# 花漾默认包 · Petal Pop Default Pack

[花漾贴贴 Petal Pop](https://github.com/Aezir/petal-pop) 的第一个素材包。仓库根目录就是一个包：`manifest.json` + 按类型分的文件夹。

| 目录 | 内容 |
|---|---|
| `stickers/` | 贴纸 |
| `boards/` | 底板（本子） |
| `backgrounds/` | 桌面背景 |
| `bgm/` | 音乐 |

在游戏里安装：打开「素材包」面板，输入 `Aezir/petal-pop-assets`。
想固定到某个版本就写 `Aezir/petal-pop-assets@v1.0.0`。

## 改动素材后

```bash
python tools/make-manifest.py packs/default
```

工具会保留已有条目的 id，只刷新尺寸和 sha256。**条目 id 一旦定下不要再改**，别人的存档靠它找图。完整规则见游戏仓库的 `docs/08-pack-format.md`。

## 许可

素材为 AI 生成后整理，仅供 Petal Pop 及其素材包生态使用，暂不授权其它用途。
