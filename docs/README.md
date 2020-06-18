---
title: すごいドキュメント
meta:
  - name: description
    content: すごい説明
---

# Hello VuePress

text text text text

text text text text

```typescript{6}
import Vue from 'vue'
import Component from 'vue-class-component'

@Component({})
export default class extends Vue {
  private highlight: boolean = true
}
```

[[toc]]

## Heading 1

### Heading 1-1

## Heading 2

### Heading 2-1

## Heading 3

## 絵文字変換
- :smile:
- :zipper_mouth_face:
- :thinking:
- :mask:

## カスタムブロック

::: tip
すごい
:::

::: warning
あぶない
:::

::: danger
やばい
:::

## コンポーネント

<MyComponent/>