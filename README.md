# all-contributors-cli test
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)

Official website: https://allcontributors.org

English | 中文
-|-
[README.md](README.md)|[README-zh-CN.md](README-zh-CN.md)

## Ⅰ.Install from NPM

```bash
yarn add --dev all-contributors-cli 
# OR
npm i -D all-contributors-cli
```

## Ⅱ.Init the Project

```bash
yarn all-contributors init
# Or 
npm run all-contributors init
# Or directly execute the bin
./node_modules/.bin/all-contributors init
```

## Ⅲ.Add some contributors

```bash
# Add new contributor <username>, who made a contribution of type <contribution>
all-contributors add <username> <contribution>

# Example:
# all-contributors add jfmengels code,doc

# generate table
yarn all-contributors generate
```

### NOTE1：Before generate

Use generate to read the contributors list from your .all-contributorsrc file and update the contributor tables specified by the files key.

Please note the command must be able to find the following tags in those files, in order to update the table:

```
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Allenem"><img src="https://avatars1.githubusercontent.com/u/33366355?v=4" width="100px;" alt="蒲尧"/><br /><sub><b>蒲尧</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=Allenem" title="Code">💻</a> <a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=Allenem" title="Documentation">📖</a> <a href="#translation-Allenem" title="Translation">🌍</a></td>
    <td align="center"><a href="http://yirongchen.com/"><img src="https://avatars3.githubusercontent.com/u/45977848?v=4" width="100px;" alt="Yirong Chen"/><br /><sub><b>Yirong Chen</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=scutcyr" title="Code">💻</a></td>
    <td align="center"><a href="https://gitee.com/icyzeroice"><img src="https://avatars2.githubusercontent.com/u/17965578?v=4" width="100px;" alt="Ice Zero"/><br /><sub><b>Ice Zero</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=icyzeroice" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->
```
&hearts; The code above will be modified as runing `yarn all-contributors generate` , please delete contents between the first tag and the last one.

### NOTE2：Emoji Key ✨ (and Contribution Types)

| Emoji/Type | Represents | Comments |
| --- | --- | --- |
| 💬
`question` | Answering Questions | Answering Questions in Issues, Stack Overflow, Gitter, Slack, etc. |
| 🐛
`bug` | Bug reports | links to issues reported by the user on this project |
| 📝
`blog` | Blogposts | links to the blogpost |
| 💼
`business` | Business Development | people who execute on the business end |
| 💻
`code` | Code | links to commits by the user on this project |
| 🖋
`content` | Content | e.g. website copy, blog posts are separate |
| 📖
`doc` | Documentation | links to commits by the user on this project, Wiki, or other source of documentation |
| 🎨
`design` | Design | links to the logo/iconography/visual design/etc. |
| 💡
`example` | Examples | links to the examples |
| 📋
`eventOrganizing` | Event Organizers | links to event page |
| 💵
`financial` | Financial Support | people or orgs who provide financial support, links to relevant page |
| 🔍
`fundingFinding` | Funding/Grant Finders | people who help find financial support |
| 🤔
`ideas` | Ideas & Planning |  |
| 🚇
`infra` | Infrastructure | Hosting, Build-Tools, etc. Links to source file (like `travis.yml`) in repo, if applicable |
| 🚧
`maintenance` | Maintenance | people who help in maintaining the repo, links to commits by the user on this project |
| 📦
`platform` | Packaging | porting to support a new platform |
| 🔌
`plugin` | Plugin/utility libraries | links to the repo home |
| 📆
`projectManagement` | Project Management |  |
| 👀
`review` | Reviewed Pull Requests |  |
| 🛡️
`security` | Security | identify and/or reduce security threats, GDPR, Privacy, etc |
| 🔧
`tool` | Tools | links to the repo home |
| 🌍
`translation` | Translation | links to the translated content |
| ⚠️
`test` | Tests | links to commits by the user on this project |
| ✅
`tutorial` | Tutorials | links to the tutorial |
| 📢
`talk` | Talks | links to the slides/recording/repo/etc |
| 📓
`userTesting` | User Testing | links to user test notes |
| 📹
`video` | Videos | links to the video |

## Ⅳ.Update your Contributing documentation

Consider updating your `.all-contributorsrc` or similar with steps on how your contributors can add themselves. 

## Ⅴ.Optionally add shortcut scripts to your package.json

You can optionally add shortcuts to your commands in your package.json scripts field.

For example:
```json
{
  "scripts": {
    "contributors:add": "all-contributors add",
    "contributors:generate": "all-contributors generate"
  }
}
```
To allow shortcuts such as
```bash
yarn contributors:add jfmengels doc
```

* * *

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

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

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!