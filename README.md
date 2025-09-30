<!-- Plugin description -->

# Intellij Copy Git Link plugin

https://github.com/timabell/intellij-copy-git-link

Provides a shortcut to copy permalink in their online Git repositories from inside IDE.

## About

Fork of https://github.com/kawamataryo/copy-git-link

This fork adds support for Azure DevOps links.

This fork is *not* on the marketplace. Obtain a copy from [releases](https://github.com/timabell/intellij-copy-git-link/releases).


## Works with

- GitHub (upstream)
- GitLab (upstream)
- Bitbucket (upstream)
- Azure DevOps (this fork only)

## Usage

Select the code you want to copy the permalink to, and click "Copy permalink" from the context menu. The permalink will be saved to the clipboard.

And, Click "Copy permalink as MD" to copy the link in Markdown format.

<!-- Plugin description end -->

## Installation

- Manually:

  Download the [latest release](https://github.com/timabell/intellij-copy-git-link/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>


## Development

To build the plugin:

```sh
./gradlew build
```

This will download gradle, including java, if necessary.

### Run locally built plugin

Use the Gradle IntelliJ Plugin’s runIde task to launch a sandboxed IntelliJ IDEA with your plugin installed:

```sh
./gradlew runIde
```

### Run tests

```sh
./gradlew test
```
