# ShellChecker

[![License: LGPL-3.0-or-later](https://img.shields.io/badge/license-LGPL--3.0%2B-blue)](https://www.gnu.org/licenses/lgpl-3.0.html)
[![GitHub release](https://img.shields.io/github/v/release/a5k-actions/shellchecker)](https://github.com/a5k-actions/shellchecker/releases/latest)

<!-- action-docs-description -->
## Description

GitHub action to execute a lint check of all shell scripts using ShellCheck.


<!-- action-docs-description -->

<!-- action-docs-inputs -->
## Inputs

| parameter | description | required | default |
| - | - | - | - |
| shellcheck-version | Version of ShellCheck to use. Values: [stable, latest, v0.7.2, ...] | `false` | stable |
| severity | Minimum severity of issues to display. Values: [style, info, warning, error] | `false` | style |
| enable-all-opt-checks | Enable all optional checks. Values: [true, false] | `false` | false |
| ignore-files | List of files to ignore, the separator is: &#124; | `false` |  |



<!-- action-docs-inputs -->

<!-- action-docs-outputs -->



<!-- action-docs-outputs -->

<!-- action-docs-runs -->
## Runs

This action is an `composite` action.


<!-- action-docs-runs -->
