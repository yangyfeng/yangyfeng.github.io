---
type: blog
title: git提交规范
categories:
  - 开发工具
tags:
  - 开发工具
  - Git
abbrlink: '596552e8'
date: 2021-03-23 00:00:00
---

规范化 git commit 对于提高 git log 可读性、可控的版本控制和 changelog 生成都有着重要的作用。然而阻碍我们脚步的不只是团队的推广，单单对于一系列工具的配置都让人头大。这其中主要就是 commitlint 和 commitizen 的配合使用以及自定义提交规范。

## Conventional Commits 约定式提交规范

[Conventional Commits](https://www.conventionalcommits.org/zh-hans/v1.0.0-beta.4/) 是一种用于给提交信息增加人机可读含义的规范。约定式提交规范是一种基于消息的轻量级约定。它提供了一组用于创建清晰的提交历史的简单规则；这使得编写基于规范的自动化工具变得更容易。这个约定与 [SemVer](http://semver.org/) 相吻合，在提交信息中描述新特性、bug 修复和破坏性变更。

 提交说明的结构如下所示： 

```js
<类型>([可选的作用域]): <描述>

[可选的正文]

[可选的脚注]

```

### 类型（type）

`feat:`:  类型为 `feat` 的提交表示在代码库中新增了一个功能（这和语义化版本中的 [`MINOR`](https://semver.org/lang/zh-CN/#摘要) 相对应）。

`fix:`：类型为 `fix` 的 提交表示在代码库中修复了一个 bug （这和语义化版本中的 [`PATCH`](https://semver.org/lang/zh-CN/#摘要) 相对应）。

`docs:`: 只是更改文档。

`style:`: 不影响代码含义的变化（空白、格式化、缺少分号等）。

`refactor:`: 代码重构，既不修复错误也不添加功能。

`perf:`: 改进性能的代码更改。

`test:`: 添加确实测试或更正现有的测试。

`build:`: 影响构建系统或外部依赖关系的更改（示例范围：gulp、broccoli、NPM）。

`ci:`: 更改持续集成文件和脚本（示例范围：Travis、Circle、BrowserStack、SauceLabs）。

`chore:`:  其他不修改`src`或`test`文件。

`revert:`: commit 回退。

### 范围（scope）

 可以为提交类型添加一个围在圆括号内的作用域，以为其提供额外的上下文信息。例如 `feat(parser): adds ability to parse arrays.`。 

包含了可选的 `!` 字符以提醒注意破坏性变更的提交说明

```
chore!: drop Node 6 from testing matrix

BREAKING CHANGE: dropping Node 6 which hits end of life in April

```

### 约定式提交规范

每个提交都**必须**使用类型字段前缀，它由一个名词组成，诸如`feat`或`fix`，其后接一个**可选的**作用域字段，以及一个**必要的**冒号（英文半角）和空格。

当一个提交为应用或类库实现了新特性时，**必须**使用`feat`类型。

当一个提交为应用修复 bug 时，**必须**使用`fix`类型。

作用域字段可以跟随在类型字段后面。作用有**必须**是一个描述某部分代码的名词，并用圆括号包围，例如：`fix(parser): `

描述字段**必须**紧接在类型/作用域前缀的空格之后。描述指的是对代码变更的简短总结，例如：`fix:array parsing issue when multiplejspaces were contained in string`。

在简短描述之后，**可以**编写更长的提交正文，为代码变更提供额外的上下文信息。正文**必须**起始于描述字段结束的一个空行后。

在正文结束的一个空行之后，**可以**编写一行或或多行脚注。脚注**必须**包含关于提交的元信息，例如：关联的合并请求、Reviewer、破坏性变更、每条元信息一行。

破坏性变更**必须**标示在正文区域最开始处，或脚注区域中某一行的开始。一个破坏性变更**必须**包含大写的文本`BREAKING CHANGE`，后面紧跟冒号和空格。

在`BREAKING CHANGE:`之后**必须**提供描述，以描述对 API 的变更。例如：`BREAKING CHANGE: enviroment variables now take precedence over cofig files`。

在提交说明中，**可以**使用`feat`和`fix`之外的类型。

工具的实现**必须不**区分大小写地解析构成约定式提交的信息单元，只有`BREAKING CHANGE`  **必须**是大写的。

**可以**在类型/作用域前缀之后，`:`之前，附加`!`字符，以进一步提醒注意破坏性变更。当有`!`前缀时，正文或脚注内必须包含`BREAKING CHANGE: description`

### 为什么使用约定式提交

- 自动化生产 CHANGELOG。
- 基于提交的类型，自动决定语义化的版本变更。
- 向同事、公众与其他利益关系者传达变化的性质。
- 触发构建和部署流程。
- 让人们探索一个更加结构化的提交历史，以便降低对你的项目作出贡献的难度。

## cz-customizable

可自定义的Commitizen插件（或独立实用运行）可帮助实现一致的提交消息。

安装 commitizen、cz-customizable：

```
yarn add -D commitizen cz-customizable
```

 向 package.json 添加新的 script： 

```json
{
  "scripts" : {
    ...
    "commit": "git cz"
  }
  "config": {
    "commitizen": {
      "path": "cz-customizable"
    }
  }
}

```

 在根目录新建 `.cz-config.js` 并复制 [cz-config-EXAMPLE.js](https://github.com/leonardoanalista/cz-customizable/blob/master/cz-config-EXAMPLE.js) 到文件。 



