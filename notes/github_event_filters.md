# イベントのフィルタリング

## Filters

- paths
- paths-ignore
- branches
- branches-ignore
- tags
- tags-ignore

### フィルターの注意点

- 通常のフィルターと ignore フィルターは同時使用できない
- paths 系とそれ以外を同時に指定した場合、AND 条件（かつ）になる
  - OR ではないことに注意

## Glob

- `*` や `**`, `?+[]!` がサポートされている

## アクティビティタイプ

- pull_request なら opened, edited など
