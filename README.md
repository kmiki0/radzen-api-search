# Radzen API 検索

Radzen.Blazor の API を、クラス名・コンポーネント名・メンバー名で検索できる 1 枚の HTML。

公開ページ: <https://kmiki0.github.io/radzen-api-search/>

外部への通信なしで動く 1 枚のファイルなので、`index.html` をダウンロードしてブラウザで直接開いても使える。説明文は日本語で、右上の「English」で原文に切り替えられる。

## 検索のしかた

- `Radzen` は省略できる（`DataGrid` → `RadzenDataGrid<TItem>`）
- 大文字の頭文字でも探せる（`rdg` → `RadzenDataGrid`、`dp` → `RadzenDatePicker`）
- `型名.メンバー名` でメンバーに直接飛べる（`DialogService.Open`、`DataGrid.AllowFiltering`）
- キーボード: `/` か `Ctrl+K` で検索欄、`↑` `↓` で結果を移動、`Enter` で開く、`Esc` で検索欄をクリア

## 出典とライセンス

Radzen Ltd とは関係のない、非公式のページ。API の情報と英語の説明文は Radzen.Blazor の `Radzen.Blazor.dll` と `Radzen.Blazor.xml` から作り、日本語の説明文はそれを AI で翻訳した。Radzen.Blazor のライセンス（MIT）は [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) と、`index.html` の先頭のコメントにある。

このリポジトリには生成済みの HTML だけを置いている。生成ツールは別のリポジトリで管理している。それ以外の部分にはライセンスを付けていない（著作権は作者が持つ）。
