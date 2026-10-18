# bill-owl

个人私有项目，通过 Git 在多台电脑间同步。

## 目录结构

- `projects/` — 按项目分类，每个子文件夹是一个独立小项目（见其中的 README）

## 日常同步流程

```bash
git pull    # 开工前拉取最新
# ...开发...
git add . && git commit -m "改动说明" && git push    # 收工前推送
```
