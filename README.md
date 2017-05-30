<p align="center">
  <img alt="githubdark-logo" src="https://rawgit.com/StylishThemes/logos/master/github.dark/githubdark-mini.svg" width="580">
  <br>
  <a href="https://github.com/StylishThemes/GitHub-Dark/tags">
    <img src="https://img.shields.io/github/tag/StylishThemes/GitHub-Dark.svg?label=%20tag%20" alt="Tag">
  </a>
  <a href="https://github.com/StylishThemes/GitHub-Dark/stargazers">
    <img src="http://github-svg-buttons.herokuapp.com/star.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=007ec6" alt="Star">
  </a>
  <a href="http://github.com/StylishThemes/GitHub-Dark/fork">
    <img src="http://github-svg-buttons.herokuapp.com/fork.svg?user=StylishThemes&repo=GitHub-Dark&style=flat&background=007ec6" alt="Fork">
  </a>
  <a href="https://david-dm.org/StylishThemes/GitHub-Dark?type=dev">
    <img src="https://img.shields.io/david/dev/StylishThemes/GitHub-Dark.svg?label=%20devDependencies%20" alt="devDependencies">
  </a>
  <a href="https://gitter.im/StylishThemes/GitHub-Dark">
    <img src="https://img.shields.io/gitter/room/StylishThemes/Github-Dark.js.svg?maxAge=2592000" alt="Gitter">
  </a>
</p>
<h2 align="center">Your eyes will :heart: you.</h2>

## Preview
![](./images/screenshots/after_blue.png)

## Installing

* If you're using a browser extension:
  * Stylus - get the addon for [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne).
  * Stylish - get the addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/2108/), [Chrome](https://chrome.google.com/extensions/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe), [Opera](https://addons.opera.com/en/extensions/details/stylish/), [Safari](http://sobolev.us/stylish/) and [Firefox Mobile](https://addons.mozilla.org/en-US/firefox/addon/2108/).
  * Then install this style using:
    * [userstyles.org](http://userstyles.org/styles/37035) (with customization options)
    * or, add it [manually](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/github-dark.css) into the editor.
      * Use the [grunt build process](https://github.com/StylishThemes/GitHub-Dark/wiki/Build) to customize your GitHub Dark theme.
      * Please refer to the [installation documentation](https://github.com/StylishThemes/GitHub-Dark/wiki/Install) for more details.
* Or, use our [GitHub-Dark Script](https://github.com/StylishThemes/GitHub-Dark-Script) which requires a [user script addon](https://github.com/StylishThemes/GitHub-Dark-Script/wiki/Install), but allows dynamic style changes & updates:bangbang:

## Updating

If a recent change by GitHub broke the style, chances are that we already fixed it. Make sure to reinstall from [userstyles.org](https://userstyles.org/styles/37035/github-dark) or [GitHub](https://raw.githubusercontent.com/StylishThemes/GitHub-Dark/master/github-dark.css) before opening an issue. Note that only Stylish for Firefox performs automatic style updates.

## Additional GitHub Customization

* [GitHub-code-wrap](https://github.com/StylishThemes/GitHub-code-wrap) to wrap long lines in code boxes
* [GitHub-FixedHeader](https://github.com/StylishThemes/GitHub-FixedHeader) to have a fixed header
* [GitHub-Commit-Limit](https://github.com/StylishThemes/GitHub-Commit-Limit) to show line length limits when editing a commit message
* [GitHub-Selected-Tab-Color](https://github.com/StylishThemes/GitHub-Selected-Tab-Color)

## Supported GitHub Addons

* [ZenHub](https://www.zenhub.io/)
* [Octotree](https://github.com/buunguyen/octotree/#octotree)
* [GitHub Awesome Autocomplete](https://github.com/algolia/github-awesome-autocomplete)
* [GitHub canned responses](https://github.com/notwaldorf/github-canned-responses#how-to-get-it)
* [Lovely forks](https://github.com/musically-ut/lovely-forks#lovely-forks)
* [npmhub](https://github.com/npmhub/npmhub)
* [GitHub Notifications Dropdown](https://openuserjs.org/scripts/joeytwiddle/Github_Notifications_Dropdown) (userscript)

## Available Syntax Highlighting Themes ([Demo](https://stylishthemes.github.io/GitHub-Dark/))

* **NEW**: In v1.17.0+, themes for GitHub, CodeMirror and Jupyter may be set separately.

| Theme                      | GitHub | CodeMirror | Jupyter  |
|----------------------------|:------:|:----------:|:--------:|
| Ambiance                   |   *    |     *      |          |
| Base16 Ocean Dark          |        |     *      |     *    |
| Chaos                      |   *    |            |          |
| Clouds Midnight            |   *    |            |          |
| Cobalt                     |   *    |     *      |          |
| Dracula                    |        |     *      |     *    |
| GitHub Dark                |   *    |            |     *    |
| Idle Fingers               |   *    |            |     *    |
| Kr Theme                   |   *    |            |          |
| Merbivore                  |   *    |            |          |
| Merbivore Soft             |   *    |            |          |
| Mono Industrial            |   *    |            |          |
| Mono Industrial Clear      |   *    |            |          |
| Monokai                    |   *    |     *      |     *    |
| Monokai Spacegray Eighties |   *    |     *      |     *    |
| Obsidian                   |   *    |            |     *    |
| Pastel on Dark             |   *    |     *      |     *    |
| Solarized Dark             |   *    |     *      |     *    |
| Terminal                   |   *    |            |          |
| Tomorrow Night             |   *    |            |     *    |
| Tomorrow Night Blue        |   *    |            |     *    |
| Tomorrow Night Bright      |   *    |     *      |     *    |
| Tomorrow Night Eigthies    |   *    |     *      |     *    |
| Twilight                   |   *    |     *      |     *    |
| Vibrant Ink                |   *    |     *      |          |

* Support for [Codemirror](https://codemirror.net/demo/theme.html) and [Jupyter notebook syntax highlighting](https://github.com/sujitpal/statlearning-notebooks/blob/master/src/chapter2.ipynb) themes as listed above.
* Please provide a pull request if you have or want to create a missing theme.

## Notes

* If you're using a custom domain for GitHub Enterprise, be sure to include it though a `@-moz-document` rule (Firefox) or add it to the `Applies to` section in (Chrome).
* If you want GitHub commit messages to use a monospaced font, and have a background color indicating the width limits, check out [GitHub Commit Limit](https://github.com/StylishThemes/GitHub-Commit-Limit).

## Contributions

If you would like to contribute to this repository, please...

1. Fork
2. Make changes (please read the [contribution guidelines](./.github/CONTRIBUTING.md) and abide by them)
3. Create a pull request!

Thanks to all that have [contributed](./AUTHORS) so far!

