---
title: tests/
sidebar_position: 4
---

模块工程方案测试文件目录。

模块工程方案默认支持对模块进行测试，测试文件统一在项目 tests 目录进行管理，test 命令默认会自动将后缀为 `.test.[tj]sx?` 的文件识别为测试文件。

如果测试中有公共函数和公共组件需要定义，可以直接在 tests 目录使用后缀为 `.[tj]s` 的文件进行编写。