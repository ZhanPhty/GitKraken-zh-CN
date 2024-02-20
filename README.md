# GitKraken-zh-CN

[GitKraken](https://www.gitkraken.com/) 简体中文补丁

## 翻译说明
- Pull -> 拉取
- Push -> 推送
- Repo -> 仓库
- Stage -> 暂存
- Stash -> 存档
- Blame -> 追责
- Rebase -> 变基

## 使用方法
- 至 [Release](https://github.com/ZhanPhty/GitKraken-zh-CN/releases) 下載 `strings.json`
- 替换文件
  - Windows: `%LOCALAPPDATA%\gitkraken\app-xxx\resources\app.asar.unpacked\src\strings.json`
  - Mac: `/Applications/GitKraken.app/Contents/Resources/app.asar.unpacked/src/strings.json`
  - Linux: `/usr/share/gitkraken/resources/app.asar.unpacked/src`
- 重启 GitKraken Preference -> UI Customization -> Language 切换语言

## 说明
尽量使用对应版本的中文补丁。版本不对应可能会存在翻译不完整的情况，但不会影响功能使用。
后续翻译都会根据官方对应的版本进行翻译（官方去掉的功能，翻译中也会去掉），所以高版本的翻译文件是不兼容低版本的。

## 翻译参考
- [GitKraken-zh-Simplified](https://github.com/qisumi/GitKraken-zh-Simplified)
- [GitKraken-zh-tw](https://github.com/rogeraabbccdd/GitKraken-zh-tw)
