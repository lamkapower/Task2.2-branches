# «Внедрение системы контроля версий»
## Описание проекта
Внедрение системы контроля версий, позволяющей отслеживать изменения кода, как для индивидуальной разработки, так и при работе в команде.

## Prerequisites
* Наличие установлнного программного обеспечения Git
    * [Для Windows](https://git-scm.com/download/win)
    * [Для Mac](https://git-scm.com/download/mac)

## Инструкция по установке
1. **Для Mac:**
There are several ways to install Git on a Mac. The easiest is probably to install the Xcode Command Line Tools. On Mavericks (10.9) or above you can do this simply by trying to run git from the Terminal the very first time.

$ git --version

If you don’t have it installed already, it will prompt you to install it.

If you want a more up to date version, you can also install it via a binary installer. A macOS Git installer is maintained and available for download at the Git website, at [https://git-scm.com/download/mac](https://git-scm.com/download/mac)

![](https://git-scm.com/book/en/v2/images/git-osx-installer.png)

Figure 7. Git macOS Installer.
You can also install it as part of the GitHub for macOS install. Their GUI Git tool has an option to install command line tools as well. You can download that tool from the GitHub for macOS website, at [https://desktop.github.com](https://desktop.github.com)

1. **Для Windows:**

To get an automated installation you can use the [Git Chocolatey package](https://chocolatey.org/packages/git). Note that the Chocolatey package is community maintained.

Another easy way to get Git installed is by installing GitHub Desktop. The installer includes a command line version of Git as well as the GUI. It also works well with PowerShell, and sets up solid credential caching and sane CRLF settings. We’ll learn more about those things a little later, but suffice it to say they’re things you want. You can download this from the [GitHub Desktop website](https://desktop.github.com/).

## Лицензирование

### Free and Open Source

Git is released under the [GNU General Public License version 2.0](http://opensource.org/licenses/GPL-2.0), which is an [open source license](http://www.opensource.org/docs/osd). The Git project chose to use GPLv2 to guarantee your freedom to share and change free software---to make sure the software is free for all its users.

However, we do restrict the use of the term "Git" and the logos to avoid confusion. Please see our [trademark](https://git-scm.com/trademark) policy for details.