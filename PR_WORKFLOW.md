# Git & Pull Request 工作流备忘录

这个文档记录了如何向本仓库提交贡献的标准流程。

## 核心原理图解
1. **Fork**: 把仓库复制到你自己的账号下。
2. **Clone**: 把你账号下的仓库下载到本地。
3. **Branch**: 必须新建分支修改，保护主分支。
4. **Push**: 推送到你的远程仓库 (Origin)。
5. **PR**: 通知原仓库 (Upstream) 合并你的修改。

## 常用命令速查表

### 1. 第一次配置 (仅需做一次)
```bash
# 克隆你 Fork 后的仓库 (注意是你自己的用户名)
git clone [https://github.com/GeYugong/test04.git](https://github.com/GeYugong/test04.git)

# 进入目录
cd test04

# (可选) 关联上游仓库，方便同步更新
git remote add upstream [https://github.com/FogMoe/test04.git](https://github.com/FogMoe/test04.git)

```

## 操作记录
- 2026-01-14: GeYugong 成功初始化仓库，并添加了 gitignore 配置以优化项目结构。