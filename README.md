# Lucid DPT VSCode Extension

This VSCode extension gives crude syntax highlighiting to the expirimental dataplane language [Lucid](https://github.com/PrincetonUniversity/lucid). This extension will remain unpublished due to its wholly exterimental nature.

## Requirements

Running on your own machine:
* Download the `.vsix` file from [Releases](https://github.com/benherber/Lucid-DPT-VSCode-Extension/releases) *OR* clone the repository and build by running: `vsce package`
* Navigate into the directory containing `.vsix` file
* Run the following command to install/update: ```code --install-extension lucid-dpt-<version>.vsix```

## Requirements

None currently.

## Extension Settings

None currently.

## Known Issues

Many will arise.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release.

### 1.0.1

Added icons.

---

## Contributing

Please feel free to submit issues and PRs as well as make forks of your own, the language is still is a work in progress and so is this extension! The syntax highlighting is defined in `lucid.tmLanguage.yml` and converted to the necessary JSON format using the [TextMate Languages Extension](https://marketplace.visualstudio.com/items?itemName=pedro-w.tmlanguage).

**Enjoy!**
