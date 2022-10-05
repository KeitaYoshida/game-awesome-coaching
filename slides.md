---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

<img src="https://i.imgur.com/P29VpRq.png" class="mx-auto w-18"  />

<div class="mt-5">
  <span class="text-teal-400">LGym</span> <span class="text-gray-400 text-xs">with Game Awesome</span>
</div>
<div class="mb-5">
  <span class="text-teal-400 text-xs">概要・操作 MANUAL</span>
</div>

<div class="w-100 mx-auto">

```
what is a LGym
--------------
Over30向けフォートナイトコーチング
Over30系の大会、スクリムをメインにコーチング
LGメンバー同行+コーチングもあり
```

</div>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://le-game.fortnite-info.net/" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
      <img src="https://i.imgur.com/camnvEY.png" class="w-6" />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# コーチング機能 (試験運用中)

コーチャーのスケジュール・受講者の予約・実績情報を管理

- 📝 画面表示・遷移
- 🎨 スケジュールページ概要
- 🧑‍💻 予約・メッセージ (ログインユーザーのみ)
- 🤹 予約閲覧
- 🎥 **Recording** - built-in recording and camera view
- 📤 **Portable** - export into PDF, PNGs, or even a hostable SPA
- 🛠 **Hackable** - anything possible on a webpage

<br>
<br>

Read more about [Why Slidev?](https://sli.dev/guide/why)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image-right
image: https://i.imgur.com/KGlfe5X.png
---

# 画面表示・遷移

Game Awesome webサイト コーチングエリアより各コーチャーのカードを押下

<div class="abs-bl m-6 flex gap-2">
  <a href="https://le-game.fortnite-info.net/coach-awesome/495453037234749458/2022-10-05">Link</a>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image-right
image: https://i.imgur.com/uRf4YsJ.png
---

# スケジュールページ

対象コーチの月度スケジュールを表示

#### 機能
##### カレンダー(月度表示エリア)
```ts
・スケジュール予定のある日は日付の右上にドットマークが表示されます
(コーチング予定日は緑、講習会予定日はオレンジ色で表示)
・日付押下で各日程の詳細を表示
```
<br>

##### スケジュールカード
```ts
・選択された日付のスケジュール一覧が表示されます
・カード下部「参加申し込み」ボタンより申し込みが可能です
・予約が完了するとスケジュールカード左下部
 予約数アイコンのカウントが上がります
・予約数アイコン押下にて予約の詳細を閲覧できます
```

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image-right
image: https://i.imgur.com/jLXnqUr.png
---

# メッセージ機能

予約の確定・取り消しが行われるとメッセージが届きます
メッセージはGame Awesomeのページ（全ページ共通）左下部
メールアイコンにて確認できます。

また、メッセージが届いている際は左下のアイコンに未読メッセージ数が表示されます。

<div class="abs-bl m-6 flex gap-2">
  <a href="https://le-game.fortnite-info.net/coach-awesome/495453037234749458/2022-10-05">Link</a>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>