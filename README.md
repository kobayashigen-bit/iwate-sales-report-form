# 営業活動日報フォーム

GitHub Pagesで公開している営業活動日報フォームです。

## 自分でフォームを修正する

次の管理ページを開くと、岩手・長崎版／近畿1版のGitHub編集画面へ直接進めます。

- 管理ページ: https://kobayashigen-bit.github.io/iwate-sales-report-form/admin/
- 岩手・長崎の公開フォーム: https://kobayashigen-bit.github.io/iwate-sales-report-form/
- 近畿1の公開フォーム: https://kobayashigen-bit.github.io/iwate-sales-report-form/kinki1/

### 手順

1. 管理ページから対象フォームの「編集する」を押す
2. GitHubにログインする
3. `Ctrl + F` で変更したい文章を検索し、文字部分を修正する
4. 右上の **Commit changes...** を押す
5. **Commit directly to the main branch** を選んで保存する
6. 通常1〜3分後、同じGitHub Pages URLへ自動反映される

フォームはMarkdownではなくHTMLです。

- 岩手・長崎: `index.html`
- 近畿1: `kinki1/index.html`

HTMLタグ（`<...>`）やJavaScriptを削除するとフォームが動かなくなる場合があります。文章変更では、タグに囲まれた日本語部分だけを書き換えてください。誤って変更してもGitHubのコミット履歴から元に戻せます。

## 変更場所の区分

- フォームの文章・注釈・選択肢: GitHubのHTML
- スタッフ名: Googleスプレッドシート「担当者メール」シート（E列を〇）
- メール宛先・回答先シート・自動返信本文: Google Apps Script
