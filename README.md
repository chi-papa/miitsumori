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

## 🔢 管理番号の自動採番・重複防止

以下の形式で連番生成。

- `EST-20260512-001`
- `INV-20260512-001`

管理番号の日付部分は **発行日と自動連動**。発行日を変更すると即座に反映されます。  
既存番号をスキップして **未使用の最小番号** を自動採番。  
保存時に重複が検出された場合は、該当書類をハイライト表示して上書き確認を行います。

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

- 発行日（管理番号の日付と連動）
- 有効期限
- 納期 / 納品日（自由入力）

---

## 🖨 A4プレビュー・PDF保存対応

ブラウザの印刷機能を利用してそのまま PDF 保存可能。

- A4 レイアウト最適化
- 印刷向けデザイン
- 編集 UI は印刷に映り込まない設計

**PDFファイル名の自動設定：**  
「印刷 / PDF保存」ボタンを押すと、ファイル名が `管理番号_会社名様` の形式で自動セットされます。

---

## 💾 書類の保存・管理

localStorage に保存。「📄 書類一覧」ボタンでモーダルを開いて管理できます。

- 複数書類の保存・管理
- 直近3件 / それ以前 に分けて一覧表示
- 書類種別アイコン（📋💴🧾📦）付き
- ワンクリックで呼び出し・再編集
- 削除はモーダル内インライン確認で操作

---

## 🏢 発行者情報の登録・自動入力

会社情報を一度登録すると、次回以降は自動で入力済みになります。  
発行日は都度変わるため、発行者情報には含まれません。

登録できる項目：

- 会社名・屋号
- 住所
- 電話番号
- 担当者名
- インボイス登録番号

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
3. 発行者情報を入力して「発行者情報を保存する」
4. 書類種別・発行日・宛先などを入力
5. 「A4プレビュー表示」で確認
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

## 🔢 Auto-Numbered Document IDs with Duplicate Prevention

Generates sequential IDs in formats like:

- `EST-20260512-001`
- `INV-20260512-001`

The date portion of the document ID **automatically syncs with the issue date** — change the date and the ID updates instantly.  
Skips already-used numbers and assigns the **lowest available sequence number**.  
If a duplicate is detected on save, the conflicting document is highlighted in the list with an inline overwrite confirmation.

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

- Issue date (synced to document ID)
- Expiry date
- Delivery date (free text)

---

## 🖨 A4 Preview & PDF Export

Uses the browser's built-in print function for PDF output.

- A4-optimized layout
- Print-ready design
- UI controls are excluded from print output

**Auto PDF filename:**  
Clicking "Print / Save as PDF" automatically sets the filename to `DocumentID_CompanyName様`.

---

## 💾 Document Storage & Management

Saved to `localStorage`. Open the **"📄 書類一覧" modal** to manage all saved documents.

- Save and manage multiple documents
- List split into "Recent (3)" and "Older"
- Document type icons (📋💴🧾📦)
- One-click load and re-edit
- Inline delete confirmation inside the modal

---

## 🏢 Issuer Info — Register Once, Auto-Fill Forever

Save your company information once and it will be automatically filled in on every new document.  
The issue date is intentionally excluded from saved issuer info as it changes each time.

Fields available:

- Company name
- Address
- Phone number
- Contact name
- Invoice registration number

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
3. Enter your company info and click "発行者情報を保存する"
4. Fill in document type, issue date, recipient, and line items
5. Click "A4 Preview" to review
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
