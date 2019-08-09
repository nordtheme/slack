<p align="center"><a href="https://www.nordtheme.com/ports/slack" target="_blank"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/slack/repository-hero.svg?sanitize=true"/></a></p>

<p align="center"><a href="https://www.nordtheme.com/docs/ports/slack" target="_blank"><img src="https://img.shields.io/github/release/arcticicestudio/nord-slack.svg?style=flat-square&label=Docs&colorA=4c566a&colorB=88c0d0&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiI%2BCiAgICA8cGF0aCBmaWxsPSIjZDhkZWU5IiBkPSJNMTMuNzQ2IDIuODEzYS42Ny42NyAwIDAgMC0uNTU5LS4xMzNMOCAzLjg0OGwtNS4xODgtMS4xOGEuNjY5LjY2OSAwIDAgMC0uNTcuMTMzLjY3Ny42NzcgMCAwIDAtLjI0Mi41MzF2OC4xMzNjLS4wMDguMzIuMjEuNTk4LjUyLjY2OGw1LjMzMiAxLjE5OWguMjk2bDUuMzMyLTEuMmEuNjY4LjY2OCAwIDAgMCAuNTItLjY2N1YzLjMzMmEuNjU5LjY1OSAwIDAgMC0uMjU0LS41MnpNMy4zMzIgNC4xNjhsNCAuODk4djYuNzY2bC00LS44OTh6bTkuMzM2IDYuNzY2bC00IC44OThWNS4wNjZsNC0uODk4em0wIDAiLz4KPC9zdmc%2BCg%3D%3D"/></a></p>

<!--lint disable no-duplicate-headings no-duplicate-headings-in-section-->

<p align="center">Changelog for <a href="https://www.nordtheme.com/ports/slack">Nord Slack</a> — An arctic, north-bluish clean and elegant <a href="https://slack.com" target="_blank">Slack</a> theme.</p>

# 0.2.0

![Release Date: 2019-08-06](https://img.shields.io/static/v1.svg?style=flat-square&label=Release%20Date&message=2019-08-06&colorA=4c566a&colorB=88c0d0) [![Project Board](https://img.shields.io/static/v1.svg?style=flat-square&label=Project%20Board&message=0.1.0&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0)](https://github.com/arcticicestudio/nord-sublime-text/projects/2) [![Milestone](https://img.shields.io/static/v1.svg?style=flat-square&label=Milestone&message=0.1.0&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0)](https://github.com/arcticicestudio/nord-sublime-text/milestone/1)

## Features

**Nord Docs Transition** — #5 ⇄ #6 (⊶ 67050955)
↠ Transferred all documentations, assets and from „Nord Slack“ to [Nord Docs][nord]
Please see the [corresponding issue in the Nord Docs repository][nord-docs#175] to get an overview of what has changed for _Nord Slack_ and what has been done to migrate to Nord Docs.

###### Landing Page

<p align="center"><a href="https://www.nordtheme.com/ports/slack" target="_blank"><img src="https://user-images.githubusercontent.com/7836623/62790926-6a3d2e80-bacc-11e9-98b1-a19d1bc18725.png" alt="Preview: Nord Slack Port Project Landing Page"/></a></p>

###### Landing Page Docs

<p align="center"><a href="https://www.nordtheme.com/docs/ports/slack" target="_blank"><img src="https://user-images.githubusercontent.com/7836623/62790924-69a49800-bacc-11e9-9748-be6f26ba5c30.png" alt="Preview: Nord Slack Docs Project Landing Page"/></a></p>

###### Installation & Activation Docs

<p align="center"><a href="https://www.nordtheme.com/docs/ports/slack/installation" target="_blank"><img src="https://user-images.githubusercontent.com/7836623/62790925-6a3d2e80-bacc-11e9-9a8a-c713d0cafd1f.png" alt="Preview: Nord Slack Docs Installation & Activation Docs Page"/></a></p>

**Color values in multiple data formats** — #6 (⊶ b5a81555)
↠ Previously the color values were only provided through the documentation in the `README.md` file that can not be simply parsed programmatically for automated usage in other projects. This has been changed by adding the following data file formats that can be parsed:

- [JSON][] - The file provides an object that contains an `colors` collection/array that stores the individual colors as [HEX][wiki-web_color#hex] values. They can be read and concatenated with a _comma_ (`,`) to match Slack's shareable theme format.
- [YAML][] - Like the _JSON_ format, the _YAML_ file also provides the `colors` collection/array containing the color [HEX][wiki-web_color#hex] values.
- _Plain Text_ - The colors are also provided as _plain text_ through a [`.txt`][wiki-txt_file] file.

## Tasks

### Documentation

**Migration to MIT license** — #3 ⇄ #4 (⊶ 23552e95)
↠ Adapted to the MIT license migration of [Nord][]. Details can be found in the main task ticket [arcticicestudio/nord#55][nord#55].

# 0.1.0

![Release Date: 2017-10-21](https://img.shields.io/static/v1.svg?style=flat-square&label=Release%20Date&message=2017-10-21&colorA=4c566a&colorB=88c0d0) [![Project Board](https://img.shields.io/static/v1.svg?style=flat-square&label=Project%20Board&message=0.1.0&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0)](https://github.com/arcticicestudio/nord-slack/projects/2) [![Milestone](https://img.shields.io/static/v1.svg?style=flat-square&label=Milestone&message=0.1.0&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0)](https://github.com/arcticicestudio/nord-slack/milestone/1)

## Features

Detailed information about features and install instructions can be found in the [README](https://github.com/arcticicestudio/nord-slack/blob/develop/README.md#installation) and in the [project wiki](https://github.com/arcticicestudio/nord-slack/wiki).

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-slack/develop/assets/scrot-hero.png"/></p>

<p align="center"><strong>Menu- and item hovering</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-slack/develop/assets/scrcast-hovering.gif"/></p>

❯ Defined the theme colors according to the [Nord Style Guidelines][gh-repo]. (@arcticicestudio, #1 in PR #2, b37cbde4)

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-slack/develop/assets/scrot-definitions.png"/></p>

<!--
+------------------+
+ Symbol Reference +
+------------------+
↠ (U+21A0): Start of a log section description
— (U+2014): Separator between a log section title and the metadata
⇄ (U+21C4): Separator between a issue ID and pull request ID in a log metadata
⊶ (U+22B6): Icon prefix for the short commit SHA checksum in a log metadata
-->

<!--lint disable final-definition-->

<!-- Base Links -->

[gh-repo]: https://github.com/arcticicestudio/nord
[json]: https://json.org
[nord]: https://www.nordtheme.com
[wiki-txt_file]: https://en.wikipedia.org/wiki/Text_file
[wiki-web_color#hex]: https://en.wikipedia.org/wiki/Web_colors#Converting_RGB_to_hexadecimal
[yaml]: https://yaml.org

<!-- v0.2.0 -->

[nord-docs#172]: https://github.com/arcticicestudio/nord-docs/issues/172
[nord#55]: https://github.com/arcticicestudio/nord/issues/55
