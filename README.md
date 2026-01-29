# cw-sample-01-copy-to-lp｜原稿＋素材からLP制作（ポートフォリオ）

原稿（テキスト）と素材（ロゴ/イラスト）をもとに、サービス紹介の1ページLPを制作しました。  
第三者がURLを開くだけで確認できるよう、GitHub Pagesで公開しています。

- **デモURL**：https://aoiishikawa1818.github.io/cw-sample-01-copy-to-lp/

---

## 目次
- [概要](#概要)
- [デモ](#デモ)
- [主な機能・見どころ](#主な機能見どころ)
- [使用技術](#使用技術)
- [ディレクトリ構成](#ディレクトリ構成)
- [ローカル起動（動作確認）](#ローカル起動動作確認)
- [カスタマイズ方法（差し替えポイント）](#カスタマイズ方法差し替えポイント)
- [品質面で意識したこと](#品質面で意識したこと)
- [スクリーンショット](#スクリーンショット)
- [ライセンス](#ライセンス)

---

## 概要
クラウドワークス等の「**原稿＋素材あり → LPコーディング**」を想定したポートフォリオ作品です。  
読みやすい導線（Hero→課題→解決→機能→料金→FAQ→CTA）と、スマホ〜PCのレスポンシブ対応を意識しています。

---

## デモ
- 公開URL：**https://aoiishikawa1818.github.io/kanriflow-lp/**

---

## 主な機能・見どころ
- **1ページ完結のサービスLP**（構成：Hero / 課題 / 解決 / 機能 / 料金 / FAQ / CTA）
- **レスポンシブ対応**（スマホ375px〜PCで崩れにくいレイアウト）
- **セマンティックHTML**（header/main/section/footer、見出し階層）
- **アクセシビリティ配慮**（alt、フォーカス可視化等の基本）
- **差し替えやすい素材管理**（画像は `assets/` 配下に集約）

---

## 使用技術
- HTML / CSS / JavaScript（Vanilla）
- Git / GitHub
- GitHub Pages
- Chrome DevTools
- OpenAI Codex（叩き台作成 → 手動で調整・検証）

---

## ディレクトリ構成
```txt
kanriflow-lp/
  index.html
  styles.css
  script.js        # 使用していない場合は存在しないことがあります
  assets/
    (logo / icons / illustrations ...)
```
