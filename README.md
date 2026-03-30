# book_reading

技術書・ビジネス書の読書ノートを蓄積・管理するリポジトリ。AI支援（Claude Code）を活用して体系的にまとめ、副読書として活用する。

## 収録書籍

| 書籍 | 著者 | 章数 | 状態 |
|------|------|------|------|
| [The Software Engineer's Guidebook](the_software_engineers_guidebook/toc.md) | Gergely Orosz | 25章 | 読了 |
| [プロダクトマネージャーのしごと 第2版](product_managers_job/toc.md) | Matt LeMay | 16章 | 読了 |
| [Wardley Maps](wardley_maps/toc.md) | Simon Wardley | 19章 | 読了 |
| [サイバー攻撃 その瞬間 社長の決定](cyber-attack-book/README.md) | 関通サイバー攻撃対策室 | 9ファイル | 読了 |

全書籍の一覧と次の候補は [reading_list.md](reading_list.md) を参照。

## プロジェクト構造

```
book_reading/
├── README.md                     # このファイル
├── CLAUDE.md                     # Claude Code設定・筆者プロフィール
├── reading_list.md               # 読書リスト（読了・候補）
└── {書籍名}/
    ├── toc.md                    # 目次（各章summaryへのリンク + 原著リンク）
    ├── .gitignore                # PDF等のローカルファイル除外
    └── contents/
        └── chapter_XX/
            ├── summary.md        # 章全体のまとめ
            ├── note.md           # 筆者の考察・メモ（SRE/PFE/GTM視点）
            └── section_XX.md     # 各セクションの詳細（任意）
```

### ファイルの役割

| ファイル | 目的 |
|---------|------|
| `toc.md` | 書籍全体の目次。各章summaryへのリンク付き |
| `summary.md` | 章の体系的なサマリー。セクション別要約・チェックリスト・ポイント |
| `note.md` | 筆者個人の考察。SRE/PFE/AIOps/GTMエンジニアリングの文脈で読み替え |
| `section_XX.md` | セクション単位の詳細（書籍によっては省略） |

## 読書の視点

このリポジトリのnote.mdは、以下の視点で書かれている:

- **AIOps・GTMエンジニアリング**: AI時代のエンジニアリングとビジネスの接続
- **プラットフォームエンジニアリング**: 開発者体験・内部プラットフォームの設計と運営
- **経営者の片腕**: 技術をビジネス価値に翻訳し、意思決定を支援する立場
- **AI-Assisted多能工**: 足りないケイパビリティはAIで補完して横断的に成果を出す

## 使い方

1. 新しい書籍を追加する際は `CLAUDE.md` の手順に従う
2. `reading_list.md` に書籍情報を追加
3. AI支援でsummary.mdを生成し、読了後にnote.mdで考察を記録

## ライセンス

読書ノート自体はパブリックリポジトリとして公開。原著の著作権は各著者に帰属する。引用は適切な範囲で行い、ページ番号を添える。
