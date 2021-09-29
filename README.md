# ShellChecker

<!-- action-docs-description -->
## Description

GitHub action to execute a lint check of shell scripts using ShellCheck.
<!-- action-docs-description -->

<!-- action-docs-inputs -->
## Inputs

| parameter | description | required | default |
| - | - | - | - |
| shellcheck-version | Version of ShellCheck to use. Values: [stable, latest, v0.7.2, etc.]. Default: [stable] | `false` | stable |
| severity | Minimum severity of issues to display. Values: [error, warning, info, style]. Default: [style] | `false` | style |
| ignore-files | List of files to ignore, the separator is &#124; | `false` |  |
<!-- action-docs-inputs -->

<!-- action-docs-outputs -->

<!-- action-docs-outputs -->

<!-- action-docs-runs -->
## Runs

This action is an `composite` action.
<!-- action-docs-runs -->
