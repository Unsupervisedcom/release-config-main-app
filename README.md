# release-config-general
A semantic-release sharable configuration for releasing general code. This is a fairly standard configuration with no exec plugins, and no npm plugin.
This release config generats release notes, a changelog, commits the changelog via the git plugin, and releases to github.
## Plugins

This shareable configuration use the following plugins:

- [`@semantic-release/commit-analyzer`](https://github.com/semantic-release/commit-analyzer)
- [`@semantic-release/release-notes-generator`](https://github.com/semantic-release/release-notes-generator)
- [`@semantic-release/changelog`](https://github.com/semantic-release/changelog)
- [`@semantic-release/git`](https://github.com/semantic-release/git)
- [`@semantic-release/github`](https://github.com/semantic-release/github)

## Install

```bash
$ npm install --save-dev semantic-release @unsupervised/release-config-general
```

## Usage

The shareable config can be configured in the [**semantic-release** configuration file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```json
{
  "extends": "@unsupervised/release-config-general"
}
```

## Configuration

See each [plugin](#plugins) documentation for required installation and configuration steps.

