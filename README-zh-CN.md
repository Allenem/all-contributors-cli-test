# all-contributors-cli 测试
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)

官方网址：https://allcontributors.org

English | 中文
-|-
[README.md](README.md)|[README-zh-CN.md](README-zh-CN.md)

## 一、从 NPM 安装

 ```bash
yarn add --dev all-contributors-cli 
# 或者
npm i -D all-contributors-cli
```

## 二、初始化项目

```bash
yarn all-contributors init
# 或者
npm run all-contributors init
# 或者直接执行bin
./node_modules/.bin/all-contributors init
```

## 三、添加贡献者

```bash
# 添加做出了 <contribution> 类型贡献的贡献者 <username>, 
all-contributors add <username> <contribution>

# 例如：
# all-contributors add jfmengels code,doc

# 生成表格
yarn all-contributors generate
```

### 注1：generate 前注意事项

使用 `generate` 从 `.all-contributorsrc` 文件读取贡献者列表 `contributors` 并对指定的文件 `files` 更新贡献者表格。

请注意在这些文件中，下面的标签必须能够被 `generate` 指令找到，以生成或者更新贡献者表格：

```
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Allenem"><img src="https://avatars1.githubusercontent.com/u/33366355?v=4" width="100px;" alt="蒲尧"/><br /><sub><b>蒲尧</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=Allenem" title="Code">💻</a> <a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=Allenem" title="Documentation">📖</a> <a href="#translation-Allenem" title="Translation">🌍</a></td>
    <td align="center"><a href="http://yirongchen.com/"><img src="https://avatars3.githubusercontent.com/u/45977848?v=4" width="100px;" alt="Yirong Chen"/><br /><sub><b>Yirong Chen</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=scutcyr" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->
```
&hearts; 在运行 `yarn all-contributors generate` 时，上面的代码会被自动注入贡献者 , 请删除第一个和最后一个标签之间的内容。

### 注2：Emoji 关键词 ✨ (和贡献种类)

| Emoji图标/关键词 | 含义 | 说明 |
| --- | --- | --- |
| 💬
`question` | 回答了问题 | Answering Questions in Issues, Stack Overflow, Gitter, Slack, etc. |
| 🐛
`bug` | 报告了漏洞 | links to issues reported by the user on this project |
| 📝
`blog` | 博文 | links to the blogpost |
| 💼
`business` | 商业开发 | people who execute on the business end |
| 💻
`code` | 编码 | links to commits by the user on this project |
| 🖋
`content` | 内容 | e.g. website copy, blog posts are separate |
| 📖
`doc` | 文档 | links to commits by the user on this project, Wiki, or other source of documentation |
| 🎨
`design` | 设计 | links to the logo/iconography/visual design/etc. |
| 💡
`example` | 举例 | links to the examples |
| 📋
`eventOrganizing` | 事件组织者 | links to event page |
| 💵
`financial` | 赞助商 | people or orgs who provide financial support, links to relevant page |
| 🔍
`fundingFinding` | 抽募资金者 | people who help find financial support |
| 🤔
`ideas` | 出了点子，想了方案 |  |
| 🚇
`infra` | 基础设施 | Hosting, Build-Tools, etc. Links to source file (like `travis.yml`) in repo, if applicable |
| 🚧
`maintenance` | 维护 | people who help in maintaining the repo, links to commits by the user on this project |
| 📦
`platform` | 打包 | porting to support a new platform |
| 🔌
`plugin` | 插件/工具库 | links to the repo home |
| 📆
`projectManagement` | 项目管理 |  |
| 👀
`review` | 检查 |  |
| 🛡️
`security` | 安全 | identify and/or reduce security threats, GDPR, Privacy, etc |
| 🔧
`tool` | 工具 | links to the repo home |
| 🌍
`translation` | 翻译 | links to the translated content |
| ⚠️
`test` | 测试 | links to commits by the user on this project |
| ✅
`tutorial` | 教程 | links to the tutorial |
| 📢
`talk` | 讨论 | links to the slides/recording/repo/etc |
| 📓
`userTesting` | 用户测试 | links to user test notes |
| 📹
`video` | 视频 | links to the video |


## 四、更新贡献者文档

考虑更新 `.all-contributorsrc` 或者 重复上面相同的步骤添加贡献者。

## 五、在 `package.json` 中选择性添加快捷指令

你可以在 `package.json` 的 `scripts` 区域选择性添加快捷指令。

例如:
```json
{
  "scripts": {
    "contributors:add": "all-contributors add",
    "contributors:generate": "all-contributors generate"
  }
}
```
运行如下指令
```bash
yarn contributors:add jfmengels doc
```

* * *

## 贡献者 ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Allenem"><img src="https://avatars1.githubusercontent.com/u/33366355?v=4" width="100px;" alt="蒲尧"/><br /><sub><b>蒲尧</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=Allenem" title="Code">💻</a> <a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=Allenem" title="Documentation">📖</a> <a href="#translation-Allenem" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/ionicbond-lzj"><img src="https://avatars0.githubusercontent.com/u/45113875?v=4" width="100px;" alt="ionicbond-lzj"/><br /><sub><b>ionicbond-lzj</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=ionicbond-lzj" title="Tests">⚠️</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->