# show-plan

English | [简体中文](README.zh-CN.md)

Preview code changes before implementation: inspect the workspace without editing files, show affected files and locations with exact **before / after** code (plus a unified **diff** for every change except pure additions or deletions), then stop for review. Manually invoked; explanations are in Simplified Chinese.

## Install

Requires Node.js 22.20+ and Git. Follow the prompts to choose your coding agent and installation scope (current project or global):

```sh
npx skills add Kieran351/show-plan
```

## Update

Follow the prompts to choose the installation scope to update:

```sh
npx skills update show-plan
```

## Uninstall

Remove the global installation:

```sh
npx skills remove show-plan -g
```

For a project installation, run the command in that project directory without `-g`.
