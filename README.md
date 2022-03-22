# renovate-config

Funteractive社内向けのRenovate[共有preset](https://docs.renovatebot.com/config-presets/)です。

## 使い方
`renovate.json`に下記を記載する

```json
{
  "extends": ["github>funteractive-inc/renovate-config"]
}
```

## 拡張例
[examples](https://github.com/funteractive-inc/renovate-config/blob/main/examples)に拡張例を載せています。

## preset 一覧

### [autoMergePinPatch](https://github.com/funteractive-inc/renovate-config/blob/main/automergePinPatch.json)
version固定およびpatch updateのPRを自動マージ

### [autoMergeTypesMinor](https://github.com/funteractive-inc/renovate-config/blob/main/automergeTypesMinor.json)
型定義のminor/patch updateを自動マージ

### [groupLinters](https://github.com/funteractive-inc/renovate-config/blob/main/groupLinters.json)

linter関連パッケージをグループ化
### [groupJest](https://github.com/funteractive-inc/renovate-config/blob/main/groupJest.json)

jest関連パッケージをグループ化
### [groupReact](https://github.com/funteractive-inc/renovate-config/blob/main/groupReact.json)

react関連パッケージをグループ化

### [labelMajor](https://github.com/funteractive-inc/renovate-config/blob/main/labelMajor.json)

major update PRに`major`ラベル付与

### [schedule](https://github.com/funteractive-inc/renovate-config/blob/main/schedule.json)

日本時間平日の 00:00 - 08:00, 20:00 - 24:00のみ稼働