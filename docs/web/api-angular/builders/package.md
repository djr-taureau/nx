# package

Build an Angular library

Builder properties can be configured in workspace.json when defining the builder, or when invoking it.
Read more about how to use builders and the CLI here: https://nx.dev/web/guides/cli.

## Properties

### project

Type: `string`

The file path for the ng-packagr configuration file, relative to the current workspace.

### tsConfig

Type: `string`

The full path for the TypeScript configuration file, relative to the current workspace.

### watch

Default: `false`

Type: `boolean`

Run build when files change.
