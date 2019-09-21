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

## Ⅵ.Attention

### NOTE1：Before generate

Use generate to read the contributors list from your .all-contributorsrc file and update the contributor tables specified by the files key.

Please note the command must be able to find the following tags in those files, in order to update the table:

```
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- ALL-CONTRIBUTORS-LIST:END -->
```
&hearts; The code above will be modified as runing `yarn all-contributors generate` , please move contents between the first tag and the last one to the last paragraph [Contributors](#contributors-).

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

### NOTE3：CLI Configuration

 You can configure all-contributors by updating the `.all-contributorsrc` JSON file. The data used to generate the contributors list will be stored in there, and you can configure how you want `all-contributors-cli` to generate the list.

These are the keys you can specify:

| Option | Description | Example/Default |
| --- | --- | --- |
| `projectName` | Mandatory, name of the project. | Example: `all-contributors-cli` |
| `projectOwner` | Mandatory, name of the user the project is hosted by. | Example: `jfmengels` |
| `repoType` | Type of repository. Must be either `github` or `gitlab`. | Default: `github` |
| `repoHost` | Points to the repository hostname. Change it if you use a self-hosted repository. | Default: `https://github.com` if `repoType` is `github`, and `https://gitlab.com` if `repoType` is `gitlab` |
| `files` | Array of files to update. | Default: `['README.md']` |
| `imageSize` | Size (in px) of the user's avatar. | Default: `100` |
| `commit` | Auto-commit badge when adding contributors. | `true` or `false` |
| `commitConvention` | Commit convention ([`angular`](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-guidelines), [`atom`](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#git-commit-messages), [`ember`](https://guides.emberjs.com/v1.10.0/contributing/#toc_commits), [`eslint`](https://eslint.org/docs/1.0.0/developer-guide/contributing#step-2-make-your-changes), [`jshint`](https://jshint.com/contribute/) or [`gitmoji`](https://gitmoji.carloscuesta.me/)). | Default: `none` |
| `contributorsPerLine` | Maximum number of columns for the contributors table. | Default: `7` |
| `badgeTemplate` | Define your own lodash template to generate the badge. |  |
| `contributorTemplate` | Define your own lodash template to generate the contributor. |  |
| `types` | Specify custom symbols or link templates for contribution types. Can override the documented types. |  |
| `contributors` | List of contributors for this project, this is updated by [all-contributors add](https://allcontributors.org/docs/en/cli/usage#all-contributors-add) |  |

* * *

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Allenem"><img src="https://avatars1.githubusercontent.com/u/33366355?v=4" width="100px;" alt="蒲尧"/><br /><sub><b>蒲尧</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=Allenem" title="Code">💻</a> <a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=Allenem" title="Documentation">📖</a> <a href="#translation-Allenem" title="Translation">🌍</a> <a href="#review-Allenem" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/ionicbond-lzj"><img src="https://avatars0.githubusercontent.com/u/45113875?v=4" width="100px;" alt="ionicbond-lzj"/><br /><sub><b>ionicbond-lzj</b></sub></a><br /><a href="https://github.com/Allenem/all-contributors-cli-test/commits?author=ionicbond-lzj" title="Tests">⚠️</a></td>
    <td align="center"><a href="https://github.com/Juliayao"><img src="https://avatars3.githubusercontent.com/u/55355288?v=4" width="100px;" alt="Juliayao"/><br /><sub><b>Juliayao</b></sub></a><br /><a href="#userTesting-Juliayao" title="User Testing">📓</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!