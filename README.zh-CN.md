# show-plan

[English](README.md) | 简体中文

编码前预览改动：只读检查工作区，按文件和位置展示准确的 **before / after** 代码（除纯新增、纯删除外附带 unified **diff**），输出后停止等待审阅，不修改文件。仅手动调用，说明使用简体中文。

## 安装

需要 Node.js 22.20+ 和 Git。运行后按提示选择编程助手及安装范围（当前项目或全局）：

```sh
npx skills add Kieran351/show-plan
```

## 更新

按提示选择需要更新的安装范围：

```sh
npx skills update show-plan
```

## 卸载

卸载全局安装：

```sh
npx skills remove show-plan -g
```

如果是项目安装，请在对应项目目录执行，并去掉 `-g`。
