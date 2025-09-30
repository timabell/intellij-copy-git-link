<img width="180" alt="Screen Shot 2021-10-11 at 7 51 44" src="https://user-images.githubusercontent.com/11070996/136715482-49f3b847-7926-404d-985b-3259d7e20a30.png">

# Copy Git Link

<!-- Plugin description -->

Provides a shortcut to copy permalink in their online Git repositories from inside IDE.

Works with:

- GitHub
- GitLab
- Bitbucket
- Azure DevOps

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
