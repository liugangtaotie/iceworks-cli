# `@iceworks/generate-project`

## 1.4.1

- support default def version

## 1.4.0

- remove `fs-readdir-recursive` use `glob`. Add ignore directories such as `node_modules`, `.rax`, `.ice` and `build`.

## 1.3.2

- remove `@iceworks/constant`, use `@appworks/constant`

## 1.3.1

- set `goldlog: false` of `@ali/build-plugin-event-tracking-register`

## 1.3.0

- add `@ali/build-plugin-event-tracking-register` and `@ali/universal-event-tracking`

## 1.2.4

- add `"builtInLibrary": { "lib-mtop": false }` to `src/app.json`

## 1.2.3

- add `mini.project.json` for ali (taobao) miniapp

## 1.2.2

- add `formatScaffoldToProject` method, which formats filename and formats to project

## 1.2.1

- add `pha` ejs option

## 1.2.0

- 升级 plugin-def 到 3.x

## 1.1.5

- chore: abc.json 存在时不再覆盖
- feat: 支持通过 `pkg.bizTeam` 定制生成逻辑

## 1.1.4

- chore: ejs ignore node_modules
