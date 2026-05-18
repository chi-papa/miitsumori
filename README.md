# Mitsumori — 見積書・請求書・領収書・納品書メーカー

インストール不要。ブラウザで開くだけで使える、日本語対応のビジネス書類ジェネレーター。  
HTML / CSS / JavaScript のみで構築された、完全ローカル動作のシングルファイルアプリです。

---

# ✨ 特徴

## 📄 書類種別の切り替え

- 見積書
- 請求書
- 領収書
- 納品書

書類種別を切り替えるだけで、タイトル・ラベル・表示項目を自動変更。  
納品書では「納品日」表示・「以上」締めに自動対応。

---

## ⚡ インストール不要

`mitsumori.html` をブラウザで開くだけ。

- サーバー不要
- npm 不要
- ビルド不要
- 外部ライブラリ不要

完全オフライン動作。

---

## 🔢 管理番号の自動採番

以下の形式で連番生成。

- `EST-20260512-001`
- `INV-20260512-001`

既存番号を自動判定して次番号を生成。

---

## 🧾 インボイス制度対応

適格請求書発行事業者登録番号を記載可能。

---

## 💴 税込・税抜・非課税対応

- 税込
- 税抜（別途消費税）
- 非課税

を切り替え可能。消費税を自動計算。

---

## 🗓 カレンダー入力対応

- 発行日
- 有効期限
- 納期 / 納品日

すべてカレンダーピッカーからクリックで選択可能。

---

## 🖨 A4プレビュー・PDF保存対応

ブラウザの印刷機能を利用してそのまま PDF 保存可能。

- A4 レイアウト最適化
- 1枚 / 2枚モードの切り替え対応
- はみ出し検知・自動縮小印刷
- 編集 UI は印刷に映り込まない設計

### ページモード切り替え

プレビュー画面で **「1枚（A4×1）」「2枚（A4×2）」** を選択可能。  
明細が多い場合は 2枚モードを使用すると、前半・後半に自動分割されます。

---

## 💾 書類保存機能

localStorage に保存。

- 複数書類管理
- 保存済み一覧表示
- ワンクリック呼び出し
- 再編集対応

---

## 🏢 発行者情報の登録・自動入力

会社情報を一度登録すると、次回以降は自動で入力済みになります。

登録できる項目：

- 会社名・屋号
- 住所
- 電話番号
- 担当者名
- インボイス登録番号

「自社情報を登録」ボタンで保存。登録済みの場合は ✓ バッジを表示。  
新規作成時も登録済み情報を自動復元。

---

## 📦 明細・自由項目

- 明細行の追加
- 数量・単価の入力
- 自動金額計算
- 自由条件行の追加
- 備考欄

---

# 🚀 使い方

1. `mitsumori.html` をダウンロード
2. ブラウザで開く
3. 必要事項を入力
4. 「A4プレビュー表示」で確認
5. ページ設定（1枚 / 2枚）を選択
6. 「印刷 / PDF保存」で出力

---

# 🖥 動作環境

- Google Chrome（推奨）
- Microsoft Edge
- Firefox
- Safari

モダンブラウザ対応。Internet Explorer 非対応。

---

# 📁 ファイル構成

```
mitsumori.html
README.md
```

これだけで動作します。

---

# 💾 データ保存について

データはブラウザの `localStorage` に保存されます。

> ⚠️ ブラウザデータ削除時は保存内容も消えます。  
> 重要な書類は PDF 保存を推奨します。

---

# 📄 ライセンス

MIT License  
Copyright (c) 2026

---

# 🙏 クレジット

使用フォント（OS 標準フォント／外部読み込みなし）：

- Hiragino Kaku Gothic ProN
- Hiragino Sans
- Meiryo

---

# Mitsumori — Estimate, Invoice, Receipt & Delivery Note Generator

No installation required. Just open it in your browser.  
A Japanese-ready business document generator built with HTML / CSS / JavaScript only. Runs entirely offline as a single-file app.

---

# ✨ Features

## 📄 Multiple Document Types

- Estimate (見積書)
- Invoice (請求書)
- Receipt (領収書)
- Delivery Note (納品書)

Switching document type automatically updates the title, labels, and visible fields.  
Delivery notes include a dedicated delivery date field and close with the traditional "以上" end mark.

---

## ⚡ Zero Installation

Just open `mitsumori.html` in your browser.

- No server
- No npm
- No build step
- No external libraries

Fully offline.

---

## 🔢 Auto-Numbered Document IDs

Generates sequential IDs in formats like:

- `EST-20260512-001`
- `INV-20260512-001`

Automatically detects existing numbers and increments to the next.

---

## 🧾 Japanese Invoice (Qualified Invoice) Support

Supports entry of the Qualified Invoice Issuer registration number (インボイス登録番号).

---

## 💴 Tax Calculation Modes

- Tax-inclusive (税込)
- Tax-exclusive (税抜)
- Tax-exempt (非課税)

Consumption tax is calculated automatically.

---

## 🗓 Date Picker Support

- Issue date
- Expiry date
- Delivery date

All fields support click-to-select via the browser's native calendar picker.

---

## 🖨 A4 Preview & PDF Export

Uses the browser's built-in print function for PDF output.

- A4-optimized layout
- 1-page / 2-page mode toggle
- Overflow detection with auto-scaling
- UI controls are excluded from print output

### Page Mode

In the preview screen, select **"1 page (A4×1)"** or **"2 pages (A4×2)"**.  
In 2-page mode, line items are automatically split across two pages.

---

## 💾 Document Storage

Saved to `localStorage`.

- Manage multiple documents
- View saved document list
- One-click reload
- Re-edit anytime

---

## 🏢 Issuer Info — Register Once, Auto-Fill Forever

Save your company information once and it will be automatically filled in on every new document.

Fields available:

- Company name
- Address
- Phone number
- Contact name
- Invoice registration number

A ✓ badge is shown when saved info is in use. Auto-restored on new document creation.

---

## 📦 Line Items & Custom Fields

- Add / remove line item rows
- Enter quantity and unit price
- Automatic amount calculation
- Add custom condition rows
- Notes field

---

# 🚀 How to Use

1. Download `mitsumori.html`
2. Open it in your browser
3. Fill in the required fields
4. Click "A4 Preview" to review
5. Choose 1-page or 2-page mode
6. Click "Print / Save as PDF" to export

---

# 🖥 Browser Compatibility

- Google Chrome (recommended)
- Microsoft Edge
- Firefox
- Safari

Requires a modern browser. Internet Explorer is not supported.

---

# 📁 File Structure

```
mitsumori.html
README.md
```

That's all you need.

---

# 💾 About Data Storage

All data is stored in your browser's `localStorage`.

> ⚠️ Clearing browser data will also delete saved documents.  
> PDF export is recommended for important records.

---

# 📄 License

MIT License  
Copyright (c) 2026

---

# 🙏 Credits

Fonts (OS system fonts — no external loading):

- Hiragino Kaku Gothic ProN
- Hiragino Sans
- Meiryo
